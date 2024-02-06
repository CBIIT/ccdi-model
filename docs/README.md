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
<svg width="3782pt" height="305pt"
 viewBox="0.00 0.00 3781.58 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 3777.5761,-301 3777.5761,4 -4,4"/>
<!-- sample -->
<g id="node1" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1424.6332" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1424.6332" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- participant -->
<g id="node11" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="2606.6332" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="2606.6332" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge37" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1458.3493,-180.124C1466.2318,-177.7434 1474.657,-175.5124 1482.6332,-174 1580.2755,-155.4858 1829.437,-147.0752 1928.6332,-141 2093.4073,-130.9085 2134.7867,-131.8314 2299.6332,-123 2380.4368,-118.6711 2473.1696,-113.1587 2535.3839,-109.3816"/>
<polygon fill="#000000" stroke="#000000" points="2535.7141,-112.868 2545.4832,-108.7674 2535.2892,-105.881 2535.7141,-112.868"/>
<text text-anchor="middle" x="1965.1332" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node15" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="1397.6332" cy="-105" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="1397.6332" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge38" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1389.8009,-180.8083C1359.0005,-170.8321 1318.7591,-157.5667 1317.6332,-156 1313.7427,-150.5863 1314.0134,-146.5983 1317.6332,-141 1321.9476,-134.3274 1336.0355,-127.1134 1351.213,-120.908"/>
<polygon fill="#000000" stroke="#000000" points="1352.6873,-124.0896 1360.7262,-117.1884 1350.1383,-117.5702 1352.6873,-124.0896"/>
<text text-anchor="middle" x="1354.1332" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node24" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1523.6332" cy="-105" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1523.6332" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge39" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1451.3984,-177.5107C1461.3835,-171.5008 1472.5027,-164.05 1481.6332,-156 1490.37,-148.2971 1498.784,-138.6805 1505.7567,-129.8806"/>
<polygon fill="#000000" stroke="#000000" points="1508.658,-131.8487 1511.9637,-121.7828 1503.1024,-127.5902 1508.658,-131.8487"/>
<text text-anchor="middle" x="1533.1332" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_arm -->
<g id="node2" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="762.6332" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="762.6332" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study -->
<g id="node12" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1462.6332" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1462.6332" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge15" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M786.6567,-88.4779C805.3654,-76.5695 832.47,-61.3518 858.6332,-54 911.6806,-39.0938 1283.5071,-24.439 1415.935,-19.6367"/>
<polygon fill="#000000" stroke="#000000" points="1416.2886,-23.1263 1426.1561,-19.2684 1416.0365,-16.1309 1416.2886,-23.1263"/>
<text text-anchor="middle" x="907.1332" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- exposure -->
<g id="node3" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="2461.6332" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="2461.6332" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2476.8038,-174.6128C2486.9435,-163.8161 2501.0555,-150.2776 2515.6332,-141 2527.5131,-133.4393 2541.2392,-127.0008 2554.3708,-121.7503"/>
<polygon fill="#000000" stroke="#000000" points="2555.7084,-124.986 2563.7927,-118.1381 2553.2025,-118.4499 2555.7084,-124.986"/>
<text text-anchor="middle" x="2559.1332" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- radiology_file -->
<g id="node4" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="2606.6332" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="2606.6332" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2606.6332,-173.9735C2606.6332,-162.1918 2606.6332,-146.5607 2606.6332,-133.1581"/>
<polygon fill="#000000" stroke="#000000" points="2610.1333,-133.0033 2606.6332,-123.0034 2603.1333,-133.0034 2610.1333,-133.0033"/>
<text text-anchor="middle" x="2665.6332" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- pathology_file -->
<g id="node5" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="343.6332" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="343.6332" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge28" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M398.3334,-266.4527C408.3746,-264.4244 418.7914,-262.501 428.6332,-261 583.0926,-237.4432 622.6909,-237.7286 778.6332,-228 909.1074,-219.8602 1237.6972,-231.5705 1366.6332,-210 1371.4491,-209.1943 1376.4207,-208.091 1381.3341,-206.8242"/>
<polygon fill="#000000" stroke="#000000" points="1382.5863,-210.1081 1391.2693,-204.0371 1380.6956,-203.3683 1382.5863,-210.1081"/>
<text text-anchor="middle" x="839.6332" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge27" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M269.6873,-274.4392C180.9585,-267.2445 40.0471,-249.7467 7.6332,-210 -2.4788,-197.6005 -2.5913,-186.3069 7.6332,-174 58.7698,-112.4483 105.0104,-148.9852 184.6332,-141 440.0498,-115.3848 1086.143,-163.4535 1339.6332,-123 1343.8498,-122.3271 1348.1839,-121.4166 1352.4928,-120.3605"/>
<polygon fill="#000000" stroke="#000000" points="1353.6925,-123.6619 1362.4339,-117.6754 1351.8672,-116.9041 1353.6925,-123.6619"/>
<text text-anchor="middle" x="68.6332" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge26" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M349.784,-260.7679C359.1113,-236.2795 379.3581,-193.5808 412.6332,-174 433.9031,-161.4837 830.9875,-142.287 855.6332,-141 988.845,-134.0436 1323.6278,-142.1926 1455.6332,-123 1466.5315,-121.4155 1478.1898,-118.7137 1488.7202,-115.8784"/>
<polygon fill="#000000" stroke="#000000" points="1489.7316,-119.2298 1498.4092,-113.1512 1487.8349,-112.4916 1489.7316,-119.2298"/>
<text text-anchor="middle" x="473.6332" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- medical_history -->
<g id="node6" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2783.6332" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2783.6332" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2768.3987,-174.1713C2758.1578,-163.1983 2743.7994,-149.6295 2728.6332,-141 2717.1875,-134.4875 2689.9277,-126.2296 2664.0726,-119.2661"/>
<polygon fill="#000000" stroke="#000000" points="2664.831,-115.8463 2654.268,-116.6669 2663.0373,-122.6126 2664.831,-115.8463"/>
<text text-anchor="middle" x="2816.6332" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- publication -->
<g id="node7" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="903.6332" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="903.6332" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge12" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M926.4823,-88.0898C943.723,-76.3129 968.4627,-61.4345 992.6332,-54 1070.808,-29.9546 1313.4409,-21.5111 1416.0542,-18.9649"/>
<polygon fill="#000000" stroke="#000000" points="1416.2057,-22.4623 1426.1187,-18.723 1416.0375,-15.4644 1416.2057,-22.4623"/>
<text text-anchor="middle" x="1043.6332" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- cytogenomic_file -->
<g id="node8" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1865.6332" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1865.6332" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1783.479,-271.7431C1731.707,-266.1698 1663.7169,-257.0093 1604.6332,-243 1584.5299,-238.2333 1580.5025,-233.6635 1560.6332,-228 1526.4182,-218.2474 1516.9796,-219.279 1482.6332,-210 1478.2788,-208.8236 1473.76,-207.5377 1469.2533,-206.2118"/>
<polygon fill="#000000" stroke="#000000" points="1470.0596,-202.7995 1459.4754,-203.272 1468.0442,-209.5031 1470.0596,-202.7995"/>
<text text-anchor="middle" x="1676.1332" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;cell_line -->
<g id="edge20" class="edge">
<title>cytogenomic_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1867.2115,-260.9371C1867.1147,-249.7249 1864.8371,-235.9786 1855.6332,-228 1826.1255,-202.4207 1536.3132,-232.8337 1504.6332,-210 1477.9183,-190.745 1500.3311,-164.859 1477.6332,-141 1469.1039,-132.0344 1457.9301,-125.1335 1446.6497,-119.8898"/>
<polygon fill="#000000" stroke="#000000" points="1447.7765,-116.5655 1437.2048,-115.8659 1445.0328,-123.0054 1447.7765,-116.5655"/>
<text text-anchor="middle" x="1576.1332" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;pdx -->
<g id="edge19" class="edge">
<title>cytogenomic_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1876.447,-260.939C1880.944,-251.1286 1884.3473,-238.8248 1880.6332,-228 1877.3441,-218.4137 1871.6977,-218.7787 1866.6332,-210 1850.0949,-181.333 1864.989,-161.017 1838.6332,-141 1816.9499,-124.5317 1640.6051,-112.0143 1561.6327,-107.1785"/>
<polygon fill="#000000" stroke="#000000" points="1561.7998,-103.6823 1551.6073,-106.5739 1561.3784,-110.6696 1561.7998,-103.6823"/>
<text text-anchor="middle" x="1938.1332" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- diagnosis -->
<g id="node9" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="2941.6332" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="2941.6332" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2928.67,-174.3736C2919.0338,-162.7376 2904.7977,-148.3321 2888.6332,-141 2845.9783,-121.6521 2724.833,-130.7044 2678.6332,-123 2673.2318,-122.0992 2667.6394,-121.0015 2662.0683,-119.7969"/>
<polygon fill="#000000" stroke="#000000" points="2662.6364,-116.3368 2652.1093,-117.5329 2661.0846,-123.1627 2662.6364,-116.3368"/>
<text text-anchor="middle" x="2954.1332" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- study_funding -->
<g id="node10" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="1061.6332" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="1061.6332" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge24" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1077.3871,-87.2208C1088.7386,-75.6735 1105.0943,-61.4343 1122.6332,-54 1174.3473,-32.0796 1335.4166,-22.8947 1415.8925,-19.5952"/>
<polygon fill="#000000" stroke="#000000" points="1416.3739,-23.079 1426.2275,-19.1858 1416.0967,-16.0845 1416.3739,-23.079"/>
<text text-anchor="middle" x="1184.6332" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge36" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2549.3321,-97.7404C2461.0567,-86.7895 2286.4155,-66.0478 2137.6332,-54 1901.9363,-34.9142 1619.0876,-23.5702 1509.3383,-19.6051"/>
<polygon fill="#000000" stroke="#000000" points="1509.384,-16.1046 1499.2651,-19.2444 1509.1334,-23.1001 1509.384,-16.1046"/>
<text text-anchor="middle" x="2343.1332" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- therapeutic_procedure -->
<g id="node13" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="3131.6332" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="3131.6332" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3097.0049,-174.7772C3071.5655,-163.0097 3035.8006,-148.2775 3002.6332,-141 2861.7623,-110.0905 2821.2306,-144.5863 2678.6332,-123 2673.1393,-122.1683 2667.4531,-121.1061 2661.7954,-119.9145"/>
<polygon fill="#000000" stroke="#000000" points="2662.2131,-116.4214 2651.6899,-117.6519 2660.6836,-123.2523 2662.2131,-116.4214"/>
<text text-anchor="middle" x="3142.6332" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- study_personnel -->
<g id="node14" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="1243.6332" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1243.6332" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge13" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1244.7081,-86.8855C1246.3481,-75.7986 1250.2941,-62.2101 1259.6332,-54 1282.3779,-34.0048 1363.7515,-24.714 1416.3073,-20.7128"/>
<polygon fill="#000000" stroke="#000000" points="1416.6872,-24.1945 1426.4083,-19.9815 1416.1817,-17.2128 1416.6872,-24.1945"/>
<text text-anchor="middle" x="1329.1332" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1394.2672,-123.4103C1393.1926,-133.3229 1393.0694,-145.6131 1396.6332,-156 1397.926,-159.7681 1399.7922,-163.4455 1401.9564,-166.9225"/>
<polygon fill="#000000" stroke="#000000" points="1399.1313,-168.9889 1407.7933,-175.0897 1404.8264,-164.9187 1399.1313,-168.9889"/>
<text text-anchor="middle" x="1437.1332" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge8" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1398.2405,-86.6884C1399.3596,-76.3345 1402.1096,-63.5845 1408.6332,-54 1413.5089,-46.8366 1420.3286,-40.7282 1427.4842,-35.6874"/>
<polygon fill="#000000" stroke="#000000" points="1429.4154,-38.6069 1435.9423,-30.2612 1425.6356,-32.7151 1429.4154,-38.6069"/>
<text text-anchor="middle" x="1449.1332" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- follow_up -->
<g id="node16" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="3322.6332" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="3322.6332" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3301.9348,-175.025C3285.9814,-163.05 3262.7978,-147.9512 3239.6332,-141 3120.1653,-105.1503 2802.1692,-140.2233 2678.6332,-123 2672.9106,-122.2022 2666.9835,-121.1315 2661.0992,-119.9081"/>
<polygon fill="#000000" stroke="#000000" points="2661.8016,-116.4789 2651.2804,-117.7262 2660.2831,-123.3122 2661.8016,-116.4789"/>
<text text-anchor="middle" x="3315.6332" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- sequencing_file -->
<g id="node17" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1422.6332" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1422.6332" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1422.958,-260.5864C1423.1382,-250.8901 1423.3773,-238.8011 1423.6332,-228 1423.6907,-225.574 1423.7537,-223.0561 1423.8193,-220.5299"/>
<polygon fill="#000000" stroke="#000000" points="1427.3239,-220.4044 1424.0956,-210.3134 1420.3264,-220.2151 1427.3239,-220.4044"/>
<text text-anchor="middle" x="1490.1332" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge2" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1352.0979,-269.3711C1298.9584,-261.7481 1230.7774,-251.0768 1203.6332,-243 1187.8028,-238.2896 1185.5534,-232.3975 1169.6332,-228 1138.3357,-219.355 1046.132,-234.3326 1024.6332,-210 953.8751,-129.9151 930.3353,-219.1436 1339.6332,-123 1343.4501,-122.1034 1347.3819,-121.0875 1351.3148,-120.0058"/>
<polygon fill="#000000" stroke="#000000" points="1352.3852,-123.3399 1361.0282,-117.2121 1350.4503,-116.6126 1352.3852,-123.3399"/>
<text text-anchor="middle" x="1091.1332" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge3" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1481.6197,-266.2564C1505.3285,-260.3382 1532.6695,-252.4919 1556.6332,-243 1569.7587,-237.8011 1571.5077,-233.1989 1584.6332,-228 1613.3,-216.6453 1632.8709,-234.4682 1651.6332,-210 1671.2194,-184.4573 1655.1577,-160.6099 1629.6332,-141 1609.676,-125.6674 1582.7872,-116.635 1561.0855,-111.4523"/>
<polygon fill="#000000" stroke="#000000" points="1561.733,-108.011 1551.2132,-109.2699 1560.2219,-114.846 1561.733,-108.011"/>
<text text-anchor="middle" x="1727.1332" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- family_relationship -->
<g id="node18" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="3495.6332" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="3495.6332" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3461.5924,-174.9897C3435.7126,-162.9966 3398.8465,-147.8907 3364.6332,-141 3215.1382,-110.8909 2829.7301,-143.6162 2678.6332,-123 2672.9083,-122.2189 2666.9797,-121.1591 2661.0945,-119.9422"/>
<polygon fill="#000000" stroke="#000000" points="2661.795,-116.5126 2651.2747,-117.7675 2660.2814,-123.347 2661.795,-116.5126"/>
<text text-anchor="middle" x="3492.1332" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- molecular_test -->
<g id="node19" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="3693.6332" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="3693.6332" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3663.671,-175.1756C3640.4479,-163.1089 3607.0374,-147.8253 3575.6332,-141 3380.808,-98.657 2876.2585,-149.344 2678.6332,-123 2672.8241,-122.2256 2666.8063,-121.1582 2660.8374,-119.9263"/>
<polygon fill="#000000" stroke="#000000" points="2661.4043,-116.4671 2650.8839,-117.7205 2659.8897,-123.3013 2661.4043,-116.4671"/>
<text text-anchor="middle" x="3682.6332" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- synonym -->
<g id="node20" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2025.6332" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2025.6332" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge33" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1987.1166,-266.7737C1979.7018,-264.6651 1971.9623,-262.6307 1964.6332,-261 1869.4084,-239.813 1844.6036,-238.648 1747.6332,-228 1630.2894,-215.1148 1598.6816,-231.6417 1482.6332,-210 1477.8331,-209.1048 1472.8716,-207.9445 1467.9641,-206.6441"/>
<polygon fill="#000000" stroke="#000000" points="1468.6119,-203.1896 1458.0358,-203.8186 1466.6958,-209.9222 1468.6119,-203.1896"/>
<text text-anchor="middle" x="1914.1332" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2075.1519,-273.1913C2128.3857,-265.254 2214.0541,-247.4767 2278.6332,-210 2298.2039,-198.6427 2294.8711,-185.0209 2314.6332,-174 2384.0163,-135.3063 2474.3637,-118.2268 2536.0722,-110.7413"/>
<polygon fill="#000000" stroke="#000000" points="2536.573,-114.2068 2546.1033,-109.5783 2535.7667,-107.2534 2536.573,-114.2068"/>
<text text-anchor="middle" x="2357.1332" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge32" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2028.2875,-260.9934C2030.6104,-237.9318 2030.8401,-198.0772 2009.6332,-174 1942.156,-97.39 1626.8634,-42.769 1508.0702,-24.5912"/>
<polygon fill="#000000" stroke="#000000" points="1508.2748,-21.0824 1497.8634,-23.0453 1507.2265,-28.0035 1508.2748,-21.0824"/>
<text text-anchor="middle" x="2030.1332" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- clinical_measure_file -->
<g id="node21" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="2160.6332" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="2160.6332" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2153.6142,-173.7502C2150.7381,-162.8935 2149.6923,-149.6031 2157.6332,-141 2163.9531,-134.1531 2409.8591,-117.5396 2535.0117,-109.5027"/>
<polygon fill="#000000" stroke="#000000" points="2535.5166,-112.9776 2545.2724,-108.8456 2535.0692,-105.9919 2535.5166,-112.9776"/>
<text text-anchor="middle" x="2243.6332" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge29" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2150.977,-174.0417C2133.2279,-143.1046 2092.1811,-80.5293 2037.6332,-54 1990.7175,-31.1826 1638.3622,-21.6457 1509.5824,-18.8978"/>
<polygon fill="#000000" stroke="#000000" points="1509.3344,-15.3919 1499.2633,-18.682 1509.1879,-22.3904 1509.3344,-15.3919"/>
<text text-anchor="middle" x="2202.6332" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- study_admin -->
<g id="node22" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="2757.6332" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2757.6332" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge10" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2706.1484,-92.5887C2696.6981,-90.5466 2686.8947,-88.5833 2677.6332,-87 2554.1193,-65.8851 2522.5589,-63.7514 2397.6332,-54 2057.4839,-27.4487 1646.1243,-20.2326 1509.3521,-18.4972"/>
<polygon fill="#000000" stroke="#000000" points="1509.27,-14.996 1499.2277,-18.3724 1509.1837,-21.9954 1509.27,-14.996"/>
<text text-anchor="middle" x="2614.1332" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node23" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="575.6332" cy="-279" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="575.6332" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M688.5669,-268.6687C752.1751,-262.3423 832.9942,-253.458 904.6332,-243 941.2938,-237.6482 949.825,-232.2192 986.6332,-228 1154.6115,-208.745 1200.1117,-239.2925 1366.6332,-210 1371.4422,-209.1541 1376.4094,-208.0251 1381.3202,-206.7432"/>
<polygon fill="#000000" stroke="#000000" points="1382.5797,-210.0245 1391.2524,-203.9388 1380.6776,-203.2879 1382.5797,-210.0245"/>
<text text-anchor="middle" x="1095.1332" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge6" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M476.3026,-266.4951C351.5823,-250.3159 152.476,-222.7028 141.6332,-210 131.2456,-197.8305 130.5895,-185.5774 141.6332,-174 195.301,-117.7388 762.9473,-144.2348 840.6332,-141 951.4981,-136.3836 1230.2435,-141.6073 1339.6332,-123 1343.7843,-122.2939 1348.0517,-121.37 1352.2983,-120.3135"/>
<polygon fill="#000000" stroke="#000000" points="1353.3727,-123.6485 1362.1043,-117.6477 1351.5363,-116.8937 1353.3727,-123.6485"/>
<text text-anchor="middle" x="250.1332" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge5" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M561.9136,-260.9248C546.1211,-237.789 525.0811,-197.8543 547.6332,-174 549.8025,-171.7054 1452.5145,-123.4951 1455.6332,-123 1466.5099,-121.2733 1478.1617,-118.5295 1488.693,-115.6994"/>
<polygon fill="#000000" stroke="#000000" points="1489.6963,-119.0532 1498.3847,-112.99 1487.8116,-112.3117 1489.6963,-119.0532"/>
<text text-anchor="middle" x="656.1332" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge40" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1546.5376,-115.6168C1564.9305,-125.5861 1585.8337,-141.1498 1573.6332,-156 1547.4614,-187.8557 1522.5989,-163.8759 1482.6332,-174 1478.2017,-175.1226 1473.6075,-176.3813 1469.0328,-177.6977"/>
<polygon fill="#000000" stroke="#000000" points="1467.7098,-174.4395 1459.1201,-180.6416 1469.7027,-181.1498 1467.7098,-174.4395"/>
<text text-anchor="middle" x="1601.6332" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge41" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1514.3737,-87.5185C1508.7871,-77.4414 1501.2871,-64.6914 1493.6332,-54 1490.913,-50.2004 1487.8785,-46.3193 1484.802,-42.5789"/>
<polygon fill="#000000" stroke="#000000" points="1487.2493,-40.0539 1478.1058,-34.7016 1481.9159,-44.5877 1487.2493,-40.0539"/>
<text text-anchor="middle" x="1527.6332" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- methylation_array_file -->
<g id="node25" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1158.6332" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1158.6332" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1180.0706,-261.2243C1194.9962,-249.8332 1215.8753,-235.7738 1236.6332,-228 1291.2573,-207.5434 1309.7006,-222.6866 1366.6332,-210 1371.2769,-208.9652 1376.0857,-207.7359 1380.857,-206.4129"/>
<polygon fill="#000000" stroke="#000000" points="1381.9091,-209.752 1390.5333,-203.5978 1379.9536,-203.0307 1381.9091,-209.752"/>
<text text-anchor="middle" x="1328.1332" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge23" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1044.0165,-276.3098C933.8747,-272.5085 781.414,-263.5656 762.6332,-243 758.1376,-238.0772 760.7426,-234.393 762.6332,-228 770.744,-200.5739 773.1729,-188.8213 797.6332,-174 901.0978,-111.3072 1221.0054,-146.7224 1339.6332,-123 1343.704,-122.1859 1347.8946,-121.1965 1352.072,-120.1048"/>
<polygon fill="#000000" stroke="#000000" points="1353.0425,-123.4678 1361.7323,-117.4066 1351.1594,-116.7258 1353.0425,-123.4678"/>
<text text-anchor="middle" x="889.1332" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge22" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1158.6577,-260.7039C1159.7103,-237.3293 1165.1192,-197.1366 1188.6332,-174 1274.7485,-89.2669 1337.031,-146.0018 1455.6332,-123 1466.3538,-120.9208 1477.8818,-118.098 1488.3451,-115.3046"/>
<polygon fill="#000000" stroke="#000000" points="1489.2707,-118.6801 1497.9896,-112.6607 1487.42,-111.9291 1489.2707,-118.6801"/>
<text text-anchor="middle" x="1280.1332" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
</g>
</svg>
</div>
