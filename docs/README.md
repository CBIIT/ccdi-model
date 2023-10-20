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
<svg width="2541pt" height="392pt"
 viewBox="0.00 0.00 2541.28 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 2537.2849,-388 2537.2849,4 -4,4"/>
<!-- pathology_file -->
<g id="node1" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1789.1926" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1789.1926" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- cell_line -->
<g id="node10" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="657.1926" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="657.1926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge39" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1725.4922,-356.0456C1698.6841,-350.4607 1667.6395,-342.1109 1641.1926,-330 1630.7643,-325.2245 1631.0479,-318.7038 1620.1926,-315 1609.457,-311.3371 925.2231,-288.0251 716.7936,-281.0005"/>
<polygon fill="#000000" stroke="#000000" points="716.7621,-277.4976 706.65,-280.6589 716.5264,-284.4936 716.7621,-277.4976"/>
<text text-anchor="middle" x="1702.1926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- sample -->
<g id="node15" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1252.1926" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1252.1926" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge37" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1850.2312,-355.2593C1879.304,-348.9785 1909.9456,-340.2669 1920.1926,-330 1942.0397,-308.1105 1950.1513,-283.7415 1929.1926,-261 1882.0491,-209.8462 1373.308,-224.1253 1305.1926,-210 1301.6036,-209.2557 1297.9217,-208.34 1294.2521,-207.3196"/>
<polygon fill="#000000" stroke="#000000" points="1295.2243,-203.9571 1284.6395,-204.4195 1293.2023,-210.6588 1295.2243,-203.9571"/>
<text text-anchor="middle" x="2002.1926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pdx -->
<g id="node19" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1468.1926" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1468.1926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge38" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1786.0833,-347.8118C1783.1688,-336.5483 1777.6211,-322.7918 1767.1926,-315 1746.666,-299.6633 1582.254,-286.7055 1506.3505,-281.4762"/>
<polygon fill="#000000" stroke="#000000" points="1506.4661,-277.9761 1496.2518,-280.7902 1505.9916,-284.96 1506.4661,-277.9761"/>
<text text-anchor="middle" x="1840.1926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- publication -->
<g id="node2" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="1707.1926" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="1707.1926" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- study -->
<g id="node24" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1868.1926" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1868.1926" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge35" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1702.3904,-86.5794C1700.7688,-75.9311 1700.913,-62.9189 1708.1926,-54 1722.4131,-36.5773 1780.0107,-26.9485 1822.0352,-22.1292"/>
<polygon fill="#000000" stroke="#000000" points="1822.5182,-25.5973 1832.0796,-21.0335 1821.759,-18.6386 1822.5182,-25.5973"/>
<text text-anchor="middle" x="1759.1926" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- methylation_array_file -->
<g id="node3" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="395.1926" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="395.1926" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge14" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M390.2027,-347.8444C388.403,-337.0231 388.4262,-323.7368 396.1926,-315 397.8899,-313.0906 524.431,-296.3006 600.6701,-286.3383"/>
<polygon fill="#000000" stroke="#000000" points="601.1561,-289.8046 610.6189,-285.0397 600.25,-282.8635 601.1561,-289.8046"/>
<text text-anchor="middle" x="487.6926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M292.0299,-357.7306C200.9782,-349.9228 81.5398,-338.2173 74.1926,-330 69.749,-325.0302 69.8618,-320.0683 74.1926,-315 80.4406,-307.6881 406.6338,-262.0621 416.1926,-261 503.2845,-251.3231 1117.4604,-228.1279 1203.1926,-210 1205.9773,-209.4112 1208.8162,-208.6959 1211.6542,-207.8941"/>
<polygon fill="#000000" stroke="#000000" points="1212.7257,-211.2262 1221.2189,-204.8925 1210.6297,-204.5474 1212.7257,-211.2262"/>
<text text-anchor="middle" x="507.6926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge13" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M509.9137,-363.6541C615.8931,-360.1554 764.8754,-351.4746 819.1926,-330 829.1979,-326.0444 828.084,-318.6836 838.1926,-315 899.6061,-292.6209 1362.3721,-311.1206 1426.1926,-297 1429.6274,-296.24 1433.1324,-295.2033 1436.5803,-294.0084"/>
<polygon fill="#000000" stroke="#000000" points="1437.9942,-297.2138 1446.0402,-290.3209 1435.4518,-290.6918 1437.9942,-297.2138"/>
<text text-anchor="middle" x="929.6926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node4" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="187.1926" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="187.1926" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- participant -->
<g id="node11" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1252.1926" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1252.1926" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M189.6604,-173.7863C192.2404,-162.3607 197.4988,-148.4317 208.1926,-141 247.9775,-113.3515 948.9342,-106.7767 1179.4091,-105.3591"/>
<polygon fill="#000000" stroke="#000000" points="1179.7196,-108.8574 1189.6984,-105.2973 1179.6775,-101.8575 1179.7196,-108.8574"/>
<text text-anchor="middle" x="337.6926" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge28" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M183.7036,-173.9644C182.6904,-162.909 183.6604,-149.326 192.1926,-141 252.239,-82.4052 1557.8225,-29.7926 1821.8761,-19.7289"/>
<polygon fill="#000000" stroke="#000000" points="1822.0361,-23.2255 1831.8961,-19.3485 1821.7704,-16.2305 1822.0361,-23.2255"/>
<text text-anchor="middle" x="646.1926" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- follow_up -->
<g id="node5" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="1369.1926" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="1369.1926" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1358.3146,-174.1996C1351.0925,-163.512 1340.8211,-150.2414 1329.1926,-141 1320.6128,-134.1814 1310.5308,-128.2893 1300.5403,-123.3599"/>
<polygon fill="#000000" stroke="#000000" points="1301.978,-120.1685 1291.4367,-119.1046 1299.0138,-126.5099 1301.978,-120.1685"/>
<text text-anchor="middle" x="1389.1926" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- sequencing_file -->
<g id="node6" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="83.1926" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="83.1926" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge23" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M77.9156,-347.5767C76.0079,-336.6547 76.0183,-323.3565 84.1926,-315 100.9897,-297.8286 492.2571,-299.0227 516.1926,-297 544.3051,-294.6243 575.4288,-290.7806 601.2675,-287.254"/>
<polygon fill="#000000" stroke="#000000" points="601.8332,-290.7092 611.2585,-285.8705 600.873,-283.7753 601.8332,-290.7092"/>
<text text-anchor="middle" x="150.6926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M64.7034,-348.2981C43.1378,-325.5659 13.3008,-286.067 37.1926,-261 89.9184,-205.6808 647.8412,-231.2683 724.1926,-228 830.6147,-223.4446 1098.6878,-230.6193 1203.1926,-210 1205.9851,-209.449 1208.8298,-208.7624 1211.672,-207.9815"/>
<polygon fill="#000000" stroke="#000000" points="1212.7241,-211.3198 1221.2459,-205.0246 1210.6583,-204.6315 1212.7241,-211.3198"/>
<text text-anchor="middle" x="103.6926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge22" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M139.8027,-352.6963C163.8951,-346.5456 192.1564,-338.6785 217.1926,-330 233.1831,-324.4571 235.6409,-318.5298 252.1926,-315 379.7833,-287.7902 1298.602,-324.2098 1426.1926,-297 1429.6331,-296.2663 1433.1418,-295.2467 1436.592,-294.0622"/>
<polygon fill="#000000" stroke="#000000" points="1437.9996,-297.2704 1446.0548,-290.3882 1435.466,-290.7449 1437.9996,-297.2704"/>
<text text-anchor="middle" x="318.6926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- exposure -->
<g id="node7" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1496.1926" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1496.1926" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1481.172,-174.6783C1470.3603,-163.3352 1454.8039,-149.1521 1438.1926,-141 1417.4673,-130.8289 1363.5402,-120.9873 1319.0574,-114.1724"/>
<polygon fill="#000000" stroke="#000000" points="1319.555,-110.7079 1309.1451,-112.6792 1318.5122,-117.6298 1319.555,-110.7079"/>
<text text-anchor="middle" x="1502.6926" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- radiology_file -->
<g id="node8" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1641.1926" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1641.1926" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1616.919,-174.9218C1599.2517,-163.383 1574.2957,-148.8679 1550.1926,-141 1509.3249,-127.6596 1397.355,-116.5615 1322.9076,-110.3565"/>
<polygon fill="#000000" stroke="#000000" points="1322.9164,-106.8455 1312.6631,-109.5138 1322.3424,-113.822 1322.9164,-106.8455"/>
<text text-anchor="middle" x="1643.1926" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- cytogenomic_file -->
<g id="node9" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1478.1926" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1478.1926" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;cell_line -->
<g id="edge25" class="edge">
<title>cytogenomic_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1407.3388,-354.9294C1389.3807,-352.3848 1370.1035,-349.8782 1352.1926,-348 1233.4641,-335.5499 1202.0848,-348.7851 1084.1926,-330 1057.4733,-325.7425 1051.844,-319.6638 1025.1926,-315 917.3112,-296.1215 789.7776,-286.4166 716.7011,-282.0428"/>
<polygon fill="#000000" stroke="#000000" points="716.5106,-278.5257 706.3233,-281.4357 716.1018,-285.5138 716.5106,-278.5257"/>
<text text-anchor="middle" x="1155.6926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge24" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1561.6953,-359.3105C1685.579,-349.3377 1903.751,-331.5682 1905.1926,-330 1909.7043,-325.0919 1909.5399,-320.0543 1905.1926,-315 1887.7523,-294.7233 1812.5488,-301.5455 1786.1926,-297 1627.3706,-269.6088 1589.111,-254.8267 1430.1926,-228 1374.847,-218.6572 1359.7758,-223.0805 1305.1926,-210 1301.7818,-209.1826 1298.2791,-208.2379 1294.7784,-207.218"/>
<polygon fill="#000000" stroke="#000000" points="1295.5834,-203.8033 1284.9956,-204.188 1293.5123,-210.49 1295.5834,-203.8033"/>
<text text-anchor="middle" x="1857.6926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;pdx -->
<g id="edge26" class="edge">
<title>cytogenomic_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1476.1206,-347.9735C1474.7664,-336.1918 1472.9697,-320.5607 1471.4292,-307.1581"/>
<polygon fill="#000000" stroke="#000000" points="1474.8811,-306.5383 1470.262,-297.0034 1467.9269,-307.3376 1474.8811,-306.5383"/>
<text text-anchor="middle" x="1544.6926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M704.1418,-273.0346C807.636,-259.6473 1048.8822,-227.0538 1082.1926,-210 1102.3339,-199.6884 1099.9151,-187.3392 1118.1926,-174 1145.7973,-153.8537 1180.1118,-136.3048 1207.1054,-123.9466"/>
<polygon fill="#000000" stroke="#000000" points="1208.6433,-127.0926 1216.3251,-119.796 1205.7697,-120.7096 1208.6433,-127.0926"/>
<text text-anchor="middle" x="1158.6926" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M705.8083,-275.5882C800.6151,-268.3127 1016.4737,-248.6895 1194.1926,-210 1198.8414,-208.988 1203.6534,-207.7734 1208.4266,-206.4592"/>
<polygon fill="#000000" stroke="#000000" points="1209.4745,-209.7997 1218.1052,-203.6547 1207.5262,-203.0762 1209.4745,-209.7997"/>
<text text-anchor="middle" x="1132.6926" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge7" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M622.3632,-266.1122C616.0512,-264.1443 609.4769,-262.3295 603.1926,-261 486.5673,-236.327 149.3774,-298.2078 69.1926,-210 58.4302,-198.1607 63.3013,-188.8759 69.1926,-174 102.3521,-90.2703 163.914,-104.8074 252.1926,-87 409.417,-55.285 1573.1141,-25.2216 1821.5962,-19.1221"/>
<polygon fill="#000000" stroke="#000000" points="1821.8199,-22.6177 1831.7313,-18.8741 1821.6486,-15.6198 1821.8199,-22.6177"/>
<text text-anchor="middle" x="127.6926" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge4" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1307.5634,-96.5194C1375.5088,-86.1756 1494.2516,-68.3019 1596.1926,-54 1675.7397,-42.8399 1768.512,-30.7618 1822.5699,-23.8175"/>
<polygon fill="#000000" stroke="#000000" points="1823.0521,-27.2844 1832.5255,-22.5405 1822.1614,-20.3413 1823.0521,-27.2844"/>
<text text-anchor="middle" x="1646.6926" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- medical_history -->
<g id="node12" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1818.1926" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1818.1926" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1788.3506,-174.9403C1766.3716,-163.2518 1735.3573,-148.5469 1706.1926,-141 1636.1175,-122.8667 1434.0468,-112.2567 1324.6347,-107.6842"/>
<polygon fill="#000000" stroke="#000000" points="1324.4788,-104.1749 1314.3433,-107.2605 1324.1908,-111.169 1324.4788,-104.1749"/>
<text text-anchor="middle" x="1815.1926" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- study_arm -->
<g id="node13" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1912.1926" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1912.1926" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge36" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1903.0758,-86.9735C1896.8993,-74.7609 1888.631,-58.4123 1881.6946,-44.697"/>
<polygon fill="#000000" stroke="#000000" points="1884.7837,-43.0498 1877.1472,-35.7057 1878.5371,-46.209 1884.7837,-43.0498"/>
<text text-anchor="middle" x="1940.6926" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- study_funding -->
<g id="node14" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2067.1926" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2067.1926" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge29" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2045.9857,-87.6273C2031.7703,-76.6985 2012.2328,-63.0085 1993.1926,-54 1967.3563,-41.776 1936.5141,-32.8398 1911.9305,-26.9281"/>
<polygon fill="#000000" stroke="#000000" points="1912.6879,-23.511 1902.1552,-24.6562 1911.1032,-30.3292 1912.6879,-23.511"/>
<text text-anchor="middle" x="2080.1926" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1252.1926,-173.9735C1252.1926,-162.1918 1252.1926,-146.5607 1252.1926,-133.1581"/>
<polygon fill="#000000" stroke="#000000" points="1255.6927,-133.0033 1252.1926,-123.0034 1248.6927,-133.0034 1255.6927,-133.0033"/>
<text text-anchor="middle" x="1288.6926" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- therapeutic_procedure -->
<g id="node16" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="431.1926" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="431.1926" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M448.4203,-174.1352C460.9874,-162.3898 479.0991,-147.9517 498.1926,-141 561.0145,-118.1274 1002.7639,-108.8449 1179.4312,-106.0198"/>
<polygon fill="#000000" stroke="#000000" points="1179.7248,-109.5157 1189.6684,-105.8586 1179.6145,-102.5166 1179.7248,-109.5157"/>
<text text-anchor="middle" x="591.1926" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- family_relationship -->
<g id="node17" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="667.1926" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="667.1926" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M675.9141,-173.8602C682.5097,-162.3111 692.7326,-148.2122 706.1926,-141 746.8846,-119.1963 1040.5844,-109.7482 1179.6035,-106.4632"/>
<polygon fill="#000000" stroke="#000000" points="1179.8272,-109.9591 1189.7434,-106.2281 1179.6649,-102.961 1179.8272,-109.9591"/>
<text text-anchor="middle" x="785.6926" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- study_admin -->
<g id="node18" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="2233.1926" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2233.1926" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge34" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2210.0778,-87.9607C2193.2303,-76.4402 2169.3853,-61.9311 2146.1926,-54 2104.4492,-39.7252 1982.3991,-27.6134 1914.7264,-21.7605"/>
<polygon fill="#000000" stroke="#000000" points="1914.6142,-18.2383 1904.3528,-20.8755 1914.0191,-25.213 1914.6142,-18.2383"/>
<text text-anchor="middle" x="2234.6926" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1444.6941,-268.795C1438.6766,-266.2187 1432.2063,-263.4805 1426.1926,-261 1381.1583,-242.4247 1329.2021,-221.944 1293.8725,-208.1588"/>
<polygon fill="#000000" stroke="#000000" points="1294.9566,-204.825 1284.3682,-204.4554 1292.4151,-211.3473 1294.9566,-204.825"/>
<text text-anchor="middle" x="1402.1926" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge3" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1495.4111,-274.5229C1522.0416,-270.3239 1563.7916,-264.2226 1600.1926,-261 1624.4516,-258.8523 2021.3291,-260.5708 2038.1926,-243 2059.4274,-220.8747 2056.9341,-198.2735 2038.1926,-174 2024.506,-156.2734 1856.8793,-140.7266 1843.1926,-123 1825.5786,-100.1868 1838.1546,-66.8839 1851.0016,-43.9311"/>
<polygon fill="#000000" stroke="#000000" points="1854.1559,-45.4739 1856.2489,-35.0878 1848.1359,-41.9018 1854.1559,-45.4739"/>
<text text-anchor="middle" x="2003.1926" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study_personnel -->
<g id="node20" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2446.1926" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2446.1926" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2419.0926,-87.6176C2399.4088,-75.9355 2371.6863,-61.3741 2345.1926,-54 2265.1351,-31.7172 2018.7394,-22.2728 1914.9992,-19.2117"/>
<polygon fill="#000000" stroke="#000000" points="1914.9248,-15.7082 1904.8281,-18.9186 1914.7232,-22.7053 1914.9248,-15.7082"/>
<text text-anchor="middle" x="2451.6926" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node21" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1205.1926" cy="-366" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="1205.1926" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge32" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1069.6032,-362.5596C896.6961,-357.4964 618.0023,-346.7817 602.1926,-330 591.8171,-318.9866 602.191,-307.4642 616.6161,-298.1637"/>
<polygon fill="#000000" stroke="#000000" points="618.6074,-301.053 625.4512,-292.9652 615.0575,-295.0199 618.6074,-301.053"/>
<text text-anchor="middle" x="710.6926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge30" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1204.4897,-347.7355C1204.1838,-326.4421 1205.2722,-290.4144 1214.1926,-261 1218.7596,-245.9407 1226.8987,-230.4784 1234.4757,-218.0181"/>
<polygon fill="#000000" stroke="#000000" points="1237.4587,-219.8493 1239.8346,-209.5243 1231.5385,-216.1142 1237.4587,-219.8493"/>
<text text-anchor="middle" x="1322.6926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge31" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1216.3283,-347.9779C1224.4764,-336.4798 1236.6262,-322.3937 1251.1926,-315 1320.9134,-279.6107 1350.5072,-316.6238 1426.1926,-297 1429.5979,-296.1171 1433.0836,-295 1436.5197,-293.7563"/>
<polygon fill="#000000" stroke="#000000" points="1437.9624,-296.9493 1445.9644,-290.0054 1435.3786,-290.4436 1437.9624,-296.9493"/>
<text text-anchor="middle" x="1359.6926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- synonym -->
<g id="node22" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2143.1926" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2143.1926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2121.4312,-262.5557C2079.073,-231.6667 1981.4178,-165.8503 1887.1926,-141 1860.3881,-133.9308 1484.8046,-115.7959 1324.197,-108.3092"/>
<polygon fill="#000000" stroke="#000000" points="1324.0869,-104.8004 1313.935,-107.8317 1323.7614,-111.7928 1324.0869,-104.8004"/>
<text text-anchor="middle" x="2080.6926" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2103.1941,-267.4964C2094.6478,-265.2056 2085.6479,-262.9179 2077.1926,-261 2033.5792,-251.1073 2021.6176,-253.6899 1978.1926,-243 1956.4898,-237.6575 1952.2367,-231.6896 1930.1926,-228 1656.1123,-182.1256 1578.6901,-259.2304 1305.1926,-210 1301.4836,-209.3324 1297.6821,-208.4539 1293.9012,-207.4439"/>
<polygon fill="#000000" stroke="#000000" points="1294.6009,-204.0009 1284.0187,-204.5172 1292.6132,-210.7128 1294.6009,-204.0009"/>
<text text-anchor="middle" x="2020.6926" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge17" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2170.7457,-263.7239C2210.7264,-239.7752 2283.2061,-189.2047 2312.1926,-123 2324.86,-94.0679 2321.4437,-71.5616 2295.1926,-54 2264.1439,-33.2289 2018.97,-22.8906 1914.7793,-19.4004"/>
<polygon fill="#000000" stroke="#000000" points="1914.6673,-15.8949 1904.5578,-19.0649 1914.4375,-22.8911 1914.6673,-15.8949"/>
<text text-anchor="middle" x="2344.6926" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- molecular_test -->
<g id="node23" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="865.1926" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="865.1926" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M865.2627,-173.9387C866.334,-162.7272 869.7086,-148.981 879.1926,-141 901.661,-122.0924 1077.9695,-111.9481 1179.9444,-107.6109"/>
<polygon fill="#000000" stroke="#000000" points="1180.333,-111.0978 1190.1786,-107.1844 1180.0416,-104.1039 1180.333,-111.0978"/>
<text text-anchor="middle" x="943.1926" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- diagnosis -->
<g id="node25" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1018.1926" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1018.1926" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge40" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1012.8362,-173.9384C1010.8203,-163.1525 1010.5825,-149.8704 1018.1926,-141 1028.8624,-128.5631 1117.0395,-117.6515 1182.0212,-111.1908"/>
<polygon fill="#000000" stroke="#000000" points="1182.6237,-114.6487 1192.2358,-110.1925 1181.9428,-107.6818 1182.6237,-114.6487"/>
<text text-anchor="middle" x="1062.6926" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
</g>
</svg>
</div>
