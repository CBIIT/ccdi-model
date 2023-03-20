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
<svg width="5171pt" height="1965pt"
 viewBox="0.00 0.00 5170.50 1965.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1961)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1961 5166.5,-1961 5166.5,4 -4,4"/>
<!-- study_arm -->
<g id="node1" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M3416,-374.5C3416,-374.5 3713,-374.5 3713,-374.5 3719,-374.5 3725,-380.5 3725,-386.5 3725,-386.5 3725,-431.5 3725,-431.5 3725,-437.5 3719,-443.5 3713,-443.5 3713,-443.5 3416,-443.5 3416,-443.5 3410,-443.5 3404,-437.5 3404,-431.5 3404,-431.5 3404,-386.5 3404,-386.5 3404,-380.5 3410,-374.5 3416,-374.5"/>
<text text-anchor="middle" x="3450" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="3496,-374.5 3496,-443.5 "/>
<text text-anchor="middle" x="3506.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3517,-374.5 3517,-443.5 "/>
<text text-anchor="middle" x="3610.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="3517,-420.5 3704,-420.5 "/>
<text text-anchor="middle" x="3610.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="3517,-397.5 3704,-397.5 "/>
<text text-anchor="middle" x="3610.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="3704,-374.5 3704,-443.5 "/>
<text text-anchor="middle" x="3714.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node3" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M3749.5,-.5C3749.5,-.5 4139.5,-.5 4139.5,-.5 4145.5,-.5 4151.5,-6.5 4151.5,-12.5 4151.5,-12.5 4151.5,-264.5 4151.5,-264.5 4151.5,-270.5 4145.5,-276.5 4139.5,-276.5 4139.5,-276.5 3749.5,-276.5 3749.5,-276.5 3743.5,-276.5 3737.5,-270.5 3737.5,-264.5 3737.5,-264.5 3737.5,-12.5 3737.5,-12.5 3737.5,-6.5 3743.5,-.5 3749.5,-.5"/>
<text text-anchor="middle" x="3765.5" y="-134.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="3793.5,-.5 3793.5,-276.5 "/>
<text text-anchor="middle" x="3804" y="-134.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3814.5,-.5 3814.5,-276.5 "/>
<text text-anchor="middle" x="3972.5" y="-261.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="3814.5,-253.5 4130.5,-253.5 "/>
<text text-anchor="middle" x="3972.5" y="-238.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="3814.5,-230.5 4130.5,-230.5 "/>
<text text-anchor="middle" x="3972.5" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_shorthand</text>
<polyline fill="none" stroke="#000000" points="3814.5,-207.5 4130.5,-207.5 "/>
<text text-anchor="middle" x="3972.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="3814.5,-184.5 4130.5,-184.5 "/>
<text text-anchor="middle" x="3972.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="3814.5,-161.5 4130.5,-161.5 "/>
<text text-anchor="middle" x="3972.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="3814.5,-138.5 4130.5,-138.5 "/>
<text text-anchor="middle" x="3972.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="3814.5,-115.5 4130.5,-115.5 "/>
<text text-anchor="middle" x="3972.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="3814.5,-92.5 4130.5,-92.5 "/>
<text text-anchor="middle" x="3972.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="3814.5,-69.5 4130.5,-69.5 "/>
<text text-anchor="middle" x="3972.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="3814.5,-46.5 4130.5,-46.5 "/>
<text text-anchor="middle" x="3972.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="3814.5,-23.5 4130.5,-23.5 "/>
<text text-anchor="middle" x="3972.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="4130.5,-.5 4130.5,-276.5 "/>
<text text-anchor="middle" x="4141" y="-134.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge11" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3613.0132,-374.4662C3646.586,-350.5677 3693.7558,-316.9903 3742.0047,-282.6447"/>
<polygon fill="#000000" stroke="#000000" points="3744.2699,-285.3285 3750.3869,-276.6779 3740.2104,-279.6257 3744.2699,-285.3285"/>
<text text-anchor="middle" x="3769" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- family_relationship -->
<g id="node2" class="node">
<title>family_relationship</title>
<path fill="none" stroke="#000000" d="M2052,-973C2052,-973 2421,-973 2421,-973 2427,-973 2433,-979 2433,-985 2433,-985 2433,-1030 2433,-1030 2433,-1036 2427,-1042 2421,-1042 2421,-1042 2052,-1042 2052,-1042 2046,-1042 2040,-1036 2040,-1030 2040,-1030 2040,-985 2040,-985 2040,-979 2046,-973 2052,-973"/>
<text text-anchor="middle" x="2117" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
<polyline fill="none" stroke="#000000" points="2194,-973 2194,-1042 "/>
<text text-anchor="middle" x="2204.5" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2215,-973 2215,-1042 "/>
<text text-anchor="middle" x="2313.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">family_id</text>
<polyline fill="none" stroke="#000000" points="2215,-1019 2412,-1019 "/>
<text text-anchor="middle" x="2313.5" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">related_to_participant_id</text>
<polyline fill="none" stroke="#000000" points="2215,-996 2412,-996 "/>
<text text-anchor="middle" x="2313.5" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">relationship</text>
<polyline fill="none" stroke="#000000" points="2412,-973 2412,-1042 "/>
<text text-anchor="middle" x="2422.5" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node8" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M3088.5,-541.5C3088.5,-541.5 3392.5,-541.5 3392.5,-541.5 3398.5,-541.5 3404.5,-547.5 3404.5,-553.5 3404.5,-553.5 3404.5,-644.5 3404.5,-644.5 3404.5,-650.5 3398.5,-656.5 3392.5,-656.5 3392.5,-656.5 3088.5,-656.5 3088.5,-656.5 3082.5,-656.5 3076.5,-650.5 3076.5,-644.5 3076.5,-644.5 3076.5,-553.5 3076.5,-553.5 3076.5,-547.5 3082.5,-541.5 3088.5,-541.5"/>
<text text-anchor="middle" x="3124.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="3172.5,-541.5 3172.5,-656.5 "/>
<text text-anchor="middle" x="3183" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3193.5,-541.5 3193.5,-656.5 "/>
<text text-anchor="middle" x="3288.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="3193.5,-633.5 3383.5,-633.5 "/>
<text text-anchor="middle" x="3288.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="3193.5,-610.5 3383.5,-610.5 "/>
<text text-anchor="middle" x="3288.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="3193.5,-587.5 3383.5,-587.5 "/>
<text text-anchor="middle" x="3288.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="3193.5,-564.5 3383.5,-564.5 "/>
<text text-anchor="middle" x="3288.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="3383.5,-541.5 3383.5,-656.5 "/>
<text text-anchor="middle" x="3394" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2249.9161,-972.8698C2276.3367,-909.5312 2341.3811,-775.3513 2441.5,-708 2540.5975,-641.3358 2862.5168,-615.1149 3066.225,-605.0401"/>
<polygon fill="#000000" stroke="#000000" points="3066.621,-608.525 3076.4392,-604.5435 3066.281,-601.5333 3066.621,-608.525"/>
<text text-anchor="middle" x="2595" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- diagnosis -->
<g id="node4" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M4269.5,-812C4269.5,-812 4643.5,-812 4643.5,-812 4649.5,-812 4655.5,-818 4655.5,-824 4655.5,-824 4655.5,-1191 4655.5,-1191 4655.5,-1197 4649.5,-1203 4643.5,-1203 4643.5,-1203 4269.5,-1203 4269.5,-1203 4263.5,-1203 4257.5,-1197 4257.5,-1191 4257.5,-1191 4257.5,-824 4257.5,-824 4257.5,-818 4263.5,-812 4269.5,-812"/>
<text text-anchor="middle" x="4299.5" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="4341.5,-812 4341.5,-1203 "/>
<text text-anchor="middle" x="4352" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4362.5,-812 4362.5,-1203 "/>
<text text-anchor="middle" x="4498.5" y="-1187.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="4362.5,-1180 4634.5,-1180 "/>
<text text-anchor="middle" x="4498.5" y="-1164.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="4362.5,-1157 4634.5,-1157 "/>
<text text-anchor="middle" x="4498.5" y="-1141.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="4362.5,-1134 4634.5,-1134 "/>
<text text-anchor="middle" x="4498.5" y="-1118.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="4362.5,-1111 4634.5,-1111 "/>
<text text-anchor="middle" x="4498.5" y="-1095.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="4362.5,-1088 4634.5,-1088 "/>
<text text-anchor="middle" x="4498.5" y="-1072.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="4362.5,-1065 4634.5,-1065 "/>
<text text-anchor="middle" x="4498.5" y="-1049.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="4362.5,-1042 4634.5,-1042 "/>
<text text-anchor="middle" x="4498.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="4362.5,-1019 4634.5,-1019 "/>
<text text-anchor="middle" x="4498.5" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="4362.5,-996 4634.5,-996 "/>
<text text-anchor="middle" x="4498.5" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="4362.5,-973 4634.5,-973 "/>
<text text-anchor="middle" x="4498.5" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="4362.5,-950 4634.5,-950 "/>
<text text-anchor="middle" x="4498.5" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="4362.5,-927 4634.5,-927 "/>
<text text-anchor="middle" x="4498.5" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="4362.5,-904 4634.5,-904 "/>
<text text-anchor="middle" x="4498.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="4362.5,-881 4634.5,-881 "/>
<text text-anchor="middle" x="4498.5" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="4362.5,-858 4634.5,-858 "/>
<text text-anchor="middle" x="4498.5" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="4362.5,-835 4634.5,-835 "/>
<text text-anchor="middle" x="4498.5" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="4634.5,-812 4634.5,-1203 "/>
<text text-anchor="middle" x="4645" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M4356.7824,-811.8469C4327.2895,-771.3845 4291.2135,-733.4002 4248.5,-708 4178.6227,-666.4464 3684.6185,-628.1002 3415.0462,-609.9739"/>
<polygon fill="#000000" stroke="#000000" points="3414.9716,-606.4611 3404.76,-609.2847 3414.5036,-613.4454 3414.9716,-606.4611"/>
<text text-anchor="middle" x="4226" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- study_admin -->
<g id="node5" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M2910.5,-328.5C2910.5,-328.5 3236.5,-328.5 3236.5,-328.5 3242.5,-328.5 3248.5,-334.5 3248.5,-340.5 3248.5,-340.5 3248.5,-477.5 3248.5,-477.5 3248.5,-483.5 3242.5,-489.5 3236.5,-489.5 3236.5,-489.5 2910.5,-489.5 2910.5,-489.5 2904.5,-489.5 2898.5,-483.5 2898.5,-477.5 2898.5,-477.5 2898.5,-340.5 2898.5,-340.5 2898.5,-334.5 2904.5,-328.5 2910.5,-328.5"/>
<text text-anchor="middle" x="2952.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="3006.5,-328.5 3006.5,-489.5 "/>
<text text-anchor="middle" x="3017" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3027.5,-328.5 3027.5,-489.5 "/>
<text text-anchor="middle" x="3127.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="3027.5,-466.5 3227.5,-466.5 "/>
<text text-anchor="middle" x="3127.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="3027.5,-443.5 3227.5,-443.5 "/>
<text text-anchor="middle" x="3127.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="3027.5,-420.5 3227.5,-420.5 "/>
<text text-anchor="middle" x="3127.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="3027.5,-397.5 3227.5,-397.5 "/>
<text text-anchor="middle" x="3127.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="3027.5,-374.5 3227.5,-374.5 "/>
<text text-anchor="middle" x="3127.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="3027.5,-351.5 3227.5,-351.5 "/>
<text text-anchor="middle" x="3127.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="3227.5,-328.5 3227.5,-489.5 "/>
<text text-anchor="middle" x="3238" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge22" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3120.7574,-328.4934C3131.4033,-315.6725 3143.7013,-303.7675 3157.5,-295 3250.2916,-236.0416 3527.8231,-190.2942 3727.0211,-163.8792"/>
<polygon fill="#000000" stroke="#000000" points="3727.5847,-167.3353 3737.0413,-162.558 3726.6696,-160.3954 3727.5847,-167.3353"/>
<text text-anchor="middle" x="3214" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node6" class="node">
<title>single_cell_sequencing_file</title>
<path fill="none" stroke="#000000" d="M1644,-1358.5C1644,-1358.5 2253,-1358.5 2253,-1358.5 2259,-1358.5 2265,-1364.5 2265,-1370.5 2265,-1370.5 2265,-1944.5 2265,-1944.5 2265,-1950.5 2259,-1956.5 2253,-1956.5 2253,-1956.5 1644,-1956.5 1644,-1956.5 1638,-1956.5 1632,-1950.5 1632,-1944.5 1632,-1944.5 1632,-1370.5 1632,-1370.5 1632,-1364.5 1638,-1358.5 1644,-1358.5"/>
<text text-anchor="middle" x="1738" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
<polyline fill="none" stroke="#000000" points="1844,-1358.5 1844,-1956.5 "/>
<text text-anchor="middle" x="1854.5" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1865,-1358.5 1865,-1956.5 "/>
<text text-anchor="middle" x="2054.5" y="-1941.3" font-family="Times,serif" font-size="14.00" fill="#000000">Cell_Barcode</text>
<polyline fill="none" stroke="#000000" points="1865,-1933.5 2244,-1933.5 "/>
<text text-anchor="middle" x="2054.5" y="-1918.3" font-family="Times,serif" font-size="14.00" fill="#000000">Cryopreserved_Cells_in_Sample</text>
<polyline fill="none" stroke="#000000" points="1865,-1910.5 2244,-1910.5 "/>
<text text-anchor="middle" x="2054.5" y="-1895.3" font-family="Times,serif" font-size="14.00" fill="#000000">Dissociation_Method</text>
<polyline fill="none" stroke="#000000" points="1865,-1887.5 2244,-1887.5 "/>
<text text-anchor="middle" x="2054.5" y="-1872.3" font-family="Times,serif" font-size="14.00" fill="#000000">End_Bias</text>
<polyline fill="none" stroke="#000000" points="1865,-1864.5 2244,-1864.5 "/>
<text text-anchor="middle" x="2054.5" y="-1849.3" font-family="Times,serif" font-size="14.00" fill="#000000">Input_Cells_and_Nuclei</text>
<polyline fill="none" stroke="#000000" points="1865,-1841.5 2244,-1841.5 "/>
<text text-anchor="middle" x="2054.5" y="-1826.3" font-family="Times,serif" font-size="14.00" fill="#000000">Library_Construction_Method</text>
<polyline fill="none" stroke="#000000" points="1865,-1818.5 2244,-1818.5 "/>
<text text-anchor="middle" x="2054.5" y="-1803.3" font-family="Times,serif" font-size="14.00" fill="#000000">Library_Preparation_Date</text>
<polyline fill="none" stroke="#000000" points="1865,-1795.5 2244,-1795.5 "/>
<text text-anchor="middle" x="2054.5" y="-1780.3" font-family="Times,serif" font-size="14.00" fill="#000000">Nucleic_Acid_Capture_Date</text>
<polyline fill="none" stroke="#000000" points="1865,-1772.5 2244,-1772.5 "/>
<text text-anchor="middle" x="2054.5" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">Paired_End</text>
<polyline fill="none" stroke="#000000" points="1865,-1749.5 2244,-1749.5 "/>
<text text-anchor="middle" x="2054.5" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">Protocols_Link</text>
<polyline fill="none" stroke="#000000" points="1865,-1726.5 2244,-1726.5 "/>
<text text-anchor="middle" x="2054.5" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">Read1</text>
<polyline fill="none" stroke="#000000" points="1865,-1703.5 2244,-1703.5 "/>
<text text-anchor="middle" x="2054.5" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">Read2</text>
<polyline fill="none" stroke="#000000" points="1865,-1680.5 2244,-1680.5 "/>
<text text-anchor="middle" x="2054.5" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Feature_barcoding</text>
<polyline fill="none" stroke="#000000" points="1865,-1657.5 2244,-1657.5 "/>
<text text-anchor="middle" x="2054.5" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Oligo_dT_Poly_dT</text>
<polyline fill="none" stroke="#000000" points="1865,-1634.5 2244,-1634.5 "/>
<text text-anchor="middle" x="2054.5" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Random</text>
<polyline fill="none" stroke="#000000" points="1865,-1611.5 2244,-1611.5 "/>
<text text-anchor="middle" x="2054.5" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">Sequencing_Library_Construction_Date</text>
<polyline fill="none" stroke="#000000" points="1865,-1588.5 2244,-1588.5 "/>
<text text-anchor="middle" x="2054.5" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">Single_Cell_Dissociation_Date</text>
<polyline fill="none" stroke="#000000" points="1865,-1565.5 2244,-1565.5 "/>
<text text-anchor="middle" x="2054.5" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">Single_Cell_Isolation_Method</text>
<polyline fill="none" stroke="#000000" points="1865,-1542.5 2244,-1542.5 "/>
<text text-anchor="middle" x="2054.5" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">Spike_In</text>
<polyline fill="none" stroke="#000000" points="1865,-1519.5 2244,-1519.5 "/>
<text text-anchor="middle" x="2054.5" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">Total_Number_of_Input_Cells</text>
<polyline fill="none" stroke="#000000" points="1865,-1496.5 2244,-1496.5 "/>
<text text-anchor="middle" x="2054.5" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">UMI</text>
<polyline fill="none" stroke="#000000" points="1865,-1473.5 2244,-1473.5 "/>
<text text-anchor="middle" x="2054.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="1865,-1450.5 2244,-1450.5 "/>
<text text-anchor="middle" x="2054.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">cDNA_Length</text>
<polyline fill="none" stroke="#000000" points="1865,-1427.5 2244,-1427.5 "/>
<text text-anchor="middle" x="2054.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">cDNA_Offset</text>
<polyline fill="none" stroke="#000000" points="1865,-1404.5 2244,-1404.5 "/>
<text text-anchor="middle" x="2054.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1865,-1381.5 2244,-1381.5 "/>
<text text-anchor="middle" x="2054.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 23 properties</text>
<polyline fill="none" stroke="#000000" points="2244,-1358.5 2244,-1956.5 "/>
<text text-anchor="middle" x="2254.5" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node7" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1261.5,-927C1261.5,-927 1575.5,-927 1575.5,-927 1581.5,-927 1587.5,-933 1587.5,-939 1587.5,-939 1587.5,-1076 1587.5,-1076 1587.5,-1082 1581.5,-1088 1575.5,-1088 1575.5,-1088 1261.5,-1088 1261.5,-1088 1255.5,-1088 1249.5,-1082 1249.5,-1076 1249.5,-1076 1249.5,-939 1249.5,-939 1249.5,-933 1255.5,-927 1261.5,-927"/>
<text text-anchor="middle" x="1283.5" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1317.5,-927 1317.5,-1088 "/>
<text text-anchor="middle" x="1328" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1338.5,-927 1338.5,-1088 "/>
<text text-anchor="middle" x="1452.5" y="-1072.8" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="1338.5,-1065 1566.5,-1065 "/>
<text text-anchor="middle" x="1452.5" y="-1049.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1338.5,-1042 1566.5,-1042 "/>
<text text-anchor="middle" x="1452.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1338.5,-1019 1566.5,-1019 "/>
<text text-anchor="middle" x="1452.5" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1338.5,-996 1566.5,-996 "/>
<text text-anchor="middle" x="1452.5" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1338.5,-973 1566.5,-973 "/>
<text text-anchor="middle" x="1452.5" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1338.5,-950 1566.5,-950 "/>
<text text-anchor="middle" x="1452.5" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="1566.5,-927 1566.5,-1088 "/>
<text text-anchor="middle" x="1577" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1638.7183,-1358.4248C1624.0511,-1341.3761 1609.8834,-1324.1774 1596.5,-1307 1545.034,-1240.9442 1497.1761,-1158.7437 1464.0751,-1097.1783"/>
<polygon fill="#000000" stroke="#000000" points="1467.1021,-1095.4166 1459.2998,-1088.249 1460.9294,-1098.7177 1467.1021,-1095.4166"/>
<text text-anchor="middle" x="1731" y="-1328.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge4" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1452.386,-926.6968C1482.7598,-861.6131 1532.387,-770.9095 1596.5,-708 1617.6692,-687.2282 1627.1325,-686.4291 1654.5,-675 2380.7651,-371.7012 3311.5618,-220.9866 3727.19,-165.0251"/>
<polygon fill="#000000" stroke="#000000" points="3727.7691,-168.4788 3737.2149,-163.6802 3726.8383,-161.541 3727.7691,-168.4788"/>
<text text-anchor="middle" x="2132" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1442.8341,-926.8689C1468.7437,-856.2295 1517.1486,-757.3617 1596.5,-708 1718.9362,-631.8368 2668.4127,-608.0308 3066.1433,-601.3547"/>
<polygon fill="#000000" stroke="#000000" points="3066.3626,-604.8516 3076.3031,-601.1859 3066.2463,-597.8526 3066.3626,-604.8516"/>
<text text-anchor="middle" x="1742" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge7" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M3338.5899,-541.4781C3389.6829,-511.5162 3450.8768,-475.6309 3496.6809,-448.7705"/>
<polygon fill="#000000" stroke="#000000" points="3498.4827,-451.7713 3505.3384,-443.6935 3494.9417,-445.733 3498.4827,-451.7713"/>
<text text-anchor="middle" x="3444" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge8" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3250.2029,-541.3745C3263.4281,-464.1757 3286.2949,-335.8856 3293.5,-328 3352.4226,-263.5122 3561.8382,-210.1043 3727.4422,-176.6046"/>
<polygon fill="#000000" stroke="#000000" points="3728.1708,-180.0282 3737.2851,-174.6264 3726.7915,-173.1655 3728.1708,-180.0282"/>
<text text-anchor="middle" x="3344" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_funding -->
<g id="node9" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M3755,-374.5C3755,-374.5 4134,-374.5 4134,-374.5 4140,-374.5 4146,-380.5 4146,-386.5 4146,-386.5 4146,-431.5 4146,-431.5 4146,-437.5 4140,-443.5 4134,-443.5 4134,-443.5 3755,-443.5 3755,-443.5 3749,-443.5 3743,-437.5 3743,-431.5 3743,-431.5 3743,-386.5 3743,-386.5 3743,-380.5 3749,-374.5 3755,-374.5"/>
<text text-anchor="middle" x="3802.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="3862,-374.5 3862,-443.5 "/>
<text text-anchor="middle" x="3872.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3883,-374.5 3883,-443.5 "/>
<text text-anchor="middle" x="4004" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="3883,-420.5 4125,-420.5 "/>
<text text-anchor="middle" x="4004" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="3883,-397.5 4125,-397.5 "/>
<text text-anchor="middle" x="4004" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="4125,-374.5 4125,-443.5 "/>
<text text-anchor="middle" x="4135.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge9" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3944.5,-374.4662C3944.5,-351.5553 3944.5,-319.7488 3944.5,-286.8978"/>
<polygon fill="#000000" stroke="#000000" points="3948.0001,-286.6778 3944.5,-276.6779 3941.0001,-286.6779 3948.0001,-286.6778"/>
<text text-anchor="middle" x="4006.5" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- study_personnel -->
<g id="node10" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M4176,-351.5C4176,-351.5 4483,-351.5 4483,-351.5 4489,-351.5 4495,-357.5 4495,-363.5 4495,-363.5 4495,-454.5 4495,-454.5 4495,-460.5 4489,-466.5 4483,-466.5 4483,-466.5 4176,-466.5 4176,-466.5 4170,-466.5 4164,-460.5 4164,-454.5 4164,-454.5 4164,-363.5 4164,-363.5 4164,-357.5 4170,-351.5 4176,-351.5"/>
<text text-anchor="middle" x="4231" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="4298,-351.5 4298,-466.5 "/>
<text text-anchor="middle" x="4308.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4319,-351.5 4319,-466.5 "/>
<text text-anchor="middle" x="4396.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="4319,-443.5 4474,-443.5 "/>
<text text-anchor="middle" x="4396.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="4319,-420.5 4474,-420.5 "/>
<text text-anchor="middle" x="4396.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="4319,-397.5 4474,-397.5 "/>
<text text-anchor="middle" x="4396.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="4319,-374.5 4474,-374.5 "/>
<text text-anchor="middle" x="4396.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="4474,-351.5 4474,-466.5 "/>
<text text-anchor="middle" x="4484.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge24" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M4247.3801,-351.3027C4218.3482,-330.905 4184.2572,-306.9528 4149.619,-282.6161"/>
<polygon fill="#000000" stroke="#000000" points="4151.4746,-279.6423 4141.2801,-276.7572 4147.4503,-285.3699 4151.4746,-279.6423"/>
<text text-anchor="middle" x="4253" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- sequencing_file -->
<g id="node11" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M2295,-1370C2295,-1370 2764,-1370 2764,-1370 2770,-1370 2776,-1376 2776,-1382 2776,-1382 2776,-1933 2776,-1933 2776,-1939 2770,-1945 2764,-1945 2764,-1945 2295,-1945 2295,-1945 2289,-1945 2283,-1939 2283,-1933 2283,-1933 2283,-1382 2283,-1382 2283,-1376 2289,-1370 2295,-1370"/>
<text text-anchor="middle" x="2347" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="2411,-1370 2411,-1945 "/>
<text text-anchor="middle" x="2421.5" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2432,-1370 2432,-1945 "/>
<text text-anchor="middle" x="2593.5" y="-1929.8" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="2432,-1922 2755,-1922 "/>
<text text-anchor="middle" x="2593.5" y="-1906.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2432,-1899 2755,-1899 "/>
<text text-anchor="middle" x="2593.5" y="-1883.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2432,-1876 2755,-1876 "/>
<text text-anchor="middle" x="2593.5" y="-1860.8" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="2432,-1853 2755,-1853 "/>
<text text-anchor="middle" x="2593.5" y="-1837.8" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="2432,-1830 2755,-1830 "/>
<text text-anchor="middle" x="2593.5" y="-1814.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2432,-1807 2755,-1807 "/>
<text text-anchor="middle" x="2593.5" y="-1791.8" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="2432,-1784 2755,-1784 "/>
<text text-anchor="middle" x="2593.5" y="-1768.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2432,-1761 2755,-1761 "/>
<text text-anchor="middle" x="2593.5" y="-1745.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2432,-1738 2755,-1738 "/>
<text text-anchor="middle" x="2593.5" y="-1722.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2432,-1715 2755,-1715 "/>
<text text-anchor="middle" x="2593.5" y="-1699.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2432,-1692 2755,-1692 "/>
<text text-anchor="middle" x="2593.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2432,-1669 2755,-1669 "/>
<text text-anchor="middle" x="2593.5" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2432,-1646 2755,-1646 "/>
<text text-anchor="middle" x="2593.5" y="-1630.8" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="2432,-1623 2755,-1623 "/>
<text text-anchor="middle" x="2593.5" y="-1607.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="2432,-1600 2755,-1600 "/>
<text text-anchor="middle" x="2593.5" y="-1584.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="2432,-1577 2755,-1577 "/>
<text text-anchor="middle" x="2593.5" y="-1561.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="2432,-1554 2755,-1554 "/>
<text text-anchor="middle" x="2593.5" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="2432,-1531 2755,-1531 "/>
<text text-anchor="middle" x="2593.5" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="2432,-1508 2755,-1508 "/>
<text text-anchor="middle" x="2593.5" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2432,-1485 2755,-1485 "/>
<text text-anchor="middle" x="2593.5" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="2432,-1462 2755,-1462 "/>
<text text-anchor="middle" x="2593.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="2432,-1439 2755,-1439 "/>
<text text-anchor="middle" x="2593.5" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="2432,-1416 2755,-1416 "/>
<text text-anchor="middle" x="2593.5" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="2432,-1393 2755,-1393 "/>
<text text-anchor="middle" x="2593.5" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="2755,-1370 2755,-1945 "/>
<text text-anchor="middle" x="2765.5" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2294.6371,-1369.7769C2287.7127,-1365.5778 2280.6656,-1361.6405 2273.5,-1358 2102.6165,-1271.1819 2034.639,-1339.2989 1843.5,-1325 1816.0595,-1322.9472 1619.9064,-1321.4685 1596.5,-1307 1520.58,-1260.0706 1473.0422,-1167.7353 1446.3911,-1097.9303"/>
<polygon fill="#000000" stroke="#000000" points="1449.5478,-1096.379 1442.7683,-1088.2372 1442.9908,-1098.8297 1449.5478,-1096.379"/>
<text text-anchor="middle" x="2292" y="-1328.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- synonym -->
<g id="node12" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M2806,-1634.5C2806,-1634.5 3107,-1634.5 3107,-1634.5 3113,-1634.5 3119,-1640.5 3119,-1646.5 3119,-1646.5 3119,-1668.5 3119,-1668.5 3119,-1674.5 3113,-1680.5 3107,-1680.5 3107,-1680.5 2806,-1680.5 2806,-1680.5 2800,-1680.5 2794,-1674.5 2794,-1668.5 2794,-1668.5 2794,-1646.5 2794,-1646.5 2794,-1640.5 2800,-1634.5 2806,-1634.5"/>
<text text-anchor="middle" x="2834" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="2874,-1634.5 2874,-1680.5 "/>
<text text-anchor="middle" x="2884.5" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2895,-1634.5 2895,-1680.5 "/>
<text text-anchor="middle" x="2996.5" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="2895,-1657.5 3098,-1657.5 "/>
<text text-anchor="middle" x="2996.5" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="3098,-1634.5 3098,-1680.5 "/>
<text text-anchor="middle" x="3108.5" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge17" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3119.3147,-1641.9551C3590.1174,-1595.4316 4927.9781,-1451.5447 5058.5,-1307 5147.8888,-1208.0075 5077.5,-1140.8787 5077.5,-1007.5 5077.5,-1007.5 5077.5,-1007.5 5077.5,-409 5077.5,-222.7298 4490.8123,-164.4683 4161.7927,-146.4405"/>
<polygon fill="#000000" stroke="#000000" points="4161.8247,-142.9373 4151.6506,-145.8931 4161.4474,-149.9271 4161.8247,-142.9373"/>
<text text-anchor="middle" x="5120" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2951.1113,-1634.3971C2936.1919,-1576.2261 2888.3979,-1423.6854 2784.5,-1358 2704.9926,-1307.7345 2456.4429,-1329.7733 2362.5,-1325 2319.9875,-1322.8399 1633.2483,-1328.4835 1596.5,-1307 1519.0734,-1261.7355 1471.6235,-1168.4307 1445.3999,-1097.9208"/>
<polygon fill="#000000" stroke="#000000" points="1448.5464,-1096.332 1441.8396,-1088.1302 1441.9679,-1098.7243 1448.5464,-1096.332"/>
<text text-anchor="middle" x="2778" y="-1328.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2949.9581,-1634.3792C2934.5683,-1578.6412 2896.4,-1432.2041 2883.5,-1307 2876.6788,-1240.7949 2843.9012,-761.4937 2883.5,-708 2906.7481,-676.5943 2987.3121,-650.5896 3066.0344,-631.8664"/>
<polygon fill="#000000" stroke="#000000" points="3067.1822,-635.1924 3076.1205,-629.5041 3065.5859,-628.3768 3067.1822,-635.1924"/>
<text text-anchor="middle" x="2926" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- therapeutic_procedure -->
<g id="node13" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M1617.5,-950C1617.5,-950 2009.5,-950 2009.5,-950 2015.5,-950 2021.5,-956 2021.5,-962 2021.5,-962 2021.5,-1053 2021.5,-1053 2021.5,-1059 2015.5,-1065 2009.5,-1065 2009.5,-1065 1617.5,-1065 1617.5,-1065 1611.5,-1065 1605.5,-1059 1605.5,-1053 1605.5,-1053 1605.5,-962 1605.5,-962 1605.5,-956 1611.5,-950 1617.5,-950"/>
<text text-anchor="middle" x="1696" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="1786.5,-950 1786.5,-1065 "/>
<text text-anchor="middle" x="1797" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1807.5,-950 1807.5,-1065 "/>
<text text-anchor="middle" x="1904" y="-1049.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment_start</text>
<polyline fill="none" stroke="#000000" points="1807.5,-1042 2000.5,-1042 "/>
<text text-anchor="middle" x="1904" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="1807.5,-1019 2000.5,-1019 "/>
<text text-anchor="middle" x="1904" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1807.5,-996 2000.5,-996 "/>
<text text-anchor="middle" x="1904" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="1807.5,-973 2000.5,-973 "/>
<text text-anchor="middle" x="1904" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="2000.5,-950 2000.5,-1065 "/>
<text text-anchor="middle" x="2011" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1837.6875,-949.7625C1870.3314,-879.7274 1935.5507,-764.0937 2030.5,-708 2117.5163,-656.5929 2752.5115,-621.0623 3066.1577,-606.4513"/>
<polygon fill="#000000" stroke="#000000" points="3066.4334,-609.9424 3076.2604,-605.9828 3066.109,-602.9499 3066.4334,-609.9424"/>
<text text-anchor="middle" x="2246.5" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- publication -->
<g id="node14" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M4739.5,-391C4739.5,-391 4949.5,-391 4949.5,-391 4955.5,-391 4961.5,-397 4961.5,-403 4961.5,-403 4961.5,-415 4961.5,-415 4961.5,-421 4955.5,-427 4949.5,-427 4949.5,-427 4739.5,-427 4739.5,-427 4733.5,-427 4727.5,-421 4727.5,-415 4727.5,-415 4727.5,-403 4727.5,-403 4727.5,-397 4733.5,-391 4739.5,-391"/>
<text text-anchor="middle" x="4776" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="4824.5,-391 4824.5,-427 "/>
<text text-anchor="middle" x="4835" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4845.5,-391 4845.5,-427 "/>
<text text-anchor="middle" x="4893" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="4940.5,-391 4940.5,-427 "/>
<text text-anchor="middle" x="4951" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge25" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M4829.2095,-390.7458C4806.6588,-365.1026 4761.894,-318.8831 4713.5,-295 4539.5301,-209.1434 4321.1748,-170.379 4161.6347,-152.882"/>
<polygon fill="#000000" stroke="#000000" points="4162.0094,-149.4022 4151.692,-151.8107 4161.2595,-156.3619 4162.0094,-149.4022"/>
<text text-anchor="middle" x="4788.5" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- clinical_measure_file -->
<g id="node15" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M4685.5,-881C4685.5,-881 5037.5,-881 5037.5,-881 5043.5,-881 5049.5,-887 5049.5,-893 5049.5,-893 5049.5,-1122 5049.5,-1122 5049.5,-1128 5043.5,-1134 5037.5,-1134 5037.5,-1134 4685.5,-1134 4685.5,-1134 4679.5,-1134 4673.5,-1128 4673.5,-1122 4673.5,-1122 4673.5,-893 4673.5,-893 4673.5,-887 4679.5,-881 4685.5,-881"/>
<text text-anchor="middle" x="4757" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="4840.5,-881 4840.5,-1134 "/>
<text text-anchor="middle" x="4851" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4861.5,-881 4861.5,-1134 "/>
<text text-anchor="middle" x="4945" y="-1118.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="4861.5,-1111 5028.5,-1111 "/>
<text text-anchor="middle" x="4945" y="-1095.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="4861.5,-1088 5028.5,-1088 "/>
<text text-anchor="middle" x="4945" y="-1072.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="4861.5,-1065 5028.5,-1065 "/>
<text text-anchor="middle" x="4945" y="-1049.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="4861.5,-1042 5028.5,-1042 "/>
<text text-anchor="middle" x="4945" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="4861.5,-1019 5028.5,-1019 "/>
<text text-anchor="middle" x="4945" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="4861.5,-996 5028.5,-996 "/>
<text text-anchor="middle" x="4945" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="4861.5,-973 5028.5,-973 "/>
<text text-anchor="middle" x="4945" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="4861.5,-950 5028.5,-950 "/>
<text text-anchor="middle" x="4945" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="4861.5,-927 5028.5,-927 "/>
<text text-anchor="middle" x="4945" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="4861.5,-904 5028.5,-904 "/>
<text text-anchor="middle" x="4945" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="5028.5,-881 5028.5,-1134 "/>
<text text-anchor="middle" x="5039" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge19" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M4826.6703,-880.7798C4778.576,-728.6943 4677.5505,-475.7433 4504.5,-328 4407.9832,-245.598 4274.0621,-198.5882 4161.3845,-172.0051"/>
<polygon fill="#000000" stroke="#000000" points="4162.1202,-168.5829 4151.5879,-169.7324 4160.5383,-175.4018 4162.1202,-168.5829"/>
<text text-anchor="middle" x="4748.5" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M4810.839,-880.8192C4778.7113,-817.7909 4730.596,-746.9255 4664.5,-708 4618.7968,-681.0843 4479.3397,-694.6048 4426.5,-690 4358.8726,-684.1066 4342.1336,-680.8218 4274.5,-675 3972.558,-649.0091 3620.5245,-624.3321 3414.8936,-610.483"/>
<polygon fill="#000000" stroke="#000000" points="3415.1218,-606.9905 3404.9094,-609.8113 3414.6519,-613.9748 3415.1218,-606.9905"/>
<text text-anchor="middle" x="4556" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- follow_up -->
<g id="node16" class="node">
<title>follow_up</title>
<path fill="none" stroke="#000000" d="M2463,-904C2463,-904 2826,-904 2826,-904 2832,-904 2838,-910 2838,-916 2838,-916 2838,-1099 2838,-1099 2838,-1105 2832,-1111 2826,-1111 2826,-1111 2463,-1111 2463,-1111 2457,-1111 2451,-1105 2451,-1099 2451,-1099 2451,-916 2451,-916 2451,-910 2457,-904 2463,-904"/>
<text text-anchor="middle" x="2493.5" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
<polyline fill="none" stroke="#000000" points="2536,-904 2536,-1111 "/>
<text text-anchor="middle" x="2546.5" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2557,-904 2557,-1111 "/>
<text text-anchor="middle" x="2687" y="-1095.8" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event</text>
<polyline fill="none" stroke="#000000" points="2557,-1088 2817,-1088 "/>
<text text-anchor="middle" x="2687" y="-1072.8" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity</text>
<polyline fill="none" stroke="#000000" points="2557,-1065 2817,-1065 "/>
<text text-anchor="middle" x="2687" y="-1049.8" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity_method_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2557,-1042 2817,-1042 "/>
<text text-anchor="middle" x="2687" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_follow_up</text>
<polyline fill="none" stroke="#000000" points="2557,-1019 2817,-1019 "/>
<text text-anchor="middle" x="2687" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_response</text>
<polyline fill="none" stroke="#000000" points="2557,-996 2817,-996 "/>
<text text-anchor="middle" x="2687" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_category</text>
<polyline fill="none" stroke="#000000" points="2557,-973 2817,-973 "/>
<text text-anchor="middle" x="2687" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_id</text>
<polyline fill="none" stroke="#000000" points="2557,-950 2817,-950 "/>
<text text-anchor="middle" x="2687" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_other</text>
<polyline fill="none" stroke="#000000" points="2557,-927 2817,-927 "/>
<text text-anchor="middle" x="2687" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">risk_factor</text>
<polyline fill="none" stroke="#000000" points="2817,-904 2817,-1111 "/>
<text text-anchor="middle" x="2827.5" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2656.3496,-903.7481C2670.5873,-828.7005 2701.8671,-731.0068 2770.5,-675 2815.336,-638.4123 2951.7362,-619.112 3066.1214,-609.1338"/>
<polygon fill="#000000" stroke="#000000" points="3066.7487,-612.5931 3076.415,-608.2556 3066.1536,-605.6185 3066.7487,-612.5931"/>
<text text-anchor="middle" x="2815.5" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- sample_diagnosis -->
<g id="node17" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M12,-1496.5C12,-1496.5 445,-1496.5 445,-1496.5 451,-1496.5 457,-1502.5 457,-1508.5 457,-1508.5 457,-1806.5 457,-1806.5 457,-1812.5 451,-1818.5 445,-1818.5 445,-1818.5 12,-1818.5 12,-1818.5 6,-1818.5 0,-1812.5 0,-1806.5 0,-1806.5 0,-1508.5 0,-1508.5 0,-1502.5 6,-1496.5 12,-1496.5"/>
<text text-anchor="middle" x="71.5" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="143,-1496.5 143,-1818.5 "/>
<text text-anchor="middle" x="153.5" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="164,-1496.5 164,-1818.5 "/>
<text text-anchor="middle" x="300" y="-1803.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="164,-1795.5 436,-1795.5 "/>
<text text-anchor="middle" x="300" y="-1780.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="164,-1772.5 436,-1772.5 "/>
<text text-anchor="middle" x="300" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="164,-1749.5 436,-1749.5 "/>
<text text-anchor="middle" x="300" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="164,-1726.5 436,-1726.5 "/>
<text text-anchor="middle" x="300" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="164,-1703.5 436,-1703.5 "/>
<text text-anchor="middle" x="300" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="164,-1680.5 436,-1680.5 "/>
<text text-anchor="middle" x="300" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="164,-1657.5 436,-1657.5 "/>
<text text-anchor="middle" x="300" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="164,-1634.5 436,-1634.5 "/>
<text text-anchor="middle" x="300" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="164,-1611.5 436,-1611.5 "/>
<text text-anchor="middle" x="300" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="164,-1588.5 436,-1588.5 "/>
<text text-anchor="middle" x="300" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="164,-1565.5 436,-1565.5 "/>
<text text-anchor="middle" x="300" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="164,-1542.5 436,-1542.5 "/>
<text text-anchor="middle" x="300" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="164,-1519.5 436,-1519.5 "/>
<text text-anchor="middle" x="300" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="436,-1496.5 436,-1818.5 "/>
<text text-anchor="middle" x="446.5" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M330.3949,-1496.1356C367.9742,-1446.5271 414.0835,-1395.245 465.5,-1358 703.9396,-1185.2793 1036.8857,-1088.7426 1239.5394,-1042.4995"/>
<polygon fill="#000000" stroke="#000000" points="1240.4107,-1045.8908 1249.3903,-1040.2678 1238.8641,-1039.0638 1240.4107,-1045.8908"/>
<text text-anchor="middle" x="584.5" y="-1328.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
<!-- pdx -->
<g id="node18" class="node">
<title>pdx</title>
<path fill="none" stroke="#000000" d="M487,-1554C487,-1554 816,-1554 816,-1554 822,-1554 828,-1560 828,-1566 828,-1566 828,-1749 828,-1749 828,-1755 822,-1761 816,-1761 816,-1761 487,-1761 487,-1761 481,-1761 475,-1755 475,-1749 475,-1749 475,-1566 475,-1566 475,-1560 481,-1554 487,-1554"/>
<text text-anchor="middle" x="496.5" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
<polyline fill="none" stroke="#000000" points="518,-1554 518,-1761 "/>
<text text-anchor="middle" x="528.5" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="539,-1554 539,-1761 "/>
<text text-anchor="middle" x="673" y="-1745.8" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_site</text>
<polyline fill="none" stroke="#000000" points="539,-1738 807,-1738 "/>
<text text-anchor="middle" x="673" y="-1722.8" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_type</text>
<polyline fill="none" stroke="#000000" points="539,-1715 807,-1715 "/>
<text text-anchor="middle" x="673" y="-1699.8" font-family="Times,serif" font-size="14.00" fill="#000000">model_id</text>
<polyline fill="none" stroke="#000000" points="539,-1692 807,-1692 "/>
<text text-anchor="middle" x="673" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">mouse_strain</text>
<polyline fill="none" stroke="#000000" points="539,-1669 807,-1669 "/>
<text text-anchor="middle" x="673" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000">strain_immune_system_humanized</text>
<polyline fill="none" stroke="#000000" points="539,-1646 807,-1646 "/>
<text text-anchor="middle" x="673" y="-1630.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_characterization_method</text>
<polyline fill="none" stroke="#000000" points="539,-1623 807,-1623 "/>
<text text-anchor="middle" x="673" y="-1607.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_not_mus_or_ebv_origin</text>
<polyline fill="none" stroke="#000000" points="539,-1600 807,-1600 "/>
<text text-anchor="middle" x="673" y="-1584.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_preparation</text>
<polyline fill="none" stroke="#000000" points="539,-1577 807,-1577 "/>
<text text-anchor="middle" x="673" y="-1561.8" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_humanization</text>
<polyline fill="none" stroke="#000000" points="807,-1554 807,-1761 "/>
<text text-anchor="middle" x="817.5" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M700.23,-1553.658C732.8889,-1491.7299 780.3286,-1414.4373 837.5,-1358 954.5589,-1242.4441 1116.7679,-1148.6715 1240.0497,-1087.2971"/>
<polygon fill="#000000" stroke="#000000" points="1241.8226,-1090.3248 1249.2307,-1082.7504 1238.716,-1084.0519 1241.8226,-1090.3248"/>
<text text-anchor="middle" x="888.5" y="-1328.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- exposure -->
<g id="node19" class="node">
<title>exposure</title>
<path fill="none" stroke="#000000" d="M2990,-766C2990,-766 3401,-766 3401,-766 3407,-766 3413,-772 3413,-778 3413,-778 3413,-1237 3413,-1237 3413,-1243 3407,-1249 3401,-1249 3401,-1249 2990,-1249 2990,-1249 2984,-1249 2978,-1243 2978,-1237 2978,-1237 2978,-778 2978,-778 2978,-772 2984,-766 2990,-766"/>
<text text-anchor="middle" x="3019" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
<polyline fill="none" stroke="#000000" points="3060,-766 3060,-1249 "/>
<text text-anchor="middle" x="3070.5" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3081,-766 3081,-1249 "/>
<text text-anchor="middle" x="3236.5" y="-1233.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_days_per_week</text>
<polyline fill="none" stroke="#000000" points="3081,-1226 3392,-1226 "/>
<text text-anchor="middle" x="3236.5" y="-1210.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_drinks_per_day</text>
<polyline fill="none" stroke="#000000" points="3081,-1203 3392,-1203 "/>
<text text-anchor="middle" x="3236.5" y="-1187.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_history</text>
<polyline fill="none" stroke="#000000" points="3081,-1180 3392,-1180 "/>
<text text-anchor="middle" x="3236.5" y="-1164.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_intensity</text>
<polyline fill="none" stroke="#000000" points="3081,-1157 3392,-1157 "/>
<text text-anchor="middle" x="3236.5" y="-1141.8" font-family="Times,serif" font-size="14.00" fill="#000000">asbestos_exposure</text>
<polyline fill="none" stroke="#000000" points="3081,-1134 3392,-1134 "/>
<text text-anchor="middle" x="3236.5" y="-1118.8" font-family="Times,serif" font-size="14.00" fill="#000000">cigarettes_per_day</text>
<polyline fill="none" stroke="#000000" points="3081,-1111 3392,-1111 "/>
<text text-anchor="middle" x="3236.5" y="-1095.8" font-family="Times,serif" font-size="14.00" fill="#000000">coal_dust_exposure</text>
<polyline fill="none" stroke="#000000" points="3081,-1088 3392,-1088 "/>
<text text-anchor="middle" x="3236.5" y="-1072.8" font-family="Times,serif" font-size="14.00" fill="#000000">environmental_tobacco_smoke_exposure</text>
<polyline fill="none" stroke="#000000" points="3081,-1065 3392,-1065 "/>
<text text-anchor="middle" x="3236.5" y="-1049.8" font-family="Times,serif" font-size="14.00" fill="#000000">exposure_id</text>
<polyline fill="none" stroke="#000000" points="3081,-1042 3392,-1042 "/>
<text text-anchor="middle" x="3236.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">pack_years_smoked</text>
<polyline fill="none" stroke="#000000" points="3081,-1019 3392,-1019 "/>
<text text-anchor="middle" x="3236.5" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">radon_exposure</text>
<polyline fill="none" stroke="#000000" points="3081,-996 3392,-996 "/>
<text text-anchor="middle" x="3236.5" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">respirable_crystalline_silica_exposure</text>
<polyline fill="none" stroke="#000000" points="3081,-973 3392,-973 "/>
<text text-anchor="middle" x="3236.5" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">smoking_frequency</text>
<polyline fill="none" stroke="#000000" points="3081,-950 3392,-950 "/>
<text text-anchor="middle" x="3236.5" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">start_days_from_index</text>
<polyline fill="none" stroke="#000000" points="3081,-927 3392,-927 "/>
<text text-anchor="middle" x="3236.5" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">time_between_waking_and_first_smoke</text>
<polyline fill="none" stroke="#000000" points="3081,-904 3392,-904 "/>
<text text-anchor="middle" x="3236.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_onset_year</text>
<polyline fill="none" stroke="#000000" points="3081,-881 3392,-881 "/>
<text text-anchor="middle" x="3236.5" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_quit_year</text>
<polyline fill="none" stroke="#000000" points="3081,-858 3392,-858 "/>
<text text-anchor="middle" x="3236.5" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_status</text>
<polyline fill="none" stroke="#000000" points="3081,-835 3392,-835 "/>
<text text-anchor="middle" x="3236.5" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_smoke_exposure</text>
<polyline fill="none" stroke="#000000" points="3081,-812 3392,-812 "/>
<text text-anchor="middle" x="3236.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_tobacco_used</text>
<polyline fill="none" stroke="#000000" points="3081,-789 3392,-789 "/>
<text text-anchor="middle" x="3236.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">years_smoked</text>
<polyline fill="none" stroke="#000000" points="3392,-766 3392,-1249 "/>
<text text-anchor="middle" x="3402.5" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3222.1319,-765.7418C3226.1207,-729.5325 3229.93,-694.9519 3233.0351,-666.7651"/>
<polygon fill="#000000" stroke="#000000" points="3236.5301,-667.0017 3234.1462,-656.6785 3229.5722,-666.2351 3236.5301,-667.0017"/>
<text text-anchor="middle" x="3276" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- imaging_file -->
<g id="node20" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M858.5,-1496.5C858.5,-1496.5 1192.5,-1496.5 1192.5,-1496.5 1198.5,-1496.5 1204.5,-1502.5 1204.5,-1508.5 1204.5,-1508.5 1204.5,-1806.5 1204.5,-1806.5 1204.5,-1812.5 1198.5,-1818.5 1192.5,-1818.5 1192.5,-1818.5 858.5,-1818.5 858.5,-1818.5 852.5,-1818.5 846.5,-1812.5 846.5,-1806.5 846.5,-1806.5 846.5,-1508.5 846.5,-1508.5 846.5,-1502.5 852.5,-1496.5 858.5,-1496.5"/>
<text text-anchor="middle" x="898.5" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="950.5,-1496.5 950.5,-1818.5 "/>
<text text-anchor="middle" x="961" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="971.5,-1496.5 971.5,-1818.5 "/>
<text text-anchor="middle" x="1077.5" y="-1803.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="971.5,-1795.5 1183.5,-1795.5 "/>
<text text-anchor="middle" x="1077.5" y="-1780.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="971.5,-1772.5 1183.5,-1772.5 "/>
<text text-anchor="middle" x="1077.5" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="971.5,-1749.5 1183.5,-1749.5 "/>
<text text-anchor="middle" x="1077.5" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="971.5,-1726.5 1183.5,-1726.5 "/>
<text text-anchor="middle" x="1077.5" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="971.5,-1703.5 1183.5,-1703.5 "/>
<text text-anchor="middle" x="1077.5" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="971.5,-1680.5 1183.5,-1680.5 "/>
<text text-anchor="middle" x="1077.5" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="971.5,-1657.5 1183.5,-1657.5 "/>
<text text-anchor="middle" x="1077.5" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="971.5,-1634.5 1183.5,-1634.5 "/>
<text text-anchor="middle" x="1077.5" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="971.5,-1611.5 1183.5,-1611.5 "/>
<text text-anchor="middle" x="1077.5" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="971.5,-1588.5 1183.5,-1588.5 "/>
<text text-anchor="middle" x="1077.5" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="971.5,-1565.5 1183.5,-1565.5 "/>
<text text-anchor="middle" x="1077.5" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="971.5,-1542.5 1183.5,-1542.5 "/>
<text text-anchor="middle" x="1077.5" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="971.5,-1519.5 1183.5,-1519.5 "/>
<text text-anchor="middle" x="1077.5" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="1183.5,-1496.5 1183.5,-1818.5 "/>
<text text-anchor="middle" x="1194" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge23" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1122.8985,-1496.4084C1199.1013,-1370.3732 1302.239,-1199.7892 1364.3732,-1097.0227"/>
<polygon fill="#000000" stroke="#000000" points="1367.5209,-1098.5811 1369.6998,-1088.2127 1361.5307,-1094.9593 1367.5209,-1098.5811"/>
<text text-anchor="middle" x="1277" y="-1328.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- methylation_array_file -->
<g id="node21" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M1235,-1542.5C1235,-1542.5 1602,-1542.5 1602,-1542.5 1608,-1542.5 1614,-1548.5 1614,-1554.5 1614,-1554.5 1614,-1760.5 1614,-1760.5 1614,-1766.5 1608,-1772.5 1602,-1772.5 1602,-1772.5 1235,-1772.5 1235,-1772.5 1229,-1772.5 1223,-1766.5 1223,-1760.5 1223,-1760.5 1223,-1554.5 1223,-1554.5 1223,-1548.5 1229,-1542.5 1235,-1542.5"/>
<text text-anchor="middle" x="1312" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="1401,-1542.5 1401,-1772.5 "/>
<text text-anchor="middle" x="1411.5" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1422,-1542.5 1422,-1772.5 "/>
<text text-anchor="middle" x="1507.5" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1422,-1749.5 1593,-1749.5 "/>
<text text-anchor="middle" x="1507.5" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1422,-1726.5 1593,-1726.5 "/>
<text text-anchor="middle" x="1507.5" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1422,-1703.5 1593,-1703.5 "/>
<text text-anchor="middle" x="1507.5" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1422,-1680.5 1593,-1680.5 "/>
<text text-anchor="middle" x="1507.5" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1422,-1657.5 1593,-1657.5 "/>
<text text-anchor="middle" x="1507.5" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1422,-1634.5 1593,-1634.5 "/>
<text text-anchor="middle" x="1507.5" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1422,-1611.5 1593,-1611.5 "/>
<text text-anchor="middle" x="1507.5" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1422,-1588.5 1593,-1588.5 "/>
<text text-anchor="middle" x="1507.5" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="1422,-1565.5 1593,-1565.5 "/>
<text text-anchor="middle" x="1507.5" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="1593,-1542.5 1593,-1772.5 "/>
<text text-anchor="middle" x="1603.5" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1418.5,-1542.4159C1418.5,-1415.7007 1418.5,-1214.5724 1418.5,-1098.4196"/>
<polygon fill="#000000" stroke="#000000" points="1422.0001,-1098.1392 1418.5,-1088.1393 1415.0001,-1098.1393 1422.0001,-1098.1392"/>
<text text-anchor="middle" x="1510" y="-1328.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- molecular_test -->
<g id="node22" class="node">
<title>molecular_test</title>
<path fill="none" stroke="#000000" d="M3443.5,-708.5C3443.5,-708.5 3831.5,-708.5 3831.5,-708.5 3837.5,-708.5 3843.5,-714.5 3843.5,-720.5 3843.5,-720.5 3843.5,-1294.5 3843.5,-1294.5 3843.5,-1300.5 3837.5,-1306.5 3831.5,-1306.5 3831.5,-1306.5 3443.5,-1306.5 3443.5,-1306.5 3437.5,-1306.5 3431.5,-1300.5 3431.5,-1294.5 3431.5,-1294.5 3431.5,-720.5 3431.5,-720.5 3431.5,-714.5 3437.5,-708.5 3443.5,-708.5"/>
<text text-anchor="middle" x="3493" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
<polyline fill="none" stroke="#000000" points="3554.5,-708.5 3554.5,-1306.5 "/>
<text text-anchor="middle" x="3565" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3575.5,-708.5 3575.5,-1306.5 "/>
<text text-anchor="middle" x="3699" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">aa_change</text>
<polyline fill="none" stroke="#000000" points="3575.5,-1283.5 3822.5,-1283.5 "/>
<text text-anchor="middle" x="3699" y="-1268.3" font-family="Times,serif" font-size="14.00" fill="#000000">antigen</text>
<polyline fill="none" stroke="#000000" points="3575.5,-1260.5 3822.5,-1260.5 "/>
<text text-anchor="middle" x="3699" y="-1245.3" font-family="Times,serif" font-size="14.00" fill="#000000">biospecimen_type</text>
<polyline fill="none" stroke="#000000" points="3575.5,-1237.5 3822.5,-1237.5 "/>
<text text-anchor="middle" x="3699" y="-1222.3" font-family="Times,serif" font-size="14.00" fill="#000000">blood_test_normal_range_lower</text>
<polyline fill="none" stroke="#000000" points="3575.5,-1214.5 3822.5,-1214.5 "/>
<text text-anchor="middle" x="3699" y="-1199.3" font-family="Times,serif" font-size="14.00" fill="#000000">blood_test_normal_range_upper</text>
<polyline fill="none" stroke="#000000" points="3575.5,-1191.5 3822.5,-1191.5 "/>
<text text-anchor="middle" x="3699" y="-1176.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_count</text>
<polyline fill="none" stroke="#000000" points="3575.5,-1168.5 3822.5,-1168.5 "/>
<text text-anchor="middle" x="3699" y="-1153.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome</text>
<polyline fill="none" stroke="#000000" points="3575.5,-1145.5 3822.5,-1145.5 "/>
<text text-anchor="middle" x="3699" y="-1130.3" font-family="Times,serif" font-size="14.00" fill="#000000">copy_number</text>
<polyline fill="none" stroke="#000000" points="3575.5,-1122.5 3822.5,-1122.5 "/>
<text text-anchor="middle" x="3699" y="-1107.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytoband</text>
<polyline fill="none" stroke="#000000" points="3575.5,-1099.5 3822.5,-1099.5 "/>
<text text-anchor="middle" x="3699" y="-1084.3" font-family="Times,serif" font-size="14.00" fill="#000000">exon</text>
<polyline fill="none" stroke="#000000" points="3575.5,-1076.5 3822.5,-1076.5 "/>
<text text-anchor="middle" x="3699" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">gene_symbol</text>
<polyline fill="none" stroke="#000000" points="3575.5,-1053.5 3822.5,-1053.5 "/>
<text text-anchor="middle" x="3699" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">histone_family</text>
<polyline fill="none" stroke="#000000" points="3575.5,-1030.5 3822.5,-1030.5 "/>
<text text-anchor="middle" x="3699" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">histone_variant</text>
<polyline fill="none" stroke="#000000" points="3575.5,-1007.5 3822.5,-1007.5 "/>
<text text-anchor="middle" x="3699" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">intron</text>
<polyline fill="none" stroke="#000000" points="3575.5,-984.5 3822.5,-984.5 "/>
<text text-anchor="middle" x="3699" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
<polyline fill="none" stroke="#000000" points="3575.5,-961.5 3822.5,-961.5 "/>
<text text-anchor="middle" x="3699" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">loci_abnormal_count</text>
<polyline fill="none" stroke="#000000" points="3575.5,-938.5 3822.5,-938.5 "/>
<text text-anchor="middle" x="3699" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">loci_count</text>
<polyline fill="none" stroke="#000000" points="3575.5,-915.5 3822.5,-915.5 "/>
<text text-anchor="middle" x="3699" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">locus</text>
<polyline fill="none" stroke="#000000" points="3575.5,-892.5 3822.5,-892.5 "/>
<text text-anchor="middle" x="3699" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">mismatch_repair_mutation</text>
<polyline fill="none" stroke="#000000" points="3575.5,-869.5 3822.5,-869.5 "/>
<text text-anchor="middle" x="3699" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_analysis_method</text>
<polyline fill="none" stroke="#000000" points="3575.5,-846.5 3822.5,-846.5 "/>
<text text-anchor="middle" x="3699" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_consequence</text>
<polyline fill="none" stroke="#000000" points="3575.5,-823.5 3822.5,-823.5 "/>
<text text-anchor="middle" x="3699" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test_id</text>
<polyline fill="none" stroke="#000000" points="3575.5,-800.5 3822.5,-800.5 "/>
<text text-anchor="middle" x="3699" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathogenicity</text>
<polyline fill="none" stroke="#000000" points="3575.5,-777.5 3822.5,-777.5 "/>
<text text-anchor="middle" x="3699" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">ploidy</text>
<polyline fill="none" stroke="#000000" points="3575.5,-754.5 3822.5,-754.5 "/>
<text text-anchor="middle" x="3699" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">second_exon</text>
<polyline fill="none" stroke="#000000" points="3575.5,-731.5 3822.5,-731.5 "/>
<text text-anchor="middle" x="3699" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 11 properties</text>
<polyline fill="none" stroke="#000000" points="3822.5,-708.5 3822.5,-1306.5 "/>
<text text-anchor="middle" x="3833" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3431.3467,-717.2853C3428.0845,-714.1361 3424.8018,-711.0392 3421.5,-708 3403.2731,-691.2226 3382.0662,-675.7113 3360.7203,-661.9659"/>
<polygon fill="#000000" stroke="#000000" points="3362.5409,-658.976 3352.219,-656.5865 3358.7978,-664.8913 3362.5409,-658.976"/>
<text text-anchor="middle" x="3464.5" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- medical_history -->
<g id="node23" class="node">
<title>medical_history</title>
<path fill="none" stroke="#000000" d="M3873.5,-973C3873.5,-973 4227.5,-973 4227.5,-973 4233.5,-973 4239.5,-979 4239.5,-985 4239.5,-985 4239.5,-1030 4239.5,-1030 4239.5,-1036 4233.5,-1042 4227.5,-1042 4227.5,-1042 3873.5,-1042 3873.5,-1042 3867.5,-1042 3861.5,-1036 3861.5,-1030 3861.5,-1030 3861.5,-985 3861.5,-985 3861.5,-979 3867.5,-973 3873.5,-973"/>
<text text-anchor="middle" x="3927" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
<polyline fill="none" stroke="#000000" points="3992.5,-973 3992.5,-1042 "/>
<text text-anchor="middle" x="4003" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4013.5,-973 4013.5,-1042 "/>
<text text-anchor="middle" x="4116" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_category</text>
<polyline fill="none" stroke="#000000" points="4013.5,-1019 4218.5,-1019 "/>
<text text-anchor="middle" x="4116" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_condition</text>
<polyline fill="none" stroke="#000000" points="4013.5,-996 4218.5,-996 "/>
<text text-anchor="middle" x="4116" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_id</text>
<polyline fill="none" stroke="#000000" points="4218.5,-973 4218.5,-1042 "/>
<text text-anchor="middle" x="4229" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M4038.2188,-972.7787C4013.7202,-908.9816 3952.3799,-773.6462 3852.5,-708 3782.0663,-661.7073 3569.7524,-631.3272 3414.9118,-614.6753"/>
<polygon fill="#000000" stroke="#000000" points="3415.1124,-611.1769 3404.798,-613.5982 3414.3711,-618.1376 3415.1124,-611.1769"/>
<text text-anchor="middle" x="3875.5" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
</g>
</svg>
</div>
