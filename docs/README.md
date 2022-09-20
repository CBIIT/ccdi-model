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
<svg width="2908pt" height="1384pt"
 viewBox="0.00 0.00 2908.46 1384.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1380)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1380 2904.4566,-1380 2904.4566,4 -4,4"/>
<!-- clinical_measure_file -->
<g id="node1" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M81.9566,-530C81.9566,-530 433.9566,-530 433.9566,-530 439.9566,-530 445.9566,-536 445.9566,-542 445.9566,-542 445.9566,-771 445.9566,-771 445.9566,-777 439.9566,-783 433.9566,-783 433.9566,-783 81.9566,-783 81.9566,-783 75.9566,-783 69.9566,-777 69.9566,-771 69.9566,-771 69.9566,-542 69.9566,-542 69.9566,-536 75.9566,-530 81.9566,-530"/>
<text text-anchor="middle" x="153.4566" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="236.9566,-530 236.9566,-783 "/>
<text text-anchor="middle" x="247.4566" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="257.9566,-530 257.9566,-783 "/>
<text text-anchor="middle" x="341.4566" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="257.9566,-760 424.9566,-760 "/>
<text text-anchor="middle" x="341.4566" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="257.9566,-737 424.9566,-737 "/>
<text text-anchor="middle" x="341.4566" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="257.9566,-714 424.9566,-714 "/>
<text text-anchor="middle" x="341.4566" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="257.9566,-691 424.9566,-691 "/>
<text text-anchor="middle" x="341.4566" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="257.9566,-668 424.9566,-668 "/>
<text text-anchor="middle" x="341.4566" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="257.9566,-645 424.9566,-645 "/>
<text text-anchor="middle" x="341.4566" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="257.9566,-622 424.9566,-622 "/>
<text text-anchor="middle" x="341.4566" y="-606.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="257.9566,-599 424.9566,-599 "/>
<text text-anchor="middle" x="341.4566" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="257.9566,-576 424.9566,-576 "/>
<text text-anchor="middle" x="341.4566" y="-560.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="257.9566,-553 424.9566,-553 "/>
<text text-anchor="middle" x="341.4566" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="424.9566,-530 424.9566,-783 "/>
<text text-anchor="middle" x="435.4566" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node10" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M1027.4566,-294C1027.4566,-294 1258.4566,-294 1258.4566,-294 1264.4566,-294 1270.4566,-300 1270.4566,-306 1270.4566,-306 1270.4566,-397 1270.4566,-397 1270.4566,-403 1264.4566,-409 1258.4566,-409 1258.4566,-409 1027.4566,-409 1027.4566,-409 1021.4566,-409 1015.4566,-403 1015.4566,-397 1015.4566,-397 1015.4566,-306 1015.4566,-306 1015.4566,-300 1021.4566,-294 1027.4566,-294"/>
<text text-anchor="middle" x="1063.4566" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1111.4566,-294 1111.4566,-409 "/>
<text text-anchor="middle" x="1121.9566" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1132.4566,-294 1132.4566,-409 "/>
<text text-anchor="middle" x="1190.9566" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="1132.4566,-386 1249.4566,-386 "/>
<text text-anchor="middle" x="1190.9566" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="1132.4566,-363 1249.4566,-363 "/>
<text text-anchor="middle" x="1190.9566" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1132.4566,-340 1249.4566,-340 "/>
<text text-anchor="middle" x="1190.9566" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1132.4566,-317 1249.4566,-317 "/>
<text text-anchor="middle" x="1190.9566" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="1249.4566,-294 1249.4566,-409 "/>
<text text-anchor="middle" x="1259.9566" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M396.3159,-529.8076C415.1411,-516.6368 434.9088,-504.5895 454.9566,-495 633.3918,-409.6491 861.7254,-374.8509 1005.2109,-360.8066"/>
<polygon fill="#000000" stroke="#000000" points="1005.7728,-364.2688 1015.3934,-359.8308 1005.1051,-357.3008 1005.7728,-364.2688"/>
<text text-anchor="middle" x="654.4566" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- study -->
<g id="node13" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M1368.9566,-.5C1368.9566,-.5 1758.9566,-.5 1758.9566,-.5 1764.9566,-.5 1770.9566,-6.5 1770.9566,-12.5 1770.9566,-12.5 1770.9566,-195.5 1770.9566,-195.5 1770.9566,-201.5 1764.9566,-207.5 1758.9566,-207.5 1758.9566,-207.5 1368.9566,-207.5 1368.9566,-207.5 1362.9566,-207.5 1356.9566,-201.5 1356.9566,-195.5 1356.9566,-195.5 1356.9566,-12.5 1356.9566,-12.5 1356.9566,-6.5 1362.9566,-.5 1368.9566,-.5"/>
<text text-anchor="middle" x="1384.9566" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="1412.9566,-.5 1412.9566,-207.5 "/>
<text text-anchor="middle" x="1423.4566" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1433.9566,-.5 1433.9566,-207.5 "/>
<text text-anchor="middle" x="1591.9566" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="1433.9566,-184.5 1749.9566,-184.5 "/>
<text text-anchor="middle" x="1591.9566" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="1433.9566,-161.5 1749.9566,-161.5 "/>
<text text-anchor="middle" x="1591.9566" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="1433.9566,-138.5 1749.9566,-138.5 "/>
<text text-anchor="middle" x="1591.9566" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="1433.9566,-115.5 1749.9566,-115.5 "/>
<text text-anchor="middle" x="1591.9566" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="1433.9566,-92.5 1749.9566,-92.5 "/>
<text text-anchor="middle" x="1591.9566" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="1433.9566,-69.5 1749.9566,-69.5 "/>
<text text-anchor="middle" x="1591.9566" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="1433.9566,-46.5 1749.9566,-46.5 "/>
<text text-anchor="middle" x="1591.9566" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="1433.9566,-23.5 1749.9566,-23.5 "/>
<text text-anchor="middle" x="1591.9566" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="1749.9566,-.5 1749.9566,-207.5 "/>
<text text-anchor="middle" x="1760.4566" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge5" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M408.1736,-529.9326C438.764,-506.2685 471.2928,-482.5439 502.9566,-462 648.0465,-367.8638 674.2867,-323.0147 834.9566,-259 1000.3414,-193.1068 1198.5301,-153.2699 1346.4886,-130.5148"/>
<polygon fill="#000000" stroke="#000000" points="1347.2482,-133.9396 1356.6069,-128.9733 1346.1938,-127.0194 1347.2482,-133.9396"/>
<text text-anchor="middle" x="920.9566" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- synonym -->
<g id="node2" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M976.4566,-1076.5C976.4566,-1076.5 1277.4566,-1076.5 1277.4566,-1076.5 1283.4566,-1076.5 1289.4566,-1082.5 1289.4566,-1088.5 1289.4566,-1088.5 1289.4566,-1156.5 1289.4566,-1156.5 1289.4566,-1162.5 1283.4566,-1168.5 1277.4566,-1168.5 1277.4566,-1168.5 976.4566,-1168.5 976.4566,-1168.5 970.4566,-1168.5 964.4566,-1162.5 964.4566,-1156.5 964.4566,-1156.5 964.4566,-1088.5 964.4566,-1088.5 964.4566,-1082.5 970.4566,-1076.5 976.4566,-1076.5"/>
<text text-anchor="middle" x="1004.4566" y="-1118.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="1044.4566,-1076.5 1044.4566,-1168.5 "/>
<text text-anchor="middle" x="1054.9566" y="-1118.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1065.4566,-1076.5 1065.4566,-1168.5 "/>
<text text-anchor="middle" x="1166.9566" y="-1153.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_id</text>
<polyline fill="none" stroke="#000000" points="1065.4566,-1145.5 1268.4566,-1145.5 "/>
<text text-anchor="middle" x="1166.9566" y="-1130.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_node</text>
<polyline fill="none" stroke="#000000" points="1065.4566,-1122.5 1268.4566,-1122.5 "/>
<text text-anchor="middle" x="1166.9566" y="-1107.3" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="1065.4566,-1099.5 1268.4566,-1099.5 "/>
<text text-anchor="middle" x="1166.9566" y="-1084.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="1268.4566,-1076.5 1268.4566,-1168.5 "/>
<text text-anchor="middle" x="1278.9566" y="-1118.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node7" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1429.9566,-495.5C1429.9566,-495.5 1743.9566,-495.5 1743.9566,-495.5 1749.9566,-495.5 1755.9566,-501.5 1755.9566,-507.5 1755.9566,-507.5 1755.9566,-805.5 1755.9566,-805.5 1755.9566,-811.5 1749.9566,-817.5 1743.9566,-817.5 1743.9566,-817.5 1429.9566,-817.5 1429.9566,-817.5 1423.9566,-817.5 1417.9566,-811.5 1417.9566,-805.5 1417.9566,-805.5 1417.9566,-507.5 1417.9566,-507.5 1417.9566,-501.5 1423.9566,-495.5 1429.9566,-495.5"/>
<text text-anchor="middle" x="1451.9566" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1485.9566,-495.5 1485.9566,-817.5 "/>
<text text-anchor="middle" x="1496.4566" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1506.9566,-495.5 1506.9566,-817.5 "/>
<text text-anchor="middle" x="1620.9566" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1506.9566,-794.5 1734.9566,-794.5 "/>
<text text-anchor="middle" x="1620.9566" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1506.9566,-771.5 1734.9566,-771.5 "/>
<text text-anchor="middle" x="1620.9566" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1506.9566,-748.5 1734.9566,-748.5 "/>
<text text-anchor="middle" x="1620.9566" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1506.9566,-725.5 1734.9566,-725.5 "/>
<text text-anchor="middle" x="1620.9566" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1506.9566,-702.5 1734.9566,-702.5 "/>
<text text-anchor="middle" x="1620.9566" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="1506.9566,-679.5 1734.9566,-679.5 "/>
<text text-anchor="middle" x="1620.9566" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1506.9566,-656.5 1734.9566,-656.5 "/>
<text text-anchor="middle" x="1620.9566" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="1506.9566,-633.5 1734.9566,-633.5 "/>
<text text-anchor="middle" x="1620.9566" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="1506.9566,-610.5 1734.9566,-610.5 "/>
<text text-anchor="middle" x="1620.9566" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage</text>
<polyline fill="none" stroke="#000000" points="1506.9566,-587.5 1734.9566,-587.5 "/>
<text text-anchor="middle" x="1620.9566" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1506.9566,-564.5 1734.9566,-564.5 "/>
<text text-anchor="middle" x="1620.9566" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1506.9566,-541.5 1734.9566,-541.5 "/>
<text text-anchor="middle" x="1620.9566" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1506.9566,-518.5 1734.9566,-518.5 "/>
<text text-anchor="middle" x="1620.9566" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_status</text>
<polyline fill="none" stroke="#000000" points="1734.9566,-495.5 1734.9566,-817.5 "/>
<text text-anchor="middle" x="1745.4566" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1148.7536,-1076.4155C1176.861,-1021.085 1230.3899,-928.3416 1298.9566,-869 1318.571,-852.0246 1382.3675,-832.3805 1403.9566,-818 1405.6758,-816.8548 1407.396,-815.6947 1409.1163,-814.5206"/>
<polygon fill="#000000" stroke="#000000" points="1411.506,-817.1218 1417.7168,-808.5383 1407.5089,-811.3753 1411.506,-817.1218"/>
<text text-anchor="middle" x="1407.4566" y="-839.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1159.8212,-1076.4956C1198.7014,-1019.1455 1261.4861,-916.6163 1287.9566,-818 1308.4793,-741.5426 1337.5302,-532.2089 1300.9566,-462 1291.8041,-444.4303 1278.4388,-429.0784 1263.2978,-415.858"/>
<polygon fill="#000000" stroke="#000000" points="1265.1547,-412.8495 1255.2311,-409.1384 1260.6745,-418.228 1265.1547,-412.8495"/>
<text text-anchor="middle" x="1360.4566" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge8" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M964.3362,-1100.033C693.7402,-1058.9508 169.9124,-962.4366 60.9566,-818 -25.4954,-703.3953 -14.2011,-617.3091 60.9566,-495 182.5009,-297.203 305.7656,-329.5069 526.9566,-259 801.8265,-171.3824 1133.8038,-132.8441 1346.834,-116.1974"/>
<polygon fill="#000000" stroke="#000000" points="1347.1869,-119.6807 1356.8877,-115.4212 1346.6479,-112.7015 1347.1869,-119.6807"/>
<text text-anchor="middle" x="123.4566" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study_personnel -->
<g id="node3" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M1539.4566,-294C1539.4566,-294 1846.4566,-294 1846.4566,-294 1852.4566,-294 1858.4566,-300 1858.4566,-306 1858.4566,-306 1858.4566,-397 1858.4566,-397 1858.4566,-403 1852.4566,-409 1846.4566,-409 1846.4566,-409 1539.4566,-409 1539.4566,-409 1533.4566,-409 1527.4566,-403 1527.4566,-397 1527.4566,-397 1527.4566,-306 1527.4566,-306 1527.4566,-300 1533.4566,-294 1539.4566,-294"/>
<text text-anchor="middle" x="1594.4566" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="1661.4566,-294 1661.4566,-409 "/>
<text text-anchor="middle" x="1671.9566" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1682.4566,-294 1682.4566,-409 "/>
<text text-anchor="middle" x="1759.9566" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="1682.4566,-386 1837.4566,-386 "/>
<text text-anchor="middle" x="1759.9566" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="1682.4566,-363 1837.4566,-363 "/>
<text text-anchor="middle" x="1759.9566" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="1682.4566,-340 1837.4566,-340 "/>
<text text-anchor="middle" x="1759.9566" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="1682.4566,-317 1837.4566,-317 "/>
<text text-anchor="middle" x="1759.9566" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="1837.4566,-294 1837.4566,-409 "/>
<text text-anchor="middle" x="1847.9566" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1662.8747,-293.7846C1650.9016,-270.813 1636.6907,-243.548 1622.8292,-216.9532"/>
<polygon fill="#000000" stroke="#000000" points="1625.8712,-215.2171 1618.1455,-207.967 1619.6638,-218.4525 1625.8712,-215.2171"/>
<text text-anchor="middle" x="1701.4566" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- study_admin -->
<g id="node4" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M1888.9566,-259.5C1888.9566,-259.5 2214.9566,-259.5 2214.9566,-259.5 2220.9566,-259.5 2226.9566,-265.5 2226.9566,-271.5 2226.9566,-271.5 2226.9566,-431.5 2226.9566,-431.5 2226.9566,-437.5 2220.9566,-443.5 2214.9566,-443.5 2214.9566,-443.5 1888.9566,-443.5 1888.9566,-443.5 1882.9566,-443.5 1876.9566,-437.5 1876.9566,-431.5 1876.9566,-431.5 1876.9566,-271.5 1876.9566,-271.5 1876.9566,-265.5 1882.9566,-259.5 1888.9566,-259.5"/>
<text text-anchor="middle" x="1930.9566" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="1984.9566,-259.5 1984.9566,-443.5 "/>
<text text-anchor="middle" x="1995.4566" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2005.9566,-259.5 2005.9566,-443.5 "/>
<text text-anchor="middle" x="2105.9566" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="2005.9566,-420.5 2205.9566,-420.5 "/>
<text text-anchor="middle" x="2105.9566" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="2005.9566,-397.5 2205.9566,-397.5 "/>
<text text-anchor="middle" x="2105.9566" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="2005.9566,-374.5 2205.9566,-374.5 "/>
<text text-anchor="middle" x="2105.9566" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="2005.9566,-351.5 2205.9566,-351.5 "/>
<text text-anchor="middle" x="2105.9566" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="2005.9566,-328.5 2205.9566,-328.5 "/>
<text text-anchor="middle" x="2105.9566" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="2005.9566,-305.5 2205.9566,-305.5 "/>
<text text-anchor="middle" x="2105.9566" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="2005.9566,-282.5 2205.9566,-282.5 "/>
<text text-anchor="middle" x="2105.9566" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="2205.9566,-259.5 2205.9566,-443.5 "/>
<text text-anchor="middle" x="2216.4566" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge16" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1876.8114,-262.6712C1844.4394,-246.253 1810.3062,-228.9417 1776.9583,-212.0285"/>
<polygon fill="#000000" stroke="#000000" points="1778.5405,-208.9066 1768.0388,-207.5048 1775.3742,-215.1496 1778.5405,-208.9066"/>
<text text-anchor="middle" x="1878.4566" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- methylation_array_file -->
<g id="node5" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M2161.9566,-1007.5C2161.9566,-1007.5 2507.9566,-1007.5 2507.9566,-1007.5 2513.9566,-1007.5 2519.9566,-1013.5 2519.9566,-1019.5 2519.9566,-1019.5 2519.9566,-1225.5 2519.9566,-1225.5 2519.9566,-1231.5 2513.9566,-1237.5 2507.9566,-1237.5 2507.9566,-1237.5 2161.9566,-1237.5 2161.9566,-1237.5 2155.9566,-1237.5 2149.9566,-1231.5 2149.9566,-1225.5 2149.9566,-1225.5 2149.9566,-1019.5 2149.9566,-1019.5 2149.9566,-1013.5 2155.9566,-1007.5 2161.9566,-1007.5"/>
<text text-anchor="middle" x="2238.9566" y="-1118.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="2327.9566,-1007.5 2327.9566,-1237.5 "/>
<text text-anchor="middle" x="2338.4566" y="-1118.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2348.9566,-1007.5 2348.9566,-1237.5 "/>
<text text-anchor="middle" x="2423.9566" y="-1222.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2348.9566,-1214.5 2498.9566,-1214.5 "/>
<text text-anchor="middle" x="2423.9566" y="-1199.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2348.9566,-1191.5 2498.9566,-1191.5 "/>
<text text-anchor="middle" x="2423.9566" y="-1176.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2348.9566,-1168.5 2498.9566,-1168.5 "/>
<text text-anchor="middle" x="2423.9566" y="-1153.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2348.9566,-1145.5 2498.9566,-1145.5 "/>
<text text-anchor="middle" x="2423.9566" y="-1130.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2348.9566,-1122.5 2498.9566,-1122.5 "/>
<text text-anchor="middle" x="2423.9566" y="-1107.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2348.9566,-1099.5 2498.9566,-1099.5 "/>
<text text-anchor="middle" x="2423.9566" y="-1084.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2348.9566,-1076.5 2498.9566,-1076.5 "/>
<text text-anchor="middle" x="2423.9566" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">label</text>
<polyline fill="none" stroke="#000000" points="2348.9566,-1053.5 2498.9566,-1053.5 "/>
<text text-anchor="middle" x="2423.9566" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2348.9566,-1030.5 2498.9566,-1030.5 "/>
<text text-anchor="middle" x="2423.9566" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="2498.9566,-1007.5 2498.9566,-1237.5 "/>
<text text-anchor="middle" x="2509.4566" y="-1118.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2267.0536,-1007.3844C2234.018,-959.3304 2190.6709,-906.1634 2140.9566,-869 2029.3062,-785.5368 1880.8962,-730.9347 1765.7853,-698.0029"/>
<polygon fill="#000000" stroke="#000000" points="1766.733,-694.6337 1756.1577,-695.2767 1764.8258,-701.3689 1766.733,-694.6337"/>
<text text-anchor="middle" x="2206.4566" y="-839.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- publication -->
<g id="node6" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M2256.9566,-333.5C2256.9566,-333.5 2466.9566,-333.5 2466.9566,-333.5 2472.9566,-333.5 2478.9566,-339.5 2478.9566,-345.5 2478.9566,-345.5 2478.9566,-357.5 2478.9566,-357.5 2478.9566,-363.5 2472.9566,-369.5 2466.9566,-369.5 2466.9566,-369.5 2256.9566,-369.5 2256.9566,-369.5 2250.9566,-369.5 2244.9566,-363.5 2244.9566,-357.5 2244.9566,-357.5 2244.9566,-345.5 2244.9566,-345.5 2244.9566,-339.5 2250.9566,-333.5 2256.9566,-333.5"/>
<text text-anchor="middle" x="2293.4566" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="2341.9566,-333.5 2341.9566,-369.5 "/>
<text text-anchor="middle" x="2352.4566" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2362.9566,-333.5 2362.9566,-369.5 "/>
<text text-anchor="middle" x="2410.4566" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="2457.9566,-333.5 2457.9566,-369.5 "/>
<text text-anchor="middle" x="2468.4566" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge4" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2342.6346,-333.3355C2319.2022,-312.3059 2277.6434,-278.1173 2235.9566,-259 2091.6921,-192.8412 1916.6519,-153.6382 1781.3878,-131.214"/>
<polygon fill="#000000" stroke="#000000" points="1781.7432,-127.7256 1771.3087,-129.5618 1780.6108,-134.6334 1781.7432,-127.7256"/>
<text text-anchor="middle" x="2234.9566" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1417.7012,-503.2568C1413.1388,-500.3889 1408.554,-497.6303 1403.9566,-495 1381.632,-482.2273 1372.1487,-488.1201 1348.9566,-477 1337.9522,-471.7236 1336.2929,-468.4884 1325.9566,-462 1300.9633,-446.3108 1273.8419,-429.7078 1248.3253,-414.2722"/>
<polygon fill="#000000" stroke="#000000" points="1250.108,-411.2601 1239.7388,-409.0852 1246.4886,-417.2517 1250.108,-411.2601"/>
<text text-anchor="middle" x="1385.4566" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge6" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1466.7392,-495.3814C1458.3773,-478.6429 1451.1981,-461.3796 1445.9566,-444 1422.2155,-365.2799 1419.6755,-336.9089 1445.9566,-259 1450.8782,-244.4102 1457.7813,-230.1076 1465.8055,-216.4512"/>
<polygon fill="#000000" stroke="#000000" points="1469.0025,-217.9318 1471.2308,-207.5739 1463.0296,-214.2814 1469.0025,-217.9318"/>
<text text-anchor="middle" x="1482.4566" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sequencing_file -->
<g id="node8" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M1319.4566,-869.5C1319.4566,-869.5 1788.4566,-869.5 1788.4566,-869.5 1794.4566,-869.5 1800.4566,-875.5 1800.4566,-881.5 1800.4566,-881.5 1800.4566,-1363.5 1800.4566,-1363.5 1800.4566,-1369.5 1794.4566,-1375.5 1788.4566,-1375.5 1788.4566,-1375.5 1319.4566,-1375.5 1319.4566,-1375.5 1313.4566,-1375.5 1307.4566,-1369.5 1307.4566,-1363.5 1307.4566,-1363.5 1307.4566,-881.5 1307.4566,-881.5 1307.4566,-875.5 1313.4566,-869.5 1319.4566,-869.5"/>
<text text-anchor="middle" x="1371.4566" y="-1118.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="1435.4566,-869.5 1435.4566,-1375.5 "/>
<text text-anchor="middle" x="1445.9566" y="-1118.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1456.4566,-869.5 1456.4566,-1375.5 "/>
<text text-anchor="middle" x="1617.9566" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="1456.4566,-1352.5 1779.4566,-1352.5 "/>
<text text-anchor="middle" x="1617.9566" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1456.4566,-1329.5 1779.4566,-1329.5 "/>
<text text-anchor="middle" x="1617.9566" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1456.4566,-1306.5 1779.4566,-1306.5 "/>
<text text-anchor="middle" x="1617.9566" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="1456.4566,-1283.5 1779.4566,-1283.5 "/>
<text text-anchor="middle" x="1617.9566" y="-1268.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="1456.4566,-1260.5 1779.4566,-1260.5 "/>
<text text-anchor="middle" x="1617.9566" y="-1245.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1456.4566,-1237.5 1779.4566,-1237.5 "/>
<text text-anchor="middle" x="1617.9566" y="-1222.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1456.4566,-1214.5 1779.4566,-1214.5 "/>
<text text-anchor="middle" x="1617.9566" y="-1199.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1456.4566,-1191.5 1779.4566,-1191.5 "/>
<text text-anchor="middle" x="1617.9566" y="-1176.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1456.4566,-1168.5 1779.4566,-1168.5 "/>
<text text-anchor="middle" x="1617.9566" y="-1153.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1456.4566,-1145.5 1779.4566,-1145.5 "/>
<text text-anchor="middle" x="1617.9566" y="-1130.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1456.4566,-1122.5 1779.4566,-1122.5 "/>
<text text-anchor="middle" x="1617.9566" y="-1107.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1456.4566,-1099.5 1779.4566,-1099.5 "/>
<text text-anchor="middle" x="1617.9566" y="-1084.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="1456.4566,-1076.5 1779.4566,-1076.5 "/>
<text text-anchor="middle" x="1617.9566" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="1456.4566,-1053.5 1779.4566,-1053.5 "/>
<text text-anchor="middle" x="1617.9566" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="1456.4566,-1030.5 1779.4566,-1030.5 "/>
<text text-anchor="middle" x="1617.9566" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="1456.4566,-1007.5 1779.4566,-1007.5 "/>
<text text-anchor="middle" x="1617.9566" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="1456.4566,-984.5 1779.4566,-984.5 "/>
<text text-anchor="middle" x="1617.9566" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1456.4566,-961.5 1779.4566,-961.5 "/>
<text text-anchor="middle" x="1617.9566" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="1456.4566,-938.5 1779.4566,-938.5 "/>
<text text-anchor="middle" x="1617.9566" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="1456.4566,-915.5 1779.4566,-915.5 "/>
<text text-anchor="middle" x="1617.9566" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="1456.4566,-892.5 1779.4566,-892.5 "/>
<text text-anchor="middle" x="1617.9566" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="1779.4566,-869.5 1779.4566,-1375.5 "/>
<text text-anchor="middle" x="1789.9566" y="-1118.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1571.8811,-869.3851C1572.87,-855.42 1573.8521,-841.552 1574.8129,-827.9838"/>
<polygon fill="#000000" stroke="#000000" points="1578.3281,-827.8922 1575.5433,-817.6699 1571.3456,-827.3977 1578.3281,-827.8922"/>
<text text-anchor="middle" x="1639.4566" y="-839.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- study_funding -->
<g id="node9" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M2509.4566,-282.5C2509.4566,-282.5 2888.4566,-282.5 2888.4566,-282.5 2894.4566,-282.5 2900.4566,-288.5 2900.4566,-294.5 2900.4566,-294.5 2900.4566,-408.5 2900.4566,-408.5 2900.4566,-414.5 2894.4566,-420.5 2888.4566,-420.5 2888.4566,-420.5 2509.4566,-420.5 2509.4566,-420.5 2503.4566,-420.5 2497.4566,-414.5 2497.4566,-408.5 2497.4566,-408.5 2497.4566,-294.5 2497.4566,-294.5 2497.4566,-288.5 2503.4566,-282.5 2509.4566,-282.5"/>
<text text-anchor="middle" x="2556.9566" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="2616.4566,-282.5 2616.4566,-420.5 "/>
<text text-anchor="middle" x="2626.9566" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2637.4566,-282.5 2637.4566,-420.5 "/>
<text text-anchor="middle" x="2758.4566" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="2637.4566,-397.5 2879.4566,-397.5 "/>
<text text-anchor="middle" x="2758.4566" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="2637.4566,-374.5 2879.4566,-374.5 "/>
<text text-anchor="middle" x="2758.4566" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_system</text>
<polyline fill="none" stroke="#000000" points="2637.4566,-351.5 2879.4566,-351.5 "/>
<text text-anchor="middle" x="2758.4566" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="2637.4566,-328.5 2879.4566,-328.5 "/>
<text text-anchor="middle" x="2758.4566" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="2637.4566,-305.5 2879.4566,-305.5 "/>
<text text-anchor="middle" x="2758.4566" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="2879.4566,-282.5 2879.4566,-420.5 "/>
<text text-anchor="middle" x="2889.9566" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge12" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2553.9987,-282.4047C2532.1869,-273.6384 2509.7094,-265.4837 2487.9566,-259 2251.5453,-188.5345 1970.9507,-147.16 1781.4968,-125.1392"/>
<polygon fill="#000000" stroke="#000000" points="1781.751,-121.6454 1771.4157,-123.9757 1780.9484,-128.5992 1781.751,-121.6454"/>
<text text-anchor="middle" x="2475.9566" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge17" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1219.2623,-293.9452C1250.1461,-271.6531 1286.5734,-246.5964 1320.9566,-226 1329.7028,-220.7608 1338.7029,-215.5373 1347.8516,-210.3641"/>
<polygon fill="#000000" stroke="#000000" points="1349.6556,-213.3652 1356.6653,-205.4207 1346.2313,-207.26 1349.6556,-213.3652"/>
<text text-anchor="middle" x="1371.4566" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- diagnosis -->
<g id="node11" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M476.4566,-507C476.4566,-507 859.4566,-507 859.4566,-507 865.4566,-507 871.4566,-513 871.4566,-519 871.4566,-519 871.4566,-794 871.4566,-794 871.4566,-800 865.4566,-806 859.4566,-806 859.4566,-806 476.4566,-806 476.4566,-806 470.4566,-806 464.4566,-800 464.4566,-794 464.4566,-794 464.4566,-519 464.4566,-519 464.4566,-513 470.4566,-507 476.4566,-507"/>
<text text-anchor="middle" x="506.4566" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="548.4566,-507 548.4566,-806 "/>
<text text-anchor="middle" x="558.9566" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="569.4566,-507 569.4566,-806 "/>
<text text-anchor="middle" x="709.9566" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="569.4566,-783 850.4566,-783 "/>
<text text-anchor="middle" x="709.9566" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="569.4566,-760 850.4566,-760 "/>
<text text-anchor="middle" x="709.9566" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="569.4566,-737 850.4566,-737 "/>
<text text-anchor="middle" x="709.9566" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="569.4566,-714 850.4566,-714 "/>
<text text-anchor="middle" x="709.9566" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="569.4566,-691 850.4566,-691 "/>
<text text-anchor="middle" x="709.9566" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="569.4566,-668 850.4566,-668 "/>
<text text-anchor="middle" x="709.9566" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="569.4566,-645 850.4566,-645 "/>
<text text-anchor="middle" x="709.9566" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="569.4566,-622 850.4566,-622 "/>
<text text-anchor="middle" x="709.9566" y="-606.8" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis_reference_source</text>
<polyline fill="none" stroke="#000000" points="569.4566,-599 850.4566,-599 "/>
<text text-anchor="middle" x="709.9566" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="569.4566,-576 850.4566,-576 "/>
<text text-anchor="middle" x="709.9566" y="-560.8" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="569.4566,-553 850.4566,-553 "/>
<text text-anchor="middle" x="709.9566" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="569.4566,-530 850.4566,-530 "/>
<text text-anchor="middle" x="709.9566" y="-514.8" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="850.4566,-507 850.4566,-806 "/>
<text text-anchor="middle" x="860.9566" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M862.0812,-506.836C868.0689,-502.7932 874.0362,-498.8387 879.9566,-495 924.2475,-466.2822 974.7533,-437.782 1019.5862,-413.8399"/>
<polygon fill="#000000" stroke="#000000" points="1021.2879,-416.8992 1028.4737,-409.1135 1018.0011,-410.7188 1021.2879,-416.8992"/>
<text text-anchor="middle" x="972.4566" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- therapeutic_procedure -->
<g id="node12" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M901.4566,-599C901.4566,-599 1266.4566,-599 1266.4566,-599 1272.4566,-599 1278.4566,-605 1278.4566,-611 1278.4566,-611 1278.4566,-702 1278.4566,-702 1278.4566,-708 1272.4566,-714 1266.4566,-714 1266.4566,-714 901.4566,-714 901.4566,-714 895.4566,-714 889.4566,-708 889.4566,-702 889.4566,-702 889.4566,-611 889.4566,-611 889.4566,-605 895.4566,-599 901.4566,-599"/>
<text text-anchor="middle" x="979.9566" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="1070.4566,-599 1070.4566,-714 "/>
<text text-anchor="middle" x="1080.9566" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1091.4566,-599 1091.4566,-714 "/>
<text text-anchor="middle" x="1174.4566" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="1091.4566,-691 1257.4566,-691 "/>
<text text-anchor="middle" x="1174.4566" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="1091.4566,-668 1257.4566,-668 "/>
<text text-anchor="middle" x="1174.4566" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatement_outcome</text>
<polyline fill="none" stroke="#000000" points="1091.4566,-645 1257.4566,-645 "/>
<text text-anchor="middle" x="1174.4566" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1091.4566,-622 1257.4566,-622 "/>
<text text-anchor="middle" x="1174.4566" y="-606.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1257.4566,-599 1257.4566,-714 "/>
<text text-anchor="middle" x="1267.9566" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1091.7603,-598.8064C1097.3533,-559.9765 1105.5416,-507.7148 1114.9566,-462 1117.8156,-448.1181 1121.2663,-433.3552 1124.754,-419.2907"/>
<polygon fill="#000000" stroke="#000000" points="1128.2481,-419.7472 1127.2921,-409.1956 1121.4593,-418.0403 1128.2481,-419.7472"/>
<text text-anchor="middle" x="1207.9566" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- imaging_file -->
<g id="node14" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M1830.4566,-961.5C1830.4566,-961.5 2119.4566,-961.5 2119.4566,-961.5 2125.4566,-961.5 2131.4566,-967.5 2131.4566,-973.5 2131.4566,-973.5 2131.4566,-1271.5 2131.4566,-1271.5 2131.4566,-1277.5 2125.4566,-1283.5 2119.4566,-1283.5 2119.4566,-1283.5 1830.4566,-1283.5 1830.4566,-1283.5 1824.4566,-1283.5 1818.4566,-1277.5 1818.4566,-1271.5 1818.4566,-1271.5 1818.4566,-973.5 1818.4566,-973.5 1818.4566,-967.5 1824.4566,-961.5 1830.4566,-961.5"/>
<text text-anchor="middle" x="1870.4566" y="-1118.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="1922.4566,-961.5 1922.4566,-1283.5 "/>
<text text-anchor="middle" x="1932.9566" y="-1118.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1943.4566,-961.5 1943.4566,-1283.5 "/>
<text text-anchor="middle" x="2026.9566" y="-1268.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1943.4566,-1260.5 2110.4566,-1260.5 "/>
<text text-anchor="middle" x="2026.9566" y="-1245.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1943.4566,-1237.5 2110.4566,-1237.5 "/>
<text text-anchor="middle" x="2026.9566" y="-1222.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1943.4566,-1214.5 2110.4566,-1214.5 "/>
<text text-anchor="middle" x="2026.9566" y="-1199.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1943.4566,-1191.5 2110.4566,-1191.5 "/>
<text text-anchor="middle" x="2026.9566" y="-1176.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1943.4566,-1168.5 2110.4566,-1168.5 "/>
<text text-anchor="middle" x="2026.9566" y="-1153.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1943.4566,-1145.5 2110.4566,-1145.5 "/>
<text text-anchor="middle" x="2026.9566" y="-1130.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1943.4566,-1122.5 2110.4566,-1122.5 "/>
<text text-anchor="middle" x="2026.9566" y="-1107.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1943.4566,-1099.5 2110.4566,-1099.5 "/>
<text text-anchor="middle" x="2026.9566" y="-1084.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1943.4566,-1076.5 2110.4566,-1076.5 "/>
<text text-anchor="middle" x="2026.9566" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="1943.4566,-1053.5 2110.4566,-1053.5 "/>
<text text-anchor="middle" x="2026.9566" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="1943.4566,-1030.5 2110.4566,-1030.5 "/>
<text text-anchor="middle" x="2026.9566" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="1943.4566,-1007.5 2110.4566,-1007.5 "/>
<text text-anchor="middle" x="2026.9566" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1943.4566,-984.5 2110.4566,-984.5 "/>
<text text-anchor="middle" x="2026.9566" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="2110.4566,-961.5 2110.4566,-1283.5 "/>
<text text-anchor="middle" x="2120.9566" y="-1118.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1878.095,-961.2757C1856.9198,-929.7197 1833.6984,-897.5764 1809.9566,-869 1795.3789,-851.4538 1779.4679,-833.855 1763.0725,-816.7083"/>
<polygon fill="#000000" stroke="#000000" points="1765.4782,-814.1607 1756.0188,-809.3889 1760.4378,-819.0182 1765.4782,-814.1607"/>
<text text-anchor="middle" x="1847.4566" y="-839.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
</g>
</svg>
</div>
