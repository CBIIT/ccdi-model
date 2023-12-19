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
<svg width="3398pt" height="392pt"
 viewBox="0.00 0.00 3398.30 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3394.2953,-388 3394.2953,4 -4,4"/>
<!-- study_personnel -->
<g id="node1" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="837.2953" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="837.2953" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study -->
<g id="node21" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1801.2953" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1801.2953" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge7" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M875.5997,-88.7124C905.6526,-76.7612 948.8581,-61.3797 988.2953,-54 1136.7979,-26.2115 1604.5893,-19.7278 1754.5463,-18.3463"/>
<polygon fill="#000000" stroke="#000000" points="1754.8166,-21.8441 1764.7851,-18.2554 1754.7544,-14.8444 1754.8166,-21.8441"/>
<text text-anchor="middle" x="1057.7953" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- study_admin -->
<g id="node2" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1012.2953" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1012.2953" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge12" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1054.9522,-90.5743C1092.2925,-78.6076 1148.2452,-62.2632 1198.2953,-54 1305.2476,-36.3422 1632.6763,-23.7273 1754.7614,-19.5252"/>
<polygon fill="#000000" stroke="#000000" points="1755.0275,-23.0183 1764.9023,-19.1793 1754.7888,-16.0224 1755.0275,-23.0183"/>
<text text-anchor="middle" x="1254.7953" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- diagnosis -->
<g id="node3" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="496.2953" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="496.2953" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- participant -->
<g id="node13" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1336.2953" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1336.2953" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M525.8738,-176.8652C551.4471,-164.6294 589.7903,-148.2832 625.2953,-141 764.4539,-112.454 1123.5617,-142.3404 1264.2953,-123 1270.0195,-122.2134 1275.9475,-121.15 1281.8324,-119.9309"/>
<polygon fill="#000000" stroke="#000000" points="1282.6465,-123.3355 1291.6519,-117.7539 1281.1313,-116.5015 1282.6465,-123.3355"/>
<text text-anchor="middle" x="669.7953" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- radiology_file -->
<g id="node4" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1293.2953" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1293.2953" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1276.6928,-174.0437C1269.5222,-164.0428 1264.0481,-151.5237 1270.2953,-141 1274.3241,-134.2133 1280.132,-128.6242 1286.6537,-124.0455"/>
<polygon fill="#000000" stroke="#000000" points="1288.5368,-126.9964 1295.2162,-118.7722 1284.866,-121.036 1288.5368,-126.9964"/>
<text text-anchor="middle" x="1329.2953" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- medical_history -->
<g id="node5" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="338.2953" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="338.2953" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M364.1599,-174.6874C383.6267,-162.7106 411.4594,-147.7581 438.2953,-141 527.3154,-118.5819 1173.3111,-135.2083 1264.2953,-123 1270.1037,-122.2206 1276.1211,-121.15 1282.0897,-119.9161"/>
<polygon fill="#000000" stroke="#000000" points="1283.0382,-123.2909 1292.043,-117.7083 1281.5223,-116.457 1283.0382,-123.2909"/>
<text text-anchor="middle" x="506.2953" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- study_funding -->
<g id="node6" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="1178.2953" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="1178.2953" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge15" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1226.3061,-90.77C1267.5674,-79.0931 1328.8477,-63.0591 1383.2953,-54 1516.7664,-31.7928 1676.6314,-22.8586 1754.3067,-19.6278"/>
<polygon fill="#000000" stroke="#000000" points="1754.8592,-23.1085 1764.7103,-19.209 1754.5776,-16.1141 1754.8592,-23.1085"/>
<text text-anchor="middle" x="1445.2953" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- sequencing_file -->
<g id="node7" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2705.2953" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="2705.2953" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- cell_line -->
<g id="node9" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2563.2953" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2563.2953" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge42" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2633.1533,-356.8158C2600.9351,-351.088 2568.0271,-342.4027 2558.2953,-330 2553.1414,-323.4317 2552.4381,-314.8257 2553.6148,-306.5585"/>
<polygon fill="#000000" stroke="#000000" points="2557.0294,-307.3266 2555.8099,-296.8022 2550.2001,-305.79 2557.0294,-307.3266"/>
<text text-anchor="middle" x="2624.7953" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- pdx -->
<g id="node14" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2093.2953" cy="-105" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2093.2953" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge41" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2785.3021,-360.9843C2831.248,-356.2675 2882.6662,-347.2203 2897.2953,-330 2926.6514,-295.444 2928.3168,-262.8375 2899.2953,-228 2752.6805,-52.0034 2618.9523,-166.3577 2391.2953,-141 2275.7344,-128.1282 2242.6383,-152.984 2130.2953,-123 2128.1083,-122.4163 2125.8958,-121.7013 2123.6976,-120.8965"/>
<polygon fill="#000000" stroke="#000000" points="2124.8499,-117.5839 2114.2758,-116.9213 2122.1287,-124.0334 2124.8499,-117.5839"/>
<text text-anchor="middle" x="2975.7953" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sample -->
<g id="node23" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2349.2953" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2349.2953" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge40" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2702.2063,-347.8708C2700.0366,-337.8158 2696.5628,-325.3002 2691.2953,-315 2668.6986,-270.814 2664.5497,-252.3325 2621.2953,-228 2585.1137,-207.6463 2472.1078,-198.32 2403.6651,-194.4403"/>
<polygon fill="#000000" stroke="#000000" points="2403.6692,-190.9355 2393.4933,-193.8852 2403.2877,-197.9251 2403.6692,-190.9355"/>
<text text-anchor="middle" x="2747.7953" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node8" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2072.2953" cy="-366" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="2072.2953" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge28" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2106.0035,-348.4169C2130.1671,-336.721 2163.8671,-322.2263 2195.2953,-315 2327.6335,-284.5713 2366.4298,-319.7893 2500.2953,-297 2505.6218,-296.0932 2511.1407,-294.9032 2516.5971,-293.5663"/>
<polygon fill="#000000" stroke="#000000" points="2517.5065,-296.9463 2526.2962,-291.0308 2515.736,-290.1739 2517.5065,-296.9463"/>
<text text-anchor="middle" x="2303.7953" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge29" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1972.8876,-353.5018C1946.2849,-348.0166 1922.5853,-340.3914 1914.2953,-330 1910.1377,-324.7886 1909.99,-320.0901 1914.2953,-315 1945.438,-278.1807 1990.1525,-333.8193 2021.2953,-297 2031.628,-284.7838 2029.9828,-274.436 2021.2953,-261 2010.7101,-244.6292 1991.8804,-259.3708 1981.2953,-243 1963.6707,-215.7421 1937.181,-218.9731 2007.2953,-141 2020.0515,-126.8139 2039.2921,-118.0595 2056.3418,-112.7422"/>
<polygon fill="#000000" stroke="#000000" points="2057.3915,-116.0827 2066.0617,-109.9936 2055.4866,-109.3468 2057.3915,-116.0827"/>
<text text-anchor="middle" x="2089.7953" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1977.4774,-352.8717C1952.3823,-347.364 1930.0883,-339.8846 1922.2953,-330 1918.1678,-324.7647 1917.9245,-320.034 1922.2953,-315 1940.9832,-293.4766 2021.6296,-303.8634 2049.2953,-297 2095.1422,-285.6261 2103.2076,-271.3552 2149.2953,-261 2189.8116,-251.8966 2303.5255,-269.7419 2335.2953,-243 2342.0371,-237.3251 2345.6916,-228.737 2347.6261,-220.2177"/>
<polygon fill="#000000" stroke="#000000" points="2351.1273,-220.4831 2349.2245,-210.0605 2344.2124,-219.3948 2351.1273,-220.4831"/>
<text text-anchor="middle" x="2257.7953" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2527.7961,-266.3056C2521.6732,-264.3643 2515.3355,-262.5083 2509.2953,-261 2487.9751,-255.6764 2336.1702,-230.0916 2314.2953,-228 2271.0366,-223.8637 1571.5852,-228.5666 1532.2953,-210 1513.2048,-200.9788 1519.0068,-185.4948 1501.2953,-174 1477.9416,-158.8435 1467.2338,-166.1145 1441.2953,-156 1428.6131,-151.0547 1400.3272,-137.2557 1376.3062,-125.2568"/>
<polygon fill="#000000" stroke="#000000" points="1377.8584,-122.1199 1367.3501,-120.7685 1374.7221,-128.378 1377.8584,-122.1199"/>
<text text-anchor="middle" x="1572.7953" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge21" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2605.6772,-269.5507C2621.763,-266.3165 2640.2993,-263.01 2657.2953,-261 2678.7798,-258.4591 3031.3553,-258.6473 3046.2953,-243 3050.8991,-238.1782 3050.4119,-233.2438 3046.2953,-228 2845.1415,28.2317 2656.2188,-103.8275 2334.2953,-54 2241.1768,-39.5871 1960.0852,-25.3738 1848.0864,-20.1235"/>
<polygon fill="#000000" stroke="#000000" points="1847.9398,-16.613 1837.7877,-19.6437 1847.614,-23.6054 1847.9398,-16.613"/>
<text text-anchor="middle" x="3016.7953" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge23" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2524.0731,-267.9126C2495.5949,-259.6967 2459.6443,-248.9356 2445.2953,-243 2433.3397,-238.0545 2406.653,-223.7771 2384.4441,-211.5825"/>
<polygon fill="#000000" stroke="#000000" points="2386.0169,-208.453 2375.5697,-206.6905 2382.6376,-214.5832 2386.0169,-208.453"/>
<text text-anchor="middle" x="2485.7953" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- molecular_test -->
<g id="node10" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="649.2953" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="649.2953" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M677.2823,-175.0552C698.6439,-163.0956 729.2512,-148.0028 758.2953,-141 867.6764,-114.6271 1152.8848,-138.7307 1264.2953,-123 1270.0165,-122.1922 1275.9427,-121.1151 1281.8264,-119.8878"/>
<polygon fill="#000000" stroke="#000000" points="1282.6444,-123.2914 1291.6446,-117.7015 1281.1229,-116.4588 1282.6444,-123.2914"/>
<text text-anchor="middle" x="822.2953" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- therapeutic_procedure -->
<g id="node11" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="865.2953" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="865.2953" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M875.1547,-174.0084C882.6006,-162.3664 893.9773,-148.1011 908.2953,-141 943.7772,-123.4024 1225.1207,-128.8305 1264.2953,-123 1270.0103,-122.1494 1275.9324,-121.0445 1281.8137,-119.8004"/>
<polygon fill="#000000" stroke="#000000" points="1282.6394,-123.2023 1291.6292,-117.5958 1281.1053,-116.3724 1282.6394,-123.2023"/>
<text text-anchor="middle" x="1001.2953" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- family_relationship -->
<g id="node12" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1101.2953" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1101.2953" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1097.4682,-173.6293C1096.3407,-162.7271 1097.1496,-149.4313 1105.2953,-141 1130.0024,-115.4265 1229.3035,-129.326 1264.2953,-123 1269.6839,-122.0258 1275.2678,-120.879 1280.8335,-119.6437"/>
<polygon fill="#000000" stroke="#000000" points="1281.8315,-123.0054 1290.7862,-117.3428 1280.2548,-116.1852 1281.8315,-123.0054"/>
<text text-anchor="middle" x="1184.7953" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge17" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1386.4721,-94.2209C1436.8775,-83.5208 1516.8291,-66.8971 1586.2953,-54 1644.8576,-43.1273 1712.6738,-32.0169 1756.232,-25.0705"/>
<polygon fill="#000000" stroke="#000000" points="1756.8965,-28.5089 1766.2231,-23.4824 1755.7976,-21.5957 1756.8965,-28.5089"/>
<text text-anchor="middle" x="1636.7953" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge5" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2067.893,-97.4315C2017.29,-82.3546 1903.5122,-48.455 1842.2328,-30.1971"/>
<polygon fill="#000000" stroke="#000000" points="1843.0896,-26.8004 1832.5065,-27.2992 1841.0908,-33.509 1843.0896,-26.8004"/>
<text text-anchor="middle" x="1988.2953" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2114.7567,-116.8014C2119.7413,-119.1558 2125.1091,-121.3944 2130.2953,-123 2182.2328,-139.0791 2199.58,-124.2196 2251.2953,-141 2274.1852,-148.4273 2298.1785,-160.8249 2316.6951,-171.5366"/>
<polygon fill="#000000" stroke="#000000" points="2314.9264,-174.5569 2325.3164,-176.6306 2318.4873,-168.5302 2314.9264,-174.5569"/>
<text text-anchor="middle" x="2308.2953" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- methylation_array_file -->
<g id="node15" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1801.2953" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1801.2953" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge24" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1843.5557,-349.1108C1875.5787,-337.1795 1920.9725,-322.0979 1962.2953,-315 2198.087,-274.4986 2263.9509,-334.1408 2500.2953,-297 2505.7032,-296.1502 2511.3043,-294.9837 2516.8348,-293.6498"/>
<polygon fill="#000000" stroke="#000000" points="2517.8568,-297.0005 2526.6564,-291.0999 2516.0978,-290.2251 2517.8568,-297.0005"/>
<text text-anchor="middle" x="2053.7953" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge25" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1791.2024,-348.0492C1776.5474,-319.3123 1754.0447,-262.6939 1782.2953,-228 1807.2274,-197.3814 1832.3321,-223.8865 1869.2953,-210 1927.6095,-188.0923 1934.595,-166.7988 1991.2953,-141 2012.9363,-131.1533 2038.1203,-122.2408 2058.0495,-115.7469"/>
<polygon fill="#000000" stroke="#000000" points="2059.2021,-119.053 2067.6582,-112.6698 2057.0672,-112.3865 2059.2021,-119.053"/>
<text text-anchor="middle" x="1873.7953" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1806.0062,-347.6762C1813.4088,-323.0813 1830.3343,-280.2597 1862.2953,-261 1904.9648,-235.2874 2266.0853,-265.963 2310.2953,-243 2320.8221,-237.5323 2329.3365,-227.797 2335.6924,-218.2871"/>
<polygon fill="#000000" stroke="#000000" points="2338.6848,-220.1026 2340.9185,-209.7459 2332.7138,-216.4491 2338.6848,-220.1026"/>
<text text-anchor="middle" x="1953.7953" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node16" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="1731.2953" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="1731.2953" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge36" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1650.6145,-179.9167C1636.5166,-177.8843 1621.9845,-175.8395 1608.2953,-174 1543.0603,-165.234 1523.1289,-178.5621 1461.2953,-156 1449.8306,-151.8167 1449.2383,-146.4026 1438.2953,-141 1423.0261,-133.4616 1405.7762,-126.7467 1389.8646,-121.2178"/>
<polygon fill="#000000" stroke="#000000" points="1390.7543,-117.8239 1380.16,-117.9318 1388.5092,-124.4541 1390.7543,-117.8239"/>
<text text-anchor="middle" x="1590.7953" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge30" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1727.6817,-174.0031C1725.6483,-164.2116 1722.9835,-151.9052 1720.2953,-141 1714.5265,-117.5979 1704.8697,-108.7312 1715.2953,-87 1725.9457,-64.8003 1747.6051,-47.4894 1766.5217,-35.7591"/>
<polygon fill="#000000" stroke="#000000" points="1768.4153,-38.7057 1775.2482,-30.6086 1764.8573,-32.6774 1768.4153,-38.7057"/>
<text text-anchor="middle" x="1801.2953" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- pathology_file -->
<g id="node17" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2412.2953" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2412.2953" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge38" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2412.8474,-347.638C2414.1501,-336.739 2417.6006,-323.4436 2426.2953,-315 2450.5774,-291.4191 2467.5716,-305.6511 2500.2953,-297 2504.9966,-295.7571 2509.8847,-294.4274 2514.7659,-293.0745"/>
<polygon fill="#000000" stroke="#000000" points="2516.03,-296.3551 2524.7138,-290.2852 2514.1402,-289.615 2516.03,-296.3551"/>
<text text-anchor="middle" x="2487.2953" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge37" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2482.959,-359.2805C2521.4716,-355.717 2569.9836,-351.388 2613.2953,-348 2643.1598,-345.6639 2861.8327,-351.8776 2882.2953,-330 2886.8492,-325.1311 2885.1045,-321.0459 2882.2953,-315 2866.6127,-281.2488 2851.4355,-277.9355 2818.2953,-261 2720.005,-210.7713 2445.1663,-159.1934 2336.2953,-141 2245.6478,-125.8519 2218.8708,-147.5109 2130.2953,-123 2128.3331,-122.457 2126.3493,-121.8119 2124.3729,-121.094"/>
<polygon fill="#000000" stroke="#000000" points="2125.2638,-117.6724 2114.6881,-117.0352 2122.5581,-124.1284 2125.2638,-117.6724"/>
<text text-anchor="middle" x="2835.2953" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge39" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2404.2398,-348.0077C2398.1699,-334.1809 2389.8083,-314.5415 2383.2953,-297 2377.9962,-282.728 2366.1754,-245.7172 2357.971,-219.6959"/>
<polygon fill="#000000" stroke="#000000" points="2361.2584,-218.4821 2354.9187,-209.9933 2354.581,-220.5827 2361.2584,-218.4821"/>
<text text-anchor="middle" x="2444.2953" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- exposure -->
<g id="node18" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="53.2953" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="53.2953" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M80.6183,-176.3897C103.6891,-164.1315 138.0307,-148.0038 170.2953,-141 289.1004,-115.2104 1143.7604,-138.8461 1264.2953,-123 1270.1058,-122.2361 1276.1245,-121.1755 1282.0939,-119.9476"/>
<polygon fill="#000000" stroke="#000000" points="1283.0397,-123.3231 1292.048,-117.7462 1281.5281,-116.4882 1283.0397,-123.3231"/>
<text text-anchor="middle" x="213.7953" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- study_arm -->
<g id="node19" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2199.2953" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2199.2953" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge6" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2157.4572,-91.9766C2120.5706,-80.8226 2065.2315,-64.8839 2016.2953,-54 1958.1528,-41.0686 1890.2403,-30.4308 1846.5455,-24.154"/>
<polygon fill="#000000" stroke="#000000" points="1846.914,-20.6713 1836.5211,-22.7295 1845.9292,-27.6016 1846.914,-20.6713"/>
<text text-anchor="middle" x="2119.7953" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- follow_up -->
<g id="node20" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="180.2953" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="180.2953" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M209.6208,-176.6573C234.7692,-164.3827 272.3681,-148.0923 307.2953,-141 515.7455,-98.6724 1053.4384,-150.9729 1264.2953,-123 1270.1049,-122.2293 1276.123,-121.1642 1282.092,-119.9337"/>
<polygon fill="#000000" stroke="#000000" points="1283.0391,-123.3089 1292.0458,-117.7295 1281.5256,-116.4744 1283.0391,-123.3089"/>
<text text-anchor="middle" x="352.2953" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- publication -->
<g id="node22" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="2340.2953" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="2340.2953" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge9" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2301.1422,-90.7C2267.4468,-78.9798 2217.2932,-62.9217 2172.2953,-54 2057.1258,-31.1654 1918.8505,-22.6152 1848.0713,-19.5716"/>
<polygon fill="#000000" stroke="#000000" points="1847.8524,-16.0597 1837.7169,-19.1452 1847.5644,-23.0538 1847.8524,-16.0597"/>
<text text-anchor="middle" x="2279.2953" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge19" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2392.1037,-196.6304C2438.3007,-202.2964 2508.2276,-213.0186 2530.2953,-228 2539.0377,-233.9351 2545.9918,-243.0367 2551.2183,-251.9171"/>
<polygon fill="#000000" stroke="#000000" points="2548.2438,-253.7771 2556.042,-260.9492 2554.4184,-250.4795 2548.2438,-253.7771"/>
<text text-anchor="middle" x="2580.7953" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2306.9145,-186.6629C2251.8949,-179.713 2152.8988,-167.1358 2068.2953,-156 2018.9392,-149.5036 2006.8473,-145.7774 1957.2953,-141 1903.934,-135.8554 1559.7507,-117.0335 1407.9916,-108.8465"/>
<polygon fill="#000000" stroke="#000000" points="1408.0153,-105.3428 1397.8413,-108.2993 1407.6384,-112.3327 1408.0153,-105.3428"/>
<text text-anchor="middle" x="2104.7953" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge20" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2306.3342,-187.5248C2270.1241,-182.7372 2217.4619,-173.3617 2174.2953,-156 2154.8343,-148.1728 2134.8719,-135.6652 2119.6339,-124.9957"/>
<polygon fill="#000000" stroke="#000000" points="2121.4121,-121.9638 2111.2475,-118.9754 2117.33,-127.6503 2121.4121,-121.9638"/>
<text text-anchor="middle" x="2210.7953" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cytogenomic_file -->
<g id="node24" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="3069.2953" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="3069.2953" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;cell_line -->
<g id="edge2" class="edge">
<title>cytogenomic_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M3001.0539,-354.2668C2899.6494,-336.8316 2711.1755,-304.4261 2618.1456,-288.4308"/>
<polygon fill="#000000" stroke="#000000" points="2618.5438,-284.948 2608.0953,-286.7028 2617.3576,-291.8467 2618.5438,-284.948"/>
<text text-anchor="middle" x="2917.7953" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;pdx -->
<g id="edge1" class="edge">
<title>cytogenomic_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M3136.9898,-354.0765C3169.8519,-344.5121 3206.4392,-327.4157 3226.2953,-297 3291.9319,-196.4574 3200.3367,-187.7048 3061.2953,-141 2963.2169,-108.0549 2230.8898,-147.197 2130.2953,-123 2128.0945,-122.4706 2125.8716,-121.7965 2123.6659,-121.0216"/>
<polygon fill="#000000" stroke="#000000" points="2124.805,-117.7052 2114.2266,-117.1152 2122.1282,-124.1732 2124.805,-117.7052"/>
<text text-anchor="middle" x="3318.7953" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3074.0076,-347.6125C3080.4354,-317.7302 3087.7517,-258.868 3055.2953,-228 3031.7861,-205.6414 2565.3149,-195.6558 2403.7875,-192.8589"/>
<polygon fill="#000000" stroke="#000000" points="2403.6552,-189.3563 2393.5969,-192.6851 2403.5357,-196.3553 2403.6552,-189.3563"/>
<text text-anchor="middle" x="3150.7953" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- synonym -->
<g id="node25" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1698.2953" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1698.2953" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1649.6347,-272.5115C1578.5394,-262.151 1450.952,-239.9476 1416.2953,-210 1391.2539,-188.3612 1408.9862,-166.8301 1388.2953,-141 1384.2408,-135.9385 1379.2893,-131.2963 1374.0705,-127.1493"/>
<polygon fill="#000000" stroke="#000000" points="1375.8765,-124.1338 1365.74,-121.0512 1371.7417,-129.7822 1375.8765,-124.1338"/>
<text text-anchor="middle" x="1458.7953" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge34" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1714.2787,-261.7293C1725.7326,-250.4091 1742.1164,-236.2322 1759.2953,-228 1796.0818,-210.3718 1819.2551,-237.5969 1849.2953,-210 1872.8084,-188.3993 1853.0506,-168.4876 1869.2953,-141 1875.0514,-131.26 1882.9657,-133.4525 1887.2953,-123 1893.4182,-108.2179 1894.2161,-101.4258 1887.2953,-87 1876.6449,-64.8003 1854.9854,-47.4894 1836.0689,-35.7591"/>
<polygon fill="#000000" stroke="#000000" points="1837.7333,-32.6774 1827.3424,-30.6086 1834.1752,-38.7057 1837.7333,-32.6774"/>
<text text-anchor="middle" x="1911.7953" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge35" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1743.4242,-269.9094C1761.6364,-266.5761 1782.8943,-263.1069 1802.2953,-261 1890.754,-251.3935 2117.5968,-270.2654 2202.2953,-243 2213.9122,-239.2604 2214.2034,-233.09 2225.2953,-228 2248.9882,-217.1274 2276.7435,-208.704 2299.9811,-202.7484"/>
<polygon fill="#000000" stroke="#000000" points="2301.1115,-206.074 2309.9728,-200.2665 2299.424,-199.2805 2301.1115,-206.074"/>
<text text-anchor="middle" x="2267.7953" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
</g>
</svg>
</div>
