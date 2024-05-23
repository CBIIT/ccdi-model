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
<svg width="2315pt" height="305pt"
 viewBox="0.00 0.00 2315.25 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 2311.2469,-301 2311.2469,4 -4,4"/>
<!-- pathology_file -->
<g id="node1" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1981.5572" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1981.5572" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- sample -->
<g id="node10" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1893.5572" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1893.5572" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1969.2778,-261.0556C1961.8513,-250.8241 1951.8513,-238.0741 1941.5572,-228 1936.5552,-223.1049 1930.8725,-218.2996 1925.2109,-213.874"/>
<polygon fill="#000000" stroke="#000000" points="1927.1055,-210.9192 1917.0129,-207.6957 1922.8924,-216.5094 1927.1055,-210.9192"/>
<text text-anchor="middle" x="2015.5572" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pdx -->
<g id="node2" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1002.5572" cy="-105" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1002.5572" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1023.4907,-117.1062C1028.5909,-119.5082 1034.1413,-121.6907 1039.5572,-123 1084.4956,-133.8641 1833.2069,-115.1785 1871.5572,-141 1879.519,-146.3608 1884.6154,-155.2632 1887.871,-164.1426"/>
<polygon fill="#000000" stroke="#000000" points="1884.5927,-165.3956 1890.819,-173.9679 1891.2974,-163.3839 1884.5927,-165.3956"/>
<text text-anchor="middle" x="1907.5572" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study -->
<g id="node15" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="632.5572" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="632.5572" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge17" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M978.8893,-95.0615C972.0537,-92.3197 964.5508,-89.4326 957.5572,-87 908.9465,-70.0917 896.6947,-65.6241 846.5572,-54 788.9655,-40.6477 721.5713,-30.1382 678.0308,-24.0032"/>
<polygon fill="#000000" stroke="#000000" points="678.4232,-20.5242 668.0363,-22.6129 677.4586,-27.4574 678.4232,-20.5242"/>
<text text-anchor="middle" x="927.5572" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- methylation_array_file -->
<g id="node3" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2191.5572" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2191.5572" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2159.357,-261.6953C2137.6315,-250.6536 2108.0208,-236.8107 2080.5572,-228 2036.3866,-213.8295 1984.4607,-204.3781 1946.5491,-198.7295"/>
<polygon fill="#000000" stroke="#000000" points="1946.6444,-195.2068 1936.2458,-197.2364 1945.6405,-202.1345 1946.6444,-195.2068"/>
<text text-anchor="middle" x="2209.0572" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study_arm -->
<g id="node4" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="136.5572" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="136.5572" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge31" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M154.1989,-87.6044C167.2352,-75.916 186.0416,-61.3526 205.5572,-54 274.0855,-28.1815 489.7403,-20.7828 585.707,-18.7423"/>
<polygon fill="#000000" stroke="#000000" points="586.0537,-22.2361 595.9809,-18.5348 585.9122,-15.2376 586.0537,-22.2361"/>
<text text-anchor="middle" x="254.0572" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- study_admin -->
<g id="node5" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="284.5572" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="284.5572" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge10" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M293.2029,-86.832C299.6365,-75.4257 309.548,-61.5009 322.5572,-54 366.2657,-28.7983 510.4481,-21.2118 585.7816,-18.9486"/>
<polygon fill="#000000" stroke="#000000" points="586.0392,-22.4429 595.937,-18.6633 585.8426,-15.4456 586.0392,-22.4429"/>
<text text-anchor="middle" x="379.0572" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- exposure -->
<g id="node6" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="428.5572" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="428.5572" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- participant -->
<g id="node20" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="886.5572" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="886.5572" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M446.4914,-175.0287C460.1653,-163.2215 480.0783,-148.3319 500.5572,-141 553.4144,-122.076 696.7087,-128.74 752.5572,-123 774.8312,-120.7107 799.1114,-117.6282 820.81,-114.6615"/>
<polygon fill="#000000" stroke="#000000" points="821.481,-118.1021 830.9068,-113.2643 820.5214,-111.1682 821.481,-118.1021"/>
<text text-anchor="middle" x="544.0572" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- medical_history -->
<g id="node7" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="584.5572" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="584.5572" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M585.8149,-173.9247C587.5971,-162.7076 591.7905,-148.9602 601.5572,-141 627.7519,-119.6502 719.0323,-127.2496 752.5572,-123 774.5697,-120.2097 798.5966,-117.0258 820.1488,-114.1194"/>
<polygon fill="#000000" stroke="#000000" points="820.7439,-117.5709 830.1845,-112.7621 819.8056,-110.634 820.7439,-117.5709"/>
<text text-anchor="middle" x="669.5572" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- study_funding -->
<g id="node8" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="450.5572" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="450.5572" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M442.4202,-87.079C438.8886,-76.346 437.0591,-63.0701 444.5572,-54 462.1505,-32.7181 536.1226,-23.8963 585.8646,-20.3257"/>
<polygon fill="#000000" stroke="#000000" points="586.3387,-23.8019 596.0822,-19.6409 585.8705,-16.8176 586.3387,-23.8019"/>
<text text-anchor="middle" x="506.5572" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- cell_line -->
<g id="node9" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="1097.5572" cy="-105" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="1097.5572" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge29" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1132.7633,-117.6331C1140.1998,-119.8173 1148.0653,-121.7764 1155.5572,-123 1177.1381,-126.5247 1927.2728,-125.362 1942.5572,-141 1952.5785,-151.2532 1943.2641,-162.7632 1930.1676,-172.2505"/>
<polygon fill="#000000" stroke="#000000" points="1928.0792,-169.4353 1921.6636,-177.8669 1931.9369,-175.2764 1928.0792,-169.4353"/>
<text text-anchor="middle" x="1987.0572" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge28" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1065.7751,-91.1576C1037.4131,-79.3958 994.471,-63.0253 955.5572,-54 858.7142,-31.5391 742.1749,-22.9428 678.9243,-19.766"/>
<polygon fill="#000000" stroke="#000000" points="679.0248,-16.2669 668.8688,-19.2844 678.6899,-23.2589 679.0248,-16.2669"/>
<text text-anchor="middle" x="1044.0572" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge2" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1858.4883,-180.7464C1840.216,-174.3792 1817.7412,-165.7464 1798.5572,-156 1787.6768,-150.4723 1787.2119,-144.6203 1775.5572,-141 1697.437,-116.7338 1119.0416,-142.3345 1039.5572,-123 1037.3577,-122.465 1035.1359,-121.7866 1032.9309,-121.0086"/>
<polygon fill="#000000" stroke="#000000" points="1034.0713,-117.6926 1023.4933,-117.0951 1031.39,-124.1587 1034.0713,-117.6926"/>
<text text-anchor="middle" x="1835.0572" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge4" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1936.6283,-187.7826C1976.9781,-182.8361 2033.0457,-173.0596 2046.5572,-156 2050.6963,-150.7739 2051.2234,-145.7614 2046.5572,-141 2029.2304,-123.3196 1179.9938,-126.9576 1155.5572,-123 1151.3421,-122.3174 1147.0091,-121.4002 1142.7009,-120.3398"/>
<polygon fill="#000000" stroke="#000000" points="1143.328,-116.8836 1132.7608,-117.6486 1141.4986,-123.6404 1143.328,-116.8836"/>
<text text-anchor="middle" x="2086.0572" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1860.7196,-179.9239C1853.8003,-177.6994 1846.494,-175.583 1839.5572,-174 1777.9653,-159.9445 1756.8035,-180.4637 1698.5572,-156 1688.6377,-151.8338 1689.6757,-144.6563 1679.5572,-141 1604.9218,-114.0308 1044.3004,-132.8636 965.5572,-123 958.1814,-122.0761 950.4845,-120.7666 942.9133,-119.2702"/>
<polygon fill="#000000" stroke="#000000" points="943.5749,-115.8329 933.0702,-117.2119 942.1421,-122.6847 943.5749,-115.8329"/>
<text text-anchor="middle" x="1735.0572" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- family_relationship -->
<g id="node11" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1565.5572" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1565.5572" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1493.6883,-179.4566C1446.031,-170.903 1390.3426,-160.3648 1379.5572,-156 1368.2444,-151.4218 1368.1722,-144.7456 1356.5572,-141 1273.7743,-114.304 1051.7465,-134.708 965.5572,-123 958.1914,-121.9994 950.5004,-120.645 942.9322,-119.1253"/>
<polygon fill="#000000" stroke="#000000" points="943.5988,-115.689 933.0916,-117.0484 942.1532,-122.5381 943.5988,-115.689"/>
<text text-anchor="middle" x="1459.0572" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- radiology_file -->
<g id="node12" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1757.5572" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1757.5572" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1703.1762,-179.7536C1693.6561,-177.7394 1683.8314,-175.7429 1674.5572,-174 1624.5767,-164.6072 1609.009,-174.2921 1561.5572,-156 1550.1699,-151.6104 1550.1992,-144.6607 1538.5572,-141 1477.7923,-121.893 1028.7365,-131.113 965.5572,-123 958.1843,-122.0532 950.4891,-120.7304 942.9188,-119.227"/>
<polygon fill="#000000" stroke="#000000" points="943.5819,-115.79 933.0764,-117.1631 942.1452,-122.641 943.5819,-115.79"/>
<text text-anchor="middle" x="1620.5572" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- synonym -->
<g id="node13" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="272.5572" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="272.5572" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M324.1473,-276.3405C478.7782,-268.4132 951.997,-244.4749 1344.5572,-228 1454.5331,-223.3846 1731.2442,-229.6033 1839.5572,-210 1843.4924,-209.2878 1847.5329,-208.3509 1851.5471,-207.2782"/>
<polygon fill="#000000" stroke="#000000" points="1852.7892,-210.5612 1861.3959,-204.3827 1850.8147,-203.8455 1852.7892,-210.5612"/>
<text text-anchor="middle" x="1387.0572" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge27" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M223.0699,-273.1841C154.3256,-263.9711 35.436,-243.5441 9.5572,-210 -25.7493,-164.2357 51.219,-99.1561 67.5572,-87 107.8249,-57.0396 126.2469,-63.3596 175.5572,-54 253.3402,-39.236 486.2544,-25.6761 586.1869,-20.3664"/>
<polygon fill="#000000" stroke="#000000" points="586.4823,-23.8558 596.2841,-19.834 586.1136,-16.8655 586.4823,-23.8558"/>
<text text-anchor="middle" x="58.0572" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M268.1194,-260.8102C263.6286,-237.5505 260.0614,-197.4819 281.5572,-174 288.7174,-166.1783 459.0268,-142.2482 469.5572,-141 597.3559,-125.8516 630.5191,-135.9703 758.5572,-123 779.0894,-120.9201 801.3879,-118.0117 821.5342,-115.1384"/>
<polygon fill="#000000" stroke="#000000" points="822.1469,-118.5863 831.5421,-113.6893 821.1437,-111.6585 822.1469,-118.5863"/>
<text text-anchor="middle" x="324.0572" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- molecular_test -->
<g id="node14" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="767.5572" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="767.5572" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M750.6914,-174.3399C742.8552,-163.9612 736.803,-150.9654 744.5572,-141 754.1405,-128.6839 787.1669,-119.9031 818.9584,-114.0983"/>
<polygon fill="#000000" stroke="#000000" points="819.9525,-117.4781 829.2056,-112.3175 818.754,-110.5815 819.9525,-117.4781"/>
<text text-anchor="middle" x="808.5572" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- diagnosis -->
<g id="node16" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1211.5572" cy="-279" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1211.5572" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1259.3386,-270.2175C1323.5219,-258.7466 1441.2404,-238.8521 1542.5572,-228 1674.0473,-213.916 1709.7234,-235.1233 1839.5572,-210 1843.4305,-209.2505 1847.4089,-208.297 1851.3656,-207.2214"/>
<polygon fill="#000000" stroke="#000000" points="1852.4894,-210.5389 1861.0835,-204.3428 1850.5012,-203.8272 1852.4894,-210.5389"/>
<text text-anchor="middle" x="1587.0572" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1158.0902,-275.0982C1076.4095,-267.932 926.4353,-249.6204 892.5572,-210 874.6523,-189.0603 875.7698,-156.3268 879.7059,-132.9771"/>
<polygon fill="#000000" stroke="#000000" points="883.1755,-133.4703 881.6544,-122.9852 876.305,-132.1303 883.1755,-133.4703"/>
<text text-anchor="middle" x="937.0572" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- survival -->
<g id="node17" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1038.5572" cy="-192" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1038.5572" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1010.3601,-177.2304C998.3321,-170.832 984.1859,-163.1761 971.5572,-156 955.047,-146.6183 936.9777,-135.8491 921.7607,-126.6314"/>
<polygon fill="#000000" stroke="#000000" points="923.5273,-123.6094 913.1641,-121.4057 919.8912,-129.591 923.5273,-123.6094"/>
<text text-anchor="middle" x="1011.0572" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- clinical_measure_file -->
<g id="node18" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="127.5572" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="127.5572" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge24" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M135.7632,-174.0484C142.117,-162.4243 152.1087,-148.1639 165.5572,-141 238.4072,-102.1932 461.8535,-158.1063 536.5572,-123 572.195,-106.2523 600.676,-69.6439 617.0933,-44.4057"/>
<polygon fill="#000000" stroke="#000000" points="620.221,-46.0071 622.5868,-35.6798 614.2972,-42.2776 620.221,-46.0071"/>
<text text-anchor="middle" x="668.5572" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M145.163,-174.1067C158.6284,-160.9017 176.3922,-144.6235 185.5572,-141 244.174,-117.8252 689.7405,-128.2025 752.5572,-123 775.0741,-121.1351 799.6026,-118.1279 821.4467,-115.101"/>
<polygon fill="#000000" stroke="#000000" points="822.1925,-118.5304 831.6045,-113.6658 821.2132,-111.5993 822.1925,-118.5304"/>
<text text-anchor="middle" x="271.5572" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- cytogenomic_file -->
<g id="node19" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1613.5572" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1613.5572" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1622.4957,-260.739C1629.1262,-249.2935 1639.3048,-235.36 1652.5572,-228 1689.0541,-207.7308 1798.7168,-218.656 1839.5572,-210 1843.3637,-209.1932 1847.2768,-208.2088 1851.1735,-207.1204"/>
<polygon fill="#000000" stroke="#000000" points="1852.1853,-210.4711 1860.7563,-204.2431 1850.1722,-203.7668 1852.1853,-210.4711"/>
<text text-anchor="middle" x="1724.0572" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge5" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M836.0062,-94.3418C808.8543,-88.0571 775.004,-79.3161 745.5572,-69 718.6613,-59.5776 689.3588,-46.259 667.3339,-35.5952"/>
<polygon fill="#000000" stroke="#000000" points="668.5859,-32.3112 658.0656,-31.0566 665.5073,-38.5979 668.5859,-32.3112"/>
<text text-anchor="middle" x="796.0572" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- publication -->
<g id="node21" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="1227.5572" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="1227.5572" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge32" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1193.7768,-89.6456C1166.0989,-77.7943 1125.5973,-62.0972 1088.5572,-54 1011.4738,-37.1491 779.2985,-24.7671 679.255,-20.0697"/>
<polygon fill="#000000" stroke="#000000" points="679.2944,-16.5678 669.1428,-19.6 678.9696,-23.5603 679.2944,-16.5678"/>
<text text-anchor="middle" x="1190.5572" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- treatment_response -->
<g id="node22" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1209.5572" cy="-192" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1209.5572" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1141.0008,-178.3779C1118.9542,-172.8138 1094.7594,-165.426 1073.5572,-156 1062.4056,-151.0422 1061.8295,-145.677 1050.5572,-141 1014.8898,-126.2013 1003.2725,-131.2896 965.5572,-123 959.0033,-121.5595 952.1489,-120.0309 945.3334,-118.4969"/>
<polygon fill="#000000" stroke="#000000" points="945.941,-115.046 935.4154,-116.2554 944.3978,-121.8738 945.941,-115.046"/>
<text text-anchor="middle" x="1156.5572" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- sequencing_file -->
<g id="node23" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1804.5572" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1804.5572" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1799.8055,-260.5478C1798.2216,-250.147 1798.2216,-237.397 1804.5572,-228 1807.4862,-223.6556 1829.0099,-214.8937 1850.1549,-207.102"/>
<polygon fill="#000000" stroke="#000000" points="1851.5698,-210.3119 1859.7753,-203.6096 1849.1812,-203.732 1851.5698,-210.3119"/>
<text text-anchor="middle" x="1871.0572" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- treatment -->
<g id="node24" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="1389.5572" cy="-192" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="1389.5572" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1346.0158,-179.9922C1310.8399,-170.2382 1266.5334,-157.8095 1262.5572,-156 1251.4492,-150.9451 1251.1349,-144.8593 1239.5572,-141 1181.6684,-121.7037 1025.9386,-131.8056 965.5572,-123 958.3799,-121.9533 950.889,-120.598 943.5019,-119.101"/>
<polygon fill="#000000" stroke="#000000" points="944.0407,-115.6375 933.5322,-116.9872 942.5888,-122.4852 944.0407,-115.6375"/>
<text text-anchor="middle" x="1309.5572" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- study_personnel -->
<g id="node25" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="1395.5572" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1395.5572" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1357.1774,-88.7463C1327.3264,-76.8964 1284.5635,-61.6312 1245.5572,-54 1137.2887,-32.8184 803.4141,-22.3558 679.4905,-19.1249"/>
<polygon fill="#000000" stroke="#000000" points="679.2874,-15.6187 669.2008,-18.8608 679.1077,-22.6163 679.2874,-15.6187"/>
<text text-anchor="middle" x="1370.0572" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
</g>
</svg>
</div>
