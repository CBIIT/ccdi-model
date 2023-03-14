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
<svg width="3389pt" height="1735pt"
 viewBox="0.00 0.00 3389.18 1735.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1731)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1731 3385.1798,-1731 3385.1798,4 -4,4"/>
<!-- sequencing_file -->
<g id="node1" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M2900.1798,-1151.5C2900.1798,-1151.5 3369.1798,-1151.5 3369.1798,-1151.5 3375.1798,-1151.5 3381.1798,-1157.5 3381.1798,-1163.5 3381.1798,-1163.5 3381.1798,-1714.5 3381.1798,-1714.5 3381.1798,-1720.5 3375.1798,-1726.5 3369.1798,-1726.5 3369.1798,-1726.5 2900.1798,-1726.5 2900.1798,-1726.5 2894.1798,-1726.5 2888.1798,-1720.5 2888.1798,-1714.5 2888.1798,-1714.5 2888.1798,-1163.5 2888.1798,-1163.5 2888.1798,-1157.5 2894.1798,-1151.5 2900.1798,-1151.5"/>
<text text-anchor="middle" x="2952.1798" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="3016.1798,-1151.5 3016.1798,-1726.5 "/>
<text text-anchor="middle" x="3026.6798" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3037.1798,-1151.5 3037.1798,-1726.5 "/>
<text text-anchor="middle" x="3198.6798" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="3037.1798,-1703.5 3360.1798,-1703.5 "/>
<text text-anchor="middle" x="3198.6798" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="3037.1798,-1680.5 3360.1798,-1680.5 "/>
<text text-anchor="middle" x="3198.6798" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="3037.1798,-1657.5 3360.1798,-1657.5 "/>
<text text-anchor="middle" x="3198.6798" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="3037.1798,-1634.5 3360.1798,-1634.5 "/>
<text text-anchor="middle" x="3198.6798" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="3037.1798,-1611.5 3360.1798,-1611.5 "/>
<text text-anchor="middle" x="3198.6798" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="3037.1798,-1588.5 3360.1798,-1588.5 "/>
<text text-anchor="middle" x="3198.6798" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="3037.1798,-1565.5 3360.1798,-1565.5 "/>
<text text-anchor="middle" x="3198.6798" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="3037.1798,-1542.5 3360.1798,-1542.5 "/>
<text text-anchor="middle" x="3198.6798" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="3037.1798,-1519.5 3360.1798,-1519.5 "/>
<text text-anchor="middle" x="3198.6798" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="3037.1798,-1496.5 3360.1798,-1496.5 "/>
<text text-anchor="middle" x="3198.6798" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="3037.1798,-1473.5 3360.1798,-1473.5 "/>
<text text-anchor="middle" x="3198.6798" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="3037.1798,-1450.5 3360.1798,-1450.5 "/>
<text text-anchor="middle" x="3198.6798" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="3037.1798,-1427.5 3360.1798,-1427.5 "/>
<text text-anchor="middle" x="3198.6798" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="3037.1798,-1404.5 3360.1798,-1404.5 "/>
<text text-anchor="middle" x="3198.6798" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="3037.1798,-1381.5 3360.1798,-1381.5 "/>
<text text-anchor="middle" x="3198.6798" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="3037.1798,-1358.5 3360.1798,-1358.5 "/>
<text text-anchor="middle" x="3198.6798" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="3037.1798,-1335.5 3360.1798,-1335.5 "/>
<text text-anchor="middle" x="3198.6798" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="3037.1798,-1312.5 3360.1798,-1312.5 "/>
<text text-anchor="middle" x="3198.6798" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="3037.1798,-1289.5 3360.1798,-1289.5 "/>
<text text-anchor="middle" x="3198.6798" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="3037.1798,-1266.5 3360.1798,-1266.5 "/>
<text text-anchor="middle" x="3198.6798" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="3037.1798,-1243.5 3360.1798,-1243.5 "/>
<text text-anchor="middle" x="3198.6798" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="3037.1798,-1220.5 3360.1798,-1220.5 "/>
<text text-anchor="middle" x="3198.6798" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="3037.1798,-1197.5 3360.1798,-1197.5 "/>
<text text-anchor="middle" x="3198.6798" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="3037.1798,-1174.5 3360.1798,-1174.5 "/>
<text text-anchor="middle" x="3198.6798" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="3360.1798,-1151.5 3360.1798,-1726.5 "/>
<text text-anchor="middle" x="3370.6798" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node3" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1971.6798,-823.5C1971.6798,-823.5 2285.6798,-823.5 2285.6798,-823.5 2291.6798,-823.5 2297.6798,-829.5 2297.6798,-835.5 2297.6798,-835.5 2297.6798,-972.5 2297.6798,-972.5 2297.6798,-978.5 2291.6798,-984.5 2285.6798,-984.5 2285.6798,-984.5 1971.6798,-984.5 1971.6798,-984.5 1965.6798,-984.5 1959.6798,-978.5 1959.6798,-972.5 1959.6798,-972.5 1959.6798,-835.5 1959.6798,-835.5 1959.6798,-829.5 1965.6798,-823.5 1971.6798,-823.5"/>
<text text-anchor="middle" x="1993.6798" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="2027.6798,-823.5 2027.6798,-984.5 "/>
<text text-anchor="middle" x="2038.1798" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2048.6798,-823.5 2048.6798,-984.5 "/>
<text text-anchor="middle" x="2162.6798" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="2048.6798,-961.5 2276.6798,-961.5 "/>
<text text-anchor="middle" x="2162.6798" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="2048.6798,-938.5 2276.6798,-938.5 "/>
<text text-anchor="middle" x="2162.6798" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="2048.6798,-915.5 2276.6798,-915.5 "/>
<text text-anchor="middle" x="2162.6798" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="2048.6798,-892.5 2276.6798,-892.5 "/>
<text text-anchor="middle" x="2162.6798" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="2048.6798,-869.5 2276.6798,-869.5 "/>
<text text-anchor="middle" x="2162.6798" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="2048.6798,-846.5 2276.6798,-846.5 "/>
<text text-anchor="middle" x="2162.6798" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="2276.6798,-823.5 2276.6798,-984.5 "/>
<text text-anchor="middle" x="2287.1798" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2888.0127,-1156.6182C2885.2472,-1154.7088 2882.4693,-1152.8353 2879.6798,-1151 2703.3525,-1034.9905 2467.8713,-969.2269 2307.9311,-935.2049"/>
<polygon fill="#000000" stroke="#000000" points="2308.4924,-931.7464 2297.9856,-933.1095 2307.0492,-938.596 2308.4924,-931.7464"/>
<text text-anchor="middle" x="2910.1798" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- imaging_file -->
<g id="node2" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M1268.6798,-1278C1268.6798,-1278 1602.6798,-1278 1602.6798,-1278 1608.6798,-1278 1614.6798,-1284 1614.6798,-1290 1614.6798,-1290 1614.6798,-1588 1614.6798,-1588 1614.6798,-1594 1608.6798,-1600 1602.6798,-1600 1602.6798,-1600 1268.6798,-1600 1268.6798,-1600 1262.6798,-1600 1256.6798,-1594 1256.6798,-1588 1256.6798,-1588 1256.6798,-1290 1256.6798,-1290 1256.6798,-1284 1262.6798,-1278 1268.6798,-1278"/>
<text text-anchor="middle" x="1308.6798" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="1360.6798,-1278 1360.6798,-1600 "/>
<text text-anchor="middle" x="1371.1798" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1381.6798,-1278 1381.6798,-1600 "/>
<text text-anchor="middle" x="1487.6798" y="-1584.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1381.6798,-1577 1593.6798,-1577 "/>
<text text-anchor="middle" x="1487.6798" y="-1561.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1381.6798,-1554 1593.6798,-1554 "/>
<text text-anchor="middle" x="1487.6798" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1381.6798,-1531 1593.6798,-1531 "/>
<text text-anchor="middle" x="1487.6798" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1381.6798,-1508 1593.6798,-1508 "/>
<text text-anchor="middle" x="1487.6798" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1381.6798,-1485 1593.6798,-1485 "/>
<text text-anchor="middle" x="1487.6798" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1381.6798,-1462 1593.6798,-1462 "/>
<text text-anchor="middle" x="1487.6798" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1381.6798,-1439 1593.6798,-1439 "/>
<text text-anchor="middle" x="1487.6798" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1381.6798,-1416 1593.6798,-1416 "/>
<text text-anchor="middle" x="1487.6798" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1381.6798,-1393 1593.6798,-1393 "/>
<text text-anchor="middle" x="1487.6798" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="1381.6798,-1370 1593.6798,-1370 "/>
<text text-anchor="middle" x="1487.6798" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="1381.6798,-1347 1593.6798,-1347 "/>
<text text-anchor="middle" x="1487.6798" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="1381.6798,-1324 1593.6798,-1324 "/>
<text text-anchor="middle" x="1487.6798" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1381.6798,-1301 1593.6798,-1301 "/>
<text text-anchor="middle" x="1487.6798" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="1593.6798,-1278 1593.6798,-1600 "/>
<text text-anchor="middle" x="1604.1798" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1514.6711,-1277.7542C1543.6477,-1231.6649 1580.2031,-1184.8211 1623.6798,-1151 1678.9261,-1108.0232 1708.6703,-1128.3187 1772.6798,-1100 1845.0866,-1067.9661 1922.4227,-1026.3531 1986.4524,-989.715"/>
<polygon fill="#000000" stroke="#000000" points="1988.4673,-992.5941 1995.397,-984.5798 1984.982,-986.5234 1988.4673,-992.5941"/>
<text text-anchor="middle" x="1761.1798" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- participant -->
<g id="node17" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M805.6798,-541.5C805.6798,-541.5 1109.6798,-541.5 1109.6798,-541.5 1115.6798,-541.5 1121.6798,-547.5 1121.6798,-553.5 1121.6798,-553.5 1121.6798,-644.5 1121.6798,-644.5 1121.6798,-650.5 1115.6798,-656.5 1109.6798,-656.5 1109.6798,-656.5 805.6798,-656.5 805.6798,-656.5 799.6798,-656.5 793.6798,-650.5 793.6798,-644.5 793.6798,-644.5 793.6798,-553.5 793.6798,-553.5 793.6798,-547.5 799.6798,-541.5 805.6798,-541.5"/>
<text text-anchor="middle" x="841.6798" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="889.6798,-541.5 889.6798,-656.5 "/>
<text text-anchor="middle" x="900.1798" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="910.6798,-541.5 910.6798,-656.5 "/>
<text text-anchor="middle" x="1005.6798" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="910.6798,-633.5 1100.6798,-633.5 "/>
<text text-anchor="middle" x="1005.6798" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="910.6798,-610.5 1100.6798,-610.5 "/>
<text text-anchor="middle" x="1005.6798" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="910.6798,-587.5 1100.6798,-587.5 "/>
<text text-anchor="middle" x="1005.6798" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="910.6798,-564.5 1100.6798,-564.5 "/>
<text text-anchor="middle" x="1005.6798" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1100.6798,-541.5 1100.6798,-656.5 "/>
<text text-anchor="middle" x="1111.1798" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2009.0209,-823.4813C1942.2453,-782.3931 1855.9444,-735.4188 1772.6798,-708 1657.2578,-669.9918 1334.8975,-634.3291 1131.8934,-614.7024"/>
<polygon fill="#000000" stroke="#000000" points="1132.0053,-611.1971 1121.7158,-613.7222 1131.3341,-618.1649 1132.0053,-611.1971"/>
<text text-anchor="middle" x="1729.1798" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study -->
<g id="node18" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M853.6798,-.5C853.6798,-.5 1243.6798,-.5 1243.6798,-.5 1249.6798,-.5 1255.6798,-6.5 1255.6798,-12.5 1255.6798,-12.5 1255.6798,-264.5 1255.6798,-264.5 1255.6798,-270.5 1249.6798,-276.5 1243.6798,-276.5 1243.6798,-276.5 853.6798,-276.5 853.6798,-276.5 847.6798,-276.5 841.6798,-270.5 841.6798,-264.5 841.6798,-264.5 841.6798,-12.5 841.6798,-12.5 841.6798,-6.5 847.6798,-.5 853.6798,-.5"/>
<text text-anchor="middle" x="869.6798" y="-134.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="897.6798,-.5 897.6798,-276.5 "/>
<text text-anchor="middle" x="908.1798" y="-134.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="918.6798,-.5 918.6798,-276.5 "/>
<text text-anchor="middle" x="1076.6798" y="-261.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="918.6798,-253.5 1234.6798,-253.5 "/>
<text text-anchor="middle" x="1076.6798" y="-238.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="918.6798,-230.5 1234.6798,-230.5 "/>
<text text-anchor="middle" x="1076.6798" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_shorthand</text>
<polyline fill="none" stroke="#000000" points="918.6798,-207.5 1234.6798,-207.5 "/>
<text text-anchor="middle" x="1076.6798" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="918.6798,-184.5 1234.6798,-184.5 "/>
<text text-anchor="middle" x="1076.6798" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="918.6798,-161.5 1234.6798,-161.5 "/>
<text text-anchor="middle" x="1076.6798" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="918.6798,-138.5 1234.6798,-138.5 "/>
<text text-anchor="middle" x="1076.6798" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="918.6798,-115.5 1234.6798,-115.5 "/>
<text text-anchor="middle" x="1076.6798" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="918.6798,-92.5 1234.6798,-92.5 "/>
<text text-anchor="middle" x="1076.6798" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="918.6798,-69.5 1234.6798,-69.5 "/>
<text text-anchor="middle" x="1076.6798" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="918.6798,-46.5 1234.6798,-46.5 "/>
<text text-anchor="middle" x="1076.6798" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="918.6798,-23.5 1234.6798,-23.5 "/>
<text text-anchor="middle" x="1076.6798" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="1234.6798,-.5 1234.6798,-276.5 "/>
<text text-anchor="middle" x="1245.1798" y="-134.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge2" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2184.4288,-823.4438C2261.2034,-701.6481 2376.9804,-469.8307 2255.6798,-328 2192.2291,-253.8102 1595.8677,-188.3273 1265.8528,-157.394"/>
<polygon fill="#000000" stroke="#000000" points="1265.9648,-153.8893 1255.6825,-156.4437 1265.3135,-160.8589 1265.9648,-153.8893"/>
<text text-anchor="middle" x="2344.1798" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- clinical_measure_file -->
<g id="node4" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M51.6798,-777.5C51.6798,-777.5 403.6798,-777.5 403.6798,-777.5 409.6798,-777.5 415.6798,-783.5 415.6798,-789.5 415.6798,-789.5 415.6798,-1018.5 415.6798,-1018.5 415.6798,-1024.5 409.6798,-1030.5 403.6798,-1030.5 403.6798,-1030.5 51.6798,-1030.5 51.6798,-1030.5 45.6798,-1030.5 39.6798,-1024.5 39.6798,-1018.5 39.6798,-1018.5 39.6798,-789.5 39.6798,-789.5 39.6798,-783.5 45.6798,-777.5 51.6798,-777.5"/>
<text text-anchor="middle" x="123.1798" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="206.6798,-777.5 206.6798,-1030.5 "/>
<text text-anchor="middle" x="217.1798" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="227.6798,-777.5 227.6798,-1030.5 "/>
<text text-anchor="middle" x="311.1798" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="227.6798,-1007.5 394.6798,-1007.5 "/>
<text text-anchor="middle" x="311.1798" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="227.6798,-984.5 394.6798,-984.5 "/>
<text text-anchor="middle" x="311.1798" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="227.6798,-961.5 394.6798,-961.5 "/>
<text text-anchor="middle" x="311.1798" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="227.6798,-938.5 394.6798,-938.5 "/>
<text text-anchor="middle" x="311.1798" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="227.6798,-915.5 394.6798,-915.5 "/>
<text text-anchor="middle" x="311.1798" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="227.6798,-892.5 394.6798,-892.5 "/>
<text text-anchor="middle" x="311.1798" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="227.6798,-869.5 394.6798,-869.5 "/>
<text text-anchor="middle" x="311.1798" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="227.6798,-846.5 394.6798,-846.5 "/>
<text text-anchor="middle" x="311.1798" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="227.6798,-823.5 394.6798,-823.5 "/>
<text text-anchor="middle" x="311.1798" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="227.6798,-800.5 394.6798,-800.5 "/>
<text text-anchor="middle" x="311.1798" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="394.6798,-777.5 394.6798,-1030.5 "/>
<text text-anchor="middle" x="405.1798" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M335.3594,-777.4103C362.3449,-751.5193 392.7738,-726.5524 424.6798,-708 484.81,-673.0361 652.1827,-642.2235 783.4912,-622.3591"/>
<polygon fill="#000000" stroke="#000000" points="784.3087,-625.7757 793.6778,-620.829 783.2688,-618.8533 784.3087,-625.7757"/>
<text text-anchor="middle" x="638.1798" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge5" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M227.6962,-777.256C231.1793,-697.8989 242.1467,-594.6297 272.6798,-508 304.1575,-418.6901 319.7511,-394.99 386.6798,-328 449.6407,-264.9815 663.6493,-211.1138 831.5021,-177.0997"/>
<polygon fill="#000000" stroke="#000000" points="832.3646,-180.4964 841.4766,-175.0908 830.9824,-173.6342 832.3646,-180.4964"/>
<text text-anchor="middle" x="358.6798" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- study_admin -->
<g id="node5" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M885.6798,-328.5C885.6798,-328.5 1211.6798,-328.5 1211.6798,-328.5 1217.6798,-328.5 1223.6798,-334.5 1223.6798,-340.5 1223.6798,-340.5 1223.6798,-477.5 1223.6798,-477.5 1223.6798,-483.5 1217.6798,-489.5 1211.6798,-489.5 1211.6798,-489.5 885.6798,-489.5 885.6798,-489.5 879.6798,-489.5 873.6798,-483.5 873.6798,-477.5 873.6798,-477.5 873.6798,-340.5 873.6798,-340.5 873.6798,-334.5 879.6798,-328.5 885.6798,-328.5"/>
<text text-anchor="middle" x="927.6798" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="981.6798,-328.5 981.6798,-489.5 "/>
<text text-anchor="middle" x="992.1798" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1002.6798,-328.5 1002.6798,-489.5 "/>
<text text-anchor="middle" x="1102.6798" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="1002.6798,-466.5 1202.6798,-466.5 "/>
<text text-anchor="middle" x="1102.6798" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="1002.6798,-443.5 1202.6798,-443.5 "/>
<text text-anchor="middle" x="1102.6798" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="1002.6798,-420.5 1202.6798,-420.5 "/>
<text text-anchor="middle" x="1102.6798" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="1002.6798,-397.5 1202.6798,-397.5 "/>
<text text-anchor="middle" x="1102.6798" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="1002.6798,-374.5 1202.6798,-374.5 "/>
<text text-anchor="middle" x="1102.6798" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="1002.6798,-351.5 1202.6798,-351.5 "/>
<text text-anchor="middle" x="1102.6798" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="1202.6798,-328.5 1202.6798,-489.5 "/>
<text text-anchor="middle" x="1213.1798" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge4" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1048.6798,-328.2075C1048.6798,-315.0539 1048.6798,-301.0753 1048.6798,-286.9023"/>
<polygon fill="#000000" stroke="#000000" points="1052.1799,-286.5567 1048.6798,-276.5568 1045.1799,-286.5568 1052.1799,-286.5567"/>
<text text-anchor="middle" x="1105.1798" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- family_relationship -->
<g id="node6" class="node">
<title>family_relationship</title>
<path fill="none" stroke="#000000" d="M446.1798,-881C446.1798,-881 815.1798,-881 815.1798,-881 821.1798,-881 827.1798,-887 827.1798,-893 827.1798,-893 827.1798,-915 827.1798,-915 827.1798,-921 821.1798,-927 815.1798,-927 815.1798,-927 446.1798,-927 446.1798,-927 440.1798,-927 434.1798,-921 434.1798,-915 434.1798,-915 434.1798,-893 434.1798,-893 434.1798,-887 440.1798,-881 446.1798,-881"/>
<text text-anchor="middle" x="511.1798" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
<polyline fill="none" stroke="#000000" points="588.1798,-881 588.1798,-927 "/>
<text text-anchor="middle" x="598.6798" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="609.1798,-881 609.1798,-927 "/>
<text text-anchor="middle" x="707.6798" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">related_to_participant_id</text>
<polyline fill="none" stroke="#000000" points="609.1798,-904 806.1798,-904 "/>
<text text-anchor="middle" x="707.6798" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">relationship</text>
<polyline fill="none" stroke="#000000" points="806.1798,-881 806.1798,-927 "/>
<text text-anchor="middle" x="816.6798" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M645.3435,-880.7273C674.1989,-836.3314 742.2323,-738.3368 818.6798,-675 823.8736,-670.6969 829.3479,-666.5208 835.0013,-662.4869"/>
<polygon fill="#000000" stroke="#000000" points="837.1652,-665.2459 843.4005,-656.6802 833.1844,-659.488 837.1652,-665.2459"/>
<text text-anchor="middle" x="898.1798" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- diagnosis -->
<g id="node7" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M857.6798,-708.5C857.6798,-708.5 1231.6798,-708.5 1231.6798,-708.5 1237.6798,-708.5 1243.6798,-714.5 1243.6798,-720.5 1243.6798,-720.5 1243.6798,-1087.5 1243.6798,-1087.5 1243.6798,-1093.5 1237.6798,-1099.5 1231.6798,-1099.5 1231.6798,-1099.5 857.6798,-1099.5 857.6798,-1099.5 851.6798,-1099.5 845.6798,-1093.5 845.6798,-1087.5 845.6798,-1087.5 845.6798,-720.5 845.6798,-720.5 845.6798,-714.5 851.6798,-708.5 857.6798,-708.5"/>
<text text-anchor="middle" x="887.6798" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="929.6798,-708.5 929.6798,-1099.5 "/>
<text text-anchor="middle" x="940.1798" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="950.6798,-708.5 950.6798,-1099.5 "/>
<text text-anchor="middle" x="1086.6798" y="-1084.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="950.6798,-1076.5 1222.6798,-1076.5 "/>
<text text-anchor="middle" x="1086.6798" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="950.6798,-1053.5 1222.6798,-1053.5 "/>
<text text-anchor="middle" x="1086.6798" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="950.6798,-1030.5 1222.6798,-1030.5 "/>
<text text-anchor="middle" x="1086.6798" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="950.6798,-1007.5 1222.6798,-1007.5 "/>
<text text-anchor="middle" x="1086.6798" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="950.6798,-984.5 1222.6798,-984.5 "/>
<text text-anchor="middle" x="1086.6798" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="950.6798,-961.5 1222.6798,-961.5 "/>
<text text-anchor="middle" x="1086.6798" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="950.6798,-938.5 1222.6798,-938.5 "/>
<text text-anchor="middle" x="1086.6798" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="950.6798,-915.5 1222.6798,-915.5 "/>
<text text-anchor="middle" x="1086.6798" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="950.6798,-892.5 1222.6798,-892.5 "/>
<text text-anchor="middle" x="1086.6798" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="950.6798,-869.5 1222.6798,-869.5 "/>
<text text-anchor="middle" x="1086.6798" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="950.6798,-846.5 1222.6798,-846.5 "/>
<text text-anchor="middle" x="1086.6798" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="950.6798,-823.5 1222.6798,-823.5 "/>
<text text-anchor="middle" x="1086.6798" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="950.6798,-800.5 1222.6798,-800.5 "/>
<text text-anchor="middle" x="1086.6798" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="950.6798,-777.5 1222.6798,-777.5 "/>
<text text-anchor="middle" x="1086.6798" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="950.6798,-754.5 1222.6798,-754.5 "/>
<text text-anchor="middle" x="1086.6798" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="950.6798,-731.5 1222.6798,-731.5 "/>
<text text-anchor="middle" x="1086.6798" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="1222.6798,-708.5 1222.6798,-1099.5 "/>
<text text-anchor="middle" x="1233.1798" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M988.8431,-708.2505C984.624,-693.4594 980.5736,-679.2601 976.8697,-666.275"/>
<polygon fill="#000000" stroke="#000000" points="980.2166,-665.2485 974.1077,-656.5922 973.4851,-667.1687 980.2166,-665.2485"/>
<text text-anchor="middle" x="1028.1798" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- study_personnel -->
<g id="node8" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M1254.1798,-351.5C1254.1798,-351.5 1561.1798,-351.5 1561.1798,-351.5 1567.1798,-351.5 1573.1798,-357.5 1573.1798,-363.5 1573.1798,-363.5 1573.1798,-454.5 1573.1798,-454.5 1573.1798,-460.5 1567.1798,-466.5 1561.1798,-466.5 1561.1798,-466.5 1254.1798,-466.5 1254.1798,-466.5 1248.1798,-466.5 1242.1798,-460.5 1242.1798,-454.5 1242.1798,-454.5 1242.1798,-363.5 1242.1798,-363.5 1242.1798,-357.5 1248.1798,-351.5 1254.1798,-351.5"/>
<text text-anchor="middle" x="1309.1798" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="1376.1798,-351.5 1376.1798,-466.5 "/>
<text text-anchor="middle" x="1386.6798" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1397.1798,-351.5 1397.1798,-466.5 "/>
<text text-anchor="middle" x="1474.6798" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="1397.1798,-443.5 1552.1798,-443.5 "/>
<text text-anchor="middle" x="1474.6798" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="1397.1798,-420.5 1552.1798,-420.5 "/>
<text text-anchor="middle" x="1474.6798" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="1397.1798,-397.5 1552.1798,-397.5 "/>
<text text-anchor="middle" x="1474.6798" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="1397.1798,-374.5 1552.1798,-374.5 "/>
<text text-anchor="middle" x="1474.6798" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="1552.1798,-351.5 1552.1798,-466.5 "/>
<text text-anchor="middle" x="1562.6798" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge9" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1331.1056,-351.3027C1304.1486,-330.9911 1272.5138,-307.1549 1240.3554,-282.9241"/>
<polygon fill="#000000" stroke="#000000" points="1242.2637,-279.9797 1232.1708,-276.7572 1238.0513,-285.5703 1242.2637,-279.9797"/>
<text text-anchor="middle" x="1341.1798" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- publication -->
<g id="node9" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M1603.6798,-391C1603.6798,-391 1813.6798,-391 1813.6798,-391 1819.6798,-391 1825.6798,-397 1825.6798,-403 1825.6798,-403 1825.6798,-415 1825.6798,-415 1825.6798,-421 1819.6798,-427 1813.6798,-427 1813.6798,-427 1603.6798,-427 1603.6798,-427 1597.6798,-427 1591.6798,-421 1591.6798,-415 1591.6798,-415 1591.6798,-403 1591.6798,-403 1591.6798,-397 1597.6798,-391 1603.6798,-391"/>
<text text-anchor="middle" x="1640.1798" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="1688.6798,-391 1688.6798,-427 "/>
<text text-anchor="middle" x="1699.1798" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1709.6798,-391 1709.6798,-427 "/>
<text text-anchor="middle" x="1757.1798" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="1804.6798,-391 1804.6798,-427 "/>
<text text-anchor="middle" x="1815.1798" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge17" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1683.8869,-390.7904C1658.9801,-373.0847 1619.0361,-346.2609 1581.6798,-328 1481.0285,-278.7985 1364.2426,-235.8177 1265.6878,-203.2834"/>
<polygon fill="#000000" stroke="#000000" points="1266.4971,-199.8652 1255.9042,-200.0681 1264.3116,-206.5153 1266.4971,-199.8652"/>
<text text-anchor="middle" x="1591.6798" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- study_arm -->
<g id="node10" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M546.1798,-374.5C546.1798,-374.5 843.1798,-374.5 843.1798,-374.5 849.1798,-374.5 855.1798,-380.5 855.1798,-386.5 855.1798,-386.5 855.1798,-431.5 855.1798,-431.5 855.1798,-437.5 849.1798,-443.5 843.1798,-443.5 843.1798,-443.5 546.1798,-443.5 546.1798,-443.5 540.1798,-443.5 534.1798,-437.5 534.1798,-431.5 534.1798,-431.5 534.1798,-386.5 534.1798,-386.5 534.1798,-380.5 540.1798,-374.5 546.1798,-374.5"/>
<text text-anchor="middle" x="580.1798" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="626.1798,-374.5 626.1798,-443.5 "/>
<text text-anchor="middle" x="636.6798" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="647.1798,-374.5 647.1798,-443.5 "/>
<text text-anchor="middle" x="740.6798" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="647.1798,-420.5 834.1798,-420.5 "/>
<text text-anchor="middle" x="740.6798" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="647.1798,-397.5 834.1798,-397.5 "/>
<text text-anchor="middle" x="740.6798" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="834.1798,-374.5 834.1798,-443.5 "/>
<text text-anchor="middle" x="844.6798" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge20" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M739.8737,-374.4662C771.0848,-350.6171 814.9102,-317.129 859.7609,-282.8575"/>
<polygon fill="#000000" stroke="#000000" points="862.0274,-285.5305 867.8481,-276.6779 857.7772,-279.9685 862.0274,-285.5305"/>
<text text-anchor="middle" x="889.1798" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- therapeutic_procedure -->
<g id="node11" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M1395.1798,-846.5C1395.1798,-846.5 1752.1798,-846.5 1752.1798,-846.5 1758.1798,-846.5 1764.1798,-852.5 1764.1798,-858.5 1764.1798,-858.5 1764.1798,-949.5 1764.1798,-949.5 1764.1798,-955.5 1758.1798,-961.5 1752.1798,-961.5 1752.1798,-961.5 1395.1798,-961.5 1395.1798,-961.5 1389.1798,-961.5 1383.1798,-955.5 1383.1798,-949.5 1383.1798,-949.5 1383.1798,-858.5 1383.1798,-858.5 1383.1798,-852.5 1389.1798,-846.5 1395.1798,-846.5"/>
<text text-anchor="middle" x="1473.6798" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="1564.1798,-846.5 1564.1798,-961.5 "/>
<text text-anchor="middle" x="1574.6798" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1585.1798,-846.5 1585.1798,-961.5 "/>
<text text-anchor="middle" x="1664.1798" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="1585.1798,-938.5 1743.1798,-938.5 "/>
<text text-anchor="middle" x="1664.1798" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="1585.1798,-915.5 1743.1798,-915.5 "/>
<text text-anchor="middle" x="1664.1798" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1585.1798,-892.5 1743.1798,-892.5 "/>
<text text-anchor="middle" x="1664.1798" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="1585.1798,-869.5 1743.1798,-869.5 "/>
<text text-anchor="middle" x="1664.1798" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1743.1798,-846.5 1743.1798,-961.5 "/>
<text text-anchor="middle" x="1753.6798" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1523.7519,-846.4463C1484.7409,-804.0718 1427.4431,-747.2375 1368.6798,-708 1298.5453,-661.1697 1209.1606,-634.4293 1131.6725,-619.1743"/>
<polygon fill="#000000" stroke="#000000" points="1132.2783,-615.7267 1121.7978,-617.2793 1130.959,-622.6013 1132.2783,-615.7267"/>
<text text-anchor="middle" x="1422.6798" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- methylation_array_file -->
<g id="node12" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M1645.1798,-1324C1645.1798,-1324 2012.1798,-1324 2012.1798,-1324 2018.1798,-1324 2024.1798,-1330 2024.1798,-1336 2024.1798,-1336 2024.1798,-1542 2024.1798,-1542 2024.1798,-1548 2018.1798,-1554 2012.1798,-1554 2012.1798,-1554 1645.1798,-1554 1645.1798,-1554 1639.1798,-1554 1633.1798,-1548 1633.1798,-1542 1633.1798,-1542 1633.1798,-1336 1633.1798,-1336 1633.1798,-1330 1639.1798,-1324 1645.1798,-1324"/>
<text text-anchor="middle" x="1722.1798" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="1811.1798,-1324 1811.1798,-1554 "/>
<text text-anchor="middle" x="1821.6798" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1832.1798,-1324 1832.1798,-1554 "/>
<text text-anchor="middle" x="1917.6798" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1832.1798,-1531 2003.1798,-1531 "/>
<text text-anchor="middle" x="1917.6798" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1832.1798,-1508 2003.1798,-1508 "/>
<text text-anchor="middle" x="1917.6798" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1832.1798,-1485 2003.1798,-1485 "/>
<text text-anchor="middle" x="1917.6798" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1832.1798,-1462 2003.1798,-1462 "/>
<text text-anchor="middle" x="1917.6798" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1832.1798,-1439 2003.1798,-1439 "/>
<text text-anchor="middle" x="1917.6798" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1832.1798,-1416 2003.1798,-1416 "/>
<text text-anchor="middle" x="1917.6798" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1832.1798,-1393 2003.1798,-1393 "/>
<text text-anchor="middle" x="1917.6798" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1832.1798,-1370 2003.1798,-1370 "/>
<text text-anchor="middle" x="1917.6798" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="1832.1798,-1347 2003.1798,-1347 "/>
<text text-anchor="middle" x="1917.6798" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="2003.1798,-1324 2003.1798,-1554 "/>
<text text-anchor="middle" x="2013.6798" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1888.6752,-1323.889C1921.1414,-1262.408 1962.345,-1185.662 2000.6798,-1118 2024.0418,-1076.7654 2050.8303,-1031.6633 2073.8426,-993.542"/>
<polygon fill="#000000" stroke="#000000" points="2077.1222,-994.8822 2079.3007,-984.5138 2071.1318,-991.2607 2077.1222,-994.8822"/>
<text text-anchor="middle" x="2092.1798" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- sample_diagnosis -->
<g id="node13" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M2054.1798,-1278C2054.1798,-1278 2487.1798,-1278 2487.1798,-1278 2493.1798,-1278 2499.1798,-1284 2499.1798,-1290 2499.1798,-1290 2499.1798,-1588 2499.1798,-1588 2499.1798,-1594 2493.1798,-1600 2487.1798,-1600 2487.1798,-1600 2054.1798,-1600 2054.1798,-1600 2048.1798,-1600 2042.1798,-1594 2042.1798,-1588 2042.1798,-1588 2042.1798,-1290 2042.1798,-1290 2042.1798,-1284 2048.1798,-1278 2054.1798,-1278"/>
<text text-anchor="middle" x="2113.6798" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2185.1798,-1278 2185.1798,-1600 "/>
<text text-anchor="middle" x="2195.6798" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2206.1798,-1278 2206.1798,-1600 "/>
<text text-anchor="middle" x="2342.1798" y="-1584.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2206.1798,-1577 2478.1798,-1577 "/>
<text text-anchor="middle" x="2342.1798" y="-1561.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="2206.1798,-1554 2478.1798,-1554 "/>
<text text-anchor="middle" x="2342.1798" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2206.1798,-1531 2478.1798,-1531 "/>
<text text-anchor="middle" x="2342.1798" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="2206.1798,-1508 2478.1798,-1508 "/>
<text text-anchor="middle" x="2342.1798" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="2206.1798,-1485 2478.1798,-1485 "/>
<text text-anchor="middle" x="2342.1798" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="2206.1798,-1462 2478.1798,-1462 "/>
<text text-anchor="middle" x="2342.1798" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="2206.1798,-1439 2478.1798,-1439 "/>
<text text-anchor="middle" x="2342.1798" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2206.1798,-1416 2478.1798,-1416 "/>
<text text-anchor="middle" x="2342.1798" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="2206.1798,-1393 2478.1798,-1393 "/>
<text text-anchor="middle" x="2342.1798" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="2206.1798,-1370 2478.1798,-1370 "/>
<text text-anchor="middle" x="2342.1798" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="2206.1798,-1347 2478.1798,-1347 "/>
<text text-anchor="middle" x="2342.1798" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="2206.1798,-1324 2478.1798,-1324 "/>
<text text-anchor="middle" x="2342.1798" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="2206.1798,-1301 2478.1798,-1301 "/>
<text text-anchor="middle" x="2342.1798" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="2478.1798,-1278 2478.1798,-1600 "/>
<text text-anchor="middle" x="2488.6798" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2227.8825,-1277.7568C2203.2533,-1184.9635 2173.2175,-1071.8004 2152.691,-994.4646"/>
<polygon fill="#000000" stroke="#000000" points="2156.0589,-993.5102 2150.1106,-984.7427 2149.2932,-995.306 2156.0589,-993.5102"/>
<text text-anchor="middle" x="2261.6798" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
<!-- study_funding -->
<g id="node14" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M1856.1798,-374.5C1856.1798,-374.5 2235.1798,-374.5 2235.1798,-374.5 2241.1798,-374.5 2247.1798,-380.5 2247.1798,-386.5 2247.1798,-386.5 2247.1798,-431.5 2247.1798,-431.5 2247.1798,-437.5 2241.1798,-443.5 2235.1798,-443.5 2235.1798,-443.5 1856.1798,-443.5 1856.1798,-443.5 1850.1798,-443.5 1844.1798,-437.5 1844.1798,-431.5 1844.1798,-431.5 1844.1798,-386.5 1844.1798,-386.5 1844.1798,-380.5 1850.1798,-374.5 1856.1798,-374.5"/>
<text text-anchor="middle" x="1903.6798" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="1963.1798,-374.5 1963.1798,-443.5 "/>
<text text-anchor="middle" x="1973.6798" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1984.1798,-374.5 1984.1798,-443.5 "/>
<text text-anchor="middle" x="2105.1798" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="1984.1798,-420.5 2226.1798,-420.5 "/>
<text text-anchor="middle" x="2105.1798" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="1984.1798,-397.5 2226.1798,-397.5 "/>
<text text-anchor="middle" x="2105.1798" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="2226.1798,-374.5 2226.1798,-443.5 "/>
<text text-anchor="middle" x="2236.6798" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge13" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1963.124,-374.4477C1924.519,-359.0321 1877.6741,-341.3732 1834.6798,-328 1644.9725,-268.9925 1424.7756,-217.3077 1265.7917,-182.8855"/>
<polygon fill="#000000" stroke="#000000" points="1266.4005,-179.4364 1255.887,-180.7462 1264.9226,-186.2786 1266.4005,-179.4364"/>
<text text-anchor="middle" x="1834.6798" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- pdx -->
<g id="node15" class="node">
<title>pdx</title>
<path fill="none" stroke="#000000" d="M2529.1798,-1335.5C2529.1798,-1335.5 2858.1798,-1335.5 2858.1798,-1335.5 2864.1798,-1335.5 2870.1798,-1341.5 2870.1798,-1347.5 2870.1798,-1347.5 2870.1798,-1530.5 2870.1798,-1530.5 2870.1798,-1536.5 2864.1798,-1542.5 2858.1798,-1542.5 2858.1798,-1542.5 2529.1798,-1542.5 2529.1798,-1542.5 2523.1798,-1542.5 2517.1798,-1536.5 2517.1798,-1530.5 2517.1798,-1530.5 2517.1798,-1347.5 2517.1798,-1347.5 2517.1798,-1341.5 2523.1798,-1335.5 2529.1798,-1335.5"/>
<text text-anchor="middle" x="2538.6798" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
<polyline fill="none" stroke="#000000" points="2560.1798,-1335.5 2560.1798,-1542.5 "/>
<text text-anchor="middle" x="2570.6798" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2581.1798,-1335.5 2581.1798,-1542.5 "/>
<text text-anchor="middle" x="2715.1798" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_site</text>
<polyline fill="none" stroke="#000000" points="2581.1798,-1519.5 2849.1798,-1519.5 "/>
<text text-anchor="middle" x="2715.1798" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_type</text>
<polyline fill="none" stroke="#000000" points="2581.1798,-1496.5 2849.1798,-1496.5 "/>
<text text-anchor="middle" x="2715.1798" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_id</text>
<polyline fill="none" stroke="#000000" points="2581.1798,-1473.5 2849.1798,-1473.5 "/>
<text text-anchor="middle" x="2715.1798" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">mouse_strain</text>
<polyline fill="none" stroke="#000000" points="2581.1798,-1450.5 2849.1798,-1450.5 "/>
<text text-anchor="middle" x="2715.1798" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">strain_immune_system_humanized</text>
<polyline fill="none" stroke="#000000" points="2581.1798,-1427.5 2849.1798,-1427.5 "/>
<text text-anchor="middle" x="2715.1798" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_characterization_method</text>
<polyline fill="none" stroke="#000000" points="2581.1798,-1404.5 2849.1798,-1404.5 "/>
<text text-anchor="middle" x="2715.1798" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_not_mus_or_ebv_origin</text>
<polyline fill="none" stroke="#000000" points="2581.1798,-1381.5 2849.1798,-1381.5 "/>
<text text-anchor="middle" x="2715.1798" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_preparation</text>
<polyline fill="none" stroke="#000000" points="2581.1798,-1358.5 2849.1798,-1358.5 "/>
<text text-anchor="middle" x="2715.1798" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_humanization</text>
<polyline fill="none" stroke="#000000" points="2849.1798,-1335.5 2849.1798,-1542.5 "/>
<text text-anchor="middle" x="2859.6798" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2641.0003,-1335.4877C2607.9405,-1276.9837 2561.4405,-1204.9837 2507.6798,-1151 2444.8385,-1087.8981 2363.3105,-1032.2372 2291.9784,-989.8056"/>
<polygon fill="#000000" stroke="#000000" points="2293.7219,-986.7704 2283.3319,-984.697 2290.1611,-992.7972 2293.7219,-986.7704"/>
<text text-anchor="middle" x="2505.6798" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- synonym -->
<g id="node16" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M925.1798,-1416C925.1798,-1416 1226.1798,-1416 1226.1798,-1416 1232.1798,-1416 1238.1798,-1422 1238.1798,-1428 1238.1798,-1428 1238.1798,-1450 1238.1798,-1450 1238.1798,-1456 1232.1798,-1462 1226.1798,-1462 1226.1798,-1462 925.1798,-1462 925.1798,-1462 919.1798,-1462 913.1798,-1456 913.1798,-1450 913.1798,-1450 913.1798,-1428 913.1798,-1428 913.1798,-1422 919.1798,-1416 925.1798,-1416"/>
<text text-anchor="middle" x="953.1798" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="993.1798,-1416 993.1798,-1462 "/>
<text text-anchor="middle" x="1003.6798" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1014.1798,-1416 1014.1798,-1462 "/>
<text text-anchor="middle" x="1115.6798" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="1014.1798,-1439 1217.1798,-1439 "/>
<text text-anchor="middle" x="1115.6798" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="1217.1798,-1416 1217.1798,-1462 "/>
<text text-anchor="middle" x="1227.6798" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1081.8084,-1415.6736C1098.0138,-1359.1332 1147.7689,-1214.7459 1247.6798,-1151 1297.0878,-1119.4763 1716.6037,-1117.04 1772.6798,-1100 1853.9207,-1075.3131 1937.4535,-1030.5214 2003.1693,-989.9834"/>
<polygon fill="#000000" stroke="#000000" points="2005.2648,-992.8019 2011.9112,-984.5511 2001.5702,-986.8564 2005.2648,-992.8019"/>
<text text-anchor="middle" x="1579.1798" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1092.8413,-1415.9451C1130.8048,-1363.3302 1221.0393,-1228.9622 1252.6798,-1100 1273.4367,-1015.398 1302.4709,-779.4786 1252.6798,-708 1236.6753,-685.0244 1186.1417,-662.9624 1131.3162,-644.77"/>
<polygon fill="#000000" stroke="#000000" points="1132.3562,-641.4279 1121.7638,-641.6521 1130.1841,-648.0824 1132.3562,-641.4279"/>
<text text-anchor="middle" x="1323.1798" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge12" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M950.1515,-1415.9689C698.8214,-1367.171 147.8309,-1245.8011 30.6798,-1100 -24.1386,-1031.7754 11.6798,-991.5195 11.6798,-904 11.6798,-904 11.6798,-904 11.6798,-409 11.6798,-241.0705 527.2789,-175.4706 831.3525,-151.3848"/>
<polygon fill="#000000" stroke="#000000" points="831.9343,-154.85 841.6306,-150.58 831.3878,-147.8714 831.9343,-154.85"/>
<text text-anchor="middle" x="54.1798" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge7" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M878.0574,-541.4781C837.0149,-511.8276 787.9428,-476.3763 750.894,-449.611"/>
<polygon fill="#000000" stroke="#000000" points="752.8586,-446.7125 742.703,-443.6935 748.7593,-452.3867 752.8586,-446.7125"/>
<text text-anchor="middle" x="901.1798" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge6" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M793.5357,-587.8195C654.2391,-574.507 469.8338,-546.5266 423.6798,-490 378.1429,-434.2291 380.7856,-385.8281 423.6798,-328 473.2615,-261.1562 671.5017,-208.66 831.6017,-176.0371"/>
<polygon fill="#000000" stroke="#000000" points="832.498,-179.4268 841.6059,-174.0142 831.1106,-172.5656 832.498,-179.4268"/>
<text text-anchor="middle" x="474.1798" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
</g>
</svg>
</div>
