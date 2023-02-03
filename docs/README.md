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
<svg width="3591pt" height="1597pt"
 viewBox="0.00 0.00 3591.00 1597.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1593)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1593 3587,-1593 3587,4 -4,4"/>
<!-- study -->
<g id="node1" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M2361,-.5C2361,-.5 2751,-.5 2751,-.5 2757,-.5 2763,-6.5 2763,-12.5 2763,-12.5 2763,-195.5 2763,-195.5 2763,-201.5 2757,-207.5 2751,-207.5 2751,-207.5 2361,-207.5 2361,-207.5 2355,-207.5 2349,-201.5 2349,-195.5 2349,-195.5 2349,-12.5 2349,-12.5 2349,-6.5 2355,-.5 2361,-.5"/>
<text text-anchor="middle" x="2377" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="2405,-.5 2405,-207.5 "/>
<text text-anchor="middle" x="2415.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2426,-.5 2426,-207.5 "/>
<text text-anchor="middle" x="2584" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="2426,-184.5 2742,-184.5 "/>
<text text-anchor="middle" x="2584" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="2426,-161.5 2742,-161.5 "/>
<text text-anchor="middle" x="2584" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="2426,-138.5 2742,-138.5 "/>
<text text-anchor="middle" x="2584" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="2426,-115.5 2742,-115.5 "/>
<text text-anchor="middle" x="2584" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="2426,-92.5 2742,-92.5 "/>
<text text-anchor="middle" x="2584" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="2426,-69.5 2742,-69.5 "/>
<text text-anchor="middle" x="2584" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="2426,-46.5 2742,-46.5 "/>
<text text-anchor="middle" x="2584" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="2426,-23.5 2742,-23.5 "/>
<text text-anchor="middle" x="2584" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="2742,-.5 2742,-207.5 "/>
<text text-anchor="middle" x="2752.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure -->
<g id="node2" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M2257.5,-754.5C2257.5,-754.5 2614.5,-754.5 2614.5,-754.5 2620.5,-754.5 2626.5,-760.5 2626.5,-766.5 2626.5,-766.5 2626.5,-857.5 2626.5,-857.5 2626.5,-863.5 2620.5,-869.5 2614.5,-869.5 2614.5,-869.5 2257.5,-869.5 2257.5,-869.5 2251.5,-869.5 2245.5,-863.5 2245.5,-857.5 2245.5,-857.5 2245.5,-766.5 2245.5,-766.5 2245.5,-760.5 2251.5,-754.5 2257.5,-754.5"/>
<text text-anchor="middle" x="2336" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="2426.5,-754.5 2426.5,-869.5 "/>
<text text-anchor="middle" x="2437" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2447.5,-754.5 2447.5,-869.5 "/>
<text text-anchor="middle" x="2526.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="2447.5,-846.5 2605.5,-846.5 "/>
<text text-anchor="middle" x="2526.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="2447.5,-823.5 2605.5,-823.5 "/>
<text text-anchor="middle" x="2526.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="2447.5,-800.5 2605.5,-800.5 "/>
<text text-anchor="middle" x="2526.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="2447.5,-777.5 2605.5,-777.5 "/>
<text text-anchor="middle" x="2526.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="2605.5,-754.5 2605.5,-869.5 "/>
<text text-anchor="middle" x="2616" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node10" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M1990,-495.5C1990,-495.5 2294,-495.5 2294,-495.5 2300,-495.5 2306,-501.5 2306,-507.5 2306,-507.5 2306,-598.5 2306,-598.5 2306,-604.5 2300,-610.5 2294,-610.5 2294,-610.5 1990,-610.5 1990,-610.5 1984,-610.5 1978,-604.5 1978,-598.5 1978,-598.5 1978,-507.5 1978,-507.5 1978,-501.5 1984,-495.5 1990,-495.5"/>
<text text-anchor="middle" x="2026" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="2074,-495.5 2074,-610.5 "/>
<text text-anchor="middle" x="2084.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2095,-495.5 2095,-610.5 "/>
<text text-anchor="middle" x="2190" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="2095,-587.5 2285,-587.5 "/>
<text text-anchor="middle" x="2190" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="2095,-564.5 2285,-564.5 "/>
<text text-anchor="middle" x="2190" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="2095,-541.5 2285,-541.5 "/>
<text text-anchor="middle" x="2190" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="2095,-518.5 2285,-518.5 "/>
<text text-anchor="middle" x="2190" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="2285,-495.5 2285,-610.5 "/>
<text text-anchor="middle" x="2295.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2370.3866,-754.1977C2324.2825,-713.5822 2262.582,-659.227 2214.9347,-617.252"/>
<polygon fill="#000000" stroke="#000000" points="2217.2301,-614.6097 2207.4129,-610.6256 2212.6028,-619.8622 2217.2301,-614.6097"/>
<text text-anchor="middle" x="2331" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- diagnosis -->
<g id="node3" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1710.5,-662.5C1710.5,-662.5 2093.5,-662.5 2093.5,-662.5 2099.5,-662.5 2105.5,-668.5 2105.5,-674.5 2105.5,-674.5 2105.5,-949.5 2105.5,-949.5 2105.5,-955.5 2099.5,-961.5 2093.5,-961.5 2093.5,-961.5 1710.5,-961.5 1710.5,-961.5 1704.5,-961.5 1698.5,-955.5 1698.5,-949.5 1698.5,-949.5 1698.5,-674.5 1698.5,-674.5 1698.5,-668.5 1704.5,-662.5 1710.5,-662.5"/>
<text text-anchor="middle" x="1740.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1782.5,-662.5 1782.5,-961.5 "/>
<text text-anchor="middle" x="1793" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1803.5,-662.5 1803.5,-961.5 "/>
<text text-anchor="middle" x="1944" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1803.5,-938.5 2084.5,-938.5 "/>
<text text-anchor="middle" x="1944" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1803.5,-915.5 2084.5,-915.5 "/>
<text text-anchor="middle" x="1944" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1803.5,-892.5 2084.5,-892.5 "/>
<text text-anchor="middle" x="1944" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1803.5,-869.5 2084.5,-869.5 "/>
<text text-anchor="middle" x="1944" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1803.5,-846.5 2084.5,-846.5 "/>
<text text-anchor="middle" x="1944" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="1803.5,-823.5 2084.5,-823.5 "/>
<text text-anchor="middle" x="1944" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1803.5,-800.5 2084.5,-800.5 "/>
<text text-anchor="middle" x="1944" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1803.5,-777.5 2084.5,-777.5 "/>
<text text-anchor="middle" x="1944" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis_reference_source</text>
<polyline fill="none" stroke="#000000" points="1803.5,-754.5 2084.5,-754.5 "/>
<text text-anchor="middle" x="1944" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="1803.5,-731.5 2084.5,-731.5 "/>
<text text-anchor="middle" x="1944" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="1803.5,-708.5 2084.5,-708.5 "/>
<text text-anchor="middle" x="1944" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="1803.5,-685.5 2084.5,-685.5 "/>
<text text-anchor="middle" x="1944" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="2084.5,-662.5 2084.5,-961.5 "/>
<text text-anchor="middle" x="2095" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2008.3662,-662.0806C2018.3113,-650.5264 2028.5806,-639.3473 2039,-629 2042.9421,-625.0852 2047.0965,-621.2101 2051.3842,-617.4045"/>
<polygon fill="#000000" stroke="#000000" points="2053.9443,-619.8184 2059.229,-610.6357 2049.3713,-614.5186 2053.9443,-619.8184"/>
<text text-anchor="middle" x="2083.5" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- synonym -->
<g id="node4" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M2164.5,-1278C2164.5,-1278 2465.5,-1278 2465.5,-1278 2471.5,-1278 2477.5,-1284 2477.5,-1290 2477.5,-1290 2477.5,-1312 2477.5,-1312 2477.5,-1318 2471.5,-1324 2465.5,-1324 2465.5,-1324 2164.5,-1324 2164.5,-1324 2158.5,-1324 2152.5,-1318 2152.5,-1312 2152.5,-1312 2152.5,-1290 2152.5,-1290 2152.5,-1284 2158.5,-1278 2164.5,-1278"/>
<text text-anchor="middle" x="2192.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="2232.5,-1278 2232.5,-1324 "/>
<text text-anchor="middle" x="2243" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2253.5,-1278 2253.5,-1324 "/>
<text text-anchor="middle" x="2355" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="2253.5,-1301 2456.5,-1301 "/>
<text text-anchor="middle" x="2355" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="2456.5,-1278 2456.5,-1324 "/>
<text text-anchor="middle" x="2467" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge6" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2477.722,-1284.9347C2734.5435,-1249.6175 3205,-1140.1392 3205,-812 3205,-812 3205,-812 3205,-351.5 3205,-309.5306 3215.0978,-289.2448 3186,-259 3128.9667,-199.7185 2931.9178,-157.625 2773.199,-132.4048"/>
<polygon fill="#000000" stroke="#000000" points="2773.7045,-128.9414 2763.2817,-130.8429 2772.6154,-135.8561 2773.7045,-128.9414"/>
<text text-anchor="middle" x="3247.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2299.2847,-1277.6814C2264.4898,-1224.5266 2181.6107,-1089.1256 2151,-962 2122.7378,-844.6279 2128.0391,-702.8043 2134.7926,-620.7465"/>
<polygon fill="#000000" stroke="#000000" points="2138.2995,-620.8142 2135.6646,-610.5523 2131.325,-620.2176 2138.2995,-620.8142"/>
<text text-anchor="middle" x="2193.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- sample -->
<g id="node12" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1354,-731.5C1354,-731.5 1668,-731.5 1668,-731.5 1674,-731.5 1680,-737.5 1680,-743.5 1680,-743.5 1680,-880.5 1680,-880.5 1680,-886.5 1674,-892.5 1668,-892.5 1668,-892.5 1354,-892.5 1354,-892.5 1348,-892.5 1342,-886.5 1342,-880.5 1342,-880.5 1342,-743.5 1342,-743.5 1342,-737.5 1348,-731.5 1354,-731.5"/>
<text text-anchor="middle" x="1376" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1410,-731.5 1410,-892.5 "/>
<text text-anchor="middle" x="1420.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1431,-731.5 1431,-892.5 "/>
<text text-anchor="middle" x="1545" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="1431,-869.5 1659,-869.5 "/>
<text text-anchor="middle" x="1545" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1431,-846.5 1659,-846.5 "/>
<text text-anchor="middle" x="1545" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1431,-823.5 1659,-823.5 "/>
<text text-anchor="middle" x="1545" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1431,-800.5 1659,-800.5 "/>
<text text-anchor="middle" x="1545" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1431,-777.5 1659,-777.5 "/>
<text text-anchor="middle" x="1545" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1431,-754.5 1659,-754.5 "/>
<text text-anchor="middle" x="1545" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="1659,-731.5 1659,-892.5 "/>
<text text-anchor="middle" x="1669.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2308.8235,-1277.7483C2292.5101,-1221.376 2242.5307,-1077.3379 2143,-1013 2116.2281,-995.6943 1889.6831,-983.5215 1858,-980 1782.9263,-971.6558 1758.4795,-991.6357 1689,-962 1654.6827,-947.3623 1621.9677,-923.7744 1594.1623,-899.5953"/>
<polygon fill="#000000" stroke="#000000" points="1596.2593,-896.7771 1586.4528,-892.7668 1591.618,-902.0173 1596.2593,-896.7771"/>
<text text-anchor="middle" x="2083.5" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- sequencing_file -->
<g id="node5" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M1276.5,-1013.5C1276.5,-1013.5 1745.5,-1013.5 1745.5,-1013.5 1751.5,-1013.5 1757.5,-1019.5 1757.5,-1025.5 1757.5,-1025.5 1757.5,-1576.5 1757.5,-1576.5 1757.5,-1582.5 1751.5,-1588.5 1745.5,-1588.5 1745.5,-1588.5 1276.5,-1588.5 1276.5,-1588.5 1270.5,-1588.5 1264.5,-1582.5 1264.5,-1576.5 1264.5,-1576.5 1264.5,-1025.5 1264.5,-1025.5 1264.5,-1019.5 1270.5,-1013.5 1276.5,-1013.5"/>
<text text-anchor="middle" x="1328.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="1392.5,-1013.5 1392.5,-1588.5 "/>
<text text-anchor="middle" x="1403" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1413.5,-1013.5 1413.5,-1588.5 "/>
<text text-anchor="middle" x="1575" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="1413.5,-1565.5 1736.5,-1565.5 "/>
<text text-anchor="middle" x="1575" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1413.5,-1542.5 1736.5,-1542.5 "/>
<text text-anchor="middle" x="1575" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1413.5,-1519.5 1736.5,-1519.5 "/>
<text text-anchor="middle" x="1575" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="1413.5,-1496.5 1736.5,-1496.5 "/>
<text text-anchor="middle" x="1575" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="1413.5,-1473.5 1736.5,-1473.5 "/>
<text text-anchor="middle" x="1575" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1413.5,-1450.5 1736.5,-1450.5 "/>
<text text-anchor="middle" x="1575" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="1413.5,-1427.5 1736.5,-1427.5 "/>
<text text-anchor="middle" x="1575" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1413.5,-1404.5 1736.5,-1404.5 "/>
<text text-anchor="middle" x="1575" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1413.5,-1381.5 1736.5,-1381.5 "/>
<text text-anchor="middle" x="1575" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1413.5,-1358.5 1736.5,-1358.5 "/>
<text text-anchor="middle" x="1575" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1413.5,-1335.5 1736.5,-1335.5 "/>
<text text-anchor="middle" x="1575" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1413.5,-1312.5 1736.5,-1312.5 "/>
<text text-anchor="middle" x="1575" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1413.5,-1289.5 1736.5,-1289.5 "/>
<text text-anchor="middle" x="1575" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="1413.5,-1266.5 1736.5,-1266.5 "/>
<text text-anchor="middle" x="1575" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="1413.5,-1243.5 1736.5,-1243.5 "/>
<text text-anchor="middle" x="1575" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="1413.5,-1220.5 1736.5,-1220.5 "/>
<text text-anchor="middle" x="1575" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="1413.5,-1197.5 1736.5,-1197.5 "/>
<text text-anchor="middle" x="1575" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="1413.5,-1174.5 1736.5,-1174.5 "/>
<text text-anchor="middle" x="1575" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="1413.5,-1151.5 1736.5,-1151.5 "/>
<text text-anchor="middle" x="1575" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1413.5,-1128.5 1736.5,-1128.5 "/>
<text text-anchor="middle" x="1575" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="1413.5,-1105.5 1736.5,-1105.5 "/>
<text text-anchor="middle" x="1575" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="1413.5,-1082.5 1736.5,-1082.5 "/>
<text text-anchor="middle" x="1575" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="1413.5,-1059.5 1736.5,-1059.5 "/>
<text text-anchor="middle" x="1575" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="1413.5,-1036.5 1736.5,-1036.5 "/>
<text text-anchor="middle" x="1575" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="1736.5,-1013.5 1736.5,-1588.5 "/>
<text text-anchor="middle" x="1747" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1511,-1013.365C1511,-973.4615 1511,-935.1409 1511,-902.8379"/>
<polygon fill="#000000" stroke="#000000" points="1514.5001,-902.5669 1511,-892.567 1507.5001,-902.567 1514.5001,-902.5669"/>
<text text-anchor="middle" x="1577.5" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- publication -->
<g id="node6" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M1669,-333.5C1669,-333.5 1879,-333.5 1879,-333.5 1885,-333.5 1891,-339.5 1891,-345.5 1891,-345.5 1891,-357.5 1891,-357.5 1891,-363.5 1885,-369.5 1879,-369.5 1879,-369.5 1669,-369.5 1669,-369.5 1663,-369.5 1657,-363.5 1657,-357.5 1657,-357.5 1657,-345.5 1657,-345.5 1657,-339.5 1663,-333.5 1669,-333.5"/>
<text text-anchor="middle" x="1705.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="1754,-333.5 1754,-369.5 "/>
<text text-anchor="middle" x="1764.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1775,-333.5 1775,-369.5 "/>
<text text-anchor="middle" x="1822.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="1870,-333.5 1870,-369.5 "/>
<text text-anchor="middle" x="1880.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge13" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1773.7078,-333.4161C1774.3198,-305.8201 1779.8362,-253.5102 1811,-226 1887.6199,-158.363 2147.3866,-127.8575 2338.7108,-114.3444"/>
<polygon fill="#000000" stroke="#000000" points="2339.1803,-117.8203 2348.9135,-113.6352 2338.6949,-110.8371 2339.1803,-117.8203"/>
<text text-anchor="middle" x="1862" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- study_arm -->
<g id="node7" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M2407.5,-317C2407.5,-317 2704.5,-317 2704.5,-317 2710.5,-317 2716.5,-323 2716.5,-329 2716.5,-329 2716.5,-374 2716.5,-374 2716.5,-380 2710.5,-386 2704.5,-386 2704.5,-386 2407.5,-386 2407.5,-386 2401.5,-386 2395.5,-380 2395.5,-374 2395.5,-374 2395.5,-329 2395.5,-329 2395.5,-323 2401.5,-317 2407.5,-317"/>
<text text-anchor="middle" x="2441.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="2487.5,-317 2487.5,-386 "/>
<text text-anchor="middle" x="2498" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2508.5,-317 2508.5,-386 "/>
<text text-anchor="middle" x="2602" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="2508.5,-363 2695.5,-363 "/>
<text text-anchor="middle" x="2602" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="2508.5,-340 2695.5,-340 "/>
<text text-anchor="middle" x="2602" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="2695.5,-317 2695.5,-386 "/>
<text text-anchor="middle" x="2706" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge16" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2556,-316.8256C2556,-290.8629 2556,-253.7725 2556,-217.8091"/>
<polygon fill="#000000" stroke="#000000" points="2559.5001,-217.7056 2556,-207.7056 2552.5001,-217.7056 2559.5001,-217.7056"/>
<text text-anchor="middle" x="2604.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- imaging_file -->
<g id="node8" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M1788,-1140C1788,-1140 2122,-1140 2122,-1140 2128,-1140 2134,-1146 2134,-1152 2134,-1152 2134,-1450 2134,-1450 2134,-1456 2128,-1462 2122,-1462 2122,-1462 1788,-1462 1788,-1462 1782,-1462 1776,-1456 1776,-1450 1776,-1450 1776,-1152 1776,-1152 1776,-1146 1782,-1140 1788,-1140"/>
<text text-anchor="middle" x="1828" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="1880,-1140 1880,-1462 "/>
<text text-anchor="middle" x="1890.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1901,-1140 1901,-1462 "/>
<text text-anchor="middle" x="2007" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1901,-1439 2113,-1439 "/>
<text text-anchor="middle" x="2007" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1901,-1416 2113,-1416 "/>
<text text-anchor="middle" x="2007" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1901,-1393 2113,-1393 "/>
<text text-anchor="middle" x="2007" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1901,-1370 2113,-1370 "/>
<text text-anchor="middle" x="2007" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1901,-1347 2113,-1347 "/>
<text text-anchor="middle" x="2007" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1901,-1324 2113,-1324 "/>
<text text-anchor="middle" x="2007" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1901,-1301 2113,-1301 "/>
<text text-anchor="middle" x="2007" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1901,-1278 2113,-1278 "/>
<text text-anchor="middle" x="2007" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1901,-1255 2113,-1255 "/>
<text text-anchor="middle" x="2007" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="1901,-1232 2113,-1232 "/>
<text text-anchor="middle" x="2007" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="1901,-1209 2113,-1209 "/>
<text text-anchor="middle" x="2007" y="-1193.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="1901,-1186 2113,-1186 "/>
<text text-anchor="middle" x="2007" y="-1170.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1901,-1163 2113,-1163 "/>
<text text-anchor="middle" x="2007" y="-1147.8" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="2113,-1140 2113,-1462 "/>
<text text-anchor="middle" x="2123.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1865.6232,-1139.8794C1837.0727,-1095.9782 1803.135,-1050.2929 1766,-1013 1737.0363,-983.9132 1721.8601,-986.5998 1689,-962 1662.9068,-942.466 1635.5864,-920.3512 1610.4023,-899.2208"/>
<polygon fill="#000000" stroke="#000000" points="1612.5621,-896.4638 1602.6589,-892.6986 1608.0526,-901.8177 1612.5621,-896.4638"/>
<text text-anchor="middle" x="1799.5" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- study_personnel -->
<g id="node9" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M2058.5,-294C2058.5,-294 2365.5,-294 2365.5,-294 2371.5,-294 2377.5,-300 2377.5,-306 2377.5,-306 2377.5,-397 2377.5,-397 2377.5,-403 2371.5,-409 2365.5,-409 2365.5,-409 2058.5,-409 2058.5,-409 2052.5,-409 2046.5,-403 2046.5,-397 2046.5,-397 2046.5,-306 2046.5,-306 2046.5,-300 2052.5,-294 2058.5,-294"/>
<text text-anchor="middle" x="2113.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="2180.5,-294 2180.5,-409 "/>
<text text-anchor="middle" x="2191" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2201.5,-294 2201.5,-409 "/>
<text text-anchor="middle" x="2279" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="2201.5,-386 2356.5,-386 "/>
<text text-anchor="middle" x="2279" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="2201.5,-363 2356.5,-363 "/>
<text text-anchor="middle" x="2279" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="2201.5,-340 2356.5,-340 "/>
<text text-anchor="middle" x="2279" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="2201.5,-317 2356.5,-317 "/>
<text text-anchor="middle" x="2279" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="2356.5,-294 2356.5,-409 "/>
<text text-anchor="middle" x="2367" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge7" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2292.2186,-293.7846C2325.4889,-269.8474 2365.2386,-241.2484 2403.6621,-213.6036"/>
<polygon fill="#000000" stroke="#000000" points="2405.765,-216.4024 2411.8383,-207.721 2401.6768,-210.7202 2405.765,-216.4024"/>
<text text-anchor="middle" x="2453.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge18" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1986.1646,-495.3803C1966.1951,-481.5486 1948.4202,-464.6236 1936,-444 1893.5814,-373.5645 1885.3994,-323.808 1936,-259 1985.8182,-195.194 2180.2844,-153.7671 2338.3123,-129.9379"/>
<polygon fill="#000000" stroke="#000000" points="2339.2924,-133.3305 2348.6667,-128.3937 2338.2598,-126.4071 2339.2924,-133.3305"/>
<text text-anchor="middle" x="1986.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge19" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M2275.8453,-495.4682C2311.8739,-479.3691 2350.6493,-461.4801 2386,-444 2419.4439,-427.4628 2455.8585,-407.8689 2486.3749,-390.9812"/>
<polygon fill="#000000" stroke="#000000" points="2488.1866,-393.9786 2495.2309,-386.0648 2484.789,-387.8585 2488.1866,-393.9786"/>
<text text-anchor="middle" x="2397.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sample_diagnosis -->
<g id="node11" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M12,-1082.5C12,-1082.5 454,-1082.5 454,-1082.5 460,-1082.5 466,-1088.5 466,-1094.5 466,-1094.5 466,-1507.5 466,-1507.5 466,-1513.5 460,-1519.5 454,-1519.5 454,-1519.5 12,-1519.5 12,-1519.5 6,-1519.5 0,-1513.5 0,-1507.5 0,-1507.5 0,-1094.5 0,-1094.5 0,-1088.5 6,-1082.5 12,-1082.5"/>
<text text-anchor="middle" x="71.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="143,-1082.5 143,-1519.5 "/>
<text text-anchor="middle" x="153.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="164,-1082.5 164,-1519.5 "/>
<text text-anchor="middle" x="304.5" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="164,-1496.5 445,-1496.5 "/>
<text text-anchor="middle" x="304.5" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="164,-1473.5 445,-1473.5 "/>
<text text-anchor="middle" x="304.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="164,-1450.5 445,-1450.5 "/>
<text text-anchor="middle" x="304.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="164,-1427.5 445,-1427.5 "/>
<text text-anchor="middle" x="304.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="164,-1404.5 445,-1404.5 "/>
<text text-anchor="middle" x="304.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="164,-1381.5 445,-1381.5 "/>
<text text-anchor="middle" x="304.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="164,-1358.5 445,-1358.5 "/>
<text text-anchor="middle" x="304.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis_reference_source</text>
<polyline fill="none" stroke="#000000" points="164,-1335.5 445,-1335.5 "/>
<text text-anchor="middle" x="304.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="164,-1312.5 445,-1312.5 "/>
<text text-anchor="middle" x="304.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="164,-1289.5 445,-1289.5 "/>
<text text-anchor="middle" x="304.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="164,-1266.5 445,-1266.5 "/>
<text text-anchor="middle" x="304.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="164,-1243.5 445,-1243.5 "/>
<text text-anchor="middle" x="304.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="164,-1220.5 445,-1220.5 "/>
<text text-anchor="middle" x="304.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="164,-1197.5 445,-1197.5 "/>
<text text-anchor="middle" x="304.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="164,-1174.5 445,-1174.5 "/>
<text text-anchor="middle" x="304.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="164,-1151.5 445,-1151.5 "/>
<text text-anchor="middle" x="304.5" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="164,-1128.5 445,-1128.5 "/>
<text text-anchor="middle" x="304.5" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="164,-1105.5 445,-1105.5 "/>
<text text-anchor="middle" x="304.5" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="445,-1082.5 445,-1519.5 "/>
<text text-anchor="middle" x="455.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M387.6081,-1082.2724C414.1673,-1055.7587 443.4783,-1031.5456 475,-1013 617.6331,-929.0828 1074.8483,-863.5104 1331.6441,-832.1795"/>
<polygon fill="#000000" stroke="#000000" points="1332.3229,-835.6229 1341.8277,-830.9422 1331.4786,-828.674 1332.3229,-835.6229"/>
<text text-anchor="middle" x="609" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge21" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1506.4352,-731.1268C1504.3493,-610.603 1519.4024,-384.6148 1648,-259 1743.6507,-165.5679 2101.775,-128.0614 2338.6562,-113.2841"/>
<polygon fill="#000000" stroke="#000000" points="2339.021,-116.7684 2348.7874,-112.6613 2338.5915,-109.7816 2339.021,-116.7684"/>
<text text-anchor="middle" x="1573.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1590.7722,-731.1487C1619.6401,-705.7757 1653.8381,-679.7808 1689,-662 1775.71,-618.1522 1880.784,-591.4546 1967.8976,-575.4667"/>
<polygon fill="#000000" stroke="#000000" points="1968.6672,-578.8845 1977.8875,-573.6656 1967.4251,-571.9956 1968.6672,-578.8845"/>
<text text-anchor="middle" x="1795.5" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node13" class="node">
<title>pdx</title>
<path fill="none" stroke="#000000" d="M496.5,-1197.5C496.5,-1197.5 825.5,-1197.5 825.5,-1197.5 831.5,-1197.5 837.5,-1203.5 837.5,-1209.5 837.5,-1209.5 837.5,-1392.5 837.5,-1392.5 837.5,-1398.5 831.5,-1404.5 825.5,-1404.5 825.5,-1404.5 496.5,-1404.5 496.5,-1404.5 490.5,-1404.5 484.5,-1398.5 484.5,-1392.5 484.5,-1392.5 484.5,-1209.5 484.5,-1209.5 484.5,-1203.5 490.5,-1197.5 496.5,-1197.5"/>
<text text-anchor="middle" x="506" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
<polyline fill="none" stroke="#000000" points="527.5,-1197.5 527.5,-1404.5 "/>
<text text-anchor="middle" x="538" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="548.5,-1197.5 548.5,-1404.5 "/>
<text text-anchor="middle" x="682.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">injection_type_and_site</text>
<polyline fill="none" stroke="#000000" points="548.5,-1381.5 816.5,-1381.5 "/>
<text text-anchor="middle" x="682.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_id</text>
<polyline fill="none" stroke="#000000" points="548.5,-1358.5 816.5,-1358.5 "/>
<text text-anchor="middle" x="682.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_type</text>
<polyline fill="none" stroke="#000000" points="548.5,-1335.5 816.5,-1335.5 "/>
<text text-anchor="middle" x="682.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">mouse_strain</text>
<polyline fill="none" stroke="#000000" points="548.5,-1312.5 816.5,-1312.5 "/>
<text text-anchor="middle" x="682.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">strain_immune_system_humanized</text>
<polyline fill="none" stroke="#000000" points="548.5,-1289.5 816.5,-1289.5 "/>
<text text-anchor="middle" x="682.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_characterization_method</text>
<polyline fill="none" stroke="#000000" points="548.5,-1266.5 816.5,-1266.5 "/>
<text text-anchor="middle" x="682.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_not_mus_or_ebv_origin</text>
<polyline fill="none" stroke="#000000" points="548.5,-1243.5 816.5,-1243.5 "/>
<text text-anchor="middle" x="682.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_preparation</text>
<polyline fill="none" stroke="#000000" points="548.5,-1220.5 816.5,-1220.5 "/>
<text text-anchor="middle" x="682.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_humanization</text>
<polyline fill="none" stroke="#000000" points="816.5,-1197.5 816.5,-1404.5 "/>
<text text-anchor="middle" x="827" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M704.9237,-1197.3656C735.9862,-1135.6425 783.2758,-1060.3542 846,-1013 988.4134,-905.4837 1188.3273,-855.1066 1331.7135,-831.7346"/>
<polygon fill="#000000" stroke="#000000" points="1332.617,-835.1346 1341.9381,-830.098 1331.5106,-828.2226 1332.617,-835.1346"/>
<text text-anchor="middle" x="917" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study_funding -->
<g id="node14" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M2785.5,-317C2785.5,-317 3164.5,-317 3164.5,-317 3170.5,-317 3176.5,-323 3176.5,-329 3176.5,-329 3176.5,-374 3176.5,-374 3176.5,-380 3170.5,-386 3164.5,-386 3164.5,-386 2785.5,-386 2785.5,-386 2779.5,-386 2773.5,-380 2773.5,-374 2773.5,-374 2773.5,-329 2773.5,-329 2773.5,-323 2779.5,-317 2785.5,-317"/>
<text text-anchor="middle" x="2833" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="2892.5,-317 2892.5,-386 "/>
<text text-anchor="middle" x="2903" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2913.5,-317 2913.5,-386 "/>
<text text-anchor="middle" x="3034.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="2913.5,-363 3155.5,-363 "/>
<text text-anchor="middle" x="3034.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="2913.5,-340 3155.5,-340 "/>
<text text-anchor="middle" x="3034.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="3155.5,-317 3155.5,-386 "/>
<text text-anchor="middle" x="3166" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge3" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2916.2987,-316.8256C2870.3734,-289.6979 2803.8812,-250.4215 2740.4882,-212.9757"/>
<polygon fill="#000000" stroke="#000000" points="2741.9564,-209.778 2731.5662,-207.7056 2738.3963,-215.8051 2741.9564,-209.778"/>
<text text-anchor="middle" x="2840" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- clinical_measure_file -->
<g id="node15" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M2657,-685.5C2657,-685.5 3009,-685.5 3009,-685.5 3015,-685.5 3021,-691.5 3021,-697.5 3021,-697.5 3021,-926.5 3021,-926.5 3021,-932.5 3015,-938.5 3009,-938.5 3009,-938.5 2657,-938.5 2657,-938.5 2651,-938.5 2645,-932.5 2645,-926.5 2645,-926.5 2645,-697.5 2645,-697.5 2645,-691.5 2651,-685.5 2657,-685.5"/>
<text text-anchor="middle" x="2728.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="2812,-685.5 2812,-938.5 "/>
<text text-anchor="middle" x="2822.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2833,-685.5 2833,-938.5 "/>
<text text-anchor="middle" x="2916.5" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2833,-915.5 3000,-915.5 "/>
<text text-anchor="middle" x="2916.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2833,-892.5 3000,-892.5 "/>
<text text-anchor="middle" x="2916.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2833,-869.5 3000,-869.5 "/>
<text text-anchor="middle" x="2916.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2833,-846.5 3000,-846.5 "/>
<text text-anchor="middle" x="2916.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2833,-823.5 3000,-823.5 "/>
<text text-anchor="middle" x="2916.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2833,-800.5 3000,-800.5 "/>
<text text-anchor="middle" x="2916.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2833,-777.5 3000,-777.5 "/>
<text text-anchor="middle" x="2916.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2833,-754.5 3000,-754.5 "/>
<text text-anchor="middle" x="2916.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2833,-731.5 3000,-731.5 "/>
<text text-anchor="middle" x="2916.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2833,-708.5 3000,-708.5 "/>
<text text-anchor="middle" x="2916.5" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="3000,-685.5 3000,-938.5 "/>
<text text-anchor="middle" x="3010.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge11" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2809.2991,-685.4652C2779.1253,-525.1482 2730.2485,-268.3672 2725,-259 2716.3796,-243.615 2705.6825,-228.9135 2693.8853,-215.1195"/>
<polygon fill="#000000" stroke="#000000" points="2696.4585,-212.7455 2687.2244,-207.5509 2691.2037,-217.3701 2696.4585,-212.7455"/>
<text text-anchor="middle" x="2854" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2682.2167,-685.4785C2666.8762,-676.4367 2651.025,-668.385 2635,-662 2567.2917,-635.0225 2543.1397,-659.8536 2472,-644 2451.834,-639.506 2447.7733,-634.9899 2428,-629 2392.004,-618.0958 2353.207,-607.2129 2316.1545,-597.231"/>
<polygon fill="#000000" stroke="#000000" points="2316.8318,-593.789 2306.2664,-594.5772 2315.0173,-600.5497 2316.8318,-593.789"/>
<text text-anchor="middle" x="2601.5" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- study_admin -->
<g id="node16" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M3245,-259.5C3245,-259.5 3571,-259.5 3571,-259.5 3577,-259.5 3583,-265.5 3583,-271.5 3583,-271.5 3583,-431.5 3583,-431.5 3583,-437.5 3577,-443.5 3571,-443.5 3571,-443.5 3245,-443.5 3245,-443.5 3239,-443.5 3233,-437.5 3233,-431.5 3233,-431.5 3233,-271.5 3233,-271.5 3233,-265.5 3239,-259.5 3245,-259.5"/>
<text text-anchor="middle" x="3287" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="3341,-259.5 3341,-443.5 "/>
<text text-anchor="middle" x="3351.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3362,-259.5 3362,-443.5 "/>
<text text-anchor="middle" x="3462" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="3362,-420.5 3562,-420.5 "/>
<text text-anchor="middle" x="3462" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="3362,-397.5 3562,-397.5 "/>
<text text-anchor="middle" x="3462" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="3362,-374.5 3562,-374.5 "/>
<text text-anchor="middle" x="3462" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="3362,-351.5 3562,-351.5 "/>
<text text-anchor="middle" x="3462" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="3362,-328.5 3562,-328.5 "/>
<text text-anchor="middle" x="3462" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="3362,-305.5 3562,-305.5 "/>
<text text-anchor="middle" x="3462" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="3362,-282.5 3562,-282.5 "/>
<text text-anchor="middle" x="3462" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="3562,-259.5 3562,-443.5 "/>
<text text-anchor="middle" x="3572.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3284.5932,-259.4941C3263.4837,-246.7437 3241.1847,-234.9658 3219,-226 3076.6273,-168.4611 2906.0351,-137.8553 2773.5488,-121.6892"/>
<polygon fill="#000000" stroke="#000000" points="2773.619,-118.1725 2763.2729,-120.4549 2772.7841,-125.1226 2773.619,-118.1725"/>
<text text-anchor="middle" x="3303.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- methylation_array_file -->
<g id="node17" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M867.5,-1186C867.5,-1186 1234.5,-1186 1234.5,-1186 1240.5,-1186 1246.5,-1192 1246.5,-1198 1246.5,-1198 1246.5,-1404 1246.5,-1404 1246.5,-1410 1240.5,-1416 1234.5,-1416 1234.5,-1416 867.5,-1416 867.5,-1416 861.5,-1416 855.5,-1410 855.5,-1404 855.5,-1404 855.5,-1198 855.5,-1198 855.5,-1192 861.5,-1186 867.5,-1186"/>
<text text-anchor="middle" x="944.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="1033.5,-1186 1033.5,-1416 "/>
<text text-anchor="middle" x="1044" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1054.5,-1186 1054.5,-1416 "/>
<text text-anchor="middle" x="1140" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1054.5,-1393 1225.5,-1393 "/>
<text text-anchor="middle" x="1140" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1054.5,-1370 1225.5,-1370 "/>
<text text-anchor="middle" x="1140" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1054.5,-1347 1225.5,-1347 "/>
<text text-anchor="middle" x="1140" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1054.5,-1324 1225.5,-1324 "/>
<text text-anchor="middle" x="1140" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1054.5,-1301 1225.5,-1301 "/>
<text text-anchor="middle" x="1140" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1054.5,-1278 1225.5,-1278 "/>
<text text-anchor="middle" x="1140" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1054.5,-1255 1225.5,-1255 "/>
<text text-anchor="middle" x="1140" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1054.5,-1232 1225.5,-1232 "/>
<text text-anchor="middle" x="1140" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="1054.5,-1209 1225.5,-1209 "/>
<text text-anchor="middle" x="1140" y="-1193.8" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="1225.5,-1186 1225.5,-1416 "/>
<text text-anchor="middle" x="1236" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1121.4724,-1185.8139C1157.9143,-1130.6512 1205.1513,-1065.3703 1255,-1013 1294.2435,-971.7714 1342.2393,-931.8681 1386.0238,-898.6303"/>
<polygon fill="#000000" stroke="#000000" points="1388.2715,-901.319 1394.1473,-892.5028 1384.0561,-895.7305 1388.2715,-901.319"/>
<text text-anchor="middle" x="1378.5" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
</g>
</svg>
</div>
