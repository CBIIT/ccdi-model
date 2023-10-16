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
<svg width="3029pt" height="392pt"
 viewBox="0.00 0.00 3029.34 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3025.3431,-388 3025.3431,4 -4,4"/>
<!-- family_relationship -->
<g id="node1" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="2014.3431" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="2014.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- participant -->
<g id="node21" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1202.3431" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1202.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1981.1327,-174.8904C1956.0842,-162.9311 1920.4881,-147.9118 1887.3431,-141 1753.7146,-113.1342 1408.5334,-141.8857 1273.3431,-123 1267.912,-122.2413 1262.2958,-121.2274 1256.7111,-120.0658"/>
<polygon fill="#000000" stroke="#000000" points="1257.2619,-116.6027 1246.7394,-117.8387 1255.736,-123.4343 1257.2619,-116.6027"/>
<text text-anchor="middle" x="2012.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- study_funding -->
<g id="node2" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="77.3431" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="77.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study -->
<g id="node17" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1126.3431" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1126.3431" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge33" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M72.0447,-86.5556C70.1289,-75.6257 70.1383,-62.3266 78.3431,-54 96.153,-35.9258 878.23,-22.0223 1079.5037,-18.739"/>
<polygon fill="#000000" stroke="#000000" points="1079.8003,-22.2347 1089.7422,-18.573 1079.6867,-15.2357 1079.8003,-22.2347"/>
<text text-anchor="middle" x="140.3431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- synonym -->
<g id="node3" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1074.3431" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1074.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- sample -->
<g id="node4" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1674.3431" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1674.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge38" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1082.5194,-260.992C1088.8599,-249.3427 1098.8479,-235.0755 1112.3431,-228 1162.4631,-201.7223 1565.6805,-220.208 1621.3431,-210 1624.9991,-209.3295 1628.7458,-208.4576 1632.4745,-207.4593"/>
<polygon fill="#000000" stroke="#000000" points="1633.6317,-210.767 1642.2276,-204.5735 1631.6455,-204.0546 1633.6317,-210.767"/>
<text text-anchor="middle" x="1154.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge37" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1022.3013,-278.7166C847.4037,-277.23 288.7205,-267.9474 235.3431,-210 224.503,-198.2318 230.7066,-189.3135 235.3431,-174 257.4539,-100.973 309.7076,-106.9908 383.3431,-87 515.8335,-51.0312 938.2259,-27.3251 1079.6779,-20.2313"/>
<polygon fill="#000000" stroke="#000000" points="1079.9468,-23.7223 1089.7606,-19.73 1079.5991,-16.7309 1079.9468,-23.7223"/>
<text text-anchor="middle" x="292.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge39" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1073.609,-260.6498C1073.604,-238.2972 1076.5504,-200.2747 1094.3431,-174 1109.2986,-151.9151 1133.929,-135.3837 1155.8942,-124.0473"/>
<polygon fill="#000000" stroke="#000000" points="1157.6863,-127.0662 1165.1087,-119.5059 1154.5917,-120.7873 1157.6863,-127.0662"/>
<text text-anchor="middle" x="1136.8431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1661.5621,-174.7018C1651.743,-162.8979 1637.0593,-148.153 1620.3431,-141 1549.3545,-110.6234 1349.6902,-134.5433 1273.3431,-123 1267.9208,-122.1802 1262.3106,-121.1258 1256.7295,-119.9391"/>
<polygon fill="#000000" stroke="#000000" points="1257.2882,-116.477 1246.7621,-117.6822 1255.7423,-123.3042 1257.2882,-116.477"/>
<text text-anchor="middle" x="1678.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- clinical_measure_file -->
<g id="node5" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="353.3431" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="353.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge16" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M347.0986,-174.0019C344.5921,-163.2399 343.8254,-149.9605 351.3431,-141 398.735,-84.5126 920.2424,-35.5983 1080.0618,-21.8474"/>
<polygon fill="#000000" stroke="#000000" points="1080.3914,-25.3321 1090.0569,-20.9928 1079.795,-18.3576 1080.3914,-25.3321"/>
<text text-anchor="middle" x="608.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M352.0766,-173.8121C352.3758,-162.5487 354.9195,-148.7922 364.3431,-141 397.191,-113.8389 1089.1132,-128.7737 1131.3431,-123 1136.8553,-122.2464 1142.557,-121.2246 1148.2226,-120.0484"/>
<polygon fill="#000000" stroke="#000000" points="1149.3369,-123.3858 1158.3327,-117.789 1147.8101,-116.5543 1149.3369,-123.3858"/>
<text text-anchor="middle" x="493.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- radiology_file -->
<g id="node6" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="595.3431" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="595.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M608.5132,-174.1227C618.3139,-162.3717 632.8134,-147.9319 649.3431,-141 698.7662,-120.2741 1078.2958,-130.6275 1131.3431,-123 1136.7712,-122.2195 1142.3854,-121.1912 1147.9688,-120.0207"/>
<polygon fill="#000000" stroke="#000000" points="1148.9482,-123.388 1157.939,-117.783 1147.4152,-116.5579 1148.9482,-123.388"/>
<text text-anchor="middle" x="708.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node7" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2508.3431" cy="-366" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="2508.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2610.0241,-353.8449C2627.7888,-351.8204 2646.0985,-349.797 2663.3431,-348 2684.9847,-345.7449 2843.6815,-346.0773 2858.3431,-330 2862.8353,-325.0741 2862.8257,-319.9347 2858.3431,-315 2844.308,-299.5491 2692.0803,-299.3848 2671.3431,-297 2551.5115,-283.219 2522.1339,-275.1316 2402.3431,-261 2259.034,-244.094 2223.2245,-239.0216 2079.3431,-228 1923.1519,-216.0354 1881.1952,-239.4685 1727.3431,-210 1723.6925,-209.3008 1719.9496,-208.4086 1716.2235,-207.3969"/>
<polygon fill="#000000" stroke="#000000" points="1717.0576,-203.9934 1706.4744,-204.4896 1715.0571,-210.7014 1717.0576,-203.9934"/>
<text text-anchor="middle" x="2779.8431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- cell_line -->
<g id="node16" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2344.3431" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2344.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge29" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2504.8159,-348.003C2501.7433,-336.9629 2496.1766,-323.3825 2486.3431,-315 2473.1753,-303.7751 2433.8888,-294.3122 2399.9688,-287.9095"/>
<polygon fill="#000000" stroke="#000000" points="2400.5779,-284.4629 2390.111,-286.1041 2399.3168,-291.3484 2400.5779,-284.4629"/>
<text text-anchor="middle" x="2605.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- pdx -->
<g id="node24" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1907.3431" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1907.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge30" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2373.9974,-361.8738C2205.2116,-356.0951 1935.3844,-344.6371 1918.3431,-330 1911.7485,-324.3357 1908.5525,-315.7502 1907.1337,-307.23"/>
<polygon fill="#000000" stroke="#000000" points="1910.5991,-306.6976 1906.1755,-297.0704 1903.63,-307.3549 1910.5991,-306.6976"/>
<text text-anchor="middle" x="2026.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- diagnosis -->
<g id="node8" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="741.3431" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="741.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge40" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M753.285,-174.2233C762.2438,-162.5184 775.6346,-148.0923 791.3431,-141 860.3018,-109.8656 1056.5381,-134.3509 1131.3431,-123 1136.765,-122.1773 1142.375,-121.121 1147.9558,-119.9331"/>
<polygon fill="#000000" stroke="#000000" points="1148.9436,-123.2981 1157.923,-117.6748 1147.3968,-116.4711 1148.9436,-123.2981"/>
<text text-anchor="middle" x="835.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- study_admin -->
<g id="node9" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="908.3431" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="908.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge36" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M917.3425,-86.9296C923.8663,-75.7144 933.7448,-61.9675 946.3431,-54 968.2538,-40.1433 1035.0161,-29.359 1080.7715,-23.3385"/>
<polygon fill="#000000" stroke="#000000" points="1081.2914,-26.8006 1090.7639,-22.055 1080.3995,-19.8576 1081.2914,-26.8006"/>
<text text-anchor="middle" x="1002.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- cytogenomic_file -->
<g id="node10" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1017.3431" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1017.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1007.5773,-348.0025C1003.1982,-337.2408 1000.5622,-323.9615 1008.3431,-315 1027.0311,-293.4766 1107.5163,-303.1775 1135.3431,-297 1188.8708,-285.117 1199.7972,-272.8004 1253.3431,-261 1414.5926,-225.4639 1460.6693,-248.054 1621.3431,-210 1624.7562,-209.1917 1628.2603,-208.2534 1631.7621,-207.238"/>
<polygon fill="#000000" stroke="#000000" points="1633.0251,-210.5112 1641.5468,-204.2158 1630.9593,-203.8229 1633.0251,-210.5112"/>
<text text-anchor="middle" x="1324.8431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;cell_line -->
<g id="edge11" class="edge">
<title>cytogenomic_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1073.6271,-351.929C1134.0098,-336.8333 1221.3431,-315 1221.3431,-315 1380.5987,-293.3795 1783.7247,-302.6127 1944.3431,-297 2065.516,-292.7657 2207.2539,-285.9456 2285.2851,-282.0288"/>
<polygon fill="#000000" stroke="#000000" points="2285.5913,-285.5179 2295.4026,-281.5193 2285.2392,-278.5268 2285.5913,-285.5179"/>
<text text-anchor="middle" x="1292.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;pdx -->
<g id="edge12" class="edge">
<title>cytogenomic_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1012.0955,-348.0135C1010.0779,-336.9777 1009.9589,-323.398 1018.3431,-315 1051.5966,-281.6919 1819.3413,-306.9527 1865.3431,-297 1868.7814,-296.2561 1872.2887,-295.2299 1875.738,-294.0414"/>
<polygon fill="#000000" stroke="#000000" points="1877.1481,-297.2484 1885.1997,-290.3621 1874.6111,-290.7243 1877.1481,-297.2484"/>
<text text-anchor="middle" x="1089.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- methylation_array_file -->
<g id="node11" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1711.3431" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1711.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1703.849,-347.8614C1698.4658,-334.1235 1691.4596,-314.6635 1687.3431,-297 1681.3516,-271.2902 1677.9901,-241.3544 1676.194,-220.0406"/>
<polygon fill="#000000" stroke="#000000" points="1679.6809,-219.735 1675.4126,-210.038 1672.7022,-220.2802 1679.6809,-219.735"/>
<text text-anchor="middle" x="1778.8431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge20" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1825.1622,-362.5888C1930.8736,-358.2914 2080.0239,-349.0287 2135.3431,-330 2146.8835,-326.0303 2147.0304,-319.5782 2158.3431,-315 2199.3102,-298.421 2248.5136,-289.3281 2286.0212,-284.4301"/>
<polygon fill="#000000" stroke="#000000" points="2286.7811,-287.8627 2296.2736,-283.1571 2285.9185,-280.916 2286.7811,-287.8627"/>
<text text-anchor="middle" x="2249.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge19" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1706.2921,-347.7896C1704.4694,-336.9476 1704.4899,-323.6589 1712.3431,-315 1735.3421,-289.6416 1832.2681,-305.8341 1865.3431,-297 1868.7418,-296.0922 1872.2233,-294.9589 1875.6568,-293.7053"/>
<polygon fill="#000000" stroke="#000000" points="1877.1051,-296.8959 1885.0982,-289.9417 1874.513,-290.3935 1877.1051,-296.8959"/>
<text text-anchor="middle" x="1803.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- exposure -->
<g id="node12" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="867.3431" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="867.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M873.477,-173.7496C878.3374,-162.3085 886.336,-148.3759 898.3431,-141 942.593,-113.8175 1080.0969,-131.4119 1131.3431,-123 1136.6762,-122.1246 1142.1954,-121.0438 1147.6919,-119.8498"/>
<polygon fill="#000000" stroke="#000000" points="1148.5505,-123.2439 1157.516,-117.5985 1146.9868,-116.4207 1148.5505,-123.2439"/>
<text text-anchor="middle" x="941.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- sequencing_file -->
<g id="node13" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1374.3431" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1374.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1364.4771,-347.6658C1360.355,-337.3044 1357.855,-324.5544 1364.3431,-315 1372.2827,-303.3081 1548.4727,-237.8894 1631.6218,-207.5086"/>
<polygon fill="#000000" stroke="#000000" points="1632.8503,-210.7861 1641.0446,-204.0702 1630.4507,-204.2102 1632.8503,-210.7861"/>
<text text-anchor="middle" x="1553.8431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge2" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1426.7682,-351.9268C1481.7492,-337.2119 1561.2,-316.0921 1568.3431,-315 1577.1912,-313.6472 2105.4278,-289.7626 2285.1956,-281.6619"/>
<polygon fill="#000000" stroke="#000000" points="2285.4323,-285.1549 2295.2646,-281.2082 2285.1172,-278.162 2285.4323,-285.1549"/>
<text text-anchor="middle" x="1634.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge1" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1369.0517,-347.5625C1367.1385,-336.6351 1367.1483,-323.3363 1375.3431,-315 1394.4396,-295.5739 1838.7639,-302.9661 1865.3431,-297 1868.7756,-296.2295 1872.2791,-295.1859 1875.726,-293.9869"/>
<polygon fill="#000000" stroke="#000000" points="1877.1424,-297.1912 1885.1847,-290.2939 1874.5966,-290.6706 1877.1424,-297.1912"/>
<text text-anchor="middle" x="1441.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- follow_up -->
<g id="node14" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="994.3431" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="994.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M989.3364,-173.8294C987.5303,-163.0025 987.5528,-149.7155 995.3431,-141 1015.6597,-118.2707 1101.4056,-128.7557 1131.3431,-123 1136.3655,-122.0344 1141.5622,-120.928 1146.7545,-119.7487"/>
<polygon fill="#000000" stroke="#000000" points="1147.756,-123.1087 1156.6872,-117.4092 1146.1511,-116.2951 1147.756,-123.1087"/>
<text text-anchor="middle" x="1040.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- publication -->
<g id="node15" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="1059.3431" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="1059.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge28" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1059.4483,-86.6462C1060.3167,-76.2783 1062.8167,-63.5283 1069.3431,-54 1074.4773,-46.5043 1081.7387,-40.2443 1089.3652,-35.1599"/>
<polygon fill="#000000" stroke="#000000" points="1091.6215,-37.8867 1098.3802,-29.7276 1088.0086,-31.8911 1091.6215,-37.8867"/>
<text text-anchor="middle" x="1120.3431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2296.4235,-273.9269C2156.2486,-259.0493 1755.0903,-216.1869 1727.3431,-210 1723.7656,-209.2023 1720.0918,-208.2489 1716.4276,-207.203"/>
<polygon fill="#000000" stroke="#000000" points="1717.4105,-203.8437 1706.8239,-204.2619 1715.3607,-210.5368 1717.4105,-203.8437"/>
<text text-anchor="middle" x="2034.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge27" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2355.2551,-261.3701C2366.8269,-240.3734 2382.1805,-204.3283 2372.3431,-174 2352.0182,-111.3386 2343.5515,-84.8438 2285.3431,-54 2235.4609,-27.5681 1382.9667,-19.8161 1172.8558,-18.3029"/>
<polygon fill="#000000" stroke="#000000" points="1172.7954,-14.8025 1162.7708,-18.2315 1172.7458,-21.8023 1172.7954,-14.8025"/>
<text text-anchor="middle" x="2405.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2332.0156,-261.2054C2309.1425,-229.9281 2256.7393,-166.0412 2194.3431,-141 2146.8487,-121.9393 1324.0614,-129.8329 1273.3431,-123 1267.8295,-122.2572 1262.1268,-121.2426 1256.4607,-120.0707"/>
<polygon fill="#000000" stroke="#000000" points="1256.8719,-116.5765 1246.3498,-117.8163 1255.3485,-123.4088 1256.8719,-116.5765"/>
<text text-anchor="middle" x="2327.8431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- pathology_file -->
<g id="node18" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2748.3431" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2748.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2806.3278,-354.2161C2833.8019,-347.672 2862.8739,-339.0404 2873.3431,-330 2897.0959,-309.4891 2910.0144,-283.699 2888.3431,-261 2833.6548,-203.7182 2255.4653,-231.4195 2176.3431,-228 2076.5783,-223.6883 1825.5203,-228.2442 1727.3431,-210 1723.6887,-209.3209 1719.9432,-208.4429 1716.2153,-207.4406"/>
<polygon fill="#000000" stroke="#000000" points="1717.0457,-204.0363 1706.4633,-204.5483 1715.0553,-210.7473 1717.0457,-204.0363"/>
<text text-anchor="middle" x="2960.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge23" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2742.513,-347.8378C2737.8541,-336.4339 2730.1236,-322.5097 2718.3431,-315 2692.4447,-298.4905 2502.2323,-286.7883 2403.4891,-281.7555"/>
<polygon fill="#000000" stroke="#000000" points="2403.5239,-278.2529 2393.3607,-281.2463 2403.1723,-285.2441 2403.5239,-278.2529"/>
<text text-anchor="middle" x="2793.3431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge24" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2691.9749,-353.8701C2679.9328,-351.6216 2667.2531,-349.5094 2655.3431,-348 2590.1868,-339.7424 2421.703,-353.4199 2360.3431,-330 2350.2916,-326.1635 2351.3523,-318.9459 2341.3431,-315 2269.7942,-286.7931 2037.8698,-280.6825 1945.6601,-279.3624"/>
<polygon fill="#000000" stroke="#000000" points="1945.4282,-275.8591 1935.3829,-279.227 1945.3359,-282.8585 1945.4282,-275.8591"/>
<text text-anchor="middle" x="2421.3431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- therapeutic_procedure -->
<g id="node19" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="1306.3431" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="1306.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1285.0462,-174.1843C1269.4188,-161.1114 1248.0275,-143.2167 1230.9155,-128.9019"/>
<polygon fill="#000000" stroke="#000000" points="1232.8187,-125.9308 1222.9028,-122.199 1228.3272,-131.2999 1232.8187,-125.9308"/>
<text text-anchor="middle" x="1354.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- study_personnel -->
<g id="node20" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="1369.3431" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1369.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge32" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1346.0931,-87.5764C1330.2706,-76.4845 1308.447,-62.6303 1287.3431,-54 1250.0254,-38.7391 1205.0685,-29.3764 1172.1565,-24.0397"/>
<polygon fill="#000000" stroke="#000000" points="1172.3383,-20.5259 1161.9189,-22.446 1171.2616,-27.4426 1172.3383,-20.5259"/>
<text text-anchor="middle" x="1384.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge7" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1193.4104,-86.971C1187.8495,-76.7113 1180.0995,-63.9613 1171.3431,-54 1166.7276,-48.7493 1161.2791,-43.6829 1155.7963,-39.0914"/>
<polygon fill="#000000" stroke="#000000" points="1157.8317,-36.2379 1147.8317,-32.7379 1153.4664,-41.7101 1157.8317,-36.2379"/>
<text text-anchor="middle" x="1232.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_arm -->
<g id="node22" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2230.3431" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2230.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge6" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2211.9043,-87.803C2197.8473,-75.8836 2177.38,-60.9524 2156.3431,-54 2062.3962,-22.9519 1361.8412,-18.6811 1173.0776,-18.0937"/>
<polygon fill="#000000" stroke="#000000" points="1172.9381,-14.5933 1162.9279,-18.0641 1172.9176,-21.5933 1172.9381,-14.5933"/>
<text text-anchor="middle" x="2232.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- medical_history -->
<g id="node23" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1527.3431" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1527.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1507.2502,-174.4716C1492.7422,-162.8806 1472.1219,-148.4886 1451.3431,-141 1376.5383,-114.0406 1351.6497,-136.8078 1273.3431,-123 1268.2302,-122.0984 1262.9422,-121.0266 1257.665,-119.8617"/>
<polygon fill="#000000" stroke="#000000" points="1258.1107,-116.3724 1247.579,-117.5273 1256.5322,-123.1922 1258.1107,-116.3724"/>
<text text-anchor="middle" x="1548.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1883.8967,-268.666C1877.8782,-266.0921 1871.3944,-263.3874 1865.3431,-261 1815.1535,-241.1988 1756.7167,-220.4147 1717.8274,-206.8985"/>
<polygon fill="#000000" stroke="#000000" points="1718.9731,-203.5914 1708.3783,-203.6238 1716.6809,-210.2055 1718.9731,-203.5914"/>
<text text-anchor="middle" x="1836.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge10" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1934.4347,-274.3937C1987.2283,-264.8065 2100.7054,-240.9962 2123.3431,-210 2142.7655,-183.4064 2125.0786,-157.0847 2096.3431,-141 1934.7523,-50.5497 1344.0223,-24.9327 1173.0152,-19.3379"/>
<polygon fill="#000000" stroke="#000000" points="1172.9405,-15.8339 1162.8337,-19.0125 1172.7168,-22.8303 1172.9405,-15.8339"/>
<text text-anchor="middle" x="2139.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- molecular_test -->
<g id="node25" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1816.3431" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1816.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1791.2918,-174.833C1772.4276,-162.9285 1745.4368,-148.0028 1719.3431,-141 1623.5414,-115.2894 1371.5038,-137.2651 1273.3431,-123 1267.9162,-122.2113 1262.3029,-121.1776 1256.7199,-120.0037"/>
<polygon fill="#000000" stroke="#000000" points="1257.2745,-116.5411 1246.7503,-117.762 1255.7389,-123.3706 1257.2745,-116.5411"/>
<text text-anchor="middle" x="1819.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
</g>
</svg>
</div>
