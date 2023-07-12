<link rel='stylesheet' href="assets/style.css">
<link rel='stylesheet' href="https://unpkg.com/leaflet@1.5.1/dist/leaflet.css" integrity="sha512-xwE/Az9zrjBIphAcBb3F6JVqxf46+CDLwfLMHloNu6KEQCAWi6HcDUbeOfBIptF7tcCzusKFjFw2yuvEpDL9wQ==" crossorigin="">
<script type="text/javascript" src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
<script type="text/javascript"  src="https://unpkg.com/leaflet@1.5.1/dist/leaflet.js"></script>
<script type="text/javascript" src="assets/actions.js"></script>

![Build Status](https://github.com/CBIIT/ccdi-model/actions/workflows/model-test-and-deploy.yml/badge.svg)

# Children's Cancer Data Initiative Draft Model

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
<svg width="2604pt" height="392pt"
 viewBox="0.00 0.00 2603.52 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 2599.5223,-388 2599.5223,4 -4,4"/>
<!-- diagnosis -->
<g id="node1" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1009.5223" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1009.5223" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- participant -->
<g id="node4" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1156.5223" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1156.5223" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1004.7764,-173.6249C1003.1747,-162.9928 1003.3201,-149.9815 1010.5223,-141 1031.6975,-114.5937 1051.6591,-131.1047 1084.5223,-123 1089.4012,-121.7968 1094.4645,-120.5424 1099.5429,-119.2804"/>
<polygon fill="#000000" stroke="#000000" points="1100.4248,-122.6678 1109.283,-116.8555 1098.7336,-115.8751 1100.4248,-122.6678"/>
<text text-anchor="middle" x="1055.0223" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- study_arm -->
<g id="node2" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="493.5223" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="493.5223" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study -->
<g id="node18" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1005.5223" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1005.5223" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge3" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M518.8357,-88.4485C538.1834,-76.6896 565.9615,-61.6757 592.5223,-54 660.1823,-34.4473 865.7636,-23.7504 958.8466,-19.7963"/>
<polygon fill="#000000" stroke="#000000" points="959.2476,-23.2827 969.0931,-19.3691 958.9559,-16.2888 959.2476,-23.2827"/>
<text text-anchor="middle" x="641.0223" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- study_funding -->
<g id="node3" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="648.5223" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="648.5223" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge31" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M667.7549,-87.3668C681.438,-75.8847 700.8213,-61.6634 720.5223,-54 762.9642,-37.4908 889.891,-26.2155 959.1641,-21.1083"/>
<polygon fill="#000000" stroke="#000000" points="959.6362,-24.5834 969.3574,-20.3706 959.1309,-17.6016 959.6362,-24.5834"/>
<text text-anchor="middle" x="782.5223" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge13" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1148.5058,-87.0987C1142.734,-76.0969 1133.9543,-62.5231 1122.5223,-54 1101.6695,-38.4532 1074.0137,-29.5435 1050.8258,-24.4781"/>
<polygon fill="#000000" stroke="#000000" points="1051.3557,-21.0146 1040.8617,-22.4728 1049.9746,-27.877 1051.3557,-21.0146"/>
<text text-anchor="middle" x="1187.0223" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- pathology_file -->
<g id="node5" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1326.5223" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1326.5223" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pdx -->
<g id="node12" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1469.5223" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1469.5223" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge9" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1320.7574,-347.9982C1318.5096,-337.2349 1318.0089,-323.9554 1325.5223,-315 1355.1098,-279.734 1383.4079,-310.1539 1427.5223,-297 1430.7153,-296.0479 1433.9911,-294.9238 1437.2366,-293.7096"/>
<polygon fill="#000000" stroke="#000000" points="1438.795,-296.8554 1446.7689,-289.8792 1436.185,-290.3602 1438.795,-296.8554"/>
<text text-anchor="middle" x="1386.5223" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- cell_line -->
<g id="node20" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="1942.5223" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="1942.5223" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge7" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1402.735,-364.9308C1519.3735,-362.5186 1736.3403,-354.7522 1809.5223,-330 1821.083,-326.0899 1821.5179,-320.2764 1832.5223,-315 1851.4233,-305.9375 1873.1854,-298.283 1892.3385,-292.3939"/>
<polygon fill="#000000" stroke="#000000" points="1893.5104,-295.6967 1902.0876,-289.4771 1891.504,-288.9904 1893.5104,-295.6967"/>
<text text-anchor="middle" x="1893.5223" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- sample -->
<g id="node22" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1247.5223" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1247.5223" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1270.8417,-353.6716C1261.0909,-351.6664 1251.0264,-349.6943 1241.5223,-348 1214.1102,-343.1132 1135.7423,-351.0557 1117.5223,-330 1113.16,-324.9587 1113.0849,-319.9753 1117.5223,-315 1140.8972,-288.7921 1248.2218,-320.2706 1274.5223,-297 1297.8936,-276.3212 1300.2182,-256.5069 1287.5223,-228 1285.3451,-223.1112 1282.1395,-218.6079 1278.4748,-214.5622"/>
<polygon fill="#000000" stroke="#000000" points="1280.6393,-211.7871 1271.0113,-207.3653 1275.7803,-216.8261 1280.6393,-211.7871"/>
<text text-anchor="middle" x="1355.5223" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- study_personnel -->
<g id="node6" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="830.5223" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="830.5223" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge6" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M837.6787,-86.9027C842.9559,-75.8226 851.1924,-62.2353 862.5223,-54 878.0719,-42.6976 924.5882,-32.2671 960.3886,-25.575"/>
<polygon fill="#000000" stroke="#000000" points="961.4277,-28.9433 970.6371,-23.7053 960.1713,-22.057 961.4277,-28.9433"/>
<text text-anchor="middle" x="932.0223" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- methylation_array_file -->
<g id="node7" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1116.5223" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1116.5223" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge16" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1117.2538,-347.7631C1118.7456,-336.4796 1122.6555,-322.7191 1132.5223,-315 1158.3866,-294.7658 1395.5703,-304.5797 1427.5223,-297 1430.9452,-296.188 1434.4424,-295.1173 1437.8856,-293.9017"/>
<polygon fill="#000000" stroke="#000000" points="1439.3118,-297.1019 1447.3393,-290.1874 1436.752,-290.5867 1439.3118,-297.1019"/>
<text text-anchor="middle" x="1224.0223" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge17" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1197.7499,-353.1815C1212.2967,-351.2062 1227.337,-349.371 1241.5223,-348 1321.6926,-340.2516 1528.1129,-358.2971 1603.5223,-330 1613.5954,-326.2201 1612.572,-319.092 1622.5223,-315 1646.0916,-305.3074 1798.4255,-291.1588 1884.14,-283.8191"/>
<polygon fill="#000000" stroke="#000000" points="1884.5825,-287.2942 1894.2496,-282.9585 1883.9887,-280.3194 1884.5825,-287.2942"/>
<text text-anchor="middle" x="1714.0223" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1013.9266,-357.593C931.2474,-348.4374 824.4743,-330.4049 797.5223,-297 787.4755,-284.5477 786.9636,-273.0214 797.5223,-261 801.1455,-256.8749 1184.1586,-211.1721 1189.5223,-210 1194.1703,-208.9843 1198.9817,-207.7674 1203.7547,-206.4518"/>
<polygon fill="#000000" stroke="#000000" points="1204.8033,-209.792 1213.4329,-203.6455 1202.8538,-203.0689 1204.8033,-209.792"/>
<text text-anchor="middle" x="889.0223" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- sequencing_file -->
<g id="node8" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2208.5223" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="2208.5223" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge19" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2125.1304,-364.946C1936.7775,-362.1606 1493.0196,-353.1625 1470.5223,-330 1464.6443,-323.9482 1463.0026,-315.3379 1463.2583,-306.9114"/>
<polygon fill="#000000" stroke="#000000" points="1466.7442,-307.2302 1464.3539,-296.9085 1459.7858,-306.4679 1466.7442,-307.2302"/>
<text text-anchor="middle" x="1537.0223" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge24" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2134.2729,-357.8583C2077.8991,-351.0378 2005.4709,-340.7198 1977.5223,-330 1966.1277,-325.6295 1966.1367,-318.7477 1954.5223,-315 1872.378,-288.4938 1652.268,-306.8974 1566.5223,-297 1546.3738,-294.6743 1524.1102,-290.6487 1505.9996,-286.9935"/>
<polygon fill="#000000" stroke="#000000" points="1506.6363,-283.5512 1496.1352,-284.9572 1505.2211,-290.4067 1506.6363,-283.5512"/>
<text text-anchor="middle" x="2086.0223" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge20" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2287.0241,-359.8704C2356.3644,-353.6385 2448.2049,-343.0565 2459.5223,-330 2463.8889,-324.9624 2464.0697,-319.875 2459.5223,-315 2444.1171,-298.4847 2134.7617,-285.7279 2002.0966,-280.9953"/>
<polygon fill="#000000" stroke="#000000" points="2001.8339,-277.4839 1991.7165,-280.6285 2001.5867,-284.4795 2001.8339,-277.4839"/>
<text text-anchor="middle" x="2529.0223" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge23" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2219.3186,-348.0174C2224.242,-337.2613 2227.4131,-323.9826 2219.5223,-315 2205.3752,-298.8953 2078.6341,-287.8637 2001.5782,-282.58"/>
<polygon fill="#000000" stroke="#000000" points="2001.7267,-279.0821 1991.5144,-281.9031 2001.2569,-286.0664 2001.7267,-279.0821"/>
<text text-anchor="middle" x="2332.0223" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2208.5985,-347.7599C2207.5873,-336.4751 2204.2246,-322.7143 2194.5223,-315 2175.2425,-299.6705 1775.9589,-300.0917 1751.5223,-297 1606.3199,-278.629 1573.6503,-253.4632 1429.5223,-228 1372.5164,-217.9287 1356.8466,-223.3675 1300.5223,-210 1297.1097,-209.1901 1293.6058,-208.2507 1290.1042,-207.2345"/>
<polygon fill="#000000" stroke="#000000" points="1290.9074,-203.8195 1280.3198,-204.2109 1288.8406,-210.5074 1290.9074,-203.8195"/>
<text text-anchor="middle" x="1818.0223" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- follow_up -->
<g id="node9" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="1364.5223" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="1364.5223" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1342.1109,-175.43C1326.3715,-164.4225 1304.4705,-150.3315 1283.5223,-141 1262.373,-131.5789 1238.1375,-123.987 1216.5454,-118.2479"/>
<polygon fill="#000000" stroke="#000000" points="1217.3886,-114.8509 1206.8313,-115.7414 1215.6397,-121.6289 1217.3886,-114.8509"/>
<text text-anchor="middle" x="1355.5223" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- study_admin -->
<g id="node10" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1005.5223" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1005.5223" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1005.5223,-86.9735C1005.5223,-75.1918 1005.5223,-59.5607 1005.5223,-46.1581"/>
<polygon fill="#000000" stroke="#000000" points="1009.0224,-46.0033 1005.5223,-36.0034 1002.0224,-46.0034 1009.0224,-46.0033"/>
<text text-anchor="middle" x="1062.0223" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node11" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1127.5223" cy="-279" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="1127.5223" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1087.9459,-261.5728C1072.2061,-252.241 1060.0451,-240.1812 1070.5223,-228 1087.9626,-207.7233 1163.4543,-215.9806 1189.5223,-210 1194.1595,-208.9361 1198.964,-207.688 1203.7327,-206.3537"/>
<polygon fill="#000000" stroke="#000000" points="1204.7902,-209.6911 1213.406,-203.5252 1202.8256,-202.9725 1204.7902,-209.6911"/>
<text text-anchor="middle" x="1179.0223" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge29" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1446.0434,-268.7472C1440.0256,-266.1717 1433.5501,-263.4459 1427.5223,-261 1380.6931,-241.9979 1326.4802,-221.4052 1289.8883,-207.71"/>
<polygon fill="#000000" stroke="#000000" points="1291.1111,-204.4306 1280.5185,-204.2098 1288.6614,-210.988 1291.1111,-204.4306"/>
<text text-anchor="middle" x="1401.5223" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- medical_history -->
<g id="node13" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1639.5223" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1639.5223" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1576.5956,-179.8381C1532.4543,-171.1081 1479.5886,-160.1766 1469.5223,-156 1458.2501,-151.323 1457.9835,-145.1928 1446.5223,-141 1407.5585,-126.746 1300.0081,-116.0109 1227.4148,-110.1166"/>
<polygon fill="#000000" stroke="#000000" points="1227.6615,-106.6252 1217.4144,-109.3171 1227.1037,-113.6029 1227.6615,-106.6252"/>
<text text-anchor="middle" x="1537.5223" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- therapeutic_procedure -->
<g id="node14" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="134.5223" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="134.5223" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M153.8283,-174.2031C168.0595,-162.3256 188.5211,-147.7012 209.5223,-141 302.1633,-111.4397 988.1354,-135.8734 1084.5223,-123 1090.3313,-122.2242 1096.3489,-121.1558 1102.3177,-119.9233"/>
<polygon fill="#000000" stroke="#000000" points="1103.2657,-123.2983 1112.2712,-117.717 1101.7507,-116.4641 1103.2657,-123.2983"/>
<text text-anchor="middle" x="302.5223" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- radiology_file -->
<g id="node15" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="343.5223" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="343.5223" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M366.5536,-174.737C383.9509,-162.7848 408.9549,-147.8415 433.5223,-141 572.9394,-102.1756 941.1428,-142.6661 1084.5223,-123 1090.2467,-122.2148 1096.1749,-121.1524 1102.0599,-119.934"/>
<polygon fill="#000000" stroke="#000000" points="1102.8738,-123.3386 1111.8794,-117.7575 1101.359,-116.5045 1102.8738,-123.3386"/>
<text text-anchor="middle" x="492.5223" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- molecular_test -->
<g id="node16" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="514.5223" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="514.5223" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M531.1513,-174.3197C543.505,-162.4972 561.4563,-147.8905 580.5223,-141 633.2221,-121.9543 1029.0375,-130.8382 1084.5223,-123 1090.2435,-122.1918 1096.1696,-121.1144 1102.0533,-119.8869"/>
<polygon fill="#000000" stroke="#000000" points="1102.8714,-123.2906 1111.8715,-117.7005 1101.3498,-116.4579 1102.8714,-123.2906"/>
<text text-anchor="middle" x="644.5223" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- clinical_measure_file -->
<g id="node17" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="1882.5223" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="1882.5223" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1794.2975,-181.4055C1727.2702,-173.0347 1644.027,-161.8245 1628.5223,-156 1617.0978,-151.7083 1617.072,-144.9426 1605.5223,-141 1537.9492,-117.9334 1338.3171,-109.4568 1229.4087,-106.4924"/>
<polygon fill="#000000" stroke="#000000" points="1229.2486,-102.9871 1219.1599,-106.2225 1229.0643,-109.9847 1229.2486,-102.9871"/>
<text text-anchor="middle" x="1758.0223" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge10" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1890.3313,-173.9303C1893.6612,-163.1413 1895.2315,-149.8589 1887.5223,-141 1831.9483,-77.138 1225.8467,-32.5169 1051.9262,-20.9597"/>
<polygon fill="#000000" stroke="#000000" points="1052.0256,-17.4588 1041.8169,-20.293 1051.5648,-24.4436 1052.0256,-17.4588"/>
<text text-anchor="middle" x="1938.5223" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- exposure -->
<g id="node19" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="665.5223" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="665.5223" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M684.5782,-174.9115C699.0741,-163.0461 720.1164,-148.1349 741.5223,-141 813.933,-116.8646 1009.0376,-134.3084 1084.5223,-123 1090.2366,-122.144 1096.1582,-121.0355 1102.0391,-119.7893"/>
<polygon fill="#000000" stroke="#000000" points="1102.8657,-123.1909 1111.8543,-117.5823 1101.33,-116.3614 1102.8657,-123.1909"/>
<text text-anchor="middle" x="785.0223" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1894.7651,-274.0164C1781.2442,-261.8995 1501.9274,-230.396 1464.5223,-210 1428.8425,-190.5448 1440.1944,-160.4694 1404.5223,-141 1374.8587,-124.8099 1289.8695,-115.0122 1227.6264,-109.8107"/>
<polygon fill="#000000" stroke="#000000" points="1227.7067,-106.3058 1217.4561,-108.9844 1227.1398,-113.2828 1227.7067,-106.3058"/>
<text text-anchor="middle" x="1505.0223" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge5" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1961.0827,-262.3082C1999.0577,-226.2282 2078.0332,-139.9628 2028.5223,-87 1994.7457,-50.8684 1248.3372,-25.4607 1052.3214,-19.395"/>
<polygon fill="#000000" stroke="#000000" points="1052.1717,-15.8889 1042.0689,-19.0799 1051.9566,-22.8856 1052.1717,-15.8889"/>
<text text-anchor="middle" x="2083.0223" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- publication -->
<g id="node21" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="2141.5223" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="2141.5223" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge15" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2122.2154,-87.7925C2107.5286,-75.8679 2086.2094,-60.9348 2064.5223,-54 1967.3653,-22.9325 1243.6513,-18.6754 1051.9861,-18.0924"/>
<polygon fill="#000000" stroke="#000000" points="1051.9643,-14.5925 1041.9544,-18.0638 1051.9443,-21.5924 1051.9643,-14.5925"/>
<text text-anchor="middle" x="2144.5223" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1229.9766,-175.2255C1216.4304,-162.2748 1197.487,-144.1641 1182.2308,-129.5785"/>
<polygon fill="#000000" stroke="#000000" points="1184.2839,-126.699 1174.637,-122.3185 1179.4466,-131.7588 1184.2839,-126.699"/>
<text text-anchor="middle" x="1243.0223" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- synonym -->
<g id="node23" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="700.5223" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="700.5223" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M728.1617,-263.5952C751.0811,-251.631 784.9126,-235.8049 816.5223,-228 872.1041,-214.2761 1022.898,-236.7368 1073.5223,-210 1090.5796,-200.9913 1120.4238,-159.5019 1139.294,-131.4524"/>
<polygon fill="#000000" stroke="#000000" points="1142.3756,-133.1393 1145.0049,-122.8759 1136.5492,-129.2595 1142.3756,-133.1393"/>
<text text-anchor="middle" x="1150.0223" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge32" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M648.5999,-277.7586C494.9275,-273.5535 50.4044,-257.3637 7.5223,-210 -3.2163,-198.1391 -1.5151,-187.2032 7.5223,-174 61.1222,-95.6931 -96.8938,-140.96 552.5223,-54 700.2499,-34.2186 876.6435,-24.0278 958.9419,-20.0454"/>
<polygon fill="#000000" stroke="#000000" points="959.1532,-23.5394 968.9756,-19.5682 958.8206,-16.5473 959.1532,-23.5394"/>
<text text-anchor="middle" x="65.0223" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge33" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M740.7927,-267.4158C767.6945,-259.4401 800.4554,-249.2022 813.5223,-243 824.5475,-237.767 824.9166,-231.7743 836.5223,-228 911.2179,-203.708 1112.1885,-223.7478 1189.5223,-210 1194.3298,-209.1454 1199.296,-208.0109 1204.2063,-206.7257"/>
<polygon fill="#000000" stroke="#000000" points="1205.4674,-210.0064 1214.1378,-203.9176 1203.5627,-203.2705 1205.4674,-210.0064"/>
<text text-anchor="middle" x="879.0223" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- family_relationship -->
<g id="node24" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="836.5223" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="836.5223" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M832.6349,-174.012C831.387,-162.9755 832.0876,-149.3958 840.5223,-141 859.7894,-121.822 1057.6818,-127.3125 1084.5223,-123 1090.0085,-122.1185 1095.6895,-121.0233 1101.344,-119.8112"/>
<polygon fill="#000000" stroke="#000000" points="1102.4653,-123.146 1111.4457,-117.5244 1100.9197,-116.3188 1102.4653,-123.146"/>
<text text-anchor="middle" x="920.0223" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
</g>
</svg>
</div>
