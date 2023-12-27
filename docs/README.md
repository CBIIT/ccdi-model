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
<svg width="4006pt" height="392pt"
 viewBox="0.00 0.00 4006.21 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 4002.2114,-388 4002.2114,4 -4,4"/>
<!-- study_admin -->
<g id="node1" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1303.8683" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1303.8683" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study -->
<g id="node19" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="3241.8683" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="3241.8683" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge11" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1298.613,-87.0059C1296.5924,-75.967 1296.4729,-62.3869 1304.8683,-54 1322.1296,-36.7564 2900.7258,-21.1846 3194.9427,-18.4308"/>
<polygon fill="#000000" stroke="#000000" points="3195.2897,-21.9278 3205.2565,-18.3346 3195.2243,-14.9281 3195.2897,-21.9278"/>
<text text-anchor="middle" x="1361.3683" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- synonym -->
<g id="node2" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2630.8683" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2630.8683" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- sample -->
<g id="node6" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1434.8683" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1434.8683" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2579.2665,-363.0399C2360.5498,-350.4724 1519.9601,-301.9506 1492.8683,-297 1488.065,-296.1223 1483.1014,-294.973 1478.1927,-293.6792"/>
<polygon fill="#000000" stroke="#000000" points="1478.8387,-290.2244 1468.263,-290.8612 1476.9275,-296.9585 1478.8387,-290.2244"/>
<text text-anchor="middle" x="2049.3683" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- participant -->
<g id="node16" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="2429.8683" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="2429.8683" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2636.3164,-347.801C2647.7177,-305.6107 2668.951,-200.2182 2616.8683,-141 2601.6119,-123.6535 2547.2881,-114.5177 2501.0956,-109.7976"/>
<polygon fill="#000000" stroke="#000000" points="2501.368,-106.3077 2491.0774,-108.8284 2500.6939,-113.2751 2501.368,-106.3077"/>
<text text-anchor="middle" x="2693.3683" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge20" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2682.8617,-365.0971C2846.7673,-361.569 3341.8683,-345.415 3341.8683,-279 3341.8683,-279 3341.8683,-279 3341.8683,-105 3341.8683,-70.9901 3308.5389,-47.2526 3280.3633,-33.2619"/>
<polygon fill="#000000" stroke="#000000" points="3281.6003,-29.976 3271.0612,-28.8901 3278.6228,-36.3112 3281.6003,-29.976"/>
<text text-anchor="middle" x="3384.3683" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- follow_up -->
<g id="node3" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="1831.8683" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="1831.8683" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1827.9435,-173.9742C1826.6807,-162.9227 1827.3787,-149.3403 1835.8683,-141 1854.1945,-122.9961 2202.7163,-111.2347 2357.1995,-106.8854"/>
<polygon fill="#000000" stroke="#000000" points="2357.6359,-110.3747 2367.5345,-106.5974 2357.4408,-103.3774 2357.6359,-110.3747"/>
<text text-anchor="middle" x="1880.8683" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- radiology_file -->
<g id="node4" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="2086.8683" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="2086.8683" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2104.5585,-174.3728C2117.1991,-162.8933 2135.211,-148.6728 2153.8683,-141 2189.8619,-126.1977 2289.8307,-115.7703 2359.0167,-110.0727"/>
<polygon fill="#000000" stroke="#000000" points="2359.3044,-113.5609 2368.9898,-109.2664 2358.7403,-106.5837 2359.3044,-113.5609"/>
<text text-anchor="middle" x="2212.8683" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- medical_history -->
<g id="node5" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2263.8683" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2263.8683" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2267.76,-173.9832C2271.0536,-162.9353 2276.8875,-149.3535 2286.8683,-141 2299.0473,-130.8066 2333.0107,-122.0377 2364.7818,-115.7068"/>
<polygon fill="#000000" stroke="#000000" points="2365.8333,-119.0686 2374.9896,-113.7383 2364.5078,-112.1953 2365.8333,-119.0686"/>
<text text-anchor="middle" x="2354.8683" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- pdx -->
<g id="node13" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1115.8683" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1115.8683" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge5" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1400.0345,-267.6966C1392.432,-265.3679 1384.4058,-263.0142 1376.8683,-261 1341.6592,-251.5915 1332.1979,-251.9452 1296.8683,-243 1245.8091,-230.0722 1187.22,-213.1837 1150.8702,-202.461"/>
<polygon fill="#000000" stroke="#000000" points="1151.8143,-199.0904 1141.2321,-199.6085 1149.8277,-205.8026 1151.8143,-199.0904"/>
<text text-anchor="middle" x="1333.3683" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1466.1677,-266.2886C1471.9799,-264.277 1478.0534,-262.4017 1483.8683,-261 1548.2857,-245.4723 1566.1039,-251.1094 1631.8683,-243 1749.2259,-228.5286 1789.6457,-261.9517 1895.8683,-210 1916.1948,-200.0586 1911.775,-184.4048 1931.8683,-174 2008.7559,-134.1857 2038.1756,-153.396 2123.8683,-141 2204.9836,-129.2661 2298.6171,-118.6821 2360.7269,-112.0748"/>
<polygon fill="#000000" stroke="#000000" points="2361.2231,-115.542 2370.7991,-111.0088 2360.4863,-108.5808 2361.2231,-115.542"/>
<text text-anchor="middle" x="1968.3683" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node23" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="1489.8683" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="1489.8683" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge4" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1445.9984,-261.3943C1453.826,-249.0124 1464.4357,-232.2297 1473.2605,-218.2704"/>
<polygon fill="#000000" stroke="#000000" points="1476.3695,-219.9024 1478.7548,-209.5796 1470.4527,-216.1619 1476.3695,-219.9024"/>
<text text-anchor="middle" x="1502.3683" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- therapeutic_procedure -->
<g id="node7" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="2484.8683" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="2484.8683" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2448.4226,-174.7731C2441.4135,-169.7337 2434.9827,-163.51 2430.8683,-156 2427.1238,-149.1653 2425.8355,-141.0031 2425.7572,-133.2337"/>
<polygon fill="#000000" stroke="#000000" points="2429.263,-133.2112 2426.2834,-123.044 2422.2723,-132.8502 2429.263,-133.2112"/>
<text text-anchor="middle" x="2523.8683" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- molecular_test -->
<g id="node8" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="2738.8683" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="2738.8683" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2703.3957,-175.8527C2691.0304,-169.9337 2677.1753,-162.9706 2664.8683,-156 2654.2493,-149.9855 2653.2329,-145.4479 2641.8683,-141 2596.9051,-123.4022 2543.2623,-114.3971 2501.1867,-109.794"/>
<polygon fill="#000000" stroke="#000000" points="2501.3334,-106.2905 2491.0263,-108.7428 2500.613,-113.2534 2501.3334,-106.2905"/>
<text text-anchor="middle" x="2728.8683" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- exposure -->
<g id="node9" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="2889.8683" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="2889.8683" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge41" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2857.7289,-177.4403C2844.5623,-171.1997 2829.2941,-163.6043 2815.8683,-156 2805.2493,-149.9855 2804.3803,-145.0512 2792.8683,-141 2740.9547,-122.731 2592.2157,-112.6749 2502.0515,-108.1006"/>
<polygon fill="#000000" stroke="#000000" points="2502.0582,-104.5967 2491.8967,-107.596 2501.7107,-111.5881 2502.0582,-104.5967"/>
<text text-anchor="middle" x="2859.3683" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- clinical_measure_file -->
<g id="node10" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="3196.8683" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="3196.8683" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge36" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3117.0943,-179.7121C3091.2084,-174.2169 3062.7609,-166.5327 3037.8683,-156 3026.629,-151.2444 3026.454,-144.8353 3014.8683,-141 2967.4059,-125.2882 2648.0334,-112.483 2502.2191,-107.3818"/>
<polygon fill="#000000" stroke="#000000" points="2502.142,-103.8771 2492.0265,-107.0278 2501.899,-110.8729 2502.142,-103.8771"/>
<text text-anchor="middle" x="3167.3683" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge15" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3256.2901,-176.8615C3274.6489,-170.9067 3291.4837,-163.6614 3296.8683,-156 3300.7017,-150.5457 3301.2738,-146.0036 3296.8683,-141 3255.1208,-93.5842 3197.6158,-170.4158 3155.8683,-123 3129.9252,-93.5344 3174.1783,-57.9475 3208.2455,-36.6879"/>
<polygon fill="#000000" stroke="#000000" points="3210.3317,-39.5166 3217.077,-31.3464 3206.7089,-33.5269 3210.3317,-39.5166"/>
<text text-anchor="middle" x="3241.8683" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- cytogenomic_file -->
<g id="node11" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1434.8683" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1434.8683" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge24" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1434.8683,-347.9735C1434.8683,-336.1918 1434.8683,-320.5607 1434.8683,-307.1581"/>
<polygon fill="#000000" stroke="#000000" points="1438.3684,-307.0033 1434.8683,-297.0034 1431.3684,-307.0034 1438.3684,-307.0033"/>
<text text-anchor="middle" x="1506.3683" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;pdx -->
<g id="edge25" class="edge">
<title>cytogenomic_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1369.692,-353.516C1341.4726,-347.4564 1308.2428,-339.4352 1278.8683,-330 1262.3654,-324.6992 1259.6418,-319.3695 1242.8683,-315 1209.0986,-306.2031 1110.0867,-323.0515 1086.8683,-297 1067.008,-274.7164 1082.6611,-239.997 1097.5857,-216.6469"/>
<polygon fill="#000000" stroke="#000000" points="1100.5198,-218.5557 1103.1945,-208.304 1094.7106,-214.6502 1100.5198,-218.5557"/>
<text text-anchor="middle" x="1158.3683" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;cell_line -->
<g id="edge23" class="edge">
<title>cytogenomic_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1499.3599,-353.4539C1524.5912,-347.6254 1553.5056,-339.7904 1578.8683,-330 1592.0388,-324.916 1594.0723,-320.9642 1606.8683,-315 1626.3923,-305.8999 1639.792,-314.8371 1651.8683,-297 1669.7686,-270.5607 1657.8821,-246.5132 1631.8683,-228 1600.7607,-205.8618 1584.8048,-219.6681 1547.8683,-210 1544.2379,-209.0497 1540.4957,-208.0158 1536.7432,-206.9397"/>
<polygon fill="#000000" stroke="#000000" points="1537.4368,-203.4952 1526.855,-204.0217 1535.4554,-210.209 1537.4368,-203.4952"/>
<text text-anchor="middle" x="1732.3683" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- sequencing_file -->
<g id="node12" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1881.8683" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1881.8683" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge38" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1805.3229,-358.862C1754.3269,-353.2115 1686.0585,-343.9215 1626.8683,-330 1606.3464,-325.1733 1602.238,-320.433 1581.8683,-315 1542.875,-304.5997 1531.9678,-306.9936 1492.8683,-297 1488.4392,-295.8679 1483.8466,-294.603 1479.2729,-293.2827"/>
<polygon fill="#000000" stroke="#000000" points="1479.9443,-289.8309 1469.3614,-290.3338 1477.9481,-296.5402 1479.9443,-289.8309"/>
<text text-anchor="middle" x="1693.3683" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge37" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1881.9177,-347.7935C1880.8954,-336.5224 1877.5305,-322.7643 1867.8683,-315 1837.2545,-290.3996 1549.5365,-315.4525 1514.8683,-297 1497.2134,-287.603 1502.0862,-275.0659 1487.8683,-261 1470.237,-243.5573 1465.9806,-236.9963 1442.8683,-228 1391.0612,-207.8344 1228.9477,-197.5204 1154.2527,-193.7362"/>
<polygon fill="#000000" stroke="#000000" points="1154.0503,-190.222 1143.8899,-193.2248 1153.7053,-197.2135 1154.0503,-190.222"/>
<text text-anchor="middle" x="1581.3683" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge39" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1891.5555,-348.1209C1895.7013,-337.9112 1898.4513,-325.1612 1892.8683,-315 1871.316,-275.7742 1849.2777,-277.9828 1807.8683,-261 1698.9174,-216.3171 1662.4223,-237.2807 1547.8683,-210 1544.0542,-209.0917 1540.1243,-208.0674 1536.1928,-206.9801"/>
<polygon fill="#000000" stroke="#000000" points="1537.0599,-203.5876 1526.4815,-204.1774 1535.1189,-210.3131 1537.0599,-203.5876"/>
<text text-anchor="middle" x="1947.3683" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge34" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1143.6934,-194.1133C1200.854,-198.7504 1329.5136,-210.7934 1369.8683,-228 1378.1957,-231.5507 1394.1139,-243.999 1408.1127,-255.7074"/>
<polygon fill="#000000" stroke="#000000" points="1406.1693,-258.6482 1416.0613,-262.4427 1410.6947,-253.3076 1406.1693,-258.6482"/>
<text text-anchor="middle" x="1415.8683" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge35" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1141.8602,-185.0571C1222.563,-163.6039 1468.2965,-99.091 1549.8683,-87 1880.3041,-38.0211 2957.3581,-21.627 3195.1338,-18.5622"/>
<polygon fill="#000000" stroke="#000000" points="3195.222,-22.0614 3205.1766,-18.4343 3195.1328,-15.062 3195.222,-22.0614"/>
<text text-anchor="middle" x="1573.8683" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study_personnel -->
<g id="node14" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="3456.8683" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="3456.8683" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge19" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3426.5261,-88.0559C3406.7763,-77.4359 3380.2464,-63.9279 3355.8683,-54 3332.5314,-44.4961 3305.6898,-35.9099 3283.9164,-29.5084"/>
<polygon fill="#000000" stroke="#000000" points="3284.8787,-26.1433 3274.2998,-26.7255 3282.9327,-32.8674 3284.8787,-26.1433"/>
<text text-anchor="middle" x="3456.3683" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- diagnosis -->
<g id="node15" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="3015.8683" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="3015.8683" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2978.3505,-178.8916C2961.9105,-172.6673 2942.5934,-164.6903 2925.8683,-156 2915.0389,-150.3731 2914.4259,-144.9192 2902.8683,-141 2830.7561,-116.5467 2616.0235,-108.6367 2502.3376,-106.1293"/>
<polygon fill="#000000" stroke="#000000" points="2502.399,-102.6299 2492.3269,-105.9168 2502.2503,-109.6284 2502.399,-102.6299"/>
<text text-anchor="middle" x="2970.3683" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge1" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2488.592,-98.7082C2642.8602,-82.1794 3057.2364,-37.782 3195.9272,-22.9223"/>
<polygon fill="#000000" stroke="#000000" points="3196.6258,-26.3675 3206.196,-21.822 3195.88,-19.4074 3196.6258,-26.3675"/>
<text text-anchor="middle" x="2935.3683" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- methylation_array_file -->
<g id="node17" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="415.8683" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="415.8683" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M500.2247,-353.5995C513.4872,-351.6947 527.0471,-349.7733 539.8683,-348 651.3228,-332.5846 678.719,-324.0719 790.8683,-315 920.7278,-304.4955 1248.3716,-318.504 1376.8683,-297 1381.6841,-296.1941 1386.6557,-295.0906 1391.5691,-293.8237"/>
<polygon fill="#000000" stroke="#000000" points="1392.8214,-297.1076 1401.5043,-291.0365 1390.9305,-290.3678 1392.8214,-297.1076"/>
<text text-anchor="middle" x="882.3683" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge32" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M318.8544,-356.1543C204.6158,-343.5644 27.7782,-320.5598 7.8683,-297 -2.4592,-284.7794 -2.7396,-272.978 7.8683,-261 44.1197,-220.0664 886.9674,-197.4798 1077.7271,-192.8821"/>
<polygon fill="#000000" stroke="#000000" points="1077.9237,-196.3785 1087.8372,-192.6406 1077.7565,-189.3805 1077.9237,-196.3785"/>
<text text-anchor="middle" x="99.3683" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge30" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M418.4214,-347.9351C422.9075,-323.6407 434.6798,-281.166 463.8683,-261 483.8971,-247.1623 1215.0073,-206.7939 1430.6081,-195.1674"/>
<polygon fill="#000000" stroke="#000000" points="1430.9835,-198.6523 1440.7808,-194.6195 1430.607,-191.6624 1430.9835,-198.6523"/>
<text text-anchor="middle" x="555.3683" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- publication -->
<g id="node18" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="3624.8683" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="3624.8683" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge33" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3599.8042,-88.2234C3581.2815,-76.672 3555.0164,-62.0146 3529.8683,-54 3485.9721,-40.0105 3357.8388,-27.6381 3288.2083,-21.7106"/>
<polygon fill="#000000" stroke="#000000" points="3288.2249,-18.1997 3277.9667,-20.8493 3287.6382,-25.1751 3288.2249,-18.1997"/>
<text text-anchor="middle" x="3615.8683" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- family_relationship -->
<g id="node20" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1656.8683" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1656.8683" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge42" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1654.8923,-173.9636C1654.7514,-162.7623 1656.7559,-149.0181 1665.8683,-141 1691.551,-118.4015 2171.0839,-108.8565 2357.038,-105.9942"/>
<polygon fill="#000000" stroke="#000000" points="2357.3191,-109.4904 2367.2648,-105.839 2357.2128,-102.4913 2357.3191,-109.4904"/>
<text text-anchor="middle" x="1745.3683" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node21" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="686.8683" cy="-366" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="686.8683" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M792.1156,-354.3587C847.4914,-347.8854 916.4594,-339.2746 977.8683,-330 1015.3669,-324.3366 1024.2032,-319.423 1061.8683,-315 1201.1397,-298.6453 1238.8804,-321.9671 1376.8683,-297 1381.6731,-296.1306 1386.6377,-294.9867 1391.5469,-293.696"/>
<polygon fill="#000000" stroke="#000000" points="1392.8106,-296.9758 1401.4773,-290.8816 1390.9018,-290.2411 1392.8106,-296.9758"/>
<text text-anchor="middle" x="1170.3683" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge18" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M587.6239,-353.4967C447.8427,-335.6554 209.1517,-304.2428 202.8683,-297 192.3833,-284.9143 191.9892,-272.7323 202.8683,-261 233.0912,-228.4068 907.6537,-200.0881 1077.3817,-193.4613"/>
<polygon fill="#000000" stroke="#000000" points="1077.7372,-196.9503 1087.5939,-193.0651 1077.4657,-189.9555 1077.7372,-196.9503"/>
<text text-anchor="middle" x="311.3683" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge16" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M673.6689,-347.8951C658.5072,-324.7273 638.4333,-284.7579 660.8683,-261 684.8614,-235.5921 940.0283,-245.7225 974.8683,-243 1141.2362,-229.9995 1337.2818,-209.018 1432.3698,-198.4794"/>
<polygon fill="#000000" stroke="#000000" points="1432.8033,-201.9529 1442.3556,-197.3699 1432.0302,-194.9957 1432.8033,-201.9529"/>
<text text-anchor="middle" x="769.3683" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- study_arm -->
<g id="node22" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="3765.8683" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="3765.8683" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge40" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3741.6812,-88.4092C3723.168,-76.6302 3696.533,-61.6085 3670.8683,-54 3600.3314,-33.0889 3384.5745,-23.0498 3288.6678,-19.5278"/>
<polygon fill="#000000" stroke="#000000" points="3288.5205,-16.0203 3278.4012,-19.1589 3288.2691,-23.0158 3288.5205,-16.0203"/>
<text text-anchor="middle" x="3754.3683" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1520.9522,-206.0374C1537.658,-215.5972 1552.9481,-229.0151 1542.8683,-243 1541.843,-244.4225 1508.7474,-255.3365 1479.4631,-264.7785"/>
<polygon fill="#000000" stroke="#000000" points="1478.1783,-261.5151 1469.7298,-267.9083 1480.3212,-268.1791 1478.1783,-261.5151"/>
<text text-anchor="middle" x="1587.3683" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1510.2531,-175.3421C1526.2264,-163.3626 1549.5767,-148.1153 1572.8683,-141 1646.761,-118.4268 2164.0815,-108.7935 2357.3013,-105.9551"/>
<polygon fill="#000000" stroke="#000000" points="2357.4091,-109.454 2367.3573,-105.8092 2357.3075,-102.4547 2357.4091,-109.454"/>
<text text-anchor="middle" x="1613.3683" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge10" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1501.2195,-174.3309C1509.7683,-162.6753 1522.608,-148.264 1537.8683,-141 1691.4049,-67.9158 2937.2155,-27.068 3195.2091,-19.3479"/>
<polygon fill="#000000" stroke="#000000" points="3195.4711,-22.8418 3205.3626,-19.046 3195.263,-15.8449 3195.4711,-22.8418"/>
<text text-anchor="middle" x="1906.3683" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- study_funding -->
<g id="node24" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="3920.8683" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="3920.8683" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge3" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3891.4363,-88.3076C3869.0125,-76.4768 3836.9689,-61.4347 3806.8683,-54 3709.032,-29.8351 3405.4109,-21.2845 3288.4553,-18.8385"/>
<polygon fill="#000000" stroke="#000000" points="3288.4559,-15.3379 3278.3867,-18.6335 3288.3133,-22.3365 3288.4559,-15.3379"/>
<text text-anchor="middle" x="3910.8683" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- pathology_file -->
<g id="node25" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1231.8683" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1231.8683" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1253.9776,-348.5303C1268.7868,-337.5617 1289.1199,-323.8638 1308.8683,-315 1337.3902,-302.1983 1346.8214,-305.6351 1376.8683,-297 1381.2033,-295.7542 1385.7093,-294.422 1390.2079,-293.0672"/>
<polygon fill="#000000" stroke="#000000" points="1391.4304,-296.3537 1399.9753,-290.0899 1389.3893,-289.6578 1391.4304,-296.3537"/>
<text text-anchor="middle" x="1369.8683" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge28" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1156.967,-362.7304C1030.6407,-356.8494 787.6307,-343.8073 774.8683,-330 770.3431,-325.1044 770.563,-320.0901 774.8683,-315 806.011,-278.1807 841.3922,-323.2148 881.8683,-297 912.8036,-276.9644 897.1607,-248.3829 927.8683,-228 951.9865,-211.991 1030.346,-201.0988 1077.9509,-195.7733"/>
<polygon fill="#000000" stroke="#000000" points="1078.3368,-199.252 1087.8997,-194.6911 1077.5798,-192.2931 1078.3368,-199.252"/>
<text text-anchor="middle" x="966.8683" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge27" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1230.3827,-347.6743C1229.0688,-317.8808 1231.2609,-259.1435 1264.8683,-228 1288.3403,-206.2488 1372.0086,-197.6119 1430.4133,-194.2008"/>
<polygon fill="#000000" stroke="#000000" points="1430.8479,-197.6823 1440.6417,-193.6411 1430.4654,-190.6928 1430.8479,-197.6823"/>
<text text-anchor="middle" x="1303.8683" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
</g>
</svg>
</div>
