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
<a href="./model-desc/ccdi-model.svg">SVG file (in view above)</a>
<p>
<a href="./model-desc">Additional model files</a>
<div id='graph' style='display:off;'>
<svg width="2858pt" height="392pt"
 viewBox="0.00 0.00 2857.99 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 2853.9885,-388 2853.9885,4 -4,4"/>
<!-- single_cell_sequencing_file -->
<g id="node1" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1978.1938" cy="-366" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="1978.1938" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- sample -->
<g id="node5" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2106.1938" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2106.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge37" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1974.9676,-347.6969C1972.0469,-325.3916 1970.4315,-287.4169 1987.1938,-261 1996.818,-245.8324 2036.225,-224.6635 2067.0878,-209.7844"/>
<polygon fill="#000000" stroke="#000000" points="2068.8201,-212.8364 2076.3492,-205.3823 2065.815,-206.5142 2068.8201,-212.8364"/>
<text text-anchor="middle" x="2095.6938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- cell_line -->
<g id="node9" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2262.1938" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2262.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge36" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2068.3616,-352.2875C2090.5418,-347.0132 2113.7718,-339.8032 2134.1938,-330 2143.893,-325.3441 2143.7194,-320.0979 2153.1938,-315 2164.0681,-309.1488 2189.9571,-300.5264 2213.7758,-293.1869"/>
<polygon fill="#000000" stroke="#000000" points="2214.9124,-296.4995 2223.4582,-290.2369 2212.8723,-289.8034 2214.9124,-296.4995"/>
<text text-anchor="middle" x="2261.6938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- pdx -->
<g id="node17" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1226.1938" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1226.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge35" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1851.3893,-358.9283C1743.9071,-352.3113 1598.3855,-341.7108 1541.1938,-330 1520.5405,-325.7709 1516.7341,-319.7477 1496.1938,-315 1414.7246,-296.1692 1316.9897,-286.1769 1264.3243,-281.7971"/>
<polygon fill="#000000" stroke="#000000" points="1264.3506,-278.2879 1254.1011,-280.9708 1263.7866,-285.2652 1264.3506,-278.2879"/>
<text text-anchor="middle" x="1649.6938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- study_admin -->
<g id="node2" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="70.1938" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="70.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study -->
<g id="node10" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="621.1938" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="621.1938" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge7" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M87.814,-87.5469C100.8402,-75.8314 119.6433,-61.2592 139.1938,-54 179.3384,-39.094 461.9198,-25.0704 574.7889,-19.9992"/>
<polygon fill="#000000" stroke="#000000" points="575.0168,-23.4926 584.851,-19.5507 574.705,-16.4996 575.0168,-23.4926"/>
<text text-anchor="middle" x="195.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- study_funding -->
<g id="node3" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="236.1938" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="236.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge24" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M243.778,-86.8034C249.5436,-75.385 258.6368,-61.4576 271.1938,-54 296.738,-38.8294 485.5908,-25.9257 574.7872,-20.6049"/>
<polygon fill="#000000" stroke="#000000" points="575.1204,-24.0914 584.8971,-20.0088 574.7084,-17.1035 575.1204,-24.0914"/>
<text text-anchor="middle" x="333.1938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- study_personnel -->
<g id="node4" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="418.1938" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="418.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge28" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M405.2286,-86.7465C399.4212,-76.1575 395.4318,-63.1489 403.1938,-54 414.1904,-41.0385 514.4629,-28.7678 575.1163,-22.4448"/>
<polygon fill="#000000" stroke="#000000" points="575.6297,-25.9105 585.2202,-21.4081 574.9152,-18.9471 575.6297,-25.9105"/>
<text text-anchor="middle" x="472.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- participant -->
<g id="node15" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1595.1938" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1595.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2089.3883,-175.3352C2076.3308,-163.5184 2057.1382,-148.4818 2037.1938,-141 1971.5514,-116.3753 1775.6004,-108.5673 1667.974,-106.1116"/>
<polygon fill="#000000" stroke="#000000" points="1667.9156,-102.6096 1657.8416,-105.8903 1667.7627,-109.6079 1667.9156,-102.6096"/>
<text text-anchor="middle" x="2099.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- clinical_measure_file -->
<g id="node6" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="686.1938" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="686.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge25" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M679.4825,-174.0343C668.0677,-143.4778 644.8073,-81.2116 631.3777,-45.2616"/>
<polygon fill="#000000" stroke="#000000" points="634.6468,-44.0108 627.8686,-35.868 628.0894,-46.4605 634.6468,-44.0108"/>
<text text-anchor="middle" x="746.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M680.9109,-173.5709C679.0009,-162.6467 679.011,-149.3482 687.1938,-141 701.7686,-126.1304 1310.1113,-111.297 1522.7426,-106.5575"/>
<polygon fill="#000000" stroke="#000000" points="1522.9469,-110.0539 1532.8667,-106.3328 1522.7915,-103.0557 1522.9469,-110.0539"/>
<text text-anchor="middle" x="816.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- molecular_test -->
<g id="node7" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1746.1938" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1746.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1728.4901,-174.232C1717.1351,-163.5565 1701.6664,-150.2875 1686.1938,-141 1674.0029,-133.6824 1660.0576,-127.302 1646.8079,-122.0279"/>
<polygon fill="#000000" stroke="#000000" points="1647.9081,-118.7013 1637.3179,-118.3855 1645.3997,-125.2365 1647.9081,-118.7013"/>
<text text-anchor="middle" x="1771.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- sequencing_file -->
<g id="node8" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="997.1938" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="997.1938" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M988.7776,-347.7946C985.3713,-337.7158 983.268,-325.2017 988.1938,-315 1004.9742,-280.2466 1020.4887,-275.6469 1056.1938,-261 1182.7479,-209.0849 1225.7097,-237.1219 1362.1938,-228 1515.4595,-217.7565 1901.9785,-237.0047 2053.1938,-210 2056.9037,-209.3375 2060.7058,-208.4626 2064.4872,-207.4549"/>
<polygon fill="#000000" stroke="#000000" points="2065.7736,-210.7244 2074.3704,-204.5319 2063.7883,-204.0118 2065.7736,-210.7244"/>
<text text-anchor="middle" x="1122.6938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge5" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1078.4978,-361.9638C1163.6578,-356.9264 1291.2951,-346.856 1337.1938,-330 1348.3026,-325.9203 1347.9233,-318.6093 1359.1938,-315 1448.1009,-286.5283 2106.8854,-310.9381 2199.1938,-297 2204.6067,-296.1827 2210.2109,-295.0365 2215.7432,-293.7141"/>
<polygon fill="#000000" stroke="#000000" points="2216.7601,-297.0664 2225.5667,-291.1762 2215.0091,-290.2889 2216.7601,-297.0664"/>
<text text-anchor="middle" x="1425.6938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge4" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M992.2642,-347.8975C990.4872,-337.0962 990.513,-323.8123 998.1938,-315 1001.3115,-311.423 1124.6848,-293.424 1188.6156,-284.3081"/>
<polygon fill="#000000" stroke="#000000" points="1189.3016,-287.7458 1198.709,-282.8722 1188.3157,-280.8156 1189.3016,-287.7458"/>
<text text-anchor="middle" x="1064.6938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2224.0588,-267.3557C2215.8979,-265.0744 2207.2944,-262.8261 2199.1938,-261 2175.4584,-255.6493 2106.9208,-261.5651 2091.1938,-243 2085.3233,-236.0702 2086.1825,-226.9321 2089.465,-218.3074"/>
<polygon fill="#000000" stroke="#000000" points="2092.6254,-219.8114 2093.7743,-209.279 2086.3081,-216.7961 2092.6254,-219.8114"/>
<text text-anchor="middle" x="2131.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge18" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2309.7748,-273.7895C2379.7715,-265.0335 2505.1525,-244.8208 2532.1938,-210 2542.0074,-197.363 2539.7104,-188.1245 2532.1938,-174 2400.0582,74.2968 1552.8942,-71.8431 1272.1938,-54 1045.6177,-39.5974 774.4665,-25.6648 667.6695,-20.3067"/>
<polygon fill="#000000" stroke="#000000" points="667.7176,-16.8048 657.5551,-19.8002 667.3675,-23.796 667.7176,-16.8048"/>
<text text-anchor="middle" x="2557.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2244.6358,-261.8646C2230.8289,-248.1677 2211.3019,-228.2982 2195.1938,-210 2169.2807,-180.5638 2174.9447,-159.1754 2140.1938,-141 2099.3604,-119.6434 1806.3105,-109.9634 1667.6124,-106.5409"/>
<polygon fill="#000000" stroke="#000000" points="1667.5779,-103.0392 1657.496,-106.2957 1667.4082,-110.0371 1667.5779,-103.0392"/>
<text text-anchor="middle" x="2235.6938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- methylation_array_file -->
<g id="node11" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1507.1938" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1507.1938" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1507.6332,-347.5196C1508.8935,-336.5761 1512.3389,-323.2754 1521.1938,-315 1697.2742,-150.4417 1820.1904,-271.5887 2053.1938,-210 2056.5363,-209.1165 2059.9734,-208.1309 2063.4143,-207.0886"/>
<polygon fill="#000000" stroke="#000000" points="2064.5689,-210.3944 2073.046,-204.0391 2062.4559,-203.7209 2064.5689,-210.3944"/>
<text text-anchor="middle" x="1680.6938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge1" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1603.2039,-355.8954C1650.2435,-350.0164 1707.5299,-341.4715 1758.1938,-330 1779.9927,-325.0642 1784.1818,-318.8766 1806.1938,-315 1978.3934,-284.6731 2026.6343,-325.2079 2199.1938,-297 2204.5262,-296.1283 2210.0487,-294.9604 2215.5073,-293.6362"/>
<polygon fill="#000000" stroke="#000000" points="2216.4109,-297.0177 2225.2086,-291.1141 2214.6496,-290.2429 2216.4109,-297.0177"/>
<text text-anchor="middle" x="1897.6938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge3" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1394.1201,-361.9285C1297.0403,-357.2365 1170.2456,-347.7721 1154.1938,-330 1138.8985,-313.0656 1165.7847,-298.5702 1190.94,-289.4096"/>
<polygon fill="#000000" stroke="#000000" points="1192.0796,-292.719 1200.4047,-286.1659 1189.8101,-286.097 1192.0796,-292.719"/>
<text text-anchor="middle" x="1245.6938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- family_relationship -->
<g id="node12" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1944.1938" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1944.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1914.8667,-174.7385C1894.341,-163.4223 1865.917,-149.2465 1839.1938,-141 1782.5641,-123.5246 1715.847,-114.4225 1666.5026,-109.7477"/>
<polygon fill="#000000" stroke="#000000" points="1666.5223,-106.2352 1656.2466,-108.816 1665.8889,-113.2065 1666.5223,-106.2352"/>
<text text-anchor="middle" x="1953.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- diagnosis -->
<g id="node13" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="2340.1938" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="2340.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2308.1609,-177.3003C2280.277,-165.2472 2238.4415,-148.9281 2200.1938,-141 2100.4327,-120.3211 1805.4018,-110.3274 1667.6153,-106.6861"/>
<polygon fill="#000000" stroke="#000000" points="1667.6596,-103.1862 1657.5719,-106.4246 1667.4774,-110.1838 1667.6596,-103.1862"/>
<text text-anchor="middle" x="2295.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- follow_up -->
<g id="node14" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="2468.1938" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="2468.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2439.0575,-176.6702C2414.5,-164.5789 2378.048,-148.539 2344.1938,-141 2279.4068,-126.5726 1842.5115,-112.2855 1667.489,-107.0711"/>
<polygon fill="#000000" stroke="#000000" points="1667.4456,-103.5683 1657.3462,-106.7703 1667.2381,-110.5653 1667.4456,-103.5683"/>
<text text-anchor="middle" x="2434.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge17" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1535.3668,-99.6561C1356.3334,-83.6644 827.3071,-36.4105 667.4556,-22.1322"/>
<polygon fill="#000000" stroke="#000000" points="667.302,-18.6046 657.0303,-21.201 666.6792,-25.5769 667.302,-18.6046"/>
<text text-anchor="middle" x="1217.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- pathology_file -->
<g id="node16" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2396.1938" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2396.1938" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2463.6756,-357.6334C2497.0944,-350.5366 2527.0478,-337.7276 2510.1938,-315 2414.4704,-185.917 2317.8241,-257.1497 2164.1938,-210 2159.94,-208.6945 2155.5125,-207.3303 2151.0841,-205.9621"/>
<polygon fill="#000000" stroke="#000000" points="2152.043,-202.5952 2141.4553,-202.982 2149.9734,-209.2822 2152.043,-202.5952"/>
<text text-anchor="middle" x="2555.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge9" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2392.3417,-347.7178C2389.1715,-336.8489 2383.6168,-323.557 2374.1938,-315 2358.866,-301.0809 2338.1151,-292.5404 2318.6395,-287.3013"/>
<polygon fill="#000000" stroke="#000000" points="2319.4554,-283.8977 2308.9099,-284.9186 2317.7903,-290.6968 2319.4554,-283.8977"/>
<text text-anchor="middle" x="2445.1938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge8" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2322.2525,-361.4108C2217.8013,-354.5825 2036.5388,-341.3346 2008.1938,-330 1998.204,-326.0053 1999.293,-318.7093 1989.1938,-315 1936.5938,-295.6805 1541.1521,-299.9429 1485.1938,-297 1406.6117,-292.8673 1314.7561,-286 1264.2773,-282.0499"/>
<polygon fill="#000000" stroke="#000000" points="1264.3971,-278.5486 1254.1533,-281.2533 1263.8479,-285.527 1264.3971,-278.5486"/>
<text text-anchor="middle" x="2069.1938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1251.5156,-271.3628C1291.9903,-259.5523 1373.9622,-237.2545 1445.1938,-228 1579.2375,-210.5848 1920.1711,-233.9998 2053.1938,-210 2056.9025,-209.3309 2060.7038,-208.4514 2064.4847,-207.4407"/>
<polygon fill="#000000" stroke="#000000" points="2065.7731,-210.7094 2074.3669,-204.5129 2063.7846,-203.9977 2065.7731,-210.7094"/>
<text text-anchor="middle" x="1469.1938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge16" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1205.7775,-266.332C1201.7275,-264.2641 1197.4187,-262.3577 1193.1938,-261 1078.9377,-224.2832 1044.7563,-238.3617 925.1938,-228 905.4094,-226.2854 581.8778,-224.3913 568.1938,-210 557.1686,-198.4049 565.5854,-189.786 568.1938,-174 575.9024,-127.3471 595.7561,-75.8953 608.855,-45.2964"/>
<polygon fill="#000000" stroke="#000000" points="612.226,-46.3216 613.0109,-35.7559 605.8084,-43.526 612.226,-46.3216"/>
<text text-anchor="middle" x="599.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- therapeutic_procedure -->
<g id="node18" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="1052.1938" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="1052.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1067.5605,-174.0479C1078.6684,-162.4235 1094.7402,-148.1631 1112.1938,-141 1149.1742,-125.823 1397.7063,-113.3301 1523.1096,-107.9076"/>
<polygon fill="#000000" stroke="#000000" points="1523.5455,-111.3922 1533.3865,-107.4671 1523.2457,-104.3986 1523.5455,-111.3922"/>
<text text-anchor="middle" x="1205.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- synonym -->
<g id="node19" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="806.1938" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="806.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge30" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M820.4149,-261.4857C831.2674,-249.5772 847.3538,-234.7961 865.1938,-228 926.8771,-204.5019 1988.152,-221.2503 2053.1938,-210 2056.9072,-209.3577 2060.7119,-208.4969 2064.4949,-207.4986"/>
<polygon fill="#000000" stroke="#000000" points="2065.775,-210.7704 2074.3806,-204.5903 2063.7993,-204.0549 2065.775,-210.7704"/>
<text text-anchor="middle" x="907.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge31" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M755.6061,-274.4982C698.6876,-267.6043 605.0698,-250.6408 535.1938,-210 506.3924,-193.2488 495.6533,-186.9012 483.1938,-156 480.7008,-149.817 479.8676,-146.7776 483.1938,-141 491.1427,-127.1927 501.8298,-133.0479 514.1938,-123 546.1886,-96.9984 546.2184,-82.306 576.1938,-54 581.3744,-49.1079 587.1552,-44.1516 592.8014,-39.5454"/>
<polygon fill="#000000" stroke="#000000" points="595.2544,-42.066 600.8918,-33.0955 590.8907,-36.5925 595.2544,-42.066"/>
<text text-anchor="middle" x="525.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M806.4961,-260.9797C807.9454,-237.1388 814.3089,-195.6158 840.1938,-174 850.7355,-165.1969 1071.5314,-142.4009 1085.1938,-141 1241.0448,-125.0195 1424.4237,-113.9619 1523.2852,-108.6355"/>
<polygon fill="#000000" stroke="#000000" points="1523.6598,-112.1205 1533.4586,-108.0915 1523.286,-105.1305 1523.6598,-112.1205"/>
<text text-anchor="middle" x="882.6938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- medical_history -->
<g id="node20" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1273.1938" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1273.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1285.5772,-173.8555C1294.3946,-162.4592 1307.2924,-148.5367 1322.1938,-141 1356.3293,-123.7352 1454.473,-113.9875 1523.2574,-109.1055"/>
<polygon fill="#000000" stroke="#000000" points="1523.8703,-112.5716 1533.6057,-108.3917 1523.3886,-105.5882 1523.8703,-112.5716"/>
<text text-anchor="middle" x="1390.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- publication -->
<g id="node21" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="2649.1938" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="2649.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge22" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2629.9185,-87.6922C2615.2474,-75.7177 2593.934,-60.7662 2572.1938,-54 2478.4844,-24.8351 955.414,-18.9716 667.8336,-18.1227"/>
<polygon fill="#000000" stroke="#000000" points="667.7532,-14.6226 657.743,-18.0935 667.7328,-21.6225 667.7532,-14.6226"/>
<text text-anchor="middle" x="2652.1938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- study_arm -->
<g id="node22" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2790.1938" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2790.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge33" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2769.5251,-87.9246C2753.5869,-75.8983 2730.4092,-60.7794 2707.1938,-54 2606.097,-24.4778 966.3961,-18.883 667.6956,-18.1073"/>
<polygon fill="#000000" stroke="#000000" points="667.6493,-14.6072 657.6404,-18.0817 667.6314,-21.6072 667.6493,-14.6072"/>
<text text-anchor="middle" x="2786.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- radiology_file -->
<g id="node23" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1450.1938" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1450.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1454.3528,-173.6252C1457.7168,-162.7214 1463.5298,-149.4254 1473.1938,-141 1482.8984,-132.5392 1509.0731,-124.3171 1534.7009,-117.8717"/>
<polygon fill="#000000" stroke="#000000" points="1535.5747,-121.2613 1544.4607,-115.4916 1533.9162,-114.4606 1535.5747,-121.2613"/>
<text text-anchor="middle" x="1532.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- exposure -->
<g id="node24" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1595.1938" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1595.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1595.1938,-173.9735C1595.1938,-162.1918 1595.1938,-146.5607 1595.1938,-133.1581"/>
<polygon fill="#000000" stroke="#000000" points="1598.6939,-133.0033 1595.1938,-123.0034 1591.6939,-133.0034 1598.6939,-133.0033"/>
<text text-anchor="middle" x="1638.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
</g>
</svg>
</div>
