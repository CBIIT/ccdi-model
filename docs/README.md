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
<svg width="3152pt" height="392pt"
 viewBox="0.00 0.00 3151.69 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3147.6942,-388 3147.6942,4 -4,4"/>
<!-- radiology_file -->
<g id="node1" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1930.6942" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1930.6942" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- participant -->
<g id="node23" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="2039.6942" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="2039.6942" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1913.8936,-174.3902C1906.0806,-164.0294 1900.0298,-151.0346 1907.6942,-141 1908.9503,-139.3554 1947.9753,-128.8281 1983.2657,-119.5792"/>
<polygon fill="#000000" stroke="#000000" points="1984.2958,-122.9276 1993.0859,-117.0129 1982.5258,-116.1551 1984.2958,-122.9276"/>
<text text-anchor="middle" x="1966.6942" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- therapeutic_procedure -->
<g id="node2" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="2248.6942" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="2248.6942" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge37" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2207.9007,-175.019C2172.5686,-160.3114 2121.5247,-139.0634 2084.9457,-123.8367"/>
<polygon fill="#000000" stroke="#000000" points="2086.0846,-120.5198 2075.5075,-119.9079 2083.3945,-126.9822 2086.0846,-120.5198"/>
<text text-anchor="middle" x="2249.6942" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- diagnosis -->
<g id="node3" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="2477.6942" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="2477.6942" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2454.9914,-175.4658C2434.9675,-160.9542 2408.5297,-141.9986 2405.6942,-141 2343.7463,-119.1829 2175.5882,-133.1144 2110.6942,-123 2105.3542,-122.1677 2099.8304,-121.1157 2094.331,-119.9398"/>
<polygon fill="#000000" stroke="#000000" points="2095.0301,-116.5095 2084.5035,-117.7101 2093.4812,-123.336 2095.0301,-116.5095"/>
<text text-anchor="middle" x="2471.1942" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- synonym -->
<g id="node4" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2394.6942" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2394.6942" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- sample -->
<g id="node6" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1415.6942" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1415.6942" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge30" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2344.4499,-361.3116C2240.681,-351.7302 1995.1171,-329.5813 1788.6942,-315 1648.8143,-305.1192 1611.682,-321.9671 1473.6942,-297 1468.8894,-296.1306 1463.9248,-294.9867 1459.0156,-293.696"/>
<polygon fill="#000000" stroke="#000000" points="1459.6607,-290.2411 1449.0852,-290.8816 1457.7518,-296.9758 1459.6607,-290.2411"/>
<text text-anchor="middle" x="2014.1942" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study -->
<g id="node12" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1964.6942" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1964.6942" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge31" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2446.7972,-364.6342C2603.3289,-359.8455 3058.6942,-340.6194 3058.6942,-279 3058.6942,-279 3058.6942,-279 3058.6942,-105 3058.6942,-56.6884 3063.0405,-76.1103 2917.6942,-54 2740.006,-26.9699 2178.2716,-19.8945 2011.6938,-18.3686"/>
<polygon fill="#000000" stroke="#000000" points="2011.3322,-14.8654 2001.3014,-18.276 2011.2697,-21.8651 2011.3322,-14.8654"/>
<text text-anchor="middle" x="3101.1942" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2398.3412,-347.8089C2406.5322,-301.0467 2420.312,-177.747 2346.6942,-141 2299.6344,-117.5097 2162.6005,-131.4942 2110.6942,-123 2105.3607,-122.1272 2099.8412,-121.0481 2094.3445,-119.8552"/>
<polygon fill="#000000" stroke="#000000" points="2095.0492,-116.4261 2084.5202,-117.6052 2093.4865,-123.2494 2095.0492,-116.4261"/>
<text text-anchor="middle" x="2445.1942" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- cell_line -->
<g id="node5" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="1140.6942" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="1140.6942" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1176.9044,-204.3354C1184.3695,-206.5131 1192.2311,-208.5454 1199.6942,-210 1243.9286,-218.6216 1367.1059,-199.1095 1401.6942,-228 1408.4575,-233.6492 1412.1174,-242.2309 1414.0502,-250.7523"/>
<polygon fill="#000000" stroke="#000000" points="1410.6368,-251.5782 1415.6437,-260.9153 1417.5523,-250.4938 1410.6368,-251.5782"/>
<text text-anchor="middle" x="1453.1942" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge15" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1157.1201,-174.9979C1168.8424,-163.7976 1185.5169,-149.6536 1202.6942,-141 1291.0677,-96.479 1321.8047,-107.1106 1418.6942,-87 1601.742,-49.0062 1823.9391,-28.7826 1918.5077,-21.3603"/>
<polygon fill="#000000" stroke="#000000" points="1918.8962,-24.8407 1928.5962,-20.5792 1918.3558,-17.8616 1918.8962,-24.8407"/>
<text text-anchor="middle" x="1459.1942" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1165.1717,-176.2113C1185.5445,-164.0244 1215.7877,-148.0859 1244.6942,-141 1401.005,-102.6833 1809.2542,-144.9117 1968.6942,-123 1974.2058,-122.2425 1979.9072,-121.2183 1985.5725,-120.0405"/>
<polygon fill="#000000" stroke="#000000" points="1986.6876,-123.3777 1995.6824,-117.7792 1985.1596,-116.5465 1986.6876,-123.3777"/>
<text text-anchor="middle" x="1285.1942" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge10" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1450.8779,-267.9575C1483.493,-257.6814 1527.0926,-243.8252 1527.6942,-243 1531.6213,-237.6128 1532.2773,-232.8415 1527.6942,-228 1502.6024,-201.4934 1235.633,-216.3717 1199.6942,-210 1195.305,-209.2218 1190.7832,-208.2208 1186.2882,-207.09"/>
<polygon fill="#000000" stroke="#000000" points="1187.1199,-203.6892 1176.552,-204.4433 1185.2836,-210.4441 1187.1199,-203.6892"/>
<text text-anchor="middle" x="1568.1942" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node20" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="911.6942" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="911.6942" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge11" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1381.6532,-267.1982C1364.5093,-260.8032 1343.6139,-252.3111 1325.6942,-243 1314.8648,-237.3731 1314.2406,-231.952 1302.6942,-228 1209.8758,-196.2313 1180.3724,-219.1356 1082.6942,-210 1036.904,-205.7173 984.2962,-200.0703 949.6605,-196.2521"/>
<polygon fill="#000000" stroke="#000000" points="949.8402,-192.7507 939.5159,-195.1293 949.0702,-199.7082 949.8402,-192.7507"/>
<text text-anchor="middle" x="1362.1942" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1449.4336,-267.2437C1457.315,-264.8575 1465.7339,-262.594 1473.6942,-261 1591.665,-237.3771 1921.197,-288.1245 2012.6942,-210 2034.6396,-191.262 2039.9835,-157.3089 2040.7395,-133.0851"/>
<polygon fill="#000000" stroke="#000000" points="2044.2396,-133.0763 2040.8127,-123.051 2037.2398,-133.0252 2044.2396,-133.0763"/>
<text text-anchor="middle" x="2070.1942" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- methylation_array_file -->
<g id="node7" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1436.6942" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1436.6942" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge22" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1533.2895,-355.9834C1568.4049,-350.414 1602.4866,-342.0926 1614.6942,-330 1646.9567,-298.0414 1645.6603,-254.3767 1608.6942,-228 1571.6656,-201.5787 1244.5265,-217.698 1199.6942,-210 1195.3008,-209.2456 1190.7763,-208.2607 1186.2794,-207.1401"/>
<polygon fill="#000000" stroke="#000000" points="1187.1078,-203.7385 1176.5408,-204.5071 1185.2807,-210.4958 1187.1078,-203.7385"/>
<text text-anchor="middle" x="1730.1942" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1432.343,-347.9735C1429.4709,-336.0751 1425.6513,-320.2508 1422.395,-306.7606"/>
<polygon fill="#000000" stroke="#000000" points="1425.7886,-305.9029 1420.0398,-297.0034 1418.984,-307.5455 1425.7886,-305.9029"/>
<text text-anchor="middle" x="1519.1942" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge20" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1352.1495,-353.5912C1322.7246,-347.9977 1289.8076,-340.2839 1260.6942,-330 1247.0118,-325.1669 1245.6491,-318.9784 1231.6942,-315 1182.3913,-300.9442 1047.3994,-320.2245 1001.6942,-297 983.5573,-287.784 949.9927,-244.7559 929.3744,-216.7207"/>
<polygon fill="#000000" stroke="#000000" points="932.1415,-214.575 923.4227,-208.5556 926.4848,-218.6983 932.1415,-214.575"/>
<text text-anchor="middle" x="1093.1942" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- medical_history -->
<g id="node8" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2635.6942" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2635.6942" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2589.4108,-176.7345C2573.6378,-170.9396 2556.1043,-163.829 2540.6942,-156 2529.8138,-150.4723 2529.3126,-144.7351 2517.6942,-141 2431.5057,-113.2917 2200.2606,-136.1927 2110.6942,-123 2105.2688,-122.2009 2099.6565,-121.1602 2094.0742,-119.982"/>
<polygon fill="#000000" stroke="#000000" points="2094.6301,-116.5196 2084.1053,-117.7352 2093.091,-123.3483 2094.6301,-116.5196"/>
<text text-anchor="middle" x="2608.6942" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- study_funding -->
<g id="node9" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="1585.6942" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="1585.6942" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge34" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1600.8334,-87.2557C1611.769,-75.724 1627.5763,-61.4891 1644.6942,-54 1692.5725,-33.0531 1841.1875,-23.5011 1917.8682,-19.8723"/>
<polygon fill="#000000" stroke="#000000" points="1918.3636,-23.3534 1928.1928,-19.3991 1918.043,-16.3607 1918.3636,-23.3534"/>
<text text-anchor="middle" x="1706.6942" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- study_admin -->
<g id="node10" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1751.6942" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1751.6942" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1759.6566,-86.9505C1765.5313,-75.7439 1774.6033,-61.9987 1786.6942,-54 1807.9788,-39.9192 1873.5268,-29.2507 1918.8436,-23.3097"/>
<polygon fill="#000000" stroke="#000000" points="1919.5587,-26.7469 1929.0346,-22.008 1918.6718,-19.8033 1919.5587,-26.7469"/>
<text text-anchor="middle" x="1843.1942" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- exposure -->
<g id="node11" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1261.6942" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1261.6942" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1287.3786,-176.005C1308.3756,-163.8739 1339.292,-148.1138 1368.6942,-141 1498.3466,-109.6308 1836.59,-141.5006 1968.6942,-123 1974.1251,-122.2394 1979.7411,-121.2243 1985.3257,-120.062"/>
<polygon fill="#000000" stroke="#000000" points="1986.3011,-123.4304 1995.2973,-117.834 1984.7747,-116.5988 1986.3011,-123.4304"/>
<text text-anchor="middle" x="1412.1942" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- study_arm -->
<g id="node13" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1899.6942" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1899.6942" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge6" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1900.3015,-86.6884C1901.4206,-76.3345 1904.1706,-63.5845 1910.6942,-54 1915.5699,-46.8366 1922.3896,-40.7282 1929.5452,-35.6874"/>
<polygon fill="#000000" stroke="#000000" points="1931.4764,-38.6069 1938.0033,-30.2612 1927.6966,-32.7151 1931.4764,-38.6069"/>
<text text-anchor="middle" x="1959.1942" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- molecular_test -->
<g id="node14" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1412.6942" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1412.6942" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1432.3344,-174.3111C1446.7917,-162.4845 1467.5378,-147.8764 1488.6942,-141 1590.2083,-108.005 1863.0403,-138.2001 1968.6942,-123 1974.1222,-122.2191 1979.7363,-121.1905 1985.3197,-120.0198"/>
<polygon fill="#000000" stroke="#000000" points="1986.2992,-123.3871 1995.2899,-117.7819 1984.7661,-116.557 1986.2992,-123.3871"/>
<text text-anchor="middle" x="1552.6942" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node15" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="612.6942" cy="-366" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="612.6942" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge38" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M599.7574,-347.8843C584.9138,-324.7048 565.3258,-284.7228 587.6942,-261 611.0596,-236.2198 859.9281,-247.4552 893.6942,-243 962.329,-233.9441 1040.4005,-216.6208 1090.0723,-204.6964"/>
<polygon fill="#000000" stroke="#000000" points="1091.0254,-208.0669 1099.9217,-202.3132 1089.3791,-201.2632 1091.0254,-208.0669"/>
<text text-anchor="middle" x="696.1942" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge39" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M731.0284,-356.6788C799.9731,-350.5717 888.4731,-341.5717 966.6942,-330 1001.1843,-324.8977 1009.0999,-319.3409 1043.6942,-315 1182.3912,-297.5961 1220.1452,-321.9006 1357.6942,-297 1362.4989,-296.1302 1367.4634,-294.986 1372.3727,-293.6952"/>
<polygon fill="#000000" stroke="#000000" points="1373.6364,-296.9749 1382.303,-290.8805 1371.7275,-290.2402 1373.6364,-296.9749"/>
<text text-anchor="middle" x="1152.1942" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge40" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M517.2212,-352.9662C386.5791,-334.9092 167.4791,-303.7373 161.6942,-297 151.271,-284.8609 150.9112,-272.8206 161.6942,-261 210.0532,-207.9877 726.895,-195.156 873.2654,-192.5749"/>
<polygon fill="#000000" stroke="#000000" points="873.606,-196.0697 883.545,-192.3999 873.4868,-189.0707 873.606,-196.0697"/>
<text text-anchor="middle" x="270.1942" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- family_relationship -->
<g id="node16" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1610.6942" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1610.6942" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge36" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1613.5714,-173.8293C1616.3976,-162.4219 1621.9341,-148.4969 1632.6942,-141 1663.3697,-119.6273 1931.7322,-128.6205 1968.6942,-123 1974.1158,-122.1756 1979.7256,-121.1181 1985.3064,-119.9295"/>
<polygon fill="#000000" stroke="#000000" points="1986.2945,-123.2944 1995.2734,-117.6705 1984.7471,-116.4676 1986.2945,-123.2944"/>
<text text-anchor="middle" x="1712.1942" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- cytogenomic_file -->
<g id="node17" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="367.6942" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="367.6942" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;cell_line -->
<g id="edge5" class="edge">
<title>cytogenomic_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M372.9027,-347.9171C380.9462,-323.6017 398.8865,-281.1029 430.6942,-261 434.1429,-258.8203 913.4891,-213.4297 1082.5172,-197.4816"/>
<polygon fill="#000000" stroke="#000000" points="1083.0918,-200.943 1092.7188,-196.5192 1082.4343,-193.974 1083.0918,-200.943"/>
<text text-anchor="middle" x="502.1942" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M431.8751,-353.3695C443.1189,-351.3979 454.7273,-349.5153 465.6942,-348 622.2226,-326.3725 661.9942,-324.9797 819.6942,-315 939.0778,-307.4451 1239.7396,-316.9058 1357.6942,-297 1362.5089,-296.1875 1367.4798,-295.0798 1372.3928,-293.8104"/>
<polygon fill="#000000" stroke="#000000" points="1373.6463,-297.0939 1382.3275,-291.0204 1371.7536,-290.3546 1373.6463,-297.0939"/>
<text text-anchor="middle" x="891.1942" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;pdx -->
<g id="edge4" class="edge">
<title>cytogenomic_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M280.5434,-361.6915C185.2881,-354.9425 41.6487,-338.0805 7.6942,-297 -2.4992,-284.6673 -2.6115,-273.239 7.6942,-261 63.1818,-195.1034 113.0755,-237.5227 198.6942,-228 455.3391,-199.4554 766.4977,-193.5282 873.4507,-192.3106"/>
<polygon fill="#000000" stroke="#000000" points="873.7749,-195.8074 883.737,-192.2011 873.7003,-188.8078 873.7749,-195.8074"/>
<text text-anchor="middle" x="79.1942" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- sequencing_file -->
<g id="node18" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1219.6942" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1219.6942" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge17" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1215.4362,-347.9759C1213.0369,-338.1764 1209.887,-325.8711 1206.6942,-315 1199.5652,-290.727 1200.0334,-283.6146 1188.6942,-261 1181.0415,-245.7377 1170.3577,-230.0136 1161.0119,-217.4377"/>
<polygon fill="#000000" stroke="#000000" points="1163.6475,-215.1212 1154.8092,-209.2786 1158.075,-219.3576 1163.6475,-215.1212"/>
<text text-anchor="middle" x="1269.1942" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1239.2066,-348.4016C1252.3541,-337.3802 1270.5501,-323.6718 1288.6942,-315 1317.2891,-301.3333 1327.2185,-305.6992 1357.6942,-297 1362.0315,-295.7619 1366.5389,-294.435 1371.0384,-293.0834"/>
<polygon fill="#000000" stroke="#000000" points="1372.2595,-296.3704 1380.8071,-290.1103 1370.2213,-289.6737 1372.2595,-296.3704"/>
<text text-anchor="middle" x="1355.1942" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge18" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1136.3424,-364.6996C1021.359,-362.0273 825.683,-353.9739 803.6942,-330 799.1879,-325.0869 802.1775,-321.4918 803.6942,-315 813.5071,-272.9994 816.9167,-259.2033 846.6942,-228 855.5305,-218.7406 867.2812,-211.2509 878.3599,-205.55"/>
<polygon fill="#000000" stroke="#000000" points="879.9382,-208.6748 887.4293,-201.1825 876.901,-202.368 879.9382,-208.6748"/>
<text text-anchor="middle" x="887.1942" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- pathology_file -->
<g id="node19" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1910.6942" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1910.6942" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge25" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1920.5841,-348.006C1924.7973,-337.758 1927.5473,-325.008 1921.6942,-315 1896.9802,-272.7429 1871.8451,-277.3261 1825.6942,-261 1562.5313,-167.9049 1474.8648,-256.931 1199.6942,-210 1195.3,-209.2506 1190.7749,-208.2689 1186.2776,-207.1505"/>
<polygon fill="#000000" stroke="#000000" points="1187.1053,-203.7487 1176.5386,-204.5203 1185.2802,-210.5066 1187.1053,-203.7487"/>
<text text-anchor="middle" x="1968.6942" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge24" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1841.6229,-358.321C1792.519,-352.2519 1725.174,-342.6885 1666.6942,-330 1643.1877,-324.8997 1638.2493,-319.8707 1614.6942,-315 1552.8277,-302.2073 1535.4291,-310.4132 1473.6942,-297 1469.045,-295.9899 1464.2328,-294.7766 1459.4594,-293.4631"/>
<polygon fill="#000000" stroke="#000000" points="1460.3595,-290.0801 1449.7805,-290.6594 1458.4118,-296.8036 1460.3595,-290.0801"/>
<text text-anchor="middle" x="1727.6942" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge23" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1910.7555,-347.7786C1909.7381,-336.5014 1906.3742,-322.7421 1896.6942,-315 1862.9907,-288.0437 1548.6177,-313.3915 1508.6942,-297 1486.5689,-287.916 1488.8452,-273.8836 1468.6942,-261 1451.5837,-250.0604 1444.9957,-251.8034 1426.6942,-243 1413.9719,-236.8803 1412.2839,-231.8248 1398.6942,-228 1330.9887,-208.9441 1152.8003,-215.6832 1082.6942,-210 1036.7197,-206.2731 983.9474,-200.4876 949.3319,-196.4863"/>
<polygon fill="#000000" stroke="#000000" points="949.5376,-192.9867 939.1998,-195.3061 948.7276,-199.9397 949.5376,-192.9867"/>
<text text-anchor="middle" x="1569.6942" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M939.1922,-196.0127C1029.9707,-209.2931 1316.6625,-251.5136 1357.6942,-261 1362.3295,-262.0717 1367.1329,-263.3248 1371.9009,-264.6622"/>
<polygon fill="#000000" stroke="#000000" points="1370.9927,-268.0431 1381.5733,-267.4943 1372.9598,-261.3252 1370.9927,-268.0431"/>
<text text-anchor="middle" x="1275.6942" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge2" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M934.215,-181.2255C980.8621,-159.43 1091.9477,-110.2126 1190.6942,-87 1330.347,-54.1714 1772.1619,-28.2664 1917.697,-20.4388"/>
<polygon fill="#000000" stroke="#000000" points="1918.2581,-23.9139 1928.0571,-19.8853 1917.8846,-16.9239 1918.2581,-23.9139"/>
<text text-anchor="middle" x="1214.6942" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- follow_up -->
<g id="node21" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="1783.6942" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="1783.6942" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1788.1541,-173.9625C1791.9415,-162.6113 1798.585,-148.699 1809.6942,-141 1838.9207,-120.7452 1933.7129,-129.3839 1968.6942,-123 1973.8017,-122.0679 1979.0859,-120.9753 1984.3607,-119.797"/>
<polygon fill="#000000" stroke="#000000" points="1985.5,-123.1253 1994.4436,-117.4454 1983.91,-116.3083 1985.5,-123.1253"/>
<text text-anchor="middle" x="1854.6942" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- publication -->
<g id="node22" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="2182.6942" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="2182.6942" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge42" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2166.7904,-87.36C2155.7542,-76.1767 2140.1301,-62.302 2123.6942,-54 2088.2466,-36.0949 2043.8905,-27.0025 2011.0406,-22.4412"/>
<polygon fill="#000000" stroke="#000000" points="2011.1723,-18.9291 2000.8052,-21.1141 2010.2721,-25.871 2011.1723,-18.9291"/>
<text text-anchor="middle" x="2195.6942" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge27" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2030.2887,-87.0635C2024.4869,-76.8347 2016.4869,-64.0847 2007.6942,-54 2003.3273,-48.9915 1998.2325,-44.0948 1993.1084,-39.6062"/>
<polygon fill="#000000" stroke="#000000" points="1995.0476,-36.6652 1985.1325,-32.9314 1990.5551,-42.0334 1995.0476,-36.6652"/>
<text text-anchor="middle" x="2069.1942" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_personnel -->
<g id="node24" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2943.6942" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2943.6942" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge29" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2886.346,-91.4505C2833.3148,-79.5017 2752.1436,-62.6797 2680.6942,-54 2550.3426,-38.1648 2148.452,-23.9765 2011.1987,-19.478"/>
<polygon fill="#000000" stroke="#000000" points="2011.1285,-15.9739 2001.0198,-19.1463 2010.9005,-22.9702 2011.1285,-15.9739"/>
<text text-anchor="middle" x="2844.1942" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- clinical_measure_file -->
<g id="node25" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="2911.6942" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="2911.6942" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge41" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2943.4407,-174.6954C2957.6728,-164.7894 2969.1582,-152.1507 2958.6942,-141 2937.1334,-118.0243 2707.0039,-126.5288 2675.6942,-123 2485.536,-101.5678 2440.1008,-81.2872 2250.6942,-54 2166.0592,-41.8069 2066.9951,-29.8529 2010.4662,-23.2507"/>
<polygon fill="#000000" stroke="#000000" points="2010.7567,-19.7609 2000.4191,-22.0813 2009.9474,-26.714 2010.7567,-19.7609"/>
<text text-anchor="middle" x="2761.6942" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2814.4695,-183.9626C2777.6168,-178.7451 2735.8494,-170.1505 2699.6942,-156 2688.3296,-151.5521 2688.3355,-144.663 2676.6942,-141 2556.655,-103.2291 2235.3036,-140.5654 2110.6942,-123 2105.2639,-122.2345 2099.6484,-121.2162 2094.0641,-120.0518"/>
<polygon fill="#000000" stroke="#000000" points="2094.6157,-116.5888 2084.0928,-117.8214 2093.0877,-123.42 2094.6157,-116.5888"/>
<text text-anchor="middle" x="2829.1942" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
</g>
</svg>
</div>
