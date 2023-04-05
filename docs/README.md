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
<svg width="4575pt" height="1821pt"
 viewBox="0.00 0.00 4574.50 1821.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1817)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1817 4570.5,-1817 4570.5,4 -4,4"/>
<!-- exposure -->
<g id="node1" class="node">
<title>exposure</title>
<path fill="none" stroke="#000000" d="M579,-622C579,-622 990,-622 990,-622 996,-622 1002,-628 1002,-634 1002,-634 1002,-1093 1002,-1093 1002,-1099 996,-1105 990,-1105 990,-1105 579,-1105 579,-1105 573,-1105 567,-1099 567,-1093 567,-1093 567,-634 567,-634 567,-628 573,-622 579,-622"/>
<text text-anchor="middle" x="608" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
<polyline fill="none" stroke="#000000" points="649,-622 649,-1105 "/>
<text text-anchor="middle" x="659.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="670,-622 670,-1105 "/>
<text text-anchor="middle" x="825.5" y="-1089.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_days_per_week</text>
<polyline fill="none" stroke="#000000" points="670,-1082 981,-1082 "/>
<text text-anchor="middle" x="825.5" y="-1066.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_drinks_per_day</text>
<polyline fill="none" stroke="#000000" points="670,-1059 981,-1059 "/>
<text text-anchor="middle" x="825.5" y="-1043.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_history</text>
<polyline fill="none" stroke="#000000" points="670,-1036 981,-1036 "/>
<text text-anchor="middle" x="825.5" y="-1020.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_intensity</text>
<polyline fill="none" stroke="#000000" points="670,-1013 981,-1013 "/>
<text text-anchor="middle" x="825.5" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000">asbestos_exposure</text>
<polyline fill="none" stroke="#000000" points="670,-990 981,-990 "/>
<text text-anchor="middle" x="825.5" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">cigarettes_per_day</text>
<polyline fill="none" stroke="#000000" points="670,-967 981,-967 "/>
<text text-anchor="middle" x="825.5" y="-951.8" font-family="Times,serif" font-size="14.00" fill="#000000">coal_dust_exposure</text>
<polyline fill="none" stroke="#000000" points="670,-944 981,-944 "/>
<text text-anchor="middle" x="825.5" y="-928.8" font-family="Times,serif" font-size="14.00" fill="#000000">environmental_tobacco_smoke_exposure</text>
<polyline fill="none" stroke="#000000" points="670,-921 981,-921 "/>
<text text-anchor="middle" x="825.5" y="-905.8" font-family="Times,serif" font-size="14.00" fill="#000000">exposure_id</text>
<polyline fill="none" stroke="#000000" points="670,-898 981,-898 "/>
<text text-anchor="middle" x="825.5" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">pack_years_smoked</text>
<polyline fill="none" stroke="#000000" points="670,-875 981,-875 "/>
<text text-anchor="middle" x="825.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">radon_exposure</text>
<polyline fill="none" stroke="#000000" points="670,-852 981,-852 "/>
<text text-anchor="middle" x="825.5" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">respirable_crystalline_silica_exposure</text>
<polyline fill="none" stroke="#000000" points="670,-829 981,-829 "/>
<text text-anchor="middle" x="825.5" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">smoking_frequency</text>
<polyline fill="none" stroke="#000000" points="670,-806 981,-806 "/>
<text text-anchor="middle" x="825.5" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">start_days_from_index</text>
<polyline fill="none" stroke="#000000" points="670,-783 981,-783 "/>
<text text-anchor="middle" x="825.5" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">time_between_waking_and_first_smoke</text>
<polyline fill="none" stroke="#000000" points="670,-760 981,-760 "/>
<text text-anchor="middle" x="825.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_onset_year</text>
<polyline fill="none" stroke="#000000" points="670,-737 981,-737 "/>
<text text-anchor="middle" x="825.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_quit_year</text>
<polyline fill="none" stroke="#000000" points="670,-714 981,-714 "/>
<text text-anchor="middle" x="825.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_status</text>
<polyline fill="none" stroke="#000000" points="670,-691 981,-691 "/>
<text text-anchor="middle" x="825.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_smoke_exposure</text>
<polyline fill="none" stroke="#000000" points="670,-668 981,-668 "/>
<text text-anchor="middle" x="825.5" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_tobacco_used</text>
<polyline fill="none" stroke="#000000" points="670,-645 981,-645 "/>
<text text-anchor="middle" x="825.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">years_smoked</text>
<polyline fill="none" stroke="#000000" points="981,-622 981,-1105 "/>
<text text-anchor="middle" x="991.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node3" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M2435.5,-374.5C2435.5,-374.5 2739.5,-374.5 2739.5,-374.5 2745.5,-374.5 2751.5,-380.5 2751.5,-386.5 2751.5,-386.5 2751.5,-477.5 2751.5,-477.5 2751.5,-483.5 2745.5,-489.5 2739.5,-489.5 2739.5,-489.5 2435.5,-489.5 2435.5,-489.5 2429.5,-489.5 2423.5,-483.5 2423.5,-477.5 2423.5,-477.5 2423.5,-386.5 2423.5,-386.5 2423.5,-380.5 2429.5,-374.5 2435.5,-374.5"/>
<text text-anchor="middle" x="2471.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="2519.5,-374.5 2519.5,-489.5 "/>
<text text-anchor="middle" x="2530" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2540.5,-374.5 2540.5,-489.5 "/>
<text text-anchor="middle" x="2635.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="2540.5,-466.5 2730.5,-466.5 "/>
<text text-anchor="middle" x="2635.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="2540.5,-443.5 2730.5,-443.5 "/>
<text text-anchor="middle" x="2635.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="2540.5,-420.5 2730.5,-420.5 "/>
<text text-anchor="middle" x="2635.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="2540.5,-397.5 2730.5,-397.5 "/>
<text text-anchor="middle" x="2635.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="2730.5,-374.5 2730.5,-489.5 "/>
<text text-anchor="middle" x="2741" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M936.3069,-621.7116C959.0113,-599.2039 984.1103,-579.1844 1011.5,-564 1147.9292,-488.3659 2262.5316,-548.2004 2414.5,-513 2434.0744,-508.466 2454.0733,-501.5413 2473.1996,-493.6114"/>
<polygon fill="#000000" stroke="#000000" points="2474.6848,-496.7831 2482.513,-489.6438 2471.9413,-490.3431 2474.6848,-496.7831"/>
<text text-anchor="middle" x="1267" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- study_admin -->
<g id="node2" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M2067.5,-351.5C2067.5,-351.5 2393.5,-351.5 2393.5,-351.5 2399.5,-351.5 2405.5,-357.5 2405.5,-363.5 2405.5,-363.5 2405.5,-500.5 2405.5,-500.5 2405.5,-506.5 2399.5,-512.5 2393.5,-512.5 2393.5,-512.5 2067.5,-512.5 2067.5,-512.5 2061.5,-512.5 2055.5,-506.5 2055.5,-500.5 2055.5,-500.5 2055.5,-363.5 2055.5,-363.5 2055.5,-357.5 2061.5,-351.5 2067.5,-351.5"/>
<text text-anchor="middle" x="2109.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="2163.5,-351.5 2163.5,-512.5 "/>
<text text-anchor="middle" x="2174" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2184.5,-351.5 2184.5,-512.5 "/>
<text text-anchor="middle" x="2284.5" y="-497.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="2184.5,-489.5 2384.5,-489.5 "/>
<text text-anchor="middle" x="2284.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="2184.5,-466.5 2384.5,-466.5 "/>
<text text-anchor="middle" x="2284.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="2184.5,-443.5 2384.5,-443.5 "/>
<text text-anchor="middle" x="2284.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="2184.5,-420.5 2384.5,-420.5 "/>
<text text-anchor="middle" x="2284.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="2184.5,-397.5 2384.5,-397.5 "/>
<text text-anchor="middle" x="2284.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="2184.5,-374.5 2384.5,-374.5 "/>
<text text-anchor="middle" x="2284.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="2384.5,-351.5 2384.5,-512.5 "/>
<text text-anchor="middle" x="2395" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node16" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M3187.5,-.5C3187.5,-.5 3577.5,-.5 3577.5,-.5 3583.5,-.5 3589.5,-6.5 3589.5,-12.5 3589.5,-12.5 3589.5,-287.5 3589.5,-287.5 3589.5,-293.5 3583.5,-299.5 3577.5,-299.5 3577.5,-299.5 3187.5,-299.5 3187.5,-299.5 3181.5,-299.5 3175.5,-293.5 3175.5,-287.5 3175.5,-287.5 3175.5,-12.5 3175.5,-12.5 3175.5,-6.5 3181.5,-.5 3187.5,-.5"/>
<text text-anchor="middle" x="3203.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="3231.5,-.5 3231.5,-299.5 "/>
<text text-anchor="middle" x="3242" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3252.5,-.5 3252.5,-299.5 "/>
<text text-anchor="middle" x="3410.5" y="-284.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="3252.5,-276.5 3568.5,-276.5 "/>
<text text-anchor="middle" x="3410.5" y="-261.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="3252.5,-253.5 3568.5,-253.5 "/>
<text text-anchor="middle" x="3410.5" y="-238.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_number</text>
<polyline fill="none" stroke="#000000" points="3252.5,-230.5 3568.5,-230.5 "/>
<text text-anchor="middle" x="3410.5" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="3252.5,-207.5 3568.5,-207.5 "/>
<text text-anchor="middle" x="3410.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="3252.5,-184.5 3568.5,-184.5 "/>
<text text-anchor="middle" x="3410.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="3252.5,-161.5 3568.5,-161.5 "/>
<text text-anchor="middle" x="3410.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="3252.5,-138.5 3568.5,-138.5 "/>
<text text-anchor="middle" x="3410.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="3252.5,-115.5 3568.5,-115.5 "/>
<text text-anchor="middle" x="3410.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="3252.5,-92.5 3568.5,-92.5 "/>
<text text-anchor="middle" x="3410.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="3252.5,-69.5 3568.5,-69.5 "/>
<text text-anchor="middle" x="3410.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="3252.5,-46.5 3568.5,-46.5 "/>
<text text-anchor="middle" x="3410.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="3252.5,-23.5 3568.5,-23.5 "/>
<text text-anchor="middle" x="3410.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="3568.5,-.5 3568.5,-299.5 "/>
<text text-anchor="middle" x="3579" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge16" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2405.7301,-353.8822C2408.6665,-352.8926 2411.5913,-351.9308 2414.5,-351 2666.8931,-270.2316 2966.9398,-213.7764 3165.3575,-181.6857"/>
<polygon fill="#000000" stroke="#000000" points="3166.0027,-185.127 3175.3189,-180.0813 3164.8896,-178.2161 3166.0027,-185.127"/>
<text text-anchor="middle" x="2574" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge21" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2705.2957,-374.4516C2723.6139,-366.2004 2742.449,-358.1101 2760.5,-351 2892.9895,-298.8141 3045.0313,-249.4969 3165.6289,-212.7735"/>
<polygon fill="#000000" stroke="#000000" points="3166.8059,-216.0739 3175.3565,-209.8178 3164.7709,-209.3763 3166.8059,-216.0739"/>
<text text-anchor="middle" x="2894" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sequencing_file -->
<g id="node4" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M12,-1214.5C12,-1214.5 481,-1214.5 481,-1214.5 487,-1214.5 493,-1220.5 493,-1226.5 493,-1226.5 493,-1800.5 493,-1800.5 493,-1806.5 487,-1812.5 481,-1812.5 481,-1812.5 12,-1812.5 12,-1812.5 6,-1812.5 0,-1806.5 0,-1800.5 0,-1800.5 0,-1226.5 0,-1226.5 0,-1220.5 6,-1214.5 12,-1214.5"/>
<text text-anchor="middle" x="64" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="128,-1214.5 128,-1812.5 "/>
<text text-anchor="middle" x="138.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="149,-1214.5 149,-1812.5 "/>
<text text-anchor="middle" x="310.5" y="-1797.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="149,-1789.5 472,-1789.5 "/>
<text text-anchor="middle" x="310.5" y="-1774.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="149,-1766.5 472,-1766.5 "/>
<text text-anchor="middle" x="310.5" y="-1751.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="149,-1743.5 472,-1743.5 "/>
<text text-anchor="middle" x="310.5" y="-1728.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="149,-1720.5 472,-1720.5 "/>
<text text-anchor="middle" x="310.5" y="-1705.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="149,-1697.5 472,-1697.5 "/>
<text text-anchor="middle" x="310.5" y="-1682.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="149,-1674.5 472,-1674.5 "/>
<text text-anchor="middle" x="310.5" y="-1659.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="149,-1651.5 472,-1651.5 "/>
<text text-anchor="middle" x="310.5" y="-1636.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="149,-1628.5 472,-1628.5 "/>
<text text-anchor="middle" x="310.5" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="149,-1605.5 472,-1605.5 "/>
<text text-anchor="middle" x="310.5" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="149,-1582.5 472,-1582.5 "/>
<text text-anchor="middle" x="310.5" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="149,-1559.5 472,-1559.5 "/>
<text text-anchor="middle" x="310.5" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="149,-1536.5 472,-1536.5 "/>
<text text-anchor="middle" x="310.5" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="149,-1513.5 472,-1513.5 "/>
<text text-anchor="middle" x="310.5" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="149,-1490.5 472,-1490.5 "/>
<text text-anchor="middle" x="310.5" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="149,-1467.5 472,-1467.5 "/>
<text text-anchor="middle" x="310.5" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="149,-1444.5 472,-1444.5 "/>
<text text-anchor="middle" x="310.5" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="149,-1421.5 472,-1421.5 "/>
<text text-anchor="middle" x="310.5" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="149,-1398.5 472,-1398.5 "/>
<text text-anchor="middle" x="310.5" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="149,-1375.5 472,-1375.5 "/>
<text text-anchor="middle" x="310.5" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="149,-1352.5 472,-1352.5 "/>
<text text-anchor="middle" x="310.5" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="149,-1329.5 472,-1329.5 "/>
<text text-anchor="middle" x="310.5" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="149,-1306.5 472,-1306.5 "/>
<text text-anchor="middle" x="310.5" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="149,-1283.5 472,-1283.5 "/>
<text text-anchor="middle" x="310.5" y="-1268.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="149,-1260.5 472,-1260.5 "/>
<text text-anchor="middle" x="310.5" y="-1245.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="149,-1237.5 472,-1237.5 "/>
<text text-anchor="middle" x="310.5" y="-1222.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 1 properties</text>
<polyline fill="none" stroke="#000000" points="472,-1214.5 472,-1812.5 "/>
<text text-anchor="middle" x="482.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node7" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1448.5,-783C1448.5,-783 1762.5,-783 1762.5,-783 1768.5,-783 1774.5,-789 1774.5,-795 1774.5,-795 1774.5,-932 1774.5,-932 1774.5,-938 1768.5,-944 1762.5,-944 1762.5,-944 1448.5,-944 1448.5,-944 1442.5,-944 1436.5,-938 1436.5,-932 1436.5,-932 1436.5,-795 1436.5,-795 1436.5,-789 1442.5,-783 1448.5,-783"/>
<text text-anchor="middle" x="1470.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1504.5,-783 1504.5,-944 "/>
<text text-anchor="middle" x="1515" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1525.5,-783 1525.5,-944 "/>
<text text-anchor="middle" x="1639.5" y="-928.8" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="1525.5,-921 1753.5,-921 "/>
<text text-anchor="middle" x="1639.5" y="-905.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1525.5,-898 1753.5,-898 "/>
<text text-anchor="middle" x="1639.5" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1525.5,-875 1753.5,-875 "/>
<text text-anchor="middle" x="1639.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1525.5,-852 1753.5,-852 "/>
<text text-anchor="middle" x="1639.5" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1525.5,-829 1753.5,-829 "/>
<text text-anchor="middle" x="1639.5" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1525.5,-806 1753.5,-806 "/>
<text text-anchor="middle" x="1639.5" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="1753.5,-783 1753.5,-944 "/>
<text text-anchor="middle" x="1764" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M493.3026,-1218.2431C496.017,-1216.7857 498.7496,-1215.3707 501.5,-1214 612.4774,-1158.6942 934.6856,-1187.6874 1058.5,-1181 1099.489,-1178.7861 1392.327,-1184.1628 1427.5,-1163 1504.2253,-1116.8362 1551.7372,-1023.911 1578.1656,-953.7429"/>
<polygon fill="#000000" stroke="#000000" points="1581.5821,-954.5935 1581.7556,-944.0001 1575.0139,-952.1732 1581.5821,-954.5935"/>
<text text-anchor="middle" x="1125" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- publication -->
<g id="node5" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M2782,-409C2782,-409 3015,-409 3015,-409 3021,-409 3027,-415 3027,-421 3027,-421 3027,-443 3027,-443 3027,-449 3021,-455 3015,-455 3015,-455 2782,-455 2782,-455 2776,-455 2770,-449 2770,-443 2770,-443 2770,-421 2770,-421 2770,-415 2776,-409 2782,-409"/>
<text text-anchor="middle" x="2818.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="2867,-409 2867,-455 "/>
<text text-anchor="middle" x="2877.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2888,-409 2888,-455 "/>
<text text-anchor="middle" x="2947" y="-439.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication_id</text>
<polyline fill="none" stroke="#000000" points="2888,-432 3006,-432 "/>
<text text-anchor="middle" x="2947" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="3006,-409 3006,-455 "/>
<text text-anchor="middle" x="3016.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge10" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2937.7317,-408.9096C2965.3352,-392.6786 3003.154,-370.4719 3036.5,-351 3078.4529,-326.5022 3123.3046,-300.3894 3166.3408,-275.372"/>
<polygon fill="#000000" stroke="#000000" points="3168.3213,-278.2692 3175.2081,-270.2179 3164.8036,-272.2172 3168.3213,-278.2692"/>
<text text-anchor="middle" x="3143.5" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- diagnosis -->
<g id="node6" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1032.5,-668C1032.5,-668 1406.5,-668 1406.5,-668 1412.5,-668 1418.5,-674 1418.5,-680 1418.5,-680 1418.5,-1047 1418.5,-1047 1418.5,-1053 1412.5,-1059 1406.5,-1059 1406.5,-1059 1032.5,-1059 1032.5,-1059 1026.5,-1059 1020.5,-1053 1020.5,-1047 1020.5,-1047 1020.5,-680 1020.5,-680 1020.5,-674 1026.5,-668 1032.5,-668"/>
<text text-anchor="middle" x="1062.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1104.5,-668 1104.5,-1059 "/>
<text text-anchor="middle" x="1115" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1125.5,-668 1125.5,-1059 "/>
<text text-anchor="middle" x="1261.5" y="-1043.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1125.5,-1036 1397.5,-1036 "/>
<text text-anchor="middle" x="1261.5" y="-1020.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1125.5,-1013 1397.5,-1013 "/>
<text text-anchor="middle" x="1261.5" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1125.5,-990 1397.5,-990 "/>
<text text-anchor="middle" x="1261.5" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1125.5,-967 1397.5,-967 "/>
<text text-anchor="middle" x="1261.5" y="-951.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1125.5,-944 1397.5,-944 "/>
<text text-anchor="middle" x="1261.5" y="-928.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="1125.5,-921 1397.5,-921 "/>
<text text-anchor="middle" x="1261.5" y="-905.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="1125.5,-898 1397.5,-898 "/>
<text text-anchor="middle" x="1261.5" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="1125.5,-875 1397.5,-875 "/>
<text text-anchor="middle" x="1261.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1125.5,-852 1397.5,-852 "/>
<text text-anchor="middle" x="1261.5" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="1125.5,-829 1397.5,-829 "/>
<text text-anchor="middle" x="1261.5" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1125.5,-806 1397.5,-806 "/>
<text text-anchor="middle" x="1261.5" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="1125.5,-783 1397.5,-783 "/>
<text text-anchor="middle" x="1261.5" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1125.5,-760 1397.5,-760 "/>
<text text-anchor="middle" x="1261.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1125.5,-737 1397.5,-737 "/>
<text text-anchor="middle" x="1261.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1125.5,-714 1397.5,-714 "/>
<text text-anchor="middle" x="1261.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1125.5,-691 1397.5,-691 "/>
<text text-anchor="middle" x="1261.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="1397.5,-668 1397.5,-1059 "/>
<text text-anchor="middle" x="1408" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1319.1852,-667.7924C1348.6793,-627.3321 1384.764,-589.3624 1427.5,-564 1545.1329,-494.1887 1597.0177,-540.148 1733.5,-531 1809.0236,-525.9379 2340.8376,-530.4154 2414.5,-513 2433.9149,-508.4099 2453.7581,-501.5043 2472.7562,-493.625"/>
<polygon fill="#000000" stroke="#000000" points="2474.18,-496.8229 2482.0091,-489.6846 2471.4373,-490.3826 2474.18,-496.8229"/>
<text text-anchor="middle" x="1778" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1630.1068,-782.76C1656.1465,-712.3024 1704.5865,-613.7759 1783.5,-564 1902.4866,-488.9473 2278.2762,-548.1254 2414.5,-513 2433.3183,-508.1477 2452.5862,-501.2726 2471.1118,-493.5551"/>
<polygon fill="#000000" stroke="#000000" points="2472.6088,-496.7217 2480.4322,-489.577 2469.8609,-490.2836 2472.6088,-496.7217"/>
<text text-anchor="middle" x="1931" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node8" class="node">
<title>single_cell_sequencing_file</title>
<path fill="none" stroke="#000000" d="M523,-1214.5C523,-1214.5 1132,-1214.5 1132,-1214.5 1138,-1214.5 1144,-1220.5 1144,-1226.5 1144,-1226.5 1144,-1800.5 1144,-1800.5 1144,-1806.5 1138,-1812.5 1132,-1812.5 1132,-1812.5 523,-1812.5 523,-1812.5 517,-1812.5 511,-1806.5 511,-1800.5 511,-1800.5 511,-1226.5 511,-1226.5 511,-1220.5 517,-1214.5 523,-1214.5"/>
<text text-anchor="middle" x="617" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
<polyline fill="none" stroke="#000000" points="723,-1214.5 723,-1812.5 "/>
<text text-anchor="middle" x="733.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="744,-1214.5 744,-1812.5 "/>
<text text-anchor="middle" x="933.5" y="-1797.3" font-family="Times,serif" font-size="14.00" fill="#000000">Cell_Barcode</text>
<polyline fill="none" stroke="#000000" points="744,-1789.5 1123,-1789.5 "/>
<text text-anchor="middle" x="933.5" y="-1774.3" font-family="Times,serif" font-size="14.00" fill="#000000">Cryopreserved_Cells_in_Sample</text>
<polyline fill="none" stroke="#000000" points="744,-1766.5 1123,-1766.5 "/>
<text text-anchor="middle" x="933.5" y="-1751.3" font-family="Times,serif" font-size="14.00" fill="#000000">Dissociation_Method</text>
<polyline fill="none" stroke="#000000" points="744,-1743.5 1123,-1743.5 "/>
<text text-anchor="middle" x="933.5" y="-1728.3" font-family="Times,serif" font-size="14.00" fill="#000000">End_Bias</text>
<polyline fill="none" stroke="#000000" points="744,-1720.5 1123,-1720.5 "/>
<text text-anchor="middle" x="933.5" y="-1705.3" font-family="Times,serif" font-size="14.00" fill="#000000">Input_Cells_and_Nuclei</text>
<polyline fill="none" stroke="#000000" points="744,-1697.5 1123,-1697.5 "/>
<text text-anchor="middle" x="933.5" y="-1682.3" font-family="Times,serif" font-size="14.00" fill="#000000">Library_Construction_Method</text>
<polyline fill="none" stroke="#000000" points="744,-1674.5 1123,-1674.5 "/>
<text text-anchor="middle" x="933.5" y="-1659.3" font-family="Times,serif" font-size="14.00" fill="#000000">Library_Preparation_Date</text>
<polyline fill="none" stroke="#000000" points="744,-1651.5 1123,-1651.5 "/>
<text text-anchor="middle" x="933.5" y="-1636.3" font-family="Times,serif" font-size="14.00" fill="#000000">Nucleic_Acid_Capture_Date</text>
<polyline fill="none" stroke="#000000" points="744,-1628.5 1123,-1628.5 "/>
<text text-anchor="middle" x="933.5" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">Paired_End</text>
<polyline fill="none" stroke="#000000" points="744,-1605.5 1123,-1605.5 "/>
<text text-anchor="middle" x="933.5" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">Protocols_Link</text>
<polyline fill="none" stroke="#000000" points="744,-1582.5 1123,-1582.5 "/>
<text text-anchor="middle" x="933.5" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">Read1</text>
<polyline fill="none" stroke="#000000" points="744,-1559.5 1123,-1559.5 "/>
<text text-anchor="middle" x="933.5" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">Read2</text>
<polyline fill="none" stroke="#000000" points="744,-1536.5 1123,-1536.5 "/>
<text text-anchor="middle" x="933.5" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Feature_barcoding</text>
<polyline fill="none" stroke="#000000" points="744,-1513.5 1123,-1513.5 "/>
<text text-anchor="middle" x="933.5" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Oligo_dT_Poly_dT</text>
<polyline fill="none" stroke="#000000" points="744,-1490.5 1123,-1490.5 "/>
<text text-anchor="middle" x="933.5" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Random</text>
<polyline fill="none" stroke="#000000" points="744,-1467.5 1123,-1467.5 "/>
<text text-anchor="middle" x="933.5" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">Sequencing_Library_Construction_Date</text>
<polyline fill="none" stroke="#000000" points="744,-1444.5 1123,-1444.5 "/>
<text text-anchor="middle" x="933.5" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">Single_Cell_Dissociation_Date</text>
<polyline fill="none" stroke="#000000" points="744,-1421.5 1123,-1421.5 "/>
<text text-anchor="middle" x="933.5" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">Single_Cell_Isolation_Method</text>
<polyline fill="none" stroke="#000000" points="744,-1398.5 1123,-1398.5 "/>
<text text-anchor="middle" x="933.5" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">Spike_In</text>
<polyline fill="none" stroke="#000000" points="744,-1375.5 1123,-1375.5 "/>
<text text-anchor="middle" x="933.5" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">Total_Number_of_Input_Cells</text>
<polyline fill="none" stroke="#000000" points="744,-1352.5 1123,-1352.5 "/>
<text text-anchor="middle" x="933.5" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">UMI</text>
<polyline fill="none" stroke="#000000" points="744,-1329.5 1123,-1329.5 "/>
<text text-anchor="middle" x="933.5" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="744,-1306.5 1123,-1306.5 "/>
<text text-anchor="middle" x="933.5" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">cDNA_Length</text>
<polyline fill="none" stroke="#000000" points="744,-1283.5 1123,-1283.5 "/>
<text text-anchor="middle" x="933.5" y="-1268.3" font-family="Times,serif" font-size="14.00" fill="#000000">cDNA_Offset</text>
<polyline fill="none" stroke="#000000" points="744,-1260.5 1123,-1260.5 "/>
<text text-anchor="middle" x="933.5" y="-1245.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="744,-1237.5 1123,-1237.5 "/>
<text text-anchor="middle" x="933.5" y="-1222.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 24 properties</text>
<polyline fill="none" stroke="#000000" points="1123,-1214.5 1123,-1812.5 "/>
<text text-anchor="middle" x="1133.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1144.1891,-1218.6484C1146.954,-1217.071 1149.7245,-1215.5212 1152.5,-1214 1202.8877,-1186.3847 1221.0618,-1191.7822 1277.5,-1181 1310.4761,-1174.7001 1399.3627,-1181.314 1427.5,-1163 1502.0619,-1114.469 1549.7033,-1022.8404 1576.7454,-953.6565"/>
<polygon fill="#000000" stroke="#000000" points="1580.1165,-954.6405 1580.4251,-944.0502 1573.5796,-952.1366 1580.1165,-954.6405"/>
<text text-anchor="middle" x="1386" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- follow_up -->
<g id="node9" class="node">
<title>follow_up</title>
<path fill="none" stroke="#000000" d="M1805,-760C1805,-760 2168,-760 2168,-760 2174,-760 2180,-766 2180,-772 2180,-772 2180,-955 2180,-955 2180,-961 2174,-967 2168,-967 2168,-967 1805,-967 1805,-967 1799,-967 1793,-961 1793,-955 1793,-955 1793,-772 1793,-772 1793,-766 1799,-760 1805,-760"/>
<text text-anchor="middle" x="1835.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
<polyline fill="none" stroke="#000000" points="1878,-760 1878,-967 "/>
<text text-anchor="middle" x="1888.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1899,-760 1899,-967 "/>
<text text-anchor="middle" x="2029" y="-951.8" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event</text>
<polyline fill="none" stroke="#000000" points="1899,-944 2159,-944 "/>
<text text-anchor="middle" x="2029" y="-928.8" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity</text>
<polyline fill="none" stroke="#000000" points="1899,-921 2159,-921 "/>
<text text-anchor="middle" x="2029" y="-905.8" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity_method_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1899,-898 2159,-898 "/>
<text text-anchor="middle" x="2029" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_follow_up</text>
<polyline fill="none" stroke="#000000" points="1899,-875 2159,-875 "/>
<text text-anchor="middle" x="2029" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_response</text>
<polyline fill="none" stroke="#000000" points="1899,-852 2159,-852 "/>
<text text-anchor="middle" x="2029" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_category</text>
<polyline fill="none" stroke="#000000" points="1899,-829 2159,-829 "/>
<text text-anchor="middle" x="2029" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_id</text>
<polyline fill="none" stroke="#000000" points="1899,-806 2159,-806 "/>
<text text-anchor="middle" x="2029" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_other</text>
<polyline fill="none" stroke="#000000" points="1899,-783 2159,-783 "/>
<text text-anchor="middle" x="2029" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">risk_factor</text>
<polyline fill="none" stroke="#000000" points="2159,-760 2159,-967 "/>
<text text-anchor="middle" x="2169.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2031.4422,-759.8663C2065.2846,-693.9574 2117.9574,-612.2279 2188.5,-564 2273.5034,-505.8856 2317.0831,-546.3589 2414.5,-513 2430.7612,-507.4316 2447.529,-500.7979 2463.9316,-493.7585"/>
<polygon fill="#000000" stroke="#000000" points="2465.7709,-496.775 2473.5405,-489.5719 2462.9749,-490.3576 2465.7709,-496.775"/>
<text text-anchor="middle" x="2314.5" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- study_personnel -->
<g id="node10" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M3057,-374.5C3057,-374.5 3364,-374.5 3364,-374.5 3370,-374.5 3376,-380.5 3376,-386.5 3376,-386.5 3376,-477.5 3376,-477.5 3376,-483.5 3370,-489.5 3364,-489.5 3364,-489.5 3057,-489.5 3057,-489.5 3051,-489.5 3045,-483.5 3045,-477.5 3045,-477.5 3045,-386.5 3045,-386.5 3045,-380.5 3051,-374.5 3057,-374.5"/>
<text text-anchor="middle" x="3112" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="3179,-374.5 3179,-489.5 "/>
<text text-anchor="middle" x="3189.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3200,-374.5 3200,-489.5 "/>
<text text-anchor="middle" x="3277.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="3200,-466.5 3355,-466.5 "/>
<text text-anchor="middle" x="3277.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="3200,-443.5 3355,-443.5 "/>
<text text-anchor="middle" x="3277.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="3200,-420.5 3355,-420.5 "/>
<text text-anchor="middle" x="3277.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="3200,-397.5 3355,-397.5 "/>
<text text-anchor="middle" x="3277.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="3355,-374.5 3355,-489.5 "/>
<text text-anchor="middle" x="3365.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge11" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3245.7218,-374.2526C3257.6263,-354.7347 3271.5533,-331.901 3285.8795,-308.4127"/>
<polygon fill="#000000" stroke="#000000" points="3288.9535,-310.0942 3291.1727,-299.7344 3282.9774,-306.4492 3288.9535,-310.0942"/>
<text text-anchor="middle" x="3345" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- therapeutic_procedure -->
<g id="node11" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M2210,-794.5C2210,-794.5 2611,-794.5 2611,-794.5 2617,-794.5 2623,-800.5 2623,-806.5 2623,-806.5 2623,-920.5 2623,-920.5 2623,-926.5 2617,-932.5 2611,-932.5 2611,-932.5 2210,-932.5 2210,-932.5 2204,-932.5 2198,-926.5 2198,-920.5 2198,-920.5 2198,-806.5 2198,-806.5 2198,-800.5 2204,-794.5 2210,-794.5"/>
<text text-anchor="middle" x="2288.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="2379,-794.5 2379,-932.5 "/>
<text text-anchor="middle" x="2389.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2400,-794.5 2400,-932.5 "/>
<text text-anchor="middle" x="2501" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment_end</text>
<polyline fill="none" stroke="#000000" points="2400,-909.5 2602,-909.5 "/>
<text text-anchor="middle" x="2501" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment_start</text>
<polyline fill="none" stroke="#000000" points="2400,-886.5 2602,-886.5 "/>
<text text-anchor="middle" x="2501" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="2400,-863.5 2602,-863.5 "/>
<text text-anchor="middle" x="2501" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure_id</text>
<polyline fill="none" stroke="#000000" points="2400,-840.5 2602,-840.5 "/>
<text text-anchor="middle" x="2501" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="2400,-817.5 2602,-817.5 "/>
<text text-anchor="middle" x="2501" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="2602,-794.5 2602,-932.5 "/>
<text text-anchor="middle" x="2612.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2438.9381,-794.1721C2472.2274,-713.0176 2526.9839,-579.5295 2559.9054,-499.2716"/>
<polygon fill="#000000" stroke="#000000" points="2563.2521,-500.3352 2563.8091,-489.755 2556.7758,-497.6786 2563.2521,-500.3352"/>
<text text-anchor="middle" x="2638.5" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- sample_diagnosis -->
<g id="node12" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M1174,-1364C1174,-1364 1607,-1364 1607,-1364 1613,-1364 1619,-1370 1619,-1376 1619,-1376 1619,-1651 1619,-1651 1619,-1657 1613,-1663 1607,-1663 1607,-1663 1174,-1663 1174,-1663 1168,-1663 1162,-1657 1162,-1651 1162,-1651 1162,-1376 1162,-1376 1162,-1370 1168,-1364 1174,-1364"/>
<text text-anchor="middle" x="1233.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1305,-1364 1305,-1663 "/>
<text text-anchor="middle" x="1315.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1326,-1364 1326,-1663 "/>
<text text-anchor="middle" x="1462" y="-1647.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1326,-1640 1598,-1640 "/>
<text text-anchor="middle" x="1462" y="-1624.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1326,-1617 1598,-1617 "/>
<text text-anchor="middle" x="1462" y="-1601.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="1326,-1594 1598,-1594 "/>
<text text-anchor="middle" x="1462" y="-1578.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="1326,-1571 1598,-1571 "/>
<text text-anchor="middle" x="1462" y="-1555.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="1326,-1548 1598,-1548 "/>
<text text-anchor="middle" x="1462" y="-1532.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="1326,-1525 1598,-1525 "/>
<text text-anchor="middle" x="1462" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1326,-1502 1598,-1502 "/>
<text text-anchor="middle" x="1462" y="-1486.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1326,-1479 1598,-1479 "/>
<text text-anchor="middle" x="1462" y="-1463.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="1326,-1456 1598,-1456 "/>
<text text-anchor="middle" x="1462" y="-1440.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1326,-1433 1598,-1433 "/>
<text text-anchor="middle" x="1462" y="-1417.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1326,-1410 1598,-1410 "/>
<text text-anchor="middle" x="1462" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1326,-1387 1598,-1387 "/>
<text text-anchor="middle" x="1462" y="-1371.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1598,-1364 1598,-1663 "/>
<text text-anchor="middle" x="1608.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1439.9603,-1363.969C1481.8641,-1237.2828 1540.5718,-1059.7945 1575.6438,-953.7629"/>
<polygon fill="#000000" stroke="#000000" points="1579.0407,-954.6384 1578.8582,-944.0451 1572.3948,-952.4401 1579.0407,-954.6384"/>
<text text-anchor="middle" x="1572.5" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
<!-- study_arm -->
<g id="node13" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M3406,-386C3406,-386 3703,-386 3703,-386 3709,-386 3715,-392 3715,-398 3715,-398 3715,-466 3715,-466 3715,-472 3709,-478 3703,-478 3703,-478 3406,-478 3406,-478 3400,-478 3394,-472 3394,-466 3394,-466 3394,-398 3394,-398 3394,-392 3400,-386 3406,-386"/>
<text text-anchor="middle" x="3440" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="3486,-386 3486,-478 "/>
<text text-anchor="middle" x="3496.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3507,-386 3507,-478 "/>
<text text-anchor="middle" x="3600.5" y="-462.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="3507,-455 3694,-455 "/>
<text text-anchor="middle" x="3600.5" y="-439.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="3507,-432 3694,-432 "/>
<text text-anchor="middle" x="3600.5" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="3507,-409 3694,-409 "/>
<text text-anchor="middle" x="3600.5" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm_id</text>
<polyline fill="none" stroke="#000000" points="3694,-386 3694,-478 "/>
<text text-anchor="middle" x="3704.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge9" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3526.2903,-385.7492C3513.0325,-364.0127 3496.3644,-336.6847 3479.1178,-308.4083"/>
<polygon fill="#000000" stroke="#000000" points="3481.9452,-306.3223 3473.75,-299.6075 3475.9691,-309.9674 3481.9452,-306.3223"/>
<text text-anchor="middle" x="3542" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- imaging_file -->
<g id="node14" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M1649,-1318C1649,-1318 1990,-1318 1990,-1318 1996,-1318 2002,-1324 2002,-1330 2002,-1330 2002,-1697 2002,-1697 2002,-1703 1996,-1709 1990,-1709 1990,-1709 1649,-1709 1649,-1709 1643,-1709 1637,-1703 1637,-1697 1637,-1697 1637,-1330 1637,-1330 1637,-1324 1643,-1318 1649,-1318"/>
<text text-anchor="middle" x="1689" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="1741,-1318 1741,-1709 "/>
<text text-anchor="middle" x="1751.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1762,-1318 1762,-1709 "/>
<text text-anchor="middle" x="1871.5" y="-1693.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1762,-1686 1981,-1686 "/>
<text text-anchor="middle" x="1871.5" y="-1670.8" font-family="Times,serif" font-size="14.00" fill="#000000">deidentification_method</text>
<polyline fill="none" stroke="#000000" points="1762,-1663 1981,-1663 "/>
<text text-anchor="middle" x="1871.5" y="-1647.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1762,-1640 1981,-1640 "/>
<text text-anchor="middle" x="1871.5" y="-1624.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1762,-1617 1981,-1617 "/>
<text text-anchor="middle" x="1871.5" y="-1601.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1762,-1594 1981,-1594 "/>
<text text-anchor="middle" x="1871.5" y="-1578.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1762,-1571 1981,-1571 "/>
<text text-anchor="middle" x="1871.5" y="-1555.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1762,-1548 1981,-1548 "/>
<text text-anchor="middle" x="1871.5" y="-1532.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1762,-1525 1981,-1525 "/>
<text text-anchor="middle" x="1871.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">fixation_embedding_method</text>
<polyline fill="none" stroke="#000000" points="1762,-1502 1981,-1502 "/>
<text text-anchor="middle" x="1871.5" y="-1486.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="1762,-1479 1981,-1479 "/>
<text text-anchor="middle" x="1871.5" y="-1463.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file_id</text>
<polyline fill="none" stroke="#000000" points="1762,-1456 1981,-1456 "/>
<text text-anchor="middle" x="1871.5" y="-1440.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="1762,-1433 1981,-1433 "/>
<text text-anchor="middle" x="1871.5" y="-1417.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="1762,-1410 1981,-1410 "/>
<text text-anchor="middle" x="1871.5" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">magnification</text>
<polyline fill="none" stroke="#000000" points="1762,-1387 1981,-1387 "/>
<text text-anchor="middle" x="1871.5" y="-1371.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1762,-1364 1981,-1364 "/>
<text text-anchor="middle" x="1871.5" y="-1348.8" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="1762,-1341 1981,-1341 "/>
<text text-anchor="middle" x="1871.5" y="-1325.8" font-family="Times,serif" font-size="14.00" fill="#000000">staining_method</text>
<polyline fill="none" stroke="#000000" points="1981,-1318 1981,-1709 "/>
<text text-anchor="middle" x="1991.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1755.0027,-1317.5971C1715.2436,-1196.8333 1666.1354,-1047.673 1635.3065,-954.0339"/>
<polygon fill="#000000" stroke="#000000" points="1638.5551,-952.7087 1632.1034,-944.3047 1631.9062,-954.8977 1638.5551,-952.7087"/>
<text text-anchor="middle" x="1767" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- study_funding -->
<g id="node15" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M3745,-386C3745,-386 4124,-386 4124,-386 4130,-386 4136,-392 4136,-398 4136,-398 4136,-466 4136,-466 4136,-472 4130,-478 4124,-478 4124,-478 3745,-478 3745,-478 3739,-478 3733,-472 3733,-466 3733,-466 3733,-398 3733,-398 3733,-392 3739,-386 3745,-386"/>
<text text-anchor="middle" x="3792.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="3852,-386 3852,-478 "/>
<text text-anchor="middle" x="3862.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3873,-386 3873,-478 "/>
<text text-anchor="middle" x="3994" y="-462.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="3873,-455 4115,-455 "/>
<text text-anchor="middle" x="3994" y="-439.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="3873,-432 4115,-432 "/>
<text text-anchor="middle" x="3994" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="3873,-409 4115,-409 "/>
<text text-anchor="middle" x="3994" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding_id</text>
<polyline fill="none" stroke="#000000" points="4115,-386 4115,-478 "/>
<text text-anchor="middle" x="4125.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge18" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3844.275,-385.9068C3777.7,-351.8957 3684.2081,-304.1335 3598.7452,-260.4731"/>
<polygon fill="#000000" stroke="#000000" points="3600.2011,-257.2866 3589.7036,-255.854 3597.0165,-263.5203 3600.2011,-257.2866"/>
<text text-anchor="middle" x="3801.5" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- pdx -->
<g id="node17" class="node">
<title>pdx</title>
<path fill="none" stroke="#000000" d="M2032,-1398.5C2032,-1398.5 2361,-1398.5 2361,-1398.5 2367,-1398.5 2373,-1404.5 2373,-1410.5 2373,-1410.5 2373,-1616.5 2373,-1616.5 2373,-1622.5 2367,-1628.5 2361,-1628.5 2361,-1628.5 2032,-1628.5 2032,-1628.5 2026,-1628.5 2020,-1622.5 2020,-1616.5 2020,-1616.5 2020,-1410.5 2020,-1410.5 2020,-1404.5 2026,-1398.5 2032,-1398.5"/>
<text text-anchor="middle" x="2041.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
<polyline fill="none" stroke="#000000" points="2063,-1398.5 2063,-1628.5 "/>
<text text-anchor="middle" x="2073.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2084,-1398.5 2084,-1628.5 "/>
<text text-anchor="middle" x="2218" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_site</text>
<polyline fill="none" stroke="#000000" points="2084,-1605.5 2352,-1605.5 "/>
<text text-anchor="middle" x="2218" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_type</text>
<polyline fill="none" stroke="#000000" points="2084,-1582.5 2352,-1582.5 "/>
<text text-anchor="middle" x="2218" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_id</text>
<polyline fill="none" stroke="#000000" points="2084,-1559.5 2352,-1559.5 "/>
<text text-anchor="middle" x="2218" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">mouse_strain</text>
<polyline fill="none" stroke="#000000" points="2084,-1536.5 2352,-1536.5 "/>
<text text-anchor="middle" x="2218" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx_id</text>
<polyline fill="none" stroke="#000000" points="2084,-1513.5 2352,-1513.5 "/>
<text text-anchor="middle" x="2218" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">strain_immune_system_humanized</text>
<polyline fill="none" stroke="#000000" points="2084,-1490.5 2352,-1490.5 "/>
<text text-anchor="middle" x="2218" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_characterization_method</text>
<polyline fill="none" stroke="#000000" points="2084,-1467.5 2352,-1467.5 "/>
<text text-anchor="middle" x="2218" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_not_mus_or_ebv_origin</text>
<polyline fill="none" stroke="#000000" points="2084,-1444.5 2352,-1444.5 "/>
<text text-anchor="middle" x="2218" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_preparation</text>
<polyline fill="none" stroke="#000000" points="2084,-1421.5 2352,-1421.5 "/>
<text text-anchor="middle" x="2218" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_humanization</text>
<polyline fill="none" stroke="#000000" points="2352,-1398.5 2352,-1628.5 "/>
<text text-anchor="middle" x="2362.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2151.5691,-1398.169C2121.0354,-1334.5634 2074.4785,-1259.4845 2010.5,-1214 1968.3617,-1184.0425 1825.3441,-1193.3671 1783.5,-1163 1712.1991,-1111.2555 1664.4126,-1021.4433 1636.4636,-953.6297"/>
<polygon fill="#000000" stroke="#000000" points="1639.6482,-952.1688 1632.6512,-944.2131 1633.1598,-954.7958 1639.6482,-952.1688"/>
<text text-anchor="middle" x="1975.5" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- medical_history -->
<g id="node18" class="node">
<title>medical_history</title>
<path fill="none" stroke="#000000" d="M2653.5,-829C2653.5,-829 3007.5,-829 3007.5,-829 3013.5,-829 3019.5,-835 3019.5,-841 3019.5,-841 3019.5,-886 3019.5,-886 3019.5,-892 3013.5,-898 3007.5,-898 3007.5,-898 2653.5,-898 2653.5,-898 2647.5,-898 2641.5,-892 2641.5,-886 2641.5,-886 2641.5,-841 2641.5,-841 2641.5,-835 2647.5,-829 2653.5,-829"/>
<text text-anchor="middle" x="2707" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
<polyline fill="none" stroke="#000000" points="2772.5,-829 2772.5,-898 "/>
<text text-anchor="middle" x="2783" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2793.5,-829 2793.5,-898 "/>
<text text-anchor="middle" x="2896" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_category</text>
<polyline fill="none" stroke="#000000" points="2793.5,-875 2998.5,-875 "/>
<text text-anchor="middle" x="2896" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_condition</text>
<polyline fill="none" stroke="#000000" points="2793.5,-852 2998.5,-852 "/>
<text text-anchor="middle" x="2896" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_id</text>
<polyline fill="none" stroke="#000000" points="2998.5,-829 2998.5,-898 "/>
<text text-anchor="middle" x="3009" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2828.3637,-828.7616C2822.8307,-764.2435 2803.2998,-624.0345 2735.5,-531 2726.1521,-518.1729 2714.6006,-506.5088 2702.1054,-496.0571"/>
<polygon fill="#000000" stroke="#000000" points="2704.1995,-493.2497 2694.2147,-489.7066 2699.8107,-498.703 2704.1995,-493.2497"/>
<text text-anchor="middle" x="2809.5" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- methylation_array_file -->
<g id="node19" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M2403,-1387C2403,-1387 2798,-1387 2798,-1387 2804,-1387 2810,-1393 2810,-1399 2810,-1399 2810,-1628 2810,-1628 2810,-1634 2804,-1640 2798,-1640 2798,-1640 2403,-1640 2403,-1640 2397,-1640 2391,-1634 2391,-1628 2391,-1628 2391,-1399 2391,-1399 2391,-1393 2397,-1387 2403,-1387"/>
<text text-anchor="middle" x="2480" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="2569,-1387 2569,-1640 "/>
<text text-anchor="middle" x="2579.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2590,-1387 2590,-1640 "/>
<text text-anchor="middle" x="2689.5" y="-1624.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2590,-1617 2789,-1617 "/>
<text text-anchor="middle" x="2689.5" y="-1601.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2590,-1594 2789,-1594 "/>
<text text-anchor="middle" x="2689.5" y="-1578.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2590,-1571 2789,-1571 "/>
<text text-anchor="middle" x="2689.5" y="-1555.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2590,-1548 2789,-1548 "/>
<text text-anchor="middle" x="2689.5" y="-1532.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2590,-1525 2789,-1525 "/>
<text text-anchor="middle" x="2689.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2590,-1502 2789,-1502 "/>
<text text-anchor="middle" x="2689.5" y="-1486.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2590,-1479 2789,-1479 "/>
<text text-anchor="middle" x="2689.5" y="-1463.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2590,-1456 2789,-1456 "/>
<text text-anchor="middle" x="2689.5" y="-1440.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file_id</text>
<polyline fill="none" stroke="#000000" points="2590,-1433 2789,-1433 "/>
<text text-anchor="middle" x="2689.5" y="-1417.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="2590,-1410 2789,-1410 "/>
<text text-anchor="middle" x="2689.5" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="2789,-1387 2789,-1640 "/>
<text text-anchor="middle" x="2799.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge24" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2540.6999,-1386.8647C2503.9899,-1323.8495 2450.6615,-1252.9819 2381.5,-1214 2234.5898,-1131.196 2171.5393,-1195.2093 2003.5,-1181 1954.6222,-1176.8669 1825.1092,-1188.9768 1783.5,-1163 1707.7894,-1115.7336 1660.2195,-1023.4498 1633.5038,-953.7489"/>
<polygon fill="#000000" stroke="#000000" points="1636.6622,-952.2034 1629.8717,-944.0707 1630.1085,-954.6629 1636.6622,-952.2034"/>
<text text-anchor="middle" x="2432" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- molecular_test -->
<g id="node20" class="node">
<title>molecular_test</title>
<path fill="none" stroke="#000000" d="M3049.5,-564.5C3049.5,-564.5 3437.5,-564.5 3437.5,-564.5 3443.5,-564.5 3449.5,-570.5 3449.5,-576.5 3449.5,-576.5 3449.5,-1150.5 3449.5,-1150.5 3449.5,-1156.5 3443.5,-1162.5 3437.5,-1162.5 3437.5,-1162.5 3049.5,-1162.5 3049.5,-1162.5 3043.5,-1162.5 3037.5,-1156.5 3037.5,-1150.5 3037.5,-1150.5 3037.5,-576.5 3037.5,-576.5 3037.5,-570.5 3043.5,-564.5 3049.5,-564.5"/>
<text text-anchor="middle" x="3099" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
<polyline fill="none" stroke="#000000" points="3160.5,-564.5 3160.5,-1162.5 "/>
<text text-anchor="middle" x="3171" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3181.5,-564.5 3181.5,-1162.5 "/>
<text text-anchor="middle" x="3305" y="-1147.3" font-family="Times,serif" font-size="14.00" fill="#000000">aa_change</text>
<polyline fill="none" stroke="#000000" points="3181.5,-1139.5 3428.5,-1139.5 "/>
<text text-anchor="middle" x="3305" y="-1124.3" font-family="Times,serif" font-size="14.00" fill="#000000">antigen</text>
<polyline fill="none" stroke="#000000" points="3181.5,-1116.5 3428.5,-1116.5 "/>
<text text-anchor="middle" x="3305" y="-1101.3" font-family="Times,serif" font-size="14.00" fill="#000000">biospecimen_type</text>
<polyline fill="none" stroke="#000000" points="3181.5,-1093.5 3428.5,-1093.5 "/>
<text text-anchor="middle" x="3305" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000">blood_test_normal_range_lower</text>
<polyline fill="none" stroke="#000000" points="3181.5,-1070.5 3428.5,-1070.5 "/>
<text text-anchor="middle" x="3305" y="-1055.3" font-family="Times,serif" font-size="14.00" fill="#000000">blood_test_normal_range_upper</text>
<polyline fill="none" stroke="#000000" points="3181.5,-1047.5 3428.5,-1047.5 "/>
<text text-anchor="middle" x="3305" y="-1032.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_count</text>
<polyline fill="none" stroke="#000000" points="3181.5,-1024.5 3428.5,-1024.5 "/>
<text text-anchor="middle" x="3305" y="-1009.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome</text>
<polyline fill="none" stroke="#000000" points="3181.5,-1001.5 3428.5,-1001.5 "/>
<text text-anchor="middle" x="3305" y="-986.3" font-family="Times,serif" font-size="14.00" fill="#000000">copy_number</text>
<polyline fill="none" stroke="#000000" points="3181.5,-978.5 3428.5,-978.5 "/>
<text text-anchor="middle" x="3305" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytoband</text>
<polyline fill="none" stroke="#000000" points="3181.5,-955.5 3428.5,-955.5 "/>
<text text-anchor="middle" x="3305" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">exon</text>
<polyline fill="none" stroke="#000000" points="3181.5,-932.5 3428.5,-932.5 "/>
<text text-anchor="middle" x="3305" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">gene_symbol</text>
<polyline fill="none" stroke="#000000" points="3181.5,-909.5 3428.5,-909.5 "/>
<text text-anchor="middle" x="3305" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">histone_family</text>
<polyline fill="none" stroke="#000000" points="3181.5,-886.5 3428.5,-886.5 "/>
<text text-anchor="middle" x="3305" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">histone_variant</text>
<polyline fill="none" stroke="#000000" points="3181.5,-863.5 3428.5,-863.5 "/>
<text text-anchor="middle" x="3305" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">intron</text>
<polyline fill="none" stroke="#000000" points="3181.5,-840.5 3428.5,-840.5 "/>
<text text-anchor="middle" x="3305" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
<polyline fill="none" stroke="#000000" points="3181.5,-817.5 3428.5,-817.5 "/>
<text text-anchor="middle" x="3305" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">loci_abnormal_count</text>
<polyline fill="none" stroke="#000000" points="3181.5,-794.5 3428.5,-794.5 "/>
<text text-anchor="middle" x="3305" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">loci_count</text>
<polyline fill="none" stroke="#000000" points="3181.5,-771.5 3428.5,-771.5 "/>
<text text-anchor="middle" x="3305" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">locus</text>
<polyline fill="none" stroke="#000000" points="3181.5,-748.5 3428.5,-748.5 "/>
<text text-anchor="middle" x="3305" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">mismatch_repair_mutation</text>
<polyline fill="none" stroke="#000000" points="3181.5,-725.5 3428.5,-725.5 "/>
<text text-anchor="middle" x="3305" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_analysis_method</text>
<polyline fill="none" stroke="#000000" points="3181.5,-702.5 3428.5,-702.5 "/>
<text text-anchor="middle" x="3305" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_consequence</text>
<polyline fill="none" stroke="#000000" points="3181.5,-679.5 3428.5,-679.5 "/>
<text text-anchor="middle" x="3305" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test_id</text>
<polyline fill="none" stroke="#000000" points="3181.5,-656.5 3428.5,-656.5 "/>
<text text-anchor="middle" x="3305" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathogenicity</text>
<polyline fill="none" stroke="#000000" points="3181.5,-633.5 3428.5,-633.5 "/>
<text text-anchor="middle" x="3305" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">ploidy</text>
<polyline fill="none" stroke="#000000" points="3181.5,-610.5 3428.5,-610.5 "/>
<text text-anchor="middle" x="3305" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">second_exon</text>
<polyline fill="none" stroke="#000000" points="3181.5,-587.5 3428.5,-587.5 "/>
<text text-anchor="middle" x="3305" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 11 properties</text>
<polyline fill="none" stroke="#000000" points="3428.5,-564.5 3428.5,-1162.5 "/>
<text text-anchor="middle" x="3439" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3037.2269,-569.9886C3034.345,-567.9398 3031.4359,-565.9425 3028.5,-564 2927.3804,-497.0966 2876.5888,-547.9947 2760.5,-513 2743.0857,-507.7505 2725.1929,-501.0327 2707.8258,-493.7166"/>
<polygon fill="#000000" stroke="#000000" points="2708.8074,-490.3289 2698.2379,-489.596 2706.0434,-496.7602 2708.8074,-490.3289"/>
<text text-anchor="middle" x="3057.5" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- family_relationship -->
<g id="node21" class="node">
<title>family_relationship</title>
<path fill="none" stroke="#000000" d="M3480,-817.5C3480,-817.5 3849,-817.5 3849,-817.5 3855,-817.5 3861,-823.5 3861,-829.5 3861,-829.5 3861,-897.5 3861,-897.5 3861,-903.5 3855,-909.5 3849,-909.5 3849,-909.5 3480,-909.5 3480,-909.5 3474,-909.5 3468,-903.5 3468,-897.5 3468,-897.5 3468,-829.5 3468,-829.5 3468,-823.5 3474,-817.5 3480,-817.5"/>
<text text-anchor="middle" x="3545" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
<polyline fill="none" stroke="#000000" points="3622,-817.5 3622,-909.5 "/>
<text text-anchor="middle" x="3632.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3643,-817.5 3643,-909.5 "/>
<text text-anchor="middle" x="3741.5" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_id</text>
<polyline fill="none" stroke="#000000" points="3643,-886.5 3840,-886.5 "/>
<text text-anchor="middle" x="3741.5" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship_id</text>
<polyline fill="none" stroke="#000000" points="3643,-863.5 3840,-863.5 "/>
<text text-anchor="middle" x="3741.5" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">related_to_participant_id</text>
<polyline fill="none" stroke="#000000" points="3643,-840.5 3840,-840.5 "/>
<text text-anchor="middle" x="3741.5" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">relationship</text>
<polyline fill="none" stroke="#000000" points="3840,-817.5 3840,-909.5 "/>
<text text-anchor="middle" x="3850.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3647.4879,-817.2524C3619.6206,-748.7998 3557.2582,-622.3342 3458.5,-564 3324.5912,-484.9031 2911.4335,-550.5097 2760.5,-513 2741.5022,-508.2787 2722.0676,-501.4282 2703.4078,-493.6815"/>
<polygon fill="#000000" stroke="#000000" points="2704.5941,-490.3826 2694.0223,-489.6843 2701.8512,-496.8228 2704.5941,-490.3826"/>
<text text-anchor="middle" x="3489" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- clinical_measure_file -->
<g id="node22" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M3891,-725.5C3891,-725.5 4264,-725.5 4264,-725.5 4270,-725.5 4276,-731.5 4276,-737.5 4276,-737.5 4276,-989.5 4276,-989.5 4276,-995.5 4270,-1001.5 4264,-1001.5 4264,-1001.5 3891,-1001.5 3891,-1001.5 3885,-1001.5 3879,-995.5 3879,-989.5 3879,-989.5 3879,-737.5 3879,-737.5 3879,-731.5 3885,-725.5 3891,-725.5"/>
<text text-anchor="middle" x="3962.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="4046,-725.5 4046,-1001.5 "/>
<text text-anchor="middle" x="4056.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4067,-725.5 4067,-1001.5 "/>
<text text-anchor="middle" x="4161" y="-986.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="4067,-978.5 4255,-978.5 "/>
<text text-anchor="middle" x="4161" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="4067,-955.5 4255,-955.5 "/>
<text text-anchor="middle" x="4161" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file_id</text>
<polyline fill="none" stroke="#000000" points="4067,-932.5 4255,-932.5 "/>
<text text-anchor="middle" x="4161" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="4067,-909.5 4255,-909.5 "/>
<text text-anchor="middle" x="4161" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="4067,-886.5 4255,-886.5 "/>
<text text-anchor="middle" x="4161" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="4067,-863.5 4255,-863.5 "/>
<text text-anchor="middle" x="4161" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="4067,-840.5 4255,-840.5 "/>
<text text-anchor="middle" x="4161" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="4067,-817.5 4255,-817.5 "/>
<text text-anchor="middle" x="4161" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="4067,-794.5 4255,-794.5 "/>
<text text-anchor="middle" x="4161" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="4067,-771.5 4255,-771.5 "/>
<text text-anchor="middle" x="4161" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="4067,-748.5 4255,-748.5 "/>
<text text-anchor="middle" x="4161" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="4255,-725.5 4255,-1001.5 "/>
<text text-anchor="middle" x="4265.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M4015.3103,-725.3093C3981.234,-665.7585 3933.0496,-601.3379 3870.5,-564 3756.0811,-495.6996 3705.4619,-539.8185 3572.5,-531 3482.4534,-525.0278 2848.3674,-533.5762 2760.5,-513 2740.9366,-508.4188 2720.9435,-501.4692 2701.8197,-493.5288"/>
<polygon fill="#000000" stroke="#000000" points="2703.0786,-490.2608 2692.5071,-489.5573 2700.3325,-496.6997 2703.0786,-490.2608"/>
<text text-anchor="middle" x="3961" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge15" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M4145.9931,-725.2618C4190.7075,-613.1636 4227.1367,-456.9277 4145.5,-351 4079.0465,-264.7732 3800.9931,-208.1366 3599.7064,-177.5853"/>
<polygon fill="#000000" stroke="#000000" points="3599.9889,-174.0885 3589.5792,-176.0603 3598.9465,-181.0104 3599.9889,-174.0885"/>
<text text-anchor="middle" x="4279.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- synonym -->
<g id="node23" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M4161,-1490.5C4161,-1490.5 4462,-1490.5 4462,-1490.5 4468,-1490.5 4474,-1496.5 4474,-1502.5 4474,-1502.5 4474,-1524.5 4474,-1524.5 4474,-1530.5 4468,-1536.5 4462,-1536.5 4462,-1536.5 4161,-1536.5 4161,-1536.5 4155,-1536.5 4149,-1530.5 4149,-1524.5 4149,-1524.5 4149,-1502.5 4149,-1502.5 4149,-1496.5 4155,-1490.5 4161,-1490.5"/>
<text text-anchor="middle" x="4189" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="4229,-1490.5 4229,-1536.5 "/>
<text text-anchor="middle" x="4239.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4250,-1490.5 4250,-1536.5 "/>
<text text-anchor="middle" x="4351.5" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="4250,-1513.5 4453,-1513.5 "/>
<text text-anchor="middle" x="4351.5" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="4453,-1490.5 4453,-1536.5 "/>
<text text-anchor="middle" x="4463.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M4312.5879,-1490.1631C4318.844,-1351.1685 4347.8316,-636.0006 4285.5,-564 4229.1156,-498.8691 4180.28,-538.9391 4094.5,-531 3946.8951,-517.3389 2904.9764,-546.1724 2760.5,-513 2740.7781,-508.4718 2720.6297,-501.5007 2701.3784,-493.5085"/>
<polygon fill="#000000" stroke="#000000" points="2702.577,-490.2147 2692.0057,-489.5093 2699.8298,-496.6531 2702.577,-490.2147"/>
<text text-anchor="middle" x="4367" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M4226.5324,-1490.391C3971.6684,-1422.6559 3190.3132,-1226.51 2527.5,-1181 2486.2517,-1178.1678 1819.1862,-1183.8792 1783.5,-1163 1706.0891,-1117.7086 1658.6368,-1024.4081 1632.4083,-953.9065"/>
<polygon fill="#000000" stroke="#000000" points="1635.5549,-952.3182 1628.8472,-944.1172 1628.9766,-954.7112 1635.5549,-952.3182"/>
<text text-anchor="middle" x="2717" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge3" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M4323.2883,-1490.1866C4389.079,-1356.4712 4696.3729,-681.4018 4369.5,-351 4264.0636,-244.4253 3857.111,-190.4451 3599.828,-166.4153"/>
<polygon fill="#000000" stroke="#000000" points="3599.8776,-162.905 3589.5975,-165.4681 3599.2323,-169.8752 3599.8776,-162.905"/>
<text text-anchor="middle" x="4524" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
</g>
</svg>
</div>
