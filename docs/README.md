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
<svg width="2879pt" height="305pt"
 viewBox="0.00 0.00 2878.79 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 2874.7878,-301 2874.7878,4 -4,4"/>
<!-- cell_line -->
<g id="node1" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="388.7878" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="388.7878" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample -->
<g id="node14" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="829.7878" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="829.7878" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M387.6809,-260.9994C388.0456,-249.8129 390.6023,-236.0716 399.7878,-228 427.4203,-203.7182 665.7753,-195.5046 775.2362,-192.9966"/>
<polygon fill="#000000" stroke="#000000" points="775.4953,-196.4918 785.4154,-192.7714 775.3404,-189.4936 775.4953,-196.4918"/>
<text text-anchor="middle" x="440.2878" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- study -->
<g id="node24" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1979.7878" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1979.7878" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge17" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M383.1461,-260.6889C381.0653,-250.0794 380.6967,-237.0696 387.7878,-228 486.5167,-101.7255 580.7794,-173.2647 737.7878,-141 883.7928,-110.9964 921.2793,-108.423 1068.7878,-87 1183.6247,-70.322 1212.2256,-64.5388 1327.7878,-54 1554.2292,-33.3494 1826.0706,-22.9592 1933.1727,-19.4279"/>
<polygon fill="#000000" stroke="#000000" points="1933.4355,-22.9213 1943.3164,-19.0979 1933.2078,-15.925 1933.4355,-22.9213"/>
<text text-anchor="middle" x="778.2878" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- study_arm -->
<g id="node2" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1137.7878" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1137.7878" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge12" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1181.7662,-92.6277C1190.0366,-90.5575 1198.6439,-88.5743 1206.7878,-87 1478.6489,-34.4461 1812.1811,-21.8032 1933.1684,-18.8605"/>
<polygon fill="#000000" stroke="#000000" points="1933.2829,-22.3588 1943.1987,-18.6271 1933.12,-15.3607 1933.2829,-22.3588"/>
<text text-anchor="middle" x="1465.2878" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- pdx -->
<g id="node3" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1243.7878" cy="-105" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1243.7878" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1222.829,-117.0045C1217.7298,-119.4106 1212.1862,-121.6205 1206.7878,-123 1166.0492,-133.4101 857.8042,-110.569 828.7878,-141 822.9658,-147.1058 821.6154,-155.7299 822.2148,-164.1524"/>
<polygon fill="#000000" stroke="#000000" points="818.7711,-164.7876 823.7433,-174.1432 825.6906,-163.7289 818.7711,-164.7876"/>
<text text-anchor="middle" x="852.7878" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge21" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1271.2966,-101.7483C1381.934,-88.6702 1795.1215,-39.8288 1933.9556,-23.4177"/>
<polygon fill="#000000" stroke="#000000" points="1934.7176,-26.852 1944.2375,-22.2023 1933.8958,-19.9004 1934.7176,-26.852"/>
<text text-anchor="middle" x="1679.7878" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- family_relationship -->
<g id="node4" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1516.7878" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1516.7878" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- participant -->
<g id="node15" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1873.7878" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1873.7878" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1529.6197,-174.0807C1539.0296,-162.471 1552.8989,-148.2146 1568.7878,-141 1616.2752,-119.4375 1751.3215,-131.4393 1802.7878,-123 1808.121,-122.1255 1813.6403,-121.0452 1819.1368,-119.8516"/>
<polygon fill="#000000" stroke="#000000" points="1819.9952,-123.2457 1828.961,-117.6008 1818.4319,-116.4225 1819.9952,-123.2457"/>
<text text-anchor="middle" x="1648.2878" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- radiology_file -->
<g id="node5" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1708.7878" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1708.7878" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1718.5079,-174.022C1725.3378,-162.9895 1735.4447,-149.4104 1747.7878,-141 1753.9163,-136.8241 1786.4886,-127.563 1816.9775,-119.4801"/>
<polygon fill="#000000" stroke="#000000" points="1817.9865,-122.8338 1826.7672,-116.9051 1816.2058,-116.0641 1817.9865,-122.8338"/>
<text text-anchor="middle" x="1806.7878" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- methylation_array_file -->
<g id="node6" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="768.7878" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="768.7878" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge24" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M765.0267,-260.8567C763.8564,-250.5589 764.1064,-237.8089 769.7878,-228 774.1639,-220.4446 780.8124,-214.294 788.1123,-209.3548"/>
<polygon fill="#000000" stroke="#000000" points="790.1029,-212.2424 796.8838,-204.1017 786.5063,-206.237 790.1029,-212.2424"/>
<text text-anchor="middle" x="861.2878" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study_personnel -->
<g id="node7" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="1706.7878" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1706.7878" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge11" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1721.8875,-87.0389C1732.4378,-75.7199 1747.5072,-61.8148 1763.7878,-54 1793.0882,-39.9357 1879.6029,-28.5994 1933.8356,-22.6209"/>
<polygon fill="#000000" stroke="#000000" points="1934.3297,-26.0879 1943.8951,-21.5324 1933.5766,-19.1285 1934.3297,-26.0879"/>
<text text-anchor="middle" x="1833.2878" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- therapeutic_procedure -->
<g id="node8" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="1917.7878" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="1917.7878" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1889.5319,-174.3104C1883.6134,-169.1746 1878.1525,-163.0247 1874.7878,-156 1871.4739,-149.0813 1870.2882,-141.0054 1870.1698,-133.3476"/>
<polygon fill="#000000" stroke="#000000" points="1873.6687,-133.4439 1870.5705,-123.3122 1866.6743,-133.1646 1873.6687,-133.4439"/>
<text text-anchor="middle" x="1967.7878" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- cytogenomic_file -->
<g id="node9" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="545.7878" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="545.7878" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge28" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M565.7424,-261.3973C579.6641,-250.0814 599.193,-236.0407 618.7878,-228 646.6673,-216.5596 723.9119,-205.1656 776.7814,-198.3511"/>
<polygon fill="#000000" stroke="#000000" points="777.5299,-201.7842 787.0085,-197.0506 776.6468,-194.8401 777.5299,-201.7842"/>
<text text-anchor="middle" x="690.2878" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- synonym -->
<g id="node10" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1375.7878" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1375.7878" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1336.9332,-266.9799C1318.3525,-260.7037 1296.0208,-252.3782 1276.7878,-243 1265.4816,-237.487 1264.7337,-231.9391 1252.7878,-228 1155.8313,-196.0288 1125.5067,-218.7162 1023.7878,-210 976.1446,-205.9175 921.9613,-200.8549 882.9894,-197.1396"/>
<polygon fill="#000000" stroke="#000000" points="883.2091,-193.6447 872.9215,-196.1775 882.5432,-200.613 883.2091,-193.6447"/>
<text text-anchor="middle" x="1319.2878" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1374.561,-260.7147C1372.9956,-250.1144 1369.506,-237.1051 1361.7878,-228 1349.4435,-213.4376 1333.0766,-226.0805 1322.7878,-210 1314.1645,-196.5226 1312.3469,-186.1238 1322.7878,-174 1392.7856,-92.7194 1696.8688,-139.9525 1802.7878,-123 1808.1243,-122.1459 1813.6458,-121.0793 1819.1437,-119.8942"/>
<polygon fill="#000000" stroke="#000000" points="1819.998,-123.2893 1828.9696,-117.6536 1818.4417,-116.4645 1819.998,-123.2893"/>
<text text-anchor="middle" x="1365.2878" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge3" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1428.0165,-278.4071C1675.785,-275.3447 2722.6744,-259.5031 2769.7878,-210 2834.2177,-142.3021 2719.115,-77.9836 2628.7878,-54 2571.1209,-38.6884 2165.7946,-24.1058 2026.5927,-19.4978"/>
<polygon fill="#000000" stroke="#000000" points="2026.3756,-15.9888 2016.2659,-19.1581 2026.1454,-22.985 2026.3756,-15.9888"/>
<text text-anchor="middle" x="2828.2878" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- sequencing_file -->
<g id="node11" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="985.7878" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="985.7878" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M978.1665,-261.0464C972.6281,-250.0237 964.1176,-236.4463 952.7878,-228 932.4317,-212.8246 905.7834,-204.0252 882.4973,-198.9327"/>
<polygon fill="#000000" stroke="#000000" points="882.9051,-195.4448 872.4116,-196.9068 881.5265,-202.3077 882.9051,-195.4448"/>
<text text-anchor="middle" x="1033.2878" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- exposure -->
<g id="node12" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="2106.7878" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="2106.7878" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2095.2518,-174.1389C2087.0119,-162.8621 2074.9122,-148.9665 2060.7878,-141 2040.5749,-129.5995 1986.2975,-119.8769 1941.3938,-113.4201"/>
<polygon fill="#000000" stroke="#000000" points="1941.7753,-109.9394 1931.3852,-112.0119 1940.8,-116.8711 1941.7753,-109.9394"/>
<text text-anchor="middle" x="2123.2878" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- medical_history -->
<g id="node13" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2262.7878" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2262.7878" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2229.4413,-175.4294C2218.0068,-169.5299 2205.2166,-162.687 2193.7878,-156 2183.2543,-149.8368 2182.2639,-145.1518 2170.7878,-141 2105.9877,-117.5568 2085.1961,-131.3031 2016.7878,-123 1992.0099,-119.9926 1964.8302,-116.5959 1940.8824,-113.57"/>
<polygon fill="#000000" stroke="#000000" points="1941.1937,-110.0816 1930.8334,-112.2981 1940.3147,-117.0262 1941.1937,-110.0816"/>
<text text-anchor="middle" x="2261.7878" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge7" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M786.0097,-195.1078C711.7996,-200.6921 564.519,-213.2289 514.7878,-228 500.4977,-232.2444 498.4522,-237.0414 484.7878,-243 468.5736,-250.0705 450.4817,-257.0764 434.4131,-263.0025"/>
<polygon fill="#000000" stroke="#000000" points="432.8997,-259.8288 424.7044,-266.5436 435.2984,-266.4051 432.8997,-259.8288"/>
<text text-anchor="middle" x="551.2878" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge8" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M851.7281,-176.0169C871.8363,-161.4379 898.9152,-142.0085 901.7878,-141 1029.9131,-96.0198 1075.417,-157.3662 1206.7878,-123 1208.9777,-122.4271 1211.1923,-121.7203 1213.392,-120.9214"/>
<polygon fill="#000000" stroke="#000000" points="1214.9548,-124.0613 1222.8175,-116.96 1212.2425,-117.6081 1214.9548,-124.0613"/>
<text text-anchor="middle" x="938.2878" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M868.4015,-183.0097C897.7003,-176.044 938.9175,-165.9355 974.7878,-156 996.7367,-149.9205 1001.3036,-144.6304 1023.7878,-141 1194.7311,-113.3986 1631.2222,-146.4247 1802.7878,-123 1808.3,-122.2474 1814.0019,-121.2263 1819.6675,-120.0505"/>
<polygon fill="#000000" stroke="#000000" points="1820.7816,-123.3879 1829.7777,-117.7915 1819.2551,-116.5564 1820.7816,-123.3879"/>
<text text-anchor="middle" x="1060.2878" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge1" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1889.1173,-87.4939C1898.5891,-77.1698 1911.2875,-64.1773 1923.7878,-54 1931.0162,-48.1149 1939.248,-42.3649 1947.1336,-37.249"/>
<polygon fill="#000000" stroke="#000000" points="1949.2286,-40.0657 1955.8177,-31.769 1945.4929,-34.1458 1949.2286,-40.0657"/>
<text text-anchor="middle" x="1974.2878" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_admin -->
<g id="node16" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="2298.7878" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2298.7878" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge13" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2250.6849,-91.881C2188.326,-74.8741 2080.5929,-45.4923 2021.5213,-29.3819"/>
<polygon fill="#000000" stroke="#000000" points="2022.3446,-25.9786 2011.776,-26.7241 2020.5027,-32.732 2022.3446,-25.9786"/>
<text text-anchor="middle" x="2214.2878" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- molecular_test -->
<g id="node17" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="2445.7878" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="2445.7878" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2401.4375,-176.985C2385.7564,-171.1173 2368.1953,-163.8967 2352.7878,-156 2341.9271,-150.4336 2341.3812,-144.812 2329.7878,-141 2263.6033,-119.2379 2086.1679,-129.3542 2016.7878,-123 1991.714,-120.7036 1964.2579,-117.4315 1940.1662,-114.3054"/>
<polygon fill="#000000" stroke="#000000" points="1940.4347,-110.8107 1930.0639,-112.9779 1939.5226,-117.7511 1940.4347,-110.8107"/>
<text text-anchor="middle" x="2416.7878" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- pathology_file -->
<g id="node18" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1162.7878" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1162.7878" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1147.6036,-261.357C1136.6481,-249.8706 1120.8352,-235.6481 1103.7878,-228 1084.1117,-219.1726 956.9227,-204.9875 882.9425,-197.3244"/>
<polygon fill="#000000" stroke="#000000" points="883.1793,-193.8304 872.8734,-196.2876 882.4623,-200.7935 883.1793,-193.8304"/>
<text text-anchor="middle" x="1187.7878" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- study_funding -->
<g id="node19" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2464.7878" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2464.7878" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge25" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2418.3663,-90.5737C2380.1583,-79.1773 2324.4081,-63.6375 2274.7878,-54 2187.5893,-37.0639 2084.2545,-26.6254 2025.9246,-21.6049"/>
<polygon fill="#000000" stroke="#000000" points="2026.1772,-18.1139 2015.9179,-20.7589 2025.5875,-25.089 2026.1772,-18.1139"/>
<text text-anchor="middle" x="2399.7878" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- diagnosis -->
<g id="node20" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1087.7878" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1087.7878" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1091.9538,-173.8937C1095.6352,-162.3591 1102.2717,-148.2638 1113.7878,-141 1146.1743,-120.572 1764.8568,-128.2372 1802.7878,-123 1808.2989,-122.2391 1814,-121.2125 1819.6651,-120.0333"/>
<polygon fill="#000000" stroke="#000000" points="1820.7808,-123.3703 1829.7748,-117.7704 1819.2518,-116.5393 1820.7808,-123.3703"/>
<text text-anchor="middle" x="1158.2878" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- publication -->
<g id="node21" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="2622.7878" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="2622.7878" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge27" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2586.0228,-90.2724C2554.6214,-78.3731 2507.9697,-62.2881 2465.7878,-54 2382.5156,-37.6383 2131.3092,-24.8128 2026.5025,-20.0288"/>
<polygon fill="#000000" stroke="#000000" points="2026.3829,-16.5199 2016.235,-19.5645 2026.0667,-23.5127 2026.3829,-16.5199"/>
<text text-anchor="middle" x="2573.7878" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- clinical_measure_file -->
<g id="node22" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="2651.7878" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="2651.7878" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2576.7842,-178.9401C2552.8931,-173.423 2526.7233,-165.921 2503.7878,-156 2492.5867,-151.1549 2492.4163,-144.7036 2480.7878,-141 2382.4656,-109.6848 2119.6298,-131.4514 2016.7878,-123 1991.5846,-120.9288 1963.9944,-117.6877 1939.8297,-114.5231"/>
<polygon fill="#000000" stroke="#000000" points="1940.0744,-111.0249 1929.7001,-113.1752 1939.151,-117.9638 1940.0744,-111.0249"/>
<text text-anchor="middle" x="2589.7878" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge19" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2669.5615,-174.2152C2678.1275,-163.5334 2684.7896,-150.2636 2675.7878,-141 2651.4636,-115.9686 2075.8074,-143.8118 2047.7878,-123 2021.8374,-103.7252 2043.2769,-80.5158 2024.7878,-54 2020.8661,-48.3758 2015.8192,-43.1829 2010.5306,-38.5935"/>
<polygon fill="#000000" stroke="#000000" points="2012.7026,-35.8488 2002.7122,-32.3212 2008.3222,-41.3089 2012.7026,-35.8488"/>
<text text-anchor="middle" x="2133.7878" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- follow_up -->
<g id="node23" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="1215.7878" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="1215.7878" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1209.2256,-174.0988C1206.4565,-163.097 1205.521,-149.5232 1213.7878,-141 1236.5804,-117.5002 1770.3679,-127.5495 1802.7878,-123 1808.2185,-122.2379 1813.8343,-121.2218 1819.4188,-120.0588"/>
<polygon fill="#000000" stroke="#000000" points="1820.3946,-123.4272 1829.3903,-117.8301 1818.8676,-116.5957 1820.3946,-123.4272"/>
<text text-anchor="middle" x="1258.7878" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node25" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="137.7878" cy="-279" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="137.7878" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M144.4484,-260.8836C149.7172,-249.3446 158.2893,-235.2482 170.7878,-228 196.767,-212.9338 622.2965,-198.3966 775.4275,-193.6294"/>
<polygon fill="#000000" stroke="#000000" points="775.6565,-197.1241 785.5434,-193.3164 775.4399,-190.1274 775.6565,-197.1241"/>
<text text-anchor="middle" x="279.2878" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
</g>
</svg>
</div>
