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
<svg width="2873pt" height="392pt"
 viewBox="0.00 0.00 2873.19 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 2869.1938,-388 2869.1938,4 -4,4"/>
<!-- study_admin -->
<g id="node1" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="70.1938" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="70.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study -->
<g id="node5" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="700.1938" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="700.1938" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M64.9626,-86.6212C63.0721,-75.7159 63.0846,-62.4197 71.1938,-54 91.3424,-33.0799 511.1814,-22.09 653.4946,-18.9553"/>
<polygon fill="#000000" stroke="#000000" points="653.7251,-22.4513 663.6467,-18.7347 653.573,-15.4529 653.7251,-22.4513"/>
<text text-anchor="middle" x="127.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- sequencing_file -->
<g id="node2" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2525.1938" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="2525.1938" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- cell_line -->
<g id="node3" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2173.1938" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2173.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge25" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2514.515,-347.7996C2506.7836,-336.3796 2495.2437,-322.4518 2481.1938,-315 2439.3748,-292.8202 2309.6719,-284.1249 2232.5588,-280.8544"/>
<polygon fill="#000000" stroke="#000000" points="2232.6368,-277.3547 2222.5029,-280.4459 2232.3526,-284.349 2232.6368,-277.3547"/>
<text text-anchor="middle" x="2565.6938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sample -->
<g id="node6" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2160.1938" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2160.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2584.7137,-353.3531C2607.4429,-347.2142 2629.5228,-339.1765 2636.1938,-330 2659.4003,-298.077 2630.1919,-283.6437 2587.1938,-261 2438.758,-182.8308 2376.4804,-248.4847 2213.1938,-210 2209.7799,-209.1954 2206.2751,-208.2598 2202.7729,-207.2463"/>
<polygon fill="#000000" stroke="#000000" points="2203.5748,-203.831 2192.9874,-204.2272 2201.5111,-210.5199 2203.5748,-203.831"/>
<text text-anchor="middle" x="2706.6938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- pdx -->
<g id="node21" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1697.1938" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1697.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge27" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2450.5501,-358.036C2417.1018,-352.7437 2377.7247,-344.073 2344.1938,-330 2333.2817,-325.4201 2333.4389,-318.6872 2322.1938,-315 2268.3143,-297.3331 1868.6386,-302.3939 1812.1938,-297 1785.9705,-294.4941 1756.6352,-289.8731 1734.1565,-285.9407"/>
<polygon fill="#000000" stroke="#000000" points="1734.4913,-282.4453 1724.0321,-284.1354 1733.2624,-289.3366 1734.4913,-282.4453"/>
<text text-anchor="middle" x="2410.6938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge19" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2220.7786,-273.99C2366.9502,-258.5738 2799.7564,-212.7194 2802.1938,-210 2812.8728,-198.0854 2810.5637,-187.6362 2802.1938,-174 2636.5322,95.8938 1698.3337,-72.4924 1382.1938,-54 1143.1144,-40.0152 856.7421,-25.6876 746.5377,-20.264"/>
<polygon fill="#000000" stroke="#000000" points="746.59,-16.7625 736.4302,-19.7673 746.2463,-23.754 746.59,-16.7625"/>
<text text-anchor="middle" x="2824.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2170.5002,-260.9735C2168.7397,-249.1918 2166.404,-233.5607 2164.4013,-220.1581"/>
<polygon fill="#000000" stroke="#000000" points="2167.8234,-219.3763 2162.8839,-210.0034 2160.9003,-220.4108 2167.8234,-219.3763"/>
<text text-anchor="middle" x="2207.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- participant -->
<g id="node24" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1731.1938" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1731.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2218.1994,-271.1593C2275.7948,-260.1028 2370.6111,-238.1037 2391.1938,-210 2410.2123,-184.0319 2397.1336,-156.9817 2369.1938,-141 2321.1658,-113.5278 1960.5522,-107.0107 1803.7005,-105.4722"/>
<polygon fill="#000000" stroke="#000000" points="1803.7016,-101.9721 1793.6691,-105.3778 1803.6358,-108.9718 1803.7016,-101.9721"/>
<text text-anchor="middle" x="2439.6938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- family_relationship -->
<g id="node4" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="2693.1938" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="2693.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2646.304,-175.9506C2609.2834,-164.0445 2556.0677,-148.6103 2508.1938,-141 2373.8888,-119.6501 1969.9684,-109.6112 1803.8042,-106.3004"/>
<polygon fill="#000000" stroke="#000000" points="1803.7514,-102.7988 1793.6845,-106.1013 1803.6136,-109.7975 1803.7514,-102.7988"/>
<text text-anchor="middle" x="2653.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2145.255,-174.6759C2134.1084,-163.0213 2117.8161,-148.4688 2100.1938,-141 2048.4267,-119.0599 1895.469,-110.2994 1803.5389,-106.9479"/>
<polygon fill="#000000" stroke="#000000" points="1803.5831,-103.4474 1793.4661,-106.5934 1803.3368,-110.4431 1803.5831,-103.4474"/>
<text text-anchor="middle" x="2159.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_personnel -->
<g id="node7" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="313.1938" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="313.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge39" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M324.1798,-86.7415C332.1143,-75.297 343.9225,-61.3636 358.1938,-54 408.4629,-28.0623 571.6956,-20.7985 653.1172,-18.7749"/>
<polygon fill="#000000" stroke="#000000" points="653.6556,-22.2635 663.5718,-18.5329 653.4934,-15.2654 653.6556,-22.2635"/>
<text text-anchor="middle" x="427.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- study_funding -->
<g id="node8" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="495.1938" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="495.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge2" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M496.3043,-86.9258C497.9586,-75.855 501.9071,-62.2693 511.1938,-54 531.8632,-35.5951 604.9677,-25.9331 653.9623,-21.4072"/>
<polygon fill="#000000" stroke="#000000" points="654.3707,-24.8848 664.0237,-20.5181 653.7544,-17.912 654.3707,-24.8848"/>
<text text-anchor="middle" x="573.1938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- therapeutic_procedure -->
<g id="node9" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="1247.1938" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="1247.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1257.9506,-173.8858C1265.8621,-162.3477 1277.733,-148.2516 1292.1938,-141 1324.0857,-125.0073 1542.7675,-113.2006 1658.9613,-107.9755"/>
<polygon fill="#000000" stroke="#000000" points="1659.3593,-111.4614 1669.1939,-107.5205 1659.0482,-104.4683 1659.3593,-111.4614"/>
<text text-anchor="middle" x="1385.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- pathology_file -->
<g id="node10" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1834.1938" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1834.1938" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge33" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1841.4699,-347.875C1847.0322,-336.4869 1855.8569,-322.5662 1868.1938,-315 1888.7008,-302.4231 2031.8744,-289.6874 2114.57,-283.2674"/>
<polygon fill="#000000" stroke="#000000" points="2114.8862,-286.7535 2124.5886,-282.4975 2114.3498,-279.7741 2114.8862,-286.7535"/>
<text text-anchor="middle" x="1929.1938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1835.2346,-347.5525C1836.7341,-336.8947 1840.2197,-323.8819 1848.1938,-315 1857.6996,-304.4119 2034.6597,-238.2566 2117.7577,-207.5838"/>
<polygon fill="#000000" stroke="#000000" points="2118.999,-210.8565 2127.1706,-204.1129 2116.5772,-204.2888 2118.999,-210.8565"/>
<text text-anchor="middle" x="2034.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge32" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1769.3526,-356.4386C1738.9725,-350.5134 1707.4345,-341.7647 1698.1938,-330 1693.1167,-323.5362 1691.5895,-315.0558 1691.7056,-306.8705"/>
<polygon fill="#000000" stroke="#000000" points="1695.1986,-307.1027 1692.588,-296.8345 1688.2255,-306.4895 1695.1986,-307.1027"/>
<text text-anchor="middle" x="1759.1938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- publication -->
<g id="node11" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="653.1938" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="653.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge4" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M644.0127,-87.0859C640.1189,-76.8645 637.6189,-64.1145 643.1938,-54 647.5794,-46.0431 654.5461,-39.6017 662.1255,-34.4882"/>
<polygon fill="#000000" stroke="#000000" points="664.3907,-37.2125 671.1865,-29.0842 660.8052,-31.2005 664.3907,-37.2125"/>
<text text-anchor="middle" x="694.1938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- clinical_measure_file -->
<g id="node12" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="881.1938" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="881.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge15" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M890.361,-173.9688C904.1347,-144.0594 925.2333,-84.4691 892.1938,-54 871.4785,-34.8964 796.7521,-25.4248 746.8651,-21.1302"/>
<polygon fill="#000000" stroke="#000000" points="746.8777,-17.6195 736.6252,-20.2907 746.3057,-24.5961 746.8777,-17.6195"/>
<text text-anchor="middle" x="995.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M892.3431,-173.9501C900.6479,-162.2821 913.1286,-148.0097 928.1938,-141 960.9811,-125.7444 1467.2635,-111.5886 1658.6597,-106.7558"/>
<polygon fill="#000000" stroke="#000000" points="1658.9905,-110.2487 1668.8994,-106.4986 1658.8146,-103.2509 1658.9905,-110.2487"/>
<text text-anchor="middle" x="1057.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- radiology_file -->
<g id="node13" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1456.1938" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1456.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1467.3051,-173.9769C1475.2924,-162.6318 1487.1125,-148.7208 1501.1938,-141 1528.0228,-126.2895 1603.5711,-116.3869 1660.8245,-110.7508"/>
<polygon fill="#000000" stroke="#000000" points="1661.3049,-114.2209 1670.9248,-109.7816 1660.6362,-107.2529 1661.3049,-114.2209"/>
<text text-anchor="middle" x="1560.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- study_arm -->
<g id="node14" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="832.1938" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="832.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge3" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M814.5604,-87.6462C803.31,-77.1267 788.0892,-63.876 773.1938,-54 762.042,-46.6061 749.1529,-39.7568 737.3373,-34.0608"/>
<polygon fill="#000000" stroke="#000000" points="738.6853,-30.8273 728.1452,-29.7515 735.7139,-37.1654 738.6853,-30.8273"/>
<text text-anchor="middle" x="839.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- cytogenomic_file -->
<g id="node15" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="2178.1938" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="2178.1938" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;cell_line -->
<g id="edge36" class="edge">
<title>cytogenomic_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2177.1578,-347.9735C2176.4807,-336.1918 2175.5823,-320.5607 2174.8121,-307.1581"/>
<polygon fill="#000000" stroke="#000000" points="2178.2965,-306.786 2174.2284,-297.0034 2171.3081,-307.1877 2178.2965,-306.786"/>
<text text-anchor="middle" x="2246.6938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge34" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2264.9057,-361.3817C2348.4216,-356.0242 2464.1381,-345.8432 2478.1938,-330 2482.6181,-325.013 2481.9628,-320.499 2478.1938,-315 2470.0051,-303.0529 2288.4097,-237.4602 2203.3851,-207.2471"/>
<polygon fill="#000000" stroke="#000000" points="2204.3514,-203.8762 2193.7566,-203.8302 2202.0103,-210.4731 2204.3514,-203.8762"/>
<text text-anchor="middle" x="2511.6938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;pdx -->
<g id="edge35" class="edge">
<title>cytogenomic_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2115.6241,-353.0473C2088.5077,-346.9048 2056.5421,-338.9482 2028.1938,-330 2010.8788,-324.5345 2007.8374,-319.2872 1990.1938,-315 1912.9276,-296.225 1891.0576,-307.1518 1812.1938,-297 1786.2397,-293.659 1757.118,-289.0925 1734.674,-285.395"/>
<polygon fill="#000000" stroke="#000000" points="1734.9907,-281.8997 1724.5521,-283.712 1733.8425,-288.8049 1734.9907,-281.8997"/>
<text text-anchor="middle" x="2099.6938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node16" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="780.1938" cy="-366" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="780.1938" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge12" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M871.9842,-352.5402C911.025,-346.3766 956.9696,-338.5421 998.1938,-330 1025.1094,-324.4228 1030.9472,-318.6305 1058.1938,-315 1256.9217,-288.5203 1759.9818,-307.4465 1960.1938,-297 2012.8596,-294.252 2072.6897,-289.0083 2115.5016,-284.8864"/>
<polygon fill="#000000" stroke="#000000" points="2115.8431,-288.3698 2125.4575,-283.9186 2115.1658,-281.4027 2115.8431,-288.3698"/>
<text text-anchor="middle" x="1166.6938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M769.8432,-347.6374C765.3664,-337.0097 762.6701,-323.9988 770.1938,-315 857.0913,-211.0644 935.7161,-277.4174 1070.1938,-261 1294.78,-233.582 1352.2166,-239.1817 1578.1938,-228 1695.6736,-222.1869 1991.4855,-231.1399 2107.1938,-210 2110.901,-209.3227 2114.7013,-208.4375 2118.4814,-207.423"/>
<polygon fill="#000000" stroke="#000000" points="2119.7724,-210.6908 2128.3627,-204.4893 2117.7801,-203.9803 2119.7724,-210.6908"/>
<text text-anchor="middle" x="1178.6938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge13" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M774.8749,-347.5354C772.9514,-336.5979 772.9599,-323.2978 781.1938,-315 794.0728,-302.0209 1420.9307,-297.8865 1439.1938,-297 1517.4899,-293.1995 1608.9845,-286.2113 1659.2626,-282.1507"/>
<polygon fill="#000000" stroke="#000000" points="1659.6628,-285.6298 1669.3462,-281.3308 1659.0955,-278.6528 1659.6628,-285.6298"/>
<text text-anchor="middle" x="889.6938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- follow_up -->
<g id="node17" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="1603.1938" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="1603.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1611.6739,-173.8675C1617.5244,-163.055 1626.2211,-149.7697 1637.1938,-141 1648.0688,-132.3084 1661.2782,-125.5401 1674.316,-120.3397"/>
<polygon fill="#000000" stroke="#000000" points="1675.5961,-123.5979 1683.7434,-116.8251 1673.1508,-117.0389 1675.5961,-123.5979"/>
<text text-anchor="middle" x="1682.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- diagnosis -->
<g id="node18" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1731.1938" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1731.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge37" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1731.1938,-173.9735C1731.1938,-162.1918 1731.1938,-146.5607 1731.1938,-133.1581"/>
<polygon fill="#000000" stroke="#000000" points="1734.6939,-133.0033 1731.1938,-123.0034 1727.6939,-133.0034 1734.6939,-133.0033"/>
<text text-anchor="middle" x="1775.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- medical_history -->
<g id="node19" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1889.1938" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1889.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1869.7996,-174.2855C1857.4172,-163.6303 1840.65,-150.3636 1824.1938,-141 1811.356,-133.6954 1796.7464,-127.2612 1782.9716,-121.9287"/>
<polygon fill="#000000" stroke="#000000" points="1784.1929,-118.6487 1773.6006,-118.4157 1781.7357,-125.2033 1784.1929,-118.6487"/>
<text text-anchor="middle" x="1914.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- exposure -->
<g id="node20" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="2045.1938" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="2045.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2029.9861,-174.4092C2019.02,-162.946 2003.2042,-148.7299 1986.1938,-141 1954.2215,-126.4711 1865.4631,-116.2171 1801.6527,-110.4625"/>
<polygon fill="#000000" stroke="#000000" points="1801.9075,-106.9715 1791.6382,-109.5776 1801.2913,-113.9443 1801.9075,-106.9715"/>
<text text-anchor="middle" x="2052.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge24" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1677.2034,-266.2865C1673.0445,-264.1672 1668.5867,-262.2534 1664.1938,-261 1567.7707,-233.4875 836.1339,-278.8047 763.1938,-210 712.4242,-162.1088 778.9888,-115.0656 745.1938,-54 741.8738,-48.0009 737.1064,-42.6339 731.9046,-37.9904"/>
<polygon fill="#000000" stroke="#000000" points="734.0791,-35.2478 724.0904,-31.7155 729.6962,-40.7058 734.0791,-35.2478"/>
<text text-anchor="middle" x="770.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge23" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1713.3253,-264.1355C1727.6196,-251.9795 1749.6652,-235.6017 1772.1938,-228 1842.8327,-204.1647 2033.9912,-224.1193 2107.1938,-210 2110.8435,-209.296 2114.5857,-208.4006 2118.3114,-207.3866"/>
<polygon fill="#000000" stroke="#000000" points="2119.4794,-210.6907 2128.0599,-204.4758 2117.4765,-203.9833 2119.4794,-210.6907"/>
<text text-anchor="middle" x="1796.1938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- synonym -->
<g id="node22" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="611.1938" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="611.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge28" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M560.6895,-274.14C434.6033,-260.028 122.7023,-211.8296 217.1938,-87 243.4071,-52.3704 537.636,-28.9403 653.608,-20.9918"/>
<polygon fill="#000000" stroke="#000000" points="654.1939,-24.4603 663.9347,-20.2928 653.7211,-17.4762 654.1939,-24.4603"/>
<text text-anchor="middle" x="246.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge30" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M625.4095,-261.4715C636.2594,-249.5562 652.3449,-234.7727 670.1938,-228 744.8403,-199.6758 2028.5046,-223.5045 2107.1938,-210 2110.9081,-209.3626 2114.7133,-208.5052 2118.4967,-207.5091"/>
<polygon fill="#000000" stroke="#000000" points="2119.7753,-210.7815 2128.383,-204.6043 2117.8019,-204.0653 2119.7753,-210.7815"/>
<text text-anchor="middle" x="712.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M617.1573,-260.8964C621.9794,-249.3629 630.0001,-235.2679 642.1938,-228 710.4268,-187.3303 926.5951,-242.2368 999.1938,-210 1019.8741,-200.8171 1014.8351,-183.8754 1035.1938,-174 1096.4006,-144.3102 1119.9351,-166.199 1187.1938,-156 1223.392,-150.511 1231.8923,-145.759 1268.1938,-141 1405.7848,-122.9621 1567.6518,-112.9061 1658.9566,-108.2526"/>
<polygon fill="#000000" stroke="#000000" points="1659.3815,-111.7358 1669.1933,-107.7385 1659.0303,-104.7446 1659.3815,-111.7358"/>
<text text-anchor="middle" x="1077.6938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- methylation_array_file -->
<g id="node23" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1285.1938" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1285.1938" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge11" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1368.4992,-353.3718C1400.3521,-347.5906 1436.7942,-339.8098 1469.1938,-330 1485.7834,-324.9771 1488.2676,-318.7347 1505.1938,-315 1604.0072,-293.1973 1859.1975,-303.262 1960.1938,-297 2012.8301,-293.7364 2072.6635,-288.5495 2115.4841,-284.5802"/>
<polygon fill="#000000" stroke="#000000" points="2115.8108,-288.0651 2125.4422,-283.6507 2115.1602,-281.0954 2115.8108,-288.0651"/>
<text text-anchor="middle" x="1596.6938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1275.1196,-347.859C1270.7409,-337.3098 1268.0505,-324.3036 1275.1938,-315 1331.7876,-241.2898 1385.9934,-278.8478 1477.1938,-261 1592.3734,-238.4595 1622.274,-238.2077 1739.1938,-228 1902.3243,-213.7579 1946.3322,-240.6262 2107.1938,-210 2110.8452,-209.3048 2114.5886,-208.4155 2118.3151,-207.4057"/>
<polygon fill="#000000" stroke="#000000" points="2119.4802,-210.7107 2128.0648,-204.5014 2117.4817,-204.002 2119.4802,-210.7107"/>
<text text-anchor="middle" x="1568.6938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge9" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1280.0528,-347.7067C1278.1962,-336.8336 1278.2126,-323.5412 1286.1938,-315 1292.5332,-308.2158 1558.3872,-288.7937 1659.0797,-281.6652"/>
<polygon fill="#000000" stroke="#000000" points="1659.4019,-285.1513 1669.1306,-280.9557 1658.909,-278.1687 1659.4019,-285.1513"/>
<text text-anchor="middle" x="1377.6938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge40" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1671.3065,-99.9465C1484.2742,-84.1639 913.5808,-36.0065 746.57,-21.9134"/>
<polygon fill="#000000" stroke="#000000" points="746.4203,-18.3884 736.1614,-21.0351 745.8317,-25.3636 746.4203,-18.3884"/>
<text text-anchor="middle" x="1327.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- molecular_test -->
<g id="node25" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="2302.1938" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="2302.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge38" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2275.2238,-174.8813C2255.3077,-163.1643 2227.0974,-148.4495 2200.1938,-141 2127.5951,-120.8977 1916.0557,-111.0726 1803.54,-107.1521"/>
<polygon fill="#000000" stroke="#000000" points="1803.4128,-103.6458 1793.2991,-106.802 1803.1736,-110.6417 1803.4128,-103.6458"/>
<text text-anchor="middle" x="2301.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
</g>
</svg>
</div>
