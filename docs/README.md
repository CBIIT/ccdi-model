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
<svg width="1989pt" height="1039pt"
 viewBox="0.00 0.00 1988.50 1039.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1035)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1035 1984.5,-1035 1984.5,4 -4,4"/>
<!-- sequencing_file -->
<g id="node1" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M328,-662.5C328,-662.5 698,-662.5 698,-662.5 704,-662.5 710,-668.5 710,-674.5 710,-674.5 710,-1018.5 710,-1018.5 710,-1024.5 704,-1030.5 698,-1030.5 698,-1030.5 328,-1030.5 328,-1030.5 322,-1030.5 316,-1024.5 316,-1018.5 316,-1018.5 316,-674.5 316,-674.5 316,-668.5 322,-662.5 328,-662.5"/>
<text text-anchor="middle" x="380" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="444,-662.5 444,-1030.5 "/>
<text text-anchor="middle" x="454.5" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="465,-662.5 465,-1030.5 "/>
<text text-anchor="middle" x="577" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">average_read_length</text>
<polyline fill="none" stroke="#000000" points="465,-1007.5 689,-1007.5 "/>
<text text-anchor="middle" x="577" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_url</text>
<polyline fill="none" stroke="#000000" points="465,-984.5 689,-984.5 "/>
<text text-anchor="middle" x="577" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="465,-961.5 689,-961.5 "/>
<text text-anchor="middle" x="577" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="465,-938.5 689,-938.5 "/>
<text text-anchor="middle" x="577" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="465,-915.5 689,-915.5 "/>
<text text-anchor="middle" x="577" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="465,-892.5 689,-892.5 "/>
<text text-anchor="middle" x="577" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="465,-869.5 689,-869.5 "/>
<text text-anchor="middle" x="577" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="465,-846.5 689,-846.5 "/>
<text text-anchor="middle" x="577" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="465,-823.5 689,-823.5 "/>
<text text-anchor="middle" x="577" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="465,-800.5 689,-800.5 "/>
<text text-anchor="middle" x="577" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="465,-777.5 689,-777.5 "/>
<text text-anchor="middle" x="577" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="465,-754.5 689,-754.5 "/>
<text text-anchor="middle" x="577" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="465,-731.5 689,-731.5 "/>
<text text-anchor="middle" x="577" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="465,-708.5 689,-708.5 "/>
<text text-anchor="middle" x="577" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="465,-685.5 689,-685.5 "/>
<text text-anchor="middle" x="577" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="689,-662.5 689,-1030.5 "/>
<text text-anchor="middle" x="699.5" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node3" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M12,-357.5C12,-357.5 326,-357.5 326,-357.5 332,-357.5 338,-363.5 338,-369.5 338,-369.5 338,-598.5 338,-598.5 338,-604.5 332,-610.5 326,-610.5 326,-610.5 12,-610.5 12,-610.5 6,-610.5 0,-604.5 0,-598.5 0,-598.5 0,-369.5 0,-369.5 0,-363.5 6,-357.5 12,-357.5"/>
<text text-anchor="middle" x="34" y="-480.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="68,-357.5 68,-610.5 "/>
<text text-anchor="middle" x="78.5" y="-480.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="89,-357.5 89,-610.5 "/>
<text text-anchor="middle" x="203" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="89,-587.5 317,-587.5 "/>
<text text-anchor="middle" x="203" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_sample_id</text>
<polyline fill="none" stroke="#000000" points="89,-564.5 317,-564.5 "/>
<text text-anchor="middle" x="203" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="89,-541.5 317,-541.5 "/>
<text text-anchor="middle" x="203" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="89,-518.5 317,-518.5 "/>
<text text-anchor="middle" x="203" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="89,-495.5 317,-495.5 "/>
<text text-anchor="middle" x="203" y="-480.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="89,-472.5 317,-472.5 "/>
<text text-anchor="middle" x="203" y="-457.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="89,-449.5 317,-449.5 "/>
<text text-anchor="middle" x="203" y="-434.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="89,-426.5 317,-426.5 "/>
<text text-anchor="middle" x="203" y="-411.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="89,-403.5 317,-403.5 "/>
<text text-anchor="middle" x="203" y="-388.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage</text>
<polyline fill="none" stroke="#000000" points="89,-380.5 317,-380.5 "/>
<text text-anchor="middle" x="203" y="-365.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_status</text>
<polyline fill="none" stroke="#000000" points="317,-357.5 317,-610.5 "/>
<text text-anchor="middle" x="327.5" y="-480.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M338.2286,-662.3296C324.0803,-647.4204 309.957,-632.5376 296.2418,-618.0847"/>
<polygon fill="#000000" stroke="#000000" points="298.5312,-615.4127 289.1088,-610.5682 293.4536,-620.2312 298.5312,-615.4127"/>
<text text-anchor="middle" x="387.5" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- experiment -->
<g id="node10" class="node">
<title>experiment</title>
<path fill="none" stroke="#000000" d="M1085,-461C1085,-461 1353,-461 1353,-461 1359,-461 1365,-467 1365,-473 1365,-473 1365,-495 1365,-495 1365,-501 1359,-507 1353,-507 1353,-507 1085,-507 1085,-507 1079,-507 1073,-501 1073,-495 1073,-495 1073,-473 1073,-473 1073,-467 1079,-461 1085,-461"/>
<text text-anchor="middle" x="1122" y="-480.3" font-family="Times,serif" font-size="14.00" fill="#000000">experiment</text>
<polyline fill="none" stroke="#000000" points="1171,-461 1171,-507 "/>
<text text-anchor="middle" x="1181.5" y="-480.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1192,-461 1192,-507 "/>
<text text-anchor="middle" x="1268" y="-491.8" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="1192,-484 1344,-484 "/>
<text text-anchor="middle" x="1268" y="-468.8" font-family="Times,serif" font-size="14.00" fill="#000000">experiment_id</text>
<polyline fill="none" stroke="#000000" points="1344,-461 1344,-507 "/>
<text text-anchor="middle" x="1354.5" y="-480.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;experiment -->
<g id="edge6" class="edge">
<title>sequencing_file&#45;&gt;experiment</title>
<path fill="none" stroke="#000000" d="M658.7742,-662.3952C675.4521,-649.3219 693.2501,-637.8372 712,-629 782.8495,-595.6074 990.941,-639.2329 1064,-611 1116.501,-590.7115 1164.5504,-545.3422 1192.8056,-514.6971"/>
<polygon fill="#000000" stroke="#000000" points="1195.434,-517.0087 1199.5532,-507.2474 1190.2459,-512.3094 1195.434,-517.0087"/>
<text text-anchor="middle" x="778.5" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- participant -->
<g id="node2" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M373.5,-179C373.5,-179 604.5,-179 604.5,-179 610.5,-179 616.5,-185 616.5,-191 616.5,-191 616.5,-282 616.5,-282 616.5,-288 610.5,-294 604.5,-294 604.5,-294 373.5,-294 373.5,-294 367.5,-294 361.5,-288 361.5,-282 361.5,-282 361.5,-191 361.5,-191 361.5,-185 367.5,-179 373.5,-179"/>
<text text-anchor="middle" x="409.5" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="457.5,-179 457.5,-294 "/>
<text text-anchor="middle" x="468" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="478.5,-179 478.5,-294 "/>
<text text-anchor="middle" x="537" y="-278.8" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="478.5,-271 595.5,-271 "/>
<text text-anchor="middle" x="537" y="-255.8" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="478.5,-248 595.5,-248 "/>
<text text-anchor="middle" x="537" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="478.5,-225 595.5,-225 "/>
<text text-anchor="middle" x="537" y="-209.8" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="478.5,-202 595.5,-202 "/>
<text text-anchor="middle" x="537" y="-186.8" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="595.5,-179 595.5,-294 "/>
<text text-anchor="middle" x="606" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node5" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M912.5,-.5C912.5,-.5 1157.5,-.5 1157.5,-.5 1163.5,-.5 1169.5,-6.5 1169.5,-12.5 1169.5,-12.5 1169.5,-103.5 1169.5,-103.5 1169.5,-109.5 1163.5,-115.5 1157.5,-115.5 1157.5,-115.5 912.5,-115.5 912.5,-115.5 906.5,-115.5 900.5,-109.5 900.5,-103.5 900.5,-103.5 900.5,-12.5 900.5,-12.5 900.5,-6.5 906.5,-.5 912.5,-.5"/>
<text text-anchor="middle" x="928.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="956.5,-.5 956.5,-115.5 "/>
<text text-anchor="middle" x="967" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="977.5,-.5 977.5,-115.5 "/>
<text text-anchor="middle" x="1063" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_phs_accession</text>
<polyline fill="none" stroke="#000000" points="977.5,-92.5 1148.5,-92.5 "/>
<text text-anchor="middle" x="1063" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="977.5,-69.5 1148.5,-69.5 "/>
<text text-anchor="middle" x="1063" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="977.5,-46.5 1148.5,-46.5 "/>
<text text-anchor="middle" x="1063" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="977.5,-23.5 1148.5,-23.5 "/>
<text text-anchor="middle" x="1063" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_title</text>
<polyline fill="none" stroke="#000000" points="1148.5,-.5 1148.5,-115.5 "/>
<text text-anchor="middle" x="1159" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge11" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M597.6241,-178.8383C607.1121,-174.5847 616.6574,-170.5696 626,-167 711.5788,-134.3024 810.8024,-107.6014 890.0859,-88.811"/>
<polygon fill="#000000" stroke="#000000" points="891.2142,-92.1411 900.1467,-86.4436 889.6108,-85.3273 891.2142,-92.1411"/>
<text text-anchor="middle" x="763.5" y="-137.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M332.7497,-357.3498C358.3346,-337.5616 383.7915,-317.8722 406.5018,-300.3072"/>
<polygon fill="#000000" stroke="#000000" points="408.6471,-303.0727 414.4159,-294.1861 404.3644,-297.5356 408.6471,-303.0727"/>
<text text-anchor="middle" x="404.5" y="-327.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge14" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M181.6542,-357.1358C195.0773,-290.6295 222.6149,-213.5361 279,-167 369.6164,-92.212 697.0178,-68.7342 889.9783,-61.3667"/>
<polygon fill="#000000" stroke="#000000" points="890.3418,-64.8557 900.2048,-60.9865 890.0817,-57.8605 890.3418,-64.8557"/>
<text text-anchor="middle" x="315.5" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- clinical_measure -->
<g id="node4" class="node">
<title>clinical_measure</title>
<path fill="none" stroke="#000000" d="M646.5,-218.5C646.5,-218.5 857.5,-218.5 857.5,-218.5 863.5,-218.5 869.5,-224.5 869.5,-230.5 869.5,-230.5 869.5,-242.5 869.5,-242.5 869.5,-248.5 863.5,-254.5 857.5,-254.5 857.5,-254.5 646.5,-254.5 646.5,-254.5 640.5,-254.5 634.5,-248.5 634.5,-242.5 634.5,-242.5 634.5,-230.5 634.5,-230.5 634.5,-224.5 640.5,-218.5 646.5,-218.5"/>
<text text-anchor="middle" x="703" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure</text>
<polyline fill="none" stroke="#000000" points="771.5,-218.5 771.5,-254.5 "/>
<text text-anchor="middle" x="782" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="792.5,-218.5 792.5,-254.5 "/>
<text text-anchor="middle" x="820.5" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000">name</text>
<polyline fill="none" stroke="#000000" points="848.5,-218.5 848.5,-254.5 "/>
<text text-anchor="middle" x="859" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure&#45;&gt;study -->
<g id="edge3" class="edge">
<title>clinical_measure&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M773.9871,-218.288C800.4059,-196.8278 846.4972,-160.7147 889,-134 896.1296,-129.5188 903.5523,-125.0622 911.1064,-120.6839"/>
<polygon fill="#000000" stroke="#000000" points="913.0817,-123.5862 920.0247,-115.5834 909.6065,-117.5098 913.0817,-123.5862"/>
<text text-anchor="middle" x="960" y="-137.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure</text>
</g>
<!-- study_admin -->
<g id="node6" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M899.5,-167.5C899.5,-167.5 1170.5,-167.5 1170.5,-167.5 1176.5,-167.5 1182.5,-173.5 1182.5,-179.5 1182.5,-179.5 1182.5,-293.5 1182.5,-293.5 1182.5,-299.5 1176.5,-305.5 1170.5,-305.5 1170.5,-305.5 899.5,-305.5 899.5,-305.5 893.5,-305.5 887.5,-299.5 887.5,-293.5 887.5,-293.5 887.5,-179.5 887.5,-179.5 887.5,-173.5 893.5,-167.5 899.5,-167.5"/>
<text text-anchor="middle" x="941.5" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="995.5,-167.5 995.5,-305.5 "/>
<text text-anchor="middle" x="1006" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1016.5,-167.5 1016.5,-305.5 "/>
<text text-anchor="middle" x="1089" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_access_level</text>
<polyline fill="none" stroke="#000000" points="1016.5,-282.5 1161.5,-282.5 "/>
<text text-anchor="middle" x="1089" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="1016.5,-259.5 1161.5,-259.5 "/>
<text text-anchor="middle" x="1089" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types</text>
<polyline fill="none" stroke="#000000" points="1016.5,-236.5 1161.5,-236.5 "/>
<text text-anchor="middle" x="1089" y="-221.3" font-family="Times,serif" font-size="14.00" fill="#000000">species</text>
<polyline fill="none" stroke="#000000" points="1016.5,-213.5 1161.5,-213.5 "/>
<text text-anchor="middle" x="1089" y="-198.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="1016.5,-190.5 1161.5,-190.5 "/>
<text text-anchor="middle" x="1089" y="-175.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_type</text>
<polyline fill="none" stroke="#000000" points="1161.5,-167.5 1161.5,-305.5 "/>
<text text-anchor="middle" x="1172" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge7" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1035,-167.4872C1035,-153.8062 1035,-139.4554 1035,-125.8146"/>
<polygon fill="#000000" stroke="#000000" points="1038.5001,-125.5447 1035,-115.5447 1031.5001,-125.5448 1038.5001,-125.5447"/>
<text text-anchor="middle" x="1091.5" y="-137.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- diagnosis -->
<g id="node7" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M368,-403.5C368,-403.5 682,-403.5 682,-403.5 688,-403.5 694,-409.5 694,-415.5 694,-415.5 694,-552.5 694,-552.5 694,-558.5 688,-564.5 682,-564.5 682,-564.5 368,-564.5 368,-564.5 362,-564.5 356,-558.5 356,-552.5 356,-552.5 356,-415.5 356,-415.5 356,-409.5 362,-403.5 368,-403.5"/>
<text text-anchor="middle" x="398" y="-480.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="440,-403.5 440,-564.5 "/>
<text text-anchor="middle" x="450.5" y="-480.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="461,-403.5 461,-564.5 "/>
<text text-anchor="middle" x="567" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="461,-541.5 673,-541.5 "/>
<text text-anchor="middle" x="567" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_status</text>
<polyline fill="none" stroke="#000000" points="461,-518.5 673,-518.5 "/>
<text text-anchor="middle" x="567" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="461,-495.5 673,-495.5 "/>
<text text-anchor="middle" x="567" y="-480.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="461,-472.5 673,-472.5 "/>
<text text-anchor="middle" x="567" y="-457.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="461,-449.5 673,-449.5 "/>
<text text-anchor="middle" x="567" y="-434.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="461,-426.5 673,-426.5 "/>
<text text-anchor="middle" x="567" y="-411.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="673,-403.5 673,-564.5 "/>
<text text-anchor="middle" x="683.5" y="-480.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M502.0922,-403.3074C497.1413,-382.5245 492.6117,-360.074 490,-339 488.6119,-327.7991 487.8502,-315.8571 487.4897,-304.2286"/>
<polygon fill="#000000" stroke="#000000" points="490.9865,-304.0385 487.2705,-294.1168 483.9881,-304.1903 490.9865,-304.0385"/>
<text text-anchor="middle" x="534.5" y="-327.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- clinical_measure_file -->
<g id="node8" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M723.5,-403.5C723.5,-403.5 1042.5,-403.5 1042.5,-403.5 1048.5,-403.5 1054.5,-409.5 1054.5,-415.5 1054.5,-415.5 1054.5,-552.5 1054.5,-552.5 1054.5,-558.5 1048.5,-564.5 1042.5,-564.5 1042.5,-564.5 723.5,-564.5 723.5,-564.5 717.5,-564.5 711.5,-558.5 711.5,-552.5 711.5,-552.5 711.5,-415.5 711.5,-415.5 711.5,-409.5 717.5,-403.5 723.5,-403.5"/>
<text text-anchor="middle" x="795" y="-480.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="878.5,-403.5 878.5,-564.5 "/>
<text text-anchor="middle" x="889" y="-480.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="899.5,-403.5 899.5,-564.5 "/>
<text text-anchor="middle" x="966.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_url</text>
<polyline fill="none" stroke="#000000" points="899.5,-541.5 1033.5,-541.5 "/>
<text text-anchor="middle" x="966.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="899.5,-518.5 1033.5,-518.5 "/>
<text text-anchor="middle" x="966.5" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="899.5,-495.5 1033.5,-495.5 "/>
<text text-anchor="middle" x="966.5" y="-480.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="899.5,-472.5 1033.5,-472.5 "/>
<text text-anchor="middle" x="966.5" y="-457.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="899.5,-449.5 1033.5,-449.5 "/>
<text text-anchor="middle" x="966.5" y="-434.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="899.5,-426.5 1033.5,-426.5 "/>
<text text-anchor="middle" x="966.5" y="-411.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1033.5,-403.5 1033.5,-564.5 "/>
<text text-anchor="middle" x="1044" y="-480.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M785.3155,-403.3638C759.8073,-385.689 731.4508,-368.7651 703,-357 659.2461,-338.9066 640.3789,-360.1142 598,-339 592.2019,-336.1113 574.3732,-319.9115 554.7697,-301.2126"/>
<polygon fill="#000000" stroke="#000000" points="557.127,-298.624 547.486,-294.2305 552.2829,-303.6772 557.127,-298.624"/>
<text text-anchor="middle" x="727.5" y="-327.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;clinical_measure -->
<g id="edge2" class="edge">
<title>clinical_measure_file&#45;&gt;clinical_measure</title>
<path fill="none" stroke="#000000" d="M883.6416,-403.3006C880.8797,-376.6615 874.4772,-347.7853 861,-324 845.7248,-297.0414 818.5704,-275.2073 795.1872,-260.0924"/>
<polygon fill="#000000" stroke="#000000" points="796.7785,-256.9598 786.4426,-254.6318 793.0708,-262.8973 796.7785,-256.9598"/>
<text text-anchor="middle" x="952" y="-327.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- alias -->
<g id="node9" class="node">
<title>alias</title>
<path fill="none" stroke="#000000" d="M1071.5,-800.5C1071.5,-800.5 1276.5,-800.5 1276.5,-800.5 1282.5,-800.5 1288.5,-806.5 1288.5,-812.5 1288.5,-812.5 1288.5,-880.5 1288.5,-880.5 1288.5,-886.5 1282.5,-892.5 1276.5,-892.5 1276.5,-892.5 1071.5,-892.5 1071.5,-892.5 1065.5,-892.5 1059.5,-886.5 1059.5,-880.5 1059.5,-880.5 1059.5,-812.5 1059.5,-812.5 1059.5,-806.5 1065.5,-800.5 1071.5,-800.5"/>
<text text-anchor="middle" x="1084.5" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">alias</text>
<polyline fill="none" stroke="#000000" points="1109.5,-800.5 1109.5,-892.5 "/>
<text text-anchor="middle" x="1120" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1130.5,-800.5 1130.5,-892.5 "/>
<text text-anchor="middle" x="1199" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_id</text>
<polyline fill="none" stroke="#000000" points="1130.5,-869.5 1267.5,-869.5 "/>
<text text-anchor="middle" x="1199" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_node</text>
<polyline fill="none" stroke="#000000" points="1130.5,-846.5 1267.5,-846.5 "/>
<text text-anchor="middle" x="1199" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">repository_id</text>
<polyline fill="none" stroke="#000000" points="1130.5,-823.5 1267.5,-823.5 "/>
<text text-anchor="middle" x="1199" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">repository_name</text>
<polyline fill="none" stroke="#000000" points="1267.5,-800.5 1267.5,-892.5 "/>
<text text-anchor="middle" x="1278" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- experiment&#45;&gt;study -->
<g id="edge13" class="edge">
<title>experiment&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1222.8195,-460.8256C1230.671,-406.056 1243.8168,-265.8103 1192,-167 1183.0764,-149.9834 1170.1569,-135.0881 1155.5058,-122.2249"/>
<polygon fill="#000000" stroke="#000000" points="1157.6112,-119.4229 1147.6983,-115.6831 1153.1155,-124.7884 1157.6112,-119.4229"/>
<text text-anchor="middle" x="1279.5" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_experiment</text>
</g>
<!-- study_funding -->
<g id="node11" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M1352.5,-213.5C1352.5,-213.5 1619.5,-213.5 1619.5,-213.5 1625.5,-213.5 1631.5,-219.5 1631.5,-225.5 1631.5,-225.5 1631.5,-247.5 1631.5,-247.5 1631.5,-253.5 1625.5,-259.5 1619.5,-259.5 1619.5,-259.5 1352.5,-259.5 1352.5,-259.5 1346.5,-259.5 1340.5,-253.5 1340.5,-247.5 1340.5,-247.5 1340.5,-225.5 1340.5,-225.5 1340.5,-219.5 1346.5,-213.5 1352.5,-213.5"/>
<text text-anchor="middle" x="1400" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="1459.5,-213.5 1459.5,-259.5 "/>
<text text-anchor="middle" x="1470" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1480.5,-213.5 1480.5,-259.5 "/>
<text text-anchor="middle" x="1545.5" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="1480.5,-236.5 1610.5,-236.5 "/>
<text text-anchor="middle" x="1545.5" y="-221.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_id</text>
<polyline fill="none" stroke="#000000" points="1610.5,-213.5 1610.5,-259.5 "/>
<text text-anchor="middle" x="1621" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge12" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1434.7624,-213.4455C1403.5047,-199.5806 1362.6426,-181.8095 1326,-167 1278.5039,-147.8039 1226.2049,-127.8514 1179.201,-110.3449"/>
<polygon fill="#000000" stroke="#000000" points="1180.1578,-106.9666 1169.5649,-106.7625 1177.7185,-113.5278 1180.1578,-106.9666"/>
<text text-anchor="middle" x="1340" y="-137.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- study_personnel -->
<g id="node12" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M1661.5,-179C1661.5,-179 1968.5,-179 1968.5,-179 1974.5,-179 1980.5,-185 1980.5,-191 1980.5,-191 1980.5,-282 1980.5,-282 1980.5,-288 1974.5,-294 1968.5,-294 1968.5,-294 1661.5,-294 1661.5,-294 1655.5,-294 1649.5,-288 1649.5,-282 1649.5,-282 1649.5,-191 1649.5,-191 1649.5,-185 1655.5,-179 1661.5,-179"/>
<text text-anchor="middle" x="1716.5" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="1783.5,-179 1783.5,-294 "/>
<text text-anchor="middle" x="1794" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1804.5,-179 1804.5,-294 "/>
<text text-anchor="middle" x="1882" y="-278.8" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="1804.5,-271 1959.5,-271 "/>
<text text-anchor="middle" x="1882" y="-255.8" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="1804.5,-248 1959.5,-248 "/>
<text text-anchor="middle" x="1882" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="1804.5,-225 1959.5,-225 "/>
<text text-anchor="middle" x="1882" y="-209.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="1804.5,-202 1959.5,-202 "/>
<text text-anchor="middle" x="1882" y="-186.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="1959.5,-179 1959.5,-294 "/>
<text text-anchor="middle" x="1970" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge4" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1678.1732,-178.8782C1665.7139,-174.5357 1653.1958,-170.4936 1641,-167 1486.1666,-122.6466 1303.6732,-92.7448 1179.7121,-75.6474"/>
<polygon fill="#000000" stroke="#000000" points="1180.1539,-72.1753 1169.7716,-74.2864 1179.2044,-79.1106 1180.1539,-72.1753"/>
<text text-anchor="middle" x="1629.5" y="-137.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- imaging_file -->
<g id="node13" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M760.5,-720C760.5,-720 1029.5,-720 1029.5,-720 1035.5,-720 1041.5,-726 1041.5,-732 1041.5,-732 1041.5,-961 1041.5,-961 1041.5,-967 1035.5,-973 1029.5,-973 1029.5,-973 760.5,-973 760.5,-973 754.5,-973 748.5,-967 748.5,-961 748.5,-961 748.5,-732 748.5,-732 748.5,-726 754.5,-720 760.5,-720"/>
<text text-anchor="middle" x="800.5" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="852.5,-720 852.5,-973 "/>
<text text-anchor="middle" x="863" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="873.5,-720 873.5,-973 "/>
<text text-anchor="middle" x="947" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">cds_url</text>
<polyline fill="none" stroke="#000000" points="873.5,-950 1020.5,-950 "/>
<text text-anchor="middle" x="947" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="873.5,-927 1020.5,-927 "/>
<text text-anchor="middle" x="947" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="873.5,-904 1020.5,-904 "/>
<text text-anchor="middle" x="947" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="873.5,-881 1020.5,-881 "/>
<text text-anchor="middle" x="947" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="873.5,-858 1020.5,-858 "/>
<text text-anchor="middle" x="947" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="873.5,-835 1020.5,-835 "/>
<text text-anchor="middle" x="947" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="873.5,-812 1020.5,-812 "/>
<text text-anchor="middle" x="947" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="873.5,-789 1020.5,-789 "/>
<text text-anchor="middle" x="947" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="873.5,-766 1020.5,-766 "/>
<text text-anchor="middle" x="947" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="873.5,-743 1020.5,-743 "/>
<text text-anchor="middle" x="947" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="1020.5,-720 1020.5,-973 "/>
<text text-anchor="middle" x="1031" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M893.3379,-719.8965C886.3571,-685.4305 872.1819,-651.4563 845,-629 804.1477,-595.25 433.3777,-625.9469 347.8639,-610.1917"/>
<polygon fill="#000000" stroke="#000000" points="348.6747,-606.7868 338.1264,-607.7786 346.9909,-613.5813 348.6747,-606.7868"/>
<text text-anchor="middle" x="911.5" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- imaging_file&#45;&gt;experiment -->
<g id="edge9" class="edge">
<title>imaging_file&#45;&gt;experiment</title>
<path fill="none" stroke="#000000" d="M1000.6675,-719.6687C1017.336,-700.2035 1034.5108,-680.4551 1051,-662 1098.1153,-609.2674 1154.9675,-549.8753 1188.988,-514.765"/>
<polygon fill="#000000" stroke="#000000" points="1191.8488,-516.8428 1196.3011,-507.2289 1186.8252,-511.968 1191.8488,-516.8428"/>
<text text-anchor="middle" x="1131.5" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
</g>
</svg>
</div>
