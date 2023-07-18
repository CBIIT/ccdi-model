<link rel='stylesheet' href="assets/style.css">
<link rel='stylesheet' href="https://unpkg.com/leaflet@1.5.1/dist/leaflet.css" integrity="sha512-xwE/Az9zrjBIphAcBb3F6JVqxf46+CDLwfLMHloNu6KEQCAWi6HcDUbeOfBIptF7tcCzusKFjFw2yuvEpDL9wQ==" crossorigin="">
<script type="text/javascript" src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
<script type="text/javascript"  src="https://unpkg.com/leaflet@1.5.1/dist/leaflet.js"></script>
<script type="text/javascript" src="assets/actions.js"></script>

![Build Status](https://github.com/CBIIT/ccdi-model/actions/workflows/model-test-and-deploy.yml/badge.svg)

# Children's Cancer Data Initiative Draft Model

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
<svg width="2954pt" height="392pt"
 viewBox="0.00 0.00 2953.69 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 2949.6867,-388 2949.6867,4 -4,4"/>
<!-- clinical_measure_file -->
<g id="node1" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="124.6867" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="124.6867" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- participant -->
<g id="node11" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1319.6867" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1319.6867" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M130.2258,-173.7793C134.7915,-162.195 142.5283,-148.0873 154.6867,-141 207.202,-110.3881 1188.4325,-131.0228 1248.6867,-123 1254.2015,-122.2657 1259.9049,-121.2567 1265.5715,-120.0883"/>
<polygon fill="#000000" stroke="#000000" points="1266.6821,-123.4268 1275.6829,-117.8379 1265.1614,-116.594 1266.6821,-123.4268"/>
<text text-anchor="middle" x="284.1867" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- study -->
<g id="node15" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1876.6867" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1876.6867" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge32" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M123.9312,-173.9278C124.5146,-162.7119 127.3406,-148.9648 136.6867,-141 341.7008,33.7134 1076.9806,-72.7767 1345.6867,-54 1524.7476,-41.4876 1737.8217,-27.2348 1830.1775,-21.0881"/>
<polygon fill="#000000" stroke="#000000" points="1830.5632,-24.5703 1840.3088,-20.4141 1830.0985,-17.5857 1830.5632,-24.5703"/>
<text text-anchor="middle" x="320.6867" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- study_arm -->
<g id="node2" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1179.6867" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1179.6867" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge31" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1223.6991,-92.7978C1231.9662,-90.711 1240.5636,-88.6783 1248.6867,-87 1463.1343,-42.6934 1725.0405,-25.5282 1829.9611,-20.1179"/>
<polygon fill="#000000" stroke="#000000" points="1830.3962,-23.6005 1840.2073,-19.6014 1830.0437,-16.6093 1830.3962,-23.6005"/>
<text text-anchor="middle" x="1485.1867" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- cell_line -->
<g id="node3" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2271.6867" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2271.6867" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2226.5934,-271.4323C2205.1517,-267.9801 2179.1359,-264.0028 2155.6867,-261 2076.8162,-250.9002 2054.8493,-262.1964 1977.6867,-243 1939.9636,-233.6153 1930.2107,-229.6787 1896.6867,-210 1874.5986,-197.0342 1873.0357,-188.15 1851.6867,-174 1825.9937,-156.9708 1820.258,-149.6986 1790.6867,-141 1718.1118,-119.6514 1505.5232,-110.3763 1392.4195,-106.8603"/>
<polygon fill="#000000" stroke="#000000" points="1392.2265,-103.353 1382.1249,-106.5477 1392.014,-110.3497 1392.2265,-103.353"/>
<text text-anchor="middle" x="1937.1867" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge12" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2235.8978,-266.3676C2146.4069,-234.475 1918.4405,-151.2375 1895.6867,-123 1878.3273,-101.4568 1874.7559,-69.3137 1874.7932,-46.2706"/>
<polygon fill="#000000" stroke="#000000" points="1878.2967,-46.1679 1875.042,-36.0854 1871.2988,-45.9969 1878.2967,-46.1679"/>
<text text-anchor="middle" x="1992.1867" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node4" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1962.6867" cy="-366" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="1962.6867" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge1" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2095.6786,-361.2307C2244.7965,-355.22 2467.6576,-343.9661 2480.6867,-330 2485.2344,-325.1253 2484.9821,-320.0985 2480.6867,-315 2470.9659,-303.4616 2388.0147,-291.9406 2329.5924,-285.1448"/>
<polygon fill="#000000" stroke="#000000" points="2329.6888,-281.633 2319.3555,-283.9728 2328.8925,-288.5876 2329.6888,-281.633"/>
<text text-anchor="middle" x="2592.1867" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- sample -->
<g id="node16" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1798.6867" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1798.6867" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1960.4873,-347.8925C1958.5875,-337.6066 1955.0875,-324.8566 1948.6867,-315 1919.3903,-269.886 1868.2581,-233.1853 1833.9431,-211.9618"/>
<polygon fill="#000000" stroke="#000000" points="1835.5404,-208.8373 1825.1743,-206.6479 1831.9126,-214.8238 1835.5404,-208.8373"/>
<text text-anchor="middle" x="2043.1867" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- pdx -->
<g id="node17" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1730.6867" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1730.6867" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge2" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1852.2907,-355.1829C1797.0811,-348.6419 1740.1637,-339.7062 1731.6867,-330 1726.28,-323.8093 1724.6622,-315.4039 1724.7967,-307.2034"/>
<polygon fill="#000000" stroke="#000000" points="1728.2943,-307.3929 1725.7509,-297.1079 1721.3254,-306.7342 1728.2943,-307.3929"/>
<text text-anchor="middle" x="1840.1867" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- study_funding -->
<g id="node5" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="1981.6867" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="1981.6867" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge9" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1960.6908,-87.6033C1944.187,-73.9288 1921.0921,-54.793 1903.2938,-40.0458"/>
<polygon fill="#000000" stroke="#000000" points="1905.4649,-37.2994 1895.5315,-33.6143 1900.9987,-42.6896 1905.4649,-37.2994"/>
<text text-anchor="middle" x="1996.6867" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- publication -->
<g id="node6" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="2139.6867" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="2139.6867" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge5" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2118.7442,-87.8194C2103.9438,-76.5394 2083.1686,-62.3735 2062.6867,-54 2017.3262,-35.4554 1961.7625,-26.3026 1923.237,-21.8911"/>
<polygon fill="#000000" stroke="#000000" points="1923.1633,-18.3629 1912.8452,-20.7687 1922.4115,-25.3224 1923.1633,-18.3629"/>
<text text-anchor="middle" x="2139.6867" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- synonym -->
<g id="node7" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1234.6867" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1234.6867" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1250.4955,-261.689C1262.4529,-249.8788 1279.9667,-235.1318 1298.6867,-228 1332.5873,-215.0849 1598.795,-235.41 1624.6867,-210 1646.6107,-188.4839 1649.1123,-163.9434 1628.6867,-141 1613.1633,-123.563 1477.6514,-113.2579 1391.3144,-108.4051"/>
<polygon fill="#000000" stroke="#000000" points="1391.4781,-104.9089 1381.3009,-107.8542 1391.0935,-111.8983 1391.4781,-104.9089"/>
<text text-anchor="middle" x="1684.1867" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge8" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1182.7021,-278.0496C954.1003,-273.6219 47.6919,-253.3739 6.6867,-210 -4.305,-198.3733 .6777,-188.8287 6.6867,-174 61.3954,-38.9937 167.0852,-71.6108 311.6867,-54 465.3686,-35.2833 1585.3515,-21.3644 1829.6939,-18.5308"/>
<polygon fill="#000000" stroke="#000000" points="1830.0457,-22.027 1840.0046,-18.4118 1829.9649,-15.0275 1830.0457,-22.027"/>
<text text-anchor="middle" x="64.1867" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1261.566,-263.4856C1272.2503,-257.2281 1284.6121,-249.8745 1295.6867,-243 1306.0555,-236.5637 1307.0654,-231.726 1318.6867,-228 1408.0681,-199.3426 1648.2051,-226.0441 1740.6867,-210 1745.4977,-209.1654 1750.4662,-208.0436 1755.3778,-206.766"/>
<polygon fill="#000000" stroke="#000000" points="1756.6352,-210.048 1765.3108,-203.9664 1754.7363,-203.3105 1756.6352,-210.048"/>
<text text-anchor="middle" x="1361.1867" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- therapeutic_procedure -->
<g id="node8" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="368.6867" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="368.6867" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M388.8923,-174.2087C403.7529,-162.3339 425.0523,-147.7103 446.6867,-141 531.8193,-114.5948 1160.3686,-135.0288 1248.6867,-123 1254.1992,-122.2492 1259.9012,-121.2293 1265.567,-120.0542"/>
<polygon fill="#000000" stroke="#000000" points="1266.6807,-123.3918 1275.6773,-117.7961 1265.1548,-116.5601 1266.6807,-123.3918"/>
<text text-anchor="middle" x="539.6867" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- radiology_file -->
<g id="node9" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="577.6867" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="577.6867" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M602.0424,-175.0145C620.7066,-163.0341 647.6047,-147.9332 673.6867,-141 797.2365,-108.1577 1122.0934,-140.8129 1248.6867,-123 1254.1172,-122.2359 1259.7328,-121.2184 1265.3172,-120.0546"/>
<polygon fill="#000000" stroke="#000000" points="1266.2934,-123.4229 1275.2886,-117.8249 1264.7658,-116.5916 1266.2934,-123.4229"/>
<text text-anchor="middle" x="732.6867" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- study_admin -->
<g id="node10" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="2290.6867" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2290.6867" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge21" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2265.3617,-88.1403C2246.6455,-76.5487 2220.1044,-61.8774 2194.6867,-54 2145.1405,-38.6447 1998.7009,-26.5376 1923.0668,-21.109"/>
<polygon fill="#000000" stroke="#000000" points="1923.1041,-17.603 1912.8818,-20.3877 1922.6096,-24.5855 1923.1041,-17.603"/>
<text text-anchor="middle" x="2286.1867" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge29" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1374.6184,-96.42C1484.7368,-79.2202 1730.5815,-40.8207 1831.8112,-25.0093"/>
<polygon fill="#000000" stroke="#000000" points="1832.3778,-28.4633 1841.7178,-23.4619 1831.2975,-21.5472 1832.3778,-28.4633"/>
<text text-anchor="middle" x="1681.1867" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- methylation_array_file -->
<g id="node12" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1544.6867" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1544.6867" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge33" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1649.5316,-358.371C1699.7793,-354.8849 1760.8308,-350.8969 1815.6867,-348 1841.1708,-346.6542 2256.9987,-348.3952 2274.6867,-330 2280.5432,-323.9093 2281.6255,-315.2891 2280.6758,-306.8655"/>
<polygon fill="#000000" stroke="#000000" points="2284.0723,-305.9995 2278.694,-296.8713 2277.206,-307.3611 2284.0723,-305.9995"/>
<text text-anchor="middle" x="2372.1867" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge34" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1528.0123,-348.0554C1523.7281,-342.6026 1519.5308,-336.3609 1516.6867,-330 1504.1223,-301.8986 1491.5351,-285.0992 1510.6867,-261 1573.1335,-182.4209 1633.2717,-234.1783 1730.6867,-210 1737.4556,-208.32 1744.5886,-206.4937 1751.5863,-204.6701"/>
<polygon fill="#000000" stroke="#000000" points="1752.9013,-207.9435 1761.6838,-202.0175 1751.1227,-201.1732 1752.9013,-207.9435"/>
<text text-anchor="middle" x="1602.1867" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge35" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1529.4774,-347.7684C1522.5515,-337.1871 1517.5243,-324.179 1525.6867,-315 1548.436,-289.4174 1645.3165,-304.6438 1678.6867,-297 1684.6523,-295.6335 1690.8886,-293.8237 1696.8864,-291.8781"/>
<polygon fill="#000000" stroke="#000000" points="1698.3385,-295.0805 1706.6654,-288.5298 1696.0708,-288.4579 1698.3385,-295.0805"/>
<text text-anchor="middle" x="1617.1867" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study_personnel -->
<g id="node13" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2465.6867" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2465.6867" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge26" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2434.3503,-88.1928C2410.9077,-76.4671 2377.6843,-61.6076 2346.6867,-54 2267.2547,-34.5053 2025.3279,-23.5061 1923.0845,-19.6208"/>
<polygon fill="#000000" stroke="#000000" points="1923.1808,-16.1221 1913.0569,-19.2456 1922.919,-23.1172 1923.1808,-16.1221"/>
<text text-anchor="middle" x="2459.1867" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- sequencing_file -->
<g id="node14" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1327.6867" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1327.6867" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge25" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1385.8632,-353.0917C1397.0381,-351.046 1408.6859,-349.2092 1419.6867,-348 1496.914,-339.5113 2045.6255,-356.4228 2118.6867,-330 2128.8043,-326.341 2128.072,-319.8281 2137.6867,-315 2162.2831,-302.6487 2191.6167,-294.1514 2216.5593,-288.5283"/>
<polygon fill="#000000" stroke="#000000" points="2217.557,-291.8937 2226.595,-286.3652 2216.082,-285.0508 2217.557,-291.8937"/>
<text text-anchor="middle" x="2204.1867" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge24" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1328.6207,-347.8147C1330.8559,-324.1796 1338.3901,-283.3022 1363.6867,-261 1390.7554,-237.1356 1486.9816,-233.2314 1522.6867,-228 1614.4965,-214.5482 1639.2747,-225.9313 1730.6867,-210 1737.9654,-208.7315 1745.6016,-207.0572 1753.0198,-205.2398"/>
<polygon fill="#000000" stroke="#000000" points="1754.1275,-208.5692 1762.9465,-202.6975 1752.3908,-201.788 1754.1275,-208.5692"/>
<text text-anchor="middle" x="1430.1867" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge23" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1341.5358,-348.2374C1351.7873,-336.539 1366.8501,-322.1149 1383.6867,-315 1444.1842,-289.4347 1614.2808,-309.8609 1678.6867,-297 1684.7484,-295.7896 1691.0677,-294.0412 1697.1272,-292.104"/>
<polygon fill="#000000" stroke="#000000" points="1698.6614,-295.2783 1706.9884,-288.7275 1696.3938,-288.6557 1698.6614,-295.2783"/>
<text text-anchor="middle" x="1450.1867" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1769.5509,-178.2688C1743.0672,-166.4116 1702.6041,-149.8358 1665.6867,-141 1572.8971,-118.7919 1462.8646,-110.2838 1392.2075,-107.0242"/>
<polygon fill="#000000" stroke="#000000" points="1392.2188,-103.5215 1382.0752,-106.5804 1391.9124,-110.5148 1392.2188,-103.5215"/>
<text text-anchor="middle" x="1750.1867" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1743.477,-262.636C1753.4468,-249.8805 1767.4677,-231.942 1778.8848,-217.3348"/>
<polygon fill="#000000" stroke="#000000" points="1781.8553,-219.2178 1785.2559,-209.1835 1776.3401,-214.907 1781.8553,-219.2178"/>
<text text-anchor="middle" x="1792.6867" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- follow_up -->
<g id="node18" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="724.6867" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="724.6867" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M751.9596,-176.1237C774.2178,-164.0598 806.9084,-148.3321 837.6867,-141 1015.5513,-98.6289 1067.791,-149.6054 1248.6867,-123 1254.1123,-122.202 1259.7247,-121.1621 1265.3071,-119.9844"/>
<polygon fill="#000000" stroke="#000000" points="1266.29,-123.3508 1275.2761,-117.7382 1264.7513,-116.522 1266.29,-123.3508"/>
<text text-anchor="middle" x="882.6867" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- family_relationship -->
<g id="node19" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="897.6867" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="897.6867" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M912.3926,-173.9805C923.0638,-162.326 938.5816,-148.0574 955.6867,-141 1015.9896,-116.1198 1184.2331,-133.0594 1248.6867,-123 1254.0265,-122.1666 1259.5502,-121.1138 1265.0495,-119.9375"/>
<polygon fill="#000000" stroke="#000000" points="1265.8996,-123.3336 1274.877,-117.7073 1264.3503,-116.5072 1265.8996,-123.3336"/>
<text text-anchor="middle" x="1035.1867" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- molecular_test -->
<g id="node20" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1095.6867" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1095.6867" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1105.4621,-174.0055C1112.5924,-162.6724 1123.3288,-148.7641 1136.6867,-141 1180.2752,-115.6647 1199.3138,-133.2049 1248.6867,-123 1253.6193,-121.9805 1258.7253,-120.8455 1263.8328,-119.6553"/>
<polygon fill="#000000" stroke="#000000" points="1264.7015,-123.0463 1273.6117,-117.314 1263.0716,-116.2387 1264.7015,-123.0463"/>
<text text-anchor="middle" x="1200.6867" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- diagnosis -->
<g id="node21" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1248.6867" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1248.6867" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1257.8391,-174.1585C1263.4733,-163.9613 1271.2233,-151.2113 1279.6867,-141 1283.0292,-136.9673 1286.826,-132.9744 1290.7179,-129.1972"/>
<polygon fill="#000000" stroke="#000000" points="1293.2655,-131.6082 1298.2249,-122.2457 1288.5095,-126.472 1293.2655,-131.6082"/>
<text text-anchor="middle" x="1324.1867" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- medical_history -->
<g id="node22" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1406.6867" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1406.6867" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1395.2073,-173.9701C1388.2141,-163.7102 1378.7141,-150.9602 1368.6867,-141 1364.0668,-136.411 1358.8281,-131.9432 1353.5372,-127.8048"/>
<polygon fill="#000000" stroke="#000000" points="1355.3625,-124.7989 1345.2614,-121.6024 1351.1645,-130.4004 1355.3625,-124.7989"/>
<text text-anchor="middle" x="1448.6867" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- exposure -->
<g id="node23" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1562.6867" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1562.6867" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1552.5274,-174.0818C1545.1617,-162.781 1534.1496,-148.88 1520.6867,-141 1498.6466,-128.0997 1437.7511,-118.3173 1388.716,-112.2294"/>
<polygon fill="#000000" stroke="#000000" points="1389.1152,-108.7522 1378.7668,-111.0239 1388.2732,-115.7014 1389.1152,-108.7522"/>
<text text-anchor="middle" x="1581.1867" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- pathology_file -->
<g id="node24" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2742.6867" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2742.6867" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge18" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2734.2613,-347.9438C2727.8661,-336.4309 2717.9132,-322.3411 2704.6867,-315 2672.7875,-297.295 2441.8192,-285.7903 2330.874,-281.2258"/>
<polygon fill="#000000" stroke="#000000" points="2330.9778,-277.7272 2320.844,-280.8186 2330.6938,-284.7215 2330.9778,-277.7272"/>
<text text-anchor="middle" x="2781.6867" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2804.7424,-355.5882C2836.2301,-347.6813 2864.4351,-334.7388 2846.6867,-315 2699.3561,-151.147 2076.8894,-252.5501 1860.6867,-210 1854.9801,-208.8769 1849.0396,-207.4695 1843.1944,-205.9393"/>
<polygon fill="#000000" stroke="#000000" points="1844.0756,-202.5518 1833.5056,-203.2765 1842.2206,-209.3015 1844.0756,-202.5518"/>
<text text-anchor="middle" x="2884.6867" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge20" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2666.5921,-365.3367C2502.4538,-363.4191 2119.7202,-356.1966 1992.6867,-330 1974.0913,-326.1653 1971.0364,-319.8768 1952.6867,-315 1889.1059,-298.102 1813.051,-287.8527 1768.4848,-282.8202"/>
<polygon fill="#000000" stroke="#000000" points="1768.7191,-279.325 1758.3961,-281.7097 1767.9531,-286.2829 1768.7191,-279.325"/>
<text text-anchor="middle" x="2053.6867" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
</g>
</svg>
</div>
