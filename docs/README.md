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
<svg width="3411pt" height="1574pt"
 viewBox="0.00 0.00 3410.50 1574.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1570)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1570 3406.5,-1570 3406.5,4 -4,4"/>
<!-- study_admin -->
<g id="node1" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M12,-259.5C12,-259.5 338,-259.5 338,-259.5 344,-259.5 350,-265.5 350,-271.5 350,-271.5 350,-431.5 350,-431.5 350,-437.5 344,-443.5 338,-443.5 338,-443.5 12,-443.5 12,-443.5 6,-443.5 0,-437.5 0,-431.5 0,-431.5 0,-271.5 0,-271.5 0,-265.5 6,-259.5 12,-259.5"/>
<text text-anchor="middle" x="54" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="108,-259.5 108,-443.5 "/>
<text text-anchor="middle" x="118.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="129,-259.5 129,-443.5 "/>
<text text-anchor="middle" x="229" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="129,-420.5 329,-420.5 "/>
<text text-anchor="middle" x="229" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="129,-397.5 329,-397.5 "/>
<text text-anchor="middle" x="229" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="129,-374.5 329,-374.5 "/>
<text text-anchor="middle" x="229" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="129,-351.5 329,-351.5 "/>
<text text-anchor="middle" x="229" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="129,-328.5 329,-328.5 "/>
<text text-anchor="middle" x="229" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="129,-305.5 329,-305.5 "/>
<text text-anchor="middle" x="229" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="129,-282.5 329,-282.5 "/>
<text text-anchor="middle" x="229" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="329,-259.5 329,-443.5 "/>
<text text-anchor="middle" x="339.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node8" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M1240,-.5C1240,-.5 1630,-.5 1630,-.5 1636,-.5 1642,-6.5 1642,-12.5 1642,-12.5 1642,-195.5 1642,-195.5 1642,-201.5 1636,-207.5 1630,-207.5 1630,-207.5 1240,-207.5 1240,-207.5 1234,-207.5 1228,-201.5 1228,-195.5 1228,-195.5 1228,-12.5 1228,-12.5 1228,-6.5 1234,-.5 1240,-.5"/>
<text text-anchor="middle" x="1256" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="1284,-.5 1284,-207.5 "/>
<text text-anchor="middle" x="1294.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1305,-.5 1305,-207.5 "/>
<text text-anchor="middle" x="1463" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="1305,-184.5 1621,-184.5 "/>
<text text-anchor="middle" x="1463" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="1305,-161.5 1621,-161.5 "/>
<text text-anchor="middle" x="1463" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="1305,-138.5 1621,-138.5 "/>
<text text-anchor="middle" x="1463" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="1305,-115.5 1621,-115.5 "/>
<text text-anchor="middle" x="1463" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="1305,-92.5 1621,-92.5 "/>
<text text-anchor="middle" x="1463" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="1305,-69.5 1621,-69.5 "/>
<text text-anchor="middle" x="1463" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="1305,-46.5 1621,-46.5 "/>
<text text-anchor="middle" x="1463" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="1305,-23.5 1621,-23.5 "/>
<text text-anchor="middle" x="1463" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="1621,-.5 1621,-207.5 "/>
<text text-anchor="middle" x="1631.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge10" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M350.084,-262.1436C353.0657,-261.0593 356.0391,-260.0101 359,-259 513.4779,-206.2986 950.3937,-154.0559 1217.5784,-125.7095"/>
<polygon fill="#000000" stroke="#000000" points="1218.2239,-129.1608 1227.8001,-124.6279 1217.4873,-122.1997 1218.2239,-129.1608"/>
<text text-anchor="middle" x="544.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- study_funding -->
<g id="node2" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M380.5,-317C380.5,-317 759.5,-317 759.5,-317 765.5,-317 771.5,-323 771.5,-329 771.5,-329 771.5,-374 771.5,-374 771.5,-380 765.5,-386 759.5,-386 759.5,-386 380.5,-386 380.5,-386 374.5,-386 368.5,-380 368.5,-374 368.5,-374 368.5,-329 368.5,-329 368.5,-323 374.5,-317 380.5,-317"/>
<text text-anchor="middle" x="428" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="487.5,-317 487.5,-386 "/>
<text text-anchor="middle" x="498" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="508.5,-317 508.5,-386 "/>
<text text-anchor="middle" x="629.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="508.5,-363 750.5,-363 "/>
<text text-anchor="middle" x="629.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="508.5,-340 750.5,-340 "/>
<text text-anchor="middle" x="629.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="750.5,-317 750.5,-386 "/>
<text text-anchor="middle" x="761" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge7" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M585.8534,-316.773C601.077,-287.608 626.9361,-247.3715 662,-226 752.9384,-170.5728 1022.3958,-137.2787 1217.6177,-119.7962"/>
<polygon fill="#000000" stroke="#000000" points="1218.0805,-123.269 1227.732,-118.8986 1217.4617,-116.2964 1218.0805,-123.269"/>
<text text-anchor="middle" x="724" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- clinical_measure_file -->
<g id="node3" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M840,-685.5C840,-685.5 1192,-685.5 1192,-685.5 1198,-685.5 1204,-691.5 1204,-697.5 1204,-697.5 1204,-903.5 1204,-903.5 1204,-909.5 1198,-915.5 1192,-915.5 1192,-915.5 840,-915.5 840,-915.5 834,-915.5 828,-909.5 828,-903.5 828,-903.5 828,-697.5 828,-697.5 828,-691.5 834,-685.5 840,-685.5"/>
<text text-anchor="middle" x="911.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="995,-685.5 995,-915.5 "/>
<text text-anchor="middle" x="1005.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1016,-685.5 1016,-915.5 "/>
<text text-anchor="middle" x="1099.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1016,-892.5 1183,-892.5 "/>
<text text-anchor="middle" x="1099.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1016,-869.5 1183,-869.5 "/>
<text text-anchor="middle" x="1099.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1016,-846.5 1183,-846.5 "/>
<text text-anchor="middle" x="1099.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1016,-823.5 1183,-823.5 "/>
<text text-anchor="middle" x="1099.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1016,-800.5 1183,-800.5 "/>
<text text-anchor="middle" x="1099.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1016,-777.5 1183,-777.5 "/>
<text text-anchor="middle" x="1099.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1016,-754.5 1183,-754.5 "/>
<text text-anchor="middle" x="1099.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1016,-731.5 1183,-731.5 "/>
<text text-anchor="middle" x="1099.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1016,-708.5 1183,-708.5 "/>
<text text-anchor="middle" x="1099.5" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1183,-685.5 1183,-915.5 "/>
<text text-anchor="middle" x="1193.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge9" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1053.6614,-685.2812C1094.5689,-570.484 1167.3706,-392.5473 1265,-259 1276.0397,-243.8987 1288.7302,-229.135 1302.0978,-215.0907"/>
<polygon fill="#000000" stroke="#000000" points="1304.7022,-217.4325 1309.1448,-207.8141 1299.6737,-212.5627 1304.7022,-217.4325"/>
<text text-anchor="middle" x="1231" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- participant -->
<g id="node13" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M1516.5,-495.5C1516.5,-495.5 1747.5,-495.5 1747.5,-495.5 1753.5,-495.5 1759.5,-501.5 1759.5,-507.5 1759.5,-507.5 1759.5,-575.5 1759.5,-575.5 1759.5,-581.5 1753.5,-587.5 1747.5,-587.5 1747.5,-587.5 1516.5,-587.5 1516.5,-587.5 1510.5,-587.5 1504.5,-581.5 1504.5,-575.5 1504.5,-575.5 1504.5,-507.5 1504.5,-507.5 1504.5,-501.5 1510.5,-495.5 1516.5,-495.5"/>
<text text-anchor="middle" x="1552.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1600.5,-495.5 1600.5,-587.5 "/>
<text text-anchor="middle" x="1611" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1621.5,-495.5 1621.5,-587.5 "/>
<text text-anchor="middle" x="1680" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="1621.5,-564.5 1738.5,-564.5 "/>
<text text-anchor="middle" x="1680" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="1621.5,-541.5 1738.5,-541.5 "/>
<text text-anchor="middle" x="1680" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1621.5,-518.5 1738.5,-518.5 "/>
<text text-anchor="middle" x="1680" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1738.5,-495.5 1738.5,-587.5 "/>
<text text-anchor="middle" x="1749" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1143.2224,-685.4315C1165.5387,-668.4566 1189.248,-652.2515 1213,-639 1299.579,-590.6967 1409.0288,-566.2716 1494.352,-553.9491"/>
<polygon fill="#000000" stroke="#000000" points="1494.9546,-557.3989 1504.3704,-552.5416 1493.9807,-550.467 1494.9546,-557.3989"/>
<text text-anchor="middle" x="1406.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- synonym -->
<g id="node4" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M1792.5,-1243.5C1792.5,-1243.5 2093.5,-1243.5 2093.5,-1243.5 2099.5,-1243.5 2105.5,-1249.5 2105.5,-1255.5 2105.5,-1255.5 2105.5,-1323.5 2105.5,-1323.5 2105.5,-1329.5 2099.5,-1335.5 2093.5,-1335.5 2093.5,-1335.5 1792.5,-1335.5 1792.5,-1335.5 1786.5,-1335.5 1780.5,-1329.5 1780.5,-1323.5 1780.5,-1323.5 1780.5,-1255.5 1780.5,-1255.5 1780.5,-1249.5 1786.5,-1243.5 1792.5,-1243.5"/>
<text text-anchor="middle" x="1820.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="1860.5,-1243.5 1860.5,-1335.5 "/>
<text text-anchor="middle" x="1871" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1881.5,-1243.5 1881.5,-1335.5 "/>
<text text-anchor="middle" x="1983" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_id</text>
<polyline fill="none" stroke="#000000" points="1881.5,-1312.5 2084.5,-1312.5 "/>
<text text-anchor="middle" x="1983" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_node</text>
<polyline fill="none" stroke="#000000" points="1881.5,-1289.5 2084.5,-1289.5 "/>
<text text-anchor="middle" x="1983" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="1881.5,-1266.5 2084.5,-1266.5 "/>
<text text-anchor="middle" x="1983" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="2084.5,-1243.5 2084.5,-1335.5 "/>
<text text-anchor="middle" x="2095" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge19" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1780.3255,-1264.4925C1499.8826,-1217.9074 943.4288,-1109.0715 819,-962 772.3195,-906.8249 800,-872.7728 800,-800.5 800,-800.5 800,-800.5 800,-351.5 800,-259.5242 1034.1948,-187.9812 1218.1324,-145.975"/>
<polygon fill="#000000" stroke="#000000" points="1218.9769,-149.3725 1227.9559,-143.7486 1217.4296,-142.5456 1218.9769,-149.3725"/>
<text text-anchor="middle" x="842.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- sample -->
<g id="node10" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M2179,-639.5C2179,-639.5 2493,-639.5 2493,-639.5 2499,-639.5 2505,-645.5 2505,-651.5 2505,-651.5 2505,-949.5 2505,-949.5 2505,-955.5 2499,-961.5 2493,-961.5 2493,-961.5 2179,-961.5 2179,-961.5 2173,-961.5 2167,-955.5 2167,-949.5 2167,-949.5 2167,-651.5 2167,-651.5 2167,-645.5 2173,-639.5 2179,-639.5"/>
<text text-anchor="middle" x="2201" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="2235,-639.5 2235,-961.5 "/>
<text text-anchor="middle" x="2245.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2256,-639.5 2256,-961.5 "/>
<text text-anchor="middle" x="2370" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="2256,-938.5 2484,-938.5 "/>
<text text-anchor="middle" x="2370" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="2256,-915.5 2484,-915.5 "/>
<text text-anchor="middle" x="2370" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="2256,-892.5 2484,-892.5 "/>
<text text-anchor="middle" x="2370" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="2256,-869.5 2484,-869.5 "/>
<text text-anchor="middle" x="2370" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="2256,-846.5 2484,-846.5 "/>
<text text-anchor="middle" x="2370" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="2256,-823.5 2484,-823.5 "/>
<text text-anchor="middle" x="2370" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="2256,-800.5 2484,-800.5 "/>
<text text-anchor="middle" x="2370" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="2256,-777.5 2484,-777.5 "/>
<text text-anchor="middle" x="2370" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="2256,-754.5 2484,-754.5 "/>
<text text-anchor="middle" x="2370" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage</text>
<polyline fill="none" stroke="#000000" points="2256,-731.5 2484,-731.5 "/>
<text text-anchor="middle" x="2370" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="2256,-708.5 2484,-708.5 "/>
<text text-anchor="middle" x="2370" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="2256,-685.5 2484,-685.5 "/>
<text text-anchor="middle" x="2370" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="2256,-662.5 2484,-662.5 "/>
<text text-anchor="middle" x="2370" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_status</text>
<polyline fill="none" stroke="#000000" points="2484,-639.5 2484,-961.5 "/>
<text text-anchor="middle" x="2494.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1967.1716,-1243.1406C1997.8534,-1186.2566 2054.1574,-1088.1243 2115,-1013 2128.8717,-995.8722 2144.0379,-978.7256 2159.717,-962.0143"/>
<polygon fill="#000000" stroke="#000000" points="2162.6217,-964.037 2166.9542,-954.3685 2157.538,-959.225 2162.6217,-964.037"/>
<text text-anchor="middle" x="2184.5" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1960.6509,-1243.4786C1983.617,-1180.8993 2022.5181,-1064.9484 2037,-962 2046.9986,-890.922 2081.4195,-695.3822 2037,-639 2003.8588,-596.9335 1873.5211,-570.9082 1769.5359,-556.4426"/>
<polygon fill="#000000" stroke="#000000" points="1769.9412,-552.9655 1759.5593,-555.0786 1768.993,-559.901 1769.9412,-552.9655"/>
<text text-anchor="middle" x="2101.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- diagnosis -->
<g id="node5" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1234.5,-651C1234.5,-651 1617.5,-651 1617.5,-651 1623.5,-651 1629.5,-657 1629.5,-663 1629.5,-663 1629.5,-938 1629.5,-938 1629.5,-944 1623.5,-950 1617.5,-950 1617.5,-950 1234.5,-950 1234.5,-950 1228.5,-950 1222.5,-944 1222.5,-938 1222.5,-938 1222.5,-663 1222.5,-663 1222.5,-657 1228.5,-651 1234.5,-651"/>
<text text-anchor="middle" x="1264.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1306.5,-651 1306.5,-950 "/>
<text text-anchor="middle" x="1317" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1327.5,-651 1327.5,-950 "/>
<text text-anchor="middle" x="1468" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1327.5,-927 1608.5,-927 "/>
<text text-anchor="middle" x="1468" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1327.5,-904 1608.5,-904 "/>
<text text-anchor="middle" x="1468" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1327.5,-881 1608.5,-881 "/>
<text text-anchor="middle" x="1468" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1327.5,-858 1608.5,-858 "/>
<text text-anchor="middle" x="1468" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1327.5,-835 1608.5,-835 "/>
<text text-anchor="middle" x="1468" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="1327.5,-812 1608.5,-812 "/>
<text text-anchor="middle" x="1468" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1327.5,-789 1608.5,-789 "/>
<text text-anchor="middle" x="1468" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1327.5,-766 1608.5,-766 "/>
<text text-anchor="middle" x="1468" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis_reference_source</text>
<polyline fill="none" stroke="#000000" points="1327.5,-743 1608.5,-743 "/>
<text text-anchor="middle" x="1468" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="1327.5,-720 1608.5,-720 "/>
<text text-anchor="middle" x="1468" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="1327.5,-697 1608.5,-697 "/>
<text text-anchor="middle" x="1468" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="1327.5,-674 1608.5,-674 "/>
<text text-anchor="middle" x="1468" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="1608.5,-651 1608.5,-950 "/>
<text text-anchor="middle" x="1619" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1544.936,-650.9639C1560.6519,-631.2047 1575.8605,-612.0832 1589.0502,-595.5"/>
<polygon fill="#000000" stroke="#000000" points="1591.8707,-597.5764 1595.3564,-587.5714 1586.3923,-593.219 1591.8707,-597.5764"/>
<text text-anchor="middle" x="1621.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- study_personnel -->
<g id="node6" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M2225.5,-294C2225.5,-294 2532.5,-294 2532.5,-294 2538.5,-294 2544.5,-300 2544.5,-306 2544.5,-306 2544.5,-397 2544.5,-397 2544.5,-403 2538.5,-409 2532.5,-409 2532.5,-409 2225.5,-409 2225.5,-409 2219.5,-409 2213.5,-403 2213.5,-397 2213.5,-397 2213.5,-306 2213.5,-306 2213.5,-300 2219.5,-294 2225.5,-294"/>
<text text-anchor="middle" x="2280.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="2347.5,-294 2347.5,-409 "/>
<text text-anchor="middle" x="2358" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2368.5,-294 2368.5,-409 "/>
<text text-anchor="middle" x="2446" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="2368.5,-386 2523.5,-386 "/>
<text text-anchor="middle" x="2446" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="2368.5,-363 2523.5,-363 "/>
<text text-anchor="middle" x="2446" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="2368.5,-340 2523.5,-340 "/>
<text text-anchor="middle" x="2446" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="2368.5,-317 2523.5,-317 "/>
<text text-anchor="middle" x="2446" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="2523.5,-294 2523.5,-409 "/>
<text text-anchor="middle" x="2534" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge2" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2311.8883,-293.8225C2279.724,-269.153 2239.4495,-242.3253 2199,-226 2102.4059,-187.0148 1842.419,-150.4868 1652.4815,-127.7486"/>
<polygon fill="#000000" stroke="#000000" points="1652.6987,-124.2498 1642.3547,-126.5413 1651.8701,-131.2005 1652.6987,-124.2498"/>
<text text-anchor="middle" x="2295.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- therapeutic_procedure -->
<g id="node7" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M1659.5,-743C1659.5,-743 2016.5,-743 2016.5,-743 2022.5,-743 2028.5,-749 2028.5,-755 2028.5,-755 2028.5,-846 2028.5,-846 2028.5,-852 2022.5,-858 2016.5,-858 2016.5,-858 1659.5,-858 1659.5,-858 1653.5,-858 1647.5,-852 1647.5,-846 1647.5,-846 1647.5,-755 1647.5,-755 1647.5,-749 1653.5,-743 1659.5,-743"/>
<text text-anchor="middle" x="1738" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="1828.5,-743 1828.5,-858 "/>
<text text-anchor="middle" x="1839" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1849.5,-743 1849.5,-858 "/>
<text text-anchor="middle" x="1928.5" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="1849.5,-835 2007.5,-835 "/>
<text text-anchor="middle" x="1928.5" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="1849.5,-812 2007.5,-812 "/>
<text text-anchor="middle" x="1928.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1849.5,-789 2007.5,-789 "/>
<text text-anchor="middle" x="1928.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="1849.5,-766 2007.5,-766 "/>
<text text-anchor="middle" x="1928.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="2007.5,-743 2007.5,-858 "/>
<text text-anchor="middle" x="2018" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1792.026,-742.6977C1757.0852,-698.7673 1709.3597,-638.7629 1675.1376,-595.7361"/>
<polygon fill="#000000" stroke="#000000" points="1677.8749,-593.555 1668.9109,-587.9073 1672.3965,-597.9124 1677.8749,-593.555"/>
<text text-anchor="middle" x="1786" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- sequencing_file -->
<g id="node9" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M2921.5,-1013.5C2921.5,-1013.5 3390.5,-1013.5 3390.5,-1013.5 3396.5,-1013.5 3402.5,-1019.5 3402.5,-1025.5 3402.5,-1025.5 3402.5,-1553.5 3402.5,-1553.5 3402.5,-1559.5 3396.5,-1565.5 3390.5,-1565.5 3390.5,-1565.5 2921.5,-1565.5 2921.5,-1565.5 2915.5,-1565.5 2909.5,-1559.5 2909.5,-1553.5 2909.5,-1553.5 2909.5,-1025.5 2909.5,-1025.5 2909.5,-1019.5 2915.5,-1013.5 2921.5,-1013.5"/>
<text text-anchor="middle" x="2973.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="3037.5,-1013.5 3037.5,-1565.5 "/>
<text text-anchor="middle" x="3048" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3058.5,-1013.5 3058.5,-1565.5 "/>
<text text-anchor="middle" x="3220" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="3058.5,-1542.5 3381.5,-1542.5 "/>
<text text-anchor="middle" x="3220" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="3058.5,-1519.5 3381.5,-1519.5 "/>
<text text-anchor="middle" x="3220" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="3058.5,-1496.5 3381.5,-1496.5 "/>
<text text-anchor="middle" x="3220" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="3058.5,-1473.5 3381.5,-1473.5 "/>
<text text-anchor="middle" x="3220" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="3058.5,-1450.5 3381.5,-1450.5 "/>
<text text-anchor="middle" x="3220" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="3058.5,-1427.5 3381.5,-1427.5 "/>
<text text-anchor="middle" x="3220" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="3058.5,-1404.5 3381.5,-1404.5 "/>
<text text-anchor="middle" x="3220" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="3058.5,-1381.5 3381.5,-1381.5 "/>
<text text-anchor="middle" x="3220" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="3058.5,-1358.5 3381.5,-1358.5 "/>
<text text-anchor="middle" x="3220" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="3058.5,-1335.5 3381.5,-1335.5 "/>
<text text-anchor="middle" x="3220" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="3058.5,-1312.5 3381.5,-1312.5 "/>
<text text-anchor="middle" x="3220" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="3058.5,-1289.5 3381.5,-1289.5 "/>
<text text-anchor="middle" x="3220" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="3058.5,-1266.5 3381.5,-1266.5 "/>
<text text-anchor="middle" x="3220" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="3058.5,-1243.5 3381.5,-1243.5 "/>
<text text-anchor="middle" x="3220" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="3058.5,-1220.5 3381.5,-1220.5 "/>
<text text-anchor="middle" x="3220" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="3058.5,-1197.5 3381.5,-1197.5 "/>
<text text-anchor="middle" x="3220" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="3058.5,-1174.5 3381.5,-1174.5 "/>
<text text-anchor="middle" x="3220" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="3058.5,-1151.5 3381.5,-1151.5 "/>
<text text-anchor="middle" x="3220" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="3058.5,-1128.5 3381.5,-1128.5 "/>
<text text-anchor="middle" x="3220" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="3058.5,-1105.5 3381.5,-1105.5 "/>
<text text-anchor="middle" x="3220" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="3058.5,-1082.5 3381.5,-1082.5 "/>
<text text-anchor="middle" x="3220" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="3058.5,-1059.5 3381.5,-1059.5 "/>
<text text-anchor="middle" x="3220" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="3058.5,-1036.5 3381.5,-1036.5 "/>
<text text-anchor="middle" x="3220" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="3381.5,-1013.5 3381.5,-1565.5 "/>
<text text-anchor="middle" x="3392" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2909.0978,-1018.5729C2906.4075,-1016.6824 2903.708,-1014.8241 2901,-1013 2783.0638,-933.5587 2631.4236,-878.6325 2514.9381,-844.5512"/>
<polygon fill="#000000" stroke="#000000" points="2515.7781,-841.1507 2505.1989,-841.7262 2513.828,-847.8736 2515.7781,-841.1507"/>
<text text-anchor="middle" x="2925.5" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge5" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2203.4496,-639.4103C2192.7168,-627.8738 2181.8307,-616.6166 2171,-606 1996.6119,-435.0602 1950.113,-391.5152 1745,-259 1715.5487,-239.9727 1683.4431,-221.5766 1651.4177,-204.5102"/>
<polygon fill="#000000" stroke="#000000" points="1652.865,-201.3163 1642.3892,-199.7324 1649.5908,-207.5034 1652.865,-201.3163"/>
<text text-anchor="middle" x="2071.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2166.7446,-647.2568C2162.1822,-644.3889 2157.5974,-641.6303 2153,-639 2130.6754,-626.2273 2121.1921,-632.1201 2098,-621 2086.9955,-615.7236 2086.4164,-610.3133 2075,-606 2020.6242,-585.4557 1878.5497,-566.8988 1769.8249,-555.0208"/>
<polygon fill="#000000" stroke="#000000" points="1770.0624,-551.5261 1759.7434,-553.928 1769.308,-558.4853 1770.0624,-551.5261"/>
<text text-anchor="middle" x="2134.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- imaging_file -->
<g id="node11" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M2136,-1128.5C2136,-1128.5 2470,-1128.5 2470,-1128.5 2476,-1128.5 2482,-1134.5 2482,-1140.5 2482,-1140.5 2482,-1438.5 2482,-1438.5 2482,-1444.5 2476,-1450.5 2470,-1450.5 2470,-1450.5 2136,-1450.5 2136,-1450.5 2130,-1450.5 2124,-1444.5 2124,-1438.5 2124,-1438.5 2124,-1140.5 2124,-1140.5 2124,-1134.5 2130,-1128.5 2136,-1128.5"/>
<text text-anchor="middle" x="2176" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="2228,-1128.5 2228,-1450.5 "/>
<text text-anchor="middle" x="2238.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2249,-1128.5 2249,-1450.5 "/>
<text text-anchor="middle" x="2355" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2249,-1427.5 2461,-1427.5 "/>
<text text-anchor="middle" x="2355" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2249,-1404.5 2461,-1404.5 "/>
<text text-anchor="middle" x="2355" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2249,-1381.5 2461,-1381.5 "/>
<text text-anchor="middle" x="2355" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2249,-1358.5 2461,-1358.5 "/>
<text text-anchor="middle" x="2355" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2249,-1335.5 2461,-1335.5 "/>
<text text-anchor="middle" x="2355" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2249,-1312.5 2461,-1312.5 "/>
<text text-anchor="middle" x="2355" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2249,-1289.5 2461,-1289.5 "/>
<text text-anchor="middle" x="2355" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2249,-1266.5 2461,-1266.5 "/>
<text text-anchor="middle" x="2355" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2249,-1243.5 2461,-1243.5 "/>
<text text-anchor="middle" x="2355" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="2249,-1220.5 2461,-1220.5 "/>
<text text-anchor="middle" x="2355" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="2249,-1197.5 2461,-1197.5 "/>
<text text-anchor="middle" x="2355" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="2249,-1174.5 2461,-1174.5 "/>
<text text-anchor="middle" x="2355" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2249,-1151.5 2461,-1151.5 "/>
<text text-anchor="middle" x="2355" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="2461,-1128.5 2461,-1450.5 "/>
<text text-anchor="middle" x="2471.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2313.874,-1128.3669C2317.2632,-1078.1459 2321.0121,-1022.594 2324.446,-971.7088"/>
<polygon fill="#000000" stroke="#000000" points="2327.9471,-971.81 2325.1284,-961.597 2320.963,-971.3386 2327.9471,-971.81"/>
<text text-anchor="middle" x="2377.5" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- study_arm -->
<g id="node12" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M1286.5,-317C1286.5,-317 1583.5,-317 1583.5,-317 1589.5,-317 1595.5,-323 1595.5,-329 1595.5,-329 1595.5,-374 1595.5,-374 1595.5,-380 1589.5,-386 1583.5,-386 1583.5,-386 1286.5,-386 1286.5,-386 1280.5,-386 1274.5,-380 1274.5,-374 1274.5,-374 1274.5,-329 1274.5,-329 1274.5,-323 1280.5,-317 1286.5,-317"/>
<text text-anchor="middle" x="1320.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="1366.5,-317 1366.5,-386 "/>
<text text-anchor="middle" x="1377" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1387.5,-317 1387.5,-386 "/>
<text text-anchor="middle" x="1481" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="1387.5,-363 1574.5,-363 "/>
<text text-anchor="middle" x="1481" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="1387.5,-340 1574.5,-340 "/>
<text text-anchor="middle" x="1481" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="1574.5,-317 1574.5,-386 "/>
<text text-anchor="middle" x="1585" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge15" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1435,-316.8256C1435,-290.8629 1435,-253.7725 1435,-217.8091"/>
<polygon fill="#000000" stroke="#000000" points="1438.5001,-217.7056 1435,-207.7056 1431.5001,-217.7056 1438.5001,-217.7056"/>
<text text-anchor="middle" x="1483.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge4" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1637.1235,-495.4648C1641.5164,-437.1672 1642.079,-335.1506 1604,-259 1596.3345,-243.6704 1586.4678,-229.1133 1575.357,-215.5023"/>
<polygon fill="#000000" stroke="#000000" points="1577.8064,-212.9782 1568.6786,-207.599 1572.4596,-217.4962 1577.8064,-212.9782"/>
<text text-anchor="middle" x="1690.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge3" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1539.9959,-495.4008C1531.839,-489.7115 1524.0242,-483.5647 1517,-477 1491.9958,-453.6315 1471.0437,-421.1575 1456.578,-395.0977"/>
<polygon fill="#000000" stroke="#000000" points="1459.5811,-393.2936 1451.7358,-386.1731 1453.4284,-396.6318 1459.5811,-393.2936"/>
<text text-anchor="middle" x="1567.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- publication -->
<g id="node14" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M2575,-333.5C2575,-333.5 2785,-333.5 2785,-333.5 2791,-333.5 2797,-339.5 2797,-345.5 2797,-345.5 2797,-357.5 2797,-357.5 2797,-363.5 2791,-369.5 2785,-369.5 2785,-369.5 2575,-369.5 2575,-369.5 2569,-369.5 2563,-363.5 2563,-357.5 2563,-357.5 2563,-345.5 2563,-345.5 2563,-339.5 2569,-333.5 2575,-333.5"/>
<text text-anchor="middle" x="2611.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="2660,-333.5 2660,-369.5 "/>
<text text-anchor="middle" x="2670.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2681,-333.5 2681,-369.5 "/>
<text text-anchor="middle" x="2728.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="2776,-333.5 2776,-369.5 "/>
<text text-anchor="middle" x="2786.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge14" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2661.2509,-333.3493C2638.0526,-312.0003 2596.4025,-277.1726 2554,-259 2477.233,-226.0997 2451.5418,-238.7456 2369,-226 2124.0912,-188.1827 1841.8533,-152.3881 1652.2966,-129.4728"/>
<polygon fill="#000000" stroke="#000000" points="1652.5588,-125.9791 1642.2114,-128.2552 1651.7197,-132.9286 1652.5588,-125.9791"/>
<text text-anchor="middle" x="2550" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- methylation_array_file -->
<g id="node15" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M2512.5,-1174.5C2512.5,-1174.5 2879.5,-1174.5 2879.5,-1174.5 2885.5,-1174.5 2891.5,-1180.5 2891.5,-1186.5 2891.5,-1186.5 2891.5,-1392.5 2891.5,-1392.5 2891.5,-1398.5 2885.5,-1404.5 2879.5,-1404.5 2879.5,-1404.5 2512.5,-1404.5 2512.5,-1404.5 2506.5,-1404.5 2500.5,-1398.5 2500.5,-1392.5 2500.5,-1392.5 2500.5,-1186.5 2500.5,-1186.5 2500.5,-1180.5 2506.5,-1174.5 2512.5,-1174.5"/>
<text text-anchor="middle" x="2589.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="2678.5,-1174.5 2678.5,-1404.5 "/>
<text text-anchor="middle" x="2689" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2699.5,-1174.5 2699.5,-1404.5 "/>
<text text-anchor="middle" x="2785" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2699.5,-1381.5 2870.5,-1381.5 "/>
<text text-anchor="middle" x="2785" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2699.5,-1358.5 2870.5,-1358.5 "/>
<text text-anchor="middle" x="2785" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2699.5,-1335.5 2870.5,-1335.5 "/>
<text text-anchor="middle" x="2785" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2699.5,-1312.5 2870.5,-1312.5 "/>
<text text-anchor="middle" x="2785" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2699.5,-1289.5 2870.5,-1289.5 "/>
<text text-anchor="middle" x="2785" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2699.5,-1266.5 2870.5,-1266.5 "/>
<text text-anchor="middle" x="2785" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2699.5,-1243.5 2870.5,-1243.5 "/>
<text text-anchor="middle" x="2785" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2699.5,-1220.5 2870.5,-1220.5 "/>
<text text-anchor="middle" x="2785" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="2699.5,-1197.5 2870.5,-1197.5 "/>
<text text-anchor="middle" x="2785" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="2870.5,-1174.5 2870.5,-1404.5 "/>
<text text-anchor="middle" x="2881" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2611.1409,-1174.233C2566.296,-1113.3188 2510.3948,-1037.3862 2460.7158,-969.9057"/>
<polygon fill="#000000" stroke="#000000" points="2463.4367,-967.6978 2454.6894,-961.7198 2457.7995,-971.8479 2463.4367,-967.6978"/>
<text text-anchor="middle" x="2564.5" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
</g>
</svg>
</div>
