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
<svg width="3533pt" height="305pt"
 viewBox="0.00 0.00 3532.74 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 3528.7364,-301 3528.7364,4 -4,4"/>
<!-- therapeutic_procedure -->
<g id="node1" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="2665.692" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="2665.692" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- participant -->
<g id="node5" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="2011.692" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="2011.692" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2596.6356,-177.3036C2576.2296,-171.8295 2554.1558,-164.7632 2534.692,-156 2523.5639,-150.9898 2523.2576,-144.8956 2511.692,-141 2472.2433,-127.7127 2212.4998,-114.1791 2083.7641,-108.1885"/>
<polygon fill="#000000" stroke="#000000" points="2083.7514,-104.6842 2073.6003,-107.7185 2083.428,-111.6768 2083.7514,-104.6842"/>
<text text-anchor="middle" x="2627.692" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- exposure -->
<g id="node2" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="2123.692" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="2123.692" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2119.6267,-173.9447C2116.3762,-163.1611 2110.8121,-149.8793 2101.692,-141 2092.6535,-132.2 2081.1914,-125.4669 2069.5002,-120.3447"/>
<polygon fill="#000000" stroke="#000000" points="2070.7007,-117.0552 2060.1169,-116.5735 2068.0903,-123.5503 2070.7007,-117.0552"/>
<text text-anchor="middle" x="2155.192" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- synonym -->
<g id="node3" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1213.692" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1213.692" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- sample -->
<g id="node4" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="873.692" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="873.692" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1174.2789,-266.9832C1155.7762,-260.7621 1133.6701,-252.4816 1114.692,-243 1103.7747,-237.5456 1103.0667,-232.4221 1091.692,-228 1038.2894,-207.2391 972.9909,-198.4492 927.8575,-194.7286"/>
<polygon fill="#000000" stroke="#000000" points="927.9314,-191.2241 917.6928,-193.9482 927.3955,-198.2035 927.9314,-191.2241"/>
<text text-anchor="middle" x="1157.192" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1265.0572,-276.1978C1377.7291,-269.3875 1642.888,-249.5456 1722.692,-210 1742.9667,-199.9532 1739.1214,-185.3573 1758.692,-174 1816.4016,-140.5098 1890.9524,-122.751 1944.1487,-113.6876"/>
<polygon fill="#000000" stroke="#000000" points="1944.8582,-117.118 1954.1577,-112.0416 1943.7223,-110.2107 1944.8582,-117.118"/>
<text text-anchor="middle" x="1801.192" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study -->
<g id="node15" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2527.692" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2527.692" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge17" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1208.9651,-260.8975C1200.7416,-227.5163 1186.0989,-158.1065 1201.692,-141 1289.7041,-44.4461 2256.0623,-22.5057 2481.0667,-18.6924"/>
<polygon fill="#000000" stroke="#000000" points="2481.2738,-22.1896 2491.2144,-18.5243 2481.1577,-15.1905 2481.2738,-22.1896"/>
<text text-anchor="middle" x="1244.192" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M917.9908,-190.6045C1010.6796,-187.2901 1222.1539,-177.5546 1290.692,-156 1303.4183,-151.9977 1303.8989,-144.783 1316.692,-141 1375.1373,-123.7172 1773.21,-111.314 1939.2233,-106.835"/>
<polygon fill="#000000" stroke="#000000" points="1939.4378,-110.3307 1949.3405,-106.5642 1939.2503,-103.3332 1939.4378,-110.3307"/>
<text text-anchor="middle" x="1353.192" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node8" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="1082.692" cy="-105" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="1082.692" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge25" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M917.1162,-188.3291C965.2741,-183.4628 1039.043,-173.3948 1060.692,-156 1067.9318,-150.1829 1072.838,-141.5242 1076.1418,-132.9854"/>
<polygon fill="#000000" stroke="#000000" points="1079.5618,-133.7863 1079.3278,-123.1941 1072.9053,-131.6203 1079.5618,-133.7863"/>
<text text-anchor="middle" x="1109.192" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node9" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="907.692" cy="-105" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="907.692" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge24" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M840.1926,-179.9543C820.1622,-170.7871 800.5777,-157.038 811.692,-141 818.8654,-130.6488 847.4397,-120.7417 871.5646,-113.9503"/>
<polygon fill="#000000" stroke="#000000" points="872.483,-117.3278 881.2151,-111.3277 870.6472,-110.5728 872.483,-117.3278"/>
<text text-anchor="middle" x="848.192" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge30" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2065.9378,-95.8539C2168.3176,-78.5922 2388.2219,-41.5153 2482.8663,-25.5578"/>
<polygon fill="#000000" stroke="#000000" points="2483.6904,-28.9684 2492.9693,-23.8544 2482.5265,-22.0658 2483.6904,-28.9684"/>
<text text-anchor="middle" x="2350.192" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- medical_history -->
<g id="node6" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2279.692" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2279.692" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2258.44,-174.5415C2243.6668,-163.2881 2223.0458,-149.2631 2202.692,-141 2164.397,-125.4531 2119.0233,-116.5421 2082.1111,-111.476"/>
<polygon fill="#000000" stroke="#000000" points="2082.3064,-107.9719 2071.9372,-110.1468 2081.3995,-114.9129 2082.3064,-107.9719"/>
<text text-anchor="middle" x="2296.692" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- radiology_file -->
<g id="node7" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="2456.692" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="2456.692" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2427.4476,-175.4603C2416.7933,-169.3895 2404.6711,-162.4296 2393.692,-156 2382.5106,-149.4519 2380.99,-145.0817 2368.692,-141 2317.4567,-123.995 2171.9582,-113.5144 2083.3198,-108.5184"/>
<polygon fill="#000000" stroke="#000000" points="2083.5119,-105.0238 2073.3336,-107.9652 2083.1247,-112.0131 2083.5119,-105.0238"/>
<text text-anchor="middle" x="2452.692" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1044.3337,-116.4793C1023.73,-123.0006 998.042,-131.7056 975.692,-141 975.4762,-141.0898 939.9608,-158.8508 910.9028,-173.3855"/>
<polygon fill="#000000" stroke="#000000" points="909.126,-170.3608 901.7482,-177.9647 912.2576,-176.6212 909.126,-170.3608"/>
<text text-anchor="middle" x="1016.192" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge26" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1087.2071,-86.8706C1091.1121,-75.326 1098.0243,-61.2282 1109.692,-54 1139.4893,-35.5404 2238.4768,-21.4339 2480.7548,-18.5444"/>
<polygon fill="#000000" stroke="#000000" points="2481.028,-22.0415 2490.9858,-18.423 2480.9449,-15.042 2481.028,-22.0415"/>
<text text-anchor="middle" x="1150.192" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M900.7726,-122.7057C896.074,-134.7284 889.7673,-150.8663 884.4222,-164.5434"/>
<polygon fill="#000000" stroke="#000000" points="881.117,-163.3855 880.7369,-173.9735 887.6368,-165.9335 881.117,-163.3855"/>
<text text-anchor="middle" x="917.692" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge6" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M930.2862,-93.9233C956.9072,-81.5091 1002.8247,-62.0658 1044.692,-54 1188.2924,-26.3352 2244.4927,-19.422 2480.8558,-18.2147"/>
<polygon fill="#000000" stroke="#000000" points="2481.1845,-21.7132 2491.1668,-18.163 2481.1494,-14.7133 2481.1845,-21.7132"/>
<text text-anchor="middle" x="1068.692" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study_funding -->
<g id="node10" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2450.692" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2450.692" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge9" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2450.0871,-86.9649C2450.5993,-76.4533 2452.8127,-63.4494 2459.692,-54 2466.6241,-44.4782 2476.8477,-37.2448 2487.273,-31.8531"/>
<polygon fill="#000000" stroke="#000000" points="2488.8352,-34.9864 2496.409,-27.5778 2485.8682,-28.6463 2488.8352,-34.9864"/>
<text text-anchor="middle" x="2521.692" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- study_arm -->
<g id="node11" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2605.692" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2605.692" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge4" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2600.8422,-87.0458C2597.3464,-76.5628 2591.7999,-63.5607 2583.692,-54 2577.8893,-47.1574 2570.4567,-41.1545 2562.9162,-36.1112"/>
<polygon fill="#000000" stroke="#000000" points="2564.4474,-32.9421 2554.106,-30.6388 2560.7539,-38.8884 2564.4474,-32.9421"/>
<text text-anchor="middle" x="2641.192" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- clinical_measure_file -->
<g id="node12" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="2919.692" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="2919.692" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2833.1804,-180.9779C2804.0507,-175.5318 2771.8191,-167.5562 2743.692,-156 2732.4036,-151.3621 2732.2986,-144.7718 2720.692,-141 2645.358,-116.5182 2443.8023,-127.017 2364.692,-123 2267.289,-118.0542 2154.7696,-112.3116 2083.4459,-108.6679"/>
<polygon fill="#000000" stroke="#000000" points="2083.394,-105.1607 2073.2284,-108.1458 2083.0367,-112.1516 2083.394,-105.1607"/>
<text text-anchor="middle" x="2829.692" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge12" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2922.7845,-173.802C2923.5577,-163.2326 2922.6347,-150.2252 2915.692,-141 2901.9916,-122.7953 2888.9494,-131.1997 2867.692,-123 2790.0745,-93.06 2773.277,-78.2306 2693.692,-54 2653.2977,-41.7015 2606.1582,-31.8983 2572.4562,-25.6465"/>
<polygon fill="#000000" stroke="#000000" points="2572.9165,-22.1728 2562.4507,-23.8215 2571.6603,-29.0592 2572.9165,-22.1728"/>
<text text-anchor="middle" x="2953.692" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- diagnosis -->
<g id="node13" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1352.692" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1352.692" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1369.1104,-174.7172C1381.4974,-162.9208 1399.5778,-148.1785 1418.692,-141 1466.2216,-123.1498 1791.4408,-111.4615 1939.0689,-107.0161"/>
<polygon fill="#000000" stroke="#000000" points="1939.4937,-110.5051 1949.385,-106.7086 1939.2851,-103.5082 1939.4937,-110.5051"/>
<text text-anchor="middle" x="1463.192" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- follow_up -->
<g id="node14" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="1480.692" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="1480.692" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1493.6316,-174.3212C1503.257,-162.6611 1517.4898,-148.2485 1533.692,-141 1569.7126,-124.8852 1814.7417,-112.8879 1939.3022,-107.7526"/>
<polygon fill="#000000" stroke="#000000" points="1939.6654,-111.2408 1949.5143,-107.3359 1939.3799,-104.2466 1939.6654,-111.2408"/>
<text text-anchor="middle" x="1578.692" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- sequencing_file -->
<g id="node16" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="280.692" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="280.692" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M306.2127,-261.8324C325.091,-250.0917 351.8971,-235.3687 377.692,-228 459.2204,-204.7103 707.6205,-195.9665 818.8377,-193.1579"/>
<polygon fill="#000000" stroke="#000000" points="819.2512,-196.6489 829.1622,-192.9043 819.0792,-189.651 819.2512,-196.6489"/>
<text text-anchor="middle" x="444.192" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- study_personnel -->
<g id="node17" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="3135.692" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="3135.692" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge22" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3075.8878,-91.8523C3022.748,-80.5412 2942.8474,-64.4419 2872.692,-54 2766.3967,-38.179 2640.6508,-26.9218 2574.2231,-21.5535"/>
<polygon fill="#000000" stroke="#000000" points="2574.3304,-18.051 2564.0832,-20.7427 2573.7724,-25.0288 2574.3304,-18.051"/>
<text text-anchor="middle" x="3029.192" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- molecular_test -->
<g id="node18" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1633.692" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1633.692" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1628.5746,-173.7286C1626.7269,-162.8638 1626.7444,-149.5724 1634.692,-141 1654.9436,-119.1566 1835.433,-110.1989 1939.1563,-106.8294"/>
<polygon fill="#000000" stroke="#000000" points="1939.3693,-110.3245 1949.254,-106.5111 1939.1487,-103.328 1939.3693,-110.3245"/>
<text text-anchor="middle" x="1698.692" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- family_relationship -->
<g id="node19" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1952.692" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1952.692" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1943.2019,-173.9072C1939.2052,-163.6263 1936.7052,-150.8763 1942.692,-141 1946.9766,-133.9319 1953.1533,-128.1862 1960.0733,-123.5344"/>
<polygon fill="#000000" stroke="#000000" points="1962.2952,-126.2888 1969.1496,-118.21 1958.7533,-120.251 1962.2952,-126.2888"/>
<text text-anchor="middle" x="2022.192" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- pathology_file -->
<g id="node20" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="457.692" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="457.692" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M481.9418,-261.8482C499.598,-250.2748 524.5503,-235.7485 548.692,-228 597.7711,-212.2477 740.7587,-200.7286 819.7283,-195.3634"/>
<polygon fill="#000000" stroke="#000000" points="820.2197,-198.8384 829.9635,-194.6781 819.752,-191.854 820.2197,-198.8384"/>
<text text-anchor="middle" x="609.692" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- methylation_array_file -->
<g id="node21" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="667.692" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="667.692" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M668.7999,-260.9227C670.4531,-249.8507 674.4013,-236.2648 683.692,-228 703.4807,-210.3966 771.0482,-200.8172 819.9839,-196.0578"/>
<polygon fill="#000000" stroke="#000000" points="820.4871,-199.5262 830.1196,-195.1142 819.8382,-192.5564 820.4871,-199.5262"/>
<text text-anchor="middle" x="775.192" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node22" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="938.692" cy="-279" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="938.692" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M894.0086,-261.9414C886.3296,-256.9963 879.3379,-250.768 874.692,-243 870.6919,-236.3118 869.3237,-228.1953 869.2507,-220.4229"/>
<polygon fill="#000000" stroke="#000000" points="872.7583,-220.3853 869.8283,-210.2037 865.7695,-219.9903 872.7583,-220.3853"/>
<text text-anchor="middle" x="983.192" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- cytogenomic_file -->
<g id="node23" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="89.692" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="89.692" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M117.4714,-261.6941C137.9812,-249.8865 167.0239,-235.1404 194.692,-228 254.3409,-212.6063 668.1576,-198.3813 818.9129,-193.6538"/>
<polygon fill="#000000" stroke="#000000" points="819.4181,-197.1399 829.3042,-193.33 819.2,-190.1433 819.4181,-197.1399"/>
<text text-anchor="middle" x="266.192" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- study_admin -->
<g id="node24" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="3310.692" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="3310.692" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge7" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3264.9011,-91.2779C3223.0678,-79.3414 3159.2947,-62.6408 3102.692,-54 3001.1936,-38.5055 2692.6797,-24.7097 2574.4686,-19.8533"/>
<polygon fill="#000000" stroke="#000000" points="2574.4308,-16.349 2564.2963,-19.4382 2574.1453,-23.3431 2574.4308,-16.349"/>
<text text-anchor="middle" x="3234.192" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- publication -->
<g id="node25" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="3461.692" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="3461.692" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge16" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3423.8803,-90.4847C3390.4548,-78.3743 3340.0936,-61.8705 3294.692,-54 3155.1789,-29.8149 2719.0505,-20.9787 2574.6501,-18.6717"/>
<polygon fill="#000000" stroke="#000000" points="2574.4201,-15.1677 2564.3665,-18.5106 2574.3104,-22.1669 2574.4201,-15.1677"/>
<text text-anchor="middle" x="3405.692" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
</g>
</svg>
</div>
