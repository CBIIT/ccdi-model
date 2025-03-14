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
<svg width="3258pt" height="305pt"
 viewBox="0.00 0.00 3258.04 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 3254.0444,-301 3254.0444,4 -4,4"/>
<!-- study -->
<g id="node1" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1517.0444" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1517.0444" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- family_relationship -->
<g id="node2" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="2032.0444" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="2032.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- participant -->
<g id="node13" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1517.0444" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1517.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1977.6011,-176.8622C1935.432,-165.6045 1875.4027,-150.592 1822.0444,-141 1742.135,-126.6349 1649.3775,-116.622 1587.3288,-110.8662"/>
<polygon fill="#000000" stroke="#000000" points="1587.5365,-107.3707 1577.2591,-109.9445 1586.8984,-114.3415 1587.5365,-107.3707"/>
<text text-anchor="middle" x="1971.5444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- sequencing_file -->
<g id="node3" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2546.0444" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="2546.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sample -->
<g id="node17" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2683.0444" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2683.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge28" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2562.9859,-260.89C2573.5136,-250.3519 2587.7309,-237.3464 2602.0444,-228 2613.8524,-220.2897 2627.5862,-213.4863 2640.3539,-207.9286"/>
<polygon fill="#000000" stroke="#000000" points="2642.0167,-211.0265 2649.8812,-203.9271 2639.306,-204.5726 2642.0167,-211.0265"/>
<text text-anchor="middle" x="2668.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- methylation_array_file -->
<g id="node4" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2763.0444" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2763.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2757.2363,-260.5647C2753.3003,-250.1696 2747.3003,-237.4196 2739.0444,-228 2733.6344,-221.8274 2726.9165,-216.3091 2720.0327,-211.557"/>
<polygon fill="#000000" stroke="#000000" points="2721.6162,-208.4144 2711.3105,-205.9561 2717.8338,-214.3045 2721.6162,-208.4144"/>
<text text-anchor="middle" x="2839.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- radiology_file -->
<g id="node5" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="2224.0444" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="2224.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2179.9661,-177.4608C2138.403,-163.9783 2079.0155,-145.3608 2055.0444,-141 1967.8142,-125.1313 1715.1128,-113.036 1589.5775,-107.8182"/>
<polygon fill="#000000" stroke="#000000" points="1589.4339,-104.3094 1579.2982,-107.3945 1589.1456,-111.3034 1589.4339,-104.3094"/>
<text text-anchor="middle" x="2167.0444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- survival -->
<g id="node6" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="2364.0444" cy="-192" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="2364.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2326.7549,-180.4507C2300.8968,-172.2748 2268.8881,-161.7744 2256.0444,-156 2243.8768,-150.5296 2242.84,-144.7747 2230.0444,-141 2169.8296,-123.2366 1758.3115,-111.0408 1589.2854,-106.7264"/>
<polygon fill="#000000" stroke="#000000" points="1589.3207,-103.2263 1579.2353,-106.4719 1589.1434,-110.2241 1589.3207,-103.2263"/>
<text text-anchor="middle" x="2295.5444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- publication -->
<g id="node7" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="63.0444" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="63.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge9" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M79.6873,-87.5126C92.2503,-75.6172 110.6006,-60.8406 130.0444,-54 194.5234,-31.3155 1235.3096,-20.554 1470.1966,-18.4077"/>
<polygon fill="#000000" stroke="#000000" points="1470.4814,-21.9053 1480.4493,-18.3148 1470.4179,-14.9056 1470.4814,-21.9053"/>
<text text-anchor="middle" x="181.0444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- study_personnel -->
<g id="node8" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="231.0444" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="231.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge23" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M231.2884,-86.9376C232.49,-75.5759 236.102,-61.6612 246.0444,-54 270.7606,-34.9547 1243.7747,-21.4634 1470.2716,-18.577"/>
<polygon fill="#000000" stroke="#000000" points="1470.5313,-22.0741 1480.4861,-18.4476 1470.4425,-15.0747 1470.5313,-22.0741"/>
<text text-anchor="middle" x="315.5444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- study_arm -->
<g id="node9" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="396.0444" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="396.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge6" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M389.8439,-86.6055C387.4321,-75.6943 386.9121,-62.3974 395.0444,-54 414.044,-34.381 1260.4423,-21.5128 1470.3283,-18.6198"/>
<polygon fill="#000000" stroke="#000000" points="1470.4557,-22.1185 1480.4068,-18.4818 1470.3598,-15.1191 1470.4557,-22.1185"/>
<text text-anchor="middle" x="443.5444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- synonym -->
<g id="node10" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="710.0444" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="710.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge19" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M660.5571,-273.1841C591.8129,-263.9711 472.9232,-243.5441 447.0444,-210 427.8747,-185.1522 439.7772,-163.1147 462.0444,-141 503.8288,-99.5017 526.2218,-102.4675 583.0444,-87 753.1589,-40.6938 1305.3124,-23.3261 1470.1596,-19.0981"/>
<polygon fill="#000000" stroke="#000000" points="1470.541,-22.5897 1480.4495,-18.8384 1470.3644,-15.5919 1470.541,-22.5897"/>
<text text-anchor="middle" x="504.5444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M705.6562,-260.8552C701.219,-237.6442 697.7095,-197.6283 719.0444,-174 767.1439,-120.7301 1256.6538,-108.5043 1444.34,-105.7672"/>
<polygon fill="#000000" stroke="#000000" points="1444.4388,-109.2663 1454.3885,-105.6256 1444.3401,-102.267 1444.4388,-109.2663"/>
<text text-anchor="middle" x="761.5444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M762.0338,-277.1024C1011.3254,-267.9727 2085.9756,-228.2625 2421.0444,-210 2493.1743,-206.0686 2576.3769,-200.1089 2629.3184,-196.1373"/>
<polygon fill="#000000" stroke="#000000" points="2629.7823,-199.6124 2639.491,-195.3707 2629.2562,-192.6322 2629.7823,-199.6124"/>
<text text-anchor="middle" x="2056.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- clinical_measure_file -->
<g id="node11" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="565.0444" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="565.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge22" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M555.2362,-173.9654C550.841,-163.1897 548.2032,-149.9088 556.0444,-141 617.3307,-71.3696 1286.5496,-30.4101 1470.4962,-20.4119"/>
<polygon fill="#000000" stroke="#000000" points="1470.8551,-23.8978 1480.6523,-19.8647 1470.4784,-16.9079 1470.8551,-23.8978"/>
<text text-anchor="middle" x="816.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M559.7562,-173.5657C557.8443,-162.6396 557.8542,-149.3409 566.0444,-141 581.4011,-125.3607 1225.055,-110.9072 1444.576,-106.4243"/>
<polygon fill="#000000" stroke="#000000" points="1444.7779,-109.921 1454.7046,-106.2184 1444.6355,-102.9224 1444.7779,-109.921"/>
<text text-anchor="middle" x="652.0444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- pathology_file -->
<g id="node12" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2973.0444" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2973.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2964.333,-260.9442C2957.8716,-249.5853 2947.9539,-235.6712 2935.0444,-228 2902.5643,-208.6993 2801.0574,-199.1212 2737.218,-194.8882"/>
<polygon fill="#000000" stroke="#000000" points="2737.1278,-191.3753 2726.9248,-194.2301 2736.6811,-198.3611 2737.1278,-191.3753"/>
<text text-anchor="middle" x="3012.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge31" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1517.0444,-86.9735C1517.0444,-75.1918 1517.0444,-59.5607 1517.0444,-46.1581"/>
<polygon fill="#000000" stroke="#000000" points="1520.5445,-46.0033 1517.0444,-36.0034 1513.5445,-46.0034 1520.5445,-46.0033"/>
<text text-anchor="middle" x="1567.5444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- generic_file -->
<g id="node14" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="2379.0444" cy="-279" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="2379.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge12" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2395.9442,-261.5449C2415.2659,-239.4292 2441.7126,-200.9537 2421.0444,-174 2402.2821,-149.5318 2381.599,-169.8368 2354.0444,-156 2344.4297,-151.1719 2344.9169,-145.2764 2335.0444,-141 2193.8072,-79.8205 1715.5812,-34.8582 1563.7289,-21.8489"/>
<polygon fill="#000000" stroke="#000000" points="1563.6294,-18.3278 1553.3687,-20.9676 1563.036,-25.3026 1563.6294,-18.3278"/>
<text text-anchor="middle" x="2407.0444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2313.7487,-276.7433C2170.7579,-271.5353 1841.11,-257.9708 1822.0444,-243 1784.6761,-213.6573 1826.4155,-171.57 1790.0444,-141 1774.7652,-128.1578 1663.2423,-116.7506 1587.5474,-110.3713"/>
<polygon fill="#000000" stroke="#000000" points="1587.836,-106.8833 1577.5804,-109.5428 1587.256,-113.8593 1587.836,-106.8833"/>
<text text-anchor="middle" x="1860.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2412.5179,-263.4283C2424.8257,-257.4005 2438.7526,-250.219 2451.0444,-243 2461.2489,-237.0068 2462.0724,-232.4346 2473.0444,-228 2523.5263,-207.5966 2585.3848,-198.7546 2628.8465,-194.9243"/>
<polygon fill="#000000" stroke="#000000" points="2629.2493,-198.4031 2638.9293,-194.0963 2628.6764,-191.4266 2629.2493,-198.4031"/>
<text text-anchor="middle" x="2526.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- study_funding -->
<g id="node15" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2726.0444" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2726.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2693.0726,-88.6869C2666.9219,-76.6372 2629.0703,-61.1386 2594.0444,-54 2492.3426,-33.2723 1757.6502,-21.4285 1563.8238,-18.6422"/>
<polygon fill="#000000" stroke="#000000" points="1563.7308,-15.1406 1553.6819,-18.4976 1563.6309,-22.1399 1563.7308,-15.1406"/>
<text text-anchor="middle" x="2704.0444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- molecular_test -->
<g id="node16" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1340.0444" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1340.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1351.4623,-173.9777C1359.348,-162.9276 1370.7817,-149.3455 1384.0444,-141 1403.9737,-128.4596 1428.2405,-120.2405 1450.5628,-114.8736"/>
<polygon fill="#000000" stroke="#000000" points="1451.3387,-118.2866 1460.3245,-112.6736 1449.7997,-111.4579 1451.3387,-118.2866"/>
<text text-anchor="middle" x="1448.0444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2640.6358,-186.8262C2590.5449,-180.2888 2510.548,-168.3878 2483.0444,-156 2473.2347,-151.5816 2474.1393,-144.7209 2464.0444,-141 2423.2482,-125.9628 1803.983,-111.2101 1589.5065,-106.5273"/>
<polygon fill="#000000" stroke="#000000" points="1589.3728,-103.0237 1579.299,-106.3054 1589.2205,-110.022 1589.3728,-103.0237"/>
<text text-anchor="middle" x="2519.5444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node19" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2603.0444" cy="-105" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2603.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge33" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2720.3256,-182.2069C2746.9924,-173.41 2775.6348,-159.1033 2760.0444,-141 2742.4482,-120.5675 2665.7984,-130.9902 2640.0444,-123 2638.1,-122.3967 2636.1299,-121.7047 2634.164,-120.9511"/>
<polygon fill="#000000" stroke="#000000" points="2635.0764,-117.5336 2624.5072,-116.7967 2632.31,-123.9638 2635.0764,-117.5336"/>
<text text-anchor="middle" x="2800.5444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node24" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2508.0444" cy="-105" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2508.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge32" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2680.8214,-173.8352C2678.4963,-162.7283 2673.7452,-149.1363 2664.0444,-141 2630.1145,-112.5421 2609.0457,-133.5817 2566.0444,-123 2562.2372,-122.0631 2558.3122,-121.0186 2554.384,-119.9175"/>
<polygon fill="#000000" stroke="#000000" points="2555.2578,-116.5267 2544.6781,-117.0929 2553.3018,-123.2478 2555.2578,-116.5267"/>
<text text-anchor="middle" x="2710.5444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_admin -->
<g id="node18" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="2892.0444" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2892.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge4" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2861.478,-88.5068C2837.402,-76.4451 2802.5841,-61.0152 2770.0444,-54 2650.6668,-28.2635 1777.3514,-19.9825 1563.9778,-18.3327"/>
<polygon fill="#000000" stroke="#000000" points="1563.7688,-14.8311 1553.7424,-18.2548 1563.7154,-21.8309 1563.7688,-14.8311"/>
<text text-anchor="middle" x="2870.5444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge24" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2584.054,-91.7011C2565.2344,-79.3487 2535.0935,-61.7345 2506.0444,-54 2414.5324,-29.6344 1747.1164,-20.536 1563.6195,-18.4798"/>
<polygon fill="#000000" stroke="#000000" points="1563.5259,-14.9787 1553.4879,-18.368 1563.4486,-21.9783 1563.5259,-14.9787"/>
<text text-anchor="middle" x="2566.0444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2624.433,-117.0508C2629.4213,-119.3922 2634.8092,-121.5626 2640.0444,-123 2686.4919,-135.7528 2823.4305,-105.5552 2856.0444,-141 2860.5585,-145.9059 2860.2509,-150.828 2856.0444,-156 2841.2287,-174.2161 2782.2753,-183.5192 2737.2661,-188.0553"/>
<polygon fill="#000000" stroke="#000000" points="2736.6524,-184.5978 2727.0295,-189.0304 2737.3163,-191.5662 2736.6524,-184.5978"/>
<text text-anchor="middle" x="2883.0444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- treatment_response -->
<g id="node20" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1543.0444" cy="-192" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1543.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1527.5421,-174.0674C1523.7071,-168.6148 1520.1081,-162.3702 1518.0444,-156 1515.7441,-148.8995 1514.85,-140.9465 1514.6856,-133.4719"/>
<polygon fill="#000000" stroke="#000000" points="1518.1869,-133.4242 1514.8684,-123.3625 1511.1881,-133.2976 1518.1869,-133.4242"/>
<text text-anchor="middle" x="1601.0444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- exposure -->
<g id="node21" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1719.0444" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1719.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1711.0476,-174.0021C1705.1588,-162.8167 1696.084,-149.0757 1684.0444,-141 1667.6517,-130.0044 1623.1586,-120.7107 1584.2179,-114.3217"/>
<polygon fill="#000000" stroke="#000000" points="1584.3625,-110.8005 1573.9356,-112.6793 1583.2583,-117.7129 1584.3625,-110.8005"/>
<text text-anchor="middle" x="1742.5444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- treatment -->
<g id="node22" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="871.0444" cy="-192" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="871.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M881.4071,-174.288C889.2936,-162.6128 901.2925,-148.1957 916.0444,-141 962.4506,-118.364 1295.239,-109.2245 1444.6962,-106.2321"/>
<polygon fill="#000000" stroke="#000000" points="1444.7731,-109.7313 1454.7024,-106.0354 1444.6355,-102.7327 1444.7731,-109.7313"/>
<text text-anchor="middle" x="963.0444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- diagnosis -->
<g id="node23" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1697.0444" cy="-279" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1697.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1642.7412,-275.9988C1513.0156,-268.2766 1193.5062,-245.78 1162.0444,-210 1151.479,-197.9845 1151.8671,-186.3459 1162.0444,-174 1197.1699,-131.39 1351.637,-114.759 1444.8544,-108.5233"/>
<polygon fill="#000000" stroke="#000000" points="1445.3159,-112.001 1455.0701,-107.8651 1444.8657,-105.0154 1445.3159,-112.001"/>
<text text-anchor="middle" x="1206.5444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1750.056,-274.3225C1921.2606,-259.2162 2458.2123,-211.8381 2629.7784,-196.6999"/>
<polygon fill="#000000" stroke="#000000" points="2630.1756,-200.1786 2639.8293,-195.8131 2629.5603,-193.2057 2630.1756,-200.1786"/>
<text text-anchor="middle" x="2293.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge2" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2477.8421,-90.6083C2450.6079,-78.4015 2409.1065,-61.6858 2371.0444,-54 2291.9598,-38.0306 1730.935,-23.2134 1563.8711,-19.1155"/>
<polygon fill="#000000" stroke="#000000" points="1563.5283,-15.6062 1553.4459,-18.8612 1563.3575,-22.6041 1563.5283,-15.6062"/>
<text text-anchor="middle" x="2461.5444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2531.3841,-121.0785C2552.354,-135.4918 2580.2737,-154.5878 2583.0444,-156 2600.0851,-164.6854 2619.721,-172.2394 2637.0566,-178.1543"/>
<polygon fill="#000000" stroke="#000000" points="2636.3673,-181.6133 2646.9608,-181.4437 2638.5737,-174.9701 2636.3673,-181.6133"/>
<text text-anchor="middle" x="2623.5444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cytogenomic_file -->
<g id="node25" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="3157.0444" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="3157.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3135.7636,-261.4188C3120.4323,-249.8036 3098.7089,-235.4043 3077.0444,-228 3015.6494,-207.0168 2830.3017,-197.3981 2737.3806,-193.7979"/>
<polygon fill="#000000" stroke="#000000" points="2737.4566,-190.2984 2727.3316,-193.4181 2737.1922,-197.2934 2737.4566,-190.2984"/>
<text text-anchor="middle" x="3178.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- medical_history -->
<g id="node26" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1032.0444" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1032.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1019.5614,-173.9403C1013.7686,-163.1551 1009.7885,-149.873 1018.0444,-141 1032.3523,-125.6227 1310.0076,-112.9276 1444.8144,-107.6426"/>
<polygon fill="#000000" stroke="#000000" points="1445.1958,-111.1305 1455.0523,-107.2447 1444.9239,-104.1358 1445.1958,-111.1305"/>
<text text-anchor="middle" x="1086.0444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
</g>
</svg>
</div>
