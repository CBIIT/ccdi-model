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
<svg width="3301pt" height="1804pt"
 viewBox="0.00 0.00 3301.06 1804.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1800)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1800 3297.0588,-1800 3297.0588,4 -4,4"/>
<!-- imaging_file -->
<g id="node1" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M2947.0588,-1347C2947.0588,-1347 3281.0588,-1347 3281.0588,-1347 3287.0588,-1347 3293.0588,-1353 3293.0588,-1359 3293.0588,-1359 3293.0588,-1657 3293.0588,-1657 3293.0588,-1663 3287.0588,-1669 3281.0588,-1669 3281.0588,-1669 2947.0588,-1669 2947.0588,-1669 2941.0588,-1669 2935.0588,-1663 2935.0588,-1657 2935.0588,-1657 2935.0588,-1359 2935.0588,-1359 2935.0588,-1353 2941.0588,-1347 2947.0588,-1347"/>
<text text-anchor="middle" x="2987.0588" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="3039.0588,-1347 3039.0588,-1669 "/>
<text text-anchor="middle" x="3049.5588" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3060.0588,-1347 3060.0588,-1669 "/>
<text text-anchor="middle" x="3166.0588" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="3060.0588,-1646 3272.0588,-1646 "/>
<text text-anchor="middle" x="3166.0588" y="-1630.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="3060.0588,-1623 3272.0588,-1623 "/>
<text text-anchor="middle" x="3166.0588" y="-1607.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="3060.0588,-1600 3272.0588,-1600 "/>
<text text-anchor="middle" x="3166.0588" y="-1584.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="3060.0588,-1577 3272.0588,-1577 "/>
<text text-anchor="middle" x="3166.0588" y="-1561.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="3060.0588,-1554 3272.0588,-1554 "/>
<text text-anchor="middle" x="3166.0588" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="3060.0588,-1531 3272.0588,-1531 "/>
<text text-anchor="middle" x="3166.0588" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="3060.0588,-1508 3272.0588,-1508 "/>
<text text-anchor="middle" x="3166.0588" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="3060.0588,-1485 3272.0588,-1485 "/>
<text text-anchor="middle" x="3166.0588" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="3060.0588,-1462 3272.0588,-1462 "/>
<text text-anchor="middle" x="3166.0588" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="3060.0588,-1439 3272.0588,-1439 "/>
<text text-anchor="middle" x="3166.0588" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="3060.0588,-1416 3272.0588,-1416 "/>
<text text-anchor="middle" x="3166.0588" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="3060.0588,-1393 3272.0588,-1393 "/>
<text text-anchor="middle" x="3166.0588" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="3060.0588,-1370 3272.0588,-1370 "/>
<text text-anchor="middle" x="3166.0588" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="3272.0588,-1347 3272.0588,-1669 "/>
<text text-anchor="middle" x="3282.5588" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node9" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1663.0588,-858C1663.0588,-858 1977.0588,-858 1977.0588,-858 1983.0588,-858 1989.0588,-864 1989.0588,-870 1989.0588,-870 1989.0588,-1007 1989.0588,-1007 1989.0588,-1013 1983.0588,-1019 1977.0588,-1019 1977.0588,-1019 1663.0588,-1019 1663.0588,-1019 1657.0588,-1019 1651.0588,-1013 1651.0588,-1007 1651.0588,-1007 1651.0588,-870 1651.0588,-870 1651.0588,-864 1657.0588,-858 1663.0588,-858"/>
<text text-anchor="middle" x="1685.0588" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1719.0588,-858 1719.0588,-1019 "/>
<text text-anchor="middle" x="1729.5588" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1740.0588,-858 1740.0588,-1019 "/>
<text text-anchor="middle" x="1854.0588" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="1740.0588,-996 1968.0588,-996 "/>
<text text-anchor="middle" x="1854.0588" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1740.0588,-973 1968.0588,-973 "/>
<text text-anchor="middle" x="1854.0588" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1740.0588,-950 1968.0588,-950 "/>
<text text-anchor="middle" x="1854.0588" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1740.0588,-927 1968.0588,-927 "/>
<text text-anchor="middle" x="1854.0588" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1740.0588,-904 1968.0588,-904 "/>
<text text-anchor="middle" x="1854.0588" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1740.0588,-881 1968.0588,-881 "/>
<text text-anchor="middle" x="1854.0588" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="1968.0588,-858 1968.0588,-1019 "/>
<text text-anchor="middle" x="1978.5588" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3038.0995,-1346.8243C3008.9867,-1299.9013 2971.5906,-1252.564 2926.0588,-1220 2778.0091,-1114.1159 2272.7854,-1015.2204 1999.3284,-967.8213"/>
<polygon fill="#000000" stroke="#000000" points="1999.7477,-964.3419 1989.2977,-966.0877 1998.5555,-971.2397 1999.7477,-964.3419"/>
<text text-anchor="middle" x="2935.5588" y="-1190.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- study_funding -->
<g id="node2" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M459.5588,-363C459.5588,-363 838.5588,-363 838.5588,-363 844.5588,-363 850.5588,-369 850.5588,-375 850.5588,-375 850.5588,-420 850.5588,-420 850.5588,-426 844.5588,-432 838.5588,-432 838.5588,-432 459.5588,-432 459.5588,-432 453.5588,-432 447.5588,-426 447.5588,-420 447.5588,-420 447.5588,-375 447.5588,-375 447.5588,-369 453.5588,-363 459.5588,-363"/>
<text text-anchor="middle" x="507.0588" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="566.5588,-363 566.5588,-432 "/>
<text text-anchor="middle" x="577.0588" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="587.5588,-363 587.5588,-432 "/>
<text text-anchor="middle" x="708.5588" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="587.5588,-409 829.5588,-409 "/>
<text text-anchor="middle" x="708.5588" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="587.5588,-386 829.5588,-386 "/>
<text text-anchor="middle" x="708.5588" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="829.5588,-363 829.5588,-432 "/>
<text text-anchor="middle" x="840.0588" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node15" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M791.0588,-.5C791.0588,-.5 1181.0588,-.5 1181.0588,-.5 1187.0588,-.5 1193.0588,-6.5 1193.0588,-12.5 1193.0588,-12.5 1193.0588,-241.5 1193.0588,-241.5 1193.0588,-247.5 1187.0588,-253.5 1181.0588,-253.5 1181.0588,-253.5 791.0588,-253.5 791.0588,-253.5 785.0588,-253.5 779.0588,-247.5 779.0588,-241.5 779.0588,-241.5 779.0588,-12.5 779.0588,-12.5 779.0588,-6.5 785.0588,-.5 791.0588,-.5"/>
<text text-anchor="middle" x="807.0588" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="835.0588,-.5 835.0588,-253.5 "/>
<text text-anchor="middle" x="845.5588" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="856.0588,-.5 856.0588,-253.5 "/>
<text text-anchor="middle" x="1014.0588" y="-238.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="856.0588,-230.5 1172.0588,-230.5 "/>
<text text-anchor="middle" x="1014.0588" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_shorthand</text>
<polyline fill="none" stroke="#000000" points="856.0588,-207.5 1172.0588,-207.5 "/>
<text text-anchor="middle" x="1014.0588" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="856.0588,-184.5 1172.0588,-184.5 "/>
<text text-anchor="middle" x="1014.0588" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="856.0588,-161.5 1172.0588,-161.5 "/>
<text text-anchor="middle" x="1014.0588" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="856.0588,-138.5 1172.0588,-138.5 "/>
<text text-anchor="middle" x="1014.0588" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="856.0588,-115.5 1172.0588,-115.5 "/>
<text text-anchor="middle" x="1014.0588" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="856.0588,-92.5 1172.0588,-92.5 "/>
<text text-anchor="middle" x="1014.0588" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="856.0588,-69.5 1172.0588,-69.5 "/>
<text text-anchor="middle" x="1014.0588" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="856.0588,-46.5 1172.0588,-46.5 "/>
<text text-anchor="middle" x="1014.0588" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="856.0588,-23.5 1172.0588,-23.5 "/>
<text text-anchor="middle" x="1014.0588" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="1172.0588,-.5 1172.0588,-253.5 "/>
<text text-anchor="middle" x="1182.5588" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge4" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M692.0824,-362.9662C725.0272,-336.5224 772.7358,-298.2281 820.1686,-260.1552"/>
<polygon fill="#000000" stroke="#000000" points="822.4776,-262.7899 828.0852,-253.8007 818.0958,-257.3309 822.4776,-262.7899"/>
<text text-anchor="middle" x="860.0588" y="-275.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- diagnosis -->
<g id="node3" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M449.0588,-708.5C449.0588,-708.5 823.0588,-708.5 823.0588,-708.5 829.0588,-708.5 835.0588,-714.5 835.0588,-720.5 835.0588,-720.5 835.0588,-1156.5 835.0588,-1156.5 835.0588,-1162.5 829.0588,-1168.5 823.0588,-1168.5 823.0588,-1168.5 449.0588,-1168.5 449.0588,-1168.5 443.0588,-1168.5 437.0588,-1162.5 437.0588,-1156.5 437.0588,-1156.5 437.0588,-720.5 437.0588,-720.5 437.0588,-714.5 443.0588,-708.5 449.0588,-708.5"/>
<text text-anchor="middle" x="479.0588" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="521.0588,-708.5 521.0588,-1168.5 "/>
<text text-anchor="middle" x="531.5588" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="542.0588,-708.5 542.0588,-1168.5 "/>
<text text-anchor="middle" x="678.0588" y="-1153.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="542.0588,-1145.5 814.0588,-1145.5 "/>
<text text-anchor="middle" x="678.0588" y="-1130.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="542.0588,-1122.5 814.0588,-1122.5 "/>
<text text-anchor="middle" x="678.0588" y="-1107.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="542.0588,-1099.5 814.0588,-1099.5 "/>
<text text-anchor="middle" x="678.0588" y="-1084.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="542.0588,-1076.5 814.0588,-1076.5 "/>
<text text-anchor="middle" x="678.0588" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="542.0588,-1053.5 814.0588,-1053.5 "/>
<text text-anchor="middle" x="678.0588" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="542.0588,-1030.5 814.0588,-1030.5 "/>
<text text-anchor="middle" x="678.0588" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="542.0588,-1007.5 814.0588,-1007.5 "/>
<text text-anchor="middle" x="678.0588" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="542.0588,-984.5 814.0588,-984.5 "/>
<text text-anchor="middle" x="678.0588" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="542.0588,-961.5 814.0588,-961.5 "/>
<text text-anchor="middle" x="678.0588" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="542.0588,-938.5 814.0588,-938.5 "/>
<text text-anchor="middle" x="678.0588" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="542.0588,-915.5 814.0588,-915.5 "/>
<text text-anchor="middle" x="678.0588" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="542.0588,-892.5 814.0588,-892.5 "/>
<text text-anchor="middle" x="678.0588" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="542.0588,-869.5 814.0588,-869.5 "/>
<text text-anchor="middle" x="678.0588" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="542.0588,-846.5 814.0588,-846.5 "/>
<text text-anchor="middle" x="678.0588" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="542.0588,-823.5 814.0588,-823.5 "/>
<text text-anchor="middle" x="678.0588" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="542.0588,-800.5 814.0588,-800.5 "/>
<text text-anchor="middle" x="678.0588" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="542.0588,-777.5 814.0588,-777.5 "/>
<text text-anchor="middle" x="678.0588" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="542.0588,-754.5 814.0588,-754.5 "/>
<text text-anchor="middle" x="678.0588" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="542.0588,-731.5 814.0588,-731.5 "/>
<text text-anchor="middle" x="678.0588" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="814.0588,-708.5 814.0588,-1168.5 "/>
<text text-anchor="middle" x="824.5588" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node13" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M892.0588,-541.5C892.0588,-541.5 1196.0588,-541.5 1196.0588,-541.5 1202.0588,-541.5 1208.0588,-547.5 1208.0588,-553.5 1208.0588,-553.5 1208.0588,-644.5 1208.0588,-644.5 1208.0588,-650.5 1202.0588,-656.5 1196.0588,-656.5 1196.0588,-656.5 892.0588,-656.5 892.0588,-656.5 886.0588,-656.5 880.0588,-650.5 880.0588,-644.5 880.0588,-644.5 880.0588,-553.5 880.0588,-553.5 880.0588,-547.5 886.0588,-541.5 892.0588,-541.5"/>
<text text-anchor="middle" x="928.0588" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="976.0588,-541.5 976.0588,-656.5 "/>
<text text-anchor="middle" x="986.5588" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="997.0588,-541.5 997.0588,-656.5 "/>
<text text-anchor="middle" x="1092.0588" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="997.0588,-633.5 1187.0588,-633.5 "/>
<text text-anchor="middle" x="1092.0588" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="997.0588,-610.5 1187.0588,-610.5 "/>
<text text-anchor="middle" x="1092.0588" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="997.0588,-587.5 1187.0588,-587.5 "/>
<text text-anchor="middle" x="1092.0588" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="997.0588,-564.5 1187.0588,-564.5 "/>
<text text-anchor="middle" x="1092.0588" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1187.0588,-541.5 1187.0588,-656.5 "/>
<text text-anchor="middle" x="1197.5588" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M835.1925,-715.1394C838.1402,-712.7178 841.0962,-710.3366 844.0588,-708 865.4205,-691.1514 889.7459,-675.4861 913.8989,-661.5851"/>
<polygon fill="#000000" stroke="#000000" points="915.813,-664.5232 922.7838,-656.5445 912.3589,-658.4348 915.813,-664.5232"/>
<text text-anchor="middle" x="934.5588" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- publication -->
<g id="node4" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M881.0588,-379.5C881.0588,-379.5 1091.0588,-379.5 1091.0588,-379.5 1097.0588,-379.5 1103.0588,-385.5 1103.0588,-391.5 1103.0588,-391.5 1103.0588,-403.5 1103.0588,-403.5 1103.0588,-409.5 1097.0588,-415.5 1091.0588,-415.5 1091.0588,-415.5 881.0588,-415.5 881.0588,-415.5 875.0588,-415.5 869.0588,-409.5 869.0588,-403.5 869.0588,-403.5 869.0588,-391.5 869.0588,-391.5 869.0588,-385.5 875.0588,-379.5 881.0588,-379.5"/>
<text text-anchor="middle" x="917.5588" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="966.0588,-379.5 966.0588,-415.5 "/>
<text text-anchor="middle" x="976.5588" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="987.0588,-379.5 987.0588,-415.5 "/>
<text text-anchor="middle" x="1034.5588" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="1082.0588,-379.5 1082.0588,-415.5 "/>
<text text-anchor="middle" x="1092.5588" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge7" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M986.0588,-379.3317C986.0588,-354.9425 986.0588,-309.3638 986.0588,-263.5816"/>
<polygon fill="#000000" stroke="#000000" points="989.5589,-263.5087 986.0588,-253.5087 982.5589,-263.5088 989.5589,-263.5087"/>
<text text-anchor="middle" x="1037.0588" y="-275.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- clinical_measure_file -->
<g id="node5" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M55.0588,-812C55.0588,-812 407.0588,-812 407.0588,-812 413.0588,-812 419.0588,-818 419.0588,-824 419.0588,-824 419.0588,-1053 419.0588,-1053 419.0588,-1059 413.0588,-1065 407.0588,-1065 407.0588,-1065 55.0588,-1065 55.0588,-1065 49.0588,-1065 43.0588,-1059 43.0588,-1053 43.0588,-1053 43.0588,-824 43.0588,-824 43.0588,-818 49.0588,-812 55.0588,-812"/>
<text text-anchor="middle" x="126.5588" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="210.0588,-812 210.0588,-1065 "/>
<text text-anchor="middle" x="220.5588" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="231.0588,-812 231.0588,-1065 "/>
<text text-anchor="middle" x="314.5588" y="-1049.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="231.0588,-1042 398.0588,-1042 "/>
<text text-anchor="middle" x="314.5588" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="231.0588,-1019 398.0588,-1019 "/>
<text text-anchor="middle" x="314.5588" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="231.0588,-996 398.0588,-996 "/>
<text text-anchor="middle" x="314.5588" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="231.0588,-973 398.0588,-973 "/>
<text text-anchor="middle" x="314.5588" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="231.0588,-950 398.0588,-950 "/>
<text text-anchor="middle" x="314.5588" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="231.0588,-927 398.0588,-927 "/>
<text text-anchor="middle" x="314.5588" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="231.0588,-904 398.0588,-904 "/>
<text text-anchor="middle" x="314.5588" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="231.0588,-881 398.0588,-881 "/>
<text text-anchor="middle" x="314.5588" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="231.0588,-858 398.0588,-858 "/>
<text text-anchor="middle" x="314.5588" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="231.0588,-835 398.0588,-835 "/>
<text text-anchor="middle" x="314.5588" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="398.0588,-812 398.0588,-1065 "/>
<text text-anchor="middle" x="408.5588" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M313.4622,-811.7396C344.84,-772.7995 383.834,-733.5248 428.0588,-708 501.52,-665.6011 714.6561,-634.3633 869.6776,-616.4507"/>
<polygon fill="#000000" stroke="#000000" points="870.2661,-619.9063 879.8024,-615.2901 869.4689,-612.9518 870.2661,-619.9063"/>
<text text-anchor="middle" x="641.5588" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge5" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M202.3248,-811.8014C187.3898,-725.278 176.4827,-608.5471 199.0588,-508 220.9233,-410.6222 227.2034,-378.1857 295.0588,-305 359.1234,-235.9029 591.0514,-186.0711 768.7202,-157.0077"/>
<polygon fill="#000000" stroke="#000000" points="769.4274,-160.4388 778.7373,-155.3816 768.3056,-153.5292 769.4274,-160.4388"/>
<text text-anchor="middle" x="285.0588" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- sample_diagnosis -->
<g id="node6" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M1180.5588,-1289.5C1180.5588,-1289.5 1613.5588,-1289.5 1613.5588,-1289.5 1619.5588,-1289.5 1625.5588,-1295.5 1625.5588,-1301.5 1625.5588,-1301.5 1625.5588,-1714.5 1625.5588,-1714.5 1625.5588,-1720.5 1619.5588,-1726.5 1613.5588,-1726.5 1613.5588,-1726.5 1180.5588,-1726.5 1180.5588,-1726.5 1174.5588,-1726.5 1168.5588,-1720.5 1168.5588,-1714.5 1168.5588,-1714.5 1168.5588,-1301.5 1168.5588,-1301.5 1168.5588,-1295.5 1174.5588,-1289.5 1180.5588,-1289.5"/>
<text text-anchor="middle" x="1240.0588" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1311.5588,-1289.5 1311.5588,-1726.5 "/>
<text text-anchor="middle" x="1322.0588" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1332.5588,-1289.5 1332.5588,-1726.5 "/>
<text text-anchor="middle" x="1468.5588" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1332.5588,-1703.5 1604.5588,-1703.5 "/>
<text text-anchor="middle" x="1468.5588" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1332.5588,-1680.5 1604.5588,-1680.5 "/>
<text text-anchor="middle" x="1468.5588" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1332.5588,-1657.5 1604.5588,-1657.5 "/>
<text text-anchor="middle" x="1468.5588" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1332.5588,-1634.5 1604.5588,-1634.5 "/>
<text text-anchor="middle" x="1468.5588" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="1332.5588,-1611.5 1604.5588,-1611.5 "/>
<text text-anchor="middle" x="1468.5588" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="1332.5588,-1588.5 1604.5588,-1588.5 "/>
<text text-anchor="middle" x="1468.5588" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="1332.5588,-1565.5 1604.5588,-1565.5 "/>
<text text-anchor="middle" x="1468.5588" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1332.5588,-1542.5 1604.5588,-1542.5 "/>
<text text-anchor="middle" x="1468.5588" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="1332.5588,-1519.5 1604.5588,-1519.5 "/>
<text text-anchor="middle" x="1468.5588" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="1332.5588,-1496.5 1604.5588,-1496.5 "/>
<text text-anchor="middle" x="1468.5588" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1332.5588,-1473.5 1604.5588,-1473.5 "/>
<text text-anchor="middle" x="1468.5588" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="1332.5588,-1450.5 1604.5588,-1450.5 "/>
<text text-anchor="middle" x="1468.5588" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="1332.5588,-1427.5 1604.5588,-1427.5 "/>
<text text-anchor="middle" x="1468.5588" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classfication</text>
<polyline fill="none" stroke="#000000" points="1332.5588,-1404.5 1604.5588,-1404.5 "/>
<text text-anchor="middle" x="1468.5588" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1332.5588,-1381.5 1604.5588,-1381.5 "/>
<text text-anchor="middle" x="1468.5588" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="1332.5588,-1358.5 1604.5588,-1358.5 "/>
<text text-anchor="middle" x="1468.5588" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1332.5588,-1335.5 1604.5588,-1335.5 "/>
<text text-anchor="middle" x="1468.5588" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1332.5588,-1312.5 1604.5588,-1312.5 "/>
<text text-anchor="middle" x="1468.5588" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1604.5588,-1289.5 1604.5588,-1726.5 "/>
<text text-anchor="middle" x="1615.0588" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1559.3919,-1289.4452C1627.1167,-1198.2647 1701.962,-1097.4979 1754.0128,-1027.42"/>
<polygon fill="#000000" stroke="#000000" points="1757.0925,-1029.1436 1760.2455,-1019.0288 1751.473,-1024.9696 1757.0925,-1029.1436"/>
<text text-anchor="middle" x="1708.0588" y="-1190.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
<!-- study_arm -->
<g id="node7" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M1133.5588,-363C1133.5588,-363 1430.5588,-363 1430.5588,-363 1436.5588,-363 1442.5588,-369 1442.5588,-375 1442.5588,-375 1442.5588,-420 1442.5588,-420 1442.5588,-426 1436.5588,-432 1430.5588,-432 1430.5588,-432 1133.5588,-432 1133.5588,-432 1127.5588,-432 1121.5588,-426 1121.5588,-420 1121.5588,-420 1121.5588,-375 1121.5588,-375 1121.5588,-369 1127.5588,-363 1133.5588,-363"/>
<text text-anchor="middle" x="1167.5588" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="1213.5588,-363 1213.5588,-432 "/>
<text text-anchor="middle" x="1224.0588" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1234.5588,-363 1234.5588,-432 "/>
<text text-anchor="middle" x="1328.0588" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="1234.5588,-409 1421.5588,-409 "/>
<text text-anchor="middle" x="1328.0588" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="1234.5588,-386 1421.5588,-386 "/>
<text text-anchor="middle" x="1328.0588" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="1421.5588,-363 1421.5588,-432 "/>
<text text-anchor="middle" x="1432.0588" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge18" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1244.2695,-362.9662C1215.4521,-336.6314 1173.7739,-298.5437 1132.2819,-260.6262"/>
<polygon fill="#000000" stroke="#000000" points="1134.556,-257.963 1124.813,-253.8007 1129.8338,-263.1304 1134.556,-257.963"/>
<text text-anchor="middle" x="1209.5588" y="-275.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- pdx -->
<g id="node8" class="node">
<title>pdx</title>
<path fill="none" stroke="#000000" d="M1655.5588,-1404.5C1655.5588,-1404.5 1984.5588,-1404.5 1984.5588,-1404.5 1990.5588,-1404.5 1996.5588,-1410.5 1996.5588,-1416.5 1996.5588,-1416.5 1996.5588,-1599.5 1996.5588,-1599.5 1996.5588,-1605.5 1990.5588,-1611.5 1984.5588,-1611.5 1984.5588,-1611.5 1655.5588,-1611.5 1655.5588,-1611.5 1649.5588,-1611.5 1643.5588,-1605.5 1643.5588,-1599.5 1643.5588,-1599.5 1643.5588,-1416.5 1643.5588,-1416.5 1643.5588,-1410.5 1649.5588,-1404.5 1655.5588,-1404.5"/>
<text text-anchor="middle" x="1665.0588" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
<polyline fill="none" stroke="#000000" points="1686.5588,-1404.5 1686.5588,-1611.5 "/>
<text text-anchor="middle" x="1697.0588" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1707.5588,-1404.5 1707.5588,-1611.5 "/>
<text text-anchor="middle" x="1841.5588" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_site</text>
<polyline fill="none" stroke="#000000" points="1707.5588,-1588.5 1975.5588,-1588.5 "/>
<text text-anchor="middle" x="1841.5588" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_type</text>
<polyline fill="none" stroke="#000000" points="1707.5588,-1565.5 1975.5588,-1565.5 "/>
<text text-anchor="middle" x="1841.5588" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_id</text>
<polyline fill="none" stroke="#000000" points="1707.5588,-1542.5 1975.5588,-1542.5 "/>
<text text-anchor="middle" x="1841.5588" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">mouse_strain</text>
<polyline fill="none" stroke="#000000" points="1707.5588,-1519.5 1975.5588,-1519.5 "/>
<text text-anchor="middle" x="1841.5588" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">strain_immune_system_humanized</text>
<polyline fill="none" stroke="#000000" points="1707.5588,-1496.5 1975.5588,-1496.5 "/>
<text text-anchor="middle" x="1841.5588" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_characterization_method</text>
<polyline fill="none" stroke="#000000" points="1707.5588,-1473.5 1975.5588,-1473.5 "/>
<text text-anchor="middle" x="1841.5588" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_not_mus_or_ebv_origin</text>
<polyline fill="none" stroke="#000000" points="1707.5588,-1450.5 1975.5588,-1450.5 "/>
<text text-anchor="middle" x="1841.5588" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_preparation</text>
<polyline fill="none" stroke="#000000" points="1707.5588,-1427.5 1975.5588,-1427.5 "/>
<text text-anchor="middle" x="1841.5588" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_humanization</text>
<polyline fill="none" stroke="#000000" points="1975.5588,-1404.5 1975.5588,-1611.5 "/>
<text text-anchor="middle" x="1986.0588" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1820.0588,-1404.2071C1820.0588,-1297.0419 1820.0588,-1131.4893 1820.0588,-1029.3452"/>
<polygon fill="#000000" stroke="#000000" points="1823.5589,-1029.0505 1820.0588,-1019.0505 1816.5589,-1029.0506 1823.5589,-1029.0505"/>
<text text-anchor="middle" x="1844.0588" y="-1190.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1675.5662,-857.9818C1569.5689,-801.2818 1420.8621,-726.5856 1284.0588,-675 1262.7678,-666.9716 1240.2105,-659.0654 1217.7825,-651.5637"/>
<polygon fill="#000000" stroke="#000000" points="1218.776,-648.2057 1208.1825,-648.3743 1216.569,-654.8487 1218.776,-648.2057"/>
<text text-anchor="middle" x="1350.5588" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge8" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1822.9389,-857.8643C1827.9224,-696.6733 1834.5706,-346.5156 1800.0588,-305 1725.0162,-214.7284 1417.9532,-167.3739 1203.2243,-144.8023"/>
<polygon fill="#000000" stroke="#000000" points="1203.3786,-141.2996 1193.0702,-143.7461 1202.6544,-148.262 1203.3786,-141.2996"/>
<text text-anchor="middle" x="1862.5588" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_personnel -->
<g id="node10" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M1472.5588,-340C1472.5588,-340 1779.5588,-340 1779.5588,-340 1785.5588,-340 1791.5588,-346 1791.5588,-352 1791.5588,-352 1791.5588,-443 1791.5588,-443 1791.5588,-449 1785.5588,-455 1779.5588,-455 1779.5588,-455 1472.5588,-455 1472.5588,-455 1466.5588,-455 1460.5588,-449 1460.5588,-443 1460.5588,-443 1460.5588,-352 1460.5588,-352 1460.5588,-346 1466.5588,-340 1472.5588,-340"/>
<text text-anchor="middle" x="1527.5588" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="1594.5588,-340 1594.5588,-455 "/>
<text text-anchor="middle" x="1605.0588" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1615.5588,-340 1615.5588,-455 "/>
<text text-anchor="middle" x="1693.0588" y="-439.8" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="1615.5588,-432 1770.5588,-432 "/>
<text text-anchor="middle" x="1693.0588" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="1615.5588,-409 1770.5588,-409 "/>
<text text-anchor="middle" x="1693.0588" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="1615.5588,-386 1770.5588,-386 "/>
<text text-anchor="middle" x="1693.0588" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="1615.5588,-363 1770.5588,-363 "/>
<text text-anchor="middle" x="1693.0588" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="1770.5588,-340 1770.5588,-455 "/>
<text text-anchor="middle" x="1781.0588" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge16" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1522.0529,-339.8927C1498.9391,-327.8325 1474.3735,-315.5776 1451.0588,-305 1371.2542,-268.7937 1281.733,-233.3488 1202.7064,-203.7403"/>
<polygon fill="#000000" stroke="#000000" points="1203.7149,-200.3808 1193.1224,-200.1588 1201.2644,-206.9379 1203.7149,-200.3808"/>
<text text-anchor="middle" x="1471.5588" y="-275.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- synonym -->
<g id="node11" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M837.5588,-1485C837.5588,-1485 1138.5588,-1485 1138.5588,-1485 1144.5588,-1485 1150.5588,-1491 1150.5588,-1497 1150.5588,-1497 1150.5588,-1519 1150.5588,-1519 1150.5588,-1525 1144.5588,-1531 1138.5588,-1531 1138.5588,-1531 837.5588,-1531 837.5588,-1531 831.5588,-1531 825.5588,-1525 825.5588,-1519 825.5588,-1519 825.5588,-1497 825.5588,-1497 825.5588,-1491 831.5588,-1485 837.5588,-1485"/>
<text text-anchor="middle" x="865.5588" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="905.5588,-1485 905.5588,-1531 "/>
<text text-anchor="middle" x="916.0588" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="926.5588,-1485 926.5588,-1531 "/>
<text text-anchor="middle" x="1028.0588" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="926.5588,-1508 1129.5588,-1508 "/>
<text text-anchor="middle" x="1028.0588" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="1129.5588,-1485 1129.5588,-1531 "/>
<text text-anchor="middle" x="1140.0588" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M994.2842,-1484.9465C1010.6936,-1429.0203 1060.7787,-1285.9086 1159.0588,-1220 1204.5796,-1189.4728 1228.2847,-1216.7969 1281.0588,-1202 1424.0914,-1161.8963 1575.039,-1084.6977 1680.6924,-1024.1811"/>
<polygon fill="#000000" stroke="#000000" points="1682.5712,-1027.1382 1689.4943,-1019.1181 1679.0809,-1021.0704 1682.5712,-1027.1382"/>
<text text-anchor="middle" x="1370.5588" y="-1190.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M997.1183,-1484.942C1018.5965,-1432.5827 1077.0243,-1302.846 1159.0588,-1220 1189.7897,-1188.9651 1221.6394,-1207.0627 1243.0588,-1169 1350.7509,-977.6285 1380.2149,-838.8873 1234.0588,-675 1228.6553,-668.9409 1222.7025,-663.358 1216.3416,-658.2145"/>
<polygon fill="#000000" stroke="#000000" points="1218.1558,-655.1972 1208.0768,-651.9317 1213.9195,-660.7698 1218.1558,-655.1972"/>
<text text-anchor="middle" x="1376.5588" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge10" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M879.6804,-1484.9195C652.8293,-1434.2846 140.1717,-1306.9155 34.0588,-1169 -28.6235,-1087.5316 15.0588,-1041.2919 15.0588,-938.5 15.0588,-938.5 15.0588,-938.5 15.0588,-397.5 15.0588,-242.0659 482.6197,-172.097 768.8417,-143.8266"/>
<polygon fill="#000000" stroke="#000000" points="769.3341,-147.2952 778.9459,-142.8385 768.6527,-140.3285 769.3341,-147.2952"/>
<text text-anchor="middle" x="57.5588" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- therapeutic_procedure -->
<g id="node12" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M865.5588,-881C865.5588,-881 1222.5588,-881 1222.5588,-881 1228.5588,-881 1234.5588,-887 1234.5588,-893 1234.5588,-893 1234.5588,-984 1234.5588,-984 1234.5588,-990 1228.5588,-996 1222.5588,-996 1222.5588,-996 865.5588,-996 865.5588,-996 859.5588,-996 853.5588,-990 853.5588,-984 853.5588,-984 853.5588,-893 853.5588,-893 853.5588,-887 859.5588,-881 865.5588,-881"/>
<text text-anchor="middle" x="944.0588" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="1034.5588,-881 1034.5588,-996 "/>
<text text-anchor="middle" x="1045.0588" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1055.5588,-881 1055.5588,-996 "/>
<text text-anchor="middle" x="1134.5588" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="1055.5588,-973 1213.5588,-973 "/>
<text text-anchor="middle" x="1134.5588" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="1055.5588,-950 1213.5588,-950 "/>
<text text-anchor="middle" x="1134.5588" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1055.5588,-927 1213.5588,-927 "/>
<text text-anchor="middle" x="1134.5588" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="1055.5588,-904 1213.5588,-904 "/>
<text text-anchor="middle" x="1134.5588" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1213.5588,-881 1213.5588,-996 "/>
<text text-anchor="middle" x="1224.0588" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1044.0588,-880.9085C1044.0588,-821.6812 1044.0588,-729.4816 1044.0588,-666.7773"/>
<polygon fill="#000000" stroke="#000000" points="1047.5589,-666.59 1044.0588,-656.59 1040.5589,-666.5901 1047.5589,-666.59"/>
<text text-anchor="middle" x="1137.0588" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge21" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1112.26,-541.2582C1150.9538,-508.4985 1198.4689,-468.2704 1233.3858,-438.7084"/>
<polygon fill="#000000" stroke="#000000" points="1235.7122,-441.3248 1241.0827,-432.1919 1231.1891,-435.9823 1235.7122,-441.3248"/>
<text text-anchor="middle" x="1199.5588" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge20" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M879.8932,-584.8733C682.1577,-566.1652 372.0016,-530.7429 337.0588,-490 283.5313,-427.5876 287.1973,-370.3783 337.0588,-305 389.8975,-235.718 601.4748,-186.7439 768.8816,-157.9322"/>
<polygon fill="#000000" stroke="#000000" points="769.563,-161.3666 778.8318,-156.2344 768.3856,-154.4663 769.563,-161.3666"/>
<text text-anchor="middle" x="387.5588" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_admin -->
<g id="node14" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M1860.0588,-305.5C1860.0588,-305.5 2186.0588,-305.5 2186.0588,-305.5 2192.0588,-305.5 2198.0588,-311.5 2198.0588,-317.5 2198.0588,-317.5 2198.0588,-477.5 2198.0588,-477.5 2198.0588,-483.5 2192.0588,-489.5 2186.0588,-489.5 2186.0588,-489.5 1860.0588,-489.5 1860.0588,-489.5 1854.0588,-489.5 1848.0588,-483.5 1848.0588,-477.5 1848.0588,-477.5 1848.0588,-317.5 1848.0588,-317.5 1848.0588,-311.5 1854.0588,-305.5 1860.0588,-305.5"/>
<text text-anchor="middle" x="1902.0588" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="1956.0588,-305.5 1956.0588,-489.5 "/>
<text text-anchor="middle" x="1966.5588" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1977.0588,-305.5 1977.0588,-489.5 "/>
<text text-anchor="middle" x="2077.0588" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="1977.0588,-466.5 2177.0588,-466.5 "/>
<text text-anchor="middle" x="2077.0588" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="1977.0588,-443.5 2177.0588,-443.5 "/>
<text text-anchor="middle" x="2077.0588" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="1977.0588,-420.5 2177.0588,-420.5 "/>
<text text-anchor="middle" x="2077.0588" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="1977.0588,-397.5 2177.0588,-397.5 "/>
<text text-anchor="middle" x="2077.0588" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="1977.0588,-374.5 2177.0588,-374.5 "/>
<text text-anchor="middle" x="2077.0588" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="1977.0588,-351.5 2177.0588,-351.5 "/>
<text text-anchor="middle" x="2077.0588" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="1977.0588,-328.5 2177.0588,-328.5 "/>
<text text-anchor="middle" x="2077.0588" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="2177.0588,-305.5 2177.0588,-489.5 "/>
<text text-anchor="middle" x="2187.5588" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge13" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1900.0107,-305.4066C1878.8119,-292.6262 1856.3912,-280.8619 1834.0588,-272 1629.2715,-190.7366 1378.9303,-154.9801 1203.5276,-139.2684"/>
<polygon fill="#000000" stroke="#000000" points="1203.6667,-135.7672 1193.3981,-138.3759 1203.0523,-142.7402 1203.6667,-135.7672"/>
<text text-anchor="middle" x="1919.5588" y="-275.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- sequencing_file -->
<g id="node16" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M2026.5588,-1220.5C2026.5588,-1220.5 2495.5588,-1220.5 2495.5588,-1220.5 2501.5588,-1220.5 2507.5588,-1226.5 2507.5588,-1232.5 2507.5588,-1232.5 2507.5588,-1783.5 2507.5588,-1783.5 2507.5588,-1789.5 2501.5588,-1795.5 2495.5588,-1795.5 2495.5588,-1795.5 2026.5588,-1795.5 2026.5588,-1795.5 2020.5588,-1795.5 2014.5588,-1789.5 2014.5588,-1783.5 2014.5588,-1783.5 2014.5588,-1232.5 2014.5588,-1232.5 2014.5588,-1226.5 2020.5588,-1220.5 2026.5588,-1220.5"/>
<text text-anchor="middle" x="2078.5588" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="2142.5588,-1220.5 2142.5588,-1795.5 "/>
<text text-anchor="middle" x="2153.0588" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2163.5588,-1220.5 2163.5588,-1795.5 "/>
<text text-anchor="middle" x="2325.0588" y="-1780.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="2163.5588,-1772.5 2486.5588,-1772.5 "/>
<text text-anchor="middle" x="2325.0588" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2163.5588,-1749.5 2486.5588,-1749.5 "/>
<text text-anchor="middle" x="2325.0588" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2163.5588,-1726.5 2486.5588,-1726.5 "/>
<text text-anchor="middle" x="2325.0588" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="2163.5588,-1703.5 2486.5588,-1703.5 "/>
<text text-anchor="middle" x="2325.0588" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="2163.5588,-1680.5 2486.5588,-1680.5 "/>
<text text-anchor="middle" x="2325.0588" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2163.5588,-1657.5 2486.5588,-1657.5 "/>
<text text-anchor="middle" x="2325.0588" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="2163.5588,-1634.5 2486.5588,-1634.5 "/>
<text text-anchor="middle" x="2325.0588" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2163.5588,-1611.5 2486.5588,-1611.5 "/>
<text text-anchor="middle" x="2325.0588" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2163.5588,-1588.5 2486.5588,-1588.5 "/>
<text text-anchor="middle" x="2325.0588" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2163.5588,-1565.5 2486.5588,-1565.5 "/>
<text text-anchor="middle" x="2325.0588" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2163.5588,-1542.5 2486.5588,-1542.5 "/>
<text text-anchor="middle" x="2325.0588" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2163.5588,-1519.5 2486.5588,-1519.5 "/>
<text text-anchor="middle" x="2325.0588" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2163.5588,-1496.5 2486.5588,-1496.5 "/>
<text text-anchor="middle" x="2325.0588" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="2163.5588,-1473.5 2486.5588,-1473.5 "/>
<text text-anchor="middle" x="2325.0588" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="2163.5588,-1450.5 2486.5588,-1450.5 "/>
<text text-anchor="middle" x="2325.0588" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="2163.5588,-1427.5 2486.5588,-1427.5 "/>
<text text-anchor="middle" x="2325.0588" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="2163.5588,-1404.5 2486.5588,-1404.5 "/>
<text text-anchor="middle" x="2325.0588" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="2163.5588,-1381.5 2486.5588,-1381.5 "/>
<text text-anchor="middle" x="2325.0588" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="2163.5588,-1358.5 2486.5588,-1358.5 "/>
<text text-anchor="middle" x="2325.0588" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2163.5588,-1335.5 2486.5588,-1335.5 "/>
<text text-anchor="middle" x="2325.0588" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="2163.5588,-1312.5 2486.5588,-1312.5 "/>
<text text-anchor="middle" x="2325.0588" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="2163.5588,-1289.5 2486.5588,-1289.5 "/>
<text text-anchor="middle" x="2325.0588" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="2163.5588,-1266.5 2486.5588,-1266.5 "/>
<text text-anchor="middle" x="2325.0588" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="2163.5588,-1243.5 2486.5588,-1243.5 "/>
<text text-anchor="middle" x="2325.0588" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="2486.5588,-1220.5 2486.5588,-1795.5 "/>
<text text-anchor="middle" x="2497.0588" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2038.2978,-1220.3302C1983.7844,-1149.9326 1929.4553,-1079.7729 1888.64,-1027.0646"/>
<polygon fill="#000000" stroke="#000000" points="1891.3528,-1024.8513 1882.4629,-1019.0876 1885.8182,-1029.1371 1891.3528,-1024.8513"/>
<text text-anchor="middle" x="2081.5588" y="-1190.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- methylation_array_file -->
<g id="node17" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M2537.5588,-1393C2537.5588,-1393 2904.5588,-1393 2904.5588,-1393 2910.5588,-1393 2916.5588,-1399 2916.5588,-1405 2916.5588,-1405 2916.5588,-1611 2916.5588,-1611 2916.5588,-1617 2910.5588,-1623 2904.5588,-1623 2904.5588,-1623 2537.5588,-1623 2537.5588,-1623 2531.5588,-1623 2525.5588,-1617 2525.5588,-1611 2525.5588,-1611 2525.5588,-1405 2525.5588,-1405 2525.5588,-1399 2531.5588,-1393 2537.5588,-1393"/>
<text text-anchor="middle" x="2614.5588" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="2703.5588,-1393 2703.5588,-1623 "/>
<text text-anchor="middle" x="2714.0588" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2724.5588,-1393 2724.5588,-1623 "/>
<text text-anchor="middle" x="2810.0588" y="-1607.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2724.5588,-1600 2895.5588,-1600 "/>
<text text-anchor="middle" x="2810.0588" y="-1584.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2724.5588,-1577 2895.5588,-1577 "/>
<text text-anchor="middle" x="2810.0588" y="-1561.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2724.5588,-1554 2895.5588,-1554 "/>
<text text-anchor="middle" x="2810.0588" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2724.5588,-1531 2895.5588,-1531 "/>
<text text-anchor="middle" x="2810.0588" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2724.5588,-1508 2895.5588,-1508 "/>
<text text-anchor="middle" x="2810.0588" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2724.5588,-1485 2895.5588,-1485 "/>
<text text-anchor="middle" x="2810.0588" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2724.5588,-1462 2895.5588,-1462 "/>
<text text-anchor="middle" x="2810.0588" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2724.5588,-1439 2895.5588,-1439 "/>
<text text-anchor="middle" x="2810.0588" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="2724.5588,-1416 2895.5588,-1416 "/>
<text text-anchor="middle" x="2810.0588" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="2895.5588,-1393 2895.5588,-1623 "/>
<text text-anchor="middle" x="2906.0588" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2660.0992,-1392.7301C2624.545,-1334.5319 2575.0691,-1266.5848 2516.0588,-1220 2362.1437,-1098.494 2148.7568,-1022.58 1998.9571,-980.6354"/>
<polygon fill="#000000" stroke="#000000" points="1999.7552,-977.2247 1989.1833,-977.9216 1997.8824,-983.9695 1999.7552,-977.2247"/>
<text text-anchor="middle" x="2575.5588" y="-1190.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
</g>
</svg>
</div>
