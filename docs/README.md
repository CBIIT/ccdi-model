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
<svg width="3183pt" height="392pt"
 viewBox="0.00 0.00 3182.79 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3178.786,-388 3178.786,4 -4,4"/>
<!-- exposure -->
<g id="node1" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1461.786" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1461.786" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- participant -->
<g id="node5" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1144.786" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1144.786" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1435.0727,-176.263C1424.6352,-170.0384 1412.5986,-162.7663 1401.786,-156 1391.4407,-149.5261 1390.1849,-145.3594 1378.786,-141 1349.4505,-129.781 1271.7486,-119.1274 1213.8812,-112.3623"/>
<polygon fill="#000000" stroke="#000000" points="1214.0224,-108.8554 1203.6871,-111.1865 1213.2202,-115.8093 1214.0224,-108.8554"/>
<text text-anchor="middle" x="1445.286" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- pathology_file -->
<g id="node2" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2983.786" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2983.786" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- cell_line -->
<g id="node3" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2528.786" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2528.786" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge3" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2927.615,-353.757C2918.011,-351.7635 2908.1222,-349.773 2898.786,-348 2851.409,-339.0027 2839.2384,-338.5908 2791.786,-330 2718.909,-316.8062 2634.9367,-300.2937 2581.869,-289.6958"/>
<polygon fill="#000000" stroke="#000000" points="2582.4971,-286.2522 2572.0049,-287.7229 2581.1242,-293.1163 2582.4971,-286.2522"/>
<text text-anchor="middle" x="2852.786" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- sample -->
<g id="node12" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2328.786" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2328.786" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2969.9943,-348.0031C2950.7179,-324.1886 2913.377,-282.6955 2871.786,-261 2787.4614,-217.013 2503.032,-199.6286 2382.9743,-194.1378"/>
<polygon fill="#000000" stroke="#000000" points="2383.051,-190.6378 2372.9047,-193.6876 2382.7383,-197.6308 2383.051,-190.6378"/>
<text text-anchor="middle" x="2981.786" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pdx -->
<g id="node16" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2398.786" cy="-105" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2398.786" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge2" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M3006.76,-348.5638C3021.2724,-336.0236 3038.7501,-317.7193 3046.786,-297 3057.8764,-268.4055 3062.1198,-253.9586 3045.786,-228 3001.0054,-156.8318 2958.6786,-163.9481 2877.786,-141 2795.1531,-117.5582 2535.3584,-108.5325 2437.0171,-105.9009"/>
<polygon fill="#000000" stroke="#000000" points="2437.0144,-102.3997 2426.9267,-105.6383 2436.8322,-109.3974 2437.0144,-102.3997"/>
<text text-anchor="middle" x="3113.786" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2488.9449,-268.3525C2478.5219,-265.7561 2467.2683,-263.119 2456.786,-261 2405.6479,-250.6624 2392.2403,-251.6272 2340.786,-243 2088.6971,-200.7331 2028.6256,-171.013 1774.786,-141 1668.7129,-128.4583 1358.7137,-114.1359 1216.9918,-108.022"/>
<polygon fill="#000000" stroke="#000000" points="1216.815,-104.5113 1206.6739,-107.5786 1216.5144,-111.5049 1216.815,-104.5113"/>
<text text-anchor="middle" x="2201.286" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- study -->
<g id="node7" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1917.786" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1917.786" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge30" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2576.3702,-274.1604C2635.593,-267.6494 2730.278,-255.4428 2740.786,-243 2745.0874,-237.9066 2744.3773,-233.6167 2740.786,-228 2638.7599,-68.4328 2536.2575,-96.9101 2351.786,-54 2279.1363,-37.1009 2060.659,-24.8659 1964.303,-20.1442"/>
<polygon fill="#000000" stroke="#000000" points="1964.4272,-16.6462 1954.2695,-19.6581 1964.0884,-23.638 1964.4272,-16.6462"/>
<text text-anchor="middle" x="2721.286" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2490.6467,-267.3747C2482.4861,-265.0921 2473.8838,-262.8385 2465.786,-261 2419.1864,-250.4201 2399.3215,-269.8403 2359.786,-243 2351.133,-237.1255 2344.4842,-227.9549 2339.6044,-219.0007"/>
<polygon fill="#000000" stroke="#000000" points="2342.6881,-217.3395 2335.1495,-209.895 2336.4003,-220.4158 2342.6881,-217.3395"/>
<text text-anchor="middle" x="2400.286" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- publication -->
<g id="node4" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="1001.786" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="1001.786" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge21" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1048.11,-92.6951C1056.6166,-90.6421 1065.4433,-88.6477 1073.786,-87 1173.372,-67.3322 1198.7998,-64.2946 1299.786,-54 1512.4685,-32.319 1767.7604,-22.5957 1871.0336,-19.3375"/>
<polygon fill="#000000" stroke="#000000" points="1871.2415,-22.8329 1881.1281,-19.0245 1871.0244,-15.8362 1871.2415,-22.8329"/>
<text text-anchor="middle" x="1350.786" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge10" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1200.2822,-96.6579C1273.3905,-85.8509 1406.0238,-66.8743 1519.786,-54 1646.7662,-39.6299 1797.0579,-27.3019 1871.3812,-21.5166"/>
<polygon fill="#000000" stroke="#000000" points="1872.084,-24.9727 1881.7839,-20.711 1871.5435,-17.9936 1872.084,-24.9727"/>
<text text-anchor="middle" x="1570.286" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- medical_history -->
<g id="node6" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="534.786" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="534.786" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M522.1809,-173.8243C516.3421,-162.9955 512.3565,-149.7083 520.786,-141 542.1649,-118.9139 1043.35,-127.3019 1073.786,-123 1079.216,-122.2325 1084.8313,-121.2128 1090.4155,-120.0476"/>
<polygon fill="#000000" stroke="#000000" points="1091.3923,-123.4157 1100.3866,-117.8163 1089.8636,-116.5846 1091.3923,-123.4157"/>
<text text-anchor="middle" x="588.786" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- family_relationship -->
<g id="node8" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="858.786" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="858.786" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge38" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M859.5939,-173.8593C861.117,-162.6153 865.0331,-148.8626 874.786,-141 909.3542,-113.1316 1030.0177,-130.4793 1073.786,-123 1078.9037,-122.1255 1084.1949,-121.0721 1089.4741,-119.9191"/>
<polygon fill="#000000" stroke="#000000" points="1090.6011,-123.2514 1099.5628,-117.5999 1089.0328,-116.4293 1090.6011,-123.2514"/>
<text text-anchor="middle" x="954.286" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- study_personnel -->
<g id="node9" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="1630.786" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1630.786" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1625.7598,-86.8119C1623.9464,-75.9784 1623.9679,-62.6907 1631.786,-54 1647.5094,-36.5217 1794.2467,-25.3058 1871.1898,-20.576"/>
<polygon fill="#000000" stroke="#000000" points="1871.7911,-24.0463 1881.5627,-19.9517 1871.3705,-17.0589 1871.7911,-24.0463"/>
<text text-anchor="middle" x="1701.286" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- synonym -->
<g id="node10" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="655.786" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="655.786" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M651.3262,-260.7899C646.8115,-237.5083 643.2184,-197.416 664.786,-174 726.8382,-106.6297 983.4539,-138.1439 1073.786,-123 1079.1161,-122.1064 1084.6332,-121.0135 1090.1285,-119.8119"/>
<polygon fill="#000000" stroke="#000000" points="1090.9907,-123.205 1099.9511,-117.5515 1089.4208,-116.3833 1090.9907,-123.205"/>
<text text-anchor="middle" x="707.286" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge17" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M603.7659,-278.4048C421.9997,-275.3248 -162.7812,-256.4155 43.786,-141 207.8372,-49.3395 1596.2614,-23.0163 1870.7516,-18.6877"/>
<polygon fill="#000000" stroke="#000000" points="1871.2066,-22.1812 1881.1509,-18.5259 1871.0977,-15.182 1871.2066,-22.1812"/>
<text text-anchor="middle" x="86.286" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M708.0766,-278.8198C904.9443,-277.9172 1595.0591,-272.6485 1688.786,-243 1700.4218,-239.3193 1700.1502,-231.6805 1711.786,-228 1821.3921,-193.3305 2114.4782,-222.214 2228.786,-210 2245.3328,-208.232 2263.2638,-205.3227 2279.312,-202.3534"/>
<polygon fill="#000000" stroke="#000000" points="2280.383,-205.7125 2289.5525,-200.4049 2279.0745,-198.8358 2280.383,-205.7125"/>
<text text-anchor="middle" x="1754.286" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study_funding -->
<g id="node11" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2051.786" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2051.786" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge20" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2025.6314,-88.019C2003.4793,-73.6367 1971.6942,-53.0001 1948.3685,-37.8558"/>
<polygon fill="#000000" stroke="#000000" points="1950.1738,-34.8549 1939.8805,-32.3449 1946.3619,-40.726 1950.1738,-34.8549"/>
<text text-anchor="middle" x="2054.786" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge11" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2367.1317,-201.0326C2390.2249,-207.1674 2419.8824,-216.2938 2444.786,-228 2455.8307,-233.1917 2457.4172,-236.5637 2467.786,-243 2475.9957,-248.0961 2484.9127,-253.4555 2493.3293,-258.4364"/>
<polygon fill="#000000" stroke="#000000" points="2491.8152,-261.6065 2502.2087,-263.6624 2495.3658,-255.5737 2491.8152,-261.6065"/>
<text text-anchor="middle" x="2504.286" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2296.5937,-179.6426C2262.6524,-167.2718 2207.3372,-148.9643 2157.786,-141 2021.0389,-119.0208 1673.1908,-128.193 1534.786,-123 1423.6157,-118.8288 1294.6843,-112.6072 1216.4636,-108.679"/>
<polygon fill="#000000" stroke="#000000" points="1216.404,-105.1717 1206.2406,-108.1642 1216.0519,-112.1628 1216.404,-105.1717"/>
<text text-anchor="middle" x="2256.286" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge12" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2317.7019,-174.3148C2312.7228,-163.9272 2309.2686,-150.9309 2315.786,-141 2326.0157,-125.4126 2344.6039,-116.5403 2361.5999,-111.5071"/>
<polygon fill="#000000" stroke="#000000" points="2362.5542,-114.8754 2371.3476,-108.9656 2360.788,-108.1019 2362.5542,-114.8754"/>
<text text-anchor="middle" x="2352.286" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_arm -->
<g id="node13" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2206.786" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2206.786" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge33" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2183.8489,-88.2841C2167.1536,-76.916 2143.5693,-62.4561 2120.786,-54 2069.1252,-34.8259 2006.1834,-25.6939 1964.2125,-21.4603"/>
<polygon fill="#000000" stroke="#000000" points="1964.3009,-17.9529 1954.0134,-20.4864 1963.6354,-24.9212 1964.3009,-17.9529"/>
<text text-anchor="middle" x="2198.286" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node14" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2076.786" cy="-366" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="2076.786" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge39" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2094.9267,-347.9301C2107.91,-336.2532 2126.45,-321.9783 2145.786,-315 2212.7802,-290.822 2395.5563,-308.8563 2465.786,-297 2471.1138,-296.1005 2476.6335,-294.9152 2482.0903,-293.581"/>
<polygon fill="#000000" stroke="#000000" points="2482.9986,-296.9612 2491.7899,-291.0482 2481.23,-290.1883 2482.9986,-296.9612"/>
<text text-anchor="middle" x="2254.286" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge40" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2070.5019,-347.9488C2063.8295,-325.2035 2056.6427,-286.0634 2075.786,-261 2088.2645,-244.6626 2209.0735,-217.0316 2279.1393,-202.1755"/>
<polygon fill="#000000" stroke="#000000" points="2280.0262,-205.5655 2289.0898,-200.0791 2278.583,-198.7159 2280.0262,-205.5655"/>
<text text-anchor="middle" x="2184.286" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge41" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1968.5071,-354.8584C1939.2718,-349.523 1908.1678,-341.6407 1880.786,-330 1846.8671,-315.5803 1816.1406,-292.7926 1834.786,-261 1911.4167,-130.3359 2004.5652,-167.0489 2153.786,-141 2158.8613,-140.114 2293.7765,-120.3596 2361.1861,-110.4984"/>
<polygon fill="#000000" stroke="#000000" points="2362.007,-113.9156 2371.3951,-109.0051 2360.9938,-106.9893 2362.007,-113.9156"/>
<text text-anchor="middle" x="1964.286" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- therapeutic_procedure -->
<g id="node15" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="1094.786" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="1094.786" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1058.2953,-174.6923C1044.0077,-165.4827 1032.9165,-153.4956 1041.786,-141 1047.6044,-132.8028 1066.3018,-125.2149 1086.1994,-119.1399"/>
<polygon fill="#000000" stroke="#000000" points="1087.3894,-122.4388 1096.0125,-116.2831 1085.4328,-115.7178 1087.3894,-122.4388"/>
<text text-anchor="middle" x="1134.786" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge37" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2375.4203,-95.1139C2346.6427,-83.3701 2296.0086,-64.1018 2250.786,-54 2150.2585,-31.5443 2029.4129,-22.9285 1964.4991,-19.7511"/>
<polygon fill="#000000" stroke="#000000" points="1964.3434,-16.2401 1954.191,-19.2696 1964.0167,-23.2325 1964.3434,-16.2401"/>
<text text-anchor="middle" x="2323.786" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge36" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2398.7623,-123.4103C2397.9211,-133.797 2395.4211,-146.547 2388.786,-156 2383.7699,-163.1465 2376.8408,-169.1179 2369.4683,-174.0106"/>
<polygon fill="#000000" stroke="#000000" points="2367.4779,-171.123 2360.6981,-179.2646 2371.0752,-177.1279 2367.4779,-171.123"/>
<text text-anchor="middle" x="2418.786" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- molecular_test -->
<g id="node17" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1310.786" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1310.786" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1281.9647,-175.0045C1272.0358,-169.071 1260.8778,-162.3152 1250.786,-156 1240.4407,-149.5261 1238.5334,-146.782 1227.786,-141 1216.3259,-134.8346 1203.5901,-128.8892 1191.6046,-123.6672"/>
<polygon fill="#000000" stroke="#000000" points="1192.763,-120.3561 1182.1921,-119.644 1190.0117,-126.7927 1192.763,-120.3561"/>
<text text-anchor="middle" x="1314.786" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- clinical_measure_file -->
<g id="node18" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="1650.786" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="1650.786" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1579.6428,-178.2755C1557.3985,-172.7506 1533.1092,-165.4116 1511.786,-156 1500.6212,-151.0721 1500.287,-145.0824 1488.786,-141 1440.2531,-123.7728 1302.3223,-113.4692 1216.5801,-108.5452"/>
<polygon fill="#000000" stroke="#000000" points="1216.5731,-105.0394 1206.392,-107.9713 1216.1793,-112.0283 1216.5731,-105.0394"/>
<text text-anchor="middle" x="1641.286" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge42" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1717.2559,-177.7588C1740.3084,-171.65 1762.473,-164.0649 1770.786,-156 1793.9872,-133.4912 1773.1503,-111.8818 1793.786,-87 1815.6369,-60.653 1850.2939,-42.5804 1877.4205,-31.5612"/>
<polygon fill="#000000" stroke="#000000" points="1878.9868,-34.7074 1887.0362,-27.8184 1876.4477,-28.1842 1878.9868,-34.7074"/>
<text text-anchor="middle" x="1879.786" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- cytogenomic_file -->
<g id="node19" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="2799.786" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="2799.786" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;cell_line -->
<g id="edge29" class="edge">
<title>cytogenomic_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2714.7139,-360.1668C2640.2707,-354.1818 2542.1097,-343.8006 2529.786,-330 2524.3114,-323.8693 2522.6749,-315.4804 2522.8132,-307.2766"/>
<polygon fill="#000000" stroke="#000000" points="2526.312,-307.4563 2523.7822,-297.168 2519.3439,-306.7883 2526.312,-307.4563"/>
<text text-anchor="middle" x="2601.286" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2828.5307,-348.9336C2841.6956,-338.9948 2852.4456,-326.2448 2842.786,-315 2808.2172,-274.7581 2766.4233,-329.8749 2724.786,-297 2698.811,-276.4913 2723.3039,-247.8018 2696.786,-228 2672.2205,-209.656 2479.3857,-198.6425 2383.1024,-194.2342"/>
<polygon fill="#000000" stroke="#000000" points="2383.1221,-190.7317 2372.9749,-193.7786 2382.8074,-197.7246 2383.1221,-190.7317"/>
<text text-anchor="middle" x="2796.286" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;pdx -->
<g id="edge28" class="edge">
<title>cytogenomic_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2835.5438,-349.3978C2843.7903,-344.1721 2851.8679,-337.7083 2857.786,-330 2908.94,-263.3721 2917.3274,-200.2522 2857.786,-141 2842.9299,-126.2161 2544.2441,-111.4892 2436.8399,-106.652"/>
<polygon fill="#000000" stroke="#000000" points="2436.9104,-103.1517 2426.7642,-106.202 2436.598,-110.1447 2436.9104,-103.1517"/>
<text text-anchor="middle" x="2970.286" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- follow_up -->
<g id="node20" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="83.786" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="83.786" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M103.3245,-174.9488C118.4262,-162.9349 140.46,-147.8209 162.786,-141 259.6101,-111.4192 973.4519,-136.5282 1073.786,-123 1079.2995,-122.2566 1085.0022,-121.2416 1090.6683,-120.0695"/>
<polygon fill="#000000" stroke="#000000" points="1091.7806,-123.4075 1100.7791,-117.8148 1090.2571,-116.5753 1091.7806,-123.4075"/>
<text text-anchor="middle" x="207.786" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- diagnosis -->
<g id="node21" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="211.786" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="211.786" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M229.618,-174.7318C243.2411,-162.7771 263.1353,-147.8329 283.786,-141 367.1421,-113.4193 986.7907,-134.8637 1073.786,-123 1079.2984,-122.2483 1085.0003,-121.2278 1090.666,-120.0523"/>
<polygon fill="#000000" stroke="#000000" points="1091.7799,-123.3898 1100.7763,-117.7937 1090.2537,-116.5582 1091.7799,-123.3898"/>
<text text-anchor="middle" x="328.286" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- study_admin -->
<g id="node22" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="2870.786" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2870.786" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge34" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2849.4452,-87.8369C2833.2847,-75.9344 2809.9761,-61.0094 2786.786,-54 2708.035,-30.1967 2133.5692,-20.831 1964.483,-18.5722"/>
<polygon fill="#000000" stroke="#000000" points="1964.449,-15.0716 1954.4038,-18.4396 1964.3568,-22.071 1964.449,-15.0716"/>
<text text-anchor="middle" x="2874.286" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- sequencing_file -->
<g id="node23" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2372.786" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="2372.786" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge25" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2367.9709,-347.9954C2366.2369,-337.231 2366.2678,-323.9514 2373.786,-315 2400.582,-283.0958 2425.2744,-306.7318 2465.786,-297 2470.7062,-295.8181 2475.8188,-294.5034 2480.9082,-293.1378"/>
<polygon fill="#000000" stroke="#000000" points="2481.8961,-296.4961 2490.6105,-290.4704 2480.0405,-289.7465 2481.8961,-296.4961"/>
<text text-anchor="middle" x="2440.286" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge24" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2300.3455,-357.0498C2225.1095,-347.5834 2117.8615,-333.5344 2114.786,-330 2110.4098,-324.9708 2110.31,-319.9406 2114.786,-315 2142.0732,-284.8809 2265.358,-322.7689 2296.786,-297 2319.379,-278.4752 2326.3881,-244.4799 2328.3759,-220.188"/>
<polygon fill="#000000" stroke="#000000" points="2331.8746,-220.3095 2328.9627,-210.1227 2324.8865,-219.902 2331.8746,-220.3095"/>
<text text-anchor="middle" x="2386.286" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge23" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2454.19,-362.244C2579.265,-356.0736 2805.65,-343.1575 2817.786,-330 2822.306,-325.0996 2822.1063,-320.0773 2817.786,-315 2785.3981,-276.9369 2753.5759,-314.5636 2706.786,-297 2647.2045,-274.6348 2489.8846,-168.0227 2426.1653,-124.0401"/>
<polygon fill="#000000" stroke="#000000" points="2428.0307,-121.0747 2417.8153,-118.2649 2424.0488,-126.8319 2428.0307,-121.0747"/>
<text text-anchor="middle" x="2670.286" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- radiology_file -->
<g id="node24" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="357.786" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="357.786" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M365.2755,-173.9796C371.1679,-162.3247 380.5988,-148.0559 393.786,-141 427.1071,-123.1713 1036.3511,-128.1753 1073.786,-123 1079.297,-122.2381 1084.998,-121.2109 1090.6631,-120.0314"/>
<polygon fill="#000000" stroke="#000000" points="1091.779,-123.3683 1100.7727,-117.768 1090.2496,-116.5374 1091.779,-123.3683"/>
<text text-anchor="middle" x="452.786" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- methylation_array_file -->
<g id="node25" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1805.786" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1805.786" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge5" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1839.2527,-348.6801C1864.0714,-336.7833 1899.1212,-321.9332 1931.786,-315 2047.9326,-290.3474 2348.4937,-315.4472 2465.786,-297 2471.1938,-296.1495 2476.7948,-294.9826 2482.3253,-293.6484"/>
<polygon fill="#000000" stroke="#000000" points="2483.3475,-296.9992 2492.1469,-291.0983 2481.5882,-290.2238 2483.3475,-296.9992"/>
<text text-anchor="middle" x="2023.286" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1812.2084,-347.9368C1821.8825,-323.6443 1842.6671,-281.1719 1875.786,-261 1906.5326,-242.273 2001.2206,-248.5815 2036.786,-243 2069.938,-237.7973 2077.7448,-233.8653 2110.786,-228 2163.0205,-218.7276 2176.4531,-218.6999 2228.786,-210 2244.9162,-207.3185 2262.4762,-204.2189 2278.3157,-201.3556"/>
<polygon fill="#000000" stroke="#000000" points="2279.2309,-204.7467 2288.4438,-199.5149 2277.9791,-197.8595 2279.2309,-204.7467"/>
<text text-anchor="middle" x="1967.286" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge6" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1711.9688,-355.4107C1599.0558,-339.1631 1432.7148,-301.8845 1501.786,-228 1522.0917,-206.2793 1739.6833,-216.0946 1768.786,-210 1815.0198,-200.3178 1823.5461,-187.5889 1868.786,-174 1928.3551,-156.1069 1943.3065,-150.4292 2004.786,-141 2124.1007,-122.7006 2155.7514,-135.7493 2275.786,-123 2304.7046,-119.9285 2337.2583,-115.1033 2361.608,-111.2216"/>
<polygon fill="#000000" stroke="#000000" points="2362.1924,-114.6727 2371.5068,-109.6237 2361.0768,-107.7622 2362.1924,-114.6727"/>
<text text-anchor="middle" x="1593.286" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
</g>
</svg>
</div>
