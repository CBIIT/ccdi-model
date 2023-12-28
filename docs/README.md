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
<svg width="2773pt" height="392pt"
 viewBox="0.00 0.00 2772.61 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 2768.6129,-388 2768.6129,4 -4,4"/>
<!-- radiology_file -->
<g id="node1" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="2189.6129" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="2189.6129" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- participant -->
<g id="node22" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1827.6129" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1827.6129" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2168.6423,-174.7265C2153.2843,-163.0956 2131.4011,-148.5508 2109.6129,-141 2033.6464,-114.6734 2009.2567,-133.9938 1929.6129,-123 1916.6247,-121.2071 1902.7606,-118.9754 1889.5731,-116.7001"/>
<polygon fill="#000000" stroke="#000000" points="1890.1007,-113.2393 1879.6463,-114.9583 1888.8909,-120.134 1890.1007,-113.2393"/>
<text text-anchor="middle" x="2198.6129" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- sample -->
<g id="node2" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1354.6129" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1354.6129" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pdx -->
<g id="node20" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="676.6129" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="676.6129" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge27" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1320.8663,-267.2793C1312.9852,-264.8916 1304.5682,-262.6183 1296.6129,-261 1241.2399,-249.7358 846.6539,-217.2427 790.6129,-210 764.8807,-206.6744 736.0124,-202.1076 713.7644,-198.4062"/>
<polygon fill="#000000" stroke="#000000" points="714.1727,-194.9259 703.7311,-196.7211 713.0132,-201.8292 714.1727,-194.9259"/>
<text text-anchor="middle" x="1173.1129" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node21" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="1084.6129" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="1084.6129" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge25" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1340.5518,-261.7735C1330.0242,-250.1647 1314.5664,-235.6271 1297.6129,-228 1234.3667,-199.5467 1210.4661,-224.3394 1142.6129,-210 1138.7205,-209.1774 1134.7153,-208.2062 1130.7154,-207.1482"/>
<polygon fill="#000000" stroke="#000000" points="1131.4242,-203.7118 1120.8501,-204.3742 1129.5293,-210.4505 1131.4242,-203.7118"/>
<text text-anchor="middle" x="1357.1129" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1388.0063,-267.1315C1395.9774,-264.7197 1404.5222,-262.4732 1412.6129,-261 1506.6788,-243.8721 2206.0387,-279.5829 2271.6129,-210 2292.8648,-187.4489 2285.9902,-160.1297 2261.6129,-141 2232.5501,-118.1934 1966.3144,-127.2177 1929.6129,-123 1916.4449,-121.4867 1902.4035,-119.3526 1889.0835,-117.0806"/>
<polygon fill="#000000" stroke="#000000" points="1889.5187,-113.6036 1879.0645,-115.3243 1888.31,-120.4985 1889.5187,-113.6036"/>
<text text-anchor="middle" x="2320.1129" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- therapeutic_procedure -->
<g id="node3" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="2545.6129" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="2545.6129" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2510.4503,-174.724C2484.3996,-162.8487 2447.6628,-148.0063 2413.6129,-141 2308.1916,-119.3078 2036.6396,-134.3791 1929.6129,-123 1916.3613,-121.5911 1902.234,-119.4894 1888.8487,-117.2142"/>
<polygon fill="#000000" stroke="#000000" points="1889.2385,-113.7292 1878.7842,-115.449 1888.0292,-120.624 1889.2385,-113.7292"/>
<text text-anchor="middle" x="2554.6129" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- molecular_test -->
<g id="node4" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1231.6129" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1231.6129" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1254.8872,-174.5463C1271.8783,-162.8305 1295.9812,-148.2583 1319.6129,-141 1398.8638,-116.6588 1634.6151,-108.6612 1755.0475,-106.1244"/>
<polygon fill="#000000" stroke="#000000" points="1755.3504,-109.6191 1765.2771,-105.9163 1755.2079,-102.6205 1755.3504,-109.6191"/>
<text text-anchor="middle" x="1383.6129" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- medical_history -->
<g id="node5" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1414.6129" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1414.6129" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1430.3584,-174.2008C1441.7061,-162.6447 1458.0607,-148.403 1475.6129,-141 1524.4098,-120.4188 1667.1557,-111.2306 1755.1599,-107.4248"/>
<polygon fill="#000000" stroke="#000000" points="1755.5019,-110.9137 1765.3465,-106.9977 1755.2086,-103.9198 1755.5019,-110.9137"/>
<text text-anchor="middle" x="1543.6129" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node6" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1012.6129" cy="-366" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="1012.6129" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1032.3678,-348.1168C1046.4257,-336.5232 1066.3459,-322.2713 1086.6129,-315 1174.7855,-283.366 1204.6804,-314.9869 1296.6129,-297 1301.3434,-296.0745 1306.2342,-294.9054 1311.077,-293.6093"/>
<polygon fill="#000000" stroke="#000000" points="1312.2297,-296.9201 1320.8837,-290.8079 1310.3069,-290.1894 1312.2297,-296.9201"/>
<text text-anchor="middle" x="1195.1129" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge4" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M882.1207,-360.1021C794.511,-354.7727 692.6067,-345.3579 678.6129,-330 651.6446,-300.403 659.0324,-250.643 667.4143,-219.6551"/>
<polygon fill="#000000" stroke="#000000" points="670.8131,-220.5018 670.2468,-209.9221 664.0919,-218.5458 670.8131,-220.5018"/>
<text text-anchor="middle" x="771.1129" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge5" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1021.0205,-347.9484C1027.4023,-334.0905 1036.2964,-314.4383 1043.6129,-297 1054.5937,-270.8282 1066.2918,-240.6104 1074.3701,-219.3308"/>
<polygon fill="#000000" stroke="#000000" points="1077.656,-220.5363 1077.9186,-209.9447 1071.1083,-218.0608 1077.656,-220.5363"/>
<text text-anchor="middle" x="1167.1129" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- exposure -->
<g id="node7" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1570.6129" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1570.6129" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1589.4088,-175.0125C1602.9737,-163.6696 1622.2408,-149.3518 1641.6129,-141 1678.0371,-125.2966 1721.42,-116.3994 1757.1224,-111.3806"/>
<polygon fill="#000000" stroke="#000000" points="1758.006,-114.7939 1767.4566,-110.0049 1757.0822,-107.8552 1758.006,-114.7939"/>
<text text-anchor="middle" x="1685.1129" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- pathology_file -->
<g id="node8" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1310.6129" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1310.6129" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge42" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1307.3956,-347.6878C1306.4751,-337.5755 1306.7927,-325.0636 1311.6129,-315 1314.0838,-309.8412 1317.6853,-305.1543 1321.7683,-300.9942"/>
<polygon fill="#000000" stroke="#000000" points="1324.3732,-303.3604 1329.4975,-294.0872 1319.7088,-298.1408 1324.3732,-303.3604"/>
<text text-anchor="middle" x="1372.6129" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge41" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1243.2816,-357.629C1173.5534,-348.7842 1072.3259,-335.386 1054.6129,-330 1039.969,-325.5472 1038.1919,-319.661 1023.6129,-315 978.0969,-300.4484 959.7512,-319.5348 917.6129,-297 898.2059,-286.6215 902.1668,-272.8364 883.6129,-261 829.8029,-226.672 757.1549,-207.6413 713.7762,-198.642"/>
<polygon fill="#000000" stroke="#000000" points="714.4254,-195.2026 703.9325,-196.6683 713.0492,-202.066 714.4254,-195.2026"/>
<text text-anchor="middle" x="978.6129" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge40" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1363.8047,-353.0209C1385.77,-346.9986 1411.2686,-339.1396 1433.6129,-330 1446.6797,-324.6552 1448.1338,-319.1979 1461.6129,-315 1495.7743,-304.3608 1597.7688,-323.6769 1621.6129,-297 1632.2755,-285.0706 1631.044,-273.9249 1621.6129,-261 1593.2784,-222.1687 1565.9152,-236.5561 1518.6129,-228 1353.9819,-198.2215 1307.3782,-239.0263 1142.6129,-210 1138.4661,-209.2695 1134.2015,-208.3288 1129.9568,-207.2613"/>
<polygon fill="#000000" stroke="#000000" points="1130.7228,-203.8423 1120.1536,-204.5796 1128.8757,-210.5942 1130.7228,-203.8423"/>
<text text-anchor="middle" x="1689.6129" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- sequencing_file -->
<g id="node9" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="305.6129" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="305.6129" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M365.8628,-353.4696C376.4184,-351.4869 387.3166,-349.5746 397.6129,-348 529.3356,-327.8562 562.6863,-324.3355 695.6129,-315 828.9,-305.6392 1164.8216,-319.0034 1296.6129,-297 1301.6192,-296.1642 1306.7936,-295.0062 1311.896,-293.6767"/>
<polygon fill="#000000" stroke="#000000" points="1312.8837,-297.0347 1321.556,-290.9484 1310.9811,-290.2983 1312.8837,-297.0347"/>
<text text-anchor="middle" x="762.1129" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge6" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M229.0345,-358.961C150.0883,-349.9325 34.7926,-331.1921 7.6129,-297 -2.3433,-284.4751 -2.6764,-273.2527 7.6129,-261 48.4162,-212.4106 502.2318,-196.5892 638.2854,-192.9203"/>
<polygon fill="#000000" stroke="#000000" points="638.7207,-196.4102 648.6253,-192.6486 638.5368,-189.4126 638.7207,-196.4102"/>
<text text-anchor="middle" x="74.1129" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge8" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M309.0949,-347.9714C314.8175,-323.719 328.7044,-281.2929 358.6129,-261 481.8087,-177.4117 880.1584,-236.7448 1026.6129,-210 1030.7551,-209.2436 1035.0165,-208.2851 1039.259,-207.206"/>
<polygon fill="#000000" stroke="#000000" points="1040.3472,-210.5367 1049.0593,-204.5075 1038.4889,-203.7878 1040.3472,-210.5367"/>
<text text-anchor="middle" x="425.1129" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- publication -->
<g id="node10" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="800.6129" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="800.6129" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- study -->
<g id="node12" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1885.6129" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1885.6129" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge39" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M794.8933,-86.6075C792.7407,-75.697 792.4868,-62.4002 800.6129,-54 818.9269,-35.0683 1633.0752,-21.7426 1838.7866,-18.6738"/>
<polygon fill="#000000" stroke="#000000" points="1839.0105,-22.171 1848.9575,-18.523 1838.9067,-15.1717 1839.0105,-22.171"/>
<text text-anchor="middle" x="851.6129" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- family_relationship -->
<g id="node11" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1741.6129" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1741.6129" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1734.8329,-173.5602C1732.2396,-163.1636 1731.2396,-150.4136 1737.6129,-141 1744.394,-130.984 1754.4618,-123.7545 1765.4362,-118.5363"/>
<polygon fill="#000000" stroke="#000000" points="1766.9434,-121.6997 1774.8157,-114.609 1764.2399,-115.2428 1766.9434,-121.6997"/>
<text text-anchor="middle" x="1817.1129" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- clinical_measure_file -->
<g id="node13" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="908.6129" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="908.6129" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge29" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M921.3438,-173.7713C929.0874,-163.4451 939.5874,-150.6951 950.6129,-141 984.5056,-111.197 993.7842,-101.2353 1036.6129,-87 1187.5122,-36.8444 1684.0368,-22.2627 1838.993,-18.8815"/>
<polygon fill="#000000" stroke="#000000" points="1839.2017,-22.3779 1849.1249,-18.6658 1839.0527,-15.3795 1839.2017,-22.3779"/>
<text text-anchor="middle" x="1122.6129" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M927.9676,-174.0928C941.9977,-162.3281 962.0466,-147.8841 982.6129,-141 1018.9239,-128.8457 1557.2298,-112.5931 1755.2322,-106.9938"/>
<polygon fill="#000000" stroke="#000000" points="1755.3498,-110.4919 1765.2471,-106.7114 1755.1525,-103.4947 1755.3498,-110.4919"/>
<text text-anchor="middle" x="1068.6129" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- diagnosis -->
<g id="node14" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1914.6129" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1914.6129" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1911.637,-173.7983C1909.1286,-163.2276 1904.6119,-150.2201 1896.6129,-141 1890.8852,-134.398 1883.6465,-128.8338 1876.0261,-124.2046"/>
<polygon fill="#000000" stroke="#000000" points="1877.4169,-120.974 1866.9727,-119.1935 1874.027,-127.0985 1877.4169,-120.974"/>
<text text-anchor="middle" x="1950.1129" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- synonym -->
<g id="node15" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2399.6129" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2399.6129" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge32" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2348.6154,-362.474C2147.2934,-348.5498 1418.4329,-298.0913 1412.6129,-297 1407.8137,-296.1001 1402.8527,-294.9367 1397.9456,-293.6346"/>
<polygon fill="#000000" stroke="#000000" points="1398.5939,-290.1801 1388.0176,-290.807 1396.6764,-296.9124 1398.5939,-290.1801"/>
<text text-anchor="middle" x="1921.1129" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge33" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2442.8825,-355.8267C2506.4428,-338.2909 2622.8832,-295.6932 2672.6129,-210 2688.7024,-182.2749 2679.5091,-156.791 2651.6129,-141 2584.9679,-103.2747 2026.8628,-164.6738 1962.6129,-123 1934.0933,-104.5016 1950.6046,-80.7377 1929.6129,-54 1925.5331,-48.8035 1920.5787,-43.8632 1915.4858,-39.4004"/>
<polygon fill="#000000" stroke="#000000" points="1917.4216,-36.4608 1907.4747,-32.8124 1912.9753,-41.8674 1917.4216,-36.4608"/>
<text text-anchor="middle" x="2722.1129" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2401.145,-347.808C2403.2568,-310.7383 2402.8163,-225.6085 2360.6129,-174 2336.7842,-144.861 2319.3007,-149.4199 2282.6129,-141 2129.5007,-105.8607 2085.7071,-140.684 1929.6129,-123 1916.3713,-121.4998 1902.2483,-119.3598 1888.8638,-117.076"/>
<polygon fill="#000000" stroke="#000000" points="1889.254,-113.5911 1878.7995,-115.3098 1888.044,-120.4857 1889.254,-113.5911"/>
<text text-anchor="middle" x="2434.1129" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study_funding -->
<g id="node16" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2048.6129" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2048.6129" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge2" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2019.2984,-88.1084C2001.5583,-78.0021 1978.4169,-65.0228 1957.6129,-54 1945.7249,-47.7013 1932.5965,-41.0491 1920.8416,-35.2"/>
<polygon fill="#000000" stroke="#000000" points="1922.2735,-32.0035 1911.7587,-30.7034 1919.1677,-38.2768 1922.2735,-32.0035"/>
<text text-anchor="middle" x="2044.6129" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- study_arm -->
<g id="node17" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2203.6129" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2203.6129" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge34" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2179.0422,-88.4668C2160.8928,-77.0332 2135.1749,-62.4167 2110.6129,-54 2050.9449,-33.5536 1978.3235,-24.6115 1932.0293,-20.7747"/>
<polygon fill="#000000" stroke="#000000" points="1932.237,-17.2804 1921.9943,-19.989 1931.6906,-24.259 1932.237,-17.2804"/>
<text text-anchor="middle" x="2191.1129" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- follow_up -->
<g id="node18" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="2042.6129" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="2042.6129" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2031.7008,-174.2164C2023.8708,-162.9724 2012.3088,-149.0841 1998.6129,-141 1989.14,-135.4086 1935.5172,-124.5982 1890.8093,-116.2768"/>
<polygon fill="#000000" stroke="#000000" points="1891.3109,-112.8103 1880.8414,-114.4348 1890.0389,-119.6938 1891.3109,-112.8103"/>
<text text-anchor="middle" x="2060.6129" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- study_admin -->
<g id="node19" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="2351.6129" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2351.6129" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge36" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2323.3158,-88.351C2302.111,-76.704 2271.985,-61.8736 2243.6129,-54 2186.1789,-38.0613 2015.4298,-25.8803 1932.2262,-20.7119"/>
<polygon fill="#000000" stroke="#000000" points="1932.242,-17.2064 1922.0465,-20.0875 1931.8134,-24.1933 1932.242,-17.2064"/>
<text text-anchor="middle" x="2339.1129" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge37" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M703.6801,-197.1659C726.7078,-201.3462 760.7065,-207.0125 790.6129,-210 977.8511,-228.7042 1029.0015,-191.5768 1213.6129,-228 1223.6645,-229.9831 1274.6773,-248.8146 1312.4704,-263.022"/>
<polygon fill="#000000" stroke="#000000" points="1311.6549,-266.4549 1322.2468,-266.7047 1314.1226,-259.9042 1311.6549,-266.4549"/>
<text text-anchor="middle" x="1279.6129" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge38" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M671.5099,-173.9151C666.2601,-151.1342 661.2956,-111.9566 680.6129,-87 711.8552,-46.6372 740.241,-62.2407 790.6129,-54 894.869,-36.944 1642.8349,-22.379 1838.7424,-18.8266"/>
<polygon fill="#000000" stroke="#000000" points="1839.0525,-22.3217 1848.9877,-18.6418 1838.9262,-15.3229 1839.0525,-22.3217"/>
<text text-anchor="middle" x="704.6129" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1120.4797,-204.5843C1127.7288,-206.7143 1135.3544,-208.665 1142.6129,-210 1173.9283,-215.7595 1406.8167,-204.7889 1428.6129,-228 1442.6001,-242.8951 1422.9123,-255.8969 1400.3423,-265.0447"/>
<polygon fill="#000000" stroke="#000000" points="1399.0471,-261.7924 1390.9297,-268.6011 1401.5213,-268.3406 1399.0471,-261.7924"/>
<text text-anchor="middle" x="1474.1129" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge11" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1102.7533,-175.103C1116.0931,-163.6496 1135.209,-149.1621 1154.6129,-141 1280.4693,-88.0596 1699.9012,-38.3768 1839.7726,-22.9225"/>
<polygon fill="#000000" stroke="#000000" points="1840.1816,-26.3987 1849.7393,-21.827 1839.4167,-19.4406 1840.1816,-26.3987"/>
<text text-anchor="middle" x="1410.1129" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1112.0147,-176.7355C1135.1324,-164.6831 1169.4987,-148.6636 1201.6129,-141 1304.6564,-116.4101 1612.8535,-108.4018 1754.6991,-105.9753"/>
<polygon fill="#000000" stroke="#000000" points="1755.0895,-109.4693 1765.0298,-105.8034 1754.973,-102.4703 1755.0895,-109.4693"/>
<text text-anchor="middle" x="1242.1129" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge19" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1823.9363,-86.905C1822.7941,-76.6233 1823.0441,-63.8733 1828.6129,-54 1833.0763,-46.0865 1840.0737,-39.6621 1847.6579,-34.5514"/>
<polygon fill="#000000" stroke="#000000" points="1849.922,-37.276 1856.7142,-29.1448 1846.3338,-31.2657 1849.922,-37.276"/>
<text text-anchor="middle" x="1879.1129" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_personnel -->
<g id="node23" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2526.6129" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2526.6129" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2493.3157,-88.2864C2468.2235,-76.5267 2432.6107,-61.5834 2399.6129,-54 2311.3547,-33.7168 2041.1887,-22.9989 1932.0609,-19.4034"/>
<polygon fill="#000000" stroke="#000000" points="1932.1226,-15.9036 1922.0144,-19.0776 1931.8957,-22.8999 1932.1226,-15.9036"/>
<text text-anchor="middle" x="2515.1129" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- cytogenomic_file -->
<g id="node24" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="496.6129" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="496.6129" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M579.3543,-359.0149C647.5095,-352.8103 746.5792,-342.7554 832.6129,-330 867.9649,-324.7587 876.1196,-319.1782 911.6129,-315 1081.7362,-294.9733 1127.8961,-326.6253 1296.6129,-297 1301.4221,-296.1555 1306.3895,-295.0275 1311.3005,-293.7462"/>
<polygon fill="#000000" stroke="#000000" points="1312.5597,-297.0276 1321.2327,-290.9424 1310.658,-290.2908 1312.5597,-297.0276"/>
<text text-anchor="middle" x="983.1129" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;pdx -->
<g id="edge17" class="edge">
<title>cytogenomic_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M430.3431,-353.8358C331.3887,-335.5206 156.0542,-302.4175 151.6129,-297 141.4691,-284.6265 141.062,-273.0283 151.6129,-261 183.7614,-224.3498 523.106,-201.0615 638.473,-194.1557"/>
<polygon fill="#000000" stroke="#000000" points="638.8306,-197.6408 648.6067,-193.557 638.4177,-190.653 638.8306,-197.6408"/>
<text text-anchor="middle" x="223.1129" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;cell_line -->
<g id="edge15" class="edge">
<title>cytogenomic_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M493.5234,-347.7145C490.6707,-323.9687 489.9122,-282.9688 513.6129,-261 530.9506,-244.9293 702.0836,-245.2884 725.6129,-243 859.5603,-229.9729 894.8531,-237.4038 1026.6129,-210 1030.508,-209.1899 1034.5149,-208.2275 1038.5161,-207.1754"/>
<polygon fill="#000000" stroke="#000000" points="1039.6985,-210.479 1048.3833,-204.4107 1037.8099,-203.7385 1039.6985,-210.479"/>
<text text-anchor="middle" x="585.1129" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- methylation_array_file -->
<g id="node25" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1786.6129" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1786.6129" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1676.9968,-360.0974C1618.3497,-355.1847 1545.2908,-346.2377 1481.6129,-330 1464.6294,-325.6693 1425.0415,-309.3918 1394.5436,-296.3759"/>
<polygon fill="#000000" stroke="#000000" points="1395.5714,-293.0084 1385.0013,-292.2838 1392.8125,-299.4418 1395.5714,-293.0084"/>
<text text-anchor="middle" x="1573.1129" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge23" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1786.6564,-347.8008C1785.6317,-336.5327 1782.2664,-322.7752 1772.6129,-315 1743.3232,-291.4091 1467.7919,-314.7079 1434.6129,-297 1416.9686,-287.5831 1424.2746,-272.0629 1407.6129,-261 1380.1338,-242.7545 1366.3847,-254.8784 1335.6129,-243 1322.4424,-237.916 1321.244,-231.6745 1307.6129,-228 1196.6165,-198.0793 905.0454,-220.985 790.6129,-210 764.7855,-207.5207 735.9182,-202.9441 713.6946,-199.0262"/>
<polygon fill="#000000" stroke="#000000" points="714.1357,-195.5495 703.6743,-197.2254 712.8975,-202.4391 714.1357,-195.5495"/>
<text text-anchor="middle" x="1526.1129" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge21" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1795.3264,-347.7619C1798.8537,-337.8996 1801.3187,-325.6027 1797.6129,-315 1787.4905,-286.0384 1780.9299,-276.7687 1754.6129,-261 1658.4827,-203.4004 1271.8614,-232.3569 1142.6129,-210 1138.4638,-209.2823 1134.1977,-208.3505 1129.9521,-207.2888"/>
<polygon fill="#000000" stroke="#000000" points="1130.7159,-203.8693 1120.1474,-204.6154 1128.8744,-210.6228 1130.7159,-203.8693"/>
<text text-anchor="middle" x="1881.1129" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
</g>
</svg>
</div>
