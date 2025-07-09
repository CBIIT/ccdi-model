<link rel='stylesheet' href="assets/style.css">
<link rel='stylesheet' href="https://unpkg.com/leaflet@1.5.1/dist/leaflet.css" integrity="sha512-xwE/Az9zrjBIphAcBb3F6JVqxf46+CDLwfLMHloNu6KEQCAWi6HcDUbeOfBIptF7tcCzusKFjFw2yuvEpDL9wQ==" crossorigin="">
<script type="text/javascript" src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
<script type="text/javascript"  src="https://unpkg.com/leaflet@1.5.1/dist/leaflet.js"></script>
<script type="text/javascript" src="assets/actions.js"></script>

![Build Status](https://github.com/CBIIT/ccdi-model/actions/workflows/model-test-and-deploy.yml/badge.svg)

# Childhood Cancer Data Initiative Model

[View model on GitHub Pages](https://cbiit.github.io/ccdi-model/)



Zoom to Node: <select id="node_select">
  <option value="">Zoom to Node</option>
</select>
<div id="model"></div>

<p>
<a href="./model-desc/ccdi-model.svg">SVG file (in view above)</a>
<p>
<a href="./model-desc">Additional model files</a>
<div id='graph' style='display:off;'>
<svg width="3104pt" height="392pt"
 viewBox="0.00 0.00 3103.79 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3099.7901,-388 3099.7901,4 -4,4"/>
<!-- sequencing_file -->
<g id="node1" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="374.9954" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="374.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sample -->
<g id="node3" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="797.9954" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="797.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M398.4188,-348.554C415.2203,-337.0008 438.883,-322.6201 461.9954,-315 512.9559,-298.1984 662.6464,-287.0269 743.9508,-282.0182"/>
<polygon fill="#000000" stroke="#000000" points="744.2246,-285.5081 753.9945,-281.4094 743.8011,-278.521 744.2246,-285.5081"/>
<text text-anchor="middle" x="528.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- publication -->
<g id="node2" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="1078.9954" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="1078.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- study -->
<g id="node12" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1395.9954" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1395.9954" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge14" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1098.8984,-87.7696C1113.2496,-76.3153 1133.6088,-61.9642 1153.9954,-54 1188.778,-40.4119 1289.9407,-28.5068 1349.8919,-22.3828"/>
<polygon fill="#000000" stroke="#000000" points="1350.2631,-25.8632 1359.8621,-21.3788 1349.5617,-18.8984 1350.2631,-25.8632"/>
<text text-anchor="middle" x="1204.9954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- pdx -->
<g id="node11" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="726.9954" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="726.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge9" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M754.5665,-275.6466C710.6429,-271.2461 647.1281,-261.7663 631.9954,-243 613.0936,-219.5596 655.455,-205.4406 689.5524,-198.1837"/>
<polygon fill="#000000" stroke="#000000" points="690.6659,-201.531 699.792,-196.1492 689.3016,-194.6652 690.6659,-201.531"/>
<text text-anchor="middle" x="668.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- participant -->
<g id="node14" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1761.9954" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1761.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M839.6808,-272.8502C874.3256,-267.0947 924.6247,-257.2347 966.9954,-243 981.8848,-237.9978 983.7487,-231.7755 998.9954,-228 1064.776,-211.7111 1511.9569,-198.4828 1689.5308,-193.8124"/>
<polygon fill="#000000" stroke="#000000" points="1689.6577,-197.3104 1699.5628,-193.5501 1689.4747,-190.3128 1689.6577,-197.3104"/>
<text text-anchor="middle" x="1035.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node24" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="893.9954" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="893.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge10" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M793.6626,-260.9358C792.2074,-250.4138 792.3617,-237.4093 798.9954,-228 804.7597,-219.8239 824.0689,-211.8251 843.7872,-205.4518"/>
<polygon fill="#000000" stroke="#000000" points="844.9264,-208.763 853.4424,-202.46 842.8545,-202.0767 844.9264,-208.763"/>
<text text-anchor="middle" x="835.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- exposure -->
<g id="node4" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="2592.9954" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="2592.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2552.3696,-267.1284C2533.3022,-260.939 2510.5281,-252.6434 2490.9954,-243 2480.0523,-237.5974 2479.6011,-231.7743 2467.9954,-228 2409.0143,-208.8186 2002.9877,-197.4832 1834.7585,-193.5627"/>
<polygon fill="#000000" stroke="#000000" points="1834.5879,-190.058 1824.5098,-193.3262 1834.4264,-197.0561 1834.5879,-190.058"/>
<text text-anchor="middle" x="2534.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- methylation_array_file -->
<g id="node5" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="591.9954" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="591.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge28" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M593.864,-347.8818C595.972,-336.7934 600.4567,-323.2046 609.9954,-315 629.812,-297.955 696.2636,-288.2644 744.5535,-283.326"/>
<polygon fill="#000000" stroke="#000000" points="744.9491,-286.804 754.5591,-282.3433 744.2649,-279.8376 744.9491,-286.804"/>
<text text-anchor="middle" x="701.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- diagnosis -->
<g id="node6" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1431.9954" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1431.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge30" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1395.6382,-352.5329C1361.7916,-340.5975 1309.6864,-323.7462 1262.9954,-315 1243.0781,-311.2691 969.9111,-291.3555 851.7895,-282.8528"/>
<polygon fill="#000000" stroke="#000000" points="851.7546,-279.3413 841.5292,-282.1149 851.2524,-286.3233 851.7546,-279.3413"/>
<text text-anchor="middle" x="1368.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1435.6198,-347.8221C1441.3007,-324.1953 1454.6102,-283.3269 1481.9954,-261 1514.4231,-234.562 1623.8603,-213.234 1695.9276,-201.6131"/>
<polygon fill="#000000" stroke="#000000" points="1696.51,-205.0645 1705.8367,-200.0382 1695.4112,-198.1513 1696.51,-205.0645"/>
<text text-anchor="middle" x="1526.4954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- laboratory_test -->
<g id="node7" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1235.9954" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1235.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1184.6598,-351.8482C1166.3702,-346.0404 1145.8825,-338.6366 1127.9954,-330 1117.0054,-324.6936 1116.4707,-319.154 1104.9954,-315 1059.7544,-298.6232 927.2671,-287.5259 851.9541,-282.3471"/>
<polygon fill="#000000" stroke="#000000" points="851.9348,-278.8379 841.7216,-281.6557 851.4628,-285.822 851.9348,-278.8379"/>
<text text-anchor="middle" x="1193.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1253.3677,-347.9157C1261.3833,-337.3866 1267.4465,-324.3816 1258.9954,-315 1233.2737,-286.446 1112.7171,-325.554 1086.9954,-297 1076.2866,-285.1121 1076.5668,-273.1344 1086.9954,-261 1125.7494,-215.907 1523.2189,-199.0231 1689.4877,-193.9007"/>
<polygon fill="#000000" stroke="#000000" points="1689.7322,-197.395 1699.6218,-193.5943 1689.5206,-190.3982 1689.7322,-197.395"/>
<text text-anchor="middle" x="1152.4954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- treatment_response -->
<g id="node8" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1331.9954" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1331.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1316.9863,-261.1457C1309.8518,-250.4378 1304.536,-237.1648 1312.9954,-228 1325.5868,-214.3587 1566.5934,-201.1449 1690.1907,-195.2316"/>
<polygon fill="#000000" stroke="#000000" points="1690.5057,-198.7207 1700.3285,-194.7503 1690.1737,-191.7285 1690.5057,-198.7207"/>
<text text-anchor="middle" x="1395.9954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- study_admin -->
<g id="node9" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1229.9954" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1229.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge15" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1243.2284,-87.1697C1252.2167,-76.1962 1264.9853,-62.6272 1278.9954,-54 1301.0646,-40.4101 1328.6588,-31.5983 1351.5057,-26.0964"/>
<polygon fill="#000000" stroke="#000000" points="1352.3295,-29.4985 1361.3034,-23.8665 1350.776,-22.673 1352.3295,-29.4985"/>
<text text-anchor="middle" x="1335.4954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- study_funding -->
<g id="node10" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="1395.9954" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="1395.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge24" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1395.9954,-86.9735C1395.9954,-75.1918 1395.9954,-59.5607 1395.9954,-46.1581"/>
<polygon fill="#000000" stroke="#000000" points="1399.4955,-46.0033 1395.9954,-36.0034 1392.4955,-46.0034 1399.4955,-46.0033"/>
<text text-anchor="middle" x="1457.9954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M722.996,-210.2866C721.7463,-220.6321 721.9963,-233.3821 727.9954,-243 733.6954,-252.1384 742.5203,-259.0621 752.0057,-264.2686"/>
<polygon fill="#000000" stroke="#000000" points="750.6983,-267.5247 761.222,-268.7505 753.7597,-261.2296 750.6983,-267.5247"/>
<text text-anchor="middle" x="751.9954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge12" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M741.0351,-176.3308C762.4912,-153.3399 805.739,-110.6392 850.9954,-87 937.4806,-41.8253 1233.8773,-24.7848 1349.3857,-19.7639"/>
<polygon fill="#000000" stroke="#000000" points="1349.8202,-23.2487 1359.663,-19.3283 1349.5237,-16.255 1349.8202,-23.2487"/>
<text text-anchor="middle" x="874.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- cytogenomic_file -->
<g id="node13" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="814.9954" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="814.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M805.2238,-347.7992C802.7066,-342.2419 800.3322,-336.0086 798.9954,-330 797.3745,-322.7143 796.7124,-314.698 796.5536,-307.222"/>
<polygon fill="#000000" stroke="#000000" points="800.0539,-307.167 796.6167,-297.1452 793.0541,-307.1231 800.0539,-307.167"/>
<text text-anchor="middle" x="870.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- consent_group -->
<g id="node16" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1761.9954" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1761.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge26" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1761.9954,-173.9735C1761.9954,-162.1918 1761.9954,-146.5607 1761.9954,-133.1581"/>
<polygon fill="#000000" stroke="#000000" points="1765.4955,-133.0033 1761.9954,-123.0034 1758.4955,-133.0034 1765.4955,-133.0033"/>
<text text-anchor="middle" x="1812.4954" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_personnel -->
<g id="node15" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="1577.9954" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1577.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge13" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1563.1357,-87.0955C1553.12,-76.0924 1539.0294,-62.5183 1523.9954,-54 1498.2857,-39.4328 1466.2833,-30.4326 1440.7096,-25.0743"/>
<polygon fill="#000000" stroke="#000000" points="1441.3847,-21.6401 1430.8949,-23.1285 1440.0234,-28.5064 1441.3847,-21.6401"/>
<text text-anchor="middle" x="1612.4954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge36" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1741.5336,-87.3701C1727.0186,-75.8895 1706.5388,-61.6686 1685.9954,-54 1642.4814,-37.7567 1512.8596,-26.3327 1442.5651,-21.1436"/>
<polygon fill="#000000" stroke="#000000" points="1442.4551,-17.6266 1432.2281,-20.394 1441.9488,-24.6082 1442.4551,-17.6266"/>
<text text-anchor="middle" x="1778.4954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- synonym -->
<g id="node17" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="51.9954" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="51.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M80.6505,-350.75C104.8051,-338.7061 140.6657,-322.6912 173.9954,-315 281.5748,-290.1748 612.3933,-282.0697 743.5819,-279.7891"/>
<polygon fill="#000000" stroke="#000000" points="743.8532,-283.2851 753.7926,-279.6165 743.7348,-276.2861 743.8532,-283.2851"/>
<text text-anchor="middle" x="216.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge19" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M50.6634,-347.6807C49.4998,-330.0822 47.9954,-302.7386 47.9954,-279 47.9954,-279 47.9954,-279 47.9954,-105 47.9954,-38.3119 1112.4967,-21.4449 1349.5724,-18.5153"/>
<polygon fill="#000000" stroke="#000000" points="1349.6341,-22.015 1359.5909,-18.3938 1349.5491,-15.0155 1349.6341,-22.015"/>
<text text-anchor="middle" x="90.4954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M71.3544,-349.1705C85.5422,-337.749 105.7782,-323.2717 125.9954,-315 333.5433,-230.0831 399.9234,-250.933 622.9954,-228 728.4403,-217.1597 1455.5965,-199.2393 1689.6151,-193.6905"/>
<polygon fill="#000000" stroke="#000000" points="1689.8071,-197.187 1699.7214,-193.4513 1689.6414,-190.189 1689.8071,-197.187"/>
<text text-anchor="middle" x="329.4954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study_arm -->
<g id="node18" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="3035.9954" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="3035.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge23" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3017.581,-87.7281C3003.5362,-75.7715 2983.0735,-60.8265 2961.9954,-54 2888.03,-30.0449 1696.2558,-20.1586 1443.0512,-18.3233"/>
<polygon fill="#000000" stroke="#000000" points="1442.7523,-14.8212 1432.7274,-18.2492 1442.702,-21.821 1442.7523,-14.8212"/>
<text text-anchor="middle" x="3038.4954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- radiology_file -->
<g id="node19" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1652.9954" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1652.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1636.1948,-261.3902C1628.3819,-251.0294 1622.331,-238.0346 1629.9954,-228 1638.5723,-216.7707 1667.6866,-208.2034 1696.3969,-202.2492"/>
<polygon fill="#000000" stroke="#000000" points="1697.3694,-205.6248 1706.5009,-200.252 1696.012,-198.7576 1697.3694,-205.6248"/>
<text text-anchor="middle" x="1688.9954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- genetic_analysis -->
<g id="node20" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="1009.9954" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="1009.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M988.5077,-348.4078C972.4719,-335.5668 951.7223,-319.6297 941.9954,-315 912.9829,-301.1909 878.0712,-292.2933 849.8895,-286.7988"/>
<polygon fill="#000000" stroke="#000000" points="850.3066,-283.3163 839.8347,-284.9256 849.0245,-290.1979 850.3066,-283.3163"/>
<text text-anchor="middle" x="1033.9954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- survival -->
<g id="node21" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1933.9954" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1933.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1905.2065,-264.4382C1876.9181,-250.1295 1833.5153,-228.1758 1801.9045,-212.1866"/>
<polygon fill="#000000" stroke="#000000" points="1803.4171,-209.0295 1792.9139,-207.639 1800.2576,-215.2759 1803.4171,-209.0295"/>
<text text-anchor="middle" x="1897.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- family_relationship -->
<g id="node22" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="2099.9954" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="2099.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2054.471,-262.9001C2022.8916,-252.1024 1979.7129,-238.0691 1940.9954,-228 1903.1612,-218.1607 1860.238,-209.4466 1825.9095,-203.0572"/>
<polygon fill="#000000" stroke="#000000" points="1826.4764,-199.6028 1816.008,-201.2341 1825.2089,-206.4871 1826.4764,-199.6028"/>
<text text-anchor="middle" x="2068.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- clinical_measure_file -->
<g id="node23" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="2781.9954" cy="-279" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="2781.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge33" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2783.5808,-260.6337C2783.4737,-249.7332 2781.3417,-236.4375 2772.9954,-228 2478.1953,70.0224 2261.5057,-109.4585 1845.9954,-54 1699.3811,-34.4313 1524.3699,-24.1497 1442.5144,-20.0974"/>
<polygon fill="#000000" stroke="#000000" points="1442.4561,-16.5905 1432.2977,-19.6002 1442.1157,-23.5823 1442.4561,-16.5905"/>
<text text-anchor="middle" x="2771.9954" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2693.9473,-268.4163C2663.7497,-262.9894 2630.2186,-254.914 2600.9954,-243 2589.6944,-238.3927 2589.614,-231.7345 2577.9954,-228 2508.393,-205.628 2021.391,-195.9385 1834.6476,-193.0163"/>
<polygon fill="#000000" stroke="#000000" points="1834.4359,-189.5127 1824.383,-192.8578 1834.3278,-196.5119 1834.4359,-189.5127"/>
<text text-anchor="middle" x="2686.9954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge38" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M889.5468,-210.3155C886.1933,-220.9265 880.6554,-233.9365 871.9954,-243 863.8274,-251.5486 853.207,-258.3323 842.5733,-263.5988"/>
<polygon fill="#000000" stroke="#000000" points="840.9271,-260.5029 833.2866,-267.8427 843.8366,-266.8696 840.9271,-260.5029"/>
<text text-anchor="middle" x="922.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge37" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M894.0574,-173.7308C895.1939,-150.003 900.9518,-109.0231 925.9954,-87 957.6002,-59.2071 1237.631,-31.8664 1349.8171,-21.9275"/>
<polygon fill="#000000" stroke="#000000" points="1350.1655,-25.4105 1359.8205,-21.0481 1349.5524,-18.4374 1350.1655,-25.4105"/>
<text text-anchor="middle" x="966.4954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- pathology_file -->
<g id="node25" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="197.9954" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="197.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge35" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M225.3825,-349.1074C245.9365,-337.3394 275.203,-322.4642 302.9954,-315 384.719,-293.0517 632.4261,-283.5909 743.3101,-280.3759"/>
<polygon fill="#000000" stroke="#000000" points="743.7067,-283.8661 753.6035,-280.084 743.5083,-276.8689 743.7067,-283.8661"/>
<text text-anchor="middle" x="363.9954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- medical_history -->
<g id="node26" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2302.9954" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2302.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2263.9603,-263.0009C2233.8793,-251.3664 2190.9743,-236.2625 2151.9954,-228 2093.0303,-215.5009 1928.6884,-203.0481 1833.2051,-196.5721"/>
<polygon fill="#000000" stroke="#000000" points="1833.2629,-193.0682 1823.0503,-195.8883 1832.7925,-200.0523 1833.2629,-193.0682"/>
<text text-anchor="middle" x="2273.9954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- treatment -->
<g id="node27" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="2463.9954" cy="-279" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="2463.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2426.8179,-265.2008C2410.4409,-258.8485 2391.0789,-250.9626 2373.9954,-243 2361.1994,-237.0358 2359.5761,-231.8565 2345.9954,-228 2251.9492,-201.2936 1969.166,-194.3955 1834.6357,-192.6166"/>
<polygon fill="#000000" stroke="#000000" points="1834.4726,-189.1144 1824.4291,-192.4877 1834.3841,-196.1138 1834.4726,-189.1144"/>
<text text-anchor="middle" x="2420.9954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- generic_file -->
<g id="node28" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="1761.9954" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="1761.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1706.9285,-356.1751C1639.0012,-344.4458 1519.8799,-325.1454 1416.9954,-315 1257.127,-299.2355 1216.3526,-306.5907 1055.9954,-297 985.4032,-292.778 904.016,-286.9378 851.8369,-283.0686"/>
<polygon fill="#000000" stroke="#000000" points="852.0345,-279.5737 841.8023,-282.3221 851.5151,-286.5544 852.0345,-279.5737"/>
<text text-anchor="middle" x="1583.9954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge3" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1827.8746,-364.6437C2077.0739,-359.0863 2947.9954,-335.6141 2947.9954,-279 2947.9954,-279 2947.9954,-279 2947.9954,-105 2947.9954,-27.6005 1701.2798,-19.0556 1442.6309,-18.1157"/>
<polygon fill="#000000" stroke="#000000" points="1442.4627,-14.6152 1432.4507,-18.0808 1442.4386,-21.6152 1442.4627,-14.6152"/>
<text text-anchor="middle" x="3000.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1761.9954,-347.7078C1761.9954,-317.3436 1761.9954,-256.3226 1761.9954,-220.3464"/>
<polygon fill="#000000" stroke="#000000" points="1765.4955,-220.0471 1761.9954,-210.0471 1758.4955,-220.0471 1765.4955,-220.0471"/>
<text text-anchor="middle" x="1814.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
</g>
</svg>
</div>
