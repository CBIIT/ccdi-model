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
<svg width="2730pt" height="392pt"
 viewBox="0.00 0.00 2729.89 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 2725.887,-388 2725.887,4 -4,4"/>
<!-- radiology_file -->
<g id="node1" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1280.0923" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1280.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- participant -->
<g id="node13" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1353.0923" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1353.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1278.2779,-173.5761C1278.1731,-163.1849 1279.6731,-150.4349 1286.0923,-141 1290.636,-134.3216 1296.8339,-128.7793 1303.6359,-124.2114"/>
<polygon fill="#000000" stroke="#000000" points="1305.6953,-127.0587 1312.4959,-118.9345 1302.1133,-121.0446 1305.6953,-127.0587"/>
<text text-anchor="middle" x="1345.0923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- diagnosis -->
<g id="node2" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1426.0923" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1426.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1420.9253,-173.6882C1417.3696,-163.3343 1411.8696,-150.5843 1404.0923,-141 1400.0141,-135.9743 1395.0632,-131.3343 1389.8689,-127.1735"/>
<polygon fill="#000000" stroke="#000000" points="1391.7145,-124.185 1381.5962,-121.0431 1387.5468,-129.8091 1391.7145,-124.185"/>
<text text-anchor="middle" x="1456.5923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- study_personnel -->
<g id="node3" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="87.0923" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="87.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study -->
<g id="node16" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="623.0923" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="623.0923" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge25" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M94.1349,-86.9396C99.6416,-75.425 108.493,-61.3347 121.0923,-54 159.85,-31.4372 459.3052,-21.9102 576.3889,-19.0217"/>
<polygon fill="#000000" stroke="#000000" points="576.5669,-22.5185 586.4795,-18.7782 576.3979,-15.5206 576.5669,-22.5185"/>
<text text-anchor="middle" x="190.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- pathology_file -->
<g id="node4" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1688.0923" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1688.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- cell_line -->
<g id="node10" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="741.0923" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="741.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge1" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1614.6008,-361.3305C1537.2471,-355.7262 1420.9946,-345.1505 1379.0923,-330 1367.6154,-325.8503 1367.723,-318.6966 1356.0923,-315 1254.5766,-282.7355 983.2311,-305.9981 877.0923,-297 850.6164,-294.7555 821.3881,-291.0488 796.8346,-287.5806"/>
<polygon fill="#000000" stroke="#000000" points="797.0154,-284.0707 786.6195,-286.1138 796.0204,-290.9997 797.0154,-284.0707"/>
<text text-anchor="middle" x="1440.0923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- sample -->
<g id="node11" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1939.0923" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1939.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1742.7943,-353.4645C1752.8353,-351.435 1763.2516,-349.5081 1773.0923,-348 1793.8345,-344.8212 1946.9789,-345.5292 1961.0923,-330 1988.5967,-299.7364 1970.3425,-249.4965 1954.6644,-218.7078"/>
<polygon fill="#000000" stroke="#000000" points="1957.7227,-217.0043 1949.935,-209.8208 1951.5432,-220.2929 1957.7227,-217.0043"/>
<text text-anchor="middle" x="2036.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pdx -->
<g id="node20" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1255.0923" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1255.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge2" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1682.984,-347.84C1678.7763,-336.4371 1671.5928,-322.5131 1660.0923,-315 1629.796,-295.2079 1388.1704,-284.0246 1293.2157,-280.3579"/>
<polygon fill="#000000" stroke="#000000" points="1293.2995,-276.8586 1283.1741,-279.9771 1293.0342,-283.8536 1293.2995,-276.8586"/>
<text text-anchor="middle" x="1734.0923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- study_funding -->
<g id="node5" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="269.0923" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="269.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge9" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M263.9943,-86.7466C262.1539,-75.8885 262.1722,-62.5979 270.0923,-54 290.4877,-31.859 485.5354,-22.5413 576.6362,-19.3728"/>
<polygon fill="#000000" stroke="#000000" points="576.8138,-22.8689 586.69,-19.0334 576.5776,-15.8728 576.8138,-22.8689"/>
<text text-anchor="middle" x="332.0923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- sequencing_file -->
<g id="node6" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1865.0923" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1865.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge32" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1805.8792,-353.3182C1795.0119,-351.3036 1783.7396,-349.4196 1773.0923,-348 1662.6706,-333.278 1628.293,-366.64 1523.0923,-330 1511.9165,-326.1076 1512.3492,-318.651 1501.0923,-315 1435.1136,-293.6009 946.2314,-302.5578 877.0923,-297 850.6068,-294.871 821.3774,-291.1791 796.8254,-287.6909"/>
<polygon fill="#000000" stroke="#000000" points="797.0093,-284.1811 786.6112,-286.2136 796.0072,-291.109 797.0093,-284.1811"/>
<text text-anchor="middle" x="1589.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge34" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1936.7137,-356.7975C2005.0539,-346.3535 2100.8079,-326.7975 2123.0923,-297 2132.6747,-284.1869 2132.2058,-274.1508 2123.0923,-261 2118.8732,-254.9119 2035.6789,-225.3224 1982.6169,-206.9243"/>
<polygon fill="#000000" stroke="#000000" points="1983.6803,-203.5887 1973.0856,-203.6274 1981.392,-210.2041 1983.6803,-203.5887"/>
<text text-anchor="middle" x="2196.5923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge33" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1848.1313,-348.2456C1835.7561,-336.551 1817.916,-322.128 1799.0923,-315 1752.1499,-297.2243 1409.4828,-284.1891 1293.4115,-280.2433"/>
<polygon fill="#000000" stroke="#000000" points="1293.3312,-276.7388 1283.2192,-279.9005 1293.0959,-283.7348 1293.3312,-276.7388"/>
<text text-anchor="middle" x="1890.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node7" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="710.0923" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="710.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M682.0858,-174.4119C669.3337,-164.2992 659.0837,-151.5492 669.0923,-141 679.5244,-130.0044 1107.416,-113.6813 1281.0244,-107.4969"/>
<polygon fill="#000000" stroke="#000000" points="1281.2219,-110.9922 1291.0914,-107.1395 1280.9735,-103.9966 1281.2219,-110.9922"/>
<text text-anchor="middle" x="798.5923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge18" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M679.7566,-174.5959C672.7921,-169.3856 666.0007,-163.1297 661.0923,-156 638.1253,-122.6397 628.9999,-75.8216 625.4006,-46.2038"/>
<polygon fill="#000000" stroke="#000000" points="628.8657,-45.6919 624.3092,-36.127 621.9064,-46.4457 628.8657,-45.6919"/>
<text text-anchor="middle" x="730.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- molecular_test -->
<g id="node8" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1579.0923" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1579.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1558.3716,-174.4936C1544.203,-163.3666 1524.5333,-149.5046 1505.0923,-141 1471.7029,-126.3936 1460.5507,-131.4201 1425.0923,-123 1420.2032,-121.839 1415.1327,-120.614 1410.0496,-119.3714"/>
<polygon fill="#000000" stroke="#000000" points="1410.85,-115.9641 1400.3033,-116.9725 1409.1769,-122.7612 1410.85,-115.9641"/>
<text text-anchor="middle" x="1594.0923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- publication -->
<g id="node9" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="499.0923" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="499.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge36" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M486.4311,-86.9929C480.7314,-76.4912 476.7486,-63.4879 484.0923,-54 495.5492,-39.1978 541.3981,-29.3737 577.346,-23.7809"/>
<polygon fill="#000000" stroke="#000000" points="578.2828,-27.1802 587.6594,-22.2477 577.2534,-20.2563 578.2828,-27.1802"/>
<text text-anchor="middle" x="535.0923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M773.0182,-265.0989C801.7624,-253.2145 845.457,-236.6961 885.0923,-228 970.5376,-209.253 1001.8905,-247.1406 1081.0923,-210 1101.579,-200.393 1097.6257,-185.5349 1117.0923,-174 1170.0027,-142.6481 1238.1071,-124.7307 1287.545,-115.0564"/>
<polygon fill="#000000" stroke="#000000" points="1288.3125,-118.4733 1297.486,-113.1726 1287.0091,-111.5957 1288.3125,-118.4733"/>
<text text-anchor="middle" x="1157.5923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge20" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M694.129,-273.0648C619.4654,-260.6883 477.0299,-224.2727 427.0923,-123 395.7514,-59.4412 510.1472,-33.0441 577.3821,-23.1954"/>
<polygon fill="#000000" stroke="#000000" points="577.917,-26.6547 587.3376,-21.8067 576.9499,-19.7219 577.917,-26.6547"/>
<text text-anchor="middle" x="489.5923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1921.796,-175.3428C1908.1423,-163.3636 1887.9709,-148.1165 1867.0923,-141 1774.0452,-109.285 1522.3948,-136.994 1425.0923,-123 1419.3731,-122.1775 1413.4483,-121.0908 1407.5654,-119.8577"/>
<polygon fill="#000000" stroke="#000000" points="1408.2706,-116.4291 1397.7482,-117.6652 1406.7448,-123.2608 1408.2706,-116.4291"/>
<text text-anchor="middle" x="1930.5923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node12" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1154.0923" cy="-366" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="1154.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge21" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1057.1958,-353.1731C1040.8253,-351.2588 1023.9886,-349.446 1008.0923,-348 974.1735,-344.9147 725.4577,-354.7802 702.0923,-330 693.8051,-321.2111 699.524,-310.7235 708.8755,-301.5506"/>
<polygon fill="#000000" stroke="#000000" points="711.3295,-304.0544 716.5628,-294.8422 706.727,-298.7802 711.3295,-304.0544"/>
<text text-anchor="middle" x="810.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge23" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1285.1861,-360.4176C1422.5494,-353.9625 1623.1001,-342.5966 1657.0923,-330 1681.2224,-321.058 1727.4375,-273.2058 1750.0923,-261 1763.3093,-253.879 1844.0124,-225.2037 1895.5986,-207.1357"/>
<polygon fill="#000000" stroke="#000000" points="1896.9002,-210.3884 1905.1839,-203.7831 1894.5891,-203.7809 1896.9002,-210.3884"/>
<text text-anchor="middle" x="1858.5923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge22" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1141.3371,-347.6333C1135.8354,-337.261 1132.0854,-324.511 1139.0923,-315 1148.6154,-302.0734 1187.8567,-291.7869 1218.0898,-285.5737"/>
<polygon fill="#000000" stroke="#000000" points="1218.8108,-288.999 1227.9414,-283.6248 1217.4523,-282.132 1218.8108,-288.999"/>
<text text-anchor="middle" x="1247.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge10" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1295.2002,-98.1005C1154.3214,-81.3109 795.8872,-38.5934 668.7061,-23.4362"/>
<polygon fill="#000000" stroke="#000000" points="668.8822,-19.9325 658.5383,-22.2244 668.0538,-26.8833 668.8822,-19.9325"/>
<text text-anchor="middle" x="1082.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- family_relationship -->
<g id="node14" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1777.0923" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1777.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1745.919,-174.6732C1723.3574,-163.0172 1691.7439,-148.4643 1662.0923,-141 1559.6516,-115.2121 1529.3731,-139.8706 1425.0923,-123 1419.6071,-122.1126 1413.9267,-121.0134 1408.2726,-119.7989"/>
<polygon fill="#000000" stroke="#000000" points="1408.6977,-116.3065 1398.1714,-117.5091 1407.1502,-123.1333 1408.6977,-116.3065"/>
<text text-anchor="middle" x="1783.5923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- synonym -->
<g id="node15" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2461.0923" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2461.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2415.7299,-270.0388C2358.448,-258.9628 2256.7757,-240.1 2169.0923,-228 2090.7622,-217.1908 2069.3547,-226.8215 1992.0923,-210 1988.5108,-209.2203 1984.8342,-208.2795 1981.1682,-207.2422"/>
<polygon fill="#000000" stroke="#000000" points="1982.1474,-203.8817 1971.5614,-204.3148 1980.1069,-210.5778 1982.1474,-203.8817"/>
<text text-anchor="middle" x="2307.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2460.3535,-260.8605C2457.8678,-228.083 2447.1347,-160.5707 2401.0923,-141 2351.1824,-119.7854 1478.854,-130.1222 1425.0923,-123 1419.2825,-122.2303 1413.2643,-121.166 1407.2952,-119.9359"/>
<polygon fill="#000000" stroke="#000000" points="1407.8616,-116.4766 1397.3414,-117.7321 1406.3484,-123.3111 1407.8616,-116.4766"/>
<text text-anchor="middle" x="2493.5923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge6" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2487.5678,-263.3407C2518.8977,-242.8173 2563.9775,-205.7032 2540.0923,-174 2489.7953,-107.2401 2784.2984,-144.289 1410.0923,-54 1129.2792,-35.5498 791.4788,-23.5024 669.6924,-19.4839"/>
<polygon fill="#000000" stroke="#000000" points="669.7103,-15.9827 659.601,-19.153 669.4809,-22.9789 669.7103,-15.9827"/>
<text text-anchor="middle" x="2577.5923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- therapeutic_procedure -->
<g id="node17" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="2119.0923" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="2119.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2080.0716,-174.9571C2050.7206,-163.0314 2009.1773,-148.0249 1971.0923,-141 1732.3217,-96.958 1665.5501,-156.6325 1425.0923,-123 1419.37,-122.1996 1413.4432,-121.1273 1407.559,-119.903"/>
<polygon fill="#000000" stroke="#000000" points="1408.2617,-116.4738 1397.7404,-117.7199 1406.7424,-123.3069 1408.2617,-116.4738"/>
<text text-anchor="middle" x="2118.0923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- study_admin -->
<g id="node18" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1504.0923" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1504.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge24" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1452.6112,-92.567C1443.1605,-90.5271 1433.356,-88.5701 1424.0923,-87 1140.2768,-38.8953 793.8875,-23.5162 669.9494,-19.355"/>
<polygon fill="#000000" stroke="#000000" points="669.7957,-15.8482 659.6865,-19.0192 669.5667,-22.8444 669.7957,-15.8482"/>
<text text-anchor="middle" x="1349.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- medical_history -->
<g id="node19" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2340.0923" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2340.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2308.2243,-175.2031C2283.5562,-163.1509 2248.1359,-147.8733 2215.0923,-141 2043.171,-105.2392 1599.122,-146.4393 1425.0923,-123 1419.2842,-122.2177 1413.2671,-121.1452 1407.2986,-119.9103"/>
<polygon fill="#000000" stroke="#000000" points="1407.8663,-116.4512 1397.3455,-117.7013 1406.3496,-123.2849 1407.8663,-116.4512"/>
<text text-anchor="middle" x="2329.0923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1282.5415,-274.2978C1341.9195,-264.2911 1486.8125,-240.7615 1609.0923,-228 1731.7966,-215.1942 1765.0871,-234.0437 1886.0923,-210 1889.738,-209.2756 1893.4774,-208.3658 1897.2013,-207.3423"/>
<polygon fill="#000000" stroke="#000000" points="1898.3756,-210.6441 1906.9467,-204.4161 1896.3626,-203.9398 1898.3756,-210.6441"/>
<text text-anchor="middle" x="1633.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge15" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1235.0774,-266.3707C1230.9205,-264.2444 1226.4697,-262.3066 1222.0923,-261 1087.5017,-220.8275 687.3199,-313.248 592.0923,-210 549.9355,-164.2926 584.4719,-84.9901 607.177,-44.0785"/>
<polygon fill="#000000" stroke="#000000" points="610.2992,-45.6692 612.2257,-35.251 604.2228,-42.194 610.2992,-45.6692"/>
<text text-anchor="middle" x="597.0923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- follow_up -->
<g id="node21" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="892.0923" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="892.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M909.8529,-174.7831C923.9148,-161.5689 942.6994,-144.9382 952.0923,-141 1009.5253,-116.9195 1181.2933,-108.92 1280.399,-106.2817"/>
<polygon fill="#000000" stroke="#000000" points="1280.7318,-109.7745 1290.6395,-106.0213 1280.5537,-102.7768 1280.7318,-109.7745"/>
<text text-anchor="middle" x="997.0923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- study_arm -->
<g id="node22" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2662.0923" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2662.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge12" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2643.6874,-87.6988C2629.6473,-75.7277 2609.1862,-60.7774 2588.0923,-54 2493.9333,-23.7473 958.1273,-18.7634 669.6122,-18.0928"/>
<polygon fill="#000000" stroke="#000000" points="669.5004,-14.5927 659.4924,-18.0699 669.4844,-21.5926 669.5004,-14.5927"/>
<text text-anchor="middle" x="2664.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- methylation_array_file -->
<g id="node23" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="883.0923" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="883.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge29" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M768.0094,-364.0072C650.511,-360.7501 482.4953,-352.2222 462.0923,-330 431.2689,-296.4284 590.9079,-284.7414 681.6765,-280.8433"/>
<polygon fill="#000000" stroke="#000000" points="682.001,-284.333 691.8493,-280.4265 681.7144,-277.3389 682.001,-284.333"/>
<text text-anchor="middle" x="553.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M892.8121,-347.6618C899.1647,-337.0428 908.2792,-324.0323 919.0923,-315 962.7369,-278.5429 980.0528,-275.3051 1035.0923,-261 1230.0389,-210.3319 1286.0189,-239.8733 1487.0923,-228 1664.2973,-217.5362 1711.6483,-242.8696 1886.0923,-210 1889.745,-209.3117 1893.4893,-208.4273 1897.2164,-207.4207"/>
<polygon fill="#000000" stroke="#000000" points="1898.3793,-210.7264 1906.9671,-204.5216 1896.3843,-204.0167 1898.3793,-210.7264"/>
<text text-anchor="middle" x="1126.5923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge28" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M900.3932,-348.0399C912.5865,-336.5688 929.9246,-322.4894 948.0923,-315 954.2649,-312.4554 1136.4634,-292.101 1217.2043,-283.1727"/>
<polygon fill="#000000" stroke="#000000" points="1217.8858,-286.6188 1227.441,-282.0418 1217.1171,-279.6611 1217.8858,-286.6188"/>
<text text-anchor="middle" x="1039.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- exposure -->
<g id="node24" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1019.0923" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1019.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1030.1026,-174.3312C1038.2746,-162.8332 1050.5018,-148.6076 1065.0923,-141 1101.5245,-122.004 1208.4123,-112.601 1281.2066,-108.2776"/>
<polygon fill="#000000" stroke="#000000" points="1281.4584,-111.769 1291.241,-107.7008 1281.0566,-104.7805 1281.4584,-111.769"/>
<text text-anchor="middle" x="1108.5923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
</g>
</svg>
</div>
