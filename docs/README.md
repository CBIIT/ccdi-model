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
<svg width="2865pt" height="305pt"
 viewBox="0.00 0.00 2865.34 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 2861.3431,-301 2861.3431,4 -4,4"/>
<!-- methylation_array_file -->
<g id="node1" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2385.3431" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2385.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- sample -->
<g id="node7" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2262.3431" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2262.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2376.4285,-260.9594C2370.3363,-250.1815 2361.3757,-236.9003 2350.3431,-228 2338.3389,-218.3158 2323.3744,-210.9051 2309.2096,-205.3983"/>
<polygon fill="#000000" stroke="#000000" points="2310.1712,-202.0236 2299.5773,-201.8856 2307.7729,-208.5999 2310.1712,-202.0236"/>
<text text-anchor="middle" x="2454.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study_funding -->
<g id="node2" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="77.3431" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="77.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study -->
<g id="node8" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1546.3431" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1546.3431" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M72.1049,-87.0229C70.091,-75.9908 69.9726,-62.4117 78.3431,-54 104.007,-28.2098 1251.8526,-19.7857 1499.5492,-18.2667"/>
<polygon fill="#000000" stroke="#000000" points="1499.6809,-21.766 1509.6595,-18.2055 1499.6384,-14.7662 1499.6809,-21.766"/>
<text text-anchor="middle" x="140.3431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- clinical_measure_file -->
<g id="node3" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="530.3431" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="530.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- participant -->
<g id="node5" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1328.3431" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1328.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M552.4362,-174.1415C568.3491,-162.399 590.8891,-147.9617 613.3431,-141 673.4752,-122.3565 1086.2943,-110.6737 1255.8666,-106.6116"/>
<polygon fill="#000000" stroke="#000000" points="1256.0353,-110.1087 1265.9493,-106.3722 1255.869,-103.1107 1256.0353,-110.1087"/>
<text text-anchor="middle" x="699.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge4" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M542.3828,-173.8342C550.9819,-162.4289 563.6078,-148.5044 578.3431,-141 742.9321,-57.1789 1329.4655,-26.9114 1499.7051,-19.7809"/>
<polygon fill="#000000" stroke="#000000" points="1499.9956,-23.272 1509.8429,-19.3631 1499.7073,-16.2779 1499.9956,-23.272"/>
<text text-anchor="middle" x="852.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- synonym -->
<g id="node4" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1721.3431" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1721.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1725.3292,-261.0413C1730.7665,-231.2386 1736.3984,-171.8014 1703.3431,-141 1678.5877,-117.9325 1432.7811,-128.1808 1399.3431,-123 1394.0024,-122.1725 1388.4781,-121.1237 1382.9784,-119.9498"/>
<polygon fill="#000000" stroke="#000000" points="1383.6768,-116.5194 1373.1505,-117.7226 1382.1296,-123.3463 1383.6768,-116.5194"/>
<text text-anchor="middle" x="1771.8431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1766.4814,-269.9287C1820.8676,-259.1612 1915.0763,-241.0269 1996.3431,-228 2070.2632,-216.1507 2156.1575,-204.9965 2209.8889,-198.3311"/>
<polygon fill="#000000" stroke="#000000" points="2210.3694,-201.7985 2219.8651,-197.0994 2209.5115,-194.8512 2210.3694,-201.7985"/>
<text text-anchor="middle" x="2038.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge15" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1669.1318,-278.5733C1411.4771,-276.2181 285.862,-262.9191 235.3431,-210 113.5433,-82.4134 272.6824,-138.4433 620.3431,-87 742.9894,-68.852 773.8303,-64.7721 897.3431,-54 1122.5533,-34.3585 1392.7164,-23.4123 1499.5678,-19.5804"/>
<polygon fill="#000000" stroke="#000000" points="1499.8216,-23.0737 1509.6912,-19.2212 1499.5733,-16.0781 1499.8216,-23.0737"/>
<text text-anchor="middle" x="238.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge21" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1342.9272,-87.3045C1353.1133,-76.0976 1367.6552,-62.2177 1383.3431,-54 1419.8692,-34.8667 1466.1443,-25.8812 1500.0489,-21.6736"/>
<polygon fill="#000000" stroke="#000000" points="1500.6133,-25.1319 1510.1493,-20.5152 1499.8157,-18.1775 1500.6133,-25.1319"/>
<text text-anchor="middle" x="1433.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sequencing_file -->
<g id="node6" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2602.3431" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="2602.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2588.9849,-260.8185C2579.5362,-249.4066 2565.8282,-235.4806 2550.3431,-228 2510.233,-208.6235 2388.1539,-198.8399 2316.4605,-194.6411"/>
<polygon fill="#000000" stroke="#000000" points="2316.4466,-191.1347 2306.2641,-194.0616 2316.0494,-198.1234 2316.4466,-191.1347"/>
<text text-anchor="middle" x="2637.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2218.2669,-189.1556C2167.7504,-185.0952 2082.8426,-175.8118 2012.3431,-156 1996.0503,-151.4214 1993.8665,-144.6605 1977.3431,-141 1851.8783,-113.2054 1526.5977,-140.8954 1399.3431,-123 1393.9126,-122.2363 1388.2969,-121.2191 1382.7125,-120.0555"/>
<polygon fill="#000000" stroke="#000000" points="1383.2639,-116.5925 1372.7412,-117.826 1381.7365,-123.4238 1383.2639,-116.5925"/>
<text text-anchor="middle" x="2048.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node17" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2226.3431" cy="-105" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2226.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge13" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2301.1587,-183.2225C2329.0296,-175.0299 2359.2543,-161.0411 2344.3431,-141 2327.7241,-118.6635 2310.9717,-131.1261 2284.3431,-123 2280.861,-121.9374 2277.2629,-120.8339 2273.6436,-119.7199"/>
<polygon fill="#000000" stroke="#000000" points="2274.6658,-116.3726 2264.0783,-116.7676 2272.6013,-123.0612 2274.6658,-116.3726"/>
<text text-anchor="middle" x="2383.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node19" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2095.3431" cy="-105" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2095.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge12" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2218.583,-188.5471C2174.7353,-184.0799 2111.6123,-174.5601 2096.3431,-156 2091.1212,-149.6526 2089.5543,-141.2042 2089.6785,-133.0125"/>
<polygon fill="#000000" stroke="#000000" points="2093.1733,-133.2267 2090.5924,-122.9511 2086.202,-132.5934 2093.1733,-133.2267"/>
<text text-anchor="middle" x="2132.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- molecular_test -->
<g id="node9" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="324.3431" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="324.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M356.5189,-175.3774C381.4119,-163.4164 417.1271,-148.1768 450.3431,-141 527.8947,-124.244 1059.1804,-110.9481 1255.5738,-106.5535"/>
<polygon fill="#000000" stroke="#000000" points="1255.87,-110.0479 1265.7896,-106.3262 1255.7142,-103.0496 1255.87,-110.0479"/>
<text text-anchor="middle" x="514.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- publication -->
<g id="node10" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="1471.3431" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="1471.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge6" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1478.5952,-86.8119C1483.2626,-76.4991 1490.0126,-63.7491 1498.3431,-54 1503.1815,-48.3377 1509.0615,-43.0301 1515.0239,-38.3207"/>
<polygon fill="#000000" stroke="#000000" points="1517.1872,-41.0737 1523.1154,-32.2926 1513.0051,-35.4602 1517.1872,-41.0737"/>
<text text-anchor="middle" x="1549.3431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- treatment -->
<g id="node11" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="714.3431" cy="-192" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="714.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M743.4501,-176.1371C766.7652,-164.2497 800.6949,-148.7517 832.3431,-141 910.5677,-121.8402 1138.1995,-111.4869 1255.9302,-107.2801"/>
<polygon fill="#000000" stroke="#000000" points="1256.0671,-110.7775 1265.9377,-106.9278 1255.8208,-103.7818 1256.0671,-110.7775"/>
<text text-anchor="middle" x="879.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- study_admin -->
<g id="node12" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1622.3431" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1622.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge17" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1617.2714,-86.6098C1613.7475,-76.2298 1608.2475,-63.4798 1600.3431,-54 1594.7938,-47.3447 1587.7053,-41.4392 1580.5031,-36.4335"/>
<polygon fill="#000000" stroke="#000000" points="1582.3777,-33.4777 1572.0816,-30.9797 1578.5727,-39.3533 1582.3777,-33.4777"/>
<text text-anchor="middle" x="1666.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- study_arm -->
<g id="node13" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1770.3431" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1770.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge24" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1759.7967,-87.1659C1752.1944,-75.9006 1740.9064,-62.0075 1727.3431,-54 1704.8995,-40.7497 1637.8778,-29.801 1592.0041,-23.5802"/>
<polygon fill="#000000" stroke="#000000" points="1592.3607,-20.0969 1581.9871,-22.251 1591.4398,-27.0361 1592.3607,-20.0969"/>
<text text-anchor="middle" x="1794.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- medical_history -->
<g id="node14" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1435.3431" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1435.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1428.6658,-173.5895C1424.0377,-162.9448 1416.9676,-149.9328 1407.3431,-141 1399.4737,-133.6961 1389.8669,-127.6696 1380.099,-122.775"/>
<polygon fill="#000000" stroke="#000000" points="1381.2796,-119.4643 1370.7359,-118.4244 1378.3299,-125.8124 1381.2796,-119.4643"/>
<text text-anchor="middle" x="1487.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- radiology_file -->
<g id="node15" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1612.3431" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1612.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1599.1088,-174.2572C1589.4485,-162.7263 1575.2934,-148.4915 1559.3431,-141 1494.572,-110.5782 1469.7446,-135.8225 1399.3431,-123 1394.2353,-122.0697 1388.9508,-120.9783 1383.6759,-119.8008"/>
<polygon fill="#000000" stroke="#000000" points="1384.1263,-116.312 1373.5928,-117.4502 1382.537,-123.1292 1384.1263,-116.312"/>
<text text-anchor="middle" x="1640.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- family_relationship -->
<g id="node16" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="890.3431" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="890.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M907.3292,-174.1708C919.5139,-162.6013 936.9664,-148.3559 955.3431,-141 1008.1745,-119.8523 1162.9868,-110.7963 1255.7275,-107.1815"/>
<polygon fill="#000000" stroke="#000000" points="1256.0263,-110.6728 1265.887,-106.7976 1255.7619,-103.6778 1256.0263,-110.6728"/>
<text text-anchor="middle" x="1034.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2233.7928,-123.0034C2238.7624,-135.0133 2245.3903,-151.0307 2251.0091,-164.6093"/>
<polygon fill="#000000" stroke="#000000" points="2247.8263,-166.0716 2254.8839,-173.9735 2254.2944,-163.3951 2247.8263,-166.0716"/>
<text text-anchor="middle" x="2286.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge25" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2185.1747,-94.7681C2136.8907,-83.1475 2054.293,-64.4489 1982.3431,-54 1841.3527,-33.5248 1672.8937,-23.7271 1592.9163,-19.9524"/>
<polygon fill="#000000" stroke="#000000" points="1592.8403,-16.4452 1582.6894,-19.4799 1592.5172,-23.4378 1592.8403,-16.4452"/>
<text text-anchor="middle" x="2104.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- survival -->
<g id="node18" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1056.3431" cy="-192" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1056.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1080.5321,-176.2591C1098.9813,-164.9138 1125.3873,-150.0624 1150.3431,-141 1185.794,-128.1264 1226.9808,-119.4233 1260.802,-113.8041"/>
<polygon fill="#000000" stroke="#000000" points="1261.7291,-117.2001 1271.0473,-112.158 1260.6186,-110.2887 1261.7291,-117.2001"/>
<text text-anchor="middle" x="1189.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2118.9447,-115.0884C2133.7854,-121.7682 2153.1255,-131.0983 2169.3431,-141 2178.8264,-146.79 2179.8754,-150.1845 2189.3431,-156 2199.9729,-162.5293 2211.9526,-168.8365 2223.087,-174.2983"/>
<polygon fill="#000000" stroke="#000000" points="2221.6636,-177.4974 2232.193,-178.6737 2224.6953,-171.188 2221.6636,-177.4974"/>
<text text-anchor="middle" x="2213.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge19" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2069.0509,-98.8362C2023.9176,-88.4259 1928.6967,-67.2062 1847.3431,-54 1757.4154,-39.402 1651.4755,-28.0855 1592.2969,-22.2875"/>
<polygon fill="#000000" stroke="#000000" points="1592.4481,-18.7858 1582.1567,-21.3033 1591.7718,-25.753 1592.4481,-18.7858"/>
<text text-anchor="middle" x="1954.3431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pathology_file -->
<g id="node20" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2779.3431" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2779.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge32" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2760.8181,-261.3333C2747.3774,-249.6789 2728.1474,-235.2679 2708.3431,-228 2637.8379,-202.1256 2419.3993,-194.7998 2316.7212,-192.7639"/>
<polygon fill="#000000" stroke="#000000" points="2316.6268,-189.2616 2306.5625,-192.5723 2316.4947,-196.2604 2316.6268,-189.2616"/>
<text text-anchor="middle" x="2796.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- treatment_response -->
<g id="node21" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1227.3431" cy="-192" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1227.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1228.4385,-173.601C1229.9572,-162.9604 1233.444,-149.9486 1241.3431,-141 1249.1241,-132.1852 1259.401,-125.4817 1270.1569,-120.3991"/>
<polygon fill="#000000" stroke="#000000" points="1271.856,-123.4796 1279.6816,-116.3375 1269.1102,-117.0406 1271.856,-123.4796"/>
<text text-anchor="middle" x="1324.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- exposure -->
<g id="node22" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1877.3431" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1877.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1845.4017,-177.4881C1817.1145,-165.38 1774.3718,-148.8775 1735.3431,-141 1588.7519,-111.4121 1547.1911,-145.4819 1399.3431,-123 1393.9215,-122.1756 1388.3117,-121.1181 1382.731,-119.9295"/>
<polygon fill="#000000" stroke="#000000" points="1383.2902,-116.4676 1372.7639,-117.6705 1381.7429,-123.2944 1383.2902,-116.4676"/>
<text text-anchor="middle" x="1830.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- study_personnel -->
<g id="node23" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2380.3431" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2380.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge5" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2327.0993,-90.7365C2280.5562,-78.8725 2210.9686,-62.5877 2149.3431,-54 2041.9804,-39.0386 1714.8042,-24.7653 1592.8314,-19.8249"/>
<polygon fill="#000000" stroke="#000000" points="1592.8327,-16.3222 1582.6999,-19.417 1592.551,-23.3166 1592.8327,-16.3222"/>
<text text-anchor="middle" x="2301.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- diagnosis -->
<g id="node24" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="2197.3431" cy="-279" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="2197.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2157.5888,-266.5889C2149.9287,-264.4973 2141.9281,-262.5165 2134.3431,-261 2100.5566,-254.2451 2009.2482,-261.7525 1980.3431,-243 1950.4172,-223.5853 1965.0696,-198.7112 1939.3431,-174 1917.113,-152.6471 1908.0772,-149.1245 1878.3431,-141 1775.5902,-112.924 1504.7766,-138.1726 1399.3431,-123 1393.9151,-122.2189 1388.3011,-121.1901 1382.7177,-120.0193"/>
<polygon fill="#000000" stroke="#000000" points="1383.2713,-116.5566 1372.7475,-117.7813 1381.7381,-123.3866 1383.2713,-116.5566"/>
<text text-anchor="middle" x="2002.8431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2228.2523,-264.1571C2236.896,-258.6289 2245.5105,-251.5693 2251.3431,-243 2255.8791,-236.3358 2258.5906,-228.1412 2260.1981,-220.2857"/>
<polygon fill="#000000" stroke="#000000" points="2263.6711,-220.7282 2261.7358,-210.3116 2256.7529,-219.6615 2263.6711,-220.7282"/>
<text text-anchor="middle" x="2301.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- cytogenomic_file -->
<g id="node25" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="2035.3431" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="2035.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge28" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2059.9152,-261.6363C2068.0638,-255.7912 2077.1446,-249.183 2085.3431,-243 2093.9331,-236.5219 2094.6374,-232.6425 2104.3431,-228 2137.4353,-212.1712 2177.8058,-203.1276 2209.4557,-198.0636"/>
<polygon fill="#000000" stroke="#000000" points="2210.0424,-201.5147 2219.405,-196.5557 2208.9934,-194.5938 2210.0424,-201.5147"/>
<text text-anchor="middle" x="2175.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
</g>
</svg>
</div>
