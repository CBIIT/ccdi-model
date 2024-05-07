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
<svg width="2572pt" height="305pt"
 viewBox="0.00 0.00 2571.58 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 2567.5825,-301 2567.5825,4 -4,4"/>
<!-- family_relationship -->
<g id="node1" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1145.7947" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1145.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- participant -->
<g id="node9" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1222.7947" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1222.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1134.377,-173.7636C1129.4877,-163.4349 1126.2377,-150.6849 1132.7947,-141 1139.5758,-130.984 1149.6436,-123.7545 1160.618,-118.5363"/>
<polygon fill="#000000" stroke="#000000" points="1162.1252,-121.6997 1169.9975,-114.609 1159.4217,-115.2428 1162.1252,-121.6997"/>
<text text-anchor="middle" x="1212.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- cytogenomic_file -->
<g id="node2" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="2180.7947" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="2180.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- sample -->
<g id="node21" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1986.7947" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1986.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2165.3155,-261.0152C2154.9013,-249.9801 2140.2841,-236.4005 2124.7947,-228 2098.2577,-213.6079 2065.6956,-204.7589 2038.867,-199.4376"/>
<polygon fill="#000000" stroke="#000000" points="2039.3636,-195.9698 2028.8898,-197.5666 2038.0734,-202.8498 2039.3636,-195.9698"/>
<text text-anchor="middle" x="2216.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- study_arm -->
<g id="node3" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="59.7947" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="59.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study -->
<g id="node7" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1676.7947" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1676.7947" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge20" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M54.55,-87.0165C52.5336,-75.9818 52.4148,-62.4023 60.7947,-54 89.243,-25.4757 1367.5601,-19.1563 1630.0021,-18.1587"/>
<polygon fill="#000000" stroke="#000000" points="1630.3371,-21.6576 1640.324,-18.1203 1630.311,-14.6576 1630.3371,-21.6576"/>
<text text-anchor="middle" x="109.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node4" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2425.7947" cy="-279" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="2425.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2387.6071,-261.5757C2361.2254,-250.2625 2325.0353,-236.1549 2291.7947,-228 2205.6401,-206.8637 2102.6459,-197.995 2041.0896,-194.3759"/>
<polygon fill="#000000" stroke="#000000" points="2041.0144,-190.8662 2030.8336,-193.7991 2040.6213,-197.8551 2041.0144,-190.8662"/>
<text text-anchor="middle" x="2445.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- radiology_file -->
<g id="node5" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1337.7947" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1337.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1324.2407,-173.9946C1315.7214,-163.4935 1304.0507,-150.4902 1291.7947,-141 1284.1036,-135.0445 1275.2815,-129.5916 1266.5727,-124.8296"/>
<polygon fill="#000000" stroke="#000000" points="1268.0728,-121.6643 1257.5904,-120.125 1264.825,-127.8653 1268.0728,-121.6643"/>
<text text-anchor="middle" x="1365.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node6" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="496.7947" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="496.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge21" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M497.2923,-173.968C498.6136,-162.7686 502.2637,-149.0248 511.7947,-141 598.816,-67.7311 1423.5736,-28.5819 1630.0886,-19.8774"/>
<polygon fill="#000000" stroke="#000000" points="1630.4477,-23.3656 1640.2928,-19.451 1630.1554,-16.3717 1630.4477,-23.3656"/>
<text text-anchor="middle" x="813.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M503.7911,-173.8593C509.2777,-162.3098 518.1241,-148.2108 530.7947,-141 557.3709,-125.8756 978.3406,-112.0644 1150.3864,-107.0229"/>
<polygon fill="#000000" stroke="#000000" points="1150.7193,-110.5148 1160.6131,-106.725 1150.5154,-103.5177 1150.7193,-110.5148"/>
<text text-anchor="middle" x="616.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- synonym -->
<g id="node8" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="942.7947" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="942.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge25" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M890.8281,-278.1896C728.3434,-275.1234 237.9058,-261.6317 190.7947,-210 180.0102,-198.1807 182.557,-187.7164 190.7947,-174 266.9164,-47.2508 1386.0215,-22.5338 1630.039,-18.642"/>
<polygon fill="#000000" stroke="#000000" points="1630.391,-22.137 1640.3354,-18.482 1630.2822,-15.1379 1630.391,-22.137"/>
<text text-anchor="middle" x="275.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M938.6346,-261.0549C934.4441,-238.0598 931.2011,-198.277 951.7947,-174 977.7624,-143.3877 1083.2622,-123.5327 1154.7085,-113.3109"/>
<polygon fill="#000000" stroke="#000000" points="1155.5706,-116.7244 1164.9892,-111.8725 1154.6006,-109.792 1155.5706,-116.7244"/>
<text text-anchor="middle" x="994.2947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge23" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M991.5829,-272.5948C1077.5354,-261.5719 1261.643,-239.1296 1417.7947,-228 1643.5855,-211.907 1703.4464,-246.8241 1926.7947,-210 1932.227,-209.1044 1937.8572,-207.859 1943.3945,-206.4374"/>
<polygon fill="#000000" stroke="#000000" points="1944.4938,-209.7648 1953.1987,-203.7253 1942.6275,-203.0181 1944.4938,-209.7648"/>
<text text-anchor="middle" x="1460.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge2" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1274.8743,-95.02C1364.9797,-77.7531 1548.3843,-42.6073 1632.6522,-26.459"/>
<polygon fill="#000000" stroke="#000000" points="1633.5025,-29.8598 1642.6651,-24.5403 1632.1851,-22.9849 1633.5025,-29.8598"/>
<text text-anchor="middle" x="1527.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_admin -->
<g id="node10" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1608.7947" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1608.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge19" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1604.8606,-86.7537C1603.6326,-76.4216 1603.8826,-63.6716 1609.7947,-54 1615.8671,-44.0661 1625.7045,-36.7046 1635.9931,-31.3219"/>
<polygon fill="#000000" stroke="#000000" points="1637.4865,-34.4874 1645.0675,-27.0861 1634.5256,-28.1444 1637.4865,-34.4874"/>
<text text-anchor="middle" x="1666.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- methylation_array_file -->
<g id="node11" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1475.7947" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1475.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1489.1946,-260.9104C1498.9996,-249.2247 1513.4115,-234.9474 1529.7947,-228 1611.0993,-193.5222 1839.7308,-224.8002 1926.7947,-210 1932.1554,-209.0887 1937.711,-207.8467 1943.1807,-206.438"/>
<polygon fill="#000000" stroke="#000000" points="1944.1676,-209.7966 1952.8729,-203.7577 1942.3018,-203.0498 1944.1676,-209.7966"/>
<text text-anchor="middle" x="1621.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- therapeutic_procedure -->
<g id="node12" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="1671.7947" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="1671.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1587.555,-179.4201C1545.8091,-172.5259 1500.2461,-163.8165 1480.7947,-156 1469.4708,-151.4495 1469.195,-145.3557 1457.7947,-141 1428.2876,-129.7262 1350.0583,-119.0644 1291.9159,-112.3128"/>
<polygon fill="#000000" stroke="#000000" points="1292.0086,-108.8006 1281.6752,-111.1397 1291.2118,-115.7551 1292.0086,-108.8006"/>
<text text-anchor="middle" x="1573.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- pathology_file -->
<g id="node13" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1812.7947" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1812.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge32" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1825.9454,-261.0338C1834.9008,-250.0061 1847.6637,-236.4278 1861.7947,-228 1887.5397,-212.6455 1897.9927,-218.3073 1926.7947,-210 1931.51,-208.64 1936.4272,-207.2002 1941.3286,-205.7509"/>
<polygon fill="#000000" stroke="#000000" points="1942.7107,-208.9914 1951.2976,-202.7854 1940.7148,-202.282 1942.7107,-208.9914"/>
<text text-anchor="middle" x="1922.7947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- cell_line -->
<g id="node14" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="1753.7947" cy="-105" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="1753.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge12" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1744.9018,-86.9358C1739.3542,-76.6643 1731.6042,-63.9143 1722.7947,-54 1718.088,-48.703 1712.5236,-43.6155 1706.9204,-39.0179"/>
<polygon fill="#000000" stroke="#000000" points="1708.8157,-36.0574 1698.7786,-32.665 1704.5094,-41.5761 1708.8157,-36.0574"/>
<text text-anchor="middle" x="1773.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1791.1901,-116.7665C1798.0346,-118.8743 1805.1219,-121.0266 1811.7947,-123 1840.1296,-131.3798 1849.4671,-127.5857 1875.7947,-141 1885.381,-145.8843 1885.4614,-150.6482 1894.7947,-156 1909.4412,-164.3984 1926.4267,-171.661 1941.7869,-177.4194"/>
<polygon fill="#000000" stroke="#000000" points="1941.0109,-180.8611 1951.6051,-180.9831 1943.3993,-174.2811 1941.0109,-180.8611"/>
<text text-anchor="middle" x="1935.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- follow_up -->
<g id="node15" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="1862.7947" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="1862.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1821.9949,-179.7996C1814.3246,-177.7127 1806.3434,-175.6794 1798.7947,-174 1750.866,-163.3368 1735.5586,-173.7913 1689.7947,-156 1678.42,-151.5779 1678.3426,-144.9477 1666.7947,-141 1632.565,-129.2983 1411.1976,-115.4712 1294.5242,-108.8763"/>
<polygon fill="#000000" stroke="#000000" points="1294.435,-105.3659 1284.2543,-108.2992 1294.0422,-112.3548 1294.435,-105.3659"/>
<text text-anchor="middle" x="1734.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- medical_history -->
<g id="node16" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="284.7947" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="284.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M308.5155,-174.5939C326.1189,-162.7377 351.2298,-147.9747 375.7947,-141 412.7387,-130.5104 952.6014,-113.1912 1150.6467,-107.1548"/>
<polygon fill="#000000" stroke="#000000" points="1150.7735,-110.6526 1160.6625,-106.8502 1150.5607,-103.6559 1150.7735,-110.6526"/>
<text text-anchor="middle" x="443.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- pdx -->
<g id="node17" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1848.7947" cy="-105" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1848.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge31" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1842.2115,-87.4147C1837.1614,-76.2545 1829.1202,-62.385 1817.7947,-54 1802.5942,-42.7461 1756.9452,-32.3422 1721.6624,-25.6434"/>
<polygon fill="#000000" stroke="#000000" points="1722.0265,-22.1513 1711.5561,-23.7707 1720.751,-29.0342 1722.0265,-22.1513"/>
<text text-anchor="middle" x="1854.7947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge30" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1870.1954,-117.0069C1875.1832,-119.3506 1880.5677,-121.533 1885.7947,-123 1926.6283,-134.4602 2047.2546,-109.6283 2075.7947,-141 2092.4295,-159.2852 2064.8585,-172.7353 2036.1296,-181.2178"/>
<polygon fill="#000000" stroke="#000000" points="2035.1118,-177.8678 2026.4046,-183.9039 2036.9755,-184.6152 2035.1118,-177.8678"/>
<text text-anchor="middle" x="2104.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- molecular_test -->
<g id="node18" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="702.7947" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="702.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M702.4179,-173.8906C703.2313,-162.6594 706.3288,-148.9093 715.7947,-141 732.1907,-127.3003 1014.0453,-113.7215 1150.2504,-107.9241"/>
<polygon fill="#000000" stroke="#000000" points="1150.7486,-111.4063 1160.5919,-107.487 1150.453,-104.4125 1150.7486,-111.4063"/>
<text text-anchor="middle" x="779.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- publication -->
<g id="node19" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="1957.7947" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="1957.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge3" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1937.5162,-87.685C1923.1537,-76.3449 1902.9329,-62.1626 1882.7947,-54 1830.5735,-32.8332 1765.9557,-24.0997 1723.1666,-20.5038"/>
<polygon fill="#000000" stroke="#000000" points="1723.2885,-17.0028 1713.0467,-19.715 1722.7445,-23.9816 1723.2885,-17.0028"/>
<text text-anchor="middle" x="1959.7947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- exposure -->
<g id="node20" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="853.7947" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="853.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M848.6842,-173.7351C846.8392,-162.8727 846.857,-149.5815 854.7947,-141 874.4436,-119.7574 1048.97,-110.5795 1150.4578,-107.0093"/>
<polygon fill="#000000" stroke="#000000" points="1150.7719,-110.5007 1160.6465,-106.661 1150.5327,-103.5048 1150.7719,-110.5007"/>
<text text-anchor="middle" x="898.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1952.129,-180.6266C1943.888,-178.1945 1935.0811,-175.8146 1926.7947,-174 1870.6759,-161.7108 1851.6185,-178.583 1798.7947,-156 1788.902,-151.7707 1789.8394,-144.8546 1779.7947,-141 1774.1934,-138.8505 1443.657,-118.4665 1294.4792,-109.359"/>
<polygon fill="#000000" stroke="#000000" points="1294.2534,-105.8388 1284.0587,-108.7231 1293.827,-112.8258 1294.2534,-105.8388"/>
<text text-anchor="middle" x="1835.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge4" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1989.3952,-173.9751C1989.9027,-162.924 1988.3876,-149.3416 1979.7947,-141 1952.8541,-114.847 1848.5644,-130.6002 1811.7947,-123 1807.8986,-122.1947 1803.891,-121.2357 1799.8893,-120.1858"/>
<polygon fill="#000000" stroke="#000000" points="1800.5946,-116.7488 1790.0213,-117.4247 1798.7083,-123.4899 1800.5946,-116.7488"/>
<text text-anchor="middle" x="2023.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge5" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2030.2342,-188.2442C2072.5137,-183.5819 2132.4321,-173.9532 2146.7947,-156 2150.9593,-150.7942 2151.3437,-145.8735 2146.7947,-141 2126.9596,-119.7498 1913.8805,-130.496 1885.7947,-123 1883.6077,-122.4163 1881.3952,-121.7013 1879.197,-120.8965"/>
<polygon fill="#000000" stroke="#000000" points="1880.3493,-117.5839 1869.7752,-116.9213 1877.6281,-124.0334 1880.3493,-117.5839"/>
<text text-anchor="middle" x="2186.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- diagnosis -->
<g id="node22" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1663.7947" cy="-279" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1663.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1623.2778,-266.8004C1615.8328,-264.7367 1608.1046,-262.7114 1600.7947,-261 1557.6764,-250.9053 1543.6364,-260.1186 1502.7947,-243 1479.2552,-233.1335 1471.5607,-230.0721 1455.7947,-210 1435.4532,-184.1027 1454.2885,-161.8449 1428.7947,-141 1408.4064,-124.3296 1344.9674,-114.992 1293.8202,-110.0299"/>
<polygon fill="#000000" stroke="#000000" points="1294.0523,-106.5365 1283.771,-109.095 1293.4038,-113.5064 1294.0523,-106.5365"/>
<text text-anchor="middle" x="1500.2947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1685.8408,-262.2562C1702.4841,-250.5621 1726.3838,-235.7142 1749.7947,-228 1824.8949,-203.2533 1849.2425,-225.4303 1926.7947,-210 1931.9295,-208.9783 1937.2548,-207.7044 1942.5175,-206.3092"/>
<polygon fill="#000000" stroke="#000000" points="1943.8108,-209.5816 1952.4941,-203.5111 1941.9204,-202.8417 1943.8108,-209.5816"/>
<text text-anchor="middle" x="1794.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- study_funding -->
<g id="node23" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2115.7947" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2115.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge17" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2088.6228,-87.8683C2068.9052,-76.3042 2041.1717,-61.781 2014.7947,-54 1961.3028,-38.2204 1802.5441,-26.1171 1723.1233,-20.8635"/>
<polygon fill="#000000" stroke="#000000" points="1723.1291,-17.3565 1712.9223,-20.1975 1722.673,-24.3416 1723.1291,-17.3565"/>
<text text-anchor="middle" x="2113.7947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- sequencing_file -->
<g id="node24" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1989.7947" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1989.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge29" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1989.1731,-260.9735C1988.7668,-249.1918 1988.2278,-233.5607 1987.7657,-220.1581"/>
<polygon fill="#000000" stroke="#000000" points="1991.2581,-219.8768 1987.4155,-210.0034 1984.2623,-220.1181 1991.2581,-219.8768"/>
<text text-anchor="middle" x="2054.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- study_personnel -->
<g id="node25" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2297.7947" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2297.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge27" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2266.7501,-88.1429C2243.5186,-76.3925 2210.5797,-61.5239 2179.7947,-54 2093.9909,-33.0294 1830.951,-22.7514 1723.3794,-19.3385"/>
<polygon fill="#000000" stroke="#000000" points="1723.2667,-15.8334 1713.1626,-19.0202 1723.0487,-22.83 1723.2667,-15.8334"/>
<text text-anchor="middle" x="2292.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
</g>
</svg>
</div>
