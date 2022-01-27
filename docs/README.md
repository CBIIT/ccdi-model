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
<svg width="1298pt" height="1350pt"
 viewBox="0.00 0.00 1297.87 1350.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1346)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1346 1293.8662,-1346 1293.8662,4 -4,4"/>
<!-- study -->
<g id="node1" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M379.8662,-167.5C379.8662,-167.5 624.8662,-167.5 624.8662,-167.5 630.8662,-167.5 636.8662,-173.5 636.8662,-179.5 636.8662,-179.5 636.8662,-293.5 636.8662,-293.5 636.8662,-299.5 630.8662,-305.5 624.8662,-305.5 624.8662,-305.5 379.8662,-305.5 379.8662,-305.5 373.8662,-305.5 367.8662,-299.5 367.8662,-293.5 367.8662,-293.5 367.8662,-179.5 367.8662,-179.5 367.8662,-173.5 373.8662,-167.5 379.8662,-167.5"/>
<text text-anchor="middle" x="395.8662" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="423.8662,-167.5 423.8662,-305.5 "/>
<text text-anchor="middle" x="434.3662" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="444.8662,-167.5 444.8662,-305.5 "/>
<text text-anchor="middle" x="530.3662" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_phs_accession</text>
<polyline fill="none" stroke="#000000" points="444.8662,-282.5 615.8662,-282.5 "/>
<text text-anchor="middle" x="530.3662" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="444.8662,-259.5 615.8662,-259.5 "/>
<text text-anchor="middle" x="530.3662" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="444.8662,-236.5 615.8662,-236.5 "/>
<text text-anchor="middle" x="530.3662" y="-221.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="444.8662,-213.5 615.8662,-213.5 "/>
<text text-anchor="middle" x="530.3662" y="-198.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="444.8662,-190.5 615.8662,-190.5 "/>
<text text-anchor="middle" x="530.3662" y="-175.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_title</text>
<polyline fill="none" stroke="#000000" points="615.8662,-167.5 615.8662,-305.5 "/>
<text text-anchor="middle" x="626.3662" y="-232.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel -->
<g id="node8" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M181.8662,-.5C181.8662,-.5 492.8662,-.5 492.8662,-.5 498.8662,-.5 504.8662,-6.5 504.8662,-12.5 504.8662,-12.5 504.8662,-103.5 504.8662,-103.5 504.8662,-109.5 498.8662,-115.5 492.8662,-115.5 492.8662,-115.5 181.8662,-115.5 181.8662,-115.5 175.8662,-115.5 169.8662,-109.5 169.8662,-103.5 169.8662,-103.5 169.8662,-12.5 169.8662,-12.5 169.8662,-6.5 175.8662,-.5 181.8662,-.5"/>
<text text-anchor="middle" x="236.8662" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="303.8662,-.5 303.8662,-115.5 "/>
<text text-anchor="middle" x="314.3662" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="324.8662,-.5 324.8662,-115.5 "/>
<text text-anchor="middle" x="404.3662" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="324.8662,-92.5 483.8662,-92.5 "/>
<text text-anchor="middle" x="404.3662" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="324.8662,-69.5 483.8662,-69.5 "/>
<text text-anchor="middle" x="404.3662" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="324.8662,-46.5 483.8662,-46.5 "/>
<text text-anchor="middle" x="404.3662" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="324.8662,-23.5 483.8662,-23.5 "/>
<text text-anchor="middle" x="404.3662" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_ID</text>
<polyline fill="none" stroke="#000000" points="483.8662,-.5 483.8662,-115.5 "/>
<text text-anchor="middle" x="494.3662" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study&#45;&gt;study_personnel -->
<g id="edge7" class="edge">
<title>study&#45;&gt;study_personnel</title>
<path fill="none" stroke="#000000" d="M438.5728,-167.4872C425.0586,-152.8673 410.8374,-137.4825 397.4656,-123.0167"/>
<polygon fill="#000000" stroke="#000000" points="399.9169,-120.5123 390.5588,-115.5447 394.7766,-125.2638 399.9169,-120.5123"/>
<text text-anchor="middle" x="500.3662" y="-137.8" font-family="Times,serif" font-size="14.00" fill="#000000">from_study_personnel</text>
</g>
<!-- study_funding -->
<g id="node11" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M534.8662,-35C534.8662,-35 801.8662,-35 801.8662,-35 807.8662,-35 813.8662,-41 813.8662,-47 813.8662,-47 813.8662,-69 813.8662,-69 813.8662,-75 807.8662,-81 801.8662,-81 801.8662,-81 534.8662,-81 534.8662,-81 528.8662,-81 522.8662,-75 522.8662,-69 522.8662,-69 522.8662,-47 522.8662,-47 522.8662,-41 528.8662,-35 534.8662,-35"/>
<text text-anchor="middle" x="582.3662" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="641.8662,-35 641.8662,-81 "/>
<text text-anchor="middle" x="652.3662" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="662.8662,-35 662.8662,-81 "/>
<text text-anchor="middle" x="727.8662" y="-65.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="662.8662,-58 792.8662,-58 "/>
<text text-anchor="middle" x="727.8662" y="-42.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_id</text>
<polyline fill="none" stroke="#000000" points="792.8662,-35 792.8662,-81 "/>
<text text-anchor="middle" x="803.3662" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study&#45;&gt;study_funding -->
<g id="edge15" class="edge">
<title>study&#45;&gt;study_funding</title>
<path fill="none" stroke="#000000" d="M567.3171,-167.2891C573.0885,-161.11 578.8365,-154.9454 584.3662,-149 602.9053,-129.0672 623.6529,-106.5923 639.8899,-88.9653"/>
<polygon fill="#000000" stroke="#000000" points="642.8097,-90.9614 647.0086,-81.2341 637.6601,-86.2198 642.8097,-90.9614"/>
<text text-anchor="middle" x="673.8662" y="-137.8" font-family="Times,serif" font-size="14.00" fill="#000000">from_study__funding</text>
</g>
<!-- sequencing_detail -->
<g id="node2" class="node">
<title>sequencing_detail</title>
<path fill="none" stroke="#000000" d="M118.3662,-1111.5C118.3662,-1111.5 506.3662,-1111.5 506.3662,-1111.5 512.3662,-1111.5 518.3662,-1117.5 518.3662,-1123.5 518.3662,-1123.5 518.3662,-1329.5 518.3662,-1329.5 518.3662,-1335.5 512.3662,-1341.5 506.3662,-1341.5 506.3662,-1341.5 118.3662,-1341.5 118.3662,-1341.5 112.3662,-1341.5 106.3662,-1335.5 106.3662,-1329.5 106.3662,-1329.5 106.3662,-1123.5 106.3662,-1123.5 106.3662,-1117.5 112.3662,-1111.5 118.3662,-1111.5"/>
<text text-anchor="middle" x="179.3662" y="-1222.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_detail</text>
<polyline fill="none" stroke="#000000" points="252.3662,-1111.5 252.3662,-1341.5 "/>
<text text-anchor="middle" x="262.8662" y="-1222.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="273.3662,-1111.5 273.3662,-1341.5 "/>
<text text-anchor="middle" x="385.3662" y="-1326.3" font-family="Times,serif" font-size="14.00" fill="#000000">average_read_length</text>
<polyline fill="none" stroke="#000000" points="273.3662,-1318.5 497.3662,-1318.5 "/>
<text text-anchor="middle" x="385.3662" y="-1303.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="273.3662,-1295.5 497.3662,-1295.5 "/>
<text text-anchor="middle" x="385.3662" y="-1280.3" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_detail_id</text>
<polyline fill="none" stroke="#000000" points="273.3662,-1272.5 497.3662,-1272.5 "/>
<text text-anchor="middle" x="385.3662" y="-1257.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="273.3662,-1249.5 497.3662,-1249.5 "/>
<text text-anchor="middle" x="385.3662" y="-1234.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="273.3662,-1226.5 497.3662,-1226.5 "/>
<text text-anchor="middle" x="385.3662" y="-1211.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="273.3662,-1203.5 497.3662,-1203.5 "/>
<text text-anchor="middle" x="385.3662" y="-1188.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="273.3662,-1180.5 497.3662,-1180.5 "/>
<text text-anchor="middle" x="385.3662" y="-1165.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="273.3662,-1157.5 497.3662,-1157.5 "/>
<text text-anchor="middle" x="385.3662" y="-1142.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="273.3662,-1134.5 497.3662,-1134.5 "/>
<text text-anchor="middle" x="385.3662" y="-1119.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="497.3662,-1111.5 497.3662,-1341.5 "/>
<text text-anchor="middle" x="507.8662" y="-1222.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file -->
<g id="node5" class="node">
<title>file</title>
<path fill="none" stroke="#000000" d="M406.8662,-875.5C406.8662,-875.5 597.8662,-875.5 597.8662,-875.5 603.8662,-875.5 609.8662,-881.5 609.8662,-887.5 609.8662,-887.5 609.8662,-1047.5 609.8662,-1047.5 609.8662,-1053.5 603.8662,-1059.5 597.8662,-1059.5 597.8662,-1059.5 406.8662,-1059.5 406.8662,-1059.5 400.8662,-1059.5 394.8662,-1053.5 394.8662,-1047.5 394.8662,-1047.5 394.8662,-887.5 394.8662,-887.5 394.8662,-881.5 400.8662,-875.5 406.8662,-875.5"/>
<text text-anchor="middle" x="414.3662" y="-963.8" font-family="Times,serif" font-size="14.00" fill="#000000">file</text>
<polyline fill="none" stroke="#000000" points="433.8662,-875.5 433.8662,-1059.5 "/>
<text text-anchor="middle" x="444.3662" y="-963.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="454.8662,-875.5 454.8662,-1059.5 "/>
<text text-anchor="middle" x="521.8662" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_url</text>
<polyline fill="none" stroke="#000000" points="454.8662,-1036.5 588.8662,-1036.5 "/>
<text text-anchor="middle" x="521.8662" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="454.8662,-1013.5 588.8662,-1013.5 "/>
<text text-anchor="middle" x="521.8662" y="-998.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="454.8662,-990.5 588.8662,-990.5 "/>
<text text-anchor="middle" x="521.8662" y="-975.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_id</text>
<polyline fill="none" stroke="#000000" points="454.8662,-967.5 588.8662,-967.5 "/>
<text text-anchor="middle" x="521.8662" y="-952.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="454.8662,-944.5 588.8662,-944.5 "/>
<text text-anchor="middle" x="521.8662" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="454.8662,-921.5 588.8662,-921.5 "/>
<text text-anchor="middle" x="521.8662" y="-906.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="454.8662,-898.5 588.8662,-898.5 "/>
<text text-anchor="middle" x="521.8662" y="-883.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="588.8662,-875.5 588.8662,-1059.5 "/>
<text text-anchor="middle" x="599.3662" y="-963.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_detail&#45;&gt;file -->
<g id="edge9" class="edge">
<title>sequencing_detail&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M396.8094,-1111.3905C407.4142,-1096.9345 418.1966,-1082.2364 428.6193,-1068.0286"/>
<polygon fill="#000000" stroke="#000000" points="431.6175,-1069.8588 434.7104,-1059.7255 425.9733,-1065.7183 431.6175,-1069.8588"/>
<text text-anchor="middle" x="441.3662" y="-1081.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- alias -->
<g id="node3" class="node">
<title>alias</title>
<path fill="none" stroke="#000000" d="M877.8662,-1180.5C877.8662,-1180.5 1082.8662,-1180.5 1082.8662,-1180.5 1088.8662,-1180.5 1094.8662,-1186.5 1094.8662,-1192.5 1094.8662,-1192.5 1094.8662,-1260.5 1094.8662,-1260.5 1094.8662,-1266.5 1088.8662,-1272.5 1082.8662,-1272.5 1082.8662,-1272.5 877.8662,-1272.5 877.8662,-1272.5 871.8662,-1272.5 865.8662,-1266.5 865.8662,-1260.5 865.8662,-1260.5 865.8662,-1192.5 865.8662,-1192.5 865.8662,-1186.5 871.8662,-1180.5 877.8662,-1180.5"/>
<text text-anchor="middle" x="890.8662" y="-1222.8" font-family="Times,serif" font-size="14.00" fill="#000000">alias</text>
<polyline fill="none" stroke="#000000" points="915.8662,-1180.5 915.8662,-1272.5 "/>
<text text-anchor="middle" x="926.3662" y="-1222.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="936.8662,-1180.5 936.8662,-1272.5 "/>
<text text-anchor="middle" x="1005.3662" y="-1257.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_id</text>
<polyline fill="none" stroke="#000000" points="936.8662,-1249.5 1073.8662,-1249.5 "/>
<text text-anchor="middle" x="1005.3662" y="-1234.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_node</text>
<polyline fill="none" stroke="#000000" points="936.8662,-1226.5 1073.8662,-1226.5 "/>
<text text-anchor="middle" x="1005.3662" y="-1211.3" font-family="Times,serif" font-size="14.00" fill="#000000">repository_id</text>
<polyline fill="none" stroke="#000000" points="936.8662,-1203.5 1073.8662,-1203.5 "/>
<text text-anchor="middle" x="1005.3662" y="-1188.3" font-family="Times,serif" font-size="14.00" fill="#000000">repository_name</text>
<polyline fill="none" stroke="#000000" points="1073.8662,-1180.5 1073.8662,-1272.5 "/>
<text text-anchor="middle" x="1084.3662" y="-1222.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure -->
<g id="node4" class="node">
<title>clinical_measure</title>
<path fill="none" stroke="#000000" d="M72.8662,-651C72.8662,-651 453.8662,-651 453.8662,-651 459.8662,-651 465.8662,-657 465.8662,-663 465.8662,-663 465.8662,-731 465.8662,-731 465.8662,-737 459.8662,-743 453.8662,-743 453.8662,-743 72.8662,-743 72.8662,-743 66.8662,-743 60.8662,-737 60.8662,-731 60.8662,-731 60.8662,-663 60.8662,-663 60.8662,-657 66.8662,-651 72.8662,-651"/>
<text text-anchor="middle" x="129.3662" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure</text>
<polyline fill="none" stroke="#000000" points="197.8662,-651 197.8662,-743 "/>
<text text-anchor="middle" x="208.3662" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="218.8662,-651 218.8662,-743 "/>
<text text-anchor="middle" x="331.8662" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_measure</text>
<polyline fill="none" stroke="#000000" points="218.8662,-720 444.8662,-720 "/>
<text text-anchor="middle" x="331.8662" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_description</text>
<polyline fill="none" stroke="#000000" points="218.8662,-697 444.8662,-697 "/>
<text text-anchor="middle" x="331.8662" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_id</text>
<polyline fill="none" stroke="#000000" points="218.8662,-674 444.8662,-674 "/>
<text text-anchor="middle" x="331.8662" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_measure</text>
<polyline fill="none" stroke="#000000" points="444.8662,-651 444.8662,-743 "/>
<text text-anchor="middle" x="455.3662" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure&#45;&gt;study -->
<g id="edge5" class="edge">
<title>clinical_measure&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M252.0085,-650.738C237.6808,-581.131 221.2624,-447.9461 278.3662,-357 297.5225,-326.4907 327.2173,-303.1893 358.7886,-285.6002"/>
<polygon fill="#000000" stroke="#000000" points="360.5858,-288.6078 367.7358,-280.7894 357.2708,-282.4425 360.5858,-288.6078"/>
<text text-anchor="middle" x="308.8662" y="-434.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- study_subject -->
<g id="node9" class="node">
<title>study_subject</title>
<path fill="none" stroke="#000000" d="M360.8662,-357.5C360.8662,-357.5 643.8662,-357.5 643.8662,-357.5 649.8662,-357.5 655.8662,-363.5 655.8662,-369.5 655.8662,-369.5 655.8662,-506.5 655.8662,-506.5 655.8662,-512.5 649.8662,-518.5 643.8662,-518.5 643.8662,-518.5 360.8662,-518.5 360.8662,-518.5 354.8662,-518.5 348.8662,-512.5 348.8662,-506.5 348.8662,-506.5 348.8662,-369.5 348.8662,-369.5 348.8662,-363.5 354.8662,-357.5 360.8662,-357.5"/>
<text text-anchor="middle" x="406.8662" y="-434.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_subject</text>
<polyline fill="none" stroke="#000000" points="464.8662,-357.5 464.8662,-518.5 "/>
<text text-anchor="middle" x="475.3662" y="-434.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="485.8662,-357.5 485.8662,-518.5 "/>
<text text-anchor="middle" x="560.3662" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_enrollment</text>
<polyline fill="none" stroke="#000000" points="485.8662,-495.5 634.8662,-495.5 "/>
<text text-anchor="middle" x="560.3662" y="-480.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_unit</text>
<polyline fill="none" stroke="#000000" points="485.8662,-472.5 634.8662,-472.5 "/>
<text text-anchor="middle" x="560.3662" y="-457.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="485.8662,-449.5 634.8662,-449.5 "/>
<text text-anchor="middle" x="560.3662" y="-434.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="485.8662,-426.5 634.8662,-426.5 "/>
<text text-anchor="middle" x="560.3662" y="-411.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="485.8662,-403.5 634.8662,-403.5 "/>
<text text-anchor="middle" x="560.3662" y="-388.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_subject_id</text>
<polyline fill="none" stroke="#000000" points="485.8662,-380.5 634.8662,-380.5 "/>
<text text-anchor="middle" x="560.3662" y="-365.3" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="634.8662,-357.5 634.8662,-518.5 "/>
<text text-anchor="middle" x="645.3662" y="-434.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure&#45;&gt;study_subject -->
<g id="edge14" class="edge">
<title>clinical_measure&#45;&gt;study_subject</title>
<path fill="none" stroke="#000000" d="M279.6413,-650.9964C293.462,-616.6909 315.9176,-570.2182 346.3662,-537 349.9323,-533.1095 353.6844,-529.3101 357.5839,-525.6063"/>
<polygon fill="#000000" stroke="#000000" points="360.2297,-527.93 365.2543,-518.6024 355.5096,-522.7607 360.2297,-527.93"/>
<text text-anchor="middle" x="417.3662" y="-540.8" font-family="Times,serif" font-size="14.00" fill="#000000">from_study_subject</text>
</g>
<!-- file&#45;&gt;study -->
<g id="edge4" class="edge">
<title>file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M394.6396,-948.2514C274.6854,-924.3679 92.2266,-879.88 51.3662,-824 -80.2144,-644.0529 64.5541,-501.424 234.3662,-357 270.3892,-326.3626 315.4639,-302.1133 358.3116,-283.6428"/>
<polygon fill="#000000" stroke="#000000" points="359.8568,-286.7895 367.7031,-279.6701 357.1296,-280.3426 359.8568,-286.7895"/>
<text text-anchor="middle" x="84.8662" y="-540.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- file&#45;&gt;clinical_measure -->
<g id="edge1" class="edge">
<title>file&#45;&gt;clinical_measure</title>
<path fill="none" stroke="#000000" d="M394.6867,-901.6088C377.3033,-888.1661 360.4256,-873.1431 346.3662,-857 319.6173,-826.2868 298.6134,-785.4467 284.4268,-752.7156"/>
<polygon fill="#000000" stroke="#000000" points="287.5513,-751.1183 280.426,-743.2773 281.1064,-753.8503 287.5513,-751.1183"/>
<text text-anchor="middle" x="417.3662" y="-845.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure</text>
</g>
<!-- experiment -->
<g id="node6" class="node">
<title>experiment</title>
<path fill="none" stroke="#000000" d="M696.3662,-415C696.3662,-415 964.3662,-415 964.3662,-415 970.3662,-415 976.3662,-421 976.3662,-427 976.3662,-427 976.3662,-449 976.3662,-449 976.3662,-455 970.3662,-461 964.3662,-461 964.3662,-461 696.3662,-461 696.3662,-461 690.3662,-461 684.3662,-455 684.3662,-449 684.3662,-449 684.3662,-427 684.3662,-427 684.3662,-421 690.3662,-415 696.3662,-415"/>
<text text-anchor="middle" x="733.3662" y="-434.3" font-family="Times,serif" font-size="14.00" fill="#000000">experiment</text>
<polyline fill="none" stroke="#000000" points="782.3662,-415 782.3662,-461 "/>
<text text-anchor="middle" x="792.8662" y="-434.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="803.3662,-415 803.3662,-461 "/>
<text text-anchor="middle" x="879.3662" y="-445.8" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="803.3662,-438 955.3662,-438 "/>
<text text-anchor="middle" x="879.3662" y="-422.8" font-family="Times,serif" font-size="14.00" fill="#000000">experiment_id</text>
<polyline fill="none" stroke="#000000" points="955.3662,-415 955.3662,-461 "/>
<text text-anchor="middle" x="965.8662" y="-434.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file&#45;&gt;experiment -->
<g id="edge11" class="edge">
<title>file&#45;&gt;experiment</title>
<path fill="none" stroke="#000000" d="M610.0482,-953.5992C748.938,-933.2054 978.738,-890.2573 1029.3662,-824 1097.907,-734.3002 1082.7492,-669.4693 1029.3662,-570 1013.4281,-540.3024 937.4605,-495.0807 884.1459,-466.0345"/>
<polygon fill="#000000" stroke="#000000" points="885.5975,-462.8405 875.1365,-461.162 882.2675,-468.9977 885.5975,-462.8405"/>
<text text-anchor="middle" x="1125.8662" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_experiment</text>
</g>
<!-- file&#45;&gt;study_subject -->
<g id="edge13" class="edge">
<title>file&#45;&gt;study_subject</title>
<path fill="none" stroke="#000000" d="M502.3662,-875.2681C502.3662,-777.9697 502.3662,-625.609 502.3662,-528.8397"/>
<polygon fill="#000000" stroke="#000000" points="505.8663,-528.7797 502.3662,-518.7797 498.8663,-528.7798 505.8663,-528.7797"/>
<text text-anchor="middle" x="573.3662" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">from_study_subject</text>
</g>
<!-- sample -->
<g id="node12" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M674.3662,-570.5C674.3662,-570.5 1008.3662,-570.5 1008.3662,-570.5 1014.3662,-570.5 1020.3662,-576.5 1020.3662,-582.5 1020.3662,-582.5 1020.3662,-811.5 1020.3662,-811.5 1020.3662,-817.5 1014.3662,-823.5 1008.3662,-823.5 1008.3662,-823.5 674.3662,-823.5 674.3662,-823.5 668.3662,-823.5 662.3662,-817.5 662.3662,-811.5 662.3662,-811.5 662.3662,-582.5 662.3662,-582.5 662.3662,-576.5 668.3662,-570.5 674.3662,-570.5"/>
<text text-anchor="middle" x="696.3662" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="730.3662,-570.5 730.3662,-823.5 "/>
<text text-anchor="middle" x="740.8662" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="751.3662,-570.5 751.3662,-823.5 "/>
<text text-anchor="middle" x="875.3662" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="751.3662,-800.5 999.3662,-800.5 "/>
<text text-anchor="middle" x="875.3662" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_sample_id</text>
<polyline fill="none" stroke="#000000" points="751.3662,-777.5 999.3662,-777.5 "/>
<text text-anchor="middle" x="875.3662" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="751.3662,-754.5 999.3662,-754.5 "/>
<text text-anchor="middle" x="875.3662" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="751.3662,-731.5 999.3662,-731.5 "/>
<text text-anchor="middle" x="875.3662" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="751.3662,-708.5 999.3662,-708.5 "/>
<text text-anchor="middle" x="875.3662" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_subject_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="751.3662,-685.5 999.3662,-685.5 "/>
<text text-anchor="middle" x="875.3662" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="751.3662,-662.5 999.3662,-662.5 "/>
<text text-anchor="middle" x="875.3662" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="751.3662,-639.5 999.3662,-639.5 "/>
<text text-anchor="middle" x="875.3662" y="-624.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="751.3662,-616.5 999.3662,-616.5 "/>
<text text-anchor="middle" x="875.3662" y="-601.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage</text>
<polyline fill="none" stroke="#000000" points="751.3662,-593.5 999.3662,-593.5 "/>
<text text-anchor="middle" x="875.3662" y="-578.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_status</text>
<polyline fill="none" stroke="#000000" points="999.3662,-570.5 999.3662,-823.5 "/>
<text text-anchor="middle" x="1009.8662" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M610.0937,-881.5404C630.6414,-865.1447 652.5922,-847.6294 674.4848,-830.1605"/>
<polygon fill="#000000" stroke="#000000" points="676.9115,-832.7018 682.5451,-823.7289 672.5455,-827.2302 676.9115,-832.7018"/>
<text text-anchor="middle" x="698.8662" y="-845.8" font-family="Times,serif" font-size="14.00" fill="#000000">from_sample</text>
</g>
<!-- experiment&#45;&gt;study -->
<g id="edge2" class="edge">
<title>experiment&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M792.7404,-414.8854C751.602,-389.6128 683.5449,-347.8034 623.6557,-311.0117"/>
<polygon fill="#000000" stroke="#000000" points="625.2357,-307.8747 614.883,-305.6224 621.5716,-313.8391 625.2357,-307.8747"/>
<text text-anchor="middle" x="696.8662" y="-327.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- imaging_detail -->
<g id="node7" class="node">
<title>imaging_detail</title>
<path fill="none" stroke="#000000" d="M548.8662,-1169C548.8662,-1169 835.8662,-1169 835.8662,-1169 841.8662,-1169 847.8662,-1175 847.8662,-1181 847.8662,-1181 847.8662,-1272 847.8662,-1272 847.8662,-1278 841.8662,-1284 835.8662,-1284 835.8662,-1284 548.8662,-1284 548.8662,-1284 542.8662,-1284 536.8662,-1278 536.8662,-1272 536.8662,-1272 536.8662,-1181 536.8662,-1181 536.8662,-1175 542.8662,-1169 548.8662,-1169"/>
<text text-anchor="middle" x="597.8662" y="-1222.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_detail</text>
<polyline fill="none" stroke="#000000" points="658.8662,-1169 658.8662,-1284 "/>
<text text-anchor="middle" x="669.3662" y="-1222.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="679.8662,-1169 679.8662,-1284 "/>
<text text-anchor="middle" x="753.3662" y="-1268.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="679.8662,-1261 826.8662,-1261 "/>
<text text-anchor="middle" x="753.3662" y="-1245.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_detail_id</text>
<polyline fill="none" stroke="#000000" points="679.8662,-1238 826.8662,-1238 "/>
<text text-anchor="middle" x="753.3662" y="-1222.8" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="679.8662,-1215 826.8662,-1215 "/>
<text text-anchor="middle" x="753.3662" y="-1199.8" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="679.8662,-1192 826.8662,-1192 "/>
<text text-anchor="middle" x="753.3662" y="-1176.8" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="826.8662,-1169 826.8662,-1284 "/>
<text text-anchor="middle" x="837.3662" y="-1222.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_detail&#45;&gt;file -->
<g id="edge8" class="edge">
<title>imaging_detail&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M649.9629,-1168.6977C628.1937,-1139.0227 601.0438,-1102.0132 575.9868,-1067.8566"/>
<polygon fill="#000000" stroke="#000000" points="578.7418,-1065.6948 570.0046,-1059.7019 573.0976,-1069.8353 578.7418,-1065.6948"/>
<text text-anchor="middle" x="614.3662" y="-1081.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- study_subject&#45;&gt;study -->
<g id="edge6" class="edge">
<title>study_subject&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M502.3662,-357.4932C502.3662,-343.7786 502.3662,-329.5421 502.3662,-315.8576"/>
<polygon fill="#000000" stroke="#000000" points="505.8663,-315.5183 502.3662,-305.5184 498.8663,-315.5184 505.8663,-315.5183"/>
<text text-anchor="middle" x="532.8662" y="-327.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- study_admin -->
<g id="node10" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M1006.8662,-369C1006.8662,-369 1277.8662,-369 1277.8662,-369 1283.8662,-369 1289.8662,-375 1289.8662,-381 1289.8662,-381 1289.8662,-495 1289.8662,-495 1289.8662,-501 1283.8662,-507 1277.8662,-507 1277.8662,-507 1006.8662,-507 1006.8662,-507 1000.8662,-507 994.8662,-501 994.8662,-495 994.8662,-495 994.8662,-381 994.8662,-381 994.8662,-375 1000.8662,-369 1006.8662,-369"/>
<text text-anchor="middle" x="1048.8662" y="-434.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="1102.8662,-369 1102.8662,-507 "/>
<text text-anchor="middle" x="1113.3662" y="-434.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1123.8662,-369 1123.8662,-507 "/>
<text text-anchor="middle" x="1196.3662" y="-491.8" font-family="Times,serif" font-size="14.00" fill="#000000">data_access_level</text>
<polyline fill="none" stroke="#000000" points="1123.8662,-484 1268.8662,-484 "/>
<text text-anchor="middle" x="1196.3662" y="-468.8" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="1123.8662,-461 1268.8662,-461 "/>
<text text-anchor="middle" x="1196.3662" y="-445.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_types</text>
<polyline fill="none" stroke="#000000" points="1123.8662,-438 1268.8662,-438 "/>
<text text-anchor="middle" x="1196.3662" y="-422.8" font-family="Times,serif" font-size="14.00" fill="#000000">species</text>
<polyline fill="none" stroke="#000000" points="1123.8662,-415 1268.8662,-415 "/>
<text text-anchor="middle" x="1196.3662" y="-399.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="1123.8662,-392 1268.8662,-392 "/>
<text text-anchor="middle" x="1196.3662" y="-376.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_type</text>
<polyline fill="none" stroke="#000000" points="1268.8662,-369 1268.8662,-507 "/>
<text text-anchor="middle" x="1279.3662" y="-434.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge3" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1014.0803,-368.816C1004.4755,-364.5643 994.8373,-360.5693 985.3662,-357 874.7316,-315.3065 744.4119,-283.7631 647.039,-263.4278"/>
<polygon fill="#000000" stroke="#000000" points="647.6277,-259.9755 637.1253,-261.3724 646.2065,-266.8297 647.6277,-259.9755"/>
<text text-anchor="middle" x="964.8662" y="-327.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- sample&#45;&gt;experiment -->
<g id="edge12" class="edge">
<title>sample&#45;&gt;experiment</title>
<path fill="none" stroke="#000000" d="M835.9789,-570.1556C834.4262,-533.5951 832.8614,-496.7523 831.78,-471.2899"/>
<polygon fill="#000000" stroke="#000000" points="835.2689,-470.9506 831.3476,-461.1082 828.2752,-471.2477 835.2689,-470.9506"/>
<text text-anchor="middle" x="886.8662" y="-540.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_experiment</text>
</g>
<!-- sample&#45;&gt;study_subject -->
<g id="edge16" class="edge">
<title>sample&#45;&gt;study_subject</title>
<path fill="none" stroke="#000000" d="M675.342,-570.1556C655.2319,-554.7912 635.0565,-539.377 615.9488,-524.7785"/>
<polygon fill="#000000" stroke="#000000" points="617.8996,-521.8643 607.8285,-518.5745 613.6499,-527.4267 617.8996,-521.8643"/>
<text text-anchor="middle" x="712.8662" y="-540.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_subject</text>
</g>
</g>
</svg>
</div>
