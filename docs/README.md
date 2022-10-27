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
<svg width="2311pt" height="1551pt"
 viewBox="0.00 0.00 2311.00 1551.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1547)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1547 2307,-1547 2307,4 -4,4"/>
<!-- study_arm -->
<g id="node1" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M1080.5,-317C1080.5,-317 1377.5,-317 1377.5,-317 1383.5,-317 1389.5,-323 1389.5,-329 1389.5,-329 1389.5,-374 1389.5,-374 1389.5,-380 1383.5,-386 1377.5,-386 1377.5,-386 1080.5,-386 1080.5,-386 1074.5,-386 1068.5,-380 1068.5,-374 1068.5,-374 1068.5,-329 1068.5,-329 1068.5,-323 1074.5,-317 1080.5,-317"/>
<text text-anchor="middle" x="1114.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="1160.5,-317 1160.5,-386 "/>
<text text-anchor="middle" x="1171" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1181.5,-317 1181.5,-386 "/>
<text text-anchor="middle" x="1275" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="1181.5,-363 1368.5,-363 "/>
<text text-anchor="middle" x="1275" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="1181.5,-340 1368.5,-340 "/>
<text text-anchor="middle" x="1275" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="1368.5,-317 1368.5,-386 "/>
<text text-anchor="middle" x="1379" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node8" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M754,-.5C754,-.5 1144,-.5 1144,-.5 1150,-.5 1156,-6.5 1156,-12.5 1156,-12.5 1156,-195.5 1156,-195.5 1156,-201.5 1150,-207.5 1144,-207.5 1144,-207.5 754,-207.5 754,-207.5 748,-207.5 742,-201.5 742,-195.5 742,-195.5 742,-12.5 742,-12.5 742,-6.5 748,-.5 754,-.5"/>
<text text-anchor="middle" x="770" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="798,-.5 798,-207.5 "/>
<text text-anchor="middle" x="808.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="819,-.5 819,-207.5 "/>
<text text-anchor="middle" x="977" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="819,-184.5 1135,-184.5 "/>
<text text-anchor="middle" x="977" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="819,-161.5 1135,-161.5 "/>
<text text-anchor="middle" x="977" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="819,-138.5 1135,-138.5 "/>
<text text-anchor="middle" x="977" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="819,-115.5 1135,-115.5 "/>
<text text-anchor="middle" x="977" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="819,-92.5 1135,-92.5 "/>
<text text-anchor="middle" x="977" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="819,-69.5 1135,-69.5 "/>
<text text-anchor="middle" x="977" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="819,-46.5 1135,-46.5 "/>
<text text-anchor="middle" x="977" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="819,-23.5 1135,-23.5 "/>
<text text-anchor="middle" x="977" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="1135,-.5 1135,-207.5 "/>
<text text-anchor="middle" x="1145.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge19" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1189.7724,-316.8256C1159.459,-290.0308 1115.7369,-251.3835 1073.846,-214.3549"/>
<polygon fill="#000000" stroke="#000000" points="1076.1341,-211.7061 1066.3235,-207.7056 1071.498,-216.9509 1076.1341,-211.7061"/>
<text text-anchor="middle" x="1146.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- clinical_measure_file -->
<g id="node2" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M95,-662.5C95,-662.5 447,-662.5 447,-662.5 453,-662.5 459,-668.5 459,-674.5 459,-674.5 459,-903.5 459,-903.5 459,-909.5 453,-915.5 447,-915.5 447,-915.5 95,-915.5 95,-915.5 89,-915.5 83,-909.5 83,-903.5 83,-903.5 83,-674.5 83,-674.5 83,-668.5 89,-662.5 95,-662.5"/>
<text text-anchor="middle" x="166.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="250,-662.5 250,-915.5 "/>
<text text-anchor="middle" x="260.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="271,-662.5 271,-915.5 "/>
<text text-anchor="middle" x="354.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="271,-892.5 438,-892.5 "/>
<text text-anchor="middle" x="354.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="271,-869.5 438,-869.5 "/>
<text text-anchor="middle" x="354.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="271,-846.5 438,-846.5 "/>
<text text-anchor="middle" x="354.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="271,-823.5 438,-823.5 "/>
<text text-anchor="middle" x="354.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="271,-800.5 438,-800.5 "/>
<text text-anchor="middle" x="354.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="271,-777.5 438,-777.5 "/>
<text text-anchor="middle" x="354.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="271,-754.5 438,-754.5 "/>
<text text-anchor="middle" x="354.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="271,-731.5 438,-731.5 "/>
<text text-anchor="middle" x="354.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="271,-708.5 438,-708.5 "/>
<text text-anchor="middle" x="354.5" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="271,-685.5 438,-685.5 "/>
<text text-anchor="middle" x="354.5" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="438,-662.5 438,-915.5 "/>
<text text-anchor="middle" x="448.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node6" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M833.5,-495.5C833.5,-495.5 1064.5,-495.5 1064.5,-495.5 1070.5,-495.5 1076.5,-501.5 1076.5,-507.5 1076.5,-507.5 1076.5,-575.5 1076.5,-575.5 1076.5,-581.5 1070.5,-587.5 1064.5,-587.5 1064.5,-587.5 833.5,-587.5 833.5,-587.5 827.5,-587.5 821.5,-581.5 821.5,-575.5 821.5,-575.5 821.5,-507.5 821.5,-507.5 821.5,-501.5 827.5,-495.5 833.5,-495.5"/>
<text text-anchor="middle" x="869.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="917.5,-495.5 917.5,-587.5 "/>
<text text-anchor="middle" x="928" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="938.5,-495.5 938.5,-587.5 "/>
<text text-anchor="middle" x="997" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="938.5,-564.5 1055.5,-564.5 "/>
<text text-anchor="middle" x="997" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="938.5,-541.5 1055.5,-541.5 "/>
<text text-anchor="middle" x="997" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="938.5,-518.5 1055.5,-518.5 "/>
<text text-anchor="middle" x="997" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1055.5,-495.5 1055.5,-587.5 "/>
<text text-anchor="middle" x="1066" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M372.0894,-662.4783C395.4171,-640.4247 421.7609,-620.0789 450,-606 511.5098,-575.3335 685.95,-557.9967 811.2419,-549.1896"/>
<polygon fill="#000000" stroke="#000000" points="811.5753,-552.6749 821.3098,-548.4927 811.0919,-545.6916 811.5753,-552.6749"/>
<text text-anchor="middle" x="579.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge9" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M180.9552,-662.4467C109.9039,-545.6518 37.1996,-373.4768 132,-259 206.8365,-168.6307 516.0132,-130.5315 731.7753,-114.7579"/>
<polygon fill="#000000" stroke="#000000" points="732.2548,-118.2325 741.9777,-114.0235 731.7522,-111.2506 732.2548,-118.2325"/>
<text text-anchor="middle" x="184" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- study_admin -->
<g id="node3" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M153,-259.5C153,-259.5 479,-259.5 479,-259.5 485,-259.5 491,-265.5 491,-271.5 491,-271.5 491,-431.5 491,-431.5 491,-437.5 485,-443.5 479,-443.5 479,-443.5 153,-443.5 153,-443.5 147,-443.5 141,-437.5 141,-431.5 141,-431.5 141,-271.5 141,-271.5 141,-265.5 147,-259.5 153,-259.5"/>
<text text-anchor="middle" x="195" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="249,-259.5 249,-443.5 "/>
<text text-anchor="middle" x="259.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="270,-259.5 270,-443.5 "/>
<text text-anchor="middle" x="370" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="270,-420.5 470,-420.5 "/>
<text text-anchor="middle" x="370" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="270,-397.5 470,-397.5 "/>
<text text-anchor="middle" x="370" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="270,-374.5 470,-374.5 "/>
<text text-anchor="middle" x="370" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="270,-351.5 470,-351.5 "/>
<text text-anchor="middle" x="370" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="270,-328.5 470,-328.5 "/>
<text text-anchor="middle" x="370" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="270,-305.5 470,-305.5 "/>
<text text-anchor="middle" x="370" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="270,-282.5 470,-282.5 "/>
<text text-anchor="middle" x="370" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="470,-259.5 470,-443.5 "/>
<text text-anchor="middle" x="480.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge2" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M491.0533,-262.8272C494.0512,-261.5273 497.0351,-260.2505 500,-259 574.5072,-227.5769 657.8115,-197.4853 732.2425,-172.3154"/>
<polygon fill="#000000" stroke="#000000" points="733.3844,-175.6241 741.7426,-169.1132 731.1485,-168.9908 733.3844,-175.6241"/>
<text text-anchor="middle" x="629.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- diagnosis -->
<g id="node4" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1036.5,-639.5C1036.5,-639.5 1419.5,-639.5 1419.5,-639.5 1425.5,-639.5 1431.5,-645.5 1431.5,-651.5 1431.5,-651.5 1431.5,-926.5 1431.5,-926.5 1431.5,-932.5 1425.5,-938.5 1419.5,-938.5 1419.5,-938.5 1036.5,-938.5 1036.5,-938.5 1030.5,-938.5 1024.5,-932.5 1024.5,-926.5 1024.5,-926.5 1024.5,-651.5 1024.5,-651.5 1024.5,-645.5 1030.5,-639.5 1036.5,-639.5"/>
<text text-anchor="middle" x="1066.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1108.5,-639.5 1108.5,-938.5 "/>
<text text-anchor="middle" x="1119" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1129.5,-639.5 1129.5,-938.5 "/>
<text text-anchor="middle" x="1270" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1129.5,-915.5 1410.5,-915.5 "/>
<text text-anchor="middle" x="1270" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1129.5,-892.5 1410.5,-892.5 "/>
<text text-anchor="middle" x="1270" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1129.5,-869.5 1410.5,-869.5 "/>
<text text-anchor="middle" x="1270" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1129.5,-846.5 1410.5,-846.5 "/>
<text text-anchor="middle" x="1270" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1129.5,-823.5 1410.5,-823.5 "/>
<text text-anchor="middle" x="1270" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="1129.5,-800.5 1410.5,-800.5 "/>
<text text-anchor="middle" x="1270" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1129.5,-777.5 1410.5,-777.5 "/>
<text text-anchor="middle" x="1270" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1129.5,-754.5 1410.5,-754.5 "/>
<text text-anchor="middle" x="1270" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis_reference_source</text>
<polyline fill="none" stroke="#000000" points="1129.5,-731.5 1410.5,-731.5 "/>
<text text-anchor="middle" x="1270" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="1129.5,-708.5 1410.5,-708.5 "/>
<text text-anchor="middle" x="1270" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="1129.5,-685.5 1410.5,-685.5 "/>
<text text-anchor="middle" x="1270" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="1129.5,-662.5 1410.5,-662.5 "/>
<text text-anchor="middle" x="1270" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="1410.5,-639.5 1410.5,-938.5 "/>
<text text-anchor="middle" x="1421" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1059.2682,-639.3186C1041.3848,-623.4542 1024.1724,-608.1852 1008.8794,-594.6188"/>
<polygon fill="#000000" stroke="#000000" points="1010.8671,-591.7034 1001.0637,-587.6855 1006.2218,-596.94 1010.8671,-591.7034"/>
<text text-anchor="middle" x="1076.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- study_funding -->
<g id="node5" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M521.5,-317C521.5,-317 900.5,-317 900.5,-317 906.5,-317 912.5,-323 912.5,-329 912.5,-329 912.5,-374 912.5,-374 912.5,-380 906.5,-386 900.5,-386 900.5,-386 521.5,-386 521.5,-386 515.5,-386 509.5,-380 509.5,-374 509.5,-374 509.5,-329 509.5,-329 509.5,-323 515.5,-317 521.5,-317"/>
<text text-anchor="middle" x="569" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="628.5,-317 628.5,-386 "/>
<text text-anchor="middle" x="639" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="649.5,-317 649.5,-386 "/>
<text text-anchor="middle" x="770.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="649.5,-363 891.5,-363 "/>
<text text-anchor="middle" x="770.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="649.5,-340 891.5,-340 "/>
<text text-anchor="middle" x="770.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="891.5,-317 891.5,-386 "/>
<text text-anchor="middle" x="902" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge6" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M736.0088,-316.8833C755.3766,-290.9063 783.4634,-254.9822 811,-226 814.5569,-222.2563 818.2143,-218.4995 821.9451,-214.7461"/>
<polygon fill="#000000" stroke="#000000" points="824.5751,-217.067 829.2035,-207.5366 819.6421,-212.1005 824.5751,-217.067"/>
<text text-anchor="middle" x="873" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge5" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1017.1377,-495.2637C1063.6727,-463.6864 1124.741,-422.2472 1169.3525,-391.9751"/>
<polygon fill="#000000" stroke="#000000" points="1171.4551,-394.7781 1177.7646,-386.2669 1167.5245,-388.9858 1171.4551,-394.7781"/>
<text text-anchor="middle" x="1114.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge4" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M949,-495.094C949,-429.596 949,-307.9591 949,-217.6598"/>
<polygon fill="#000000" stroke="#000000" points="952.5001,-217.6413 949,-207.6413 945.5001,-217.6414 952.5001,-217.6413"/>
<text text-anchor="middle" x="999.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- imaging_file -->
<g id="node7" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M1957,-1105.5C1957,-1105.5 2291,-1105.5 2291,-1105.5 2297,-1105.5 2303,-1111.5 2303,-1117.5 2303,-1117.5 2303,-1415.5 2303,-1415.5 2303,-1421.5 2297,-1427.5 2291,-1427.5 2291,-1427.5 1957,-1427.5 1957,-1427.5 1951,-1427.5 1945,-1421.5 1945,-1415.5 1945,-1415.5 1945,-1117.5 1945,-1117.5 1945,-1111.5 1951,-1105.5 1957,-1105.5"/>
<text text-anchor="middle" x="1997" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="2049,-1105.5 2049,-1427.5 "/>
<text text-anchor="middle" x="2059.5" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2070,-1105.5 2070,-1427.5 "/>
<text text-anchor="middle" x="2176" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2070,-1404.5 2282,-1404.5 "/>
<text text-anchor="middle" x="2176" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2070,-1381.5 2282,-1381.5 "/>
<text text-anchor="middle" x="2176" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2070,-1358.5 2282,-1358.5 "/>
<text text-anchor="middle" x="2176" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2070,-1335.5 2282,-1335.5 "/>
<text text-anchor="middle" x="2176" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2070,-1312.5 2282,-1312.5 "/>
<text text-anchor="middle" x="2176" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2070,-1289.5 2282,-1289.5 "/>
<text text-anchor="middle" x="2176" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2070,-1266.5 2282,-1266.5 "/>
<text text-anchor="middle" x="2176" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2070,-1243.5 2282,-1243.5 "/>
<text text-anchor="middle" x="2176" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2070,-1220.5 2282,-1220.5 "/>
<text text-anchor="middle" x="2176" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="2070,-1197.5 2282,-1197.5 "/>
<text text-anchor="middle" x="2176" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="2070,-1174.5 2282,-1174.5 "/>
<text text-anchor="middle" x="2176" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="2070,-1151.5 2282,-1151.5 "/>
<text text-anchor="middle" x="2176" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2070,-1128.5 2282,-1128.5 "/>
<text text-anchor="middle" x="2176" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="2282,-1105.5 2282,-1427.5 "/>
<text text-anchor="middle" x="2292.5" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node12" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1497,-651C1497,-651 1811,-651 1811,-651 1817,-651 1823,-657 1823,-663 1823,-663 1823,-915 1823,-915 1823,-921 1817,-927 1811,-927 1811,-927 1497,-927 1497,-927 1491,-927 1485,-921 1485,-915 1485,-915 1485,-663 1485,-663 1485,-657 1491,-651 1497,-651"/>
<text text-anchor="middle" x="1519" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1553,-651 1553,-927 "/>
<text text-anchor="middle" x="1563.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1574,-651 1574,-927 "/>
<text text-anchor="middle" x="1688" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1574,-904 1802,-904 "/>
<text text-anchor="middle" x="1688" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1574,-881 1802,-881 "/>
<text text-anchor="middle" x="1688" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1574,-858 1802,-858 "/>
<text text-anchor="middle" x="1688" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1574,-835 1802,-835 "/>
<text text-anchor="middle" x="1688" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1574,-812 1802,-812 "/>
<text text-anchor="middle" x="1688" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="1574,-789 1802,-789 "/>
<text text-anchor="middle" x="1688" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1574,-766 1802,-766 "/>
<text text-anchor="middle" x="1688" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="1574,-743 1802,-743 "/>
<text text-anchor="middle" x="1688" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="1574,-720 1802,-720 "/>
<text text-anchor="middle" x="1688" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1574,-697 1802,-697 "/>
<text text-anchor="middle" x="1688" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1574,-674 1802,-674 "/>
<text text-anchor="middle" x="1688" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1802,-651 1802,-927 "/>
<text text-anchor="middle" x="1812.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2028.3812,-1105.1762C2001.1056,-1065.3693 1969.5883,-1024.3395 1936,-990 1904.8305,-958.1335 1868.0616,-927.8655 1831.5512,-900.9431"/>
<polygon fill="#000000" stroke="#000000" points="1833.4129,-897.9686 1823.2743,-894.8929 1829.2819,-903.6198 1833.4129,-897.9686"/>
<text text-anchor="middle" x="1969.5" y="-960.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- synonym -->
<g id="node9" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M693.5,-1243.5C693.5,-1243.5 994.5,-1243.5 994.5,-1243.5 1000.5,-1243.5 1006.5,-1249.5 1006.5,-1255.5 1006.5,-1255.5 1006.5,-1277.5 1006.5,-1277.5 1006.5,-1283.5 1000.5,-1289.5 994.5,-1289.5 994.5,-1289.5 693.5,-1289.5 693.5,-1289.5 687.5,-1289.5 681.5,-1283.5 681.5,-1277.5 681.5,-1277.5 681.5,-1255.5 681.5,-1255.5 681.5,-1249.5 687.5,-1243.5 693.5,-1243.5"/>
<text text-anchor="middle" x="721.5" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="761.5,-1243.5 761.5,-1289.5 "/>
<text text-anchor="middle" x="772" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="782.5,-1243.5 782.5,-1289.5 "/>
<text text-anchor="middle" x="884" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="782.5,-1266.5 985.5,-1266.5 "/>
<text text-anchor="middle" x="884" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="985.5,-1243.5 985.5,-1289.5 "/>
<text text-anchor="middle" x="996" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M847.8352,-1243.1074C856.5768,-1189.435 878.4258,-1053.264 894,-939 912.136,-805.9404 909.143,-771.6603 930,-639 932.113,-625.56 934.7281,-611.1443 937.3351,-597.6306"/>
<polygon fill="#000000" stroke="#000000" points="940.8312,-597.9898 939.3187,-587.5035 933.9617,-596.6442 940.8312,-597.9898"/>
<text text-anchor="middle" x="972.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge16" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M681.2683,-1247.9429C436.0117,-1209.9225 0,-1098.7693 0,-789 0,-789 0,-789 0,-351.5 0,-201.1807 451.4506,-140.4788 731.604,-117.2813"/>
<polygon fill="#000000" stroke="#000000" points="732.2292,-120.742 741.9106,-116.4384 731.6586,-113.7653 732.2292,-120.742"/>
<text text-anchor="middle" x="42.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M850.7428,-1243.3741C868.0138,-1188.7023 919.4263,-1051.4752 1016,-990 1176.4871,-887.8399 1263.3901,-1007.1726 1441,-939 1452.6614,-934.524 1464.2856,-929.268 1475.7449,-923.4524"/>
<polygon fill="#000000" stroke="#000000" points="1477.6535,-926.4043 1484.8973,-918.6727 1474.413,-920.1995 1477.6535,-926.4043"/>
<text text-anchor="middle" x="1413.5" y="-960.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- sequencing_file -->
<g id="node10" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M1036.5,-990.5C1036.5,-990.5 1505.5,-990.5 1505.5,-990.5 1511.5,-990.5 1517.5,-996.5 1517.5,-1002.5 1517.5,-1002.5 1517.5,-1530.5 1517.5,-1530.5 1517.5,-1536.5 1511.5,-1542.5 1505.5,-1542.5 1505.5,-1542.5 1036.5,-1542.5 1036.5,-1542.5 1030.5,-1542.5 1024.5,-1536.5 1024.5,-1530.5 1024.5,-1530.5 1024.5,-1002.5 1024.5,-1002.5 1024.5,-996.5 1030.5,-990.5 1036.5,-990.5"/>
<text text-anchor="middle" x="1088.5" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="1152.5,-990.5 1152.5,-1542.5 "/>
<text text-anchor="middle" x="1163" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1173.5,-990.5 1173.5,-1542.5 "/>
<text text-anchor="middle" x="1335" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="1173.5,-1519.5 1496.5,-1519.5 "/>
<text text-anchor="middle" x="1335" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1173.5,-1496.5 1496.5,-1496.5 "/>
<text text-anchor="middle" x="1335" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1173.5,-1473.5 1496.5,-1473.5 "/>
<text text-anchor="middle" x="1335" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="1173.5,-1450.5 1496.5,-1450.5 "/>
<text text-anchor="middle" x="1335" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="1173.5,-1427.5 1496.5,-1427.5 "/>
<text text-anchor="middle" x="1335" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1173.5,-1404.5 1496.5,-1404.5 "/>
<text text-anchor="middle" x="1335" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1173.5,-1381.5 1496.5,-1381.5 "/>
<text text-anchor="middle" x="1335" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1173.5,-1358.5 1496.5,-1358.5 "/>
<text text-anchor="middle" x="1335" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1173.5,-1335.5 1496.5,-1335.5 "/>
<text text-anchor="middle" x="1335" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1173.5,-1312.5 1496.5,-1312.5 "/>
<text text-anchor="middle" x="1335" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1173.5,-1289.5 1496.5,-1289.5 "/>
<text text-anchor="middle" x="1335" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1173.5,-1266.5 1496.5,-1266.5 "/>
<text text-anchor="middle" x="1335" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="1173.5,-1243.5 1496.5,-1243.5 "/>
<text text-anchor="middle" x="1335" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="1173.5,-1220.5 1496.5,-1220.5 "/>
<text text-anchor="middle" x="1335" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="1173.5,-1197.5 1496.5,-1197.5 "/>
<text text-anchor="middle" x="1335" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="1173.5,-1174.5 1496.5,-1174.5 "/>
<text text-anchor="middle" x="1335" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="1173.5,-1151.5 1496.5,-1151.5 "/>
<text text-anchor="middle" x="1335" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="1173.5,-1128.5 1496.5,-1128.5 "/>
<text text-anchor="middle" x="1335" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1173.5,-1105.5 1496.5,-1105.5 "/>
<text text-anchor="middle" x="1335" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="1173.5,-1082.5 1496.5,-1082.5 "/>
<text text-anchor="middle" x="1335" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="1173.5,-1059.5 1496.5,-1059.5 "/>
<text text-anchor="middle" x="1335" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="1173.5,-1036.5 1496.5,-1036.5 "/>
<text text-anchor="middle" x="1335" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="1173.5,-1013.5 1496.5,-1013.5 "/>
<text text-anchor="middle" x="1335" y="-998.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="1496.5,-990.5 1496.5,-1542.5 "/>
<text text-anchor="middle" x="1507" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1492.4061,-990.4649C1507.5604,-971.5715 1522.4585,-952.9975 1536.7082,-935.232"/>
<polygon fill="#000000" stroke="#000000" points="1539.6815,-937.1188 1543.2082,-927.1281 1534.221,-932.7389 1539.6815,-937.1188"/>
<text text-anchor="middle" x="1585.5" y="-960.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- publication -->
<g id="node11" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M1420,-333.5C1420,-333.5 1630,-333.5 1630,-333.5 1636,-333.5 1642,-339.5 1642,-345.5 1642,-345.5 1642,-357.5 1642,-357.5 1642,-363.5 1636,-369.5 1630,-369.5 1630,-369.5 1420,-369.5 1420,-369.5 1414,-369.5 1408,-363.5 1408,-357.5 1408,-357.5 1408,-345.5 1408,-345.5 1408,-339.5 1414,-333.5 1420,-333.5"/>
<text text-anchor="middle" x="1456.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="1505,-333.5 1505,-369.5 "/>
<text text-anchor="middle" x="1515.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1526,-333.5 1526,-369.5 "/>
<text text-anchor="middle" x="1573.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="1621,-333.5 1621,-369.5 "/>
<text text-anchor="middle" x="1631.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge11" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1504.4584,-333.3579C1480.533,-312.9841 1439.145,-280.0272 1399,-259 1325.9977,-220.7628 1241.5767,-188.7934 1165.7143,-164.0117"/>
<polygon fill="#000000" stroke="#000000" points="1166.621,-160.6263 1156.029,-160.8715 1164.462,-167.2851 1166.621,-160.6263"/>
<text text-anchor="middle" x="1403" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1484.6962,-660.7486C1470.3141,-652.6676 1455.6559,-645.276 1441,-639 1327.1227,-590.2353 1187.8734,-565.5593 1086.6186,-553.2585"/>
<polygon fill="#000000" stroke="#000000" points="1086.9756,-549.7764 1076.6321,-552.0705 1086.1486,-556.7274 1086.9756,-549.7764"/>
<text text-anchor="middle" x="1426.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge7" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1671.996,-650.8686C1686.5826,-514.1182 1697.8769,-317.0191 1651,-259 1590.6345,-184.2861 1349.0898,-143.3832 1166.0529,-122.6426"/>
<polygon fill="#000000" stroke="#000000" points="1166.3382,-119.1527 1156.0108,-121.5182 1165.5592,-126.1093 1166.3382,-119.1527"/>
<text text-anchor="middle" x="1720.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- therapeutic_procedure -->
<g id="node13" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M516.5,-731.5C516.5,-731.5 873.5,-731.5 873.5,-731.5 879.5,-731.5 885.5,-737.5 885.5,-743.5 885.5,-743.5 885.5,-834.5 885.5,-834.5 885.5,-840.5 879.5,-846.5 873.5,-846.5 873.5,-846.5 516.5,-846.5 516.5,-846.5 510.5,-846.5 504.5,-840.5 504.5,-834.5 504.5,-834.5 504.5,-743.5 504.5,-743.5 504.5,-737.5 510.5,-731.5 516.5,-731.5"/>
<text text-anchor="middle" x="595" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="685.5,-731.5 685.5,-846.5 "/>
<text text-anchor="middle" x="696" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="706.5,-731.5 706.5,-846.5 "/>
<text text-anchor="middle" x="785.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="706.5,-823.5 864.5,-823.5 "/>
<text text-anchor="middle" x="785.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="706.5,-800.5 864.5,-800.5 "/>
<text text-anchor="middle" x="785.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="706.5,-777.5 864.5,-777.5 "/>
<text text-anchor="middle" x="785.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="706.5,-754.5 864.5,-754.5 "/>
<text text-anchor="middle" x="785.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="864.5,-731.5 864.5,-846.5 "/>
<text text-anchor="middle" x="875" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M687.9694,-731.1684C686.4355,-691.3897 691.4402,-639.8312 721,-606 734.3433,-590.7286 771.2283,-577.653 811.5422,-567.3471"/>
<polygon fill="#000000" stroke="#000000" points="812.4338,-570.732 821.2936,-564.9221 810.7445,-563.9389 812.4338,-570.732"/>
<text text-anchor="middle" x="814" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- study_personnel -->
<g id="node14" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M1710.5,-294C1710.5,-294 2017.5,-294 2017.5,-294 2023.5,-294 2029.5,-300 2029.5,-306 2029.5,-306 2029.5,-397 2029.5,-397 2029.5,-403 2023.5,-409 2017.5,-409 2017.5,-409 1710.5,-409 1710.5,-409 1704.5,-409 1698.5,-403 1698.5,-397 1698.5,-397 1698.5,-306 1698.5,-306 1698.5,-300 1704.5,-294 1710.5,-294"/>
<text text-anchor="middle" x="1765.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="1832.5,-294 1832.5,-409 "/>
<text text-anchor="middle" x="1843" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1853.5,-294 1853.5,-409 "/>
<text text-anchor="middle" x="1931" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="1853.5,-386 2008.5,-386 "/>
<text text-anchor="middle" x="1931" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="1853.5,-363 2008.5,-363 "/>
<text text-anchor="middle" x="1931" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="1853.5,-340 2008.5,-340 "/>
<text text-anchor="middle" x="1931" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="1853.5,-317 2008.5,-317 "/>
<text text-anchor="middle" x="1931" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="2008.5,-294 2008.5,-409 "/>
<text text-anchor="middle" x="2019" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge15" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1796.8422,-293.9362C1764.6684,-269.2901 1724.3992,-242.4494 1684,-226 1592.4648,-188.7295 1348.3124,-152.4832 1166.3616,-129.3187"/>
<polygon fill="#000000" stroke="#000000" points="1166.744,-125.8393 1156.3831,-128.0535 1165.8634,-132.7837 1166.744,-125.8393"/>
<text text-anchor="middle" x="1779.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- methylation_array_file -->
<g id="node15" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M1547.5,-1151.5C1547.5,-1151.5 1914.5,-1151.5 1914.5,-1151.5 1920.5,-1151.5 1926.5,-1157.5 1926.5,-1163.5 1926.5,-1163.5 1926.5,-1369.5 1926.5,-1369.5 1926.5,-1375.5 1920.5,-1381.5 1914.5,-1381.5 1914.5,-1381.5 1547.5,-1381.5 1547.5,-1381.5 1541.5,-1381.5 1535.5,-1375.5 1535.5,-1369.5 1535.5,-1369.5 1535.5,-1163.5 1535.5,-1163.5 1535.5,-1157.5 1541.5,-1151.5 1547.5,-1151.5"/>
<text text-anchor="middle" x="1624.5" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="1713.5,-1151.5 1713.5,-1381.5 "/>
<text text-anchor="middle" x="1724" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1734.5,-1151.5 1734.5,-1381.5 "/>
<text text-anchor="middle" x="1820" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1734.5,-1358.5 1905.5,-1358.5 "/>
<text text-anchor="middle" x="1820" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1734.5,-1335.5 1905.5,-1335.5 "/>
<text text-anchor="middle" x="1820" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1734.5,-1312.5 1905.5,-1312.5 "/>
<text text-anchor="middle" x="1820" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1734.5,-1289.5 1905.5,-1289.5 "/>
<text text-anchor="middle" x="1820" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1734.5,-1266.5 1905.5,-1266.5 "/>
<text text-anchor="middle" x="1820" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1734.5,-1243.5 1905.5,-1243.5 "/>
<text text-anchor="middle" x="1820" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1734.5,-1220.5 1905.5,-1220.5 "/>
<text text-anchor="middle" x="1820" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1734.5,-1197.5 1905.5,-1197.5 "/>
<text text-anchor="middle" x="1820" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="1734.5,-1174.5 1905.5,-1174.5 "/>
<text text-anchor="middle" x="1820" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="1905.5,-1151.5 1905.5,-1381.5 "/>
<text text-anchor="middle" x="1916" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1712.4095,-1151.215C1702.0382,-1086.8995 1689.0076,-1006.0925 1677.887,-937.1303"/>
<polygon fill="#000000" stroke="#000000" points="1681.3081,-936.3601 1676.2606,-927.0449 1674.3974,-937.4746 1681.3081,-936.3601"/>
<text text-anchor="middle" x="1774.5" y="-960.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
</g>
</svg>
</div>
