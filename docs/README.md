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
<svg width="3214pt" height="392pt"
 viewBox="0.00 0.00 3213.69 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3209.6897,-388 3209.6897,4 -4,4"/>
<!-- pathology_file -->
<g id="node1" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="325.6897" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="325.6897" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- sample -->
<g id="node25" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="812.6897" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="812.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge38" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M342.0775,-348.3561C354.0504,-336.7122 371.3418,-322.3043 389.6897,-315 455.2468,-288.9017 659.373,-281.7044 758.1102,-279.7343"/>
<polygon fill="#000000" stroke="#000000" points="758.254,-283.2323 768.1861,-279.5441 758.1218,-276.2335 758.254,-283.2323"/>
<text text-anchor="middle" x="450.6897" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- sequencing_file -->
<g id="node2" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="700.6897" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="700.6897" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M682.9597,-347.9442C675.0496,-337.6756 669.0496,-324.9256 676.6897,-315 687.0857,-301.4941 726.5666,-292.0147 760.3305,-286.1856"/>
<polygon fill="#000000" stroke="#000000" points="761.2901,-289.5747 770.5869,-284.4934 760.1505,-282.6681 761.2901,-289.5747"/>
<text text-anchor="middle" x="743.1897" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- study_admin -->
<g id="node3" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="456.6897" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="456.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study -->
<g id="node28" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1109.6897" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1109.6897" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge19" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M461.6303,-86.9737C465.7921,-75.4738 472.9883,-61.3872 484.6897,-54 509.0663,-38.6109 922.4208,-24.0001 1063.1841,-19.45"/>
<polygon fill="#000000" stroke="#000000" points="1063.3469,-22.9467 1073.2294,-19.1275 1063.1222,-15.9503 1063.3469,-22.9467"/>
<text text-anchor="middle" x="541.1897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- methylation_array_file -->
<g id="node4" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="115.6897" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="115.6897" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M131.331,-347.9458C142.6323,-336.2758 158.9741,-322.0029 176.6897,-315 229.9318,-293.9535 613.1488,-283.4012 757.7,-280.1362"/>
<polygon fill="#000000" stroke="#000000" points="758.1753,-283.6265 768.0948,-279.9047 758.0194,-276.6283 758.1753,-283.6265"/>
<text text-anchor="middle" x="268.1897" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- treatment_response -->
<g id="node5" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="2473.6897" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="2473.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- participant -->
<g id="node15" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1832.6897" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1832.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2423.3084,-263.2201C2384.2433,-251.6217 2328.5411,-236.4637 2278.6897,-228 2148.2946,-205.8616 1994.0683,-197.2469 1905.3864,-193.9597"/>
<polygon fill="#000000" stroke="#000000" points="1905.2853,-190.454 1895.1664,-193.5938 1905.0348,-197.4495 1905.2853,-190.454"/>
<text text-anchor="middle" x="2431.6897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- publication -->
<g id="node6" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="607.6897" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="607.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge3" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M602.5019,-86.6626C600.6277,-75.7729 600.6421,-62.4785 608.6897,-54 624.2029,-37.6563 941.3573,-24.2332 1062.8749,-19.6713"/>
<polygon fill="#000000" stroke="#000000" points="1063.1262,-23.1645 1072.9892,-19.2951 1062.866,-16.1693 1063.1262,-23.1645"/>
<text text-anchor="middle" x="659.6897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- diagnosis -->
<g id="node7" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1873.6897" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1873.6897" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1926.315,-360.8311C1966.4068,-355.6778 2016.8416,-346.1508 2029.6897,-330 2037.9389,-319.6304 2067.4193,-277.1922 2023.6897,-228 2007.8875,-210.2237 1951.5697,-201.1086 1904.1501,-196.5062"/>
<polygon fill="#000000" stroke="#000000" points="1904.4623,-193.0202 1894.1841,-195.5911 1903.8221,-199.9909 1904.4623,-193.0202"/>
<text text-anchor="middle" x="2091.1897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge28" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1820.4194,-361.7297C1705.2199,-352.5618 1424.2966,-330.566 1188.6897,-315 1050.0946,-305.8433 1013.68,-319.9372 876.6897,-297 870.4145,-295.9493 863.8742,-294.5165 857.474,-292.9148"/>
<polygon fill="#000000" stroke="#000000" points="858.1535,-289.474 847.5901,-290.2896 856.3565,-296.2394 858.1535,-289.474"/>
<text text-anchor="middle" x="1440.1897" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- radiology_file -->
<g id="node8" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="2669.6897" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="2669.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2632.9112,-263.4158C2602.7971,-251.433 2558.7758,-235.6709 2518.6897,-228 2402.8968,-205.8418 2056.7997,-196.4371 1905.1869,-193.303"/>
<polygon fill="#000000" stroke="#000000" points="1905.1183,-189.801 1895.0492,-193.0968 1904.9759,-196.7996 1905.1183,-189.801"/>
<text text-anchor="middle" x="2632.6897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- pdx -->
<g id="node9" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="718.6897" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="718.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M726.5649,-209.5905C731.953,-220.1991 739.8887,-233.4603 749.6897,-243 756.6576,-249.7821 765.151,-255.7471 773.6165,-260.7713"/>
<polygon fill="#000000" stroke="#000000" points="771.9268,-263.8365 782.3633,-265.6613 775.3427,-257.7264 771.9268,-263.8365"/>
<text text-anchor="middle" x="773.6897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge30" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M719.6783,-173.6136C721.8788,-150.5143 728.9574,-111.0005 751.6897,-87 793.7255,-42.6192 976.1217,-25.9296 1063.1495,-20.4097"/>
<polygon fill="#000000" stroke="#000000" points="1063.5063,-23.8945 1073.2741,-19.7908 1063.0791,-16.9075 1063.5063,-23.8945"/>
<text text-anchor="middle" x="775.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- synonym -->
<g id="node10" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2774.6897" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2774.6897" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge36" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2774.9684,-347.8997C2774.4304,-325.4566 2770.5211,-286.993 2751.6897,-261 2734.7409,-237.6055 2723.3962,-236.1805 2695.6897,-228 2621.0263,-205.9553 2099.6416,-195.9867 1905.3973,-193.008"/>
<polygon fill="#000000" stroke="#000000" points="1905.3413,-189.5069 1895.2893,-192.8548 1905.2351,-196.5061 1905.3413,-189.5069"/>
<text text-anchor="middle" x="2810.1897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge35" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2722.6726,-364.3647C2575.5738,-359.6846 2144.0157,-345.5695 1785.6897,-330 1653.6461,-324.2626 1620.7526,-320.2764 1488.6897,-315 1352.7394,-309.5682 1011.1842,-317.5725 876.6897,-297 870.3254,-296.0265 863.6959,-294.6226 857.2191,-293.0222"/>
<polygon fill="#000000" stroke="#000000" points="857.7894,-289.5527 847.2268,-290.3789 855.9992,-296.3199 857.7894,-289.5527"/>
<text text-anchor="middle" x="1828.1897" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge37" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2814.1711,-354.261C2876.7379,-335.5691 2991.9316,-300.7556 2994.6897,-297 3004.1604,-284.104 3005.2209,-273.0456 2994.6897,-261 2869.2516,-117.5231 1435.0168,-35.1033 1156.4145,-20.3897"/>
<polygon fill="#000000" stroke="#000000" points="1156.4155,-16.885 1146.2457,-19.8557 1156.0484,-23.8754 1156.4155,-16.885"/>
<text text-anchor="middle" x="2926.1897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study_personnel -->
<g id="node11" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="994.6897" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="994.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge6" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M968.8348,-87.5751C957.2674,-77.6302 947.9833,-64.9928 956.6897,-54 969.8595,-37.3718 1023.4605,-27.663 1063.5285,-22.602"/>
<polygon fill="#000000" stroke="#000000" points="1064.1385,-26.0539 1073.6488,-21.3845 1063.3023,-19.104 1064.1385,-26.0539"/>
<text text-anchor="middle" x="1026.1897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- genetic_analysis -->
<g id="node12" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="1315.6897" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="1315.6897" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1339.7616,-348.6245C1358.049,-335.1208 1383.5691,-315.6157 1404.6897,-297 1421.6647,-282.0383 1420.6174,-271.4452 1440.6897,-261 1495.7491,-232.3483 1666.5649,-209.9308 1763.5654,-199.1069"/>
<polygon fill="#000000" stroke="#000000" points="1764.0225,-202.5778 1773.578,-198.0015 1763.2543,-195.6201 1764.0225,-202.5778"/>
<text text-anchor="middle" x="1510.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1239.8342,-356.8492C1151.9187,-345.6045 1002.9414,-324.5747 876.6897,-297 870.6216,-295.6747 864.2767,-294.1112 858.0395,-292.4682"/>
<polygon fill="#000000" stroke="#000000" points="858.9499,-289.0887 848.382,-289.8437 857.1141,-295.8437 858.9499,-289.0887"/>
<text text-anchor="middle" x="1114.6897" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- exposure -->
<g id="node13" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1342.6897" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1342.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1337.5071,-260.6675C1335.6349,-249.7797 1335.6495,-236.4856 1343.6897,-228 1357.795,-213.1135 1627.8173,-200.2375 1760.4289,-194.7821"/>
<polygon fill="#000000" stroke="#000000" points="1760.6576,-198.2758 1770.5066,-194.3709 1760.3722,-191.2816 1760.6576,-198.2758"/>
<text text-anchor="middle" x="1387.1897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- clinical_measure_file -->
<g id="node14" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="994.6897" cy="-279" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="994.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1049.1171,-263.4155C1066.0016,-257.8175 1084.4353,-250.905 1100.6897,-243 1111.6647,-237.6626 1112.0836,-231.7731 1123.6897,-228 1182.9883,-208.7224 1591.5751,-197.4268 1760.1766,-193.5399"/>
<polygon fill="#000000" stroke="#000000" points="1760.2865,-197.0384 1770.2039,-193.311 1760.1266,-190.0402 1760.2865,-197.0384"/>
<text text-anchor="middle" x="1209.6897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge20" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M997.394,-260.8862C999.3574,-250.836 1002.5863,-238.3201 1007.6897,-228 1034.0582,-174.6777 1066.2188,-177.2194 1090.6897,-123 1101.7074,-98.5885 1106.3406,-68.2613 1108.2865,-46.4858"/>
<polygon fill="#000000" stroke="#000000" points="1111.7963,-46.4864 1109.0605,-36.2509 1104.8162,-45.9585 1111.7963,-46.4864"/>
<text text-anchor="middle" x="1166.6897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- consent_group -->
<g id="node16" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1216.6897" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1216.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge23" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1774.005,-185.6627C1676.4765,-174.8295 1474.9918,-151.1689 1305.6897,-123 1299.003,-121.8874 1292.0517,-120.6408 1285.1131,-119.3365"/>
<polygon fill="#000000" stroke="#000000" points="1285.4695,-115.8411 1274.989,-117.3932 1284.1499,-122.7156 1285.4695,-115.8411"/>
<text text-anchor="middle" x="1572.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge2" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1195.2939,-87.6033C1178.4757,-73.9288 1154.9409,-54.793 1136.8036,-40.0458"/>
<polygon fill="#000000" stroke="#000000" points="1138.8605,-37.2073 1128.8935,-33.6143 1134.4444,-42.6386 1138.8605,-37.2073"/>
<text text-anchor="middle" x="1232.1897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- study_funding -->
<g id="node17" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="1391.6897" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="1391.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge33" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1366.1769,-87.9407C1348.2743,-76.7148 1323.3919,-62.5638 1299.6897,-54 1252.1542,-36.825 1194.8197,-27.4004 1155.6504,-22.5503"/>
<polygon fill="#000000" stroke="#000000" points="1155.9478,-19.0611 1145.6048,-21.3573 1155.1223,-26.0122 1155.9478,-19.0611"/>
<text text-anchor="middle" x="1392.6897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- laboratory_test -->
<g id="node18" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1012.6897" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1012.6897" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1069.9843,-353.0525C1093.8993,-346.6275 1118.1103,-338.4443 1126.6897,-330 1149.728,-307.3245 1124.6738,-281.4729 1149.6897,-261 1174.9878,-240.2962 1264.0478,-251.2115 1295.6897,-243 1312.8652,-238.5427 1315.4066,-232.0197 1332.6897,-228 1411.8651,-209.5854 1641.728,-198.8763 1760.2035,-194.4325"/>
<polygon fill="#000000" stroke="#000000" points="1760.4086,-197.9274 1770.2723,-194.0598 1760.1496,-190.9322 1760.4086,-197.9274"/>
<text text-anchor="middle" x="1215.1897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M938.2566,-358.3495C896.167,-352.6548 848.8144,-343.5056 832.6897,-330 825.6675,-324.1184 821.0983,-315.4437 818.1302,-306.9101"/>
<polygon fill="#000000" stroke="#000000" points="821.4482,-305.783 815.3304,-297.1329 814.7187,-307.7101 821.4482,-305.783"/>
<text text-anchor="middle" x="898.1897" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- medical_history -->
<g id="node19" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1674.6897" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1674.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge39" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1675.2609,-260.6574C1676.5707,-249.7658 1680.022,-236.4712 1688.6897,-228 1700.1721,-216.7779 1734.5943,-207.9512 1766.9037,-201.8467"/>
<polygon fill="#000000" stroke="#000000" points="1767.6231,-205.2733 1776.8351,-200.04 1766.3701,-198.3864 1767.6231,-205.2733"/>
<text text-anchor="middle" x="1756.6897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- survival -->
<g id="node20" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1825.6897" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1825.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1827.1401,-260.9735C1828.0881,-249.1918 1829.3458,-233.5607 1830.4241,-220.1581"/>
<polygon fill="#000000" stroke="#000000" points="1833.9278,-220.2519 1831.2412,-210.0034 1826.9504,-219.6904 1833.9278,-220.2519"/>
<text text-anchor="middle" x="1868.1897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- treatment -->
<g id="node21" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="1949.6897" cy="-279" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="1949.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1939.5634,-261.1377C1932.7806,-250.4268 1923.032,-237.1535 1911.6897,-228 1902.979,-220.9702 1892.6738,-214.9895 1882.4323,-210.0407"/>
<polygon fill="#000000" stroke="#000000" points="1883.6434,-206.7464 1873.0922,-205.7855 1880.7412,-213.1164 1883.6434,-206.7464"/>
<text text-anchor="middle" x="1972.6897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- generic_file -->
<g id="node22" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="2910.6897" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="2910.6897" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2906.3101,-347.8411C2899.6599,-324.2353 2884.7169,-283.3901 2856.6897,-261 2810.7891,-224.3314 2786.8118,-236.5607 2728.6897,-228 2570.5369,-204.7058 2089.5077,-195.6178 1905.4151,-192.934"/>
<polygon fill="#000000" stroke="#000000" points="1905.3459,-189.4328 1895.2966,-192.7886 1905.2453,-196.4321 1905.3459,-189.4328"/>
<text text-anchor="middle" x="2937.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2864.1556,-353.2974C2854.7944,-351.1772 2844.978,-349.2603 2835.6897,-348 2410.4469,-290.2997 2299.6827,-326.2186 1870.6897,-315 1760.2649,-312.1123 985.9749,-313.0853 876.6897,-297 870.32,-296.0625 863.6875,-294.6789 857.2092,-293.0881"/>
<polygon fill="#000000" stroke="#000000" points="857.7778,-289.6185 847.2158,-290.4523 855.9924,-296.387 857.7778,-289.6185"/>
<text text-anchor="middle" x="2726.6897" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge9" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2959.3619,-353.8098C3015.3613,-338.3269 3099.6897,-309.8843 3099.6897,-279 3099.6897,-279 3099.6897,-279 3099.6897,-105 3099.6897,-78.0021 3090.2857,-67.1195 3066.6897,-54 3023.6012,-30.0425 1449.5717,-19.9327 1156.431,-18.2557"/>
<polygon fill="#000000" stroke="#000000" points="1156.1751,-14.7543 1146.1553,-18.1974 1156.1353,-21.7542 1156.1751,-14.7543"/>
<text text-anchor="middle" x="3152.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- study_arm -->
<g id="node23" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="3011.6897" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="3011.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge18" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2993.2821,-87.7074C2979.2406,-75.7406 2958.779,-60.7918 2937.6897,-54 2850.4822,-25.9147 1433.4036,-19.2058 1156.4264,-18.1603"/>
<polygon fill="#000000" stroke="#000000" points="1156.3255,-14.66 1146.3126,-18.1228 1156.2995,-21.66 1156.3255,-14.66"/>
<text text-anchor="middle" x="3014.1897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- cell_line -->
<g id="node24" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="813.6897" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="813.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M848.8986,-204.7024C867.6373,-213.6304 885.0639,-226.8466 875.6897,-243 870.9999,-251.0814 863.7391,-257.5019 855.7908,-262.5456"/>
<polygon fill="#000000" stroke="#000000" points="853.9901,-259.5427 846.9854,-267.4916 857.4182,-265.6458 853.9901,-259.5427"/>
<text text-anchor="middle" x="918.1897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge16" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M808.4124,-173.777C802.9785,-150.8504 797.8197,-111.5188 817.6897,-87 848.2692,-49.2662 989.2382,-29.893 1063.5479,-22.1537"/>
<polygon fill="#000000" stroke="#000000" points="1063.9762,-25.6283 1073.5725,-21.1381 1063.2706,-18.6639 1063.9762,-25.6283"/>
<text text-anchor="middle" x="858.1897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge11" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M768.9711,-276.2889C722.1118,-272.3634 652.2076,-263.2156 635.6897,-243 619.1051,-222.7027 653.0204,-208.2896 682.3693,-200.0751"/>
<polygon fill="#000000" stroke="#000000" points="683.2853,-203.4533 692.0679,-197.5274 681.5067,-196.683 683.2853,-203.4533"/>
<text text-anchor="middle" x="672.1897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M848.7924,-268.3844C857.8675,-265.8434 867.6091,-263.2246 876.6897,-261 914.6186,-251.7083 924.6125,-251.6637 962.6897,-243 989.9127,-236.806 996.0551,-231.9731 1023.6897,-228 1164.6659,-207.7315 1589.242,-196.9959 1760.2019,-193.3996"/>
<polygon fill="#000000" stroke="#000000" points="1760.4323,-196.8956 1770.3572,-193.1881 1760.2864,-189.8971 1760.4323,-196.8956"/>
<text text-anchor="middle" x="1060.1897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge13" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M806.1371,-261.131C803.3314,-251.3768 801.0369,-239.0655 802.6897,-228 803.0922,-225.3055 803.6553,-222.5339 804.316,-219.7819"/>
<polygon fill="#000000" stroke="#000000" points="807.7088,-220.6449 807.0242,-210.0722 800.9662,-218.7642 807.7088,-220.6449"/>
<text text-anchor="middle" x="839.1897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cytogenomic_file -->
<g id="node26" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="509.6897" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="509.6897" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge24" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M510.5897,-347.9716C512.1506,-336.7736 516.0742,-323.0301 525.6897,-315 543.2114,-300.3674 680.6395,-288.359 758.7957,-282.6293"/>
<polygon fill="#000000" stroke="#000000" points="759.2265,-286.1074 768.9482,-281.8959 758.722,-279.1256 759.2265,-286.1074"/>
<text text-anchor="middle" x="597.1897" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- family_relationship -->
<g id="node27" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="2250.6897" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="2250.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2198.193,-263.6111C2159.5717,-252.6615 2105.6674,-238.1508 2057.6897,-228 2004.9771,-216.8474 1944.6665,-207.3718 1899.7632,-200.9456"/>
<polygon fill="#000000" stroke="#000000" points="1900.2416,-197.4786 1889.8494,-199.5405 1899.2592,-204.4093 1900.2416,-197.4786"/>
<text text-anchor="middle" x="2195.1897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
</g>
</svg>
</div>
