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
<svg width="5214pt" height="1988pt"
 viewBox="0.00 0.00 5213.58 1988.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1984)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1984 5209.5774,-1984 5209.5774,4 -4,4"/>
<!-- clinical_measure_file -->
<g id="node1" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M54.0774,-904C54.0774,-904 406.0774,-904 406.0774,-904 412.0774,-904 418.0774,-910 418.0774,-916 418.0774,-916 418.0774,-1145 418.0774,-1145 418.0774,-1151 412.0774,-1157 406.0774,-1157 406.0774,-1157 54.0774,-1157 54.0774,-1157 48.0774,-1157 42.0774,-1151 42.0774,-1145 42.0774,-1145 42.0774,-916 42.0774,-916 42.0774,-910 48.0774,-904 54.0774,-904"/>
<text text-anchor="middle" x="125.5774" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="209.0774,-904 209.0774,-1157 "/>
<text text-anchor="middle" x="219.5774" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="230.0774,-904 230.0774,-1157 "/>
<text text-anchor="middle" x="313.5774" y="-1141.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="230.0774,-1134 397.0774,-1134 "/>
<text text-anchor="middle" x="313.5774" y="-1118.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="230.0774,-1111 397.0774,-1111 "/>
<text text-anchor="middle" x="313.5774" y="-1095.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="230.0774,-1088 397.0774,-1088 "/>
<text text-anchor="middle" x="313.5774" y="-1072.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="230.0774,-1065 397.0774,-1065 "/>
<text text-anchor="middle" x="313.5774" y="-1049.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="230.0774,-1042 397.0774,-1042 "/>
<text text-anchor="middle" x="313.5774" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="230.0774,-1019 397.0774,-1019 "/>
<text text-anchor="middle" x="313.5774" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="230.0774,-996 397.0774,-996 "/>
<text text-anchor="middle" x="313.5774" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="230.0774,-973 397.0774,-973 "/>
<text text-anchor="middle" x="313.5774" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="230.0774,-950 397.0774,-950 "/>
<text text-anchor="middle" x="313.5774" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="230.0774,-927 397.0774,-927 "/>
<text text-anchor="middle" x="313.5774" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="397.0774,-904 397.0774,-1157 "/>
<text text-anchor="middle" x="407.5774" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node14" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M1118.0774,-.5C1118.0774,-.5 1508.0774,-.5 1508.0774,-.5 1514.0774,-.5 1520.0774,-6.5 1520.0774,-12.5 1520.0774,-12.5 1520.0774,-287.5 1520.0774,-287.5 1520.0774,-293.5 1514.0774,-299.5 1508.0774,-299.5 1508.0774,-299.5 1118.0774,-299.5 1118.0774,-299.5 1112.0774,-299.5 1106.0774,-293.5 1106.0774,-287.5 1106.0774,-287.5 1106.0774,-12.5 1106.0774,-12.5 1106.0774,-6.5 1112.0774,-.5 1118.0774,-.5"/>
<text text-anchor="middle" x="1134.0774" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="1162.0774,-.5 1162.0774,-299.5 "/>
<text text-anchor="middle" x="1172.5774" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1183.0774,-.5 1183.0774,-299.5 "/>
<text text-anchor="middle" x="1341.0774" y="-284.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="1183.0774,-276.5 1499.0774,-276.5 "/>
<text text-anchor="middle" x="1341.0774" y="-261.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="1183.0774,-253.5 1499.0774,-253.5 "/>
<text text-anchor="middle" x="1341.0774" y="-238.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_shorthand</text>
<polyline fill="none" stroke="#000000" points="1183.0774,-230.5 1499.0774,-230.5 "/>
<text text-anchor="middle" x="1341.0774" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="1183.0774,-207.5 1499.0774,-207.5 "/>
<text text-anchor="middle" x="1341.0774" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="1183.0774,-184.5 1499.0774,-184.5 "/>
<text text-anchor="middle" x="1341.0774" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="1183.0774,-161.5 1499.0774,-161.5 "/>
<text text-anchor="middle" x="1341.0774" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="1183.0774,-138.5 1499.0774,-138.5 "/>
<text text-anchor="middle" x="1341.0774" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="1183.0774,-115.5 1499.0774,-115.5 "/>
<text text-anchor="middle" x="1341.0774" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="1183.0774,-92.5 1499.0774,-92.5 "/>
<text text-anchor="middle" x="1341.0774" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="1183.0774,-69.5 1499.0774,-69.5 "/>
<text text-anchor="middle" x="1341.0774" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="1183.0774,-46.5 1499.0774,-46.5 "/>
<text text-anchor="middle" x="1341.0774" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="1183.0774,-23.5 1499.0774,-23.5 "/>
<text text-anchor="middle" x="1341.0774" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="1499.0774,-.5 1499.0774,-299.5 "/>
<text text-anchor="middle" x="1509.5774" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge11" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M244.5074,-903.6488C258.3057,-835.1751 285.2941,-753.5481 338.0774,-698 496.709,-531.059 620.0742,-623.5803 822.0774,-513 928.9275,-454.5083 1038.7794,-375.3912 1127.4112,-305.9487"/>
<polygon fill="#000000" stroke="#000000" points="1129.6775,-308.6192 1135.3776,-299.6884 1125.3523,-303.1153 1129.6775,-308.6192"/>
<text text-anchor="middle" x="872.0774" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- participant -->
<g id="node15" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M1441.0774,-564.5C1441.0774,-564.5 1745.0774,-564.5 1745.0774,-564.5 1751.0774,-564.5 1757.0774,-570.5 1757.0774,-576.5 1757.0774,-576.5 1757.0774,-667.5 1757.0774,-667.5 1757.0774,-673.5 1751.0774,-679.5 1745.0774,-679.5 1745.0774,-679.5 1441.0774,-679.5 1441.0774,-679.5 1435.0774,-679.5 1429.0774,-673.5 1429.0774,-667.5 1429.0774,-667.5 1429.0774,-576.5 1429.0774,-576.5 1429.0774,-570.5 1435.0774,-564.5 1441.0774,-564.5"/>
<text text-anchor="middle" x="1477.0774" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1525.0774,-564.5 1525.0774,-679.5 "/>
<text text-anchor="middle" x="1535.5774" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1546.0774,-564.5 1546.0774,-679.5 "/>
<text text-anchor="middle" x="1641.0774" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="1546.0774,-656.5 1736.0774,-656.5 "/>
<text text-anchor="middle" x="1641.0774" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="1546.0774,-633.5 1736.0774,-633.5 "/>
<text text-anchor="middle" x="1641.0774" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="1546.0774,-610.5 1736.0774,-610.5 "/>
<text text-anchor="middle" x="1641.0774" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1546.0774,-587.5 1736.0774,-587.5 "/>
<text text-anchor="middle" x="1641.0774" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1736.0774,-564.5 1736.0774,-679.5 "/>
<text text-anchor="middle" x="1746.5774" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M244.3825,-903.9871C259.6233,-831.582 291.0953,-745.8754 356.0774,-698 377.1736,-682.4574 1082.8235,-646.5441 1418.6988,-630.2755"/>
<polygon fill="#000000" stroke="#000000" points="1419.1986,-633.7555 1429.0177,-629.7763 1418.8602,-626.7637 1419.1986,-633.7555"/>
<text text-anchor="middle" x="485.5774" y="-701.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- study_admin -->
<g id="node2" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M54.0774,-351.5C54.0774,-351.5 380.0774,-351.5 380.0774,-351.5 386.0774,-351.5 392.0774,-357.5 392.0774,-363.5 392.0774,-363.5 392.0774,-500.5 392.0774,-500.5 392.0774,-506.5 386.0774,-512.5 380.0774,-512.5 380.0774,-512.5 54.0774,-512.5 54.0774,-512.5 48.0774,-512.5 42.0774,-506.5 42.0774,-500.5 42.0774,-500.5 42.0774,-363.5 42.0774,-363.5 42.0774,-357.5 48.0774,-351.5 54.0774,-351.5"/>
<text text-anchor="middle" x="96.0774" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="150.0774,-351.5 150.0774,-512.5 "/>
<text text-anchor="middle" x="160.5774" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="171.0774,-351.5 171.0774,-512.5 "/>
<text text-anchor="middle" x="271.0774" y="-497.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="171.0774,-489.5 371.0774,-489.5 "/>
<text text-anchor="middle" x="271.0774" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="171.0774,-466.5 371.0774,-466.5 "/>
<text text-anchor="middle" x="271.0774" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="171.0774,-443.5 371.0774,-443.5 "/>
<text text-anchor="middle" x="271.0774" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="171.0774,-420.5 371.0774,-420.5 "/>
<text text-anchor="middle" x="271.0774" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="171.0774,-397.5 371.0774,-397.5 "/>
<text text-anchor="middle" x="271.0774" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="171.0774,-374.5 371.0774,-374.5 "/>
<text text-anchor="middle" x="271.0774" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="371.0774,-351.5 371.0774,-512.5 "/>
<text text-anchor="middle" x="381.5774" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge28" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M392.3235,-353.9318C395.2549,-352.9268 398.1744,-351.9485 401.0774,-351 633.6747,-275.0004 908.9991,-218.7506 1095.8277,-185.3787"/>
<polygon fill="#000000" stroke="#000000" points="1096.5384,-188.8073 1105.7705,-183.6093 1095.312,-181.9155 1096.5384,-188.8073"/>
<text text-anchor="middle" x="554.5774" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- family_relationship -->
<g id="node3" class="node">
<title>family_relationship</title>
<path fill="none" stroke="#000000" d="M569.5774,-984.5C569.5774,-984.5 938.5774,-984.5 938.5774,-984.5 944.5774,-984.5 950.5774,-990.5 950.5774,-996.5 950.5774,-996.5 950.5774,-1064.5 950.5774,-1064.5 950.5774,-1070.5 944.5774,-1076.5 938.5774,-1076.5 938.5774,-1076.5 569.5774,-1076.5 569.5774,-1076.5 563.5774,-1076.5 557.5774,-1070.5 557.5774,-1064.5 557.5774,-1064.5 557.5774,-996.5 557.5774,-996.5 557.5774,-990.5 563.5774,-984.5 569.5774,-984.5"/>
<text text-anchor="middle" x="634.5774" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
<polyline fill="none" stroke="#000000" points="711.5774,-984.5 711.5774,-1076.5 "/>
<text text-anchor="middle" x="722.0774" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="732.5774,-984.5 732.5774,-1076.5 "/>
<text text-anchor="middle" x="831.0774" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_id</text>
<polyline fill="none" stroke="#000000" points="732.5774,-1053.5 929.5774,-1053.5 "/>
<text text-anchor="middle" x="831.0774" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship_id</text>
<polyline fill="none" stroke="#000000" points="732.5774,-1030.5 929.5774,-1030.5 "/>
<text text-anchor="middle" x="831.0774" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">related_to_participant_id</text>
<polyline fill="none" stroke="#000000" points="732.5774,-1007.5 929.5774,-1007.5 "/>
<text text-anchor="middle" x="831.0774" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">relationship</text>
<polyline fill="none" stroke="#000000" points="929.5774,-984.5 929.5774,-1076.5 "/>
<text text-anchor="middle" x="940.0774" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M771.989,-984.3007C800.73,-916.8021 863.8736,-792.5836 960.0774,-731 1034.3613,-683.4481 1258.5387,-653.0438 1419.0009,-636.7519"/>
<polygon fill="#000000" stroke="#000000" points="1419.3944,-640.23 1428.9941,-635.7471 1418.6941,-633.2651 1419.3944,-640.23"/>
<text text-anchor="middle" x="1111.5774" y="-701.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- methylation_array_file -->
<g id="node4" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M2952.5774,-1565.5C2952.5774,-1565.5 3319.5774,-1565.5 3319.5774,-1565.5 3325.5774,-1565.5 3331.5774,-1571.5 3331.5774,-1577.5 3331.5774,-1577.5 3331.5774,-1783.5 3331.5774,-1783.5 3331.5774,-1789.5 3325.5774,-1795.5 3319.5774,-1795.5 3319.5774,-1795.5 2952.5774,-1795.5 2952.5774,-1795.5 2946.5774,-1795.5 2940.5774,-1789.5 2940.5774,-1783.5 2940.5774,-1783.5 2940.5774,-1577.5 2940.5774,-1577.5 2940.5774,-1571.5 2946.5774,-1565.5 2952.5774,-1565.5"/>
<text text-anchor="middle" x="3029.5774" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="3118.5774,-1565.5 3118.5774,-1795.5 "/>
<text text-anchor="middle" x="3129.0774" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3139.5774,-1565.5 3139.5774,-1795.5 "/>
<text text-anchor="middle" x="3225.0774" y="-1780.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="3139.5774,-1772.5 3310.5774,-1772.5 "/>
<text text-anchor="middle" x="3225.0774" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="3139.5774,-1749.5 3310.5774,-1749.5 "/>
<text text-anchor="middle" x="3225.0774" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="3139.5774,-1726.5 3310.5774,-1726.5 "/>
<text text-anchor="middle" x="3225.0774" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="3139.5774,-1703.5 3310.5774,-1703.5 "/>
<text text-anchor="middle" x="3225.0774" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="3139.5774,-1680.5 3310.5774,-1680.5 "/>
<text text-anchor="middle" x="3225.0774" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="3139.5774,-1657.5 3310.5774,-1657.5 "/>
<text text-anchor="middle" x="3225.0774" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="3139.5774,-1634.5 3310.5774,-1634.5 "/>
<text text-anchor="middle" x="3225.0774" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="3139.5774,-1611.5 3310.5774,-1611.5 "/>
<text text-anchor="middle" x="3225.0774" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="3139.5774,-1588.5 3310.5774,-1588.5 "/>
<text text-anchor="middle" x="3225.0774" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="3310.5774,-1565.5 3310.5774,-1795.5 "/>
<text text-anchor="middle" x="3321.0774" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node16" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M3304.0774,-950C3304.0774,-950 3618.0774,-950 3618.0774,-950 3624.0774,-950 3630.0774,-956 3630.0774,-962 3630.0774,-962 3630.0774,-1099 3630.0774,-1099 3630.0774,-1105 3624.0774,-1111 3618.0774,-1111 3618.0774,-1111 3304.0774,-1111 3304.0774,-1111 3298.0774,-1111 3292.0774,-1105 3292.0774,-1099 3292.0774,-1099 3292.0774,-962 3292.0774,-962 3292.0774,-956 3298.0774,-950 3304.0774,-950"/>
<text text-anchor="middle" x="3326.0774" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="3360.0774,-950 3360.0774,-1111 "/>
<text text-anchor="middle" x="3370.5774" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3381.0774,-950 3381.0774,-1111 "/>
<text text-anchor="middle" x="3495.0774" y="-1095.8" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="3381.0774,-1088 3609.0774,-1088 "/>
<text text-anchor="middle" x="3495.0774" y="-1072.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="3381.0774,-1065 3609.0774,-1065 "/>
<text text-anchor="middle" x="3495.0774" y="-1049.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="3381.0774,-1042 3609.0774,-1042 "/>
<text text-anchor="middle" x="3495.0774" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="3381.0774,-1019 3609.0774,-1019 "/>
<text text-anchor="middle" x="3495.0774" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="3381.0774,-996 3609.0774,-996 "/>
<text text-anchor="middle" x="3495.0774" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="3381.0774,-973 3609.0774,-973 "/>
<text text-anchor="middle" x="3495.0774" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="3609.0774,-950 3609.0774,-1111 "/>
<text text-anchor="middle" x="3619.5774" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3193.6194,-1565.4159C3257.1682,-1438.3183 3358.1485,-1236.3577 3416.1423,-1120.3702"/>
<polygon fill="#000000" stroke="#000000" points="3419.416,-1121.6488 3420.7577,-1111.1393 3413.155,-1118.5183 3419.416,-1121.6488"/>
<text text-anchor="middle" x="3389.5774" y="-1351.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study_funding -->
<g id="node5" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M422.5774,-386C422.5774,-386 801.5774,-386 801.5774,-386 807.5774,-386 813.5774,-392 813.5774,-398 813.5774,-398 813.5774,-466 813.5774,-466 813.5774,-472 807.5774,-478 801.5774,-478 801.5774,-478 422.5774,-478 422.5774,-478 416.5774,-478 410.5774,-472 410.5774,-466 410.5774,-466 410.5774,-398 410.5774,-398 410.5774,-392 416.5774,-386 422.5774,-386"/>
<text text-anchor="middle" x="470.0774" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="529.5774,-386 529.5774,-478 "/>
<text text-anchor="middle" x="540.0774" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="550.5774,-386 550.5774,-478 "/>
<text text-anchor="middle" x="671.5774" y="-462.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="550.5774,-455 792.5774,-455 "/>
<text text-anchor="middle" x="671.5774" y="-439.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="550.5774,-432 792.5774,-432 "/>
<text text-anchor="middle" x="671.5774" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="550.5774,-409 792.5774,-409 "/>
<text text-anchor="middle" x="671.5774" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding_id</text>
<polyline fill="none" stroke="#000000" points="792.5774,-386 792.5774,-478 "/>
<text text-anchor="middle" x="803.0774" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge2" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M639.3944,-385.839C655.4782,-362.3626 677.8128,-335.2257 704.0774,-318 821.2769,-241.1343 973.219,-199.1459 1096.0148,-176.3682"/>
<polygon fill="#000000" stroke="#000000" points="1096.7166,-179.798 1105.9258,-174.5596 1095.4599,-172.9117 1096.7166,-179.798"/>
<text text-anchor="middle" x="766.0774" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node6" class="node">
<title>single_cell_sequencing_file</title>
<path fill="none" stroke="#000000" d="M3361.5774,-1381.5C3361.5774,-1381.5 3970.5774,-1381.5 3970.5774,-1381.5 3976.5774,-1381.5 3982.5774,-1387.5 3982.5774,-1393.5 3982.5774,-1393.5 3982.5774,-1967.5 3982.5774,-1967.5 3982.5774,-1973.5 3976.5774,-1979.5 3970.5774,-1979.5 3970.5774,-1979.5 3361.5774,-1979.5 3361.5774,-1979.5 3355.5774,-1979.5 3349.5774,-1973.5 3349.5774,-1967.5 3349.5774,-1967.5 3349.5774,-1393.5 3349.5774,-1393.5 3349.5774,-1387.5 3355.5774,-1381.5 3361.5774,-1381.5"/>
<text text-anchor="middle" x="3455.5774" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
<polyline fill="none" stroke="#000000" points="3561.5774,-1381.5 3561.5774,-1979.5 "/>
<text text-anchor="middle" x="3572.0774" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3582.5774,-1381.5 3582.5774,-1979.5 "/>
<text text-anchor="middle" x="3772.0774" y="-1964.3" font-family="Times,serif" font-size="14.00" fill="#000000">Cell_Barcode</text>
<polyline fill="none" stroke="#000000" points="3582.5774,-1956.5 3961.5774,-1956.5 "/>
<text text-anchor="middle" x="3772.0774" y="-1941.3" font-family="Times,serif" font-size="14.00" fill="#000000">Cryopreserved_Cells_in_Sample</text>
<polyline fill="none" stroke="#000000" points="3582.5774,-1933.5 3961.5774,-1933.5 "/>
<text text-anchor="middle" x="3772.0774" y="-1918.3" font-family="Times,serif" font-size="14.00" fill="#000000">Dissociation_Method</text>
<polyline fill="none" stroke="#000000" points="3582.5774,-1910.5 3961.5774,-1910.5 "/>
<text text-anchor="middle" x="3772.0774" y="-1895.3" font-family="Times,serif" font-size="14.00" fill="#000000">End_Bias</text>
<polyline fill="none" stroke="#000000" points="3582.5774,-1887.5 3961.5774,-1887.5 "/>
<text text-anchor="middle" x="3772.0774" y="-1872.3" font-family="Times,serif" font-size="14.00" fill="#000000">Input_Cells_and_Nuclei</text>
<polyline fill="none" stroke="#000000" points="3582.5774,-1864.5 3961.5774,-1864.5 "/>
<text text-anchor="middle" x="3772.0774" y="-1849.3" font-family="Times,serif" font-size="14.00" fill="#000000">Library_Construction_Method</text>
<polyline fill="none" stroke="#000000" points="3582.5774,-1841.5 3961.5774,-1841.5 "/>
<text text-anchor="middle" x="3772.0774" y="-1826.3" font-family="Times,serif" font-size="14.00" fill="#000000">Library_Preparation_Date</text>
<polyline fill="none" stroke="#000000" points="3582.5774,-1818.5 3961.5774,-1818.5 "/>
<text text-anchor="middle" x="3772.0774" y="-1803.3" font-family="Times,serif" font-size="14.00" fill="#000000">Nucleic_Acid_Capture_Date</text>
<polyline fill="none" stroke="#000000" points="3582.5774,-1795.5 3961.5774,-1795.5 "/>
<text text-anchor="middle" x="3772.0774" y="-1780.3" font-family="Times,serif" font-size="14.00" fill="#000000">Paired_End</text>
<polyline fill="none" stroke="#000000" points="3582.5774,-1772.5 3961.5774,-1772.5 "/>
<text text-anchor="middle" x="3772.0774" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">Protocols_Link</text>
<polyline fill="none" stroke="#000000" points="3582.5774,-1749.5 3961.5774,-1749.5 "/>
<text text-anchor="middle" x="3772.0774" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">Read1</text>
<polyline fill="none" stroke="#000000" points="3582.5774,-1726.5 3961.5774,-1726.5 "/>
<text text-anchor="middle" x="3772.0774" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">Read2</text>
<polyline fill="none" stroke="#000000" points="3582.5774,-1703.5 3961.5774,-1703.5 "/>
<text text-anchor="middle" x="3772.0774" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Feature_barcoding</text>
<polyline fill="none" stroke="#000000" points="3582.5774,-1680.5 3961.5774,-1680.5 "/>
<text text-anchor="middle" x="3772.0774" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Oligo_dT_Poly_dT</text>
<polyline fill="none" stroke="#000000" points="3582.5774,-1657.5 3961.5774,-1657.5 "/>
<text text-anchor="middle" x="3772.0774" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Random</text>
<polyline fill="none" stroke="#000000" points="3582.5774,-1634.5 3961.5774,-1634.5 "/>
<text text-anchor="middle" x="3772.0774" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">Sequencing_Library_Construction_Date</text>
<polyline fill="none" stroke="#000000" points="3582.5774,-1611.5 3961.5774,-1611.5 "/>
<text text-anchor="middle" x="3772.0774" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">Single_Cell_Dissociation_Date</text>
<polyline fill="none" stroke="#000000" points="3582.5774,-1588.5 3961.5774,-1588.5 "/>
<text text-anchor="middle" x="3772.0774" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">Single_Cell_Isolation_Method</text>
<polyline fill="none" stroke="#000000" points="3582.5774,-1565.5 3961.5774,-1565.5 "/>
<text text-anchor="middle" x="3772.0774" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">Spike_In</text>
<polyline fill="none" stroke="#000000" points="3582.5774,-1542.5 3961.5774,-1542.5 "/>
<text text-anchor="middle" x="3772.0774" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">Total_Number_of_Input_Cells</text>
<polyline fill="none" stroke="#000000" points="3582.5774,-1519.5 3961.5774,-1519.5 "/>
<text text-anchor="middle" x="3772.0774" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">UMI</text>
<polyline fill="none" stroke="#000000" points="3582.5774,-1496.5 3961.5774,-1496.5 "/>
<text text-anchor="middle" x="3772.0774" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="3582.5774,-1473.5 3961.5774,-1473.5 "/>
<text text-anchor="middle" x="3772.0774" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">cDNA_Length</text>
<polyline fill="none" stroke="#000000" points="3582.5774,-1450.5 3961.5774,-1450.5 "/>
<text text-anchor="middle" x="3772.0774" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">cDNA_Offset</text>
<polyline fill="none" stroke="#000000" points="3582.5774,-1427.5 3961.5774,-1427.5 "/>
<text text-anchor="middle" x="3772.0774" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="3582.5774,-1404.5 3961.5774,-1404.5 "/>
<text text-anchor="middle" x="3772.0774" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 23 properties</text>
<polyline fill="none" stroke="#000000" points="3961.5774,-1381.5 3961.5774,-1979.5 "/>
<text text-anchor="middle" x="3972.0774" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3571.6778,-1381.1842C3541.8308,-1286.5476 3511.0622,-1188.9884 3489.5797,-1120.8732"/>
<polygon fill="#000000" stroke="#000000" points="3492.8245,-1119.5252 3486.4787,-1111.041 3486.1487,-1121.6307 3492.8245,-1119.5252"/>
<text text-anchor="middle" x="3671.5774" y="-1351.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- study_arm -->
<g id="node7" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M1444.5774,-386C1444.5774,-386 1741.5774,-386 1741.5774,-386 1747.5774,-386 1753.5774,-392 1753.5774,-398 1753.5774,-398 1753.5774,-466 1753.5774,-466 1753.5774,-472 1747.5774,-478 1741.5774,-478 1741.5774,-478 1444.5774,-478 1444.5774,-478 1438.5774,-478 1432.5774,-472 1432.5774,-466 1432.5774,-466 1432.5774,-398 1432.5774,-398 1432.5774,-392 1438.5774,-386 1444.5774,-386"/>
<text text-anchor="middle" x="1478.5774" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="1524.5774,-386 1524.5774,-478 "/>
<text text-anchor="middle" x="1535.0774" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1545.5774,-386 1545.5774,-478 "/>
<text text-anchor="middle" x="1639.0774" y="-462.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="1545.5774,-455 1732.5774,-455 "/>
<text text-anchor="middle" x="1639.0774" y="-439.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="1545.5774,-432 1732.5774,-432 "/>
<text text-anchor="middle" x="1639.0774" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="1545.5774,-409 1732.5774,-409 "/>
<text text-anchor="middle" x="1639.0774" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm_id</text>
<polyline fill="none" stroke="#000000" points="1732.5774,-386 1732.5774,-478 "/>
<text text-anchor="middle" x="1743.0774" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1547.1546,-385.7492C1525.2001,-363.6379 1497.5007,-335.7407 1468.9092,-306.9449"/>
<polygon fill="#000000" stroke="#000000" points="1471.1534,-304.2377 1461.6238,-299.6075 1466.186,-309.1698 1471.1534,-304.2377"/>
<text text-anchor="middle" x="1543.5774" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- synonym -->
<g id="node8" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M303.5774,-1657.5C303.5774,-1657.5 604.5774,-1657.5 604.5774,-1657.5 610.5774,-1657.5 616.5774,-1663.5 616.5774,-1669.5 616.5774,-1669.5 616.5774,-1691.5 616.5774,-1691.5 616.5774,-1697.5 610.5774,-1703.5 604.5774,-1703.5 604.5774,-1703.5 303.5774,-1703.5 303.5774,-1703.5 297.5774,-1703.5 291.5774,-1697.5 291.5774,-1691.5 291.5774,-1691.5 291.5774,-1669.5 291.5774,-1669.5 291.5774,-1663.5 297.5774,-1657.5 303.5774,-1657.5"/>
<text text-anchor="middle" x="331.5774" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="371.5774,-1657.5 371.5774,-1703.5 "/>
<text text-anchor="middle" x="382.0774" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="392.5774,-1657.5 392.5774,-1703.5 "/>
<text text-anchor="middle" x="494.0774" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="392.5774,-1680.5 595.5774,-1680.5 "/>
<text text-anchor="middle" x="494.0774" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="595.5774,-1657.5 595.5774,-1703.5 "/>
<text text-anchor="middle" x="606.0774" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge9" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M405.9507,-1657.3662C314.295,-1610.3656 116.4115,-1494.079 33.0774,-1330 -27.3209,-1211.0802 14.0774,-1163.8787 14.0774,-1030.5 14.0774,-1030.5 14.0774,-1030.5 14.0774,-432 14.0774,-395.0229 5.9732,-376.153 33.0774,-351 183.7024,-211.2184 771.2942,-168.5783 1095.4183,-155.62"/>
<polygon fill="#000000" stroke="#000000" points="1096.0284,-159.0988 1105.8831,-155.2083 1095.7532,-152.1042 1096.0284,-159.0988"/>
<text text-anchor="middle" x="56.5774" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M452.4774,-1657.1108C443.1834,-1517.8112 398.7397,-801.1712 463.0774,-731 467.0792,-726.6353 1102.5959,-667.3315 1418.6815,-638.0829"/>
<polygon fill="#000000" stroke="#000000" points="1419.2292,-641.5473 1428.8642,-637.1409 1418.5843,-634.5771 1419.2292,-641.5473"/>
<text text-anchor="middle" x="505.5774" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M552.4804,-1657.4279C794.785,-1601.4568 1440.2458,-1457.4593 1986.0774,-1381 2156.5939,-1357.1143 2200.1333,-1357.037 2372.0774,-1348 2422.684,-1345.3402 3240.3119,-1355.5479 3284.0774,-1330 3361.4197,-1284.8516 3408.5475,-1191.5284 3434.5149,-1120.9825"/>
<polygon fill="#000000" stroke="#000000" points="3437.9472,-1121.7811 3438.0395,-1111.1867 3431.3606,-1119.4112 3437.9472,-1121.7811"/>
<text text-anchor="middle" x="2414.5774" y="-1351.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- sample_diagnosis -->
<g id="node9" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M4012.5774,-1542.5C4012.5774,-1542.5 4445.5774,-1542.5 4445.5774,-1542.5 4451.5774,-1542.5 4457.5774,-1548.5 4457.5774,-1554.5 4457.5774,-1554.5 4457.5774,-1806.5 4457.5774,-1806.5 4457.5774,-1812.5 4451.5774,-1818.5 4445.5774,-1818.5 4445.5774,-1818.5 4012.5774,-1818.5 4012.5774,-1818.5 4006.5774,-1818.5 4000.5774,-1812.5 4000.5774,-1806.5 4000.5774,-1806.5 4000.5774,-1554.5 4000.5774,-1554.5 4000.5774,-1548.5 4006.5774,-1542.5 4012.5774,-1542.5"/>
<text text-anchor="middle" x="4072.0774" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="4143.5774,-1542.5 4143.5774,-1818.5 "/>
<text text-anchor="middle" x="4154.0774" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4164.5774,-1542.5 4164.5774,-1818.5 "/>
<text text-anchor="middle" x="4300.5774" y="-1803.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="4164.5774,-1795.5 4436.5774,-1795.5 "/>
<text text-anchor="middle" x="4300.5774" y="-1780.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="4164.5774,-1772.5 4436.5774,-1772.5 "/>
<text text-anchor="middle" x="4300.5774" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="4164.5774,-1749.5 4436.5774,-1749.5 "/>
<text text-anchor="middle" x="4300.5774" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="4164.5774,-1726.5 4436.5774,-1726.5 "/>
<text text-anchor="middle" x="4300.5774" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="4164.5774,-1703.5 4436.5774,-1703.5 "/>
<text text-anchor="middle" x="4300.5774" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="4164.5774,-1680.5 4436.5774,-1680.5 "/>
<text text-anchor="middle" x="4300.5774" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="4164.5774,-1657.5 4436.5774,-1657.5 "/>
<text text-anchor="middle" x="4300.5774" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="4164.5774,-1634.5 4436.5774,-1634.5 "/>
<text text-anchor="middle" x="4300.5774" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="4164.5774,-1611.5 4436.5774,-1611.5 "/>
<text text-anchor="middle" x="4300.5774" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="4164.5774,-1588.5 4436.5774,-1588.5 "/>
<text text-anchor="middle" x="4300.5774" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="4164.5774,-1565.5 4436.5774,-1565.5 "/>
<text text-anchor="middle" x="4300.5774" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="4436.5774,-1542.5 4436.5774,-1818.5 "/>
<text text-anchor="middle" x="4447.0774" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M4134.2384,-1542.2194C4093.8689,-1488.5943 4044.1114,-1428.7411 3992.0774,-1381 3877.864,-1276.2096 3729.3162,-1180.9878 3618.3911,-1116.3301"/>
<polygon fill="#000000" stroke="#000000" points="3619.8685,-1113.1407 3609.4633,-1111.1448 3616.3527,-1119.1938 3619.8685,-1113.1407"/>
<text text-anchor="middle" x="4040.0774" y="-1351.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
<!-- molecular_test -->
<g id="node10" class="node">
<title>molecular_test</title>
<path fill="none" stroke="#000000" d="M981.0774,-731.5C981.0774,-731.5 1369.0774,-731.5 1369.0774,-731.5 1375.0774,-731.5 1381.0774,-737.5 1381.0774,-743.5 1381.0774,-743.5 1381.0774,-1317.5 1381.0774,-1317.5 1381.0774,-1323.5 1375.0774,-1329.5 1369.0774,-1329.5 1369.0774,-1329.5 981.0774,-1329.5 981.0774,-1329.5 975.0774,-1329.5 969.0774,-1323.5 969.0774,-1317.5 969.0774,-1317.5 969.0774,-743.5 969.0774,-743.5 969.0774,-737.5 975.0774,-731.5 981.0774,-731.5"/>
<text text-anchor="middle" x="1030.5774" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
<polyline fill="none" stroke="#000000" points="1092.0774,-731.5 1092.0774,-1329.5 "/>
<text text-anchor="middle" x="1102.5774" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1113.0774,-731.5 1113.0774,-1329.5 "/>
<text text-anchor="middle" x="1236.5774" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">aa_change</text>
<polyline fill="none" stroke="#000000" points="1113.0774,-1306.5 1360.0774,-1306.5 "/>
<text text-anchor="middle" x="1236.5774" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">antigen</text>
<polyline fill="none" stroke="#000000" points="1113.0774,-1283.5 1360.0774,-1283.5 "/>
<text text-anchor="middle" x="1236.5774" y="-1268.3" font-family="Times,serif" font-size="14.00" fill="#000000">biospecimen_type</text>
<polyline fill="none" stroke="#000000" points="1113.0774,-1260.5 1360.0774,-1260.5 "/>
<text text-anchor="middle" x="1236.5774" y="-1245.3" font-family="Times,serif" font-size="14.00" fill="#000000">blood_test_normal_range_lower</text>
<polyline fill="none" stroke="#000000" points="1113.0774,-1237.5 1360.0774,-1237.5 "/>
<text text-anchor="middle" x="1236.5774" y="-1222.3" font-family="Times,serif" font-size="14.00" fill="#000000">blood_test_normal_range_upper</text>
<polyline fill="none" stroke="#000000" points="1113.0774,-1214.5 1360.0774,-1214.5 "/>
<text text-anchor="middle" x="1236.5774" y="-1199.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_count</text>
<polyline fill="none" stroke="#000000" points="1113.0774,-1191.5 1360.0774,-1191.5 "/>
<text text-anchor="middle" x="1236.5774" y="-1176.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome</text>
<polyline fill="none" stroke="#000000" points="1113.0774,-1168.5 1360.0774,-1168.5 "/>
<text text-anchor="middle" x="1236.5774" y="-1153.3" font-family="Times,serif" font-size="14.00" fill="#000000">copy_number</text>
<polyline fill="none" stroke="#000000" points="1113.0774,-1145.5 1360.0774,-1145.5 "/>
<text text-anchor="middle" x="1236.5774" y="-1130.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytoband</text>
<polyline fill="none" stroke="#000000" points="1113.0774,-1122.5 1360.0774,-1122.5 "/>
<text text-anchor="middle" x="1236.5774" y="-1107.3" font-family="Times,serif" font-size="14.00" fill="#000000">exon</text>
<polyline fill="none" stroke="#000000" points="1113.0774,-1099.5 1360.0774,-1099.5 "/>
<text text-anchor="middle" x="1236.5774" y="-1084.3" font-family="Times,serif" font-size="14.00" fill="#000000">gene_symbol</text>
<polyline fill="none" stroke="#000000" points="1113.0774,-1076.5 1360.0774,-1076.5 "/>
<text text-anchor="middle" x="1236.5774" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">histone_family</text>
<polyline fill="none" stroke="#000000" points="1113.0774,-1053.5 1360.0774,-1053.5 "/>
<text text-anchor="middle" x="1236.5774" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">histone_variant</text>
<polyline fill="none" stroke="#000000" points="1113.0774,-1030.5 1360.0774,-1030.5 "/>
<text text-anchor="middle" x="1236.5774" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">intron</text>
<polyline fill="none" stroke="#000000" points="1113.0774,-1007.5 1360.0774,-1007.5 "/>
<text text-anchor="middle" x="1236.5774" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
<polyline fill="none" stroke="#000000" points="1113.0774,-984.5 1360.0774,-984.5 "/>
<text text-anchor="middle" x="1236.5774" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">loci_abnormal_count</text>
<polyline fill="none" stroke="#000000" points="1113.0774,-961.5 1360.0774,-961.5 "/>
<text text-anchor="middle" x="1236.5774" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">loci_count</text>
<polyline fill="none" stroke="#000000" points="1113.0774,-938.5 1360.0774,-938.5 "/>
<text text-anchor="middle" x="1236.5774" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">locus</text>
<polyline fill="none" stroke="#000000" points="1113.0774,-915.5 1360.0774,-915.5 "/>
<text text-anchor="middle" x="1236.5774" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">mismatch_repair_mutation</text>
<polyline fill="none" stroke="#000000" points="1113.0774,-892.5 1360.0774,-892.5 "/>
<text text-anchor="middle" x="1236.5774" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_analysis_method</text>
<polyline fill="none" stroke="#000000" points="1113.0774,-869.5 1360.0774,-869.5 "/>
<text text-anchor="middle" x="1236.5774" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_consequence</text>
<polyline fill="none" stroke="#000000" points="1113.0774,-846.5 1360.0774,-846.5 "/>
<text text-anchor="middle" x="1236.5774" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test_id</text>
<polyline fill="none" stroke="#000000" points="1113.0774,-823.5 1360.0774,-823.5 "/>
<text text-anchor="middle" x="1236.5774" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathogenicity</text>
<polyline fill="none" stroke="#000000" points="1113.0774,-800.5 1360.0774,-800.5 "/>
<text text-anchor="middle" x="1236.5774" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">ploidy</text>
<polyline fill="none" stroke="#000000" points="1113.0774,-777.5 1360.0774,-777.5 "/>
<text text-anchor="middle" x="1236.5774" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">second_exon</text>
<polyline fill="none" stroke="#000000" points="1113.0774,-754.5 1360.0774,-754.5 "/>
<text text-anchor="middle" x="1236.5774" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 11 properties</text>
<polyline fill="none" stroke="#000000" points="1360.0774,-731.5 1360.0774,-1329.5 "/>
<text text-anchor="middle" x="1370.5774" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1381.1153,-739.0627C1384.0834,-736.3282 1387.0711,-733.6393 1390.0774,-731 1409.6695,-713.7999 1432.4431,-698.2929 1455.5084,-684.7317"/>
<polygon fill="#000000" stroke="#000000" points="1457.4417,-687.6572 1464.3566,-679.6301 1453.9452,-681.593 1457.4417,-687.6572"/>
<text text-anchor="middle" x="1494.0774" y="-701.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- follow_up -->
<g id="node11" class="node">
<title>follow_up</title>
<path fill="none" stroke="#000000" d="M1411.5774,-927C1411.5774,-927 1774.5774,-927 1774.5774,-927 1780.5774,-927 1786.5774,-933 1786.5774,-939 1786.5774,-939 1786.5774,-1122 1786.5774,-1122 1786.5774,-1128 1780.5774,-1134 1774.5774,-1134 1774.5774,-1134 1411.5774,-1134 1411.5774,-1134 1405.5774,-1134 1399.5774,-1128 1399.5774,-1122 1399.5774,-1122 1399.5774,-939 1399.5774,-939 1399.5774,-933 1405.5774,-927 1411.5774,-927"/>
<text text-anchor="middle" x="1442.0774" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
<polyline fill="none" stroke="#000000" points="1484.5774,-927 1484.5774,-1134 "/>
<text text-anchor="middle" x="1495.0774" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1505.5774,-927 1505.5774,-1134 "/>
<text text-anchor="middle" x="1635.5774" y="-1118.8" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event</text>
<polyline fill="none" stroke="#000000" points="1505.5774,-1111 1765.5774,-1111 "/>
<text text-anchor="middle" x="1635.5774" y="-1095.8" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity</text>
<polyline fill="none" stroke="#000000" points="1505.5774,-1088 1765.5774,-1088 "/>
<text text-anchor="middle" x="1635.5774" y="-1072.8" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity_method_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1505.5774,-1065 1765.5774,-1065 "/>
<text text-anchor="middle" x="1635.5774" y="-1049.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_follow_up</text>
<polyline fill="none" stroke="#000000" points="1505.5774,-1042 1765.5774,-1042 "/>
<text text-anchor="middle" x="1635.5774" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_response</text>
<polyline fill="none" stroke="#000000" points="1505.5774,-1019 1765.5774,-1019 "/>
<text text-anchor="middle" x="1635.5774" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_category</text>
<polyline fill="none" stroke="#000000" points="1505.5774,-996 1765.5774,-996 "/>
<text text-anchor="middle" x="1635.5774" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_id</text>
<polyline fill="none" stroke="#000000" points="1505.5774,-973 1765.5774,-973 "/>
<text text-anchor="middle" x="1635.5774" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_other</text>
<polyline fill="none" stroke="#000000" points="1505.5774,-950 1765.5774,-950 "/>
<text text-anchor="middle" x="1635.5774" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">risk_factor</text>
<polyline fill="none" stroke="#000000" points="1765.5774,-927 1765.5774,-1134 "/>
<text text-anchor="middle" x="1776.0774" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1593.0774,-926.8901C1593.0774,-852.512 1593.0774,-754.3964 1593.0774,-689.814"/>
<polygon fill="#000000" stroke="#000000" points="1596.5775,-689.7456 1593.0774,-679.7456 1589.5775,-689.7457 1596.5775,-689.7456"/>
<text text-anchor="middle" x="1638.0774" y="-701.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- medical_history -->
<g id="node12" class="node">
<title>medical_history</title>
<path fill="none" stroke="#000000" d="M1817.0774,-996C1817.0774,-996 2171.0774,-996 2171.0774,-996 2177.0774,-996 2183.0774,-1002 2183.0774,-1008 2183.0774,-1008 2183.0774,-1053 2183.0774,-1053 2183.0774,-1059 2177.0774,-1065 2171.0774,-1065 2171.0774,-1065 1817.0774,-1065 1817.0774,-1065 1811.0774,-1065 1805.0774,-1059 1805.0774,-1053 1805.0774,-1053 1805.0774,-1008 1805.0774,-1008 1805.0774,-1002 1811.0774,-996 1817.0774,-996"/>
<text text-anchor="middle" x="1870.5774" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
<polyline fill="none" stroke="#000000" points="1936.0774,-996 1936.0774,-1065 "/>
<text text-anchor="middle" x="1946.5774" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1957.0774,-996 1957.0774,-1065 "/>
<text text-anchor="middle" x="2059.5774" y="-1049.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_category</text>
<polyline fill="none" stroke="#000000" points="1957.0774,-1042 2162.0774,-1042 "/>
<text text-anchor="middle" x="2059.5774" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_condition</text>
<polyline fill="none" stroke="#000000" points="1957.0774,-1019 2162.0774,-1019 "/>
<text text-anchor="middle" x="2059.5774" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_id</text>
<polyline fill="none" stroke="#000000" points="2162.0774,-996 2162.0774,-1065 "/>
<text text-anchor="middle" x="2172.5774" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1977.9997,-995.556C1948.8149,-935.2071 1882.0111,-810.3116 1795.0774,-731 1776.0868,-713.6745 1753.8405,-698.1594 1731.1851,-684.6423"/>
<polygon fill="#000000" stroke="#000000" points="1732.8879,-681.5836 1722.4881,-679.56 1729.356,-687.6274 1732.8879,-681.5836"/>
<text text-anchor="middle" x="1840.0774" y="-701.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- imaging_file -->
<g id="node13" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M4488.0774,-1519.5C4488.0774,-1519.5 4822.0774,-1519.5 4822.0774,-1519.5 4828.0774,-1519.5 4834.0774,-1525.5 4834.0774,-1531.5 4834.0774,-1531.5 4834.0774,-1829.5 4834.0774,-1829.5 4834.0774,-1835.5 4828.0774,-1841.5 4822.0774,-1841.5 4822.0774,-1841.5 4488.0774,-1841.5 4488.0774,-1841.5 4482.0774,-1841.5 4476.0774,-1835.5 4476.0774,-1829.5 4476.0774,-1829.5 4476.0774,-1531.5 4476.0774,-1531.5 4476.0774,-1525.5 4482.0774,-1519.5 4488.0774,-1519.5"/>
<text text-anchor="middle" x="4528.0774" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="4580.0774,-1519.5 4580.0774,-1841.5 "/>
<text text-anchor="middle" x="4590.5774" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4601.0774,-1519.5 4601.0774,-1841.5 "/>
<text text-anchor="middle" x="4707.0774" y="-1826.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="4601.0774,-1818.5 4813.0774,-1818.5 "/>
<text text-anchor="middle" x="4707.0774" y="-1803.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="4601.0774,-1795.5 4813.0774,-1795.5 "/>
<text text-anchor="middle" x="4707.0774" y="-1780.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="4601.0774,-1772.5 4813.0774,-1772.5 "/>
<text text-anchor="middle" x="4707.0774" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="4601.0774,-1749.5 4813.0774,-1749.5 "/>
<text text-anchor="middle" x="4707.0774" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="4601.0774,-1726.5 4813.0774,-1726.5 "/>
<text text-anchor="middle" x="4707.0774" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="4601.0774,-1703.5 4813.0774,-1703.5 "/>
<text text-anchor="middle" x="4707.0774" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="4601.0774,-1680.5 4813.0774,-1680.5 "/>
<text text-anchor="middle" x="4707.0774" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="4601.0774,-1657.5 4813.0774,-1657.5 "/>
<text text-anchor="middle" x="4707.0774" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="4601.0774,-1634.5 4813.0774,-1634.5 "/>
<text text-anchor="middle" x="4707.0774" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="4601.0774,-1611.5 4813.0774,-1611.5 "/>
<text text-anchor="middle" x="4707.0774" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="4601.0774,-1588.5 4813.0774,-1588.5 "/>
<text text-anchor="middle" x="4707.0774" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="4601.0774,-1565.5 4813.0774,-1565.5 "/>
<text text-anchor="middle" x="4707.0774" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="4601.0774,-1542.5 4813.0774,-1542.5 "/>
<text text-anchor="middle" x="4707.0774" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="4813.0774,-1519.5 4813.0774,-1841.5 "/>
<text text-anchor="middle" x="4823.5774" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M4580.8085,-1519.1902C4551.3305,-1469.2913 4513.2918,-1417.8211 4467.0774,-1381 4220.5635,-1184.5913 3856.4403,-1094.3546 3640.5388,-1055.9724"/>
<polygon fill="#000000" stroke="#000000" points="3640.826,-1052.4693 3630.3708,-1054.1837 3639.6132,-1059.3634 3640.826,-1052.4693"/>
<text text-anchor="middle" x="4486.5774" y="-1351.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge23" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1593.0774,-564.4781C1593.0774,-540.299 1593.0774,-512.2624 1593.0774,-488.2242"/>
<polygon fill="#000000" stroke="#000000" points="1596.5775,-488.1898 1593.0774,-478.1898 1589.5775,-488.1898 1596.5775,-488.1898"/>
<text text-anchor="middle" x="1643.5774" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge24" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1428.9975,-590.1555C1387.4897,-574.0026 1347.5173,-549.6649 1322.0774,-513 1281.7451,-454.8716 1275.0464,-377.9435 1280.243,-309.8713"/>
<polygon fill="#000000" stroke="#000000" points="1283.7313,-310.1566 1281.0935,-299.8954 1276.7566,-309.5619 1283.7313,-310.1566"/>
<text text-anchor="middle" x="1372.5774" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge4" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3432.8964,-949.9734C3405.1584,-882.1149 3356.3796,-787.328 3284.0774,-731 3142.9309,-621.038 2012.5458,-326.6103 1530.0756,-204.3685"/>
<polygon fill="#000000" stroke="#000000" points="1530.7589,-200.9311 1520.2057,-201.8689 1529.0404,-207.7169 1530.7589,-200.9311"/>
<text text-anchor="middle" x="2814.5774" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3437.9392,-949.9843C3412.7439,-878.6468 3364.8415,-778.6401 3284.0774,-731 3224.3344,-695.7596 2726.2721,-733.7211 2660.0774,-713 2648.4306,-709.3542 2648.6414,-701.9002 2637.0774,-698 2480.8485,-645.3094 2021.5956,-629.1308 1767.3682,-624.1764"/>
<polygon fill="#000000" stroke="#000000" points="1767.3551,-620.6756 1757.29,-623.9838 1767.2212,-627.6743 1767.3551,-620.6756"/>
<text text-anchor="middle" x="2696.5774" y="-701.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node17" class="node">
<title>pdx</title>
<path fill="none" stroke="#000000" d="M4864.5774,-1577C4864.5774,-1577 5193.5774,-1577 5193.5774,-1577 5199.5774,-1577 5205.5774,-1583 5205.5774,-1589 5205.5774,-1589 5205.5774,-1772 5205.5774,-1772 5205.5774,-1778 5199.5774,-1784 5193.5774,-1784 5193.5774,-1784 4864.5774,-1784 4864.5774,-1784 4858.5774,-1784 4852.5774,-1778 4852.5774,-1772 4852.5774,-1772 4852.5774,-1589 4852.5774,-1589 4852.5774,-1583 4858.5774,-1577 4864.5774,-1577"/>
<text text-anchor="middle" x="4874.0774" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
<polyline fill="none" stroke="#000000" points="4895.5774,-1577 4895.5774,-1784 "/>
<text text-anchor="middle" x="4906.0774" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4916.5774,-1577 4916.5774,-1784 "/>
<text text-anchor="middle" x="5050.5774" y="-1768.8" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_site</text>
<polyline fill="none" stroke="#000000" points="4916.5774,-1761 5184.5774,-1761 "/>
<text text-anchor="middle" x="5050.5774" y="-1745.8" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_type</text>
<polyline fill="none" stroke="#000000" points="4916.5774,-1738 5184.5774,-1738 "/>
<text text-anchor="middle" x="5050.5774" y="-1722.8" font-family="Times,serif" font-size="14.00" fill="#000000">model_id</text>
<polyline fill="none" stroke="#000000" points="4916.5774,-1715 5184.5774,-1715 "/>
<text text-anchor="middle" x="5050.5774" y="-1699.8" font-family="Times,serif" font-size="14.00" fill="#000000">mouse_strain</text>
<polyline fill="none" stroke="#000000" points="4916.5774,-1692 5184.5774,-1692 "/>
<text text-anchor="middle" x="5050.5774" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">strain_immune_system_humanized</text>
<polyline fill="none" stroke="#000000" points="4916.5774,-1669 5184.5774,-1669 "/>
<text text-anchor="middle" x="5050.5774" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_characterization_method</text>
<polyline fill="none" stroke="#000000" points="4916.5774,-1646 5184.5774,-1646 "/>
<text text-anchor="middle" x="5050.5774" y="-1630.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_not_mus_or_ebv_origin</text>
<polyline fill="none" stroke="#000000" points="4916.5774,-1623 5184.5774,-1623 "/>
<text text-anchor="middle" x="5050.5774" y="-1607.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_preparation</text>
<polyline fill="none" stroke="#000000" points="4916.5774,-1600 5184.5774,-1600 "/>
<text text-anchor="middle" x="5050.5774" y="-1584.8" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_humanization</text>
<polyline fill="none" stroke="#000000" points="5184.5774,-1577 5184.5774,-1784 "/>
<text text-anchor="middle" x="5195.0774" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M4988.8986,-1576.8126C4958.3732,-1511.3125 4910.1318,-1430.067 4843.0774,-1381 4651.1757,-1240.5763 3968.8639,-1113.5032 3640.3683,-1058.8397"/>
<polygon fill="#000000" stroke="#000000" points="3640.7115,-1055.3489 3630.2734,-1057.1642 3639.5653,-1062.2544 3640.7115,-1055.3489"/>
<text text-anchor="middle" x="4832.0774" y="-1351.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- diagnosis -->
<g id="node18" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M2435.0774,-835C2435.0774,-835 2809.0774,-835 2809.0774,-835 2815.0774,-835 2821.0774,-841 2821.0774,-847 2821.0774,-847 2821.0774,-1214 2821.0774,-1214 2821.0774,-1220 2815.0774,-1226 2809.0774,-1226 2809.0774,-1226 2435.0774,-1226 2435.0774,-1226 2429.0774,-1226 2423.0774,-1220 2423.0774,-1214 2423.0774,-1214 2423.0774,-847 2423.0774,-847 2423.0774,-841 2429.0774,-835 2435.0774,-835"/>
<text text-anchor="middle" x="2465.0774" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="2507.0774,-835 2507.0774,-1226 "/>
<text text-anchor="middle" x="2517.5774" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2528.0774,-835 2528.0774,-1226 "/>
<text text-anchor="middle" x="2664.0774" y="-1210.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2528.0774,-1203 2800.0774,-1203 "/>
<text text-anchor="middle" x="2664.0774" y="-1187.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="2528.0774,-1180 2800.0774,-1180 "/>
<text text-anchor="middle" x="2664.0774" y="-1164.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="2528.0774,-1157 2800.0774,-1157 "/>
<text text-anchor="middle" x="2664.0774" y="-1141.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2528.0774,-1134 2800.0774,-1134 "/>
<text text-anchor="middle" x="2664.0774" y="-1118.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="2528.0774,-1111 2800.0774,-1111 "/>
<text text-anchor="middle" x="2664.0774" y="-1095.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="2528.0774,-1088 2800.0774,-1088 "/>
<text text-anchor="middle" x="2664.0774" y="-1072.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="2528.0774,-1065 2800.0774,-1065 "/>
<text text-anchor="middle" x="2664.0774" y="-1049.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="2528.0774,-1042 2800.0774,-1042 "/>
<text text-anchor="middle" x="2664.0774" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="2528.0774,-1019 2800.0774,-1019 "/>
<text text-anchor="middle" x="2664.0774" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="2528.0774,-996 2800.0774,-996 "/>
<text text-anchor="middle" x="2664.0774" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2528.0774,-973 2800.0774,-973 "/>
<text text-anchor="middle" x="2664.0774" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="2528.0774,-950 2800.0774,-950 "/>
<text text-anchor="middle" x="2664.0774" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="2528.0774,-927 2800.0774,-927 "/>
<text text-anchor="middle" x="2664.0774" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="2528.0774,-904 2800.0774,-904 "/>
<text text-anchor="middle" x="2664.0774" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="2528.0774,-881 2800.0774,-881 "/>
<text text-anchor="middle" x="2664.0774" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="2528.0774,-858 2800.0774,-858 "/>
<text text-anchor="middle" x="2664.0774" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="2800.0774,-835 2800.0774,-1226 "/>
<text text-anchor="middle" x="2810.5774" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2516.0023,-834.8107C2486.2283,-795.1118 2450.4671,-757.4697 2409.0774,-731 2305.8626,-664.9917 1974.9225,-638.5087 1767.5618,-628.2153"/>
<polygon fill="#000000" stroke="#000000" points="1767.6338,-624.7148 1757.4749,-627.7225 1767.2921,-631.7064 1767.6338,-624.7148"/>
<text text-anchor="middle" x="2407.5774" y="-701.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- therapeutic_procedure -->
<g id="node19" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M2007.0774,-1623C2007.0774,-1623 2399.0774,-1623 2399.0774,-1623 2405.0774,-1623 2411.0774,-1629 2411.0774,-1635 2411.0774,-1635 2411.0774,-1726 2411.0774,-1726 2411.0774,-1732 2405.0774,-1738 2399.0774,-1738 2399.0774,-1738 2007.0774,-1738 2007.0774,-1738 2001.0774,-1738 1995.0774,-1732 1995.0774,-1726 1995.0774,-1726 1995.0774,-1635 1995.0774,-1635 1995.0774,-1629 2001.0774,-1623 2007.0774,-1623"/>
<text text-anchor="middle" x="2085.5774" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="2176.0774,-1623 2176.0774,-1738 "/>
<text text-anchor="middle" x="2186.5774" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2197.0774,-1623 2197.0774,-1738 "/>
<text text-anchor="middle" x="2293.5774" y="-1722.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment_start</text>
<polyline fill="none" stroke="#000000" points="2197.0774,-1715 2390.0774,-1715 "/>
<text text-anchor="middle" x="2293.5774" y="-1699.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="2197.0774,-1692 2390.0774,-1692 "/>
<text text-anchor="middle" x="2293.5774" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="2197.0774,-1669 2390.0774,-1669 "/>
<text text-anchor="middle" x="2293.5774" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="2197.0774,-1646 2390.0774,-1646 "/>
<text text-anchor="middle" x="2293.5774" y="-1630.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="2390.0774,-1623 2390.0774,-1738 "/>
<text text-anchor="middle" x="2400.5774" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2206.5816,-1622.8436C2217.892,-1427.4903 2249.4744,-798.9798 2192.0774,-731 2138.4468,-667.4811 1924.578,-640.8678 1767.6317,-629.7883"/>
<polygon fill="#000000" stroke="#000000" points="1767.5958,-626.2776 1757.3785,-629.0808 1767.1138,-633.261 1767.5958,-626.2776"/>
<text text-anchor="middle" x="2319.0774" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>therapeutic_procedure&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2226.5861,-1622.9136C2258.858,-1552.1774 2324.1382,-1434.9457 2421.0774,-1381 2594.3722,-1284.5631 2668.0961,-1359.6008 2866.0774,-1348 2912.4852,-1345.2807 3244.2054,-1353.9022 3284.0774,-1330 3360.7648,-1284.0278 3407.9483,-1191.0726 3434.1063,-1120.8451"/>
<polygon fill="#000000" stroke="#000000" points="3437.5243,-1121.6878 3437.6587,-1111.0938 3430.9471,-1119.2917 3437.5243,-1121.6878"/>
<text text-anchor="middle" x="2959.0774" y="-1351.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- sequencing_file -->
<g id="node20" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M2441.5774,-1393C2441.5774,-1393 2910.5774,-1393 2910.5774,-1393 2916.5774,-1393 2922.5774,-1399 2922.5774,-1405 2922.5774,-1405 2922.5774,-1956 2922.5774,-1956 2922.5774,-1962 2916.5774,-1968 2910.5774,-1968 2910.5774,-1968 2441.5774,-1968 2441.5774,-1968 2435.5774,-1968 2429.5774,-1962 2429.5774,-1956 2429.5774,-1956 2429.5774,-1405 2429.5774,-1405 2429.5774,-1399 2435.5774,-1393 2441.5774,-1393"/>
<text text-anchor="middle" x="2493.5774" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="2557.5774,-1393 2557.5774,-1968 "/>
<text text-anchor="middle" x="2568.0774" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2578.5774,-1393 2578.5774,-1968 "/>
<text text-anchor="middle" x="2740.0774" y="-1952.8" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="2578.5774,-1945 2901.5774,-1945 "/>
<text text-anchor="middle" x="2740.0774" y="-1929.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2578.5774,-1922 2901.5774,-1922 "/>
<text text-anchor="middle" x="2740.0774" y="-1906.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2578.5774,-1899 2901.5774,-1899 "/>
<text text-anchor="middle" x="2740.0774" y="-1883.8" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="2578.5774,-1876 2901.5774,-1876 "/>
<text text-anchor="middle" x="2740.0774" y="-1860.8" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="2578.5774,-1853 2901.5774,-1853 "/>
<text text-anchor="middle" x="2740.0774" y="-1837.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2578.5774,-1830 2901.5774,-1830 "/>
<text text-anchor="middle" x="2740.0774" y="-1814.8" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="2578.5774,-1807 2901.5774,-1807 "/>
<text text-anchor="middle" x="2740.0774" y="-1791.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2578.5774,-1784 2901.5774,-1784 "/>
<text text-anchor="middle" x="2740.0774" y="-1768.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2578.5774,-1761 2901.5774,-1761 "/>
<text text-anchor="middle" x="2740.0774" y="-1745.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2578.5774,-1738 2901.5774,-1738 "/>
<text text-anchor="middle" x="2740.0774" y="-1722.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2578.5774,-1715 2901.5774,-1715 "/>
<text text-anchor="middle" x="2740.0774" y="-1699.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2578.5774,-1692 2901.5774,-1692 "/>
<text text-anchor="middle" x="2740.0774" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2578.5774,-1669 2901.5774,-1669 "/>
<text text-anchor="middle" x="2740.0774" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="2578.5774,-1646 2901.5774,-1646 "/>
<text text-anchor="middle" x="2740.0774" y="-1630.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="2578.5774,-1623 2901.5774,-1623 "/>
<text text-anchor="middle" x="2740.0774" y="-1607.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="2578.5774,-1600 2901.5774,-1600 "/>
<text text-anchor="middle" x="2740.0774" y="-1584.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="2578.5774,-1577 2901.5774,-1577 "/>
<text text-anchor="middle" x="2740.0774" y="-1561.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="2578.5774,-1554 2901.5774,-1554 "/>
<text text-anchor="middle" x="2740.0774" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="2578.5774,-1531 2901.5774,-1531 "/>
<text text-anchor="middle" x="2740.0774" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2578.5774,-1508 2901.5774,-1508 "/>
<text text-anchor="middle" x="2740.0774" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="2578.5774,-1485 2901.5774,-1485 "/>
<text text-anchor="middle" x="2740.0774" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="2578.5774,-1462 2901.5774,-1462 "/>
<text text-anchor="middle" x="2740.0774" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="2578.5774,-1439 2901.5774,-1439 "/>
<text text-anchor="middle" x="2740.0774" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="2578.5774,-1416 2901.5774,-1416 "/>
<text text-anchor="middle" x="2740.0774" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="2901.5774,-1393 2901.5774,-1968 "/>
<text text-anchor="middle" x="2912.0774" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2912.1571,-1392.8697C2918.6963,-1388.6807 2925.3378,-1384.7144 2932.0774,-1381 2933.159,-1380.4039 3283.0515,-1330.6876 3284.0774,-1330 3357.6314,-1280.7026 3404.9886,-1189.6453 3432.031,-1120.825"/>
<polygon fill="#000000" stroke="#000000" points="3435.3837,-1121.8581 3435.7126,-1111.2684 3428.8516,-1119.3416 3435.3837,-1121.8581"/>
<text text-anchor="middle" x="3225.5774" y="-1351.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- exposure -->
<g id="node21" class="node">
<title>exposure</title>
<path fill="none" stroke="#000000" d="M2851.5774,-789C2851.5774,-789 3262.5774,-789 3262.5774,-789 3268.5774,-789 3274.5774,-795 3274.5774,-801 3274.5774,-801 3274.5774,-1260 3274.5774,-1260 3274.5774,-1266 3268.5774,-1272 3262.5774,-1272 3262.5774,-1272 2851.5774,-1272 2851.5774,-1272 2845.5774,-1272 2839.5774,-1266 2839.5774,-1260 2839.5774,-1260 2839.5774,-801 2839.5774,-801 2839.5774,-795 2845.5774,-789 2851.5774,-789"/>
<text text-anchor="middle" x="2880.5774" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
<polyline fill="none" stroke="#000000" points="2921.5774,-789 2921.5774,-1272 "/>
<text text-anchor="middle" x="2932.0774" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2942.5774,-789 2942.5774,-1272 "/>
<text text-anchor="middle" x="3098.0774" y="-1256.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_days_per_week</text>
<polyline fill="none" stroke="#000000" points="2942.5774,-1249 3253.5774,-1249 "/>
<text text-anchor="middle" x="3098.0774" y="-1233.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_drinks_per_day</text>
<polyline fill="none" stroke="#000000" points="2942.5774,-1226 3253.5774,-1226 "/>
<text text-anchor="middle" x="3098.0774" y="-1210.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_history</text>
<polyline fill="none" stroke="#000000" points="2942.5774,-1203 3253.5774,-1203 "/>
<text text-anchor="middle" x="3098.0774" y="-1187.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_intensity</text>
<polyline fill="none" stroke="#000000" points="2942.5774,-1180 3253.5774,-1180 "/>
<text text-anchor="middle" x="3098.0774" y="-1164.8" font-family="Times,serif" font-size="14.00" fill="#000000">asbestos_exposure</text>
<polyline fill="none" stroke="#000000" points="2942.5774,-1157 3253.5774,-1157 "/>
<text text-anchor="middle" x="3098.0774" y="-1141.8" font-family="Times,serif" font-size="14.00" fill="#000000">cigarettes_per_day</text>
<polyline fill="none" stroke="#000000" points="2942.5774,-1134 3253.5774,-1134 "/>
<text text-anchor="middle" x="3098.0774" y="-1118.8" font-family="Times,serif" font-size="14.00" fill="#000000">coal_dust_exposure</text>
<polyline fill="none" stroke="#000000" points="2942.5774,-1111 3253.5774,-1111 "/>
<text text-anchor="middle" x="3098.0774" y="-1095.8" font-family="Times,serif" font-size="14.00" fill="#000000">environmental_tobacco_smoke_exposure</text>
<polyline fill="none" stroke="#000000" points="2942.5774,-1088 3253.5774,-1088 "/>
<text text-anchor="middle" x="3098.0774" y="-1072.8" font-family="Times,serif" font-size="14.00" fill="#000000">exposure_id</text>
<polyline fill="none" stroke="#000000" points="2942.5774,-1065 3253.5774,-1065 "/>
<text text-anchor="middle" x="3098.0774" y="-1049.8" font-family="Times,serif" font-size="14.00" fill="#000000">pack_years_smoked</text>
<polyline fill="none" stroke="#000000" points="2942.5774,-1042 3253.5774,-1042 "/>
<text text-anchor="middle" x="3098.0774" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">radon_exposure</text>
<polyline fill="none" stroke="#000000" points="2942.5774,-1019 3253.5774,-1019 "/>
<text text-anchor="middle" x="3098.0774" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">respirable_crystalline_silica_exposure</text>
<polyline fill="none" stroke="#000000" points="2942.5774,-996 3253.5774,-996 "/>
<text text-anchor="middle" x="3098.0774" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">smoking_frequency</text>
<polyline fill="none" stroke="#000000" points="2942.5774,-973 3253.5774,-973 "/>
<text text-anchor="middle" x="3098.0774" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">start_days_from_index</text>
<polyline fill="none" stroke="#000000" points="2942.5774,-950 3253.5774,-950 "/>
<text text-anchor="middle" x="3098.0774" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">time_between_waking_and_first_smoke</text>
<polyline fill="none" stroke="#000000" points="2942.5774,-927 3253.5774,-927 "/>
<text text-anchor="middle" x="3098.0774" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_onset_year</text>
<polyline fill="none" stroke="#000000" points="2942.5774,-904 3253.5774,-904 "/>
<text text-anchor="middle" x="3098.0774" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_quit_year</text>
<polyline fill="none" stroke="#000000" points="2942.5774,-881 3253.5774,-881 "/>
<text text-anchor="middle" x="3098.0774" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_status</text>
<polyline fill="none" stroke="#000000" points="2942.5774,-858 3253.5774,-858 "/>
<text text-anchor="middle" x="3098.0774" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_smoke_exposure</text>
<polyline fill="none" stroke="#000000" points="2942.5774,-835 3253.5774,-835 "/>
<text text-anchor="middle" x="3098.0774" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_tobacco_used</text>
<polyline fill="none" stroke="#000000" points="2942.5774,-812 3253.5774,-812 "/>
<text text-anchor="middle" x="3098.0774" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">years_smoked</text>
<polyline fill="none" stroke="#000000" points="3253.5774,-789 3253.5774,-1272 "/>
<text text-anchor="middle" x="3264.0774" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2906.3672,-788.705C2883.4078,-766.0369 2857.9492,-745.9819 2830.0774,-731 2775.1581,-701.4793 2612.0428,-719.9203 2550.0774,-713 2508.0324,-708.3044 2498.0639,-703.1922 2456.0774,-698 2218.134,-668.575 1941.9058,-646.3273 1767.3282,-633.7275"/>
<polygon fill="#000000" stroke="#000000" points="1767.5024,-630.231 1757.2771,-633.0046 1767.0002,-637.213 1767.5024,-630.231"/>
<text text-anchor="middle" x="2593.5774" y="-701.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- publication -->
<g id="node22" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M2787.0774,-414C2787.0774,-414 2997.0774,-414 2997.0774,-414 3003.0774,-414 3009.0774,-420 3009.0774,-426 3009.0774,-426 3009.0774,-438 3009.0774,-438 3009.0774,-444 3003.0774,-450 2997.0774,-450 2997.0774,-450 2787.0774,-450 2787.0774,-450 2781.0774,-450 2775.0774,-444 2775.0774,-438 2775.0774,-438 2775.0774,-426 2775.0774,-426 2775.0774,-420 2781.0774,-414 2787.0774,-414"/>
<text text-anchor="middle" x="2823.5774" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="2872.0774,-414 2872.0774,-450 "/>
<text text-anchor="middle" x="2882.5774" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2893.0774,-414 2893.0774,-450 "/>
<text text-anchor="middle" x="2940.5774" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="2988.0774,-414 2988.0774,-450 "/>
<text text-anchor="middle" x="2998.5774" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge22" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2877.4217,-413.6195C2855.3177,-387.3753 2810.7211,-339.9207 2761.0774,-318 2545.7979,-222.9411 1879.0985,-177.3332 1530.4907,-159.4954"/>
<polygon fill="#000000" stroke="#000000" points="1530.4352,-155.9882 1520.2704,-158.9758 1530.0797,-162.9791 1530.4352,-155.9882"/>
<text text-anchor="middle" x="2836.0774" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- study_personnel -->
<g id="node23" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M3039.5774,-374.5C3039.5774,-374.5 3346.5774,-374.5 3346.5774,-374.5 3352.5774,-374.5 3358.5774,-380.5 3358.5774,-386.5 3358.5774,-386.5 3358.5774,-477.5 3358.5774,-477.5 3358.5774,-483.5 3352.5774,-489.5 3346.5774,-489.5 3346.5774,-489.5 3039.5774,-489.5 3039.5774,-489.5 3033.5774,-489.5 3027.5774,-483.5 3027.5774,-477.5 3027.5774,-477.5 3027.5774,-386.5 3027.5774,-386.5 3027.5774,-380.5 3033.5774,-374.5 3039.5774,-374.5"/>
<text text-anchor="middle" x="3094.5774" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="3161.5774,-374.5 3161.5774,-489.5 "/>
<text text-anchor="middle" x="3172.0774" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3182.5774,-374.5 3182.5774,-489.5 "/>
<text text-anchor="middle" x="3260.0774" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="3182.5774,-466.5 3337.5774,-466.5 "/>
<text text-anchor="middle" x="3260.0774" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="3182.5774,-443.5 3337.5774,-443.5 "/>
<text text-anchor="middle" x="3260.0774" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="3182.5774,-420.5 3337.5774,-420.5 "/>
<text text-anchor="middle" x="3260.0774" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="3182.5774,-397.5 3337.5774,-397.5 "/>
<text text-anchor="middle" x="3260.0774" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="3337.5774,-374.5 3337.5774,-489.5 "/>
<text text-anchor="middle" x="3348.0774" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge16" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3076.142,-374.3801C3056.976,-365.953 3037.1462,-357.8282 3018.0774,-351 2963.1724,-331.3395 2948.4525,-328.449 2891.0774,-318 2409.507,-230.298 1836.3082,-183.4103 1530.6213,-162.9279"/>
<polygon fill="#000000" stroke="#000000" points="1530.5201,-159.4135 1520.3093,-162.2402 1530.0542,-166.398 1530.5201,-159.4135"/>
<text text-anchor="middle" x="3030.5774" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
</g>
</svg>
</div>
