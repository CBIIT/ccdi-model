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
<svg width="3236pt" height="392pt"
 viewBox="0.00 0.00 3236.06 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3232.0585,-388 3232.0585,4 -4,4"/>
<!-- sample -->
<g id="node1" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1467.8648" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1467.8648" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- cell_line -->
<g id="node4" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="1152.8648" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="1152.8648" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge30" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1498.9983,-266.0316C1518.5885,-256.1013 1537.9018,-241.8058 1524.8648,-228 1500.8716,-202.5921 1245.252,-216.2251 1210.8648,-210 1206.7214,-209.2499 1202.4592,-208.2958 1198.2162,-207.2196"/>
<polygon fill="#000000" stroke="#000000" points="1198.9853,-203.8012 1188.4152,-204.5252 1197.1297,-210.5508 1198.9853,-203.8012"/>
<text text-anchor="middle" x="1566.3648" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- participant -->
<g id="node11" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="2240.8648" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="2240.8648" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1501.581,-267.1248C1509.4635,-264.7442 1517.8887,-262.5129 1525.8648,-261 1601.1761,-246.7147 2155.0664,-259.1794 2213.8648,-210 2235.9997,-191.4862 2241.306,-157.4888 2242.0016,-133.1933"/>
<polygon fill="#000000" stroke="#000000" points="2245.5017,-133.1422 2242.047,-123.1264 2238.5018,-133.1105 2245.5017,-133.1422"/>
<text text-anchor="middle" x="2271.3648" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node20" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="988.8648" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="988.8648" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge29" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1432.624,-267.9498C1425.1197,-265.6285 1417.2361,-263.2137 1409.8648,-261 1382.3838,-252.7473 1374.4341,-253.8341 1347.8648,-243 1334.7921,-237.6694 1333.4097,-231.9804 1319.8648,-228 1223.6151,-199.7155 1194.4137,-222.4096 1094.8648,-210 1071.8356,-207.1292 1046.1736,-202.8014 1025.8677,-199.1088"/>
<polygon fill="#000000" stroke="#000000" points="1026.2488,-195.6201 1015.7796,-197.2468 1024.9782,-202.5038 1026.2488,-195.6201"/>
<text text-anchor="middle" x="1384.3648" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node2" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="402.8648" cy="-366" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="402.8648" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M495.5284,-352.6173C582.2627,-340.6538 715.5596,-323.7076 831.8648,-315 960.0128,-305.4058 1283.1251,-318.2376 1409.8648,-297 1414.6804,-296.193 1419.6519,-295.089 1424.5653,-293.8217"/>
<polygon fill="#000000" stroke="#000000" points="1425.8177,-297.1055 1434.5003,-291.034 1423.9266,-290.3658 1425.8177,-297.1055"/>
<text text-anchor="middle" x="940.3648" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge12" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M401.9051,-347.8978C401.729,-323.9641 405.4226,-282.3363 430.8648,-261 481.7065,-218.3631 959.9355,-217.4919 1025.8648,-210 1049.3699,-207.329 1075.2362,-203.7752 1097.4566,-200.5313"/>
<polygon fill="#000000" stroke="#000000" points="1098.0054,-203.9883 1107.3878,-199.0669 1096.9842,-197.0631 1098.0054,-203.9883"/>
<text text-anchor="middle" x="539.3648" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge11" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M271.0204,-360.722C169.5691,-353.5635 41.2333,-336.7028 7.8648,-297 -2.4296,-284.7515 -2.7587,-272.9642 7.8648,-261 39.7516,-225.0889 773.5682,-198.9965 950.6621,-193.2086"/>
<polygon fill="#000000" stroke="#000000" points="950.9265,-196.702 960.8077,-192.8794 950.6994,-189.7057 950.9265,-196.702"/>
<text text-anchor="middle" x="116.3648" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- pathology_file -->
<g id="node3" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1922.8648" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1922.8648" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1854.0764,-358.2627C1804.9593,-352.1525 1737.481,-342.5638 1678.8648,-330 1654.9277,-324.8693 1649.7178,-320.5083 1625.8648,-315 1581.864,-304.839 1569.7344,-307.7127 1525.8648,-297 1521.4238,-295.9155 1516.8233,-294.6821 1512.2448,-293.3812"/>
<polygon fill="#000000" stroke="#000000" points="1512.9086,-289.928 1502.327,-290.4573 1510.9291,-296.6423 1512.9086,-289.928"/>
<text text-anchor="middle" x="1739.8648" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge27" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1932.9224,-347.9053C1937.1916,-337.6238 1939.9416,-324.8738 1933.8648,-315 1905.9444,-269.635 1877.3557,-277.9762 1826.8648,-261 1566.4744,-173.4507 1481.5683,-256.7721 1210.8648,-210 1206.7155,-209.2831 1202.4493,-208.3518 1198.2036,-207.2904"/>
<polygon fill="#000000" stroke="#000000" points="1198.9673,-203.871 1188.3988,-204.6176 1197.1262,-210.6245 1198.9673,-203.871"/>
<text text-anchor="middle" x="1979.8648" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge28" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1922.9171,-347.7898C1921.896,-336.5172 1918.5314,-322.7589 1908.8648,-315 1877.5448,-289.8611 1583.3273,-315.8497 1547.8648,-297 1530.2045,-287.6129 1537.5264,-272.0629 1520.8648,-261 1493.3856,-242.7545 1479.6365,-254.8784 1448.8648,-243 1435.6943,-237.916 1434.4578,-231.813 1420.8648,-228 1351.0064,-208.4039 1166.9675,-218.0863 1094.8648,-210 1071.802,-207.4135 1046.139,-203.0938 1025.841,-199.3344"/>
<polygon fill="#000000" stroke="#000000" points="1026.2333,-195.8467 1015.7577,-197.4317 1024.9353,-202.7254 1026.2333,-195.8467"/>
<text text-anchor="middle" x="1608.8648" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1188.7571,-204.4496C1196.0042,-206.5906 1203.6224,-208.5799 1210.8648,-210 1256.3928,-218.9271 1377.0053,-207.9929 1418.8648,-228 1430.8951,-233.75 1441.5361,-243.7987 1449.8017,-253.4646"/>
<polygon fill="#000000" stroke="#000000" points="1447.1752,-255.7837 1456.1646,-261.391 1452.634,-251.4017 1447.1752,-255.7837"/>
<text text-anchor="middle" x="1480.3648" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- study -->
<g id="node6" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2449.8648" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2449.8648" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge6" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1175.5995,-175.7709C1193.3141,-164.016 1218.9988,-148.862 1243.8648,-141 1466.5249,-70.6001 2209.4042,-29.8258 2403.2666,-20.2165"/>
<polygon fill="#000000" stroke="#000000" points="2403.587,-23.7051 2413.4029,-19.7178 2403.2429,-16.7136 2403.587,-23.7051"/>
<text text-anchor="middle" x="1573.3648" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1184.3691,-178.0188C1214.0193,-165.6375 1260.0001,-148.4132 1301.8648,-141 1491.8397,-107.3602 1978.6772,-148.8733 2169.8648,-123 2175.3779,-122.2539 2181.0803,-121.2371 2186.7463,-120.0639"/>
<polygon fill="#000000" stroke="#000000" points="2187.8592,-123.4018 2196.8569,-117.808 2186.3347,-116.5698 2187.8592,-123.4018"/>
<text text-anchor="middle" x="1342.3648" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- synonym -->
<g id="node5" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2469.8648" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2469.8648" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge33" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2419.1036,-361.9435C2307.3893,-353.0571 2031.7956,-331.3596 1800.8648,-315 1678.6872,-306.3447 1646.3002,-319.3066 1525.8648,-297 1521.0636,-296.1107 1516.1014,-294.9541 1511.1935,-293.656"/>
<polygon fill="#000000" stroke="#000000" points="1511.8406,-290.2014 1501.2647,-290.833 1509.9262,-296.9345 1511.8406,-290.2014"/>
<text text-anchor="middle" x="2045.3648" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge35" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2521.7062,-363.7745C2665.6771,-356.9083 3059.8648,-333.1634 3059.8648,-279 3059.8648,-279 3059.8648,-279 3059.8648,-105 3059.8648,-48.1223 2638.8533,-25.7035 2496.3597,-19.7447"/>
<polygon fill="#000000" stroke="#000000" points="2496.3313,-16.2406 2486.1962,-19.3279 2496.0444,-23.2348 2496.3313,-16.2406"/>
<text text-anchor="middle" x="3102.3648" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2472.1759,-347.8967C2475.8552,-312.4133 2479.9314,-232.1194 2450.8648,-174 2421.4303,-115.1452 2376.215,-136.7595 2311.8648,-123 2306.9392,-121.9468 2301.8382,-120.7886 2296.7339,-119.5831"/>
<polygon fill="#000000" stroke="#000000" points="2297.5015,-116.168 2286.9592,-117.2218 2295.8576,-122.9722 2297.5015,-116.168"/>
<text text-anchor="middle" x="2512.3648" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study_arm -->
<g id="node7" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2100.8648" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2100.8648" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge36" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2119.1967,-87.6245C2132.4792,-76.1037 2151.4475,-61.7326 2170.8648,-54 2212.1346,-37.5649 2335.631,-26.3092 2403.656,-21.1708"/>
<polygon fill="#000000" stroke="#000000" points="2403.9612,-24.6579 2413.675,-20.428 2403.4435,-17.677 2403.9612,-24.6579"/>
<text text-anchor="middle" x="2219.3648" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- family_relationship -->
<g id="node8" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="2104.8648" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="2104.8648" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge39" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2079.6152,-174.5449C2068.1153,-164.4766 2058.8653,-151.7266 2067.8648,-141 2082.6585,-123.367 2147.3606,-127.8314 2169.8648,-123 2174.7894,-121.9427 2179.8898,-120.7817 2184.9938,-119.5744"/>
<polygon fill="#000000" stroke="#000000" points="2185.8709,-122.9632 2194.7679,-117.2106 2184.2254,-116.1594 2185.8709,-122.9632"/>
<text text-anchor="middle" x="2147.3648" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- diagnosis -->
<g id="node9" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="2386.8648" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="2386.8648" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2360.4253,-176.245C2337.0499,-162.3158 2302.743,-141.8727 2276.8669,-126.4533"/>
<polygon fill="#000000" stroke="#000000" points="2278.4797,-123.3401 2268.0975,-121.2277 2274.8963,-129.3534 2278.4797,-123.3401"/>
<text text-anchor="middle" x="2366.3648" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- follow_up -->
<g id="node10" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="2552.8648" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="2552.8648" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2530.1515,-175.4944C2510.12,-161.0035 2483.677,-142.0624 2480.8648,-141 2410.203,-114.3056 2386.2179,-136.315 2311.8648,-123 2306.7542,-122.0848 2301.4679,-121.0037 2296.1918,-119.8329"/>
<polygon fill="#000000" stroke="#000000" points="2296.6397,-116.3438 2286.1071,-117.4908 2295.056,-123.1623 2296.6397,-116.3438"/>
<text text-anchor="middle" x="2546.8648" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge17" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2253.8171,-87.3042C2262.948,-76.0973 2276.139,-62.2173 2290.8648,-54 2325.6553,-34.5862 2370.2596,-25.6376 2403.3662,-21.5152"/>
<polygon fill="#000000" stroke="#000000" points="2404.1448,-24.9492 2413.6841,-20.3392 2403.352,-17.9943 2404.1448,-24.9492"/>
<text text-anchor="middle" x="2341.3648" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- exposure -->
<g id="node12" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="2679.8648" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="2679.8648" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2652.0592,-176.5764C2641.0185,-170.3315 2628.2589,-162.9627 2616.8648,-156 2606.4511,-149.6365 2605.4461,-144.8485 2593.8648,-141 2474.6843,-101.396 2435.9278,-142.5145 2311.8648,-123 2306.526,-122.1602 2301.003,-121.1032 2295.5041,-119.9242"/>
<polygon fill="#000000" stroke="#000000" points="2296.2041,-116.4941 2285.6771,-117.6908 2294.6527,-123.32 2296.2041,-116.4941"/>
<text text-anchor="middle" x="2660.3648" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- publication -->
<g id="node13" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="2383.8648" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="2383.8648" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge10" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2388.8506,-86.8548C2392.2625,-76.5565 2397.5125,-63.8065 2404.8648,-54 2408.9777,-48.5141 2414.1134,-43.3855 2419.4296,-38.816"/>
<polygon fill="#000000" stroke="#000000" points="2421.6379,-41.5315 2427.2494,-32.5447 2417.2585,-36.0707 2421.6379,-41.5315"/>
<text text-anchor="middle" x="2455.8648" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- study_funding -->
<g id="node14" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2541.8648" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2541.8648" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge23" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2532.0844,-87.1335C2525.791,-76.6816 2516.9226,-63.6814 2506.8648,-54 2500.0529,-47.4431 2491.8644,-41.4397 2483.8463,-36.2933"/>
<polygon fill="#000000" stroke="#000000" points="2485.6434,-33.2897 2475.2859,-31.0597 2481.992,-39.262 2485.6434,-33.2897"/>
<text text-anchor="middle" x="2580.8648" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- sequencing_file -->
<g id="node15" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="655.8648" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="655.8648" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M736.3797,-361.2337C816.7941,-355.8783 943.7929,-345.8063 1052.8648,-330 1086.5068,-325.1247 1094.1606,-319.4259 1127.8648,-315 1252.3841,-298.6485 1286.3582,-319.7721 1409.8648,-297 1414.6666,-296.1146 1419.6293,-294.9605 1424.5375,-293.6638"/>
<polygon fill="#000000" stroke="#000000" points="1425.8041,-296.9426 1434.4666,-290.8425 1423.8907,-290.2091 1425.8041,-296.9426"/>
<text text-anchor="middle" x="1194.3648" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge2" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M651.9824,-347.8037C648.1185,-324.1565 645.6804,-283.2657 668.8648,-261 686.3147,-244.2416 861.8934,-246.2742 885.8648,-243 960.9799,-232.7401 1046.9632,-215.2737 1100.595,-203.6856"/>
<polygon fill="#000000" stroke="#000000" points="1101.5215,-207.066 1110.5499,-201.5218 1100.0346,-200.2257 1101.5215,-207.066"/>
<text text-anchor="middle" x="735.3648" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge3" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M590.2745,-354.8524C576.9041,-352.5827 562.9317,-350.2128 549.8648,-348 412.1447,-324.6781 153.7857,-364.2465 247.8648,-261 295.5663,-208.6503 805.1421,-195.3578 950.4122,-192.6208"/>
<polygon fill="#000000" stroke="#000000" points="950.6865,-196.1165 960.621,-192.4347 950.5588,-189.1177 950.6865,-196.1165"/>
<text text-anchor="middle" x="314.3648" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- therapeutic_procedure -->
<g id="node16" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="1337.8648" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="1337.8648" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1358.0733,-174.2182C1372.9353,-162.3479 1394.2351,-147.7257 1415.8648,-141 1495.887,-116.1172 2086.8378,-134.3685 2169.8648,-123 2175.3767,-122.2453 2181.0784,-121.2228 2186.7439,-120.0461"/>
<polygon fill="#000000" stroke="#000000" points="2187.8584,-123.3835 2196.854,-117.7861 2186.3312,-116.5521 2187.8584,-123.3835"/>
<text text-anchor="middle" x="1508.8648" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- cytogenomic_file -->
<g id="node17" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1486.8648" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1486.8648" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1482.9279,-347.9735C1480.3549,-336.1918 1476.9412,-320.5607 1474.0142,-307.1581"/>
<polygon fill="#000000" stroke="#000000" points="1477.3496,-306.0263 1471.7965,-297.0034 1470.5108,-307.5199 1477.3496,-306.0263"/>
<text text-anchor="middle" x="1550.3648" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;cell_line -->
<g id="edge15" class="edge">
<title>cytogenomic_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1553.1868,-353.7945C1576.7507,-348.1765 1603.0703,-340.3949 1625.8648,-330 1637.6422,-324.6291 1667.8385,-308.456 1673.8648,-297 1681.3135,-282.8396 1682.3172,-274.5852 1673.8648,-261 1656.3293,-232.8161 1639.0139,-236.2618 1606.8648,-228 1436.2275,-184.1489 1384.4114,-240.3574 1210.8648,-210 1206.717,-209.2745 1202.4519,-208.3372 1198.2068,-207.272"/>
<polygon fill="#000000" stroke="#000000" points="1198.9719,-203.8528 1188.403,-204.5936 1197.1271,-210.6053 1198.9719,-203.8528"/>
<text text-anchor="middle" x="1751.3648" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;pdx -->
<g id="edge16" class="edge">
<title>cytogenomic_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1410.2817,-356.508C1356.2016,-349.2829 1288.7606,-339.0695 1261.8648,-330 1248.4872,-325.489 1247.3802,-319.0793 1233.8648,-315 1193.2626,-302.7452 1079.0737,-320.6442 1043.8648,-297 1017.4061,-279.2319 1002.8313,-244.5324 995.4453,-219.8909"/>
<polygon fill="#000000" stroke="#000000" points="998.7538,-218.7241 992.7063,-210.0248 992.0089,-220.5966 998.7538,-218.7241"/>
<text text-anchor="middle" x="1115.3648" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node18" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="2893.8648" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="2893.8648" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge38" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2901.8512,-173.7713C2905.2479,-162.9225 2906.8261,-149.633 2898.8648,-141 2865.3103,-104.6148 2717.1252,-151.7901 2676.8648,-123 2649.6641,-103.5489 2673.0609,-74.7842 2646.8648,-54 2624.0593,-35.906 2546.7911,-26.0795 2496.0728,-21.4468"/>
<polygon fill="#000000" stroke="#000000" points="2496.2626,-17.9501 2485.9948,-20.5623 2495.6505,-24.9233 2496.2626,-17.9501"/>
<text text-anchor="middle" x="2762.8648" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge37" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2810.9267,-180.319C2783.511,-174.843 2753.2806,-167.0165 2726.8648,-156 2715.601,-151.3025 2715.48,-144.745 2703.8648,-141 2620.869,-114.2408 2398.126,-135.7803 2311.8648,-123 2306.44,-122.1963 2300.8282,-121.1526 2295.2461,-119.9725"/>
<polygon fill="#000000" stroke="#000000" points="2295.8027,-116.5101 2285.2776,-117.7235 2294.2621,-123.3385 2295.8027,-116.5101"/>
<text text-anchor="middle" x="2812.8648" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- study_personnel -->
<g id="node19" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2944.8648" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2944.8648" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge24" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2882.8138,-92.2845C2829.5966,-81.543 2750.821,-66.0315 2681.8648,-54 2617.0974,-42.6993 2541.8429,-31.3473 2495.0295,-24.4949"/>
<polygon fill="#000000" stroke="#000000" points="2495.3134,-20.9994 2484.9129,-23.0194 2494.303,-27.9261 2495.3134,-20.9994"/>
<text text-anchor="middle" x="2830.3648" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1015.7156,-197.2883C1065.9003,-207.072 1177.3929,-228.3352 1271.8648,-243 1332.9856,-252.4878 1349.4401,-247.785 1409.8648,-261 1414.5125,-262.0165 1419.3239,-263.2339 1424.0968,-264.5498"/>
<polygon fill="#000000" stroke="#000000" points="1423.1958,-267.9327 1433.7749,-267.3564 1425.1455,-261.2096 1423.1958,-267.9327"/>
<text text-anchor="middle" x="1295.8648" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge20" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1010.9877,-180.9768C1056.8277,-158.7226 1166.0789,-108.7036 1263.8648,-87 1486.9102,-37.495 2212.1643,-21.9975 2403.3272,-18.7229"/>
<polygon fill="#000000" stroke="#000000" points="2403.3902,-22.2224 2413.3298,-18.5544 2403.2723,-15.2234 2403.3902,-22.2224"/>
<text text-anchor="middle" x="1287.8648" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study_admin -->
<g id="node21" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="3157.8648" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="3157.8648" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge18" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3136.1468,-87.6979C3119.9837,-75.8922 3096.8343,-61.1467 3073.8648,-54 3019.2707,-37.0138 2631.6295,-23.596 2496.3254,-19.3841"/>
<polygon fill="#000000" stroke="#000000" points="2496.378,-15.8841 2486.2747,-19.0737 2496.1619,-22.8808 2496.378,-15.8841"/>
<text text-anchor="middle" x="3161.3648" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- medical_history -->
<g id="node22" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1558.8648" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1558.8648" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1578.1978,-174.2871C1592.4418,-162.4492 1612.9075,-147.8376 1633.8648,-141 1747.1652,-104.0343 2051.8681,-139.7402 2169.8648,-123 2175.2943,-122.2297 2180.9094,-121.2081 2186.4934,-120.0418"/>
<polygon fill="#000000" stroke="#000000" points="2187.4708,-123.4097 2196.4643,-117.8091 2185.9412,-116.5789 2187.4708,-123.4097"/>
<text text-anchor="middle" x="1701.8648" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- methylation_array_file -->
<g id="node23" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1222.8648" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1222.8648" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge40" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1241.1563,-347.988C1253.7866,-336.6476 1271.5512,-322.7376 1289.8648,-315 1339.5426,-294.0107 1357.293,-309.0271 1409.8648,-297 1414.5026,-295.939 1419.3075,-294.6927 1424.0765,-293.3595"/>
<polygon fill="#000000" stroke="#000000" points="1425.1335,-296.6971 1433.75,-290.5323 1423.1697,-289.9782 1425.1335,-296.6971"/>
<text text-anchor="middle" x="1381.3648" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge42" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1218.1755,-347.9943C1215.5611,-338.2001 1212.1731,-325.8941 1208.8648,-315 1201.5137,-290.7934 1201.0086,-284.1755 1190.8648,-261 1184.5107,-246.483 1176.1234,-230.9711 1168.8453,-218.3393"/>
<polygon fill="#000000" stroke="#000000" points="1171.8619,-216.5644 1163.7866,-209.7057 1165.8223,-220.1032 1171.8619,-216.5644"/>
<text text-anchor="middle" x="1295.3648" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge41" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1107.9569,-363.6239C994.559,-360.0591 835.3534,-351.2886 815.8648,-330 805.0278,-318.1622 790.0364,-275.7223 838.8648,-228 854.6443,-212.5779 912.2543,-202.0943 951.3087,-196.5811"/>
<polygon fill="#000000" stroke="#000000" points="951.8545,-200.0392 961.291,-195.2222 950.9103,-193.1031 951.8545,-200.0392"/>
<text text-anchor="middle" x="905.3648" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- molecular_test -->
<g id="node24" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1741.8648" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1741.8648" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1754.7435,-174.1826C1764.341,-162.4591 1778.5655,-148.0274 1794.8648,-141 1871.4767,-107.9689 2087.3491,-135.3129 2169.8648,-123 2175.2886,-122.1907 2180.8999,-121.1432 2186.4816,-119.9608"/>
<polygon fill="#000000" stroke="#000000" points="2187.4668,-123.3265 2196.4498,-117.7091 2185.9243,-116.4986 2187.4668,-123.3265"/>
<text text-anchor="middle" x="1858.8648" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- radiology_file -->
<g id="node25" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1912.8648" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1912.8648" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1918.3013,-173.7863C1922.7208,-162.3607 1930.1747,-148.4316 1941.8648,-141 1984.7557,-113.7332 2119.7186,-131.2747 2169.8648,-123 2175.1971,-122.1201 2180.7158,-121.0363 2186.212,-119.8404"/>
<polygon fill="#000000" stroke="#000000" points="2187.0715,-123.2343 2196.0357,-117.5869 2185.5063,-116.4115 2187.0715,-123.2343"/>
<text text-anchor="middle" x="2000.8648" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
</g>
</svg>
</div>
