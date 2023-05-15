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
<svg width="2106pt" height="305pt"
 viewBox="0.00 0.00 2106.04 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 2102.0398,-301 2102.0398,4 -4,4"/>
<!-- publication -->
<g id="node1" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="525.2451" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="525.2451" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- study -->
<g id="node18" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1110.2451" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1110.2451" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge3" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M550.8091,-88.3517C570.3498,-76.5433 598.4074,-61.5101 625.2451,-54 706.8027,-31.1775 958.3677,-22.017 1063.4098,-19.1214"/>
<polygon fill="#000000" stroke="#000000" points="1063.7986,-22.6123 1073.701,-18.8449 1063.6106,-15.6148 1063.7986,-22.6123"/>
<text text-anchor="middle" x="676.2451" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- study_personnel -->
<g id="node2" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="693.2451" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="693.2451" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge14" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M709.3028,-87.1965C720.8607,-75.6384 737.4901,-61.3962 755.2451,-54 809.8101,-31.2697 980.3006,-22.4229 1063.5583,-19.3918"/>
<polygon fill="#000000" stroke="#000000" points="1063.8755,-22.883 1073.7465,-19.0342 1063.6299,-15.8873 1063.8755,-22.883"/>
<text text-anchor="middle" x="824.7451" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- study_admin -->
<g id="node3" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="868.2451" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="868.2451" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge17" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M881.0981,-87.1222C890.187,-75.8384 903.3686,-61.9411 918.2451,-54 943.0345,-40.7673 1016.1822,-29.5815 1064.6948,-23.3373"/>
<polygon fill="#000000" stroke="#000000" points="1065.1638,-26.8059 1074.6467,-22.0809 1064.287,-19.861 1065.1638,-26.8059"/>
<text text-anchor="middle" x="974.7451" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- molecular_test -->
<g id="node4" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="208.2451" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="208.2451" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- participant -->
<g id="node14" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1192.2451" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1192.2451" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M239.2993,-175.2017C263.3497,-163.1486 297.9093,-147.8708 330.2451,-141 502.0115,-104.5028 946.2153,-146.4393 1120.2451,-123 1126.0532,-122.2177 1132.0703,-121.1452 1138.0387,-119.9103"/>
<polygon fill="#000000" stroke="#000000" points="1138.9878,-123.2849 1147.9919,-117.7013 1137.471,-116.4512 1138.9878,-123.2849"/>
<text text-anchor="middle" x="394.2451" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- diagnosis -->
<g id="node5" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1127.2451" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1127.2451" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1126.5189,-173.6896C1126.9435,-163.3362 1128.9435,-150.5862 1135.2451,-141 1139.0032,-135.2831 1144.0169,-130.3 1149.5167,-126.0137"/>
<polygon fill="#000000" stroke="#000000" points="1151.623,-128.8121 1157.833,-120.228 1147.6253,-123.0659 1151.623,-128.8121"/>
<text text-anchor="middle" x="1179.7451" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- family_relationship -->
<g id="node6" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="594.2451" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="594.2451" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M614.7859,-174.3264C629.8729,-162.507 651.457,-147.9013 673.2451,-141 768.0183,-110.9808 1021.8405,-137.1297 1120.2451,-123 1125.9644,-122.1788 1131.8893,-121.0929 1137.7723,-119.8604"/>
<polygon fill="#000000" stroke="#000000" points="1138.5927,-123.2635 1147.5897,-117.6684 1137.0673,-116.4317 1138.5927,-123.2635"/>
<text text-anchor="middle" x="752.7451" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- study_funding -->
<g id="node7" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="1034.2451" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="1034.2451" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge23" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1032.8042,-87.0031C1032.8587,-76.505 1034.5593,-63.5019 1041.2451,-54 1048.1608,-44.1713 1058.6003,-36.8266 1069.2802,-31.4264"/>
<polygon fill="#000000" stroke="#000000" points="1070.9908,-34.4934 1078.6448,-27.1676 1068.093,-28.1214 1070.9908,-34.4934"/>
<text text-anchor="middle" x="1103.2451" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- exposure -->
<g id="node8" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1253.2451" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1253.2451" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1246.0416,-173.722C1241.6392,-163.6204 1235.4701,-151.1078 1228.2451,-141 1225.4374,-137.0721 1222.1889,-133.1813 1218.8154,-129.4907"/>
<polygon fill="#000000" stroke="#000000" points="1221.2827,-127.0072 1211.8166,-122.2486 1216.249,-131.8717 1221.2827,-127.0072"/>
<text text-anchor="middle" x="1280.7451" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- synonym -->
<g id="node9" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1507.2451" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1507.2451" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- sample -->
<g id="node12" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1010.2451" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1010.2451" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1471.0327,-265.8511C1452.2885,-259.0401 1429.0346,-250.5828 1408.2451,-243 1390.0164,-236.3512 1386.2425,-231.9487 1367.2451,-228 1234.7296,-200.4563 1196.0728,-235.9962 1063.2451,-210 1059.5973,-209.2861 1055.8564,-208.3837 1052.1316,-207.365"/>
<polygon fill="#000000" stroke="#000000" points="1052.9684,-203.9621 1042.3846,-204.4467 1050.9605,-210.668 1052.9684,-203.9621"/>
<text text-anchor="middle" x="1450.7451" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1508.8404,-260.554C1510.3121,-230.5876 1508.3416,-171.6072 1474.2451,-141 1458.801,-127.1364 1341.9171,-115.9497 1263.5572,-109.907"/>
<polygon fill="#000000" stroke="#000000" points="1263.4846,-106.3915 1253.2483,-109.1244 1262.9546,-113.3714 1263.4846,-106.3915"/>
<text text-anchor="middle" x="1548.7451" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge9" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1558.2941,-275.0071C1647.9322,-267.1185 1828.9017,-247.0086 1879.2451,-210 1926.2704,-175.4306 1964.7359,-129.9755 1925.2451,-87 1873.0663,-30.217 1322.6016,-20.1178 1157.0697,-18.3613"/>
<polygon fill="#000000" stroke="#000000" points="1156.7672,-14.8581 1146.7324,-18.2572 1156.6967,-21.8578 1156.7672,-14.8581"/>
<text text-anchor="middle" x="1980.7451" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- radiology_file -->
<g id="node10" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1398.2451" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1398.2451" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1378.3975,-174.4362C1365.038,-163.4289 1346.5739,-149.7233 1328.2451,-141 1305.5709,-130.2086 1279.1734,-122.2786 1255.7005,-116.6522"/>
<polygon fill="#000000" stroke="#000000" points="1256.3696,-113.2148 1245.8391,-114.3803 1254.7981,-120.0361 1256.3696,-113.2148"/>
<text text-anchor="middle" x="1411.2451" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node11" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="708.2451" cy="-279" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="708.2451" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M708.6414,-260.8453C709.9211,-249.5956 713.5629,-235.8417 723.2451,-228 763.7734,-195.1754 906.1528,-220.4679 957.2451,-210 960.8864,-209.254 964.6228,-208.329 968.3446,-207.2953"/>
<polygon fill="#000000" stroke="#000000" points="969.5258,-210.5948 978.0868,-204.353 967.5019,-203.8937 969.5258,-210.5948"/>
<text text-anchor="middle" x="831.7451" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1020.604,-174.4086C1028.0539,-163.2457 1039.0849,-149.3756 1052.2451,-141 1054.1279,-139.8017 1097.1659,-128.8145 1135.0292,-119.2899"/>
<polygon fill="#000000" stroke="#000000" points="1136.1768,-122.6105 1145.0228,-116.7796 1134.4714,-115.8214 1136.1768,-122.6105"/>
<text text-anchor="middle" x="1088.7451" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- follow_up -->
<g id="node13" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="55.2451" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="55.2451" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M85.9719,-177.0329C112.9811,-164.7234 153.7226,-148.1802 191.2451,-141 394.0486,-102.192 915.563,-150.2127 1120.2451,-123 1126.0545,-122.2276 1132.0724,-121.1615 1138.0414,-119.9304"/>
<polygon fill="#000000" stroke="#000000" points="1138.9888,-123.3055 1147.9951,-117.7255 1137.4748,-116.4711 1138.9888,-123.3055"/>
<text text-anchor="middle" x="236.2451" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge15" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1185.4372,-87.0932C1180.8435,-76.6271 1174.018,-63.626 1165.2451,-54 1159.2779,-47.4525 1151.8725,-41.5658 1144.4499,-36.541"/>
<polygon fill="#000000" stroke="#000000" points="1146.1302,-33.4619 1135.8134,-31.0504 1142.3746,-39.3692 1146.1302,-33.4619"/>
<text text-anchor="middle" x="1226.7451" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- pdx -->
<g id="node15" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="892.2451" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="892.2451" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M910.6826,-265.4063C929.3374,-251.6523 958.4781,-230.1672 980.4223,-213.988"/>
<polygon fill="#000000" stroke="#000000" points="982.7674,-216.6074 988.7393,-207.856 978.6134,-210.9732 982.7674,-216.6074"/>
<text text-anchor="middle" x="983.2451" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- methylation_array_file -->
<g id="node16" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1054.2451" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1054.2451" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1045.1283,-260.9735C1038.9518,-248.7609 1030.6835,-232.4123 1023.747,-218.697"/>
<polygon fill="#000000" stroke="#000000" points="1026.8362,-217.0498 1019.1997,-209.7057 1020.5896,-220.209 1026.8362,-217.0498"/>
<text text-anchor="middle" x="1126.7451" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node17" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="1761.2451" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="1761.2451" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1670.5964,-182.0423C1616.3444,-175.3097 1553.0632,-165.8738 1527.2451,-156 1515.8462,-151.6406 1515.7243,-145.1433 1504.2451,-141 1461.4196,-125.5425 1341.6932,-114.9322 1263.6236,-109.4231"/>
<polygon fill="#000000" stroke="#000000" points="1263.589,-105.9123 1253.3708,-108.7119 1263.1046,-112.8956 1263.589,-105.9123"/>
<text text-anchor="middle" x="1656.7451" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge22" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1779.421,-174.2505C1787.883,-163.8401 1794.4582,-150.8423 1786.2451,-141 1745.4226,-92.0795 1301.8859,-39.1424 1156.2661,-22.9676"/>
<polygon fill="#000000" stroke="#000000" points="1156.2283,-19.4422 1145.9044,-21.823 1155.4596,-26.3999 1156.2283,-19.4422"/>
<text text-anchor="middle" x="1835.2451" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- medical_history -->
<g id="node19" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="391.2451" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="391.2451" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M420.051,-175.0025C442.0253,-163.016 473.4848,-147.9127 503.2451,-141 636.8574,-109.9646 984.3623,-141.7433 1120.2451,-123 1125.9689,-122.2105 1131.8967,-121.1452 1137.7814,-119.9251"/>
<polygon fill="#000000" stroke="#000000" points="1138.5961,-123.3295 1147.6007,-117.7468 1137.08,-116.4957 1138.5961,-123.3295"/>
<text text-anchor="middle" x="571.2451" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- therapeutic_procedure -->
<g id="node20" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="830.2451" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="830.2451" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M830.9887,-173.7785C832.4854,-162.5013 836.3962,-148.742 846.2451,-141 870.2314,-122.1448 1090.1022,-127.7189 1120.2451,-123 1125.7348,-122.1406 1131.4181,-121.0599 1137.074,-119.857"/>
<polygon fill="#000000" stroke="#000000" points="1138.1911,-123.1931 1147.1774,-117.5809 1136.6527,-116.3642 1138.1911,-123.1931"/>
<text text-anchor="middle" x="939.2451" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- study_arm -->
<g id="node21" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2038.2451" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2038.2451" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge20" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2019.7913,-87.8479C2005.7269,-75.9509 1985.2569,-61.028 1964.2451,-54 1887.6927,-28.3948 1324.3475,-20.3091 1156.9957,-18.4589"/>
<polygon fill="#000000" stroke="#000000" points="1156.8209,-14.9569 1146.7836,-18.3484 1156.7451,-21.9565 1156.8209,-14.9569"/>
<text text-anchor="middle" x="2040.7451" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- pathology_file -->
<g id="node22" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1264.2451" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1264.2451" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1254.2486,-260.793C1246.9517,-249.3702 1235.955,-235.4418 1222.2451,-228 1159.7413,-194.0728 1132.648,-225.5245 1063.2451,-210 1059.6681,-209.1999 1055.9947,-208.2448 1052.3308,-207.1977"/>
<polygon fill="#000000" stroke="#000000" points="1053.3142,-203.8385 1042.7275,-204.2547 1051.2631,-210.5313 1053.3142,-203.8385"/>
<text text-anchor="middle" x="1302.2451" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- sequencing_file -->
<g id="node23" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="469.2451" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="469.2451" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M497.1419,-261.9003C518.0815,-250.0294 547.9032,-235.1161 576.2451,-228 740.6639,-186.7176 790.6879,-241.567 957.2451,-210 960.8971,-209.3079 964.6409,-208.4207 968.3677,-207.4123"/>
<polygon fill="#000000" stroke="#000000" points="969.5318,-210.7176 978.1178,-204.5102 967.5349,-204.0085 969.5318,-210.7176"/>
<text text-anchor="middle" x="642.7451" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
</g>
</svg>
</div>
