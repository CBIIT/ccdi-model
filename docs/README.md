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
<svg width="2830pt" height="392pt"
 viewBox="0.00 0.00 2830.23 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 2826.2262,-388 2826.2262,4 -4,4"/>
<!-- family_relationship -->
<g id="node1" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="2030.2262" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="2030.2262" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- participant -->
<g id="node21" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1275.2262" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1275.2262" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1982.9173,-176.0533C1945.8935,-164.2853 1892.8702,-148.984 1845.2262,-141 1751.56,-125.3037 1478.9081,-112.9404 1347.5842,-107.711"/>
<polygon fill="#000000" stroke="#000000" points="1347.3627,-104.1996 1337.2322,-107.3019 1347.0862,-111.1941 1347.3627,-104.1996"/>
<text text-anchor="middle" x="1990.7262" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- therapeutic_procedure -->
<g id="node2" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="766.2262" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="766.2262" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M781.29,-174.0794C792.1918,-162.4691 807.99,-148.2126 825.2262,-141 859.1229,-126.8157 1084.844,-114.094 1203.1552,-108.3039"/>
<polygon fill="#000000" stroke="#000000" points="1203.4004,-111.7962 1213.2189,-107.8154 1203.061,-104.8044 1203.4004,-111.7962"/>
<text text-anchor="middle" x="918.2262" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- cell_line -->
<g id="node3" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="1778.2262" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="1778.2262" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1787.969,-261.1159C1803.3406,-230.2936 1827.9071,-167.8904 1791.2262,-141 1756.3304,-115.4183 1481.5187,-107.9508 1347.8096,-105.8222"/>
<polygon fill="#000000" stroke="#000000" points="1347.706,-102.3203 1337.6535,-105.6665 1347.5986,-109.3195 1347.706,-102.3203"/>
<text text-anchor="middle" x="1850.7262" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- study -->
<g id="node23" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="575.2262" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="575.2262" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge17" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1826.1067,-274.4748C1864.7371,-270.8269 1920.4792,-265.5702 1969.2262,-261 2055.0001,-252.9585 2078.4583,-263.119 2162.2262,-243 2200.8261,-233.7292 2222.9364,-242.8491 2245.2262,-210 2254.21,-196.7603 2252.8723,-188.0548 2245.2262,-174 2120.0072,56.1705 1333.5197,-73.5936 1072.2262,-54 906.4287,-41.5674 709.4615,-27.5123 621.5682,-21.2779"/>
<polygon fill="#000000" stroke="#000000" points="621.6221,-17.773 611.3996,-20.557 621.127,-24.7555 621.6221,-17.773"/>
<text text-anchor="middle" x="2271.7262" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- publication -->
<g id="node4" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="79.2262" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="79.2262" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge15" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M102.3878,-88.1793C119.8501,-76.447 144.878,-61.585 169.2262,-54 235.1738,-33.4558 436.6519,-23.3095 528.5962,-19.6499"/>
<polygon fill="#000000" stroke="#000000" points="528.8684,-23.142 538.7246,-19.2554 528.596,-16.1473 528.8684,-23.142"/>
<text text-anchor="middle" x="220.2262" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- radiology_file -->
<g id="node5" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="975.2262" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="975.2262" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M992.2956,-174.2388C1004.3163,-162.854 1021.3914,-148.7962 1039.2262,-141 1068.3047,-128.2887 1147.046,-117.9028 1205.6271,-111.6088"/>
<polygon fill="#000000" stroke="#000000" points="1206.0011,-115.0889 1215.5782,-110.5579 1205.2658,-108.1276 1206.0011,-115.0889"/>
<text text-anchor="middle" x="1098.2262" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- study_personnel -->
<g id="node6" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="247.2262" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="247.2262" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge25" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M258.9356,-86.8415C267.3219,-75.4392 279.6773,-61.5153 294.2262,-54 334.0758,-33.4154 459.7751,-23.8887 528.7698,-20.112"/>
<polygon fill="#000000" stroke="#000000" points="529.1263,-23.5981 538.9276,-19.5751 528.7568,-16.6079 529.1263,-23.5981"/>
<text text-anchor="middle" x="363.7262" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- follow_up -->
<g id="node7" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="1122.2262" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="1122.2262" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1139.0464,-174.6394C1150.2226,-163.8532 1165.6581,-150.3166 1181.2262,-141 1193.8972,-133.4171 1208.4448,-126.9179 1222.2496,-121.6131"/>
<polygon fill="#000000" stroke="#000000" points="1223.4919,-124.8854 1231.6559,-118.1327 1221.0628,-118.3204 1223.4919,-124.8854"/>
<text text-anchor="middle" x="1226.2262" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- study_funding -->
<g id="node8" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="429.2262" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="429.2262" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge7" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M431.0461,-86.6725C433.0606,-75.7866 437.3015,-62.4926 446.2262,-54 458.4614,-42.3571 498.3537,-32.335 530.5725,-25.8437"/>
<polygon fill="#000000" stroke="#000000" points="531.5748,-29.2142 540.7187,-23.8627 530.2333,-22.3439 531.5748,-29.2142"/>
<text text-anchor="middle" x="508.2262" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- molecular_test -->
<g id="node9" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1275.2262" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1275.2262" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1275.2262,-173.9735C1275.2262,-162.1918 1275.2262,-146.5607 1275.2262,-133.1581"/>
<polygon fill="#000000" stroke="#000000" points="1278.7263,-133.0033 1275.2262,-123.0034 1271.7263,-133.0034 1278.7263,-133.0033"/>
<text text-anchor="middle" x="1339.2262" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- exposure -->
<g id="node10" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1426.2262" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1426.2262" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1422.4898,-173.5879C1419.3632,-162.67 1413.8136,-149.3724 1404.2262,-141 1393.8144,-131.9078 1365.2473,-123.4957 1337.6353,-117.0933"/>
<polygon fill="#000000" stroke="#000000" points="1338.0647,-113.6027 1327.541,-114.8279 1336.5318,-120.4328 1338.0647,-113.6027"/>
<text text-anchor="middle" x="1457.7262" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- diagnosis -->
<g id="node11" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1552.2262" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1552.2262" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1540.4468,-173.9745C1532.031,-162.6284 1519.669,-148.7171 1505.2262,-141 1478.2396,-126.5805 1402.7202,-116.6247 1345.5166,-110.8965"/>
<polygon fill="#000000" stroke="#000000" points="1345.7184,-107.3996 1335.4254,-109.9104 1345.0376,-114.3664 1345.7184,-107.3996"/>
<text text-anchor="middle" x="1568.7262" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- medical_history -->
<g id="node12" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1710.2262" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1710.2262" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1685.0129,-174.5685C1666.9726,-163.022 1641.6541,-148.6433 1617.2262,-141 1568.4273,-125.7313 1431.823,-114.7783 1346.7591,-109.2014"/>
<polygon fill="#000000" stroke="#000000" points="1346.8553,-105.7004 1336.6503,-108.548 1346.4037,-112.6858 1346.8553,-105.7004"/>
<text text-anchor="middle" x="1719.2262" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- methylation_array_file -->
<g id="node13" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2477.2262" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2477.2262" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge21" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2382.8666,-355.5479C2330.4018,-348.9023 2270.8549,-339.7375 2246.2262,-330 2235.2209,-325.6488 2235.4047,-318.8845 2224.2262,-315 2170.5661,-296.3532 2025.8419,-301.6653 1969.2262,-297 1924.6241,-293.3247 1874.2241,-288.5487 1836.4,-284.8399"/>
<polygon fill="#000000" stroke="#000000" points="1836.3752,-281.3206 1826.0804,-283.824 1835.6893,-288.287 1836.3752,-281.3206"/>
<text text-anchor="middle" x="2337.7262" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- sample -->
<g id="node14" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2192.2262" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2192.2262" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2570.0682,-355.1398C2600.3894,-349.5756 2628.7394,-341.4814 2638.2262,-330 2640.1769,-327.6391 2639.3709,-261.1688 2639.2262,-261 2613.8543,-231.4112 2358.9493,-206.2136 2245.8214,-196.3946"/>
<polygon fill="#000000" stroke="#000000" points="2245.9153,-192.8898 2235.6522,-195.5203 2245.3156,-199.8641 2245.9153,-192.8898"/>
<text text-anchor="middle" x="2730.7262" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- pdx -->
<g id="node18" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2006.2262" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2006.2262" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge22" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2466.7946,-347.9025C2459.0963,-336.3717 2447.4986,-322.2774 2433.2262,-315 2416.0231,-306.2283 2145.7856,-288.0007 2044.3241,-281.4286"/>
<polygon fill="#000000" stroke="#000000" points="2044.4097,-277.9269 2034.205,-280.7756 2043.9588,-284.9124 2044.4097,-277.9269"/>
<text text-anchor="middle" x="2542.7262" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2165.9923,-177.3595C2142.6841,-165.1689 2107.2826,-148.6177 2074.2262,-141 2004.6312,-124.9622 1530.8546,-111.4511 1347.4895,-106.7637"/>
<polygon fill="#000000" stroke="#000000" points="1347.4915,-103.2627 1337.4058,-106.5074 1347.3136,-110.2605 1347.4915,-103.2627"/>
<text text-anchor="middle" x="2153.7262" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node15" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2006.2262" cy="-366" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="2006.2262" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge32" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1872.3818,-361.6049C1716.9675,-355.8342 1479.967,-344.6874 1466.2262,-330 1461.6716,-325.1317 1461.7905,-319.9769 1466.2262,-315 1482.7201,-296.4935 1633.2279,-286.1133 1719.0244,-281.6529"/>
<polygon fill="#000000" stroke="#000000" points="1719.3438,-285.1413 1729.1533,-281.1382 1718.9885,-278.1503 1719.3438,-285.1413"/>
<text text-anchor="middle" x="1574.7262" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge33" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2134.185,-359.3137C2255.3154,-352.347 2420.1756,-340.9401 2430.2262,-330 2461.2528,-296.2273 2311.8045,-235.4687 2235.1862,-207.2152"/>
<polygon fill="#000000" stroke="#000000" points="2236.3686,-203.9209 2225.7748,-203.773 2233.9642,-210.495 2236.3686,-203.9209"/>
<text text-anchor="middle" x="2526.7262" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge31" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2006.2262,-347.9735C2006.2262,-336.1918 2006.2262,-320.5607 2006.2262,-307.1581"/>
<polygon fill="#000000" stroke="#000000" points="2009.7263,-307.0033 2006.2262,-297.0034 2002.7263,-307.0034 2009.7263,-307.0033"/>
<text text-anchor="middle" x="2114.7262" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- study_admin -->
<g id="node16" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="595.2262" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="595.2262" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge24" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M583.6252,-86.9883C580.6361,-81.4363 577.8158,-75.1585 576.2262,-69 574.3607,-61.773 573.6151,-53.7769 573.4543,-46.3013"/>
<polygon fill="#000000" stroke="#000000" points="576.9549,-46.2505 573.5605,-36.2142 569.9553,-46.1767 576.9549,-46.2505"/>
<text text-anchor="middle" x="632.7262" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- clinical_measure_file -->
<g id="node17" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="400.2262" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="400.2262" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M411.3686,-173.9354C419.6704,-162.2608 432.1503,-147.9866 447.2262,-141 490.7139,-120.8465 830.3409,-125.0855 878.2262,-123 991.6899,-118.0585 1123.38,-112.0296 1202.945,-108.3548"/>
<polygon fill="#000000" stroke="#000000" points="1203.5126,-111.8324 1213.3403,-107.8744 1203.1894,-104.8399 1203.5126,-111.8324"/>
<text text-anchor="middle" x="576.7262" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge10" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M404.9414,-173.7969C408.9098,-162.3758 415.8168,-148.4477 427.2262,-141 473.311,-110.9171 631.6517,-157.8741 674.2262,-123 698.5039,-103.1133 707.7775,-79.3127 689.2262,-54 680.6657,-42.3195 647.564,-32.6762 619.2199,-26.3198"/>
<polygon fill="#000000" stroke="#000000" points="619.9538,-22.8977 609.4407,-24.2107 618.4779,-29.7404 619.9538,-22.8977"/>
<text text-anchor="middle" x="785.2262" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge35" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2029.0334,-268.3321C2060.1543,-253.7755 2116.3466,-227.492 2153.9731,-209.8926"/>
<polygon fill="#000000" stroke="#000000" points="2155.5374,-213.0249 2163.1126,-205.6177 2152.5715,-206.6842 2155.5374,-213.0249"/>
<text text-anchor="middle" x="2134.2262" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- synonym -->
<g id="node19" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="545.2262" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="545.2262" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge30" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M593.652,-272.1357C677.6313,-260.5725 855.8187,-237.5395 1007.2262,-228 1132.7709,-220.09 2015.2811,-231.4866 2139.2262,-210 2142.9394,-209.3563 2146.7439,-208.4945 2150.5268,-207.4956"/>
<polygon fill="#000000" stroke="#000000" points="2151.8073,-210.7672 2160.4123,-204.5863 2149.831,-204.052 2151.8073,-210.7672"/>
<text text-anchor="middle" x="1049.7262" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M540.6702,-261.0253C535.9272,-237.6235 531.9553,-197.0036 554.2262,-174 577.8852,-149.5625 672.544,-160.7379 706.2262,-156 747.2511,-150.2293 757.0878,-145.8968 798.2262,-141 941.3012,-123.9694 1109.5345,-113.4878 1203.1107,-108.5007"/>
<polygon fill="#000000" stroke="#000000" points="1203.5126,-111.9844 1213.3145,-107.9629 1203.1441,-104.9941 1203.5126,-111.9844"/>
<text text-anchor="middle" x="596.7262" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge28" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M496.6904,-272.4675C375.6884,-255.0759 66.1298,-203.416 7.2262,-123 -2.2285,-110.0923 -2.5374,-99.6757 7.2262,-87 38.9488,-45.8157 398.5755,-25.8485 528.6415,-19.9372"/>
<polygon fill="#000000" stroke="#000000" points="528.8588,-23.431 538.6924,-19.4877 528.546,-16.438 528.8588,-23.431"/>
<text text-anchor="middle" x="89.7262" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- pathology_file -->
<g id="node20" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1320.2262" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1320.2262" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge5" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1321.0106,-347.8301C1322.524,-336.574 1326.4382,-322.819 1336.2262,-315 1365.4288,-291.6719 1604.6515,-283.0205 1718.4717,-280.2028"/>
<polygon fill="#000000" stroke="#000000" points="1718.8417,-283.695 1728.7547,-279.9557 1718.6735,-276.697 1718.8417,-283.695"/>
<text text-anchor="middle" x="1397.2262" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1315.823,-347.9469C1314.3224,-337.1642 1314.6163,-323.8824 1322.2262,-315 1403.5478,-220.0795 1474.5203,-278.8875 1598.2262,-261 1837.2508,-226.4377 1903.0566,-260.5097 2139.2262,-210 2142.8104,-209.2334 2146.4891,-208.302 2150.1565,-207.2709"/>
<polygon fill="#000000" stroke="#000000" points="2151.2134,-210.6078 2159.7654,-204.3537 2149.1799,-203.9097 2151.2134,-210.6078"/>
<text text-anchor="middle" x="1659.2262" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge6" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1395.5051,-363.3816C1518.4104,-358.6688 1756.7419,-347.5801 1839.2262,-330 1858.2034,-325.9553 1861.7745,-321.0025 1880.2262,-315 1910.2692,-305.2266 1944.7943,-295.4633 1970.0986,-288.575"/>
<polygon fill="#000000" stroke="#000000" points="1971.2568,-291.8876 1979.9968,-285.899 1969.4299,-285.1302 1971.2568,-291.8876"/>
<text text-anchor="middle" x="1941.2262" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge23" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1217.6448,-97.8435C1081.952,-80.9788 744.3093,-39.0146 621.1316,-23.7054"/>
<polygon fill="#000000" stroke="#000000" points="621.2735,-20.1962 610.9182,-22.436 620.4101,-27.1427 621.2735,-20.1962"/>
<text text-anchor="middle" x="1017.7262" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sequencing_file -->
<g id="node22" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1139.2262" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1139.2262" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge1" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1151.3804,-348.0107C1160.3462,-336.3697 1173.6595,-322.1048 1189.2262,-315 1201.1719,-309.5478 1571.963,-289.7284 1719.0012,-282.0594"/>
<polygon fill="#000000" stroke="#000000" points="1719.3888,-285.544 1729.1932,-281.5286 1719.0247,-278.5535 1719.3888,-285.544"/>
<text text-anchor="middle" x="1255.7262" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1144.3241,-347.7916C1152.392,-322.9103 1170.7339,-279.2926 1204.2262,-261 1386.8492,-161.256 1934.9215,-249.4923 2139.2262,-210 2142.8756,-209.2946 2146.6176,-208.3981 2150.3432,-207.3834"/>
<polygon fill="#000000" stroke="#000000" points="2151.5116,-210.6873 2160.0915,-204.4715 2149.508,-203.9801 2151.5116,-210.6873"/>
<text text-anchor="middle" x="1270.7262" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge2" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1198.9394,-353.4165C1210.9094,-351.2865 1223.4316,-349.3355 1235.2262,-348 1284.7278,-342.3948 1636.5011,-347.2799 1683.2262,-330 1693.3171,-326.2682 1692.2878,-319.121 1702.2262,-315 1714.3832,-309.9589 1889.7731,-291.1616 1968.4803,-282.9173"/>
<polygon fill="#000000" stroke="#000000" points="1968.8915,-286.3935 1978.4735,-281.8729 1968.1638,-279.4314 1968.8915,-286.3935"/>
<text text-anchor="middle" x="1768.7262" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- study_arm -->
<g id="node24" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2402.2262" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2402.2262" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge14" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2383.8168,-87.7127C2369.7745,-75.7485 2349.3126,-60.8007 2328.2262,-54 2244.8266,-27.1023 892.8035,-19.4648 622.1651,-18.2024"/>
<polygon fill="#000000" stroke="#000000" points="621.9187,-14.7013 611.9027,-18.1552 621.8865,-21.7012 621.9187,-14.7013"/>
<text text-anchor="middle" x="2404.7262" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
</g>
</svg>
</div>
