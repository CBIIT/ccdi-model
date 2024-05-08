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
<svg width="3179pt" height="305pt"
 viewBox="0.00 0.00 3178.98 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 3174.9815,-301 3174.9815,4 -4,4"/>
<!-- study_admin -->
<g id="node1" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="70.1938" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="70.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study -->
<g id="node10" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="733.1938" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="733.1938" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge24" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M74.5138,-86.7545C78.2421,-75.3155 84.8724,-61.3834 96.1938,-54 120.8307,-37.9326 543.2179,-23.7417 686.2683,-19.377"/>
<polygon fill="#000000" stroke="#000000" points="686.583,-22.8691 696.4724,-19.0679 686.371,-15.8723 686.583,-22.8691"/>
<text text-anchor="middle" x="152.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- sequencing_file -->
<g id="node2" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2427.1938" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="2427.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sample -->
<g id="node21" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2243.1938" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2243.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2423.7504,-260.9031C2420.7113,-249.8232 2415.1503,-236.236 2405.1938,-228 2388.6677,-214.3297 2336.571,-204.3838 2295.8671,-198.4539"/>
<polygon fill="#000000" stroke="#000000" points="2296.1835,-194.964 2285.7927,-197.033 2295.2058,-201.8954 2296.1835,-194.964"/>
<text text-anchor="middle" x="2482.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- pathology_file -->
<g id="node3" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2604.1938" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2604.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2591.1868,-260.7753C2581.9596,-249.3451 2568.5242,-235.415 2553.1938,-228 2509.4046,-206.8201 2374.5397,-197.6409 2297.8992,-194.0474"/>
<polygon fill="#000000" stroke="#000000" points="2297.6347,-190.5319 2287.4868,-193.5767 2297.3186,-197.5248 2297.6347,-190.5319"/>
<text text-anchor="middle" x="2634.1938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- cytogenomic_file -->
<g id="node4" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="2788.1938" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="2788.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2764.6065,-261.6075C2747.3994,-249.9205 2723.0153,-235.3576 2699.1938,-228 2625.6535,-205.286 2402.0351,-196.3294 2297.7806,-193.3191"/>
<polygon fill="#000000" stroke="#000000" points="2297.5669,-189.8119 2287.4725,-193.0297 2297.3703,-196.8091 2297.5669,-189.8119"/>
<text text-anchor="middle" x="2803.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- study_arm -->
<g id="node5" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="218.1938" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="218.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge2" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M213.0005,-86.6575C211.1243,-75.7658 211.1384,-62.4712 219.1938,-54 235.1788,-37.1897 562.7963,-23.9834 686.4766,-19.5793"/>
<polygon fill="#000000" stroke="#000000" points="686.8879,-23.067 696.7583,-19.2167 686.6412,-16.0714 686.8879,-23.067"/>
<text text-anchor="middle" x="267.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- molecular_test -->
<g id="node6" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1157.1938" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1157.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- participant -->
<g id="node14" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1157.1938" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1157.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1157.1938,-173.9735C1157.1938,-162.1918 1157.1938,-146.5607 1157.1938,-133.1581"/>
<polygon fill="#000000" stroke="#000000" points="1160.6939,-133.0033 1157.1938,-123.0034 1153.6939,-133.0034 1160.6939,-133.0033"/>
<text text-anchor="middle" x="1221.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node7" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="3033.1938" cy="-279" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="3033.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2991.1751,-261.7438C2960.6564,-250.0412 2918.0658,-235.4022 2879.1938,-228 2768.525,-206.9259 2431.195,-196.5941 2298.0635,-193.2538"/>
<polygon fill="#000000" stroke="#000000" points="2297.7887,-189.746 2287.7052,-192.9977 2297.6156,-196.7439 2297.7887,-189.746"/>
<text text-anchor="middle" x="3043.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- family_relationship -->
<g id="node8" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1355.1938" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1355.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1336.3466,-174.1855C1323.8319,-163.2182 1306.563,-149.6504 1289.1938,-141 1282.1123,-137.4732 1246.6553,-127.8682 1214.2728,-119.466"/>
<polygon fill="#000000" stroke="#000000" points="1214.9141,-116.0168 1204.3566,-116.9051 1213.1637,-122.7945 1214.9141,-116.0168"/>
<text text-anchor="middle" x="1391.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- medical_history -->
<g id="node9" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1558.1938" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1558.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1536.3937,-174.5505C1520.4396,-162.8367 1497.7293,-148.2651 1475.1938,-141 1370.4342,-107.2272 1336.8477,-140.5923 1228.1938,-123 1222.8588,-122.1362 1217.3384,-121.0631 1211.8411,-119.874"/>
<polygon fill="#000000" stroke="#000000" points="1212.5445,-116.4446 1202.016,-117.6286 1210.9848,-123.2687 1212.5445,-116.4446"/>
<text text-anchor="middle" x="1574.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- survival -->
<g id="node11" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1011.1938" cy="-192" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1011.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1029.2239,-175.1891C1041.3161,-164.4909 1057.9474,-150.8467 1074.1938,-141 1085.1106,-134.3834 1097.4614,-128.3396 1109.2353,-123.1718"/>
<polygon fill="#000000" stroke="#000000" points="1110.6858,-126.3583 1118.5157,-119.2208 1107.9438,-119.9177 1110.6858,-126.3583"/>
<text text-anchor="middle" x="1113.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- clinical_measure_file -->
<g id="node12" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="715.1938" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="715.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge29" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M638.2177,-179.2406C624.8964,-177.2952 611.1626,-175.4547 598.1938,-174 570.0771,-170.8463 364.9804,-175.194 344.1938,-156 321.6042,-135.1411 319.4162,-110.5421 339.1938,-87 383.1094,-34.7252 592.0035,-22.0465 686.5342,-18.9773"/>
<polygon fill="#000000" stroke="#000000" points="686.7788,-22.4716 696.6685,-18.6711 686.5673,-15.4748 686.7788,-22.4716"/>
<text text-anchor="middle" x="425.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M691.5018,-174.2309C680.5665,-163.9374 671.8602,-151.0661 681.1938,-141 687.9745,-133.6871 953.8024,-117.011 1085.1868,-109.1922"/>
<polygon fill="#000000" stroke="#000000" points="1085.7822,-112.6631 1095.5573,-108.5768 1085.3675,-105.6754 1085.7822,-112.6631"/>
<text text-anchor="middle" x="767.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- publication -->
<g id="node13" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="583.1938" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="583.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge7" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M571.9571,-86.801C567.0048,-76.2312 563.7947,-63.2238 571.1938,-54 585.4751,-36.1966 644.1298,-26.641 686.763,-21.9434"/>
<polygon fill="#000000" stroke="#000000" points="687.3662,-25.3995 696.948,-20.8785 686.6382,-18.4374 687.3662,-25.3995"/>
<text text-anchor="middle" x="622.1938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge6" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1106.0495,-94.5058C1021.9435,-77.2482 855.8966,-43.1772 776.9165,-26.9714"/>
<polygon fill="#000000" stroke="#000000" points="777.3196,-23.4813 766.8201,-24.8997 775.9125,-30.3384 777.3196,-23.4813"/>
<text text-anchor="middle" x="1020.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- diagnosis -->
<g id="node15" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1995.1938" cy="-279" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1995.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1988.2879,-260.9672C1974.7371,-226.6631 1943.9998,-154.2386 1921.1938,-141 1887.8859,-121.6651 1266.3452,-128.2647 1228.1938,-123 1222.6826,-122.2395 1216.9815,-121.2132 1211.3163,-120.0342"/>
<polygon fill="#000000" stroke="#000000" points="1211.7296,-116.5402 1201.2066,-117.7715 1210.2007,-123.3712 1211.7296,-116.5402"/>
<text text-anchor="middle" x="2009.6938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2030.6205,-265.2534C2047.7323,-258.5838 2068.5511,-250.4261 2087.1938,-243 2103.6785,-236.4335 2107.462,-233.9085 2124.1938,-228 2147.8442,-219.6483 2174.5429,-211.461 2196.6495,-205.0098"/>
<polygon fill="#000000" stroke="#000000" points="2197.8222,-208.3141 2206.4561,-202.1735 2195.8773,-201.5897 2197.8222,-208.3141"/>
<text text-anchor="middle" x="2168.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- study_funding -->
<g id="node16" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="779.1938" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="779.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge17" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M769.6625,-86.9735C763.2053,-74.7609 754.5612,-58.4123 747.3094,-44.697"/>
<polygon fill="#000000" stroke="#000000" points="750.3238,-42.9101 742.5554,-35.7057 744.1355,-46.182 750.3238,-42.9101"/>
<text text-anchor="middle" x="820.1938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- synonym -->
<g id="node17" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="860.1938" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="860.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge11" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M808.7303,-275.9092C684.1912,-267.907 374.5505,-244.6863 344.1938,-210 320.2404,-182.6303 354.0956,-153.6562 388.1938,-141 443.9453,-120.3068 602.9942,-151.4895 655.1938,-123 671.8312,-113.9196 699.9373,-72.0341 717.4805,-43.988"/>
<polygon fill="#000000" stroke="#000000" points="720.4919,-45.773 722.7773,-35.4275 714.5392,-42.0897 720.4919,-45.773"/>
<text text-anchor="middle" x="430.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M855.9809,-261.0098C851.7334,-237.966 848.4287,-198.1305 869.1938,-174 897.3575,-141.2716 1012.5361,-121.7874 1088.4272,-112.2567"/>
<polygon fill="#000000" stroke="#000000" points="1088.901,-115.7249 1098.4002,-111.0329 1088.0483,-108.7771 1088.901,-115.7249"/>
<text text-anchor="middle" x="911.6938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M912.0428,-276.7857C1078.8911,-269.4966 1616.9128,-244.7176 2061.1938,-210 2104.5542,-206.6117 2153.6197,-201.6959 2189.8709,-197.8574"/>
<polygon fill="#000000" stroke="#000000" points="2190.6412,-201.2952 2200.2138,-196.7546 2189.899,-194.3346 2190.6412,-201.2952"/>
<text text-anchor="middle" x="1840.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study_personnel -->
<g id="node18" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="1324.1938" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1324.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1266.1218,-91.4391C1215.8409,-80.0982 1141.042,-64.1845 1075.1938,-54 969.9038,-37.7151 845.2194,-26.6408 779.3425,-21.4258"/>
<polygon fill="#000000" stroke="#000000" points="779.5291,-17.9298 769.2866,-20.6393 778.9832,-24.9085 779.5291,-17.9298"/>
<text text-anchor="middle" x="1226.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- pdx -->
<g id="node19" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2097.1938" cy="-105" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2097.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge14" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2069.3119,-103.2108C1966.8577,-96.6374 1601.495,-73.2052 1300.1938,-54 1106.6816,-41.6653 876.0138,-27.0456 779.3689,-20.924"/>
<polygon fill="#000000" stroke="#000000" points="779.5478,-17.4284 769.3466,-20.2892 779.1053,-24.4144 779.5478,-17.4284"/>
<text text-anchor="middle" x="1542.1938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2092.5382,-122.8739C2090.8644,-133.5892 2090.9024,-146.863 2098.1938,-156 2109.8025,-170.5472 2153.9619,-180.0977 2190.5296,-185.682"/>
<polygon fill="#000000" stroke="#000000" points="2190.2083,-189.1721 2200.6089,-187.1528 2191.2191,-182.2455 2190.2083,-189.1721"/>
<text text-anchor="middle" x="2122.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- exposure -->
<g id="node20" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1714.1938" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1714.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1697.4886,-174.8626C1684.69,-162.9729 1665.9261,-148.0527 1646.1938,-141 1558.643,-109.7077 1320.1841,-136.4952 1228.1938,-123 1222.7679,-122.204 1217.1553,-121.1654 1211.5728,-119.9885"/>
<polygon fill="#000000" stroke="#000000" points="1212.1283,-116.526 1201.6037,-117.7433 1210.5903,-123.355 1212.1283,-116.526"/>
<text text-anchor="middle" x="1715.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2199.8721,-188.4288C2153.2975,-183.8443 2077.4246,-174.2104 2014.1938,-156 1997.9308,-151.3163 1995.7301,-144.6012 1979.1938,-141 1816.0801,-105.4778 1393.5863,-145.6544 1228.1938,-123 1222.6818,-122.245 1216.9802,-121.2224 1211.3147,-120.0456"/>
<polygon fill="#000000" stroke="#000000" points="1211.7274,-116.5515 1201.2047,-117.7855 1210.2002,-123.3829 1211.7274,-116.5515"/>
<text text-anchor="middle" x="2050.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge23" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2215.0833,-177.8583C2202.7058,-171.4426 2188.0795,-163.6017 2175.1938,-156 2158.2298,-145.9924 2139.7618,-133.9702 2125.056,-124.1123"/>
<polygon fill="#000000" stroke="#000000" points="2126.6796,-120.9855 2116.4329,-118.2915 2122.7631,-126.7873 2126.6796,-120.9855"/>
<text text-anchor="middle" x="2211.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node22" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2264.1938" cy="-105" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2264.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge21" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2282.1954,-183.3256C2308.0029,-176.7051 2338.4639,-166.8901 2346.1938,-156 2358.3899,-138.8177 2338.8459,-126.214 2315.7878,-117.8347"/>
<polygon fill="#000000" stroke="#000000" points="2316.7245,-114.4576 2306.1308,-114.611 2314.5079,-121.0974 2316.7245,-114.4576"/>
<text text-anchor="middle" x="2385.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge28" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2218.8753,-97.8283C2193.9435,-94.1091 2162.4247,-89.776 2134.1938,-87 1604.0005,-34.8658 956.8604,-21.4464 779.8341,-18.6457"/>
<polygon fill="#000000" stroke="#000000" points="779.8721,-15.146 769.8192,-18.4908 779.7638,-22.1452 779.8721,-15.146"/>
<text text-anchor="middle" x="1945.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2259.8481,-123.0034C2256.9773,-134.8967 2253.1579,-150.72 2249.9009,-164.2132"/>
<polygon fill="#000000" stroke="#000000" points="2246.4892,-163.4315 2247.545,-173.9735 2253.2938,-165.074 2246.4892,-163.4315"/>
<text text-anchor="middle" x="2294.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- methylation_array_file -->
<g id="node23" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2210.1938" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2210.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2213.1415,-260.6609C2215.0685,-250.7691 2218.0145,-238.4761 2222.1938,-228 2223.4932,-224.7426 2225.0534,-221.4282 2226.729,-218.1951"/>
<polygon fill="#000000" stroke="#000000" points="2229.8133,-219.8506 2231.6362,-209.4138 2223.7026,-216.4359 2229.8133,-219.8506"/>
<text text-anchor="middle" x="2313.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- radiology_file -->
<g id="node24" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1859.1938" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1859.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1834.4405,-174.7807C1815.7905,-162.8502 1789.0853,-147.915 1763.1938,-141 1648.2659,-110.3057 1345.9701,-139.7127 1228.1938,-123 1222.7642,-122.2295 1217.1492,-121.2079 1211.5652,-120.0415"/>
<polygon fill="#000000" stroke="#000000" points="1212.1174,-116.5785 1201.5942,-117.8086 1210.5877,-123.4093 1212.1174,-116.5785"/>
<text text-anchor="middle" x="1858.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- therapeutic_procedure -->
<g id="node25" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="471.1938" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="471.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M471.8584,-173.9696C473.3109,-162.6214 477.2021,-148.7097 487.1938,-141 503.8386,-128.1567 844.2013,-124.1468 865.1938,-123 940.5457,-118.8836 1026.7911,-113.4821 1085.9027,-109.6739"/>
<polygon fill="#000000" stroke="#000000" points="1086.4949,-113.143 1096.2485,-109.0058 1086.0437,-106.1576 1086.4949,-113.143"/>
<text text-anchor="middle" x="580.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
</g>
</svg>
</div>
