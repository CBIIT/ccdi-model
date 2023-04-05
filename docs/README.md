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
<svg width="4937pt" height="1821pt"
 viewBox="0.00 0.00 4936.50 1821.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1817)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1817 4932.5,-1817 4932.5,4 -4,4"/>
<!-- study_admin -->
<g id="node1" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M12,-351.5C12,-351.5 338,-351.5 338,-351.5 344,-351.5 350,-357.5 350,-363.5 350,-363.5 350,-500.5 350,-500.5 350,-506.5 344,-512.5 338,-512.5 338,-512.5 12,-512.5 12,-512.5 6,-512.5 0,-506.5 0,-500.5 0,-500.5 0,-363.5 0,-363.5 0,-357.5 6,-351.5 12,-351.5"/>
<text text-anchor="middle" x="54" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="108,-351.5 108,-512.5 "/>
<text text-anchor="middle" x="118.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="129,-351.5 129,-512.5 "/>
<text text-anchor="middle" x="229" y="-497.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="129,-489.5 329,-489.5 "/>
<text text-anchor="middle" x="229" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="129,-466.5 329,-466.5 "/>
<text text-anchor="middle" x="229" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="129,-443.5 329,-443.5 "/>
<text text-anchor="middle" x="229" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="129,-420.5 329,-420.5 "/>
<text text-anchor="middle" x="229" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="129,-397.5 329,-397.5 "/>
<text text-anchor="middle" x="229" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="129,-374.5 329,-374.5 "/>
<text text-anchor="middle" x="229" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="329,-351.5 329,-512.5 "/>
<text text-anchor="middle" x="339.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node11" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M834,-.5C834,-.5 1224,-.5 1224,-.5 1230,-.5 1236,-6.5 1236,-12.5 1236,-12.5 1236,-287.5 1236,-287.5 1236,-293.5 1230,-299.5 1224,-299.5 1224,-299.5 834,-299.5 834,-299.5 828,-299.5 822,-293.5 822,-287.5 822,-287.5 822,-12.5 822,-12.5 822,-6.5 828,-.5 834,-.5"/>
<text text-anchor="middle" x="850" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="878,-.5 878,-299.5 "/>
<text text-anchor="middle" x="888.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="899,-.5 899,-299.5 "/>
<text text-anchor="middle" x="1057" y="-284.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="899,-276.5 1215,-276.5 "/>
<text text-anchor="middle" x="1057" y="-261.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="899,-253.5 1215,-253.5 "/>
<text text-anchor="middle" x="1057" y="-238.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_number</text>
<polyline fill="none" stroke="#000000" points="899,-230.5 1215,-230.5 "/>
<text text-anchor="middle" x="1057" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="899,-207.5 1215,-207.5 "/>
<text text-anchor="middle" x="1057" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="899,-184.5 1215,-184.5 "/>
<text text-anchor="middle" x="1057" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="899,-161.5 1215,-161.5 "/>
<text text-anchor="middle" x="1057" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="899,-138.5 1215,-138.5 "/>
<text text-anchor="middle" x="1057" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="899,-115.5 1215,-115.5 "/>
<text text-anchor="middle" x="1057" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="899,-92.5 1215,-92.5 "/>
<text text-anchor="middle" x="1057" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="899,-69.5 1215,-69.5 "/>
<text text-anchor="middle" x="1057" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="899,-46.5 1215,-46.5 "/>
<text text-anchor="middle" x="1057" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="899,-23.5 1215,-23.5 "/>
<text text-anchor="middle" x="1057" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="1215,-.5 1215,-299.5 "/>
<text text-anchor="middle" x="1225.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge9" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M350.1021,-354.3268C353.0849,-353.1961 356.0525,-352.0862 359,-351 508.104,-296.053 679.8268,-244.7636 812.0913,-207.7482"/>
<polygon fill="#000000" stroke="#000000" points="813.2558,-211.057 821.9459,-204.9963 811.373,-204.3149 813.2558,-211.057"/>
<text text-anchor="middle" x="505.5" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- exposure -->
<g id="node2" class="node">
<title>exposure</title>
<path fill="none" stroke="#000000" d="M3550.5,-622C3550.5,-622 3961.5,-622 3961.5,-622 3967.5,-622 3973.5,-628 3973.5,-634 3973.5,-634 3973.5,-1093 3973.5,-1093 3973.5,-1099 3967.5,-1105 3961.5,-1105 3961.5,-1105 3550.5,-1105 3550.5,-1105 3544.5,-1105 3538.5,-1099 3538.5,-1093 3538.5,-1093 3538.5,-634 3538.5,-634 3538.5,-628 3544.5,-622 3550.5,-622"/>
<text text-anchor="middle" x="3579.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
<polyline fill="none" stroke="#000000" points="3620.5,-622 3620.5,-1105 "/>
<text text-anchor="middle" x="3631" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3641.5,-622 3641.5,-1105 "/>
<text text-anchor="middle" x="3797" y="-1089.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_days_per_week</text>
<polyline fill="none" stroke="#000000" points="3641.5,-1082 3952.5,-1082 "/>
<text text-anchor="middle" x="3797" y="-1066.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_drinks_per_day</text>
<polyline fill="none" stroke="#000000" points="3641.5,-1059 3952.5,-1059 "/>
<text text-anchor="middle" x="3797" y="-1043.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_history</text>
<polyline fill="none" stroke="#000000" points="3641.5,-1036 3952.5,-1036 "/>
<text text-anchor="middle" x="3797" y="-1020.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_intensity</text>
<polyline fill="none" stroke="#000000" points="3641.5,-1013 3952.5,-1013 "/>
<text text-anchor="middle" x="3797" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000">asbestos_exposure</text>
<polyline fill="none" stroke="#000000" points="3641.5,-990 3952.5,-990 "/>
<text text-anchor="middle" x="3797" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">cigarettes_per_day</text>
<polyline fill="none" stroke="#000000" points="3641.5,-967 3952.5,-967 "/>
<text text-anchor="middle" x="3797" y="-951.8" font-family="Times,serif" font-size="14.00" fill="#000000">coal_dust_exposure</text>
<polyline fill="none" stroke="#000000" points="3641.5,-944 3952.5,-944 "/>
<text text-anchor="middle" x="3797" y="-928.8" font-family="Times,serif" font-size="14.00" fill="#000000">environmental_tobacco_smoke_exposure</text>
<polyline fill="none" stroke="#000000" points="3641.5,-921 3952.5,-921 "/>
<text text-anchor="middle" x="3797" y="-905.8" font-family="Times,serif" font-size="14.00" fill="#000000">exposure_id</text>
<polyline fill="none" stroke="#000000" points="3641.5,-898 3952.5,-898 "/>
<text text-anchor="middle" x="3797" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">pack_years_smoked</text>
<polyline fill="none" stroke="#000000" points="3641.5,-875 3952.5,-875 "/>
<text text-anchor="middle" x="3797" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">radon_exposure</text>
<polyline fill="none" stroke="#000000" points="3641.5,-852 3952.5,-852 "/>
<text text-anchor="middle" x="3797" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">respirable_crystalline_silica_exposure</text>
<polyline fill="none" stroke="#000000" points="3641.5,-829 3952.5,-829 "/>
<text text-anchor="middle" x="3797" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">smoking_frequency</text>
<polyline fill="none" stroke="#000000" points="3641.5,-806 3952.5,-806 "/>
<text text-anchor="middle" x="3797" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">start_days_from_index</text>
<polyline fill="none" stroke="#000000" points="3641.5,-783 3952.5,-783 "/>
<text text-anchor="middle" x="3797" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">time_between_waking_and_first_smoke</text>
<polyline fill="none" stroke="#000000" points="3641.5,-760 3952.5,-760 "/>
<text text-anchor="middle" x="3797" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_onset_year</text>
<polyline fill="none" stroke="#000000" points="3641.5,-737 3952.5,-737 "/>
<text text-anchor="middle" x="3797" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_quit_year</text>
<polyline fill="none" stroke="#000000" points="3641.5,-714 3952.5,-714 "/>
<text text-anchor="middle" x="3797" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_status</text>
<polyline fill="none" stroke="#000000" points="3641.5,-691 3952.5,-691 "/>
<text text-anchor="middle" x="3797" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_smoke_exposure</text>
<polyline fill="none" stroke="#000000" points="3641.5,-668 3952.5,-668 "/>
<text text-anchor="middle" x="3797" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_tobacco_used</text>
<polyline fill="none" stroke="#000000" points="3641.5,-645 3952.5,-645 "/>
<text text-anchor="middle" x="3797" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">years_smoked</text>
<polyline fill="none" stroke="#000000" points="3952.5,-622 3952.5,-1105 "/>
<text text-anchor="middle" x="3963" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node16" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M2199,-374.5C2199,-374.5 2503,-374.5 2503,-374.5 2509,-374.5 2515,-380.5 2515,-386.5 2515,-386.5 2515,-477.5 2515,-477.5 2515,-483.5 2509,-489.5 2503,-489.5 2503,-489.5 2199,-489.5 2199,-489.5 2193,-489.5 2187,-483.5 2187,-477.5 2187,-477.5 2187,-386.5 2187,-386.5 2187,-380.5 2193,-374.5 2199,-374.5"/>
<text text-anchor="middle" x="2235" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="2283,-374.5 2283,-489.5 "/>
<text text-anchor="middle" x="2293.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2304,-374.5 2304,-489.5 "/>
<text text-anchor="middle" x="2399" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="2304,-466.5 2494,-466.5 "/>
<text text-anchor="middle" x="2399" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="2304,-443.5 2494,-443.5 "/>
<text text-anchor="middle" x="2399" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="2304,-420.5 2494,-420.5 "/>
<text text-anchor="middle" x="2399" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="2304,-397.5 2494,-397.5 "/>
<text text-anchor="middle" x="2399" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="2494,-374.5 2494,-489.5 "/>
<text text-anchor="middle" x="2504.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3604.4525,-621.6832C3581.9512,-599.2602 3557.0988,-579.268 3530,-564 3404.2787,-493.166 3351.0065,-540.2435 3207,-531 3131.3515,-526.1443 2598.79,-530.358 2525,-513 2505.4879,-508.4101 2485.5379,-501.5046 2466.4333,-493.6253"/>
<polygon fill="#000000" stroke="#000000" points="2467.7014,-490.3614 2457.1282,-489.6849 2464.9718,-496.8073 2467.7014,-490.3614"/>
<text text-anchor="middle" x="3530.5" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- publication -->
<g id="node3" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M380.5,-409C380.5,-409 613.5,-409 613.5,-409 619.5,-409 625.5,-415 625.5,-421 625.5,-421 625.5,-443 625.5,-443 625.5,-449 619.5,-455 613.5,-455 613.5,-455 380.5,-455 380.5,-455 374.5,-455 368.5,-449 368.5,-443 368.5,-443 368.5,-421 368.5,-421 368.5,-415 374.5,-409 380.5,-409"/>
<text text-anchor="middle" x="417" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="465.5,-409 465.5,-455 "/>
<text text-anchor="middle" x="476" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="486.5,-409 486.5,-455 "/>
<text text-anchor="middle" x="545.5" y="-439.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication_id</text>
<polyline fill="none" stroke="#000000" points="486.5,-432 604.5,-432 "/>
<text text-anchor="middle" x="545.5" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="604.5,-409 604.5,-455 "/>
<text text-anchor="middle" x="615" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge18" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M534.7194,-408.828C562.0312,-392.2643 599.9745,-369.6914 634,-351 691.4908,-319.4183 754.4943,-286.5811 812.9638,-256.8267"/>
<polygon fill="#000000" stroke="#000000" points="814.6021,-259.9202 821.9312,-252.2694 811.4307,-253.6799 814.6021,-259.9202"/>
<text text-anchor="middle" x="739" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- therapeutic_procedure -->
<g id="node4" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M4003.5,-794.5C4003.5,-794.5 4404.5,-794.5 4404.5,-794.5 4410.5,-794.5 4416.5,-800.5 4416.5,-806.5 4416.5,-806.5 4416.5,-920.5 4416.5,-920.5 4416.5,-926.5 4410.5,-932.5 4404.5,-932.5 4404.5,-932.5 4003.5,-932.5 4003.5,-932.5 3997.5,-932.5 3991.5,-926.5 3991.5,-920.5 3991.5,-920.5 3991.5,-806.5 3991.5,-806.5 3991.5,-800.5 3997.5,-794.5 4003.5,-794.5"/>
<text text-anchor="middle" x="4082" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="4172.5,-794.5 4172.5,-932.5 "/>
<text text-anchor="middle" x="4183" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4193.5,-794.5 4193.5,-932.5 "/>
<text text-anchor="middle" x="4294.5" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment_end</text>
<polyline fill="none" stroke="#000000" points="4193.5,-909.5 4395.5,-909.5 "/>
<text text-anchor="middle" x="4294.5" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment_start</text>
<polyline fill="none" stroke="#000000" points="4193.5,-886.5 4395.5,-886.5 "/>
<text text-anchor="middle" x="4294.5" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="4193.5,-863.5 4395.5,-863.5 "/>
<text text-anchor="middle" x="4294.5" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure_id</text>
<polyline fill="none" stroke="#000000" points="4193.5,-840.5 4395.5,-840.5 "/>
<text text-anchor="middle" x="4294.5" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="4193.5,-817.5 4395.5,-817.5 "/>
<text text-anchor="middle" x="4294.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="4395.5,-794.5 4395.5,-932.5 "/>
<text text-anchor="middle" x="4406" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M4174.2843,-794.2603C4139.6512,-722.9893 4075.1606,-615.3325 3983,-564 3841.3863,-485.1225 2682.9629,-549.3846 2525,-513 2505.3272,-508.4686 2485.2204,-501.5453 2465.9869,-493.616"/>
<polygon fill="#000000" stroke="#000000" points="2467.194,-490.3263 2456.6208,-489.6487 2464.4637,-496.7719 2467.194,-490.3263"/>
<text text-anchor="middle" x="4005" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- study_arm -->
<g id="node5" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M655.5,-386C655.5,-386 952.5,-386 952.5,-386 958.5,-386 964.5,-392 964.5,-398 964.5,-398 964.5,-466 964.5,-466 964.5,-472 958.5,-478 952.5,-478 952.5,-478 655.5,-478 655.5,-478 649.5,-478 643.5,-472 643.5,-466 643.5,-466 643.5,-398 643.5,-398 643.5,-392 649.5,-386 655.5,-386"/>
<text text-anchor="middle" x="689.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="735.5,-386 735.5,-478 "/>
<text text-anchor="middle" x="746" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="756.5,-386 756.5,-478 "/>
<text text-anchor="middle" x="850" y="-462.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="756.5,-455 943.5,-455 "/>
<text text-anchor="middle" x="850" y="-439.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="756.5,-432 943.5,-432 "/>
<text text-anchor="middle" x="850" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="756.5,-409 943.5,-409 "/>
<text text-anchor="middle" x="850" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm_id</text>
<polyline fill="none" stroke="#000000" points="943.5,-386 943.5,-478 "/>
<text text-anchor="middle" x="954" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M833.728,-385.906C847.7991,-364.7953 865.1771,-339.7012 882,-318 884.6045,-314.6403 887.2557,-311.26 889.9447,-307.8672"/>
<polygon fill="#000000" stroke="#000000" points="892.7772,-309.9292 896.2839,-299.9315 887.3079,-305.5602 892.7772,-309.9292"/>
<text text-anchor="middle" x="930.5" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- clinical_measure_file -->
<g id="node6" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M1005.5,-725.5C1005.5,-725.5 1378.5,-725.5 1378.5,-725.5 1384.5,-725.5 1390.5,-731.5 1390.5,-737.5 1390.5,-737.5 1390.5,-989.5 1390.5,-989.5 1390.5,-995.5 1384.5,-1001.5 1378.5,-1001.5 1378.5,-1001.5 1005.5,-1001.5 1005.5,-1001.5 999.5,-1001.5 993.5,-995.5 993.5,-989.5 993.5,-989.5 993.5,-737.5 993.5,-737.5 993.5,-731.5 999.5,-725.5 1005.5,-725.5"/>
<text text-anchor="middle" x="1077" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="1160.5,-725.5 1160.5,-1001.5 "/>
<text text-anchor="middle" x="1171" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1181.5,-725.5 1181.5,-1001.5 "/>
<text text-anchor="middle" x="1275.5" y="-986.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1181.5,-978.5 1369.5,-978.5 "/>
<text text-anchor="middle" x="1275.5" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1181.5,-955.5 1369.5,-955.5 "/>
<text text-anchor="middle" x="1275.5" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file_id</text>
<polyline fill="none" stroke="#000000" points="1181.5,-932.5 1369.5,-932.5 "/>
<text text-anchor="middle" x="1275.5" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1181.5,-909.5 1369.5,-909.5 "/>
<text text-anchor="middle" x="1275.5" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1181.5,-886.5 1369.5,-886.5 "/>
<text text-anchor="middle" x="1275.5" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1181.5,-863.5 1369.5,-863.5 "/>
<text text-anchor="middle" x="1275.5" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1181.5,-840.5 1369.5,-840.5 "/>
<text text-anchor="middle" x="1275.5" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1181.5,-817.5 1369.5,-817.5 "/>
<text text-anchor="middle" x="1275.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1181.5,-794.5 1369.5,-794.5 "/>
<text text-anchor="middle" x="1275.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1181.5,-771.5 1369.5,-771.5 "/>
<text text-anchor="middle" x="1275.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1181.5,-748.5 1369.5,-748.5 "/>
<text text-anchor="middle" x="1275.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="1369.5,-725.5 1369.5,-1001.5 "/>
<text text-anchor="middle" x="1380" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge25" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1138.9429,-725.4285C1116.2324,-661.6078 1091.2532,-584.3037 1075,-513 1059.9909,-447.1541 1049.5147,-373.3946 1042.3949,-309.65"/>
<polygon fill="#000000" stroke="#000000" points="1045.852,-309.0662 1041.2809,-299.5081 1038.8938,-309.8305 1045.852,-309.0662"/>
<text text-anchor="middle" x="1161" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1130.0222,-725.415C1110.164,-658.3199 1104.2485,-581.4852 1153,-531 1172.8868,-510.406 1639.4551,-515.1877 1668,-513 1841.5013,-499.7029 2038.7948,-475.2968 2176.5705,-456.7382"/>
<polygon fill="#000000" stroke="#000000" points="2177.3595,-460.1635 2186.8009,-455.3562 2176.4223,-453.2265 2177.3595,-460.1635"/>
<text text-anchor="middle" x="1282.5" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- follow_up -->
<g id="node7" class="node">
<title>follow_up</title>
<path fill="none" stroke="#000000" d="M4446.5,-760C4446.5,-760 4809.5,-760 4809.5,-760 4815.5,-760 4821.5,-766 4821.5,-772 4821.5,-772 4821.5,-955 4821.5,-955 4821.5,-961 4815.5,-967 4809.5,-967 4809.5,-967 4446.5,-967 4446.5,-967 4440.5,-967 4434.5,-961 4434.5,-955 4434.5,-955 4434.5,-772 4434.5,-772 4434.5,-766 4440.5,-760 4446.5,-760"/>
<text text-anchor="middle" x="4477" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
<polyline fill="none" stroke="#000000" points="4519.5,-760 4519.5,-967 "/>
<text text-anchor="middle" x="4530" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4540.5,-760 4540.5,-967 "/>
<text text-anchor="middle" x="4670.5" y="-951.8" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event</text>
<polyline fill="none" stroke="#000000" points="4540.5,-944 4800.5,-944 "/>
<text text-anchor="middle" x="4670.5" y="-928.8" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity</text>
<polyline fill="none" stroke="#000000" points="4540.5,-921 4800.5,-921 "/>
<text text-anchor="middle" x="4670.5" y="-905.8" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity_method_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="4540.5,-898 4800.5,-898 "/>
<text text-anchor="middle" x="4670.5" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_follow_up</text>
<polyline fill="none" stroke="#000000" points="4540.5,-875 4800.5,-875 "/>
<text text-anchor="middle" x="4670.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_response</text>
<polyline fill="none" stroke="#000000" points="4540.5,-852 4800.5,-852 "/>
<text text-anchor="middle" x="4670.5" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_category</text>
<polyline fill="none" stroke="#000000" points="4540.5,-829 4800.5,-829 "/>
<text text-anchor="middle" x="4670.5" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_id</text>
<polyline fill="none" stroke="#000000" points="4540.5,-806 4800.5,-806 "/>
<text text-anchor="middle" x="4670.5" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_other</text>
<polyline fill="none" stroke="#000000" points="4540.5,-783 4800.5,-783 "/>
<text text-anchor="middle" x="4670.5" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">risk_factor</text>
<polyline fill="none" stroke="#000000" points="4800.5,-760 4800.5,-967 "/>
<text text-anchor="middle" x="4811" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M4586.3229,-759.9678C4553.3479,-692.3194 4500.3935,-608.5392 4426,-564 4301.8108,-489.6484 4246.5144,-539.1676 4102,-531 4014.5228,-526.056 2610.4366,-532.4239 2525,-513 2505.1748,-508.4928 2484.9156,-501.5327 2465.5554,-493.5451"/>
<polygon fill="#000000" stroke="#000000" points="2466.7022,-490.2297 2456.1293,-489.5476 2463.9691,-496.6742 2466.7022,-490.2297"/>
<text text-anchor="middle" x="4435" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- sequencing_file -->
<g id="node8" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M3796.5,-1214.5C3796.5,-1214.5 4265.5,-1214.5 4265.5,-1214.5 4271.5,-1214.5 4277.5,-1220.5 4277.5,-1226.5 4277.5,-1226.5 4277.5,-1800.5 4277.5,-1800.5 4277.5,-1806.5 4271.5,-1812.5 4265.5,-1812.5 4265.5,-1812.5 3796.5,-1812.5 3796.5,-1812.5 3790.5,-1812.5 3784.5,-1806.5 3784.5,-1800.5 3784.5,-1800.5 3784.5,-1226.5 3784.5,-1226.5 3784.5,-1220.5 3790.5,-1214.5 3796.5,-1214.5"/>
<text text-anchor="middle" x="3848.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="3912.5,-1214.5 3912.5,-1812.5 "/>
<text text-anchor="middle" x="3923" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3933.5,-1214.5 3933.5,-1812.5 "/>
<text text-anchor="middle" x="4095" y="-1797.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="3933.5,-1789.5 4256.5,-1789.5 "/>
<text text-anchor="middle" x="4095" y="-1774.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="3933.5,-1766.5 4256.5,-1766.5 "/>
<text text-anchor="middle" x="4095" y="-1751.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="3933.5,-1743.5 4256.5,-1743.5 "/>
<text text-anchor="middle" x="4095" y="-1728.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="3933.5,-1720.5 4256.5,-1720.5 "/>
<text text-anchor="middle" x="4095" y="-1705.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="3933.5,-1697.5 4256.5,-1697.5 "/>
<text text-anchor="middle" x="4095" y="-1682.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="3933.5,-1674.5 4256.5,-1674.5 "/>
<text text-anchor="middle" x="4095" y="-1659.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="3933.5,-1651.5 4256.5,-1651.5 "/>
<text text-anchor="middle" x="4095" y="-1636.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="3933.5,-1628.5 4256.5,-1628.5 "/>
<text text-anchor="middle" x="4095" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="3933.5,-1605.5 4256.5,-1605.5 "/>
<text text-anchor="middle" x="4095" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="3933.5,-1582.5 4256.5,-1582.5 "/>
<text text-anchor="middle" x="4095" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="3933.5,-1559.5 4256.5,-1559.5 "/>
<text text-anchor="middle" x="4095" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="3933.5,-1536.5 4256.5,-1536.5 "/>
<text text-anchor="middle" x="4095" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="3933.5,-1513.5 4256.5,-1513.5 "/>
<text text-anchor="middle" x="4095" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="3933.5,-1490.5 4256.5,-1490.5 "/>
<text text-anchor="middle" x="4095" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="3933.5,-1467.5 4256.5,-1467.5 "/>
<text text-anchor="middle" x="4095" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="3933.5,-1444.5 4256.5,-1444.5 "/>
<text text-anchor="middle" x="4095" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="3933.5,-1421.5 4256.5,-1421.5 "/>
<text text-anchor="middle" x="4095" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="3933.5,-1398.5 4256.5,-1398.5 "/>
<text text-anchor="middle" x="4095" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="3933.5,-1375.5 4256.5,-1375.5 "/>
<text text-anchor="middle" x="4095" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="3933.5,-1352.5 4256.5,-1352.5 "/>
<text text-anchor="middle" x="4095" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="3933.5,-1329.5 4256.5,-1329.5 "/>
<text text-anchor="middle" x="4095" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="3933.5,-1306.5 4256.5,-1306.5 "/>
<text text-anchor="middle" x="4095" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="3933.5,-1283.5 4256.5,-1283.5 "/>
<text text-anchor="middle" x="4095" y="-1268.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="3933.5,-1260.5 4256.5,-1260.5 "/>
<text text-anchor="middle" x="4095" y="-1245.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="3933.5,-1237.5 4256.5,-1237.5 "/>
<text text-anchor="middle" x="4095" y="-1222.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 1 properties</text>
<polyline fill="none" stroke="#000000" points="4256.5,-1214.5 4256.5,-1812.5 "/>
<text text-anchor="middle" x="4267" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node23" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M3195,-783C3195,-783 3509,-783 3509,-783 3515,-783 3521,-789 3521,-795 3521,-795 3521,-932 3521,-932 3521,-938 3515,-944 3509,-944 3509,-944 3195,-944 3195,-944 3189,-944 3183,-938 3183,-932 3183,-932 3183,-795 3183,-795 3183,-789 3189,-783 3195,-783"/>
<text text-anchor="middle" x="3217" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="3251,-783 3251,-944 "/>
<text text-anchor="middle" x="3261.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3272,-783 3272,-944 "/>
<text text-anchor="middle" x="3386" y="-928.8" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="3272,-921 3500,-921 "/>
<text text-anchor="middle" x="3386" y="-905.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="3272,-898 3500,-898 "/>
<text text-anchor="middle" x="3386" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="3272,-875 3500,-875 "/>
<text text-anchor="middle" x="3386" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="3272,-852 3500,-852 "/>
<text text-anchor="middle" x="3386" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="3272,-829 3500,-829 "/>
<text text-anchor="middle" x="3386" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="3272,-806 3500,-806 "/>
<text text-anchor="middle" x="3386" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="3500,-783 3500,-944 "/>
<text text-anchor="middle" x="3510.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3784.2385,-1219.2258C3781.5073,-1217.4453 3778.761,-1215.7027 3776,-1214 3723.4269,-1181.578 3701.5323,-1193.2864 3641,-1181 3592.021,-1171.0586 3571.3143,-1191.1231 3530,-1163 3456.8151,-1113.1823 3409.1298,-1022.4273 3381.709,-953.8309"/>
<polygon fill="#000000" stroke="#000000" points="3384.8829,-952.3374 3377.9737,-944.3053 3378.366,-954.8929 3384.8829,-952.3374"/>
<text text-anchor="middle" x="3803.5" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- synonym -->
<g id="node9" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M1275.5,-1490.5C1275.5,-1490.5 1576.5,-1490.5 1576.5,-1490.5 1582.5,-1490.5 1588.5,-1496.5 1588.5,-1502.5 1588.5,-1502.5 1588.5,-1524.5 1588.5,-1524.5 1588.5,-1530.5 1582.5,-1536.5 1576.5,-1536.5 1576.5,-1536.5 1275.5,-1536.5 1275.5,-1536.5 1269.5,-1536.5 1263.5,-1530.5 1263.5,-1524.5 1263.5,-1524.5 1263.5,-1502.5 1263.5,-1502.5 1263.5,-1496.5 1269.5,-1490.5 1275.5,-1490.5"/>
<text text-anchor="middle" x="1303.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="1343.5,-1490.5 1343.5,-1536.5 "/>
<text text-anchor="middle" x="1354" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1364.5,-1490.5 1364.5,-1536.5 "/>
<text text-anchor="middle" x="1466" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="1364.5,-1513.5 1567.5,-1513.5 "/>
<text text-anchor="middle" x="1466" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="1567.5,-1490.5 1567.5,-1536.5 "/>
<text text-anchor="middle" x="1578" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge13" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1372.2784,-1490.4784C1273.534,-1444.8069 1065.8181,-1332.3013 984,-1163 913.4531,-1017.0215 967.7227,-556.6742 1003.7157,-309.9207"/>
<polygon fill="#000000" stroke="#000000" points="1007.2142,-310.1861 1005.2016,-299.7841 1000.2882,-309.1708 1007.2142,-310.1861"/>
<text text-anchor="middle" x="1017.5" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1424.4477,-1490.1534C1415.4312,-1351.1025 1372.3274,-635.6623 1435,-564 1459.2188,-536.3073 1917.7661,-480.6616 2176.6846,-451.2444"/>
<polygon fill="#000000" stroke="#000000" points="2177.4117,-454.6844 2186.9535,-450.0795 2176.6227,-447.729 2177.4117,-454.6844"/>
<text text-anchor="middle" x="1477.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1465.1238,-1490.4549C1567.0929,-1431.7335 1851.0863,-1276.7097 2110,-1214 2338.0863,-1158.7568 2402.5896,-1192.2655 2637,-1181 2666.8157,-1179.5671 3148.3062,-1178.194 3174,-1163 3251.0747,-1117.422 3298.5319,-1024.4051 3324.852,-954.0554"/>
<polygon fill="#000000" stroke="#000000" points="3328.2771,-954.8803 3328.4265,-944.2865 3321.7033,-952.4749 3328.2771,-954.8803"/>
<text text-anchor="middle" x="2679.5" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- molecular_test -->
<g id="node10" class="node">
<title>molecular_test</title>
<path fill="none" stroke="#000000" d="M1541,-564.5C1541,-564.5 1929,-564.5 1929,-564.5 1935,-564.5 1941,-570.5 1941,-576.5 1941,-576.5 1941,-1150.5 1941,-1150.5 1941,-1156.5 1935,-1162.5 1929,-1162.5 1929,-1162.5 1541,-1162.5 1541,-1162.5 1535,-1162.5 1529,-1156.5 1529,-1150.5 1529,-1150.5 1529,-576.5 1529,-576.5 1529,-570.5 1535,-564.5 1541,-564.5"/>
<text text-anchor="middle" x="1590.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
<polyline fill="none" stroke="#000000" points="1652,-564.5 1652,-1162.5 "/>
<text text-anchor="middle" x="1662.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1673,-564.5 1673,-1162.5 "/>
<text text-anchor="middle" x="1796.5" y="-1147.3" font-family="Times,serif" font-size="14.00" fill="#000000">aa_change</text>
<polyline fill="none" stroke="#000000" points="1673,-1139.5 1920,-1139.5 "/>
<text text-anchor="middle" x="1796.5" y="-1124.3" font-family="Times,serif" font-size="14.00" fill="#000000">antigen</text>
<polyline fill="none" stroke="#000000" points="1673,-1116.5 1920,-1116.5 "/>
<text text-anchor="middle" x="1796.5" y="-1101.3" font-family="Times,serif" font-size="14.00" fill="#000000">biospecimen_type</text>
<polyline fill="none" stroke="#000000" points="1673,-1093.5 1920,-1093.5 "/>
<text text-anchor="middle" x="1796.5" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000">blood_test_normal_range_lower</text>
<polyline fill="none" stroke="#000000" points="1673,-1070.5 1920,-1070.5 "/>
<text text-anchor="middle" x="1796.5" y="-1055.3" font-family="Times,serif" font-size="14.00" fill="#000000">blood_test_normal_range_upper</text>
<polyline fill="none" stroke="#000000" points="1673,-1047.5 1920,-1047.5 "/>
<text text-anchor="middle" x="1796.5" y="-1032.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_count</text>
<polyline fill="none" stroke="#000000" points="1673,-1024.5 1920,-1024.5 "/>
<text text-anchor="middle" x="1796.5" y="-1009.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome</text>
<polyline fill="none" stroke="#000000" points="1673,-1001.5 1920,-1001.5 "/>
<text text-anchor="middle" x="1796.5" y="-986.3" font-family="Times,serif" font-size="14.00" fill="#000000">copy_number</text>
<polyline fill="none" stroke="#000000" points="1673,-978.5 1920,-978.5 "/>
<text text-anchor="middle" x="1796.5" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytoband</text>
<polyline fill="none" stroke="#000000" points="1673,-955.5 1920,-955.5 "/>
<text text-anchor="middle" x="1796.5" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">exon</text>
<polyline fill="none" stroke="#000000" points="1673,-932.5 1920,-932.5 "/>
<text text-anchor="middle" x="1796.5" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">gene_symbol</text>
<polyline fill="none" stroke="#000000" points="1673,-909.5 1920,-909.5 "/>
<text text-anchor="middle" x="1796.5" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">histone_family</text>
<polyline fill="none" stroke="#000000" points="1673,-886.5 1920,-886.5 "/>
<text text-anchor="middle" x="1796.5" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">histone_variant</text>
<polyline fill="none" stroke="#000000" points="1673,-863.5 1920,-863.5 "/>
<text text-anchor="middle" x="1796.5" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">intron</text>
<polyline fill="none" stroke="#000000" points="1673,-840.5 1920,-840.5 "/>
<text text-anchor="middle" x="1796.5" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
<polyline fill="none" stroke="#000000" points="1673,-817.5 1920,-817.5 "/>
<text text-anchor="middle" x="1796.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">loci_abnormal_count</text>
<polyline fill="none" stroke="#000000" points="1673,-794.5 1920,-794.5 "/>
<text text-anchor="middle" x="1796.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">loci_count</text>
<polyline fill="none" stroke="#000000" points="1673,-771.5 1920,-771.5 "/>
<text text-anchor="middle" x="1796.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">locus</text>
<polyline fill="none" stroke="#000000" points="1673,-748.5 1920,-748.5 "/>
<text text-anchor="middle" x="1796.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">mismatch_repair_mutation</text>
<polyline fill="none" stroke="#000000" points="1673,-725.5 1920,-725.5 "/>
<text text-anchor="middle" x="1796.5" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_analysis_method</text>
<polyline fill="none" stroke="#000000" points="1673,-702.5 1920,-702.5 "/>
<text text-anchor="middle" x="1796.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_consequence</text>
<polyline fill="none" stroke="#000000" points="1673,-679.5 1920,-679.5 "/>
<text text-anchor="middle" x="1796.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test_id</text>
<polyline fill="none" stroke="#000000" points="1673,-656.5 1920,-656.5 "/>
<text text-anchor="middle" x="1796.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathogenicity</text>
<polyline fill="none" stroke="#000000" points="1673,-633.5 1920,-633.5 "/>
<text text-anchor="middle" x="1796.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">ploidy</text>
<polyline fill="none" stroke="#000000" points="1673,-610.5 1920,-610.5 "/>
<text text-anchor="middle" x="1796.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">second_exon</text>
<polyline fill="none" stroke="#000000" points="1673,-587.5 1920,-587.5 "/>
<text text-anchor="middle" x="1796.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 11 properties</text>
<polyline fill="none" stroke="#000000" points="1920,-564.5 1920,-1162.5 "/>
<text text-anchor="middle" x="1930.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1941.1734,-570.6888C1944.0905,-568.4082 1947.0329,-566.1775 1950,-564 2016.446,-515.2377 2101.8911,-483.8446 2176.8233,-463.9703"/>
<polygon fill="#000000" stroke="#000000" points="2178.0529,-467.2671 2186.8499,-461.3625 2176.2909,-460.4924 2178.0529,-467.2671"/>
<text text-anchor="middle" x="2061" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node12" class="node">
<title>single_cell_sequencing_file</title>
<path fill="none" stroke="#000000" d="M4307.5,-1214.5C4307.5,-1214.5 4916.5,-1214.5 4916.5,-1214.5 4922.5,-1214.5 4928.5,-1220.5 4928.5,-1226.5 4928.5,-1226.5 4928.5,-1800.5 4928.5,-1800.5 4928.5,-1806.5 4922.5,-1812.5 4916.5,-1812.5 4916.5,-1812.5 4307.5,-1812.5 4307.5,-1812.5 4301.5,-1812.5 4295.5,-1806.5 4295.5,-1800.5 4295.5,-1800.5 4295.5,-1226.5 4295.5,-1226.5 4295.5,-1220.5 4301.5,-1214.5 4307.5,-1214.5"/>
<text text-anchor="middle" x="4401.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
<polyline fill="none" stroke="#000000" points="4507.5,-1214.5 4507.5,-1812.5 "/>
<text text-anchor="middle" x="4518" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4528.5,-1214.5 4528.5,-1812.5 "/>
<text text-anchor="middle" x="4718" y="-1797.3" font-family="Times,serif" font-size="14.00" fill="#000000">Cell_Barcode</text>
<polyline fill="none" stroke="#000000" points="4528.5,-1789.5 4907.5,-1789.5 "/>
<text text-anchor="middle" x="4718" y="-1774.3" font-family="Times,serif" font-size="14.00" fill="#000000">Cryopreserved_Cells_in_Sample</text>
<polyline fill="none" stroke="#000000" points="4528.5,-1766.5 4907.5,-1766.5 "/>
<text text-anchor="middle" x="4718" y="-1751.3" font-family="Times,serif" font-size="14.00" fill="#000000">Dissociation_Method</text>
<polyline fill="none" stroke="#000000" points="4528.5,-1743.5 4907.5,-1743.5 "/>
<text text-anchor="middle" x="4718" y="-1728.3" font-family="Times,serif" font-size="14.00" fill="#000000">End_Bias</text>
<polyline fill="none" stroke="#000000" points="4528.5,-1720.5 4907.5,-1720.5 "/>
<text text-anchor="middle" x="4718" y="-1705.3" font-family="Times,serif" font-size="14.00" fill="#000000">Input_Cells_and_Nuclei</text>
<polyline fill="none" stroke="#000000" points="4528.5,-1697.5 4907.5,-1697.5 "/>
<text text-anchor="middle" x="4718" y="-1682.3" font-family="Times,serif" font-size="14.00" fill="#000000">Library_Construction_Method</text>
<polyline fill="none" stroke="#000000" points="4528.5,-1674.5 4907.5,-1674.5 "/>
<text text-anchor="middle" x="4718" y="-1659.3" font-family="Times,serif" font-size="14.00" fill="#000000">Library_Preparation_Date</text>
<polyline fill="none" stroke="#000000" points="4528.5,-1651.5 4907.5,-1651.5 "/>
<text text-anchor="middle" x="4718" y="-1636.3" font-family="Times,serif" font-size="14.00" fill="#000000">Nucleic_Acid_Capture_Date</text>
<polyline fill="none" stroke="#000000" points="4528.5,-1628.5 4907.5,-1628.5 "/>
<text text-anchor="middle" x="4718" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">Paired_End</text>
<polyline fill="none" stroke="#000000" points="4528.5,-1605.5 4907.5,-1605.5 "/>
<text text-anchor="middle" x="4718" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">Protocols_Link</text>
<polyline fill="none" stroke="#000000" points="4528.5,-1582.5 4907.5,-1582.5 "/>
<text text-anchor="middle" x="4718" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">Read1</text>
<polyline fill="none" stroke="#000000" points="4528.5,-1559.5 4907.5,-1559.5 "/>
<text text-anchor="middle" x="4718" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">Read2</text>
<polyline fill="none" stroke="#000000" points="4528.5,-1536.5 4907.5,-1536.5 "/>
<text text-anchor="middle" x="4718" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Feature_barcoding</text>
<polyline fill="none" stroke="#000000" points="4528.5,-1513.5 4907.5,-1513.5 "/>
<text text-anchor="middle" x="4718" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Oligo_dT_Poly_dT</text>
<polyline fill="none" stroke="#000000" points="4528.5,-1490.5 4907.5,-1490.5 "/>
<text text-anchor="middle" x="4718" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Random</text>
<polyline fill="none" stroke="#000000" points="4528.5,-1467.5 4907.5,-1467.5 "/>
<text text-anchor="middle" x="4718" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">Sequencing_Library_Construction_Date</text>
<polyline fill="none" stroke="#000000" points="4528.5,-1444.5 4907.5,-1444.5 "/>
<text text-anchor="middle" x="4718" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">Single_Cell_Dissociation_Date</text>
<polyline fill="none" stroke="#000000" points="4528.5,-1421.5 4907.5,-1421.5 "/>
<text text-anchor="middle" x="4718" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">Single_Cell_Isolation_Method</text>
<polyline fill="none" stroke="#000000" points="4528.5,-1398.5 4907.5,-1398.5 "/>
<text text-anchor="middle" x="4718" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">Spike_In</text>
<polyline fill="none" stroke="#000000" points="4528.5,-1375.5 4907.5,-1375.5 "/>
<text text-anchor="middle" x="4718" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">Total_Number_of_Input_Cells</text>
<polyline fill="none" stroke="#000000" points="4528.5,-1352.5 4907.5,-1352.5 "/>
<text text-anchor="middle" x="4718" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">UMI</text>
<polyline fill="none" stroke="#000000" points="4528.5,-1329.5 4907.5,-1329.5 "/>
<text text-anchor="middle" x="4718" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="4528.5,-1306.5 4907.5,-1306.5 "/>
<text text-anchor="middle" x="4718" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">cDNA_Length</text>
<polyline fill="none" stroke="#000000" points="4528.5,-1283.5 4907.5,-1283.5 "/>
<text text-anchor="middle" x="4718" y="-1268.3" font-family="Times,serif" font-size="14.00" fill="#000000">cDNA_Offset</text>
<polyline fill="none" stroke="#000000" points="4528.5,-1260.5 4907.5,-1260.5 "/>
<text text-anchor="middle" x="4718" y="-1245.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="4528.5,-1237.5 4907.5,-1237.5 "/>
<text text-anchor="middle" x="4718" y="-1222.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 24 properties</text>
<polyline fill="none" stroke="#000000" points="4907.5,-1214.5 4907.5,-1812.5 "/>
<text text-anchor="middle" x="4918" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M4295.4103,-1217.7911C4292.6157,-1216.4936 4289.8121,-1215.2295 4287,-1214 4118.2798,-1140.2351 4057.7396,-1193.1455 3874,-1181 3835.8088,-1178.4755 3562.7609,-1182.7904 3530,-1163 3453.4801,-1116.7753 3405.9851,-1024.0962 3379.5062,-954.01"/>
<polygon fill="#000000" stroke="#000000" points="3382.6588,-952.4438 3375.9086,-944.2777 3376.093,-954.8709 3382.6588,-952.4438"/>
<text text-anchor="middle" x="4347.5" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- pdx -->
<g id="node13" class="node">
<title>pdx</title>
<path fill="none" stroke="#000000" d="M2130.5,-1398.5C2130.5,-1398.5 2459.5,-1398.5 2459.5,-1398.5 2465.5,-1398.5 2471.5,-1404.5 2471.5,-1410.5 2471.5,-1410.5 2471.5,-1616.5 2471.5,-1616.5 2471.5,-1622.5 2465.5,-1628.5 2459.5,-1628.5 2459.5,-1628.5 2130.5,-1628.5 2130.5,-1628.5 2124.5,-1628.5 2118.5,-1622.5 2118.5,-1616.5 2118.5,-1616.5 2118.5,-1410.5 2118.5,-1410.5 2118.5,-1404.5 2124.5,-1398.5 2130.5,-1398.5"/>
<text text-anchor="middle" x="2140" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
<polyline fill="none" stroke="#000000" points="2161.5,-1398.5 2161.5,-1628.5 "/>
<text text-anchor="middle" x="2172" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2182.5,-1398.5 2182.5,-1628.5 "/>
<text text-anchor="middle" x="2316.5" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_site</text>
<polyline fill="none" stroke="#000000" points="2182.5,-1605.5 2450.5,-1605.5 "/>
<text text-anchor="middle" x="2316.5" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_type</text>
<polyline fill="none" stroke="#000000" points="2182.5,-1582.5 2450.5,-1582.5 "/>
<text text-anchor="middle" x="2316.5" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_id</text>
<polyline fill="none" stroke="#000000" points="2182.5,-1559.5 2450.5,-1559.5 "/>
<text text-anchor="middle" x="2316.5" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">mouse_strain</text>
<polyline fill="none" stroke="#000000" points="2182.5,-1536.5 2450.5,-1536.5 "/>
<text text-anchor="middle" x="2316.5" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx_id</text>
<polyline fill="none" stroke="#000000" points="2182.5,-1513.5 2450.5,-1513.5 "/>
<text text-anchor="middle" x="2316.5" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">strain_immune_system_humanized</text>
<polyline fill="none" stroke="#000000" points="2182.5,-1490.5 2450.5,-1490.5 "/>
<text text-anchor="middle" x="2316.5" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_characterization_method</text>
<polyline fill="none" stroke="#000000" points="2182.5,-1467.5 2450.5,-1467.5 "/>
<text text-anchor="middle" x="2316.5" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_not_mus_or_ebv_origin</text>
<polyline fill="none" stroke="#000000" points="2182.5,-1444.5 2450.5,-1444.5 "/>
<text text-anchor="middle" x="2316.5" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_preparation</text>
<polyline fill="none" stroke="#000000" points="2182.5,-1421.5 2450.5,-1421.5 "/>
<text text-anchor="middle" x="2316.5" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_humanization</text>
<polyline fill="none" stroke="#000000" points="2450.5,-1398.5 2450.5,-1628.5 "/>
<text text-anchor="middle" x="2461" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2335.8367,-1398.3324C2365.4855,-1332.6743 2412.5341,-1255.4377 2481,-1214 2489.2566,-1209.0029 3165.7926,-1168.0774 3174,-1163 3249.9032,-1116.0434 3297.4436,-1023.7123 3324.0999,-953.9157"/>
<polygon fill="#000000" stroke="#000000" points="3327.4998,-954.8162 3327.7234,-944.2238 3320.943,-952.3649 3327.4998,-954.8162"/>
<text text-anchor="middle" x="2952" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study_funding -->
<g id="node14" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M1268.5,-386C1268.5,-386 1647.5,-386 1647.5,-386 1653.5,-386 1659.5,-392 1659.5,-398 1659.5,-398 1659.5,-466 1659.5,-466 1659.5,-472 1653.5,-478 1647.5,-478 1647.5,-478 1268.5,-478 1268.5,-478 1262.5,-478 1256.5,-472 1256.5,-466 1256.5,-466 1256.5,-398 1256.5,-398 1256.5,-392 1262.5,-386 1268.5,-386"/>
<text text-anchor="middle" x="1316" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="1375.5,-386 1375.5,-478 "/>
<text text-anchor="middle" x="1386" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1396.5,-386 1396.5,-478 "/>
<text text-anchor="middle" x="1517.5" y="-462.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="1396.5,-455 1638.5,-455 "/>
<text text-anchor="middle" x="1517.5" y="-439.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="1396.5,-432 1638.5,-432 "/>
<text text-anchor="middle" x="1517.5" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="1396.5,-409 1638.5,-409 "/>
<text text-anchor="middle" x="1517.5" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding_id</text>
<polyline fill="none" stroke="#000000" points="1638.5,-386 1638.5,-478 "/>
<text text-anchor="middle" x="1649" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge4" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1387.6398,-385.7492C1348.1221,-359.7726 1296.4561,-325.8103 1244.6973,-291.787"/>
<polygon fill="#000000" stroke="#000000" points="1246.3331,-288.6738 1236.0542,-286.1056 1242.488,-294.5233 1246.3331,-288.6738"/>
<text text-anchor="middle" x="1369" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- medical_history -->
<g id="node15" class="node">
<title>medical_history</title>
<path fill="none" stroke="#000000" d="M1971,-829C1971,-829 2325,-829 2325,-829 2331,-829 2337,-835 2337,-841 2337,-841 2337,-886 2337,-886 2337,-892 2331,-898 2325,-898 2325,-898 1971,-898 1971,-898 1965,-898 1959,-892 1959,-886 1959,-886 1959,-841 1959,-841 1959,-835 1965,-829 1971,-829"/>
<text text-anchor="middle" x="2024.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
<polyline fill="none" stroke="#000000" points="2090,-829 2090,-898 "/>
<text text-anchor="middle" x="2100.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2111,-829 2111,-898 "/>
<text text-anchor="middle" x="2213.5" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_category</text>
<polyline fill="none" stroke="#000000" points="2111,-875 2316,-875 "/>
<text text-anchor="middle" x="2213.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_condition</text>
<polyline fill="none" stroke="#000000" points="2111,-852 2316,-852 "/>
<text text-anchor="middle" x="2213.5" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_id</text>
<polyline fill="none" stroke="#000000" points="2316,-829 2316,-898 "/>
<text text-anchor="middle" x="2326.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2164.2692,-828.918C2197.9585,-757.3074 2275.8582,-591.7225 2319.6518,-498.6343"/>
<polygon fill="#000000" stroke="#000000" points="2322.8204,-500.1208 2323.9103,-489.5822 2316.4863,-497.1409 2322.8204,-500.1208"/>
<text text-anchor="middle" x="2369" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge24" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2186.9064,-396.9967C1949.5777,-346.3713 1510.1238,-252.63 1246.1717,-196.3256"/>
<polygon fill="#000000" stroke="#000000" points="1246.5876,-192.8356 1236.0774,-194.1723 1245.1272,-199.6816 1246.5876,-192.8356"/>
<text text-anchor="middle" x="1936.5" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sample_diagnosis -->
<g id="node17" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M2501.5,-1364C2501.5,-1364 2934.5,-1364 2934.5,-1364 2940.5,-1364 2946.5,-1370 2946.5,-1376 2946.5,-1376 2946.5,-1651 2946.5,-1651 2946.5,-1657 2940.5,-1663 2934.5,-1663 2934.5,-1663 2501.5,-1663 2501.5,-1663 2495.5,-1663 2489.5,-1657 2489.5,-1651 2489.5,-1651 2489.5,-1376 2489.5,-1376 2489.5,-1370 2495.5,-1364 2501.5,-1364"/>
<text text-anchor="middle" x="2561" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2632.5,-1364 2632.5,-1663 "/>
<text text-anchor="middle" x="2643" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2653.5,-1364 2653.5,-1663 "/>
<text text-anchor="middle" x="2789.5" y="-1647.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="2653.5,-1640 2925.5,-1640 "/>
<text text-anchor="middle" x="2789.5" y="-1624.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2653.5,-1617 2925.5,-1617 "/>
<text text-anchor="middle" x="2789.5" y="-1601.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="2653.5,-1594 2925.5,-1594 "/>
<text text-anchor="middle" x="2789.5" y="-1578.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="2653.5,-1571 2925.5,-1571 "/>
<text text-anchor="middle" x="2789.5" y="-1555.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="2653.5,-1548 2925.5,-1548 "/>
<text text-anchor="middle" x="2789.5" y="-1532.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="2653.5,-1525 2925.5,-1525 "/>
<text text-anchor="middle" x="2789.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2653.5,-1502 2925.5,-1502 "/>
<text text-anchor="middle" x="2789.5" y="-1486.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="2653.5,-1479 2925.5,-1479 "/>
<text text-anchor="middle" x="2789.5" y="-1463.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="2653.5,-1456 2925.5,-1456 "/>
<text text-anchor="middle" x="2789.5" y="-1440.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="2653.5,-1433 2925.5,-1433 "/>
<text text-anchor="middle" x="2789.5" y="-1417.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="2653.5,-1410 2925.5,-1410 "/>
<text text-anchor="middle" x="2789.5" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="2653.5,-1387 2925.5,-1387 "/>
<text text-anchor="middle" x="2789.5" y="-1371.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="2925.5,-1364 2925.5,-1663 "/>
<text text-anchor="middle" x="2936" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2806.4007,-1363.9338C2845.7408,-1309.2206 2896.6668,-1251.5813 2956,-1214 3010.3711,-1179.5616 3034.3314,-1195.6585 3097,-1181 3131.2212,-1172.9955 3145.6456,-1183.765 3174,-1163 3245.0766,-1110.9479 3292.894,-1021.1781 3320.9114,-953.4582"/>
<polygon fill="#000000" stroke="#000000" points="3324.2102,-954.6371 3324.7337,-944.0552 3317.7255,-952.001 3324.2102,-954.6371"/>
<text text-anchor="middle" x="3171" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
<!-- study_personnel -->
<g id="node18" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M2545.5,-374.5C2545.5,-374.5 2852.5,-374.5 2852.5,-374.5 2858.5,-374.5 2864.5,-380.5 2864.5,-386.5 2864.5,-386.5 2864.5,-477.5 2864.5,-477.5 2864.5,-483.5 2858.5,-489.5 2852.5,-489.5 2852.5,-489.5 2545.5,-489.5 2545.5,-489.5 2539.5,-489.5 2533.5,-483.5 2533.5,-477.5 2533.5,-477.5 2533.5,-386.5 2533.5,-386.5 2533.5,-380.5 2539.5,-374.5 2545.5,-374.5"/>
<text text-anchor="middle" x="2600.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="2667.5,-374.5 2667.5,-489.5 "/>
<text text-anchor="middle" x="2678" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2688.5,-374.5 2688.5,-489.5 "/>
<text text-anchor="middle" x="2766" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="2688.5,-466.5 2843.5,-466.5 "/>
<text text-anchor="middle" x="2766" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="2688.5,-443.5 2843.5,-443.5 "/>
<text text-anchor="middle" x="2766" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="2688.5,-420.5 2843.5,-420.5 "/>
<text text-anchor="middle" x="2766" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="2688.5,-397.5 2843.5,-397.5 "/>
<text text-anchor="middle" x="2766" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="2843.5,-374.5 2843.5,-489.5 "/>
<text text-anchor="middle" x="2854" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge6" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2587.4798,-374.3865C2566.7886,-365.4336 2545.0527,-357.1353 2524,-351 2081.7081,-222.1055 1541.3394,-175.4432 1246.5316,-158.8624"/>
<polygon fill="#000000" stroke="#000000" points="1246.3274,-155.3458 1236.1485,-158.2852 1245.9388,-162.335 1246.3274,-155.3458"/>
<text text-anchor="middle" x="2514.5" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- imaging_file -->
<g id="node19" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M2976.5,-1318C2976.5,-1318 3317.5,-1318 3317.5,-1318 3323.5,-1318 3329.5,-1324 3329.5,-1330 3329.5,-1330 3329.5,-1697 3329.5,-1697 3329.5,-1703 3323.5,-1709 3317.5,-1709 3317.5,-1709 2976.5,-1709 2976.5,-1709 2970.5,-1709 2964.5,-1703 2964.5,-1697 2964.5,-1697 2964.5,-1330 2964.5,-1330 2964.5,-1324 2970.5,-1318 2976.5,-1318"/>
<text text-anchor="middle" x="3016.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="3068.5,-1318 3068.5,-1709 "/>
<text text-anchor="middle" x="3079" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3089.5,-1318 3089.5,-1709 "/>
<text text-anchor="middle" x="3199" y="-1693.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="3089.5,-1686 3308.5,-1686 "/>
<text text-anchor="middle" x="3199" y="-1670.8" font-family="Times,serif" font-size="14.00" fill="#000000">deidentification_method</text>
<polyline fill="none" stroke="#000000" points="3089.5,-1663 3308.5,-1663 "/>
<text text-anchor="middle" x="3199" y="-1647.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="3089.5,-1640 3308.5,-1640 "/>
<text text-anchor="middle" x="3199" y="-1624.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="3089.5,-1617 3308.5,-1617 "/>
<text text-anchor="middle" x="3199" y="-1601.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="3089.5,-1594 3308.5,-1594 "/>
<text text-anchor="middle" x="3199" y="-1578.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="3089.5,-1571 3308.5,-1571 "/>
<text text-anchor="middle" x="3199" y="-1555.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="3089.5,-1548 3308.5,-1548 "/>
<text text-anchor="middle" x="3199" y="-1532.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="3089.5,-1525 3308.5,-1525 "/>
<text text-anchor="middle" x="3199" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">fixation_embedding_method</text>
<polyline fill="none" stroke="#000000" points="3089.5,-1502 3308.5,-1502 "/>
<text text-anchor="middle" x="3199" y="-1486.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="3089.5,-1479 3308.5,-1479 "/>
<text text-anchor="middle" x="3199" y="-1463.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file_id</text>
<polyline fill="none" stroke="#000000" points="3089.5,-1456 3308.5,-1456 "/>
<text text-anchor="middle" x="3199" y="-1440.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="3089.5,-1433 3308.5,-1433 "/>
<text text-anchor="middle" x="3199" y="-1417.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="3089.5,-1410 3308.5,-1410 "/>
<text text-anchor="middle" x="3199" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">magnification</text>
<polyline fill="none" stroke="#000000" points="3089.5,-1387 3308.5,-1387 "/>
<text text-anchor="middle" x="3199" y="-1371.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="3089.5,-1364 3308.5,-1364 "/>
<text text-anchor="middle" x="3199" y="-1348.8" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="3089.5,-1341 3308.5,-1341 "/>
<text text-anchor="middle" x="3199" y="-1325.8" font-family="Times,serif" font-size="14.00" fill="#000000">staining_method</text>
<polyline fill="none" stroke="#000000" points="3308.5,-1318 3308.5,-1709 "/>
<text text-anchor="middle" x="3319" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3208.7848,-1317.5971C3246.8718,-1196.8333 3293.9147,-1047.673 3323.447,-954.0339"/>
<polygon fill="#000000" stroke="#000000" points="3326.8455,-954.8944 3326.5154,-944.3047 3320.1696,-952.7889 3326.8455,-954.8944"/>
<text text-anchor="middle" x="3303.5" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- diagnosis -->
<g id="node20" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M2367,-668C2367,-668 2741,-668 2741,-668 2747,-668 2753,-674 2753,-680 2753,-680 2753,-1047 2753,-1047 2753,-1053 2747,-1059 2741,-1059 2741,-1059 2367,-1059 2367,-1059 2361,-1059 2355,-1053 2355,-1047 2355,-1047 2355,-680 2355,-680 2355,-674 2361,-668 2367,-668"/>
<text text-anchor="middle" x="2397" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="2439,-668 2439,-1059 "/>
<text text-anchor="middle" x="2449.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2460,-668 2460,-1059 "/>
<text text-anchor="middle" x="2596" y="-1043.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2460,-1036 2732,-1036 "/>
<text text-anchor="middle" x="2596" y="-1020.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="2460,-1013 2732,-1013 "/>
<text text-anchor="middle" x="2596" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="2460,-990 2732,-990 "/>
<text text-anchor="middle" x="2596" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2460,-967 2732,-967 "/>
<text text-anchor="middle" x="2596" y="-951.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="2460,-944 2732,-944 "/>
<text text-anchor="middle" x="2596" y="-928.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="2460,-921 2732,-921 "/>
<text text-anchor="middle" x="2596" y="-905.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="2460,-898 2732,-898 "/>
<text text-anchor="middle" x="2596" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="2460,-875 2732,-875 "/>
<text text-anchor="middle" x="2596" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="2460,-852 2732,-852 "/>
<text text-anchor="middle" x="2596" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="2460,-829 2732,-829 "/>
<text text-anchor="middle" x="2596" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2460,-806 2732,-806 "/>
<text text-anchor="middle" x="2596" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="2460,-783 2732,-783 "/>
<text text-anchor="middle" x="2596" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="2460,-760 2732,-760 "/>
<text text-anchor="middle" x="2596" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="2460,-737 2732,-737 "/>
<text text-anchor="middle" x="2596" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="2460,-714 2732,-714 "/>
<text text-anchor="middle" x="2596" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="2460,-691 2732,-691 "/>
<text text-anchor="middle" x="2596" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="2732,-668 2732,-1059 "/>
<text text-anchor="middle" x="2742.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2502.3331,-667.6954C2486.0954,-621.2428 2465.7711,-573.0161 2441,-531 2434.1652,-519.4069 2425.8142,-507.9905 2416.9835,-497.2646"/>
<polygon fill="#000000" stroke="#000000" points="2419.6151,-494.9563 2410.4834,-489.5839 2414.2718,-499.4783 2419.6151,-494.9563"/>
<text text-anchor="middle" x="2489.5" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- family_relationship -->
<g id="node21" class="node">
<title>family_relationship</title>
<path fill="none" stroke="#000000" d="M2783.5,-817.5C2783.5,-817.5 3152.5,-817.5 3152.5,-817.5 3158.5,-817.5 3164.5,-823.5 3164.5,-829.5 3164.5,-829.5 3164.5,-897.5 3164.5,-897.5 3164.5,-903.5 3158.5,-909.5 3152.5,-909.5 3152.5,-909.5 2783.5,-909.5 2783.5,-909.5 2777.5,-909.5 2771.5,-903.5 2771.5,-897.5 2771.5,-897.5 2771.5,-829.5 2771.5,-829.5 2771.5,-823.5 2777.5,-817.5 2783.5,-817.5"/>
<text text-anchor="middle" x="2848.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
<polyline fill="none" stroke="#000000" points="2925.5,-817.5 2925.5,-909.5 "/>
<text text-anchor="middle" x="2936" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2946.5,-817.5 2946.5,-909.5 "/>
<text text-anchor="middle" x="3045" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_id</text>
<polyline fill="none" stroke="#000000" points="2946.5,-886.5 3143.5,-886.5 "/>
<text text-anchor="middle" x="3045" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship_id</text>
<polyline fill="none" stroke="#000000" points="2946.5,-863.5 3143.5,-863.5 "/>
<text text-anchor="middle" x="3045" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">related_to_participant_id</text>
<polyline fill="none" stroke="#000000" points="2946.5,-840.5 3143.5,-840.5 "/>
<text text-anchor="middle" x="3045" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">relationship</text>
<polyline fill="none" stroke="#000000" points="3143.5,-817.5 3143.5,-909.5 "/>
<text text-anchor="middle" x="3154" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2949.5121,-817.2552C2920.2357,-750.2808 2856.6452,-627.3877 2762,-564 2672.4783,-504.0438 2627.1447,-547.2833 2525,-513 2508.3416,-507.4089 2491.1628,-500.6841 2474.3849,-493.53"/>
<polygon fill="#000000" stroke="#000000" points="2475.6785,-490.2761 2465.111,-489.5158 2472.8978,-496.7002 2475.6785,-490.2761"/>
<text text-anchor="middle" x="2805.5" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- methylation_array_file -->
<g id="node22" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M3359.5,-1387C3359.5,-1387 3754.5,-1387 3754.5,-1387 3760.5,-1387 3766.5,-1393 3766.5,-1399 3766.5,-1399 3766.5,-1628 3766.5,-1628 3766.5,-1634 3760.5,-1640 3754.5,-1640 3754.5,-1640 3359.5,-1640 3359.5,-1640 3353.5,-1640 3347.5,-1634 3347.5,-1628 3347.5,-1628 3347.5,-1399 3347.5,-1399 3347.5,-1393 3353.5,-1387 3359.5,-1387"/>
<text text-anchor="middle" x="3436.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="3525.5,-1387 3525.5,-1640 "/>
<text text-anchor="middle" x="3536" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3546.5,-1387 3546.5,-1640 "/>
<text text-anchor="middle" x="3646" y="-1624.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="3546.5,-1617 3745.5,-1617 "/>
<text text-anchor="middle" x="3646" y="-1601.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="3546.5,-1594 3745.5,-1594 "/>
<text text-anchor="middle" x="3646" y="-1578.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="3546.5,-1571 3745.5,-1571 "/>
<text text-anchor="middle" x="3646" y="-1555.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="3546.5,-1548 3745.5,-1548 "/>
<text text-anchor="middle" x="3646" y="-1532.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="3546.5,-1525 3745.5,-1525 "/>
<text text-anchor="middle" x="3646" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="3546.5,-1502 3745.5,-1502 "/>
<text text-anchor="middle" x="3646" y="-1486.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="3546.5,-1479 3745.5,-1479 "/>
<text text-anchor="middle" x="3646" y="-1463.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="3546.5,-1456 3745.5,-1456 "/>
<text text-anchor="middle" x="3646" y="-1440.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file_id</text>
<polyline fill="none" stroke="#000000" points="3546.5,-1433 3745.5,-1433 "/>
<text text-anchor="middle" x="3646" y="-1417.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="3546.5,-1410 3745.5,-1410 "/>
<text text-anchor="middle" x="3646" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="3745.5,-1387 3745.5,-1640 "/>
<text text-anchor="middle" x="3756" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3516.9873,-1386.6304C3476.8504,-1259.3672 3416.0422,-1066.5608 3380.544,-954.0053"/>
<polygon fill="#000000" stroke="#000000" points="3383.8515,-952.856 3377.5057,-944.3718 3377.1757,-954.9615 3383.8515,-952.856"/>
<text text-anchor="middle" x="3545.5" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3326.9753,-782.8726C3300.7093,-712.7452 3252.1743,-614.6514 3174,-564 3052.5903,-485.335 2665.4324,-547.7454 2525,-513 2505.9071,-508.2761 2486.3682,-501.4242 2467.6041,-493.6769"/>
<polygon fill="#000000" stroke="#000000" points="2468.7389,-490.3566 2458.1657,-489.6794 2466.0089,-496.8023 2468.7389,-490.3566"/>
<text text-anchor="middle" x="3166.5" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
</g>
</svg>
</div>
