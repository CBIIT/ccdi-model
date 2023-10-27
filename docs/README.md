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
<svg width="2812pt" height="392pt"
 viewBox="0.00 0.00 2812.34 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 2808.3385,-388 2808.3385,4 -4,4"/>
<!-- study_funding -->
<g id="node1" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="77.3431" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="77.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study -->
<g id="node11" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1010.3431" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1010.3431" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge14" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M81.1891,-86.9646C84.6595,-75.4607 91.0234,-61.3731 102.3431,-54 138.6951,-30.3221 783.1056,-20.7541 963.6638,-18.531"/>
<polygon fill="#000000" stroke="#000000" points="963.9367,-22.028 973.8934,-18.4068 963.8517,-15.0285 963.9367,-22.028"/>
<text text-anchor="middle" x="164.3431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- medical_history -->
<g id="node2" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="701.3431" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="701.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- participant -->
<g id="node7" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1472.3431" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1472.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M726.5161,-174.619C745.1589,-162.775 771.6744,-148.0163 797.3431,-141 882.5309,-117.7148 1106.1637,-127.8533 1194.3431,-123 1264.8096,-119.1216 1345.2651,-113.8165 1401.4284,-109.9711"/>
<polygon fill="#000000" stroke="#000000" points="1401.8881,-113.4479 1411.6247,-109.2708 1401.4084,-106.4643 1401.8881,-113.4479"/>
<text text-anchor="middle" x="865.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- pathology_file -->
<g id="node3" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="623.3431" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="623.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pdx -->
<g id="node8" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1615.3431" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1615.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge6" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M671.4362,-352.0091C721.2896,-337.6125 793.8172,-317.0058 807.3431,-315 971.8148,-290.6095 1391.1375,-323.1218 1555.3431,-297 1563.8187,-295.6517 1572.7704,-293.4242 1581.0992,-290.9877"/>
<polygon fill="#000000" stroke="#000000" points="1582.3604,-294.2611 1590.8757,-287.9571 1580.2878,-287.575 1582.3604,-294.2611"/>
<text text-anchor="middle" x="868.3431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- sample -->
<g id="node16" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1615.3431" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1615.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M613.7882,-347.8449C609.6743,-337.2907 607.2425,-324.2842 614.3431,-315 670.0162,-242.2063 723.5901,-279.5152 813.3431,-261 914.9135,-240.047 941.0415,-237.1826 1044.3431,-228 1269.3753,-207.9967 1329.1973,-245.2923 1552.3431,-210 1558.5367,-209.0204 1564.9841,-207.6281 1571.2889,-206.0462"/>
<polygon fill="#000000" stroke="#000000" points="1572.2696,-209.407 1581.0219,-203.4364 1570.4566,-202.6458 1572.2696,-209.407"/>
<text text-anchor="middle" x="874.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- cell_line -->
<g id="node24" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="1177.3431" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="1177.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge7" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M618.0702,-347.5807C616.164,-336.6602 616.1746,-323.3622 624.3431,-315 640.5853,-298.3728 1019.1889,-299.038 1042.3431,-297 1068.5174,-294.6961 1097.4057,-291.0007 1121.72,-287.556"/>
<polygon fill="#000000" stroke="#000000" points="1122.4396,-290.9885 1131.8391,-286.0998 1121.4425,-284.0599 1122.4396,-290.9885"/>
<text text-anchor="middle" x="685.3431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- family_relationship -->
<g id="node4" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="904.3431" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="904.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge36" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M918.1171,-174.0361C928.1599,-162.4064 942.8541,-148.1445 959.3431,-141 964.3539,-138.8289 1261.5765,-118.9339 1401.2559,-109.686"/>
<polygon fill="#000000" stroke="#000000" points="1401.6922,-113.1649 1411.4393,-109.0122 1401.23,-106.1802 1401.6922,-113.1649"/>
<text text-anchor="middle" x="1038.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- molecular_test -->
<g id="node5" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1102.3431" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1102.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1109.9385,-173.8222C1115.709,-162.4118 1124.8031,-148.4861 1137.3431,-141 1159.4305,-127.8143 1309.3343,-115.7518 1400.9725,-109.4946"/>
<polygon fill="#000000" stroke="#000000" points="1401.2816,-112.9818 1411.0229,-108.8156 1400.8097,-105.9977 1401.2816,-112.9818"/>
<text text-anchor="middle" x="1201.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- publication -->
<g id="node6" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="235.3431" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="235.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge37" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M230.0804,-86.5906C228.178,-75.6738 228.189,-62.3762 236.3431,-54 261.7938,-27.856 800.1632,-20.168 963.6661,-18.4319"/>
<polygon fill="#000000" stroke="#000000" points="963.9211,-21.9295 973.8842,-18.326 963.8485,-14.9299 963.9211,-21.9295"/>
<text text-anchor="middle" x="287.3431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge17" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1422.8824,-93.8879C1374.0647,-83.0832 1297.2372,-66.5152 1230.3431,-54 1169.9917,-42.7089 1099.9541,-31.587 1055.4117,-24.7607"/>
<polygon fill="#000000" stroke="#000000" points="1055.8971,-21.2943 1045.4835,-23.2456 1054.8411,-28.2142 1055.8971,-21.2943"/>
<text text-anchor="middle" x="1354.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge16" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1643.2818,-277.9165C1756.2305,-273.2547 2174.8819,-253.1542 2213.3431,-210 2223.9887,-198.0555 2219.5762,-188.736 2213.3431,-174 2157.3396,-41.5988 2361.2206,-150.7043 1409.3431,-54 1281.89,-41.0516 1131.2882,-28.0995 1056.8282,-21.8521"/>
<polygon fill="#000000" stroke="#000000" points="1056.6637,-18.3262 1046.4066,-20.9798 1056.0798,-25.3018 1056.6637,-18.3262"/>
<text text-anchor="middle" x="2229.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1615.3431,-260.9735C1615.3431,-249.1918 1615.3431,-233.5607 1615.3431,-220.1581"/>
<polygon fill="#000000" stroke="#000000" points="1618.8432,-220.0033 1615.3431,-210.0034 1611.8432,-220.0034 1618.8432,-220.0033"/>
<text text-anchor="middle" x="1639.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study_admin -->
<g id="node9" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="923.3431" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="923.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge25" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M935.6609,-87.0946C943.1002,-76.8762 953.1002,-64.1262 963.3431,-54 968.6699,-48.734 974.7726,-43.5488 980.7778,-38.8252"/>
<polygon fill="#000000" stroke="#000000" points="982.9834,-41.5451 988.8244,-32.7057 978.746,-35.9733 982.9834,-41.5451"/>
<text text-anchor="middle" x="1019.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node10" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2050.3431" cy="-366" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="2050.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge30" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2048.4261,-347.7652C2046.2243,-336.4825 2041.4958,-322.7221 2031.3431,-315 2001.6591,-292.4224 1750.8893,-282.8805 1653.6544,-280.0059"/>
<polygon fill="#000000" stroke="#000000" points="1653.4828,-276.4996 1643.3862,-279.7104 1653.2814,-283.4967 1653.4828,-276.4996"/>
<text text-anchor="middle" x="2150.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge29" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2144.4634,-352.8501C2199.5905,-344.689 2259.2352,-334.8605 2263.3431,-330 2267.6465,-324.9083 2267.628,-320.1073 2263.3431,-315 2177.0463,-212.1408 1798.3999,-243.3525 1668.3431,-210 1664.9942,-209.1412 1661.5524,-208.1734 1658.1083,-207.1435"/>
<polygon fill="#000000" stroke="#000000" points="1659.0603,-203.774 1648.471,-204.1157 1656.9621,-210.4522 1659.0603,-203.774"/>
<text text-anchor="middle" x="2350.8431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge31" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1915.485,-362.2724C1806.762,-357.9272 1663.2511,-348.7819 1608.3431,-330 1596.796,-326.0502 1596.8769,-318.9887 1585.3431,-315 1583.2964,-314.2922 1347.8447,-293.7927 1235.5975,-284.05"/>
<polygon fill="#000000" stroke="#000000" points="1235.7212,-280.5477 1225.456,-283.17 1235.116,-287.5215 1235.7212,-280.5477"/>
<text text-anchor="middle" x="1716.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- cytogenomic_file -->
<g id="node12" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1408.3431" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1408.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;pdx -->
<g id="edge39" class="edge">
<title>cytogenomic_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1415.7218,-348.0386C1421.3275,-336.7195 1430.1619,-322.8143 1442.3431,-315 1485.1479,-287.5406 1505.7663,-308.3318 1555.3431,-297 1563.6342,-295.1049 1572.4588,-292.6879 1580.7173,-290.2447"/>
<polygon fill="#000000" stroke="#000000" points="1581.8897,-293.5465 1590.4362,-287.2849 1579.8503,-286.8501 1581.8897,-293.5465"/>
<text text-anchor="middle" x="1513.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge40" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1408.1831,-347.7091C1408.9601,-324.7107 1413.6716,-285.3034 1435.3431,-261 1444.7921,-250.4035 1520.7994,-223.5388 1570.9782,-206.6281"/>
<polygon fill="#000000" stroke="#000000" points="1572.2745,-209.885 1580.6423,-203.3864 1570.0483,-203.2484 1572.2745,-209.885"/>
<text text-anchor="middle" x="1506.8431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;cell_line -->
<g id="edge38" class="edge">
<title>cytogenomic_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1335.7845,-355.302C1308.5697,-349.7692 1277.8362,-341.6541 1251.3431,-330 1248.886,-328.9191 1227.6817,-314.2592 1208.5984,-300.9337"/>
<polygon fill="#000000" stroke="#000000" points="1210.5342,-298.0165 1200.3334,-295.1538 1206.5226,-303.753 1210.5342,-298.0165"/>
<text text-anchor="middle" x="1322.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- study_personnel -->
<g id="node13" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="1098.3431" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1098.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge13" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1093.7395,-86.8292C1090.3311,-76.2695 1084.7898,-63.2627 1076.3431,-54 1068.6671,-45.5824 1058.5533,-38.7199 1048.5563,-33.3307"/>
<polygon fill="#000000" stroke="#000000" points="1049.9909,-30.1349 1039.4814,-28.7931 1046.8604,-36.3959 1049.9909,-30.1349"/>
<text text-anchor="middle" x="1156.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- therapeutic_procedure -->
<g id="node14" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="1318.3431" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="1318.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1287.0245,-174.5864C1273.5262,-164.862 1262.783,-152.4346 1272.3431,-141 1288.6184,-121.5337 1349.7452,-112.5773 1400.1835,-108.4659"/>
<polygon fill="#000000" stroke="#000000" points="1400.7331,-111.9342 1410.4377,-107.6833 1400.2003,-104.9545 1400.7331,-111.9342"/>
<text text-anchor="middle" x="1365.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- methylation_array_file -->
<g id="node15" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2321.3431" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2321.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge34" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2306.6504,-347.9486C2295.985,-336.2798 2280.4689,-322.0072 2263.3431,-315 2207.0493,-291.9665 1784.7004,-282.1772 1653.8635,-279.6769"/>
<polygon fill="#000000" stroke="#000000" points="1653.5988,-276.1714 1643.5348,-279.4832 1653.4674,-283.1702 1653.5988,-276.1714"/>
<text text-anchor="middle" x="2377.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge33" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2410.4549,-354.4505C2438.637,-348.8445 2464.722,-340.9015 2473.3431,-330 2485.6425,-314.4473 2493.8265,-288.0904 2463.3431,-261 2452.856,-251.6801 1973.3448,-228.8914 1959.3431,-228 1830.0244,-219.7668 1795.4781,-235.0561 1668.3431,-210 1664.6963,-209.2813 1660.9561,-208.3755 1657.2317,-207.3546"/>
<polygon fill="#000000" stroke="#000000" points="1658.0693,-203.9518 1647.4854,-204.4327 1656.0591,-210.657 1658.0693,-203.9518"/>
<text text-anchor="middle" x="2574.8431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge32" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2240.1001,-353.1007C2225.8771,-351.159 2211.1991,-349.356 2197.3431,-348 2119.1702,-340.3499 1917.865,-357.6418 1844.3431,-330 1834.2725,-326.2138 1835.4325,-318.736 1825.3431,-315 1779.5622,-298.0478 1435.0637,-300.0953 1386.3431,-297 1335.1378,-293.7469 1276.9941,-288.6228 1235.0568,-284.6723"/>
<polygon fill="#000000" stroke="#000000" points="1235.3127,-281.181 1225.0268,-283.7208 1234.6516,-288.1497 1235.3127,-281.181"/>
<text text-anchor="middle" x="1935.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1590.4344,-176.8458C1567.6718,-162.9971 1533.7503,-142.3596 1508.0957,-126.7515"/>
<polygon fill="#000000" stroke="#000000" points="1509.7603,-123.6674 1499.3979,-121.4599 1506.1219,-129.6476 1509.7603,-123.6674"/>
<text text-anchor="middle" x="1589.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- clinical_measure_file -->
<g id="node17" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="489.3431" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="489.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M487.3104,-173.8984C487.1463,-162.6704 489.1461,-148.921 498.3431,-141 512.9972,-128.3791 1175.0231,-123.875 1194.3431,-123 1264.9577,-119.802 1345.5543,-114.3886 1401.719,-110.3318"/>
<polygon fill="#000000" stroke="#000000" points="1402.194,-113.8066 1411.9139,-109.5909 1401.6865,-106.825 1402.194,-113.8066"/>
<text text-anchor="middle" x="627.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge12" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M482.8464,-173.7982C480.301,-163.2275 479.4192,-150.22 486.3431,-141 544.0125,-64.2067 846.8835,-31.4356 964.0258,-21.5011"/>
<polygon fill="#000000" stroke="#000000" points="964.4368,-24.9791 974.1128,-20.6635 963.8574,-18.0032 964.4368,-24.9791"/>
<text text-anchor="middle" x="661.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- sequencing_file -->
<g id="node18" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="938.3431" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="938.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge2" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1001.0201,-354.0683C1024.0887,-348.4196 1050.0181,-340.5471 1072.3431,-330 1082.7138,-325.1005 1082.4907,-318.7123 1093.3431,-315 1190.5573,-281.7457 1453.9974,-313.8962 1555.3431,-297 1563.8085,-295.5887 1572.7561,-293.337 1581.0844,-290.8973"/>
<polygon fill="#000000" stroke="#000000" points="1582.3434,-294.1715 1590.8618,-287.8718 1580.2741,-287.4843 1582.3434,-294.1715"/>
<text text-anchor="middle" x="1159.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M930.2747,-347.9533C926.9772,-337.924 924.8669,-325.4068 929.3431,-315 943.1319,-282.943 954.7572,-275.8361 986.3431,-261 1100.6492,-207.3099 1427.8748,-231.3572 1552.3431,-210 1558.3044,-208.9771 1564.5072,-207.6026 1570.594,-206.0667"/>
<polygon fill="#000000" stroke="#000000" points="1571.9144,-209.3362 1580.665,-203.363 1570.0994,-202.5756 1571.9144,-209.3362"/>
<text text-anchor="middle" x="1052.8431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge3" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M933.3935,-347.88C931.6089,-337.0721 931.6339,-323.7873 939.3431,-315 942.3434,-311.5802 1051.4431,-296.1478 1120.8722,-286.633"/>
<polygon fill="#000000" stroke="#000000" points="1121.3769,-290.0966 1130.8106,-285.2742 1120.4286,-283.1611 1121.3769,-290.0966"/>
<text text-anchor="middle" x="1005.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- synonym -->
<g id="node19" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2752.3431" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2752.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2721.3919,-264.4264C2656.5416,-234.713 2500.9269,-167.6901 2362.3431,-141 2283.1915,-125.7561 1742.6042,-111.4631 1544.7199,-106.6838"/>
<polygon fill="#000000" stroke="#000000" points="1544.7944,-103.1847 1534.7131,-106.4432 1544.6261,-110.1827 1544.7944,-103.1847"/>
<text text-anchor="middle" x="2630.8431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge27" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2742.9826,-261.1145C2730.4678,-238.5443 2706.4494,-199.5889 2677.3431,-174 2592.521,-99.4282 2562.5356,-82.8577 2453.3431,-54 2384.4094,-35.782 1297.3012,-21.5006 1057.0841,-18.5577"/>
<polygon fill="#000000" stroke="#000000" points="1056.9803,-15.0562 1046.9384,-18.4339 1056.8949,-22.0557 1056.9803,-15.0562"/>
<text text-anchor="middle" x="2696.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2713.1714,-267.0641C2704.4101,-264.7462 2695.1137,-262.5567 2686.3431,-261 2643.8512,-253.4582 2342.4296,-230.4496 2299.3431,-228 2159.29,-220.0375 1806.407,-234.8324 1668.3431,-210 1664.6341,-209.3329 1660.8325,-208.4548 1657.0515,-207.445"/>
<polygon fill="#000000" stroke="#000000" points="1657.7511,-204.002 1647.1689,-204.5187 1655.7637,-210.7139 1657.7511,-204.002"/>
<text text-anchor="middle" x="2534.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study_arm -->
<g id="node20" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2398.3431" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2398.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge4" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2379.9198,-87.7557C2365.8706,-75.8128 2345.4061,-60.873 2324.3431,-54 2263.0106,-33.9869 1284.5168,-21.2378 1057.24,-18.5376"/>
<polygon fill="#000000" stroke="#000000" points="1057.0324,-15.035 1046.9917,-18.4166 1056.9497,-22.0345 1057.0324,-15.035"/>
<text text-anchor="middle" x="2400.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- exposure -->
<g id="node21" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1730.3431" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1730.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1703.9911,-176.2784C1684.282,-165.0925 1656.3598,-150.4326 1630.3431,-141 1600.2958,-130.106 1565.8013,-121.7913 1536.724,-115.9121"/>
<polygon fill="#000000" stroke="#000000" points="1537.1691,-112.4326 1526.6812,-113.9339 1535.8162,-119.3006 1537.1691,-112.4326"/>
<text text-anchor="middle" x="1707.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- radiology_file -->
<g id="node22" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1875.3431" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1875.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1843.607,-175.6606C1819.8996,-164.1675 1786.372,-149.394 1755.3431,-141 1684.985,-121.9665 1601.9977,-112.9195 1544.1521,-108.6672"/>
<polygon fill="#000000" stroke="#000000" points="1544.2343,-105.1644 1534.0128,-107.952 1543.7417,-112.147 1544.2343,-105.1644"/>
<text text-anchor="middle" x="1854.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- diagnosis -->
<g id="node23" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="2021.3431" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="2021.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1995.4991,-175.9103C1975.0895,-164.0654 1945.4588,-148.7305 1917.3431,-141 1849.1964,-122.2627 1652.3155,-111.9522 1544.6963,-107.5712"/>
<polygon fill="#000000" stroke="#000000" points="1544.6996,-104.0686 1534.5675,-107.1656 1544.4195,-111.063 1544.6996,-104.0686"/>
<text text-anchor="middle" x="1999.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1198.1805,-262.4623C1214.2049,-250.7104 1237.4164,-235.6993 1260.3431,-228 1299.4994,-214.8505 1413.9663,-236.863 1445.3431,-210 1467.2637,-191.2329 1472.6125,-157.2855 1473.3765,-133.071"/>
<polygon fill="#000000" stroke="#000000" points="1476.8765,-133.0678 1473.4533,-123.0412 1469.8767,-133.0141 1476.8765,-133.0678"/>
<text text-anchor="middle" x="1507.8431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge22" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1142.8345,-266.0579C1136.4308,-264.0698 1129.7421,-262.2621 1123.3431,-261 1041.1785,-244.7945 428.523,-271.1891 371.3431,-210 300.141,-133.8054 476.8479,-96.322 502.3431,-87 562.7894,-64.8987 579.845,-64.4978 643.3431,-54 757.6445,-35.1032 893.7325,-24.9335 963.6928,-20.5952"/>
<polygon fill="#000000" stroke="#000000" points="964.163,-24.0732 973.9322,-19.9728 963.7383,-17.0861 964.163,-24.0732"/>
<text text-anchor="middle" x="413.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge23" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1207.6398,-264.7772C1234.711,-252.7685 1275.783,-236.2496 1313.3431,-228 1419.5507,-204.6729 1450.5054,-230.2457 1557.3431,-210 1562.1406,-209.0909 1567.1004,-207.9216 1572.007,-206.616"/>
<polygon fill="#000000" stroke="#000000" points="1573.2777,-209.8932 1581.9341,-203.7845 1571.3576,-203.1617 1573.2777,-209.8932"/>
<text text-anchor="middle" x="1353.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- follow_up -->
<g id="node25" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="2149.3431" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="2149.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2124.3484,-175.7578C2104.5833,-163.831 2075.8317,-148.4602 2048.3431,-141 1955.5147,-115.807 1677.9341,-108.1535 1544.9417,-105.9013"/>
<polygon fill="#000000" stroke="#000000" points="1544.9037,-102.4003 1534.8477,-105.7361 1544.789,-109.3994 1544.9037,-102.4003"/>
<text text-anchor="middle" x="2130.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
</g>
</svg>
</div>
