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
<svg width="3249pt" height="1551pt"
 viewBox="0.00 0.00 3248.50 1551.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1547)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1547 3244.5,-1547 3244.5,4 -4,4"/>
<!-- methylation_array_file -->
<g id="node1" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M1973.5,-1151.5C1973.5,-1151.5 2340.5,-1151.5 2340.5,-1151.5 2346.5,-1151.5 2352.5,-1157.5 2352.5,-1163.5 2352.5,-1163.5 2352.5,-1369.5 2352.5,-1369.5 2352.5,-1375.5 2346.5,-1381.5 2340.5,-1381.5 2340.5,-1381.5 1973.5,-1381.5 1973.5,-1381.5 1967.5,-1381.5 1961.5,-1375.5 1961.5,-1369.5 1961.5,-1369.5 1961.5,-1163.5 1961.5,-1163.5 1961.5,-1157.5 1967.5,-1151.5 1973.5,-1151.5"/>
<text text-anchor="middle" x="2050.5" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="2139.5,-1151.5 2139.5,-1381.5 "/>
<text text-anchor="middle" x="2150" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2160.5,-1151.5 2160.5,-1381.5 "/>
<text text-anchor="middle" x="2246" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2160.5,-1358.5 2331.5,-1358.5 "/>
<text text-anchor="middle" x="2246" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2160.5,-1335.5 2331.5,-1335.5 "/>
<text text-anchor="middle" x="2246" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2160.5,-1312.5 2331.5,-1312.5 "/>
<text text-anchor="middle" x="2246" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2160.5,-1289.5 2331.5,-1289.5 "/>
<text text-anchor="middle" x="2246" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2160.5,-1266.5 2331.5,-1266.5 "/>
<text text-anchor="middle" x="2246" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2160.5,-1243.5 2331.5,-1243.5 "/>
<text text-anchor="middle" x="2246" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2160.5,-1220.5 2331.5,-1220.5 "/>
<text text-anchor="middle" x="2246" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2160.5,-1197.5 2331.5,-1197.5 "/>
<text text-anchor="middle" x="2246" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="2160.5,-1174.5 2331.5,-1174.5 "/>
<text text-anchor="middle" x="2246" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="2331.5,-1151.5 2331.5,-1381.5 "/>
<text text-anchor="middle" x="2342" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node9" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M2393,-651C2393,-651 2707,-651 2707,-651 2713,-651 2719,-657 2719,-663 2719,-663 2719,-915 2719,-915 2719,-921 2713,-927 2707,-927 2707,-927 2393,-927 2393,-927 2387,-927 2381,-921 2381,-915 2381,-915 2381,-663 2381,-663 2381,-657 2387,-651 2393,-651"/>
<text text-anchor="middle" x="2415" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="2449,-651 2449,-927 "/>
<text text-anchor="middle" x="2459.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2470,-651 2470,-927 "/>
<text text-anchor="middle" x="2584" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="2470,-904 2698,-904 "/>
<text text-anchor="middle" x="2584" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="2470,-881 2698,-881 "/>
<text text-anchor="middle" x="2584" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="2470,-858 2698,-858 "/>
<text text-anchor="middle" x="2584" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="2470,-835 2698,-835 "/>
<text text-anchor="middle" x="2584" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="2470,-812 2698,-812 "/>
<text text-anchor="middle" x="2584" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="2470,-789 2698,-789 "/>
<text text-anchor="middle" x="2584" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="2470,-766 2698,-766 "/>
<text text-anchor="middle" x="2584" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="2470,-743 2698,-743 "/>
<text text-anchor="middle" x="2584" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="2470,-720 2698,-720 "/>
<text text-anchor="middle" x="2584" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="2470,-697 2698,-697 "/>
<text text-anchor="middle" x="2584" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="2470,-674 2698,-674 "/>
<text text-anchor="middle" x="2584" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="2698,-651 2698,-927 "/>
<text text-anchor="middle" x="2708.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2223.9786,-1151.3114C2261.4815,-1090.8431 2311.0653,-1017.0493 2363,-957 2369.4235,-949.5728 2376.1625,-942.1534 2383.1117,-934.7978"/>
<polygon fill="#000000" stroke="#000000" points="2385.7428,-937.1107 2390.1272,-927.4656 2380.685,-932.2714 2385.7428,-937.1107"/>
<text text-anchor="middle" x="2454.5" y="-960.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study_admin -->
<g id="node2" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M12,-259.5C12,-259.5 338,-259.5 338,-259.5 344,-259.5 350,-265.5 350,-271.5 350,-271.5 350,-431.5 350,-431.5 350,-437.5 344,-443.5 338,-443.5 338,-443.5 12,-443.5 12,-443.5 6,-443.5 0,-437.5 0,-431.5 0,-431.5 0,-271.5 0,-271.5 0,-265.5 6,-259.5 12,-259.5"/>
<text text-anchor="middle" x="54" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="108,-259.5 108,-443.5 "/>
<text text-anchor="middle" x="118.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="129,-259.5 129,-443.5 "/>
<text text-anchor="middle" x="229" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="129,-420.5 329,-420.5 "/>
<text text-anchor="middle" x="229" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="129,-397.5 329,-397.5 "/>
<text text-anchor="middle" x="229" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="129,-374.5 329,-374.5 "/>
<text text-anchor="middle" x="229" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="129,-351.5 329,-351.5 "/>
<text text-anchor="middle" x="229" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="129,-328.5 329,-328.5 "/>
<text text-anchor="middle" x="229" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="129,-305.5 329,-305.5 "/>
<text text-anchor="middle" x="229" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="129,-282.5 329,-282.5 "/>
<text text-anchor="middle" x="229" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="329,-259.5 329,-443.5 "/>
<text text-anchor="middle" x="339.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node4" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M932,-.5C932,-.5 1322,-.5 1322,-.5 1328,-.5 1334,-6.5 1334,-12.5 1334,-12.5 1334,-195.5 1334,-195.5 1334,-201.5 1328,-207.5 1322,-207.5 1322,-207.5 932,-207.5 932,-207.5 926,-207.5 920,-201.5 920,-195.5 920,-195.5 920,-12.5 920,-12.5 920,-6.5 926,-.5 932,-.5"/>
<text text-anchor="middle" x="948" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="976,-.5 976,-207.5 "/>
<text text-anchor="middle" x="986.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="997,-.5 997,-207.5 "/>
<text text-anchor="middle" x="1155" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="997,-184.5 1313,-184.5 "/>
<text text-anchor="middle" x="1155" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="997,-161.5 1313,-161.5 "/>
<text text-anchor="middle" x="1155" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="997,-138.5 1313,-138.5 "/>
<text text-anchor="middle" x="1155" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="997,-115.5 1313,-115.5 "/>
<text text-anchor="middle" x="1155" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="997,-92.5 1313,-92.5 "/>
<text text-anchor="middle" x="1155" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="997,-69.5 1313,-69.5 "/>
<text text-anchor="middle" x="1155" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="997,-46.5 1313,-46.5 "/>
<text text-anchor="middle" x="1155" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="997,-23.5 1313,-23.5 "/>
<text text-anchor="middle" x="1155" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="1313,-.5 1313,-207.5 "/>
<text text-anchor="middle" x="1323.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M350.0945,-262.1743C353.0729,-261.0805 356.0429,-260.0211 359,-259 539.6948,-196.6057 753.4539,-156.004 909.5159,-132.0719"/>
<polygon fill="#000000" stroke="#000000" points="910.3518,-135.4851 919.711,-130.5196 909.2981,-128.5648 910.3518,-135.4851"/>
<text text-anchor="middle" x="517.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- imaging_file -->
<g id="node3" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M2383,-1105.5C2383,-1105.5 2717,-1105.5 2717,-1105.5 2723,-1105.5 2729,-1111.5 2729,-1117.5 2729,-1117.5 2729,-1415.5 2729,-1415.5 2729,-1421.5 2723,-1427.5 2717,-1427.5 2717,-1427.5 2383,-1427.5 2383,-1427.5 2377,-1427.5 2371,-1421.5 2371,-1415.5 2371,-1415.5 2371,-1117.5 2371,-1117.5 2371,-1111.5 2377,-1105.5 2383,-1105.5"/>
<text text-anchor="middle" x="2423" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="2475,-1105.5 2475,-1427.5 "/>
<text text-anchor="middle" x="2485.5" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2496,-1105.5 2496,-1427.5 "/>
<text text-anchor="middle" x="2602" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2496,-1404.5 2708,-1404.5 "/>
<text text-anchor="middle" x="2602" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2496,-1381.5 2708,-1381.5 "/>
<text text-anchor="middle" x="2602" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2496,-1358.5 2708,-1358.5 "/>
<text text-anchor="middle" x="2602" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2496,-1335.5 2708,-1335.5 "/>
<text text-anchor="middle" x="2602" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2496,-1312.5 2708,-1312.5 "/>
<text text-anchor="middle" x="2602" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2496,-1289.5 2708,-1289.5 "/>
<text text-anchor="middle" x="2602" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2496,-1266.5 2708,-1266.5 "/>
<text text-anchor="middle" x="2602" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2496,-1243.5 2708,-1243.5 "/>
<text text-anchor="middle" x="2602" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2496,-1220.5 2708,-1220.5 "/>
<text text-anchor="middle" x="2602" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="2496,-1197.5 2708,-1197.5 "/>
<text text-anchor="middle" x="2602" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="2496,-1174.5 2708,-1174.5 "/>
<text text-anchor="middle" x="2602" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="2496,-1151.5 2708,-1151.5 "/>
<text text-anchor="middle" x="2602" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2496,-1128.5 2708,-1128.5 "/>
<text text-anchor="middle" x="2602" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="2708,-1105.5 2708,-1427.5 "/>
<text text-anchor="middle" x="2718.5" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2550,-1105.1732C2550,-1050.8872 2550,-990.6125 2550,-937.3722"/>
<polygon fill="#000000" stroke="#000000" points="2553.5001,-937.1694 2550,-927.1694 2546.5001,-937.1695 2553.5001,-937.1694"/>
<text text-anchor="middle" x="2604.5" y="-960.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- publication -->
<g id="node5" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M380,-333.5C380,-333.5 590,-333.5 590,-333.5 596,-333.5 602,-339.5 602,-345.5 602,-345.5 602,-357.5 602,-357.5 602,-363.5 596,-369.5 590,-369.5 590,-369.5 380,-369.5 380,-369.5 374,-369.5 368,-363.5 368,-357.5 368,-357.5 368,-345.5 368,-345.5 368,-339.5 374,-333.5 380,-333.5"/>
<text text-anchor="middle" x="416.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="465,-333.5 465,-369.5 "/>
<text text-anchor="middle" x="475.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="486,-333.5 486,-369.5 "/>
<text text-anchor="middle" x="533.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="581,-333.5 581,-369.5 "/>
<text text-anchor="middle" x="591.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge19" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M504.967,-333.4355C528.6867,-312.8224 570.2006,-279.3432 611,-259 704.8784,-212.1909 815.5319,-176.6474 910.2463,-151.4823"/>
<polygon fill="#000000" stroke="#000000" points="911.1689,-154.8588 919.947,-148.9262 909.3853,-148.0898 911.1689,-154.8588"/>
<text text-anchor="middle" x="729" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- therapeutic_procedure -->
<g id="node6" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M1994.5,-731.5C1994.5,-731.5 2351.5,-731.5 2351.5,-731.5 2357.5,-731.5 2363.5,-737.5 2363.5,-743.5 2363.5,-743.5 2363.5,-834.5 2363.5,-834.5 2363.5,-840.5 2357.5,-846.5 2351.5,-846.5 2351.5,-846.5 1994.5,-846.5 1994.5,-846.5 1988.5,-846.5 1982.5,-840.5 1982.5,-834.5 1982.5,-834.5 1982.5,-743.5 1982.5,-743.5 1982.5,-737.5 1988.5,-731.5 1994.5,-731.5"/>
<text text-anchor="middle" x="2073" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="2163.5,-731.5 2163.5,-846.5 "/>
<text text-anchor="middle" x="2174" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2184.5,-731.5 2184.5,-846.5 "/>
<text text-anchor="middle" x="2263.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="2184.5,-823.5 2342.5,-823.5 "/>
<text text-anchor="middle" x="2263.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="2184.5,-800.5 2342.5,-800.5 "/>
<text text-anchor="middle" x="2263.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="2184.5,-777.5 2342.5,-777.5 "/>
<text text-anchor="middle" x="2263.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="2184.5,-754.5 2342.5,-754.5 "/>
<text text-anchor="middle" x="2263.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="2342.5,-731.5 2342.5,-846.5 "/>
<text text-anchor="middle" x="2353" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node15" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M1645.5,-495.5C1645.5,-495.5 1876.5,-495.5 1876.5,-495.5 1882.5,-495.5 1888.5,-501.5 1888.5,-507.5 1888.5,-507.5 1888.5,-575.5 1888.5,-575.5 1888.5,-581.5 1882.5,-587.5 1876.5,-587.5 1876.5,-587.5 1645.5,-587.5 1645.5,-587.5 1639.5,-587.5 1633.5,-581.5 1633.5,-575.5 1633.5,-575.5 1633.5,-507.5 1633.5,-507.5 1633.5,-501.5 1639.5,-495.5 1645.5,-495.5"/>
<text text-anchor="middle" x="1681.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1729.5,-495.5 1729.5,-587.5 "/>
<text text-anchor="middle" x="1740" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1750.5,-495.5 1750.5,-587.5 "/>
<text text-anchor="middle" x="1809" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="1750.5,-564.5 1867.5,-564.5 "/>
<text text-anchor="middle" x="1809" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="1750.5,-541.5 1867.5,-541.5 "/>
<text text-anchor="middle" x="1809" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1750.5,-518.5 1867.5,-518.5 "/>
<text text-anchor="middle" x="1809" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1867.5,-495.5 1867.5,-587.5 "/>
<text text-anchor="middle" x="1878" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2103.8238,-731.3693C2066.4353,-701.7275 2018.6772,-666.2117 1973,-639 1944.4557,-621.995 1912.4416,-605.8786 1882.1106,-591.8268"/>
<polygon fill="#000000" stroke="#000000" points="1883.3057,-588.5243 1872.7573,-587.5335 1880.3855,-594.8861 1883.3057,-588.5243"/>
<text text-anchor="middle" x="2033" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- study_funding -->
<g id="node7" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M632.5,-317C632.5,-317 1011.5,-317 1011.5,-317 1017.5,-317 1023.5,-323 1023.5,-329 1023.5,-329 1023.5,-374 1023.5,-374 1023.5,-380 1017.5,-386 1011.5,-386 1011.5,-386 632.5,-386 632.5,-386 626.5,-386 620.5,-380 620.5,-374 620.5,-374 620.5,-329 620.5,-329 620.5,-323 626.5,-317 632.5,-317"/>
<text text-anchor="middle" x="680" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="739.5,-317 739.5,-386 "/>
<text text-anchor="middle" x="750" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="760.5,-317 760.5,-386 "/>
<text text-anchor="middle" x="881.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="760.5,-363 1002.5,-363 "/>
<text text-anchor="middle" x="881.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="760.5,-340 1002.5,-340 "/>
<text text-anchor="middle" x="881.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="1002.5,-317 1002.5,-386 "/>
<text text-anchor="middle" x="1013" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge13" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M841.8976,-316.7326C858.6231,-289.6578 884.4863,-252.3692 914,-226 918.6402,-221.8542 923.4441,-217.7843 928.3778,-213.7954"/>
<polygon fill="#000000" stroke="#000000" points="930.5525,-216.5378 936.2327,-207.5943 926.2151,-211.0435 930.5525,-216.5378"/>
<text text-anchor="middle" x="976" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- sequencing_file -->
<g id="node8" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M2759.5,-990.5C2759.5,-990.5 3228.5,-990.5 3228.5,-990.5 3234.5,-990.5 3240.5,-996.5 3240.5,-1002.5 3240.5,-1002.5 3240.5,-1530.5 3240.5,-1530.5 3240.5,-1536.5 3234.5,-1542.5 3228.5,-1542.5 3228.5,-1542.5 2759.5,-1542.5 2759.5,-1542.5 2753.5,-1542.5 2747.5,-1536.5 2747.5,-1530.5 2747.5,-1530.5 2747.5,-1002.5 2747.5,-1002.5 2747.5,-996.5 2753.5,-990.5 2759.5,-990.5"/>
<text text-anchor="middle" x="2811.5" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="2875.5,-990.5 2875.5,-1542.5 "/>
<text text-anchor="middle" x="2886" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2896.5,-990.5 2896.5,-1542.5 "/>
<text text-anchor="middle" x="3058" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="2896.5,-1519.5 3219.5,-1519.5 "/>
<text text-anchor="middle" x="3058" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2896.5,-1496.5 3219.5,-1496.5 "/>
<text text-anchor="middle" x="3058" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2896.5,-1473.5 3219.5,-1473.5 "/>
<text text-anchor="middle" x="3058" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="2896.5,-1450.5 3219.5,-1450.5 "/>
<text text-anchor="middle" x="3058" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="2896.5,-1427.5 3219.5,-1427.5 "/>
<text text-anchor="middle" x="3058" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2896.5,-1404.5 3219.5,-1404.5 "/>
<text text-anchor="middle" x="3058" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2896.5,-1381.5 3219.5,-1381.5 "/>
<text text-anchor="middle" x="3058" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2896.5,-1358.5 3219.5,-1358.5 "/>
<text text-anchor="middle" x="3058" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2896.5,-1335.5 3219.5,-1335.5 "/>
<text text-anchor="middle" x="3058" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2896.5,-1312.5 3219.5,-1312.5 "/>
<text text-anchor="middle" x="3058" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2896.5,-1289.5 3219.5,-1289.5 "/>
<text text-anchor="middle" x="3058" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2896.5,-1266.5 3219.5,-1266.5 "/>
<text text-anchor="middle" x="3058" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="2896.5,-1243.5 3219.5,-1243.5 "/>
<text text-anchor="middle" x="3058" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="2896.5,-1220.5 3219.5,-1220.5 "/>
<text text-anchor="middle" x="3058" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="2896.5,-1197.5 3219.5,-1197.5 "/>
<text text-anchor="middle" x="3058" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="2896.5,-1174.5 3219.5,-1174.5 "/>
<text text-anchor="middle" x="3058" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="2896.5,-1151.5 3219.5,-1151.5 "/>
<text text-anchor="middle" x="3058" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="2896.5,-1128.5 3219.5,-1128.5 "/>
<text text-anchor="middle" x="3058" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2896.5,-1105.5 3219.5,-1105.5 "/>
<text text-anchor="middle" x="3058" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="2896.5,-1082.5 3219.5,-1082.5 "/>
<text text-anchor="middle" x="3058" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="2896.5,-1059.5 3219.5,-1059.5 "/>
<text text-anchor="middle" x="3058" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="2896.5,-1036.5 3219.5,-1036.5 "/>
<text text-anchor="middle" x="3058" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="2896.5,-1013.5 3219.5,-1013.5 "/>
<text text-anchor="middle" x="3058" y="-998.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="3219.5,-990.5 3219.5,-1542.5 "/>
<text text-anchor="middle" x="3230" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2747.4178,-1000.1234C2744.26,-996.7281 2741.1196,-993.3523 2738,-990 2721.2614,-972.0127 2703.6616,-953.1414 2686.222,-934.4669"/>
<polygon fill="#000000" stroke="#000000" points="2688.6717,-931.962 2679.2879,-927.0431 2683.5561,-936.7402 2688.6717,-931.962"/>
<text text-anchor="middle" x="2784.5" y="-960.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge9" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2458.7016,-650.9644C2368.4757,-526.6887 2218.5962,-350.0157 2042,-259 1923.4172,-197.8838 1575.3693,-150.9772 1344.3489,-125.4705"/>
<polygon fill="#000000" stroke="#000000" points="1344.4469,-121.9603 1334.1245,-124.3471 1343.6824,-128.9184 1344.4469,-121.9603"/>
<text text-anchor="middle" x="2348.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2395.1739,-650.9449C2387.5472,-646.5882 2379.8086,-642.574 2372,-639 2289.9247,-601.4341 2052.2879,-571.1713 1898.7091,-554.8127"/>
<polygon fill="#000000" stroke="#000000" points="1899.0301,-551.3272 1888.7172,-553.7554 1898.2934,-558.2883 1899.0301,-551.3272"/>
<text text-anchor="middle" x="2349.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- synonym -->
<g id="node10" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M1303.5,-1243.5C1303.5,-1243.5 1604.5,-1243.5 1604.5,-1243.5 1610.5,-1243.5 1616.5,-1249.5 1616.5,-1255.5 1616.5,-1255.5 1616.5,-1277.5 1616.5,-1277.5 1616.5,-1283.5 1610.5,-1289.5 1604.5,-1289.5 1604.5,-1289.5 1303.5,-1289.5 1303.5,-1289.5 1297.5,-1289.5 1291.5,-1283.5 1291.5,-1277.5 1291.5,-1277.5 1291.5,-1255.5 1291.5,-1255.5 1291.5,-1249.5 1297.5,-1243.5 1303.5,-1243.5"/>
<text text-anchor="middle" x="1331.5" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="1371.5,-1243.5 1371.5,-1289.5 "/>
<text text-anchor="middle" x="1382" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1392.5,-1243.5 1392.5,-1289.5 "/>
<text text-anchor="middle" x="1494" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="1392.5,-1266.5 1595.5,-1266.5 "/>
<text text-anchor="middle" x="1494" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="1595.5,-1243.5 1595.5,-1289.5 "/>
<text text-anchor="middle" x="1606" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge3" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1398.7618,-1243.4239C1303.2259,-1200.0772 1109.9889,-1096.4309 1033,-939 972.1822,-814.6365 1053.2118,-415.7111 1099.1894,-217.6964"/>
<polygon fill="#000000" stroke="#000000" points="1102.6248,-218.3755 1101.4871,-207.8419 1095.8077,-216.7859 1102.6248,-218.3755"/>
<text text-anchor="middle" x="1085.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1485.2025,-1243.4194C1560.7871,-1188.8469 1761.5276,-1051.821 1952,-990 1996.7133,-975.4876 2328.8967,-957.7616 2372,-939 2377.0371,-936.8075 2382.0411,-934.4249 2387.0014,-931.8786"/>
<polygon fill="#000000" stroke="#000000" points="2388.7169,-934.9302 2395.8803,-927.1241 2385.4124,-928.7593 2388.7169,-934.9302"/>
<text text-anchor="middle" x="2293.5" y="-960.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1452.7659,-1243.2954C1447.2498,-1135.6829 1426.6731,-688.3587 1463,-639 1483.2206,-611.5256 1555.0725,-587.5829 1623.1522,-570.2993"/>
<polygon fill="#000000" stroke="#000000" points="1624.3096,-573.6178 1633.1628,-567.798 1622.6126,-566.8266 1624.3096,-573.6178"/>
<text text-anchor="middle" x="1505.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study_arm -->
<g id="node11" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M1724.5,-317C1724.5,-317 2021.5,-317 2021.5,-317 2027.5,-317 2033.5,-323 2033.5,-329 2033.5,-329 2033.5,-374 2033.5,-374 2033.5,-380 2027.5,-386 2021.5,-386 2021.5,-386 1724.5,-386 1724.5,-386 1718.5,-386 1712.5,-380 1712.5,-374 1712.5,-374 1712.5,-329 1712.5,-329 1712.5,-323 1718.5,-317 1724.5,-317"/>
<text text-anchor="middle" x="1758.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="1804.5,-317 1804.5,-386 "/>
<text text-anchor="middle" x="1815" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1825.5,-317 1825.5,-386 "/>
<text text-anchor="middle" x="1919" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="1825.5,-363 2012.5,-363 "/>
<text text-anchor="middle" x="1919" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="1825.5,-340 2012.5,-340 "/>
<text text-anchor="middle" x="1919" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="2012.5,-317 2012.5,-386 "/>
<text text-anchor="middle" x="2023" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge10" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1817.184,-316.7831C1784.7667,-297.7404 1742.6186,-274.8514 1703,-259 1587.5035,-212.7898 1453.5721,-175.8183 1343.9367,-149.5899"/>
<polygon fill="#000000" stroke="#000000" points="1344.6161,-146.1539 1334.0775,-147.2445 1342.996,-152.9639 1344.6161,-146.1539"/>
<text text-anchor="middle" x="1691.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- diagnosis -->
<g id="node12" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1569.5,-639.5C1569.5,-639.5 1952.5,-639.5 1952.5,-639.5 1958.5,-639.5 1964.5,-645.5 1964.5,-651.5 1964.5,-651.5 1964.5,-926.5 1964.5,-926.5 1964.5,-932.5 1958.5,-938.5 1952.5,-938.5 1952.5,-938.5 1569.5,-938.5 1569.5,-938.5 1563.5,-938.5 1557.5,-932.5 1557.5,-926.5 1557.5,-926.5 1557.5,-651.5 1557.5,-651.5 1557.5,-645.5 1563.5,-639.5 1569.5,-639.5"/>
<text text-anchor="middle" x="1599.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1641.5,-639.5 1641.5,-938.5 "/>
<text text-anchor="middle" x="1652" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1662.5,-639.5 1662.5,-938.5 "/>
<text text-anchor="middle" x="1803" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1662.5,-915.5 1943.5,-915.5 "/>
<text text-anchor="middle" x="1803" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1662.5,-892.5 1943.5,-892.5 "/>
<text text-anchor="middle" x="1803" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1662.5,-869.5 1943.5,-869.5 "/>
<text text-anchor="middle" x="1803" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1662.5,-846.5 1943.5,-846.5 "/>
<text text-anchor="middle" x="1803" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1662.5,-823.5 1943.5,-823.5 "/>
<text text-anchor="middle" x="1803" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="1662.5,-800.5 1943.5,-800.5 "/>
<text text-anchor="middle" x="1803" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1662.5,-777.5 1943.5,-777.5 "/>
<text text-anchor="middle" x="1803" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1662.5,-754.5 1943.5,-754.5 "/>
<text text-anchor="middle" x="1803" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis_reference_source</text>
<polyline fill="none" stroke="#000000" points="1662.5,-731.5 1943.5,-731.5 "/>
<text text-anchor="middle" x="1803" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="1662.5,-708.5 1943.5,-708.5 "/>
<text text-anchor="middle" x="1803" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="1662.5,-685.5 1943.5,-685.5 "/>
<text text-anchor="middle" x="1803" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="1662.5,-662.5 1943.5,-662.5 "/>
<text text-anchor="middle" x="1803" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="1943.5,-639.5 1943.5,-938.5 "/>
<text text-anchor="middle" x="1954" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1761,-639.3186C1761,-624.7641 1761,-610.7108 1761,-598.0135"/>
<polygon fill="#000000" stroke="#000000" points="1764.5001,-597.6855 1761,-587.6855 1757.5001,-597.6855 1764.5001,-597.6855"/>
<text text-anchor="middle" x="1805.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- study_personnel -->
<g id="node13" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M1375.5,-294C1375.5,-294 1682.5,-294 1682.5,-294 1688.5,-294 1694.5,-300 1694.5,-306 1694.5,-306 1694.5,-397 1694.5,-397 1694.5,-403 1688.5,-409 1682.5,-409 1682.5,-409 1375.5,-409 1375.5,-409 1369.5,-409 1363.5,-403 1363.5,-397 1363.5,-397 1363.5,-306 1363.5,-306 1363.5,-300 1369.5,-294 1375.5,-294"/>
<text text-anchor="middle" x="1430.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="1497.5,-294 1497.5,-409 "/>
<text text-anchor="middle" x="1508" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1518.5,-294 1518.5,-409 "/>
<text text-anchor="middle" x="1596" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="1518.5,-386 1673.5,-386 "/>
<text text-anchor="middle" x="1596" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="1518.5,-363 1673.5,-363 "/>
<text text-anchor="middle" x="1596" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="1518.5,-340 1673.5,-340 "/>
<text text-anchor="middle" x="1596" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="1518.5,-317 1673.5,-317 "/>
<text text-anchor="middle" x="1596" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="1673.5,-294 1673.5,-409 "/>
<text text-anchor="middle" x="1684" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge12" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1435.5096,-293.9406C1396.2821,-269.7894 1349.3135,-240.8721 1303.9961,-212.9715"/>
<polygon fill="#000000" stroke="#000000" points="1305.6077,-209.8536 1295.2572,-207.5912 1301.9377,-215.8144 1305.6077,-209.8536"/>
<text text-anchor="middle" x="1410.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- clinical_measure_file -->
<g id="node14" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M1054,-662.5C1054,-662.5 1406,-662.5 1406,-662.5 1412,-662.5 1418,-668.5 1418,-674.5 1418,-674.5 1418,-903.5 1418,-903.5 1418,-909.5 1412,-915.5 1406,-915.5 1406,-915.5 1054,-915.5 1054,-915.5 1048,-915.5 1042,-909.5 1042,-903.5 1042,-903.5 1042,-674.5 1042,-674.5 1042,-668.5 1048,-662.5 1054,-662.5"/>
<text text-anchor="middle" x="1125.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="1209,-662.5 1209,-915.5 "/>
<text text-anchor="middle" x="1219.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1230,-662.5 1230,-915.5 "/>
<text text-anchor="middle" x="1313.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1230,-892.5 1397,-892.5 "/>
<text text-anchor="middle" x="1313.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1230,-869.5 1397,-869.5 "/>
<text text-anchor="middle" x="1313.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1230,-846.5 1397,-846.5 "/>
<text text-anchor="middle" x="1313.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1230,-823.5 1397,-823.5 "/>
<text text-anchor="middle" x="1313.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1230,-800.5 1397,-800.5 "/>
<text text-anchor="middle" x="1313.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1230,-777.5 1397,-777.5 "/>
<text text-anchor="middle" x="1313.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1230,-754.5 1397,-754.5 "/>
<text text-anchor="middle" x="1313.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1230,-731.5 1397,-731.5 "/>
<text text-anchor="middle" x="1313.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1230,-708.5 1397,-708.5 "/>
<text text-anchor="middle" x="1313.5" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1230,-685.5 1397,-685.5 "/>
<text text-anchor="middle" x="1313.5" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="1397,-662.5 1397,-915.5 "/>
<text text-anchor="middle" x="1407.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge7" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1181.2176,-662.2731C1176.7293,-648.4545 1172.5455,-634.5058 1169,-621 1133.4481,-485.5709 1125.5886,-323.9358 1124.8976,-217.8857"/>
<polygon fill="#000000" stroke="#000000" points="1128.3972,-217.7833 1124.8524,-207.7991 1121.3973,-217.8147 1128.3972,-217.7833"/>
<text text-anchor="middle" x="1228" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1165.1153,-662.4771C1162.826,-641.8712 1166.6333,-622.0529 1181,-606 1210.0158,-573.5785 1461.2391,-555.6259 1623.3986,-547.3226"/>
<polygon fill="#000000" stroke="#000000" points="1623.6537,-550.8143 1633.4642,-546.8137 1623.3001,-543.8232 1623.6537,-550.8143"/>
<text text-anchor="middle" x="1310.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge18" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1633.4219,-520.2226C1487.7693,-495.4544 1267.5939,-456.3613 1253,-444 1186.5716,-387.7339 1155.1436,-293.0404 1140.2865,-217.8557"/>
<polygon fill="#000000" stroke="#000000" points="1143.6907,-217.022 1138.3839,-207.852 1136.814,-218.3299 1143.6907,-217.022"/>
<text text-anchor="middle" x="1303.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge17" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1788.3983,-495.0208C1806.3572,-464.5547 1829.6807,-424.988 1847.2893,-395.1164"/>
<polygon fill="#000000" stroke="#000000" points="1850.4952,-396.5701 1852.5582,-386.178 1844.4649,-393.0153 1850.4952,-396.5701"/>
<text text-anchor="middle" x="1857.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
</g>
</svg>
</div>
