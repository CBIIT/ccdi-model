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
<svg width="3939pt" height="392pt"
 viewBox="0.00 0.00 3938.74 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3934.7364,-388 3934.7364,4 -4,4"/>
<!-- study_funding -->
<g id="node1" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="623.692" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="623.692" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study -->
<g id="node3" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1425.692" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1425.692" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge42" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M634.8477,-86.9638C643.1554,-75.3018 655.6369,-61.0311 670.692,-54 734.6171,-24.1456 1223.9589,-19.0449 1378.8422,-18.177"/>
<polygon fill="#000000" stroke="#000000" points="1378.9981,-21.6764 1388.9795,-18.1237 1378.9612,-14.6765 1378.9981,-21.6764"/>
<text text-anchor="middle" x="732.692" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- pathology_file -->
<g id="node2" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="665.692" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="665.692" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- sample -->
<g id="node5" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="970.692" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="970.692" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge33" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M653.3286,-347.9644C639.4292,-325.2356 621.2996,-286.1129 641.692,-261 675.7278,-219.0855 832.4373,-201.7145 916.7067,-195.3046"/>
<polygon fill="#000000" stroke="#000000" points="917.1422,-198.7821 926.8589,-194.5587 916.6293,-191.8009 917.1422,-198.7821"/>
<text text-anchor="middle" x="702.692" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- cell_line -->
<g id="node10" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="821.692" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="821.692" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge31" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M660.8769,-347.9954C659.1429,-337.231 659.1739,-323.9514 666.692,-315 693.488,-283.0958 718.1804,-306.7318 758.692,-297 763.6122,-295.8181 768.7248,-294.5034 773.8143,-293.1378"/>
<polygon fill="#000000" stroke="#000000" points="774.8022,-296.4961 783.5166,-290.4704 772.9465,-289.7465 774.8022,-296.4961"/>
<text text-anchor="middle" x="727.692" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pdx -->
<g id="node18" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1085.692" cy="-105" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1085.692" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge32" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M736.8276,-359.5021C779.4076,-355.7683 834.6173,-351.1997 883.692,-348 904.5605,-346.6394 1245.2623,-345.137 1259.692,-330 1288.044,-300.2583 1276.5068,-299.3813 1208.692,-261 1176.22,-242.6217 1151.6041,-270.7774 1126.692,-243 1096.249,-209.0554 1133.4935,-182.9776 1115.692,-141 1113.7684,-136.4639 1111.0759,-132.0592 1108.086,-127.9776"/>
<polygon fill="#000000" stroke="#000000" points="1110.7111,-125.6584 1101.6822,-120.1149 1105.2835,-130.0789 1110.7111,-125.6584"/>
<text text-anchor="middle" x="1187.692" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- radiology_file -->
<g id="node4" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="2601.692" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="2601.692" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- participant -->
<g id="node19" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="2392.692" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="2392.692" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2598.3278,-173.8059C2595.3204,-162.6873 2589.7648,-149.0933 2579.692,-141 2561.7216,-126.561 2507.8391,-117.1703 2462.5025,-111.6125"/>
<polygon fill="#000000" stroke="#000000" points="2462.7235,-108.1144 2452.3819,-110.4168 2461.9021,-115.066 2462.7235,-108.1144"/>
<text text-anchor="middle" x="2650.692" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge40" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M929.1114,-198.4447C894.5101,-204.6212 848.8611,-214.9268 835.692,-228 829.5771,-234.0705 826.064,-242.5437 824.067,-250.8423"/>
<polygon fill="#000000" stroke="#000000" points="820.6182,-250.246 822.3099,-260.7049 827.5097,-251.4738 820.6182,-250.246"/>
<text text-anchor="middle" x="872.192" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge38" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M992.729,-175.9843C1001.1934,-169.787 1010.9243,-162.6068 1019.692,-156 1033.035,-145.9456 1047.7567,-134.595 1059.9042,-125.1588"/>
<polygon fill="#000000" stroke="#000000" points="1062.1124,-127.8753 1067.8542,-118.9713 1057.8129,-122.3513 1062.1124,-127.8753"/>
<text text-anchor="middle" x="1075.192" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge39" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1013.9631,-188.1671C1118.823,-178.9799 1394.8852,-155.3988 1625.692,-141 1880.8168,-125.0842 2184.0784,-112.8133 2320.2231,-107.6567"/>
<polygon fill="#000000" stroke="#000000" points="2320.6587,-111.1429 2330.5196,-107.2683 2320.3948,-104.1479 2320.6587,-111.1429"/>
<text text-anchor="middle" x="1662.192" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cytogenomic_file -->
<g id="node6" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="89.692" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="89.692" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M98.3439,-347.7421C111.0495,-323.2237 137.2574,-280.4903 173.692,-261 181.9283,-256.5941 739.5843,-210.8313 917.072,-196.3609"/>
<polygon fill="#000000" stroke="#000000" points="917.5363,-199.8348 927.2189,-195.534 916.9676,-192.8579 917.5363,-199.8348"/>
<text text-anchor="middle" x="245.192" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;cell_line -->
<g id="edge23" class="edge">
<title>cytogenomic_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M142.1739,-351.3115C187.669,-339.2656 255.4783,-322.9505 315.692,-315 511.0478,-289.2058 564.1405,-328.2878 758.692,-297 764.0267,-296.1421 769.5506,-294.9828 775.01,-293.6636"/>
<polygon fill="#000000" stroke="#000000" points="775.9114,-297.0457 784.7121,-291.1468 774.1536,-290.27 775.9114,-297.0457"/>
<text text-anchor="middle" x="387.192" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;pdx -->
<g id="edge24" class="edge">
<title>cytogenomic_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M91.8942,-347.6095C95.5867,-324.5058 105.1048,-284.9874 128.692,-261 153.9406,-235.3231 168.4211,-239.0585 202.692,-228 444.4865,-149.9785 514.6873,-164.2484 767.692,-141 873.3269,-131.2933 900.7781,-138.6846 1005.692,-123 1020.1655,-120.8362 1035.9147,-117.5078 1049.5814,-114.299"/>
<polygon fill="#000000" stroke="#000000" points="1050.6702,-117.6368 1059.5708,-111.8897 1049.0289,-110.8319 1050.6702,-117.6368"/>
<text text-anchor="middle" x="274.192" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- study_arm -->
<g id="node7" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="778.692" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="778.692" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge30" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M786.2555,-87.1151C792.1808,-75.5207 801.6208,-61.2685 814.692,-54 863.5184,-26.849 1244.4663,-20.0121 1378.907,-18.4364"/>
<polygon fill="#000000" stroke="#000000" points="1379.3157,-21.9321 1389.2756,-18.3196 1379.2368,-14.9325 1379.3157,-21.9321"/>
<text text-anchor="middle" x="863.192" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- study_admin -->
<g id="node8" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="926.692" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="926.692" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge15" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M918.1877,-86.7566C914.5179,-75.9023 912.672,-62.6121 920.692,-54 936.1891,-37.3588 1256.7067,-24.095 1378.917,-19.6246"/>
<polygon fill="#000000" stroke="#000000" points="1379.2182,-23.1161 1389.0849,-19.2563 1378.9647,-16.1207 1379.2182,-23.1161"/>
<text text-anchor="middle" x="977.192" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- molecular_test -->
<g id="node9" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="2772.692" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="2772.692" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2757.5536,-174.2538C2746.6185,-162.7213 2730.8112,-148.4862 2713.692,-141 2670.4548,-122.0925 2545.3282,-112.486 2464.6727,-108.1231"/>
<polygon fill="#000000" stroke="#000000" points="2464.7479,-104.6223 2454.5777,-107.5917 2464.3799,-111.6126 2464.7479,-104.6223"/>
<text text-anchor="middle" x="2801.692" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge13" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M820.0354,-260.6415C819.7274,-250.7439 820.3025,-238.4517 823.692,-228 838.0278,-183.7949 842.4048,-165.8217 881.692,-141 928.7716,-111.2552 954.8566,-145.7376 1005.692,-123 1028.4444,-112.8234 1026.1311,-97.5943 1048.692,-87 1107.0744,-59.5845 1293.2422,-34.1207 1380.1687,-23.3755"/>
<polygon fill="#000000" stroke="#000000" points="1380.7621,-26.8291 1390.2622,-22.139 1379.9108,-19.881 1380.7621,-26.8291"/>
<text text-anchor="middle" x="922.192" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M859.8228,-267.2284C876.665,-261.2066 896.3146,-253.0183 912.692,-243 924.9667,-235.4914 937.1423,-225.3162 947.145,-216.0293"/>
<polygon fill="#000000" stroke="#000000" points="949.8542,-218.2813 954.6614,-208.8399 945.0156,-213.2227 949.8542,-218.2813"/>
<text text-anchor="middle" x="974.192" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M869.0634,-273.722C908.3016,-269.5626 965.5503,-263.9836 1015.692,-261 1053.5826,-258.7454 1665.1125,-260.6974 1698.692,-243 1732.1956,-225.3426 1717.3339,-195.2353 1748.692,-174 1798.4066,-140.334 1820.4027,-150.4718 1879.692,-141 1962.4675,-127.7761 2199.8193,-114.5828 2320.4471,-108.49"/>
<polygon fill="#000000" stroke="#000000" points="2320.8784,-111.9728 2330.6902,-107.9755 2320.5272,-104.9816 2320.8784,-111.9728"/>
<text text-anchor="middle" x="1789.192" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- diagnosis -->
<g id="node11" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="2925.692" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="2925.692" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2912.0314,-174.5645C2901.761,-162.8573 2886.5978,-148.2879 2869.692,-141 2833.5302,-125.4111 2589.118,-113.1604 2464.8869,-107.8585"/>
<polygon fill="#000000" stroke="#000000" points="2464.8407,-104.3536 2454.7018,-107.4279 2464.545,-111.3473 2464.8407,-104.3536"/>
<text text-anchor="middle" x="2937.192" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- study_personnel -->
<g id="node12" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="3699.692" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="3699.692" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge5" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3673.5545,-87.645C3653.8859,-75.647 3625.7723,-60.6868 3598.692,-54 3492.011,-27.6578 1779.6291,-19.4454 1472.6277,-18.1818"/>
<polygon fill="#000000" stroke="#000000" points="1472.3187,-14.6806 1462.3045,-18.1398 1472.2901,-21.6806 1472.3187,-14.6806"/>
<text text-anchor="middle" x="3705.192" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- publication -->
<g id="node13" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="3867.692" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="3867.692" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge2" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3845.3332,-87.9011C3828.1427,-75.8629 3803.2502,-60.7393 3778.692,-54 3663.5271,-22.3964 1795.4226,-18.4913 1472.9279,-18.0521"/>
<polygon fill="#000000" stroke="#000000" points="1472.5468,-14.5517 1462.5422,-18.0385 1472.5376,-21.5517 1472.5468,-14.5517"/>
<text text-anchor="middle" x="3862.692" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- follow_up -->
<g id="node14" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="3053.692" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="3053.692" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3032.1622,-175.3695C3013.6797,-161.2521 2989.1748,-142.9718 2983.692,-141 2936.1069,-123.8862 2612.4888,-111.8116 2465.3047,-107.1408"/>
<polygon fill="#000000" stroke="#000000" points="2465.1237,-103.6335 2455.0186,-106.8174 2464.9036,-110.63 2465.1237,-103.6335"/>
<text text-anchor="middle" x="3049.692" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node15" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1323.692" cy="-366" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="1323.692" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1322.2691,-347.8761C1320.6342,-337.333 1317.1403,-324.3272 1309.692,-315 1277.9288,-275.2243 1256.7423,-277.7983 1208.692,-261 1166.8888,-246.3857 1153.4246,-254.6197 1110.692,-243 1076.417,-233.6801 1038.6332,-219.6857 1010.9653,-208.7126"/>
<polygon fill="#000000" stroke="#000000" points="1012.2075,-205.4399 1001.6231,-204.9699 1009.6042,-211.9378 1012.2075,-205.4399"/>
<text text-anchor="middle" x="1401.192" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge20" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1232.5216,-352.4669C1189.9805,-345.9792 1138.6932,-337.911 1092.692,-330 1017.1176,-317.0031 930.0222,-300.3044 875.4094,-289.6243"/>
<polygon fill="#000000" stroke="#000000" points="875.7532,-286.1252 865.2668,-287.637 874.4071,-292.9946 875.7532,-286.1252"/>
<text text-anchor="middle" x="1201.192" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge22" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1390.8917,-350.284C1439.4635,-337.4058 1499.0155,-317.9443 1513.692,-297 1522.874,-283.8969 1521.8595,-274.7584 1513.692,-261 1505.1639,-246.634 1490.1794,-256.7514 1480.692,-243 1454.7069,-205.3357 1499.7235,-172.6663 1466.692,-141 1442.2696,-117.5869 1215.5175,-108.641 1123.8619,-105.9625"/>
<polygon fill="#000000" stroke="#000000" points="1123.7261,-102.4573 1113.6312,-105.6733 1123.5283,-109.4545 1123.7261,-102.4573"/>
<text text-anchor="middle" x="1589.192" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- medical_history -->
<g id="node16" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="3211.692" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="3211.692" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3166.894,-176.5799C3151.621,-170.7727 3134.6363,-163.6938 3119.692,-156 3108.8416,-150.4138 3108.2975,-144.7752 3096.692,-141 3037.879,-121.8685 2633.0021,-110.5042 2465.2491,-106.5694"/>
<polygon fill="#000000" stroke="#000000" points="2465.1081,-103.0652 2455.0295,-106.332 2464.9455,-110.0634 2465.1081,-103.0652"/>
<text text-anchor="middle" x="3187.692" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- synonym -->
<g id="node17" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1845.692" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1845.692" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge26" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1898.0917,-278.9001C2178.8824,-278.1142 3494.9443,-271.169 3553.692,-210 3574.9345,-187.8821 3566.5063,-168.8611 3553.692,-141 3538.2822,-107.4957 3525.061,-100.3706 3490.692,-87 3393.5388,-49.2045 1769.6703,-23.1488 1472.2706,-18.6825"/>
<polygon fill="#000000" stroke="#000000" points="1472.3067,-15.1827 1462.2555,-18.5327 1472.202,-22.1819 1472.3067,-15.1827"/>
<text text-anchor="middle" x="3602.192" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge28" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1809.7297,-265.9697C1768.908,-251.2229 1707.2213,-229.0909 1701.692,-228 1572.1925,-202.4502 1171.4124,-194.66 1024.9775,-192.6314"/>
<polygon fill="#000000" stroke="#000000" points="1024.9273,-189.1305 1014.881,-192.4951 1024.8328,-196.1299 1024.9273,-189.1305"/>
<text text-anchor="middle" x="1787.192" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1841.5394,-260.8952C1835.9197,-234.3203 1827.7768,-186.5404 1838.692,-174 1869.8682,-138.1821 2177.9609,-116.7677 2320.7354,-108.6943"/>
<polygon fill="#000000" stroke="#000000" points="2321.3475,-112.1656 2331.1367,-108.1132 2320.957,-105.1765 2321.3475,-112.1656"/>
<text text-anchor="middle" x="1881.192" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge19" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1111.8067,-98.3177C1170.2013,-83.3756 1311.7944,-47.1444 1383.1264,-28.8918"/>
<polygon fill="#000000" stroke="#000000" points="1384.3025,-32.2037 1393.1227,-26.3339 1382.5672,-25.4222 1384.3025,-32.2037"/>
<text text-anchor="middle" x="1300.692" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1062.1659,-115.3169C1055.606,-118.0032 1048.4296,-120.7672 1041.692,-123 1011.1996,-133.105 991.6239,-115.8083 971.692,-141 966.7252,-147.2776 965.1411,-155.4803 965.1702,-163.4661"/>
<polygon fill="#000000" stroke="#000000" points="961.6995,-163.9713 965.9889,-173.659 968.677,-163.4109 961.6995,-163.9713"/>
<text text-anchor="middle" x="995.692" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge4" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2332.9316,-99.6234C2155.0159,-83.6165 1631.2905,-36.4975 1472.1099,-22.1762"/>
<polygon fill="#000000" stroke="#000000" points="1471.9968,-18.6519 1461.7234,-21.2417 1471.3695,-25.6238 1471.9968,-18.6519"/>
<text text-anchor="middle" x="2018.192" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- family_relationship -->
<g id="node20" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="2032.692" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="2032.692" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2053.4766,-174.1372C2067.9748,-162.7082 2088.3073,-148.6394 2108.692,-141 2146.5071,-126.8284 2250.7548,-116.1422 2321.8546,-110.227"/>
<polygon fill="#000000" stroke="#000000" points="2322.4113,-113.6932 2332.0924,-109.389 2321.8402,-106.7166 2322.4113,-113.6932"/>
<text text-anchor="middle" x="2188.192" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- sequencing_file -->
<g id="node21" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="285.692" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="285.692" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M286.3347,-347.7298C287.6715,-336.8654 291.126,-323.574 299.692,-315 363.5542,-251.0784 407.732,-281.6732 495.692,-261 570.1917,-243.4904 589.0795,-239.8127 664.692,-228 752.8716,-214.224 856.0909,-203.113 917.2891,-197.0449"/>
<polygon fill="#000000" stroke="#000000" points="917.8679,-200.505 927.4773,-196.0429 917.1827,-193.5386 917.8679,-200.505"/>
<text text-anchor="middle" x="562.192" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge7" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M348.0782,-353.9516C382.0393,-347.2318 424.7525,-338.5193 462.692,-330 489.9325,-323.8832 496.1245,-319.4144 523.692,-315 627.1247,-298.4373 655.5851,-315.4826 758.692,-297 764.0105,-296.0466 769.5242,-294.8274 774.9777,-293.4737"/>
<polygon fill="#000000" stroke="#000000" points="775.8947,-296.8516 784.6736,-290.9203 774.112,-290.0824 775.8947,-296.8516"/>
<text text-anchor="middle" x="590.192" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge8" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M283.9354,-347.7618C283.5095,-337.8996 283.8334,-325.6027 286.692,-315 293.8391,-288.4916 295.0519,-277.8962 316.692,-261 362.2248,-225.4491 458.7981,-206.6492 857.692,-141 923.075,-130.2394 940.3979,-134.2869 1005.692,-123 1020.1125,-120.5073 1035.8512,-117.1141 1049.5244,-113.9455"/>
<polygon fill="#000000" stroke="#000000" points="1050.5937,-117.2894 1059.5217,-111.5849 1048.985,-110.4767 1050.5937,-117.2894"/>
<text text-anchor="middle" x="457.192" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- exposure -->
<g id="node22" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="2203.692" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="2203.692" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2231.6146,-176.4886C2251.0177,-165.9536 2277.6143,-151.9924 2301.692,-141 2315.5054,-134.6937 2330.7652,-128.4029 2344.778,-122.8853"/>
<polygon fill="#000000" stroke="#000000" points="2346.1982,-126.0883 2354.2467,-119.1983 2343.6582,-119.5654 2346.1982,-126.0883"/>
<text text-anchor="middle" x="2345.192" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- clinical_measure_file -->
<g id="node23" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="3435.692" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="3435.692" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge41" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3506.6243,-178.3397C3533.295,-170.1661 3553.7145,-158.0022 3537.692,-141 3523.7128,-126.1659 2093.0415,-55.1704 2072.692,-54 1847.6934,-41.0596 1578.6355,-26.3268 1472.2548,-20.5311"/>
<polygon fill="#000000" stroke="#000000" points="1472.3518,-17.0313 1462.1762,-19.9822 1471.9711,-24.0209 1472.3518,-17.0313"/>
<text text-anchor="middle" x="3400.692" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3356.9227,-179.6033C3331.3625,-174.1012 3303.2726,-166.4404 3278.692,-156 3267.4593,-151.229 3267.3151,-144.7206 3255.692,-141 3181.5482,-117.2663 2659.8401,-108.3489 2465.4552,-105.8274"/>
<polygon fill="#000000" stroke="#000000" points="2465.3838,-102.3263 2455.3399,-105.6981 2465.2943,-109.3257 2465.3838,-102.3263"/>
<text text-anchor="middle" x="3408.192" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- methylation_array_file -->
<g id="node24" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1008.692" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1008.692" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge36" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1011.9189,-347.8127C1017.3364,-315.2811 1026.7304,-248.6032 1016.692,-228 1014.0172,-222.5101 1010.0555,-217.6111 1005.5603,-213.3286"/>
<polygon fill="#000000" stroke="#000000" points="1007.5455,-210.4266 997.6246,-206.7082 1003.0612,-215.8018 1007.5455,-210.4266"/>
<text text-anchor="middle" x="1113.192" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge34" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M902.8469,-358.7335C862.9016,-353.5959 824.0772,-344.8535 811.692,-330 806.21,-323.4253 806.1647,-314.7191 808.2795,-306.3643"/>
<polygon fill="#000000" stroke="#000000" points="811.6034,-307.4614 811.5578,-296.8666 804.9865,-305.1773 811.6034,-307.4614"/>
<text text-anchor="middle" x="903.192" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge35" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1101.852,-355.2984C1180.7508,-346.0132 1281.5984,-333.5234 1284.692,-330 1294.8893,-318.3863 1293.2259,-284.2029 1252.692,-228 1216.4348,-177.7269 1194.3345,-176.7396 1143.692,-141 1134.5931,-134.5787 1124.3592,-128.0209 1115.0496,-122.292"/>
<polygon fill="#000000" stroke="#000000" points="1116.8384,-119.2836 1106.4742,-117.0849 1113.2052,-125.2669 1116.8384,-119.2836"/>
<text text-anchor="middle" x="1354.192" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- therapeutic_procedure -->
<g id="node25" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="2392.692" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="2392.692" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge37" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2392.692,-173.9735C2392.692,-162.1918 2392.692,-146.5607 2392.692,-133.1581"/>
<polygon fill="#000000" stroke="#000000" points="2396.1921,-133.0033 2392.692,-123.0034 2389.1921,-133.0034 2396.1921,-133.0033"/>
<text text-anchor="middle" x="2485.692" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
</g>
</svg>
</div>
