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
<svg width="3021pt" height="1574pt"
 viewBox="0.00 0.00 3021.00 1574.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1570)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1570 3017,-1570 3017,4 -4,4"/>
<!-- sample -->
<g id="node1" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M862,-720C862,-720 1176,-720 1176,-720 1182,-720 1188,-726 1188,-732 1188,-732 1188,-846 1188,-846 1188,-852 1182,-858 1176,-858 1176,-858 862,-858 862,-858 856,-858 850,-852 850,-846 850,-846 850,-732 850,-732 850,-726 856,-720 862,-720"/>
<text text-anchor="middle" x="884" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="918,-720 918,-858 "/>
<text text-anchor="middle" x="928.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="939,-720 939,-858 "/>
<text text-anchor="middle" x="1053" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="939,-835 1167,-835 "/>
<text text-anchor="middle" x="1053" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="939,-812 1167,-812 "/>
<text text-anchor="middle" x="1053" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="939,-789 1167,-789 "/>
<text text-anchor="middle" x="1053" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="939,-766 1167,-766 "/>
<text text-anchor="middle" x="1053" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="939,-743 1167,-743 "/>
<text text-anchor="middle" x="1053" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="1167,-720 1167,-858 "/>
<text text-anchor="middle" x="1177.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node7" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M1776,-.5C1776,-.5 2166,-.5 2166,-.5 2172,-.5 2178,-6.5 2178,-12.5 2178,-12.5 2178,-195.5 2178,-195.5 2178,-201.5 2172,-207.5 2166,-207.5 2166,-207.5 1776,-207.5 1776,-207.5 1770,-207.5 1764,-201.5 1764,-195.5 1764,-195.5 1764,-12.5 1764,-12.5 1764,-6.5 1770,-.5 1776,-.5"/>
<text text-anchor="middle" x="1792" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="1820,-.5 1820,-207.5 "/>
<text text-anchor="middle" x="1830.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1841,-.5 1841,-207.5 "/>
<text text-anchor="middle" x="1999" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="1841,-184.5 2157,-184.5 "/>
<text text-anchor="middle" x="1999" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="1841,-161.5 2157,-161.5 "/>
<text text-anchor="middle" x="1999" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="1841,-138.5 2157,-138.5 "/>
<text text-anchor="middle" x="1999" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="1841,-115.5 2157,-115.5 "/>
<text text-anchor="middle" x="1999" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="1841,-92.5 2157,-92.5 "/>
<text text-anchor="middle" x="1999" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="1841,-69.5 2157,-69.5 "/>
<text text-anchor="middle" x="1999" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="1841,-46.5 2157,-46.5 "/>
<text text-anchor="middle" x="1999" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="1841,-23.5 2157,-23.5 "/>
<text text-anchor="middle" x="1999" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="2157,-.5 2157,-207.5 "/>
<text text-anchor="middle" x="2167.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge16" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M992.6326,-719.9578C956.2889,-612.3037 904.8841,-401.9908 995,-259 1035.1248,-195.3322 1478.7173,-146.1272 1753.8735,-121.4676"/>
<polygon fill="#000000" stroke="#000000" points="1754.3468,-124.9394 1763.9963,-120.5647 1753.7248,-117.9671 1754.3468,-124.9394"/>
<text text-anchor="middle" x="981.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- participant -->
<g id="node16" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M1685.5,-495.5C1685.5,-495.5 1916.5,-495.5 1916.5,-495.5 1922.5,-495.5 1928.5,-501.5 1928.5,-507.5 1928.5,-507.5 1928.5,-575.5 1928.5,-575.5 1928.5,-581.5 1922.5,-587.5 1916.5,-587.5 1916.5,-587.5 1685.5,-587.5 1685.5,-587.5 1679.5,-587.5 1673.5,-581.5 1673.5,-575.5 1673.5,-575.5 1673.5,-507.5 1673.5,-507.5 1673.5,-501.5 1679.5,-495.5 1685.5,-495.5"/>
<text text-anchor="middle" x="1721.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1769.5,-495.5 1769.5,-587.5 "/>
<text text-anchor="middle" x="1780" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1790.5,-495.5 1790.5,-587.5 "/>
<text text-anchor="middle" x="1849" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="1790.5,-564.5 1907.5,-564.5 "/>
<text text-anchor="middle" x="1849" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="1790.5,-541.5 1907.5,-541.5 "/>
<text text-anchor="middle" x="1849" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1790.5,-518.5 1907.5,-518.5 "/>
<text text-anchor="middle" x="1849" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1907.5,-495.5 1907.5,-587.5 "/>
<text text-anchor="middle" x="1918" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1153.647,-719.8846C1212.47,-691.7784 1282.9797,-660.8447 1349,-639 1452.2109,-604.8497 1572.7121,-579.546 1663.3282,-563.2858"/>
<polygon fill="#000000" stroke="#000000" points="1664.1584,-566.6931 1673.3905,-561.4953 1662.932,-559.8014 1664.1584,-566.6931"/>
<text text-anchor="middle" x="1494.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- imaging_file -->
<g id="node2" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M12,-1117C12,-1117 346,-1117 346,-1117 352,-1117 358,-1123 358,-1129 358,-1129 358,-1427 358,-1427 358,-1433 352,-1439 346,-1439 346,-1439 12,-1439 12,-1439 6,-1439 0,-1433 0,-1427 0,-1427 0,-1129 0,-1129 0,-1123 6,-1117 12,-1117"/>
<text text-anchor="middle" x="52" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="104,-1117 104,-1439 "/>
<text text-anchor="middle" x="114.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="125,-1117 125,-1439 "/>
<text text-anchor="middle" x="231" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="125,-1416 337,-1416 "/>
<text text-anchor="middle" x="231" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="125,-1393 337,-1393 "/>
<text text-anchor="middle" x="231" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="125,-1370 337,-1370 "/>
<text text-anchor="middle" x="231" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="125,-1347 337,-1347 "/>
<text text-anchor="middle" x="231" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="125,-1324 337,-1324 "/>
<text text-anchor="middle" x="231" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="125,-1301 337,-1301 "/>
<text text-anchor="middle" x="231" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="125,-1278 337,-1278 "/>
<text text-anchor="middle" x="231" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="125,-1255 337,-1255 "/>
<text text-anchor="middle" x="231" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="125,-1232 337,-1232 "/>
<text text-anchor="middle" x="231" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="125,-1209 337,-1209 "/>
<text text-anchor="middle" x="231" y="-1193.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="125,-1186 337,-1186 "/>
<text text-anchor="middle" x="231" y="-1170.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="125,-1163 337,-1163 "/>
<text text-anchor="middle" x="231" y="-1147.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="125,-1140 337,-1140 "/>
<text text-anchor="middle" x="231" y="-1124.8" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="337,-1117 337,-1439 "/>
<text text-anchor="middle" x="347.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M256.8895,-1116.6789C285.9118,-1070.311 322.7701,-1023.3284 367,-990 505.8061,-885.4059 699.6853,-834.6792 839.9071,-810.431"/>
<polygon fill="#000000" stroke="#000000" points="840.637,-813.8572 849.9088,-808.7305 839.4636,-806.9562 840.637,-813.8572"/>
<text text-anchor="middle" x="467.5" y="-960.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- study_arm -->
<g id="node3" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M2202.5,-317C2202.5,-317 2499.5,-317 2499.5,-317 2505.5,-317 2511.5,-323 2511.5,-329 2511.5,-329 2511.5,-374 2511.5,-374 2511.5,-380 2505.5,-386 2499.5,-386 2499.5,-386 2202.5,-386 2202.5,-386 2196.5,-386 2190.5,-380 2190.5,-374 2190.5,-374 2190.5,-329 2190.5,-329 2190.5,-323 2196.5,-317 2202.5,-317"/>
<text text-anchor="middle" x="2236.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="2282.5,-317 2282.5,-386 "/>
<text text-anchor="middle" x="2293" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2303.5,-317 2303.5,-386 "/>
<text text-anchor="middle" x="2397" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="2303.5,-363 2490.5,-363 "/>
<text text-anchor="middle" x="2397" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="2303.5,-340 2490.5,-340 "/>
<text text-anchor="middle" x="2397" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="2490.5,-317 2490.5,-386 "/>
<text text-anchor="middle" x="2501" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge17" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2297.7625,-316.8256C2256.1971,-289.7534 2196.0553,-250.582 2138.669,-213.2055"/>
<polygon fill="#000000" stroke="#000000" points="2140.5144,-210.2305 2130.2248,-207.7056 2136.694,-216.0961 2140.5144,-210.2305"/>
<text text-anchor="middle" x="2220.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- methylation_array_file -->
<g id="node4" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M388.5,-1163C388.5,-1163 755.5,-1163 755.5,-1163 761.5,-1163 767.5,-1169 767.5,-1175 767.5,-1175 767.5,-1381 767.5,-1381 767.5,-1387 761.5,-1393 755.5,-1393 755.5,-1393 388.5,-1393 388.5,-1393 382.5,-1393 376.5,-1387 376.5,-1381 376.5,-1381 376.5,-1175 376.5,-1175 376.5,-1169 382.5,-1163 388.5,-1163"/>
<text text-anchor="middle" x="465.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="554.5,-1163 554.5,-1393 "/>
<text text-anchor="middle" x="565" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="575.5,-1163 575.5,-1393 "/>
<text text-anchor="middle" x="661" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="575.5,-1370 746.5,-1370 "/>
<text text-anchor="middle" x="661" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="575.5,-1347 746.5,-1347 "/>
<text text-anchor="middle" x="661" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="575.5,-1324 746.5,-1324 "/>
<text text-anchor="middle" x="661" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="575.5,-1301 746.5,-1301 "/>
<text text-anchor="middle" x="661" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="575.5,-1278 746.5,-1278 "/>
<text text-anchor="middle" x="661" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="575.5,-1255 746.5,-1255 "/>
<text text-anchor="middle" x="661" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="575.5,-1232 746.5,-1232 "/>
<text text-anchor="middle" x="661" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="575.5,-1209 746.5,-1209 "/>
<text text-anchor="middle" x="661" y="-1193.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="575.5,-1186 746.5,-1186 "/>
<text text-anchor="middle" x="661" y="-1170.8" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="746.5,-1163 746.5,-1393 "/>
<text text-anchor="middle" x="757" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M644.007,-1162.7333C680.7317,-1107.8635 727.9426,-1042.8557 777,-990 819.1472,-944.5895 871.46,-899.9561 916.6533,-864.3278"/>
<polygon fill="#000000" stroke="#000000" points="919.0024,-866.9335 924.713,-858.0094 914.6837,-861.4246 919.0024,-866.9335"/>
<text text-anchor="middle" x="898.5" y="-960.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study_admin -->
<g id="node5" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M1161,-259.5C1161,-259.5 1487,-259.5 1487,-259.5 1493,-259.5 1499,-265.5 1499,-271.5 1499,-271.5 1499,-431.5 1499,-431.5 1499,-437.5 1493,-443.5 1487,-443.5 1487,-443.5 1161,-443.5 1161,-443.5 1155,-443.5 1149,-437.5 1149,-431.5 1149,-431.5 1149,-271.5 1149,-271.5 1149,-265.5 1155,-259.5 1161,-259.5"/>
<text text-anchor="middle" x="1203" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="1257,-259.5 1257,-443.5 "/>
<text text-anchor="middle" x="1267.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1278,-259.5 1278,-443.5 "/>
<text text-anchor="middle" x="1378" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="1278,-420.5 1478,-420.5 "/>
<text text-anchor="middle" x="1378" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="1278,-397.5 1478,-397.5 "/>
<text text-anchor="middle" x="1378" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="1278,-374.5 1478,-374.5 "/>
<text text-anchor="middle" x="1378" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="1278,-351.5 1478,-351.5 "/>
<text text-anchor="middle" x="1378" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="1278,-328.5 1478,-328.5 "/>
<text text-anchor="middle" x="1378" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="1278,-305.5 1478,-305.5 "/>
<text text-anchor="middle" x="1378" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="1278,-282.5 1478,-282.5 "/>
<text text-anchor="middle" x="1378" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="1478,-259.5 1478,-443.5 "/>
<text text-anchor="middle" x="1488.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge7" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1499.0371,-262.7884C1502.0399,-261.5005 1505.0292,-260.2366 1508,-259 1587.055,-226.0937 1675.8138,-195.0219 1754.3085,-169.4608"/>
<polygon fill="#000000" stroke="#000000" points="1755.3975,-172.7871 1763.8287,-166.3711 1753.2367,-166.1289 1755.3975,-172.7871"/>
<text text-anchor="middle" x="1638.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- publication -->
<g id="node6" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M1529,-333.5C1529,-333.5 1739,-333.5 1739,-333.5 1745,-333.5 1751,-339.5 1751,-345.5 1751,-345.5 1751,-357.5 1751,-357.5 1751,-363.5 1745,-369.5 1739,-369.5 1739,-369.5 1529,-369.5 1529,-369.5 1523,-369.5 1517,-363.5 1517,-357.5 1517,-357.5 1517,-345.5 1517,-345.5 1517,-339.5 1523,-333.5 1529,-333.5"/>
<text text-anchor="middle" x="1565.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="1614,-333.5 1614,-369.5 "/>
<text text-anchor="middle" x="1624.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1635,-333.5 1635,-369.5 "/>
<text text-anchor="middle" x="1682.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="1730,-333.5 1730,-369.5 "/>
<text text-anchor="middle" x="1740.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge11" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1658.7804,-333.3007C1693.4756,-307.8198 1759.2873,-259.4863 1821.5764,-213.7399"/>
<polygon fill="#000000" stroke="#000000" points="1823.9538,-216.3364 1829.9419,-207.5961 1819.8102,-210.6945 1823.9538,-216.3364"/>
<text text-anchor="middle" x="1853" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- sample_diagnosis -->
<g id="node8" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M798,-1059.5C798,-1059.5 1240,-1059.5 1240,-1059.5 1246,-1059.5 1252,-1065.5 1252,-1071.5 1252,-1071.5 1252,-1484.5 1252,-1484.5 1252,-1490.5 1246,-1496.5 1240,-1496.5 1240,-1496.5 798,-1496.5 798,-1496.5 792,-1496.5 786,-1490.5 786,-1484.5 786,-1484.5 786,-1071.5 786,-1071.5 786,-1065.5 792,-1059.5 798,-1059.5"/>
<text text-anchor="middle" x="857.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="929,-1059.5 929,-1496.5 "/>
<text text-anchor="middle" x="939.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="950,-1059.5 950,-1496.5 "/>
<text text-anchor="middle" x="1090.5" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="950,-1473.5 1231,-1473.5 "/>
<text text-anchor="middle" x="1090.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="950,-1450.5 1231,-1450.5 "/>
<text text-anchor="middle" x="1090.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="950,-1427.5 1231,-1427.5 "/>
<text text-anchor="middle" x="1090.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="950,-1404.5 1231,-1404.5 "/>
<text text-anchor="middle" x="1090.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="950,-1381.5 1231,-1381.5 "/>
<text text-anchor="middle" x="1090.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="950,-1358.5 1231,-1358.5 "/>
<text text-anchor="middle" x="1090.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="950,-1335.5 1231,-1335.5 "/>
<text text-anchor="middle" x="1090.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis_reference_source</text>
<polyline fill="none" stroke="#000000" points="950,-1312.5 1231,-1312.5 "/>
<text text-anchor="middle" x="1090.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="950,-1289.5 1231,-1289.5 "/>
<text text-anchor="middle" x="1090.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="950,-1266.5 1231,-1266.5 "/>
<text text-anchor="middle" x="1090.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="950,-1243.5 1231,-1243.5 "/>
<text text-anchor="middle" x="1090.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="950,-1220.5 1231,-1220.5 "/>
<text text-anchor="middle" x="1090.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="950,-1197.5 1231,-1197.5 "/>
<text text-anchor="middle" x="1090.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="950,-1174.5 1231,-1174.5 "/>
<text text-anchor="middle" x="1090.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="950,-1151.5 1231,-1151.5 "/>
<text text-anchor="middle" x="1090.5" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="950,-1128.5 1231,-1128.5 "/>
<text text-anchor="middle" x="1090.5" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="950,-1105.5 1231,-1105.5 "/>
<text text-anchor="middle" x="1090.5" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="950,-1082.5 1231,-1082.5 "/>
<text text-anchor="middle" x="1090.5" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1231,-1059.5 1231,-1496.5 "/>
<text text-anchor="middle" x="1241.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1019,-1059.2446C1019,-991.1811 1019,-920.4265 1019,-868.3952"/>
<polygon fill="#000000" stroke="#000000" points="1022.5001,-868.2449 1019,-858.2449 1015.5001,-868.245 1022.5001,-868.2449"/>
<text text-anchor="middle" x="1093" y="-960.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
<!-- sequencing_file -->
<g id="node9" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M1281.5,-990.5C1281.5,-990.5 1750.5,-990.5 1750.5,-990.5 1756.5,-990.5 1762.5,-996.5 1762.5,-1002.5 1762.5,-1002.5 1762.5,-1553.5 1762.5,-1553.5 1762.5,-1559.5 1756.5,-1565.5 1750.5,-1565.5 1750.5,-1565.5 1281.5,-1565.5 1281.5,-1565.5 1275.5,-1565.5 1269.5,-1559.5 1269.5,-1553.5 1269.5,-1553.5 1269.5,-1002.5 1269.5,-1002.5 1269.5,-996.5 1275.5,-990.5 1281.5,-990.5"/>
<text text-anchor="middle" x="1333.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="1397.5,-990.5 1397.5,-1565.5 "/>
<text text-anchor="middle" x="1408" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1418.5,-990.5 1418.5,-1565.5 "/>
<text text-anchor="middle" x="1580" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="1418.5,-1542.5 1741.5,-1542.5 "/>
<text text-anchor="middle" x="1580" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1418.5,-1519.5 1741.5,-1519.5 "/>
<text text-anchor="middle" x="1580" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1418.5,-1496.5 1741.5,-1496.5 "/>
<text text-anchor="middle" x="1580" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="1418.5,-1473.5 1741.5,-1473.5 "/>
<text text-anchor="middle" x="1580" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="1418.5,-1450.5 1741.5,-1450.5 "/>
<text text-anchor="middle" x="1580" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1418.5,-1427.5 1741.5,-1427.5 "/>
<text text-anchor="middle" x="1580" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="1418.5,-1404.5 1741.5,-1404.5 "/>
<text text-anchor="middle" x="1580" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1418.5,-1381.5 1741.5,-1381.5 "/>
<text text-anchor="middle" x="1580" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1418.5,-1358.5 1741.5,-1358.5 "/>
<text text-anchor="middle" x="1580" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1418.5,-1335.5 1741.5,-1335.5 "/>
<text text-anchor="middle" x="1580" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1418.5,-1312.5 1741.5,-1312.5 "/>
<text text-anchor="middle" x="1580" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1418.5,-1289.5 1741.5,-1289.5 "/>
<text text-anchor="middle" x="1580" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1418.5,-1266.5 1741.5,-1266.5 "/>
<text text-anchor="middle" x="1580" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="1418.5,-1243.5 1741.5,-1243.5 "/>
<text text-anchor="middle" x="1580" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="1418.5,-1220.5 1741.5,-1220.5 "/>
<text text-anchor="middle" x="1580" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="1418.5,-1197.5 1741.5,-1197.5 "/>
<text text-anchor="middle" x="1580" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="1418.5,-1174.5 1741.5,-1174.5 "/>
<text text-anchor="middle" x="1580" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="1418.5,-1151.5 1741.5,-1151.5 "/>
<text text-anchor="middle" x="1580" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="1418.5,-1128.5 1741.5,-1128.5 "/>
<text text-anchor="middle" x="1580" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1418.5,-1105.5 1741.5,-1105.5 "/>
<text text-anchor="middle" x="1580" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="1418.5,-1082.5 1741.5,-1082.5 "/>
<text text-anchor="middle" x="1580" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="1418.5,-1059.5 1741.5,-1059.5 "/>
<text text-anchor="middle" x="1580" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="1418.5,-1036.5 1741.5,-1036.5 "/>
<text text-anchor="middle" x="1580" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="1418.5,-1013.5 1741.5,-1013.5 "/>
<text text-anchor="middle" x="1580" y="-998.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="1741.5,-990.5 1741.5,-1565.5 "/>
<text text-anchor="middle" x="1752" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1269.2862,-998.0895C1266.5204,-995.3694 1263.7578,-992.6721 1261,-990 1215.7643,-946.1711 1162.1731,-901.0399 1116.9349,-864.6745"/>
<polygon fill="#000000" stroke="#000000" points="1118.8729,-861.7424 1108.8803,-858.2211 1114.496,-867.2053 1118.8729,-861.7424"/>
<text text-anchor="middle" x="1302.5" y="-960.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- study_funding -->
<g id="node10" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M1781.5,-317C1781.5,-317 2160.5,-317 2160.5,-317 2166.5,-317 2172.5,-323 2172.5,-329 2172.5,-329 2172.5,-374 2172.5,-374 2172.5,-380 2166.5,-386 2160.5,-386 2160.5,-386 1781.5,-386 1781.5,-386 1775.5,-386 1769.5,-380 1769.5,-374 1769.5,-374 1769.5,-329 1769.5,-329 1769.5,-323 1775.5,-317 1781.5,-317"/>
<text text-anchor="middle" x="1829" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="1888.5,-317 1888.5,-386 "/>
<text text-anchor="middle" x="1899" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1909.5,-317 1909.5,-386 "/>
<text text-anchor="middle" x="2030.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="1909.5,-363 2151.5,-363 "/>
<text text-anchor="middle" x="2030.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="1909.5,-340 2151.5,-340 "/>
<text text-anchor="middle" x="2030.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="2151.5,-317 2151.5,-386 "/>
<text text-anchor="middle" x="2162" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge4" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1971,-316.8256C1971,-290.8629 1971,-253.7725 1971,-217.8091"/>
<polygon fill="#000000" stroke="#000000" points="1974.5001,-217.7056 1971,-207.7056 1967.5001,-217.7056 1974.5001,-217.7056"/>
<text text-anchor="middle" x="2033" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- diagnosis -->
<g id="node11" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1369.5,-639.5C1369.5,-639.5 1752.5,-639.5 1752.5,-639.5 1758.5,-639.5 1764.5,-645.5 1764.5,-651.5 1764.5,-651.5 1764.5,-926.5 1764.5,-926.5 1764.5,-932.5 1758.5,-938.5 1752.5,-938.5 1752.5,-938.5 1369.5,-938.5 1369.5,-938.5 1363.5,-938.5 1357.5,-932.5 1357.5,-926.5 1357.5,-926.5 1357.5,-651.5 1357.5,-651.5 1357.5,-645.5 1363.5,-639.5 1369.5,-639.5"/>
<text text-anchor="middle" x="1399.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1441.5,-639.5 1441.5,-938.5 "/>
<text text-anchor="middle" x="1452" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1462.5,-639.5 1462.5,-938.5 "/>
<text text-anchor="middle" x="1603" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1462.5,-915.5 1743.5,-915.5 "/>
<text text-anchor="middle" x="1603" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1462.5,-892.5 1743.5,-892.5 "/>
<text text-anchor="middle" x="1603" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1462.5,-869.5 1743.5,-869.5 "/>
<text text-anchor="middle" x="1603" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1462.5,-846.5 1743.5,-846.5 "/>
<text text-anchor="middle" x="1603" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1462.5,-823.5 1743.5,-823.5 "/>
<text text-anchor="middle" x="1603" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="1462.5,-800.5 1743.5,-800.5 "/>
<text text-anchor="middle" x="1603" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1462.5,-777.5 1743.5,-777.5 "/>
<text text-anchor="middle" x="1603" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1462.5,-754.5 1743.5,-754.5 "/>
<text text-anchor="middle" x="1603" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis_reference_source</text>
<polyline fill="none" stroke="#000000" points="1462.5,-731.5 1743.5,-731.5 "/>
<text text-anchor="middle" x="1603" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="1462.5,-708.5 1743.5,-708.5 "/>
<text text-anchor="middle" x="1603" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="1462.5,-685.5 1743.5,-685.5 "/>
<text text-anchor="middle" x="1603" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="1462.5,-662.5 1743.5,-662.5 "/>
<text text-anchor="middle" x="1603" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="1743.5,-639.5 1743.5,-938.5 "/>
<text text-anchor="middle" x="1754" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1665.6967,-639.1145C1676.0799,-627.4238 1686.9019,-616.2116 1698,-606 1702.5851,-601.7811 1707.483,-597.6773 1712.5605,-593.7181"/>
<polygon fill="#000000" stroke="#000000" points="1714.7803,-596.4281 1720.6682,-587.6199 1710.5726,-590.8339 1714.7803,-596.4281"/>
<text text-anchor="middle" x="1742.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- synonym -->
<g id="node12" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M1792.5,-1255C1792.5,-1255 2093.5,-1255 2093.5,-1255 2099.5,-1255 2105.5,-1261 2105.5,-1267 2105.5,-1267 2105.5,-1289 2105.5,-1289 2105.5,-1295 2099.5,-1301 2093.5,-1301 2093.5,-1301 1792.5,-1301 1792.5,-1301 1786.5,-1301 1780.5,-1295 1780.5,-1289 1780.5,-1289 1780.5,-1267 1780.5,-1267 1780.5,-1261 1786.5,-1255 1792.5,-1255"/>
<text text-anchor="middle" x="1820.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="1860.5,-1255 1860.5,-1301 "/>
<text text-anchor="middle" x="1871" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1881.5,-1255 1881.5,-1301 "/>
<text text-anchor="middle" x="1983" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="1881.5,-1278 2084.5,-1278 "/>
<text text-anchor="middle" x="1983" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="2084.5,-1255 2084.5,-1301 "/>
<text text-anchor="middle" x="2095" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1936.8837,-1254.7815C1920.7198,-1198.4839 1871.1446,-1054.6009 1772,-990 1732.3365,-964.1559 1394.5833,-951.778 1349,-939 1283.284,-920.5783 1214.0245,-890.8456 1156.0171,-862.6911"/>
<polygon fill="#000000" stroke="#000000" points="1157.3273,-859.4357 1146.8062,-858.188 1154.2528,-865.7245 1157.3273,-859.4357"/>
<text text-anchor="middle" x="1723.5" y="-960.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge8" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2105.6527,-1269.5844C2385.4203,-1245.4044 2928,-1151.7492 2928,-789 2928,-789 2928,-789 2928,-351.5 2928,-309.5306 2939.0747,-288.2736 2909,-259 2809.1103,-161.7711 2432.6903,-125.3684 2188.1346,-111.8528"/>
<polygon fill="#000000" stroke="#000000" points="2188.2175,-108.3523 2178.0421,-111.3039 2187.8372,-115.3419 2188.2175,-108.3523"/>
<text text-anchor="middle" x="2970.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1930.5942,-1254.6145C1902.7831,-1200.7768 1835.9389,-1063.1526 1811,-939 1786.9622,-819.3334 1791.3585,-675.3496 1796.3784,-597.7229"/>
<polygon fill="#000000" stroke="#000000" points="1799.875,-597.8894 1797.0558,-587.6766 1792.8909,-597.4184 1799.875,-597.8894"/>
<text text-anchor="middle" x="1853.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- therapeutic_procedure -->
<g id="node13" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M1916.5,-731.5C1916.5,-731.5 2273.5,-731.5 2273.5,-731.5 2279.5,-731.5 2285.5,-737.5 2285.5,-743.5 2285.5,-743.5 2285.5,-834.5 2285.5,-834.5 2285.5,-840.5 2279.5,-846.5 2273.5,-846.5 2273.5,-846.5 1916.5,-846.5 1916.5,-846.5 1910.5,-846.5 1904.5,-840.5 1904.5,-834.5 1904.5,-834.5 1904.5,-743.5 1904.5,-743.5 1904.5,-737.5 1910.5,-731.5 1916.5,-731.5"/>
<text text-anchor="middle" x="1995" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="2085.5,-731.5 2085.5,-846.5 "/>
<text text-anchor="middle" x="2096" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2106.5,-731.5 2106.5,-846.5 "/>
<text text-anchor="middle" x="2185.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="2106.5,-823.5 2264.5,-823.5 "/>
<text text-anchor="middle" x="2185.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="2106.5,-800.5 2264.5,-800.5 "/>
<text text-anchor="middle" x="2185.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="2106.5,-777.5 2264.5,-777.5 "/>
<text text-anchor="middle" x="2185.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="2106.5,-754.5 2264.5,-754.5 "/>
<text text-anchor="middle" x="2185.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="2264.5,-731.5 2264.5,-846.5 "/>
<text text-anchor="middle" x="2275" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2026.4411,-731.2846C1977.258,-689.8804 1911.5069,-634.5287 1863.7113,-594.2926"/>
<polygon fill="#000000" stroke="#000000" points="1865.806,-591.481 1855.9018,-587.7183 1861.2979,-596.8361 1865.806,-591.481"/>
<text text-anchor="middle" x="1980" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- clinical_measure_file -->
<g id="node14" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M2326,-662.5C2326,-662.5 2678,-662.5 2678,-662.5 2684,-662.5 2690,-668.5 2690,-674.5 2690,-674.5 2690,-903.5 2690,-903.5 2690,-909.5 2684,-915.5 2678,-915.5 2678,-915.5 2326,-915.5 2326,-915.5 2320,-915.5 2314,-909.5 2314,-903.5 2314,-903.5 2314,-674.5 2314,-674.5 2314,-668.5 2320,-662.5 2326,-662.5"/>
<text text-anchor="middle" x="2397.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="2481,-662.5 2481,-915.5 "/>
<text text-anchor="middle" x="2491.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2502,-662.5 2502,-915.5 "/>
<text text-anchor="middle" x="2585.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2502,-892.5 2669,-892.5 "/>
<text text-anchor="middle" x="2585.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2502,-869.5 2669,-869.5 "/>
<text text-anchor="middle" x="2585.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2502,-846.5 2669,-846.5 "/>
<text text-anchor="middle" x="2585.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2502,-823.5 2669,-823.5 "/>
<text text-anchor="middle" x="2585.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2502,-800.5 2669,-800.5 "/>
<text text-anchor="middle" x="2585.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2502,-777.5 2669,-777.5 "/>
<text text-anchor="middle" x="2585.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2502,-754.5 2669,-754.5 "/>
<text text-anchor="middle" x="2585.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2502,-731.5 2669,-731.5 "/>
<text text-anchor="middle" x="2585.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2502,-708.5 2669,-708.5 "/>
<text text-anchor="middle" x="2585.5" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2502,-685.5 2669,-685.5 "/>
<text text-anchor="middle" x="2585.5" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="2669,-662.5 2669,-915.5 "/>
<text text-anchor="middle" x="2679.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge12" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2524.309,-662.3631C2545.315,-525.924 2567.269,-320.1107 2521,-259 2479.7761,-204.5527 2323.8113,-163.8378 2188.447,-137.8329"/>
<polygon fill="#000000" stroke="#000000" points="2188.8031,-134.3379 2178.3253,-135.9082 2187.4954,-141.2147 2188.8031,-134.3379"/>
<text text-anchor="middle" x="2632" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2340.6654,-662.4173C2325.6891,-653.674 2310.3588,-645.6931 2295,-639 2180.7006,-589.1904 2040.4255,-564.6182 1938.5964,-552.623"/>
<polygon fill="#000000" stroke="#000000" points="1938.8889,-549.1337 1928.554,-551.4661 1938.0877,-556.0877 1938.8889,-549.1337"/>
<text text-anchor="middle" x="2373.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- study_personnel -->
<g id="node15" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M2580.5,-294C2580.5,-294 2887.5,-294 2887.5,-294 2893.5,-294 2899.5,-300 2899.5,-306 2899.5,-306 2899.5,-397 2899.5,-397 2899.5,-403 2893.5,-409 2887.5,-409 2887.5,-409 2580.5,-409 2580.5,-409 2574.5,-409 2568.5,-403 2568.5,-397 2568.5,-397 2568.5,-306 2568.5,-306 2568.5,-300 2574.5,-294 2580.5,-294"/>
<text text-anchor="middle" x="2635.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="2702.5,-294 2702.5,-409 "/>
<text text-anchor="middle" x="2713" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2723.5,-294 2723.5,-409 "/>
<text text-anchor="middle" x="2801" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="2723.5,-386 2878.5,-386 "/>
<text text-anchor="middle" x="2801" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="2723.5,-363 2878.5,-363 "/>
<text text-anchor="middle" x="2801" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="2723.5,-340 2878.5,-340 "/>
<text text-anchor="middle" x="2801" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="2723.5,-317 2878.5,-317 "/>
<text text-anchor="middle" x="2801" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="2878.5,-294 2878.5,-409 "/>
<text text-anchor="middle" x="2889" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge19" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2665.2479,-293.7431C2633.2245,-269.5155 2593.522,-243.0635 2554,-226 2438.3445,-176.066 2300.7407,-146.0289 2188.2683,-128.2598"/>
<polygon fill="#000000" stroke="#000000" points="2188.5743,-124.7654 2178.1547,-126.6843 2187.4967,-131.6819 2188.5743,-124.7654"/>
<text text-anchor="middle" x="2649.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge13" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1928.7723,-517.1802C2003.9604,-500.8197 2100.0643,-476.3148 2182,-444 2218.1076,-429.7595 2256.2063,-409.4224 2287.0716,-391.4421"/>
<polygon fill="#000000" stroke="#000000" points="2289.1472,-394.2818 2295.9917,-386.1944 2285.5978,-388.2484 2289.1472,-394.2818"/>
<text text-anchor="middle" x="2181.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge14" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1673.3347,-534.2431C1467.2805,-521.2134 1080.1683,-490.7715 1039,-444 984.6748,-382.2808 985.8427,-321.7279 1039,-259 1084.7895,-204.9664 1493.0258,-153.2892 1753.7991,-125.3841"/>
<polygon fill="#000000" stroke="#000000" points="1754.2118,-128.8601 1763.7844,-124.3195 1753.4696,-121.8995 1754.2118,-128.8601"/>
<text text-anchor="middle" x="1089.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
</g>
</svg>
</div>
