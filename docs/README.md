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
<svg width="3280pt" height="1574pt"
 viewBox="0.00 0.00 3280.00 1574.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1570)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1570 3276,-1570 3276,4 -4,4"/>
<!-- participant -->
<g id="node1" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M1341,-495.5C1341,-495.5 1572,-495.5 1572,-495.5 1578,-495.5 1584,-501.5 1584,-507.5 1584,-507.5 1584,-575.5 1584,-575.5 1584,-581.5 1578,-587.5 1572,-587.5 1572,-587.5 1341,-587.5 1341,-587.5 1335,-587.5 1329,-581.5 1329,-575.5 1329,-575.5 1329,-507.5 1329,-507.5 1329,-501.5 1335,-495.5 1341,-495.5"/>
<text text-anchor="middle" x="1377" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1425,-495.5 1425,-587.5 "/>
<text text-anchor="middle" x="1435.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1446,-495.5 1446,-587.5 "/>
<text text-anchor="middle" x="1504.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="1446,-564.5 1563,-564.5 "/>
<text text-anchor="middle" x="1504.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="1446,-541.5 1563,-541.5 "/>
<text text-anchor="middle" x="1504.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1446,-518.5 1563,-518.5 "/>
<text text-anchor="middle" x="1504.5" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1563,-495.5 1563,-587.5 "/>
<text text-anchor="middle" x="1573.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node4" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M1253.5,-.5C1253.5,-.5 1643.5,-.5 1643.5,-.5 1649.5,-.5 1655.5,-6.5 1655.5,-12.5 1655.5,-12.5 1655.5,-195.5 1655.5,-195.5 1655.5,-201.5 1649.5,-207.5 1643.5,-207.5 1643.5,-207.5 1253.5,-207.5 1253.5,-207.5 1247.5,-207.5 1241.5,-201.5 1241.5,-195.5 1241.5,-195.5 1241.5,-12.5 1241.5,-12.5 1241.5,-6.5 1247.5,-.5 1253.5,-.5"/>
<text text-anchor="middle" x="1269.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="1297.5,-.5 1297.5,-207.5 "/>
<text text-anchor="middle" x="1308" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1318.5,-.5 1318.5,-207.5 "/>
<text text-anchor="middle" x="1476.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="1318.5,-184.5 1634.5,-184.5 "/>
<text text-anchor="middle" x="1476.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="1318.5,-161.5 1634.5,-161.5 "/>
<text text-anchor="middle" x="1476.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="1318.5,-138.5 1634.5,-138.5 "/>
<text text-anchor="middle" x="1476.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="1318.5,-115.5 1634.5,-115.5 "/>
<text text-anchor="middle" x="1476.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="1318.5,-92.5 1634.5,-92.5 "/>
<text text-anchor="middle" x="1476.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="1318.5,-69.5 1634.5,-69.5 "/>
<text text-anchor="middle" x="1476.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="1318.5,-46.5 1634.5,-46.5 "/>
<text text-anchor="middle" x="1476.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="1318.5,-23.5 1634.5,-23.5 "/>
<text text-anchor="middle" x="1476.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="1634.5,-.5 1634.5,-207.5 "/>
<text text-anchor="middle" x="1645" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge9" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1532.4568,-495.4401C1549.3951,-481.2192 1565.1027,-463.9549 1574.5,-444 1609.5306,-369.6135 1596.6239,-338.1898 1574.5,-259 1570.3665,-244.2047 1563.891,-229.8888 1556.0076,-216.3293"/>
<polygon fill="#000000" stroke="#000000" points="1558.8332,-214.2408 1550.6342,-207.5306 1552.8592,-217.8892 1558.8332,-214.2408"/>
<text text-anchor="middle" x="1646" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_arm -->
<g id="node14" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M1004,-317C1004,-317 1301,-317 1301,-317 1307,-317 1313,-323 1313,-329 1313,-329 1313,-374 1313,-374 1313,-380 1307,-386 1301,-386 1301,-386 1004,-386 1004,-386 998,-386 992,-380 992,-374 992,-374 992,-329 992,-329 992,-323 998,-317 1004,-317"/>
<text text-anchor="middle" x="1038" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="1084,-317 1084,-386 "/>
<text text-anchor="middle" x="1094.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1105,-317 1105,-386 "/>
<text text-anchor="middle" x="1198.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="1105,-363 1292,-363 "/>
<text text-anchor="middle" x="1198.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="1105,-340 1292,-340 "/>
<text text-anchor="middle" x="1198.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="1292,-317 1292,-386 "/>
<text text-anchor="middle" x="1302.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge8" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1382.522,-495.2637C1331.7881,-463.5551 1265.1438,-421.9024 1216.6569,-391.5981"/>
<polygon fill="#000000" stroke="#000000" points="1218.462,-388.5989 1208.127,-386.2669 1214.752,-394.5349 1218.462,-388.5989"/>
<text text-anchor="middle" x="1399" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_funding -->
<g id="node2" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M12,-317C12,-317 391,-317 391,-317 397,-317 403,-323 403,-329 403,-329 403,-374 403,-374 403,-380 397,-386 391,-386 391,-386 12,-386 12,-386 6,-386 0,-380 0,-374 0,-374 0,-329 0,-329 0,-323 6,-317 12,-317"/>
<text text-anchor="middle" x="59.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="119,-317 119,-386 "/>
<text text-anchor="middle" x="129.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="140,-317 140,-386 "/>
<text text-anchor="middle" x="261" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="140,-363 382,-363 "/>
<text text-anchor="middle" x="261" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="140,-340 382,-340 "/>
<text text-anchor="middle" x="261" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="382,-317 382,-386 "/>
<text text-anchor="middle" x="392.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge13" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M216.792,-316.9042C231.8026,-287.4042 257.6654,-246.5999 293.5,-226 372.7518,-180.4414 919.2931,-138.2091 1231.3261,-117.4516"/>
<polygon fill="#000000" stroke="#000000" points="1231.6607,-120.9372 1241.4072,-116.783 1231.1974,-113.9525 1231.6607,-120.9372"/>
<text text-anchor="middle" x="355.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- sequencing_file -->
<g id="node3" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M2791,-990.5C2791,-990.5 3260,-990.5 3260,-990.5 3266,-990.5 3272,-996.5 3272,-1002.5 3272,-1002.5 3272,-1553.5 3272,-1553.5 3272,-1559.5 3266,-1565.5 3260,-1565.5 3260,-1565.5 2791,-1565.5 2791,-1565.5 2785,-1565.5 2779,-1559.5 2779,-1553.5 2779,-1553.5 2779,-1002.5 2779,-1002.5 2779,-996.5 2785,-990.5 2791,-990.5"/>
<text text-anchor="middle" x="2843" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="2907,-990.5 2907,-1565.5 "/>
<text text-anchor="middle" x="2917.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2928,-990.5 2928,-1565.5 "/>
<text text-anchor="middle" x="3089.5" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="2928,-1542.5 3251,-1542.5 "/>
<text text-anchor="middle" x="3089.5" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2928,-1519.5 3251,-1519.5 "/>
<text text-anchor="middle" x="3089.5" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2928,-1496.5 3251,-1496.5 "/>
<text text-anchor="middle" x="3089.5" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="2928,-1473.5 3251,-1473.5 "/>
<text text-anchor="middle" x="3089.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="2928,-1450.5 3251,-1450.5 "/>
<text text-anchor="middle" x="3089.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2928,-1427.5 3251,-1427.5 "/>
<text text-anchor="middle" x="3089.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="2928,-1404.5 3251,-1404.5 "/>
<text text-anchor="middle" x="3089.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2928,-1381.5 3251,-1381.5 "/>
<text text-anchor="middle" x="3089.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2928,-1358.5 3251,-1358.5 "/>
<text text-anchor="middle" x="3089.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2928,-1335.5 3251,-1335.5 "/>
<text text-anchor="middle" x="3089.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2928,-1312.5 3251,-1312.5 "/>
<text text-anchor="middle" x="3089.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2928,-1289.5 3251,-1289.5 "/>
<text text-anchor="middle" x="3089.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2928,-1266.5 3251,-1266.5 "/>
<text text-anchor="middle" x="3089.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="2928,-1243.5 3251,-1243.5 "/>
<text text-anchor="middle" x="3089.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="2928,-1220.5 3251,-1220.5 "/>
<text text-anchor="middle" x="3089.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="2928,-1197.5 3251,-1197.5 "/>
<text text-anchor="middle" x="3089.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="2928,-1174.5 3251,-1174.5 "/>
<text text-anchor="middle" x="3089.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="2928,-1151.5 3251,-1151.5 "/>
<text text-anchor="middle" x="3089.5" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="2928,-1128.5 3251,-1128.5 "/>
<text text-anchor="middle" x="3089.5" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2928,-1105.5 3251,-1105.5 "/>
<text text-anchor="middle" x="3089.5" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="2928,-1082.5 3251,-1082.5 "/>
<text text-anchor="middle" x="3089.5" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="2928,-1059.5 3251,-1059.5 "/>
<text text-anchor="middle" x="3089.5" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="2928,-1036.5 3251,-1036.5 "/>
<text text-anchor="middle" x="3089.5" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="2928,-1013.5 3251,-1013.5 "/>
<text text-anchor="middle" x="3089.5" y="-998.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="3251,-990.5 3251,-1565.5 "/>
<text text-anchor="middle" x="3261.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node13" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1811.5,-720C1811.5,-720 2125.5,-720 2125.5,-720 2131.5,-720 2137.5,-726 2137.5,-732 2137.5,-732 2137.5,-846 2137.5,-846 2137.5,-852 2131.5,-858 2125.5,-858 2125.5,-858 1811.5,-858 1811.5,-858 1805.5,-858 1799.5,-852 1799.5,-846 1799.5,-846 1799.5,-732 1799.5,-732 1799.5,-726 1805.5,-720 1811.5,-720"/>
<text text-anchor="middle" x="1833.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1867.5,-720 1867.5,-858 "/>
<text text-anchor="middle" x="1878" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1888.5,-720 1888.5,-858 "/>
<text text-anchor="middle" x="2002.5" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1888.5,-835 2116.5,-835 "/>
<text text-anchor="middle" x="2002.5" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1888.5,-812 2116.5,-812 "/>
<text text-anchor="middle" x="2002.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1888.5,-789 2116.5,-789 "/>
<text text-anchor="middle" x="2002.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1888.5,-766 2116.5,-766 "/>
<text text-anchor="middle" x="2002.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1888.5,-743 2116.5,-743 "/>
<text text-anchor="middle" x="2002.5" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="2116.5,-720 2116.5,-858 "/>
<text text-anchor="middle" x="2127" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2778.5948,-995.0524C2775.9097,-993.3316 2773.2112,-991.6468 2770.5,-990 2577.4363,-872.7362 2318.6798,-823.6873 2147.9464,-803.2989"/>
<polygon fill="#000000" stroke="#000000" points="2148.1889,-799.8034 2137.8492,-802.1143 2147.3732,-806.7557 2148.1889,-799.8034"/>
<text text-anchor="middle" x="2798" y="-960.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node5" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M471.5,-662.5C471.5,-662.5 823.5,-662.5 823.5,-662.5 829.5,-662.5 835.5,-668.5 835.5,-674.5 835.5,-674.5 835.5,-903.5 835.5,-903.5 835.5,-909.5 829.5,-915.5 823.5,-915.5 823.5,-915.5 471.5,-915.5 471.5,-915.5 465.5,-915.5 459.5,-909.5 459.5,-903.5 459.5,-903.5 459.5,-674.5 459.5,-674.5 459.5,-668.5 465.5,-662.5 471.5,-662.5"/>
<text text-anchor="middle" x="543" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="626.5,-662.5 626.5,-915.5 "/>
<text text-anchor="middle" x="637" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="647.5,-662.5 647.5,-915.5 "/>
<text text-anchor="middle" x="731" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="647.5,-892.5 814.5,-892.5 "/>
<text text-anchor="middle" x="731" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="647.5,-869.5 814.5,-869.5 "/>
<text text-anchor="middle" x="731" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="647.5,-846.5 814.5,-846.5 "/>
<text text-anchor="middle" x="731" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="647.5,-823.5 814.5,-823.5 "/>
<text text-anchor="middle" x="731" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="647.5,-800.5 814.5,-800.5 "/>
<text text-anchor="middle" x="731" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="647.5,-777.5 814.5,-777.5 "/>
<text text-anchor="middle" x="731" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="647.5,-754.5 814.5,-754.5 "/>
<text text-anchor="middle" x="731" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="647.5,-731.5 814.5,-731.5 "/>
<text text-anchor="middle" x="731" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="647.5,-708.5 814.5,-708.5 "/>
<text text-anchor="middle" x="731" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="647.5,-685.5 814.5,-685.5 "/>
<text text-anchor="middle" x="731" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="814.5,-662.5 814.5,-915.5 "/>
<text text-anchor="middle" x="825" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M801.7913,-662.4548C815.7958,-653.792 830.1283,-645.8142 844.5,-639 926.25,-600.239 1164.7256,-570.3261 1318.7179,-554.3648"/>
<polygon fill="#000000" stroke="#000000" points="1319.1473,-557.8392 1328.7364,-553.3337 1318.4305,-550.8759 1319.1473,-557.8392"/>
<text text-anchor="middle" x="1086" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge20" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M697.5226,-662.3477C751.0479,-542.33 846.9583,-365.0914 982.5,-259 1054.3402,-202.7692 1147.5368,-166.4655 1231.6865,-143.2547"/>
<polygon fill="#000000" stroke="#000000" points="1232.6376,-146.6232 1241.3737,-140.629 1230.8063,-139.867 1232.6376,-146.6232"/>
<text text-anchor="middle" x="889.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- imaging_file -->
<g id="node6" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M1521.5,-1117C1521.5,-1117 1855.5,-1117 1855.5,-1117 1861.5,-1117 1867.5,-1123 1867.5,-1129 1867.5,-1129 1867.5,-1427 1867.5,-1427 1867.5,-1433 1861.5,-1439 1855.5,-1439 1855.5,-1439 1521.5,-1439 1521.5,-1439 1515.5,-1439 1509.5,-1433 1509.5,-1427 1509.5,-1427 1509.5,-1129 1509.5,-1129 1509.5,-1123 1515.5,-1117 1521.5,-1117"/>
<text text-anchor="middle" x="1561.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="1613.5,-1117 1613.5,-1439 "/>
<text text-anchor="middle" x="1624" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1634.5,-1117 1634.5,-1439 "/>
<text text-anchor="middle" x="1740.5" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1634.5,-1416 1846.5,-1416 "/>
<text text-anchor="middle" x="1740.5" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1634.5,-1393 1846.5,-1393 "/>
<text text-anchor="middle" x="1740.5" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1634.5,-1370 1846.5,-1370 "/>
<text text-anchor="middle" x="1740.5" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1634.5,-1347 1846.5,-1347 "/>
<text text-anchor="middle" x="1740.5" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1634.5,-1324 1846.5,-1324 "/>
<text text-anchor="middle" x="1740.5" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1634.5,-1301 1846.5,-1301 "/>
<text text-anchor="middle" x="1740.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1634.5,-1278 1846.5,-1278 "/>
<text text-anchor="middle" x="1740.5" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1634.5,-1255 1846.5,-1255 "/>
<text text-anchor="middle" x="1740.5" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1634.5,-1232 1846.5,-1232 "/>
<text text-anchor="middle" x="1740.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="1634.5,-1209 1846.5,-1209 "/>
<text text-anchor="middle" x="1740.5" y="-1193.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="1634.5,-1186 1846.5,-1186 "/>
<text text-anchor="middle" x="1740.5" y="-1170.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="1634.5,-1163 1846.5,-1163 "/>
<text text-anchor="middle" x="1740.5" y="-1147.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1634.5,-1140 1846.5,-1140 "/>
<text text-anchor="middle" x="1740.5" y="-1124.8" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="1846.5,-1117 1846.5,-1439 "/>
<text text-anchor="middle" x="1857" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1780.7643,-1116.8669C1828.8769,-1032.8418 1885.534,-933.8942 1923.9248,-866.8474"/>
<polygon fill="#000000" stroke="#000000" points="1927.0512,-868.431 1928.9829,-858.0138 1920.9765,-864.9527 1927.0512,-868.431"/>
<text text-anchor="middle" x="1924" y="-960.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- therapeutic_procedure -->
<g id="node7" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M866,-731.5C866,-731.5 1223,-731.5 1223,-731.5 1229,-731.5 1235,-737.5 1235,-743.5 1235,-743.5 1235,-834.5 1235,-834.5 1235,-840.5 1229,-846.5 1223,-846.5 1223,-846.5 866,-846.5 866,-846.5 860,-846.5 854,-840.5 854,-834.5 854,-834.5 854,-743.5 854,-743.5 854,-737.5 860,-731.5 866,-731.5"/>
<text text-anchor="middle" x="944.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="1035,-731.5 1035,-846.5 "/>
<text text-anchor="middle" x="1045.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1056,-731.5 1056,-846.5 "/>
<text text-anchor="middle" x="1135" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="1056,-823.5 1214,-823.5 "/>
<text text-anchor="middle" x="1135" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="1056,-800.5 1214,-800.5 "/>
<text text-anchor="middle" x="1135" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1056,-777.5 1214,-777.5 "/>
<text text-anchor="middle" x="1135" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="1056,-754.5 1214,-754.5 "/>
<text text-anchor="middle" x="1135" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1214,-731.5 1214,-846.5 "/>
<text text-anchor="middle" x="1224.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1102.3094,-731.2941C1144.7468,-691.5747 1205.414,-640.0353 1266.5,-606 1283.0198,-596.7957 1301.0773,-588.5945 1319.2776,-581.3851"/>
<polygon fill="#000000" stroke="#000000" points="1320.7344,-584.5744 1328.8008,-577.7053 1318.2114,-578.0449 1320.7344,-584.5744"/>
<text text-anchor="middle" x="1359.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- publication -->
<g id="node8" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M1343.5,-333.5C1343.5,-333.5 1553.5,-333.5 1553.5,-333.5 1559.5,-333.5 1565.5,-339.5 1565.5,-345.5 1565.5,-345.5 1565.5,-357.5 1565.5,-357.5 1565.5,-363.5 1559.5,-369.5 1553.5,-369.5 1553.5,-369.5 1343.5,-369.5 1343.5,-369.5 1337.5,-369.5 1331.5,-363.5 1331.5,-357.5 1331.5,-357.5 1331.5,-345.5 1331.5,-345.5 1331.5,-339.5 1337.5,-333.5 1343.5,-333.5"/>
<text text-anchor="middle" x="1380" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="1428.5,-333.5 1428.5,-369.5 "/>
<text text-anchor="middle" x="1439" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1449.5,-333.5 1449.5,-369.5 "/>
<text text-anchor="middle" x="1497" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="1544.5,-333.5 1544.5,-369.5 "/>
<text text-anchor="middle" x="1555" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge18" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1448.5,-333.3007C1448.5,-308.5479 1448.5,-262.2296 1448.5,-217.6668"/>
<polygon fill="#000000" stroke="#000000" points="1452.0001,-217.5961 1448.5,-207.5961 1445.0001,-217.5961 1452.0001,-217.5961"/>
<text text-anchor="middle" x="1499.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- sample_diagnosis -->
<g id="node9" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M1897.5,-1059.5C1897.5,-1059.5 2339.5,-1059.5 2339.5,-1059.5 2345.5,-1059.5 2351.5,-1065.5 2351.5,-1071.5 2351.5,-1071.5 2351.5,-1484.5 2351.5,-1484.5 2351.5,-1490.5 2345.5,-1496.5 2339.5,-1496.5 2339.5,-1496.5 1897.5,-1496.5 1897.5,-1496.5 1891.5,-1496.5 1885.5,-1490.5 1885.5,-1484.5 1885.5,-1484.5 1885.5,-1071.5 1885.5,-1071.5 1885.5,-1065.5 1891.5,-1059.5 1897.5,-1059.5"/>
<text text-anchor="middle" x="1957" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2028.5,-1059.5 2028.5,-1496.5 "/>
<text text-anchor="middle" x="2039" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2049.5,-1059.5 2049.5,-1496.5 "/>
<text text-anchor="middle" x="2190" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2049.5,-1473.5 2330.5,-1473.5 "/>
<text text-anchor="middle" x="2190" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="2049.5,-1450.5 2330.5,-1450.5 "/>
<text text-anchor="middle" x="2190" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2049.5,-1427.5 2330.5,-1427.5 "/>
<text text-anchor="middle" x="2190" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="2049.5,-1404.5 2330.5,-1404.5 "/>
<text text-anchor="middle" x="2190" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="2049.5,-1381.5 2330.5,-1381.5 "/>
<text text-anchor="middle" x="2190" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2049.5,-1358.5 2330.5,-1358.5 "/>
<text text-anchor="middle" x="2190" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2049.5,-1335.5 2330.5,-1335.5 "/>
<text text-anchor="middle" x="2190" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis_reference_source</text>
<polyline fill="none" stroke="#000000" points="2049.5,-1312.5 2330.5,-1312.5 "/>
<text text-anchor="middle" x="2190" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="2049.5,-1289.5 2330.5,-1289.5 "/>
<text text-anchor="middle" x="2190" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="2049.5,-1266.5 2330.5,-1266.5 "/>
<text text-anchor="middle" x="2190" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="2049.5,-1243.5 2330.5,-1243.5 "/>
<text text-anchor="middle" x="2190" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="2049.5,-1220.5 2330.5,-1220.5 "/>
<text text-anchor="middle" x="2190" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="2049.5,-1197.5 2330.5,-1197.5 "/>
<text text-anchor="middle" x="2190" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="2049.5,-1174.5 2330.5,-1174.5 "/>
<text text-anchor="middle" x="2190" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="2049.5,-1151.5 2330.5,-1151.5 "/>
<text text-anchor="middle" x="2190" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="2049.5,-1128.5 2330.5,-1128.5 "/>
<text text-anchor="middle" x="2190" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="2049.5,-1105.5 2330.5,-1105.5 "/>
<text text-anchor="middle" x="2190" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="2049.5,-1082.5 2330.5,-1082.5 "/>
<text text-anchor="middle" x="2190" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="2330.5,-1059.5 2330.5,-1496.5 "/>
<text text-anchor="middle" x="2341" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2051.3971,-1059.2446C2030.4752,-991.0393 2008.7244,-920.1317 1992.7547,-868.0702"/>
<polygon fill="#000000" stroke="#000000" points="1996.0196,-866.7788 1989.7408,-858.2449 1989.3273,-868.8317 1996.0196,-866.7788"/>
<text text-anchor="middle" x="2094.5" y="-960.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
<!-- synonym -->
<g id="node10" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M1178,-1255C1178,-1255 1479,-1255 1479,-1255 1485,-1255 1491,-1261 1491,-1267 1491,-1267 1491,-1289 1491,-1289 1491,-1295 1485,-1301 1479,-1301 1479,-1301 1178,-1301 1178,-1301 1172,-1301 1166,-1295 1166,-1289 1166,-1289 1166,-1267 1166,-1267 1166,-1261 1172,-1255 1178,-1255"/>
<text text-anchor="middle" x="1206" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="1246,-1255 1246,-1301 "/>
<text text-anchor="middle" x="1256.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1267,-1255 1267,-1301 "/>
<text text-anchor="middle" x="1368.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="1267,-1278 1470,-1278 "/>
<text text-anchor="middle" x="1368.5" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="1470,-1255 1470,-1301 "/>
<text text-anchor="middle" x="1480.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1335.8517,-1254.6247C1354.2862,-1199.8512 1407.7634,-1062.3834 1500.5,-990 1562.3475,-941.7264 1622.718,-1001.9834 1669.5,-939 1709.2518,-885.4814 1705.5181,-695.0994 1669.5,-639 1651.5788,-611.0871 1623.4558,-591.0634 1593.4509,-576.7353"/>
<polygon fill="#000000" stroke="#000000" points="1594.639,-573.4305 1584.0878,-572.4691 1591.7365,-579.8004 1594.639,-573.4305"/>
<text text-anchor="middle" x="1740" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge3" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1165.9762,-1264.34C963.9599,-1238.0401 624.6167,-1161.4299 450.5,-939 409.0784,-886.0849 431.5,-856.1994 431.5,-789 431.5,-789 431.5,-789 431.5,-351.5 431.5,-188.2203 932.6642,-132.2166 1231.3703,-113.3381"/>
<polygon fill="#000000" stroke="#000000" points="1231.706,-116.824 1241.469,-112.709 1231.2708,-109.8376 1231.706,-116.824"/>
<text text-anchor="middle" x="474" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1334.4442,-1254.9852C1350.3749,-1198.5033 1399.8146,-1053.0658 1500.5,-990 1539.6311,-965.4897 1662.6884,-983.132 1707.5,-972 1744.0313,-962.925 1753.2811,-958.4636 1785.5,-939 1820.5211,-917.8436 1855.9919,-890.4443 1886.2615,-864.8621"/>
<polygon fill="#000000" stroke="#000000" points="1888.9087,-867.2045 1894.2476,-858.0531 1884.3672,-861.8777 1888.9087,-867.2045"/>
<text text-anchor="middle" x="1795" y="-960.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study_personnel -->
<g id="node11" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M1858,-294C1858,-294 2165,-294 2165,-294 2171,-294 2177,-300 2177,-306 2177,-306 2177,-397 2177,-397 2177,-403 2171,-409 2165,-409 2165,-409 1858,-409 1858,-409 1852,-409 1846,-403 1846,-397 1846,-397 1846,-306 1846,-306 1846,-300 1852,-294 1858,-294"/>
<text text-anchor="middle" x="1913" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="1980,-294 1980,-409 "/>
<text text-anchor="middle" x="1990.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2001,-294 2001,-409 "/>
<text text-anchor="middle" x="2078.5" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="2001,-386 2156,-386 "/>
<text text-anchor="middle" x="2078.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="2001,-363 2156,-363 "/>
<text text-anchor="middle" x="2078.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="2001,-340 2156,-340 "/>
<text text-anchor="middle" x="2078.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="2001,-317 2156,-317 "/>
<text text-anchor="middle" x="2078.5" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="2156,-294 2156,-409 "/>
<text text-anchor="middle" x="2166.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge16" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1939.3054,-293.7033C1907.5927,-270.332 1869.0751,-244.5519 1831.5,-226 1779.4464,-200.2997 1720.7804,-178.4197 1665.2958,-160.591"/>
<polygon fill="#000000" stroke="#000000" points="1666.2906,-157.2346 1655.7001,-157.5374 1664.1679,-163.9051 1666.2906,-157.2346"/>
<text text-anchor="middle" x="1927" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- study_admin -->
<g id="node12" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M2207.5,-259.5C2207.5,-259.5 2533.5,-259.5 2533.5,-259.5 2539.5,-259.5 2545.5,-265.5 2545.5,-271.5 2545.5,-271.5 2545.5,-431.5 2545.5,-431.5 2545.5,-437.5 2539.5,-443.5 2533.5,-443.5 2533.5,-443.5 2207.5,-443.5 2207.5,-443.5 2201.5,-443.5 2195.5,-437.5 2195.5,-431.5 2195.5,-431.5 2195.5,-271.5 2195.5,-271.5 2195.5,-265.5 2201.5,-259.5 2207.5,-259.5"/>
<text text-anchor="middle" x="2249.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="2303.5,-259.5 2303.5,-443.5 "/>
<text text-anchor="middle" x="2314" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2324.5,-259.5 2324.5,-443.5 "/>
<text text-anchor="middle" x="2424.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="2324.5,-420.5 2524.5,-420.5 "/>
<text text-anchor="middle" x="2424.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="2324.5,-397.5 2524.5,-397.5 "/>
<text text-anchor="middle" x="2424.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="2324.5,-374.5 2524.5,-374.5 "/>
<text text-anchor="middle" x="2424.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="2324.5,-351.5 2524.5,-351.5 "/>
<text text-anchor="middle" x="2424.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="2324.5,-328.5 2524.5,-328.5 "/>
<text text-anchor="middle" x="2424.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="2324.5,-305.5 2524.5,-305.5 "/>
<text text-anchor="middle" x="2424.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="2324.5,-282.5 2524.5,-282.5 "/>
<text text-anchor="middle" x="2424.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="2524.5,-259.5 2524.5,-443.5 "/>
<text text-anchor="middle" x="2535" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge10" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2195.3942,-262.2068C2192.4193,-261.1029 2189.4531,-260.0327 2186.5,-259 2016.0131,-199.3786 1814.9577,-159.0037 1665.7891,-134.4459"/>
<polygon fill="#000000" stroke="#000000" points="1666.0237,-130.9379 1655.5899,-132.7781 1664.894,-137.8461 1666.0237,-130.9379"/>
<text text-anchor="middle" x="2185" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1896.9268,-719.8612C1864.8421,-691.7509 1825.3046,-660.8206 1785.5,-639 1762.9463,-626.6363 1753.6921,-632.1201 1730.5,-621 1719.4955,-615.7236 1718.6695,-610.9174 1707.5,-606 1671.8732,-590.3153 1631.6585,-577.8652 1594.0263,-568.2548"/>
<polygon fill="#000000" stroke="#000000" points="1594.5552,-564.7793 1584.0046,-565.7461 1592.8553,-571.5698 1594.5552,-564.7793"/>
<text text-anchor="middle" x="1767" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge5" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1947.3092,-719.9431C1911.2036,-611.3349 1828.9523,-398.6196 1700.5,-259 1685.6474,-242.8562 1668.7367,-227.7849 1650.868,-213.8775"/>
<polygon fill="#000000" stroke="#000000" points="1652.6691,-210.8495 1642.5946,-207.5699 1648.425,-216.4162 1652.6691,-210.8495"/>
<text text-anchor="middle" x="1882" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge7" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1193.9692,-316.8256C1226.0811,-289.9753 1272.4268,-251.2234 1316.795,-214.1249"/>
<polygon fill="#000000" stroke="#000000" points="1319.0458,-216.8053 1324.4723,-207.7056 1314.5556,-211.4352 1319.0458,-216.8053"/>
<text text-anchor="middle" x="1349" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- diagnosis -->
<g id="node15" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1265,-639.5C1265,-639.5 1648,-639.5 1648,-639.5 1654,-639.5 1660,-645.5 1660,-651.5 1660,-651.5 1660,-926.5 1660,-926.5 1660,-932.5 1654,-938.5 1648,-938.5 1648,-938.5 1265,-938.5 1265,-938.5 1259,-938.5 1253,-932.5 1253,-926.5 1253,-926.5 1253,-651.5 1253,-651.5 1253,-645.5 1259,-639.5 1265,-639.5"/>
<text text-anchor="middle" x="1295" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1337,-639.5 1337,-938.5 "/>
<text text-anchor="middle" x="1347.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1358,-639.5 1358,-938.5 "/>
<text text-anchor="middle" x="1498.5" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1358,-915.5 1639,-915.5 "/>
<text text-anchor="middle" x="1498.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1358,-892.5 1639,-892.5 "/>
<text text-anchor="middle" x="1498.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1358,-869.5 1639,-869.5 "/>
<text text-anchor="middle" x="1498.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1358,-846.5 1639,-846.5 "/>
<text text-anchor="middle" x="1498.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1358,-823.5 1639,-823.5 "/>
<text text-anchor="middle" x="1498.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="1358,-800.5 1639,-800.5 "/>
<text text-anchor="middle" x="1498.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1358,-777.5 1639,-777.5 "/>
<text text-anchor="middle" x="1498.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1358,-754.5 1639,-754.5 "/>
<text text-anchor="middle" x="1498.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis_reference_source</text>
<polyline fill="none" stroke="#000000" points="1358,-731.5 1639,-731.5 "/>
<text text-anchor="middle" x="1498.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="1358,-708.5 1639,-708.5 "/>
<text text-anchor="middle" x="1498.5" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="1358,-685.5 1639,-685.5 "/>
<text text-anchor="middle" x="1498.5" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="1358,-662.5 1639,-662.5 "/>
<text text-anchor="middle" x="1498.5" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="1639,-639.5 1639,-938.5 "/>
<text text-anchor="middle" x="1649.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1456.5,-639.3186C1456.5,-624.7641 1456.5,-610.7108 1456.5,-598.0135"/>
<polygon fill="#000000" stroke="#000000" points="1460.0001,-597.6855 1456.5,-587.6855 1453.0001,-597.6855 1460.0001,-597.6855"/>
<text text-anchor="middle" x="1501" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- methylation_array_file -->
<g id="node16" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M2382,-1163C2382,-1163 2749,-1163 2749,-1163 2755,-1163 2761,-1169 2761,-1175 2761,-1175 2761,-1381 2761,-1381 2761,-1387 2755,-1393 2749,-1393 2749,-1393 2382,-1393 2382,-1393 2376,-1393 2370,-1387 2370,-1381 2370,-1381 2370,-1175 2370,-1175 2370,-1169 2376,-1163 2382,-1163"/>
<text text-anchor="middle" x="2459" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="2548,-1163 2548,-1393 "/>
<text text-anchor="middle" x="2558.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2569,-1163 2569,-1393 "/>
<text text-anchor="middle" x="2654.5" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2569,-1370 2740,-1370 "/>
<text text-anchor="middle" x="2654.5" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2569,-1347 2740,-1347 "/>
<text text-anchor="middle" x="2654.5" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2569,-1324 2740,-1324 "/>
<text text-anchor="middle" x="2654.5" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2569,-1301 2740,-1301 "/>
<text text-anchor="middle" x="2654.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2569,-1278 2740,-1278 "/>
<text text-anchor="middle" x="2654.5" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2569,-1255 2740,-1255 "/>
<text text-anchor="middle" x="2654.5" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2569,-1232 2740,-1232 "/>
<text text-anchor="middle" x="2654.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2569,-1209 2740,-1209 "/>
<text text-anchor="middle" x="2654.5" y="-1193.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="2569,-1186 2740,-1186 "/>
<text text-anchor="middle" x="2654.5" y="-1170.8" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="2740,-1163 2740,-1393 "/>
<text text-anchor="middle" x="2750.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2501.4629,-1162.7239C2465.5416,-1105.5714 2416.6719,-1038.5747 2360.5,-990 2297.8103,-935.7891 2217.9537,-891.4573 2146.6967,-858.3546"/>
<polygon fill="#000000" stroke="#000000" points="2148.1503,-855.1708 2137.6029,-854.1689 2145.2235,-861.5295 2148.1503,-855.1708"/>
<text text-anchor="middle" x="2424" y="-960.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
</g>
</svg>
</div>
