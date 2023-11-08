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
<svg width="3452pt" height="392pt"
 viewBox="0.00 0.00 3452.19 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3448.1938,-388 3448.1938,4 -4,4"/>
<!-- cell_line -->
<g id="node1" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2372.1938" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2372.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample -->
<g id="node7" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2210.1938" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2210.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2333.2493,-267.7209C2325.2998,-265.4614 2316.9845,-263.1288 2309.1938,-261 2278.6216,-252.6461 2265.479,-262.1076 2240.1938,-243 2232.1288,-236.9055 2225.8313,-227.9605 2221.1342,-219.2571"/>
<polygon fill="#000000" stroke="#000000" points="2224.1792,-217.5155 2216.6574,-210.054 2217.8844,-220.5776 2224.1792,-217.5155"/>
<text text-anchor="middle" x="2280.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- participant -->
<g id="node8" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1394.1938" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1394.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2335.574,-266.7676C2328.8342,-264.7072 2321.8308,-262.6915 2315.1938,-261 2274.8202,-250.7105 2263.9683,-251.5638 2223.1938,-243 2157.6641,-229.2369 2138.9168,-233.4387 2076.1938,-210 2015.6545,-187.3773 2010.3112,-158.8385 1948.1938,-141 1859.9139,-115.6483 1596.0201,-108.0912 1466.9269,-105.8845"/>
<polygon fill="#000000" stroke="#000000" points="1466.7979,-102.382 1456.7416,-105.7167 1466.6826,-109.3811 1466.7979,-102.382"/>
<text text-anchor="middle" x="2116.6938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- study -->
<g id="node14" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2224.1938" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2224.1938" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge4" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2421.6964,-277.2826C2546.0531,-272.7291 2862.7751,-259.5546 2878.1938,-243 2882.7375,-238.1216 2879.1339,-234.6 2878.1938,-228 2866.5957,-146.5756 2886.4943,-94.9961 2815.1938,-54 2768.5037,-27.1544 2402.1781,-20.1363 2270.8475,-18.4738"/>
<polygon fill="#000000" stroke="#000000" points="2270.7477,-14.9724 2260.7057,-18.3502 2270.6623,-21.9719 2270.7477,-14.9724"/>
<text text-anchor="middle" x="2912.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- therapeutic_procedure -->
<g id="node2" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="715.1938" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="715.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M714.0072,-173.9075C714.3393,-162.6832 716.8895,-148.9344 726.1938,-141 748.5614,-121.9255 1153.4686,-110.5029 1321.7663,-106.561"/>
<polygon fill="#000000" stroke="#000000" points="1321.8628,-110.0598 1331.779,-106.3288 1321.7005,-103.0617 1321.8628,-110.0598"/>
<text text-anchor="middle" x="819.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- molecular_test -->
<g id="node3" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1052.1938" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1052.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1067.6844,-174.3387C1078.8475,-162.8441 1094.9345,-148.6194 1112.1938,-141 1148.7736,-124.8513 1252.0191,-114.7229 1322.8861,-109.4632"/>
<polygon fill="#000000" stroke="#000000" points="1323.3748,-112.937 1333.0952,-108.7224 1322.8681,-105.9554 1323.3748,-112.937"/>
<text text-anchor="middle" x="1176.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- study_admin -->
<g id="node4" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="70.1938" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="70.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge33" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M64.9332,-87.0006C62.9104,-75.9596 62.7905,-62.379 71.1938,-54 90.5081,-34.7413 1865.3562,-20.6676 2177.5632,-18.3398"/>
<polygon fill="#000000" stroke="#000000" points="2177.6569,-21.8393 2187.6306,-18.2651 2177.6049,-14.8395 2177.6569,-21.8393"/>
<text text-anchor="middle" x="127.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- clinical_measure_file -->
<g id="node5" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="335.1938" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="335.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M328.0367,-173.6198C325.1085,-162.7139 324.0566,-149.4177 332.1938,-141 349.3978,-123.2029 1084.6115,-109.9379 1321.4796,-106.1197"/>
<polygon fill="#000000" stroke="#000000" points="1321.7666,-109.6157 1331.7091,-105.9557 1321.6543,-102.6166 1321.7666,-109.6157"/>
<text text-anchor="middle" x="461.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge1" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M323.1938,-173.8898C317.661,-163.0857 313.947,-149.8014 322.1938,-141 387.7032,-71.0846 1891.8758,-26.9898 2177.5753,-19.2303"/>
<polygon fill="#000000" stroke="#000000" points="2177.7021,-22.7282 2187.6039,-18.9593 2177.513,-15.7308 2177.7021,-22.7282"/>
<text text-anchor="middle" x="748.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- pdx -->
<g id="node6" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2154.1938" cy="-105" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2154.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge34" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2176.2845,-116.3304C2181.1426,-118.6574 2186.2991,-121.0037 2191.1938,-123 2214.6185,-132.554 2230.4016,-120.477 2245.1938,-141 2251.7671,-150.12 2247.1113,-160.3097 2239.3111,-169.169"/>
<polygon fill="#000000" stroke="#000000" points="2236.8186,-166.7117 2232.1969,-176.2453 2241.7551,-171.6746 2236.8186,-166.7117"/>
<text text-anchor="middle" x="2273.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge35" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2164.4215,-87.8725C2170.7926,-77.6826 2179.4233,-64.6983 2188.1938,-54 2191.6085,-49.8347 2195.4374,-45.6125 2199.2898,-41.5966"/>
<polygon fill="#000000" stroke="#000000" points="2202.0702,-43.7634 2206.6244,-34.1973 2197.0987,-38.8354 2202.0702,-43.7634"/>
<text text-anchor="middle" x="2212.1938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge17" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2249.8918,-200.0413C2271.9795,-205.6683 2299.339,-214.6155 2321.1938,-228 2332.3726,-234.8462 2342.9372,-244.6218 2351.5205,-253.7859"/>
<polygon fill="#000000" stroke="#000000" points="2348.9489,-256.1606 2358.2346,-261.2623 2354.1571,-251.4835 2348.9489,-256.1606"/>
<text text-anchor="middle" x="2376.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge16" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2189.7845,-175.9655C2183.476,-170.209 2176.9445,-163.3172 2172.1938,-156 2167.592,-148.9123 2164.0011,-140.5048 2161.2791,-132.5814"/>
<polygon fill="#000000" stroke="#000000" points="2164.5934,-131.452 2158.2852,-122.9398 2157.9083,-133.5279 2164.5934,-131.452"/>
<text text-anchor="middle" x="2208.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2174.2246,-181.469C2125.4242,-167.2511 2042.6384,-143.4047 2028.1938,-141 1922.0988,-123.3373 1609.4311,-111.6859 1466.7125,-107.143"/>
<polygon fill="#000000" stroke="#000000" points="1466.4284,-103.6324 1456.323,-106.8153 1466.2077,-110.6289 1466.4284,-103.6324"/>
<text text-anchor="middle" x="2118.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge11" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1452.8885,-98.8477C1609.9517,-82.3844 2037.468,-37.5725 2178.4289,-22.797"/>
<polygon fill="#000000" stroke="#000000" points="2178.8839,-26.2686 2188.4645,-21.7451 2178.1541,-19.3068 2178.8839,-26.2686"/>
<text text-anchor="middle" x="1909.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- medical_history -->
<g id="node9" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1235.1938" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1235.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge40" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1237.3342,-173.582C1239.5475,-162.6619 1244.0473,-149.364 1253.1938,-141 1264.6759,-130.5002 1297.7491,-121.7704 1328.979,-115.538"/>
<polygon fill="#000000" stroke="#000000" points="1329.8666,-118.9314 1339.0241,-113.6031 1328.5426,-112.0578 1329.8666,-118.9314"/>
<text text-anchor="middle" x="1321.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- study_arm -->
<g id="node10" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2260.1938" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2260.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge5" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2252.7345,-86.9735C2247.7297,-74.8784 2241.046,-58.7263 2235.4048,-45.0934"/>
<polygon fill="#000000" stroke="#000000" points="2238.5779,-43.6076 2231.5203,-35.7057 2232.1098,-46.2841 2238.5779,-43.6076"/>
<text text-anchor="middle" x="2293.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- exposure -->
<g id="node11" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1391.1938" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1391.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1391.8154,-173.9735C1392.2216,-162.1918 1392.7606,-146.5607 1393.2228,-133.1581"/>
<polygon fill="#000000" stroke="#000000" points="1396.7262,-133.1181 1393.573,-123.0034 1389.7303,-132.8768 1396.7262,-133.1181"/>
<text text-anchor="middle" x="1436.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- cytogenomic_file -->
<g id="node12" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="2207.1938" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="2207.1938" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;cell_line -->
<g id="edge20" class="edge">
<title>cytogenomic_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2202.3257,-347.9506C2200.5719,-337.1693 2200.6005,-323.8877 2208.1938,-315 2223.0027,-297.6666 2286.9823,-302.1382 2309.1938,-297 2314.1238,-295.8595 2319.2427,-294.5719 2324.336,-293.2227"/>
<polygon fill="#000000" stroke="#000000" points="2325.3166,-296.5832 2334.0429,-290.5747 2323.4743,-289.83 2325.3166,-296.5832"/>
<text text-anchor="middle" x="2279.6938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;pdx -->
<g id="edge21" class="edge">
<title>cytogenomic_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2296.2169,-363.7383C2456.8804,-359.2189 2780.3171,-347.9379 2797.1938,-330 2801.762,-325.1445 2801.0494,-320.4386 2797.1938,-315 2662.0828,-124.4187 2527.5585,-198.7512 2301.1938,-141 2253.1922,-128.7536 2238.4093,-137.9938 2191.1938,-123 2189.2534,-122.3838 2187.2865,-121.6817 2185.323,-120.9205"/>
<polygon fill="#000000" stroke="#000000" points="2186.2403,-117.5039 2175.6727,-116.7456 2183.4609,-123.9285 2186.2403,-117.5039"/>
<text text-anchor="middle" x="2802.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2137.364,-354.6405C2096.328,-347.2525 2051.3007,-337.613 2045.1938,-330 2041.0223,-324.7997 2040.9963,-320.1794 2045.1938,-315 2069.5067,-284.9993 2097.563,-317.6493 2130.1938,-297 2160.2829,-277.9591 2183.3173,-243.3526 2196.7766,-219.0892"/>
<polygon fill="#000000" stroke="#000000" points="2199.9901,-220.5022 2201.6244,-210.0341 2193.8189,-217.1982 2199.9901,-220.5022"/>
<text text-anchor="middle" x="2239.6938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- pathology_file -->
<g id="node13" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2004.1938" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2004.1938" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge12" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2023.016,-348.3127C2036.6627,-336.6488 2056.1684,-322.235 2076.1938,-315 2173.8779,-279.7075 2206.9652,-315.3597 2309.1938,-297 2314.3107,-296.081 2319.6086,-294.9165 2324.8597,-293.6233"/>
<polygon fill="#000000" stroke="#000000" points="2326.0537,-296.9287 2334.8403,-291.0088 2324.2797,-290.1572 2326.0537,-296.9287"/>
<text text-anchor="middle" x="2137.1938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge13" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1943.0757,-355.1463C1876.9874,-340.6281 1785.6634,-310.7731 1822.1938,-261 1851.1371,-221.5644 1879.2306,-237.6135 1927.1938,-228 1970.2966,-219.3607 2090.3403,-238.0435 2124.1938,-210 2146.5773,-191.458 2152.9105,-157.4661 2154.3897,-133.1797"/>
<polygon fill="#000000" stroke="#000000" points="2157.8898,-133.2401 2154.7639,-123.1169 2150.8946,-132.9799 2157.8898,-133.2401"/>
<text text-anchor="middle" x="1988.1938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1998.2782,-347.7241C1992.1748,-325.0997 1985.8792,-286.4492 2004.1938,-261 2006.6524,-257.5835 2105.9011,-225.3643 2165.7219,-206.1841"/>
<polygon fill="#000000" stroke="#000000" points="2166.8665,-209.4927 2175.3225,-203.1093 2164.7314,-202.8263 2166.8665,-209.4927"/>
<text text-anchor="middle" x="2065.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- synonym -->
<g id="node15" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="869.1938" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="869.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge23" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M921.3671,-278.3755C1093.5782,-276.0928 1637.2168,-267.0412 1712.1938,-243 1723.815,-239.2737 1723.5815,-231.7541 1735.1938,-228 1815.4226,-202.0632 2030.4472,-219.7926 2114.1938,-210 2129.5203,-208.2078 2146.081,-205.4154 2161.0618,-202.5602"/>
<polygon fill="#000000" stroke="#000000" points="2162.0054,-205.9419 2171.1462,-200.585 2160.6599,-199.0725 2162.0054,-205.9419"/>
<text text-anchor="middle" x="1777.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M864.6996,-260.7581C860.1478,-237.4421 856.5146,-197.3127 878.1938,-174 907.9989,-141.949 1188.1233,-118.8968 1322.6922,-109.5754"/>
<polygon fill="#000000" stroke="#000000" points="1323.1691,-113.051 1332.9062,-108.8749 1322.6901,-106.0674 1323.1691,-113.051"/>
<text text-anchor="middle" x="920.6938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge22" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M817.2132,-277.4111C669.8055,-272.3744 257.1406,-254.3974 217.1938,-210 196.374,-186.8607 207.1956,-163.022 229.1938,-141 278.6781,-91.462 308.615,-101.1302 377.1938,-87 558.14,-49.7173 1908.2761,-23.6732 2177.5524,-18.8194"/>
<polygon fill="#000000" stroke="#000000" points="2177.8251,-22.3152 2187.7606,-18.6363 2177.6994,-15.3163 2177.8251,-22.3152"/>
<text text-anchor="middle" x="271.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- family_relationship -->
<g id="node16" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1562.1938" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1562.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1538.0128,-174.394C1522.9798,-163.9088 1502.9957,-150.7835 1484.1938,-141 1471.3401,-134.3116 1456.9518,-128.05 1443.5152,-122.6846"/>
<polygon fill="#000000" stroke="#000000" points="1444.5231,-119.3208 1433.935,-118.9429 1441.9764,-125.8412 1444.5231,-119.3208"/>
<text text-anchor="middle" x="1588.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- follow_up -->
<g id="node17" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="1735.1938" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="1735.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1719.0115,-174.6046C1707.2025,-163.0746 1690.1744,-148.7008 1672.1938,-141 1636.1101,-125.5459 1535.1141,-115.2735 1465.3418,-109.7889"/>
<polygon fill="#000000" stroke="#000000" points="1465.5248,-106.2927 1455.2856,-109.0144 1464.9872,-113.272 1465.5248,-106.2927"/>
<text text-anchor="middle" x="1742.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- publication -->
<g id="node18" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="2401.1938" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="2401.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge42" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2385.9593,-87.1713C2375.7184,-76.1983 2361.36,-62.6295 2346.1938,-54 2322.2614,-40.3826 2292.7002,-31.49 2268.6708,-25.9501"/>
<polygon fill="#000000" stroke="#000000" points="2269.2609,-22.4964 2258.7437,-23.7771 2267.764,-29.3345 2269.2609,-22.4964"/>
<text text-anchor="middle" x="2418.1938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- sequencing_file -->
<g id="node19" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1798.1938" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1798.1938" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge29" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1827.5867,-349.1462C1849.9905,-337.2331 1882.0263,-322.1586 1912.1938,-315 2084.0473,-274.2199 2134.8751,-325.4543 2309.1938,-297 2314.5264,-296.1295 2320.0491,-294.9624 2325.5077,-293.6387"/>
<polygon fill="#000000" stroke="#000000" points="2326.4111,-297.0202 2335.209,-291.117 2324.6501,-290.2453 2326.4111,-297.0202"/>
<text text-anchor="middle" x="1978.6938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge30" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1739.0678,-353.1819C1655.1998,-332.5197 1517.8927,-288.0138 1575.1938,-228 1605.0737,-196.7055 1925.245,-228.8455 1964.1938,-210 2000.7759,-192.2996 1989.8182,-162.6766 2024.1938,-141 2052.2982,-123.2779 2089.1795,-114.142 2116.4775,-109.5185"/>
<polygon fill="#000000" stroke="#000000" points="2117.0945,-112.9646 2126.4322,-107.9589 2116.011,-106.049 2117.0945,-112.9646"/>
<text text-anchor="middle" x="1641.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge28" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1802.8747,-347.8415C1810.0677,-323.8438 1826.2546,-282.1439 1856.1938,-261 1896.3008,-232.6753 1916.8026,-251.3159 1965.1938,-243 2002.5698,-236.577 2011.8482,-234.5976 2049.1938,-228 2094.9567,-219.9154 2107.0209,-220.9094 2152.1938,-210 2156.6375,-208.9268 2161.2398,-207.7008 2165.8194,-206.4045"/>
<polygon fill="#000000" stroke="#000000" points="2167.1329,-209.6665 2175.7386,-203.4865 2165.1573,-202.9511 2167.1329,-209.6665"/>
<text text-anchor="middle" x="1922.6938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- study_funding -->
<g id="node20" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2559.1938" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2559.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge31" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2535.98,-87.8131C2519.3443,-76.3787 2495.9455,-62.0335 2473.1938,-54 2436.7903,-41.1462 2331.9335,-28.8785 2270.5182,-22.5165"/>
<polygon fill="#000000" stroke="#000000" points="2270.6216,-19.0088 2260.3172,-21.4726 2269.9089,-25.9725 2270.6216,-19.0088"/>
<text text-anchor="middle" x="2567.1938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node21" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2822.1938" cy="-366" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="2822.1938" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge38" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2692.7278,-359.7713C2564.3649,-352.9635 2385.2197,-341.4874 2374.1938,-330 2368.4989,-324.0667 2366.6704,-315.7321 2366.6535,-307.5173"/>
<polygon fill="#000000" stroke="#000000" points="2370.157,-307.6078 2367.4461,-297.3656 2363.1782,-307.0628 2370.157,-307.6078"/>
<text text-anchor="middle" x="2482.6938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge37" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2892.7048,-350.5325C2943.2043,-337.8598 3004.8815,-318.5515 3020.1938,-297 3058.1844,-243.5294 3008.7831,-173.0158 2957.1938,-141 2921.0253,-118.5542 2232.5598,-133.0413 2191.1938,-123 2188.9941,-122.466 2186.7721,-121.7885 2184.5669,-121.0111"/>
<polygon fill="#000000" stroke="#000000" points="2185.7071,-117.6949 2175.129,-117.0989 2183.0266,-124.1614 2185.7071,-117.6949"/>
<text text-anchor="middle" x="3140.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge39" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2825.604,-347.8308C2826.6708,-337.7632 2826.6019,-325.2484 2822.1938,-315 2817.5975,-304.3143 2809.7518,-306.6073 2803.1938,-297 2784.5352,-269.6657 2802.0433,-247.3497 2775.1938,-228 2754.6965,-213.2281 2402.5483,-198.9585 2264.8002,-193.9162"/>
<polygon fill="#000000" stroke="#000000" points="2264.6011,-190.4067 2254.4806,-193.541 2264.3468,-197.4021 2264.6011,-190.4067"/>
<text text-anchor="middle" x="2911.6938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- radiology_file -->
<g id="node22" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1882.1938" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1882.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge41" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1858.3675,-174.9492C1840.713,-163.2651 1815.5844,-148.5617 1791.1938,-141 1732.458,-122.7905 1563.9585,-112.5144 1466.3918,-107.9322"/>
<polygon fill="#000000" stroke="#000000" points="1466.4585,-104.4317 1456.3078,-107.467 1466.1359,-111.4242 1466.4585,-104.4317"/>
<text text-anchor="middle" x="1885.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- methylation_array_file -->
<g id="node23" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="3093.1938" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="3093.1938" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge8" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M3009.5298,-353.5168C2996.0518,-351.6033 2982.2442,-349.701 2969.1938,-348 2771.6943,-322.2576 2536.784,-296.5399 2430.0722,-285.1237"/>
<polygon fill="#000000" stroke="#000000" points="2430.1595,-281.6132 2419.8444,-284.0313 2429.4161,-288.5736 2430.1595,-281.6132"/>
<text text-anchor="middle" x="2912.6938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge9" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M3161.1793,-351.4143C3191.8966,-341.2947 3225.8014,-324.5026 3246.1938,-297 3264.5528,-272.2397 3271.3821,-252.8859 3253.1938,-228 3178.051,-125.1873 3105.796,-161.9995 2980.1938,-141 2807.2157,-112.0798 2361.6376,-164.3122 2191.1938,-123 2188.9939,-122.4668 2186.7717,-121.7898 2184.5665,-121.0128"/>
<polygon fill="#000000" stroke="#000000" points="2185.7065,-117.6966 2175.1284,-117.1016 2183.0266,-124.1634 2185.7065,-117.6966"/>
<text text-anchor="middle" x="3352.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3086.682,-347.681C3077.056,-323.5015 3056.592,-281.5961 3024.1938,-261 2960.2694,-220.3623 2436.1552,-199.4975 2264.4393,-193.7047"/>
<polygon fill="#000000" stroke="#000000" points="2264.4749,-190.2041 2254.3637,-193.3686 2264.2414,-197.2002 2264.4749,-190.2041"/>
<text text-anchor="middle" x="3150.6938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- diagnosis -->
<g id="node24" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="525.1938" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="525.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M553.6153,-176.5718C580.1482,-162.2985 616.7458,-142.9909 624.1938,-141 690.341,-123.3179 1142.8178,-110.9 1321.67,-106.6299"/>
<polygon fill="#000000" stroke="#000000" points="1321.8576,-110.1265 1331.7718,-106.3904 1321.6916,-103.1285 1321.8576,-110.1265"/>
<text text-anchor="middle" x="668.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- study_personnel -->
<g id="node25" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2741.1938" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2741.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge36" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2712.4764,-87.9984C2691.3108,-76.3381 2661.4141,-61.6429 2633.1938,-54 2565.9505,-35.7884 2362.9477,-24.3996 2270.7043,-20.0319"/>
<polygon fill="#000000" stroke="#000000" points="2270.6991,-16.5279 2260.5469,-19.5582 2270.3729,-23.5203 2270.6991,-16.5279"/>
<text text-anchor="middle" x="2741.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
</g>
</svg>
</div>
