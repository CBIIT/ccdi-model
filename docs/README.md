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
<svg width="3010pt" height="392pt"
 viewBox="0.00 0.00 3010.19 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3006.1903,-388 3006.1903,4 -4,4"/>
<!-- study -->
<g id="node1" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="898.3956" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="898.3956" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- participant -->
<g id="node2" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1512.3956" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1512.3956" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- consent_group -->
<g id="node27" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1246.3956" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1246.3956" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge39" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1470.8331,-178.4063C1425.2169,-163.4866 1351.7865,-139.4699 1301.4202,-122.9968"/>
<polygon fill="#000000" stroke="#000000" points="1302.2622,-119.5897 1291.6696,-119.8076 1300.0861,-126.2429 1302.2622,-119.5897"/>
<text text-anchor="middle" x="1445.8956" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- radiology_file -->
<g id="node3" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1278.3956" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1278.3956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1267.6522,-261.0635C1262.7487,-250.3246 1259.5799,-237.048 1267.3956,-228 1278.7562,-214.8481 1373.5119,-203.9479 1441.7793,-197.702"/>
<polygon fill="#000000" stroke="#000000" points="1442.422,-201.1585 1452.0685,-196.7773 1441.7953,-194.1866 1442.422,-201.1585"/>
<text text-anchor="middle" x="1326.3956" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- diagnosis -->
<g id="node4" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1239.3956" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1239.3956" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1272.5515,-351.6651C1298.2843,-339.5126 1333.9168,-320.3541 1360.3956,-297 1375.3951,-283.7706 1372.3047,-274.125 1387.3956,-261 1411.1121,-240.3731 1442.0015,-223.2516 1467.1395,-211.2234"/>
<polygon fill="#000000" stroke="#000000" points="1468.887,-214.2702 1476.4654,-206.8662 1465.9239,-207.9282 1468.887,-214.2702"/>
<text text-anchor="middle" x="1431.8956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- sample -->
<g id="node22" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="606.3956" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="606.3956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge34" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1203.0997,-352.4127C1168.7022,-340.217 1115.3143,-323.0368 1067.3956,-315 888.3861,-284.9769 837.7832,-330.5209 659.3956,-297 655.7426,-296.3136 651.998,-295.4304 648.2707,-294.4246"/>
<polygon fill="#000000" stroke="#000000" points="649.1025,-291.0206 638.5198,-291.5269 647.1084,-297.7306 649.1025,-291.0206"/>
<text text-anchor="middle" x="1174.8956" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- laboratory_test -->
<g id="node5" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1453.3956" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1453.3956" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1460.8865,-347.9825C1466.533,-334.1424 1474.316,-314.4975 1480.3956,-297 1489.4257,-271.0106 1498.4483,-240.9395 1504.5998,-219.6567"/>
<polygon fill="#000000" stroke="#000000" points="1507.985,-220.5484 1507.3764,-209.9711 1501.2561,-218.6194 1507.985,-220.5484"/>
<text text-anchor="middle" x="1557.8956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1402.2647,-351.7855C1355.97,-339.6069 1285.6875,-322.8309 1223.3956,-315 974.5599,-283.7183 906.1536,-341.8138 659.3956,-297 655.6877,-296.3266 651.8869,-295.4441 648.1064,-294.4314"/>
<polygon fill="#000000" stroke="#000000" points="648.8071,-290.9886 638.2247,-291.5006 646.8166,-297.6997 648.8071,-290.9886"/>
<text text-anchor="middle" x="1371.8956" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- cell_line -->
<g id="node6" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="49.3956" cy="-366" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="49.3956" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge3" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M38.4071,-348.4091C28.8074,-331.3379 16.3956,-304.3621 16.3956,-279 16.3956,-279 16.3956,-279 16.3956,-105 16.3956,14.0663 161.2556,-68.8228 279.3956,-54 492.1175,-27.3102 748.4984,-20.3596 851.8606,-18.5888"/>
<polygon fill="#000000" stroke="#000000" points="852.0191,-22.0868 861.9607,-18.4241 851.9049,-15.0877 852.0191,-22.0868"/>
<text text-anchor="middle" x="56.8956" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M79.4241,-351.6895C108.3108,-338.1684 150.0742,-319.3287 167.3956,-315 238.7807,-297.1605 450.9127,-285.7987 551.8496,-281.2565"/>
<polygon fill="#000000" stroke="#000000" points="552.302,-284.74 562.1369,-280.7999 551.9915,-277.7469 552.302,-284.74"/>
<text text-anchor="middle" x="207.8956" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- study_admin -->
<g id="node7" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="288.3956" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="288.3956" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge10" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M283.17,-86.6265C281.2816,-75.7233 281.2943,-62.4273 289.3956,-54 308.8001,-33.8147 711.7838,-22.411 851.3278,-19.0558"/>
<polygon fill="#000000" stroke="#000000" points="851.7721,-22.5463 861.6862,-18.8099 851.6059,-15.5483 851.7721,-22.5463"/>
<text text-anchor="middle" x="345.8956" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- pdx -->
<g id="node8" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="535.3956" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="535.3956" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge1" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M511.2109,-182.5311C469.9796,-165.0367 393.4875,-125.8757 425.3956,-87 452.3278,-54.1868 738.3734,-29.7475 852.1258,-21.2581"/>
<polygon fill="#000000" stroke="#000000" points="852.5473,-24.7366 862.2625,-20.5099 852.032,-17.7556 852.5473,-24.7366"/>
<text text-anchor="middle" x="449.3956" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M531.3963,-210.2866C530.1465,-220.6321 530.3965,-233.3821 536.3956,-243 542.0956,-252.1384 550.9205,-259.0621 560.406,-264.2686"/>
<polygon fill="#000000" stroke="#000000" points="559.0986,-267.5247 569.6222,-268.7505 562.1599,-261.2296 559.0986,-267.5247"/>
<text text-anchor="middle" x="560.3956" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study_funding -->
<g id="node9" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="559.3956" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="559.3956" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge27" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M574.573,-87.342C585.5256,-75.8488 601.3376,-61.6245 618.3956,-54 659.1469,-35.7852 783.6609,-25.2654 852.1088,-20.7117"/>
<polygon fill="#000000" stroke="#000000" points="852.4357,-24.198 862.1879,-20.0574 851.9821,-17.2127 852.4357,-24.198"/>
<text text-anchor="middle" x="680.3956" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- study_personnel -->
<g id="node10" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="741.3956" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="741.3956" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge23" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M741.9717,-86.6625C743.2833,-75.7727 746.7349,-62.4783 755.3956,-54 769.2332,-40.4539 816.6516,-30.3463 853.1312,-24.3436"/>
<polygon fill="#000000" stroke="#000000" points="853.7668,-27.7866 863.0933,-22.76 852.6678,-20.8734 853.7668,-27.7866"/>
<text text-anchor="middle" x="824.8956" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- pathology_file -->
<g id="node11" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="403.3956" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="403.3956" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M409.6134,-348.0061C414.3996,-336.8223 422.126,-323.0816 433.3956,-315 452.379,-301.3868 509.9995,-291.2301 553.5696,-285.2351"/>
<polygon fill="#000000" stroke="#000000" points="554.3025,-288.6684 563.7505,-283.8739 553.3748,-281.7301 554.3025,-288.6684"/>
<text text-anchor="middle" x="494.3956" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- methylation_array_file -->
<g id="node12" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="613.3956" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="613.3956" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge35" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M578.4341,-348.7957C571.5873,-343.7298 565.3195,-337.489 561.3956,-330 555.6311,-318.998 562.2011,-308.4269 571.9425,-299.7901"/>
<polygon fill="#000000" stroke="#000000" points="574.1458,-302.5102 579.8583,-293.5874 569.8282,-297.0003 574.1458,-302.5102"/>
<text text-anchor="middle" x="652.8956" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- publication -->
<g id="node13" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="909.3956" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="909.3956" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge6" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M903.4055,-86.8765C901.794,-81.215 900.2595,-74.9049 899.3956,-69 898.3151,-61.6148 897.8377,-53.5645 897.6833,-46.0876"/>
<polygon fill="#000000" stroke="#000000" points="901.1832,-46.0171 897.6511,-36.0284 894.1833,-46.0396 901.1832,-46.0171"/>
<text text-anchor="middle" x="950.3956" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- synonym -->
<g id="node14" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1981.3956" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1981.3956" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge19" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2032.4172,-362.3169C2185.4117,-351.0713 2631.3019,-316.7475 2655.3956,-297 2677.5215,-278.8653 2674.3956,-264.108 2674.3956,-235.5 2674.3956,-235.5 2674.3956,-235.5 2674.3956,-105 2674.3956,-60.4015 1226.4208,-25.4114 945.3407,-19.0392"/>
<polygon fill="#000000" stroke="#000000" points="945.1587,-15.5343 935.0822,-18.8077 945.0007,-22.5326 945.1587,-15.5343"/>
<text text-anchor="middle" x="2716.8956" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1980.5415,-347.6844C1978.6885,-325.3667 1972.8365,-287.3793 1954.3956,-261 1939.5627,-239.7819 1930.7438,-236.7969 1906.3956,-228 1849.0724,-207.2893 1681.8774,-197.9927 1584.6942,-194.2379"/>
<polygon fill="#000000" stroke="#000000" points="1584.7721,-190.7384 1574.6475,-193.8598 1584.5088,-197.7335 1584.7721,-190.7384"/>
<text text-anchor="middle" x="2013.8956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1931.976,-360.1451C1837.0595,-349.1639 1622.5914,-325.6283 1441.3956,-315 1267.8701,-304.8216 830.5583,-327.2996 659.3956,-297 655.6847,-296.3431 651.8818,-295.4721 648.1,-294.467"/>
<polygon fill="#000000" stroke="#000000" points="648.798,-291.0238 638.2161,-291.5482 646.8154,-297.7372 648.798,-291.0238"/>
<text text-anchor="middle" x="1677.8956" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- medical_history -->
<g id="node15" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1746.3956" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1746.3956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1704.2909,-263.3457C1663.7625,-248.2774 1602.55,-225.5189 1560.2066,-209.7759"/>
<polygon fill="#000000" stroke="#000000" points="1561.2667,-206.436 1550.6738,-206.2316 1558.8272,-212.9972 1561.2667,-206.436"/>
<text text-anchor="middle" x="1712.3956" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- sequencing_file -->
<g id="node16" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="830.3956" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="830.3956" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M800.0623,-349.1439C789.6311,-343.2216 777.9298,-336.4372 767.3956,-330 756.982,-323.6365 755.6679,-319.677 744.3956,-315 708.7283,-300.2013 696.6323,-307.2271 659.3956,-297 656.0617,-296.0844 652.6309,-295.0755 649.1943,-294.0172"/>
<polygon fill="#000000" stroke="#000000" points="650.1612,-290.6518 639.5703,-290.9393 648.0289,-297.3192 650.1612,-290.6518"/>
<text text-anchor="middle" x="833.8956" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- survival -->
<g id="node17" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1897.3956" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1897.3956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1870.3865,-264.0919C1848.0108,-252.4159 1815.0295,-236.7351 1784.3956,-228 1717.9845,-209.0633 1639.5588,-200.0292 1584.0255,-195.755"/>
<polygon fill="#000000" stroke="#000000" points="1584.1609,-192.2555 1573.9307,-195.011 1583.6463,-199.2366 1584.1609,-192.2555"/>
<text text-anchor="middle" x="1862.8956" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- treatment -->
<g id="node18" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="2142.3956" cy="-279" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="2142.3956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2108.3594,-264.3542C2079.0135,-252.4204 2035.206,-236.243 1995.3956,-228 1918.9645,-212.1745 1699.3812,-200.3697 1584.4633,-195.0766"/>
<polygon fill="#000000" stroke="#000000" points="1584.5003,-191.5747 1574.3511,-194.6152 1584.1811,-198.5675 1584.5003,-191.5747"/>
<text text-anchor="middle" x="2096.3956" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- family_relationship -->
<g id="node19" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="2318.3956" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="2318.3956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2274.4312,-262.7948C2240.2889,-250.9707 2191.4913,-235.7165 2147.3956,-228 2041.2838,-209.4311 1728.0441,-198.2549 1585.0542,-193.9892"/>
<polygon fill="#000000" stroke="#000000" points="1584.744,-190.4786 1574.645,-193.6819 1584.5374,-197.4756 1584.744,-190.4786"/>
<text text-anchor="middle" x="2288.8956" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- genetic_analysis -->
<g id="node20" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="1054.3956" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="1054.3956" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1064.178,-347.9881C1068.5634,-337.2209 1071.2001,-323.941 1063.3956,-315 1024.4591,-270.3936 970.3321,-341.6064 931.3956,-297 920.8739,-284.9462 920.8679,-273.0485 931.3956,-261 951.02,-238.5408 1034.9173,-247.5345 1064.3956,-243 1103.1767,-237.0345 1112.5158,-233.2835 1151.3956,-228 1251.9828,-214.331 1369.0016,-203.6043 1441.8939,-197.533"/>
<polygon fill="#000000" stroke="#000000" points="1442.2026,-201.0195 1451.8802,-196.7073 1441.6258,-194.0433 1442.2026,-201.0195"/>
<text text-anchor="middle" x="1001.3956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M992.3677,-353.1449C970.0904,-347.4464 945.1176,-339.7799 923.3956,-330 912.2675,-324.9898 911.956,-318.911 900.3956,-315 798.6511,-280.5784 764.6432,-318.4416 659.3956,-297 655.7535,-296.258 652.0165,-295.3359 648.2943,-294.3041"/>
<polygon fill="#000000" stroke="#000000" points="649.1362,-290.9023 638.5515,-291.3648 647.1144,-297.604 649.1362,-290.9023"/>
<text text-anchor="middle" x="993.3956" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- generic_file -->
<g id="node21" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="2720.3956" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="2720.3956" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge30" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2771.4375,-354.6502C2809.3059,-342.8675 2854.3956,-320.1895 2854.3956,-279 2854.3956,-279 2854.3956,-279 2854.3956,-105 2854.3956,-55.6314 1242.7111,-24.2039 945.2834,-18.8245"/>
<polygon fill="#000000" stroke="#000000" points="944.9257,-15.3176 934.8644,-18.637 944.7997,-22.3165 944.9257,-15.3176"/>
<text text-anchor="middle" x="2907.3956" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2713.0355,-348.03C2698.2145,-314.8723 2661.1733,-245.8243 2603.3956,-228 2506.8078,-198.2029 1813.4803,-193.0676 1585.1212,-192.1836"/>
<polygon fill="#000000" stroke="#000000" points="1584.9383,-188.683 1574.9254,-192.1457 1584.9123,-195.6829 1584.9383,-188.683"/>
<text text-anchor="middle" x="2736.3956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge28" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2656.3403,-361.9576C2498.2022,-352.1439 2076.538,-326.988 1724.3956,-315 1606.1139,-310.9733 775.9965,-317.2735 659.3956,-297 655.6827,-296.3544 651.8785,-295.4914 648.0957,-294.4915"/>
<polygon fill="#000000" stroke="#000000" points="648.7918,-291.048 638.2104,-291.5809 646.8146,-297.763 648.7918,-291.048"/>
<text text-anchor="middle" x="2134.3956" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M639.8113,-267.1948C676.6433,-254.8092 737.9059,-236.045 792.3956,-228 915.7454,-209.7883 1283.2482,-198.1175 1440.1216,-193.8381"/>
<polygon fill="#000000" stroke="#000000" points="1440.2435,-197.3362 1450.1452,-193.5669 1440.0542,-190.3387 1440.2435,-197.3362"/>
<text text-anchor="middle" x="828.8956" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge25" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M561.9059,-280.3223C433.6956,-284.3389 71.4146,-297.2185 53.3956,-315 47.3733,-320.9429 45.2793,-329.5253 45.0238,-337.9598"/>
<polygon fill="#000000" stroke="#000000" points="41.5291,-338.158 45.4836,-347.9871 48.5218,-337.8373 41.5291,-338.158"/>
<text text-anchor="middle" x="89.8956" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge26" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M601.1602,-260.7432C597.5817,-250.4076 592.0817,-237.6576 584.3956,-228 578.915,-221.1136 571.8069,-214.8942 564.7127,-209.6379"/>
<polygon fill="#000000" stroke="#000000" points="566.6996,-206.7565 556.4894,-203.9275 562.7069,-212.5062 566.6996,-206.7565"/>
<text text-anchor="middle" x="629.8956" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- clinical_measure_file -->
<g id="node23" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="777.3956" cy="-279" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="777.3956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge37" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M812.7093,-261.9449C823.1998,-256.3741 834.5204,-249.8463 844.3956,-243 910.9168,-196.8825 935.4859,-189.6648 981.3956,-123 999.5051,-96.7035 1019.8766,-80.0367 1001.3956,-54 994.0634,-43.6701 966.2788,-34.3077 941.4136,-27.7213"/>
<polygon fill="#000000" stroke="#000000" points="942.2753,-24.3291 931.7205,-25.2494 940.5455,-31.112 942.2753,-24.3291"/>
<text text-anchor="middle" x="1054.3956" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge38" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M824.5442,-262.6812C839.1945,-257.0488 855.2138,-250.3013 869.3956,-243 880.2461,-237.4138 880.8033,-231.8152 892.3956,-228 943.173,-211.2883 1287.3585,-198.8644 1439.8839,-194.1141"/>
<polygon fill="#000000" stroke="#000000" points="1440.2011,-197.6061 1450.0882,-193.7989 1439.9849,-190.6094 1440.2011,-197.6061"/>
<text text-anchor="middle" x="978.3956" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- treatment_response -->
<g id="node24" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="2541.3956" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="2541.3956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2497.9942,-262.6041C2464.2771,-250.6789 2416.0613,-235.3814 2372.3956,-228 2221.8934,-202.5586 1763.9567,-194.7968 1585.0791,-192.6991"/>
<polygon fill="#000000" stroke="#000000" points="1585.0209,-189.1983 1574.9814,-192.5833 1584.9406,-196.1978 1585.0209,-189.1983"/>
<text text-anchor="middle" x="2516.3956" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- cytogenomic_file -->
<g id="node25" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="219.3956" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="219.3956" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M233.1539,-347.9826C243.0168,-336.4866 257.3541,-322.4009 273.3956,-315 321.6256,-292.7485 470.6009,-283.9221 551.9728,-280.6916"/>
<polygon fill="#000000" stroke="#000000" points="552.1704,-284.1867 562.0294,-280.3072 551.903,-277.1918 552.1704,-284.1867"/>
<text text-anchor="middle" x="344.8956" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- exposure -->
<g id="node26" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1133.3956" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1133.3956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge36" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1142.3574,-260.7806C1148.9977,-249.3526 1159.1784,-235.423 1172.3956,-228 1195.2488,-215.1652 1348.4198,-202.9039 1441.2026,-196.5346"/>
<polygon fill="#000000" stroke="#000000" points="1441.6329,-200.0135 1451.3725,-195.8434 1441.1582,-193.0296 1441.6329,-200.0135"/>
<text text-anchor="middle" x="1215.8956" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge13" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1192.7833,-91.5969C1123.6121,-74.3041 1004.6544,-44.5647 941.1993,-28.7009"/>
<polygon fill="#000000" stroke="#000000" points="941.6862,-25.215 931.1358,-26.1851 939.9884,-32.006 941.6862,-25.215"/>
<text text-anchor="middle" x="1156.8956" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- study_arm -->
<g id="node28" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2942.3956" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2942.3956" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge32" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2923.9908,-87.6985C2909.9507,-75.7272 2889.4897,-60.7769 2868.3956,-54 2773.9965,-23.6726 1234.283,-18.7493 945.0339,-18.0908"/>
<polygon fill="#000000" stroke="#000000" points="944.8961,-14.5906 934.8884,-18.0683 944.8805,-21.5906 944.8961,-14.5906"/>
<text text-anchor="middle" x="2944.8956" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
</g>
</svg>
</div>
