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
<svg width="3280pt" height="1712pt"
 viewBox="0.00 0.00 3279.50 1712.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1708)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1708 3275.5,-1708 3275.5,4 -4,4"/>
<!-- pdx -->
<g id="node1" class="node">
<title>pdx</title>
<path fill="none" stroke="#000000" d="M523,-1312.5C523,-1312.5 852,-1312.5 852,-1312.5 858,-1312.5 864,-1318.5 864,-1324.5 864,-1324.5 864,-1507.5 864,-1507.5 864,-1513.5 858,-1519.5 852,-1519.5 852,-1519.5 523,-1519.5 523,-1519.5 517,-1519.5 511,-1513.5 511,-1507.5 511,-1507.5 511,-1324.5 511,-1324.5 511,-1318.5 517,-1312.5 523,-1312.5"/>
<text text-anchor="middle" x="532.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
<polyline fill="none" stroke="#000000" points="554,-1312.5 554,-1519.5 "/>
<text text-anchor="middle" x="564.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="575,-1312.5 575,-1519.5 "/>
<text text-anchor="middle" x="709" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_site</text>
<polyline fill="none" stroke="#000000" points="575,-1496.5 843,-1496.5 "/>
<text text-anchor="middle" x="709" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_type</text>
<polyline fill="none" stroke="#000000" points="575,-1473.5 843,-1473.5 "/>
<text text-anchor="middle" x="709" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_id</text>
<polyline fill="none" stroke="#000000" points="575,-1450.5 843,-1450.5 "/>
<text text-anchor="middle" x="709" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">mouse_strain</text>
<polyline fill="none" stroke="#000000" points="575,-1427.5 843,-1427.5 "/>
<text text-anchor="middle" x="709" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">strain_immune_system_humanized</text>
<polyline fill="none" stroke="#000000" points="575,-1404.5 843,-1404.5 "/>
<text text-anchor="middle" x="709" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_characterization_method</text>
<polyline fill="none" stroke="#000000" points="575,-1381.5 843,-1381.5 "/>
<text text-anchor="middle" x="709" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_not_mus_or_ebv_origin</text>
<polyline fill="none" stroke="#000000" points="575,-1358.5 843,-1358.5 "/>
<text text-anchor="middle" x="709" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_preparation</text>
<polyline fill="none" stroke="#000000" points="575,-1335.5 843,-1335.5 "/>
<text text-anchor="middle" x="709" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_humanization</text>
<polyline fill="none" stroke="#000000" points="843,-1312.5 843,-1519.5 "/>
<text text-anchor="middle" x="853.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node8" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1297.5,-812C1297.5,-812 1611.5,-812 1611.5,-812 1617.5,-812 1623.5,-818 1623.5,-824 1623.5,-824 1623.5,-961 1623.5,-961 1623.5,-967 1617.5,-973 1611.5,-973 1611.5,-973 1297.5,-973 1297.5,-973 1291.5,-973 1285.5,-967 1285.5,-961 1285.5,-961 1285.5,-824 1285.5,-824 1285.5,-818 1291.5,-812 1297.5,-812"/>
<text text-anchor="middle" x="1319.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1353.5,-812 1353.5,-973 "/>
<text text-anchor="middle" x="1364" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1374.5,-812 1374.5,-973 "/>
<text text-anchor="middle" x="1488.5" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="1374.5,-950 1602.5,-950 "/>
<text text-anchor="middle" x="1488.5" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1374.5,-927 1602.5,-927 "/>
<text text-anchor="middle" x="1488.5" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1374.5,-904 1602.5,-904 "/>
<text text-anchor="middle" x="1488.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1374.5,-881 1602.5,-881 "/>
<text text-anchor="middle" x="1488.5" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1374.5,-858 1602.5,-858 "/>
<text text-anchor="middle" x="1488.5" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1374.5,-835 1602.5,-835 "/>
<text text-anchor="middle" x="1488.5" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="1602.5,-812 1602.5,-973 "/>
<text text-anchor="middle" x="1613" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M734.4446,-1312.2668C766.3083,-1251.6724 813.5396,-1177.6113 873.5,-1128 990.3554,-1031.3138 1152.1467,-970.1078 1275.328,-934.4042"/>
<polygon fill="#000000" stroke="#000000" points="1276.6012,-937.6802 1285.2491,-931.5594 1274.6718,-930.9514 1276.6012,-937.6802"/>
<text text-anchor="middle" x="937.5" y="-1098.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- publication -->
<g id="node2" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M1243.5,-391C1243.5,-391 1453.5,-391 1453.5,-391 1459.5,-391 1465.5,-397 1465.5,-403 1465.5,-403 1465.5,-415 1465.5,-415 1465.5,-421 1459.5,-427 1453.5,-427 1453.5,-427 1243.5,-427 1243.5,-427 1237.5,-427 1231.5,-421 1231.5,-415 1231.5,-415 1231.5,-403 1231.5,-403 1231.5,-397 1237.5,-391 1243.5,-391"/>
<text text-anchor="middle" x="1280" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="1328.5,-391 1328.5,-427 "/>
<text text-anchor="middle" x="1339" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1349.5,-391 1349.5,-427 "/>
<text text-anchor="middle" x="1397" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="1444.5,-391 1444.5,-427 "/>
<text text-anchor="middle" x="1455" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node5" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M2052.5,-.5C2052.5,-.5 2442.5,-.5 2442.5,-.5 2448.5,-.5 2454.5,-6.5 2454.5,-12.5 2454.5,-12.5 2454.5,-264.5 2454.5,-264.5 2454.5,-270.5 2448.5,-276.5 2442.5,-276.5 2442.5,-276.5 2052.5,-276.5 2052.5,-276.5 2046.5,-276.5 2040.5,-270.5 2040.5,-264.5 2040.5,-264.5 2040.5,-12.5 2040.5,-12.5 2040.5,-6.5 2046.5,-.5 2052.5,-.5"/>
<text text-anchor="middle" x="2068.5" y="-134.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="2096.5,-.5 2096.5,-276.5 "/>
<text text-anchor="middle" x="2107" y="-134.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2117.5,-.5 2117.5,-276.5 "/>
<text text-anchor="middle" x="2275.5" y="-261.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="2117.5,-253.5 2433.5,-253.5 "/>
<text text-anchor="middle" x="2275.5" y="-238.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="2117.5,-230.5 2433.5,-230.5 "/>
<text text-anchor="middle" x="2275.5" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_shorthand</text>
<polyline fill="none" stroke="#000000" points="2117.5,-207.5 2433.5,-207.5 "/>
<text text-anchor="middle" x="2275.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="2117.5,-184.5 2433.5,-184.5 "/>
<text text-anchor="middle" x="2275.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="2117.5,-161.5 2433.5,-161.5 "/>
<text text-anchor="middle" x="2275.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="2117.5,-138.5 2433.5,-138.5 "/>
<text text-anchor="middle" x="2275.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="2117.5,-115.5 2433.5,-115.5 "/>
<text text-anchor="middle" x="2275.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="2117.5,-92.5 2433.5,-92.5 "/>
<text text-anchor="middle" x="2275.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="2117.5,-69.5 2433.5,-69.5 "/>
<text text-anchor="middle" x="2275.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="2117.5,-46.5 2433.5,-46.5 "/>
<text text-anchor="middle" x="2275.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="2117.5,-23.5 2433.5,-23.5 "/>
<text text-anchor="middle" x="2275.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="2433.5,-.5 2433.5,-276.5 "/>
<text text-anchor="middle" x="2444" y="-134.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge14" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1347.5274,-390.5994C1347.2692,-365.2111 1350.8982,-319.7741 1377.5,-295 1470.075,-208.7855 1804.2251,-168.7094 2030.4129,-151.1015"/>
<polygon fill="#000000" stroke="#000000" points="2030.7258,-154.5878 2040.4278,-150.331 2030.1888,-147.6084 2030.7258,-154.5878"/>
<text text-anchor="middle" x="1428.5" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- imaging_file -->
<g id="node3" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M894.5,-1255C894.5,-1255 1228.5,-1255 1228.5,-1255 1234.5,-1255 1240.5,-1261 1240.5,-1267 1240.5,-1267 1240.5,-1565 1240.5,-1565 1240.5,-1571 1234.5,-1577 1228.5,-1577 1228.5,-1577 894.5,-1577 894.5,-1577 888.5,-1577 882.5,-1571 882.5,-1565 882.5,-1565 882.5,-1267 882.5,-1267 882.5,-1261 888.5,-1255 894.5,-1255"/>
<text text-anchor="middle" x="934.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="986.5,-1255 986.5,-1577 "/>
<text text-anchor="middle" x="997" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1007.5,-1255 1007.5,-1577 "/>
<text text-anchor="middle" x="1113.5" y="-1561.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1007.5,-1554 1219.5,-1554 "/>
<text text-anchor="middle" x="1113.5" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1007.5,-1531 1219.5,-1531 "/>
<text text-anchor="middle" x="1113.5" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1007.5,-1508 1219.5,-1508 "/>
<text text-anchor="middle" x="1113.5" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1007.5,-1485 1219.5,-1485 "/>
<text text-anchor="middle" x="1113.5" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1007.5,-1462 1219.5,-1462 "/>
<text text-anchor="middle" x="1113.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1007.5,-1439 1219.5,-1439 "/>
<text text-anchor="middle" x="1113.5" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1007.5,-1416 1219.5,-1416 "/>
<text text-anchor="middle" x="1113.5" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1007.5,-1393 1219.5,-1393 "/>
<text text-anchor="middle" x="1113.5" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1007.5,-1370 1219.5,-1370 "/>
<text text-anchor="middle" x="1113.5" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="1007.5,-1347 1219.5,-1347 "/>
<text text-anchor="middle" x="1113.5" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="1007.5,-1324 1219.5,-1324 "/>
<text text-anchor="middle" x="1113.5" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="1007.5,-1301 1219.5,-1301 "/>
<text text-anchor="middle" x="1113.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1007.5,-1278 1219.5,-1278 "/>
<text text-anchor="middle" x="1113.5" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="1219.5,-1255 1219.5,-1577 "/>
<text text-anchor="middle" x="1230" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1161.7812,-1254.945C1189.4431,-1212.8575 1220.2056,-1168.0742 1250.5,-1128 1288.6572,-1077.5246 1334.5373,-1024.0067 1373.1155,-980.7657"/>
<polygon fill="#000000" stroke="#000000" points="1375.9226,-982.8772 1379.9821,-973.0909 1370.7058,-978.2097 1375.9226,-982.8772"/>
<text text-anchor="middle" x="1325" y="-1098.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- methylation_array_file -->
<g id="node4" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M1271,-1301C1271,-1301 1638,-1301 1638,-1301 1644,-1301 1650,-1307 1650,-1313 1650,-1313 1650,-1519 1650,-1519 1650,-1525 1644,-1531 1638,-1531 1638,-1531 1271,-1531 1271,-1531 1265,-1531 1259,-1525 1259,-1519 1259,-1519 1259,-1313 1259,-1313 1259,-1307 1265,-1301 1271,-1301"/>
<text text-anchor="middle" x="1348" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="1437,-1301 1437,-1531 "/>
<text text-anchor="middle" x="1447.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1458,-1301 1458,-1531 "/>
<text text-anchor="middle" x="1543.5" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1458,-1508 1629,-1508 "/>
<text text-anchor="middle" x="1543.5" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1458,-1485 1629,-1485 "/>
<text text-anchor="middle" x="1543.5" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1458,-1462 1629,-1462 "/>
<text text-anchor="middle" x="1543.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1458,-1439 1629,-1439 "/>
<text text-anchor="middle" x="1543.5" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1458,-1416 1629,-1416 "/>
<text text-anchor="middle" x="1543.5" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1458,-1393 1629,-1393 "/>
<text text-anchor="middle" x="1543.5" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1458,-1370 1629,-1370 "/>
<text text-anchor="middle" x="1543.5" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1458,-1347 1629,-1347 "/>
<text text-anchor="middle" x="1543.5" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="1458,-1324 1629,-1324 "/>
<text text-anchor="middle" x="1543.5" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="1629,-1301 1629,-1531 "/>
<text text-anchor="middle" x="1639.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1454.5,-1300.7918C1454.5,-1205.3765 1454.5,-1071.6299 1454.5,-983.5742"/>
<polygon fill="#000000" stroke="#000000" points="1458.0001,-983.3349 1454.5,-973.3349 1451.0001,-983.3349 1458.0001,-983.3349"/>
<text text-anchor="middle" x="1546" y="-1098.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- therapeutic_procedure -->
<g id="node6" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M2191,-835C2191,-835 2548,-835 2548,-835 2554,-835 2560,-841 2560,-847 2560,-847 2560,-938 2560,-938 2560,-944 2554,-950 2548,-950 2548,-950 2191,-950 2191,-950 2185,-950 2179,-944 2179,-938 2179,-938 2179,-847 2179,-847 2179,-841 2185,-835 2191,-835"/>
<text text-anchor="middle" x="2269.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="2360,-835 2360,-950 "/>
<text text-anchor="middle" x="2370.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2381,-835 2381,-950 "/>
<text text-anchor="middle" x="2460" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="2381,-927 2539,-927 "/>
<text text-anchor="middle" x="2460" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="2381,-904 2539,-904 "/>
<text text-anchor="middle" x="2460" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="2381,-881 2539,-881 "/>
<text text-anchor="middle" x="2460" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="2381,-858 2539,-858 "/>
<text text-anchor="middle" x="2460" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="2539,-835 2539,-950 "/>
<text text-anchor="middle" x="2549.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node16" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M1923.5,-541.5C1923.5,-541.5 2227.5,-541.5 2227.5,-541.5 2233.5,-541.5 2239.5,-547.5 2239.5,-553.5 2239.5,-553.5 2239.5,-644.5 2239.5,-644.5 2239.5,-650.5 2233.5,-656.5 2227.5,-656.5 2227.5,-656.5 1923.5,-656.5 1923.5,-656.5 1917.5,-656.5 1911.5,-650.5 1911.5,-644.5 1911.5,-644.5 1911.5,-553.5 1911.5,-553.5 1911.5,-547.5 1917.5,-541.5 1923.5,-541.5"/>
<text text-anchor="middle" x="1959.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="2007.5,-541.5 2007.5,-656.5 "/>
<text text-anchor="middle" x="2018" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2028.5,-541.5 2028.5,-656.5 "/>
<text text-anchor="middle" x="2123.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="2028.5,-633.5 2218.5,-633.5 "/>
<text text-anchor="middle" x="2123.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="2028.5,-610.5 2218.5,-610.5 "/>
<text text-anchor="middle" x="2123.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="2028.5,-587.5 2218.5,-587.5 "/>
<text text-anchor="middle" x="2123.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="2028.5,-564.5 2218.5,-564.5 "/>
<text text-anchor="middle" x="2123.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="2218.5,-541.5 2218.5,-656.5 "/>
<text text-anchor="middle" x="2229" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2311.7658,-834.864C2262.4137,-785.5958 2191.4577,-714.7605 2140.1998,-663.5898"/>
<polygon fill="#000000" stroke="#000000" points="2142.652,-661.0922 2133.1021,-656.5041 2137.7064,-666.0462 2142.652,-661.0922"/>
<text text-anchor="middle" x="2254.5" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- study_arm -->
<g id="node7" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M1534,-374.5C1534,-374.5 1831,-374.5 1831,-374.5 1837,-374.5 1843,-380.5 1843,-386.5 1843,-386.5 1843,-431.5 1843,-431.5 1843,-437.5 1837,-443.5 1831,-443.5 1831,-443.5 1534,-443.5 1534,-443.5 1528,-443.5 1522,-437.5 1522,-431.5 1522,-431.5 1522,-386.5 1522,-386.5 1522,-380.5 1528,-374.5 1534,-374.5"/>
<text text-anchor="middle" x="1568" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="1614,-374.5 1614,-443.5 "/>
<text text-anchor="middle" x="1624.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1635,-374.5 1635,-443.5 "/>
<text text-anchor="middle" x="1728.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="1635,-420.5 1822,-420.5 "/>
<text text-anchor="middle" x="1728.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="1635,-397.5 1822,-397.5 "/>
<text text-anchor="middle" x="1728.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="1822,-374.5 1822,-443.5 "/>
<text text-anchor="middle" x="1832.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge7" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1754.6315,-374.4662C1824.3014,-341.111 1933.3527,-288.9015 2031.1833,-242.064"/>
<polygon fill="#000000" stroke="#000000" points="2032.8032,-245.169 2040.3114,-237.6939 2029.7804,-238.8553 2032.8032,-245.169"/>
<text text-anchor="middle" x="1962" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge12" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1457.8898,-811.8786C1464.8076,-664.6195 1482.5685,-363.9038 1513.5,-328 1580.5713,-250.147 1838.9365,-196.7617 2030.2602,-166.9627"/>
<polygon fill="#000000" stroke="#000000" points="2030.8297,-170.4163 2040.1777,-165.4297 2029.7603,-163.4984 2030.8297,-170.4163"/>
<text text-anchor="middle" x="1514" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1514.6272,-811.8333C1545.9585,-775.0975 1587.1752,-734.0894 1632.5,-708 1714.2942,-660.9185 1815.9212,-634.0509 1901.1976,-618.7801"/>
<polygon fill="#000000" stroke="#000000" points="1902.0013,-622.1927 1911.2477,-617.0202 1900.7939,-615.2976 1902.0013,-622.1927"/>
<text text-anchor="middle" x="1735" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample_diagnosis -->
<g id="node9" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M1680,-1255C1680,-1255 2113,-1255 2113,-1255 2119,-1255 2125,-1261 2125,-1267 2125,-1267 2125,-1565 2125,-1565 2125,-1571 2119,-1577 2113,-1577 2113,-1577 1680,-1577 1680,-1577 1674,-1577 1668,-1571 1668,-1565 1668,-1565 1668,-1267 1668,-1267 1668,-1261 1674,-1255 1680,-1255"/>
<text text-anchor="middle" x="1739.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1811,-1255 1811,-1577 "/>
<text text-anchor="middle" x="1821.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1832,-1255 1832,-1577 "/>
<text text-anchor="middle" x="1968" y="-1561.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1832,-1554 2104,-1554 "/>
<text text-anchor="middle" x="1968" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1832,-1531 2104,-1531 "/>
<text text-anchor="middle" x="1968" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1832,-1508 2104,-1508 "/>
<text text-anchor="middle" x="1968" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1832,-1485 2104,-1485 "/>
<text text-anchor="middle" x="1968" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="1832,-1462 2104,-1462 "/>
<text text-anchor="middle" x="1968" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="1832,-1439 2104,-1439 "/>
<text text-anchor="middle" x="1968" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="1832,-1416 2104,-1416 "/>
<text text-anchor="middle" x="1968" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1832,-1393 2104,-1393 "/>
<text text-anchor="middle" x="1968" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1832,-1370 2104,-1370 "/>
<text text-anchor="middle" x="1968" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="1832,-1347 2104,-1347 "/>
<text text-anchor="middle" x="1968" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1832,-1324 2104,-1324 "/>
<text text-anchor="middle" x="1968" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1832,-1301 2104,-1301 "/>
<text text-anchor="middle" x="1968" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1832,-1278 2104,-1278 "/>
<text text-anchor="middle" x="1968" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="2104,-1255 2104,-1577 "/>
<text text-anchor="middle" x="2114.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1772.3405,-1254.9092C1731.4646,-1203.1815 1685.2634,-1146.0736 1641.5,-1095 1608.6518,-1056.6648 1571.12,-1015.5362 1538.3432,-980.4266"/>
<polygon fill="#000000" stroke="#000000" points="1540.8116,-977.9418 1531.4246,-973.0291 1535.6991,-982.7234 1540.8116,-977.9418"/>
<text text-anchor="middle" x="1722.5" y="-1098.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
<!-- sequencing_file -->
<g id="node10" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M12,-1128.5C12,-1128.5 481,-1128.5 481,-1128.5 487,-1128.5 493,-1134.5 493,-1140.5 493,-1140.5 493,-1691.5 493,-1691.5 493,-1697.5 487,-1703.5 481,-1703.5 481,-1703.5 12,-1703.5 12,-1703.5 6,-1703.5 0,-1697.5 0,-1691.5 0,-1691.5 0,-1140.5 0,-1140.5 0,-1134.5 6,-1128.5 12,-1128.5"/>
<text text-anchor="middle" x="64" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="128,-1128.5 128,-1703.5 "/>
<text text-anchor="middle" x="138.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="149,-1128.5 149,-1703.5 "/>
<text text-anchor="middle" x="310.5" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="149,-1680.5 472,-1680.5 "/>
<text text-anchor="middle" x="310.5" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="149,-1657.5 472,-1657.5 "/>
<text text-anchor="middle" x="310.5" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="149,-1634.5 472,-1634.5 "/>
<text text-anchor="middle" x="310.5" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="149,-1611.5 472,-1611.5 "/>
<text text-anchor="middle" x="310.5" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="149,-1588.5 472,-1588.5 "/>
<text text-anchor="middle" x="310.5" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="149,-1565.5 472,-1565.5 "/>
<text text-anchor="middle" x="310.5" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="149,-1542.5 472,-1542.5 "/>
<text text-anchor="middle" x="310.5" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="149,-1519.5 472,-1519.5 "/>
<text text-anchor="middle" x="310.5" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="149,-1496.5 472,-1496.5 "/>
<text text-anchor="middle" x="310.5" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="149,-1473.5 472,-1473.5 "/>
<text text-anchor="middle" x="310.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="149,-1450.5 472,-1450.5 "/>
<text text-anchor="middle" x="310.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="149,-1427.5 472,-1427.5 "/>
<text text-anchor="middle" x="310.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="149,-1404.5 472,-1404.5 "/>
<text text-anchor="middle" x="310.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="149,-1381.5 472,-1381.5 "/>
<text text-anchor="middle" x="310.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="149,-1358.5 472,-1358.5 "/>
<text text-anchor="middle" x="310.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="149,-1335.5 472,-1335.5 "/>
<text text-anchor="middle" x="310.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="149,-1312.5 472,-1312.5 "/>
<text text-anchor="middle" x="310.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="149,-1289.5 472,-1289.5 "/>
<text text-anchor="middle" x="310.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="149,-1266.5 472,-1266.5 "/>
<text text-anchor="middle" x="310.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="149,-1243.5 472,-1243.5 "/>
<text text-anchor="middle" x="310.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="149,-1220.5 472,-1220.5 "/>
<text text-anchor="middle" x="310.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="149,-1197.5 472,-1197.5 "/>
<text text-anchor="middle" x="310.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="149,-1174.5 472,-1174.5 "/>
<text text-anchor="middle" x="310.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="149,-1151.5 472,-1151.5 "/>
<text text-anchor="middle" x="310.5" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="472,-1128.5 472,-1703.5 "/>
<text text-anchor="middle" x="482.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M493.3973,-1133.0395C496.085,-1131.3228 498.786,-1129.6423 501.5,-1128 744.187,-981.1442 1074.1417,-925.7002 1275.3039,-904.8806"/>
<polygon fill="#000000" stroke="#000000" points="1275.7863,-908.3496 1285.3807,-903.8555 1275.0778,-901.3856 1275.7863,-908.3496"/>
<text text-anchor="middle" x="614" y="-1098.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- study_admin -->
<g id="node11" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M1873.5,-328.5C1873.5,-328.5 2199.5,-328.5 2199.5,-328.5 2205.5,-328.5 2211.5,-334.5 2211.5,-340.5 2211.5,-340.5 2211.5,-477.5 2211.5,-477.5 2211.5,-483.5 2205.5,-489.5 2199.5,-489.5 2199.5,-489.5 1873.5,-489.5 1873.5,-489.5 1867.5,-489.5 1861.5,-483.5 1861.5,-477.5 1861.5,-477.5 1861.5,-340.5 1861.5,-340.5 1861.5,-334.5 1867.5,-328.5 1873.5,-328.5"/>
<text text-anchor="middle" x="1915.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="1969.5,-328.5 1969.5,-489.5 "/>
<text text-anchor="middle" x="1980" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1990.5,-328.5 1990.5,-489.5 "/>
<text text-anchor="middle" x="2090.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="1990.5,-466.5 2190.5,-466.5 "/>
<text text-anchor="middle" x="2090.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="1990.5,-443.5 2190.5,-443.5 "/>
<text text-anchor="middle" x="2090.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="1990.5,-420.5 2190.5,-420.5 "/>
<text text-anchor="middle" x="2090.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="1990.5,-397.5 2190.5,-397.5 "/>
<text text-anchor="middle" x="2090.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="1990.5,-374.5 2190.5,-374.5 "/>
<text text-anchor="middle" x="2090.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="1990.5,-351.5 2190.5,-351.5 "/>
<text text-anchor="middle" x="2090.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="2190.5,-328.5 2190.5,-489.5 "/>
<text text-anchor="middle" x="2201" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2095.2345,-328.3048C2103.632,-317.0568 2112.2273,-305.6952 2120.5,-295 2123.0891,-291.6528 2125.717,-288.2725 2128.3742,-284.8699"/>
<polygon fill="#000000" stroke="#000000" points="2131.2106,-286.9247 2134.6233,-276.8946 2125.7005,-282.6073 2131.2106,-286.9247"/>
<text text-anchor="middle" x="2177" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- synonym -->
<g id="node12" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M2155,-1393C2155,-1393 2456,-1393 2456,-1393 2462,-1393 2468,-1399 2468,-1405 2468,-1405 2468,-1427 2468,-1427 2468,-1433 2462,-1439 2456,-1439 2456,-1439 2155,-1439 2155,-1439 2149,-1439 2143,-1433 2143,-1427 2143,-1427 2143,-1405 2143,-1405 2143,-1399 2149,-1393 2155,-1393"/>
<text text-anchor="middle" x="2183" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="2223,-1393 2223,-1439 "/>
<text text-anchor="middle" x="2233.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2244,-1393 2244,-1439 "/>
<text text-anchor="middle" x="2345.5" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="2244,-1416 2447,-1416 "/>
<text text-anchor="middle" x="2345.5" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="2447,-1393 2447,-1439 "/>
<text text-anchor="middle" x="2457.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge19" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2468.1157,-1394.0304C2722.6756,-1349.4863 3186.5,-1222.9799 3186.5,-892.5 3186.5,-892.5 3186.5,-892.5 3186.5,-409 3186.5,-372.0229 3194.0008,-353.7879 3167.5,-328 3069.4207,-232.5591 2704.4943,-180.8098 2464.7809,-156.4861"/>
<polygon fill="#000000" stroke="#000000" points="2464.8303,-152.9734 2454.5301,-155.4549 2464.1296,-159.9383 2464.8303,-152.9734"/>
<text text-anchor="middle" x="3229" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2299.4595,-1392.6639C2283.4663,-1336.1016 2234.2456,-1191.6689 2134.5,-1128 2122.6855,-1120.4586 1645.1069,-1083.1254 1632.5,-1077 1587.6522,-1055.2094 1547.9688,-1017.1585 1517.5183,-981.2515"/>
<polygon fill="#000000" stroke="#000000" points="1519.859,-978.5929 1510.7695,-973.1493 1514.4804,-983.073 1519.859,-978.5929"/>
<text text-anchor="middle" x="2012" y="-1098.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2294.0756,-1392.8395C2268.7154,-1342.4137 2204.4102,-1219.8468 2134.5,-1128 2115.4619,-1102.988 2097.5423,-1106.035 2085.5,-1077 2055.5966,-1004.9007 2064.2338,-780.748 2070.9226,-666.872"/>
<polygon fill="#000000" stroke="#000000" points="2074.4174,-667.0613 2071.5218,-656.8699 2067.4299,-666.6426 2074.4174,-667.0613"/>
<text text-anchor="middle" x="2128" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study_personnel -->
<g id="node13" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M2379,-351.5C2379,-351.5 2686,-351.5 2686,-351.5 2692,-351.5 2698,-357.5 2698,-363.5 2698,-363.5 2698,-454.5 2698,-454.5 2698,-460.5 2692,-466.5 2686,-466.5 2686,-466.5 2379,-466.5 2379,-466.5 2373,-466.5 2367,-460.5 2367,-454.5 2367,-454.5 2367,-363.5 2367,-363.5 2367,-357.5 2373,-351.5 2379,-351.5"/>
<text text-anchor="middle" x="2434" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="2501,-351.5 2501,-466.5 "/>
<text text-anchor="middle" x="2511.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2522,-351.5 2522,-466.5 "/>
<text text-anchor="middle" x="2599.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="2522,-443.5 2677,-443.5 "/>
<text text-anchor="middle" x="2599.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="2522,-420.5 2677,-420.5 "/>
<text text-anchor="middle" x="2599.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="2522,-397.5 2677,-397.5 "/>
<text text-anchor="middle" x="2599.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="2522,-374.5 2677,-374.5 "/>
<text text-anchor="middle" x="2599.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="2677,-351.5 2677,-466.5 "/>
<text text-anchor="middle" x="2687.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge6" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2471.7099,-351.3027C2450.5815,-331.2493 2425.8334,-307.7603 2400.6393,-283.848"/>
<polygon fill="#000000" stroke="#000000" points="2402.831,-281.1027 2393.1684,-276.7572 2398.0121,-286.18 2402.831,-281.1027"/>
<text text-anchor="middle" x="2493" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- clinical_measure_file -->
<g id="node14" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M2590.5,-766C2590.5,-766 2942.5,-766 2942.5,-766 2948.5,-766 2954.5,-772 2954.5,-778 2954.5,-778 2954.5,-1007 2954.5,-1007 2954.5,-1013 2948.5,-1019 2942.5,-1019 2942.5,-1019 2590.5,-1019 2590.5,-1019 2584.5,-1019 2578.5,-1013 2578.5,-1007 2578.5,-1007 2578.5,-778 2578.5,-778 2578.5,-772 2584.5,-766 2590.5,-766"/>
<text text-anchor="middle" x="2662" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="2745.5,-766 2745.5,-1019 "/>
<text text-anchor="middle" x="2756" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2766.5,-766 2766.5,-1019 "/>
<text text-anchor="middle" x="2850" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2766.5,-996 2933.5,-996 "/>
<text text-anchor="middle" x="2850" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2766.5,-973 2933.5,-973 "/>
<text text-anchor="middle" x="2850" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2766.5,-950 2933.5,-950 "/>
<text text-anchor="middle" x="2850" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2766.5,-927 2933.5,-927 "/>
<text text-anchor="middle" x="2850" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2766.5,-904 2933.5,-904 "/>
<text text-anchor="middle" x="2850" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2766.5,-881 2933.5,-881 "/>
<text text-anchor="middle" x="2850" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2766.5,-858 2933.5,-858 "/>
<text text-anchor="middle" x="2850" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2766.5,-835 2933.5,-835 "/>
<text text-anchor="middle" x="2850" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2766.5,-812 2933.5,-812 "/>
<text text-anchor="middle" x="2850" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2766.5,-789 2933.5,-789 "/>
<text text-anchor="middle" x="2850" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="2933.5,-766 2933.5,-1019 "/>
<text text-anchor="middle" x="2944" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge17" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2760.0803,-765.7449C2751.1493,-610.0625 2733.1327,-362.2781 2707.5,-328 2649.3586,-250.2486 2553.5909,-204.2414 2464.4478,-177.0917"/>
<polygon fill="#000000" stroke="#000000" points="2465.315,-173.6981 2454.732,-174.1984 2463.3171,-180.407 2465.315,-173.6981"/>
<text text-anchor="middle" x="2827.5" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2653.6832,-765.7649C2628.0826,-743.3952 2599.515,-722.6211 2569.5,-708 2522.5964,-685.1521 2504.6828,-700.1142 2453.5,-690 2386.4199,-676.7444 2313.2399,-659.7305 2249.291,-644.0083"/>
<polygon fill="#000000" stroke="#000000" points="2250.0648,-640.5943 2239.5176,-641.5979 2248.3886,-647.3907 2250.0648,-640.5943"/>
<text text-anchor="middle" x="2583" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- study_funding -->
<g id="node15" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M2767,-374.5C2767,-374.5 3146,-374.5 3146,-374.5 3152,-374.5 3158,-380.5 3158,-386.5 3158,-386.5 3158,-431.5 3158,-431.5 3158,-437.5 3152,-443.5 3146,-443.5 3146,-443.5 2767,-443.5 2767,-443.5 2761,-443.5 2755,-437.5 2755,-431.5 2755,-431.5 2755,-386.5 2755,-386.5 2755,-380.5 2761,-374.5 2767,-374.5"/>
<text text-anchor="middle" x="2814.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="2874,-374.5 2874,-443.5 "/>
<text text-anchor="middle" x="2884.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2895,-374.5 2895,-443.5 "/>
<text text-anchor="middle" x="3016" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="2895,-420.5 3137,-420.5 "/>
<text text-anchor="middle" x="3016" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="2895,-397.5 3137,-397.5 "/>
<text text-anchor="middle" x="3016" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="3137,-374.5 3137,-443.5 "/>
<text text-anchor="middle" x="3147.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge16" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2897.8283,-374.3731C2855.1486,-350.099 2795.4533,-318.0077 2740.5,-295 2651.978,-257.9379 2551.4492,-224.5462 2464.3649,-198.2193"/>
<polygon fill="#000000" stroke="#000000" points="2465.2137,-194.8197 2454.6292,-195.2884 2463.1958,-201.5226 2465.2137,-194.8197"/>
<text text-anchor="middle" x="2832.5" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge9" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2176.3878,-541.221C2193.8124,-526.7232 2209.752,-509.6075 2220.5,-490 2239.4378,-455.4519 2246.1565,-366.7535 2248.1565,-287.1075"/>
<polygon fill="#000000" stroke="#000000" points="2251.6593,-287.0198 2248.3878,-276.9428 2244.6611,-286.8605 2251.6593,-287.0198"/>
<text text-anchor="middle" x="2297" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge10" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1956.5205,-541.4781C1893.9242,-511.2153 1818.8287,-474.9095 1763.0939,-447.964"/>
<polygon fill="#000000" stroke="#000000" points="1764.4976,-444.7551 1753.9711,-443.5535 1761.4507,-451.0572 1764.4976,-444.7551"/>
<text text-anchor="middle" x="1964" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- diagnosis -->
<g id="node17" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1653.5,-708.5C1653.5,-708.5 2027.5,-708.5 2027.5,-708.5 2033.5,-708.5 2039.5,-714.5 2039.5,-720.5 2039.5,-720.5 2039.5,-1064.5 2039.5,-1064.5 2039.5,-1070.5 2033.5,-1076.5 2027.5,-1076.5 2027.5,-1076.5 1653.5,-1076.5 1653.5,-1076.5 1647.5,-1076.5 1641.5,-1070.5 1641.5,-1064.5 1641.5,-1064.5 1641.5,-720.5 1641.5,-720.5 1641.5,-714.5 1647.5,-708.5 1653.5,-708.5"/>
<text text-anchor="middle" x="1683.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1725.5,-708.5 1725.5,-1076.5 "/>
<text text-anchor="middle" x="1736" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1746.5,-708.5 1746.5,-1076.5 "/>
<text text-anchor="middle" x="1882.5" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1746.5,-1053.5 2018.5,-1053.5 "/>
<text text-anchor="middle" x="1882.5" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1746.5,-1030.5 2018.5,-1030.5 "/>
<text text-anchor="middle" x="1882.5" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1746.5,-1007.5 2018.5,-1007.5 "/>
<text text-anchor="middle" x="1882.5" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1746.5,-984.5 2018.5,-984.5 "/>
<text text-anchor="middle" x="1882.5" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1746.5,-961.5 2018.5,-961.5 "/>
<text text-anchor="middle" x="1882.5" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="1746.5,-938.5 2018.5,-938.5 "/>
<text text-anchor="middle" x="1882.5" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="1746.5,-915.5 2018.5,-915.5 "/>
<text text-anchor="middle" x="1882.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="1746.5,-892.5 2018.5,-892.5 "/>
<text text-anchor="middle" x="1882.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1746.5,-869.5 2018.5,-869.5 "/>
<text text-anchor="middle" x="1882.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="1746.5,-846.5 2018.5,-846.5 "/>
<text text-anchor="middle" x="1882.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1746.5,-823.5 2018.5,-823.5 "/>
<text text-anchor="middle" x="1882.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1746.5,-800.5 2018.5,-800.5 "/>
<text text-anchor="middle" x="1882.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1746.5,-777.5 2018.5,-777.5 "/>
<text text-anchor="middle" x="1882.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1746.5,-754.5 2018.5,-754.5 "/>
<text text-anchor="middle" x="1882.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1746.5,-731.5 2018.5,-731.5 "/>
<text text-anchor="middle" x="1882.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="2018.5,-708.5 2018.5,-1076.5 "/>
<text text-anchor="middle" x="2029" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1944.9302,-708.3139C1953.7534,-696.6599 1962.9662,-685.4351 1972.5,-675 1976.0167,-671.1509 1979.7538,-667.3689 1983.6415,-663.6742"/>
<polygon fill="#000000" stroke="#000000" points="1986.2691,-666.0141 1991.285,-656.6818 1981.5442,-660.8492 1986.2691,-666.0141"/>
<text text-anchor="middle" x="2017" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
</g>
</svg>
</div>
