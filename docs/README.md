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
<svg width="2883pt" height="305pt"
 viewBox="0.00 0.00 2882.69 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 2878.6897,-301 2878.6897,4 -4,4"/>
<!-- pathology_file -->
<g id="node1" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="707.6897" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="707.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- sample -->
<g id="node8" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="689.6897" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="689.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M697.3077,-260.8593C694.6331,-255.3037 692.1103,-249.0563 690.6897,-243 688.9853,-235.7334 688.2948,-227.7236 688.1352,-220.2477"/>
<polygon fill="#000000" stroke="#000000" points="691.6357,-220.1943 688.213,-210.1676 684.6359,-220.1403 691.6357,-220.1943"/>
<text text-anchor="middle" x="751.6897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- methylation_array_file -->
<g id="node2" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="115.6897" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="115.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M132.9292,-261.0206C145.2979,-249.384 163.018,-235.1203 181.6897,-228 223.231,-212.1586 513.091,-198.9868 635.4205,-194.0688"/>
<polygon fill="#000000" stroke="#000000" points="635.8267,-197.5555 645.6794,-193.66 635.5479,-190.5611 635.8267,-197.5555"/>
<text text-anchor="middle" x="273.1897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- participant -->
<g id="node3" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1758.6897" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1758.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- study -->
<g id="node14" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1225.6897" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1225.6897" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge32" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1738.9749,-87.8311C1724.2523,-76.0898 1703.0644,-61.3666 1681.6897,-54 1607.0013,-28.2594 1372.9756,-20.7846 1272.3941,-18.7316"/>
<polygon fill="#000000" stroke="#000000" points="1272.2963,-15.2291 1262.23,-18.5334 1272.1598,-22.2278 1272.2963,-15.2291"/>
<text text-anchor="middle" x="1761.1897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_personnel -->
<g id="node4" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="774.6897" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="774.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge15" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M779.7888,-86.8258C783.9925,-75.4168 791.1751,-61.4915 802.6897,-54 833.6733,-33.8418 1075.8542,-23.1699 1179.2031,-19.4956"/>
<polygon fill="#000000" stroke="#000000" points="1179.4739,-22.9884 1189.3457,-19.1417 1179.2297,-15.9926 1179.4739,-22.9884"/>
<text text-anchor="middle" x="872.1897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- treatment -->
<g id="node5" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="1947.6897" cy="-192" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="1947.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1915.1995,-177.0442C1883.7494,-162.5671 1835.8935,-140.5382 1801.3811,-124.6516"/>
<polygon fill="#000000" stroke="#000000" points="1802.5728,-121.3472 1792.0254,-120.345 1799.6457,-127.7058 1802.5728,-121.3472"/>
<text text-anchor="middle" x="1910.6897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- medical_history -->
<g id="node6" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2108.6897" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2108.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2068.3512,-176.0637C2039.1099,-164.9915 1998.4185,-150.5637 1961.6897,-141 1916.9205,-129.3427 1865.6121,-120.2799 1825.7793,-114.1634"/>
<polygon fill="#000000" stroke="#000000" points="1826.0605,-110.6662 1815.6499,-112.6332 1825.0149,-117.5877 1826.0605,-110.6662"/>
<text text-anchor="middle" x="2078.6897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- survival -->
<g id="node7" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="2259.6897" cy="-192" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="2259.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2233.7944,-176.7457C2212.3022,-164.8688 2180.5346,-149.0867 2150.6897,-141 2092.2165,-125.1561 1926.7259,-113.9913 1830.4898,-108.6235"/>
<polygon fill="#000000" stroke="#000000" points="1830.4318,-105.1151 1820.2545,-108.0599 1830.0469,-112.1045 1830.4318,-105.1151"/>
<text text-anchor="middle" x="2230.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M733.4074,-189.2184C775.0747,-185.4101 838.9517,-176.5188 890.6897,-156 902.0342,-151.5009 902.0329,-144.6134 913.6897,-141 995.7497,-115.5626 1601.5492,-134.4889 1686.6897,-123 1692.4976,-122.2163 1698.5146,-121.1428 1704.483,-119.9074"/>
<polygon fill="#000000" stroke="#000000" points="1705.4323,-123.2819 1714.436,-117.6977 1703.9151,-116.4483 1705.4323,-123.2819"/>
<text text-anchor="middle" x="950.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node22" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="928.6897" cy="-105" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="928.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge18" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M693.4394,-174.0029C696.7804,-162.6688 702.8781,-148.7603 713.6897,-141 742.2189,-120.5226 836.3259,-130.2359 870.6897,-123 874.5828,-122.1803 878.5883,-121.2111 882.5886,-120.1544"/>
<polygon fill="#000000" stroke="#000000" points="883.7738,-123.457 892.4543,-117.3825 881.8803,-116.7179 883.7738,-123.457"/>
<text text-anchor="middle" x="750.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node24" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="641.6897" cy="-105" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="641.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge16" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M646.896,-187.0216C609.3817,-181.6725 558.9658,-171.7496 546.6897,-156 528.2301,-132.3173 570.2017,-118.2899 604.1211,-111.1162"/>
<polygon fill="#000000" stroke="#000000" points="605.1793,-114.4751 614.3135,-109.1068 603.8253,-107.6072 605.1793,-114.4751"/>
<text text-anchor="middle" x="583.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- synonym -->
<g id="node9" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1071.6897" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1071.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1123.5681,-277.2118C1275.5292,-271.5074 1711.9686,-251.6233 1759.6897,-210 1783.2072,-189.4876 1778.4437,-171.6711 1772.6897,-141 1772.1565,-138.1576 1771.4056,-135.2513 1770.5256,-132.3832"/>
<polygon fill="#000000" stroke="#000000" points="1773.8118,-131.1779 1767.1644,-122.9279 1767.2161,-133.5226 1773.8118,-131.1779"/>
<text text-anchor="middle" x="1819.1897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1035.599,-265.9327C995.0397,-251.277 934.1062,-229.3602 928.6897,-228 865.8082,-212.2085 791.7692,-202.3651 742.9473,-197.0422"/>
<polygon fill="#000000" stroke="#000000" points="743.2396,-193.5537 732.9251,-195.9745 742.498,-200.5143 743.2396,-193.5537"/>
<text text-anchor="middle" x="1012.1897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge28" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1066.1387,-261.0392C1056.0865,-224.7593 1039.0325,-141.5554 1074.6897,-87 1098.0838,-51.2072 1145.0747,-33.7265 1180.4566,-25.3543"/>
<polygon fill="#000000" stroke="#000000" points="1181.5462,-28.6984 1190.5612,-23.1323 1180.0429,-21.8617 1181.5462,-28.6984"/>
<text text-anchor="middle" x="1097.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- treatment_response -->
<g id="node10" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="2430.6897" cy="-192" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="2430.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2389.1122,-175.4086C2357.8837,-163.7103 2313.7788,-148.7906 2273.6897,-141 2190.9778,-124.9265 1951.9599,-113.0443 1830.8514,-107.8672"/>
<polygon fill="#000000" stroke="#000000" points="1830.7085,-104.3581 1820.5693,-107.4316 1830.4122,-111.3518 1830.7085,-104.3581"/>
<text text-anchor="middle" x="2413.6897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- clinical_measure_file -->
<g id="node11" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="2699.6897" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="2699.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2636.5072,-177.3288C2610.2062,-171.0408 2579.3995,-163.4406 2551.6897,-156 2528.8713,-149.8728 2523.9867,-144.9335 2500.6897,-141 2373.5288,-119.5298 1992.2321,-109.6349 1831.4558,-106.3327"/>
<polygon fill="#000000" stroke="#000000" points="1831.2586,-102.8281 1821.1897,-106.1247 1831.1167,-109.8266 1831.2586,-102.8281"/>
<text text-anchor="middle" x="2637.6897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge2" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2717.6262,-173.9395C2725.9226,-163.4189 2732.2453,-150.4145 2723.6897,-141 2587.3645,9.0116 2017.7716,-69.8417 1815.6897,-54 1613.3755,-38.1401 1371.567,-25.3013 1272.0025,-20.2799"/>
<polygon fill="#000000" stroke="#000000" points="1272.1374,-16.7823 1261.9744,-19.7764 1271.7863,-23.7735 1272.1374,-16.7823"/>
<text text-anchor="middle" x="2788.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- publication -->
<g id="node12" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="1146.6897" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="1146.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge3" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1156.7861,-87.03C1162.9849,-76.79 1171.4849,-64.04 1180.6897,-54 1185.4141,-48.847 1190.912,-43.825 1196.4092,-39.2463"/>
<polygon fill="#000000" stroke="#000000" points="1198.7392,-41.8648 1204.3725,-32.8917 1194.373,-36.3933 1198.7392,-41.8648"/>
<text text-anchor="middle" x="1231.6897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- sequencing_file -->
<g id="node13" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="332.6897" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="332.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M348.4808,-261.3075C359.8489,-249.799 376.2091,-235.5704 393.6897,-228 435.8543,-209.7397 561.8745,-199.4934 635.1785,-194.9272"/>
<polygon fill="#000000" stroke="#000000" points="635.8257,-198.3944 645.595,-194.2944 635.4012,-191.4073 635.8257,-198.3944"/>
<text text-anchor="middle" x="460.1897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- study_funding -->
<g id="node15" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="1304.6897" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="1304.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge13" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1299.8677,-87.0221C1296.3818,-76.5307 1290.8359,-63.5281 1282.6897,-54 1276.6663,-46.9547 1268.9146,-40.8231 1261.0805,-35.7143"/>
<polygon fill="#000000" stroke="#000000" points="1262.6544,-32.5756 1252.2881,-30.3865 1259.0267,-38.5623 1262.6544,-32.5756"/>
<text text-anchor="middle" x="1353.6897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- exposure -->
<g id="node16" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1136.6897" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1136.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1160.6986,-175.8296C1180.0327,-163.7726 1208.3948,-148.1966 1235.6897,-141 1332.6773,-115.4283 1587.4034,-137.2382 1686.6897,-123 1692.4092,-122.1798 1698.3342,-121.0946 1704.2173,-119.8625"/>
<polygon fill="#000000" stroke="#000000" points="1705.0375,-123.2656 1714.0347,-117.6709 1703.5123,-116.4338 1705.0375,-123.2656"/>
<text text-anchor="middle" x="1279.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- study_arm -->
<g id="node17" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1459.6897" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1459.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge19" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1450.1908,-87.1136C1443.2505,-75.8263 1432.7795,-61.9282 1419.6897,-54 1395.3443,-39.2544 1320.8579,-28.4829 1271.5862,-22.7396"/>
<polygon fill="#000000" stroke="#000000" points="1271.8135,-19.243 1261.482,-21.5908 1271.0226,-26.1982 1271.8135,-19.243"/>
<text text-anchor="middle" x="1485.1897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- family_relationship -->
<g id="node18" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1307.6897" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1307.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1315.3676,-173.8356C1321.294,-162.2757 1330.6901,-148.1742 1343.6897,-141 1377.1028,-122.5602 1648.9474,-128.6542 1686.6897,-123 1692.404,-122.144 1698.3256,-121.0355 1704.2065,-119.7893"/>
<polygon fill="#000000" stroke="#000000" points="1705.0331,-123.1909 1714.0217,-117.5823 1703.4974,-116.3614 1705.0331,-123.1909"/>
<text text-anchor="middle" x="1423.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- cytogenomic_file -->
<g id="node19" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="523.6897" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="523.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M525.4058,-260.5614C527.3812,-249.6337 531.6175,-236.3348 540.6897,-228 554.7965,-215.04 600.1585,-205.2714 637.161,-199.2033"/>
<polygon fill="#000000" stroke="#000000" points="638.0137,-202.612 647.3429,-197.5904 636.9185,-195.6982 638.0137,-202.612"/>
<text text-anchor="middle" x="612.1897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- study_admin -->
<g id="node20" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1607.6897" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1607.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge31" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1589.3901,-87.5426C1576.1224,-75.9842 1557.1585,-61.6019 1537.6897,-54 1490.3927,-35.5321 1346.7846,-24.8818 1272.0305,-20.4487"/>
<polygon fill="#000000" stroke="#000000" points="1272.1425,-16.9494 1261.9565,-19.8643 1271.737,-23.9376 1272.1425,-16.9494"/>
<text text-anchor="middle" x="1621.1897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- diagnosis -->
<g id="node21" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="897.6897" cy="-279" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="897.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M911.4831,-261.4011C931.9525,-235.4871 969.6738,-188.5587 985.6897,-174 1004.8466,-156.5863 1009.0743,-149.0188 1033.6897,-141 1102.7032,-118.5179 1614.7795,-132.8602 1686.6897,-123 1692.4142,-122.2151 1698.3424,-121.1528 1704.2274,-119.9345"/>
<polygon fill="#000000" stroke="#000000" points="1705.0412,-123.3391 1714.0469,-117.7581 1703.5264,-116.505 1705.0412,-123.3391"/>
<text text-anchor="middle" x="1030.1897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge24" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M870.0392,-263.3536C859.2477,-257.1408 846.818,-249.8532 835.6897,-243 825.2982,-236.6005 823.7761,-233.1021 812.6897,-228 789.2727,-217.2231 761.8592,-208.8274 738.8625,-202.8649"/>
<polygon fill="#000000" stroke="#000000" points="739.5223,-199.4219 728.9707,-200.3779 737.8154,-206.2106 739.5223,-199.4219"/>
<text text-anchor="middle" x="880.1897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M890.9621,-116.7924C884.2164,-118.8769 877.2489,-121.0146 870.6897,-123 843.6352,-131.1893 835.3547,-129.1542 809.6897,-141 798.609,-146.1143 797.589,-150.5096 786.6897,-156 770.1951,-164.3091 751.3027,-171.751 734.5994,-177.682"/>
<polygon fill="#000000" stroke="#000000" points="733.3525,-174.4098 725.0524,-180.9945 735.6472,-181.023 733.3525,-174.4098"/>
<text text-anchor="middle" x="850.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge21" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M935.3163,-86.9658C940.4579,-75.616 948.7424,-61.7039 960.6897,-54 995.8768,-31.3105 1113.0096,-22.723 1179.163,-19.629"/>
<polygon fill="#000000" stroke="#000000" points="1179.4871,-23.1182 1189.3221,-19.1783 1179.1768,-16.125 1179.4871,-23.1182"/>
<text text-anchor="middle" x="1001.1897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- radiology_file -->
<g id="node23" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1499.6897" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1499.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1501.66,-173.8343C1503.8836,-162.58 1508.6164,-148.8253 1518.6897,-141 1548.3411,-117.9658 1649.7218,-129.5689 1686.6897,-123 1692.0813,-122.042 1697.6671,-120.9059 1703.234,-119.6774"/>
<polygon fill="#000000" stroke="#000000" points="1704.2289,-123.04 1713.1881,-117.3846 1702.6576,-116.2186 1704.2289,-123.04"/>
<text text-anchor="middle" x="1577.6897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge23" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M638.3517,-122.914C637.3224,-133.1353 637.5724,-145.8853 642.6897,-156 645.613,-161.7779 649.9439,-166.8923 654.8125,-171.3197"/>
<polygon fill="#000000" stroke="#000000" points="652.7895,-174.1838 662.7809,-177.7084 657.1682,-168.7223 652.7895,-174.1838"/>
<text text-anchor="middle" x="666.6897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge22" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M660.6625,-91.7008C679.1327,-79.531 708.47,-62.2091 736.6897,-54 818.8583,-30.0973 1073.5801,-21.5345 1179.1364,-18.9599"/>
<polygon fill="#000000" stroke="#000000" points="1179.2589,-22.4581 1189.1732,-18.7223 1179.0932,-15.4601 1179.2589,-22.4581"/>
<text text-anchor="middle" x="760.6897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- molecular_test -->
<g id="node25" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1670.6897" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1670.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1652.0499,-174.1954C1643.6699,-164.0106 1637.1699,-151.2606 1644.6897,-141 1648.5005,-135.8003 1675.4636,-127.1683 1702.2087,-119.6603"/>
<polygon fill="#000000" stroke="#000000" points="1703.3018,-122.9895 1712.0091,-116.9535 1701.4381,-116.2422 1703.3018,-122.9895"/>
<text text-anchor="middle" x="1708.6897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
</g>
</svg>
</div>
