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
<svg width="3770pt" height="392pt"
 viewBox="0.00 0.00 3769.84 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3765.8436,-388 3765.8436,4 -4,4"/>
<!-- sequencing_file -->
<g id="node1" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="355.7514" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="355.7514" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sample -->
<g id="node3" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1354.7514" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1354.7514" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M416.0043,-353.4891C426.5595,-351.5042 437.4568,-349.5861 447.7514,-348 576.8321,-328.1118 609.4898,-324.4501 739.7514,-315 863.2691,-306.0391 1174.6239,-317.5384 1296.7514,-297 1301.5666,-296.1902 1306.5378,-295.0843 1311.4509,-293.816"/>
<polygon fill="#000000" stroke="#000000" points="1312.7039,-297.0996 1321.3858,-291.0271 1310.8119,-290.3601 1312.7039,-297.0996"/>
<text text-anchor="middle" x="806.2514" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- cell_line -->
<g id="node11" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="1446.7514" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="1446.7514" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge8" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M360.0389,-347.8446C366.8549,-323.4451 382.6911,-280.8491 413.7514,-261 434.4155,-247.7946 1170.9888,-206.9369 1387.4852,-195.1894"/>
<polygon fill="#000000" stroke="#000000" points="1387.9022,-198.672 1397.6981,-194.6359 1387.5233,-191.6822 1387.9022,-198.672"/>
<text text-anchor="middle" x="480.2514" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- pdx -->
<g id="node20" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1028.7514" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1028.7514" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge9" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M274.754,-361.5076C182.6977,-354.5105 40.879,-337.3409 7.7514,-297 -2.4027,-284.6349 -2.7131,-273.1035 7.7514,-261 40.5231,-223.0955 808.6506,-198.4067 990.4374,-193.0825"/>
<polygon fill="#000000" stroke="#000000" points="990.6986,-196.5764 1000.5927,-192.7874 990.4952,-189.5794 990.6986,-196.5764"/>
<text text-anchor="middle" x="74.2514" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- study -->
<g id="node2" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="3023.7514" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="3023.7514" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- participant -->
<g id="node10" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="2304.7514" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="2304.7514" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1386.0338,-266.2169C1391.8477,-264.2126 1397.9262,-262.3583 1403.7514,-261 1477.3141,-243.8474 1497.9538,-253.5357 1572.7514,-243 1656.7552,-231.1676 1685.4885,-249.1425 1760.7514,-210 1780.8262,-199.5596 1776.6491,-184.3875 1796.7514,-174 1874.4517,-133.8497 1904.1625,-153.3189 1990.7514,-141 2074.6299,-129.0667 2171.5541,-118.4322 2235.2738,-111.871"/>
<polygon fill="#000000" stroke="#000000" points="2236.0076,-115.3142 2245.599,-110.8135 2235.2944,-108.3506 2236.0076,-115.3142"/>
<text text-anchor="middle" x="1833.2514" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge33" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1389.5893,-267.7121C1397.1916,-265.3824 1405.2166,-263.0244 1412.7514,-261 1447.529,-251.6563 1469.2936,-271.1503 1491.7514,-243 1499.7511,-232.9726 1492.8583,-222.2718 1482.2717,-213.2747"/>
<polygon fill="#000000" stroke="#000000" points="1484.154,-210.3097 1474.0703,-207.0586 1479.9257,-215.8884 1484.154,-210.3097"/>
<text text-anchor="middle" x="1532.2514" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge34" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1319.9003,-267.7608C1312.2988,-265.4281 1304.2774,-263.0565 1296.7514,-261 1263.2667,-251.8503 1254.4178,-251.4565 1220.7514,-243 1165.9409,-229.2324 1102.6353,-212.1952 1064.1647,-201.7143"/>
<polygon fill="#000000" stroke="#000000" points="1065.0388,-198.3249 1054.4701,-199.0686 1063.1958,-205.0779 1065.0388,-198.3249"/>
<text text-anchor="middle" x="1257.2514" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- family_relationship -->
<g id="node4" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1978.7514" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1978.7514" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1984.995,-173.9238C1989.9017,-162.5563 1997.9107,-148.6403 2009.7514,-141 2045.3605,-118.0231 2156.7415,-109.7107 2231.9871,-106.7038"/>
<polygon fill="#000000" stroke="#000000" points="2232.4918,-110.1874 2242.3531,-106.3138 2232.2285,-103.1923 2232.4918,-110.1874"/>
<text text-anchor="middle" x="2089.2514" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- publication -->
<g id="node5" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="2773.7514" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="2773.7514" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge35" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2768.7815,-86.8622C2766.9894,-76.0476 2767.0134,-62.7621 2774.7514,-54 2787.9691,-39.0329 2909.3524,-27.0796 2977.6302,-21.4712"/>
<polygon fill="#000000" stroke="#000000" points="2978.0176,-24.9514 2987.7035,-20.6581 2977.4543,-17.9741 2978.0176,-24.9514"/>
<text text-anchor="middle" x="2825.7514" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- radiology_file -->
<g id="node6" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="2170.7514" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="2170.7514" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2170.2619,-173.8568C2170.938,-163.0401 2173.6081,-149.7544 2181.7514,-141 2190.5194,-131.574 2216.4922,-123.3139 2242.3247,-117.0916"/>
<polygon fill="#000000" stroke="#000000" points="2243.2298,-120.4747 2252.1821,-114.8085 2241.6503,-113.6552 2243.2298,-120.4747"/>
<text text-anchor="middle" x="2240.7514" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node7" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="3152.7514" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="3152.7514" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge14" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3151.9812,-173.8121C3150.4736,-162.5487 3146.5606,-148.7922 3136.7514,-141 3095.3939,-108.1468 2935.6575,-161.7366 2899.7514,-123 2866.2024,-86.8064 2936.4177,-51.0444 2984.2428,-32.0271"/>
<polygon fill="#000000" stroke="#000000" points="2985.7049,-35.2143 2993.7672,-28.3404 2983.178,-28.6862 2985.7049,-35.2143"/>
<text text-anchor="middle" x="2985.7514" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3072.5568,-179.8046C3030.7418,-172.8184 2984.3204,-163.8968 2964.7514,-156 2953.4341,-151.4331 2953.3467,-144.8063 2941.7514,-141 2915.3304,-132.327 2538.2977,-115.1048 2377.0478,-108.0858"/>
<polygon fill="#000000" stroke="#000000" points="2376.887,-104.5756 2366.7446,-107.6385 2376.5833,-111.5691 2376.887,-104.5756"/>
<text text-anchor="middle" x="3050.7514" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- study_funding -->
<g id="node8" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="3157.7514" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="3157.7514" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge2" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3131.5967,-88.019C3109.4446,-73.6367 3077.6596,-53.0001 3054.3338,-37.8558"/>
<polygon fill="#000000" stroke="#000000" points="3056.1391,-34.8549 3045.8459,-32.3449 3052.3273,-40.726 3056.1391,-34.8549"/>
<text text-anchor="middle" x="3160.7514" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- study_admin -->
<g id="node9" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="3323.7514" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="3323.7514" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge42" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3297.167,-88.1457C3278.2193,-76.8639 3251.7725,-62.5643 3226.7514,-54 3174.6164,-36.1551 3111.7709,-26.7536 3069.9519,-22.0939"/>
<polygon fill="#000000" stroke="#000000" points="3070.1074,-18.5907 3059.7923,-21.0092 3069.3642,-25.5512 3070.1074,-18.5907"/>
<text text-anchor="middle" x="3316.2514" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge1" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2359.8526,-96.4153C2430.0691,-85.645 2555.24,-67.0128 2662.7514,-54 2775.7539,-40.3226 2909.1174,-28.0152 2977.7782,-21.9598"/>
<polygon fill="#000000" stroke="#000000" points="2978.1737,-25.4387 2987.8292,-21.0774 2977.5614,-18.4655 2978.1737,-25.4387"/>
<text text-anchor="middle" x="2713.2514" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge30" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1451.1307,-173.8443C1454.8841,-162.4431 1461.52,-148.5196 1472.7514,-141 1672.2749,-7.4164 2310.3723,-72.7587 2549.7514,-54 2706.5309,-41.7141 2892.5337,-27.7723 2977.3918,-21.4467"/>
<polygon fill="#000000" stroke="#000000" points="2977.7602,-24.9291 2987.4725,-20.6957 2977.2401,-17.9484 2977.7602,-24.9291"/>
<text text-anchor="middle" x="1657.2514" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge29" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1428.7534,-209.0198C1414.9006,-222.1198 1395.5788,-240.3915 1380.1523,-254.9796"/>
<polygon fill="#000000" stroke="#000000" points="1377.3509,-252.8116 1372.4899,-262.2255 1382.1605,-257.8976 1377.3509,-252.8116"/>
<text text-anchor="middle" x="1447.2514" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1458.7944,-174.429C1467.9603,-162.658 1481.709,-148.0679 1497.7514,-141 1531.0288,-126.3388 2040.2257,-111.8008 2232.2305,-106.8124"/>
<polygon fill="#000000" stroke="#000000" points="2232.5953,-110.3042 2242.5014,-106.5468 2232.4143,-103.3066 2232.5953,-110.3042"/>
<text text-anchor="middle" x="1538.2514" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cytogenomic_file -->
<g id="node12" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1130.7514" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1130.7514" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1152.364,-348.3828C1167.129,-337.2091 1187.601,-323.3366 1207.7514,-315 1245.0424,-299.572 1257.6519,-306.9936 1296.7514,-297 1301.1805,-295.8679 1305.7731,-294.603 1310.3467,-293.2827"/>
<polygon fill="#000000" stroke="#000000" points="1311.6716,-296.5402 1320.2582,-290.3338 1309.6753,-289.8309 1311.6716,-296.5402"/>
<text text-anchor="middle" x="1279.2514" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;cell_line -->
<g id="edge4" class="edge">
<title>cytogenomic_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1129.1546,-347.5523C1127.6807,-317.5834 1129.6481,-258.5996 1163.7514,-228 1180.1124,-213.3198 1309.8779,-201.6877 1387.8937,-195.9359"/>
<polygon fill="#000000" stroke="#000000" points="1388.3537,-199.4118 1398.0741,-195.197 1387.8469,-192.4302 1388.3537,-199.4118"/>
<text text-anchor="middle" x="1212.2514" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;pdx -->
<g id="edge5" class="edge">
<title>cytogenomic_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1041.0773,-364.3565C927.7253,-361.3325 744.7369,-352.9236 723.7514,-330 693.6118,-297.0768 743.0031,-325.3605 780.7514,-297 810.2183,-274.8613 795.9136,-248.1854 826.7514,-228 853.1712,-210.7064 939.8753,-200.1001 990.6965,-195.2126"/>
<polygon fill="#000000" stroke="#000000" points="991.0261,-198.6972 1000.6579,-194.2836 990.376,-191.7274 991.0261,-198.6972"/>
<text text-anchor="middle" x="875.2514" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- exposure -->
<g id="node13" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="2315.7514" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="2315.7514" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2309.7613,-173.8765C2308.1498,-168.215 2306.6153,-161.9049 2305.7514,-156 2304.6709,-148.6148 2304.1934,-140.5645 2304.0391,-133.0876"/>
<polygon fill="#000000" stroke="#000000" points="2307.539,-133.0171 2304.0068,-123.0284 2300.539,-133.0396 2307.539,-133.0171"/>
<text text-anchor="middle" x="2349.2514" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- medical_history -->
<g id="node14" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2509.7514" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2509.7514" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2479.3751,-175.1424C2468.7072,-169.1615 2456.6636,-162.3411 2445.7514,-156 2434.5479,-149.4897 2432.5793,-146.2916 2420.7514,-141 2402.0658,-132.6405 2380.8708,-125.4442 2361.7566,-119.731"/>
<polygon fill="#000000" stroke="#000000" points="2362.5551,-116.3181 2351.9751,-116.8802 2360.5964,-123.0385 2362.5551,-116.3181"/>
<text text-anchor="middle" x="2513.7514" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- pathology_file -->
<g id="node15" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1354.7514" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1354.7514" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1354.7514,-347.9735C1354.7514,-336.1918 1354.7514,-320.5607 1354.7514,-307.1581"/>
<polygon fill="#000000" stroke="#000000" points="1358.2515,-307.0033 1354.7514,-297.0034 1351.2515,-307.0034 1358.2515,-307.0033"/>
<text text-anchor="middle" x="1415.7514" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge20" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1407.9432,-353.0209C1429.9085,-346.9986 1455.4071,-339.1396 1477.7514,-330 1490.8182,-324.6552 1492.3632,-319.4795 1505.7514,-315 1530.4897,-306.7229 1604.7786,-316.8096 1621.7514,-297 1632.1616,-284.8498 1629.268,-275.1245 1621.7514,-261 1595.1025,-210.9239 1559.2701,-225.668 1504.7514,-210 1501.1985,-208.9789 1497.5308,-207.8999 1493.8464,-206.798"/>
<polygon fill="#000000" stroke="#000000" points="1494.7073,-203.4017 1484.122,-203.8515 1492.6774,-210.101 1494.7073,-203.4017"/>
<text text-anchor="middle" x="1689.7514" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge19" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1290.9267,-356.1076C1256.9261,-350.067 1214.6253,-341.3145 1177.7514,-330 1161.1806,-324.9154 1158.4878,-319.5095 1141.7514,-315 1112.3154,-307.0688 1025.8442,-319.9273 1005.7514,-297 986.5325,-275.0698 999.3444,-240.7918 1012.2453,-217.4101"/>
<polygon fill="#000000" stroke="#000000" points="1015.294,-219.13 1017.3128,-208.7292 1009.2487,-215.6009 1015.294,-219.13"/>
<text text-anchor="middle" x="1066.7514" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- study_arm -->
<g id="node16" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="3471.7514" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="3471.7514" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge28" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3447.5238,-88.5434C3428.99,-76.8329 3402.3469,-61.838 3376.7514,-54 3320.6176,-36.8104 3152.3962,-25.2616 3070.1068,-20.4826"/>
<polygon fill="#000000" stroke="#000000" points="3070.2189,-16.9834 3060.0354,-19.9066 3069.8192,-23.972 3070.2189,-16.9834"/>
<text text-anchor="middle" x="3460.2514" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- molecular_test -->
<g id="node17" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="2692.7514" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="2692.7514" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2650.3828,-176.5531C2635.662,-170.6951 2619.2228,-163.5913 2604.7514,-156 2593.944,-150.3308 2593.2005,-145.2256 2581.7514,-141 2545.0018,-127.4364 2444.3194,-116.655 2375.0324,-110.5459"/>
<polygon fill="#000000" stroke="#000000" points="2375.3143,-107.0573 2365.0489,-109.6787 2374.7085,-114.031 2375.3143,-107.0573"/>
<text text-anchor="middle" x="2668.7514" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- therapeutic_procedure -->
<g id="node18" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="2908.7514" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="2908.7514" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2828.8495,-178.6817C2804.796,-173.2276 2778.7049,-165.8265 2755.7514,-156 2744.5322,-151.197 2744.2933,-144.9651 2732.7514,-141 2669.0232,-119.1068 2481.9566,-110.1832 2377.4642,-106.8284"/>
<polygon fill="#000000" stroke="#000000" points="2377.4121,-103.3252 2367.3078,-106.5115 2377.1938,-110.3218 2377.4121,-103.3252"/>
<text text-anchor="middle" x="2848.7514" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node19" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="594.7514" cy="-366" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="594.7514" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M698.0563,-354.0611C751.4899,-347.5697 817.7181,-339.0332 876.7514,-330 914.2389,-324.2637 923.0785,-319.356 960.7514,-315 1109.3091,-297.8229 1149.5462,-323.3643 1296.7514,-297 1301.5577,-296.1392 1306.5233,-295.0007 1311.4331,-293.7133"/>
<polygon fill="#000000" stroke="#000000" points="1312.6953,-296.9936 1321.3641,-290.9025 1310.7889,-290.2582 1312.6953,-296.9936"/>
<text text-anchor="middle" x="1069.2514" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge25" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M579.2132,-348.0647C561.2148,-325.0803 536.7961,-285.3089 559.7514,-261 583.7445,-235.5921 838.8983,-245.5494 873.7514,-243 1062.2568,-229.2114 1285.2006,-207.9378 1388.6458,-197.7814"/>
<polygon fill="#000000" stroke="#000000" points="1389.2655,-201.2374 1398.8748,-196.7751 1388.5801,-194.2711 1389.2655,-201.2374"/>
<text text-anchor="middle" x="668.2514" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge24" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M494.1821,-353.67C366.9349,-337.5852 162.8577,-309.9701 151.7514,-297 141.3446,-284.8468 140.8904,-272.749 151.7514,-261 180.6633,-229.724 825.26,-200.5563 990.4561,-193.5761"/>
<polygon fill="#000000" stroke="#000000" points="990.7881,-197.0654 1000.6324,-193.1487 990.4943,-190.0715 990.7881,-197.0654"/>
<text text-anchor="middle" x="260.2514" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge16" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1054.696,-184.5188C1121.2613,-165.5758 1303.7651,-115.2214 1458.7514,-87 1578.5567,-65.1847 1609.3119,-63.0377 1730.7514,-54 1980.3255,-35.4264 2775.4547,-21.9058 2976.9755,-18.7189"/>
<polygon fill="#000000" stroke="#000000" points="2977.2724,-22.2147 2987.2161,-18.5577 2977.1622,-15.2156 2977.2724,-22.2147"/>
<text text-anchor="middle" x="1482.7514" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1056.9387,-193.6727C1116.9382,-197.5703 1255.2728,-208.4429 1297.7514,-228 1311.2077,-234.1953 1323.7609,-244.6765 1333.6425,-254.5315"/>
<polygon fill="#000000" stroke="#000000" points="1331.21,-257.0521 1340.6489,-261.8643 1336.2711,-252.2162 1331.21,-257.0521"/>
<text text-anchor="middle" x="1344.7514" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- diagnosis -->
<g id="node21" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1568.7514" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1568.7514" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1573.6758,-173.9481C1577.8307,-162.4371 1585.0251,-148.3478 1596.7514,-141 1623.3537,-124.3307 2057.3978,-111.3621 2232.4294,-106.7859"/>
<polygon fill="#000000" stroke="#000000" points="2232.6701,-110.2809 2242.5759,-106.5224 2232.4884,-103.2833 2232.6701,-110.2809"/>
<text text-anchor="middle" x="1641.2514" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- follow_up -->
<g id="node22" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="1696.7514" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="1696.7514" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1691.109,-173.6813C1688.9855,-162.7986 1688.735,-149.505 1696.7514,-141 1714.8704,-121.7764 2075.2792,-110.6266 2232.4757,-106.661"/>
<polygon fill="#000000" stroke="#000000" points="2232.6208,-110.1585 2242.5304,-106.4101 2232.4461,-103.1607 2232.6208,-110.1585"/>
<text text-anchor="middle" x="1741.7514" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- methylation_array_file -->
<g id="node23" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1830.7514" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1830.7514" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge38" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1724.344,-358.8057C1665.3384,-353.479 1590.9293,-344.549 1525.7514,-330 1505.1759,-325.4071 1500.9514,-321.0337 1480.7514,-315 1450.796,-306.0524 1442.7983,-305.6351 1412.7514,-297 1408.4163,-295.7542 1403.9104,-294.422 1399.4118,-293.0672"/>
<polygon fill="#000000" stroke="#000000" points="1400.2303,-289.6578 1389.6443,-290.0899 1398.1892,-296.3537 1400.2303,-289.6578"/>
<text text-anchor="middle" x="1617.2514" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge36" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1840.6724,-347.6181C1844.7214,-337.484 1847.2994,-324.9735 1841.7514,-315 1819.628,-275.2298 1796.7966,-278.4157 1754.7514,-261 1649.9839,-217.6039 1615.1052,-236.1054 1504.7514,-210 1500.9359,-209.0974 1497.0051,-208.0772 1493.0729,-206.9926"/>
<polygon fill="#000000" stroke="#000000" points="1493.9387,-203.5998 1483.3606,-204.1944 1492.0007,-210.3262 1493.9387,-203.5998"/>
<text text-anchor="middle" x="1920.2514" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge37" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1830.8108,-347.7809C1829.7926,-336.5047 1826.4286,-322.7457 1816.7514,-315 1783.5776,-288.4476 1472.2991,-316.8922 1434.7514,-297 1417.0783,-287.6371 1421.0761,-275.9148 1407.7514,-261 1393.5075,-245.0564 1392.1835,-236.9151 1372.7514,-228 1319.1259,-203.3976 1145.1353,-195.3532 1067.1629,-192.943"/>
<polygon fill="#000000" stroke="#000000" points="1066.9189,-189.4344 1056.8204,-192.6391 1066.7133,-196.4314 1066.9189,-189.4344"/>
<text text-anchor="middle" x="1526.2514" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- synonym -->
<g id="node24" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2396.7514" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2396.7514" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge41" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2448.9824,-364.867C2675.2822,-359.6209 3559.7514,-335.5029 3559.7514,-279 3559.7514,-279 3559.7514,-279 3559.7514,-105 3559.7514,-74.1759 3540.509,-67.403 3512.7514,-54 3473.5854,-35.0884 3185.3066,-23.4285 3070.6194,-19.4946"/>
<polygon fill="#000000" stroke="#000000" points="3070.5114,-15.989 3060.3987,-19.1487 3070.2746,-22.985 3070.5114,-15.989"/>
<text text-anchor="middle" x="3602.2514" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge40" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2345.8446,-361.9943C2231.8091,-353.0722 1947.1549,-331.0842 1708.7514,-315 1577.2517,-306.1282 1542.401,-320.7032 1412.7514,-297 1407.9482,-296.1219 1402.9846,-294.9723 1398.076,-293.6784"/>
<polygon fill="#000000" stroke="#000000" points="1398.722,-290.2235 1388.1463,-290.8601 1396.8107,-296.9576 1398.722,-290.2235"/>
<text text-anchor="middle" x="1959.2514" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge39" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2398.9157,-347.7503C2404.1639,-300.2744 2415.5324,-174.2898 2392.7514,-141 2386.1902,-131.4121 2376.585,-124.3752 2366.1056,-119.2111"/>
<polygon fill="#000000" stroke="#000000" points="2367.2925,-115.9108 2356.7259,-115.1381 2364.5044,-122.3316 2367.2925,-115.9108"/>
<text text-anchor="middle" x="2448.2514" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study_personnel -->
<g id="node25" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="3674.7514" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="3674.7514" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge12" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3648.0941,-87.787C3628.3966,-76.0243 3600.4709,-61.2937 3573.7514,-54 3479.5334,-28.281 3185.8772,-20.6884 3070.7402,-18.6674"/>
<polygon fill="#000000" stroke="#000000" points="3070.5482,-15.1637 3060.4904,-18.494 3070.4298,-22.1627 3070.5482,-15.1637"/>
<text text-anchor="middle" x="3680.2514" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
</g>
</svg>
</div>
