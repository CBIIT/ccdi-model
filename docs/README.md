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
<svg width="3462pt" height="392pt"
 viewBox="0.00 0.00 3462.04 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3458.0444,-388 3458.0444,4 -4,4"/>
<!-- consent_group -->
<g id="node1" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1693" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1693" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- study -->
<g id="node13" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2450" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2450" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge38" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1742.029,-90.7625C1784.9036,-78.915 1849.0446,-62.6398 1906,-54 2001.3983,-39.5287 2289.8972,-25.2734 2403.4056,-20.0692"/>
<polygon fill="#000000" stroke="#000000" points="2403.6832,-23.5602 2413.5134,-19.6085 2403.3644,-16.5675 2403.6832,-23.5602"/>
<text text-anchor="middle" x="1969.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- generic_file -->
<g id="node2" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="532" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="532" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- participant -->
<g id="node3" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1140" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1140" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M527.5005,-347.7531C522.9429,-324.4318 519.3035,-284.2966 541,-261 576.3933,-222.9965 916.8368,-202.4504 1068.1396,-195.1324"/>
<polygon fill="#000000" stroke="#000000" points="1068.4419,-198.622 1078.2635,-194.6488 1068.1079,-191.63 1068.4419,-198.622"/>
<text text-anchor="middle" x="594" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge8" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M467.8284,-362.1203C326.3326,-352.7067 0,-325.911 0,-279 0,-279 0,-279 0,-105 0,-42.486 2064.6512,-21.4309 2403.2747,-18.398"/>
<polygon fill="#000000" stroke="#000000" points="2403.4967,-21.8963 2413.4652,-18.3076 2403.4345,-14.8966 2403.4967,-21.8963"/>
<text text-anchor="middle" x="53" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- sample -->
<g id="node17" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2285" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2285" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M596.4154,-362.2577C755.937,-353.0938 1182.1915,-329.2413 1538,-315 1810.3438,-304.0994 1879.3416,-319.1735 2151,-297 2178.4503,-294.7594 2208.8873,-290.7914 2233.8067,-287.1502"/>
<polygon fill="#000000" stroke="#000000" points="2234.3935,-290.6015 2243.7702,-285.6691 2233.3642,-283.6776 2234.3935,-290.6015"/>
<text text-anchor="middle" x="1591" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge22" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1194.7911,-183.3801C1294.2414,-167.7342 1504.5936,-134.6408 1617.5396,-116.8717"/>
<polygon fill="#000000" stroke="#000000" points="1618.1597,-120.3173 1627.4942,-115.3056 1617.0718,-113.4023 1618.1597,-120.3173"/>
<text text-anchor="middle" x="1500.5" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- radiology_file -->
<g id="node4" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="423" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="423" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M411.9559,-260.7908C406.9392,-249.9493 403.7571,-236.6606 412,-228 434.3446,-204.5232 887.2841,-195.5652 1067.2249,-192.9244"/>
<polygon fill="#000000" stroke="#000000" points="1067.442,-196.4217 1077.3905,-192.7776 1067.341,-189.4224 1067.442,-196.4217"/>
<text text-anchor="middle" x="471" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- family_relationship -->
<g id="node5" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="880" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="880" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M874.1175,-260.8977C871.8254,-250.0965 871.3195,-236.8125 879,-228 891.3962,-213.7766 996.2252,-202.9336 1069.1938,-197.0217"/>
<polygon fill="#000000" stroke="#000000" points="1069.5747,-200.5026 1079.2655,-196.2204 1069.0194,-193.5246 1069.5747,-200.5026"/>
<text text-anchor="middle" x="958.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- sequencing_file -->
<g id="node6" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2236" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="2236" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2242.5436,-348.0342C2246.4816,-338.0303 2251.9063,-325.5114 2258,-315 2260.0142,-311.5255 2262.3083,-307.9948 2264.6885,-304.5705"/>
<polygon fill="#000000" stroke="#000000" points="2267.6048,-306.5116 2270.6724,-296.3706 2261.9503,-302.3852 2267.6048,-306.5116"/>
<text text-anchor="middle" x="2324.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- pathology_file -->
<g id="node7" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2413" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2413" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge34" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2409.0983,-347.772C2405.9094,-336.9235 2400.3525,-323.634 2391,-315 2376.0425,-301.1916 2355.5799,-292.6561 2336.6211,-287.3903"/>
<polygon fill="#000000" stroke="#000000" points="2337.4342,-283.9858 2326.881,-284.924 2335.7159,-290.7716 2337.4342,-283.9858"/>
<text text-anchor="middle" x="2463" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- survival -->
<g id="node8" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1046" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1046" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1041.6916,-260.9528C1040.245,-250.4369 1040.3998,-237.4328 1047,-228 1052.0459,-220.7887 1067.7529,-213.627 1084.8569,-207.613"/>
<polygon fill="#000000" stroke="#000000" points="1086.0764,-210.8957 1094.444,-204.397 1083.8501,-204.2591 1086.0764,-210.8957"/>
<text text-anchor="middle" x="1086.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- genetic_analysis -->
<g id="node9" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="1548" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="1548" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge40" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1519.3003,-348.8855C1511.5235,-343.4458 1503.474,-337.0034 1497,-330 1459.1583,-289.064 1473.8671,-252.9203 1424,-228 1387.9292,-209.9742 1283.4795,-200.336 1211.8296,-195.6947"/>
<polygon fill="#000000" stroke="#000000" points="1211.7082,-192.1802 1201.5083,-195.0457 1211.2689,-199.1664 1211.7082,-192.1802"/>
<text text-anchor="middle" x="1545" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge39" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1620.5402,-355.8474C1661.6831,-349.5492 1713.9874,-340.6343 1760,-330 1783.0199,-324.6797 1787.7117,-318.9849 1811,-315 1960.1549,-289.4777 2000.3342,-311.0844 2151,-297 2178.3194,-294.4462 2208.6288,-290.4716 2233.5015,-286.9062"/>
<polygon fill="#000000" stroke="#000000" points="2234.0578,-290.3622 2243.4506,-285.4606 2233.0512,-283.4349 2234.0578,-290.3622"/>
<text text-anchor="middle" x="1881" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- study_funding -->
<g id="node10" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2042" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2042" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge6" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2036.8615,-86.7091C2035.0059,-75.8369 2035.0225,-62.5446 2043,-54 2067.1662,-28.116 2301.2596,-20.7086 2403.0851,-18.7022"/>
<polygon fill="#000000" stroke="#000000" points="2403.451,-22.196 2413.3835,-18.5088 2403.3196,-15.1972 2403.451,-22.196"/>
<text text-anchor="middle" x="2105" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- treatment_response -->
<g id="node11" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1342" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1342" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1303.0524,-262.2255C1269.0992,-247.6021 1219.8708,-226.3998 1184.3986,-211.1222"/>
<polygon fill="#000000" stroke="#000000" points="1185.3514,-207.7218 1174.7825,-206.9806 1182.5824,-214.1508 1185.3514,-207.7218"/>
<text text-anchor="middle" x="1337" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- synonym -->
<g id="node12" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2083" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2083" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2085.8413,-347.7041C2086.4414,-336.8301 2085.0993,-323.5375 2077,-315 1915.427,-144.6848 1789.0001,-256.706 1556,-228 1435.3047,-213.1301 1294.159,-202.2899 1211.1912,-196.5833"/>
<polygon fill="#000000" stroke="#000000" points="1211.334,-193.085 1201.119,-195.8961 1210.8575,-200.0688 1211.334,-193.085"/>
<text text-anchor="middle" x="2098.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge16" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2099.7326,-348.7747C2115.653,-332.1429 2138.1624,-307.9196 2145,-297 2158.7537,-275.0355 2159.3992,-267.7756 2167,-243 2187.785,-175.249 2153.8944,-140.8191 2200,-87 2226.4848,-56.0843 2340.2878,-34.417 2404.84,-24.3576"/>
<polygon fill="#000000" stroke="#000000" points="2405.3995,-27.8129 2414.7564,-22.8432 2404.3426,-20.8931 2405.3995,-27.8129"/>
<text text-anchor="middle" x="2217.5" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2104.8223,-349.4551C2120.157,-338.4587 2141.5129,-324.3708 2162,-315 2185.442,-304.2776 2212.8579,-295.8871 2235.8497,-289.9138"/>
<polygon fill="#000000" stroke="#000000" points="2236.8977,-293.2592 2245.7389,-287.4211 2235.1867,-286.4715 2236.8977,-293.2592"/>
<text text-anchor="middle" x="2204.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study_personnel -->
<g id="node14" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2296" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2296" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge24" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2291.2296,-86.6052C2289.6192,-75.966 2289.764,-62.9544 2297,-54 2310.3322,-37.5017 2363.8983,-27.765 2403.9138,-22.6621"/>
<polygon fill="#000000" stroke="#000000" points="2404.5158,-26.1147 2414.0203,-21.4334 2403.6709,-19.1659 2404.5158,-26.1147"/>
<text text-anchor="middle" x="2366.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- cytogenomic_file -->
<g id="node15" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="2597" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="2597" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2578.3594,-348.2365C2565.2963,-336.8507 2546.8614,-322.7926 2528,-315 2494.6982,-301.2413 2399.4895,-289.9613 2338.6068,-283.8822"/>
<polygon fill="#000000" stroke="#000000" points="2338.698,-280.3744 2328.4037,-282.8799 2338.0135,-287.3409 2338.698,-280.3744"/>
<text text-anchor="middle" x="2625.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- diagnosis -->
<g id="node16" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1259" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1259" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1217.4942,-354.1656C1189.9123,-343.8999 1155.7878,-326.0182 1139,-297 1125.5238,-273.706 1127.9221,-242.3622 1132.3681,-219.9981"/>
<polygon fill="#000000" stroke="#000000" points="1135.8112,-220.6389 1134.5796,-210.1159 1128.9801,-219.1101 1135.8112,-220.6389"/>
<text text-anchor="middle" x="1183.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1311.5591,-361.0389C1350.1444,-357.405 1403.8282,-352.3662 1451,-348 1494.773,-343.9484 1607.1709,-346.2936 1648,-330 1657.9926,-326.0123 1656.9035,-318.7168 1667,-315 1717.5017,-296.409 2097.3809,-301.5876 2151,-297 2178.4414,-294.6521 2208.8776,-290.6752 2233.7988,-287.0557"/>
<polygon fill="#000000" stroke="#000000" points="2234.3813,-290.5078 2243.7632,-285.5853 2233.3593,-283.5828 2234.3813,-290.5078"/>
<text text-anchor="middle" x="1711.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2249.4344,-268.2634C2207.2966,-256.0726 2134.7588,-236.7446 2071,-228 1905.5781,-205.3121 1401.477,-195.8045 1212.5377,-192.974"/>
<polygon fill="#000000" stroke="#000000" points="1212.4837,-189.4729 1202.433,-192.8245 1212.3801,-196.4722 1212.4837,-189.4729"/>
<text text-anchor="middle" x="2185.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node20" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2727" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2727" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge32" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2328.7676,-276.0651C2406.3072,-270.5674 2564.6589,-257.9155 2618,-243 2643.6492,-235.8278 2670.7817,-223.1526 2691.5603,-212.2332"/>
<polygon fill="#000000" stroke="#000000" points="2693.475,-215.1779 2700.6319,-207.3658 2690.1654,-209.0097 2693.475,-215.1779"/>
<text text-anchor="middle" x="2694.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node25" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2356" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2356" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge31" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2310.3408,-264.2139C2318.6899,-258.4134 2327.4923,-251.177 2334,-243 2339.5497,-236.0268 2343.9597,-227.4413 2347.3296,-219.3166"/>
<polygon fill="#000000" stroke="#000000" points="2350.6745,-220.3658 2350.9309,-209.7741 2344.1254,-217.8941 2350.6745,-220.3658"/>
<text text-anchor="middle" x="2379.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- medical_history -->
<g id="node18" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="113" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="113" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M121.8413,-260.9743C128.6202,-249.317 139.1627,-235.0476 153,-228 193.5622,-207.3408 846.1206,-196.1828 1067.3282,-192.98"/>
<polygon fill="#000000" stroke="#000000" points="1067.583,-196.4768 1077.5317,-192.8335 1067.4824,-189.4776 1067.583,-196.4768"/>
<text text-anchor="middle" x="221" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- treatment -->
<g id="node19" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="274" cy="-279" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="274" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M281.1928,-261.063C286.8819,-249.4453 296.0399,-235.1868 309,-228 341.8588,-209.7787 870.6681,-197.3884 1067.2013,-193.3932"/>
<polygon fill="#000000" stroke="#000000" points="1067.4996,-196.888 1077.4269,-193.1868 1067.3583,-189.8894 1067.4996,-196.888"/>
<text text-anchor="middle" x="356" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge1" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2684.7813,-182.4434C2645.5881,-172.1806 2586.8553,-153.1546 2543,-123 2511.685,-101.468 2483.9883,-67.1669 2467.1362,-43.6674"/>
<polygon fill="#000000" stroke="#000000" points="2469.8317,-41.4154 2461.2234,-35.2389 2464.1012,-45.4355 2469.8317,-41.4154"/>
<text text-anchor="middle" x="2583.5" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2683.5205,-200.5582C2601.0112,-216.7987 2422.1921,-251.9961 2334.9273,-269.1727"/>
<polygon fill="#000000" stroke="#000000" points="2334.1399,-265.7604 2325.0041,-271.1259 2335.4918,-272.6286 2334.1399,-265.7604"/>
<text text-anchor="middle" x="2573.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- clinical_measure_file -->
<g id="node21" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="3117" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="3117" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3116.8361,-347.7709C3115.7109,-336.6382 3112.3115,-323.0419 3103,-315 3078.0926,-293.4888 2988.6541,-301.101 2956,-297 2717.6841,-267.0702 2659.4564,-246.733 2420,-228 2182.7778,-209.4418 1447.2683,-196.748 1212.6824,-193.0875"/>
<polygon fill="#000000" stroke="#000000" points="1212.6088,-189.586 1202.5556,-192.9302 1212.5001,-196.5852 1212.6088,-189.586"/>
<text text-anchor="middle" x="3042" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge27" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3125.4639,-347.7683C3132.7166,-330.4595 3142,-303.516 3142,-279 3142,-279 3142,-279 3142,-105 3142,-39.8253 2652.5298,-22.7406 2496.905,-18.9557"/>
<polygon fill="#000000" stroke="#000000" points="2496.7961,-15.4522 2486.7163,-18.7154 2496.631,-22.4503 2496.7961,-15.4522"/>
<text text-anchor="middle" x="3228" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge29" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3026.9932,-355.7704C2995.8392,-350.3665 2961.184,-342.2152 2931,-330 2919.6872,-325.4218 2919.5929,-318.8136 2908,-315 2854.8496,-297.5155 2481.7969,-284.8071 2339.7452,-280.5521"/>
<polygon fill="#000000" stroke="#000000" points="2339.6228,-277.047 2329.5233,-280.2485 2339.4149,-284.0439 2339.6228,-277.047"/>
<text text-anchor="middle" x="3017" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- study_arm -->
<g id="node22" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2693" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2693" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge12" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2654.4959,-91.2146C2609.2376,-75.011 2534.5487,-48.2705 2489.0537,-31.9822"/>
<polygon fill="#000000" stroke="#000000" points="2490.1283,-28.6494 2479.5337,-28.5738 2487.7688,-35.2398 2490.1283,-28.6494"/>
<text text-anchor="middle" x="2634.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- methylation_array_file -->
<g id="node23" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2820" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2820" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge35" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2771.3755,-349.6652C2756.2505,-344.032 2739.6949,-337.2881 2725,-330 2713.7312,-324.4111 2712.9303,-318.9862 2701,-315 2635.4077,-293.0841 2436.5089,-283.839 2339.4464,-280.5513"/>
<polygon fill="#000000" stroke="#000000" points="2339.3633,-277.0468 2329.2534,-280.2153 2339.1326,-284.043 2339.3633,-277.0468"/>
<text text-anchor="middle" x="2816.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- exposure -->
<g id="node24" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="709" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="709" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M727.5847,-261.9587C741.4911,-250.2791 761.5605,-235.5773 782,-228 832.7577,-209.1831 978.8837,-199.3441 1067.9772,-194.9515"/>
<polygon fill="#000000" stroke="#000000" points="1068.1953,-198.4451 1078.0152,-194.4677 1067.8582,-191.4532 1068.1953,-198.4451"/>
<text text-anchor="middle" x="825.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge36" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2368.8739,-175.8391C2386.3514,-153.1826 2417.5208,-110.1274 2436,-69 2439.2968,-61.6626 2441.9768,-53.3743 2444.076,-45.6452"/>
<polygon fill="#000000" stroke="#000000" points="2447.4739,-46.4842 2446.5041,-35.9338 2440.6829,-44.7862 2447.4739,-46.4842"/>
<text text-anchor="middle" x="2451" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge37" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2329.2569,-197.4564C2312.5454,-202.3969 2292.3047,-211.5275 2282,-228 2277.8135,-234.6922 2276.9006,-242.8954 2277.491,-250.75"/>
<polygon fill="#000000" stroke="#000000" points="2274.0413,-251.3475 2278.9843,-260.7186 2280.9641,-250.3104 2274.0413,-251.3475"/>
<text text-anchor="middle" x="2306" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study_admin -->
<g id="node26" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="3240" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="3240" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge14" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3218.2964,-87.6515C3202.1403,-75.8232 3178.9933,-61.0699 3156,-54 3093.3504,-34.7368 2643.6483,-22.5546 2496.4822,-19.0493"/>
<polygon fill="#000000" stroke="#000000" points="2496.4983,-15.5488 2486.4185,-18.8119 2496.3332,-22.5468 2496.4983,-15.5488"/>
<text text-anchor="middle" x="3243.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- publication -->
<g id="node27" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="3391" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="3391" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge23" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3369.1506,-88.0929C3352.35,-76.1525 3328.0183,-61.0674 3304,-54 3226.5617,-31.2138 2663.8365,-21.1551 2496.6908,-18.6494"/>
<polygon fill="#000000" stroke="#000000" points="2496.542,-15.1469 2486.4913,-18.4985 2496.4384,-22.1461 2496.542,-15.1469"/>
<text text-anchor="middle" x="3387" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- laboratory_test -->
<g id="node28" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1866" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1866" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1789.6347,-359.2791C1689.6507,-350.299 1526.4523,-334.9426 1522,-330 1517.538,-325.0467 1517.7376,-320.1261 1522,-315 1550.0338,-281.2854 1590.9662,-330.7146 1619,-297 1629.2297,-284.6974 1629.1788,-273.3447 1619,-261 1593.4024,-229.9556 1337.9033,-206.7359 1210.9019,-197.0136"/>
<polygon fill="#000000" stroke="#000000" points="1211.1096,-193.5194 1200.8736,-196.2535 1210.5805,-200.4993 1211.1096,-193.5194"/>
<text text-anchor="middle" x="1692.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1901.6322,-349.6889C1928.2017,-338.2099 1965.6764,-323.4417 2000,-315 2065.6305,-298.8586 2083.9503,-305.4992 2151,-297 2178.1183,-293.5625 2208.2937,-289.5276 2233.1331,-286.1502"/>
<polygon fill="#000000" stroke="#000000" points="2233.6387,-289.6137 2243.0742,-284.7949 2232.693,-282.6779 2233.6387,-289.6137"/>
<text text-anchor="middle" x="2065.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
</g>
</svg>
</div>
