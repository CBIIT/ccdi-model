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
<svg width="2855pt" height="392pt"
 viewBox="0.00 0.00 2855.34 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 2851.3431,-388 2851.3431,4 -4,4"/>
<!-- treatment_response -->
<g id="node1" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1125" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1125" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- participant -->
<g id="node20" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1175" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1175" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge37" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1098.4235,-261.4457C1087.1821,-251.7837 1078.2735,-239.46 1086,-228 1092.558,-218.2732 1102.2373,-211.1736 1112.8259,-205.9919"/>
<polygon fill="#000000" stroke="#000000" points="1114.5053,-209.0797 1122.3096,-201.9142 1111.7402,-202.6489 1114.5053,-209.0797"/>
<text text-anchor="middle" x="1169" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- clinical_measure_file -->
<g id="node2" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="258" cy="-279" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="258" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge38" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M263.9406,-260.8577C268.7527,-249.3074 276.771,-235.2083 289,-228 323.7854,-207.496 896.7972,-196.4183 1102.3411,-193.0896"/>
<polygon fill="#000000" stroke="#000000" points="1102.49,-196.5878 1112.4325,-192.9277 1102.3776,-189.5887 1102.49,-196.5878"/>
<text text-anchor="middle" x="375" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- study -->
<g id="node25" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1342" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1342" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge39" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M258.0949,-260.5986C259.1473,-249.6848 262.3327,-236.3876 271,-228 529.3581,22.0211 706.7848,-115.5716 1061,-54 1143.1689,-39.717 1239.7733,-28.5605 1295.6372,-22.6553"/>
<polygon fill="#000000" stroke="#000000" points="1296.3346,-26.1016 1305.9159,-21.5796 1295.6059,-19.1396 1296.3346,-26.1016"/>
<text text-anchor="middle" x="466" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- sequencing_file -->
<g id="node3" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1671" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1671" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sample -->
<g id="node23" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2206" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2206" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge36" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1685.4329,-348.1311C1696.0915,-336.3839 1711.7044,-321.9451 1729,-315 1816.5149,-279.8579 2060.3006,-314.3395 2153,-297 2156.6536,-296.3166 2160.3986,-295.4356 2164.1261,-294.4312"/>
<polygon fill="#000000" stroke="#000000" points="2165.2875,-297.7375 2173.8775,-291.5357 2163.2949,-291.0271 2165.2875,-297.7375"/>
<text text-anchor="middle" x="1795.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- laboratory_test -->
<g id="node4" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1268" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1268" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1271.0721,-347.9361C1274.8601,-319.5432 1277.9458,-264.0039 1252,-228 1246.3011,-220.0918 1238.4166,-213.8679 1229.8539,-208.9856"/>
<polygon fill="#000000" stroke="#000000" points="1231.2502,-205.7694 1220.7483,-204.3689 1228.0847,-212.0128 1231.2502,-205.7694"/>
<text text-anchor="middle" x="1338.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1299.3441,-349.3362C1323.8177,-337.2687 1359.0816,-321.9106 1392,-315 1557.5498,-280.2462 1986.4407,-326.5392 2153,-297 2156.7107,-296.3419 2160.5134,-295.4701 2164.2951,-294.4645"/>
<polygon fill="#000000" stroke="#000000" points="2165.5802,-297.7345 2174.1789,-291.5448 2163.597,-291.0213 2165.5802,-297.7345"/>
<text text-anchor="middle" x="1457.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- pathology_file -->
<g id="node5" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1848" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1848" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge35" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1855.0302,-347.9181C1860.5314,-336.3941 1869.3815,-322.3015 1882,-315 1934.2399,-284.7724 2093.8108,-308.805 2153,-297 2156.6452,-296.273 2160.3843,-295.3614 2164.1079,-294.3366"/>
<polygon fill="#000000" stroke="#000000" points="2165.2831,-297.6381 2173.8529,-291.4085 2163.2687,-290.9342 2165.2831,-297.6381"/>
<text text-anchor="middle" x="1943" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- diagnosis -->
<g id="node6" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="2474" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="2474" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2517.924,-355.2765C2543.9381,-346.7699 2569.2725,-333.2672 2555,-315 2505.7895,-252.0161 2285.1514,-239.1222 2206,-228 2020.6669,-201.9574 1450.8115,-194.443 1247.7781,-192.5615"/>
<polygon fill="#000000" stroke="#000000" points="1247.5558,-189.0594 1237.5244,-192.4684 1247.4921,-196.0591 1247.5558,-189.0594"/>
<text text-anchor="middle" x="2576.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2432.5665,-354.2254C2413.1227,-348.0574 2389.9033,-339.7515 2370,-330 2359.0407,-324.6305 2358.1733,-319.9087 2347,-315 2318.388,-302.4301 2284.5062,-293.6024 2257.1275,-287.8353"/>
<polygon fill="#000000" stroke="#000000" points="2257.4739,-284.3343 2246.9773,-285.7735 2256.0804,-291.1942 2257.4739,-284.3343"/>
<text text-anchor="middle" x="2414.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- radiology_file -->
<g id="node7" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1664" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1664" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1613.8731,-265.7256C1570.0812,-254.4879 1504.6706,-238.5665 1447,-228 1378.3007,-215.4128 1299.0688,-205.4347 1243.9058,-199.2061"/>
<polygon fill="#000000" stroke="#000000" points="1244.2206,-195.7196 1233.8937,-198.087 1243.443,-202.6763 1244.2206,-195.7196"/>
<text text-anchor="middle" x="1578" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- pdx -->
<g id="node8" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2602" cy="-366" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2602" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge23" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2599.0163,-347.9787C2596.1452,-336.6344 2590.5986,-322.7236 2580,-315 2567.2551,-305.7124 2360.3012,-289.9106 2259.8586,-282.7385"/>
<polygon fill="#000000" stroke="#000000" points="2259.8313,-279.2278 2249.6084,-282.0101 2259.3351,-286.2102 2259.8313,-279.2278"/>
<text text-anchor="middle" x="2616" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge22" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2621.3577,-352.5792C2629.1817,-346.4087 2637.8071,-338.5585 2644,-330 2658.3701,-310.1408 2665,-303.513 2665,-279 2665,-279 2665,-279 2665,-105 2665,-39.6468 1623.5353,-21.7755 1388.6695,-18.5762"/>
<polygon fill="#000000" stroke="#000000" points="1388.4645,-15.0733 1378.4185,-18.439 1388.3708,-22.0726 1388.4645,-15.0733"/>
<text text-anchor="middle" x="2689" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- methylation_array_file -->
<g id="node9" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2058" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2058" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge28" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2026.7804,-348.6258C2013.0602,-338.8069 2002.0719,-326.2761 2012,-315 2032.8738,-291.2921 2122.2241,-304.1147 2153,-297 2156.4173,-296.21 2159.9246,-295.2849 2163.4285,-294.2786"/>
<polygon fill="#000000" stroke="#000000" points="2164.6853,-297.5541 2173.2169,-291.2721 2162.6299,-290.8626 2164.6853,-297.5541"/>
<text text-anchor="middle" x="2103.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- synonym -->
<g id="node10" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="403" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="403" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M398.8237,-348.0411C394.6157,-325.0312 391.3538,-285.2323 412,-261 421.8046,-249.4924 529.0539,-230.2739 544,-228 649.7639,-211.9088 960.5051,-199.4442 1102.5983,-194.4174"/>
<polygon fill="#000000" stroke="#000000" points="1103.0723,-197.903 1112.9432,-194.054 1102.8265,-190.9073 1103.0723,-197.903"/>
<text text-anchor="middle" x="454.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M452.1295,-359.8837C545.9748,-348.5154 757.3057,-324.4303 936,-315 1071.0491,-307.873 2019.7376,-320.0256 2153,-297 2156.7136,-296.3584 2160.5183,-295.498 2164.3014,-294.5"/>
<polygon fill="#000000" stroke="#000000" points="2165.5812,-297.7719 2174.1872,-291.5922 2163.6059,-291.0564 2165.5812,-297.7719"/>
<text text-anchor="middle" x="978.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge17" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M353.1801,-360.4219C245.3571,-347.6756 0,-314.7438 0,-279 0,-279 0,-279 0,-105 0,16.6853 148.0562,-67.4132 269,-54 472.3182,-31.4512 1115.831,-21.1037 1295.1878,-18.6116"/>
<polygon fill="#000000" stroke="#000000" points="1295.3957,-22.1091 1305.3466,-18.472 1295.2994,-15.1098 1295.3957,-22.1091"/>
<text text-anchor="middle" x="42.5" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- medical_history -->
<g id="node11" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1841" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1841" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1792.5927,-264.1525C1752.3931,-252.4305 1693.5038,-236.6557 1641,-228 1502.8653,-205.2272 1339.2597,-196.7984 1247.2584,-193.7228"/>
<polygon fill="#000000" stroke="#000000" points="1247.3264,-190.2233 1237.2188,-193.3991 1247.1007,-197.2197 1247.3264,-190.2233"/>
<text text-anchor="middle" x="1781" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- study_arm -->
<g id="node12" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1018" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1018" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge4" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1038.1847,-88.0093C1052.967,-76.5118 1074.0296,-62.01 1095,-54 1130.781,-40.3328 1234.9214,-28.3751 1295.9528,-22.2828"/>
<polygon fill="#000000" stroke="#000000" points="1296.4815,-25.7477 1306.0906,-21.2851 1295.7959,-18.7814 1296.4815,-25.7477"/>
<text text-anchor="middle" x="1143.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- consent_group -->
<g id="node13" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1175" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1175" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge33" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1183.6373,-86.9776C1189.8081,-75.9274 1199.1145,-62.3453 1211,-54 1236.0756,-36.3934 1269.4343,-27.3856 1296.2129,-22.7834"/>
<polygon fill="#000000" stroke="#000000" points="1296.7873,-26.2362 1306.1229,-21.2265 1295.7008,-19.321 1296.7873,-26.2362"/>
<text text-anchor="middle" x="1274.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- study_admin -->
<g id="node14" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1342" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1342" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge25" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1342,-86.9735C1342,-75.1918 1342,-59.5607 1342,-46.1581"/>
<polygon fill="#000000" stroke="#000000" points="1345.5001,-46.0033 1342,-36.0034 1338.5001,-46.0034 1345.5001,-46.0033"/>
<text text-anchor="middle" x="1398.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- study_personnel -->
<g id="node15" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="1517" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1517" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge24" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1500.7223,-87.2666C1489.8382,-76.3317 1474.6821,-62.7695 1459,-54 1436.2981,-41.305 1408.5612,-32.5202 1385.7924,-26.8085"/>
<polygon fill="#000000" stroke="#000000" points="1386.5834,-23.3991 1376.043,-24.472 1384.9519,-30.2063 1386.5834,-23.3991"/>
<text text-anchor="middle" x="1548.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- generic_file -->
<g id="node16" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="648" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="648" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M643.5225,-347.7736C638.9887,-324.4743 635.3749,-284.363 657,-261 686.8815,-228.7171 968.8014,-205.7459 1103.7168,-196.5065"/>
<polygon fill="#000000" stroke="#000000" points="1104.2146,-199.9809 1113.9549,-195.8125 1103.741,-192.997 1104.2146,-199.9809"/>
<text text-anchor="middle" x="710" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M709.2775,-359.3247C816.0896,-347.9939 1043.3782,-325.2325 1236,-315 1337.765,-309.594 2052.6217,-314.5939 2153,-297 2156.712,-296.3494 2160.5157,-295.4828 2164.298,-294.4806"/>
<polygon fill="#000000" stroke="#000000" points="2165.5807,-297.7515 2174.1827,-291.5663 2163.6011,-291.0372 2165.5807,-297.7515"/>
<text text-anchor="middle" x="1289" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge29" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M586.6689,-359.444C455.235,-345.1536 156.9107,-311.3329 140,-297 118.1762,-278.5029 121,-264.108 121,-235.5 121,-235.5 121,-235.5 121,-105 121,-44.9869 1071.8724,-23.1416 1295.3716,-18.8358"/>
<polygon fill="#000000" stroke="#000000" points="1295.5263,-22.3336 1305.4579,-18.6439 1295.3931,-15.3348 1295.5263,-22.3336"/>
<text text-anchor="middle" x="174" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- family_relationship -->
<g id="node17" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="2044" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="2044" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1995.9257,-263.1828C1957.6571,-251.3207 1902.4931,-235.8343 1853,-228 1738.1234,-209.8161 1397.468,-198.2746 1247.3854,-193.9401"/>
<polygon fill="#000000" stroke="#000000" points="1247.443,-190.4404 1237.3469,-193.6527 1247.2426,-197.4375 1247.443,-190.4404"/>
<text text-anchor="middle" x="2001.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- publication -->
<g id="node18" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="1818" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="1818" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge13" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1782.1583,-90.1269C1752.581,-78.4712 1709.2477,-62.8006 1670,-54 1571.2472,-31.8563 1452.5875,-23.1308 1388.5259,-19.8493"/>
<polygon fill="#000000" stroke="#000000" points="1388.5067,-16.3443 1378.3474,-19.3505 1388.1641,-23.3359 1388.5067,-16.3443"/>
<text text-anchor="middle" x="1770" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- cytogenomic_file -->
<g id="node19" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="2281" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="2281" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2228.4718,-351.2546C2218.77,-346.1076 2209.8628,-339.2129 2204,-330 2199.7661,-323.3467 2198.7178,-315.1554 2199.1518,-307.2996"/>
<polygon fill="#000000" stroke="#000000" points="2202.6306,-307.6878 2200.4331,-297.3234 2195.6877,-306.796 2202.6306,-307.6878"/>
<text text-anchor="middle" x="2275.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge32" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1175,-173.9735C1175,-162.1918 1175,-146.5607 1175,-133.1581"/>
<polygon fill="#000000" stroke="#000000" points="1178.5001,-133.0033 1175,-123.0034 1171.5001,-133.0034 1178.5001,-133.0033"/>
<text text-anchor="middle" x="1225.5" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- exposure -->
<g id="node21" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="559" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="559" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M550.624,-261.2111C546.8286,-250.2541 544.8003,-236.688 553,-228 571.6047,-208.2874 942.5087,-197.3718 1102.5322,-193.5641"/>
<polygon fill="#000000" stroke="#000000" points="1102.8468,-197.0577 1112.7617,-193.3235 1102.6822,-190.0597 1102.8468,-197.0577"/>
<text text-anchor="middle" x="596.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- genetic_analysis -->
<g id="node22" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="1473" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="1473" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1411.1812,-353.149C1388.4856,-347.0748 1366.6825,-339.1424 1360,-330 1336.9718,-298.495 1399.541,-309.2063 1408,-297 1417.1135,-283.8492 1417.5736,-273.8197 1408,-261 1387.7943,-233.9433 1301.744,-213.7433 1240.1015,-202.4051"/>
<polygon fill="#000000" stroke="#000000" points="1240.5112,-198.9226 1230.0491,-200.5942 1239.2702,-205.8117 1240.5112,-198.9226"/>
<text text-anchor="middle" x="1485" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1495.8249,-348.5053C1512.7929,-336.6063 1537.0568,-321.8285 1561,-315 1687.5696,-278.9029 2023.4842,-320.4205 2153,-297 2156.7085,-296.3294 2160.5096,-295.4489 2164.2903,-294.4375"/>
<polygon fill="#000000" stroke="#000000" points="2165.5792,-297.706 2174.1724,-291.5086 2163.59,-290.9946 2165.5792,-297.706"/>
<text text-anchor="middle" x="1631" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge8" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2249.481,-282.5062C2300.2919,-287.2179 2386.6363,-297.1408 2459,-315 2480.0519,-320.1956 2533.1118,-339.779 2568.3408,-353.11"/>
<polygon fill="#000000" stroke="#000000" points="2567.1717,-356.4099 2577.7629,-356.6871 2569.6563,-349.8656 2567.1717,-356.4099"/>
<text text-anchor="middle" x="2540.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2179.5325,-264.5593C2155.6153,-252.3203 2119.0442,-235.5849 2085,-228 2004.3681,-210.0355 1448.9057,-197.4098 1247.6278,-193.3786"/>
<polygon fill="#000000" stroke="#000000" points="1247.5222,-189.8759 1237.4545,-193.1762 1247.3829,-196.8745 1247.5222,-189.8759"/>
<text text-anchor="middle" x="2165.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node24" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2401" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2401" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge10" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2236.0414,-265.5969C2269.2873,-250.7641 2323.058,-226.7741 2360.1223,-210.2378"/>
<polygon fill="#000000" stroke="#000000" points="2361.9256,-213.2658 2369.6318,-205.995 2359.0734,-206.8732 2361.9256,-213.2658"/>
<text text-anchor="middle" x="2351.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2439.8546,-203.1289C2464.7075,-212.166 2489.7448,-226.1505 2475,-243 2461.0715,-258.9167 2334.3492,-270.2158 2259.909,-275.5447"/>
<polygon fill="#000000" stroke="#000000" points="2259.4995,-272.0647 2249.7693,-276.2568 2259.99,-279.0475 2259.4995,-272.0647"/>
<text text-anchor="middle" x="2519.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge5" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2351.6984,-189.9035C2196.2585,-182.9473 1723.273,-159.0078 1665,-123 1634.2608,-104.0058 1652.408,-73.52 1622,-54 1584.3877,-29.8553 1458.2453,-21.8413 1388.8109,-19.2289"/>
<polygon fill="#000000" stroke="#000000" points="1388.703,-15.723 1378.5856,-18.8678 1388.4559,-22.7186 1388.703,-15.723"/>
<text text-anchor="middle" x="1705.5" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- treatment -->
<g id="node26" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="830" cy="-279" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="830" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M843.5799,-261.3131C853.4654,-249.807 867.8993,-235.5791 884,-228 921.6657,-210.2696 1029.9849,-200.5002 1103.3026,-195.7566"/>
<polygon fill="#000000" stroke="#000000" points="1103.6446,-199.2421 1113.4048,-195.1203 1103.2045,-192.256 1103.6446,-199.2421"/>
<text text-anchor="middle" x="931" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- survival -->
<g id="node27" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="954" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M965.5695,-261.1979C973.8236,-249.946 985.9264,-236.056 1000,-228 1018.4033,-217.4656 1067.0674,-207.9148 1108.4189,-201.3019"/>
<polygon fill="#000000" stroke="#000000" points="1109.139,-204.7319 1118.4773,-199.7271 1108.0562,-197.8161 1109.139,-204.7319"/>
<text text-anchor="middle" x="1039.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- study_funding -->
<g id="node28" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2770" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2770" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge18" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2746.6847,-87.7311C2729.08,-75.7759 2703.793,-60.8315 2679,-54 2615.6146,-36.5346 1617.6121,-21.7915 1388.589,-18.6275"/>
<polygon fill="#000000" stroke="#000000" points="1388.6275,-15.1278 1378.5803,-18.4898 1388.5312,-22.1271 1388.6275,-15.1278"/>
<text text-anchor="middle" x="2775" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
</g>
</svg>
</div>
