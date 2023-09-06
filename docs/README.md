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
<svg width="2310pt" height="392pt"
 viewBox="0.00 0.00 2310.34 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 2306.3385,-388 2306.3385,4 -4,4"/>
<!-- radiology_file -->
<g id="node1" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="645.3431" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="645.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- participant -->
<g id="node12" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1062.3431" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1062.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M663.002,-174.4647C675.8366,-162.8706 694.2425,-148.4776 713.3431,-141 762.1743,-121.8833 903.1978,-112.1965 990.3087,-107.9025"/>
<polygon fill="#000000" stroke="#000000" points="990.5729,-111.394 1000.3932,-107.4176 990.2366,-104.4021 990.5729,-111.394"/>
<text text-anchor="middle" x="772.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node2" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1996.3431" cy="-366" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="1996.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- pdx -->
<g id="node8" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1830.3431" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1830.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge6" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1992.8253,-347.9919C1989.7565,-336.9474 1984.1904,-323.3662 1974.3431,-315 1958.4117,-301.4647 1904.8337,-290.6259 1867.7272,-284.5024"/>
<polygon fill="#000000" stroke="#000000" points="1868.1709,-281.029 1857.743,-282.902 1867.063,-287.9407 1868.1709,-281.029"/>
<text text-anchor="middle" x="2093.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- sample -->
<g id="node10" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1432.3431" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1432.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2100.3678,-354.1489C2149.4505,-347.4869 2198.9515,-338.7666 2206.3431,-330 2210.6405,-324.9032 2210.8728,-319.8915 2206.3431,-315 2188.6253,-295.8669 1997.8817,-302.271 1972.3431,-297 1924.0281,-287.0281 1914.1246,-276.6613 1867.3431,-261 1822.5618,-246.0083 1812.7185,-236.9133 1766.3431,-228 1643.4476,-204.3796 1608.0996,-234.333 1485.3431,-210 1481.6971,-209.2773 1477.9574,-208.3687 1474.2334,-207.3459"/>
<polygon fill="#000000" stroke="#000000" points="1475.0718,-203.9433 1464.4877,-204.421 1473.0596,-210.6479 1475.0718,-203.9433"/>
<text text-anchor="middle" x="2080.8431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- cell_line -->
<g id="node22" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="993.3431" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="993.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge7" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1885.511,-355.2561C1854.1256,-352.5269 1819.9138,-349.8478 1788.3431,-348 1723.0909,-344.1808 1262.705,-349.5817 1200.3431,-330 1188.6996,-326.3439 1188.6513,-319.5896 1177.3431,-315 1137.0929,-298.6636 1088.8047,-289.5764 1051.7972,-284.6199"/>
<polygon fill="#000000" stroke="#000000" points="1052.0369,-281.1222 1041.6744,-283.3288 1051.1512,-288.0659 1052.0369,-281.1222"/>
<text text-anchor="middle" x="1308.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- diagnosis -->
<g id="node3" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1010.3431" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1010.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1006.858,-174.0098C1005.7797,-163.763 1006.0297,-151.013 1011.3431,-141 1014.142,-135.7256 1018.0983,-131.0541 1022.5841,-126.9702"/>
<polygon fill="#000000" stroke="#000000" points="1024.8796,-129.6165 1030.5226,-120.6495 1020.5194,-124.1403 1024.8796,-129.6165"/>
<text text-anchor="middle" x="1055.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- study_funding -->
<g id="node4" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="77.3431" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="77.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study -->
<g id="node19" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1140.3431" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1140.3431" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge14" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M88.9292,-87.1443C97.6553,-75.4031 110.7623,-60.9662 126.3431,-54 170.9516,-34.0555 900.1934,-21.637 1093.5805,-18.6839"/>
<polygon fill="#000000" stroke="#000000" points="1093.7572,-22.1817 1103.703,-18.5305 1093.651,-15.1825 1093.7572,-22.1817"/>
<text text-anchor="middle" x="188.3431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- molecular_test -->
<g id="node5" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1574.3431" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1574.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1536.9809,-176.0711C1504.8434,-162.6489 1460.831,-145.0071 1442.3431,-141 1307.8987,-111.8601 1269.2973,-143.998 1133.3431,-123 1128.002,-122.1751 1122.4775,-121.1279 1116.9776,-119.9551"/>
<polygon fill="#000000" stroke="#000000" points="1117.6756,-116.5246 1107.1495,-117.7292 1116.1293,-123.3517 1117.6756,-116.5246"/>
<text text-anchor="middle" x="1548.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- publication -->
<g id="node6" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="235.3431" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="235.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge15" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M242.1954,-87.0684C247.6616,-75.4531 256.5415,-61.1952 269.3431,-54 305.4843,-33.6867 918.0321,-21.7703 1093.6389,-18.7604"/>
<polygon fill="#000000" stroke="#000000" points="1093.9062,-22.2565 1103.8453,-18.5871 1093.7873,-15.2575 1093.9062,-22.2565"/>
<text text-anchor="middle" x="320.3431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- study_admin -->
<g id="node7" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="386.3431" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="386.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge24" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M377.7669,-86.6889C374.0701,-75.8091 372.2211,-62.5159 380.3431,-54 405.0287,-28.1174 932.0977,-20.2608 1093.6741,-18.4562"/>
<polygon fill="#000000" stroke="#000000" points="1093.8179,-21.9549 1103.7791,-18.3459 1093.7415,-14.9553 1093.8179,-21.9549"/>
<text text-anchor="middle" x="436.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1807.5717,-268.1805C1801.4284,-265.5559 1794.7158,-262.9482 1788.3431,-261 1713.4878,-238.1158 1692.5804,-240.7053 1615.3431,-228 1557.7876,-218.5323 1542.1028,-223.4393 1485.3431,-210 1481.9301,-209.1919 1478.4259,-208.2538 1474.9241,-207.2385"/>
<polygon fill="#000000" stroke="#000000" points="1475.7268,-203.8234 1465.1393,-204.2165 1473.6611,-210.5116 1475.7268,-203.8234"/>
<text text-anchor="middle" x="1738.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge10" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1851.3568,-266.7881C1855.2778,-264.7256 1859.3873,-262.7039 1863.3431,-261 1867.5545,-259.186 2017.6478,-213.7096 2020.3431,-210 2052.477,-165.7749 2053.8678,-130.1803 2020.3431,-87 1984.0509,-40.255 1949.8655,-62.7952 1891.3431,-54 1754.551,-33.4418 1329.4962,-22.2486 1187.2554,-19.0049"/>
<polygon fill="#000000" stroke="#000000" points="1187.1933,-15.5028 1177.1169,-18.7763 1187.0355,-22.501 1187.1933,-15.5028"/>
<text text-anchor="middle" x="2068.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- methylation_array_file -->
<g id="node9" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1663.3431" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1663.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge13" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1721.0676,-350.3352C1736.8901,-344.951 1753.7055,-338.1748 1768.3431,-330 1770.4869,-328.8028 1789.0619,-313.4661 1805.3263,-299.9215"/>
<polygon fill="#000000" stroke="#000000" points="1807.6048,-302.5788 1813.0429,-293.4861 1803.1214,-297.2029 1807.6048,-302.5788"/>
<text text-anchor="middle" x="1877.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1635.6264,-348.4916C1628.4621,-343.1312 1621.1422,-336.828 1615.3431,-330 1592.9518,-303.6358 1604.3103,-284.9392 1579.3431,-261 1563.4182,-245.7307 1512.019,-223.3408 1474.4746,-208.2446"/>
<polygon fill="#000000" stroke="#000000" points="1475.362,-204.8307 1464.7766,-204.3825 1472.7721,-211.334 1475.362,-204.8307"/>
<text text-anchor="middle" x="1689.8431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge12" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1582.8049,-353.0751C1568.0482,-351.0852 1552.7577,-349.2724 1538.3431,-348 1508.2215,-345.341 1015.5807,-351.5256 994.3431,-330 988.4179,-323.9944 986.7641,-315.3959 987.0232,-306.9661"/>
<polygon fill="#000000" stroke="#000000" points="990.5101,-307.2767 988.1295,-296.9528 983.5524,-306.5079 990.5101,-307.2767"/>
<text text-anchor="middle" x="1085.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1407.6358,-176.9838C1386.7619,-165.0791 1355.6637,-149.1374 1326.3431,-141 1243.3308,-117.9615 1218.2419,-137.6296 1133.3431,-123 1128.2267,-122.1183 1122.9363,-121.0601 1117.6577,-119.9039"/>
<polygon fill="#000000" stroke="#000000" points="1118.1001,-116.4143 1107.5697,-117.5807 1116.5291,-123.2357 1118.1001,-116.4143"/>
<text text-anchor="middle" x="1401.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- therapeutic_procedure -->
<g id="node11" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="182.3431" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="182.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M197.4015,-174.1315C208.4862,-162.3845 224.655,-147.9459 242.3431,-141 259.6291,-134.2121 792.7884,-114.5977 989.9666,-107.5553"/>
<polygon fill="#000000" stroke="#000000" points="990.3543,-111.0438 1000.2231,-107.1895 990.1047,-104.0483 990.3543,-111.0438"/>
<text text-anchor="middle" x="335.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge16" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1061.2904,-86.961C1061.5632,-76.4479 1063.5196,-63.444 1070.3431,-54 1077.5963,-43.9616 1088.4864,-36.5189 1099.5296,-31.0923"/>
<polygon fill="#000000" stroke="#000000" points="1101.0437,-34.2496 1108.7654,-26.9953 1098.2052,-27.8509 1101.0437,-34.2496"/>
<text text-anchor="middle" x="1120.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_arm -->
<g id="node13" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1202.3431" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1202.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge28" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1194.273,-86.7984C1189.4277,-76.7207 1182.7709,-64.2065 1175.3431,-54 1172.2175,-49.7051 1168.5967,-45.415 1164.8937,-41.3709"/>
<polygon fill="#000000" stroke="#000000" points="1167.2299,-38.7505 1157.7797,-33.9604 1162.1801,-43.5982 1167.2299,-38.7505"/>
<text text-anchor="middle" x="1232.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- follow_up -->
<g id="node14" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="373.3431" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="373.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M396.8169,-175.4809C415.1101,-163.5741 441.6393,-148.357 467.3431,-141 516.3485,-126.9736 842.3463,-113.214 989.9551,-107.6185"/>
<polygon fill="#000000" stroke="#000000" points="990.4073,-111.104 1000.2684,-107.2298 990.1437,-104.109 990.4073,-111.104"/>
<text text-anchor="middle" x="512.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- exposure -->
<g id="node15" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="500.3431" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="500.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M524.0153,-175.8558C542.7561,-163.9817 570.0643,-148.634 596.3431,-141 668.1285,-120.1465 877.9691,-110.6625 989.9586,-106.9843"/>
<polygon fill="#000000" stroke="#000000" points="990.2713,-110.4761 1000.1537,-106.6566 990.0464,-103.4798 990.2713,-110.4761"/>
<text text-anchor="middle" x="639.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- clinical_measure_file -->
<g id="node16" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="1902.3431" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="1902.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge37" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1821.2699,-179.9874C1754.7951,-170.0749 1671.0421,-157.4133 1667.3431,-156 1655.9429,-151.6443 1655.9782,-144.6829 1644.3431,-141 1536.0146,-106.7103 1245.8295,-139.0526 1133.3431,-123 1127.9142,-122.2253 1122.2996,-121.2007 1116.7158,-120.0326"/>
<polygon fill="#000000" stroke="#000000" points="1117.2686,-116.5697 1106.7452,-117.7977 1115.7375,-123.4002 1117.2686,-116.5697"/>
<text text-anchor="middle" x="1796.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge31" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1920.378,-173.8488C1928.7093,-163.296 1935.0341,-150.2896 1926.3431,-141 1905.8021,-119.044 1686.1416,-127.0067 1656.3431,-123 1478.7686,-99.1234 1270.6524,-50.2632 1182.8393,-28.6682"/>
<polygon fill="#000000" stroke="#000000" points="1183.5314,-25.234 1172.9839,-26.2345 1181.8532,-32.0299 1183.5314,-25.234"/>
<text text-anchor="middle" x="1742.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- family_relationship -->
<g id="node17" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="837.3431" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="837.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M834.4812,-173.6846C833.8734,-162.8031 835.2146,-149.5097 843.3431,-141 863.1678,-120.2455 934.085,-111.4552 989.9149,-107.7328"/>
<polygon fill="#000000" stroke="#000000" points="990.3854,-111.2104 1000.1483,-107.095 989.9499,-104.2239 990.3854,-111.2104"/>
<text text-anchor="middle" x="922.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- pathology_file -->
<g id="node18" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="804.3431" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="804.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge19" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M879.8866,-363.9237C1020.3018,-359.6731 1316.3967,-348.7653 1417.3431,-330 1438.9008,-325.9926 1442.7792,-318.9733 1464.3431,-315 1606.1776,-288.8658 1647.9254,-329.9068 1788.3431,-297 1791.7682,-296.1973 1795.2668,-295.1327 1798.7109,-293.9209"/>
<polygon fill="#000000" stroke="#000000" points="1800.1349,-297.122 1808.1658,-290.2113 1797.5782,-290.6055 1800.1349,-297.122"/>
<text text-anchor="middle" x="1525.3431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M808.7241,-347.8467C812.4782,-336.4466 819.1143,-322.5233 830.3431,-315 871.2784,-287.5736 1002.782,-305.3494 1051.3431,-297 1199.9808,-271.4438 1234.9668,-253.6089 1379.3431,-210 1382.506,-209.0447 1385.7636,-208.0256 1389.0349,-206.9765"/>
<polygon fill="#000000" stroke="#000000" points="1390.3967,-210.2135 1398.8095,-203.7733 1388.2168,-203.5616 1390.3967,-210.2135"/>
<text text-anchor="middle" x="1274.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge18" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M731.8404,-360.3424C687.9828,-354.1796 644.71,-341.3955 668.3431,-315 685.6906,-295.6248 844.7233,-285.5419 933.7165,-281.3756"/>
<polygon fill="#000000" stroke="#000000" points="934.1149,-284.8612 943.9448,-280.9084 933.7954,-277.8684 934.1149,-284.8612"/>
<text text-anchor="middle" x="729.3431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- sequencing_file -->
<g id="node20" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1446.3431" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1446.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge23" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1504.1864,-353.0164C1530.6322,-346.7031 1562.2595,-338.6213 1590.3431,-330 1608.8922,-324.3057 1612.4615,-319.4696 1631.3431,-315 1699.6892,-298.8212 1720.4602,-315.0235 1788.3431,-297 1791.7432,-296.0973 1795.2255,-294.9672 1798.6596,-293.7156"/>
<polygon fill="#000000" stroke="#000000" points="1800.1067,-296.9067 1808.1016,-289.9546 1797.5163,-290.4036 1800.1067,-296.9067"/>
<text text-anchor="middle" x="1697.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1507.877,-353.8292C1531.8472,-347.7302 1555.2767,-339.5919 1562.3431,-330 1566.2973,-324.6326 1566.6807,-320.0626 1562.3431,-315 1528.3976,-275.3808 1482.838,-334.2841 1446.3431,-297 1426.8207,-277.0554 1425.5244,-243.8585 1427.7057,-220.1303"/>
<polygon fill="#000000" stroke="#000000" points="1431.2078,-220.3163 1428.8996,-209.976 1424.2557,-219.4988 1431.2078,-220.3163"/>
<text text-anchor="middle" x="1512.8431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge21" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1363.4908,-364.0691C1201.3027,-359.8829 856.0668,-348.8041 838.3431,-330 833.7705,-325.1486 834.1965,-320.2201 838.3431,-315 850.4889,-299.71 896.4865,-290.3288 935.2452,-284.9932"/>
<polygon fill="#000000" stroke="#000000" points="935.9726,-288.4279 945.4331,-283.6583 935.0631,-281.4872 935.9726,-288.4279"/>
<text text-anchor="middle" x="904.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- study_personnel -->
<g id="node21" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="1924.3431" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1924.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge36" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1866.1818,-91.5937C1813.1102,-79.8698 1732.3621,-63.3039 1661.3431,-54 1487.1355,-31.1778 1278.1373,-22.279 1186.8377,-19.3016"/>
<polygon fill="#000000" stroke="#000000" points="1186.921,-15.8025 1176.8149,-18.9832 1186.6987,-22.799 1186.921,-15.8025"/>
<text text-anchor="middle" x="1817.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1026.6294,-265.6268C1041.4942,-259.2951 1059.0664,-251.3073 1074.3431,-243 1085.0645,-237.1698 1085.7618,-231.8485 1097.3431,-228 1216.5235,-188.396 1256.1489,-234.4053 1379.3431,-210 1382.9893,-209.2777 1386.729,-208.3694 1390.453,-207.3468"/>
<polygon fill="#000000" stroke="#000000" points="1391.6268,-210.6488 1400.1988,-204.4222 1389.6148,-203.9442 1391.6268,-210.6488"/>
<text text-anchor="middle" x="1137.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1016.9602,-263.0304C1034.499,-250.263 1058.0971,-231.064 1074.3431,-210 1090.611,-188.9077 1094.4168,-181.9694 1100.3431,-156 1101.8264,-149.5004 1102.9773,-147.1242 1100.3431,-141 1098.5163,-136.7529 1095.9148,-132.772 1092.9187,-129.1194"/>
<polygon fill="#000000" stroke="#000000" points="1095.2903,-126.5333 1085.8769,-121.6714 1090.2038,-131.3424 1095.2903,-126.5333"/>
<text text-anchor="middle" x="1135.8431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge2" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M944.0825,-277.2178C755.1527,-270.1482 85.8734,-242.8586 55.3431,-210 44.4523,-198.2786 46.4739,-187.3168 55.3431,-174 113.8746,-86.1173 237.107,-146.897 465.3431,-123 704.7306,-97.9354 988.7958,-46.6191 1096.2418,-26.4283"/>
<polygon fill="#000000" stroke="#000000" points="1096.9025,-29.8655 1106.081,-24.5735 1095.6057,-22.9867 1096.9025,-29.8655"/>
<text text-anchor="middle" x="131.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- synonym -->
<g id="node23" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2250.3431" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2250.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge35" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2211.1585,-267.1357C2202.3979,-264.8137 2193.1051,-262.6044 2184.3431,-261 2102.2135,-245.961 2076.1437,-270.6029 1997.3431,-243 1985.8253,-238.9654 1985.9753,-231.6921 1974.3431,-228 1870.6985,-195.1026 1592.2855,-229.692 1485.3431,-210 1481.6876,-209.3269 1477.9413,-208.4531 1474.2128,-207.4536"/>
<polygon fill="#000000" stroke="#000000" points="1475.0423,-204.049 1464.46,-204.5658 1473.0548,-210.761 1475.0423,-204.049"/>
<text text-anchor="middle" x="2039.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2215.5698,-265.6072C2182.0223,-253.3697 2129.5248,-236.0004 2082.3431,-228 1998.3372,-213.7554 1777.2751,-244.4458 1699.3431,-210 1678.6472,-200.8524 1680.6674,-188.5558 1663.3431,-174 1643.8014,-157.5811 1640.5331,-149.1427 1616.3431,-141 1514.5478,-106.7342 1239.6582,-138.2826 1133.3431,-123 1127.915,-122.2197 1122.3009,-121.1915 1116.7174,-120.0211"/>
<polygon fill="#000000" stroke="#000000" points="1117.271,-116.5583 1106.7472,-117.7835 1115.738,-123.3884 1117.271,-116.5583"/>
<text text-anchor="middle" x="1741.8431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge34" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2237.5198,-261.4845C2200.941,-213.485 2090.3131,-81.5804 1960.3431,-54 1884.8119,-37.9718 1349.3942,-23.2789 1186.9529,-19.1494"/>
<polygon fill="#000000" stroke="#000000" points="1186.8867,-15.6467 1176.8014,-18.8928 1186.7097,-22.6445 1186.8867,-15.6467"/>
<text text-anchor="middle" x="2181.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- medical_history -->
<g id="node24" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1285.3431" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1285.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1244.7008,-176.144C1206.5179,-161.2476 1149.4056,-138.9661 1109.2936,-123.317"/>
<polygon fill="#000000" stroke="#000000" points="1110.3268,-119.9632 1099.7385,-119.5892 1107.7825,-126.4845 1110.3268,-119.9632"/>
<text text-anchor="middle" x="1254.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
</g>
</svg>
</div>
