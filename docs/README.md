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
<svg width="2531pt" height="392pt"
 viewBox="0.00 0.00 2530.62 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 2526.6219,-388 2526.6219,4 -4,4"/>
<!-- diagnosis -->
<g id="node1" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="577.2788" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="577.2788" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- participant -->
<g id="node21" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1291.2788" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1291.2788" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M575.64,-173.8665C575.712,-162.6254 577.9846,-148.8733 587.2788,-141 614.0801,-118.2959 1184.4812,-127.7876 1219.2788,-123 1225.0028,-122.2125 1230.9308,-121.1485 1236.8156,-119.9291"/>
<polygon fill="#000000" stroke="#000000" points="1237.6299,-123.3337 1246.635,-117.7517 1236.1144,-116.4997 1237.6299,-123.3337"/>
<text text-anchor="middle" x="631.7788" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- medical_history -->
<g id="node2" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="856.2788" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="856.2788" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M872.3016,-174.2139C884.0375,-162.5047 901.0438,-148.0774 919.2788,-141 981.5403,-116.835 1153.2668,-133.1424 1219.2788,-123 1224.7708,-122.1562 1230.4558,-121.0858 1236.1127,-119.8893"/>
<polygon fill="#000000" stroke="#000000" points="1237.2268,-123.2263 1246.2173,-117.6207 1235.6934,-116.3963 1237.2268,-123.2263"/>
<text text-anchor="middle" x="987.2788" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node3" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="853.2788" cy="-366" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="853.2788" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- pdx -->
<g id="node12" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1411.2788" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1411.2788" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge11" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M848.0479,-347.6214C846.1575,-336.7163 846.1699,-323.4201 854.2788,-315 878.5198,-289.8285 1133.4078,-299.2908 1168.2788,-297 1240.684,-292.2433 1325.1541,-285.78 1373.016,-282.0325"/>
<polygon fill="#000000" stroke="#000000" points="1373.5309,-285.5029 1383.2261,-281.2307 1372.9828,-278.5244 1373.5309,-285.5029"/>
<text text-anchor="middle" x="962.7788" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- cell_line -->
<g id="node17" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="1970.2788" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="1970.2788" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge13" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M956.1207,-354.0076C992.8676,-348.4173 1034.3125,-340.5988 1071.2788,-330 1087.9408,-325.2227 1090.3231,-318.5985 1107.2788,-315 1274.0555,-279.6049 1704.7158,-314.768 1874.2788,-297 1888.5282,-295.5068 1903.829,-293.0386 1917.9351,-290.4015"/>
<polygon fill="#000000" stroke="#000000" points="1918.8092,-293.7973 1927.9632,-288.4629 1917.4806,-286.9246 1918.8092,-293.7973"/>
<text text-anchor="middle" x="1215.7788" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- sample -->
<g id="node19" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1003.2788" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1003.2788" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M825.3001,-348.3269C818.4448,-343.0469 811.5668,-336.8249 806.2788,-330 787.1133,-305.2645 773.8616,-286.2976 792.2788,-261 835.709,-201.3447 880.2305,-233.1988 950.2788,-210 953.3691,-208.9765 956.5582,-207.9127 959.7673,-206.8366"/>
<polygon fill="#000000" stroke="#000000" points="961.0167,-210.109 969.3759,-203.5995 958.7818,-203.4754 961.0167,-210.109"/>
<text text-anchor="middle" x="900.7788" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- follow_up -->
<g id="node4" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="1120.2788" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="1120.2788" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1141.7336,-175.3806C1156.2855,-164.6282 1176.2641,-150.8503 1195.2788,-141 1209.2811,-133.7462 1225.0893,-127.2016 1239.7763,-121.744"/>
<polygon fill="#000000" stroke="#000000" points="1241.0253,-125.0142 1249.2357,-118.318 1238.6415,-118.4326 1241.0253,-125.0142"/>
<text text-anchor="middle" x="1240.2788" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- clinical_measure_file -->
<g id="node5" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="124.2788" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="124.2788" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- study -->
<g id="node14" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1765.2788" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1765.2788" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge4" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M119.9668,-173.606C118.5787,-162.695 119.1214,-149.3981 127.2788,-141 280.8467,17.099 895.438,-69.7629 1115.2788,-54 1341.384,-37.7879 1612.1883,-24.8812 1718.8571,-20.0522"/>
<polygon fill="#000000" stroke="#000000" points="1719.1273,-23.5436 1728.9595,-19.5968 1718.812,-16.5507 1719.1273,-23.5436"/>
<text text-anchor="middle" x="297.2788" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M125.6054,-173.8065C127.4839,-162.3894 131.9164,-148.4622 142.2788,-141 166.5591,-123.5151 1189.6137,-126.9038 1219.2788,-123 1225.0892,-122.2354 1231.1078,-121.1742 1237.0772,-119.9461"/>
<polygon fill="#000000" stroke="#000000" points="1238.0231,-123.3215 1247.0312,-117.7444 1236.5113,-116.4867 1238.0231,-123.3215"/>
<text text-anchor="middle" x="271.7788" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- therapeutic_procedure -->
<g id="node6" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="1311.2788" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="1311.2788" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1299.6778,-173.9883C1296.6887,-168.4363 1293.8684,-162.1585 1292.2788,-156 1290.4133,-148.773 1289.6677,-140.7769 1289.5069,-133.3013"/>
<polygon fill="#000000" stroke="#000000" points="1293.0075,-133.2505 1289.6131,-123.2142 1286.0079,-133.1767 1293.0075,-133.2505"/>
<text text-anchor="middle" x="1385.2788" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- exposure -->
<g id="node7" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1500.2788" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1500.2788" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1496.9146,-173.8059C1493.9071,-162.6873 1488.3515,-149.0933 1478.2788,-141 1460.3083,-126.561 1406.4258,-117.1703 1361.0892,-111.6125"/>
<polygon fill="#000000" stroke="#000000" points="1361.3103,-108.1144 1350.9686,-110.4168 1360.4889,-115.066 1361.3103,-108.1144"/>
<text text-anchor="middle" x="1532.7788" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- methylation_array_file -->
<g id="node8" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1687.2788" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1687.2788" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge8" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1590.4514,-356.1235C1557.8465,-350.7653 1521.7676,-342.5524 1490.2788,-330 1478.9423,-325.4809 1477.5228,-321.6331 1467.2788,-315 1458.329,-309.205 1448.5576,-302.9117 1439.7188,-297.2318"/>
<polygon fill="#000000" stroke="#000000" points="1441.5616,-294.2557 1431.2559,-291.7975 1437.7793,-300.1459 1441.5616,-294.2557"/>
<text text-anchor="middle" x="1581.7788" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge10" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1772.7817,-353.8015C1799.5084,-348.3533 1828.6841,-340.674 1854.2788,-330 1865.5425,-325.3025 1866.4181,-320.5664 1877.2788,-315 1892.0664,-307.421 1908.8377,-300.4648 1924.0269,-294.7297"/>
<polygon fill="#000000" stroke="#000000" points="1925.5739,-297.8896 1933.7431,-291.143 1923.1498,-291.3227 1925.5739,-297.8896"/>
<text text-anchor="middle" x="1968.7788" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1686.7357,-347.6286C1685.4364,-336.7261 1681.9864,-323.4302 1673.2788,-315 1533.1916,-179.375 1436.6725,-252.848 1243.2788,-228 1160.4643,-217.3597 1137.9103,-227.5426 1056.2788,-210 1052.6952,-209.2299 1049.0171,-208.296 1045.3501,-207.2632"/>
<polygon fill="#000000" stroke="#000000" points="1046.3274,-203.9022 1035.7418,-204.3433 1044.292,-210.5998 1046.3274,-203.9022"/>
<text text-anchor="middle" x="1741.7788" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- publication -->
<g id="node9" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="989.2788" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="989.2788" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge36" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1032.4033,-91.8424C1073.5707,-79.8634 1137.5534,-62.7523 1194.2788,-54 1295.0491,-38.4518 1601.4302,-24.6884 1718.825,-19.847"/>
<polygon fill="#000000" stroke="#000000" points="1719.0787,-23.3396 1728.927,-19.4332 1718.7921,-16.3455 1719.0787,-23.3396"/>
<text text-anchor="middle" x="1245.2788" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- study_admin -->
<g id="node10" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1140.2788" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1140.2788" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge29" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1192.7452,-93.0346C1201.9156,-90.9891 1211.37,-88.9094 1220.2788,-87 1292.1257,-71.6011 1309.5962,-64.787 1382.2788,-54 1503.0158,-36.0811 1646.5656,-25.3991 1718.8193,-20.7537"/>
<polygon fill="#000000" stroke="#000000" points="1719.1924,-24.2372 1728.9512,-20.112 1718.7499,-17.2512 1719.1924,-24.2372"/>
<text text-anchor="middle" x="1438.7788" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- radiology_file -->
<g id="node11" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1645.2788" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1645.2788" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1628.2266,-174.3327C1616.0124,-162.8353 1598.5518,-148.6099 1580.2788,-141 1542.1639,-125.1269 1435.0589,-114.8548 1362.5026,-109.4976"/>
<polygon fill="#000000" stroke="#000000" points="1362.7312,-106.0051 1352.5046,-108.7742 1362.2259,-112.9868 1362.7312,-106.0051"/>
<text text-anchor="middle" x="1664.2788" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge21" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1438.9742,-276.1407C1540.857,-265.4933 1889.7543,-227.8435 1905.2788,-210 1957.0704,-150.4716 1853.3206,-72.7176 1797.5405,-37.2018"/>
<polygon fill="#000000" stroke="#000000" points="1799.3643,-34.2143 1789.0312,-31.8737 1795.6494,-40.1472 1799.3643,-34.2143"/>
<text text-anchor="middle" x="1939.2788" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1383.8254,-274.9641C1323.8241,-265.8608 1176.7289,-242.0019 1056.2788,-210 1052.9373,-209.1122 1049.501,-208.1236 1046.0607,-207.0792"/>
<polygon fill="#000000" stroke="#000000" points="1047.0202,-203.7118 1036.43,-204.0259 1044.9047,-210.3844 1047.0202,-203.7118"/>
<text text-anchor="middle" x="1215.2788" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study_arm -->
<g id="node13" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2098.2788" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2098.2788" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge23" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2079.0075,-87.9507C2064.861,-76.4255 2044.6383,-61.9148 2024.2788,-54 1986.5021,-39.3142 1875.4192,-27.6009 1811.6706,-21.8582"/>
<polygon fill="#000000" stroke="#000000" points="1811.7548,-18.352 1801.4848,-20.9551 1811.1366,-25.3247 1811.7548,-18.352"/>
<text text-anchor="middle" x="2100.7788" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- molecular_test -->
<g id="node15" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1816.2788" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1816.2788" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1792.6833,-174.6339C1775.4724,-162.9594 1751.087,-148.4005 1727.2788,-141 1661.4741,-120.5455 1469.8999,-111.0008 1363.9135,-107.1766"/>
<polygon fill="#000000" stroke="#000000" points="1363.7353,-103.6682 1353.618,-106.8134 1363.4884,-110.6639 1363.7353,-103.6682"/>
<text text-anchor="middle" x="1824.2788" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- study_personnel -->
<g id="node16" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2263.2788" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2263.2788" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge24" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2233.9778,-88.0485C2212.3952,-76.4124 2181.9361,-61.7257 2153.2788,-54 2089.9768,-36.9346 1900.1103,-25.0738 1811.6191,-20.3191"/>
<polygon fill="#000000" stroke="#000000" points="1811.7702,-16.8223 1801.5989,-19.7879 1811.3995,-23.8125 1811.7702,-16.8223"/>
<text text-anchor="middle" x="2262.7788" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge6" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2005.7758,-266.4441C2030.4272,-255.6419 2061.4154,-237.4101 2076.2788,-210 2083.9057,-195.9348 2082.9127,-188.5599 2076.2788,-174 2067.8538,-155.5092 1956.4821,-63.0291 1938.2788,-54 1898.2566,-34.1484 1847.7868,-25.2327 1811.7063,-21.235"/>
<polygon fill="#000000" stroke="#000000" points="1811.7699,-17.7233 1801.466,-20.189 1811.0586,-24.6871 1811.7699,-17.7233"/>
<text text-anchor="middle" x="2100.7788" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1977.7097,-260.9422C1988.471,-231.534 2003.9547,-173.3379 1973.2788,-141 1952.5624,-119.1612 1535.4494,-109.3153 1363.9521,-106.1787"/>
<polygon fill="#000000" stroke="#000000" points="1363.8162,-102.6758 1353.7547,-105.9949 1363.69,-109.6747 1363.8162,-102.6758"/>
<text text-anchor="middle" x="2031.7788" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- pathology_file -->
<g id="node18" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2227.2788" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2227.2788" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge19" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2162.5536,-356.5117C2135.8665,-351.0274 2105.1895,-342.6267 2079.2788,-330 2069.6072,-325.2869 2070.3596,-318.759 2060.2788,-315 2019.1131,-299.65 1709.1389,-299.553 1665.2788,-297 1588.597,-292.5365 1498.9993,-285.8401 1449.3419,-281.998"/>
<polygon fill="#000000" stroke="#000000" points="1449.3181,-278.4856 1439.077,-281.2003 1448.7757,-285.4646 1449.3181,-278.4856"/>
<text text-anchor="middle" x="2140.2788" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge20" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2224.0845,-347.9236C2221.1351,-336.706 2215.5805,-322.9586 2205.2788,-315 2178.5705,-294.3667 2090.0833,-285.404 2029.6485,-281.6214"/>
<polygon fill="#000000" stroke="#000000" points="2029.649,-278.1153 2019.4589,-281.0157 2029.2335,-285.103 2029.649,-278.1153"/>
<text text-anchor="middle" x="2278.2788" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2294.5474,-357.5663C2329.8511,-350.3576 2362.2103,-337.4531 2343.2788,-315 2271.5317,-229.9069 1641.5852,-239.7648 1415.2788,-228 1255.7382,-219.7061 1213.1974,-239.975 1056.2788,-210 1052.6278,-209.3026 1048.8846,-208.4117 1045.1584,-207.4008"/>
<polygon fill="#000000" stroke="#000000" points="1045.9921,-203.9972 1035.409,-204.4949 1043.9925,-210.7056 1045.9921,-203.9972"/>
<text text-anchor="middle" x="2377.2788" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1025.741,-176.3065C1043.518,-164.6745 1069.4093,-149.4329 1094.2788,-141 1147.4346,-122.9756 1164.2031,-133.8207 1219.2788,-123 1224.573,-121.9598 1230.0617,-120.7784 1235.5396,-119.5296"/>
<polygon fill="#000000" stroke="#000000" points="1236.41,-122.9205 1245.3439,-117.2252 1234.8083,-116.1062 1236.41,-122.9205"/>
<text text-anchor="middle" x="1130.7788" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_funding -->
<g id="node20" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2445.2788" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2445.2788" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge2" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2416.784,-88.0385C2395.4149,-76.2363 2365.0217,-61.3484 2336.2788,-54 2237.4932,-28.7446 1929.9135,-20.8438 1811.966,-18.7049"/>
<polygon fill="#000000" stroke="#000000" points="1811.8758,-15.2029 1801.8158,-18.5267 1811.7528,-22.2018 1811.8758,-15.2029"/>
<text text-anchor="middle" x="2438.2788" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge16" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1344.2729,-95.2732C1438.5024,-77.9779 1633.5029,-42.1867 1721.0449,-26.1189"/>
<polygon fill="#000000" stroke="#000000" points="1721.7211,-29.5533 1730.9249,-24.3054 1720.4574,-22.6683 1721.7211,-29.5533"/>
<text text-anchor="middle" x="1606.7788" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sequencing_file -->
<g id="node22" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1333.2788" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1333.2788" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge25" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1329.1443,-347.6274C1327.8495,-337.2532 1328.0995,-324.5032 1334.2788,-315 1343.3852,-300.995 1359.4945,-292.3365 1374.6327,-287.0347"/>
<polygon fill="#000000" stroke="#000000" points="1375.8461,-290.3228 1384.357,-284.0129 1373.7688,-283.6381 1375.8461,-290.3228"/>
<text text-anchor="middle" x="1400.7788" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge27" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1412.176,-360.0823C1497.7425,-353.2488 1628.6223,-341.4707 1677.2788,-330 1695.7588,-325.6433 1698.8204,-319.4479 1717.2788,-315 1785.5592,-298.5465 1804.8299,-307.4784 1874.2788,-297 1888.176,-294.9032 1903.1373,-292.2773 1917.0169,-289.6848"/>
<polygon fill="#000000" stroke="#000000" points="1917.7285,-293.1123 1926.9016,-287.8109 1916.4247,-286.2348 1917.7285,-293.1123"/>
<text text-anchor="middle" x="1783.7788" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1252.6559,-361.4726C1115.3455,-353.571 850.1557,-337.4007 843.2788,-330 838.7407,-325.1163 838.826,-319.9616 843.2788,-315 868.0615,-287.3847 984.496,-324.6153 1009.2788,-297 1027.8694,-276.2846 1022.192,-243.0083 1014.5565,-219.4759"/>
<polygon fill="#000000" stroke="#000000" points="1017.7469,-218 1011.1104,-209.7412 1011.1482,-220.336 1017.7469,-218"/>
<text text-anchor="middle" x="1087.7788" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- synonym -->
<g id="node23" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="668.2788" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="668.2788" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge32" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M616.3034,-277.4996C467.3413,-272.6682 46.9397,-255.1193 6.2788,-210 -4.4325,-198.1143 1.1825,-189.1667 6.2788,-174 49.2734,-46.0472 151.4263,-71.4343 285.2788,-54 430.0016,-35.1498 1482.9709,-21.4098 1718.5912,-18.5509"/>
<polygon fill="#000000" stroke="#000000" points="1718.9127,-22.0474 1728.8697,-18.4268 1718.8281,-15.0479 1718.9127,-22.0474"/>
<text text-anchor="middle" x="62.7788" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M675.3235,-260.9432C680.831,-249.43 689.6827,-235.3401 702.2788,-228 750.0203,-200.1796 896.1233,-220.9737 950.2788,-210 953.9217,-209.2618 957.6592,-208.3424 961.3817,-207.3123"/>
<polygon fill="#000000" stroke="#000000" points="962.5605,-210.6127 971.1251,-204.3759 960.5405,-203.9104 962.5605,-210.6127"/>
<text text-anchor="middle" x="744.7788" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M663.7688,-260.7435C659.2001,-237.4116 655.5486,-197.2652 677.2788,-174 715.7099,-132.8542 1156.9828,-132.4035 1219.2788,-123 1224.773,-122.1706 1230.4594,-121.1099 1236.1173,-119.9193"/>
<polygon fill="#000000" stroke="#000000" points="1237.2286,-123.2572 1246.2229,-117.6578 1235.6999,-116.4262 1237.2286,-123.2572"/>
<text text-anchor="middle" x="719.7788" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- family_relationship -->
<g id="node24" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="404.2788" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="404.2788" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M402.6239,-173.8474C402.6892,-162.5985 404.9606,-148.8449 414.2788,-141 448.4995,-112.19 1174.9444,-128.9616 1219.2788,-123 1225.087,-122.219 1231.1042,-121.1473 1237.0727,-119.9128"/>
<polygon fill="#000000" stroke="#000000" points="1238.0216,-123.2875 1247.0259,-117.7043 1236.5052,-116.4537 1238.0216,-123.2875"/>
<text text-anchor="middle" x="493.7788" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
</g>
</svg>
</div>
