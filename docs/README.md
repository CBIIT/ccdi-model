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
<svg width="2298pt" height="392pt"
 viewBox="0.00 0.00 2297.69 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 2293.6897,-388 2293.6897,4 -4,4"/>
<!-- clinical_measure_file -->
<g id="node1" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="219.6897" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="219.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- participant -->
<g id="node4" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1275.6897" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1275.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M212.4864,-173.5748C209.5409,-162.652 208.487,-149.3537 216.6897,-141 235.9019,-121.4343 1176.5056,-126.5984 1203.6897,-123 1209.4996,-122.2309 1215.5178,-121.1669 1221.4869,-119.9371"/>
<polygon fill="#000000" stroke="#000000" points="1222.4337,-123.3123 1231.4408,-117.7335 1220.9207,-116.4778 1222.4337,-123.3123"/>
<text text-anchor="middle" x="346.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- study -->
<g id="node19" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1038.6897" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1038.6897" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge30" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M208.1943,-174.0275C203.0695,-163.538 199.6064,-150.5355 206.6897,-141 256.2415,-74.2939 304.3149,-103.8291 385.6897,-87 609.871,-40.637 884.1515,-24.5533 991.989,-19.7735"/>
<polygon fill="#000000" stroke="#000000" points="992.3604,-23.2608 1002.2002,-19.3329 992.0586,-16.2673 992.3604,-23.2608"/>
<text text-anchor="middle" x="471.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- medical_history -->
<g id="node2" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1576.6897" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1576.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1555.5086,-174.3633C1540.7663,-163.0325 1520.1529,-148.9882 1499.6897,-141 1472.0134,-130.196 1399.1673,-119.6238 1343.9995,-112.7621"/>
<polygon fill="#000000" stroke="#000000" points="1344.271,-109.2692 1333.9191,-111.5248 1343.4182,-116.2171 1344.271,-109.2692"/>
<text text-anchor="middle" x="1596.6897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- diagnosis -->
<g id="node3" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1734.6897" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1734.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge37" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1717.9382,-174.6448C1705.5267,-162.9754 1687.5567,-148.4182 1668.6897,-141 1612.1097,-118.7535 1445.1081,-110.0504 1347.9736,-106.8043"/>
<polygon fill="#000000" stroke="#000000" points="1348.0393,-103.3047 1337.9315,-106.4798 1347.8132,-110.301 1348.0393,-103.3047"/>
<text text-anchor="middle" x="1738.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge1" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1258.4803,-87.5479C1246.3987,-76.2973 1229.3084,-62.273 1211.6897,-54 1171.3773,-35.071 1121.1535,-26.0337 1085.2224,-21.7564"/>
<polygon fill="#000000" stroke="#000000" points="1085.3481,-18.249 1075.0229,-20.624 1084.5756,-25.2062 1085.3481,-18.249"/>
<text text-anchor="middle" x="1284.1897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_arm -->
<g id="node5" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="626.6897" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="626.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge21" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M646.7635,-88.0191C661.7271,-76.3687 683.2073,-61.6771 704.6897,-54 756.4618,-35.4984 913.1326,-24.7227 992.1133,-20.328"/>
<polygon fill="#000000" stroke="#000000" points="992.4706,-23.8138 1002.2652,-19.7746 992.0894,-16.8242 992.4706,-23.8138"/>
<text text-anchor="middle" x="753.1897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- sample -->
<g id="node6" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1139.6897" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1139.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1156.4923,-175.2526C1167.7829,-164.5804 1183.3515,-150.9414 1198.6897,-141 1208.3633,-134.7302 1219.3029,-128.9347 1229.8352,-123.9078"/>
<polygon fill="#000000" stroke="#000000" points="1231.3365,-127.0697 1238.9439,-119.6956 1228.3983,-120.7162 1231.3365,-127.0697"/>
<text text-anchor="middle" x="1235.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- methylation_array_file -->
<g id="node7" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="115.6897" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="115.6897" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M93.5202,-348.2752C68.0719,-325.8747 32.8527,-287.0985 57.6897,-261 136.606,-178.0756 974.243,-231.4464 1086.6897,-210 1090.3409,-209.3036 1094.0842,-208.4135 1097.8106,-207.4031"/>
<polygon fill="#000000" stroke="#000000" points="1098.9761,-210.708 1107.5601,-204.4979 1096.977,-203.9995 1098.9761,-210.708"/>
<text text-anchor="middle" x="149.1897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- pdx -->
<g id="node18" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1426.6897" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1426.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge8" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M198.9951,-353.3718C230.848,-347.5906 267.2901,-339.8098 299.6897,-330 316.2793,-324.9771 318.7228,-318.545 335.6897,-315 563.907,-267.3169 1156.7162,-345.8351 1384.6897,-297 1388.1295,-296.2631 1391.6378,-295.2415 1395.0877,-294.0558"/>
<polygon fill="#000000" stroke="#000000" points="1396.4961,-297.2636 1404.5502,-290.3802 1393.9614,-290.7386 1396.4961,-297.2636"/>
<text text-anchor="middle" x="427.1897" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- cell_line -->
<g id="node23" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="698.6897" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="698.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge7" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M110.4175,-347.5813C108.5115,-336.661 108.5221,-323.363 116.6897,-315 132.8526,-298.4505 509.6231,-298.7478 532.6897,-297 569.0751,-294.243 609.8134,-289.8453 641.8267,-286.087"/>
<polygon fill="#000000" stroke="#000000" points="642.3796,-289.546 651.8975,-284.8921 641.5548,-282.5948 642.3796,-289.546"/>
<text text-anchor="middle" x="208.1897" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- molecular_test -->
<g id="node8" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1887.6897" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1887.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1861.0214,-174.8272C1841.3186,-163.084 1813.3911,-148.3601 1786.6897,-141 1706.2961,-118.8398 1469.4663,-109.8278 1348.5389,-106.5924"/>
<polygon fill="#000000" stroke="#000000" points="1348.3555,-103.0865 1338.2675,-106.3241 1348.1726,-110.0841 1348.3555,-103.0865"/>
<text text-anchor="middle" x="1887.6897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- sequencing_file -->
<g id="node9" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="527.6897" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="527.6897" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge36" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M448.3612,-360.5678C327.9729,-352.1363 112.4029,-336.2226 106.6897,-330 102.181,-325.0892 102.2911,-320.0096 106.6897,-315 127.0949,-291.7605 214.0359,-301.0971 244.6897,-297 361.6287,-281.3703 390.4494,-274.1797 507.6897,-261 571.8679,-253.7853 1023.4944,-223.313 1086.6897,-210 1090.2764,-209.2444 1093.9566,-208.3207 1097.6251,-207.2949"/>
<polygon fill="#000000" stroke="#000000" points="1098.6786,-210.6329 1107.2359,-204.3861 1096.6507,-203.9331 1098.6786,-210.6329"/>
<text text-anchor="middle" x="574.1897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge35" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M608.0307,-361.2792C683.1133,-355.9837 789.24,-345.9787 827.6897,-330 837.6248,-325.8712 836.5864,-318.698 846.6897,-315 959.0242,-273.8843 1267.9288,-323.0081 1384.6897,-297 1388.1234,-296.2352 1391.6277,-295.1952 1395.0752,-293.9984"/>
<polygon fill="#000000" stroke="#000000" points="1396.4903,-297.2033 1404.5345,-290.3084 1393.9463,-290.682 1396.4903,-297.2033"/>
<text text-anchor="middle" x="913.1897" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge34" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M522.8467,-347.5458C521.2106,-336.8857 521.3539,-323.8728 528.6897,-315 542.7935,-297.9414 596.5818,-288.6107 639.9273,-283.7534"/>
<polygon fill="#000000" stroke="#000000" points="640.5509,-287.207 650.1251,-282.6698 639.8112,-280.2462 640.5509,-287.207"/>
<text text-anchor="middle" x="595.1897" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- study_personnel -->
<g id="node10" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="791.6897" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="791.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge29" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M796.7221,-86.879C800.7983,-75.643 807.7061,-61.8919 818.6897,-54 845.7635,-34.547 936.0303,-24.9727 992.1766,-20.7909"/>
<polygon fill="#000000" stroke="#000000" points="992.5153,-24.2757 1002.2403,-20.0717 992.0162,-17.2935 992.5153,-24.2757"/>
<text text-anchor="middle" x="888.1897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- publication -->
<g id="node11" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="959.6897" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="959.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge33" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M958.6173,-86.9467C958.8831,-76.4286 960.839,-63.4243 967.6897,-54 975.054,-43.8691 986.102,-36.3995 997.3027,-30.9765"/>
<polygon fill="#000000" stroke="#000000" points="998.904,-34.0965 1006.6696,-26.8891 996.1044,-27.6807 998.904,-34.0965"/>
<text text-anchor="middle" x="1018.6897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node12" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1459.6897" cy="-366" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="1459.6897" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1582.4036,-357.7654C1723.0265,-348.184 1934.6699,-333.2558 1937.6897,-330 1942.2233,-325.1121 1942.1796,-319.9281 1937.6897,-315 1923.1847,-299.0793 1766.0205,-299.9773 1744.6897,-297 1579.0163,-273.8756 1540.2915,-251.6317 1374.6897,-228 1294.6592,-216.5795 1272.7476,-226.8866 1193.6897,-210 1189.8845,-209.1872 1185.9723,-208.1986 1182.0761,-207.1075"/>
<polygon fill="#000000" stroke="#000000" points="1183.0785,-203.7542 1172.4942,-204.226 1181.0626,-210.4576 1183.0785,-203.7542"/>
<text text-anchor="middle" x="1853.1897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge16" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1447.0234,-347.9406C1443.5838,-342.3873 1440.1379,-336.1207 1437.6897,-330 1434.8221,-322.8305 1432.6445,-314.7804 1431.0154,-307.2312"/>
<polygon fill="#000000" stroke="#000000" points="1434.4459,-306.5363 1429.1205,-297.3772 1427.5719,-307.8582 1434.4459,-306.5363"/>
<text text-anchor="middle" x="1546.1897" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge15" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1362.392,-353.2169C1346.1462,-351.3087 1329.4541,-349.4865 1313.6897,-348 1191.7469,-336.5016 1159.4937,-350.2157 1038.6897,-330 1013.7,-325.8181 1008.5421,-319.9331 983.6897,-315 905.9317,-299.5652 814.8569,-289.4184 756.9819,-283.9436"/>
<polygon fill="#000000" stroke="#000000" points="757.2076,-280.4495 746.9263,-283.0078 756.559,-287.4194 757.2076,-280.4495"/>
<text text-anchor="middle" x="1147.1897" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- follow_up -->
<g id="node13" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="433.6897" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="433.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M452.1099,-174.7461C466.1576,-162.7984 486.6215,-147.8568 507.6897,-141 581.2511,-117.059 1127.0388,-133.4438 1203.6897,-123 1209.4148,-122.2199 1215.3435,-121.1609 1221.2287,-119.9444"/>
<polygon fill="#000000" stroke="#000000" points="1222.0417,-123.3493 1231.0485,-117.7702 1220.5284,-116.5148 1222.0417,-123.3493"/>
<text text-anchor="middle" x="552.6897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- cytogenomic_file -->
<g id="node14" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1214.6897" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1214.6897" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge40" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1222.025,-347.8014C1224.9713,-337.9507 1226.98,-325.6522 1223.6897,-315 1211.8795,-276.765 1183.652,-239.8089 1163.1717,-216.5577"/>
<polygon fill="#000000" stroke="#000000" points="1165.586,-214.0086 1156.2903,-208.9253 1160.3871,-218.6961 1165.586,-214.0086"/>
<text text-anchor="middle" x="1287.1897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;pdx -->
<g id="edge38" class="edge">
<title>cytogenomic_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1234.3415,-348.2032C1247.8391,-336.9536 1266.6897,-323.064 1285.6897,-315 1326.8567,-297.5278 1341.8662,-309.8898 1384.6897,-297 1387.8802,-296.0397 1391.1544,-294.9099 1394.3988,-293.6923"/>
<polygon fill="#000000" stroke="#000000" points="1395.9593,-296.8371 1403.9296,-289.8568 1393.3459,-290.3432 1395.9593,-296.8371"/>
<text text-anchor="middle" x="1357.1897" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;cell_line -->
<g id="edge39" class="edge">
<title>cytogenomic_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1126.089,-363.1022C979.1253,-357.8598 699.5062,-345.857 684.6897,-330 678.521,-323.3981 679.1635,-314.3358 682.2922,-305.6802"/>
<polygon fill="#000000" stroke="#000000" points="685.4767,-307.1325 686.4584,-296.5832 679.1123,-304.2178 685.4767,-307.1325"/>
<text text-anchor="middle" x="756.1897" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- pathology_file -->
<g id="node15" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1821.6897" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1821.6897" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1882.7283,-355.2593C1911.8011,-348.9785 1942.4427,-340.2669 1952.6897,-330 1974.5368,-308.1105 1982.8211,-283.5812 1961.6897,-261 1903.2549,-198.556 1277.6062,-226.4897 1193.6897,-210 1189.8186,-209.2393 1185.8417,-208.2782 1181.886,-207.1975"/>
<polygon fill="#000000" stroke="#000000" points="1182.7522,-203.8037 1172.1696,-204.3114 1180.759,-210.514 1182.7522,-203.8037"/>
<text text-anchor="middle" x="2034.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge5" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1818.7054,-347.9796C1815.834,-336.6357 1810.2874,-322.7249 1799.6897,-315 1786.2748,-305.2215 1557.0867,-288.1475 1464.7675,-281.6303"/>
<polygon fill="#000000" stroke="#000000" points="1464.9444,-278.1342 1454.7237,-280.9249 1464.4539,-285.117 1464.9444,-278.1342"/>
<text text-anchor="middle" x="1872.6897" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge4" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1756.9646,-356.5117C1730.2774,-351.0274 1699.6004,-342.6267 1673.6897,-330 1664.0181,-325.2869 1664.7853,-318.7191 1654.6897,-315 1649.4063,-313.0536 966.411,-288.5486 758.2324,-281.1203"/>
<polygon fill="#000000" stroke="#000000" points="758.2191,-277.6177 748.1006,-280.7589 757.9695,-284.6132 758.2191,-277.6177"/>
<text text-anchor="middle" x="1734.6897" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- study_funding -->
<g id="node16" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="1117.6897" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="1117.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge2" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1101.3209,-86.9735C1089.4997,-73.9553 1073.4109,-56.2373 1060.5,-42.0189"/>
<polygon fill="#000000" stroke="#000000" points="1063.0152,-39.5823 1053.7015,-34.532 1057.8329,-44.2881 1063.0152,-39.5823"/>
<text text-anchor="middle" x="1145.6897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- family_relationship -->
<g id="node17" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="606.6897" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="606.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M601.3792,-173.5437C599.4588,-162.6092 599.4677,-149.3095 607.6897,-141 630.9892,-117.4526 1170.8766,-127.5433 1203.6897,-123 1209.4131,-122.2075 1215.3407,-121.1404 1221.2252,-119.9191"/>
<polygon fill="#000000" stroke="#000000" points="1222.0404,-123.3234 1231.0443,-117.7395 1220.5235,-116.4897 1222.0404,-123.3234"/>
<text text-anchor="middle" x="687.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1403.8171,-268.4913C1397.6745,-265.8643 1390.9877,-263.1777 1384.6897,-261 1301.6508,-232.2869 1277.8502,-235.2374 1193.6897,-210 1190.322,-208.9901 1186.8474,-207.9133 1183.3606,-206.8076"/>
<polygon fill="#000000" stroke="#000000" points="1184.1723,-203.3917 1173.5806,-203.6468 1182.0196,-210.0525 1184.1723,-203.3917"/>
<text text-anchor="middle" x="1346.6897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge27" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1453.7195,-274.1077C1478.3719,-269.8617 1515.8505,-263.9464 1548.6897,-261 1579.3606,-258.2482 2081.2715,-265.1254 2102.6897,-243 2124.0193,-220.9661 2121.8529,-197.942 2102.6897,-174 2037.7541,-92.8708 1280.9936,-34.8635 1084.8735,-21.1236"/>
<polygon fill="#000000" stroke="#000000" points="1085.1108,-17.6317 1074.8918,-20.4287 1084.6246,-24.6148 1085.1108,-17.6317"/>
<text text-anchor="middle" x="2097.6897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- synonym -->
<g id="node20" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2175.6897" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2175.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2161.862,-261.4593C2152.9042,-250.8695 2140.5442,-237.6105 2127.6897,-228 2110.5369,-215.1758 1976.3835,-146.518 1955.6897,-141 1898.2651,-125.6875 1511.4989,-112.2189 1348.2095,-107.1451"/>
<polygon fill="#000000" stroke="#000000" points="1347.8862,-103.6336 1337.7829,-106.8231 1347.6701,-110.6302 1347.8862,-103.6336"/>
<text text-anchor="middle" x="2137.1897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2134.8561,-267.8376C2126.5307,-265.569 2117.8293,-263.2033 2109.6897,-261 2079.9272,-252.9435 2072.2997,-251.6002 2042.6897,-243 2021.226,-236.7659 2016.7454,-231.6199 1994.6897,-228 1818.9955,-199.1639 1369.1042,-240.4921 1193.6897,-210 1189.7497,-209.3151 1185.7058,-208.3969 1181.6895,-207.3363"/>
<polygon fill="#000000" stroke="#000000" points="1182.4178,-203.9029 1171.8375,-204.4584 1180.455,-210.6221 1182.4178,-203.9029"/>
<text text-anchor="middle" x="2085.1897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge18" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2182.4963,-261.0641C2198.3216,-216.0025 2231.3956,-98.4766 2164.6897,-54 2119.1541,-23.6388 1292.2558,-18.8485 1085.3303,-18.1242"/>
<polygon fill="#000000" stroke="#000000" points="1085.1182,-14.6235 1075.1065,-18.09 1085.0947,-21.6235 1085.1182,-14.6235"/>
<text text-anchor="middle" x="2247.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- therapeutic_procedure -->
<g id="node21" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="959.6897" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="959.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M965.8412,-173.7781C970.709,-162.349 978.7092,-148.4192 990.6897,-141 1031.075,-115.9906 1156.8301,-130.7856 1203.6897,-123 1209.1711,-122.0893 1214.849,-120.9746 1220.5015,-119.7505"/>
<polygon fill="#000000" stroke="#000000" points="1221.6283,-123.0836 1230.6009,-117.4494 1220.0732,-116.2585 1221.6283,-123.0836"/>
<text text-anchor="middle" x="1083.6897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- study_admin -->
<g id="node22" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="2100.6897" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2100.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge23" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2079.3585,-87.8051C2063.2027,-75.8868 2039.8959,-60.956 2016.6897,-54 1927.0844,-27.1411 1267.8906,-19.8518 1085.4003,-18.3391"/>
<polygon fill="#000000" stroke="#000000" points="1085.3471,-14.8386 1075.319,-18.2574 1085.2903,-21.8384 1085.3471,-14.8386"/>
<text text-anchor="middle" x="2104.1897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M702.4485,-260.8141C708.4336,-236.7855 722.5612,-195.0506 751.6897,-174 833.6168,-114.7929 1103.9212,-139.241 1203.6897,-123 1209.1741,-122.1072 1214.8539,-121.0044 1220.5076,-119.7877"/>
<polygon fill="#000000" stroke="#000000" points="1221.631,-123.1218 1230.6084,-117.4954 1220.0817,-116.2954 1221.631,-123.1218"/>
<text text-anchor="middle" x="792.1897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M745.4648,-273.0151C818.8657,-263.1024 965.2643,-241.2247 1086.6897,-210 1090.0381,-209.139 1093.4795,-208.1696 1096.9233,-207.1386"/>
<polygon fill="#000000" stroke="#000000" points="1098.0702,-210.447 1106.5601,-204.1089 1095.9707,-203.7693 1098.0702,-210.447"/>
<text text-anchor="middle" x="1043.1897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge12" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M663.8621,-266.104C657.5499,-264.1369 650.9751,-262.3246 644.6897,-261 526.0968,-236.0079 183.2842,-299.6171 101.6897,-210 90.918,-198.1691 98.1087,-189.5941 101.6897,-174 116.273,-110.4952 157.5247,-106.5204 219.6897,-87 365.4324,-41.2355 840.2907,-23.7565 991.7884,-19.2617"/>
<polygon fill="#000000" stroke="#000000" points="992.2347,-22.7503 1002.1284,-18.9603 992.0307,-15.7533 992.2347,-22.7503"/>
<text text-anchor="middle" x="155.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- radiology_file -->
<g id="node24" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1275.6897" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1275.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1275.6897,-173.9735C1275.6897,-162.1918 1275.6897,-146.5607 1275.6897,-133.1581"/>
<polygon fill="#000000" stroke="#000000" points="1279.1898,-133.0033 1275.6897,-123.0034 1272.1898,-133.0034 1279.1898,-133.0033"/>
<text text-anchor="middle" x="1334.6897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- exposure -->
<g id="node25" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1420.6897" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1420.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1416.5307,-173.6252C1413.1667,-162.7214 1407.3537,-149.4254 1397.6897,-141 1387.9851,-132.5392 1361.8104,-124.3171 1336.1826,-117.8717"/>
<polygon fill="#000000" stroke="#000000" points="1336.9674,-114.4606 1326.4228,-115.4916 1335.3088,-121.2613 1336.9674,-114.4606"/>
<text text-anchor="middle" x="1452.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
</g>
</svg>
</div>
