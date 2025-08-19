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
<svg width="3600pt" height="392pt"
 viewBox="0.00 0.00 3600.19 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3596.1926,-388 3596.1926,4 -4,4"/>
<!-- methylation_array_file -->
<g id="node1" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="470.1926" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="470.1926" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- sample -->
<g id="node22" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="996.1926" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="996.1926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M475.2603,-347.7773C479.4508,-336.3479 486.6305,-322.418 498.1926,-315 534.791,-291.5191 819.9577,-282.7306 941.5551,-280.0279"/>
<polygon fill="#000000" stroke="#000000" points="941.8384,-283.5227 951.7602,-279.8069 941.6867,-276.5244 941.8384,-283.5227"/>
<text text-anchor="middle" x="589.6926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- sequencing_file -->
<g id="node2" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="83.1926" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="83.1926" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M109.3869,-348.868C129.0837,-336.981 157.2077,-322.0618 184.1926,-315 256.9414,-295.9622 771.523,-283.6687 941.702,-280.0875"/>
<polygon fill="#000000" stroke="#000000" points="942.0063,-283.582 951.9311,-279.8741 941.8602,-276.5836 942.0063,-283.582"/>
<text text-anchor="middle" x="250.6926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- pdx -->
<g id="node3" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1186.1926" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1186.1926" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1182.7704,-210.1226C1179.7398,-221.2128 1174.1802,-234.8018 1164.1926,-243 1146.7964,-257.2794 1091.5348,-267.2332 1049.0928,-272.9994"/>
<polygon fill="#000000" stroke="#000000" points="1048.6169,-269.5318 1039.1585,-274.3055 1049.5295,-276.472 1048.6169,-269.5318"/>
<text text-anchor="middle" x="1199.1926" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study -->
<g id="node25" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2851.1926" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2851.1926" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge30" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1214.3556,-191.4687C1395.5273,-187.9288 2393.4446,-166.556 2521.1926,-123 2547.7978,-113.9289 2547.5773,-98.575 2573.1926,-87 2650.8359,-51.9147 2749.0753,-32.8856 2805.5624,-24.1365"/>
<polygon fill="#000000" stroke="#000000" points="2806.2435,-27.5734 2815.6095,-22.6209 2805.1993,-20.6517 2806.2435,-27.5734"/>
<text text-anchor="middle" x="2597.1926" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- diagnosis -->
<g id="node4" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1727.1926" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1727.1926" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- participant -->
<g id="node18" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="2265.1926" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="2265.1926" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1773.4205,-356.1579C1815.2975,-345.8355 1877.5522,-326.8921 1925.1926,-297 1944.3595,-284.9737 1941.382,-271.9334 1961.1926,-261 2034.28,-220.6636 2129.6579,-203.885 2193.9309,-196.9196"/>
<polygon fill="#000000" stroke="#000000" points="2194.3831,-200.3916 2203.9711,-195.8838 2193.6647,-193.4285 2194.3831,-200.3916"/>
<text text-anchor="middle" x="2005.6926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1673.5043,-362.6355C1532.384,-353.7863 1161.7083,-330.5034 1160.1926,-330 1148.6106,-326.1534 1148.3659,-319.9087 1137.1926,-315 1108.5806,-302.4301 1074.6988,-293.6024 1047.3201,-287.8353"/>
<polygon fill="#000000" stroke="#000000" points="1047.6665,-284.3343 1037.1699,-285.7735 1046.273,-291.1942 1047.6665,-284.3343"/>
<text text-anchor="middle" x="1204.6926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- study_personnel -->
<g id="node5" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2287.1926" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2287.1926" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge2" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2287.9362,-86.7785C2289.4329,-75.5013 2293.3437,-61.742 2303.1926,-54 2322.7638,-38.6154 2675.2235,-24.3696 2804.3154,-19.6464"/>
<polygon fill="#000000" stroke="#000000" points="2804.7943,-23.1314 2814.6607,-19.2709 2804.5403,-16.1361 2804.7943,-23.1314"/>
<text text-anchor="middle" x="2372.6926" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- medical_history -->
<g id="node6" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2144.1926" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2144.1926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2123.6388,-261.1787C2114.3708,-250.9882 2107.1208,-238.2382 2115.1926,-228 2125.6432,-214.7445 2162.1719,-205.8144 2196.5625,-200.1641"/>
<polygon fill="#000000" stroke="#000000" points="2197.318,-203.5886 2206.6572,-198.5857 2196.2365,-196.6726 2197.318,-203.5886"/>
<text text-anchor="middle" x="2183.1926" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- laboratory_test -->
<g id="node7" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1019.1926" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1019.1926" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1095.5238,-359.4496C1139.3073,-355.8103 1195.3176,-351.3542 1245.1926,-348 1263.4011,-346.7754 1560.6467,-343.2533 1573.1926,-330 1577.7757,-325.1585 1577.4643,-320.1183 1573.1926,-315 1544.5375,-280.6651 1502.8477,-331.3349 1474.1926,-297 1463.9407,-284.716 1463.8607,-273.2169 1474.1926,-261 1520.1082,-206.7075 2005.8366,-195.1097 2192.598,-192.653"/>
<polygon fill="#000000" stroke="#000000" points="2192.6435,-196.1529 2202.5984,-192.5265 2192.5549,-189.1534 2192.6435,-196.1529"/>
<text text-anchor="middle" x="1539.6926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M942.0929,-359.7768C900.8492,-354.6739 855.9615,-345.6451 843.1926,-330 838.9773,-324.8352 839.0535,-320.2261 843.1926,-315 855.5957,-299.3398 903.8594,-289.8169 942.9065,-284.5336"/>
<polygon fill="#000000" stroke="#000000" points="943.6508,-287.9667 953.1215,-283.2174 942.7562,-281.0241 943.6508,-287.9667"/>
<text text-anchor="middle" x="908.6926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- study_arm -->
<g id="node8" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2452.1926" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2452.1926" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge3" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2447.0601,-86.7147C2445.2068,-75.8445 2445.2236,-62.5525 2453.1926,-54 2476.7464,-28.7217 2704.626,-20.9855 2804.5873,-18.797"/>
<polygon fill="#000000" stroke="#000000" points="2804.7802,-22.2938 2814.7047,-18.585 2804.6335,-15.2954 2804.7802,-22.2938"/>
<text text-anchor="middle" x="2501.6926" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- pathology_file -->
<g id="node9" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="260.1926" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="260.1926" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge33" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M285.5618,-348.959C304.6501,-337.1172 331.9301,-322.2148 358.1926,-315 413.6365,-299.7686 797.6802,-285.5977 941.7553,-280.7584"/>
<polygon fill="#000000" stroke="#000000" points="942.2343,-284.2444 952.112,-280.4127 942.0007,-277.2483 942.2343,-284.2444"/>
<text text-anchor="middle" x="419.1926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- genetic_analysis -->
<g id="node10" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="1342.1926" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="1342.1926" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1423.0415,-358.9066C1492.9167,-352.0838 1584.7633,-341.1829 1598.1926,-330 1623.0332,-309.3147 1596.5834,-281.9601 1621.1926,-261 1664.0697,-224.4808 2034.2813,-202.8608 2193.2074,-195.187"/>
<polygon fill="#000000" stroke="#000000" points="2193.5428,-198.675 2203.3643,-194.7017 2193.2086,-191.683 2193.5428,-198.675"/>
<text text-anchor="middle" x="1691.1926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1259.2601,-360.0925C1160.0152,-352.6204 1005.9919,-339.5748 997.1926,-330 991.6309,-323.9481 989.9706,-315.5809 990.1137,-307.3727"/>
<polygon fill="#000000" stroke="#000000" points="993.614,-307.5395 991.1017,-297.2469 986.6471,-306.8597 993.614,-307.5395"/>
<text text-anchor="middle" x="1067.1926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- family_relationship -->
<g id="node11" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="2555.1926" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="2555.1926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2503.6806,-263.5464C2451.539,-247.9039 2371.2811,-223.8266 2318.5039,-207.9934"/>
<polygon fill="#000000" stroke="#000000" points="2319.2409,-204.5605 2308.6569,-205.0393 2317.2295,-211.2652 2319.2409,-204.5605"/>
<text text-anchor="middle" x="2506.6926" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- clinical_measure_file -->
<g id="node12" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="2265.1926" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="2265.1926" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2265.1926,-347.7078C2265.1926,-317.3436 2265.1926,-256.3226 2265.1926,-220.3464"/>
<polygon fill="#000000" stroke="#000000" points="2268.6927,-220.0471 2265.1926,-210.0471 2261.6927,-220.0471 2268.6927,-220.0471"/>
<text text-anchor="middle" x="2351.1926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2159.3016,-361.8791C2063.2427,-358.1646 1917.7238,-352.5967 1791.1926,-348 1733.5293,-345.9052 1327.2086,-347.398 1272.1926,-330 1260.5566,-326.3203 1260.6159,-319.2949 1249.1926,-315 1213.6901,-301.652 1112.752,-290.0751 1049.6238,-283.8578"/>
<polygon fill="#000000" stroke="#000000" points="1049.7416,-280.3529 1039.4501,-282.8699 1049.065,-287.3201 1049.7416,-280.3529"/>
<text text-anchor="middle" x="1358.1926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge16" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2369.2682,-360.865C2627.045,-347.9034 3275.5705,-313.7081 3291.1926,-297 3366.2747,-216.699 3155.4014,-211.2393 3154.1926,-210 3104.9509,-159.5175 3176.3663,-102.5231 3125.1926,-54 3108.9949,-38.6413 2971.5522,-26.5883 2897.7008,-21.1512"/>
<polygon fill="#000000" stroke="#000000" points="2897.5148,-17.6286 2887.2881,-20.3974 2897.0093,-24.6104 2897.5148,-17.6286"/>
<text text-anchor="middle" x="3240.1926" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- publication -->
<g id="node13" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="2693.1926" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="2693.1926" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge40" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2707.533,-87.3412C2717.19,-76.436 2730.7608,-62.8789 2745.1926,-54 2764.3096,-42.2386 2787.7509,-33.7624 2807.7242,-28.001"/>
<polygon fill="#000000" stroke="#000000" points="2808.7982,-31.3356 2817.5131,-25.3105 2806.943,-24.5859 2808.7982,-31.3356"/>
<text text-anchor="middle" x="2796.1926" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- exposure -->
<g id="node14" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="2868.1926" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="2868.1926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2832.8465,-265.4377C2800.2188,-253.5233 2750.1585,-236.7614 2705.1926,-228 2636.6868,-214.6519 2442.9589,-202.0756 2336.8539,-195.9288"/>
<polygon fill="#000000" stroke="#000000" points="2337.0509,-192.4344 2326.8664,-195.3542 2336.6488,-199.4229 2337.0509,-192.4344"/>
<text text-anchor="middle" x="2807.6926" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- study_funding -->
<g id="node15" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2851.1926" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2851.1926" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge5" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2851.1926,-86.9735C2851.1926,-75.1918 2851.1926,-59.5607 2851.1926,-46.1581"/>
<polygon fill="#000000" stroke="#000000" points="2854.6927,-46.0033 2851.1926,-36.0034 2847.6927,-46.0034 2854.6927,-46.0033"/>
<text text-anchor="middle" x="2913.1926" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- cell_line -->
<g id="node16" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="994.1926" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="994.1926" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge38" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M951.1353,-201.0791C923.6416,-209.0247 895.5167,-222.5404 909.1926,-243 917.5328,-255.4771 931.081,-263.635 945.0289,-268.967"/>
<polygon fill="#000000" stroke="#000000" points="944.0957,-272.3459 954.6898,-272.2253 946.3327,-265.713 944.0957,-272.3459"/>
<text text-anchor="middle" x="949.6926" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge37" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1041.1248,-186.2455C1209.5818,-165.7501 1799.6773,-95.3349 2288.1926,-54 2479.6202,-37.8027 2708.2199,-25.2919 2804.6495,-20.3272"/>
<polygon fill="#000000" stroke="#000000" points="2805.1202,-23.8078 2814.9281,-19.8009 2804.7621,-16.817 2805.1202,-23.8078"/>
<text text-anchor="middle" x="1972.6926" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- treatment_response -->
<g id="node17" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="3044.1926" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="3044.1926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2995.4454,-262.9182C2957.6269,-251.1596 2903.6575,-235.9333 2855.1926,-228 2757.6012,-212.0251 2472.5527,-199.6995 2337.6133,-194.5827"/>
<polygon fill="#000000" stroke="#000000" points="2337.5031,-191.0761 2327.3785,-194.1975 2337.2398,-198.0712 2337.5031,-191.0761"/>
<text text-anchor="middle" x="3006.1926" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- consent_group -->
<g id="node23" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="3026.1926" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="3026.1926" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge4" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M2326.1379,-187.738C2444.4094,-179.0264 2713.1257,-157.0793 2937.1926,-123 2944.2643,-121.9244 2951.6252,-120.6647 2958.9506,-119.3198"/>
<polygon fill="#000000" stroke="#000000" points="2959.7109,-122.7381 2968.8872,-117.4424 2958.4112,-115.8598 2959.7109,-122.7381"/>
<text text-anchor="middle" x="2840.6926" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- generic_file -->
<g id="node19" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="2691.1926" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="2691.1926" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2691.1455,-347.8889C2690.1497,-325.0804 2685.2073,-285.8735 2664.1926,-261 2640.9523,-233.4922 2624.9475,-237.4281 2590.1926,-228 2543.8249,-215.4217 2416.6971,-203.7388 2335.872,-197.2659"/>
<polygon fill="#000000" stroke="#000000" points="2336.0108,-193.766 2325.7654,-196.4643 2335.4573,-200.7441 2336.0108,-193.766"/>
<text text-anchor="middle" x="2735.1926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge29" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2626.9046,-362.0273C2564.6044,-358.2283 2467.4383,-352.4379 2383.1926,-348 1900.2197,-322.5579 1779.1456,-322.8171 1296.1926,-297 1209.9994,-292.3924 1109.9279,-286.2232 1049.9078,-282.4347"/>
<polygon fill="#000000" stroke="#000000" points="1050.1047,-278.9402 1039.9037,-281.8018 1049.6627,-285.9263 1050.1047,-278.9402"/>
<text text-anchor="middle" x="2059.1926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge27" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2756.6325,-364.0737C2913.7318,-359.2081 3300.9585,-345.6875 3324.1926,-330 3344.9543,-315.9819 3348.1926,-304.0511 3348.1926,-279 3348.1926,-279 3348.1926,-279 3348.1926,-105 3348.1926,-74.4754 3329.5676,-67.5042 3302.1926,-54 3266.5724,-36.4284 3005.7013,-24.1502 2897.755,-19.77"/>
<polygon fill="#000000" stroke="#000000" points="2897.6262,-16.2621 2887.494,-19.3588 2897.3458,-23.2565 2897.6262,-16.2621"/>
<text text-anchor="middle" x="3401.1926" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- cytogenomic_file -->
<g id="node20" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="693.1926" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="693.1926" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M687.2508,-347.8455C684.9365,-337.0247 684.4279,-323.7384 692.1926,-315 708.4801,-296.67 859.2754,-286.059 942.1782,-281.5638"/>
<polygon fill="#000000" stroke="#000000" points="942.3821,-285.0581 952.1826,-281.0332 942.0112,-278.0679 942.3821,-285.0581"/>
<text text-anchor="middle" x="763.6926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- study_admin -->
<g id="node21" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="3238.1926" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="3238.1926" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge39" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3215.9908,-87.8701C3199.7788,-76.3069 3176.7737,-61.784 3154.1926,-54 3107.8901,-38.039 2970.3993,-26.3536 2897.6052,-21.0943"/>
<polygon fill="#000000" stroke="#000000" points="2897.5761,-17.5835 2887.353,-20.3652 2897.0795,-24.5659 2897.5761,-17.5835"/>
<text text-anchor="middle" x="3241.6926" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge34" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1026.3666,-265.6097C1039.5481,-259.3332 1054.9808,-251.3934 1068.1926,-243 1077.2738,-237.2307 1077.7952,-233.2384 1087.1926,-228 1107.0533,-216.9291 1130.9734,-208.1204 1150.3256,-201.9879"/>
<polygon fill="#000000" stroke="#000000" points="1151.4485,-205.3045 1159.9834,-199.0271 1149.3967,-198.6119 1151.4485,-205.3045"/>
<text text-anchor="middle" x="1123.6926" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge35" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M995.655,-260.6866C995.4963,-255.0174 995.3289,-248.7506 995.1926,-243 995.0207,-235.743 994.8563,-227.9046 994.7123,-220.6012"/>
<polygon fill="#000000" stroke="#000000" points="998.2082,-220.3447 994.5174,-210.4136 991.2094,-220.4787 998.2082,-220.3447"/>
<text text-anchor="middle" x="1031.6926" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge36" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1039.2312,-274.6522C1085.9768,-269.3847 1162.6176,-259.1534 1227.1926,-243 1246.8281,-238.0882 1250.3008,-231.7411 1270.1926,-228 1359.8739,-211.1333 1978.6127,-197.5975 2192.5817,-193.3738"/>
<polygon fill="#000000" stroke="#000000" points="2192.8352,-196.8695 2202.7645,-193.1738 2192.6977,-189.8709 2192.8352,-196.8695"/>
<text text-anchor="middle" x="1306.6926" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge15" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3012.6714,-87.0912C3003.4925,-76.0863 2990.4621,-62.512 2976.1926,-54 2951.7312,-39.4083 2921.0323,-30.4564 2896.1792,-25.1288"/>
<polygon fill="#000000" stroke="#000000" points="2896.7661,-21.6768 2886.2711,-23.1279 2895.3804,-28.5382 2896.7661,-21.6768"/>
<text text-anchor="middle" x="3057.6926" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- treatment -->
<g id="node24" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="3224.1926" cy="-279" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="3224.1926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3193.3174,-263.6427C3167.3176,-251.535 3128.7783,-235.4865 3093.1926,-228 3020.4766,-212.7021 2525.9725,-198.6519 2337.736,-193.7969"/>
<polygon fill="#000000" stroke="#000000" points="2337.7481,-190.2961 2327.6616,-193.5383 2337.5684,-197.2938 2337.7481,-190.2961"/>
<text text-anchor="middle" x="3188.1926" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- survival -->
<g id="node26" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1353.1926" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1353.1926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1347.9974,-261.0654C1346.0008,-250.0503 1345.8853,-236.4742 1354.1926,-228 1368.8165,-213.0823 1979.1686,-198.2802 2192.5021,-193.5531"/>
<polygon fill="#000000" stroke="#000000" points="2192.7394,-197.0488 2202.6597,-193.329 2192.5849,-190.0505 2192.7394,-197.0488"/>
<text text-anchor="middle" x="1393.6926" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- radiology_file -->
<g id="node27" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1843.1926" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1843.1926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1832.2515,-260.8872C1827.2737,-250.082 1824.0961,-236.7976 1832.1926,-228 1856.0245,-202.1045 2075.209,-194.8328 2192.2673,-192.7933"/>
<polygon fill="#000000" stroke="#000000" points="2192.6382,-196.2877 2202.5789,-192.6226 2192.5223,-189.2887 2192.6382,-196.2877"/>
<text text-anchor="middle" x="1891.1926" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- synonym -->
<g id="node28" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="3394.1926" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="3394.1926" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3384.9623,-347.9071C3379.2189,-337.6262 3371.2189,-324.8762 3362.1926,-315 3317.0198,-265.5736 3303.1373,-247.8655 3239.1926,-228 3154.0831,-201.5593 2549.4196,-194.2565 2337.9741,-192.4994"/>
<polygon fill="#000000" stroke="#000000" points="2337.934,-188.999 2327.9058,-192.4174 2337.877,-195.9988 2337.934,-188.999"/>
<text text-anchor="middle" x="3387.6926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge24" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3342.466,-363.6024C3169.1197,-355.6389 2592.8205,-329.7403 2116.1926,-315 1751.8346,-303.7318 1660.4194,-311.919 1296.1926,-297 1209.9487,-293.4674 1109.892,-286.9838 1049.8888,-282.8383"/>
<polygon fill="#000000" stroke="#000000" points="1050.1062,-279.3451 1039.8876,-282.1434 1049.6208,-286.3283 1050.1062,-279.3451"/>
<text text-anchor="middle" x="2579.6926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge22" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3433.0808,-353.9799C3465.7677,-341.1749 3507.1926,-317.3763 3507.1926,-279 3507.1926,-279 3507.1926,-279 3507.1926,-105 3507.1926,-43.504 3048.3083,-24.017 2898.136,-19.2862"/>
<polygon fill="#000000" stroke="#000000" points="2897.9705,-15.7796 2887.8677,-18.9708 2897.7554,-22.7763 2897.9705,-15.7796"/>
<text text-anchor="middle" x="3549.6926" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
</g>
</svg>
</div>
