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
<svg width="3150pt" height="305pt"
 viewBox="0.00 0.00 3149.69 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 3145.6908,-301 3145.6908,4 -4,4"/>
<!-- methylation_array_file -->
<g id="node1" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2696.3477" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2696.3477" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- sample -->
<g id="node24" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2338.3477" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2338.3477" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge33" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2669.659,-261.3255C2651.2289,-249.9783 2625.7365,-235.9299 2601.3477,-228 2563.4904,-215.691 2456.9571,-203.6006 2391.678,-197.0393"/>
<polygon fill="#000000" stroke="#000000" points="2391.8695,-193.5412 2381.5722,-196.0345 2391.1768,-200.5068 2391.8695,-193.5412"/>
<text text-anchor="middle" x="2727.8477" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- radiology_file -->
<g id="node2" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="695.3477" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="695.3477" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- participant -->
<g id="node7" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1184.3477" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1184.3477" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M696.1182,-173.8127C697.626,-162.5495 701.539,-148.793 711.3477,-141 741.9228,-116.708 986.8309,-108.6503 1111.6941,-106.1056"/>
<polygon fill="#000000" stroke="#000000" points="1112.0036,-109.6003 1121.9327,-105.9038 1111.8656,-102.6017 1112.0036,-109.6003"/>
<text text-anchor="middle" x="770.3477" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- molecular_test -->
<g id="node3" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1112.3477" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1112.3477" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1106.8363,-173.7117C1104.8325,-163.3656 1104.3325,-150.6156 1110.3477,-141 1115.0856,-133.4261 1121.9242,-127.4044 1129.5543,-122.6284"/>
<polygon fill="#000000" stroke="#000000" points="1131.7013,-125.4436 1138.7968,-117.5757 1128.3434,-119.3015 1131.7013,-125.4436"/>
<text text-anchor="middle" x="1174.3477" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- study -->
<g id="node4" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2299.3477" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2299.3477" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- generic_file -->
<g id="node5" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="91.3477" cy="-279" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="91.3477" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge30" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M68.727,-262.0748C34.2026,-234.2954 -24.0836,-178.3872 11.3477,-141 91.3311,-56.6012 1934.2917,-23.7603 2252.6976,-18.7079"/>
<polygon fill="#000000" stroke="#000000" points="2253.0085,-22.2036 2262.9521,-18.5465 2252.8982,-15.2044 2253.0085,-22.2036"/>
<text text-anchor="middle" x="64.3477" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M86.7559,-260.6661C82.0986,-237.2507 78.3516,-197.0139 100.3477,-174 178.0892,-92.6611 239.2572,-150.7717 351.3477,-141 631.768,-116.5537 966.8094,-108.4745 1111.6903,-106.0028"/>
<polygon fill="#000000" stroke="#000000" points="1111.8495,-109.5008 1121.7897,-105.8344 1111.7327,-102.5017 1111.8495,-109.5008"/>
<text text-anchor="middle" x="153.3477" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M156.6848,-277.2219C402.5801,-270.4143 1295.7774,-244.6404 2031.3477,-210 2120.0772,-205.8214 2223.1442,-199.4715 2284.4358,-195.5374"/>
<polygon fill="#000000" stroke="#000000" points="2284.8886,-199.0156 2294.6429,-194.8798 2284.4385,-192.0301 2284.8886,-199.0156"/>
<text text-anchor="middle" x="1660.3477" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- sequencing_file -->
<g id="node6" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2913.3477" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="2913.3477" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2889.4763,-261.5755C2872.0669,-249.8735 2847.4059,-235.3058 2823.3477,-228 2744.2018,-203.9658 2502.1104,-195.6334 2392.8549,-193.0463"/>
<polygon fill="#000000" stroke="#000000" points="2392.784,-189.5438 2382.7064,-192.8135 2392.6235,-196.542 2392.784,-189.5438"/>
<text text-anchor="middle" x="2922.8477" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge1" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1244.5952,-100.0943C1357.7783,-90.8983 1609.9208,-70.5064 1822.3477,-54 1980.3206,-41.7249 2167.7722,-27.7506 2253.0173,-21.428"/>
<polygon fill="#000000" stroke="#000000" points="2253.427,-24.9073 2263.1408,-20.6775 2252.9094,-17.9265 2253.427,-24.9073"/>
<text text-anchor="middle" x="1872.8477" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- pdx -->
<g id="node8" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2193.3477" cy="-105" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2193.3477" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge26" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2208.3788,-89.6248C2218.912,-79.1506 2233.5238,-65.2061 2247.3477,-54 2253.9448,-48.6522 2261.3021,-43.2497 2268.3581,-38.3138"/>
<polygon fill="#000000" stroke="#000000" points="2270.7868,-40.8923 2277.0547,-32.3503 2266.828,-35.1192 2270.7868,-40.8923"/>
<text text-anchor="middle" x="2271.3477" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2214.8398,-116.7041C2219.8228,-119.0636 2225.1823,-121.3289 2230.3477,-123 2274.5629,-137.3046 2301.7472,-106.9263 2333.3477,-141 2338.9625,-147.0543 2341.1632,-155.4222 2341.6874,-163.6302"/>
<polygon fill="#000000" stroke="#000000" points="2338.1864,-163.7208 2341.5855,-173.7555 2345.1861,-163.7913 2338.1864,-163.7208"/>
<text text-anchor="middle" x="2365.3477" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- cytogenomic_file -->
<g id="node9" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="2302.3477" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="2302.3477" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge29" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2308.6632,-260.9164C2312.197,-251.0994 2316.797,-238.7965 2321.3477,-228 2322.57,-225.1 2323.8953,-222.0929 2325.2482,-219.1083"/>
<polygon fill="#000000" stroke="#000000" points="2328.5288,-220.354 2329.5722,-209.8107 2322.1817,-217.4021 2328.5288,-220.354"/>
<text text-anchor="middle" x="2392.8477" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- survival -->
<g id="node10" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1258.3477" cy="-192" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1258.3477" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1254.0763,-173.6094C1250.9859,-163.2292 1245.9859,-150.4792 1238.3477,-141 1234.0728,-135.6948 1228.8046,-130.8872 1223.2508,-126.6383"/>
<polygon fill="#000000" stroke="#000000" points="1225.1827,-123.718 1214.992,-120.8198 1221.1511,-129.4405 1225.1827,-123.718"/>
<text text-anchor="middle" x="1286.8477" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- cell_line -->
<g id="node11" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2426.3477" cy="-105" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2426.3477" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge25" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2420.8935,-86.7895C2416.8075,-75.9475 2410.2029,-62.6588 2400.3477,-54 2384.5092,-40.0843 2362.9163,-31.4353 2343.7608,-26.1166"/>
<polygon fill="#000000" stroke="#000000" points="2344.5641,-22.7095 2334.0092,-23.6286 2342.8335,-29.4922 2344.5641,-22.7095"/>
<text text-anchor="middle" x="2452.8477" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge24" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2462.9424,-117.3392C2484.3233,-126.55 2504.8561,-140.2304 2492.3477,-156 2479.8298,-171.7816 2431.0713,-181.2989 2391.7274,-186.5483"/>
<polygon fill="#000000" stroke="#000000" points="2391.1757,-183.0901 2381.697,-187.8234 2392.0586,-190.0342 2391.1757,-183.0901"/>
<text text-anchor="middle" x="2536.8477" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- treatment_response -->
<g id="node12" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1429.3477" cy="-192" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1429.3477" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1399.8538,-174.4888C1380.5938,-163.6426 1354.6062,-150.0957 1330.3477,-141 1303.5784,-130.963 1272.995,-122.9254 1246.7592,-117.0134"/>
<polygon fill="#000000" stroke="#000000" points="1247.4524,-113.5823 1236.9339,-114.8519 1245.9483,-120.4188 1247.4524,-113.5823"/>
<text text-anchor="middle" x="1447.3477" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- synonym -->
<g id="node13" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1913.3477" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1913.3477" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge21" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1913.7053,-260.9875C1914.9078,-249.9413 1918.3205,-236.3598 1927.3477,-228 1958.237,-199.3942 1987.1888,-235.9409 2020.3477,-210 2046.9723,-189.171 2026.3286,-162.5806 2052.3477,-141 2077.4045,-120.2175 2095.402,-139.6971 2123.3477,-123 2141.9803,-111.8673 2138.9278,-99.9484 2156.3477,-87 2188.4876,-63.1101 2230.2017,-44.1136 2260.273,-32.1503"/>
<polygon fill="#000000" stroke="#000000" points="2261.5535,-35.4078 2269.6005,-28.516 2259.0121,-28.8854 2261.5535,-35.4078"/>
<text text-anchor="middle" x="2094.8477" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1861.4743,-277.2694C1664.1913,-270.4407 970.0871,-244.065 938.3477,-210 881.9018,-149.4184 1023.443,-122.289 1114.5437,-111.4026"/>
<polygon fill="#000000" stroke="#000000" points="1115.0307,-114.8697 1124.5633,-110.2459 1114.2278,-107.9159 1115.0307,-114.8697"/>
<text text-anchor="middle" x="980.8477" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge23" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1960.5383,-271.1453C2001.6499,-263.8595 2057.8042,-252.7104 2078.3477,-243 2088.0746,-238.4023 2087.4732,-232.2717 2097.3477,-228 2130.1058,-213.829 2224.3842,-202.6987 2284.8507,-196.7573"/>
<polygon fill="#000000" stroke="#000000" points="2285.3696,-200.2236 2294.9869,-195.7787 2284.6968,-193.256 2285.3696,-200.2236"/>
<text text-anchor="middle" x="2139.8477" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study_arm -->
<g id="node14" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2299.3477" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2299.3477" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge20" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2299.3477,-86.9735C2299.3477,-75.1918 2299.3477,-59.5607 2299.3477,-46.1581"/>
<polygon fill="#000000" stroke="#000000" points="2302.8478,-46.0033 2299.3477,-36.0034 2295.8478,-46.0034 2302.8478,-46.0033"/>
<text text-anchor="middle" x="2347.8477" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- treatment -->
<g id="node15" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="1609.3477" cy="-192" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="1609.3477" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1590.1677,-174.9782C1575.8385,-163.3081 1555.2048,-148.6096 1534.3477,-141 1484.9446,-122.9756 1343.6661,-112.9117 1256.4496,-108.2538"/>
<polygon fill="#000000" stroke="#000000" points="1256.5223,-104.7529 1246.3532,-107.7258 1256.1567,-111.7434 1256.5223,-104.7529"/>
<text text-anchor="middle" x="1610.3477" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- clinical_measure_file -->
<g id="node16" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="1793.3477" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="1793.3477" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge11" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1846.5395,-176.0793C1860.1211,-170.7857 1874.2817,-164.1189 1886.3477,-156 1921.3022,-132.48 1914.4857,-107.4013 1951.3477,-87 2002.898,-58.4694 2171.7583,-34.0455 2253.798,-23.5248"/>
<polygon fill="#000000" stroke="#000000" points="2254.3521,-26.9826 2263.8321,-22.2519 2253.4711,-20.0383 2254.3521,-26.9826"/>
<text text-anchor="middle" x="2037.3477" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1757.8241,-174.9891C1731.7496,-163.3243 1695.1379,-148.6276 1661.3477,-141 1586.3482,-124.0701 1370.301,-112.7974 1256.4778,-107.8551"/>
<polygon fill="#000000" stroke="#000000" points="1256.5988,-104.3571 1246.4579,-107.4249 1256.2985,-111.3507 1256.5988,-104.3571"/>
<text text-anchor="middle" x="1796.3477" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- pathology_file -->
<g id="node17" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2486.3477" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2486.3477" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge28" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2482.5932,-260.6086C2479.4597,-249.6986 2473.9093,-236.4018 2464.3477,-228 2452.8319,-217.8812 2418.5226,-208.4394 2388.6095,-201.7661"/>
<polygon fill="#000000" stroke="#000000" points="2389.1873,-198.3102 2378.6728,-199.6122 2387.7043,-205.1513 2389.1873,-198.3102"/>
<text text-anchor="middle" x="2536.3477" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- family_relationship -->
<g id="node18" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="315.3477" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="315.3477" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M331.954,-174.1219C344.0968,-162.3705 361.6533,-147.9305 380.3477,-141 447.7714,-116.0043 926.6507,-107.9297 1111.657,-105.7255"/>
<polygon fill="#000000" stroke="#000000" points="1111.8716,-109.2233 1121.8301,-105.6067 1111.7898,-102.2238 1111.8716,-109.2233"/>
<text text-anchor="middle" x="459.8477" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- medical_history -->
<g id="node19" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="518.3477" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="518.3477" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M528.2235,-174.0412C535.6766,-162.4138 547.0553,-148.1526 561.3477,-141 609.4419,-116.9311 957.732,-108.5416 1111.599,-105.9886"/>
<polygon fill="#000000" stroke="#000000" points="1111.9494,-109.4835 1121.8913,-105.8218 1111.8359,-102.4844 1111.9494,-109.4835"/>
<text text-anchor="middle" x="629.3477" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- study_personnel -->
<g id="node20" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2580.3477" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2580.3477" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge35" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2557.2456,-87.5522C2541.2371,-76.3035 2518.9881,-62.2797 2497.3477,-54 2447.4109,-34.8941 2386.4233,-25.7662 2345.4411,-21.5143"/>
<polygon fill="#000000" stroke="#000000" points="2345.766,-18.0295 2335.4718,-20.5353 2345.0818,-24.996 2345.766,-18.0295"/>
<text text-anchor="middle" x="2595.8477" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- study_admin -->
<g id="node21" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="2755.3477" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2755.3477" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge17" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2732.6042,-87.7292C2716.0001,-76.0997 2692.4453,-61.5553 2669.3477,-54 2610.4625,-34.7385 2431.7934,-24.1197 2346.1292,-20.0138"/>
<polygon fill="#000000" stroke="#000000" points="2346.0643,-16.507 2335.9111,-19.5339 2345.7359,-23.4993 2346.0643,-16.507"/>
<text text-anchor="middle" x="2757.8477" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- diagnosis -->
<g id="node22" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="2089.3477" cy="-279" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="2089.3477" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2041.0416,-270.3352C2007.4921,-263.5753 1966.39,-253.5825 1952.3477,-243 1909.2258,-210.5029 1934.0698,-166.2617 1886.3477,-141 1858.8693,-126.4544 1430.1764,-112.2509 1256.542,-107.0647"/>
<polygon fill="#000000" stroke="#000000" points="1256.5738,-103.5641 1246.4742,-106.7655 1256.3658,-110.5611 1256.5738,-103.5641"/>
<text text-anchor="middle" x="1971.8477" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2126.294,-265.5814C2144.4355,-258.918 2166.5882,-250.6701 2186.3477,-243 2202.8896,-236.5789 2206.6445,-233.9889 2223.3477,-228 2245.8736,-219.9234 2271.2287,-211.8771 2292.3876,-205.4465"/>
<polygon fill="#000000" stroke="#000000" points="2293.5329,-208.7569 2302.0968,-202.5191 2291.5122,-202.0549 2293.5329,-208.7569"/>
<text text-anchor="middle" x="2267.8477" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- exposure -->
<g id="node23" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="840.3477" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="840.3477" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M834.3633,-173.8074C832.0329,-162.9722 831.5225,-149.6842 839.3477,-141 857.2395,-121.1441 1016.2322,-111.5146 1112.0197,-107.4769"/>
<polygon fill="#000000" stroke="#000000" points="1112.3808,-110.9651 1122.2287,-107.0576 1112.0935,-103.971 1112.3808,-110.9651"/>
<text text-anchor="middle" x="882.8477" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2294.87,-188.2085C2258.2877,-183.8381 2205.2339,-174.691 2162.3477,-156 2151.8331,-151.4175 2152.2025,-144.705 2141.3477,-141 2099.7412,-126.7987 1473.4644,-111.4864 1257.165,-106.5956"/>
<polygon fill="#000000" stroke="#000000" points="1256.9484,-103.0899 1246.8721,-106.3637 1256.7907,-110.0881 1256.9484,-103.0899"/>
<text text-anchor="middle" x="2198.8477" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge8" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2306.8027,-179.3128C2292.2782,-173.0031 2275.0453,-164.8405 2260.3477,-156 2245.6912,-147.1842 2230.4368,-135.7738 2218.1925,-125.9819"/>
<polygon fill="#000000" stroke="#000000" points="2220.207,-123.1088 2210.2409,-119.5133 2215.7895,-128.539 2220.207,-123.1088"/>
<text text-anchor="middle" x="2296.8477" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge7" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2370.8468,-179.6047C2382.5938,-173.852 2395.2013,-166.03 2404.3477,-156 2410.3527,-149.4148 2414.8893,-140.9372 2418.235,-132.7919"/>
<polygon fill="#000000" stroke="#000000" points="2421.6056,-133.7647 2421.744,-123.1708 2415.0294,-131.3661 2421.6056,-133.7647"/>
<text text-anchor="middle" x="2451.8477" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- publication -->
<g id="node25" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="2906.3477" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="2906.3477" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge3" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2883.8005,-88.036C2866.7759,-76.2324 2842.3225,-61.3441 2818.3477,-54 2730.8173,-27.1874 2456.4888,-20.265 2346.0729,-18.5449"/>
<polygon fill="#000000" stroke="#000000" points="2345.9618,-15.0429 2335.9109,-18.3941 2345.8579,-22.0422 2345.9618,-15.0429"/>
<text text-anchor="middle" x="2902.3477" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- study_funding -->
<g id="node26" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="3064.3477" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="3064.3477" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge2" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3036.435,-87.9631C3015.4875,-76.1233 2985.6629,-61.2216 2957.3477,-54 2898.6077,-39.0188 2486.1102,-24.168 2345.8798,-19.5004"/>
<polygon fill="#000000" stroke="#000000" points="2345.9837,-16.002 2335.8734,-19.1693 2345.7521,-22.9982 2345.9837,-16.002"/>
<text text-anchor="middle" x="3058.3477" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
</g>
</svg>
</div>
