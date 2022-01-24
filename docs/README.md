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
<svg width="1838pt" height="1261pt"
 viewBox="0.00 0.00 1837.61 1261.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1257)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1257 1833.6083,-1257 1833.6083,4 -4,4"/>
<!-- genomic_detail -->
<g id="node1" class="node">
<title>genomic_detail</title>
<path fill="none" stroke="#000000" d="M104.6083,-1022.5C104.6083,-1022.5 471.6083,-1022.5 471.6083,-1022.5 477.6083,-1022.5 483.6083,-1028.5 483.6083,-1034.5 483.6083,-1034.5 483.6083,-1240.5 483.6083,-1240.5 483.6083,-1246.5 477.6083,-1252.5 471.6083,-1252.5 471.6083,-1252.5 104.6083,-1252.5 104.6083,-1252.5 98.6083,-1252.5 92.6083,-1246.5 92.6083,-1240.5 92.6083,-1240.5 92.6083,-1034.5 92.6083,-1034.5 92.6083,-1028.5 98.6083,-1022.5 104.6083,-1022.5"/>
<text text-anchor="middle" x="155.1083" y="-1133.8" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_detail</text>
<polyline fill="none" stroke="#000000" points="217.6083,-1022.5 217.6083,-1252.5 "/>
<text text-anchor="middle" x="228.1083" y="-1133.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="238.6083,-1022.5 238.6083,-1252.5 "/>
<text text-anchor="middle" x="350.6083" y="-1237.3" font-family="Times,serif" font-size="14.00" fill="#000000">average_read_length</text>
<polyline fill="none" stroke="#000000" points="238.6083,-1229.5 462.6083,-1229.5 "/>
<text text-anchor="middle" x="350.6083" y="-1214.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="238.6083,-1206.5 462.6083,-1206.5 "/>
<text text-anchor="middle" x="350.6083" y="-1191.3" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_detail_id</text>
<polyline fill="none" stroke="#000000" points="238.6083,-1183.5 462.6083,-1183.5 "/>
<text text-anchor="middle" x="350.6083" y="-1168.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="238.6083,-1160.5 462.6083,-1160.5 "/>
<text text-anchor="middle" x="350.6083" y="-1145.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="238.6083,-1137.5 462.6083,-1137.5 "/>
<text text-anchor="middle" x="350.6083" y="-1122.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="238.6083,-1114.5 462.6083,-1114.5 "/>
<text text-anchor="middle" x="350.6083" y="-1099.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="238.6083,-1091.5 462.6083,-1091.5 "/>
<text text-anchor="middle" x="350.6083" y="-1076.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="238.6083,-1068.5 462.6083,-1068.5 "/>
<text text-anchor="middle" x="350.6083" y="-1053.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="238.6083,-1045.5 462.6083,-1045.5 "/>
<text text-anchor="middle" x="350.6083" y="-1030.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="462.6083,-1022.5 462.6083,-1252.5 "/>
<text text-anchor="middle" x="473.1083" y="-1133.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file -->
<g id="node7" class="node">
<title>file</title>
<path fill="none" stroke="#000000" d="M376.6083,-786.5C376.6083,-786.5 567.6083,-786.5 567.6083,-786.5 573.6083,-786.5 579.6083,-792.5 579.6083,-798.5 579.6083,-798.5 579.6083,-958.5 579.6083,-958.5 579.6083,-964.5 573.6083,-970.5 567.6083,-970.5 567.6083,-970.5 376.6083,-970.5 376.6083,-970.5 370.6083,-970.5 364.6083,-964.5 364.6083,-958.5 364.6083,-958.5 364.6083,-798.5 364.6083,-798.5 364.6083,-792.5 370.6083,-786.5 376.6083,-786.5"/>
<text text-anchor="middle" x="384.1083" y="-874.8" font-family="Times,serif" font-size="14.00" fill="#000000">file</text>
<polyline fill="none" stroke="#000000" points="403.6083,-786.5 403.6083,-970.5 "/>
<text text-anchor="middle" x="414.1083" y="-874.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="424.6083,-786.5 424.6083,-970.5 "/>
<text text-anchor="middle" x="491.6083" y="-955.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_url</text>
<polyline fill="none" stroke="#000000" points="424.6083,-947.5 558.6083,-947.5 "/>
<text text-anchor="middle" x="491.6083" y="-932.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="424.6083,-924.5 558.6083,-924.5 "/>
<text text-anchor="middle" x="491.6083" y="-909.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="424.6083,-901.5 558.6083,-901.5 "/>
<text text-anchor="middle" x="491.6083" y="-886.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_id</text>
<polyline fill="none" stroke="#000000" points="424.6083,-878.5 558.6083,-878.5 "/>
<text text-anchor="middle" x="491.6083" y="-863.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="424.6083,-855.5 558.6083,-855.5 "/>
<text text-anchor="middle" x="491.6083" y="-840.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="424.6083,-832.5 558.6083,-832.5 "/>
<text text-anchor="middle" x="491.6083" y="-817.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="424.6083,-809.5 558.6083,-809.5 "/>
<text text-anchor="middle" x="491.6083" y="-794.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="558.6083,-786.5 558.6083,-970.5 "/>
<text text-anchor="middle" x="569.1083" y="-874.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genomic_detail&#45;&gt;file -->
<g id="edge1" class="edge">
<title>genomic_detail&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M369.8849,-1022.3905C380.1548,-1007.9345 390.5967,-993.2364 400.6903,-979.0286"/>
<polygon fill="#000000" stroke="#000000" points="403.6508,-980.9047 406.589,-970.7255 397.9442,-976.8506 403.6508,-980.9047"/>
<text text-anchor="middle" x="414.1083" y="-992.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- study_subject -->
<g id="node2" class="node">
<title>study_subject</title>
<path fill="none" stroke="#000000" d="M141.6083,-190.5C141.6083,-190.5 424.6083,-190.5 424.6083,-190.5 430.6083,-190.5 436.6083,-196.5 436.6083,-202.5 436.6083,-202.5 436.6083,-339.5 436.6083,-339.5 436.6083,-345.5 430.6083,-351.5 424.6083,-351.5 424.6083,-351.5 141.6083,-351.5 141.6083,-351.5 135.6083,-351.5 129.6083,-345.5 129.6083,-339.5 129.6083,-339.5 129.6083,-202.5 129.6083,-202.5 129.6083,-196.5 135.6083,-190.5 141.6083,-190.5"/>
<text text-anchor="middle" x="187.6083" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_subject</text>
<polyline fill="none" stroke="#000000" points="245.6083,-190.5 245.6083,-351.5 "/>
<text text-anchor="middle" x="256.1083" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="266.6083,-190.5 266.6083,-351.5 "/>
<text text-anchor="middle" x="341.1083" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_enrollment</text>
<polyline fill="none" stroke="#000000" points="266.6083,-328.5 415.6083,-328.5 "/>
<text text-anchor="middle" x="341.1083" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_unit</text>
<polyline fill="none" stroke="#000000" points="266.6083,-305.5 415.6083,-305.5 "/>
<text text-anchor="middle" x="341.1083" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="266.6083,-282.5 415.6083,-282.5 "/>
<text text-anchor="middle" x="341.1083" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="266.6083,-259.5 415.6083,-259.5 "/>
<text text-anchor="middle" x="341.1083" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="266.6083,-236.5 415.6083,-236.5 "/>
<text text-anchor="middle" x="341.1083" y="-221.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_subject_id</text>
<polyline fill="none" stroke="#000000" points="266.6083,-213.5 415.6083,-213.5 "/>
<text text-anchor="middle" x="341.1083" y="-198.3" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="415.6083,-190.5 415.6083,-351.5 "/>
<text text-anchor="middle" x="426.1083" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node3" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M660.6083,-.5C660.6083,-.5 905.6083,-.5 905.6083,-.5 911.6083,-.5 917.6083,-6.5 917.6083,-12.5 917.6083,-12.5 917.6083,-126.5 917.6083,-126.5 917.6083,-132.5 911.6083,-138.5 905.6083,-138.5 905.6083,-138.5 660.6083,-138.5 660.6083,-138.5 654.6083,-138.5 648.6083,-132.5 648.6083,-126.5 648.6083,-126.5 648.6083,-12.5 648.6083,-12.5 648.6083,-6.5 654.6083,-.5 660.6083,-.5"/>
<text text-anchor="middle" x="676.6083" y="-65.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="704.6083,-.5 704.6083,-138.5 "/>
<text text-anchor="middle" x="715.1083" y="-65.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="725.6083,-.5 725.6083,-138.5 "/>
<text text-anchor="middle" x="811.1083" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_phs_accession</text>
<polyline fill="none" stroke="#000000" points="725.6083,-115.5 896.6083,-115.5 "/>
<text text-anchor="middle" x="811.1083" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="725.6083,-92.5 896.6083,-92.5 "/>
<text text-anchor="middle" x="811.1083" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="725.6083,-69.5 896.6083,-69.5 "/>
<text text-anchor="middle" x="811.1083" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="725.6083,-46.5 896.6083,-46.5 "/>
<text text-anchor="middle" x="811.1083" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="725.6083,-23.5 896.6083,-23.5 "/>
<text text-anchor="middle" x="811.1083" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_title</text>
<polyline fill="none" stroke="#000000" points="896.6083,-.5 896.6083,-138.5 "/>
<text text-anchor="middle" x="907.1083" y="-65.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_subject&#45;&gt;study -->
<g id="edge11" class="edge">
<title>study_subject&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M436.8848,-193.9818C439.9783,-192.6279 443.0552,-191.2991 446.1083,-190 508.384,-163.5016 578.6737,-137.7378 638.8839,-116.8805"/>
<polygon fill="#000000" stroke="#000000" points="640.1473,-120.1472 648.458,-113.5759 637.8632,-113.5303 640.1473,-120.1472"/>
<text text-anchor="middle" x="558.6083" y="-160.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- alias -->
<g id="node4" class="node">
<title>alias</title>
<path fill="none" stroke="#000000" d="M842.6083,-1091.5C842.6083,-1091.5 1047.6083,-1091.5 1047.6083,-1091.5 1053.6083,-1091.5 1059.6083,-1097.5 1059.6083,-1103.5 1059.6083,-1103.5 1059.6083,-1171.5 1059.6083,-1171.5 1059.6083,-1177.5 1053.6083,-1183.5 1047.6083,-1183.5 1047.6083,-1183.5 842.6083,-1183.5 842.6083,-1183.5 836.6083,-1183.5 830.6083,-1177.5 830.6083,-1171.5 830.6083,-1171.5 830.6083,-1103.5 830.6083,-1103.5 830.6083,-1097.5 836.6083,-1091.5 842.6083,-1091.5"/>
<text text-anchor="middle" x="855.6083" y="-1133.8" font-family="Times,serif" font-size="14.00" fill="#000000">alias</text>
<polyline fill="none" stroke="#000000" points="880.6083,-1091.5 880.6083,-1183.5 "/>
<text text-anchor="middle" x="891.1083" y="-1133.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="901.6083,-1091.5 901.6083,-1183.5 "/>
<text text-anchor="middle" x="970.1083" y="-1168.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_id</text>
<polyline fill="none" stroke="#000000" points="901.6083,-1160.5 1038.6083,-1160.5 "/>
<text text-anchor="middle" x="970.1083" y="-1145.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_node</text>
<polyline fill="none" stroke="#000000" points="901.6083,-1137.5 1038.6083,-1137.5 "/>
<text text-anchor="middle" x="970.1083" y="-1122.3" font-family="Times,serif" font-size="14.00" fill="#000000">repository_id</text>
<polyline fill="none" stroke="#000000" points="901.6083,-1114.5 1038.6083,-1114.5 "/>
<text text-anchor="middle" x="970.1083" y="-1099.3" font-family="Times,serif" font-size="14.00" fill="#000000">repository_name</text>
<polyline fill="none" stroke="#000000" points="1038.6083,-1091.5 1038.6083,-1183.5 "/>
<text text-anchor="middle" x="1049.1083" y="-1133.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node5" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M305.1083,-481.5C305.1083,-481.5 639.1083,-481.5 639.1083,-481.5 645.1083,-481.5 651.1083,-487.5 651.1083,-493.5 651.1083,-493.5 651.1083,-722.5 651.1083,-722.5 651.1083,-728.5 645.1083,-734.5 639.1083,-734.5 639.1083,-734.5 305.1083,-734.5 305.1083,-734.5 299.1083,-734.5 293.1083,-728.5 293.1083,-722.5 293.1083,-722.5 293.1083,-493.5 293.1083,-493.5 293.1083,-487.5 299.1083,-481.5 305.1083,-481.5"/>
<text text-anchor="middle" x="327.1083" y="-604.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="361.1083,-481.5 361.1083,-734.5 "/>
<text text-anchor="middle" x="371.6083" y="-604.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="382.1083,-481.5 382.1083,-734.5 "/>
<text text-anchor="middle" x="506.1083" y="-719.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="382.1083,-711.5 630.1083,-711.5 "/>
<text text-anchor="middle" x="506.1083" y="-696.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_sample_id</text>
<polyline fill="none" stroke="#000000" points="382.1083,-688.5 630.1083,-688.5 "/>
<text text-anchor="middle" x="506.1083" y="-673.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="382.1083,-665.5 630.1083,-665.5 "/>
<text text-anchor="middle" x="506.1083" y="-650.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="382.1083,-642.5 630.1083,-642.5 "/>
<text text-anchor="middle" x="506.1083" y="-627.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="382.1083,-619.5 630.1083,-619.5 "/>
<text text-anchor="middle" x="506.1083" y="-604.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_subject_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="382.1083,-596.5 630.1083,-596.5 "/>
<text text-anchor="middle" x="506.1083" y="-581.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="382.1083,-573.5 630.1083,-573.5 "/>
<text text-anchor="middle" x="506.1083" y="-558.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="382.1083,-550.5 630.1083,-550.5 "/>
<text text-anchor="middle" x="506.1083" y="-535.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="382.1083,-527.5 630.1083,-527.5 "/>
<text text-anchor="middle" x="506.1083" y="-512.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage</text>
<polyline fill="none" stroke="#000000" points="382.1083,-504.5 630.1083,-504.5 "/>
<text text-anchor="middle" x="506.1083" y="-489.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_status</text>
<polyline fill="none" stroke="#000000" points="630.1083,-481.5 630.1083,-734.5 "/>
<text text-anchor="middle" x="640.6083" y="-604.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;study_subject -->
<g id="edge14" class="edge">
<title>sample&#45;&gt;study_subject</title>
<path fill="none" stroke="#000000" d="M400.9248,-481.075C378.4501,-441.0009 354.0985,-397.5805 333.3998,-360.6733"/>
<polygon fill="#000000" stroke="#000000" points="336.4393,-358.9375 328.495,-351.9275 330.3339,-362.3616 336.4393,-358.9375"/>
<text text-anchor="middle" x="449.6083" y="-412.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_subject</text>
</g>
<!-- experiment -->
<g id="node6" class="node">
<title>experiment</title>
<path fill="none" stroke="#000000" d="M467.1083,-248C467.1083,-248 735.1083,-248 735.1083,-248 741.1083,-248 747.1083,-254 747.1083,-260 747.1083,-260 747.1083,-282 747.1083,-282 747.1083,-288 741.1083,-294 735.1083,-294 735.1083,-294 467.1083,-294 467.1083,-294 461.1083,-294 455.1083,-288 455.1083,-282 455.1083,-282 455.1083,-260 455.1083,-260 455.1083,-254 461.1083,-248 467.1083,-248"/>
<text text-anchor="middle" x="504.1083" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">experiment</text>
<polyline fill="none" stroke="#000000" points="553.1083,-248 553.1083,-294 "/>
<text text-anchor="middle" x="563.6083" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="574.1083,-248 574.1083,-294 "/>
<text text-anchor="middle" x="650.1083" y="-278.8" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="574.1083,-271 726.1083,-271 "/>
<text text-anchor="middle" x="650.1083" y="-255.8" font-family="Times,serif" font-size="14.00" fill="#000000">experiment_id</text>
<polyline fill="none" stroke="#000000" points="726.1083,-248 726.1083,-294 "/>
<text text-anchor="middle" x="736.6083" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;experiment -->
<g id="edge4" class="edge">
<title>sample&#45;&gt;experiment</title>
<path fill="none" stroke="#000000" d="M520.6939,-481.075C545.1727,-417.1263 572.9136,-344.656 588.5798,-303.7296"/>
<polygon fill="#000000" stroke="#000000" points="591.8938,-304.8623 592.2001,-294.2719 585.3564,-302.3598 591.8938,-304.8623"/>
<text text-anchor="middle" x="614.6083" y="-412.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_experiment</text>
</g>
<!-- experiment&#45;&gt;study -->
<g id="edge10" class="edge">
<title>experiment&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M621.986,-247.8854C644.3015,-223.179 680.8918,-182.6683 713.5675,-146.4916"/>
<polygon fill="#000000" stroke="#000000" points="716.3687,-148.6119 720.4742,-138.8449 711.174,-143.9199 716.3687,-148.6119"/>
<text text-anchor="middle" x="732.6083" y="-160.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- file&#45;&gt;study_subject -->
<g id="edge6" class="edge">
<title>file&#45;&gt;study_subject</title>
<path fill="none" stroke="#000000" d="M364.2101,-862.8849C287.9795,-845.6071 191.0049,-809.5821 142.1083,-735 80.2135,-640.5916 109.2172,-588.9911 142.1083,-481 155.2563,-437.8311 180.5685,-395.4815 206.1604,-360.2494"/>
<polygon fill="#000000" stroke="#000000" points="209.1893,-362.0396 212.3148,-351.9163 203.5585,-357.881 209.1893,-362.0396"/>
<text text-anchor="middle" x="213.1083" y="-604.3" font-family="Times,serif" font-size="14.00" fill="#000000">from_study_subject</text>
</g>
<!-- file&#45;&gt;study -->
<g id="edge13" class="edge">
<title>file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M364.5388,-852.4894C265.5334,-825.9504 129.937,-782.0778 102.1083,-735 -21.2173,-526.3702 -52.3094,-360.3166 120.1083,-190 191.6141,-119.3656 465.8181,-89.2645 638.4043,-77.1062"/>
<polygon fill="#000000" stroke="#000000" points="638.8605,-80.5831 648.5949,-76.4008 638.377,-73.5998 638.8605,-80.5831"/>
<text text-anchor="middle" x="39.6083" y="-412.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- file&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M472.1083,-786.1658C472.1083,-772.8648 472.1083,-758.946 472.1083,-745.0023"/>
<polygon fill="#000000" stroke="#000000" points="475.6084,-744.8532 472.1083,-734.8533 468.6084,-744.8533 475.6084,-744.8532"/>
<text text-anchor="middle" x="518.6083" y="-756.8" font-family="Times,serif" font-size="14.00" fill="#000000">from_sample</text>
</g>
<!-- file&#45;&gt;experiment -->
<g id="edge5" class="edge">
<title>file&#45;&gt;experiment</title>
<path fill="none" stroke="#000000" d="M579.8776,-821.0723C611.3365,-798.6328 642.0774,-769.8214 660.1083,-735 678.7636,-698.9727 682.2661,-408.7063 670.1083,-370 662.2141,-344.8674 645.428,-320.5395 630.3897,-302.2893"/>
<polygon fill="#000000" stroke="#000000" points="632.7848,-299.703 623.6413,-294.3507 627.4514,-304.2367 632.7848,-299.703"/>
<text text-anchor="middle" x="728.6083" y="-604.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_experiment</text>
</g>
<!-- clinical_measure -->
<g id="node11" class="node">
<title>clinical_measure</title>
<path fill="none" stroke="#000000" d="M714.6083,-370.5C714.6083,-370.5 1095.6083,-370.5 1095.6083,-370.5 1101.6083,-370.5 1107.6083,-376.5 1107.6083,-382.5 1107.6083,-382.5 1107.6083,-450.5 1107.6083,-450.5 1107.6083,-456.5 1101.6083,-462.5 1095.6083,-462.5 1095.6083,-462.5 714.6083,-462.5 714.6083,-462.5 708.6083,-462.5 702.6083,-456.5 702.6083,-450.5 702.6083,-450.5 702.6083,-382.5 702.6083,-382.5 702.6083,-376.5 708.6083,-370.5 714.6083,-370.5"/>
<text text-anchor="middle" x="771.1083" y="-412.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure</text>
<polyline fill="none" stroke="#000000" points="839.6083,-370.5 839.6083,-462.5 "/>
<text text-anchor="middle" x="850.1083" y="-412.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="860.6083,-370.5 860.6083,-462.5 "/>
<text text-anchor="middle" x="973.6083" y="-447.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_measure</text>
<polyline fill="none" stroke="#000000" points="860.6083,-439.5 1086.6083,-439.5 "/>
<text text-anchor="middle" x="973.6083" y="-424.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_description</text>
<polyline fill="none" stroke="#000000" points="860.6083,-416.5 1086.6083,-416.5 "/>
<text text-anchor="middle" x="973.6083" y="-401.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_id</text>
<polyline fill="none" stroke="#000000" points="860.6083,-393.5 1086.6083,-393.5 "/>
<text text-anchor="middle" x="973.6083" y="-378.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_measure</text>
<polyline fill="none" stroke="#000000" points="1086.6083,-370.5 1086.6083,-462.5 "/>
<text text-anchor="middle" x="1097.1083" y="-412.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file&#45;&gt;clinical_measure -->
<g id="edge3" class="edge">
<title>file&#45;&gt;clinical_measure</title>
<path fill="none" stroke="#000000" d="M579.7496,-854.2022C649.451,-833.3465 737.4607,-796.6107 794.1083,-735 862.2478,-660.8906 888.9282,-542.6724 899.1035,-473.0152"/>
<polygon fill="#000000" stroke="#000000" points="902.6294,-473.0716 900.5434,-462.6842 895.6964,-472.1053 902.6294,-473.0716"/>
<text text-anchor="middle" x="845.1083" y="-756.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure</text>
</g>
<!-- study_personnel -->
<g id="node8" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M874.6083,-213.5C874.6083,-213.5 1185.6083,-213.5 1185.6083,-213.5 1191.6083,-213.5 1197.6083,-219.5 1197.6083,-225.5 1197.6083,-225.5 1197.6083,-316.5 1197.6083,-316.5 1197.6083,-322.5 1191.6083,-328.5 1185.6083,-328.5 1185.6083,-328.5 874.6083,-328.5 874.6083,-328.5 868.6083,-328.5 862.6083,-322.5 862.6083,-316.5 862.6083,-316.5 862.6083,-225.5 862.6083,-225.5 862.6083,-219.5 868.6083,-213.5 874.6083,-213.5"/>
<text text-anchor="middle" x="929.6083" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="996.6083,-213.5 996.6083,-328.5 "/>
<text text-anchor="middle" x="1007.1083" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1017.6083,-213.5 1017.6083,-328.5 "/>
<text text-anchor="middle" x="1097.1083" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="1017.6083,-305.5 1176.6083,-305.5 "/>
<text text-anchor="middle" x="1097.1083" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="1017.6083,-282.5 1176.6083,-282.5 "/>
<text text-anchor="middle" x="1097.1083" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="1017.6083,-259.5 1176.6083,-259.5 "/>
<text text-anchor="middle" x="1097.1083" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="1017.6083,-236.5 1176.6083,-236.5 "/>
<text text-anchor="middle" x="1097.1083" y="-221.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_ID</text>
<polyline fill="none" stroke="#000000" points="1176.6083,-213.5 1176.6083,-328.5 "/>
<text text-anchor="middle" x="1187.1083" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge12" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M959.328,-213.2582C933.3786,-192.0889 903.6063,-167.801 876.0095,-145.2879"/>
<polygon fill="#000000" stroke="#000000" points="877.8676,-142.2867 867.9065,-138.6775 873.4427,-147.7108 877.8676,-142.2867"/>
<text text-anchor="middle" x="936.6083" y="-160.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- study_funding -->
<g id="node9" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M1227.6083,-236.5C1227.6083,-236.5 1504.6083,-236.5 1504.6083,-236.5 1510.6083,-236.5 1516.6083,-242.5 1516.6083,-248.5 1516.6083,-248.5 1516.6083,-293.5 1516.6083,-293.5 1516.6083,-299.5 1510.6083,-305.5 1504.6083,-305.5 1504.6083,-305.5 1227.6083,-305.5 1227.6083,-305.5 1221.6083,-305.5 1215.6083,-299.5 1215.6083,-293.5 1215.6083,-293.5 1215.6083,-248.5 1215.6083,-248.5 1215.6083,-242.5 1221.6083,-236.5 1227.6083,-236.5"/>
<text text-anchor="middle" x="1275.1083" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="1334.6083,-236.5 1334.6083,-305.5 "/>
<text text-anchor="middle" x="1345.1083" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1355.6083,-236.5 1355.6083,-305.5 "/>
<text text-anchor="middle" x="1425.6083" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="1355.6083,-282.5 1495.6083,-282.5 "/>
<text text-anchor="middle" x="1425.6083" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_id</text>
<polyline fill="none" stroke="#000000" points="1355.6083,-259.5 1495.6083,-259.5 "/>
<text text-anchor="middle" x="1425.6083" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding_id</text>
<polyline fill="none" stroke="#000000" points="1495.6083,-236.5 1495.6083,-305.5 "/>
<text text-anchor="middle" x="1506.1083" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1305.0979,-236.4C1276.0341,-220.8383 1240.416,-203.0736 1207.1083,-190 1116.3164,-154.3634 1010.8319,-124.3429 927.7892,-103.1796"/>
<polygon fill="#000000" stroke="#000000" points="928.5865,-99.7711 918.0331,-100.7077 926.8671,-106.5567 928.5865,-99.7711"/>
<text text-anchor="middle" x="1180.6083" y="-160.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- study_admin -->
<g id="node10" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M1546.6083,-213.5C1546.6083,-213.5 1817.6083,-213.5 1817.6083,-213.5 1823.6083,-213.5 1829.6083,-219.5 1829.6083,-225.5 1829.6083,-225.5 1829.6083,-316.5 1829.6083,-316.5 1829.6083,-322.5 1823.6083,-328.5 1817.6083,-328.5 1817.6083,-328.5 1546.6083,-328.5 1546.6083,-328.5 1540.6083,-328.5 1534.6083,-322.5 1534.6083,-316.5 1534.6083,-316.5 1534.6083,-225.5 1534.6083,-225.5 1534.6083,-219.5 1540.6083,-213.5 1546.6083,-213.5"/>
<text text-anchor="middle" x="1588.6083" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="1642.6083,-213.5 1642.6083,-328.5 "/>
<text text-anchor="middle" x="1653.1083" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1663.6083,-213.5 1663.6083,-328.5 "/>
<text text-anchor="middle" x="1736.1083" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_access_level</text>
<polyline fill="none" stroke="#000000" points="1663.6083,-305.5 1808.6083,-305.5 "/>
<text text-anchor="middle" x="1736.1083" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="1663.6083,-282.5 1808.6083,-282.5 "/>
<text text-anchor="middle" x="1736.1083" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types</text>
<polyline fill="none" stroke="#000000" points="1663.6083,-259.5 1808.6083,-259.5 "/>
<text text-anchor="middle" x="1736.1083" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">species</text>
<polyline fill="none" stroke="#000000" points="1663.6083,-236.5 1808.6083,-236.5 "/>
<text text-anchor="middle" x="1736.1083" y="-221.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_type</text>
<polyline fill="none" stroke="#000000" points="1808.6083,-213.5 1808.6083,-328.5 "/>
<text text-anchor="middle" x="1819.1083" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge9" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1582.6175,-213.4293C1564.2629,-204.5284 1544.9381,-196.2368 1526.1083,-190 1324.809,-123.3257 1080.1725,-92.7612 928.0203,-79.3178"/>
<polygon fill="#000000" stroke="#000000" points="927.9462,-75.7982 917.6804,-78.418 927.3393,-82.7719 927.9462,-75.7982"/>
<text text-anchor="middle" x="1477.6083" y="-160.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- clinical_measure&#45;&gt;study -->
<g id="edge7" class="edge">
<title>clinical_measure&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M807.8714,-370.3306C802.1946,-364.8228 797.1584,-358.7285 793.1083,-352 773.2675,-319.038 773.9789,-220.4847 777.5102,-149.0481"/>
<polygon fill="#000000" stroke="#000000" points="781.0234,-148.885 778.0496,-138.7161 774.0329,-148.52 781.0234,-148.885"/>
<text text-anchor="middle" x="823.6083" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- imaging_detail -->
<g id="node12" class="node">
<title>imaging_detail</title>
<path fill="none" stroke="#000000" d="M513.6083,-1080C513.6083,-1080 800.6083,-1080 800.6083,-1080 806.6083,-1080 812.6083,-1086 812.6083,-1092 812.6083,-1092 812.6083,-1183 812.6083,-1183 812.6083,-1189 806.6083,-1195 800.6083,-1195 800.6083,-1195 513.6083,-1195 513.6083,-1195 507.6083,-1195 501.6083,-1189 501.6083,-1183 501.6083,-1183 501.6083,-1092 501.6083,-1092 501.6083,-1086 507.6083,-1080 513.6083,-1080"/>
<text text-anchor="middle" x="562.6083" y="-1133.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_detail</text>
<polyline fill="none" stroke="#000000" points="623.6083,-1080 623.6083,-1195 "/>
<text text-anchor="middle" x="634.1083" y="-1133.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="644.6083,-1080 644.6083,-1195 "/>
<text text-anchor="middle" x="718.1083" y="-1179.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="644.6083,-1172 791.6083,-1172 "/>
<text text-anchor="middle" x="718.1083" y="-1156.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_detail_id</text>
<polyline fill="none" stroke="#000000" points="644.6083,-1149 791.6083,-1149 "/>
<text text-anchor="middle" x="718.1083" y="-1133.8" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="644.6083,-1126 791.6083,-1126 "/>
<text text-anchor="middle" x="718.1083" y="-1110.8" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="644.6083,-1103 791.6083,-1103 "/>
<text text-anchor="middle" x="718.1083" y="-1087.8" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="791.6083,-1080 791.6083,-1195 "/>
<text text-anchor="middle" x="802.1083" y="-1133.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_detail&#45;&gt;file -->
<g id="edge2" class="edge">
<title>imaging_detail&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M615.821,-1079.6977C594.6245,-1050.0227 568.1891,-1013.0132 543.7916,-978.8566"/>
<polygon fill="#000000" stroke="#000000" points="546.6273,-976.8049 537.9668,-970.7019 540.9312,-980.8736 546.6273,-976.8049"/>
<text text-anchor="middle" x="581.1083" y="-992.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
</g>
</svg>
</div>
