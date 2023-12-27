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
<svg width="2398pt" height="479pt"
 viewBox="0.00 0.00 2398.50 479.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 475)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-475 2394.4996,-475 2394.4996,4 -4,4"/>
<!-- pdx -->
<g id="node1" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="786.1565" cy="-366" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="786.1565" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample -->
<g id="node4" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="715.1565" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="715.1565" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M762.4561,-355.9744C741.9441,-347.0586 715.1115,-334.7237 712.1565,-330 707.97,-323.3078 707.057,-315.1046 707.6475,-307.25"/>
<polygon fill="#000000" stroke="#000000" points="711.1206,-307.6896 709.1407,-297.2814 704.1978,-306.6525 711.1206,-307.6896"/>
<text text-anchor="middle" x="736.1565" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study -->
<g id="node25" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1375.1565" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1375.1565" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge5" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M765.1973,-353.6582C761.2707,-351.609 757.1452,-349.6253 753.1565,-348 648.3949,-305.3122 366.1288,-256.8394 263.1565,-210 189.8679,-176.663 84.9485,-153.6244 130.1565,-87 152.4463,-54.1509 174.2876,-62.0694 213.1565,-54 323.5101,-31.0898 1125.9211,-20.7523 1328.703,-18.489"/>
<polygon fill="#000000" stroke="#000000" points="1328.769,-21.9886 1338.7297,-18.3782 1328.6916,-14.989 1328.769,-21.9886"/>
<text text-anchor="middle" x="287.1565" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- radiology_file -->
<g id="node2" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="746.1565" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="746.1565" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- participant -->
<g id="node10" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1297.1565" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1297.1565" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M765.5806,-174.5568C779.8676,-162.8459 800.3471,-148.2753 821.1565,-141 893.5839,-115.6783 1110.2566,-108.1531 1224.6229,-105.9274"/>
<polygon fill="#000000" stroke="#000000" points="1224.7585,-109.4256 1234.6916,-105.74 1224.6282,-102.4268 1224.7585,-109.4256"/>
<text text-anchor="middle" x="880.1565" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- exposure -->
<g id="node3" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="891.1565" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="891.1565" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M912.6515,-175.3167C928.8887,-163.6526 952.2256,-148.8159 975.1565,-141 1020.0249,-125.7067 1145.3829,-114.9466 1225.7995,-109.3794"/>
<polygon fill="#000000" stroke="#000000" points="1226.1224,-112.8656 1235.8612,-108.6936 1225.6463,-105.8818 1226.1224,-112.8656"/>
<text text-anchor="middle" x="1018.6565" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge2" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M740.4973,-293.7861C748.8463,-299.5866 757.6488,-306.823 764.1565,-315 769.7062,-321.9732 774.1162,-330.5587 777.486,-338.6834"/>
<polygon fill="#000000" stroke="#000000" points="774.2818,-340.1059 781.0874,-348.2259 780.831,-337.6342 774.2818,-340.1059"/>
<text text-anchor="middle" x="808.6565" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node8" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="369.1565" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="369.1565" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge3" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M680.6279,-267.5409C645.5692,-256.2377 589.5609,-239.0877 540.1565,-228 490.5354,-216.8636 476.6791,-221.5663 427.1565,-210 423.3385,-209.1083 419.4058,-208.0958 415.4724,-207.0165"/>
<polygon fill="#000000" stroke="#000000" points="416.3358,-203.623 405.7581,-204.2265 414.4034,-210.351 416.3358,-203.623"/>
<text text-anchor="middle" x="635.6565" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M759.4682,-278.4267C879.553,-276.1531 1208.2973,-264.9395 1299.1565,-210 1324.0524,-194.9463 1327.5489,-183.7908 1336.1565,-156 1338.1289,-149.6318 1338.8303,-147.107 1336.1565,-141 1334.319,-136.8033 1331.7242,-132.8788 1328.7356,-129.2791"/>
<polygon fill="#000000" stroke="#000000" points="1331.1495,-126.7393 1321.705,-121.938 1326.0939,-131.581 1331.1495,-126.7393"/>
<text text-anchor="middle" x="1365.6565" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node5" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1200.1565" cy="-453" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="1200.1565" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge39" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1079.2792,-444.3295C1009.5308,-438.2253 929.2568,-429.0034 896.1565,-417 884.6835,-412.8395 883.9524,-407.6909 873.1565,-402 856.272,-393.0996 836.6904,-384.8289 820.3848,-378.4651"/>
<polygon fill="#000000" stroke="#000000" points="821.2995,-375.0676 810.7091,-374.7607 818.7966,-381.6049 821.2995,-375.0676"/>
<text text-anchor="middle" x="1004.6565" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge38" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1240.0069,-435.7322C1256.5112,-426.2532 1269.459,-414.0107 1258.1565,-402 1235.5757,-378.0044 993.5907,-393.8777 962.1565,-384 906.018,-366.3594 903.2334,-338.2036 849.1565,-315 822.3828,-303.5118 790.9981,-294.8434 765.3352,-288.8945"/>
<polygon fill="#000000" stroke="#000000" points="765.9665,-285.4492 755.4421,-286.6691 764.4301,-292.2785 765.9665,-285.4492"/>
<text text-anchor="middle" x="1070.6565" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge40" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1253.6545,-436.3425C1304.3588,-417.8124 1368.4594,-385.4975 1337.1565,-348 1145.8118,-118.7904 972.3738,-265.4847 676.1565,-228 566.0789,-214.0703 536.187,-230.578 427.1565,-210 423.0771,-209.2301 418.8805,-208.2712 414.6992,-207.1996"/>
<polygon fill="#000000" stroke="#000000" points="415.6041,-203.8185 405.0332,-204.5309 413.741,-210.5661 415.6041,-203.8185"/>
<text text-anchor="middle" x="1427.6565" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- study_personnel -->
<g id="node6" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="226.1565" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="226.1565" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge36" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M218.9915,-86.6122C216.0604,-75.7035 215.0082,-62.4069 223.1565,-54 242.7041,-33.832 1114.5562,-21.3436 1328.2496,-18.5822"/>
<polygon fill="#000000" stroke="#000000" points="1328.548,-22.0788 1338.5023,-18.4507 1328.4582,-15.0794 1328.548,-22.0788"/>
<text text-anchor="middle" x="292.6565" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- methylation_array_file -->
<g id="node7" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="372.1565" cy="-453" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="372.1565" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge28" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M415.0394,-436.213C446.4252,-424.6566 490.309,-409.9975 530.1565,-402 623.7373,-383.2181 651.546,-407.096 744.1565,-384 747.5698,-383.1488 751.0607,-382.0523 754.5001,-380.8212"/>
<polygon fill="#000000" stroke="#000000" points="755.9355,-384.0174 763.9489,-377.0867 753.3624,-377.5075 755.9355,-384.0174"/>
<text text-anchor="middle" x="621.6565" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M369.0156,-434.8891C366.0727,-411.3364 365.0738,-370.5499 388.1565,-348 410.5938,-326.0805 497.3963,-336.1413 528.1565,-330 577.3821,-320.172 632.7335,-304.4812 670.3579,-293.0971"/>
<polygon fill="#000000" stroke="#000000" points="671.4587,-296.4206 680.0028,-290.1556 669.4167,-289.725 671.4587,-296.4206"/>
<text text-anchor="middle" x="479.6565" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge29" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M360.4237,-434.8422C342.5038,-407.703 308.4714,-358.6044 290.1565,-348 241.2017,-319.6551 201.2203,-372.7349 164.1565,-330 112.3696,-270.2892 241.2853,-225.0511 317.6407,-204.3787"/>
<polygon fill="#000000" stroke="#000000" points="318.8163,-207.6881 327.5864,-201.7437 317.0235,-200.9215 318.8163,-207.6881"/>
<text text-anchor="middle" x="255.6565" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M390.9366,-208.2483C407.6369,-219.8525 431.7254,-234.8056 455.1565,-243 492.2102,-255.9586 597.1459,-267.78 661.8153,-274.1257"/>
<polygon fill="#000000" stroke="#000000" points="661.541,-277.6155 671.8321,-275.0965 662.2164,-270.6481 661.541,-277.6155"/>
<text text-anchor="middle" x="495.6565" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M386.4537,-175.102C399.892,-163.1662 419.6419,-148.0829 440.1565,-141 476.9291,-128.3039 1024.8206,-112.3446 1224.797,-106.9116"/>
<polygon fill="#000000" stroke="#000000" points="1225.0063,-110.4073 1234.9079,-106.6378 1224.8168,-103.4098 1225.0063,-110.4073"/>
<text text-anchor="middle" x="480.6565" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge20" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M379.6478,-174.1124C395.4257,-149.1865 427.8638,-105.0386 469.1565,-87 548.2658,-52.4413 1154.5326,-26.5328 1328.5791,-19.7498"/>
<polygon fill="#000000" stroke="#000000" points="1328.8393,-23.2424 1338.6963,-19.3581 1328.5684,-16.2476 1328.8393,-23.2424"/>
<text text-anchor="middle" x="509.6565" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- clinical_measure_file -->
<g id="node9" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="545.1565" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="545.1565" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M531.5793,-173.9325C525.2184,-163.1443 520.7002,-149.8619 529.1565,-141 541.0748,-128.5099 1035.5821,-112.6884 1224.6702,-107.0833"/>
<polygon fill="#000000" stroke="#000000" points="1224.8998,-110.5782 1234.7921,-106.7844 1224.6931,-103.5812 1224.8998,-110.5782"/>
<text text-anchor="middle" x="658.6565" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge42" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M527.3843,-174.0853C519.1461,-163.6164 512.827,-150.6151 521.1565,-141 574.7148,-79.1751 1158.5906,-33.3078 1328.8283,-21.1757"/>
<polygon fill="#000000" stroke="#000000" points="1329.2405,-24.6553 1338.9685,-20.4581 1328.7464,-17.6728 1329.2405,-24.6553"/>
<text text-anchor="middle" x="784.1565" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge22" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1296.1037,-86.961C1296.3765,-76.4479 1298.3329,-63.444 1305.1565,-54 1312.4096,-43.9616 1323.2997,-36.5189 1334.3429,-31.0923"/>
<polygon fill="#000000" stroke="#000000" points="1335.857,-34.2496 1343.5788,-26.9953 1333.0185,-27.8509 1335.857,-34.2496"/>
<text text-anchor="middle" x="1355.6565" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- family_relationship -->
<g id="node11" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1062.1565" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1062.1565" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge37" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1062.4302,-173.8955C1063.5992,-162.8126 1067.0061,-149.2248 1076.1565,-141 1097.726,-121.6121 1169.2315,-112.5949 1225.1335,-108.4457"/>
<polygon fill="#000000" stroke="#000000" points="1225.6445,-111.9185 1235.3745,-107.7262 1225.1538,-104.9357 1225.6445,-111.9185"/>
<text text-anchor="middle" x="1155.6565" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- follow_up -->
<g id="node12" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="1235.1565" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="1235.1565" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1235.86,-173.753C1237.0112,-163.4206 1239.7612,-150.6706 1246.1565,-141 1249.5267,-135.9037 1253.8857,-131.3062 1258.6347,-127.2349"/>
<polygon fill="#000000" stroke="#000000" points="1261.0973,-129.7564 1266.8893,-120.8849 1256.8292,-124.2081 1261.0973,-129.7564"/>
<text text-anchor="middle" x="1291.1565" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- therapeutic_procedure -->
<g id="node13" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="1535.1565" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="1535.1565" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1489.5493,-175.3285C1448.2263,-160.223 1387.532,-138.0364 1345.4076,-122.638"/>
<polygon fill="#000000" stroke="#000000" points="1346.5136,-119.3159 1335.9198,-119.1698 1344.1103,-125.8904 1346.5136,-119.3159"/>
<text text-anchor="middle" x="1523.1565" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- study_arm -->
<g id="node14" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1437.1565" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1437.1565" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge14" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1429.0864,-86.7984C1424.241,-76.7207 1417.5843,-64.2065 1410.1565,-54 1407.0308,-49.7051 1403.4101,-45.415 1399.707,-41.3709"/>
<polygon fill="#000000" stroke="#000000" points="1402.0432,-38.7505 1392.593,-33.9604 1396.9934,-43.5982 1402.0432,-38.7505"/>
<text text-anchor="middle" x="1467.6565" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- synonym -->
<g id="node15" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2120.1565" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2120.1565" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge32" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2072.5332,-358.5618C1997.276,-347.1269 1846.1435,-325.4575 1717.1565,-315 1530.5777,-299.8733 950.2618,-284.7537 769.4869,-280.3062"/>
<polygon fill="#000000" stroke="#000000" points="769.4992,-276.8055 759.4164,-280.0593 769.3276,-283.8034 769.4992,-276.8055"/>
<text text-anchor="middle" x="1903.6565" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2114.804,-347.8786C2107.67,-319.8935 2098.405,-265.48 2121.1565,-228 2130.0288,-213.384 2146.3371,-224.648 2155.1565,-210 2163.4094,-196.2927 2161.6987,-188.6013 2155.1565,-174 2146.1466,-153.8915 2138.6506,-149.0944 2118.1565,-141 2040.6272,-110.3788 1450.7425,-134.3135 1368.1565,-123 1362.6445,-122.2449 1356.9429,-121.2222 1351.2774,-120.0454"/>
<polygon fill="#000000" stroke="#000000" points="1351.6901,-116.5513 1341.1674,-117.7852 1350.1629,-123.3827 1351.6901,-116.5513"/>
<text text-anchor="middle" x="2163.6565" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge33" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2137.5097,-348.7691C2158.5003,-326.5768 2192.6945,-285.7469 2206.1565,-243 2222.0919,-192.3988 2191.1302,-165.6555 2144.1565,-141 2100.7235,-118.203 1972.7604,-129.6168 1924.1565,-123 1734.1648,-97.135 1510.3967,-48.6442 1418.1797,-27.8638"/>
<polygon fill="#000000" stroke="#000000" points="1418.8978,-24.4379 1408.3721,-25.6463 1417.354,-31.2656 1418.8978,-24.4379"/>
<text text-anchor="middle" x="2251.6565" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- sequencing_file -->
<g id="node16" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="589.1565" cy="-453" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="589.1565" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge15" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M650.0771,-440.6654C671.8759,-435.0196 696.2167,-427.2532 717.1565,-417 726.1305,-412.6058 744.6481,-398.8112 760.2422,-386.6755"/>
<polygon fill="#000000" stroke="#000000" points="762.82,-389.1016 768.5256,-380.1743 758.4982,-383.5951 762.82,-389.1016"/>
<text text-anchor="middle" x="805.6565" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M539.8188,-438.4616C519.2844,-429.791 502.6074,-417.4493 514.1565,-402 531.081,-379.3599 550.401,-397.6447 575.1565,-384 596.3939,-372.2944 597.0683,-362.9563 616.1565,-348 637.8479,-331.004 663.3848,-313.2574 683.0889,-300.0185"/>
<polygon fill="#000000" stroke="#000000" points="685.0491,-302.9182 691.422,-294.4543 681.1619,-297.0967 685.0491,-302.9182"/>
<text text-anchor="middle" x="682.6565" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge17" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M533.7498,-439.4945C471.0833,-423.6654 376.3631,-397.8422 366.1565,-384 347.5721,-358.796 357.8797,-267.1845 364.6828,-220.2054"/>
<polygon fill="#000000" stroke="#000000" points="368.1777,-220.4994 366.1935,-210.0921 361.2545,-219.4652 368.1777,-220.4994"/>
<text text-anchor="middle" x="422.6565" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- publication -->
<g id="node17" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="1996.1565" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="1996.1565" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge41" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1976.4697,-87.7488C1961.7606,-75.9676 1940.5775,-61.2306 1919.1565,-54 1872.6999,-38.3186 1545.0442,-24.4372 1421.8402,-19.7156"/>
<polygon fill="#000000" stroke="#000000" points="1421.7264,-16.2089 1411.6007,-19.3263 1421.4604,-23.2038 1421.7264,-16.2089"/>
<text text-anchor="middle" x="1999.1565" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- study_admin -->
<g id="node18" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="2147.1565" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2147.1565" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge26" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2123.2166,-87.9253C2105.1692,-76.0667 2079.3059,-61.158 2054.1565,-54 1993.7888,-36.8182 1565.0906,-23.3382 1421.7243,-19.2678"/>
<polygon fill="#000000" stroke="#000000" points="1421.602,-15.7631 1411.5074,-18.98 1421.4048,-22.7603 1421.602,-15.7631"/>
<text text-anchor="middle" x="2144.6565" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- diagnosis -->
<g id="node19" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1725.1565" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1725.1565" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1699.4881,-176.084C1678.8696,-164.1674 1648.7367,-148.656 1620.1565,-141 1511.6951,-111.9459 1479.0112,-140.8668 1368.1565,-123 1362.8209,-122.14 1357.3,-121.0695 1351.8025,-119.882"/>
<polygon fill="#000000" stroke="#000000" points="1352.5054,-116.4525 1341.9771,-117.6385 1350.947,-123.2769 1352.5054,-116.4525"/>
<text text-anchor="middle" x="1703.6565" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- molecular_test -->
<g id="node20" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1878.1565" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1878.1565" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1845.9686,-175.4333C1821.0692,-163.5015 1785.3513,-148.2741 1752.1565,-141 1585.2625,-104.4281 1537.1537,-148.1207 1368.1565,-123 1362.7321,-122.1937 1357.1205,-121.1482 1351.5386,-119.9671"/>
<polygon fill="#000000" stroke="#000000" points="1352.0955,-116.5048 1341.5703,-117.7169 1350.5541,-123.333 1352.0955,-116.5048"/>
<text text-anchor="middle" x="1862.1565" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- study_funding -->
<g id="node21" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2313.1565" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2313.1565" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge21" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2285.431,-88.1198C2264.2678,-76.1932 2233.9423,-61.1134 2205.1565,-54 2129.2002,-35.2299 1585.7104,-22.4155 1421.8199,-18.9457"/>
<polygon fill="#000000" stroke="#000000" points="1421.654,-15.4415 1411.5827,-18.7307 1421.5069,-22.44 1421.654,-15.4415"/>
<text text-anchor="middle" x="2307.1565" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- cytogenomic_file -->
<g id="node22" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="133.1565" cy="-453" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="133.1565" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;pdx -->
<g id="edge9" class="edge">
<title>cytogenomic_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M180.1468,-437.5392C218.8628,-425.5425 275.4453,-409.7 326.1565,-402 509.9992,-374.0852 562.8507,-425.2988 744.1565,-384 747.5864,-383.2187 751.0883,-382.168 754.5343,-380.9647"/>
<polygon fill="#000000" stroke="#000000" points="755.9533,-384.1679 763.9917,-377.2661 753.4038,-377.6487 755.9533,-384.1679"/>
<text text-anchor="middle" x="397.6565" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M142.4822,-435.015C156.3466,-410.399 184.923,-367.0946 223.1565,-348 278.9375,-320.1418 443.1997,-347.1113 503.1565,-330 516.7321,-326.1256 517.8588,-319.7415 531.1565,-315 573.894,-299.7613 624.6439,-290.4442 662.0092,-285.1181"/>
<polygon fill="#000000" stroke="#000000" points="662.7455,-288.5498 672.1754,-283.72 661.7918,-281.6151 662.7455,-288.5498"/>
<text text-anchor="middle" x="294.6565" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;cell_line -->
<g id="edge11" class="edge">
<title>cytogenomic_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M97.8071,-436.3881C50.5734,-411.8322 -23.6984,-363.4987 8.1565,-315 42.4918,-262.7248 222.7465,-220.6196 314.8564,-202.1426"/>
<polygon fill="#000000" stroke="#000000" points="315.703,-205.543 324.8314,-200.165 314.3416,-198.6767 315.703,-205.543"/>
<text text-anchor="middle" x="79.6565" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- pathology_file -->
<g id="node23" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1432.1565" cy="-453" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1432.1565" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge23" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1376.4816,-440.6391C1366.7302,-438.6376 1356.6639,-436.675 1347.1565,-435 1321.2975,-430.4441 1139.231,-405.092 1113.1565,-402 1030.2421,-392.1678 1009.1294,-393.3249 926.1565,-384 891.3907,-380.0928 851.8618,-374.9457 823.6939,-371.1566"/>
<polygon fill="#000000" stroke="#000000" points="823.8671,-367.6482 813.4882,-369.7763 822.9288,-374.585 823.8671,-367.6482"/>
<text text-anchor="middle" x="1278.1565" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge24" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1399.9184,-436.5857C1352.7046,-413.2554 1261.4156,-370.8107 1179.1565,-348 1034.1726,-307.7956 856.8059,-289.6846 769.2966,-282.7171"/>
<polygon fill="#000000" stroke="#000000" points="769.3199,-279.2084 759.0784,-281.9219 768.7767,-286.1873 769.3199,-279.2084"/>
<text text-anchor="middle" x="1342.1565" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge25" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1462.0812,-436.2574C1505.0449,-410.1171 1575.3592,-358.1322 1540.1565,-315 1464.4306,-222.2169 1394.5393,-279.1274 1276.1565,-261 1133.9532,-239.2251 1097.6834,-237.7944 954.1565,-228 837.249,-220.0221 542.6953,-229.5395 427.1565,-210 423.0047,-209.2979 418.7368,-208.3767 414.4899,-207.322"/>
<polygon fill="#000000" stroke="#000000" points="415.2513,-203.9021 404.6835,-204.6587 413.4166,-210.6574 415.2513,-203.9021"/>
<text text-anchor="middle" x="1608.1565" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- medical_history -->
<g id="node24" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2061.1565" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2061.1565" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2027.9149,-175.4229C2001.9919,-163.4015 1964.7083,-148.063 1930.1565,-141 1807.7351,-115.9751 1491.8842,-140.4553 1368.1565,-123 1362.7263,-122.2339 1357.1108,-121.2151 1351.5266,-120.0505"/>
<polygon fill="#000000" stroke="#000000" points="1352.0783,-116.5875 1341.5553,-117.8199 1350.55,-123.4187 1352.0783,-116.5875"/>
<text text-anchor="middle" x="2046.1565" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
</g>
</svg>
</div>
