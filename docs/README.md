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
<svg width="2211pt" height="1045pt"
 viewBox="0.00 0.00 2210.63 1045.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1041)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1041 2206.6255,-1041 2206.6255,4 -4,4"/>
<!-- diagnosis -->
<g id="node1" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1052.6255,-875.5C1052.6255,-875.5 1366.6255,-875.5 1366.6255,-875.5 1372.6255,-875.5 1378.6255,-881.5 1378.6255,-887.5 1378.6255,-887.5 1378.6255,-1024.5 1378.6255,-1024.5 1378.6255,-1030.5 1372.6255,-1036.5 1366.6255,-1036.5 1366.6255,-1036.5 1052.6255,-1036.5 1052.6255,-1036.5 1046.6255,-1036.5 1040.6255,-1030.5 1040.6255,-1024.5 1040.6255,-1024.5 1040.6255,-887.5 1040.6255,-887.5 1040.6255,-881.5 1046.6255,-875.5 1052.6255,-875.5"/>
<text text-anchor="middle" x="1082.6255" y="-952.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1124.6255,-875.5 1124.6255,-1036.5 "/>
<text text-anchor="middle" x="1135.1255" y="-952.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1145.6255,-875.5 1145.6255,-1036.5 "/>
<text text-anchor="middle" x="1251.6255" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1145.6255,-1013.5 1357.6255,-1013.5 "/>
<text text-anchor="middle" x="1251.6255" y="-998.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_status</text>
<polyline fill="none" stroke="#000000" points="1145.6255,-990.5 1357.6255,-990.5 "/>
<text text-anchor="middle" x="1251.6255" y="-975.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1145.6255,-967.5 1357.6255,-967.5 "/>
<text text-anchor="middle" x="1251.6255" y="-952.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1145.6255,-944.5 1357.6255,-944.5 "/>
<text text-anchor="middle" x="1251.6255" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1145.6255,-921.5 1357.6255,-921.5 "/>
<text text-anchor="middle" x="1251.6255" y="-906.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1145.6255,-898.5 1357.6255,-898.5 "/>
<text text-anchor="middle" x="1251.6255" y="-883.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="1357.6255,-875.5 1357.6255,-1036.5 "/>
<text text-anchor="middle" x="1368.1255" y="-952.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node2" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M508.6255,-357.5C508.6255,-357.5 822.6255,-357.5 822.6255,-357.5 828.6255,-357.5 834.6255,-363.5 834.6255,-369.5 834.6255,-369.5 834.6255,-598.5 834.6255,-598.5 834.6255,-604.5 828.6255,-610.5 822.6255,-610.5 822.6255,-610.5 508.6255,-610.5 508.6255,-610.5 502.6255,-610.5 496.6255,-604.5 496.6255,-598.5 496.6255,-598.5 496.6255,-369.5 496.6255,-369.5 496.6255,-363.5 502.6255,-357.5 508.6255,-357.5"/>
<text text-anchor="middle" x="530.6255" y="-480.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="564.6255,-357.5 564.6255,-610.5 "/>
<text text-anchor="middle" x="575.1255" y="-480.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="585.6255,-357.5 585.6255,-610.5 "/>
<text text-anchor="middle" x="699.6255" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="585.6255,-587.5 813.6255,-587.5 "/>
<text text-anchor="middle" x="699.6255" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_sample_id</text>
<polyline fill="none" stroke="#000000" points="585.6255,-564.5 813.6255,-564.5 "/>
<text text-anchor="middle" x="699.6255" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="585.6255,-541.5 813.6255,-541.5 "/>
<text text-anchor="middle" x="699.6255" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="585.6255,-518.5 813.6255,-518.5 "/>
<text text-anchor="middle" x="699.6255" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="585.6255,-495.5 813.6255,-495.5 "/>
<text text-anchor="middle" x="699.6255" y="-480.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="585.6255,-472.5 813.6255,-472.5 "/>
<text text-anchor="middle" x="699.6255" y="-457.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="585.6255,-449.5 813.6255,-449.5 "/>
<text text-anchor="middle" x="699.6255" y="-434.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="585.6255,-426.5 813.6255,-426.5 "/>
<text text-anchor="middle" x="699.6255" y="-411.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="585.6255,-403.5 813.6255,-403.5 "/>
<text text-anchor="middle" x="699.6255" y="-388.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage</text>
<polyline fill="none" stroke="#000000" points="585.6255,-380.5 813.6255,-380.5 "/>
<text text-anchor="middle" x="699.6255" y="-365.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_status</text>
<polyline fill="none" stroke="#000000" points="813.6255,-357.5 813.6255,-610.5 "/>
<text text-anchor="middle" x="824.1255" y="-480.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node5" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M425.1255,-179C425.1255,-179 656.1255,-179 656.1255,-179 662.1255,-179 668.1255,-185 668.1255,-191 668.1255,-191 668.1255,-282 668.1255,-282 668.1255,-288 662.1255,-294 656.1255,-294 656.1255,-294 425.1255,-294 425.1255,-294 419.1255,-294 413.1255,-288 413.1255,-282 413.1255,-282 413.1255,-191 413.1255,-191 413.1255,-185 419.1255,-179 425.1255,-179"/>
<text text-anchor="middle" x="461.1255" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="509.1255,-179 509.1255,-294 "/>
<text text-anchor="middle" x="519.6255" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="530.1255,-179 530.1255,-294 "/>
<text text-anchor="middle" x="588.6255" y="-278.8" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="530.1255,-271 647.1255,-271 "/>
<text text-anchor="middle" x="588.6255" y="-255.8" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="530.1255,-248 647.1255,-248 "/>
<text text-anchor="middle" x="588.6255" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="530.1255,-225 647.1255,-225 "/>
<text text-anchor="middle" x="588.6255" y="-209.8" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="530.1255,-202 647.1255,-202 "/>
<text text-anchor="middle" x="588.6255" y="-186.8" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="647.1255,-179 647.1255,-294 "/>
<text text-anchor="middle" x="657.6255" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M601.6607,-357.3498C592.234,-338.6849 582.8517,-320.108 574.3723,-303.3188"/>
<polygon fill="#000000" stroke="#000000" points="577.3923,-301.5344 569.7599,-294.1861 571.1439,-304.6902 577.3923,-301.5344"/>
<text text-anchor="middle" x="643.1255" y="-327.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- experiment -->
<g id="node6" class="node">
<title>experiment</title>
<path fill="none" stroke="#000000" d="M698.6255,-213.5C698.6255,-213.5 966.6255,-213.5 966.6255,-213.5 972.6255,-213.5 978.6255,-219.5 978.6255,-225.5 978.6255,-225.5 978.6255,-247.5 978.6255,-247.5 978.6255,-253.5 972.6255,-259.5 966.6255,-259.5 966.6255,-259.5 698.6255,-259.5 698.6255,-259.5 692.6255,-259.5 686.6255,-253.5 686.6255,-247.5 686.6255,-247.5 686.6255,-225.5 686.6255,-225.5 686.6255,-219.5 692.6255,-213.5 698.6255,-213.5"/>
<text text-anchor="middle" x="735.6255" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000">experiment</text>
<polyline fill="none" stroke="#000000" points="784.6255,-213.5 784.6255,-259.5 "/>
<text text-anchor="middle" x="795.1255" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="805.6255,-213.5 805.6255,-259.5 "/>
<text text-anchor="middle" x="881.6255" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="805.6255,-236.5 957.6255,-236.5 "/>
<text text-anchor="middle" x="881.6255" y="-221.3" font-family="Times,serif" font-size="14.00" fill="#000000">experiment_id</text>
<polyline fill="none" stroke="#000000" points="957.6255,-213.5 957.6255,-259.5 "/>
<text text-anchor="middle" x="968.1255" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;experiment -->
<g id="edge2" class="edge">
<title>sample&#45;&gt;experiment</title>
<path fill="none" stroke="#000000" d="M751.0823,-357.3498C773.5684,-324.0246 795.8652,-290.98 811.4451,-267.89"/>
<polygon fill="#000000" stroke="#000000" points="814.3818,-269.7952 817.0738,-259.5481 808.5792,-265.8799 814.3818,-269.7952"/>
<text text-anchor="middle" x="821.1255" y="-327.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_experiment</text>
</g>
<!-- study -->
<g id="node8" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M942.1255,-.5C942.1255,-.5 1187.1255,-.5 1187.1255,-.5 1193.1255,-.5 1199.1255,-6.5 1199.1255,-12.5 1199.1255,-12.5 1199.1255,-103.5 1199.1255,-103.5 1199.1255,-109.5 1193.1255,-115.5 1187.1255,-115.5 1187.1255,-115.5 942.1255,-115.5 942.1255,-115.5 936.1255,-115.5 930.1255,-109.5 930.1255,-103.5 930.1255,-103.5 930.1255,-12.5 930.1255,-12.5 930.1255,-6.5 936.1255,-.5 942.1255,-.5"/>
<text text-anchor="middle" x="958.1255" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="986.1255,-.5 986.1255,-115.5 "/>
<text text-anchor="middle" x="996.6255" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1007.1255,-.5 1007.1255,-115.5 "/>
<text text-anchor="middle" x="1092.6255" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_phs_accession</text>
<polyline fill="none" stroke="#000000" points="1007.1255,-92.5 1178.1255,-92.5 "/>
<text text-anchor="middle" x="1092.6255" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="1007.1255,-69.5 1178.1255,-69.5 "/>
<text text-anchor="middle" x="1092.6255" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="1007.1255,-46.5 1178.1255,-46.5 "/>
<text text-anchor="middle" x="1092.6255" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="1007.1255,-23.5 1178.1255,-23.5 "/>
<text text-anchor="middle" x="1092.6255" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_title</text>
<polyline fill="none" stroke="#000000" points="1178.1255,-.5 1178.1255,-115.5 "/>
<text text-anchor="middle" x="1188.6255" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge8" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M496.5433,-447.706C318.0454,-407.6915 58.4261,-343.9679 29.6255,-306 -7.71,-256.7806 -11.7072,-212.9141 29.6255,-167 88.07,-102.0772 648.8511,-73.0404 919.6633,-62.7205"/>
<polygon fill="#000000" stroke="#000000" points="920.1037,-66.2064 929.9645,-62.3316 919.8396,-59.2114 920.1037,-66.2064"/>
<text text-anchor="middle" x="60.1255" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- study_admin -->
<g id="node3" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M112.1255,-167.5C112.1255,-167.5 383.1255,-167.5 383.1255,-167.5 389.1255,-167.5 395.1255,-173.5 395.1255,-179.5 395.1255,-179.5 395.1255,-293.5 395.1255,-293.5 395.1255,-299.5 389.1255,-305.5 383.1255,-305.5 383.1255,-305.5 112.1255,-305.5 112.1255,-305.5 106.1255,-305.5 100.1255,-299.5 100.1255,-293.5 100.1255,-293.5 100.1255,-179.5 100.1255,-179.5 100.1255,-173.5 106.1255,-167.5 112.1255,-167.5"/>
<text text-anchor="middle" x="154.1255" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="208.1255,-167.5 208.1255,-305.5 "/>
<text text-anchor="middle" x="218.6255" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="229.1255,-167.5 229.1255,-305.5 "/>
<text text-anchor="middle" x="301.6255" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_access_level</text>
<polyline fill="none" stroke="#000000" points="229.1255,-282.5 374.1255,-282.5 "/>
<text text-anchor="middle" x="301.6255" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="229.1255,-259.5 374.1255,-259.5 "/>
<text text-anchor="middle" x="301.6255" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types</text>
<polyline fill="none" stroke="#000000" points="229.1255,-236.5 374.1255,-236.5 "/>
<text text-anchor="middle" x="301.6255" y="-221.3" font-family="Times,serif" font-size="14.00" fill="#000000">species</text>
<polyline fill="none" stroke="#000000" points="229.1255,-213.5 374.1255,-213.5 "/>
<text text-anchor="middle" x="301.6255" y="-198.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="229.1255,-190.5 374.1255,-190.5 "/>
<text text-anchor="middle" x="301.6255" y="-175.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_type</text>
<polyline fill="none" stroke="#000000" points="374.1255,-167.5 374.1255,-305.5 "/>
<text text-anchor="middle" x="384.6255" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge7" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M395.4923,-169.5299C398.2148,-168.6534 400.9274,-167.8089 403.6255,-167 577.2543,-114.946 784.4588,-85.8738 920.007,-71.0937"/>
<polygon fill="#000000" stroke="#000000" points="920.4801,-74.5631 930.047,-70.0108 919.7293,-67.6035 920.4801,-74.5631"/>
<text text-anchor="middle" x="558.1255" y="-137.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- imaging_detail -->
<g id="node4" class="node">
<title>imaging_detail</title>
<path fill="none" stroke="#000000" d="M1409.1255,-898.5C1409.1255,-898.5 1696.1255,-898.5 1696.1255,-898.5 1702.1255,-898.5 1708.1255,-904.5 1708.1255,-910.5 1708.1255,-910.5 1708.1255,-1001.5 1708.1255,-1001.5 1708.1255,-1007.5 1702.1255,-1013.5 1696.1255,-1013.5 1696.1255,-1013.5 1409.1255,-1013.5 1409.1255,-1013.5 1403.1255,-1013.5 1397.1255,-1007.5 1397.1255,-1001.5 1397.1255,-1001.5 1397.1255,-910.5 1397.1255,-910.5 1397.1255,-904.5 1403.1255,-898.5 1409.1255,-898.5"/>
<text text-anchor="middle" x="1458.1255" y="-952.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_detail</text>
<polyline fill="none" stroke="#000000" points="1519.1255,-898.5 1519.1255,-1013.5 "/>
<text text-anchor="middle" x="1529.6255" y="-952.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1540.1255,-898.5 1540.1255,-1013.5 "/>
<text text-anchor="middle" x="1613.6255" y="-998.3" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="1540.1255,-990.5 1687.1255,-990.5 "/>
<text text-anchor="middle" x="1613.6255" y="-975.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_detail_id</text>
<polyline fill="none" stroke="#000000" points="1540.1255,-967.5 1687.1255,-967.5 "/>
<text text-anchor="middle" x="1613.6255" y="-952.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="1540.1255,-944.5 1687.1255,-944.5 "/>
<text text-anchor="middle" x="1613.6255" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="1540.1255,-921.5 1687.1255,-921.5 "/>
<text text-anchor="middle" x="1613.6255" y="-906.3" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="1687.1255,-898.5 1687.1255,-1013.5 "/>
<text text-anchor="middle" x="1697.6255" y="-952.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file -->
<g id="node11" class="node">
<title>file</title>
<path fill="none" stroke="#000000" d="M1457.1255,-662.5C1457.1255,-662.5 1648.1255,-662.5 1648.1255,-662.5 1654.1255,-662.5 1660.1255,-668.5 1660.1255,-674.5 1660.1255,-674.5 1660.1255,-811.5 1660.1255,-811.5 1660.1255,-817.5 1654.1255,-823.5 1648.1255,-823.5 1648.1255,-823.5 1457.1255,-823.5 1457.1255,-823.5 1451.1255,-823.5 1445.1255,-817.5 1445.1255,-811.5 1445.1255,-811.5 1445.1255,-674.5 1445.1255,-674.5 1445.1255,-668.5 1451.1255,-662.5 1457.1255,-662.5"/>
<text text-anchor="middle" x="1464.6255" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">file</text>
<polyline fill="none" stroke="#000000" points="1484.1255,-662.5 1484.1255,-823.5 "/>
<text text-anchor="middle" x="1494.6255" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1505.1255,-662.5 1505.1255,-823.5 "/>
<text text-anchor="middle" x="1572.1255" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_url</text>
<polyline fill="none" stroke="#000000" points="1505.1255,-800.5 1639.1255,-800.5 "/>
<text text-anchor="middle" x="1572.1255" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1505.1255,-777.5 1639.1255,-777.5 "/>
<text text-anchor="middle" x="1572.1255" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1505.1255,-754.5 1639.1255,-754.5 "/>
<text text-anchor="middle" x="1572.1255" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1505.1255,-731.5 1639.1255,-731.5 "/>
<text text-anchor="middle" x="1572.1255" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1505.1255,-708.5 1639.1255,-708.5 "/>
<text text-anchor="middle" x="1572.1255" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1505.1255,-685.5 1639.1255,-685.5 "/>
<text text-anchor="middle" x="1572.1255" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1639.1255,-662.5 1639.1255,-823.5 "/>
<text text-anchor="middle" x="1649.6255" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_detail&#45;&gt;file -->
<g id="edge13" class="edge">
<title>imaging_detail&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M1552.6255,-898.3591C1552.6255,-878.5761 1552.6255,-855.9214 1552.6255,-834.1419"/>
<polygon fill="#000000" stroke="#000000" points="1556.1256,-833.8749 1552.6255,-823.875 1549.1256,-833.875 1556.1256,-833.8749"/>
<text text-anchor="middle" x="1574.6255" y="-845.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge5" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M649.3051,-178.9819C658.7809,-174.6969 668.3082,-170.6353 677.6255,-167 756.0391,-136.4052 846.4476,-110.4484 920.1527,-91.5486"/>
<polygon fill="#000000" stroke="#000000" points="921.1503,-94.9063 929.9767,-89.0458 919.4221,-88.1229 921.1503,-94.9063"/>
<text text-anchor="middle" x="802.1255" y="-137.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- experiment&#45;&gt;study -->
<g id="edge9" class="edge">
<title>experiment&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M862.9554,-213.1642C893.0091,-190.041 940.3973,-153.5807 981.6874,-121.8122"/>
<polygon fill="#000000" stroke="#000000" points="984.0659,-124.3984 989.8572,-115.5265 979.7973,-118.8505 984.0659,-124.3984"/>
<text text-anchor="middle" x="993.1255" y="-137.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- study_funding -->
<g id="node7" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M1009.1255,-213.5C1009.1255,-213.5 1276.1255,-213.5 1276.1255,-213.5 1282.1255,-213.5 1288.1255,-219.5 1288.1255,-225.5 1288.1255,-225.5 1288.1255,-247.5 1288.1255,-247.5 1288.1255,-253.5 1282.1255,-259.5 1276.1255,-259.5 1276.1255,-259.5 1009.1255,-259.5 1009.1255,-259.5 1003.1255,-259.5 997.1255,-253.5 997.1255,-247.5 997.1255,-247.5 997.1255,-225.5 997.1255,-225.5 997.1255,-219.5 1003.1255,-213.5 1009.1255,-213.5"/>
<text text-anchor="middle" x="1056.6255" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="1116.1255,-213.5 1116.1255,-259.5 "/>
<text text-anchor="middle" x="1126.6255" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1137.1255,-213.5 1137.1255,-259.5 "/>
<text text-anchor="middle" x="1202.1255" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="1137.1255,-236.5 1267.1255,-236.5 "/>
<text text-anchor="middle" x="1202.1255" y="-221.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_id</text>
<polyline fill="none" stroke="#000000" points="1267.1255,-213.5 1267.1255,-259.5 "/>
<text text-anchor="middle" x="1277.6255" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge3" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1132.4283,-213.1642C1122.6609,-190.8118 1107.4475,-155.9966 1093.9046,-125.0041"/>
<polygon fill="#000000" stroke="#000000" points="1096.9745,-123.2883 1089.7631,-115.5265 1090.5601,-126.0913 1096.9745,-123.2883"/>
<text text-anchor="middle" x="1175.6255" y="-137.8" font-family="Times,serif" font-size="14.00" fill="#000000">from_study_funding</text>
</g>
<!-- sequencing_detail -->
<g id="node9" class="node">
<title>sequencing_detail</title>
<path fill="none" stroke="#000000" d="M1802.6255,-369C1802.6255,-369 2190.6255,-369 2190.6255,-369 2196.6255,-369 2202.6255,-375 2202.6255,-381 2202.6255,-381 2202.6255,-587 2202.6255,-587 2202.6255,-593 2196.6255,-599 2190.6255,-599 2190.6255,-599 1802.6255,-599 1802.6255,-599 1796.6255,-599 1790.6255,-593 1790.6255,-587 1790.6255,-587 1790.6255,-381 1790.6255,-381 1790.6255,-375 1796.6255,-369 1802.6255,-369"/>
<text text-anchor="middle" x="1863.6255" y="-480.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_detail</text>
<polyline fill="none" stroke="#000000" points="1936.6255,-369 1936.6255,-599 "/>
<text text-anchor="middle" x="1947.1255" y="-480.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1957.6255,-369 1957.6255,-599 "/>
<text text-anchor="middle" x="2069.6255" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">average_read_length</text>
<polyline fill="none" stroke="#000000" points="1957.6255,-576 2181.6255,-576 "/>
<text text-anchor="middle" x="2069.6255" y="-560.8" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="1957.6255,-553 2181.6255,-553 "/>
<text text-anchor="middle" x="2069.6255" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="1957.6255,-530 2181.6255,-530 "/>
<text text-anchor="middle" x="2069.6255" y="-514.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="1957.6255,-507 2181.6255,-507 "/>
<text text-anchor="middle" x="2069.6255" y="-491.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="1957.6255,-484 2181.6255,-484 "/>
<text text-anchor="middle" x="2069.6255" y="-468.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="1957.6255,-461 2181.6255,-461 "/>
<text text-anchor="middle" x="2069.6255" y="-445.8" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="1957.6255,-438 2181.6255,-438 "/>
<text text-anchor="middle" x="2069.6255" y="-422.8" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="1957.6255,-415 2181.6255,-415 "/>
<text text-anchor="middle" x="2069.6255" y="-399.8" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="1957.6255,-392 2181.6255,-392 "/>
<text text-anchor="middle" x="2069.6255" y="-376.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_detail_id</text>
<polyline fill="none" stroke="#000000" points="2181.6255,-369 2181.6255,-599 "/>
<text text-anchor="middle" x="2192.1255" y="-480.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel -->
<g id="node10" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M1318.1255,-179C1318.1255,-179 1625.1255,-179 1625.1255,-179 1631.1255,-179 1637.1255,-185 1637.1255,-191 1637.1255,-191 1637.1255,-282 1637.1255,-282 1637.1255,-288 1631.1255,-294 1625.1255,-294 1625.1255,-294 1318.1255,-294 1318.1255,-294 1312.1255,-294 1306.1255,-288 1306.1255,-282 1306.1255,-282 1306.1255,-191 1306.1255,-191 1306.1255,-185 1312.1255,-179 1318.1255,-179"/>
<text text-anchor="middle" x="1373.1255" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="1440.1255,-179 1440.1255,-294 "/>
<text text-anchor="middle" x="1450.6255" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1461.1255,-179 1461.1255,-294 "/>
<text text-anchor="middle" x="1538.6255" y="-278.8" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="1461.1255,-271 1616.1255,-271 "/>
<text text-anchor="middle" x="1538.6255" y="-255.8" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="1461.1255,-248 1616.1255,-248 "/>
<text text-anchor="middle" x="1538.6255" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="1461.1255,-225 1616.1255,-225 "/>
<text text-anchor="middle" x="1538.6255" y="-209.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="1461.1255,-202 1616.1255,-202 "/>
<text text-anchor="middle" x="1538.6255" y="-186.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="1616.1255,-179 1616.1255,-294 "/>
<text text-anchor="middle" x="1626.6255" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge12" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1350.7945,-178.8825C1318.705,-163.9439 1283.9757,-148.0995 1251.6255,-134 1237.7902,-127.97 1223.3176,-121.8181 1208.8138,-115.7557"/>
<polygon fill="#000000" stroke="#000000" points="1209.8616,-112.4008 1199.2846,-111.7871 1207.1703,-118.8627 1209.8616,-112.4008"/>
<text text-anchor="middle" x="1362.6255" y="-137.8" font-family="Times,serif" font-size="14.00" fill="#000000">from_study_personnel</text>
</g>
<!-- file&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1444.7486,-711.5005C1295.5957,-667.9485 1024.4785,-588.7835 844.6895,-536.2859"/>
<polygon fill="#000000" stroke="#000000" points="845.44,-532.8589 834.8598,-533.4157 843.478,-539.5784 845.44,-532.8589"/>
<text text-anchor="middle" x="1235.1255" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">from_sample</text>
</g>
<!-- file&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1445.0002,-739.0527C1166.3414,-727.7325 437.9694,-690.7249 366.6255,-611 291.3452,-526.8764 314.2405,-456.9986 366.6255,-357 378.2163,-334.8741 395.92,-316.0024 415.673,-300.2166"/>
<polygon fill="#000000" stroke="#000000" points="417.8434,-302.9628 423.638,-294.093 413.5769,-297.4133 417.8434,-302.9628"/>
<text text-anchor="middle" x="427.1255" y="-480.3" font-family="Times,serif" font-size="14.00" fill="#000000">from_participant</text>
</g>
<!-- file&#45;&gt;experiment -->
<g id="edge1" class="edge">
<title>file&#45;&gt;experiment</title>
<path fill="none" stroke="#000000" d="M1610.6354,-662.4445C1613.3877,-656.3825 1615.7704,-650.2054 1617.6255,-644 1635.9144,-582.8216 1648.0675,-402.8497 1603.6255,-357 1508.0251,-258.3715 1120.6424,-340.2565 987.6255,-306 951.1607,-296.609 912.5125,-279.297 882.9298,-264.3013"/>
<polygon fill="#000000" stroke="#000000" points="884.1507,-260.9933 873.6578,-259.527 880.9461,-267.2167 884.1507,-260.9933"/>
<text text-anchor="middle" x="1686.1255" y="-480.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_experiment</text>
</g>
<!-- file&#45;&gt;study -->
<g id="edge4" class="edge">
<title>file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1660.5125,-693.0119C1692.5216,-672.4319 1723.7711,-645.2475 1741.6255,-611 1787.2403,-523.5035 1796.363,-245.5352 1736.6255,-167 1705.036,-125.4703 1397.2684,-89.3697 1209.3727,-70.9694"/>
<polygon fill="#000000" stroke="#000000" points="1209.6964,-67.4844 1199.4042,-69.9988 1209.0179,-74.4515 1209.6964,-67.4844"/>
<text text-anchor="middle" x="1807.1255" y="-327.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- file&#45;&gt;sequencing_detail -->
<g id="edge14" class="edge">
<title>file&#45;&gt;sequencing_detail</title>
<path fill="none" stroke="#000000" d="M1660.3104,-700.9103C1697.9628,-684.7674 1739.9644,-665.1113 1776.6255,-644 1797.2187,-632.1414 1818.2158,-618.7632 1838.6625,-604.9209"/>
<polygon fill="#000000" stroke="#000000" points="1840.7935,-607.704 1847.08,-599.1758 1836.8473,-601.9223 1840.7935,-607.704"/>
<text text-anchor="middle" x="1816.6255" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- clinical_measure -->
<g id="node12" class="node">
<title>clinical_measure</title>
<path fill="none" stroke="#000000" d="M1202.1255,-461C1202.1255,-461 1583.1255,-461 1583.1255,-461 1589.1255,-461 1595.1255,-467 1595.1255,-473 1595.1255,-473 1595.1255,-495 1595.1255,-495 1595.1255,-501 1589.1255,-507 1583.1255,-507 1583.1255,-507 1202.1255,-507 1202.1255,-507 1196.1255,-507 1190.1255,-501 1190.1255,-495 1190.1255,-495 1190.1255,-473 1190.1255,-473 1190.1255,-467 1196.1255,-461 1202.1255,-461"/>
<text text-anchor="middle" x="1258.6255" y="-480.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure</text>
<polyline fill="none" stroke="#000000" points="1327.1255,-461 1327.1255,-507 "/>
<text text-anchor="middle" x="1337.6255" y="-480.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1348.1255,-461 1348.1255,-507 "/>
<text text-anchor="middle" x="1461.1255" y="-491.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_description</text>
<polyline fill="none" stroke="#000000" points="1348.1255,-484 1574.1255,-484 "/>
<text text-anchor="middle" x="1461.1255" y="-468.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_id</text>
<polyline fill="none" stroke="#000000" points="1574.1255,-461 1574.1255,-507 "/>
<text text-anchor="middle" x="1584.6255" y="-480.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file&#45;&gt;clinical_measure -->
<g id="edge17" class="edge">
<title>file&#45;&gt;clinical_measure</title>
<path fill="none" stroke="#000000" d="M1487.958,-662.284C1483.6581,-656.1858 1479.5017,-650.0503 1475.6255,-644 1448.5073,-601.6722 1422.7401,-549.4636 1407.3068,-516.4422"/>
<polygon fill="#000000" stroke="#000000" points="1410.4279,-514.8531 1403.0471,-507.2522 1404.077,-517.7968 1410.4279,-514.8531"/>
<text text-anchor="middle" x="1546.6255" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure</text>
</g>
<!-- clinical_measure&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>clinical_measure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1332.9215,-460.9582C1237.8946,-425.3233 1045.6857,-357.4686 876.6255,-324 789.5106,-306.754 762.9765,-330.5281 677.6255,-306 669.6112,-303.6969 661.5111,-300.9196 653.4655,-297.8185"/>
<polygon fill="#000000" stroke="#000000" points="654.6382,-294.5178 644.0542,-294.0382 652.029,-301.0134 654.6382,-294.5178"/>
<text text-anchor="middle" x="995.1255" y="-327.8" font-family="Times,serif" font-size="14.00" fill="#000000">from_participant</text>
</g>
<!-- clinical_measure&#45;&gt;study -->
<g id="edge6" class="edge">
<title>clinical_measure&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1434.8279,-460.8666C1500.8949,-423.6646 1623.6038,-350.2452 1646.6255,-306 1675.1406,-251.1969 1686.0839,-214.5345 1646.6255,-167 1592.0947,-101.3083 1363.3093,-74.9751 1209.3531,-64.5815"/>
<polygon fill="#000000" stroke="#000000" points="1209.5319,-61.0858 1199.3232,-63.9197 1209.071,-68.0706 1209.5319,-61.0858"/>
<text text-anchor="middle" x="1702.1255" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- alias -->
<g id="node13" class="node">
<title>alias</title>
<path fill="none" stroke="#000000" d="M1738.1255,-910C1738.1255,-910 1943.1255,-910 1943.1255,-910 1949.1255,-910 1955.1255,-916 1955.1255,-922 1955.1255,-922 1955.1255,-990 1955.1255,-990 1955.1255,-996 1949.1255,-1002 1943.1255,-1002 1943.1255,-1002 1738.1255,-1002 1738.1255,-1002 1732.1255,-1002 1726.1255,-996 1726.1255,-990 1726.1255,-990 1726.1255,-922 1726.1255,-922 1726.1255,-916 1732.1255,-910 1738.1255,-910"/>
<text text-anchor="middle" x="1751.1255" y="-952.3" font-family="Times,serif" font-size="14.00" fill="#000000">alias</text>
<polyline fill="none" stroke="#000000" points="1776.1255,-910 1776.1255,-1002 "/>
<text text-anchor="middle" x="1786.6255" y="-952.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1797.1255,-910 1797.1255,-1002 "/>
<text text-anchor="middle" x="1865.6255" y="-986.8" font-family="Times,serif" font-size="14.00" fill="#000000">cds_id</text>
<polyline fill="none" stroke="#000000" points="1797.1255,-979 1934.1255,-979 "/>
<text text-anchor="middle" x="1865.6255" y="-963.8" font-family="Times,serif" font-size="14.00" fill="#000000">cds_node</text>
<polyline fill="none" stroke="#000000" points="1797.1255,-956 1934.1255,-956 "/>
<text text-anchor="middle" x="1865.6255" y="-940.8" font-family="Times,serif" font-size="14.00" fill="#000000">repository_id</text>
<polyline fill="none" stroke="#000000" points="1797.1255,-933 1934.1255,-933 "/>
<text text-anchor="middle" x="1865.6255" y="-917.8" font-family="Times,serif" font-size="14.00" fill="#000000">repository_name</text>
<polyline fill="none" stroke="#000000" points="1934.1255,-910 1934.1255,-1002 "/>
<text text-anchor="middle" x="1944.6255" y="-952.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
</g>
</svg>
</div>
