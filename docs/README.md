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
<svg width="2937pt" height="1574pt"
 viewBox="0.00 0.00 2936.50 1574.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1570)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1570 2932.5,-1570 2932.5,4 -4,4"/>
<!-- study -->
<g id="node1" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M1477.5,-.5C1477.5,-.5 1867.5,-.5 1867.5,-.5 1873.5,-.5 1879.5,-6.5 1879.5,-12.5 1879.5,-12.5 1879.5,-195.5 1879.5,-195.5 1879.5,-201.5 1873.5,-207.5 1867.5,-207.5 1867.5,-207.5 1477.5,-207.5 1477.5,-207.5 1471.5,-207.5 1465.5,-201.5 1465.5,-195.5 1465.5,-195.5 1465.5,-12.5 1465.5,-12.5 1465.5,-6.5 1471.5,-.5 1477.5,-.5"/>
<text text-anchor="middle" x="1493.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="1521.5,-.5 1521.5,-207.5 "/>
<text text-anchor="middle" x="1532" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1542.5,-.5 1542.5,-207.5 "/>
<text text-anchor="middle" x="1700.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="1542.5,-184.5 1858.5,-184.5 "/>
<text text-anchor="middle" x="1700.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="1542.5,-161.5 1858.5,-161.5 "/>
<text text-anchor="middle" x="1700.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="1542.5,-138.5 1858.5,-138.5 "/>
<text text-anchor="middle" x="1700.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="1542.5,-115.5 1858.5,-115.5 "/>
<text text-anchor="middle" x="1700.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="1542.5,-92.5 1858.5,-92.5 "/>
<text text-anchor="middle" x="1700.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="1542.5,-69.5 1858.5,-69.5 "/>
<text text-anchor="middle" x="1700.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="1542.5,-46.5 1858.5,-46.5 "/>
<text text-anchor="middle" x="1700.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="1542.5,-23.5 1858.5,-23.5 "/>
<text text-anchor="middle" x="1700.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="1858.5,-.5 1858.5,-207.5 "/>
<text text-anchor="middle" x="1869" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node2" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M1557,-495.5C1557,-495.5 1788,-495.5 1788,-495.5 1794,-495.5 1800,-501.5 1800,-507.5 1800,-507.5 1800,-575.5 1800,-575.5 1800,-581.5 1794,-587.5 1788,-587.5 1788,-587.5 1557,-587.5 1557,-587.5 1551,-587.5 1545,-581.5 1545,-575.5 1545,-575.5 1545,-507.5 1545,-507.5 1545,-501.5 1551,-495.5 1557,-495.5"/>
<text text-anchor="middle" x="1593" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1641,-495.5 1641,-587.5 "/>
<text text-anchor="middle" x="1651.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1662,-495.5 1662,-587.5 "/>
<text text-anchor="middle" x="1720.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="1662,-564.5 1779,-564.5 "/>
<text text-anchor="middle" x="1720.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="1662,-541.5 1779,-541.5 "/>
<text text-anchor="middle" x="1720.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1662,-518.5 1779,-518.5 "/>
<text text-anchor="middle" x="1720.5" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1779,-495.5 1779,-587.5 "/>
<text text-anchor="middle" x="1789.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge11" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1672.5,-495.094C1672.5,-429.596 1672.5,-307.9591 1672.5,-217.6598"/>
<polygon fill="#000000" stroke="#000000" points="1676.0001,-217.6413 1672.5,-207.6413 1669.0001,-217.6414 1676.0001,-217.6413"/>
<text text-anchor="middle" x="1723" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_arm -->
<g id="node5" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M1327,-317C1327,-317 1624,-317 1624,-317 1630,-317 1636,-323 1636,-329 1636,-329 1636,-374 1636,-374 1636,-380 1630,-386 1624,-386 1624,-386 1327,-386 1327,-386 1321,-386 1315,-380 1315,-374 1315,-374 1315,-329 1315,-329 1315,-323 1321,-317 1327,-317"/>
<text text-anchor="middle" x="1361" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="1407,-317 1407,-386 "/>
<text text-anchor="middle" x="1417.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1428,-317 1428,-386 "/>
<text text-anchor="middle" x="1521.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="1428,-363 1615,-363 "/>
<text text-anchor="middle" x="1521.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="1428,-340 1615,-340 "/>
<text text-anchor="middle" x="1521.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="1615,-317 1615,-386 "/>
<text text-anchor="middle" x="1625.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge10" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1580.4959,-495.4008C1572.339,-489.7115 1564.5242,-483.5647 1557.5,-477 1532.4958,-453.6315 1511.5437,-421.1575 1497.078,-395.0977"/>
<polygon fill="#000000" stroke="#000000" points="1500.0811,-393.2936 1492.2358,-386.1731 1493.9284,-396.6318 1500.0811,-393.2936"/>
<text text-anchor="middle" x="1608" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_personnel -->
<g id="node3" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M939,-294C939,-294 1246,-294 1246,-294 1252,-294 1258,-300 1258,-306 1258,-306 1258,-397 1258,-397 1258,-403 1252,-409 1246,-409 1246,-409 939,-409 939,-409 933,-409 927,-403 927,-397 927,-397 927,-306 927,-306 927,-300 933,-294 939,-294"/>
<text text-anchor="middle" x="994" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="1061,-294 1061,-409 "/>
<text text-anchor="middle" x="1071.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1082,-294 1082,-409 "/>
<text text-anchor="middle" x="1159.5" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="1082,-386 1237,-386 "/>
<text text-anchor="middle" x="1159.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="1082,-363 1237,-363 "/>
<text text-anchor="middle" x="1159.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="1082,-340 1237,-340 "/>
<text text-anchor="middle" x="1159.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="1082,-317 1237,-317 "/>
<text text-anchor="middle" x="1159.5" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="1237,-294 1237,-409 "/>
<text text-anchor="middle" x="1247.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge13" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1098.7357,-293.7767C1104.2105,-269.7042 1114.4368,-243.365 1133.5,-226 1181.1544,-182.5907 1327.2863,-151.1391 1455.3843,-131.0521"/>
<polygon fill="#000000" stroke="#000000" points="1456.0119,-134.4967 1465.3572,-129.5053 1454.9389,-127.5794 1456.0119,-134.4967"/>
<text text-anchor="middle" x="1203" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- sample_diagnosis -->
<g id="node4" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M899.5,-1059.5C899.5,-1059.5 1341.5,-1059.5 1341.5,-1059.5 1347.5,-1059.5 1353.5,-1065.5 1353.5,-1071.5 1353.5,-1071.5 1353.5,-1484.5 1353.5,-1484.5 1353.5,-1490.5 1347.5,-1496.5 1341.5,-1496.5 1341.5,-1496.5 899.5,-1496.5 899.5,-1496.5 893.5,-1496.5 887.5,-1490.5 887.5,-1484.5 887.5,-1484.5 887.5,-1071.5 887.5,-1071.5 887.5,-1065.5 893.5,-1059.5 899.5,-1059.5"/>
<text text-anchor="middle" x="959" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1030.5,-1059.5 1030.5,-1496.5 "/>
<text text-anchor="middle" x="1041" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1051.5,-1059.5 1051.5,-1496.5 "/>
<text text-anchor="middle" x="1192" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1051.5,-1473.5 1332.5,-1473.5 "/>
<text text-anchor="middle" x="1192" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1051.5,-1450.5 1332.5,-1450.5 "/>
<text text-anchor="middle" x="1192" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1051.5,-1427.5 1332.5,-1427.5 "/>
<text text-anchor="middle" x="1192" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1051.5,-1404.5 1332.5,-1404.5 "/>
<text text-anchor="middle" x="1192" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="1051.5,-1381.5 1332.5,-1381.5 "/>
<text text-anchor="middle" x="1192" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1051.5,-1358.5 1332.5,-1358.5 "/>
<text text-anchor="middle" x="1192" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1051.5,-1335.5 1332.5,-1335.5 "/>
<text text-anchor="middle" x="1192" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis_reference_source</text>
<polyline fill="none" stroke="#000000" points="1051.5,-1312.5 1332.5,-1312.5 "/>
<text text-anchor="middle" x="1192" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="1051.5,-1289.5 1332.5,-1289.5 "/>
<text text-anchor="middle" x="1192" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="1051.5,-1266.5 1332.5,-1266.5 "/>
<text text-anchor="middle" x="1192" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1051.5,-1243.5 1332.5,-1243.5 "/>
<text text-anchor="middle" x="1192" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="1051.5,-1220.5 1332.5,-1220.5 "/>
<text text-anchor="middle" x="1192" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="1051.5,-1197.5 1332.5,-1197.5 "/>
<text text-anchor="middle" x="1192" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1051.5,-1174.5 1332.5,-1174.5 "/>
<text text-anchor="middle" x="1192" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="1051.5,-1151.5 1332.5,-1151.5 "/>
<text text-anchor="middle" x="1192" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="1051.5,-1128.5 1332.5,-1128.5 "/>
<text text-anchor="middle" x="1192" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1051.5,-1105.5 1332.5,-1105.5 "/>
<text text-anchor="middle" x="1192" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1051.5,-1082.5 1332.5,-1082.5 "/>
<text text-anchor="middle" x="1192" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1332.5,-1059.5 1332.5,-1496.5 "/>
<text text-anchor="middle" x="1343" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node16" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M748.5,-720C748.5,-720 1062.5,-720 1062.5,-720 1068.5,-720 1074.5,-726 1074.5,-732 1074.5,-732 1074.5,-846 1074.5,-846 1074.5,-852 1068.5,-858 1062.5,-858 1062.5,-858 748.5,-858 748.5,-858 742.5,-858 736.5,-852 736.5,-846 736.5,-846 736.5,-732 736.5,-732 736.5,-726 742.5,-720 748.5,-720"/>
<text text-anchor="middle" x="770.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="804.5,-720 804.5,-858 "/>
<text text-anchor="middle" x="815" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="825.5,-720 825.5,-858 "/>
<text text-anchor="middle" x="939.5" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="825.5,-835 1053.5,-835 "/>
<text text-anchor="middle" x="939.5" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="825.5,-812 1053.5,-812 "/>
<text text-anchor="middle" x="939.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="825.5,-789 1053.5,-789 "/>
<text text-anchor="middle" x="939.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="825.5,-766 1053.5,-766 "/>
<text text-anchor="middle" x="939.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="825.5,-743 1053.5,-743 "/>
<text text-anchor="middle" x="939.5" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="1053.5,-720 1053.5,-858 "/>
<text text-anchor="middle" x="1064" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1024.3192,-1059.2446C994.2065,-990.7557 962.8958,-919.542 939.9799,-867.4218"/>
<polygon fill="#000000" stroke="#000000" points="943.174,-865.9905 935.9451,-858.2449 936.7661,-868.8079 943.174,-865.9905"/>
<text text-anchor="middle" x="1055.5" y="-960.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge12" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1497.4503,-316.7713C1514.141,-291.0564 1538.1419,-255.5137 1561.5,-226 1564.2739,-222.4951 1567.1222,-218.964 1570.0255,-215.423"/>
<polygon fill="#000000" stroke="#000000" points="1572.7727,-217.5933 1576.4619,-207.6614 1567.3843,-213.1249 1572.7727,-217.5933"/>
<text text-anchor="middle" x="1610" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- synonym -->
<g id="node6" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M2178,-1255C2178,-1255 2479,-1255 2479,-1255 2485,-1255 2491,-1261 2491,-1267 2491,-1267 2491,-1289 2491,-1289 2491,-1295 2485,-1301 2479,-1301 2479,-1301 2178,-1301 2178,-1301 2172,-1301 2166,-1295 2166,-1289 2166,-1289 2166,-1267 2166,-1267 2166,-1261 2172,-1255 2178,-1255"/>
<text text-anchor="middle" x="2206" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="2246,-1255 2246,-1301 "/>
<text text-anchor="middle" x="2256.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2267,-1255 2267,-1301 "/>
<text text-anchor="middle" x="2368.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="2267,-1278 2470,-1278 "/>
<text text-anchor="middle" x="2368.5" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="2470,-1255 2470,-1301 "/>
<text text-anchor="middle" x="2480.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge3" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2388.0802,-1254.9395C2523.6441,-1198.1332 2843.5,-1037.7456 2843.5,-789 2843.5,-789 2843.5,-789 2843.5,-351.5 2843.5,-309.5306 2854.7624,-288.0795 2824.5,-259 2759.2231,-196.2745 2713.0772,-239.095 2623.5,-226 2372.163,-189.2579 2082.558,-152.9702 1889.61,-129.6501"/>
<polygon fill="#000000" stroke="#000000" points="1889.9815,-126.1696 1879.634,-128.4455 1889.1423,-133.1192 1889.9815,-126.1696"/>
<text text-anchor="middle" x="2886" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2336.6049,-1254.7612C2367.0162,-1162.9067 2464.519,-821.3002 2301.5,-639 2269.1642,-602.8397 1985.2652,-570.4141 1810.112,-553.6121"/>
<polygon fill="#000000" stroke="#000000" points="1810.3242,-550.1165 1800.0371,-552.6513 1809.6596,-557.0849 1810.3242,-550.1165"/>
<text text-anchor="middle" x="2435" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2294.5157,-1254.9499C2210.2154,-1199.0313 1982.9966,-1055.9355 1771.5,-990 1661.138,-955.5939 1628.6881,-966.7597 1513.5,-957 1465.8511,-952.9628 1128.0656,-956.3386 1083.5,-939 1042.7041,-923.1281 1004.5635,-893.8324 974.135,-865.3146"/>
<polygon fill="#000000" stroke="#000000" points="976.2178,-862.4641 966.5682,-858.0897 971.3838,-867.5269 976.2178,-862.4641"/>
<text text-anchor="middle" x="1741" y="-960.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- methylation_array_file -->
<g id="node7" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M1384,-1163C1384,-1163 1751,-1163 1751,-1163 1757,-1163 1763,-1169 1763,-1175 1763,-1175 1763,-1381 1763,-1381 1763,-1387 1757,-1393 1751,-1393 1751,-1393 1384,-1393 1384,-1393 1378,-1393 1372,-1387 1372,-1381 1372,-1381 1372,-1175 1372,-1175 1372,-1169 1378,-1163 1384,-1163"/>
<text text-anchor="middle" x="1461" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="1550,-1163 1550,-1393 "/>
<text text-anchor="middle" x="1560.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1571,-1163 1571,-1393 "/>
<text text-anchor="middle" x="1656.5" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1571,-1370 1742,-1370 "/>
<text text-anchor="middle" x="1656.5" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1571,-1347 1742,-1347 "/>
<text text-anchor="middle" x="1656.5" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1571,-1324 1742,-1324 "/>
<text text-anchor="middle" x="1656.5" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1571,-1301 1742,-1301 "/>
<text text-anchor="middle" x="1656.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1571,-1278 1742,-1278 "/>
<text text-anchor="middle" x="1656.5" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1571,-1255 1742,-1255 "/>
<text text-anchor="middle" x="1656.5" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1571,-1232 1742,-1232 "/>
<text text-anchor="middle" x="1656.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1571,-1209 1742,-1209 "/>
<text text-anchor="middle" x="1656.5" y="-1193.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="1571,-1186 1742,-1186 "/>
<text text-anchor="middle" x="1656.5" y="-1170.8" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="1742,-1163 1742,-1393 "/>
<text text-anchor="middle" x="1752.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1513.0768,-1162.7316C1478.4307,-1101.9175 1427.7502,-1031.5014 1362.5,-990 1256.1367,-922.3492 1197.5203,-992.7509 1083.5,-939 1045.0839,-920.8901 1008.2111,-892.3699 978.0886,-865.0388"/>
<polygon fill="#000000" stroke="#000000" points="980.3058,-862.3227 970.5789,-858.1229 975.5638,-867.4718 980.3058,-862.3227"/>
<text text-anchor="middle" x="1418" y="-960.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node8" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M1104.5,-662.5C1104.5,-662.5 1456.5,-662.5 1456.5,-662.5 1462.5,-662.5 1468.5,-668.5 1468.5,-674.5 1468.5,-674.5 1468.5,-903.5 1468.5,-903.5 1468.5,-909.5 1462.5,-915.5 1456.5,-915.5 1456.5,-915.5 1104.5,-915.5 1104.5,-915.5 1098.5,-915.5 1092.5,-909.5 1092.5,-903.5 1092.5,-903.5 1092.5,-674.5 1092.5,-674.5 1092.5,-668.5 1098.5,-662.5 1104.5,-662.5"/>
<text text-anchor="middle" x="1176" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="1259.5,-662.5 1259.5,-915.5 "/>
<text text-anchor="middle" x="1270" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1280.5,-662.5 1280.5,-915.5 "/>
<text text-anchor="middle" x="1364" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1280.5,-892.5 1447.5,-892.5 "/>
<text text-anchor="middle" x="1364" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1280.5,-869.5 1447.5,-869.5 "/>
<text text-anchor="middle" x="1364" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1280.5,-846.5 1447.5,-846.5 "/>
<text text-anchor="middle" x="1364" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1280.5,-823.5 1447.5,-823.5 "/>
<text text-anchor="middle" x="1364" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1280.5,-800.5 1447.5,-800.5 "/>
<text text-anchor="middle" x="1364" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1280.5,-777.5 1447.5,-777.5 "/>
<text text-anchor="middle" x="1364" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1280.5,-754.5 1447.5,-754.5 "/>
<text text-anchor="middle" x="1364" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1280.5,-731.5 1447.5,-731.5 "/>
<text text-anchor="middle" x="1364" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1280.5,-708.5 1447.5,-708.5 "/>
<text text-anchor="middle" x="1364" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1280.5,-685.5 1447.5,-685.5 "/>
<text text-anchor="middle" x="1364" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="1447.5,-662.5 1447.5,-915.5 "/>
<text text-anchor="middle" x="1458" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge15" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1271.4087,-662.4043C1264.2365,-526.5542 1261.6876,-321.7987 1305.5,-259 1341.3006,-207.6851 1397.6277,-173.2816 1455.5037,-150.2452"/>
<polygon fill="#000000" stroke="#000000" points="1457.1165,-153.3741 1465.1807,-146.5026 1454.5915,-146.8454 1457.1165,-153.3741"/>
<text text-anchor="middle" x="1354.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1355.2055,-662.0464C1372.4068,-640.8537 1392.278,-620.9391 1414.5,-606 1435.2449,-592.0539 1484.5986,-578.366 1534.6482,-567.2129"/>
<polygon fill="#000000" stroke="#000000" points="1535.6414,-570.5784 1544.6591,-565.0168 1534.1414,-563.741 1535.6414,-570.5784"/>
<text text-anchor="middle" x="1544" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- therapeutic_procedure -->
<g id="node9" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M1924,-731.5C1924,-731.5 2281,-731.5 2281,-731.5 2287,-731.5 2293,-737.5 2293,-743.5 2293,-743.5 2293,-834.5 2293,-834.5 2293,-840.5 2287,-846.5 2281,-846.5 2281,-846.5 1924,-846.5 1924,-846.5 1918,-846.5 1912,-840.5 1912,-834.5 1912,-834.5 1912,-743.5 1912,-743.5 1912,-737.5 1918,-731.5 1924,-731.5"/>
<text text-anchor="middle" x="2002.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="2093,-731.5 2093,-846.5 "/>
<text text-anchor="middle" x="2103.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2114,-731.5 2114,-846.5 "/>
<text text-anchor="middle" x="2193" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="2114,-823.5 2272,-823.5 "/>
<text text-anchor="middle" x="2193" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="2114,-800.5 2272,-800.5 "/>
<text text-anchor="middle" x="2193" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="2114,-777.5 2272,-777.5 "/>
<text text-anchor="middle" x="2193" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="2114,-754.5 2272,-754.5 "/>
<text text-anchor="middle" x="2193" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="2272,-731.5 2272,-846.5 "/>
<text text-anchor="middle" x="2282.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2034.11,-731.1704C1996.7472,-701.2969 1948.7697,-665.6292 1902.5,-639 1872.2221,-621.5745 1838.2276,-605.462 1805.8527,-591.5615"/>
<polygon fill="#000000" stroke="#000000" points="1806.8902,-588.1996 1796.3178,-587.5106 1804.153,-594.6422 1806.8902,-588.1996"/>
<text text-anchor="middle" x="1960.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- sequencing_file -->
<g id="node10" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M12,-990.5C12,-990.5 481,-990.5 481,-990.5 487,-990.5 493,-996.5 493,-1002.5 493,-1002.5 493,-1553.5 493,-1553.5 493,-1559.5 487,-1565.5 481,-1565.5 481,-1565.5 12,-1565.5 12,-1565.5 6,-1565.5 0,-1559.5 0,-1553.5 0,-1553.5 0,-1002.5 0,-1002.5 0,-996.5 6,-990.5 12,-990.5"/>
<text text-anchor="middle" x="64" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="128,-990.5 128,-1565.5 "/>
<text text-anchor="middle" x="138.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="149,-990.5 149,-1565.5 "/>
<text text-anchor="middle" x="310.5" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="149,-1542.5 472,-1542.5 "/>
<text text-anchor="middle" x="310.5" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="149,-1519.5 472,-1519.5 "/>
<text text-anchor="middle" x="310.5" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="149,-1496.5 472,-1496.5 "/>
<text text-anchor="middle" x="310.5" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="149,-1473.5 472,-1473.5 "/>
<text text-anchor="middle" x="310.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="149,-1450.5 472,-1450.5 "/>
<text text-anchor="middle" x="310.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="149,-1427.5 472,-1427.5 "/>
<text text-anchor="middle" x="310.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="149,-1404.5 472,-1404.5 "/>
<text text-anchor="middle" x="310.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="149,-1381.5 472,-1381.5 "/>
<text text-anchor="middle" x="310.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="149,-1358.5 472,-1358.5 "/>
<text text-anchor="middle" x="310.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="149,-1335.5 472,-1335.5 "/>
<text text-anchor="middle" x="310.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="149,-1312.5 472,-1312.5 "/>
<text text-anchor="middle" x="310.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="149,-1289.5 472,-1289.5 "/>
<text text-anchor="middle" x="310.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="149,-1266.5 472,-1266.5 "/>
<text text-anchor="middle" x="310.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="149,-1243.5 472,-1243.5 "/>
<text text-anchor="middle" x="310.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="149,-1220.5 472,-1220.5 "/>
<text text-anchor="middle" x="310.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="149,-1197.5 472,-1197.5 "/>
<text text-anchor="middle" x="310.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="149,-1174.5 472,-1174.5 "/>
<text text-anchor="middle" x="310.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="149,-1151.5 472,-1151.5 "/>
<text text-anchor="middle" x="310.5" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="149,-1128.5 472,-1128.5 "/>
<text text-anchor="middle" x="310.5" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="149,-1105.5 472,-1105.5 "/>
<text text-anchor="middle" x="310.5" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="149,-1082.5 472,-1082.5 "/>
<text text-anchor="middle" x="310.5" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="149,-1059.5 472,-1059.5 "/>
<text text-anchor="middle" x="310.5" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="149,-1036.5 472,-1036.5 "/>
<text text-anchor="middle" x="310.5" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="149,-1013.5 472,-1013.5 "/>
<text text-anchor="middle" x="310.5" y="-998.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="472,-990.5 472,-1565.5 "/>
<text text-anchor="middle" x="482.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M493.3625,-997.1328C496.3995,-994.7169 499.4457,-992.3383 502.5,-990 570.3687,-938.0404 653.7661,-893.8029 727.0519,-860.168"/>
<polygon fill="#000000" stroke="#000000" points="728.7483,-863.2414 736.3977,-855.9108 725.8465,-856.8712 728.7483,-863.2414"/>
<text text-anchor="middle" x="609" y="-960.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- study_admin -->
<g id="node11" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M1803.5,-259.5C1803.5,-259.5 2129.5,-259.5 2129.5,-259.5 2135.5,-259.5 2141.5,-265.5 2141.5,-271.5 2141.5,-271.5 2141.5,-431.5 2141.5,-431.5 2141.5,-437.5 2135.5,-443.5 2129.5,-443.5 2129.5,-443.5 1803.5,-443.5 1803.5,-443.5 1797.5,-443.5 1791.5,-437.5 1791.5,-431.5 1791.5,-431.5 1791.5,-271.5 1791.5,-271.5 1791.5,-265.5 1797.5,-259.5 1803.5,-259.5"/>
<text text-anchor="middle" x="1845.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="1899.5,-259.5 1899.5,-443.5 "/>
<text text-anchor="middle" x="1910" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1920.5,-259.5 1920.5,-443.5 "/>
<text text-anchor="middle" x="2020.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="1920.5,-420.5 2120.5,-420.5 "/>
<text text-anchor="middle" x="2020.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="1920.5,-397.5 2120.5,-397.5 "/>
<text text-anchor="middle" x="2020.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="1920.5,-374.5 2120.5,-374.5 "/>
<text text-anchor="middle" x="2020.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="1920.5,-351.5 2120.5,-351.5 "/>
<text text-anchor="middle" x="2020.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="1920.5,-328.5 2120.5,-328.5 "/>
<text text-anchor="middle" x="2020.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="1920.5,-305.5 2120.5,-305.5 "/>
<text text-anchor="middle" x="2020.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="1920.5,-282.5 2120.5,-282.5 "/>
<text text-anchor="middle" x="2020.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="2120.5,-259.5 2120.5,-443.5 "/>
<text text-anchor="middle" x="2131" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge2" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1857.0253,-259.3401C1839.753,-244.7997 1821.74,-229.6357 1804.0299,-214.7267"/>
<polygon fill="#000000" stroke="#000000" points="1805.8221,-211.6604 1795.9179,-207.8977 1801.314,-217.0155 1805.8221,-211.6604"/>
<text text-anchor="middle" x="1885" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- study_funding -->
<g id="node12" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M2172,-317C2172,-317 2551,-317 2551,-317 2557,-317 2563,-323 2563,-329 2563,-329 2563,-374 2563,-374 2563,-380 2557,-386 2551,-386 2551,-386 2172,-386 2172,-386 2166,-386 2160,-380 2160,-374 2160,-374 2160,-329 2160,-329 2160,-323 2166,-317 2172,-317"/>
<text text-anchor="middle" x="2219.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="2279,-317 2279,-386 "/>
<text text-anchor="middle" x="2289.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2300,-317 2300,-386 "/>
<text text-anchor="middle" x="2421" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="2300,-363 2542,-363 "/>
<text text-anchor="middle" x="2421" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="2300,-340 2542,-340 "/>
<text text-anchor="middle" x="2421" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="2542,-317 2542,-386 "/>
<text text-anchor="middle" x="2552.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge18" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2287.5451,-316.9216C2247.4009,-298.7014 2196.6715,-276.5566 2150.5,-259 2066.0809,-226.8999 1971.7685,-195.4138 1889.3702,-169.2948"/>
<polygon fill="#000000" stroke="#000000" points="1890.2301,-165.896 1879.6401,-166.2179 1888.1194,-172.5702 1890.2301,-165.896"/>
<text text-anchor="middle" x="2160.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- diagnosis -->
<g id="node13" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1499,-639.5C1499,-639.5 1882,-639.5 1882,-639.5 1888,-639.5 1894,-645.5 1894,-651.5 1894,-651.5 1894,-926.5 1894,-926.5 1894,-932.5 1888,-938.5 1882,-938.5 1882,-938.5 1499,-938.5 1499,-938.5 1493,-938.5 1487,-932.5 1487,-926.5 1487,-926.5 1487,-651.5 1487,-651.5 1487,-645.5 1493,-639.5 1499,-639.5"/>
<text text-anchor="middle" x="1529" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1571,-639.5 1571,-938.5 "/>
<text text-anchor="middle" x="1581.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1592,-639.5 1592,-938.5 "/>
<text text-anchor="middle" x="1732.5" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1592,-915.5 1873,-915.5 "/>
<text text-anchor="middle" x="1732.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1592,-892.5 1873,-892.5 "/>
<text text-anchor="middle" x="1732.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1592,-869.5 1873,-869.5 "/>
<text text-anchor="middle" x="1732.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1592,-846.5 1873,-846.5 "/>
<text text-anchor="middle" x="1732.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1592,-823.5 1873,-823.5 "/>
<text text-anchor="middle" x="1732.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="1592,-800.5 1873,-800.5 "/>
<text text-anchor="middle" x="1732.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1592,-777.5 1873,-777.5 "/>
<text text-anchor="middle" x="1732.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1592,-754.5 1873,-754.5 "/>
<text text-anchor="middle" x="1732.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis_reference_source</text>
<polyline fill="none" stroke="#000000" points="1592,-731.5 1873,-731.5 "/>
<text text-anchor="middle" x="1732.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="1592,-708.5 1873,-708.5 "/>
<text text-anchor="middle" x="1732.5" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="1592,-685.5 1873,-685.5 "/>
<text text-anchor="middle" x="1732.5" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="1592,-662.5 1873,-662.5 "/>
<text text-anchor="middle" x="1732.5" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="1873,-639.5 1873,-938.5 "/>
<text text-anchor="middle" x="1883.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1679.6141,-639.3186C1678.5556,-624.7641 1677.5335,-610.7108 1676.6101,-598.0135"/>
<polygon fill="#000000" stroke="#000000" points="1680.0752,-597.4053 1675.8589,-587.6855 1673.0936,-597.9131 1680.0752,-597.4053"/>
<text text-anchor="middle" x="1723" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- imaging_file -->
<g id="node14" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M523.5,-1117C523.5,-1117 857.5,-1117 857.5,-1117 863.5,-1117 869.5,-1123 869.5,-1129 869.5,-1129 869.5,-1427 869.5,-1427 869.5,-1433 863.5,-1439 857.5,-1439 857.5,-1439 523.5,-1439 523.5,-1439 517.5,-1439 511.5,-1433 511.5,-1427 511.5,-1427 511.5,-1129 511.5,-1129 511.5,-1123 517.5,-1117 523.5,-1117"/>
<text text-anchor="middle" x="563.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="615.5,-1117 615.5,-1439 "/>
<text text-anchor="middle" x="626" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="636.5,-1117 636.5,-1439 "/>
<text text-anchor="middle" x="742.5" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="636.5,-1416 848.5,-1416 "/>
<text text-anchor="middle" x="742.5" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="636.5,-1393 848.5,-1393 "/>
<text text-anchor="middle" x="742.5" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="636.5,-1370 848.5,-1370 "/>
<text text-anchor="middle" x="742.5" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="636.5,-1347 848.5,-1347 "/>
<text text-anchor="middle" x="742.5" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="636.5,-1324 848.5,-1324 "/>
<text text-anchor="middle" x="742.5" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="636.5,-1301 848.5,-1301 "/>
<text text-anchor="middle" x="742.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="636.5,-1278 848.5,-1278 "/>
<text text-anchor="middle" x="742.5" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="636.5,-1255 848.5,-1255 "/>
<text text-anchor="middle" x="742.5" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="636.5,-1232 848.5,-1232 "/>
<text text-anchor="middle" x="742.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="636.5,-1209 848.5,-1209 "/>
<text text-anchor="middle" x="742.5" y="-1193.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="636.5,-1186 848.5,-1186 "/>
<text text-anchor="middle" x="742.5" y="-1170.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="636.5,-1163 848.5,-1163 "/>
<text text-anchor="middle" x="742.5" y="-1147.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="636.5,-1140 848.5,-1140 "/>
<text text-anchor="middle" x="742.5" y="-1124.8" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="848.5,-1117 848.5,-1439 "/>
<text text-anchor="middle" x="859" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M761.3458,-1116.8669C798.214,-1033.0132 841.6164,-934.298 871.092,-867.2583"/>
<polygon fill="#000000" stroke="#000000" points="874.3356,-868.5767 875.1565,-858.0138 867.9276,-865.7593 874.3356,-868.5767"/>
<text text-anchor="middle" x="885" y="-960.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- publication -->
<g id="node15" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M2593.5,-333.5C2593.5,-333.5 2803.5,-333.5 2803.5,-333.5 2809.5,-333.5 2815.5,-339.5 2815.5,-345.5 2815.5,-345.5 2815.5,-357.5 2815.5,-357.5 2815.5,-363.5 2809.5,-369.5 2803.5,-369.5 2803.5,-369.5 2593.5,-369.5 2593.5,-369.5 2587.5,-369.5 2581.5,-363.5 2581.5,-357.5 2581.5,-357.5 2581.5,-345.5 2581.5,-345.5 2581.5,-339.5 2587.5,-333.5 2593.5,-333.5"/>
<text text-anchor="middle" x="2630" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="2678.5,-333.5 2678.5,-369.5 "/>
<text text-anchor="middle" x="2689" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2699.5,-333.5 2699.5,-369.5 "/>
<text text-anchor="middle" x="2747" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="2794.5,-333.5 2794.5,-369.5 "/>
<text text-anchor="middle" x="2805" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge14" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2679.7692,-333.3064C2656.5889,-311.9151 2614.9566,-277.0459 2572.5,-259 2452.5344,-208.0095 2115.376,-158.5756 1889.5264,-129.7352"/>
<polygon fill="#000000" stroke="#000000" points="1889.8906,-126.2534 1879.5287,-128.4627 1889.0067,-133.1974 1889.8906,-126.2534"/>
<text text-anchor="middle" x="2568.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge9" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M882.7104,-719.9269C850.8314,-608.885 808.2525,-389.9009 917.5,-259 985.2685,-177.7994 1257.2332,-137.7789 1455.3687,-119.0435"/>
<polygon fill="#000000" stroke="#000000" points="1455.7076,-122.5272 1465.3389,-118.1128 1455.0568,-115.5575 1455.7076,-122.5272"/>
<text text-anchor="middle" x="885" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M970.0162,-719.941C1001.4418,-690.4305 1041.4817,-658.3795 1083.5,-639 1161.7052,-602.9304 1386.5768,-572.6041 1534.7437,-555.7639"/>
<polygon fill="#000000" stroke="#000000" points="1535.2888,-559.2247 1544.8329,-554.6246 1534.5032,-552.2689 1535.2888,-559.2247"/>
<text text-anchor="middle" x="1228" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
</g>
</svg>
</div>
