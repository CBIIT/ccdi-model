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
<svg width="2970pt" height="392pt"
 viewBox="0.00 0.00 2969.91 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 2965.9058,-388 2965.9058,4 -4,4"/>
<!-- clinical_measure_file -->
<g id="node1" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="169.9058" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="169.9058" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- participant -->
<g id="node6" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1034.9058" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1034.9058" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M174.4164,-173.8635C178.3195,-162.3157 185.2313,-148.2172 196.9058,-141 233.113,-118.6166 920.7214,-128.6969 962.9058,-123 968.7136,-122.2157 974.7305,-121.1418 980.6988,-119.9061"/>
<polygon fill="#000000" stroke="#000000" points="981.6483,-123.2806 990.6518,-117.6962 980.1309,-116.447 981.6483,-123.2806"/>
<text text-anchor="middle" x="326.4058" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- study -->
<g id="node19" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="876.9058" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="876.9058" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge13" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M169.1065,-173.5533C169.666,-162.6225 172.3223,-149.3232 180.9058,-141 274.2587,-50.4775 690.1028,-25.5354 830.46,-19.6317"/>
<polygon fill="#000000" stroke="#000000" points="830.6213,-23.1281 840.4704,-19.2235 830.3361,-16.1339 830.6213,-23.1281"/>
<text text-anchor="middle" x="374.9058" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- study_admin -->
<g id="node2" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="83.9058" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="83.9058" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge18" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M76.2979,-86.6599C73.1219,-75.7691 71.8053,-62.4747 79.9058,-54 105.9227,-26.7813 662.9079,-19.8277 829.9577,-18.3512"/>
<polygon fill="#000000" stroke="#000000" points="830.4178,-21.8475 840.3873,-18.2617 830.3577,-14.8478 830.4178,-21.8475"/>
<text text-anchor="middle" x="136.4058" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- family_relationship -->
<g id="node3" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="943.9058" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="943.9058" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M939.6357,-173.9795C938.2028,-163.4731 938.3583,-150.4695 944.9058,-141 951.7848,-131.051 961.8955,-123.8508 972.881,-118.6402"/>
<polygon fill="#000000" stroke="#000000" points="974.3889,-121.8033 982.2628,-114.7145 971.6868,-115.3459 974.3889,-121.8033"/>
<text text-anchor="middle" x="1024.4058" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- molecular_test -->
<g id="node4" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1141.9058" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1141.9058" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1131.2916,-173.8631C1124.4604,-163.3154 1114.832,-150.3093 1103.9058,-141 1096.7305,-134.8866 1088.3416,-129.4316 1079.9334,-124.7302"/>
<polygon fill="#000000" stroke="#000000" points="1081.3345,-121.5118 1070.8586,-119.9289 1078.0609,-127.6992 1081.3345,-121.5118"/>
<text text-anchor="middle" x="1180.9058" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- follow_up -->
<g id="node5" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="1415.9058" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="1415.9058" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1384.4104,-177.1922C1357.9252,-165.4115 1318.7509,-149.535 1282.9058,-141 1205.9839,-122.6842 1183.773,-136.753 1105.9058,-123 1100.7931,-122.097 1095.5052,-121.0242 1090.2282,-119.8587"/>
<polygon fill="#000000" stroke="#000000" points="1090.6741,-116.3694 1080.1423,-117.5234 1089.0951,-123.189 1090.6741,-116.3694"/>
<text text-anchor="middle" x="1375.9058" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge12" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1028.3881,-87.0168C1023.5171,-75.9822 1015.8085,-62.4028 1004.9058,-54 991.6656,-43.7958 952.44,-33.6154 920.8678,-26.6978"/>
<polygon fill="#000000" stroke="#000000" points="921.4398,-23.241 910.9287,-24.5706 919.9747,-30.086 921.4398,-23.241"/>
<text text-anchor="middle" x="1068.4058" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- publication -->
<g id="node7" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="718.9058" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="718.9058" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge5" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M733.2461,-87.3412C742.9032,-76.436 756.474,-62.8789 770.9058,-54 790.0228,-42.2386 813.464,-33.7624 833.4373,-28.001"/>
<polygon fill="#000000" stroke="#000000" points="834.5114,-31.3356 843.2262,-25.3105 832.6562,-24.5859 834.5114,-31.3356"/>
<text text-anchor="middle" x="821.9058" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- medical_history -->
<g id="node8" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1798.9058" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1798.9058" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1757.3474,-176.255C1723.3569,-164.1799 1673.7536,-148.3724 1628.9058,-141 1399.404,-103.2728 1336.1684,-155.7653 1105.9058,-123 1100.4765,-122.2274 1094.8617,-121.2044 1089.2778,-120.0371"/>
<polygon fill="#000000" stroke="#000000" points="1089.8303,-116.5742 1079.307,-117.8033 1088.2999,-123.4049 1089.8303,-116.5742"/>
<text text-anchor="middle" x="1757.9058" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- pdx -->
<g id="node9" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1575.9058" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1575.9058" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample -->
<g id="node18" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1532.9058" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1532.9058" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge35" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1567.4104,-261.8116C1561.3649,-249.5801 1553.1221,-232.9027 1546.209,-218.9158"/>
<polygon fill="#000000" stroke="#000000" points="1549.2474,-217.164 1541.6788,-209.75 1542.972,-220.2656 1549.2474,-217.164"/>
<text text-anchor="middle" x="1580.9058" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node10" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2563.9058" cy="-366" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="2563.9058" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge24" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2451.6392,-355.5002C2410.0699,-350.0165 2362.8631,-341.8828 2320.9058,-330 2304.6223,-325.3883 2302.4288,-318.6618 2285.9058,-315 2161.0937,-287.3394 1838.3174,-307.4613 1710.9058,-297 1677.8274,-294.284 1640.4366,-289.1349 1613.4072,-285.0373"/>
<polygon fill="#000000" stroke="#000000" points="1613.6416,-281.5323 1603.2253,-283.4693 1612.5761,-288.4507 1613.6416,-281.5323"/>
<text text-anchor="middle" x="2429.4058" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- cell_line -->
<g id="node14" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2029.9058" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2029.9058" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge26" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2560.9871,-347.8883C2558.1434,-336.5058 2552.603,-322.5864 2541.9058,-315 2505.8058,-289.3982 2217.3934,-281.8519 2090.0157,-279.7559"/>
<polygon fill="#000000" stroke="#000000" points="2089.7183,-276.2508 2079.664,-279.5917 2089.6073,-283.2499 2089.7183,-276.2508"/>
<text text-anchor="middle" x="2662.4058" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2668.1255,-354.2191C2717.5389,-347.5609 2767.4614,-338.822 2774.9058,-330 2779.2052,-324.9049 2779.4084,-319.9164 2774.9058,-315 2685.0319,-216.8686 1711.7689,-239.0284 1581.9058,-210 1579.2607,-209.4087 1576.5649,-208.71 1573.8664,-207.9369"/>
<polygon fill="#000000" stroke="#000000" points="1574.7579,-204.5481 1564.168,-204.8714 1572.6482,-211.2226 1574.7579,-204.5481"/>
<text text-anchor="middle" x="2853.4058" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- study_funding -->
<g id="node11" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="876.9058" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="876.9058" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge31" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M876.9058,-86.9735C876.9058,-75.1918 876.9058,-59.5607 876.9058,-46.1581"/>
<polygon fill="#000000" stroke="#000000" points="880.4059,-46.0033 876.9058,-36.0034 873.4059,-46.0034 880.4059,-46.0033"/>
<text text-anchor="middle" x="938.9058" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- sequencing_file -->
<g id="node12" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1432.9058" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1432.9058" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge29" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1426.656,-347.9975C1424.1475,-337.2338 1423.3806,-323.9543 1430.9058,-315 1460.8042,-279.4235 1489.3608,-310.2419 1533.9058,-297 1537.0995,-296.0506 1540.3759,-294.9282 1543.6217,-293.7152"/>
<polygon fill="#000000" stroke="#000000" points="1545.1795,-296.8613 1553.1545,-289.8864 1542.5705,-290.3656 1545.1795,-296.8613"/>
<text text-anchor="middle" x="1497.4058" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge27" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1512.1079,-360.377C1580.7998,-354.6448 1674.4531,-344.5256 1708.9058,-330 1718.8195,-325.8203 1717.9179,-318.9995 1727.9058,-315 1807.4712,-283.1391 1834.8976,-307.9268 1919.9058,-297 1938.036,-294.6696 1957.7632,-291.6082 1975.4405,-288.6726"/>
<polygon fill="#000000" stroke="#000000" points="1976.3039,-292.0766 1985.5842,-286.9652 1975.1419,-285.1737 1976.3039,-292.0766"/>
<text text-anchor="middle" x="1794.4058" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge28" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1420.5111,-348.109C1407.0271,-326.2191 1389.4531,-288.6631 1405.9058,-261 1415.6539,-244.6099 1458.5966,-223.3586 1491.8799,-208.7965"/>
<polygon fill="#000000" stroke="#000000" points="1493.6128,-211.861 1501.4127,-204.6907 1490.8438,-205.4319 1493.6128,-211.861"/>
<text text-anchor="middle" x="1472.4058" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- exposure -->
<g id="node13" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1954.9058" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1954.9058" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1926.0605,-176.7104C1901.3194,-164.4682 1864.3188,-148.1954 1829.9058,-141 1672.3739,-108.0617 1265.3458,-144.9117 1105.9058,-123 1100.3942,-122.2425 1094.6928,-121.2183 1089.0274,-120.0405"/>
<polygon fill="#000000" stroke="#000000" points="1089.4404,-116.5465 1078.9175,-117.7792 1087.9124,-123.3777 1089.4404,-116.5465"/>
<text text-anchor="middle" x="1919.4058" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1994.728,-266.2749C1988.5117,-264.3138 1982.0597,-262.4592 1975.9058,-261 1822.0927,-224.5282 1766.1687,-278.9195 1623.9058,-210 1602.9688,-199.8571 1603.6853,-189.0041 1585.9058,-174 1567.2244,-158.2349 1564.9314,-149.2068 1541.9058,-141 1450.5628,-108.4437 1201.8627,-136.9901 1105.9058,-123 1100.4792,-122.2088 1094.8661,-121.1734 1089.2833,-119.9985"/>
<polygon fill="#000000" stroke="#000000" points="1089.8383,-116.5359 1079.3139,-117.7556 1088.3018,-123.3652 1089.8383,-116.5359"/>
<text text-anchor="middle" x="1664.4058" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge21" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2032.0347,-260.7873C2033.7026,-238.5731 2033.4651,-200.6903 2016.9058,-174 2002.8686,-151.3749 1991.7204,-150.6526 1966.9058,-141 1771.4757,-64.9798 1105.6454,-28.7285 923.3668,-20.0811"/>
<polygon fill="#000000" stroke="#000000" points="923.4581,-16.5816 913.3049,-19.6086 923.1297,-23.5739 923.4581,-16.5816"/>
<text text-anchor="middle" x="2041.4058" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- radiology_file -->
<g id="node15" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="371.9058" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="371.9058" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M412.2735,-176.8132C427.4124,-170.7733 444.6396,-163.4839 459.9058,-156 471.8846,-150.1277 473.0864,-144.6932 485.9058,-141 587.8355,-111.6347 857.8882,-137.9437 962.9058,-123 968.6261,-122.186 974.5517,-121.1049 980.4351,-119.8751"/>
<polygon fill="#000000" stroke="#000000" points="981.2542,-123.2785 990.2529,-117.6863 979.7309,-116.4463 981.2542,-123.2785"/>
<text text-anchor="middle" x="544.9058" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- methylation_array_file -->
<g id="node16" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2084.9058" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2084.9058" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge16" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1988.0784,-356.1235C1955.4735,-350.7653 1919.3947,-342.5524 1887.9058,-330 1876.5693,-325.4809 1876.3819,-319.1518 1864.9058,-315 1800.1057,-291.5568 1779.2832,-305.554 1710.9058,-297 1677.9728,-292.8801 1640.5679,-287.8666 1613.4962,-284.178"/>
<polygon fill="#000000" stroke="#000000" points="1613.678,-280.6704 1603.2963,-282.7844 1612.7303,-287.606 1613.678,-280.6704"/>
<text text-anchor="middle" x="1979.4058" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge15" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2094.8445,-347.9772C2099.0741,-337.7196 2101.8241,-324.9696 2095.9058,-315 2091.1597,-307.0051 2083.9447,-300.672 2076.0021,-295.6951"/>
<polygon fill="#000000" stroke="#000000" points="2077.6247,-292.5928 2067.1805,-290.8123 2074.2348,-298.7173 2077.6247,-292.5928"/>
<text text-anchor="middle" x="2190.4058" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2084.9217,-347.8348C2083.8858,-336.5807 2080.5181,-322.826 2070.9058,-315 2046.5578,-295.1769 1819.501,-304.0504 1788.9058,-297 1745.8051,-287.0678 1632.2482,-237.094 1571.8994,-209.824"/>
<polygon fill="#000000" stroke="#000000" points="1573.2428,-206.5902 1562.6895,-205.6519 1570.3542,-212.9665 1573.2428,-206.5902"/>
<text text-anchor="middle" x="1880.4058" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study_arm -->
<g id="node17" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1174.9058" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1174.9058" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge30" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1161.9104,-87.425C1152.4275,-75.9689 1138.5382,-61.7548 1122.9058,-54 1088.7293,-37.046 984.4544,-26.3407 923.186,-21.3384"/>
<polygon fill="#000000" stroke="#000000" points="923.2527,-17.8327 913.0063,-20.5274 922.6967,-24.8106 923.2527,-17.8327"/>
<text text-anchor="middle" x="1192.4058" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1508.1958,-176.9484C1486.949,-164.8513 1455.0514,-148.6581 1424.9058,-141 1287.274,-106.0367 1246.2647,-144.5476 1105.9058,-123 1100.4854,-122.1679 1094.8763,-121.1053 1089.2961,-119.9135"/>
<polygon fill="#000000" stroke="#000000" points="1089.8563,-116.4517 1079.3296,-117.6507 1088.3064,-123.278 1089.8563,-116.4517"/>
<text text-anchor="middle" x="1501.4058" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- therapeutic_procedure -->
<g id="node20" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="580.9058" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="580.9058" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M591.7503,-173.9989C599.8482,-162.3526 612.0551,-148.0862 626.9058,-141 694.3906,-108.7989 888.9633,-134.1186 962.9058,-123 968.6195,-122.1408 974.5408,-121.0303 980.4216,-119.7829"/>
<polygon fill="#000000" stroke="#000000" points="981.2488,-123.1844 990.2366,-117.5746 979.7121,-116.3551 981.2488,-123.1844"/>
<text text-anchor="middle" x="719.9058" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- pathology_file -->
<g id="node21" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1255.9058" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1255.9058" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge4" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1265.8247,-348.1263C1273.2971,-336.5369 1284.681,-322.2861 1298.9058,-315 1345.5216,-291.1226 1483.0401,-309.4838 1533.9058,-297 1537.3222,-296.1615 1540.8153,-295.0734 1544.2559,-293.8474"/>
<polygon fill="#000000" stroke="#000000" points="1545.6883,-297.0449 1553.7063,-290.1194 1543.1196,-290.5332 1545.6883,-297.0449"/>
<text text-anchor="middle" x="1359.9058" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge2" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1310.5896,-353.3432C1320.6325,-351.326 1331.0541,-349.4347 1340.9058,-348 1439.3013,-333.6708 1471.3609,-366.3657 1563.9058,-330 1573.9193,-326.0652 1572.8397,-318.7984 1582.9058,-315 1653.0721,-288.523 1845.3453,-305.0674 1919.9058,-297 1938.1595,-295.025 1957.9923,-292.0414 1975.7265,-289.0682"/>
<polygon fill="#000000" stroke="#000000" points="1976.632,-292.4642 1985.8978,-287.3265 1975.4505,-285.5646 1976.632,-292.4642"/>
<text text-anchor="middle" x="1643.9058" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1253.3167,-347.8534C1251.0985,-324.6405 1251.1244,-284.6225 1272.9058,-261 1288.9632,-243.5853 1457.1701,-216.6482 1479.9058,-210 1483.077,-209.0727 1486.3407,-208.0742 1489.6164,-207.0398"/>
<polygon fill="#000000" stroke="#000000" points="1490.9684,-210.2808 1499.3991,-203.8641 1488.807,-203.6228 1490.9684,-210.2808"/>
<text text-anchor="middle" x="1333.9058" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- study_personnel -->
<g id="node22" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="1339.9058" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1339.9058" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge33" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1314.5109,-87.7703C1296.0413,-76.1601 1269.9801,-61.622 1244.9058,-54 1185.946,-36.0776 1008.4391,-24.7894 923.3608,-20.265"/>
<polygon fill="#000000" stroke="#000000" points="923.382,-16.7614 913.2128,-19.7342 923.0163,-23.7518 923.382,-16.7614"/>
<text text-anchor="middle" x="1349.4058" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- synonym -->
<g id="node23" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1150.9058" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1150.9058" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1169.8271,-262.0602C1181.0909,-252.0519 1195.7153,-239.1893 1208.9058,-228 1218.5399,-219.8275 1223.7369,-220.4025 1230.9058,-210 1248.89,-183.9038 1269.87,-164.7686 1248.9058,-141 1227.7195,-116.9798 1137.3774,-128.9467 1105.9058,-123 1100.8803,-122.0504 1095.6815,-120.9549 1090.4879,-119.7828"/>
<polygon fill="#000000" stroke="#000000" points="1091.0885,-116.3288 1080.5534,-117.4526 1089.4899,-123.1438 1091.0885,-116.3288"/>
<text text-anchor="middle" x="1296.4058" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1175.5046,-262.8906C1198.2933,-247.9704 1228.7141,-228.0646 1228.9058,-228 1334.8811,-192.2526 1370.2819,-232.1643 1479.9058,-210 1483.549,-209.2634 1487.2868,-208.3451 1491.0094,-207.3158"/>
<polygon fill="#000000" stroke="#000000" points="1492.1877,-210.6163 1500.7531,-204.3805 1490.1685,-203.9138 1492.1877,-210.6163"/>
<text text-anchor="middle" x="1271.4058" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge9" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1098.8384,-278.6664C892.7118,-276.9516 140.7312,-266.8208 51.9058,-210 14.8841,-186.3176 15.6789,-165.6075 4.9058,-123 .9837,-107.4882 -3.5059,-100.6104 4.9058,-87 22.1475,-59.1023 39.1635,-62.2453 70.9058,-54 144.2824,-34.9398 669.9954,-22.3708 830.494,-18.9455"/>
<polygon fill="#000000" stroke="#000000" points="830.6052,-22.4441 840.5289,-18.7332 830.4571,-15.4456 830.6052,-22.4441"/>
<text text-anchor="middle" x="55.4058" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- diagnosis -->
<g id="node24" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="770.9058" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="770.9058" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M790.5123,-175.0478C804.8852,-163.5684 825.3925,-149.0725 845.9058,-141 894.8631,-121.734 911.3304,-133.3912 962.9058,-123 967.9858,-121.9765 973.2467,-120.8303 978.5063,-119.6253"/>
<polygon fill="#000000" stroke="#000000" points="979.6414,-122.9537 988.5712,-117.2521 978.0349,-116.1405 979.6414,-122.9537"/>
<text text-anchor="middle" x="890.4058" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
</g>
</svg>
</div>
