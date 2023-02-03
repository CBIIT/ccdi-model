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
<svg width="3111pt" height="1735pt"
 viewBox="0.00 0.00 3111.03 1735.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1731)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1731 3107.0286,-1731 3107.0286,4 -4,4"/>
<!-- participant -->
<g id="node1" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M881.5286,-495.5C881.5286,-495.5 1185.5286,-495.5 1185.5286,-495.5 1191.5286,-495.5 1197.5286,-501.5 1197.5286,-507.5 1197.5286,-507.5 1197.5286,-598.5 1197.5286,-598.5 1197.5286,-604.5 1191.5286,-610.5 1185.5286,-610.5 1185.5286,-610.5 881.5286,-610.5 881.5286,-610.5 875.5286,-610.5 869.5286,-604.5 869.5286,-598.5 869.5286,-598.5 869.5286,-507.5 869.5286,-507.5 869.5286,-501.5 875.5286,-495.5 881.5286,-495.5"/>
<text text-anchor="middle" x="917.5286" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="965.5286,-495.5 965.5286,-610.5 "/>
<text text-anchor="middle" x="976.0286" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="986.5286,-495.5 986.5286,-610.5 "/>
<text text-anchor="middle" x="1081.5286" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="986.5286,-587.5 1176.5286,-587.5 "/>
<text text-anchor="middle" x="1081.5286" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="986.5286,-564.5 1176.5286,-564.5 "/>
<text text-anchor="middle" x="1081.5286" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="986.5286,-541.5 1176.5286,-541.5 "/>
<text text-anchor="middle" x="1081.5286" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="986.5286,-518.5 1176.5286,-518.5 "/>
<text text-anchor="middle" x="1081.5286" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1176.5286,-495.5 1176.5286,-610.5 "/>
<text text-anchor="middle" x="1187.0286" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm -->
<g id="node4" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M1052.0286,-317C1052.0286,-317 1349.0286,-317 1349.0286,-317 1355.0286,-317 1361.0286,-323 1361.0286,-329 1361.0286,-329 1361.0286,-374 1361.0286,-374 1361.0286,-380 1355.0286,-386 1349.0286,-386 1349.0286,-386 1052.0286,-386 1052.0286,-386 1046.0286,-386 1040.0286,-380 1040.0286,-374 1040.0286,-374 1040.0286,-329 1040.0286,-329 1040.0286,-323 1046.0286,-317 1052.0286,-317"/>
<text text-anchor="middle" x="1086.0286" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="1132.0286,-317 1132.0286,-386 "/>
<text text-anchor="middle" x="1142.5286" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1153.0286,-317 1153.0286,-386 "/>
<text text-anchor="middle" x="1246.5286" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="1153.0286,-363 1340.0286,-363 "/>
<text text-anchor="middle" x="1246.5286" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="1153.0286,-340 1340.0286,-340 "/>
<text text-anchor="middle" x="1246.5286" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="1340.0286,-317 1340.0286,-386 "/>
<text text-anchor="middle" x="1350.5286" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge1" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1081.3841,-495.2582C1108.0785,-463.0491 1140.7563,-423.6205 1165.133,-394.2079"/>
<polygon fill="#000000" stroke="#000000" points="1168.0901,-396.1248 1171.7765,-386.1919 1162.7005,-391.6579 1168.0901,-396.1248"/>
<text text-anchor="middle" x="1157.0286" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study -->
<g id="node17" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M1005.5286,-.5C1005.5286,-.5 1395.5286,-.5 1395.5286,-.5 1401.5286,-.5 1407.5286,-6.5 1407.5286,-12.5 1407.5286,-12.5 1407.5286,-195.5 1407.5286,-195.5 1407.5286,-201.5 1401.5286,-207.5 1395.5286,-207.5 1395.5286,-207.5 1005.5286,-207.5 1005.5286,-207.5 999.5286,-207.5 993.5286,-201.5 993.5286,-195.5 993.5286,-195.5 993.5286,-12.5 993.5286,-12.5 993.5286,-6.5 999.5286,-.5 1005.5286,-.5"/>
<text text-anchor="middle" x="1021.5286" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="1049.5286,-.5 1049.5286,-207.5 "/>
<text text-anchor="middle" x="1060.0286" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1070.5286,-.5 1070.5286,-207.5 "/>
<text text-anchor="middle" x="1228.5286" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="1070.5286,-184.5 1386.5286,-184.5 "/>
<text text-anchor="middle" x="1228.5286" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="1070.5286,-161.5 1386.5286,-161.5 "/>
<text text-anchor="middle" x="1228.5286" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="1070.5286,-138.5 1386.5286,-138.5 "/>
<text text-anchor="middle" x="1228.5286" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="1070.5286,-115.5 1386.5286,-115.5 "/>
<text text-anchor="middle" x="1228.5286" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="1070.5286,-92.5 1386.5286,-92.5 "/>
<text text-anchor="middle" x="1228.5286" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="1070.5286,-69.5 1386.5286,-69.5 "/>
<text text-anchor="middle" x="1228.5286" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="1070.5286,-46.5 1386.5286,-46.5 "/>
<text text-anchor="middle" x="1228.5286" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="1070.5286,-23.5 1386.5286,-23.5 "/>
<text text-anchor="middle" x="1228.5286" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="1386.5286,-.5 1386.5286,-207.5 "/>
<text text-anchor="middle" x="1397.0286" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge2" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M869.4522,-541.1563C732.8076,-527.4746 553.5489,-499.3274 508.5286,-444 456.6336,-380.2239 457.1339,-323.18 508.5286,-259 567.3934,-185.4916 803.0262,-144.4864 983.1365,-123.388"/>
<polygon fill="#000000" stroke="#000000" points="983.7594,-126.8394 993.2906,-122.2127 982.9544,-119.8858 983.7594,-126.8394"/>
<text text-anchor="middle" x="559.0286" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sequencing_file -->
<g id="node2" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M2622.0286,-1151.5C2622.0286,-1151.5 3091.0286,-1151.5 3091.0286,-1151.5 3097.0286,-1151.5 3103.0286,-1157.5 3103.0286,-1163.5 3103.0286,-1163.5 3103.0286,-1714.5 3103.0286,-1714.5 3103.0286,-1720.5 3097.0286,-1726.5 3091.0286,-1726.5 3091.0286,-1726.5 2622.0286,-1726.5 2622.0286,-1726.5 2616.0286,-1726.5 2610.0286,-1720.5 2610.0286,-1714.5 2610.0286,-1714.5 2610.0286,-1163.5 2610.0286,-1163.5 2610.0286,-1157.5 2616.0286,-1151.5 2622.0286,-1151.5"/>
<text text-anchor="middle" x="2674.0286" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="2738.0286,-1151.5 2738.0286,-1726.5 "/>
<text text-anchor="middle" x="2748.5286" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2759.0286,-1151.5 2759.0286,-1726.5 "/>
<text text-anchor="middle" x="2920.5286" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="2759.0286,-1703.5 3082.0286,-1703.5 "/>
<text text-anchor="middle" x="2920.5286" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2759.0286,-1680.5 3082.0286,-1680.5 "/>
<text text-anchor="middle" x="2920.5286" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2759.0286,-1657.5 3082.0286,-1657.5 "/>
<text text-anchor="middle" x="2920.5286" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="2759.0286,-1634.5 3082.0286,-1634.5 "/>
<text text-anchor="middle" x="2920.5286" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="2759.0286,-1611.5 3082.0286,-1611.5 "/>
<text text-anchor="middle" x="2920.5286" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2759.0286,-1588.5 3082.0286,-1588.5 "/>
<text text-anchor="middle" x="2920.5286" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="2759.0286,-1565.5 3082.0286,-1565.5 "/>
<text text-anchor="middle" x="2920.5286" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2759.0286,-1542.5 3082.0286,-1542.5 "/>
<text text-anchor="middle" x="2920.5286" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2759.0286,-1519.5 3082.0286,-1519.5 "/>
<text text-anchor="middle" x="2920.5286" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2759.0286,-1496.5 3082.0286,-1496.5 "/>
<text text-anchor="middle" x="2920.5286" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2759.0286,-1473.5 3082.0286,-1473.5 "/>
<text text-anchor="middle" x="2920.5286" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2759.0286,-1450.5 3082.0286,-1450.5 "/>
<text text-anchor="middle" x="2920.5286" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2759.0286,-1427.5 3082.0286,-1427.5 "/>
<text text-anchor="middle" x="2920.5286" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="2759.0286,-1404.5 3082.0286,-1404.5 "/>
<text text-anchor="middle" x="2920.5286" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="2759.0286,-1381.5 3082.0286,-1381.5 "/>
<text text-anchor="middle" x="2920.5286" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="2759.0286,-1358.5 3082.0286,-1358.5 "/>
<text text-anchor="middle" x="2920.5286" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="2759.0286,-1335.5 3082.0286,-1335.5 "/>
<text text-anchor="middle" x="2920.5286" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="2759.0286,-1312.5 3082.0286,-1312.5 "/>
<text text-anchor="middle" x="2920.5286" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="2759.0286,-1289.5 3082.0286,-1289.5 "/>
<text text-anchor="middle" x="2920.5286" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2759.0286,-1266.5 3082.0286,-1266.5 "/>
<text text-anchor="middle" x="2920.5286" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="2759.0286,-1243.5 3082.0286,-1243.5 "/>
<text text-anchor="middle" x="2920.5286" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="2759.0286,-1220.5 3082.0286,-1220.5 "/>
<text text-anchor="middle" x="2920.5286" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="2759.0286,-1197.5 3082.0286,-1197.5 "/>
<text text-anchor="middle" x="2920.5286" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="2759.0286,-1174.5 3082.0286,-1174.5 "/>
<text text-anchor="middle" x="2920.5286" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="3082.0286,-1151.5 3082.0286,-1726.5 "/>
<text text-anchor="middle" x="3092.5286" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node14" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1420.5286,-800.5C1420.5286,-800.5 1734.5286,-800.5 1734.5286,-800.5 1740.5286,-800.5 1746.5286,-806.5 1746.5286,-812.5 1746.5286,-812.5 1746.5286,-949.5 1746.5286,-949.5 1746.5286,-955.5 1740.5286,-961.5 1734.5286,-961.5 1734.5286,-961.5 1420.5286,-961.5 1420.5286,-961.5 1414.5286,-961.5 1408.5286,-955.5 1408.5286,-949.5 1408.5286,-949.5 1408.5286,-812.5 1408.5286,-812.5 1408.5286,-806.5 1414.5286,-800.5 1420.5286,-800.5"/>
<text text-anchor="middle" x="1442.5286" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1476.5286,-800.5 1476.5286,-961.5 "/>
<text text-anchor="middle" x="1487.0286" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1497.5286,-800.5 1497.5286,-961.5 "/>
<text text-anchor="middle" x="1611.5286" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="1497.5286,-938.5 1725.5286,-938.5 "/>
<text text-anchor="middle" x="1611.5286" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1497.5286,-915.5 1725.5286,-915.5 "/>
<text text-anchor="middle" x="1611.5286" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1497.5286,-892.5 1725.5286,-892.5 "/>
<text text-anchor="middle" x="1611.5286" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1497.5286,-869.5 1725.5286,-869.5 "/>
<text text-anchor="middle" x="1611.5286" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1497.5286,-846.5 1725.5286,-846.5 "/>
<text text-anchor="middle" x="1611.5286" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1497.5286,-823.5 1725.5286,-823.5 "/>
<text text-anchor="middle" x="1611.5286" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="1725.5286,-800.5 1725.5286,-961.5 "/>
<text text-anchor="middle" x="1736.0286" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2609.8822,-1156.9272C2606.7814,-1154.9034 2603.6633,-1152.9266 2600.5286,-1151 2334.7995,-987.6778 1971.5009,-922.2278 1756.9802,-896.669"/>
<polygon fill="#000000" stroke="#000000" points="1757.2186,-893.1731 1746.8784,-895.4819 1756.4015,-900.1252 1757.2186,-893.1731"/>
<text text-anchor="middle" x="2617.0286" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- methylation_array_file -->
<g id="node3" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M990.0286,-1324C990.0286,-1324 1357.0286,-1324 1357.0286,-1324 1363.0286,-1324 1369.0286,-1330 1369.0286,-1336 1369.0286,-1336 1369.0286,-1542 1369.0286,-1542 1369.0286,-1548 1363.0286,-1554 1357.0286,-1554 1357.0286,-1554 990.0286,-1554 990.0286,-1554 984.0286,-1554 978.0286,-1548 978.0286,-1542 978.0286,-1542 978.0286,-1336 978.0286,-1336 978.0286,-1330 984.0286,-1324 990.0286,-1324"/>
<text text-anchor="middle" x="1067.0286" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="1156.0286,-1324 1156.0286,-1554 "/>
<text text-anchor="middle" x="1166.5286" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1177.0286,-1324 1177.0286,-1554 "/>
<text text-anchor="middle" x="1262.5286" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1177.0286,-1531 1348.0286,-1531 "/>
<text text-anchor="middle" x="1262.5286" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1177.0286,-1508 1348.0286,-1508 "/>
<text text-anchor="middle" x="1262.5286" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1177.0286,-1485 1348.0286,-1485 "/>
<text text-anchor="middle" x="1262.5286" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1177.0286,-1462 1348.0286,-1462 "/>
<text text-anchor="middle" x="1262.5286" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1177.0286,-1439 1348.0286,-1439 "/>
<text text-anchor="middle" x="1262.5286" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1177.0286,-1416 1348.0286,-1416 "/>
<text text-anchor="middle" x="1262.5286" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1177.0286,-1393 1348.0286,-1393 "/>
<text text-anchor="middle" x="1262.5286" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1177.0286,-1370 1348.0286,-1370 "/>
<text text-anchor="middle" x="1262.5286" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="1177.0286,-1347 1348.0286,-1347 "/>
<text text-anchor="middle" x="1262.5286" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="1348.0286,-1324 1348.0286,-1554 "/>
<text text-anchor="middle" x="1358.5286" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1254.8938,-1323.7705C1292.3443,-1270.9711 1337.4855,-1207.6624 1378.5286,-1151 1422.4644,-1090.3442 1472.4843,-1022.483 1511.3844,-969.9677"/>
<polygon fill="#000000" stroke="#000000" points="1514.388,-971.7929 1517.5295,-961.6745 1508.7638,-967.6254 1514.388,-971.7929"/>
<text text-anchor="middle" x="1491.0286" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge18" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1200.5286,-316.8256C1200.5286,-290.8629 1200.5286,-253.7725 1200.5286,-217.8091"/>
<polygon fill="#000000" stroke="#000000" points="1204.0287,-217.7056 1200.5286,-207.7056 1197.0287,-217.7056 1204.0287,-217.7056"/>
<text text-anchor="middle" x="1249.0286" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- sample_diagnosis -->
<g id="node5" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M1399.0286,-1220.5C1399.0286,-1220.5 1832.0286,-1220.5 1832.0286,-1220.5 1838.0286,-1220.5 1844.0286,-1226.5 1844.0286,-1232.5 1844.0286,-1232.5 1844.0286,-1645.5 1844.0286,-1645.5 1844.0286,-1651.5 1838.0286,-1657.5 1832.0286,-1657.5 1832.0286,-1657.5 1399.0286,-1657.5 1399.0286,-1657.5 1393.0286,-1657.5 1387.0286,-1651.5 1387.0286,-1645.5 1387.0286,-1645.5 1387.0286,-1232.5 1387.0286,-1232.5 1387.0286,-1226.5 1393.0286,-1220.5 1399.0286,-1220.5"/>
<text text-anchor="middle" x="1458.5286" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1530.0286,-1220.5 1530.0286,-1657.5 "/>
<text text-anchor="middle" x="1540.5286" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1551.0286,-1220.5 1551.0286,-1657.5 "/>
<text text-anchor="middle" x="1687.0286" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1551.0286,-1634.5 1823.0286,-1634.5 "/>
<text text-anchor="middle" x="1687.0286" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1551.0286,-1611.5 1823.0286,-1611.5 "/>
<text text-anchor="middle" x="1687.0286" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1551.0286,-1588.5 1823.0286,-1588.5 "/>
<text text-anchor="middle" x="1687.0286" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1551.0286,-1565.5 1823.0286,-1565.5 "/>
<text text-anchor="middle" x="1687.0286" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="1551.0286,-1542.5 1823.0286,-1542.5 "/>
<text text-anchor="middle" x="1687.0286" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="1551.0286,-1519.5 1823.0286,-1519.5 "/>
<text text-anchor="middle" x="1687.0286" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="1551.0286,-1496.5 1823.0286,-1496.5 "/>
<text text-anchor="middle" x="1687.0286" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1551.0286,-1473.5 1823.0286,-1473.5 "/>
<text text-anchor="middle" x="1687.0286" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="1551.0286,-1450.5 1823.0286,-1450.5 "/>
<text text-anchor="middle" x="1687.0286" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="1551.0286,-1427.5 1823.0286,-1427.5 "/>
<text text-anchor="middle" x="1687.0286" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1551.0286,-1404.5 1823.0286,-1404.5 "/>
<text text-anchor="middle" x="1687.0286" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="1551.0286,-1381.5 1823.0286,-1381.5 "/>
<text text-anchor="middle" x="1687.0286" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="1551.0286,-1358.5 1823.0286,-1358.5 "/>
<text text-anchor="middle" x="1687.0286" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1551.0286,-1335.5 1823.0286,-1335.5 "/>
<text text-anchor="middle" x="1687.0286" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="1551.0286,-1312.5 1823.0286,-1312.5 "/>
<text text-anchor="middle" x="1687.0286" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="1551.0286,-1289.5 1823.0286,-1289.5 "/>
<text text-anchor="middle" x="1687.0286" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1551.0286,-1266.5 1823.0286,-1266.5 "/>
<text text-anchor="middle" x="1687.0286" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1551.0286,-1243.5 1823.0286,-1243.5 "/>
<text text-anchor="middle" x="1687.0286" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1823.0286,-1220.5 1823.0286,-1657.5 "/>
<text text-anchor="middle" x="1833.5286" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1600.6463,-1220.4653C1594.7493,-1133.8721 1588.2964,-1039.1156 1583.7104,-971.7739"/>
<polygon fill="#000000" stroke="#000000" points="1587.1906,-971.3637 1583.0192,-961.6246 1580.2068,-971.8393 1587.1906,-971.3637"/>
<text text-anchor="middle" x="1667.5286" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
<!-- pdx -->
<g id="node6" class="node">
<title>pdx</title>
<path fill="none" stroke="#000000" d="M1874.0286,-1335.5C1874.0286,-1335.5 2203.0286,-1335.5 2203.0286,-1335.5 2209.0286,-1335.5 2215.0286,-1341.5 2215.0286,-1347.5 2215.0286,-1347.5 2215.0286,-1530.5 2215.0286,-1530.5 2215.0286,-1536.5 2209.0286,-1542.5 2203.0286,-1542.5 2203.0286,-1542.5 1874.0286,-1542.5 1874.0286,-1542.5 1868.0286,-1542.5 1862.0286,-1536.5 1862.0286,-1530.5 1862.0286,-1530.5 1862.0286,-1347.5 1862.0286,-1347.5 1862.0286,-1341.5 1868.0286,-1335.5 1874.0286,-1335.5"/>
<text text-anchor="middle" x="1883.5286" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
<polyline fill="none" stroke="#000000" points="1905.0286,-1335.5 1905.0286,-1542.5 "/>
<text text-anchor="middle" x="1915.5286" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1926.0286,-1335.5 1926.0286,-1542.5 "/>
<text text-anchor="middle" x="2060.0286" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">injection_type_and_site</text>
<polyline fill="none" stroke="#000000" points="1926.0286,-1519.5 2194.0286,-1519.5 "/>
<text text-anchor="middle" x="2060.0286" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_id</text>
<polyline fill="none" stroke="#000000" points="1926.0286,-1496.5 2194.0286,-1496.5 "/>
<text text-anchor="middle" x="2060.0286" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_type</text>
<polyline fill="none" stroke="#000000" points="1926.0286,-1473.5 2194.0286,-1473.5 "/>
<text text-anchor="middle" x="2060.0286" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">mouse_strain</text>
<polyline fill="none" stroke="#000000" points="1926.0286,-1450.5 2194.0286,-1450.5 "/>
<text text-anchor="middle" x="2060.0286" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">strain_immune_system_humanized</text>
<polyline fill="none" stroke="#000000" points="1926.0286,-1427.5 2194.0286,-1427.5 "/>
<text text-anchor="middle" x="2060.0286" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_characterization_method</text>
<polyline fill="none" stroke="#000000" points="1926.0286,-1404.5 2194.0286,-1404.5 "/>
<text text-anchor="middle" x="2060.0286" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_not_mus_or_ebv_origin</text>
<polyline fill="none" stroke="#000000" points="1926.0286,-1381.5 2194.0286,-1381.5 "/>
<text text-anchor="middle" x="2060.0286" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_preparation</text>
<polyline fill="none" stroke="#000000" points="1926.0286,-1358.5 2194.0286,-1358.5 "/>
<text text-anchor="middle" x="2060.0286" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_humanization</text>
<polyline fill="none" stroke="#000000" points="2194.0286,-1335.5 2194.0286,-1542.5 "/>
<text text-anchor="middle" x="2204.5286" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1979.6375,-1335.1781C1945.6575,-1278.6027 1900.4504,-1208.5884 1853.5286,-1151 1800.2503,-1085.6099 1732.6657,-1019.2697 1677.711,-968.7119"/>
<polygon fill="#000000" stroke="#000000" points="1679.7802,-965.8608 1670.0432,-961.6844 1675.0506,-971.0213 1679.7802,-965.8608"/>
<text text-anchor="middle" x="1856.5286" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- therapeutic_procedure -->
<g id="node7" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M447.0286,-823.5C447.0286,-823.5 804.0286,-823.5 804.0286,-823.5 810.0286,-823.5 816.0286,-829.5 816.0286,-835.5 816.0286,-835.5 816.0286,-926.5 816.0286,-926.5 816.0286,-932.5 810.0286,-938.5 804.0286,-938.5 804.0286,-938.5 447.0286,-938.5 447.0286,-938.5 441.0286,-938.5 435.0286,-932.5 435.0286,-926.5 435.0286,-926.5 435.0286,-835.5 435.0286,-835.5 435.0286,-829.5 441.0286,-823.5 447.0286,-823.5"/>
<text text-anchor="middle" x="525.5286" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="616.0286,-823.5 616.0286,-938.5 "/>
<text text-anchor="middle" x="626.5286" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="637.0286,-823.5 637.0286,-938.5 "/>
<text text-anchor="middle" x="716.0286" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="637.0286,-915.5 795.0286,-915.5 "/>
<text text-anchor="middle" x="716.0286" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="637.0286,-892.5 795.0286,-892.5 "/>
<text text-anchor="middle" x="716.0286" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="637.0286,-869.5 795.0286,-869.5 "/>
<text text-anchor="middle" x="716.0286" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="637.0286,-846.5 795.0286,-846.5 "/>
<text text-anchor="middle" x="716.0286" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="795.0286,-823.5 795.0286,-938.5 "/>
<text text-anchor="middle" x="805.5286" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M663.0713,-823.3962C702.2508,-767.1879 768.3827,-682.5407 843.5286,-629 850.0388,-624.3616 856.8723,-619.9514 863.9221,-615.7652"/>
<polygon fill="#000000" stroke="#000000" points="866.026,-618.5934 872.9593,-610.5821 862.5434,-612.5211 866.026,-618.5934"/>
<text text-anchor="middle" x="936.5286" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- clinical_measure_file -->
<g id="node8" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M52.5286,-754.5C52.5286,-754.5 404.5286,-754.5 404.5286,-754.5 410.5286,-754.5 416.5286,-760.5 416.5286,-766.5 416.5286,-766.5 416.5286,-995.5 416.5286,-995.5 416.5286,-1001.5 410.5286,-1007.5 404.5286,-1007.5 404.5286,-1007.5 52.5286,-1007.5 52.5286,-1007.5 46.5286,-1007.5 40.5286,-1001.5 40.5286,-995.5 40.5286,-995.5 40.5286,-766.5 40.5286,-766.5 40.5286,-760.5 46.5286,-754.5 52.5286,-754.5"/>
<text text-anchor="middle" x="124.0286" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="207.5286,-754.5 207.5286,-1007.5 "/>
<text text-anchor="middle" x="218.0286" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="228.5286,-754.5 228.5286,-1007.5 "/>
<text text-anchor="middle" x="312.0286" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="228.5286,-984.5 395.5286,-984.5 "/>
<text text-anchor="middle" x="312.0286" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="228.5286,-961.5 395.5286,-961.5 "/>
<text text-anchor="middle" x="312.0286" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="228.5286,-938.5 395.5286,-938.5 "/>
<text text-anchor="middle" x="312.0286" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="228.5286,-915.5 395.5286,-915.5 "/>
<text text-anchor="middle" x="312.0286" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="228.5286,-892.5 395.5286,-892.5 "/>
<text text-anchor="middle" x="312.0286" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="228.5286,-869.5 395.5286,-869.5 "/>
<text text-anchor="middle" x="312.0286" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="228.5286,-846.5 395.5286,-846.5 "/>
<text text-anchor="middle" x="312.0286" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="228.5286,-823.5 395.5286,-823.5 "/>
<text text-anchor="middle" x="312.0286" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="228.5286,-800.5 395.5286,-800.5 "/>
<text text-anchor="middle" x="312.0286" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="228.5286,-777.5 395.5286,-777.5 "/>
<text text-anchor="middle" x="312.0286" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="395.5286,-754.5 395.5286,-1007.5 "/>
<text text-anchor="middle" x="406.0286" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M319.1513,-754.3355C349.4253,-719.8714 385.7105,-685.5909 425.5286,-662 497.3006,-619.4775 706.4047,-588.3809 859.4039,-570.5281"/>
<polygon fill="#000000" stroke="#000000" points="859.8673,-573.9979 869.3985,-569.3713 859.0624,-567.0443 859.8673,-573.9979"/>
<text text-anchor="middle" x="637.0286" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge6" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M246.2251,-754.455C271.8533,-615.9298 331.9273,-395.4159 466.5286,-259 537.6925,-186.8768 793.4877,-145.1673 983.1971,-123.5438"/>
<polygon fill="#000000" stroke="#000000" points="983.7708,-127.0014 993.3154,-122.4024 982.9861,-120.0455 983.7708,-127.0014"/>
<text text-anchor="middle" x="418.5286" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- study_funding -->
<g id="node9" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M631.0286,-317C631.0286,-317 1010.0286,-317 1010.0286,-317 1016.0286,-317 1022.0286,-323 1022.0286,-329 1022.0286,-329 1022.0286,-374 1022.0286,-374 1022.0286,-380 1016.0286,-386 1010.0286,-386 1010.0286,-386 631.0286,-386 631.0286,-386 625.0286,-386 619.0286,-380 619.0286,-374 619.0286,-374 619.0286,-329 619.0286,-329 619.0286,-323 625.0286,-317 631.0286,-317"/>
<text text-anchor="middle" x="678.5286" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="738.0286,-317 738.0286,-386 "/>
<text text-anchor="middle" x="748.5286" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="759.0286,-317 759.0286,-386 "/>
<text text-anchor="middle" x="880.0286" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="759.0286,-363 1001.0286,-363 "/>
<text text-anchor="middle" x="880.0286" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="759.0286,-340 1001.0286,-340 "/>
<text text-anchor="middle" x="880.0286" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="1001.0286,-317 1001.0286,-386 "/>
<text text-anchor="middle" x="1011.5286" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge20" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M873.7661,-316.8256C915.3315,-289.7534 975.4734,-250.582 1032.8596,-213.2055"/>
<polygon fill="#000000" stroke="#000000" points="1034.8347,-216.0961 1041.3039,-207.7056 1031.0143,-210.2305 1034.8347,-216.0961"/>
<text text-anchor="middle" x="1072.5286" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- synonym -->
<g id="node10" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M647.0286,-1416C647.0286,-1416 948.0286,-1416 948.0286,-1416 954.0286,-1416 960.0286,-1422 960.0286,-1428 960.0286,-1428 960.0286,-1450 960.0286,-1450 960.0286,-1456 954.0286,-1462 948.0286,-1462 948.0286,-1462 647.0286,-1462 647.0286,-1462 641.0286,-1462 635.0286,-1456 635.0286,-1450 635.0286,-1450 635.0286,-1428 635.0286,-1428 635.0286,-1422 641.0286,-1416 647.0286,-1416"/>
<text text-anchor="middle" x="675.0286" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="715.0286,-1416 715.0286,-1462 "/>
<text text-anchor="middle" x="725.5286" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="736.0286,-1416 736.0286,-1462 "/>
<text text-anchor="middle" x="837.5286" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="736.0286,-1439 939.0286,-1439 "/>
<text text-anchor="middle" x="837.5286" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="939.0286,-1416 939.0286,-1462 "/>
<text text-anchor="middle" x="949.5286" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M804.1229,-1415.7733C821.2205,-1360.0924 872.5515,-1218.6183 969.5286,-1151 1070.4202,-1080.6523 1162.9793,-1194.6462 1241.5286,-1100 1303.6892,-1025.1011 1291.909,-745.2802 1241.5286,-662 1230.7838,-644.2384 1216.0846,-629.2302 1199.4291,-616.5828"/>
<polygon fill="#000000" stroke="#000000" points="1201.2584,-613.5864 1191.1044,-610.562 1197.1562,-619.2584 1201.2584,-613.5864"/>
<text text-anchor="middle" x="1326.0286" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M803.362,-1415.8053C819.0396,-1358.9129 867.9474,-1212.6125 969.5286,-1151 1028.5291,-1115.2142 1213.5896,-1153.3402 1279.5286,-1133 1291.9106,-1129.1805 1292.7718,-1123.4477 1304.5286,-1118 1327.1002,-1107.5412 1336.3891,-1113.1143 1357.5286,-1100 1413.591,-1065.2208 1466.3434,-1013.6252 1506.1316,-969.2493"/>
<polygon fill="#000000" stroke="#000000" points="1508.8801,-971.4254 1512.905,-961.6248 1503.6469,-966.7763 1508.8801,-971.4254"/>
<text text-anchor="middle" x="1347.0286" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge3" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M634.9426,-1416.1453C455.2428,-1381.5391 172.6034,-1297.465 31.5286,-1100 -25.2653,-1020.5045 12.5286,-978.699 12.5286,-881 12.5286,-881 12.5286,-881 12.5286,-351.5 12.5286,-253.4807 640.3548,-167.1768 983.1961,-127.3556"/>
<polygon fill="#000000" stroke="#000000" points="983.7241,-130.818 993.2553,-126.1911 982.9191,-123.8644 983.7241,-130.818"/>
<text text-anchor="middle" x="55.0286" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- imaging_file -->
<g id="node11" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M2245.5286,-1278C2245.5286,-1278 2579.5286,-1278 2579.5286,-1278 2585.5286,-1278 2591.5286,-1284 2591.5286,-1290 2591.5286,-1290 2591.5286,-1588 2591.5286,-1588 2591.5286,-1594 2585.5286,-1600 2579.5286,-1600 2579.5286,-1600 2245.5286,-1600 2245.5286,-1600 2239.5286,-1600 2233.5286,-1594 2233.5286,-1588 2233.5286,-1588 2233.5286,-1290 2233.5286,-1290 2233.5286,-1284 2239.5286,-1278 2245.5286,-1278"/>
<text text-anchor="middle" x="2285.5286" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="2337.5286,-1278 2337.5286,-1600 "/>
<text text-anchor="middle" x="2348.0286" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2358.5286,-1278 2358.5286,-1600 "/>
<text text-anchor="middle" x="2464.5286" y="-1584.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2358.5286,-1577 2570.5286,-1577 "/>
<text text-anchor="middle" x="2464.5286" y="-1561.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2358.5286,-1554 2570.5286,-1554 "/>
<text text-anchor="middle" x="2464.5286" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2358.5286,-1531 2570.5286,-1531 "/>
<text text-anchor="middle" x="2464.5286" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2358.5286,-1508 2570.5286,-1508 "/>
<text text-anchor="middle" x="2464.5286" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2358.5286,-1485 2570.5286,-1485 "/>
<text text-anchor="middle" x="2464.5286" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2358.5286,-1462 2570.5286,-1462 "/>
<text text-anchor="middle" x="2464.5286" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2358.5286,-1439 2570.5286,-1439 "/>
<text text-anchor="middle" x="2464.5286" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2358.5286,-1416 2570.5286,-1416 "/>
<text text-anchor="middle" x="2464.5286" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2358.5286,-1393 2570.5286,-1393 "/>
<text text-anchor="middle" x="2464.5286" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="2358.5286,-1370 2570.5286,-1370 "/>
<text text-anchor="middle" x="2464.5286" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="2358.5286,-1347 2570.5286,-1347 "/>
<text text-anchor="middle" x="2464.5286" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="2358.5286,-1324 2570.5286,-1324 "/>
<text text-anchor="middle" x="2464.5286" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2358.5286,-1301 2570.5286,-1301 "/>
<text text-anchor="middle" x="2464.5286" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="2570.5286,-1278 2570.5286,-1600 "/>
<text text-anchor="middle" x="2581.0286" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2331.2013,-1277.984C2302.3264,-1232.4418 2266.4146,-1185.8459 2224.5286,-1151 2087.5793,-1037.0687 1895.7388,-965.1572 1756.5378,-924.4587"/>
<polygon fill="#000000" stroke="#000000" points="1757.1868,-921.0028 1746.6078,-921.5822 1755.239,-927.7264 1757.1868,-921.0028"/>
<text text-anchor="middle" x="2249.0286" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- publication -->
<g id="node12" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M1429.5286,-333.5C1429.5286,-333.5 1639.5286,-333.5 1639.5286,-333.5 1645.5286,-333.5 1651.5286,-339.5 1651.5286,-345.5 1651.5286,-345.5 1651.5286,-357.5 1651.5286,-357.5 1651.5286,-363.5 1645.5286,-369.5 1639.5286,-369.5 1639.5286,-369.5 1429.5286,-369.5 1429.5286,-369.5 1423.5286,-369.5 1417.5286,-363.5 1417.5286,-357.5 1417.5286,-357.5 1417.5286,-345.5 1417.5286,-345.5 1417.5286,-339.5 1423.5286,-333.5 1429.5286,-333.5"/>
<text text-anchor="middle" x="1466.0286" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="1514.5286,-333.5 1514.5286,-369.5 "/>
<text text-anchor="middle" x="1525.0286" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1535.5286,-333.5 1535.5286,-369.5 "/>
<text text-anchor="middle" x="1583.0286" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="1630.5286,-333.5 1630.5286,-369.5 "/>
<text text-anchor="middle" x="1641.0286" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge10" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1517.861,-333.1282C1494.0055,-307.4184 1448.0721,-260.0418 1403.5286,-226 1398.096,-221.8482 1392.5126,-217.721 1386.821,-213.6327"/>
<polygon fill="#000000" stroke="#000000" points="1388.5924,-210.5983 1378.4096,-207.6724 1384.5453,-216.3098 1388.5924,-210.5983"/>
<text text-anchor="middle" x="1469.5286" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- diagnosis -->
<g id="node13" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M846.5286,-662.5C846.5286,-662.5 1220.5286,-662.5 1220.5286,-662.5 1226.5286,-662.5 1232.5286,-668.5 1232.5286,-674.5 1232.5286,-674.5 1232.5286,-1087.5 1232.5286,-1087.5 1232.5286,-1093.5 1226.5286,-1099.5 1220.5286,-1099.5 1220.5286,-1099.5 846.5286,-1099.5 846.5286,-1099.5 840.5286,-1099.5 834.5286,-1093.5 834.5286,-1087.5 834.5286,-1087.5 834.5286,-674.5 834.5286,-674.5 834.5286,-668.5 840.5286,-662.5 846.5286,-662.5"/>
<text text-anchor="middle" x="876.5286" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="918.5286,-662.5 918.5286,-1099.5 "/>
<text text-anchor="middle" x="929.0286" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="939.5286,-662.5 939.5286,-1099.5 "/>
<text text-anchor="middle" x="1075.5286" y="-1084.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="939.5286,-1076.5 1211.5286,-1076.5 "/>
<text text-anchor="middle" x="1075.5286" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="939.5286,-1053.5 1211.5286,-1053.5 "/>
<text text-anchor="middle" x="1075.5286" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="939.5286,-1030.5 1211.5286,-1030.5 "/>
<text text-anchor="middle" x="1075.5286" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="939.5286,-1007.5 1211.5286,-1007.5 "/>
<text text-anchor="middle" x="1075.5286" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="939.5286,-984.5 1211.5286,-984.5 "/>
<text text-anchor="middle" x="1075.5286" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="939.5286,-961.5 1211.5286,-961.5 "/>
<text text-anchor="middle" x="1075.5286" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="939.5286,-938.5 1211.5286,-938.5 "/>
<text text-anchor="middle" x="1075.5286" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="939.5286,-915.5 1211.5286,-915.5 "/>
<text text-anchor="middle" x="1075.5286" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="939.5286,-892.5 1211.5286,-892.5 "/>
<text text-anchor="middle" x="1075.5286" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="939.5286,-869.5 1211.5286,-869.5 "/>
<text text-anchor="middle" x="1075.5286" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="939.5286,-846.5 1211.5286,-846.5 "/>
<text text-anchor="middle" x="1075.5286" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="939.5286,-823.5 1211.5286,-823.5 "/>
<text text-anchor="middle" x="1075.5286" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="939.5286,-800.5 1211.5286,-800.5 "/>
<text text-anchor="middle" x="1075.5286" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="939.5286,-777.5 1211.5286,-777.5 "/>
<text text-anchor="middle" x="1075.5286" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="939.5286,-754.5 1211.5286,-754.5 "/>
<text text-anchor="middle" x="1075.5286" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="939.5286,-731.5 1211.5286,-731.5 "/>
<text text-anchor="middle" x="1075.5286" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="939.5286,-708.5 1211.5286,-708.5 "/>
<text text-anchor="middle" x="1075.5286" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="939.5286,-685.5 1211.5286,-685.5 "/>
<text text-anchor="middle" x="1075.5286" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1211.5286,-662.5 1211.5286,-1099.5 "/>
<text text-anchor="middle" x="1222.0286" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1033.5286,-662.2193C1033.5286,-647.476 1033.5286,-633.4001 1033.5286,-620.5497"/>
<polygon fill="#000000" stroke="#000000" points="1037.0287,-620.5173 1033.5286,-610.5174 1030.0287,-620.5174 1037.0287,-620.5173"/>
<text text-anchor="middle" x="1078.0286" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1513.288,-800.4C1472.8517,-754.2893 1417.1527,-698.5315 1357.5286,-662 1335.5975,-648.5629 1325.7208,-655.1201 1302.5286,-644 1291.5242,-638.7236 1290.5766,-634.1846 1279.5286,-629 1256.654,-618.2654 1231.8868,-608.5658 1207.1781,-599.9676"/>
<polygon fill="#000000" stroke="#000000" points="1208.3099,-596.6556 1197.7153,-596.7263 1206.0415,-603.2779 1208.3099,-596.6556"/>
<text text-anchor="middle" x="1339.0286" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge11" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1541.6228,-800.2514C1504.2024,-713.592 1445.9092,-571.212 1408.5286,-444 1384.8642,-363.466 1412.0214,-331.9663 1370.5286,-259 1361.783,-243.6206 1350.974,-228.9226 1339.0776,-215.1308"/>
<polygon fill="#000000" stroke="#000000" points="1341.6179,-212.7203 1332.3628,-207.5633 1336.3819,-217.3663 1341.6179,-212.7203"/>
<text text-anchor="middle" x="1454.0286" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_personnel -->
<g id="node15" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M1682.0286,-294C1682.0286,-294 1989.0286,-294 1989.0286,-294 1995.0286,-294 2001.0286,-300 2001.0286,-306 2001.0286,-306 2001.0286,-397 2001.0286,-397 2001.0286,-403 1995.0286,-409 1989.0286,-409 1989.0286,-409 1682.0286,-409 1682.0286,-409 1676.0286,-409 1670.0286,-403 1670.0286,-397 1670.0286,-397 1670.0286,-306 1670.0286,-306 1670.0286,-300 1676.0286,-294 1682.0286,-294"/>
<text text-anchor="middle" x="1737.0286" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="1804.0286,-294 1804.0286,-409 "/>
<text text-anchor="middle" x="1814.5286" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1825.0286,-294 1825.0286,-409 "/>
<text text-anchor="middle" x="1902.5286" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="1825.0286,-386 1980.0286,-386 "/>
<text text-anchor="middle" x="1902.5286" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="1825.0286,-363 1980.0286,-363 "/>
<text text-anchor="middle" x="1902.5286" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="1825.0286,-340 1980.0286,-340 "/>
<text text-anchor="middle" x="1902.5286" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="1825.0286,-317 1980.0286,-317 "/>
<text text-anchor="middle" x="1902.5286" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="1980.0286,-294 1980.0286,-409 "/>
<text text-anchor="middle" x="1990.5286" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge14" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1733.2346,-293.9019C1709.6996,-281.6449 1684.5268,-269.3058 1660.5286,-259 1582.7427,-225.5956 1495.174,-194.5406 1417.4772,-169.1346"/>
<polygon fill="#000000" stroke="#000000" points="1418.1559,-165.6748 1407.5636,-165.9061 1415.9882,-172.3308 1418.1559,-165.6748"/>
<text text-anchor="middle" x="1681.0286" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- study_admin -->
<g id="node16" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M2031.5286,-259.5C2031.5286,-259.5 2357.5286,-259.5 2357.5286,-259.5 2363.5286,-259.5 2369.5286,-265.5 2369.5286,-271.5 2369.5286,-271.5 2369.5286,-431.5 2369.5286,-431.5 2369.5286,-437.5 2363.5286,-443.5 2357.5286,-443.5 2357.5286,-443.5 2031.5286,-443.5 2031.5286,-443.5 2025.5286,-443.5 2019.5286,-437.5 2019.5286,-431.5 2019.5286,-431.5 2019.5286,-271.5 2019.5286,-271.5 2019.5286,-265.5 2025.5286,-259.5 2031.5286,-259.5"/>
<text text-anchor="middle" x="2073.5286" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="2127.5286,-259.5 2127.5286,-443.5 "/>
<text text-anchor="middle" x="2138.0286" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2148.5286,-259.5 2148.5286,-443.5 "/>
<text text-anchor="middle" x="2248.5286" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="2148.5286,-420.5 2348.5286,-420.5 "/>
<text text-anchor="middle" x="2248.5286" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="2148.5286,-397.5 2348.5286,-397.5 "/>
<text text-anchor="middle" x="2248.5286" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="2148.5286,-374.5 2348.5286,-374.5 "/>
<text text-anchor="middle" x="2248.5286" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="2148.5286,-351.5 2348.5286,-351.5 "/>
<text text-anchor="middle" x="2248.5286" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="2148.5286,-328.5 2348.5286,-328.5 "/>
<text text-anchor="middle" x="2248.5286" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="2148.5286,-305.5 2348.5286,-305.5 "/>
<text text-anchor="middle" x="2248.5286" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="2148.5286,-282.5 2348.5286,-282.5 "/>
<text text-anchor="middle" x="2248.5286" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="2348.5286,-259.5 2348.5286,-443.5 "/>
<text text-anchor="middle" x="2359.0286" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge15" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2019.4484,-262.1326C2016.4656,-261.0517 2013.4909,-260.0062 2010.5286,-259 1815.3289,-192.6958 1583.4696,-151.9433 1417.9384,-128.9745"/>
<polygon fill="#000000" stroke="#000000" points="1418.0133,-125.4518 1407.6293,-127.5551 1417.0585,-132.3864 1418.0133,-125.4518"/>
<text text-anchor="middle" x="2003.0286" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
</g>
</svg>
</div>
