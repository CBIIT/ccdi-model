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
<svg width="2645pt" height="1528pt"
 viewBox="0.00 0.00 2644.50 1528.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1524)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1524 2640.5,-1524 2640.5,4 -4,4"/>
<!-- sample -->
<g id="node1" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M607.5,-639.5C607.5,-639.5 921.5,-639.5 921.5,-639.5 927.5,-639.5 933.5,-645.5 933.5,-651.5 933.5,-651.5 933.5,-903.5 933.5,-903.5 933.5,-909.5 927.5,-915.5 921.5,-915.5 921.5,-915.5 607.5,-915.5 607.5,-915.5 601.5,-915.5 595.5,-909.5 595.5,-903.5 595.5,-903.5 595.5,-651.5 595.5,-651.5 595.5,-645.5 601.5,-639.5 607.5,-639.5"/>
<text text-anchor="middle" x="629.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="663.5,-639.5 663.5,-915.5 "/>
<text text-anchor="middle" x="674" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="684.5,-639.5 684.5,-915.5 "/>
<text text-anchor="middle" x="798.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="684.5,-892.5 912.5,-892.5 "/>
<text text-anchor="middle" x="798.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="684.5,-869.5 912.5,-869.5 "/>
<text text-anchor="middle" x="798.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="684.5,-846.5 912.5,-846.5 "/>
<text text-anchor="middle" x="798.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="684.5,-823.5 912.5,-823.5 "/>
<text text-anchor="middle" x="798.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="684.5,-800.5 912.5,-800.5 "/>
<text text-anchor="middle" x="798.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="684.5,-777.5 912.5,-777.5 "/>
<text text-anchor="middle" x="798.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="684.5,-754.5 912.5,-754.5 "/>
<text text-anchor="middle" x="798.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="684.5,-731.5 912.5,-731.5 "/>
<text text-anchor="middle" x="798.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="684.5,-708.5 912.5,-708.5 "/>
<text text-anchor="middle" x="798.5" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="684.5,-685.5 912.5,-685.5 "/>
<text text-anchor="middle" x="798.5" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="684.5,-662.5 912.5,-662.5 "/>
<text text-anchor="middle" x="798.5" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="912.5,-639.5 912.5,-915.5 "/>
<text text-anchor="middle" x="923" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node5" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M1495.5,-.5C1495.5,-.5 1885.5,-.5 1885.5,-.5 1891.5,-.5 1897.5,-6.5 1897.5,-12.5 1897.5,-12.5 1897.5,-195.5 1897.5,-195.5 1897.5,-201.5 1891.5,-207.5 1885.5,-207.5 1885.5,-207.5 1495.5,-207.5 1495.5,-207.5 1489.5,-207.5 1483.5,-201.5 1483.5,-195.5 1483.5,-195.5 1483.5,-12.5 1483.5,-12.5 1483.5,-6.5 1489.5,-.5 1495.5,-.5"/>
<text text-anchor="middle" x="1511.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="1539.5,-.5 1539.5,-207.5 "/>
<text text-anchor="middle" x="1550" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1560.5,-.5 1560.5,-207.5 "/>
<text text-anchor="middle" x="1718.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="1560.5,-184.5 1876.5,-184.5 "/>
<text text-anchor="middle" x="1718.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="1560.5,-161.5 1876.5,-161.5 "/>
<text text-anchor="middle" x="1718.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="1560.5,-138.5 1876.5,-138.5 "/>
<text text-anchor="middle" x="1718.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="1560.5,-115.5 1876.5,-115.5 "/>
<text text-anchor="middle" x="1718.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="1560.5,-92.5 1876.5,-92.5 "/>
<text text-anchor="middle" x="1718.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="1560.5,-69.5 1876.5,-69.5 "/>
<text text-anchor="middle" x="1718.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="1560.5,-46.5 1876.5,-46.5 "/>
<text text-anchor="middle" x="1718.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="1560.5,-23.5 1876.5,-23.5 "/>
<text text-anchor="middle" x="1718.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="1876.5,-.5 1876.5,-207.5 "/>
<text text-anchor="middle" x="1887" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge2" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M635.2721,-639.2182C545.667,-526.3692 458.1128,-368.273 553.5,-259 612.9763,-190.8655 1160.169,-141.4019 1473.24,-118.4038"/>
<polygon fill="#000000" stroke="#000000" points="1473.637,-121.8842 1483.355,-117.664 1473.1263,-114.9029 1473.637,-121.8842"/>
<text text-anchor="middle" x="572" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- participant -->
<g id="node11" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M1378,-495.5C1378,-495.5 1609,-495.5 1609,-495.5 1615,-495.5 1621,-501.5 1621,-507.5 1621,-507.5 1621,-575.5 1621,-575.5 1621,-581.5 1615,-587.5 1609,-587.5 1609,-587.5 1378,-587.5 1378,-587.5 1372,-587.5 1366,-581.5 1366,-575.5 1366,-575.5 1366,-507.5 1366,-507.5 1366,-501.5 1372,-495.5 1378,-495.5"/>
<text text-anchor="middle" x="1414" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1462,-495.5 1462,-587.5 "/>
<text text-anchor="middle" x="1472.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1483,-495.5 1483,-587.5 "/>
<text text-anchor="middle" x="1541.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="1483,-564.5 1600,-564.5 "/>
<text text-anchor="middle" x="1541.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="1483,-541.5 1600,-541.5 "/>
<text text-anchor="middle" x="1541.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1483,-518.5 1600,-518.5 "/>
<text text-anchor="middle" x="1541.5" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1600,-495.5 1600,-587.5 "/>
<text text-anchor="middle" x="1610.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M933.7186,-676.5742C960.8419,-662.7262 989.0333,-649.6361 1016.5,-639 1126.5991,-596.3655 1258.5607,-571.2294 1355.749,-557.1892"/>
<polygon fill="#000000" stroke="#000000" points="1356.5269,-560.6138 1365.9341,-555.7399 1355.5407,-553.6836 1356.5269,-560.6138"/>
<text text-anchor="middle" x="1141" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_personnel -->
<g id="node2" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M575,-294C575,-294 882,-294 882,-294 888,-294 894,-300 894,-306 894,-306 894,-397 894,-397 894,-403 888,-409 882,-409 882,-409 575,-409 575,-409 569,-409 563,-403 563,-397 563,-397 563,-306 563,-306 563,-300 569,-294 575,-294"/>
<text text-anchor="middle" x="630" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="697,-294 697,-409 "/>
<text text-anchor="middle" x="707.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="718,-294 718,-409 "/>
<text text-anchor="middle" x="795.5" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="718,-386 873,-386 "/>
<text text-anchor="middle" x="795.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="718,-363 873,-363 "/>
<text text-anchor="middle" x="795.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="718,-340 873,-340 "/>
<text text-anchor="middle" x="795.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="718,-317 873,-317 "/>
<text text-anchor="middle" x="795.5" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="873,-294 873,-409 "/>
<text text-anchor="middle" x="883.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge12" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M825.243,-293.9478C850.1067,-280.9645 877.2611,-268.2921 903.5,-259 1090.2574,-192.863 1312.5037,-152.3644 1473.1124,-129.434"/>
<polygon fill="#000000" stroke="#000000" points="1473.7082,-132.8846 1483.1185,-128.0167 1472.7264,-125.9538 1473.7082,-132.8846"/>
<text text-anchor="middle" x="1055" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- study_funding -->
<g id="node3" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M924,-317C924,-317 1303,-317 1303,-317 1309,-317 1315,-323 1315,-329 1315,-329 1315,-374 1315,-374 1315,-380 1309,-386 1303,-386 1303,-386 924,-386 924,-386 918,-386 912,-380 912,-374 912,-374 912,-329 912,-329 912,-323 918,-317 924,-317"/>
<text text-anchor="middle" x="971.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="1031,-317 1031,-386 "/>
<text text-anchor="middle" x="1041.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1052,-317 1052,-386 "/>
<text text-anchor="middle" x="1173" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="1052,-363 1294,-363 "/>
<text text-anchor="middle" x="1173" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="1052,-340 1294,-340 "/>
<text text-anchor="middle" x="1173" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="1294,-317 1294,-386 "/>
<text text-anchor="middle" x="1304.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge13" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1192.0547,-316.783C1231.7135,-299.3271 1280.6052,-277.9153 1324.5,-259 1372.7229,-238.2196 1424.6161,-216.0978 1473.7366,-195.2682"/>
<polygon fill="#000000" stroke="#000000" points="1475.3568,-198.3829 1483.1977,-191.2576 1472.6247,-191.9381 1475.3568,-198.3829"/>
<text text-anchor="middle" x="1455.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- sequencing_file -->
<g id="node4" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M12,-967.5C12,-967.5 481,-967.5 481,-967.5 487,-967.5 493,-973.5 493,-979.5 493,-979.5 493,-1507.5 493,-1507.5 493,-1513.5 487,-1519.5 481,-1519.5 481,-1519.5 12,-1519.5 12,-1519.5 6,-1519.5 0,-1513.5 0,-1507.5 0,-1507.5 0,-979.5 0,-979.5 0,-973.5 6,-967.5 12,-967.5"/>
<text text-anchor="middle" x="64" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="128,-967.5 128,-1519.5 "/>
<text text-anchor="middle" x="138.5" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="149,-967.5 149,-1519.5 "/>
<text text-anchor="middle" x="310.5" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="149,-1496.5 472,-1496.5 "/>
<text text-anchor="middle" x="310.5" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="149,-1473.5 472,-1473.5 "/>
<text text-anchor="middle" x="310.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="149,-1450.5 472,-1450.5 "/>
<text text-anchor="middle" x="310.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="149,-1427.5 472,-1427.5 "/>
<text text-anchor="middle" x="310.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="149,-1404.5 472,-1404.5 "/>
<text text-anchor="middle" x="310.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="149,-1381.5 472,-1381.5 "/>
<text text-anchor="middle" x="310.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="149,-1358.5 472,-1358.5 "/>
<text text-anchor="middle" x="310.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="149,-1335.5 472,-1335.5 "/>
<text text-anchor="middle" x="310.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="149,-1312.5 472,-1312.5 "/>
<text text-anchor="middle" x="310.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="149,-1289.5 472,-1289.5 "/>
<text text-anchor="middle" x="310.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="149,-1266.5 472,-1266.5 "/>
<text text-anchor="middle" x="310.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="149,-1243.5 472,-1243.5 "/>
<text text-anchor="middle" x="310.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="149,-1220.5 472,-1220.5 "/>
<text text-anchor="middle" x="310.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="149,-1197.5 472,-1197.5 "/>
<text text-anchor="middle" x="310.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="149,-1174.5 472,-1174.5 "/>
<text text-anchor="middle" x="310.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="149,-1151.5 472,-1151.5 "/>
<text text-anchor="middle" x="310.5" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="149,-1128.5 472,-1128.5 "/>
<text text-anchor="middle" x="310.5" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="149,-1105.5 472,-1105.5 "/>
<text text-anchor="middle" x="310.5" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="149,-1082.5 472,-1082.5 "/>
<text text-anchor="middle" x="310.5" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="149,-1059.5 472,-1059.5 "/>
<text text-anchor="middle" x="310.5" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="149,-1036.5 472,-1036.5 "/>
<text text-anchor="middle" x="310.5" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="149,-1013.5 472,-1013.5 "/>
<text text-anchor="middle" x="310.5" y="-998.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="149,-990.5 472,-990.5 "/>
<text text-anchor="middle" x="310.5" y="-975.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="472,-967.5 472,-1519.5 "/>
<text text-anchor="middle" x="482.5" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M493.3116,-975.2284C496.3762,-972.4553 499.4397,-969.7114 502.5,-967 528.9045,-943.6055 558.1333,-920.2776 587.2088,-898.3934"/>
<polygon fill="#000000" stroke="#000000" points="589.4943,-901.0545 595.403,-892.2603 585.2998,-895.4504 589.4943,-901.0545"/>
<text text-anchor="middle" x="603" y="-937.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- therapeutic_procedure -->
<g id="node6" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M1037,-720C1037,-720 1394,-720 1394,-720 1400,-720 1406,-726 1406,-732 1406,-732 1406,-823 1406,-823 1406,-829 1400,-835 1394,-835 1394,-835 1037,-835 1037,-835 1031,-835 1025,-829 1025,-823 1025,-823 1025,-732 1025,-732 1025,-726 1031,-720 1037,-720"/>
<text text-anchor="middle" x="1115.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="1206,-720 1206,-835 "/>
<text text-anchor="middle" x="1216.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1227,-720 1227,-835 "/>
<text text-anchor="middle" x="1306" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="1227,-812 1385,-812 "/>
<text text-anchor="middle" x="1306" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="1227,-789 1385,-789 "/>
<text text-anchor="middle" x="1306" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1227,-766 1385,-766 "/>
<text text-anchor="middle" x="1306" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="1227,-743 1385,-743 "/>
<text text-anchor="middle" x="1306" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1385,-720 1385,-835 "/>
<text text-anchor="middle" x="1395.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1209.172,-719.7998C1208.4045,-682.8764 1214.0253,-636.3729 1241.5,-606 1258.0086,-587.75 1306.133,-573.349 1355.9623,-562.8273"/>
<polygon fill="#000000" stroke="#000000" points="1356.8522,-566.2176 1365.942,-560.7747 1355.4419,-559.3612 1356.8522,-566.2176"/>
<text text-anchor="middle" x="1334.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- study_arm -->
<g id="node7" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M1345,-317C1345,-317 1642,-317 1642,-317 1648,-317 1654,-323 1654,-329 1654,-329 1654,-374 1654,-374 1654,-380 1648,-386 1642,-386 1642,-386 1345,-386 1345,-386 1339,-386 1333,-380 1333,-374 1333,-374 1333,-329 1333,-329 1333,-323 1339,-317 1345,-317"/>
<text text-anchor="middle" x="1379" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="1425,-317 1425,-386 "/>
<text text-anchor="middle" x="1435.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1446,-317 1446,-386 "/>
<text text-anchor="middle" x="1539.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="1446,-363 1633,-363 "/>
<text text-anchor="middle" x="1539.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="1446,-340 1633,-340 "/>
<text text-anchor="middle" x="1539.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="1633,-317 1633,-386 "/>
<text text-anchor="middle" x="1643.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1515.4503,-316.7713C1532.141,-291.0564 1556.1419,-255.5137 1579.5,-226 1582.2739,-222.4951 1585.1222,-218.964 1588.0255,-215.423"/>
<polygon fill="#000000" stroke="#000000" points="1590.7727,-217.5933 1594.4619,-207.6614 1585.3843,-213.1249 1590.7727,-217.5933"/>
<text text-anchor="middle" x="1628" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- synonym -->
<g id="node8" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M1309,-1220.5C1309,-1220.5 1610,-1220.5 1610,-1220.5 1616,-1220.5 1622,-1226.5 1622,-1232.5 1622,-1232.5 1622,-1254.5 1622,-1254.5 1622,-1260.5 1616,-1266.5 1610,-1266.5 1610,-1266.5 1309,-1266.5 1309,-1266.5 1303,-1266.5 1297,-1260.5 1297,-1254.5 1297,-1254.5 1297,-1232.5 1297,-1232.5 1297,-1226.5 1303,-1220.5 1309,-1220.5"/>
<text text-anchor="middle" x="1337" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="1377,-1220.5 1377,-1266.5 "/>
<text text-anchor="middle" x="1387.5" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1398,-1220.5 1398,-1266.5 "/>
<text text-anchor="middle" x="1499.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="1398,-1243.5 1601,-1243.5 "/>
<text text-anchor="middle" x="1499.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="1601,-1220.5 1601,-1266.5 "/>
<text text-anchor="middle" x="1611.5" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1452.435,-1220.3894C1434.6349,-1166.3582 1382.5254,-1031.4832 1288.5,-967 1187.0664,-897.4362 1132.292,-957.4743 1016.5,-916 992.0163,-907.2304 967.0618,-896.2947 942.8421,-884.4375"/>
<polygon fill="#000000" stroke="#000000" points="944.1117,-881.1603 933.5981,-879.8506 941.0002,-887.4308 944.1117,-881.1603"/>
<text text-anchor="middle" x="1296" y="-937.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge6" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1560.3908,-1220.4401C1772.2801,-1169.9195 2252.5455,-1043.745 2355.5,-916 2394.4885,-867.6234 2374.5,-839.6321 2374.5,-777.5 2374.5,-777.5 2374.5,-777.5 2374.5,-351.5 2374.5,-250.5969 2107.9726,-179.226 1907.6652,-139.8355"/>
<polygon fill="#000000" stroke="#000000" points="1908.0639,-136.3474 1897.5788,-137.8679 1906.7236,-143.2179 1908.0639,-136.3474"/>
<text text-anchor="middle" x="2417" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1455.6655,-1220.3811C1442.9724,-1139.3809 1405.6579,-861.2921 1451.5,-639 1454.3757,-625.0556 1459.3403,-610.6488 1464.8712,-597.3283"/>
<polygon fill="#000000" stroke="#000000" points="1468.2165,-598.4106 1468.9769,-587.8431 1461.7925,-595.6299 1468.2165,-598.4106"/>
<text text-anchor="middle" x="1494" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study_admin -->
<g id="node9" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M1821.5,-259.5C1821.5,-259.5 2147.5,-259.5 2147.5,-259.5 2153.5,-259.5 2159.5,-265.5 2159.5,-271.5 2159.5,-271.5 2159.5,-431.5 2159.5,-431.5 2159.5,-437.5 2153.5,-443.5 2147.5,-443.5 2147.5,-443.5 1821.5,-443.5 1821.5,-443.5 1815.5,-443.5 1809.5,-437.5 1809.5,-431.5 1809.5,-431.5 1809.5,-271.5 1809.5,-271.5 1809.5,-265.5 1815.5,-259.5 1821.5,-259.5"/>
<text text-anchor="middle" x="1863.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="1917.5,-259.5 1917.5,-443.5 "/>
<text text-anchor="middle" x="1928" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1938.5,-259.5 1938.5,-443.5 "/>
<text text-anchor="middle" x="2038.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="1938.5,-420.5 2138.5,-420.5 "/>
<text text-anchor="middle" x="2038.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="1938.5,-397.5 2138.5,-397.5 "/>
<text text-anchor="middle" x="2038.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="1938.5,-374.5 2138.5,-374.5 "/>
<text text-anchor="middle" x="2038.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="1938.5,-351.5 2138.5,-351.5 "/>
<text text-anchor="middle" x="2038.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="1938.5,-328.5 2138.5,-328.5 "/>
<text text-anchor="middle" x="2038.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="1938.5,-305.5 2138.5,-305.5 "/>
<text text-anchor="middle" x="2038.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="1938.5,-282.5 2138.5,-282.5 "/>
<text text-anchor="middle" x="2038.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="2138.5,-259.5 2138.5,-443.5 "/>
<text text-anchor="middle" x="2149" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge4" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1875.0253,-259.3401C1857.753,-244.7997 1839.74,-229.6357 1822.0299,-214.7267"/>
<polygon fill="#000000" stroke="#000000" points="1823.8221,-211.6604 1813.9179,-207.8977 1819.314,-217.0155 1823.8221,-211.6604"/>
<text text-anchor="middle" x="1902" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- diagnosis -->
<g id="node10" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1557,-639.5C1557,-639.5 1940,-639.5 1940,-639.5 1946,-639.5 1952,-645.5 1952,-651.5 1952,-651.5 1952,-903.5 1952,-903.5 1952,-909.5 1946,-915.5 1940,-915.5 1940,-915.5 1557,-915.5 1557,-915.5 1551,-915.5 1545,-909.5 1545,-903.5 1545,-903.5 1545,-651.5 1545,-651.5 1545,-645.5 1551,-639.5 1557,-639.5"/>
<text text-anchor="middle" x="1587" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1629,-639.5 1629,-915.5 "/>
<text text-anchor="middle" x="1639.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1650,-639.5 1650,-915.5 "/>
<text text-anchor="middle" x="1790.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1650,-892.5 1931,-892.5 "/>
<text text-anchor="middle" x="1790.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1650,-869.5 1931,-869.5 "/>
<text text-anchor="middle" x="1790.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1650,-846.5 1931,-846.5 "/>
<text text-anchor="middle" x="1790.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1650,-823.5 1931,-823.5 "/>
<text text-anchor="middle" x="1790.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1650,-800.5 1931,-800.5 "/>
<text text-anchor="middle" x="1790.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="1650,-777.5 1931,-777.5 "/>
<text text-anchor="middle" x="1790.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1650,-754.5 1931,-754.5 "/>
<text text-anchor="middle" x="1790.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1650,-731.5 1931,-731.5 "/>
<text text-anchor="middle" x="1790.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis_reference_source</text>
<polyline fill="none" stroke="#000000" points="1650,-708.5 1931,-708.5 "/>
<text text-anchor="middle" x="1790.5" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="1650,-685.5 1931,-685.5 "/>
<text text-anchor="middle" x="1790.5" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="1650,-662.5 1931,-662.5 "/>
<text text-anchor="middle" x="1790.5" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="1931,-639.5 1931,-915.5 "/>
<text text-anchor="middle" x="1941.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1599.059,-639.1938C1582.0269,-623.4308 1565.5334,-608.1662 1550.844,-594.5713"/>
<polygon fill="#000000" stroke="#000000" points="1553.0501,-591.8441 1543.3335,-587.6204 1548.2954,-596.9816 1553.0501,-591.8441"/>
<text text-anchor="middle" x="1620" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge18" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1609.5383,-495.4279C1630.6746,-481.9254 1650.209,-464.9817 1663.5,-444 1686.6793,-407.4082 1692.1832,-301.5942 1692.6441,-217.6295"/>
<polygon fill="#000000" stroke="#000000" points="1696.1444,-217.5153 1692.6762,-207.5043 1689.1444,-217.4931 1696.1444,-217.5153"/>
<text text-anchor="middle" x="1742" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge19" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1493.5,-495.0208C1493.5,-464.9487 1493.5,-426.0098 1493.5,-396.2801"/>
<polygon fill="#000000" stroke="#000000" points="1497.0001,-396.178 1493.5,-386.178 1490.0001,-396.178 1497.0001,-396.178"/>
<text text-anchor="middle" x="1544" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- imaging_file -->
<g id="node12" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M523.5,-1082.5C523.5,-1082.5 857.5,-1082.5 857.5,-1082.5 863.5,-1082.5 869.5,-1088.5 869.5,-1094.5 869.5,-1094.5 869.5,-1392.5 869.5,-1392.5 869.5,-1398.5 863.5,-1404.5 857.5,-1404.5 857.5,-1404.5 523.5,-1404.5 523.5,-1404.5 517.5,-1404.5 511.5,-1398.5 511.5,-1392.5 511.5,-1392.5 511.5,-1094.5 511.5,-1094.5 511.5,-1088.5 517.5,-1082.5 523.5,-1082.5"/>
<text text-anchor="middle" x="563.5" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="615.5,-1082.5 615.5,-1404.5 "/>
<text text-anchor="middle" x="626" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="636.5,-1082.5 636.5,-1404.5 "/>
<text text-anchor="middle" x="742.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="636.5,-1381.5 848.5,-1381.5 "/>
<text text-anchor="middle" x="742.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="636.5,-1358.5 848.5,-1358.5 "/>
<text text-anchor="middle" x="742.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="636.5,-1335.5 848.5,-1335.5 "/>
<text text-anchor="middle" x="742.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="636.5,-1312.5 848.5,-1312.5 "/>
<text text-anchor="middle" x="742.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="636.5,-1289.5 848.5,-1289.5 "/>
<text text-anchor="middle" x="742.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="636.5,-1266.5 848.5,-1266.5 "/>
<text text-anchor="middle" x="742.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="636.5,-1243.5 848.5,-1243.5 "/>
<text text-anchor="middle" x="742.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="636.5,-1220.5 848.5,-1220.5 "/>
<text text-anchor="middle" x="742.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="636.5,-1197.5 848.5,-1197.5 "/>
<text text-anchor="middle" x="742.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="636.5,-1174.5 848.5,-1174.5 "/>
<text text-anchor="middle" x="742.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="636.5,-1151.5 848.5,-1151.5 "/>
<text text-anchor="middle" x="742.5" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="636.5,-1128.5 848.5,-1128.5 "/>
<text text-anchor="middle" x="742.5" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="636.5,-1105.5 848.5,-1105.5 "/>
<text text-anchor="middle" x="742.5" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="848.5,-1082.5 848.5,-1404.5 "/>
<text text-anchor="middle" x="859" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M716.0702,-1082.4767C724.1578,-1031.5467 733.0533,-975.529 740.9895,-925.5524"/>
<polygon fill="#000000" stroke="#000000" points="744.4517,-926.0661 742.5635,-915.6409 737.5384,-924.9682 744.4517,-926.0661"/>
<text text-anchor="middle" x="793" y="-937.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node13" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M1982.5,-651C1982.5,-651 2334.5,-651 2334.5,-651 2340.5,-651 2346.5,-657 2346.5,-663 2346.5,-663 2346.5,-892 2346.5,-892 2346.5,-898 2340.5,-904 2334.5,-904 2334.5,-904 1982.5,-904 1982.5,-904 1976.5,-904 1970.5,-898 1970.5,-892 1970.5,-892 1970.5,-663 1970.5,-663 1970.5,-657 1976.5,-651 1982.5,-651"/>
<text text-anchor="middle" x="2054" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="2137.5,-651 2137.5,-904 "/>
<text text-anchor="middle" x="2148" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2158.5,-651 2158.5,-904 "/>
<text text-anchor="middle" x="2242" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2158.5,-881 2325.5,-881 "/>
<text text-anchor="middle" x="2242" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2158.5,-858 2325.5,-858 "/>
<text text-anchor="middle" x="2242" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2158.5,-835 2325.5,-835 "/>
<text text-anchor="middle" x="2242" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2158.5,-812 2325.5,-812 "/>
<text text-anchor="middle" x="2242" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2158.5,-789 2325.5,-789 "/>
<text text-anchor="middle" x="2242" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2158.5,-766 2325.5,-766 "/>
<text text-anchor="middle" x="2242" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2158.5,-743 2325.5,-743 "/>
<text text-anchor="middle" x="2242" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2158.5,-720 2325.5,-720 "/>
<text text-anchor="middle" x="2242" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2158.5,-697 2325.5,-697 "/>
<text text-anchor="middle" x="2242" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2158.5,-674 2325.5,-674 "/>
<text text-anchor="middle" x="2242" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="2325.5,-651 2325.5,-904 "/>
<text text-anchor="middle" x="2336" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge14" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2168.8144,-650.7993C2179.2595,-507.4791 2190.9508,-289.8817 2168.5,-259 2135.9457,-214.2206 2018.1799,-175.744 1907.6966,-148.3273"/>
<polygon fill="#000000" stroke="#000000" points="1908.2618,-144.8622 1897.7156,-145.8753 1906.5918,-151.6601 1908.2618,-144.8622"/>
<text text-anchor="middle" x="2264.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1986.4809,-650.9148C1978.1902,-646.6191 1969.8429,-642.617 1961.5,-639 1903.1867,-613.7189 1747.1311,-583.7888 1631.1616,-563.8217"/>
<polygon fill="#000000" stroke="#000000" points="1631.5747,-560.3416 1621.1271,-562.1016 1630.392,-567.2409 1631.5747,-560.3416"/>
<text text-anchor="middle" x="2035" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- methylation_array_file -->
<g id="node14" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M900,-1128.5C900,-1128.5 1267,-1128.5 1267,-1128.5 1273,-1128.5 1279,-1134.5 1279,-1140.5 1279,-1140.5 1279,-1346.5 1279,-1346.5 1279,-1352.5 1273,-1358.5 1267,-1358.5 1267,-1358.5 900,-1358.5 900,-1358.5 894,-1358.5 888,-1352.5 888,-1346.5 888,-1346.5 888,-1140.5 888,-1140.5 888,-1134.5 894,-1128.5 900,-1128.5"/>
<text text-anchor="middle" x="977" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="1066,-1128.5 1066,-1358.5 "/>
<text text-anchor="middle" x="1076.5" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1087,-1128.5 1087,-1358.5 "/>
<text text-anchor="middle" x="1172.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1087,-1335.5 1258,-1335.5 "/>
<text text-anchor="middle" x="1172.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1087,-1312.5 1258,-1312.5 "/>
<text text-anchor="middle" x="1172.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1087,-1289.5 1258,-1289.5 "/>
<text text-anchor="middle" x="1172.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1087,-1266.5 1258,-1266.5 "/>
<text text-anchor="middle" x="1172.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1087,-1243.5 1258,-1243.5 "/>
<text text-anchor="middle" x="1172.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1087,-1220.5 1258,-1220.5 "/>
<text text-anchor="middle" x="1172.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1087,-1197.5 1258,-1197.5 "/>
<text text-anchor="middle" x="1172.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1087,-1174.5 1258,-1174.5 "/>
<text text-anchor="middle" x="1172.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="1087,-1151.5 1258,-1151.5 "/>
<text text-anchor="middle" x="1172.5" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="1258,-1128.5 1258,-1358.5 "/>
<text text-anchor="middle" x="1268.5" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1004.646,-1128.309C962.4472,-1066.6642 910.0279,-990.0894 864.9404,-924.2249"/>
<polygon fill="#000000" stroke="#000000" points="867.7338,-922.1094 859.1969,-915.8347 861.9576,-926.0635 867.7338,-922.1094"/>
<text text-anchor="middle" x="968" y="-937.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- publication -->
<g id="node15" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M2414.5,-333.5C2414.5,-333.5 2624.5,-333.5 2624.5,-333.5 2630.5,-333.5 2636.5,-339.5 2636.5,-345.5 2636.5,-345.5 2636.5,-357.5 2636.5,-357.5 2636.5,-363.5 2630.5,-369.5 2624.5,-369.5 2624.5,-369.5 2414.5,-369.5 2414.5,-369.5 2408.5,-369.5 2402.5,-363.5 2402.5,-357.5 2402.5,-357.5 2402.5,-345.5 2402.5,-345.5 2402.5,-339.5 2408.5,-333.5 2414.5,-333.5"/>
<text text-anchor="middle" x="2451" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="2499.5,-333.5 2499.5,-369.5 "/>
<text text-anchor="middle" x="2510" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2520.5,-333.5 2520.5,-369.5 "/>
<text text-anchor="middle" x="2568" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="2615.5,-333.5 2615.5,-369.5 "/>
<text text-anchor="middle" x="2626" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge10" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2506.1637,-333.054C2484.7703,-304.9735 2439.9264,-252.0258 2388.5,-226 2306.1309,-184.3148 2080.4282,-149.574 1907.7695,-127.9628"/>
<polygon fill="#000000" stroke="#000000" points="1908.1314,-124.4809 1897.7757,-126.7191 1907.2668,-131.4273 1908.1314,-124.4809"/>
<text text-anchor="middle" x="2460.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
</g>
</svg>
</div>
