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
<svg width="3151pt" height="305pt"
 viewBox="0.00 0.00 3150.69 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 3146.6897,-301 3146.6897,4 -4,4"/>
<!-- cytogenomic_file -->
<g id="node1" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="338.6897" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="338.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- sample -->
<g id="node22" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="822.6897" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="822.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge28" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M367.2935,-261.8016C388.0281,-250.2061 417.1477,-235.6728 444.6897,-228 504.1714,-211.4293 679.0129,-199.833 768.5292,-194.8042"/>
<polygon fill="#000000" stroke="#000000" points="768.9574,-198.2859 778.7484,-194.2379 768.57,-191.2967 768.9574,-198.2859"/>
<text text-anchor="middle" x="516.1897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- exposure -->
<g id="node2" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="2742.6897" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="2742.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- participant -->
<g id="node18" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1946.6897" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1946.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2720.159,-175.658C2702.2825,-163.6775 2676.1486,-148.2832 2650.6897,-141 2591.2285,-123.9896 2186.7271,-111.3967 2019.1607,-106.851"/>
<polygon fill="#000000" stroke="#000000" points="2019.0432,-103.3467 2008.9526,-106.5761 2018.8547,-110.3441 2019.0432,-103.3467"/>
<text text-anchor="middle" x="2728.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- pdx -->
<g id="node3" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1167.6897" cy="-105" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1167.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- study -->
<g id="node12" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1283.6897" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1283.6897" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge16" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1168.9482,-86.9266C1170.5949,-76.1362 1174.3215,-62.8536 1182.6897,-54 1197.172,-38.6778 1218.6087,-29.8669 1238.0117,-24.8048"/>
<polygon fill="#000000" stroke="#000000" points="1238.9859,-28.1715 1247.9252,-22.4848 1237.3907,-21.3556 1238.9859,-28.1715"/>
<text text-anchor="middle" x="1206.6897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1146.2035,-116.7225C1141.2202,-119.081 1135.8591,-121.3413 1130.6897,-123 1085.1892,-137.5998 1071.4477,-131.1435 1024.6897,-141 970.9044,-152.3379 909.7919,-168.187 869.0054,-179.1959"/>
<polygon fill="#000000" stroke="#000000" points="868.082,-175.8199 859.3466,-181.8151 869.9141,-182.5759 868.082,-175.8199"/>
<text text-anchor="middle" x="1048.6897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- family_relationship -->
<g id="node4" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1409.6897" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1409.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1418.7617,-173.8793C1425.5816,-162.3384 1436.0804,-148.2416 1449.6897,-141 1449.9808,-140.8451 1738.5419,-120.0135 1875.7787,-110.1137"/>
<polygon fill="#000000" stroke="#000000" points="1876.0684,-113.602 1885.7906,-109.3915 1875.5647,-106.6201 1876.0684,-113.602"/>
<text text-anchor="middle" x="1529.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node5" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="583.6897" cy="-279" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="583.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M585.4815,-260.7912C587.5589,-249.6666 592.0382,-236.0716 601.6897,-228 626.3236,-207.3986 711.2105,-198.3941 768.3181,-194.5985"/>
<polygon fill="#000000" stroke="#000000" points="768.877,-198.0703 778.6373,-193.9488 768.4371,-191.0842 768.877,-198.0703"/>
<text text-anchor="middle" x="710.1897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- study_personnel -->
<g id="node6" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="876.6897" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="876.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge3" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M882.1661,-86.8484C886.6024,-75.4491 894.0602,-61.5259 905.6897,-54 932.9621,-36.3511 1142.3323,-24.5378 1237.2145,-20.0368"/>
<polygon fill="#000000" stroke="#000000" points="1237.5611,-23.5245 1247.3868,-19.5615 1237.2343,-16.5321 1237.5611,-23.5245"/>
<text text-anchor="middle" x="975.1897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- study_admin -->
<g id="node7" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1051.6897" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1051.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge25" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1048.4044,-86.7111C1047.559,-75.8397 1048.6367,-62.5475 1056.6897,-54 1068.9368,-41.001 1175.0769,-28.5765 1237.7923,-22.2806"/>
<polygon fill="#000000" stroke="#000000" points="1238.232,-25.7543 1247.839,-21.287 1237.5431,-18.7882 1238.232,-25.7543"/>
<text text-anchor="middle" x="1113.1897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- sequencing_file -->
<g id="node8" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="822.6897" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="822.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M822.6897,-260.9735C822.6897,-249.1918 822.6897,-233.5607 822.6897,-220.1581"/>
<polygon fill="#000000" stroke="#000000" points="826.1898,-220.0033 822.6897,-210.0034 819.1898,-220.0034 826.1898,-220.0033"/>
<text text-anchor="middle" x="889.1897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- molecular_test -->
<g id="node9" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1607.6897" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1607.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1608.176,-173.9545C1609.4926,-162.7496 1613.1418,-149.0046 1622.6897,-141 1641.6129,-125.1355 1785.3176,-114.1703 1874.8734,-108.7976"/>
<polygon fill="#000000" stroke="#000000" points="1875.1998,-112.2845 1884.9762,-108.2014 1874.7874,-105.2967 1875.1998,-112.2845"/>
<text text-anchor="middle" x="1686.6897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- diagnosis -->
<g id="node10" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1760.6897" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1760.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1755.8714,-173.9927C1754.1362,-163.2273 1754.167,-149.9476 1761.6897,-141 1776.3229,-123.5953 1829.5983,-114.4778 1875.2431,-109.7793"/>
<polygon fill="#000000" stroke="#000000" points="1875.834,-113.2384 1885.4485,-108.7874 1875.1568,-106.2713 1875.834,-113.2384"/>
<text text-anchor="middle" x="1806.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- radiology_file -->
<g id="node11" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="2027.6897" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="2027.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2011.2982,-174.3943C1999.4408,-161.6586 1983.2487,-144.2671 1970.041,-130.081"/>
<polygon fill="#000000" stroke="#000000" points="1972.4328,-127.5136 1963.0569,-122.5796 1967.3095,-132.2835 1972.4328,-127.5136"/>
<text text-anchor="middle" x="2050.6897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- pathology_file -->
<g id="node13" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="999.6897" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="999.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M988.6229,-260.9652C980.953,-249.9102 969.7854,-236.3272 956.6897,-228 932.374,-212.5383 901.5245,-203.6659 875.5565,-198.6007"/>
<polygon fill="#000000" stroke="#000000" points="875.9639,-195.1176 865.5001,-196.7784 874.7157,-202.0054 875.9639,-195.1176"/>
<text text-anchor="middle" x="1033.6897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- medical_history -->
<g id="node14" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2204.6897" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2204.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2178.6359,-174.6308C2160.9703,-163.5619 2136.7275,-149.7129 2113.6897,-141 2081.5233,-128.8347 2044.2355,-120.3042 2013.0645,-114.6115"/>
<polygon fill="#000000" stroke="#000000" points="2013.63,-111.1573 2003.1732,-112.862 2012.4107,-118.0503 2013.63,-111.1573"/>
<text text-anchor="middle" x="2212.6897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- methylation_array_file -->
<g id="node15" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="115.6897" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="115.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M143.3382,-261.4932C163.4173,-249.7524 191.6906,-235.1721 218.6897,-228 321.4929,-200.6913 639.6303,-194.0603 768.0757,-192.4815"/>
<polygon fill="#000000" stroke="#000000" points="768.1274,-195.9812 778.0857,-192.364 768.0452,-188.9817 768.1274,-195.9812"/>
<text text-anchor="middle" x="310.1897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- synonym -->
<g id="node16" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1223.6897" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1223.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge23" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1220.8611,-260.9262C1217.2495,-234.3589 1212.3977,-183.3307 1220.6897,-141 1227.8057,-104.6729 1249.2282,-67.4557 1265.1275,-43.6167"/>
<polygon fill="#000000" stroke="#000000" points="1268.1518,-45.3946 1270.9093,-35.1649 1262.3744,-41.4423 1268.1518,-45.3946"/>
<text text-anchor="middle" x="1263.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1275.5975,-277.3987C1403.0633,-272.7792 1728.1032,-256.6391 1824.6897,-210 1845.066,-200.1608 1843.8401,-189.1026 1860.6897,-174 1878.4118,-158.1153 1899.2044,-141.3851 1915.9051,-128.3773"/>
<polygon fill="#000000" stroke="#000000" points="1918.4599,-130.8259 1924.2275,-121.9385 1914.1765,-125.2894 1918.4599,-130.8259"/>
<text text-anchor="middle" x="1903.1897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1184.979,-266.6782C1166.4311,-260.3333 1144.0854,-252.0371 1124.6897,-243 1112.5972,-237.3657 1111.3257,-232.2787 1098.6897,-228 1058.692,-214.4564 944.6616,-202.6258 876.3301,-196.4821"/>
<polygon fill="#000000" stroke="#000000" points="876.4546,-192.9794 866.1842,-195.5814 875.8356,-199.952 876.4546,-192.9794"/>
<text text-anchor="middle" x="1167.1897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- follow_up -->
<g id="node17" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="2362.6897" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="2362.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2342.6189,-175.0109C2327.6567,-163.3566 2306.177,-148.6635 2284.6897,-141 2237.2199,-124.0696 2102.6264,-113.7054 2018.3017,-108.6821"/>
<polygon fill="#000000" stroke="#000000" points="2018.4639,-105.1857 2008.2766,-108.096 2018.0552,-112.1738 2018.4639,-105.1857"/>
<text text-anchor="middle" x="2358.6897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge12" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1897.5906,-93.7754C1845.5074,-82.2439 1760.6923,-64.5338 1686.6897,-54 1558.1692,-35.7059 1405.1858,-25.0637 1330.0373,-20.5595"/>
<polygon fill="#000000" stroke="#000000" points="1330.1497,-17.0601 1319.9607,-19.9645 1329.737,-24.0479 1330.1497,-17.0601"/>
<text text-anchor="middle" x="1823.1897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_funding -->
<g id="node19" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="1328.6897" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="1328.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge18" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1319.3657,-86.9735C1313.0488,-74.7609 1304.5927,-58.4123 1297.4985,-44.697"/>
<polygon fill="#000000" stroke="#000000" points="1300.5509,-42.9799 1292.8479,-35.7057 1294.3334,-46.1959 1300.5509,-42.9799"/>
<text text-anchor="middle" x="1370.6897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- study_arm -->
<g id="node20" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1483.6897" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1483.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1471.7108,-87.3317C1463.2106,-76.1364 1450.8297,-62.259 1436.6897,-54 1403.9465,-34.8749 1361.669,-25.9052 1329.8558,-21.7012"/>
<polygon fill="#000000" stroke="#000000" points="1330.2683,-18.2256 1319.9198,-20.4968 1329.426,-25.1748 1330.2683,-18.2256"/>
<text text-anchor="middle" x="1502.1897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- publication -->
<g id="node21" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="1624.6897" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="1624.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge2" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1606.3487,-87.6473C1593.0621,-76.1369 1574.0924,-61.769 1554.6897,-54 1514.9573,-38.0909 1396.7056,-26.7302 1330.2879,-21.4052"/>
<polygon fill="#000000" stroke="#000000" points="1330.3372,-17.8984 1320.0933,-20.6026 1329.7877,-24.8768 1330.3372,-17.8984"/>
<text text-anchor="middle" x="1631.6897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge30" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M867.1058,-190.2705C917.9342,-187.2331 1003.1276,-178.8864 1072.6897,-156 1096.4201,-148.1926 1121.2258,-134.6657 1139.5369,-123.5042"/>
<polygon fill="#000000" stroke="#000000" points="1141.5903,-126.3486 1148.2252,-118.0885 1137.8874,-120.4081 1141.5903,-126.3486"/>
<text text-anchor="middle" x="1144.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M866.9634,-190.1332C970.4235,-185.5434 1225.6278,-172.845 1309.6897,-156 1330.3606,-151.8578 1333.9761,-144.9228 1354.6897,-141 1504.2418,-112.6773 1544.774,-132.4659 1696.6897,-123 1757.3325,-119.2214 1826.1961,-114.2098 1876.2719,-110.4344"/>
<polygon fill="#000000" stroke="#000000" points="1876.6377,-113.9168 1886.3452,-109.6725 1876.1097,-106.9367 1876.6377,-113.9168"/>
<text text-anchor="middle" x="1391.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node23" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="722.6897" cy="-105" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="722.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge29" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M784.2752,-183.033C759.3277,-176.3433 730.1168,-166.5674 722.6897,-156 718.0877,-149.4521 716.7355,-141.17 716.912,-133.1946"/>
<polygon fill="#000000" stroke="#000000" points="720.4133,-133.3459 717.8797,-123.0585 713.445,-132.6806 720.4133,-133.3459"/>
<text text-anchor="middle" x="759.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge9" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M743.1442,-88.5634C759.154,-76.6999 782.5194,-61.5008 805.6897,-54 885.0115,-28.3217 1132.9891,-20.786 1237.0193,-18.7234"/>
<polygon fill="#000000" stroke="#000000" points="1237.2838,-22.2191 1247.2155,-18.5298 1237.1508,-15.2204 1237.2838,-22.2191"/>
<text text-anchor="middle" x="846.1897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M760.8875,-116.6108C774.4661,-122.2378 789.0157,-130.179 799.6897,-141 806.0631,-147.4611 810.848,-155.9998 814.355,-164.2388"/>
<polygon fill="#000000" stroke="#000000" points="811.0949,-165.513 817.9035,-173.6305 817.6431,-163.0389 811.0949,-165.513"/>
<text text-anchor="middle" x="851.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- clinical_measure_file -->
<g id="node24" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="2951.6897" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="2951.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge21" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2982.2118,-174.5861C2995.8791,-164.6448 3006.8745,-152.0073 2996.6897,-141 2827.2984,42.0723 2126.5123,-71.2115 1877.6897,-54 1673.8711,-39.9015 1430.4956,-26.1028 1330.2958,-20.5535"/>
<polygon fill="#000000" stroke="#000000" points="1330.3818,-17.053 1320.2039,-19.9956 1329.9954,-24.0423 1330.3818,-17.053"/>
<text text-anchor="middle" x="3056.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2895.9794,-176.4791C2873.7697,-170.2208 2847.9909,-162.8682 2824.6897,-156 2802.8437,-149.5607 2798.1359,-144.8584 2775.6897,-141 2631.3526,-116.1892 2193.3476,-108.0804 2019.2083,-105.794"/>
<polygon fill="#000000" stroke="#000000" points="2019.1643,-102.2932 2009.1201,-105.6642 2019.0742,-109.2926 2019.1643,-102.2932"/>
<text text-anchor="middle" x="2910.6897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- therapeutic_procedure -->
<g id="node25" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="2553.6897" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="2553.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2513.8936,-174.958C2484.9793,-163.3577 2444.6075,-148.753 2407.6897,-141 2335.4081,-125.8204 2128.8666,-113.8633 2018.4128,-108.3386"/>
<polygon fill="#000000" stroke="#000000" points="2018.5172,-104.8395 2008.3561,-107.84 2018.1706,-111.831 2018.5172,-104.8395"/>
<text text-anchor="middle" x="2553.6897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
</g>
</svg>
</div>
