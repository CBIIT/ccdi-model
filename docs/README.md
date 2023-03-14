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
<svg width="3299pt" height="1735pt"
 viewBox="0.00 0.00 3299.00 1735.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1731)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1731 3295,-1731 3295,4 -4,4"/>
<!-- study -->
<g id="node1" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M1507,-.5C1507,-.5 1897,-.5 1897,-.5 1903,-.5 1909,-6.5 1909,-12.5 1909,-12.5 1909,-264.5 1909,-264.5 1909,-270.5 1903,-276.5 1897,-276.5 1897,-276.5 1507,-276.5 1507,-276.5 1501,-276.5 1495,-270.5 1495,-264.5 1495,-264.5 1495,-12.5 1495,-12.5 1495,-6.5 1501,-.5 1507,-.5"/>
<text text-anchor="middle" x="1523" y="-134.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="1551,-.5 1551,-276.5 "/>
<text text-anchor="middle" x="1561.5" y="-134.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1572,-.5 1572,-276.5 "/>
<text text-anchor="middle" x="1730" y="-261.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="1572,-253.5 1888,-253.5 "/>
<text text-anchor="middle" x="1730" y="-238.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="1572,-230.5 1888,-230.5 "/>
<text text-anchor="middle" x="1730" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_shorthand</text>
<polyline fill="none" stroke="#000000" points="1572,-207.5 1888,-207.5 "/>
<text text-anchor="middle" x="1730" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="1572,-184.5 1888,-184.5 "/>
<text text-anchor="middle" x="1730" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="1572,-161.5 1888,-161.5 "/>
<text text-anchor="middle" x="1730" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="1572,-138.5 1888,-138.5 "/>
<text text-anchor="middle" x="1730" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="1572,-115.5 1888,-115.5 "/>
<text text-anchor="middle" x="1730" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="1572,-92.5 1888,-92.5 "/>
<text text-anchor="middle" x="1730" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="1572,-69.5 1888,-69.5 "/>
<text text-anchor="middle" x="1730" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="1572,-46.5 1888,-46.5 "/>
<text text-anchor="middle" x="1730" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="1572,-23.5 1888,-23.5 "/>
<text text-anchor="middle" x="1730" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="1888,-.5 1888,-276.5 "/>
<text text-anchor="middle" x="1898.5" y="-134.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication -->
<g id="node2" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M312,-391C312,-391 522,-391 522,-391 528,-391 534,-397 534,-403 534,-403 534,-415 534,-415 534,-421 528,-427 522,-427 522,-427 312,-427 312,-427 306,-427 300,-421 300,-415 300,-415 300,-403 300,-403 300,-397 306,-391 312,-391"/>
<text text-anchor="middle" x="348.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="397,-391 397,-427 "/>
<text text-anchor="middle" x="407.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="418,-391 418,-427 "/>
<text text-anchor="middle" x="465.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="513,-391 513,-427 "/>
<text text-anchor="middle" x="523.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge16" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M439.1375,-390.7145C463.168,-371.8805 503.4298,-343.1979 543,-328 856.5874,-207.5588 1246.5967,-163.6547 1484.7699,-147.6584"/>
<polygon fill="#000000" stroke="#000000" points="1485.1909,-151.1383 1494.9383,-146.9862 1484.7291,-144.1535 1485.1909,-151.1383"/>
<text text-anchor="middle" x="684" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- study_funding -->
<g id="node3" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M564.5,-374.5C564.5,-374.5 943.5,-374.5 943.5,-374.5 949.5,-374.5 955.5,-380.5 955.5,-386.5 955.5,-386.5 955.5,-431.5 955.5,-431.5 955.5,-437.5 949.5,-443.5 943.5,-443.5 943.5,-443.5 564.5,-443.5 564.5,-443.5 558.5,-443.5 552.5,-437.5 552.5,-431.5 552.5,-431.5 552.5,-386.5 552.5,-386.5 552.5,-380.5 558.5,-374.5 564.5,-374.5"/>
<text text-anchor="middle" x="612" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="671.5,-374.5 671.5,-443.5 "/>
<text text-anchor="middle" x="682" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="692.5,-374.5 692.5,-443.5 "/>
<text text-anchor="middle" x="813.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="692.5,-420.5 934.5,-420.5 "/>
<text text-anchor="middle" x="813.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="692.5,-397.5 934.5,-397.5 "/>
<text text-anchor="middle" x="813.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="934.5,-374.5 934.5,-443.5 "/>
<text text-anchor="middle" x="945" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge20" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M837.4074,-374.4423C875.8856,-359.1586 922.3882,-341.6077 965,-328 1137.6966,-272.8509 1337.0101,-222.3768 1484.7865,-187.4115"/>
<polygon fill="#000000" stroke="#000000" points="1485.9622,-190.7302 1494.8903,-185.026 1484.3536,-183.9175 1485.9622,-190.7302"/>
<text text-anchor="middle" x="1126" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- study_admin -->
<g id="node4" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M986,-328.5C986,-328.5 1312,-328.5 1312,-328.5 1318,-328.5 1324,-334.5 1324,-340.5 1324,-340.5 1324,-477.5 1324,-477.5 1324,-483.5 1318,-489.5 1312,-489.5 1312,-489.5 986,-489.5 986,-489.5 980,-489.5 974,-483.5 974,-477.5 974,-477.5 974,-340.5 974,-340.5 974,-334.5 980,-328.5 986,-328.5"/>
<text text-anchor="middle" x="1028" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="1082,-328.5 1082,-489.5 "/>
<text text-anchor="middle" x="1092.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1103,-328.5 1103,-489.5 "/>
<text text-anchor="middle" x="1203" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="1103,-466.5 1303,-466.5 "/>
<text text-anchor="middle" x="1203" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="1103,-443.5 1303,-443.5 "/>
<text text-anchor="middle" x="1203" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="1103,-420.5 1303,-420.5 "/>
<text text-anchor="middle" x="1203" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="1103,-397.5 1303,-397.5 "/>
<text text-anchor="middle" x="1203" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="1103,-374.5 1303,-374.5 "/>
<text text-anchor="middle" x="1203" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="1103,-351.5 1303,-351.5 "/>
<text text-anchor="middle" x="1203" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="1303,-328.5 1303,-489.5 "/>
<text text-anchor="middle" x="1313.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge14" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1313.795,-328.3905C1367.7298,-302.0083 1428.4813,-272.2917 1485.6312,-244.3368"/>
<polygon fill="#000000" stroke="#000000" points="1487.3258,-247.4042 1494.7708,-239.8662 1484.25,-241.1162 1487.3258,-247.4042"/>
<text text-anchor="middle" x="1432.5" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- study_personnel -->
<g id="node5" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M1354.5,-351.5C1354.5,-351.5 1661.5,-351.5 1661.5,-351.5 1667.5,-351.5 1673.5,-357.5 1673.5,-363.5 1673.5,-363.5 1673.5,-454.5 1673.5,-454.5 1673.5,-460.5 1667.5,-466.5 1661.5,-466.5 1661.5,-466.5 1354.5,-466.5 1354.5,-466.5 1348.5,-466.5 1342.5,-460.5 1342.5,-454.5 1342.5,-454.5 1342.5,-363.5 1342.5,-363.5 1342.5,-357.5 1348.5,-351.5 1354.5,-351.5"/>
<text text-anchor="middle" x="1409.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="1476.5,-351.5 1476.5,-466.5 "/>
<text text-anchor="middle" x="1487" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1497.5,-351.5 1497.5,-466.5 "/>
<text text-anchor="middle" x="1575" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="1497.5,-443.5 1652.5,-443.5 "/>
<text text-anchor="middle" x="1575" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="1497.5,-420.5 1652.5,-420.5 "/>
<text text-anchor="middle" x="1575" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="1497.5,-397.5 1652.5,-397.5 "/>
<text text-anchor="middle" x="1575" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="1497.5,-374.5 1652.5,-374.5 "/>
<text text-anchor="middle" x="1575" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="1652.5,-351.5 1652.5,-466.5 "/>
<text text-anchor="middle" x="1663" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge4" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1523.3658,-351.4142C1529.7468,-332.6315 1538.2244,-312.2 1549,-295 1551.0961,-291.6542 1553.2741,-288.3222 1555.5239,-285.0084"/>
<polygon fill="#000000" stroke="#000000" points="1558.394,-287.0114 1561.2583,-276.8111 1552.6582,-282.9989 1558.394,-287.0114"/>
<text text-anchor="middle" x="1618.5" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- synonym -->
<g id="node6" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M2154.5,-1416C2154.5,-1416 2455.5,-1416 2455.5,-1416 2461.5,-1416 2467.5,-1422 2467.5,-1428 2467.5,-1428 2467.5,-1450 2467.5,-1450 2467.5,-1456 2461.5,-1462 2455.5,-1462 2455.5,-1462 2154.5,-1462 2154.5,-1462 2148.5,-1462 2142.5,-1456 2142.5,-1450 2142.5,-1450 2142.5,-1428 2142.5,-1428 2142.5,-1422 2148.5,-1416 2154.5,-1416"/>
<text text-anchor="middle" x="2182.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="2222.5,-1416 2222.5,-1462 "/>
<text text-anchor="middle" x="2233" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2243.5,-1416 2243.5,-1462 "/>
<text text-anchor="middle" x="2345" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="2243.5,-1439 2446.5,-1439 "/>
<text text-anchor="middle" x="2345" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="2446.5,-1416 2446.5,-1462 "/>
<text text-anchor="middle" x="2457" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge7" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2467.5183,-1426.5991C2671.3169,-1401.614 3014.8209,-1326.376 3187,-1100 3239.9826,-1030.3401 3206,-991.5195 3206,-904 3206,-904 3206,-904 3206,-409 3206,-279.8444 2335.763,-190.6624 1919.211,-155.3721"/>
<polygon fill="#000000" stroke="#000000" points="1919.4107,-151.8766 1909.1517,-154.5229 1918.8217,-158.8518 1919.4107,-151.8766"/>
<text text-anchor="middle" x="3248.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- sample -->
<g id="node9" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1075,-823.5C1075,-823.5 1389,-823.5 1389,-823.5 1395,-823.5 1401,-829.5 1401,-835.5 1401,-835.5 1401,-972.5 1401,-972.5 1401,-978.5 1395,-984.5 1389,-984.5 1389,-984.5 1075,-984.5 1075,-984.5 1069,-984.5 1063,-978.5 1063,-972.5 1063,-972.5 1063,-835.5 1063,-835.5 1063,-829.5 1069,-823.5 1075,-823.5"/>
<text text-anchor="middle" x="1097" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1131,-823.5 1131,-984.5 "/>
<text text-anchor="middle" x="1141.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1152,-823.5 1152,-984.5 "/>
<text text-anchor="middle" x="1266" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="1152,-961.5 1380,-961.5 "/>
<text text-anchor="middle" x="1266" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1152,-938.5 1380,-938.5 "/>
<text text-anchor="middle" x="1266" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1152,-915.5 1380,-915.5 "/>
<text text-anchor="middle" x="1266" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1152,-892.5 1380,-892.5 "/>
<text text-anchor="middle" x="1266" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1152,-869.5 1380,-869.5 "/>
<text text-anchor="middle" x="1266" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1152,-846.5 1380,-846.5 "/>
<text text-anchor="middle" x="1266" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="1380,-823.5 1380,-984.5 "/>
<text text-anchor="middle" x="1390.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2298.9028,-1415.752C2282.7821,-1359.388 2233.2965,-1215.3671 2134,-1151 2027.0012,-1081.64 1976.124,-1127.9522 1849,-1118 1800.3302,-1114.1898 1454.2262,-1120.6716 1410,-1100 1360.5178,-1076.8717 1318.621,-1032.9851 1287.929,-992.5941"/>
<polygon fill="#000000" stroke="#000000" points="1290.7267,-990.4911 1281.941,-984.5697 1285.1165,-994.6775 1290.7267,-990.4911"/>
<text text-anchor="middle" x="2139.5" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- participant -->
<g id="node13" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M1912,-541.5C1912,-541.5 2216,-541.5 2216,-541.5 2222,-541.5 2228,-547.5 2228,-553.5 2228,-553.5 2228,-644.5 2228,-644.5 2228,-650.5 2222,-656.5 2216,-656.5 2216,-656.5 1912,-656.5 1912,-656.5 1906,-656.5 1900,-650.5 1900,-644.5 1900,-644.5 1900,-553.5 1900,-553.5 1900,-547.5 1906,-541.5 1912,-541.5"/>
<text text-anchor="middle" x="1948" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1996,-541.5 1996,-656.5 "/>
<text text-anchor="middle" x="2006.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2017,-541.5 2017,-656.5 "/>
<text text-anchor="middle" x="2112" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="2017,-633.5 2207,-633.5 "/>
<text text-anchor="middle" x="2112" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="2017,-610.5 2207,-610.5 "/>
<text text-anchor="middle" x="2112" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="2017,-587.5 2207,-587.5 "/>
<text text-anchor="middle" x="2112" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="2017,-564.5 2207,-564.5 "/>
<text text-anchor="middle" x="2112" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="2207,-541.5 2207,-656.5 "/>
<text text-anchor="middle" x="2217.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2304.1962,-1415.7786C2299.9212,-1294.5448 2279.3218,-738.6568 2260,-708 2248.9386,-690.4495 2233.9913,-675.4829 2217.2548,-662.7849"/>
<polygon fill="#000000" stroke="#000000" points="2219.055,-659.7671 2208.9041,-656.7322 2214.9469,-665.4348 2219.055,-659.7671"/>
<text text-anchor="middle" x="2333.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- family_relationship -->
<g id="node7" class="node">
<title>family_relationship</title>
<path fill="none" stroke="#000000" d="M2402.5,-881C2402.5,-881 2771.5,-881 2771.5,-881 2777.5,-881 2783.5,-887 2783.5,-893 2783.5,-893 2783.5,-915 2783.5,-915 2783.5,-921 2777.5,-927 2771.5,-927 2771.5,-927 2402.5,-927 2402.5,-927 2396.5,-927 2390.5,-921 2390.5,-915 2390.5,-915 2390.5,-893 2390.5,-893 2390.5,-887 2396.5,-881 2402.5,-881"/>
<text text-anchor="middle" x="2467.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
<polyline fill="none" stroke="#000000" points="2544.5,-881 2544.5,-927 "/>
<text text-anchor="middle" x="2555" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2565.5,-881 2565.5,-927 "/>
<text text-anchor="middle" x="2664" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">related_to_participant_id</text>
<polyline fill="none" stroke="#000000" points="2565.5,-904 2762.5,-904 "/>
<text text-anchor="middle" x="2664" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">relationship</text>
<polyline fill="none" stroke="#000000" points="2762.5,-881 2762.5,-927 "/>
<text text-anchor="middle" x="2773" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2566.8722,-880.7885C2531.5208,-841.1339 2454.5451,-759.6326 2376,-708 2334.2846,-680.5779 2284.8856,-659.2049 2237.8444,-642.9369"/>
<polygon fill="#000000" stroke="#000000" points="2238.7531,-639.5492 2228.1587,-639.647 2236.5017,-646.1773 2238.7531,-639.5492"/>
<text text-anchor="middle" x="2424.5" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- therapeutic_procedure -->
<g id="node8" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M1431,-846.5C1431,-846.5 1823,-846.5 1823,-846.5 1829,-846.5 1835,-852.5 1835,-858.5 1835,-858.5 1835,-949.5 1835,-949.5 1835,-955.5 1829,-961.5 1823,-961.5 1823,-961.5 1431,-961.5 1431,-961.5 1425,-961.5 1419,-955.5 1419,-949.5 1419,-949.5 1419,-858.5 1419,-858.5 1419,-852.5 1425,-846.5 1431,-846.5"/>
<text text-anchor="middle" x="1509.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="1600,-846.5 1600,-961.5 "/>
<text text-anchor="middle" x="1610.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1621,-846.5 1621,-961.5 "/>
<text text-anchor="middle" x="1717.5" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment_start</text>
<polyline fill="none" stroke="#000000" points="1621,-938.5 1814,-938.5 "/>
<text text-anchor="middle" x="1717.5" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="1621,-915.5 1814,-915.5 "/>
<text text-anchor="middle" x="1717.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1621,-892.5 1814,-892.5 "/>
<text text-anchor="middle" x="1717.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="1621,-869.5 1814,-869.5 "/>
<text text-anchor="middle" x="1717.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1814,-846.5 1814,-961.5 "/>
<text text-anchor="middle" x="1824.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1676.5185,-846.1604C1722.4356,-795.4575 1794.8256,-722.6096 1870,-675 1877.5743,-670.2031 1885.5003,-665.6226 1893.6391,-661.2616"/>
<polygon fill="#000000" stroke="#000000" points="1895.2993,-664.3433 1902.5475,-656.6158 1892.0624,-658.1366 1895.2993,-664.3433"/>
<text text-anchor="middle" x="1963" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge19" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1300.2741,-823.0852C1332.3127,-786.6486 1371.7899,-743.8591 1410,-708 1523.2214,-601.7449 1611.9227,-628.048 1683,-490 1714.7317,-428.37 1722.0743,-352.3485 1720.4108,-286.7875"/>
<polygon fill="#000000" stroke="#000000" points="1723.9086,-286.6579 1720.0855,-276.7769 1716.9123,-286.8853 1723.9086,-286.6579"/>
<text text-anchor="middle" x="1709.5" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1282.4855,-823.2984C1313.6478,-781.0662 1357.655,-733.0543 1410,-708 1470.8418,-678.8788 1646.3724,-700.5135 1713,-690 1722.7199,-688.4663 1806.6943,-666.7178 1890.0615,-644.8693"/>
<polygon fill="#000000" stroke="#000000" points="1891.1712,-648.1968 1899.9565,-642.2749 1889.3958,-641.4256 1891.1712,-648.1968"/>
<text text-anchor="middle" x="1808.5" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- imaging_file -->
<g id="node10" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M12,-1278C12,-1278 346,-1278 346,-1278 352,-1278 358,-1284 358,-1290 358,-1290 358,-1588 358,-1588 358,-1594 352,-1600 346,-1600 346,-1600 12,-1600 12,-1600 6,-1600 0,-1594 0,-1588 0,-1588 0,-1290 0,-1290 0,-1284 6,-1278 12,-1278"/>
<text text-anchor="middle" x="52" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="104,-1278 104,-1600 "/>
<text text-anchor="middle" x="114.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="125,-1278 125,-1600 "/>
<text text-anchor="middle" x="231" y="-1584.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="125,-1577 337,-1577 "/>
<text text-anchor="middle" x="231" y="-1561.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="125,-1554 337,-1554 "/>
<text text-anchor="middle" x="231" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="125,-1531 337,-1531 "/>
<text text-anchor="middle" x="231" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="125,-1508 337,-1508 "/>
<text text-anchor="middle" x="231" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="125,-1485 337,-1485 "/>
<text text-anchor="middle" x="231" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="125,-1462 337,-1462 "/>
<text text-anchor="middle" x="231" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="125,-1439 337,-1439 "/>
<text text-anchor="middle" x="231" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="125,-1416 337,-1416 "/>
<text text-anchor="middle" x="231" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="125,-1393 337,-1393 "/>
<text text-anchor="middle" x="231" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="125,-1370 337,-1370 "/>
<text text-anchor="middle" x="231" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="125,-1347 337,-1347 "/>
<text text-anchor="middle" x="231" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="125,-1324 337,-1324 "/>
<text text-anchor="middle" x="231" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="125,-1301 337,-1301 "/>
<text text-anchor="middle" x="231" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="337,-1278 337,-1600 "/>
<text text-anchor="middle" x="347.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M255.9993,-1277.8634C285.0727,-1231.225 322.1841,-1184.0418 367,-1151 571.6924,-1000.0849 865.9603,-941.2223 1053.0312,-918.3666"/>
<polygon fill="#000000" stroke="#000000" points="1053.4571,-921.8407 1062.9687,-917.174 1052.6229,-914.8906 1053.4571,-921.8407"/>
<text text-anchor="middle" x="461.5" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- sample_diagnosis -->
<g id="node11" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M388.5,-1278C388.5,-1278 821.5,-1278 821.5,-1278 827.5,-1278 833.5,-1284 833.5,-1290 833.5,-1290 833.5,-1588 833.5,-1588 833.5,-1594 827.5,-1600 821.5,-1600 821.5,-1600 388.5,-1600 388.5,-1600 382.5,-1600 376.5,-1594 376.5,-1588 376.5,-1588 376.5,-1290 376.5,-1290 376.5,-1284 382.5,-1278 388.5,-1278"/>
<text text-anchor="middle" x="448" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="519.5,-1278 519.5,-1600 "/>
<text text-anchor="middle" x="530" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="540.5,-1278 540.5,-1600 "/>
<text text-anchor="middle" x="676.5" y="-1584.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="540.5,-1577 812.5,-1577 "/>
<text text-anchor="middle" x="676.5" y="-1561.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="540.5,-1554 812.5,-1554 "/>
<text text-anchor="middle" x="676.5" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="540.5,-1531 812.5,-1531 "/>
<text text-anchor="middle" x="676.5" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="540.5,-1508 812.5,-1508 "/>
<text text-anchor="middle" x="676.5" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="540.5,-1485 812.5,-1485 "/>
<text text-anchor="middle" x="676.5" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="540.5,-1462 812.5,-1462 "/>
<text text-anchor="middle" x="676.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="540.5,-1439 812.5,-1439 "/>
<text text-anchor="middle" x="676.5" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="540.5,-1416 812.5,-1416 "/>
<text text-anchor="middle" x="676.5" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="540.5,-1393 812.5,-1393 "/>
<text text-anchor="middle" x="676.5" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="540.5,-1370 812.5,-1370 "/>
<text text-anchor="middle" x="676.5" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="540.5,-1347 812.5,-1347 "/>
<text text-anchor="middle" x="676.5" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="540.5,-1324 812.5,-1324 "/>
<text text-anchor="middle" x="676.5" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="540.5,-1301 812.5,-1301 "/>
<text text-anchor="middle" x="676.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="812.5,-1278 812.5,-1600 "/>
<text text-anchor="middle" x="823" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M722.6674,-1277.6818C758.4057,-1234.0173 799.5308,-1188.5049 842,-1151 911.5609,-1089.5702 997.9849,-1033.1781 1071.7856,-989.8343"/>
<polygon fill="#000000" stroke="#000000" points="1073.8524,-992.6804 1080.7211,-984.6137 1070.3211,-986.6364 1073.8524,-992.6804"/>
<text text-anchor="middle" x="955" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
<!-- pdx -->
<g id="node12" class="node">
<title>pdx</title>
<path fill="none" stroke="#000000" d="M863.5,-1335.5C863.5,-1335.5 1192.5,-1335.5 1192.5,-1335.5 1198.5,-1335.5 1204.5,-1341.5 1204.5,-1347.5 1204.5,-1347.5 1204.5,-1530.5 1204.5,-1530.5 1204.5,-1536.5 1198.5,-1542.5 1192.5,-1542.5 1192.5,-1542.5 863.5,-1542.5 863.5,-1542.5 857.5,-1542.5 851.5,-1536.5 851.5,-1530.5 851.5,-1530.5 851.5,-1347.5 851.5,-1347.5 851.5,-1341.5 857.5,-1335.5 863.5,-1335.5"/>
<text text-anchor="middle" x="873" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
<polyline fill="none" stroke="#000000" points="894.5,-1335.5 894.5,-1542.5 "/>
<text text-anchor="middle" x="905" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="915.5,-1335.5 915.5,-1542.5 "/>
<text text-anchor="middle" x="1049.5" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_site</text>
<polyline fill="none" stroke="#000000" points="915.5,-1519.5 1183.5,-1519.5 "/>
<text text-anchor="middle" x="1049.5" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_type</text>
<polyline fill="none" stroke="#000000" points="915.5,-1496.5 1183.5,-1496.5 "/>
<text text-anchor="middle" x="1049.5" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_id</text>
<polyline fill="none" stroke="#000000" points="915.5,-1473.5 1183.5,-1473.5 "/>
<text text-anchor="middle" x="1049.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">mouse_strain</text>
<polyline fill="none" stroke="#000000" points="915.5,-1450.5 1183.5,-1450.5 "/>
<text text-anchor="middle" x="1049.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">strain_immune_system_humanized</text>
<polyline fill="none" stroke="#000000" points="915.5,-1427.5 1183.5,-1427.5 "/>
<text text-anchor="middle" x="1049.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_characterization_method</text>
<polyline fill="none" stroke="#000000" points="915.5,-1404.5 1183.5,-1404.5 "/>
<text text-anchor="middle" x="1049.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_not_mus_or_ebv_origin</text>
<polyline fill="none" stroke="#000000" points="915.5,-1381.5 1183.5,-1381.5 "/>
<text text-anchor="middle" x="1049.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_preparation</text>
<polyline fill="none" stroke="#000000" points="915.5,-1358.5 1183.5,-1358.5 "/>
<text text-anchor="middle" x="1049.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_humanization</text>
<polyline fill="none" stroke="#000000" points="1183.5,-1335.5 1183.5,-1542.5 "/>
<text text-anchor="middle" x="1194" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1067.5751,-1335.2123C1105.3261,-1236.2085 1161.6137,-1088.5916 1197.5595,-994.322"/>
<polygon fill="#000000" stroke="#000000" points="1200.8968,-995.393 1201.1894,-984.8022 1194.3562,-992.899 1200.8968,-995.393"/>
<text text-anchor="middle" x="1173" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge22" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2080.0627,-541.487C2092.873,-482.8225 2102.5546,-391.6193 2061,-328 2026.9561,-275.8796 1973.6638,-237.1657 1918.4595,-208.812"/>
<polygon fill="#000000" stroke="#000000" points="1919.732,-205.5344 1909.225,-204.1724 1916.5893,-211.7893 1919.732,-205.5344"/>
<text text-anchor="middle" x="2141.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_arm -->
<g id="node16" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M1742.5,-374.5C1742.5,-374.5 2039.5,-374.5 2039.5,-374.5 2045.5,-374.5 2051.5,-380.5 2051.5,-386.5 2051.5,-386.5 2051.5,-431.5 2051.5,-431.5 2051.5,-437.5 2045.5,-443.5 2039.5,-443.5 2039.5,-443.5 1742.5,-443.5 1742.5,-443.5 1736.5,-443.5 1730.5,-437.5 1730.5,-431.5 1730.5,-431.5 1730.5,-386.5 1730.5,-386.5 1730.5,-380.5 1736.5,-374.5 1742.5,-374.5"/>
<text text-anchor="middle" x="1776.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="1822.5,-374.5 1822.5,-443.5 "/>
<text text-anchor="middle" x="1833" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1843.5,-374.5 1843.5,-443.5 "/>
<text text-anchor="middle" x="1937" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="1843.5,-420.5 2030.5,-420.5 "/>
<text text-anchor="middle" x="1937" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="1843.5,-397.5 2030.5,-397.5 "/>
<text text-anchor="middle" x="1937" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="2030.5,-374.5 2030.5,-443.5 "/>
<text text-anchor="middle" x="2041" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge21" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1991.4178,-541.299C1984.9891,-535.3285 1978.7481,-529.1792 1973,-523 1952.7702,-501.253 1933.224,-474.3865 1918.2923,-452.1983"/>
<polygon fill="#000000" stroke="#000000" points="1921.0494,-450.0235 1912.5992,-443.6325 1915.2196,-453.8982 1921.0494,-450.0235"/>
<text text-anchor="middle" x="2023.5" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- diagnosis -->
<g id="node14" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1865,-708.5C1865,-708.5 2239,-708.5 2239,-708.5 2245,-708.5 2251,-714.5 2251,-720.5 2251,-720.5 2251,-1087.5 2251,-1087.5 2251,-1093.5 2245,-1099.5 2239,-1099.5 2239,-1099.5 1865,-1099.5 1865,-1099.5 1859,-1099.5 1853,-1093.5 1853,-1087.5 1853,-1087.5 1853,-720.5 1853,-720.5 1853,-714.5 1859,-708.5 1865,-708.5"/>
<text text-anchor="middle" x="1895" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1937,-708.5 1937,-1099.5 "/>
<text text-anchor="middle" x="1947.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1958,-708.5 1958,-1099.5 "/>
<text text-anchor="middle" x="2094" y="-1084.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1958,-1076.5 2230,-1076.5 "/>
<text text-anchor="middle" x="2094" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1958,-1053.5 2230,-1053.5 "/>
<text text-anchor="middle" x="2094" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1958,-1030.5 2230,-1030.5 "/>
<text text-anchor="middle" x="2094" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1958,-1007.5 2230,-1007.5 "/>
<text text-anchor="middle" x="2094" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1958,-984.5 2230,-984.5 "/>
<text text-anchor="middle" x="2094" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="1958,-961.5 2230,-961.5 "/>
<text text-anchor="middle" x="2094" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="1958,-938.5 2230,-938.5 "/>
<text text-anchor="middle" x="2094" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="1958,-915.5 2230,-915.5 "/>
<text text-anchor="middle" x="2094" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1958,-892.5 2230,-892.5 "/>
<text text-anchor="middle" x="2094" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="1958,-869.5 2230,-869.5 "/>
<text text-anchor="middle" x="2094" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1958,-846.5 2230,-846.5 "/>
<text text-anchor="middle" x="2094" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="1958,-823.5 2230,-823.5 "/>
<text text-anchor="middle" x="2094" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1958,-800.5 2230,-800.5 "/>
<text text-anchor="middle" x="2094" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1958,-777.5 2230,-777.5 "/>
<text text-anchor="middle" x="2094" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1958,-754.5 2230,-754.5 "/>
<text text-anchor="middle" x="2094" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1958,-731.5 2230,-731.5 "/>
<text text-anchor="middle" x="2094" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="2230,-708.5 2230,-1099.5 "/>
<text text-anchor="middle" x="2240.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2059.7016,-708.2505C2060.2779,-693.6044 2060.8313,-679.5385 2061.3381,-666.6572"/>
<polygon fill="#000000" stroke="#000000" points="2064.8381,-666.7221 2061.7341,-656.5922 2057.8436,-666.4468 2064.8381,-666.7221"/>
<text text-anchor="middle" x="2104.5" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- clinical_measure_file -->
<g id="node15" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M2814,-777.5C2814,-777.5 3166,-777.5 3166,-777.5 3172,-777.5 3178,-783.5 3178,-789.5 3178,-789.5 3178,-1018.5 3178,-1018.5 3178,-1024.5 3172,-1030.5 3166,-1030.5 3166,-1030.5 2814,-1030.5 2814,-1030.5 2808,-1030.5 2802,-1024.5 2802,-1018.5 2802,-1018.5 2802,-789.5 2802,-789.5 2802,-783.5 2808,-777.5 2814,-777.5"/>
<text text-anchor="middle" x="2885.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="2969,-777.5 2969,-1030.5 "/>
<text text-anchor="middle" x="2979.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2990,-777.5 2990,-1030.5 "/>
<text text-anchor="middle" x="3073.5" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2990,-1007.5 3157,-1007.5 "/>
<text text-anchor="middle" x="3073.5" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2990,-984.5 3157,-984.5 "/>
<text text-anchor="middle" x="3073.5" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2990,-961.5 3157,-961.5 "/>
<text text-anchor="middle" x="3073.5" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2990,-938.5 3157,-938.5 "/>
<text text-anchor="middle" x="3073.5" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2990,-915.5 3157,-915.5 "/>
<text text-anchor="middle" x="3073.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2990,-892.5 3157,-892.5 "/>
<text text-anchor="middle" x="3073.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2990,-869.5 3157,-869.5 "/>
<text text-anchor="middle" x="3073.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2990,-846.5 3157,-846.5 "/>
<text text-anchor="middle" x="3073.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2990,-823.5 3157,-823.5 "/>
<text text-anchor="middle" x="3073.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2990,-800.5 3157,-800.5 "/>
<text text-anchor="middle" x="3073.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="3157,-777.5 3157,-1030.5 "/>
<text text-anchor="middle" x="3167.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge5" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2999.4509,-777.3831C2996.4024,-741.5274 2987.1939,-704.319 2966,-675 2719.1114,-333.4619 2210.4602,-207.7875 1919.2912,-162.7128"/>
<polygon fill="#000000" stroke="#000000" points="1919.4401,-159.1949 1909.0259,-161.1431 1918.3819,-166.1145 1919.4401,-159.1949"/>
<text text-anchor="middle" x="2908" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2886.806,-777.2709C2859.0548,-750.4886 2827.1639,-725.167 2793,-708 2768.3549,-695.6161 2446.1937,-650.4658 2238.4746,-622.3061"/>
<polygon fill="#000000" stroke="#000000" points="2238.7423,-618.8105 2228.363,-620.9365 2237.8026,-625.7471 2238.7423,-618.8105"/>
<text text-anchor="middle" x="2832.5" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge6" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1866.871,-374.4662C1850.587,-351.1602 1827.8715,-318.6494 1804.4986,-285.1978"/>
<polygon fill="#000000" stroke="#000000" points="1807.1423,-282.8705 1798.5457,-276.6779 1801.4042,-286.8798 1807.1423,-282.8705"/>
<text text-anchor="middle" x="1866.5" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- sequencing_file -->
<g id="node17" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M1234.5,-1151.5C1234.5,-1151.5 1703.5,-1151.5 1703.5,-1151.5 1709.5,-1151.5 1715.5,-1157.5 1715.5,-1163.5 1715.5,-1163.5 1715.5,-1714.5 1715.5,-1714.5 1715.5,-1720.5 1709.5,-1726.5 1703.5,-1726.5 1703.5,-1726.5 1234.5,-1726.5 1234.5,-1726.5 1228.5,-1726.5 1222.5,-1720.5 1222.5,-1714.5 1222.5,-1714.5 1222.5,-1163.5 1222.5,-1163.5 1222.5,-1157.5 1228.5,-1151.5 1234.5,-1151.5"/>
<text text-anchor="middle" x="1286.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="1350.5,-1151.5 1350.5,-1726.5 "/>
<text text-anchor="middle" x="1361" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1371.5,-1151.5 1371.5,-1726.5 "/>
<text text-anchor="middle" x="1533" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="1371.5,-1703.5 1694.5,-1703.5 "/>
<text text-anchor="middle" x="1533" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1371.5,-1680.5 1694.5,-1680.5 "/>
<text text-anchor="middle" x="1533" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1371.5,-1657.5 1694.5,-1657.5 "/>
<text text-anchor="middle" x="1533" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="1371.5,-1634.5 1694.5,-1634.5 "/>
<text text-anchor="middle" x="1533" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="1371.5,-1611.5 1694.5,-1611.5 "/>
<text text-anchor="middle" x="1533" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1371.5,-1588.5 1694.5,-1588.5 "/>
<text text-anchor="middle" x="1533" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="1371.5,-1565.5 1694.5,-1565.5 "/>
<text text-anchor="middle" x="1533" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1371.5,-1542.5 1694.5,-1542.5 "/>
<text text-anchor="middle" x="1533" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1371.5,-1519.5 1694.5,-1519.5 "/>
<text text-anchor="middle" x="1533" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1371.5,-1496.5 1694.5,-1496.5 "/>
<text text-anchor="middle" x="1533" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1371.5,-1473.5 1694.5,-1473.5 "/>
<text text-anchor="middle" x="1533" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1371.5,-1450.5 1694.5,-1450.5 "/>
<text text-anchor="middle" x="1533" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1371.5,-1427.5 1694.5,-1427.5 "/>
<text text-anchor="middle" x="1533" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="1371.5,-1404.5 1694.5,-1404.5 "/>
<text text-anchor="middle" x="1533" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="1371.5,-1381.5 1694.5,-1381.5 "/>
<text text-anchor="middle" x="1533" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="1371.5,-1358.5 1694.5,-1358.5 "/>
<text text-anchor="middle" x="1533" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="1371.5,-1335.5 1694.5,-1335.5 "/>
<text text-anchor="middle" x="1533" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="1371.5,-1312.5 1694.5,-1312.5 "/>
<text text-anchor="middle" x="1533" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="1371.5,-1289.5 1694.5,-1289.5 "/>
<text text-anchor="middle" x="1533" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1371.5,-1266.5 1694.5,-1266.5 "/>
<text text-anchor="middle" x="1533" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="1371.5,-1243.5 1694.5,-1243.5 "/>
<text text-anchor="middle" x="1533" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="1371.5,-1220.5 1694.5,-1220.5 "/>
<text text-anchor="middle" x="1533" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="1371.5,-1197.5 1694.5,-1197.5 "/>
<text text-anchor="middle" x="1533" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="1371.5,-1174.5 1694.5,-1174.5 "/>
<text text-anchor="middle" x="1533" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="1694.5,-1151.5 1694.5,-1726.5 "/>
<text text-anchor="middle" x="1705" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1341.4814,-1151.1415C1316.1653,-1093.9934 1291.4014,-1038.0917 1271.8473,-993.9507"/>
<polygon fill="#000000" stroke="#000000" points="1275.0059,-992.4393 1267.7555,-984.7138 1268.6057,-995.2745 1275.0059,-992.4393"/>
<text text-anchor="middle" x="1396.5" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- methylation_array_file -->
<g id="node18" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M1745.5,-1324C1745.5,-1324 2112.5,-1324 2112.5,-1324 2118.5,-1324 2124.5,-1330 2124.5,-1336 2124.5,-1336 2124.5,-1542 2124.5,-1542 2124.5,-1548 2118.5,-1554 2112.5,-1554 2112.5,-1554 1745.5,-1554 1745.5,-1554 1739.5,-1554 1733.5,-1548 1733.5,-1542 1733.5,-1542 1733.5,-1336 1733.5,-1336 1733.5,-1330 1739.5,-1324 1745.5,-1324"/>
<text text-anchor="middle" x="1822.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="1911.5,-1324 1911.5,-1554 "/>
<text text-anchor="middle" x="1922" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1932.5,-1324 1932.5,-1554 "/>
<text text-anchor="middle" x="2018" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1932.5,-1531 2103.5,-1531 "/>
<text text-anchor="middle" x="2018" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1932.5,-1508 2103.5,-1508 "/>
<text text-anchor="middle" x="2018" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1932.5,-1485 2103.5,-1485 "/>
<text text-anchor="middle" x="2018" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1932.5,-1462 2103.5,-1462 "/>
<text text-anchor="middle" x="2018" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1932.5,-1439 2103.5,-1439 "/>
<text text-anchor="middle" x="2018" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1932.5,-1416 2103.5,-1416 "/>
<text text-anchor="middle" x="2018" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1932.5,-1393 2103.5,-1393 "/>
<text text-anchor="middle" x="2018" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1932.5,-1370 2103.5,-1370 "/>
<text text-anchor="middle" x="2018" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="1932.5,-1347 2103.5,-1347 "/>
<text text-anchor="middle" x="2018" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="2103.5,-1324 2103.5,-1554 "/>
<text text-anchor="middle" x="2114" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1875.6999,-1323.9501C1841.3556,-1262.8112 1790.7732,-1192.0083 1725,-1151 1664.8261,-1113.4828 1472.3324,-1133.81 1410,-1100 1363.2251,-1074.6286 1322.3544,-1032.1229 1291.6133,-993.1677"/>
<polygon fill="#000000" stroke="#000000" points="1294.1053,-990.67 1285.2088,-984.9164 1288.5755,-994.9621 1294.1053,-990.67"/>
<text text-anchor="middle" x="1753.5" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
</g>
</svg>
</div>
