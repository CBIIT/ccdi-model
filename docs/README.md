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
<svg width="3007pt" height="1735pt"
 viewBox="0.00 0.00 3007.06 1735.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1731)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1731 3003.0626,-1731 3003.0626,4 -4,4"/>
<!-- methylation_array_file -->
<g id="node1" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M2620.0626,-1324C2620.0626,-1324 2987.0626,-1324 2987.0626,-1324 2993.0626,-1324 2999.0626,-1330 2999.0626,-1336 2999.0626,-1336 2999.0626,-1542 2999.0626,-1542 2999.0626,-1548 2993.0626,-1554 2987.0626,-1554 2987.0626,-1554 2620.0626,-1554 2620.0626,-1554 2614.0626,-1554 2608.0626,-1548 2608.0626,-1542 2608.0626,-1542 2608.0626,-1336 2608.0626,-1336 2608.0626,-1330 2614.0626,-1324 2620.0626,-1324"/>
<text text-anchor="middle" x="2697.0626" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="2786.0626,-1324 2786.0626,-1554 "/>
<text text-anchor="middle" x="2796.5626" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2807.0626,-1324 2807.0626,-1554 "/>
<text text-anchor="middle" x="2892.5626" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2807.0626,-1531 2978.0626,-1531 "/>
<text text-anchor="middle" x="2892.5626" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2807.0626,-1508 2978.0626,-1508 "/>
<text text-anchor="middle" x="2892.5626" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2807.0626,-1485 2978.0626,-1485 "/>
<text text-anchor="middle" x="2892.5626" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2807.0626,-1462 2978.0626,-1462 "/>
<text text-anchor="middle" x="2892.5626" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2807.0626,-1439 2978.0626,-1439 "/>
<text text-anchor="middle" x="2892.5626" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2807.0626,-1416 2978.0626,-1416 "/>
<text text-anchor="middle" x="2892.5626" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2807.0626,-1393 2978.0626,-1393 "/>
<text text-anchor="middle" x="2892.5626" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2807.0626,-1370 2978.0626,-1370 "/>
<text text-anchor="middle" x="2892.5626" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="2807.0626,-1347 2978.0626,-1347 "/>
<text text-anchor="middle" x="2892.5626" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="2978.0626,-1324 2978.0626,-1554 "/>
<text text-anchor="middle" x="2988.5626" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node10" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1394.5626,-800.5C1394.5626,-800.5 1708.5626,-800.5 1708.5626,-800.5 1714.5626,-800.5 1720.5626,-806.5 1720.5626,-812.5 1720.5626,-812.5 1720.5626,-949.5 1720.5626,-949.5 1720.5626,-955.5 1714.5626,-961.5 1708.5626,-961.5 1708.5626,-961.5 1394.5626,-961.5 1394.5626,-961.5 1388.5626,-961.5 1382.5626,-955.5 1382.5626,-949.5 1382.5626,-949.5 1382.5626,-812.5 1382.5626,-812.5 1382.5626,-806.5 1388.5626,-800.5 1394.5626,-800.5"/>
<text text-anchor="middle" x="1416.5626" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1450.5626,-800.5 1450.5626,-961.5 "/>
<text text-anchor="middle" x="1461.0626" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1471.5626,-800.5 1471.5626,-961.5 "/>
<text text-anchor="middle" x="1585.5626" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="1471.5626,-938.5 1699.5626,-938.5 "/>
<text text-anchor="middle" x="1585.5626" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1471.5626,-915.5 1699.5626,-915.5 "/>
<text text-anchor="middle" x="1585.5626" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1471.5626,-892.5 1699.5626,-892.5 "/>
<text text-anchor="middle" x="1585.5626" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1471.5626,-869.5 1699.5626,-869.5 "/>
<text text-anchor="middle" x="1585.5626" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1471.5626,-846.5 1699.5626,-846.5 "/>
<text text-anchor="middle" x="1585.5626" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1471.5626,-823.5 1699.5626,-823.5 "/>
<text text-anchor="middle" x="1585.5626" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="1699.5626,-800.5 1699.5626,-961.5 "/>
<text text-anchor="middle" x="1710.0626" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2746.9115,-1323.7211C2711.9363,-1263.8666 2661.6539,-1194.3751 2598.5626,-1151 2458.2479,-1054.5339 1991.0004,-959.1972 1730.6553,-911.8345"/>
<polygon fill="#000000" stroke="#000000" points="1731.1803,-908.3727 1720.7161,-910.0313 1729.9307,-915.2603 1731.1803,-908.3727"/>
<text text-anchor="middle" x="2647.0626" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study_arm -->
<g id="node2" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M1051.0626,-317C1051.0626,-317 1348.0626,-317 1348.0626,-317 1354.0626,-317 1360.0626,-323 1360.0626,-329 1360.0626,-329 1360.0626,-374 1360.0626,-374 1360.0626,-380 1354.0626,-386 1348.0626,-386 1348.0626,-386 1051.0626,-386 1051.0626,-386 1045.0626,-386 1039.0626,-380 1039.0626,-374 1039.0626,-374 1039.0626,-329 1039.0626,-329 1039.0626,-323 1045.0626,-317 1051.0626,-317"/>
<text text-anchor="middle" x="1085.0626" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="1131.0626,-317 1131.0626,-386 "/>
<text text-anchor="middle" x="1141.5626" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1152.0626,-317 1152.0626,-386 "/>
<text text-anchor="middle" x="1245.5626" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="1152.0626,-363 1339.0626,-363 "/>
<text text-anchor="middle" x="1245.5626" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="1152.0626,-340 1339.0626,-340 "/>
<text text-anchor="middle" x="1245.5626" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="1339.0626,-317 1339.0626,-386 "/>
<text text-anchor="middle" x="1349.5626" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node8" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M1193.5626,-.5C1193.5626,-.5 1583.5626,-.5 1583.5626,-.5 1589.5626,-.5 1595.5626,-6.5 1595.5626,-12.5 1595.5626,-12.5 1595.5626,-195.5 1595.5626,-195.5 1595.5626,-201.5 1589.5626,-207.5 1583.5626,-207.5 1583.5626,-207.5 1193.5626,-207.5 1193.5626,-207.5 1187.5626,-207.5 1181.5626,-201.5 1181.5626,-195.5 1181.5626,-195.5 1181.5626,-12.5 1181.5626,-12.5 1181.5626,-6.5 1187.5626,-.5 1193.5626,-.5"/>
<text text-anchor="middle" x="1209.5626" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="1237.5626,-.5 1237.5626,-207.5 "/>
<text text-anchor="middle" x="1248.0626" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1258.5626,-.5 1258.5626,-207.5 "/>
<text text-anchor="middle" x="1416.5626" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="1258.5626,-184.5 1574.5626,-184.5 "/>
<text text-anchor="middle" x="1416.5626" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="1258.5626,-161.5 1574.5626,-161.5 "/>
<text text-anchor="middle" x="1416.5626" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="1258.5626,-138.5 1574.5626,-138.5 "/>
<text text-anchor="middle" x="1416.5626" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="1258.5626,-115.5 1574.5626,-115.5 "/>
<text text-anchor="middle" x="1416.5626" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="1258.5626,-92.5 1574.5626,-92.5 "/>
<text text-anchor="middle" x="1416.5626" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="1258.5626,-69.5 1574.5626,-69.5 "/>
<text text-anchor="middle" x="1416.5626" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="1258.5626,-46.5 1574.5626,-46.5 "/>
<text text-anchor="middle" x="1416.5626" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="1258.5626,-23.5 1574.5626,-23.5 "/>
<text text-anchor="middle" x="1416.5626" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="1574.5626,-.5 1574.5626,-207.5 "/>
<text text-anchor="middle" x="1585.0626" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge11" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1218.8103,-316.8369C1233.6986,-290.9966 1255.4448,-255.267 1277.5626,-226 1280.1362,-222.5946 1282.7863,-219.1722 1285.4955,-215.7462"/>
<polygon fill="#000000" stroke="#000000" points="1288.3827,-217.7407 1291.9156,-207.7523 1282.9249,-213.3574 1288.3827,-217.7407"/>
<text text-anchor="middle" x="1326.0626" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- sequencing_file -->
<g id="node3" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M886.0626,-1151.5C886.0626,-1151.5 1355.0626,-1151.5 1355.0626,-1151.5 1361.0626,-1151.5 1367.0626,-1157.5 1367.0626,-1163.5 1367.0626,-1163.5 1367.0626,-1714.5 1367.0626,-1714.5 1367.0626,-1720.5 1361.0626,-1726.5 1355.0626,-1726.5 1355.0626,-1726.5 886.0626,-1726.5 886.0626,-1726.5 880.0626,-1726.5 874.0626,-1720.5 874.0626,-1714.5 874.0626,-1714.5 874.0626,-1163.5 874.0626,-1163.5 874.0626,-1157.5 880.0626,-1151.5 886.0626,-1151.5"/>
<text text-anchor="middle" x="938.0626" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="1002.0626,-1151.5 1002.0626,-1726.5 "/>
<text text-anchor="middle" x="1012.5626" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1023.0626,-1151.5 1023.0626,-1726.5 "/>
<text text-anchor="middle" x="1184.5626" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="1023.0626,-1703.5 1346.0626,-1703.5 "/>
<text text-anchor="middle" x="1184.5626" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1023.0626,-1680.5 1346.0626,-1680.5 "/>
<text text-anchor="middle" x="1184.5626" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1023.0626,-1657.5 1346.0626,-1657.5 "/>
<text text-anchor="middle" x="1184.5626" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="1023.0626,-1634.5 1346.0626,-1634.5 "/>
<text text-anchor="middle" x="1184.5626" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="1023.0626,-1611.5 1346.0626,-1611.5 "/>
<text text-anchor="middle" x="1184.5626" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1023.0626,-1588.5 1346.0626,-1588.5 "/>
<text text-anchor="middle" x="1184.5626" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="1023.0626,-1565.5 1346.0626,-1565.5 "/>
<text text-anchor="middle" x="1184.5626" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1023.0626,-1542.5 1346.0626,-1542.5 "/>
<text text-anchor="middle" x="1184.5626" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1023.0626,-1519.5 1346.0626,-1519.5 "/>
<text text-anchor="middle" x="1184.5626" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1023.0626,-1496.5 1346.0626,-1496.5 "/>
<text text-anchor="middle" x="1184.5626" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1023.0626,-1473.5 1346.0626,-1473.5 "/>
<text text-anchor="middle" x="1184.5626" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1023.0626,-1450.5 1346.0626,-1450.5 "/>
<text text-anchor="middle" x="1184.5626" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1023.0626,-1427.5 1346.0626,-1427.5 "/>
<text text-anchor="middle" x="1184.5626" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="1023.0626,-1404.5 1346.0626,-1404.5 "/>
<text text-anchor="middle" x="1184.5626" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="1023.0626,-1381.5 1346.0626,-1381.5 "/>
<text text-anchor="middle" x="1184.5626" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="1023.0626,-1358.5 1346.0626,-1358.5 "/>
<text text-anchor="middle" x="1184.5626" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="1023.0626,-1335.5 1346.0626,-1335.5 "/>
<text text-anchor="middle" x="1184.5626" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="1023.0626,-1312.5 1346.0626,-1312.5 "/>
<text text-anchor="middle" x="1184.5626" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="1023.0626,-1289.5 1346.0626,-1289.5 "/>
<text text-anchor="middle" x="1184.5626" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1023.0626,-1266.5 1346.0626,-1266.5 "/>
<text text-anchor="middle" x="1184.5626" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="1023.0626,-1243.5 1346.0626,-1243.5 "/>
<text text-anchor="middle" x="1184.5626" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="1023.0626,-1220.5 1346.0626,-1220.5 "/>
<text text-anchor="middle" x="1184.5626" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="1023.0626,-1197.5 1346.0626,-1197.5 "/>
<text text-anchor="middle" x="1184.5626" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="1023.0626,-1174.5 1346.0626,-1174.5 "/>
<text text-anchor="middle" x="1184.5626" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="1346.0626,-1151.5 1346.0626,-1726.5 "/>
<text text-anchor="middle" x="1356.5626" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1367.3263,-1157.9911C1373.8734,-1149.6222 1380.2986,-1141.2802 1386.5626,-1133 1425.998,-1080.8713 1466.2598,-1019.5708 1497.1396,-970.4824"/>
<polygon fill="#000000" stroke="#000000" points="1500.2509,-972.1087 1502.5981,-961.7771 1494.3204,-968.39 1500.2509,-972.1087"/>
<text text-anchor="middle" x="1463.0626" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- imaging_file -->
<g id="node4" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M1397.5626,-1278C1397.5626,-1278 1731.5626,-1278 1731.5626,-1278 1737.5626,-1278 1743.5626,-1284 1743.5626,-1290 1743.5626,-1290 1743.5626,-1588 1743.5626,-1588 1743.5626,-1594 1737.5626,-1600 1731.5626,-1600 1731.5626,-1600 1397.5626,-1600 1397.5626,-1600 1391.5626,-1600 1385.5626,-1594 1385.5626,-1588 1385.5626,-1588 1385.5626,-1290 1385.5626,-1290 1385.5626,-1284 1391.5626,-1278 1397.5626,-1278"/>
<text text-anchor="middle" x="1437.5626" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="1489.5626,-1278 1489.5626,-1600 "/>
<text text-anchor="middle" x="1500.0626" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1510.5626,-1278 1510.5626,-1600 "/>
<text text-anchor="middle" x="1616.5626" y="-1584.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1510.5626,-1577 1722.5626,-1577 "/>
<text text-anchor="middle" x="1616.5626" y="-1561.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1510.5626,-1554 1722.5626,-1554 "/>
<text text-anchor="middle" x="1616.5626" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1510.5626,-1531 1722.5626,-1531 "/>
<text text-anchor="middle" x="1616.5626" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1510.5626,-1508 1722.5626,-1508 "/>
<text text-anchor="middle" x="1616.5626" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1510.5626,-1485 1722.5626,-1485 "/>
<text text-anchor="middle" x="1616.5626" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1510.5626,-1462 1722.5626,-1462 "/>
<text text-anchor="middle" x="1616.5626" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1510.5626,-1439 1722.5626,-1439 "/>
<text text-anchor="middle" x="1616.5626" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1510.5626,-1416 1722.5626,-1416 "/>
<text text-anchor="middle" x="1616.5626" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1510.5626,-1393 1722.5626,-1393 "/>
<text text-anchor="middle" x="1616.5626" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="1510.5626,-1370 1722.5626,-1370 "/>
<text text-anchor="middle" x="1616.5626" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="1510.5626,-1347 1722.5626,-1347 "/>
<text text-anchor="middle" x="1616.5626" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="1510.5626,-1324 1722.5626,-1324 "/>
<text text-anchor="middle" x="1616.5626" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1510.5626,-1301 1722.5626,-1301 "/>
<text text-anchor="middle" x="1616.5626" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="1722.5626,-1278 1722.5626,-1600 "/>
<text text-anchor="middle" x="1733.0626" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1560.8112,-1277.9777C1558.493,-1178.4707 1555.6029,-1054.4213 1553.6765,-971.732"/>
<polygon fill="#000000" stroke="#000000" points="1557.1726,-971.5217 1553.4405,-961.606 1550.1745,-971.6848 1557.1726,-971.5217"/>
<text text-anchor="middle" x="1612.0626" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- study_personnel -->
<g id="node5" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M1429.0626,-294C1429.0626,-294 1736.0626,-294 1736.0626,-294 1742.0626,-294 1748.0626,-300 1748.0626,-306 1748.0626,-306 1748.0626,-397 1748.0626,-397 1748.0626,-403 1742.0626,-409 1736.0626,-409 1736.0626,-409 1429.0626,-409 1429.0626,-409 1423.0626,-409 1417.0626,-403 1417.0626,-397 1417.0626,-397 1417.0626,-306 1417.0626,-306 1417.0626,-300 1423.0626,-294 1429.0626,-294"/>
<text text-anchor="middle" x="1484.0626" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="1551.0626,-294 1551.0626,-409 "/>
<text text-anchor="middle" x="1561.5626" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1572.0626,-294 1572.0626,-409 "/>
<text text-anchor="middle" x="1649.5626" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="1572.0626,-386 1727.0626,-386 "/>
<text text-anchor="middle" x="1649.5626" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="1572.0626,-363 1727.0626,-363 "/>
<text text-anchor="middle" x="1649.5626" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="1572.0626,-340 1727.0626,-340 "/>
<text text-anchor="middle" x="1649.5626" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="1572.0626,-317 1727.0626,-317 "/>
<text text-anchor="middle" x="1649.5626" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="1727.0626,-294 1727.0626,-409 "/>
<text text-anchor="middle" x="1737.5626" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge10" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1537.3231,-293.7846C1519.0822,-270.5133 1497.3876,-242.836 1476.2843,-215.9129"/>
<polygon fill="#000000" stroke="#000000" points="1478.9797,-213.6782 1470.056,-207.967 1473.4705,-217.9966 1478.9797,-213.6782"/>
<text text-anchor="middle" x="1561.0626" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- study_admin -->
<g id="node6" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M1778.5626,-259.5C1778.5626,-259.5 2104.5626,-259.5 2104.5626,-259.5 2110.5626,-259.5 2116.5626,-265.5 2116.5626,-271.5 2116.5626,-271.5 2116.5626,-431.5 2116.5626,-431.5 2116.5626,-437.5 2110.5626,-443.5 2104.5626,-443.5 2104.5626,-443.5 1778.5626,-443.5 1778.5626,-443.5 1772.5626,-443.5 1766.5626,-437.5 1766.5626,-431.5 1766.5626,-431.5 1766.5626,-271.5 1766.5626,-271.5 1766.5626,-265.5 1772.5626,-259.5 1778.5626,-259.5"/>
<text text-anchor="middle" x="1820.5626" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="1874.5626,-259.5 1874.5626,-443.5 "/>
<text text-anchor="middle" x="1885.0626" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1895.5626,-259.5 1895.5626,-443.5 "/>
<text text-anchor="middle" x="1995.5626" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="1895.5626,-420.5 2095.5626,-420.5 "/>
<text text-anchor="middle" x="1995.5626" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="1895.5626,-397.5 2095.5626,-397.5 "/>
<text text-anchor="middle" x="1995.5626" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="1895.5626,-374.5 2095.5626,-374.5 "/>
<text text-anchor="middle" x="1995.5626" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="1895.5626,-351.5 2095.5626,-351.5 "/>
<text text-anchor="middle" x="1995.5626" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="1895.5626,-328.5 2095.5626,-328.5 "/>
<text text-anchor="middle" x="1995.5626" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="1895.5626,-305.5 2095.5626,-305.5 "/>
<text text-anchor="middle" x="1995.5626" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="1895.5626,-282.5 2095.5626,-282.5 "/>
<text text-anchor="middle" x="1995.5626" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="2095.5626,-259.5 2095.5626,-443.5 "/>
<text text-anchor="middle" x="2106.0626" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge18" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1766.4247,-263.5696C1763.1146,-262.0253 1759.8249,-260.5007 1756.5626,-259 1707.9445,-236.6352 1655.1856,-213.6644 1605.2039,-192.4867"/>
<polygon fill="#000000" stroke="#000000" points="1606.4787,-189.2257 1595.9051,-188.5537 1603.7518,-195.6728 1606.4787,-189.2257"/>
<text text-anchor="middle" x="1764.0626" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- pdx -->
<g id="node7" class="node">
<title>pdx</title>
<path fill="none" stroke="#000000" d="M1774.0626,-1335.5C1774.0626,-1335.5 2103.0626,-1335.5 2103.0626,-1335.5 2109.0626,-1335.5 2115.0626,-1341.5 2115.0626,-1347.5 2115.0626,-1347.5 2115.0626,-1530.5 2115.0626,-1530.5 2115.0626,-1536.5 2109.0626,-1542.5 2103.0626,-1542.5 2103.0626,-1542.5 1774.0626,-1542.5 1774.0626,-1542.5 1768.0626,-1542.5 1762.0626,-1536.5 1762.0626,-1530.5 1762.0626,-1530.5 1762.0626,-1347.5 1762.0626,-1347.5 1762.0626,-1341.5 1768.0626,-1335.5 1774.0626,-1335.5"/>
<text text-anchor="middle" x="1783.5626" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
<polyline fill="none" stroke="#000000" points="1805.0626,-1335.5 1805.0626,-1542.5 "/>
<text text-anchor="middle" x="1815.5626" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1826.0626,-1335.5 1826.0626,-1542.5 "/>
<text text-anchor="middle" x="1960.0626" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">injection_type_and_site</text>
<polyline fill="none" stroke="#000000" points="1826.0626,-1519.5 2094.0626,-1519.5 "/>
<text text-anchor="middle" x="1960.0626" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_id</text>
<polyline fill="none" stroke="#000000" points="1826.0626,-1496.5 2094.0626,-1496.5 "/>
<text text-anchor="middle" x="1960.0626" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_type</text>
<polyline fill="none" stroke="#000000" points="1826.0626,-1473.5 2094.0626,-1473.5 "/>
<text text-anchor="middle" x="1960.0626" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">mouse_strain</text>
<polyline fill="none" stroke="#000000" points="1826.0626,-1450.5 2094.0626,-1450.5 "/>
<text text-anchor="middle" x="1960.0626" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">strain_immune_system_humanized</text>
<polyline fill="none" stroke="#000000" points="1826.0626,-1427.5 2094.0626,-1427.5 "/>
<text text-anchor="middle" x="1960.0626" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_characterization_method</text>
<polyline fill="none" stroke="#000000" points="1826.0626,-1404.5 2094.0626,-1404.5 "/>
<text text-anchor="middle" x="1960.0626" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_not_mus_or_ebv_origin</text>
<polyline fill="none" stroke="#000000" points="1826.0626,-1381.5 2094.0626,-1381.5 "/>
<text text-anchor="middle" x="1960.0626" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_preparation</text>
<polyline fill="none" stroke="#000000" points="1826.0626,-1358.5 2094.0626,-1358.5 "/>
<text text-anchor="middle" x="1960.0626" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_humanization</text>
<polyline fill="none" stroke="#000000" points="2094.0626,-1335.5 2094.0626,-1542.5 "/>
<text text-anchor="middle" x="2104.5626" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1873.9156,-1335.2691C1838.8724,-1279.98 1794.3038,-1211.1457 1752.5626,-1151 1709.9461,-1089.5929 1659.738,-1022.1462 1620.1631,-970.0247"/>
<polygon fill="#000000" stroke="#000000" points="1622.7442,-967.6365 1613.9057,-961.7943 1617.1718,-971.8732 1622.7442,-967.6365"/>
<text text-anchor="middle" x="1761.5626" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- clinical_measure_file -->
<g id="node9" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M51.5626,-754.5C51.5626,-754.5 403.5626,-754.5 403.5626,-754.5 409.5626,-754.5 415.5626,-760.5 415.5626,-766.5 415.5626,-766.5 415.5626,-995.5 415.5626,-995.5 415.5626,-1001.5 409.5626,-1007.5 403.5626,-1007.5 403.5626,-1007.5 51.5626,-1007.5 51.5626,-1007.5 45.5626,-1007.5 39.5626,-1001.5 39.5626,-995.5 39.5626,-995.5 39.5626,-766.5 39.5626,-766.5 39.5626,-760.5 45.5626,-754.5 51.5626,-754.5"/>
<text text-anchor="middle" x="123.0626" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="206.5626,-754.5 206.5626,-1007.5 "/>
<text text-anchor="middle" x="217.0626" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="227.5626,-754.5 227.5626,-1007.5 "/>
<text text-anchor="middle" x="311.0626" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="227.5626,-984.5 394.5626,-984.5 "/>
<text text-anchor="middle" x="311.0626" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="227.5626,-961.5 394.5626,-961.5 "/>
<text text-anchor="middle" x="311.0626" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="227.5626,-938.5 394.5626,-938.5 "/>
<text text-anchor="middle" x="311.0626" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="227.5626,-915.5 394.5626,-915.5 "/>
<text text-anchor="middle" x="311.0626" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="227.5626,-892.5 394.5626,-892.5 "/>
<text text-anchor="middle" x="311.0626" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="227.5626,-869.5 394.5626,-869.5 "/>
<text text-anchor="middle" x="311.0626" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="227.5626,-846.5 394.5626,-846.5 "/>
<text text-anchor="middle" x="311.0626" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="227.5626,-823.5 394.5626,-823.5 "/>
<text text-anchor="middle" x="311.0626" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="227.5626,-800.5 394.5626,-800.5 "/>
<text text-anchor="middle" x="311.0626" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="227.5626,-777.5 394.5626,-777.5 "/>
<text text-anchor="middle" x="311.0626" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="394.5626,-754.5 394.5626,-1007.5 "/>
<text text-anchor="middle" x="405.0626" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge15" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M323.3857,-754.4561C448.0188,-600.3879 681.2927,-345.9396 945.5626,-226 1016.6471,-193.7381 1098.1168,-168.3144 1171.6456,-149.215"/>
<polygon fill="#000000" stroke="#000000" points="1172.6867,-152.5612 1181.4998,-146.6806 1170.9431,-145.7818 1172.6867,-152.5612"/>
<text text-anchor="middle" x="680.5626" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- participant -->
<g id="node11" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M880.5626,-495.5C880.5626,-495.5 1184.5626,-495.5 1184.5626,-495.5 1190.5626,-495.5 1196.5626,-501.5 1196.5626,-507.5 1196.5626,-507.5 1196.5626,-598.5 1196.5626,-598.5 1196.5626,-604.5 1190.5626,-610.5 1184.5626,-610.5 1184.5626,-610.5 880.5626,-610.5 880.5626,-610.5 874.5626,-610.5 868.5626,-604.5 868.5626,-598.5 868.5626,-598.5 868.5626,-507.5 868.5626,-507.5 868.5626,-501.5 874.5626,-495.5 880.5626,-495.5"/>
<text text-anchor="middle" x="916.5626" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="964.5626,-495.5 964.5626,-610.5 "/>
<text text-anchor="middle" x="975.0626" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="985.5626,-495.5 985.5626,-610.5 "/>
<text text-anchor="middle" x="1080.5626" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="985.5626,-587.5 1175.5626,-587.5 "/>
<text text-anchor="middle" x="1080.5626" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="985.5626,-564.5 1175.5626,-564.5 "/>
<text text-anchor="middle" x="1080.5626" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="985.5626,-541.5 1175.5626,-541.5 "/>
<text text-anchor="middle" x="1080.5626" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="985.5626,-518.5 1175.5626,-518.5 "/>
<text text-anchor="middle" x="1080.5626" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1175.5626,-495.5 1175.5626,-610.5 "/>
<text text-anchor="middle" x="1186.0626" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M318.1619,-754.2959C348.4352,-719.8306 384.7258,-685.5593 424.5626,-662 496.3683,-619.5344 705.4651,-588.4255 858.4535,-570.5543"/>
<polygon fill="#000000" stroke="#000000" points="858.9167,-574.0242 868.4474,-569.3963 858.1109,-567.0707 858.9167,-574.0242"/>
<text text-anchor="middle" x="636.0626" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge16" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1517.7869,-800.1393C1483.3773,-713.6806 1431.7412,-571.7381 1407.5626,-444 1393.444,-369.4097 1388.7087,-284.1045 1387.4956,-217.6003"/>
<polygon fill="#000000" stroke="#000000" points="1390.9939,-217.4543 1387.3359,-207.511 1383.9947,-217.5652 1390.9939,-217.4543"/>
<text text-anchor="middle" x="1451.0626" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1496.5843,-800.4162C1461.3484,-754.1653 1411.9282,-698.2576 1356.5626,-662 1335.0457,-647.9091 1324.7548,-655.1201 1301.5626,-644 1290.5582,-638.7236 1289.6106,-634.1846 1278.5626,-629 1255.688,-618.2654 1230.9208,-608.5658 1206.2121,-599.9676"/>
<polygon fill="#000000" stroke="#000000" points="1207.3438,-596.6556 1196.7492,-596.7263 1205.0755,-603.2779 1207.3438,-596.6556"/>
<text text-anchor="middle" x="1338.0626" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge20" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1080.4181,-495.2582C1107.1125,-463.0491 1139.7903,-423.6205 1164.167,-394.2079"/>
<polygon fill="#000000" stroke="#000000" points="1167.1241,-396.1248 1170.8105,-386.1919 1161.7345,-391.6579 1167.1241,-396.1248"/>
<text text-anchor="middle" x="1157.0626" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge19" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M962.3787,-495.3661C948.6044,-480.2308 936.0995,-462.8172 928.5626,-444 897.9911,-367.6726 880.5952,-325.7803 928.5626,-259 959.0154,-216.6037 1067.7154,-178.9428 1171.8012,-151.3624"/>
<polygon fill="#000000" stroke="#000000" points="1172.7491,-154.7322 1181.5335,-148.809 1170.9726,-147.9614 1172.7491,-154.7322"/>
<text text-anchor="middle" x="979.0626" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- synonym -->
<g id="node12" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M543.0626,-1416C543.0626,-1416 844.0626,-1416 844.0626,-1416 850.0626,-1416 856.0626,-1422 856.0626,-1428 856.0626,-1428 856.0626,-1450 856.0626,-1450 856.0626,-1456 850.0626,-1462 844.0626,-1462 844.0626,-1462 543.0626,-1462 543.0626,-1462 537.0626,-1462 531.0626,-1456 531.0626,-1450 531.0626,-1450 531.0626,-1428 531.0626,-1428 531.0626,-1422 537.0626,-1416 543.0626,-1416"/>
<text text-anchor="middle" x="571.0626" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="611.0626,-1416 611.0626,-1462 "/>
<text text-anchor="middle" x="621.5626" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="632.0626,-1416 632.0626,-1462 "/>
<text text-anchor="middle" x="733.5626" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="632.0626,-1439 835.0626,-1439 "/>
<text text-anchor="middle" x="733.5626" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="835.0626,-1416 835.0626,-1462 "/>
<text text-anchor="middle" x="845.5626" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge14" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M578.3137,-1415.9952C424.8388,-1378.7169 157.954,-1289.3027 30.5626,-1100 -23.9831,-1018.9454 11.5626,-978.699 11.5626,-881 11.5626,-881 11.5626,-881 11.5626,-351.5 11.5626,-235.1459 783.0096,-154.3128 1171.0627,-121.0124"/>
<polygon fill="#000000" stroke="#000000" points="1171.6285,-124.4769 1181.294,-120.1378 1171.0322,-117.5023 1171.6285,-124.4769"/>
<text text-anchor="middle" x="54.0626" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M699.2627,-1415.7183C714.6225,-1358.6274 762.7695,-1211.9096 864.5626,-1151 904.073,-1127.3583 1235.4041,-1149.0418 1278.5626,-1133 1288.6474,-1129.2515 1288.0305,-1122.9892 1297.5626,-1118 1321.852,-1105.2866 1333.4773,-1114.7875 1356.5626,-1100 1409.2356,-1066.2598 1456.2682,-1014.4568 1490.9404,-969.7029"/>
<polygon fill="#000000" stroke="#000000" points="1493.7498,-971.7909 1497.0506,-961.7234 1488.192,-967.5352 1493.7498,-971.7909"/>
<text text-anchor="middle" x="1340.0626" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M699.7397,-1415.874C716.0404,-1359.7846 765.8997,-1216.3341 864.5626,-1151 1005.1702,-1057.8904 1129.6181,-1227.0087 1240.5626,-1100 1304.5956,-1026.6954 1290.943,-745.2802 1240.5626,-662 1229.8177,-644.2384 1215.1185,-629.2302 1198.4631,-616.5828"/>
<polygon fill="#000000" stroke="#000000" points="1200.2924,-613.5864 1190.1384,-610.562 1196.1902,-619.2584 1200.2924,-613.5864"/>
<text text-anchor="middle" x="1327.0626" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- therapeutic_procedure -->
<g id="node13" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M446.0626,-823.5C446.0626,-823.5 803.0626,-823.5 803.0626,-823.5 809.0626,-823.5 815.0626,-829.5 815.0626,-835.5 815.0626,-835.5 815.0626,-926.5 815.0626,-926.5 815.0626,-932.5 809.0626,-938.5 803.0626,-938.5 803.0626,-938.5 446.0626,-938.5 446.0626,-938.5 440.0626,-938.5 434.0626,-932.5 434.0626,-926.5 434.0626,-926.5 434.0626,-835.5 434.0626,-835.5 434.0626,-829.5 440.0626,-823.5 446.0626,-823.5"/>
<text text-anchor="middle" x="524.5626" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="615.0626,-823.5 615.0626,-938.5 "/>
<text text-anchor="middle" x="625.5626" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="636.0626,-823.5 636.0626,-938.5 "/>
<text text-anchor="middle" x="715.0626" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="636.0626,-915.5 794.0626,-915.5 "/>
<text text-anchor="middle" x="715.0626" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="636.0626,-892.5 794.0626,-892.5 "/>
<text text-anchor="middle" x="715.0626" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="636.0626,-869.5 794.0626,-869.5 "/>
<text text-anchor="middle" x="715.0626" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="636.0626,-846.5 794.0626,-846.5 "/>
<text text-anchor="middle" x="715.0626" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="794.0626,-823.5 794.0626,-938.5 "/>
<text text-anchor="middle" x="804.5626" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M662.1053,-823.3962C701.2848,-767.1879 767.4167,-682.5407 842.5626,-629 849.0728,-624.3616 855.9063,-619.9514 862.9561,-615.7652"/>
<polygon fill="#000000" stroke="#000000" points="865.06,-618.5934 871.9933,-610.5821 861.5774,-612.5211 865.06,-618.5934"/>
<text text-anchor="middle" x="935.5626" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- study_funding -->
<g id="node14" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M2147.0626,-317C2147.0626,-317 2526.0626,-317 2526.0626,-317 2532.0626,-317 2538.0626,-323 2538.0626,-329 2538.0626,-329 2538.0626,-374 2538.0626,-374 2538.0626,-380 2532.0626,-386 2526.0626,-386 2526.0626,-386 2147.0626,-386 2147.0626,-386 2141.0626,-386 2135.0626,-380 2135.0626,-374 2135.0626,-374 2135.0626,-329 2135.0626,-329 2135.0626,-323 2141.0626,-317 2147.0626,-317"/>
<text text-anchor="middle" x="2194.5626" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="2254.0626,-317 2254.0626,-386 "/>
<text text-anchor="middle" x="2264.5626" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2275.0626,-317 2275.0626,-386 "/>
<text text-anchor="middle" x="2396.0626" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="2275.0626,-363 2517.0626,-363 "/>
<text text-anchor="middle" x="2396.0626" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="2275.0626,-340 2517.0626,-340 "/>
<text text-anchor="middle" x="2396.0626" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="2517.0626,-317 2517.0626,-386 "/>
<text text-anchor="middle" x="2527.5626" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2267.6272,-316.9717C2227.0654,-297.7539 2174.3154,-274.6289 2125.5626,-259 1954.2522,-204.0823 1754.1965,-163.4232 1605.7787,-137.5594"/>
<polygon fill="#000000" stroke="#000000" points="1606.0818,-134.0598 1595.6309,-135.8 1604.886,-140.9569 1606.0818,-134.0598"/>
<text text-anchor="middle" x="2109.5626" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- publication -->
<g id="node15" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M2568.5626,-333.5C2568.5626,-333.5 2778.5626,-333.5 2778.5626,-333.5 2784.5626,-333.5 2790.5626,-339.5 2790.5626,-345.5 2790.5626,-345.5 2790.5626,-357.5 2790.5626,-357.5 2790.5626,-363.5 2784.5626,-369.5 2778.5626,-369.5 2778.5626,-369.5 2568.5626,-369.5 2568.5626,-369.5 2562.5626,-369.5 2556.5626,-363.5 2556.5626,-357.5 2556.5626,-357.5 2556.5626,-345.5 2556.5626,-345.5 2556.5626,-339.5 2562.5626,-333.5 2568.5626,-333.5"/>
<text text-anchor="middle" x="2605.0626" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="2653.5626,-333.5 2653.5626,-369.5 "/>
<text text-anchor="middle" x="2664.0626" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2674.5626,-333.5 2674.5626,-369.5 "/>
<text text-anchor="middle" x="2722.0626" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="2769.5626,-333.5 2769.5626,-369.5 "/>
<text text-anchor="middle" x="2780.0626" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge3" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2655.3493,-333.4159C2632.3629,-311.7907 2590.6027,-276.346 2547.5626,-259 2381.3084,-191.9964 1892.9151,-143.6768 1605.9297,-120.1477"/>
<polygon fill="#000000" stroke="#000000" points="1606.0582,-116.6466 1595.8066,-119.3211 1605.4885,-123.6234 1606.0582,-116.6466"/>
<text text-anchor="middle" x="2527.5626" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- sample_diagnosis -->
<g id="node16" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M2145.0626,-1220.5C2145.0626,-1220.5 2578.0626,-1220.5 2578.0626,-1220.5 2584.0626,-1220.5 2590.0626,-1226.5 2590.0626,-1232.5 2590.0626,-1232.5 2590.0626,-1645.5 2590.0626,-1645.5 2590.0626,-1651.5 2584.0626,-1657.5 2578.0626,-1657.5 2578.0626,-1657.5 2145.0626,-1657.5 2145.0626,-1657.5 2139.0626,-1657.5 2133.0626,-1651.5 2133.0626,-1645.5 2133.0626,-1645.5 2133.0626,-1232.5 2133.0626,-1232.5 2133.0626,-1226.5 2139.0626,-1220.5 2145.0626,-1220.5"/>
<text text-anchor="middle" x="2204.5626" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2276.0626,-1220.5 2276.0626,-1657.5 "/>
<text text-anchor="middle" x="2286.5626" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2297.0626,-1220.5 2297.0626,-1657.5 "/>
<text text-anchor="middle" x="2433.0626" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2297.0626,-1634.5 2569.0626,-1634.5 "/>
<text text-anchor="middle" x="2433.0626" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="2297.0626,-1611.5 2569.0626,-1611.5 "/>
<text text-anchor="middle" x="2433.0626" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2297.0626,-1588.5 2569.0626,-1588.5 "/>
<text text-anchor="middle" x="2433.0626" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="2297.0626,-1565.5 2569.0626,-1565.5 "/>
<text text-anchor="middle" x="2433.0626" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="2297.0626,-1542.5 2569.0626,-1542.5 "/>
<text text-anchor="middle" x="2433.0626" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="2297.0626,-1519.5 2569.0626,-1519.5 "/>
<text text-anchor="middle" x="2433.0626" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="2297.0626,-1496.5 2569.0626,-1496.5 "/>
<text text-anchor="middle" x="2433.0626" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2297.0626,-1473.5 2569.0626,-1473.5 "/>
<text text-anchor="middle" x="2433.0626" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="2297.0626,-1450.5 2569.0626,-1450.5 "/>
<text text-anchor="middle" x="2433.0626" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="2297.0626,-1427.5 2569.0626,-1427.5 "/>
<text text-anchor="middle" x="2433.0626" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="2297.0626,-1404.5 2569.0626,-1404.5 "/>
<text text-anchor="middle" x="2433.0626" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="2297.0626,-1381.5 2569.0626,-1381.5 "/>
<text text-anchor="middle" x="2433.0626" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="2297.0626,-1358.5 2569.0626,-1358.5 "/>
<text text-anchor="middle" x="2433.0626" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="2297.0626,-1335.5 2569.0626,-1335.5 "/>
<text text-anchor="middle" x="2433.0626" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="2297.0626,-1312.5 2569.0626,-1312.5 "/>
<text text-anchor="middle" x="2433.0626" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="2297.0626,-1289.5 2569.0626,-1289.5 "/>
<text text-anchor="middle" x="2433.0626" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="2297.0626,-1266.5 2569.0626,-1266.5 "/>
<text text-anchor="middle" x="2433.0626" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="2297.0626,-1243.5 2569.0626,-1243.5 "/>
<text text-anchor="middle" x="2433.0626" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="2569.0626,-1220.5 2569.0626,-1657.5 "/>
<text text-anchor="middle" x="2579.5626" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2198.7333,-1220.1496C2175.0898,-1195.1702 2149.8119,-1171.3973 2123.5626,-1151 2004.7347,-1058.6636 1849.2166,-987.8143 1730.3401,-941.907"/>
<polygon fill="#000000" stroke="#000000" points="1731.3544,-938.5474 1720.7642,-938.2323 1728.8464,-945.0828 1731.3544,-938.5474"/>
<text text-anchor="middle" x="2170.5626" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
<!-- diagnosis -->
<g id="node17" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M845.5626,-662.5C845.5626,-662.5 1219.5626,-662.5 1219.5626,-662.5 1225.5626,-662.5 1231.5626,-668.5 1231.5626,-674.5 1231.5626,-674.5 1231.5626,-1087.5 1231.5626,-1087.5 1231.5626,-1093.5 1225.5626,-1099.5 1219.5626,-1099.5 1219.5626,-1099.5 845.5626,-1099.5 845.5626,-1099.5 839.5626,-1099.5 833.5626,-1093.5 833.5626,-1087.5 833.5626,-1087.5 833.5626,-674.5 833.5626,-674.5 833.5626,-668.5 839.5626,-662.5 845.5626,-662.5"/>
<text text-anchor="middle" x="875.5626" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="917.5626,-662.5 917.5626,-1099.5 "/>
<text text-anchor="middle" x="928.0626" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="938.5626,-662.5 938.5626,-1099.5 "/>
<text text-anchor="middle" x="1074.5626" y="-1084.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="938.5626,-1076.5 1210.5626,-1076.5 "/>
<text text-anchor="middle" x="1074.5626" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="938.5626,-1053.5 1210.5626,-1053.5 "/>
<text text-anchor="middle" x="1074.5626" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="938.5626,-1030.5 1210.5626,-1030.5 "/>
<text text-anchor="middle" x="1074.5626" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="938.5626,-1007.5 1210.5626,-1007.5 "/>
<text text-anchor="middle" x="1074.5626" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="938.5626,-984.5 1210.5626,-984.5 "/>
<text text-anchor="middle" x="1074.5626" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="938.5626,-961.5 1210.5626,-961.5 "/>
<text text-anchor="middle" x="1074.5626" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="938.5626,-938.5 1210.5626,-938.5 "/>
<text text-anchor="middle" x="1074.5626" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="938.5626,-915.5 1210.5626,-915.5 "/>
<text text-anchor="middle" x="1074.5626" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="938.5626,-892.5 1210.5626,-892.5 "/>
<text text-anchor="middle" x="1074.5626" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="938.5626,-869.5 1210.5626,-869.5 "/>
<text text-anchor="middle" x="1074.5626" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="938.5626,-846.5 1210.5626,-846.5 "/>
<text text-anchor="middle" x="1074.5626" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="938.5626,-823.5 1210.5626,-823.5 "/>
<text text-anchor="middle" x="1074.5626" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="938.5626,-800.5 1210.5626,-800.5 "/>
<text text-anchor="middle" x="1074.5626" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="938.5626,-777.5 1210.5626,-777.5 "/>
<text text-anchor="middle" x="1074.5626" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="938.5626,-754.5 1210.5626,-754.5 "/>
<text text-anchor="middle" x="1074.5626" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="938.5626,-731.5 1210.5626,-731.5 "/>
<text text-anchor="middle" x="1074.5626" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="938.5626,-708.5 1210.5626,-708.5 "/>
<text text-anchor="middle" x="1074.5626" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="938.5626,-685.5 1210.5626,-685.5 "/>
<text text-anchor="middle" x="1074.5626" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1210.5626,-662.5 1210.5626,-1099.5 "/>
<text text-anchor="middle" x="1221.0626" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1032.5626,-662.2193C1032.5626,-647.476 1032.5626,-633.4001 1032.5626,-620.5497"/>
<polygon fill="#000000" stroke="#000000" points="1036.0627,-620.5173 1032.5626,-610.5174 1029.0627,-620.5174 1036.0627,-620.5173"/>
<text text-anchor="middle" x="1077.0626" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
</g>
</svg>
</div>
