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
<svg width="2403pt" height="1522pt"
 viewBox="0.00 0.00 2402.50 1522.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1518)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1518 2398.5,-1518 2398.5,4 -4,4"/>
<!-- imaging_file -->
<g id="node1" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M1715.5,-1088C1715.5,-1088 2004.5,-1088 2004.5,-1088 2010.5,-1088 2016.5,-1094 2016.5,-1100 2016.5,-1100 2016.5,-1421 2016.5,-1421 2016.5,-1427 2010.5,-1433 2004.5,-1433 2004.5,-1433 1715.5,-1433 1715.5,-1433 1709.5,-1433 1703.5,-1427 1703.5,-1421 1703.5,-1421 1703.5,-1100 1703.5,-1100 1703.5,-1094 1709.5,-1088 1715.5,-1088"/>
<text text-anchor="middle" x="1755.5" y="-1256.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="1807.5,-1088 1807.5,-1433 "/>
<text text-anchor="middle" x="1818" y="-1256.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1828.5,-1088 1828.5,-1433 "/>
<text text-anchor="middle" x="1912" y="-1417.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1828.5,-1410 1995.5,-1410 "/>
<text text-anchor="middle" x="1912" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1828.5,-1387 1995.5,-1387 "/>
<text text-anchor="middle" x="1912" y="-1371.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1828.5,-1364 1995.5,-1364 "/>
<text text-anchor="middle" x="1912" y="-1348.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1828.5,-1341 1995.5,-1341 "/>
<text text-anchor="middle" x="1912" y="-1325.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1828.5,-1318 1995.5,-1318 "/>
<text text-anchor="middle" x="1912" y="-1302.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1828.5,-1295 1995.5,-1295 "/>
<text text-anchor="middle" x="1912" y="-1279.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1828.5,-1272 1995.5,-1272 "/>
<text text-anchor="middle" x="1912" y="-1256.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1828.5,-1249 1995.5,-1249 "/>
<text text-anchor="middle" x="1912" y="-1233.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1828.5,-1226 1995.5,-1226 "/>
<text text-anchor="middle" x="1912" y="-1210.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="1828.5,-1203 1995.5,-1203 "/>
<text text-anchor="middle" x="1912" y="-1187.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="1828.5,-1180 1995.5,-1180 "/>
<text text-anchor="middle" x="1912" y="-1164.8" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="1828.5,-1157 1995.5,-1157 "/>
<text text-anchor="middle" x="1912" y="-1141.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1828.5,-1134 1995.5,-1134 "/>
<text text-anchor="middle" x="1912" y="-1118.8" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="1828.5,-1111 1995.5,-1111 "/>
<text text-anchor="middle" x="1912" y="-1095.8" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="1995.5,-1088 1995.5,-1433 "/>
<text text-anchor="middle" x="2006" y="-1256.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- experiment -->
<g id="node9" class="node">
<title>experiment</title>
<path fill="none" stroke="#000000" d="M1677,-714C1677,-714 1945,-714 1945,-714 1951,-714 1957,-720 1957,-726 1957,-726 1957,-748 1957,-748 1957,-754 1951,-760 1945,-760 1945,-760 1677,-760 1677,-760 1671,-760 1665,-754 1665,-748 1665,-748 1665,-726 1665,-726 1665,-720 1671,-714 1677,-714"/>
<text text-anchor="middle" x="1714" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">experiment</text>
<polyline fill="none" stroke="#000000" points="1763,-714 1763,-760 "/>
<text text-anchor="middle" x="1773.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1784,-714 1784,-760 "/>
<text text-anchor="middle" x="1860" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="1784,-737 1936,-737 "/>
<text text-anchor="middle" x="1860" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">experiment_id</text>
<polyline fill="none" stroke="#000000" points="1936,-714 1936,-760 "/>
<text text-anchor="middle" x="1946.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;experiment -->
<g id="edge5" class="edge">
<title>imaging_file&#45;&gt;experiment</title>
<path fill="none" stroke="#000000" d="M1852.678,-1087.9922C1850.4362,-1050.3756 1847.5849,-1010.8151 1844,-974 1836.8843,-900.9257 1823.8656,-815.7922 1816.4856,-770.0775"/>
<polygon fill="#000000" stroke="#000000" points="1819.9289,-769.4451 1814.8691,-760.1365 1813.0196,-770.5686 1819.9289,-769.4451"/>
<text text-anchor="middle" x="1898.5" y="-977.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- sample -->
<g id="node11" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1321,-518.5C1321,-518.5 1635,-518.5 1635,-518.5 1641,-518.5 1647,-524.5 1647,-530.5 1647,-530.5 1647,-943.5 1647,-943.5 1647,-949.5 1641,-955.5 1635,-955.5 1635,-955.5 1321,-955.5 1321,-955.5 1315,-955.5 1309,-949.5 1309,-943.5 1309,-943.5 1309,-530.5 1309,-530.5 1309,-524.5 1315,-518.5 1321,-518.5"/>
<text text-anchor="middle" x="1343" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1377,-518.5 1377,-955.5 "/>
<text text-anchor="middle" x="1387.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1398,-518.5 1398,-955.5 "/>
<text text-anchor="middle" x="1512" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">biosample_accession</text>
<polyline fill="none" stroke="#000000" points="1398,-932.5 1626,-932.5 "/>
<text text-anchor="middle" x="1512" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_sample_id</text>
<polyline fill="none" stroke="#000000" points="1398,-909.5 1626,-909.5 "/>
<text text-anchor="middle" x="1512" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">derived_from_specimen</text>
<polyline fill="none" stroke="#000000" points="1398,-886.5 1626,-886.5 "/>
<text text-anchor="middle" x="1512" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="1398,-863.5 1626,-863.5 "/>
<text text-anchor="middle" x="1512" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1398,-840.5 1626,-840.5 "/>
<text text-anchor="middle" x="1512" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1398,-817.5 1626,-817.5 "/>
<text text-anchor="middle" x="1512" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1398,-794.5 1626,-794.5 "/>
<text text-anchor="middle" x="1512" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1398,-771.5 1626,-771.5 "/>
<text text-anchor="middle" x="1512" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1398,-748.5 1626,-748.5 "/>
<text text-anchor="middle" x="1512" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1398,-725.5 1626,-725.5 "/>
<text text-anchor="middle" x="1512" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="1398,-702.5 1626,-702.5 "/>
<text text-anchor="middle" x="1512" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1398,-679.5 1626,-679.5 "/>
<text text-anchor="middle" x="1512" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="1398,-656.5 1626,-656.5 "/>
<text text-anchor="middle" x="1512" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="1398,-633.5 1626,-633.5 "/>
<text text-anchor="middle" x="1512" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage</text>
<polyline fill="none" stroke="#000000" points="1398,-610.5 1626,-610.5 "/>
<text text-anchor="middle" x="1512" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1398,-587.5 1626,-587.5 "/>
<text text-anchor="middle" x="1512" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1398,-564.5 1626,-564.5 "/>
<text text-anchor="middle" x="1512" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1398,-541.5 1626,-541.5 "/>
<text text-anchor="middle" x="1512" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_status</text>
<polyline fill="none" stroke="#000000" points="1626,-518.5 1626,-955.5 "/>
<text text-anchor="middle" x="1636.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1798.1485,-1087.8175C1776.3335,-1045.9217 1747.9994,-1004.4752 1712,-974 1692.0467,-957.1086 1677.5819,-970.754 1656,-956 1655.8167,-955.8747 1655.6335,-955.7492 1655.4504,-955.6234"/>
<polygon fill="#000000" stroke="#000000" points="1657.4507,-952.7511 1647.2737,-949.8047 1653.3921,-958.4544 1657.4507,-952.7511"/>
<text text-anchor="middle" x="1778.5" y="-977.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- sequencing_file -->
<g id="node2" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M1193.5,-1007.5C1193.5,-1007.5 1662.5,-1007.5 1662.5,-1007.5 1668.5,-1007.5 1674.5,-1013.5 1674.5,-1019.5 1674.5,-1019.5 1674.5,-1501.5 1674.5,-1501.5 1674.5,-1507.5 1668.5,-1513.5 1662.5,-1513.5 1662.5,-1513.5 1193.5,-1513.5 1193.5,-1513.5 1187.5,-1513.5 1181.5,-1507.5 1181.5,-1501.5 1181.5,-1501.5 1181.5,-1019.5 1181.5,-1019.5 1181.5,-1013.5 1187.5,-1007.5 1193.5,-1007.5"/>
<text text-anchor="middle" x="1245.5" y="-1256.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="1309.5,-1007.5 1309.5,-1513.5 "/>
<text text-anchor="middle" x="1320" y="-1256.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1330.5,-1007.5 1330.5,-1513.5 "/>
<text text-anchor="middle" x="1492" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="1330.5,-1490.5 1653.5,-1490.5 "/>
<text text-anchor="middle" x="1492" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1330.5,-1467.5 1653.5,-1467.5 "/>
<text text-anchor="middle" x="1492" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1330.5,-1444.5 1653.5,-1444.5 "/>
<text text-anchor="middle" x="1492" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="1330.5,-1421.5 1653.5,-1421.5 "/>
<text text-anchor="middle" x="1492" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="1330.5,-1398.5 1653.5,-1398.5 "/>
<text text-anchor="middle" x="1492" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1330.5,-1375.5 1653.5,-1375.5 "/>
<text text-anchor="middle" x="1492" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1330.5,-1352.5 1653.5,-1352.5 "/>
<text text-anchor="middle" x="1492" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1330.5,-1329.5 1653.5,-1329.5 "/>
<text text-anchor="middle" x="1492" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1330.5,-1306.5 1653.5,-1306.5 "/>
<text text-anchor="middle" x="1492" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1330.5,-1283.5 1653.5,-1283.5 "/>
<text text-anchor="middle" x="1492" y="-1268.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1330.5,-1260.5 1653.5,-1260.5 "/>
<text text-anchor="middle" x="1492" y="-1245.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1330.5,-1237.5 1653.5,-1237.5 "/>
<text text-anchor="middle" x="1492" y="-1222.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="1330.5,-1214.5 1653.5,-1214.5 "/>
<text text-anchor="middle" x="1492" y="-1199.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="1330.5,-1191.5 1653.5,-1191.5 "/>
<text text-anchor="middle" x="1492" y="-1176.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="1330.5,-1168.5 1653.5,-1168.5 "/>
<text text-anchor="middle" x="1492" y="-1153.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="1330.5,-1145.5 1653.5,-1145.5 "/>
<text text-anchor="middle" x="1492" y="-1130.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="1330.5,-1122.5 1653.5,-1122.5 "/>
<text text-anchor="middle" x="1492" y="-1107.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1330.5,-1099.5 1653.5,-1099.5 "/>
<text text-anchor="middle" x="1492" y="-1084.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="1330.5,-1076.5 1653.5,-1076.5 "/>
<text text-anchor="middle" x="1492" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="1330.5,-1053.5 1653.5,-1053.5 "/>
<text text-anchor="middle" x="1492" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="1330.5,-1030.5 1653.5,-1030.5 "/>
<text text-anchor="middle" x="1492" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="1653.5,-1007.5 1653.5,-1513.5 "/>
<text text-anchor="middle" x="1664" y="-1256.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;experiment -->
<g id="edge8" class="edge">
<title>sequencing_file&#45;&gt;experiment</title>
<path fill="none" stroke="#000000" d="M1539.7845,-1007.2555C1550.5633,-995.0569 1562.2801,-983.8252 1575,-974 1604.1854,-951.4564 1625.2904,-976.4186 1656,-956 1726.5816,-909.0707 1775.1358,-818.2101 1797.3165,-769.5807"/>
<polygon fill="#000000" stroke="#000000" points="1800.642,-770.7176 1801.5239,-760.1595 1794.2504,-767.8631 1800.642,-770.7176"/>
<text text-anchor="middle" x="1641.5" y="-977.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1419.9835,-1007.2383C1420.7607,-995.9937 1421.7549,-984.8733 1423,-974 1423.3157,-971.2428 1423.6515,-968.471 1424.006,-965.6871"/>
<polygon fill="#000000" stroke="#000000" points="1427.5039,-965.9374 1425.3697,-955.5597 1420.5665,-965.0032 1427.5039,-965.9374"/>
<text text-anchor="middle" x="1489.5" y="-977.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- study_personnel -->
<g id="node3" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M364.5,-317C364.5,-317 671.5,-317 671.5,-317 677.5,-317 683.5,-323 683.5,-329 683.5,-329 683.5,-420 683.5,-420 683.5,-426 677.5,-432 671.5,-432 671.5,-432 364.5,-432 364.5,-432 358.5,-432 352.5,-426 352.5,-420 352.5,-420 352.5,-329 352.5,-329 352.5,-323 358.5,-317 364.5,-317"/>
<text text-anchor="middle" x="419.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="486.5,-317 486.5,-432 "/>
<text text-anchor="middle" x="497" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="507.5,-317 507.5,-432 "/>
<text text-anchor="middle" x="585" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="507.5,-409 662.5,-409 "/>
<text text-anchor="middle" x="585" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="507.5,-386 662.5,-386 "/>
<text text-anchor="middle" x="585" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="507.5,-363 662.5,-363 "/>
<text text-anchor="middle" x="585" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="507.5,-340 662.5,-340 "/>
<text text-anchor="middle" x="585" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="662.5,-317 662.5,-432 "/>
<text text-anchor="middle" x="673" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node6" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M1198,-.5C1198,-.5 1588,-.5 1588,-.5 1594,-.5 1600,-6.5 1600,-12.5 1600,-12.5 1600,-218.5 1600,-218.5 1600,-224.5 1594,-230.5 1588,-230.5 1588,-230.5 1198,-230.5 1198,-230.5 1192,-230.5 1186,-224.5 1186,-218.5 1186,-218.5 1186,-12.5 1186,-12.5 1186,-6.5 1192,-.5 1198,-.5"/>
<text text-anchor="middle" x="1214" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="1242,-.5 1242,-230.5 "/>
<text text-anchor="middle" x="1252.5" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1263,-.5 1263,-230.5 "/>
<text text-anchor="middle" x="1421" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">bioproject_accession</text>
<polyline fill="none" stroke="#000000" points="1263,-207.5 1579,-207.5 "/>
<text text-anchor="middle" x="1421" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="1263,-184.5 1579,-184.5 "/>
<text text-anchor="middle" x="1421" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="1263,-161.5 1579,-161.5 "/>
<text text-anchor="middle" x="1421" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="1263,-138.5 1579,-138.5 "/>
<text text-anchor="middle" x="1421" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="1263,-115.5 1579,-115.5 "/>
<text text-anchor="middle" x="1421" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="1263,-92.5 1579,-92.5 "/>
<text text-anchor="middle" x="1421" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="1263,-69.5 1579,-69.5 "/>
<text text-anchor="middle" x="1421" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="1263,-46.5 1579,-46.5 "/>
<text text-anchor="middle" x="1421" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="1263,-23.5 1579,-23.5 "/>
<text text-anchor="middle" x="1421" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="1579,-.5 1579,-230.5 "/>
<text text-anchor="middle" x="1589.5" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge18" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M615.7939,-316.9174C640.1318,-304.164 666.5539,-291.6043 692,-282 849.4288,-222.5806 1034.9705,-179.6334 1175.6101,-152.254"/>
<polygon fill="#000000" stroke="#000000" points="1176.5047,-155.6459 1185.6576,-150.3096 1175.1747,-148.7734 1176.5047,-155.6459"/>
<text text-anchor="middle" x="854.5" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- clinical_measure_file -->
<g id="node4" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M12,-622C12,-622 364,-622 364,-622 370,-622 376,-628 376,-634 376,-634 376,-840 376,-840 376,-846 370,-852 364,-852 364,-852 12,-852 12,-852 6,-852 0,-846 0,-840 0,-840 0,-634 0,-634 0,-628 6,-622 12,-622"/>
<text text-anchor="middle" x="83.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="167,-622 167,-852 "/>
<text text-anchor="middle" x="177.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="188,-622 188,-852 "/>
<text text-anchor="middle" x="271.5" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="188,-829 355,-829 "/>
<text text-anchor="middle" x="271.5" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="188,-806 355,-806 "/>
<text text-anchor="middle" x="271.5" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="188,-783 355,-783 "/>
<text text-anchor="middle" x="271.5" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="188,-760 355,-760 "/>
<text text-anchor="middle" x="271.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="188,-737 355,-737 "/>
<text text-anchor="middle" x="271.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="188,-714 355,-714 "/>
<text text-anchor="middle" x="271.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="188,-691 355,-691 "/>
<text text-anchor="middle" x="271.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="188,-668 355,-668 "/>
<text text-anchor="middle" x="271.5" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="188,-645 355,-645 "/>
<text text-anchor="middle" x="271.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="355,-622 355,-852 "/>
<text text-anchor="middle" x="365.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node5" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M966.5,-305.5C966.5,-305.5 1225.5,-305.5 1225.5,-305.5 1231.5,-305.5 1237.5,-311.5 1237.5,-317.5 1237.5,-317.5 1237.5,-431.5 1237.5,-431.5 1237.5,-437.5 1231.5,-443.5 1225.5,-443.5 1225.5,-443.5 966.5,-443.5 966.5,-443.5 960.5,-443.5 954.5,-437.5 954.5,-431.5 954.5,-431.5 954.5,-317.5 954.5,-317.5 954.5,-311.5 960.5,-305.5 966.5,-305.5"/>
<text text-anchor="middle" x="1002.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1050.5,-305.5 1050.5,-443.5 "/>
<text text-anchor="middle" x="1061" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1071.5,-305.5 1071.5,-443.5 "/>
<text text-anchor="middle" x="1144" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbGaP_subject_id</text>
<polyline fill="none" stroke="#000000" points="1071.5,-420.5 1216.5,-420.5 "/>
<text text-anchor="middle" x="1144" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="1071.5,-397.5 1216.5,-397.5 "/>
<text text-anchor="middle" x="1144" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="1071.5,-374.5 1216.5,-374.5 "/>
<text text-anchor="middle" x="1144" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1071.5,-351.5 1216.5,-351.5 "/>
<text text-anchor="middle" x="1144" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1071.5,-328.5 1216.5,-328.5 "/>
<text text-anchor="middle" x="1144" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="1216.5,-305.5 1216.5,-443.5 "/>
<text text-anchor="middle" x="1227" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M262.6005,-621.7227C307.1406,-565.6217 369.5303,-505.8462 444,-485 551.2812,-454.9689 838.3352,-499.1518 945,-467 960.2348,-462.4078 975.4817,-455.8914 990.1129,-448.4166"/>
<polygon fill="#000000" stroke="#000000" points="991.9318,-451.4142 999.1378,-443.6473 988.6611,-445.2252 991.9318,-451.4142"/>
<text text-anchor="middle" x="573.5" y="-488.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure -->
<g id="node8" class="node">
<title>clinical_measure</title>
<path fill="none" stroke="#000000" d="M713.5,-356.5C713.5,-356.5 924.5,-356.5 924.5,-356.5 930.5,-356.5 936.5,-362.5 936.5,-368.5 936.5,-368.5 936.5,-380.5 936.5,-380.5 936.5,-386.5 930.5,-392.5 924.5,-392.5 924.5,-392.5 713.5,-392.5 713.5,-392.5 707.5,-392.5 701.5,-386.5 701.5,-380.5 701.5,-380.5 701.5,-368.5 701.5,-368.5 701.5,-362.5 707.5,-356.5 713.5,-356.5"/>
<text text-anchor="middle" x="770" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure</text>
<polyline fill="none" stroke="#000000" points="838.5,-356.5 838.5,-392.5 "/>
<text text-anchor="middle" x="849" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="859.5,-356.5 859.5,-392.5 "/>
<text text-anchor="middle" x="887.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">name</text>
<polyline fill="none" stroke="#000000" points="915.5,-356.5 915.5,-392.5 "/>
<text text-anchor="middle" x="926" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;clinical_measure -->
<g id="edge7" class="edge">
<title>clinical_measure_file&#45;&gt;clinical_measure</title>
<path fill="none" stroke="#000000" d="M156.3488,-621.8711C150.3954,-573.5345 154.6785,-520.4307 189,-485 208.4555,-464.9158 665.5704,-476.1306 692,-467 732.0726,-453.1561 770.301,-422.0247 794.1527,-399.7012"/>
<polygon fill="#000000" stroke="#000000" points="796.8668,-401.9483 801.6723,-392.5059 792.0273,-396.8907 796.8668,-401.9483"/>
<text text-anchor="middle" x="275" y="-488.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge14" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1175.2004,-305.433C1199.311,-284.4073 1226.5634,-260.6417 1253.4249,-237.217"/>
<polygon fill="#000000" stroke="#000000" points="1255.7515,-239.832 1260.9879,-230.6216 1251.1508,-234.5563 1255.7515,-239.832"/>
<text text-anchor="middle" x="1286.5" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- diagnosis -->
<g id="node7" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M406,-610.5C406,-610.5 780,-610.5 780,-610.5 786,-610.5 792,-616.5 792,-622.5 792,-622.5 792,-851.5 792,-851.5 792,-857.5 786,-863.5 780,-863.5 780,-863.5 406,-863.5 406,-863.5 400,-863.5 394,-857.5 394,-851.5 394,-851.5 394,-622.5 394,-622.5 394,-616.5 400,-610.5 406,-610.5"/>
<text text-anchor="middle" x="436" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="478,-610.5 478,-863.5 "/>
<text text-anchor="middle" x="488.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="499,-610.5 499,-863.5 "/>
<text text-anchor="middle" x="635" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="499,-840.5 771,-840.5 "/>
<text text-anchor="middle" x="635" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="499,-817.5 771,-817.5 "/>
<text text-anchor="middle" x="635" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="499,-794.5 771,-794.5 "/>
<text text-anchor="middle" x="635" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="499,-771.5 771,-771.5 "/>
<text text-anchor="middle" x="635" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="499,-748.5 771,-748.5 "/>
<text text-anchor="middle" x="635" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="499,-725.5 771,-725.5 "/>
<text text-anchor="middle" x="635" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="499,-702.5 771,-702.5 "/>
<text text-anchor="middle" x="635" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="499,-679.5 771,-679.5 "/>
<text text-anchor="middle" x="635" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="499,-656.5 771,-656.5 "/>
<text text-anchor="middle" x="635" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="499,-633.5 771,-633.5 "/>
<text text-anchor="middle" x="635" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="771,-610.5 771,-863.5 "/>
<text text-anchor="middle" x="781.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M630.1774,-610.2541C650.5105,-563.219 680.8377,-514.2478 725,-485 765.8965,-457.915 898.3709,-482.2265 945,-467 959.6236,-462.2247 974.2996,-455.7822 988.4488,-448.5065"/>
<polygon fill="#000000" stroke="#000000" points="990.4733,-451.3945 997.6649,-443.6142 987.1911,-445.2116 990.4733,-451.3945"/>
<text text-anchor="middle" x="769.5" y="-488.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- clinical_measure&#45;&gt;study -->
<g id="edge6" class="edge">
<title>clinical_measure&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M840.0678,-356.1684C864.1419,-335.927 905.3503,-303.3809 945,-282 1017.4896,-242.9104 1101.1131,-209.1033 1176.3402,-182.3586"/>
<polygon fill="#000000" stroke="#000000" points="1177.6816,-185.5967 1185.9449,-178.9658 1175.3501,-178.9964 1177.6816,-185.5967"/>
<text text-anchor="middle" x="1074" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure</text>
</g>
<!-- experiment&#45;&gt;study -->
<g id="edge1" class="edge">
<title>experiment&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1800.659,-713.9229C1779.6827,-669.6329 1727.9412,-572.2989 1656,-518 1601.4734,-476.8452 1554.9731,-519.2803 1511,-467 1457.3368,-403.1989 1506.5227,-361.0371 1480,-282 1475.3187,-268.0498 1469.5852,-253.8451 1463.3158,-239.9091"/>
<polygon fill="#000000" stroke="#000000" points="1466.4825,-238.418 1459.1242,-230.7953 1460.1229,-241.343 1466.4825,-238.418"/>
<text text-anchor="middle" x="1562.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_experiment</text>
</g>
<!-- therapeutic_procedure -->
<g id="node10" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M913.5,-679.5C913.5,-679.5 1278.5,-679.5 1278.5,-679.5 1284.5,-679.5 1290.5,-685.5 1290.5,-691.5 1290.5,-691.5 1290.5,-782.5 1290.5,-782.5 1290.5,-788.5 1284.5,-794.5 1278.5,-794.5 1278.5,-794.5 913.5,-794.5 913.5,-794.5 907.5,-794.5 901.5,-788.5 901.5,-782.5 901.5,-782.5 901.5,-691.5 901.5,-691.5 901.5,-685.5 907.5,-679.5 913.5,-679.5"/>
<text text-anchor="middle" x="992" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="1082.5,-679.5 1082.5,-794.5 "/>
<text text-anchor="middle" x="1093" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1103.5,-679.5 1103.5,-794.5 "/>
<text text-anchor="middle" x="1186.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="1103.5,-771.5 1269.5,-771.5 "/>
<text text-anchor="middle" x="1186.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="1103.5,-748.5 1269.5,-748.5 "/>
<text text-anchor="middle" x="1186.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatement_outcome</text>
<polyline fill="none" stroke="#000000" points="1103.5,-725.5 1269.5,-725.5 "/>
<text text-anchor="middle" x="1186.5" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1103.5,-702.5 1269.5,-702.5 "/>
<text text-anchor="middle" x="1186.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1269.5,-679.5 1269.5,-794.5 "/>
<text text-anchor="middle" x="1280" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1096,-679.16C1096,-618.2234 1096,-521.8451 1096,-453.8327"/>
<polygon fill="#000000" stroke="#000000" points="1099.5001,-453.5914 1096,-443.5914 1092.5001,-453.5915 1099.5001,-453.5914"/>
<text text-anchor="middle" x="1189" y="-488.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1317.721,-518.3875C1306.4285,-506.6626 1294.8219,-495.4309 1283,-485 1268.6729,-472.3587 1252.6918,-460.3928 1236.2725,-449.3301"/>
<polygon fill="#000000" stroke="#000000" points="1237.9243,-446.2262 1227.6528,-443.6285 1234.0624,-452.0646 1237.9243,-446.2262"/>
<text text-anchor="middle" x="1332.5" y="-488.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge16" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1416.2291,-518.2708C1412.6599,-501.014 1409.5095,-483.7774 1407,-467 1395.8716,-392.6003 1392.2111,-308.4196 1391.4083,-241.0949"/>
<polygon fill="#000000" stroke="#000000" points="1394.906,-240.8281 1391.3067,-230.8634 1387.9063,-240.8977 1394.906,-240.8281"/>
<text text-anchor="middle" x="1443.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_admin -->
<g id="node12" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M1635,-282.5C1635,-282.5 1961,-282.5 1961,-282.5 1967,-282.5 1973,-288.5 1973,-294.5 1973,-294.5 1973,-454.5 1973,-454.5 1973,-460.5 1967,-466.5 1961,-466.5 1961,-466.5 1635,-466.5 1635,-466.5 1629,-466.5 1623,-460.5 1623,-454.5 1623,-454.5 1623,-294.5 1623,-294.5 1623,-288.5 1629,-282.5 1635,-282.5"/>
<text text-anchor="middle" x="1677" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="1731,-282.5 1731,-466.5 "/>
<text text-anchor="middle" x="1741.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1752,-282.5 1752,-466.5 "/>
<text text-anchor="middle" x="1852" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="1752,-443.5 1952,-443.5 "/>
<text text-anchor="middle" x="1852" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="1752,-420.5 1952,-420.5 "/>
<text text-anchor="middle" x="1852" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="1752,-397.5 1952,-397.5 "/>
<text text-anchor="middle" x="1852" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="1752,-374.5 1952,-374.5 "/>
<text text-anchor="middle" x="1852" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="1752,-351.5 1952,-351.5 "/>
<text text-anchor="middle" x="1852" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="1752,-328.5 1952,-328.5 "/>
<text text-anchor="middle" x="1852" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="1752,-305.5 1952,-305.5 "/>
<text text-anchor="middle" x="1852" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="1952,-282.5 1952,-466.5 "/>
<text text-anchor="middle" x="1962.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge2" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1654.0718,-282.457C1630.5813,-267.4347 1605.9402,-251.6766 1581.5695,-236.0914"/>
<polygon fill="#000000" stroke="#000000" points="1583.2732,-233.0264 1572.9629,-230.5874 1579.5018,-238.9236 1583.2732,-233.0264"/>
<text text-anchor="middle" x="1675.5" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- study_funding -->
<g id="node13" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M2003.5,-305.5C2003.5,-305.5 2382.5,-305.5 2382.5,-305.5 2388.5,-305.5 2394.5,-311.5 2394.5,-317.5 2394.5,-317.5 2394.5,-431.5 2394.5,-431.5 2394.5,-437.5 2388.5,-443.5 2382.5,-443.5 2382.5,-443.5 2003.5,-443.5 2003.5,-443.5 1997.5,-443.5 1991.5,-437.5 1991.5,-431.5 1991.5,-431.5 1991.5,-317.5 1991.5,-317.5 1991.5,-311.5 1997.5,-305.5 2003.5,-305.5"/>
<text text-anchor="middle" x="2051" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="2110.5,-305.5 2110.5,-443.5 "/>
<text text-anchor="middle" x="2121" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2131.5,-305.5 2131.5,-443.5 "/>
<text text-anchor="middle" x="2252.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="2131.5,-420.5 2373.5,-420.5 "/>
<text text-anchor="middle" x="2252.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="2131.5,-397.5 2373.5,-397.5 "/>
<text text-anchor="middle" x="2252.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_system</text>
<polyline fill="none" stroke="#000000" points="2131.5,-374.5 2373.5,-374.5 "/>
<text text-anchor="middle" x="2252.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="2131.5,-351.5 2373.5,-351.5 "/>
<text text-anchor="middle" x="2252.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="2131.5,-328.5 2373.5,-328.5 "/>
<text text-anchor="middle" x="2252.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="2373.5,-305.5 2373.5,-443.5 "/>
<text text-anchor="middle" x="2384" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge11" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2042.165,-305.3933C2022.1035,-297.0828 2001.672,-289.0546 1982,-282 1860.7505,-238.5186 1722.2679,-198.8842 1610.0569,-169.2023"/>
<polygon fill="#000000" stroke="#000000" points="1610.8755,-165.7986 1600.3136,-166.6325 1609.0903,-172.5671 1610.8755,-165.7986"/>
<text text-anchor="middle" x="1981" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- alias -->
<g id="node14" class="node">
<title>alias</title>
<path fill="none" stroke="#000000" d="M855.5,-1214.5C855.5,-1214.5 1060.5,-1214.5 1060.5,-1214.5 1066.5,-1214.5 1072.5,-1220.5 1072.5,-1226.5 1072.5,-1226.5 1072.5,-1294.5 1072.5,-1294.5 1072.5,-1300.5 1066.5,-1306.5 1060.5,-1306.5 1060.5,-1306.5 855.5,-1306.5 855.5,-1306.5 849.5,-1306.5 843.5,-1300.5 843.5,-1294.5 843.5,-1294.5 843.5,-1226.5 843.5,-1226.5 843.5,-1220.5 849.5,-1214.5 855.5,-1214.5"/>
<text text-anchor="middle" x="868.5" y="-1256.8" font-family="Times,serif" font-size="14.00" fill="#000000">alias</text>
<polyline fill="none" stroke="#000000" points="893.5,-1214.5 893.5,-1306.5 "/>
<text text-anchor="middle" x="904" y="-1256.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="914.5,-1214.5 914.5,-1306.5 "/>
<text text-anchor="middle" x="983" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_id</text>
<polyline fill="none" stroke="#000000" points="914.5,-1283.5 1051.5,-1283.5 "/>
<text text-anchor="middle" x="983" y="-1268.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_node</text>
<polyline fill="none" stroke="#000000" points="914.5,-1260.5 1051.5,-1260.5 "/>
<text text-anchor="middle" x="983" y="-1245.3" font-family="Times,serif" font-size="14.00" fill="#000000">repository_id</text>
<polyline fill="none" stroke="#000000" points="914.5,-1237.5 1051.5,-1237.5 "/>
<text text-anchor="middle" x="983" y="-1222.3" font-family="Times,serif" font-size="14.00" fill="#000000">repository_name</text>
<polyline fill="none" stroke="#000000" points="1051.5,-1214.5 1051.5,-1306.5 "/>
<text text-anchor="middle" x="1062" y="-1256.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- alias&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>alias&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M933.2781,-1214.4474C903.552,-1156.2173 855.3672,-1051.9588 837,-956 818.7019,-860.4021 784.9019,-600.2166 837,-518 865.4128,-473.1615 898.2989,-492.2347 945,-467 955.6709,-461.234 966.6392,-455.0483 977.5597,-448.7092"/>
<polygon fill="#000000" stroke="#000000" points="979.4353,-451.6669 986.3008,-443.5975 975.9017,-445.6243 979.4353,-451.6669"/>
<text text-anchor="middle" x="864.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_alias</text>
</g>
<!-- alias&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>alias&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M986.7092,-1214.2966C1023.5078,-1158.4152 1092.1743,-1064.6873 1172,-1007 1221.2997,-971.3728 1249.9847,-992.0174 1299,-956 1299.5101,-955.6252 1300.0196,-955.2486 1300.5285,-954.8702"/>
<polygon fill="#000000" stroke="#000000" points="1302.9113,-957.4537 1308.7184,-948.5921 1298.6526,-951.8982 1302.9113,-957.4537"/>
<text text-anchor="middle" x="1292.5" y="-977.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_alias</text>
</g>
</g>
</svg>
</div>
