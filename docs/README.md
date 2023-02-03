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
<svg width="3470pt" height="1735pt"
 viewBox="0.00 0.00 3470.00 1735.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1731)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1731 3466,-1731 3466,4 -4,4"/>
<!-- study_personnel -->
<g id="node1" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M12,-294C12,-294 319,-294 319,-294 325,-294 331,-300 331,-306 331,-306 331,-397 331,-397 331,-403 325,-409 319,-409 319,-409 12,-409 12,-409 6,-409 0,-403 0,-397 0,-397 0,-306 0,-306 0,-300 6,-294 12,-294"/>
<text text-anchor="middle" x="67" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="134,-294 134,-409 "/>
<text text-anchor="middle" x="144.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="155,-294 155,-409 "/>
<text text-anchor="middle" x="232.5" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="155,-386 310,-386 "/>
<text text-anchor="middle" x="232.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="155,-363 310,-363 "/>
<text text-anchor="middle" x="232.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="155,-340 310,-340 "/>
<text text-anchor="middle" x="232.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="155,-317 310,-317 "/>
<text text-anchor="middle" x="232.5" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="310,-294 310,-409 "/>
<text text-anchor="middle" x="320.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node13" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M813.5,-.5C813.5,-.5 1203.5,-.5 1203.5,-.5 1209.5,-.5 1215.5,-6.5 1215.5,-12.5 1215.5,-12.5 1215.5,-195.5 1215.5,-195.5 1215.5,-201.5 1209.5,-207.5 1203.5,-207.5 1203.5,-207.5 813.5,-207.5 813.5,-207.5 807.5,-207.5 801.5,-201.5 801.5,-195.5 801.5,-195.5 801.5,-12.5 801.5,-12.5 801.5,-6.5 807.5,-.5 813.5,-.5"/>
<text text-anchor="middle" x="829.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="857.5,-.5 857.5,-207.5 "/>
<text text-anchor="middle" x="868" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="878.5,-.5 878.5,-207.5 "/>
<text text-anchor="middle" x="1036.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="878.5,-184.5 1194.5,-184.5 "/>
<text text-anchor="middle" x="1036.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="878.5,-161.5 1194.5,-161.5 "/>
<text text-anchor="middle" x="1036.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="878.5,-138.5 1194.5,-138.5 "/>
<text text-anchor="middle" x="1036.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="878.5,-115.5 1194.5,-115.5 "/>
<text text-anchor="middle" x="1036.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="878.5,-92.5 1194.5,-92.5 "/>
<text text-anchor="middle" x="1036.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="878.5,-69.5 1194.5,-69.5 "/>
<text text-anchor="middle" x="1036.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="878.5,-46.5 1194.5,-46.5 "/>
<text text-anchor="middle" x="1036.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="878.5,-23.5 1194.5,-23.5 "/>
<text text-anchor="middle" x="1036.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="1194.5,-.5 1194.5,-207.5 "/>
<text text-anchor="middle" x="1205" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge15" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M171.0192,-293.7675C176.3447,-269.394 186.6523,-242.8194 206.5,-226 292.4595,-153.1557 584.2657,-123.7104 791.023,-111.8702"/>
<polygon fill="#000000" stroke="#000000" points="791.3241,-115.3589 801.1116,-111.3026 790.9308,-108.37 791.3241,-115.3589"/>
<text text-anchor="middle" x="276" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- therapeutic_procedure -->
<g id="node2" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M794,-823.5C794,-823.5 1151,-823.5 1151,-823.5 1157,-823.5 1163,-829.5 1163,-835.5 1163,-835.5 1163,-926.5 1163,-926.5 1163,-932.5 1157,-938.5 1151,-938.5 1151,-938.5 794,-938.5 794,-938.5 788,-938.5 782,-932.5 782,-926.5 782,-926.5 782,-835.5 782,-835.5 782,-829.5 788,-823.5 794,-823.5"/>
<text text-anchor="middle" x="872.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="963,-823.5 963,-938.5 "/>
<text text-anchor="middle" x="973.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="984,-823.5 984,-938.5 "/>
<text text-anchor="middle" x="1063" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="984,-915.5 1142,-915.5 "/>
<text text-anchor="middle" x="1063" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="984,-892.5 1142,-892.5 "/>
<text text-anchor="middle" x="1063" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="984,-869.5 1142,-869.5 "/>
<text text-anchor="middle" x="1063" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="984,-846.5 1142,-846.5 "/>
<text text-anchor="middle" x="1063" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1142,-823.5 1142,-938.5 "/>
<text text-anchor="middle" x="1152.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node16" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M1228.5,-495.5C1228.5,-495.5 1532.5,-495.5 1532.5,-495.5 1538.5,-495.5 1544.5,-501.5 1544.5,-507.5 1544.5,-507.5 1544.5,-598.5 1544.5,-598.5 1544.5,-604.5 1538.5,-610.5 1532.5,-610.5 1532.5,-610.5 1228.5,-610.5 1228.5,-610.5 1222.5,-610.5 1216.5,-604.5 1216.5,-598.5 1216.5,-598.5 1216.5,-507.5 1216.5,-507.5 1216.5,-501.5 1222.5,-495.5 1228.5,-495.5"/>
<text text-anchor="middle" x="1264.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1312.5,-495.5 1312.5,-610.5 "/>
<text text-anchor="middle" x="1323" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1333.5,-495.5 1333.5,-610.5 "/>
<text text-anchor="middle" x="1428.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="1333.5,-587.5 1523.5,-587.5 "/>
<text text-anchor="middle" x="1428.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="1333.5,-564.5 1523.5,-564.5 "/>
<text text-anchor="middle" x="1428.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="1333.5,-541.5 1523.5,-541.5 "/>
<text text-anchor="middle" x="1428.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1333.5,-518.5 1523.5,-518.5 "/>
<text text-anchor="middle" x="1428.5" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1523.5,-495.5 1523.5,-610.5 "/>
<text text-anchor="middle" x="1534" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1010.0427,-823.3962C1049.2222,-767.1879 1115.3541,-682.5407 1190.5,-629 1197.0102,-624.3616 1203.8437,-619.9514 1210.8934,-615.7652"/>
<polygon fill="#000000" stroke="#000000" points="1212.9974,-618.5934 1219.9307,-610.5821 1209.5148,-612.5211 1212.9974,-618.5934"/>
<text text-anchor="middle" x="1283.5" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- sample_diagnosis -->
<g id="node3" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M2608,-1220.5C2608,-1220.5 3041,-1220.5 3041,-1220.5 3047,-1220.5 3053,-1226.5 3053,-1232.5 3053,-1232.5 3053,-1645.5 3053,-1645.5 3053,-1651.5 3047,-1657.5 3041,-1657.5 3041,-1657.5 2608,-1657.5 2608,-1657.5 2602,-1657.5 2596,-1651.5 2596,-1645.5 2596,-1645.5 2596,-1232.5 2596,-1232.5 2596,-1226.5 2602,-1220.5 2608,-1220.5"/>
<text text-anchor="middle" x="2667.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2739,-1220.5 2739,-1657.5 "/>
<text text-anchor="middle" x="2749.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2760,-1220.5 2760,-1657.5 "/>
<text text-anchor="middle" x="2896" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2760,-1634.5 3032,-1634.5 "/>
<text text-anchor="middle" x="2896" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="2760,-1611.5 3032,-1611.5 "/>
<text text-anchor="middle" x="2896" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2760,-1588.5 3032,-1588.5 "/>
<text text-anchor="middle" x="2896" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="2760,-1565.5 3032,-1565.5 "/>
<text text-anchor="middle" x="2896" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="2760,-1542.5 3032,-1542.5 "/>
<text text-anchor="middle" x="2896" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="2760,-1519.5 3032,-1519.5 "/>
<text text-anchor="middle" x="2896" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="2760,-1496.5 3032,-1496.5 "/>
<text text-anchor="middle" x="2896" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2760,-1473.5 3032,-1473.5 "/>
<text text-anchor="middle" x="2896" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="2760,-1450.5 3032,-1450.5 "/>
<text text-anchor="middle" x="2896" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="2760,-1427.5 3032,-1427.5 "/>
<text text-anchor="middle" x="2896" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="2760,-1404.5 3032,-1404.5 "/>
<text text-anchor="middle" x="2896" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="2760,-1381.5 3032,-1381.5 "/>
<text text-anchor="middle" x="2896" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="2760,-1358.5 3032,-1358.5 "/>
<text text-anchor="middle" x="2896" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="2760,-1335.5 3032,-1335.5 "/>
<text text-anchor="middle" x="2896" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="2760,-1312.5 3032,-1312.5 "/>
<text text-anchor="middle" x="2896" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="2760,-1289.5 3032,-1289.5 "/>
<text text-anchor="middle" x="2896" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="2760,-1266.5 3032,-1266.5 "/>
<text text-anchor="middle" x="2896" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="2760,-1243.5 3032,-1243.5 "/>
<text text-anchor="middle" x="2896" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="3032,-1220.5 3032,-1657.5 "/>
<text text-anchor="middle" x="3042.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node8" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1730.5,-800.5C1730.5,-800.5 2044.5,-800.5 2044.5,-800.5 2050.5,-800.5 2056.5,-806.5 2056.5,-812.5 2056.5,-812.5 2056.5,-949.5 2056.5,-949.5 2056.5,-955.5 2050.5,-961.5 2044.5,-961.5 2044.5,-961.5 1730.5,-961.5 1730.5,-961.5 1724.5,-961.5 1718.5,-955.5 1718.5,-949.5 1718.5,-949.5 1718.5,-812.5 1718.5,-812.5 1718.5,-806.5 1724.5,-800.5 1730.5,-800.5"/>
<text text-anchor="middle" x="1752.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1786.5,-800.5 1786.5,-961.5 "/>
<text text-anchor="middle" x="1797" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1807.5,-800.5 1807.5,-961.5 "/>
<text text-anchor="middle" x="1921.5" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="1807.5,-938.5 2035.5,-938.5 "/>
<text text-anchor="middle" x="1921.5" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1807.5,-915.5 2035.5,-915.5 "/>
<text text-anchor="middle" x="1921.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1807.5,-892.5 2035.5,-892.5 "/>
<text text-anchor="middle" x="1921.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1807.5,-869.5 2035.5,-869.5 "/>
<text text-anchor="middle" x="1921.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1807.5,-846.5 2035.5,-846.5 "/>
<text text-anchor="middle" x="1921.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1807.5,-823.5 2035.5,-823.5 "/>
<text text-anchor="middle" x="1921.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="2035.5,-800.5 2035.5,-961.5 "/>
<text text-anchor="middle" x="2046" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2665.9168,-1220.4478C2641.5419,-1194.9707 2615.1967,-1170.9905 2587.5,-1151 2428.9892,-1036.5926 2215.7503,-963.5319 2066.4302,-922.6594"/>
<polygon fill="#000000" stroke="#000000" points="2067.2562,-919.257 2056.6885,-920.0136 2065.4215,-926.0123 2067.2562,-919.257"/>
<text text-anchor="middle" x="2627.5" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
<!-- synonym -->
<g id="node4" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M1006,-1416C1006,-1416 1307,-1416 1307,-1416 1313,-1416 1319,-1422 1319,-1428 1319,-1428 1319,-1450 1319,-1450 1319,-1456 1313,-1462 1307,-1462 1307,-1462 1006,-1462 1006,-1462 1000,-1462 994,-1456 994,-1450 994,-1450 994,-1428 994,-1428 994,-1422 1000,-1416 1006,-1416"/>
<text text-anchor="middle" x="1034" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="1074,-1416 1074,-1462 "/>
<text text-anchor="middle" x="1084.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1095,-1416 1095,-1462 "/>
<text text-anchor="middle" x="1196.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="1095,-1439 1298,-1439 "/>
<text text-anchor="middle" x="1196.5" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="1298,-1416 1298,-1462 "/>
<text text-anchor="middle" x="1308.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1162.3423,-1415.82C1178.0402,-1358.961 1226.9907,-1212.7308 1328.5,-1151 1385.1843,-1116.5286 1564.5112,-1156.6383 1626.5,-1133 1636.5528,-1129.1666 1635.9679,-1122.9892 1645.5,-1118 1669.7894,-1105.2866 1681.6497,-1115.1482 1704.5,-1100 1755.235,-1066.3661 1799.4199,-1014.5779 1831.6572,-969.8057"/>
<polygon fill="#000000" stroke="#000000" points="1834.5962,-971.7121 1837.5364,-961.5334 1828.8904,-967.6569 1834.5962,-971.7121"/>
<text text-anchor="middle" x="1688" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge6" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M993.8976,-1417.3919C811.5824,-1383.8046 522.6419,-1300.5426 378.5,-1100 321.4789,-1020.6673 359.5,-978.699 359.5,-881 359.5,-881 359.5,-881 359.5,-351.5 359.5,-309.5306 349.4022,-289.2448 378.5,-259 435.5333,-199.7185 632.5822,-157.625 791.301,-132.4048"/>
<polygon fill="#000000" stroke="#000000" points="791.8846,-135.8561 801.2183,-130.8429 790.7955,-128.9414 791.8846,-135.8561"/>
<text text-anchor="middle" x="402" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1163.1307,-1415.8253C1180.3091,-1360.2598 1231.8059,-1219.0224 1328.5,-1151 1424.8131,-1083.2456 1513.6746,-1190.9286 1588.5,-1100 1619.4237,-1062.4212 1613.6902,-703.6401 1588.5,-662 1577.7551,-644.2384 1563.0559,-629.2302 1546.4005,-616.5828"/>
<polygon fill="#000000" stroke="#000000" points="1548.2298,-613.5864 1538.0758,-610.562 1544.1275,-619.2584 1548.2298,-613.5864"/>
<text text-anchor="middle" x="1652" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study_funding -->
<g id="node5" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M400,-317C400,-317 779,-317 779,-317 785,-317 791,-323 791,-329 791,-329 791,-374 791,-374 791,-380 785,-386 779,-386 779,-386 400,-386 400,-386 394,-386 388,-380 388,-374 388,-374 388,-329 388,-329 388,-323 394,-317 400,-317"/>
<text text-anchor="middle" x="447.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="507,-317 507,-386 "/>
<text text-anchor="middle" x="517.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="528,-317 528,-386 "/>
<text text-anchor="middle" x="649" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="528,-363 770,-363 "/>
<text text-anchor="middle" x="649" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="528,-340 770,-340 "/>
<text text-anchor="middle" x="649" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="770,-317 770,-386 "/>
<text text-anchor="middle" x="780.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge16" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M607.4569,-316.7817C623.4989,-288.8156 649.3982,-250.2855 681.5,-226 714.4933,-201.0401 753.1475,-180.7161 792.0964,-164.3305"/>
<polygon fill="#000000" stroke="#000000" points="793.557,-167.5141 801.4667,-160.4652 790.8877,-161.043 793.557,-167.5141"/>
<text text-anchor="middle" x="743.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- methylation_array_file -->
<g id="node6" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M3083,-1324C3083,-1324 3450,-1324 3450,-1324 3456,-1324 3462,-1330 3462,-1336 3462,-1336 3462,-1542 3462,-1542 3462,-1548 3456,-1554 3450,-1554 3450,-1554 3083,-1554 3083,-1554 3077,-1554 3071,-1548 3071,-1542 3071,-1542 3071,-1336 3071,-1336 3071,-1330 3077,-1324 3083,-1324"/>
<text text-anchor="middle" x="3160" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="3249,-1324 3249,-1554 "/>
<text text-anchor="middle" x="3259.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3270,-1324 3270,-1554 "/>
<text text-anchor="middle" x="3355.5" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="3270,-1531 3441,-1531 "/>
<text text-anchor="middle" x="3355.5" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="3270,-1508 3441,-1508 "/>
<text text-anchor="middle" x="3355.5" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="3270,-1485 3441,-1485 "/>
<text text-anchor="middle" x="3355.5" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="3270,-1462 3441,-1462 "/>
<text text-anchor="middle" x="3355.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="3270,-1439 3441,-1439 "/>
<text text-anchor="middle" x="3355.5" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="3270,-1416 3441,-1416 "/>
<text text-anchor="middle" x="3355.5" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="3270,-1393 3441,-1393 "/>
<text text-anchor="middle" x="3355.5" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="3270,-1370 3441,-1370 "/>
<text text-anchor="middle" x="3355.5" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="3270,-1347 3441,-1347 "/>
<text text-anchor="middle" x="3355.5" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="3441,-1324 3441,-1554 "/>
<text text-anchor="middle" x="3451.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3211.1117,-1323.783C3176.4639,-1263.5661 3126.2619,-1193.709 3062.5,-1151 2900.7863,-1042.6808 2353.8848,-949.244 2066.8191,-906.2357"/>
<polygon fill="#000000" stroke="#000000" points="2067.1253,-902.7427 2056.7179,-904.7271 2066.0912,-909.6659 2067.1253,-902.7427"/>
<text text-anchor="middle" x="3106" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study_arm -->
<g id="node7" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M860,-317C860,-317 1157,-317 1157,-317 1163,-317 1169,-323 1169,-329 1169,-329 1169,-374 1169,-374 1169,-380 1163,-386 1157,-386 1157,-386 860,-386 860,-386 854,-386 848,-380 848,-374 848,-374 848,-329 848,-329 848,-323 854,-317 860,-317"/>
<text text-anchor="middle" x="894" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="940,-317 940,-386 "/>
<text text-anchor="middle" x="950.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="961,-317 961,-386 "/>
<text text-anchor="middle" x="1054.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="961,-363 1148,-363 "/>
<text text-anchor="middle" x="1054.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="961,-340 1148,-340 "/>
<text text-anchor="middle" x="1054.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="1148,-317 1148,-386 "/>
<text text-anchor="middle" x="1158.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge14" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1008.5,-316.8256C1008.5,-290.8629 1008.5,-253.7725 1008.5,-217.8091"/>
<polygon fill="#000000" stroke="#000000" points="1012.0001,-217.7056 1008.5,-207.7056 1005.0001,-217.7056 1012.0001,-217.7056"/>
<text text-anchor="middle" x="1057" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge18" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1867.3262,-800.2782C1829.842,-667.1932 1736.675,-402.237 1559.5,-259 1507.1976,-216.7162 1356.1536,-175.8124 1225.4122,-146.6511"/>
<polygon fill="#000000" stroke="#000000" points="1226.1573,-143.2314 1215.6368,-144.4841 1224.6422,-150.0655 1226.1573,-143.2314"/>
<text text-anchor="middle" x="1770" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1836.8978,-800.3236C1804.1823,-754.0399 1757.8246,-698.1301 1704.5,-662 1683.207,-647.5729 1672.6921,-655.1201 1649.5,-644 1638.4955,-638.7236 1637.548,-634.1846 1626.5,-629 1603.6254,-618.2654 1578.8581,-608.5658 1554.1495,-599.9676"/>
<polygon fill="#000000" stroke="#000000" points="1555.2812,-596.6556 1544.6866,-596.7263 1553.0129,-603.2779 1555.2812,-596.6556"/>
<text text-anchor="middle" x="1686" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- publication -->
<g id="node9" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M1199.5,-333.5C1199.5,-333.5 1409.5,-333.5 1409.5,-333.5 1415.5,-333.5 1421.5,-339.5 1421.5,-345.5 1421.5,-345.5 1421.5,-357.5 1421.5,-357.5 1421.5,-363.5 1415.5,-369.5 1409.5,-369.5 1409.5,-369.5 1199.5,-369.5 1199.5,-369.5 1193.5,-369.5 1187.5,-363.5 1187.5,-357.5 1187.5,-357.5 1187.5,-345.5 1187.5,-345.5 1187.5,-339.5 1193.5,-333.5 1199.5,-333.5"/>
<text text-anchor="middle" x="1236" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="1284.5,-333.5 1284.5,-369.5 "/>
<text text-anchor="middle" x="1295" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1305.5,-333.5 1305.5,-369.5 "/>
<text text-anchor="middle" x="1353" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="1400.5,-333.5 1400.5,-369.5 "/>
<text text-anchor="middle" x="1411" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge4" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1282.7344,-333.3007C1252.3225,-307.8718 1194.6912,-259.6835 1140.0795,-214.02"/>
<polygon fill="#000000" stroke="#000000" points="1142.3135,-211.3256 1132.3967,-207.5961 1137.8232,-216.6958 1142.3135,-211.3256"/>
<text text-anchor="middle" x="1216.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- diagnosis -->
<g id="node10" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1193.5,-662.5C1193.5,-662.5 1567.5,-662.5 1567.5,-662.5 1573.5,-662.5 1579.5,-668.5 1579.5,-674.5 1579.5,-674.5 1579.5,-1087.5 1579.5,-1087.5 1579.5,-1093.5 1573.5,-1099.5 1567.5,-1099.5 1567.5,-1099.5 1193.5,-1099.5 1193.5,-1099.5 1187.5,-1099.5 1181.5,-1093.5 1181.5,-1087.5 1181.5,-1087.5 1181.5,-674.5 1181.5,-674.5 1181.5,-668.5 1187.5,-662.5 1193.5,-662.5"/>
<text text-anchor="middle" x="1223.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1265.5,-662.5 1265.5,-1099.5 "/>
<text text-anchor="middle" x="1276" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1286.5,-662.5 1286.5,-1099.5 "/>
<text text-anchor="middle" x="1422.5" y="-1084.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1286.5,-1076.5 1558.5,-1076.5 "/>
<text text-anchor="middle" x="1422.5" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1286.5,-1053.5 1558.5,-1053.5 "/>
<text text-anchor="middle" x="1422.5" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1286.5,-1030.5 1558.5,-1030.5 "/>
<text text-anchor="middle" x="1422.5" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1286.5,-1007.5 1558.5,-1007.5 "/>
<text text-anchor="middle" x="1422.5" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="1286.5,-984.5 1558.5,-984.5 "/>
<text text-anchor="middle" x="1422.5" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="1286.5,-961.5 1558.5,-961.5 "/>
<text text-anchor="middle" x="1422.5" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="1286.5,-938.5 1558.5,-938.5 "/>
<text text-anchor="middle" x="1422.5" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1286.5,-915.5 1558.5,-915.5 "/>
<text text-anchor="middle" x="1422.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1286.5,-892.5 1558.5,-892.5 "/>
<text text-anchor="middle" x="1422.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="1286.5,-869.5 1558.5,-869.5 "/>
<text text-anchor="middle" x="1422.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="1286.5,-846.5 1558.5,-846.5 "/>
<text text-anchor="middle" x="1422.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="1286.5,-823.5 1558.5,-823.5 "/>
<text text-anchor="middle" x="1422.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="1286.5,-800.5 1558.5,-800.5 "/>
<text text-anchor="middle" x="1422.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1286.5,-777.5 1558.5,-777.5 "/>
<text text-anchor="middle" x="1422.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="1286.5,-754.5 1558.5,-754.5 "/>
<text text-anchor="middle" x="1422.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="1286.5,-731.5 1558.5,-731.5 "/>
<text text-anchor="middle" x="1422.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1286.5,-708.5 1558.5,-708.5 "/>
<text text-anchor="middle" x="1422.5" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1286.5,-685.5 1558.5,-685.5 "/>
<text text-anchor="middle" x="1422.5" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1558.5,-662.5 1558.5,-1099.5 "/>
<text text-anchor="middle" x="1569" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1380.5,-662.2193C1380.5,-647.476 1380.5,-633.4001 1380.5,-620.5497"/>
<polygon fill="#000000" stroke="#000000" points="1384.0001,-620.5173 1380.5,-610.5174 1377.0001,-620.5174 1384.0001,-620.5173"/>
<text text-anchor="middle" x="1425" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- pdx -->
<g id="node11" class="node">
<title>pdx</title>
<path fill="none" stroke="#000000" d="M1349,-1335.5C1349,-1335.5 1678,-1335.5 1678,-1335.5 1684,-1335.5 1690,-1341.5 1690,-1347.5 1690,-1347.5 1690,-1530.5 1690,-1530.5 1690,-1536.5 1684,-1542.5 1678,-1542.5 1678,-1542.5 1349,-1542.5 1349,-1542.5 1343,-1542.5 1337,-1536.5 1337,-1530.5 1337,-1530.5 1337,-1347.5 1337,-1347.5 1337,-1341.5 1343,-1335.5 1349,-1335.5"/>
<text text-anchor="middle" x="1358.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
<polyline fill="none" stroke="#000000" points="1380,-1335.5 1380,-1542.5 "/>
<text text-anchor="middle" x="1390.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1401,-1335.5 1401,-1542.5 "/>
<text text-anchor="middle" x="1535" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">injection_type_and_site</text>
<polyline fill="none" stroke="#000000" points="1401,-1519.5 1669,-1519.5 "/>
<text text-anchor="middle" x="1535" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_id</text>
<polyline fill="none" stroke="#000000" points="1401,-1496.5 1669,-1496.5 "/>
<text text-anchor="middle" x="1535" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_type</text>
<polyline fill="none" stroke="#000000" points="1401,-1473.5 1669,-1473.5 "/>
<text text-anchor="middle" x="1535" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">mouse_strain</text>
<polyline fill="none" stroke="#000000" points="1401,-1450.5 1669,-1450.5 "/>
<text text-anchor="middle" x="1535" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">strain_immune_system_humanized</text>
<polyline fill="none" stroke="#000000" points="1401,-1427.5 1669,-1427.5 "/>
<text text-anchor="middle" x="1535" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_characterization_method</text>
<polyline fill="none" stroke="#000000" points="1401,-1404.5 1669,-1404.5 "/>
<text text-anchor="middle" x="1535" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_not_mus_or_ebv_origin</text>
<polyline fill="none" stroke="#000000" points="1401,-1381.5 1669,-1381.5 "/>
<text text-anchor="middle" x="1535" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_preparation</text>
<polyline fill="none" stroke="#000000" points="1401,-1358.5 1669,-1358.5 "/>
<text text-anchor="middle" x="1535" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_humanization</text>
<polyline fill="none" stroke="#000000" points="1669,-1335.5 1669,-1542.5 "/>
<text text-anchor="middle" x="1679.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1563.0243,-1335.4439C1595.4542,-1275.8472 1642.3811,-1202.7563 1699.5,-1151 1712.4623,-1139.2546 1721.7021,-1144.9243 1734.5,-1133 1783.3506,-1087.484 1822.1446,-1022.9184 1848.446,-970.5372"/>
<polygon fill="#000000" stroke="#000000" points="1851.5831,-972.0892 1852.8848,-961.5746 1845.3102,-968.9825 1851.5831,-972.0892"/>
<text text-anchor="middle" x="1769.5" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- imaging_file -->
<g id="node12" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M1720.5,-1278C1720.5,-1278 2054.5,-1278 2054.5,-1278 2060.5,-1278 2066.5,-1284 2066.5,-1290 2066.5,-1290 2066.5,-1588 2066.5,-1588 2066.5,-1594 2060.5,-1600 2054.5,-1600 2054.5,-1600 1720.5,-1600 1720.5,-1600 1714.5,-1600 1708.5,-1594 1708.5,-1588 1708.5,-1588 1708.5,-1290 1708.5,-1290 1708.5,-1284 1714.5,-1278 1720.5,-1278"/>
<text text-anchor="middle" x="1760.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="1812.5,-1278 1812.5,-1600 "/>
<text text-anchor="middle" x="1823" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1833.5,-1278 1833.5,-1600 "/>
<text text-anchor="middle" x="1939.5" y="-1584.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1833.5,-1577 2045.5,-1577 "/>
<text text-anchor="middle" x="1939.5" y="-1561.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1833.5,-1554 2045.5,-1554 "/>
<text text-anchor="middle" x="1939.5" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1833.5,-1531 2045.5,-1531 "/>
<text text-anchor="middle" x="1939.5" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1833.5,-1508 2045.5,-1508 "/>
<text text-anchor="middle" x="1939.5" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1833.5,-1485 2045.5,-1485 "/>
<text text-anchor="middle" x="1939.5" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1833.5,-1462 2045.5,-1462 "/>
<text text-anchor="middle" x="1939.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1833.5,-1439 2045.5,-1439 "/>
<text text-anchor="middle" x="1939.5" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1833.5,-1416 2045.5,-1416 "/>
<text text-anchor="middle" x="1939.5" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1833.5,-1393 2045.5,-1393 "/>
<text text-anchor="middle" x="1939.5" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="1833.5,-1370 2045.5,-1370 "/>
<text text-anchor="middle" x="1939.5" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="1833.5,-1347 2045.5,-1347 "/>
<text text-anchor="middle" x="1939.5" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="1833.5,-1324 2045.5,-1324 "/>
<text text-anchor="middle" x="1939.5" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1833.5,-1301 2045.5,-1301 "/>
<text text-anchor="middle" x="1939.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="2045.5,-1278 2045.5,-1600 "/>
<text text-anchor="middle" x="2056" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1887.5,-1277.9777C1887.5,-1178.4707 1887.5,-1054.4213 1887.5,-971.732"/>
<polygon fill="#000000" stroke="#000000" points="1891.0001,-971.606 1887.5,-961.606 1884.0001,-971.606 1891.0001,-971.606"/>
<text text-anchor="middle" x="1942" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- sequencing_file -->
<g id="node14" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M2097,-1151.5C2097,-1151.5 2566,-1151.5 2566,-1151.5 2572,-1151.5 2578,-1157.5 2578,-1163.5 2578,-1163.5 2578,-1714.5 2578,-1714.5 2578,-1720.5 2572,-1726.5 2566,-1726.5 2566,-1726.5 2097,-1726.5 2097,-1726.5 2091,-1726.5 2085,-1720.5 2085,-1714.5 2085,-1714.5 2085,-1163.5 2085,-1163.5 2085,-1157.5 2091,-1151.5 2097,-1151.5"/>
<text text-anchor="middle" x="2149" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="2213,-1151.5 2213,-1726.5 "/>
<text text-anchor="middle" x="2223.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2234,-1151.5 2234,-1726.5 "/>
<text text-anchor="middle" x="2395.5" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="2234,-1703.5 2557,-1703.5 "/>
<text text-anchor="middle" x="2395.5" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2234,-1680.5 2557,-1680.5 "/>
<text text-anchor="middle" x="2395.5" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2234,-1657.5 2557,-1657.5 "/>
<text text-anchor="middle" x="2395.5" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="2234,-1634.5 2557,-1634.5 "/>
<text text-anchor="middle" x="2395.5" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="2234,-1611.5 2557,-1611.5 "/>
<text text-anchor="middle" x="2395.5" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2234,-1588.5 2557,-1588.5 "/>
<text text-anchor="middle" x="2395.5" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="2234,-1565.5 2557,-1565.5 "/>
<text text-anchor="middle" x="2395.5" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2234,-1542.5 2557,-1542.5 "/>
<text text-anchor="middle" x="2395.5" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2234,-1519.5 2557,-1519.5 "/>
<text text-anchor="middle" x="2395.5" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2234,-1496.5 2557,-1496.5 "/>
<text text-anchor="middle" x="2395.5" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2234,-1473.5 2557,-1473.5 "/>
<text text-anchor="middle" x="2395.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2234,-1450.5 2557,-1450.5 "/>
<text text-anchor="middle" x="2395.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2234,-1427.5 2557,-1427.5 "/>
<text text-anchor="middle" x="2395.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="2234,-1404.5 2557,-1404.5 "/>
<text text-anchor="middle" x="2395.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="2234,-1381.5 2557,-1381.5 "/>
<text text-anchor="middle" x="2395.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="2234,-1358.5 2557,-1358.5 "/>
<text text-anchor="middle" x="2395.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="2234,-1335.5 2557,-1335.5 "/>
<text text-anchor="middle" x="2395.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="2234,-1312.5 2557,-1312.5 "/>
<text text-anchor="middle" x="2395.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="2234,-1289.5 2557,-1289.5 "/>
<text text-anchor="middle" x="2395.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2234,-1266.5 2557,-1266.5 "/>
<text text-anchor="middle" x="2395.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="2234,-1243.5 2557,-1243.5 "/>
<text text-anchor="middle" x="2395.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="2234,-1220.5 2557,-1220.5 "/>
<text text-anchor="middle" x="2395.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="2234,-1197.5 2557,-1197.5 "/>
<text text-anchor="middle" x="2395.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="2234,-1174.5 2557,-1174.5 "/>
<text text-anchor="middle" x="2395.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="2557,-1151.5 2557,-1726.5 "/>
<text text-anchor="middle" x="2567.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2102.6719,-1151.4187C2049.9841,-1085.2031 1997.8098,-1019.6325 1958.0345,-969.6447"/>
<polygon fill="#000000" stroke="#000000" points="1960.7243,-967.4039 1951.7591,-961.7581 1955.2468,-971.7624 1960.7243,-967.4039"/>
<text text-anchor="middle" x="2149" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node15" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M399.5,-754.5C399.5,-754.5 751.5,-754.5 751.5,-754.5 757.5,-754.5 763.5,-760.5 763.5,-766.5 763.5,-766.5 763.5,-995.5 763.5,-995.5 763.5,-1001.5 757.5,-1007.5 751.5,-1007.5 751.5,-1007.5 399.5,-1007.5 399.5,-1007.5 393.5,-1007.5 387.5,-1001.5 387.5,-995.5 387.5,-995.5 387.5,-766.5 387.5,-766.5 387.5,-760.5 393.5,-754.5 399.5,-754.5"/>
<text text-anchor="middle" x="471" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="554.5,-754.5 554.5,-1007.5 "/>
<text text-anchor="middle" x="565" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="575.5,-754.5 575.5,-1007.5 "/>
<text text-anchor="middle" x="659" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="575.5,-984.5 742.5,-984.5 "/>
<text text-anchor="middle" x="659" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="575.5,-961.5 742.5,-961.5 "/>
<text text-anchor="middle" x="659" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="575.5,-938.5 742.5,-938.5 "/>
<text text-anchor="middle" x="659" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="575.5,-915.5 742.5,-915.5 "/>
<text text-anchor="middle" x="659" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="575.5,-892.5 742.5,-892.5 "/>
<text text-anchor="middle" x="659" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="575.5,-869.5 742.5,-869.5 "/>
<text text-anchor="middle" x="659" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="575.5,-846.5 742.5,-846.5 "/>
<text text-anchor="middle" x="659" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="575.5,-823.5 742.5,-823.5 "/>
<text text-anchor="middle" x="659" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="575.5,-800.5 742.5,-800.5 "/>
<text text-anchor="middle" x="659" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="575.5,-777.5 742.5,-777.5 "/>
<text text-anchor="middle" x="659" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="742.5,-754.5 742.5,-1007.5 "/>
<text text-anchor="middle" x="753" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge12" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M652.0091,-754.0523C700.4047,-668.9272 760.8976,-552.8791 799.5,-444 827.5795,-364.801 796.7734,-331.9372 838.5,-259 847.2854,-243.6433 858.1204,-228.9602 870.0327,-215.1774"/>
<polygon fill="#000000" stroke="#000000" points="872.7277,-217.4138 876.7553,-207.6144 867.4957,-212.7633 872.7277,-217.4138"/>
<text text-anchor="middle" x="879.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M666.0993,-754.2959C696.3725,-719.8306 732.6632,-685.5593 772.5,-662 786.3494,-653.8095 897.7168,-632.1274 913.5,-629 1009.9009,-609.8982 1118.1939,-592.0516 1206.2089,-578.4589"/>
<polygon fill="#000000" stroke="#000000" points="1206.9419,-581.8873 1216.2929,-576.9064 1205.8768,-574.9688 1206.9419,-581.8873"/>
<text text-anchor="middle" x="1043" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge20" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1273.5321,-495.3695C1242.8362,-478.8073 1209.332,-460.7066 1178.5,-444 1146.3692,-426.5896 1110.8547,-407.2765 1080.6315,-390.82"/>
<polygon fill="#000000" stroke="#000000" points="1082.3004,-387.7436 1071.8442,-386.0347 1078.9525,-393.8911 1082.3004,-387.7436"/>
<text text-anchor="middle" x="1285" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge19" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1413.0752,-495.382C1444.1724,-431.862 1479.619,-329.3688 1430.5,-259 1404.5574,-221.8342 1315.2945,-186.4879 1225.5057,-158.96"/>
<polygon fill="#000000" stroke="#000000" points="1226.2771,-155.5366 1215.6917,-155.9823 1224.2447,-162.235 1226.2771,-155.5366"/>
<text text-anchor="middle" x="1505" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_admin -->
<g id="node17" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M1776.5,-259.5C1776.5,-259.5 2102.5,-259.5 2102.5,-259.5 2108.5,-259.5 2114.5,-265.5 2114.5,-271.5 2114.5,-271.5 2114.5,-431.5 2114.5,-431.5 2114.5,-437.5 2108.5,-443.5 2102.5,-443.5 2102.5,-443.5 1776.5,-443.5 1776.5,-443.5 1770.5,-443.5 1764.5,-437.5 1764.5,-431.5 1764.5,-431.5 1764.5,-271.5 1764.5,-271.5 1764.5,-265.5 1770.5,-259.5 1776.5,-259.5"/>
<text text-anchor="middle" x="1818.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="1872.5,-259.5 1872.5,-443.5 "/>
<text text-anchor="middle" x="1883" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1893.5,-259.5 1893.5,-443.5 "/>
<text text-anchor="middle" x="1993.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="1893.5,-420.5 2093.5,-420.5 "/>
<text text-anchor="middle" x="1993.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="1893.5,-397.5 2093.5,-397.5 "/>
<text text-anchor="middle" x="1993.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="1893.5,-374.5 2093.5,-374.5 "/>
<text text-anchor="middle" x="1993.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="1893.5,-351.5 2093.5,-351.5 "/>
<text text-anchor="middle" x="1993.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="1893.5,-328.5 2093.5,-328.5 "/>
<text text-anchor="middle" x="1993.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="1893.5,-305.5 2093.5,-305.5 "/>
<text text-anchor="middle" x="1993.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="1893.5,-282.5 2093.5,-282.5 "/>
<text text-anchor="middle" x="1993.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="2093.5,-259.5 2093.5,-443.5 "/>
<text text-anchor="middle" x="2104" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge2" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1816.7617,-259.4393C1795.4799,-246.6136 1772.9523,-234.8265 1750.5,-226 1657.3694,-189.388 1409.6876,-152.8748 1225.9572,-129.4716"/>
<polygon fill="#000000" stroke="#000000" points="1226.2434,-125.9799 1215.8823,-128.1932 1225.3622,-132.9242 1226.2434,-125.9799"/>
<text text-anchor="middle" x="1835" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
</g>
</svg>
</div>
