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
<svg width="2319pt" height="305pt"
 viewBox="0.00 0.00 2318.95 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 2314.9475,-301 2314.9475,4 -4,4"/>
<!-- family_relationship -->
<g id="node1" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="561.9475" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="561.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- participant -->
<g id="node16" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1327.9475" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1327.9475" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M578.2109,-174.0305C590.1268,-162.2372 607.4011,-147.7846 625.9475,-141 691.7137,-116.9414 1186.5729,-132.5481 1255.9475,-123 1261.6715,-122.2122 1267.5995,-121.1481 1273.4843,-119.9286"/>
<polygon fill="#000000" stroke="#000000" points="1274.2987,-123.3331 1283.3037,-117.751 1272.7831,-116.4991 1274.2987,-123.3331"/>
<text text-anchor="middle" x="705.4475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- study_admin -->
<g id="node2" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="722.9475" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="722.9475" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study -->
<g id="node23" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1245.9475" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1245.9475" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge6" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M742.3822,-87.5869C756.6742,-75.8902 777.1553,-61.3241 797.9475,-54 870.9827,-28.2731 1100.0564,-20.7991 1199.3157,-18.7392"/>
<polygon fill="#000000" stroke="#000000" points="1199.4248,-22.2379 1209.3534,-18.5403 1199.286,-15.2392 1199.4248,-22.2379"/>
<text text-anchor="middle" x="854.4475" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- follow_up -->
<g id="node3" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="862.9475" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="862.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M883.9831,-175.2023C900.1736,-163.3178 923.6542,-148.2545 946.9475,-141 1012.6193,-120.547 1187.9532,-133.3864 1255.9475,-123 1261.4403,-122.1609 1267.1257,-121.0938 1272.783,-119.8992"/>
<polygon fill="#000000" stroke="#000000" points="1273.8962,-123.2365 1282.8879,-117.633 1272.3643,-116.4062 1273.8962,-123.2365"/>
<text text-anchor="middle" x="991.9475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- publication -->
<g id="node4" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="873.9475" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="873.9475" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge9" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M891.6421,-87.5549C904.493,-76.0021 922.9038,-61.6215 941.9475,-54 987.5655,-35.7433 1125.8824,-25.0785 1199.1881,-20.5631"/>
<polygon fill="#000000" stroke="#000000" points="1199.7417,-24.0362 1209.5132,-19.9414 1199.3209,-17.0489 1199.7417,-24.0362"/>
<text text-anchor="middle" x="992.9475" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- sequencing_file -->
<g id="node5" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="871.9475" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="871.9475" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sample -->
<g id="node17" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="399.9475" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="399.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M848.7813,-261.6807C831.5808,-249.8666 807.0274,-235.1182 782.9475,-228 642.0884,-186.3608 597.1626,-237.8769 452.9475,-210 449.2981,-209.2946 445.556,-208.3981 441.8305,-207.3834"/>
<polygon fill="#000000" stroke="#000000" points="442.6657,-203.9801 432.0822,-204.4715 440.6621,-210.6873 442.6657,-203.9801"/>
<text text-anchor="middle" x="882.4475" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- pdx -->
<g id="node6" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="27.9475" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="27.9475" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M49.7824,-267.6773C73.7049,-255.8 113.5318,-237.5576 149.9475,-228 216.4119,-210.5558 295.1816,-200.9786 346.2878,-196.1735"/>
<polygon fill="#000000" stroke="#000000" points="346.8027,-199.6411 356.4435,-195.2473 346.1669,-192.67 346.8027,-199.6411"/>
<text text-anchor="middle" x="173.9475" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- methylation_array_file -->
<g id="node7" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="189.9475" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="189.9475" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M193.6814,-260.7891C196.912,-249.6637 202.735,-236.0686 212.9475,-228 233.249,-211.9604 298.6263,-202.077 346.373,-196.8177"/>
<polygon fill="#000000" stroke="#000000" points="346.9994,-200.2709 356.5737,-195.734 346.2599,-193.3101 346.9994,-200.2709"/>
<text text-anchor="middle" x="304.4475" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- molecular_test -->
<g id="node8" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1015.9475" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1015.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1026.7285,-173.9336C1034.6505,-162.4163 1046.524,-148.3254 1060.9475,-141 1099.7477,-121.2941 1213.0464,-130.2986 1255.9475,-123 1261.346,-122.0816 1266.9363,-120.972 1272.5062,-119.7601"/>
<polygon fill="#000000" stroke="#000000" points="1273.4934,-123.1248 1282.4637,-117.4872 1271.9356,-116.3004 1273.4934,-123.1248"/>
<text text-anchor="middle" x="1124.9475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- pathology_file -->
<g id="node9" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="399.9475" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="399.9475" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M399.9475,-260.9735C399.9475,-249.1918 399.9475,-233.5607 399.9475,-220.1581"/>
<polygon fill="#000000" stroke="#000000" points="403.4476,-220.0033 399.9475,-210.0034 396.4476,-220.0034 403.4476,-220.0033"/>
<text text-anchor="middle" x="460.9475" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- study_arm -->
<g id="node10" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1014.9475" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1014.9475" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1029.1589,-87.213C1039.1143,-75.9675 1053.3817,-62.0789 1068.9475,-54 1091.4122,-42.3405 1155.9242,-31.071 1200.5236,-24.3357"/>
<polygon fill="#000000" stroke="#000000" points="1201.1766,-27.7772 1210.554,-22.8462 1200.1484,-20.8531 1201.1766,-27.7772"/>
<text text-anchor="middle" x="1117.4475" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- therapeutic_procedure -->
<g id="node11" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="1584.9475" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="1584.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1534.4474,-175.6689C1519.2036,-170.1018 1502.6261,-163.3943 1487.9475,-156 1477.0483,-150.5096 1476.1036,-145.9477 1464.9475,-141 1461.0304,-139.2628 1420.7599,-128.7438 1384.8869,-119.5215"/>
<polygon fill="#000000" stroke="#000000" points="1385.4755,-116.0593 1374.9193,-116.9632 1383.7352,-122.8395 1385.4755,-116.0593"/>
<text text-anchor="middle" x="1580.9475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- medical_history -->
<g id="node12" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1363.9475" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1363.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1341.5995,-174.2351C1336.5062,-168.9558 1331.7683,-162.7571 1328.9475,-156 1325.9922,-148.9207 1324.9225,-140.7928 1324.8006,-133.1366"/>
<polygon fill="#000000" stroke="#000000" points="1328.2989,-133.2425 1325.1338,-123.1315 1321.3028,-133.0094 1328.2989,-133.2425"/>
<text text-anchor="middle" x="1396.9475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node13" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="631.9475" cy="-279" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="631.9475" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M599.753,-261.3568C579.1198,-250.5949 551.5074,-237.1883 525.9475,-228 494.5014,-216.6957 485.0197,-219.3816 452.9475,-210 449.7764,-209.0724 446.5128,-208.0737 443.2371,-207.0391"/>
<polygon fill="#000000" stroke="#000000" points="444.0466,-203.6222 433.4545,-203.8631 441.885,-210.2801 444.0466,-203.6222"/>
<text text-anchor="middle" x="670.4475" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- exposure -->
<g id="node14" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="2008.9475" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="2008.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1996.309,-174.3559C1986.7256,-162.5504 1972.419,-147.9492 1955.9475,-141 1898.8959,-116.9303 1460.2603,-131.6589 1398.9475,-123 1393.5175,-122.2331 1387.9021,-121.2138 1382.3178,-120.0489"/>
<polygon fill="#000000" stroke="#000000" points="1382.8696,-116.5859 1372.3467,-117.8179 1381.3411,-123.417 1382.8696,-116.5859"/>
<text text-anchor="middle" x="2020.4475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- study_funding -->
<g id="node15" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="1169.9475" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="1169.9475" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1168.5066,-87.0031C1168.5611,-76.505 1170.2617,-63.5019 1176.9475,-54 1183.8632,-44.1713 1194.3028,-36.8266 1204.9826,-31.4264"/>
<polygon fill="#000000" stroke="#000000" points="1206.6933,-34.4934 1214.3473,-27.1676 1203.7954,-28.1214 1206.6933,-34.4934"/>
<text text-anchor="middle" x="1238.9475" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge25" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1321.1396,-87.0932C1316.5459,-76.6271 1309.7204,-63.626 1300.9475,-54 1294.9803,-47.4525 1287.575,-41.5658 1280.1523,-36.541"/>
<polygon fill="#000000" stroke="#000000" points="1281.8326,-33.4619 1271.5159,-31.0504 1278.0771,-39.3692 1281.8326,-33.4619"/>
<text text-anchor="middle" x="1361.4475" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M427.0892,-177.4371C451.6111,-165.1179 489.0961,-148.3334 523.9475,-141 683.1765,-107.4952 1094.7074,-144.8648 1255.9475,-123 1261.6731,-122.2236 1267.6021,-121.1669 1273.4875,-119.9518"/>
<polygon fill="#000000" stroke="#000000" points="1274.2998,-123.3569 1283.3076,-117.7792 1272.7876,-116.5221 1274.2998,-123.3569"/>
<text text-anchor="middle" x="560.4475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_personnel -->
<g id="node18" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="1494.9475" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1494.9475" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge7" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1472.6766,-87.4647C1457.4871,-76.3256 1436.4742,-62.4608 1415.9475,-54 1375.5838,-37.3626 1326.5303,-28.0312 1291.5099,-23.0623"/>
<polygon fill="#000000" stroke="#000000" points="1291.9506,-19.5901 1281.5712,-21.7155 1291.0106,-26.5267 1291.9506,-19.5901"/>
<text text-anchor="middle" x="1512.4475" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- clinical_measure_file -->
<g id="node19" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="1828.9475" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="1828.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1761.4007,-177.8968C1740.2772,-172.3529 1717.2081,-165.0983 1696.9475,-156 1685.8145,-151.0005 1685.5257,-144.8579 1673.9475,-141 1557.7446,-102.2811 1519.9282,-142.13 1398.9475,-123 1393.6094,-122.1559 1388.0869,-121.096 1382.5882,-119.9152"/>
<polygon fill="#000000" stroke="#000000" points="1383.2889,-116.4852 1372.7616,-117.6796 1381.736,-123.3108 1383.2889,-116.4852"/>
<text text-anchor="middle" x="1826.4475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge14" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1908.9226,-179.7866C1921.6422,-177.8481 1934.6547,-175.8673 1946.9475,-174 1973.3895,-169.9834 2048.5072,-176.2767 2065.9475,-156 2070.2948,-150.9457 2070.2206,-146.1172 2065.9475,-141 2015.7541,-80.8912 1458.4526,-34.1008 1292.3803,-21.4153"/>
<polygon fill="#000000" stroke="#000000" points="1292.2529,-17.8957 1282.0168,-20.6293 1291.7234,-24.8756 1292.2529,-17.8957"/>
<text text-anchor="middle" x="2119.9475" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- diagnosis -->
<g id="node20" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="734.9475" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="734.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M756.4441,-175.3382C773.2551,-163.3567 797.7588,-148.1086 821.9475,-141 914.5585,-113.7834 1160.4084,-136.7769 1255.9475,-123 1261.6664,-122.1753 1267.5909,-121.0873 1273.4737,-119.8534"/>
<polygon fill="#000000" stroke="#000000" points="1274.2947,-123.2563 1283.2909,-117.6599 1272.7683,-116.4247 1274.2947,-123.2563"/>
<text text-anchor="middle" x="866.4475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- synonym -->
<g id="node21" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2104.9475" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2104.9475" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2106.2697,-260.5891C2107.3219,-230.1201 2104.3659,-169.7266 2067.9475,-141 2038.7558,-117.9738 1435.7762,-128.0997 1398.9475,-123 1393.4367,-122.2369 1387.7358,-121.2089 1382.0708,-120.0289"/>
<polygon fill="#000000" stroke="#000000" points="1382.4844,-116.5349 1371.9612,-117.765 1380.9547,-123.3657 1382.4844,-116.5349"/>
<text text-anchor="middle" x="2144.4475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2053.2849,-276.5606C1891.1685,-268.9383 1378.0216,-245.0602 952.9475,-228 841.8539,-223.5413 562.3005,-230.0902 452.9475,-210 449.2917,-209.3284 445.5452,-208.4556 441.8166,-207.4568"/>
<polygon fill="#000000" stroke="#000000" points="442.6458,-204.0522 432.0636,-204.5701 440.6591,-210.7643 442.6458,-204.0522"/>
<text text-anchor="middle" x="1343.4475" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge2" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2132.8115,-263.6265C2152.0842,-251.5435 2176.7291,-232.9416 2190.9475,-210 2220.0873,-162.9827 2247.6391,-127.4858 2209.9475,-87 2178.3184,-53.026 1480.8962,-26.2244 1292.4967,-19.5856"/>
<polygon fill="#000000" stroke="#000000" points="1292.4815,-16.083 1282.3651,-19.2308 1292.2365,-23.0787 1292.4815,-16.083"/>
<text text-anchor="middle" x="2268.4475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- radiology_file -->
<g id="node22" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1186.9475" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1186.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1188.4047,-173.719C1190.2044,-162.8506 1194.1845,-149.5587 1202.9475,-141 1205.6654,-138.3455 1240.0702,-128.5331 1272.0955,-119.8222"/>
<polygon fill="#000000" stroke="#000000" points="1273.1819,-123.1542 1281.9203,-117.1633 1271.3532,-116.3972 1273.1819,-123.1542"/>
<text text-anchor="middle" x="1261.9475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
</g>
</svg>
</div>
