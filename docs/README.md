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
<svg width="4193pt" height="305pt"
 viewBox="0.00 0.00 4193.34 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 4189.3431,-301 4189.3431,4 -4,4"/>
<!-- therapeutic_procedure -->
<g id="node1" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="907.3431" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="907.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- participant -->
<g id="node14" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1205.3431" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1205.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M911.5734,-173.7959C915.1715,-162.5258 921.5326,-148.7679 932.3431,-141 963.5183,-118.5991 1063.022,-110.1362 1132.8529,-106.9395"/>
<polygon fill="#000000" stroke="#000000" points="1133.089,-110.4327 1142.9289,-106.505 1132.7874,-103.4392 1133.089,-110.4327"/>
<text text-anchor="middle" x="1025.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- methylation_array_file -->
<g id="node2" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2710.3431" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2710.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- cell_line -->
<g id="node20" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="3270.3431" cy="-105" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="3270.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge5" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2715.162,-260.7831C2722.544,-236.7193 2739.0832,-194.9446 2769.3431,-174 2825.8277,-134.9039 2852.5127,-151.8649 2920.3431,-141 3022.0324,-124.7117 3141.584,-114.2635 3211.3658,-109.0278"/>
<polygon fill="#000000" stroke="#000000" points="3211.9954,-112.4909 3221.7099,-108.2626 3211.4789,-105.51 3211.9954,-112.4909"/>
<text text-anchor="middle" x="2860.8431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- pdx -->
<g id="node22" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2962.3431" cy="-105" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2962.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge4" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2639.4339,-264.6932C2610.9783,-258.5752 2577.9655,-251.0008 2548.3431,-243 2527.1747,-237.2825 2522.7126,-232.9128 2501.3431,-228 2473.9923,-221.712 2394.719,-231.2116 2376.3431,-210 2365.8667,-197.9069 2365.7115,-185.9569 2376.3431,-174 2412.8445,-132.9485 2799.5791,-112.2484 2924.0115,-106.6156"/>
<polygon fill="#000000" stroke="#000000" points="2924.3736,-110.1031 2934.2079,-106.1614 2924.062,-103.11 2924.3736,-110.1031"/>
<text text-anchor="middle" x="2467.8431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- sample -->
<g id="node25" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="3005.3431" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="3005.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2722.118,-260.9336C2730.6875,-249.4162 2743.3824,-235.3253 2758.3431,-228 2834.1265,-190.8937 2864.6106,-226.593 2947.3431,-210 2952.0692,-209.0521 2956.9571,-207.8687 2961.7983,-206.5641"/>
<polygon fill="#000000" stroke="#000000" points="2962.9551,-209.8736 2971.603,-203.7528 2961.0256,-203.1447 2962.9551,-209.8736"/>
<text text-anchor="middle" x="2849.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study_funding -->
<g id="node3" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="77.3431" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="77.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study -->
<g id="node19" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="690.3431" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="690.3431" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge32" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M88.8585,-87.0344C97.3975,-75.4039 110.1595,-61.1419 125.3431,-54 171.6798,-32.2048 516.9717,-22.0383 643.7972,-19.0107"/>
<polygon fill="#000000" stroke="#000000" points="644.0487,-22.5059 653.9639,-18.7722 643.8845,-15.5078 644.0487,-22.5059"/>
<text text-anchor="middle" x="187.3431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- medical_history -->
<g id="node4" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1128.3431" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1128.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1123.2612,-173.6612C1121.4838,-163.2983 1121.2338,-150.5483 1127.3431,-141 1132.5931,-132.7948 1140.2412,-126.4332 1148.7221,-121.5084"/>
<polygon fill="#000000" stroke="#000000" points="1150.4787,-124.5415 1157.796,-116.8794 1147.2976,-118.306 1150.4787,-124.5415"/>
<text text-anchor="middle" x="1195.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- study_admin -->
<g id="node5" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="243.3431" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="243.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge15" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M246.2978,-86.9386C249.1566,-75.5774 254.7005,-61.6627 265.3431,-54 295.4815,-32.3004 539.37,-22.5029 643.4974,-19.2791"/>
<polygon fill="#000000" stroke="#000000" points="643.8273,-22.7708 653.7168,-18.97 643.6156,-15.774 643.8273,-22.7708"/>
<text text-anchor="middle" x="321.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- pathology_file -->
<g id="node6" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="3085.3431" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="3085.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge38" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M3159.8047,-274.9943C3274.2115,-268.4755 3481.2816,-255.0831 3492.3431,-243 3549.4106,-180.662 3405.963,-135.9907 3323.537,-116.2721"/>
<polygon fill="#000000" stroke="#000000" points="3324.0954,-112.8083 3313.5607,-113.9356 3322.499,-119.6238 3324.0954,-112.8083"/>
<text text-anchor="middle" x="3565.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge37" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M3087.8708,-260.5403C3090.7546,-231.605 3091.8697,-175.336 3063.3431,-141 3054.7842,-130.698 3023.9353,-120.603 2998.5592,-113.7373"/>
<polygon fill="#000000" stroke="#000000" points="2999.3687,-110.3313 2988.808,-111.181 2997.5935,-117.1025 2999.3687,-110.3313"/>
<text text-anchor="middle" x="3148.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge39" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3020.4075,-269.5121C2990.0011,-263.6072 2958.4681,-254.8547 2949.3431,-243 2939.9562,-230.805 2950.8552,-219.1015 2965.4543,-209.9888"/>
<polygon fill="#000000" stroke="#000000" points="2967.383,-212.9186 2974.3523,-204.9386 2963.9277,-206.8308 2967.383,-212.9186"/>
<text text-anchor="middle" x="3010.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- publication -->
<g id="node7" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="394.3431" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="394.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge23" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M385.4929,-86.9031C381.6148,-76.1039 379.5089,-62.8202 387.3431,-54 404.0507,-35.1898 562.8156,-24.4725 643.6035,-20.1953"/>
<polygon fill="#000000" stroke="#000000" points="644.1878,-23.6698 653.9937,-19.658 643.8262,-16.6792 644.1878,-23.6698"/>
<text text-anchor="middle" x="438.3431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- clinical_measure_file -->
<g id="node8" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="534.3431" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="534.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M553.7364,-174.2064C567.7842,-162.4938 587.8384,-148.0654 608.3431,-141 656.7269,-124.3283 984.6367,-111.9846 1132.8574,-107.19"/>
<polygon fill="#000000" stroke="#000000" points="1133.3298,-110.6767 1143.2124,-106.8579 1133.1053,-103.6803 1133.3298,-110.6767"/>
<text text-anchor="middle" x="694.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge18" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M548.8624,-173.8474C556.8377,-164.0102 566.9842,-151.71 576.3431,-141 607.115,-105.7863 644.1491,-66.3412 667.4743,-41.8361"/>
<polygon fill="#000000" stroke="#000000" points="670.1702,-44.0807 674.5404,-34.4292 665.1053,-39.2488 670.1702,-44.0807"/>
<text text-anchor="middle" x="710.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- exposure -->
<g id="node9" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1284.3431" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1284.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge36" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1279.9376,-173.9995C1276.6801,-163.5002 1271.3905,-150.497 1263.3431,-141 1258.6025,-135.4053 1252.7652,-130.4121 1246.6383,-126.0563"/>
<polygon fill="#000000" stroke="#000000" points="1248.4626,-123.0673 1238.1798,-120.5152 1244.6267,-128.9227 1248.4626,-123.0673"/>
<text text-anchor="middle" x="1314.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node10" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="3531.3431" cy="-279" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="3531.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge12" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M3568.243,-261.6277C3606.4461,-241.3158 3657.079,-206.3469 3630.3431,-174 3592.8773,-128.6712 3421.8681,-112.829 3329.6693,-107.5236"/>
<polygon fill="#000000" stroke="#000000" points="3329.8216,-104.0268 3319.6439,-106.9704 3329.4359,-111.0161 3329.8216,-104.0268"/>
<text text-anchor="middle" x="3745.8431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge13" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M3531.345,-260.8521C3530.3032,-249.6051 3526.9344,-235.8518 3517.3431,-228 3472.5286,-191.3131 3304.2359,-243.9903 3257.3431,-210 3230.5468,-190.5766 3255.4951,-161.2826 3229.3431,-141 3211.5895,-127.2309 3070.0838,-113.8513 3000.587,-108.0327"/>
<polygon fill="#000000" stroke="#000000" points="3000.7343,-104.533 2990.48,-107.1974 3000.1576,-111.5092 3000.7343,-104.533"/>
<text text-anchor="middle" x="3365.8431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3402.9721,-272.447C3302.414,-266.4442 3171.1628,-256.4478 3119.3431,-243 3091.798,-235.8517 3062.5318,-222.6275 3040.5496,-211.4366"/>
<polygon fill="#000000" stroke="#000000" points="3042.0886,-208.292 3031.6009,-206.7886 3038.862,-214.5041 3042.0886,-208.292"/>
<text text-anchor="middle" x="3227.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- radiology_file -->
<g id="node11" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1429.3431" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1429.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1410.9002,-174.3325C1398.2059,-163.1376 1380.427,-149.2603 1362.3431,-141 1326.8228,-124.7751 1314.3891,-131.8002 1276.3431,-123 1271.6352,-121.911 1266.7606,-120.7488 1261.8724,-119.5589"/>
<polygon fill="#000000" stroke="#000000" points="1262.4161,-116.0882 1251.869,-117.0926 1260.7404,-122.8847 1262.4161,-116.0882"/>
<text text-anchor="middle" x="1444.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- synonym -->
<g id="node12" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1538.3431" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1538.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1540.3655,-260.8804C1542.5946,-230.8406 1542.0522,-171.0632 1507.3431,-141 1487.8834,-124.1449 1301.7462,-127.1785 1276.3431,-123 1271.0104,-122.1228 1265.4914,-121.0408 1259.995,-119.8461"/>
<polygon fill="#000000" stroke="#000000" points="1260.7003,-116.4171 1250.171,-117.5939 1259.1361,-123.2401 1260.7003,-116.4171"/>
<text text-anchor="middle" x="1580.8431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge31" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1486.19,-277.7597C1269.9579,-272.3685 453.4439,-249.4524 416.3431,-210 405.3822,-198.3442 408.3014,-187.8322 416.3431,-174 442.7624,-128.5573 583.7543,-63.4981 652.5416,-33.8316"/>
<polygon fill="#000000" stroke="#000000" points="654.3306,-36.8729 662.1444,-29.7179 651.5741,-30.4384 654.3306,-36.8729"/>
<text text-anchor="middle" x="490.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge29" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1589.7208,-275.8436C1729.7953,-267.3082 2130.168,-243.379 2463.3431,-228 2570.8586,-223.0372 2841.2474,-228.1079 2947.3431,-210 2952.1564,-209.1785 2957.1263,-208.0651 2962.0387,-206.7924"/>
<polygon fill="#000000" stroke="#000000" points="2963.2938,-210.0753 2971.9727,-203.9985 2961.3985,-203.3367 2963.2938,-210.0753"/>
<text text-anchor="middle" x="2505.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- diagnosis -->
<g id="node13" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1696.3431" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1696.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1663.6227,-177.4882C1634.9068,-165.4669 1591.7003,-149.091 1552.3431,-141 1431.9339,-116.2465 1397.7641,-142.1849 1276.3431,-123 1271.0049,-122.1565 1265.4823,-121.097 1259.9837,-119.9165"/>
<polygon fill="#000000" stroke="#000000" points="1260.6842,-116.4865 1250.157,-117.6812 1259.1316,-123.3121 1260.6842,-116.4865"/>
<text text-anchor="middle" x="1648.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge41" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1151.2025,-95.8539C1049.0212,-78.5922 829.543,-41.5153 735.082,-25.5578"/>
<polygon fill="#000000" stroke="#000000" points="735.4419,-22.0691 724.9986,-23.8544 734.2759,-28.9713 735.4419,-22.0691"/>
<text text-anchor="middle" x="1028.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_arm -->
<g id="node15" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1345.3431" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1345.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1300.9366,-92.817C1292.7858,-90.7516 1284.3306,-88.7214 1276.3431,-87 1078.3149,-44.3227 836.5576,-26.4063 736.7945,-20.4627"/>
<polygon fill="#000000" stroke="#000000" points="736.9316,-16.9648 726.7446,-19.8761 736.5236,-23.9529 736.9316,-16.9648"/>
<text text-anchor="middle" x="1229.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- study_personnel -->
<g id="node16" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="1510.3431" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1510.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge10" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1457.3457,-90.6247C1411.4159,-78.7745 1342.9884,-62.5709 1282.3431,-54 1177.2082,-39.1414 857.2481,-24.8587 736.8334,-19.8676"/>
<polygon fill="#000000" stroke="#000000" points="736.9592,-16.3699 726.8235,-19.4551 736.6709,-23.364 736.9592,-16.3699"/>
<text text-anchor="middle" x="1433.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- family_relationship -->
<g id="node17" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1869.3431" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1869.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1825.499,-175.7464C1791.1523,-163.8134 1741.888,-148.4398 1697.3431,-141 1512.6198,-110.1477 1461.646,-150.1553 1276.3431,-123 1270.9172,-122.2048 1265.3045,-121.1668 1259.7219,-119.9902"/>
<polygon fill="#000000" stroke="#000000" points="1260.2774,-116.5277 1249.7527,-117.7454 1258.7396,-123.3568 1260.2774,-116.5277"/>
<text text-anchor="middle" x="1838.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- sequencing_file -->
<g id="node18" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="3907.3431" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="3907.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge8" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M3954.9801,-264.1383C4007.0322,-245.5572 4078.7293,-211.588 4044.3431,-174 3996.3779,-121.5686 3503.0749,-108.7033 3329.9779,-105.7919"/>
<polygon fill="#000000" stroke="#000000" points="3329.8327,-102.2891 3319.777,-105.6256 3329.7186,-109.2882 3329.8327,-102.2891"/>
<text text-anchor="middle" x="4118.8431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge7" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M3904.6979,-260.8017C3900.0732,-236.3526 3888.0035,-193.6992 3858.3431,-174 3836.6225,-159.5741 3415.3373,-158.0478 3389.3431,-156 3313.8119,-150.0496 3089.6454,-121.4771 3000.005,-109.8937"/>
<polygon fill="#000000" stroke="#000000" points="3000.3741,-106.4123 2990.0076,-108.6001 2999.4758,-113.3545 3000.3741,-106.4123"/>
<text text-anchor="middle" x="3953.8431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3831.1932,-271.6315C3721.7755,-261.173 3513.7134,-241.7666 3336.3431,-228 3215.111,-218.5906 3182.9011,-232.1736 3063.3431,-210 3058.5422,-209.1096 3053.5801,-207.9523 3048.6723,-206.6537"/>
<polygon fill="#000000" stroke="#000000" points="3049.3196,-203.1991 3038.7436,-203.8302 3047.4048,-209.9321 3049.3196,-203.1991"/>
<text text-anchor="middle" x="3574.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge3" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3221.9066,-101.3015C3167.7113,-97.2754 3077.283,-90.8929 2999.3431,-87 2089.6051,-41.5603 976.6343,-22.4372 737.1261,-18.7013"/>
<polygon fill="#000000" stroke="#000000" points="737.0801,-15.2002 727.027,-18.5448 736.9716,-22.1994 737.0801,-15.2002"/>
<text text-anchor="middle" x="2597.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3233.5613,-117.0755C3185.4101,-132.8837 3101.0916,-160.5656 3049.5299,-177.4934"/>
<polygon fill="#000000" stroke="#000000" points="3048.3966,-174.1816 3039.9873,-180.6263 3050.5801,-180.8324 3048.3966,-174.1816"/>
<text text-anchor="middle" x="3193.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- molecular_test -->
<g id="node21" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="2067.3431" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="2067.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2024.8206,-176.683C1983.9615,-162.0211 1927.6403,-141.9805 1922.3431,-141 1781.1307,-114.8609 1418.5877,-142.7659 1276.3431,-123 1270.8327,-122.2343 1265.132,-121.2046 1259.4672,-120.0235"/>
<polygon fill="#000000" stroke="#000000" points="1259.8811,-116.5295 1249.3578,-117.7583 1258.3505,-123.3601 1259.8811,-116.5295"/>
<text text-anchor="middle" x="2028.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge20" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2934.4363,-103.9314C2698.4765,-94.896 1038.4702,-31.3306 737.1855,-19.7937"/>
<polygon fill="#000000" stroke="#000000" points="737.1722,-16.2907 727.0456,-19.4054 736.9043,-23.2856 737.1722,-16.2907"/>
<text text-anchor="middle" x="1986.3431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2943.3216,-118.2641C2931.1249,-128.4659 2919.0089,-142.9744 2927.3431,-156 2931.6699,-162.7624 2946.1517,-170.2037 2961.4823,-176.557"/>
<polygon fill="#000000" stroke="#000000" points="2960.4684,-179.9201 2971.0542,-180.3564 2963.0509,-173.4139 2960.4684,-179.9201"/>
<text text-anchor="middle" x="2951.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- follow_up -->
<g id="node23" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="716.3431" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="716.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge40" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M743.5644,-176.0425C765.0277,-164.2686 796.1147,-148.9648 825.3431,-141 881.5769,-125.6761 1039.9477,-114.4139 1133.5416,-108.8667"/>
<polygon fill="#000000" stroke="#000000" points="1134.0071,-112.3455 1143.7854,-108.267 1133.598,-105.3575 1134.0071,-112.3455"/>
<text text-anchor="middle" x="870.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- cytogenomic_file -->
<g id="node24" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="2487.3431" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="2487.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;cell_line -->
<g id="edge26" class="edge">
<title>cytogenomic_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2506.7783,-261.3237C2521.5524,-247.6623 2542.1894,-228.0918 2559.3431,-210 2573.8709,-194.6778 2571.9051,-184.289 2590.3431,-174 2671.6955,-128.6028 2704.8186,-151.8775 2797.3431,-141 2875.8861,-131.7662 3102.7951,-116.1255 3211.2522,-108.888"/>
<polygon fill="#000000" stroke="#000000" points="3211.624,-112.3711 3221.3693,-108.2143 3211.1588,-105.3865 3211.624,-112.3711"/>
<text text-anchor="middle" x="2661.8431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;pdx -->
<g id="edge25" class="edge">
<title>cytogenomic_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2400.8761,-273.9991C2320.3587,-268.4363 2210.7589,-258.1841 2197.3431,-243 2179.9109,-223.27 2187.3757,-200.4381 2221.3431,-174 2277.1703,-130.5476 2779.8503,-110.9412 2923.9165,-106.1834"/>
<polygon fill="#000000" stroke="#000000" points="2924.165,-109.6772 2934.0459,-105.8539 2923.9374,-102.6809 2924.165,-109.6772"/>
<text text-anchor="middle" x="2292.8431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2514.8302,-261.6718C2535.1312,-249.8534 2563.8927,-235.1035 2591.3431,-228 2744.7154,-188.3108 2791.3584,-237.6952 2947.3431,-210 2952.1508,-209.1464 2957.1171,-208.0125 2962.0275,-206.7278"/>
<polygon fill="#000000" stroke="#000000" points="2963.2883,-210.0086 2971.959,-203.9201 2961.384,-203.2726 2963.2883,-210.0086"/>
<text text-anchor="middle" x="2662.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2971.9711,-180.0108C2963.9991,-177.604 2955.4485,-175.39 2947.3431,-174 2574.2826,-110.0233 2474.6753,-152.4871 2096.3431,-141 1914.161,-135.4685 1456.948,-147.5527 1276.3431,-123 1270.8304,-122.2506 1265.1283,-121.2316 1259.4625,-120.057"/>
<polygon fill="#000000" stroke="#000000" points="1259.8745,-116.5629 1249.3521,-117.7995 1258.349,-123.3947 1259.8745,-116.5629"/>
<text text-anchor="middle" x="2859.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge35" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M3039.0922,-180.2913C3046.9732,-177.9029 3055.3895,-175.6264 3063.3431,-174 3101.6446,-166.1678 3205.1473,-176.6491 3238.3431,-156 3247.3021,-150.4272 3254.171,-141.3204 3259.2053,-132.3328"/>
<polygon fill="#000000" stroke="#000000" points="3262.4492,-133.6716 3263.7981,-123.163 3256.1903,-130.5367 3262.4492,-133.6716"/>
<text text-anchor="middle" x="3289.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge33" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2996.4335,-173.9735C2990.3574,-161.6801 2982.2099,-145.1956 2975.4037,-131.4249"/>
<polygon fill="#000000" stroke="#000000" points="2978.5165,-129.8237 2970.9479,-122.4097 2972.2412,-132.9253 2978.5165,-129.8237"/>
<text text-anchor="middle" x="3022.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
</g>
</svg>
</div>
