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
<svg width="3024pt" height="392pt"
 viewBox="0.00 0.00 3024.39 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3020.3875,-388 3020.3875,4 -4,4"/>
<!-- pathology_file -->
<g id="node1" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1470.0444" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1470.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- sample -->
<g id="node8" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="855.0444" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="855.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1428.0852,-350.9572C1412.9686,-345.0376 1395.9674,-337.7907 1381.0444,-330 1370.2259,-324.3521 1369.6624,-318.7364 1358.0444,-315 1272.2817,-287.4182 1042.5584,-307.1613 953.0444,-297 937.1118,-295.1914 919.8686,-292.3326 904.3527,-289.4212"/>
<polygon fill="#000000" stroke="#000000" points="904.9187,-285.966 894.4372,-287.5109 903.5945,-292.8396 904.9187,-285.966"/>
<text text-anchor="middle" x="1442.0444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- molecular_test -->
<g id="node2" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1042.0444" cy="-279" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1042.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- participant -->
<g id="node19" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1548.0444" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1548.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1048.7558,-260.97C1054.0465,-249.4685 1062.6242,-235.3815 1075.0444,-228 1108.5708,-208.0748 1351.4554,-197.9261 1475.5168,-193.9951"/>
<polygon fill="#000000" stroke="#000000" points="1475.8046,-197.4879 1485.6908,-193.6783 1475.5866,-190.4913 1475.8046,-197.4879"/>
<text text-anchor="middle" x="1139.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- publication -->
<g id="node3" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="63.0444" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="63.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- study -->
<g id="node6" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="723.0444" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="723.0444" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge34" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M80.95,-87.7159C94.3932,-75.9188 113.8842,-61.1763 134.0444,-54 184.5536,-36.0206 546.2846,-23.3739 676.4935,-19.3605"/>
<polygon fill="#000000" stroke="#000000" points="676.6635,-22.857 686.552,-19.0534 676.4498,-15.8603 676.6635,-22.857"/>
<text text-anchor="middle" x="185.0444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- radiology_file -->
<g id="node4" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1213.0444" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1213.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1207.9638,-260.7626C1206.1299,-249.9105 1206.1491,-236.6206 1214.0444,-228 1231.3909,-209.0601 1382.9966,-199.1403 1475.8886,-194.7946"/>
<polygon fill="#000000" stroke="#000000" points="1476.2479,-198.2819 1486.0777,-194.3292 1475.9284,-191.2892 1476.2479,-198.2819"/>
<text text-anchor="middle" x="1273.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- study_admin -->
<g id="node5" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="214.0444" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="214.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge37" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M224.2921,-87.1232C231.982,-75.5324 243.6428,-61.2813 258.0444,-54 294.7518,-35.4412 566.1422,-23.6635 676.5389,-19.5943"/>
<polygon fill="#000000" stroke="#000000" points="676.8404,-23.0858 686.7066,-19.2246 676.586,-16.0904 676.8404,-23.0858"/>
<text text-anchor="middle" x="314.5444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- study_personnel -->
<g id="node7" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="389.0444" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="389.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge12" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M379.1653,-86.9023C374.7435,-76.1029 372.1025,-62.8191 380.0444,-54 399.5322,-32.3599 587.4911,-22.8197 676.6073,-19.4865"/>
<polygon fill="#000000" stroke="#000000" points="676.8449,-22.9802 686.7112,-19.1194 676.5907,-15.9849 676.8449,-22.9802"/>
<text text-anchor="middle" x="449.5444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M886.6896,-266.2216C923.8972,-251.2073 980.7988,-228.2821 982.0444,-228 1073.9072,-207.198 1344.5847,-197.3817 1475.4995,-193.7493"/>
<polygon fill="#000000" stroke="#000000" points="1475.9209,-197.2392 1485.8217,-193.4677 1475.73,-190.2418 1475.9209,-197.2392"/>
<text text-anchor="middle" x="1018.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node21" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="675.0444" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="675.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge21" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M813.3223,-272.8329C788.5583,-269.2359 756.5329,-264.6941 728.0444,-261 694.0942,-256.5976 597.7937,-268.5826 575.0444,-243 570.6143,-238.0182 571.211,-233.4543 575.0444,-228 578.4132,-223.2069 603.0511,-214.3093 627.0257,-206.5594"/>
<polygon fill="#000000" stroke="#000000" points="628.373,-209.8037 636.8401,-203.4352 626.2496,-203.1335 628.373,-209.8037"/>
<text text-anchor="middle" x="611.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node25" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="840.0444" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="840.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge23" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M851.9364,-260.9735C849.9051,-249.1918 847.21,-233.5607 844.8992,-220.1581"/>
<polygon fill="#000000" stroke="#000000" points="848.2967,-219.2633 843.1484,-210.0034 841.3985,-220.4527 848.2967,-219.2633"/>
<text text-anchor="middle" x="884.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- generic_file -->
<g id="node9" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="1789.0444" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="1789.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge15" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1854.8285,-365.4119C2050.2585,-363.0544 2624.8303,-351.5437 2803.0444,-297 2818.2788,-292.3374 2834.0444,-294.932 2834.0444,-279 2834.0444,-279 2834.0444,-279 2834.0444,-105 2834.0444,-51.504 1080.0732,-23.2477 769.6972,-18.6663"/>
<polygon fill="#000000" stroke="#000000" points="769.7351,-15.1666 759.6848,-18.5194 769.6323,-22.1658 769.7351,-15.1666"/>
<text text-anchor="middle" x="2887.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1744.4131,-352.6058C1694.0787,-337.5008 1619.1454,-315.0162 1619.0444,-315 1472.8635,-291.5236 1100.2933,-312.4192 953.0444,-297 936.9556,-295.3153 919.5439,-292.4594 903.9228,-289.5129"/>
<polygon fill="#000000" stroke="#000000" points="904.4319,-286.0465 893.9479,-287.575 903.0968,-292.918 904.4319,-286.0465"/>
<text text-anchor="middle" x="1717.0444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1792.9155,-347.9398C1798.0589,-318.5281 1803.2038,-260.3271 1772.0444,-228 1761.2826,-216.8349 1678.9928,-205.7831 1617.2511,-198.9304"/>
<polygon fill="#000000" stroke="#000000" points="1617.4677,-195.4333 1607.1465,-197.8257 1616.7068,-202.3919 1617.4677,-195.4333"/>
<text text-anchor="middle" x="1849.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- study_arm -->
<g id="node10" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="611.0444" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="611.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge13" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M606.5469,-86.8166C605.0333,-76.2524 605.184,-63.2453 612.0444,-54 620.3503,-42.8067 651.7966,-33.2455 679.1074,-26.7957"/>
<polygon fill="#000000" stroke="#000000" points="679.956,-30.1922 688.9316,-24.563 678.4046,-23.3663 679.956,-30.1922"/>
<text text-anchor="middle" x="660.5444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- genetic_analysis -->
<g id="node11" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="855.0444" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="855.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M855.0444,-347.9735C855.0444,-336.1918 855.0444,-320.5607 855.0444,-307.1581"/>
<polygon fill="#000000" stroke="#000000" points="858.5445,-307.0033 855.0444,-297.0034 851.5445,-307.0034 858.5445,-307.0033"/>
<text text-anchor="middle" x="925.0444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- synonym -->
<g id="node12" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="500.0444" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="500.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge9" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M507.7031,-348.0349C514.3938,-330.693 523.0444,-303.5282 523.0444,-279 523.0444,-279 523.0444,-279 523.0444,-148.5 523.0444,-119.892 523.8946,-109.1134 542.0444,-87 575.355,-46.4149 635.3569,-29.6691 677.1039,-22.7802"/>
<polygon fill="#000000" stroke="#000000" points="677.6732,-26.2339 687.0329,-21.2693 676.6201,-19.3136 677.6732,-26.2339"/>
<text text-anchor="middle" x="565.5444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M525.3506,-350.1056C544.9864,-338.5261 573.2817,-323.445 600.0444,-315 654.8302,-297.7123 671.1599,-305.0309 728.0444,-297 752.8226,-293.5019 780.318,-289.6065 803.3709,-286.3368"/>
<polygon fill="#000000" stroke="#000000" points="803.8809,-289.7995 813.2902,-284.9296 802.8977,-282.8689 803.8809,-289.7995"/>
<text text-anchor="middle" x="642.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M517.2481,-349.0068C529.0529,-338.0966 545.518,-324.2832 562.0444,-315 625.6468,-279.2731 645.7286,-276.3538 717.0444,-261 805.159,-242.0296 832.6833,-268.8034 919.0444,-243 932.5712,-238.9584 933.4603,-231.8447 947.0444,-228 996.6451,-213.9614 1326.6639,-200.1823 1475.4861,-194.5985"/>
<polygon fill="#000000" stroke="#000000" points="1476.0193,-198.0812 1485.8819,-194.2108 1475.7583,-191.086 1476.0193,-198.0812"/>
<text text-anchor="middle" x="759.5444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- methylation_array_file -->
<g id="node13" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1076.0444" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1076.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge36" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1048.1608,-348.5029C1038.88,-342.6489 1028.5004,-336.0691 1019.0444,-330 1008.7738,-323.4081 1007.2177,-319.9087 996.0444,-315 967.4324,-302.4301 933.5506,-293.6024 906.1719,-287.8353"/>
<polygon fill="#000000" stroke="#000000" points="906.5183,-284.3343 896.0217,-285.7735 905.1248,-291.1942 906.5183,-284.3343"/>
<text text-anchor="middle" x="1110.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- exposure -->
<g id="node14" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1482.0444" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1482.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1488.3517,-260.9728C1492.4541,-250.7137 1498.4541,-237.9637 1506.0444,-228 1509.3907,-223.6073 1513.3527,-219.3717 1517.4849,-215.4442"/>
<polygon fill="#000000" stroke="#000000" points="1519.8718,-218.0054 1525.0106,-208.7402 1515.2156,-212.7785 1519.8718,-218.0054"/>
<text text-anchor="middle" x="1549.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- family_relationship -->
<g id="node15" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1653.0444" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1653.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1632.3469,-261.145C1620.8426,-251.287 1606.2284,-238.8728 1593.0444,-228 1588.0803,-223.9062 1582.7704,-219.5972 1577.6016,-215.4396"/>
<polygon fill="#000000" stroke="#000000" points="1579.6587,-212.603 1569.6655,-209.0835 1575.2828,-218.0666 1579.6587,-212.603"/>
<text text-anchor="middle" x="1688.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- consent_group -->
<g id="node16" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1231.0444" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1231.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge19" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1167.733,-94.1573C1063.3709,-76.2843 857.7962,-41.0776 767.4332,-25.602"/>
<polygon fill="#000000" stroke="#000000" points="767.9587,-22.1411 757.5114,-23.9028 766.777,-29.0407 767.9587,-22.1411"/>
<text text-anchor="middle" x="1070.5444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- treatment_response -->
<g id="node17" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="2018.0444" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="2018.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1960.8633,-263.9099C1917.7189,-252.8968 1856.9502,-238.1759 1803.0444,-228 1740.1297,-216.1234 1667.8093,-206.2692 1616.2929,-199.891"/>
<polygon fill="#000000" stroke="#000000" points="1616.6278,-196.406 1606.276,-198.6622 1615.7754,-203.3539 1616.6278,-196.406"/>
<text text-anchor="middle" x="1957.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- sequencing_file -->
<g id="node18" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1293.0444" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1293.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1260.1992,-349.3813C1248.9318,-343.4779 1236.3233,-336.6449 1225.0444,-330 1214.5295,-323.8052 1213.6094,-318.8972 1202.0444,-315 1096.8986,-279.5675 1063.1076,-311.0432 953.0444,-297 937.1385,-294.9705 919.9025,-292.0508 904.3852,-289.1516"/>
<polygon fill="#000000" stroke="#000000" points="904.9464,-285.6956 894.4675,-287.2589 903.6342,-292.5715 904.9464,-285.6956"/>
<text text-anchor="middle" x="1291.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge30" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1502.626,-179.535C1447.1639,-164.3136 1353.1567,-138.5135 1291.5878,-121.616"/>
<polygon fill="#000000" stroke="#000000" points="1292.1888,-118.1516 1281.619,-118.8801 1290.3361,-124.902 1292.1888,-118.1516"/>
<text text-anchor="middle" x="1458.5444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- medical_history -->
<g id="node20" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2226.0444" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2226.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2181.0011,-263.6477C2144.5197,-251.8802 2091.5628,-236.2955 2044.0444,-228 1964.684,-214.1457 1737.4503,-201.3597 1620.1077,-195.4467"/>
<polygon fill="#000000" stroke="#000000" points="1619.9531,-191.9347 1609.7905,-194.9303 1619.603,-198.9259 1619.9531,-191.9347"/>
<text text-anchor="middle" x="2177.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge26" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M680.0095,-174.0771C686.6404,-150.1318 698.7478,-106.379 709.0444,-69 711.1232,-61.4537 713.37,-53.2777 715.4423,-45.7283"/>
<polygon fill="#000000" stroke="#000000" points="718.8572,-46.5097 718.1281,-35.94 712.1067,-44.6574 718.8572,-46.5097"/>
<text text-anchor="middle" x="743.5444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M681.8162,-210.1286C686.8643,-221.2211 694.8323,-234.8105 706.0444,-243 721.5136,-254.2989 766.7057,-264.2747 803.2985,-270.8423"/>
<polygon fill="#000000" stroke="#000000" points="802.906,-274.3267 813.3596,-272.6025 804.1124,-267.4314 802.906,-274.3267"/>
<text text-anchor="middle" x="746.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- clinical_measure_file -->
<g id="node22" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="2685.0444" cy="-279" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="2685.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge28" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2684.9292,-260.9919C2683.8394,-249.8023 2680.4611,-236.0604 2671.0444,-228 2410.58,-5.049 1479.1933,-88.1515 1138.0444,-54 1004.3705,-40.6183 846.1767,-27.7014 769.4336,-21.6208"/>
<polygon fill="#000000" stroke="#000000" points="769.401,-18.1074 759.1564,-20.8089 768.8496,-25.0857 769.401,-18.1074"/>
<text text-anchor="middle" x="2623.0444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2605.2139,-266.6747C2563.9712,-259.6859 2518.3286,-250.8041 2499.0444,-243 2487.7316,-238.4218 2487.6729,-231.7036 2476.0444,-228 2395.5482,-202.3623 1824.8484,-194.5741 1620.5567,-192.5928"/>
<polygon fill="#000000" stroke="#000000" points="1620.5606,-189.0927 1610.5277,-192.4973 1620.4939,-196.0924 1620.5606,-189.0927"/>
<text text-anchor="middle" x="2585.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- diagnosis -->
<g id="node23" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1624.0444" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1624.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1584.0853,-353.6109C1565.9676,-347.4176 1544.5138,-339.2653 1526.0444,-330 1515.136,-324.5277 1514.684,-318.6684 1503.0444,-315 1444.7282,-296.6209 1013.8374,-303.541 953.0444,-297 937.1015,-295.2846 919.8554,-292.4515 904.3401,-289.535"/>
<polygon fill="#000000" stroke="#000000" points="904.9081,-286.0801 894.4254,-287.6173 903.5788,-292.9527 904.9081,-286.0801"/>
<text text-anchor="middle" x="1570.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1625.9791,-347.764C1626.0695,-336.6286 1624.0245,-323.0318 1615.0444,-315 1567.909,-272.8423 1374.3229,-343.1084 1331.0444,-297 1281.1215,-243.8128 1399.767,-214.3775 1480.5858,-201.0062"/>
<polygon fill="#000000" stroke="#000000" points="1481.4127,-204.4183 1490.7319,-199.378 1480.3036,-197.5067 1481.4127,-204.4183"/>
<text text-anchor="middle" x="1375.5444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- survival -->
<g id="node24" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="2377.0444" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="2377.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2341.2499,-266.6366C2322.8014,-260.0331 2300.0379,-251.5243 2280.0444,-243 2265.9648,-236.9971 2263.8708,-231.8014 2249.0444,-228 2189.4264,-212.7144 1787.3586,-199.135 1620.4505,-194.088"/>
<polygon fill="#000000" stroke="#000000" points="1620.382,-190.5844 1610.2813,-193.7822 1620.1716,-197.5813 1620.382,-190.5844"/>
<text text-anchor="middle" x="2319.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge32" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M833.222,-174.4048C824.4351,-152.813 807.9058,-115.5574 788.0444,-87 776.4189,-70.2844 760.8489,-53.6099 747.8622,-40.8409"/>
<polygon fill="#000000" stroke="#000000" points="750.1917,-38.225 740.5637,-33.8032 745.3327,-43.264 750.1917,-38.225"/>
<text text-anchor="middle" x="833.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge33" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M818.0368,-203.195C802.2632,-212.8261 785.2349,-227.5717 794.0444,-243 798.427,-250.6754 805.1571,-256.8786 812.5711,-261.8314"/>
<polygon fill="#000000" stroke="#000000" points="811.0963,-265.0246 821.489,-267.0843 814.649,-258.9932 811.0963,-265.0246"/>
<text text-anchor="middle" x="818.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- treatment -->
<g id="node26" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="2501.0444" cy="-279" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="2501.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2457.1083,-267.1126C2429.0706,-259.2574 2395.5454,-249.2874 2382.0444,-243 2370.9812,-237.8479 2370.6625,-231.7361 2359.0444,-228 2289.9118,-205.7687 1806.4272,-195.9996 1620.5833,-193.0361"/>
<polygon fill="#000000" stroke="#000000" points="1620.4207,-189.5332 1610.3668,-192.8752 1620.3105,-196.5323 1620.4207,-189.5332"/>
<text text-anchor="middle" x="2429.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- cytogenomic_file -->
<g id="node27" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="660.0444" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="660.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge35" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M672.7685,-347.8838C681.478,-336.7962 693.9697,-323.2076 708.0444,-315 736.5712,-298.3648 772.5187,-289.3866 801.7249,-284.5566"/>
<polygon fill="#000000" stroke="#000000" points="802.399,-287.9941 811.7511,-283.0154 801.3354,-281.0754 802.399,-287.9941"/>
<text text-anchor="middle" x="779.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- study_funding -->
<g id="node28" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2939.0444" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2939.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge6" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2915.7492,-87.6574C2898.1545,-75.6657 2872.8712,-60.7077 2848.0444,-54 2744.4155,-26.0014 1072.8193,-19.1568 769.9175,-18.1442"/>
<polygon fill="#000000" stroke="#000000" points="769.7361,-14.6436 759.7245,-18.1106 769.7129,-21.6436 769.7361,-14.6436"/>
<text text-anchor="middle" x="2944.0444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
</g>
</svg>
</div>
