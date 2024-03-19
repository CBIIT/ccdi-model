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
<svg width="3269pt" height="305pt"
 viewBox="0.00 0.00 3268.69 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 3264.6897,-301 3264.6897,4 -4,4"/>
<!-- therapeutic_procedure -->
<g id="node1" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="1896.6897" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="1896.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- participant -->
<g id="node21" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="2099.6897" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="2099.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1895.3812,-173.9812C1895.6163,-162.9325 1897.9463,-149.3506 1906.6897,-141 1926.3488,-122.2241 2001.0272,-128.3029 2027.6897,-123 2032.9816,-121.9475 2038.4686,-120.7577 2043.9455,-119.5037"/>
<polygon fill="#000000" stroke="#000000" points="2044.8183,-122.894 2053.7485,-117.1929 2043.2122,-116.0807 2044.8183,-122.894"/>
<text text-anchor="middle" x="1999.6897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- study_arm -->
<g id="node2" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1041.6897" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1041.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study -->
<g id="node3" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2187.6897" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2187.6897" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge19" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1058.9432,-87.5514C1071.9362,-75.6747 1090.8534,-60.9046 1110.6897,-54 1159.9431,-36.856 1940.688,-22.262 2141.0962,-18.7853"/>
<polygon fill="#000000" stroke="#000000" points="2141.3507,-22.2816 2151.2888,-18.6094 2141.2299,-15.2826 2141.3507,-22.2816"/>
<text text-anchor="middle" x="1159.1897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- cytogenomic_file -->
<g id="node4" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="987.6897" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="987.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- sample -->
<g id="node23" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1047.6897" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1047.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M964.4128,-261.4486C954.2087,-251.5744 946.091,-239.0471 953.6897,-228 959.5676,-219.4547 980.2043,-211.094 1000.6493,-204.584"/>
<polygon fill="#000000" stroke="#000000" points="1001.7495,-207.9077 1010.2893,-201.6369 999.7029,-201.2135 1001.7495,-207.9077"/>
<text text-anchor="middle" x="1025.1897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cell_line -->
<g id="node5" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="1214.6897" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="1214.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge14" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1251.3341,-266.6186C1264.4952,-260.9027 1278.7691,-253.1019 1289.6897,-243 1315.711,-218.9295 1305.4827,-199.8943 1329.6897,-174 1347.6202,-154.8197 1354.2275,-150.5384 1378.6897,-141 1520.5494,-85.6854 1992.0455,-36.7664 2141.6917,-22.3145"/>
<polygon fill="#000000" stroke="#000000" points="2142.2815,-25.774 2151.9011,-21.3339 2141.6122,-18.8061 2142.2815,-25.774"/>
<text text-anchor="middle" x="1419.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1211.1765,-260.9864C1208.1096,-249.9398 1202.5438,-236.3582 1192.6897,-228 1178.602,-216.0508 1135.3013,-206.2537 1099.6574,-199.9131"/>
<polygon fill="#000000" stroke="#000000" points="1099.8106,-196.3879 1089.3613,-198.1377 1098.6211,-203.2861 1099.8106,-196.3879"/>
<text text-anchor="middle" x="1245.1897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- family_relationship -->
<g id="node6" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="2132.6897" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="2132.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2112.5654,-174.3179C2107.7827,-168.9568 2103.3112,-162.6967 2100.6897,-156 2097.9251,-148.9376 2096.8983,-140.8929 2096.7559,-133.3135"/>
<polygon fill="#000000" stroke="#000000" points="2100.2619,-133.1569 2097.0547,-123.0592 2093.2649,-132.953 2100.2619,-133.1569"/>
<text text-anchor="middle" x="2180.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- synonym -->
<g id="node7" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2268.6897" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2268.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge22" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2320.7386,-278.5933C2475.8517,-276.7456 2932.6288,-266.5197 3068.6897,-210 3134.537,-182.647 3214.8491,-143.7567 3171.6897,-87 3138.468,-43.3118 3106.9076,-62.5303 3052.6897,-54 2893.0333,-28.8807 2391.1733,-20.5595 2234.7345,-18.5404"/>
<polygon fill="#000000" stroke="#000000" points="2234.5499,-15.0379 2224.5065,-18.411 2234.4614,-22.0373 2234.5499,-15.0379"/>
<text text-anchor="middle" x="3218.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2270.1064,-260.9549C2272.3127,-227.6707 2274.8766,-158.4178 2259.6897,-141 2233.4543,-110.9105 2210.6189,-131.8432 2171.6897,-123 2166.713,-121.8695 2161.5526,-120.6579 2156.3846,-119.4174"/>
<polygon fill="#000000" stroke="#000000" points="2157.0269,-115.9716 2146.4831,-117.0098 2155.373,-122.7734 2157.0269,-115.9716"/>
<text text-anchor="middle" x="2314.1897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2217.3927,-275.3449C2019.0846,-261.2149 1303.6349,-210.2369 1101.3224,-195.8215"/>
<polygon fill="#000000" stroke="#000000" points="1101.4639,-192.3228 1091.2404,-195.1031 1100.9663,-199.3051 1101.4639,-192.3228"/>
<text text-anchor="middle" x="1773.1897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study_funding -->
<g id="node8" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="1941.6897" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="1941.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge28" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1949.0949,-87.0796C1954.7118,-75.7779 1963.5486,-61.8766 1975.6897,-54 2002.3908,-36.6775 2087.5731,-26.4598 2141.4874,-21.5673"/>
<polygon fill="#000000" stroke="#000000" points="2141.8429,-25.0496 2151.498,-20.6872 2141.2298,-18.0765 2141.8429,-25.0496"/>
<text text-anchor="middle" x="2037.6897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- molecular_test -->
<g id="node9" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="2451.6897" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="2451.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2404.1216,-177.4866C2382.8619,-170.9685 2357.5043,-163.1503 2334.6897,-156 2313.7664,-149.4424 2309.032,-146.0295 2287.6897,-141 2236.9082,-129.0328 2222.8279,-133.3376 2171.6897,-123 2166.6104,-121.9732 2161.35,-120.8248 2156.0907,-119.6183"/>
<polygon fill="#000000" stroke="#000000" points="2156.5627,-116.1336 2146.0261,-117.2432 2154.9549,-122.9465 2156.5627,-116.1336"/>
<text text-anchor="middle" x="2398.6897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- pathology_file -->
<g id="node10" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="325.6897" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="325.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M356.4954,-262.2864C379.9449,-250.4448 413.4105,-235.3985 444.6897,-228 547.9276,-203.5812 864.5934,-195.2742 992.8731,-192.864"/>
<polygon fill="#000000" stroke="#000000" points="993.302,-196.3568 1003.2363,-192.6744 993.1739,-189.358 993.302,-196.3568"/>
<text text-anchor="middle" x="505.6897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pdx -->
<g id="node11" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1147.6897" cy="-105" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1147.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge3" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1167.1785,-91.9493C1186.8127,-79.5972 1218.4507,-61.8167 1248.6897,-54 1335.3651,-31.5947 1963.7462,-21.1446 2141.1593,-18.6203"/>
<polygon fill="#000000" stroke="#000000" points="2141.2672,-22.1193 2151.217,-18.4789 2141.1687,-15.1199 2141.2672,-22.1193"/>
<text text-anchor="middle" x="1272.6897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1125.6569,-116.4764C1120.7952,-118.7944 1115.6226,-121.1 1110.6897,-123 1083.914,-133.3135 1066.144,-118.226 1048.6897,-141 1043.8203,-147.3535 1042.2649,-155.5785 1042.2903,-163.5614"/>
<polygon fill="#000000" stroke="#000000" points="1038.8172,-164.0426 1043.0885,-173.7383 1045.7958,-163.4952 1038.8172,-164.0426"/>
<text text-anchor="middle" x="1072.6897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- diagnosis -->
<g id="node12" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="2604.6897" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="2604.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2563.5208,-180.1689C2532.095,-171.0328 2492.9783,-159.3943 2485.6897,-156 2474.6266,-150.8479 2474.2748,-144.8371 2462.6897,-141 2401.1853,-120.629 2235.7194,-132.8985 2171.6897,-123 2166.1984,-122.1511 2160.514,-121.0774 2154.8574,-119.8787"/>
<polygon fill="#000000" stroke="#000000" points="2155.2774,-116.3859 2144.7532,-117.6077 2153.7423,-123.2155 2155.2774,-116.3859"/>
<text text-anchor="middle" x="2530.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- radiology_file -->
<g id="node13" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="2750.6897" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="2750.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2695.702,-180.034C2655.6552,-171.1544 2606.8774,-159.9333 2597.6897,-156 2586.4706,-151.197 2586.3073,-144.7377 2574.6897,-141 2489.3527,-113.5448 2260.3963,-135.9359 2171.6897,-123 2165.9722,-122.1662 2160.0485,-121.0722 2154.1662,-119.8348"/>
<polygon fill="#000000" stroke="#000000" points="2154.8727,-116.4064 2144.3497,-117.6374 2153.3436,-123.2373 2154.8727,-116.4064"/>
<text text-anchor="middle" x="2656.6897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- exposure -->
<g id="node14" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1391.6897" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1391.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1418.7472,-176.2934C1441.2104,-164.154 1474.4278,-148.2396 1505.6897,-141 1618.7662,-114.814 1912.7519,-139.1649 2027.6897,-123 2033.4114,-122.1953 2039.3379,-121.1202 2045.2218,-119.8941"/>
<polygon fill="#000000" stroke="#000000" points="2046.0392,-123.2979 2055.0401,-117.7092 2044.5186,-116.465 2046.0392,-123.2979"/>
<text text-anchor="middle" x="1549.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- medical_history -->
<g id="node15" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1547.6897" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1547.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1568.2404,-174.3574C1583.332,-162.5525 1604.9176,-147.9516 1626.6897,-141 1711.6643,-113.8687 1939.4239,-135.8816 2027.6897,-123 2033.4072,-122.1656 2039.3308,-121.0712 2045.2131,-119.8335"/>
<polygon fill="#000000" stroke="#000000" points="2046.0358,-123.236 2055.0296,-117.6358 2044.5065,-116.4051 2046.0358,-123.236"/>
<text text-anchor="middle" x="1694.6897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- study_admin -->
<g id="node16" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="2250.6897" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2250.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge7" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2239.8969,-87.1814C2233.6841,-77.2235 2225.5668,-64.7016 2217.6897,-54 2214.9573,-50.2878 2211.965,-46.4555 2208.9616,-42.738"/>
<polygon fill="#000000" stroke="#000000" points="2211.5328,-40.355 2202.4656,-34.8745 2206.1361,-44.8132 2211.5328,-40.355"/>
<text text-anchor="middle" x="2283.1897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- follow_up -->
<g id="node17" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="1705.6897" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="1705.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1730.3084,-175.6394C1749.4565,-163.8156 1777.1464,-148.633 1803.6897,-141 1899.6762,-113.3974 1929.1304,-139.1666 2027.6897,-123 2033.173,-122.1006 2038.8521,-120.9934 2044.5054,-119.774"/>
<polygon fill="#000000" stroke="#000000" points="2045.63,-123.1077 2054.6056,-117.4784 2044.0786,-116.2818 2045.63,-123.1077"/>
<text text-anchor="middle" x="1848.6897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- methylation_array_file -->
<g id="node18" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="115.6897" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="115.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M142.1344,-261.3527C161.3724,-249.5457 188.5279,-234.944 214.6897,-228 289.4563,-208.1551 820.1426,-196.3512 993.2407,-192.9961"/>
<polygon fill="#000000" stroke="#000000" points="993.4635,-196.4926 1003.3944,-192.8011 993.329,-189.4939 993.4635,-196.4926"/>
<text text-anchor="middle" x="306.1897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node19" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="557.6897" cy="-279" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="557.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M562.0612,-260.8325C565.8112,-249.4264 572.4464,-235.5017 583.6897,-228 617.0853,-205.7179 878.3043,-196.3351 993.4655,-193.2529"/>
<polygon fill="#000000" stroke="#000000" points="993.5782,-196.7512 1003.4832,-192.9908 993.395,-189.7536 993.5782,-196.7512"/>
<text text-anchor="middle" x="692.1897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- study_personnel -->
<g id="node20" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2425.6897" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2425.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2402.4202,-87.6238C2386.5895,-76.5518 2364.764,-62.7022 2343.6897,-54 2307.8733,-39.2104 2264.8024,-29.8526 2233.0001,-24.3967"/>
<polygon fill="#000000" stroke="#000000" points="2233.5309,-20.937 2223.0941,-22.7604 2232.39,-27.8434 2233.5309,-20.937"/>
<text text-anchor="middle" x="2441.1897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge12" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2100.5662,-86.7751C2101.9267,-76.1961 2105.1614,-63.1882 2112.6897,-54 2121.2972,-43.4949 2133.7001,-35.85 2145.9491,-30.3816"/>
<polygon fill="#000000" stroke="#000000" points="2147.2747,-33.6209 2155.2205,-26.6127 2144.6386,-27.1362 2147.2747,-33.6209"/>
<text text-anchor="middle" x="2163.1897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- publication -->
<g id="node22" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="3099.6897" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="3099.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge20" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3053.3709,-92.7227C3005.5074,-80.6029 2928.4457,-62.6652 2860.6897,-54 2739.2128,-38.4646 2366.4095,-24.265 2234.5221,-19.6041"/>
<polygon fill="#000000" stroke="#000000" points="2234.4637,-16.1 2224.3469,-19.2466 2234.2178,-23.0957 2234.4637,-16.1"/>
<text text-anchor="middle" x="2997.6897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge17" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1069.7632,-207.9676C1078.2321,-214.159 1087.9565,-221.3477 1096.6897,-228 1105.2484,-234.5193 1106.2923,-237.7616 1115.6897,-243 1131.1674,-251.6277 1149.1105,-258.8815 1165.4357,-264.5654"/>
<polygon fill="#000000" stroke="#000000" points="1164.7609,-268.031 1175.3549,-267.8999 1166.9914,-261.3959 1164.7609,-268.031"/>
<text text-anchor="middle" x="1152.1897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge15" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1070.6836,-176.2062C1079.0827,-170.1544 1088.5209,-163.0145 1096.6897,-156 1106.7834,-147.3327 1117.2837,-137.0748 1126.1143,-128.0396"/>
<polygon fill="#000000" stroke="#000000" points="1128.6733,-130.4281 1133.0938,-120.7995 1123.6337,-125.5699 1128.6733,-130.4281"/>
<text text-anchor="middle" x="1150.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1088.4629,-185.0508C1117.6404,-179.289 1157.4696,-169.7922 1190.6897,-156 1202.657,-151.0315 1203.2413,-144.597 1215.6897,-141 1302.3873,-115.9484 1938.2492,-135.0182 2027.6897,-123 2033.4981,-122.2195 2039.5153,-121.1482 2045.4839,-119.9139"/>
<polygon fill="#000000" stroke="#000000" points="2046.4326,-123.2886 2055.4371,-117.7056 2044.9163,-116.4548 2046.4326,-123.2886"/>
<text text-anchor="middle" x="1252.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- clinical_measure_file -->
<g id="node24" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="2950.6897" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="2950.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge31" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2940.9495,-174.0063C2933.9728,-162.8225 2923.5525,-149.0818 2910.6897,-141 2891.6173,-129.0166 2536.916,-57.6543 2514.6897,-54 2415.3932,-37.6743 2297.8829,-26.7682 2234.2653,-21.5549"/>
<polygon fill="#000000" stroke="#000000" points="2234.4036,-18.0547 2224.154,-20.7372 2233.8393,-25.0319 2234.4036,-18.0547"/>
<text text-anchor="middle" x="2926.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2872.4723,-179.4809C2814.7369,-170.1168 2745.1103,-158.5129 2738.6897,-156 2727.3251,-151.5521 2727.3287,-144.6705 2715.6897,-141 2600.3349,-104.6216 2291.4777,-139.7619 2171.6897,-123 2165.9675,-122.1993 2160.0407,-121.1268 2154.1566,-119.9022"/>
<polygon fill="#000000" stroke="#000000" points="2154.8593,-116.4731 2144.338,-117.7191 2153.3399,-123.3062 2154.8593,-116.4731"/>
<text text-anchor="middle" x="2824.6897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- sequencing_file -->
<g id="node25" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="796.6897" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="796.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge24" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M798.459,-260.7642C800.5275,-249.6289 805.0053,-236.0321 814.6897,-228 841.159,-206.047 933.261,-197.403 993.4345,-194.0546"/>
<polygon fill="#000000" stroke="#000000" points="993.7352,-197.5437 1003.5383,-193.5251 993.3688,-190.5533 993.7352,-197.5437"/>
<text text-anchor="middle" x="881.1897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
</g>
</svg>
</div>
