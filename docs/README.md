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
<svg width="2658pt" height="1574pt"
 viewBox="0.00 0.00 2657.50 1574.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1570)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1570 2653.5,-1570 2653.5,4 -4,4"/>
<!-- sample -->
<g id="node1" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M607.5,-639.5C607.5,-639.5 921.5,-639.5 921.5,-639.5 927.5,-639.5 933.5,-645.5 933.5,-651.5 933.5,-651.5 933.5,-949.5 933.5,-949.5 933.5,-955.5 927.5,-961.5 921.5,-961.5 921.5,-961.5 607.5,-961.5 607.5,-961.5 601.5,-961.5 595.5,-955.5 595.5,-949.5 595.5,-949.5 595.5,-651.5 595.5,-651.5 595.5,-645.5 601.5,-639.5 607.5,-639.5"/>
<text text-anchor="middle" x="629.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="663.5,-639.5 663.5,-961.5 "/>
<text text-anchor="middle" x="674" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="684.5,-639.5 684.5,-961.5 "/>
<text text-anchor="middle" x="798.5" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="684.5,-938.5 912.5,-938.5 "/>
<text text-anchor="middle" x="798.5" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="684.5,-915.5 912.5,-915.5 "/>
<text text-anchor="middle" x="798.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="684.5,-892.5 912.5,-892.5 "/>
<text text-anchor="middle" x="798.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="684.5,-869.5 912.5,-869.5 "/>
<text text-anchor="middle" x="798.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="684.5,-846.5 912.5,-846.5 "/>
<text text-anchor="middle" x="798.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="684.5,-823.5 912.5,-823.5 "/>
<text text-anchor="middle" x="798.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="684.5,-800.5 912.5,-800.5 "/>
<text text-anchor="middle" x="798.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="684.5,-777.5 912.5,-777.5 "/>
<text text-anchor="middle" x="798.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="684.5,-754.5 912.5,-754.5 "/>
<text text-anchor="middle" x="798.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage</text>
<polyline fill="none" stroke="#000000" points="684.5,-731.5 912.5,-731.5 "/>
<text text-anchor="middle" x="798.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="684.5,-708.5 912.5,-708.5 "/>
<text text-anchor="middle" x="798.5" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="684.5,-685.5 912.5,-685.5 "/>
<text text-anchor="middle" x="798.5" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="684.5,-662.5 912.5,-662.5 "/>
<text text-anchor="middle" x="798.5" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_status</text>
<polyline fill="none" stroke="#000000" points="912.5,-639.5 912.5,-961.5 "/>
<text text-anchor="middle" x="923" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node2" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M1326,-495.5C1326,-495.5 1557,-495.5 1557,-495.5 1563,-495.5 1569,-501.5 1569,-507.5 1569,-507.5 1569,-575.5 1569,-575.5 1569,-581.5 1563,-587.5 1557,-587.5 1557,-587.5 1326,-587.5 1326,-587.5 1320,-587.5 1314,-581.5 1314,-575.5 1314,-575.5 1314,-507.5 1314,-507.5 1314,-501.5 1320,-495.5 1326,-495.5"/>
<text text-anchor="middle" x="1362" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1410,-495.5 1410,-587.5 "/>
<text text-anchor="middle" x="1420.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1431,-495.5 1431,-587.5 "/>
<text text-anchor="middle" x="1489.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="1431,-564.5 1548,-564.5 "/>
<text text-anchor="middle" x="1489.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="1431,-541.5 1548,-541.5 "/>
<text text-anchor="middle" x="1489.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1431,-518.5 1548,-518.5 "/>
<text text-anchor="middle" x="1489.5" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1548,-495.5 1548,-587.5 "/>
<text text-anchor="middle" x="1558.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M933.7866,-681.2919C960.6663,-665.5448 988.7677,-650.8012 1016.5,-639 1108.4629,-599.8662 1218.606,-575.1649 1303.7192,-560.4181"/>
<polygon fill="#000000" stroke="#000000" points="1304.4402,-563.8457 1313.7087,-558.713 1303.2624,-556.9455 1304.4402,-563.8457"/>
<text text-anchor="middle" x="1142" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study -->
<g id="node12" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M1596.5,-.5C1596.5,-.5 1986.5,-.5 1986.5,-.5 1992.5,-.5 1998.5,-6.5 1998.5,-12.5 1998.5,-12.5 1998.5,-195.5 1998.5,-195.5 1998.5,-201.5 1992.5,-207.5 1986.5,-207.5 1986.5,-207.5 1596.5,-207.5 1596.5,-207.5 1590.5,-207.5 1584.5,-201.5 1584.5,-195.5 1584.5,-195.5 1584.5,-12.5 1584.5,-12.5 1584.5,-6.5 1590.5,-.5 1596.5,-.5"/>
<text text-anchor="middle" x="1612.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="1640.5,-.5 1640.5,-207.5 "/>
<text text-anchor="middle" x="1651" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1661.5,-.5 1661.5,-207.5 "/>
<text text-anchor="middle" x="1819.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="1661.5,-184.5 1977.5,-184.5 "/>
<text text-anchor="middle" x="1819.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="1661.5,-161.5 1977.5,-161.5 "/>
<text text-anchor="middle" x="1819.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="1661.5,-138.5 1977.5,-138.5 "/>
<text text-anchor="middle" x="1819.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="1661.5,-115.5 1977.5,-115.5 "/>
<text text-anchor="middle" x="1819.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="1661.5,-92.5 1977.5,-92.5 "/>
<text text-anchor="middle" x="1819.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="1661.5,-69.5 1977.5,-69.5 "/>
<text text-anchor="middle" x="1819.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="1661.5,-46.5 1977.5,-46.5 "/>
<text text-anchor="middle" x="1819.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="1661.5,-23.5 1977.5,-23.5 "/>
<text text-anchor="middle" x="1819.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="1977.5,-.5 1977.5,-207.5 "/>
<text text-anchor="middle" x="1988" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge2" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M660.656,-639.3809C598.7609,-521.0238 548.2806,-363.3148 639.5,-259 699.9712,-189.8476 1257.2231,-140.6519 1573.972,-118.0083"/>
<polygon fill="#000000" stroke="#000000" points="1574.4783,-121.4812 1584.2046,-117.2801 1573.9813,-114.4989 1574.4783,-121.4812"/>
<text text-anchor="middle" x="635" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge3" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1569.2777,-537.7188C1717.4162,-530.3271 1948.2501,-508.4915 2002.5,-444 2055.4287,-381.079 2039.6356,-332.3583 2002.5,-259 1994.4455,-243.0891 1983.9039,-228.4144 1971.8265,-214.9709"/>
<polygon fill="#000000" stroke="#000000" points="1974.3501,-212.5452 1964.965,-207.6289 1969.2358,-217.3248 1974.3501,-212.5452"/>
<text text-anchor="middle" x="2087" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_arm -->
<g id="node15" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M661,-317C661,-317 958,-317 958,-317 964,-317 970,-323 970,-329 970,-329 970,-374 970,-374 970,-380 964,-386 958,-386 958,-386 661,-386 661,-386 655,-386 649,-380 649,-374 649,-374 649,-329 649,-329 649,-323 655,-317 661,-317"/>
<text text-anchor="middle" x="695" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="741,-317 741,-386 "/>
<text text-anchor="middle" x="751.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="762,-317 762,-386 "/>
<text text-anchor="middle" x="855.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="762,-363 949,-363 "/>
<text text-anchor="middle" x="855.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="762,-340 949,-340 "/>
<text text-anchor="middle" x="855.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="949,-317 949,-386 "/>
<text text-anchor="middle" x="959.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge4" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1313.7216,-524.7449C1219.3807,-509.9446 1088.9132,-484.3301 979.5,-444 942.3258,-430.2975 903.3305,-409.5935 872.0782,-391.2449"/>
<polygon fill="#000000" stroke="#000000" points="873.8626,-388.234 863.4768,-386.1399 870.2899,-394.2536 873.8626,-388.234"/>
<text text-anchor="middle" x="1128" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_personnel -->
<g id="node3" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M1000,-294C1000,-294 1307,-294 1307,-294 1313,-294 1319,-300 1319,-306 1319,-306 1319,-397 1319,-397 1319,-403 1313,-409 1307,-409 1307,-409 1000,-409 1000,-409 994,-409 988,-403 988,-397 988,-397 988,-306 988,-306 988,-300 994,-294 1000,-294"/>
<text text-anchor="middle" x="1055" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="1122,-294 1122,-409 "/>
<text text-anchor="middle" x="1132.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1143,-294 1143,-409 "/>
<text text-anchor="middle" x="1220.5" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="1143,-386 1298,-386 "/>
<text text-anchor="middle" x="1220.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="1143,-363 1298,-363 "/>
<text text-anchor="middle" x="1220.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="1143,-340 1298,-340 "/>
<text text-anchor="middle" x="1220.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="1143,-317 1298,-317 "/>
<text text-anchor="middle" x="1220.5" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="1298,-294 1298,-409 "/>
<text text-anchor="middle" x="1308.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge14" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1255.7791,-293.867C1279.3148,-281.6118 1304.4918,-269.2822 1328.5,-259 1407.3084,-225.2481 1496.1129,-193.9723 1574.7146,-168.4842"/>
<polygon fill="#000000" stroke="#000000" points="1575.8081,-171.8091 1584.2482,-165.4048 1573.6565,-165.148 1575.8081,-171.8091"/>
<text text-anchor="middle" x="1472" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- therapeutic_procedure -->
<g id="node4" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M1037,-743C1037,-743 1394,-743 1394,-743 1400,-743 1406,-749 1406,-755 1406,-755 1406,-846 1406,-846 1406,-852 1400,-858 1394,-858 1394,-858 1037,-858 1037,-858 1031,-858 1025,-852 1025,-846 1025,-846 1025,-755 1025,-755 1025,-749 1031,-743 1037,-743"/>
<text text-anchor="middle" x="1115.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="1206,-743 1206,-858 "/>
<text text-anchor="middle" x="1216.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1227,-743 1227,-858 "/>
<text text-anchor="middle" x="1306" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="1227,-835 1385,-835 "/>
<text text-anchor="middle" x="1306" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="1227,-812 1385,-812 "/>
<text text-anchor="middle" x="1306" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1227,-789 1385,-789 "/>
<text text-anchor="middle" x="1306" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="1227,-766 1385,-766 "/>
<text text-anchor="middle" x="1306" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1385,-743 1385,-858 "/>
<text text-anchor="middle" x="1395.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1207.9938,-742.5663C1205.7866,-700.0919 1210.1612,-643.5211 1241.5,-606 1251.1918,-594.3963 1275.5714,-583.5454 1304.1124,-574.1761"/>
<polygon fill="#000000" stroke="#000000" points="1305.4642,-577.4191 1313.9358,-571.0566 1303.3455,-570.7475 1305.4642,-577.4191"/>
<text text-anchor="middle" x="1334.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- publication -->
<g id="node5" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M1349.5,-333.5C1349.5,-333.5 1559.5,-333.5 1559.5,-333.5 1565.5,-333.5 1571.5,-339.5 1571.5,-345.5 1571.5,-345.5 1571.5,-357.5 1571.5,-357.5 1571.5,-363.5 1565.5,-369.5 1559.5,-369.5 1559.5,-369.5 1349.5,-369.5 1349.5,-369.5 1343.5,-369.5 1337.5,-363.5 1337.5,-357.5 1337.5,-357.5 1337.5,-345.5 1337.5,-345.5 1337.5,-339.5 1343.5,-333.5 1349.5,-333.5"/>
<text text-anchor="middle" x="1386" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="1434.5,-333.5 1434.5,-369.5 "/>
<text text-anchor="middle" x="1445" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1455.5,-333.5 1455.5,-369.5 "/>
<text text-anchor="middle" x="1503" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="1550.5,-333.5 1550.5,-369.5 "/>
<text text-anchor="middle" x="1561" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge18" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1479.2804,-333.3007C1513.9756,-307.8198 1579.7873,-259.4863 1642.0764,-213.7399"/>
<polygon fill="#000000" stroke="#000000" points="1644.4538,-216.3364 1650.4419,-207.5961 1640.3102,-210.6945 1644.4538,-216.3364"/>
<text text-anchor="middle" x="1673.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- study_funding -->
<g id="node6" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M1602,-317C1602,-317 1981,-317 1981,-317 1987,-317 1993,-323 1993,-329 1993,-329 1993,-374 1993,-374 1993,-380 1987,-386 1981,-386 1981,-386 1602,-386 1602,-386 1596,-386 1590,-380 1590,-374 1590,-374 1590,-329 1590,-329 1590,-323 1596,-317 1602,-317"/>
<text text-anchor="middle" x="1649.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="1709,-317 1709,-386 "/>
<text text-anchor="middle" x="1719.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1730,-317 1730,-386 "/>
<text text-anchor="middle" x="1851" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="1730,-363 1972,-363 "/>
<text text-anchor="middle" x="1851" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="1730,-340 1972,-340 "/>
<text text-anchor="middle" x="1851" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="1972,-317 1972,-386 "/>
<text text-anchor="middle" x="1982.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge19" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1791.5,-316.8256C1791.5,-290.8629 1791.5,-253.7725 1791.5,-217.8091"/>
<polygon fill="#000000" stroke="#000000" points="1795.0001,-217.7056 1791.5,-207.7056 1788.0001,-217.7056 1795.0001,-217.7056"/>
<text text-anchor="middle" x="1853.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- sequencing_file -->
<g id="node7" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M12,-1013.5C12,-1013.5 481,-1013.5 481,-1013.5 487,-1013.5 493,-1019.5 493,-1025.5 493,-1025.5 493,-1553.5 493,-1553.5 493,-1559.5 487,-1565.5 481,-1565.5 481,-1565.5 12,-1565.5 12,-1565.5 6,-1565.5 0,-1559.5 0,-1553.5 0,-1553.5 0,-1025.5 0,-1025.5 0,-1019.5 6,-1013.5 12,-1013.5"/>
<text text-anchor="middle" x="64" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="128,-1013.5 128,-1565.5 "/>
<text text-anchor="middle" x="138.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="149,-1013.5 149,-1565.5 "/>
<text text-anchor="middle" x="310.5" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="149,-1542.5 472,-1542.5 "/>
<text text-anchor="middle" x="310.5" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="149,-1519.5 472,-1519.5 "/>
<text text-anchor="middle" x="310.5" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="149,-1496.5 472,-1496.5 "/>
<text text-anchor="middle" x="310.5" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="149,-1473.5 472,-1473.5 "/>
<text text-anchor="middle" x="310.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="149,-1450.5 472,-1450.5 "/>
<text text-anchor="middle" x="310.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="149,-1427.5 472,-1427.5 "/>
<text text-anchor="middle" x="310.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="149,-1404.5 472,-1404.5 "/>
<text text-anchor="middle" x="310.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="149,-1381.5 472,-1381.5 "/>
<text text-anchor="middle" x="310.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="149,-1358.5 472,-1358.5 "/>
<text text-anchor="middle" x="310.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="149,-1335.5 472,-1335.5 "/>
<text text-anchor="middle" x="310.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="149,-1312.5 472,-1312.5 "/>
<text text-anchor="middle" x="310.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="149,-1289.5 472,-1289.5 "/>
<text text-anchor="middle" x="310.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="149,-1266.5 472,-1266.5 "/>
<text text-anchor="middle" x="310.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="149,-1243.5 472,-1243.5 "/>
<text text-anchor="middle" x="310.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="149,-1220.5 472,-1220.5 "/>
<text text-anchor="middle" x="310.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="149,-1197.5 472,-1197.5 "/>
<text text-anchor="middle" x="310.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="149,-1174.5 472,-1174.5 "/>
<text text-anchor="middle" x="310.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="149,-1151.5 472,-1151.5 "/>
<text text-anchor="middle" x="310.5" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="149,-1128.5 472,-1128.5 "/>
<text text-anchor="middle" x="310.5" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="149,-1105.5 472,-1105.5 "/>
<text text-anchor="middle" x="310.5" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="149,-1082.5 472,-1082.5 "/>
<text text-anchor="middle" x="310.5" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="149,-1059.5 472,-1059.5 "/>
<text text-anchor="middle" x="310.5" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="149,-1036.5 472,-1036.5 "/>
<text text-anchor="middle" x="310.5" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="472,-1013.5 472,-1565.5 "/>
<text text-anchor="middle" x="482.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M493.1693,-1021.8088C496.2854,-1018.8442 499.3964,-1015.9068 502.5,-1013 529.1828,-988.0092 558.4306,-962.5714 587.406,-938.3904"/>
<polygon fill="#000000" stroke="#000000" points="589.7135,-941.0236 595.1653,-931.9391 585.2382,-935.641 589.7135,-941.0236"/>
<text text-anchor="middle" x="603" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- synonym -->
<g id="node8" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M1309,-1243.5C1309,-1243.5 1610,-1243.5 1610,-1243.5 1616,-1243.5 1622,-1249.5 1622,-1255.5 1622,-1255.5 1622,-1323.5 1622,-1323.5 1622,-1329.5 1616,-1335.5 1610,-1335.5 1610,-1335.5 1309,-1335.5 1309,-1335.5 1303,-1335.5 1297,-1329.5 1297,-1323.5 1297,-1323.5 1297,-1255.5 1297,-1255.5 1297,-1249.5 1303,-1243.5 1309,-1243.5"/>
<text text-anchor="middle" x="1337" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="1377,-1243.5 1377,-1335.5 "/>
<text text-anchor="middle" x="1387.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1398,-1243.5 1398,-1335.5 "/>
<text text-anchor="middle" x="1499.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_id</text>
<polyline fill="none" stroke="#000000" points="1398,-1312.5 1601,-1312.5 "/>
<text text-anchor="middle" x="1499.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_node</text>
<polyline fill="none" stroke="#000000" points="1398,-1289.5 1601,-1289.5 "/>
<text text-anchor="middle" x="1499.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="1398,-1266.5 1601,-1266.5 "/>
<text text-anchor="middle" x="1499.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="1601,-1243.5 1601,-1335.5 "/>
<text text-anchor="middle" x="1611.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1444.4305,-1243.4316C1421.3779,-1180.6765 1371.1213,-1069.6622 1288.5,-1013 1187.0664,-943.4362 1130.8289,-1007.3519 1016.5,-962 991.6565,-952.1451 966.6236,-939.7311 942.4802,-926.1841"/>
<polygon fill="#000000" stroke="#000000" points="944.0496,-923.0501 933.6275,-921.1444 940.5864,-929.1334 944.0496,-923.0501"/>
<text text-anchor="middle" x="1296" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1458.3645,-1243.3993C1456.8052,-1180.0053 1453.919,-1062.3545 1451.5,-962 1448.3592,-831.6998 1444.737,-678.6863 1442.8314,-597.971"/>
<polygon fill="#000000" stroke="#000000" points="1446.3204,-597.4596 1442.5853,-587.545 1439.3223,-597.6248 1446.3204,-597.4596"/>
<text text-anchor="middle" x="1494" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge8" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1622.2496,-1253.2245C1929.5119,-1180.0026 2564.5,-1004.0576 2564.5,-800.5 2564.5,-800.5 2564.5,-800.5 2564.5,-351.5 2564.5,-309.5306 2575.1745,-288.6792 2545.5,-259 2471.2576,-184.7459 2204.0551,-143.2482 2008.7598,-122.2714"/>
<polygon fill="#000000" stroke="#000000" points="2008.9535,-118.7723 1998.6396,-121.1958 2008.2136,-125.7331 2008.9535,-118.7723"/>
<text text-anchor="middle" x="2607" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- imaging_file -->
<g id="node9" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M523.5,-1128.5C523.5,-1128.5 857.5,-1128.5 857.5,-1128.5 863.5,-1128.5 869.5,-1134.5 869.5,-1140.5 869.5,-1140.5 869.5,-1438.5 869.5,-1438.5 869.5,-1444.5 863.5,-1450.5 857.5,-1450.5 857.5,-1450.5 523.5,-1450.5 523.5,-1450.5 517.5,-1450.5 511.5,-1444.5 511.5,-1438.5 511.5,-1438.5 511.5,-1140.5 511.5,-1140.5 511.5,-1134.5 517.5,-1128.5 523.5,-1128.5"/>
<text text-anchor="middle" x="563.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="615.5,-1128.5 615.5,-1450.5 "/>
<text text-anchor="middle" x="626" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="636.5,-1128.5 636.5,-1450.5 "/>
<text text-anchor="middle" x="742.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="636.5,-1427.5 848.5,-1427.5 "/>
<text text-anchor="middle" x="742.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="636.5,-1404.5 848.5,-1404.5 "/>
<text text-anchor="middle" x="742.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="636.5,-1381.5 848.5,-1381.5 "/>
<text text-anchor="middle" x="742.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="636.5,-1358.5 848.5,-1358.5 "/>
<text text-anchor="middle" x="742.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="636.5,-1335.5 848.5,-1335.5 "/>
<text text-anchor="middle" x="742.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="636.5,-1312.5 848.5,-1312.5 "/>
<text text-anchor="middle" x="742.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="636.5,-1289.5 848.5,-1289.5 "/>
<text text-anchor="middle" x="742.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="636.5,-1266.5 848.5,-1266.5 "/>
<text text-anchor="middle" x="742.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="636.5,-1243.5 848.5,-1243.5 "/>
<text text-anchor="middle" x="742.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="636.5,-1220.5 848.5,-1220.5 "/>
<text text-anchor="middle" x="742.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="636.5,-1197.5 848.5,-1197.5 "/>
<text text-anchor="middle" x="742.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="636.5,-1174.5 848.5,-1174.5 "/>
<text text-anchor="middle" x="742.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="636.5,-1151.5 848.5,-1151.5 "/>
<text text-anchor="middle" x="742.5" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="848.5,-1128.5 848.5,-1450.5 "/>
<text text-anchor="middle" x="859" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M714.8841,-1128.3669C722.4841,-1078.1459 730.8907,-1022.594 738.5911,-971.7088"/>
<polygon fill="#000000" stroke="#000000" points="742.0856,-972.0081 740.1213,-961.597 735.1644,-970.9607 742.0856,-972.0081"/>
<text text-anchor="middle" x="791" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- methylation_array_file -->
<g id="node10" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M900,-1174.5C900,-1174.5 1267,-1174.5 1267,-1174.5 1273,-1174.5 1279,-1180.5 1279,-1186.5 1279,-1186.5 1279,-1392.5 1279,-1392.5 1279,-1398.5 1273,-1404.5 1267,-1404.5 1267,-1404.5 900,-1404.5 900,-1404.5 894,-1404.5 888,-1398.5 888,-1392.5 888,-1392.5 888,-1186.5 888,-1186.5 888,-1180.5 894,-1174.5 900,-1174.5"/>
<text text-anchor="middle" x="977" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="1066,-1174.5 1066,-1404.5 "/>
<text text-anchor="middle" x="1076.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1087,-1174.5 1087,-1404.5 "/>
<text text-anchor="middle" x="1172.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1087,-1381.5 1258,-1381.5 "/>
<text text-anchor="middle" x="1172.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1087,-1358.5 1258,-1358.5 "/>
<text text-anchor="middle" x="1172.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1087,-1335.5 1258,-1335.5 "/>
<text text-anchor="middle" x="1172.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1087,-1312.5 1258,-1312.5 "/>
<text text-anchor="middle" x="1172.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1087,-1289.5 1258,-1289.5 "/>
<text text-anchor="middle" x="1172.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1087,-1266.5 1258,-1266.5 "/>
<text text-anchor="middle" x="1172.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1087,-1243.5 1258,-1243.5 "/>
<text text-anchor="middle" x="1172.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1087,-1220.5 1258,-1220.5 "/>
<text text-anchor="middle" x="1172.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="1087,-1197.5 1258,-1197.5 "/>
<text text-anchor="middle" x="1172.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="1258,-1174.5 1258,-1404.5 "/>
<text text-anchor="middle" x="1268.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1008.3054,-1174.233C968.6486,-1113.4426 919.2345,-1037.6948 875.2806,-970.3172"/>
<polygon fill="#000000" stroke="#000000" points="878.0672,-968.1829 869.672,-961.7198 872.2044,-972.0076 878.0672,-968.1829"/>
<text text-anchor="middle" x="977" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- diagnosis -->
<g id="node11" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1557,-651C1557,-651 1940,-651 1940,-651 1946,-651 1952,-657 1952,-663 1952,-663 1952,-938 1952,-938 1952,-944 1946,-950 1940,-950 1940,-950 1557,-950 1557,-950 1551,-950 1545,-944 1545,-938 1545,-938 1545,-663 1545,-663 1545,-657 1551,-651 1557,-651"/>
<text text-anchor="middle" x="1587" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1629,-651 1629,-950 "/>
<text text-anchor="middle" x="1639.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1650,-651 1650,-950 "/>
<text text-anchor="middle" x="1790.5" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1650,-927 1931,-927 "/>
<text text-anchor="middle" x="1790.5" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1650,-904 1931,-904 "/>
<text text-anchor="middle" x="1790.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1650,-881 1931,-881 "/>
<text text-anchor="middle" x="1790.5" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1650,-858 1931,-858 "/>
<text text-anchor="middle" x="1790.5" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1650,-835 1931,-835 "/>
<text text-anchor="middle" x="1790.5" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="1650,-812 1931,-812 "/>
<text text-anchor="middle" x="1790.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1650,-789 1931,-789 "/>
<text text-anchor="middle" x="1790.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1650,-766 1931,-766 "/>
<text text-anchor="middle" x="1790.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis_reference_source</text>
<polyline fill="none" stroke="#000000" points="1650,-743 1931,-743 "/>
<text text-anchor="middle" x="1790.5" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="1650,-720 1931,-720 "/>
<text text-anchor="middle" x="1790.5" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="1650,-697 1931,-697 "/>
<text text-anchor="middle" x="1790.5" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="1650,-674 1931,-674 "/>
<text text-anchor="middle" x="1790.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="1931,-651 1931,-950 "/>
<text text-anchor="middle" x="1941.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1571.2507,-650.9639C1547.1907,-630.6658 1523.9285,-611.0407 1503.9062,-594.1489"/>
<polygon fill="#000000" stroke="#000000" points="1506.0099,-591.3445 1496.1097,-587.5714 1501.4961,-596.6948 1506.0099,-591.3445"/>
<text text-anchor="middle" x="1576" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- clinical_measure_file -->
<g id="node13" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M1982.5,-674C1982.5,-674 2334.5,-674 2334.5,-674 2340.5,-674 2346.5,-680 2346.5,-686 2346.5,-686 2346.5,-915 2346.5,-915 2346.5,-921 2340.5,-927 2334.5,-927 2334.5,-927 1982.5,-927 1982.5,-927 1976.5,-927 1970.5,-921 1970.5,-915 1970.5,-915 1970.5,-686 1970.5,-686 1970.5,-680 1976.5,-674 1982.5,-674"/>
<text text-anchor="middle" x="2054" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="2137.5,-674 2137.5,-927 "/>
<text text-anchor="middle" x="2148" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2158.5,-674 2158.5,-927 "/>
<text text-anchor="middle" x="2242" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2158.5,-904 2325.5,-904 "/>
<text text-anchor="middle" x="2242" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2158.5,-881 2325.5,-881 "/>
<text text-anchor="middle" x="2242" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2158.5,-858 2325.5,-858 "/>
<text text-anchor="middle" x="2242" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2158.5,-835 2325.5,-835 "/>
<text text-anchor="middle" x="2242" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2158.5,-812 2325.5,-812 "/>
<text text-anchor="middle" x="2242" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2158.5,-789 2325.5,-789 "/>
<text text-anchor="middle" x="2242" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2158.5,-766 2325.5,-766 "/>
<text text-anchor="middle" x="2242" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2158.5,-743 2325.5,-743 "/>
<text text-anchor="middle" x="2242" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2158.5,-720 2325.5,-720 "/>
<text text-anchor="middle" x="2242" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2158.5,-697 2325.5,-697 "/>
<text text-anchor="middle" x="2242" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="2325.5,-674 2325.5,-927 "/>
<text text-anchor="middle" x="2336" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2020.8898,-673.8043C2001.8647,-660.5468 1981.8444,-648.4791 1961.5,-639 1944.0908,-630.8885 1727.3999,-591.7465 1579.2992,-565.5909"/>
<polygon fill="#000000" stroke="#000000" points="1579.6585,-562.1003 1569.2023,-563.809 1578.4419,-568.9937 1579.6585,-562.1003"/>
<text text-anchor="middle" x="2004" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge17" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2169.6276,-673.9048C2179.2174,-535.3631 2185.433,-324.2418 2141.5,-259 2109.7223,-211.8092 2060.0571,-178.8469 2008.0217,-155.8741"/>
<polygon fill="#000000" stroke="#000000" points="2009.1965,-152.5697 1998.6266,-151.8433 2006.4365,-159.0026 2009.1965,-152.5697"/>
<text text-anchor="middle" x="2261.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- study_admin -->
<g id="node14" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M2198.5,-259.5C2198.5,-259.5 2524.5,-259.5 2524.5,-259.5 2530.5,-259.5 2536.5,-265.5 2536.5,-271.5 2536.5,-271.5 2536.5,-431.5 2536.5,-431.5 2536.5,-437.5 2530.5,-443.5 2524.5,-443.5 2524.5,-443.5 2198.5,-443.5 2198.5,-443.5 2192.5,-443.5 2186.5,-437.5 2186.5,-431.5 2186.5,-431.5 2186.5,-271.5 2186.5,-271.5 2186.5,-265.5 2192.5,-259.5 2198.5,-259.5"/>
<text text-anchor="middle" x="2240.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="2294.5,-259.5 2294.5,-443.5 "/>
<text text-anchor="middle" x="2305" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2315.5,-259.5 2315.5,-443.5 "/>
<text text-anchor="middle" x="2415.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="2315.5,-420.5 2515.5,-420.5 "/>
<text text-anchor="middle" x="2415.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="2315.5,-397.5 2515.5,-397.5 "/>
<text text-anchor="middle" x="2415.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="2315.5,-374.5 2515.5,-374.5 "/>
<text text-anchor="middle" x="2415.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="2315.5,-351.5 2515.5,-351.5 "/>
<text text-anchor="middle" x="2415.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="2315.5,-328.5 2515.5,-328.5 "/>
<text text-anchor="middle" x="2415.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="2315.5,-305.5 2515.5,-305.5 "/>
<text text-anchor="middle" x="2415.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="2315.5,-282.5 2515.5,-282.5 "/>
<text text-anchor="middle" x="2415.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="2515.5,-259.5 2515.5,-443.5 "/>
<text text-anchor="middle" x="2526" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge16" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2232.8585,-259.3648C2213.1484,-247.2401 2192.6463,-235.6829 2172.5,-226 2120.9758,-201.236 2063.1983,-179.7845 2008.5149,-162.0755"/>
<polygon fill="#000000" stroke="#000000" points="2009.2918,-158.6491 1998.7006,-158.9263 2007.153,-165.3144 2009.2918,-158.6491"/>
<text text-anchor="middle" x="2256" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge13" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M862.9939,-316.7965C895.5076,-297.1513 938.5294,-273.6528 979.5,-259 1174.4057,-189.2935 1407.436,-148.9323 1573.7654,-126.9763"/>
<polygon fill="#000000" stroke="#000000" points="1574.6626,-130.3888 1584.1241,-125.6213 1573.7546,-123.4479 1574.6626,-130.3888"/>
<text text-anchor="middle" x="1113" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
</g>
</svg>
</div>
