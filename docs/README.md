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
<svg width="3827pt" height="1712pt"
 viewBox="0.00 0.00 3826.50 1712.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1708)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1708 3822.5,-1708 3822.5,4 -4,4"/>
<!-- sample -->
<g id="node1" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1228.5,-812C1228.5,-812 1542.5,-812 1542.5,-812 1548.5,-812 1554.5,-818 1554.5,-824 1554.5,-824 1554.5,-961 1554.5,-961 1554.5,-967 1548.5,-973 1542.5,-973 1542.5,-973 1228.5,-973 1228.5,-973 1222.5,-973 1216.5,-967 1216.5,-961 1216.5,-961 1216.5,-824 1216.5,-824 1216.5,-818 1222.5,-812 1228.5,-812"/>
<text text-anchor="middle" x="1250.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1284.5,-812 1284.5,-973 "/>
<text text-anchor="middle" x="1295" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1305.5,-812 1305.5,-973 "/>
<text text-anchor="middle" x="1419.5" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="1305.5,-950 1533.5,-950 "/>
<text text-anchor="middle" x="1419.5" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1305.5,-927 1533.5,-927 "/>
<text text-anchor="middle" x="1419.5" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1305.5,-904 1533.5,-904 "/>
<text text-anchor="middle" x="1419.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1305.5,-881 1533.5,-881 "/>
<text text-anchor="middle" x="1419.5" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1305.5,-858 1533.5,-858 "/>
<text text-anchor="middle" x="1419.5" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1305.5,-835 1533.5,-835 "/>
<text text-anchor="middle" x="1419.5" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="1533.5,-812 1533.5,-973 "/>
<text text-anchor="middle" x="1544" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node2" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M1854.5,-541.5C1854.5,-541.5 2158.5,-541.5 2158.5,-541.5 2164.5,-541.5 2170.5,-547.5 2170.5,-553.5 2170.5,-553.5 2170.5,-644.5 2170.5,-644.5 2170.5,-650.5 2164.5,-656.5 2158.5,-656.5 2158.5,-656.5 1854.5,-656.5 1854.5,-656.5 1848.5,-656.5 1842.5,-650.5 1842.5,-644.5 1842.5,-644.5 1842.5,-553.5 1842.5,-553.5 1842.5,-547.5 1848.5,-541.5 1854.5,-541.5"/>
<text text-anchor="middle" x="1890.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1938.5,-541.5 1938.5,-656.5 "/>
<text text-anchor="middle" x="1949" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1959.5,-541.5 1959.5,-656.5 "/>
<text text-anchor="middle" x="2054.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="1959.5,-633.5 2149.5,-633.5 "/>
<text text-anchor="middle" x="2054.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="1959.5,-610.5 2149.5,-610.5 "/>
<text text-anchor="middle" x="2054.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="1959.5,-587.5 2149.5,-587.5 "/>
<text text-anchor="middle" x="2054.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1959.5,-564.5 2149.5,-564.5 "/>
<text text-anchor="middle" x="2054.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="2149.5,-541.5 2149.5,-656.5 "/>
<text text-anchor="middle" x="2160" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1445.6272,-811.8333C1476.9585,-775.0975 1518.1752,-734.0894 1563.5,-708 1645.2942,-660.9185 1746.9212,-634.0509 1832.1976,-618.7801"/>
<polygon fill="#000000" stroke="#000000" points="1833.0013,-622.1927 1842.2477,-617.0202 1831.7939,-615.2976 1833.0013,-622.1927"/>
<text text-anchor="middle" x="1666" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study -->
<g id="node16" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M2531.5,-.5C2531.5,-.5 2921.5,-.5 2921.5,-.5 2927.5,-.5 2933.5,-6.5 2933.5,-12.5 2933.5,-12.5 2933.5,-264.5 2933.5,-264.5 2933.5,-270.5 2927.5,-276.5 2921.5,-276.5 2921.5,-276.5 2531.5,-276.5 2531.5,-276.5 2525.5,-276.5 2519.5,-270.5 2519.5,-264.5 2519.5,-264.5 2519.5,-12.5 2519.5,-12.5 2519.5,-6.5 2525.5,-.5 2531.5,-.5"/>
<text text-anchor="middle" x="2547.5" y="-134.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="2575.5,-.5 2575.5,-276.5 "/>
<text text-anchor="middle" x="2586" y="-134.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2596.5,-.5 2596.5,-276.5 "/>
<text text-anchor="middle" x="2754.5" y="-261.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="2596.5,-253.5 2912.5,-253.5 "/>
<text text-anchor="middle" x="2754.5" y="-238.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="2596.5,-230.5 2912.5,-230.5 "/>
<text text-anchor="middle" x="2754.5" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_shorthand</text>
<polyline fill="none" stroke="#000000" points="2596.5,-207.5 2912.5,-207.5 "/>
<text text-anchor="middle" x="2754.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="2596.5,-184.5 2912.5,-184.5 "/>
<text text-anchor="middle" x="2754.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="2596.5,-161.5 2912.5,-161.5 "/>
<text text-anchor="middle" x="2754.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="2596.5,-138.5 2912.5,-138.5 "/>
<text text-anchor="middle" x="2754.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="2596.5,-115.5 2912.5,-115.5 "/>
<text text-anchor="middle" x="2754.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="2596.5,-92.5 2912.5,-92.5 "/>
<text text-anchor="middle" x="2754.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="2596.5,-69.5 2912.5,-69.5 "/>
<text text-anchor="middle" x="2754.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="2596.5,-46.5 2912.5,-46.5 "/>
<text text-anchor="middle" x="2754.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="2596.5,-23.5 2912.5,-23.5 "/>
<text text-anchor="middle" x="2754.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="2912.5,-.5 2912.5,-276.5 "/>
<text text-anchor="middle" x="2923" y="-134.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge3" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1422.3056,-811.8128C1483.6984,-686.9153 1619.3029,-448.6223 1809.5,-328 1923.6091,-255.6324 2276.1964,-197.3435 2509.4267,-165.3644"/>
<polygon fill="#000000" stroke="#000000" points="2509.9671,-168.8231 2519.4018,-164.0027 2509.0203,-161.8875 2509.9671,-168.8231"/>
<text text-anchor="middle" x="1646" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_arm -->
<g id="node4" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M1830,-374.5C1830,-374.5 2127,-374.5 2127,-374.5 2133,-374.5 2139,-380.5 2139,-386.5 2139,-386.5 2139,-431.5 2139,-431.5 2139,-437.5 2133,-443.5 2127,-443.5 2127,-443.5 1830,-443.5 1830,-443.5 1824,-443.5 1818,-437.5 1818,-431.5 1818,-431.5 1818,-386.5 1818,-386.5 1818,-380.5 1824,-374.5 1830,-374.5"/>
<text text-anchor="middle" x="1864" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="1910,-374.5 1910,-443.5 "/>
<text text-anchor="middle" x="1920.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1931,-374.5 1931,-443.5 "/>
<text text-anchor="middle" x="2024.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="1931,-420.5 2118,-420.5 "/>
<text text-anchor="middle" x="2024.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="1931,-397.5 2118,-397.5 "/>
<text text-anchor="middle" x="2024.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="2118,-374.5 2118,-443.5 "/>
<text text-anchor="middle" x="2128.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge5" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1998.0231,-541.4781C1993.8739,-513.3226 1988.9538,-479.9365 1985.0909,-453.7239"/>
<polygon fill="#000000" stroke="#000000" points="1988.5334,-453.0764 1983.6127,-443.6935 1981.6082,-454.097 1988.5334,-453.0764"/>
<text text-anchor="middle" x="2045" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge6" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2100.9365,-541.4101C2118.9796,-526.6322 2136.0831,-509.3579 2148.5,-490 2188.3747,-427.8355 2136.2925,-383.0731 2185.5,-328 2230.4182,-277.7275 2379.3209,-227.5898 2509.5623,-191.5251"/>
<polygon fill="#000000" stroke="#000000" points="2510.5905,-194.8724 2519.3032,-188.8442 2508.7329,-188.1233 2510.5905,-194.8724"/>
<text text-anchor="middle" x="2236" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- imaging_file -->
<g id="node3" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M421.5,-1255C421.5,-1255 755.5,-1255 755.5,-1255 761.5,-1255 767.5,-1261 767.5,-1267 767.5,-1267 767.5,-1565 767.5,-1565 767.5,-1571 761.5,-1577 755.5,-1577 755.5,-1577 421.5,-1577 421.5,-1577 415.5,-1577 409.5,-1571 409.5,-1565 409.5,-1565 409.5,-1267 409.5,-1267 409.5,-1261 415.5,-1255 421.5,-1255"/>
<text text-anchor="middle" x="461.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="513.5,-1255 513.5,-1577 "/>
<text text-anchor="middle" x="524" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="534.5,-1255 534.5,-1577 "/>
<text text-anchor="middle" x="640.5" y="-1561.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="534.5,-1554 746.5,-1554 "/>
<text text-anchor="middle" x="640.5" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="534.5,-1531 746.5,-1531 "/>
<text text-anchor="middle" x="640.5" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="534.5,-1508 746.5,-1508 "/>
<text text-anchor="middle" x="640.5" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="534.5,-1485 746.5,-1485 "/>
<text text-anchor="middle" x="640.5" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="534.5,-1462 746.5,-1462 "/>
<text text-anchor="middle" x="640.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="534.5,-1439 746.5,-1439 "/>
<text text-anchor="middle" x="640.5" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="534.5,-1416 746.5,-1416 "/>
<text text-anchor="middle" x="640.5" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="534.5,-1393 746.5,-1393 "/>
<text text-anchor="middle" x="640.5" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="534.5,-1370 746.5,-1370 "/>
<text text-anchor="middle" x="640.5" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="534.5,-1347 746.5,-1347 "/>
<text text-anchor="middle" x="640.5" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="534.5,-1324 746.5,-1324 "/>
<text text-anchor="middle" x="640.5" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="534.5,-1301 746.5,-1301 "/>
<text text-anchor="middle" x="640.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="534.5,-1278 746.5,-1278 "/>
<text text-anchor="middle" x="640.5" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="746.5,-1255 746.5,-1577 "/>
<text text-anchor="middle" x="757" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M669.6087,-1254.6874C698.6623,-1209.0012 734.9427,-1162.3997 777.5,-1128 902.7661,-1026.7455 1076.6194,-965.2945 1206.3465,-930.6813"/>
<polygon fill="#000000" stroke="#000000" points="1207.6178,-933.9658 1216.394,-928.0305 1205.832,-927.1974 1207.6178,-933.9658"/>
<text text-anchor="middle" x="874" y="-1098.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge12" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1996.0059,-374.3714C2010.8055,-348.6131 2034.3977,-314.6498 2064.5,-295 2137.3308,-247.4584 2345.4992,-202.8166 2509.1611,-173.4757"/>
<polygon fill="#000000" stroke="#000000" points="2510.1507,-176.8545 2519.3807,-171.6529 2508.9215,-169.9632 2510.1507,-176.8545"/>
<text text-anchor="middle" x="2113" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- study_funding -->
<g id="node5" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M2307,-374.5C2307,-374.5 2686,-374.5 2686,-374.5 2692,-374.5 2698,-380.5 2698,-386.5 2698,-386.5 2698,-431.5 2698,-431.5 2698,-437.5 2692,-443.5 2686,-443.5 2686,-443.5 2307,-443.5 2307,-443.5 2301,-443.5 2295,-437.5 2295,-431.5 2295,-431.5 2295,-386.5 2295,-386.5 2295,-380.5 2301,-374.5 2307,-374.5"/>
<text text-anchor="middle" x="2354.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="2414,-374.5 2414,-443.5 "/>
<text text-anchor="middle" x="2424.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2435,-374.5 2435,-443.5 "/>
<text text-anchor="middle" x="2556" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="2435,-420.5 2677,-420.5 "/>
<text text-anchor="middle" x="2556" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="2435,-397.5 2677,-397.5 "/>
<text text-anchor="middle" x="2556" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="2677,-374.5 2677,-443.5 "/>
<text text-anchor="middle" x="2687.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge4" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2523.8915,-374.2586C2541.9859,-351.5091 2566.3595,-321.2417 2588.5,-295 2591.4035,-291.5586 2594.3504,-288.0825 2597.3296,-284.5831"/>
<polygon fill="#000000" stroke="#000000" points="2600.0671,-286.7672 2603.899,-276.8896 2594.7437,-282.2216 2600.0671,-286.7672"/>
<text text-anchor="middle" x="2650.5" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- pdx -->
<g id="node6" class="node">
<title>pdx</title>
<path fill="none" stroke="#000000" d="M798,-1312.5C798,-1312.5 1127,-1312.5 1127,-1312.5 1133,-1312.5 1139,-1318.5 1139,-1324.5 1139,-1324.5 1139,-1507.5 1139,-1507.5 1139,-1513.5 1133,-1519.5 1127,-1519.5 1127,-1519.5 798,-1519.5 798,-1519.5 792,-1519.5 786,-1513.5 786,-1507.5 786,-1507.5 786,-1324.5 786,-1324.5 786,-1318.5 792,-1312.5 798,-1312.5"/>
<text text-anchor="middle" x="807.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
<polyline fill="none" stroke="#000000" points="829,-1312.5 829,-1519.5 "/>
<text text-anchor="middle" x="839.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="850,-1312.5 850,-1519.5 "/>
<text text-anchor="middle" x="984" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_site</text>
<polyline fill="none" stroke="#000000" points="850,-1496.5 1118,-1496.5 "/>
<text text-anchor="middle" x="984" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_type</text>
<polyline fill="none" stroke="#000000" points="850,-1473.5 1118,-1473.5 "/>
<text text-anchor="middle" x="984" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_id</text>
<polyline fill="none" stroke="#000000" points="850,-1450.5 1118,-1450.5 "/>
<text text-anchor="middle" x="984" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">mouse_strain</text>
<polyline fill="none" stroke="#000000" points="850,-1427.5 1118,-1427.5 "/>
<text text-anchor="middle" x="984" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">strain_immune_system_humanized</text>
<polyline fill="none" stroke="#000000" points="850,-1404.5 1118,-1404.5 "/>
<text text-anchor="middle" x="984" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_characterization_method</text>
<polyline fill="none" stroke="#000000" points="850,-1381.5 1118,-1381.5 "/>
<text text-anchor="middle" x="984" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_not_mus_or_ebv_origin</text>
<polyline fill="none" stroke="#000000" points="850,-1358.5 1118,-1358.5 "/>
<text text-anchor="middle" x="984" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_preparation</text>
<polyline fill="none" stroke="#000000" points="850,-1335.5 1118,-1335.5 "/>
<text text-anchor="middle" x="984" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_humanization</text>
<polyline fill="none" stroke="#000000" points="1118,-1312.5 1118,-1519.5 "/>
<text text-anchor="middle" x="1128.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1021.972,-1312.3484C1056.2151,-1255.8246 1101.6588,-1185.8053 1148.5,-1128 1190.7897,-1075.8116 1243.3158,-1022.6492 1288.1637,-980.0731"/>
<polygon fill="#000000" stroke="#000000" points="1290.7168,-982.476 1295.5793,-973.0629 1285.908,-977.3892 1290.7168,-982.476"/>
<text text-anchor="middle" x="1195.5" y="-1098.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- synonym -->
<g id="node7" class="node">
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
<!-- synonym&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2299.6634,-1392.9419C2283.9921,-1336.3611 2235.1904,-1190.7158 2134.5,-1128 2091.5476,-1101.2468 1957.9097,-1114.4162 1907.5,-1110 1902.7186,-1109.5811 1567.823,-1079.0855 1563.5,-1077 1518.5912,-1055.3353 1478.9003,-1017.3001 1448.4605,-981.3709"/>
<polygon fill="#000000" stroke="#000000" points="1450.8009,-978.7116 1441.7144,-973.263 1445.4199,-983.1888 1450.8009,-978.7116"/>
<text text-anchor="middle" x="1950" y="-1098.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2297.5113,-1392.9216C2277.9001,-1339.3791 2222.4761,-1205.3902 2134.5,-1128 2091.6024,-1090.2641 2048.3758,-1124.4145 2016.5,-1077 1972.7831,-1011.9722 1988.1101,-782.8693 1999.1687,-667.074"/>
<polygon fill="#000000" stroke="#000000" points="2002.673,-667.1984 2000.1566,-656.9067 1995.7058,-666.5214 2002.673,-667.1984"/>
<text text-anchor="middle" x="2059" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge9" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2401.4426,-1392.9597C2539.1519,-1354.1427 2787.9685,-1261.2306 2894.5,-1077 3021.1018,-858.0606 3014.2923,-726.8291 2887.5,-508 2879.8948,-494.8743 2868.1242,-501.726 2858.5,-490 2810.6083,-431.6494 2779.034,-354.1621 2758.8146,-286.7918"/>
<polygon fill="#000000" stroke="#000000" points="2762.0931,-285.5346 2755.9132,-276.9288 2755.3776,-287.5101 2762.0931,-285.5346"/>
<text text-anchor="middle" x="3001" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- clinical_measure_file -->
<g id="node8" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M2521.5,-766C2521.5,-766 2873.5,-766 2873.5,-766 2879.5,-766 2885.5,-772 2885.5,-778 2885.5,-778 2885.5,-1007 2885.5,-1007 2885.5,-1013 2879.5,-1019 2873.5,-1019 2873.5,-1019 2521.5,-1019 2521.5,-1019 2515.5,-1019 2509.5,-1013 2509.5,-1007 2509.5,-1007 2509.5,-778 2509.5,-778 2509.5,-772 2515.5,-766 2521.5,-766"/>
<text text-anchor="middle" x="2593" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="2676.5,-766 2676.5,-1019 "/>
<text text-anchor="middle" x="2687" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2697.5,-766 2697.5,-1019 "/>
<text text-anchor="middle" x="2781" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2697.5,-996 2864.5,-996 "/>
<text text-anchor="middle" x="2781" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2697.5,-973 2864.5,-973 "/>
<text text-anchor="middle" x="2781" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2697.5,-950 2864.5,-950 "/>
<text text-anchor="middle" x="2781" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2697.5,-927 2864.5,-927 "/>
<text text-anchor="middle" x="2781" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2697.5,-904 2864.5,-904 "/>
<text text-anchor="middle" x="2781" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2697.5,-881 2864.5,-881 "/>
<text text-anchor="middle" x="2781" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2697.5,-858 2864.5,-858 "/>
<text text-anchor="middle" x="2781" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2697.5,-835 2864.5,-835 "/>
<text text-anchor="middle" x="2781" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2697.5,-812 2864.5,-812 "/>
<text text-anchor="middle" x="2781" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2697.5,-789 2864.5,-789 "/>
<text text-anchor="middle" x="2781" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="2864.5,-766 2864.5,-1019 "/>
<text text-anchor="middle" x="2875" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2582.3208,-765.8176C2557.1994,-743.8642 2529.4161,-723.2348 2500.5,-708 2471.7466,-692.8509 2311.0927,-658.78 2180.6803,-632.733"/>
<polygon fill="#000000" stroke="#000000" points="2181.0435,-629.2366 2170.5522,-630.714 2179.675,-636.1015 2181.0435,-629.2366"/>
<text text-anchor="middle" x="2569" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge21" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2702.3703,-765.8723C2707.4502,-633.7958 2715.4079,-426.895 2720.7826,-287.1526"/>
<polygon fill="#000000" stroke="#000000" points="2724.2941,-286.917 2721.1812,-276.7899 2717.2993,-286.6479 2724.2941,-286.917"/>
<text text-anchor="middle" x="2797.5" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- sample_diagnosis -->
<g id="node9" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M1169,-1255C1169,-1255 1602,-1255 1602,-1255 1608,-1255 1614,-1261 1614,-1267 1614,-1267 1614,-1565 1614,-1565 1614,-1571 1608,-1577 1602,-1577 1602,-1577 1169,-1577 1169,-1577 1163,-1577 1157,-1571 1157,-1565 1157,-1565 1157,-1267 1157,-1267 1157,-1261 1163,-1255 1169,-1255"/>
<text text-anchor="middle" x="1228.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1300,-1255 1300,-1577 "/>
<text text-anchor="middle" x="1310.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1321,-1255 1321,-1577 "/>
<text text-anchor="middle" x="1457" y="-1561.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1321,-1554 1593,-1554 "/>
<text text-anchor="middle" x="1457" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1321,-1531 1593,-1531 "/>
<text text-anchor="middle" x="1457" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1321,-1508 1593,-1508 "/>
<text text-anchor="middle" x="1457" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1321,-1485 1593,-1485 "/>
<text text-anchor="middle" x="1457" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="1321,-1462 1593,-1462 "/>
<text text-anchor="middle" x="1457" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="1321,-1439 1593,-1439 "/>
<text text-anchor="middle" x="1457" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="1321,-1416 1593,-1416 "/>
<text text-anchor="middle" x="1457" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1321,-1393 1593,-1393 "/>
<text text-anchor="middle" x="1457" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1321,-1370 1593,-1370 "/>
<text text-anchor="middle" x="1457" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="1321,-1347 1593,-1347 "/>
<text text-anchor="middle" x="1457" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1321,-1324 1593,-1324 "/>
<text text-anchor="middle" x="1457" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1321,-1301 1593,-1301 "/>
<text text-anchor="middle" x="1457" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1321,-1278 1593,-1278 "/>
<text text-anchor="middle" x="1457" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1593,-1255 1593,-1577 "/>
<text text-anchor="middle" x="1603.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1385.5,-1254.6611C1385.5,-1165.5701 1385.5,-1058.1863 1385.5,-983.5881"/>
<polygon fill="#000000" stroke="#000000" points="1389.0001,-983.2848 1385.5,-973.2849 1382.0001,-983.2849 1389.0001,-983.2848"/>
<text text-anchor="middle" x="1459.5" y="-1098.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
<!-- sequencing_file -->
<g id="node10" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M1644,-1128.5C1644,-1128.5 2113,-1128.5 2113,-1128.5 2119,-1128.5 2125,-1134.5 2125,-1140.5 2125,-1140.5 2125,-1691.5 2125,-1691.5 2125,-1697.5 2119,-1703.5 2113,-1703.5 2113,-1703.5 1644,-1703.5 1644,-1703.5 1638,-1703.5 1632,-1697.5 1632,-1691.5 1632,-1691.5 1632,-1140.5 1632,-1140.5 1632,-1134.5 1638,-1128.5 1644,-1128.5"/>
<text text-anchor="middle" x="1696" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="1760,-1128.5 1760,-1703.5 "/>
<text text-anchor="middle" x="1770.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1781,-1128.5 1781,-1703.5 "/>
<text text-anchor="middle" x="1942.5" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="1781,-1680.5 2104,-1680.5 "/>
<text text-anchor="middle" x="1942.5" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1781,-1657.5 2104,-1657.5 "/>
<text text-anchor="middle" x="1942.5" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1781,-1634.5 2104,-1634.5 "/>
<text text-anchor="middle" x="1942.5" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="1781,-1611.5 2104,-1611.5 "/>
<text text-anchor="middle" x="1942.5" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="1781,-1588.5 2104,-1588.5 "/>
<text text-anchor="middle" x="1942.5" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1781,-1565.5 2104,-1565.5 "/>
<text text-anchor="middle" x="1942.5" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="1781,-1542.5 2104,-1542.5 "/>
<text text-anchor="middle" x="1942.5" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1781,-1519.5 2104,-1519.5 "/>
<text text-anchor="middle" x="1942.5" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1781,-1496.5 2104,-1496.5 "/>
<text text-anchor="middle" x="1942.5" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1781,-1473.5 2104,-1473.5 "/>
<text text-anchor="middle" x="1942.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1781,-1450.5 2104,-1450.5 "/>
<text text-anchor="middle" x="1942.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1781,-1427.5 2104,-1427.5 "/>
<text text-anchor="middle" x="1942.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1781,-1404.5 2104,-1404.5 "/>
<text text-anchor="middle" x="1942.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="1781,-1381.5 2104,-1381.5 "/>
<text text-anchor="middle" x="1942.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="1781,-1358.5 2104,-1358.5 "/>
<text text-anchor="middle" x="1942.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="1781,-1335.5 2104,-1335.5 "/>
<text text-anchor="middle" x="1942.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="1781,-1312.5 2104,-1312.5 "/>
<text text-anchor="middle" x="1942.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="1781,-1289.5 2104,-1289.5 "/>
<text text-anchor="middle" x="1942.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="1781,-1266.5 2104,-1266.5 "/>
<text text-anchor="middle" x="1942.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1781,-1243.5 2104,-1243.5 "/>
<text text-anchor="middle" x="1942.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="1781,-1220.5 2104,-1220.5 "/>
<text text-anchor="middle" x="1942.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="1781,-1197.5 2104,-1197.5 "/>
<text text-anchor="middle" x="1942.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="1781,-1174.5 2104,-1174.5 "/>
<text text-anchor="middle" x="1942.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="1781,-1151.5 2104,-1151.5 "/>
<text text-anchor="middle" x="1942.5" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="2104,-1128.5 2104,-1703.5 "/>
<text text-anchor="middle" x="2114.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1631.7424,-1136.1344C1628.9906,-1133.4 1626.2426,-1130.6877 1623.5,-1128 1598.5036,-1103.5037 1589.0145,-1100.9562 1563.5,-1077 1531.0578,-1046.5391 1496.8049,-1011.7284 1467.1045,-980.6121"/>
<polygon fill="#000000" stroke="#000000" points="1469.4823,-978.0338 1460.0524,-973.2039 1464.4122,-982.8601 1469.4823,-978.0338"/>
<text text-anchor="middle" x="1669" y="-1098.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- study_personnel -->
<g id="node11" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M2879,-351.5C2879,-351.5 3186,-351.5 3186,-351.5 3192,-351.5 3198,-357.5 3198,-363.5 3198,-363.5 3198,-454.5 3198,-454.5 3198,-460.5 3192,-466.5 3186,-466.5 3186,-466.5 2879,-466.5 2879,-466.5 2873,-466.5 2867,-460.5 2867,-454.5 2867,-454.5 2867,-363.5 2867,-363.5 2867,-357.5 2873,-351.5 2879,-351.5"/>
<text text-anchor="middle" x="2934" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="3001,-351.5 3001,-466.5 "/>
<text text-anchor="middle" x="3011.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3022,-351.5 3022,-466.5 "/>
<text text-anchor="middle" x="3099.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="3022,-443.5 3177,-443.5 "/>
<text text-anchor="middle" x="3099.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="3022,-420.5 3177,-420.5 "/>
<text text-anchor="middle" x="3099.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="3022,-397.5 3177,-397.5 "/>
<text text-anchor="middle" x="3099.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="3022,-374.5 3177,-374.5 "/>
<text text-anchor="middle" x="3099.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="3177,-351.5 3177,-466.5 "/>
<text text-anchor="middle" x="3187.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge15" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2967.2307,-351.3027C2944.448,-331.1632 2917.7456,-307.5586 2890.5749,-283.5401"/>
<polygon fill="#000000" stroke="#000000" points="2892.7123,-280.758 2882.9018,-276.7572 2888.0761,-286.0026 2892.7123,-280.758"/>
<text text-anchor="middle" x="2985" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- diagnosis -->
<g id="node12" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1584.5,-708.5C1584.5,-708.5 1958.5,-708.5 1958.5,-708.5 1964.5,-708.5 1970.5,-714.5 1970.5,-720.5 1970.5,-720.5 1970.5,-1064.5 1970.5,-1064.5 1970.5,-1070.5 1964.5,-1076.5 1958.5,-1076.5 1958.5,-1076.5 1584.5,-1076.5 1584.5,-1076.5 1578.5,-1076.5 1572.5,-1070.5 1572.5,-1064.5 1572.5,-1064.5 1572.5,-720.5 1572.5,-720.5 1572.5,-714.5 1578.5,-708.5 1584.5,-708.5"/>
<text text-anchor="middle" x="1614.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1656.5,-708.5 1656.5,-1076.5 "/>
<text text-anchor="middle" x="1667" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1677.5,-708.5 1677.5,-1076.5 "/>
<text text-anchor="middle" x="1813.5" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1677.5,-1053.5 1949.5,-1053.5 "/>
<text text-anchor="middle" x="1813.5" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1677.5,-1030.5 1949.5,-1030.5 "/>
<text text-anchor="middle" x="1813.5" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1677.5,-1007.5 1949.5,-1007.5 "/>
<text text-anchor="middle" x="1813.5" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1677.5,-984.5 1949.5,-984.5 "/>
<text text-anchor="middle" x="1813.5" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1677.5,-961.5 1949.5,-961.5 "/>
<text text-anchor="middle" x="1813.5" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="1677.5,-938.5 1949.5,-938.5 "/>
<text text-anchor="middle" x="1813.5" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="1677.5,-915.5 1949.5,-915.5 "/>
<text text-anchor="middle" x="1813.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="1677.5,-892.5 1949.5,-892.5 "/>
<text text-anchor="middle" x="1813.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1677.5,-869.5 1949.5,-869.5 "/>
<text text-anchor="middle" x="1813.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="1677.5,-846.5 1949.5,-846.5 "/>
<text text-anchor="middle" x="1813.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1677.5,-823.5 1949.5,-823.5 "/>
<text text-anchor="middle" x="1813.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1677.5,-800.5 1949.5,-800.5 "/>
<text text-anchor="middle" x="1813.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1677.5,-777.5 1949.5,-777.5 "/>
<text text-anchor="middle" x="1813.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1677.5,-754.5 1949.5,-754.5 "/>
<text text-anchor="middle" x="1813.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1677.5,-731.5 1949.5,-731.5 "/>
<text text-anchor="middle" x="1813.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="1949.5,-708.5 1949.5,-1076.5 "/>
<text text-anchor="middle" x="1960" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1875.9302,-708.3139C1884.7534,-696.6599 1893.9662,-685.4351 1903.5,-675 1907.0167,-671.1509 1910.7538,-667.3689 1914.6415,-663.6742"/>
<polygon fill="#000000" stroke="#000000" points="1917.2691,-666.0141 1922.285,-656.6818 1912.5442,-660.8492 1917.2691,-666.0141"/>
<text text-anchor="middle" x="1948" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- publication -->
<g id="node13" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M3228.5,-391C3228.5,-391 3438.5,-391 3438.5,-391 3444.5,-391 3450.5,-397 3450.5,-403 3450.5,-403 3450.5,-415 3450.5,-415 3450.5,-421 3444.5,-427 3438.5,-427 3438.5,-427 3228.5,-427 3228.5,-427 3222.5,-427 3216.5,-421 3216.5,-415 3216.5,-415 3216.5,-403 3216.5,-403 3216.5,-397 3222.5,-391 3228.5,-391"/>
<text text-anchor="middle" x="3265" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="3313.5,-391 3313.5,-427 "/>
<text text-anchor="middle" x="3324" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3334.5,-391 3334.5,-427 "/>
<text text-anchor="middle" x="3382" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="3429.5,-391 3429.5,-427 "/>
<text text-anchor="middle" x="3440" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge10" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3308.3208,-390.7118C3283.4956,-373.1945 3244.071,-346.7297 3207.5,-328 3123.4738,-284.9662 3027.2963,-245.305 2943.1373,-213.5095"/>
<polygon fill="#000000" stroke="#000000" points="2944.3165,-210.2137 2933.7245,-209.9671 2941.8509,-216.7651 2944.3165,-210.2137"/>
<text text-anchor="middle" x="3220.5" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- study_admin -->
<g id="node14" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M3480.5,-328.5C3480.5,-328.5 3806.5,-328.5 3806.5,-328.5 3812.5,-328.5 3818.5,-334.5 3818.5,-340.5 3818.5,-340.5 3818.5,-477.5 3818.5,-477.5 3818.5,-483.5 3812.5,-489.5 3806.5,-489.5 3806.5,-489.5 3480.5,-489.5 3480.5,-489.5 3474.5,-489.5 3468.5,-483.5 3468.5,-477.5 3468.5,-477.5 3468.5,-340.5 3468.5,-340.5 3468.5,-334.5 3474.5,-328.5 3480.5,-328.5"/>
<text text-anchor="middle" x="3522.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="3576.5,-328.5 3576.5,-489.5 "/>
<text text-anchor="middle" x="3587" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3597.5,-328.5 3597.5,-489.5 "/>
<text text-anchor="middle" x="3697.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="3597.5,-466.5 3797.5,-466.5 "/>
<text text-anchor="middle" x="3697.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="3597.5,-443.5 3797.5,-443.5 "/>
<text text-anchor="middle" x="3697.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="3597.5,-420.5 3797.5,-420.5 "/>
<text text-anchor="middle" x="3697.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="3597.5,-397.5 3797.5,-397.5 "/>
<text text-anchor="middle" x="3697.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="3597.5,-374.5 3797.5,-374.5 "/>
<text text-anchor="middle" x="3697.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="3597.5,-351.5 3797.5,-351.5 "/>
<text text-anchor="middle" x="3697.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="3797.5,-328.5 3797.5,-489.5 "/>
<text text-anchor="middle" x="3808" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge16" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3468.4547,-331.1679C3465.4544,-330.0863 3462.4678,-329.0293 3459.5,-328 3289.2436,-268.9518 3091.116,-218.7993 2943.801,-184.9499"/>
<polygon fill="#000000" stroke="#000000" points="2944.2569,-181.4637 2933.7278,-182.6425 2942.6939,-188.287 2944.2569,-181.4637"/>
<text text-anchor="middle" x="3457" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- therapeutic_procedure -->
<g id="node15" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M2122,-835C2122,-835 2479,-835 2479,-835 2485,-835 2491,-841 2491,-847 2491,-847 2491,-938 2491,-938 2491,-944 2485,-950 2479,-950 2479,-950 2122,-950 2122,-950 2116,-950 2110,-944 2110,-938 2110,-938 2110,-847 2110,-847 2110,-841 2116,-835 2122,-835"/>
<text text-anchor="middle" x="2200.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="2291,-835 2291,-950 "/>
<text text-anchor="middle" x="2301.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2312,-835 2312,-950 "/>
<text text-anchor="middle" x="2391" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="2312,-927 2470,-927 "/>
<text text-anchor="middle" x="2391" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="2312,-904 2470,-904 "/>
<text text-anchor="middle" x="2391" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="2312,-881 2470,-881 "/>
<text text-anchor="middle" x="2391" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="2312,-858 2470,-858 "/>
<text text-anchor="middle" x="2391" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="2470,-835 2470,-950 "/>
<text text-anchor="middle" x="2480.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2242.7658,-834.864C2193.4137,-785.5958 2122.4577,-714.7605 2071.1998,-663.5898"/>
<polygon fill="#000000" stroke="#000000" points="2073.652,-661.0922 2064.1021,-656.5041 2068.7064,-666.0462 2073.652,-661.0922"/>
<text text-anchor="middle" x="2185.5" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- methylation_array_file -->
<g id="node17" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M12,-1301C12,-1301 379,-1301 379,-1301 385,-1301 391,-1307 391,-1313 391,-1313 391,-1519 391,-1519 391,-1525 385,-1531 379,-1531 379,-1531 12,-1531 12,-1531 6,-1531 0,-1525 0,-1519 0,-1519 0,-1313 0,-1313 0,-1307 6,-1301 12,-1301"/>
<text text-anchor="middle" x="89" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="178,-1301 178,-1531 "/>
<text text-anchor="middle" x="188.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="199,-1301 199,-1531 "/>
<text text-anchor="middle" x="284.5" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="199,-1508 370,-1508 "/>
<text text-anchor="middle" x="284.5" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="199,-1485 370,-1485 "/>
<text text-anchor="middle" x="284.5" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="199,-1462 370,-1462 "/>
<text text-anchor="middle" x="284.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="199,-1439 370,-1439 "/>
<text text-anchor="middle" x="284.5" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="199,-1416 370,-1416 "/>
<text text-anchor="middle" x="284.5" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="199,-1393 370,-1393 "/>
<text text-anchor="middle" x="284.5" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="199,-1370 370,-1370 "/>
<text text-anchor="middle" x="284.5" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="199,-1347 370,-1347 "/>
<text text-anchor="middle" x="284.5" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="199,-1324 370,-1324 "/>
<text text-anchor="middle" x="284.5" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="370,-1301 370,-1531 "/>
<text text-anchor="middle" x="380.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M251.6409,-1300.64C286.5338,-1240.5709 336.9002,-1170.9008 400.5,-1128 530.793,-1040.1117 959.4586,-960.1287 1206.2339,-919.8698"/>
<polygon fill="#000000" stroke="#000000" points="1207.0811,-923.2781 1216.3898,-918.2187 1205.9577,-916.3689 1207.0811,-923.2781"/>
<text text-anchor="middle" x="548" y="-1098.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
</g>
</svg>
</div>
