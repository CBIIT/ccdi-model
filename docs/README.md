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
<svg width="2670pt" height="305pt"
 viewBox="0.00 0.00 2669.58 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 2665.5836,-301 2665.5836,4 -4,4"/>
<!-- sequencing_file -->
<g id="node1" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2158.5404" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="2158.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sample -->
<g id="node16" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2150.5404" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2150.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2156.8828,-260.9735C2155.7994,-249.1918 2154.362,-233.5607 2153.1296,-220.1581"/>
<polygon fill="#000000" stroke="#000000" points="2156.5969,-219.6408 2152.1959,-210.0034 2149.6263,-220.2819 2156.5969,-219.6408"/>
<text text-anchor="middle" x="2221.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- medical_history -->
<g id="node2" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="320.5404" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="320.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- participant -->
<g id="node11" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1190.5404" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1190.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M338.0528,-174.2453C351.0283,-162.3876 369.815,-147.7696 389.5404,-141 466.1775,-114.6987 1038.2511,-133.8917 1118.5404,-123 1124.2659,-122.2233 1130.1949,-121.1664 1136.0803,-119.9513"/>
<polygon fill="#000000" stroke="#000000" points="1136.8926,-123.3562 1145.9003,-117.7785 1135.3803,-116.5216 1136.8926,-123.3562"/>
<text text-anchor="middle" x="457.5404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- clinical_measure_file -->
<g id="node3" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="108.5404" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="108.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M129.0375,-174.1859C144.1039,-162.3002 165.6813,-147.6731 187.5404,-141 286.4958,-110.791 1015.9788,-136.6335 1118.5404,-123 1124.3498,-122.2278 1130.3677,-121.1617 1136.3367,-119.9306"/>
<polygon fill="#000000" stroke="#000000" points="1137.284,-123.3057 1146.2904,-117.7258 1135.7701,-116.4714 1137.284,-123.3057"/>
<text text-anchor="middle" x="273.5404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- study -->
<g id="node20" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1948.5404" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1948.5404" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge24" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M119.3043,-173.8999C127.2189,-162.3679 139.0906,-148.2734 153.5404,-141 590.4051,78.897 762.3761,-84.0203 1250.5404,-54 1495.756,-38.9202 1789.7005,-25.175 1901.9097,-20.0859"/>
<polygon fill="#000000" stroke="#000000" points="1902.362,-23.5691 1912.1936,-19.6207 1902.0456,-16.5763 1902.362,-23.5691"/>
<text text-anchor="middle" x="350.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- molecular_test -->
<g id="node4" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="503.5404" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="503.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M513.6843,-173.912C521.3279,-162.227 532.9759,-147.95 547.5404,-141 604.8281,-113.663 1055.67,-131.7474 1118.5404,-123 1124.2632,-122.2038 1130.1904,-121.1341 1136.0748,-119.9114"/>
<polygon fill="#000000" stroke="#000000" points="1136.8907,-123.3155 1145.8937,-117.7301 1135.3726,-116.4821 1136.8907,-123.3155"/>
<text text-anchor="middle" x="611.5404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- study_admin -->
<g id="node5" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1039.5404" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1039.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge30" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1091.021,-92.564C1100.4717,-90.5244 1110.2763,-88.5683 1119.5404,-87 1414.5488,-37.058 1775.0091,-22.7597 1901.7721,-19.1223"/>
<polygon fill="#000000" stroke="#000000" points="1902.0036,-22.6173 1911.9023,-18.8403 1901.8087,-15.62 1902.0036,-22.6173"/>
<text text-anchor="middle" x="1403.0404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- methylation_array_file -->
<g id="node6" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2375.5404" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2375.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2350.8513,-261.326C2334.6435,-250.4148 2312.6165,-236.8567 2291.5404,-228 2262.7294,-215.893 2228.8409,-207.0809 2201.5085,-201.2063"/>
<polygon fill="#000000" stroke="#000000" points="2201.8817,-197.709 2191.3783,-199.0979 2200.4553,-204.5622 2201.8817,-197.709"/>
<text text-anchor="middle" x="2411.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- family_relationship -->
<g id="node7" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="701.5404" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="701.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M686.9224,-173.9897C680.0133,-163.2231 674.9595,-149.9433 683.5404,-141 700.2861,-123.547 1094.6005,-126.451 1118.5404,-123 1124.2592,-122.1756 1130.1839,-121.0877 1136.0667,-119.8539"/>
<polygon fill="#000000" stroke="#000000" points="1136.8876,-123.2569 1145.8838,-117.6605 1135.3612,-116.4253 1136.8876,-123.2569"/>
<text text-anchor="middle" x="763.0404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- pathology_file -->
<g id="node8" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2585.5404" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2585.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2564.5391,-261.481C2549.4056,-249.8943 2527.9556,-235.5036 2506.5404,-228 2452.2465,-208.9762 2290.1594,-198.6353 2204.6815,-194.3714"/>
<polygon fill="#000000" stroke="#000000" points="2204.8084,-190.8735 2194.6495,-193.8813 2204.4668,-197.8652 2204.8084,-190.8735"/>
<text text-anchor="middle" x="2597.5404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- cytogenomic_file -->
<g id="node9" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1967.5404" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1967.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1977.1662,-260.8811C1983.9585,-249.7924 1994.0589,-236.2036 2006.5404,-228 2021.8771,-217.9197 2064.7273,-207.9118 2099.7258,-201.0164"/>
<polygon fill="#000000" stroke="#000000" points="2100.6703,-204.3988 2109.8266,-199.0683 2099.3447,-197.5254 2100.6703,-204.3988"/>
<text text-anchor="middle" x="2078.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- pdx -->
<g id="node10" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2254.5404" cy="-105" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2254.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2277.1449,-115.9968C2298.9069,-126.5837 2328.5404,-141 2328.5404,-141 2332.076,-146.6519 2332.7614,-150.8398 2328.5404,-156 2313.0577,-174.9274 2250.9849,-184.1349 2204.4672,-188.4524"/>
<polygon fill="#000000" stroke="#000000" points="2204.1594,-184.9659 2194.5033,-189.3257 2204.7707,-191.9391 2204.1594,-184.9659"/>
<text text-anchor="middle" x="2354.5404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge3" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2247.1362,-87.425C2241.3528,-75.969 2232.1688,-61.7548 2219.5404,-54 2182.9248,-31.5153 2062.538,-22.8277 1995.196,-19.6683"/>
<polygon fill="#000000" stroke="#000000" points="1995.0105,-16.1566 1984.8644,-19.2074 1994.6985,-23.1497 1995.0105,-16.1566"/>
<text text-anchor="middle" x="2258.5404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge28" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1248.7607,-98.3177C1394.2359,-81.6207 1771.322,-38.3404 1902.6395,-23.2683"/>
<polygon fill="#000000" stroke="#000000" points="1903.2224,-26.7245 1912.758,-22.1069 1902.4241,-19.7701 1903.2224,-26.7245"/>
<text text-anchor="middle" x="1666.0404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_funding -->
<g id="node12" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="1871.5404" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="1871.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge2" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1870.5078,-86.9755C1870.7878,-76.4676 1872.7446,-63.464 1879.5404,-54 1886.5501,-44.2381 1897.0183,-36.9138 1907.6955,-31.5117"/>
<polygon fill="#000000" stroke="#000000" points="1909.4039,-34.5795 1917.0507,-27.2463 1906.4998,-28.2103 1909.4039,-34.5795"/>
<text text-anchor="middle" x="1941.5404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- survival -->
<g id="node13" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1763.5404" cy="-192" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1763.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1747.3625,-175.0264C1734.9582,-163.2181 1716.7528,-148.328 1697.5404,-141 1658.0051,-125.9204 1393.1022,-113.2283 1262.7346,-107.8112"/>
<polygon fill="#000000" stroke="#000000" points="1262.5819,-104.302 1252.4462,-107.3872 1262.2936,-111.296 1262.5819,-104.302"/>
<text text-anchor="middle" x="1763.0404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- publication -->
<g id="node14" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="2029.5404" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="2029.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge29" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2023.116,-87.086C2018.7391,-76.6173 2012.1692,-63.616 2003.5404,-54 1997.6239,-47.4067 1990.2385,-41.5018 1982.819,-36.4742"/>
<polygon fill="#000000" stroke="#000000" points="1984.4972,-33.3938 1974.1795,-30.9864 1980.744,-39.3026 1984.4972,-33.3938"/>
<text text-anchor="middle" x="2064.5404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- diagnosis -->
<g id="node15" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="854.5404" cy="-279" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="854.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M847.8848,-260.7414C840.9102,-238.1348 833.2784,-199.5027 851.5404,-174 887.981,-123.111 1115.4922,-123.5397 1118.5404,-123 1123.9325,-122.0453 1129.5187,-120.9115 1135.0859,-119.6844"/>
<polygon fill="#000000" stroke="#000000" points="1136.0801,-123.0471 1145.0403,-117.3933 1134.51,-116.2255 1136.0801,-123.0471"/>
<text text-anchor="middle" x="896.0404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M908.1689,-275.3999C1118.5032,-261.2803 1885.9092,-209.7646 2096.67,-195.6163"/>
<polygon fill="#000000" stroke="#000000" points="2097.1197,-199.0941 2106.8628,-194.9321 2096.6508,-192.1098 2097.1197,-199.0941"/>
<text text-anchor="middle" x="1625.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge9" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2187.9532,-182.2178C2203.3447,-176.6364 2220.3765,-168.2424 2232.5404,-156 2238.9886,-149.5102 2243.679,-140.8259 2247.0288,-132.4651"/>
<polygon fill="#000000" stroke="#000000" points="2250.3592,-133.5445 2250.3704,-122.9497 2243.7547,-131.2251 2250.3592,-133.5445"/>
<text text-anchor="middle" x="2279.0404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2111.6332,-183.3171C2079.4257,-176.0991 2032.4805,-165.5082 1991.5404,-156 1963.5039,-149.4886 1957.0365,-145.0518 1928.5404,-141 1801.6282,-122.9544 1423.062,-111.1433 1263.1336,-106.8309"/>
<polygon fill="#000000" stroke="#000000" points="1263.0106,-103.3265 1252.9206,-106.5577 1262.8234,-110.324 1263.0106,-103.3265"/>
<text text-anchor="middle" x="2028.0404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node18" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2159.5404" cy="-105" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2159.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge10" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2112.4416,-182.7211C2086.6292,-174.465 2059.4132,-160.6386 2072.5404,-141 2077.484,-133.6042 2093.9509,-125.9896 2111.2486,-119.6793"/>
<polygon fill="#000000" stroke="#000000" points="2112.589,-122.9185 2120.8761,-116.3173 2110.2812,-116.3099 2112.589,-122.9185"/>
<text text-anchor="middle" x="2109.0404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- synonym -->
<g id="node17" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1807.5404" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1807.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1755.3806,-278.6992C1580.7649,-277.1566 1024.6889,-267.7159 971.5404,-210 960.702,-198.2302 962.0781,-186.9021 971.5404,-174 981.3803,-160.583 1071.532,-135.3188 1133.0564,-119.3669"/>
<polygon fill="#000000" stroke="#000000" points="1134.2361,-122.6773 1143.0466,-116.7929 1132.4896,-115.8986 1134.2361,-122.6773"/>
<text text-anchor="middle" x="1014.0404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1831.5868,-262.8488C1849.9633,-251.2942 1876.3408,-236.3606 1901.5404,-228 1966.3106,-206.511 2044.766,-197.8427 2096.078,-194.3501"/>
<polygon fill="#000000" stroke="#000000" points="2096.5263,-197.8287 2106.2833,-193.6994 2096.0808,-190.8429 2096.5263,-197.8287"/>
<text text-anchor="middle" x="1944.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge14" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1813.2725,-261.0281C1819.1694,-240.0097 1826.6897,-204.2399 1820.5404,-174 1817.3656,-158.3876 1815.9485,-153.8575 1806.5404,-141 1799.2813,-131.0795 1790.677,-134.1681 1785.5404,-123 1778.8547,-108.4638 1776.7028,-100.3378 1785.5404,-87 1811.405,-47.9646 1864.2317,-30.9526 1902.7581,-23.5763"/>
<polygon fill="#000000" stroke="#000000" points="1903.4741,-27.0041 1912.7144,-21.8208 1902.2586,-20.1104 1903.4741,-27.0041"/>
<text text-anchor="middle" x="1859.0404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2154.7593,-123.1928C2153.4706,-128.8572 2152.2405,-135.1515 2151.5404,-141 2150.6776,-148.2076 2150.2648,-156.0282 2150.1023,-163.3303"/>
<polygon fill="#000000" stroke="#000000" points="2146.6009,-163.498 2150.02,-173.526 2153.6007,-163.5546 2146.6009,-163.498"/>
<text text-anchor="middle" x="2192.0404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge5" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2149.9781,-87.2169C2143.011,-75.9731 2132.534,-62.0848 2119.5404,-54 2098.9126,-41.165 2037.1647,-30.2992 1993.8221,-23.9623"/>
<polygon fill="#000000" stroke="#000000" points="1994.1783,-20.4777 1983.7835,-22.5268 1993.1873,-27.4072 1994.1783,-20.4777"/>
<text text-anchor="middle" x="2175.0404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- study_personnel -->
<g id="node19" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2387.5404" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2387.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge31" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2360.3685,-87.8683C2340.6508,-76.3042 2312.9174,-61.781 2286.5404,-54 2233.0484,-38.2204 2074.2897,-26.1171 1994.869,-20.8635"/>
<polygon fill="#000000" stroke="#000000" points="1994.8748,-17.3565 1984.668,-20.1975 1994.4187,-24.3416 1994.8748,-17.3565"/>
<text text-anchor="middle" x="2393.0404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- exposure -->
<g id="node21" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1118.5404" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1118.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1130.1562,-173.9822C1136.8844,-163.962 1145.7428,-151.4442 1154.5404,-141 1157.7185,-137.227 1161.222,-133.388 1164.758,-129.6912"/>
<polygon fill="#000000" stroke="#000000" points="1167.4454,-131.9504 1171.9676,-122.3692 1162.4575,-127.039 1167.4454,-131.9504"/>
<text text-anchor="middle" x="1198.0404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- radiology_file -->
<g id="node22" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1263.5404" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1263.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1258.3734,-173.6882C1254.8177,-163.3343 1249.3177,-150.5843 1241.5404,-141 1237.4622,-135.9743 1232.5113,-131.3343 1227.317,-127.1735"/>
<polygon fill="#000000" stroke="#000000" points="1229.1626,-124.185 1219.0443,-121.0431 1224.9949,-129.8091 1229.1626,-124.185"/>
<text text-anchor="middle" x="1309.5404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- treatment -->
<g id="node23" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="1412.5404" cy="-192" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="1412.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1403.0105,-174.1645C1396.057,-162.8986 1385.5831,-149.0053 1372.5404,-141 1353.5035,-129.3156 1301.6722,-119.725 1258.1692,-113.3891"/>
<polygon fill="#000000" stroke="#000000" points="1258.5674,-109.9106 1248.1743,-111.9683 1257.5821,-116.841 1258.5674,-109.9106"/>
<text text-anchor="middle" x="1437.5404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- study_arm -->
<g id="node24" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2552.5404" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2552.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge18" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2530.5658,-88.033C2513.9581,-76.228 2490.0715,-61.3392 2466.5404,-54 2379.315,-26.7952 2105.4355,-20.1017 1995.1933,-18.4939"/>
<polygon fill="#000000" stroke="#000000" points="1995.0947,-14.9923 1985.0473,-18.3536 1994.9979,-21.9916 1995.0947,-14.9923"/>
<text text-anchor="middle" x="2547.0404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- treatment_response -->
<g id="node25" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1592.5404" cy="-192" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1592.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1563.5813,-174.5076C1543.2906,-163.0884 1515.1482,-148.8843 1488.5404,-141 1447.3219,-128.7863 1335.4534,-117.3626 1261.1224,-110.7837"/>
<polygon fill="#000000" stroke="#000000" points="1261.1616,-107.2739 1250.8943,-109.888 1260.5508,-114.2472 1261.1616,-107.2739"/>
<text text-anchor="middle" x="1610.5404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
</g>
</svg>
</div>
