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
<svg width="2279pt" height="305pt"
 viewBox="0.00 0.00 2279.14 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 2275.1426,-301 2275.1426,4 -4,4"/>
<!-- diagnosis -->
<g id="node1" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1290.1426" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1290.1426" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- participant -->
<g id="node22" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="966.1426" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="966.1426" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1263.605,-176.0398C1253.4127,-169.8493 1241.6965,-162.6593 1231.1426,-156 1220.8214,-149.4876 1219.5522,-145.331 1208.1426,-141 1177.4538,-129.3508 1095.6106,-118.6456 1035.5676,-111.9908"/>
<polygon fill="#000000" stroke="#000000" points="1035.7011,-108.4846 1025.38,-110.8771 1034.9404,-115.4432 1035.7011,-108.4846"/>
<text text-anchor="middle" x="1275.6426" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- family_relationship -->
<g id="node2" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1463.1426" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1463.1426" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1402.9986,-177.6069C1383.4661,-171.9784 1361.9827,-164.7474 1343.1426,-156 1332.0734,-150.8606 1331.6495,-145.0656 1320.1426,-141 1316.8166,-139.8249 1137.888,-121.9866 1035.7304,-111.871"/>
<polygon fill="#000000" stroke="#000000" points="1035.7831,-108.3592 1025.4869,-110.8571 1035.0935,-115.3252 1035.7831,-108.3592"/>
<text text-anchor="middle" x="1422.6426" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- sequencing_file -->
<g id="node3" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2183.1426" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="2183.1426" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sample -->
<g id="node14" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1822.1426" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1822.1426" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge30" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2163.604,-261.3627C2149.7134,-249.8788 2130.0562,-235.657 2110.1426,-228 2068.6211,-212.0346 1947.3728,-200.967 1876.1268,-195.6358"/>
<polygon fill="#000000" stroke="#000000" points="1876.223,-192.1335 1865.9933,-194.8909 1875.7098,-199.1147 1876.223,-192.1335"/>
<text text-anchor="middle" x="2204.6426" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- synonym -->
<g id="node4" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="273.1426" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="273.1426" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M324.5336,-276.1781C472.8462,-268.082 914.4113,-244.3143 1281.1426,-228 1489.5344,-218.7295 1543.6345,-239.4532 1750.1426,-210 1758.6689,-208.7839 1767.6514,-206.9757 1776.2706,-204.9675"/>
<polygon fill="#000000" stroke="#000000" points="1777.2928,-208.3206 1786.1728,-202.5416 1775.6271,-201.5217 1777.2928,-208.3206"/>
<text text-anchor="middle" x="1323.6426" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M268.6484,-260.7581C264.0966,-237.4421 260.4634,-197.3127 282.1426,-174 323.2415,-129.8042 726.3866,-112.3728 893.8176,-107.0023"/>
<polygon fill="#000000" stroke="#000000" points="894.134,-110.4942 904.0187,-106.6807 893.9133,-103.4976 894.134,-110.4942"/>
<text text-anchor="middle" x="324.6426" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study -->
<g id="node23" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1482.1426" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1482.1426" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge10" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M223.6553,-273.1841C154.911,-263.9711 36.0214,-243.5441 10.1426,-210 -9.0271,-185.1522 2.7116,-162.9486 25.1426,-141 68.6895,-98.3894 92.2654,-102.6679 151.1426,-87 274.3671,-54.2086 308.9865,-63.5341 436.1426,-54 821.4497,-25.1098 1288.3649,-19.3756 1435.4584,-18.262"/>
<polygon fill="#000000" stroke="#000000" points="1435.5165,-21.7618 1445.4909,-18.1896 1435.4659,-14.762 1435.5165,-21.7618"/>
<text text-anchor="middle" x="67.6426" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- molecular_test -->
<g id="node5" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1661.1426" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1661.1426" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1600.1501,-180.2377C1576.1827,-174.4973 1548.7998,-166.5175 1525.1426,-156 1513.9909,-151.0422 1513.7477,-144.776 1502.1426,-141 1427.8726,-116.8345 1229.0307,-128.7832 1151.1426,-123 1112.6264,-120.1402 1069.6879,-116.02 1034.8808,-112.4431"/>
<polygon fill="#000000" stroke="#000000" points="1035.1303,-108.9503 1024.8229,-111.4015 1034.4091,-115.9131 1035.1303,-108.9503"/>
<text text-anchor="middle" x="1589.1426" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- cell_line -->
<g id="node6" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="1938.1426" cy="-105" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="1938.1426" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1934.1232,-123.1029C1930.8899,-133.9043 1925.3279,-147.1883 1916.1426,-156 1903.924,-167.7216 1887.4892,-175.7274 1871.78,-181.1509"/>
<polygon fill="#000000" stroke="#000000" points="1870.6137,-177.8488 1862.1367,-184.2042 1872.7267,-184.5223 1870.6137,-177.8488"/>
<text text-anchor="middle" x="1966.6426" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge25" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1918.7044,-88.1822C1903.9524,-76.4514 1882.6091,-61.5899 1861.1426,-54 1801.0377,-32.7488 1616.3075,-23.0831 1528.9038,-19.6097"/>
<polygon fill="#000000" stroke="#000000" points="1528.8701,-16.1059 1518.7422,-19.2164 1528.5993,-23.1006 1528.8701,-16.1059"/>
<text text-anchor="middle" x="1930.6426" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- radiology_file -->
<g id="node7" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="449.1426" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="449.1426" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M467.9799,-174.5888C481.8534,-162.893 501.7763,-148.3272 522.1426,-141 588.4969,-117.1275 785.6316,-108.9981 893.5451,-106.2966"/>
<polygon fill="#000000" stroke="#000000" points="893.7897,-109.7919 903.7024,-106.0518 893.621,-102.7939 893.7897,-109.7919"/>
<text text-anchor="middle" x="581.1426" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- medical_history -->
<g id="node8" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="626.1426" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="626.1426" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M633.4177,-173.8735C638.9797,-162.4847 647.8042,-148.5639 660.1426,-141 698.0042,-117.7894 815.4846,-109.543 893.3718,-106.6136"/>
<polygon fill="#000000" stroke="#000000" points="893.743,-110.1027 903.6125,-106.2503 893.4947,-103.1071 893.743,-110.1027"/>
<text text-anchor="middle" x="728.1426" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node9" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1328.1426" cy="-279" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="1328.1426" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1345.9903,-261.1515C1358.9811,-249.4137 1377.648,-234.9778 1397.1426,-228 1471.0944,-201.5299 1672.4544,-221.5796 1750.1426,-210 1758.5695,-208.7439 1767.4468,-206.9358 1775.9797,-204.9446"/>
<polygon fill="#000000" stroke="#000000" points="1776.9084,-208.3207 1785.7906,-202.5452 1775.2454,-201.5211 1776.9084,-208.3207"/>
<text text-anchor="middle" x="1505.6426" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- follow_up -->
<g id="node10" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="784.1426" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="784.1426" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M790.1784,-173.8632C794.7815,-162.7674 802.2149,-149.1774 813.1426,-141 827.1615,-130.5093 865.5738,-121.4898 900.3999,-115.1027"/>
<polygon fill="#000000" stroke="#000000" points="901.3502,-118.4886 910.5815,-113.2893 900.1227,-111.5971 901.3502,-118.4886"/>
<text text-anchor="middle" x="858.1426" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- clinical_measure_file -->
<g id="node11" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="128.1426" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="128.1426" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M122.8695,-173.5805C120.9633,-162.66 120.9739,-149.362 129.1426,-141 142.4262,-127.4021 692.4943,-111.9983 893.5364,-106.812"/>
<polygon fill="#000000" stroke="#000000" points="893.795,-110.3066 903.7018,-106.5508 893.6151,-103.3089 893.795,-110.3066"/>
<text text-anchor="middle" x="215.1426" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge29" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M118.2183,-173.8614C113.7796,-163.0466 111.1366,-149.761 119.1426,-141 209.8615,-41.7257 1206.2041,-21.8417 1435.3474,-18.5711"/>
<polygon fill="#000000" stroke="#000000" points="1435.722,-22.0664 1445.6724,-18.4277 1435.6247,-15.0671 1435.722,-22.0664"/>
<text text-anchor="middle" x="371.1426" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- methylation_array_file -->
<g id="node12" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1599.1426" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1599.1426" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1607.2032,-261.013C1613.2434,-249.6832 1622.6209,-235.7756 1635.1426,-228 1679.0918,-200.7088 1699.4416,-220.2839 1750.1426,-210 1758.2222,-208.3612 1766.7609,-206.4171 1775.0243,-204.4227"/>
<polygon fill="#000000" stroke="#000000" points="1776.0472,-207.7754 1784.918,-201.9823 1774.3708,-200.9791 1776.0472,-207.7754"/>
<text text-anchor="middle" x="1726.6426" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study_personnel -->
<g id="node13" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="1247.1426" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1247.1426" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1252.5595,-86.9032C1256.8682,-75.6771 1264.048,-61.928 1275.1426,-54 1300.2532,-36.0563 1382.6126,-26.1049 1435.565,-21.42"/>
<polygon fill="#000000" stroke="#000000" points="1436.0713,-24.8896 1445.7377,-20.5525 1435.4764,-17.915 1436.0713,-24.8896"/>
<text text-anchor="middle" x="1344.6426" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge18" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1866.3441,-190.3407C1918.6083,-187.3413 2000.9459,-179.0017 2020.1426,-156 2024.4142,-150.8817 2023.788,-146.5817 2020.1426,-141 2015.6297,-134.0901 2000.7576,-126.7201 1984.8943,-120.46"/>
<polygon fill="#000000" stroke="#000000" points="1986.1022,-117.1749 1975.5106,-116.9142 1983.6279,-123.723 1986.1022,-117.1749"/>
<text text-anchor="middle" x="2058.6426" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node17" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1669.1426" cy="-105" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1669.1426" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge19" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1826.6592,-173.8478C1828.2026,-163.0278 1827.9137,-149.7417 1820.1426,-141 1803.1025,-121.832 1730.6084,-130.6941 1706.1426,-123 1704.2005,-122.3892 1702.2322,-121.6914 1700.2677,-120.9334"/>
<polygon fill="#000000" stroke="#000000" points="1701.183,-117.5164 1690.6147,-116.7671 1698.409,-123.9433 1701.183,-117.5164"/>
<text text-anchor="middle" x="1862.6426" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1784.4331,-182.4355C1773.3919,-179.6721 1761.2924,-176.68 1750.1426,-174 1715.55,-165.6852 1704.2164,-171.3964 1672.1426,-156 1662.4433,-151.3441 1663.2415,-144.7101 1653.1426,-141 1600.7524,-121.7534 1206.8331,-126.7042 1151.1426,-123 1112.459,-120.427 1069.339,-116.3046 1034.4664,-112.6539"/>
<polygon fill="#000000" stroke="#000000" points="1034.7053,-109.1597 1024.3926,-111.5885 1033.969,-116.1209 1034.7053,-109.1597"/>
<text text-anchor="middle" x="1708.6426" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- publication -->
<g id="node15" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="1415.1426" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="1415.1426" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge5" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1415.2478,-86.6462C1416.1162,-76.2783 1418.6162,-63.5283 1425.1426,-54 1430.2767,-46.5043 1437.5381,-40.2443 1445.1646,-35.1599"/>
<polygon fill="#000000" stroke="#000000" points="1447.4209,-37.8867 1454.1796,-29.7276 1443.808,-31.8911 1447.4209,-37.8867"/>
<text text-anchor="middle" x="1476.1426" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- study_arm -->
<g id="node16" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1556.1426" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1556.1426" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge24" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1547.9906,-86.9373C1542.8566,-76.6664 1535.6066,-63.9164 1527.1426,-54 1522.604,-48.6826 1517.1905,-43.586 1511.7178,-38.9857"/>
<polygon fill="#000000" stroke="#000000" points="1513.7527,-36.1318 1503.7523,-32.633 1509.3881,-41.6045 1513.7527,-36.1318"/>
<text text-anchor="middle" x="1585.6426" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1691.3515,-116.0554C1696.2022,-118.3996 1701.3258,-120.8223 1706.1426,-123 1725.0208,-131.5351 1730.9919,-131.0105 1749.1426,-141 1753.7111,-143.5144 1773.7413,-157.5447 1791.6663,-170.2538"/>
<polygon fill="#000000" stroke="#000000" points="1790.0405,-173.3921 1800.2197,-176.3304 1794.0946,-167.6856 1790.0405,-173.3921"/>
<text text-anchor="middle" x="1794.1426" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge7" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1662.6229,-87.3278C1657.5997,-76.1309 1649.5645,-62.2532 1638.1426,-54 1620.6298,-41.3458 1566.8544,-30.7843 1527.3191,-24.4406"/>
<polygon fill="#000000" stroke="#000000" points="1527.7725,-20.969 1517.3517,-22.8812 1526.6905,-27.8849 1527.7725,-20.969"/>
<text text-anchor="middle" x="1675.1426" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study_funding -->
<g id="node18" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="1792.1426" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="1792.1426" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge31" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1767.6096,-87.7196C1750.3568,-76.395 1726.3039,-62.2169 1703.1426,-54 1645.0214,-33.3805 1574.0658,-24.4918 1528.5027,-20.7132"/>
<polygon fill="#000000" stroke="#000000" points="1528.5775,-17.2085 1518.3356,-19.9201 1528.033,-24.1873 1528.5775,-17.2085"/>
<text text-anchor="middle" x="1795.1426" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- exposure -->
<g id="node19" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="911.1426" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="911.1426" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M907.5577,-173.956C906.4461,-163.6913 906.6961,-150.9413 912.1426,-141 915.1979,-135.4231 919.5306,-130.5555 924.429,-126.3555"/>
<polygon fill="#000000" stroke="#000000" points="926.5974,-129.1041 932.4897,-120.2989 922.3925,-123.5078 926.5974,-129.1041"/>
<text text-anchor="middle" x="955.6426" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- cytogenomic_file -->
<g id="node20" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1822.1426" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1822.1426" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1822.1426,-260.9735C1822.1426,-249.1918 1822.1426,-233.5607 1822.1426,-220.1581"/>
<polygon fill="#000000" stroke="#000000" points="1825.6427,-220.0033 1822.1426,-210.0034 1818.6427,-220.0034 1825.6427,-220.0033"/>
<text text-anchor="middle" x="1893.6426" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- pathology_file -->
<g id="node21" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2006.1426" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2006.1426" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1997.2318,-260.8619C1990.8762,-249.7656 1981.3089,-236.1755 1969.1426,-228 1953.4941,-217.4846 1909.1957,-207.4457 1873.2858,-200.6535"/>
<polygon fill="#000000" stroke="#000000" points="1873.8806,-197.2042 1863.4106,-198.8262 1872.6068,-204.0874 1873.8806,-197.2042"/>
<text text-anchor="middle" x="2045.1426" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge1" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1008.3512,-91.6848C1046.5748,-80.1044 1104.6219,-63.7009 1156.1426,-54 1254.7357,-35.4358 1372.0371,-25.3725 1435.5929,-20.9022"/>
<polygon fill="#000000" stroke="#000000" points="1435.959,-24.3854 1445.6951,-20.2071 1435.4784,-17.4019 1435.959,-24.3854"/>
<text text-anchor="middle" x="1206.6426" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- therapeutic_procedure -->
<g id="node24" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="1100.1426" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="1100.1426" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1057.5884,-175.2086C1045.7157,-169.7741 1033.0807,-163.2535 1022.1426,-156 1010.7279,-148.4305 999.3317,-138.5782 989.8283,-129.5536"/>
<polygon fill="#000000" stroke="#000000" points="992.2518,-127.0282 982.6485,-122.553 987.3649,-132.0401 992.2518,-127.0282"/>
<text text-anchor="middle" x="1115.1426" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- study_admin -->
<g id="node25" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="2076.1426" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2076.1426" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge15" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2049.8866,-88.097C2030.1591,-76.3238 2002.0238,-61.4467 1975.1426,-54 1891.9029,-30.9406 1634.7503,-21.8866 1528.6522,-19.0701"/>
<polygon fill="#000000" stroke="#000000" points="1528.6548,-15.5691 1518.5676,-18.8092 1528.4737,-22.5668 1528.6548,-15.5691"/>
<text text-anchor="middle" x="2068.6426" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
</g>
</svg>
</div>
