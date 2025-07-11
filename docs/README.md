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
<svg width="3513pt" height="392pt"
 viewBox="0.00 0.00 3512.69 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3508.6886,-388 3508.6886,4 -4,4"/>
<!-- synonym -->
<g id="node1" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2681.6442" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2681.6442" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- study -->
<g id="node8" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2843.6442" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2843.6442" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge10" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2732.9574,-362.7861C2816.5549,-356.3797 2976.3861,-338.8547 3011.6442,-297 3056.3361,-243.9464 3061.7783,-193.6779 3016.6442,-141 2982.6987,-101.3808 2943.2965,-153.0459 2900.6442,-123 2874.5303,-104.6044 2859.2077,-70.3438 2851.1431,-45.9628"/>
<polygon fill="#000000" stroke="#000000" points="2854.4201,-44.7127 2848.1209,-36.1938 2847.7327,-46.7815 2854.4201,-44.7127"/>
<text text-anchor="middle" x="3090.1442" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- sample -->
<g id="node18" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="742.6442" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="742.6442" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2632.897,-359.4807C2602.1777,-355.5945 2561.6532,-350.8735 2525.6442,-348 1858.0494,-294.7261 1688.706,-326.6178 1019.6442,-297 941.9142,-293.5591 852.0532,-287.2989 796.279,-283.1442"/>
<polygon fill="#000000" stroke="#000000" points="796.5057,-279.6514 786.272,-282.3941 795.9823,-286.6319 796.5057,-279.6514"/>
<text text-anchor="middle" x="2282.1442" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- participant -->
<g id="node21" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1851.6442" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1851.6442" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2677.5535,-347.7083C2671.2565,-323.9555 2656.8443,-282.948 2628.6442,-261 2575.4606,-219.6075 2547.394,-237.2893 2480.6442,-228 2375.0852,-213.3098 2065.7528,-200.124 1924.0488,-194.6647"/>
<polygon fill="#000000" stroke="#000000" points="1923.8578,-191.1549 1913.7311,-194.2694 1923.5897,-198.1498 1923.8578,-191.1549"/>
<text text-anchor="middle" x="2699.1442" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- treatment_response -->
<g id="node2" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="2146.6442" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="2146.6442" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2117.2446,-261.5386C2097.3608,-250.4307 2070.1689,-236.5729 2044.6442,-228 2004.4774,-214.5093 1957.8103,-205.6318 1920.4273,-200.0683"/>
<polygon fill="#000000" stroke="#000000" points="1920.5397,-196.5484 1910.1427,-198.5859 1919.541,-203.4768 1920.5397,-196.5484"/>
<text text-anchor="middle" x="2162.6442" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- cytogenomic_file -->
<g id="node3" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="409.6442" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="409.6442" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M416.2304,-347.9027C421.355,-336.5262 429.6357,-322.6082 441.6442,-315 462.0553,-302.0682 608.0804,-289.164 688.9935,-282.9026"/>
<polygon fill="#000000" stroke="#000000" points="689.2996,-286.3895 699.0032,-282.1362 688.7651,-279.41 689.2996,-286.3895"/>
<text text-anchor="middle" x="513.1442" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- methylation_array_file -->
<g id="node4" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="817.6442" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="817.6442" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M756.3333,-350.5162C746.9648,-345.4817 738.4856,-338.8178 732.6442,-330 728.0388,-323.0481 728.0621,-314.4685 729.9722,-306.3427"/>
<polygon fill="#000000" stroke="#000000" points="733.3127,-307.3875 733.0536,-296.7959 726.6511,-305.2374 733.3127,-307.3875"/>
<text text-anchor="middle" x="824.1442" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- family_relationship -->
<g id="node5" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="2369.6442" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="2369.6442" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2337.2425,-261.954C2313.6241,-250.3518 2280.4911,-235.7465 2249.6442,-228 2189.7721,-212.9645 2020.8234,-201.4369 1923.3724,-195.8055"/>
<polygon fill="#000000" stroke="#000000" points="1923.4864,-192.3064 1913.3029,-195.2299 1923.0868,-199.295 1923.4864,-192.3064"/>
<text text-anchor="middle" x="2374.1442" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- diagnosis -->
<g id="node6" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1023.6442" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1023.6442" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M987.4217,-352.3124C972.0863,-346.0968 954.2045,-338.285 938.6442,-330 927.8719,-324.2644 926.9247,-319.6571 915.6442,-315 877.0599,-299.0705 830.6177,-289.9043 795.5713,-284.8119"/>
<polygon fill="#000000" stroke="#000000" points="795.9306,-281.3283 785.5444,-283.4204 794.9683,-288.2619 795.9306,-281.3283"/>
<text text-anchor="middle" x="983.1442" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1027.7911,-347.78C1034.1505,-324.1066 1048.6315,-283.1868 1076.6442,-261 1125.7407,-222.1143 1151.6835,-237.1345 1213.6442,-228 1320.8926,-212.189 1636.2199,-199.5378 1779.4196,-194.4366"/>
<polygon fill="#000000" stroke="#000000" points="1779.5573,-197.934 1789.4272,-194.0824 1779.3097,-190.9384 1779.5573,-197.934"/>
<text text-anchor="middle" x="1121.1442" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- study_personnel -->
<g id="node7" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2689.6442" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2689.6442" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge5" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2684.8737,-86.6052C2683.2634,-75.966 2683.4082,-62.9544 2690.6442,-54 2703.9763,-37.5017 2757.5424,-27.765 2797.558,-22.6621"/>
<polygon fill="#000000" stroke="#000000" points="2798.16,-26.1147 2807.6644,-21.4334 2797.3151,-19.1659 2798.16,-26.1147"/>
<text text-anchor="middle" x="2760.1442" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- consent_group -->
<g id="node9" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="2268.6442" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="2268.6442" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge21" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2328.8736,-93.1988C2386.2531,-82.19 2475.1315,-65.7454 2552.6442,-54 2638.88,-40.9328 2740.0335,-29.2311 2797.5082,-22.9204"/>
<polygon fill="#000000" stroke="#000000" points="2798.1572,-26.3704 2807.7183,-21.8057 2797.3974,-19.4118 2798.1572,-26.3704"/>
<text text-anchor="middle" x="2616.1442" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- cell_line -->
<g id="node10" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="857.6442" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="857.6442" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge13" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M905.7525,-187.7851C1178.7431,-163.8675 2530.2915,-45.4539 2797.6475,-22.0299"/>
<polygon fill="#000000" stroke="#000000" points="2798.1209,-25.5019 2807.7772,-21.1424 2797.5099,-18.5287 2798.1209,-25.5019"/>
<text text-anchor="middle" x="2089.1442" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M816.3719,-202.0793C791.5825,-208.9342 763.2295,-218.4609 754.6442,-228 748.9966,-234.275 745.8668,-242.7035 744.1714,-250.8993"/>
<polygon fill="#000000" stroke="#000000" points="740.6815,-250.5775 742.7096,-260.9764 747.609,-251.5825 740.6815,-250.5775"/>
<text text-anchor="middle" x="795.1442" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- generic_file -->
<g id="node11" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="65.6442" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="65.6442" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge3" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M62.6473,-347.7262C60.0292,-330.1607 56.6442,-302.8401 56.6442,-279 56.6442,-279 56.6442,-279 56.6442,-105 56.6442,-33.4889 2432.3485,-19.8647 2796.9343,-18.195"/>
<polygon fill="#000000" stroke="#000000" points="2797.1458,-21.6942 2807.1299,-18.149 2797.1142,-14.6942 2797.1458,-21.6942"/>
<text text-anchor="middle" x="109.6442" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M90.3437,-349.2501C109.2483,-337.3899 136.4446,-322.3362 162.6442,-315 260.4464,-287.6141 563.1718,-281.0373 687.9866,-279.4773"/>
<polygon fill="#000000" stroke="#000000" points="688.1252,-282.976 698.0829,-279.3573 688.0419,-275.9765 688.1252,-282.976"/>
<text text-anchor="middle" x="215.6442" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M80.7884,-348.1306C91.3575,-336.8503 106.4311,-322.9539 122.6442,-315 314.1516,-221.0492 382.5176,-250.4529 594.6442,-228 712.0853,-215.5693 1528.9917,-198.4337 1779.0635,-193.427"/>
<polygon fill="#000000" stroke="#000000" points="1779.2043,-196.925 1789.1324,-193.2258 1779.0644,-189.9264 1779.2043,-196.925"/>
<text text-anchor="middle" x="312.6442" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node12" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="2893.6442" cy="-279" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="2893.6442" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge34" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2883.9393,-260.9027C2871.9718,-237.478 2852.2783,-195.0266 2844.6442,-156 2837.3352,-118.6359 2838.7147,-74.4859 2840.8125,-46.3708"/>
<polygon fill="#000000" stroke="#000000" points="2844.3277,-46.3309 2841.6672,-36.0756 2837.3517,-45.7517 2844.3277,-46.3309"/>
<text text-anchor="middle" x="2930.6442" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2813.2631,-266.8937C2758.9522,-258.4372 2694.9704,-247.8298 2682.6442,-243 2671.2813,-238.5477 2671.262,-231.737 2659.6442,-228 2590.8097,-205.8583 2109.645,-196.0411 1924.2458,-193.0501"/>
<polygon fill="#000000" stroke="#000000" points="1924.1071,-189.5476 1914.0526,-192.8878 1923.9955,-196.5467 1924.1071,-189.5476"/>
<text text-anchor="middle" x="2768.6442" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- genetic_analysis -->
<g id="node13" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="2428.6442" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="2428.6442" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge35" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2342.4422,-362.2582C2122.151,-352.5918 1520.5936,-325.5405 1019.6442,-297 941.9641,-292.5743 852.09,-286.5716 796.2994,-282.7412"/>
<polygon fill="#000000" stroke="#000000" points="796.5061,-279.2473 786.2893,-282.0522 796.0253,-286.2307 796.5061,-279.2473"/>
<text text-anchor="middle" x="1708.6442" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge36" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2446.4552,-348.1937C2458.1063,-335.222 2472.302,-316.5607 2478.6442,-297 2488.5308,-266.5072 2485.2743,-244.2522 2457.6442,-228 2412.7153,-201.5726 2075.3375,-194.4915 1924.3335,-192.638"/>
<polygon fill="#000000" stroke="#000000" points="1924.2664,-189.1371 1914.2257,-192.5184 1924.1835,-196.1366 1924.2664,-189.1371"/>
<text text-anchor="middle" x="2554.6442" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- medical_history -->
<g id="node14" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1400.6442" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1400.6442" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1417.6227,-261.1519C1429.804,-249.574 1447.2556,-235.3263 1465.6442,-228 1520.8432,-206.0077 1683.5208,-197.2268 1779.16,-193.895"/>
<polygon fill="#000000" stroke="#000000" points="1779.4625,-197.3869 1789.339,-193.5521 1779.2268,-190.3908 1779.4625,-197.3869"/>
<text text-anchor="middle" x="1533.6442" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- pathology_file -->
<g id="node15" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="225.6442" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="225.6442" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M245.0813,-348.5938C259.3744,-336.9004 279.8559,-322.3354 300.6442,-315 370.6609,-290.2937 586.0722,-282.3807 688.0466,-279.9806"/>
<polygon fill="#000000" stroke="#000000" points="688.2229,-283.4776 698.1412,-279.7523 688.0646,-276.4794 688.2229,-283.4776"/>
<text text-anchor="middle" x="361.6442" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- radiology_file -->
<g id="node16" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1577.6442" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1577.6442" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1589.4286,-260.9841C1597.8467,-249.642 1610.2091,-235.7317 1624.6442,-228 1651.1899,-213.7816 1725.3444,-203.8149 1781.7394,-198.0291"/>
<polygon fill="#000000" stroke="#000000" points="1782.09,-201.5115 1791.6913,-197.0321 1781.3922,-194.5464 1782.09,-201.5115"/>
<text text-anchor="middle" x="1683.6442" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- exposure -->
<g id="node17" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1722.6442" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1722.6442" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1732.6092,-260.9326C1739.3314,-250.1445 1749.0728,-236.8621 1760.6442,-228 1771.2854,-219.8503 1784.01,-213.3047 1796.5235,-208.1486"/>
<polygon fill="#000000" stroke="#000000" points="1797.9526,-211.3485 1806.0134,-204.4729 1795.4243,-204.821 1797.9526,-211.3485"/>
<text text-anchor="middle" x="1804.1442" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge39" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M782.6833,-270.9738C800.725,-265.6268 821.1763,-256.9293 835.6442,-243 842.2347,-236.6547 846.962,-228.0079 850.3018,-219.6369"/>
<polygon fill="#000000" stroke="#000000" points="853.6424,-220.6861 853.6136,-210.0913 847.0291,-218.3916 853.6424,-220.6861"/>
<text text-anchor="middle" x="883.1442" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node20" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="682.6442" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="682.6442" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge37" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M700.0294,-273.7883C663.3712,-268.3255 614.5622,-258.3704 602.6442,-243 587.3179,-223.2341 618.3219,-208.9729 646.0852,-200.6406"/>
<polygon fill="#000000" stroke="#000000" points="647.3915,-203.9094 656.0754,-197.8398 645.5018,-197.1693 647.3915,-203.9094"/>
<text text-anchor="middle" x="639.1442" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge38" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M785.1281,-273.668C822.3187,-268.2696 877.4708,-258.4808 923.6442,-243 938.1562,-238.1345 939.7968,-231.7183 954.6442,-228 1033.4961,-208.2528 1579.541,-196.7827 1778.9508,-193.2136"/>
<polygon fill="#000000" stroke="#000000" points="1779.0973,-196.7117 1789.0335,-193.0346 1778.9729,-189.7128 1779.0973,-196.7117"/>
<text text-anchor="middle" x="991.1442" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- laboratory_test -->
<g id="node19" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1199.6442" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1199.6442" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge32" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1148.8076,-351.8117C1126.3153,-345.3873 1099.5879,-337.5526 1075.6442,-330 1055.9405,-323.7848 1051.7784,-319.6345 1031.6442,-315 950.9978,-296.4367 855.3405,-286.8946 796.832,-282.4264"/>
<polygon fill="#000000" stroke="#000000" points="796.9377,-278.9248 786.7063,-281.6756 796.4201,-285.9056 796.9377,-278.9248"/>
<text text-anchor="middle" x="1141.1442" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1207.4249,-347.9355C1210.6017,-337.664 1212.3517,-324.914 1206.6442,-315 1198.6952,-301.1927 1183.5931,-310.8073 1175.6442,-297 1167.6613,-283.1337 1165.0638,-273.0023 1175.6442,-261 1215.0197,-216.3324 1612.7524,-199.2029 1779.1047,-193.9577"/>
<polygon fill="#000000" stroke="#000000" points="1779.357,-197.4517 1789.2438,-193.6437 1779.1402,-190.455 1779.357,-197.4517"/>
<text text-anchor="middle" x="1241.1442" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge15" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M710.0174,-187.4354C733.6975,-183.5714 768.8747,-178.0338 799.6442,-174 1155.138,-127.3961 1244.3068,-116.2874 1601.6442,-87 2067.359,-48.8299 2633.0824,-25.891 2797.0586,-19.7042"/>
<polygon fill="#000000" stroke="#000000" points="2797.4114,-23.1935 2807.2731,-19.3209 2797.1488,-16.1984 2797.4114,-23.1935"/>
<text text-anchor="middle" x="1625.6442" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M678.9105,-210.1275C677.7493,-220.42 677.9993,-233.17 683.6442,-243 687.8961,-250.4043 694.3425,-256.4737 701.4351,-261.3784"/>
<polygon fill="#000000" stroke="#000000" points="699.6111,-264.3655 709.9652,-266.6112 703.2714,-258.3987 699.6111,-264.3655"/>
<text text-anchor="middle" x="707.6442" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge24" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1902.3597,-181.4191C1977.0293,-165.8405 2116.7188,-136.6967 2200.3436,-119.2498"/>
<polygon fill="#000000" stroke="#000000" points="2201.1813,-122.6504 2210.2557,-117.1818 2199.7516,-115.798 2201.1813,-122.6504"/>
<text text-anchor="middle" x="2136.1442" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sequencing_file -->
<g id="node22" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="600.6442" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="600.6442" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M591.4955,-347.747C587.6064,-337.1582 585.4307,-324.1496 592.6442,-315 604.7066,-299.7001 651.5112,-290.1628 689.6699,-284.78"/>
<polygon fill="#000000" stroke="#000000" points="690.2178,-288.2379 699.6616,-283.4353 689.2841,-281.3004 690.2178,-288.2379"/>
<text text-anchor="middle" x="659.1442" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- study_arm -->
<g id="node23" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2969.6442" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2969.6442" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge26" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2945.648,-88.4312C2925.0987,-74.2424 2895.422,-53.7513 2873.3716,-38.5261"/>
<polygon fill="#000000" stroke="#000000" points="2875.2505,-35.5702 2865.0328,-32.7684 2871.2732,-41.3305 2875.2505,-35.5702"/>
<text text-anchor="middle" x="2962.1442" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- study_admin -->
<g id="node24" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="3117.6442" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="3117.6442" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge30" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3089.1885,-88.4706C3068.9647,-77.3378 3040.8508,-63.0828 3014.6442,-54 2973.161,-39.6227 2923.9341,-29.9962 2888.9746,-24.3436"/>
<polygon fill="#000000" stroke="#000000" points="2889.4822,-20.8805 2879.06,-22.7851 2888.3952,-27.7956 2889.4822,-20.8805"/>
<text text-anchor="middle" x="3106.1442" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- study_funding -->
<g id="node25" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="3283.6442" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="3283.6442" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge28" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3252.2994,-88.2528C3229.2566,-76.7156 3196.8291,-62.0632 3166.6442,-54 3115.622,-40.3707 2966.5099,-27.4245 2890.0423,-21.4501"/>
<polygon fill="#000000" stroke="#000000" points="2889.9925,-17.9358 2879.7523,-20.654 2889.4525,-24.915 2889.9925,-17.9358"/>
<text text-anchor="middle" x="3271.6442" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- treatment -->
<g id="node26" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="1851.6442" cy="-279" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="1851.6442" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1851.6442,-260.9735C1851.6442,-249.1918 1851.6442,-233.5607 1851.6442,-220.1581"/>
<polygon fill="#000000" stroke="#000000" points="1855.1443,-220.0033 1851.6442,-210.0034 1848.1443,-220.0034 1855.1443,-220.0033"/>
<text text-anchor="middle" x="1898.6442" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- survival -->
<g id="node27" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1975.6442" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1975.6442" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1970.1605,-260.8229C1966.0634,-249.9935 1959.4575,-236.7062 1949.6442,-228 1938.8974,-218.4656 1925.4108,-211.3841 1911.9113,-206.1507"/>
<polygon fill="#000000" stroke="#000000" points="1912.7129,-202.7207 1902.1183,-202.6579 1910.3613,-209.3139 1912.7129,-202.7207"/>
<text text-anchor="middle" x="2001.1442" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- publication -->
<g id="node28" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="3441.6442" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="3441.6442" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge18" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3415.394,-88.6008C3395.0085,-76.7568 3365.5963,-61.5658 3337.6442,-54 3254.1014,-31.3875 2996.5041,-22.0776 2890.2298,-19.1314"/>
<polygon fill="#000000" stroke="#000000" points="2890.2196,-15.6299 2880.1285,-18.8579 2890.0301,-22.6273 2890.2196,-15.6299"/>
<text text-anchor="middle" x="3426.6442" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
</g>
</svg>
</div>
