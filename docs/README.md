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
<svg width="2183pt" height="392pt"
 viewBox="0.00 0.00 2183.02 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 2179.0237,-388 2179.0237,4 -4,4"/>
<!-- synonym -->
<g id="node1" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="290.0237" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="290.0237" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- study -->
<g id="node5" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1160.0237" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1160.0237" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge24" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M241.3351,-272.6081C179.1234,-261.4437 74.5293,-231.823 33.0237,-156 -4.4951,-87.4601 -51.066,-123.8472 157.0237,-54 248.1719,-23.4053 927.7156,-18.8061 1113.308,-18.1195"/>
<polygon fill="#000000" stroke="#000000" points="1113.5625,-21.6188 1123.5502,-18.0838 1113.538,-14.6188 1113.5625,-21.6188"/>
<text text-anchor="middle" x="75.5237" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- sample -->
<g id="node17" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1062.0237" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1062.0237" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M326.6636,-266.2234C343.2907,-259.9519 363,-251.8455 380.0237,-243 390.8531,-237.3731 391.3785,-231.6508 403.0237,-228 531.5803,-187.6972 876.4394,-233.9274 1009.0237,-210 1012.7324,-209.3307 1016.5337,-208.4511 1020.3145,-207.4403"/>
<polygon fill="#000000" stroke="#000000" points="1021.603,-210.709 1030.1968,-204.5124 1019.6145,-203.9974 1021.603,-210.709"/>
<text text-anchor="middle" x="445.5237" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- participant -->
<g id="node21" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1102.0237" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1102.0237" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M313.1373,-262.8166C331.9476,-249.3327 358.9067,-229.2841 381.0237,-210 398.0787,-195.1296 396.753,-184.0548 417.0237,-174 470.0664,-147.6894 490.6864,-166.1261 549.0237,-156 580.8006,-150.4842 588.0934,-145.5446 620.0237,-141 764.5044,-120.4364 935.1294,-111.198 1029.6967,-107.3877"/>
<polygon fill="#000000" stroke="#000000" points="1029.8717,-110.8836 1039.7261,-106.9925 1029.596,-103.889 1029.8717,-110.8836"/>
<text text-anchor="middle" x="459.5237" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- molecular_test -->
<g id="node2" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1765.0237" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1765.0237" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1730.7002,-175.6584C1703.7272,-163.6781 1664.855,-148.2839 1629.0237,-141 1443.7547,-103.3382 1391.9702,-143.4726 1204.0237,-123 1190.7758,-121.5569 1176.6501,-119.4409 1163.265,-117.1625"/>
<polygon fill="#000000" stroke="#000000" points="1163.655,-113.6775 1153.2006,-115.3969 1162.4454,-120.5722 1163.655,-113.6775"/>
<text text-anchor="middle" x="1742.0237" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- pathology_file -->
<g id="node3" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="121.0237" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="121.0237" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pdx -->
<g id="node6" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="546.0237" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="546.0237" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge9" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M122.0625,-347.9451C123.7462,-336.5865 127.912,-322.6725 138.0237,-315 170.4592,-290.3887 464.3526,-306.164 504.0237,-297 507.4513,-296.2082 510.9516,-295.1507 514.3966,-293.9432"/>
<polygon fill="#000000" stroke="#000000" points="515.8181,-297.1454 523.8528,-290.2393 513.2651,-290.6275 515.8181,-297.1454"/>
<text text-anchor="middle" x="199.0237" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- cell_line -->
<g id="node16" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="1660.0237" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="1660.0237" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge7" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M196.1161,-363.0736C331.9437,-357.4585 608.2955,-344.4415 650.0237,-330 661.2071,-326.1296 660.7497,-318.5982 672.0237,-315 769.9542,-283.7448 1495.3636,-312.2478 1597.0237,-297 1602.4375,-296.188 1608.0421,-295.0452 1613.5747,-293.7246"/>
<polygon fill="#000000" stroke="#000000" points="1614.5907,-297.0772 1623.3985,-291.1887 1612.8411,-290.2993 1614.5907,-297.0772"/>
<text text-anchor="middle" x="733.0237" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M116.6861,-347.5809C115.2883,-336.6605 115.8299,-323.3625 124.0237,-315 159.4389,-278.8558 305.0754,-318.1989 351.0237,-297 371.5698,-287.5208 366.6542,-270.8531 387.0237,-261 415.6216,-247.1667 639.369,-230.6793 671.0237,-228 820.9228,-215.3122 861.3044,-238.4556 1009.0237,-210 1012.6736,-209.2969 1016.416,-208.4021 1020.1417,-207.3885"/>
<polygon fill="#000000" stroke="#000000" points="1021.3094,-210.6926 1029.8903,-204.4783 1019.307,-203.9851 1021.3094,-210.6926"/>
<text text-anchor="middle" x="448.0237" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- study_admin -->
<g id="node4" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="224.0237" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="224.0237" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M213.4441,-86.7342C208.6805,-75.8715 205.7637,-62.5803 214.0237,-54 229.7904,-37.6218 925.3238,-22.6561 1113.5027,-18.9015"/>
<polygon fill="#000000" stroke="#000000" points="1113.6949,-22.3985 1123.6235,-18.7006 1113.556,-15.3998 1113.6949,-22.3985"/>
<text text-anchor="middle" x="270.5237" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge32" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M525.5984,-266.3597C521.5493,-264.2893 517.2431,-262.3748 513.0237,-261 434.5264,-235.4223 199.1167,-272.3698 145.0237,-210 109.206,-168.7019 117.2005,-134.0565 145.0237,-87 160.5134,-60.8028 175.6945,-62.1253 205.0237,-54 292.8644,-29.6647 933.5762,-20.5818 1113.2785,-18.4973"/>
<polygon fill="#000000" stroke="#000000" points="1113.5015,-21.9951 1123.4609,-18.381 1113.4215,-14.9955 1113.5015,-21.9951"/>
<text text-anchor="middle" x="147.0237" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge33" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M571.4161,-270.9858C609.2505,-259.4053 682.8558,-238.2593 747.0237,-228 862.2788,-209.5727 894.5852,-232.9593 1009.0237,-210 1012.6681,-209.2688 1016.4066,-208.3543 1020.1298,-207.3276"/>
<polygon fill="#000000" stroke="#000000" points="1021.3063,-210.6287 1029.8742,-204.3964 1019.2899,-203.9254 1021.3063,-210.6287"/>
<text text-anchor="middle" x="771.0237" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- methylation_array_file -->
<g id="node7" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1471.0237" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1471.0237" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge19" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1359.2151,-361.3544C1211.6143,-354.8697 959.7283,-342.4897 868.0237,-330 836.4974,-325.7063 829.3468,-320.5865 798.0237,-315 722.4288,-301.5176 633.3639,-289.7531 583.9367,-283.5852"/>
<polygon fill="#000000" stroke="#000000" points="584.0721,-280.0753 573.7177,-282.3195 583.2116,-287.0223 584.0721,-280.0753"/>
<text text-anchor="middle" x="959.5237" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge17" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1559.7239,-354.3346C1592.8157,-348.4607 1625.4213,-340.3574 1638.0237,-330 1645.1987,-324.1032 1650.0888,-315.4247 1653.3978,-306.8923"/>
<polygon fill="#000000" stroke="#000000" points="1656.8125,-307.7111 1656.5981,-297.1185 1650.16,-305.5328 1656.8125,-307.7111"/>
<text text-anchor="middle" x="1740.5237" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1470.2805,-347.8286C1468.9059,-337.0013 1465.447,-323.7143 1457.0237,-315 1456.6294,-314.5921 1210.3713,-238.0745 1106.9345,-205.9471"/>
<polygon fill="#000000" stroke="#000000" points="1107.9715,-202.6043 1097.3833,-202.9806 1105.8952,-209.2893 1107.9715,-202.6043"/>
<text text-anchor="middle" x="1488.5237" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study_funding -->
<g id="node8" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="1323.0237" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="1323.0237" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge11" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1293.7092,-88.1084C1275.9691,-78.0021 1252.8277,-65.0228 1232.0237,-54 1220.1358,-47.7013 1207.0073,-41.0491 1195.2524,-35.2"/>
<polygon fill="#000000" stroke="#000000" points="1196.6843,-32.0035 1186.1695,-30.7034 1193.5785,-38.2768 1196.6843,-32.0035"/>
<text text-anchor="middle" x="1319.0237" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- clinical_measure_file -->
<g id="node9" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="263.0237" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="263.0237" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge2" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M261.6872,-173.9517C261.911,-162.8912 264.2391,-149.3073 273.0237,-141 334.8749,-82.5091 940.1725,-34.0684 1113.7299,-21.2959"/>
<polygon fill="#000000" stroke="#000000" points="1114.0996,-24.7783 1123.8176,-20.558 1113.5889,-17.7969 1114.0996,-24.7783"/>
<text text-anchor="middle" x="558.0237" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge36" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M267.5834,-173.942C271.5079,-162.4283 278.4249,-148.3383 290.0237,-141 305.5464,-131.1792 833.2687,-113.51 1029.4978,-107.2632"/>
<polygon fill="#000000" stroke="#000000" points="1029.8239,-110.7547 1039.7077,-106.9389 1029.6016,-103.7582 1029.8239,-110.7547"/>
<text text-anchor="middle" x="419.5237" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node10" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="699.0237" cy="-366" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="699.0237" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge13" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M562.1516,-363.7077C443.2185,-360.2564 286.9137,-351.6165 267.0237,-330 262.5096,-325.0941 262.4917,-319.8893 267.0237,-315 284.9768,-295.6317 478.3737,-303.2865 504.0237,-297 507.4404,-296.1626 510.9336,-295.0752 514.3744,-293.8496"/>
<polygon fill="#000000" stroke="#000000" points="515.8065,-297.0472 523.825,-290.1222 513.2382,-290.5354 515.8065,-297.0472"/>
<text text-anchor="middle" x="375.5237" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge15" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M797.5306,-353.3717C813.4,-351.4766 829.6575,-349.6181 845.0237,-348 890.7232,-343.1879 1008.3108,-346.9474 1051.0237,-330 1061.0241,-326.0321 1059.9216,-318.7015 1070.0237,-315 1125.0368,-294.8428 1539.1475,-306.1158 1597.0237,-297 1602.4313,-296.1483 1608.0322,-294.9807 1613.5626,-293.646"/>
<polygon fill="#000000" stroke="#000000" points="1614.585,-296.9967 1623.3842,-291.0955 1612.8254,-290.2214 1614.585,-296.9967"/>
<text text-anchor="middle" x="1178.5237" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M767.5498,-350.2525C777.9357,-345.2522 787.6317,-338.6681 795.0237,-330 815.328,-306.1904 787.4516,-283.6672 809.0237,-261 872.264,-194.5494 921.0825,-236.103 1009.0237,-210 1012.1911,-209.0598 1015.452,-208.0519 1018.7258,-207.0108"/>
<polygon fill="#000000" stroke="#000000" points="1020.0823,-210.2499 1028.5048,-203.8225 1017.9124,-203.5947 1020.0823,-210.2499"/>
<text text-anchor="middle" x="917.5237" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- therapeutic_procedure -->
<g id="node11" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="1981.0237" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="1981.0237" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1936.4059,-175.2067C1902.329,-163.241 1853.9134,-148.0726 1810.0237,-141 1544.0034,-98.1325 1472.0703,-150.4856 1204.0237,-123 1190.6956,-121.6333 1176.4855,-119.5375 1163.0358,-117.2526"/>
<polygon fill="#000000" stroke="#000000" points="1163.3808,-113.7597 1152.9261,-115.4775 1162.1701,-120.6542 1163.3808,-113.7597"/>
<text text-anchor="middle" x="1965.0237" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- radiology_file -->
<g id="node12" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="584.0237" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="584.0237" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M600.7068,-174.3236C612.8849,-162.6648 630.4518,-148.2525 649.0237,-141 683.5226,-127.5279 911.1383,-114.4505 1030.0053,-108.4371"/>
<polygon fill="#000000" stroke="#000000" points="1030.3023,-111.9267 1040.1141,-107.9295 1029.9511,-104.9355 1030.3023,-111.9267"/>
<text text-anchor="middle" x="708.0237" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- exposure -->
<g id="node13" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="729.0237" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="729.0237" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M746.4409,-174.8015C759.303,-163.206 777.8415,-148.6726 797.0237,-141 838.0653,-124.5839 953.887,-114.331 1030.4055,-109.144"/>
<polygon fill="#000000" stroke="#000000" points="1030.718,-112.6311 1040.464,-108.4759 1030.254,-105.6465 1030.718,-112.6311"/>
<text text-anchor="middle" x="840.5237" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- family_relationship -->
<g id="node14" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="900.0237" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="900.0237" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M890.8436,-174.061C886.763,-163.3212 884.3977,-150.0445 892.0237,-141 901.218,-130.0955 975.5638,-119.2627 1033.2163,-112.3737"/>
<polygon fill="#000000" stroke="#000000" points="1033.8797,-115.8199 1043.4027,-111.1763 1033.0625,-108.8677 1033.8797,-115.8199"/>
<text text-anchor="middle" x="971.5237" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- publication -->
<g id="node15" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="1481.0237" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="1481.0237" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge10" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1455.5852,-88.4924C1436.8139,-77.0712 1410.2538,-62.4589 1385.0237,-54 1325.2214,-33.9499 1252.633,-24.9105 1206.3827,-20.9439"/>
<polygon fill="#000000" stroke="#000000" points="1206.6088,-17.4508 1196.3579,-20.1284 1206.0411,-24.4277 1206.6088,-17.4508"/>
<text text-anchor="middle" x="1468.0237" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge28" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1708.3712,-275.0762C1818.8276,-265.6231 2082.1817,-240.1268 2108.0237,-210 2118.4408,-197.8557 2115.3304,-188.2342 2108.0237,-174 2096.5334,-151.6157 2085.8913,-148.964 2062.0237,-141 2018.5365,-126.4894 1275.5393,-147.8644 1237.0237,-123 1208.4644,-104.563 1225.0154,-80.7377 1204.0237,-54 1199.944,-48.8035 1194.9895,-43.8632 1189.8966,-39.4004"/>
<polygon fill="#000000" stroke="#000000" points="1191.8324,-36.4608 1181.8855,-32.8124 1187.3861,-41.8674 1191.8324,-36.4608"/>
<text text-anchor="middle" x="2134.5237" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge29" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1621.8552,-267.5004C1613.6966,-265.2094 1605.1024,-262.9205 1597.0237,-261 1558.9472,-251.9482 1462.8617,-232.8334 1424.0237,-228 1289.7121,-211.2848 1253.184,-234.2354 1120.0237,-210 1115.2198,-209.1257 1110.2558,-207.9786 1105.3469,-206.6861"/>
<polygon fill="#000000" stroke="#000000" points="1105.9925,-203.2312 1095.4169,-203.8695 1104.0823,-209.9655 1105.9925,-203.2312"/>
<text text-anchor="middle" x="1550.5237" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1644.2049,-261.8549C1632.0451,-249.9613 1614.1365,-235.0397 1595.0237,-228 1548.6926,-210.9352 1189.6839,-240.711 1151.0237,-210 1126.1177,-190.2151 1146.7605,-169.1883 1132.0237,-141 1130.1685,-137.4514 1127.9177,-133.9366 1125.4921,-130.5738"/>
<polygon fill="#000000" stroke="#000000" points="1128.1562,-128.2992 1119.228,-122.595 1122.6503,-132.6219 1128.1562,-128.2992"/>
<text text-anchor="middle" x="1191.5237" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1056.8304,-173.736C1054.948,-163.6387 1054.2951,-151.1259 1059.0237,-141 1061.1273,-136.4954 1064.1024,-132.3556 1067.5178,-128.6142"/>
<polygon fill="#000000" stroke="#000000" points="1070.1646,-130.9275 1075.0084,-121.5048 1065.3457,-125.8503 1070.1646,-130.9275"/>
<text text-anchor="middle" x="1095.5237" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_arm -->
<g id="node18" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1622.0237" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1622.0237" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge27" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1596.6834,-88.5408C1577.3219,-76.829 1549.5384,-61.8336 1523.0237,-54 1464.8665,-36.8177 1290.5722,-25.1962 1206.4512,-20.4314"/>
<polygon fill="#000000" stroke="#000000" points="1206.5905,-16.9338 1196.411,-19.8711 1206.2004,-23.9229 1206.5905,-16.9338"/>
<text text-anchor="middle" x="1607.5237" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- cytogenomic_file -->
<g id="node19" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="944.0237" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="944.0237" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;pdx -->
<g id="edge38" class="edge">
<title>cytogenomic_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M880.9436,-353.1813C869.3681,-351.1806 857.3622,-349.3367 846.0237,-348 808.5634,-343.5838 532.9788,-357.3698 507.0237,-330 497.5233,-319.9818 506.3471,-307.7183 517.9868,-297.7279"/>
<polygon fill="#000000" stroke="#000000" points="520.1704,-300.4634 525.878,-291.5374 515.8498,-294.9558 520.1704,-300.4634"/>
<text text-anchor="middle" x="578.5237" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;cell_line -->
<g id="edge40" class="edge">
<title>cytogenomic_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1031.3901,-361.7702C1102.0052,-357.1965 1203.6733,-347.9917 1291.0237,-330 1312.9149,-325.491 1317.0596,-319.1392 1339.0237,-315 1451.9808,-293.7128 1483.8135,-316.8971 1597.0237,-297 1602.3453,-296.0647 1607.8611,-294.8568 1613.3157,-293.5096"/>
<polygon fill="#000000" stroke="#000000" points="1614.2298,-296.8883 1623.0129,-290.9632 1612.4518,-290.1179 1614.2298,-296.8883"/>
<text text-anchor="middle" x="1410.5237" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge39" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M881.2422,-353.1379C854.3438,-344.8505 832.3114,-332.3429 848.0237,-315 875.3109,-284.8809 998.5957,-322.7689 1030.0237,-297 1052.6167,-278.4752 1059.6258,-244.4799 1061.6136,-220.188"/>
<polygon fill="#000000" stroke="#000000" points="1065.1123,-220.3095 1062.2004,-210.1227 1058.1242,-219.902 1065.1123,-220.3095"/>
<text text-anchor="middle" x="1124.5237" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- sequencing_file -->
<g id="node20" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1866.0237" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1866.0237" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge6" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1786.4305,-360.5359C1687.0187,-353.3415 1526.7864,-340.3887 1501.0237,-330 1491.0456,-325.9764 1492.141,-318.6598 1482.0237,-315 1409.3822,-288.723 864.1744,-300.8779 787.0237,-297 715.147,-293.3872 631.3951,-286.5349 583.9496,-282.4061"/>
<polygon fill="#000000" stroke="#000000" points="584.096,-278.9056 573.8285,-281.5186 583.4845,-285.8788 584.096,-278.9056"/>
<text text-anchor="middle" x="1567.5237" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge5" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1859.8152,-347.9932C1855.0327,-336.8041 1847.307,-323.0624 1836.0237,-315 1817.2489,-301.5847 1761.3754,-291.6501 1717.5637,-285.6546"/>
<polygon fill="#000000" stroke="#000000" points="1717.9425,-282.1742 1707.5684,-284.3255 1717.0197,-289.1132 1717.9425,-282.1742"/>
<text text-anchor="middle" x="1915.5237" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1939.6193,-357.4532C1974.1512,-350.3542 2004.1512,-337.6042 1986.0237,-315 1866.5385,-166.0065 1322.0438,-237.3344 1133.0237,-210 1124.792,-208.8096 1116.132,-207.0525 1107.7998,-205.096"/>
<polygon fill="#000000" stroke="#000000" points="1108.3976,-201.6385 1097.8498,-202.6352 1106.717,-208.4337 1108.3976,-201.6385"/>
<text text-anchor="middle" x="2033.5237" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge34" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1098.3471,-86.905C1097.205,-76.6233 1097.455,-63.8733 1103.0237,-54 1107.4871,-46.0865 1114.4845,-39.6621 1122.0687,-34.5514"/>
<polygon fill="#000000" stroke="#000000" points="1124.3328,-37.276 1131.125,-29.1448 1120.7446,-31.2657 1124.3328,-37.276"/>
<text text-anchor="middle" x="1153.5237" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- follow_up -->
<g id="node22" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="1296.0237" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="1296.0237" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1263.1143,-177.2416C1230.6642,-162.6893 1180.8929,-140.3692 1145.2646,-124.3915"/>
<polygon fill="#000000" stroke="#000000" points="1146.6311,-121.1685 1136.0744,-120.2702 1143.7667,-127.5557 1146.6311,-121.1685"/>
<text text-anchor="middle" x="1255.0237" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- study_personnel -->
<g id="node23" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="1787.0237" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1787.0237" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge23" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1753.7221,-88.3054C1728.6277,-76.5552 1693.0141,-61.6156 1660.0237,-54 1574.5711,-34.2738 1313.7756,-23.2949 1206.6802,-19.5163"/>
<polygon fill="#000000" stroke="#000000" points="1206.6205,-16.0122 1196.5049,-19.1628 1206.3773,-23.008 1206.6205,-16.0122"/>
<text text-anchor="middle" x="1775.5237" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- diagnosis -->
<g id="node24" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1424.0237" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1424.0237" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1393.6509,-176.8283C1369.8042,-165.4769 1335.4847,-150.3582 1304.0237,-141 1302.3166,-140.4922 1223.8428,-126.5577 1165.224,-116.1775"/>
<polygon fill="#000000" stroke="#000000" points="1165.7256,-112.712 1155.2685,-114.415 1164.5052,-119.6048 1165.7256,-112.712"/>
<text text-anchor="middle" x="1388.5237" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- medical_history -->
<g id="node25" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1582.0237" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1582.0237" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge37" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1544.6381,-175.8055C1515.8038,-164.0687 1474.6251,-148.9223 1437.0237,-141 1335.3909,-119.5868 1307.0659,-136.0405 1204.0237,-123 1190.945,-121.3448 1176.992,-119.1614 1163.738,-116.8881"/>
<polygon fill="#000000" stroke="#000000" points="1164.2192,-113.4192 1153.765,-115.1394 1163.0102,-120.314 1164.2192,-113.4192"/>
<text text-anchor="middle" x="1557.0237" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
</g>
</svg>
</div>
