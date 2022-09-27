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
<svg width="2965pt" height="1574pt"
 viewBox="0.00 0.00 2965.00 1574.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1570)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1570 2961,-1570 2961,4 -4,4"/>
<!-- synonym -->
<g id="node1" class="node">
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
<!-- study -->
<g id="node4" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M1476.5,-.5C1476.5,-.5 1866.5,-.5 1866.5,-.5 1872.5,-.5 1878.5,-6.5 1878.5,-12.5 1878.5,-12.5 1878.5,-195.5 1878.5,-195.5 1878.5,-201.5 1872.5,-207.5 1866.5,-207.5 1866.5,-207.5 1476.5,-207.5 1476.5,-207.5 1470.5,-207.5 1464.5,-201.5 1464.5,-195.5 1464.5,-195.5 1464.5,-12.5 1464.5,-12.5 1464.5,-6.5 1470.5,-.5 1476.5,-.5"/>
<text text-anchor="middle" x="1492.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="1520.5,-.5 1520.5,-207.5 "/>
<text text-anchor="middle" x="1531" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1541.5,-.5 1541.5,-207.5 "/>
<text text-anchor="middle" x="1699.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="1541.5,-184.5 1857.5,-184.5 "/>
<text text-anchor="middle" x="1699.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="1541.5,-161.5 1857.5,-161.5 "/>
<text text-anchor="middle" x="1699.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="1541.5,-138.5 1857.5,-138.5 "/>
<text text-anchor="middle" x="1699.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="1541.5,-115.5 1857.5,-115.5 "/>
<text text-anchor="middle" x="1699.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="1541.5,-92.5 1857.5,-92.5 "/>
<text text-anchor="middle" x="1699.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="1541.5,-69.5 1857.5,-69.5 "/>
<text text-anchor="middle" x="1699.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="1541.5,-46.5 1857.5,-46.5 "/>
<text text-anchor="middle" x="1699.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="1541.5,-23.5 1857.5,-23.5 "/>
<text text-anchor="middle" x="1699.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="1857.5,-.5 1857.5,-207.5 "/>
<text text-anchor="middle" x="1868" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge14" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1448.4083,-1243.2932C1428.6702,-1156.8897 1389.5,-964.7328 1389.5,-800.5 1389.5,-800.5 1389.5,-800.5 1389.5,-351.5 1389.5,-309.6177 1384.8869,-294.253 1407.5,-259 1420.6782,-238.4557 1437.6237,-220.2944 1456.561,-204.3221"/>
<polygon fill="#000000" stroke="#000000" points="1458.9633,-206.8792 1464.4972,-197.8444 1454.537,-201.4563 1458.9633,-206.8792"/>
<text text-anchor="middle" x="1432" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- participant -->
<g id="node5" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M1718,-495.5C1718,-495.5 1949,-495.5 1949,-495.5 1955,-495.5 1961,-501.5 1961,-507.5 1961,-507.5 1961,-575.5 1961,-575.5 1961,-581.5 1955,-587.5 1949,-587.5 1949,-587.5 1718,-587.5 1718,-587.5 1712,-587.5 1706,-581.5 1706,-575.5 1706,-575.5 1706,-507.5 1706,-507.5 1706,-501.5 1712,-495.5 1718,-495.5"/>
<text text-anchor="middle" x="1754" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1802,-495.5 1802,-587.5 "/>
<text text-anchor="middle" x="1812.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1823,-495.5 1823,-587.5 "/>
<text text-anchor="middle" x="1881.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="1823,-564.5 1940,-564.5 "/>
<text text-anchor="middle" x="1881.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="1823,-541.5 1940,-541.5 "/>
<text text-anchor="middle" x="1881.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1823,-518.5 1940,-518.5 "/>
<text text-anchor="middle" x="1881.5" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1940,-495.5 1940,-587.5 "/>
<text text-anchor="middle" x="1950.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1535.2028,-1243.4244C1618.3199,-1188.1242 1747.7631,-1087.0208 1806.5,-962 1836.093,-899.0117 1836.6117,-697.3732 1834.9271,-597.9762"/>
<polygon fill="#000000" stroke="#000000" points="1838.4236,-597.7525 1834.7411,-587.8183 1831.4248,-597.8807 1838.4236,-597.7525"/>
<text text-anchor="middle" x="1878" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- sample -->
<g id="node13" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M864.5,-639.5C864.5,-639.5 1178.5,-639.5 1178.5,-639.5 1184.5,-639.5 1190.5,-645.5 1190.5,-651.5 1190.5,-651.5 1190.5,-949.5 1190.5,-949.5 1190.5,-955.5 1184.5,-961.5 1178.5,-961.5 1178.5,-961.5 864.5,-961.5 864.5,-961.5 858.5,-961.5 852.5,-955.5 852.5,-949.5 852.5,-949.5 852.5,-651.5 852.5,-651.5 852.5,-645.5 858.5,-639.5 864.5,-639.5"/>
<text text-anchor="middle" x="886.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="920.5,-639.5 920.5,-961.5 "/>
<text text-anchor="middle" x="931" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="941.5,-639.5 941.5,-961.5 "/>
<text text-anchor="middle" x="1055.5" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="941.5,-938.5 1169.5,-938.5 "/>
<text text-anchor="middle" x="1055.5" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="941.5,-915.5 1169.5,-915.5 "/>
<text text-anchor="middle" x="1055.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="941.5,-892.5 1169.5,-892.5 "/>
<text text-anchor="middle" x="1055.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="941.5,-869.5 1169.5,-869.5 "/>
<text text-anchor="middle" x="1055.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="941.5,-846.5 1169.5,-846.5 "/>
<text text-anchor="middle" x="1055.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="941.5,-823.5 1169.5,-823.5 "/>
<text text-anchor="middle" x="1055.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="941.5,-800.5 1169.5,-800.5 "/>
<text text-anchor="middle" x="1055.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="941.5,-777.5 1169.5,-777.5 "/>
<text text-anchor="middle" x="1055.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="941.5,-754.5 1169.5,-754.5 "/>
<text text-anchor="middle" x="1055.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage</text>
<polyline fill="none" stroke="#000000" points="941.5,-731.5 1169.5,-731.5 "/>
<text text-anchor="middle" x="1055.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="941.5,-708.5 1169.5,-708.5 "/>
<text text-anchor="middle" x="1055.5" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="941.5,-685.5 1169.5,-685.5 "/>
<text text-anchor="middle" x="1055.5" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="941.5,-662.5 1169.5,-662.5 "/>
<text text-anchor="middle" x="1055.5" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_status</text>
<polyline fill="none" stroke="#000000" points="1169.5,-639.5 1169.5,-961.5 "/>
<text text-anchor="middle" x="1180" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1436.9625,-1243.2022C1407.5366,-1185.5114 1352.0989,-1085.678 1287.5,-1013 1260.9837,-983.1674 1229.9481,-954.2876 1198.6225,-927.9337"/>
<polygon fill="#000000" stroke="#000000" points="1200.5763,-925.0056 1190.6547,-921.2889 1196.093,-930.3816 1200.5763,-925.0056"/>
<text text-anchor="middle" x="1312" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study_personnel -->
<g id="node2" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M1042,-294C1042,-294 1349,-294 1349,-294 1355,-294 1361,-300 1361,-306 1361,-306 1361,-397 1361,-397 1361,-403 1355,-409 1349,-409 1349,-409 1042,-409 1042,-409 1036,-409 1030,-403 1030,-397 1030,-397 1030,-306 1030,-306 1030,-300 1036,-294 1042,-294"/>
<text text-anchor="middle" x="1097" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="1164,-294 1164,-409 "/>
<text text-anchor="middle" x="1174.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1185,-294 1185,-409 "/>
<text text-anchor="middle" x="1262.5" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="1185,-386 1340,-386 "/>
<text text-anchor="middle" x="1262.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="1185,-363 1340,-363 "/>
<text text-anchor="middle" x="1262.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="1185,-340 1340,-340 "/>
<text text-anchor="middle" x="1262.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="1185,-317 1340,-317 "/>
<text text-anchor="middle" x="1262.5" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="1340,-294 1340,-409 "/>
<text text-anchor="middle" x="1350.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge9" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1202.2319,-293.9082C1207.8028,-270.0067 1217.9671,-243.7646 1236.5,-226 1269.5184,-194.3504 1362.7336,-166.2177 1454.4452,-144.9662"/>
<polygon fill="#000000" stroke="#000000" points="1455.496,-148.3162 1464.4614,-142.6707 1453.9322,-141.4931 1455.496,-148.3162"/>
<text text-anchor="middle" x="1306" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- study_arm -->
<g id="node3" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M1819,-317C1819,-317 2116,-317 2116,-317 2122,-317 2128,-323 2128,-329 2128,-329 2128,-374 2128,-374 2128,-380 2122,-386 2116,-386 2116,-386 1819,-386 1819,-386 1813,-386 1807,-380 1807,-374 1807,-374 1807,-329 1807,-329 1807,-323 1813,-317 1819,-317"/>
<text text-anchor="middle" x="1853" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="1899,-317 1899,-386 "/>
<text text-anchor="middle" x="1909.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1920,-317 1920,-386 "/>
<text text-anchor="middle" x="2013.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="1920,-363 2107,-363 "/>
<text text-anchor="middle" x="2013.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="1920,-340 2107,-340 "/>
<text text-anchor="middle" x="2013.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="2107,-317 2107,-386 "/>
<text text-anchor="middle" x="2117.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge15" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1926.0308,-316.8256C1893.9189,-289.9753 1847.5732,-251.2234 1803.205,-214.1249"/>
<polygon fill="#000000" stroke="#000000" points="1805.4444,-211.4352 1795.5277,-207.7056 1800.9542,-216.8053 1805.4444,-211.4352"/>
<text text-anchor="middle" x="1877" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge11" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1866.2801,-495.0208C1887.8593,-464.4234 1915.9123,-424.6468 1937.011,-394.7307"/>
<polygon fill="#000000" stroke="#000000" points="1940.1396,-396.3673 1943.0429,-386.178 1934.4192,-392.3329 1940.1396,-396.3673"/>
<text text-anchor="middle" x="1939" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge10" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1705.9264,-526.4799C1605.2952,-511.6982 1476.7033,-485.271 1444.5,-444 1393.919,-379.1767 1406.1057,-331.7074 1444.5,-259 1452.9608,-242.9778 1463.9052,-228.2987 1476.4106,-214.9167"/>
<polygon fill="#000000" stroke="#000000" points="1479.0489,-217.224 1483.5127,-207.6154 1474.0312,-212.3431 1479.0489,-217.224"/>
<text text-anchor="middle" x="1495" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sequencing_file -->
<g id="node6" class="node">
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
<g id="edge1" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M862.2978,-1013.2045C873.2633,-998.5539 884.1129,-984.0582 894.6853,-969.9327"/>
<polygon fill="#000000" stroke="#000000" points="897.6869,-971.7634 900.877,-961.6602 892.0828,-967.5689 897.6869,-971.7634"/>
<text text-anchor="middle" x="949" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- publication -->
<g id="node7" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M1566.5,-333.5C1566.5,-333.5 1776.5,-333.5 1776.5,-333.5 1782.5,-333.5 1788.5,-339.5 1788.5,-345.5 1788.5,-345.5 1788.5,-357.5 1788.5,-357.5 1788.5,-363.5 1782.5,-369.5 1776.5,-369.5 1776.5,-369.5 1566.5,-369.5 1566.5,-369.5 1560.5,-369.5 1554.5,-363.5 1554.5,-357.5 1554.5,-357.5 1554.5,-345.5 1554.5,-345.5 1554.5,-339.5 1560.5,-333.5 1566.5,-333.5"/>
<text text-anchor="middle" x="1603" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="1651.5,-333.5 1651.5,-369.5 "/>
<text text-anchor="middle" x="1662" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1672.5,-333.5 1672.5,-369.5 "/>
<text text-anchor="middle" x="1720" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="1767.5,-333.5 1767.5,-369.5 "/>
<text text-anchor="middle" x="1778" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge7" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1671.5,-333.3007C1671.5,-308.5479 1671.5,-262.2296 1671.5,-217.6668"/>
<polygon fill="#000000" stroke="#000000" points="1675.0001,-217.5961 1671.5,-207.5961 1668.0001,-217.5961 1675.0001,-217.5961"/>
<text text-anchor="middle" x="1722.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- therapeutic_procedure -->
<g id="node8" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M1429,-743C1429,-743 1786,-743 1786,-743 1792,-743 1798,-749 1798,-755 1798,-755 1798,-846 1798,-846 1798,-852 1792,-858 1786,-858 1786,-858 1429,-858 1429,-858 1423,-858 1417,-852 1417,-846 1417,-846 1417,-755 1417,-755 1417,-749 1423,-743 1429,-743"/>
<text text-anchor="middle" x="1507.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="1598,-743 1598,-858 "/>
<text text-anchor="middle" x="1608.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1619,-743 1619,-858 "/>
<text text-anchor="middle" x="1698" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="1619,-835 1777,-835 "/>
<text text-anchor="middle" x="1698" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="1619,-812 1777,-812 "/>
<text text-anchor="middle" x="1698" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1619,-789 1777,-789 "/>
<text text-anchor="middle" x="1698" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="1619,-766 1777,-766 "/>
<text text-anchor="middle" x="1698" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1777,-743 1777,-858 "/>
<text text-anchor="middle" x="1787.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1599.9938,-742.5663C1597.7866,-700.0919 1602.1612,-643.5211 1633.5,-606 1643.1918,-594.3963 1667.5714,-583.5454 1696.1124,-574.1761"/>
<polygon fill="#000000" stroke="#000000" points="1697.4642,-577.4191 1705.9358,-571.0566 1695.3455,-570.7475 1697.4642,-577.4191"/>
<text text-anchor="middle" x="1726.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- clinical_measure_file -->
<g id="node9" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M2374.5,-674C2374.5,-674 2726.5,-674 2726.5,-674 2732.5,-674 2738.5,-680 2738.5,-686 2738.5,-686 2738.5,-915 2738.5,-915 2738.5,-921 2732.5,-927 2726.5,-927 2726.5,-927 2374.5,-927 2374.5,-927 2368.5,-927 2362.5,-921 2362.5,-915 2362.5,-915 2362.5,-686 2362.5,-686 2362.5,-680 2368.5,-674 2374.5,-674"/>
<text text-anchor="middle" x="2446" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="2529.5,-674 2529.5,-927 "/>
<text text-anchor="middle" x="2540" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2550.5,-674 2550.5,-927 "/>
<text text-anchor="middle" x="2634" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2550.5,-904 2717.5,-904 "/>
<text text-anchor="middle" x="2634" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2550.5,-881 2717.5,-881 "/>
<text text-anchor="middle" x="2634" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2550.5,-858 2717.5,-858 "/>
<text text-anchor="middle" x="2634" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2550.5,-835 2717.5,-835 "/>
<text text-anchor="middle" x="2634" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2550.5,-812 2717.5,-812 "/>
<text text-anchor="middle" x="2634" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2550.5,-789 2717.5,-789 "/>
<text text-anchor="middle" x="2634" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2550.5,-766 2717.5,-766 "/>
<text text-anchor="middle" x="2634" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2550.5,-743 2717.5,-743 "/>
<text text-anchor="middle" x="2634" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2550.5,-720 2717.5,-720 "/>
<text text-anchor="middle" x="2634" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2550.5,-697 2717.5,-697 "/>
<text text-anchor="middle" x="2634" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="2717.5,-674 2717.5,-927 "/>
<text text-anchor="middle" x="2728" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge18" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2547.9397,-673.9041C2543.6802,-523.5301 2532.7206,-289.114 2505.5,-259 2424.8952,-169.8275 2107.9739,-131.3539 1888.8903,-115.1803"/>
<polygon fill="#000000" stroke="#000000" points="1889.087,-111.6854 1878.8593,-114.4503 1888.5788,-118.667 1889.087,-111.6854"/>
<text text-anchor="middle" x="2624.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2413.2528,-673.8235C2394.1301,-660.5185 2373.9872,-648.4339 2353.5,-639 2312.0838,-619.9288 2297.3436,-629.25 2252.5,-621 2158.5595,-603.7176 2052.8949,-583.6648 1971.1781,-568.0226"/>
<polygon fill="#000000" stroke="#000000" points="1971.8137,-564.5807 1961.3338,-566.1373 1970.497,-571.4558 1971.8137,-564.5807"/>
<text text-anchor="middle" x="2382" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- imaging_file -->
<g id="node10" class="node">
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
<g id="edge8" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1073.7978,-1128.3669C1065.7871,-1078.1459 1056.926,-1022.594 1048.8094,-971.7088"/>
<polygon fill="#000000" stroke="#000000" points="1052.228,-970.9208 1047.1965,-961.597 1045.3154,-972.0235 1052.228,-970.9208"/>
<text text-anchor="middle" x="1106" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- study_admin -->
<g id="node11" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M2158.5,-259.5C2158.5,-259.5 2484.5,-259.5 2484.5,-259.5 2490.5,-259.5 2496.5,-265.5 2496.5,-271.5 2496.5,-271.5 2496.5,-431.5 2496.5,-431.5 2496.5,-437.5 2490.5,-443.5 2484.5,-443.5 2484.5,-443.5 2158.5,-443.5 2158.5,-443.5 2152.5,-443.5 2146.5,-437.5 2146.5,-431.5 2146.5,-431.5 2146.5,-271.5 2146.5,-271.5 2146.5,-265.5 2152.5,-259.5 2158.5,-259.5"/>
<text text-anchor="middle" x="2200.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="2254.5,-259.5 2254.5,-443.5 "/>
<text text-anchor="middle" x="2265" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2275.5,-259.5 2275.5,-443.5 "/>
<text text-anchor="middle" x="2375.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="2275.5,-420.5 2475.5,-420.5 "/>
<text text-anchor="middle" x="2375.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="2275.5,-397.5 2475.5,-397.5 "/>
<text text-anchor="middle" x="2375.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="2275.5,-374.5 2475.5,-374.5 "/>
<text text-anchor="middle" x="2375.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="2275.5,-351.5 2475.5,-351.5 "/>
<text text-anchor="middle" x="2375.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="2275.5,-328.5 2475.5,-328.5 "/>
<text text-anchor="middle" x="2375.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="2275.5,-305.5 2475.5,-305.5 "/>
<text text-anchor="middle" x="2375.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="2275.5,-282.5 2475.5,-282.5 "/>
<text text-anchor="middle" x="2375.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="2475.5,-259.5 2475.5,-443.5 "/>
<text text-anchor="middle" x="2486" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge17" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2146.4663,-262.7803C2143.4624,-261.495 2140.472,-260.2337 2137.5,-259 2057.4793,-225.7827 1967.5598,-194.5134 1888.2089,-168.8796"/>
<polygon fill="#000000" stroke="#000000" points="1889.1772,-165.5145 1878.5857,-165.7817 1887.0321,-172.1777 1889.1772,-165.5145"/>
<text text-anchor="middle" x="2145" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- diagnosis -->
<g id="node12" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1949,-651C1949,-651 2332,-651 2332,-651 2338,-651 2344,-657 2344,-663 2344,-663 2344,-938 2344,-938 2344,-944 2338,-950 2332,-950 2332,-950 1949,-950 1949,-950 1943,-950 1937,-944 1937,-938 1937,-938 1937,-663 1937,-663 1937,-657 1943,-651 1949,-651"/>
<text text-anchor="middle" x="1979" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="2021,-651 2021,-950 "/>
<text text-anchor="middle" x="2031.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2042,-651 2042,-950 "/>
<text text-anchor="middle" x="2182.5" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2042,-927 2323,-927 "/>
<text text-anchor="middle" x="2182.5" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="2042,-904 2323,-904 "/>
<text text-anchor="middle" x="2182.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2042,-881 2323,-881 "/>
<text text-anchor="middle" x="2182.5" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="2042,-858 2323,-858 "/>
<text text-anchor="middle" x="2182.5" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="2042,-835 2323,-835 "/>
<text text-anchor="middle" x="2182.5" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="2042,-812 2323,-812 "/>
<text text-anchor="middle" x="2182.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2042,-789 2323,-789 "/>
<text text-anchor="middle" x="2182.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2042,-766 2323,-766 "/>
<text text-anchor="middle" x="2182.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis_reference_source</text>
<polyline fill="none" stroke="#000000" points="2042,-743 2323,-743 "/>
<text text-anchor="middle" x="2182.5" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="2042,-720 2323,-720 "/>
<text text-anchor="middle" x="2182.5" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="2042,-697 2323,-697 "/>
<text text-anchor="middle" x="2182.5" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="2042,-674 2323,-674 "/>
<text text-anchor="middle" x="2182.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="2323,-651 2323,-950 "/>
<text text-anchor="middle" x="2333.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1963.2507,-650.9639C1939.1907,-630.6658 1915.9285,-611.0407 1895.9062,-594.1489"/>
<polygon fill="#000000" stroke="#000000" points="1898.0099,-591.3445 1888.1097,-587.5714 1893.4961,-596.6948 1898.0099,-591.3445"/>
<text text-anchor="middle" x="1969" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge4" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M972.5133,-639.4062C947.2854,-521.6436 937.0273,-364.6805 1020.5,-259 1074.2485,-190.9518 1286.6662,-149.5601 1454.4342,-126.8751"/>
<polygon fill="#000000" stroke="#000000" points="1454.9576,-130.3363 1464.4054,-125.5416 1454.0296,-123.3981 1454.9576,-130.3363"/>
<text text-anchor="middle" x="992" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1190.7142,-722.5934C1257.3505,-693.8007 1335.1241,-662.4936 1407.5,-639 1468.3042,-619.2626 1485.2076,-620.3655 1547.5,-606 1595.7723,-594.8677 1648.6784,-582.8773 1695.7175,-572.2902"/>
<polygon fill="#000000" stroke="#000000" points="1696.6742,-575.6625 1705.6623,-570.0531 1695.1379,-568.8332 1696.6742,-575.6625"/>
<text text-anchor="middle" x="1584" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- methylation_array_file -->
<g id="node14" class="node">
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
<g id="edge2" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M257.9339,-1174.467C293.1136,-1118.9627 341.6287,-1055.3884 399.5,-1013 531.4129,-916.3792 710.5228,-861.346 842.6683,-831.6157"/>
<polygon fill="#000000" stroke="#000000" points="843.4968,-835.0171 852.4994,-829.431 841.9782,-828.1838 843.4968,-835.0171"/>
<text text-anchor="middle" x="535" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study_funding -->
<g id="node15" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M2566,-317C2566,-317 2945,-317 2945,-317 2951,-317 2957,-323 2957,-329 2957,-329 2957,-374 2957,-374 2957,-380 2951,-386 2945,-386 2945,-386 2566,-386 2566,-386 2560,-386 2554,-380 2554,-374 2554,-374 2554,-329 2554,-329 2554,-323 2560,-317 2566,-317"/>
<text text-anchor="middle" x="2613.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="2673,-317 2673,-386 "/>
<text text-anchor="middle" x="2683.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2694,-317 2694,-386 "/>
<text text-anchor="middle" x="2815" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="2694,-363 2936,-363 "/>
<text text-anchor="middle" x="2815" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="2694,-340 2936,-340 "/>
<text text-anchor="middle" x="2815" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="2936,-317 2936,-386 "/>
<text text-anchor="middle" x="2946.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge19" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2708.3656,-316.8606C2666.2684,-287.7516 2601.8015,-247.5483 2539.5,-226 2422.8823,-185.6653 2105.6722,-147.4734 1888.8212,-124.8966"/>
<polygon fill="#000000" stroke="#000000" points="1888.8798,-121.3839 1878.572,-123.8333 1888.1574,-128.3466 1888.8798,-121.3839"/>
<text text-anchor="middle" x="2632.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
</g>
</svg>
</div>
