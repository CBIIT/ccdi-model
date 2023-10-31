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
<svg width="2900pt" height="392pt"
 viewBox="0.00 0.00 2899.84 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 2895.8391,-388 2895.8391,4 -4,4"/>
<!-- study_arm -->
<g id="node1" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="59.7947" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="59.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study -->
<g id="node5" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2195.7947" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2195.7947" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge33" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M54.5345,-87.001C52.5119,-75.9601 52.392,-62.3796 60.7947,-54 79.9361,-34.911 1838.094,-20.7107 2149.0611,-18.3473"/>
<polygon fill="#000000" stroke="#000000" points="2149.1191,-21.847 2159.0922,-18.2713 2149.066,-14.8472 2149.1191,-21.847"/>
<text text-anchor="middle" x="109.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- participant -->
<g id="node2" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1305.7947" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1305.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge8" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1365.2253,-99.1905C1531.8005,-82.9073 2000.7368,-37.0675 2149.7388,-22.5021"/>
<polygon fill="#000000" stroke="#000000" points="2150.2934,-25.9647 2159.9054,-21.5083 2149.6123,-18.9979 2150.2934,-25.9647"/>
<text text-anchor="middle" x="1855.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sample -->
<g id="node3" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1125.7947" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1125.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1153.6901,-177.9769C1174.3647,-167.6351 1203.263,-153.2875 1228.7947,-141 1239.9103,-135.6505 1251.9768,-129.956 1263.1881,-124.7123"/>
<polygon fill="#000000" stroke="#000000" points="1264.7822,-127.8308 1272.3647,-120.431 1261.8226,-121.4872 1264.7822,-127.8308"/>
<text text-anchor="middle" x="1265.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cytogenomic_file -->
<g id="node4" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1855.7947" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1855.7947" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1931.0801,-356.1316C1964.2824,-350.2698 1998.3625,-341.6704 2009.7947,-330 2031.3647,-307.9805 2037.9182,-283.4482 2016.7947,-261 1952.8682,-193.0648 1270.3265,-227.9921 1178.7947,-210 1175.1475,-209.2831 1171.407,-208.3786 1167.6825,-207.3585"/>
<polygon fill="#000000" stroke="#000000" points="1168.5198,-203.9557 1157.9359,-204.438 1166.5105,-210.6611 1168.5198,-203.9557"/>
<text text-anchor="middle" x="2101.2947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cell_line -->
<g id="node10" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="727.7947" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="727.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cytogenomic_file&#45;&gt;cell_line -->
<g id="edge15" class="edge">
<title>cytogenomic_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1777.6737,-357.0238C1748.2202,-351.691 1715.0338,-343.2628 1686.7947,-330 1677.0564,-325.4263 1677.8891,-318.7224 1667.7947,-315 1662.6061,-313.0867 992.5565,-288.6136 787.0385,-281.1478"/>
<polygon fill="#000000" stroke="#000000" points="787.153,-277.6497 777.0326,-280.7844 786.8989,-284.6451 787.153,-277.6497"/>
<text text-anchor="middle" x="1758.2947" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- pdx -->
<g id="node23" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1439.7947" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1439.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- cytogenomic_file&#45;&gt;pdx -->
<g id="edge14" class="edge">
<title>cytogenomic_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1852.8233,-347.9618C1849.9574,-336.6103 1844.412,-322.6979 1833.7947,-315 1805.3819,-294.3999 1571.224,-283.7472 1477.9362,-280.2884"/>
<polygon fill="#000000" stroke="#000000" points="1477.9183,-276.7855 1467.7979,-279.9204 1477.6644,-283.7809 1477.9183,-276.7855"/>
<text text-anchor="middle" x="1918.2947" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- methylation_array_file -->
<g id="node6" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="460.7947" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="460.7947" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge23" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M360.2177,-357.0728C276.0124,-349.103 168.4944,-337.5547 161.7947,-330 157.3714,-325.0122 157.4843,-320.0857 161.7947,-315 167.7118,-308.0187 477.7151,-262.1449 486.7947,-261 552.0777,-252.7678 1012.5682,-224.304 1076.7947,-210 1079.4402,-209.4108 1082.1363,-208.7136 1084.8351,-207.9417"/>
<polygon fill="#000000" stroke="#000000" points="1086.0523,-211.2278 1094.5341,-204.8789 1083.9443,-204.5527 1086.0523,-211.2278"/>
<text text-anchor="middle" x="578.2947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge21" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M455.797,-347.8374C453.9943,-337.0135 454.0171,-323.7269 461.7947,-315 462.2299,-314.5116 593.0972,-296.9737 671.0855,-286.5604"/>
<polygon fill="#000000" stroke="#000000" points="671.8047,-289.9956 681.2536,-285.2031 670.8784,-283.0571 671.8047,-289.9956"/>
<text text-anchor="middle" x="553.2947" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge22" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M572.0951,-360.8795C655.0026,-355.8237 760.5288,-346.4052 800.7947,-330 810.7583,-325.9406 809.687,-318.6863 819.7947,-315 880.1589,-292.9851 1335.0623,-310.8973 1397.7947,-297 1401.2293,-296.2391 1404.7342,-295.2018 1408.182,-294.0065"/>
<polygon fill="#000000" stroke="#000000" points="1409.5961,-297.2119 1417.6417,-290.3186 1407.0534,-290.69 1409.5961,-297.2119"/>
<text text-anchor="middle" x="911.2947" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study_personnel -->
<g id="node7" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2329.7947" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2329.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge38" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2303.3206,-87.8116C2281.2724,-73.4967 2249.8454,-53.0926 2226.6581,-38.0382"/>
<polygon fill="#000000" stroke="#000000" points="2228.5047,-35.0642 2218.2115,-32.5542 2224.6929,-40.9353 2228.5047,-35.0642"/>
<text text-anchor="middle" x="2340.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- therapeutic_procedure -->
<g id="node8" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="1305.7947" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="1305.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1305.7947,-173.9735C1305.7947,-162.1918 1305.7947,-146.5607 1305.7947,-133.1581"/>
<polygon fill="#000000" stroke="#000000" points="1309.2948,-133.0033 1305.7947,-123.0034 1302.2948,-133.0034 1309.2948,-133.0033"/>
<text text-anchor="middle" x="1398.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- radiology_file -->
<g id="node9" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1514.7947" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1514.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1511.4305,-173.8059C1508.423,-162.6873 1502.8675,-149.0933 1492.7947,-141 1474.8243,-126.561 1420.9418,-117.1703 1375.6052,-111.6125"/>
<polygon fill="#000000" stroke="#000000" points="1375.8262,-108.1144 1365.4846,-110.4168 1375.0048,-115.066 1375.8262,-108.1144"/>
<text text-anchor="middle" x="1563.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M773.7485,-271.9293C821.8128,-263.0257 898.1406,-244.5308 955.7947,-210 975.2067,-198.3735 971.9465,-184.8651 991.7947,-174 1068.0102,-132.2789 1167.6435,-115.7838 1234.0315,-109.2627"/>
<polygon fill="#000000" stroke="#000000" points="1234.7592,-112.7102 1244.3922,-108.2994 1234.1111,-105.7403 1234.7592,-112.7102"/>
<text text-anchor="middle" x="1032.2947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M773.0462,-271.7057C838.6059,-260.7126 963.5671,-238.158 1067.7947,-210 1072.1491,-208.8236 1076.6679,-207.5377 1081.1746,-206.2118"/>
<polygon fill="#000000" stroke="#000000" points="1082.3837,-209.5031 1090.9525,-203.272 1080.3682,-202.7995 1082.3837,-209.5031"/>
<text text-anchor="middle" x="1035.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge30" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M692.9541,-266.1646C686.6433,-264.1911 680.0723,-262.3608 673.7947,-261 568.3146,-238.1342 262.9947,-290.225 190.7947,-210 169.8622,-186.7408 182.2035,-162.6518 204.7947,-141 254.142,-93.7047 281.9118,-101.0952 348.7947,-87 529.5711,-48.9023 1879.8429,-23.5095 2149.1482,-18.7948"/>
<polygon fill="#000000" stroke="#000000" points="2149.42,-22.2907 2159.3575,-18.6169 2149.298,-15.2918 2149.42,-22.2907"/>
<text text-anchor="middle" x="245.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- pathology_file -->
<g id="node11" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="170.7947" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="170.7947" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M153.938,-348.1775C134.3428,-325.3151 107.4879,-285.6754 130.7947,-261 219.1358,-167.4714 580.3214,-234.8094 708.7947,-228 790.5555,-223.6665 996.5587,-226.303 1076.7947,-210 1079.584,-209.4333 1082.4263,-208.7347 1085.2668,-207.9451"/>
<polygon fill="#000000" stroke="#000000" points="1086.327,-211.2808 1094.8369,-204.9695 1084.2487,-204.5964 1086.327,-211.2808"/>
<text text-anchor="middle" x="191.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge24" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M165.5212,-347.5801C163.6148,-336.6594 163.6253,-323.3613 171.7947,-315 188.1161,-298.295 568.5287,-299.0342 591.7947,-297 618.2646,-294.6857 647.4921,-290.9701 672.0467,-287.514"/>
<polygon fill="#000000" stroke="#000000" points="672.8583,-290.9336 682.2623,-286.0535 671.8676,-284.0041 672.8583,-290.9336"/>
<text text-anchor="middle" x="232.7947" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge25" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M221.4636,-352.5257C243.8194,-346.2336 270.2993,-338.3049 293.7947,-330 310.1372,-324.2235 312.8272,-318.5424 329.7947,-315 562.1517,-266.4889 1165.6856,-346.6839 1397.7947,-297 1401.2346,-296.2637 1404.743,-295.2424 1408.1929,-294.0569"/>
<polygon fill="#000000" stroke="#000000" points="1409.6011,-297.2647 1417.6555,-290.3815 1407.0667,-290.7396 1409.6011,-297.2647"/>
<text text-anchor="middle" x="390.7947" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- study_admin -->
<g id="node12" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="2504.7947" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2504.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge29" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2480.0316,-87.9986C2462.337,-76.6493 2437.5504,-62.3296 2413.7947,-54 2356.7034,-33.9817 2287.2158,-24.9652 2242.2748,-20.9926"/>
<polygon fill="#000000" stroke="#000000" points="2242.494,-17.4988 2232.2371,-20.1532 2241.9106,-24.4744 2242.494,-17.4988"/>
<text text-anchor="middle" x="2501.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- synonym -->
<g id="node13" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2251.7947" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2251.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2232.7162,-262.1793C2220.1849,-251.6085 2203.1421,-238.109 2186.7947,-228 2170.9004,-218.1711 2165.3982,-218.5766 2148.7947,-210 2093.1048,-181.2332 2086.0242,-158.358 2025.7947,-141 1964.8053,-123.423 1548.3793,-111.0976 1378.1127,-106.7377"/>
<polygon fill="#000000" stroke="#000000" points="1378.0768,-103.2357 1367.9911,-106.4805 1377.8989,-110.2335 1378.0768,-103.2357"/>
<text text-anchor="middle" x="2191.2947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2211.3973,-267.6037C2202.9595,-265.3299 2194.1036,-263.0216 2185.7947,-261 2148.6962,-251.9735 2138.7765,-252.4933 2101.7947,-243 2079.3226,-237.2314 2074.7135,-231.6055 2051.7947,-228 1860.1109,-197.8453 1369.9057,-243.5946 1178.7947,-210 1175.083,-209.3475 1171.2796,-208.4797 1167.4974,-207.4767"/>
<polygon fill="#000000" stroke="#000000" points="1168.1946,-204.0333 1157.613,-204.561 1166.2141,-210.7473 1168.1946,-204.0333"/>
<text text-anchor="middle" x="2144.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge6" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2248.6537,-260.6333C2244.0488,-234.1295 2235.0082,-183.6562 2225.7947,-141 2218.6888,-108.1016 2209.3503,-70.5526 2202.9924,-45.6868"/>
<polygon fill="#000000" stroke="#000000" points="2206.345,-44.6706 2200.4652,-35.8571 2199.5655,-46.4136 2206.345,-44.6706"/>
<text text-anchor="middle" x="2271.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- clinical_measure_file -->
<g id="node14" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="308.7947" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="308.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M300.1843,-173.6561C296.4745,-162.7639 294.624,-149.4692 302.7947,-141 318.9355,-124.2694 1005.5726,-110.4091 1233.2777,-106.2654"/>
<polygon fill="#000000" stroke="#000000" points="1233.5124,-109.7618 1243.4474,-106.0813 1233.3856,-102.763 1233.5124,-109.7618"/>
<text text-anchor="middle" x="432.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge12" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M295.7991,-173.967C289.7352,-163.1918 285.4875,-149.911 293.7947,-141 359.127,-70.9191 1863.443,-26.9583 2149.1714,-19.2258"/>
<polygon fill="#000000" stroke="#000000" points="2149.2989,-22.7237 2159.201,-18.9557 2149.1104,-15.7262 2149.2989,-22.7237"/>
<text text-anchor="middle" x="719.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- diagnosis -->
<g id="node15" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1660.7947" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1660.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1653.5331,-173.8514C1647.9768,-162.4533 1639.1535,-148.5304 1626.7947,-141 1605.9502,-128.2992 1464.983,-116.2227 1376.9263,-109.7959"/>
<polygon fill="#000000" stroke="#000000" points="1376.9524,-106.2887 1366.7263,-109.0594 1376.4482,-113.2706 1376.9524,-106.2887"/>
<text text-anchor="middle" x="1687.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- medical_history -->
<g id="node16" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1818.7947" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1818.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1796.6272,-174.3746C1780.6802,-162.739 1758.13,-148.3337 1735.7947,-141 1671.3903,-119.8532 1483.153,-110.614 1378.3507,-107.0149"/>
<polygon fill="#000000" stroke="#000000" points="1378.2779,-103.5105 1368.1663,-106.6738 1378.0435,-110.5066 1378.2779,-103.5105"/>
<text text-anchor="middle" x="1835.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- exposure -->
<g id="node17" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1974.7947" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1974.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1958.0802,-174.7108C1945.4825,-162.9113 1927.1202,-148.168 1907.7947,-141 1859.353,-123.0326 1527.7169,-111.3702 1378.3972,-106.9717"/>
<polygon fill="#000000" stroke="#000000" points="1378.0655,-103.4606 1367.9677,-106.6676 1377.8614,-110.4576 1378.0655,-103.4606"/>
<text text-anchor="middle" x="1978.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node18" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1474.7947" cy="-366" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="1474.7947" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1598.2687,-357.9462C1751.2352,-347.8963 1992.1135,-331.8019 1993.7947,-330 1998.3427,-325.1256 1998.2857,-319.927 1993.7947,-315 1979.2114,-299.001 1821.2601,-299.8069 1799.7947,-297 1617.439,-273.1546 1574.2468,-251.0965 1391.7947,-228 1297.5428,-216.0687 1271.793,-229.4191 1178.7947,-210 1175.2067,-209.2508 1171.5255,-208.3316 1167.8564,-207.3088"/>
<polygon fill="#000000" stroke="#000000" points="1168.8296,-203.9466 1158.2446,-204.4049 1166.805,-210.6475 1168.8296,-203.9466"/>
<text text-anchor="middle" x="1908.2947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge18" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1376.8256,-353.2565C1360.4691,-351.3435 1343.6642,-349.5095 1327.7947,-348 1210.2759,-336.822 1179.2451,-349.3627 1062.7947,-330 1037.3774,-325.7738 1032.0726,-319.9931 1006.7947,-315 931.2424,-300.0762 842.9102,-289.8787 786.2068,-284.2473"/>
<polygon fill="#000000" stroke="#000000" points="786.2906,-280.7388 775.9973,-283.2488 785.6091,-287.7056 786.2906,-280.7388"/>
<text text-anchor="middle" x="1171.2947" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge19" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1460.9305,-348.0736C1457.1769,-342.524 1453.4287,-336.2262 1450.7947,-330 1447.7376,-322.7737 1445.49,-314.5984 1443.8539,-306.9437"/>
<polygon fill="#000000" stroke="#000000" points="1447.2662,-306.15 1441.9836,-296.9661 1440.3861,-307.4398 1447.2662,-306.15"/>
<text text-anchor="middle" x="1559.2947" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- molecular_test -->
<g id="node19" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="520.7947" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="520.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M541.082,-174.4104C556.8285,-161.1785 577.6342,-144.713 587.7947,-141 647.2093,-119.2876 1062.813,-109.3871 1233.192,-106.2071"/>
<polygon fill="#000000" stroke="#000000" points="1233.3878,-109.7042 1243.3216,-106.0206 1233.2588,-102.7054 1233.3878,-109.7042"/>
<text text-anchor="middle" x="651.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- sequencing_file -->
<g id="node20" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1235.7947" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1235.7947" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge36" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1244.7689,-348.0733C1248.5218,-338.0816 1251.1189,-325.5619 1246.7947,-315 1228.9238,-271.3507 1187.2613,-234.8641 1157.8348,-213.242"/>
<polygon fill="#000000" stroke="#000000" points="1159.6806,-210.2588 1149.5129,-207.2808 1155.6042,-215.9495 1159.6806,-210.2588"/>
<text text-anchor="middle" x="1304.2947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge34" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1153.0887,-363.7083C999.4764,-359.0462 684.1298,-347.4032 667.7947,-330 656.7426,-318.2252 668.6647,-306.4582 684.7125,-297.1988"/>
<polygon fill="#000000" stroke="#000000" points="686.7251,-300.094 693.9326,-292.3286 683.4556,-293.9044 686.7251,-300.094"/>
<text text-anchor="middle" x="734.2947" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge35" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1256.4612,-348.368C1270.6069,-337.1881 1290.2715,-323.3141 1309.7947,-315 1346.5238,-299.3586 1359.6963,-308.9243 1397.7947,-297 1400.9745,-296.0048 1404.2414,-294.8516 1407.4813,-293.6191"/>
<polygon fill="#000000" stroke="#000000" points="1409.0504,-296.7599 1417.0055,-289.7623 1406.4229,-290.2716 1409.0504,-296.7599"/>
<text text-anchor="middle" x="1376.2947" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- study_funding -->
<g id="node21" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2670.7947" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2670.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge37" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2641.767,-88.0911C2620.3839,-76.4757 2590.2029,-61.7961 2561.7947,-54 2502.762,-37.7995 2326.8202,-25.6706 2242.2268,-20.6031"/>
<polygon fill="#000000" stroke="#000000" points="2242.3229,-17.1028 2232.1337,-20.0061 2241.9095,-24.0905 2242.3229,-17.1028"/>
<text text-anchor="middle" x="2663.7947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- follow_up -->
<g id="node22" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="673.7947" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="673.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M692.2959,-174.987C706.3838,-163.1591 726.8626,-148.2618 747.7947,-141 792.5042,-125.4893 1092.8476,-112.7209 1233.4523,-107.5162"/>
<polygon fill="#000000" stroke="#000000" points="1233.8369,-111.0046 1243.7016,-107.1398 1233.5799,-104.0093 1233.8369,-111.0046"/>
<text text-anchor="middle" x="792.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge39" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1416.9203,-268.4964C1410.7778,-265.8693 1404.0913,-263.1814 1397.7947,-261 1344.3134,-242.4716 1329.9839,-240.5579 1274.7947,-228 1232.4665,-218.3685 1220.7861,-221.0077 1178.7947,-210 1175.4504,-209.1233 1172.0119,-208.1426 1168.5701,-207.1038"/>
<polygon fill="#000000" stroke="#000000" points="1169.5268,-203.7356 1158.9369,-204.0603 1167.4179,-210.4104 1169.5268,-203.7356"/>
<text text-anchor="middle" x="1363.7947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge40" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1467.1847,-274.9508C1497.0196,-270.7135 1546.1854,-264.2365 1588.7947,-261 1620.5522,-258.5877 2138.3299,-264.5352 2161.7947,-243 2195.4244,-212.1358 2167.1066,-186.1534 2173.7947,-141 2178.6339,-108.3288 2185.4985,-71.0134 2190.2677,-46.1336"/>
<polygon fill="#000000" stroke="#000000" points="2193.7105,-46.7645 2192.1714,-36.2821 2186.8377,-45.4364 2193.7105,-46.7645"/>
<text text-anchor="middle" x="2197.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- publication -->
<g id="node24" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="2828.7947" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="2828.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge2" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2803.5247,-88.2959C2784.199,-76.4591 2756.4296,-61.4146 2729.7947,-54 2638.6494,-28.6271 2354.6044,-20.8411 2242.2304,-18.7176"/>
<polygon fill="#000000" stroke="#000000" points="2242.2813,-15.218 2232.219,-18.5349 2242.1535,-22.2169 2242.2813,-15.218"/>
<text text-anchor="middle" x="2816.7947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- family_relationship -->
<g id="node25" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="846.7947" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="846.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M841.6269,-173.6816C839.7602,-162.799 839.7755,-149.5055 847.7947,-141 860.8167,-127.1884 1107.8111,-114.0079 1233.5455,-108.1596"/>
<polygon fill="#000000" stroke="#000000" points="1234.0262,-111.6413 1243.8542,-107.6839 1233.7035,-104.6487 1234.0262,-111.6413"/>
<text text-anchor="middle" x="927.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
</g>
</svg>
</div>
