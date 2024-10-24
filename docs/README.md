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
<svg width="3031pt" height="305pt"
 viewBox="0.00 0.00 3030.61 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 3026.6067,-301 3026.6067,4 -4,4"/>
<!-- pdx -->
<g id="node1" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2543.5145" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2543.5145" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample -->
<g id="node3" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2154.5145" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2154.5145" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2527.9574,-263.9226C2513.7046,-250.4656 2493.3708,-232.2458 2483.5145,-228 2435.4728,-207.3055 2289.344,-197.8375 2208.9552,-194.0951"/>
<polygon fill="#000000" stroke="#000000" points="2208.6873,-190.5796 2198.5397,-193.6252 2208.3718,-197.5724 2208.6873,-190.5796"/>
<text text-anchor="middle" x="2527.5145" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study -->
<g id="node8" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="966.5145" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="966.5145" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge27" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2564.9064,-266.9616C2569.8946,-264.6195 2575.2815,-262.4457 2580.5145,-261 2625.2341,-248.6451 2757.1543,-277.1912 2788.5145,-243 2793.0207,-238.0869 2792.6524,-233.2271 2788.5145,-228 2637.0837,-36.7115 1948.0729,-68.2081 1704.5145,-54 1443.1571,-38.7536 1129.4702,-24.9363 1013.0023,-19.9597"/>
<polygon fill="#000000" stroke="#000000" points="1013.1428,-16.4626 1003.0027,-19.5334 1012.8446,-23.4562 1013.1428,-16.4626"/>
<text text-anchor="middle" x="2707.5145" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study_arm -->
<g id="node2" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="653.5145" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="653.5145" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge20" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M672.1994,-87.7472C685.7134,-76.2827 704.9652,-61.9284 724.5145,-54 759.1194,-39.9655 860.3485,-28.2272 920.3587,-22.2514"/>
<polygon fill="#000000" stroke="#000000" points="920.7283,-25.7321 930.339,-21.2728 920.0452,-18.7655 920.7283,-25.7321"/>
<text text-anchor="middle" x="773.0145" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge32" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2198.6972,-192.6899C2297.7692,-194.6948 2530.8761,-202.1386 2554.5145,-228 2560.5529,-234.6063 2560.291,-243.711 2557.6928,-252.4011"/>
<polygon fill="#000000" stroke="#000000" points="2554.3678,-251.2935 2553.9779,-261.8811 2560.8852,-253.8475 2554.3678,-251.2935"/>
<text text-anchor="middle" x="2595.0145" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- participant -->
<g id="node6" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1268.5145" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1268.5145" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2120.1294,-180.69C2099.7749,-173.848 2073.547,-164.7753 2050.5145,-156 2034.3169,-149.8288 2031.4243,-144.8081 2014.5145,-141 1950.0597,-126.4847 1515.3783,-112.2633 1340.8389,-107.0684"/>
<polygon fill="#000000" stroke="#000000" points="1340.8222,-103.5665 1330.7229,-106.7688 1340.6149,-110.5634 1340.8222,-103.5665"/>
<text text-anchor="middle" x="2087.0145" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node25" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2132.5145" cy="-105" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2132.5145" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge34" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2139.4559,-174.8316C2135.4238,-169.2089 2131.6066,-162.6806 2129.5145,-156 2127.2804,-148.8663 2126.8425,-140.902 2127.2603,-133.4272"/>
<polygon fill="#000000" stroke="#000000" points="2130.7577,-133.6348 2128.3225,-123.3236 2123.796,-132.9028 2130.7577,-133.6348"/>
<text text-anchor="middle" x="2166.0145" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_funding -->
<g id="node4" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="808.5145" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="808.5145" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge35" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M815.0321,-87.0168C819.9032,-75.9822 827.6117,-62.4028 838.5145,-54 851.7546,-43.7958 890.9802,-33.6154 922.5524,-26.6978"/>
<polygon fill="#000000" stroke="#000000" points="923.4455,-30.086 932.4916,-24.5706 921.9805,-23.241 923.4455,-30.086"/>
<text text-anchor="middle" x="900.5145" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- publication -->
<g id="node5" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="966.5145" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="966.5145" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge2" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M966.5145,-86.9735C966.5145,-75.1918 966.5145,-59.5607 966.5145,-46.1581"/>
<polygon fill="#000000" stroke="#000000" points="970.0146,-46.0033 966.5145,-36.0034 963.0146,-46.0034 970.0146,-46.0033"/>
<text text-anchor="middle" x="1017.5145" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge3" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1252.3408,-87.4657C1240.7311,-76.0278 1224.0875,-61.8187 1206.5145,-54 1172.7422,-38.9739 1072.5169,-27.6336 1012.7994,-21.9855"/>
<polygon fill="#000000" stroke="#000000" points="1012.7847,-18.4692 1002.5041,-21.0302 1012.1379,-25.4393 1012.7847,-18.4692"/>
<text text-anchor="middle" x="1282.0145" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- medical_history -->
<g id="node7" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1768.5145" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1768.5145" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1732.9356,-175.6093C1706.17,-164.0121 1668.2785,-149.1309 1633.5145,-141 1579.4101,-128.3456 1429.4374,-116.2137 1339.4554,-109.7731"/>
<polygon fill="#000000" stroke="#000000" points="1339.5509,-106.2712 1329.3281,-109.0541 1339.0551,-113.2536 1339.5509,-106.2712"/>
<text text-anchor="middle" x="1751.5145" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- survival -->
<g id="node9" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1919.5145" cy="-192" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1919.5145" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1896.2548,-176.0106C1877.5185,-164.0535 1850.0214,-148.5234 1823.5145,-141 1734.9978,-115.8766 1470.6655,-108.2079 1341.3637,-105.9292"/>
<polygon fill="#000000" stroke="#000000" points="1341.2201,-102.4264 1331.162,-105.7557 1341.101,-109.4253 1341.2201,-102.4264"/>
<text text-anchor="middle" x="1899.0145" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- sequencing_file -->
<g id="node10" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2672.5145" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="2672.5145" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2664.4459,-260.9185C2658.2778,-249.3946 2648.6014,-235.302 2635.5145,-228 2599.0459,-207.6519 2327.3582,-197.1565 2209.1677,-193.514"/>
<polygon fill="#000000" stroke="#000000" points="2208.9979,-190.0073 2198.8964,-193.2028 2208.7858,-197.0041 2208.9979,-190.0073"/>
<text text-anchor="middle" x="2718.0145" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- study_admin -->
<g id="node11" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1117.5145" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1117.5145" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge28" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1105.1995,-86.7768C1097.0455,-75.9301 1085.4868,-62.6408 1072.5145,-54 1053.8339,-41.5569 1030.4354,-33.0141 1010.3774,-27.3849"/>
<polygon fill="#000000" stroke="#000000" points="1011.099,-23.9554 1000.536,-24.7765 1009.3055,-30.7217 1011.099,-23.9554"/>
<text text-anchor="middle" x="1146.0145" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- treatment_response -->
<g id="node12" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="620.5145" cy="-192" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="620.5145" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M636.7919,-174.0687C648.7142,-162.2929 665.9905,-147.8456 684.5145,-141 737.9091,-121.2678 1140.1478,-130.9468 1196.5145,-123 1202.2359,-122.1934 1208.1621,-121.117 1214.0459,-119.8902"/>
<polygon fill="#000000" stroke="#000000" points="1214.8637,-123.2939 1223.8642,-117.7045 1213.3425,-116.4612 1214.8637,-123.2939"/>
<text text-anchor="middle" x="767.5145" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- cytogenomic_file -->
<g id="node13" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1970.5145" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1970.5145" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1979.1731,-260.942C1985.4825,-249.7319 1995.0926,-235.9859 2007.5145,-228 2041.4609,-206.1761 2057.415,-219.9936 2096.5145,-210 2100.9435,-208.8679 2105.5362,-207.603 2110.1098,-206.2827"/>
<polygon fill="#000000" stroke="#000000" points="2111.4346,-209.5402 2120.0213,-203.3338 2109.4384,-202.8309 2111.4346,-209.5402"/>
<text text-anchor="middle" x="2079.0145" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- family_relationship -->
<g id="node14" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="843.5145" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="843.5145" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M846.7551,-173.8099C849.808,-162.3943 855.6182,-148.4675 866.5145,-141 896.805,-120.2411 1160.2042,-128.4779 1196.5145,-123 1202.2278,-122.1381 1208.1488,-121.0258 1214.0295,-119.7773"/>
<polygon fill="#000000" stroke="#000000" points="1214.8571,-123.1786 1223.8442,-117.5677 1213.3196,-116.3496 1214.8571,-123.1786"/>
<text text-anchor="middle" x="946.0145" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- generic_file -->
<g id="node15" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="391.5145" cy="-279" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="391.5145" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M456.2058,-275.6443C626.3657,-266.8973 1100.5462,-243.0366 1495.5145,-228 1629.0332,-222.9169 1964.7232,-232.0034 2096.5145,-210 2101.5207,-209.1642 2106.6952,-208.0062 2111.7975,-206.6767"/>
<polygon fill="#000000" stroke="#000000" points="2112.7853,-210.0347 2121.4575,-203.9484 2110.8827,-203.2983 2112.7853,-210.0347"/>
<text text-anchor="middle" x="1548.5145" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M386.9155,-260.6593C382.2505,-237.2364 378.495,-196.9916 400.5145,-174 479.5577,-91.4669 541.6105,-150.2439 655.5145,-141 895.3036,-121.5398 958.2613,-156.3611 1196.5145,-123 1202.2366,-122.1988 1208.1634,-121.1259 1214.0475,-119.9012"/>
<polygon fill="#000000" stroke="#000000" points="1214.8642,-123.3051 1223.866,-117.7178 1213.3447,-116.472 1214.8642,-123.3051"/>
<text text-anchor="middle" x="453.5145" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge8" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M334.7371,-269.9041C217.8239,-249.8739 -35.6425,-199.0889 4.5145,-141 43.1463,-85.1172 82.0263,-105.0725 147.5145,-87 227.6033,-64.8982 249.0003,-63.7024 331.5145,-54 550.4527,-28.2563 814.1026,-20.771 919.5733,-18.723"/>
<polygon fill="#000000" stroke="#000000" points="919.9392,-22.2169 929.8721,-18.5307 919.8084,-15.2181 919.9392,-22.2169"/>
<text text-anchor="middle" x="57.5145" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- exposure -->
<g id="node16" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1014.5145" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1014.5145" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1019.6921,-173.9445C1023.929,-162.5857 1031.1191,-148.6717 1042.5145,-141 1071.0961,-121.7581 1162.6201,-129.1911 1196.5145,-123 1201.9013,-122.016 1207.484,-120.8627 1213.049,-119.6233"/>
<polygon fill="#000000" stroke="#000000" points="1214.0489,-122.9844 1223.0007,-117.3175 1212.4688,-116.1651 1214.0489,-122.9844"/>
<text text-anchor="middle" x="1086.0145" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- radiology_file -->
<g id="node17" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1159.5145" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1159.5145" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1142.7139,-174.3902C1134.9009,-164.0294 1128.8501,-151.0346 1136.5145,-141 1137.7706,-139.3554 1176.7956,-128.8281 1212.086,-119.5792"/>
<polygon fill="#000000" stroke="#000000" points="1213.116,-122.9276 1221.9062,-117.0129 1211.3461,-116.1551 1213.116,-122.9276"/>
<text text-anchor="middle" x="1195.5145" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- synonym -->
<g id="node18" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1268.5145" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1268.5145" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1317.9669,-273.2121C1407.9157,-262.855 1604.3622,-241.0201 1770.5145,-228 1915.1805,-216.6636 1953.6987,-235.699 2096.5145,-210 2101.3201,-209.1352 2106.2852,-207.9943 2111.1948,-206.7053"/>
<polygon fill="#000000" stroke="#000000" points="2112.4577,-209.9854 2121.1255,-203.8929 2110.5502,-203.2503 2112.4577,-209.9854"/>
<text text-anchor="middle" x="1813.0145" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1268.5145,-260.7078C1268.5145,-230.3436 1268.5145,-169.3226 1268.5145,-133.3464"/>
<polygon fill="#000000" stroke="#000000" points="1272.0146,-133.0471 1268.5145,-123.0471 1265.0146,-133.0471 1272.0146,-133.0471"/>
<text text-anchor="middle" x="1311.0145" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge17" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1216.2655,-277.8098C997.6976,-272.5818 166.27,-250.1099 128.5145,-210 53.5066,-130.3149 227.3192,-94.1546 250.5145,-87 376.4132,-48.1665 781.1913,-26.473 919.5972,-20.0466"/>
<polygon fill="#000000" stroke="#000000" points="920.0336,-23.5303 929.8625,-19.5754 919.7125,-16.5377 920.0336,-23.5303"/>
<text text-anchor="middle" x="168.0145" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- pathology_file -->
<g id="node19" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2154.5145" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2154.5145" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2154.5145,-260.9735C2154.5145,-249.1918 2154.5145,-233.5607 2154.5145,-220.1581"/>
<polygon fill="#000000" stroke="#000000" points="2158.0146,-220.0033 2154.5145,-210.0034 2151.0146,-220.0034 2158.0146,-220.0033"/>
<text text-anchor="middle" x="2215.5145" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node20" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="246.5145" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="246.5145" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M241.2603,-174.007C239.2401,-162.9686 239.1206,-149.3885 247.5145,-141 266.1639,-122.3625 1170.3779,-126.4695 1196.5145,-123 1202.324,-122.2288 1208.3421,-121.1635 1214.3111,-119.9328"/>
<polygon fill="#000000" stroke="#000000" points="1215.2582,-123.3079 1224.2648,-117.7284 1213.7446,-116.4735 1215.2582,-123.3079"/>
<text text-anchor="middle" x="333.5145" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge6" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M237.0761,-173.9324C233.0035,-163.4093 230.5742,-150.4047 237.5145,-141 285.846,-75.5061 332.9336,-104.0957 412.5145,-87 598.1585,-47.1195 824.1047,-27.869 919.9531,-21.0287"/>
<polygon fill="#000000" stroke="#000000" points="920.4446,-24.503 930.175,-20.3114 919.9545,-17.5201 920.4446,-24.503"/>
<text text-anchor="middle" x="498.5145" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- diagnosis -->
<g id="node21" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1772.5145" cy="-279" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1772.5145" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge30" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1805.4878,-264.4887C1836.6072,-251.0274 1881.151,-232.4256 1899.5145,-228 1984.9876,-207.401 2010.2779,-227.1239 2096.5145,-210 2101.2424,-209.0612 2106.1314,-207.8836 2110.9733,-206.5825"/>
<polygon fill="#000000" stroke="#000000" points="2112.1284,-209.8925 2120.7788,-203.7751 2110.2017,-203.1628 2112.1284,-209.8925"/>
<text text-anchor="middle" x="1944.0145" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1755.8049,-261.8052C1747.3982,-251.0852 1740.6825,-237.56 1749.5145,-228 1783.8527,-190.8311 1942.1762,-247.1689 1976.5145,-210 1999.7136,-184.8885 1973.8424,-154.6876 1942.5145,-141 1888.5993,-117.4438 1504.4394,-108.6911 1341.3946,-106.0129"/>
<polygon fill="#000000" stroke="#000000" points="1341.0358,-102.5068 1330.9807,-105.8452 1340.923,-109.5059 1341.0358,-102.5068"/>
<text text-anchor="middle" x="2030.0145" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- treatment -->
<g id="node22" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="1429.5145" cy="-192" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="1429.5145" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1400.3586,-176.245C1374.193,-162.1058 1335.6065,-141.2547 1306.9311,-125.7593"/>
<polygon fill="#000000" stroke="#000000" points="1308.4591,-122.6067 1297.9975,-120.9318 1305.1313,-128.7651 1308.4591,-122.6067"/>
<text text-anchor="middle" x="1406.5145" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- methylation_array_file -->
<g id="node23" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2364.5145" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2364.5145" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge29" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2332.7011,-261.645C2322.3531,-255.8567 2310.8699,-249.28 2300.5145,-243 2290.0794,-236.6717 2288.6008,-233.1021 2277.5145,-228 2254.0974,-217.2231 2226.6839,-208.8274 2203.6873,-202.8649"/>
<polygon fill="#000000" stroke="#000000" points="2204.347,-199.4219 2193.7954,-200.3779 2202.6401,-206.2106 2204.347,-199.4219"/>
<text text-anchor="middle" x="2392.0145" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- molecular_test -->
<g id="node24" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1585.5145" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1585.5145" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1550.02,-175.7303C1524.6807,-164.6451 1489.5507,-150.3403 1457.5145,-141 1417.5042,-129.3349 1371.5993,-120.489 1335.0497,-114.4853"/>
<polygon fill="#000000" stroke="#000000" points="1335.4309,-111.0016 1325.0016,-112.8673 1334.318,-117.9126 1335.4309,-111.0016"/>
<text text-anchor="middle" x="1565.5145" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2173.0206,-115.319C2185.9885,-120.7452 2198.9375,-128.8879 2206.5145,-141 2213.9961,-152.9598 2205.0814,-164.1812 2192.6402,-173.0365"/>
<polygon fill="#000000" stroke="#000000" points="2190.6346,-170.1645 2184.0922,-178.498 2194.4035,-176.0633 2190.6346,-170.1645"/>
<text text-anchor="middle" x="2250.0145" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge12" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2083.8974,-101.3725C1893.3325,-87.1537 1198.6284,-35.319 1012.6008,-21.4387"/>
<polygon fill="#000000" stroke="#000000" points="1012.835,-17.9465 1002.6023,-20.6927 1012.3141,-24.9271 1012.835,-17.9465"/>
<text text-anchor="middle" x="1660.0145" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- study_personnel -->
<g id="node26" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2935.5145" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2935.5145" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge10" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2909.3715,-87.6667C2889.7002,-75.6796 2861.5857,-60.7234 2834.5145,-54 2743.5553,-31.4093 1293.875,-20.2639 1013.3207,-18.3131"/>
<polygon fill="#000000" stroke="#000000" points="1013.1074,-14.8117 1003.0835,-18.2424 1013.059,-21.8115 1013.1074,-14.8117"/>
<text text-anchor="middle" x="2941.0145" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
</g>
</svg>
</div>
