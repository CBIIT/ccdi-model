<link rel='stylesheet' href="assets/style.css">
<link rel='stylesheet' href="https://unpkg.com/leaflet@1.5.1/dist/leaflet.css" integrity="sha512-xwE/Az9zrjBIphAcBb3F6JVqxf46+CDLwfLMHloNu6KEQCAWi6HcDUbeOfBIptF7tcCzusKFjFw2yuvEpDL9wQ==" crossorigin="">
<script type="text/javascript" src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
<script type="text/javascript"  src="https://unpkg.com/leaflet@1.5.1/dist/leaflet.js"></script>
<script type="text/javascript" src="assets/actions.js"></script>

![Build Status](https://github.com/CBIIT/ccdi-model/actions/workflows/model-test-and-deploy.yml/badge.svg)

# Children's Cancer Data Initiative Draft Model

[View model on GitHub Pages](https://cbiit.github.io/ccdi-model/)



Zoom to Node: <select id="node_select">
  <option value="">Zoom to Node</option>
</select>
<div id="model"></div>

<p>
<a href="./model-desc/ccdi-model-nodes-only.svg">SVG file (in view above)</a>
<p>
<a href="./model-desc">Additional model files</a>
<div id='graph' style='display:off;'>
<svg width="2751pt" height="305pt"
 viewBox="0.00 0.00 2751.29 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 2733.8919,-301 2733.8919,4 -4,4"/>
<!-- pathology_file -->
<g id="node1" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2637.8919" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2637.8919" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- sample -->
<g id="node8" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2220.8919" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2220.8919" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2625.6528,-261.1922C2616.6491,-249.6322 2603.3254,-235.3895 2587.8919,-228 2534.0138,-202.2035 2363.6723,-194.8865 2275.2886,-192.8151"/>
<polygon fill="#000000" stroke="#000000" points="2275.2626,-189.3138 2265.188,-192.5929 2275.1086,-196.3121 2275.2626,-189.3138"/>
<text text-anchor="middle" x="2668.8919" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- study_admin -->
<g id="node2" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="97.8919" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="97.8919" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study -->
<g id="node15" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="492.8919" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="492.8919" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge23" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M114.9514,-87.4977C127.3718,-75.9186 145.2254,-61.5302 163.8919,-54 214.0601,-33.7619 368.4186,-23.8191 446.5558,-19.9755"/>
<polygon fill="#000000" stroke="#000000" points="446.782,-23.4688 456.6031,-19.4943 446.4471,-16.4768 446.782,-23.4688"/>
<text text-anchor="middle" x="220.3919" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- methylation_array_file -->
<g id="node3" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1853.8919" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1853.8919" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1873.9314,-261.0511C1888.1871,-249.4281 1908.3787,-235.1681 1928.8919,-228 2029.4522,-192.8604 2063.5195,-231.2971 2167.8919,-210 2171.5338,-209.2569 2175.2706,-208.334 2178.9927,-207.3016"/>
<polygon fill="#000000" stroke="#000000" points="2180.173,-210.6014 2188.7353,-204.3615 2178.1506,-203.8999 2180.173,-210.6014"/>
<text text-anchor="middle" x="2020.3919" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- family_relationship -->
<g id="node4" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="893.8919" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="893.8919" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- participant -->
<g id="node19" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1338.8919" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1338.8919" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M913.673,-174.1893C927.7427,-162.628 947.6661,-148.3849 967.8919,-141 1021.0629,-121.5861 1174.8167,-111.8942 1266.853,-107.703"/>
<polygon fill="#000000" stroke="#000000" points="1267.1003,-111.1955 1276.9349,-107.2546 1266.7892,-104.2025 1267.1003,-111.1955"/>
<text text-anchor="middle" x="1047.3919" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- therapeutic_procedure -->
<g id="node5" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="1129.8919" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="1129.8919" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1127.8805,-173.6463C1127.7491,-162.7504 1129.6175,-149.4554 1137.8919,-141 1155.7246,-122.7773 1216.9745,-113.667 1267.2215,-109.1821"/>
<polygon fill="#000000" stroke="#000000" points="1267.7622,-112.649 1277.4321,-108.3195 1267.1729,-105.6738 1267.7622,-112.649"/>
<text text-anchor="middle" x="1230.8919" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- study_personnel -->
<g id="node6" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="272.8919" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="272.8919" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge18" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M274.3453,-86.8607C276.2121,-75.7639 280.4262,-62.1737 289.8919,-54 312.8132,-34.2074 394.1299,-24.8514 446.6269,-20.7826"/>
<polygon fill="#000000" stroke="#000000" points="447.001,-24.2646 456.7162,-20.0379 446.4856,-17.2836 447.001,-24.2646"/>
<text text-anchor="middle" x="359.3919" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- publication -->
<g id="node7" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="440.8919" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="440.8919" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge7" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M434.2692,-86.9798C431.645,-76.7231 430.395,-63.9731 435.8919,-54 440.2775,-46.0431 447.2442,-39.6017 454.8236,-34.4882"/>
<polygon fill="#000000" stroke="#000000" points="457.0889,-37.2125 463.8846,-29.0842 453.5033,-31.2005 457.0889,-37.2125"/>
<text text-anchor="middle" x="486.8919" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2203.0643,-175.2403C2189.0047,-163.2075 2168.2619,-147.938 2146.8919,-141 2068.9818,-115.7056 1491.0449,-134.1346 1409.8919,-123 1404.3801,-122.2438 1398.6786,-121.2203 1393.0132,-120.043"/>
<polygon fill="#000000" stroke="#000000" points="1393.426,-116.5489 1382.9032,-117.7823 1391.8984,-123.3802 1393.426,-116.5489"/>
<text text-anchor="middle" x="2212.3919" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- clinical_measure_file -->
<g id="node9" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="545.8919" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="545.8919" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge22" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M549.2995,-173.8003C553.5281,-146.1822 557.9441,-92.8023 537.8919,-54 534.7441,-47.9088 530.0568,-42.499 524.8798,-37.8422"/>
<polygon fill="#000000" stroke="#000000" points="527.055,-35.1002 517.0668,-31.5667 522.6714,-40.5577 527.055,-35.1002"/>
<text text-anchor="middle" x="638.8919" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M552.8776,-173.8405C558.3596,-162.2828 567.2048,-148.1817 579.8919,-141 587.3161,-136.7974 1078.714,-115.8647 1266.7753,-107.9964"/>
<polygon fill="#000000" stroke="#000000" points="1266.9976,-111.4902 1276.8427,-107.5755 1266.7052,-104.4963 1266.9976,-111.4902"/>
<text text-anchor="middle" x="709.3919" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- exposure -->
<g id="node10" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1318.8919" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1318.8919" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1323.0359,-173.9735C1325.7712,-162.0751 1329.409,-146.2508 1332.5101,-132.7606"/>
<polygon fill="#000000" stroke="#000000" points="1335.9237,-133.5333 1334.7532,-123.0034 1329.1017,-131.965 1335.9237,-133.5333"/>
<text text-anchor="middle" x="1374.3919" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- radiology_file -->
<g id="node11" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1463.8919" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1463.8919" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1452.3882,-174.1066C1444.7742,-163.3839 1433.9857,-150.1093 1421.8919,-141 1412.2864,-133.7649 1401.0025,-127.6375 1389.9033,-122.6023"/>
<polygon fill="#000000" stroke="#000000" points="1391.2336,-119.3645 1380.6643,-118.6293 1388.4682,-125.7951 1391.2336,-119.3645"/>
<text text-anchor="middle" x="1496.8919" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- pdx -->
<g id="node12" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2037.8919" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2037.8919" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2060.177,-268.1083C2065.023,-265.7539 2070.1254,-263.2856 2074.8919,-261 2111.3888,-243.4988 2153.1559,-223.7918 2182.6409,-209.9334"/>
<polygon fill="#000000" stroke="#000000" points="2184.1971,-213.0694 2191.76,-205.6497 2181.2208,-206.7336 2184.1971,-213.0694"/>
<text text-anchor="middle" x="2166.8919" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- molecular_test -->
<g id="node13" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1634.8919" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1634.8919" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1614.7481,-174.3393C1600.4458,-162.8449 1580.2415,-148.6202 1559.8919,-141 1497.0111,-117.4533 1475.9051,-135.2758 1409.8919,-123 1404.7876,-122.0508 1399.5054,-120.9465 1394.2321,-119.7608"/>
<polygon fill="#000000" stroke="#000000" points="1394.6856,-116.2724 1384.1509,-117.3995 1393.0891,-123.0879 1394.6856,-116.2724"/>
<text text-anchor="middle" x="1652.8919" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- study_funding -->
<g id="node14" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="812.8919" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="812.8919" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge13" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M762.5399,-91.3105C699.647,-74.2116 593.2025,-45.2719 534.6297,-29.3475"/>
<polygon fill="#000000" stroke="#000000" points="535.5305,-25.9654 524.9625,-26.7192 533.6939,-32.7202 535.5305,-25.9654"/>
<text text-anchor="middle" x="734.8919" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- synonym -->
<g id="node16" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="690.8919" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="690.8919" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M742.7703,-276.6746C1002.5172,-265.0198 2149.9996,-213.3862 2167.8919,-210 2171.544,-209.3088 2175.288,-208.4223 2179.0149,-207.4144"/>
<polygon fill="#000000" stroke="#000000" points="2180.1787,-210.7198 2188.7651,-204.5131 2178.1822,-204.0105 2180.1787,-210.7198"/>
<text text-anchor="middle" x="1845.3919" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge5" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M639.9003,-275.1304C496.8113,-263.1108 96.8854,-221.1731 18.8919,-123 -47.9179,-38.9043 81.1303,-64.2665 134.8919,-54 245.487,-32.8804 377.8202,-23.6543 446.4536,-20.0433"/>
<polygon fill="#000000" stroke="#000000" points="446.6995,-23.5355 456.5083,-19.5308 446.343,-16.5445 446.6995,-23.5355"/>
<text text-anchor="middle" x="99.3919" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M686.3738,-261.0617C681.6725,-237.7001 677.7469,-197.1247 699.8919,-174 721.4344,-151.5045 808.0546,-160.3803 838.8919,-156 882.0819,-149.865 892.5887,-146.2768 935.8919,-141 1051.9081,-126.8627 1187.3523,-115.895 1267.9632,-109.9488"/>
<polygon fill="#000000" stroke="#000000" points="1268.2821,-113.4349 1277.9996,-109.2135 1267.7706,-106.4536 1268.2821,-113.4349"/>
<text text-anchor="middle" x="742.3919" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- medical_history -->
<g id="node17" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1817.8919" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1817.8919" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1792.4034,-174.7179C1773.5408,-162.9218 1746.7401,-148.1797 1720.8919,-141 1587.4889,-103.9456 1546.727,-144.1079 1409.8919,-123 1404.4721,-122.1639 1398.8634,-121.0988 1393.2834,-119.9054"/>
<polygon fill="#000000" stroke="#000000" points="1393.8442,-116.4437 1383.3172,-117.6407 1392.293,-123.2697 1393.8442,-116.4437"/>
<text text-anchor="middle" x="1825.8919" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node18" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2221.8919" cy="-279" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="2221.8919" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2221.6847,-260.9735C2221.5493,-249.1918 2221.3696,-233.5607 2221.2155,-220.1581"/>
<polygon fill="#000000" stroke="#000000" points="2224.7136,-219.9624 2221.0988,-210.0034 2217.7141,-220.043 2224.7136,-219.9624"/>
<text text-anchor="middle" x="2330.3919" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge11" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1280.0745,-98.9514C1120.6875,-82.5605 682.8293,-37.5326 539.1984,-22.762"/>
<polygon fill="#000000" stroke="#000000" points="539.2827,-19.2523 528.977,-21.7109 538.5665,-26.2156 539.2827,-19.2523"/>
<text text-anchor="middle" x="1017.3919" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- diagnosis -->
<g id="node20" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1975.8919" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1975.8919" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1956.6034,-175.0613C1941.6942,-163.1048 1919.9399,-148.0133 1897.8919,-141 1794.4794,-108.1053 1517.3089,-138.4201 1409.8919,-123 1404.4636,-122.2208 1398.8494,-121.1932 1393.2659,-120.0232"/>
<polygon fill="#000000" stroke="#000000" points="1393.8193,-116.5604 1383.2956,-117.7861 1392.2867,-123.3906 1393.8193,-116.5604"/>
<text text-anchor="middle" x="1972.3919" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- sequencing_file -->
<g id="node21" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2460.8919" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="2460.8919" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2457.6665,-260.9638C2454.7043,-249.7626 2449.1471,-236.0184 2438.8919,-228 2414.0706,-208.5925 2331.337,-199.2685 2275.2367,-195.0785"/>
<polygon fill="#000000" stroke="#000000" points="2275.3153,-191.5753 2265.0915,-194.3546 2274.817,-198.5576 2275.3153,-191.5753"/>
<text text-anchor="middle" x="2517.3919" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- study_arm -->
<g id="node22" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1478.8919" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1478.8919" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1435.3201,-92.5236C1426.9333,-90.4381 1418.1799,-88.4761 1409.8919,-87 1239.6532,-56.6802 700.9439,-28.2677 539.2305,-20.2437"/>
<polygon fill="#000000" stroke="#000000" points="539.2924,-16.7425 529.1318,-19.7448 538.9469,-23.734 539.2924,-16.7425"/>
<text text-anchor="middle" x="1307.3919" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- follow_up -->
<g id="node23" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="2103.8919" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="2103.8919" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2083.5324,-175.2582C2067.5724,-163.2348 2044.2276,-147.9692 2020.8919,-141 1890.7357,-102.129 1544.4209,-141.8032 1409.8919,-123 1404.4608,-122.2409 1398.8446,-121.2267 1393.26,-120.065"/>
<polygon fill="#000000" stroke="#000000" points="1393.8108,-116.6019 1383.2883,-117.8377 1392.2848,-123.4335 1393.8108,-116.6019"/>
<text text-anchor="middle" x="2097.8919" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
</g>
</svg>
</div>
