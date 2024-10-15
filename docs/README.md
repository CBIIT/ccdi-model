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
<svg width="2569pt" height="305pt"
 viewBox="0.00 0.00 2568.79 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 2564.7947,-301 2564.7947,4 -4,4"/>
<!-- study -->
<g id="node1" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1432.7947" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1432.7947" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- sample -->
<g id="node2" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2218.7947" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2218.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- participant -->
<g id="node4" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1308.7947" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1308.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2184.8758,-180.4486C2178.5366,-178.2988 2171.9655,-176.0763 2165.7947,-174 2141.8174,-165.9322 2134.0561,-168.0179 2111.7947,-156 2102.3273,-150.889 2102.9125,-144.6583 2092.7947,-141 2019.3137,-114.4315 1467.3494,-132.5194 1389.7947,-123 1381.8659,-122.0268 1373.5714,-120.6306 1365.4417,-119.0404"/>
<polygon fill="#000000" stroke="#000000" points="1366.1435,-115.6115 1355.6427,-117.0198 1364.7297,-122.4673 1366.1435,-115.6115"/>
<text text-anchor="middle" x="2148.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node8" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1426.7947" cy="-105" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1426.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge19" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2213.336,-174.0652C2208.775,-162.4485 2201.0118,-148.1902 2188.7947,-141 2154.0718,-120.5643 1502.9415,-132.5301 1463.7947,-123 1461.5954,-122.4646 1459.3736,-121.7859 1457.1687,-121.0077"/>
<polygon fill="#000000" stroke="#000000" points="1458.3092,-117.6917 1447.7312,-117.0937 1455.6275,-124.1577 1458.3092,-117.6917"/>
<text text-anchor="middle" x="2239.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node14" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="1521.7947" cy="-105" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="1521.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge17" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2262.8153,-189.5254C2314.7061,-185.1154 2390.1612,-173.1006 2358.7947,-141 2343.6871,-125.5388 1602.1368,-126.4359 1580.7947,-123 1576.3326,-122.2816 1571.7382,-121.3109 1567.1764,-120.1906"/>
<polygon fill="#000000" stroke="#000000" points="1567.8717,-116.7533 1557.306,-117.5389 1566.0555,-123.5136 1567.8717,-116.7533"/>
<text text-anchor="middle" x="2402.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_arm -->
<g id="node3" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="59.7947" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="59.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge4" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M54.5614,-87.0278C52.5494,-75.9976 52.4314,-62.4189 60.7947,-54 84.6582,-29.9778 1148.4133,-20.2288 1386.048,-18.3487"/>
<polygon fill="#000000" stroke="#000000" points="1386.12,-21.8484 1396.0923,-18.2701 1386.0651,-14.8486 1386.12,-21.8484"/>
<text text-anchor="middle" x="109.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge20" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1309.9807,-86.8572C1311.6001,-76.0408 1315.3234,-62.7551 1323.7947,-54 1333.2258,-44.253 1363.4412,-34.6938 1389.6735,-27.8782"/>
<polygon fill="#000000" stroke="#000000" points="1390.6397,-31.2442 1399.4806,-25.4057 1388.9284,-24.4566 1390.6397,-31.2442"/>
<text text-anchor="middle" x="1374.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- treatment -->
<g id="node5" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="2098.7947" cy="-192" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="2098.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2057.031,-179.3817C2038.7501,-173.2481 2017.2967,-165.2067 1998.7947,-156 1987.8686,-150.5631 1987.438,-144.6567 1975.7947,-141 1913.6458,-121.4816 1454.4308,-131.1014 1389.7947,-123 1381.8684,-122.0065 1373.5753,-120.5989 1365.4463,-119.0031"/>
<polygon fill="#000000" stroke="#000000" points="1366.1492,-115.5744 1355.6478,-116.9784 1364.7327,-122.4296 1366.1492,-115.5744"/>
<text text-anchor="middle" x="2045.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- exposure -->
<g id="node6" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="757.7947" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="757.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M749.2703,-173.7379C745.5929,-162.8765 743.7462,-149.5855 751.7947,-141 768.1165,-123.5892 1089.2306,-111.6546 1236.3239,-107.0796"/>
<polygon fill="#000000" stroke="#000000" points="1236.7198,-110.5691 1246.6073,-106.7629 1236.5043,-103.5724 1236.7198,-110.5691"/>
<text text-anchor="middle" x="795.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- clinical_measure_file -->
<g id="node7" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="435.7947" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="435.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge26" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M425.9688,-173.9499C421.567,-163.1683 418.9284,-149.8867 426.7947,-141 491.3573,-68.0628 1196.9321,-29.2757 1386.2683,-20.1321"/>
<polygon fill="#000000" stroke="#000000" points="1386.6241,-23.6192 1396.4454,-19.6452 1386.2896,-16.6272 1386.6241,-23.6192"/>
<text text-anchor="middle" x="695.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M430.5166,-173.5756C428.6084,-162.6531 428.6188,-149.3549 436.7947,-141 450.717,-126.7729 1029.682,-111.6382 1236.391,-106.6783"/>
<polygon fill="#000000" stroke="#000000" points="1236.6235,-110.1738 1246.537,-106.4359 1236.4563,-103.1758 1236.6235,-110.1738"/>
<text text-anchor="middle" x="522.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge15" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1428.0379,-86.9735C1428.8504,-75.1918 1429.9284,-59.5607 1430.8528,-46.1581"/>
<polygon fill="#000000" stroke="#000000" points="1434.3567,-46.2205 1431.5531,-36.0034 1427.3733,-45.7388 1434.3567,-46.2205"/>
<text text-anchor="middle" x="1453.7947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1447.7284,-117.1051C1452.8287,-119.5071 1458.379,-121.6899 1463.7947,-123 1508.1377,-133.727 2252.8905,-108.3887 2284.7947,-141 2297.5581,-154.0463 2281.7553,-166.6085 2262.4211,-176.0009"/>
<polygon fill="#000000" stroke="#000000" points="2260.7487,-172.9155 2253.0688,-180.2141 2263.624,-179.2977 2260.7487,-172.9155"/>
<text text-anchor="middle" x="2312.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- generic_file -->
<g id="node9" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="580.7947" cy="-279" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="580.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge7" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M525.0761,-269.3548C412.421,-248.5585 171.3842,-196.8415 209.7947,-141 247.8249,-85.7115 286.0116,-104.5004 350.7947,-87 438.6147,-63.2764 462.2942,-63.2093 552.7947,-54 716.74,-37.3169 1228.4688,-23.2059 1386.1,-19.1629"/>
<polygon fill="#000000" stroke="#000000" points="1386.4889,-22.6542 1396.3963,-18.9003 1386.3103,-15.6565 1386.4889,-22.6542"/>
<text text-anchor="middle" x="262.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M643.5974,-273.4626C684.1691,-269.891 738.1008,-265.154 785.7947,-261 955.5621,-246.2139 997.6158,-236.875 1167.7947,-228 1278.5511,-222.2239 2056.5379,-229.0604 2165.7947,-210 2169.5072,-209.3523 2173.3112,-208.4878 2177.0938,-207.487"/>
<polygon fill="#000000" stroke="#000000" points="2178.3756,-210.7582 2186.9789,-204.5748 2176.3974,-204.0435 2178.3756,-210.7582"/>
<text text-anchor="middle" x="1220.7947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M576.4979,-260.9367C572.1596,-237.8139 568.7569,-197.8931 589.7947,-174 631.9942,-126.0731 1062.2357,-110.7309 1236.2936,-106.4622"/>
<polygon fill="#000000" stroke="#000000" points="1236.4722,-109.959 1246.3854,-106.2201 1236.3043,-102.961 1236.4722,-109.959"/>
<text text-anchor="middle" x="642.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- synonym -->
<g id="node10" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="846.7947" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="846.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge34" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M796.4094,-274.2281C667.2891,-261.7615 333.5494,-227.9431 317.7947,-210 297.0884,-186.4174 310.4605,-163.0471 332.7947,-141 375.2833,-99.0576 398.1464,-102.528 455.7947,-87 634.7086,-38.8082 1217.0685,-22.6623 1386.2879,-18.9264"/>
<polygon fill="#000000" stroke="#000000" points="1386.4443,-22.4239 1396.3661,-18.7079 1386.2925,-15.4256 1386.4443,-22.4239"/>
<text text-anchor="middle" x="375.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge33" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M897.2482,-274.0997C1005.7327,-263.7626 1269.3166,-239.7147 1490.7947,-228 1640.6386,-220.0743 2018.0866,-236.4254 2165.7947,-210 2169.5044,-209.3363 2173.3064,-208.4606 2177.0877,-207.4524"/>
<polygon fill="#000000" stroke="#000000" points="2178.3744,-210.7218 2186.9707,-204.5286 2176.3886,-204.0094 2178.3744,-210.7218"/>
<text text-anchor="middle" x="1533.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M842.3171,-260.7736C837.7834,-237.4743 834.1696,-197.363 855.7947,-174 881.4255,-146.3094 1117.8644,-121.7652 1238.5765,-110.9121"/>
<polygon fill="#000000" stroke="#000000" points="1239.1785,-114.3724 1248.8282,-109.9983 1238.5569,-107.4001 1239.1785,-114.3724"/>
<text text-anchor="middle" x="898.2947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- diagnosis -->
<g id="node11" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="2332.7947" cy="-279" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="2332.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2300.9834,-264.2496C2289.703,-258.3596 2277.2288,-251.0566 2266.7947,-243 2257.0685,-235.49 2247.5409,-225.9613 2239.571,-217.1782"/>
<polygon fill="#000000" stroke="#000000" points="2241.9618,-214.5969 2232.7285,-209.401 2236.7063,-219.2208 2241.9618,-214.5969"/>
<text text-anchor="middle" x="2311.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2346.904,-261.3019C2350.5242,-255.7587 2353.9227,-249.4071 2355.7947,-243 2365.4869,-209.8274 2376.7061,-171.8353 2340.7947,-141 2320.749,-123.7878 1416.0299,-126.1314 1389.7947,-123 1381.8627,-122.0532 1373.5664,-120.6721 1365.4358,-119.0891"/>
<polygon fill="#000000" stroke="#000000" points="1366.1362,-115.6599 1355.6361,-117.0737 1364.7261,-122.5164 1366.1362,-115.6599"/>
<text text-anchor="middle" x="2409.2947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- pathology_file -->
<g id="node12" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1516.7947" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1516.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1542.8295,-262.0284C1562.7402,-250.0551 1591.3509,-234.957 1618.7947,-228 1736.687,-198.1142 2046.1415,-231.7915 2165.7947,-210 2169.5023,-209.3248 2173.3029,-208.441 2177.0832,-207.4275"/>
<polygon fill="#000000" stroke="#000000" points="2178.3735,-210.6955 2186.9647,-204.4953 2176.3821,-203.9847 2178.3735,-210.6955"/>
<text text-anchor="middle" x="1679.7947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- methylation_array_file -->
<g id="node13" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1726.7947" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1726.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge28" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1734.1145,-260.8152C1739.8136,-249.2464 1748.9329,-235.1426 1761.7947,-228 1801.0772,-206.1849 2121.636,-218.3079 2165.7947,-210 2169.4476,-209.3128 2173.1921,-208.429 2176.9193,-207.4229"/>
<polygon fill="#000000" stroke="#000000" points="2178.0819,-210.7288 2186.6701,-204.5245 2176.0874,-204.0189 2178.0819,-210.7288"/>
<text text-anchor="middle" x="1853.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge14" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1509.8981,-87.4957C1502.4508,-77.1723 1492.3,-64.1798 1481.7947,-54 1476.2702,-48.6467 1469.9202,-43.4239 1463.6625,-38.6912"/>
<polygon fill="#000000" stroke="#000000" points="1465.415,-35.6375 1455.2725,-32.5749 1461.2914,-41.294 1465.415,-35.6375"/>
<text text-anchor="middle" x="1535.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1557.3031,-117.5569C1564.9597,-119.7766 1573.0745,-121.7692 1580.7947,-123 1605.3781,-126.9194 2459.3697,-123.2214 2476.7947,-141 2481.4612,-145.7612 2481.1709,-150.9708 2476.7947,-156 2476.7947,-156 2346.4758,-174.184 2271.0765,-184.7049"/>
<polygon fill="#000000" stroke="#000000" points="2270.2414,-181.2874 2260.8211,-186.1359 2271.2088,-188.2202 2270.2414,-181.2874"/>
<text text-anchor="middle" x="2520.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- study_admin -->
<g id="node15" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1659.7947" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1659.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge29" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1637.4575,-87.9332C1621.9972,-76.8499 1600.5448,-62.8674 1579.7947,-54 1546.9429,-39.961 1507.5199,-30.6795 1477.7734,-25.0622"/>
<polygon fill="#000000" stroke="#000000" points="1478.1468,-21.5728 1467.6818,-23.2263 1476.8939,-28.4598 1478.1468,-21.5728"/>
<text text-anchor="middle" x="1663.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- radiology_file -->
<g id="node16" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1022.7947" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1022.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1039.1777,-174.0182C1050.5627,-162.6905 1066.7108,-148.7834 1083.7947,-141 1110.9066,-128.6478 1184.007,-118.3683 1239.5928,-111.9987"/>
<polygon fill="#000000" stroke="#000000" points="1240.2072,-115.4517 1249.753,-110.8552 1239.4243,-108.4956 1240.2072,-115.4517"/>
<text text-anchor="middle" x="1142.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- study_personnel -->
<g id="node17" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="1834.7947" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1834.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge24" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1804.6683,-88.0748C1782.8739,-76.6081 1752.3544,-62.1164 1723.7947,-54 1639.7226,-30.1076 1537.5286,-22.0703 1479.3357,-19.3678"/>
<polygon fill="#000000" stroke="#000000" points="1479.4848,-15.871 1469.3431,-18.9364 1479.1828,-22.8645 1479.4848,-15.871"/>
<text text-anchor="middle" x="1833.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- sequencing_file -->
<g id="node18" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1943.7947" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1943.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1944.5946,-260.8494C1946.1144,-249.6012 1950.0298,-235.8478 1959.7947,-228 1995.6131,-199.2137 2120.8261,-219.4569 2165.7947,-210 2169.3816,-209.2457 2173.0621,-208.3229 2176.7307,-207.2976"/>
<polygon fill="#000000" stroke="#000000" points="2177.7837,-210.6358 2186.3416,-204.3898 2175.7565,-203.9358 2177.7837,-210.6358"/>
<text text-anchor="middle" x="2026.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- cytogenomic_file -->
<g id="node19" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="2134.7947" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="2134.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2111.1161,-261.158C2100.7864,-251.1928 2092.6768,-238.6714 2100.7947,-228 2118.9435,-204.1423 2137.1466,-218.8235 2165.7947,-210 2168.9523,-209.0275 2172.206,-207.9958 2175.4747,-206.9378"/>
<polygon fill="#000000" stroke="#000000" points="2176.8423,-210.1723 2185.2441,-203.7177 2174.651,-203.5241 2176.8423,-210.1723"/>
<text text-anchor="middle" x="2172.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- survival -->
<g id="node20" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1162.7947" cy="-192" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1162.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1180.8248,-175.1891C1192.9171,-164.4909 1209.5484,-150.8467 1225.7947,-141 1236.7115,-134.3834 1249.0623,-128.3396 1260.8362,-123.1718"/>
<polygon fill="#000000" stroke="#000000" points="1262.2867,-126.3583 1270.1166,-119.2208 1259.5447,-119.9177 1262.2867,-126.3583"/>
<text text-anchor="middle" x="1265.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- molecular_test -->
<g id="node21" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1308.7947" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1308.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1308.7947,-173.9735C1308.7947,-162.1918 1308.7947,-146.5607 1308.7947,-133.1581"/>
<polygon fill="#000000" stroke="#000000" points="1312.2948,-133.0033 1308.7947,-123.0034 1305.2948,-133.0034 1312.2948,-133.0033"/>
<text text-anchor="middle" x="1372.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- medical_history -->
<g id="node22" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1491.7947" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1491.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1477.9741,-174.0298C1468.6001,-163.0004 1455.3071,-149.4219 1440.7947,-141 1428.2058,-133.6944 1397.4198,-125.1334 1368.7441,-118.1931"/>
<polygon fill="#000000" stroke="#000000" points="1369.2608,-114.7185 1358.7224,-115.8105 1367.6417,-121.5286 1369.2608,-114.7185"/>
<text text-anchor="middle" x="1526.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- treatment_response -->
<g id="node23" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1699.7947" cy="-192" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1699.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1665.3207,-174.8829C1653.4149,-168.9396 1640.0025,-162.2088 1627.7947,-156 1614.8604,-149.4218 1612.734,-145.0329 1598.7947,-141 1509.2349,-115.0887 1481.9484,-137.1437 1389.7947,-123 1382.1858,-121.8322 1374.2241,-120.3676 1366.3885,-118.7811"/>
<polygon fill="#000000" stroke="#000000" points="1367.0725,-115.3484 1356.5667,-116.7193 1365.6344,-122.1991 1367.0725,-115.3484"/>
<text text-anchor="middle" x="1710.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- study_funding -->
<g id="node24" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2016.7947" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2016.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge3" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1987.9897,-88.1519C1966.4002,-76.406 1935.7193,-61.539 1906.7947,-54 1826.8834,-33.1717 1582.2387,-22.9077 1479.2559,-19.4196"/>
<polygon fill="#000000" stroke="#000000" points="1479.27,-15.9182 1469.1592,-19.084 1479.0374,-22.9143 1479.27,-15.9182"/>
<text text-anchor="middle" x="2008.7947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- publication -->
<g id="node25" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="2174.7947" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="2174.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge1" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2149.6779,-88.4585C2130.1413,-76.54 2101.8873,-61.318 2074.7947,-54 2017.879,-38.6264 1617.7409,-24.1115 1479.5776,-19.5064"/>
<polygon fill="#000000" stroke="#000000" points="1479.4338,-15.9999 1469.3234,-19.1669 1479.202,-22.996 1479.4338,-15.9999"/>
<text text-anchor="middle" x="2162.7947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- family_relationship -->
<g id="node26" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1922.7947" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1922.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1869.1831,-176.6853C1852.078,-171.0403 1833.3113,-164.0325 1816.7947,-156 1805.8197,-150.6626 1805.4125,-144.737 1793.7947,-141 1708.2448,-113.4815 1478.8845,-134.7921 1389.7947,-123 1382.0629,-121.9766 1373.9786,-120.581 1366.0367,-119.0164"/>
<polygon fill="#000000" stroke="#000000" points="1366.5919,-115.5572 1356.0903,-116.9595 1365.1743,-122.4122 1366.5919,-115.5572"/>
<text text-anchor="middle" x="1896.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
</g>
</svg>
</div>
