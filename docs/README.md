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
<svg width="5766pt" height="1821pt"
 viewBox="0.00 0.00 5766.00 1821.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1817)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1817 5762,-1817 5762,4 -4,4"/>
<!-- radiology_file -->
<g id="node1" class="node">
<title>radiology_file</title>
<path fill="none" stroke="#000000" d="M3529,-714C3529,-714 3876,-714 3876,-714 3882,-714 3888,-720 3888,-726 3888,-726 3888,-1001 3888,-1001 3888,-1007 3882,-1013 3876,-1013 3876,-1013 3529,-1013 3529,-1013 3523,-1013 3517,-1007 3517,-1001 3517,-1001 3517,-726 3517,-726 3517,-720 3523,-714 3529,-714"/>
<text text-anchor="middle" x="3573.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
<polyline fill="none" stroke="#000000" points="3630,-714 3630,-1013 "/>
<text text-anchor="middle" x="3640.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3651,-714 3651,-1013 "/>
<text text-anchor="middle" x="3759" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="3651,-990 3867,-990 "/>
<text text-anchor="middle" x="3759" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="3651,-967 3867,-967 "/>
<text text-anchor="middle" x="3759" y="-951.8" font-family="Times,serif" font-size="14.00" fill="#000000">deidentification_method</text>
<polyline fill="none" stroke="#000000" points="3651,-944 3867,-944 "/>
<text text-anchor="middle" x="3759" y="-928.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="3651,-921 3867,-921 "/>
<text text-anchor="middle" x="3759" y="-905.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="3651,-898 3867,-898 "/>
<text text-anchor="middle" x="3759" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="3651,-875 3867,-875 "/>
<text text-anchor="middle" x="3759" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="3651,-852 3867,-852 "/>
<text text-anchor="middle" x="3759" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="3651,-829 3867,-829 "/>
<text text-anchor="middle" x="3759" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="3651,-806 3867,-806 "/>
<text text-anchor="middle" x="3759" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="3651,-783 3867,-783 "/>
<text text-anchor="middle" x="3759" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="3651,-760 3867,-760 "/>
<text text-anchor="middle" x="3759" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_imaging</text>
<polyline fill="none" stroke="#000000" points="3651,-737 3867,-737 "/>
<text text-anchor="middle" x="3759" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file_id</text>
<polyline fill="none" stroke="#000000" points="3867,-714 3867,-1013 "/>
<text text-anchor="middle" x="3877.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node17" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M3293.5,-374.5C3293.5,-374.5 3597.5,-374.5 3597.5,-374.5 3603.5,-374.5 3609.5,-380.5 3609.5,-386.5 3609.5,-386.5 3609.5,-477.5 3609.5,-477.5 3609.5,-483.5 3603.5,-489.5 3597.5,-489.5 3597.5,-489.5 3293.5,-489.5 3293.5,-489.5 3287.5,-489.5 3281.5,-483.5 3281.5,-477.5 3281.5,-477.5 3281.5,-386.5 3281.5,-386.5 3281.5,-380.5 3287.5,-374.5 3293.5,-374.5"/>
<text text-anchor="middle" x="3329.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="3377.5,-374.5 3377.5,-489.5 "/>
<text text-anchor="middle" x="3388" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3398.5,-374.5 3398.5,-489.5 "/>
<text text-anchor="middle" x="3493.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="3398.5,-466.5 3588.5,-466.5 "/>
<text text-anchor="middle" x="3493.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="3398.5,-443.5 3588.5,-443.5 "/>
<text text-anchor="middle" x="3493.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="3398.5,-420.5 3588.5,-420.5 "/>
<text text-anchor="middle" x="3493.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="3398.5,-397.5 3588.5,-397.5 "/>
<text text-anchor="middle" x="3493.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="3588.5,-374.5 3588.5,-489.5 "/>
<text text-anchor="middle" x="3599" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3615.0646,-713.7503C3581.3798,-656.4344 3542.3883,-590.542 3506.5,-531 3500.127,-520.4266 3493.3179,-509.2555 3486.6448,-498.3756"/>
<polygon fill="#000000" stroke="#000000" points="3489.5499,-496.418 3481.3331,-489.7296 3483.5855,-500.0823 3489.5499,-496.418"/>
<text text-anchor="middle" x="3570.5" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- synonym -->
<g id="node2" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M4648,-1490.5C4648,-1490.5 4949,-1490.5 4949,-1490.5 4955,-1490.5 4961,-1496.5 4961,-1502.5 4961,-1502.5 4961,-1524.5 4961,-1524.5 4961,-1530.5 4955,-1536.5 4949,-1536.5 4949,-1536.5 4648,-1536.5 4648,-1536.5 4642,-1536.5 4636,-1530.5 4636,-1524.5 4636,-1524.5 4636,-1502.5 4636,-1502.5 4636,-1496.5 4642,-1490.5 4648,-1490.5"/>
<text text-anchor="middle" x="4676" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="4716,-1490.5 4716,-1536.5 "/>
<text text-anchor="middle" x="4726.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4737,-1490.5 4737,-1536.5 "/>
<text text-anchor="middle" x="4838.5" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="4737,-1513.5 4940,-1513.5 "/>
<text text-anchor="middle" x="4838.5" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="4940,-1490.5 4940,-1536.5 "/>
<text text-anchor="middle" x="4950.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node3" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M4605.5,-.5C4605.5,-.5 4995.5,-.5 4995.5,-.5 5001.5,-.5 5007.5,-6.5 5007.5,-12.5 5007.5,-12.5 5007.5,-287.5 5007.5,-287.5 5007.5,-293.5 5001.5,-299.5 4995.5,-299.5 4995.5,-299.5 4605.5,-299.5 4605.5,-299.5 4599.5,-299.5 4593.5,-293.5 4593.5,-287.5 4593.5,-287.5 4593.5,-12.5 4593.5,-12.5 4593.5,-6.5 4599.5,-.5 4605.5,-.5"/>
<text text-anchor="middle" x="4621.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="4649.5,-.5 4649.5,-299.5 "/>
<text text-anchor="middle" x="4660" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4670.5,-.5 4670.5,-299.5 "/>
<text text-anchor="middle" x="4828.5" y="-284.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="4670.5,-276.5 4986.5,-276.5 "/>
<text text-anchor="middle" x="4828.5" y="-261.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="4670.5,-253.5 4986.5,-253.5 "/>
<text text-anchor="middle" x="4828.5" y="-238.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_number</text>
<polyline fill="none" stroke="#000000" points="4670.5,-230.5 4986.5,-230.5 "/>
<text text-anchor="middle" x="4828.5" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="4670.5,-207.5 4986.5,-207.5 "/>
<text text-anchor="middle" x="4828.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="4670.5,-184.5 4986.5,-184.5 "/>
<text text-anchor="middle" x="4828.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="4670.5,-161.5 4986.5,-161.5 "/>
<text text-anchor="middle" x="4828.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="4670.5,-138.5 4986.5,-138.5 "/>
<text text-anchor="middle" x="4828.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="4670.5,-115.5 4986.5,-115.5 "/>
<text text-anchor="middle" x="4828.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="4670.5,-92.5 4986.5,-92.5 "/>
<text text-anchor="middle" x="4828.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="4670.5,-69.5 4986.5,-69.5 "/>
<text text-anchor="middle" x="4828.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="4670.5,-46.5 4986.5,-46.5 "/>
<text text-anchor="middle" x="4828.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="4670.5,-23.5 4986.5,-23.5 "/>
<text text-anchor="middle" x="4828.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="4986.5,-.5 4986.5,-299.5 "/>
<text text-anchor="middle" x="4997" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge19" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M4866.9661,-1490.4556C4982.8772,-1447.2667 5214.3289,-1341.9859 5308.5,-1163 5350.5141,-1083.1461 5349.0035,-424.384 5296.5,-351 5231.7526,-260.5028 5119.0333,-210.6884 5017.3968,-183.2982"/>
<polygon fill="#000000" stroke="#000000" points="5018.1593,-179.8798 5007.5976,-180.717 5016.3762,-186.6489 5018.1593,-179.8798"/>
<text text-anchor="middle" x="5372" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M4798.6913,-1490.4992C4799.7656,-1348.785 4803.9014,-599.105 4771.5,-564 4725.5615,-514.2284 4536.0796,-535.5337 4468.5,-531 4311.9121,-520.495 3917.9516,-534.5624 3762.5,-513 3715.6188,-506.4972 3665.6731,-495.6465 3619.6243,-483.9671"/>
<polygon fill="#000000" stroke="#000000" points="3620.4156,-480.5568 3609.8597,-481.4635 3618.6771,-487.3375 3620.4156,-480.5568"/>
<text text-anchor="middle" x="4841" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- sample -->
<g id="node20" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1045.5,-668C1045.5,-668 1403.5,-668 1403.5,-668 1409.5,-668 1415.5,-674 1415.5,-680 1415.5,-680 1415.5,-1047 1415.5,-1047 1415.5,-1053 1409.5,-1059 1403.5,-1059 1403.5,-1059 1045.5,-1059 1045.5,-1059 1039.5,-1059 1033.5,-1053 1033.5,-1047 1033.5,-1047 1033.5,-680 1033.5,-680 1033.5,-674 1039.5,-668 1045.5,-668"/>
<text text-anchor="middle" x="1067.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1101.5,-668 1101.5,-1059 "/>
<text text-anchor="middle" x="1112" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1122.5,-668 1122.5,-1059 "/>
<text text-anchor="middle" x="1258.5" y="-1043.8" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="1122.5,-1036 1394.5,-1036 "/>
<text text-anchor="middle" x="1258.5" y="-1020.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1122.5,-1013 1394.5,-1013 "/>
<text text-anchor="middle" x="1258.5" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1122.5,-990 1394.5,-990 "/>
<text text-anchor="middle" x="1258.5" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="1122.5,-967 1394.5,-967 "/>
<text text-anchor="middle" x="1258.5" y="-951.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="1122.5,-944 1394.5,-944 "/>
<text text-anchor="middle" x="1258.5" y="-928.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="1122.5,-921 1394.5,-921 "/>
<text text-anchor="middle" x="1258.5" y="-905.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1122.5,-898 1394.5,-898 "/>
<text text-anchor="middle" x="1258.5" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1122.5,-875 1394.5,-875 "/>
<text text-anchor="middle" x="1258.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1122.5,-852 1394.5,-852 "/>
<text text-anchor="middle" x="1258.5" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1122.5,-829 1394.5,-829 "/>
<text text-anchor="middle" x="1258.5" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1122.5,-806 1394.5,-806 "/>
<text text-anchor="middle" x="1258.5" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="1122.5,-783 1394.5,-783 "/>
<text text-anchor="middle" x="1258.5" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="1122.5,-760 1394.5,-760 "/>
<text text-anchor="middle" x="1258.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1122.5,-737 1394.5,-737 "/>
<text text-anchor="middle" x="1258.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1122.5,-714 1394.5,-714 "/>
<text text-anchor="middle" x="1258.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1122.5,-691 1394.5,-691 "/>
<text text-anchor="middle" x="1258.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1394.5,-668 1394.5,-1059 "/>
<text text-anchor="middle" x="1405" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M4653.4394,-1490.4803C4234.6924,-1425.355 2987.2215,-1240.6667 1943.5,-1181 1914.6964,-1179.3534 1449.7025,-1177.0426 1424.5,-1163 1383.7072,-1140.2707 1349.6934,-1105.3113 1321.9753,-1067.1927"/>
<polygon fill="#000000" stroke="#000000" points="1324.8052,-1065.1328 1316.1559,-1059.0139 1319.1016,-1069.1911 1324.8052,-1065.1328"/>
<text text-anchor="middle" x="2141" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node4" class="node">
<title>single_cell_sequencing_file</title>
<path fill="none" stroke="#000000" d="M12,-1214.5C12,-1214.5 621,-1214.5 621,-1214.5 627,-1214.5 633,-1220.5 633,-1226.5 633,-1226.5 633,-1800.5 633,-1800.5 633,-1806.5 627,-1812.5 621,-1812.5 621,-1812.5 12,-1812.5 12,-1812.5 6,-1812.5 0,-1806.5 0,-1800.5 0,-1800.5 0,-1226.5 0,-1226.5 0,-1220.5 6,-1214.5 12,-1214.5"/>
<text text-anchor="middle" x="106" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
<polyline fill="none" stroke="#000000" points="212,-1214.5 212,-1812.5 "/>
<text text-anchor="middle" x="222.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="233,-1214.5 233,-1812.5 "/>
<text text-anchor="middle" x="422.5" y="-1797.3" font-family="Times,serif" font-size="14.00" fill="#000000">Cell_Barcode</text>
<polyline fill="none" stroke="#000000" points="233,-1789.5 612,-1789.5 "/>
<text text-anchor="middle" x="422.5" y="-1774.3" font-family="Times,serif" font-size="14.00" fill="#000000">Cryopreserved_Cells_in_Sample</text>
<polyline fill="none" stroke="#000000" points="233,-1766.5 612,-1766.5 "/>
<text text-anchor="middle" x="422.5" y="-1751.3" font-family="Times,serif" font-size="14.00" fill="#000000">Dissociation_Method</text>
<polyline fill="none" stroke="#000000" points="233,-1743.5 612,-1743.5 "/>
<text text-anchor="middle" x="422.5" y="-1728.3" font-family="Times,serif" font-size="14.00" fill="#000000">End_Bias</text>
<polyline fill="none" stroke="#000000" points="233,-1720.5 612,-1720.5 "/>
<text text-anchor="middle" x="422.5" y="-1705.3" font-family="Times,serif" font-size="14.00" fill="#000000">Input_Cells_and_Nuclei</text>
<polyline fill="none" stroke="#000000" points="233,-1697.5 612,-1697.5 "/>
<text text-anchor="middle" x="422.5" y="-1682.3" font-family="Times,serif" font-size="14.00" fill="#000000">Library_Construction_Method</text>
<polyline fill="none" stroke="#000000" points="233,-1674.5 612,-1674.5 "/>
<text text-anchor="middle" x="422.5" y="-1659.3" font-family="Times,serif" font-size="14.00" fill="#000000">Library_Preparation_Date</text>
<polyline fill="none" stroke="#000000" points="233,-1651.5 612,-1651.5 "/>
<text text-anchor="middle" x="422.5" y="-1636.3" font-family="Times,serif" font-size="14.00" fill="#000000">Nucleic_Acid_Capture_Date</text>
<polyline fill="none" stroke="#000000" points="233,-1628.5 612,-1628.5 "/>
<text text-anchor="middle" x="422.5" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">Paired_End</text>
<polyline fill="none" stroke="#000000" points="233,-1605.5 612,-1605.5 "/>
<text text-anchor="middle" x="422.5" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">Protocols_Link</text>
<polyline fill="none" stroke="#000000" points="233,-1582.5 612,-1582.5 "/>
<text text-anchor="middle" x="422.5" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">Read1</text>
<polyline fill="none" stroke="#000000" points="233,-1559.5 612,-1559.5 "/>
<text text-anchor="middle" x="422.5" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">Read2</text>
<polyline fill="none" stroke="#000000" points="233,-1536.5 612,-1536.5 "/>
<text text-anchor="middle" x="422.5" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Feature_barcoding</text>
<polyline fill="none" stroke="#000000" points="233,-1513.5 612,-1513.5 "/>
<text text-anchor="middle" x="422.5" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Oligo_dT_Poly_dT</text>
<polyline fill="none" stroke="#000000" points="233,-1490.5 612,-1490.5 "/>
<text text-anchor="middle" x="422.5" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Random</text>
<polyline fill="none" stroke="#000000" points="233,-1467.5 612,-1467.5 "/>
<text text-anchor="middle" x="422.5" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">Sequencing_Library_Construction_Date</text>
<polyline fill="none" stroke="#000000" points="233,-1444.5 612,-1444.5 "/>
<text text-anchor="middle" x="422.5" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">Single_Cell_Dissociation_Date</text>
<polyline fill="none" stroke="#000000" points="233,-1421.5 612,-1421.5 "/>
<text text-anchor="middle" x="422.5" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">Single_Cell_Isolation_Method</text>
<polyline fill="none" stroke="#000000" points="233,-1398.5 612,-1398.5 "/>
<text text-anchor="middle" x="422.5" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">Spike_In</text>
<polyline fill="none" stroke="#000000" points="233,-1375.5 612,-1375.5 "/>
<text text-anchor="middle" x="422.5" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">Total_Number_of_Input_Cells</text>
<polyline fill="none" stroke="#000000" points="233,-1352.5 612,-1352.5 "/>
<text text-anchor="middle" x="422.5" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">UMI</text>
<polyline fill="none" stroke="#000000" points="233,-1329.5 612,-1329.5 "/>
<text text-anchor="middle" x="422.5" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="233,-1306.5 612,-1306.5 "/>
<text text-anchor="middle" x="422.5" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">cDNA_Length</text>
<polyline fill="none" stroke="#000000" points="233,-1283.5 612,-1283.5 "/>
<text text-anchor="middle" x="422.5" y="-1268.3" font-family="Times,serif" font-size="14.00" fill="#000000">cDNA_Offset</text>
<polyline fill="none" stroke="#000000" points="233,-1260.5 612,-1260.5 "/>
<text text-anchor="middle" x="422.5" y="-1245.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="233,-1237.5 612,-1237.5 "/>
<text text-anchor="middle" x="422.5" y="-1222.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 24 properties</text>
<polyline fill="none" stroke="#000000" points="612,-1214.5 612,-1812.5 "/>
<text text-anchor="middle" x="622.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M633.2595,-1220.9794C636.343,-1218.6299 639.4236,-1216.3028 642.5,-1214 763.4033,-1123.5004 908.9556,-1035.8494 1024.2558,-970.8362"/>
<polygon fill="#000000" stroke="#000000" points="1026.2056,-973.7553 1033.2047,-965.8015 1022.7732,-967.6545 1026.2056,-973.7553"/>
<text text-anchor="middle" x="796" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- study_admin -->
<g id="node5" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M3783.5,-351.5C3783.5,-351.5 4109.5,-351.5 4109.5,-351.5 4115.5,-351.5 4121.5,-357.5 4121.5,-363.5 4121.5,-363.5 4121.5,-500.5 4121.5,-500.5 4121.5,-506.5 4115.5,-512.5 4109.5,-512.5 4109.5,-512.5 3783.5,-512.5 3783.5,-512.5 3777.5,-512.5 3771.5,-506.5 3771.5,-500.5 3771.5,-500.5 3771.5,-363.5 3771.5,-363.5 3771.5,-357.5 3777.5,-351.5 3783.5,-351.5"/>
<text text-anchor="middle" x="3825.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="3879.5,-351.5 3879.5,-512.5 "/>
<text text-anchor="middle" x="3890" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3900.5,-351.5 3900.5,-512.5 "/>
<text text-anchor="middle" x="4000.5" y="-497.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="3900.5,-489.5 4100.5,-489.5 "/>
<text text-anchor="middle" x="4000.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="3900.5,-466.5 4100.5,-466.5 "/>
<text text-anchor="middle" x="4000.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="3900.5,-443.5 4100.5,-443.5 "/>
<text text-anchor="middle" x="4000.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="3900.5,-420.5 4100.5,-420.5 "/>
<text text-anchor="middle" x="4000.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="3900.5,-397.5 4100.5,-397.5 "/>
<text text-anchor="middle" x="4000.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="3900.5,-374.5 4100.5,-374.5 "/>
<text text-anchor="middle" x="4000.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="4100.5,-351.5 4100.5,-512.5 "/>
<text text-anchor="middle" x="4111" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge2" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M4121.5589,-354.7124C4124.8931,-353.4486 4128.2091,-352.2098 4131.5,-351 4280.3044,-296.2972 4451.5888,-245.0481 4583.59,-207.9904"/>
<polygon fill="#000000" stroke="#000000" points="4584.7401,-211.303 4593.4252,-205.2351 4582.8518,-204.5625 4584.7401,-211.303"/>
<text text-anchor="middle" x="4277" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- study_arm -->
<g id="node6" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M4152,-386C4152,-386 4449,-386 4449,-386 4455,-386 4461,-392 4461,-398 4461,-398 4461,-466 4461,-466 4461,-472 4455,-478 4449,-478 4449,-478 4152,-478 4152,-478 4146,-478 4140,-472 4140,-466 4140,-466 4140,-398 4140,-398 4140,-392 4146,-386 4152,-386"/>
<text text-anchor="middle" x="4186" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="4232,-386 4232,-478 "/>
<text text-anchor="middle" x="4242.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4253,-386 4253,-478 "/>
<text text-anchor="middle" x="4346.5" y="-462.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="4253,-455 4440,-455 "/>
<text text-anchor="middle" x="4346.5" y="-439.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="4253,-432 4440,-432 "/>
<text text-anchor="middle" x="4346.5" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="4253,-409 4440,-409 "/>
<text text-anchor="middle" x="4346.5" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm_id</text>
<polyline fill="none" stroke="#000000" points="4440,-386 4440,-478 "/>
<text text-anchor="middle" x="4450.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge5" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M4382.2255,-385.9068C4437.3683,-354.8063 4512.898,-312.2075 4584.6115,-271.7611"/>
<polygon fill="#000000" stroke="#000000" points="4586.3457,-274.8014 4593.3365,-266.8402 4582.9069,-268.7042 4586.3457,-274.8014"/>
<text text-anchor="middle" x="4539" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- pathology_file -->
<g id="node7" class="node">
<title>pathology_file</title>
<path fill="none" stroke="#000000" d="M663.5,-1364C663.5,-1364 1017.5,-1364 1017.5,-1364 1023.5,-1364 1029.5,-1370 1029.5,-1376 1029.5,-1376 1029.5,-1651 1029.5,-1651 1029.5,-1657 1023.5,-1663 1017.5,-1663 1017.5,-1663 663.5,-1663 663.5,-1663 657.5,-1663 651.5,-1657 651.5,-1651 651.5,-1651 651.5,-1376 651.5,-1376 651.5,-1370 657.5,-1364 663.5,-1364"/>
<text text-anchor="middle" x="710" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
<polyline fill="none" stroke="#000000" points="768.5,-1364 768.5,-1663 "/>
<text text-anchor="middle" x="779" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="789.5,-1364 789.5,-1663 "/>
<text text-anchor="middle" x="899" y="-1647.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="789.5,-1640 1008.5,-1640 "/>
<text text-anchor="middle" x="899" y="-1624.8" font-family="Times,serif" font-size="14.00" fill="#000000">deidentification_method</text>
<polyline fill="none" stroke="#000000" points="789.5,-1617 1008.5,-1617 "/>
<text text-anchor="middle" x="899" y="-1601.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="789.5,-1594 1008.5,-1594 "/>
<text text-anchor="middle" x="899" y="-1578.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="789.5,-1571 1008.5,-1571 "/>
<text text-anchor="middle" x="899" y="-1555.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="789.5,-1548 1008.5,-1548 "/>
<text text-anchor="middle" x="899" y="-1532.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="789.5,-1525 1008.5,-1525 "/>
<text text-anchor="middle" x="899" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="789.5,-1502 1008.5,-1502 "/>
<text text-anchor="middle" x="899" y="-1486.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="789.5,-1479 1008.5,-1479 "/>
<text text-anchor="middle" x="899" y="-1463.8" font-family="Times,serif" font-size="14.00" fill="#000000">fixation_embedding_method</text>
<polyline fill="none" stroke="#000000" points="789.5,-1456 1008.5,-1456 "/>
<text text-anchor="middle" x="899" y="-1440.8" font-family="Times,serif" font-size="14.00" fill="#000000">magnification</text>
<polyline fill="none" stroke="#000000" points="789.5,-1433 1008.5,-1433 "/>
<text text-anchor="middle" x="899" y="-1417.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="789.5,-1410 1008.5,-1410 "/>
<text text-anchor="middle" x="899" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file_id</text>
<polyline fill="none" stroke="#000000" points="789.5,-1387 1008.5,-1387 "/>
<text text-anchor="middle" x="899" y="-1371.8" font-family="Times,serif" font-size="14.00" fill="#000000">staining_method</text>
<polyline fill="none" stroke="#000000" points="1008.5,-1364 1008.5,-1663 "/>
<text text-anchor="middle" x="1019" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M928.8383,-1363.969C980.754,-1276.0909 1047.1109,-1163.7681 1103.8014,-1067.8075"/>
<polygon fill="#000000" stroke="#000000" points="1106.8342,-1069.5548 1108.9073,-1059.1648 1100.8074,-1065.9943 1106.8342,-1069.5548"/>
<text text-anchor="middle" x="1093.5" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- study_personnel -->
<g id="node8" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M4491,-374.5C4491,-374.5 4798,-374.5 4798,-374.5 4804,-374.5 4810,-380.5 4810,-386.5 4810,-386.5 4810,-477.5 4810,-477.5 4810,-483.5 4804,-489.5 4798,-489.5 4798,-489.5 4491,-489.5 4491,-489.5 4485,-489.5 4479,-483.5 4479,-477.5 4479,-477.5 4479,-386.5 4479,-386.5 4479,-380.5 4485,-374.5 4491,-374.5"/>
<text text-anchor="middle" x="4546" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="4613,-374.5 4613,-489.5 "/>
<text text-anchor="middle" x="4623.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4634,-374.5 4634,-489.5 "/>
<text text-anchor="middle" x="4711.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="4634,-466.5 4789,-466.5 "/>
<text text-anchor="middle" x="4711.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="4634,-443.5 4789,-443.5 "/>
<text text-anchor="middle" x="4711.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="4634,-420.5 4789,-420.5 "/>
<text text-anchor="middle" x="4711.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="4634,-397.5 4789,-397.5 "/>
<text text-anchor="middle" x="4711.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="4789,-374.5 4789,-489.5 "/>
<text text-anchor="middle" x="4799.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge11" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M4676.4454,-374.2526C4687.1951,-354.8203 4699.7631,-332.1012 4712.6965,-308.7217"/>
<polygon fill="#000000" stroke="#000000" points="4715.8902,-310.179 4717.6682,-299.7344 4709.7649,-306.7905 4715.8902,-310.179"/>
<text text-anchor="middle" x="4773" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- pdx -->
<g id="node9" class="node">
<title>pdx</title>
<path fill="none" stroke="#000000" d="M1060,-1398.5C1060,-1398.5 1389,-1398.5 1389,-1398.5 1395,-1398.5 1401,-1404.5 1401,-1410.5 1401,-1410.5 1401,-1616.5 1401,-1616.5 1401,-1622.5 1395,-1628.5 1389,-1628.5 1389,-1628.5 1060,-1628.5 1060,-1628.5 1054,-1628.5 1048,-1622.5 1048,-1616.5 1048,-1616.5 1048,-1410.5 1048,-1410.5 1048,-1404.5 1054,-1398.5 1060,-1398.5"/>
<text text-anchor="middle" x="1069.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
<polyline fill="none" stroke="#000000" points="1091,-1398.5 1091,-1628.5 "/>
<text text-anchor="middle" x="1101.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1112,-1398.5 1112,-1628.5 "/>
<text text-anchor="middle" x="1246" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_site</text>
<polyline fill="none" stroke="#000000" points="1112,-1605.5 1380,-1605.5 "/>
<text text-anchor="middle" x="1246" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_type</text>
<polyline fill="none" stroke="#000000" points="1112,-1582.5 1380,-1582.5 "/>
<text text-anchor="middle" x="1246" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_id</text>
<polyline fill="none" stroke="#000000" points="1112,-1559.5 1380,-1559.5 "/>
<text text-anchor="middle" x="1246" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">mouse_strain</text>
<polyline fill="none" stroke="#000000" points="1112,-1536.5 1380,-1536.5 "/>
<text text-anchor="middle" x="1246" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx_id</text>
<polyline fill="none" stroke="#000000" points="1112,-1513.5 1380,-1513.5 "/>
<text text-anchor="middle" x="1246" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">strain_immune_system_humanized</text>
<polyline fill="none" stroke="#000000" points="1112,-1490.5 1380,-1490.5 "/>
<text text-anchor="middle" x="1246" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_characterization_method</text>
<polyline fill="none" stroke="#000000" points="1112,-1467.5 1380,-1467.5 "/>
<text text-anchor="middle" x="1246" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_not_mus_or_ebv_origin</text>
<polyline fill="none" stroke="#000000" points="1112,-1444.5 1380,-1444.5 "/>
<text text-anchor="middle" x="1246" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_preparation</text>
<polyline fill="none" stroke="#000000" points="1112,-1421.5 1380,-1421.5 "/>
<text text-anchor="middle" x="1246" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_humanization</text>
<polyline fill="none" stroke="#000000" points="1380,-1398.5 1380,-1628.5 "/>
<text text-anchor="middle" x="1390.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1224.5,-1398.4159C1224.5,-1307.3647 1224.5,-1177.8929 1224.5,-1069.1334"/>
<polygon fill="#000000" stroke="#000000" points="1228.0001,-1069.0098 1224.5,-1059.0098 1221.0001,-1069.0098 1228.0001,-1069.0098"/>
<text text-anchor="middle" x="1248.5" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- exposure -->
<g id="node10" class="node">
<title>exposure</title>
<path fill="none" stroke="#000000" d="M1446,-622C1446,-622 1857,-622 1857,-622 1863,-622 1869,-628 1869,-634 1869,-634 1869,-1093 1869,-1093 1869,-1099 1863,-1105 1857,-1105 1857,-1105 1446,-1105 1446,-1105 1440,-1105 1434,-1099 1434,-1093 1434,-1093 1434,-634 1434,-634 1434,-628 1440,-622 1446,-622"/>
<text text-anchor="middle" x="1475" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
<polyline fill="none" stroke="#000000" points="1516,-622 1516,-1105 "/>
<text text-anchor="middle" x="1526.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1537,-622 1537,-1105 "/>
<text text-anchor="middle" x="1692.5" y="-1089.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_days_per_week</text>
<polyline fill="none" stroke="#000000" points="1537,-1082 1848,-1082 "/>
<text text-anchor="middle" x="1692.5" y="-1066.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_drinks_per_day</text>
<polyline fill="none" stroke="#000000" points="1537,-1059 1848,-1059 "/>
<text text-anchor="middle" x="1692.5" y="-1043.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_history</text>
<polyline fill="none" stroke="#000000" points="1537,-1036 1848,-1036 "/>
<text text-anchor="middle" x="1692.5" y="-1020.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_intensity</text>
<polyline fill="none" stroke="#000000" points="1537,-1013 1848,-1013 "/>
<text text-anchor="middle" x="1692.5" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000">asbestos_exposure</text>
<polyline fill="none" stroke="#000000" points="1537,-990 1848,-990 "/>
<text text-anchor="middle" x="1692.5" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">cigarettes_per_day</text>
<polyline fill="none" stroke="#000000" points="1537,-967 1848,-967 "/>
<text text-anchor="middle" x="1692.5" y="-951.8" font-family="Times,serif" font-size="14.00" fill="#000000">coal_dust_exposure</text>
<polyline fill="none" stroke="#000000" points="1537,-944 1848,-944 "/>
<text text-anchor="middle" x="1692.5" y="-928.8" font-family="Times,serif" font-size="14.00" fill="#000000">environmental_tobacco_smoke_exposure</text>
<polyline fill="none" stroke="#000000" points="1537,-921 1848,-921 "/>
<text text-anchor="middle" x="1692.5" y="-905.8" font-family="Times,serif" font-size="14.00" fill="#000000">exposure_id</text>
<polyline fill="none" stroke="#000000" points="1537,-898 1848,-898 "/>
<text text-anchor="middle" x="1692.5" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">pack_years_smoked</text>
<polyline fill="none" stroke="#000000" points="1537,-875 1848,-875 "/>
<text text-anchor="middle" x="1692.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">radon_exposure</text>
<polyline fill="none" stroke="#000000" points="1537,-852 1848,-852 "/>
<text text-anchor="middle" x="1692.5" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">respirable_crystalline_silica_exposure</text>
<polyline fill="none" stroke="#000000" points="1537,-829 1848,-829 "/>
<text text-anchor="middle" x="1692.5" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">smoking_frequency</text>
<polyline fill="none" stroke="#000000" points="1537,-806 1848,-806 "/>
<text text-anchor="middle" x="1692.5" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">start_days_from_index</text>
<polyline fill="none" stroke="#000000" points="1537,-783 1848,-783 "/>
<text text-anchor="middle" x="1692.5" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">time_between_waking_and_first_smoke</text>
<polyline fill="none" stroke="#000000" points="1537,-760 1848,-760 "/>
<text text-anchor="middle" x="1692.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_onset_year</text>
<polyline fill="none" stroke="#000000" points="1537,-737 1848,-737 "/>
<text text-anchor="middle" x="1692.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_quit_year</text>
<polyline fill="none" stroke="#000000" points="1537,-714 1848,-714 "/>
<text text-anchor="middle" x="1692.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_status</text>
<polyline fill="none" stroke="#000000" points="1537,-691 1848,-691 "/>
<text text-anchor="middle" x="1692.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_smoke_exposure</text>
<polyline fill="none" stroke="#000000" points="1537,-668 1848,-668 "/>
<text text-anchor="middle" x="1692.5" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_tobacco_used</text>
<polyline fill="none" stroke="#000000" points="1537,-645 1848,-645 "/>
<text text-anchor="middle" x="1692.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">years_smoked</text>
<polyline fill="none" stroke="#000000" points="1848,-622 1848,-1105 "/>
<text text-anchor="middle" x="1858.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1803.3069,-621.7116C1826.0113,-599.2039 1851.1103,-579.1844 1878.5,-564 1997.9842,-497.7599 2888.5997,-454.4066 3271.4279,-438.646"/>
<polygon fill="#000000" stroke="#000000" points="3271.6427,-442.1402 3281.4909,-438.2332 3271.3558,-435.1461 3271.6427,-442.1402"/>
<text text-anchor="middle" x="2027" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- methylation_array_file -->
<g id="node11" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M1431,-1387C1431,-1387 1826,-1387 1826,-1387 1832,-1387 1838,-1393 1838,-1399 1838,-1399 1838,-1628 1838,-1628 1838,-1634 1832,-1640 1826,-1640 1826,-1640 1431,-1640 1431,-1640 1425,-1640 1419,-1634 1419,-1628 1419,-1628 1419,-1399 1419,-1399 1419,-1393 1425,-1387 1431,-1387"/>
<text text-anchor="middle" x="1508" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="1597,-1387 1597,-1640 "/>
<text text-anchor="middle" x="1607.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1618,-1387 1618,-1640 "/>
<text text-anchor="middle" x="1717.5" y="-1624.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1618,-1617 1817,-1617 "/>
<text text-anchor="middle" x="1717.5" y="-1601.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1618,-1594 1817,-1594 "/>
<text text-anchor="middle" x="1717.5" y="-1578.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1618,-1571 1817,-1571 "/>
<text text-anchor="middle" x="1717.5" y="-1555.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1618,-1548 1817,-1548 "/>
<text text-anchor="middle" x="1717.5" y="-1532.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1618,-1525 1817,-1525 "/>
<text text-anchor="middle" x="1717.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1618,-1502 1817,-1502 "/>
<text text-anchor="middle" x="1717.5" y="-1486.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1618,-1479 1817,-1479 "/>
<text text-anchor="middle" x="1717.5" y="-1463.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1618,-1456 1817,-1456 "/>
<text text-anchor="middle" x="1717.5" y="-1440.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file_id</text>
<polyline fill="none" stroke="#000000" points="1618,-1433 1817,-1433 "/>
<text text-anchor="middle" x="1717.5" y="-1417.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="1618,-1410 1817,-1410 "/>
<text text-anchor="middle" x="1717.5" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="1817,-1387 1817,-1640 "/>
<text text-anchor="middle" x="1827.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1549.6457,-1386.6304C1493.3608,-1296.0731 1416.4489,-1172.3287 1351.559,-1067.9266"/>
<polygon fill="#000000" stroke="#000000" points="1354.3671,-1065.8142 1346.1156,-1059.1687 1348.4219,-1069.5095 1354.3671,-1065.8142"/>
<text text-anchor="middle" x="1518" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- medical_history -->
<g id="node12" class="node">
<title>medical_history</title>
<path fill="none" stroke="#000000" d="M1899.5,-829C1899.5,-829 2253.5,-829 2253.5,-829 2259.5,-829 2265.5,-835 2265.5,-841 2265.5,-841 2265.5,-886 2265.5,-886 2265.5,-892 2259.5,-898 2253.5,-898 2253.5,-898 1899.5,-898 1899.5,-898 1893.5,-898 1887.5,-892 1887.5,-886 1887.5,-886 1887.5,-841 1887.5,-841 1887.5,-835 1893.5,-829 1899.5,-829"/>
<text text-anchor="middle" x="1953" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
<polyline fill="none" stroke="#000000" points="2018.5,-829 2018.5,-898 "/>
<text text-anchor="middle" x="2029" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2039.5,-829 2039.5,-898 "/>
<text text-anchor="middle" x="2142" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_category</text>
<polyline fill="none" stroke="#000000" points="2039.5,-875 2244.5,-875 "/>
<text text-anchor="middle" x="2142" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_condition</text>
<polyline fill="none" stroke="#000000" points="2039.5,-852 2244.5,-852 "/>
<text text-anchor="middle" x="2142" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_id</text>
<polyline fill="none" stroke="#000000" points="2244.5,-829 2244.5,-898 "/>
<text text-anchor="middle" x="2255" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2088.1157,-828.9255C2111.7799,-764.433 2172.1721,-626.6608 2274.5,-564 2357.6031,-513.1115 2965.606,-464.8563 3271.1844,-443.5011"/>
<polygon fill="#000000" stroke="#000000" points="3271.7459,-446.9705 3281.4785,-442.7839 3271.2594,-439.9875 3271.7459,-446.9705"/>
<text text-anchor="middle" x="2461.5" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- family_relationship -->
<g id="node13" class="node">
<title>family_relationship</title>
<path fill="none" stroke="#000000" d="M2296,-817.5C2296,-817.5 2665,-817.5 2665,-817.5 2671,-817.5 2677,-823.5 2677,-829.5 2677,-829.5 2677,-897.5 2677,-897.5 2677,-903.5 2671,-909.5 2665,-909.5 2665,-909.5 2296,-909.5 2296,-909.5 2290,-909.5 2284,-903.5 2284,-897.5 2284,-897.5 2284,-829.5 2284,-829.5 2284,-823.5 2290,-817.5 2296,-817.5"/>
<text text-anchor="middle" x="2361" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
<polyline fill="none" stroke="#000000" points="2438,-817.5 2438,-909.5 "/>
<text text-anchor="middle" x="2448.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2459,-817.5 2459,-909.5 "/>
<text text-anchor="middle" x="2557.5" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_id</text>
<polyline fill="none" stroke="#000000" points="2459,-886.5 2656,-886.5 "/>
<text text-anchor="middle" x="2557.5" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship_id</text>
<polyline fill="none" stroke="#000000" points="2459,-863.5 2656,-863.5 "/>
<text text-anchor="middle" x="2557.5" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">related_to_participant_id</text>
<polyline fill="none" stroke="#000000" points="2459,-840.5 2656,-840.5 "/>
<text text-anchor="middle" x="2557.5" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">relationship</text>
<polyline fill="none" stroke="#000000" points="2656,-817.5 2656,-909.5 "/>
<text text-anchor="middle" x="2666.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2498.4248,-817.3213C2527.1827,-749.8491 2590.3476,-625.6637 2686.5,-564 2781.0465,-503.3662 3078.2321,-465.4758 3271.4688,-446.5848"/>
<polygon fill="#000000" stroke="#000000" points="3271.8369,-450.0657 3281.4524,-445.6167 3271.1612,-443.0983 3271.8369,-450.0657"/>
<text text-anchor="middle" x="2837" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- diagnosis -->
<g id="node14" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M2707.5,-668C2707.5,-668 3081.5,-668 3081.5,-668 3087.5,-668 3093.5,-674 3093.5,-680 3093.5,-680 3093.5,-1047 3093.5,-1047 3093.5,-1053 3087.5,-1059 3081.5,-1059 3081.5,-1059 2707.5,-1059 2707.5,-1059 2701.5,-1059 2695.5,-1053 2695.5,-1047 2695.5,-1047 2695.5,-680 2695.5,-680 2695.5,-674 2701.5,-668 2707.5,-668"/>
<text text-anchor="middle" x="2737.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="2779.5,-668 2779.5,-1059 "/>
<text text-anchor="middle" x="2790" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2800.5,-668 2800.5,-1059 "/>
<text text-anchor="middle" x="2936.5" y="-1043.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2800.5,-1036 3072.5,-1036 "/>
<text text-anchor="middle" x="2936.5" y="-1020.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="2800.5,-1013 3072.5,-1013 "/>
<text text-anchor="middle" x="2936.5" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="2800.5,-990 3072.5,-990 "/>
<text text-anchor="middle" x="2936.5" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2800.5,-967 3072.5,-967 "/>
<text text-anchor="middle" x="2936.5" y="-951.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="2800.5,-944 3072.5,-944 "/>
<text text-anchor="middle" x="2936.5" y="-928.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="2800.5,-921 3072.5,-921 "/>
<text text-anchor="middle" x="2936.5" y="-905.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="2800.5,-898 3072.5,-898 "/>
<text text-anchor="middle" x="2936.5" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="2800.5,-875 3072.5,-875 "/>
<text text-anchor="middle" x="2936.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="2800.5,-852 3072.5,-852 "/>
<text text-anchor="middle" x="2936.5" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="2800.5,-829 3072.5,-829 "/>
<text text-anchor="middle" x="2936.5" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2800.5,-806 3072.5,-806 "/>
<text text-anchor="middle" x="2936.5" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="2800.5,-783 3072.5,-783 "/>
<text text-anchor="middle" x="2936.5" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="2800.5,-760 3072.5,-760 "/>
<text text-anchor="middle" x="2936.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="2800.5,-737 3072.5,-737 "/>
<text text-anchor="middle" x="2936.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="2800.5,-714 3072.5,-714 "/>
<text text-anchor="middle" x="2936.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="2800.5,-691 3072.5,-691 "/>
<text text-anchor="middle" x="2936.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="3072.5,-668 3072.5,-1059 "/>
<text text-anchor="middle" x="3083" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3005.1082,-667.6955C3033.1724,-629.6549 3065.9013,-592.7327 3102.5,-564 3151.8236,-525.2773 3213.8279,-496.8318 3271.5073,-476.4796"/>
<polygon fill="#000000" stroke="#000000" points="3272.795,-479.7376 3281.0972,-473.1554 3270.5024,-473.1237 3272.795,-479.7376"/>
<text text-anchor="middle" x="3188" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- publication -->
<g id="node15" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M4840,-409C4840,-409 5073,-409 5073,-409 5079,-409 5085,-415 5085,-421 5085,-421 5085,-443 5085,-443 5085,-449 5079,-455 5073,-455 5073,-455 4840,-455 4840,-455 4834,-455 4828,-449 4828,-443 4828,-443 4828,-421 4828,-421 4828,-415 4834,-409 4840,-409"/>
<text text-anchor="middle" x="4876.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="4925,-409 4925,-455 "/>
<text text-anchor="middle" x="4935.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4946,-409 4946,-455 "/>
<text text-anchor="middle" x="5005" y="-439.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication_id</text>
<polyline fill="none" stroke="#000000" points="4946,-432 5064,-432 "/>
<text text-anchor="middle" x="5005" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="5064,-409 5064,-455 "/>
<text text-anchor="middle" x="5074.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge21" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M4943.7339,-408.9228C4930.9815,-385.8704 4910.1784,-348.2649 4888.3298,-308.7692"/>
<polygon fill="#000000" stroke="#000000" points="4891.2609,-306.8372 4883.3576,-299.7811 4885.1357,-310.2257 4891.2609,-306.8372"/>
<text text-anchor="middle" x="4952.5" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- sequencing_file -->
<g id="node16" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M1868,-1214.5C1868,-1214.5 2337,-1214.5 2337,-1214.5 2343,-1214.5 2349,-1220.5 2349,-1226.5 2349,-1226.5 2349,-1800.5 2349,-1800.5 2349,-1806.5 2343,-1812.5 2337,-1812.5 2337,-1812.5 1868,-1812.5 1868,-1812.5 1862,-1812.5 1856,-1806.5 1856,-1800.5 1856,-1800.5 1856,-1226.5 1856,-1226.5 1856,-1220.5 1862,-1214.5 1868,-1214.5"/>
<text text-anchor="middle" x="1920" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="1984,-1214.5 1984,-1812.5 "/>
<text text-anchor="middle" x="1994.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2005,-1214.5 2005,-1812.5 "/>
<text text-anchor="middle" x="2166.5" y="-1797.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="2005,-1789.5 2328,-1789.5 "/>
<text text-anchor="middle" x="2166.5" y="-1774.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2005,-1766.5 2328,-1766.5 "/>
<text text-anchor="middle" x="2166.5" y="-1751.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2005,-1743.5 2328,-1743.5 "/>
<text text-anchor="middle" x="2166.5" y="-1728.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="2005,-1720.5 2328,-1720.5 "/>
<text text-anchor="middle" x="2166.5" y="-1705.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="2005,-1697.5 2328,-1697.5 "/>
<text text-anchor="middle" x="2166.5" y="-1682.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2005,-1674.5 2328,-1674.5 "/>
<text text-anchor="middle" x="2166.5" y="-1659.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="2005,-1651.5 2328,-1651.5 "/>
<text text-anchor="middle" x="2166.5" y="-1636.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2005,-1628.5 2328,-1628.5 "/>
<text text-anchor="middle" x="2166.5" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2005,-1605.5 2328,-1605.5 "/>
<text text-anchor="middle" x="2166.5" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2005,-1582.5 2328,-1582.5 "/>
<text text-anchor="middle" x="2166.5" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2005,-1559.5 2328,-1559.5 "/>
<text text-anchor="middle" x="2166.5" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2005,-1536.5 2328,-1536.5 "/>
<text text-anchor="middle" x="2166.5" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2005,-1513.5 2328,-1513.5 "/>
<text text-anchor="middle" x="2166.5" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="2005,-1490.5 2328,-1490.5 "/>
<text text-anchor="middle" x="2166.5" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="2005,-1467.5 2328,-1467.5 "/>
<text text-anchor="middle" x="2166.5" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="2005,-1444.5 2328,-1444.5 "/>
<text text-anchor="middle" x="2166.5" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="2005,-1421.5 2328,-1421.5 "/>
<text text-anchor="middle" x="2166.5" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="2005,-1398.5 2328,-1398.5 "/>
<text text-anchor="middle" x="2166.5" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="2005,-1375.5 2328,-1375.5 "/>
<text text-anchor="middle" x="2166.5" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2005,-1352.5 2328,-1352.5 "/>
<text text-anchor="middle" x="2166.5" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="2005,-1329.5 2328,-1329.5 "/>
<text text-anchor="middle" x="2166.5" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="2005,-1306.5 2328,-1306.5 "/>
<text text-anchor="middle" x="2166.5" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="2005,-1283.5 2328,-1283.5 "/>
<text text-anchor="middle" x="2166.5" y="-1268.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="2005,-1260.5 2328,-1260.5 "/>
<text text-anchor="middle" x="2166.5" y="-1245.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="2005,-1237.5 2328,-1237.5 "/>
<text text-anchor="middle" x="2166.5" y="-1222.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 1 properties</text>
<polyline fill="none" stroke="#000000" points="2328,-1214.5 2328,-1812.5 "/>
<text text-anchor="middle" x="2338.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1855.8788,-1219.3473C1852.7743,-1217.5118 1849.6479,-1215.7284 1846.5,-1214 1754.821,-1163.6628 1717.3639,-1193.2945 1613.5,-1181 1571.6025,-1176.0405 1460.7195,-1184.6367 1424.5,-1163 1385.2022,-1139.5244 1352.024,-1104.9805 1324.6792,-1067.6191"/>
<polygon fill="#000000" stroke="#000000" points="1327.2436,-1065.1887 1318.5749,-1059.0974 1321.5529,-1069.2651 1327.2436,-1065.1887"/>
<text text-anchor="middle" x="1873" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge12" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3609.5861,-388.113C3658.6288,-375.5265 3712.6176,-362.1924 3762.5,-351 4044.8073,-287.6569 4372.9839,-226.1163 4583.5208,-188.1722"/>
<polygon fill="#000000" stroke="#000000" points="4584.2353,-191.5999 4593.4568,-186.3833 4582.9949,-184.7107 4584.2353,-191.5999"/>
<text text-anchor="middle" x="3953" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- follow_up -->
<g id="node18" class="node">
<title>follow_up</title>
<path fill="none" stroke="#000000" d="M3124,-760C3124,-760 3487,-760 3487,-760 3493,-760 3499,-766 3499,-772 3499,-772 3499,-955 3499,-955 3499,-961 3493,-967 3487,-967 3487,-967 3124,-967 3124,-967 3118,-967 3112,-961 3112,-955 3112,-955 3112,-772 3112,-772 3112,-766 3118,-760 3124,-760"/>
<text text-anchor="middle" x="3154.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
<polyline fill="none" stroke="#000000" points="3197,-760 3197,-967 "/>
<text text-anchor="middle" x="3207.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3218,-760 3218,-967 "/>
<text text-anchor="middle" x="3348" y="-951.8" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event</text>
<polyline fill="none" stroke="#000000" points="3218,-944 3478,-944 "/>
<text text-anchor="middle" x="3348" y="-928.8" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity</text>
<polyline fill="none" stroke="#000000" points="3218,-921 3478,-921 "/>
<text text-anchor="middle" x="3348" y="-905.8" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity_method_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="3218,-898 3478,-898 "/>
<text text-anchor="middle" x="3348" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_follow_up</text>
<polyline fill="none" stroke="#000000" points="3218,-875 3478,-875 "/>
<text text-anchor="middle" x="3348" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_response</text>
<polyline fill="none" stroke="#000000" points="3218,-852 3478,-852 "/>
<text text-anchor="middle" x="3348" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_category</text>
<polyline fill="none" stroke="#000000" points="3218,-829 3478,-829 "/>
<text text-anchor="middle" x="3348" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_id</text>
<polyline fill="none" stroke="#000000" points="3218,-806 3478,-806 "/>
<text text-anchor="middle" x="3348" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_other</text>
<polyline fill="none" stroke="#000000" points="3218,-783 3478,-783 "/>
<text text-anchor="middle" x="3348" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">risk_factor</text>
<polyline fill="none" stroke="#000000" points="3478,-760 3478,-967 "/>
<text text-anchor="middle" x="3488.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3339.1225,-759.8706C3365.355,-679.0185 3401.026,-569.0752 3423.6597,-499.3148"/>
<polygon fill="#000000" stroke="#000000" points="3427.0076,-500.3372 3426.7646,-489.7452 3420.3492,-498.1769 3427.0076,-500.3372"/>
<text text-anchor="middle" x="3457.5" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- clinical_measure_file -->
<g id="node19" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M4914,-725.5C4914,-725.5 5287,-725.5 5287,-725.5 5293,-725.5 5299,-731.5 5299,-737.5 5299,-737.5 5299,-989.5 5299,-989.5 5299,-995.5 5293,-1001.5 5287,-1001.5 5287,-1001.5 4914,-1001.5 4914,-1001.5 4908,-1001.5 4902,-995.5 4902,-989.5 4902,-989.5 4902,-737.5 4902,-737.5 4902,-731.5 4908,-725.5 4914,-725.5"/>
<text text-anchor="middle" x="4985.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="5069,-725.5 5069,-1001.5 "/>
<text text-anchor="middle" x="5079.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="5090,-725.5 5090,-1001.5 "/>
<text text-anchor="middle" x="5184" y="-986.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="5090,-978.5 5278,-978.5 "/>
<text text-anchor="middle" x="5184" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="5090,-955.5 5278,-955.5 "/>
<text text-anchor="middle" x="5184" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file_id</text>
<polyline fill="none" stroke="#000000" points="5090,-932.5 5278,-932.5 "/>
<text text-anchor="middle" x="5184" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="5090,-909.5 5278,-909.5 "/>
<text text-anchor="middle" x="5184" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="5090,-886.5 5278,-886.5 "/>
<text text-anchor="middle" x="5184" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="5090,-863.5 5278,-863.5 "/>
<text text-anchor="middle" x="5184" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="5090,-840.5 5278,-840.5 "/>
<text text-anchor="middle" x="5184" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="5090,-817.5 5278,-817.5 "/>
<text text-anchor="middle" x="5184" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="5090,-794.5 5278,-794.5 "/>
<text text-anchor="middle" x="5184" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="5090,-771.5 5278,-771.5 "/>
<text text-anchor="middle" x="5184" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="5090,-748.5 5278,-748.5 "/>
<text text-anchor="middle" x="5184" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="5278,-725.5 5278,-1001.5 "/>
<text text-anchor="middle" x="5288.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge20" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M5113.7271,-725.2436C5123.5161,-595.4676 5129.7757,-412.3817 5094.5,-351 5074.8321,-316.7767 5046.6903,-287.1225 5015.5242,-261.8869"/>
<polygon fill="#000000" stroke="#000000" points="5017.552,-259.0282 5007.5388,-255.5662 5013.2075,-264.5169 5017.552,-259.0282"/>
<text text-anchor="middle" x="5206.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M5024.537,-725.2419C4988.6826,-669.5768 4941.7936,-608.2252 4887.5,-564 4885.7353,-562.5625 4814.7233,-531.4874 4812.5,-531 4698.5232,-506.0119 3878.1432,-528.5489 3762.5,-513 3715.5921,-506.6929 3665.637,-495.9106 3619.5878,-484.2343"/>
<polygon fill="#000000" stroke="#000000" points="3620.3792,-480.824 3609.8232,-481.7304 3618.6405,-487.6047 3620.3792,-480.824"/>
<text text-anchor="middle" x="4975" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1317.9513,-667.6922C1346.477,-626.974 1381.8499,-588.9148 1424.5,-564 1581.879,-472.0641 2810.1105,-442.4609 3271.2961,-434.5292"/>
<polygon fill="#000000" stroke="#000000" points="3271.4395,-438.0273 3281.3783,-434.3571 3271.32,-431.0283 3271.4395,-438.0273"/>
<text text-anchor="middle" x="1565" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- molecular_test -->
<g id="node21" class="node">
<title>molecular_test</title>
<path fill="none" stroke="#000000" d="M3918.5,-564.5C3918.5,-564.5 4306.5,-564.5 4306.5,-564.5 4312.5,-564.5 4318.5,-570.5 4318.5,-576.5 4318.5,-576.5 4318.5,-1150.5 4318.5,-1150.5 4318.5,-1156.5 4312.5,-1162.5 4306.5,-1162.5 4306.5,-1162.5 3918.5,-1162.5 3918.5,-1162.5 3912.5,-1162.5 3906.5,-1156.5 3906.5,-1150.5 3906.5,-1150.5 3906.5,-576.5 3906.5,-576.5 3906.5,-570.5 3912.5,-564.5 3918.5,-564.5"/>
<text text-anchor="middle" x="3968" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
<polyline fill="none" stroke="#000000" points="4029.5,-564.5 4029.5,-1162.5 "/>
<text text-anchor="middle" x="4040" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4050.5,-564.5 4050.5,-1162.5 "/>
<text text-anchor="middle" x="4174" y="-1147.3" font-family="Times,serif" font-size="14.00" fill="#000000">aa_change</text>
<polyline fill="none" stroke="#000000" points="4050.5,-1139.5 4297.5,-1139.5 "/>
<text text-anchor="middle" x="4174" y="-1124.3" font-family="Times,serif" font-size="14.00" fill="#000000">antigen</text>
<polyline fill="none" stroke="#000000" points="4050.5,-1116.5 4297.5,-1116.5 "/>
<text text-anchor="middle" x="4174" y="-1101.3" font-family="Times,serif" font-size="14.00" fill="#000000">biospecimen_type</text>
<polyline fill="none" stroke="#000000" points="4050.5,-1093.5 4297.5,-1093.5 "/>
<text text-anchor="middle" x="4174" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000">blood_test_normal_range_lower</text>
<polyline fill="none" stroke="#000000" points="4050.5,-1070.5 4297.5,-1070.5 "/>
<text text-anchor="middle" x="4174" y="-1055.3" font-family="Times,serif" font-size="14.00" fill="#000000">blood_test_normal_range_upper</text>
<polyline fill="none" stroke="#000000" points="4050.5,-1047.5 4297.5,-1047.5 "/>
<text text-anchor="middle" x="4174" y="-1032.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_count</text>
<polyline fill="none" stroke="#000000" points="4050.5,-1024.5 4297.5,-1024.5 "/>
<text text-anchor="middle" x="4174" y="-1009.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome</text>
<polyline fill="none" stroke="#000000" points="4050.5,-1001.5 4297.5,-1001.5 "/>
<text text-anchor="middle" x="4174" y="-986.3" font-family="Times,serif" font-size="14.00" fill="#000000">copy_number</text>
<polyline fill="none" stroke="#000000" points="4050.5,-978.5 4297.5,-978.5 "/>
<text text-anchor="middle" x="4174" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytoband</text>
<polyline fill="none" stroke="#000000" points="4050.5,-955.5 4297.5,-955.5 "/>
<text text-anchor="middle" x="4174" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">exon</text>
<polyline fill="none" stroke="#000000" points="4050.5,-932.5 4297.5,-932.5 "/>
<text text-anchor="middle" x="4174" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">gene_symbol</text>
<polyline fill="none" stroke="#000000" points="4050.5,-909.5 4297.5,-909.5 "/>
<text text-anchor="middle" x="4174" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">histone_family</text>
<polyline fill="none" stroke="#000000" points="4050.5,-886.5 4297.5,-886.5 "/>
<text text-anchor="middle" x="4174" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">histone_variant</text>
<polyline fill="none" stroke="#000000" points="4050.5,-863.5 4297.5,-863.5 "/>
<text text-anchor="middle" x="4174" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">intron</text>
<polyline fill="none" stroke="#000000" points="4050.5,-840.5 4297.5,-840.5 "/>
<text text-anchor="middle" x="4174" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
<polyline fill="none" stroke="#000000" points="4050.5,-817.5 4297.5,-817.5 "/>
<text text-anchor="middle" x="4174" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">loci_abnormal_count</text>
<polyline fill="none" stroke="#000000" points="4050.5,-794.5 4297.5,-794.5 "/>
<text text-anchor="middle" x="4174" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">loci_count</text>
<polyline fill="none" stroke="#000000" points="4050.5,-771.5 4297.5,-771.5 "/>
<text text-anchor="middle" x="4174" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">locus</text>
<polyline fill="none" stroke="#000000" points="4050.5,-748.5 4297.5,-748.5 "/>
<text text-anchor="middle" x="4174" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">mismatch_repair_mutation</text>
<polyline fill="none" stroke="#000000" points="4050.5,-725.5 4297.5,-725.5 "/>
<text text-anchor="middle" x="4174" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_analysis_method</text>
<polyline fill="none" stroke="#000000" points="4050.5,-702.5 4297.5,-702.5 "/>
<text text-anchor="middle" x="4174" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_consequence</text>
<polyline fill="none" stroke="#000000" points="4050.5,-679.5 4297.5,-679.5 "/>
<text text-anchor="middle" x="4174" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test_id</text>
<polyline fill="none" stroke="#000000" points="4050.5,-656.5 4297.5,-656.5 "/>
<text text-anchor="middle" x="4174" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathogenicity</text>
<polyline fill="none" stroke="#000000" points="4050.5,-633.5 4297.5,-633.5 "/>
<text text-anchor="middle" x="4174" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">ploidy</text>
<polyline fill="none" stroke="#000000" points="4050.5,-610.5 4297.5,-610.5 "/>
<text text-anchor="middle" x="4174" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">second_exon</text>
<polyline fill="none" stroke="#000000" points="4050.5,-587.5 4297.5,-587.5 "/>
<text text-anchor="middle" x="4174" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 11 properties</text>
<polyline fill="none" stroke="#000000" points="4297.5,-564.5 4297.5,-1162.5 "/>
<text text-anchor="middle" x="4308" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3906.4311,-570.5438C3903.4807,-568.3094 3900.5036,-566.1269 3897.5,-564 3873.7535,-547.1845 3736.6186,-508.2457 3619.5603,-476.992"/>
<polygon fill="#000000" stroke="#000000" points="3620.3025,-473.5677 3609.7385,-474.375 3618.5002,-480.3318 3620.3025,-473.5677"/>
<text text-anchor="middle" x="3915.5" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- study_funding -->
<g id="node22" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M5367,-386C5367,-386 5746,-386 5746,-386 5752,-386 5758,-392 5758,-398 5758,-398 5758,-466 5758,-466 5758,-472 5752,-478 5746,-478 5746,-478 5367,-478 5367,-478 5361,-478 5355,-472 5355,-466 5355,-466 5355,-398 5355,-398 5355,-392 5361,-386 5367,-386"/>
<text text-anchor="middle" x="5414.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="5474,-386 5474,-478 "/>
<text text-anchor="middle" x="5484.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="5495,-386 5495,-478 "/>
<text text-anchor="middle" x="5616" y="-462.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="5495,-455 5737,-455 "/>
<text text-anchor="middle" x="5616" y="-439.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="5495,-432 5737,-432 "/>
<text text-anchor="middle" x="5616" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="5495,-409 5737,-409 "/>
<text text-anchor="middle" x="5616" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding_id</text>
<polyline fill="none" stroke="#000000" points="5737,-386 5737,-478 "/>
<text text-anchor="middle" x="5747.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge22" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M5477.671,-385.9062C5437.4696,-363.5651 5387.2958,-337.434 5340.5,-318 5236.4092,-274.7717 5117.0862,-236.5305 5017.1232,-207.4961"/>
<polygon fill="#000000" stroke="#000000" points="5018.0898,-204.1323 5007.511,-204.7152 5016.1444,-210.8565 5018.0898,-204.1323"/>
<text text-anchor="middle" x="5432.5" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- therapeutic_procedure -->
<g id="node23" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M4349,-794.5C4349,-794.5 4750,-794.5 4750,-794.5 4756,-794.5 4762,-800.5 4762,-806.5 4762,-806.5 4762,-920.5 4762,-920.5 4762,-926.5 4756,-932.5 4750,-932.5 4750,-932.5 4349,-932.5 4349,-932.5 4343,-932.5 4337,-926.5 4337,-920.5 4337,-920.5 4337,-806.5 4337,-806.5 4337,-800.5 4343,-794.5 4349,-794.5"/>
<text text-anchor="middle" x="4427.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="4518,-794.5 4518,-932.5 "/>
<text text-anchor="middle" x="4528.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4539,-794.5 4539,-932.5 "/>
<text text-anchor="middle" x="4640" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment_end</text>
<polyline fill="none" stroke="#000000" points="4539,-909.5 4741,-909.5 "/>
<text text-anchor="middle" x="4640" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment_start</text>
<polyline fill="none" stroke="#000000" points="4539,-886.5 4741,-886.5 "/>
<text text-anchor="middle" x="4640" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="4539,-863.5 4741,-863.5 "/>
<text text-anchor="middle" x="4640" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure_id</text>
<polyline fill="none" stroke="#000000" points="4539,-840.5 4741,-840.5 "/>
<text text-anchor="middle" x="4640" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="4539,-817.5 4741,-817.5 "/>
<text text-anchor="middle" x="4640" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="4741,-794.5 4741,-932.5 "/>
<text text-anchor="middle" x="4751.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M4519.2588,-794.1868C4484.2375,-723.1262 4419.3522,-615.896 4327.5,-564 4217.7412,-501.9868 3886.8389,-533.7959 3762.5,-513 3715.6876,-505.1705 3665.6629,-493.8229 3619.5099,-482.0878"/>
<polygon fill="#000000" stroke="#000000" points="3620.2786,-478.6718 3609.7226,-479.5789 3618.5403,-485.4525 3620.2786,-478.6718"/>
<text text-anchor="middle" x="4371.5" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
</g>
</svg>
</div>
