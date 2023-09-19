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
<svg width="3363pt" height="392pt"
 viewBox="0.00 0.00 3363.04 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3359.0444,-388 3359.0444,4 -4,4"/>
<!-- publication -->
<g id="node1" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="63.0444" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="63.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- study -->
<g id="node17" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="676.0444" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="676.0444" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge40" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M78.2164,-87.499C89.5413,-75.7609 106.1027,-61.1815 124.0444,-54 170.3322,-35.4725 504.7478,-23.3148 629.3861,-19.3841"/>
<polygon fill="#000000" stroke="#000000" points="629.5033,-22.8823 639.3894,-19.0722 629.2851,-15.8857 629.5033,-22.8823"/>
<text text-anchor="middle" x="175.0444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- study_arm -->
<g id="node2" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="204.0444" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="204.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge11" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M214.3075,-87.1537C222.0044,-75.5765 233.667,-61.3291 248.0444,-54 281.3628,-37.0153 525.2896,-24.5432 629.2847,-19.9413"/>
<polygon fill="#000000" stroke="#000000" points="629.6525,-23.4286 639.4901,-19.4951 629.3467,-16.4353 629.6525,-23.4286"/>
<text text-anchor="middle" x="296.5444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- molecular_test -->
<g id="node3" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1181.0444" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1181.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- participant -->
<g id="node24" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1434.0444" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1434.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1181.2847,-173.8581C1182.4404,-162.7602 1185.845,-149.1699 1195.0444,-141 1219.192,-119.5548 1300.7109,-110.8834 1361.8768,-107.3778"/>
<polygon fill="#000000" stroke="#000000" points="1362.092,-110.8713 1371.8895,-106.839 1361.7158,-103.8815 1362.092,-110.8713"/>
<text text-anchor="middle" x="1259.0444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- exposure -->
<g id="node4" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1332.0444" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1332.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge38" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1327.6441,-173.8876C1326.1649,-163.3486 1326.3177,-150.343 1333.0444,-141 1338.7668,-133.0519 1356.8482,-125.5556 1376.1622,-119.4825"/>
<polygon fill="#000000" stroke="#000000" points="1377.4304,-122.7563 1386.0034,-116.5309 1375.4194,-116.0514 1377.4304,-122.7563"/>
<text text-anchor="middle" x="1376.5444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- diagnosis -->
<g id="node5" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1579.0444" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1579.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1552.4492,-176.0429C1529.3384,-162.1764 1495.6556,-141.9667 1470.1186,-126.6445"/>
<polygon fill="#000000" stroke="#000000" points="1471.832,-123.5909 1461.4563,-121.4471 1468.2305,-129.5934 1471.832,-123.5909"/>
<text text-anchor="middle" x="1559.5444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- sequencing_file -->
<g id="node6" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2745.0444" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="2745.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sample -->
<g id="node19" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1824.0444" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1824.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2745.0773,-347.8139C2744.0483,-336.5512 2740.6821,-322.7948 2731.0444,-315 2703.8728,-293.0241 2451.7851,-300.7842 2417.0444,-297 2356.6281,-290.419 1936.0243,-224.6567 1877.0444,-210 1873.6405,-209.1541 1870.1429,-208.1889 1866.6456,-207.1549"/>
<polygon fill="#000000" stroke="#000000" points="1867.4575,-203.7418 1856.8687,-204.1005 1865.37,-210.4233 1867.4575,-203.7418"/>
<text text-anchor="middle" x="2483.5444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- cell_line -->
<g id="node23" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2608.0444" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2608.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge28" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2755.7034,-347.8259C2760.3702,-337.265 2763.3205,-324.2581 2756.0444,-315 2744.7305,-300.6042 2702.3498,-291.2487 2665.8234,-285.693"/>
<polygon fill="#000000" stroke="#000000" points="2666.1059,-282.1975 2655.707,-284.2258 2665.1011,-289.125 2666.1059,-282.1975"/>
<text text-anchor="middle" x="2826.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- pdx -->
<g id="node25" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1984.0444" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1984.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge27" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2662.2248,-364.265C2475.0878,-360.033 2033.7319,-348.1771 2007.0444,-330 1999.112,-324.5972 1993.8765,-315.7669 1990.4379,-306.9601"/>
<polygon fill="#000000" stroke="#000000" points="1993.6892,-305.6402 1987.271,-297.2107 1987.0317,-307.8029 1993.6892,-305.6402"/>
<text text-anchor="middle" x="2073.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- cytogenomic_file -->
<g id="node7" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="3100.0444" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="3100.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge35" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3183.2622,-359.0069C3223.4678,-352.4143 3258.7799,-339.6527 3237.0444,-315 3134.9828,-199.2407 2701.9233,-239.7502 2548.0444,-228 2399.3126,-216.6428 2023.8758,-236.2806 1877.0444,-210 1873.3348,-209.336 1869.5328,-208.4601 1865.7515,-207.4518"/>
<polygon fill="#000000" stroke="#000000" points="1866.4507,-204.0087 1855.8686,-204.5278 1864.4647,-210.7211 1866.4507,-204.0087"/>
<text text-anchor="middle" x="3283.5444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;cell_line -->
<g id="edge37" class="edge">
<title>cytogenomic_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M3097.11,-347.9103C3094.2598,-336.5371 3088.7179,-322.6198 3078.0444,-315 3061.5816,-303.2472 2790.1412,-288.1722 2667.4393,-281.919"/>
<polygon fill="#000000" stroke="#000000" points="2667.264,-278.4058 2657.0997,-281.3951 2666.9097,-285.3968 2667.264,-278.4058"/>
<text text-anchor="middle" x="3161.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;pdx -->
<g id="edge36" class="edge">
<title>cytogenomic_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M3030.5408,-354.5325C2999.682,-348.591 2963.1564,-340.3815 2931.0444,-330 2915.3289,-324.9193 2913.1432,-318.6906 2897.0444,-315 2786.2914,-289.6104 2499.5796,-301.5414 2386.0444,-297 2252.5859,-291.6617 2094.2553,-284.2576 2022.6374,-280.8506"/>
<polygon fill="#000000" stroke="#000000" points="2022.4639,-277.3385 2012.3085,-280.3584 2022.1306,-284.3305 2022.4639,-277.3385"/>
<text text-anchor="middle" x="3002.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node8" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1365.0444" cy="-366" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="1365.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1359.0354,-347.8756C1352.6063,-324.6867 1345.9491,-284.6945 1367.0444,-261 1371.574,-255.9123 1603.284,-228.8368 1610.0444,-228 1681.5004,-219.1549 1700.7686,-225.6685 1771.0444,-210 1774.6219,-209.2024 1778.2958,-208.249 1781.9599,-207.2032"/>
<polygon fill="#000000" stroke="#000000" points="1783.0269,-210.5369 1791.5636,-204.2621 1780.9771,-203.8438 1783.0269,-210.5369"/>
<text text-anchor="middle" x="1475.5444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge8" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1469.1729,-354.1C1492.7775,-351.7507 1517.7518,-349.5391 1541.0444,-348 1607.4851,-343.6099 2077.4767,-352.7798 2140.0444,-330 2150.1541,-326.3192 2148.9656,-318.7643 2159.0444,-315 2239.4879,-284.9554 2460.304,-310.8884 2545.0444,-297 2550.3765,-296.1261 2555.8988,-294.9568 2561.3572,-293.6318"/>
<polygon fill="#000000" stroke="#000000" points="2562.2612,-297.0132 2571.0583,-291.1089 2560.4993,-290.2386 2562.2612,-297.0132"/>
<text text-anchor="middle" x="2267.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge7" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1381.63,-348.0656C1393.7633,-336.2883 1411.3169,-321.8406 1430.0444,-315 1536.9818,-275.9387 1830.9408,-321.8469 1942.0444,-297 1945.4774,-296.2322 1948.9813,-295.1904 1952.4285,-293.9924"/>
<polygon fill="#000000" stroke="#000000" points="1953.8443,-297.1971 1961.8875,-290.3009 1951.2993,-290.6761 1953.8443,-297.1971"/>
<text text-anchor="middle" x="1538.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- follow_up -->
<g id="node9" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="1707.0444" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="1707.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1681.0318,-176.1115C1661.5575,-164.8426 1633.9285,-150.152 1608.0444,-141 1573.5166,-128.7918 1533.5927,-120.1645 1500.703,-114.4222"/>
<polygon fill="#000000" stroke="#000000" points="1501.1798,-110.9532 1490.7354,-112.732 1500.0095,-117.8547 1501.1798,-110.9532"/>
<text text-anchor="middle" x="1686.0444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- medical_history -->
<g id="node10" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1971.0444" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1971.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge39" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1937.7223,-175.3279C1912.83,-163.6695 1877.6262,-148.8348 1845.0444,-141 1782.596,-125.9832 1605.9374,-114.3387 1505.7364,-108.7114"/>
<polygon fill="#000000" stroke="#000000" points="1505.8698,-105.2135 1495.6909,-108.153 1505.4812,-112.2027 1505.8698,-105.2135"/>
<text text-anchor="middle" x="1959.0444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- study_personnel -->
<g id="node11" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="369.0444" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="369.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge21" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M355.6704,-87.1201C349.3859,-76.4026 344.8767,-63.1286 353.0444,-54 371.1478,-33.7667 544.6116,-23.6083 629.5887,-19.8125"/>
<polygon fill="#000000" stroke="#000000" points="629.9039,-23.3022 639.7422,-19.3705 629.5994,-16.3088 629.9039,-23.3022"/>
<text text-anchor="middle" x="422.5444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- pathology_file -->
<g id="node12" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1626.0444" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1626.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1612.4281,-347.9134C1597.3389,-325.4844 1577.5448,-287.0354 1597.0444,-261 1645.3538,-196.4986 1694.2075,-234.2964 1771.0444,-210 1774.1483,-209.0185 1777.3475,-207.9857 1780.5637,-206.9317"/>
<polygon fill="#000000" stroke="#000000" points="1781.7984,-210.2097 1790.186,-203.7368 1779.5925,-203.5664 1781.7984,-210.2097"/>
<text text-anchor="middle" x="1658.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge18" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1679.7581,-353.0856C1690.0861,-351.0405 1700.8582,-349.2054 1711.0444,-348 1784.8894,-339.2613 2310.1313,-355.3299 2380.0444,-330 2390.1598,-326.3351 2389.116,-319.1449 2399.0444,-315 2459.378,-289.8123 2480.9738,-310.0201 2545.0444,-297 2550.0712,-295.9785 2555.2818,-294.7584 2560.4555,-293.4413"/>
<polygon fill="#000000" stroke="#000000" points="2561.5409,-296.7742 2570.3014,-290.8156 2559.7372,-290.0106 2561.5409,-296.7742"/>
<text text-anchor="middle" x="2460.0444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge17" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1636.5928,-348.0659C1644.4878,-336.4496 1656.4219,-322.1914 1671.0444,-315 1725.2039,-288.3641 1883.3569,-311.0889 1942.0444,-297 1945.4651,-296.1788 1948.9608,-295.102 1952.4031,-293.8829"/>
<polygon fill="#000000" stroke="#000000" points="1953.8315,-297.0821 1961.8557,-290.1638 1951.2686,-290.5681 1953.8315,-297.0821"/>
<text text-anchor="middle" x="1732.0444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node13" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="580.0444" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="580.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge20" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M567.1843,-173.773C553.4702,-151.8787 535.789,-114.6479 552.0444,-87 569.5247,-57.2687 604.9686,-39.4204 633.5018,-29.3496"/>
<polygon fill="#000000" stroke="#000000" points="634.8793,-32.5801 643.2653,-26.1051 632.6718,-25.9373 634.8793,-32.5801"/>
<text text-anchor="middle" x="638.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M576.0565,-173.9093C574.7685,-162.8318 575.4622,-149.245 584.0444,-141 602.9278,-122.8586 1028.8826,-124.1211 1055.0444,-123 1161.8995,-118.4208 1285.6655,-112.4097 1361.9091,-108.6249"/>
<polygon fill="#000000" stroke="#000000" points="1362.5315,-112.0984 1372.3453,-108.106 1362.1838,-105.107 1362.5315,-112.0984"/>
<text text-anchor="middle" x="713.5444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- therapeutic_procedure -->
<g id="node14" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="2192.0444" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="2192.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2149.0518,-175.1865C2117.039,-163.4578 2071.9801,-148.5971 2031.0444,-141 1932.5407,-122.719 1643.3176,-111.5427 1506.8745,-107.1476"/>
<polygon fill="#000000" stroke="#000000" points="1506.6342,-103.6383 1496.5278,-106.8179 1506.4112,-110.6347 1506.6342,-103.6383"/>
<text text-anchor="middle" x="2182.0444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- synonym -->
<g id="node15" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1256.0444" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1256.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge2" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1203.8703,-278.4558C1035.1282,-276.1606 512.1593,-264.6589 462.0444,-210 406.3882,-149.2974 490.2068,-94.2712 562.0444,-54 583.8673,-41.7664 610.4137,-33.0719 632.3972,-27.296"/>
<polygon fill="#000000" stroke="#000000" points="633.2987,-30.6784 642.1432,-24.8454 631.5916,-23.8897 633.2987,-30.6784"/>
<text text-anchor="middle" x="493.5444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1296.624,-267.5535C1328.7875,-258.3761 1369.5362,-246.4757 1377.0444,-243 1388.1194,-237.8732 1388.434,-231.76 1400.0444,-228 1478.5706,-202.5693 1689.9564,-225.4217 1771.0444,-210 1774.6959,-209.3055 1778.4395,-208.4168 1782.166,-207.4072"/>
<polygon fill="#000000" stroke="#000000" points="1783.3309,-210.7123 1791.9158,-204.5035 1781.3328,-204.0035 1783.3309,-210.7123"/>
<text text-anchor="middle" x="1442.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1295.3833,-267.1603C1325.5723,-256.3841 1366.5981,-237.859 1394.0444,-210 1414.5831,-189.1525 1424.7864,-156.6793 1429.7145,-133.3661"/>
<polygon fill="#000000" stroke="#000000" points="1433.1846,-133.8534 1431.6257,-123.3739 1426.3093,-132.5383 1433.1846,-133.8534"/>
<text text-anchor="middle" x="1458.5444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study_funding -->
<g id="node16" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="810.0444" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="810.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge12" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M783.8898,-88.019C761.7377,-73.6367 729.9526,-53.0001 706.6268,-37.8558"/>
<polygon fill="#000000" stroke="#000000" points="708.4322,-34.8549 698.1389,-32.3449 704.6203,-40.726 708.4322,-34.8549"/>
<text text-anchor="middle" x="813.0444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- methylation_array_file -->
<g id="node18" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1836.0444" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1836.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge29" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1755.4763,-353.0256C1705.7486,-344.6269 1650.7311,-334.4552 1647.0444,-330 1612.4078,-288.1432 1650.5177,-338.3995 1723.0444,-297 1741.5382,-286.4434 1779.3976,-244.3497 1803.1474,-216.7715"/>
<polygon fill="#000000" stroke="#000000" points="1805.8928,-218.9465 1809.7359,-209.0732 1800.5746,-214.3949 1805.8928,-218.9465"/>
<text text-anchor="middle" x="1854.5444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge30" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1950.4882,-363.1081C2132.2409,-358.052 2471.8601,-346.5447 2525.0444,-330 2544.4841,-323.9527 2563.9936,-312.3162 2579.2091,-301.6839"/>
<polygon fill="#000000" stroke="#000000" points="2581.5852,-304.285 2587.6385,-295.5896 2577.484,-298.6122 2581.5852,-304.285"/>
<text text-anchor="middle" x="2647.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge31" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1811.7319,-348.2374C1800.7111,-338.0666 1791.9611,-325.3166 1801.0444,-315 1821.9182,-291.2921 1911.5672,-305.3015 1942.0444,-297 1945.4386,-296.0755 1948.9171,-294.9312 1952.3488,-293.671"/>
<polygon fill="#000000" stroke="#000000" points="1953.8008,-296.8599 1961.7878,-289.8987 1951.203,-290.3598 1953.8008,-296.8599"/>
<text text-anchor="middle" x="1892.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1802.1836,-176.1274C1784.8552,-164.3992 1759.5583,-149.1154 1735.0444,-141 1693.7681,-127.3354 1580.385,-116.3131 1505.1686,-110.2146"/>
<polygon fill="#000000" stroke="#000000" points="1505.0673,-106.6954 1494.8201,-109.387 1504.5092,-113.6732 1505.0673,-106.6954"/>
<text text-anchor="middle" x="1804.5444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_admin -->
<g id="node20" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="976.0444" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="976.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge15" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M949.46,-88.1457C930.5123,-76.8639 904.0655,-62.5643 879.0444,-54 826.9095,-36.1551 764.0639,-26.7536 722.2449,-22.0939"/>
<polygon fill="#000000" stroke="#000000" points="722.4005,-18.5907 712.0854,-21.0092 721.6572,-25.5512 722.4005,-18.5907"/>
<text text-anchor="middle" x="968.5444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- radiology_file -->
<g id="node21" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="791.0444" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="791.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M814.814,-174.762C832.441,-162.9872 857.5601,-148.2525 882.0444,-141 926.8773,-127.7202 1222.9598,-113.811 1362.0705,-107.9156"/>
<polygon fill="#000000" stroke="#000000" points="1362.3692,-111.4062 1372.2129,-107.4882 1362.0744,-104.4124 1362.3692,-111.4062"/>
<text text-anchor="middle" x="941.0444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- family_relationship -->
<g id="node22" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="983.0444" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="983.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M991.8162,-173.953C998.4337,-162.4441 1008.6621,-148.3552 1022.0444,-141 1051.0278,-125.0701 1251.7055,-113.4224 1361.9209,-108.1447"/>
<polygon fill="#000000" stroke="#000000" points="1362.1474,-111.6379 1371.9708,-107.669 1361.8164,-104.6458 1362.1474,-111.6379"/>
<text text-anchor="middle" x="1101.5444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge24" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2611.5919,-260.9938C2615.0174,-237.9328 2617.0072,-198.0787 2596.0444,-174 2494.1901,-57.0063 2411.2719,-111.1485 2258.0444,-87 1950.9617,-38.6041 951.7638,-21.8658 722.9993,-18.6213"/>
<polygon fill="#000000" stroke="#000000" points="722.742,-15.1174 712.6939,-18.4769 722.6439,-22.1167 722.742,-15.1174"/>
<text text-anchor="middle" x="2617.5444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge23" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2569.4819,-267.6422C2561.4276,-265.3657 2552.9747,-263.0465 2545.0444,-261 2510.5952,-252.1101 2501.2923,-252.6362 2467.0444,-243 2446.7506,-237.29 2442.7955,-231.72 2422.0444,-228 2183.4929,-185.2355 2115.4741,-253.4381 1877.0444,-210 1873.3368,-209.3245 1869.5363,-208.4406 1865.756,-207.427"/>
<polygon fill="#000000" stroke="#000000" points="1866.4571,-203.9842 1855.8745,-204.4946 1864.4656,-210.695 1866.4571,-203.9842"/>
<text text-anchor="middle" x="2507.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2592.8752,-261.7819C2582.3688,-250.7767 2567.5321,-236.942 2552.0444,-228 2496.9024,-196.1633 2341.7387,-152.1199 2279.0444,-141 2131.7087,-114.8674 1683.3661,-107.527 1506.7011,-105.6202"/>
<polygon fill="#000000" stroke="#000000" points="1506.5077,-102.1181 1496.4714,-105.5126 1506.434,-109.1177 1506.5077,-102.1181"/>
<text text-anchor="middle" x="2551.5444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge1" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1377.4174,-97.4403C1299.1594,-87.0908 1153.498,-68.18 1029.0444,-54 919.0931,-41.4723 789.6315,-28.7998 722.1819,-22.3544"/>
<polygon fill="#000000" stroke="#000000" points="722.1886,-18.8392 711.9015,-21.3744 721.5242,-25.8076 722.1886,-18.8392"/>
<text text-anchor="middle" x="1201.5444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge34" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2012.164,-277.6046C2085.6206,-273.3131 2280.2635,-257.5827 2319.0444,-210 2329.1527,-197.5975 2325.8666,-188.4726 2319.0444,-174 2217.6818,41.0295 1493.1267,-71.4366 1256.0444,-54 1057.7602,-39.4168 821.0499,-25.9525 722.5768,-20.5264"/>
<polygon fill="#000000" stroke="#000000" points="722.5487,-17.0197 712.3717,-19.9656 722.1646,-24.0091 722.5487,-17.0197"/>
<text text-anchor="middle" x="2331.0444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge33" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1962.4661,-267.2668C1936.07,-252.9139 1891.0161,-228.4159 1859.5004,-211.2792"/>
<polygon fill="#000000" stroke="#000000" points="1861.0514,-208.1386 1850.5942,-206.4365 1857.7075,-214.2883 1861.0514,-208.1386"/>
<text text-anchor="middle" x="1937.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
</g>
</svg>
</div>
