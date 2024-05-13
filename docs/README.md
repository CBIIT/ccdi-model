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
<svg width="2598pt" height="305pt"
 viewBox="0.00 0.00 2597.68 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 2593.6778,-301 2593.6778,4 -4,4"/>
<!-- radiology_file -->
<g id="node1" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1632.7947" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1632.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- participant -->
<g id="node24" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1553.7947" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1553.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1627.9727,-174.0221C1624.4868,-163.5307 1618.9408,-150.5281 1610.7947,-141 1606.0363,-135.4344 1600.1994,-130.439 1594.0953,-126.0675"/>
<polygon fill="#000000" stroke="#000000" points="1595.9527,-123.0997 1585.6822,-120.4982 1592.0887,-128.9367 1595.9527,-123.0997"/>
<text text-anchor="middle" x="1678.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- sequencing_file -->
<g id="node2" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="855.7947" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="855.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sample -->
<g id="node23" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="664.7947" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="664.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M843.9117,-261.164C835.452,-249.8978 823.0802,-236.0046 808.7947,-228 772.828,-207.8469 757.6228,-220.6523 717.7947,-210 714.4548,-209.1067 711.0195,-208.114 707.5799,-207.0669"/>
<polygon fill="#000000" stroke="#000000" points="708.5409,-203.6999 697.9506,-204.0087 706.422,-210.3715 708.5409,-203.6999"/>
<text text-anchor="middle" x="895.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- methylation_array_file -->
<g id="node3" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="270.7947" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="270.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M286.8014,-260.9818C298.1448,-249.4853 314.391,-235.3996 331.7947,-228 380.6755,-207.2171 529.3728,-197.7633 610.532,-194.053"/>
<polygon fill="#000000" stroke="#000000" points="610.7267,-197.5479 620.5617,-193.608 610.4164,-190.5547 610.7267,-197.5479"/>
<text text-anchor="middle" x="423.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study -->
<g id="node4" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="749.7947" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="749.7947" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_arm -->
<g id="node5" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="59.7947" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="59.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge27" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M83.931,-88.2342C102.4183,-76.3659 129.0431,-61.3091 154.7947,-54 206.9552,-39.1952 572.4753,-24.5035 703.3338,-19.6618"/>
<polygon fill="#000000" stroke="#000000" points="703.5734,-23.1554 713.438,-19.2903 703.3162,-16.1601 703.5734,-23.1554"/>
<text text-anchor="middle" x="203.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- publication -->
<g id="node6" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="200.7947" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="200.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge18" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M223.0743,-88.0941C239.8997,-76.3194 264.0732,-61.4418 287.7947,-54 364.2506,-30.0147 601.454,-21.5593 702.9485,-18.988"/>
<polygon fill="#000000" stroke="#000000" points="703.2897,-22.4808 713.2009,-18.7367 703.1181,-15.4829 703.2897,-22.4808"/>
<text text-anchor="middle" x="338.7947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- study_personnel -->
<g id="node7" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="368.7947" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="368.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge30" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M379.1121,-86.7573C386.6178,-75.3195 397.8842,-61.3877 411.7947,-54 461.1125,-27.8081 622.2355,-20.6672 702.9022,-18.7241"/>
<polygon fill="#000000" stroke="#000000" points="703.3443,-22.2152 713.2636,-18.4926 703.1879,-15.2169 703.3443,-22.2152"/>
<text text-anchor="middle" x="481.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- study_funding -->
<g id="node8" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="550.7947" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="550.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge24" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M550.4168,-86.5472C551.2131,-75.6141 554.1328,-62.3146 562.7947,-54 582.5012,-35.0835 654.6825,-25.5881 703.3834,-21.2331"/>
<polygon fill="#000000" stroke="#000000" points="703.7252,-24.7168 713.3919,-20.3803 703.1308,-17.742 703.7252,-24.7168"/>
<text text-anchor="middle" x="624.7947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- exposure -->
<g id="node9" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1777.7947" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1777.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1769.6459,-174.1523C1763.5685,-162.8813 1754.1826,-148.9869 1741.7947,-141 1722.2551,-128.4021 1667.9147,-118.8211 1622.6515,-112.7225"/>
<polygon fill="#000000" stroke="#000000" points="1622.9266,-109.2287 1612.5564,-111.3987 1622.0164,-116.1692 1622.9266,-109.2287"/>
<text text-anchor="middle" x="1800.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- clinical_measure_file -->
<g id="node10" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="1053.7947" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="1053.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge7" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M984.8103,-177.9974C967.3817,-172.6977 949.244,-165.5482 933.7947,-156 880.8383,-123.2712 889.1045,-89.2542 837.7947,-54 823.6212,-44.2616 806.4098,-36.4873 790.9805,-30.6914"/>
<polygon fill="#000000" stroke="#000000" points="791.7429,-27.2467 781.1484,-27.1676 789.3812,-33.8363 791.7429,-27.2467"/>
<text text-anchor="middle" x="982.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1082.7102,-174.5941C1092.3202,-168.7463 1103.0526,-162.147 1112.7947,-156 1123.1159,-149.4876 1124.2567,-144.9766 1135.7947,-141 1167.6395,-130.0245 1371.6995,-116.1146 1482.4772,-109.241"/>
<polygon fill="#000000" stroke="#000000" points="1482.8059,-112.7275 1492.5714,-108.6182 1482.3748,-105.7408 1482.8059,-112.7275"/>
<text text-anchor="middle" x="1221.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- pathology_file -->
<g id="node11" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="480.7947" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="480.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M497.0126,-261.1584C507.8728,-250.1804 523.0249,-236.6107 538.7947,-228 562.0321,-215.3119 590.1806,-206.7201 613.9732,-201.1223"/>
<polygon fill="#000000" stroke="#000000" points="614.8835,-204.5052 623.8763,-198.9034 613.353,-197.6746 614.8835,-204.5052"/>
<text text-anchor="middle" x="599.7947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- diagnosis -->
<g id="node12" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1105.7947" cy="-279" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1105.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1060.9869,-268.5248C1038.4644,-262.4679 1011.0812,-253.8779 987.7947,-243 976.7376,-237.8349 976.3586,-231.9006 964.7947,-228 860.4992,-192.8203 825.6679,-231.8752 717.7947,-210 714.1519,-209.2613 710.4144,-208.3415 706.692,-207.3112"/>
<polygon fill="#000000" stroke="#000000" points="707.5332,-203.9093 696.9486,-204.3744 705.5131,-210.6115 707.5332,-203.9093"/>
<text text-anchor="middle" x="1032.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1147.6395,-267.3379C1161.0251,-261.8319 1174.9172,-253.9823 1184.7947,-243 1206.4113,-218.9655 1183.3556,-195.1582 1207.7947,-174 1241.936,-144.442 1263.4594,-164.5844 1307.7947,-156 1371.2917,-143.7055 1443.7656,-128.5426 1493.5128,-117.9593"/>
<polygon fill="#000000" stroke="#000000" points="1494.4097,-121.3468 1503.4606,-115.8395 1492.9508,-114.5005 1494.4097,-121.3468"/>
<text text-anchor="middle" x="1252.2947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- medical_history -->
<g id="node13" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1933.7947" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1933.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1910.6348,-174.6578C1894.0238,-163.1522 1870.6324,-148.7857 1847.7947,-141 1807.8169,-127.371 1698.0857,-116.4095 1624.5833,-110.3042"/>
<polygon fill="#000000" stroke="#000000" points="1624.7156,-106.8034 1614.4632,-109.4751 1624.144,-113.78 1624.7156,-106.8034"/>
<text text-anchor="middle" x="1947.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- survival -->
<g id="node14" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="2205.7947" cy="-192" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="2205.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2175.539,-177.8635C2148.2698,-165.8245 2106.7469,-149.2115 2068.7947,-141 1986.5475,-123.2047 1747.8729,-112.1462 1626.5026,-107.516"/>
<polygon fill="#000000" stroke="#000000" points="1626.3208,-104.0067 1616.1961,-107.1275 1626.0571,-111.0018 1626.3208,-104.0067"/>
<text text-anchor="middle" x="2158.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- molecular_test -->
<g id="node15" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="2351.7947" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="2351.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2314.3471,-176.0797C2284.4626,-164.1606 2241.218,-148.6481 2201.7947,-141 2093.4383,-119.979 1771.3906,-110.0478 1626.2041,-106.5443"/>
<polygon fill="#000000" stroke="#000000" points="1626.1421,-103.0419 1616.0617,-106.3031 1625.9757,-110.0399 1626.1421,-103.0419"/>
<text text-anchor="middle" x="2319.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- synonym -->
<g id="node16" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2054.7947" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2054.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge3" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2106.8694,-277.6295C2202.184,-273.9047 2398.7909,-260.1781 2440.7947,-210 2451.0649,-197.7312 2448.5629,-187.9877 2440.7947,-174 2367.8423,-42.6389 3254.944,-190.0938 1359.7947,-54 1149.7781,-38.9184 898.7498,-25.5831 796.5402,-20.3517"/>
<polygon fill="#000000" stroke="#000000" points="796.4218,-16.8412 786.2564,-19.827 796.0651,-23.8321 796.4218,-16.8412"/>
<text text-anchor="middle" x="2486.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2003.3682,-276.2819C1857.9369,-268.603 1431.2531,-246.1281 1076.7947,-228 917.2472,-219.8402 874.7134,-239.975 717.7947,-210 714.1437,-209.3026 710.4006,-208.4117 706.6743,-207.4008"/>
<polygon fill="#000000" stroke="#000000" points="707.508,-203.9972 696.9249,-204.4949 705.5085,-210.7056 707.508,-203.9972"/>
<text text-anchor="middle" x="1388.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2056.2435,-260.8159C2057.5307,-230.6812 2055.1534,-170.7675 2019.7947,-141 1990.4361,-116.2838 1749.9829,-108.4378 1626.462,-106.0259"/>
<polygon fill="#000000" stroke="#000000" points="1626.3933,-102.5241 1616.3291,-105.8351 1626.2614,-109.5228 1626.3933,-102.5241"/>
<text text-anchor="middle" x="2095.2947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- cell_line -->
<g id="node17" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="695.7947" cy="-105" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="695.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge11" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M691.2515,-86.9787C689.6538,-76.7216 689.4038,-63.9716 694.7947,-54 698.9687,-46.2793 705.5985,-39.9485 712.8319,-34.8693"/>
<polygon fill="#000000" stroke="#000000" points="714.8543,-37.733 721.4896,-29.4733 711.1517,-31.7924 714.8543,-37.733"/>
<text text-anchor="middle" x="735.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M658.1237,-116.8643C651.0584,-118.9838 643.7178,-121.115 636.7947,-123 603.7189,-132.0057 583.0182,-114.0802 561.7947,-141 543.9729,-163.6051 578.9443,-176.9286 612.8687,-184.2529"/>
<polygon fill="#000000" stroke="#000000" points="612.3398,-187.7164 622.8326,-186.2497 613.7153,-180.8529 612.3398,-187.7164"/>
<text text-anchor="middle" x="602.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cytogenomic_file -->
<g id="node18" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="664.7947" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="664.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M664.7947,-260.9735C664.7947,-249.1918 664.7947,-233.5607 664.7947,-220.1581"/>
<polygon fill="#000000" stroke="#000000" points="668.2948,-220.0033 664.7947,-210.0034 661.2948,-220.0034 668.2948,-220.0033"/>
<text text-anchor="middle" x="736.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- study_admin -->
<g id="node19" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1179.7947" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1179.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge4" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1126.0383,-93.3961C1115.9912,-91.2513 1105.576,-89.0442 1095.7947,-87 1023.87,-71.9685 1005.8509,-68.3878 933.7947,-54 885.9446,-44.4455 831.0413,-33.7365 793.7527,-26.5013"/>
<polygon fill="#000000" stroke="#000000" points="794.2064,-23.0242 783.723,-24.5565 792.8739,-29.8962 794.2064,-23.0242"/>
<text text-anchor="middle" x="1063.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- pdx -->
<g id="node20" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="790.7947" cy="-105" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="790.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge15" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M789.0347,-86.8388C787.5386,-76.7737 784.7957,-64.2588 779.7947,-54 777.8696,-50.051 775.4218,-46.1661 772.7575,-42.4941"/>
<polygon fill="#000000" stroke="#000000" points="775.2618,-40.0206 766.2919,-34.3822 769.7879,-44.3837 775.2618,-40.0206"/>
<text text-anchor="middle" x="809.7947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M769.2661,-116.5943C764.285,-118.9594 758.9355,-121.2548 753.7947,-123 715.9927,-135.833 691.3386,-110.3212 665.7947,-141 660.5354,-147.3165 658.9582,-155.7564 659.0845,-163.9499"/>
<polygon fill="#000000" stroke="#000000" points="655.609,-164.3789 660.0065,-174.018 662.5799,-163.7404 655.609,-164.3789"/>
<text text-anchor="middle" x="689.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- family_relationship -->
<g id="node21" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="826.7947" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="826.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M865.3648,-175.2478C898.0933,-161.1598 941.092,-142.9975 949.7947,-141 1083.8742,-110.2247 1121.4725,-131.1892 1258.7947,-123 1335.2959,-118.4379 1422.9471,-113.072 1482.6969,-109.3932"/>
<polygon fill="#000000" stroke="#000000" points="1483.0132,-112.8805 1492.779,-108.7722 1482.5827,-105.8937 1483.0132,-112.8805"/>
<text text-anchor="middle" x="1029.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- therapeutic_procedure -->
<g id="node22" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="1423.7947" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="1423.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1417.2371,-173.7521C1414.6702,-163.165 1413.7871,-150.1565 1420.7947,-141 1429.4429,-129.6997 1458.7782,-121.1274 1487.7047,-115.1882"/>
<polygon fill="#000000" stroke="#000000" points="1488.7425,-118.5516 1497.8847,-113.1971 1487.3988,-111.6818 1488.7425,-118.5516"/>
<text text-anchor="middle" x="1513.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge20" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M620.6765,-189.6456C571.9848,-186.016 498.1735,-177.1085 480.7947,-156 476.5573,-150.8532 476.359,-145.9769 480.7947,-141 504.0131,-114.9485 602.6323,-130.1208 636.7947,-123 640.9227,-122.1396 645.1766,-121.118 649.4201,-120.0052"/>
<polygon fill="#000000" stroke="#000000" points="650.541,-123.3264 659.2383,-117.276 648.6662,-116.5821 650.541,-123.3264"/>
<text text-anchor="middle" x="517.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge19" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M686.7397,-176.2132C700.9444,-166.0548 719.8785,-152.6264 736.7947,-141 745.2026,-135.2213 754.4183,-129.0267 762.8185,-123.4334"/>
<polygon fill="#000000" stroke="#000000" points="764.8125,-126.3108 771.2092,-117.8649 760.9418,-120.4783 764.8125,-126.3108"/>
<text text-anchor="middle" x="773.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M697.9477,-179.9805C704.4786,-177.8288 711.3155,-175.7257 717.7947,-174 758.0552,-163.2766 770.6587,-170.2926 809.7947,-156 822.6892,-151.2909 823.5825,-144.7259 836.7947,-141 927.1343,-115.5241 1165.0575,-127.8585 1258.7947,-123 1335.329,-119.0331 1422.9747,-113.568 1482.7142,-109.7031"/>
<polygon fill="#000000" stroke="#000000" points="1483.0421,-113.1893 1492.7945,-109.049 1482.5888,-106.204 1483.0421,-113.1893"/>
<text text-anchor="middle" x="873.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge28" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1496.459,-97.7914C1414.0726,-87.5262 1257.4032,-68.3519 1123.7947,-54 1005.8113,-41.3265 866.656,-28.4865 795.9927,-22.116"/>
<polygon fill="#000000" stroke="#000000" points="795.9372,-18.597 785.6638,-21.187 795.3101,-25.5688 795.9372,-18.597"/>
<text text-anchor="middle" x="1305.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
</g>
</svg>
</div>
