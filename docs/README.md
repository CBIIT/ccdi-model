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
<svg width="3071pt" height="1735pt"
 viewBox="0.00 0.00 3070.68 1735.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1731)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1731 3066.6823,-1731 3066.6823,4 -4,4"/>
<!-- study -->
<g id="node1" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M675.1823,-.5C675.1823,-.5 1065.1823,-.5 1065.1823,-.5 1071.1823,-.5 1077.1823,-6.5 1077.1823,-12.5 1077.1823,-12.5 1077.1823,-195.5 1077.1823,-195.5 1077.1823,-201.5 1071.1823,-207.5 1065.1823,-207.5 1065.1823,-207.5 675.1823,-207.5 675.1823,-207.5 669.1823,-207.5 663.1823,-201.5 663.1823,-195.5 663.1823,-195.5 663.1823,-12.5 663.1823,-12.5 663.1823,-6.5 669.1823,-.5 675.1823,-.5"/>
<text text-anchor="middle" x="691.1823" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="719.1823,-.5 719.1823,-207.5 "/>
<text text-anchor="middle" x="729.6823" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="740.1823,-.5 740.1823,-207.5 "/>
<text text-anchor="middle" x="898.1823" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="740.1823,-184.5 1056.1823,-184.5 "/>
<text text-anchor="middle" x="898.1823" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="740.1823,-161.5 1056.1823,-161.5 "/>
<text text-anchor="middle" x="898.1823" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="740.1823,-138.5 1056.1823,-138.5 "/>
<text text-anchor="middle" x="898.1823" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="740.1823,-115.5 1056.1823,-115.5 "/>
<text text-anchor="middle" x="898.1823" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="740.1823,-92.5 1056.1823,-92.5 "/>
<text text-anchor="middle" x="898.1823" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="740.1823,-69.5 1056.1823,-69.5 "/>
<text text-anchor="middle" x="898.1823" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="740.1823,-46.5 1056.1823,-46.5 "/>
<text text-anchor="middle" x="898.1823" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="740.1823,-23.5 1056.1823,-23.5 "/>
<text text-anchor="middle" x="898.1823" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="1056.1823,-.5 1056.1823,-207.5 "/>
<text text-anchor="middle" x="1066.6823" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis -->
<g id="node2" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M2106.6823,-1220.5C2106.6823,-1220.5 2539.6823,-1220.5 2539.6823,-1220.5 2545.6823,-1220.5 2551.6823,-1226.5 2551.6823,-1232.5 2551.6823,-1232.5 2551.6823,-1645.5 2551.6823,-1645.5 2551.6823,-1651.5 2545.6823,-1657.5 2539.6823,-1657.5 2539.6823,-1657.5 2106.6823,-1657.5 2106.6823,-1657.5 2100.6823,-1657.5 2094.6823,-1651.5 2094.6823,-1645.5 2094.6823,-1645.5 2094.6823,-1232.5 2094.6823,-1232.5 2094.6823,-1226.5 2100.6823,-1220.5 2106.6823,-1220.5"/>
<text text-anchor="middle" x="2166.1823" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2237.6823,-1220.5 2237.6823,-1657.5 "/>
<text text-anchor="middle" x="2248.1823" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2258.6823,-1220.5 2258.6823,-1657.5 "/>
<text text-anchor="middle" x="2394.6823" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2258.6823,-1634.5 2530.6823,-1634.5 "/>
<text text-anchor="middle" x="2394.6823" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="2258.6823,-1611.5 2530.6823,-1611.5 "/>
<text text-anchor="middle" x="2394.6823" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2258.6823,-1588.5 2530.6823,-1588.5 "/>
<text text-anchor="middle" x="2394.6823" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="2258.6823,-1565.5 2530.6823,-1565.5 "/>
<text text-anchor="middle" x="2394.6823" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="2258.6823,-1542.5 2530.6823,-1542.5 "/>
<text text-anchor="middle" x="2394.6823" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="2258.6823,-1519.5 2530.6823,-1519.5 "/>
<text text-anchor="middle" x="2394.6823" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="2258.6823,-1496.5 2530.6823,-1496.5 "/>
<text text-anchor="middle" x="2394.6823" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2258.6823,-1473.5 2530.6823,-1473.5 "/>
<text text-anchor="middle" x="2394.6823" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="2258.6823,-1450.5 2530.6823,-1450.5 "/>
<text text-anchor="middle" x="2394.6823" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="2258.6823,-1427.5 2530.6823,-1427.5 "/>
<text text-anchor="middle" x="2394.6823" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="2258.6823,-1404.5 2530.6823,-1404.5 "/>
<text text-anchor="middle" x="2394.6823" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="2258.6823,-1381.5 2530.6823,-1381.5 "/>
<text text-anchor="middle" x="2394.6823" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="2258.6823,-1358.5 2530.6823,-1358.5 "/>
<text text-anchor="middle" x="2394.6823" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="2258.6823,-1335.5 2530.6823,-1335.5 "/>
<text text-anchor="middle" x="2394.6823" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="2258.6823,-1312.5 2530.6823,-1312.5 "/>
<text text-anchor="middle" x="2394.6823" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="2258.6823,-1289.5 2530.6823,-1289.5 "/>
<text text-anchor="middle" x="2394.6823" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="2258.6823,-1266.5 2530.6823,-1266.5 "/>
<text text-anchor="middle" x="2394.6823" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="2258.6823,-1243.5 2530.6823,-1243.5 "/>
<text text-anchor="middle" x="2394.6823" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="2530.6823,-1220.5 2530.6823,-1657.5 "/>
<text text-anchor="middle" x="2541.1823" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node12" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1382.1823,-800.5C1382.1823,-800.5 1696.1823,-800.5 1696.1823,-800.5 1702.1823,-800.5 1708.1823,-806.5 1708.1823,-812.5 1708.1823,-812.5 1708.1823,-949.5 1708.1823,-949.5 1708.1823,-955.5 1702.1823,-961.5 1696.1823,-961.5 1696.1823,-961.5 1382.1823,-961.5 1382.1823,-961.5 1376.1823,-961.5 1370.1823,-955.5 1370.1823,-949.5 1370.1823,-949.5 1370.1823,-812.5 1370.1823,-812.5 1370.1823,-806.5 1376.1823,-800.5 1382.1823,-800.5"/>
<text text-anchor="middle" x="1404.1823" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1438.1823,-800.5 1438.1823,-961.5 "/>
<text text-anchor="middle" x="1448.6823" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1459.1823,-800.5 1459.1823,-961.5 "/>
<text text-anchor="middle" x="1573.1823" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="1459.1823,-938.5 1687.1823,-938.5 "/>
<text text-anchor="middle" x="1573.1823" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1459.1823,-915.5 1687.1823,-915.5 "/>
<text text-anchor="middle" x="1573.1823" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1459.1823,-892.5 1687.1823,-892.5 "/>
<text text-anchor="middle" x="1573.1823" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1459.1823,-869.5 1687.1823,-869.5 "/>
<text text-anchor="middle" x="1573.1823" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1459.1823,-846.5 1687.1823,-846.5 "/>
<text text-anchor="middle" x="1573.1823" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1459.1823,-823.5 1687.1823,-823.5 "/>
<text text-anchor="middle" x="1573.1823" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="1687.1823,-800.5 1687.1823,-961.5 "/>
<text text-anchor="middle" x="1697.6823" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2159.649,-1220.2404C2136.165,-1195.3181 2111.1175,-1171.5349 2085.1823,-1151 1974.2013,-1063.1278 1829.9953,-993.328 1717.6555,-946.7268"/>
<polygon fill="#000000" stroke="#000000" points="1718.8372,-943.4282 1708.258,-942.8517 1716.1686,-949.8996 1718.8372,-943.4282"/>
<text text-anchor="middle" x="2132.1823" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
<!-- sequencing_file -->
<g id="node3" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M2581.6823,-1151.5C2581.6823,-1151.5 3050.6823,-1151.5 3050.6823,-1151.5 3056.6823,-1151.5 3062.6823,-1157.5 3062.6823,-1163.5 3062.6823,-1163.5 3062.6823,-1714.5 3062.6823,-1714.5 3062.6823,-1720.5 3056.6823,-1726.5 3050.6823,-1726.5 3050.6823,-1726.5 2581.6823,-1726.5 2581.6823,-1726.5 2575.6823,-1726.5 2569.6823,-1720.5 2569.6823,-1714.5 2569.6823,-1714.5 2569.6823,-1163.5 2569.6823,-1163.5 2569.6823,-1157.5 2575.6823,-1151.5 2581.6823,-1151.5"/>
<text text-anchor="middle" x="2633.6823" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="2697.6823,-1151.5 2697.6823,-1726.5 "/>
<text text-anchor="middle" x="2708.1823" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2718.6823,-1151.5 2718.6823,-1726.5 "/>
<text text-anchor="middle" x="2880.1823" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="2718.6823,-1703.5 3041.6823,-1703.5 "/>
<text text-anchor="middle" x="2880.1823" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2718.6823,-1680.5 3041.6823,-1680.5 "/>
<text text-anchor="middle" x="2880.1823" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2718.6823,-1657.5 3041.6823,-1657.5 "/>
<text text-anchor="middle" x="2880.1823" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="2718.6823,-1634.5 3041.6823,-1634.5 "/>
<text text-anchor="middle" x="2880.1823" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="2718.6823,-1611.5 3041.6823,-1611.5 "/>
<text text-anchor="middle" x="2880.1823" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2718.6823,-1588.5 3041.6823,-1588.5 "/>
<text text-anchor="middle" x="2880.1823" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="2718.6823,-1565.5 3041.6823,-1565.5 "/>
<text text-anchor="middle" x="2880.1823" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2718.6823,-1542.5 3041.6823,-1542.5 "/>
<text text-anchor="middle" x="2880.1823" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2718.6823,-1519.5 3041.6823,-1519.5 "/>
<text text-anchor="middle" x="2880.1823" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2718.6823,-1496.5 3041.6823,-1496.5 "/>
<text text-anchor="middle" x="2880.1823" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2718.6823,-1473.5 3041.6823,-1473.5 "/>
<text text-anchor="middle" x="2880.1823" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2718.6823,-1450.5 3041.6823,-1450.5 "/>
<text text-anchor="middle" x="2880.1823" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2718.6823,-1427.5 3041.6823,-1427.5 "/>
<text text-anchor="middle" x="2880.1823" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="2718.6823,-1404.5 3041.6823,-1404.5 "/>
<text text-anchor="middle" x="2880.1823" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="2718.6823,-1381.5 3041.6823,-1381.5 "/>
<text text-anchor="middle" x="2880.1823" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="2718.6823,-1358.5 3041.6823,-1358.5 "/>
<text text-anchor="middle" x="2880.1823" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="2718.6823,-1335.5 3041.6823,-1335.5 "/>
<text text-anchor="middle" x="2880.1823" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="2718.6823,-1312.5 3041.6823,-1312.5 "/>
<text text-anchor="middle" x="2880.1823" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="2718.6823,-1289.5 3041.6823,-1289.5 "/>
<text text-anchor="middle" x="2880.1823" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2718.6823,-1266.5 3041.6823,-1266.5 "/>
<text text-anchor="middle" x="2880.1823" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="2718.6823,-1243.5 3041.6823,-1243.5 "/>
<text text-anchor="middle" x="2880.1823" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="2718.6823,-1220.5 3041.6823,-1220.5 "/>
<text text-anchor="middle" x="2880.1823" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="2718.6823,-1197.5 3041.6823,-1197.5 "/>
<text text-anchor="middle" x="2880.1823" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="2718.6823,-1174.5 3041.6823,-1174.5 "/>
<text text-anchor="middle" x="2880.1823" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="3041.6823,-1151.5 3041.6823,-1726.5 "/>
<text text-anchor="middle" x="3052.1823" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2569.669,-1156.3767C2566.8543,-1154.5446 2564.0252,-1152.7516 2561.1823,-1151 2295.8744,-987.5371 1932.8782,-922.1331 1718.5134,-896.6212"/>
<polygon fill="#000000" stroke="#000000" points="1718.7588,-893.1261 1708.4189,-895.4363 1717.9426,-900.0783 1718.7588,-893.1261"/>
<text text-anchor="middle" x="2577.6823" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- diagnosis -->
<g id="node4" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M446.1823,-662.5C446.1823,-662.5 820.1823,-662.5 820.1823,-662.5 826.1823,-662.5 832.1823,-668.5 832.1823,-674.5 832.1823,-674.5 832.1823,-1087.5 832.1823,-1087.5 832.1823,-1093.5 826.1823,-1099.5 820.1823,-1099.5 820.1823,-1099.5 446.1823,-1099.5 446.1823,-1099.5 440.1823,-1099.5 434.1823,-1093.5 434.1823,-1087.5 434.1823,-1087.5 434.1823,-674.5 434.1823,-674.5 434.1823,-668.5 440.1823,-662.5 446.1823,-662.5"/>
<text text-anchor="middle" x="476.1823" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="518.1823,-662.5 518.1823,-1099.5 "/>
<text text-anchor="middle" x="528.6823" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="539.1823,-662.5 539.1823,-1099.5 "/>
<text text-anchor="middle" x="675.1823" y="-1084.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="539.1823,-1076.5 811.1823,-1076.5 "/>
<text text-anchor="middle" x="675.1823" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="539.1823,-1053.5 811.1823,-1053.5 "/>
<text text-anchor="middle" x="675.1823" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="539.1823,-1030.5 811.1823,-1030.5 "/>
<text text-anchor="middle" x="675.1823" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="539.1823,-1007.5 811.1823,-1007.5 "/>
<text text-anchor="middle" x="675.1823" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="539.1823,-984.5 811.1823,-984.5 "/>
<text text-anchor="middle" x="675.1823" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="539.1823,-961.5 811.1823,-961.5 "/>
<text text-anchor="middle" x="675.1823" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="539.1823,-938.5 811.1823,-938.5 "/>
<text text-anchor="middle" x="675.1823" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="539.1823,-915.5 811.1823,-915.5 "/>
<text text-anchor="middle" x="675.1823" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="539.1823,-892.5 811.1823,-892.5 "/>
<text text-anchor="middle" x="675.1823" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="539.1823,-869.5 811.1823,-869.5 "/>
<text text-anchor="middle" x="675.1823" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="539.1823,-846.5 811.1823,-846.5 "/>
<text text-anchor="middle" x="675.1823" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="539.1823,-823.5 811.1823,-823.5 "/>
<text text-anchor="middle" x="675.1823" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="539.1823,-800.5 811.1823,-800.5 "/>
<text text-anchor="middle" x="675.1823" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="539.1823,-777.5 811.1823,-777.5 "/>
<text text-anchor="middle" x="675.1823" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="539.1823,-754.5 811.1823,-754.5 "/>
<text text-anchor="middle" x="675.1823" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="539.1823,-731.5 811.1823,-731.5 "/>
<text text-anchor="middle" x="675.1823" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="539.1823,-708.5 811.1823,-708.5 "/>
<text text-anchor="middle" x="675.1823" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="539.1823,-685.5 811.1823,-685.5 "/>
<text text-anchor="middle" x="675.1823" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="811.1823,-662.5 811.1823,-1099.5 "/>
<text text-anchor="middle" x="821.6823" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node11" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M718.1823,-495.5C718.1823,-495.5 1022.1823,-495.5 1022.1823,-495.5 1028.1823,-495.5 1034.1823,-501.5 1034.1823,-507.5 1034.1823,-507.5 1034.1823,-598.5 1034.1823,-598.5 1034.1823,-604.5 1028.1823,-610.5 1022.1823,-610.5 1022.1823,-610.5 718.1823,-610.5 718.1823,-610.5 712.1823,-610.5 706.1823,-604.5 706.1823,-598.5 706.1823,-598.5 706.1823,-507.5 706.1823,-507.5 706.1823,-501.5 712.1823,-495.5 718.1823,-495.5"/>
<text text-anchor="middle" x="754.1823" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="802.1823,-495.5 802.1823,-610.5 "/>
<text text-anchor="middle" x="812.6823" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="823.1823,-495.5 823.1823,-610.5 "/>
<text text-anchor="middle" x="918.1823" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="823.1823,-587.5 1013.1823,-587.5 "/>
<text text-anchor="middle" x="918.1823" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="823.1823,-564.5 1013.1823,-564.5 "/>
<text text-anchor="middle" x="918.1823" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="823.1823,-541.5 1013.1823,-541.5 "/>
<text text-anchor="middle" x="918.1823" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="823.1823,-518.5 1013.1823,-518.5 "/>
<text text-anchor="middle" x="918.1823" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1013.1823,-495.5 1013.1823,-610.5 "/>
<text text-anchor="middle" x="1023.6823" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M739.2557,-662.2675C747.4836,-650.6405 756.1327,-639.4566 765.1823,-629 768.5475,-625.1116 772.1485,-621.3119 775.9165,-617.6159"/>
<polygon fill="#000000" stroke="#000000" points="778.4531,-620.0353 783.3502,-610.6402 773.6631,-614.9308 778.4531,-620.0353"/>
<text text-anchor="middle" x="809.6823" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- pdx -->
<g id="node5" class="node">
<title>pdx</title>
<path fill="none" stroke="#000000" d="M949.6823,-1335.5C949.6823,-1335.5 1278.6823,-1335.5 1278.6823,-1335.5 1284.6823,-1335.5 1290.6823,-1341.5 1290.6823,-1347.5 1290.6823,-1347.5 1290.6823,-1530.5 1290.6823,-1530.5 1290.6823,-1536.5 1284.6823,-1542.5 1278.6823,-1542.5 1278.6823,-1542.5 949.6823,-1542.5 949.6823,-1542.5 943.6823,-1542.5 937.6823,-1536.5 937.6823,-1530.5 937.6823,-1530.5 937.6823,-1347.5 937.6823,-1347.5 937.6823,-1341.5 943.6823,-1335.5 949.6823,-1335.5"/>
<text text-anchor="middle" x="959.1823" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
<polyline fill="none" stroke="#000000" points="980.6823,-1335.5 980.6823,-1542.5 "/>
<text text-anchor="middle" x="991.1823" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1001.6823,-1335.5 1001.6823,-1542.5 "/>
<text text-anchor="middle" x="1135.6823" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">injection_type_and_site</text>
<polyline fill="none" stroke="#000000" points="1001.6823,-1519.5 1269.6823,-1519.5 "/>
<text text-anchor="middle" x="1135.6823" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_id</text>
<polyline fill="none" stroke="#000000" points="1001.6823,-1496.5 1269.6823,-1496.5 "/>
<text text-anchor="middle" x="1135.6823" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_type</text>
<polyline fill="none" stroke="#000000" points="1001.6823,-1473.5 1269.6823,-1473.5 "/>
<text text-anchor="middle" x="1135.6823" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">mouse_strain</text>
<polyline fill="none" stroke="#000000" points="1001.6823,-1450.5 1269.6823,-1450.5 "/>
<text text-anchor="middle" x="1135.6823" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">strain_immune_system_humanized</text>
<polyline fill="none" stroke="#000000" points="1001.6823,-1427.5 1269.6823,-1427.5 "/>
<text text-anchor="middle" x="1135.6823" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_characterization_method</text>
<polyline fill="none" stroke="#000000" points="1001.6823,-1404.5 1269.6823,-1404.5 "/>
<text text-anchor="middle" x="1135.6823" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_not_mus_or_ebv_origin</text>
<polyline fill="none" stroke="#000000" points="1001.6823,-1381.5 1269.6823,-1381.5 "/>
<text text-anchor="middle" x="1135.6823" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_preparation</text>
<polyline fill="none" stroke="#000000" points="1001.6823,-1358.5 1269.6823,-1358.5 "/>
<text text-anchor="middle" x="1135.6823" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_humanization</text>
<polyline fill="none" stroke="#000000" points="1269.6823,-1335.5 1269.6823,-1542.5 "/>
<text text-anchor="middle" x="1280.1823" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1170.7327,-1335.4336C1204.4925,-1278.1132 1250.4102,-1207.2988 1300.1823,-1151 1323.5884,-1124.5246 1336.3682,-1125.1605 1361.1823,-1100 1401.0159,-1059.6105 1441.228,-1010.9588 1473.3284,-969.78"/>
<polygon fill="#000000" stroke="#000000" points="1476.2727,-971.6948 1479.6378,-961.6486 1470.7422,-967.4036 1476.2727,-971.6948"/>
<text text-anchor="middle" x="1362.1823" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- synonym -->
<g id="node6" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M606.6823,-1416C606.6823,-1416 907.6823,-1416 907.6823,-1416 913.6823,-1416 919.6823,-1422 919.6823,-1428 919.6823,-1428 919.6823,-1450 919.6823,-1450 919.6823,-1456 913.6823,-1462 907.6823,-1462 907.6823,-1462 606.6823,-1462 606.6823,-1462 600.6823,-1462 594.6823,-1456 594.6823,-1450 594.6823,-1450 594.6823,-1428 594.6823,-1428 594.6823,-1422 600.6823,-1416 606.6823,-1416"/>
<text text-anchor="middle" x="634.6823" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="674.6823,-1416 674.6823,-1462 "/>
<text text-anchor="middle" x="685.1823" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="695.6823,-1416 695.6823,-1462 "/>
<text text-anchor="middle" x="797.1823" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="695.6823,-1439 898.6823,-1439 "/>
<text text-anchor="middle" x="797.1823" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="898.6823,-1416 898.6823,-1462 "/>
<text text-anchor="middle" x="909.1823" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge15" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M614.1856,-1415.9373C444.4133,-1380.3293 167.1987,-1294.5094 31.1823,-1100 -24.8056,-1019.9348 12.1823,-978.699 12.1823,-881 12.1823,-881 12.1823,-881 12.1823,-351.5 12.1823,-308.2808 10.3696,-288.255 42.1823,-259 129.4064,-178.7885 437.9915,-138.0173 652.7345,-118.8953"/>
<polygon fill="#000000" stroke="#000000" points="653.2339,-122.3649 662.8882,-118.001 652.6197,-115.3919 653.2339,-122.3649"/>
<text text-anchor="middle" x="54.6823" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M764.5341,-1415.8796C781.4734,-1361.4772 823.1743,-1220.8432 841.1823,-1100 866.6847,-928.8659 870.5856,-724.6914 870.7084,-620.8816"/>
<polygon fill="#000000" stroke="#000000" points="874.2083,-620.8501 870.7087,-610.8499 867.2083,-620.8498 874.2083,-620.8501"/>
<text text-anchor="middle" x="913.6823" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M763.2875,-1415.7643C779.4262,-1359.428 828.9491,-1215.4647 928.1823,-1151 948.4944,-1137.8047 1339.958,-1111.6715 1361.1823,-1100 1415.2397,-1070.2732 1459.1818,-1016.8093 1489.8818,-970.1497"/>
<polygon fill="#000000" stroke="#000000" points="1492.9686,-971.8216 1495.4595,-961.5238 1487.0904,-968.0207 1492.9686,-971.8216"/>
<text text-anchor="middle" x="1259.6823" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- publication -->
<g id="node7" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M63.1823,-333.5C63.1823,-333.5 273.1823,-333.5 273.1823,-333.5 279.1823,-333.5 285.1823,-339.5 285.1823,-345.5 285.1823,-345.5 285.1823,-357.5 285.1823,-357.5 285.1823,-363.5 279.1823,-369.5 273.1823,-369.5 273.1823,-369.5 63.1823,-369.5 63.1823,-369.5 57.1823,-369.5 51.1823,-363.5 51.1823,-357.5 51.1823,-357.5 51.1823,-345.5 51.1823,-345.5 51.1823,-339.5 57.1823,-333.5 63.1823,-333.5"/>
<text text-anchor="middle" x="99.6823" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="148.1823,-333.5 148.1823,-369.5 "/>
<text text-anchor="middle" x="158.6823" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="169.1823,-333.5 169.1823,-369.5 "/>
<text text-anchor="middle" x="216.6823" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="264.1823,-333.5 264.1823,-369.5 "/>
<text text-anchor="middle" x="274.6823" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge11" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M166.6667,-333.1429C165.4945,-305.6675 167.7245,-254.0835 197.1823,-226 261.6469,-164.543 481.6534,-133.2196 652.7764,-117.8172"/>
<polygon fill="#000000" stroke="#000000" points="653.2913,-121.2853 662.943,-116.9155 652.6729,-114.3127 653.2913,-121.2853"/>
<text text-anchor="middle" x="248.1823" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- study_arm -->
<g id="node8" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M721.6823,-317C721.6823,-317 1018.6823,-317 1018.6823,-317 1024.6823,-317 1030.6823,-323 1030.6823,-329 1030.6823,-329 1030.6823,-374 1030.6823,-374 1030.6823,-380 1024.6823,-386 1018.6823,-386 1018.6823,-386 721.6823,-386 721.6823,-386 715.6823,-386 709.6823,-380 709.6823,-374 709.6823,-374 709.6823,-329 709.6823,-329 709.6823,-323 715.6823,-317 721.6823,-317"/>
<text text-anchor="middle" x="755.6823" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="801.6823,-317 801.6823,-386 "/>
<text text-anchor="middle" x="812.1823" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="822.6823,-317 822.6823,-386 "/>
<text text-anchor="middle" x="916.1823" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="822.6823,-363 1009.6823,-363 "/>
<text text-anchor="middle" x="916.1823" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="822.6823,-340 1009.6823,-340 "/>
<text text-anchor="middle" x="916.1823" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="1009.6823,-317 1009.6823,-386 "/>
<text text-anchor="middle" x="1020.1823" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge4" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M870.1823,-316.8256C870.1823,-290.8629 870.1823,-253.7725 870.1823,-217.8091"/>
<polygon fill="#000000" stroke="#000000" points="873.6824,-217.7056 870.1823,-207.7056 866.6824,-217.7056 873.6824,-217.7056"/>
<text text-anchor="middle" x="918.6823" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- methylation_array_file -->
<g id="node9" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M1320.6823,-1324C1320.6823,-1324 1687.6823,-1324 1687.6823,-1324 1693.6823,-1324 1699.6823,-1330 1699.6823,-1336 1699.6823,-1336 1699.6823,-1542 1699.6823,-1542 1699.6823,-1548 1693.6823,-1554 1687.6823,-1554 1687.6823,-1554 1320.6823,-1554 1320.6823,-1554 1314.6823,-1554 1308.6823,-1548 1308.6823,-1542 1308.6823,-1542 1308.6823,-1336 1308.6823,-1336 1308.6823,-1330 1314.6823,-1324 1320.6823,-1324"/>
<text text-anchor="middle" x="1397.6823" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="1486.6823,-1324 1486.6823,-1554 "/>
<text text-anchor="middle" x="1497.1823" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1507.6823,-1324 1507.6823,-1554 "/>
<text text-anchor="middle" x="1593.1823" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1507.6823,-1531 1678.6823,-1531 "/>
<text text-anchor="middle" x="1593.1823" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1507.6823,-1508 1678.6823,-1508 "/>
<text text-anchor="middle" x="1593.1823" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1507.6823,-1485 1678.6823,-1485 "/>
<text text-anchor="middle" x="1593.1823" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1507.6823,-1462 1678.6823,-1462 "/>
<text text-anchor="middle" x="1593.1823" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1507.6823,-1439 1678.6823,-1439 "/>
<text text-anchor="middle" x="1593.1823" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1507.6823,-1416 1678.6823,-1416 "/>
<text text-anchor="middle" x="1593.1823" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1507.6823,-1393 1678.6823,-1393 "/>
<text text-anchor="middle" x="1593.1823" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1507.6823,-1370 1678.6823,-1370 "/>
<text text-anchor="middle" x="1593.1823" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="1507.6823,-1347 1678.6823,-1347 "/>
<text text-anchor="middle" x="1593.1823" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="1678.6823,-1324 1678.6823,-1554 "/>
<text text-anchor="middle" x="1689.1823" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1511.4131,-1323.7205C1517.9507,-1219.4927 1527.4472,-1068.0921 1533.4674,-972.1115"/>
<polygon fill="#000000" stroke="#000000" points="1536.9784,-972.0449 1534.1114,-961.8453 1529.9921,-971.6066 1536.9784,-972.0449"/>
<text text-anchor="middle" x="1614.6823" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study_admin -->
<g id="node10" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M353.1823,-259.5C353.1823,-259.5 679.1823,-259.5 679.1823,-259.5 685.1823,-259.5 691.1823,-265.5 691.1823,-271.5 691.1823,-271.5 691.1823,-431.5 691.1823,-431.5 691.1823,-437.5 685.1823,-443.5 679.1823,-443.5 679.1823,-443.5 353.1823,-443.5 353.1823,-443.5 347.1823,-443.5 341.1823,-437.5 341.1823,-431.5 341.1823,-431.5 341.1823,-271.5 341.1823,-271.5 341.1823,-265.5 347.1823,-259.5 353.1823,-259.5"/>
<text text-anchor="middle" x="395.1823" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="449.1823,-259.5 449.1823,-443.5 "/>
<text text-anchor="middle" x="459.6823" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="470.1823,-259.5 470.1823,-443.5 "/>
<text text-anchor="middle" x="570.1823" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="470.1823,-420.5 670.1823,-420.5 "/>
<text text-anchor="middle" x="570.1823" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="470.1823,-397.5 670.1823,-397.5 "/>
<text text-anchor="middle" x="570.1823" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="470.1823,-374.5 670.1823,-374.5 "/>
<text text-anchor="middle" x="570.1823" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="470.1823,-351.5 670.1823,-351.5 "/>
<text text-anchor="middle" x="570.1823" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="470.1823,-328.5 670.1823,-328.5 "/>
<text text-anchor="middle" x="570.1823" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="470.1823,-305.5 670.1823,-305.5 "/>
<text text-anchor="middle" x="570.1823" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="470.1823,-282.5 670.1823,-282.5 "/>
<text text-anchor="middle" x="570.1823" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="670.1823,-259.5 670.1823,-443.5 "/>
<text text-anchor="middle" x="680.6823" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge6" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M647.9989,-259.3401C669.3516,-244.4113 691.6446,-228.8251 713.5177,-213.5325"/>
<polygon fill="#000000" stroke="#000000" points="715.6873,-216.2862 721.8774,-207.6878 711.6763,-210.5493 715.6873,-216.2862"/>
<text text-anchor="middle" x="749.6823" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge20" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M993.0533,-495.4352C1011.5815,-481.2787 1028.1555,-464.2333 1039.1823,-444 1078.5283,-371.8031 1072.2801,-334.2664 1039.1823,-259 1032.417,-243.6153 1023.2874,-229.0896 1012.7572,-215.5581"/>
<polygon fill="#000000" stroke="#000000" points="1015.4144,-213.2779 1006.4026,-207.7068 1009.9733,-217.6818 1015.4144,-213.2779"/>
<text text-anchor="middle" x="1117.6823" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge19" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M870.1823,-495.2582C870.1823,-463.875 870.1823,-425.6377 870.1823,-396.4898"/>
<polygon fill="#000000" stroke="#000000" points="873.6824,-396.1919 870.1823,-386.1919 866.6824,-396.192 873.6824,-396.1919"/>
<text text-anchor="middle" x="920.6823" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge8" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1473.9729,-800.2811C1390.7148,-695.9059 1253.2142,-518.6787 1218.1823,-444 1182.1997,-367.2946 1224.8064,-325.4017 1172.1823,-259 1148.9135,-229.6391 1118.579,-205.3023 1086.1226,-185.3049"/>
<polygon fill="#000000" stroke="#000000" points="1087.7484,-182.1986 1077.3742,-180.0474 1084.1426,-188.1985 1087.7484,-182.1986"/>
<text text-anchor="middle" x="1271.6823" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1496.4536,-800.4013C1465.7978,-751.3423 1419.6316,-692.4362 1361.1823,-662 1311.7796,-636.2746 1163.9678,-661.7794 1111.1823,-644 1099.6167,-640.1044 1099.1357,-634.3816 1088.1823,-629 1074.0317,-622.0476 1059.0827,-615.4373 1043.9147,-609.2283"/>
<polygon fill="#000000" stroke="#000000" points="1045.031,-605.9047 1034.4475,-605.4146 1042.4154,-612.3977 1045.031,-605.9047"/>
<text text-anchor="middle" x="1147.6823" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- clinical_measure_file -->
<g id="node13" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M52.1823,-754.5C52.1823,-754.5 404.1823,-754.5 404.1823,-754.5 410.1823,-754.5 416.1823,-760.5 416.1823,-766.5 416.1823,-766.5 416.1823,-995.5 416.1823,-995.5 416.1823,-1001.5 410.1823,-1007.5 404.1823,-1007.5 404.1823,-1007.5 52.1823,-1007.5 52.1823,-1007.5 46.1823,-1007.5 40.1823,-1001.5 40.1823,-995.5 40.1823,-995.5 40.1823,-766.5 40.1823,-766.5 40.1823,-760.5 46.1823,-754.5 52.1823,-754.5"/>
<text text-anchor="middle" x="123.6823" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="207.1823,-754.5 207.1823,-1007.5 "/>
<text text-anchor="middle" x="217.6823" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="228.1823,-754.5 228.1823,-1007.5 "/>
<text text-anchor="middle" x="311.6823" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="228.1823,-984.5 395.1823,-984.5 "/>
<text text-anchor="middle" x="311.6823" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="228.1823,-961.5 395.1823,-961.5 "/>
<text text-anchor="middle" x="311.6823" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="228.1823,-938.5 395.1823,-938.5 "/>
<text text-anchor="middle" x="311.6823" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="228.1823,-915.5 395.1823,-915.5 "/>
<text text-anchor="middle" x="311.6823" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="228.1823,-892.5 395.1823,-892.5 "/>
<text text-anchor="middle" x="311.6823" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="228.1823,-869.5 395.1823,-869.5 "/>
<text text-anchor="middle" x="311.6823" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="228.1823,-846.5 395.1823,-846.5 "/>
<text text-anchor="middle" x="311.6823" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="228.1823,-823.5 395.1823,-823.5 "/>
<text text-anchor="middle" x="311.6823" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="228.1823,-800.5 395.1823,-800.5 "/>
<text text-anchor="middle" x="311.6823" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="228.1823,-777.5 395.1823,-777.5 "/>
<text text-anchor="middle" x="311.6823" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="395.1823,-754.5 395.1823,-1007.5 "/>
<text text-anchor="middle" x="405.6823" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge3" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M247.6668,-754.1306C275.4319,-574.9271 323.9472,-268.2397 332.1823,-259 375.8716,-209.9817 523.293,-169.5312 652.7876,-142.2581"/>
<polygon fill="#000000" stroke="#000000" points="653.796,-145.6231 662.8698,-140.1534 652.3656,-138.7708 653.796,-145.6231"/>
<text text-anchor="middle" x="380.1823" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M327.1853,-754.2355C356.4705,-721.6391 390.1403,-688.365 425.1823,-662 452.026,-641.8033 461.3518,-639.7383 493.1823,-629 558.0218,-607.1258 631.3693,-590.585 696.0203,-578.6132"/>
<polygon fill="#000000" stroke="#000000" points="696.6985,-582.0473 705.9057,-576.8055 695.4392,-575.1615 696.6985,-582.0473"/>
<text text-anchor="middle" x="622.6823" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- study_personnel -->
<g id="node14" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M1238.6823,-294C1238.6823,-294 1545.6823,-294 1545.6823,-294 1551.6823,-294 1557.6823,-300 1557.6823,-306 1557.6823,-306 1557.6823,-397 1557.6823,-397 1557.6823,-403 1551.6823,-409 1545.6823,-409 1545.6823,-409 1238.6823,-409 1238.6823,-409 1232.6823,-409 1226.6823,-403 1226.6823,-397 1226.6823,-397 1226.6823,-306 1226.6823,-306 1226.6823,-300 1232.6823,-294 1238.6823,-294"/>
<text text-anchor="middle" x="1293.6823" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="1360.6823,-294 1360.6823,-409 "/>
<text text-anchor="middle" x="1371.1823" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1381.6823,-294 1381.6823,-409 "/>
<text text-anchor="middle" x="1459.1823" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="1381.6823,-386 1536.6823,-386 "/>
<text text-anchor="middle" x="1459.1823" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="1381.6823,-363 1536.6823,-363 "/>
<text text-anchor="middle" x="1459.1823" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="1381.6823,-340 1536.6823,-340 "/>
<text text-anchor="middle" x="1459.1823" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="1381.6823,-317 1536.6823,-317 "/>
<text text-anchor="middle" x="1459.1823" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="1536.6823,-294 1536.6823,-409 "/>
<text text-anchor="middle" x="1547.1823" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1318.8041,-293.6938C1287.2067,-270.5936 1249.0953,-245.0186 1212.1823,-226 1172.8478,-205.7337 1129.3724,-187.4092 1086.9841,-171.4852"/>
<polygon fill="#000000" stroke="#000000" points="1087.9802,-168.1215 1077.3874,-167.9136 1085.5386,-174.6819 1087.9802,-168.1215"/>
<text text-anchor="middle" x="1307.6823" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- study_funding -->
<g id="node15" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M1587.6823,-317C1587.6823,-317 1966.6823,-317 1966.6823,-317 1972.6823,-317 1978.6823,-323 1978.6823,-329 1978.6823,-329 1978.6823,-374 1978.6823,-374 1978.6823,-380 1972.6823,-386 1966.6823,-386 1966.6823,-386 1587.6823,-386 1587.6823,-386 1581.6823,-386 1575.6823,-380 1575.6823,-374 1575.6823,-374 1575.6823,-329 1575.6823,-329 1575.6823,-323 1581.6823,-317 1587.6823,-317"/>
<text text-anchor="middle" x="1635.1823" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="1694.6823,-317 1694.6823,-386 "/>
<text text-anchor="middle" x="1705.1823" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1715.6823,-317 1715.6823,-386 "/>
<text text-anchor="middle" x="1836.6823" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="1715.6823,-363 1957.6823,-363 "/>
<text text-anchor="middle" x="1836.6823" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="1715.6823,-340 1957.6823,-340 "/>
<text text-anchor="middle" x="1836.6823" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="1957.6823,-317 1957.6823,-386 "/>
<text text-anchor="middle" x="1968.1823" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge16" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1708.0495,-316.942C1667.7269,-297.8333 1615.4477,-274.8268 1567.1823,-259 1409.5898,-207.3236 1226.3492,-167.3264 1087.311,-140.9151"/>
<polygon fill="#000000" stroke="#000000" points="1087.8538,-137.4558 1077.3776,-139.037 1086.5533,-144.3339 1087.8538,-137.4558"/>
<text text-anchor="middle" x="1555.1823" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- imaging_file -->
<g id="node16" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M1730.1823,-1278C1730.1823,-1278 2064.1823,-1278 2064.1823,-1278 2070.1823,-1278 2076.1823,-1284 2076.1823,-1290 2076.1823,-1290 2076.1823,-1588 2076.1823,-1588 2076.1823,-1594 2070.1823,-1600 2064.1823,-1600 2064.1823,-1600 1730.1823,-1600 1730.1823,-1600 1724.1823,-1600 1718.1823,-1594 1718.1823,-1588 1718.1823,-1588 1718.1823,-1290 1718.1823,-1290 1718.1823,-1284 1724.1823,-1278 1730.1823,-1278"/>
<text text-anchor="middle" x="1770.1823" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="1822.1823,-1278 1822.1823,-1600 "/>
<text text-anchor="middle" x="1832.6823" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1843.1823,-1278 1843.1823,-1600 "/>
<text text-anchor="middle" x="1949.1823" y="-1584.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1843.1823,-1577 2055.1823,-1577 "/>
<text text-anchor="middle" x="1949.1823" y="-1561.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1843.1823,-1554 2055.1823,-1554 "/>
<text text-anchor="middle" x="1949.1823" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1843.1823,-1531 2055.1823,-1531 "/>
<text text-anchor="middle" x="1949.1823" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1843.1823,-1508 2055.1823,-1508 "/>
<text text-anchor="middle" x="1949.1823" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1843.1823,-1485 2055.1823,-1485 "/>
<text text-anchor="middle" x="1949.1823" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1843.1823,-1462 2055.1823,-1462 "/>
<text text-anchor="middle" x="1949.1823" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1843.1823,-1439 2055.1823,-1439 "/>
<text text-anchor="middle" x="1949.1823" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1843.1823,-1416 2055.1823,-1416 "/>
<text text-anchor="middle" x="1949.1823" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1843.1823,-1393 2055.1823,-1393 "/>
<text text-anchor="middle" x="1949.1823" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="1843.1823,-1370 2055.1823,-1370 "/>
<text text-anchor="middle" x="1949.1823" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="1843.1823,-1347 2055.1823,-1347 "/>
<text text-anchor="middle" x="1949.1823" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="1843.1823,-1324 2055.1823,-1324 "/>
<text text-anchor="middle" x="1949.1823" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1843.1823,-1301 2055.1823,-1301 "/>
<text text-anchor="middle" x="1949.1823" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="2055.1823,-1278 2055.1823,-1600 "/>
<text text-anchor="middle" x="2065.6823" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1807.4659,-1277.9478C1777.566,-1226.2224 1743.3927,-1169.106 1710.1823,-1118 1677.584,-1067.8358 1638.7381,-1013.6039 1606.3152,-969.6934"/>
<polygon fill="#000000" stroke="#000000" points="1609.101,-967.574 1600.3389,-961.6178 1603.4742,-971.7381 1609.101,-967.574"/>
<text text-anchor="middle" x="1769.6823" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- therapeutic_procedure -->
<g id="node17" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M983.6823,-823.5C983.6823,-823.5 1340.6823,-823.5 1340.6823,-823.5 1346.6823,-823.5 1352.6823,-829.5 1352.6823,-835.5 1352.6823,-835.5 1352.6823,-926.5 1352.6823,-926.5 1352.6823,-932.5 1346.6823,-938.5 1340.6823,-938.5 1340.6823,-938.5 983.6823,-938.5 983.6823,-938.5 977.6823,-938.5 971.6823,-932.5 971.6823,-926.5 971.6823,-926.5 971.6823,-835.5 971.6823,-835.5 971.6823,-829.5 977.6823,-823.5 983.6823,-823.5"/>
<text text-anchor="middle" x="1062.1823" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="1152.6823,-823.5 1152.6823,-938.5 "/>
<text text-anchor="middle" x="1163.1823" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1173.6823,-823.5 1173.6823,-938.5 "/>
<text text-anchor="middle" x="1252.6823" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="1173.6823,-915.5 1331.6823,-915.5 "/>
<text text-anchor="middle" x="1252.6823" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="1173.6823,-892.5 1331.6823,-892.5 "/>
<text text-anchor="middle" x="1252.6823" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1173.6823,-869.5 1331.6823,-869.5 "/>
<text text-anchor="middle" x="1252.6823" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="1173.6823,-846.5 1331.6823,-846.5 "/>
<text text-anchor="middle" x="1252.6823" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1331.6823,-823.5 1331.6823,-938.5 "/>
<text text-anchor="middle" x="1342.1823" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1121.5955,-823.4837C1084.0871,-774.226 1024.1604,-704.6804 957.1823,-662 935.4917,-648.1781 920.5669,-661.9871 902.1823,-644 895.2525,-637.22 889.8204,-628.8529 885.5631,-619.9632"/>
<polygon fill="#000000" stroke="#000000" points="888.6893,-618.3721 881.5382,-610.5547 882.2535,-621.1254 888.6893,-618.3721"/>
<text text-anchor="middle" x="995.1823" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
</g>
</svg>
</div>
