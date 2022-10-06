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
<svg width="2569pt" height="1574pt"
 viewBox="0.00 0.00 2569.12 1574.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1570)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1570 2565.1239,-1570 2565.1239,4 -4,4"/>
<!-- study_arm -->
<g id="node1" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M822.6239,-317C822.6239,-317 1119.6239,-317 1119.6239,-317 1125.6239,-317 1131.6239,-323 1131.6239,-329 1131.6239,-329 1131.6239,-374 1131.6239,-374 1131.6239,-380 1125.6239,-386 1119.6239,-386 1119.6239,-386 822.6239,-386 822.6239,-386 816.6239,-386 810.6239,-380 810.6239,-374 810.6239,-374 810.6239,-329 810.6239,-329 810.6239,-323 816.6239,-317 822.6239,-317"/>
<text text-anchor="middle" x="856.6239" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="902.6239,-317 902.6239,-386 "/>
<text text-anchor="middle" x="913.1239" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="923.6239,-317 923.6239,-386 "/>
<text text-anchor="middle" x="1017.1239" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="923.6239,-363 1110.6239,-363 "/>
<text text-anchor="middle" x="1017.1239" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="923.6239,-340 1110.6239,-340 "/>
<text text-anchor="middle" x="1017.1239" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="1110.6239,-317 1110.6239,-386 "/>
<text text-anchor="middle" x="1121.1239" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node3" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M965.1239,-.5C965.1239,-.5 1355.1239,-.5 1355.1239,-.5 1361.1239,-.5 1367.1239,-6.5 1367.1239,-12.5 1367.1239,-12.5 1367.1239,-195.5 1367.1239,-195.5 1367.1239,-201.5 1361.1239,-207.5 1355.1239,-207.5 1355.1239,-207.5 965.1239,-207.5 965.1239,-207.5 959.1239,-207.5 953.1239,-201.5 953.1239,-195.5 953.1239,-195.5 953.1239,-12.5 953.1239,-12.5 953.1239,-6.5 959.1239,-.5 965.1239,-.5"/>
<text text-anchor="middle" x="981.1239" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="1009.1239,-.5 1009.1239,-207.5 "/>
<text text-anchor="middle" x="1019.6239" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1030.1239,-.5 1030.1239,-207.5 "/>
<text text-anchor="middle" x="1188.1239" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="1030.1239,-184.5 1346.1239,-184.5 "/>
<text text-anchor="middle" x="1188.1239" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="1030.1239,-161.5 1346.1239,-161.5 "/>
<text text-anchor="middle" x="1188.1239" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="1030.1239,-138.5 1346.1239,-138.5 "/>
<text text-anchor="middle" x="1188.1239" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="1030.1239,-115.5 1346.1239,-115.5 "/>
<text text-anchor="middle" x="1188.1239" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="1030.1239,-92.5 1346.1239,-92.5 "/>
<text text-anchor="middle" x="1188.1239" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="1030.1239,-69.5 1346.1239,-69.5 "/>
<text text-anchor="middle" x="1188.1239" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="1030.1239,-46.5 1346.1239,-46.5 "/>
<text text-anchor="middle" x="1188.1239" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="1030.1239,-23.5 1346.1239,-23.5 "/>
<text text-anchor="middle" x="1188.1239" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="1346.1239,-.5 1346.1239,-207.5 "/>
<text text-anchor="middle" x="1356.6239" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge12" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M990.3715,-316.8369C1005.2599,-290.9966 1027.0061,-255.267 1049.1239,-226 1051.6974,-222.5946 1054.3476,-219.1722 1057.0568,-215.7462"/>
<polygon fill="#000000" stroke="#000000" points="1059.9439,-217.7407 1063.4769,-207.7523 1054.4862,-213.3574 1059.9439,-217.7407"/>
<text text-anchor="middle" x="1097.6239" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- synonym -->
<g id="node2" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M293.6239,-1243.5C293.6239,-1243.5 594.6239,-1243.5 594.6239,-1243.5 600.6239,-1243.5 606.6239,-1249.5 606.6239,-1255.5 606.6239,-1255.5 606.6239,-1323.5 606.6239,-1323.5 606.6239,-1329.5 600.6239,-1335.5 594.6239,-1335.5 594.6239,-1335.5 293.6239,-1335.5 293.6239,-1335.5 287.6239,-1335.5 281.6239,-1329.5 281.6239,-1323.5 281.6239,-1323.5 281.6239,-1255.5 281.6239,-1255.5 281.6239,-1249.5 287.6239,-1243.5 293.6239,-1243.5"/>
<text text-anchor="middle" x="321.6239" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="361.6239,-1243.5 361.6239,-1335.5 "/>
<text text-anchor="middle" x="372.1239" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="382.6239,-1243.5 382.6239,-1335.5 "/>
<text text-anchor="middle" x="484.1239" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_id</text>
<polyline fill="none" stroke="#000000" points="382.6239,-1312.5 585.6239,-1312.5 "/>
<text text-anchor="middle" x="484.1239" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_node</text>
<polyline fill="none" stroke="#000000" points="382.6239,-1289.5 585.6239,-1289.5 "/>
<text text-anchor="middle" x="484.1239" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="382.6239,-1266.5 585.6239,-1266.5 "/>
<text text-anchor="middle" x="484.1239" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="585.6239,-1243.5 585.6239,-1335.5 "/>
<text text-anchor="middle" x="596.1239" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge16" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M347.1602,-1243.2953C247.663,-1190.3015 97.2555,-1093.4815 23.1239,-962 -12.3717,-899.0443 4.1239,-872.7728 4.1239,-800.5 4.1239,-800.5 4.1239,-800.5 4.1239,-351.5 4.1239,-256.5646 607.959,-169.5746 942.8013,-128.6344"/>
<polygon fill="#000000" stroke="#000000" points="943.6176,-132.0609 953.1208,-127.3769 942.7708,-125.1123 943.6176,-132.0609"/>
<text text-anchor="middle" x="46.6239" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- sample -->
<g id="node8" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1384.1239,-639.5C1384.1239,-639.5 1698.1239,-639.5 1698.1239,-639.5 1704.1239,-639.5 1710.1239,-645.5 1710.1239,-651.5 1710.1239,-651.5 1710.1239,-949.5 1710.1239,-949.5 1710.1239,-955.5 1704.1239,-961.5 1698.1239,-961.5 1698.1239,-961.5 1384.1239,-961.5 1384.1239,-961.5 1378.1239,-961.5 1372.1239,-955.5 1372.1239,-949.5 1372.1239,-949.5 1372.1239,-651.5 1372.1239,-651.5 1372.1239,-645.5 1378.1239,-639.5 1384.1239,-639.5"/>
<text text-anchor="middle" x="1406.1239" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1440.1239,-639.5 1440.1239,-961.5 "/>
<text text-anchor="middle" x="1450.6239" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1461.1239,-639.5 1461.1239,-961.5 "/>
<text text-anchor="middle" x="1575.1239" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1461.1239,-938.5 1689.1239,-938.5 "/>
<text text-anchor="middle" x="1575.1239" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1461.1239,-915.5 1689.1239,-915.5 "/>
<text text-anchor="middle" x="1575.1239" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1461.1239,-892.5 1689.1239,-892.5 "/>
<text text-anchor="middle" x="1575.1239" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1461.1239,-869.5 1689.1239,-869.5 "/>
<text text-anchor="middle" x="1575.1239" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1461.1239,-846.5 1689.1239,-846.5 "/>
<text text-anchor="middle" x="1575.1239" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="1461.1239,-823.5 1689.1239,-823.5 "/>
<text text-anchor="middle" x="1575.1239" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1461.1239,-800.5 1689.1239,-800.5 "/>
<text text-anchor="middle" x="1575.1239" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="1461.1239,-777.5 1689.1239,-777.5 "/>
<text text-anchor="middle" x="1575.1239" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="1461.1239,-754.5 1689.1239,-754.5 "/>
<text text-anchor="middle" x="1575.1239" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage</text>
<polyline fill="none" stroke="#000000" points="1461.1239,-731.5 1689.1239,-731.5 "/>
<text text-anchor="middle" x="1575.1239" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1461.1239,-708.5 1689.1239,-708.5 "/>
<text text-anchor="middle" x="1575.1239" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1461.1239,-685.5 1689.1239,-685.5 "/>
<text text-anchor="middle" x="1575.1239" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1461.1239,-662.5 1689.1239,-662.5 "/>
<text text-anchor="middle" x="1575.1239" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_status</text>
<polyline fill="none" stroke="#000000" points="1689.1239,-639.5 1689.1239,-961.5 "/>
<text text-anchor="middle" x="1699.6239" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M508.1631,-1243.28C599.6854,-1179.8128 775.4239,-1067.3774 943.1239,-1013 987.7364,-998.5342 1319.4471,-981.4479 1362.1239,-962 1362.4363,-961.8576 1362.7486,-961.7145 1363.0607,-961.5706"/>
<polygon fill="#000000" stroke="#000000" points="1364.5979,-964.7151 1372.0631,-957.1969 1361.5389,-958.4188 1364.5979,-964.7151"/>
<text text-anchor="middle" x="1283.6239" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- participant -->
<g id="node15" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M622.6239,-495.5C622.6239,-495.5 853.6239,-495.5 853.6239,-495.5 859.6239,-495.5 865.6239,-501.5 865.6239,-507.5 865.6239,-507.5 865.6239,-575.5 865.6239,-575.5 865.6239,-581.5 859.6239,-587.5 853.6239,-587.5 853.6239,-587.5 622.6239,-587.5 622.6239,-587.5 616.6239,-587.5 610.6239,-581.5 610.6239,-575.5 610.6239,-575.5 610.6239,-507.5 610.6239,-507.5 610.6239,-501.5 616.6239,-495.5 622.6239,-495.5"/>
<text text-anchor="middle" x="658.6239" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="706.6239,-495.5 706.6239,-587.5 "/>
<text text-anchor="middle" x="717.1239" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="727.6239,-495.5 727.6239,-587.5 "/>
<text text-anchor="middle" x="786.1239" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="727.6239,-564.5 844.6239,-564.5 "/>
<text text-anchor="middle" x="786.1239" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="727.6239,-541.5 844.6239,-541.5 "/>
<text text-anchor="middle" x="786.1239" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="727.6239,-518.5 844.6239,-518.5 "/>
<text text-anchor="middle" x="786.1239" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="844.6239,-495.5 844.6239,-587.5 "/>
<text text-anchor="middle" x="855.1239" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M441.7396,-1243.2484C434.9103,-1102.7418 417.9367,-687.5142 453.1239,-639 462.8375,-625.6074 532.5902,-601.6304 600.6505,-580.8059"/>
<polygon fill="#000000" stroke="#000000" points="601.6879,-584.1487 610.2364,-577.8898 599.6506,-577.4518 601.6879,-584.1487"/>
<text text-anchor="middle" x="495.6239" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study_personnel -->
<g id="node4" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M1200.6239,-294C1200.6239,-294 1507.6239,-294 1507.6239,-294 1513.6239,-294 1519.6239,-300 1519.6239,-306 1519.6239,-306 1519.6239,-397 1519.6239,-397 1519.6239,-403 1513.6239,-409 1507.6239,-409 1507.6239,-409 1200.6239,-409 1200.6239,-409 1194.6239,-409 1188.6239,-403 1188.6239,-397 1188.6239,-397 1188.6239,-306 1188.6239,-306 1188.6239,-300 1194.6239,-294 1200.6239,-294"/>
<text text-anchor="middle" x="1255.6239" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="1322.6239,-294 1322.6239,-409 "/>
<text text-anchor="middle" x="1333.1239" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1343.6239,-294 1343.6239,-409 "/>
<text text-anchor="middle" x="1421.1239" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="1343.6239,-386 1498.6239,-386 "/>
<text text-anchor="middle" x="1421.1239" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="1343.6239,-363 1498.6239,-363 "/>
<text text-anchor="middle" x="1421.1239" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="1343.6239,-340 1498.6239,-340 "/>
<text text-anchor="middle" x="1421.1239" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="1343.6239,-317 1498.6239,-317 "/>
<text text-anchor="middle" x="1421.1239" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="1498.6239,-294 1498.6239,-409 "/>
<text text-anchor="middle" x="1509.1239" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge5" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1308.8843,-293.7846C1290.6434,-270.5133 1268.9489,-242.836 1247.8455,-215.9129"/>
<polygon fill="#000000" stroke="#000000" points="1250.541,-213.6782 1241.6172,-207.967 1245.0317,-217.9966 1250.541,-213.6782"/>
<text text-anchor="middle" x="1332.6239" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- therapeutic_procedure -->
<g id="node5" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M559.6239,-743C559.6239,-743 916.6239,-743 916.6239,-743 922.6239,-743 928.6239,-749 928.6239,-755 928.6239,-755 928.6239,-846 928.6239,-846 928.6239,-852 922.6239,-858 916.6239,-858 916.6239,-858 559.6239,-858 559.6239,-858 553.6239,-858 547.6239,-852 547.6239,-846 547.6239,-846 547.6239,-755 547.6239,-755 547.6239,-749 553.6239,-743 559.6239,-743"/>
<text text-anchor="middle" x="638.1239" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="728.6239,-743 728.6239,-858 "/>
<text text-anchor="middle" x="739.1239" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="749.6239,-743 749.6239,-858 "/>
<text text-anchor="middle" x="828.6239" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="749.6239,-835 907.6239,-835 "/>
<text text-anchor="middle" x="828.6239" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="749.6239,-812 907.6239,-812 "/>
<text text-anchor="middle" x="828.6239" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="749.6239,-789 907.6239,-789 "/>
<text text-anchor="middle" x="828.6239" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="749.6239,-766 907.6239,-766 "/>
<text text-anchor="middle" x="828.6239" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="907.6239,-743 907.6239,-858 "/>
<text text-anchor="middle" x="918.1239" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M738.1239,-742.6977C738.1239,-699.5876 738.1239,-640.9982 738.1239,-598.1639"/>
<polygon fill="#000000" stroke="#000000" points="741.624,-597.9073 738.1239,-587.9073 734.624,-597.9074 741.624,-597.9073"/>
<text text-anchor="middle" x="831.1239" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- study_funding -->
<g id="node6" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M1549.6239,-317C1549.6239,-317 1928.6239,-317 1928.6239,-317 1934.6239,-317 1940.6239,-323 1940.6239,-329 1940.6239,-329 1940.6239,-374 1940.6239,-374 1940.6239,-380 1934.6239,-386 1928.6239,-386 1928.6239,-386 1549.6239,-386 1549.6239,-386 1543.6239,-386 1537.6239,-380 1537.6239,-374 1537.6239,-374 1537.6239,-329 1537.6239,-329 1537.6239,-323 1543.6239,-317 1549.6239,-317"/>
<text text-anchor="middle" x="1597.1239" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="1656.6239,-317 1656.6239,-386 "/>
<text text-anchor="middle" x="1667.1239" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1677.6239,-317 1677.6239,-386 "/>
<text text-anchor="middle" x="1798.6239" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="1677.6239,-363 1919.6239,-363 "/>
<text text-anchor="middle" x="1798.6239" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="1677.6239,-340 1919.6239,-340 "/>
<text text-anchor="middle" x="1798.6239" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="1919.6239,-317 1919.6239,-386 "/>
<text text-anchor="middle" x="1930.1239" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge7" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1661.0822,-316.9654C1621.3393,-299.4605 1572.2209,-277.9514 1528.1239,-259 1479.1066,-237.9341 1426.3028,-215.5258 1376.4191,-194.4862"/>
<polygon fill="#000000" stroke="#000000" points="1377.7146,-191.2341 1367.1403,-190.5742 1374.9951,-197.6843 1377.7146,-191.2341"/>
<text text-anchor="middle" x="1541.1239" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- diagnosis -->
<g id="node7" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M958.6239,-651C958.6239,-651 1341.6239,-651 1341.6239,-651 1347.6239,-651 1353.6239,-657 1353.6239,-663 1353.6239,-663 1353.6239,-938 1353.6239,-938 1353.6239,-944 1347.6239,-950 1341.6239,-950 1341.6239,-950 958.6239,-950 958.6239,-950 952.6239,-950 946.6239,-944 946.6239,-938 946.6239,-938 946.6239,-663 946.6239,-663 946.6239,-657 952.6239,-651 958.6239,-651"/>
<text text-anchor="middle" x="988.6239" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1030.6239,-651 1030.6239,-950 "/>
<text text-anchor="middle" x="1041.1239" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1051.6239,-651 1051.6239,-950 "/>
<text text-anchor="middle" x="1192.1239" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1051.6239,-927 1332.6239,-927 "/>
<text text-anchor="middle" x="1192.1239" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1051.6239,-904 1332.6239,-904 "/>
<text text-anchor="middle" x="1192.1239" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1051.6239,-881 1332.6239,-881 "/>
<text text-anchor="middle" x="1192.1239" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1051.6239,-858 1332.6239,-858 "/>
<text text-anchor="middle" x="1192.1239" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1051.6239,-835 1332.6239,-835 "/>
<text text-anchor="middle" x="1192.1239" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="1051.6239,-812 1332.6239,-812 "/>
<text text-anchor="middle" x="1192.1239" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1051.6239,-789 1332.6239,-789 "/>
<text text-anchor="middle" x="1192.1239" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1051.6239,-766 1332.6239,-766 "/>
<text text-anchor="middle" x="1192.1239" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis_reference_source</text>
<polyline fill="none" stroke="#000000" points="1051.6239,-743 1332.6239,-743 "/>
<text text-anchor="middle" x="1192.1239" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="1051.6239,-720 1332.6239,-720 "/>
<text text-anchor="middle" x="1192.1239" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="1051.6239,-697 1332.6239,-697 "/>
<text text-anchor="middle" x="1192.1239" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="1051.6239,-674 1332.6239,-674 "/>
<text text-anchor="middle" x="1192.1239" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="1332.6239,-651 1332.6239,-950 "/>
<text text-anchor="middle" x="1343.1239" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M994.275,-650.9655C972.9662,-634.4852 950.648,-618.9973 928.1239,-606 911.6801,-596.5113 893.6266,-588.1394 875.3939,-580.8388"/>
<polygon fill="#000000" stroke="#000000" points="876.4389,-577.4897 865.8506,-577.1185 873.8964,-584.0117 876.4389,-577.4897"/>
<text text-anchor="middle" x="993.6239" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge9" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1371.9199,-644.4457C1283.3796,-560.9442 1190.8839,-470.0231 1179.1239,-444 1161.4493,-404.8889 1157.7117,-300.773 1157.7874,-217.9702"/>
<polygon fill="#000000" stroke="#000000" points="1161.288,-217.7366 1157.816,-207.7268 1154.288,-217.717 1161.288,-217.7366"/>
<text text-anchor="middle" x="1239.6239" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1371.8987,-643.39C1368.6624,-641.845 1365.4034,-640.3793 1362.1239,-639 1302.8098,-614.0533 1135.3665,-637.3203 1073.1239,-621 1058.3184,-617.1179 1056.6046,-610.9578 1042.1239,-606 988.8957,-587.776 928.5899,-573.6965 875.8044,-563.4089"/>
<polygon fill="#000000" stroke="#000000" points="876.1769,-559.9165 865.6961,-561.467 874.8562,-566.7908 876.1769,-559.9165"/>
<text text-anchor="middle" x="1109.6239" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- methylation_array_file -->
<g id="node9" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M964.6239,-1174.5C964.6239,-1174.5 1331.6239,-1174.5 1331.6239,-1174.5 1337.6239,-1174.5 1343.6239,-1180.5 1343.6239,-1186.5 1343.6239,-1186.5 1343.6239,-1392.5 1343.6239,-1392.5 1343.6239,-1398.5 1337.6239,-1404.5 1331.6239,-1404.5 1331.6239,-1404.5 964.6239,-1404.5 964.6239,-1404.5 958.6239,-1404.5 952.6239,-1398.5 952.6239,-1392.5 952.6239,-1392.5 952.6239,-1186.5 952.6239,-1186.5 952.6239,-1180.5 958.6239,-1174.5 964.6239,-1174.5"/>
<text text-anchor="middle" x="1041.6239" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="1130.6239,-1174.5 1130.6239,-1404.5 "/>
<text text-anchor="middle" x="1141.1239" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1151.6239,-1174.5 1151.6239,-1404.5 "/>
<text text-anchor="middle" x="1237.1239" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1151.6239,-1381.5 1322.6239,-1381.5 "/>
<text text-anchor="middle" x="1237.1239" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1151.6239,-1358.5 1322.6239,-1358.5 "/>
<text text-anchor="middle" x="1237.1239" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1151.6239,-1335.5 1322.6239,-1335.5 "/>
<text text-anchor="middle" x="1237.1239" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1151.6239,-1312.5 1322.6239,-1312.5 "/>
<text text-anchor="middle" x="1237.1239" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1151.6239,-1289.5 1322.6239,-1289.5 "/>
<text text-anchor="middle" x="1237.1239" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1151.6239,-1266.5 1322.6239,-1266.5 "/>
<text text-anchor="middle" x="1237.1239" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1151.6239,-1243.5 1322.6239,-1243.5 "/>
<text text-anchor="middle" x="1237.1239" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1151.6239,-1220.5 1322.6239,-1220.5 "/>
<text text-anchor="middle" x="1237.1239" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="1151.6239,-1197.5 1322.6239,-1197.5 "/>
<text text-anchor="middle" x="1237.1239" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="1322.6239,-1174.5 1322.6239,-1404.5 "/>
<text text-anchor="middle" x="1333.1239" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1216.3714,-1174.2631C1254.0453,-1114.1252 1303.3944,-1040.6506 1354.1239,-980 1357.7329,-975.6852 1361.4353,-971.3637 1365.2134,-967.0467"/>
<polygon fill="#000000" stroke="#000000" points="1368.0801,-969.0889 1372.0919,-959.283 1362.8407,-964.4469 1368.0801,-969.0889"/>
<text text-anchor="middle" x="1445.6239" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- publication -->
<g id="node10" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M1971.1239,-333.5C1971.1239,-333.5 2181.1239,-333.5 2181.1239,-333.5 2187.1239,-333.5 2193.1239,-339.5 2193.1239,-345.5 2193.1239,-345.5 2193.1239,-357.5 2193.1239,-357.5 2193.1239,-363.5 2187.1239,-369.5 2181.1239,-369.5 2181.1239,-369.5 1971.1239,-369.5 1971.1239,-369.5 1965.1239,-369.5 1959.1239,-363.5 1959.1239,-357.5 1959.1239,-357.5 1959.1239,-345.5 1959.1239,-345.5 1959.1239,-339.5 1965.1239,-333.5 1971.1239,-333.5"/>
<text text-anchor="middle" x="2007.6239" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="2056.1239,-333.5 2056.1239,-369.5 "/>
<text text-anchor="middle" x="2066.6239" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2077.1239,-333.5 2077.1239,-369.5 "/>
<text text-anchor="middle" x="2124.6239" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="2172.1239,-333.5 2172.1239,-369.5 "/>
<text text-anchor="middle" x="2182.6239" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge4" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2057.3213,-333.4726C2034.0703,-312.2451 1992.3684,-277.537 1950.1239,-259 1766.4668,-178.4108 1540.4873,-139.4669 1377.3352,-120.802"/>
<polygon fill="#000000" stroke="#000000" points="1377.5002,-117.2985 1367.171,-119.6561 1376.7159,-124.2545 1377.5002,-117.2985"/>
<text text-anchor="middle" x="1940.1239" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- study_admin -->
<g id="node11" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M2223.1239,-259.5C2223.1239,-259.5 2549.1239,-259.5 2549.1239,-259.5 2555.1239,-259.5 2561.1239,-265.5 2561.1239,-271.5 2561.1239,-271.5 2561.1239,-431.5 2561.1239,-431.5 2561.1239,-437.5 2555.1239,-443.5 2549.1239,-443.5 2549.1239,-443.5 2223.1239,-443.5 2223.1239,-443.5 2217.1239,-443.5 2211.1239,-437.5 2211.1239,-431.5 2211.1239,-431.5 2211.1239,-271.5 2211.1239,-271.5 2211.1239,-265.5 2217.1239,-259.5 2223.1239,-259.5"/>
<text text-anchor="middle" x="2265.1239" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="2319.1239,-259.5 2319.1239,-443.5 "/>
<text text-anchor="middle" x="2329.6239" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2340.1239,-259.5 2340.1239,-443.5 "/>
<text text-anchor="middle" x="2440.1239" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="2340.1239,-420.5 2540.1239,-420.5 "/>
<text text-anchor="middle" x="2440.1239" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="2340.1239,-397.5 2540.1239,-397.5 "/>
<text text-anchor="middle" x="2440.1239" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="2340.1239,-374.5 2540.1239,-374.5 "/>
<text text-anchor="middle" x="2440.1239" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="2340.1239,-351.5 2540.1239,-351.5 "/>
<text text-anchor="middle" x="2440.1239" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="2340.1239,-328.5 2540.1239,-328.5 "/>
<text text-anchor="middle" x="2440.1239" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="2340.1239,-305.5 2540.1239,-305.5 "/>
<text text-anchor="middle" x="2440.1239" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="2340.1239,-282.5 2540.1239,-282.5 "/>
<text text-anchor="middle" x="2440.1239" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="2540.1239,-259.5 2540.1239,-443.5 "/>
<text text-anchor="middle" x="2550.6239" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge11" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2211.0863,-262.0038C2208.0902,-260.9628 2205.1014,-259.9602 2202.1239,-259 1925.8281,-169.899 1591.564,-131.7007 1377.4392,-115.5365"/>
<polygon fill="#000000" stroke="#000000" points="1377.5668,-112.0364 1367.3343,-114.7833 1377.0465,-119.017 1377.5668,-112.0364"/>
<text text-anchor="middle" x="2176.6239" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- imaging_file -->
<g id="node12" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M1374.1239,-1128.5C1374.1239,-1128.5 1708.1239,-1128.5 1708.1239,-1128.5 1714.1239,-1128.5 1720.1239,-1134.5 1720.1239,-1140.5 1720.1239,-1140.5 1720.1239,-1438.5 1720.1239,-1438.5 1720.1239,-1444.5 1714.1239,-1450.5 1708.1239,-1450.5 1708.1239,-1450.5 1374.1239,-1450.5 1374.1239,-1450.5 1368.1239,-1450.5 1362.1239,-1444.5 1362.1239,-1438.5 1362.1239,-1438.5 1362.1239,-1140.5 1362.1239,-1140.5 1362.1239,-1134.5 1368.1239,-1128.5 1374.1239,-1128.5"/>
<text text-anchor="middle" x="1414.1239" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="1466.1239,-1128.5 1466.1239,-1450.5 "/>
<text text-anchor="middle" x="1476.6239" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1487.1239,-1128.5 1487.1239,-1450.5 "/>
<text text-anchor="middle" x="1593.1239" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1487.1239,-1427.5 1699.1239,-1427.5 "/>
<text text-anchor="middle" x="1593.1239" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1487.1239,-1404.5 1699.1239,-1404.5 "/>
<text text-anchor="middle" x="1593.1239" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1487.1239,-1381.5 1699.1239,-1381.5 "/>
<text text-anchor="middle" x="1593.1239" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1487.1239,-1358.5 1699.1239,-1358.5 "/>
<text text-anchor="middle" x="1593.1239" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1487.1239,-1335.5 1699.1239,-1335.5 "/>
<text text-anchor="middle" x="1593.1239" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1487.1239,-1312.5 1699.1239,-1312.5 "/>
<text text-anchor="middle" x="1593.1239" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1487.1239,-1289.5 1699.1239,-1289.5 "/>
<text text-anchor="middle" x="1593.1239" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1487.1239,-1266.5 1699.1239,-1266.5 "/>
<text text-anchor="middle" x="1593.1239" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1487.1239,-1243.5 1699.1239,-1243.5 "/>
<text text-anchor="middle" x="1593.1239" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="1487.1239,-1220.5 1699.1239,-1220.5 "/>
<text text-anchor="middle" x="1593.1239" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="1487.1239,-1197.5 1699.1239,-1197.5 "/>
<text text-anchor="middle" x="1593.1239" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="1487.1239,-1174.5 1699.1239,-1174.5 "/>
<text text-anchor="middle" x="1593.1239" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1487.1239,-1151.5 1699.1239,-1151.5 "/>
<text text-anchor="middle" x="1593.1239" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="1699.1239,-1128.5 1699.1239,-1450.5 "/>
<text text-anchor="middle" x="1709.6239" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1541.1239,-1128.3669C1541.1239,-1078.1459 1541.1239,-1022.594 1541.1239,-971.7088"/>
<polygon fill="#000000" stroke="#000000" points="1544.624,-971.5969 1541.1239,-961.597 1537.624,-971.597 1544.624,-971.5969"/>
<text text-anchor="middle" x="1595.6239" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- sequencing_file -->
<g id="node13" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M1750.6239,-1013.5C1750.6239,-1013.5 2219.6239,-1013.5 2219.6239,-1013.5 2225.6239,-1013.5 2231.6239,-1019.5 2231.6239,-1025.5 2231.6239,-1025.5 2231.6239,-1553.5 2231.6239,-1553.5 2231.6239,-1559.5 2225.6239,-1565.5 2219.6239,-1565.5 2219.6239,-1565.5 1750.6239,-1565.5 1750.6239,-1565.5 1744.6239,-1565.5 1738.6239,-1559.5 1738.6239,-1553.5 1738.6239,-1553.5 1738.6239,-1025.5 1738.6239,-1025.5 1738.6239,-1019.5 1744.6239,-1013.5 1750.6239,-1013.5"/>
<text text-anchor="middle" x="1802.6239" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="1866.6239,-1013.5 1866.6239,-1565.5 "/>
<text text-anchor="middle" x="1877.1239" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1887.6239,-1013.5 1887.6239,-1565.5 "/>
<text text-anchor="middle" x="2049.1239" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="1887.6239,-1542.5 2210.6239,-1542.5 "/>
<text text-anchor="middle" x="2049.1239" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1887.6239,-1519.5 2210.6239,-1519.5 "/>
<text text-anchor="middle" x="2049.1239" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1887.6239,-1496.5 2210.6239,-1496.5 "/>
<text text-anchor="middle" x="2049.1239" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="1887.6239,-1473.5 2210.6239,-1473.5 "/>
<text text-anchor="middle" x="2049.1239" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="1887.6239,-1450.5 2210.6239,-1450.5 "/>
<text text-anchor="middle" x="2049.1239" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1887.6239,-1427.5 2210.6239,-1427.5 "/>
<text text-anchor="middle" x="2049.1239" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1887.6239,-1404.5 2210.6239,-1404.5 "/>
<text text-anchor="middle" x="2049.1239" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1887.6239,-1381.5 2210.6239,-1381.5 "/>
<text text-anchor="middle" x="2049.1239" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1887.6239,-1358.5 2210.6239,-1358.5 "/>
<text text-anchor="middle" x="2049.1239" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1887.6239,-1335.5 2210.6239,-1335.5 "/>
<text text-anchor="middle" x="2049.1239" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1887.6239,-1312.5 2210.6239,-1312.5 "/>
<text text-anchor="middle" x="2049.1239" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1887.6239,-1289.5 2210.6239,-1289.5 "/>
<text text-anchor="middle" x="2049.1239" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="1887.6239,-1266.5 2210.6239,-1266.5 "/>
<text text-anchor="middle" x="2049.1239" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="1887.6239,-1243.5 2210.6239,-1243.5 "/>
<text text-anchor="middle" x="2049.1239" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="1887.6239,-1220.5 2210.6239,-1220.5 "/>
<text text-anchor="middle" x="2049.1239" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="1887.6239,-1197.5 2210.6239,-1197.5 "/>
<text text-anchor="middle" x="2049.1239" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="1887.6239,-1174.5 2210.6239,-1174.5 "/>
<text text-anchor="middle" x="2049.1239" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="1887.6239,-1151.5 2210.6239,-1151.5 "/>
<text text-anchor="middle" x="2049.1239" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1887.6239,-1128.5 2210.6239,-1128.5 "/>
<text text-anchor="middle" x="2049.1239" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="1887.6239,-1105.5 2210.6239,-1105.5 "/>
<text text-anchor="middle" x="2049.1239" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="1887.6239,-1082.5 2210.6239,-1082.5 "/>
<text text-anchor="middle" x="2049.1239" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="1887.6239,-1059.5 2210.6239,-1059.5 "/>
<text text-anchor="middle" x="2049.1239" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="1887.6239,-1036.5 2210.6239,-1036.5 "/>
<text text-anchor="middle" x="2049.1239" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="2210.6239,-1013.5 2210.6239,-1565.5 "/>
<text text-anchor="middle" x="2221.1239" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1738.4544,-1017.8303C1723.5311,-1001.3945 1708.7584,-985.1245 1694.4105,-969.3224"/>
<polygon fill="#000000" stroke="#000000" points="1696.7158,-966.6547 1687.4023,-961.6039 1691.5333,-971.3603 1696.7158,-966.6547"/>
<text text-anchor="middle" x="1777.6239" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node14" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M44.1239,-685.5C44.1239,-685.5 396.1239,-685.5 396.1239,-685.5 402.1239,-685.5 408.1239,-691.5 408.1239,-697.5 408.1239,-697.5 408.1239,-903.5 408.1239,-903.5 408.1239,-909.5 402.1239,-915.5 396.1239,-915.5 396.1239,-915.5 44.1239,-915.5 44.1239,-915.5 38.1239,-915.5 32.1239,-909.5 32.1239,-903.5 32.1239,-903.5 32.1239,-697.5 32.1239,-697.5 32.1239,-691.5 38.1239,-685.5 44.1239,-685.5"/>
<text text-anchor="middle" x="115.6239" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="199.1239,-685.5 199.1239,-915.5 "/>
<text text-anchor="middle" x="209.6239" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="220.1239,-685.5 220.1239,-915.5 "/>
<text text-anchor="middle" x="303.6239" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="220.1239,-892.5 387.1239,-892.5 "/>
<text text-anchor="middle" x="303.6239" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="220.1239,-869.5 387.1239,-869.5 "/>
<text text-anchor="middle" x="303.6239" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="220.1239,-846.5 387.1239,-846.5 "/>
<text text-anchor="middle" x="303.6239" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="220.1239,-823.5 387.1239,-823.5 "/>
<text text-anchor="middle" x="303.6239" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="220.1239,-800.5 387.1239,-800.5 "/>
<text text-anchor="middle" x="303.6239" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="220.1239,-777.5 387.1239,-777.5 "/>
<text text-anchor="middle" x="303.6239" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="220.1239,-754.5 387.1239,-754.5 "/>
<text text-anchor="middle" x="303.6239" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="220.1239,-731.5 387.1239,-731.5 "/>
<text text-anchor="middle" x="303.6239" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="220.1239,-708.5 387.1239,-708.5 "/>
<text text-anchor="middle" x="303.6239" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="387.1239,-685.5 387.1239,-915.5 "/>
<text text-anchor="middle" x="397.6239" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge10" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M193.7381,-685.4342C192.6471,-658.2771 196.0158,-630.2058 208.1239,-606 334.4212,-353.5145 462.3693,-347.6554 717.1239,-226 787.7392,-192.2784 869.2833,-166.4867 943.0121,-147.4989"/>
<polygon fill="#000000" stroke="#000000" points="944.067,-150.8421 952.894,-144.9825 942.3395,-144.0586 944.067,-150.8421"/>
<text text-anchor="middle" x="387.1239" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M195.3598,-685.3291C195.4835,-656.458 201.9585,-627.5928 221.1239,-606 246.0262,-577.9436 455.7589,-559.1639 600.3166,-549.4197"/>
<polygon fill="#000000" stroke="#000000" points="600.8636,-552.8911 610.6086,-548.7337 600.398,-545.9066 600.8636,-552.8911"/>
<text text-anchor="middle" x="350.6239" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge13" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M794.8242,-495.2637C833.1454,-464.0146 883.3103,-423.1076 920.3265,-392.9228"/>
<polygon fill="#000000" stroke="#000000" points="922.9507,-395.2991 928.4887,-386.2669 918.5268,-389.8741 922.9507,-395.2991"/>
<text text-anchor="middle" x="884.6239" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge14" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M713.8243,-495.4185C685.8064,-435.2195 649.6735,-329.2371 700.1239,-259 730.5766,-216.6037 839.2767,-178.9428 943.3625,-151.3624"/>
<polygon fill="#000000" stroke="#000000" points="944.3103,-154.7322 953.0947,-148.809 942.5338,-147.9614 944.3103,-154.7322"/>
<text text-anchor="middle" x="750.6239" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
</g>
</svg>
</div>
