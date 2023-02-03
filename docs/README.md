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
<svg width="3145pt" height="1735pt"
 viewBox="0.00 0.00 3145.30 1735.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1731)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1731 3141.3036,-1731 3141.3036,4 -4,4"/>
<!-- sequencing_file -->
<g id="node1" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M2181.3036,-1151.5C2181.3036,-1151.5 2650.3036,-1151.5 2650.3036,-1151.5 2656.3036,-1151.5 2662.3036,-1157.5 2662.3036,-1163.5 2662.3036,-1163.5 2662.3036,-1714.5 2662.3036,-1714.5 2662.3036,-1720.5 2656.3036,-1726.5 2650.3036,-1726.5 2650.3036,-1726.5 2181.3036,-1726.5 2181.3036,-1726.5 2175.3036,-1726.5 2169.3036,-1720.5 2169.3036,-1714.5 2169.3036,-1714.5 2169.3036,-1163.5 2169.3036,-1163.5 2169.3036,-1157.5 2175.3036,-1151.5 2181.3036,-1151.5"/>
<text text-anchor="middle" x="2233.3036" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="2297.3036,-1151.5 2297.3036,-1726.5 "/>
<text text-anchor="middle" x="2307.8036" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2318.3036,-1151.5 2318.3036,-1726.5 "/>
<text text-anchor="middle" x="2479.8036" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="2318.3036,-1703.5 2641.3036,-1703.5 "/>
<text text-anchor="middle" x="2479.8036" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2318.3036,-1680.5 2641.3036,-1680.5 "/>
<text text-anchor="middle" x="2479.8036" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2318.3036,-1657.5 2641.3036,-1657.5 "/>
<text text-anchor="middle" x="2479.8036" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="2318.3036,-1634.5 2641.3036,-1634.5 "/>
<text text-anchor="middle" x="2479.8036" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="2318.3036,-1611.5 2641.3036,-1611.5 "/>
<text text-anchor="middle" x="2479.8036" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2318.3036,-1588.5 2641.3036,-1588.5 "/>
<text text-anchor="middle" x="2479.8036" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="2318.3036,-1565.5 2641.3036,-1565.5 "/>
<text text-anchor="middle" x="2479.8036" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2318.3036,-1542.5 2641.3036,-1542.5 "/>
<text text-anchor="middle" x="2479.8036" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2318.3036,-1519.5 2641.3036,-1519.5 "/>
<text text-anchor="middle" x="2479.8036" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2318.3036,-1496.5 2641.3036,-1496.5 "/>
<text text-anchor="middle" x="2479.8036" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2318.3036,-1473.5 2641.3036,-1473.5 "/>
<text text-anchor="middle" x="2479.8036" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2318.3036,-1450.5 2641.3036,-1450.5 "/>
<text text-anchor="middle" x="2479.8036" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2318.3036,-1427.5 2641.3036,-1427.5 "/>
<text text-anchor="middle" x="2479.8036" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="2318.3036,-1404.5 2641.3036,-1404.5 "/>
<text text-anchor="middle" x="2479.8036" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="2318.3036,-1381.5 2641.3036,-1381.5 "/>
<text text-anchor="middle" x="2479.8036" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="2318.3036,-1358.5 2641.3036,-1358.5 "/>
<text text-anchor="middle" x="2479.8036" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="2318.3036,-1335.5 2641.3036,-1335.5 "/>
<text text-anchor="middle" x="2479.8036" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="2318.3036,-1312.5 2641.3036,-1312.5 "/>
<text text-anchor="middle" x="2479.8036" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="2318.3036,-1289.5 2641.3036,-1289.5 "/>
<text text-anchor="middle" x="2479.8036" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2318.3036,-1266.5 2641.3036,-1266.5 "/>
<text text-anchor="middle" x="2479.8036" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="2318.3036,-1243.5 2641.3036,-1243.5 "/>
<text text-anchor="middle" x="2479.8036" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="2318.3036,-1220.5 2641.3036,-1220.5 "/>
<text text-anchor="middle" x="2479.8036" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="2318.3036,-1197.5 2641.3036,-1197.5 "/>
<text text-anchor="middle" x="2479.8036" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="2318.3036,-1174.5 2641.3036,-1174.5 "/>
<text text-anchor="middle" x="2479.8036" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="2641.3036,-1151.5 2641.3036,-1726.5 "/>
<text text-anchor="middle" x="2651.8036" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node8" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1466.8036,-800.5C1466.8036,-800.5 1780.8036,-800.5 1780.8036,-800.5 1786.8036,-800.5 1792.8036,-806.5 1792.8036,-812.5 1792.8036,-812.5 1792.8036,-949.5 1792.8036,-949.5 1792.8036,-955.5 1786.8036,-961.5 1780.8036,-961.5 1780.8036,-961.5 1466.8036,-961.5 1466.8036,-961.5 1460.8036,-961.5 1454.8036,-955.5 1454.8036,-949.5 1454.8036,-949.5 1454.8036,-812.5 1454.8036,-812.5 1454.8036,-806.5 1460.8036,-800.5 1466.8036,-800.5"/>
<text text-anchor="middle" x="1488.8036" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1522.8036,-800.5 1522.8036,-961.5 "/>
<text text-anchor="middle" x="1533.3036" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1543.8036,-800.5 1543.8036,-961.5 "/>
<text text-anchor="middle" x="1657.8036" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="1543.8036,-938.5 1771.8036,-938.5 "/>
<text text-anchor="middle" x="1657.8036" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1543.8036,-915.5 1771.8036,-915.5 "/>
<text text-anchor="middle" x="1657.8036" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1543.8036,-892.5 1771.8036,-892.5 "/>
<text text-anchor="middle" x="1657.8036" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1543.8036,-869.5 1771.8036,-869.5 "/>
<text text-anchor="middle" x="1657.8036" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1543.8036,-846.5 1771.8036,-846.5 "/>
<text text-anchor="middle" x="1657.8036" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1543.8036,-823.5 1771.8036,-823.5 "/>
<text text-anchor="middle" x="1657.8036" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="1771.8036,-800.5 1771.8036,-961.5 "/>
<text text-anchor="middle" x="1782.3036" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2169.1177,-1157.5135C2166.3536,-1155.3104 2163.582,-1153.1385 2160.8036,-1151 2051.5277,-1066.8907 1911.9763,-997.6705 1802.5246,-950.38"/>
<polygon fill="#000000" stroke="#000000" points="1803.6021,-947.0337 1793.0326,-946.3012 1800.8384,-953.465 1803.6021,-947.0337"/>
<text text-anchor="middle" x="2201.3036" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- study -->
<g id="node2" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M751.8036,-.5C751.8036,-.5 1141.8036,-.5 1141.8036,-.5 1147.8036,-.5 1153.8036,-6.5 1153.8036,-12.5 1153.8036,-12.5 1153.8036,-195.5 1153.8036,-195.5 1153.8036,-201.5 1147.8036,-207.5 1141.8036,-207.5 1141.8036,-207.5 751.8036,-207.5 751.8036,-207.5 745.8036,-207.5 739.8036,-201.5 739.8036,-195.5 739.8036,-195.5 739.8036,-12.5 739.8036,-12.5 739.8036,-6.5 745.8036,-.5 751.8036,-.5"/>
<text text-anchor="middle" x="767.8036" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="795.8036,-.5 795.8036,-207.5 "/>
<text text-anchor="middle" x="806.3036" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="816.8036,-.5 816.8036,-207.5 "/>
<text text-anchor="middle" x="974.8036" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="816.8036,-184.5 1132.8036,-184.5 "/>
<text text-anchor="middle" x="974.8036" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="816.8036,-161.5 1132.8036,-161.5 "/>
<text text-anchor="middle" x="974.8036" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="816.8036,-138.5 1132.8036,-138.5 "/>
<text text-anchor="middle" x="974.8036" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="816.8036,-115.5 1132.8036,-115.5 "/>
<text text-anchor="middle" x="974.8036" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="816.8036,-92.5 1132.8036,-92.5 "/>
<text text-anchor="middle" x="974.8036" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="816.8036,-69.5 1132.8036,-69.5 "/>
<text text-anchor="middle" x="974.8036" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="816.8036,-46.5 1132.8036,-46.5 "/>
<text text-anchor="middle" x="974.8036" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="816.8036,-23.5 1132.8036,-23.5 "/>
<text text-anchor="middle" x="974.8036" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="1132.8036,-.5 1132.8036,-207.5 "/>
<text text-anchor="middle" x="1143.3036" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm -->
<g id="node3" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M798.3036,-317C798.3036,-317 1095.3036,-317 1095.3036,-317 1101.3036,-317 1107.3036,-323 1107.3036,-329 1107.3036,-329 1107.3036,-374 1107.3036,-374 1107.3036,-380 1101.3036,-386 1095.3036,-386 1095.3036,-386 798.3036,-386 798.3036,-386 792.3036,-386 786.3036,-380 786.3036,-374 786.3036,-374 786.3036,-329 786.3036,-329 786.3036,-323 792.3036,-317 798.3036,-317"/>
<text text-anchor="middle" x="832.3036" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="878.3036,-317 878.3036,-386 "/>
<text text-anchor="middle" x="888.8036" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="899.3036,-317 899.3036,-386 "/>
<text text-anchor="middle" x="992.8036" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="899.3036,-363 1086.3036,-363 "/>
<text text-anchor="middle" x="992.8036" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="899.3036,-340 1086.3036,-340 "/>
<text text-anchor="middle" x="992.8036" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="1086.3036,-317 1086.3036,-386 "/>
<text text-anchor="middle" x="1096.8036" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge20" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M946.8036,-316.8256C946.8036,-290.8629 946.8036,-253.7725 946.8036,-217.8091"/>
<polygon fill="#000000" stroke="#000000" points="950.3037,-217.7056 946.8036,-207.7056 943.3037,-217.7056 950.3037,-217.7056"/>
<text text-anchor="middle" x="995.3036" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- sample_diagnosis -->
<g id="node4" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M2692.3036,-1220.5C2692.3036,-1220.5 3125.3036,-1220.5 3125.3036,-1220.5 3131.3036,-1220.5 3137.3036,-1226.5 3137.3036,-1232.5 3137.3036,-1232.5 3137.3036,-1645.5 3137.3036,-1645.5 3137.3036,-1651.5 3131.3036,-1657.5 3125.3036,-1657.5 3125.3036,-1657.5 2692.3036,-1657.5 2692.3036,-1657.5 2686.3036,-1657.5 2680.3036,-1651.5 2680.3036,-1645.5 2680.3036,-1645.5 2680.3036,-1232.5 2680.3036,-1232.5 2680.3036,-1226.5 2686.3036,-1220.5 2692.3036,-1220.5"/>
<text text-anchor="middle" x="2751.8036" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2823.3036,-1220.5 2823.3036,-1657.5 "/>
<text text-anchor="middle" x="2833.8036" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2844.3036,-1220.5 2844.3036,-1657.5 "/>
<text text-anchor="middle" x="2980.3036" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2844.3036,-1634.5 3116.3036,-1634.5 "/>
<text text-anchor="middle" x="2980.3036" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="2844.3036,-1611.5 3116.3036,-1611.5 "/>
<text text-anchor="middle" x="2980.3036" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2844.3036,-1588.5 3116.3036,-1588.5 "/>
<text text-anchor="middle" x="2980.3036" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="2844.3036,-1565.5 3116.3036,-1565.5 "/>
<text text-anchor="middle" x="2980.3036" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="2844.3036,-1542.5 3116.3036,-1542.5 "/>
<text text-anchor="middle" x="2980.3036" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="2844.3036,-1519.5 3116.3036,-1519.5 "/>
<text text-anchor="middle" x="2980.3036" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="2844.3036,-1496.5 3116.3036,-1496.5 "/>
<text text-anchor="middle" x="2980.3036" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2844.3036,-1473.5 3116.3036,-1473.5 "/>
<text text-anchor="middle" x="2980.3036" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="2844.3036,-1450.5 3116.3036,-1450.5 "/>
<text text-anchor="middle" x="2980.3036" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="2844.3036,-1427.5 3116.3036,-1427.5 "/>
<text text-anchor="middle" x="2980.3036" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="2844.3036,-1404.5 3116.3036,-1404.5 "/>
<text text-anchor="middle" x="2980.3036" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="2844.3036,-1381.5 3116.3036,-1381.5 "/>
<text text-anchor="middle" x="2980.3036" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="2844.3036,-1358.5 3116.3036,-1358.5 "/>
<text text-anchor="middle" x="2980.3036" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="2844.3036,-1335.5 3116.3036,-1335.5 "/>
<text text-anchor="middle" x="2980.3036" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="2844.3036,-1312.5 3116.3036,-1312.5 "/>
<text text-anchor="middle" x="2980.3036" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="2844.3036,-1289.5 3116.3036,-1289.5 "/>
<text text-anchor="middle" x="2980.3036" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="2844.3036,-1266.5 3116.3036,-1266.5 "/>
<text text-anchor="middle" x="2980.3036" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="2844.3036,-1243.5 3116.3036,-1243.5 "/>
<text text-anchor="middle" x="2980.3036" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="3116.3036,-1220.5 3116.3036,-1657.5 "/>
<text text-anchor="middle" x="3126.8036" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2755.1243,-1220.1983C2729.6561,-1194.1205 2701.7046,-1170.0474 2671.8036,-1151 2400.4431,-978.1389 2023.1892,-915.7257 1803.1307,-893.3462"/>
<polygon fill="#000000" stroke="#000000" points="1803.3953,-889.8553 1793.0965,-892.3425 1802.6985,-896.8206 1803.3953,-889.8553"/>
<text text-anchor="middle" x="2695.8036" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
<!-- study_admin -->
<g id="node5" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M42.8036,-259.5C42.8036,-259.5 368.8036,-259.5 368.8036,-259.5 374.8036,-259.5 380.8036,-265.5 380.8036,-271.5 380.8036,-271.5 380.8036,-431.5 380.8036,-431.5 380.8036,-437.5 374.8036,-443.5 368.8036,-443.5 368.8036,-443.5 42.8036,-443.5 42.8036,-443.5 36.8036,-443.5 30.8036,-437.5 30.8036,-431.5 30.8036,-431.5 30.8036,-271.5 30.8036,-271.5 30.8036,-265.5 36.8036,-259.5 42.8036,-259.5"/>
<text text-anchor="middle" x="84.8036" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="138.8036,-259.5 138.8036,-443.5 "/>
<text text-anchor="middle" x="149.3036" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="159.8036,-259.5 159.8036,-443.5 "/>
<text text-anchor="middle" x="259.8036" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="159.8036,-420.5 359.8036,-420.5 "/>
<text text-anchor="middle" x="259.8036" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="159.8036,-397.5 359.8036,-397.5 "/>
<text text-anchor="middle" x="259.8036" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="159.8036,-374.5 359.8036,-374.5 "/>
<text text-anchor="middle" x="259.8036" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="159.8036,-351.5 359.8036,-351.5 "/>
<text text-anchor="middle" x="259.8036" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="159.8036,-328.5 359.8036,-328.5 "/>
<text text-anchor="middle" x="259.8036" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="159.8036,-305.5 359.8036,-305.5 "/>
<text text-anchor="middle" x="259.8036" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="159.8036,-282.5 359.8036,-282.5 "/>
<text text-anchor="middle" x="259.8036" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="359.8036,-259.5 359.8036,-443.5 "/>
<text text-anchor="middle" x="370.3036" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge11" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M248.6518,-259.3385C258.0038,-246.5666 269.0136,-234.8228 281.8036,-226 353.2554,-176.7109 564.1167,-143.6524 729.4505,-124.5225"/>
<polygon fill="#000000" stroke="#000000" points="730.2375,-127.9553 739.7738,-123.3393 729.4403,-121.0009 730.2375,-127.9553"/>
<text text-anchor="middle" x="338.3036" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- synonym -->
<g id="node6" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M681.3036,-1416C681.3036,-1416 982.3036,-1416 982.3036,-1416 988.3036,-1416 994.3036,-1422 994.3036,-1428 994.3036,-1428 994.3036,-1450 994.3036,-1450 994.3036,-1456 988.3036,-1462 982.3036,-1462 982.3036,-1462 681.3036,-1462 681.3036,-1462 675.3036,-1462 669.3036,-1456 669.3036,-1450 669.3036,-1450 669.3036,-1428 669.3036,-1428 669.3036,-1422 675.3036,-1416 681.3036,-1416"/>
<text text-anchor="middle" x="709.3036" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="749.3036,-1416 749.3036,-1462 "/>
<text text-anchor="middle" x="759.8036" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="770.3036,-1416 770.3036,-1462 "/>
<text text-anchor="middle" x="871.8036" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="770.3036,-1439 973.3036,-1439 "/>
<text text-anchor="middle" x="871.8036" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="973.3036,-1416 973.3036,-1462 "/>
<text text-anchor="middle" x="983.8036" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge5" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M709.9272,-1415.9889C479.4952,-1364.6637 2.8036,-1217.7874 2.8036,-881 2.8036,-881 2.8036,-881 2.8036,-351.5 2.8036,-309.5306 -8.4108,-288.1294 21.8036,-259 120.3213,-164.0201 488.2393,-126.9438 729.3181,-112.6801"/>
<polygon fill="#000000" stroke="#000000" points="729.8472,-116.1553 739.6266,-112.0795 729.4399,-109.1672 729.8472,-116.1553"/>
<text text-anchor="middle" x="45.3036" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M837.9785,-1415.7458C854.2882,-1359.3679 904.26,-1215.318 1003.8036,-1151 1024.5653,-1137.5853 1424.13,-1111.8852 1445.8036,-1100 1499.8961,-1070.3372 1543.8388,-1016.8743 1574.5303,-970.1992"/>
<polygon fill="#000000" stroke="#000000" points="1577.6185,-971.8689 1580.1063,-961.5702 1571.7392,-968.0697 1577.6185,-971.8689"/>
<text text-anchor="middle" x="1342.3036" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- participant -->
<g id="node12" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M794.8036,-495.5C794.8036,-495.5 1098.8036,-495.5 1098.8036,-495.5 1104.8036,-495.5 1110.8036,-501.5 1110.8036,-507.5 1110.8036,-507.5 1110.8036,-598.5 1110.8036,-598.5 1110.8036,-604.5 1104.8036,-610.5 1098.8036,-610.5 1098.8036,-610.5 794.8036,-610.5 794.8036,-610.5 788.8036,-610.5 782.8036,-604.5 782.8036,-598.5 782.8036,-598.5 782.8036,-507.5 782.8036,-507.5 782.8036,-501.5 788.8036,-495.5 794.8036,-495.5"/>
<text text-anchor="middle" x="830.8036" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="878.8036,-495.5 878.8036,-610.5 "/>
<text text-anchor="middle" x="889.3036" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="899.8036,-495.5 899.8036,-610.5 "/>
<text text-anchor="middle" x="994.8036" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="899.8036,-587.5 1089.8036,-587.5 "/>
<text text-anchor="middle" x="994.8036" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="899.8036,-564.5 1089.8036,-564.5 "/>
<text text-anchor="middle" x="994.8036" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="899.8036,-541.5 1089.8036,-541.5 "/>
<text text-anchor="middle" x="994.8036" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="899.8036,-518.5 1089.8036,-518.5 "/>
<text text-anchor="middle" x="994.8036" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1089.8036,-495.5 1089.8036,-610.5 "/>
<text text-anchor="middle" x="1100.3036" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M838.3758,-1415.8074C853.5478,-1361.2509 891.0687,-1220.3117 908.8036,-1100 934.0613,-928.654 942.6113,-724.5688 945.4444,-620.8284"/>
<polygon fill="#000000" stroke="#000000" points="948.9439,-620.8924 945.7088,-610.8036 941.9463,-620.7078 948.9439,-620.8924"/>
<text text-anchor="middle" x="987.3036" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study_personnel -->
<g id="node7" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M449.3036,-294C449.3036,-294 756.3036,-294 756.3036,-294 762.3036,-294 768.3036,-300 768.3036,-306 768.3036,-306 768.3036,-397 768.3036,-397 768.3036,-403 762.3036,-409 756.3036,-409 756.3036,-409 449.3036,-409 449.3036,-409 443.3036,-409 437.3036,-403 437.3036,-397 437.3036,-397 437.3036,-306 437.3036,-306 437.3036,-300 443.3036,-294 449.3036,-294"/>
<text text-anchor="middle" x="504.3036" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="571.3036,-294 571.3036,-409 "/>
<text text-anchor="middle" x="581.8036" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="592.3036,-294 592.3036,-409 "/>
<text text-anchor="middle" x="669.8036" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="592.3036,-386 747.3036,-386 "/>
<text text-anchor="middle" x="669.8036" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="592.3036,-363 747.3036,-363 "/>
<text text-anchor="middle" x="669.8036" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="592.3036,-340 747.3036,-340 "/>
<text text-anchor="middle" x="669.8036" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="592.3036,-317 747.3036,-317 "/>
<text text-anchor="middle" x="669.8036" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="747.3036,-294 747.3036,-409 "/>
<text text-anchor="middle" x="757.8036" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge21" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M683.0222,-293.7846C716.2925,-269.8474 756.0422,-241.2484 794.4657,-213.6036"/>
<polygon fill="#000000" stroke="#000000" points="796.5686,-216.4024 802.6419,-207.721 792.4804,-210.7202 796.5686,-216.4024"/>
<text text-anchor="middle" x="844.3036" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge9" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1559.3535,-800.0242C1468.069,-684.7611 1310.1047,-482.9712 1291.8036,-444 1255.9219,-367.5917 1300.7254,-325.5572 1248.8036,-259 1225.6773,-229.355 1195.3213,-204.8592 1162.7754,-184.7873"/>
<polygon fill="#000000" stroke="#000000" points="1164.3751,-181.6653 1154.0014,-179.5118 1160.768,-187.6644 1164.3751,-181.6653"/>
<text text-anchor="middle" x="1348.3036" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1581.1032,-800.3468C1550.4588,-751.2659 1504.2948,-692.3556 1445.8036,-662 1394.398,-635.3216 1242.3681,-656.439 1185.8036,-644 1152.9473,-636.7746 1118.6034,-625.8545 1086.5307,-614.0597"/>
<polygon fill="#000000" stroke="#000000" points="1087.6955,-610.7586 1077.1028,-610.5439 1085.2496,-617.3174 1087.6955,-610.7586"/>
<text text-anchor="middle" x="1222.3036" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- clinical_measure_file -->
<g id="node9" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M136.8036,-754.5C136.8036,-754.5 488.8036,-754.5 488.8036,-754.5 494.8036,-754.5 500.8036,-760.5 500.8036,-766.5 500.8036,-766.5 500.8036,-995.5 500.8036,-995.5 500.8036,-1001.5 494.8036,-1007.5 488.8036,-1007.5 488.8036,-1007.5 136.8036,-1007.5 136.8036,-1007.5 130.8036,-1007.5 124.8036,-1001.5 124.8036,-995.5 124.8036,-995.5 124.8036,-766.5 124.8036,-766.5 124.8036,-760.5 130.8036,-754.5 136.8036,-754.5"/>
<text text-anchor="middle" x="208.3036" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="291.8036,-754.5 291.8036,-1007.5 "/>
<text text-anchor="middle" x="302.3036" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="312.8036,-754.5 312.8036,-1007.5 "/>
<text text-anchor="middle" x="396.3036" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="312.8036,-984.5 479.8036,-984.5 "/>
<text text-anchor="middle" x="396.3036" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="312.8036,-961.5 479.8036,-961.5 "/>
<text text-anchor="middle" x="396.3036" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="312.8036,-938.5 479.8036,-938.5 "/>
<text text-anchor="middle" x="396.3036" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="312.8036,-915.5 479.8036,-915.5 "/>
<text text-anchor="middle" x="396.3036" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="312.8036,-892.5 479.8036,-892.5 "/>
<text text-anchor="middle" x="396.3036" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="312.8036,-869.5 479.8036,-869.5 "/>
<text text-anchor="middle" x="396.3036" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="312.8036,-846.5 479.8036,-846.5 "/>
<text text-anchor="middle" x="396.3036" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="312.8036,-823.5 479.8036,-823.5 "/>
<text text-anchor="middle" x="396.3036" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="312.8036,-800.5 479.8036,-800.5 "/>
<text text-anchor="middle" x="396.3036" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="312.8036,-777.5 479.8036,-777.5 "/>
<text text-anchor="middle" x="396.3036" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="479.8036,-754.5 479.8036,-1007.5 "/>
<text text-anchor="middle" x="490.3036" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge2" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M335.3625,-754.4325C367.6529,-573.9233 423.6449,-263.6312 427.8036,-259 469.401,-212.6769 606.8196,-172.8057 729.8049,-145.1053"/>
<polygon fill="#000000" stroke="#000000" points="730.7659,-148.477 739.7628,-142.8817 729.2403,-141.6452 730.7659,-148.477"/>
<text text-anchor="middle" x="473.8036" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M362.2565,-754.2953C386.6151,-707.8544 420.644,-659.2974 465.8036,-629 515.2619,-595.8186 655.9758,-576.1405 772.5165,-565.1528"/>
<polygon fill="#000000" stroke="#000000" points="773.0078,-568.6224 782.642,-564.2141 772.3616,-561.6522 773.0078,-568.6224"/>
<text text-anchor="middle" x="595.3036" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- imaging_file -->
<g id="node10" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M1024.8036,-1278C1024.8036,-1278 1358.8036,-1278 1358.8036,-1278 1364.8036,-1278 1370.8036,-1284 1370.8036,-1290 1370.8036,-1290 1370.8036,-1588 1370.8036,-1588 1370.8036,-1594 1364.8036,-1600 1358.8036,-1600 1358.8036,-1600 1024.8036,-1600 1024.8036,-1600 1018.8036,-1600 1012.8036,-1594 1012.8036,-1588 1012.8036,-1588 1012.8036,-1290 1012.8036,-1290 1012.8036,-1284 1018.8036,-1278 1024.8036,-1278"/>
<text text-anchor="middle" x="1064.8036" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="1116.8036,-1278 1116.8036,-1600 "/>
<text text-anchor="middle" x="1127.3036" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1137.8036,-1278 1137.8036,-1600 "/>
<text text-anchor="middle" x="1243.8036" y="-1584.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1137.8036,-1577 1349.8036,-1577 "/>
<text text-anchor="middle" x="1243.8036" y="-1561.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1137.8036,-1554 1349.8036,-1554 "/>
<text text-anchor="middle" x="1243.8036" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1137.8036,-1531 1349.8036,-1531 "/>
<text text-anchor="middle" x="1243.8036" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1137.8036,-1508 1349.8036,-1508 "/>
<text text-anchor="middle" x="1243.8036" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1137.8036,-1485 1349.8036,-1485 "/>
<text text-anchor="middle" x="1243.8036" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1137.8036,-1462 1349.8036,-1462 "/>
<text text-anchor="middle" x="1243.8036" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1137.8036,-1439 1349.8036,-1439 "/>
<text text-anchor="middle" x="1243.8036" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1137.8036,-1416 1349.8036,-1416 "/>
<text text-anchor="middle" x="1243.8036" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1137.8036,-1393 1349.8036,-1393 "/>
<text text-anchor="middle" x="1243.8036" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="1137.8036,-1370 1349.8036,-1370 "/>
<text text-anchor="middle" x="1243.8036" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="1137.8036,-1347 1349.8036,-1347 "/>
<text text-anchor="middle" x="1243.8036" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="1137.8036,-1324 1349.8036,-1324 "/>
<text text-anchor="middle" x="1243.8036" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1137.8036,-1301 1349.8036,-1301 "/>
<text text-anchor="middle" x="1243.8036" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="1349.8036,-1278 1349.8036,-1600 "/>
<text text-anchor="middle" x="1360.3036" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1283.5894,-1277.7013C1311.7491,-1234.3899 1344.6622,-1189.0548 1379.8036,-1151 1404.9532,-1123.7654 1419.2704,-1125.8884 1445.8036,-1100 1486.7381,-1060.0603 1527.3502,-1011.0118 1559.4233,-969.4647"/>
<polygon fill="#000000" stroke="#000000" points="1562.202,-971.5928 1565.516,-961.5296 1556.6498,-967.3298 1562.202,-971.5928"/>
<text text-anchor="middle" x="1478.3036" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- methylation_array_file -->
<g id="node11" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M1401.3036,-1324C1401.3036,-1324 1768.3036,-1324 1768.3036,-1324 1774.3036,-1324 1780.3036,-1330 1780.3036,-1336 1780.3036,-1336 1780.3036,-1542 1780.3036,-1542 1780.3036,-1548 1774.3036,-1554 1768.3036,-1554 1768.3036,-1554 1401.3036,-1554 1401.3036,-1554 1395.3036,-1554 1389.3036,-1548 1389.3036,-1542 1389.3036,-1542 1389.3036,-1336 1389.3036,-1336 1389.3036,-1330 1395.3036,-1324 1401.3036,-1324"/>
<text text-anchor="middle" x="1478.3036" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="1567.3036,-1324 1567.3036,-1554 "/>
<text text-anchor="middle" x="1577.8036" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1588.3036,-1324 1588.3036,-1554 "/>
<text text-anchor="middle" x="1673.8036" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1588.3036,-1531 1759.3036,-1531 "/>
<text text-anchor="middle" x="1673.8036" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1588.3036,-1508 1759.3036,-1508 "/>
<text text-anchor="middle" x="1673.8036" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1588.3036,-1485 1759.3036,-1485 "/>
<text text-anchor="middle" x="1673.8036" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1588.3036,-1462 1759.3036,-1462 "/>
<text text-anchor="middle" x="1673.8036" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1588.3036,-1439 1759.3036,-1439 "/>
<text text-anchor="middle" x="1673.8036" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1588.3036,-1416 1759.3036,-1416 "/>
<text text-anchor="middle" x="1673.8036" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1588.3036,-1393 1759.3036,-1393 "/>
<text text-anchor="middle" x="1673.8036" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1588.3036,-1370 1759.3036,-1370 "/>
<text text-anchor="middle" x="1673.8036" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="1588.3036,-1347 1759.3036,-1347 "/>
<text text-anchor="middle" x="1673.8036" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="1759.3036,-1324 1759.3036,-1554 "/>
<text text-anchor="middle" x="1769.8036" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1592.8608,-1323.7205C1600.1455,-1219.4927 1610.7273,-1068.0921 1617.4356,-972.1115"/>
<polygon fill="#000000" stroke="#000000" points="1620.9473,-972.0651 1618.1531,-961.8453 1613.9643,-971.577 1620.9473,-972.0651"/>
<text text-anchor="middle" x="1698.3036" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge14" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1069.6746,-495.4352C1088.2027,-481.2787 1104.7768,-464.2333 1115.8036,-444 1155.1496,-371.8031 1148.9014,-334.2664 1115.8036,-259 1109.0383,-243.6153 1099.9087,-229.0896 1089.3784,-215.5581"/>
<polygon fill="#000000" stroke="#000000" points="1092.0357,-213.2779 1083.0238,-207.7068 1086.5946,-217.6818 1092.0357,-213.2779"/>
<text text-anchor="middle" x="1194.3036" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge13" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M946.8036,-495.2582C946.8036,-463.875 946.8036,-425.6377 946.8036,-396.4898"/>
<polygon fill="#000000" stroke="#000000" points="950.3037,-396.1919 946.8036,-386.1919 943.3037,-396.192 950.3037,-396.1919"/>
<text text-anchor="middle" x="997.3036" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_funding -->
<g id="node13" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M1313.3036,-317C1313.3036,-317 1692.3036,-317 1692.3036,-317 1698.3036,-317 1704.3036,-323 1704.3036,-329 1704.3036,-329 1704.3036,-374 1704.3036,-374 1704.3036,-380 1698.3036,-386 1692.3036,-386 1692.3036,-386 1313.3036,-386 1313.3036,-386 1307.3036,-386 1301.3036,-380 1301.3036,-374 1301.3036,-374 1301.3036,-329 1301.3036,-329 1301.3036,-323 1307.3036,-317 1313.3036,-317"/>
<text text-anchor="middle" x="1360.8036" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="1420.3036,-317 1420.3036,-386 "/>
<text text-anchor="middle" x="1430.8036" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1441.3036,-317 1441.3036,-386 "/>
<text text-anchor="middle" x="1562.3036" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="1441.3036,-363 1683.3036,-363 "/>
<text text-anchor="middle" x="1562.3036" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="1441.3036,-340 1683.3036,-340 "/>
<text text-anchor="middle" x="1562.3036" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="1683.3036,-317 1683.3036,-386 "/>
<text text-anchor="middle" x="1693.8036" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge19" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1449.6743,-316.969C1406.8234,-290.0264 1344.4122,-252.8001 1286.8036,-226 1247.685,-207.8017 1205.0369,-190.5737 1163.5815,-175.1087"/>
<polygon fill="#000000" stroke="#000000" points="1164.7912,-171.8245 1154.1981,-171.6305 1162.3581,-178.3881 1164.7912,-171.8245"/>
<text text-anchor="middle" x="1379.8036" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- diagnosis -->
<g id="node14" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1050.8036,-662.5C1050.8036,-662.5 1424.8036,-662.5 1424.8036,-662.5 1430.8036,-662.5 1436.8036,-668.5 1436.8036,-674.5 1436.8036,-674.5 1436.8036,-1087.5 1436.8036,-1087.5 1436.8036,-1093.5 1430.8036,-1099.5 1424.8036,-1099.5 1424.8036,-1099.5 1050.8036,-1099.5 1050.8036,-1099.5 1044.8036,-1099.5 1038.8036,-1093.5 1038.8036,-1087.5 1038.8036,-1087.5 1038.8036,-674.5 1038.8036,-674.5 1038.8036,-668.5 1044.8036,-662.5 1050.8036,-662.5"/>
<text text-anchor="middle" x="1080.8036" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1122.8036,-662.5 1122.8036,-1099.5 "/>
<text text-anchor="middle" x="1133.3036" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1143.8036,-662.5 1143.8036,-1099.5 "/>
<text text-anchor="middle" x="1279.8036" y="-1084.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1143.8036,-1076.5 1415.8036,-1076.5 "/>
<text text-anchor="middle" x="1279.8036" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1143.8036,-1053.5 1415.8036,-1053.5 "/>
<text text-anchor="middle" x="1279.8036" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1143.8036,-1030.5 1415.8036,-1030.5 "/>
<text text-anchor="middle" x="1279.8036" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1143.8036,-1007.5 1415.8036,-1007.5 "/>
<text text-anchor="middle" x="1279.8036" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="1143.8036,-984.5 1415.8036,-984.5 "/>
<text text-anchor="middle" x="1279.8036" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="1143.8036,-961.5 1415.8036,-961.5 "/>
<text text-anchor="middle" x="1279.8036" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="1143.8036,-938.5 1415.8036,-938.5 "/>
<text text-anchor="middle" x="1279.8036" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1143.8036,-915.5 1415.8036,-915.5 "/>
<text text-anchor="middle" x="1279.8036" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1143.8036,-892.5 1415.8036,-892.5 "/>
<text text-anchor="middle" x="1279.8036" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="1143.8036,-869.5 1415.8036,-869.5 "/>
<text text-anchor="middle" x="1279.8036" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="1143.8036,-846.5 1415.8036,-846.5 "/>
<text text-anchor="middle" x="1279.8036" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="1143.8036,-823.5 1415.8036,-823.5 "/>
<text text-anchor="middle" x="1279.8036" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="1143.8036,-800.5 1415.8036,-800.5 "/>
<text text-anchor="middle" x="1279.8036" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1143.8036,-777.5 1415.8036,-777.5 "/>
<text text-anchor="middle" x="1279.8036" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="1143.8036,-754.5 1415.8036,-754.5 "/>
<text text-anchor="middle" x="1279.8036" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="1143.8036,-731.5 1415.8036,-731.5 "/>
<text text-anchor="middle" x="1279.8036" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1143.8036,-708.5 1415.8036,-708.5 "/>
<text text-anchor="middle" x="1279.8036" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1143.8036,-685.5 1415.8036,-685.5 "/>
<text text-anchor="middle" x="1279.8036" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1415.8036,-662.5 1415.8036,-1099.5 "/>
<text text-anchor="middle" x="1426.3036" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1043.7024,-662.2193C1029.8452,-646.6002 1016.6525,-631.7301 1004.7132,-618.2727"/>
<polygon fill="#000000" stroke="#000000" points="1007.0875,-615.675 997.8327,-610.5174 1001.8512,-620.3206 1007.0875,-615.675"/>
<text text-anchor="middle" x="1070.3036" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- therapeutic_procedure -->
<g id="node15" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M531.3036,-823.5C531.3036,-823.5 888.3036,-823.5 888.3036,-823.5 894.3036,-823.5 900.3036,-829.5 900.3036,-835.5 900.3036,-835.5 900.3036,-926.5 900.3036,-926.5 900.3036,-932.5 894.3036,-938.5 888.3036,-938.5 888.3036,-938.5 531.3036,-938.5 531.3036,-938.5 525.3036,-938.5 519.3036,-932.5 519.3036,-926.5 519.3036,-926.5 519.3036,-835.5 519.3036,-835.5 519.3036,-829.5 525.3036,-823.5 531.3036,-823.5"/>
<text text-anchor="middle" x="609.8036" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="700.3036,-823.5 700.3036,-938.5 "/>
<text text-anchor="middle" x="710.8036" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="721.3036,-823.5 721.3036,-938.5 "/>
<text text-anchor="middle" x="800.3036" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="721.3036,-915.5 879.3036,-915.5 "/>
<text text-anchor="middle" x="800.3036" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="721.3036,-892.5 879.3036,-892.5 "/>
<text text-anchor="middle" x="800.3036" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="721.3036,-869.5 879.3036,-869.5 "/>
<text text-anchor="middle" x="800.3036" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="721.3036,-846.5 879.3036,-846.5 "/>
<text text-anchor="middle" x="800.3036" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="879.3036,-823.5 879.3036,-938.5 "/>
<text text-anchor="middle" x="889.8036" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M699.5818,-823.3376C693.1157,-767.6846 692.7776,-683.9895 735.8036,-629 742.4439,-620.5133 756.0769,-612.1436 773.3684,-604.237"/>
<polygon fill="#000000" stroke="#000000" points="774.9655,-607.3587 782.7265,-600.1464 772.1617,-600.9447 774.9655,-607.3587"/>
<text text-anchor="middle" x="828.8036" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- publication -->
<g id="node16" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M1734.8036,-333.5C1734.8036,-333.5 1944.8036,-333.5 1944.8036,-333.5 1950.8036,-333.5 1956.8036,-339.5 1956.8036,-345.5 1956.8036,-345.5 1956.8036,-357.5 1956.8036,-357.5 1956.8036,-363.5 1950.8036,-369.5 1944.8036,-369.5 1944.8036,-369.5 1734.8036,-369.5 1734.8036,-369.5 1728.8036,-369.5 1722.8036,-363.5 1722.8036,-357.5 1722.8036,-357.5 1722.8036,-345.5 1722.8036,-345.5 1722.8036,-339.5 1728.8036,-333.5 1734.8036,-333.5"/>
<text text-anchor="middle" x="1771.3036" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="1819.8036,-333.5 1819.8036,-369.5 "/>
<text text-anchor="middle" x="1830.3036" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1840.8036,-333.5 1840.8036,-369.5 "/>
<text text-anchor="middle" x="1888.3036" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="1935.8036,-333.5 1935.8036,-369.5 "/>
<text text-anchor="middle" x="1946.3036" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge3" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1820.389,-333.1453C1796.829,-311.9328 1754.9966,-277.5684 1712.8036,-259 1537.2082,-181.7235 1321.9054,-142.5257 1164.3261,-122.9172"/>
<polygon fill="#000000" stroke="#000000" points="1164.383,-119.398 1154.0311,-121.6537 1163.5303,-126.3459 1164.383,-119.398"/>
<text text-anchor="middle" x="1705.8036" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- pdx -->
<g id="node17" class="node">
<title>pdx</title>
<path fill="none" stroke="#000000" d="M1810.3036,-1335.5C1810.3036,-1335.5 2139.3036,-1335.5 2139.3036,-1335.5 2145.3036,-1335.5 2151.3036,-1341.5 2151.3036,-1347.5 2151.3036,-1347.5 2151.3036,-1530.5 2151.3036,-1530.5 2151.3036,-1536.5 2145.3036,-1542.5 2139.3036,-1542.5 2139.3036,-1542.5 1810.3036,-1542.5 1810.3036,-1542.5 1804.3036,-1542.5 1798.3036,-1536.5 1798.3036,-1530.5 1798.3036,-1530.5 1798.3036,-1347.5 1798.3036,-1347.5 1798.3036,-1341.5 1804.3036,-1335.5 1810.3036,-1335.5"/>
<text text-anchor="middle" x="1819.8036" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
<polyline fill="none" stroke="#000000" points="1841.3036,-1335.5 1841.3036,-1542.5 "/>
<text text-anchor="middle" x="1851.8036" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1862.3036,-1335.5 1862.3036,-1542.5 "/>
<text text-anchor="middle" x="1996.3036" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">injection_type_and_site</text>
<polyline fill="none" stroke="#000000" points="1862.3036,-1519.5 2130.3036,-1519.5 "/>
<text text-anchor="middle" x="1996.3036" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_id</text>
<polyline fill="none" stroke="#000000" points="1862.3036,-1496.5 2130.3036,-1496.5 "/>
<text text-anchor="middle" x="1996.3036" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_type</text>
<polyline fill="none" stroke="#000000" points="1862.3036,-1473.5 2130.3036,-1473.5 "/>
<text text-anchor="middle" x="1996.3036" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">mouse_strain</text>
<polyline fill="none" stroke="#000000" points="1862.3036,-1450.5 2130.3036,-1450.5 "/>
<text text-anchor="middle" x="1996.3036" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">strain_immune_system_humanized</text>
<polyline fill="none" stroke="#000000" points="1862.3036,-1427.5 2130.3036,-1427.5 "/>
<text text-anchor="middle" x="1996.3036" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_characterization_method</text>
<polyline fill="none" stroke="#000000" points="1862.3036,-1404.5 2130.3036,-1404.5 "/>
<text text-anchor="middle" x="1996.3036" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_not_mus_or_ebv_origin</text>
<polyline fill="none" stroke="#000000" points="1862.3036,-1381.5 2130.3036,-1381.5 "/>
<text text-anchor="middle" x="1996.3036" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_preparation</text>
<polyline fill="none" stroke="#000000" points="1862.3036,-1358.5 2130.3036,-1358.5 "/>
<text text-anchor="middle" x="1996.3036" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_humanization</text>
<polyline fill="none" stroke="#000000" points="2130.3036,-1335.5 2130.3036,-1542.5 "/>
<text text-anchor="middle" x="2140.8036" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1920.1188,-1335.4081C1885.5711,-1271.6875 1839.0498,-1188.9282 1793.8036,-1118 1761.7574,-1067.7642 1723.2521,-1013.6348 1690.997,-969.8061"/>
<polygon fill="#000000" stroke="#000000" points="1693.8034,-967.7144 1685.05,-961.7454 1688.1705,-971.8703 1693.8034,-967.7144"/>
<text text-anchor="middle" x="1823.8036" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
</g>
</svg>
</div>
