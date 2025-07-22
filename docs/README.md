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
<svg width="2899pt" height="392pt"
 viewBox="0.00 0.00 2898.74 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 2894.7376,-388 2894.7376,4 -4,4"/>
<!-- sequencing_file -->
<g id="node1" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2337.9954" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="2337.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sample -->
<g id="node28" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2087.9954" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2087.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2322.8455,-348.142C2312.2741,-336.8665 2297.2,-322.9712 2280.9954,-315 2256.7961,-303.0961 2188.7689,-292.1533 2140.3441,-285.5318"/>
<polygon fill="#000000" stroke="#000000" points="2140.7083,-282.0493 2130.3311,-284.1856 2139.7755,-288.9869 2140.7083,-282.0493"/>
<text text-anchor="middle" x="2369.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- medical_history -->
<g id="node2" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="480.9954" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="480.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- participant -->
<g id="node26" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1215.9954" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1215.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge36" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M468.4379,-260.8701C462.6171,-250.0585 458.6336,-236.7733 466.9954,-228 490.0937,-203.7648 959.8151,-195.2321 1143.3803,-192.8157"/>
<polygon fill="#000000" stroke="#000000" points="1143.5258,-196.3142 1153.4796,-192.6851 1143.4352,-189.3147 1143.5258,-196.3142"/>
<text text-anchor="middle" x="534.9954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- methylation_array_file -->
<g id="node3" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2554.9954" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2554.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2513.694,-349.1232C2499.7337,-343.2558 2484.1115,-336.5105 2469.9954,-330 2456.4586,-323.7567 2454.3104,-319.1595 2439.9954,-315 2385.5616,-299.1832 2226.6739,-287.4618 2142.2254,-282.1511"/>
<polygon fill="#000000" stroke="#000000" points="2142.2577,-278.6465 2132.06,-281.5202 2141.824,-285.633 2142.2577,-278.6465"/>
<text text-anchor="middle" x="2561.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- consent_group -->
<g id="node4" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="910.9954" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="910.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- study -->
<g id="node11" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1070.9954" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1070.9954" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge9" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M917.1358,-87.0004C921.7807,-75.9593 929.2213,-62.3787 939.9954,-54 953.5618,-43.4498 994.1331,-33.2453 1026.5679,-26.4117"/>
<polygon fill="#000000" stroke="#000000" points="1027.6776,-29.7569 1036.7682,-24.3153 1026.2683,-22.9002 1027.6776,-29.7569"/>
<text text-anchor="middle" x="1003.4954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- synonym -->
<g id="node5" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="51.9954" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="51.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge40" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M36.4219,-348.7467C23.0769,-332.1293 5.9954,-305.6534 5.9954,-279 5.9954,-279 5.9954,-279 5.9954,-105 5.9954,-53.1182 819.4573,-25.4703 1024.5074,-19.3252"/>
<polygon fill="#000000" stroke="#000000" points="1024.7521,-22.8196 1034.6438,-19.0241 1024.5442,-15.8226 1024.7521,-22.8196"/>
<text text-anchor="middle" x="48.4954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge38" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M61.0737,-348.2089C74.3059,-324.2323 101.2593,-282.1245 136.9954,-261 208.5166,-218.722 238.4043,-237.0242 320.9954,-228 479.7316,-210.656 959.7647,-197.9714 1143.4404,-193.6323"/>
<polygon fill="#000000" stroke="#000000" points="1143.6208,-197.1291 1153.5359,-193.3952 1143.4564,-190.1311 1143.6208,-197.1291"/>
<text text-anchor="middle" x="179.4954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge39" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M102.7683,-361.8892C228.9044,-351.8646 566.7147,-326.167 848.9954,-315 980.6853,-309.7903 1905.1311,-319.4643 2034.9954,-297 2038.7088,-296.3576 2042.5135,-295.4968 2046.2965,-294.4985"/>
<polygon fill="#000000" stroke="#000000" points="2047.5766,-297.7703 2056.1822,-291.5901 2045.6009,-291.0548 2047.5766,-297.7703"/>
<text text-anchor="middle" x="891.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- exposure -->
<g id="node6" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1338.9954" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1338.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1333.1176,-260.8418C1328.794,-250.0196 1321.9259,-236.7332 1311.9954,-228 1301.4547,-218.7302 1288.2984,-211.7553 1275.1382,-206.5411"/>
<polygon fill="#000000" stroke="#000000" points="1276.186,-203.1976 1265.5922,-203.0479 1273.7804,-209.7713 1276.186,-203.1976"/>
<text text-anchor="middle" x="1367.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- pdx -->
<g id="node7" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2411.9954" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2411.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge10" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2385.6712,-185.7554C2291.1516,-163.6055 1959.7745,-88.2962 1681.9954,-54 1472.4717,-28.131 1220.1563,-20.732 1117.6654,-18.7155"/>
<polygon fill="#000000" stroke="#000000" points="1117.708,-15.2158 1107.6437,-18.5263 1117.5758,-22.2146 1117.708,-15.2158"/>
<text text-anchor="middle" x="2114.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2385.9393,-198.9965C2331.3181,-213.6633 2204.166,-247.806 2134.9401,-266.3945"/>
<polygon fill="#000000" stroke="#000000" points="2133.9125,-263.0463 2125.1623,-269.02 2135.7279,-269.8069 2133.9125,-263.0463"/>
<text text-anchor="middle" x="2292.9954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- treatment_response -->
<g id="node8" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1514.9954" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1514.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge37" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1486.2317,-261.4711C1466.7629,-250.3346 1440.1099,-236.4704 1414.9954,-228 1373.0041,-213.8375 1324.0439,-204.8891 1285.1948,-199.456"/>
<polygon fill="#000000" stroke="#000000" points="1285.4131,-195.9538 1275.0344,-198.0825 1284.4753,-202.8907 1285.4131,-195.9538"/>
<text text-anchor="middle" x="1532.9954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- study_personnel -->
<g id="node9" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="726.9954" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="726.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge14" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M742.3203,-86.8246C753.0388,-75.4152 768.3688,-61.4897 784.9954,-54 826.7144,-35.207 954.7604,-24.8935 1024.5187,-20.5344"/>
<polygon fill="#000000" stroke="#000000" points="1025.0126,-24.0109 1034.7814,-19.9098 1024.5873,-17.0238 1025.0126,-24.0109"/>
<text text-anchor="middle" x="854.4954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- generic_file -->
<g id="node10" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="563.9954" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="563.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge4" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M503.3959,-359.0018C391.7769,-345.2856 164.9954,-313.2085 164.9954,-279 164.9954,-279 164.9954,-279 164.9954,-105 164.9954,-61.3803 839.2062,-28.2754 1024.4142,-20.0043"/>
<polygon fill="#000000" stroke="#000000" points="1024.8039,-23.4906 1034.639,-19.5508 1024.4937,-16.4974 1024.8039,-23.4906"/>
<text text-anchor="middle" x="217.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M570.3332,-347.9438C579.6971,-324.0621 599.5868,-282.4931 630.9954,-261 672.6687,-232.4827 998.2577,-206.8968 1144.8618,-196.6939"/>
<polygon fill="#000000" stroke="#000000" points="1145.3668,-200.1674 1155.1016,-195.986 1144.884,-193.1841 1145.3668,-200.1674"/>
<text text-anchor="middle" x="683.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M610.7227,-353.3107C619.7174,-351.2448 629.1056,-349.3445 637.9954,-348 645.3563,-346.8867 1165.557,-315.3069 1172.9954,-315 1268.7126,-311.0502 1940.6456,-313.5981 2034.9954,-297 2038.707,-296.3471 2042.5103,-295.4788 2046.2925,-294.4756"/>
<polygon fill="#000000" stroke="#000000" points="2047.5759,-297.7462 2056.1769,-291.5596 2045.5952,-291.0322 2047.5759,-297.7462"/>
<text text-anchor="middle" x="1225.9954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- publication -->
<g id="node12" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="1070.9954" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="1070.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge12" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1070.9954,-86.9735C1070.9954,-75.1918 1070.9954,-59.5607 1070.9954,-46.1581"/>
<polygon fill="#000000" stroke="#000000" points="1074.4955,-46.0033 1070.9954,-36.0034 1067.4955,-46.0034 1074.4955,-46.0033"/>
<text text-anchor="middle" x="1121.9954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- pathology_file -->
<g id="node13" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1962.9954" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1962.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1972.2609,-347.9499C1978.5634,-337.1683 1987.7843,-323.8866 1998.9954,-315 2006.6146,-308.9605 2025.7729,-300.9492 2044.3707,-294.0175"/>
<polygon fill="#000000" stroke="#000000" points="2045.7888,-297.2257 2053.981,-290.5072 2043.3871,-290.6506 2045.7888,-297.2257"/>
<text text-anchor="middle" x="2059.9954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- family_relationship -->
<g id="node14" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1033.9954" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1033.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1035.2547,-260.5095C1036.98,-249.5622 1040.9512,-236.2611 1049.9954,-228 1064.3863,-214.8551 1108.1752,-205.6867 1147.1654,-199.8929"/>
<polygon fill="#000000" stroke="#000000" points="1148.0741,-203.2987 1157.4788,-198.4201 1147.0844,-196.369 1148.0741,-203.2987"/>
<text text-anchor="middle" x="1129.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- study_admin -->
<g id="node15" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1221.9954" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1221.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1209.6804,-86.7768C1201.5264,-75.9301 1189.9677,-62.6408 1176.9954,-54 1158.3149,-41.5569 1134.9163,-33.0141 1114.8584,-27.3849"/>
<polygon fill="#000000" stroke="#000000" points="1115.5799,-23.9554 1105.0169,-24.7765 1113.7864,-30.7217 1115.5799,-23.9554"/>
<text text-anchor="middle" x="1250.4954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- study_funding -->
<g id="node16" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="1387.9954" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="1387.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge29" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1367.1628,-87.5422C1352.4114,-76.1384 1331.6498,-61.9386 1310.9954,-54 1276.492,-40.7386 1176.5378,-28.7438 1117.0633,-22.5095"/>
<polygon fill="#000000" stroke="#000000" points="1117.1181,-18.9966 1106.8112,-21.4498 1116.3983,-25.9595 1117.1181,-18.9966"/>
<text text-anchor="middle" x="1402.9954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- treatment -->
<g id="node17" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="1209.9954" cy="-279" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="1209.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1211.2386,-260.9735C1212.0511,-249.1918 1213.1291,-233.5607 1214.0535,-220.1581"/>
<polygon fill="#000000" stroke="#000000" points="1217.5574,-220.2205 1214.7538,-210.0034 1210.574,-219.7388 1217.5574,-220.2205"/>
<text text-anchor="middle" x="1260.9954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- cell_line -->
<g id="node18" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2049.9954" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2049.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge15" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2000.7736,-190.2674C1885.9628,-185.4847 1604.0442,-169.2409 1522.9954,-123 1489.1716,-103.7025 1503.1982,-72.6176 1468.9954,-54 1438.7531,-37.5382 1216.0841,-24.9593 1117.6107,-20.1402"/>
<polygon fill="#000000" stroke="#000000" points="1117.5137,-16.6315 1107.3564,-19.6445 1117.1757,-23.6234 1117.5137,-16.6315"/>
<text text-anchor="middle" x="1563.4954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2047.0713,-210.1785C2046.2426,-220.2489 2046.5542,-232.7635 2050.9954,-243 2052.9863,-247.5889 2055.8678,-251.888 2059.1569,-255.8056"/>
<polygon fill="#000000" stroke="#000000" points="2056.8784,-258.4864 2066.326,-263.2816 2061.9308,-253.6414 2056.8784,-258.4864"/>
<text text-anchor="middle" x="2091.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cytogenomic_file -->
<g id="node19" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="2146.9954" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="2146.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2141.0695,-347.6432C2137.3248,-337.517 2131.8876,-325.006 2124.9954,-315 2122.0212,-310.6822 2118.4742,-306.4578 2114.7715,-302.5097"/>
<polygon fill="#000000" stroke="#000000" points="2117.1144,-299.9028 2107.5688,-295.3059 2112.1643,-304.8522 2117.1144,-299.9028"/>
<text text-anchor="middle" x="2205.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- study_arm -->
<g id="node20" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1672.9954" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1672.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge28" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1638.8555,-90.1501C1609.9211,-78.2609 1567.0267,-62.2544 1527.9954,-54 1450.5368,-37.6189 1217.4428,-24.9555 1117.414,-20.1256"/>
<polygon fill="#000000" stroke="#000000" points="1117.4627,-16.624 1107.3069,-19.6424 1117.1283,-23.616 1117.4627,-16.624"/>
<text text-anchor="middle" x="1629.4954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- clinical_measure_file -->
<g id="node21" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="755.9954" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="755.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge3" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M677.3751,-353.5629C664.5574,-351.6336 651.414,-349.7143 638.9954,-348 546.5152,-335.234 283.8723,-366.9057 221.9954,-297 211.3906,-285.0192 213.1698,-274.3457 221.9954,-261 292.4265,-154.4969 632.4743,-77.4077 757.9954,-54 851.7784,-36.5109 963.0553,-26.1425 1024.4594,-21.3099"/>
<polygon fill="#000000" stroke="#000000" points="1024.9018,-24.7863 1034.6025,-20.5265 1024.3627,-17.8071 1024.9018,-24.7863"/>
<text text-anchor="middle" x="427.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M748.8921,-347.9803C741.1088,-324.9045 732.2772,-285.0345 752.9954,-261 778.2527,-231.6997 1022.0484,-207.8157 1145.3399,-197.4988"/>
<polygon fill="#000000" stroke="#000000" points="1145.7681,-200.9754 1155.4447,-196.6611 1145.1897,-193.9994 1145.7681,-200.9754"/>
<text text-anchor="middle" x="838.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M856.0021,-358.9593C1033.3096,-346.5419 1396.0445,-321.4506 1522.9954,-315 1636.6968,-309.2226 1923.0127,-317.5245 2034.9954,-297 2038.6515,-296.3299 2042.3982,-295.4582 2046.1269,-294.4601"/>
<polygon fill="#000000" stroke="#000000" points="2047.2839,-297.7678 2055.8801,-291.5746 2045.298,-291.0554 2047.2839,-297.7678"/>
<text text-anchor="middle" x="1608.9954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- diagnosis -->
<g id="node22" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1632.9954" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1632.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1638.4522,-347.8491C1639.9052,-342.1864 1641.2712,-335.8826 1641.9954,-330 1647.6617,-283.9717 1655.5637,-257.7592 1619.9954,-228 1595.2092,-207.262 1398.2204,-197.754 1288.7486,-194.0342"/>
<polygon fill="#000000" stroke="#000000" points="1288.5471,-190.5257 1278.4365,-193.6921 1288.3149,-197.5218 1288.5471,-190.5257"/>
<text text-anchor="middle" x="1691.4954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge32" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1658.3753,-349.9948C1678.7733,-338.0289 1708.608,-322.4948 1736.9954,-315 1865.2853,-281.1292 1904.7952,-322.5623 2034.9954,-297 2038.6427,-296.2839 2042.3833,-295.38 2046.1079,-294.3603"/>
<polygon fill="#000000" stroke="#000000" points="2047.2797,-297.663 2055.8546,-291.4404 2045.2708,-290.9575 2047.2797,-297.663"/>
<text text-anchor="middle" x="1781.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- genetic_analysis -->
<g id="node23" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="2802.9954" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="2802.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2814.7493,-348.1115C2820.1896,-337.3907 2823.8926,-324.1163 2815.9954,-315 2793.7977,-289.3758 2245.7613,-231.0333 2211.9954,-228 2032.6366,-211.8877 1486.4786,-198.1768 1288.5781,-193.6142"/>
<polygon fill="#000000" stroke="#000000" points="1288.3716,-190.1087 1278.2938,-193.3781 1288.2108,-197.1068 1288.3716,-190.1087"/>
<text text-anchor="middle" x="2816.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2742.5504,-352.8479C2721.0355,-347.1375 2696.9587,-339.5397 2675.9954,-330 2664.8874,-324.9451 2664.5769,-318.8479 2652.9954,-315 2605.4303,-299.197 2274.9668,-285.7221 2142.6186,-280.898"/>
<polygon fill="#000000" stroke="#000000" points="2142.4316,-277.389 2132.3116,-280.5252 2142.1785,-284.3845 2142.4316,-277.389"/>
<text text-anchor="middle" x="2745.9954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- survival -->
<g id="node24" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1977.9954" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1977.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1939.9886,-267.8596C1932.0663,-265.5673 1923.7635,-263.1868 1915.9954,-261 1902.5813,-257.2239 1808.7435,-230.2776 1794.9954,-228 1699.489,-212.1779 1420.9146,-199.8178 1288.0775,-194.6425"/>
<polygon fill="#000000" stroke="#000000" points="1288.1258,-191.1419 1277.998,-194.2527 1287.8552,-198.1367 1288.1258,-191.1419"/>
<text text-anchor="middle" x="1889.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- radiology_file -->
<g id="node25" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="303.9954" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="303.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M311.8519,-261.0287C317.9789,-249.3957 327.6913,-235.1329 340.9954,-228 376.0823,-209.1883 939.648,-197.0579 1143.2984,-193.2706"/>
<polygon fill="#000000" stroke="#000000" points="1143.6562,-196.7647 1153.5899,-193.0806 1143.527,-189.7659 1143.6562,-196.7647"/>
<text text-anchor="middle" x="399.9954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge20" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1171.3191,-179.2563C1118.2167,-164.109 1029.4028,-138.7752 970.5113,-121.9767"/>
<polygon fill="#000000" stroke="#000000" points="971.1802,-118.5279 960.6036,-119.1506 969.26,-125.2594 971.1802,-118.5279"/>
<text text-anchor="middle" x="1132.4954" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- laboratory_test -->
<g id="node27" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1786.9954" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1786.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1740.2236,-350.9861C1730.9933,-345.8182 1722.4765,-338.9824 1716.9954,-330 1713.5228,-324.3092 1714.0754,-320.9932 1716.9954,-315 1722.6809,-303.3309 1734.3099,-308.6691 1739.9954,-297 1747.0034,-282.6164 1749.3309,-273.9942 1739.9954,-261 1713.1799,-223.6754 1686.9958,-237.3358 1641.9954,-228 1576.2346,-214.3573 1390.5576,-202.0125 1287.3726,-195.9485"/>
<polygon fill="#000000" stroke="#000000" points="1287.5332,-192.452 1277.3464,-195.3638 1287.1256,-199.4401 1287.5332,-192.452"/>
<text text-anchor="middle" x="1812.4954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge35" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1806.3277,-348.2682C1821.0721,-335.1546 1840.4241,-318.9204 1849.9954,-315 1926.4416,-283.6875 1954.2378,-314.3984 2034.9954,-297 2038.5785,-296.2281 2042.2564,-295.2928 2045.9232,-294.2592"/>
<polygon fill="#000000" stroke="#000000" points="2046.9819,-297.5956 2055.5312,-291.3378 2044.9455,-290.8983 2046.9819,-297.5956"/>
<text text-anchor="middle" x="1915.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge24" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2132.055,-276.8721C2179.7599,-273.5027 2257.5349,-264.8829 2320.9954,-243 2343.5941,-235.2074 2367.0805,-221.8927 2384.5316,-210.8218"/>
<polygon fill="#000000" stroke="#000000" points="2386.589,-213.6591 2393.0706,-205.2781 2382.7773,-207.7878 2386.589,-213.6591"/>
<text text-anchor="middle" x="2388.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge23" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2114.2877,-264.2306C2128.1068,-254.478 2140.5639,-241.1197 2131.9954,-228 2125.0858,-217.4204 2114.2987,-209.9298 2102.7924,-204.6333"/>
<polygon fill="#000000" stroke="#000000" points="2104.0525,-201.3674 2093.4709,-200.8388 2101.4133,-207.8508 2104.0525,-201.3674"/>
<text text-anchor="middle" x="2171.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2054.1544,-267.2076C2047.8077,-265.0811 2041.2139,-262.9289 2034.9954,-261 2006.7739,-252.2458 1999.0372,-252.3136 1970.9954,-243 1953.3709,-237.1463 1950.1636,-231.8478 1931.9954,-228 1810.839,-202.3404 1445.3713,-194.8199 1288.6453,-192.7431"/>
<polygon fill="#000000" stroke="#000000" points="1288.673,-189.2432 1278.6287,-192.614 1288.5827,-196.2426 1288.673,-189.2432"/>
<text text-anchor="middle" x="2007.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
</g>
</svg>
</div>
