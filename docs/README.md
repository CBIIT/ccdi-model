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
<svg width="3143pt" height="1735pt"
 viewBox="0.00 0.00 3143.28 1735.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1731)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1731 3139.2805,-1731 3139.2805,4 -4,4"/>
<!-- therapeutic_procedure -->
<g id="node1" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M471.7805,-846.5C471.7805,-846.5 863.7805,-846.5 863.7805,-846.5 869.7805,-846.5 875.7805,-852.5 875.7805,-858.5 875.7805,-858.5 875.7805,-949.5 875.7805,-949.5 875.7805,-955.5 869.7805,-961.5 863.7805,-961.5 863.7805,-961.5 471.7805,-961.5 471.7805,-961.5 465.7805,-961.5 459.7805,-955.5 459.7805,-949.5 459.7805,-949.5 459.7805,-858.5 459.7805,-858.5 459.7805,-852.5 465.7805,-846.5 471.7805,-846.5"/>
<text text-anchor="middle" x="550.2805" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="640.7805,-846.5 640.7805,-961.5 "/>
<text text-anchor="middle" x="651.2805" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="661.7805,-846.5 661.7805,-961.5 "/>
<text text-anchor="middle" x="758.2805" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment_start</text>
<polyline fill="none" stroke="#000000" points="661.7805,-938.5 854.7805,-938.5 "/>
<text text-anchor="middle" x="758.2805" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="661.7805,-915.5 854.7805,-915.5 "/>
<text text-anchor="middle" x="758.2805" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="661.7805,-892.5 854.7805,-892.5 "/>
<text text-anchor="middle" x="758.2805" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="661.7805,-869.5 854.7805,-869.5 "/>
<text text-anchor="middle" x="758.2805" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="854.7805,-846.5 854.7805,-961.5 "/>
<text text-anchor="middle" x="865.2805" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node5" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M910.7805,-541.5C910.7805,-541.5 1214.7805,-541.5 1214.7805,-541.5 1220.7805,-541.5 1226.7805,-547.5 1226.7805,-553.5 1226.7805,-553.5 1226.7805,-644.5 1226.7805,-644.5 1226.7805,-650.5 1220.7805,-656.5 1214.7805,-656.5 1214.7805,-656.5 910.7805,-656.5 910.7805,-656.5 904.7805,-656.5 898.7805,-650.5 898.7805,-644.5 898.7805,-644.5 898.7805,-553.5 898.7805,-553.5 898.7805,-547.5 904.7805,-541.5 910.7805,-541.5"/>
<text text-anchor="middle" x="946.7805" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="994.7805,-541.5 994.7805,-656.5 "/>
<text text-anchor="middle" x="1005.2805" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1015.7805,-541.5 1015.7805,-656.5 "/>
<text text-anchor="middle" x="1110.7805" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="1015.7805,-633.5 1205.7805,-633.5 "/>
<text text-anchor="middle" x="1110.7805" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="1015.7805,-610.5 1205.7805,-610.5 "/>
<text text-anchor="middle" x="1110.7805" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="1015.7805,-587.5 1205.7805,-587.5 "/>
<text text-anchor="middle" x="1110.7805" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1015.7805,-564.5 1205.7805,-564.5 "/>
<text text-anchor="middle" x="1110.7805" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1205.7805,-541.5 1205.7805,-656.5 "/>
<text text-anchor="middle" x="1216.2805" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M662.4537,-846.4025C661.0287,-794.609 667.8608,-719.9599 711.7805,-675 737.424,-648.7491 813.6991,-630.5705 888.6207,-618.591"/>
<polygon fill="#000000" stroke="#000000" points="889.3602,-622.018 898.6993,-617.0147 888.2786,-615.102 889.3602,-622.018"/>
<text text-anchor="middle" x="804.7805" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- synonym -->
<g id="node2" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M679.2805,-1416C679.2805,-1416 980.2805,-1416 980.2805,-1416 986.2805,-1416 992.2805,-1422 992.2805,-1428 992.2805,-1428 992.2805,-1450 992.2805,-1450 992.2805,-1456 986.2805,-1462 980.2805,-1462 980.2805,-1462 679.2805,-1462 679.2805,-1462 673.2805,-1462 667.2805,-1456 667.2805,-1450 667.2805,-1450 667.2805,-1428 667.2805,-1428 667.2805,-1422 673.2805,-1416 679.2805,-1416"/>
<text text-anchor="middle" x="707.2805" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="747.2805,-1416 747.2805,-1462 "/>
<text text-anchor="middle" x="757.7805" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="768.2805,-1416 768.2805,-1462 "/>
<text text-anchor="middle" x="869.7805" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="768.2805,-1439 971.2805,-1439 "/>
<text text-anchor="middle" x="869.7805" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="971.2805,-1416 971.2805,-1462 "/>
<text text-anchor="middle" x="981.7805" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M834.1411,-1415.6544C844.2667,-1360.7717 869.6576,-1219.1862 884.7805,-1100 895.7917,-1013.2181 878.5461,-784.6068 920.7805,-708 929.9802,-691.3131 942.9185,-676.3669 957.2769,-663.2848"/>
<polygon fill="#000000" stroke="#000000" points="959.6802,-665.8326 964.9026,-656.6142 955.0715,-660.5639 959.6802,-665.8326"/>
<text text-anchor="middle" x="963.2805" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study -->
<g id="node11" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M626.7805,-.5C626.7805,-.5 1016.7805,-.5 1016.7805,-.5 1022.7805,-.5 1028.7805,-6.5 1028.7805,-12.5 1028.7805,-12.5 1028.7805,-264.5 1028.7805,-264.5 1028.7805,-270.5 1022.7805,-276.5 1016.7805,-276.5 1016.7805,-276.5 626.7805,-276.5 626.7805,-276.5 620.7805,-276.5 614.7805,-270.5 614.7805,-264.5 614.7805,-264.5 614.7805,-12.5 614.7805,-12.5 614.7805,-6.5 620.7805,-.5 626.7805,-.5"/>
<text text-anchor="middle" x="642.7805" y="-134.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="670.7805,-.5 670.7805,-276.5 "/>
<text text-anchor="middle" x="681.2805" y="-134.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="691.7805,-.5 691.7805,-276.5 "/>
<text text-anchor="middle" x="849.7805" y="-261.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="691.7805,-253.5 1007.7805,-253.5 "/>
<text text-anchor="middle" x="849.7805" y="-238.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="691.7805,-230.5 1007.7805,-230.5 "/>
<text text-anchor="middle" x="849.7805" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_shorthand</text>
<polyline fill="none" stroke="#000000" points="691.7805,-207.5 1007.7805,-207.5 "/>
<text text-anchor="middle" x="849.7805" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="691.7805,-184.5 1007.7805,-184.5 "/>
<text text-anchor="middle" x="849.7805" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="691.7805,-161.5 1007.7805,-161.5 "/>
<text text-anchor="middle" x="849.7805" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="691.7805,-138.5 1007.7805,-138.5 "/>
<text text-anchor="middle" x="849.7805" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="691.7805,-115.5 1007.7805,-115.5 "/>
<text text-anchor="middle" x="849.7805" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="691.7805,-92.5 1007.7805,-92.5 "/>
<text text-anchor="middle" x="849.7805" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="691.7805,-69.5 1007.7805,-69.5 "/>
<text text-anchor="middle" x="849.7805" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="691.7805,-46.5 1007.7805,-46.5 "/>
<text text-anchor="middle" x="849.7805" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="691.7805,-23.5 1007.7805,-23.5 "/>
<text text-anchor="middle" x="849.7805" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="1007.7805,-.5 1007.7805,-276.5 "/>
<text text-anchor="middle" x="1018.2805" y="-134.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge12" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M693.0243,-1415.9361C519.7666,-1379.5155 223.6924,-1292.0276 56.7805,-1100 -2.574,-1031.7144 1.7805,-994.4758 1.7805,-904 1.7805,-904 1.7805,-904 1.7805,-409 1.7805,-372.0229 -5.3414,-354.1717 20.7805,-328 101.7911,-246.8348 396.0598,-192.9574 604.3453,-164.0544"/>
<polygon fill="#000000" stroke="#000000" points="605.0793,-167.4864 614.5081,-162.6544 604.124,-160.5519 605.0793,-167.4864"/>
<text text-anchor="middle" x="44.2805" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- sample -->
<g id="node16" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1854.7805,-823.5C1854.7805,-823.5 2168.7805,-823.5 2168.7805,-823.5 2174.7805,-823.5 2180.7805,-829.5 2180.7805,-835.5 2180.7805,-835.5 2180.7805,-972.5 2180.7805,-972.5 2180.7805,-978.5 2174.7805,-984.5 2168.7805,-984.5 2168.7805,-984.5 1854.7805,-984.5 1854.7805,-984.5 1848.7805,-984.5 1842.7805,-978.5 1842.7805,-972.5 1842.7805,-972.5 1842.7805,-835.5 1842.7805,-835.5 1842.7805,-829.5 1848.7805,-823.5 1854.7805,-823.5"/>
<text text-anchor="middle" x="1876.7805" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1910.7805,-823.5 1910.7805,-984.5 "/>
<text text-anchor="middle" x="1921.2805" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1931.7805,-823.5 1931.7805,-984.5 "/>
<text text-anchor="middle" x="2045.7805" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="1931.7805,-961.5 2159.7805,-961.5 "/>
<text text-anchor="middle" x="2045.7805" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1931.7805,-938.5 2159.7805,-938.5 "/>
<text text-anchor="middle" x="2045.7805" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1931.7805,-915.5 2159.7805,-915.5 "/>
<text text-anchor="middle" x="2045.7805" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1931.7805,-892.5 2159.7805,-892.5 "/>
<text text-anchor="middle" x="2045.7805" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1931.7805,-869.5 2159.7805,-869.5 "/>
<text text-anchor="middle" x="2045.7805" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1931.7805,-846.5 2159.7805,-846.5 "/>
<text text-anchor="middle" x="2045.7805" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="2159.7805,-823.5 2159.7805,-984.5 "/>
<text text-anchor="middle" x="2170.2805" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M835.7107,-1415.9628C851.6093,-1359.4297 900.9818,-1213.8846 1001.7805,-1151 1151.622,-1057.5194 1221.512,-1128.9783 1397.7805,-1118 1446.1724,-1114.9861 1789.8589,-1120.5368 1833.7805,-1100 1883.2594,-1076.8648 1925.1559,-1032.9776 1955.8487,-992.5881"/>
<polygon fill="#000000" stroke="#000000" points="1958.661,-994.6717 1961.8368,-984.5641 1953.0509,-990.4851 1958.661,-994.6717"/>
<text text-anchor="middle" x="1440.2805" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study_personnel -->
<g id="node3" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M42.2805,-351.5C42.2805,-351.5 349.2805,-351.5 349.2805,-351.5 355.2805,-351.5 361.2805,-357.5 361.2805,-363.5 361.2805,-363.5 361.2805,-454.5 361.2805,-454.5 361.2805,-460.5 355.2805,-466.5 349.2805,-466.5 349.2805,-466.5 42.2805,-466.5 42.2805,-466.5 36.2805,-466.5 30.2805,-460.5 30.2805,-454.5 30.2805,-454.5 30.2805,-363.5 30.2805,-363.5 30.2805,-357.5 36.2805,-351.5 42.2805,-351.5"/>
<text text-anchor="middle" x="97.2805" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="164.2805,-351.5 164.2805,-466.5 "/>
<text text-anchor="middle" x="174.7805" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="185.2805,-351.5 185.2805,-466.5 "/>
<text text-anchor="middle" x="262.7805" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="185.2805,-443.5 340.2805,-443.5 "/>
<text text-anchor="middle" x="262.7805" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="185.2805,-420.5 340.2805,-420.5 "/>
<text text-anchor="middle" x="262.7805" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="185.2805,-397.5 340.2805,-397.5 "/>
<text text-anchor="middle" x="262.7805" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="185.2805,-374.5 340.2805,-374.5 "/>
<text text-anchor="middle" x="262.7805" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="340.2805,-351.5 340.2805,-466.5 "/>
<text text-anchor="middle" x="350.7805" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge10" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M205.1214,-351.2258C211.0816,-330.9814 220.8333,-309.6631 236.7805,-295 291.1088,-245.046 461.8022,-202.8129 604.8828,-174.8571"/>
<polygon fill="#000000" stroke="#000000" points="605.5495,-178.2931 614.7,-172.9527 604.2164,-171.4212 605.5495,-178.2931"/>
<text text-anchor="middle" x="306.2805" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- clinical_measure_file -->
<g id="node4" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M77.7805,-777.5C77.7805,-777.5 429.7805,-777.5 429.7805,-777.5 435.7805,-777.5 441.7805,-783.5 441.7805,-789.5 441.7805,-789.5 441.7805,-1018.5 441.7805,-1018.5 441.7805,-1024.5 435.7805,-1030.5 429.7805,-1030.5 429.7805,-1030.5 77.7805,-1030.5 77.7805,-1030.5 71.7805,-1030.5 65.7805,-1024.5 65.7805,-1018.5 65.7805,-1018.5 65.7805,-789.5 65.7805,-789.5 65.7805,-783.5 71.7805,-777.5 77.7805,-777.5"/>
<text text-anchor="middle" x="149.2805" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="232.7805,-777.5 232.7805,-1030.5 "/>
<text text-anchor="middle" x="243.2805" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="253.7805,-777.5 253.7805,-1030.5 "/>
<text text-anchor="middle" x="337.2805" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="253.7805,-1007.5 420.7805,-1007.5 "/>
<text text-anchor="middle" x="337.2805" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="253.7805,-984.5 420.7805,-984.5 "/>
<text text-anchor="middle" x="337.2805" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="253.7805,-961.5 420.7805,-961.5 "/>
<text text-anchor="middle" x="337.2805" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="253.7805,-938.5 420.7805,-938.5 "/>
<text text-anchor="middle" x="337.2805" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="253.7805,-915.5 420.7805,-915.5 "/>
<text text-anchor="middle" x="337.2805" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="253.7805,-892.5 420.7805,-892.5 "/>
<text text-anchor="middle" x="337.2805" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="253.7805,-869.5 420.7805,-869.5 "/>
<text text-anchor="middle" x="337.2805" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="253.7805,-846.5 420.7805,-846.5 "/>
<text text-anchor="middle" x="337.2805" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="253.7805,-823.5 420.7805,-823.5 "/>
<text text-anchor="middle" x="337.2805" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="253.7805,-800.5 420.7805,-800.5 "/>
<text text-anchor="middle" x="337.2805" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="420.7805,-777.5 420.7805,-1030.5 "/>
<text text-anchor="middle" x="431.2805" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M327.8382,-777.4395C357.0861,-738.3403 394.21,-699.2269 437.7805,-675 512.7972,-633.2878 730.9971,-614.1516 888.4657,-605.5903"/>
<polygon fill="#000000" stroke="#000000" points="888.9487,-609.0695 898.7479,-605.0415 888.5756,-602.0795 888.9487,-609.0695"/>
<text text-anchor="middle" x="567.2805" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge17" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M271.3486,-777.1493C285.9838,-696.8088 311.6142,-592.5108 354.7805,-508 359.5174,-498.7261 363.5859,-498.3709 369.7805,-490 420.9629,-420.8349 417.6281,-391.4173 475.7805,-328 512.0574,-288.4387 558.5505,-255.3396 605.6047,-228.454"/>
<polygon fill="#000000" stroke="#000000" points="607.3975,-231.4613 614.3949,-223.506 603.9638,-225.3612 607.3975,-231.4613"/>
<text text-anchor="middle" x="440.7805" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge15" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M898.4442,-589.147C753.6237,-576.6258 558.3302,-549.0534 509.7805,-490 464.0558,-434.383 474.4755,-390.75 509.7805,-328 532.3874,-287.819 567.341,-255.1718 605.7985,-229.0214"/>
<polygon fill="#000000" stroke="#000000" points="608.1798,-231.642 614.5805,-223.1991 604.3118,-225.8078 608.1798,-231.642"/>
<text text-anchor="middle" x="560.2805" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_arm -->
<g id="node17" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M1674.2805,-374.5C1674.2805,-374.5 1971.2805,-374.5 1971.2805,-374.5 1977.2805,-374.5 1983.2805,-380.5 1983.2805,-386.5 1983.2805,-386.5 1983.2805,-431.5 1983.2805,-431.5 1983.2805,-437.5 1977.2805,-443.5 1971.2805,-443.5 1971.2805,-443.5 1674.2805,-443.5 1674.2805,-443.5 1668.2805,-443.5 1662.2805,-437.5 1662.2805,-431.5 1662.2805,-431.5 1662.2805,-386.5 1662.2805,-386.5 1662.2805,-380.5 1668.2805,-374.5 1674.2805,-374.5"/>
<text text-anchor="middle" x="1708.2805" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="1754.2805,-374.5 1754.2805,-443.5 "/>
<text text-anchor="middle" x="1764.7805" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1775.2805,-374.5 1775.2805,-443.5 "/>
<text text-anchor="middle" x="1868.7805" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="1775.2805,-420.5 1962.2805,-420.5 "/>
<text text-anchor="middle" x="1868.7805" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="1775.2805,-397.5 1962.2805,-397.5 "/>
<text text-anchor="middle" x="1868.7805" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="1962.2805,-374.5 1962.2805,-443.5 "/>
<text text-anchor="middle" x="1972.7805" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge16" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1226.8259,-580.4264C1346.8204,-564.0326 1512.4561,-535.5177 1652.7805,-490 1686.1765,-479.1671 1721.4695,-463.1689 1751.1911,-448.2453"/>
<polygon fill="#000000" stroke="#000000" points="1752.897,-451.3044 1760.2278,-443.6552 1749.727,-445.0634 1752.897,-451.3044"/>
<text text-anchor="middle" x="1640.2805" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- imaging_file -->
<g id="node6" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M1022.7805,-1278C1022.7805,-1278 1356.7805,-1278 1356.7805,-1278 1362.7805,-1278 1368.7805,-1284 1368.7805,-1290 1368.7805,-1290 1368.7805,-1588 1368.7805,-1588 1368.7805,-1594 1362.7805,-1600 1356.7805,-1600 1356.7805,-1600 1022.7805,-1600 1022.7805,-1600 1016.7805,-1600 1010.7805,-1594 1010.7805,-1588 1010.7805,-1588 1010.7805,-1290 1010.7805,-1290 1010.7805,-1284 1016.7805,-1278 1022.7805,-1278"/>
<text text-anchor="middle" x="1062.7805" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="1114.7805,-1278 1114.7805,-1600 "/>
<text text-anchor="middle" x="1125.2805" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1135.7805,-1278 1135.7805,-1600 "/>
<text text-anchor="middle" x="1241.7805" y="-1584.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1135.7805,-1577 1347.7805,-1577 "/>
<text text-anchor="middle" x="1241.7805" y="-1561.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1135.7805,-1554 1347.7805,-1554 "/>
<text text-anchor="middle" x="1241.7805" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1135.7805,-1531 1347.7805,-1531 "/>
<text text-anchor="middle" x="1241.7805" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1135.7805,-1508 1347.7805,-1508 "/>
<text text-anchor="middle" x="1241.7805" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1135.7805,-1485 1347.7805,-1485 "/>
<text text-anchor="middle" x="1241.7805" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1135.7805,-1462 1347.7805,-1462 "/>
<text text-anchor="middle" x="1241.7805" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1135.7805,-1439 1347.7805,-1439 "/>
<text text-anchor="middle" x="1241.7805" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1135.7805,-1416 1347.7805,-1416 "/>
<text text-anchor="middle" x="1241.7805" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1135.7805,-1393 1347.7805,-1393 "/>
<text text-anchor="middle" x="1241.7805" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="1135.7805,-1370 1347.7805,-1370 "/>
<text text-anchor="middle" x="1241.7805" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="1135.7805,-1347 1347.7805,-1347 "/>
<text text-anchor="middle" x="1241.7805" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="1135.7805,-1324 1347.7805,-1324 "/>
<text text-anchor="middle" x="1241.7805" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1135.7805,-1301 1347.7805,-1301 "/>
<text text-anchor="middle" x="1241.7805" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="1347.7805,-1278 1347.7805,-1600 "/>
<text text-anchor="middle" x="1358.2805" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1261.4209,-1277.7167C1290.849,-1229.3123 1329.732,-1181.1279 1378.7805,-1151 1422.1281,-1124.3737 1788.4835,-1123.1551 1833.7805,-1100 1881.5437,-1075.5842 1922.7498,-1032.6988 1953.4517,-993.2565"/>
<polygon fill="#000000" stroke="#000000" points="1956.5477,-994.9697 1959.8423,-984.9001 1950.9873,-990.7173 1956.5477,-994.9697"/>
<text text-anchor="middle" x="1744.2805" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- study_funding -->
<g id="node7" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M632.2805,-374.5C632.2805,-374.5 1011.2805,-374.5 1011.2805,-374.5 1017.2805,-374.5 1023.2805,-380.5 1023.2805,-386.5 1023.2805,-386.5 1023.2805,-431.5 1023.2805,-431.5 1023.2805,-437.5 1017.2805,-443.5 1011.2805,-443.5 1011.2805,-443.5 632.2805,-443.5 632.2805,-443.5 626.2805,-443.5 620.2805,-437.5 620.2805,-431.5 620.2805,-431.5 620.2805,-386.5 620.2805,-386.5 620.2805,-380.5 626.2805,-374.5 632.2805,-374.5"/>
<text text-anchor="middle" x="679.7805" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="739.2805,-374.5 739.2805,-443.5 "/>
<text text-anchor="middle" x="749.7805" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="760.2805,-374.5 760.2805,-443.5 "/>
<text text-anchor="middle" x="881.2805" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="760.2805,-420.5 1002.2805,-420.5 "/>
<text text-anchor="middle" x="881.2805" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="760.2805,-397.5 1002.2805,-397.5 "/>
<text text-anchor="middle" x="881.2805" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="1002.2805,-374.5 1002.2805,-443.5 "/>
<text text-anchor="middle" x="1012.7805" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge2" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M821.7805,-374.4662C821.7805,-351.5553 821.7805,-319.7488 821.7805,-286.8978"/>
<polygon fill="#000000" stroke="#000000" points="825.2806,-286.6778 821.7805,-276.6779 818.2806,-286.6779 825.2806,-286.6778"/>
<text text-anchor="middle" x="883.7805" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- study_admin -->
<g id="node8" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M1053.7805,-328.5C1053.7805,-328.5 1379.7805,-328.5 1379.7805,-328.5 1385.7805,-328.5 1391.7805,-334.5 1391.7805,-340.5 1391.7805,-340.5 1391.7805,-477.5 1391.7805,-477.5 1391.7805,-483.5 1385.7805,-489.5 1379.7805,-489.5 1379.7805,-489.5 1053.7805,-489.5 1053.7805,-489.5 1047.7805,-489.5 1041.7805,-483.5 1041.7805,-477.5 1041.7805,-477.5 1041.7805,-340.5 1041.7805,-340.5 1041.7805,-334.5 1047.7805,-328.5 1053.7805,-328.5"/>
<text text-anchor="middle" x="1095.7805" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="1149.7805,-328.5 1149.7805,-489.5 "/>
<text text-anchor="middle" x="1160.2805" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1170.7805,-328.5 1170.7805,-489.5 "/>
<text text-anchor="middle" x="1270.7805" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="1170.7805,-466.5 1370.7805,-466.5 "/>
<text text-anchor="middle" x="1270.7805" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="1170.7805,-443.5 1370.7805,-443.5 "/>
<text text-anchor="middle" x="1270.7805" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="1170.7805,-420.5 1370.7805,-420.5 "/>
<text text-anchor="middle" x="1270.7805" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="1170.7805,-397.5 1370.7805,-397.5 "/>
<text text-anchor="middle" x="1270.7805" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="1170.7805,-374.5 1370.7805,-374.5 "/>
<text text-anchor="middle" x="1270.7805" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="1170.7805,-351.5 1370.7805,-351.5 "/>
<text text-anchor="middle" x="1270.7805" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="1370.7805,-328.5 1370.7805,-489.5 "/>
<text text-anchor="middle" x="1381.2805" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1099.0698,-328.3905C1077.807,-313.8295 1055.0609,-298.2528 1032.0828,-282.5172"/>
<polygon fill="#000000" stroke="#000000" points="1033.8374,-279.4767 1023.609,-276.7142 1029.8822,-285.2523 1033.8374,-279.4767"/>
<text text-anchor="middle" x="1123.2805" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- sequencing_file -->
<g id="node9" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M1399.2805,-1151.5C1399.2805,-1151.5 1868.2805,-1151.5 1868.2805,-1151.5 1874.2805,-1151.5 1880.2805,-1157.5 1880.2805,-1163.5 1880.2805,-1163.5 1880.2805,-1714.5 1880.2805,-1714.5 1880.2805,-1720.5 1874.2805,-1726.5 1868.2805,-1726.5 1868.2805,-1726.5 1399.2805,-1726.5 1399.2805,-1726.5 1393.2805,-1726.5 1387.2805,-1720.5 1387.2805,-1714.5 1387.2805,-1714.5 1387.2805,-1163.5 1387.2805,-1163.5 1387.2805,-1157.5 1393.2805,-1151.5 1399.2805,-1151.5"/>
<text text-anchor="middle" x="1451.2805" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="1515.2805,-1151.5 1515.2805,-1726.5 "/>
<text text-anchor="middle" x="1525.7805" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1536.2805,-1151.5 1536.2805,-1726.5 "/>
<text text-anchor="middle" x="1697.7805" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="1536.2805,-1703.5 1859.2805,-1703.5 "/>
<text text-anchor="middle" x="1697.7805" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1536.2805,-1680.5 1859.2805,-1680.5 "/>
<text text-anchor="middle" x="1697.7805" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1536.2805,-1657.5 1859.2805,-1657.5 "/>
<text text-anchor="middle" x="1697.7805" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="1536.2805,-1634.5 1859.2805,-1634.5 "/>
<text text-anchor="middle" x="1697.7805" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="1536.2805,-1611.5 1859.2805,-1611.5 "/>
<text text-anchor="middle" x="1697.7805" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1536.2805,-1588.5 1859.2805,-1588.5 "/>
<text text-anchor="middle" x="1697.7805" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="1536.2805,-1565.5 1859.2805,-1565.5 "/>
<text text-anchor="middle" x="1697.7805" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1536.2805,-1542.5 1859.2805,-1542.5 "/>
<text text-anchor="middle" x="1697.7805" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1536.2805,-1519.5 1859.2805,-1519.5 "/>
<text text-anchor="middle" x="1697.7805" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1536.2805,-1496.5 1859.2805,-1496.5 "/>
<text text-anchor="middle" x="1697.7805" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1536.2805,-1473.5 1859.2805,-1473.5 "/>
<text text-anchor="middle" x="1697.7805" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1536.2805,-1450.5 1859.2805,-1450.5 "/>
<text text-anchor="middle" x="1697.7805" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1536.2805,-1427.5 1859.2805,-1427.5 "/>
<text text-anchor="middle" x="1697.7805" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="1536.2805,-1404.5 1859.2805,-1404.5 "/>
<text text-anchor="middle" x="1697.7805" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="1536.2805,-1381.5 1859.2805,-1381.5 "/>
<text text-anchor="middle" x="1697.7805" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="1536.2805,-1358.5 1859.2805,-1358.5 "/>
<text text-anchor="middle" x="1697.7805" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="1536.2805,-1335.5 1859.2805,-1335.5 "/>
<text text-anchor="middle" x="1697.7805" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="1536.2805,-1312.5 1859.2805,-1312.5 "/>
<text text-anchor="middle" x="1697.7805" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="1536.2805,-1289.5 1859.2805,-1289.5 "/>
<text text-anchor="middle" x="1697.7805" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1536.2805,-1266.5 1859.2805,-1266.5 "/>
<text text-anchor="middle" x="1697.7805" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="1536.2805,-1243.5 1859.2805,-1243.5 "/>
<text text-anchor="middle" x="1697.7805" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="1536.2805,-1220.5 1859.2805,-1220.5 "/>
<text text-anchor="middle" x="1697.7805" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="1536.2805,-1197.5 1859.2805,-1197.5 "/>
<text text-anchor="middle" x="1697.7805" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="1536.2805,-1174.5 1859.2805,-1174.5 "/>
<text text-anchor="middle" x="1697.7805" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="1859.2805,-1151.5 1859.2805,-1726.5 "/>
<text text-anchor="middle" x="1869.7805" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1837.1646,-1151.1415C1877.7955,-1093.6348 1917.5348,-1037.3901 1948.8127,-993.121"/>
<polygon fill="#000000" stroke="#000000" points="1951.8408,-994.9006 1954.7528,-984.7138 1946.1238,-990.8613 1951.8408,-994.9006"/>
<text text-anchor="middle" x="1922.2805" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- methylation_array_file -->
<g id="node10" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M1910.2805,-1324C1910.2805,-1324 2277.2805,-1324 2277.2805,-1324 2283.2805,-1324 2289.2805,-1330 2289.2805,-1336 2289.2805,-1336 2289.2805,-1542 2289.2805,-1542 2289.2805,-1548 2283.2805,-1554 2277.2805,-1554 2277.2805,-1554 1910.2805,-1554 1910.2805,-1554 1904.2805,-1554 1898.2805,-1548 1898.2805,-1542 1898.2805,-1542 1898.2805,-1336 1898.2805,-1336 1898.2805,-1330 1904.2805,-1324 1910.2805,-1324"/>
<text text-anchor="middle" x="1987.2805" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="2076.2805,-1324 2076.2805,-1554 "/>
<text text-anchor="middle" x="2086.7805" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2097.2805,-1324 2097.2805,-1554 "/>
<text text-anchor="middle" x="2182.7805" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2097.2805,-1531 2268.2805,-1531 "/>
<text text-anchor="middle" x="2182.7805" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2097.2805,-1508 2268.2805,-1508 "/>
<text text-anchor="middle" x="2182.7805" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2097.2805,-1485 2268.2805,-1485 "/>
<text text-anchor="middle" x="2182.7805" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2097.2805,-1462 2268.2805,-1462 "/>
<text text-anchor="middle" x="2182.7805" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2097.2805,-1439 2268.2805,-1439 "/>
<text text-anchor="middle" x="2182.7805" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2097.2805,-1416 2268.2805,-1416 "/>
<text text-anchor="middle" x="2182.7805" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2097.2805,-1393 2268.2805,-1393 "/>
<text text-anchor="middle" x="2182.7805" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2097.2805,-1370 2268.2805,-1370 "/>
<text text-anchor="middle" x="2182.7805" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="2097.2805,-1347 2268.2805,-1347 "/>
<text text-anchor="middle" x="2182.7805" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="2268.2805,-1324 2268.2805,-1554 "/>
<text text-anchor="middle" x="2278.7805" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2076.139,-1323.9005C2061.031,-1225.3294 2039.5727,-1085.3276 2025.6634,-994.5776"/>
<polygon fill="#000000" stroke="#000000" points="2029.1064,-993.9384 2024.1317,-984.5841 2022.1872,-994.999 2029.1064,-993.9384"/>
<text text-anchor="middle" x="2136.2805" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- diagnosis -->
<g id="node12" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1026.7805,-708.5C1026.7805,-708.5 1400.7805,-708.5 1400.7805,-708.5 1406.7805,-708.5 1412.7805,-714.5 1412.7805,-720.5 1412.7805,-720.5 1412.7805,-1087.5 1412.7805,-1087.5 1412.7805,-1093.5 1406.7805,-1099.5 1400.7805,-1099.5 1400.7805,-1099.5 1026.7805,-1099.5 1026.7805,-1099.5 1020.7805,-1099.5 1014.7805,-1093.5 1014.7805,-1087.5 1014.7805,-1087.5 1014.7805,-720.5 1014.7805,-720.5 1014.7805,-714.5 1020.7805,-708.5 1026.7805,-708.5"/>
<text text-anchor="middle" x="1056.7805" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1098.7805,-708.5 1098.7805,-1099.5 "/>
<text text-anchor="middle" x="1109.2805" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1119.7805,-708.5 1119.7805,-1099.5 "/>
<text text-anchor="middle" x="1255.7805" y="-1084.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1119.7805,-1076.5 1391.7805,-1076.5 "/>
<text text-anchor="middle" x="1255.7805" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1119.7805,-1053.5 1391.7805,-1053.5 "/>
<text text-anchor="middle" x="1255.7805" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1119.7805,-1030.5 1391.7805,-1030.5 "/>
<text text-anchor="middle" x="1255.7805" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1119.7805,-1007.5 1391.7805,-1007.5 "/>
<text text-anchor="middle" x="1255.7805" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1119.7805,-984.5 1391.7805,-984.5 "/>
<text text-anchor="middle" x="1255.7805" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="1119.7805,-961.5 1391.7805,-961.5 "/>
<text text-anchor="middle" x="1255.7805" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="1119.7805,-938.5 1391.7805,-938.5 "/>
<text text-anchor="middle" x="1255.7805" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="1119.7805,-915.5 1391.7805,-915.5 "/>
<text text-anchor="middle" x="1255.7805" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1119.7805,-892.5 1391.7805,-892.5 "/>
<text text-anchor="middle" x="1255.7805" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="1119.7805,-869.5 1391.7805,-869.5 "/>
<text text-anchor="middle" x="1255.7805" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1119.7805,-846.5 1391.7805,-846.5 "/>
<text text-anchor="middle" x="1255.7805" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="1119.7805,-823.5 1391.7805,-823.5 "/>
<text text-anchor="middle" x="1255.7805" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1119.7805,-800.5 1391.7805,-800.5 "/>
<text text-anchor="middle" x="1255.7805" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1119.7805,-777.5 1391.7805,-777.5 "/>
<text text-anchor="middle" x="1255.7805" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1119.7805,-754.5 1391.7805,-754.5 "/>
<text text-anchor="middle" x="1255.7805" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1119.7805,-731.5 1391.7805,-731.5 "/>
<text text-anchor="middle" x="1255.7805" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="1391.7805,-708.5 1391.7805,-1099.5 "/>
<text text-anchor="middle" x="1402.2805" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1116.8684,-708.2505C1109.4738,-693.3144 1102.378,-678.9817 1095.8982,-665.8934"/>
<polygon fill="#000000" stroke="#000000" points="1098.8669,-664.0011 1091.2933,-656.5922 1092.5936,-667.1069 1098.8669,-664.0011"/>
<text text-anchor="middle" x="1152.2805" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- family_relationship -->
<g id="node13" class="node">
<title>family_relationship</title>
<path fill="none" stroke="#000000" d="M1443.2805,-881C1443.2805,-881 1812.2805,-881 1812.2805,-881 1818.2805,-881 1824.2805,-887 1824.2805,-893 1824.2805,-893 1824.2805,-915 1824.2805,-915 1824.2805,-921 1818.2805,-927 1812.2805,-927 1812.2805,-927 1443.2805,-927 1443.2805,-927 1437.2805,-927 1431.2805,-921 1431.2805,-915 1431.2805,-915 1431.2805,-893 1431.2805,-893 1431.2805,-887 1437.2805,-881 1443.2805,-881"/>
<text text-anchor="middle" x="1508.2805" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
<polyline fill="none" stroke="#000000" points="1585.2805,-881 1585.2805,-927 "/>
<text text-anchor="middle" x="1595.7805" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1606.2805,-881 1606.2805,-927 "/>
<text text-anchor="middle" x="1704.7805" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">related_to_participant_id</text>
<polyline fill="none" stroke="#000000" points="1606.2805,-904 1803.2805,-904 "/>
<text text-anchor="middle" x="1704.7805" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">relationship</text>
<polyline fill="none" stroke="#000000" points="1803.2805,-881 1803.2805,-927 "/>
<text text-anchor="middle" x="1813.7805" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1609.6623,-880.729C1576.6483,-839.8684 1502.6047,-755.1017 1421.7805,-708 1365.2898,-675.0791 1297.9041,-651.2167 1236.8528,-634.3705"/>
<polygon fill="#000000" stroke="#000000" points="1237.6792,-630.9682 1227.1115,-631.7267 1235.8456,-637.7238 1237.6792,-630.9682"/>
<text text-anchor="middle" x="1465.2805" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- pdx -->
<g id="node14" class="node">
<title>pdx</title>
<path fill="none" stroke="#000000" d="M2319.2805,-1335.5C2319.2805,-1335.5 2648.2805,-1335.5 2648.2805,-1335.5 2654.2805,-1335.5 2660.2805,-1341.5 2660.2805,-1347.5 2660.2805,-1347.5 2660.2805,-1530.5 2660.2805,-1530.5 2660.2805,-1536.5 2654.2805,-1542.5 2648.2805,-1542.5 2648.2805,-1542.5 2319.2805,-1542.5 2319.2805,-1542.5 2313.2805,-1542.5 2307.2805,-1536.5 2307.2805,-1530.5 2307.2805,-1530.5 2307.2805,-1347.5 2307.2805,-1347.5 2307.2805,-1341.5 2313.2805,-1335.5 2319.2805,-1335.5"/>
<text text-anchor="middle" x="2328.7805" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
<polyline fill="none" stroke="#000000" points="2350.2805,-1335.5 2350.2805,-1542.5 "/>
<text text-anchor="middle" x="2360.7805" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2371.2805,-1335.5 2371.2805,-1542.5 "/>
<text text-anchor="middle" x="2505.2805" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_site</text>
<polyline fill="none" stroke="#000000" points="2371.2805,-1519.5 2639.2805,-1519.5 "/>
<text text-anchor="middle" x="2505.2805" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_type</text>
<polyline fill="none" stroke="#000000" points="2371.2805,-1496.5 2639.2805,-1496.5 "/>
<text text-anchor="middle" x="2505.2805" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_id</text>
<polyline fill="none" stroke="#000000" points="2371.2805,-1473.5 2639.2805,-1473.5 "/>
<text text-anchor="middle" x="2505.2805" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">mouse_strain</text>
<polyline fill="none" stroke="#000000" points="2371.2805,-1450.5 2639.2805,-1450.5 "/>
<text text-anchor="middle" x="2505.2805" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">strain_immune_system_humanized</text>
<polyline fill="none" stroke="#000000" points="2371.2805,-1427.5 2639.2805,-1427.5 "/>
<text text-anchor="middle" x="2505.2805" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_characterization_method</text>
<polyline fill="none" stroke="#000000" points="2371.2805,-1404.5 2639.2805,-1404.5 "/>
<text text-anchor="middle" x="2505.2805" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_not_mus_or_ebv_origin</text>
<polyline fill="none" stroke="#000000" points="2371.2805,-1381.5 2639.2805,-1381.5 "/>
<text text-anchor="middle" x="2505.2805" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_preparation</text>
<polyline fill="none" stroke="#000000" points="2371.2805,-1358.5 2639.2805,-1358.5 "/>
<text text-anchor="middle" x="2505.2805" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_humanization</text>
<polyline fill="none" stroke="#000000" points="2639.2805,-1335.5 2639.2805,-1542.5 "/>
<text text-anchor="middle" x="2649.7805" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2427.1159,-1335.3438C2393.4879,-1278.1622 2347.9043,-1207.5116 2298.7805,-1151 2248.0144,-1092.5992 2183.255,-1035.6831 2128.104,-991.2336"/>
<polygon fill="#000000" stroke="#000000" points="2130.0307,-988.2923 2120.0395,-984.7673 2125.6517,-993.7536 2130.0307,-988.2923"/>
<text text-anchor="middle" x="2301.7805" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- publication -->
<g id="node15" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M1421.7805,-391C1421.7805,-391 1631.7805,-391 1631.7805,-391 1637.7805,-391 1643.7805,-397 1643.7805,-403 1643.7805,-403 1643.7805,-415 1643.7805,-415 1643.7805,-421 1637.7805,-427 1631.7805,-427 1631.7805,-427 1421.7805,-427 1421.7805,-427 1415.7805,-427 1409.7805,-421 1409.7805,-415 1409.7805,-415 1409.7805,-403 1409.7805,-403 1409.7805,-397 1415.7805,-391 1421.7805,-391"/>
<text text-anchor="middle" x="1458.2805" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="1506.7805,-391 1506.7805,-427 "/>
<text text-anchor="middle" x="1517.2805" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1527.7805,-391 1527.7805,-427 "/>
<text text-anchor="middle" x="1575.2805" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="1622.7805,-391 1622.7805,-427 "/>
<text text-anchor="middle" x="1633.2805" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge7" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1502.7662,-390.9084C1478.1821,-373.0403 1438.3577,-345.8662 1400.7805,-328 1285.2251,-273.0587 1149.5867,-227.7261 1038.6505,-195.1897"/>
<polygon fill="#000000" stroke="#000000" points="1039.5948,-191.8193 1029.0146,-192.3775 1037.6336,-198.539 1039.5948,-191.8193"/>
<text text-anchor="middle" x="1406.7805" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1959.1652,-823.1795C1927.8384,-781.8687 1884.3558,-734.7795 1833.7805,-708 1733.3052,-654.7985 1432.0261,-624.4528 1237.1872,-609.8956"/>
<polygon fill="#000000" stroke="#000000" points="1237.3534,-606.3984 1227.1223,-609.1505 1236.8366,-613.3793 1237.3534,-606.3984"/>
<text text-anchor="middle" x="1824.2805" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge4" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2037.6041,-823.4795C2071.5335,-700.4072 2113.6602,-465.3599 1992.7805,-328 1930.6156,-257.3599 1360.3636,-190.9969 1039.184,-158.8087"/>
<polygon fill="#000000" stroke="#000000" points="1039.1086,-155.2838 1028.8101,-157.7722 1038.4126,-162.2491 1039.1086,-155.2838"/>
<text text-anchor="middle" x="2106.2805" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge19" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1758.8068,-374.3963C1727.5262,-358.5529 1688.912,-340.5549 1652.7805,-328 1449.4377,-257.3429 1208.8468,-205.7951 1039.0073,-174.4554"/>
<polygon fill="#000000" stroke="#000000" points="1039.4104,-170.971 1028.9426,-172.6066 1038.1457,-177.8558 1039.4104,-170.971"/>
<text text-anchor="middle" x="1635.2805" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- sample_diagnosis -->
<g id="node18" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M2690.2805,-1278C2690.2805,-1278 3123.2805,-1278 3123.2805,-1278 3129.2805,-1278 3135.2805,-1284 3135.2805,-1290 3135.2805,-1290 3135.2805,-1588 3135.2805,-1588 3135.2805,-1594 3129.2805,-1600 3123.2805,-1600 3123.2805,-1600 2690.2805,-1600 2690.2805,-1600 2684.2805,-1600 2678.2805,-1594 2678.2805,-1588 2678.2805,-1588 2678.2805,-1290 2678.2805,-1290 2678.2805,-1284 2684.2805,-1278 2690.2805,-1278"/>
<text text-anchor="middle" x="2749.7805" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2821.2805,-1278 2821.2805,-1600 "/>
<text text-anchor="middle" x="2831.7805" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2842.2805,-1278 2842.2805,-1600 "/>
<text text-anchor="middle" x="2978.2805" y="-1584.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2842.2805,-1577 3114.2805,-1577 "/>
<text text-anchor="middle" x="2978.2805" y="-1561.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="2842.2805,-1554 3114.2805,-1554 "/>
<text text-anchor="middle" x="2978.2805" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2842.2805,-1531 3114.2805,-1531 "/>
<text text-anchor="middle" x="2978.2805" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="2842.2805,-1508 3114.2805,-1508 "/>
<text text-anchor="middle" x="2978.2805" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="2842.2805,-1485 3114.2805,-1485 "/>
<text text-anchor="middle" x="2978.2805" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="2842.2805,-1462 3114.2805,-1462 "/>
<text text-anchor="middle" x="2978.2805" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="2842.2805,-1439 3114.2805,-1439 "/>
<text text-anchor="middle" x="2978.2805" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2842.2805,-1416 3114.2805,-1416 "/>
<text text-anchor="middle" x="2978.2805" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="2842.2805,-1393 3114.2805,-1393 "/>
<text text-anchor="middle" x="2978.2805" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="2842.2805,-1370 3114.2805,-1370 "/>
<text text-anchor="middle" x="2978.2805" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="2842.2805,-1347 3114.2805,-1347 "/>
<text text-anchor="middle" x="2978.2805" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="2842.2805,-1324 3114.2805,-1324 "/>
<text text-anchor="middle" x="2978.2805" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="2842.2805,-1301 3114.2805,-1301 "/>
<text text-anchor="middle" x="2978.2805" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="3114.2805,-1278 3114.2805,-1600 "/>
<text text-anchor="middle" x="3124.7805" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2798.6723,-1277.7598C2762,-1232.0763 2717.979,-1185.4582 2669.7805,-1151 2524.6203,-1047.2218 2330.5823,-981.4075 2190.8793,-944.0489"/>
<polygon fill="#000000" stroke="#000000" points="2191.4789,-940.5871 2180.916,-941.4081 2189.6855,-947.3534 2191.4789,-940.5871"/>
<text text-anchor="middle" x="2711.7805" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
</g>
</svg>
</div>
