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
<svg width="4751pt" height="1988pt"
 viewBox="0.00 0.00 4750.50 1988.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1984)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1984 4746.5,-1984 4746.5,4 -4,4"/>
<!-- follow_up -->
<g id="node1" class="node">
<title>follow_up</title>
<path fill="none" stroke="#000000" d="M3105,-927C3105,-927 3468,-927 3468,-927 3474,-927 3480,-933 3480,-939 3480,-939 3480,-1122 3480,-1122 3480,-1128 3474,-1134 3468,-1134 3468,-1134 3105,-1134 3105,-1134 3099,-1134 3093,-1128 3093,-1122 3093,-1122 3093,-939 3093,-939 3093,-933 3099,-927 3105,-927"/>
<text text-anchor="middle" x="3135.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
<polyline fill="none" stroke="#000000" points="3178,-927 3178,-1134 "/>
<text text-anchor="middle" x="3188.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3199,-927 3199,-1134 "/>
<text text-anchor="middle" x="3329" y="-1118.8" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event</text>
<polyline fill="none" stroke="#000000" points="3199,-1111 3459,-1111 "/>
<text text-anchor="middle" x="3329" y="-1095.8" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity</text>
<polyline fill="none" stroke="#000000" points="3199,-1088 3459,-1088 "/>
<text text-anchor="middle" x="3329" y="-1072.8" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity_method_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="3199,-1065 3459,-1065 "/>
<text text-anchor="middle" x="3329" y="-1049.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_follow_up</text>
<polyline fill="none" stroke="#000000" points="3199,-1042 3459,-1042 "/>
<text text-anchor="middle" x="3329" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_response</text>
<polyline fill="none" stroke="#000000" points="3199,-1019 3459,-1019 "/>
<text text-anchor="middle" x="3329" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_category</text>
<polyline fill="none" stroke="#000000" points="3199,-996 3459,-996 "/>
<text text-anchor="middle" x="3329" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_id</text>
<polyline fill="none" stroke="#000000" points="3199,-973 3459,-973 "/>
<text text-anchor="middle" x="3329" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_other</text>
<polyline fill="none" stroke="#000000" points="3199,-950 3459,-950 "/>
<text text-anchor="middle" x="3329" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">risk_factor</text>
<polyline fill="none" stroke="#000000" points="3459,-927 3459,-1134 "/>
<text text-anchor="middle" x="3469.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node12" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M2733.5,-564.5C2733.5,-564.5 3037.5,-564.5 3037.5,-564.5 3043.5,-564.5 3049.5,-570.5 3049.5,-576.5 3049.5,-576.5 3049.5,-667.5 3049.5,-667.5 3049.5,-673.5 3043.5,-679.5 3037.5,-679.5 3037.5,-679.5 2733.5,-679.5 2733.5,-679.5 2727.5,-679.5 2721.5,-673.5 2721.5,-667.5 2721.5,-667.5 2721.5,-576.5 2721.5,-576.5 2721.5,-570.5 2727.5,-564.5 2733.5,-564.5"/>
<text text-anchor="middle" x="2769.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="2817.5,-564.5 2817.5,-679.5 "/>
<text text-anchor="middle" x="2828" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2838.5,-564.5 2838.5,-679.5 "/>
<text text-anchor="middle" x="2933.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="2838.5,-656.5 3028.5,-656.5 "/>
<text text-anchor="middle" x="2933.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="2838.5,-633.5 3028.5,-633.5 "/>
<text text-anchor="middle" x="2933.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="2838.5,-610.5 3028.5,-610.5 "/>
<text text-anchor="middle" x="2933.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="2838.5,-587.5 3028.5,-587.5 "/>
<text text-anchor="middle" x="2933.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="3028.5,-564.5 3028.5,-679.5 "/>
<text text-anchor="middle" x="3039" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3232.6811,-926.7295C3196.6358,-864.4461 3144.6604,-786.753 3083.5,-731 3064.6003,-713.7713 3042.4907,-698.2503 3020.0305,-684.6841"/>
<polygon fill="#000000" stroke="#000000" points="3021.7993,-681.6639 3011.4112,-679.5809 3018.233,-687.6873 3021.7993,-681.6639"/>
<text text-anchor="middle" x="3104.5" y="-701.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- study_personnel -->
<g id="node2" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M1121,-374.5C1121,-374.5 1428,-374.5 1428,-374.5 1434,-374.5 1440,-380.5 1440,-386.5 1440,-386.5 1440,-477.5 1440,-477.5 1440,-483.5 1434,-489.5 1428,-489.5 1428,-489.5 1121,-489.5 1121,-489.5 1115,-489.5 1109,-483.5 1109,-477.5 1109,-477.5 1109,-386.5 1109,-386.5 1109,-380.5 1115,-374.5 1121,-374.5"/>
<text text-anchor="middle" x="1176" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="1243,-374.5 1243,-489.5 "/>
<text text-anchor="middle" x="1253.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1264,-374.5 1264,-489.5 "/>
<text text-anchor="middle" x="1341.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="1264,-466.5 1419,-466.5 "/>
<text text-anchor="middle" x="1341.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="1264,-443.5 1419,-443.5 "/>
<text text-anchor="middle" x="1341.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="1264,-420.5 1419,-420.5 "/>
<text text-anchor="middle" x="1341.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="1264,-397.5 1419,-397.5 "/>
<text text-anchor="middle" x="1341.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="1419,-374.5 1419,-489.5 "/>
<text text-anchor="middle" x="1429.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node8" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M2149.5,-.5C2149.5,-.5 2539.5,-.5 2539.5,-.5 2545.5,-.5 2551.5,-6.5 2551.5,-12.5 2551.5,-12.5 2551.5,-287.5 2551.5,-287.5 2551.5,-293.5 2545.5,-299.5 2539.5,-299.5 2539.5,-299.5 2149.5,-299.5 2149.5,-299.5 2143.5,-299.5 2137.5,-293.5 2137.5,-287.5 2137.5,-287.5 2137.5,-12.5 2137.5,-12.5 2137.5,-6.5 2143.5,-.5 2149.5,-.5"/>
<text text-anchor="middle" x="2165.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="2193.5,-.5 2193.5,-299.5 "/>
<text text-anchor="middle" x="2204" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2214.5,-.5 2214.5,-299.5 "/>
<text text-anchor="middle" x="2372.5" y="-284.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="2214.5,-276.5 2530.5,-276.5 "/>
<text text-anchor="middle" x="2372.5" y="-261.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="2214.5,-253.5 2530.5,-253.5 "/>
<text text-anchor="middle" x="2372.5" y="-238.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_shorthand</text>
<polyline fill="none" stroke="#000000" points="2214.5,-230.5 2530.5,-230.5 "/>
<text text-anchor="middle" x="2372.5" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="2214.5,-207.5 2530.5,-207.5 "/>
<text text-anchor="middle" x="2372.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="2214.5,-184.5 2530.5,-184.5 "/>
<text text-anchor="middle" x="2372.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="2214.5,-161.5 2530.5,-161.5 "/>
<text text-anchor="middle" x="2372.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="2214.5,-138.5 2530.5,-138.5 "/>
<text text-anchor="middle" x="2372.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="2214.5,-115.5 2530.5,-115.5 "/>
<text text-anchor="middle" x="2372.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="2214.5,-92.5 2530.5,-92.5 "/>
<text text-anchor="middle" x="2372.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="2214.5,-69.5 2530.5,-69.5 "/>
<text text-anchor="middle" x="2372.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="2214.5,-46.5 2530.5,-46.5 "/>
<text text-anchor="middle" x="2372.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="2214.5,-23.5 2530.5,-23.5 "/>
<text text-anchor="middle" x="2372.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="2530.5,-.5 2530.5,-299.5 "/>
<text text-anchor="middle" x="2541" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge7" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1389.1329,-374.424C1408.6537,-365.8434 1428.9435,-357.6589 1448.5,-351 1674.8555,-273.9276 1943.5453,-218.1696 2127.2591,-185.2071"/>
<polygon fill="#000000" stroke="#000000" points="2128.0839,-188.6153 2137.3124,-183.4109 2126.8527,-181.7244 2128.0839,-188.6153"/>
<text text-anchor="middle" x="1613" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- study_funding -->
<g id="node3" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M1470,-386C1470,-386 1849,-386 1849,-386 1855,-386 1861,-392 1861,-398 1861,-398 1861,-466 1861,-466 1861,-472 1855,-478 1849,-478 1849,-478 1470,-478 1470,-478 1464,-478 1458,-472 1458,-466 1458,-466 1458,-398 1458,-398 1458,-392 1464,-386 1470,-386"/>
<text text-anchor="middle" x="1517.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="1577,-386 1577,-478 "/>
<text text-anchor="middle" x="1587.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1598,-386 1598,-478 "/>
<text text-anchor="middle" x="1719" y="-462.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="1598,-455 1840,-455 "/>
<text text-anchor="middle" x="1719" y="-439.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="1598,-432 1840,-432 "/>
<text text-anchor="middle" x="1719" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="1598,-409 1840,-409 "/>
<text text-anchor="middle" x="1719" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding_id</text>
<polyline fill="none" stroke="#000000" points="1840,-386 1840,-478 "/>
<text text-anchor="middle" x="1850.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge26" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1746.9364,-385.9234C1789.4585,-364.2234 1841.6154,-338.6378 1889.5,-318 1966.1605,-284.9601 2051.6796,-252.3162 2127.7005,-224.7161"/>
<polygon fill="#000000" stroke="#000000" points="2129.1906,-227.899 2137.4011,-221.2028 2126.8069,-221.3173 2129.1906,-227.899"/>
<text text-anchor="middle" x="1951.5" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- sequencing_file -->
<g id="node4" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M858,-1393C858,-1393 1327,-1393 1327,-1393 1333,-1393 1339,-1399 1339,-1405 1339,-1405 1339,-1956 1339,-1956 1339,-1962 1333,-1968 1327,-1968 1327,-1968 858,-1968 858,-1968 852,-1968 846,-1962 846,-1956 846,-1956 846,-1405 846,-1405 846,-1399 852,-1393 858,-1393"/>
<text text-anchor="middle" x="910" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="974,-1393 974,-1968 "/>
<text text-anchor="middle" x="984.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="995,-1393 995,-1968 "/>
<text text-anchor="middle" x="1156.5" y="-1952.8" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="995,-1945 1318,-1945 "/>
<text text-anchor="middle" x="1156.5" y="-1929.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="995,-1922 1318,-1922 "/>
<text text-anchor="middle" x="1156.5" y="-1906.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="995,-1899 1318,-1899 "/>
<text text-anchor="middle" x="1156.5" y="-1883.8" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="995,-1876 1318,-1876 "/>
<text text-anchor="middle" x="1156.5" y="-1860.8" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="995,-1853 1318,-1853 "/>
<text text-anchor="middle" x="1156.5" y="-1837.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="995,-1830 1318,-1830 "/>
<text text-anchor="middle" x="1156.5" y="-1814.8" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="995,-1807 1318,-1807 "/>
<text text-anchor="middle" x="1156.5" y="-1791.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="995,-1784 1318,-1784 "/>
<text text-anchor="middle" x="1156.5" y="-1768.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="995,-1761 1318,-1761 "/>
<text text-anchor="middle" x="1156.5" y="-1745.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="995,-1738 1318,-1738 "/>
<text text-anchor="middle" x="1156.5" y="-1722.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="995,-1715 1318,-1715 "/>
<text text-anchor="middle" x="1156.5" y="-1699.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="995,-1692 1318,-1692 "/>
<text text-anchor="middle" x="1156.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="995,-1669 1318,-1669 "/>
<text text-anchor="middle" x="1156.5" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="995,-1646 1318,-1646 "/>
<text text-anchor="middle" x="1156.5" y="-1630.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="995,-1623 1318,-1623 "/>
<text text-anchor="middle" x="1156.5" y="-1607.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="995,-1600 1318,-1600 "/>
<text text-anchor="middle" x="1156.5" y="-1584.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="995,-1577 1318,-1577 "/>
<text text-anchor="middle" x="1156.5" y="-1561.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="995,-1554 1318,-1554 "/>
<text text-anchor="middle" x="1156.5" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="995,-1531 1318,-1531 "/>
<text text-anchor="middle" x="1156.5" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="995,-1508 1318,-1508 "/>
<text text-anchor="middle" x="1156.5" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="995,-1485 1318,-1485 "/>
<text text-anchor="middle" x="1156.5" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="995,-1462 1318,-1462 "/>
<text text-anchor="middle" x="1156.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="995,-1439 1318,-1439 "/>
<text text-anchor="middle" x="1156.5" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="995,-1416 1318,-1416 "/>
<text text-anchor="middle" x="1156.5" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="1318,-1393 1318,-1968 "/>
<text text-anchor="middle" x="1328.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node9" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1448.5,-950C1448.5,-950 1762.5,-950 1762.5,-950 1768.5,-950 1774.5,-956 1774.5,-962 1774.5,-962 1774.5,-1099 1774.5,-1099 1774.5,-1105 1768.5,-1111 1762.5,-1111 1762.5,-1111 1448.5,-1111 1448.5,-1111 1442.5,-1111 1436.5,-1105 1436.5,-1099 1436.5,-1099 1436.5,-962 1436.5,-962 1436.5,-956 1442.5,-950 1448.5,-950"/>
<text text-anchor="middle" x="1470.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1504.5,-950 1504.5,-1111 "/>
<text text-anchor="middle" x="1515" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1525.5,-950 1525.5,-1111 "/>
<text text-anchor="middle" x="1639.5" y="-1095.8" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="1525.5,-1088 1753.5,-1088 "/>
<text text-anchor="middle" x="1639.5" y="-1072.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1525.5,-1065 1753.5,-1065 "/>
<text text-anchor="middle" x="1639.5" y="-1049.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1525.5,-1042 1753.5,-1042 "/>
<text text-anchor="middle" x="1639.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1525.5,-1019 1753.5,-1019 "/>
<text text-anchor="middle" x="1639.5" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1525.5,-996 1753.5,-996 "/>
<text text-anchor="middle" x="1639.5" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1525.5,-973 1753.5,-973 "/>
<text text-anchor="middle" x="1639.5" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="1753.5,-950 1753.5,-1111 "/>
<text text-anchor="middle" x="1764" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1334.4009,-1392.6585C1338.7549,-1388.7015 1343.1227,-1384.8122 1347.5,-1381 1379.2976,-1353.3072 1398.1544,-1360.2789 1427.5,-1330 1486.8814,-1268.7301 1534.8675,-1184.0459 1565.9865,-1120.3544"/>
<polygon fill="#000000" stroke="#000000" points="1569.2519,-1121.6412 1570.4548,-1111.1149 1562.9501,-1118.5936 1569.2519,-1121.6412"/>
<text text-anchor="middle" x="1472" y="-1351.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- family_relationship -->
<g id="node5" class="node">
<title>family_relationship</title>
<path fill="none" stroke="#000000" d="M3854,-984.5C3854,-984.5 4223,-984.5 4223,-984.5 4229,-984.5 4235,-990.5 4235,-996.5 4235,-996.5 4235,-1064.5 4235,-1064.5 4235,-1070.5 4229,-1076.5 4223,-1076.5 4223,-1076.5 3854,-1076.5 3854,-1076.5 3848,-1076.5 3842,-1070.5 3842,-1064.5 3842,-1064.5 3842,-996.5 3842,-996.5 3842,-990.5 3848,-984.5 3854,-984.5"/>
<text text-anchor="middle" x="3919" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
<polyline fill="none" stroke="#000000" points="3996,-984.5 3996,-1076.5 "/>
<text text-anchor="middle" x="4006.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4017,-984.5 4017,-1076.5 "/>
<text text-anchor="middle" x="4115.5" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_id</text>
<polyline fill="none" stroke="#000000" points="4017,-1053.5 4214,-1053.5 "/>
<text text-anchor="middle" x="4115.5" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship_id</text>
<polyline fill="none" stroke="#000000" points="4017,-1030.5 4214,-1030.5 "/>
<text text-anchor="middle" x="4115.5" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">related_to_participant_id</text>
<polyline fill="none" stroke="#000000" points="4017,-1007.5 4214,-1007.5 "/>
<text text-anchor="middle" x="4115.5" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">relationship</text>
<polyline fill="none" stroke="#000000" points="4214,-984.5 4214,-1076.5 "/>
<text text-anchor="middle" x="4224.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M4016.2145,-984.2706C3983.0943,-919.8147 3915.2439,-802.7978 3827.5,-731 3799.3157,-707.9378 3787.7764,-707.044 3752.5,-698 3625.8919,-665.5407 3274.4468,-642.2439 3059.8747,-630.5498"/>
<polygon fill="#000000" stroke="#000000" points="3059.9367,-627.0481 3049.7619,-630.0017 3059.5578,-634.0379 3059.9367,-627.0481"/>
<text text-anchor="middle" x="3879" y="-701.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- publication -->
<g id="node6" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M1891.5,-414C1891.5,-414 2101.5,-414 2101.5,-414 2107.5,-414 2113.5,-420 2113.5,-426 2113.5,-426 2113.5,-438 2113.5,-438 2113.5,-444 2107.5,-450 2101.5,-450 2101.5,-450 1891.5,-450 1891.5,-450 1885.5,-450 1879.5,-444 1879.5,-438 1879.5,-438 1879.5,-426 1879.5,-426 1879.5,-420 1885.5,-414 1891.5,-414"/>
<text text-anchor="middle" x="1928" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="1976.5,-414 1976.5,-450 "/>
<text text-anchor="middle" x="1987" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1997.5,-414 1997.5,-450 "/>
<text text-anchor="middle" x="2045" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="2092.5,-414 2092.5,-450 "/>
<text text-anchor="middle" x="2103" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge11" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1996.707,-413.8291C1997.8856,-389.5244 2003.2483,-346.2266 2025.5,-318 2052.9697,-283.1544 2089.6866,-254.7249 2128.4232,-231.83"/>
<polygon fill="#000000" stroke="#000000" points="2130.3385,-234.7656 2137.2437,-226.73 2126.8346,-228.7056 2130.3385,-234.7656"/>
<text text-anchor="middle" x="2076.5" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- medical_history -->
<g id="node7" class="node">
<title>medical_history</title>
<path fill="none" stroke="#000000" d="M1052.5,-996C1052.5,-996 1406.5,-996 1406.5,-996 1412.5,-996 1418.5,-1002 1418.5,-1008 1418.5,-1008 1418.5,-1053 1418.5,-1053 1418.5,-1059 1412.5,-1065 1406.5,-1065 1406.5,-1065 1052.5,-1065 1052.5,-1065 1046.5,-1065 1040.5,-1059 1040.5,-1053 1040.5,-1053 1040.5,-1008 1040.5,-1008 1040.5,-1002 1046.5,-996 1052.5,-996"/>
<text text-anchor="middle" x="1106" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
<polyline fill="none" stroke="#000000" points="1171.5,-996 1171.5,-1065 "/>
<text text-anchor="middle" x="1182" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1192.5,-996 1192.5,-1065 "/>
<text text-anchor="middle" x="1295" y="-1049.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_category</text>
<polyline fill="none" stroke="#000000" points="1192.5,-1042 1397.5,-1042 "/>
<text text-anchor="middle" x="1295" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_condition</text>
<polyline fill="none" stroke="#000000" points="1192.5,-1019 1397.5,-1019 "/>
<text text-anchor="middle" x="1295" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_id</text>
<polyline fill="none" stroke="#000000" points="1397.5,-996 1397.5,-1065 "/>
<text text-anchor="middle" x="1408" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1240.8108,-995.8214C1264.0488,-930.8329 1323.8769,-791.8035 1427.5,-731 1535.8456,-667.4255 2348.4495,-636.9951 2711.3531,-626.4644"/>
<polygon fill="#000000" stroke="#000000" points="2711.5338,-629.9608 2721.4287,-626.1738 2711.332,-622.9637 2711.5338,-629.9608"/>
<text text-anchor="middle" x="1617.5" y="-701.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge14" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1640.6131,-949.9507C1671.5474,-885.4441 1721.3252,-795.4061 1783.5,-731 1907.9126,-602.1225 2019.1699,-659.3243 2122.5,-513 2165.1599,-452.59 2125.9672,-416.3966 2160.5,-351 2168.256,-336.312 2177.3455,-321.8723 2187.2567,-307.8889"/>
<polygon fill="#000000" stroke="#000000" points="2190.1498,-309.8612 2193.1834,-299.7099 2184.4815,-305.7538 2190.1498,-309.8612"/>
<text text-anchor="middle" x="2145" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1629.2444,-949.9999C1654.858,-878.9338 1703.166,-779.3351 1783.5,-731 1853.8459,-688.6745 2074.3994,-738.3041 2152.5,-713 2164.1099,-709.2385 2164.0039,-702.096 2175.5,-698 2270.9133,-664.005 2533.8114,-642.4429 2711.4989,-631.2928"/>
<polygon fill="#000000" stroke="#000000" points="2711.7203,-634.7859 2721.4836,-630.6715 2711.2855,-627.7994 2711.7203,-634.7859"/>
<text text-anchor="middle" x="2212" y="-701.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_admin -->
<g id="node10" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M2181.5,-351.5C2181.5,-351.5 2507.5,-351.5 2507.5,-351.5 2513.5,-351.5 2519.5,-357.5 2519.5,-363.5 2519.5,-363.5 2519.5,-500.5 2519.5,-500.5 2519.5,-506.5 2513.5,-512.5 2507.5,-512.5 2507.5,-512.5 2181.5,-512.5 2181.5,-512.5 2175.5,-512.5 2169.5,-506.5 2169.5,-500.5 2169.5,-500.5 2169.5,-363.5 2169.5,-363.5 2169.5,-357.5 2175.5,-351.5 2181.5,-351.5"/>
<text text-anchor="middle" x="2223.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="2277.5,-351.5 2277.5,-512.5 "/>
<text text-anchor="middle" x="2288" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2298.5,-351.5 2298.5,-512.5 "/>
<text text-anchor="middle" x="2398.5" y="-497.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="2298.5,-489.5 2498.5,-489.5 "/>
<text text-anchor="middle" x="2398.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="2298.5,-466.5 2498.5,-466.5 "/>
<text text-anchor="middle" x="2398.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="2298.5,-443.5 2498.5,-443.5 "/>
<text text-anchor="middle" x="2398.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="2298.5,-420.5 2498.5,-420.5 "/>
<text text-anchor="middle" x="2398.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="2298.5,-397.5 2498.5,-397.5 "/>
<text text-anchor="middle" x="2398.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="2298.5,-374.5 2498.5,-374.5 "/>
<text text-anchor="middle" x="2398.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="2498.5,-351.5 2498.5,-512.5 "/>
<text text-anchor="middle" x="2509" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge4" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2344.5,-351.1901C2344.5,-338.0934 2344.5,-324.1439 2344.5,-309.933"/>
<polygon fill="#000000" stroke="#000000" points="2348.0001,-309.5475 2344.5,-299.5475 2341.0001,-309.5475 2348.0001,-309.5475"/>
<text text-anchor="middle" x="2401" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node11" class="node">
<title>single_cell_sequencing_file</title>
<path fill="none" stroke="#000000" d="M1369,-1381.5C1369,-1381.5 1978,-1381.5 1978,-1381.5 1984,-1381.5 1990,-1387.5 1990,-1393.5 1990,-1393.5 1990,-1967.5 1990,-1967.5 1990,-1973.5 1984,-1979.5 1978,-1979.5 1978,-1979.5 1369,-1979.5 1369,-1979.5 1363,-1979.5 1357,-1973.5 1357,-1967.5 1357,-1967.5 1357,-1393.5 1357,-1393.5 1357,-1387.5 1363,-1381.5 1369,-1381.5"/>
<text text-anchor="middle" x="1463" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
<polyline fill="none" stroke="#000000" points="1569,-1381.5 1569,-1979.5 "/>
<text text-anchor="middle" x="1579.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1590,-1381.5 1590,-1979.5 "/>
<text text-anchor="middle" x="1779.5" y="-1964.3" font-family="Times,serif" font-size="14.00" fill="#000000">Cell_Barcode</text>
<polyline fill="none" stroke="#000000" points="1590,-1956.5 1969,-1956.5 "/>
<text text-anchor="middle" x="1779.5" y="-1941.3" font-family="Times,serif" font-size="14.00" fill="#000000">Cryopreserved_Cells_in_Sample</text>
<polyline fill="none" stroke="#000000" points="1590,-1933.5 1969,-1933.5 "/>
<text text-anchor="middle" x="1779.5" y="-1918.3" font-family="Times,serif" font-size="14.00" fill="#000000">Dissociation_Method</text>
<polyline fill="none" stroke="#000000" points="1590,-1910.5 1969,-1910.5 "/>
<text text-anchor="middle" x="1779.5" y="-1895.3" font-family="Times,serif" font-size="14.00" fill="#000000">End_Bias</text>
<polyline fill="none" stroke="#000000" points="1590,-1887.5 1969,-1887.5 "/>
<text text-anchor="middle" x="1779.5" y="-1872.3" font-family="Times,serif" font-size="14.00" fill="#000000">Input_Cells_and_Nuclei</text>
<polyline fill="none" stroke="#000000" points="1590,-1864.5 1969,-1864.5 "/>
<text text-anchor="middle" x="1779.5" y="-1849.3" font-family="Times,serif" font-size="14.00" fill="#000000">Library_Construction_Method</text>
<polyline fill="none" stroke="#000000" points="1590,-1841.5 1969,-1841.5 "/>
<text text-anchor="middle" x="1779.5" y="-1826.3" font-family="Times,serif" font-size="14.00" fill="#000000">Library_Preparation_Date</text>
<polyline fill="none" stroke="#000000" points="1590,-1818.5 1969,-1818.5 "/>
<text text-anchor="middle" x="1779.5" y="-1803.3" font-family="Times,serif" font-size="14.00" fill="#000000">Nucleic_Acid_Capture_Date</text>
<polyline fill="none" stroke="#000000" points="1590,-1795.5 1969,-1795.5 "/>
<text text-anchor="middle" x="1779.5" y="-1780.3" font-family="Times,serif" font-size="14.00" fill="#000000">Paired_End</text>
<polyline fill="none" stroke="#000000" points="1590,-1772.5 1969,-1772.5 "/>
<text text-anchor="middle" x="1779.5" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">Protocols_Link</text>
<polyline fill="none" stroke="#000000" points="1590,-1749.5 1969,-1749.5 "/>
<text text-anchor="middle" x="1779.5" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">Read1</text>
<polyline fill="none" stroke="#000000" points="1590,-1726.5 1969,-1726.5 "/>
<text text-anchor="middle" x="1779.5" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">Read2</text>
<polyline fill="none" stroke="#000000" points="1590,-1703.5 1969,-1703.5 "/>
<text text-anchor="middle" x="1779.5" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Feature_barcoding</text>
<polyline fill="none" stroke="#000000" points="1590,-1680.5 1969,-1680.5 "/>
<text text-anchor="middle" x="1779.5" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Oligo_dT_Poly_dT</text>
<polyline fill="none" stroke="#000000" points="1590,-1657.5 1969,-1657.5 "/>
<text text-anchor="middle" x="1779.5" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Random</text>
<polyline fill="none" stroke="#000000" points="1590,-1634.5 1969,-1634.5 "/>
<text text-anchor="middle" x="1779.5" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">Sequencing_Library_Construction_Date</text>
<polyline fill="none" stroke="#000000" points="1590,-1611.5 1969,-1611.5 "/>
<text text-anchor="middle" x="1779.5" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">Single_Cell_Dissociation_Date</text>
<polyline fill="none" stroke="#000000" points="1590,-1588.5 1969,-1588.5 "/>
<text text-anchor="middle" x="1779.5" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">Single_Cell_Isolation_Method</text>
<polyline fill="none" stroke="#000000" points="1590,-1565.5 1969,-1565.5 "/>
<text text-anchor="middle" x="1779.5" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">Spike_In</text>
<polyline fill="none" stroke="#000000" points="1590,-1542.5 1969,-1542.5 "/>
<text text-anchor="middle" x="1779.5" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">Total_Number_of_Input_Cells</text>
<polyline fill="none" stroke="#000000" points="1590,-1519.5 1969,-1519.5 "/>
<text text-anchor="middle" x="1779.5" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">UMI</text>
<polyline fill="none" stroke="#000000" points="1590,-1496.5 1969,-1496.5 "/>
<text text-anchor="middle" x="1779.5" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="1590,-1473.5 1969,-1473.5 "/>
<text text-anchor="middle" x="1779.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">cDNA_Length</text>
<polyline fill="none" stroke="#000000" points="1590,-1450.5 1969,-1450.5 "/>
<text text-anchor="middle" x="1779.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">cDNA_Offset</text>
<polyline fill="none" stroke="#000000" points="1590,-1427.5 1969,-1427.5 "/>
<text text-anchor="middle" x="1779.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1590,-1404.5 1969,-1404.5 "/>
<text text-anchor="middle" x="1779.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 23 properties</text>
<polyline fill="none" stroke="#000000" points="1969,-1381.5 1969,-1979.5 "/>
<text text-anchor="middle" x="1979.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge28" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1642.187,-1381.1842C1632.3068,-1286.7416 1622.1222,-1189.3882 1614.9983,-1121.2924"/>
<polygon fill="#000000" stroke="#000000" points="1618.4474,-1120.6225 1613.9258,-1111.041 1611.4854,-1121.3509 1618.4474,-1120.6225"/>
<text text-anchor="middle" x="1748" y="-1351.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge22" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2898.6658,-564.3012C2908.7077,-504.8478 2914.0734,-412.4267 2868.5,-351 2796.5772,-254.0581 2671.5511,-203.8705 2561.6617,-177.8883"/>
<polygon fill="#000000" stroke="#000000" points="2562.2862,-174.4405 2551.7551,-175.6013 2560.7116,-181.2611 2562.2862,-174.4405"/>
<text text-anchor="middle" x="2956" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_arm -->
<g id="node21" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M2550,-386C2550,-386 2847,-386 2847,-386 2853,-386 2859,-392 2859,-398 2859,-398 2859,-466 2859,-466 2859,-472 2853,-478 2847,-478 2847,-478 2550,-478 2550,-478 2544,-478 2538,-472 2538,-466 2538,-466 2538,-398 2538,-398 2538,-392 2544,-386 2550,-386"/>
<text text-anchor="middle" x="2584" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="2630,-386 2630,-478 "/>
<text text-anchor="middle" x="2640.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2651,-386 2651,-478 "/>
<text text-anchor="middle" x="2744.5" y="-462.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="2651,-455 2838,-455 "/>
<text text-anchor="middle" x="2744.5" y="-439.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="2651,-432 2838,-432 "/>
<text text-anchor="middle" x="2744.5" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="2651,-409 2838,-409 "/>
<text text-anchor="middle" x="2744.5" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm_id</text>
<polyline fill="none" stroke="#000000" points="2838,-386 2838,-478 "/>
<text text-anchor="middle" x="2848.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge21" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M2800.694,-564.3758C2793.615,-558.4562 2786.776,-552.2946 2780.5,-546 2762.8023,-528.2497 2746.0939,-506.3696 2732.4346,-486.5398"/>
<polygon fill="#000000" stroke="#000000" points="2735.2804,-484.5001 2726.7733,-478.1849 2729.4854,-488.4268 2735.2804,-484.5001"/>
<text text-anchor="middle" x="2831" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- methylation_array_file -->
<g id="node13" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M2020,-1565.5C2020,-1565.5 2387,-1565.5 2387,-1565.5 2393,-1565.5 2399,-1571.5 2399,-1577.5 2399,-1577.5 2399,-1783.5 2399,-1783.5 2399,-1789.5 2393,-1795.5 2387,-1795.5 2387,-1795.5 2020,-1795.5 2020,-1795.5 2014,-1795.5 2008,-1789.5 2008,-1783.5 2008,-1783.5 2008,-1577.5 2008,-1577.5 2008,-1571.5 2014,-1565.5 2020,-1565.5"/>
<text text-anchor="middle" x="2097" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="2186,-1565.5 2186,-1795.5 "/>
<text text-anchor="middle" x="2196.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2207,-1565.5 2207,-1795.5 "/>
<text text-anchor="middle" x="2292.5" y="-1780.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2207,-1772.5 2378,-1772.5 "/>
<text text-anchor="middle" x="2292.5" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2207,-1749.5 2378,-1749.5 "/>
<text text-anchor="middle" x="2292.5" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2207,-1726.5 2378,-1726.5 "/>
<text text-anchor="middle" x="2292.5" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2207,-1703.5 2378,-1703.5 "/>
<text text-anchor="middle" x="2292.5" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2207,-1680.5 2378,-1680.5 "/>
<text text-anchor="middle" x="2292.5" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2207,-1657.5 2378,-1657.5 "/>
<text text-anchor="middle" x="2292.5" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2207,-1634.5 2378,-1634.5 "/>
<text text-anchor="middle" x="2292.5" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2207,-1611.5 2378,-1611.5 "/>
<text text-anchor="middle" x="2292.5" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="2207,-1588.5 2378,-1588.5 "/>
<text text-anchor="middle" x="2292.5" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="2378,-1565.5 2378,-1795.5 "/>
<text text-anchor="middle" x="2388.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2151.0368,-1565.4087C2116.3955,-1501.8837 2065.0751,-1426.8054 1998.5,-1381 1946.5466,-1345.2547 1921.8704,-1362.5108 1860.5,-1348 1826.2982,-1339.9131 1811.8544,-1350.765 1783.5,-1330 1712.4234,-1277.9479 1664.606,-1188.1781 1636.5886,-1120.4582"/>
<polygon fill="#000000" stroke="#000000" points="1639.7745,-1119.001 1632.7663,-1111.0552 1633.2898,-1121.6371 1639.7745,-1119.001"/>
<text text-anchor="middle" x="2054" y="-1351.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- molecular_test -->
<g id="node14" class="node">
<title>molecular_test</title>
<path fill="none" stroke="#000000" d="M1804.5,-731.5C1804.5,-731.5 2192.5,-731.5 2192.5,-731.5 2198.5,-731.5 2204.5,-737.5 2204.5,-743.5 2204.5,-743.5 2204.5,-1317.5 2204.5,-1317.5 2204.5,-1323.5 2198.5,-1329.5 2192.5,-1329.5 2192.5,-1329.5 1804.5,-1329.5 1804.5,-1329.5 1798.5,-1329.5 1792.5,-1323.5 1792.5,-1317.5 1792.5,-1317.5 1792.5,-743.5 1792.5,-743.5 1792.5,-737.5 1798.5,-731.5 1804.5,-731.5"/>
<text text-anchor="middle" x="1854" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
<polyline fill="none" stroke="#000000" points="1915.5,-731.5 1915.5,-1329.5 "/>
<text text-anchor="middle" x="1926" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1936.5,-731.5 1936.5,-1329.5 "/>
<text text-anchor="middle" x="2060" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">aa_change</text>
<polyline fill="none" stroke="#000000" points="1936.5,-1306.5 2183.5,-1306.5 "/>
<text text-anchor="middle" x="2060" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">antigen</text>
<polyline fill="none" stroke="#000000" points="1936.5,-1283.5 2183.5,-1283.5 "/>
<text text-anchor="middle" x="2060" y="-1268.3" font-family="Times,serif" font-size="14.00" fill="#000000">biospecimen_type</text>
<polyline fill="none" stroke="#000000" points="1936.5,-1260.5 2183.5,-1260.5 "/>
<text text-anchor="middle" x="2060" y="-1245.3" font-family="Times,serif" font-size="14.00" fill="#000000">blood_test_normal_range_lower</text>
<polyline fill="none" stroke="#000000" points="1936.5,-1237.5 2183.5,-1237.5 "/>
<text text-anchor="middle" x="2060" y="-1222.3" font-family="Times,serif" font-size="14.00" fill="#000000">blood_test_normal_range_upper</text>
<polyline fill="none" stroke="#000000" points="1936.5,-1214.5 2183.5,-1214.5 "/>
<text text-anchor="middle" x="2060" y="-1199.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_count</text>
<polyline fill="none" stroke="#000000" points="1936.5,-1191.5 2183.5,-1191.5 "/>
<text text-anchor="middle" x="2060" y="-1176.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome</text>
<polyline fill="none" stroke="#000000" points="1936.5,-1168.5 2183.5,-1168.5 "/>
<text text-anchor="middle" x="2060" y="-1153.3" font-family="Times,serif" font-size="14.00" fill="#000000">copy_number</text>
<polyline fill="none" stroke="#000000" points="1936.5,-1145.5 2183.5,-1145.5 "/>
<text text-anchor="middle" x="2060" y="-1130.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytoband</text>
<polyline fill="none" stroke="#000000" points="1936.5,-1122.5 2183.5,-1122.5 "/>
<text text-anchor="middle" x="2060" y="-1107.3" font-family="Times,serif" font-size="14.00" fill="#000000">exon</text>
<polyline fill="none" stroke="#000000" points="1936.5,-1099.5 2183.5,-1099.5 "/>
<text text-anchor="middle" x="2060" y="-1084.3" font-family="Times,serif" font-size="14.00" fill="#000000">gene_symbol</text>
<polyline fill="none" stroke="#000000" points="1936.5,-1076.5 2183.5,-1076.5 "/>
<text text-anchor="middle" x="2060" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">histone_family</text>
<polyline fill="none" stroke="#000000" points="1936.5,-1053.5 2183.5,-1053.5 "/>
<text text-anchor="middle" x="2060" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">histone_variant</text>
<polyline fill="none" stroke="#000000" points="1936.5,-1030.5 2183.5,-1030.5 "/>
<text text-anchor="middle" x="2060" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">intron</text>
<polyline fill="none" stroke="#000000" points="1936.5,-1007.5 2183.5,-1007.5 "/>
<text text-anchor="middle" x="2060" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
<polyline fill="none" stroke="#000000" points="1936.5,-984.5 2183.5,-984.5 "/>
<text text-anchor="middle" x="2060" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">loci_abnormal_count</text>
<polyline fill="none" stroke="#000000" points="1936.5,-961.5 2183.5,-961.5 "/>
<text text-anchor="middle" x="2060" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">loci_count</text>
<polyline fill="none" stroke="#000000" points="1936.5,-938.5 2183.5,-938.5 "/>
<text text-anchor="middle" x="2060" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">locus</text>
<polyline fill="none" stroke="#000000" points="1936.5,-915.5 2183.5,-915.5 "/>
<text text-anchor="middle" x="2060" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">mismatch_repair_mutation</text>
<polyline fill="none" stroke="#000000" points="1936.5,-892.5 2183.5,-892.5 "/>
<text text-anchor="middle" x="2060" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_analysis_method</text>
<polyline fill="none" stroke="#000000" points="1936.5,-869.5 2183.5,-869.5 "/>
<text text-anchor="middle" x="2060" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_consequence</text>
<polyline fill="none" stroke="#000000" points="1936.5,-846.5 2183.5,-846.5 "/>
<text text-anchor="middle" x="2060" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test_id</text>
<polyline fill="none" stroke="#000000" points="1936.5,-823.5 2183.5,-823.5 "/>
<text text-anchor="middle" x="2060" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathogenicity</text>
<polyline fill="none" stroke="#000000" points="1936.5,-800.5 2183.5,-800.5 "/>
<text text-anchor="middle" x="2060" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">ploidy</text>
<polyline fill="none" stroke="#000000" points="1936.5,-777.5 2183.5,-777.5 "/>
<text text-anchor="middle" x="2060" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">second_exon</text>
<polyline fill="none" stroke="#000000" points="1936.5,-754.5 2183.5,-754.5 "/>
<text text-anchor="middle" x="2060" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 11 properties</text>
<polyline fill="none" stroke="#000000" points="2183.5,-731.5 2183.5,-1329.5 "/>
<text text-anchor="middle" x="2194" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2204.6094,-736.733C2207.5435,-734.7656 2210.5071,-732.8535 2213.5,-731 2294.5943,-680.7781 2540.5735,-650.555 2711.2775,-635.077"/>
<polygon fill="#000000" stroke="#000000" points="2711.7403,-638.5497 2721.3874,-634.1696 2711.1145,-631.5777 2711.7403,-638.5497"/>
<text text-anchor="middle" x="2353.5" y="-701.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- exposure -->
<g id="node15" class="node">
<title>exposure</title>
<path fill="none" stroke="#000000" d="M2235,-789C2235,-789 2646,-789 2646,-789 2652,-789 2658,-795 2658,-801 2658,-801 2658,-1260 2658,-1260 2658,-1266 2652,-1272 2646,-1272 2646,-1272 2235,-1272 2235,-1272 2229,-1272 2223,-1266 2223,-1260 2223,-1260 2223,-801 2223,-801 2223,-795 2229,-789 2235,-789"/>
<text text-anchor="middle" x="2264" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
<polyline fill="none" stroke="#000000" points="2305,-789 2305,-1272 "/>
<text text-anchor="middle" x="2315.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2326,-789 2326,-1272 "/>
<text text-anchor="middle" x="2481.5" y="-1256.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_days_per_week</text>
<polyline fill="none" stroke="#000000" points="2326,-1249 2637,-1249 "/>
<text text-anchor="middle" x="2481.5" y="-1233.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_drinks_per_day</text>
<polyline fill="none" stroke="#000000" points="2326,-1226 2637,-1226 "/>
<text text-anchor="middle" x="2481.5" y="-1210.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_history</text>
<polyline fill="none" stroke="#000000" points="2326,-1203 2637,-1203 "/>
<text text-anchor="middle" x="2481.5" y="-1187.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_intensity</text>
<polyline fill="none" stroke="#000000" points="2326,-1180 2637,-1180 "/>
<text text-anchor="middle" x="2481.5" y="-1164.8" font-family="Times,serif" font-size="14.00" fill="#000000">asbestos_exposure</text>
<polyline fill="none" stroke="#000000" points="2326,-1157 2637,-1157 "/>
<text text-anchor="middle" x="2481.5" y="-1141.8" font-family="Times,serif" font-size="14.00" fill="#000000">cigarettes_per_day</text>
<polyline fill="none" stroke="#000000" points="2326,-1134 2637,-1134 "/>
<text text-anchor="middle" x="2481.5" y="-1118.8" font-family="Times,serif" font-size="14.00" fill="#000000">coal_dust_exposure</text>
<polyline fill="none" stroke="#000000" points="2326,-1111 2637,-1111 "/>
<text text-anchor="middle" x="2481.5" y="-1095.8" font-family="Times,serif" font-size="14.00" fill="#000000">environmental_tobacco_smoke_exposure</text>
<polyline fill="none" stroke="#000000" points="2326,-1088 2637,-1088 "/>
<text text-anchor="middle" x="2481.5" y="-1072.8" font-family="Times,serif" font-size="14.00" fill="#000000">exposure_id</text>
<polyline fill="none" stroke="#000000" points="2326,-1065 2637,-1065 "/>
<text text-anchor="middle" x="2481.5" y="-1049.8" font-family="Times,serif" font-size="14.00" fill="#000000">pack_years_smoked</text>
<polyline fill="none" stroke="#000000" points="2326,-1042 2637,-1042 "/>
<text text-anchor="middle" x="2481.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">radon_exposure</text>
<polyline fill="none" stroke="#000000" points="2326,-1019 2637,-1019 "/>
<text text-anchor="middle" x="2481.5" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">respirable_crystalline_silica_exposure</text>
<polyline fill="none" stroke="#000000" points="2326,-996 2637,-996 "/>
<text text-anchor="middle" x="2481.5" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">smoking_frequency</text>
<polyline fill="none" stroke="#000000" points="2326,-973 2637,-973 "/>
<text text-anchor="middle" x="2481.5" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">start_days_from_index</text>
<polyline fill="none" stroke="#000000" points="2326,-950 2637,-950 "/>
<text text-anchor="middle" x="2481.5" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">time_between_waking_and_first_smoke</text>
<polyline fill="none" stroke="#000000" points="2326,-927 2637,-927 "/>
<text text-anchor="middle" x="2481.5" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_onset_year</text>
<polyline fill="none" stroke="#000000" points="2326,-904 2637,-904 "/>
<text text-anchor="middle" x="2481.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_quit_year</text>
<polyline fill="none" stroke="#000000" points="2326,-881 2637,-881 "/>
<text text-anchor="middle" x="2481.5" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_status</text>
<polyline fill="none" stroke="#000000" points="2326,-858 2637,-858 "/>
<text text-anchor="middle" x="2481.5" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_smoke_exposure</text>
<polyline fill="none" stroke="#000000" points="2326,-835 2637,-835 "/>
<text text-anchor="middle" x="2481.5" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_tobacco_used</text>
<polyline fill="none" stroke="#000000" points="2326,-812 2637,-812 "/>
<text text-anchor="middle" x="2481.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">years_smoked</text>
<polyline fill="none" stroke="#000000" points="2637,-789 2637,-1272 "/>
<text text-anchor="middle" x="2647.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2607.3201,-788.8627C2626.3839,-768.0914 2646.5429,-748.4006 2667.5,-731 2688.5212,-713.5462 2712.807,-697.9626 2737.3733,-684.4162"/>
<polygon fill="#000000" stroke="#000000" points="2739.2998,-687.3534 2746.4312,-679.5179 2735.9701,-681.196 2739.2998,-687.3534"/>
<text text-anchor="middle" x="2754" y="-701.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- sample_diagnosis -->
<g id="node16" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M12,-1542.5C12,-1542.5 445,-1542.5 445,-1542.5 451,-1542.5 457,-1548.5 457,-1554.5 457,-1554.5 457,-1806.5 457,-1806.5 457,-1812.5 451,-1818.5 445,-1818.5 445,-1818.5 12,-1818.5 12,-1818.5 6,-1818.5 0,-1812.5 0,-1806.5 0,-1806.5 0,-1554.5 0,-1554.5 0,-1548.5 6,-1542.5 12,-1542.5"/>
<text text-anchor="middle" x="71.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="143,-1542.5 143,-1818.5 "/>
<text text-anchor="middle" x="153.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="164,-1542.5 164,-1818.5 "/>
<text text-anchor="middle" x="300" y="-1803.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="164,-1795.5 436,-1795.5 "/>
<text text-anchor="middle" x="300" y="-1780.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="164,-1772.5 436,-1772.5 "/>
<text text-anchor="middle" x="300" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="164,-1749.5 436,-1749.5 "/>
<text text-anchor="middle" x="300" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="164,-1726.5 436,-1726.5 "/>
<text text-anchor="middle" x="300" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="164,-1703.5 436,-1703.5 "/>
<text text-anchor="middle" x="300" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="164,-1680.5 436,-1680.5 "/>
<text text-anchor="middle" x="300" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="164,-1657.5 436,-1657.5 "/>
<text text-anchor="middle" x="300" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="164,-1634.5 436,-1634.5 "/>
<text text-anchor="middle" x="300" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="164,-1611.5 436,-1611.5 "/>
<text text-anchor="middle" x="300" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="164,-1588.5 436,-1588.5 "/>
<text text-anchor="middle" x="300" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="164,-1565.5 436,-1565.5 "/>
<text text-anchor="middle" x="300" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="436,-1542.5 436,-1818.5 "/>
<text text-anchor="middle" x="446.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M303.309,-1542.446C343.2444,-1482.5414 398.1425,-1417.7912 465.5,-1381 596.4118,-1309.495 650.6341,-1357.476 799.5,-1348 834.3327,-1345.7827 1397.4137,-1347.6931 1427.5,-1330 1504.8095,-1284.5359 1552.278,-1191.2627 1578.5379,-1120.8148"/>
<polygon fill="#000000" stroke="#000000" points="1581.9671,-1121.6271 1582.1035,-1111.0331 1575.3903,-1119.2297 1581.9671,-1121.6271"/>
<text text-anchor="middle" x="873.5" y="-1351.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
<!-- diagnosis -->
<g id="node17" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M2688.5,-835C2688.5,-835 3062.5,-835 3062.5,-835 3068.5,-835 3074.5,-841 3074.5,-847 3074.5,-847 3074.5,-1214 3074.5,-1214 3074.5,-1220 3068.5,-1226 3062.5,-1226 3062.5,-1226 2688.5,-1226 2688.5,-1226 2682.5,-1226 2676.5,-1220 2676.5,-1214 2676.5,-1214 2676.5,-847 2676.5,-847 2676.5,-841 2682.5,-835 2688.5,-835"/>
<text text-anchor="middle" x="2718.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="2760.5,-835 2760.5,-1226 "/>
<text text-anchor="middle" x="2771" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2781.5,-835 2781.5,-1226 "/>
<text text-anchor="middle" x="2917.5" y="-1210.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2781.5,-1203 3053.5,-1203 "/>
<text text-anchor="middle" x="2917.5" y="-1187.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="2781.5,-1180 3053.5,-1180 "/>
<text text-anchor="middle" x="2917.5" y="-1164.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="2781.5,-1157 3053.5,-1157 "/>
<text text-anchor="middle" x="2917.5" y="-1141.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2781.5,-1134 3053.5,-1134 "/>
<text text-anchor="middle" x="2917.5" y="-1118.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="2781.5,-1111 3053.5,-1111 "/>
<text text-anchor="middle" x="2917.5" y="-1095.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="2781.5,-1088 3053.5,-1088 "/>
<text text-anchor="middle" x="2917.5" y="-1072.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="2781.5,-1065 3053.5,-1065 "/>
<text text-anchor="middle" x="2917.5" y="-1049.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="2781.5,-1042 3053.5,-1042 "/>
<text text-anchor="middle" x="2917.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="2781.5,-1019 3053.5,-1019 "/>
<text text-anchor="middle" x="2917.5" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="2781.5,-996 3053.5,-996 "/>
<text text-anchor="middle" x="2917.5" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2781.5,-973 3053.5,-973 "/>
<text text-anchor="middle" x="2917.5" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="2781.5,-950 3053.5,-950 "/>
<text text-anchor="middle" x="2917.5" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="2781.5,-927 3053.5,-927 "/>
<text text-anchor="middle" x="2917.5" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="2781.5,-904 3053.5,-904 "/>
<text text-anchor="middle" x="2917.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="2781.5,-881 3053.5,-881 "/>
<text text-anchor="middle" x="2917.5" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="2781.5,-858 3053.5,-858 "/>
<text text-anchor="middle" x="2917.5" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="3053.5,-835 3053.5,-1226 "/>
<text text-anchor="middle" x="3064" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2880.2877,-834.9243C2881.5661,-782.7 2882.8631,-729.7181 2883.8435,-689.6686"/>
<polygon fill="#000000" stroke="#000000" points="2887.3462,-689.5955 2884.0921,-679.5128 2880.3483,-689.4241 2887.3462,-689.5955"/>
<text text-anchor="middle" x="2928" y="-701.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- pdx -->
<g id="node18" class="node">
<title>pdx</title>
<path fill="none" stroke="#000000" d="M487,-1577C487,-1577 816,-1577 816,-1577 822,-1577 828,-1583 828,-1589 828,-1589 828,-1772 828,-1772 828,-1778 822,-1784 816,-1784 816,-1784 487,-1784 487,-1784 481,-1784 475,-1778 475,-1772 475,-1772 475,-1589 475,-1589 475,-1583 481,-1577 487,-1577"/>
<text text-anchor="middle" x="496.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
<polyline fill="none" stroke="#000000" points="518,-1577 518,-1784 "/>
<text text-anchor="middle" x="528.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="539,-1577 539,-1784 "/>
<text text-anchor="middle" x="673" y="-1768.8" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_site</text>
<polyline fill="none" stroke="#000000" points="539,-1761 807,-1761 "/>
<text text-anchor="middle" x="673" y="-1745.8" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_type</text>
<polyline fill="none" stroke="#000000" points="539,-1738 807,-1738 "/>
<text text-anchor="middle" x="673" y="-1722.8" font-family="Times,serif" font-size="14.00" fill="#000000">model_id</text>
<polyline fill="none" stroke="#000000" points="539,-1715 807,-1715 "/>
<text text-anchor="middle" x="673" y="-1699.8" font-family="Times,serif" font-size="14.00" fill="#000000">mouse_strain</text>
<polyline fill="none" stroke="#000000" points="539,-1692 807,-1692 "/>
<text text-anchor="middle" x="673" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">strain_immune_system_humanized</text>
<polyline fill="none" stroke="#000000" points="539,-1669 807,-1669 "/>
<text text-anchor="middle" x="673" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_characterization_method</text>
<polyline fill="none" stroke="#000000" points="539,-1646 807,-1646 "/>
<text text-anchor="middle" x="673" y="-1630.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_not_mus_or_ebv_origin</text>
<polyline fill="none" stroke="#000000" points="539,-1623 807,-1623 "/>
<text text-anchor="middle" x="673" y="-1607.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_preparation</text>
<polyline fill="none" stroke="#000000" points="539,-1600 807,-1600 "/>
<text text-anchor="middle" x="673" y="-1584.8" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_humanization</text>
<polyline fill="none" stroke="#000000" points="807,-1577 807,-1784 "/>
<text text-anchor="middle" x="817.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M687.2441,-1576.8104C716.3539,-1509.0914 764.5458,-1425.2913 836.5,-1381 892.6293,-1346.4497 1371.6681,-1365.0288 1427.5,-1330 1502.9831,-1282.6422 1550.5372,-1190.6058 1577.3096,-1120.9967"/>
<polygon fill="#000000" stroke="#000000" points="1580.7009,-1121.9223 1580.9501,-1111.3304 1574.1501,-1119.4551 1580.7009,-1121.9223"/>
<text text-anchor="middle" x="1337.5" y="-1351.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- synonym -->
<g id="node19" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M3588,-1657.5C3588,-1657.5 3889,-1657.5 3889,-1657.5 3895,-1657.5 3901,-1663.5 3901,-1669.5 3901,-1669.5 3901,-1691.5 3901,-1691.5 3901,-1697.5 3895,-1703.5 3889,-1703.5 3889,-1703.5 3588,-1703.5 3588,-1703.5 3582,-1703.5 3576,-1697.5 3576,-1691.5 3576,-1691.5 3576,-1669.5 3576,-1669.5 3576,-1663.5 3582,-1657.5 3588,-1657.5"/>
<text text-anchor="middle" x="3616" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="3656,-1657.5 3656,-1703.5 "/>
<text text-anchor="middle" x="3666.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3677,-1657.5 3677,-1703.5 "/>
<text text-anchor="middle" x="3778.5" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="3677,-1680.5 3880,-1680.5 "/>
<text text-anchor="middle" x="3778.5" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="3880,-1657.5 3880,-1703.5 "/>
<text text-anchor="middle" x="3890.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge1" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3901.109,-1668.4164C4109.8501,-1643.3522 4465.6626,-1566.361 4638.5,-1330 4717.2289,-1222.3355 4657.5,-1163.8787 4657.5,-1030.5 4657.5,-1030.5 4657.5,-1030.5 4657.5,-432 4657.5,-222.0884 3137.0423,-167.1846 2561.6195,-153.9223"/>
<polygon fill="#000000" stroke="#000000" points="2561.6213,-150.4215 2551.544,-153.6921 2561.4614,-157.4197 2561.6213,-150.4215"/>
<text text-anchor="middle" x="4700" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3728.1652,-1657.4466C3700.4212,-1598.7051 3618.0158,-1443.6378 3495.5,-1381 3378.974,-1321.4245 3038.2873,-1352.7154 2907.5,-1348 2876.294,-1346.8749 1810.5163,-1345.6587 1783.5,-1330 1705.9046,-1285.0255 1658.4815,-1191.6747 1632.3102,-1121.0748"/>
<polygon fill="#000000" stroke="#000000" points="1635.4553,-1119.4805 1628.7575,-1111.2713 1628.8741,-1121.8655 1635.4553,-1119.4805"/>
<text text-anchor="middle" x="3477" y="-1351.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3738.6562,-1657.0502C3739.5028,-1514.2502 3742.3991,-766.4947 3710.5,-731 3667.7392,-683.4193 3289.2412,-649.5018 3060.0428,-633.1169"/>
<polygon fill="#000000" stroke="#000000" points="3060.1444,-629.6154 3049.9215,-632.3978 3059.6482,-636.5978 3060.1444,-629.6154"/>
<text text-anchor="middle" x="3781" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- clinical_measure_file -->
<g id="node20" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M4265.5,-904C4265.5,-904 4617.5,-904 4617.5,-904 4623.5,-904 4629.5,-910 4629.5,-916 4629.5,-916 4629.5,-1145 4629.5,-1145 4629.5,-1151 4623.5,-1157 4617.5,-1157 4617.5,-1157 4265.5,-1157 4265.5,-1157 4259.5,-1157 4253.5,-1151 4253.5,-1145 4253.5,-1145 4253.5,-916 4253.5,-916 4253.5,-910 4259.5,-904 4265.5,-904"/>
<text text-anchor="middle" x="4337" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="4420.5,-904 4420.5,-1157 "/>
<text text-anchor="middle" x="4431" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4441.5,-904 4441.5,-1157 "/>
<text text-anchor="middle" x="4525" y="-1141.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="4441.5,-1134 4608.5,-1134 "/>
<text text-anchor="middle" x="4525" y="-1118.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="4441.5,-1111 4608.5,-1111 "/>
<text text-anchor="middle" x="4525" y="-1095.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="4441.5,-1088 4608.5,-1088 "/>
<text text-anchor="middle" x="4525" y="-1072.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="4441.5,-1065 4608.5,-1065 "/>
<text text-anchor="middle" x="4525" y="-1049.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="4441.5,-1042 4608.5,-1042 "/>
<text text-anchor="middle" x="4525" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="4441.5,-1019 4608.5,-1019 "/>
<text text-anchor="middle" x="4525" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="4441.5,-996 4608.5,-996 "/>
<text text-anchor="middle" x="4525" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="4441.5,-973 4608.5,-973 "/>
<text text-anchor="middle" x="4525" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="4441.5,-950 4608.5,-950 "/>
<text text-anchor="middle" x="4525" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="4441.5,-927 4608.5,-927 "/>
<text text-anchor="middle" x="4525" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="4608.5,-904 4608.5,-1157 "/>
<text text-anchor="middle" x="4619" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge17" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M4463.9015,-903.6588C4468.5883,-835.3993 4461.316,-753.9771 4414.5,-698 4293.7419,-553.6118 3068.4475,-294.6933 2561.8784,-192.8351"/>
<polygon fill="#000000" stroke="#000000" points="2562.3833,-189.3666 2551.8898,-190.8282 2561.0044,-196.2295 2562.3833,-189.3666"/>
<text text-anchor="middle" x="4139.5" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M4389.5924,-903.7598C4357.2834,-841.3258 4309.3868,-771.0272 4244.5,-731 4194.8355,-700.3631 3415.0539,-652.2355 3059.6361,-631.7525"/>
<polygon fill="#000000" stroke="#000000" points="3059.6895,-628.2499 3049.5049,-631.1695 3059.2873,-635.2383 3059.6895,-628.2499"/>
<text text-anchor="middle" x="4281" y="-701.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge27" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2640.4405,-385.7492C2612.3309,-363.3568 2576.7723,-335.0305 2540.1368,-305.8463"/>
<polygon fill="#000000" stroke="#000000" points="2542.3076,-303.1008 2532.3052,-299.6075 2537.946,-308.5759 2542.3076,-303.1008"/>
<text text-anchor="middle" x="2622" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- therapeutic_procedure -->
<g id="node22" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M3082.5,-1611.5C3082.5,-1611.5 3474.5,-1611.5 3474.5,-1611.5 3480.5,-1611.5 3486.5,-1617.5 3486.5,-1623.5 3486.5,-1623.5 3486.5,-1737.5 3486.5,-1737.5 3486.5,-1743.5 3480.5,-1749.5 3474.5,-1749.5 3474.5,-1749.5 3082.5,-1749.5 3082.5,-1749.5 3076.5,-1749.5 3070.5,-1743.5 3070.5,-1737.5 3070.5,-1737.5 3070.5,-1623.5 3070.5,-1623.5 3070.5,-1617.5 3076.5,-1611.5 3082.5,-1611.5"/>
<text text-anchor="middle" x="3161" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="3251.5,-1611.5 3251.5,-1749.5 "/>
<text text-anchor="middle" x="3262" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3272.5,-1611.5 3272.5,-1749.5 "/>
<text text-anchor="middle" x="3369" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment_end</text>
<polyline fill="none" stroke="#000000" points="3272.5,-1726.5 3465.5,-1726.5 "/>
<text text-anchor="middle" x="3369" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment_start</text>
<polyline fill="none" stroke="#000000" points="3272.5,-1703.5 3465.5,-1703.5 "/>
<text text-anchor="middle" x="3369" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="3272.5,-1680.5 3465.5,-1680.5 "/>
<text text-anchor="middle" x="3369" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="3272.5,-1657.5 3465.5,-1657.5 "/>
<text text-anchor="middle" x="3369" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="3272.5,-1634.5 3465.5,-1634.5 "/>
<text text-anchor="middle" x="3369" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="3465.5,-1611.5 3465.5,-1749.5 "/>
<text text-anchor="middle" x="3476" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>therapeutic_procedure&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3191.5618,-1611.4815C3097.2258,-1540.6671 2939.2739,-1433.6405 2784.5,-1381 2658.7612,-1338.2347 2620.0044,-1357.0388 2487.5,-1348 2448.4668,-1345.3373 1817.2552,-1349.7805 1783.5,-1330 1706.1203,-1284.6555 1658.663,-1191.3633 1632.4248,-1120.8783"/>
<polygon fill="#000000" stroke="#000000" points="1635.5717,-1119.291 1628.8624,-1111.0913 1628.9939,-1121.6853 1635.5717,-1119.291"/>
<text text-anchor="middle" x="2810.5" y="-1351.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3346.7122,-1611.2826C3400.7329,-1551.2624 3472.0027,-1459.1296 3502.5,-1363 3523.7396,-1296.0513 3535.1048,-784.4177 3489.5,-731 3434.9173,-667.0663 3218.1667,-640.5359 3059.8878,-629.5894"/>
<polygon fill="#000000" stroke="#000000" points="3059.7624,-626.0731 3049.5492,-628.8907 3059.2904,-633.0571 3059.7624,-626.0731"/>
<text text-anchor="middle" x="3613.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- imaging_file -->
<g id="node23" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M2429.5,-1519.5C2429.5,-1519.5 2763.5,-1519.5 2763.5,-1519.5 2769.5,-1519.5 2775.5,-1525.5 2775.5,-1531.5 2775.5,-1531.5 2775.5,-1829.5 2775.5,-1829.5 2775.5,-1835.5 2769.5,-1841.5 2763.5,-1841.5 2763.5,-1841.5 2429.5,-1841.5 2429.5,-1841.5 2423.5,-1841.5 2417.5,-1835.5 2417.5,-1829.5 2417.5,-1829.5 2417.5,-1531.5 2417.5,-1531.5 2417.5,-1525.5 2423.5,-1519.5 2429.5,-1519.5"/>
<text text-anchor="middle" x="2469.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="2521.5,-1519.5 2521.5,-1841.5 "/>
<text text-anchor="middle" x="2532" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2542.5,-1519.5 2542.5,-1841.5 "/>
<text text-anchor="middle" x="2648.5" y="-1826.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2542.5,-1818.5 2754.5,-1818.5 "/>
<text text-anchor="middle" x="2648.5" y="-1803.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2542.5,-1795.5 2754.5,-1795.5 "/>
<text text-anchor="middle" x="2648.5" y="-1780.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2542.5,-1772.5 2754.5,-1772.5 "/>
<text text-anchor="middle" x="2648.5" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2542.5,-1749.5 2754.5,-1749.5 "/>
<text text-anchor="middle" x="2648.5" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2542.5,-1726.5 2754.5,-1726.5 "/>
<text text-anchor="middle" x="2648.5" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2542.5,-1703.5 2754.5,-1703.5 "/>
<text text-anchor="middle" x="2648.5" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2542.5,-1680.5 2754.5,-1680.5 "/>
<text text-anchor="middle" x="2648.5" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2542.5,-1657.5 2754.5,-1657.5 "/>
<text text-anchor="middle" x="2648.5" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2542.5,-1634.5 2754.5,-1634.5 "/>
<text text-anchor="middle" x="2648.5" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="2542.5,-1611.5 2754.5,-1611.5 "/>
<text text-anchor="middle" x="2648.5" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="2542.5,-1588.5 2754.5,-1588.5 "/>
<text text-anchor="middle" x="2648.5" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="2542.5,-1565.5 2754.5,-1565.5 "/>
<text text-anchor="middle" x="2648.5" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2542.5,-1542.5 2754.5,-1542.5 "/>
<text text-anchor="middle" x="2648.5" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="2754.5,-1519.5 2754.5,-1841.5 "/>
<text text-anchor="middle" x="2765" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2529.243,-1519.2165C2499.5254,-1466.9812 2459.3451,-1414.0512 2407.5,-1381 2310.0222,-1318.858 2264.6517,-1358.1803 2149.5,-1348 2108.9424,-1344.4144 1818.3835,-1350.9981 1783.5,-1330 1706.9077,-1283.8954 1659.4239,-1191.1978 1632.9674,-1121.0744"/>
<polygon fill="#000000" stroke="#000000" points="1636.1194,-1119.506 1629.373,-1111.3367 1629.5524,-1121.93 1636.1194,-1119.506"/>
<text text-anchor="middle" x="2429" y="-1351.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
</g>
</svg>
</div>
