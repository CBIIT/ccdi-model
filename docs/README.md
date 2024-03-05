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
<svg width="3034pt" height="305pt"
 viewBox="0.00 0.00 3033.93 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 3029.9348,-301 3029.9348,4 -4,4"/>
<!-- radiology_file -->
<g id="node1" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="2440.6897" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="2440.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- participant -->
<g id="node21" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1828.6897" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1828.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2415.9222,-174.8337C2397.2652,-162.9296 2370.5573,-148.0041 2344.6897,-141 2249.3742,-115.1918 1998.4331,-137.0483 1900.6897,-123 1894.9705,-122.178 1889.0457,-121.0917 1883.1627,-119.8588"/>
<polygon fill="#000000" stroke="#000000" points="1883.8679,-116.4301 1873.3454,-117.6665 1882.3422,-123.2619 1883.8679,-116.4301"/>
<text text-anchor="middle" x="2439.6897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- study_admin -->
<g id="node2" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="945.6897" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="945.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study -->
<g id="node4" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1311.6897" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1311.6897" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge19" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M950.1313,-86.936C953.9109,-75.5736 960.5528,-61.6587 971.6897,-54 995.3652,-37.7187 1177.7351,-25.4715 1265.1938,-20.4702"/>
<polygon fill="#000000" stroke="#000000" points="1265.5848,-23.9538 1275.3719,-19.8964 1265.1908,-16.9649 1265.5848,-23.9538"/>
<text text-anchor="middle" x="1028.1897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- therapeutic_procedure -->
<g id="node3" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="2770.6897" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="2770.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2718.5393,-175.8527C2677.038,-163.8086 2617.2405,-148.2384 2563.6897,-141 2271.571,-101.5148 2192.7407,-162.9837 1900.6897,-123 1894.9651,-122.2163 1889.0368,-121.1548 1883.1518,-119.9369"/>
<polygon fill="#000000" stroke="#000000" points="1883.8526,-116.5074 1873.3322,-117.7611 1882.3382,-123.3416 1883.8526,-116.5074"/>
<text text-anchor="middle" x="2730.6897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- clinical_measure_file -->
<g id="node5" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="1403.6897" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="1403.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge28" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1406.9991,-173.609C1408.0571,-163.7019 1408.1826,-151.411 1404.6897,-141 1391.3017,-101.0948 1359.279,-63.8108 1336.5612,-40.9806"/>
<polygon fill="#000000" stroke="#000000" points="1338.8427,-38.3157 1329.2539,-33.8094 1333.9396,-43.3117 1338.8427,-38.3157"/>
<text text-anchor="middle" x="1483.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1422.8645,-174.2156C1436.5219,-162.6661 1455.898,-148.4263 1475.6897,-141 1501.3924,-131.3558 1662.4514,-117.6879 1757.9055,-110.2756"/>
<polygon fill="#000000" stroke="#000000" points="1758.3679,-113.7504 1768.0687,-109.4908 1757.8289,-106.7712 1758.3679,-113.7504"/>
<text text-anchor="middle" x="1561.6897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- follow_up -->
<g id="node6" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="2970.6897" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="2970.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2938.8562,-177.2801C2910.4063,-164.9487 2867.2291,-148.2357 2827.6897,-141 2625.0166,-103.9107 2104.9308,-150.1584 1900.6897,-123 1894.8803,-122.2275 1888.8624,-121.1613 1882.8934,-119.9301"/>
<polygon fill="#000000" stroke="#000000" points="1883.4601,-116.4709 1872.9398,-117.7252 1881.9461,-123.3052 1883.4601,-116.4709"/>
<text text-anchor="middle" x="2924.6897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- publication -->
<g id="node7" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="1170.6897" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="1170.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge30" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1161.5462,-86.751C1157.6588,-76.1636 1155.4832,-63.1551 1162.6897,-54 1175.3823,-37.8756 1226.8554,-28.1138 1265.7788,-22.9004"/>
<polygon fill="#000000" stroke="#000000" points="1266.4005,-26.3495 1275.8763,-21.6104 1265.5134,-19.4059 1266.4005,-26.3495"/>
<text text-anchor="middle" x="1213.6897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- family_relationship -->
<g id="node8" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1630.6897" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1630.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1638.7002,-174.0225C1644.5947,-162.8454 1653.6706,-149.106 1665.6897,-141 1681.57,-130.2899 1724.5104,-121.0418 1762.3314,-114.6014"/>
<polygon fill="#000000" stroke="#000000" points="1763.0329,-118.033 1772.325,-112.9431 1761.8869,-111.1274 1763.0329,-118.033"/>
<text text-anchor="middle" x="1745.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- methylation_array_file -->
<g id="node9" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="115.6897" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="115.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- sample -->
<g id="node25" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="886.6897" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="886.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M142.7416,-261.4407C162.4026,-249.6752 190.1178,-235.0869 216.6897,-228 275.3568,-212.3531 682.8796,-198.3139 832.1011,-193.6424"/>
<polygon fill="#000000" stroke="#000000" points="832.5039,-197.1317 842.3903,-193.3224 832.2862,-190.1351 832.5039,-197.1317"/>
<text text-anchor="middle" x="308.1897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- cytogenomic_file -->
<g id="node10" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="338.6897" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="338.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M366.0937,-261.6639C385.9891,-250.0035 413.9916,-235.4492 440.6897,-228 512.9394,-207.8413 729.988,-197.6102 832.2578,-193.8003"/>
<polygon fill="#000000" stroke="#000000" points="832.5126,-197.2934 842.378,-193.4304 832.2568,-190.2981 832.5126,-197.2934"/>
<text text-anchor="middle" x="512.1897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node11" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="583.6897" cy="-279" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="583.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M583.4743,-260.8072C584.3725,-249.689 587.5037,-236.0952 596.6897,-228 614.0155,-212.7317 753.3925,-200.9714 832.4432,-195.4526"/>
<polygon fill="#000000" stroke="#000000" points="832.9729,-198.9245 842.7095,-194.7472 832.4931,-191.941 832.9729,-198.9245"/>
<text text-anchor="middle" x="705.1897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- synonym -->
<g id="node12" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1222.6897" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1222.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge24" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1217.294,-260.902C1210.162,-233.4169 1200.5865,-180.2083 1219.6897,-141 1225.3752,-129.3309 1233.8982,-132.55 1242.6897,-123 1264.9239,-98.8474 1284.863,-66.8034 1297.5211,-44.494"/>
<polygon fill="#000000" stroke="#000000" points="1300.6776,-46.0197 1302.4857,-35.5802 1294.5621,-42.6136 1300.6776,-46.0197"/>
<text text-anchor="middle" x="1262.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1274.9117,-278.2134C1512.1886,-274.3898 2479.0464,-256.0212 2522.6897,-210 2544.6604,-186.8322 2530.2719,-157.0836 2502.6897,-141 2473.7855,-124.1455 1933.8336,-127.584 1900.6897,-123 1894.9662,-122.2084 1889.0386,-121.1418 1883.154,-119.9208"/>
<polygon fill="#000000" stroke="#000000" points="1883.8557,-116.4915 1873.3348,-117.7416 1882.339,-123.3252 1883.8557,-116.4915"/>
<text text-anchor="middle" x="2575.1897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge23" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1183.9098,-266.8249C1165.3462,-260.5134 1143.0072,-252.203 1123.6897,-243 1111.9917,-237.427 1110.8425,-232.4956 1098.6897,-228 1046.988,-208.8743 984.3966,-199.8348 940.6794,-195.6092"/>
<polygon fill="#000000" stroke="#000000" points="940.8215,-192.1077 930.5444,-194.6831 940.1844,-199.0787 940.8215,-192.1077"/>
<text text-anchor="middle" x="1166.1897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- molecular_test -->
<g id="node13" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1828.6897" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1828.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1828.6897,-173.9735C1828.6897,-162.1918 1828.6897,-146.5607 1828.6897,-133.1581"/>
<polygon fill="#000000" stroke="#000000" points="1832.1898,-133.0033 1828.6897,-123.0034 1825.1898,-133.0034 1832.1898,-133.0033"/>
<text text-anchor="middle" x="1892.6897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- study_funding -->
<g id="node14" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="1986.6897" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="1986.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge9" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1929.1842,-92.809C1919.3557,-90.8095 1909.2381,-88.8035 1899.6897,-87 1814.1791,-70.8486 1792.9767,-65.2912 1706.6897,-54 1581.252,-37.5856 1432.4259,-26.1903 1358.3808,-21.0637"/>
<polygon fill="#000000" stroke="#000000" points="1358.2263,-17.545 1348.0104,-20.353 1357.7476,-24.5286 1358.2263,-17.545"/>
<text text-anchor="middle" x="1865.6897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- study_arm -->
<g id="node15" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2141.6897" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2141.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge6" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2099.1185,-92.154C2057.0181,-80.0481 1990.5408,-62.5307 1931.6897,-54 1821.1377,-37.975 1483.3546,-24.3062 1358.6185,-19.6782"/>
<polygon fill="#000000" stroke="#000000" points="1358.3878,-16.1674 1348.2657,-19.2967 1358.13,-23.1627 1358.3878,-16.1674"/>
<text text-anchor="middle" x="2055.1897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- pathology_file -->
<g id="node16" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="819.6897" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="819.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M816.6771,-260.7205C815.9229,-250.3774 816.6729,-237.6274 822.6897,-228 827.8045,-219.816 835.4909,-213.3241 843.7807,-208.2393"/>
<polygon fill="#000000" stroke="#000000" points="845.4631,-211.3085 852.5555,-203.4378 842.1028,-205.1678 845.4631,-211.3085"/>
<text text-anchor="middle" x="883.6897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pdx -->
<g id="node17" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1061.6897" cy="-105" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1061.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge27" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1072.1521,-88.0538C1080.1625,-76.5771 1092.2688,-62.0822 1106.6897,-54 1133.2864,-39.0941 1213.8952,-28.1969 1265.7521,-22.5003"/>
<polygon fill="#000000" stroke="#000000" points="1266.1463,-25.9782 1275.7156,-21.4307 1265.3991,-19.0182 1266.1463,-25.9782"/>
<text text-anchor="middle" x="1130.6897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1039.3457,-115.8637C1017.7962,-126.3421 988.3338,-140.671 987.6897,-141 975.1176,-147.4226 972.2446,-149.5437 959.6897,-156 948.3012,-161.8565 935.8276,-168.0781 924.4643,-173.6722"/>
<polygon fill="#000000" stroke="#000000" points="922.6656,-170.6561 915.2285,-178.202 925.748,-176.9409 922.6656,-170.6561"/>
<text text-anchor="middle" x="1011.6897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- exposure -->
<g id="node18" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1979.6897" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1979.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1975.9534,-173.5879C1972.8267,-162.67 1967.2772,-149.3724 1957.6897,-141 1954.7109,-138.3987 1918.4548,-128.3923 1885.1379,-119.5876"/>
<polygon fill="#000000" stroke="#000000" points="1885.9537,-116.1832 1875.3923,-117.0236 1884.1726,-122.9528 1885.9537,-116.1832"/>
<text text-anchor="middle" x="2011.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- diagnosis -->
<g id="node19" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="2105.6897" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="2105.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2094.3815,-174.2769C2086.0057,-162.7548 2073.5055,-148.5224 2058.6897,-141 1995.6709,-109.0034 1970.2343,-135.598 1900.6897,-123 1895.3014,-122.0239 1889.7178,-120.8758 1884.1522,-119.6397"/>
<polygon fill="#000000" stroke="#000000" points="1884.7313,-116.1813 1874.1997,-117.3379 1883.1539,-123.0013 1884.7313,-116.1813"/>
<text text-anchor="middle" x="2122.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- sequencing_file -->
<g id="node20" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="996.6897" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="996.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M980.2379,-260.9963C970.4206,-250.745 957.4206,-237.995 944.6897,-228 937.5105,-222.3636 929.4016,-216.8603 921.5721,-211.9201"/>
<polygon fill="#000000" stroke="#000000" points="923.2687,-208.8548 912.9155,-206.6048 919.6058,-214.82 923.2687,-208.8548"/>
<text text-anchor="middle" x="1028.1897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge21" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1774.3388,-95.8539C1671.6357,-78.5712 1450.8933,-41.425 1356.2564,-25.4996"/>
<polygon fill="#000000" stroke="#000000" points="1356.6001,-22.0083 1346.1579,-23.8003 1355.4384,-28.9113 1356.6001,-22.0083"/>
<text text-anchor="middle" x="1652.1897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- medical_history -->
<g id="node22" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2263.6897" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2263.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2238.9527,-174.5262C2220.9301,-162.8009 2195.4364,-148.2256 2170.6897,-141 2055.2439,-107.2917 2019.4999,-141.6586 1900.6897,-123 1895.2005,-122.1379 1889.5174,-121.0555 1883.8617,-119.8514"/>
<polygon fill="#000000" stroke="#000000" points="1884.2834,-116.3587 1873.7585,-117.574 1882.744,-123.1874 1884.2834,-116.3587"/>
<text text-anchor="middle" x="2272.6897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- study_personnel -->
<g id="node23" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2306.6897" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2306.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge3" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2259.0026,-89.8271C2219.0398,-77.829 2160.2496,-61.8382 2107.6897,-54 1961.7144,-32.2308 1506.0693,-21.7407 1358.396,-18.8511"/>
<polygon fill="#000000" stroke="#000000" points="1358.37,-15.35 1348.3043,-18.6561 1358.2348,-22.3487 1358.37,-15.35"/>
<text text-anchor="middle" x="2248.1897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- cell_line -->
<g id="node24" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="807.6897" cy="-105" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="807.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge12" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M824.1552,-87.8406C836.565,-76.104 854.6533,-61.3824 873.6897,-54 944.041,-26.7176 1167.1478,-20.1031 1264.967,-18.5057"/>
<polygon fill="#000000" stroke="#000000" points="1265.2019,-22.0026 1275.1473,-18.3503 1265.095,-15.0034 1265.2019,-22.0026"/>
<text text-anchor="middle" x="914.1897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M837.8028,-119.4248C847.3418,-125.1123 857.3121,-132.3708 864.6897,-141 870.4811,-147.7739 874.9583,-156.3039 878.3153,-164.4392"/>
<polygon fill="#000000" stroke="#000000" points="875.11,-165.8622 881.8677,-174.0221 881.6736,-163.429 875.11,-165.8622"/>
<text text-anchor="middle" x="915.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge16" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M928.7794,-186.4114C968.0665,-180.4443 1023.0599,-169.931 1039.6897,-156 1046.8091,-150.0361 1051.6854,-141.341 1054.9989,-132.814"/>
<polygon fill="#000000" stroke="#000000" points="1058.4091,-133.6479 1058.2113,-123.0549 1051.76,-131.4591 1058.4091,-133.6479"/>
<text text-anchor="middle" x="1088.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M930.9992,-190.3875C1008.1603,-187.0975 1172.0248,-177.974 1308.6897,-156 1337.1075,-151.4308 1343.2573,-145.477 1371.6897,-141 1381.0929,-139.5194 1631.8162,-120.1351 1757.8123,-110.4419"/>
<polygon fill="#000000" stroke="#000000" points="1758.4325,-113.9046 1768.1346,-109.648 1757.8957,-106.9252 1758.4325,-113.9046"/>
<text text-anchor="middle" x="1408.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge17" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M848.3894,-182.9106C823.7475,-176.1994 795.008,-166.4483 787.6897,-156 782.4807,-148.5631 783.9383,-139.5803 787.8147,-131.2389"/>
<polygon fill="#000000" stroke="#000000" points="790.8599,-132.9641 792.7692,-122.5428 784.7777,-129.4989 790.8599,-132.9641"/>
<text text-anchor="middle" x="824.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
</g>
</svg>
</div>
