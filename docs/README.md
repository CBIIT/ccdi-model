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
<svg width="3263pt" height="305pt"
 viewBox="0.00 0.00 3263.24 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 3259.237,-301 3259.237,4 -4,4"/>
<!-- study_personnel -->
<g id="node1" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="952.0433" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="952.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study -->
<g id="node7" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2388.0433" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2388.0433" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge18" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M983.0839,-88.1181C1006.9222,-76.1065 1041.0702,-60.9195 1073.0433,-54 1198.7756,-26.7893 2121.7973,-19.59 2341.2987,-18.2549"/>
<polygon fill="#000000" stroke="#000000" points="2341.5316,-21.7537 2351.5105,-18.194 2341.4897,-14.7538 2341.5316,-21.7537"/>
<text text-anchor="middle" x="1142.5433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- pathology_file -->
<g id="node2" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="76.0433" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="76.0433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- sample -->
<g id="node4" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="707.0433" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="707.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M105.1151,-262.0977C126.9032,-250.3248 157.864,-235.4478 187.0433,-228 273.8784,-205.836 537.6216,-196.4186 652.5458,-193.2913"/>
<polygon fill="#000000" stroke="#000000" points="652.9608,-196.7816 662.8641,-193.0166 652.7744,-189.7841 652.9608,-196.7816"/>
<text text-anchor="middle" x="248.0433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- survival -->
<g id="node3" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="2326.0433" cy="-192" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="2326.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- participant -->
<g id="node22" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1841.0433" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1841.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2288.0388,-180.8815C2256.7581,-171.6345 2216.4042,-159.4492 2209.0433,-156 2197.9923,-150.8217 2197.5448,-145.0807 2186.0433,-141 2137.3682,-123.7305 1999.0368,-113.4414 1913.0457,-108.5314"/>
<polygon fill="#000000" stroke="#000000" points="1913.0081,-105.0239 1902.828,-107.9592 1912.6166,-112.013 1913.0081,-105.0239"/>
<text text-anchor="middle" x="2248.5433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- pdx -->
<g id="node17" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1223.0433" cy="-105" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1223.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge12" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M701.8427,-174.0602C699.8439,-163.0429 699.7281,-149.4665 708.0433,-141 726.664,-122.0404 1160.2638,-129.4512 1186.0433,-123 1188.2391,-122.4505 1190.4583,-121.7612 1192.6613,-120.9753"/>
<polygon fill="#000000" stroke="#000000" points="1194.2106,-124.1214 1202.0943,-117.0434 1191.5175,-117.6602 1194.2106,-124.1214"/>
<text text-anchor="middle" x="744.5433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node18" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="1318.0433" cy="-105" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="1318.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge13" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M750.4458,-187.8602C787.3321,-183.2651 841.1331,-173.9843 885.0433,-156 896.3368,-151.3745 896.4378,-144.7752 908.0433,-141 982.526,-116.7713 1182.9289,-136.7145 1260.0433,-123 1264.1889,-122.2627 1268.4526,-121.3174 1272.6968,-120.2469"/>
<polygon fill="#000000" stroke="#000000" points="1273.7797,-123.5792 1282.4992,-117.5608 1271.9297,-116.8281 1273.7797,-123.5792"/>
<text text-anchor="middle" x="944.5433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M750.5897,-188.6477C816.8778,-183.1462 939.7568,-171.2708 981.0433,-156 992.4894,-151.7663 992.4226,-144.7281 1004.0433,-141 1013.1042,-138.0931 1567.1442,-115.8634 1768.7223,-107.8599"/>
<polygon fill="#000000" stroke="#000000" points="1769.0592,-111.3494 1778.9125,-107.4555 1768.7815,-104.3549 1769.0592,-111.3494"/>
<text text-anchor="middle" x="1040.5433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_arm -->
<g id="node5" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1117.0433" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1117.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge7" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1152.0079,-90.301C1182.9482,-78.073 1229.6414,-61.4997 1272.0433,-54 1378.2921,-35.2076 2143.8372,-21.8733 2341.5452,-18.7172"/>
<polygon fill="#000000" stroke="#000000" points="2341.6621,-22.2159 2351.6053,-18.5576 2341.551,-15.2168 2341.6621,-22.2159"/>
<text text-anchor="middle" x="1320.5433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- synonym -->
<g id="node6" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2175.0433" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2175.0433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2123.3001,-276.6297C1952.4618,-268.6988 1390.8723,-241.7915 927.0433,-210 870.1147,-206.098 804.9821,-200.6456 760.4486,-196.7664"/>
<polygon fill="#000000" stroke="#000000" points="760.6975,-193.2749 750.4305,-195.89 760.0874,-200.2482 760.6975,-193.2749"/>
<text text-anchor="middle" x="1483.5433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge5" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2227.0245,-276.6295C2362.2931,-269.9342 2717.2051,-248.801 2752.0433,-210 2788.5666,-169.3221 2787.9252,-129.0939 2753.0433,-87 2713.0657,-38.757 2523.4996,-23.9972 2434.4544,-19.685"/>
<polygon fill="#000000" stroke="#000000" points="2434.5162,-16.1843 2424.3657,-19.2205 2434.1942,-23.1769 2434.5162,-16.1843"/>
<text text-anchor="middle" x="2821.5433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2175.7536,-260.7736C2176.6449,-227.1834 2176.4114,-157.4355 2160.0433,-141 2142.9312,-123.8175 2001.6445,-113.3589 1912.9335,-108.4235"/>
<polygon fill="#000000" stroke="#000000" points="1913.097,-104.9273 1902.9212,-107.8774 1912.7157,-111.9169 1913.097,-104.9273"/>
<text text-anchor="middle" x="2218.5433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- treatment -->
<g id="node8" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="2450.0433" cy="-192" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="2450.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2406.1035,-180.0776C2398.4232,-178.0273 2390.5049,-175.9349 2383.0433,-174 2351.1144,-165.7206 2341.2754,-169.1916 2311.0433,-156 2299.8577,-151.1192 2299.5922,-144.9446 2288.0433,-141 2220.7733,-118.0235 2022.0294,-109.5085 1913.6055,-106.5147"/>
<polygon fill="#000000" stroke="#000000" points="1913.4923,-103.0105 1903.4023,-106.2419 1913.3051,-110.008 1913.4923,-103.0105"/>
<text text-anchor="middle" x="2358.0433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- diagnosis -->
<g id="node9" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="903.0433" cy="-279" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="903.0433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M877.4558,-262.9505C867.6152,-256.7491 856.2872,-249.5749 846.0433,-243 835.7727,-236.4081 834.0879,-233.1917 823.0433,-228 801.5444,-217.8942 776.5027,-209.7111 755.2,-203.7156"/>
<polygon fill="#000000" stroke="#000000" points="755.9581,-200.2944 745.389,-201.0326 754.1116,-207.0465 755.9581,-200.2944"/>
<text text-anchor="middle" x="890.5433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M920.8744,-261.8066C925.9769,-256.1828 931.1927,-249.6602 935.0433,-243 951.2227,-215.015 933.1538,-194.6265 958.0433,-174 963.2882,-169.6534 1194.2624,-141.6501 1201.0433,-141 1406.3694,-121.3142 1649.8638,-111.2629 1768.6261,-107.2143"/>
<polygon fill="#000000" stroke="#000000" points="1768.8119,-110.7101 1778.6884,-106.8755 1768.5763,-103.7141 1768.8119,-110.7101"/>
<text text-anchor="middle" x="1002.5433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- cytogenomic_file -->
<g id="node10" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="260.0433" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="260.0433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M282.8484,-261.491C299.227,-249.9089 322.3348,-235.5196 345.0433,-228 400.7124,-209.566 566.101,-198.9327 652.7362,-194.4829"/>
<polygon fill="#000000" stroke="#000000" points="653.0872,-197.9698 662.8984,-193.9708 652.7348,-190.9786 653.0872,-197.9698"/>
<text text-anchor="middle" x="416.5433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node11" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="2634.0433" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="2634.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge8" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2624.7685,-173.9818C2618.7352,-163.4762 2610.125,-150.4727 2600.0433,-141 2547.3173,-91.4596 2471.1137,-53.4685 2425.8758,-33.5381"/>
<polygon fill="#000000" stroke="#000000" points="2427.0064,-30.2135 2416.4395,-29.4452 2424.221,-36.6354 2427.0064,-30.2135"/>
<text text-anchor="middle" x="2663.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2554.7282,-179.7083C2501.8859,-171.2485 2440.0129,-160.7179 2428.0433,-156 2416.6894,-151.5248 2416.6246,-144.8485 2405.0433,-141 2359.5682,-125.8885 2055.0453,-112.8759 1913.3316,-107.5591"/>
<polygon fill="#000000" stroke="#000000" points="1913.1283,-104.0492 1903.005,-107.1745 1912.8677,-111.0444 1913.1283,-104.0492"/>
<text text-anchor="middle" x="2514.0433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- medical_history -->
<g id="node12" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1141.0433" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1141.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1167.6888,-174.7438C1187.3806,-162.9603 1215.3043,-148.2224 1242.0433,-141 1291.6439,-127.6024 1620.4751,-113.4764 1768.7525,-107.6997"/>
<polygon fill="#000000" stroke="#000000" points="1769.2532,-111.1831 1779.1101,-107.2984 1768.9821,-104.1883 1769.2532,-111.1831"/>
<text text-anchor="middle" x="1310.0433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- methylation_array_file -->
<g id="node13" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="483.0433" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="483.0433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge28" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M485.2447,-260.8094C487.5612,-249.6921 492.3107,-236.0984 502.0433,-228 524.4381,-209.3654 599.9549,-199.9229 652.7873,-195.486"/>
<polygon fill="#000000" stroke="#000000" points="653.3409,-198.9529 663.0288,-194.6641 652.7808,-191.9754 653.3409,-198.9529"/>
<text text-anchor="middle" x="593.5433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- radiology_file -->
<g id="node14" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1318.0433" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1318.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1344.7449,-174.9464C1364.4639,-163.2609 1392.397,-148.5571 1419.0433,-141 1482.797,-122.9189 1665.9788,-112.4525 1768.806,-107.8415"/>
<polygon fill="#000000" stroke="#000000" points="1768.9678,-111.3379 1778.8037,-107.4003 1768.6591,-104.3447 1768.9678,-111.3379"/>
<text text-anchor="middle" x="1478.0433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- sequencing_file -->
<g id="node15" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="700.0433" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="700.0433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M692.8564,-261.0127C689.8649,-251.2239 687.5952,-238.9171 690.0433,-228 690.7172,-224.9946 691.6716,-221.9446 692.7885,-218.9567"/>
<polygon fill="#000000" stroke="#000000" points="696.0112,-220.3222 696.7649,-209.7542 689.5854,-217.5455 696.0112,-220.3222"/>
<text text-anchor="middle" x="756.5433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- study_funding -->
<g id="node16" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2876.0433" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2876.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge2" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2851.8402,-87.7001C2834.2061,-76.0569 2809.2609,-61.5081 2785.0433,-54 2720.7429,-34.0653 2524.8958,-23.6385 2434.5747,-19.7813"/>
<polygon fill="#000000" stroke="#000000" points="2434.4948,-16.275 2424.3572,-19.3539 2434.2022,-23.2689 2434.4948,-16.275"/>
<text text-anchor="middle" x="2881.0433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge32" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1202.0983,-117.0594C1196.9985,-119.4633 1191.4512,-121.6584 1186.0433,-123 1157.1253,-130.1741 670.7546,-119.5814 650.0433,-141 638.906,-152.5175 650.9288,-164.5073 666.7544,-173.9657"/>
<polygon fill="#000000" stroke="#000000" points="665.3645,-177.1954 675.8146,-178.9408 668.7339,-171.0596 665.3645,-177.1954"/>
<text text-anchor="middle" x="674.0433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge31" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1244.024,-93.0796C1249.1223,-90.6699 1254.66,-88.4374 1260.0433,-87 1469.1192,-31.1741 2155.4292,-20.3243 2341.2763,-18.3909"/>
<polygon fill="#000000" stroke="#000000" points="2341.5623,-21.8883 2351.5267,-18.2881 2341.4921,-14.8887 2341.5623,-21.8883"/>
<text text-anchor="middle" x="1495.0433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1282.5113,-117.63C1275.1677,-119.7849 1267.421,-121.7334 1260.0433,-123 1159.2178,-140.309 896.0111,-105.5661 800.0433,-141 789.9504,-144.7266 790.1557,-150.2802 781.0433,-156 770.3607,-162.7053 758.2458,-169.0672 746.9568,-174.525"/>
<polygon fill="#000000" stroke="#000000" points="745.2678,-171.4518 737.7178,-178.8847 748.2551,-177.7824 745.2678,-171.4518"/>
<text text-anchor="middle" x="840.5433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge17" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1366.4479,-101.0643C1545.16,-86.5335 2166.5426,-36.0099 2341.7386,-21.765"/>
<polygon fill="#000000" stroke="#000000" points="2342.2259,-25.237 2351.9094,-20.938 2341.6586,-18.26 2342.2259,-25.237"/>
<text text-anchor="middle" x="1958.5433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- treatment_response -->
<g id="node19" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1514.0433" cy="-192" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1514.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1525.0835,-173.8451C1533.0408,-162.4444 1544.8542,-148.5209 1559.0433,-141 1594.321,-122.3012 1697.6463,-112.8584 1768.9156,-108.4408"/>
<polygon fill="#000000" stroke="#000000" points="1769.4137,-111.9173 1779.1863,-107.8249 1768.9947,-104.9298 1769.4137,-111.9173"/>
<text text-anchor="middle" x="1642.0433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- publication -->
<g id="node20" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="3034.0433" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="3034.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge11" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3011.7931,-87.9991C2994.9824,-76.1772 2970.8143,-61.282 2947.0433,-54 2898.7134,-39.1946 2560.1925,-24.693 2434.7024,-19.7668"/>
<polygon fill="#000000" stroke="#000000" points="2434.764,-16.2666 2424.6352,-19.3742 2434.4912,-23.2613 2434.764,-16.2666"/>
<text text-anchor="middle" x="3030.0433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- exposure -->
<g id="node21" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1690.0433" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1690.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1707.2336,-174.7154C1718.6332,-163.9596 1734.3362,-150.4282 1750.0433,-141 1762.2341,-133.6824 1776.1794,-127.302 1789.4291,-122.0279"/>
<polygon fill="#000000" stroke="#000000" points="1790.8373,-125.2365 1798.9191,-118.3855 1788.329,-118.7013 1790.8373,-125.2365"/>
<text text-anchor="middle" x="1793.5433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge10" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1895.7436,-96.2999C2003.9333,-79.0924 2243.3901,-41.007 2343.1022,-25.1478"/>
<polygon fill="#000000" stroke="#000000" points="2343.8253,-28.5769 2353.1513,-23.5495 2342.7257,-21.6638 2343.8253,-28.5769"/>
<text text-anchor="middle" x="2198.5433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_admin -->
<g id="node23" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="3185.0433" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="3185.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3159.5276,-88.175C3140.0116,-76.2765 3111.9637,-61.2078 3085.0433,-54 3022.6681,-37.2993 2580.9031,-23.4505 2434.8153,-19.2837"/>
<polygon fill="#000000" stroke="#000000" points="2434.5089,-15.7737 2424.4138,-18.9891 2434.3107,-22.7709 2434.5089,-15.7737"/>
<text text-anchor="middle" x="3178.5433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- molecular_test -->
<g id="node24" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1841.0433" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1841.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1841.0433,-173.9735C1841.0433,-162.1918 1841.0433,-146.5607 1841.0433,-133.1581"/>
<polygon fill="#000000" stroke="#000000" points="1844.5434,-133.0033 1841.0433,-123.0034 1837.5434,-133.0034 1844.5434,-133.0033"/>
<text text-anchor="middle" x="1905.0433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- family_relationship -->
<g id="node25" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="2039.0433" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="2039.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2020.1961,-174.1855C2007.6814,-163.2182 1990.4125,-149.6504 1973.0433,-141 1951.558,-130.2997 1926.4683,-122.4378 1903.967,-116.8406"/>
<polygon fill="#000000" stroke="#000000" points="1904.707,-113.419 1894.1678,-114.5027 1903.0825,-120.2279 1904.707,-113.419"/>
<text text-anchor="middle" x="2076.5433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
</g>
</svg>
</div>
