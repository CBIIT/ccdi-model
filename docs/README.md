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
<svg width="3835pt" height="305pt"
 viewBox="0.00 0.00 3835.29 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 3831.2907,-301 3831.2907,4 -4,4"/>
<!-- study -->
<g id="node1" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="3061.9475" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="3061.9475" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- therapeutic_procedure -->
<g id="node2" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="1791.9475" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="1791.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- participant -->
<g id="node21" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="2120.9475" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="2120.9475" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1803.3211,-173.8399C1811.4924,-162.4369 1823.5767,-148.5129 1837.9475,-141 1873.5067,-122.41 1977.4241,-112.9307 2048.922,-108.4764"/>
<polygon fill="#000000" stroke="#000000" points="2049.4525,-111.9508 2059.2237,-107.8552 2049.0311,-104.9635 2049.4525,-111.9508"/>
<text text-anchor="middle" x="1930.9475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- pdx -->
<g id="node3" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="27.9475" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="27.9475" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge5" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M28.5914,-260.8542C29.9838,-249.7548 33.6582,-236.1642 42.9475,-228 343.4381,36.0934 533.729,-125.235 931.9475,-87 1356.2596,-46.2597 2742.3622,-22.9583 3015.1125,-18.7087"/>
<polygon fill="#000000" stroke="#000000" points="3015.4985,-22.2032 3025.443,-18.5486 3015.39,-15.2041 3015.4985,-22.2032"/>
<text text-anchor="middle" x="186.9475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- sample -->
<g id="node10" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="885.9475" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="885.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M49.5314,-267.5632C54.5096,-265.1899 59.8439,-262.8514 64.9475,-261 72.1041,-258.4039 190.4175,-229.1207 197.9475,-228 319.8562,-209.8566 691.3754,-197.5941 831.5983,-193.5025"/>
<polygon fill="#000000" stroke="#000000" points="831.7888,-196.9985 841.6834,-193.2107 831.5863,-190.0015 831.7888,-196.9985"/>
<text text-anchor="middle" x="221.9475" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- cytogenomic_file -->
<g id="node4" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="163.9475" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="163.9475" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M199.1602,-262.3526C225.8979,-250.5447 263.9163,-235.5116 298.9475,-228 399.5696,-206.424 705.6956,-196.5055 831.2933,-193.2637"/>
<polygon fill="#000000" stroke="#000000" points="831.5413,-196.7586 841.4492,-193.006 831.3636,-189.7609 831.5413,-196.7586"/>
<text text-anchor="middle" x="370.4475" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- study_admin -->
<g id="node5" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="3110.9475" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="3110.9475" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge28" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3100.7947,-86.9735C3093.8708,-74.6801 3084.5864,-58.1956 3076.8305,-44.4249"/>
<polygon fill="#000000" stroke="#000000" points="3079.71,-42.4052 3071.753,-35.4097 3073.6108,-45.8404 3079.71,-42.4052"/>
<text text-anchor="middle" x="3145.4475" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node6" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="408.9475" cy="-279" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="408.9475" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge32" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M424.5837,-260.8605C435.6942,-249.3115 451.6624,-235.2126 468.9475,-228 533.004,-201.2711 733.6771,-194.3871 831.3955,-192.6145"/>
<polygon fill="#000000" stroke="#000000" points="831.7165,-196.1096 841.6556,-192.4404 831.5977,-189.1106 831.7165,-196.1096"/>
<text text-anchor="middle" x="577.4475" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- methylation_array_file -->
<g id="node7" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="679.9475" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="679.9475" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge30" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M682.5709,-260.8464C685.1315,-249.7439 690.1521,-236.1527 699.9475,-228 719.6725,-211.5829 784.463,-201.8038 832.0485,-196.6703"/>
<polygon fill="#000000" stroke="#000000" points="832.6356,-200.1283 842.2208,-195.6145 831.9129,-193.1657 832.6356,-200.1283"/>
<text text-anchor="middle" x="791.4475" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- synonym -->
<g id="node8" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2475.9475" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2475.9475" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge22" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2528.1685,-277.8251C2640.4686,-274.3418 2900.3945,-260.8578 2969.9475,-210 2977.2004,-204.6966 3026.5225,-96.6576 3049.814,-45.0265"/>
<polygon fill="#000000" stroke="#000000" points="3053.0589,-46.3445 3053.9747,-35.7893 3046.6765,-43.4696 3053.0589,-46.3445"/>
<text text-anchor="middle" x="3047.4475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge23" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2424.3987,-276.1794C2185.1473,-263.0883 1184.2984,-208.3249 939.9378,-194.9542"/>
<polygon fill="#000000" stroke="#000000" points="940.0572,-191.4556 929.8809,-194.4039 939.6747,-198.4451 940.0572,-191.4556"/>
<text text-anchor="middle" x="1819.4475" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2479.7037,-260.7151C2484.632,-230.9805 2489.2301,-172.3256 2456.9475,-141 2438.4066,-123.0087 2286.3033,-112.732 2193.2171,-108.0715"/>
<polygon fill="#000000" stroke="#000000" points="2193.1668,-104.5649 2183.0074,-107.5709 2192.824,-111.5565 2193.1668,-104.5649"/>
<text text-anchor="middle" x="2525.4475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- pathology_file -->
<g id="node9" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="889.9475" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="889.9475" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M888.1962,-260.701C887.7146,-255.0324 887.2438,-248.7623 886.9475,-243 886.5748,-235.7505 886.3382,-227.9149 886.1888,-220.6116"/>
<polygon fill="#000000" stroke="#000000" points="889.6854,-220.3658 886.0266,-210.4228 882.6863,-220.4773 889.6854,-220.3658"/>
<text text-anchor="middle" x="947.9475" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge7" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M841.7096,-192.827C675.5047,-196.0764 96.1156,-208.7427 61.9475,-228 52.2831,-233.4469 44.8516,-242.915 39.437,-252.2261"/>
<polygon fill="#000000" stroke="#000000" points="36.2098,-250.8451 34.6868,-261.3299 42.4158,-254.0833 36.2098,-250.8451"/>
<text text-anchor="middle" x="98.4475" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node14" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="989.9475" cy="-105" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="989.9475" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge9" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M923.3604,-182.2178C938.7519,-176.6364 955.7837,-168.2424 967.9475,-156 974.3957,-149.5102 979.0861,-140.8259 982.436,-132.4651"/>
<polygon fill="#000000" stroke="#000000" points="985.7664,-133.5445 985.7776,-122.9497 979.1618,-131.2251 985.7664,-133.5445"/>
<text text-anchor="middle" x="1015.4475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M924.8346,-183.3605C979.9459,-171.5184 1084.0762,-150.6196 1173.9475,-141 1343.1199,-122.8922 1857.0404,-110.5459 2048.2558,-106.4705"/>
<polygon fill="#000000" stroke="#000000" points="2048.5547,-109.9651 2058.4783,-106.254 2048.4064,-102.9666 2048.5547,-109.9651"/>
<text text-anchor="middle" x="1210.4475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- diagnosis -->
<g id="node11" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1256.9475" cy="-279" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1256.9475" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1226.3728,-263.8547C1214.2638,-257.6482 1200.3093,-250.2329 1187.9475,-243 1177.4141,-236.8368 1176.3986,-232.2204 1164.9475,-228 1124.7919,-213.2003 1008.8614,-201.7923 939.7236,-196.0681"/>
<polygon fill="#000000" stroke="#000000" points="939.7139,-192.5558 929.4626,-195.2318 939.1452,-199.5327 939.7139,-192.5558"/>
<text text-anchor="middle" x="1232.4475" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1269.2338,-261.0773C1272.3823,-255.5277 1275.3334,-249.229 1276.9475,-243 1278.6198,-236.5465 1278.1768,-234.5524 1276.9475,-228 1275.3648,-219.5635 1271.5302,-218.4365 1269.9475,-210 1266.9974,-194.2743 1259.4429,-186.0687 1269.9475,-174 1295.4155,-144.7401 1848.3902,-117.1901 2049.0356,-108.1227"/>
<polygon fill="#000000" stroke="#000000" points="2049.3447,-111.6124 2059.1773,-107.6666 2049.0301,-104.6195 2049.3447,-111.6124"/>
<text text-anchor="middle" x="1314.4475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- radiology_file -->
<g id="node12" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="2651.9475" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="2651.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2596.9367,-180.0098C2564.0138,-172.4547 2525.6123,-162.8661 2509.9475,-156 2498.7701,-151.1007 2498.4611,-145.0466 2486.9475,-141 2434.4566,-122.5516 2283.803,-112.537 2192.9722,-108.0234"/>
<polygon fill="#000000" stroke="#000000" points="2192.9044,-104.516 2182.7461,-107.5258 2192.5641,-111.5077 2192.9044,-104.516"/>
<text text-anchor="middle" x="2568.9475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- sequencing_file -->
<g id="node13" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1066.9475" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1066.9475" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1050.7107,-261.1929C1039.8429,-250.2286 1024.6896,-236.6613 1008.9475,-228 986.6172,-215.7138 959.6439,-207.2149 936.6535,-201.5738"/>
<polygon fill="#000000" stroke="#000000" points="937.271,-198.1239 926.7366,-199.2543 935.6767,-204.9399 937.271,-198.1239"/>
<text text-anchor="middle" x="1096.4475" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge18" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1039.1221,-102.9352C1322.1366,-91.0519 2740.2981,-31.5055 3015.6062,-19.9458"/>
<polygon fill="#000000" stroke="#000000" points="3015.8103,-23.4404 3025.6546,-19.5239 3015.5166,-16.4466 3015.8103,-23.4404"/>
<text text-anchor="middle" x="2191.4475" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M947.1597,-114.0373C920.8755,-120.554 890.7824,-130.0975 882.9475,-141 878.2163,-147.5836 877.2462,-155.9677 877.9545,-164.0272"/>
<polygon fill="#000000" stroke="#000000" points="874.5033,-164.6099 879.5926,-173.9024 881.4089,-163.4644 874.5033,-164.6099"/>
<text text-anchor="middle" x="923.4475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- publication -->
<g id="node15" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="3261.9475" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="3261.9475" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge1" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3246.9604,-87.4547C3236.5309,-76.3113 3221.7114,-62.4456 3205.9475,-54 3175.3672,-37.6165 3137.1263,-28.5086 3107.7392,-23.5551"/>
<polygon fill="#000000" stroke="#000000" points="3108.1654,-20.0791 3097.7409,-21.9711 3107.0701,-26.9929 3108.1654,-20.0791"/>
<text text-anchor="middle" x="3276.9475" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- molecular_test -->
<g id="node16" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1447.9475" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1447.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1474.3113,-174.7634C1493.7994,-162.9893 1521.4436,-148.2548 1547.9475,-141 1640.1227,-115.7694 1915.7004,-108.1381 2048.2128,-105.8968"/>
<polygon fill="#000000" stroke="#000000" points="2048.3309,-109.3954 2058.2724,-105.7324 2048.2165,-102.3964 2048.3309,-109.3954"/>
<text text-anchor="middle" x="1611.9475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- follow_up -->
<g id="node17" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="1600.9475" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="1600.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1630.6692,-176.808C1655.2715,-164.9673 1691.4878,-149.2034 1724.9475,-141 1784.6041,-126.3738 1952.6705,-114.6865 2049.6035,-108.9197"/>
<polygon fill="#000000" stroke="#000000" points="2049.8426,-112.4117 2059.6195,-108.3298 2049.431,-105.4238 2049.8426,-112.4117"/>
<text text-anchor="middle" x="1769.9475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- study_personnel -->
<g id="node18" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="3429.9475" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="3429.9475" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge11" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3403.1774,-87.8148C3384.0749,-76.3812 3357.3675,-62.0362 3331.9475,-54 3291.287,-41.1457 3173.9112,-28.5356 3108.0922,-22.2055"/>
<polygon fill="#000000" stroke="#000000" points="3108.2776,-18.7074 3097.991,-21.2444 3107.6145,-25.6759 3108.2776,-18.7074"/>
<text text-anchor="middle" x="3437.4475" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- clinical_measure_file -->
<g id="node19" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="2851.9475" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="2851.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge24" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2839.4002,-173.838C2825.5573,-151.3312 2807.6323,-112.8019 2826.9475,-87 2849.7111,-56.5917 2955.1632,-35.0196 3016.7986,-24.7611"/>
<polygon fill="#000000" stroke="#000000" points="3017.7239,-28.1567 3027.0313,-23.0948 3016.5987,-21.2477 3017.7239,-28.1567"/>
<text text-anchor="middle" x="2912.9475" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2773.4645,-179.4767C2722.1475,-171.0229 2662.5433,-160.5988 2650.9475,-156 2639.6031,-151.5009 2639.515,-144.8898 2627.9475,-141 2587.8409,-127.5132 2323.2229,-114.0271 2193.034,-108.1116"/>
<polygon fill="#000000" stroke="#000000" points="2192.9075,-104.6024 2182.7598,-107.6478 2192.5918,-111.5953 2192.9075,-104.6024"/>
<text text-anchor="middle" x="2736.9475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- study_arm -->
<g id="node20" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="3594.9475" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="3594.9475" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge29" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3573.5236,-88.1024C3557.3218,-76.3318 3533.998,-61.4557 3510.9475,-54 3437.1083,-30.1166 3207.8763,-21.6276 3108.5864,-19.0185"/>
<polygon fill="#000000" stroke="#000000" points="3108.6316,-15.5186 3098.5458,-18.7631 3108.4536,-22.5163 3108.6316,-15.5186"/>
<text text-anchor="middle" x="3590.4475" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge26" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2180.5252,-99.4918C2354.6899,-83.3894 2860.4374,-36.6306 3015.923,-22.2552"/>
<polygon fill="#000000" stroke="#000000" points="3016.4425,-25.7222 3026.0778,-21.3163 3015.798,-18.7519 3016.4425,-25.7222"/>
<text text-anchor="middle" x="2698.4475" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_funding -->
<g id="node22" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="3749.9475" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="3749.9475" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge31" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3722.0192,-88.0239C3701.0639,-76.2144 3671.2364,-61.3239 3642.9475,-54 3542.2798,-27.9376 3228.0181,-20.5134 3108.6144,-18.6036"/>
<polygon fill="#000000" stroke="#000000" points="3108.3996,-15.1 3098.3469,-18.4454 3108.2917,-22.0992 3108.3996,-15.1"/>
<text text-anchor="middle" x="3743.9475" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- family_relationship -->
<g id="node23" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="2027.9475" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="2027.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2025.7947,-173.8142C2025.516,-163.2491 2026.954,-150.242 2033.9475,-141 2040.8898,-131.8257 2050.5909,-124.9749 2061.0092,-119.8634"/>
<polygon fill="#000000" stroke="#000000" points="2062.5359,-123.0158 2070.2978,-115.8045 2059.733,-116.6015 2062.5359,-123.0158"/>
<text text-anchor="middle" x="2113.4475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- medical_history -->
<g id="node24" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2230.9475" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2230.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2220.3914,-173.7944C2213.5808,-163.2223 2203.9535,-150.2148 2192.9475,-141 2185.2323,-134.5405 2176.1616,-128.8668 2167.1081,-124.0478"/>
<polygon fill="#000000" stroke="#000000" points="2168.6168,-120.8889 2158.1113,-119.5164 2165.4679,-127.1406 2168.6168,-120.8889"/>
<text text-anchor="middle" x="2275.9475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- exposure -->
<g id="node25" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="2386.9475" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="2386.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2377.8561,-174.0046C2371.1611,-162.6711 2360.9681,-148.7628 2347.9475,-141 2322.1223,-125.6032 2248.0375,-115.8584 2191.4614,-110.4468"/>
<polygon fill="#000000" stroke="#000000" points="2191.7552,-106.9591 2181.4742,-109.5187 2191.1074,-113.9291 2191.7552,-106.9591"/>
<text text-anchor="middle" x="2409.4475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
</g>
</svg>
</div>
