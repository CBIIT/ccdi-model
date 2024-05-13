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
<svg width="2655pt" height="305pt"
 viewBox="0.00 0.00 2655.49 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 2651.493,-301 2651.493,4 -4,4"/>
<!-- diagnosis -->
<g id="node1" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1769.493" cy="-279" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1769.493" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- sample -->
<g id="node3" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2002.493" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2002.493" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1811.2432,-267.1093C1829.4161,-261.1104 1850.6017,-252.9732 1868.493,-243 1877.8905,-237.7616 1877.9791,-233.0238 1887.493,-228 1908.0951,-217.1211 1932.5349,-208.8946 1953.575,-203.0716"/>
<polygon fill="#000000" stroke="#000000" points="1954.5246,-206.4408 1963.2869,-200.4848 1952.7229,-199.6766 1954.5246,-206.4408"/>
<text text-anchor="middle" x="1931.993" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- participant -->
<g id="node14" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1065.493" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1065.493" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1765.3123,-261.0079C1759.2497,-238.3252 1746.077,-199.251 1722.493,-174 1701.1861,-151.187 1690.6454,-149.0781 1660.493,-141 1548.1634,-110.9059 1252.6513,-139.192 1137.493,-123 1131.7713,-122.1955 1125.8448,-121.1205 1119.9609,-119.8945"/>
<polygon fill="#000000" stroke="#000000" points="1120.6641,-116.4654 1110.1426,-117.7097 1119.1436,-123.2983 1120.6641,-116.4654"/>
<text text-anchor="middle" x="1790.993" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- family_relationship -->
<g id="node2" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1046.493" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1046.493" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1047.6077,-173.8867C1048.466,-164.061 1049.9531,-151.7592 1052.493,-141 1053.1295,-138.304 1053.9033,-135.5313 1054.753,-132.7786"/>
<polygon fill="#000000" stroke="#000000" points="1058.1492,-133.6624 1058.0524,-123.068 1051.5213,-131.4104 1058.1492,-133.6624"/>
<text text-anchor="middle" x="1131.993" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1959.3126,-187.829C1916.5173,-182.9385 1849.4448,-173.2222 1793.493,-156 1778.0952,-151.2605 1776.1877,-144.6377 1760.493,-141 1625.5675,-109.7273 1274.6988,-141.9061 1137.493,-123 1131.7691,-122.2113 1125.8412,-121.1466 1119.9564,-119.9267"/>
<polygon fill="#000000" stroke="#000000" points="1120.6578,-116.4973 1110.1371,-117.7487 1119.1419,-123.3312 1120.6578,-116.4973"/>
<text text-anchor="middle" x="1829.993" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node17" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="1861.493" cy="-105" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="1861.493" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge28" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1991.5199,-174.3364C1983.9631,-163.4294 1973.044,-149.8719 1960.493,-141 1951.7261,-134.803 1930.1778,-126.7182 1909.4156,-119.7806"/>
<polygon fill="#000000" stroke="#000000" points="1910.257,-116.3732 1899.6643,-116.5828 1908.0758,-123.0247 1910.257,-116.3732"/>
<text text-anchor="middle" x="2013.993" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node19" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2095.493" cy="-105" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2095.493" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge30" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2043.415,-185.0793C2074.2789,-178.9278 2112.8851,-168.9133 2122.493,-156 2128.9031,-147.3846 2125.212,-137.0429 2118.7547,-127.9309"/>
<polygon fill="#000000" stroke="#000000" points="2121.2998,-125.5144 2112.2573,-119.9932 2115.8831,-129.9483 2121.2998,-125.5144"/>
<text text-anchor="middle" x="2162.993" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- medical_history -->
<g id="node4" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1249.493" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1249.493" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1240.2352,-173.8544C1233.6655,-162.755 1223.8324,-149.1644 1211.493,-141 1183.2647,-122.3226 1170.3563,-131.1047 1137.493,-123 1132.6142,-121.7968 1127.5508,-120.5424 1122.4724,-119.2804"/>
<polygon fill="#000000" stroke="#000000" points="1123.2817,-115.8751 1112.7323,-116.8555 1121.5905,-122.6678 1123.2817,-115.8751"/>
<text text-anchor="middle" x="1295.493" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- survival -->
<g id="node5" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="652.493" cy="-192" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="652.493" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M681.5442,-177.586C706.411,-165.878 743.4804,-149.8978 777.493,-141 849.6933,-122.1121 934.749,-113.0295 993.6188,-108.7286"/>
<polygon fill="#000000" stroke="#000000" points="994.2008,-112.1965 1003.9311,-108.0046 993.7105,-105.2137 994.2008,-112.1965"/>
<text text-anchor="middle" x="816.993" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- study_admin -->
<g id="node6" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1216.493" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1216.493" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study -->
<g id="node8" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1482.493" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1482.493" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge3" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1230.2889,-87.0393C1239.9957,-75.7206 1253.9844,-61.8155 1269.493,-54 1298.0461,-39.6108 1383.0569,-28.4189 1436.6502,-22.5486"/>
<polygon fill="#000000" stroke="#000000" points="1437.0282,-26.0283 1446.5973,-21.4805 1436.2808,-19.0683 1437.0282,-26.0283"/>
<text text-anchor="middle" x="1325.993" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- treatment_response -->
<g id="node7" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="823.493" cy="-192" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="823.493" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M838.6634,-174.1835C849.2435,-162.9256 864.3196,-149.0342 880.493,-141 901.0187,-130.8038 954.4782,-120.9866 998.6812,-114.1868"/>
<polygon fill="#000000" stroke="#000000" points="999.4577,-117.6092 1008.8223,-112.6539 998.4114,-110.6879 999.4577,-117.6092"/>
<text text-anchor="middle" x="963.493" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- study_personnel -->
<g id="node9" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="1391.493" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1391.493" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge19" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1386.7901,-87.0156C1385.123,-76.522 1385.0219,-63.5191 1391.493,-54 1401.8731,-38.7308 1419.8386,-29.938 1437.0792,-24.8745"/>
<polygon fill="#000000" stroke="#000000" points="1438.2694,-28.1825 1447.0835,-22.3035 1436.527,-21.4028 1438.2694,-28.1825"/>
<text text-anchor="middle" x="1460.993" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- sequencing_file -->
<g id="node10" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2561.493" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="2561.493" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2541.4608,-261.2994C2526.9807,-249.6295 2506.3687,-235.2138 2485.493,-228 2407.6351,-201.0953 2166.0317,-194.2863 2056.9343,-192.5721"/>
<polygon fill="#000000" stroke="#000000" points="2056.851,-189.0706 2046.8001,-192.4217 2056.747,-196.0698 2056.851,-189.0706"/>
<text text-anchor="middle" x="2580.993" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- pathology_file -->
<g id="node11" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1937.493" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1937.493" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1962.1278,-261.7126C1968.6917,-256.2702 1975.3728,-249.8696 1980.493,-243 1985.737,-235.9643 1990.0327,-227.4863 1993.3917,-219.4804"/>
<polygon fill="#000000" stroke="#000000" points="1996.6853,-220.6671 1997.0251,-210.0777 1990.1559,-218.1439 1996.6853,-220.6671"/>
<text text-anchor="middle" x="2050.493" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- study_funding -->
<g id="node12" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="1573.493" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="1573.493" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge6" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1561.7362,-86.8853C1554.5673,-76.5971 1544.8173,-63.8471 1534.493,-54 1528.4593,-48.2452 1521.4297,-42.7369 1514.526,-37.8351"/>
<polygon fill="#000000" stroke="#000000" points="1516.1672,-34.7181 1505.9329,-31.9778 1512.2246,-40.5022 1516.1672,-34.7181"/>
<text text-anchor="middle" x="1610.493" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- methylation_array_file -->
<g id="node13" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2147.493" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2147.493" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2139.9182,-260.6449C2134.5649,-249.7485 2126.3979,-236.4533 2115.493,-228 2097.8027,-214.2867 2074.7596,-205.7283 2054.0999,-200.4196"/>
<polygon fill="#000000" stroke="#000000" points="2054.7213,-196.9699 2044.1833,-198.0662 2053.1049,-203.7808 2054.7213,-196.9699"/>
<text text-anchor="middle" x="2220.993" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge22" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1085.8824,-87.7604C1100.8296,-76.1455 1122.157,-61.6059 1143.493,-54 1196.1794,-35.2183 1355.8672,-24.546 1435.8294,-20.2468"/>
<polygon fill="#000000" stroke="#000000" points="1436.2986,-23.727 1446.1008,-19.7061 1435.9306,-16.7367 1436.2986,-23.727"/>
<text text-anchor="middle" x="1193.993" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- cytogenomic_file -->
<g id="node15" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="2370.493" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="2370.493" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2356.5023,-260.7643C2346.6401,-249.3295 2332.3936,-235.3983 2316.493,-228 2271.6189,-207.1207 2134.0612,-197.7911 2056.73,-194.1017"/>
<polygon fill="#000000" stroke="#000000" points="2056.8428,-190.6033 2046.692,-193.6383 2056.5199,-197.5958 2056.8428,-190.6033"/>
<text text-anchor="middle" x="2409.993" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- molecular_test -->
<g id="node16" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="106.493" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="106.493" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M139.2208,-175.5302C164.7447,-163.5657 201.4576,-148.2515 235.493,-141 308.3881,-125.4692 804.6571,-111.549 993.106,-106.7633"/>
<polygon fill="#000000" stroke="#000000" points="993.2822,-110.2601 1003.1905,-106.5085 993.1053,-103.2623 993.2822,-110.2601"/>
<text text-anchor="middle" x="299.493" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1863.7367,-123.3071C1865.9889,-134.1854 1870.4933,-147.4784 1879.493,-156 1890.2601,-166.1951 1923.1573,-175.5327 1952.2221,-182.1421"/>
<polygon fill="#000000" stroke="#000000" points="1951.7813,-185.6289 1962.3003,-184.3631 1953.2879,-178.7929 1951.7813,-185.6289"/>
<text text-anchor="middle" x="1919.993" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge12" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1846.9879,-87.2514C1836.4771,-75.7179 1821.2204,-61.4824 1804.493,-54 1756.4325,-32.5018 1606.4854,-23.1947 1529.355,-19.7448"/>
<polygon fill="#000000" stroke="#000000" points="1529.1149,-16.2312 1518.9731,-19.2962 1528.8126,-23.2247 1529.1149,-16.2312"/>
<text text-anchor="middle" x="1867.993" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- radiology_file -->
<g id="node18" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="512.493" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="512.493" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M538.7637,-175.1497C558.4984,-163.4026 586.6365,-148.5352 613.493,-141 682.7882,-121.5577 883.6915,-111.523 992.8445,-107.3759"/>
<polygon fill="#000000" stroke="#000000" points="993.2512,-110.8632 1003.1137,-106.9928 992.9902,-103.8681 993.2512,-110.8632"/>
<text text-anchor="middle" x="672.493" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2084.7884,-121.7495C2077.5658,-132.2919 2067.3912,-145.7865 2056.493,-156 2050.539,-161.5799 2043.632,-166.8839 2036.7878,-171.6214"/>
<polygon fill="#000000" stroke="#000000" points="2034.6282,-168.8539 2028.2285,-177.2976 2038.4969,-174.6877 2034.6282,-168.8539"/>
<text text-anchor="middle" x="2094.493" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge8" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2083.8902,-88.5188C2074.4949,-76.6318 2060.1202,-61.423 2043.493,-54 1997.1183,-33.2967 1655.2798,-22.4607 1529.1071,-19.1331"/>
<polygon fill="#000000" stroke="#000000" points="1529.0763,-15.6312 1518.9887,-18.8702 1528.8944,-22.6289 1529.0763,-15.6312"/>
<text text-anchor="middle" x="2089.493" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- publication -->
<g id="node20" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="1731.493" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="1731.493" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge10" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1716.9992,-87.1285C1706.8513,-75.8473 1692.3179,-61.9507 1676.493,-54 1651.0597,-41.2218 1576.8978,-29.8635 1527.9878,-23.4662"/>
<polygon fill="#000000" stroke="#000000" points="1528.3254,-19.9809 1517.9608,-22.1777 1527.4331,-26.9238 1528.3254,-19.9809"/>
<text text-anchor="middle" x="1749.493" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- clinical_measure_file -->
<g id="node21" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="312.493" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="312.493" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge26" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M325.5037,-173.7829C334.7324,-162.3559 348.1681,-148.4265 363.493,-141 664.2797,4.7618 778.0996,-89.1242 1110.493,-54 1227.7195,-41.6126 1365.9107,-28.6766 1436.273,-22.2092"/>
<polygon fill="#000000" stroke="#000000" points="1436.9225,-25.6644 1446.5608,-21.2653 1436.2829,-18.6937 1436.9225,-25.6644"/>
<text text-anchor="middle" x="578.493" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M336.0953,-174.1721C353.0486,-162.4438 376.9708,-148.0107 400.493,-141 456.026,-124.4486 832.3908,-111.7432 993.0458,-107.0102"/>
<polygon fill="#000000" stroke="#000000" points="993.4169,-110.501 1003.3103,-106.71 993.2122,-103.504 993.4169,-110.501"/>
<text text-anchor="middle" x="486.493" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- study_arm -->
<g id="node22" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1988.493" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1988.493" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge32" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1969.0617,-87.8599C1954.5436,-76.1326 1933.6355,-61.4142 1912.493,-54 1842.7505,-29.5428 1625.0751,-21.4004 1528.9341,-18.9525"/>
<polygon fill="#000000" stroke="#000000" points="1529.0046,-15.4532 1518.9218,-18.707 1528.833,-22.4511 1529.0046,-15.4532"/>
<text text-anchor="middle" x="1990.993" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- exposure -->
<g id="node23" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1405.493" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1405.493" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1397.2184,-174.1749C1390.834,-162.6072 1380.8339,-148.3623 1367.493,-141 1322.607,-116.2292 1188.0929,-131.2458 1137.493,-123 1132.0088,-122.1063 1126.3291,-121.0029 1120.6754,-119.7858"/>
<polygon fill="#000000" stroke="#000000" points="1121.1014,-116.2935 1110.5747,-117.493 1119.5518,-123.1199 1121.1014,-116.2935"/>
<text text-anchor="middle" x="1427.993" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- synonym -->
<g id="node24" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1494.493" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1494.493" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1540.8531,-270.4539C1597.2155,-260.1218 1695.2534,-242.3358 1779.493,-228 1838.1353,-218.0203 1905.5747,-207.2281 1950.7982,-200.0899"/>
<polygon fill="#000000" stroke="#000000" points="1951.614,-203.5047 1960.9472,-198.4905 1950.5243,-196.59 1951.614,-203.5047"/>
<text text-anchor="middle" x="1821.993" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge15" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1442.1731,-278.5569C1185.2683,-276.1313 67.6715,-262.5773 17.493,-210 -60.6014,-128.1721 128.8973,-103.1708 568.493,-54 739.1368,-34.9127 1273.6916,-22.3841 1435.574,-18.9537"/>
<polygon fill="#000000" stroke="#000000" points="1435.766,-22.4505 1445.6902,-18.7409 1435.6187,-15.452 1435.766,-22.4505"/>
<text text-anchor="middle" x="74.993" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1498.3509,-261.0005C1503.5751,-231.1376 1508.7804,-171.6142 1475.493,-141 1447.8113,-115.5413 1174.6846,-128.5864 1137.493,-123 1131.7791,-122.1417 1125.8577,-121.0318 1119.9769,-119.7848"/>
<polygon fill="#000000" stroke="#000000" points="1120.6863,-116.357 1110.1619,-117.5768 1119.1499,-123.1863 1120.6863,-116.357"/>
<text text-anchor="middle" x="1544.993" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- treatment -->
<g id="node25" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="1655.493" cy="-192" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="1655.493" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1621.8011,-177.2114C1592.4872,-165.1028 1548.5394,-148.7521 1508.493,-141 1346.4189,-109.6261 1300.802,-147.1356 1137.493,-123 1131.7771,-122.1552 1125.8544,-121.0541 1119.9728,-119.8123"/>
<polygon fill="#000000" stroke="#000000" points="1120.6806,-116.3842 1110.1569,-117.6102 1119.1482,-123.2144 1120.6806,-116.3842"/>
<text text-anchor="middle" x="1609.493" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
</g>
</svg>
</div>
