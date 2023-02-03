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
<svg width="3790pt" height="1574pt"
 viewBox="0.00 0.00 3790.00 1574.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1570)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1570 3786,-1570 3786,4 -4,4"/>
<!-- synonym -->
<g id="node1" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M2165,-1255C2165,-1255 2466,-1255 2466,-1255 2472,-1255 2478,-1261 2478,-1267 2478,-1267 2478,-1289 2478,-1289 2478,-1295 2472,-1301 2466,-1301 2466,-1301 2165,-1301 2165,-1301 2159,-1301 2153,-1295 2153,-1289 2153,-1289 2153,-1267 2153,-1267 2153,-1261 2159,-1255 2165,-1255"/>
<text text-anchor="middle" x="2193" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="2233,-1255 2233,-1301 "/>
<text text-anchor="middle" x="2243.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2254,-1255 2254,-1301 "/>
<text text-anchor="middle" x="2355.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="2254,-1278 2457,-1278 "/>
<text text-anchor="middle" x="2355.5" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="2457,-1255 2457,-1301 "/>
<text text-anchor="middle" x="2467.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node5" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M2513.5,-.5C2513.5,-.5 2903.5,-.5 2903.5,-.5 2909.5,-.5 2915.5,-6.5 2915.5,-12.5 2915.5,-12.5 2915.5,-195.5 2915.5,-195.5 2915.5,-201.5 2909.5,-207.5 2903.5,-207.5 2903.5,-207.5 2513.5,-207.5 2513.5,-207.5 2507.5,-207.5 2501.5,-201.5 2501.5,-195.5 2501.5,-195.5 2501.5,-12.5 2501.5,-12.5 2501.5,-6.5 2507.5,-.5 2513.5,-.5"/>
<text text-anchor="middle" x="2529.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="2557.5,-.5 2557.5,-207.5 "/>
<text text-anchor="middle" x="2568" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2578.5,-.5 2578.5,-207.5 "/>
<text text-anchor="middle" x="2736.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="2578.5,-184.5 2894.5,-184.5 "/>
<text text-anchor="middle" x="2736.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="2578.5,-161.5 2894.5,-161.5 "/>
<text text-anchor="middle" x="2736.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="2578.5,-138.5 2894.5,-138.5 "/>
<text text-anchor="middle" x="2736.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="2578.5,-115.5 2894.5,-115.5 "/>
<text text-anchor="middle" x="2736.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="2578.5,-92.5 2894.5,-92.5 "/>
<text text-anchor="middle" x="2736.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="2578.5,-69.5 2894.5,-69.5 "/>
<text text-anchor="middle" x="2736.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="2578.5,-46.5 2894.5,-46.5 "/>
<text text-anchor="middle" x="2736.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="2578.5,-23.5 2894.5,-23.5 "/>
<text text-anchor="middle" x="2736.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="2894.5,-.5 2894.5,-207.5 "/>
<text text-anchor="middle" x="2905" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge8" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2471.4968,-1254.9402C2649.1704,-1219.8475 2933.6688,-1135.0353 3079.5,-939 3119.6089,-885.0831 3098.5,-856.1994 3098.5,-789 3098.5,-789 3098.5,-789 3098.5,-351.5 3098.5,-256.5258 3015.029,-196.4558 2925.3198,-159.3216"/>
<polygon fill="#000000" stroke="#000000" points="2926.3585,-155.9664 2915.7755,-155.4648 2923.7358,-162.4565 2926.3585,-155.9664"/>
<text text-anchor="middle" x="3141" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- participant -->
<g id="node8" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M1949,-495.5C1949,-495.5 2180,-495.5 2180,-495.5 2186,-495.5 2192,-501.5 2192,-507.5 2192,-507.5 2192,-575.5 2192,-575.5 2192,-581.5 2186,-587.5 2180,-587.5 2180,-587.5 1949,-587.5 1949,-587.5 1943,-587.5 1937,-581.5 1937,-575.5 1937,-575.5 1937,-507.5 1937,-507.5 1937,-501.5 1943,-495.5 1949,-495.5"/>
<text text-anchor="middle" x="1985" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="2033,-495.5 2033,-587.5 "/>
<text text-anchor="middle" x="2043.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2054,-495.5 2054,-587.5 "/>
<text text-anchor="middle" x="2112.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="2054,-564.5 2171,-564.5 "/>
<text text-anchor="middle" x="2112.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="2054,-541.5 2171,-541.5 "/>
<text text-anchor="middle" x="2112.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="2054,-518.5 2171,-518.5 "/>
<text text-anchor="middle" x="2112.5" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="2171,-495.5 2171,-587.5 "/>
<text text-anchor="middle" x="2181.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2305.7137,-1254.6433C2283.3633,-1200.3077 2228.3557,-1060.7729 2200.5,-939 2170.5425,-808.0391 2222.8854,-759.5055 2163.5,-639 2155.5374,-622.8421 2143.7969,-607.8149 2131.1599,-594.6335"/>
<polygon fill="#000000" stroke="#000000" points="2133.6004,-592.124 2124.0654,-587.5049 2128.6387,-597.0619 2133.6004,-592.124"/>
<text text-anchor="middle" x="2243" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- sample -->
<g id="node13" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1403.5,-720C1403.5,-720 1717.5,-720 1717.5,-720 1723.5,-720 1729.5,-726 1729.5,-732 1729.5,-732 1729.5,-846 1729.5,-846 1729.5,-852 1723.5,-858 1717.5,-858 1717.5,-858 1403.5,-858 1403.5,-858 1397.5,-858 1391.5,-852 1391.5,-846 1391.5,-846 1391.5,-732 1391.5,-732 1391.5,-726 1397.5,-720 1403.5,-720"/>
<text text-anchor="middle" x="1425.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1459.5,-720 1459.5,-858 "/>
<text text-anchor="middle" x="1470" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1480.5,-720 1480.5,-858 "/>
<text text-anchor="middle" x="1594.5" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1480.5,-835 1708.5,-835 "/>
<text text-anchor="middle" x="1594.5" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1480.5,-812 1708.5,-812 "/>
<text text-anchor="middle" x="1594.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1480.5,-789 1708.5,-789 "/>
<text text-anchor="middle" x="1594.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1480.5,-766 1708.5,-766 "/>
<text text-anchor="middle" x="1594.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1480.5,-743 1708.5,-743 "/>
<text text-anchor="middle" x="1594.5" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="1708.5,-720 1708.5,-858 "/>
<text text-anchor="middle" x="1719" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2309.2828,-1254.8109C2292.8778,-1198.5796 2242.7081,-1054.8343 2143.5,-990 2105.5332,-965.188 1780.0464,-957.1935 1738.5,-939 1699.084,-921.7394 1661.6635,-892.8881 1631.3971,-865.0737"/>
<polygon fill="#000000" stroke="#000000" points="1633.5563,-862.3012 1623.8595,-858.0323 1628.7777,-867.4165 1633.5563,-862.3012"/>
<text text-anchor="middle" x="2090" y="-960.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- sample_diagnosis -->
<g id="node2" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M894.5,-1059.5C894.5,-1059.5 1336.5,-1059.5 1336.5,-1059.5 1342.5,-1059.5 1348.5,-1065.5 1348.5,-1071.5 1348.5,-1071.5 1348.5,-1484.5 1348.5,-1484.5 1348.5,-1490.5 1342.5,-1496.5 1336.5,-1496.5 1336.5,-1496.5 894.5,-1496.5 894.5,-1496.5 888.5,-1496.5 882.5,-1490.5 882.5,-1484.5 882.5,-1484.5 882.5,-1071.5 882.5,-1071.5 882.5,-1065.5 888.5,-1059.5 894.5,-1059.5"/>
<text text-anchor="middle" x="954" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1025.5,-1059.5 1025.5,-1496.5 "/>
<text text-anchor="middle" x="1036" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1046.5,-1059.5 1046.5,-1496.5 "/>
<text text-anchor="middle" x="1187" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1046.5,-1473.5 1327.5,-1473.5 "/>
<text text-anchor="middle" x="1187" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1046.5,-1450.5 1327.5,-1450.5 "/>
<text text-anchor="middle" x="1187" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1046.5,-1427.5 1327.5,-1427.5 "/>
<text text-anchor="middle" x="1187" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1046.5,-1404.5 1327.5,-1404.5 "/>
<text text-anchor="middle" x="1187" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="1046.5,-1381.5 1327.5,-1381.5 "/>
<text text-anchor="middle" x="1187" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1046.5,-1358.5 1327.5,-1358.5 "/>
<text text-anchor="middle" x="1187" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1046.5,-1335.5 1327.5,-1335.5 "/>
<text text-anchor="middle" x="1187" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis_reference_source</text>
<polyline fill="none" stroke="#000000" points="1046.5,-1312.5 1327.5,-1312.5 "/>
<text text-anchor="middle" x="1187" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="1046.5,-1289.5 1327.5,-1289.5 "/>
<text text-anchor="middle" x="1187" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="1046.5,-1266.5 1327.5,-1266.5 "/>
<text text-anchor="middle" x="1187" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1046.5,-1243.5 1327.5,-1243.5 "/>
<text text-anchor="middle" x="1187" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="1046.5,-1220.5 1327.5,-1220.5 "/>
<text text-anchor="middle" x="1187" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="1046.5,-1197.5 1327.5,-1197.5 "/>
<text text-anchor="middle" x="1187" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1046.5,-1174.5 1327.5,-1174.5 "/>
<text text-anchor="middle" x="1187" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="1046.5,-1151.5 1327.5,-1151.5 "/>
<text text-anchor="middle" x="1187" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="1046.5,-1128.5 1327.5,-1128.5 "/>
<text text-anchor="middle" x="1187" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1046.5,-1105.5 1327.5,-1105.5 "/>
<text text-anchor="middle" x="1187" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1046.5,-1082.5 1327.5,-1082.5 "/>
<text text-anchor="middle" x="1187" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1327.5,-1059.5 1327.5,-1496.5 "/>
<text text-anchor="middle" x="1338" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1295.7691,-1059.1523C1316.286,-1035.5432 1337.1417,-1012.0918 1357.5,-990 1396.5714,-947.6018 1442.0183,-902.2619 1479.9936,-865.3949"/>
<polygon fill="#000000" stroke="#000000" points="1482.7377,-867.6096 1487.4849,-858.1378 1477.8671,-862.5818 1482.7377,-867.6096"/>
<text text-anchor="middle" x="1458.5" y="-960.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
<!-- diagnosis -->
<g id="node3" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1760,-639.5C1760,-639.5 2143,-639.5 2143,-639.5 2149,-639.5 2155,-645.5 2155,-651.5 2155,-651.5 2155,-926.5 2155,-926.5 2155,-932.5 2149,-938.5 2143,-938.5 2143,-938.5 1760,-938.5 1760,-938.5 1754,-938.5 1748,-932.5 1748,-926.5 1748,-926.5 1748,-651.5 1748,-651.5 1748,-645.5 1754,-639.5 1760,-639.5"/>
<text text-anchor="middle" x="1790" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1832,-639.5 1832,-938.5 "/>
<text text-anchor="middle" x="1842.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1853,-639.5 1853,-938.5 "/>
<text text-anchor="middle" x="1993.5" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1853,-915.5 2134,-915.5 "/>
<text text-anchor="middle" x="1993.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1853,-892.5 2134,-892.5 "/>
<text text-anchor="middle" x="1993.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1853,-869.5 2134,-869.5 "/>
<text text-anchor="middle" x="1993.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1853,-846.5 2134,-846.5 "/>
<text text-anchor="middle" x="1993.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1853,-823.5 2134,-823.5 "/>
<text text-anchor="middle" x="1993.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="1853,-800.5 2134,-800.5 "/>
<text text-anchor="middle" x="1993.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1853,-777.5 2134,-777.5 "/>
<text text-anchor="middle" x="1993.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1853,-754.5 2134,-754.5 "/>
<text text-anchor="middle" x="1993.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis_reference_source</text>
<polyline fill="none" stroke="#000000" points="1853,-731.5 2134,-731.5 "/>
<text text-anchor="middle" x="1993.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="1853,-708.5 2134,-708.5 "/>
<text text-anchor="middle" x="1993.5" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="1853,-685.5 2134,-685.5 "/>
<text text-anchor="middle" x="1993.5" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="1853,-662.5 2134,-662.5 "/>
<text text-anchor="middle" x="1993.5" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="2134,-639.5 2134,-938.5 "/>
<text text-anchor="middle" x="2144.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2019.8394,-639.3186C2026.6838,-624.3275 2033.2855,-609.868 2039.2179,-596.8744"/>
<polygon fill="#000000" stroke="#000000" points="2042.4438,-598.2359 2043.4133,-587.6855 2036.0761,-595.3286 2042.4438,-598.2359"/>
<text text-anchor="middle" x="2079" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- methylation_array_file -->
<g id="node4" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M1379,-1163C1379,-1163 1746,-1163 1746,-1163 1752,-1163 1758,-1169 1758,-1175 1758,-1175 1758,-1381 1758,-1381 1758,-1387 1752,-1393 1746,-1393 1746,-1393 1379,-1393 1379,-1393 1373,-1393 1367,-1387 1367,-1381 1367,-1381 1367,-1175 1367,-1175 1367,-1169 1373,-1163 1379,-1163"/>
<text text-anchor="middle" x="1456" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="1545,-1163 1545,-1393 "/>
<text text-anchor="middle" x="1555.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1566,-1163 1566,-1393 "/>
<text text-anchor="middle" x="1651.5" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1566,-1370 1737,-1370 "/>
<text text-anchor="middle" x="1651.5" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1566,-1347 1737,-1347 "/>
<text text-anchor="middle" x="1651.5" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1566,-1324 1737,-1324 "/>
<text text-anchor="middle" x="1651.5" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1566,-1301 1737,-1301 "/>
<text text-anchor="middle" x="1651.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1566,-1278 1737,-1278 "/>
<text text-anchor="middle" x="1651.5" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1566,-1255 1737,-1255 "/>
<text text-anchor="middle" x="1651.5" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1566,-1232 1737,-1232 "/>
<text text-anchor="middle" x="1651.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1566,-1209 1737,-1209 "/>
<text text-anchor="middle" x="1651.5" y="-1193.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="1566,-1186 1737,-1186 "/>
<text text-anchor="middle" x="1651.5" y="-1170.8" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="1737,-1163 1737,-1393 "/>
<text text-anchor="middle" x="1747.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1562.0286,-1162.733C1561.6583,-1072.206 1561.1524,-948.5094 1560.8259,-868.6797"/>
<polygon fill="#000000" stroke="#000000" points="1564.324,-868.185 1560.783,-858.1994 1557.324,-868.2137 1564.324,-868.185"/>
<text text-anchor="middle" x="1653" y="-960.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study_arm -->
<g id="node6" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M1719,-317C1719,-317 2016,-317 2016,-317 2022,-317 2028,-323 2028,-329 2028,-329 2028,-374 2028,-374 2028,-380 2022,-386 2016,-386 2016,-386 1719,-386 1719,-386 1713,-386 1707,-380 1707,-374 1707,-374 1707,-329 1707,-329 1707,-323 1713,-317 1719,-317"/>
<text text-anchor="middle" x="1753" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="1799,-317 1799,-386 "/>
<text text-anchor="middle" x="1809.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1820,-317 1820,-386 "/>
<text text-anchor="middle" x="1913.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="1820,-363 2007,-363 "/>
<text text-anchor="middle" x="1913.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="1820,-340 2007,-340 "/>
<text text-anchor="middle" x="1913.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="2007,-317 2007,-386 "/>
<text text-anchor="middle" x="2017.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge13" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1881.7606,-316.8365C1895.6332,-287.7122 1919.5942,-247.4998 1953.5,-226 2040.6658,-170.7279 2300.4125,-137.5942 2490.9764,-120.0946"/>
<polygon fill="#000000" stroke="#000000" points="2491.4958,-123.5618 2501.1376,-119.1702 2490.8616,-116.5906 2491.4958,-123.5618"/>
<text text-anchor="middle" x="2002" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- imaging_file -->
<g id="node7" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M1788.5,-1117C1788.5,-1117 2122.5,-1117 2122.5,-1117 2128.5,-1117 2134.5,-1123 2134.5,-1129 2134.5,-1129 2134.5,-1427 2134.5,-1427 2134.5,-1433 2128.5,-1439 2122.5,-1439 2122.5,-1439 1788.5,-1439 1788.5,-1439 1782.5,-1439 1776.5,-1433 1776.5,-1427 1776.5,-1427 1776.5,-1129 1776.5,-1129 1776.5,-1123 1782.5,-1117 1788.5,-1117"/>
<text text-anchor="middle" x="1828.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="1880.5,-1117 1880.5,-1439 "/>
<text text-anchor="middle" x="1891" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1901.5,-1117 1901.5,-1439 "/>
<text text-anchor="middle" x="2007.5" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1901.5,-1416 2113.5,-1416 "/>
<text text-anchor="middle" x="2007.5" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1901.5,-1393 2113.5,-1393 "/>
<text text-anchor="middle" x="2007.5" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1901.5,-1370 2113.5,-1370 "/>
<text text-anchor="middle" x="2007.5" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1901.5,-1347 2113.5,-1347 "/>
<text text-anchor="middle" x="2007.5" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1901.5,-1324 2113.5,-1324 "/>
<text text-anchor="middle" x="2007.5" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1901.5,-1301 2113.5,-1301 "/>
<text text-anchor="middle" x="2007.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1901.5,-1278 2113.5,-1278 "/>
<text text-anchor="middle" x="2007.5" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1901.5,-1255 2113.5,-1255 "/>
<text text-anchor="middle" x="2007.5" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1901.5,-1232 2113.5,-1232 "/>
<text text-anchor="middle" x="2007.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="1901.5,-1209 2113.5,-1209 "/>
<text text-anchor="middle" x="2007.5" y="-1193.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="1901.5,-1186 2113.5,-1186 "/>
<text text-anchor="middle" x="2007.5" y="-1170.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="1901.5,-1163 2113.5,-1163 "/>
<text text-anchor="middle" x="2007.5" y="-1147.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1901.5,-1140 2113.5,-1140 "/>
<text text-anchor="middle" x="2007.5" y="-1124.8" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="2113.5,-1117 2113.5,-1439 "/>
<text text-anchor="middle" x="2124" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1863.4952,-1116.9234C1830.127,-1063.8283 1790.2876,-1005.8995 1748.5,-957 1720.7118,-924.4825 1686.7453,-892.3112 1655.366,-864.9599"/>
<polygon fill="#000000" stroke="#000000" points="1657.3024,-862.0072 1647.4493,-858.1127 1652.7232,-867.3016 1657.3024,-862.0072"/>
<text text-anchor="middle" x="1810" y="-960.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge18" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2059.4856,-495.3504C2052.8513,-424.6596 2045.0568,-294.0572 2073.5,-259 2126.1987,-194.0471 2328.7625,-152.5027 2491.1224,-128.9454"/>
<polygon fill="#000000" stroke="#000000" points="2491.8647,-132.3748 2501.2659,-127.4893 2490.87,-125.4458 2491.8647,-132.3748"/>
<text text-anchor="middle" x="2124" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge19" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1972.4959,-495.4008C1964.339,-489.7115 1956.5242,-483.5647 1949.5,-477 1924.4958,-453.6315 1903.5437,-421.1575 1889.078,-395.0977"/>
<polygon fill="#000000" stroke="#000000" points="1892.0811,-393.2936 1884.2358,-386.1731 1885.9284,-396.6318 1892.0811,-393.2936"/>
<text text-anchor="middle" x="2000" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- pdx -->
<g id="node9" class="node">
<title>pdx</title>
<path fill="none" stroke="#000000" d="M12,-1174.5C12,-1174.5 341,-1174.5 341,-1174.5 347,-1174.5 353,-1180.5 353,-1186.5 353,-1186.5 353,-1369.5 353,-1369.5 353,-1375.5 347,-1381.5 341,-1381.5 341,-1381.5 12,-1381.5 12,-1381.5 6,-1381.5 0,-1375.5 0,-1369.5 0,-1369.5 0,-1186.5 0,-1186.5 0,-1180.5 6,-1174.5 12,-1174.5"/>
<text text-anchor="middle" x="21.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
<polyline fill="none" stroke="#000000" points="43,-1174.5 43,-1381.5 "/>
<text text-anchor="middle" x="53.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="64,-1174.5 64,-1381.5 "/>
<text text-anchor="middle" x="198" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">injection_type_and_site</text>
<polyline fill="none" stroke="#000000" points="64,-1358.5 332,-1358.5 "/>
<text text-anchor="middle" x="198" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_id</text>
<polyline fill="none" stroke="#000000" points="64,-1335.5 332,-1335.5 "/>
<text text-anchor="middle" x="198" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_type</text>
<polyline fill="none" stroke="#000000" points="64,-1312.5 332,-1312.5 "/>
<text text-anchor="middle" x="198" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">mouse_strain</text>
<polyline fill="none" stroke="#000000" points="64,-1289.5 332,-1289.5 "/>
<text text-anchor="middle" x="198" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">strain_immune_system_humanized</text>
<polyline fill="none" stroke="#000000" points="64,-1266.5 332,-1266.5 "/>
<text text-anchor="middle" x="198" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_characterization_method</text>
<polyline fill="none" stroke="#000000" points="64,-1243.5 332,-1243.5 "/>
<text text-anchor="middle" x="198" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_not_mus_or_ebv_origin</text>
<polyline fill="none" stroke="#000000" points="64,-1220.5 332,-1220.5 "/>
<text text-anchor="middle" x="198" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_preparation</text>
<polyline fill="none" stroke="#000000" points="64,-1197.5 332,-1197.5 "/>
<text text-anchor="middle" x="198" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_humanization</text>
<polyline fill="none" stroke="#000000" points="332,-1174.5 332,-1381.5 "/>
<text text-anchor="middle" x="342.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M217.0364,-1174.3393C247.271,-1110.9771 294.8958,-1033.9186 361.5,-990 526.0626,-881.488 1088.7845,-824.3189 1381.0417,-801.3375"/>
<polygon fill="#000000" stroke="#000000" points="1381.6259,-804.8026 1391.323,-800.5344 1381.0807,-797.8239 1381.6259,-804.8026"/>
<text text-anchor="middle" x="434.5" y="-960.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study_personnel -->
<g id="node10" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M2196,-294C2196,-294 2503,-294 2503,-294 2509,-294 2515,-300 2515,-306 2515,-306 2515,-397 2515,-397 2515,-403 2509,-409 2503,-409 2503,-409 2196,-409 2196,-409 2190,-409 2184,-403 2184,-397 2184,-397 2184,-306 2184,-306 2184,-300 2190,-294 2196,-294"/>
<text text-anchor="middle" x="2251" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="2318,-294 2318,-409 "/>
<text text-anchor="middle" x="2328.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2339,-294 2339,-409 "/>
<text text-anchor="middle" x="2416.5" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="2339,-386 2494,-386 "/>
<text text-anchor="middle" x="2416.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="2339,-363 2494,-363 "/>
<text text-anchor="middle" x="2416.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="2339,-340 2494,-340 "/>
<text text-anchor="middle" x="2416.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="2339,-317 2494,-317 "/>
<text text-anchor="middle" x="2416.5" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="2494,-294 2494,-409 "/>
<text text-anchor="middle" x="2504.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2433.2165,-293.7846C2468.0101,-269.7973 2509.5941,-241.1287 2549.7711,-213.4301"/>
<polygon fill="#000000" stroke="#000000" points="2551.8057,-216.2786 2558.0522,-207.721 2547.8325,-210.5155 2551.8057,-216.2786"/>
<text text-anchor="middle" x="2599" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- study_admin -->
<g id="node11" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M2545.5,-259.5C2545.5,-259.5 2871.5,-259.5 2871.5,-259.5 2877.5,-259.5 2883.5,-265.5 2883.5,-271.5 2883.5,-271.5 2883.5,-431.5 2883.5,-431.5 2883.5,-437.5 2877.5,-443.5 2871.5,-443.5 2871.5,-443.5 2545.5,-443.5 2545.5,-443.5 2539.5,-443.5 2533.5,-437.5 2533.5,-431.5 2533.5,-431.5 2533.5,-271.5 2533.5,-271.5 2533.5,-265.5 2539.5,-259.5 2545.5,-259.5"/>
<text text-anchor="middle" x="2587.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="2641.5,-259.5 2641.5,-443.5 "/>
<text text-anchor="middle" x="2652" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2662.5,-259.5 2662.5,-443.5 "/>
<text text-anchor="middle" x="2762.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="2662.5,-420.5 2862.5,-420.5 "/>
<text text-anchor="middle" x="2762.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="2662.5,-397.5 2862.5,-397.5 "/>
<text text-anchor="middle" x="2762.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="2662.5,-374.5 2862.5,-374.5 "/>
<text text-anchor="middle" x="2762.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="2662.5,-351.5 2862.5,-351.5 "/>
<text text-anchor="middle" x="2762.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="2662.5,-328.5 2862.5,-328.5 "/>
<text text-anchor="middle" x="2762.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="2662.5,-305.5 2862.5,-305.5 "/>
<text text-anchor="middle" x="2762.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="2662.5,-282.5 2862.5,-282.5 "/>
<text text-anchor="middle" x="2762.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="2862.5,-259.5 2862.5,-443.5 "/>
<text text-anchor="middle" x="2873" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge20" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2708.5,-259.3401C2708.5,-245.8477 2708.5,-231.8183 2708.5,-217.9539"/>
<polygon fill="#000000" stroke="#000000" points="2712.0001,-217.8977 2708.5,-207.8977 2705.0001,-217.8977 2712.0001,-217.8977"/>
<text text-anchor="middle" x="2765" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- therapeutic_procedure -->
<g id="node12" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M2307,-731.5C2307,-731.5 2664,-731.5 2664,-731.5 2670,-731.5 2676,-737.5 2676,-743.5 2676,-743.5 2676,-834.5 2676,-834.5 2676,-840.5 2670,-846.5 2664,-846.5 2664,-846.5 2307,-846.5 2307,-846.5 2301,-846.5 2295,-840.5 2295,-834.5 2295,-834.5 2295,-743.5 2295,-743.5 2295,-737.5 2301,-731.5 2307,-731.5"/>
<text text-anchor="middle" x="2385.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="2476,-731.5 2476,-846.5 "/>
<text text-anchor="middle" x="2486.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2497,-731.5 2497,-846.5 "/>
<text text-anchor="middle" x="2576" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="2497,-823.5 2655,-823.5 "/>
<text text-anchor="middle" x="2576" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="2497,-800.5 2655,-800.5 "/>
<text text-anchor="middle" x="2576" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="2497,-777.5 2655,-777.5 "/>
<text text-anchor="middle" x="2576" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="2497,-754.5 2655,-754.5 "/>
<text text-anchor="middle" x="2576" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="2655,-731.5 2655,-846.5 "/>
<text text-anchor="middle" x="2665.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2414.4727,-731.368C2376.1156,-701.7258 2327.1699,-666.2101 2280.5,-639 2251.2232,-621.9307 2218.4247,-605.7518 2187.4016,-591.6576"/>
<polygon fill="#000000" stroke="#000000" points="2188.8267,-588.4609 2178.2715,-587.5458 2185.9523,-594.8435 2188.8267,-588.4609"/>
<text text-anchor="middle" x="2340.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge2" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1556.2476,-719.7614C1553.3616,-605.434 1565.8353,-378.0166 1697.5,-259 1810.9751,-156.4257 2229.6092,-121.7124 2491.272,-109.9781"/>
<polygon fill="#000000" stroke="#000000" points="2491.4508,-113.4737 2501.287,-109.5368 2491.1426,-106.4805 2491.4508,-113.4737"/>
<text text-anchor="middle" x="1619" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1629.144,-719.6712C1660.3298,-691.3584 1699.0358,-660.3256 1738.5,-639 1796.8386,-607.4751 1866.6949,-584.8505 1926.7519,-569.3821"/>
<polygon fill="#000000" stroke="#000000" points="1927.8532,-572.7137 1936.6873,-566.8649 1926.134,-565.9281 1927.8532,-572.7137"/>
<text text-anchor="middle" x="1843" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- clinical_measure_file -->
<g id="node14" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M2706.5,-662.5C2706.5,-662.5 3058.5,-662.5 3058.5,-662.5 3064.5,-662.5 3070.5,-668.5 3070.5,-674.5 3070.5,-674.5 3070.5,-903.5 3070.5,-903.5 3070.5,-909.5 3064.5,-915.5 3058.5,-915.5 3058.5,-915.5 2706.5,-915.5 2706.5,-915.5 2700.5,-915.5 2694.5,-909.5 2694.5,-903.5 2694.5,-903.5 2694.5,-674.5 2694.5,-674.5 2694.5,-668.5 2700.5,-662.5 2706.5,-662.5"/>
<text text-anchor="middle" x="2778" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="2861.5,-662.5 2861.5,-915.5 "/>
<text text-anchor="middle" x="2872" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2882.5,-662.5 2882.5,-915.5 "/>
<text text-anchor="middle" x="2966" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2882.5,-892.5 3049.5,-892.5 "/>
<text text-anchor="middle" x="2966" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2882.5,-869.5 3049.5,-869.5 "/>
<text text-anchor="middle" x="2966" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2882.5,-846.5 3049.5,-846.5 "/>
<text text-anchor="middle" x="2966" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2882.5,-823.5 3049.5,-823.5 "/>
<text text-anchor="middle" x="2966" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2882.5,-800.5 3049.5,-800.5 "/>
<text text-anchor="middle" x="2966" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2882.5,-777.5 3049.5,-777.5 "/>
<text text-anchor="middle" x="2966" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2882.5,-754.5 3049.5,-754.5 "/>
<text text-anchor="middle" x="2966" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2882.5,-731.5 3049.5,-731.5 "/>
<text text-anchor="middle" x="2966" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2882.5,-708.5 3049.5,-708.5 "/>
<text text-anchor="middle" x="2966" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2882.5,-685.5 3049.5,-685.5 "/>
<text text-anchor="middle" x="2966" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="3049.5,-662.5 3049.5,-915.5 "/>
<text text-anchor="middle" x="3060" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge5" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2897.469,-662.4056C2911.0699,-528.7226 2924.5694,-327.9466 2892.5,-259 2885.2845,-243.4873 2875.6675,-228.9707 2864.602,-215.5284"/>
<polygon fill="#000000" stroke="#000000" points="2867.0914,-213.0545 2857.9267,-207.7385 2861.776,-217.6094 2867.0914,-213.0545"/>
<text text-anchor="middle" x="2997.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2729.9608,-662.4016C2715.137,-653.5383 2699.8779,-645.5408 2684.5,-639 2599.9376,-603.0325 2357.6562,-572.1349 2202.1992,-555.2404"/>
<polygon fill="#000000" stroke="#000000" points="2202.4058,-551.7424 2192.0877,-554.1479 2201.6539,-558.7019 2202.4058,-551.7424"/>
<text text-anchor="middle" x="2754" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- sequencing_file -->
<g id="node15" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M383,-990.5C383,-990.5 852,-990.5 852,-990.5 858,-990.5 864,-996.5 864,-1002.5 864,-1002.5 864,-1553.5 864,-1553.5 864,-1559.5 858,-1565.5 852,-1565.5 852,-1565.5 383,-1565.5 383,-1565.5 377,-1565.5 371,-1559.5 371,-1553.5 371,-1553.5 371,-1002.5 371,-1002.5 371,-996.5 377,-990.5 383,-990.5"/>
<text text-anchor="middle" x="435" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="499,-990.5 499,-1565.5 "/>
<text text-anchor="middle" x="509.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="520,-990.5 520,-1565.5 "/>
<text text-anchor="middle" x="681.5" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="520,-1542.5 843,-1542.5 "/>
<text text-anchor="middle" x="681.5" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="520,-1519.5 843,-1519.5 "/>
<text text-anchor="middle" x="681.5" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="520,-1496.5 843,-1496.5 "/>
<text text-anchor="middle" x="681.5" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="520,-1473.5 843,-1473.5 "/>
<text text-anchor="middle" x="681.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="520,-1450.5 843,-1450.5 "/>
<text text-anchor="middle" x="681.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="520,-1427.5 843,-1427.5 "/>
<text text-anchor="middle" x="681.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="520,-1404.5 843,-1404.5 "/>
<text text-anchor="middle" x="681.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="520,-1381.5 843,-1381.5 "/>
<text text-anchor="middle" x="681.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="520,-1358.5 843,-1358.5 "/>
<text text-anchor="middle" x="681.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="520,-1335.5 843,-1335.5 "/>
<text text-anchor="middle" x="681.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="520,-1312.5 843,-1312.5 "/>
<text text-anchor="middle" x="681.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="520,-1289.5 843,-1289.5 "/>
<text text-anchor="middle" x="681.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="520,-1266.5 843,-1266.5 "/>
<text text-anchor="middle" x="681.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="520,-1243.5 843,-1243.5 "/>
<text text-anchor="middle" x="681.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="520,-1220.5 843,-1220.5 "/>
<text text-anchor="middle" x="681.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="520,-1197.5 843,-1197.5 "/>
<text text-anchor="middle" x="681.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="520,-1174.5 843,-1174.5 "/>
<text text-anchor="middle" x="681.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="520,-1151.5 843,-1151.5 "/>
<text text-anchor="middle" x="681.5" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="520,-1128.5 843,-1128.5 "/>
<text text-anchor="middle" x="681.5" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="520,-1105.5 843,-1105.5 "/>
<text text-anchor="middle" x="681.5" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="520,-1082.5 843,-1082.5 "/>
<text text-anchor="middle" x="681.5" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="520,-1059.5 843,-1059.5 "/>
<text text-anchor="middle" x="681.5" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="520,-1036.5 843,-1036.5 "/>
<text text-anchor="middle" x="681.5" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="520,-1013.5 843,-1013.5 "/>
<text text-anchor="middle" x="681.5" y="-998.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="843,-990.5 843,-1565.5 "/>
<text text-anchor="middle" x="853.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M864.2208,-996.0464C867.2979,-993.9846 870.3912,-991.9681 873.5,-990 1029.5124,-891.2306 1235.858,-839.4026 1381.5512,-813.2985"/>
<polygon fill="#000000" stroke="#000000" points="1382.2589,-816.7277 1391.4965,-811.5396 1381.0398,-809.8347 1382.2589,-816.7277"/>
<text text-anchor="middle" x="990" y="-960.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- publication -->
<g id="node16" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M3138.5,-333.5C3138.5,-333.5 3348.5,-333.5 3348.5,-333.5 3354.5,-333.5 3360.5,-339.5 3360.5,-345.5 3360.5,-345.5 3360.5,-357.5 3360.5,-357.5 3360.5,-363.5 3354.5,-369.5 3348.5,-369.5 3348.5,-369.5 3138.5,-369.5 3138.5,-369.5 3132.5,-369.5 3126.5,-363.5 3126.5,-357.5 3126.5,-357.5 3126.5,-345.5 3126.5,-345.5 3126.5,-339.5 3132.5,-333.5 3138.5,-333.5"/>
<text text-anchor="middle" x="3175" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="3223.5,-333.5 3223.5,-369.5 "/>
<text text-anchor="middle" x="3234" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3244.5,-333.5 3244.5,-369.5 "/>
<text text-anchor="middle" x="3292" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="3339.5,-333.5 3339.5,-369.5 "/>
<text text-anchor="middle" x="3350" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge11" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3229.3979,-333.35C3207.3276,-306.1451 3161.9979,-254.9097 3112.5,-226 3055.3314,-192.6102 2988.1863,-167.5918 2925.2302,-149.1951"/>
<polygon fill="#000000" stroke="#000000" points="2926.1477,-145.8171 2915.5697,-146.414 2924.2111,-152.5439 2926.1477,-145.8171"/>
<text text-anchor="middle" x="3183.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- study_funding -->
<g id="node17" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M3391,-317C3391,-317 3770,-317 3770,-317 3776,-317 3782,-323 3782,-329 3782,-329 3782,-374 3782,-374 3782,-380 3776,-386 3770,-386 3770,-386 3391,-386 3391,-386 3385,-386 3379,-380 3379,-374 3379,-374 3379,-329 3379,-329 3379,-323 3385,-317 3391,-317"/>
<text text-anchor="middle" x="3438.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="3498,-317 3498,-386 "/>
<text text-anchor="middle" x="3508.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3519,-317 3519,-386 "/>
<text text-anchor="middle" x="3640" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="3519,-363 3761,-363 "/>
<text text-anchor="middle" x="3640" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="3519,-340 3761,-340 "/>
<text text-anchor="middle" x="3640" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="3761,-317 3761,-386 "/>
<text text-anchor="middle" x="3771.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge15" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3509.4122,-316.7986C3469.0374,-297.9922 3417.178,-275.329 3369.5,-259 3224.5483,-209.3561 3056.3759,-170.164 2925.9368,-143.6091"/>
<polygon fill="#000000" stroke="#000000" points="2926.3159,-140.1149 2915.82,-141.5594 2924.9259,-146.9755 2926.3159,-140.1149"/>
<text text-anchor="middle" x="3360.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
</g>
</svg>
</div>
