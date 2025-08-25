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
<svg width="2788pt" height="392pt"
 viewBox="0.00 0.00 2787.84 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 2783.8391,-388 2783.8391,4 -4,4"/>
<!-- medical_history -->
<g id="node1" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2177.0444" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2177.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- participant -->
<g id="node24" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1354.0444" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1354.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge37" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2113.9095,-266.8703C2062.1431,-256.8798 1996.9222,-244.1697 1994.0444,-243 1982.7387,-238.4045 1982.6362,-231.8169 1971.0444,-228 1920.5453,-211.372 1578.4153,-198.9129 1426.4862,-194.1341"/>
<polygon fill="#000000" stroke="#000000" points="1426.425,-190.6306 1416.3207,-193.8169 1426.2066,-197.6272 1426.425,-190.6306"/>
<text text-anchor="middle" x="2062.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- diagnosis -->
<g id="node2" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1045.0444" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1045.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- sample -->
<g id="node12" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2324.0444" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2324.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge29" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1091.2143,-356.2113C1151.218,-343.9848 1259.4032,-323.6252 1353.0444,-315 1556.2235,-296.2853 2070.0686,-332.224 2271.0444,-297 2274.7564,-296.3494 2278.5601,-295.4829 2282.3424,-294.4807"/>
<polygon fill="#000000" stroke="#000000" points="2283.6251,-297.7516 2292.2271,-291.5664 2281.6455,-291.0373 2283.6251,-297.7516"/>
<text text-anchor="middle" x="1397.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M992.1901,-361.4086C949.9948,-356.5184 895.7466,-347.0587 882.0444,-330 877.8695,-324.8024 877.6143,-319.9818 882.0444,-315 904.7937,-289.4174 1002.4569,-307.4908 1035.0444,-297 1066.4794,-286.8802 1069.5784,-273.7433 1100.0444,-261 1147.9187,-240.9753 1161.9953,-241.7122 1212.0444,-228 1239.6536,-220.4358 1270.4358,-212.5637 1296.2633,-206.1169"/>
<polygon fill="#000000" stroke="#000000" points="1297.4079,-209.4389 1306.2676,-203.6289 1295.7185,-202.6458 1297.4079,-209.4389"/>
<text text-anchor="middle" x="1144.5444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- radiology_file -->
<g id="node3" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="507.0444" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="507.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M495.9775,-260.769C490.9523,-249.9194 487.7692,-236.6297 496.0444,-228 523.033,-199.8552 1079.0755,-193.6686 1281.3172,-192.3475"/>
<polygon fill="#000000" stroke="#000000" points="1281.5632,-195.8461 1291.5408,-192.2829 1281.5189,-188.8462 1281.5632,-195.8461"/>
<text text-anchor="middle" x="555.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- laboratory_test -->
<g id="node4" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1352.0444" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1352.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1388.8623,-349.8518C1418.5156,-337.7211 1461.6121,-322.0361 1501.0444,-315 1669.5409,-284.9342 2102.5122,-326.8651 2271.0444,-297 2274.7552,-296.3424 2278.558,-295.471 2282.3397,-294.4656"/>
<polygon fill="#000000" stroke="#000000" points="2283.6246,-297.7357 2292.2235,-291.5462 2281.6417,-291.0224 2283.6246,-297.7357"/>
<text text-anchor="middle" x="1566.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1343.6374,-348.0123C1337.3779,-336.6821 1327.7282,-322.7745 1315.0444,-315 1271.3116,-288.1942 1234.3667,-335.9966 1201.0444,-297 1190.6503,-284.836 1192.3623,-274.4396 1201.0444,-261 1220.7471,-230.5009 1257.5194,-213.3448 1290.0757,-203.7683"/>
<polygon fill="#000000" stroke="#000000" points="1291.3066,-207.0598 1300.0205,-201.0332 1289.4503,-200.3104 1291.3066,-207.0598"/>
<text text-anchor="middle" x="1266.5444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- family_relationship -->
<g id="node5" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1840.0444" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1840.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1768.7871,-266.2977C1744.7894,-260.7226 1718.2315,-253.0952 1695.0444,-243 1683.8549,-238.1283 1683.528,-232.131 1672.0444,-228 1628.2015,-212.2285 1505.3118,-201.6703 1425.7698,-196.264"/>
<polygon fill="#000000" stroke="#000000" points="1425.5401,-192.741 1415.3292,-195.5669 1425.0738,-199.7254 1425.5401,-192.741"/>
<text text-anchor="middle" x="1774.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- publication -->
<g id="node6" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="63.0444" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="63.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- study -->
<g id="node26" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1405.0444" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1405.0444" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge4" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M57.8128,-87.0295C55.8016,-76 55.6837,-62.4214 64.0444,-54 87.3252,-30.5502 1123.8073,-20.3807 1358.2478,-18.3782"/>
<polygon fill="#000000" stroke="#000000" points="1358.5124,-21.8762 1368.4824,-18.2917 1358.4531,-14.8765 1358.5124,-21.8762"/>
<text text-anchor="middle" x="115.0444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- treatment -->
<g id="node7" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="2016.0444" cy="-279" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="2016.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1972.1047,-267.0776C1964.4244,-265.0273 1956.506,-262.9349 1949.0444,-261 1917.1156,-252.7206 1907.2765,-256.1916 1877.0444,-243 1865.8589,-238.1192 1865.61,-231.8956 1854.0444,-228 1776.9081,-202.0186 1545.562,-194.7853 1426.5352,-192.7736"/>
<polygon fill="#000000" stroke="#000000" points="1426.4758,-189.2723 1416.4207,-192.6106 1426.363,-196.2713 1426.4758,-189.2723"/>
<text text-anchor="middle" x="1924.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- treatment_response -->
<g id="node8" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1617.0444" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1617.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1567.5554,-263.0676C1548.3362,-256.8493 1526.1492,-249.6329 1506.0444,-243 1472.0838,-231.7959 1433.9268,-218.9925 1404.3389,-209.0169"/>
<polygon fill="#000000" stroke="#000000" points="1405.2458,-205.6292 1394.6516,-205.7488 1403.0081,-212.2619 1405.2458,-205.6292"/>
<text text-anchor="middle" x="1589.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- generic_file -->
<g id="node9" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="310.0444" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="310.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M370.8861,-359.1541C477.5028,-347.509 705.1147,-324.2119 898.0444,-315 1050.4395,-307.7235 2120.6816,-322.8502 2271.0444,-297 2274.7585,-296.3615 2278.5636,-295.5033 2282.3469,-294.5067"/>
<polygon fill="#000000" stroke="#000000" points="2283.6258,-297.779 2292.2331,-291.6012 2281.652,-291.063 2283.6258,-297.779"/>
<text text-anchor="middle" x="951.0444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M305.68,-347.8766C301.2685,-324.6888 297.7868,-284.6978 319.0444,-261 369.8552,-204.3565 411.4776,-236.9377 487.0444,-228 640.0404,-209.9043 1101.9815,-197.7443 1281.5493,-193.5861"/>
<polygon fill="#000000" stroke="#000000" points="1281.7666,-197.0821 1291.6834,-193.353 1281.6056,-190.084 1281.7666,-197.0821"/>
<text text-anchor="middle" x="372.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge19" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M260.1548,-354.0727C223.4941,-341.9905 180.0444,-319.1927 180.0444,-279 180.0444,-279 180.0444,-279 180.0444,-105 180.0444,-44.7913 1134.0319,-23.0956 1358.2632,-18.8277"/>
<polygon fill="#000000" stroke="#000000" points="1358.4501,-22.3249 1368.3826,-18.6375 1358.3186,-15.3261 1358.4501,-22.3249"/>
<text text-anchor="middle" x="233.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- cell_line -->
<g id="node10" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2248.0444" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2248.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2241.9381,-210.3389C2239.6526,-220.7018 2238.9026,-233.4518 2245.0444,-243 2249.5089,-249.9407 2264.6096,-257.5308 2280.4299,-263.9447"/>
<polygon fill="#000000" stroke="#000000" points="2279.1642,-267.2078 2289.7528,-267.5714 2281.7021,-260.684 2279.1642,-267.2078"/>
<text text-anchor="middle" x="2285.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge15" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2201.6768,-185.4909C2158.7461,-179.1332 2093.2512,-168.592 2037.0444,-156 1872.2634,-119.0842 1836.4371,-88.0706 1671.0444,-54 1594.6634,-38.2656 1504.4774,-27.7189 1451.1728,-22.3011"/>
<polygon fill="#000000" stroke="#000000" points="1451.3173,-18.7982 1441.0187,-21.2859 1450.6208,-25.7634 1451.3173,-18.7982"/>
<text text-anchor="middle" x="1952.5444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- pathology_file -->
<g id="node11" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2150.0444" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2150.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2151.4863,-347.8473C2153.3485,-336.7452 2157.5618,-323.1541 2167.0444,-315 2202.6122,-284.4153 2225.5862,-308.5778 2271.0444,-297 2274.3948,-296.1467 2277.8376,-295.1829 2281.2824,-294.1558"/>
<polygon fill="#000000" stroke="#000000" points="2282.4266,-297.4651 2290.9209,-291.1329 2280.3318,-290.7859 2282.4266,-297.4651"/>
<text text-anchor="middle" x="2228.0444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge1" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2331.5798,-261.1497C2334.7356,-250.7035 2336.3819,-237.7036 2330.0444,-228 2323.1348,-217.4204 2312.3477,-209.9298 2300.8415,-204.6333"/>
<polygon fill="#000000" stroke="#000000" points="2302.1015,-201.3674 2291.5199,-200.8388 2299.4623,-207.8508 2302.1015,-201.3674"/>
<text text-anchor="middle" x="2370.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node21" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2473.0444" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2473.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge3" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2365.648,-272.8175C2422.2276,-264.2112 2517.0354,-249.0019 2522.0444,-243 2532.2383,-230.7855 2519.5609,-217.8706 2504.5526,-208.0933"/>
<polygon fill="#000000" stroke="#000000" points="2505.9785,-204.8674 2495.6019,-202.7281 2502.3796,-210.8714 2505.9785,-204.8674"/>
<text text-anchor="middle" x="2561.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2291.213,-266.9278C2284.5935,-264.7556 2277.6415,-262.6583 2271.0444,-261 2223.8506,-249.1365 2209.5918,-257.1894 2163.0444,-243 2147.6338,-238.3023 2145.7067,-231.7747 2130.0444,-228 2062.8825,-211.8138 1606.1183,-198.4759 1426.4364,-193.7959"/>
<polygon fill="#000000" stroke="#000000" points="1426.3775,-190.2933 1416.2902,-193.5332 1426.1962,-197.291 1426.3775,-190.2933"/>
<text text-anchor="middle" x="2199.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_funding -->
<g id="node13" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="1048.0444" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="1048.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge34" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1067.277,-87.3668C1080.9601,-75.8847 1100.3433,-61.6634 1120.0444,-54 1162.4862,-37.4908 1289.4131,-26.2155 1358.6862,-21.1083"/>
<polygon fill="#000000" stroke="#000000" points="1359.1582,-24.5834 1368.8795,-20.3706 1358.6529,-17.6016 1359.1582,-24.5834"/>
<text text-anchor="middle" x="1182.0444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- study_personnel -->
<g id="node14" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="1230.0444" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1230.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge33" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1237.2007,-86.9027C1242.478,-75.8226 1250.7145,-62.2353 1262.0444,-54 1277.594,-42.6976 1324.1103,-32.2671 1359.9107,-25.575"/>
<polygon fill="#000000" stroke="#000000" points="1360.9497,-28.9433 1370.1592,-23.7053 1359.6933,-22.057 1360.9497,-28.9433"/>
<text text-anchor="middle" x="1331.5444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- survival -->
<g id="node15" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="854.0444" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="854.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge36" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M858.4119,-260.8265C862.1602,-249.4178 868.795,-235.4926 880.0444,-228 912.5723,-206.335 1156.4836,-197.0212 1281.1464,-193.6421"/>
<polygon fill="#000000" stroke="#000000" points="1281.4664,-197.135 1291.3701,-193.3711 1281.2808,-190.1374 1281.4664,-197.135"/>
<text text-anchor="middle" x="919.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- study_admin -->
<g id="node16" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1405.0444" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1405.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge39" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1405.0444,-86.9735C1405.0444,-75.1918 1405.0444,-59.5607 1405.0444,-46.1581"/>
<polygon fill="#000000" stroke="#000000" points="1408.5445,-46.0033 1405.0444,-36.0034 1401.5445,-46.0034 1408.5445,-46.0033"/>
<text text-anchor="middle" x="1461.5444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- consent_group -->
<g id="node17" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1572.0444" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1572.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge22" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1558.4704,-87.1789C1549.2704,-76.209 1536.2363,-62.6407 1522.0444,-54 1499.9069,-40.5217 1472.3094,-31.7152 1449.4779,-26.1882"/>
<polygon fill="#000000" stroke="#000000" points="1450.2172,-22.7669 1439.6881,-23.9454 1448.654,-29.5902 1450.2172,-22.7669"/>
<text text-anchor="middle" x="1603.5444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- methylation_array_file -->
<g id="node18" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2360.0444" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2360.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge30" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2315.5658,-349.2206C2307.7681,-344.2373 2300.6783,-337.9232 2296.0444,-330 2291.0725,-321.4989 2293.9493,-312.0754 2299.4175,-303.6654"/>
<polygon fill="#000000" stroke="#000000" points="2302.2453,-305.7295 2305.5548,-295.6648 2296.6912,-301.4689 2302.2453,-305.7295"/>
<text text-anchor="middle" x="2387.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- exposure -->
<g id="node19" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="973.0444" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="973.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge38" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M965.0948,-260.8051C961.7119,-249.969 960.1354,-236.6809 968.0444,-228 988.6895,-205.3399 1175.4403,-196.6999 1281.4217,-193.6012"/>
<polygon fill="#000000" stroke="#000000" points="1281.8342,-197.0911 1291.7313,-193.3098 1281.6364,-190.0939 1281.8342,-197.0911"/>
<text text-anchor="middle" x="1011.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- synonym -->
<g id="node20" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2601.0444" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2601.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2561.6313,-353.9832C2543.1285,-347.7621 2521.0224,-339.4816 2502.0444,-330 2491.1271,-324.5456 2490.2705,-319.7868 2479.0444,-315 2446.1673,-300.9812 2406.9335,-291.9374 2376.1648,-286.4205"/>
<polygon fill="#000000" stroke="#000000" points="2376.5251,-282.9311 2366.0761,-284.6827 2375.3368,-289.8295 2376.5251,-282.9311"/>
<text text-anchor="middle" x="2544.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2600.24,-347.8872C2598.8423,-337.082 2595.3807,-323.7976 2587.0444,-315 2569.6438,-296.6364 2556.1621,-307.2748 2533.0444,-297 2476.1201,-271.6995 2471.0078,-244.8787 2411.0444,-228 2363.8009,-214.7017 1657.9752,-198.5012 1426.7667,-193.5257"/>
<polygon fill="#000000" stroke="#000000" points="1426.5194,-190.0196 1416.4466,-193.3042 1426.3692,-197.018 1426.5194,-190.0196"/>
<text text-anchor="middle" x="2575.5444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge10" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2611.367,-348.3247C2620.3849,-331.1924 2632.0444,-304.174 2632.0444,-279 2632.0444,-279 2632.0444,-279 2632.0444,-105 2632.0444,-44.6606 1675.4582,-23.049 1451.5356,-18.8167"/>
<polygon fill="#000000" stroke="#000000" points="1451.4968,-15.3154 1441.4332,-18.6282 1451.3661,-22.3142 1451.4968,-15.3154"/>
<text text-anchor="middle" x="2674.5444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2457.4588,-207.045C2445.4784,-218.035 2428.1357,-232.7469 2411.0444,-243 2397.6053,-251.0622 2382.0298,-258.1349 2367.8032,-263.8286"/>
<polygon fill="#000000" stroke="#000000" points="2366.272,-260.6683 2358.2123,-267.5452 2368.8014,-267.1953 2366.272,-260.6683"/>
<text text-anchor="middle" x="2454.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge32" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2446.9077,-185.2688C2375.3771,-167.0574 2170.1933,-116.2258 1997.0444,-87 1873.4864,-66.1447 1841.5066,-68.5149 1717.0444,-54 1622.3296,-42.9543 1511.4185,-30.1997 1450.6406,-23.2258"/>
<polygon fill="#000000" stroke="#000000" points="1450.9423,-19.7376 1440.6085,-22.075 1450.1445,-26.692 1450.9423,-19.7376"/>
<text text-anchor="middle" x="2203.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- sequencing_file -->
<g id="node22" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1775.0444" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1775.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1795.2933,-348.3457C1810.1742,-336.5354 1831.4802,-321.9327 1853.0444,-315 1941.5576,-286.5438 2179.6597,-314.1223 2271.0444,-297 2274.6978,-296.3155 2278.4427,-295.4337 2282.1701,-294.4288"/>
<polygon fill="#000000" stroke="#000000" points="2283.3318,-297.735 2291.9213,-291.5325 2281.3387,-291.0247 2283.3318,-297.735"/>
<text text-anchor="middle" x="1919.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node23" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="616.0444" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="616.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M720.6405,-360.9965C799.9547,-356.092 911.4263,-346.8168 1008.0444,-330 1034.2759,-325.4343 1039.6572,-318.5574 1066.0444,-315 1331.4511,-279.2194 2007.1504,-342.6167 2271.0444,-297 2274.7579,-296.3581 2278.5626,-295.4976 2282.3457,-294.4994"/>
<polygon fill="#000000" stroke="#000000" points="2283.6256,-297.7713 2292.2314,-291.5914 2281.6502,-291.0558 2283.6256,-297.7713"/>
<text text-anchor="middle" x="1152.0444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M611.4777,-347.69C606.8474,-324.3003 603.1296,-284.0914 625.0444,-261 669.6625,-213.9865 1105.8308,-198.089 1281.3918,-193.5673"/>
<polygon fill="#000000" stroke="#000000" points="1281.6596,-197.0617 1291.5681,-193.3104 1281.4829,-190.064 1281.6596,-197.0617"/>
<text text-anchor="middle" x="711.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge9" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M518.8391,-357.9507C436.3606,-348.8653 327.206,-330.7325 300.0444,-297 290.0098,-284.5378 290.274,-273.6704 300.0444,-261 433.1359,-88.4063 1165.8375,-32.4401 1358.5774,-20.597"/>
<polygon fill="#000000" stroke="#000000" points="1358.8899,-24.0846 1368.6605,-19.9877 1358.4676,-17.0974 1358.8899,-24.0846"/>
<text text-anchor="middle" x="519.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge35" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1391.0251,-177.2416C1427.4626,-162.7001 1483.3352,-140.4023 1523.3651,-124.4271"/>
<polygon fill="#000000" stroke="#000000" points="1524.6784,-127.6714 1532.6688,-120.7141 1522.0838,-121.17 1524.6784,-127.6714"/>
<text text-anchor="middle" x="1526.5444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- cytogenomic_file -->
<g id="node25" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1966.0444" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1966.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1975.9451,-348.0907C1983.4094,-336.4854 1994.7912,-322.2302 2009.0444,-315 2061.0905,-288.5986 2213.8251,-308.4797 2271.0444,-297 2274.6888,-296.2688 2278.4273,-295.3543 2282.1505,-294.3276"/>
<polygon fill="#000000" stroke="#000000" points="2283.327,-297.6287 2291.8949,-291.3964 2281.3106,-290.9254 2283.327,-297.6287"/>
<text text-anchor="middle" x="2080.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- genetic_analysis -->
<g id="node27" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="1563.0444" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="1563.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge24" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1592.9599,-349.0162C1615.7603,-337.0367 1648.3595,-321.9361 1679.0444,-315 1807.4219,-285.9812 2141.5286,-320.4205 2271.0444,-297 2274.7529,-296.3294 2278.554,-295.4489 2282.3347,-294.4375"/>
<polygon fill="#000000" stroke="#000000" points="2283.6236,-297.706 2292.2168,-291.5086 2281.6345,-290.9946 2283.6236,-297.706"/>
<text text-anchor="middle" x="1749.0444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1502.0504,-352.9926C1449.6016,-340.4404 1379.8221,-319.9963 1363.0444,-297 1347.0326,-275.0534 1346.5672,-243.2416 1349.0006,-220.3917"/>
<polygon fill="#000000" stroke="#000000" points="1352.496,-220.6545 1350.3246,-210.2846 1345.5553,-219.7452 1352.496,-220.6545"/>
<text text-anchor="middle" x="1433.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- study_arm -->
<g id="node28" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2720.0444" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2720.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge40" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2701.6178,-87.7658C2687.5669,-75.8279 2667.1019,-60.8899 2646.0444,-54 2588.3495,-35.1224 1670.9243,-21.588 1451.7869,-18.6142"/>
<polygon fill="#000000" stroke="#000000" points="1451.6354,-15.1119 1441.589,-18.4766 1451.5409,-22.1113 1451.6354,-15.1119"/>
<text text-anchor="middle" x="2722.5444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
</g>
</svg>
</div>
