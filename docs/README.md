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
<svg width="2801pt" height="1735pt"
 viewBox="0.00 0.00 2801.00 1735.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1731)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1731 2797,-1731 2797,4 -4,4"/>
<!-- study_personnel -->
<g id="node1" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M483,-294C483,-294 790,-294 790,-294 796,-294 802,-300 802,-306 802,-306 802,-397 802,-397 802,-403 796,-409 790,-409 790,-409 483,-409 483,-409 477,-409 471,-403 471,-397 471,-397 471,-306 471,-306 471,-300 477,-294 483,-294"/>
<text text-anchor="middle" x="538" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="605,-294 605,-409 "/>
<text text-anchor="middle" x="615.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="626,-294 626,-409 "/>
<text text-anchor="middle" x="703.5" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="626,-386 781,-386 "/>
<text text-anchor="middle" x="703.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="626,-363 781,-363 "/>
<text text-anchor="middle" x="703.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="626,-340 781,-340 "/>
<text text-anchor="middle" x="703.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="626,-317 781,-317 "/>
<text text-anchor="middle" x="703.5" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="781,-294 781,-409 "/>
<text text-anchor="middle" x="791.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node5" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M1230.5,-.5C1230.5,-.5 1620.5,-.5 1620.5,-.5 1626.5,-.5 1632.5,-6.5 1632.5,-12.5 1632.5,-12.5 1632.5,-195.5 1632.5,-195.5 1632.5,-201.5 1626.5,-207.5 1620.5,-207.5 1620.5,-207.5 1230.5,-207.5 1230.5,-207.5 1224.5,-207.5 1218.5,-201.5 1218.5,-195.5 1218.5,-195.5 1218.5,-12.5 1218.5,-12.5 1218.5,-6.5 1224.5,-.5 1230.5,-.5"/>
<text text-anchor="middle" x="1246.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="1274.5,-.5 1274.5,-207.5 "/>
<text text-anchor="middle" x="1285" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1295.5,-.5 1295.5,-207.5 "/>
<text text-anchor="middle" x="1453.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="1295.5,-184.5 1611.5,-184.5 "/>
<text text-anchor="middle" x="1453.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="1295.5,-161.5 1611.5,-161.5 "/>
<text text-anchor="middle" x="1453.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="1295.5,-138.5 1611.5,-138.5 "/>
<text text-anchor="middle" x="1453.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="1295.5,-115.5 1611.5,-115.5 "/>
<text text-anchor="middle" x="1453.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="1295.5,-92.5 1611.5,-92.5 "/>
<text text-anchor="middle" x="1453.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="1295.5,-69.5 1611.5,-69.5 "/>
<text text-anchor="middle" x="1453.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="1295.5,-46.5 1611.5,-46.5 "/>
<text text-anchor="middle" x="1453.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="1295.5,-23.5 1611.5,-23.5 "/>
<text text-anchor="middle" x="1453.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="1611.5,-.5 1611.5,-207.5 "/>
<text text-anchor="middle" x="1622" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge2" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M642.1032,-293.8661C647.4453,-269.5121 657.7427,-242.9255 677.5,-226 755.4818,-159.1951 1016.4269,-128.5006 1208.2431,-114.7171"/>
<polygon fill="#000000" stroke="#000000" points="1208.7436,-118.1905 1218.4716,-113.9933 1208.2494,-111.208 1208.7436,-118.1905"/>
<text text-anchor="middle" x="747" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- pdx -->
<g id="node2" class="node">
<title>pdx</title>
<path fill="none" stroke="#000000" d="M12,-1335.5C12,-1335.5 341,-1335.5 341,-1335.5 347,-1335.5 353,-1341.5 353,-1347.5 353,-1347.5 353,-1530.5 353,-1530.5 353,-1536.5 347,-1542.5 341,-1542.5 341,-1542.5 12,-1542.5 12,-1542.5 6,-1542.5 0,-1536.5 0,-1530.5 0,-1530.5 0,-1347.5 0,-1347.5 0,-1341.5 6,-1335.5 12,-1335.5"/>
<text text-anchor="middle" x="21.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
<polyline fill="none" stroke="#000000" points="43,-1335.5 43,-1542.5 "/>
<text text-anchor="middle" x="53.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="64,-1335.5 64,-1542.5 "/>
<text text-anchor="middle" x="198" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">injection_type_and_site</text>
<polyline fill="none" stroke="#000000" points="64,-1519.5 332,-1519.5 "/>
<text text-anchor="middle" x="198" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_id</text>
<polyline fill="none" stroke="#000000" points="64,-1496.5 332,-1496.5 "/>
<text text-anchor="middle" x="198" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_type</text>
<polyline fill="none" stroke="#000000" points="64,-1473.5 332,-1473.5 "/>
<text text-anchor="middle" x="198" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">mouse_strain</text>
<polyline fill="none" stroke="#000000" points="64,-1450.5 332,-1450.5 "/>
<text text-anchor="middle" x="198" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">strain_immune_system_humanized</text>
<polyline fill="none" stroke="#000000" points="64,-1427.5 332,-1427.5 "/>
<text text-anchor="middle" x="198" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_characterization_method</text>
<polyline fill="none" stroke="#000000" points="64,-1404.5 332,-1404.5 "/>
<text text-anchor="middle" x="198" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_not_mus_or_ebv_origin</text>
<polyline fill="none" stroke="#000000" points="64,-1381.5 332,-1381.5 "/>
<text text-anchor="middle" x="198" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_preparation</text>
<polyline fill="none" stroke="#000000" points="64,-1358.5 332,-1358.5 "/>
<text text-anchor="middle" x="198" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_humanization</text>
<polyline fill="none" stroke="#000000" points="332,-1335.5 332,-1542.5 "/>
<text text-anchor="middle" x="342.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node8" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1071.5,-800.5C1071.5,-800.5 1385.5,-800.5 1385.5,-800.5 1391.5,-800.5 1397.5,-806.5 1397.5,-812.5 1397.5,-812.5 1397.5,-949.5 1397.5,-949.5 1397.5,-955.5 1391.5,-961.5 1385.5,-961.5 1385.5,-961.5 1071.5,-961.5 1071.5,-961.5 1065.5,-961.5 1059.5,-955.5 1059.5,-949.5 1059.5,-949.5 1059.5,-812.5 1059.5,-812.5 1059.5,-806.5 1065.5,-800.5 1071.5,-800.5"/>
<text text-anchor="middle" x="1093.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1127.5,-800.5 1127.5,-961.5 "/>
<text text-anchor="middle" x="1138" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1148.5,-800.5 1148.5,-961.5 "/>
<text text-anchor="middle" x="1262.5" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="1148.5,-938.5 1376.5,-938.5 "/>
<text text-anchor="middle" x="1262.5" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1148.5,-915.5 1376.5,-915.5 "/>
<text text-anchor="middle" x="1262.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1148.5,-892.5 1376.5,-892.5 "/>
<text text-anchor="middle" x="1262.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1148.5,-869.5 1376.5,-869.5 "/>
<text text-anchor="middle" x="1262.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1148.5,-846.5 1376.5,-846.5 "/>
<text text-anchor="middle" x="1262.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1148.5,-823.5 1376.5,-823.5 "/>
<text text-anchor="middle" x="1262.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="1376.5,-800.5 1376.5,-961.5 "/>
<text text-anchor="middle" x="1387" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M214.7339,-1335.3919C244.3703,-1270.7709 292.1942,-1192.2881 361.5,-1151 377.7969,-1141.2913 1025.5935,-1108.6034 1042.5,-1100 1098.909,-1071.2947 1145.0929,-1017.2463 1177.3305,-970.028"/>
<polygon fill="#000000" stroke="#000000" points="1180.3181,-971.8572 1182.9857,-961.6037 1174.5061,-967.9557 1180.3181,-971.8572"/>
<text text-anchor="middle" x="824.5" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- clinical_measure_file -->
<g id="node3" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M669.5,-754.5C669.5,-754.5 1021.5,-754.5 1021.5,-754.5 1027.5,-754.5 1033.5,-760.5 1033.5,-766.5 1033.5,-766.5 1033.5,-995.5 1033.5,-995.5 1033.5,-1001.5 1027.5,-1007.5 1021.5,-1007.5 1021.5,-1007.5 669.5,-1007.5 669.5,-1007.5 663.5,-1007.5 657.5,-1001.5 657.5,-995.5 657.5,-995.5 657.5,-766.5 657.5,-766.5 657.5,-760.5 663.5,-754.5 669.5,-754.5"/>
<text text-anchor="middle" x="741" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="824.5,-754.5 824.5,-1007.5 "/>
<text text-anchor="middle" x="835" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="845.5,-754.5 845.5,-1007.5 "/>
<text text-anchor="middle" x="929" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="845.5,-984.5 1012.5,-984.5 "/>
<text text-anchor="middle" x="929" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="845.5,-961.5 1012.5,-961.5 "/>
<text text-anchor="middle" x="929" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="845.5,-938.5 1012.5,-938.5 "/>
<text text-anchor="middle" x="929" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="845.5,-915.5 1012.5,-915.5 "/>
<text text-anchor="middle" x="929" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="845.5,-892.5 1012.5,-892.5 "/>
<text text-anchor="middle" x="929" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="845.5,-869.5 1012.5,-869.5 "/>
<text text-anchor="middle" x="929" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="845.5,-846.5 1012.5,-846.5 "/>
<text text-anchor="middle" x="929" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="845.5,-823.5 1012.5,-823.5 "/>
<text text-anchor="middle" x="929" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="845.5,-800.5 1012.5,-800.5 "/>
<text text-anchor="middle" x="929" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="845.5,-777.5 1012.5,-777.5 "/>
<text text-anchor="middle" x="929" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="1012.5,-754.5 1012.5,-1007.5 "/>
<text text-anchor="middle" x="1023" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge18" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M828.9187,-754.3546C810.9663,-595.1236 791.9837,-333.5422 849.5,-259 894.1027,-201.1941 1064.3294,-160.0421 1208.255,-134.7358"/>
<polygon fill="#000000" stroke="#000000" points="1208.8808,-138.1796 1218.1324,-133.0165 1207.6803,-131.2833 1208.8808,-138.1796"/>
<text text-anchor="middle" x="897.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- participant -->
<g id="node13" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M1470.5,-495.5C1470.5,-495.5 1774.5,-495.5 1774.5,-495.5 1780.5,-495.5 1786.5,-501.5 1786.5,-507.5 1786.5,-507.5 1786.5,-598.5 1786.5,-598.5 1786.5,-604.5 1780.5,-610.5 1774.5,-610.5 1774.5,-610.5 1470.5,-610.5 1470.5,-610.5 1464.5,-610.5 1458.5,-604.5 1458.5,-598.5 1458.5,-598.5 1458.5,-507.5 1458.5,-507.5 1458.5,-501.5 1464.5,-495.5 1470.5,-495.5"/>
<text text-anchor="middle" x="1506.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1554.5,-495.5 1554.5,-610.5 "/>
<text text-anchor="middle" x="1565" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1575.5,-495.5 1575.5,-610.5 "/>
<text text-anchor="middle" x="1670.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="1575.5,-587.5 1765.5,-587.5 "/>
<text text-anchor="middle" x="1670.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="1575.5,-564.5 1765.5,-564.5 "/>
<text text-anchor="middle" x="1670.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="1575.5,-541.5 1765.5,-541.5 "/>
<text text-anchor="middle" x="1670.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1575.5,-518.5 1765.5,-518.5 "/>
<text text-anchor="middle" x="1670.5" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1765.5,-495.5 1765.5,-610.5 "/>
<text text-anchor="middle" x="1776" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M938.9475,-754.4057C970.6659,-719.5179 1008.7578,-684.986 1050.5,-662 1117.6289,-625.0345 1305.8685,-593.6228 1448.2229,-574.1518"/>
<polygon fill="#000000" stroke="#000000" points="1448.9529,-577.5849 1458.3908,-572.7706 1448.0106,-570.6486 1448.9529,-577.5849"/>
<text text-anchor="middle" x="1271" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- sample_diagnosis -->
<g id="node4" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M383,-1220.5C383,-1220.5 816,-1220.5 816,-1220.5 822,-1220.5 828,-1226.5 828,-1232.5 828,-1232.5 828,-1645.5 828,-1645.5 828,-1651.5 822,-1657.5 816,-1657.5 816,-1657.5 383,-1657.5 383,-1657.5 377,-1657.5 371,-1651.5 371,-1645.5 371,-1645.5 371,-1232.5 371,-1232.5 371,-1226.5 377,-1220.5 383,-1220.5"/>
<text text-anchor="middle" x="442.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="514,-1220.5 514,-1657.5 "/>
<text text-anchor="middle" x="524.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="535,-1220.5 535,-1657.5 "/>
<text text-anchor="middle" x="671" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="535,-1634.5 807,-1634.5 "/>
<text text-anchor="middle" x="671" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="535,-1611.5 807,-1611.5 "/>
<text text-anchor="middle" x="671" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="535,-1588.5 807,-1588.5 "/>
<text text-anchor="middle" x="671" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="535,-1565.5 807,-1565.5 "/>
<text text-anchor="middle" x="671" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="535,-1542.5 807,-1542.5 "/>
<text text-anchor="middle" x="671" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="535,-1519.5 807,-1519.5 "/>
<text text-anchor="middle" x="671" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="535,-1496.5 807,-1496.5 "/>
<text text-anchor="middle" x="671" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="535,-1473.5 807,-1473.5 "/>
<text text-anchor="middle" x="671" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="535,-1450.5 807,-1450.5 "/>
<text text-anchor="middle" x="671" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="535,-1427.5 807,-1427.5 "/>
<text text-anchor="middle" x="671" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="535,-1404.5 807,-1404.5 "/>
<text text-anchor="middle" x="671" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="535,-1381.5 807,-1381.5 "/>
<text text-anchor="middle" x="671" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="535,-1358.5 807,-1358.5 "/>
<text text-anchor="middle" x="671" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="535,-1335.5 807,-1335.5 "/>
<text text-anchor="middle" x="671" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="535,-1312.5 807,-1312.5 "/>
<text text-anchor="middle" x="671" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="535,-1289.5 807,-1289.5 "/>
<text text-anchor="middle" x="671" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="535,-1266.5 807,-1266.5 "/>
<text text-anchor="middle" x="671" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="535,-1243.5 807,-1243.5 "/>
<text text-anchor="middle" x="671" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="807,-1220.5 807,-1657.5 "/>
<text text-anchor="middle" x="817.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M752.6639,-1220.2926C778.2508,-1194.117 806.3724,-1169.9921 836.5,-1151 916.2891,-1100.7019 962.3226,-1149.6768 1042.5,-1100 1094.8939,-1067.5375 1140.0412,-1015.3941 1172.7317,-970.1303"/>
<polygon fill="#000000" stroke="#000000" points="1175.7392,-971.9406 1178.6897,-961.7649 1170.0375,-967.8797 1175.7392,-971.9406"/>
<text text-anchor="middle" x="1076.5" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
<!-- study_admin -->
<g id="node6" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M870.5,-259.5C870.5,-259.5 1196.5,-259.5 1196.5,-259.5 1202.5,-259.5 1208.5,-265.5 1208.5,-271.5 1208.5,-271.5 1208.5,-431.5 1208.5,-431.5 1208.5,-437.5 1202.5,-443.5 1196.5,-443.5 1196.5,-443.5 870.5,-443.5 870.5,-443.5 864.5,-443.5 858.5,-437.5 858.5,-431.5 858.5,-431.5 858.5,-271.5 858.5,-271.5 858.5,-265.5 864.5,-259.5 870.5,-259.5"/>
<text text-anchor="middle" x="912.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="966.5,-259.5 966.5,-443.5 "/>
<text text-anchor="middle" x="977" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="987.5,-259.5 987.5,-443.5 "/>
<text text-anchor="middle" x="1087.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="987.5,-420.5 1187.5,-420.5 "/>
<text text-anchor="middle" x="1087.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="987.5,-397.5 1187.5,-397.5 "/>
<text text-anchor="middle" x="1087.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="987.5,-374.5 1187.5,-374.5 "/>
<text text-anchor="middle" x="1087.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="987.5,-351.5 1187.5,-351.5 "/>
<text text-anchor="middle" x="1087.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="987.5,-328.5 1187.5,-328.5 "/>
<text text-anchor="middle" x="1087.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="987.5,-305.5 1187.5,-305.5 "/>
<text text-anchor="middle" x="1087.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="987.5,-282.5 1187.5,-282.5 "/>
<text text-anchor="middle" x="1087.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="1187.5,-259.5 1187.5,-443.5 "/>
<text text-anchor="middle" x="1198" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge16" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1079.241,-259.4337C1088.0811,-247.1183 1098.1754,-235.4877 1109.5,-226 1138.6733,-201.5588 1173.2914,-181.6783 1208.7371,-165.6146"/>
<polygon fill="#000000" stroke="#000000" points="1210.5298,-168.6486 1218.2561,-161.3991 1207.6953,-162.2482 1210.5298,-168.6486"/>
<text text-anchor="middle" x="1166" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- therapeutic_procedure -->
<g id="node7" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M1427,-823.5C1427,-823.5 1784,-823.5 1784,-823.5 1790,-823.5 1796,-829.5 1796,-835.5 1796,-835.5 1796,-926.5 1796,-926.5 1796,-932.5 1790,-938.5 1784,-938.5 1784,-938.5 1427,-938.5 1427,-938.5 1421,-938.5 1415,-932.5 1415,-926.5 1415,-926.5 1415,-835.5 1415,-835.5 1415,-829.5 1421,-823.5 1427,-823.5"/>
<text text-anchor="middle" x="1505.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="1596,-823.5 1596,-938.5 "/>
<text text-anchor="middle" x="1606.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1617,-823.5 1617,-938.5 "/>
<text text-anchor="middle" x="1696" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="1617,-915.5 1775,-915.5 "/>
<text text-anchor="middle" x="1696" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="1617,-892.5 1775,-892.5 "/>
<text text-anchor="middle" x="1696" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1617,-869.5 1775,-869.5 "/>
<text text-anchor="middle" x="1696" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="1617,-846.5 1775,-846.5 "/>
<text text-anchor="middle" x="1696" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1775,-823.5 1775,-938.5 "/>
<text text-anchor="middle" x="1785.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1608.8545,-823.0565C1611.5898,-775.0786 1615.4806,-705.1189 1618.5,-644 1618.8689,-636.5321 1619.238,-628.7186 1619.5947,-620.9419"/>
<polygon fill="#000000" stroke="#000000" points="1623.0991,-620.9202 1620.0552,-610.772 1616.1063,-620.6034 1623.0991,-620.9202"/>
<text text-anchor="middle" x="1712.5" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge11" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1224.4287,-800.2958C1218.2986,-654.2956 1211.6567,-352.7485 1255.5,-259 1262.7134,-243.5759 1272.239,-228.9903 1283.1065,-215.3918"/>
<polygon fill="#000000" stroke="#000000" points="1285.962,-217.4315 1289.653,-207.5003 1280.5745,-212.9622 1285.962,-217.4315"/>
<text text-anchor="middle" x="1260" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1272.7819,-800.3592C1303.5628,-752.256 1349.1356,-694.4112 1405.5,-662 1451.1089,-635.7735 1475.0229,-666.67 1522.5,-644 1524.8536,-642.8762 1537.6285,-631.5621 1553.3041,-617.2695"/>
<polygon fill="#000000" stroke="#000000" points="1555.6674,-619.8512 1560.6836,-610.519 1550.9427,-614.6862 1555.6674,-619.8512"/>
<text text-anchor="middle" x="1577" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sequencing_file -->
<g id="node9" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M858,-1151.5C858,-1151.5 1327,-1151.5 1327,-1151.5 1333,-1151.5 1339,-1157.5 1339,-1163.5 1339,-1163.5 1339,-1714.5 1339,-1714.5 1339,-1720.5 1333,-1726.5 1327,-1726.5 1327,-1726.5 858,-1726.5 858,-1726.5 852,-1726.5 846,-1720.5 846,-1714.5 846,-1714.5 846,-1163.5 846,-1163.5 846,-1157.5 852,-1151.5 858,-1151.5"/>
<text text-anchor="middle" x="910" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="974,-1151.5 974,-1726.5 "/>
<text text-anchor="middle" x="984.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="995,-1151.5 995,-1726.5 "/>
<text text-anchor="middle" x="1156.5" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="995,-1703.5 1318,-1703.5 "/>
<text text-anchor="middle" x="1156.5" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="995,-1680.5 1318,-1680.5 "/>
<text text-anchor="middle" x="1156.5" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="995,-1657.5 1318,-1657.5 "/>
<text text-anchor="middle" x="1156.5" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="995,-1634.5 1318,-1634.5 "/>
<text text-anchor="middle" x="1156.5" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="995,-1611.5 1318,-1611.5 "/>
<text text-anchor="middle" x="1156.5" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="995,-1588.5 1318,-1588.5 "/>
<text text-anchor="middle" x="1156.5" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="995,-1565.5 1318,-1565.5 "/>
<text text-anchor="middle" x="1156.5" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="995,-1542.5 1318,-1542.5 "/>
<text text-anchor="middle" x="1156.5" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="995,-1519.5 1318,-1519.5 "/>
<text text-anchor="middle" x="1156.5" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="995,-1496.5 1318,-1496.5 "/>
<text text-anchor="middle" x="1156.5" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="995,-1473.5 1318,-1473.5 "/>
<text text-anchor="middle" x="1156.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="995,-1450.5 1318,-1450.5 "/>
<text text-anchor="middle" x="1156.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="995,-1427.5 1318,-1427.5 "/>
<text text-anchor="middle" x="1156.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="995,-1404.5 1318,-1404.5 "/>
<text text-anchor="middle" x="1156.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="995,-1381.5 1318,-1381.5 "/>
<text text-anchor="middle" x="1156.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="995,-1358.5 1318,-1358.5 "/>
<text text-anchor="middle" x="1156.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="995,-1335.5 1318,-1335.5 "/>
<text text-anchor="middle" x="1156.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="995,-1312.5 1318,-1312.5 "/>
<text text-anchor="middle" x="1156.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="995,-1289.5 1318,-1289.5 "/>
<text text-anchor="middle" x="1156.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="995,-1266.5 1318,-1266.5 "/>
<text text-anchor="middle" x="1156.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="995,-1243.5 1318,-1243.5 "/>
<text text-anchor="middle" x="1156.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="995,-1220.5 1318,-1220.5 "/>
<text text-anchor="middle" x="1156.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="995,-1197.5 1318,-1197.5 "/>
<text text-anchor="middle" x="1156.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="995,-1174.5 1318,-1174.5 "/>
<text text-anchor="middle" x="1156.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="1318,-1151.5 1318,-1726.5 "/>
<text text-anchor="middle" x="1328.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1162.5915,-1151.4187C1178.5308,-1086.0205 1194.3168,-1021.2516 1206.4419,-971.5032"/>
<polygon fill="#000000" stroke="#000000" points="1209.8495,-972.3025 1208.817,-961.7581 1203.0485,-970.6449 1209.8495,-972.3025"/>
<text text-anchor="middle" x="1236" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- study_arm -->
<g id="node10" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M1277,-317C1277,-317 1574,-317 1574,-317 1580,-317 1586,-323 1586,-329 1586,-329 1586,-374 1586,-374 1586,-380 1580,-386 1574,-386 1574,-386 1277,-386 1277,-386 1271,-386 1265,-380 1265,-374 1265,-374 1265,-329 1265,-329 1265,-323 1271,-317 1277,-317"/>
<text text-anchor="middle" x="1311" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="1357,-317 1357,-386 "/>
<text text-anchor="middle" x="1367.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1378,-317 1378,-386 "/>
<text text-anchor="middle" x="1471.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="1378,-363 1565,-363 "/>
<text text-anchor="middle" x="1471.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="1378,-340 1565,-340 "/>
<text text-anchor="middle" x="1471.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="1565,-317 1565,-386 "/>
<text text-anchor="middle" x="1575.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge3" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1425.5,-316.8256C1425.5,-290.8629 1425.5,-253.7725 1425.5,-217.8091"/>
<polygon fill="#000000" stroke="#000000" points="1429.0001,-217.7056 1425.5,-207.7056 1422.0001,-217.7056 1429.0001,-217.7056"/>
<text text-anchor="middle" x="1474" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- diagnosis -->
<g id="node11" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1826.5,-662.5C1826.5,-662.5 2200.5,-662.5 2200.5,-662.5 2206.5,-662.5 2212.5,-668.5 2212.5,-674.5 2212.5,-674.5 2212.5,-1087.5 2212.5,-1087.5 2212.5,-1093.5 2206.5,-1099.5 2200.5,-1099.5 2200.5,-1099.5 1826.5,-1099.5 1826.5,-1099.5 1820.5,-1099.5 1814.5,-1093.5 1814.5,-1087.5 1814.5,-1087.5 1814.5,-674.5 1814.5,-674.5 1814.5,-668.5 1820.5,-662.5 1826.5,-662.5"/>
<text text-anchor="middle" x="1856.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1898.5,-662.5 1898.5,-1099.5 "/>
<text text-anchor="middle" x="1909" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1919.5,-662.5 1919.5,-1099.5 "/>
<text text-anchor="middle" x="2055.5" y="-1084.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1919.5,-1076.5 2191.5,-1076.5 "/>
<text text-anchor="middle" x="2055.5" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1919.5,-1053.5 2191.5,-1053.5 "/>
<text text-anchor="middle" x="2055.5" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1919.5,-1030.5 2191.5,-1030.5 "/>
<text text-anchor="middle" x="2055.5" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1919.5,-1007.5 2191.5,-1007.5 "/>
<text text-anchor="middle" x="2055.5" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="1919.5,-984.5 2191.5,-984.5 "/>
<text text-anchor="middle" x="2055.5" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="1919.5,-961.5 2191.5,-961.5 "/>
<text text-anchor="middle" x="2055.5" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="1919.5,-938.5 2191.5,-938.5 "/>
<text text-anchor="middle" x="2055.5" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1919.5,-915.5 2191.5,-915.5 "/>
<text text-anchor="middle" x="2055.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1919.5,-892.5 2191.5,-892.5 "/>
<text text-anchor="middle" x="2055.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="1919.5,-869.5 2191.5,-869.5 "/>
<text text-anchor="middle" x="2055.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="1919.5,-846.5 2191.5,-846.5 "/>
<text text-anchor="middle" x="2055.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="1919.5,-823.5 2191.5,-823.5 "/>
<text text-anchor="middle" x="2055.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="1919.5,-800.5 2191.5,-800.5 "/>
<text text-anchor="middle" x="2055.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1919.5,-777.5 2191.5,-777.5 "/>
<text text-anchor="middle" x="2055.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="1919.5,-754.5 2191.5,-754.5 "/>
<text text-anchor="middle" x="2055.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="1919.5,-731.5 2191.5,-731.5 "/>
<text text-anchor="middle" x="2055.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1919.5,-708.5 2191.5,-708.5 "/>
<text text-anchor="middle" x="2055.5" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1919.5,-685.5 2191.5,-685.5 "/>
<text text-anchor="middle" x="2055.5" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="2191.5,-662.5 2191.5,-1099.5 "/>
<text text-anchor="middle" x="2202" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1849.2775,-662.3877C1836.4689,-650.4081 1823.1763,-639.1433 1809.5,-629 1803.2658,-624.3763 1796.7106,-619.9837 1789.9366,-615.817"/>
<polygon fill="#000000" stroke="#000000" points="1791.6327,-612.7536 1781.2468,-610.6594 1788.0599,-618.7732 1791.6327,-612.7536"/>
<text text-anchor="middle" x="1868" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- methylation_array_file -->
<g id="node12" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M1369,-1324C1369,-1324 1736,-1324 1736,-1324 1742,-1324 1748,-1330 1748,-1336 1748,-1336 1748,-1542 1748,-1542 1748,-1548 1742,-1554 1736,-1554 1736,-1554 1369,-1554 1369,-1554 1363,-1554 1357,-1548 1357,-1542 1357,-1542 1357,-1336 1357,-1336 1357,-1330 1363,-1324 1369,-1324"/>
<text text-anchor="middle" x="1446" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="1535,-1324 1535,-1554 "/>
<text text-anchor="middle" x="1545.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1556,-1324 1556,-1554 "/>
<text text-anchor="middle" x="1641.5" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1556,-1531 1727,-1531 "/>
<text text-anchor="middle" x="1641.5" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1556,-1508 1727,-1508 "/>
<text text-anchor="middle" x="1641.5" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1556,-1485 1727,-1485 "/>
<text text-anchor="middle" x="1641.5" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1556,-1462 1727,-1462 "/>
<text text-anchor="middle" x="1641.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1556,-1439 1727,-1439 "/>
<text text-anchor="middle" x="1641.5" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1556,-1416 1727,-1416 "/>
<text text-anchor="middle" x="1641.5" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1556,-1393 1727,-1393 "/>
<text text-anchor="middle" x="1641.5" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1556,-1370 1727,-1370 "/>
<text text-anchor="middle" x="1641.5" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="1556,-1347 1727,-1347 "/>
<text text-anchor="middle" x="1641.5" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="1727,-1324 1727,-1554 "/>
<text text-anchor="middle" x="1737.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1485.5635,-1323.7205C1424.7379,-1218.9652 1336.2436,-1066.5585 1280.5598,-970.6585"/>
<polygon fill="#000000" stroke="#000000" points="1283.4906,-968.7358 1275.4425,-961.8453 1277.4371,-972.2507 1283.4906,-968.7358"/>
<text text-anchor="middle" x="1463" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge7" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1628.7847,-495.2651C1632.915,-433.4623 1631.9062,-334.1656 1594.5,-259 1586.8639,-243.6557 1577.0168,-229.0888 1565.9181,-215.4718"/>
<polygon fill="#000000" stroke="#000000" points="1568.3702,-212.9506 1559.2461,-207.5654 1563.0205,-217.4651 1568.3702,-212.9506"/>
<text text-anchor="middle" x="1681" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge6" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1528.0121,-495.3192C1520.7717,-489.4914 1513.8291,-483.3623 1507.5,-477 1483.5274,-452.9018 1462.6728,-420.7282 1447.9942,-394.9907"/>
<polygon fill="#000000" stroke="#000000" points="1451.0016,-393.1976 1443.0647,-386.1793 1444.8925,-396.6153 1451.0016,-393.1976"/>
<text text-anchor="middle" x="1558" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- publication -->
<g id="node14" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M1753.5,-333.5C1753.5,-333.5 1963.5,-333.5 1963.5,-333.5 1969.5,-333.5 1975.5,-339.5 1975.5,-345.5 1975.5,-345.5 1975.5,-357.5 1975.5,-357.5 1975.5,-363.5 1969.5,-369.5 1963.5,-369.5 1963.5,-369.5 1753.5,-369.5 1753.5,-369.5 1747.5,-369.5 1741.5,-363.5 1741.5,-357.5 1741.5,-357.5 1741.5,-345.5 1741.5,-345.5 1741.5,-339.5 1747.5,-333.5 1753.5,-333.5"/>
<text text-anchor="middle" x="1790" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="1838.5,-333.5 1838.5,-369.5 "/>
<text text-anchor="middle" x="1849" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1859.5,-333.5 1859.5,-369.5 "/>
<text text-anchor="middle" x="1907" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="1954.5,-333.5 1954.5,-369.5 "/>
<text text-anchor="middle" x="1965" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge1" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1835.0368,-333.411C1809.3345,-313.9614 1766.5567,-282.6513 1727.5,-259 1700.2035,-242.4703 1670.943,-225.9985 1641.7706,-210.2998"/>
<polygon fill="#000000" stroke="#000000" points="1643.19,-207.0896 1632.7222,-205.4534 1639.8849,-213.2603 1643.19,-207.0896"/>
<text text-anchor="middle" x="1747.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- imaging_file -->
<g id="node15" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M1778.5,-1278C1778.5,-1278 2112.5,-1278 2112.5,-1278 2118.5,-1278 2124.5,-1284 2124.5,-1290 2124.5,-1290 2124.5,-1588 2124.5,-1588 2124.5,-1594 2118.5,-1600 2112.5,-1600 2112.5,-1600 1778.5,-1600 1778.5,-1600 1772.5,-1600 1766.5,-1594 1766.5,-1588 1766.5,-1588 1766.5,-1290 1766.5,-1290 1766.5,-1284 1772.5,-1278 1778.5,-1278"/>
<text text-anchor="middle" x="1818.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="1870.5,-1278 1870.5,-1600 "/>
<text text-anchor="middle" x="1881" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1891.5,-1278 1891.5,-1600 "/>
<text text-anchor="middle" x="1997.5" y="-1584.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1891.5,-1577 2103.5,-1577 "/>
<text text-anchor="middle" x="1997.5" y="-1561.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1891.5,-1554 2103.5,-1554 "/>
<text text-anchor="middle" x="1997.5" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1891.5,-1531 2103.5,-1531 "/>
<text text-anchor="middle" x="1997.5" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1891.5,-1508 2103.5,-1508 "/>
<text text-anchor="middle" x="1997.5" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1891.5,-1485 2103.5,-1485 "/>
<text text-anchor="middle" x="1997.5" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1891.5,-1462 2103.5,-1462 "/>
<text text-anchor="middle" x="1997.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1891.5,-1439 2103.5,-1439 "/>
<text text-anchor="middle" x="1997.5" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1891.5,-1416 2103.5,-1416 "/>
<text text-anchor="middle" x="1997.5" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1891.5,-1393 2103.5,-1393 "/>
<text text-anchor="middle" x="1997.5" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="1891.5,-1370 2103.5,-1370 "/>
<text text-anchor="middle" x="1997.5" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="1891.5,-1347 2103.5,-1347 "/>
<text text-anchor="middle" x="1997.5" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="1891.5,-1324 2103.5,-1324 "/>
<text text-anchor="middle" x="1997.5" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1891.5,-1301 2103.5,-1301 "/>
<text text-anchor="middle" x="1997.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="2103.5,-1278 2103.5,-1600 "/>
<text text-anchor="middle" x="2114" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1871.975,-1277.7319C1842.5986,-1229.9309 1804.2236,-1182.1032 1756.5,-1151 1681.7585,-1102.2883 1646.8269,-1130.5489 1558.5,-1118 1490.7118,-1108.3691 1465.4525,-1133.071 1405.5,-1100 1351.6022,-1070.2689 1307.9045,-1016.8049 1277.4119,-970.1463"/>
<polygon fill="#000000" stroke="#000000" points="1280.2212,-968.0436 1271.8725,-961.5206 1274.3312,-971.8262 1280.2212,-968.0436"/>
<text text-anchor="middle" x="1774" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- synonym -->
<g id="node16" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M2155,-1416C2155,-1416 2456,-1416 2456,-1416 2462,-1416 2468,-1422 2468,-1428 2468,-1428 2468,-1450 2468,-1450 2468,-1456 2462,-1462 2456,-1462 2456,-1462 2155,-1462 2155,-1462 2149,-1462 2143,-1456 2143,-1450 2143,-1450 2143,-1428 2143,-1428 2143,-1422 2149,-1416 2155,-1416"/>
<text text-anchor="middle" x="2183" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="2223,-1416 2223,-1462 "/>
<text text-anchor="middle" x="2233.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2244,-1416 2244,-1462 "/>
<text text-anchor="middle" x="2345.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="2244,-1439 2447,-1439 "/>
<text text-anchor="middle" x="2345.5" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="2447,-1416 2447,-1462 "/>
<text text-anchor="middle" x="2457.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge15" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2309.4825,-1415.9615C2322.2762,-1339.8758 2361.5,-1089.5973 2361.5,-881 2361.5,-881 2361.5,-881 2361.5,-351.5 2361.5,-203.6267 1919.342,-142.1054 1642.8226,-118.0894"/>
<polygon fill="#000000" stroke="#000000" points="1642.9108,-114.5841 1632.6481,-117.2161 1642.3121,-121.5585 1642.9108,-114.5841"/>
<text text-anchor="middle" x="2404" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2299.3481,-1415.7101C2283.0901,-1359.2518 2233.2258,-1215.0351 2133.5,-1151 2020.2564,-1078.2849 1966.6943,-1128.1731 1832.5,-1118 1785.1493,-1114.4104 1447.9105,-1121.3618 1405.5,-1100 1349.8968,-1071.9931 1305.8118,-1017.6533 1275.5457,-970.1117"/>
<polygon fill="#000000" stroke="#000000" points="1278.5121,-968.254 1270.244,-961.629 1272.5761,-971.964 1278.5121,-968.254"/>
<text text-anchor="middle" x="2143" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2302.2635,-1415.6048C2294.7153,-1360.6167 2275.5937,-1218.8221 2262.5,-1100 2257.1461,-1051.4147 2254.5333,-698.0278 2221.5,-662 2165.4496,-600.8687 1953.0279,-573.7255 1797.0102,-561.8722"/>
<polygon fill="#000000" stroke="#000000" points="1797.0497,-558.3656 1786.8174,-561.1134 1796.5299,-565.3463 1797.0497,-558.3656"/>
<text text-anchor="middle" x="2305" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study_funding -->
<g id="node17" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M2402,-317C2402,-317 2781,-317 2781,-317 2787,-317 2793,-323 2793,-329 2793,-329 2793,-374 2793,-374 2793,-380 2787,-386 2781,-386 2781,-386 2402,-386 2402,-386 2396,-386 2390,-380 2390,-374 2390,-374 2390,-329 2390,-329 2390,-323 2396,-317 2402,-317"/>
<text text-anchor="middle" x="2449.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="2509,-317 2509,-386 "/>
<text text-anchor="middle" x="2519.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2530,-317 2530,-386 "/>
<text text-anchor="middle" x="2651" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="2530,-363 2772,-363 "/>
<text text-anchor="middle" x="2651" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="2530,-340 2772,-340 "/>
<text text-anchor="middle" x="2651" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="2772,-317 2772,-386 "/>
<text text-anchor="middle" x="2782.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge21" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2544.8429,-316.9646C2502.7958,-287.7149 2438.1341,-247.2464 2375.5,-226 2244.078,-181.4198 1880.17,-143.1087 1642.8133,-121.8435"/>
<polygon fill="#000000" stroke="#000000" points="1642.9364,-118.3407 1632.6648,-120.9378 1642.314,-125.313 1642.9364,-118.3407"/>
<text text-anchor="middle" x="2474.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
</g>
</svg>
</div>
