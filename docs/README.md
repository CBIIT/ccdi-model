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
<svg width="2578pt" height="392pt"
 viewBox="0.00 0.00 2578.29 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 2574.2884,-388 2574.2884,4 -4,4"/>
<!-- synonym -->
<g id="node1" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="274.1961" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="274.1961" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- study -->
<g id="node5" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1908.1961" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1908.1961" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge5" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M224.8112,-273.2511C155.8532,-264.092 36.2189,-243.6982 10.1961,-210 -8.9292,-185.2335 2.5682,-163.6139 24.1961,-141 101.174,-60.513 148.9608,-69.8719 259.1961,-54 421.2579,-30.6661 1609.9649,-20.291 1861.515,-18.3445"/>
<polygon fill="#000000" stroke="#000000" points="1861.7958,-21.8425 1871.7686,-18.2658 1861.742,-14.8427 1861.7958,-21.8425"/>
<text text-anchor="middle" x="66.6961" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- participant -->
<g id="node8" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1087.1961" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1087.1961" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M269.6993,-260.7556C265.1446,-237.4369 261.5083,-197.3046 283.1961,-174 287.1815,-169.7175 485.373,-141.5598 491.1961,-141 723.153,-118.7009 784.4387,-155.4383 1015.1961,-123 1020.9179,-122.1957 1026.8444,-121.1208 1032.7283,-119.8949"/>
<polygon fill="#000000" stroke="#000000" points="1033.5456,-123.2987 1042.5467,-117.7102 1032.0252,-116.4658 1033.5456,-123.2987"/>
<text text-anchor="middle" x="325.6961" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- sample -->
<g id="node10" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="891.1961" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="891.1961" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M281.0316,-261.0383C286.4903,-249.4096 295.3681,-235.1481 308.1961,-228 359.6675,-199.319 780.2324,-220.588 838.1961,-210 841.9034,-209.3228 845.7037,-208.4377 849.4839,-207.4232"/>
<polygon fill="#000000" stroke="#000000" points="850.7748,-210.691 859.3651,-204.4896 848.7825,-203.9805 850.7748,-210.691"/>
<text text-anchor="middle" x="350.6961" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- cell_line -->
<g id="node2" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="1717.1961" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="1717.1961" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge24" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1752.3535,-266.187C1758.5721,-264.2357 1765.0301,-262.4071 1771.1961,-261 1882.6027,-235.5766 1946.8353,-295.0106 2023.1961,-210 2069.9458,-157.9549 2086.8683,-109.4374 2044.1961,-54 2033.0774,-39.5551 1988.6888,-29.7161 1953.6077,-24.0226"/>
<polygon fill="#000000" stroke="#000000" points="1953.9506,-20.534 1943.5318,-22.4573 1952.876,-27.451 1953.9506,-20.534"/>
<text text-anchor="middle" x="2105.6961" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1764.8303,-274.1522C1809.2852,-268.7477 1871.4912,-258.6509 1890.1961,-243 1926.954,-212.2438 1958.3511,-175.6098 1925.1961,-141 1898.9266,-113.5777 1358.9447,-106.9419 1159.9781,-105.425"/>
<polygon fill="#000000" stroke="#000000" points="1159.9393,-101.9247 1149.9136,-105.3504 1159.8873,-108.9245 1159.9393,-101.9247"/>
<text text-anchor="middle" x="1978.6961" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- exposure -->
<g id="node3" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="430.1961" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="430.1961" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M455.2638,-175.8129C475.4281,-163.7467 504.9586,-148.1664 533.1961,-141 637.0883,-114.6333 909.0764,-138.0794 1015.1961,-123 1020.9167,-122.1871 1026.8424,-121.1067 1032.7258,-119.8774"/>
<polygon fill="#000000" stroke="#000000" points="1033.5447,-123.2809 1042.5437,-117.689 1032.0217,-116.4485 1033.5447,-123.2809"/>
<text text-anchor="middle" x="576.6961" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- study_admin -->
<g id="node4" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="936.1961" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="936.1961" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M987.2345,-92.5796C996.8186,-90.514 1006.7839,-88.5449 1016.1961,-87 1336.6708,-34.3991 1728.6848,-21.6932 1861.5972,-18.8029"/>
<polygon fill="#000000" stroke="#000000" points="1861.8943,-22.2975 1871.8188,-18.5891 1861.7478,-15.2991 1861.8943,-22.2975"/>
<text text-anchor="middle" x="1316.6961" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- diagnosis -->
<g id="node6" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="556.1961" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="556.1961" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M582.6178,-175.9304C603.8365,-163.929 634.8353,-148.3786 664.1961,-141 815.6905,-102.9284 860.7013,-146.0507 1015.1961,-123 1020.9109,-122.1474 1026.8328,-121.0411 1032.714,-119.7963"/>
<polygon fill="#000000" stroke="#000000" points="1033.54,-123.198 1042.5293,-117.5907 1032.0053,-116.3683 1033.54,-123.198"/>
<text text-anchor="middle" x="708.6961" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- clinical_measure_file -->
<g id="node7" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="128.1961" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="128.1961" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge13" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M117.2918,-173.9208C112.3278,-163.1283 109.1518,-149.8454 117.1961,-141 273.234,30.576 925.6793,-67.6406 1157.1961,-54 1423.7699,-38.2939 1743.8805,-24.7005 1861.7291,-19.873"/>
<polygon fill="#000000" stroke="#000000" points="1861.991,-23.3654 1871.8398,-19.4601 1861.7053,-16.3712 1861.991,-23.3654"/>
<text text-anchor="middle" x="281.1961" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M121.9608,-173.5716C119.536,-162.6477 119.0144,-149.3492 127.1961,-141 144.464,-123.3786 990.7411,-126.2625 1015.1961,-123 1021.0052,-122.225 1027.0229,-121.1572 1032.9918,-119.9251"/>
<polygon fill="#000000" stroke="#000000" points="1033.9396,-123.3001 1042.9453,-117.7191 1032.4248,-116.4659 1033.9396,-123.3001"/>
<text text-anchor="middle" x="256.6961" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge2" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1145.911,-98.7781C1301.6608,-82.2735 1722.9244,-37.6329 1862.5472,-22.8373"/>
<polygon fill="#000000" stroke="#000000" points="1862.9162,-26.3179 1872.4917,-21.7835 1862.1785,-19.3569 1862.9162,-26.3179"/>
<text text-anchor="middle" x="1597.6961" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- family_relationship -->
<g id="node9" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="729.1961" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="729.1961" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M740.7386,-174.0916C749.2898,-162.4868 762.0552,-148.2317 777.1961,-141 825.0571,-118.1403 962.8356,-131.4624 1015.1961,-123 1020.6815,-122.1135 1026.362,-121.0148 1032.0161,-119.8007"/>
<polygon fill="#000000" stroke="#000000" points="1033.1384,-123.1352 1042.1174,-117.5114 1031.5911,-116.3083 1033.1384,-123.1352"/>
<text text-anchor="middle" x="856.6961" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M910.8646,-175.8696C925.1983,-164.7774 945.4813,-150.4066 965.1961,-141 977.2139,-135.2659 1004.9818,-126.9455 1030.9943,-119.7479"/>
<polygon fill="#000000" stroke="#000000" points="1032.1205,-123.0685 1040.8414,-117.052 1030.2721,-116.3169 1032.1205,-123.0685"/>
<text text-anchor="middle" x="1001.6961" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- methylation_array_file -->
<g id="node11" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="625.1961" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="625.1961" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge12" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M707.4882,-353.2162C739.545,-347.3762 776.3932,-339.5957 809.1961,-330 826.6229,-324.9022 829.4101,-318.6516 847.1961,-315 982.2158,-287.2796 1329.5357,-303.9509 1467.1961,-297 1532.8599,-293.6844 1608.0979,-288.0125 1658.7358,-283.9206"/>
<polygon fill="#000000" stroke="#000000" points="1659.157,-287.398 1668.8403,-283.0987 1658.5894,-280.4211 1659.157,-287.398"/>
<text text-anchor="middle" x="938.6961" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M559.2365,-351.1136C497.2846,-334.1588 419.225,-303.2351 456.1961,-261 512.6052,-196.5594 754.8105,-229.5296 838.1961,-210 841.6112,-209.2002 845.1168,-208.2681 848.6195,-207.2569"/>
<polygon fill="#000000" stroke="#000000" points="849.8797,-210.5311 858.406,-204.242 847.8187,-203.8413 849.8797,-210.5311"/>
<text text-anchor="middle" x="547.6961" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- pdx -->
<g id="node16" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1110.1961" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1110.1961" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge11" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M620.0158,-347.6697C618.1444,-336.7827 618.1591,-323.4886 626.1961,-315 641.4715,-298.8664 960.2014,-284.8777 1071.9179,-280.4535"/>
<polygon fill="#000000" stroke="#000000" points="1072.2107,-283.9448 1082.0658,-280.0555 1071.9363,-276.9502 1072.2107,-283.9448"/>
<text text-anchor="middle" x="717.6961" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node12" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1904.1961" cy="-366" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="1904.1961" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge34" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1900.7635,-347.89C1897.7287,-336.8049 1892.1685,-323.2168 1882.1961,-315 1865.873,-301.5505 1815.5428,-291.8265 1774.7205,-285.9005"/>
<polygon fill="#000000" stroke="#000000" points="1774.9628,-282.4003 1764.5732,-284.4758 1773.9894,-289.3323 1774.9628,-282.4003"/>
<text text-anchor="middle" x="2001.6961" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge35" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2008.2208,-354.1489C2057.3035,-347.4869 2106.8045,-338.7666 2114.1961,-330 2118.4935,-324.9032 2118.5236,-320.0713 2114.1961,-315 2015.1637,-198.9439 1926.8464,-277.6923 1775.1961,-261 1683.2444,-250.8788 1034.9617,-227.8656 944.1961,-210 940.5492,-209.2822 936.8088,-208.377 933.0844,-207.3565"/>
<polygon fill="#000000" stroke="#000000" points="933.9218,-203.9537 923.3379,-204.4353 931.912,-210.659 933.9218,-203.9537"/>
<text text-anchor="middle" x="2202.6961" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge36" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1793.7904,-355.2135C1741.3869,-348.9742 1685.0792,-340.3146 1661.1961,-330 1651.3191,-325.7343 1652.2613,-318.8008 1642.1961,-315 1572.6589,-288.7414 1382.3322,-302.3657 1308.1961,-297 1252.4175,-292.963 1187.9326,-286.8259 1148.1043,-282.8641"/>
<polygon fill="#000000" stroke="#000000" points="1148.3403,-279.3704 1138.0415,-281.8572 1147.6433,-286.3356 1148.3403,-279.3704"/>
<text text-anchor="middle" x="1769.6961" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- publication -->
<g id="node13" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="1967.1961" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="1967.1961" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge32" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1954.667,-87.101C1950.6596,-81.338 1946.2201,-74.9135 1942.1961,-69 1936.6567,-60.8593 1930.6798,-51.9406 1925.3053,-43.8698"/>
<polygon fill="#000000" stroke="#000000" points="1928.2082,-41.9143 1919.7591,-35.5219 1922.3777,-45.7881 1928.2082,-41.9143"/>
<text text-anchor="middle" x="1993.1961" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- follow_up -->
<g id="node14" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="1008.1961" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="1008.1961" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1023.9159,-174.5017C1032.7875,-164.644 1044.0888,-152.1157 1054.1961,-141 1057.4474,-137.4244 1060.8868,-133.6563 1064.2695,-129.9587"/>
<polygon fill="#000000" stroke="#000000" points="1066.8803,-132.2902 1071.0545,-122.5522 1061.7187,-127.5617 1066.8803,-132.2902"/>
<text text-anchor="middle" x="1099.1961" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- sequencing_file -->
<g id="node15" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1330.1961" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1330.1961" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge26" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1398.6329,-355.602C1426.4941,-349.9987 1458.5746,-341.7548 1486.1961,-330 1497.4256,-325.2211 1497.8386,-319.4659 1509.1961,-315 1557.246,-296.1062 1615.4045,-287.105 1657.9931,-282.8302"/>
<polygon fill="#000000" stroke="#000000" points="1658.5693,-286.2915 1668.1958,-281.8663 1657.9109,-279.3225 1658.5693,-286.2915"/>
<text text-anchor="middle" x="1575.6961" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge28" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1329.3509,-347.9256C1327.9379,-337.1349 1324.4744,-323.8522 1316.1961,-315 1235.8394,-229.0722 1180.4518,-256.0436 1066.1961,-228 1012.9669,-214.9351 997.474,-222.8654 944.1961,-210 940.7867,-209.1767 937.2851,-208.2277 933.7851,-207.2049"/>
<polygon fill="#000000" stroke="#000000" points="934.5915,-203.7906 924.0035,-204.1698 932.517,-210.4761 934.5915,-203.7906"/>
<text text-anchor="middle" x="1364.6961" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge27" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1263.7006,-355.1532C1237.8552,-349.5524 1208.4504,-341.4293 1183.1961,-330 1178.1272,-327.706 1155.6764,-311.8657 1136.9947,-298.4391"/>
<polygon fill="#000000" stroke="#000000" points="1138.9111,-295.5059 1128.7524,-292.4973 1134.8176,-301.1843 1138.9111,-295.5059"/>
<text text-anchor="middle" x="1249.6961" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge17" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1137.532,-274.7686C1163.8012,-270.8081 1204.6404,-264.928 1240.1961,-261 1308.5695,-253.4465 1804.4424,-254.1477 1857.1961,-210 1869.8822,-199.3835 1892.1974,-96.8443 1902.5841,-46.124"/>
<polygon fill="#000000" stroke="#000000" points="1906.0515,-46.6356 1904.6117,-36.1391 1899.1915,-45.2425 1906.0515,-46.6356"/>
<text text-anchor="middle" x="1904.1961" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1086.3424,-269.5239C1049.4711,-254.8763 978.1549,-226.5453 932.7038,-208.4893"/>
<polygon fill="#000000" stroke="#000000" points="933.7261,-205.1295 923.1404,-204.6902 931.1417,-211.6349 933.7261,-205.1295"/>
<text text-anchor="middle" x="1038.1961" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study_arm -->
<g id="node17" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2146.1961" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2146.1961" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge31" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2126.1113,-87.9498C2111.9062,-76.7279 2091.9455,-62.578 2072.1961,-54 2034.1544,-37.4768 1987.7395,-28.2 1954.0098,-23.2187"/>
<polygon fill="#000000" stroke="#000000" points="1954.3625,-19.7339 1943.9726,-21.8074 1953.3878,-26.6657 1954.3625,-19.7339"/>
<text text-anchor="middle" x="2145.6961" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- medical_history -->
<g id="node18" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1166.1961" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1166.1961" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1161.3741,-174.0221C1157.8882,-163.5307 1152.3423,-150.5281 1144.1961,-141 1139.4377,-135.4344 1133.6008,-130.439 1127.4968,-126.0675"/>
<polygon fill="#000000" stroke="#000000" points="1129.3541,-123.0997 1119.0836,-120.4982 1125.4902,-128.9367 1129.3541,-123.0997"/>
<text text-anchor="middle" x="1222.1961" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- study_funding -->
<g id="node19" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2301.1961" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2301.1961" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge3" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2273.3979,-88.0228C2253.2482,-76.5316 2224.9521,-62.0319 2198.1961,-54 2153.7105,-40.6458 2024.507,-27.9782 1954.5295,-21.8465"/>
<polygon fill="#000000" stroke="#000000" points="1954.5053,-18.3313 1944.2403,-20.9546 1953.9007,-25.3052 1954.5053,-18.3313"/>
<text text-anchor="middle" x="2298.1961" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- study_personnel -->
<g id="node20" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2483.1961" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2483.1961" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge22" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2451.3576,-87.9663C2427.9413,-76.2905 2394.9666,-61.59 2364.1961,-54 2287.4954,-35.0806 2054.5853,-23.8244 1954.6008,-19.7475"/>
<polygon fill="#000000" stroke="#000000" points="1954.6304,-16.246 1944.4979,-19.3417 1954.3494,-23.2403 1954.6304,-16.246"/>
<text text-anchor="middle" x="2476.6961" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- pathology_file -->
<g id="node21" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1037.1961" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1037.1961" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge9" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1110.7594,-361.3465C1168.3898,-356.5769 1250.2442,-347.315 1320.1961,-330 1338.6266,-325.438 1341.7079,-319.3218 1360.1961,-315 1415.2791,-302.1239 1571.8867,-289.3984 1658.2436,-283.0905"/>
<polygon fill="#000000" stroke="#000000" points="1658.6942,-286.5671 1668.4151,-282.3534 1658.1883,-279.5854 1658.6942,-286.5671"/>
<text text-anchor="middle" x="1421.1961" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M963.6712,-360.9737C844.5549,-352.6571 622.0023,-336.3239 616.1961,-330 611.6874,-325.0892 612.57,-320.5942 616.1961,-315 629.7578,-294.0778 775.6974,-236.079 849.2798,-207.8471"/>
<polygon fill="#000000" stroke="#000000" points="850.6452,-211.0723 858.7348,-204.2305 848.1443,-204.5342 850.6452,-211.0723"/>
<text text-anchor="middle" x="778.1961" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge8" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1033.1559,-347.6878C1031.8925,-337.3337 1032.1425,-324.5837 1038.1961,-315 1046.2439,-302.2594 1060.2859,-293.8648 1073.8447,-288.4153"/>
<polygon fill="#000000" stroke="#000000" points="1075.3025,-291.6111 1083.5396,-284.9478 1072.945,-285.02 1075.3025,-291.6111"/>
<text text-anchor="middle" x="1099.1961" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- radiology_file -->
<g id="node22" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1343.1961" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1343.1961" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1330.7086,-174.0562C1321.8473,-162.7446 1308.9396,-148.8412 1294.1961,-141 1270.6836,-128.4951 1206.6505,-118.5434 1155.9697,-112.3005"/>
<polygon fill="#000000" stroke="#000000" points="1156.3747,-108.8241 1146.0275,-111.1017 1155.5366,-115.7737 1156.3747,-108.8241"/>
<text text-anchor="middle" x="1374.1961" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- molecular_test -->
<g id="node23" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1514.1961" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1514.1961" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1493.796,-174.4859C1479.0775,-162.9014 1458.1801,-148.5114 1437.1961,-141 1387.6842,-123.2767 1246.4433,-113.1089 1159.2631,-108.3507"/>
<polygon fill="#000000" stroke="#000000" points="1159.3437,-104.8501 1149.1709,-107.8108 1158.9697,-111.8401 1159.3437,-104.8501"/>
<text text-anchor="middle" x="1531.1961" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- therapeutic_procedure -->
<g id="node24" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="1730.1961" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="1730.1961" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1694.6922,-174.8081C1668.8458,-163.1362 1632.6544,-148.5075 1599.1961,-141 1517.5634,-122.6829 1280.216,-111.8681 1159.5094,-107.4048"/>
<polygon fill="#000000" stroke="#000000" points="1159.3802,-103.8979 1149.2591,-107.0307 1159.1248,-110.8932 1159.3802,-103.8979"/>
<text text-anchor="middle" x="1741.1961" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
</g>
</svg>
</div>
