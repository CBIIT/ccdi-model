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
<svg width="2291pt" height="1528pt"
 viewBox="0.00 0.00 2291.00 1528.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1524)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1524 2287,-1524 2287,4 -4,4"/>
<!-- methylation_array_file -->
<g id="node1" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M1527.5,-1128.5C1527.5,-1128.5 1894.5,-1128.5 1894.5,-1128.5 1900.5,-1128.5 1906.5,-1134.5 1906.5,-1140.5 1906.5,-1140.5 1906.5,-1346.5 1906.5,-1346.5 1906.5,-1352.5 1900.5,-1358.5 1894.5,-1358.5 1894.5,-1358.5 1527.5,-1358.5 1527.5,-1358.5 1521.5,-1358.5 1515.5,-1352.5 1515.5,-1346.5 1515.5,-1346.5 1515.5,-1140.5 1515.5,-1140.5 1515.5,-1134.5 1521.5,-1128.5 1527.5,-1128.5"/>
<text text-anchor="middle" x="1604.5" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="1693.5,-1128.5 1693.5,-1358.5 "/>
<text text-anchor="middle" x="1704" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1714.5,-1128.5 1714.5,-1358.5 "/>
<text text-anchor="middle" x="1800" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1714.5,-1335.5 1885.5,-1335.5 "/>
<text text-anchor="middle" x="1800" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1714.5,-1312.5 1885.5,-1312.5 "/>
<text text-anchor="middle" x="1800" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1714.5,-1289.5 1885.5,-1289.5 "/>
<text text-anchor="middle" x="1800" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1714.5,-1266.5 1885.5,-1266.5 "/>
<text text-anchor="middle" x="1800" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1714.5,-1243.5 1885.5,-1243.5 "/>
<text text-anchor="middle" x="1800" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1714.5,-1220.5 1885.5,-1220.5 "/>
<text text-anchor="middle" x="1800" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1714.5,-1197.5 1885.5,-1197.5 "/>
<text text-anchor="middle" x="1800" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1714.5,-1174.5 1885.5,-1174.5 "/>
<text text-anchor="middle" x="1800" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="1714.5,-1151.5 1885.5,-1151.5 "/>
<text text-anchor="middle" x="1800" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="1885.5,-1128.5 1885.5,-1358.5 "/>
<text text-anchor="middle" x="1896" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node3" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1554,-639.5C1554,-639.5 1868,-639.5 1868,-639.5 1874,-639.5 1880,-645.5 1880,-651.5 1880,-651.5 1880,-903.5 1880,-903.5 1880,-909.5 1874,-915.5 1868,-915.5 1868,-915.5 1554,-915.5 1554,-915.5 1548,-915.5 1542,-909.5 1542,-903.5 1542,-903.5 1542,-651.5 1542,-651.5 1542,-645.5 1548,-639.5 1554,-639.5"/>
<text text-anchor="middle" x="1576" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1610,-639.5 1610,-915.5 "/>
<text text-anchor="middle" x="1620.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1631,-639.5 1631,-915.5 "/>
<text text-anchor="middle" x="1745" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1631,-892.5 1859,-892.5 "/>
<text text-anchor="middle" x="1745" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1631,-869.5 1859,-869.5 "/>
<text text-anchor="middle" x="1745" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1631,-846.5 1859,-846.5 "/>
<text text-anchor="middle" x="1745" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1631,-823.5 1859,-823.5 "/>
<text text-anchor="middle" x="1745" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1631,-800.5 1859,-800.5 "/>
<text text-anchor="middle" x="1745" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="1631,-777.5 1859,-777.5 "/>
<text text-anchor="middle" x="1745" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1631,-754.5 1859,-754.5 "/>
<text text-anchor="middle" x="1745" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="1631,-731.5 1859,-731.5 "/>
<text text-anchor="middle" x="1745" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="1631,-708.5 1859,-708.5 "/>
<text text-anchor="middle" x="1745" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1631,-685.5 1859,-685.5 "/>
<text text-anchor="middle" x="1745" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1631,-662.5 1859,-662.5 "/>
<text text-anchor="middle" x="1745" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1859,-639.5 1859,-915.5 "/>
<text text-anchor="middle" x="1869.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1711,-1128.309C1711,-1067.1664 1711,-991.336 1711,-925.8368"/>
<polygon fill="#000000" stroke="#000000" points="1714.5001,-925.8346 1711,-915.8347 1707.5001,-925.8347 1714.5001,-925.8346"/>
<text text-anchor="middle" x="1802.5" y="-937.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- imaging_file -->
<g id="node2" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M1937,-1082.5C1937,-1082.5 2271,-1082.5 2271,-1082.5 2277,-1082.5 2283,-1088.5 2283,-1094.5 2283,-1094.5 2283,-1392.5 2283,-1392.5 2283,-1398.5 2277,-1404.5 2271,-1404.5 2271,-1404.5 1937,-1404.5 1937,-1404.5 1931,-1404.5 1925,-1398.5 1925,-1392.5 1925,-1392.5 1925,-1094.5 1925,-1094.5 1925,-1088.5 1931,-1082.5 1937,-1082.5"/>
<text text-anchor="middle" x="1977" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="2029,-1082.5 2029,-1404.5 "/>
<text text-anchor="middle" x="2039.5" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2050,-1082.5 2050,-1404.5 "/>
<text text-anchor="middle" x="2156" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2050,-1381.5 2262,-1381.5 "/>
<text text-anchor="middle" x="2156" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2050,-1358.5 2262,-1358.5 "/>
<text text-anchor="middle" x="2156" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2050,-1335.5 2262,-1335.5 "/>
<text text-anchor="middle" x="2156" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2050,-1312.5 2262,-1312.5 "/>
<text text-anchor="middle" x="2156" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2050,-1289.5 2262,-1289.5 "/>
<text text-anchor="middle" x="2156" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2050,-1266.5 2262,-1266.5 "/>
<text text-anchor="middle" x="2156" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2050,-1243.5 2262,-1243.5 "/>
<text text-anchor="middle" x="2156" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2050,-1220.5 2262,-1220.5 "/>
<text text-anchor="middle" x="2156" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2050,-1197.5 2262,-1197.5 "/>
<text text-anchor="middle" x="2156" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="2050,-1174.5 2262,-1174.5 "/>
<text text-anchor="middle" x="2156" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="2050,-1151.5 2262,-1151.5 "/>
<text text-anchor="middle" x="2156" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="2050,-1128.5 2262,-1128.5 "/>
<text text-anchor="middle" x="2156" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2050,-1105.5 2262,-1105.5 "/>
<text text-anchor="middle" x="2156" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="2262,-1082.5 2262,-1404.5 "/>
<text text-anchor="middle" x="2272.5" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2009.3078,-1082.4304C1976.8131,-1032.6341 1938.3812,-979.0677 1898,-934 1894.5569,-930.1573 1891.0179,-926.3259 1887.3998,-922.5132"/>
<polygon fill="#000000" stroke="#000000" points="1889.8114,-919.972 1880.3489,-915.2064 1884.7742,-924.8328 1889.8114,-919.972"/>
<text text-anchor="middle" x="1958.5" y="-937.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- study -->
<g id="node8" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M754,-.5C754,-.5 1144,-.5 1144,-.5 1150,-.5 1156,-6.5 1156,-12.5 1156,-12.5 1156,-195.5 1156,-195.5 1156,-201.5 1150,-207.5 1144,-207.5 1144,-207.5 754,-207.5 754,-207.5 748,-207.5 742,-201.5 742,-195.5 742,-195.5 742,-12.5 742,-12.5 742,-6.5 748,-.5 754,-.5"/>
<text text-anchor="middle" x="770" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="798,-.5 798,-207.5 "/>
<text text-anchor="middle" x="808.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="819,-.5 819,-207.5 "/>
<text text-anchor="middle" x="977" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="819,-184.5 1135,-184.5 "/>
<text text-anchor="middle" x="977" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="819,-161.5 1135,-161.5 "/>
<text text-anchor="middle" x="977" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="819,-138.5 1135,-138.5 "/>
<text text-anchor="middle" x="977" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="819,-115.5 1135,-115.5 "/>
<text text-anchor="middle" x="977" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="819,-92.5 1135,-92.5 "/>
<text text-anchor="middle" x="977" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="819,-69.5 1135,-69.5 "/>
<text text-anchor="middle" x="977" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="819,-46.5 1135,-46.5 "/>
<text text-anchor="middle" x="977" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="819,-23.5 1135,-23.5 "/>
<text text-anchor="middle" x="977" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="1135,-.5 1135,-207.5 "/>
<text text-anchor="middle" x="1145.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge10" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1875.9033,-639.3502C1987.6914,-529.1491 2098.6625,-374.6372 2000,-259 1946.6682,-196.4926 1458.3287,-145.9027 1166.4336,-120.9265"/>
<polygon fill="#000000" stroke="#000000" points="1166.395,-117.4106 1156.1339,-120.0489 1165.8006,-124.3853 1166.395,-117.4106"/>
<text text-anchor="middle" x="2046.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- participant -->
<g id="node15" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M833.5,-495.5C833.5,-495.5 1064.5,-495.5 1064.5,-495.5 1070.5,-495.5 1076.5,-501.5 1076.5,-507.5 1076.5,-507.5 1076.5,-575.5 1076.5,-575.5 1076.5,-581.5 1070.5,-587.5 1064.5,-587.5 1064.5,-587.5 833.5,-587.5 833.5,-587.5 827.5,-587.5 821.5,-581.5 821.5,-575.5 821.5,-575.5 821.5,-507.5 821.5,-507.5 821.5,-501.5 827.5,-495.5 833.5,-495.5"/>
<text text-anchor="middle" x="869.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="917.5,-495.5 917.5,-587.5 "/>
<text text-anchor="middle" x="928" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="938.5,-495.5 938.5,-587.5 "/>
<text text-anchor="middle" x="997" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="938.5,-564.5 1055.5,-564.5 "/>
<text text-anchor="middle" x="997" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="938.5,-541.5 1055.5,-541.5 "/>
<text text-anchor="middle" x="997" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="938.5,-518.5 1055.5,-518.5 "/>
<text text-anchor="middle" x="997" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1055.5,-495.5 1055.5,-587.5 "/>
<text text-anchor="middle" x="1066" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1541.8548,-643.0679C1538.9108,-641.6552 1535.9583,-640.2975 1533,-639 1455.0118,-604.7945 1233.3301,-574.0228 1086.6331,-556.5692"/>
<polygon fill="#000000" stroke="#000000" points="1086.9845,-553.0864 1076.6425,-555.3873 1086.1621,-560.038 1086.9845,-553.0864"/>
<text text-anchor="middle" x="1512.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- clinical_measure_file -->
<g id="node4" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M61,-651C61,-651 413,-651 413,-651 419,-651 425,-657 425,-663 425,-663 425,-892 425,-892 425,-898 419,-904 413,-904 413,-904 61,-904 61,-904 55,-904 49,-898 49,-892 49,-892 49,-663 49,-663 49,-657 55,-651 61,-651"/>
<text text-anchor="middle" x="132.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="216,-651 216,-904 "/>
<text text-anchor="middle" x="226.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="237,-651 237,-904 "/>
<text text-anchor="middle" x="320.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="237,-881 404,-881 "/>
<text text-anchor="middle" x="320.5" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="237,-858 404,-858 "/>
<text text-anchor="middle" x="320.5" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="237,-835 404,-835 "/>
<text text-anchor="middle" x="320.5" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="237,-812 404,-812 "/>
<text text-anchor="middle" x="320.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="237,-789 404,-789 "/>
<text text-anchor="middle" x="320.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="237,-766 404,-766 "/>
<text text-anchor="middle" x="320.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="237,-743 404,-743 "/>
<text text-anchor="middle" x="320.5" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="237,-720 404,-720 "/>
<text text-anchor="middle" x="320.5" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="237,-697 404,-697 "/>
<text text-anchor="middle" x="320.5" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="237,-674 404,-674 "/>
<text text-anchor="middle" x="320.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="404,-651 404,-904 "/>
<text text-anchor="middle" x="414.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge16" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M158.7539,-650.816C99.0331,-536.1328 41.0553,-368.8208 132,-259 206.8365,-168.6307 516.0132,-130.5315 731.7753,-114.7579"/>
<polygon fill="#000000" stroke="#000000" points="732.2548,-118.2325 741.9777,-114.0235 731.7522,-111.2506 732.2548,-118.2325"/>
<text text-anchor="middle" x="179" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M294.5695,-650.8148C307.5262,-633.3393 322.921,-617.4783 341,-606 379.7774,-581.3805 644.0653,-560.5667 811.1881,-549.6671"/>
<polygon fill="#000000" stroke="#000000" points="811.5532,-553.1509 821.3059,-549.0116 811.1005,-546.1656 811.5532,-553.1509"/>
<text text-anchor="middle" x="470.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- study_funding -->
<g id="node5" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M153.5,-317C153.5,-317 532.5,-317 532.5,-317 538.5,-317 544.5,-323 544.5,-329 544.5,-329 544.5,-374 544.5,-374 544.5,-380 538.5,-386 532.5,-386 532.5,-386 153.5,-386 153.5,-386 147.5,-386 141.5,-380 141.5,-374 141.5,-374 141.5,-329 141.5,-329 141.5,-323 147.5,-317 153.5,-317"/>
<text text-anchor="middle" x="201" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="260.5,-317 260.5,-386 "/>
<text text-anchor="middle" x="271" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="281.5,-317 281.5,-386 "/>
<text text-anchor="middle" x="402.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="281.5,-363 523.5,-363 "/>
<text text-anchor="middle" x="402.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="281.5,-340 523.5,-340 "/>
<text text-anchor="middle" x="402.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="523.5,-317 523.5,-386 "/>
<text text-anchor="middle" x="534" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M419.856,-316.9429C459.7203,-299.2385 509.3029,-277.5587 554,-259 611.5197,-235.1173 674.128,-210.1041 732.1906,-187.3119"/>
<polygon fill="#000000" stroke="#000000" points="733.8117,-190.4358 741.8437,-183.5266 731.2562,-183.9189 733.8117,-190.4358"/>
<text text-anchor="middle" x="692" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- study_admin -->
<g id="node6" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M575,-259.5C575,-259.5 901,-259.5 901,-259.5 907,-259.5 913,-265.5 913,-271.5 913,-271.5 913,-431.5 913,-431.5 913,-437.5 907,-443.5 901,-443.5 901,-443.5 575,-443.5 575,-443.5 569,-443.5 563,-437.5 563,-431.5 563,-431.5 563,-271.5 563,-271.5 563,-265.5 569,-259.5 575,-259.5"/>
<text text-anchor="middle" x="617" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="671,-259.5 671,-443.5 "/>
<text text-anchor="middle" x="681.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="692,-259.5 692,-443.5 "/>
<text text-anchor="middle" x="792" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="692,-420.5 892,-420.5 "/>
<text text-anchor="middle" x="792" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="692,-397.5 892,-397.5 "/>
<text text-anchor="middle" x="792" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="692,-374.5 892,-374.5 "/>
<text text-anchor="middle" x="792" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="692,-351.5 892,-351.5 "/>
<text text-anchor="middle" x="792" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="692,-328.5 892,-328.5 "/>
<text text-anchor="middle" x="792" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="692,-305.5 892,-305.5 "/>
<text text-anchor="middle" x="792" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="692,-282.5 892,-282.5 "/>
<text text-anchor="middle" x="792" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="892,-259.5 892,-443.5 "/>
<text text-anchor="middle" x="902.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge19" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M796.3253,-259.3345C804.5753,-247.8297 813.2415,-236.448 822,-226 824.9523,-222.4781 827.9958,-218.9493 831.1096,-215.4263"/>
<polygon fill="#000000" stroke="#000000" points="833.9473,-217.505 838.0303,-207.7285 828.7417,-212.825 833.9473,-217.505"/>
<text text-anchor="middle" x="878.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- synonym -->
<g id="node7" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M463.5,-1220.5C463.5,-1220.5 764.5,-1220.5 764.5,-1220.5 770.5,-1220.5 776.5,-1226.5 776.5,-1232.5 776.5,-1232.5 776.5,-1254.5 776.5,-1254.5 776.5,-1260.5 770.5,-1266.5 764.5,-1266.5 764.5,-1266.5 463.5,-1266.5 463.5,-1266.5 457.5,-1266.5 451.5,-1260.5 451.5,-1254.5 451.5,-1254.5 451.5,-1232.5 451.5,-1232.5 451.5,-1226.5 457.5,-1220.5 463.5,-1220.5"/>
<text text-anchor="middle" x="491.5" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="531.5,-1220.5 531.5,-1266.5 "/>
<text text-anchor="middle" x="542" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="552.5,-1220.5 552.5,-1266.5 "/>
<text text-anchor="middle" x="654" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="552.5,-1243.5 755.5,-1243.5 "/>
<text text-anchor="middle" x="654" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="755.5,-1220.5 755.5,-1266.5 "/>
<text text-anchor="middle" x="766" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M636.3444,-1220.3937C691.4096,-1165.1442 840.4945,-1025.6413 996,-967 1049.78,-946.7195 1443.0352,-938.7748 1532.2502,-915.3245"/>
<polygon fill="#000000" stroke="#000000" points="1533.5109,-918.5963 1541.9785,-912.2283 1531.3879,-911.926 1533.5109,-918.5963"/>
<text text-anchor="middle" x="1419.5" y="-937.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge7" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M523.4022,-1220.4229C352.6078,-1170.8649 0,-1037.114 0,-777.5 0,-777.5 0,-777.5 0,-351.5 0,-201.1807 451.4506,-140.4788 731.604,-117.2813"/>
<polygon fill="#000000" stroke="#000000" points="732.2292,-120.742 741.9106,-116.4384 731.6586,-113.7653 732.2292,-120.742"/>
<text text-anchor="middle" x="42.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M605.7191,-1220.4597C576.1231,-1133.6712 484.5007,-822.1219 623,-639 646.6223,-607.7669 733.2133,-582.7339 811.2157,-565.8562"/>
<polygon fill="#000000" stroke="#000000" points="812.12,-569.2422 821.1714,-563.7355 810.6616,-562.3958 812.12,-569.2422"/>
<text text-anchor="middle" x="665.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study_personnel -->
<g id="node9" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M1080.5,-294C1080.5,-294 1387.5,-294 1387.5,-294 1393.5,-294 1399.5,-300 1399.5,-306 1399.5,-306 1399.5,-397 1399.5,-397 1399.5,-403 1393.5,-409 1387.5,-409 1387.5,-409 1080.5,-409 1080.5,-409 1074.5,-409 1068.5,-403 1068.5,-397 1068.5,-397 1068.5,-306 1068.5,-306 1068.5,-300 1074.5,-294 1080.5,-294"/>
<text text-anchor="middle" x="1135.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="1202.5,-294 1202.5,-409 "/>
<text text-anchor="middle" x="1213" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1223.5,-294 1223.5,-409 "/>
<text text-anchor="middle" x="1301" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="1223.5,-386 1378.5,-386 "/>
<text text-anchor="middle" x="1301" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="1223.5,-363 1378.5,-363 "/>
<text text-anchor="middle" x="1301" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="1223.5,-340 1378.5,-340 "/>
<text text-anchor="middle" x="1301" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="1223.5,-317 1378.5,-317 "/>
<text text-anchor="middle" x="1301" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="1378.5,-294 1378.5,-409 "/>
<text text-anchor="middle" x="1389" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge18" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1167.5398,-293.7846C1140.2065,-270.0477 1107.5944,-241.7267 1076.0096,-214.2978"/>
<polygon fill="#000000" stroke="#000000" points="1078.2816,-211.6353 1068.4363,-207.721 1073.6917,-216.9205 1078.2816,-211.6353"/>
<text text-anchor="middle" x="1170.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- study_arm -->
<g id="node10" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M1429.5,-317C1429.5,-317 1726.5,-317 1726.5,-317 1732.5,-317 1738.5,-323 1738.5,-329 1738.5,-329 1738.5,-374 1738.5,-374 1738.5,-380 1732.5,-386 1726.5,-386 1726.5,-386 1429.5,-386 1429.5,-386 1423.5,-386 1417.5,-380 1417.5,-374 1417.5,-374 1417.5,-329 1417.5,-329 1417.5,-323 1423.5,-317 1429.5,-317"/>
<text text-anchor="middle" x="1463.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="1509.5,-317 1509.5,-386 "/>
<text text-anchor="middle" x="1520" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1530.5,-317 1530.5,-386 "/>
<text text-anchor="middle" x="1624" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="1530.5,-363 1717.5,-363 "/>
<text text-anchor="middle" x="1624" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="1530.5,-340 1717.5,-340 "/>
<text text-anchor="middle" x="1624" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="1717.5,-317 1717.5,-386 "/>
<text text-anchor="middle" x="1728" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge14" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1520.6139,-316.8037C1488.4862,-298.2238 1447.2959,-275.7769 1409,-259 1331.3667,-224.9899 1243.7344,-193.7794 1165.9418,-168.418"/>
<polygon fill="#000000" stroke="#000000" points="1166.6079,-164.9545 1156.0158,-165.1962 1164.4468,-171.6126 1166.6079,-164.9545"/>
<text text-anchor="middle" x="1408.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- therapeutic_procedure -->
<g id="node11" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M729.5,-720C729.5,-720 1086.5,-720 1086.5,-720 1092.5,-720 1098.5,-726 1098.5,-732 1098.5,-732 1098.5,-823 1098.5,-823 1098.5,-829 1092.5,-835 1086.5,-835 1086.5,-835 729.5,-835 729.5,-835 723.5,-835 717.5,-829 717.5,-823 717.5,-823 717.5,-732 717.5,-732 717.5,-726 723.5,-720 729.5,-720"/>
<text text-anchor="middle" x="808" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="898.5,-720 898.5,-835 "/>
<text text-anchor="middle" x="909" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="919.5,-720 919.5,-835 "/>
<text text-anchor="middle" x="998.5" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="919.5,-812 1077.5,-812 "/>
<text text-anchor="middle" x="998.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="919.5,-789 1077.5,-789 "/>
<text text-anchor="middle" x="998.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="919.5,-766 1077.5,-766 "/>
<text text-anchor="middle" x="998.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="919.5,-743 1077.5,-743 "/>
<text text-anchor="middle" x="998.5" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1077.5,-720 1077.5,-835 "/>
<text text-anchor="middle" x="1088" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M918.0297,-719.7679C924.4873,-682.5975 932.8396,-634.5208 939.2429,-597.6631"/>
<polygon fill="#000000" stroke="#000000" points="942.7306,-598.0347 940.994,-587.5832 935.8339,-596.8365 942.7306,-598.0347"/>
<text text-anchor="middle" x="1030" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- diagnosis -->
<g id="node12" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1128.5,-639.5C1128.5,-639.5 1511.5,-639.5 1511.5,-639.5 1517.5,-639.5 1523.5,-645.5 1523.5,-651.5 1523.5,-651.5 1523.5,-903.5 1523.5,-903.5 1523.5,-909.5 1517.5,-915.5 1511.5,-915.5 1511.5,-915.5 1128.5,-915.5 1128.5,-915.5 1122.5,-915.5 1116.5,-909.5 1116.5,-903.5 1116.5,-903.5 1116.5,-651.5 1116.5,-651.5 1116.5,-645.5 1122.5,-639.5 1128.5,-639.5"/>
<text text-anchor="middle" x="1158.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1200.5,-639.5 1200.5,-915.5 "/>
<text text-anchor="middle" x="1211" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1221.5,-639.5 1221.5,-915.5 "/>
<text text-anchor="middle" x="1362" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1221.5,-892.5 1502.5,-892.5 "/>
<text text-anchor="middle" x="1362" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1221.5,-869.5 1502.5,-869.5 "/>
<text text-anchor="middle" x="1362" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1221.5,-846.5 1502.5,-846.5 "/>
<text text-anchor="middle" x="1362" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1221.5,-823.5 1502.5,-823.5 "/>
<text text-anchor="middle" x="1362" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1221.5,-800.5 1502.5,-800.5 "/>
<text text-anchor="middle" x="1362" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="1221.5,-777.5 1502.5,-777.5 "/>
<text text-anchor="middle" x="1362" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1221.5,-754.5 1502.5,-754.5 "/>
<text text-anchor="middle" x="1362" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1221.5,-731.5 1502.5,-731.5 "/>
<text text-anchor="middle" x="1362" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis_reference_source</text>
<polyline fill="none" stroke="#000000" points="1221.5,-708.5 1502.5,-708.5 "/>
<text text-anchor="middle" x="1362" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="1221.5,-685.5 1502.5,-685.5 "/>
<text text-anchor="middle" x="1362" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="1221.5,-662.5 1502.5,-662.5 "/>
<text text-anchor="middle" x="1362" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="1502.5,-639.5 1502.5,-915.5 "/>
<text text-anchor="middle" x="1513" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1175.9006,-639.3702C1160.0036,-627.2481 1143.5609,-615.8611 1127,-606 1114.1423,-598.344 1100.2282,-591.3711 1086.0401,-585.0806"/>
<polygon fill="#000000" stroke="#000000" points="1087.2537,-581.7923 1076.6852,-581.045 1084.4809,-588.2198 1087.2537,-581.7923"/>
<text text-anchor="middle" x="1189.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- sequencing_file -->
<g id="node13" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M1016.5,-967.5C1016.5,-967.5 1485.5,-967.5 1485.5,-967.5 1491.5,-967.5 1497.5,-973.5 1497.5,-979.5 1497.5,-979.5 1497.5,-1507.5 1497.5,-1507.5 1497.5,-1513.5 1491.5,-1519.5 1485.5,-1519.5 1485.5,-1519.5 1016.5,-1519.5 1016.5,-1519.5 1010.5,-1519.5 1004.5,-1513.5 1004.5,-1507.5 1004.5,-1507.5 1004.5,-979.5 1004.5,-979.5 1004.5,-973.5 1010.5,-967.5 1016.5,-967.5"/>
<text text-anchor="middle" x="1068.5" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="1132.5,-967.5 1132.5,-1519.5 "/>
<text text-anchor="middle" x="1143" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1153.5,-967.5 1153.5,-1519.5 "/>
<text text-anchor="middle" x="1315" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="1153.5,-1496.5 1476.5,-1496.5 "/>
<text text-anchor="middle" x="1315" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1153.5,-1473.5 1476.5,-1473.5 "/>
<text text-anchor="middle" x="1315" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1153.5,-1450.5 1476.5,-1450.5 "/>
<text text-anchor="middle" x="1315" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="1153.5,-1427.5 1476.5,-1427.5 "/>
<text text-anchor="middle" x="1315" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="1153.5,-1404.5 1476.5,-1404.5 "/>
<text text-anchor="middle" x="1315" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1153.5,-1381.5 1476.5,-1381.5 "/>
<text text-anchor="middle" x="1315" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1153.5,-1358.5 1476.5,-1358.5 "/>
<text text-anchor="middle" x="1315" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1153.5,-1335.5 1476.5,-1335.5 "/>
<text text-anchor="middle" x="1315" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1153.5,-1312.5 1476.5,-1312.5 "/>
<text text-anchor="middle" x="1315" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1153.5,-1289.5 1476.5,-1289.5 "/>
<text text-anchor="middle" x="1315" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1153.5,-1266.5 1476.5,-1266.5 "/>
<text text-anchor="middle" x="1315" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1153.5,-1243.5 1476.5,-1243.5 "/>
<text text-anchor="middle" x="1315" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="1153.5,-1220.5 1476.5,-1220.5 "/>
<text text-anchor="middle" x="1315" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="1153.5,-1197.5 1476.5,-1197.5 "/>
<text text-anchor="middle" x="1315" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="1153.5,-1174.5 1476.5,-1174.5 "/>
<text text-anchor="middle" x="1315" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="1153.5,-1151.5 1476.5,-1151.5 "/>
<text text-anchor="middle" x="1315" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="1153.5,-1128.5 1476.5,-1128.5 "/>
<text text-anchor="middle" x="1315" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="1153.5,-1105.5 1476.5,-1105.5 "/>
<text text-anchor="middle" x="1315" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1153.5,-1082.5 1476.5,-1082.5 "/>
<text text-anchor="middle" x="1315" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="1153.5,-1059.5 1476.5,-1059.5 "/>
<text text-anchor="middle" x="1315" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="1153.5,-1036.5 1476.5,-1036.5 "/>
<text text-anchor="middle" x="1315" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="1153.5,-1013.5 1476.5,-1013.5 "/>
<text text-anchor="middle" x="1315" y="-998.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="1153.5,-990.5 1476.5,-990.5 "/>
<text text-anchor="middle" x="1315" y="-975.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="1476.5,-967.5 1476.5,-1519.5 "/>
<text text-anchor="middle" x="1487" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1497.6029,-976.4537C1500.7468,-973.2774 1503.8801,-970.125 1507,-967 1521.455,-952.5212 1536.7064,-937.6502 1552.0958,-922.9124"/>
<polygon fill="#000000" stroke="#000000" points="1554.8436,-925.1279 1559.6588,-915.6905 1550.0093,-920.0653 1554.8436,-925.1279"/>
<text text-anchor="middle" x="1605.5" y="-937.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- publication -->
<g id="node14" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M1769,-333.5C1769,-333.5 1979,-333.5 1979,-333.5 1985,-333.5 1991,-339.5 1991,-345.5 1991,-345.5 1991,-357.5 1991,-357.5 1991,-363.5 1985,-369.5 1979,-369.5 1979,-369.5 1769,-369.5 1769,-369.5 1763,-369.5 1757,-363.5 1757,-357.5 1757,-357.5 1757,-345.5 1757,-345.5 1757,-339.5 1763,-333.5 1769,-333.5"/>
<text text-anchor="middle" x="1805.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="1854,-333.5 1854,-369.5 "/>
<text text-anchor="middle" x="1864.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1875,-333.5 1875,-369.5 "/>
<text text-anchor="middle" x="1922.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="1970,-333.5 1970,-369.5 "/>
<text text-anchor="middle" x="1980.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge15" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1855.204,-333.4574C1831.9596,-312.2149 1790.2642,-277.492 1748,-259 1561.4487,-177.3775 1331.7375,-138.5327 1166.572,-120.1691"/>
<polygon fill="#000000" stroke="#000000" points="1166.6052,-116.6519 1156.2836,-119.0424 1165.8431,-123.6103 1166.6052,-116.6519"/>
<text text-anchor="middle" x="1738" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge2" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M949,-495.094C949,-429.596 949,-307.9591 949,-217.6598"/>
<polygon fill="#000000" stroke="#000000" points="952.5001,-217.6413 949,-207.6413 945.5001,-217.6414 952.5001,-217.6413"/>
<text text-anchor="middle" x="999.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge3" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1076.7489,-524.6762C1170.6564,-509.8686 1300.2992,-484.275 1409,-444 1445.8245,-430.356 1484.4194,-409.7703 1515.4149,-391.4803"/>
<polygon fill="#000000" stroke="#000000" points="1517.5695,-394.2704 1524.3626,-386.1399 1513.982,-388.2595 1517.5695,-394.2704"/>
<text text-anchor="middle" x="1398.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
</g>
</svg>
</div>
