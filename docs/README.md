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
<svg width="2329pt" height="479pt"
 viewBox="0.00 0.00 2329.34 479.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 475)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-475 2325.3431,-475 2325.3431,4 -4,4"/>
<!-- study_funding -->
<g id="node1" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="77.3431" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="77.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study -->
<g id="node18" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1606.3431" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1606.3431" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge29" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M72.1021,-87.0201C70.0872,-75.9869 69.9686,-62.4077 78.3431,-54 105.1259,-27.1112 1304.9824,-19.5282 1559.2936,-18.2217"/>
<polygon fill="#000000" stroke="#000000" points="1559.6783,-21.7199 1569.6605,-18.1693 1559.6429,-14.72 1559.6783,-21.7199"/>
<text text-anchor="middle" x="140.3431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- radiology_file -->
<g id="node2" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1438.3431" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1438.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- participant -->
<g id="node7" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1205.3431" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1205.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1426.8071,-174.1389C1418.5673,-162.8621 1406.4676,-148.9665 1392.3431,-141 1381.6005,-134.941 1319.8462,-123.714 1270.1986,-115.4025"/>
<polygon fill="#000000" stroke="#000000" points="1270.569,-111.9161 1260.1304,-113.7288 1269.421,-118.8214 1270.569,-111.9161"/>
<text text-anchor="middle" x="1470.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- pdx -->
<g id="node3" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="819.3431" cy="-366" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="819.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample -->
<g id="node8" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="874.3431" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="874.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M807.981,-349.4844C802.313,-339.0353 797.9012,-325.5569 804.3431,-315 809.9533,-305.8062 818.7436,-298.8612 828.2243,-293.6517"/>
<polygon fill="#000000" stroke="#000000" points="829.9793,-296.6904 837.4444,-289.1721 826.9202,-290.3942 829.9793,-296.6904"/>
<text text-anchor="middle" x="828.3431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge17" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M846.5905,-361.3038C873.0181,-356.9748 914.2955,-350.809 950.3431,-348 976.6016,-345.9538 1877.4781,-346.0731 1898.3431,-330 1935.6796,-301.2385 1892.4105,-259.6377 1927.3431,-228 1960.8147,-197.6856 1996.8199,-243.2812 2027.3431,-210 2064.371,-169.6264 2067.4415,-131.3935 2035.3431,-87 2007.9206,-49.0734 1981.0788,-63.9333 1935.3431,-54 1836.1459,-32.4554 1717.1789,-23.5021 1652.9695,-20.0219"/>
<polygon fill="#000000" stroke="#000000" points="1652.9365,-16.5156 1642.7679,-19.4904 1652.5722,-23.5061 1652.9365,-16.5156"/>
<text text-anchor="middle" x="2075.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- methylation_array_file -->
<g id="node4" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="360.3431" cy="-453" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="360.3431" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge7" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M399.4081,-435.9346C427.0744,-424.556 465.3405,-410.2274 500.3431,-402 552.9598,-389.6324 708.9669,-375.3399 781.4903,-369.139"/>
<polygon fill="#000000" stroke="#000000" points="781.8944,-372.6174 791.5625,-368.284 781.3022,-365.6424 781.8944,-372.6174"/>
<text text-anchor="middle" x="591.8431" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M300.3068,-437.5911C278.6823,-429.1315 262.4396,-417.2321 275.3431,-402 291.0701,-383.4349 359.5759,-389.2076 383.3431,-384 497.1935,-359.0543 522.3085,-339.0896 636.3431,-315 699.5177,-301.6545 773.1317,-291.3045 821.5706,-285.1955"/>
<polygon fill="#000000" stroke="#000000" points="822.0216,-288.6665 831.512,-283.9568 821.156,-281.7202 822.0216,-288.6665"/>
<text text-anchor="middle" x="603.8431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- cell_line -->
<g id="node19" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="205.3431" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="205.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge9" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M290.1076,-438.5934C258.9749,-428.5451 224.8275,-411.7612 204.3431,-384 168.658,-335.6381 183.7361,-260.1568 195.7728,-219.7476"/>
<polygon fill="#000000" stroke="#000000" points="199.1664,-220.6221 198.8115,-210.0332 192.4856,-218.5323 199.1664,-220.6221"/>
<text text-anchor="middle" x="275.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- cytogenomic_file -->
<g id="node5" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="137.3431" cy="-453" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="137.3431" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;pdx -->
<g id="edge36" class="edge">
<title>cytogenomic_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M185.7248,-437.7734C231.2769,-423.5399 294.2756,-404.1574 306.3431,-402 436.0846,-378.8049 470.8837,-393.4482 602.3431,-384 665.2178,-379.4811 738.2527,-373.2121 781.5349,-369.3901"/>
<polygon fill="#000000" stroke="#000000" points="781.96,-372.8663 791.6119,-368.497 781.3419,-365.8936 781.96,-372.8663"/>
<text text-anchor="middle" x="377.8431" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge35" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M148.4626,-434.8127C164.5076,-410.3763 196.6318,-367.7376 236.3431,-348 249.4329,-341.494 670.0726,-299.2597 821.0575,-284.2682"/>
<polygon fill="#000000" stroke="#000000" points="821.4242,-287.7491 831.0298,-283.2788 820.733,-280.7833 821.4242,-287.7491"/>
<text text-anchor="middle" x="307.8431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;cell_line -->
<g id="edge34" class="edge">
<title>cytogenomic_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M105.6953,-436.1075C64.2283,-411.5844 -.3673,-363.7087 25.3431,-315 53.5134,-261.6312 116.4162,-227.0285 159.8601,-208.5181"/>
<polygon fill="#000000" stroke="#000000" points="161.454,-211.6466 169.3598,-204.5932 158.781,-205.177 161.454,-211.6466"/>
<text text-anchor="middle" x="96.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- exposure -->
<g id="node6" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1691.3431" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1691.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1651.5995,-179.8703C1632.2147,-173.5119 1608.7376,-165.1485 1588.3431,-156 1575.8181,-150.3815 1574.4924,-144.9424 1561.3431,-141 1459.732,-110.5349 1428.7413,-135.007 1323.3431,-123 1305.787,-121 1286.8354,-118.3355 1269.3654,-115.6709"/>
<polygon fill="#000000" stroke="#000000" points="1269.6903,-112.1796 1259.2723,-114.1071 1268.6185,-119.097 1269.6903,-112.1796"/>
<text text-anchor="middle" x="1631.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge37" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1232.6877,-88.7602C1253.5266,-77.1604 1283.3172,-62.209 1311.3431,-54 1356.8852,-40.6604 1489.2971,-27.9034 1560.2201,-21.7795"/>
<polygon fill="#000000" stroke="#000000" points="1560.5547,-25.2637 1570.2203,-20.9248 1559.9585,-18.2892 1560.5547,-25.2637"/>
<text text-anchor="middle" x="1361.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge30" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M868.194,-297.2076C864.3793,-307.2872 858.9467,-319.8012 852.3431,-330 849.4228,-334.5104 845.9259,-338.9939 842.3169,-343.1873"/>
<polygon fill="#000000" stroke="#000000" points="839.5068,-341.075 835.3608,-350.8249 844.682,-345.7885 839.5068,-341.075"/>
<text text-anchor="middle" x="897.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M918.59,-277.189C1056.9903,-271.1289 1475.1549,-249.6715 1520.3431,-210 1543.7943,-189.4119 1554.446,-163.9891 1533.3431,-141 1517.5064,-123.7477 1346.598,-125.7673 1323.3431,-123 1305.8833,-120.9223 1287.0348,-118.2446 1269.6361,-115.5928"/>
<polygon fill="#000000" stroke="#000000" points="1269.9982,-112.1073 1259.581,-114.0392 1268.9293,-119.0252 1269.9982,-112.1073"/>
<text text-anchor="middle" x="1579.8431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge32" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M864.5286,-261.4194C856.8919,-249.6439 845.1179,-235.0523 830.3431,-228 773.4593,-200.848 325.505,-220.4357 263.3431,-210 259.1906,-209.3029 254.922,-208.3852 250.6748,-207.3327"/>
<polygon fill="#000000" stroke="#000000" points="251.4354,-203.9126 240.8678,-204.6727 249.6029,-210.6685 251.4354,-203.9126"/>
<text text-anchor="middle" x="885.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- molecular_test -->
<g id="node9" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="352.3431" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="352.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M379.3943,-174.9024C399.7153,-163.0324 428.6891,-148.1195 456.3431,-141 520.6211,-124.4518 957.8184,-111.4228 1132.9848,-106.8079"/>
<polygon fill="#000000" stroke="#000000" points="1133.231,-110.3028 1143.1359,-106.5422 1133.0477,-103.3052 1133.231,-110.3028"/>
<text text-anchor="middle" x="520.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- follow_up -->
<g id="node10" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="505.3431" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="505.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M535.7489,-176.943C561.5681,-164.9289 599.9597,-148.8554 635.3431,-141 728.0331,-120.422 1001.0354,-110.4854 1132.6981,-106.785"/>
<polygon fill="#000000" stroke="#000000" points="1132.7955,-110.2837 1142.6949,-106.5084 1132.6019,-103.2864 1132.7955,-110.2837"/>
<text text-anchor="middle" x="680.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- study_admin -->
<g id="node11" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1402.3431" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1402.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge4" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1407.4785,-87.0195C1411.5971,-75.8413 1418.5133,-62.1017 1429.3431,-54 1449.6681,-38.7951 1515.0702,-28.4242 1560.4095,-22.8539"/>
<polygon fill="#000000" stroke="#000000" points="1561.0926,-26.2974 1570.6086,-21.6396 1560.2649,-19.3465 1561.0926,-26.2974"/>
<text text-anchor="middle" x="1485.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node12" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1327.3431" cy="-453" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="1327.3431" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge42" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1236.4641,-439.4268C1193.8716,-432.9144 1142.4599,-424.8374 1096.3431,-417 1010.2478,-402.3684 909.465,-383.3305 856.3893,-373.1554"/>
<polygon fill="#000000" stroke="#000000" points="856.9095,-369.6914 846.4288,-371.2424 855.5892,-376.5657 856.9095,-369.6914"/>
<text text-anchor="middle" x="1204.8431" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge41" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1325.4824,-434.6612C1323.6955,-424.2982 1320.1955,-411.5482 1313.3431,-402 1288.3317,-367.1485 1272.9897,-364.3812 1233.3431,-348 1130.6125,-305.5537 1000.4206,-288.8906 928.4225,-282.599"/>
<polygon fill="#000000" stroke="#000000" points="928.4899,-279.0924 918.2323,-281.7441 927.9047,-286.0679 928.4899,-279.0924"/>
<text text-anchor="middle" x="1407.8431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge40" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1410.339,-438.5863C1478.1996,-423.1288 1557.3625,-394.3448 1520.3431,-348 1411.1281,-211.2729 1307.3067,-298.3321 1136.3431,-261 1066.6821,-245.7886 1050.1652,-236.2635 979.3431,-228 821.2542,-209.5542 420.3941,-235.8329 263.3431,-210 259.1883,-209.3166 254.9182,-208.4083 250.6699,-207.362"/>
<polygon fill="#000000" stroke="#000000" points="251.4284,-203.9414 240.8615,-204.7108 249.6018,-210.699 251.4284,-203.9414"/>
<text text-anchor="middle" x="1610.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- family_relationship -->
<g id="node13" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="678.3431" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="678.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge38" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M700.2031,-174.3526C715.9394,-162.707 738.2123,-148.2986 760.3431,-141 827.463,-118.8642 1024.78,-109.9972 1132.7351,-106.7277"/>
<polygon fill="#000000" stroke="#000000" points="1133.0034,-110.2214 1142.896,-106.4285 1132.7973,-103.2244 1133.0034,-110.2214"/>
<text text-anchor="middle" x="839.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- medical_history -->
<g id="node14" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="881.3431" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="881.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M899.6498,-174.187C912.4958,-162.7797 930.6566,-148.7163 949.3431,-141 981.9772,-127.5243 1071.1927,-117.0149 1135.1155,-110.9156"/>
<polygon fill="#000000" stroke="#000000" points="1135.5156,-114.3935 1145.145,-109.9748 1134.8618,-107.4241 1135.5156,-114.3935"/>
<text text-anchor="middle" x="1017.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- study_arm -->
<g id="node15" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1550.3431" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1550.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge27" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1546.7269,-86.9387C1545.6048,-76.6683 1545.8548,-63.9183 1551.3431,-54 1555.5926,-46.3206 1562.2525,-40.0063 1569.4912,-34.9299"/>
<polygon fill="#000000" stroke="#000000" points="1571.5128,-37.794 1578.1448,-29.5317 1567.8078,-31.8549 1571.5128,-37.794"/>
<text text-anchor="middle" x="1599.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- pathology_file -->
<g id="node16" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="691.3431" cy="-453" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="691.3431" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge19" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M686.7209,-434.7222C685.163,-424.1245 685.311,-411.1154 692.3431,-402 703.3482,-387.7347 748.7439,-377.4122 782.1335,-371.5707"/>
<polygon fill="#000000" stroke="#000000" points="782.7775,-375.0116 792.0589,-369.9022 781.6171,-368.1084 782.7775,-375.0116"/>
<text text-anchor="middle" x="753.3431" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M765.2323,-448.4492C843.2799,-442.8714 956.9396,-432.2441 970.3431,-417 974.7452,-411.9934 971.7271,-408.5214 970.3431,-402 968.5258,-393.4362 965.5617,-392.1414 962.3431,-384 950.406,-353.8052 959.1748,-339.9051 938.3431,-315 932.0905,-307.5248 923.8652,-301.3038 915.4029,-296.2546"/>
<polygon fill="#000000" stroke="#000000" points="917.0227,-293.1512 906.5713,-291.4136 913.6579,-299.2895 917.0227,-293.1512"/>
<text text-anchor="middle" x="1023.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge18" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M687.8237,-434.8397C682.4107,-411.6119 669.8724,-371.5778 644.3431,-348 629.2536,-334.064 361.6417,-244.0016 251.8063,-207.4149"/>
<polygon fill="#000000" stroke="#000000" points="252.587,-203.986 241.9934,-204.1486 250.3762,-210.6277 252.587,-203.986"/>
<text text-anchor="middle" x="665.3431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- diagnosis -->
<g id="node17" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1039.3431" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1039.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1060.1708,-175.1249C1074.0816,-164.4004 1093.1069,-150.751 1111.3431,-141 1124.7408,-133.8363 1139.8795,-127.3863 1154.0318,-121.9916"/>
<polygon fill="#000000" stroke="#000000" points="1155.479,-125.1879 1163.6384,-118.4295 1153.0453,-118.6245 1155.479,-125.1879"/>
<text text-anchor="middle" x="1155.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M234.1987,-177.2238C259.5788,-165.0352 297.9003,-148.5621 333.3431,-141 410.3629,-124.5669 937.4134,-111.0815 1132.7299,-106.5944"/>
<polygon fill="#000000" stroke="#000000" points="1132.9736,-110.0899 1142.891,-106.3623 1132.8136,-103.0917 1132.9736,-110.0899"/>
<text text-anchor="middle" x="373.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M240.8799,-204.6019C248.2231,-206.7589 255.9685,-208.7155 263.3431,-210 442.598,-241.2228 492.3158,-201.5931 672.3431,-228 727.3897,-236.0744 789.2129,-252.8578 829.7963,-264.9696"/>
<polygon fill="#000000" stroke="#000000" points="828.8013,-268.3252 839.3861,-267.8628 830.8232,-261.6235 828.8013,-268.3252"/>
<text text-anchor="middle" x="785.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge23" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M224.7766,-175.169C239.5263,-163.4316 260.8688,-148.5677 282.3431,-141 525.7747,-55.2132 1354.1182,-25.4473 1559.8182,-19.2888"/>
<polygon fill="#000000" stroke="#000000" points="1560.0844,-22.7825 1569.9767,-18.9888 1559.8777,-15.7856 1560.0844,-22.7825"/>
<text text-anchor="middle" x="584.8431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- study_personnel -->
<g id="node20" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="1939.3431" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1939.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge39" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1885.0998,-90.8283C1819.0715,-73.5777 1708.9559,-44.8087 1648.7844,-29.0883"/>
<polygon fill="#000000" stroke="#000000" points="1649.4211,-25.6372 1638.8611,-26.4957 1647.6516,-32.4099 1649.4211,-25.6372"/>
<text text-anchor="middle" x="1861.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- sequencing_file -->
<g id="node21" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1016.3431" cy="-453" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1016.3431" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge15" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M944.9192,-443.7542C919.8738,-438.4249 892.2888,-430.0689 869.3431,-417 857.5586,-410.288 846.7168,-400.0018 838.1635,-390.4208"/>
<polygon fill="#000000" stroke="#000000" points="840.6885,-387.9872 831.5464,-382.6326 835.354,-392.5196 840.6885,-387.9872"/>
<text text-anchor="middle" x="935.8431" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1017.0834,-434.8257C1018.4569,-423.9974 1021.9157,-410.7103 1030.3431,-402 1049.1108,-382.6024 1072.3343,-405.7304 1088.3431,-384 1097.8332,-371.1183 1097.7623,-360.9337 1088.3431,-348 1068.9405,-321.3578 982.0249,-299.8415 925.1032,-288.2806"/>
<polygon fill="#000000" stroke="#000000" points="925.6869,-284.8282 915.1957,-286.3069 924.3192,-291.6933 925.6869,-284.8282"/>
<text text-anchor="middle" x="1162.8431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge13" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1090.6535,-444.7278C1162.5418,-436.3631 1261.5042,-423.7361 1267.3431,-417 1287.345,-393.9246 1269.5487,-377.9272 1233.3431,-348 1120.4272,-254.6645 1069.9239,-257.0875 926.3431,-228 781.89,-198.7358 408.7524,-234.0679 263.3431,-210 259.189,-209.3124 254.9193,-208.4013 250.6714,-207.3531"/>
<polygon fill="#000000" stroke="#000000" points="251.4305,-203.9327 240.8634,-204.6992 249.6021,-210.6897 251.4305,-203.9327"/>
<text text-anchor="middle" x="1277.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- therapeutic_procedure -->
<g id="node22" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="1229.3431" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="1229.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1215.0721,-173.9076C1211.5438,-168.4524 1208.2349,-162.2465 1206.3431,-156 1204.1798,-148.8566 1203.3325,-140.8889 1203.1692,-133.414"/>
<polygon fill="#000000" stroke="#000000" points="1206.6703,-133.3659 1203.3279,-123.3122 1199.6711,-133.2559 1206.6703,-133.3659"/>
<text text-anchor="middle" x="1299.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- clinical_measure_file -->
<g id="node23" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="1909.3431" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="1909.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1829.5126,-179.6747C1788.2699,-172.6859 1742.6274,-163.8041 1723.3431,-156 1712.0304,-151.4218 1711.955,-144.7555 1700.3431,-141 1620.54,-115.1898 1406.8012,-131.3352 1323.3431,-123 1305.6747,-121.2354 1286.6147,-118.6356 1269.0738,-115.9573"/>
<polygon fill="#000000" stroke="#000000" points="1269.3636,-112.4603 1258.9436,-114.3771 1268.2846,-119.3766 1269.3636,-112.4603"/>
<text text-anchor="middle" x="1809.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge26" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1909.3158,-173.8876C1908.262,-162.6551 1904.8908,-148.9047 1895.3431,-141 1856.8773,-109.1534 1710.6522,-153.7997 1671.3431,-123 1645.898,-103.063 1666.3804,-80.8253 1648.3431,-54 1644.7561,-48.6653 1640.1734,-43.6592 1635.361,-39.1744"/>
<polygon fill="#000000" stroke="#000000" points="1637.5781,-36.4646 1627.7196,-32.5838 1633.0063,-41.7655 1637.5781,-36.4646"/>
<text text-anchor="middle" x="1757.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- publication -->
<g id="node24" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="2145.3431" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="2145.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge33" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2125.6305,-87.8245C2110.909,-76.08 2089.7216,-61.3557 2068.3431,-54 1992.5729,-27.9297 1754.988,-20.6341 1653.2906,-18.68"/>
<polygon fill="#000000" stroke="#000000" points="1653.0797,-15.1757 1643.0173,-18.4921 1652.9516,-22.1745 1653.0797,-15.1757"/>
<text text-anchor="middle" x="2148.3431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- synonym -->
<g id="node25" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1950.3431" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1950.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1944.212,-347.8353C1940.1683,-337.5303 1934.1683,-324.7803 1926.3431,-315 1878.8556,-255.6475 1849.0019,-259.5303 1791.3431,-210 1773.6959,-194.8406 1773.1527,-186.199 1753.3431,-174 1733.2322,-161.6154 1724.9215,-165.6022 1703.3431,-156 1690.4449,-150.2604 1688.9439,-144.7854 1675.3431,-141 1599.8867,-119.9989 1401.2666,-130.9155 1323.3431,-123 1305.6778,-121.2055 1286.6187,-118.5958 1269.0778,-115.9177"/>
<polygon fill="#000000" stroke="#000000" points="1269.3672,-112.4206 1258.9475,-114.3385 1268.289,-119.3371 1269.3672,-112.4206"/>
<text text-anchor="middle" x="1877.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1913.7587,-353.0746C1874.3764,-339.3884 1814.1765,-319.1875 1790.3431,-315 1623.2907,-285.6489 1099.4212,-280.2172 928.7116,-279.2212"/>
<polygon fill="#000000" stroke="#000000" points="928.7171,-275.7213 918.6978,-279.1656 928.6781,-282.7212 928.7171,-275.7213"/>
<text text-anchor="middle" x="1882.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge12" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2000.4878,-361.1348C2082.5114,-351.7729 2236.3431,-327.7204 2236.3431,-279 2236.3431,-279 2236.3431,-279 2236.3431,-105 2236.3431,-78.0021 2226.6595,-67.6101 2203.3431,-54 2156.3047,-26.5429 1785.3395,-19.9107 1653.0268,-18.4114"/>
<polygon fill="#000000" stroke="#000000" points="1652.8509,-14.9093 1642.8135,-18.3005 1652.7749,-21.9089 1652.8509,-14.9093"/>
<text text-anchor="middle" x="2278.8431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
</g>
</svg>
</div>
