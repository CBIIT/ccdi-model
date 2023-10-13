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
<svg width="2971pt" height="392pt"
 viewBox="0.00 0.00 2971.19 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 2967.1938,-388 2967.1938,4 -4,4"/>
<!-- study_admin -->
<g id="node1" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="70.1938" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="70.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study -->
<g id="node3" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2277.1938" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2277.1938" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge35" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M80.1398,-87.0972C87.7654,-75.3344 99.4722,-60.891 114.1938,-54 163.8027,-30.7785 1920.1489,-19.9794 2230.5569,-18.2502"/>
<polygon fill="#000000" stroke="#000000" points="2230.5891,-21.7502 2240.5695,-18.1948 2230.5503,-14.7503 2230.5891,-21.7502"/>
<text text-anchor="middle" x="170.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- exposure -->
<g id="node2" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1590.1938" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1590.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- participant -->
<g id="node15" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1472.1938" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1472.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1584.2606,-173.9043C1579.9161,-163.1055 1573.0455,-149.8219 1563.1938,-141 1553.4103,-132.2392 1541.2385,-125.4869 1529.0127,-120.3288"/>
<polygon fill="#000000" stroke="#000000" points="1530.2798,-117.0662 1519.6917,-116.6883 1527.7331,-123.5865 1530.2798,-117.0662"/>
<text text-anchor="middle" x="1618.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- molecular_test -->
<g id="node4" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="737.1938" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="737.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M737.5202,-173.7579C738.7712,-162.4722 742.4074,-148.7112 752.1938,-141 777.3268,-121.1964 1221.8838,-110.0575 1399.63,-106.379"/>
<polygon fill="#000000" stroke="#000000" points="1399.7487,-109.8774 1409.6749,-106.1732 1399.6053,-102.8788 1399.7487,-109.8774"/>
<text text-anchor="middle" x="816.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- study_funding -->
<g id="node5" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="236.1938" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="236.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge33" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M230.9359,-87.0032C228.9141,-75.9633 228.7944,-62.3829 237.1938,-54 255.4288,-35.8007 1926.6456,-20.9375 2230.1834,-18.3868"/>
<polygon fill="#000000" stroke="#000000" points="2230.429,-21.885 2240.3993,-18.3013 2230.3703,-14.8853 2230.429,-21.885"/>
<text text-anchor="middle" x="299.1938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- methylation_array_file -->
<g id="node6" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1172.1938" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1172.1938" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- cell_line -->
<g id="node12" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2531.1938" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2531.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge1" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1252.4146,-352.9899C1266.9508,-351.0219 1281.9992,-349.2387 1296.1938,-348 1362.7485,-342.1919 1834.4162,-352.8527 1897.1938,-330 1907.3036,-326.3198 1906.0888,-318.6937 1916.1938,-315 1973.8299,-293.9322 2407.5678,-306.5009 2468.1938,-297 2473.6021,-296.1525 2479.2034,-294.9874 2484.734,-293.6543"/>
<polygon fill="#000000" stroke="#000000" points="2485.7557,-297.0052 2494.5558,-291.1053 2483.9972,-290.2296 2485.7557,-297.0052"/>
<text text-anchor="middle" x="2007.6938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- sample -->
<g id="node16" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1128.1938" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1128.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1144.5392,-348.3785C1138.2933,-343.1724 1132.3024,-336.9729 1128.1938,-330 1108.3707,-296.3575 1113.7887,-249.6165 1120.3428,-220.092"/>
<polygon fill="#000000" stroke="#000000" points="1123.8226,-220.5915 1122.7642,-210.0497 1117.0176,-218.9506 1123.8226,-220.5915"/>
<text text-anchor="middle" x="1208.6938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- pdx -->
<g id="node24" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1590.1938" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1590.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge2" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1172.8645,-347.9774C1174.3195,-336.6325 1178.2112,-322.7216 1188.1938,-315 1219.8728,-290.4961 1509.1751,-306.0301 1548.1938,-297 1551.621,-296.2068 1555.1211,-295.1484 1558.566,-293.9403"/>
<polygon fill="#000000" stroke="#000000" points="1559.9879,-297.1424 1568.0221,-290.2357 1557.4344,-290.6247 1559.9879,-297.1424"/>
<text text-anchor="middle" x="1279.6938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- sequencing_file -->
<g id="node7" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="955.1938" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="955.1938" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge10" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1013.3704,-353.0934C1024.5453,-351.0475 1036.1931,-349.2102 1047.1938,-348 1123.8682,-339.5649 1668.6572,-356.2406 1741.1938,-330 1751.311,-326.34 1750.0756,-318.6574 1760.1938,-315 1834.1995,-288.2494 2390.4073,-308.9042 2468.1938,-297 2473.6051,-296.1719 2479.2082,-295.019 2484.7399,-293.6927"/>
<polygon fill="#000000" stroke="#000000" points="2485.7585,-297.0445 2494.5628,-291.1509 2484.0049,-290.2677 2485.7585,-297.0445"/>
<text text-anchor="middle" x="1826.6938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M954.3926,-347.8919C954.3522,-325.0866 957.6244,-285.8832 978.1938,-261 991.1331,-245.347 1001.6753,-251.3373 1020.1938,-243 1043.6406,-232.4438 1069.714,-220.1475 1090.3674,-210.2739"/>
<polygon fill="#000000" stroke="#000000" points="1091.9413,-213.4009 1099.4466,-205.9228 1088.9161,-207.0883 1091.9413,-213.4009"/>
<text text-anchor="middle" x="1044.6938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge8" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M977.4475,-348.5428C994.0045,-336.662 1017.7082,-321.8904 1041.1938,-315 1149.3717,-283.2618 1438.1781,-321.6236 1548.1938,-297 1551.6267,-296.2317 1555.1305,-295.1894 1558.5776,-293.9912"/>
<polygon fill="#000000" stroke="#000000" points="1559.9935,-297.1958 1568.0366,-290.2994 1557.4484,-290.6749 1559.9935,-297.1958"/>
<text text-anchor="middle" x="1107.6938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- diagnosis -->
<g id="node8" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="890.1938" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="890.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M884.5593,-173.6887C882.4388,-162.8088 882.1886,-149.5156 890.1938,-141 907.3933,-122.7037 1247.6344,-111.1411 1399.7659,-106.8666"/>
<polygon fill="#000000" stroke="#000000" points="1400.0495,-110.3601 1409.9483,-106.5835 1399.8549,-103.3628 1400.0495,-110.3601"/>
<text text-anchor="middle" x="934.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- synonym -->
<g id="node9" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="851.1938" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="851.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge27" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M800.1928,-275.0112C686.5569,-265.6074 420.4577,-240.527 394.1938,-210 383.7587,-197.8711 386.3106,-187.9232 394.1938,-174 408.2391,-149.1933 421.9923,-149.5279 449.1938,-141 795.9089,-32.3022 1979.7258,-19.6537 2230.3437,-18.1903"/>
<polygon fill="#000000" stroke="#000000" points="2230.5797,-21.6891 2240.5602,-18.1339 2230.541,-14.6892 2230.5797,-21.6891"/>
<text text-anchor="middle" x="491.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M869.9049,-262.1005C882.2139,-251.4983 898.9895,-237.9934 915.1938,-228 931.4426,-217.9791 938.5344,-220.9191 954.1938,-210 972.7545,-197.0578 970.105,-184.4136 990.1938,-174 1060.2215,-137.6991 1284.2895,-117.6562 1400.6015,-109.4584"/>
<polygon fill="#000000" stroke="#000000" points="1401.0975,-112.9325 1410.8311,-108.7484 1400.6128,-105.9493 1401.0975,-112.9325"/>
<text text-anchor="middle" x="1032.6938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge29" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M878.0731,-263.4856C888.7573,-257.2281 901.1191,-249.8745 912.1938,-243 922.5626,-236.5637 923.7517,-232.2446 935.1938,-228 991.9457,-206.9471 1011.0789,-223.0168 1070.1938,-210 1074.8401,-208.9769 1079.6505,-207.7552 1084.4228,-206.4367"/>
<polygon fill="#000000" stroke="#000000" points="1085.4728,-209.7765 1094.1003,-203.627 1083.521,-203.0541 1085.4728,-209.7765"/>
<text text-anchor="middle" x="977.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- pathology_file -->
<g id="node10" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2357.1938" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2357.1938" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge37" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2365.0151,-347.8272C2370.709,-336.717 2379.4752,-323.1245 2391.1938,-315 2420.0761,-294.9757 2434.1763,-305.8301 2468.1938,-297 2472.9007,-295.7782 2477.7924,-294.4625 2482.6759,-293.1184"/>
<polygon fill="#000000" stroke="#000000" points="2483.9362,-296.4004 2492.6267,-290.3403 2482.0539,-289.6582 2483.9362,-296.4004"/>
<text text-anchor="middle" x="2452.1938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge38" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2357.0983,-347.9688C2356.0166,-336.7697 2352.6399,-323.0259 2343.1938,-315 2203.5485,-196.3496 1705.8652,-242.4873 1523.1938,-228 1371.4598,-215.9662 1330.6653,-238.745 1181.1938,-210 1177.5437,-209.298 1173.8011,-208.404 1170.0753,-207.391"/>
<polygon fill="#000000" stroke="#000000" points="1170.9098,-203.9876 1160.3265,-204.4816 1168.908,-210.6952 1170.9098,-203.9876"/>
<text text-anchor="middle" x="2377.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge39" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2281.3282,-364.2598C2098.5974,-359.8048 1647.0419,-347.1219 1619.1938,-330 1610.3069,-324.5361 1603.8891,-315.2807 1599.3871,-306.1424"/>
<polygon fill="#000000" stroke="#000000" points="1602.5421,-304.6198 1595.366,-296.8254 1596.1152,-307.3937 1602.5421,-304.6198"/>
<text text-anchor="middle" x="1680.1938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- cytogenomic_file -->
<g id="node11" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="2701.1938" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="2701.1938" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;cell_line -->
<g id="edge11" class="edge">
<title>cytogenomic_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2697.6941,-347.9705C2694.6325,-336.9175 2689.0677,-323.3348 2679.1938,-315 2665.2025,-303.1896 2623.041,-293.6224 2587.2801,-287.3275"/>
<polygon fill="#000000" stroke="#000000" points="2587.8385,-283.8723 2577.3922,-285.6397 2586.6606,-290.7725 2587.8385,-283.8723"/>
<text text-anchor="middle" x="2761.6938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2784.9843,-359.4453C2823.5596,-353.0115 2856.8766,-340.2626 2837.1938,-315 2740.0039,-190.2588 2648.9853,-248.5585 2492.1938,-228 2347.7498,-209.0605 1324.7602,-234.7276 1181.1938,-210 1177.4799,-209.3603 1173.6749,-208.5014 1169.8917,-207.5043"/>
<polygon fill="#000000" stroke="#000000" points="1170.5868,-204.0606 1160.0056,-204.5979 1168.6124,-210.7764 1170.5868,-204.0606"/>
<text text-anchor="middle" x="2891.6938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;pdx -->
<g id="edge13" class="edge">
<title>cytogenomic_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2623.0728,-357.0238C2593.6193,-351.691 2560.4328,-343.2628 2532.1938,-330 2522.4555,-325.4263 2523.2869,-318.7259 2513.1938,-315 2471.1261,-299.4705 1797.7837,-283.5922 1628.5521,-279.8329"/>
<polygon fill="#000000" stroke="#000000" points="1628.4456,-276.3298 1618.3707,-279.6079 1628.2909,-283.3281 1628.4456,-276.3298"/>
<text text-anchor="middle" x="2603.6938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge32" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2578.6744,-273.7911C2682.5115,-259.9743 2916.9258,-214.3084 2870.1938,-87 2863.5656,-68.9434 2859.3827,-62.6323 2842.1938,-54 2796.4335,-31.0192 2450.7796,-21.5973 2323.7995,-18.8877"/>
<polygon fill="#000000" stroke="#000000" points="2323.6913,-15.3848 2313.6203,-18.675 2323.545,-22.3833 2323.6913,-15.3848"/>
<text text-anchor="middle" x="2912.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2522.8176,-261.253C2516.2602,-249.5617 2505.944,-235.1397 2492.1938,-228 2403.1764,-181.7787 2129.8306,-256.9469 2041.1938,-210 2007.4946,-192.151 2023.6261,-159.344 1990.1938,-141 1952.1624,-120.1325 1678.4723,-110.2929 1545.0061,-106.6949"/>
<polygon fill="#000000" stroke="#000000" points="1544.9562,-103.1924 1534.867,-106.4263 1544.7708,-110.19 1544.9562,-103.1924"/>
<text text-anchor="middle" x="2081.6938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge30" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2492.6223,-267.4751C2443.2114,-252.7533 2363.0783,-229.0366 2356.1938,-228 2097.9628,-189.1184 1438.5108,-254.5303 1181.1938,-210 1177.4804,-209.3574 1173.6758,-208.4964 1169.8928,-207.4979"/>
<polygon fill="#000000" stroke="#000000" points="1170.5884,-204.0543 1160.0071,-204.5894 1168.6126,-210.7697 1170.5884,-204.0543"/>
<text text-anchor="middle" x="2447.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- family_relationship -->
<g id="node13" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1290.1938" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1290.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge36" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1290.6648,-173.5532C1291.9369,-162.6224 1295.3838,-149.3231 1304.1938,-141 1318.6357,-127.3562 1363.537,-118.1639 1403.2879,-112.4848"/>
<polygon fill="#000000" stroke="#000000" points="1403.8302,-115.9433 1413.2614,-111.116 1402.8784,-109.0083 1403.8302,-115.9433"/>
<text text-anchor="middle" x="1383.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- follow_up -->
<g id="node14" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="1463.1938" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="1463.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1465.0586,-173.9735C1466.2774,-162.1918 1467.8944,-146.5607 1469.2809,-133.1581"/>
<polygon fill="#000000" stroke="#000000" points="1472.7837,-133.3105 1470.3314,-123.0034 1465.8209,-132.5901 1472.7837,-133.3105"/>
<text text-anchor="middle" x="1514.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge24" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1530.7358,-98.6731C1683.7724,-82.1337 2093.4069,-37.8627 2231.2239,-22.9682"/>
<polygon fill="#000000" stroke="#000000" points="2231.8664,-26.4192 2241.4324,-21.8649 2231.1142,-19.4597 2231.8664,-26.4192"/>
<text text-anchor="middle" x="1973.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1150.3781,-176.2841C1167.943,-164.6402 1193.5425,-149.3934 1218.1938,-141 1251.3421,-129.7135 1339.6009,-118.7097 1402.761,-111.8997"/>
<polygon fill="#000000" stroke="#000000" points="1403.4894,-115.342 1413.0622,-110.802 1402.7477,-108.3814 1403.4894,-115.342"/>
<text text-anchor="middle" x="1254.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- clinical_measure_file -->
<g id="node17" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="2240.1938" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="2240.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge19" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2284.7635,-175.4184C2302.564,-166.31 2316.4687,-154.1948 2305.1938,-141 2271.8714,-102.0034 2224.5161,-161.9966 2191.1938,-123 2180.7997,-110.836 2184.273,-101.4258 2191.1938,-87 2201.8442,-64.8003 2223.5036,-47.4894 2242.4202,-35.7591"/>
<polygon fill="#000000" stroke="#000000" points="2244.3138,-38.7057 2251.1467,-30.6086 2240.7558,-32.6774 2244.3138,-38.7057"/>
<text text-anchor="middle" x="2277.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2158.4593,-180.1095C2115.0478,-173.146 2066.5478,-164.146 2046.1938,-156 2034.8635,-151.4654 2034.7722,-144.8572 2023.1938,-141 1978.9401,-126.2575 1683.4913,-113.1232 1544.3794,-107.673"/>
<polygon fill="#000000" stroke="#000000" points="1544.3642,-104.1699 1534.2356,-107.2784 1544.092,-111.1646 1544.3642,-104.1699"/>
<text text-anchor="middle" x="2175.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- medical_history -->
<g id="node18" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1746.1938" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1746.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1724.0141,-174.5497C1708.6222,-163.2999 1687.1869,-149.2758 1666.1938,-141 1626.8683,-125.4974 1580.3791,-116.5755 1542.7694,-111.4922"/>
<polygon fill="#000000" stroke="#000000" points="1542.7756,-107.9642 1532.4104,-110.158 1541.8813,-114.9069 1542.7756,-107.9642"/>
<text text-anchor="middle" x="1762.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- study_personnel -->
<g id="node19" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2492.1938" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2492.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge40" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2461.8516,-88.0559C2442.1018,-77.4359 2415.5719,-63.9279 2391.1938,-54 2367.8569,-44.4961 2341.0153,-35.9099 2319.2419,-29.5084"/>
<polygon fill="#000000" stroke="#000000" points="2320.2042,-26.1433 2309.6253,-26.7255 2318.2582,-32.8674 2320.2042,-26.1433"/>
<text text-anchor="middle" x="2491.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- publication -->
<g id="node20" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="2660.1938" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="2660.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge4" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2635.1297,-88.2234C2616.607,-76.672 2590.3419,-62.0146 2565.1938,-54 2521.2976,-40.0105 2393.1643,-27.6381 2323.5338,-21.7106"/>
<polygon fill="#000000" stroke="#000000" points="2323.5504,-18.1997 2313.2922,-20.8493 2322.9637,-25.1751 2323.5504,-18.1997"/>
<text text-anchor="middle" x="2651.1938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- radiology_file -->
<g id="node21" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1923.1938" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1923.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1899.5597,-174.7565C1882.3305,-163.1397 1857.9392,-148.5995 1834.1938,-141 1781.9213,-124.2708 1633.7717,-113.6637 1544.0229,-108.5768"/>
<polygon fill="#000000" stroke="#000000" points="1544.0947,-105.0755 1533.9154,-108.0133 1543.705,-112.0647 1544.0947,-105.0755"/>
<text text-anchor="middle" x="1927.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- study_arm -->
<g id="node22" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2801.1938" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2801.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge20" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2777.0067,-88.4092C2758.4935,-76.6302 2731.8585,-61.6085 2706.1938,-54 2635.6569,-33.0889 2419.9,-23.0498 2323.9933,-19.5278"/>
<polygon fill="#000000" stroke="#000000" points="2323.846,-16.0203 2313.7267,-19.1589 2323.5946,-23.0158 2323.846,-16.0203"/>
<text text-anchor="middle" x="2789.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- therapeutic_procedure -->
<g id="node23" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="521.1938" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="521.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M527.1309,-173.8518C531.9415,-162.2989 539.9594,-148.1991 552.1938,-141 588.4941,-119.6397 1188.8049,-109.0475 1399.6685,-105.9729"/>
<polygon fill="#000000" stroke="#000000" points="1399.7627,-109.472 1409.711,-105.8279 1399.6615,-102.4728 1399.7627,-109.472"/>
<text text-anchor="middle" x="645.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge5" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1618.5043,-278.5967C1751.0149,-276.4297 2305.753,-264.1569 2358.1938,-210 2396.2531,-170.6952 2386.8594,-136.3287 2363.1938,-87 2352.5434,-64.8003 2330.8839,-47.4894 2311.9674,-35.7591"/>
<polygon fill="#000000" stroke="#000000" points="2313.6318,-32.6774 2303.2409,-30.6086 2310.0737,-38.7057 2313.6318,-32.6774"/>
<text text-anchor="middle" x="2407.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1567.4614,-268.049C1561.3178,-265.4254 1554.5953,-262.8511 1548.1938,-261 1458.6987,-235.1208 1433.5071,-240.5442 1341.1938,-228 1270.2857,-218.3645 1251.0332,-225.5965 1181.1938,-210 1177.6165,-209.2011 1173.9429,-208.2469 1170.2789,-207.2005"/>
<polygon fill="#000000" stroke="#000000" points="1171.262,-203.8412 1160.6754,-204.2584 1169.2115,-210.5341 1171.262,-203.8412"/>
<text text-anchor="middle" x="1495.1938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node25" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1443.1938" cy="-366" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="1443.1938" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge14" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1577.9551,-362.2464C1741.0188,-357.0742 2005.8188,-346.4811 2103.1938,-330 2126.9099,-325.986 2131.4836,-319.0491 2155.1938,-315 2292.5463,-291.5439 2330.8116,-320.2818 2468.1938,-297 2473.521,-296.0972 2479.0403,-294.9097 2484.497,-293.5743"/>
<polygon fill="#000000" stroke="#000000" points="2485.4057,-296.9544 2494.1963,-291.0403 2483.6363,-290.1818 2485.4057,-296.9544"/>
<text text-anchor="middle" x="2263.6938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1343.7762,-353.4498C1267.7521,-343.736 1175.6483,-331.6621 1174.1938,-330 1169.8035,-324.983 1169.8149,-320.0269 1174.1938,-315 1212.5059,-271.0176 1265.8816,-340.9824 1304.1938,-297 1314.703,-284.9354 1313.2093,-274.2182 1304.1938,-261 1300.2088,-255.1574 1221.7811,-225.8946 1170.9768,-207.4032"/>
<polygon fill="#000000" stroke="#000000" points="1172.1196,-204.0946 1161.5255,-203.9713 1169.7304,-210.6743 1172.1196,-204.0946"/>
<text text-anchor="middle" x="1420.6938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge16" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1398.5462,-348.8465C1381.1446,-339.6762 1367.7946,-327.6778 1379.1938,-315 1404.446,-286.9154 1511.6519,-306.5451 1548.1938,-297 1551.5974,-296.1109 1555.0821,-294.9898 1558.5176,-293.7437"/>
<polygon fill="#000000" stroke="#000000" points="1559.9616,-296.9361 1567.9615,-289.9897 1557.3758,-290.4312 1559.9616,-296.9361"/>
<text text-anchor="middle" x="1487.6938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
</g>
</svg>
</div>
