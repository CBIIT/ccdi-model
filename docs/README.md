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
<svg width="2897pt" height="305pt"
 viewBox="0.00 0.00 2896.64 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 2892.6363,-301 2892.6363,4 -4,4"/>
<!-- family_relationship -->
<g id="node1" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1240.5919" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1240.5919" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- participant -->
<g id="node12" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1069.5919" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1069.5919" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1215.7427,-174.415C1200.3067,-163.9375 1179.8086,-150.8128 1160.5919,-141 1147.5635,-134.3472 1133.005,-128.0972 1119.4193,-122.7316"/>
<polygon fill="#000000" stroke="#000000" points="1120.3239,-119.3289 1109.7345,-118.9878 1117.7999,-125.8581 1120.3239,-119.3289"/>
<text text-anchor="middle" x="1264.0919" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- radiology_file -->
<g id="node2" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1556.5919" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1556.5919" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1500.6521,-180.2635C1459.1401,-171.3833 1408.1433,-160.0491 1398.5919,-156 1387.3558,-151.2367 1387.0664,-145.1561 1375.5919,-141 1333.8366,-125.8761 1217.5135,-115.2261 1140.9203,-109.609"/>
<polygon fill="#000000" stroke="#000000" points="1141.0802,-106.1116 1130.8543,-108.8829 1140.5765,-113.0934 1141.0802,-106.1116"/>
<text text-anchor="middle" x="1457.5919" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- synonym -->
<g id="node3" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="71.5919" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="71.5919" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- sample -->
<g id="node8" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1927.5919" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1927.5919" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M123.745,-277.0548C418.5517,-266.0531 1863.5281,-212.0456 1874.5919,-210 1878.2469,-209.3242 1881.9929,-208.4485 1885.7211,-207.4478"/>
<polygon fill="#000000" stroke="#000000" points="1886.88,-210.7549 1895.4735,-204.558 1884.8912,-204.0433 1886.88,-210.7549"/>
<text text-anchor="middle" x="1427.0919" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M67.0647,-260.7273C62.4773,-237.3781 58.8057,-197.2128 80.5919,-174 148.2542,-101.907 202.193,-150.6577 300.5919,-141 555.6521,-115.9663 860.0679,-108.2369 996.7961,-105.934"/>
<polygon fill="#000000" stroke="#000000" points="997.1956,-109.428 1007.137,-105.7648 997.0811,-102.429 997.1956,-109.428"/>
<text text-anchor="middle" x="123.0919" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study -->
<g id="node23" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2126.5919" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2126.5919" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge8" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M53.569,-262.0828C25.5607,-233.8146 -21.8852,-176.5802 11.5919,-141 120.4444,-25.3089 1279.9961,-62.9837 1438.5919,-54 1679.7944,-40.337 1968.6746,-25.8234 2079.8429,-20.307"/>
<polygon fill="#000000" stroke="#000000" points="2080.2243,-23.7925 2090.0387,-19.8016 2079.8777,-16.8011 2080.2243,-23.7925"/>
<text text-anchor="middle" x="54.0919" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study_arm -->
<g id="node4" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2044.5919" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2044.5919" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2060.1267,-87.3298C2068.9404,-77.4184 2080.2454,-64.8935 2090.5919,-54 2094.4723,-49.9144 2098.6526,-45.6311 2102.7427,-41.502"/>
<polygon fill="#000000" stroke="#000000" points="2105.3333,-43.8611 2109.9233,-34.3121 2100.3803,-38.9145 2105.3333,-43.8611"/>
<text text-anchor="middle" x="2139.0919" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- survival -->
<g id="node5" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="222.5919" cy="-192" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="222.5919" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M251.4505,-177.4243C277.0463,-165.2753 315.8159,-148.7487 351.5919,-141 473.041,-114.6955 839.9724,-107.5311 997.0108,-105.6461"/>
<polygon fill="#000000" stroke="#000000" points="997.0877,-109.1455 1007.0463,-105.5294 997.0062,-102.146 997.0877,-109.1455"/>
<text text-anchor="middle" x="391.0919" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- molecular_test -->
<g id="node6" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="368.5919" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="368.5919" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M396.2347,-175.0092C416.982,-163.1923 446.5262,-148.2991 474.5919,-141 571.2285,-115.8676 860.2629,-108.1691 996.7262,-105.9017"/>
<polygon fill="#000000" stroke="#000000" points="997.1325,-109.3957 1007.0749,-105.7354 997.0199,-102.3966 997.1325,-109.3957"/>
<text text-anchor="middle" x="538.5919" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- cell_line -->
<g id="node7" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2536.5919" cy="-105" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2536.5919" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2500.3652,-117.2524C2492.9014,-119.4365 2485.0444,-121.4924 2477.5919,-123 2401.3894,-138.4151 2380.7885,-131.774 2303.5919,-141 2187.6321,-154.8587 2051.9621,-173.9807 1979.4907,-184.4301"/>
<polygon fill="#000000" stroke="#000000" points="1978.6633,-181.0132 1969.2666,-185.9073 1979.6643,-187.9413 1978.6633,-181.0132"/>
<text text-anchor="middle" x="2344.0919" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge6" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2525.18,-87.4561C2516.6034,-75.858 2503.7554,-61.4639 2488.5919,-54 2434.2639,-27.2585 2258.223,-20.3797 2173.2836,-18.6113"/>
<polygon fill="#000000" stroke="#000000" points="2173.2119,-15.1094 2163.1462,-18.4157 2173.0768,-22.1081 2173.2119,-15.1094"/>
<text text-anchor="middle" x="2548.0919" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge29" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1971.6937,-189.9054C2070.3681,-184.9951 2306.4158,-171.9421 2384.5919,-156 2422.6142,-148.2463 2464.3023,-133.8127 2494.3874,-122.2742"/>
<polygon fill="#000000" stroke="#000000" points="2495.6766,-125.5282 2503.7282,-118.6418 2493.1395,-119.0042 2495.6766,-125.5282"/>
<text text-anchor="middle" x="2476.0919" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1894.4298,-180.0144C1887.8996,-177.8598 1881.0654,-175.7469 1874.5919,-174 1803.2303,-154.7427 1784.9025,-150.4268 1711.5919,-141 1603.2623,-127.0703 1285.4446,-113.4021 1141.6845,-107.7342"/>
<polygon fill="#000000" stroke="#000000" points="1141.7694,-104.2349 1131.6398,-107.34 1141.4948,-111.2295 1141.7694,-104.2349"/>
<text text-anchor="middle" x="1838.0919" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node25" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1938.5919" cy="-105" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1938.5919" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge30" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1903.4442,-176.7578C1891.4433,-167.1362 1880.8101,-154.0883 1887.5919,-141 1891.8207,-132.8387 1898.8452,-126.1337 1906.3489,-120.8159"/>
<polygon fill="#000000" stroke="#000000" points="1908.6495,-123.5028 1915.2388,-115.2063 1904.9139,-117.5828 1908.6495,-123.5028"/>
<text text-anchor="middle" x="1924.0919" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cytogenomic_file -->
<g id="node9" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="2201.5919" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="2201.5919" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2182.2731,-261.1635C2168.9893,-249.8972 2150.4096,-236.0039 2131.5919,-228 2105.0423,-216.7074 2031.6396,-205.4289 1980.5424,-198.5826"/>
<polygon fill="#000000" stroke="#000000" points="1980.6941,-195.0723 1970.3218,-197.2321 1979.7771,-202.012 1980.6941,-195.0723"/>
<text text-anchor="middle" x="2229.0919" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- study_personnel -->
<g id="node10" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2209.5919" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2209.5919" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge15" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2204.8736,-86.932C2201.4245,-76.4088 2195.8807,-63.4041 2187.5919,-54 2180.8933,-46.4001 2172.1888,-39.9635 2163.4632,-34.7284"/>
<polygon fill="#000000" stroke="#000000" points="2164.8857,-31.5146 2154.4457,-29.7095 2161.4814,-37.631 2164.8857,-31.5146"/>
<text text-anchor="middle" x="2266.0919" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- study_funding -->
<g id="node11" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2391.5919" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2391.5919" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge4" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2378.125,-87.0372C2368.6305,-75.7176 2354.9122,-61.8123 2339.5919,-54 2311.1076,-39.475 2226.0739,-28.3282 2172.4577,-22.5032"/>
<polygon fill="#000000" stroke="#000000" points="2172.8205,-19.0221 2162.5062,-21.4438 2172.0794,-25.9828 2172.8205,-19.0221"/>
<text text-anchor="middle" x="2422.5919" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge32" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1128.6367,-98.878C1227.328,-88.7586 1432.077,-68.2473 1605.5919,-54 1780.6988,-39.622 1989.2348,-26.3836 2080.2567,-20.7979"/>
<polygon fill="#000000" stroke="#000000" points="2080.4807,-24.2908 2090.2482,-20.1866 2080.0531,-17.3039 2080.4807,-24.2908"/>
<text text-anchor="middle" x="1656.0919" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- treatment_response -->
<g id="node13" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="571.5919" cy="-192" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="571.5919" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M586.6603,-174.0904C597.5642,-162.4849 613.3628,-148.2297 630.5919,-141 663.4899,-127.1951 881.711,-114.3865 997.5811,-108.4576"/>
<polygon fill="#000000" stroke="#000000" points="997.9751,-111.9422 1007.7848,-107.9398 997.6202,-104.9512 997.9751,-111.9422"/>
<text text-anchor="middle" x="713.5919" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- diagnosis -->
<g id="node14" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1684.5919" cy="-279" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1684.5919" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1704.2049,-262.0643C1718.5809,-250.5927 1739.0892,-236.0993 1759.5919,-228 1807.707,-208.9928 1824.3576,-222.364 1874.5919,-210 1877.9976,-209.1617 1881.4966,-208.202 1884.9948,-207.1718"/>
<polygon fill="#000000" stroke="#000000" points="1886.2679,-210.4412 1894.7733,-204.1239 1884.1848,-203.7583 1886.2679,-210.4412"/>
<text text-anchor="middle" x="1804.0919" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1644.0847,-266.7583C1636.6388,-264.6989 1628.9077,-262.6859 1621.5919,-261 1576.7337,-250.6629 1564.6328,-252.5092 1519.5919,-243 1459.5798,-230.33 1434.2547,-247.335 1385.5919,-210 1357.8153,-188.6893 1376.5243,-160.7127 1347.5919,-141 1315.152,-118.8976 1213.2075,-110.3557 1142.2353,-107.0605"/>
<polygon fill="#000000" stroke="#000000" points="1142.1445,-103.5533 1132.0006,-106.6115 1141.8376,-110.5466 1142.1445,-103.5533"/>
<text text-anchor="middle" x="1430.0919" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- clinical_measure_file -->
<g id="node15" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="1756.5919" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="1756.5919" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1677.4291,-179.6473C1618.1584,-170.2729 1546.1979,-158.571 1539.5919,-156 1528.2188,-151.5737 1528.1408,-144.9446 1516.5919,-141 1449.3219,-118.0235 1250.578,-109.5085 1142.1541,-106.5147"/>
<polygon fill="#000000" stroke="#000000" points="1142.0409,-103.0105 1131.9509,-106.2419 1141.8537,-110.008 1142.0409,-103.0105"/>
<text text-anchor="middle" x="1625.5919" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge22" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1791.3493,-174.7664C1805.7814,-165.2972 1817.1802,-153.053 1807.5919,-141 1785.4429,-113.1576 1751.7408,-150.8424 1729.5919,-123 1719.631,-110.4787 1719.2923,-99.2441 1729.5919,-87 1773.92,-34.3029 1984.8538,-21.85 2079.9305,-18.9088"/>
<polygon fill="#000000" stroke="#000000" points="2080.2243,-22.4019 2090.1197,-18.6165 2080.0235,-15.4047 2080.2243,-22.4019"/>
<text text-anchor="middle" x="1815.5919" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- study_admin -->
<g id="node16" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="2674.5919" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2674.5919" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge11" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2653.4152,-87.8289C2637.6486,-76.0865 2615.0544,-61.363 2592.5919,-54 2515.6222,-28.7702 2275.2924,-20.9973 2173.209,-18.7977"/>
<polygon fill="#000000" stroke="#000000" points="2173.263,-15.2982 2163.1927,-18.5903 2173.1181,-22.2967 2173.263,-15.2982"/>
<text text-anchor="middle" x="2680.0919" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- publication -->
<g id="node17" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="2825.5919" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="2825.5919" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge21" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2803.9276,-87.9561C2787.5402,-76.1129 2763.9414,-61.2099 2740.5919,-54 2687.012,-37.4556 2307.9527,-23.8233 2173.6352,-19.4635"/>
<polygon fill="#000000" stroke="#000000" points="2173.38,-15.9535 2163.2725,-19.1298 2173.1546,-22.9499 2173.38,-15.9535"/>
<text text-anchor="middle" x="2823.5919" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- methylation_array_file -->
<g id="node18" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1496.5919" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1496.5919" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1507.7626,-260.9958C1516.0769,-249.3481 1528.5602,-235.0814 1543.5919,-228 1610.2316,-196.6062 1802.2653,-223.9746 1874.5919,-210 1878.2413,-209.2949 1881.9834,-208.3986 1885.709,-207.3841"/>
<polygon fill="#000000" stroke="#000000" points="1886.8773,-210.688 1895.4573,-204.4723 1884.8739,-203.9808 1886.8773,-210.688"/>
<text text-anchor="middle" x="1635.0919" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- medical_history -->
<g id="node19" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="779.5919" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="779.5919" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M788.3033,-173.9442C794.7646,-162.5853 804.6824,-148.6712 817.5919,-141 847.2989,-123.3471 934.7496,-113.8276 998.31,-109.092"/>
<polygon fill="#000000" stroke="#000000" points="998.5709,-112.5823 1008.2934,-108.3725 998.0677,-105.6004 998.5709,-112.5823"/>
<text text-anchor="middle" x="885.5919" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- treatment -->
<g id="node20" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="940.5919" cy="-192" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="940.5919" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M947.9307,-173.8104C953.117,-162.9763 961.0289,-149.6885 971.5919,-141 982.9087,-131.6914 996.8512,-124.6719 1010.6323,-119.4239"/>
<polygon fill="#000000" stroke="#000000" points="1011.8545,-122.7042 1020.1131,-116.0675 1009.5184,-116.1055 1011.8545,-122.7042"/>
<text text-anchor="middle" x="1018.5919" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- sequencing_file -->
<g id="node21" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1840.5919" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1840.5919" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1845.2172,-260.849C1848.6334,-250.2963 1854.1751,-237.2899 1862.5919,-228 1869.2773,-220.6211 1877.8404,-214.419 1886.5412,-209.3551"/>
<polygon fill="#000000" stroke="#000000" points="1888.4378,-212.3091 1895.5851,-204.4882 1885.1206,-206.1449 1888.4378,-212.3091"/>
<text text-anchor="middle" x="1929.0919" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- exposure -->
<g id="node22" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1069.5919" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1069.5919" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1069.5919,-173.9735C1069.5919,-162.1918 1069.5919,-146.5607 1069.5919,-133.1581"/>
<polygon fill="#000000" stroke="#000000" points="1073.092,-133.0033 1069.5919,-123.0034 1066.092,-133.0034 1073.092,-133.0033"/>
<text text-anchor="middle" x="1113.0919" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- pathology_file -->
<g id="node24" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2017.5919" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2017.5919" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2013.03,-260.7909C2009.6364,-250.2176 2004.096,-237.2099 1995.5919,-228 1988.3812,-220.191 1979.0836,-213.7584 1969.6929,-208.6011"/>
<polygon fill="#000000" stroke="#000000" points="1971.2265,-205.4545 1960.726,-204.0438 1968.055,-211.6948 1971.2265,-205.4545"/>
<text text-anchor="middle" x="2066.5919" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1954.2081,-120.3494C1962.4059,-130.3332 1969.7724,-143.7315 1964.5919,-156 1962.646,-160.6082 1959.7899,-164.9182 1956.513,-168.841"/>
<polygon fill="#000000" stroke="#000000" points="1953.7395,-166.6768 1949.3525,-176.3207 1958.796,-171.5175 1953.7395,-166.6768"/>
<text text-anchor="middle" x="1989.5919" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge3" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1958.4009,-91.9375C1975.6681,-80.9084 2001.6314,-65.1722 2025.5919,-54 2044.8984,-44.9978 2067.1259,-36.8504 2085.8053,-30.5923"/>
<polygon fill="#000000" stroke="#000000" points="2087.0883,-33.8549 2095.4953,-27.4072 2084.9024,-27.2049 2087.0883,-33.8549"/>
<text text-anchor="middle" x="2049.5919" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
</g>
</svg>
</div>
