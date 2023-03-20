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
<svg width="4830pt" height="1965pt"
 viewBox="0.00 0.00 4829.50 1965.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1961)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1961 4825.5,-1961 4825.5,4 -4,4"/>
<!-- publication -->
<g id="node1" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M12,-391C12,-391 222,-391 222,-391 228,-391 234,-397 234,-403 234,-403 234,-415 234,-415 234,-421 228,-427 222,-427 222,-427 12,-427 12,-427 6,-427 0,-421 0,-415 0,-415 0,-403 0,-403 0,-397 6,-391 12,-391"/>
<text text-anchor="middle" x="48.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="97,-391 97,-427 "/>
<text text-anchor="middle" x="107.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="118,-391 118,-427 "/>
<text text-anchor="middle" x="165.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="213,-391 213,-427 "/>
<text text-anchor="middle" x="223.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node8" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M798,-.5C798,-.5 1188,-.5 1188,-.5 1194,-.5 1200,-6.5 1200,-12.5 1200,-12.5 1200,-264.5 1200,-264.5 1200,-270.5 1194,-276.5 1188,-276.5 1188,-276.5 798,-276.5 798,-276.5 792,-276.5 786,-270.5 786,-264.5 786,-264.5 786,-12.5 786,-12.5 786,-6.5 792,-.5 798,-.5"/>
<text text-anchor="middle" x="814" y="-134.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="842,-.5 842,-276.5 "/>
<text text-anchor="middle" x="852.5" y="-134.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="863,-.5 863,-276.5 "/>
<text text-anchor="middle" x="1021" y="-261.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="863,-253.5 1179,-253.5 "/>
<text text-anchor="middle" x="1021" y="-238.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="863,-230.5 1179,-230.5 "/>
<text text-anchor="middle" x="1021" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_shorthand</text>
<polyline fill="none" stroke="#000000" points="863,-207.5 1179,-207.5 "/>
<text text-anchor="middle" x="1021" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="863,-184.5 1179,-184.5 "/>
<text text-anchor="middle" x="1021" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="863,-161.5 1179,-161.5 "/>
<text text-anchor="middle" x="1021" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="863,-138.5 1179,-138.5 "/>
<text text-anchor="middle" x="1021" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="863,-115.5 1179,-115.5 "/>
<text text-anchor="middle" x="1021" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="863,-92.5 1179,-92.5 "/>
<text text-anchor="middle" x="1021" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="863,-69.5 1179,-69.5 "/>
<text text-anchor="middle" x="1021" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="863,-46.5 1179,-46.5 "/>
<text text-anchor="middle" x="1021" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="863,-23.5 1179,-23.5 "/>
<text text-anchor="middle" x="1021" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="1179,-.5 1179,-276.5 "/>
<text text-anchor="middle" x="1189.5" y="-134.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge23" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M116.0437,-390.6169C115.805,-365.2493 119.4569,-319.8369 146,-295 235.189,-211.5443 555.4667,-170.8711 775.5786,-152.363"/>
<polygon fill="#000000" stroke="#000000" points="775.9798,-155.8418 785.6554,-151.5252 775.3998,-148.8658 775.9798,-155.8418"/>
<text text-anchor="middle" x="197" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- sample_diagnosis -->
<g id="node2" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M4376.5,-1496.5C4376.5,-1496.5 4809.5,-1496.5 4809.5,-1496.5 4815.5,-1496.5 4821.5,-1502.5 4821.5,-1508.5 4821.5,-1508.5 4821.5,-1806.5 4821.5,-1806.5 4821.5,-1812.5 4815.5,-1818.5 4809.5,-1818.5 4809.5,-1818.5 4376.5,-1818.5 4376.5,-1818.5 4370.5,-1818.5 4364.5,-1812.5 4364.5,-1806.5 4364.5,-1806.5 4364.5,-1508.5 4364.5,-1508.5 4364.5,-1502.5 4370.5,-1496.5 4376.5,-1496.5"/>
<text text-anchor="middle" x="4436" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="4507.5,-1496.5 4507.5,-1818.5 "/>
<text text-anchor="middle" x="4518" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4528.5,-1496.5 4528.5,-1818.5 "/>
<text text-anchor="middle" x="4664.5" y="-1803.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="4528.5,-1795.5 4800.5,-1795.5 "/>
<text text-anchor="middle" x="4664.5" y="-1780.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="4528.5,-1772.5 4800.5,-1772.5 "/>
<text text-anchor="middle" x="4664.5" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="4528.5,-1749.5 4800.5,-1749.5 "/>
<text text-anchor="middle" x="4664.5" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="4528.5,-1726.5 4800.5,-1726.5 "/>
<text text-anchor="middle" x="4664.5" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="4528.5,-1703.5 4800.5,-1703.5 "/>
<text text-anchor="middle" x="4664.5" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="4528.5,-1680.5 4800.5,-1680.5 "/>
<text text-anchor="middle" x="4664.5" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="4528.5,-1657.5 4800.5,-1657.5 "/>
<text text-anchor="middle" x="4664.5" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="4528.5,-1634.5 4800.5,-1634.5 "/>
<text text-anchor="middle" x="4664.5" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="4528.5,-1611.5 4800.5,-1611.5 "/>
<text text-anchor="middle" x="4664.5" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="4528.5,-1588.5 4800.5,-1588.5 "/>
<text text-anchor="middle" x="4664.5" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="4528.5,-1565.5 4800.5,-1565.5 "/>
<text text-anchor="middle" x="4664.5" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="4528.5,-1542.5 4800.5,-1542.5 "/>
<text text-anchor="middle" x="4664.5" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="4528.5,-1519.5 4800.5,-1519.5 "/>
<text text-anchor="middle" x="4664.5" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="4800.5,-1496.5 4800.5,-1818.5 "/>
<text text-anchor="middle" x="4811" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node5" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M2915,-927C2915,-927 3229,-927 3229,-927 3235,-927 3241,-933 3241,-939 3241,-939 3241,-1076 3241,-1076 3241,-1082 3235,-1088 3229,-1088 3229,-1088 2915,-1088 2915,-1088 2909,-1088 2903,-1082 2903,-1076 2903,-1076 2903,-939 2903,-939 2903,-933 2909,-927 2915,-927"/>
<text text-anchor="middle" x="2937" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="2971,-927 2971,-1088 "/>
<text text-anchor="middle" x="2981.5" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2992,-927 2992,-1088 "/>
<text text-anchor="middle" x="3106" y="-1072.8" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="2992,-1065 3220,-1065 "/>
<text text-anchor="middle" x="3106" y="-1049.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="2992,-1042 3220,-1042 "/>
<text text-anchor="middle" x="3106" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="2992,-1019 3220,-1019 "/>
<text text-anchor="middle" x="3106" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="2992,-996 3220,-996 "/>
<text text-anchor="middle" x="3106" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="2992,-973 3220,-973 "/>
<text text-anchor="middle" x="3106" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="2992,-950 3220,-950 "/>
<text text-anchor="middle" x="3106" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="3220,-927 3220,-1088 "/>
<text text-anchor="middle" x="3230.5" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M4494.4387,-1496.2361C4456.4618,-1445.5876 4409.058,-1393.6494 4355,-1358 4007.4356,-1128.7931 3513.0082,-1048.5847 3251.0118,-1021.1916"/>
<polygon fill="#000000" stroke="#000000" points="3251.3277,-1017.7057 3241.0212,-1020.1609 3250.6092,-1024.6687 3251.3277,-1017.7057"/>
<text text-anchor="middle" x="4399" y="-1328.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
<!-- synonym -->
<g id="node3" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M1714.5,-1634.5C1714.5,-1634.5 2015.5,-1634.5 2015.5,-1634.5 2021.5,-1634.5 2027.5,-1640.5 2027.5,-1646.5 2027.5,-1646.5 2027.5,-1668.5 2027.5,-1668.5 2027.5,-1674.5 2021.5,-1680.5 2015.5,-1680.5 2015.5,-1680.5 1714.5,-1680.5 1714.5,-1680.5 1708.5,-1680.5 1702.5,-1674.5 1702.5,-1668.5 1702.5,-1668.5 1702.5,-1646.5 1702.5,-1646.5 1702.5,-1640.5 1708.5,-1634.5 1714.5,-1634.5"/>
<text text-anchor="middle" x="1742.5" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="1782.5,-1634.5 1782.5,-1680.5 "/>
<text text-anchor="middle" x="1793" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1803.5,-1634.5 1803.5,-1680.5 "/>
<text text-anchor="middle" x="1905" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="1803.5,-1657.5 2006.5,-1657.5 "/>
<text text-anchor="middle" x="1905" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="2006.5,-1634.5 2006.5,-1680.5 "/>
<text text-anchor="middle" x="2017" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1870.4473,-1634.4891C1885.5043,-1576.534 1933.5947,-1424.4582 2037,-1358 2169.9289,-1272.5671 2233.3117,-1335.163 2391,-1325 2418.9044,-1323.2016 2869.9472,-1321.2603 2894,-1307 2971.0231,-1261.3348 3018.4884,-1168.3316 3044.8245,-1098.0089"/>
<polygon fill="#000000" stroke="#000000" points="3048.2483,-1098.8376 3048.4013,-1088.2439 3041.6753,-1096.43 3048.2483,-1098.8376"/>
<text text-anchor="middle" x="2433.5" y="-1328.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge17" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1702.2283,-1645.6596C1336.0611,-1615.3955 465.0625,-1521.9284 281,-1307 194.2423,-1205.6937 262,-1140.8787 262,-1007.5 262,-1007.5 262,-1007.5 262,-409 262,-298.3012 560.579,-218.6118 776.0915,-175.5107"/>
<polygon fill="#000000" stroke="#000000" points="776.8414,-178.9302 785.9681,-173.5493 775.4779,-172.0642 776.8414,-178.9302"/>
<text text-anchor="middle" x="304.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- participant -->
<g id="node21" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M1574,-541.5C1574,-541.5 1878,-541.5 1878,-541.5 1884,-541.5 1890,-547.5 1890,-553.5 1890,-553.5 1890,-644.5 1890,-644.5 1890,-650.5 1884,-656.5 1878,-656.5 1878,-656.5 1574,-656.5 1574,-656.5 1568,-656.5 1562,-650.5 1562,-644.5 1562,-644.5 1562,-553.5 1562,-553.5 1562,-547.5 1568,-541.5 1574,-541.5"/>
<text text-anchor="middle" x="1610" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1658,-541.5 1658,-656.5 "/>
<text text-anchor="middle" x="1668.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1679,-541.5 1679,-656.5 "/>
<text text-anchor="middle" x="1774" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="1679,-633.5 1869,-633.5 "/>
<text text-anchor="middle" x="1774" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="1679,-610.5 1869,-610.5 "/>
<text text-anchor="middle" x="1774" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="1679,-587.5 1869,-587.5 "/>
<text text-anchor="middle" x="1774" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1679,-564.5 1869,-564.5 "/>
<text text-anchor="middle" x="1774" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1869,-541.5 1869,-656.5 "/>
<text text-anchor="middle" x="1879.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1872.703,-1634.4783C1890.8248,-1578.9574 1935.7728,-1432.9606 1951,-1307 1966.9754,-1174.851 2021.6882,-820.7907 1951,-708 1937.8824,-687.0695 1919.4779,-670.0582 1898.7853,-656.258"/>
<polygon fill="#000000" stroke="#000000" points="1900.4252,-653.1529 1890.1099,-650.7349 1896.6659,-659.0578 1900.4252,-653.1529"/>
<text text-anchor="middle" x="2028.5" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- clinical_measure_file -->
<g id="node4" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M302,-881C302,-881 654,-881 654,-881 660,-881 666,-887 666,-893 666,-893 666,-1122 666,-1122 666,-1128 660,-1134 654,-1134 654,-1134 302,-1134 302,-1134 296,-1134 290,-1128 290,-1122 290,-1122 290,-893 290,-893 290,-887 296,-881 302,-881"/>
<text text-anchor="middle" x="373.5" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="457,-881 457,-1134 "/>
<text text-anchor="middle" x="467.5" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="478,-881 478,-1134 "/>
<text text-anchor="middle" x="561.5" y="-1118.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="478,-1111 645,-1111 "/>
<text text-anchor="middle" x="561.5" y="-1095.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="478,-1088 645,-1088 "/>
<text text-anchor="middle" x="561.5" y="-1072.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="478,-1065 645,-1065 "/>
<text text-anchor="middle" x="561.5" y="-1049.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="478,-1042 645,-1042 "/>
<text text-anchor="middle" x="561.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="478,-1019 645,-1019 "/>
<text text-anchor="middle" x="561.5" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="478,-996 645,-996 "/>
<text text-anchor="middle" x="561.5" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="478,-973 645,-973 "/>
<text text-anchor="middle" x="561.5" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="478,-950 645,-950 "/>
<text text-anchor="middle" x="561.5" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="478,-927 645,-927 "/>
<text text-anchor="middle" x="561.5" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="478,-904 645,-904 "/>
<text text-anchor="middle" x="561.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="645,-881 645,-1134 "/>
<text text-anchor="middle" x="655.5" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge6" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M479.1202,-880.8833C483.3954,-777.9436 497.2692,-630.2624 539,-508 569.0629,-419.9219 584.195,-397.5821 646,-328 682.1541,-287.2966 729.2134,-253.6249 776.9503,-226.5348"/>
<polygon fill="#000000" stroke="#000000" points="778.8457,-229.4851 785.8692,-221.5529 775.4321,-223.3739 778.8457,-229.4851"/>
<text text-anchor="middle" x="625" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M530.8758,-880.9043C563.3362,-818.9107 611.0737,-748.9702 675,-708 747.0137,-661.8466 1271.9452,-625.088 1551.6287,-608.5324"/>
<polygon fill="#000000" stroke="#000000" points="1552.1072,-612.0104 1561.8839,-607.9279 1551.6952,-605.0225 1552.1072,-612.0104"/>
<text text-anchor="middle" x="930.5" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge13" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3048.8933,-926.8814C3024.546,-853.7687 2980.0299,-746.7603 2911,-675 2683.7002,-438.7097 2571.3187,-430.854 2260,-328 1903.7652,-210.3065 1466.8889,-165.4379 1210.3131,-148.5223"/>
<polygon fill="#000000" stroke="#000000" points="1210.3332,-145.0163 1200.127,-147.8592 1209.8784,-152.0015 1210.3332,-145.0163"/>
<text text-anchor="middle" x="2773.5" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3047.3679,-926.8C3021.3111,-856.3697 2972.8601,-757.8605 2894,-708 2812.0358,-656.1769 2205.5182,-621.1317 1900.3425,-606.5844"/>
<polygon fill="#000000" stroke="#000000" points="1900.2164,-603.0746 1890.0617,-606.0966 1899.8846,-610.0667 1900.2164,-603.0746"/>
<text text-anchor="middle" x="2870.5" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- therapeutic_procedure -->
<g id="node6" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M696,-950C696,-950 1088,-950 1088,-950 1094,-950 1100,-956 1100,-962 1100,-962 1100,-1053 1100,-1053 1100,-1059 1094,-1065 1088,-1065 1088,-1065 696,-1065 696,-1065 690,-1065 684,-1059 684,-1053 684,-1053 684,-962 684,-962 684,-956 690,-950 696,-950"/>
<text text-anchor="middle" x="774.5" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="865,-950 865,-1065 "/>
<text text-anchor="middle" x="875.5" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="886,-950 886,-1065 "/>
<text text-anchor="middle" x="982.5" y="-1049.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment_start</text>
<polyline fill="none" stroke="#000000" points="886,-1042 1079,-1042 "/>
<text text-anchor="middle" x="982.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="886,-1019 1079,-1019 "/>
<text text-anchor="middle" x="982.5" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="886,-996 1079,-996 "/>
<text text-anchor="middle" x="982.5" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="886,-973 1079,-973 "/>
<text text-anchor="middle" x="982.5" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1079,-950 1079,-1065 "/>
<text text-anchor="middle" x="1089.5" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M916.9566,-949.9439C950.1842,-880.6541 1015.7965,-766.3461 1109,-708 1181.1759,-662.8174 1395.841,-632.1314 1551.7151,-615.1098"/>
<polygon fill="#000000" stroke="#000000" points="1552.3296,-618.5638 1561.8951,-614.0084 1551.5766,-611.6044 1552.3296,-618.5638"/>
<text text-anchor="middle" x="1285" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- methylation_array_file -->
<g id="node7" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M2057.5,-1542.5C2057.5,-1542.5 2424.5,-1542.5 2424.5,-1542.5 2430.5,-1542.5 2436.5,-1548.5 2436.5,-1554.5 2436.5,-1554.5 2436.5,-1760.5 2436.5,-1760.5 2436.5,-1766.5 2430.5,-1772.5 2424.5,-1772.5 2424.5,-1772.5 2057.5,-1772.5 2057.5,-1772.5 2051.5,-1772.5 2045.5,-1766.5 2045.5,-1760.5 2045.5,-1760.5 2045.5,-1554.5 2045.5,-1554.5 2045.5,-1548.5 2051.5,-1542.5 2057.5,-1542.5"/>
<text text-anchor="middle" x="2134.5" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="2223.5,-1542.5 2223.5,-1772.5 "/>
<text text-anchor="middle" x="2234" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2244.5,-1542.5 2244.5,-1772.5 "/>
<text text-anchor="middle" x="2330" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2244.5,-1749.5 2415.5,-1749.5 "/>
<text text-anchor="middle" x="2330" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2244.5,-1726.5 2415.5,-1726.5 "/>
<text text-anchor="middle" x="2330" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2244.5,-1703.5 2415.5,-1703.5 "/>
<text text-anchor="middle" x="2330" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2244.5,-1680.5 2415.5,-1680.5 "/>
<text text-anchor="middle" x="2330" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2244.5,-1657.5 2415.5,-1657.5 "/>
<text text-anchor="middle" x="2330" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2244.5,-1634.5 2415.5,-1634.5 "/>
<text text-anchor="middle" x="2330" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2244.5,-1611.5 2415.5,-1611.5 "/>
<text text-anchor="middle" x="2330" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2244.5,-1588.5 2415.5,-1588.5 "/>
<text text-anchor="middle" x="2330" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="2244.5,-1565.5 2415.5,-1565.5 "/>
<text text-anchor="middle" x="2330" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="2415.5,-1542.5 2415.5,-1772.5 "/>
<text text-anchor="middle" x="2426" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2291.1933,-1542.3516C2325.4033,-1477.7715 2377.0536,-1401.6428 2446,-1358 2524.7168,-1308.1726 2560.4678,-1335.8122 2653,-1325 2706.3418,-1318.7671 2848.3438,-1335.2791 2894,-1307 2969.8776,-1260.0021 3017.4219,-1167.6773 3044.0861,-1097.8935"/>
<polygon fill="#000000" stroke="#000000" points="3047.4854,-1098.7958 3047.7107,-1088.2033 3040.929,-1096.3433 3047.4854,-1098.7958"/>
<text text-anchor="middle" x="2744.5" y="-1328.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- pdx -->
<g id="node9" class="node">
<title>pdx</title>
<path fill="none" stroke="#000000" d="M2466.5,-1554C2466.5,-1554 2795.5,-1554 2795.5,-1554 2801.5,-1554 2807.5,-1560 2807.5,-1566 2807.5,-1566 2807.5,-1749 2807.5,-1749 2807.5,-1755 2801.5,-1761 2795.5,-1761 2795.5,-1761 2466.5,-1761 2466.5,-1761 2460.5,-1761 2454.5,-1755 2454.5,-1749 2454.5,-1749 2454.5,-1566 2454.5,-1566 2454.5,-1560 2460.5,-1554 2466.5,-1554"/>
<text text-anchor="middle" x="2476" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
<polyline fill="none" stroke="#000000" points="2497.5,-1554 2497.5,-1761 "/>
<text text-anchor="middle" x="2508" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2518.5,-1554 2518.5,-1761 "/>
<text text-anchor="middle" x="2652.5" y="-1745.8" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_site</text>
<polyline fill="none" stroke="#000000" points="2518.5,-1738 2786.5,-1738 "/>
<text text-anchor="middle" x="2652.5" y="-1722.8" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_type</text>
<polyline fill="none" stroke="#000000" points="2518.5,-1715 2786.5,-1715 "/>
<text text-anchor="middle" x="2652.5" y="-1699.8" font-family="Times,serif" font-size="14.00" fill="#000000">model_id</text>
<polyline fill="none" stroke="#000000" points="2518.5,-1692 2786.5,-1692 "/>
<text text-anchor="middle" x="2652.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">mouse_strain</text>
<polyline fill="none" stroke="#000000" points="2518.5,-1669 2786.5,-1669 "/>
<text text-anchor="middle" x="2652.5" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000">strain_immune_system_humanized</text>
<polyline fill="none" stroke="#000000" points="2518.5,-1646 2786.5,-1646 "/>
<text text-anchor="middle" x="2652.5" y="-1630.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_characterization_method</text>
<polyline fill="none" stroke="#000000" points="2518.5,-1623 2786.5,-1623 "/>
<text text-anchor="middle" x="2652.5" y="-1607.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_not_mus_or_ebv_origin</text>
<polyline fill="none" stroke="#000000" points="2518.5,-1600 2786.5,-1600 "/>
<text text-anchor="middle" x="2652.5" y="-1584.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_preparation</text>
<polyline fill="none" stroke="#000000" points="2518.5,-1577 2786.5,-1577 "/>
<text text-anchor="middle" x="2652.5" y="-1561.8" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_humanization</text>
<polyline fill="none" stroke="#000000" points="2786.5,-1554 2786.5,-1761 "/>
<text text-anchor="middle" x="2797" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2680.9644,-1553.8031C2713.923,-1492.3043 2761.2447,-1415.4109 2817,-1358 2845.5976,-1328.5532 2865.6909,-1336.7243 2894,-1307 2952.7448,-1245.3184 3000.7227,-1160.8683 3032.003,-1097.3645"/>
<polygon fill="#000000" stroke="#000000" points="3035.2581,-1098.6745 3036.4962,-1088.1522 3028.9666,-1095.6058 3035.2581,-1098.6745"/>
<text text-anchor="middle" x="2894" y="-1328.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- sequencing_file -->
<g id="node10" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M2837.5,-1370C2837.5,-1370 3306.5,-1370 3306.5,-1370 3312.5,-1370 3318.5,-1376 3318.5,-1382 3318.5,-1382 3318.5,-1933 3318.5,-1933 3318.5,-1939 3312.5,-1945 3306.5,-1945 3306.5,-1945 2837.5,-1945 2837.5,-1945 2831.5,-1945 2825.5,-1939 2825.5,-1933 2825.5,-1933 2825.5,-1382 2825.5,-1382 2825.5,-1376 2831.5,-1370 2837.5,-1370"/>
<text text-anchor="middle" x="2889.5" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="2953.5,-1370 2953.5,-1945 "/>
<text text-anchor="middle" x="2964" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2974.5,-1370 2974.5,-1945 "/>
<text text-anchor="middle" x="3136" y="-1929.8" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="2974.5,-1922 3297.5,-1922 "/>
<text text-anchor="middle" x="3136" y="-1906.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2974.5,-1899 3297.5,-1899 "/>
<text text-anchor="middle" x="3136" y="-1883.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2974.5,-1876 3297.5,-1876 "/>
<text text-anchor="middle" x="3136" y="-1860.8" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="2974.5,-1853 3297.5,-1853 "/>
<text text-anchor="middle" x="3136" y="-1837.8" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="2974.5,-1830 3297.5,-1830 "/>
<text text-anchor="middle" x="3136" y="-1814.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2974.5,-1807 3297.5,-1807 "/>
<text text-anchor="middle" x="3136" y="-1791.8" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="2974.5,-1784 3297.5,-1784 "/>
<text text-anchor="middle" x="3136" y="-1768.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2974.5,-1761 3297.5,-1761 "/>
<text text-anchor="middle" x="3136" y="-1745.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2974.5,-1738 3297.5,-1738 "/>
<text text-anchor="middle" x="3136" y="-1722.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2974.5,-1715 3297.5,-1715 "/>
<text text-anchor="middle" x="3136" y="-1699.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2974.5,-1692 3297.5,-1692 "/>
<text text-anchor="middle" x="3136" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2974.5,-1669 3297.5,-1669 "/>
<text text-anchor="middle" x="3136" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2974.5,-1646 3297.5,-1646 "/>
<text text-anchor="middle" x="3136" y="-1630.8" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="2974.5,-1623 3297.5,-1623 "/>
<text text-anchor="middle" x="3136" y="-1607.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="2974.5,-1600 3297.5,-1600 "/>
<text text-anchor="middle" x="3136" y="-1584.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="2974.5,-1577 3297.5,-1577 "/>
<text text-anchor="middle" x="3136" y="-1561.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="2974.5,-1554 3297.5,-1554 "/>
<text text-anchor="middle" x="3136" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="2974.5,-1531 3297.5,-1531 "/>
<text text-anchor="middle" x="3136" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="2974.5,-1508 3297.5,-1508 "/>
<text text-anchor="middle" x="3136" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2974.5,-1485 3297.5,-1485 "/>
<text text-anchor="middle" x="3136" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="2974.5,-1462 3297.5,-1462 "/>
<text text-anchor="middle" x="3136" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="2974.5,-1439 3297.5,-1439 "/>
<text text-anchor="middle" x="3136" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="2974.5,-1416 3297.5,-1416 "/>
<text text-anchor="middle" x="3136" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="2974.5,-1393 3297.5,-1393 "/>
<text text-anchor="middle" x="3136" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="3297.5,-1370 3297.5,-1945 "/>
<text text-anchor="middle" x="3308" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3072,-1369.562C3072,-1271.6551 3072,-1169.2023 3072,-1098.3708"/>
<polygon fill="#000000" stroke="#000000" points="3075.5001,-1098.1539 3072,-1088.154 3068.5001,-1098.154 3075.5001,-1098.1539"/>
<text text-anchor="middle" x="3138.5" y="-1328.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- study_funding -->
<g id="node11" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M803.5,-374.5C803.5,-374.5 1182.5,-374.5 1182.5,-374.5 1188.5,-374.5 1194.5,-380.5 1194.5,-386.5 1194.5,-386.5 1194.5,-431.5 1194.5,-431.5 1194.5,-437.5 1188.5,-443.5 1182.5,-443.5 1182.5,-443.5 803.5,-443.5 803.5,-443.5 797.5,-443.5 791.5,-437.5 791.5,-431.5 791.5,-431.5 791.5,-386.5 791.5,-386.5 791.5,-380.5 797.5,-374.5 803.5,-374.5"/>
<text text-anchor="middle" x="851" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="910.5,-374.5 910.5,-443.5 "/>
<text text-anchor="middle" x="921" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="931.5,-374.5 931.5,-443.5 "/>
<text text-anchor="middle" x="1052.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="931.5,-420.5 1173.5,-420.5 "/>
<text text-anchor="middle" x="1052.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="931.5,-397.5 1173.5,-397.5 "/>
<text text-anchor="middle" x="1052.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="1173.5,-374.5 1173.5,-443.5 "/>
<text text-anchor="middle" x="1184" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge5" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M993,-374.4662C993,-351.5553 993,-319.7488 993,-286.8978"/>
<polygon fill="#000000" stroke="#000000" points="996.5001,-286.6778 993,-276.6779 989.5001,-286.6779 996.5001,-286.6778"/>
<text text-anchor="middle" x="1055" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- study_personnel -->
<g id="node12" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M1224.5,-351.5C1224.5,-351.5 1531.5,-351.5 1531.5,-351.5 1537.5,-351.5 1543.5,-357.5 1543.5,-363.5 1543.5,-363.5 1543.5,-454.5 1543.5,-454.5 1543.5,-460.5 1537.5,-466.5 1531.5,-466.5 1531.5,-466.5 1224.5,-466.5 1224.5,-466.5 1218.5,-466.5 1212.5,-460.5 1212.5,-454.5 1212.5,-454.5 1212.5,-363.5 1212.5,-363.5 1212.5,-357.5 1218.5,-351.5 1224.5,-351.5"/>
<text text-anchor="middle" x="1279.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="1346.5,-351.5 1346.5,-466.5 "/>
<text text-anchor="middle" x="1357" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1367.5,-351.5 1367.5,-466.5 "/>
<text text-anchor="middle" x="1445" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="1367.5,-443.5 1522.5,-443.5 "/>
<text text-anchor="middle" x="1445" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="1367.5,-420.5 1522.5,-420.5 "/>
<text text-anchor="middle" x="1445" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="1367.5,-397.5 1522.5,-397.5 "/>
<text text-anchor="middle" x="1445" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="1367.5,-374.5 1522.5,-374.5 "/>
<text text-anchor="middle" x="1445" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="1522.5,-351.5 1522.5,-466.5 "/>
<text text-anchor="middle" x="1533" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge21" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1295.8801,-351.3027C1266.8482,-330.905 1232.7572,-306.9528 1198.119,-282.6161"/>
<polygon fill="#000000" stroke="#000000" points="1199.9746,-279.6423 1189.7801,-276.7572 1195.9503,-285.3699 1199.9746,-279.6423"/>
<text text-anchor="middle" x="1301.5" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- study_arm -->
<g id="node13" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M1573.5,-374.5C1573.5,-374.5 1870.5,-374.5 1870.5,-374.5 1876.5,-374.5 1882.5,-380.5 1882.5,-386.5 1882.5,-386.5 1882.5,-431.5 1882.5,-431.5 1882.5,-437.5 1876.5,-443.5 1870.5,-443.5 1870.5,-443.5 1573.5,-443.5 1573.5,-443.5 1567.5,-443.5 1561.5,-437.5 1561.5,-431.5 1561.5,-431.5 1561.5,-386.5 1561.5,-386.5 1561.5,-380.5 1567.5,-374.5 1573.5,-374.5"/>
<text text-anchor="middle" x="1607.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="1653.5,-374.5 1653.5,-443.5 "/>
<text text-anchor="middle" x="1664" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1674.5,-374.5 1674.5,-443.5 "/>
<text text-anchor="middle" x="1768" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="1674.5,-420.5 1861.5,-420.5 "/>
<text text-anchor="middle" x="1768" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="1674.5,-397.5 1861.5,-397.5 "/>
<text text-anchor="middle" x="1768" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="1861.5,-374.5 1861.5,-443.5 "/>
<text text-anchor="middle" x="1872" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge25" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1654.5901,-374.3903C1623.9706,-359.2695 1587.0522,-341.863 1553,-328 1441.5724,-282.6368 1314.7812,-239.0865 1210.0563,-205.1992"/>
<polygon fill="#000000" stroke="#000000" points="1210.9055,-201.7955 1200.3139,-202.0539 1208.7549,-208.457 1210.9055,-201.7955"/>
<text text-anchor="middle" x="1541.5" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node14" class="node">
<title>single_cell_sequencing_file</title>
<path fill="none" stroke="#000000" d="M3348.5,-1358.5C3348.5,-1358.5 3957.5,-1358.5 3957.5,-1358.5 3963.5,-1358.5 3969.5,-1364.5 3969.5,-1370.5 3969.5,-1370.5 3969.5,-1944.5 3969.5,-1944.5 3969.5,-1950.5 3963.5,-1956.5 3957.5,-1956.5 3957.5,-1956.5 3348.5,-1956.5 3348.5,-1956.5 3342.5,-1956.5 3336.5,-1950.5 3336.5,-1944.5 3336.5,-1944.5 3336.5,-1370.5 3336.5,-1370.5 3336.5,-1364.5 3342.5,-1358.5 3348.5,-1358.5"/>
<text text-anchor="middle" x="3442.5" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
<polyline fill="none" stroke="#000000" points="3548.5,-1358.5 3548.5,-1956.5 "/>
<text text-anchor="middle" x="3559" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3569.5,-1358.5 3569.5,-1956.5 "/>
<text text-anchor="middle" x="3759" y="-1941.3" font-family="Times,serif" font-size="14.00" fill="#000000">Cell_Barcode</text>
<polyline fill="none" stroke="#000000" points="3569.5,-1933.5 3948.5,-1933.5 "/>
<text text-anchor="middle" x="3759" y="-1918.3" font-family="Times,serif" font-size="14.00" fill="#000000">Cryopreserved_Cells_in_Sample</text>
<polyline fill="none" stroke="#000000" points="3569.5,-1910.5 3948.5,-1910.5 "/>
<text text-anchor="middle" x="3759" y="-1895.3" font-family="Times,serif" font-size="14.00" fill="#000000">Dissociation_Method</text>
<polyline fill="none" stroke="#000000" points="3569.5,-1887.5 3948.5,-1887.5 "/>
<text text-anchor="middle" x="3759" y="-1872.3" font-family="Times,serif" font-size="14.00" fill="#000000">End_Bias</text>
<polyline fill="none" stroke="#000000" points="3569.5,-1864.5 3948.5,-1864.5 "/>
<text text-anchor="middle" x="3759" y="-1849.3" font-family="Times,serif" font-size="14.00" fill="#000000">Input_Cells_and_Nuclei</text>
<polyline fill="none" stroke="#000000" points="3569.5,-1841.5 3948.5,-1841.5 "/>
<text text-anchor="middle" x="3759" y="-1826.3" font-family="Times,serif" font-size="14.00" fill="#000000">Library_Construction_Method</text>
<polyline fill="none" stroke="#000000" points="3569.5,-1818.5 3948.5,-1818.5 "/>
<text text-anchor="middle" x="3759" y="-1803.3" font-family="Times,serif" font-size="14.00" fill="#000000">Library_Preparation_Date</text>
<polyline fill="none" stroke="#000000" points="3569.5,-1795.5 3948.5,-1795.5 "/>
<text text-anchor="middle" x="3759" y="-1780.3" font-family="Times,serif" font-size="14.00" fill="#000000">Nucleic_Acid_Capture_Date</text>
<polyline fill="none" stroke="#000000" points="3569.5,-1772.5 3948.5,-1772.5 "/>
<text text-anchor="middle" x="3759" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">Paired_End</text>
<polyline fill="none" stroke="#000000" points="3569.5,-1749.5 3948.5,-1749.5 "/>
<text text-anchor="middle" x="3759" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">Protocols_Link</text>
<polyline fill="none" stroke="#000000" points="3569.5,-1726.5 3948.5,-1726.5 "/>
<text text-anchor="middle" x="3759" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">Read1</text>
<polyline fill="none" stroke="#000000" points="3569.5,-1703.5 3948.5,-1703.5 "/>
<text text-anchor="middle" x="3759" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">Read2</text>
<polyline fill="none" stroke="#000000" points="3569.5,-1680.5 3948.5,-1680.5 "/>
<text text-anchor="middle" x="3759" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Feature_barcoding</text>
<polyline fill="none" stroke="#000000" points="3569.5,-1657.5 3948.5,-1657.5 "/>
<text text-anchor="middle" x="3759" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Oligo_dT_Poly_dT</text>
<polyline fill="none" stroke="#000000" points="3569.5,-1634.5 3948.5,-1634.5 "/>
<text text-anchor="middle" x="3759" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Random</text>
<polyline fill="none" stroke="#000000" points="3569.5,-1611.5 3948.5,-1611.5 "/>
<text text-anchor="middle" x="3759" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">Sequencing_Library_Construction_Date</text>
<polyline fill="none" stroke="#000000" points="3569.5,-1588.5 3948.5,-1588.5 "/>
<text text-anchor="middle" x="3759" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">Single_Cell_Dissociation_Date</text>
<polyline fill="none" stroke="#000000" points="3569.5,-1565.5 3948.5,-1565.5 "/>
<text text-anchor="middle" x="3759" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">Single_Cell_Isolation_Method</text>
<polyline fill="none" stroke="#000000" points="3569.5,-1542.5 3948.5,-1542.5 "/>
<text text-anchor="middle" x="3759" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">Spike_In</text>
<polyline fill="none" stroke="#000000" points="3569.5,-1519.5 3948.5,-1519.5 "/>
<text text-anchor="middle" x="3759" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">Total_Number_of_Input_Cells</text>
<polyline fill="none" stroke="#000000" points="3569.5,-1496.5 3948.5,-1496.5 "/>
<text text-anchor="middle" x="3759" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">UMI</text>
<polyline fill="none" stroke="#000000" points="3569.5,-1473.5 3948.5,-1473.5 "/>
<text text-anchor="middle" x="3759" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="3569.5,-1450.5 3948.5,-1450.5 "/>
<text text-anchor="middle" x="3759" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">cDNA_Length</text>
<polyline fill="none" stroke="#000000" points="3569.5,-1427.5 3948.5,-1427.5 "/>
<text text-anchor="middle" x="3759" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">cDNA_Offset</text>
<polyline fill="none" stroke="#000000" points="3569.5,-1404.5 3948.5,-1404.5 "/>
<text text-anchor="middle" x="3759" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="3569.5,-1381.5 3948.5,-1381.5 "/>
<text text-anchor="middle" x="3759" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 23 properties</text>
<polyline fill="none" stroke="#000000" points="3948.5,-1358.5 3948.5,-1956.5 "/>
<text text-anchor="middle" x="3959" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3385.4577,-1358.1842C3300.0005,-1262.578 3211.877,-1163.9889 3150.9167,-1095.7889"/>
<polygon fill="#000000" stroke="#000000" points="3153.265,-1093.1642 3143.9912,-1088.041 3148.046,-1097.8292 3153.265,-1093.1642"/>
<text text-anchor="middle" x="3470.5" y="-1328.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- family_relationship -->
<g id="node15" class="node">
<title>family_relationship</title>
<path fill="none" stroke="#000000" d="M1130.5,-973C1130.5,-973 1499.5,-973 1499.5,-973 1505.5,-973 1511.5,-979 1511.5,-985 1511.5,-985 1511.5,-1030 1511.5,-1030 1511.5,-1036 1505.5,-1042 1499.5,-1042 1499.5,-1042 1130.5,-1042 1130.5,-1042 1124.5,-1042 1118.5,-1036 1118.5,-1030 1118.5,-1030 1118.5,-985 1118.5,-985 1118.5,-979 1124.5,-973 1130.5,-973"/>
<text text-anchor="middle" x="1195.5" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
<polyline fill="none" stroke="#000000" points="1272.5,-973 1272.5,-1042 "/>
<text text-anchor="middle" x="1283" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1293.5,-973 1293.5,-1042 "/>
<text text-anchor="middle" x="1392" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">family_id</text>
<polyline fill="none" stroke="#000000" points="1293.5,-1019 1490.5,-1019 "/>
<text text-anchor="middle" x="1392" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">related_to_participant_id</text>
<polyline fill="none" stroke="#000000" points="1293.5,-996 1490.5,-996 "/>
<text text-anchor="middle" x="1392" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">relationship</text>
<polyline fill="none" stroke="#000000" points="1490.5,-973 1490.5,-1042 "/>
<text text-anchor="middle" x="1501" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1329.9662,-972.8454C1361.8544,-903.5515 1443.5529,-748.2864 1564,-675 1571.6011,-670.3751 1579.5291,-665.8338 1587.6157,-661.4152"/>
<polygon fill="#000000" stroke="#000000" points="1589.2929,-664.4873 1596.4448,-656.6707 1585.9793,-658.3212 1589.2929,-664.4873"/>
<text text-anchor="middle" x="1643.5" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- study_admin -->
<g id="node16" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M1913,-328.5C1913,-328.5 2239,-328.5 2239,-328.5 2245,-328.5 2251,-334.5 2251,-340.5 2251,-340.5 2251,-477.5 2251,-477.5 2251,-483.5 2245,-489.5 2239,-489.5 2239,-489.5 1913,-489.5 1913,-489.5 1907,-489.5 1901,-483.5 1901,-477.5 1901,-477.5 1901,-340.5 1901,-340.5 1901,-334.5 1907,-328.5 1913,-328.5"/>
<text text-anchor="middle" x="1955" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="2009,-328.5 2009,-489.5 "/>
<text text-anchor="middle" x="2019.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2030,-328.5 2030,-489.5 "/>
<text text-anchor="middle" x="2130" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="2030,-466.5 2230,-466.5 "/>
<text text-anchor="middle" x="2130" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="2030,-443.5 2230,-443.5 "/>
<text text-anchor="middle" x="2130" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="2030,-420.5 2230,-420.5 "/>
<text text-anchor="middle" x="2130" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="2030,-397.5 2230,-397.5 "/>
<text text-anchor="middle" x="2130" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="2030,-374.5 2230,-374.5 "/>
<text text-anchor="middle" x="2130" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="2030,-351.5 2230,-351.5 "/>
<text text-anchor="middle" x="2130" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="2230,-328.5 2230,-489.5 "/>
<text text-anchor="middle" x="2240.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge4" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1900.766,-330.8945C1897.8308,-329.9011 1894.9073,-328.9352 1892,-328 1664.0628,-254.679 1394.3282,-202.1881 1210.1885,-171.3092"/>
<polygon fill="#000000" stroke="#000000" points="1210.5522,-167.8216 1200.1123,-169.6268 1209.3993,-174.726 1210.5522,-167.8216"/>
<text text-anchor="middle" x="1876.5" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- molecular_test -->
<g id="node17" class="node">
<title>molecular_test</title>
<path fill="none" stroke="#000000" d="M1542,-708.5C1542,-708.5 1930,-708.5 1930,-708.5 1936,-708.5 1942,-714.5 1942,-720.5 1942,-720.5 1942,-1294.5 1942,-1294.5 1942,-1300.5 1936,-1306.5 1930,-1306.5 1930,-1306.5 1542,-1306.5 1542,-1306.5 1536,-1306.5 1530,-1300.5 1530,-1294.5 1530,-1294.5 1530,-720.5 1530,-720.5 1530,-714.5 1536,-708.5 1542,-708.5"/>
<text text-anchor="middle" x="1591.5" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
<polyline fill="none" stroke="#000000" points="1653,-708.5 1653,-1306.5 "/>
<text text-anchor="middle" x="1663.5" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1674,-708.5 1674,-1306.5 "/>
<text text-anchor="middle" x="1797.5" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">aa_change</text>
<polyline fill="none" stroke="#000000" points="1674,-1283.5 1921,-1283.5 "/>
<text text-anchor="middle" x="1797.5" y="-1268.3" font-family="Times,serif" font-size="14.00" fill="#000000">antigen</text>
<polyline fill="none" stroke="#000000" points="1674,-1260.5 1921,-1260.5 "/>
<text text-anchor="middle" x="1797.5" y="-1245.3" font-family="Times,serif" font-size="14.00" fill="#000000">biospecimen_type</text>
<polyline fill="none" stroke="#000000" points="1674,-1237.5 1921,-1237.5 "/>
<text text-anchor="middle" x="1797.5" y="-1222.3" font-family="Times,serif" font-size="14.00" fill="#000000">blood_test_normal_range_lower</text>
<polyline fill="none" stroke="#000000" points="1674,-1214.5 1921,-1214.5 "/>
<text text-anchor="middle" x="1797.5" y="-1199.3" font-family="Times,serif" font-size="14.00" fill="#000000">blood_test_normal_range_upper</text>
<polyline fill="none" stroke="#000000" points="1674,-1191.5 1921,-1191.5 "/>
<text text-anchor="middle" x="1797.5" y="-1176.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_count</text>
<polyline fill="none" stroke="#000000" points="1674,-1168.5 1921,-1168.5 "/>
<text text-anchor="middle" x="1797.5" y="-1153.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome</text>
<polyline fill="none" stroke="#000000" points="1674,-1145.5 1921,-1145.5 "/>
<text text-anchor="middle" x="1797.5" y="-1130.3" font-family="Times,serif" font-size="14.00" fill="#000000">copy_number</text>
<polyline fill="none" stroke="#000000" points="1674,-1122.5 1921,-1122.5 "/>
<text text-anchor="middle" x="1797.5" y="-1107.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytoband</text>
<polyline fill="none" stroke="#000000" points="1674,-1099.5 1921,-1099.5 "/>
<text text-anchor="middle" x="1797.5" y="-1084.3" font-family="Times,serif" font-size="14.00" fill="#000000">exon</text>
<polyline fill="none" stroke="#000000" points="1674,-1076.5 1921,-1076.5 "/>
<text text-anchor="middle" x="1797.5" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">gene_symbol</text>
<polyline fill="none" stroke="#000000" points="1674,-1053.5 1921,-1053.5 "/>
<text text-anchor="middle" x="1797.5" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">histone_family</text>
<polyline fill="none" stroke="#000000" points="1674,-1030.5 1921,-1030.5 "/>
<text text-anchor="middle" x="1797.5" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">histone_variant</text>
<polyline fill="none" stroke="#000000" points="1674,-1007.5 1921,-1007.5 "/>
<text text-anchor="middle" x="1797.5" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">intron</text>
<polyline fill="none" stroke="#000000" points="1674,-984.5 1921,-984.5 "/>
<text text-anchor="middle" x="1797.5" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
<polyline fill="none" stroke="#000000" points="1674,-961.5 1921,-961.5 "/>
<text text-anchor="middle" x="1797.5" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">loci_abnormal_count</text>
<polyline fill="none" stroke="#000000" points="1674,-938.5 1921,-938.5 "/>
<text text-anchor="middle" x="1797.5" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">loci_count</text>
<polyline fill="none" stroke="#000000" points="1674,-915.5 1921,-915.5 "/>
<text text-anchor="middle" x="1797.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">locus</text>
<polyline fill="none" stroke="#000000" points="1674,-892.5 1921,-892.5 "/>
<text text-anchor="middle" x="1797.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">mismatch_repair_mutation</text>
<polyline fill="none" stroke="#000000" points="1674,-869.5 1921,-869.5 "/>
<text text-anchor="middle" x="1797.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_analysis_method</text>
<polyline fill="none" stroke="#000000" points="1674,-846.5 1921,-846.5 "/>
<text text-anchor="middle" x="1797.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_consequence</text>
<polyline fill="none" stroke="#000000" points="1674,-823.5 1921,-823.5 "/>
<text text-anchor="middle" x="1797.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test_id</text>
<polyline fill="none" stroke="#000000" points="1674,-800.5 1921,-800.5 "/>
<text text-anchor="middle" x="1797.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathogenicity</text>
<polyline fill="none" stroke="#000000" points="1674,-777.5 1921,-777.5 "/>
<text text-anchor="middle" x="1797.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">ploidy</text>
<polyline fill="none" stroke="#000000" points="1674,-754.5 1921,-754.5 "/>
<text text-anchor="middle" x="1797.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">second_exon</text>
<polyline fill="none" stroke="#000000" points="1674,-731.5 1921,-731.5 "/>
<text text-anchor="middle" x="1797.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 11 properties</text>
<polyline fill="none" stroke="#000000" points="1921,-708.5 1921,-1306.5 "/>
<text text-anchor="middle" x="1931.5" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1728.6798,-708.4705C1728.3168,-693.6429 1727.9748,-679.6715 1727.6644,-666.9889"/>
<polygon fill="#000000" stroke="#000000" points="1731.155,-666.5595 1727.4112,-656.6482 1724.1571,-666.7309 1731.155,-666.5595"/>
<text text-anchor="middle" x="1792" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- imaging_file -->
<g id="node18" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M4000,-1496.5C4000,-1496.5 4334,-1496.5 4334,-1496.5 4340,-1496.5 4346,-1502.5 4346,-1508.5 4346,-1508.5 4346,-1806.5 4346,-1806.5 4346,-1812.5 4340,-1818.5 4334,-1818.5 4334,-1818.5 4000,-1818.5 4000,-1818.5 3994,-1818.5 3988,-1812.5 3988,-1806.5 3988,-1806.5 3988,-1508.5 3988,-1508.5 3988,-1502.5 3994,-1496.5 4000,-1496.5"/>
<text text-anchor="middle" x="4040" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="4092,-1496.5 4092,-1818.5 "/>
<text text-anchor="middle" x="4102.5" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4113,-1496.5 4113,-1818.5 "/>
<text text-anchor="middle" x="4219" y="-1803.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="4113,-1795.5 4325,-1795.5 "/>
<text text-anchor="middle" x="4219" y="-1780.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="4113,-1772.5 4325,-1772.5 "/>
<text text-anchor="middle" x="4219" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="4113,-1749.5 4325,-1749.5 "/>
<text text-anchor="middle" x="4219" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="4113,-1726.5 4325,-1726.5 "/>
<text text-anchor="middle" x="4219" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="4113,-1703.5 4325,-1703.5 "/>
<text text-anchor="middle" x="4219" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="4113,-1680.5 4325,-1680.5 "/>
<text text-anchor="middle" x="4219" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="4113,-1657.5 4325,-1657.5 "/>
<text text-anchor="middle" x="4219" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="4113,-1634.5 4325,-1634.5 "/>
<text text-anchor="middle" x="4219" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="4113,-1611.5 4325,-1611.5 "/>
<text text-anchor="middle" x="4219" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="4113,-1588.5 4325,-1588.5 "/>
<text text-anchor="middle" x="4219" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="4113,-1565.5 4325,-1565.5 "/>
<text text-anchor="middle" x="4219" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="4113,-1542.5 4325,-1542.5 "/>
<text text-anchor="middle" x="4219" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="4113,-1519.5 4325,-1519.5 "/>
<text text-anchor="middle" x="4219" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="4325,-1496.5 4325,-1818.5 "/>
<text text-anchor="middle" x="4335.5" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M4091.5421,-1496.3117C4062.0814,-1446.7147 4024.3543,-1395.3948 3979,-1358 3763.4922,-1180.3129 3447.681,-1085.8975 3251.2444,-1041.3383"/>
<polygon fill="#000000" stroke="#000000" points="3251.9232,-1037.9036 3241.3989,-1039.1241 3250.3872,-1044.733 3251.9232,-1037.9036"/>
<text text-anchor="middle" x="3991.5" y="-1328.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- follow_up -->
<g id="node19" class="node">
<title>follow_up</title>
<path fill="none" stroke="#000000" d="M2093.5,-904C2093.5,-904 2456.5,-904 2456.5,-904 2462.5,-904 2468.5,-910 2468.5,-916 2468.5,-916 2468.5,-1099 2468.5,-1099 2468.5,-1105 2462.5,-1111 2456.5,-1111 2456.5,-1111 2093.5,-1111 2093.5,-1111 2087.5,-1111 2081.5,-1105 2081.5,-1099 2081.5,-1099 2081.5,-916 2081.5,-916 2081.5,-910 2087.5,-904 2093.5,-904"/>
<text text-anchor="middle" x="2124" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
<polyline fill="none" stroke="#000000" points="2166.5,-904 2166.5,-1111 "/>
<text text-anchor="middle" x="2177" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2187.5,-904 2187.5,-1111 "/>
<text text-anchor="middle" x="2317.5" y="-1095.8" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event</text>
<polyline fill="none" stroke="#000000" points="2187.5,-1088 2447.5,-1088 "/>
<text text-anchor="middle" x="2317.5" y="-1072.8" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity</text>
<polyline fill="none" stroke="#000000" points="2187.5,-1065 2447.5,-1065 "/>
<text text-anchor="middle" x="2317.5" y="-1049.8" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity_method_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2187.5,-1042 2447.5,-1042 "/>
<text text-anchor="middle" x="2317.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_follow_up</text>
<polyline fill="none" stroke="#000000" points="2187.5,-1019 2447.5,-1019 "/>
<text text-anchor="middle" x="2317.5" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_response</text>
<polyline fill="none" stroke="#000000" points="2187.5,-996 2447.5,-996 "/>
<text text-anchor="middle" x="2317.5" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_category</text>
<polyline fill="none" stroke="#000000" points="2187.5,-973 2447.5,-973 "/>
<text text-anchor="middle" x="2317.5" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_id</text>
<polyline fill="none" stroke="#000000" points="2187.5,-950 2447.5,-950 "/>
<text text-anchor="middle" x="2317.5" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_other</text>
<polyline fill="none" stroke="#000000" points="2187.5,-927 2447.5,-927 "/>
<text text-anchor="middle" x="2317.5" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">risk_factor</text>
<polyline fill="none" stroke="#000000" points="2447.5,-904 2447.5,-1111 "/>
<text text-anchor="middle" x="2458" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2222.3001,-903.9551C2185.7875,-840.5824 2132.1047,-761.6394 2067,-708 2019.6141,-668.959 1958.0228,-643.8178 1900.2451,-627.6625"/>
<polygon fill="#000000" stroke="#000000" points="1900.8273,-624.1938 1890.2594,-624.9479 1898.991,-630.9487 1900.8273,-624.1938"/>
<text text-anchor="middle" x="2080" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- diagnosis -->
<g id="node20" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M2499,-812C2499,-812 2873,-812 2873,-812 2879,-812 2885,-818 2885,-824 2885,-824 2885,-1191 2885,-1191 2885,-1197 2879,-1203 2873,-1203 2873,-1203 2499,-1203 2499,-1203 2493,-1203 2487,-1197 2487,-1191 2487,-1191 2487,-824 2487,-824 2487,-818 2493,-812 2499,-812"/>
<text text-anchor="middle" x="2529" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="2571,-812 2571,-1203 "/>
<text text-anchor="middle" x="2581.5" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2592,-812 2592,-1203 "/>
<text text-anchor="middle" x="2728" y="-1187.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2592,-1180 2864,-1180 "/>
<text text-anchor="middle" x="2728" y="-1164.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="2592,-1157 2864,-1157 "/>
<text text-anchor="middle" x="2728" y="-1141.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="2592,-1134 2864,-1134 "/>
<text text-anchor="middle" x="2728" y="-1118.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2592,-1111 2864,-1111 "/>
<text text-anchor="middle" x="2728" y="-1095.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="2592,-1088 2864,-1088 "/>
<text text-anchor="middle" x="2728" y="-1072.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="2592,-1065 2864,-1065 "/>
<text text-anchor="middle" x="2728" y="-1049.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="2592,-1042 2864,-1042 "/>
<text text-anchor="middle" x="2728" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="2592,-1019 2864,-1019 "/>
<text text-anchor="middle" x="2728" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="2592,-996 2864,-996 "/>
<text text-anchor="middle" x="2728" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="2592,-973 2864,-973 "/>
<text text-anchor="middle" x="2728" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2592,-950 2864,-950 "/>
<text text-anchor="middle" x="2728" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="2592,-927 2864,-927 "/>
<text text-anchor="middle" x="2728" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="2592,-904 2864,-904 "/>
<text text-anchor="middle" x="2728" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="2592,-881 2864,-881 "/>
<text text-anchor="middle" x="2728" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="2592,-858 2864,-858 "/>
<text text-anchor="middle" x="2728" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="2592,-835 2864,-835 "/>
<text text-anchor="middle" x="2728" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="2864,-812 2864,-1203 "/>
<text text-anchor="middle" x="2874.5" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2584.7904,-811.7513C2555.4821,-771.678 2519.862,-733.8887 2478,-708 2384.1015,-649.9304 2091.5162,-621.1993 1900.1991,-608.2663"/>
<polygon fill="#000000" stroke="#000000" points="1900.2396,-604.7613 1890.0286,-607.5872 1899.7732,-611.7457 1900.2396,-604.7613"/>
<text text-anchor="middle" x="2479.5" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge8" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1561.9717,-593.7197C1282.5811,-583.0212 738.7915,-554.1331 681,-490 632.8015,-436.5126 645.6951,-390.75 681,-328 703.607,-287.819 738.5606,-255.1718 777.0181,-229.0214"/>
<polygon fill="#000000" stroke="#000000" points="779.3994,-231.642 785.8,-223.1991 775.5313,-225.8078 779.3994,-231.642"/>
<text text-anchor="middle" x="731.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge7" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1724.789,-541.4781C1724.1963,-513.3226 1723.4934,-479.9365 1722.9416,-453.7239"/>
<polygon fill="#000000" stroke="#000000" points="1726.4402,-453.6176 1722.7304,-443.6935 1719.4417,-453.765 1726.4402,-453.6176"/>
<text text-anchor="middle" x="1774.5" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
</g>
</svg>
</div>
