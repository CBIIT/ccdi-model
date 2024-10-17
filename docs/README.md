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
<svg width="2726pt" height="305pt"
 viewBox="0.00 0.00 2725.65 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 2721.6546,-301 2721.6546,4 -4,4"/>
<!-- molecular_test -->
<g id="node1" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="507.8599" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="507.8599" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- participant -->
<g id="node6" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1154.8599" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1154.8599" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M495.7541,-173.789C490.1815,-162.9468 486.4628,-149.6581 494.8599,-141 517.6132,-117.5395 1050.4877,-127.489 1082.8599,-123 1088.5831,-122.2064 1094.5106,-121.1384 1100.3951,-119.9167"/>
<polygon fill="#000000" stroke="#000000" points="1101.2105,-123.321 1110.2141,-117.7366 1099.6932,-116.4874 1101.2105,-123.321"/>
<text text-anchor="middle" x="558.8599" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- methylation_array_file -->
<g id="node2" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1736.8599" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1736.8599" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- sample -->
<g id="node17" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1946.8599" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1946.8599" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1740.3703,-260.8402C1743.524,-249.5884 1749.345,-235.8341 1759.8599,-228 1808.0464,-192.0984 1835.3582,-223.7265 1893.8599,-210 1897.2746,-209.1988 1900.78,-208.2657 1904.2826,-207.2538"/>
<polygon fill="#000000" stroke="#000000" points="1905.5432,-210.5279 1914.0688,-204.2377 1903.4814,-203.8384 1905.5432,-210.5279"/>
<text text-anchor="middle" x="1851.3599" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- pdx -->
<g id="node3" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1574.8599" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1574.8599" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge30" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1596.224,-267.3138C1619.6579,-255.1257 1658.7501,-236.6195 1694.8599,-228 1781.2386,-207.3812 1806.9833,-228.4085 1893.8599,-210 1897.4456,-209.2402 1901.1253,-208.3136 1904.7934,-207.2857"/>
<polygon fill="#000000" stroke="#000000" points="1905.8481,-210.6233 1914.4034,-204.3737 1903.8181,-203.9241 1905.8481,-210.6233"/>
<text text-anchor="middle" x="1718.8599" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study -->
<g id="node26" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1998.8599" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1998.8599" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge31" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1595.8104,-266.963C1600.91,-264.5582 1606.4558,-262.3571 1611.8599,-261 1710.6491,-236.1924 1971.6285,-269.9314 2069.8599,-243 2070.3244,-242.8727 2130.6133,-210.4137 2130.8599,-210 2158.9818,-162.8132 2116.0313,-87.0627 2083.8599,-54 2072.4916,-42.3168 2056.7378,-34.2344 2041.8784,-28.7358"/>
<polygon fill="#000000" stroke="#000000" points="2042.8922,-25.3838 2032.2978,-25.4837 2040.6421,-32.0123 2042.8922,-25.3838"/>
<text text-anchor="middle" x="2161.8599" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- treatment -->
<g id="node4" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="788.8599" cy="-192" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="788.8599" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M803.3677,-174.313C814.0606,-162.6493 829.6838,-148.2355 846.8599,-141 895.3314,-120.5811 1030.9396,-131.4082 1082.8599,-123 1088.345,-122.1117 1094.0252,-121.0119 1099.6793,-119.7971"/>
<polygon fill="#000000" stroke="#000000" points="1100.8019,-123.1315 1109.7804,-117.5069 1099.254,-116.3047 1100.8019,-123.1315"/>
<text text-anchor="middle" x="893.8599" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- publication -->
<g id="node5" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="86.8599" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="86.8599" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge35" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M79.3209,-87.0789C76.0107,-76.0691 74.524,-62.494 82.8599,-54 99.7553,-36.7841 1659.7234,-21.2047 1951.9731,-18.4357"/>
<polygon fill="#000000" stroke="#000000" points="1952.2552,-21.9333 1962.2217,-18.3389 1952.1891,-14.9336 1952.2552,-21.9333"/>
<text text-anchor="middle" x="133.8599" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge27" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1213.8729,-98.9169C1373.1793,-82.4955 1809.5755,-37.5115 1952.7138,-22.7568"/>
<polygon fill="#000000" stroke="#000000" points="1953.3117,-26.2138 1962.9001,-21.7068 1952.5939,-19.2507 1953.3117,-26.2138"/>
<text text-anchor="middle" x="1677.3599" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_admin -->
<g id="node7" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1003.8599" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1003.8599" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge3" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1054.8947,-92.5576C1064.4791,-90.4942 1074.4454,-88.5314 1083.8599,-87 1413.7222,-33.3428 1817.4121,-21.2909 1952.4168,-18.6882"/>
<polygon fill="#000000" stroke="#000000" points="1952.4816,-22.1877 1962.4152,-18.5034 1952.3522,-15.1889 1952.4816,-22.1877"/>
<text text-anchor="middle" x="1389.3599" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- exposure -->
<g id="node8" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="917.8599" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="917.8599" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M929.6293,-173.956C938.041,-162.602 950.4021,-148.6891 964.8599,-141 1011.699,-116.0897 1030.8472,-133.4448 1082.8599,-123 1087.9405,-121.9797 1093.2019,-120.8358 1098.4618,-119.6322"/>
<polygon fill="#000000" stroke="#000000" points="1099.5962,-122.9608 1108.5271,-117.2609 1097.991,-116.1473 1099.5962,-122.9608"/>
<text text-anchor="middle" x="1008.3599" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- medical_history -->
<g id="node9" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1353.8599" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1353.8599" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1326.5549,-174.8678C1317.1284,-168.9233 1306.5129,-162.1956 1296.8599,-156 1286.5893,-149.4081 1284.9231,-146.1521 1273.8599,-141 1254.7778,-132.1134 1232.9647,-124.7731 1213.2706,-119.0906"/>
<polygon fill="#000000" stroke="#000000" points="1214.0669,-115.679 1203.4935,-116.3529 1212.1794,-122.4197 1214.0669,-115.679"/>
<text text-anchor="middle" x="1364.8599" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- cell_line -->
<g id="node10" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="1998.8599" cy="-105" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="1998.8599" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge23" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1966.5006,-118.8437C1957.546,-124.3598 1948.9073,-131.6637 1943.8599,-141 1940.1058,-147.944 1939.3246,-156.2239 1939.9029,-164.0715"/>
<polygon fill="#000000" stroke="#000000" points="1936.4401,-164.5812 1941.3105,-173.9902 1943.3706,-163.5976 1936.4401,-164.5812"/>
<text text-anchor="middle" x="1984.3599" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge24" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1998.8599,-86.9735C1998.8599,-75.1918 1998.8599,-59.5607 1998.8599,-46.1581"/>
<polygon fill="#000000" stroke="#000000" points="2002.36,-46.0033 1998.8599,-36.0034 1995.36,-46.0034 2002.36,-46.0033"/>
<text text-anchor="middle" x="2039.3599" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- family_relationship -->
<g id="node11" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1556.8599" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1556.8599" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1505.806,-176.4221C1489.5095,-170.7621 1471.6216,-163.812 1455.8599,-156 1444.9253,-150.5804 1444.31,-145.223 1432.8599,-141 1395.9767,-127.3968 1294.9311,-116.6257 1225.3943,-110.5297"/>
<polygon fill="#000000" stroke="#000000" points="1225.6388,-107.0379 1215.3748,-109.6644 1225.0365,-114.0119 1225.6388,-107.0379"/>
<text text-anchor="middle" x="1535.3599" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- treatment_response -->
<g id="node12" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1779.8599" cy="-192" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1779.8599" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1708.6317,-178.7897C1685.5145,-173.236 1660.1051,-165.7504 1637.8599,-156 1626.6824,-151.1007 1626.4133,-144.9316 1614.8599,-141 1545.1817,-117.289 1338.5116,-109.0689 1227.4253,-106.3178"/>
<polygon fill="#000000" stroke="#000000" points="1227.3888,-102.816 1217.3079,-106.0758 1227.2214,-109.814 1227.3888,-102.816"/>
<text text-anchor="middle" x="1720.8599" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- clinical_measure_file -->
<g id="node13" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="158.8599" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="158.8599" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M171.3641,-174.0495C180.7202,-162.2648 194.6582,-147.8149 210.8599,-141 255.5243,-122.2128 1034.8318,-129.4163 1082.8599,-123 1088.6688,-122.224 1094.6864,-121.1555 1100.6552,-119.9229"/>
<polygon fill="#000000" stroke="#000000" points="1101.6032,-123.2978 1110.6087,-117.7165 1100.0882,-116.4637 1101.6032,-123.2978"/>
<text text-anchor="middle" x="296.8599" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge10" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M165.3884,-173.8103C170.4886,-162.3949 178.7638,-148.4681 190.8599,-141 404.3729,-9.1776 502.7868,-107.6973 752.8599,-87 963.7588,-69.545 1016.5959,-66.2693 1227.8599,-54 1502.1795,-38.0687 1831.727,-24.5612 1952.0127,-19.8165"/>
<polygon fill="#000000" stroke="#000000" points="1952.4699,-23.3013 1962.3247,-19.411 1952.1948,-16.3067 1952.4699,-23.3013"/>
<text text-anchor="middle" x="838.8599" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- generic_file -->
<g id="node14" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="303.8599" cy="-279" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="303.8599" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M299.4717,-260.8552C295.0345,-237.6442 291.525,-197.6283 312.8599,-174 319.4537,-166.6974 477.0791,-142.0685 486.8599,-141 750.3023,-112.221 820.3546,-159.3465 1082.8599,-123 1088.5833,-122.2075 1094.5108,-121.1404 1100.3954,-119.9191"/>
<polygon fill="#000000" stroke="#000000" points="1101.2106,-123.3234 1110.2145,-117.7395 1099.6936,-116.4897 1101.2106,-123.3234"/>
<text text-anchor="middle" x="365.8599" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M366.8606,-273.8493C497.7208,-263.3618 808.5519,-239.5472 1069.8599,-228 1252.8361,-219.9143 1713.4904,-241.8203 1893.8599,-210 1897.5712,-209.3453 1901.3743,-208.4758 1905.1563,-207.4717"/>
<polygon fill="#000000" stroke="#000000" points="1906.4403,-210.7421 1915.0405,-204.5544 1904.4587,-204.0284 1906.4403,-210.7421"/>
<text text-anchor="middle" x="1122.8599" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge15" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M245.728,-270.5086C177.4753,-259.415 69.8775,-238.0523 40.8599,-210 .688,-171.1645 -13.23,-135.3005 14.8599,-87 29.7699,-61.3622 44.2604,-61.8532 72.8599,-54 166.1914,-28.3718 1666.0117,-19.6542 1951.9645,-18.2215"/>
<polygon fill="#000000" stroke="#000000" points="1952.4051,-21.7195 1962.3876,-18.1698 1952.3704,-14.7196 1952.4051,-21.7195"/>
<text text-anchor="middle" x="56.8599" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- study_personnel -->
<g id="node15" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2261.8599" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2261.8599" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge25" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2232.6715,-87.8122C2212.9501,-76.8198 2186.0175,-62.988 2160.8599,-54 2122.5456,-40.3116 2077.2063,-30.7704 2044.2511,-24.9663"/>
<polygon fill="#000000" stroke="#000000" points="2044.4584,-21.451 2034.0111,-23.2127 2043.2768,-28.3505 2044.4584,-21.451"/>
<text text-anchor="middle" x="2264.3599" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- pathology_file -->
<g id="node16" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1946.8599" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1946.8599" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1946.8599,-260.9735C1946.8599,-249.1918 1946.8599,-233.5607 1946.8599,-220.1581"/>
<polygon fill="#000000" stroke="#000000" points="1950.36,-220.0033 1946.8599,-210.0034 1943.36,-220.0034 1950.36,-220.0033"/>
<text text-anchor="middle" x="2007.8599" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge5" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1914.7233,-204.4615C1907.9254,-206.6581 1900.7281,-208.6657 1893.8599,-210 1859.0106,-216.7703 1599.2454,-202.1997 1574.8599,-228 1569.0659,-234.1301 1567.5842,-242.7604 1568.0076,-251.1811"/>
<polygon fill="#000000" stroke="#000000" points="1564.5458,-251.7019 1569.3072,-261.1665 1571.4872,-250.7984 1564.5458,-251.7019"/>
<text text-anchor="middle" x="1611.3599" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1913.3213,-180.243C1906.8858,-178.0911 1900.1825,-175.9208 1893.8599,-174 1864.3575,-165.0375 1855.0115,-168.5778 1826.8599,-156 1815.7174,-151.0217 1815.4572,-144.8002 1803.8599,-141 1750.3116,-123.4531 1385.2366,-111.3721 1227.3596,-106.9095"/>
<polygon fill="#000000" stroke="#000000" points="1227.3598,-103.4082 1217.2656,-106.6266 1227.1636,-110.4055 1227.3598,-103.4082"/>
<text text-anchor="middle" x="1863.3599" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge4" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1981.9892,-180.8906C2001.6229,-173.8942 2023.2488,-164.5914 2028.8599,-156 2034.3936,-147.527 2031.2256,-138.0226 2025.2336,-129.5354"/>
<polygon fill="#000000" stroke="#000000" points="2027.8862,-127.2511 2018.8152,-121.7768 2022.4926,-131.713 2027.8862,-127.2511"/>
<text text-anchor="middle" x="2067.3599" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sequencing_file -->
<g id="node18" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2123.8599" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="2123.8599" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2110.0393,-261.0298C2100.6653,-250.0004 2087.3723,-236.4219 2072.8599,-228 2046.5626,-212.7391 2036.0901,-218.369 2006.8599,-210 2002.142,-208.6492 1997.2231,-207.2153 1992.3206,-205.7696"/>
<polygon fill="#000000" stroke="#000000" points="1992.933,-202.3005 1982.3503,-202.8084 1990.94,-209.0108 1992.933,-202.3005"/>
<text text-anchor="middle" x="2157.3599" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- synonym -->
<g id="node19" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2372.8599" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2372.8599" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2372.5662,-260.9177C2371.3892,-249.8436 2367.9809,-236.2573 2358.8599,-228 2341.188,-212.0014 1958.7583,-162.6266 1935.8599,-156 1919.2097,-151.1816 1916.7696,-144.8087 1899.8599,-141 1835.4918,-126.5021 1401.393,-112.2704 1227.0874,-107.0706"/>
<polygon fill="#000000" stroke="#000000" points="1227.0845,-103.5691 1216.985,-106.7707 1226.8767,-110.566 1227.0845,-103.5691"/>
<text text-anchor="middle" x="2322.3599" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge33" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2337.124,-265.8912C2297.8427,-251.5682 2238.8221,-230.3335 2227.8599,-228 2131.4721,-207.4819 2103.701,-228.2594 2006.8599,-210 2001.5164,-208.9925 1995.9714,-207.6919 1990.5074,-206.2511"/>
<polygon fill="#000000" stroke="#000000" points="1991.3941,-202.8649 1980.8208,-203.5394 1989.507,-209.6057 1991.3941,-202.8649"/>
<text text-anchor="middle" x="2312.3599" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge32" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2377.3912,-260.9418C2387.5603,-215.5935 2406.2688,-97.4499 2337.8599,-54 2313.7058,-38.6585 2132.5891,-25.9517 2045.4405,-20.6539"/>
<polygon fill="#000000" stroke="#000000" points="2045.4871,-17.1504 2035.2953,-20.0448 2045.0675,-24.1379 2045.4871,-17.1504"/>
<text text-anchor="middle" x="2429.3599" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- survival -->
<g id="node20" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1036.8599" cy="-192" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1036.8599" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1045.0835,-173.9963C1050.7592,-163.2322 1059.1998,-149.9527 1069.8599,-141 1079.1599,-133.1896 1090.4023,-126.8487 1101.6222,-121.7916"/>
<polygon fill="#000000" stroke="#000000" points="1103.1417,-124.9495 1110.9985,-117.8416 1100.424,-118.4985 1103.1417,-124.9495"/>
<text text-anchor="middle" x="1109.3599" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- radiology_file -->
<g id="node21" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1176.8599" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1176.8599" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1164.0429,-174.1282C1160.7393,-168.5801 1157.621,-162.2694 1155.8599,-156 1153.8415,-148.8143 1153.0437,-140.8322 1152.8816,-133.3569"/>
<polygon fill="#000000" stroke="#000000" points="1156.3824,-133.3079 1153.0147,-123.2625 1149.383,-133.2155 1156.3824,-133.3079"/>
<text text-anchor="middle" x="1214.8599" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- study_funding -->
<g id="node22" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2502.8599" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2502.8599" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge29" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2478.6649,-87.6741C2461.0345,-76.0186 2436.0906,-61.4658 2411.8599,-54 2344.5538,-33.262 2138.7853,-23.1921 2045.5946,-19.5991"/>
<polygon fill="#000000" stroke="#000000" points="2045.4608,-16.0916 2035.336,-19.2123 2045.197,-23.0867 2045.4608,-16.0916"/>
<text text-anchor="middle" x="2507.8599" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- cytogenomic_file -->
<g id="node23" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1407.8599" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1407.8599" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1407.3968,-260.7857C1408.1749,-249.5114 1411.2654,-235.7528 1420.8599,-228 1461.7677,-194.9449 1842.1418,-219.5564 1893.8599,-210 1897.515,-209.3246 1901.261,-208.4492 1904.9893,-207.4486"/>
<polygon fill="#000000" stroke="#000000" points="1906.148,-210.7558 1914.7418,-204.5591 1904.1595,-204.0442 1906.148,-210.7558"/>
<text text-anchor="middle" x="1492.3599" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- study_arm -->
<g id="node24" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2657.8599" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2657.8599" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge26" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2636.4743,-87.9824C2620.2915,-76.1522 2596.9747,-61.254 2573.8599,-54 2524.0834,-38.3789 2173.5303,-24.3087 2045.5154,-19.6368"/>
<polygon fill="#000000" stroke="#000000" points="2045.3783,-16.1297 2035.2582,-19.2653 2045.1249,-23.1251 2045.3783,-16.1297"/>
<text text-anchor="middle" x="2653.3599" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- diagnosis -->
<g id="node25" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="934.8599" cy="-279" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="934.8599" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M881.7158,-274.6607C803.5233,-267.0495 663.412,-248.3198 632.8599,-210 622.8855,-197.4896 622.5762,-186.2574 632.8599,-174 666.5097,-133.8921 1058.1244,-126.907 1082.8599,-123 1088.3484,-122.1331 1094.0309,-121.0475 1099.6864,-119.8414"/>
<polygon fill="#000000" stroke="#000000" points="1100.8049,-123.1771 1109.7892,-117.5616 1099.264,-116.3488 1100.8049,-123.1771"/>
<text text-anchor="middle" x="677.3599" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M983.6609,-270.8906C1056.2781,-259.1901 1197.1855,-237.8945 1317.8599,-228 1445.4941,-217.5349 1767.8509,-232.8413 1893.8599,-210 1897.5681,-209.3278 1901.369,-208.4462 1905.1496,-207.4341"/>
<polygon fill="#000000" stroke="#000000" points="1906.439,-210.7025 1915.0315,-204.5041 1904.4491,-203.9912 1906.439,-210.7025"/>
<text text-anchor="middle" x="1362.3599" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
</g>
</svg>
</div>
