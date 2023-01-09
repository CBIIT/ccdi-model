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
<svg width="2581pt" height="1551pt"
 viewBox="0.00 0.00 2580.50 1551.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1547)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1547 2576.5,-1547 2576.5,4 -4,4"/>
<!-- publication -->
<g id="node1" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M12,-333.5C12,-333.5 222,-333.5 222,-333.5 228,-333.5 234,-339.5 234,-345.5 234,-345.5 234,-357.5 234,-357.5 234,-363.5 228,-369.5 222,-369.5 222,-369.5 12,-369.5 12,-369.5 6,-369.5 0,-363.5 0,-357.5 0,-357.5 0,-345.5 0,-345.5 0,-339.5 6,-333.5 12,-333.5"/>
<text text-anchor="middle" x="48.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="97,-333.5 97,-369.5 "/>
<text text-anchor="middle" x="107.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="118,-333.5 118,-369.5 "/>
<text text-anchor="middle" x="165.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="213,-333.5 213,-369.5 "/>
<text text-anchor="middle" x="223.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node14" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M823,-.5C823,-.5 1213,-.5 1213,-.5 1219,-.5 1225,-6.5 1225,-12.5 1225,-12.5 1225,-195.5 1225,-195.5 1225,-201.5 1219,-207.5 1213,-207.5 1213,-207.5 823,-207.5 823,-207.5 817,-207.5 811,-201.5 811,-195.5 811,-195.5 811,-12.5 811,-12.5 811,-6.5 817,-.5 823,-.5"/>
<text text-anchor="middle" x="839" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="867,-.5 867,-207.5 "/>
<text text-anchor="middle" x="877.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="888,-.5 888,-207.5 "/>
<text text-anchor="middle" x="1046" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="888,-184.5 1204,-184.5 "/>
<text text-anchor="middle" x="1046" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="888,-161.5 1204,-161.5 "/>
<text text-anchor="middle" x="1046" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="888,-138.5 1204,-138.5 "/>
<text text-anchor="middle" x="1046" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="888,-115.5 1204,-115.5 "/>
<text text-anchor="middle" x="1046" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="888,-92.5 1204,-92.5 "/>
<text text-anchor="middle" x="1046" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="888,-69.5 1204,-69.5 "/>
<text text-anchor="middle" x="1046" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="888,-46.5 1204,-46.5 "/>
<text text-anchor="middle" x="1046" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="888,-23.5 1204,-23.5 "/>
<text text-anchor="middle" x="1046" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="1204,-.5 1204,-207.5 "/>
<text text-anchor="middle" x="1214.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge13" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M136.3379,-333.3701C159.7857,-312.3738 201.3592,-278.2172 243,-259 420.5548,-177.0583 640.606,-138.3136 800.8101,-120.0654"/>
<polygon fill="#000000" stroke="#000000" points="801.2455,-123.5386 810.7932,-118.946 800.4654,-116.5822 801.2455,-123.5386"/>
<text text-anchor="middle" x="373" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- study_admin -->
<g id="node2" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M264,-259.5C264,-259.5 590,-259.5 590,-259.5 596,-259.5 602,-265.5 602,-271.5 602,-271.5 602,-431.5 602,-431.5 602,-437.5 596,-443.5 590,-443.5 590,-443.5 264,-443.5 264,-443.5 258,-443.5 252,-437.5 252,-431.5 252,-431.5 252,-271.5 252,-271.5 252,-265.5 258,-259.5 264,-259.5"/>
<text text-anchor="middle" x="306" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="360,-259.5 360,-443.5 "/>
<text text-anchor="middle" x="370.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="381,-259.5 381,-443.5 "/>
<text text-anchor="middle" x="481" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="381,-420.5 581,-420.5 "/>
<text text-anchor="middle" x="481" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="381,-397.5 581,-397.5 "/>
<text text-anchor="middle" x="481" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="381,-374.5 581,-374.5 "/>
<text text-anchor="middle" x="481" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="381,-351.5 581,-351.5 "/>
<text text-anchor="middle" x="481" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="381,-328.5 581,-328.5 "/>
<text text-anchor="middle" x="481" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="381,-305.5 581,-305.5 "/>
<text text-anchor="middle" x="481" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="381,-282.5 581,-282.5 "/>
<text text-anchor="middle" x="481" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="581,-259.5 581,-443.5 "/>
<text text-anchor="middle" x="591.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge12" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M470.7071,-259.2721C479.9078,-246.6708 490.6458,-234.9971 503,-226 551.1777,-190.9138 682.7771,-160.0584 800.8784,-138.1559"/>
<polygon fill="#000000" stroke="#000000" points="801.6028,-141.5814 810.8046,-136.33 800.3364,-134.6969 801.6028,-141.5814"/>
<text text-anchor="middle" x="559.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- synonym -->
<g id="node3" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M479.5,-1232C479.5,-1232 780.5,-1232 780.5,-1232 786.5,-1232 792.5,-1238 792.5,-1244 792.5,-1244 792.5,-1266 792.5,-1266 792.5,-1272 786.5,-1278 780.5,-1278 780.5,-1278 479.5,-1278 479.5,-1278 473.5,-1278 467.5,-1272 467.5,-1266 467.5,-1266 467.5,-1244 467.5,-1244 467.5,-1238 473.5,-1232 479.5,-1232"/>
<text text-anchor="middle" x="507.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="547.5,-1232 547.5,-1278 "/>
<text text-anchor="middle" x="558" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="568.5,-1232 568.5,-1278 "/>
<text text-anchor="middle" x="670" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="568.5,-1255 771.5,-1255 "/>
<text text-anchor="middle" x="670" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="771.5,-1232 771.5,-1278 "/>
<text text-anchor="middle" x="782" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node5" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M1284.5,-495.5C1284.5,-495.5 1515.5,-495.5 1515.5,-495.5 1521.5,-495.5 1527.5,-501.5 1527.5,-507.5 1527.5,-507.5 1527.5,-575.5 1527.5,-575.5 1527.5,-581.5 1521.5,-587.5 1515.5,-587.5 1515.5,-587.5 1284.5,-587.5 1284.5,-587.5 1278.5,-587.5 1272.5,-581.5 1272.5,-575.5 1272.5,-575.5 1272.5,-507.5 1272.5,-507.5 1272.5,-501.5 1278.5,-495.5 1284.5,-495.5"/>
<text text-anchor="middle" x="1320.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1368.5,-495.5 1368.5,-587.5 "/>
<text text-anchor="middle" x="1379" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1389.5,-495.5 1389.5,-587.5 "/>
<text text-anchor="middle" x="1448" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="1389.5,-564.5 1506.5,-564.5 "/>
<text text-anchor="middle" x="1448" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="1389.5,-541.5 1506.5,-541.5 "/>
<text text-anchor="middle" x="1448" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1389.5,-518.5 1506.5,-518.5 "/>
<text text-anchor="middle" x="1448" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1506.5,-495.5 1506.5,-587.5 "/>
<text text-anchor="middle" x="1517" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M630.8977,-1231.8142C635.3373,-1129.9355 658.384,-723.3366 746,-639 782.6034,-603.7666 1081.3226,-570.6382 1262.1393,-553.5519"/>
<polygon fill="#000000" stroke="#000000" points="1262.637,-557.0206 1272.2656,-552.6001 1261.9819,-550.0513 1262.637,-557.0206"/>
<text text-anchor="middle" x="788.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- sample -->
<g id="node8" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M852,-639.5C852,-639.5 1166,-639.5 1166,-639.5 1172,-639.5 1178,-645.5 1178,-651.5 1178,-651.5 1178,-903.5 1178,-903.5 1178,-909.5 1172,-915.5 1166,-915.5 1166,-915.5 852,-915.5 852,-915.5 846,-915.5 840,-909.5 840,-903.5 840,-903.5 840,-651.5 840,-651.5 840,-645.5 846,-639.5 852,-639.5"/>
<text text-anchor="middle" x="874" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="908,-639.5 908,-915.5 "/>
<text text-anchor="middle" x="918.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="929,-639.5 929,-915.5 "/>
<text text-anchor="middle" x="1043" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="929,-892.5 1157,-892.5 "/>
<text text-anchor="middle" x="1043" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="929,-869.5 1157,-869.5 "/>
<text text-anchor="middle" x="1043" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="929,-846.5 1157,-846.5 "/>
<text text-anchor="middle" x="1043" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="929,-823.5 1157,-823.5 "/>
<text text-anchor="middle" x="1043" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="929,-800.5 1157,-800.5 "/>
<text text-anchor="middle" x="1043" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="929,-777.5 1157,-777.5 "/>
<text text-anchor="middle" x="1043" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="929,-754.5 1157,-754.5 "/>
<text text-anchor="middle" x="1043" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="929,-731.5 1157,-731.5 "/>
<text text-anchor="middle" x="1043" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="929,-708.5 1157,-708.5 "/>
<text text-anchor="middle" x="1043" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="929,-685.5 1157,-685.5 "/>
<text text-anchor="middle" x="1043" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="929,-662.5 1157,-662.5 "/>
<text text-anchor="middle" x="1043" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1157,-639.5 1157,-915.5 "/>
<text text-anchor="middle" x="1167.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M640.784,-1231.865C665.1147,-1180.9711 727.8912,-1056.6971 801,-967 813.0897,-952.1672 826.3496,-937.4367 840.1386,-923.1247"/>
<polygon fill="#000000" stroke="#000000" points="842.921,-925.2844 847.3941,-915.6802 837.908,-920.3987 842.921,-925.2844"/>
<text text-anchor="middle" x="869.5" y="-937.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge8" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M630,-1231.6473C630,-1162.378 630,-952.003 630,-777.5 630,-777.5 630,-777.5 630,-351.5 630,-309.5306 622.3544,-291.426 649,-259 688.072,-211.4519 744.2768,-178.2514 801.0825,-155.1621"/>
<polygon fill="#000000" stroke="#000000" points="802.5666,-158.3389 810.5724,-151.3993 799.9864,-151.8317 802.5666,-158.3389"/>
<text text-anchor="middle" x="672.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study_personnel -->
<g id="node4" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M670.5,-294C670.5,-294 977.5,-294 977.5,-294 983.5,-294 989.5,-300 989.5,-306 989.5,-306 989.5,-397 989.5,-397 989.5,-403 983.5,-409 977.5,-409 977.5,-409 670.5,-409 670.5,-409 664.5,-409 658.5,-403 658.5,-397 658.5,-397 658.5,-306 658.5,-306 658.5,-300 664.5,-294 670.5,-294"/>
<text text-anchor="middle" x="725.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="792.5,-294 792.5,-409 "/>
<text text-anchor="middle" x="803" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="813.5,-294 813.5,-409 "/>
<text text-anchor="middle" x="891" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="813.5,-386 968.5,-386 "/>
<text text-anchor="middle" x="891" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="813.5,-363 968.5,-363 "/>
<text text-anchor="middle" x="891" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="813.5,-340 968.5,-340 "/>
<text text-anchor="middle" x="891" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="813.5,-317 968.5,-317 "/>
<text text-anchor="middle" x="891" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="968.5,-294 968.5,-409 "/>
<text text-anchor="middle" x="979" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge19" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M835.2881,-293.923C841.5593,-271.379 851.0162,-246.1488 865,-226 867.4516,-222.4676 870.0347,-218.9864 872.7304,-215.5597"/>
<polygon fill="#000000" stroke="#000000" points="875.5724,-217.6139 879.2156,-207.6652 870.1634,-213.1706 875.5724,-217.6139"/>
<text text-anchor="middle" x="934.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- study_arm -->
<g id="node9" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M1058.5,-317C1058.5,-317 1355.5,-317 1355.5,-317 1361.5,-317 1367.5,-323 1367.5,-329 1367.5,-329 1367.5,-374 1367.5,-374 1367.5,-380 1361.5,-386 1355.5,-386 1355.5,-386 1058.5,-386 1058.5,-386 1052.5,-386 1046.5,-380 1046.5,-374 1046.5,-374 1046.5,-329 1046.5,-329 1046.5,-323 1052.5,-317 1058.5,-317"/>
<text text-anchor="middle" x="1092.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="1138.5,-317 1138.5,-386 "/>
<text text-anchor="middle" x="1149" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1159.5,-317 1159.5,-386 "/>
<text text-anchor="middle" x="1253" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="1159.5,-363 1346.5,-363 "/>
<text text-anchor="middle" x="1253" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="1159.5,-340 1346.5,-340 "/>
<text text-anchor="middle" x="1253" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="1346.5,-317 1346.5,-386 "/>
<text text-anchor="middle" x="1357" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge14" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1311.4992,-495.3482C1303.52,-489.6535 1295.8711,-483.5204 1289,-477 1264.1747,-453.4416 1243.2176,-420.9728 1228.7049,-394.963"/>
<polygon fill="#000000" stroke="#000000" points="1231.7075,-393.1586 1223.8445,-386.0576 1225.563,-396.5121 1231.7075,-393.1586"/>
<text text-anchor="middle" x="1339.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge15" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1401.8346,-495.4745C1403.723,-425.2795 1403.3501,-295.7363 1377,-259 1342.3077,-210.6333 1289.2682,-177.2154 1234.5185,-154.1801"/>
<polygon fill="#000000" stroke="#000000" points="1235.5832,-150.8341 1225.0025,-150.2856 1232.9317,-157.3125 1235.5832,-150.8341"/>
<text text-anchor="middle" x="1452.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- imaging_file -->
<g id="node6" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M1232,-1094C1232,-1094 1566,-1094 1566,-1094 1572,-1094 1578,-1100 1578,-1106 1578,-1106 1578,-1404 1578,-1404 1578,-1410 1572,-1416 1566,-1416 1566,-1416 1232,-1416 1232,-1416 1226,-1416 1220,-1410 1220,-1404 1220,-1404 1220,-1106 1220,-1106 1220,-1100 1226,-1094 1232,-1094"/>
<text text-anchor="middle" x="1272" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="1324,-1094 1324,-1416 "/>
<text text-anchor="middle" x="1334.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1345,-1094 1345,-1416 "/>
<text text-anchor="middle" x="1451" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1345,-1393 1557,-1393 "/>
<text text-anchor="middle" x="1451" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1345,-1370 1557,-1370 "/>
<text text-anchor="middle" x="1451" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1345,-1347 1557,-1347 "/>
<text text-anchor="middle" x="1451" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1345,-1324 1557,-1324 "/>
<text text-anchor="middle" x="1451" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1345,-1301 1557,-1301 "/>
<text text-anchor="middle" x="1451" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1345,-1278 1557,-1278 "/>
<text text-anchor="middle" x="1451" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1345,-1255 1557,-1255 "/>
<text text-anchor="middle" x="1451" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1345,-1232 1557,-1232 "/>
<text text-anchor="middle" x="1451" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1345,-1209 1557,-1209 "/>
<text text-anchor="middle" x="1451" y="-1193.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="1345,-1186 1557,-1186 "/>
<text text-anchor="middle" x="1451" y="-1170.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="1345,-1163 1557,-1163 "/>
<text text-anchor="middle" x="1451" y="-1147.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="1345,-1140 1557,-1140 "/>
<text text-anchor="middle" x="1451" y="-1124.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1345,-1117 1557,-1117 "/>
<text text-anchor="middle" x="1451" y="-1101.8" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="1557,-1094 1557,-1416 "/>
<text text-anchor="middle" x="1567.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1309.9809,-1093.9437C1277.0809,-1040.564 1237.3893,-982.4556 1195,-934 1191.7829,-930.3225 1188.4762,-926.6574 1185.0949,-923.0113"/>
<polygon fill="#000000" stroke="#000000" points="1187.4645,-920.423 1178.0538,-915.5559 1182.3754,-925.2293 1187.4645,-920.423"/>
<text text-anchor="middle" x="1255.5" y="-937.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- sample_diagnosis -->
<g id="node7" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M1608,-1117C1608,-1117 2050,-1117 2050,-1117 2056,-1117 2062,-1123 2062,-1129 2062,-1129 2062,-1381 2062,-1381 2062,-1387 2056,-1393 2050,-1393 2050,-1393 1608,-1393 1608,-1393 1602,-1393 1596,-1387 1596,-1381 1596,-1381 1596,-1129 1596,-1129 1596,-1123 1602,-1117 1608,-1117"/>
<text text-anchor="middle" x="1667.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1739,-1117 1739,-1393 "/>
<text text-anchor="middle" x="1749.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1760,-1117 1760,-1393 "/>
<text text-anchor="middle" x="1900.5" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1760,-1370 2041,-1370 "/>
<text text-anchor="middle" x="1900.5" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1760,-1347 2041,-1347 "/>
<text text-anchor="middle" x="1900.5" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1760,-1324 2041,-1324 "/>
<text text-anchor="middle" x="1900.5" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1760,-1301 2041,-1301 "/>
<text text-anchor="middle" x="1900.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="1760,-1278 2041,-1278 "/>
<text text-anchor="middle" x="1900.5" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1760,-1255 2041,-1255 "/>
<text text-anchor="middle" x="1900.5" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1760,-1232 2041,-1232 "/>
<text text-anchor="middle" x="1900.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis_reference_source</text>
<polyline fill="none" stroke="#000000" points="1760,-1209 2041,-1209 "/>
<text text-anchor="middle" x="1900.5" y="-1193.8" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="1760,-1186 2041,-1186 "/>
<text text-anchor="middle" x="1900.5" y="-1170.8" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="1760,-1163 2041,-1163 "/>
<text text-anchor="middle" x="1900.5" y="-1147.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1760,-1140 2041,-1140 "/>
<text text-anchor="middle" x="1900.5" y="-1124.8" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="2041,-1117 2041,-1393 "/>
<text text-anchor="middle" x="2051.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1745.8293,-1116.6519C1705.0674,-1061.013 1650.9201,-1001.8825 1587,-967 1547.7677,-945.5901 1229.2897,-933.109 1188,-916 1187.7958,-915.9154 1187.5917,-915.8305 1187.3875,-915.7453"/>
<polygon fill="#000000" stroke="#000000" points="1188.7909,-912.539 1178.2279,-911.7179 1185.9733,-918.9469 1188.7909,-912.539"/>
<text text-anchor="middle" x="1555" y="-937.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1178.146,-645.0985C1181.4371,-643.0205 1184.7236,-640.9854 1188,-639 1216.1803,-621.9238 1247.8541,-605.8563 1277.9569,-591.8803"/>
<polygon fill="#000000" stroke="#000000" points="1279.6192,-594.9683 1287.2431,-587.6113 1276.6953,-588.6082 1279.6192,-594.9683"/>
<text text-anchor="middle" x="1280.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge16" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1010.8484,-639.1747C1012.51,-514.8317 1014.9214,-334.3826 1016.4752,-218.1048"/>
<polygon fill="#000000" stroke="#000000" points="1019.9795,-217.8012 1016.6135,-207.7553 1012.9801,-217.7076 1019.9795,-217.8012"/>
<text text-anchor="middle" x="1050.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge4" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1180.5214,-316.8256C1160.3564,-290.4191 1131.4009,-252.5012 1103.5012,-215.9658"/>
<polygon fill="#000000" stroke="#000000" points="1106.0442,-213.5291 1097.1934,-207.7056 1100.4808,-217.7775 1106.0442,-213.5291"/>
<text text-anchor="middle" x="1166.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- therapeutic_procedure -->
<g id="node10" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M1633.5,-720C1633.5,-720 1990.5,-720 1990.5,-720 1996.5,-720 2002.5,-726 2002.5,-732 2002.5,-732 2002.5,-823 2002.5,-823 2002.5,-829 1996.5,-835 1990.5,-835 1990.5,-835 1633.5,-835 1633.5,-835 1627.5,-835 1621.5,-829 1621.5,-823 1621.5,-823 1621.5,-732 1621.5,-732 1621.5,-726 1627.5,-720 1633.5,-720"/>
<text text-anchor="middle" x="1712" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="1802.5,-720 1802.5,-835 "/>
<text text-anchor="middle" x="1813" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1823.5,-720 1823.5,-835 "/>
<text text-anchor="middle" x="1902.5" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="1823.5,-812 1981.5,-812 "/>
<text text-anchor="middle" x="1902.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="1823.5,-789 1981.5,-789 "/>
<text text-anchor="middle" x="1902.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1823.5,-766 1981.5,-766 "/>
<text text-anchor="middle" x="1902.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="1823.5,-743 1981.5,-743 "/>
<text text-anchor="middle" x="1902.5" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1981.5,-720 1981.5,-835 "/>
<text text-anchor="middle" x="1992" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1736.1255,-719.9156C1699.8542,-693.6457 1655.2232,-663.0997 1613,-639 1583.5047,-622.165 1550.5877,-605.9385 1519.6198,-591.715"/>
<polygon fill="#000000" stroke="#000000" points="1521.0621,-588.526 1510.5111,-587.5627 1518.1585,-594.8954 1521.0621,-588.526"/>
<text text-anchor="middle" x="1672" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- diagnosis -->
<g id="node11" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1208.5,-639.5C1208.5,-639.5 1591.5,-639.5 1591.5,-639.5 1597.5,-639.5 1603.5,-645.5 1603.5,-651.5 1603.5,-651.5 1603.5,-903.5 1603.5,-903.5 1603.5,-909.5 1597.5,-915.5 1591.5,-915.5 1591.5,-915.5 1208.5,-915.5 1208.5,-915.5 1202.5,-915.5 1196.5,-909.5 1196.5,-903.5 1196.5,-903.5 1196.5,-651.5 1196.5,-651.5 1196.5,-645.5 1202.5,-639.5 1208.5,-639.5"/>
<text text-anchor="middle" x="1238.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1280.5,-639.5 1280.5,-915.5 "/>
<text text-anchor="middle" x="1291" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1301.5,-639.5 1301.5,-915.5 "/>
<text text-anchor="middle" x="1442" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1301.5,-892.5 1582.5,-892.5 "/>
<text text-anchor="middle" x="1442" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1301.5,-869.5 1582.5,-869.5 "/>
<text text-anchor="middle" x="1442" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1301.5,-846.5 1582.5,-846.5 "/>
<text text-anchor="middle" x="1442" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1301.5,-823.5 1582.5,-823.5 "/>
<text text-anchor="middle" x="1442" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1301.5,-800.5 1582.5,-800.5 "/>
<text text-anchor="middle" x="1442" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="1301.5,-777.5 1582.5,-777.5 "/>
<text text-anchor="middle" x="1442" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1301.5,-754.5 1582.5,-754.5 "/>
<text text-anchor="middle" x="1442" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1301.5,-731.5 1582.5,-731.5 "/>
<text text-anchor="middle" x="1442" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis_reference_source</text>
<polyline fill="none" stroke="#000000" points="1301.5,-708.5 1582.5,-708.5 "/>
<text text-anchor="middle" x="1442" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="1301.5,-685.5 1582.5,-685.5 "/>
<text text-anchor="middle" x="1442" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="1301.5,-662.5 1582.5,-662.5 "/>
<text text-anchor="middle" x="1442" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="1582.5,-639.5 1582.5,-915.5 "/>
<text text-anchor="middle" x="1593" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1400,-639.1938C1400,-624.7323 1400,-610.6904 1400,-597.9724"/>
<polygon fill="#000000" stroke="#000000" points="1403.5001,-597.6204 1400,-587.6204 1396.5001,-597.6205 1403.5001,-597.6204"/>
<text text-anchor="middle" x="1444.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- methylation_array_file -->
<g id="node12" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M822.5,-1140C822.5,-1140 1189.5,-1140 1189.5,-1140 1195.5,-1140 1201.5,-1146 1201.5,-1152 1201.5,-1152 1201.5,-1358 1201.5,-1358 1201.5,-1364 1195.5,-1370 1189.5,-1370 1189.5,-1370 822.5,-1370 822.5,-1370 816.5,-1370 810.5,-1364 810.5,-1358 810.5,-1358 810.5,-1152 810.5,-1152 810.5,-1146 816.5,-1140 822.5,-1140"/>
<text text-anchor="middle" x="899.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="988.5,-1140 988.5,-1370 "/>
<text text-anchor="middle" x="999" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1009.5,-1140 1009.5,-1370 "/>
<text text-anchor="middle" x="1095" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1009.5,-1347 1180.5,-1347 "/>
<text text-anchor="middle" x="1095" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1009.5,-1324 1180.5,-1324 "/>
<text text-anchor="middle" x="1095" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1009.5,-1301 1180.5,-1301 "/>
<text text-anchor="middle" x="1095" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1009.5,-1278 1180.5,-1278 "/>
<text text-anchor="middle" x="1095" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1009.5,-1255 1180.5,-1255 "/>
<text text-anchor="middle" x="1095" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1009.5,-1232 1180.5,-1232 "/>
<text text-anchor="middle" x="1095" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1009.5,-1209 1180.5,-1209 "/>
<text text-anchor="middle" x="1095" y="-1193.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1009.5,-1186 1180.5,-1186 "/>
<text text-anchor="middle" x="1095" y="-1170.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="1009.5,-1163 1180.5,-1163 "/>
<text text-anchor="middle" x="1095" y="-1147.8" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="1180.5,-1140 1180.5,-1370 "/>
<text text-anchor="middle" x="1191" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1006.7243,-1139.715C1007.1284,-1075.3995 1007.6361,-994.5925 1008.0693,-925.6303"/>
<polygon fill="#000000" stroke="#000000" points="1011.5697,-925.5667 1008.1327,-915.5449 1004.5698,-925.5226 1011.5697,-925.5667"/>
<text text-anchor="middle" x="1099.5" y="-937.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- sequencing_file -->
<g id="node13" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M2091.5,-967.5C2091.5,-967.5 2560.5,-967.5 2560.5,-967.5 2566.5,-967.5 2572.5,-973.5 2572.5,-979.5 2572.5,-979.5 2572.5,-1530.5 2572.5,-1530.5 2572.5,-1536.5 2566.5,-1542.5 2560.5,-1542.5 2560.5,-1542.5 2091.5,-1542.5 2091.5,-1542.5 2085.5,-1542.5 2079.5,-1536.5 2079.5,-1530.5 2079.5,-1530.5 2079.5,-979.5 2079.5,-979.5 2079.5,-973.5 2085.5,-967.5 2091.5,-967.5"/>
<text text-anchor="middle" x="2143.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="2207.5,-967.5 2207.5,-1542.5 "/>
<text text-anchor="middle" x="2218" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2228.5,-967.5 2228.5,-1542.5 "/>
<text text-anchor="middle" x="2390" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="2228.5,-1519.5 2551.5,-1519.5 "/>
<text text-anchor="middle" x="2390" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2228.5,-1496.5 2551.5,-1496.5 "/>
<text text-anchor="middle" x="2390" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2228.5,-1473.5 2551.5,-1473.5 "/>
<text text-anchor="middle" x="2390" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="2228.5,-1450.5 2551.5,-1450.5 "/>
<text text-anchor="middle" x="2390" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="2228.5,-1427.5 2551.5,-1427.5 "/>
<text text-anchor="middle" x="2390" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2228.5,-1404.5 2551.5,-1404.5 "/>
<text text-anchor="middle" x="2390" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="2228.5,-1381.5 2551.5,-1381.5 "/>
<text text-anchor="middle" x="2390" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2228.5,-1358.5 2551.5,-1358.5 "/>
<text text-anchor="middle" x="2390" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2228.5,-1335.5 2551.5,-1335.5 "/>
<text text-anchor="middle" x="2390" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2228.5,-1312.5 2551.5,-1312.5 "/>
<text text-anchor="middle" x="2390" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2228.5,-1289.5 2551.5,-1289.5 "/>
<text text-anchor="middle" x="2390" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2228.5,-1266.5 2551.5,-1266.5 "/>
<text text-anchor="middle" x="2390" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2228.5,-1243.5 2551.5,-1243.5 "/>
<text text-anchor="middle" x="2390" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="2228.5,-1220.5 2551.5,-1220.5 "/>
<text text-anchor="middle" x="2390" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="2228.5,-1197.5 2551.5,-1197.5 "/>
<text text-anchor="middle" x="2390" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="2228.5,-1174.5 2551.5,-1174.5 "/>
<text text-anchor="middle" x="2390" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="2228.5,-1151.5 2551.5,-1151.5 "/>
<text text-anchor="middle" x="2390" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="2228.5,-1128.5 2551.5,-1128.5 "/>
<text text-anchor="middle" x="2390" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="2228.5,-1105.5 2551.5,-1105.5 "/>
<text text-anchor="middle" x="2390" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2228.5,-1082.5 2551.5,-1082.5 "/>
<text text-anchor="middle" x="2390" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="2228.5,-1059.5 2551.5,-1059.5 "/>
<text text-anchor="middle" x="2390" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="2228.5,-1036.5 2551.5,-1036.5 "/>
<text text-anchor="middle" x="2390" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="2228.5,-1013.5 2551.5,-1013.5 "/>
<text text-anchor="middle" x="2390" y="-998.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="2228.5,-990.5 2551.5,-990.5 "/>
<text text-anchor="middle" x="2390" y="-975.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="2551.5,-967.5 2551.5,-1542.5 "/>
<text text-anchor="middle" x="2562" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2079.4713,-971.3686C2076.6654,-969.8671 2073.8415,-968.4101 2071,-967 1896.1303,-880.2197 1827.8922,-945.28 1633,-934 1583.5978,-931.1407 1234.4936,-932.9439 1188,-916 1187.8962,-915.9622 1187.7924,-915.9242 1187.6885,-915.8862"/>
<polygon fill="#000000" stroke="#000000" points="1188.6603,-912.5079 1178.0727,-912.1168 1186.1055,-919.0251 1188.6603,-912.5079"/>
<text text-anchor="middle" x="2096.5" y="-937.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- study_funding -->
<g id="node15" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M1535.5,-317C1535.5,-317 1914.5,-317 1914.5,-317 1920.5,-317 1926.5,-323 1926.5,-329 1926.5,-329 1926.5,-374 1926.5,-374 1926.5,-380 1920.5,-386 1914.5,-386 1914.5,-386 1535.5,-386 1535.5,-386 1529.5,-386 1523.5,-380 1523.5,-374 1523.5,-374 1523.5,-329 1523.5,-329 1523.5,-323 1529.5,-317 1535.5,-317"/>
<text text-anchor="middle" x="1583" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="1642.5,-317 1642.5,-386 "/>
<text text-anchor="middle" x="1653" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1663.5,-317 1663.5,-386 "/>
<text text-anchor="middle" x="1784.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="1663.5,-363 1905.5,-363 "/>
<text text-anchor="middle" x="1784.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="1663.5,-340 1905.5,-340 "/>
<text text-anchor="middle" x="1784.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="1905.5,-317 1905.5,-386 "/>
<text text-anchor="middle" x="1916" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge5" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1647.2062,-316.9214C1606.3031,-299.0622 1555.1923,-277.2493 1509,-259 1420.6536,-224.0969 1321.0485,-191.4624 1234.7547,-165.2273"/>
<polygon fill="#000000" stroke="#000000" points="1235.6926,-161.8544 1225.1073,-162.3041 1233.6626,-168.5536 1235.6926,-161.8544"/>
<text text-anchor="middle" x="1518" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- clinical_measure_file -->
<g id="node16" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M2033,-651C2033,-651 2385,-651 2385,-651 2391,-651 2397,-657 2397,-663 2397,-663 2397,-892 2397,-892 2397,-898 2391,-904 2385,-904 2385,-904 2033,-904 2033,-904 2027,-904 2021,-898 2021,-892 2021,-892 2021,-663 2021,-663 2021,-657 2027,-651 2033,-651"/>
<text text-anchor="middle" x="2104.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="2188,-651 2188,-904 "/>
<text text-anchor="middle" x="2198.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2209,-651 2209,-904 "/>
<text text-anchor="middle" x="2292.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2209,-881 2376,-881 "/>
<text text-anchor="middle" x="2292.5" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2209,-858 2376,-858 "/>
<text text-anchor="middle" x="2292.5" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2209,-835 2376,-835 "/>
<text text-anchor="middle" x="2292.5" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2209,-812 2376,-812 "/>
<text text-anchor="middle" x="2292.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2209,-789 2376,-789 "/>
<text text-anchor="middle" x="2292.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2209,-766 2376,-766 "/>
<text text-anchor="middle" x="2292.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2209,-743 2376,-743 "/>
<text text-anchor="middle" x="2292.5" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2209,-720 2376,-720 "/>
<text text-anchor="middle" x="2292.5" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2209,-697 2376,-697 "/>
<text text-anchor="middle" x="2292.5" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2209,-674 2376,-674 "/>
<text text-anchor="middle" x="2292.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="2376,-651 2376,-904 "/>
<text text-anchor="middle" x="2386.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2038.3413,-650.9914C2029.6167,-646.6091 2020.8137,-642.5754 2012,-639 1968.91,-621.5201 1704.9166,-583.1843 1538.0293,-560.1328"/>
<polygon fill="#000000" stroke="#000000" points="1538.0618,-556.6042 1527.6774,-558.7053 1537.1056,-563.5386 1538.0618,-556.6042"/>
<text text-anchor="middle" x="2052.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge20" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2199.1778,-650.636C2195.9025,-635.3029 2191.6105,-620.0951 2186,-606 2115.7038,-429.397 2097.3611,-359.4628 1936,-259 1821.9101,-187.9681 1468.6633,-143.8136 1235.1189,-121.5917"/>
<polygon fill="#000000" stroke="#000000" points="1235.4155,-118.1042 1225.1305,-120.6477 1234.7568,-125.0731 1235.4155,-118.1042"/>
<text text-anchor="middle" x="2218" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
</g>
</svg>
</div>
