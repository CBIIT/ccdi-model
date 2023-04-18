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
<svg width="4276pt" height="1821pt"
 viewBox="0.00 0.00 4276.00 1821.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1817)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1817 4272,-1817 4272,4 -4,4"/>
<!-- study_funding -->
<g id="node1" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M1649,-386C1649,-386 2028,-386 2028,-386 2034,-386 2040,-392 2040,-398 2040,-398 2040,-466 2040,-466 2040,-472 2034,-478 2028,-478 2028,-478 1649,-478 1649,-478 1643,-478 1637,-472 1637,-466 1637,-466 1637,-398 1637,-398 1637,-392 1643,-386 1649,-386"/>
<text text-anchor="middle" x="1696.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="1756,-386 1756,-478 "/>
<text text-anchor="middle" x="1766.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1777,-386 1777,-478 "/>
<text text-anchor="middle" x="1898" y="-462.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="1777,-455 2019,-455 "/>
<text text-anchor="middle" x="1898" y="-439.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="1777,-432 2019,-432 "/>
<text text-anchor="middle" x="1898" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="1777,-409 2019,-409 "/>
<text text-anchor="middle" x="1898" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding_id</text>
<polyline fill="none" stroke="#000000" points="2019,-386 2019,-478 "/>
<text text-anchor="middle" x="2029.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node21" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M2987.5,-.5C2987.5,-.5 3377.5,-.5 3377.5,-.5 3383.5,-.5 3389.5,-6.5 3389.5,-12.5 3389.5,-12.5 3389.5,-287.5 3389.5,-287.5 3389.5,-293.5 3383.5,-299.5 3377.5,-299.5 3377.5,-299.5 2987.5,-299.5 2987.5,-299.5 2981.5,-299.5 2975.5,-293.5 2975.5,-287.5 2975.5,-287.5 2975.5,-12.5 2975.5,-12.5 2975.5,-6.5 2981.5,-.5 2987.5,-.5"/>
<text text-anchor="middle" x="3003.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="3031.5,-.5 3031.5,-299.5 "/>
<text text-anchor="middle" x="3042" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3052.5,-.5 3052.5,-299.5 "/>
<text text-anchor="middle" x="3210.5" y="-284.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="3052.5,-276.5 3368.5,-276.5 "/>
<text text-anchor="middle" x="3210.5" y="-261.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="3052.5,-253.5 3368.5,-253.5 "/>
<text text-anchor="middle" x="3210.5" y="-238.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_number</text>
<polyline fill="none" stroke="#000000" points="3052.5,-230.5 3368.5,-230.5 "/>
<text text-anchor="middle" x="3210.5" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="3052.5,-207.5 3368.5,-207.5 "/>
<text text-anchor="middle" x="3210.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="3052.5,-184.5 3368.5,-184.5 "/>
<text text-anchor="middle" x="3210.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="3052.5,-161.5 3368.5,-161.5 "/>
<text text-anchor="middle" x="3210.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="3052.5,-138.5 3368.5,-138.5 "/>
<text text-anchor="middle" x="3210.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="3052.5,-115.5 3368.5,-115.5 "/>
<text text-anchor="middle" x="3210.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="3052.5,-92.5 3368.5,-92.5 "/>
<text text-anchor="middle" x="3210.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="3052.5,-69.5 3368.5,-69.5 "/>
<text text-anchor="middle" x="3210.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="3052.5,-46.5 3368.5,-46.5 "/>
<text text-anchor="middle" x="3210.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="3052.5,-23.5 3368.5,-23.5 "/>
<text text-anchor="middle" x="3210.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="3368.5,-.5 3368.5,-299.5 "/>
<text text-anchor="middle" x="3379" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge12" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1946.1501,-385.9035C1978.6094,-373.2549 2014.6221,-360.4409 2048.5,-351 2361.8798,-263.6692 2734.9893,-206.1542 2965.3136,-175.8322"/>
<polygon fill="#000000" stroke="#000000" points="2966.0302,-179.2683 2975.4904,-174.4979 2965.1202,-172.3277 2966.0302,-179.2683"/>
<text text-anchor="middle" x="2231.5" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- family_relationship -->
<g id="node2" class="node">
<title>family_relationship</title>
<path fill="none" stroke="#000000" d="M2151,-817.5C2151,-817.5 2520,-817.5 2520,-817.5 2526,-817.5 2532,-823.5 2532,-829.5 2532,-829.5 2532,-897.5 2532,-897.5 2532,-903.5 2526,-909.5 2520,-909.5 2520,-909.5 2151,-909.5 2151,-909.5 2145,-909.5 2139,-903.5 2139,-897.5 2139,-897.5 2139,-829.5 2139,-829.5 2139,-823.5 2145,-817.5 2151,-817.5"/>
<text text-anchor="middle" x="2216" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
<polyline fill="none" stroke="#000000" points="2293,-817.5 2293,-909.5 "/>
<text text-anchor="middle" x="2303.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2314,-817.5 2314,-909.5 "/>
<text text-anchor="middle" x="2412.5" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_id</text>
<polyline fill="none" stroke="#000000" points="2314,-886.5 2511,-886.5 "/>
<text text-anchor="middle" x="2412.5" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship_id</text>
<polyline fill="none" stroke="#000000" points="2314,-863.5 2511,-863.5 "/>
<text text-anchor="middle" x="2412.5" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">related_to_participant_id</text>
<polyline fill="none" stroke="#000000" points="2314,-840.5 2511,-840.5 "/>
<text text-anchor="middle" x="2412.5" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">relationship</text>
<polyline fill="none" stroke="#000000" points="2511,-817.5 2511,-909.5 "/>
<text text-anchor="middle" x="2521.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node15" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M2713.5,-374.5C2713.5,-374.5 3017.5,-374.5 3017.5,-374.5 3023.5,-374.5 3029.5,-380.5 3029.5,-386.5 3029.5,-386.5 3029.5,-477.5 3029.5,-477.5 3029.5,-483.5 3023.5,-489.5 3017.5,-489.5 3017.5,-489.5 2713.5,-489.5 2713.5,-489.5 2707.5,-489.5 2701.5,-483.5 2701.5,-477.5 2701.5,-477.5 2701.5,-386.5 2701.5,-386.5 2701.5,-380.5 2707.5,-374.5 2713.5,-374.5"/>
<text text-anchor="middle" x="2749.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="2797.5,-374.5 2797.5,-489.5 "/>
<text text-anchor="middle" x="2808" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2818.5,-374.5 2818.5,-489.5 "/>
<text text-anchor="middle" x="2913.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="2818.5,-466.5 3008.5,-466.5 "/>
<text text-anchor="middle" x="2913.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="2818.5,-443.5 3008.5,-443.5 "/>
<text text-anchor="middle" x="2913.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="2818.5,-420.5 3008.5,-420.5 "/>
<text text-anchor="middle" x="2913.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="2818.5,-397.5 3008.5,-397.5 "/>
<text text-anchor="middle" x="2913.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="3008.5,-374.5 3008.5,-489.5 "/>
<text text-anchor="middle" x="3019" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2355.4317,-817.2438C2385.9635,-751.6682 2450.3907,-632.0964 2540.5,-564 2597.3493,-521.0385 2626.3477,-539.484 2692.5,-513 2707.2879,-507.0797 2722.6167,-500.5295 2737.7628,-493.7943"/>
<polygon fill="#000000" stroke="#000000" points="2739.4697,-496.8649 2747.1634,-489.5808 2736.6065,-490.4772 2739.4697,-496.8649"/>
<text text-anchor="middle" x="2698" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- publication -->
<g id="node3" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M2070,-409C2070,-409 2303,-409 2303,-409 2309,-409 2315,-415 2315,-421 2315,-421 2315,-443 2315,-443 2315,-449 2309,-455 2303,-455 2303,-455 2070,-455 2070,-455 2064,-455 2058,-449 2058,-443 2058,-443 2058,-421 2058,-421 2058,-415 2064,-409 2070,-409"/>
<text text-anchor="middle" x="2106.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="2155,-409 2155,-455 "/>
<text text-anchor="middle" x="2165.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2176,-409 2176,-455 "/>
<text text-anchor="middle" x="2235" y="-439.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication_id</text>
<polyline fill="none" stroke="#000000" points="2176,-432 2294,-432 "/>
<text text-anchor="middle" x="2235" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="2294,-409 2294,-455 "/>
<text text-anchor="middle" x="2304.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge20" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2219.3515,-408.883C2246.4373,-390.7877 2286.4536,-366.2158 2324.5,-351 2534.6704,-266.9469 2788.4941,-212.9121 2965.3129,-182.273"/>
<polygon fill="#000000" stroke="#000000" points="2965.9971,-185.7068 2975.258,-180.5603 2964.8091,-178.8083 2965.9971,-185.7068"/>
<text text-anchor="middle" x="2442.5" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- methylation_array_file -->
<g id="node4" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M1405,-1387C1405,-1387 1800,-1387 1800,-1387 1806,-1387 1812,-1393 1812,-1399 1812,-1399 1812,-1628 1812,-1628 1812,-1634 1806,-1640 1800,-1640 1800,-1640 1405,-1640 1405,-1640 1399,-1640 1393,-1634 1393,-1628 1393,-1628 1393,-1399 1393,-1399 1393,-1393 1399,-1387 1405,-1387"/>
<text text-anchor="middle" x="1482" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="1571,-1387 1571,-1640 "/>
<text text-anchor="middle" x="1581.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1592,-1387 1592,-1640 "/>
<text text-anchor="middle" x="1691.5" y="-1624.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1592,-1617 1791,-1617 "/>
<text text-anchor="middle" x="1691.5" y="-1601.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1592,-1594 1791,-1594 "/>
<text text-anchor="middle" x="1691.5" y="-1578.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1592,-1571 1791,-1571 "/>
<text text-anchor="middle" x="1691.5" y="-1555.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1592,-1548 1791,-1548 "/>
<text text-anchor="middle" x="1691.5" y="-1532.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1592,-1525 1791,-1525 "/>
<text text-anchor="middle" x="1691.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1592,-1502 1791,-1502 "/>
<text text-anchor="middle" x="1691.5" y="-1486.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1592,-1479 1791,-1479 "/>
<text text-anchor="middle" x="1691.5" y="-1463.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1592,-1456 1791,-1456 "/>
<text text-anchor="middle" x="1691.5" y="-1440.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file_id</text>
<polyline fill="none" stroke="#000000" points="1592,-1433 1791,-1433 "/>
<text text-anchor="middle" x="1691.5" y="-1417.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="1592,-1410 1791,-1410 "/>
<text text-anchor="middle" x="1691.5" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="1791,-1387 1791,-1640 "/>
<text text-anchor="middle" x="1801.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node10" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M2967.5,-668C2967.5,-668 3325.5,-668 3325.5,-668 3331.5,-668 3337.5,-674 3337.5,-680 3337.5,-680 3337.5,-1047 3337.5,-1047 3337.5,-1053 3331.5,-1059 3325.5,-1059 3325.5,-1059 2967.5,-1059 2967.5,-1059 2961.5,-1059 2955.5,-1053 2955.5,-1047 2955.5,-1047 2955.5,-680 2955.5,-680 2955.5,-674 2961.5,-668 2967.5,-668"/>
<text text-anchor="middle" x="2989.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="3023.5,-668 3023.5,-1059 "/>
<text text-anchor="middle" x="3034" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3044.5,-668 3044.5,-1059 "/>
<text text-anchor="middle" x="3180.5" y="-1043.8" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="3044.5,-1036 3316.5,-1036 "/>
<text text-anchor="middle" x="3180.5" y="-1020.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="3044.5,-1013 3316.5,-1013 "/>
<text text-anchor="middle" x="3180.5" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="3044.5,-990 3316.5,-990 "/>
<text text-anchor="middle" x="3180.5" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="3044.5,-967 3316.5,-967 "/>
<text text-anchor="middle" x="3180.5" y="-951.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="3044.5,-944 3316.5,-944 "/>
<text text-anchor="middle" x="3180.5" y="-928.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="3044.5,-921 3316.5,-921 "/>
<text text-anchor="middle" x="3180.5" y="-905.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="3044.5,-898 3316.5,-898 "/>
<text text-anchor="middle" x="3180.5" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="3044.5,-875 3316.5,-875 "/>
<text text-anchor="middle" x="3180.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="3044.5,-852 3316.5,-852 "/>
<text text-anchor="middle" x="3180.5" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="3044.5,-829 3316.5,-829 "/>
<text text-anchor="middle" x="3180.5" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="3044.5,-806 3316.5,-806 "/>
<text text-anchor="middle" x="3180.5" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="3044.5,-783 3316.5,-783 "/>
<text text-anchor="middle" x="3180.5" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="3044.5,-760 3316.5,-760 "/>
<text text-anchor="middle" x="3180.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="3044.5,-737 3316.5,-737 "/>
<text text-anchor="middle" x="3180.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="3044.5,-714 3316.5,-714 "/>
<text text-anchor="middle" x="3180.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="3044.5,-691 3316.5,-691 "/>
<text text-anchor="middle" x="3180.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="3316.5,-668 3316.5,-1059 "/>
<text text-anchor="middle" x="3327" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1661.9515,-1386.975C1698.4723,-1323.9913 1751.5607,-1253.1187 1820.5,-1214 1961.3959,-1134.0506 2021.7657,-1190.2514 2183.5,-1181 2225.776,-1178.5818 2908.3726,-1183.3633 2945.5,-1163 2986.507,-1140.5089 3020.695,-1105.6488 3048.5526,-1067.5512"/>
<polygon fill="#000000" stroke="#000000" points="3051.4295,-1069.5453 3054.4012,-1059.3758 3045.7363,-1065.4725 3051.4295,-1069.5453"/>
<text text-anchor="middle" x="2275" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- diagnosis -->
<g id="node5" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M908.5,-668C908.5,-668 1282.5,-668 1282.5,-668 1288.5,-668 1294.5,-674 1294.5,-680 1294.5,-680 1294.5,-1047 1294.5,-1047 1294.5,-1053 1288.5,-1059 1282.5,-1059 1282.5,-1059 908.5,-1059 908.5,-1059 902.5,-1059 896.5,-1053 896.5,-1047 896.5,-1047 896.5,-680 896.5,-680 896.5,-674 902.5,-668 908.5,-668"/>
<text text-anchor="middle" x="938.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="980.5,-668 980.5,-1059 "/>
<text text-anchor="middle" x="991" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1001.5,-668 1001.5,-1059 "/>
<text text-anchor="middle" x="1137.5" y="-1043.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1001.5,-1036 1273.5,-1036 "/>
<text text-anchor="middle" x="1137.5" y="-1020.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1001.5,-1013 1273.5,-1013 "/>
<text text-anchor="middle" x="1137.5" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1001.5,-990 1273.5,-990 "/>
<text text-anchor="middle" x="1137.5" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1001.5,-967 1273.5,-967 "/>
<text text-anchor="middle" x="1137.5" y="-951.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1001.5,-944 1273.5,-944 "/>
<text text-anchor="middle" x="1137.5" y="-928.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="1001.5,-921 1273.5,-921 "/>
<text text-anchor="middle" x="1137.5" y="-905.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="1001.5,-898 1273.5,-898 "/>
<text text-anchor="middle" x="1137.5" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="1001.5,-875 1273.5,-875 "/>
<text text-anchor="middle" x="1137.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1001.5,-852 1273.5,-852 "/>
<text text-anchor="middle" x="1137.5" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="1001.5,-829 1273.5,-829 "/>
<text text-anchor="middle" x="1137.5" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1001.5,-806 1273.5,-806 "/>
<text text-anchor="middle" x="1137.5" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="1001.5,-783 1273.5,-783 "/>
<text text-anchor="middle" x="1137.5" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1001.5,-760 1273.5,-760 "/>
<text text-anchor="middle" x="1137.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1001.5,-737 1273.5,-737 "/>
<text text-anchor="middle" x="1137.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1001.5,-714 1273.5,-714 "/>
<text text-anchor="middle" x="1137.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1001.5,-691 1273.5,-691 "/>
<text text-anchor="middle" x="1137.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="1273.5,-668 1273.5,-1059 "/>
<text text-anchor="middle" x="1284" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1194.2532,-667.9364C1223.8639,-627.2094 1260.2344,-589.0851 1303.5,-564 1437.1051,-486.5367 2542.0541,-547.8844 2692.5,-513 2712.0733,-508.4615 2732.0717,-501.5344 2751.1977,-493.6034"/>
<polygon fill="#000000" stroke="#000000" points="2752.6831,-496.7751 2760.5111,-489.6355 2749.9394,-490.3352 2752.6831,-496.7751"/>
<text text-anchor="middle" x="1530" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- study_admin -->
<g id="node6" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M2345.5,-351.5C2345.5,-351.5 2671.5,-351.5 2671.5,-351.5 2677.5,-351.5 2683.5,-357.5 2683.5,-363.5 2683.5,-363.5 2683.5,-500.5 2683.5,-500.5 2683.5,-506.5 2677.5,-512.5 2671.5,-512.5 2671.5,-512.5 2345.5,-512.5 2345.5,-512.5 2339.5,-512.5 2333.5,-506.5 2333.5,-500.5 2333.5,-500.5 2333.5,-363.5 2333.5,-363.5 2333.5,-357.5 2339.5,-351.5 2345.5,-351.5"/>
<text text-anchor="middle" x="2387.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="2441.5,-351.5 2441.5,-512.5 "/>
<text text-anchor="middle" x="2452" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2462.5,-351.5 2462.5,-512.5 "/>
<text text-anchor="middle" x="2562.5" y="-497.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="2462.5,-489.5 2662.5,-489.5 "/>
<text text-anchor="middle" x="2562.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="2462.5,-466.5 2662.5,-466.5 "/>
<text text-anchor="middle" x="2562.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="2462.5,-443.5 2662.5,-443.5 "/>
<text text-anchor="middle" x="2562.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="2462.5,-420.5 2662.5,-420.5 "/>
<text text-anchor="middle" x="2562.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="2462.5,-397.5 2662.5,-397.5 "/>
<text text-anchor="middle" x="2562.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="2462.5,-374.5 2662.5,-374.5 "/>
<text text-anchor="middle" x="2562.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="2662.5,-351.5 2662.5,-512.5 "/>
<text text-anchor="middle" x="2673" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge4" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2683.7603,-354.7256C2686.6941,-353.4717 2689.6091,-352.229 2692.5,-351 2781.7984,-313.0366 2880.7403,-272.2163 2966.2006,-237.3455"/>
<polygon fill="#000000" stroke="#000000" points="2967.5499,-240.5752 2975.4877,-233.5578 2964.9064,-234.0935 2967.5499,-240.5752"/>
<text text-anchor="middle" x="2816" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- sequencing_file -->
<g id="node7" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M1842,-1214.5C1842,-1214.5 2311,-1214.5 2311,-1214.5 2317,-1214.5 2323,-1220.5 2323,-1226.5 2323,-1226.5 2323,-1800.5 2323,-1800.5 2323,-1806.5 2317,-1812.5 2311,-1812.5 2311,-1812.5 1842,-1812.5 1842,-1812.5 1836,-1812.5 1830,-1806.5 1830,-1800.5 1830,-1800.5 1830,-1226.5 1830,-1226.5 1830,-1220.5 1836,-1214.5 1842,-1214.5"/>
<text text-anchor="middle" x="1894" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="1958,-1214.5 1958,-1812.5 "/>
<text text-anchor="middle" x="1968.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1979,-1214.5 1979,-1812.5 "/>
<text text-anchor="middle" x="2140.5" y="-1797.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="1979,-1789.5 2302,-1789.5 "/>
<text text-anchor="middle" x="2140.5" y="-1774.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1979,-1766.5 2302,-1766.5 "/>
<text text-anchor="middle" x="2140.5" y="-1751.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1979,-1743.5 2302,-1743.5 "/>
<text text-anchor="middle" x="2140.5" y="-1728.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="1979,-1720.5 2302,-1720.5 "/>
<text text-anchor="middle" x="2140.5" y="-1705.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="1979,-1697.5 2302,-1697.5 "/>
<text text-anchor="middle" x="2140.5" y="-1682.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1979,-1674.5 2302,-1674.5 "/>
<text text-anchor="middle" x="2140.5" y="-1659.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="1979,-1651.5 2302,-1651.5 "/>
<text text-anchor="middle" x="2140.5" y="-1636.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1979,-1628.5 2302,-1628.5 "/>
<text text-anchor="middle" x="2140.5" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1979,-1605.5 2302,-1605.5 "/>
<text text-anchor="middle" x="2140.5" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1979,-1582.5 2302,-1582.5 "/>
<text text-anchor="middle" x="2140.5" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1979,-1559.5 2302,-1559.5 "/>
<text text-anchor="middle" x="2140.5" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1979,-1536.5 2302,-1536.5 "/>
<text text-anchor="middle" x="2140.5" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1979,-1513.5 2302,-1513.5 "/>
<text text-anchor="middle" x="2140.5" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="1979,-1490.5 2302,-1490.5 "/>
<text text-anchor="middle" x="2140.5" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="1979,-1467.5 2302,-1467.5 "/>
<text text-anchor="middle" x="2140.5" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="1979,-1444.5 2302,-1444.5 "/>
<text text-anchor="middle" x="2140.5" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="1979,-1421.5 2302,-1421.5 "/>
<text text-anchor="middle" x="2140.5" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="1979,-1398.5 2302,-1398.5 "/>
<text text-anchor="middle" x="2140.5" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="1979,-1375.5 2302,-1375.5 "/>
<text text-anchor="middle" x="2140.5" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1979,-1352.5 2302,-1352.5 "/>
<text text-anchor="middle" x="2140.5" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="1979,-1329.5 2302,-1329.5 "/>
<text text-anchor="middle" x="2140.5" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="1979,-1306.5 2302,-1306.5 "/>
<text text-anchor="middle" x="2140.5" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="1979,-1283.5 2302,-1283.5 "/>
<text text-anchor="middle" x="2140.5" y="-1268.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="1979,-1260.5 2302,-1260.5 "/>
<text text-anchor="middle" x="2140.5" y="-1245.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="1979,-1237.5 2302,-1237.5 "/>
<text text-anchor="middle" x="2140.5" y="-1222.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 1 properties</text>
<polyline fill="none" stroke="#000000" points="2302,-1214.5 2302,-1812.5 "/>
<text text-anchor="middle" x="2312.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2323.4105,-1218.4527C2326.0903,-1216.9279 2328.7868,-1215.4431 2331.5,-1214 2447.1987,-1152.4634 2493.9174,-1192.0061 2624.5,-1181 2660.0965,-1177.9998 2914.4614,-1180.6837 2945.5,-1163 2985.7143,-1140.0886 3019.4622,-1105.4421 3047.1254,-1067.7464"/>
<polygon fill="#000000" stroke="#000000" points="3050.3111,-1069.3103 3053.2977,-1059.1451 3044.6239,-1065.2291 3050.3111,-1069.3103"/>
<text text-anchor="middle" x="2691" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- follow_up -->
<g id="node8" class="node">
<title>follow_up</title>
<path fill="none" stroke="#000000" d="M2562,-760C2562,-760 2925,-760 2925,-760 2931,-760 2937,-766 2937,-772 2937,-772 2937,-955 2937,-955 2937,-961 2931,-967 2925,-967 2925,-967 2562,-967 2562,-967 2556,-967 2550,-961 2550,-955 2550,-955 2550,-772 2550,-772 2550,-766 2556,-760 2562,-760"/>
<text text-anchor="middle" x="2592.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
<polyline fill="none" stroke="#000000" points="2635,-760 2635,-967 "/>
<text text-anchor="middle" x="2645.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2656,-760 2656,-967 "/>
<text text-anchor="middle" x="2786" y="-951.8" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event</text>
<polyline fill="none" stroke="#000000" points="2656,-944 2916,-944 "/>
<text text-anchor="middle" x="2786" y="-928.8" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity</text>
<polyline fill="none" stroke="#000000" points="2656,-921 2916,-921 "/>
<text text-anchor="middle" x="2786" y="-905.8" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity_method_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2656,-898 2916,-898 "/>
<text text-anchor="middle" x="2786" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_follow_up</text>
<polyline fill="none" stroke="#000000" points="2656,-875 2916,-875 "/>
<text text-anchor="middle" x="2786" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_response</text>
<polyline fill="none" stroke="#000000" points="2656,-852 2916,-852 "/>
<text text-anchor="middle" x="2786" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_category</text>
<polyline fill="none" stroke="#000000" points="2656,-829 2916,-829 "/>
<text text-anchor="middle" x="2786" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_id</text>
<polyline fill="none" stroke="#000000" points="2656,-806 2916,-806 "/>
<text text-anchor="middle" x="2786" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_other</text>
<polyline fill="none" stroke="#000000" points="2656,-783 2916,-783 "/>
<text text-anchor="middle" x="2786" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">risk_factor</text>
<polyline fill="none" stroke="#000000" points="2916,-760 2916,-967 "/>
<text text-anchor="middle" x="2926.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2772.7996,-759.8706C2795.6126,-679.1838 2826.617,-569.5248 2846.3466,-499.7433"/>
<polygon fill="#000000" stroke="#000000" points="2849.8206,-500.3202 2849.1734,-489.7452 2843.0847,-498.4157 2849.8206,-500.3202"/>
<text text-anchor="middle" x="2881.5" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- pdx -->
<g id="node9" class="node">
<title>pdx</title>
<path fill="none" stroke="#000000" d="M2353,-1398.5C2353,-1398.5 2682,-1398.5 2682,-1398.5 2688,-1398.5 2694,-1404.5 2694,-1410.5 2694,-1410.5 2694,-1616.5 2694,-1616.5 2694,-1622.5 2688,-1628.5 2682,-1628.5 2682,-1628.5 2353,-1628.5 2353,-1628.5 2347,-1628.5 2341,-1622.5 2341,-1616.5 2341,-1616.5 2341,-1410.5 2341,-1410.5 2341,-1404.5 2347,-1398.5 2353,-1398.5"/>
<text text-anchor="middle" x="2362.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
<polyline fill="none" stroke="#000000" points="2384,-1398.5 2384,-1628.5 "/>
<text text-anchor="middle" x="2394.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2405,-1398.5 2405,-1628.5 "/>
<text text-anchor="middle" x="2539" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_site</text>
<polyline fill="none" stroke="#000000" points="2405,-1605.5 2673,-1605.5 "/>
<text text-anchor="middle" x="2539" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_type</text>
<polyline fill="none" stroke="#000000" points="2405,-1582.5 2673,-1582.5 "/>
<text text-anchor="middle" x="2539" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_id</text>
<polyline fill="none" stroke="#000000" points="2405,-1559.5 2673,-1559.5 "/>
<text text-anchor="middle" x="2539" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">mouse_strain</text>
<polyline fill="none" stroke="#000000" points="2405,-1536.5 2673,-1536.5 "/>
<text text-anchor="middle" x="2539" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx_id</text>
<polyline fill="none" stroke="#000000" points="2405,-1513.5 2673,-1513.5 "/>
<text text-anchor="middle" x="2539" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">strain_immune_system_humanized</text>
<polyline fill="none" stroke="#000000" points="2405,-1490.5 2673,-1490.5 "/>
<text text-anchor="middle" x="2539" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_characterization_method</text>
<polyline fill="none" stroke="#000000" points="2405,-1467.5 2673,-1467.5 "/>
<text text-anchor="middle" x="2539" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_not_mus_or_ebv_origin</text>
<polyline fill="none" stroke="#000000" points="2405,-1444.5 2673,-1444.5 "/>
<text text-anchor="middle" x="2539" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_preparation</text>
<polyline fill="none" stroke="#000000" points="2405,-1421.5 2673,-1421.5 "/>
<text text-anchor="middle" x="2539" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_humanization</text>
<polyline fill="none" stroke="#000000" points="2673,-1398.5 2673,-1628.5 "/>
<text text-anchor="middle" x="2683.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2561.6292,-1398.2106C2591.8662,-1334.4143 2638.2271,-1259.1295 2702.5,-1214 2747.6566,-1182.2931 2899.753,-1193.849 2945.5,-1163 2982.4254,-1138.0998 3014.3474,-1103.9189 3041.1961,-1067.5358"/>
<polygon fill="#000000" stroke="#000000" points="3044.169,-1069.3979 3047.2007,-1059.2461 3038.4999,-1065.2916 3044.169,-1069.3979"/>
<text text-anchor="middle" x="2905.5" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3019.5933,-667.7989C2990.3705,-622.8314 2959.389,-575.2343 2930.5,-531 2923.5119,-520.2999 2916.0853,-508.9595 2908.8452,-497.9207"/>
<polygon fill="#000000" stroke="#000000" points="2911.7676,-495.9945 2903.3554,-489.5536 2905.9149,-499.8346 2911.7676,-495.9945"/>
<text text-anchor="middle" x="2973" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- medical_history -->
<g id="node11" class="node">
<title>medical_history</title>
<path fill="none" stroke="#000000" d="M1754.5,-829C1754.5,-829 2108.5,-829 2108.5,-829 2114.5,-829 2120.5,-835 2120.5,-841 2120.5,-841 2120.5,-886 2120.5,-886 2120.5,-892 2114.5,-898 2108.5,-898 2108.5,-898 1754.5,-898 1754.5,-898 1748.5,-898 1742.5,-892 1742.5,-886 1742.5,-886 1742.5,-841 1742.5,-841 1742.5,-835 1748.5,-829 1754.5,-829"/>
<text text-anchor="middle" x="1808" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
<polyline fill="none" stroke="#000000" points="1873.5,-829 1873.5,-898 "/>
<text text-anchor="middle" x="1884" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1894.5,-829 1894.5,-898 "/>
<text text-anchor="middle" x="1997" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_category</text>
<polyline fill="none" stroke="#000000" points="1894.5,-875 2099.5,-875 "/>
<text text-anchor="middle" x="1997" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_condition</text>
<polyline fill="none" stroke="#000000" points="1894.5,-852 2099.5,-852 "/>
<text text-anchor="middle" x="1997" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_id</text>
<polyline fill="none" stroke="#000000" points="2099.5,-829 2099.5,-898 "/>
<text text-anchor="middle" x="2110" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1943.094,-828.8899C1966.7215,-764.3373 2027.0542,-626.468 2129.5,-564 2236.7563,-498.5987 2570.8917,-544.5063 2692.5,-513 2711.3127,-508.126 2730.5776,-501.2392 2749.1018,-493.5164"/>
<polygon fill="#000000" stroke="#000000" points="2750.5998,-496.6825 2758.4216,-489.5362 2747.8505,-490.245 2750.5998,-496.6825"/>
<text text-anchor="middle" x="2331.5" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- synonym -->
<g id="node12" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M3758,-1490.5C3758,-1490.5 4059,-1490.5 4059,-1490.5 4065,-1490.5 4071,-1496.5 4071,-1502.5 4071,-1502.5 4071,-1524.5 4071,-1524.5 4071,-1530.5 4065,-1536.5 4059,-1536.5 4059,-1536.5 3758,-1536.5 3758,-1536.5 3752,-1536.5 3746,-1530.5 3746,-1524.5 3746,-1524.5 3746,-1502.5 3746,-1502.5 3746,-1496.5 3752,-1490.5 3758,-1490.5"/>
<text text-anchor="middle" x="3786" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="3826,-1490.5 3826,-1536.5 "/>
<text text-anchor="middle" x="3836.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3847,-1490.5 3847,-1536.5 "/>
<text text-anchor="middle" x="3948.5" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="3847,-1513.5 4050,-1513.5 "/>
<text text-anchor="middle" x="3948.5" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="4050,-1490.5 4050,-1536.5 "/>
<text text-anchor="middle" x="4060.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3903.3176,-1490.1914C3888.8954,-1431.5377 3842.2631,-1277.9578 3737.5,-1214 3660.2289,-1166.8261 3407.4545,-1243.6886 3330.5,-1196 3281.961,-1165.9205 3245.2108,-1118.1723 3217.8264,-1068.1415"/>
<polygon fill="#000000" stroke="#000000" points="3220.7974,-1066.2753 3212.9945,-1059.1084 3214.625,-1069.577 3220.7974,-1066.2753"/>
<text text-anchor="middle" x="3373" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3902.8132,-1490.3781C3887.3475,-1432.8359 3838.7266,-1282.8889 3737.5,-1214 3704.6467,-1191.642 3410.4335,-1192.22 3383.5,-1163 3293.1116,-1064.9382 3436.6629,-662.2692 3346.5,-564 3328.1214,-543.969 3251.9863,-552.1228 3225.5,-546 3163.6326,-531.6983 3097.0466,-511.8996 3038.1688,-492.8109"/>
<polygon fill="#000000" stroke="#000000" points="3039.0017,-489.4013 3028.4094,-489.6306 3036.8328,-496.0568 3039.0017,-489.4013"/>
<text text-anchor="middle" x="3426" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge6" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3909.749,-1490.3038C3917.9252,-1334.5592 3961.284,-444.4394 3889.5,-351 3829.451,-272.8357 3584.4121,-215.8125 3399.5193,-182.8794"/>
<polygon fill="#000000" stroke="#000000" points="3400.1105,-179.4297 3389.6538,-181.1347 3398.8915,-186.3227 3400.1105,-179.4297"/>
<text text-anchor="middle" x="3966" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- imaging_file -->
<g id="node13" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M2724,-1318C2724,-1318 3065,-1318 3065,-1318 3071,-1318 3077,-1324 3077,-1330 3077,-1330 3077,-1697 3077,-1697 3077,-1703 3071,-1709 3065,-1709 3065,-1709 2724,-1709 2724,-1709 2718,-1709 2712,-1703 2712,-1697 2712,-1697 2712,-1330 2712,-1330 2712,-1324 2718,-1318 2724,-1318"/>
<text text-anchor="middle" x="2764" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="2816,-1318 2816,-1709 "/>
<text text-anchor="middle" x="2826.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2837,-1318 2837,-1709 "/>
<text text-anchor="middle" x="2946.5" y="-1693.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2837,-1686 3056,-1686 "/>
<text text-anchor="middle" x="2946.5" y="-1670.8" font-family="Times,serif" font-size="14.00" fill="#000000">deidentification_method</text>
<polyline fill="none" stroke="#000000" points="2837,-1663 3056,-1663 "/>
<text text-anchor="middle" x="2946.5" y="-1647.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2837,-1640 3056,-1640 "/>
<text text-anchor="middle" x="2946.5" y="-1624.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2837,-1617 3056,-1617 "/>
<text text-anchor="middle" x="2946.5" y="-1601.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2837,-1594 3056,-1594 "/>
<text text-anchor="middle" x="2946.5" y="-1578.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2837,-1571 3056,-1571 "/>
<text text-anchor="middle" x="2946.5" y="-1555.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2837,-1548 3056,-1548 "/>
<text text-anchor="middle" x="2946.5" y="-1532.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2837,-1525 3056,-1525 "/>
<text text-anchor="middle" x="2946.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">fixation_embedding_method</text>
<polyline fill="none" stroke="#000000" points="2837,-1502 3056,-1502 "/>
<text text-anchor="middle" x="2946.5" y="-1486.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="2837,-1479 3056,-1479 "/>
<text text-anchor="middle" x="2946.5" y="-1463.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file_id</text>
<polyline fill="none" stroke="#000000" points="2837,-1456 3056,-1456 "/>
<text text-anchor="middle" x="2946.5" y="-1440.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="2837,-1433 3056,-1433 "/>
<text text-anchor="middle" x="2946.5" y="-1417.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="2837,-1410 3056,-1410 "/>
<text text-anchor="middle" x="2946.5" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">magnification</text>
<polyline fill="none" stroke="#000000" points="2837,-1387 3056,-1387 "/>
<text text-anchor="middle" x="2946.5" y="-1371.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2837,-1364 3056,-1364 "/>
<text text-anchor="middle" x="2946.5" y="-1348.8" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="2837,-1341 3056,-1341 "/>
<text text-anchor="middle" x="2946.5" y="-1325.8" font-family="Times,serif" font-size="14.00" fill="#000000">staining_method</text>
<polyline fill="none" stroke="#000000" points="3056,-1318 3056,-1709 "/>
<text text-anchor="middle" x="3066.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2920.5434,-1317.8515C2929.7968,-1272.1007 2942.1409,-1224.1495 2958.5,-1181 2972.8489,-1143.1527 2991.5672,-1104.6466 3011.624,-1068.1126"/>
<polygon fill="#000000" stroke="#000000" points="3014.6857,-1069.8084 3016.4721,-1059.3653 3008.5632,-1066.4151 3014.6857,-1069.8084"/>
<text text-anchor="middle" x="3013" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- exposure -->
<g id="node14" class="node">
<title>exposure</title>
<path fill="none" stroke="#000000" d="M12,-622C12,-622 423,-622 423,-622 429,-622 435,-628 435,-634 435,-634 435,-1093 435,-1093 435,-1099 429,-1105 423,-1105 423,-1105 12,-1105 12,-1105 6,-1105 0,-1099 0,-1093 0,-1093 0,-634 0,-634 0,-628 6,-622 12,-622"/>
<text text-anchor="middle" x="41" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
<polyline fill="none" stroke="#000000" points="82,-622 82,-1105 "/>
<text text-anchor="middle" x="92.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="103,-622 103,-1105 "/>
<text text-anchor="middle" x="258.5" y="-1089.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_days_per_week</text>
<polyline fill="none" stroke="#000000" points="103,-1082 414,-1082 "/>
<text text-anchor="middle" x="258.5" y="-1066.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_drinks_per_day</text>
<polyline fill="none" stroke="#000000" points="103,-1059 414,-1059 "/>
<text text-anchor="middle" x="258.5" y="-1043.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_history</text>
<polyline fill="none" stroke="#000000" points="103,-1036 414,-1036 "/>
<text text-anchor="middle" x="258.5" y="-1020.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_intensity</text>
<polyline fill="none" stroke="#000000" points="103,-1013 414,-1013 "/>
<text text-anchor="middle" x="258.5" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000">asbestos_exposure</text>
<polyline fill="none" stroke="#000000" points="103,-990 414,-990 "/>
<text text-anchor="middle" x="258.5" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">cigarettes_per_day</text>
<polyline fill="none" stroke="#000000" points="103,-967 414,-967 "/>
<text text-anchor="middle" x="258.5" y="-951.8" font-family="Times,serif" font-size="14.00" fill="#000000">coal_dust_exposure</text>
<polyline fill="none" stroke="#000000" points="103,-944 414,-944 "/>
<text text-anchor="middle" x="258.5" y="-928.8" font-family="Times,serif" font-size="14.00" fill="#000000">environmental_tobacco_smoke_exposure</text>
<polyline fill="none" stroke="#000000" points="103,-921 414,-921 "/>
<text text-anchor="middle" x="258.5" y="-905.8" font-family="Times,serif" font-size="14.00" fill="#000000">exposure_id</text>
<polyline fill="none" stroke="#000000" points="103,-898 414,-898 "/>
<text text-anchor="middle" x="258.5" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">pack_years_smoked</text>
<polyline fill="none" stroke="#000000" points="103,-875 414,-875 "/>
<text text-anchor="middle" x="258.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">radon_exposure</text>
<polyline fill="none" stroke="#000000" points="103,-852 414,-852 "/>
<text text-anchor="middle" x="258.5" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">respirable_crystalline_silica_exposure</text>
<polyline fill="none" stroke="#000000" points="103,-829 414,-829 "/>
<text text-anchor="middle" x="258.5" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">smoking_frequency</text>
<polyline fill="none" stroke="#000000" points="103,-806 414,-806 "/>
<text text-anchor="middle" x="258.5" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">start_days_from_index</text>
<polyline fill="none" stroke="#000000" points="103,-783 414,-783 "/>
<text text-anchor="middle" x="258.5" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">time_between_waking_and_first_smoke</text>
<polyline fill="none" stroke="#000000" points="103,-760 414,-760 "/>
<text text-anchor="middle" x="258.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_onset_year</text>
<polyline fill="none" stroke="#000000" points="103,-737 414,-737 "/>
<text text-anchor="middle" x="258.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_quit_year</text>
<polyline fill="none" stroke="#000000" points="103,-714 414,-714 "/>
<text text-anchor="middle" x="258.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_status</text>
<polyline fill="none" stroke="#000000" points="103,-691 414,-691 "/>
<text text-anchor="middle" x="258.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_smoke_exposure</text>
<polyline fill="none" stroke="#000000" points="103,-668 414,-668 "/>
<text text-anchor="middle" x="258.5" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_tobacco_used</text>
<polyline fill="none" stroke="#000000" points="103,-645 414,-645 "/>
<text text-anchor="middle" x="258.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">years_smoked</text>
<polyline fill="none" stroke="#000000" points="414,-622 414,-1105 "/>
<text text-anchor="middle" x="424.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M367.9941,-621.7634C390.7432,-599.166 415.9416,-579.1116 443.5,-564 606.9018,-474.399 675.3271,-539.2542 861.5,-531 963.1273,-526.4942 2593.3112,-535.583 2692.5,-513 2712.2302,-508.5079 2732.3829,-501.5557 2751.636,-493.5714"/>
<polygon fill="#000000" stroke="#000000" points="2753.1832,-496.7166 2761.0094,-489.5751 2750.4378,-490.2774 2753.1832,-496.7166"/>
<text text-anchor="middle" x="905" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge15" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2930.4146,-374.2526C2952.9323,-354.2211 2979.3761,-330.6969 3006.5122,-306.557"/>
<polygon fill="#000000" stroke="#000000" points="3009.0364,-308.996 3014.1816,-299.7344 3004.3837,-303.7659 3009.0364,-308.996"/>
<text text-anchor="middle" x="3037" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- therapeutic_procedure -->
<g id="node16" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M465,-794.5C465,-794.5 866,-794.5 866,-794.5 872,-794.5 878,-800.5 878,-806.5 878,-806.5 878,-920.5 878,-920.5 878,-926.5 872,-932.5 866,-932.5 866,-932.5 465,-932.5 465,-932.5 459,-932.5 453,-926.5 453,-920.5 453,-920.5 453,-806.5 453,-806.5 453,-800.5 459,-794.5 465,-794.5"/>
<text text-anchor="middle" x="543.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="634,-794.5 634,-932.5 "/>
<text text-anchor="middle" x="644.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="655,-794.5 655,-932.5 "/>
<text text-anchor="middle" x="756" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment_end</text>
<polyline fill="none" stroke="#000000" points="655,-909.5 857,-909.5 "/>
<text text-anchor="middle" x="756" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment_start</text>
<polyline fill="none" stroke="#000000" points="655,-886.5 857,-886.5 "/>
<text text-anchor="middle" x="756" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="655,-863.5 857,-863.5 "/>
<text text-anchor="middle" x="756" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure_id</text>
<polyline fill="none" stroke="#000000" points="655,-840.5 857,-840.5 "/>
<text text-anchor="middle" x="756" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="655,-817.5 857,-817.5 "/>
<text text-anchor="middle" x="756" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="857,-794.5 857,-932.5 "/>
<text text-anchor="middle" x="867.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M695.9082,-794.4796C731.0689,-723.6635 796.0696,-616.6356 887.5,-564 1061.3804,-463.8988 2496.9172,-557.7439 2692.5,-513 2712.2255,-508.4873 2732.3758,-501.5244 2751.6278,-493.5356"/>
<polygon fill="#000000" stroke="#000000" points="2753.1758,-496.6805 2761.0008,-489.5377 2750.4294,-490.2417 2753.1758,-496.6805"/>
<text text-anchor="middle" x="1121.5" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- study_arm -->
<g id="node17" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M3571,-386C3571,-386 3868,-386 3868,-386 3874,-386 3880,-392 3880,-398 3880,-398 3880,-466 3880,-466 3880,-472 3874,-478 3868,-478 3868,-478 3571,-478 3571,-478 3565,-478 3559,-472 3559,-466 3559,-466 3559,-398 3559,-398 3559,-392 3565,-386 3571,-386"/>
<text text-anchor="middle" x="3605" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="3651,-386 3651,-478 "/>
<text text-anchor="middle" x="3661.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3672,-386 3672,-478 "/>
<text text-anchor="middle" x="3765.5" y="-462.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="3672,-455 3859,-455 "/>
<text text-anchor="middle" x="3765.5" y="-439.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="3672,-432 3859,-432 "/>
<text text-anchor="middle" x="3765.5" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="3672,-409 3859,-409 "/>
<text text-anchor="middle" x="3765.5" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm_id</text>
<polyline fill="none" stroke="#000000" points="3859,-386 3859,-478 "/>
<text text-anchor="middle" x="3869.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge24" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3631.7268,-385.9068C3568.461,-352.6834 3480.2086,-306.3386 3398.6582,-263.5132"/>
<polygon fill="#000000" stroke="#000000" points="3400.2527,-260.3974 3389.772,-258.8467 3396.9982,-266.5948 3400.2527,-260.3974"/>
<text text-anchor="middle" x="3578" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node18" class="node">
<title>single_cell_sequencing_file</title>
<path fill="none" stroke="#000000" d="M3107,-1214.5C3107,-1214.5 3716,-1214.5 3716,-1214.5 3722,-1214.5 3728,-1220.5 3728,-1226.5 3728,-1226.5 3728,-1800.5 3728,-1800.5 3728,-1806.5 3722,-1812.5 3716,-1812.5 3716,-1812.5 3107,-1812.5 3107,-1812.5 3101,-1812.5 3095,-1806.5 3095,-1800.5 3095,-1800.5 3095,-1226.5 3095,-1226.5 3095,-1220.5 3101,-1214.5 3107,-1214.5"/>
<text text-anchor="middle" x="3201" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
<polyline fill="none" stroke="#000000" points="3307,-1214.5 3307,-1812.5 "/>
<text text-anchor="middle" x="3317.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3328,-1214.5 3328,-1812.5 "/>
<text text-anchor="middle" x="3517.5" y="-1797.3" font-family="Times,serif" font-size="14.00" fill="#000000">Cell_Barcode</text>
<polyline fill="none" stroke="#000000" points="3328,-1789.5 3707,-1789.5 "/>
<text text-anchor="middle" x="3517.5" y="-1774.3" font-family="Times,serif" font-size="14.00" fill="#000000">Cryopreserved_Cells_in_Sample</text>
<polyline fill="none" stroke="#000000" points="3328,-1766.5 3707,-1766.5 "/>
<text text-anchor="middle" x="3517.5" y="-1751.3" font-family="Times,serif" font-size="14.00" fill="#000000">Dissociation_Method</text>
<polyline fill="none" stroke="#000000" points="3328,-1743.5 3707,-1743.5 "/>
<text text-anchor="middle" x="3517.5" y="-1728.3" font-family="Times,serif" font-size="14.00" fill="#000000">End_Bias</text>
<polyline fill="none" stroke="#000000" points="3328,-1720.5 3707,-1720.5 "/>
<text text-anchor="middle" x="3517.5" y="-1705.3" font-family="Times,serif" font-size="14.00" fill="#000000">Input_Cells_and_Nuclei</text>
<polyline fill="none" stroke="#000000" points="3328,-1697.5 3707,-1697.5 "/>
<text text-anchor="middle" x="3517.5" y="-1682.3" font-family="Times,serif" font-size="14.00" fill="#000000">Library_Construction_Method</text>
<polyline fill="none" stroke="#000000" points="3328,-1674.5 3707,-1674.5 "/>
<text text-anchor="middle" x="3517.5" y="-1659.3" font-family="Times,serif" font-size="14.00" fill="#000000">Library_Preparation_Date</text>
<polyline fill="none" stroke="#000000" points="3328,-1651.5 3707,-1651.5 "/>
<text text-anchor="middle" x="3517.5" y="-1636.3" font-family="Times,serif" font-size="14.00" fill="#000000">Nucleic_Acid_Capture_Date</text>
<polyline fill="none" stroke="#000000" points="3328,-1628.5 3707,-1628.5 "/>
<text text-anchor="middle" x="3517.5" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">Paired_End</text>
<polyline fill="none" stroke="#000000" points="3328,-1605.5 3707,-1605.5 "/>
<text text-anchor="middle" x="3517.5" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">Protocols_Link</text>
<polyline fill="none" stroke="#000000" points="3328,-1582.5 3707,-1582.5 "/>
<text text-anchor="middle" x="3517.5" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">Read1</text>
<polyline fill="none" stroke="#000000" points="3328,-1559.5 3707,-1559.5 "/>
<text text-anchor="middle" x="3517.5" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">Read2</text>
<polyline fill="none" stroke="#000000" points="3328,-1536.5 3707,-1536.5 "/>
<text text-anchor="middle" x="3517.5" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Feature_barcoding</text>
<polyline fill="none" stroke="#000000" points="3328,-1513.5 3707,-1513.5 "/>
<text text-anchor="middle" x="3517.5" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Oligo_dT_Poly_dT</text>
<polyline fill="none" stroke="#000000" points="3328,-1490.5 3707,-1490.5 "/>
<text text-anchor="middle" x="3517.5" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Random</text>
<polyline fill="none" stroke="#000000" points="3328,-1467.5 3707,-1467.5 "/>
<text text-anchor="middle" x="3517.5" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">Sequencing_Library_Construction_Date</text>
<polyline fill="none" stroke="#000000" points="3328,-1444.5 3707,-1444.5 "/>
<text text-anchor="middle" x="3517.5" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">Single_Cell_Dissociation_Date</text>
<polyline fill="none" stroke="#000000" points="3328,-1421.5 3707,-1421.5 "/>
<text text-anchor="middle" x="3517.5" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">Single_Cell_Isolation_Method</text>
<polyline fill="none" stroke="#000000" points="3328,-1398.5 3707,-1398.5 "/>
<text text-anchor="middle" x="3517.5" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">Spike_In</text>
<polyline fill="none" stroke="#000000" points="3328,-1375.5 3707,-1375.5 "/>
<text text-anchor="middle" x="3517.5" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">Total_Number_of_Input_Cells</text>
<polyline fill="none" stroke="#000000" points="3328,-1352.5 3707,-1352.5 "/>
<text text-anchor="middle" x="3517.5" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">UMI</text>
<polyline fill="none" stroke="#000000" points="3328,-1329.5 3707,-1329.5 "/>
<text text-anchor="middle" x="3517.5" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="3328,-1306.5 3707,-1306.5 "/>
<text text-anchor="middle" x="3517.5" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">cDNA_Length</text>
<polyline fill="none" stroke="#000000" points="3328,-1283.5 3707,-1283.5 "/>
<text text-anchor="middle" x="3517.5" y="-1268.3" font-family="Times,serif" font-size="14.00" fill="#000000">cDNA_Offset</text>
<polyline fill="none" stroke="#000000" points="3328,-1260.5 3707,-1260.5 "/>
<text text-anchor="middle" x="3517.5" y="-1245.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="3328,-1237.5 3707,-1237.5 "/>
<text text-anchor="middle" x="3517.5" y="-1222.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 24 properties</text>
<polyline fill="none" stroke="#000000" points="3707,-1214.5 3707,-1812.5 "/>
<text text-anchor="middle" x="3717.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3098.735,-1214.2678C3095.8166,-1208.2387 3093.0666,-1202.1485 3090.5,-1196 3073.9729,-1156.4074 3071.499,-1112.232 3076.3862,-1069.3431"/>
<polygon fill="#000000" stroke="#000000" points="3079.8678,-1069.7089 3077.6591,-1059.3468 3072.9239,-1068.8246 3079.8678,-1069.7089"/>
<text text-anchor="middle" x="3199" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node19" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M3489,-725.5C3489,-725.5 3862,-725.5 3862,-725.5 3868,-725.5 3874,-731.5 3874,-737.5 3874,-737.5 3874,-989.5 3874,-989.5 3874,-995.5 3868,-1001.5 3862,-1001.5 3862,-1001.5 3489,-1001.5 3489,-1001.5 3483,-1001.5 3477,-995.5 3477,-989.5 3477,-989.5 3477,-737.5 3477,-737.5 3477,-731.5 3483,-725.5 3489,-725.5"/>
<text text-anchor="middle" x="3560.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="3644,-725.5 3644,-1001.5 "/>
<text text-anchor="middle" x="3654.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3665,-725.5 3665,-1001.5 "/>
<text text-anchor="middle" x="3759" y="-986.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="3665,-978.5 3853,-978.5 "/>
<text text-anchor="middle" x="3759" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="3665,-955.5 3853,-955.5 "/>
<text text-anchor="middle" x="3759" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file_id</text>
<polyline fill="none" stroke="#000000" points="3665,-932.5 3853,-932.5 "/>
<text text-anchor="middle" x="3759" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="3665,-909.5 3853,-909.5 "/>
<text text-anchor="middle" x="3759" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="3665,-886.5 3853,-886.5 "/>
<text text-anchor="middle" x="3759" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="3665,-863.5 3853,-863.5 "/>
<text text-anchor="middle" x="3759" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="3665,-840.5 3853,-840.5 "/>
<text text-anchor="middle" x="3759" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="3665,-817.5 3853,-817.5 "/>
<text text-anchor="middle" x="3759" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="3665,-794.5 3853,-794.5 "/>
<text text-anchor="middle" x="3759" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="3665,-771.5 3853,-771.5 "/>
<text text-anchor="middle" x="3759" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="3665,-748.5 3853,-748.5 "/>
<text text-anchor="middle" x="3759" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="3853,-725.5 3853,-1001.5 "/>
<text text-anchor="middle" x="3863.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3611.5448,-725.2271C3576.3645,-665.2751 3526.6772,-600.5481 3462.5,-564 3420.4525,-540.0545 3291.2718,-561.6949 3245.5,-546 3233.9558,-542.0416 3233.6223,-536.0232 3222.5,-531 3164.8916,-504.9824 3098.9003,-484.3505 3039.4528,-468.8037"/>
<polygon fill="#000000" stroke="#000000" points="3040.1456,-465.3678 3029.5879,-466.2544 3038.3942,-472.1451 3040.1456,-465.3678"/>
<text text-anchor="middle" x="3375" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge13" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3637.8135,-725.4388C3611.722,-656.2022 3569.6677,-577.4099 3504.5,-531 3458.422,-498.1851 3424.9051,-545.3507 3378.5,-513 3308.7755,-464.3925 3261.5754,-382.8429 3231.0002,-309.339"/>
<polygon fill="#000000" stroke="#000000" points="3234.1889,-307.8895 3227.1678,-299.9551 3227.7085,-310.5361 3234.1889,-307.8895"/>
<text text-anchor="middle" x="3464.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- molecular_test -->
<g id="node20" class="node">
<title>molecular_test</title>
<path fill="none" stroke="#000000" d="M1324.5,-564.5C1324.5,-564.5 1712.5,-564.5 1712.5,-564.5 1718.5,-564.5 1724.5,-570.5 1724.5,-576.5 1724.5,-576.5 1724.5,-1150.5 1724.5,-1150.5 1724.5,-1156.5 1718.5,-1162.5 1712.5,-1162.5 1712.5,-1162.5 1324.5,-1162.5 1324.5,-1162.5 1318.5,-1162.5 1312.5,-1156.5 1312.5,-1150.5 1312.5,-1150.5 1312.5,-576.5 1312.5,-576.5 1312.5,-570.5 1318.5,-564.5 1324.5,-564.5"/>
<text text-anchor="middle" x="1374" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
<polyline fill="none" stroke="#000000" points="1435.5,-564.5 1435.5,-1162.5 "/>
<text text-anchor="middle" x="1446" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1456.5,-564.5 1456.5,-1162.5 "/>
<text text-anchor="middle" x="1580" y="-1147.3" font-family="Times,serif" font-size="14.00" fill="#000000">aa_change</text>
<polyline fill="none" stroke="#000000" points="1456.5,-1139.5 1703.5,-1139.5 "/>
<text text-anchor="middle" x="1580" y="-1124.3" font-family="Times,serif" font-size="14.00" fill="#000000">antigen</text>
<polyline fill="none" stroke="#000000" points="1456.5,-1116.5 1703.5,-1116.5 "/>
<text text-anchor="middle" x="1580" y="-1101.3" font-family="Times,serif" font-size="14.00" fill="#000000">biospecimen_type</text>
<polyline fill="none" stroke="#000000" points="1456.5,-1093.5 1703.5,-1093.5 "/>
<text text-anchor="middle" x="1580" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000">blood_test_normal_range_lower</text>
<polyline fill="none" stroke="#000000" points="1456.5,-1070.5 1703.5,-1070.5 "/>
<text text-anchor="middle" x="1580" y="-1055.3" font-family="Times,serif" font-size="14.00" fill="#000000">blood_test_normal_range_upper</text>
<polyline fill="none" stroke="#000000" points="1456.5,-1047.5 1703.5,-1047.5 "/>
<text text-anchor="middle" x="1580" y="-1032.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_count</text>
<polyline fill="none" stroke="#000000" points="1456.5,-1024.5 1703.5,-1024.5 "/>
<text text-anchor="middle" x="1580" y="-1009.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome</text>
<polyline fill="none" stroke="#000000" points="1456.5,-1001.5 1703.5,-1001.5 "/>
<text text-anchor="middle" x="1580" y="-986.3" font-family="Times,serif" font-size="14.00" fill="#000000">copy_number</text>
<polyline fill="none" stroke="#000000" points="1456.5,-978.5 1703.5,-978.5 "/>
<text text-anchor="middle" x="1580" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytoband</text>
<polyline fill="none" stroke="#000000" points="1456.5,-955.5 1703.5,-955.5 "/>
<text text-anchor="middle" x="1580" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">exon</text>
<polyline fill="none" stroke="#000000" points="1456.5,-932.5 1703.5,-932.5 "/>
<text text-anchor="middle" x="1580" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">gene_symbol</text>
<polyline fill="none" stroke="#000000" points="1456.5,-909.5 1703.5,-909.5 "/>
<text text-anchor="middle" x="1580" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">histone_family</text>
<polyline fill="none" stroke="#000000" points="1456.5,-886.5 1703.5,-886.5 "/>
<text text-anchor="middle" x="1580" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">histone_variant</text>
<polyline fill="none" stroke="#000000" points="1456.5,-863.5 1703.5,-863.5 "/>
<text text-anchor="middle" x="1580" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">intron</text>
<polyline fill="none" stroke="#000000" points="1456.5,-840.5 1703.5,-840.5 "/>
<text text-anchor="middle" x="1580" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
<polyline fill="none" stroke="#000000" points="1456.5,-817.5 1703.5,-817.5 "/>
<text text-anchor="middle" x="1580" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">loci_abnormal_count</text>
<polyline fill="none" stroke="#000000" points="1456.5,-794.5 1703.5,-794.5 "/>
<text text-anchor="middle" x="1580" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">loci_count</text>
<polyline fill="none" stroke="#000000" points="1456.5,-771.5 1703.5,-771.5 "/>
<text text-anchor="middle" x="1580" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">locus</text>
<polyline fill="none" stroke="#000000" points="1456.5,-748.5 1703.5,-748.5 "/>
<text text-anchor="middle" x="1580" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">mismatch_repair_mutation</text>
<polyline fill="none" stroke="#000000" points="1456.5,-725.5 1703.5,-725.5 "/>
<text text-anchor="middle" x="1580" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_analysis_method</text>
<polyline fill="none" stroke="#000000" points="1456.5,-702.5 1703.5,-702.5 "/>
<text text-anchor="middle" x="1580" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_consequence</text>
<polyline fill="none" stroke="#000000" points="1456.5,-679.5 1703.5,-679.5 "/>
<text text-anchor="middle" x="1580" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test_id</text>
<polyline fill="none" stroke="#000000" points="1456.5,-656.5 1703.5,-656.5 "/>
<text text-anchor="middle" x="1580" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathogenicity</text>
<polyline fill="none" stroke="#000000" points="1456.5,-633.5 1703.5,-633.5 "/>
<text text-anchor="middle" x="1580" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">ploidy</text>
<polyline fill="none" stroke="#000000" points="1456.5,-610.5 1703.5,-610.5 "/>
<text text-anchor="middle" x="1580" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">second_exon</text>
<polyline fill="none" stroke="#000000" points="1456.5,-587.5 1703.5,-587.5 "/>
<text text-anchor="middle" x="1580" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 11 properties</text>
<polyline fill="none" stroke="#000000" points="1703.5,-564.5 1703.5,-1162.5 "/>
<text text-anchor="middle" x="1714" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1724.8718,-569.2353C1727.7191,-567.4355 1730.5952,-565.6894 1733.5,-564 1854.0363,-493.8961 1906.3689,-540.2792 2045.5,-531 2117.2573,-526.2142 2622.5242,-529.5951 2692.5,-513 2711.9117,-508.3964 2731.7532,-501.4837 2750.7506,-493.6013"/>
<polygon fill="#000000" stroke="#000000" points="2752.175,-496.799 2760.0033,-489.6598 2749.4315,-490.359 2752.175,-496.799"/>
<text text-anchor="middle" x="2109.5" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- study_personnel -->
<g id="node22" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M3949,-374.5C3949,-374.5 4256,-374.5 4256,-374.5 4262,-374.5 4268,-380.5 4268,-386.5 4268,-386.5 4268,-477.5 4268,-477.5 4268,-483.5 4262,-489.5 4256,-489.5 4256,-489.5 3949,-489.5 3949,-489.5 3943,-489.5 3937,-483.5 3937,-477.5 3937,-477.5 3937,-386.5 3937,-386.5 3937,-380.5 3943,-374.5 3949,-374.5"/>
<text text-anchor="middle" x="4004" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="4071,-374.5 4071,-489.5 "/>
<text text-anchor="middle" x="4081.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4092,-374.5 4092,-489.5 "/>
<text text-anchor="middle" x="4169.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="4092,-466.5 4247,-466.5 "/>
<text text-anchor="middle" x="4169.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="4092,-443.5 4247,-443.5 "/>
<text text-anchor="middle" x="4169.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="4092,-420.5 4247,-420.5 "/>
<text text-anchor="middle" x="4169.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="4092,-397.5 4247,-397.5 "/>
<text text-anchor="middle" x="4169.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="4247,-374.5 4247,-489.5 "/>
<text text-anchor="middle" x="4257.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M4024.6119,-374.4773C3994.0417,-354.1401 3957.8529,-332.6937 3922.5,-318 3753.7825,-247.8762 3550.6849,-204.4246 3399.9758,-179.3268"/>
<polygon fill="#000000" stroke="#000000" points="3400.1078,-175.8013 3389.6713,-177.6258 3398.9677,-182.7079 3400.1078,-175.8013"/>
<text text-anchor="middle" x="4023" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
</g>
</svg>
</div>
