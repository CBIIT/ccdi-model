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
<svg width="3004pt" height="392pt"
 viewBox="0.00 0.00 3004.19 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3000.1926,-388 3000.1926,4 -4,4"/>
<!-- cytogenomic_file -->
<g id="node1" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1834.1926" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1834.1926" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cell_line -->
<g id="node4" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="1700.1926" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="1700.1926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cytogenomic_file&#45;&gt;cell_line -->
<g id="edge16" class="edge">
<title>cytogenomic_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1830.3406,-347.7178C1827.1703,-336.8489 1821.6157,-323.557 1812.1926,-315 1796.8648,-301.0809 1776.1139,-292.5404 1756.6384,-287.3013"/>
<polygon fill="#000000" stroke="#000000" points="1757.4543,-283.8977 1746.9087,-284.9186 1755.7892,-290.6968 1757.4543,-283.8977"/>
<text text-anchor="middle" x="1893.6926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- sample -->
<g id="node8" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1064.1926" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1064.1926" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1917.7149,-359.3358C1955.781,-352.8671 1988.5182,-340.1198 1969.1926,-315 1852.8708,-163.8022 1304.8465,-244.3158 1117.1926,-210 1113.4855,-209.3221 1109.6853,-208.4365 1105.9052,-207.4217"/>
<polygon fill="#000000" stroke="#000000" points="1106.6067,-203.979 1096.024,-204.4876 1104.614,-210.6894 1106.6067,-203.979"/>
<text text-anchor="middle" x="2022.6926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- pdx -->
<g id="node15" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="520.1926" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="520.1926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- cytogenomic_file&#45;&gt;pdx -->
<g id="edge14" class="edge">
<title>cytogenomic_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1756.7588,-356.8463C1725.5606,-353.504 1689.2086,-350.0452 1656.1926,-348 1569.2253,-342.6126 955.4239,-355.7855 872.1926,-330 860.5352,-326.3885 860.6839,-319.1095 849.1926,-315 796.4651,-296.1437 633.3066,-285.1318 558.444,-280.9502"/>
<polygon fill="#000000" stroke="#000000" points="558.2392,-277.4338 548.063,-280.3826 557.857,-284.4234 558.2392,-277.4338"/>
<text text-anchor="middle" x="943.6926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- participant -->
<g id="node2" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1725.1926" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1725.1926" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- study -->
<g id="node17" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2356.1926" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2356.1926" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge2" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1760.5543,-90.1316C1790.5133,-78.2312 1834.9013,-62.2187 1875.1926,-54 1957.3947,-37.2322 2205.5817,-24.6587 2309.5668,-19.9858"/>
<polygon fill="#000000" stroke="#000000" points="2309.923,-23.4735 2319.7576,-19.5324 2309.6119,-16.4804 2309.923,-23.4735"/>
<text text-anchor="middle" x="1925.6926" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- follow_up -->
<g id="node3" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="2171.1926" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="2171.1926" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2130.5287,-179.6825C2110.1153,-173.1876 2085.1257,-164.7615 2063.1926,-156 2048.6062,-150.1732 2046.329,-145.1959 2031.1926,-141 1955.8459,-120.1134 1933.8229,-132.3231 1856.1926,-123 1835.0379,-120.4594 1812.0036,-117.395 1791.2331,-114.5206"/>
<polygon fill="#000000" stroke="#000000" points="1791.6241,-111.0414 1781.2367,-113.1279 1790.6581,-117.9744 1791.6241,-111.0414"/>
<text text-anchor="middle" x="2108.1926" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge36" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1748.0295,-274.4474C1850.7824,-262.9242 2077.3197,-227.1616 2001.1926,-141 1979.6939,-116.6674 1888.3881,-127.2101 1856.1926,-123 1835.1636,-120.2501 1812.2522,-117.1409 1791.5557,-114.2897"/>
<polygon fill="#000000" stroke="#000000" points="1791.9763,-110.8146 1781.5915,-112.9135 1791.0186,-117.7488 1791.9763,-110.8146"/>
<text text-anchor="middle" x="2056.6926" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge35" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1662.0241,-267.5004C1653.8655,-265.2094 1645.2714,-262.9205 1637.1926,-261 1561.0396,-242.8965 1541.9035,-237.3827 1464.1926,-228 1310.8765,-209.4888 1268.8544,-239.1068 1117.1926,-210 1113.5423,-209.2994 1109.7995,-208.4064 1106.0735,-207.394"/>
<polygon fill="#000000" stroke="#000000" points="1106.9078,-203.9905 1096.3246,-204.4857 1104.9067,-210.6984 1106.9078,-203.9905"/>
<text text-anchor="middle" x="1596.6926" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge37" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1747.9241,-273.9933C1786.1131,-270.0988 1841.0503,-264.7453 1889.1926,-261 2081.2905,-246.0554 2648.3061,-289.5471 2745.1926,-123 2753.2381,-109.1699 2754.6769,-99.886 2745.1926,-87 2715.9446,-47.2619 2687.4067,-64.4868 2639.1926,-54 2556.7279,-36.0635 2458.6639,-26.0552 2402.3006,-21.3674"/>
<polygon fill="#000000" stroke="#000000" points="2402.5253,-17.8742 2392.2748,-20.5533 2401.9587,-24.8512 2402.5253,-17.8742"/>
<text text-anchor="middle" x="2771.6926" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- study_funding -->
<g id="node5" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="1942.1926" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="1942.1926" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge30" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1958.8807,-87.2064C1970.8616,-75.6527 1988.0412,-61.4117 2006.1926,-54 2060.018,-32.0216 2227.3185,-22.8237 2309.5754,-19.5518"/>
<polygon fill="#000000" stroke="#000000" points="2309.7897,-23.0463 2319.6476,-19.164 2309.5203,-16.0515 2309.7897,-23.0463"/>
<text text-anchor="middle" x="2068.1926" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- exposure -->
<g id="node6" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1357.1926" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1357.1926" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1382.2077,-176.0474C1401.6272,-164.4374 1429.6312,-149.3437 1456.1926,-141 1492.2155,-129.6842 1588.5694,-118.4268 1655.5927,-111.59"/>
<polygon fill="#000000" stroke="#000000" points="1656.0727,-115.0594 1665.6706,-110.5726 1655.3696,-108.0948 1656.0727,-115.0594"/>
<text text-anchor="middle" x="1499.6926" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- study_personnel -->
<g id="node7" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2124.1926" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2124.1926" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge34" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2127.4345,-86.9848C2130.4035,-75.7922 2135.962,-62.0498 2146.1926,-54 2170.9766,-34.4992 2255.9083,-25.0049 2309.8691,-20.8385"/>
<polygon fill="#000000" stroke="#000000" points="2310.177,-24.3254 2319.8919,-20.0981 2309.6612,-17.3444 2310.177,-24.3254"/>
<text text-anchor="middle" x="2215.6926" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge39" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1090.2008,-177.2817C1112.915,-165.2171 1147.1715,-148.8914 1179.1926,-141 1266.8655,-119.3937 1525.4115,-110.0248 1652.7092,-106.6332"/>
<polygon fill="#000000" stroke="#000000" points="1652.8515,-110.1308 1662.7566,-106.3707 1652.6686,-103.1331 1652.8515,-110.1308"/>
<text text-anchor="middle" x="1215.6926" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- family_relationship -->
<g id="node9" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1528.1926" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1528.1926" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1535.9801,-173.7781C1541.6605,-162.6483 1550.4244,-149.0525 1562.1926,-141 1578.0005,-130.1834 1620.9432,-120.9387 1658.7835,-114.5266"/>
<polygon fill="#000000" stroke="#000000" points="1659.486,-117.9581 1668.7826,-112.8764 1658.3461,-111.0515 1659.486,-117.9581"/>
<text text-anchor="middle" x="1641.6926" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- medical_history -->
<g id="node10" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1731.1926" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1731.1926" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge38" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1728.2284,-173.7317C1727.4239,-168.0642 1726.6496,-161.7872 1726.1926,-156 1725.6212,-148.7635 1725.3131,-140.9325 1725.1584,-133.6296"/>
<polygon fill="#000000" stroke="#000000" points="1728.6558,-133.3932 1725.0286,-123.4386 1721.6564,-133.4824 1728.6558,-133.3932"/>
<text text-anchor="middle" x="1794.1926" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- study_admin -->
<g id="node11" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="2299.1926" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2299.1926" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge29" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2291.8968,-86.9024C2288.9649,-76.6199 2287.4649,-63.8699 2293.1926,-54 2298.5592,-44.7524 2307.2923,-37.6797 2316.5697,-32.3561"/>
<polygon fill="#000000" stroke="#000000" points="2318.2261,-35.4402 2325.5392,-27.7741 2315.0416,-29.2065 2318.2261,-35.4402"/>
<text text-anchor="middle" x="2349.6926" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- radiology_file -->
<g id="node12" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1908.1926" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1908.1926" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge40" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1896.1068,-173.9532C1887.8033,-162.8933 1875.8396,-149.3095 1862.1926,-141 1841.1485,-128.1864 1815.5929,-119.8884 1792.2801,-114.5341"/>
<polygon fill="#000000" stroke="#000000" points="1792.9589,-111.1001 1782.446,-112.4151 1791.4843,-117.9431 1792.9589,-111.1001"/>
<text text-anchor="middle" x="1938.1926" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node13" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="2474.1926" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="2474.1926" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2393.5156,-179.8888C2379.4172,-177.8595 2364.884,-175.823 2351.1926,-174 2284.6351,-165.138 2264.2974,-178.9397 2201.1926,-156 2189.7229,-151.8306 2189.7891,-144.8027 2178.1926,-141 2110.0933,-118.6688 1927.5286,-129.8835 1856.1926,-123 1834.6898,-120.9251 1811.2947,-117.9435 1790.3039,-115.0021"/>
<polygon fill="#000000" stroke="#000000" points="1790.6048,-111.5097 1780.2113,-113.5655 1789.6183,-118.4399 1790.6048,-111.5097"/>
<text text-anchor="middle" x="2330.6926" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge1" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2472.65,-173.97C2470.9726,-163.4602 2467.4762,-150.4564 2460.1926,-141 2450.4708,-128.378 2439.2506,-135.3557 2429.1926,-123 2408.7852,-97.9306 2425.3482,-80.0385 2406.1926,-54 2401.617,-47.7802 2395.6461,-42.2057 2389.4308,-37.4071"/>
<polygon fill="#000000" stroke="#000000" points="2391.0914,-34.2936 2380.9117,-31.3567 2387.0381,-40.0007 2391.0914,-34.2936"/>
<text text-anchor="middle" x="2515.1926" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- publication -->
<g id="node14" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="2673.1926" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="2673.1926" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge24" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2627.4366,-92.4424C2566.0074,-75.5832 2457.733,-45.8676 2398.2526,-29.5433"/>
<polygon fill="#000000" stroke="#000000" points="2399.0077,-26.1212 2388.438,-26.8497 2397.155,-32.8716 2399.0077,-26.1212"/>
<text text-anchor="middle" x="2584.1926" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge32" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M548.2189,-276.9156C623.8041,-270.8976 837.8415,-251.2309 1011.1926,-210 1014.6049,-209.1884 1018.1085,-208.2479 1021.6099,-207.2308"/>
<polygon fill="#000000" stroke="#000000" points="1022.874,-210.5035 1031.3939,-204.2058 1020.8063,-203.8159 1022.874,-210.5035"/>
<text text-anchor="middle" x="942.1926" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge33" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M533.0933,-262.8662C552.1035,-240.0739 589.7822,-198.5006 630.1926,-174 669.1323,-150.3911 682.5976,-150.2174 727.1926,-141 1202.684,-42.7197 1331.9488,-89.483 1816.1926,-54 1998.6817,-40.6281 2216.0204,-26.7677 2309.5812,-20.9003"/>
<polygon fill="#000000" stroke="#000000" points="2310.0763,-24.3762 2319.8379,-20.258 2309.6387,-17.3899 2310.0763,-24.3762"/>
<text text-anchor="middle" x="751.1926" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pathology_file -->
<g id="node16" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1321.1926" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1321.1926" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge10" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1369.3212,-351.9651C1390.7917,-345.5375 1416.3463,-337.6579 1439.1926,-330 1457.5901,-323.8333 1461.311,-319.4696 1480.1926,-315 1548.5387,-298.8212 1568.3056,-310.6936 1637.1926,-297 1642.2917,-295.9864 1647.578,-294.761 1652.8223,-293.4318"/>
<polygon fill="#000000" stroke="#000000" points="1654.0326,-296.7315 1662.7951,-290.7759 1652.2311,-289.9673 1654.0326,-296.7315"/>
<text text-anchor="middle" x="1541.1926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1377.3062,-353.6809C1403.5108,-345.3246 1426.0108,-332.5746 1411.1926,-315 1395.9324,-296.9011 1328.8807,-303.7599 1306.1926,-297 1230.4325,-274.4273 1146.8182,-234.5593 1100.3829,-210.9808"/>
<polygon fill="#000000" stroke="#000000" points="1101.8266,-207.788 1091.3297,-206.3504 1098.6391,-214.0201 1101.8266,-207.788"/>
<text text-anchor="middle" x="1367.1926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge11" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1245.1311,-365.3574C1050.1935,-363.3425 546.2144,-355.6646 521.1926,-330 515.3032,-323.9592 513.6585,-315.3518 513.915,-306.9246"/>
<polygon fill="#000000" stroke="#000000" points="517.4012,-307.2413 515.0133,-296.9191 510.443,-306.4775 517.4012,-307.2413"/>
<text text-anchor="middle" x="582.1926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- methylation_array_file -->
<g id="node18" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1531.1926" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1531.1926" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge6" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1570.9907,-348.9005C1582.6213,-343.3742 1595.1648,-336.8817 1606.1926,-330 1615.3201,-324.3042 1616.0652,-320.6958 1625.1926,-315 1635.6269,-308.4887 1647.4182,-302.3258 1658.5092,-297"/>
<polygon fill="#000000" stroke="#000000" points="1660.0449,-300.1457 1667.6157,-292.734 1657.0753,-293.8068 1660.0449,-300.1457"/>
<text text-anchor="middle" x="1716.6926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1490.2594,-349.0057C1480.9438,-343.8488 1471.6168,-337.515 1464.1926,-330 1439.8832,-305.3931 1456.2187,-281.2727 1428.1926,-261 1314.7028,-178.9073 1253.0792,-243.9704 1117.1926,-210 1113.7899,-209.1494 1110.2931,-208.1808 1106.7965,-207.1444"/>
<polygon fill="#000000" stroke="#000000" points="1107.6095,-203.7315 1097.0206,-204.0859 1105.5193,-210.4122 1107.6095,-203.7315"/>
<text text-anchor="middle" x="1539.6926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge8" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1450.9986,-353.0158C1436.1375,-351.0185 1420.7219,-349.2185 1406.1926,-348 1324.2338,-341.1266 744.7387,-354.3928 666.1926,-330 654.5377,-326.3805 654.279,-320.1021 643.1926,-315 615.3021,-302.1643 581.7421,-292.7065 556.7279,-286.7144"/>
<polygon fill="#000000" stroke="#000000" points="557.4451,-283.2879 546.9126,-284.4353 555.8617,-290.1065 557.4451,-283.2879"/>
<text text-anchor="middle" x="757.6926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node19" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="322.1926" cy="-366" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="322.1926" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge23" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M459.6017,-364.6132C664.1218,-361.7929 1038.7353,-353.509 1171.1926,-330 1192.7821,-326.1682 1196.6042,-318.8378 1218.1926,-315 1401.7094,-282.3763 1453.1977,-326.8094 1637.1926,-297 1642.5263,-296.1359 1648.0496,-294.9727 1653.5086,-293.6513"/>
<polygon fill="#000000" stroke="#000000" points="1654.411,-297.0331 1663.2103,-291.1321 1652.6516,-290.2578 1654.411,-297.0331"/>
<text text-anchor="middle" x="1326.6926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M291.8264,-348.2169C285.1841,-343.084 278.7774,-336.9588 274.1926,-330 257.2078,-304.2201 245.1214,-283.563 266.1926,-261 322.8234,-200.3599 929.8402,-226.3111 1011.1926,-210 1014.8371,-209.2693 1018.5756,-208.3551 1022.2989,-207.3286"/>
<polygon fill="#000000" stroke="#000000" points="1023.4752,-210.6297 1032.0434,-204.3977 1021.4591,-203.9263 1023.4752,-210.6297"/>
<text text-anchor="middle" x="374.6926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge21" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M294.0625,-348.3366C281.5063,-338.3147 271.4916,-325.6797 281.1926,-315 309.2628,-284.0981 427.4026,-305.8905 468.1926,-297 474.2321,-295.6836 480.5405,-293.8828 486.5961,-291.9265"/>
<polygon fill="#000000" stroke="#000000" points="488.1322,-295.0999 496.4563,-288.5456 485.8616,-288.4784 488.1322,-295.0999"/>
<text text-anchor="middle" x="389.6926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- study_arm -->
<g id="node20" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2852.1926" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2852.1926" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge19" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2833.3471,-87.8665C2819.247,-76.1424 2798.9017,-61.4251 2778.1926,-54 2710.1438,-29.6014 2497.6704,-21.4448 2402.7776,-18.9739"/>
<polygon fill="#000000" stroke="#000000" points="2402.6997,-15.4709 2392.6152,-18.7194 2402.5244,-22.4687 2402.6997,-15.4709"/>
<text text-anchor="middle" x="2854.6926" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- diagnosis -->
<g id="node21" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="694.1926" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="694.1926" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M725.0091,-176.9818C751.6302,-164.8179 791.4913,-148.512 828.1926,-141 907.8286,-124.7002 1453.3796,-111.0587 1652.5798,-106.5678"/>
<polygon fill="#000000" stroke="#000000" points="1652.7329,-110.0654 1662.6519,-106.3419 1652.5759,-103.0671 1652.7329,-110.0654"/>
<text text-anchor="middle" x="872.6926" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- therapeutic_procedure -->
<g id="node22" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="884.1926" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="884.1926" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M899.876,-174.1381C911.3866,-162.3941 928.1113,-147.9563 946.1926,-141 1010.9577,-116.0832 1471.6191,-107.9866 1652.5235,-105.75"/>
<polygon fill="#000000" stroke="#000000" points="1652.7809,-109.2472 1662.7377,-105.6263 1652.6961,-102.2477 1652.7809,-109.2472"/>
<text text-anchor="middle" x="1039.1926" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- synonym -->
<g id="node23" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2262.1926" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2262.1926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2262.5307,-260.9558C2261.973,-237.8536 2257.5255,-197.9551 2235.1926,-174 2217.9416,-155.4959 2204.4265,-166.0093 2181.1926,-156 2168.227,-150.4143 2166.7753,-144.8495 2153.1926,-141 2089.5771,-122.9705 1921.993,-129.5051 1856.1926,-123 1834.6948,-120.8747 1811.301,-117.8797 1790.3098,-114.9416"/>
<polygon fill="#000000" stroke="#000000" points="1790.6098,-111.4492 1780.2169,-113.5079 1789.6253,-118.3796 1790.6098,-111.4492"/>
<text text-anchor="middle" x="2296.6926" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2219.9694,-268.205C2169.5085,-255.8602 2082.3298,-236.2892 2006.1926,-228 1809.7573,-206.6138 1311.8111,-244.1739 1117.1926,-210 1113.4808,-209.3482 1109.6773,-208.4808 1105.8951,-207.4781"/>
<polygon fill="#000000" stroke="#000000" points="1106.5922,-204.0348 1096.0105,-204.563 1104.612,-210.7489 1106.5922,-204.0348"/>
<text text-anchor="middle" x="2140.6926" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge3" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2313.9516,-277.2047C2436.2352,-272.7047 2735.936,-260.0697 2778.1926,-243 2855.1215,-211.9242 2886.13,-198.1955 2921.1926,-123 2934.4165,-94.64 2932.7072,-72.1153 2907.1926,-54 2866.565,-25.1544 2528.5123,-19.4176 2402.9264,-18.2801"/>
<polygon fill="#000000" stroke="#000000" points="2402.8792,-14.7797 2392.8499,-18.1947 2402.8198,-21.7794 2402.8792,-14.7797"/>
<text text-anchor="middle" x="2953.6926" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- molecular_test -->
<g id="node24" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1206.1926" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1206.1926" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1227.42,-174.61C1242.9674,-162.9242 1265.1232,-148.3617 1287.1926,-141 1353.0138,-119.044 1546.4,-110.1144 1652.8612,-106.7843"/>
<polygon fill="#000000" stroke="#000000" points="1652.9965,-110.2819 1662.8854,-106.4792 1652.7835,-103.2851 1652.9965,-110.2819"/>
<text text-anchor="middle" x="1351.1926" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- sequencing_file -->
<g id="node25" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="83.1926" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="83.1926" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge25" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M141.3649,-353.0533C152.5402,-351.0111 164.1892,-349.1854 175.1926,-348 268.0103,-338.0005 927.3342,-361.5597 1015.1926,-330 1025.318,-326.3628 1024.0826,-318.6797 1034.1926,-315 1097.1801,-292.0745 1570.9568,-307.2865 1637.1926,-297 1642.6021,-296.1599 1648.2041,-294.9996 1653.7351,-293.669"/>
<polygon fill="#000000" stroke="#000000" points="1654.7556,-297.0203 1663.5573,-291.1228 1652.999,-290.2442 1654.7556,-297.0203"/>
<text text-anchor="middle" x="1100.6926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M83.8374,-347.7103C85.7191,-323.9598 92.7222,-282.9548 118.1926,-261 182.4491,-205.6127 221.7804,-236.4391 306.1926,-228 462.133,-212.4098 856.9086,-237.5116 1011.1926,-210 1014.9027,-209.3384 1018.705,-208.4642 1022.4864,-207.457"/>
<polygon fill="#000000" stroke="#000000" points="1023.7725,-210.7266 1032.3697,-204.5347 1021.7877,-204.0138 1023.7725,-210.7266"/>
<text text-anchor="middle" x="184.6926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge27" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M97.6531,-348.1991C108.3243,-336.483 123.941,-322.0536 141.1926,-315 208.5561,-287.4572 396.7828,-311.0387 468.1926,-297 474.2578,-295.8076 480.5789,-294.0681 486.6391,-292.1343"/>
<polygon fill="#000000" stroke="#000000" points="488.173,-295.3086 496.5004,-288.7584 485.9058,-288.6859 488.173,-295.3086"/>
<text text-anchor="middle" x="207.6926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
</g>
</svg>
</div>
