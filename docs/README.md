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
<svg width="3526pt" height="1574pt"
 viewBox="0.00 0.00 3525.50 1574.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1570)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1570 3521.5,-1570 3521.5,4 -4,4"/>
<!-- therapeutic_procedure -->
<g id="node1" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M854,-743C854,-743 1211,-743 1211,-743 1217,-743 1223,-749 1223,-755 1223,-755 1223,-846 1223,-846 1223,-852 1217,-858 1211,-858 1211,-858 854,-858 854,-858 848,-858 842,-852 842,-846 842,-846 842,-755 842,-755 842,-749 848,-743 854,-743"/>
<text text-anchor="middle" x="932.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="1023,-743 1023,-858 "/>
<text text-anchor="middle" x="1033.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1044,-743 1044,-858 "/>
<text text-anchor="middle" x="1123" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="1044,-835 1202,-835 "/>
<text text-anchor="middle" x="1123" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="1044,-812 1202,-812 "/>
<text text-anchor="middle" x="1123" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1044,-789 1202,-789 "/>
<text text-anchor="middle" x="1123" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="1044,-766 1202,-766 "/>
<text text-anchor="middle" x="1123" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1202,-743 1202,-858 "/>
<text text-anchor="middle" x="1212.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node9" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M1420,-495.5C1420,-495.5 1651,-495.5 1651,-495.5 1657,-495.5 1663,-501.5 1663,-507.5 1663,-507.5 1663,-575.5 1663,-575.5 1663,-581.5 1657,-587.5 1651,-587.5 1651,-587.5 1420,-587.5 1420,-587.5 1414,-587.5 1408,-581.5 1408,-575.5 1408,-575.5 1408,-507.5 1408,-507.5 1408,-501.5 1414,-495.5 1420,-495.5"/>
<text text-anchor="middle" x="1456" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1504,-495.5 1504,-587.5 "/>
<text text-anchor="middle" x="1514.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1525,-495.5 1525,-587.5 "/>
<text text-anchor="middle" x="1583.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="1525,-564.5 1642,-564.5 "/>
<text text-anchor="middle" x="1583.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="1525,-541.5 1642,-541.5 "/>
<text text-anchor="middle" x="1583.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1525,-518.5 1642,-518.5 "/>
<text text-anchor="middle" x="1583.5" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1642,-495.5 1642,-587.5 "/>
<text text-anchor="middle" x="1652.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1092.7994,-742.9949C1130.4426,-709.3614 1181.172,-667.9595 1231.5,-639 1282.7108,-609.5325 1343.9842,-587.7 1398.0604,-572.2535"/>
<polygon fill="#000000" stroke="#000000" points="1399.0386,-575.6142 1407.7193,-569.54 1397.1453,-568.8751 1399.0386,-575.6142"/>
<text text-anchor="middle" x="1386.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- sample -->
<g id="node2" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M498.5,-639.5C498.5,-639.5 812.5,-639.5 812.5,-639.5 818.5,-639.5 824.5,-645.5 824.5,-651.5 824.5,-651.5 824.5,-949.5 824.5,-949.5 824.5,-955.5 818.5,-961.5 812.5,-961.5 812.5,-961.5 498.5,-961.5 498.5,-961.5 492.5,-961.5 486.5,-955.5 486.5,-949.5 486.5,-949.5 486.5,-651.5 486.5,-651.5 486.5,-645.5 492.5,-639.5 498.5,-639.5"/>
<text text-anchor="middle" x="520.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="554.5,-639.5 554.5,-961.5 "/>
<text text-anchor="middle" x="565" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="575.5,-639.5 575.5,-961.5 "/>
<text text-anchor="middle" x="689.5" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="575.5,-938.5 803.5,-938.5 "/>
<text text-anchor="middle" x="689.5" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="575.5,-915.5 803.5,-915.5 "/>
<text text-anchor="middle" x="689.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="575.5,-892.5 803.5,-892.5 "/>
<text text-anchor="middle" x="689.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="575.5,-869.5 803.5,-869.5 "/>
<text text-anchor="middle" x="689.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="575.5,-846.5 803.5,-846.5 "/>
<text text-anchor="middle" x="689.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="575.5,-823.5 803.5,-823.5 "/>
<text text-anchor="middle" x="689.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="575.5,-800.5 803.5,-800.5 "/>
<text text-anchor="middle" x="689.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="575.5,-777.5 803.5,-777.5 "/>
<text text-anchor="middle" x="689.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="575.5,-754.5 803.5,-754.5 "/>
<text text-anchor="middle" x="689.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage</text>
<polyline fill="none" stroke="#000000" points="575.5,-731.5 803.5,-731.5 "/>
<text text-anchor="middle" x="689.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="575.5,-708.5 803.5,-708.5 "/>
<text text-anchor="middle" x="689.5" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="575.5,-685.5 803.5,-685.5 "/>
<text text-anchor="middle" x="689.5" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="575.5,-662.5 803.5,-662.5 "/>
<text text-anchor="middle" x="689.5" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_status</text>
<polyline fill="none" stroke="#000000" points="803.5,-639.5 803.5,-961.5 "/>
<text text-anchor="middle" x="814" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M824.6285,-642.8663C827.2396,-641.527 829.8639,-640.2369 832.5,-639 930.0234,-593.2395 1222.2943,-564.504 1397.7785,-550.8849"/>
<polygon fill="#000000" stroke="#000000" points="1398.1621,-554.3658 1407.864,-550.1088 1397.625,-547.3864 1398.1621,-554.3658"/>
<text text-anchor="middle" x="981" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study -->
<g id="node11" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M1921.5,-.5C1921.5,-.5 2311.5,-.5 2311.5,-.5 2317.5,-.5 2323.5,-6.5 2323.5,-12.5 2323.5,-12.5 2323.5,-195.5 2323.5,-195.5 2323.5,-201.5 2317.5,-207.5 2311.5,-207.5 2311.5,-207.5 1921.5,-207.5 1921.5,-207.5 1915.5,-207.5 1909.5,-201.5 1909.5,-195.5 1909.5,-195.5 1909.5,-12.5 1909.5,-12.5 1909.5,-6.5 1915.5,-.5 1921.5,-.5"/>
<text text-anchor="middle" x="1937.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="1965.5,-.5 1965.5,-207.5 "/>
<text text-anchor="middle" x="1976" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1986.5,-.5 1986.5,-207.5 "/>
<text text-anchor="middle" x="2144.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="1986.5,-184.5 2302.5,-184.5 "/>
<text text-anchor="middle" x="2144.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="1986.5,-161.5 2302.5,-161.5 "/>
<text text-anchor="middle" x="2144.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="1986.5,-138.5 2302.5,-138.5 "/>
<text text-anchor="middle" x="2144.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="1986.5,-115.5 2302.5,-115.5 "/>
<text text-anchor="middle" x="2144.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="1986.5,-92.5 2302.5,-92.5 "/>
<text text-anchor="middle" x="2144.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="1986.5,-69.5 2302.5,-69.5 "/>
<text text-anchor="middle" x="2144.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="1986.5,-46.5 2302.5,-46.5 "/>
<text text-anchor="middle" x="2144.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="1986.5,-23.5 2302.5,-23.5 "/>
<text text-anchor="middle" x="2144.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="2302.5,-.5 2302.5,-207.5 "/>
<text text-anchor="middle" x="2313" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge16" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M824.5732,-645.1854C827.2215,-643.0955 829.8648,-641.0324 832.5,-639 1127.6754,-411.3416 1214.0703,-358.49 1562.5,-226 1670.2938,-185.0115 1795.3865,-155.9947 1899.3994,-136.5735"/>
<polygon fill="#000000" stroke="#000000" points="1900.2015,-139.9846 1909.398,-134.7239 1898.9282,-133.1013 1900.2015,-139.9846"/>
<text text-anchor="middle" x="1106" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sequencing_file -->
<g id="node3" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M421,-1013.5C421,-1013.5 890,-1013.5 890,-1013.5 896,-1013.5 902,-1019.5 902,-1025.5 902,-1025.5 902,-1553.5 902,-1553.5 902,-1559.5 896,-1565.5 890,-1565.5 890,-1565.5 421,-1565.5 421,-1565.5 415,-1565.5 409,-1559.5 409,-1553.5 409,-1553.5 409,-1025.5 409,-1025.5 409,-1019.5 415,-1013.5 421,-1013.5"/>
<text text-anchor="middle" x="473" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="537,-1013.5 537,-1565.5 "/>
<text text-anchor="middle" x="547.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="558,-1013.5 558,-1565.5 "/>
<text text-anchor="middle" x="719.5" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="558,-1542.5 881,-1542.5 "/>
<text text-anchor="middle" x="719.5" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="558,-1519.5 881,-1519.5 "/>
<text text-anchor="middle" x="719.5" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="558,-1496.5 881,-1496.5 "/>
<text text-anchor="middle" x="719.5" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="558,-1473.5 881,-1473.5 "/>
<text text-anchor="middle" x="719.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="558,-1450.5 881,-1450.5 "/>
<text text-anchor="middle" x="719.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="558,-1427.5 881,-1427.5 "/>
<text text-anchor="middle" x="719.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="558,-1404.5 881,-1404.5 "/>
<text text-anchor="middle" x="719.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="558,-1381.5 881,-1381.5 "/>
<text text-anchor="middle" x="719.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="558,-1358.5 881,-1358.5 "/>
<text text-anchor="middle" x="719.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="558,-1335.5 881,-1335.5 "/>
<text text-anchor="middle" x="719.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="558,-1312.5 881,-1312.5 "/>
<text text-anchor="middle" x="719.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="558,-1289.5 881,-1289.5 "/>
<text text-anchor="middle" x="719.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="558,-1266.5 881,-1266.5 "/>
<text text-anchor="middle" x="719.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="558,-1243.5 881,-1243.5 "/>
<text text-anchor="middle" x="719.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="558,-1220.5 881,-1220.5 "/>
<text text-anchor="middle" x="719.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="558,-1197.5 881,-1197.5 "/>
<text text-anchor="middle" x="719.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="558,-1174.5 881,-1174.5 "/>
<text text-anchor="middle" x="719.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="558,-1151.5 881,-1151.5 "/>
<text text-anchor="middle" x="719.5" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="558,-1128.5 881,-1128.5 "/>
<text text-anchor="middle" x="719.5" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="558,-1105.5 881,-1105.5 "/>
<text text-anchor="middle" x="719.5" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="558,-1082.5 881,-1082.5 "/>
<text text-anchor="middle" x="719.5" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="558,-1059.5 881,-1059.5 "/>
<text text-anchor="middle" x="719.5" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="558,-1036.5 881,-1036.5 "/>
<text text-anchor="middle" x="719.5" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="881,-1013.5 881,-1565.5 "/>
<text text-anchor="middle" x="891.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M655.5,-1013.2045C655.5,-999.2385 655.5,-985.4133 655.5,-971.9153"/>
<polygon fill="#000000" stroke="#000000" points="659.0001,-971.6602 655.5,-961.6602 652.0001,-971.6602 659.0001,-971.6602"/>
<text text-anchor="middle" x="722" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node4" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M1799.5,-674C1799.5,-674 2151.5,-674 2151.5,-674 2157.5,-674 2163.5,-680 2163.5,-686 2163.5,-686 2163.5,-915 2163.5,-915 2163.5,-921 2157.5,-927 2151.5,-927 2151.5,-927 1799.5,-927 1799.5,-927 1793.5,-927 1787.5,-921 1787.5,-915 1787.5,-915 1787.5,-686 1787.5,-686 1787.5,-680 1793.5,-674 1799.5,-674"/>
<text text-anchor="middle" x="1871" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="1954.5,-674 1954.5,-927 "/>
<text text-anchor="middle" x="1965" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1975.5,-674 1975.5,-927 "/>
<text text-anchor="middle" x="2059" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1975.5,-904 2142.5,-904 "/>
<text text-anchor="middle" x="2059" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1975.5,-881 2142.5,-881 "/>
<text text-anchor="middle" x="2059" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1975.5,-858 2142.5,-858 "/>
<text text-anchor="middle" x="2059" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1975.5,-835 2142.5,-835 "/>
<text text-anchor="middle" x="2059" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1975.5,-812 2142.5,-812 "/>
<text text-anchor="middle" x="2059" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1975.5,-789 2142.5,-789 "/>
<text text-anchor="middle" x="2059" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1975.5,-766 2142.5,-766 "/>
<text text-anchor="middle" x="2059" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1975.5,-743 2142.5,-743 "/>
<text text-anchor="middle" x="2059" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1975.5,-720 2142.5,-720 "/>
<text text-anchor="middle" x="2059" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1975.5,-697 2142.5,-697 "/>
<text text-anchor="middle" x="2059" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="2142.5,-674 2142.5,-927 "/>
<text text-anchor="middle" x="2153" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1826.208,-673.9895C1808.8975,-661.4959 1791.1224,-649.5553 1773.5,-639 1756.0775,-628.5644 1750.0786,-629.2024 1731.5,-621 1716.7617,-614.4931 1713.3282,-612.2992 1698.5,-606 1687.2278,-601.2114 1675.4717,-596.3345 1663.6623,-591.5153"/>
<polygon fill="#000000" stroke="#000000" points="1664.7702,-588.1876 1654.1882,-587.6656 1662.135,-594.6727 1664.7702,-588.1876"/>
<text text-anchor="middle" x="1861" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge14" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1986.0847,-673.9742C1993.8563,-582.2962 2003.408,-472.6183 2005.5,-462 2021.9283,-378.6147 2050.4856,-287.1302 2074.5198,-217.5148"/>
<polygon fill="#000000" stroke="#000000" points="2077.9053,-218.4348 2077.8793,-207.84 2071.2926,-216.1386 2077.9053,-218.4348"/>
<text text-anchor="middle" x="2091.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- imaging_file -->
<g id="node5" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M932.5,-1128.5C932.5,-1128.5 1266.5,-1128.5 1266.5,-1128.5 1272.5,-1128.5 1278.5,-1134.5 1278.5,-1140.5 1278.5,-1140.5 1278.5,-1438.5 1278.5,-1438.5 1278.5,-1444.5 1272.5,-1450.5 1266.5,-1450.5 1266.5,-1450.5 932.5,-1450.5 932.5,-1450.5 926.5,-1450.5 920.5,-1444.5 920.5,-1438.5 920.5,-1438.5 920.5,-1140.5 920.5,-1140.5 920.5,-1134.5 926.5,-1128.5 932.5,-1128.5"/>
<text text-anchor="middle" x="972.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="1024.5,-1128.5 1024.5,-1450.5 "/>
<text text-anchor="middle" x="1035" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1045.5,-1128.5 1045.5,-1450.5 "/>
<text text-anchor="middle" x="1151.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1045.5,-1427.5 1257.5,-1427.5 "/>
<text text-anchor="middle" x="1151.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1045.5,-1404.5 1257.5,-1404.5 "/>
<text text-anchor="middle" x="1151.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1045.5,-1381.5 1257.5,-1381.5 "/>
<text text-anchor="middle" x="1151.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1045.5,-1358.5 1257.5,-1358.5 "/>
<text text-anchor="middle" x="1151.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1045.5,-1335.5 1257.5,-1335.5 "/>
<text text-anchor="middle" x="1151.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1045.5,-1312.5 1257.5,-1312.5 "/>
<text text-anchor="middle" x="1151.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1045.5,-1289.5 1257.5,-1289.5 "/>
<text text-anchor="middle" x="1151.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1045.5,-1266.5 1257.5,-1266.5 "/>
<text text-anchor="middle" x="1151.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1045.5,-1243.5 1257.5,-1243.5 "/>
<text text-anchor="middle" x="1151.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="1045.5,-1220.5 1257.5,-1220.5 "/>
<text text-anchor="middle" x="1151.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="1045.5,-1197.5 1257.5,-1197.5 "/>
<text text-anchor="middle" x="1151.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="1045.5,-1174.5 1257.5,-1174.5 "/>
<text text-anchor="middle" x="1151.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1045.5,-1151.5 1257.5,-1151.5 "/>
<text text-anchor="middle" x="1151.5" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="1257.5,-1128.5 1257.5,-1450.5 "/>
<text text-anchor="middle" x="1268" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1004.9467,-1128.3412C977.3468,-1088.2063 945.182,-1046.9775 910.5,-1013 880.9132,-984.0142 865.2372,-987.3738 832.5,-962 832.3356,-961.8726 832.1712,-961.745 832.0067,-961.6174"/>
<polygon fill="#000000" stroke="#000000" points="834.6151,-959.2152 824.5868,-955.7969 830.2947,-964.7228 834.6151,-959.2152"/>
<text text-anchor="middle" x="943" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- study_funding -->
<g id="node6" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M2157,-317C2157,-317 2536,-317 2536,-317 2542,-317 2548,-323 2548,-329 2548,-329 2548,-374 2548,-374 2548,-380 2542,-386 2536,-386 2536,-386 2157,-386 2157,-386 2151,-386 2145,-380 2145,-374 2145,-374 2145,-329 2145,-329 2145,-323 2151,-317 2157,-317"/>
<text text-anchor="middle" x="2204.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="2264,-317 2264,-386 "/>
<text text-anchor="middle" x="2274.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2285,-317 2285,-386 "/>
<text text-anchor="middle" x="2406" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="2285,-363 2527,-363 "/>
<text text-anchor="middle" x="2406" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="2285,-340 2527,-340 "/>
<text text-anchor="middle" x="2406" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="2527,-317 2527,-386 "/>
<text text-anchor="middle" x="2537.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge19" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2314.2773,-316.8256C2289.5317,-290.1972 2253.9081,-251.8631 2219.6934,-215.0451"/>
<polygon fill="#000000" stroke="#000000" points="2222.2441,-212.6483 2212.8729,-207.7056 2217.1164,-217.4135 2222.2441,-212.6483"/>
<text text-anchor="middle" x="2299.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- study_personnel -->
<g id="node7" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M2578,-294C2578,-294 2885,-294 2885,-294 2891,-294 2897,-300 2897,-306 2897,-306 2897,-397 2897,-397 2897,-403 2891,-409 2885,-409 2885,-409 2578,-409 2578,-409 2572,-409 2566,-403 2566,-397 2566,-397 2566,-306 2566,-306 2566,-300 2572,-294 2578,-294"/>
<text text-anchor="middle" x="2633" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="2700,-294 2700,-409 "/>
<text text-anchor="middle" x="2710.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2721,-294 2721,-409 "/>
<text text-anchor="middle" x="2798.5" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="2721,-386 2876,-386 "/>
<text text-anchor="middle" x="2798.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="2721,-363 2876,-363 "/>
<text text-anchor="middle" x="2798.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="2721,-340 2876,-340 "/>
<text text-anchor="middle" x="2798.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="2721,-317 2876,-317 "/>
<text text-anchor="middle" x="2798.5" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="2876,-294 2876,-409 "/>
<text text-anchor="middle" x="2886.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge5" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2629.2552,-293.8631C2605.9915,-281.6747 2581.1549,-269.3741 2557.5,-259 2485.8393,-227.5724 2405.5991,-197.8304 2333.4082,-172.9626"/>
<polygon fill="#000000" stroke="#000000" points="2334.3293,-169.5785 2323.7347,-169.6429 2332.0571,-176.1994 2334.3293,-169.5785"/>
<text text-anchor="middle" x="2580" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- methylation_array_file -->
<g id="node8" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M12,-1174.5C12,-1174.5 379,-1174.5 379,-1174.5 385,-1174.5 391,-1180.5 391,-1186.5 391,-1186.5 391,-1392.5 391,-1392.5 391,-1398.5 385,-1404.5 379,-1404.5 379,-1404.5 12,-1404.5 12,-1404.5 6,-1404.5 0,-1398.5 0,-1392.5 0,-1392.5 0,-1186.5 0,-1186.5 0,-1180.5 6,-1174.5 12,-1174.5"/>
<text text-anchor="middle" x="89" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="178,-1174.5 178,-1404.5 "/>
<text text-anchor="middle" x="188.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="199,-1174.5 199,-1404.5 "/>
<text text-anchor="middle" x="284.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="199,-1381.5 370,-1381.5 "/>
<text text-anchor="middle" x="284.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="199,-1358.5 370,-1358.5 "/>
<text text-anchor="middle" x="284.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="199,-1335.5 370,-1335.5 "/>
<text text-anchor="middle" x="284.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="199,-1312.5 370,-1312.5 "/>
<text text-anchor="middle" x="284.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="199,-1289.5 370,-1289.5 "/>
<text text-anchor="middle" x="284.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="199,-1266.5 370,-1266.5 "/>
<text text-anchor="middle" x="284.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="199,-1243.5 370,-1243.5 "/>
<text text-anchor="middle" x="284.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="199,-1220.5 370,-1220.5 "/>
<text text-anchor="middle" x="284.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="199,-1197.5 370,-1197.5 "/>
<text text-anchor="middle" x="284.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="370,-1174.5 370,-1404.5 "/>
<text text-anchor="middle" x="380.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M271.0678,-1174.2959C307.2454,-1122.6811 352.8064,-1062.4425 399.5,-1013 423.7882,-987.282 451.1064,-961.7075 478.6149,-937.6798"/>
<polygon fill="#000000" stroke="#000000" points="481.1173,-940.1424 486.3764,-930.9449 476.5296,-934.8553 481.1173,-940.1424"/>
<text text-anchor="middle" x="523" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study_arm -->
<g id="node10" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M1667,-317C1667,-317 1964,-317 1964,-317 1970,-317 1976,-323 1976,-329 1976,-329 1976,-374 1976,-374 1976,-380 1970,-386 1964,-386 1964,-386 1667,-386 1667,-386 1661,-386 1655,-380 1655,-374 1655,-374 1655,-329 1655,-329 1655,-323 1661,-317 1667,-317"/>
<text text-anchor="middle" x="1701" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="1747,-317 1747,-386 "/>
<text text-anchor="middle" x="1757.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1768,-317 1768,-386 "/>
<text text-anchor="middle" x="1861.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="1768,-363 1955,-363 "/>
<text text-anchor="middle" x="1861.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="1768,-340 1955,-340 "/>
<text text-anchor="middle" x="1861.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="1955,-317 1955,-386 "/>
<text text-anchor="middle" x="1965.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge3" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1603.6377,-495.2637C1650.1727,-463.6864 1711.241,-422.2472 1755.8525,-391.9751"/>
<polygon fill="#000000" stroke="#000000" points="1757.9551,-394.7781 1764.2646,-386.2669 1754.0245,-388.9858 1757.9551,-394.7781"/>
<text text-anchor="middle" x="1700" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge4" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1521.9677,-495.2835C1507.14,-434.206 1491.9781,-326.4793 1545.5,-259 1590.2261,-202.6103 1757.0892,-161.5103 1898.9691,-135.8581"/>
<polygon fill="#000000" stroke="#000000" points="1899.9123,-139.2449 1909.1392,-134.0378 1898.679,-132.3544 1899.9123,-139.2449"/>
<text text-anchor="middle" x="1596" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge2" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1830.8438,-316.9916C1844.3056,-289.7049 1866.0119,-252.0037 1893.5,-226 1897.8129,-221.92 1902.2883,-217.932 1906.8973,-214.0374"/>
<polygon fill="#000000" stroke="#000000" points="1909.2656,-216.6215 1914.7748,-207.5717 1904.8245,-211.2107 1909.2656,-216.6215"/>
<text text-anchor="middle" x="1942" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- publication -->
<g id="node12" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M2927.5,-333.5C2927.5,-333.5 3137.5,-333.5 3137.5,-333.5 3143.5,-333.5 3149.5,-339.5 3149.5,-345.5 3149.5,-345.5 3149.5,-357.5 3149.5,-357.5 3149.5,-363.5 3143.5,-369.5 3137.5,-369.5 3137.5,-369.5 2927.5,-369.5 2927.5,-369.5 2921.5,-369.5 2915.5,-363.5 2915.5,-357.5 2915.5,-357.5 2915.5,-345.5 2915.5,-345.5 2915.5,-339.5 2921.5,-333.5 2927.5,-333.5"/>
<text text-anchor="middle" x="2964" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="3012.5,-333.5 3012.5,-369.5 "/>
<text text-anchor="middle" x="3023" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3033.5,-333.5 3033.5,-369.5 "/>
<text text-anchor="middle" x="3081" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="3128.5,-333.5 3128.5,-369.5 "/>
<text text-anchor="middle" x="3139" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge12" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3013.6974,-333.4726C2990.4464,-312.2451 2948.7445,-277.537 2906.5,-259 2722.8429,-178.4108 2496.8634,-139.4669 2333.7113,-120.802"/>
<polygon fill="#000000" stroke="#000000" points="2333.8763,-117.2985 2323.5471,-119.6561 2333.092,-124.2545 2333.8763,-117.2985"/>
<text text-anchor="middle" x="2896.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- diagnosis -->
<g id="node13" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1253,-651C1253,-651 1636,-651 1636,-651 1642,-651 1648,-657 1648,-663 1648,-663 1648,-938 1648,-938 1648,-944 1642,-950 1636,-950 1636,-950 1253,-950 1253,-950 1247,-950 1241,-944 1241,-938 1241,-938 1241,-663 1241,-663 1241,-657 1247,-651 1253,-651"/>
<text text-anchor="middle" x="1283" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1325,-651 1325,-950 "/>
<text text-anchor="middle" x="1335.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1346,-651 1346,-950 "/>
<text text-anchor="middle" x="1486.5" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1346,-927 1627,-927 "/>
<text text-anchor="middle" x="1486.5" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1346,-904 1627,-904 "/>
<text text-anchor="middle" x="1486.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1346,-881 1627,-881 "/>
<text text-anchor="middle" x="1486.5" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1346,-858 1627,-858 "/>
<text text-anchor="middle" x="1486.5" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1346,-835 1627,-835 "/>
<text text-anchor="middle" x="1486.5" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="1346,-812 1627,-812 "/>
<text text-anchor="middle" x="1486.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1346,-789 1627,-789 "/>
<text text-anchor="middle" x="1486.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1346,-766 1627,-766 "/>
<text text-anchor="middle" x="1486.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis_reference_source</text>
<polyline fill="none" stroke="#000000" points="1346,-743 1627,-743 "/>
<text text-anchor="middle" x="1486.5" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="1346,-720 1627,-720 "/>
<text text-anchor="middle" x="1486.5" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="1346,-697 1627,-697 "/>
<text text-anchor="middle" x="1486.5" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="1346,-674 1627,-674 "/>
<text text-anchor="middle" x="1486.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="1627,-651 1627,-950 "/>
<text text-anchor="middle" x="1637.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1497.0397,-650.9639C1503.7297,-631.9232 1510.2116,-613.4747 1515.8879,-597.319"/>
<polygon fill="#000000" stroke="#000000" points="1519.2999,-598.1662 1519.3128,-587.5714 1512.6957,-595.8458 1519.2999,-598.1662"/>
<text text-anchor="middle" x="1555" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- synonym -->
<g id="node14" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M1534,-1266.5C1534,-1266.5 1835,-1266.5 1835,-1266.5 1841,-1266.5 1847,-1272.5 1847,-1278.5 1847,-1278.5 1847,-1300.5 1847,-1300.5 1847,-1306.5 1841,-1312.5 1835,-1312.5 1835,-1312.5 1534,-1312.5 1534,-1312.5 1528,-1312.5 1522,-1306.5 1522,-1300.5 1522,-1300.5 1522,-1278.5 1522,-1278.5 1522,-1272.5 1528,-1266.5 1534,-1266.5"/>
<text text-anchor="middle" x="1562" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="1602,-1266.5 1602,-1312.5 "/>
<text text-anchor="middle" x="1612.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1623,-1266.5 1623,-1312.5 "/>
<text text-anchor="middle" x="1724.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="1623,-1289.5 1826,-1289.5 "/>
<text text-anchor="middle" x="1724.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="1826,-1266.5 1826,-1312.5 "/>
<text text-anchor="middle" x="1836.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1660.5747,-1266.2036C1602.3979,-1211.1584 1446.5855,-1073.1739 1287.5,-1013 1167.8208,-967.7315 1128.6742,-994.1093 1001.5,-980 929.5039,-972.0124 903.5207,-991.299 833.7706,-962.2511"/>
<polygon fill="#000000" stroke="#000000" points="835.1401,-959.03 824.5738,-958.2528 832.3491,-965.4496 835.1401,-959.03"/>
<text text-anchor="middle" x="1273" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1684.6681,-1266.4201C1685.3128,-1157.2755 1686.3028,-695.8402 1657.5,-639 1648.89,-622.0087 1635.8176,-607.0003 1621.3806,-594.1662"/>
<polygon fill="#000000" stroke="#000000" points="1623.6082,-591.4662 1613.7229,-587.654 1619.0733,-596.7986 1623.6082,-591.4662"/>
<text text-anchor="middle" x="1725" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge8" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1755.1422,-1266.3953C1867.3308,-1225.4277 2082.7088,-1128.326 2172.5,-962 2278.0713,-766.4435 2299.0202,-648.0658 2177.5,-462 2166.6179,-445.3378 2147.8669,-460.3354 2136.5,-444 2091.2729,-379.004 2087.8899,-288.971 2094.9492,-217.88"/>
<polygon fill="#000000" stroke="#000000" points="2098.4724,-217.851 2096.0628,-207.5338 2091.5126,-217.1018 2098.4724,-217.851"/>
<text text-anchor="middle" x="2283" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study_admin -->
<g id="node15" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M3179.5,-259.5C3179.5,-259.5 3505.5,-259.5 3505.5,-259.5 3511.5,-259.5 3517.5,-265.5 3517.5,-271.5 3517.5,-271.5 3517.5,-431.5 3517.5,-431.5 3517.5,-437.5 3511.5,-443.5 3505.5,-443.5 3505.5,-443.5 3179.5,-443.5 3179.5,-443.5 3173.5,-443.5 3167.5,-437.5 3167.5,-431.5 3167.5,-431.5 3167.5,-271.5 3167.5,-271.5 3167.5,-265.5 3173.5,-259.5 3179.5,-259.5"/>
<text text-anchor="middle" x="3221.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="3275.5,-259.5 3275.5,-443.5 "/>
<text text-anchor="middle" x="3286" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3296.5,-259.5 3296.5,-443.5 "/>
<text text-anchor="middle" x="3396.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="3296.5,-420.5 3496.5,-420.5 "/>
<text text-anchor="middle" x="3396.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="3296.5,-397.5 3496.5,-397.5 "/>
<text text-anchor="middle" x="3396.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="3296.5,-374.5 3496.5,-374.5 "/>
<text text-anchor="middle" x="3396.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="3296.5,-351.5 3496.5,-351.5 "/>
<text text-anchor="middle" x="3396.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="3296.5,-328.5 3496.5,-328.5 "/>
<text text-anchor="middle" x="3396.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="3296.5,-305.5 3496.5,-305.5 "/>
<text text-anchor="middle" x="3396.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="3296.5,-282.5 3496.5,-282.5 "/>
<text text-anchor="middle" x="3396.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="3496.5,-259.5 3496.5,-443.5 "/>
<text text-anchor="middle" x="3507" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge11" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3167.4624,-262.0038C3164.4664,-260.9628 3161.4775,-259.9602 3158.5,-259 2882.2042,-169.899 2547.9401,-131.7007 2333.8153,-115.5365"/>
<polygon fill="#000000" stroke="#000000" points="2333.943,-112.0364 2323.7104,-114.7833 2333.4226,-119.017 2333.943,-112.0364"/>
<text text-anchor="middle" x="3133" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
</g>
</svg>
</div>
