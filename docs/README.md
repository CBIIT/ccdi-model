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
<svg width="2510pt" height="305pt"
 viewBox="0.00 0.00 2509.69 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 2505.689,-301 2505.689,4 -4,4"/>
<!-- medical_history -->
<g id="node1" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1569.689" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1569.689" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- participant -->
<g id="node23" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1045.689" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1045.689" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1536.6772,-175.3957C1511.3692,-163.5277 1475.209,-148.3988 1441.689,-141 1300.4235,-109.8189 1259.691,-144.8773 1116.689,-123 1111.2681,-122.1707 1105.6588,-121.11 1100.0784,-119.9194"/>
<polygon fill="#000000" stroke="#000000" points="1100.6383,-116.4575 1090.1117,-117.6579 1099.0893,-123.284 1100.6383,-116.4575"/>
<text text-anchor="middle" x="1556.689" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- molecular_test -->
<g id="node2" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1752.689" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1752.689" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1721.0674,-175.319C1696.5922,-163.3274 1661.4534,-148.075 1628.689,-141 1517.4058,-116.9699 1229.3957,-139.0801 1116.689,-123 1111.26,-122.2254 1105.6453,-121.201 1100.0616,-120.033"/>
<polygon fill="#000000" stroke="#000000" points="1100.6144,-116.5701 1090.0909,-117.7982 1099.0833,-123.4006 1100.6144,-116.5701"/>
<text text-anchor="middle" x="1737.689" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- cell_line -->
<g id="node3" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2061.689" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2061.689" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample -->
<g id="node20" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2122.689" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2122.689" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2035.8036,-263.6088C2022.5402,-253.7197 2010.8589,-240.4401 2019.689,-228 2020.1702,-227.3221 2051.1224,-216.5534 2078.9681,-206.9695"/>
<polygon fill="#000000" stroke="#000000" points="2080.3136,-210.2081 2088.6328,-203.6475 2078.0381,-203.5882 2080.3136,-210.2081"/>
<text text-anchor="middle" x="2060.189" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- study -->
<g id="node21" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1045.689" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1045.689" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge8" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2097.5745,-266.5152C2104.8221,-264.377 2112.4423,-262.3978 2119.689,-261 2144.2061,-256.2708 2326.755,-261.3493 2343.689,-243 2348.2103,-238.1008 2346.4219,-234.0807 2343.689,-228 2319.8127,-174.8764 2297.529,-167.5481 2245.689,-141 2088.3898,-60.4446 2032.8676,-77.3377 1857.689,-54 1708.1157,-34.0735 1241.7404,-22.3157 1092.2786,-18.9852"/>
<polygon fill="#000000" stroke="#000000" points="1092.1486,-15.4815 1082.0738,-18.7599 1091.9941,-22.4798 1092.1486,-15.4815"/>
<text text-anchor="middle" x="2314.189" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- treatment_response -->
<g id="node4" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1955.689" cy="-192" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1955.689" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1900.731,-176.6734C1880.9812,-170.751 1858.659,-163.5753 1838.689,-156 1823.6256,-150.286 1821.3887,-144.616 1805.689,-141 1656.4333,-106.6233 1268.4129,-143.9488 1116.689,-123 1111.1779,-122.2391 1105.4768,-121.2125 1099.8116,-120.0333"/>
<polygon fill="#000000" stroke="#000000" points="1100.225,-116.5393 1089.7019,-117.7704 1098.6959,-123.3703 1100.225,-116.5393"/>
<text text-anchor="middle" x="1921.689" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- synonym -->
<g id="node5" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="360.689" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="360.689" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M411.1667,-274.471C453.6946,-270.7038 516.152,-265.2848 570.689,-261 775.913,-244.8761 827.0347,-237.123 1032.689,-228 1147.8153,-222.8929 1956.1573,-229.7665 2069.689,-210 2073.4017,-209.3536 2077.2059,-208.4899 2080.9885,-207.4897"/>
<polygon fill="#000000" stroke="#000000" points="2082.2699,-210.7611 2090.8738,-204.5785 2080.2923,-204.0462 2082.2699,-210.7611"/>
<text text-anchor="middle" x="1075.189" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge6" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M314.1967,-270.6081C209.7053,-250.6359 -31.9159,-197.6938 3.689,-141 33.079,-94.202 62.8593,-103.2128 115.689,-87 283.517,-35.4955 834.3874,-21.7367 998.8957,-18.7336"/>
<polygon fill="#000000" stroke="#000000" points="999.2285,-22.2283 1009.1647,-18.5511 999.104,-15.2295 999.2285,-22.2283"/>
<text text-anchor="middle" x="46.189" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M356.4231,-260.9639C352.1182,-237.8704 348.7517,-197.9812 369.689,-174 391.7079,-148.7799 483.492,-145.3419 516.689,-141 718.6813,-114.5808 773.0784,-152.1901 974.689,-123 980.1163,-122.2142 985.7299,-121.1824 991.313,-120.0097"/>
<polygon fill="#000000" stroke="#000000" points="992.2935,-123.3767 1001.2829,-117.7694 990.7588,-116.547 992.2935,-123.3767"/>
<text text-anchor="middle" x="412.189" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- radiology_file -->
<g id="node6" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="536.689" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="536.689" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M525.6164,-173.7636C520.5891,-162.9119 517.4057,-149.622 525.689,-141 542.9844,-122.9974 949.9835,-126.5869 974.689,-123 980.116,-122.2121 985.7294,-121.1788 991.3124,-120.0052"/>
<polygon fill="#000000" stroke="#000000" points="992.2933,-123.3721 1001.2821,-117.7639 990.7579,-116.5426 992.2933,-123.3721"/>
<text text-anchor="middle" x="584.689" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- generic_file -->
<g id="node7" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="645.689" cy="-279" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="645.689" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M708.4912,-273.5212C832.4847,-262.9214 1117.5505,-239.6297 1357.689,-228 1515.7765,-220.344 1913.8706,-237.7651 2069.689,-210 2073.3991,-209.3389 2077.2015,-208.465 2080.983,-207.458"/>
<polygon fill="#000000" stroke="#000000" points="2082.2689,-210.7276 2090.8663,-204.5361 2080.2843,-204.0148 2082.2689,-210.7276"/>
<text text-anchor="middle" x="1410.689" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge12" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M583.1429,-273.3401C442.7713,-260.3404 113.6352,-228.0799 97.689,-210 77.3508,-186.9405 83.7141,-165.1937 102.689,-141 141.5525,-91.4475 172.5065,-101.9173 233.689,-87 380.6731,-51.1628 848.7853,-27.0469 998.8889,-20.0796"/>
<polygon fill="#000000" stroke="#000000" points="999.3096,-23.5641 1009.138,-19.6077 998.9876,-16.5715 999.3096,-23.5641"/>
<text text-anchor="middle" x="155.689" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M641.3007,-260.8552C636.8635,-237.6442 633.3541,-197.6283 654.689,-174 702.9469,-120.5546 903.9155,-136.2796 974.689,-123 979.7156,-122.0568 984.9152,-120.9657 990.1094,-119.7965"/>
<polygon fill="#000000" stroke="#000000" points="991.106,-123.1579 1000.0446,-117.4699 989.51,-116.3422 991.106,-123.1579"/>
<text text-anchor="middle" x="707.689" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- cytogenomic_file -->
<g id="node8" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="2218.689" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="2218.689" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2209.8126,-260.946C2204.0012,-250.4277 2195.647,-237.4233 2185.689,-228 2178.5585,-221.2524 2169.9312,-215.2769 2161.3792,-210.2287"/>
<polygon fill="#000000" stroke="#000000" points="2162.9985,-207.1243 2152.5602,-205.3101 2159.5889,-213.2378 2162.9985,-207.1243"/>
<text text-anchor="middle" x="2268.189" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- study_funding -->
<g id="node9" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="744.689" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="744.689" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge17" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M758.4256,-86.92C768.1074,-75.5509 782.0905,-61.6345 797.689,-54 832.2282,-37.0952 937.3185,-26.3711 999.0569,-21.3525"/>
<polygon fill="#000000" stroke="#000000" points="999.6227,-24.8187 1009.3145,-20.5387 999.069,-17.8406 999.6227,-24.8187"/>
<text text-anchor="middle" x="859.689" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- publication -->
<g id="node10" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="902.689" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="902.689" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge28" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M912.1417,-86.7258C918.5927,-75.8599 928.0667,-62.5684 939.689,-54 957.7553,-40.6808 981.0938,-32.0524 1001.2709,-26.5931"/>
<polygon fill="#000000" stroke="#000000" points="1002.3471,-29.9313 1011.1862,-24.0901 1000.6337,-23.1442 1002.3471,-29.9313"/>
<text text-anchor="middle" x="990.689" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- clinical_measure_file -->
<g id="node11" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="215.689" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="215.689" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge23" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M211.7138,-173.9154C210.4524,-163.1208 211.01,-149.8376 218.689,-141 298.3829,-49.2812 366.7519,-106.4565 486.689,-87 676.2491,-56.249 903.9447,-32.0719 999.7083,-22.4795"/>
<polygon fill="#000000" stroke="#000000" points="1000.3093,-25.9371 1009.9129,-21.4627 999.6151,-18.9716 1000.3093,-25.9371"/>
<text text-anchor="middle" x="572.689" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M217.0343,-173.8323C218.9207,-162.4262 223.3549,-148.5014 233.689,-141 267.0136,-116.8098 933.892,-128.5948 974.689,-123 980.2008,-122.2441 985.9023,-121.2209 991.5678,-120.0437"/>
<polygon fill="#000000" stroke="#000000" points="992.6825,-123.381 1001.6778,-117.7832 991.155,-116.5497 992.6825,-123.381"/>
<text text-anchor="middle" x="319.689" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- study_personnel -->
<g id="node12" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="1212.689" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1212.689" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge30" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1194.7128,-87.253C1182.9755,-76.451 1166.8732,-63.0385 1150.689,-54 1131.2583,-43.1484 1107.9899,-34.7611 1088.3009,-28.8232"/>
<polygon fill="#000000" stroke="#000000" points="1089.2432,-25.4524 1078.6638,-26.0233 1087.2901,-32.1744 1089.2432,-25.4524"/>
<text text-anchor="middle" x="1241.189" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- sequencing_file -->
<g id="node13" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2409.689" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="2409.689" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2391.9596,-261.3074C2379.5082,-249.9524 2361.8858,-235.902 2343.689,-228 2314.3173,-215.2452 2231.2237,-203.9977 2175.7166,-197.5998"/>
<polygon fill="#000000" stroke="#000000" points="2176.0233,-194.1122 2165.6924,-196.4623 2175.234,-201.0676 2176.0233,-194.1122"/>
<text text-anchor="middle" x="2435.189" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- exposure -->
<g id="node14" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="822.689" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="822.689" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M825.4756,-173.8904C828.1832,-162.6591 833.464,-148.909 843.689,-141 866.9319,-123.0217 945.8466,-128.6194 974.689,-123 979.7089,-122.022 984.904,-120.907 990.0952,-119.7222"/>
<polygon fill="#000000" stroke="#000000" points="991.0995,-123.0813 1000.0265,-117.3754 989.4896,-116.2689 991.0995,-123.0813"/>
<text text-anchor="middle" x="887.189" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- study_admin -->
<g id="node15" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1387.689" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1387.689" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge21" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1368.4303,-87.6664C1354.5139,-76.1648 1334.7133,-61.7995 1314.689,-54 1275.0974,-38.5791 1157.7807,-27.0187 1091.9033,-21.5331"/>
<polygon fill="#000000" stroke="#000000" points="1092.0442,-18.033 1081.7919,-20.7052 1091.4729,-25.0097 1092.0442,-18.033"/>
<text text-anchor="middle" x="1398.189" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- treatment -->
<g id="node16" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="951.689" cy="-192" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="951.689" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M939.7809,-174.1348C934.429,-163.6834 930.7097,-150.6832 937.689,-141 941.1959,-136.1343 965.6592,-127.7889 990.4168,-120.3577"/>
<polygon fill="#000000" stroke="#000000" points="991.6433,-123.645 1000.2432,-117.4569 989.6614,-116.9314 991.6433,-123.645"/>
<text text-anchor="middle" x="984.689" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- pdx -->
<g id="node17" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1823.689" cy="-105" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1823.689" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1844.6549,-116.9768C1849.7538,-119.3841 1855.2955,-121.6014 1860.689,-123 1896.1272,-132.1893 2164.5187,-114.415 2189.689,-141 2202.4138,-154.4401 2186.164,-167.0606 2166.487,-176.3847"/>
<polygon fill="#000000" stroke="#000000" points="2165.0407,-173.1972 2157.2968,-180.428 2167.8596,-179.6046 2165.0407,-173.1972"/>
<text text-anchor="middle" x="2217.689" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge32" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1796.278,-100.674C1735.5847,-91.2046 1585.206,-68.3431 1458.689,-54 1326.0112,-38.9584 1168.7322,-26.8112 1092.1906,-21.263"/>
<polygon fill="#000000" stroke="#000000" points="1092.1628,-17.752 1081.9371,-20.5243 1091.6597,-24.7339 1092.1628,-17.752"/>
<text text-anchor="middle" x="1592.689" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- methylation_array_file -->
<g id="node18" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1663.689" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1663.689" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge24" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1668.6058,-260.9359C1672.7573,-249.4196 1679.9509,-235.3289 1691.689,-228 1727.3554,-205.731 2028.3783,-217.8375 2069.689,-210 2073.3408,-209.3072 2077.0846,-208.4195 2080.8113,-207.4108"/>
<polygon fill="#000000" stroke="#000000" points="2081.9756,-210.716 2090.5613,-204.5083 2079.9783,-204.007 2081.9756,-210.716"/>
<text text-anchor="middle" x="1783.189" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study_arm -->
<g id="node19" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1929.689" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1929.689" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1885.6976,-92.6937C1877.4285,-90.6171 1868.8249,-88.6147 1860.689,-87 1755.0784,-66.0407 1727.8258,-64.7046 1620.689,-54 1424.7932,-34.427 1190.2216,-23.6705 1092.2496,-19.7438"/>
<polygon fill="#000000" stroke="#000000" points="1092.2233,-16.2401 1082.0927,-19.3416 1091.9464,-23.2346 1092.2233,-16.2401"/>
<text text-anchor="middle" x="1805.189" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge20" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2117.0399,-209.9461C2113.3235,-220.1781 2107.8235,-232.9281 2100.689,-243 2097.638,-247.3071 2093.9998,-251.489 2090.1899,-255.3863"/>
<polygon fill="#000000" stroke="#000000" points="2087.5709,-253.0479 2082.7609,-262.488 2092.408,-258.1079 2087.5709,-253.0479"/>
<text text-anchor="middle" x="2145.189" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge18" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2119.7586,-173.9047C2116.91,-162.5292 2111.3685,-148.6113 2100.689,-141 2057.1354,-109.9593 1912.3216,-136.9468 1860.689,-123 1858.5037,-122.4097 1856.2926,-121.6898 1854.0954,-120.8814"/>
<polygon fill="#000000" stroke="#000000" points="1855.2493,-117.5693 1844.6758,-116.8979 1852.5228,-124.0165 1855.2493,-117.5693"/>
<text text-anchor="middle" x="2149.189" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2088.9061,-180.3124C2062.6387,-171.1249 2029.6794,-159.3392 2023.689,-156 2014.2915,-150.7616 2014.8165,-144.6313 2004.689,-141 1911.7931,-107.6914 1214.4875,-136.2118 1116.689,-123 1111.1756,-122.2552 1105.4731,-121.2393 1099.8071,-120.0666"/>
<polygon fill="#000000" stroke="#000000" points="1100.2185,-116.5724 1089.6963,-117.8113 1098.6945,-123.4045 1100.2185,-116.5724"/>
<text text-anchor="middle" x="2060.189" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- diagnosis -->
<g id="node22" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1260.689" cy="-279" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1260.689" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1307.8055,-269.7469C1370.5032,-257.8513 1484.946,-237.5894 1583.689,-228 1798.8249,-207.1072 1857.1191,-249.1668 2069.689,-210 2073.3444,-209.3265 2077.0907,-208.4524 2080.8191,-207.4527"/>
<polygon fill="#000000" stroke="#000000" points="2081.9773,-210.76 2090.5718,-204.5645 2079.9896,-204.0481 2081.9773,-210.76"/>
<text text-anchor="middle" x="1628.189" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1213.7552,-269.5079C1159.3449,-257.4873 1074.5688,-235.2714 1054.689,-210 1037.7948,-188.5239 1037.5493,-156.3696 1040.277,-133.3055"/>
<polygon fill="#000000" stroke="#000000" points="1043.784,-133.5062 1041.7423,-123.1099 1036.8552,-132.5103 1043.784,-133.5062"/>
<text text-anchor="middle" x="1099.189" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge15" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1045.689,-86.9735C1045.689,-75.1918 1045.689,-59.5607 1045.689,-46.1581"/>
<polygon fill="#000000" stroke="#000000" points="1049.1891,-46.0033 1045.689,-36.0034 1042.1891,-46.0034 1049.1891,-46.0033"/>
<text text-anchor="middle" x="1096.189" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- family_relationship -->
<g id="node24" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1252.689" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1252.689" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1213.2666,-175.4312C1178.2704,-160.7226 1127.1602,-139.2415 1090.5975,-123.8746"/>
<polygon fill="#000000" stroke="#000000" points="1091.741,-120.5587 1081.166,-119.9106 1089.0287,-127.0119 1091.741,-120.5587"/>
<text text-anchor="middle" x="1240.189" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- survival -->
<g id="node25" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1418.689" cy="-192" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1418.689" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1395.6497,-176.168C1377.0966,-164.2978 1349.8804,-148.8076 1323.689,-141 1235.1902,-114.6186 1207.7435,-138.3972 1116.689,-123 1111.3602,-122.0989 1105.8439,-121.0009 1100.3492,-119.7962"/>
<polygon fill="#000000" stroke="#000000" points="1101.0579,-116.3679 1090.5272,-117.532 1099.4854,-123.189 1101.0579,-116.3679"/>
<text text-anchor="middle" x="1398.189" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- pathology_file -->
<g id="node26" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1873.689" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1873.689" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge34" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1874.5219,-260.8902C1876.0552,-249.6588 1879.9734,-235.9087 1889.689,-228 1920.8651,-202.6219 2030.4025,-218.5189 2069.689,-210 2073.2711,-209.2233 2076.9482,-208.2846 2080.6145,-207.2487"/>
<polygon fill="#000000" stroke="#000000" points="2081.6748,-210.5846 2090.2217,-204.3237 2079.6359,-203.8881 2081.6748,-210.5846"/>
<text text-anchor="middle" x="1950.689" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
</g>
</svg>
</div>
