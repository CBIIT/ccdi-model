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
<svg width="4382pt" height="305pt"
 viewBox="0.00 0.00 4382.19 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 4378.1938,-301 4378.1938,4 -4,4"/>
<!-- study_admin -->
<g id="node1" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="70.1938" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="70.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study -->
<g id="node25" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="705.1938" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="705.1938" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge37" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M89.2932,-87.4833C103.3588,-75.7378 123.5552,-61.156 144.1938,-54 192.1775,-37.3626 533.0085,-23.9807 658.7483,-19.5593"/>
<polygon fill="#000000" stroke="#000000" points="658.9597,-23.0542 668.8316,-19.2078 658.7157,-16.0584 658.9597,-23.0542"/>
<text text-anchor="middle" x="200.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- publication -->
<g id="node2" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="221.1938" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="221.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge22" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M237.6294,-87.6117C249.8235,-75.9268 267.5118,-61.3645 286.1938,-54 352.891,-27.7077 563.8393,-20.569 658.4654,-18.6701"/>
<polygon fill="#000000" stroke="#000000" points="658.6713,-22.1669 668.6031,-18.4779 658.5385,-15.1681 658.6713,-22.1669"/>
<text text-anchor="middle" x="337.1938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- study_funding -->
<g id="node3" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="379.1938" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="379.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge5" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M383.3135,-87.0025C386.884,-75.6682 393.2561,-61.7596 404.1938,-54 424.5284,-39.5739 579.6779,-26.7798 658.9199,-21.1058"/>
<polygon fill="#000000" stroke="#000000" points="659.387,-24.5816 669.1152,-20.3851 658.8933,-17.5991 659.387,-24.5816"/>
<text text-anchor="middle" x="466.1938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- study_personnel -->
<g id="node4" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="561.1938" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="561.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge15" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M542.5867,-87.3924C533.891,-77.0323 527.0592,-64.0376 535.1938,-54 550.5248,-35.0825 614.1163,-25.7083 659.0092,-21.364"/>
<polygon fill="#000000" stroke="#000000" points="659.4885,-24.8349 669.128,-20.4382 658.8506,-17.864 659.4885,-24.8349"/>
<text text-anchor="middle" x="604.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- molecular_test -->
<g id="node5" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1147.1938" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1147.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- participant -->
<g id="node12" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1455.1938" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1455.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1157.92,-173.8881C1165.6715,-162.5055 1177.2159,-148.5861 1191.1938,-141 1223.4355,-123.5017 1317.064,-113.8671 1383.6373,-109.069"/>
<polygon fill="#000000" stroke="#000000" points="1383.9325,-112.557 1393.664,-108.3679 1383.4441,-105.574 1383.9325,-112.557"/>
<text text-anchor="middle" x="1255.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- methylation_array_file -->
<g id="node6" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="3994.1938" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="3994.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- sample -->
<g id="node9" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="3092.1938" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="3092.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3895.1219,-269.6653C3779.8692,-258.9472 3583.832,-241.1531 3415.1938,-228 3297.502,-218.8205 3266.2422,-231.6417 3150.1938,-210 3145.3937,-209.1048 3140.4322,-207.9445 3135.5247,-206.6441"/>
<polygon fill="#000000" stroke="#000000" points="3136.1725,-203.1896 3125.5964,-203.8186 3134.2564,-209.9222 3136.1725,-203.1896"/>
<text text-anchor="middle" x="3681.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- cell_line -->
<g id="node21" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="3381.1938" cy="-105" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="3381.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge18" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M4067.4929,-264.9784C4135.9902,-248.7805 4222.0339,-218.5142 4181.1938,-174 4131.3829,-119.708 3618.2413,-108.0302 3441.0089,-105.6094"/>
<polygon fill="#000000" stroke="#000000" points="3440.8687,-102.1073 3430.8235,-105.4755 3440.7766,-109.1067 3440.8687,-102.1073"/>
<text text-anchor="middle" x="4282.6938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- pdx -->
<g id="node23" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="3049.1938" cy="-105" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="3049.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge19" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M3990.5102,-260.7328C3984.4901,-236.2037 3969.985,-193.458 3939.1938,-174 3895.6722,-146.4972 3527.4539,-160.7886 3476.1938,-156 3431.0093,-151.779 3420.1996,-146.8249 3375.1938,-141 3271.3139,-127.5552 3148.395,-114.844 3087.4373,-108.7543"/>
<polygon fill="#000000" stroke="#000000" points="3087.4424,-105.2376 3077.145,-107.7303 3086.7493,-112.2033 3087.4424,-105.2376"/>
<text text-anchor="middle" x="4061.6938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- radiology_file -->
<g id="node7" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1318.1938" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1318.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1318.8846,-173.7775C1320.2395,-162.9311 1323.6961,-149.6418 1332.1938,-141 1341.2198,-131.8208 1367.2175,-123.5844 1392.9995,-117.314"/>
<polygon fill="#000000" stroke="#000000" points="1393.8968,-120.6986 1402.8344,-115.0092 1392.2995,-113.8833 1393.8968,-120.6986"/>
<text text-anchor="middle" x="1391.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- cytogenomic_file -->
<g id="node8" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="2824.1938" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="2824.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2836.1948,-260.7577C2844.7776,-249.32 2857.3998,-235.3882 2872.1938,-228 2937.0042,-195.6331 2963.2792,-224.803 3034.1938,-210 3038.9123,-209.015 3043.7953,-207.8078 3048.6336,-206.4891"/>
<polygon fill="#000000" stroke="#000000" points="3049.7971,-209.7962 3058.4349,-203.6612 3047.8565,-203.0706 3049.7971,-209.7962"/>
<text text-anchor="middle" x="2943.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;cell_line -->
<g id="edge29" class="edge">
<title>cytogenomic_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2831.2768,-260.7641C2841.648,-236.6789 2863.3705,-194.88 2896.1938,-174 2965.7816,-129.7329 3208.2988,-112.9362 3321.7828,-107.3942"/>
<polygon fill="#000000" stroke="#000000" points="3322.2022,-110.8784 3332.0248,-106.9076 3321.8699,-103.8863 3322.2022,-110.8784"/>
<text text-anchor="middle" x="2967.6938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;pdx -->
<g id="edge30" class="edge">
<title>cytogenomic_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2763.3062,-265.6423C2735.9247,-259.3136 2703.2892,-251.3239 2674.1938,-243 2653.9251,-237.2013 2649.4711,-233.7684 2629.1938,-228 2595.8062,-218.5021 2574.7256,-237.2272 2553.1938,-210 2543.269,-197.4501 2542.6884,-186.068 2553.1938,-174 2583.2977,-139.4183 2900.5663,-114.9777 3011.3092,-107.446"/>
<polygon fill="#000000" stroke="#000000" points="3011.6222,-110.9329 3021.365,-106.7701 3011.1527,-103.9487 3011.6222,-110.9329"/>
<text text-anchor="middle" x="2624.6938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3058.8157,-180.0456C3050.8439,-177.6374 3042.295,-175.414 3034.1938,-174 2710.7559,-117.5459 2624.3314,-152.1705 2296.1938,-141 2125.135,-135.1768 1695.7751,-146.1771 1526.1938,-123 1520.6816,-122.2466 1514.9798,-121.2251 1509.3143,-120.0489"/>
<polygon fill="#000000" stroke="#000000" points="1509.7267,-116.5549 1499.2041,-117.7896 1508.2,-123.3864 1509.7267,-116.5549"/>
<text text-anchor="middle" x="2946.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge36" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M3125.9322,-180.2386C3133.8137,-177.8527 3142.2328,-175.5906 3150.1938,-174 3192.217,-165.604 3304.7041,-176.7597 3342.1938,-156 3352.3913,-150.3532 3360.7656,-140.8091 3367.1045,-131.4942"/>
<polygon fill="#000000" stroke="#000000" points="3370.2251,-133.1046 3372.5514,-122.7683 3364.287,-129.3979 3370.2251,-133.1046"/>
<text text-anchor="middle" x="3395.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge35" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M3083.2841,-173.9735C3077.2081,-161.6801 3069.0606,-145.1956 3062.2543,-131.4249"/>
<polygon fill="#000000" stroke="#000000" points="3065.3672,-129.8237 3057.7986,-122.4097 3059.0918,-132.9253 3065.3672,-129.8237"/>
<text text-anchor="middle" x="3109.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node10" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="3224.1938" cy="-279" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="3224.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3103.9696,-270.1848C3068.1719,-264.9022 3035.452,-256.4656 3024.1938,-243 3012.3453,-228.8284 3028.342,-216.3222 3047.7859,-207.2409"/>
<polygon fill="#000000" stroke="#000000" points="3049.3873,-210.3621 3057.1864,-203.191 3046.6176,-203.9333 3049.3873,-210.3621"/>
<text text-anchor="middle" x="3132.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge11" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M3316.9394,-265.5908C3408.3999,-251.4066 3536.6012,-228.5569 3551.1938,-210 3588.391,-162.6976 3497.1196,-131.2887 3434.4047,-115.9535"/>
<polygon fill="#000000" stroke="#000000" points="3435.1464,-112.5324 3424.6086,-113.6304 3433.531,-119.3435 3435.1464,-112.5324"/>
<text text-anchor="middle" x="3667.6938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge12" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M3237.9525,-260.7542C3243.9554,-250.4223 3248.2054,-237.6723 3241.1938,-228 3226.0979,-207.1758 3205.8143,-226.6303 3186.1938,-210 3159.8073,-187.6349 3176.286,-163.7077 3150.1938,-141 3132.415,-125.5274 3107.5175,-116.5538 3086.8913,-111.4354"/>
<polygon fill="#000000" stroke="#000000" points="3087.3843,-107.9583 3076.8577,-109.1585 3085.8351,-114.7848 3087.3843,-107.9583"/>
<text text-anchor="middle" x="3294.6938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- diagnosis -->
<g id="node11" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1464.1938" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1464.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1459.4127,-173.8072C1458.124,-168.1428 1456.8939,-161.8485 1456.1938,-156 1455.331,-148.7924 1454.9182,-140.9718 1454.7557,-133.6697"/>
<polygon fill="#000000" stroke="#000000" points="1458.2541,-133.4454 1454.6734,-123.474 1451.2543,-133.502 1458.2541,-133.4454"/>
<text text-anchor="middle" x="1500.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge33" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1397.2776,-98.2817C1253.2612,-81.5758 881.2165,-38.4186 751.0124,-23.315"/>
<polygon fill="#000000" stroke="#000000" points="751.3123,-19.8264 740.9756,-22.1507 750.5057,-26.7797 751.3123,-19.8264"/>
<text text-anchor="middle" x="1174.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- clinical_measure_file -->
<g id="node13" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="722.1938" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="722.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M745.5,-174.1827C762.2477,-162.4592 785.8943,-148.0276 809.1938,-141 862.8616,-124.8127 1225.6131,-111.981 1382.7985,-107.114"/>
<polygon fill="#000000" stroke="#000000" points="1382.9616,-110.6107 1392.8493,-106.805 1382.7464,-103.614 1382.9616,-110.6107"/>
<text text-anchor="middle" x="895.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge26" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M720.4066,-173.7078C717.44,-143.3436 711.4782,-82.3226 707.9632,-46.3464"/>
<polygon fill="#000000" stroke="#000000" points="711.4129,-45.6593 706.957,-36.0471 704.446,-46.3401 711.4129,-45.6593"/>
<text text-anchor="middle" x="802.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- synonym -->
<g id="node14" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1555.1938" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1555.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1606.8292,-276.2911C1757.897,-268.4007 2212.136,-244.9244 2589.1938,-228 2688.064,-223.5622 2936.662,-226.8097 3034.1938,-210 3039.0057,-209.1707 3043.9747,-208.0523 3048.8866,-206.7766"/>
<polygon fill="#000000" stroke="#000000" points="3050.1431,-210.059 3058.82,-203.9794 3048.2457,-203.3211 3050.1431,-210.059"/>
<text text-anchor="middle" x="2631.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1556.1832,-260.9279C1557.6239,-227.9327 1558.8041,-159.6155 1545.1938,-141 1538.0549,-131.2358 1527.8302,-124.1167 1516.8152,-118.927"/>
<polygon fill="#000000" stroke="#000000" points="1518.0036,-115.6303 1507.4271,-115.0058 1515.3056,-122.0896 1518.0036,-115.6303"/>
<text text-anchor="middle" x="1598.6938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge10" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1503.2731,-277.172C1309.0821,-270.0879 635.0559,-243.1825 604.1938,-210 593.2971,-198.2841 599.0975,-189.1667 604.1938,-174 610.0546,-156.5581 615.6917,-153.5005 629.1938,-141 640.0496,-130.9494 647.5044,-134.1794 657.1938,-123 676.7744,-100.4082 689.8327,-68.4978 697.3219,-45.7968"/>
<polygon fill="#000000" stroke="#000000" points="700.716,-46.6706 700.3745,-36.0813 694.0379,-44.5723 700.716,-46.6706"/>
<text text-anchor="middle" x="671.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study_arm -->
<g id="node15" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1595.1938" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1595.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge6" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1551.6058,-92.6129C1543.2205,-90.5192 1534.4718,-88.5313 1526.1938,-87 1235.1412,-33.1589 878.182,-21.2761 752.0381,-18.699"/>
<polygon fill="#000000" stroke="#000000" points="752.0195,-15.198 741.9533,-18.503 751.8834,-22.1967 752.0195,-15.198"/>
<text text-anchor="middle" x="1463.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- pathology_file -->
<g id="node16" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="3456.1938" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="3456.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge39" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3399.5002,-266.9423C3353.2435,-257.0783 3294.6599,-244.5154 3289.1938,-243 3269.284,-237.4805 3265.1711,-233.2696 3245.1938,-228 3203.6416,-217.0395 3191.8934,-220.3854 3150.1938,-210 3145.7578,-208.8952 3141.1607,-207.6483 3136.5842,-206.3391"/>
<polygon fill="#000000" stroke="#000000" points="3137.2512,-202.8865 3126.6691,-203.4045 3135.2646,-209.5987 3137.2512,-202.8865"/>
<text text-anchor="middle" x="3350.1938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge41" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M3531.7946,-277.0443C3613.1062,-273.8061 3736.2487,-265.282 3777.1938,-243 3806.119,-227.2591 3825.5228,-199.0902 3804.1938,-174 3780.7973,-146.4779 3549.5047,-121.0073 3439.1756,-110.3119"/>
<polygon fill="#000000" stroke="#000000" points="3439.4953,-106.8266 3429.2063,-109.3538 3438.8256,-113.7945 3439.4953,-106.8266"/>
<text text-anchor="middle" x="3874.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge40" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M3447.4435,-260.9741C3433.2671,-231.8715 3406.5205,-177.4228 3403.1938,-174 3381.71,-151.8963 3371.5573,-150.376 3342.1938,-141 3295.6192,-126.1284 3155.7205,-113.4278 3087.4737,-107.9226"/>
<polygon fill="#000000" stroke="#000000" points="3087.4072,-104.4063 3077.1609,-107.1016 3086.8516,-111.3842 3087.4072,-104.4063"/>
<text text-anchor="middle" x="3482.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- follow_up -->
<g id="node17" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="1713.1938" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="1713.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1677.1202,-178.2597C1648.9558,-167.6778 1608.766,-152.8961 1573.1938,-141 1552.3338,-134.024 1529.2208,-126.8516 1509.0194,-120.763"/>
<polygon fill="#000000" stroke="#000000" points="1509.9428,-117.386 1499.3588,-117.8667 1507.9325,-124.0911 1509.9428,-117.386"/>
<text text-anchor="middle" x="1660.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- therapeutic_procedure -->
<g id="node18" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="1904.1938" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="1904.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1851.7256,-175.8698C1812.7552,-164.4807 1758.1079,-149.7457 1709.1938,-141 1628.7437,-126.6158 1606.6973,-137.0816 1526.1938,-123 1521.0796,-122.1054 1515.7907,-121.0384 1510.513,-119.8766"/>
<polygon fill="#000000" stroke="#000000" points="1510.9576,-116.3871 1500.4263,-117.5461 1509.3817,-123.2075 1510.9576,-116.3871"/>
<text text-anchor="middle" x="1866.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- medical_history -->
<g id="node19" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2125.1938" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2125.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge38" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2084.9872,-176.073C2052.6481,-164.0659 2005.7451,-148.4392 1963.1938,-141 1771.7112,-107.5233 1718.5484,-151.0352 1526.1938,-123 1520.7672,-122.2091 1515.1541,-121.1738 1509.5713,-119.999"/>
<polygon fill="#000000" stroke="#000000" points="1510.1262,-116.5365 1499.6018,-117.7563 1508.5898,-123.3658 1510.1262,-116.5365"/>
<text text-anchor="middle" x="2089.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- exposure -->
<g id="node20" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="2281.1938" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="2281.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2253.0966,-176.4923C2229.3904,-164.295 2194.1453,-148.1994 2161.1938,-141 2023.2793,-110.8678 1666.0134,-142.4633 1526.1938,-123 1520.7622,-122.2439 1515.1458,-121.2318 1509.561,-120.0713"/>
<polygon fill="#000000" stroke="#000000" points="1510.1114,-116.6081 1499.5891,-117.8455 1508.5864,-123.44 1510.1114,-116.6081"/>
<text text-anchor="middle" x="2248.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3342.7354,-116.3513C3296.8576,-129.924 3217.861,-153.3944 3150.1938,-174 3145.9372,-175.2962 3141.5078,-176.6542 3137.0781,-178.0184"/>
<polygon fill="#000000" stroke="#000000" points="3135.9692,-174.6977 3127.4477,-180.9933 3138.0353,-181.3859 3135.9692,-174.6977"/>
<text text-anchor="middle" x="3297.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge20" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3332.6698,-101.6139C3274.228,-97.6341 3173.0703,-91.0591 3086.1938,-87 2145.9318,-43.068 995.4052,-22.7106 751.8366,-18.7364"/>
<polygon fill="#000000" stroke="#000000" points="751.6342,-15.2327 741.5787,-18.57 751.5206,-22.2318 751.6342,-15.2327"/>
<text text-anchor="middle" x="2670.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- sequencing_file -->
<g id="node22" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2618.1938" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="2618.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2643.6791,-261.7066C2662.5402,-249.905 2689.3404,-235.161 2715.1938,-228 2852.0445,-190.0945 2894.4504,-235.2332 3034.1938,-210 3038.9989,-209.1323 3043.9636,-207.9895 3048.873,-206.6995"/>
<polygon fill="#000000" stroke="#000000" points="3050.1364,-209.9794 3058.8035,-203.8858 3048.2281,-203.2445 3050.1364,-209.9794"/>
<text text-anchor="middle" x="2781.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge2" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2637.1479,-261.2791C2647.8907,-251.3518 2661.6526,-238.8279 2674.1938,-228 2683.7563,-219.7439 2687.4511,-219.1198 2696.1938,-210 2710.0342,-195.5624 2706.0411,-184.2853 2723.1938,-174 2773.9905,-143.5407 3170.0815,-117.3717 3322.0801,-108.3526"/>
<polygon fill="#000000" stroke="#000000" points="3322.3871,-111.8406 3332.1638,-107.7582 3321.9751,-104.8528 3322.3871,-111.8406"/>
<text text-anchor="middle" x="2789.6938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge3" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2541.2592,-272.129C2477.084,-265.5983 2394.4977,-255.0104 2384.1938,-243 2367.0863,-223.0593 2375.5057,-199.6083 2408.1938,-174 2455.8107,-136.6961 2880.0773,-113.1922 3010.9352,-106.7818"/>
<polygon fill="#000000" stroke="#000000" points="3011.4419,-110.2615 3021.2609,-106.2818 3011.1033,-103.2697 3011.4419,-110.2615"/>
<text text-anchor="middle" x="2474.6938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge24" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3030.1723,-118.2641C3017.9756,-128.4659 3005.8596,-142.9744 3014.1938,-156 3018.5206,-162.7624 3033.0023,-170.2037 3048.3329,-176.557"/>
<polygon fill="#000000" stroke="#000000" points="3047.319,-179.9201 3057.9049,-180.3564 3049.9016,-173.4139 3047.319,-179.9201"/>
<text text-anchor="middle" x="3038.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge25" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3021.2366,-103.9623C2780.5483,-95.0289 1059.5994,-31.1541 752.1406,-19.7425"/>
<polygon fill="#000000" stroke="#000000" points="751.9274,-16.2322 741.8044,-19.3588 751.6677,-23.2274 751.9274,-16.2322"/>
<text text-anchor="middle" x="2041.1938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- family_relationship -->
<g id="node24" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="949.1938" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="949.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M964.5746,-174.082C975.6888,-162.4729 991.7623,-148.2167 1009.1938,-141 1042.7669,-127.1007 1265.5058,-114.2884 1382.965,-108.3988"/>
<polygon fill="#000000" stroke="#000000" points="1383.4905,-111.8771 1393.3043,-107.8846 1383.1428,-104.8857 1383.4905,-111.8771"/>
<text text-anchor="middle" x="1088.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
</g>
</svg>
</div>
