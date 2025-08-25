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
<svg width="2859pt" height="392pt"
 viewBox="0.00 0.00 2858.88 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 2854.8835,-388 2854.8835,4 -4,4"/>
<!-- treatment_response -->
<g id="node1" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="403.5404" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="403.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- participant -->
<g id="node6" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1248.5404" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1248.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M410.177,-260.842C415.4353,-249.2849 424.0049,-235.184 436.5404,-228 468.3202,-209.7872 982.8352,-197.4339 1176.0142,-193.4179"/>
<polygon fill="#000000" stroke="#000000" points="1176.1448,-196.9161 1186.0704,-193.2104 1176.0003,-189.9176 1176.1448,-196.9161"/>
<text text-anchor="middle" x="519.5404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- sequencing_file -->
<g id="node2" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2423.5404" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="2423.5404" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sample -->
<g id="node9" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2123.5404" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2123.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2405.8335,-348.2553C2393.3919,-336.8777 2375.7719,-322.8216 2357.5404,-315 2326.0043,-301.4705 2236.0577,-290.2748 2177.3127,-284.1243"/>
<polygon fill="#000000" stroke="#000000" points="2177.394,-280.6143 2167.0881,-283.0716 2176.677,-287.5775 2177.394,-280.6143"/>
<text text-anchor="middle" x="2449.0404" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- methylation_array_file -->
<g id="node3" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2036.5404" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2036.5404" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2032.2612,-347.5312C2030.9181,-337.1249 2031.1681,-324.3749 2037.5404,-315 2040.3485,-310.8687 2060.4467,-302.3504 2080.5067,-294.6368"/>
<polygon fill="#000000" stroke="#000000" points="2081.8544,-297.869 2089.9657,-291.0531 2079.3743,-291.3231 2081.8544,-297.869"/>
<text text-anchor="middle" x="2129.0404" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- family_relationship -->
<g id="node4" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="626.5404" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="626.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M612.993,-260.9607C606.6433,-250.1832 602.1264,-236.9021 610.5404,-228 629.6949,-207.7342 1012.3988,-197.0938 1175.7064,-193.4613"/>
<polygon fill="#000000" stroke="#000000" points="1176.219,-196.951 1186.1397,-193.2322 1176.0652,-189.9527 1176.219,-196.951"/>
<text text-anchor="middle" x="690.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- clinical_measure_file -->
<g id="node5" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="108.5404" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="108.5404" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge39" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M103.9558,-347.9975C99.181,-324.5648 95.1741,-283.9108 117.5404,-261 154.5837,-223.0548 931.8029,-200.075 1175.874,-193.7739"/>
<polygon fill="#000000" stroke="#000000" points="1176.1504,-197.2681 1186.0574,-193.5128 1175.9709,-190.2704 1176.1504,-197.2681"/>
<text text-anchor="middle" x="203.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge38" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M208.3318,-358.8635C371.2957,-347.5123 704.7536,-325.5514 987.5404,-315 1107.6956,-310.5167 1951.0184,-317.2466 2069.5404,-297 2073.4824,-296.3266 2077.5276,-295.4163 2081.5448,-294.3608"/>
<polygon fill="#000000" stroke="#000000" points="2082.7761,-297.6476 2091.3981,-291.4903 2080.8182,-290.927 2082.7761,-297.6476"/>
<text text-anchor="middle" x="1073.5404" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- study -->
<g id="node28" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1390.5404" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1390.5404" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge40" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M75.3413,-348.594C51.8619,-333.64 24.5404,-309.6534 24.5404,-279 24.5404,-279 24.5404,-279 24.5404,-105 24.5404,-69.9909 60.6187,-67.8505 130.5404,-54 251.0678,-30.1253 1129.8436,-20.4339 1343.7156,-18.4148"/>
<polygon fill="#000000" stroke="#000000" points="1344.005,-21.9123 1353.9719,-18.319 1343.9396,-14.9126 1344.005,-21.9123"/>
<text text-anchor="middle" x="110.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- consent_group -->
<g id="node17" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1248.5404" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1248.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge6" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1248.5404,-173.9735C1248.5404,-162.1918 1248.5404,-146.5607 1248.5404,-133.1581"/>
<polygon fill="#000000" stroke="#000000" points="1252.0405,-133.0033 1248.5404,-123.0034 1245.0405,-133.0034 1252.0405,-133.0033"/>
<text text-anchor="middle" x="1299.0404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- treatment -->
<g id="node7" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="1183.5404" cy="-279" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="1183.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1185.9183,-260.7294C1187.9609,-250.3892 1191.7109,-237.6392 1198.5404,-228 1202.0661,-223.0238 1206.5015,-218.4784 1211.2664,-214.4188"/>
<polygon fill="#000000" stroke="#000000" points="1213.7254,-216.9417 1219.4943,-208.0552 1209.4428,-211.4046 1213.7254,-216.9417"/>
<text text-anchor="middle" x="1245.5404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- laboratory_test -->
<g id="node8" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1623.5404" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1623.5404" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1566.8841,-352.9078C1541.0513,-344.3624 1519.2669,-331.6805 1534.5404,-315 1565.2737,-281.4355 1707.8071,-330.5645 1738.5404,-297 1749.3454,-285.1996 1748.0073,-273.8988 1738.5404,-261 1709.597,-221.5644 1681.4934,-237.6643 1633.5404,-228 1526.0004,-206.3267 1398.8776,-197.6541 1320.9919,-194.2158"/>
<polygon fill="#000000" stroke="#000000" points="1320.9445,-190.7108 1310.8051,-193.7837 1320.6478,-197.7045 1320.9445,-190.7108"/>
<text text-anchor="middle" x="1811.0404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge24" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1656.9054,-349.409C1668.8306,-343.3932 1682.3344,-336.482 1694.5404,-330 1706.6643,-323.5615 1708.3452,-318.7856 1721.5404,-315 1870.4085,-272.2909 1917.3587,-325.7494 2069.5404,-297 2073.4169,-296.2677 2077.3976,-295.326 2081.3558,-294.2581"/>
<polygon fill="#000000" stroke="#000000" points="2082.4747,-297.5772 2091.0758,-291.3909 2080.4941,-290.8632 2082.4747,-297.5772"/>
<text text-anchor="middle" x="1787.0404" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2089.6839,-267.2363C2083.0365,-265.0623 2076.0931,-262.8856 2069.5404,-261 2037.0124,-251.6401 2027.5941,-253.8737 1995.5404,-243 1979.8995,-237.6941 1977.6105,-231.8131 1961.5404,-228 1900.4562,-213.506 1489.4448,-199.4044 1320.668,-194.153"/>
<polygon fill="#000000" stroke="#000000" points="1320.7363,-190.6536 1310.6327,-193.8424 1320.5196,-197.6502 1320.7363,-190.6536"/>
<text text-anchor="middle" x="2032.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node16" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2407.5404" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2407.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge34" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2158.9349,-268.1573C2213.554,-251.4254 2317.762,-219.5025 2372.2923,-202.7978"/>
<polygon fill="#000000" stroke="#000000" points="2373.6537,-206.0414 2382.19,-199.7658 2371.6034,-199.3484 2373.6537,-206.0414"/>
<text text-anchor="middle" x="2319.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node24" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2079.5404" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2079.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge33" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2096.0354,-264.4046C2088.2902,-258.8184 2080.8173,-251.6634 2076.5404,-243 2073.1392,-236.1106 2072.3833,-228.0442 2072.8719,-220.3861"/>
<polygon fill="#000000" stroke="#000000" points="2076.3588,-220.7132 2074.178,-210.3452 2069.4172,-219.8102 2076.3588,-220.7132"/>
<text text-anchor="middle" x="2113.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_admin -->
<g id="node10" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="122.5404" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="122.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge19" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M126.0073,-86.9472C129.2412,-75.4358 135.3261,-61.3463 146.5404,-54 172.0595,-37.2828 1121.3226,-22.0351 1344.091,-18.6821"/>
<polygon fill="#000000" stroke="#000000" points="1344.1969,-22.181 1354.1433,-18.5315 1344.0919,-15.1818 1344.1969,-22.181"/>
<text text-anchor="middle" x="203.0404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- radiology_file -->
<g id="node11" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1987.5404" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1987.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1936.0541,-266.1404C1877.0347,-251.4347 1787.3707,-229.2161 1779.5404,-228 1693.1746,-214.5873 1444.4728,-201.3384 1320.5297,-195.3361"/>
<polygon fill="#000000" stroke="#000000" points="1320.5356,-191.8324 1310.3788,-194.8472 1320.1988,-198.8243 1320.5356,-191.8324"/>
<text text-anchor="middle" x="1899.5404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- publication -->
<g id="node12" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="273.5404" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="273.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge3" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M265.5654,-87.1265C262.0056,-76.1357 260.2469,-62.5639 268.5404,-54 287.54,-34.381 1133.9383,-21.5128 1343.8243,-18.6198"/>
<polygon fill="#000000" stroke="#000000" points="1343.9517,-22.1185 1353.9028,-18.4818 1343.8558,-15.1191 1343.9517,-22.1185"/>
<text text-anchor="middle" x="319.5404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- genetic_analysis -->
<g id="node13" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="1435.5404" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="1435.5404" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1444.7099,-347.81C1457.9149,-318.7373 1477.6803,-261.6573 1448.5404,-228 1431.9321,-208.8171 1370.8464,-199.8256 1320.5082,-195.6291"/>
<polygon fill="#000000" stroke="#000000" points="1320.518,-192.1193 1310.2754,-194.8283 1319.9718,-199.0979 1320.518,-192.1193"/>
<text text-anchor="middle" x="1533.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1465.188,-349.0534C1487.7867,-337.0929 1520.1029,-321.9998 1550.5404,-315 1663.0073,-289.1356 1955.9654,-317.4572 2069.5404,-297 2073.4762,-296.2911 2077.5171,-295.3565 2081.5315,-294.2853"/>
<polygon fill="#000000" stroke="#000000" points="2082.7728,-297.5686 2091.3808,-291.3918 2080.7997,-290.8524 2082.7728,-297.5686"/>
<text text-anchor="middle" x="1620.5404" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- generic_file -->
<g id="node14" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="762.5404" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="762.5404" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M762.2206,-347.9772C762.8344,-324.5222 767.5929,-283.8435 791.5404,-261 819.1138,-234.6978 1057.4037,-209.4369 1178.5053,-198.1547"/>
<polygon fill="#000000" stroke="#000000" points="1179.152,-201.61 1188.7874,-197.2042 1178.5076,-194.6397 1179.152,-201.61"/>
<text text-anchor="middle" x="844.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M826.4456,-361.8417C922.8132,-355.3025 1100.7406,-342.11 1163.5404,-330 1186.3214,-325.607 1190.6223,-318.6102 1213.5404,-315 1401.4871,-285.3937 1882.0637,-329.4496 2069.5404,-297 2073.4809,-296.3179 2077.5251,-295.4017 2081.5416,-294.3424"/>
<polygon fill="#000000" stroke="#000000" points="2082.7754,-297.6284 2091.3939,-291.4663 2080.8138,-290.9088 2082.7754,-297.6284"/>
<text text-anchor="middle" x="1266.5404" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge14" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M697.1621,-364.0873C537.3925,-358.7415 137.2526,-341.0459 97.5404,-297 86.8264,-285.1168 87.3248,-273.3143 97.5404,-261 179.9088,-161.7097 1123.9347,-48.4124 1344.6072,-23.1623"/>
<polygon fill="#000000" stroke="#000000" points="1345.3211,-26.6036 1354.8601,-21.993 1344.5279,-19.6487 1345.3211,-26.6036"/>
<text text-anchor="middle" x="396.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- pathology_file -->
<g id="node15" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2246.5404" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2246.5404" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2241.0465,-347.8344C2236.9455,-337.0093 2230.3392,-323.7226 2220.5404,-315 2207.4295,-303.3291 2190.1944,-295.3227 2173.894,-289.8837"/>
<polygon fill="#000000" stroke="#000000" points="2174.4975,-286.4079 2163.9106,-286.8192 2172.4433,-293.0997 2174.4975,-286.4079"/>
<text text-anchor="middle" x="2292.5404" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge37" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2396.5562,-208.5577C2387.9233,-220.1593 2374.8267,-234.973 2359.5404,-243 2328.7548,-259.1658 2236.9391,-269.6059 2177.3222,-274.8811"/>
<polygon fill="#000000" stroke="#000000" points="2176.9787,-271.3976 2167.3168,-275.7448 2177.5808,-278.3717 2176.9787,-271.3976"/>
<text text-anchor="middle" x="2402.5404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge36" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2379.4875,-190.1017C2258.6757,-181.8003 1786.1044,-147.9903 1724.5404,-123 1678.8128,-104.4381 1682.8481,-73.5644 1637.5404,-54 1602.3763,-38.8158 1498.0009,-27.4361 1436.7648,-21.8469"/>
<polygon fill="#000000" stroke="#000000" points="1436.8644,-18.3419 1426.592,-20.9354 1436.2397,-25.3139 1436.8644,-18.3419"/>
<text text-anchor="middle" x="1748.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge4" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1243.8316,-86.6546C1242.2431,-76.0329 1242.3893,-63.0223 1249.5404,-54 1261.4104,-39.0239 1308.4882,-29.1764 1345.0185,-23.6257"/>
<polygon fill="#000000" stroke="#000000" points="1345.612,-27.0763 1355.0041,-22.1734 1344.6045,-20.1492 1345.612,-27.0763"/>
<text text-anchor="middle" x="1313.0404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- survival -->
<g id="node18" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1059.5404" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1059.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1071.9041,-261.4246C1080.6399,-250.2686 1093.2966,-236.4 1107.5404,-228 1129.8231,-214.8592 1156.8376,-206.4711 1181.2341,-201.136"/>
<polygon fill="#000000" stroke="#000000" points="1182.0579,-204.54 1191.1497,-199.1003 1180.6501,-197.683 1182.0579,-204.54"/>
<text text-anchor="middle" x="1147.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- study_personnel -->
<g id="node19" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="1576.5404" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1576.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge12" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1541.1174,-88.4312C1508.2124,-73.0401 1459.4532,-50.2334 1426.4067,-34.7762"/>
<polygon fill="#000000" stroke="#000000" points="1427.6511,-31.4943 1417.1101,-30.4278 1424.6853,-37.835 1427.6511,-31.4943"/>
<text text-anchor="middle" x="1564.0404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- synonym -->
<g id="node20" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2643.5404" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2643.5404" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2643.0431,-347.5809C2641.7611,-336.6604 2638.3131,-323.3624 2629.5404,-315 2621.5257,-307.3602 2251.5221,-229.4151 2240.5404,-228 2062.7573,-205.0912 1518.8601,-195.6422 1321.2599,-192.9053"/>
<polygon fill="#000000" stroke="#000000" points="1321.0367,-189.402 1310.9898,-192.7648 1320.9409,-196.4014 1321.0367,-189.402"/>
<text text-anchor="middle" x="2602.0404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge30" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2604.7605,-353.8249C2586.1968,-347.5134 2563.8578,-339.203 2544.5404,-330 2532.8424,-324.427 2531.8583,-319.0211 2519.5404,-315 2457.4724,-294.7381 2270.9221,-284.7642 2177.7376,-280.9371"/>
<polygon fill="#000000" stroke="#000000" points="2177.7955,-277.4367 2167.663,-280.5324 2177.5145,-284.4311 2177.7955,-277.4367"/>
<text text-anchor="middle" x="2587.0404" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge29" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2651.865,-348.1C2659.1375,-330.8051 2668.5404,-303.6732 2668.5404,-279 2668.5404,-279 2668.5404,-279 2668.5404,-105 2668.5404,-41.9969 1666.8571,-22.3598 1437.109,-18.6844"/>
<polygon fill="#000000" stroke="#000000" points="1437.1232,-15.1843 1427.0692,-18.5261 1437.0128,-22.1834 1437.1232,-15.1843"/>
<text text-anchor="middle" x="2711.0404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- medical_history -->
<g id="node21" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1344.5404" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1344.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1327.1102,-261.1287C1317.1878,-251.1543 1304.4055,-238.6335 1292.5404,-228 1288.02,-223.9489 1283.1322,-219.7666 1278.3144,-215.7499"/>
<polygon fill="#000000" stroke="#000000" points="1280.2961,-212.8481 1270.3496,-209.1988 1275.8495,-218.2543 1280.2961,-212.8481"/>
<text text-anchor="middle" x="1376.5404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- study_arm -->
<g id="node22" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1841.5404" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1841.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge17" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1813.0284,-88.9098C1790.9477,-77.2277 1759.2201,-62.104 1729.5404,-54 1675.5817,-39.2668 1516.5003,-26.6647 1436.9427,-21.0784"/>
<polygon fill="#000000" stroke="#000000" points="1436.9428,-17.5701 1426.7244,-20.3688 1436.4578,-24.5532 1436.9428,-17.5701"/>
<text text-anchor="middle" x="1819.0404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- diagnosis -->
<g id="node23" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1105.5404" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1105.5404" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1051.8035,-362.4502C1003.2047,-358.0729 936.5804,-348.773 918.5404,-330 897.236,-307.83 894.1153,-284.8338 913.5404,-261 946.108,-221.0407 1088.5955,-203.545 1176.9214,-196.4229"/>
<polygon fill="#000000" stroke="#000000" points="1177.4506,-199.8924 1187.148,-195.625 1176.906,-192.9136 1177.4506,-199.8924"/>
<text text-anchor="middle" x="958.0404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1154.3331,-357.7683C1238.1333,-343.6557 1401.7029,-316.23 1414.5404,-315 1559.487,-301.1119 1926.144,-322.2964 2069.5404,-297 2073.4787,-296.3052 2077.5214,-295.3803 2081.5369,-294.3154"/>
<polygon fill="#000000" stroke="#000000" points="2082.7742,-297.6001 2091.3878,-291.4311 2080.8072,-290.8822 2082.7742,-297.6001"/>
<text text-anchor="middle" x="1459.0404" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2120.0465,-202.319C2133.0144,-207.7452 2145.9634,-215.8879 2153.5404,-228 2158.99,-236.7115 2155.6003,-246.4019 2149.4471,-254.976"/>
<polygon fill="#000000" stroke="#000000" points="2146.6417,-252.8744 2142.8991,-262.7862 2152.0059,-257.3717 2146.6417,-252.8744"/>
<text text-anchor="middle" x="2196.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge9" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2030.0768,-190.5725C1880.9856,-185.7836 1443.489,-167.9863 1399.5404,-123 1380.0501,-103.0496 1380.5804,-69.6272 1384.1989,-45.8514"/>
<polygon fill="#000000" stroke="#000000" points="1387.6448,-46.4639 1385.9533,-36.0049 1380.7534,-45.2359 1387.6448,-46.4639"/>
<text text-anchor="middle" x="1440.0404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cytogenomic_file -->
<g id="node25" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1813.5404" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1813.5404" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1832.3947,-348.1843C1845.8382,-336.6207 1864.9386,-322.3771 1884.5404,-315 1961.8567,-285.9023 1988.7339,-314.1702 2069.5404,-297 2073.3465,-296.1913 2077.2592,-295.2055 2081.1558,-294.1162"/>
<polygon fill="#000000" stroke="#000000" points="2082.1682,-297.4667 2090.7384,-291.2375 2080.1542,-290.7627 2082.1682,-297.4667"/>
<text text-anchor="middle" x="1956.0404" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- study_funding -->
<g id="node26" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2773.5404" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2773.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge28" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2750.2231,-87.738C2732.6175,-75.7863 2707.3302,-60.8432 2682.5404,-54 2621.4581,-37.1384 1662.0184,-22.0012 1437.3492,-18.6761"/>
<polygon fill="#000000" stroke="#000000" points="1437.2631,-15.1746 1427.2126,-18.5268 1437.1599,-22.1738 1437.2631,-15.1746"/>
<text text-anchor="middle" x="2778.5404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- exposure -->
<g id="node27" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1676.5404" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1676.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1634.7478,-267.6763C1626.4034,-265.4424 1617.6977,-263.131 1609.5404,-261 1551.8656,-245.9332 1537.9434,-239.9361 1479.5404,-228 1424.7095,-216.794 1361.931,-207.2158 1315.6723,-200.7627"/>
<polygon fill="#000000" stroke="#000000" points="1316.1512,-197.2957 1305.7661,-199.3933 1315.1926,-204.2297 1316.1512,-197.2957"/>
<text text-anchor="middle" x="1586.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
</g>
</svg>
</div>
