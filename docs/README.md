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
<svg width="2683pt" height="1574pt"
 viewBox="0.00 0.00 2683.00 1574.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1570)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1570 2679,-1570 2679,4 -4,4"/>
<!-- study_funding -->
<g id="node1" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M12,-317C12,-317 391,-317 391,-317 397,-317 403,-323 403,-329 403,-329 403,-374 403,-374 403,-380 397,-386 391,-386 391,-386 12,-386 12,-386 6,-386 0,-380 0,-374 0,-374 0,-329 0,-329 0,-323 6,-317 12,-317"/>
<text text-anchor="middle" x="59.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="119,-317 119,-386 "/>
<text text-anchor="middle" x="129.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="140,-317 140,-386 "/>
<text text-anchor="middle" x="261" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="140,-363 382,-363 "/>
<text text-anchor="middle" x="261" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="140,-340 382,-340 "/>
<text text-anchor="middle" x="261" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="382,-317 382,-386 "/>
<text text-anchor="middle" x="392.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node8" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M894.5,-.5C894.5,-.5 1284.5,-.5 1284.5,-.5 1290.5,-.5 1296.5,-6.5 1296.5,-12.5 1296.5,-12.5 1296.5,-195.5 1296.5,-195.5 1296.5,-201.5 1290.5,-207.5 1284.5,-207.5 1284.5,-207.5 894.5,-207.5 894.5,-207.5 888.5,-207.5 882.5,-201.5 882.5,-195.5 882.5,-195.5 882.5,-12.5 882.5,-12.5 882.5,-6.5 888.5,-.5 894.5,-.5"/>
<text text-anchor="middle" x="910.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="938.5,-.5 938.5,-207.5 "/>
<text text-anchor="middle" x="949" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="959.5,-.5 959.5,-207.5 "/>
<text text-anchor="middle" x="1117.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="959.5,-184.5 1275.5,-184.5 "/>
<text text-anchor="middle" x="1117.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="959.5,-161.5 1275.5,-161.5 "/>
<text text-anchor="middle" x="1117.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="959.5,-138.5 1275.5,-138.5 "/>
<text text-anchor="middle" x="1117.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="959.5,-115.5 1275.5,-115.5 "/>
<text text-anchor="middle" x="1117.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="959.5,-92.5 1275.5,-92.5 "/>
<text text-anchor="middle" x="1117.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="959.5,-69.5 1275.5,-69.5 "/>
<text text-anchor="middle" x="1117.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="959.5,-46.5 1275.5,-46.5 "/>
<text text-anchor="middle" x="1117.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="959.5,-23.5 1275.5,-23.5 "/>
<text text-anchor="middle" x="1117.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="1275.5,-.5 1275.5,-207.5 "/>
<text text-anchor="middle" x="1286" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge15" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M217.3299,-316.7344C232.5384,-287.5446 258.3887,-247.2934 293.5,-226 388.2078,-168.5641 670.6202,-135.4901 872.0974,-118.6241"/>
<polygon fill="#000000" stroke="#000000" points="872.5543,-122.0983 882.2308,-117.7837 871.9757,-115.1222 872.5543,-122.0983"/>
<text text-anchor="middle" x="355.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- synonym -->
<g id="node2" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M327,-1243.5C327,-1243.5 628,-1243.5 628,-1243.5 634,-1243.5 640,-1249.5 640,-1255.5 640,-1255.5 640,-1323.5 640,-1323.5 640,-1329.5 634,-1335.5 628,-1335.5 628,-1335.5 327,-1335.5 327,-1335.5 321,-1335.5 315,-1329.5 315,-1323.5 315,-1323.5 315,-1255.5 315,-1255.5 315,-1249.5 321,-1243.5 327,-1243.5"/>
<text text-anchor="middle" x="355" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="395,-1243.5 395,-1335.5 "/>
<text text-anchor="middle" x="405.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="416,-1243.5 416,-1335.5 "/>
<text text-anchor="middle" x="517.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_id</text>
<polyline fill="none" stroke="#000000" points="416,-1312.5 619,-1312.5 "/>
<text text-anchor="middle" x="517.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_node</text>
<polyline fill="none" stroke="#000000" points="416,-1289.5 619,-1289.5 "/>
<text text-anchor="middle" x="517.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="416,-1266.5 619,-1266.5 "/>
<text text-anchor="middle" x="517.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="619,-1243.5 619,-1335.5 "/>
<text text-anchor="middle" x="629.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node6" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M892,-495.5C892,-495.5 1123,-495.5 1123,-495.5 1129,-495.5 1135,-501.5 1135,-507.5 1135,-507.5 1135,-575.5 1135,-575.5 1135,-581.5 1129,-587.5 1123,-587.5 1123,-587.5 892,-587.5 892,-587.5 886,-587.5 880,-581.5 880,-575.5 880,-575.5 880,-507.5 880,-507.5 880,-501.5 886,-495.5 892,-495.5"/>
<text text-anchor="middle" x="928" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="976,-495.5 976,-587.5 "/>
<text text-anchor="middle" x="986.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="997,-495.5 997,-587.5 "/>
<text text-anchor="middle" x="1055.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="997,-564.5 1114,-564.5 "/>
<text text-anchor="middle" x="1055.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="997,-541.5 1114,-541.5 "/>
<text text-anchor="middle" x="1055.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="997,-518.5 1114,-518.5 "/>
<text text-anchor="middle" x="1055.5" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1114,-495.5 1114,-587.5 "/>
<text text-anchor="middle" x="1124.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M474.8166,-1243.0145C467.1198,-1101.8295 447.8996,-684.8452 486.5,-639 534.7091,-581.7427 732.0356,-557.8834 869.4943,-548.097"/>
<polygon fill="#000000" stroke="#000000" points="869.9648,-551.5728 879.6983,-547.3884 869.4798,-544.5896 869.9648,-551.5728"/>
<text text-anchor="middle" x="529" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge14" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M470.2619,-1243.4533C457.3077,-1156.9192 431.5,-964.0064 431.5,-800.5 431.5,-800.5 431.5,-800.5 431.5,-351.5 431.5,-306.8842 436.6237,-288.0338 470.5,-259 531.0489,-207.1064 719.2551,-164.56 872.3914,-137.2591"/>
<polygon fill="#000000" stroke="#000000" points="873.189,-140.6725 882.4258,-135.483 871.9688,-133.7796 873.189,-140.6725"/>
<text text-anchor="middle" x="474" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- sample -->
<g id="node9" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1811.5,-639.5C1811.5,-639.5 2125.5,-639.5 2125.5,-639.5 2131.5,-639.5 2137.5,-645.5 2137.5,-651.5 2137.5,-651.5 2137.5,-949.5 2137.5,-949.5 2137.5,-955.5 2131.5,-961.5 2125.5,-961.5 2125.5,-961.5 1811.5,-961.5 1811.5,-961.5 1805.5,-961.5 1799.5,-955.5 1799.5,-949.5 1799.5,-949.5 1799.5,-651.5 1799.5,-651.5 1799.5,-645.5 1805.5,-639.5 1811.5,-639.5"/>
<text text-anchor="middle" x="1833.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1867.5,-639.5 1867.5,-961.5 "/>
<text text-anchor="middle" x="1878" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1888.5,-639.5 1888.5,-961.5 "/>
<text text-anchor="middle" x="2002.5" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1888.5,-938.5 2116.5,-938.5 "/>
<text text-anchor="middle" x="2002.5" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1888.5,-915.5 2116.5,-915.5 "/>
<text text-anchor="middle" x="2002.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1888.5,-892.5 2116.5,-892.5 "/>
<text text-anchor="middle" x="2002.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1888.5,-869.5 2116.5,-869.5 "/>
<text text-anchor="middle" x="2002.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1888.5,-846.5 2116.5,-846.5 "/>
<text text-anchor="middle" x="2002.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="1888.5,-823.5 2116.5,-823.5 "/>
<text text-anchor="middle" x="2002.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1888.5,-800.5 2116.5,-800.5 "/>
<text text-anchor="middle" x="2002.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="1888.5,-777.5 2116.5,-777.5 "/>
<text text-anchor="middle" x="2002.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="1888.5,-754.5 2116.5,-754.5 "/>
<text text-anchor="middle" x="2002.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage</text>
<polyline fill="none" stroke="#000000" points="1888.5,-731.5 2116.5,-731.5 "/>
<text text-anchor="middle" x="2002.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1888.5,-708.5 2116.5,-708.5 "/>
<text text-anchor="middle" x="2002.5" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1888.5,-685.5 2116.5,-685.5 "/>
<text text-anchor="middle" x="2002.5" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1888.5,-662.5 2116.5,-662.5 "/>
<text text-anchor="middle" x="2002.5" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_status</text>
<polyline fill="none" stroke="#000000" points="2116.5,-639.5 2116.5,-961.5 "/>
<text text-anchor="middle" x="2127" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M604.5562,-1243.4163C778.8404,-1181.9354 1102.8992,-1073.7889 1387.5,-1013 1429.3978,-1004.0509 1717.9227,-983.1425 1789.682,-961.2679"/>
<polygon fill="#000000" stroke="#000000" points="1791.0848,-964.4814 1799.2668,-957.7506 1788.6732,-957.9099 1791.0848,-964.4814"/>
<text text-anchor="middle" x="1726" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- imaging_file -->
<g id="node3" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M1408.5,-1128.5C1408.5,-1128.5 1742.5,-1128.5 1742.5,-1128.5 1748.5,-1128.5 1754.5,-1134.5 1754.5,-1140.5 1754.5,-1140.5 1754.5,-1438.5 1754.5,-1438.5 1754.5,-1444.5 1748.5,-1450.5 1742.5,-1450.5 1742.5,-1450.5 1408.5,-1450.5 1408.5,-1450.5 1402.5,-1450.5 1396.5,-1444.5 1396.5,-1438.5 1396.5,-1438.5 1396.5,-1140.5 1396.5,-1140.5 1396.5,-1134.5 1402.5,-1128.5 1408.5,-1128.5"/>
<text text-anchor="middle" x="1448.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="1500.5,-1128.5 1500.5,-1450.5 "/>
<text text-anchor="middle" x="1511" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1521.5,-1128.5 1521.5,-1450.5 "/>
<text text-anchor="middle" x="1627.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1521.5,-1427.5 1733.5,-1427.5 "/>
<text text-anchor="middle" x="1627.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1521.5,-1404.5 1733.5,-1404.5 "/>
<text text-anchor="middle" x="1627.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1521.5,-1381.5 1733.5,-1381.5 "/>
<text text-anchor="middle" x="1627.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1521.5,-1358.5 1733.5,-1358.5 "/>
<text text-anchor="middle" x="1627.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1521.5,-1335.5 1733.5,-1335.5 "/>
<text text-anchor="middle" x="1627.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1521.5,-1312.5 1733.5,-1312.5 "/>
<text text-anchor="middle" x="1627.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1521.5,-1289.5 1733.5,-1289.5 "/>
<text text-anchor="middle" x="1627.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1521.5,-1266.5 1733.5,-1266.5 "/>
<text text-anchor="middle" x="1627.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1521.5,-1243.5 1733.5,-1243.5 "/>
<text text-anchor="middle" x="1627.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="1521.5,-1220.5 1733.5,-1220.5 "/>
<text text-anchor="middle" x="1627.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="1521.5,-1197.5 1733.5,-1197.5 "/>
<text text-anchor="middle" x="1627.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="1521.5,-1174.5 1733.5,-1174.5 "/>
<text text-anchor="middle" x="1627.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1521.5,-1151.5 1733.5,-1151.5 "/>
<text text-anchor="middle" x="1627.5" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="1733.5,-1128.5 1733.5,-1450.5 "/>
<text text-anchor="middle" x="1744" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1679.072,-1128.3228C1705.7108,-1089.6438 1735.1675,-1049.1032 1764.5,-1013 1776.3084,-998.466 1788.9124,-983.7421 1801.8429,-969.1801"/>
<polygon fill="#000000" stroke="#000000" points="1804.5791,-971.3708 1808.6319,-961.5817 1799.3591,-966.7068 1804.5791,-971.3708"/>
<text text-anchor="middle" x="1844" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- publication -->
<g id="node4" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M491.5,-333.5C491.5,-333.5 701.5,-333.5 701.5,-333.5 707.5,-333.5 713.5,-339.5 713.5,-345.5 713.5,-345.5 713.5,-357.5 713.5,-357.5 713.5,-363.5 707.5,-369.5 701.5,-369.5 701.5,-369.5 491.5,-369.5 491.5,-369.5 485.5,-369.5 479.5,-363.5 479.5,-357.5 479.5,-357.5 479.5,-345.5 479.5,-345.5 479.5,-339.5 485.5,-333.5 491.5,-333.5"/>
<text text-anchor="middle" x="528" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="576.5,-333.5 576.5,-369.5 "/>
<text text-anchor="middle" x="587" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="597.5,-333.5 597.5,-369.5 "/>
<text text-anchor="middle" x="645" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="692.5,-333.5 692.5,-369.5 "/>
<text text-anchor="middle" x="703" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge11" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M617.7449,-333.4884C641.9777,-313.5337 683.3278,-281.2438 722.5,-259 769.6365,-232.2337 822.3082,-207.329 872.7083,-185.6547"/>
<polygon fill="#000000" stroke="#000000" points="874.2705,-188.7933 882.0908,-181.6454 871.5199,-182.3564 874.2705,-188.7933"/>
<text text-anchor="middle" x="831.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- diagnosis -->
<g id="node5" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M593,-651C593,-651 976,-651 976,-651 982,-651 988,-657 988,-663 988,-663 988,-938 988,-938 988,-944 982,-950 976,-950 976,-950 593,-950 593,-950 587,-950 581,-944 581,-938 581,-938 581,-663 581,-663 581,-657 587,-651 593,-651"/>
<text text-anchor="middle" x="623" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="665,-651 665,-950 "/>
<text text-anchor="middle" x="675.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="686,-651 686,-950 "/>
<text text-anchor="middle" x="826.5" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="686,-927 967,-927 "/>
<text text-anchor="middle" x="826.5" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="686,-904 967,-904 "/>
<text text-anchor="middle" x="826.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="686,-881 967,-881 "/>
<text text-anchor="middle" x="826.5" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="686,-858 967,-858 "/>
<text text-anchor="middle" x="826.5" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="686,-835 967,-835 "/>
<text text-anchor="middle" x="826.5" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="686,-812 967,-812 "/>
<text text-anchor="middle" x="826.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="686,-789 967,-789 "/>
<text text-anchor="middle" x="826.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="686,-766 967,-766 "/>
<text text-anchor="middle" x="826.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis_reference_source</text>
<polyline fill="none" stroke="#000000" points="686,-743 967,-743 "/>
<text text-anchor="middle" x="826.5" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="686,-720 967,-720 "/>
<text text-anchor="middle" x="826.5" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="686,-697 967,-697 "/>
<text text-anchor="middle" x="826.5" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="686,-674 967,-674 "/>
<text text-anchor="middle" x="826.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="967,-651 967,-950 "/>
<text text-anchor="middle" x="977.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M873.2282,-650.7355C885.2092,-634.9048 898.044,-619.6341 911.5,-606 915.566,-601.8801 919.9337,-597.8702 924.4835,-593.9977"/>
<polygon fill="#000000" stroke="#000000" points="926.7641,-596.6541 932.2913,-587.6152 922.3338,-591.2344 926.7641,-596.6541"/>
<text text-anchor="middle" x="956" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge18" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1061.5655,-495.217C1065.8832,-489.4962 1069.6643,-483.3945 1072.5,-477 1092.3519,-432.2341 1094.6927,-310.3874 1093.2772,-218.0356"/>
<polygon fill="#000000" stroke="#000000" points="1096.7724,-217.7186 1093.1028,-207.7795 1089.7734,-217.8376 1096.7724,-217.7186"/>
<text text-anchor="middle" x="1145" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_arm -->
<g id="node14" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M744,-317C744,-317 1041,-317 1041,-317 1047,-317 1053,-323 1053,-329 1053,-329 1053,-374 1053,-374 1053,-380 1047,-386 1041,-386 1041,-386 744,-386 744,-386 738,-386 732,-380 732,-374 732,-374 732,-329 732,-329 732,-323 738,-317 744,-317"/>
<text text-anchor="middle" x="778" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="824,-317 824,-386 "/>
<text text-anchor="middle" x="834.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="845,-317 845,-386 "/>
<text text-anchor="middle" x="938.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="845,-363 1032,-363 "/>
<text text-anchor="middle" x="938.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="845,-340 1032,-340 "/>
<text text-anchor="middle" x="938.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="1032,-317 1032,-386 "/>
<text text-anchor="middle" x="1042.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge19" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M979.3678,-495.0208C960.9279,-464.5547 936.9796,-424.988 918.8994,-395.1164"/>
<polygon fill="#000000" stroke="#000000" points="921.6617,-392.9207 913.4893,-386.178 915.6731,-396.5454 921.6617,-392.9207"/>
<text text-anchor="middle" x="1018" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- therapeutic_procedure -->
<g id="node7" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M1018,-743C1018,-743 1375,-743 1375,-743 1381,-743 1387,-749 1387,-755 1387,-755 1387,-846 1387,-846 1387,-852 1381,-858 1375,-858 1375,-858 1018,-858 1018,-858 1012,-858 1006,-852 1006,-846 1006,-846 1006,-755 1006,-755 1006,-749 1012,-743 1018,-743"/>
<text text-anchor="middle" x="1096.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="1187,-743 1187,-858 "/>
<text text-anchor="middle" x="1197.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1208,-743 1208,-858 "/>
<text text-anchor="middle" x="1287" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="1208,-835 1366,-835 "/>
<text text-anchor="middle" x="1287" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="1208,-812 1366,-812 "/>
<text text-anchor="middle" x="1287" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1208,-789 1366,-789 "/>
<text text-anchor="middle" x="1287" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="1208,-766 1366,-766 "/>
<text text-anchor="middle" x="1287" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1366,-743 1366,-858 "/>
<text text-anchor="middle" x="1376.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1110.0342,-742.8176C1071.3562,-711.7764 1029.7528,-669.8248 1008.5,-621 1005.3624,-613.7919 1003.5714,-605.8563 1002.6831,-597.8735"/>
<polygon fill="#000000" stroke="#000000" points="1006.1681,-597.5316 1002.0073,-587.788 999.1838,-597.9997 1006.1681,-597.5316"/>
<text text-anchor="middle" x="1101.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1799.2706,-643.2412C1796.3631,-641.7646 1793.439,-640.3491 1790.5,-639 1678.7412,-587.6964 1338.6225,-560.398 1145.4184,-548.6677"/>
<polygon fill="#000000" stroke="#000000" points="1145.3829,-545.1594 1135.1909,-548.053 1144.9628,-552.1468 1145.3829,-545.1594"/>
<text text-anchor="middle" x="1766" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge3" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2013.8291,-639.2778C2036.7435,-520.2793 2043.6488,-361.7947 1955.5,-259 1873.2064,-163.0334 1535.2323,-126.3663 1306.6528,-112.4356"/>
<polygon fill="#000000" stroke="#000000" points="1306.7236,-108.9337 1296.5322,-111.8293 1306.305,-115.9211 1306.7236,-108.9337"/>
<text text-anchor="middle" x="2064" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_admin -->
<g id="node10" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M1220.5,-259.5C1220.5,-259.5 1546.5,-259.5 1546.5,-259.5 1552.5,-259.5 1558.5,-265.5 1558.5,-271.5 1558.5,-271.5 1558.5,-431.5 1558.5,-431.5 1558.5,-437.5 1552.5,-443.5 1546.5,-443.5 1546.5,-443.5 1220.5,-443.5 1220.5,-443.5 1214.5,-443.5 1208.5,-437.5 1208.5,-431.5 1208.5,-431.5 1208.5,-271.5 1208.5,-271.5 1208.5,-265.5 1214.5,-259.5 1220.5,-259.5"/>
<text text-anchor="middle" x="1262.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="1316.5,-259.5 1316.5,-443.5 "/>
<text text-anchor="middle" x="1327" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1337.5,-259.5 1337.5,-443.5 "/>
<text text-anchor="middle" x="1437.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="1337.5,-420.5 1537.5,-420.5 "/>
<text text-anchor="middle" x="1437.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="1337.5,-397.5 1537.5,-397.5 "/>
<text text-anchor="middle" x="1437.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="1337.5,-374.5 1537.5,-374.5 "/>
<text text-anchor="middle" x="1437.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="1337.5,-351.5 1537.5,-351.5 "/>
<text text-anchor="middle" x="1437.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="1337.5,-328.5 1537.5,-328.5 "/>
<text text-anchor="middle" x="1437.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="1337.5,-305.5 1537.5,-305.5 "/>
<text text-anchor="middle" x="1437.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="1337.5,-282.5 1537.5,-282.5 "/>
<text text-anchor="middle" x="1437.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="1537.5,-259.5 1537.5,-443.5 "/>
<text text-anchor="middle" x="1548" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge10" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1274.0253,-259.3401C1256.753,-244.7997 1238.74,-229.6357 1221.0299,-214.7267"/>
<polygon fill="#000000" stroke="#000000" points="1222.8221,-211.6604 1212.9179,-207.8977 1218.314,-217.0155 1222.8221,-211.6604"/>
<text text-anchor="middle" x="1301" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- methylation_array_file -->
<g id="node11" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M1785,-1174.5C1785,-1174.5 2152,-1174.5 2152,-1174.5 2158,-1174.5 2164,-1180.5 2164,-1186.5 2164,-1186.5 2164,-1392.5 2164,-1392.5 2164,-1398.5 2158,-1404.5 2152,-1404.5 2152,-1404.5 1785,-1404.5 1785,-1404.5 1779,-1404.5 1773,-1398.5 1773,-1392.5 1773,-1392.5 1773,-1186.5 1773,-1186.5 1773,-1180.5 1779,-1174.5 1785,-1174.5"/>
<text text-anchor="middle" x="1862" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="1951,-1174.5 1951,-1404.5 "/>
<text text-anchor="middle" x="1961.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1972,-1174.5 1972,-1404.5 "/>
<text text-anchor="middle" x="2057.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1972,-1381.5 2143,-1381.5 "/>
<text text-anchor="middle" x="2057.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1972,-1358.5 2143,-1358.5 "/>
<text text-anchor="middle" x="2057.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1972,-1335.5 2143,-1335.5 "/>
<text text-anchor="middle" x="2057.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1972,-1312.5 2143,-1312.5 "/>
<text text-anchor="middle" x="2057.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1972,-1289.5 2143,-1289.5 "/>
<text text-anchor="middle" x="2057.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1972,-1266.5 2143,-1266.5 "/>
<text text-anchor="middle" x="2057.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1972,-1243.5 2143,-1243.5 "/>
<text text-anchor="middle" x="2057.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1972,-1220.5 2143,-1220.5 "/>
<text text-anchor="middle" x="2057.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="1972,-1197.5 2143,-1197.5 "/>
<text text-anchor="middle" x="2057.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="2143,-1174.5 2143,-1404.5 "/>
<text text-anchor="middle" x="2153.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1968.5,-1174.233C1968.5,-1113.9378 1968.5,-1038.928 1968.5,-971.9656"/>
<polygon fill="#000000" stroke="#000000" points="1972.0001,-971.7198 1968.5,-961.7198 1965.0001,-971.7198 1972.0001,-971.7198"/>
<text text-anchor="middle" x="2060" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node12" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M1417.5,-685.5C1417.5,-685.5 1769.5,-685.5 1769.5,-685.5 1775.5,-685.5 1781.5,-691.5 1781.5,-697.5 1781.5,-697.5 1781.5,-903.5 1781.5,-903.5 1781.5,-909.5 1775.5,-915.5 1769.5,-915.5 1769.5,-915.5 1417.5,-915.5 1417.5,-915.5 1411.5,-915.5 1405.5,-909.5 1405.5,-903.5 1405.5,-903.5 1405.5,-697.5 1405.5,-697.5 1405.5,-691.5 1411.5,-685.5 1417.5,-685.5"/>
<text text-anchor="middle" x="1489" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="1572.5,-685.5 1572.5,-915.5 "/>
<text text-anchor="middle" x="1583" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1593.5,-685.5 1593.5,-915.5 "/>
<text text-anchor="middle" x="1677" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1593.5,-892.5 1760.5,-892.5 "/>
<text text-anchor="middle" x="1677" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1593.5,-869.5 1760.5,-869.5 "/>
<text text-anchor="middle" x="1677" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1593.5,-846.5 1760.5,-846.5 "/>
<text text-anchor="middle" x="1677" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1593.5,-823.5 1760.5,-823.5 "/>
<text text-anchor="middle" x="1677" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1593.5,-800.5 1760.5,-800.5 "/>
<text text-anchor="middle" x="1677" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1593.5,-777.5 1760.5,-777.5 "/>
<text text-anchor="middle" x="1677" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1593.5,-754.5 1760.5,-754.5 "/>
<text text-anchor="middle" x="1677" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1593.5,-731.5 1760.5,-731.5 "/>
<text text-anchor="middle" x="1677" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1593.5,-708.5 1760.5,-708.5 "/>
<text text-anchor="middle" x="1677" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1760.5,-685.5 1760.5,-915.5 "/>
<text text-anchor="middle" x="1771" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1474.5369,-685.3916C1450.0078,-667.0943 1423.1658,-650.453 1395.5,-639 1322.032,-608.5859 1292.4802,-647.4677 1217.5,-621 1205.9919,-616.9377 1205.4623,-611.3634 1194.5,-606 1178.7531,-598.2956 1161.8508,-591.0992 1144.88,-584.5144"/>
<polygon fill="#000000" stroke="#000000" points="1146.0424,-581.2119 1135.4516,-580.9198 1143.5487,-587.7527 1146.0424,-581.2119"/>
<text text-anchor="middle" x="1347" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge7" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1594.8329,-685.4987C1595.5185,-536.5463 1592.7014,-291.9724 1567.5,-259 1533.9452,-215.0984 1416.5563,-176.6916 1306.5169,-149.0913"/>
<polygon fill="#000000" stroke="#000000" points="1307.125,-145.636 1296.5761,-146.6219 1305.4374,-152.4296 1307.125,-145.636"/>
<text text-anchor="middle" x="1678.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- study_personnel -->
<g id="node13" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M1627,-294C1627,-294 1934,-294 1934,-294 1940,-294 1946,-300 1946,-306 1946,-306 1946,-397 1946,-397 1946,-403 1940,-409 1934,-409 1934,-409 1627,-409 1627,-409 1621,-409 1615,-403 1615,-397 1615,-397 1615,-306 1615,-306 1615,-300 1621,-294 1627,-294"/>
<text text-anchor="middle" x="1682" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="1749,-294 1749,-409 "/>
<text text-anchor="middle" x="1759.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1770,-294 1770,-409 "/>
<text text-anchor="middle" x="1847.5" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="1770,-386 1925,-386 "/>
<text text-anchor="middle" x="1847.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="1770,-363 1925,-363 "/>
<text text-anchor="middle" x="1847.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="1770,-340 1925,-340 "/>
<text text-anchor="middle" x="1847.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="1770,-317 1925,-317 "/>
<text text-anchor="middle" x="1847.5" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="1925,-294 1925,-409 "/>
<text text-anchor="middle" x="1935.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge4" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1711.0939,-293.9404C1679.1015,-269.8989 1639.6047,-243.5387 1600.5,-226 1508.0663,-184.543 1399.6501,-156.0944 1306.5196,-137.1702"/>
<polygon fill="#000000" stroke="#000000" points="1307.1843,-133.7339 1296.6909,-135.1967 1305.8062,-140.5969 1307.1843,-133.7339"/>
<text text-anchor="middle" x="1696" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge6" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M914.4503,-316.7713C931.141,-291.0564 955.1419,-255.5137 978.5,-226 981.2739,-222.4951 984.1222,-218.964 987.0255,-215.423"/>
<polygon fill="#000000" stroke="#000000" points="989.7727,-217.5933 993.4619,-207.6614 984.3843,-213.1249 989.7727,-217.5933"/>
<text text-anchor="middle" x="1027" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- sequencing_file -->
<g id="node15" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M2194,-1013.5C2194,-1013.5 2663,-1013.5 2663,-1013.5 2669,-1013.5 2675,-1019.5 2675,-1025.5 2675,-1025.5 2675,-1553.5 2675,-1553.5 2675,-1559.5 2669,-1565.5 2663,-1565.5 2663,-1565.5 2194,-1565.5 2194,-1565.5 2188,-1565.5 2182,-1559.5 2182,-1553.5 2182,-1553.5 2182,-1025.5 2182,-1025.5 2182,-1019.5 2188,-1013.5 2194,-1013.5"/>
<text text-anchor="middle" x="2246" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="2310,-1013.5 2310,-1565.5 "/>
<text text-anchor="middle" x="2320.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2331,-1013.5 2331,-1565.5 "/>
<text text-anchor="middle" x="2492.5" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="2331,-1542.5 2654,-1542.5 "/>
<text text-anchor="middle" x="2492.5" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2331,-1519.5 2654,-1519.5 "/>
<text text-anchor="middle" x="2492.5" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2331,-1496.5 2654,-1496.5 "/>
<text text-anchor="middle" x="2492.5" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="2331,-1473.5 2654,-1473.5 "/>
<text text-anchor="middle" x="2492.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="2331,-1450.5 2654,-1450.5 "/>
<text text-anchor="middle" x="2492.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2331,-1427.5 2654,-1427.5 "/>
<text text-anchor="middle" x="2492.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2331,-1404.5 2654,-1404.5 "/>
<text text-anchor="middle" x="2492.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2331,-1381.5 2654,-1381.5 "/>
<text text-anchor="middle" x="2492.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2331,-1358.5 2654,-1358.5 "/>
<text text-anchor="middle" x="2492.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2331,-1335.5 2654,-1335.5 "/>
<text text-anchor="middle" x="2492.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2331,-1312.5 2654,-1312.5 "/>
<text text-anchor="middle" x="2492.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2331,-1289.5 2654,-1289.5 "/>
<text text-anchor="middle" x="2492.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="2331,-1266.5 2654,-1266.5 "/>
<text text-anchor="middle" x="2492.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="2331,-1243.5 2654,-1243.5 "/>
<text text-anchor="middle" x="2492.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="2331,-1220.5 2654,-1220.5 "/>
<text text-anchor="middle" x="2492.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="2331,-1197.5 2654,-1197.5 "/>
<text text-anchor="middle" x="2492.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="2331,-1174.5 2654,-1174.5 "/>
<text text-anchor="middle" x="2492.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="2331,-1151.5 2654,-1151.5 "/>
<text text-anchor="middle" x="2492.5" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2331,-1128.5 2654,-1128.5 "/>
<text text-anchor="middle" x="2492.5" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="2331,-1105.5 2654,-1105.5 "/>
<text text-anchor="middle" x="2492.5" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="2331,-1082.5 2654,-1082.5 "/>
<text text-anchor="middle" x="2492.5" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="2331,-1059.5 2654,-1059.5 "/>
<text text-anchor="middle" x="2492.5" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="2331,-1036.5 2654,-1036.5 "/>
<text text-anchor="middle" x="2492.5" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="2654,-1013.5 2654,-1565.5 "/>
<text text-anchor="middle" x="2664.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2187.0336,-1013.3629C2176.4545,-1002.0228 2165.9129,-990.861 2155.5,-980 2152.0791,-976.4318 2148.6074,-972.8394 2145.0957,-969.2314"/>
<polygon fill="#000000" stroke="#000000" points="2147.3286,-966.5088 2137.8346,-961.8062 2142.3239,-971.4029 2147.3286,-966.5088"/>
<text text-anchor="middle" x="2229" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
</g>
</svg>
</div>
