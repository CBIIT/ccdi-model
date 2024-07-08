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
<svg width="2949pt" height="305pt"
 viewBox="0.00 0.00 2949.49 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 2945.4879,-301 2945.4879,4 -4,4"/>
<!-- exposure -->
<g id="node1" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="938.3956" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="938.3956" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- participant -->
<g id="node10" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1842.3956" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1842.3956" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M933.1491,-174.0146C931.1319,-162.9792 931.013,-149.3996 939.3956,-141 955.7249,-124.6376 1748.4893,-126.1104 1771.3956,-123 1776.9084,-122.2514 1782.6106,-121.233 1788.2765,-120.0588"/>
<polygon fill="#000000" stroke="#000000" points="1789.3898,-123.3965 1798.387,-117.8017 1787.8646,-116.5647 1789.3898,-123.3965"/>
<text text-anchor="middle" x="982.8956" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- study -->
<g id="node2" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2139.3956" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2139.3956" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- publication -->
<g id="node3" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="1487.3956" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="1487.3956" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge15" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1512.1011,-88.2714C1531.0088,-76.4221 1558.2063,-61.3727 1584.3956,-54 1679.3703,-27.2631 1976.4142,-20.2721 2092.3669,-18.5397"/>
<polygon fill="#000000" stroke="#000000" points="2092.7364,-22.0349 2102.6853,-18.3924 2092.6364,-15.0356 2092.7364,-22.0349"/>
<text text-anchor="middle" x="1635.3956" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- family_relationship -->
<g id="node4" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1368.3956" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1368.3956" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1387.7766,-174.1706C1401.8187,-162.4415 1421.8713,-148.0082 1442.3956,-141 1511.6879,-117.3396 1699.0136,-134.0486 1771.3956,-123 1776.8168,-122.1725 1782.4262,-121.113 1788.0068,-119.9231"/>
<polygon fill="#000000" stroke="#000000" points="1788.9955,-123.2879 1797.9736,-117.6626 1787.4471,-116.4613 1788.9955,-123.2879"/>
<text text-anchor="middle" x="1521.8956" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- methylation_array_file -->
<g id="node5" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="429.3956" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="429.3956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- sample -->
<g id="node21" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="675.3956" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="675.3956" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M430.7948,-260.7972C432.64,-249.6751 436.8503,-236.0806 446.3956,-228 472.0401,-206.2907 561.6535,-197.5857 620.8793,-194.1567"/>
<polygon fill="#000000" stroke="#000000" points="621.4035,-197.6334 631.1982,-193.5944 621.0226,-190.6438 621.4035,-197.6334"/>
<text text-anchor="middle" x="537.8956" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- treatment_response -->
<g id="node6" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1591.3956" cy="-192" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1591.3956" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1596.9313,-173.9389C1601.3927,-162.5777 1608.856,-148.6631 1620.3956,-141 1648.5468,-122.3055 1738.1696,-129.1652 1771.3956,-123 1776.5003,-122.0528 1781.7827,-120.9499 1787.0562,-119.765"/>
<polygon fill="#000000" stroke="#000000" points="1788.1987,-123.0923 1797.1376,-117.4049 1786.603,-116.2766 1788.1987,-123.0923"/>
<text text-anchor="middle" x="1703.3956" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- study_arm -->
<g id="node7" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1628.3956" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1628.3956" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge11" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1653.9892,-88.4557C1673.5448,-76.7005 1701.6084,-61.6881 1728.3956,-54 1795.683,-34.6882 1999.8285,-23.8793 2092.6099,-19.8473"/>
<polygon fill="#000000" stroke="#000000" points="2092.9851,-23.3346 2102.8267,-19.4113 2092.6866,-16.341 2092.9851,-23.3346"/>
<text text-anchor="middle" x="1776.8956" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- molecular_test -->
<g id="node8" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1794.3956" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1794.3956" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1791.0103,-173.605C1790.0373,-163.4669 1790.3582,-150.9566 1795.3956,-141 1797.8897,-136.0704 1801.4083,-131.6239 1805.4114,-127.6748"/>
<polygon fill="#000000" stroke="#000000" points="1807.7386,-130.2896 1813.0235,-121.107 1803.1657,-124.9897 1807.7386,-130.2896"/>
<text text-anchor="middle" x="1859.3956" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- pathology_file -->
<g id="node9" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="639.3956" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="639.3956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge28" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M634.3929,-260.8222C632.5701,-250.7519 631.9134,-238.2373 636.3956,-228 638.5126,-223.165 641.6347,-218.6913 645.2063,-214.6593"/>
<polygon fill="#000000" stroke="#000000" points="647.8282,-216.989 652.4823,-207.4711 642.9085,-212.0093 647.8282,-216.989"/>
<text text-anchor="middle" x="697.3956" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge3" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1886.219,-92.1629C1943.1829,-75.4764 2041.9579,-46.5424 2097.8042,-30.1833"/>
<polygon fill="#000000" stroke="#000000" points="2099.0998,-33.451 2107.7126,-27.2809 2097.1319,-26.7333 2099.0998,-33.451"/>
<text text-anchor="middle" x="2058.8956" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- cell_line -->
<g id="node11" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="49.3956" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="49.3956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge20" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M44.4822,-260.9115C42.7112,-250.1155 42.7378,-236.8322 50.3956,-228 207.6327,-46.6496 345.2772,-171.1843 583.3956,-141 1008.4097,-87.1245 1116.1962,-86.2521 1543.3956,-54 1748.0545,-38.5489 1992.6485,-25.464 2092.9855,-20.3275"/>
<polygon fill="#000000" stroke="#000000" points="2093.2792,-23.8172 2103.0879,-19.8123 2092.9226,-16.8262 2093.2792,-23.8172"/>
<text text-anchor="middle" x="623.8956" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M82.429,-265.5453C98.9476,-258.8022 119.2392,-250.4963 137.3956,-243 153.4171,-236.3851 156.5314,-232.0054 173.3956,-228 257.1733,-208.1018 509.5146,-197.5038 621.2017,-193.6803"/>
<polygon fill="#000000" stroke="#000000" points="621.3648,-197.1769 631.2412,-193.3419 621.129,-190.1809 621.3648,-197.1769"/>
<text text-anchor="middle" x="213.8956" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- study_funding -->
<g id="node12" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2455.3956" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2455.3956" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2405.3245,-91.2146C2343.4313,-74.1744 2239.2122,-45.4812 2181.3317,-29.5457"/>
<polygon fill="#000000" stroke="#000000" points="2181.9967,-26.0986 2171.4264,-26.8186 2180.1386,-32.8475 2181.9967,-26.0986"/>
<text text-anchor="middle" x="2377.3956" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- medical_history -->
<g id="node13" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1977.3956" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1977.3956" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1961.1685,-173.8507C1951.0555,-163.2986 1937.3483,-150.2923 1923.3956,-141 1913.289,-134.2692 1901.7174,-128.2675 1890.544,-123.1848"/>
<polygon fill="#000000" stroke="#000000" points="1891.8572,-119.9391 1881.2928,-119.1358 1889.0504,-126.3518 1891.8572,-119.9391"/>
<text text-anchor="middle" x="2008.3956" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- study_admin -->
<g id="node14" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="2621.3956" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2621.3956" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge27" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2578.7117,-90.6683C2542.9487,-79.1709 2490.3533,-63.4434 2443.3956,-54 2353.2013,-35.8616 2245.9835,-25.7927 2186.0054,-21.1739"/>
<polygon fill="#000000" stroke="#000000" points="2185.9612,-17.6607 2175.7267,-20.4003 2185.4358,-24.641 2185.9612,-17.6607"/>
<text text-anchor="middle" x="2558.8956" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- sequencing_file -->
<g id="node15" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="816.3956" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="816.3956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M799.2746,-261.3677C788.2952,-250.7434 773.3418,-237.4803 758.3956,-228 746.0149,-220.1469 731.6279,-213.2345 718.3437,-207.6208"/>
<polygon fill="#000000" stroke="#000000" points="719.4911,-204.3088 708.9101,-203.7678 716.8443,-210.7891 719.4911,-204.3088"/>
<text text-anchor="middle" x="843.8956" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- diagnosis -->
<g id="node16" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1006.3956" cy="-279" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1006.3956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1016.601,-260.853C1033.1392,-231.5719 1064.3624,-176.8671 1068.3956,-174 1128.9941,-130.9219 1158.5452,-149.6034 1232.3956,-141 1470.4746,-113.2643 1534.0797,-156.6455 1771.3956,-123 1776.8252,-122.2302 1782.4404,-121.209 1788.0244,-120.0429"/>
<polygon fill="#000000" stroke="#000000" points="1789.0017,-123.4108 1797.9954,-117.8104 1787.4723,-116.5799 1789.0017,-123.4108"/>
<text text-anchor="middle" x="1112.8956" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M975.8209,-263.8547C963.7119,-257.6482 949.7574,-250.2329 937.3956,-243 926.8622,-236.8368 925.8013,-232.3414 914.3956,-228 881.4019,-215.4414 788.5264,-203.839 728.7425,-197.3615"/>
<polygon fill="#000000" stroke="#000000" points="729.0325,-193.8727 718.717,-196.2896 728.2882,-200.833 729.0325,-193.8727"/>
<text text-anchor="middle" x="981.8956" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- pdx -->
<g id="node17" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1734.3956" cy="-105" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1734.3956" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge30" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1755.9454,-93.4674C1760.9254,-91.0991 1766.2691,-88.7868 1771.3956,-87 1883.2006,-48.0322 2022.2069,-29.5851 2093.1032,-22.1848"/>
<polygon fill="#000000" stroke="#000000" points="2093.8754,-25.6245 2103.4702,-21.1312 2093.1675,-18.6604 2093.8754,-25.6245"/>
<text text-anchor="middle" x="1913.3956" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge29" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1713.466,-117.1221C1708.3656,-119.5234 1702.8141,-121.7016 1697.3956,-123 1669.757,-129.6228 694.3148,-120.7273 674.3956,-141 668.4827,-147.0178 667.1091,-155.6194 667.7151,-164.0483"/>
<polygon fill="#000000" stroke="#000000" points="664.276,-164.7117 669.2641,-174.0589 671.1937,-163.6413 664.276,-164.7117"/>
<text text-anchor="middle" x="698.3956" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- clinical_measure_file -->
<g id="node18" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="2602.3956" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="2602.3956" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge26" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2626.5113,-174.4167C2637.8865,-164.0653 2647.0632,-151.0711 2637.3956,-141 2603.5115,-105.7014 2239.0195,-148.7211 2197.3956,-123 2169.8357,-105.9696 2154.353,-70.8633 2146.4466,-45.9388"/>
<polygon fill="#000000" stroke="#000000" points="2149.7865,-44.8902 2143.5983,-36.2904 2143.0729,-46.8722 2149.7865,-44.8902"/>
<text text-anchor="middle" x="2283.3956" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2532.2797,-178.1671C2510.3555,-172.6368 2486.4149,-165.322 2465.3956,-156 2454.2395,-151.0523 2453.9843,-144.8264 2442.3956,-141 2436.1877,-138.9502 2071.756,-118.034 1913.957,-109.057"/>
<polygon fill="#000000" stroke="#000000" points="1914.0505,-105.5567 1903.8679,-108.4832 1913.653,-112.5454 1914.0505,-105.5567"/>
<text text-anchor="middle" x="2551.3956" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- synonym -->
<g id="node19" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1173.3956" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1173.3956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge24" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1225.5499,-278.673C1489.4993,-276.7685 2667.6118,-265.1905 2720.3956,-210 2742.4336,-186.9571 2724.792,-115.6757 2700.3956,-87 2675.2064,-57.3924 2657.2373,-62.895 2619.3956,-54 2537.8955,-34.8427 2289.9243,-23.6201 2185.9998,-19.6472"/>
<polygon fill="#000000" stroke="#000000" points="2185.9394,-16.1426 2175.8147,-19.2635 2185.6758,-23.1376 2185.9394,-16.1426"/>
<text text-anchor="middle" x="2770.8956" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1167.1968,-260.9201C1160.5283,-237.7792 1153.4702,-197.839 1174.3956,-174 1208.8387,-134.7612 1689.7947,-135.2482 1771.3956,-123 1776.8188,-122.186 1782.4296,-121.1354 1788.011,-119.9511"/>
<polygon fill="#000000" stroke="#000000" points="1788.9971,-123.3166 1797.9789,-117.6971 1787.4531,-116.489 1788.9971,-123.3166"/>
<text text-anchor="middle" x="1216.8956" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1137.3156,-265.8877C1096.7667,-251.1881 1035.8434,-229.2287 1030.3956,-228 1001.7746,-221.545 821.0987,-204.9284 729.0939,-196.7252"/>
<polygon fill="#000000" stroke="#000000" points="729.1361,-193.2152 718.8653,-195.8153 728.5158,-200.1877 729.1361,-193.2152"/>
<text text-anchor="middle" x="1115.8956" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- treatment -->
<g id="node20" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="2138.3956" cy="-192" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="2138.3956" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2123.4795,-174.4598C2112.7143,-163.0193 2097.1708,-148.8094 2080.3956,-141 2051.3419,-127.4746 1971.6707,-117.2337 1912.4637,-111.1967"/>
<polygon fill="#000000" stroke="#000000" points="1912.706,-107.7035 1902.4074,-110.1913 1912.0096,-114.6688 1912.706,-107.7035"/>
<text text-anchor="middle" x="2150.3956" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M714.9328,-183.8827C744.3474,-177.4355 785.2997,-167.5943 820.3956,-156 836.8541,-150.5628 839.4331,-144.5663 856.3956,-141 1055.417,-99.156 1569.8455,-150.1664 1771.3956,-123 1776.9092,-122.2568 1782.6118,-121.242 1788.278,-120.07"/>
<polygon fill="#000000" stroke="#000000" points="1789.3903,-123.408 1798.3888,-117.8155 1787.8667,-116.5758 1789.3903,-123.408"/>
<text text-anchor="middle" x="892.8956" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge16" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M630.8637,-193.2294C493.8574,-197.1937 86.5137,-210.412 64.3956,-228 57.3864,-233.5737 53.5356,-242.249 51.4559,-250.874"/>
<polygon fill="#000000" stroke="#000000" points="47.9969,-250.3374 49.7451,-260.787 54.8949,-251.5279 47.9969,-250.3374"/>
<text text-anchor="middle" x="100.8956" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge17" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M696.949,-176.2669C717.0878,-161.6395 744.4852,-141.9568 747.3956,-141 847.6894,-108.0283 1594.7441,-147.6708 1697.3956,-123 1699.5965,-122.471 1701.8195,-121.7973 1704.0253,-121.0226"/>
<polygon fill="#000000" stroke="#000000" points="1705.5627,-124.1743 1713.4647,-117.1168 1702.8862,-117.7061 1705.5627,-124.1743"/>
<text text-anchor="middle" x="783.8956" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- survival -->
<g id="node22" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="2262.3956" cy="-192" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="2262.3956" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2243.9565,-175.0759C2229.1071,-161.8365 2209.1552,-145.0175 2199.3956,-141 2149.5455,-120.4791 2003.917,-111.2506 1914.8067,-107.4252"/>
<polygon fill="#000000" stroke="#000000" points="1914.9015,-103.9262 1904.7644,-107.0067 1914.61,-110.9202 1914.9015,-103.9262"/>
<text text-anchor="middle" x="2258.8956" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- study_personnel -->
<g id="node23" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2854.3956" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2854.3956" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge9" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2827.7533,-87.732C2808.063,-75.9427 2780.1398,-61.2029 2753.3956,-54 2646.572,-25.2297 2310.4125,-19.4481 2186.1599,-18.2894"/>
<polygon fill="#000000" stroke="#000000" points="2185.8767,-14.7869 2175.8465,-18.1994 2185.8156,-21.7866 2185.8767,-14.7869"/>
<text text-anchor="middle" x="2859.8956" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- radiology_file -->
<g id="node24" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="2402.3956" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="2402.3956" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2365.3425,-176.2286C2352.2041,-170.2898 2337.4472,-163.2177 2324.3956,-156 2313.7159,-150.0939 2312.9487,-144.9325 2301.3956,-141 2265.7816,-128.8774 2034.3142,-115.1154 1914.316,-108.6813"/>
<polygon fill="#000000" stroke="#000000" points="1914.2875,-105.1749 1904.1154,-108.1376 1913.9149,-112.165 1914.2875,-105.1749"/>
<text text-anchor="middle" x="2383.3956" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- cytogenomic_file -->
<g id="node25" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="206.3956" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="206.3956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M228.585,-261.4408C244.542,-249.8356 267.0952,-235.4394 289.3956,-228 349.4889,-207.953 529.9206,-197.9227 621.22,-194.0176"/>
<polygon fill="#000000" stroke="#000000" points="621.5218,-197.5081 631.3668,-193.5932 621.2292,-190.5143 621.5218,-197.5081"/>
<text text-anchor="middle" x="360.8956" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
</g>
</svg>
</div>
