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
<a href="./model-desc/ctdc-model.svg">SVG file (in view above)</a>
<p>
<a href="./model-desc">Additional model files</a>
<div id='graph' style='display:off;'>
<svg width="2277pt" height="1327pt"
 viewBox="0.00 0.00 2276.50 1327.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1323)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1323 2272.5,-1323 2272.5,4 -4,4"/>
<!-- study -->
<g id="node1" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M1524.5,-.5C1524.5,-.5 1749.5,-.5 1749.5,-.5 1755.5,-.5 1761.5,-6.5 1761.5,-12.5 1761.5,-12.5 1761.5,-126.5 1761.5,-126.5 1761.5,-132.5 1755.5,-138.5 1749.5,-138.5 1749.5,-138.5 1524.5,-138.5 1524.5,-138.5 1518.5,-138.5 1512.5,-132.5 1512.5,-126.5 1512.5,-126.5 1512.5,-12.5 1512.5,-12.5 1512.5,-6.5 1518.5,-.5 1524.5,-.5"/>
<text text-anchor="middle" x="1540.5" y="-65.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="1568.5,-.5 1568.5,-138.5 "/>
<text text-anchor="middle" x="1579" y="-65.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1589.5,-.5 1589.5,-138.5 "/>
<text text-anchor="middle" x="1665" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">index_date</text>
<polyline fill="none" stroke="#000000" points="1589.5,-115.5 1740.5,-115.5 "/>
<text text-anchor="middle" x="1665" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="1589.5,-92.5 1740.5,-92.5 "/>
<text text-anchor="middle" x="1665" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="1589.5,-69.5 1740.5,-69.5 "/>
<text text-anchor="middle" x="1665" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="1589.5,-46.5 1740.5,-46.5 "/>
<text text-anchor="middle" x="1665" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_external_url</text>
<polyline fill="none" stroke="#000000" points="1589.5,-23.5 1740.5,-23.5 "/>
<text text-anchor="middle" x="1665" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_title</text>
<polyline fill="none" stroke="#000000" points="1740.5,-.5 1740.5,-138.5 "/>
<text text-anchor="middle" x="1751" y="-65.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- experiment -->
<g id="node2" class="node">
<title>experiment</title>
<path fill="none" stroke="#000000" d="M471,-507C471,-507 739,-507 739,-507 745,-507 751,-513 751,-519 751,-519 751,-541 751,-541 751,-547 745,-553 739,-553 739,-553 471,-553 471,-553 465,-553 459,-547 459,-541 459,-541 459,-519 459,-519 459,-513 465,-507 471,-507"/>
<text text-anchor="middle" x="508" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">experiment</text>
<polyline fill="none" stroke="#000000" points="557,-507 557,-553 "/>
<text text-anchor="middle" x="567.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="578,-507 578,-553 "/>
<text text-anchor="middle" x="654" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="578,-530 730,-530 "/>
<text text-anchor="middle" x="654" y="-514.8" font-family="Times,serif" font-size="14.00" fill="#000000">protocol</text>
<polyline fill="none" stroke="#000000" points="730,-507 730,-553 "/>
<text text-anchor="middle" x="740.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure -->
<g id="node3" class="node">
<title>clinical_measure</title>
<path fill="none" stroke="#000000" d="M205.5,-731.5C205.5,-731.5 586.5,-731.5 586.5,-731.5 592.5,-731.5 598.5,-737.5 598.5,-743.5 598.5,-743.5 598.5,-811.5 598.5,-811.5 598.5,-817.5 592.5,-823.5 586.5,-823.5 586.5,-823.5 205.5,-823.5 205.5,-823.5 199.5,-823.5 193.5,-817.5 193.5,-811.5 193.5,-811.5 193.5,-743.5 193.5,-743.5 193.5,-737.5 199.5,-731.5 205.5,-731.5"/>
<text text-anchor="middle" x="262" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure</text>
<polyline fill="none" stroke="#000000" points="330.5,-731.5 330.5,-823.5 "/>
<text text-anchor="middle" x="341" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="351.5,-731.5 351.5,-823.5 "/>
<text text-anchor="middle" x="464.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_measure</text>
<polyline fill="none" stroke="#000000" points="351.5,-800.5 577.5,-800.5 "/>
<text text-anchor="middle" x="464.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_ID</text>
<polyline fill="none" stroke="#000000" points="351.5,-777.5 577.5,-777.5 "/>
<text text-anchor="middle" x="464.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_description</text>
<polyline fill="none" stroke="#000000" points="351.5,-754.5 577.5,-754.5 "/>
<text text-anchor="middle" x="464.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_measure</text>
<polyline fill="none" stroke="#000000" points="577.5,-731.5 577.5,-823.5 "/>
<text text-anchor="middle" x="588" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_subject -->
<g id="node4" class="node">
<title>study_subject</title>
<path fill="none" stroke="#000000" d="M1051.5,-190.5C1051.5,-190.5 1334.5,-190.5 1334.5,-190.5 1340.5,-190.5 1346.5,-196.5 1346.5,-202.5 1346.5,-202.5 1346.5,-339.5 1346.5,-339.5 1346.5,-345.5 1340.5,-351.5 1334.5,-351.5 1334.5,-351.5 1051.5,-351.5 1051.5,-351.5 1045.5,-351.5 1039.5,-345.5 1039.5,-339.5 1039.5,-339.5 1039.5,-202.5 1039.5,-202.5 1039.5,-196.5 1045.5,-190.5 1051.5,-190.5"/>
<text text-anchor="middle" x="1097.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_subject</text>
<polyline fill="none" stroke="#000000" points="1155.5,-190.5 1155.5,-351.5 "/>
<text text-anchor="middle" x="1166" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1176.5,-190.5 1176.5,-351.5 "/>
<text text-anchor="middle" x="1251" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_enrollment</text>
<polyline fill="none" stroke="#000000" points="1176.5,-328.5 1325.5,-328.5 "/>
<text text-anchor="middle" x="1251" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_unit</text>
<polyline fill="none" stroke="#000000" points="1176.5,-305.5 1325.5,-305.5 "/>
<text text-anchor="middle" x="1251" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="1176.5,-282.5 1325.5,-282.5 "/>
<text text-anchor="middle" x="1251" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="1176.5,-259.5 1325.5,-259.5 "/>
<text text-anchor="middle" x="1251" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1176.5,-236.5 1325.5,-236.5 "/>
<text text-anchor="middle" x="1251" y="-221.3" font-family="Times,serif" font-size="14.00" fill="#000000">subject_id</text>
<polyline fill="none" stroke="#000000" points="1176.5,-213.5 1325.5,-213.5 "/>
<text text-anchor="middle" x="1251" y="-198.3" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="1325.5,-190.5 1325.5,-351.5 "/>
<text text-anchor="middle" x="1336" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_subject&#45;&gt;study -->
<g id="edge6" class="edge">
<title>study_subject&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1346.7324,-201.2318C1397.6824,-178.1092 1453.9469,-152.5748 1503.2681,-130.1914"/>
<polygon fill="#000000" stroke="#000000" points="1504.7341,-133.3697 1512.3938,-126.0499 1501.8412,-126.9954 1504.7341,-133.3697"/>
<text text-anchor="middle" x="1472.5" y="-160.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- sample -->
<g id="node5" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M815,-708.5C815,-708.5 1093,-708.5 1093,-708.5 1099,-708.5 1105,-714.5 1105,-720.5 1105,-720.5 1105,-834.5 1105,-834.5 1105,-840.5 1099,-846.5 1093,-846.5 1093,-846.5 815,-846.5 815,-846.5 809,-846.5 803,-840.5 803,-834.5 803,-834.5 803,-720.5 803,-720.5 803,-714.5 809,-708.5 815,-708.5"/>
<text text-anchor="middle" x="837" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="871,-708.5 871,-846.5 "/>
<text text-anchor="middle" x="881.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="892,-708.5 892,-846.5 "/>
<text text-anchor="middle" x="988" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="892,-823.5 1084,-823.5 "/>
<text text-anchor="middle" x="988" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_collection_day</text>
<polyline fill="none" stroke="#000000" points="892,-800.5 1084,-800.5 "/>
<text text-anchor="middle" x="988" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_collection_event</text>
<polyline fill="none" stroke="#000000" points="892,-777.5 1084,-777.5 "/>
<text text-anchor="middle" x="988" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="892,-754.5 1084,-754.5 "/>
<text text-anchor="middle" x="988" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="892,-731.5 1084,-731.5 "/>
<text text-anchor="middle" x="988" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="1084,-708.5 1084,-846.5 "/>
<text text-anchor="middle" x="1094.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;experiment -->
<g id="edge2" class="edge">
<title>sample&#45;&gt;experiment</title>
<path fill="none" stroke="#000000" d="M840.0338,-708.4233C806.9522,-687.9951 775.5575,-668.133 760,-657 716.6292,-625.9636 669.6192,-586.5563 638.8812,-559.9332"/>
<polygon fill="#000000" stroke="#000000" points="640.8871,-557.0392 631.0448,-553.1173 636.2932,-562.3209 640.8871,-557.0392"/>
<text text-anchor="middle" x="862.5" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_experiment</text>
</g>
<!-- sample&#45;&gt;study_subject -->
<g id="edge11" class="edge">
<title>sample&#45;&gt;study_subject</title>
<path fill="none" stroke="#000000" d="M1014.0557,-708.2746C1017.4917,-702.3265 1020.541,-696.2049 1023,-690 1070.1722,-570.9678 991.2043,-517.7525 1048,-403 1055.7001,-387.4423 1066.0857,-372.8452 1077.7814,-359.4433"/>
<polygon fill="#000000" stroke="#000000" points="1080.6849,-361.4517 1084.8087,-351.6923 1075.499,-356.75 1080.6849,-361.4517"/>
<text text-anchor="middle" x="1108.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_subject</text>
</g>
<!-- specimen -->
<g id="node13" class="node">
<title>specimen</title>
<path fill="none" stroke="#000000" d="M781.5,-512C781.5,-512 990.5,-512 990.5,-512 996.5,-512 1002.5,-518 1002.5,-524 1002.5,-524 1002.5,-536 1002.5,-536 1002.5,-542 996.5,-548 990.5,-548 990.5,-548 781.5,-548 781.5,-548 775.5,-548 769.5,-542 769.5,-536 769.5,-536 769.5,-524 769.5,-524 769.5,-518 775.5,-512 781.5,-512"/>
<text text-anchor="middle" x="812" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">specimen</text>
<polyline fill="none" stroke="#000000" points="854.5,-512 854.5,-548 "/>
<text text-anchor="middle" x="865" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="875.5,-512 875.5,-548 "/>
<text text-anchor="middle" x="928.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">specimen_id</text>
<polyline fill="none" stroke="#000000" points="981.5,-512 981.5,-548 "/>
<text text-anchor="middle" x="992" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;specimen -->
<g id="edge15" class="edge">
<title>sample&#45;&gt;specimen</title>
<path fill="none" stroke="#000000" d="M934.9678,-708.2283C921.3072,-658.5079 903.6191,-594.1285 893.6726,-557.926"/>
<polygon fill="#000000" stroke="#000000" points="896.989,-556.7854 890.9647,-548.07 890.2391,-558.64 896.989,-556.7854"/>
<text text-anchor="middle" x="974" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_specimen</text>
</g>
<!-- study_funding -->
<g id="node6" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M1676.5,-248C1676.5,-248 1943.5,-248 1943.5,-248 1949.5,-248 1955.5,-254 1955.5,-260 1955.5,-260 1955.5,-282 1955.5,-282 1955.5,-288 1949.5,-294 1943.5,-294 1943.5,-294 1676.5,-294 1676.5,-294 1670.5,-294 1664.5,-288 1664.5,-282 1664.5,-282 1664.5,-260 1664.5,-260 1664.5,-254 1670.5,-248 1676.5,-248"/>
<text text-anchor="middle" x="1724" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="1783.5,-248 1783.5,-294 "/>
<text text-anchor="middle" x="1794" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1804.5,-248 1804.5,-294 "/>
<text text-anchor="middle" x="1869.5" y="-278.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_ID</text>
<polyline fill="none" stroke="#000000" points="1804.5,-271 1934.5,-271 "/>
<text text-anchor="middle" x="1869.5" y="-255.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="1934.5,-248 1934.5,-294 "/>
<text text-anchor="middle" x="1945" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge4" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1790.1547,-247.8854C1768.9427,-223.179 1734.1618,-182.6683 1703.1019,-146.4916"/>
<polygon fill="#000000" stroke="#000000" points="1705.7065,-144.1522 1696.5368,-138.8449 1700.3954,-148.7121 1705.7065,-144.1522"/>
<text text-anchor="middle" x="1754.5" y="-160.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- diagnosis -->
<g id="node7" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1190,-403.5C1190,-403.5 1504,-403.5 1504,-403.5 1510,-403.5 1516,-409.5 1516,-415.5 1516,-415.5 1516,-644.5 1516,-644.5 1516,-650.5 1510,-656.5 1504,-656.5 1504,-656.5 1190,-656.5 1190,-656.5 1184,-656.5 1178,-650.5 1178,-644.5 1178,-644.5 1178,-415.5 1178,-415.5 1178,-409.5 1184,-403.5 1190,-403.5"/>
<text text-anchor="middle" x="1220" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1262,-403.5 1262,-656.5 "/>
<text text-anchor="middle" x="1272.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1283,-403.5 1283,-656.5 "/>
<text text-anchor="middle" x="1389" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1283,-633.5 1495,-633.5 "/>
<text text-anchor="middle" x="1389" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_status</text>
<polyline fill="none" stroke="#000000" points="1283,-610.5 1495,-610.5 "/>
<text text-anchor="middle" x="1389" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1283,-587.5 1495,-587.5 "/>
<text text-anchor="middle" x="1389" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_ID</text>
<polyline fill="none" stroke="#000000" points="1283,-564.5 1495,-564.5 "/>
<text text-anchor="middle" x="1389" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">incidence_type</text>
<polyline fill="none" stroke="#000000" points="1283,-541.5 1495,-541.5 "/>
<text text-anchor="middle" x="1389" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1283,-518.5 1495,-518.5 "/>
<text text-anchor="middle" x="1389" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1283,-495.5 1495,-495.5 "/>
<text text-anchor="middle" x="1389" y="-480.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="1283,-472.5 1495,-472.5 "/>
<text text-anchor="middle" x="1389" y="-457.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1283,-449.5 1495,-449.5 "/>
<text text-anchor="middle" x="1389" y="-434.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="1283,-426.5 1495,-426.5 "/>
<text text-anchor="middle" x="1389" y="-411.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage</text>
<polyline fill="none" stroke="#000000" points="1495,-403.5 1495,-656.5 "/>
<text text-anchor="middle" x="1505.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;study_subject -->
<g id="edge12" class="edge">
<title>diagnosis&#45;&gt;study_subject</title>
<path fill="none" stroke="#000000" d="M1271.579,-403.1556C1263.0144,-388.7515 1254.4238,-374.3036 1246.2311,-360.5251"/>
<polygon fill="#000000" stroke="#000000" points="1249.0283,-358.381 1240.9091,-351.5745 1243.0116,-361.9586 1249.0283,-358.381"/>
<text text-anchor="middle" x="1321.5" y="-373.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_subject</text>
</g>
<!-- study_admin -->
<g id="node8" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M1985.5,-213.5C1985.5,-213.5 2256.5,-213.5 2256.5,-213.5 2262.5,-213.5 2268.5,-219.5 2268.5,-225.5 2268.5,-225.5 2268.5,-316.5 2268.5,-316.5 2268.5,-322.5 2262.5,-328.5 2256.5,-328.5 2256.5,-328.5 1985.5,-328.5 1985.5,-328.5 1979.5,-328.5 1973.5,-322.5 1973.5,-316.5 1973.5,-316.5 1973.5,-225.5 1973.5,-225.5 1973.5,-219.5 1979.5,-213.5 1985.5,-213.5"/>
<text text-anchor="middle" x="2027.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="2081.5,-213.5 2081.5,-328.5 "/>
<text text-anchor="middle" x="2092" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2102.5,-213.5 2102.5,-328.5 "/>
<text text-anchor="middle" x="2175" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_access_level</text>
<polyline fill="none" stroke="#000000" points="2102.5,-305.5 2247.5,-305.5 "/>
<text text-anchor="middle" x="2175" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="2102.5,-282.5 2247.5,-282.5 "/>
<text text-anchor="middle" x="2175" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types</text>
<polyline fill="none" stroke="#000000" points="2102.5,-259.5 2247.5,-259.5 "/>
<text text-anchor="middle" x="2175" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">species</text>
<polyline fill="none" stroke="#000000" points="2102.5,-236.5 2247.5,-236.5 "/>
<text text-anchor="middle" x="2175" y="-221.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_type</text>
<polyline fill="none" stroke="#000000" points="2247.5,-213.5 2247.5,-328.5 "/>
<text text-anchor="middle" x="2258" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge7" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2013.7437,-213.4517C1997.244,-205.2445 1980.2813,-197.1672 1964,-190 1901.7131,-162.5807 1831.0318,-135.993 1771.3579,-114.7997"/>
<polygon fill="#000000" stroke="#000000" points="1772.4728,-111.4817 1761.8781,-111.4454 1770.1378,-118.0807 1772.4728,-111.4817"/>
<text text-anchor="middle" x="1950.5" y="-160.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- file -->
<g id="node9" class="node">
<title>file</title>
<path fill="none" stroke="#000000" d="M422.5,-898.5C422.5,-898.5 607.5,-898.5 607.5,-898.5 613.5,-898.5 619.5,-904.5 619.5,-910.5 619.5,-910.5 619.5,-1047.5 619.5,-1047.5 619.5,-1053.5 613.5,-1059.5 607.5,-1059.5 607.5,-1059.5 422.5,-1059.5 422.5,-1059.5 416.5,-1059.5 410.5,-1053.5 410.5,-1047.5 410.5,-1047.5 410.5,-910.5 410.5,-910.5 410.5,-904.5 416.5,-898.5 422.5,-898.5"/>
<text text-anchor="middle" x="430" y="-975.3" font-family="Times,serif" font-size="14.00" fill="#000000">file</text>
<polyline fill="none" stroke="#000000" points="449.5,-898.5 449.5,-1059.5 "/>
<text text-anchor="middle" x="460" y="-975.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="470.5,-898.5 470.5,-1059.5 "/>
<text text-anchor="middle" x="534.5" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_url</text>
<polyline fill="none" stroke="#000000" points="470.5,-1036.5 598.5,-1036.5 "/>
<text text-anchor="middle" x="534.5" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="470.5,-1013.5 598.5,-1013.5 "/>
<text text-anchor="middle" x="534.5" y="-998.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_id</text>
<polyline fill="none" stroke="#000000" points="470.5,-990.5 598.5,-990.5 "/>
<text text-anchor="middle" x="534.5" y="-975.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="470.5,-967.5 598.5,-967.5 "/>
<text text-anchor="middle" x="534.5" y="-952.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="470.5,-944.5 598.5,-944.5 "/>
<text text-anchor="middle" x="534.5" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="470.5,-921.5 598.5,-921.5 "/>
<text text-anchor="middle" x="534.5" y="-906.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="598.5,-898.5 598.5,-1059.5 "/>
<text text-anchor="middle" x="609" y="-975.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file&#45;&gt;study -->
<g id="edge8" class="edge">
<title>file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M410.4063,-953.1345C280.5592,-917.9033 76,-850.773 76,-777.5 76,-777.5 76,-777.5 76,-271 76,-127.779 1122.9322,-83.9978 1502.0246,-72.8393"/>
<polygon fill="#000000" stroke="#000000" points="1502.3299,-76.332 1512.2237,-72.5422 1502.126,-69.335 1502.3299,-76.332"/>
<text text-anchor="middle" x="106.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- file&#45;&gt;experiment -->
<g id="edge1" class="edge">
<title>file&#45;&gt;experiment</title>
<path fill="none" stroke="#000000" d="M591.9226,-898.3101C595.6904,-892.3473 599.1031,-886.2231 602,-880 651.6774,-773.2824 627.8906,-627.6622 613.3754,-563.1212"/>
<polygon fill="#000000" stroke="#000000" points="616.7235,-562.0655 611.0517,-553.1167 609.905,-563.6493 616.7235,-562.0655"/>
<text text-anchor="middle" x="683.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_experiment</text>
</g>
<!-- file&#45;&gt;clinical_measure -->
<g id="edge9" class="edge">
<title>file&#45;&gt;clinical_measure</title>
<path fill="none" stroke="#000000" d="M467.455,-898.4932C454.3718,-876.3396 440.4841,-852.824 428.4655,-832.4731"/>
<polygon fill="#000000" stroke="#000000" points="431.3602,-830.4918 423.2614,-823.661 425.3328,-834.0514 431.3602,-830.4918"/>
<text text-anchor="middle" x="527" y="-868.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure</text>
</g>
<!-- file&#45;&gt;study_subject -->
<g id="edge10" class="edge">
<title>file&#45;&gt;study_subject</title>
<path fill="none" stroke="#000000" d="M410.2662,-967.8789C333.4931,-953.6298 234.2437,-921.1284 184,-847 149.3389,-795.8619 162.3182,-765.848 184,-708 247.1267,-539.5755 293.4381,-491.5447 450,-403 546.6992,-348.3111 841.3502,-308.1518 1029.2442,-287.2721"/>
<polygon fill="#000000" stroke="#000000" points="1029.6703,-290.7464 1039.2257,-286.1698 1028.9019,-283.7887 1029.6703,-290.7464"/>
<text text-anchor="middle" x="256.5" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_subject</text>
</g>
<!-- file&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M617.9527,-898.3186C640.0611,-881.521 658.7107,-867.959 665,-865 696.801,-850.0382 708.1587,-856.4831 742,-847 758.6784,-842.3263 775.9989,-837.1647 793.2283,-831.8283"/>
<polygon fill="#000000" stroke="#000000" points="794.2816,-835.1662 802.7861,-828.8476 792.1976,-828.4836 794.2816,-835.1662"/>
<text text-anchor="middle" x="711.5" y="-868.8" font-family="Times,serif" font-size="14.00" fill="#000000">from_sample</text>
</g>
<!-- therapeutic_procedure -->
<g id="node10" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M1098.5,-1180.5C1098.5,-1180.5 1455.5,-1180.5 1455.5,-1180.5 1461.5,-1180.5 1467.5,-1186.5 1467.5,-1192.5 1467.5,-1192.5 1467.5,-1237.5 1467.5,-1237.5 1467.5,-1243.5 1461.5,-1249.5 1455.5,-1249.5 1455.5,-1249.5 1098.5,-1249.5 1098.5,-1249.5 1092.5,-1249.5 1086.5,-1243.5 1086.5,-1237.5 1086.5,-1237.5 1086.5,-1192.5 1086.5,-1192.5 1086.5,-1186.5 1092.5,-1180.5 1098.5,-1180.5"/>
<text text-anchor="middle" x="1177" y="-1211.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="1267.5,-1180.5 1267.5,-1249.5 "/>
<text text-anchor="middle" x="1278" y="-1211.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1288.5,-1180.5 1288.5,-1249.5 "/>
<text text-anchor="middle" x="1367.5" y="-1234.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="1288.5,-1226.5 1446.5,-1226.5 "/>
<text text-anchor="middle" x="1367.5" y="-1211.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="1288.5,-1203.5 1446.5,-1203.5 "/>
<text text-anchor="middle" x="1367.5" y="-1188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1446.5,-1180.5 1446.5,-1249.5 "/>
<text text-anchor="middle" x="1457" y="-1211.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_detail -->
<g id="node11" class="node">
<title>imaging_detail</title>
<path fill="none" stroke="#000000" d="M446,-1157.5C446,-1157.5 740,-1157.5 740,-1157.5 746,-1157.5 752,-1163.5 752,-1169.5 752,-1169.5 752,-1260.5 752,-1260.5 752,-1266.5 746,-1272.5 740,-1272.5 740,-1272.5 446,-1272.5 446,-1272.5 440,-1272.5 434,-1266.5 434,-1260.5 434,-1260.5 434,-1169.5 434,-1169.5 434,-1163.5 440,-1157.5 446,-1157.5"/>
<text text-anchor="middle" x="495" y="-1211.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_detail</text>
<polyline fill="none" stroke="#000000" points="556,-1157.5 556,-1272.5 "/>
<text text-anchor="middle" x="566.5" y="-1211.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="577,-1157.5 577,-1272.5 "/>
<text text-anchor="middle" x="654" y="-1257.3" font-family="Times,serif" font-size="14.00" fill="#000000">image_id</text>
<polyline fill="none" stroke="#000000" points="577,-1249.5 731,-1249.5 "/>
<text text-anchor="middle" x="654" y="-1234.3" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="577,-1226.5 731,-1226.5 "/>
<text text-anchor="middle" x="654" y="-1211.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="577,-1203.5 731,-1203.5 "/>
<text text-anchor="middle" x="654" y="-1188.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="577,-1180.5 731,-1180.5 "/>
<text text-anchor="middle" x="654" y="-1165.3" font-family="Times,serif" font-size="14.00" fill="#000000">software_packages</text>
<polyline fill="none" stroke="#000000" points="731,-1157.5 731,-1272.5 "/>
<text text-anchor="middle" x="741.5" y="-1211.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_detail&#45;&gt;file -->
<g id="edge16" class="edge">
<title>imaging_detail&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M573.9191,-1157.2679C565.1693,-1130.7942 554.5909,-1098.788 544.8261,-1069.243"/>
<polygon fill="#000000" stroke="#000000" points="548.149,-1068.1436 541.6876,-1059.7471 541.5026,-1070.3404 548.149,-1068.1436"/>
<text text-anchor="middle" x="574" y="-1081.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- genomic_detail -->
<g id="node12" class="node">
<title>genomic_detail</title>
<path fill="none" stroke="#000000" d="M12,-1111.5C12,-1111.5 404,-1111.5 404,-1111.5 410,-1111.5 416,-1117.5 416,-1123.5 416,-1123.5 416,-1306.5 416,-1306.5 416,-1312.5 410,-1318.5 404,-1318.5 404,-1318.5 12,-1318.5 12,-1318.5 6,-1318.5 0,-1312.5 0,-1306.5 0,-1306.5 0,-1123.5 0,-1123.5 0,-1117.5 6,-1111.5 12,-1111.5"/>
<text text-anchor="middle" x="62.5" y="-1211.3" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_detail</text>
<polyline fill="none" stroke="#000000" points="125,-1111.5 125,-1318.5 "/>
<text text-anchor="middle" x="135.5" y="-1211.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="146,-1111.5 146,-1318.5 "/>
<text text-anchor="middle" x="270.5" y="-1303.3" font-family="Times,serif" font-size="14.00" fill="#000000">average_read_length</text>
<polyline fill="none" stroke="#000000" points="146,-1295.5 395,-1295.5 "/>
<text text-anchor="middle" x="270.5" y="-1280.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="146,-1272.5 395,-1272.5 "/>
<text text-anchor="middle" x="270.5" y="-1257.3" font-family="Times,serif" font-size="14.00" fill="#000000">genome_reference_or_accession</text>
<polyline fill="none" stroke="#000000" points="146,-1249.5 395,-1249.5 "/>
<text text-anchor="middle" x="270.5" y="-1234.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="146,-1226.5 395,-1226.5 "/>
<text text-anchor="middle" x="270.5" y="-1211.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="146,-1203.5 395,-1203.5 "/>
<text text-anchor="middle" x="270.5" y="-1188.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="146,-1180.5 395,-1180.5 "/>
<text text-anchor="middle" x="270.5" y="-1165.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="146,-1157.5 395,-1157.5 "/>
<text text-anchor="middle" x="270.5" y="-1142.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="146,-1134.5 395,-1134.5 "/>
<text text-anchor="middle" x="270.5" y="-1119.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="395,-1111.5 395,-1318.5 "/>
<text text-anchor="middle" x="405.5" y="-1211.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genomic_detail&#45;&gt;file -->
<g id="edge18" class="edge">
<title>genomic_detail&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M342.6547,-1111.487C362.6201,-1096.139 383.0173,-1080.459 402.4676,-1065.507"/>
<polygon fill="#000000" stroke="#000000" points="404.6545,-1068.2405 410.4496,-1059.371 400.3883,-1062.6908 404.6545,-1068.2405"/>
<text text-anchor="middle" x="402" y="-1081.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- specimen&#45;&gt;study_subject -->
<g id="edge14" class="edge">
<title>specimen&#45;&gt;study_subject</title>
<path fill="none" stroke="#000000" d="M882.3429,-511.838C876.9421,-479.4907 870.7534,-411.4175 904,-370 921.5751,-348.1055 974.0446,-327.3877 1029.5396,-310.6182"/>
<polygon fill="#000000" stroke="#000000" points="1030.607,-313.9523 1039.1951,-307.7479 1028.6123,-307.2425 1030.607,-313.9523"/>
<text text-anchor="middle" x="964.5" y="-373.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_subject</text>
</g>
<!-- alias -->
<g id="node14" class="node">
<title>alias</title>
<path fill="none" stroke="#000000" d="M851.5,-1169C851.5,-1169 1056.5,-1169 1056.5,-1169 1062.5,-1169 1068.5,-1175 1068.5,-1181 1068.5,-1181 1068.5,-1249 1068.5,-1249 1068.5,-1255 1062.5,-1261 1056.5,-1261 1056.5,-1261 851.5,-1261 851.5,-1261 845.5,-1261 839.5,-1255 839.5,-1249 839.5,-1249 839.5,-1181 839.5,-1181 839.5,-1175 845.5,-1169 851.5,-1169"/>
<text text-anchor="middle" x="864.5" y="-1211.3" font-family="Times,serif" font-size="14.00" fill="#000000">alias</text>
<polyline fill="none" stroke="#000000" points="889.5,-1169 889.5,-1261 "/>
<text text-anchor="middle" x="900" y="-1211.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="910.5,-1169 910.5,-1261 "/>
<text text-anchor="middle" x="979" y="-1245.8" font-family="Times,serif" font-size="14.00" fill="#000000">CDS_ID</text>
<polyline fill="none" stroke="#000000" points="910.5,-1238 1047.5,-1238 "/>
<text text-anchor="middle" x="979" y="-1222.8" font-family="Times,serif" font-size="14.00" fill="#000000">CDS_node</text>
<polyline fill="none" stroke="#000000" points="910.5,-1215 1047.5,-1215 "/>
<text text-anchor="middle" x="979" y="-1199.8" font-family="Times,serif" font-size="14.00" fill="#000000">repository_ID</text>
<polyline fill="none" stroke="#000000" points="910.5,-1192 1047.5,-1192 "/>
<text text-anchor="middle" x="979" y="-1176.8" font-family="Times,serif" font-size="14.00" fill="#000000">repository_name</text>
<polyline fill="none" stroke="#000000" points="1047.5,-1169 1047.5,-1261 "/>
<text text-anchor="middle" x="1058" y="-1211.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- alias&#45;&gt;study -->
<g id="edge5" class="edge">
<title>alias&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M998.131,-1168.804C1020.0597,-1148.317 1048.0303,-1125.5952 1077,-1111 1305.3647,-995.9477 1637,-1234.7097 1637,-979 1637,-979 1637,-979 1637,-271 1637,-230.7098 1637,-185.8881 1637,-148.7671"/>
<polygon fill="#000000" stroke="#000000" points="1640.5001,-148.5114 1637,-138.5114 1633.5001,-148.5114 1640.5001,-148.5114"/>
<text text-anchor="middle" x="1667.5" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- alias&#45;&gt;experiment -->
<g id="edge3" class="edge">
<title>alias&#45;&gt;experiment</title>
<path fill="none" stroke="#000000" d="M933.2958,-1168.738C902.3087,-1099.1996 842.3427,-963.4611 794,-847 768.5289,-785.6384 771.4938,-765.9498 739,-708 707.9127,-652.5585 661.5226,-594.9506 632.2845,-560.8013"/>
<polygon fill="#000000" stroke="#000000" points="634.7825,-558.3387 625.5999,-553.0537 629.4825,-562.9115 634.7825,-558.3387"/>
<text text-anchor="middle" x="858.5" y="-868.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_experiment</text>
</g>
<!-- alias&#45;&gt;study_subject -->
<g id="edge13" class="edge">
<title>alias&#45;&gt;study_subject</title>
<path fill="none" stroke="#000000" d="M1005.691,-1168.7627C1141.0127,-1047.1414 1497.1694,-723.11 1525,-657 1568.8004,-552.9547 1588.3859,-496.4138 1525,-403 1486.7381,-346.6122 1420.1737,-314.3117 1356.6448,-295.8092"/>
<polygon fill="#000000" stroke="#000000" points="1357.4633,-292.4037 1346.8893,-293.0674 1355.5693,-299.1426 1357.4633,-292.4037"/>
<text text-anchor="middle" x="1547.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_subject</text>
</g>
<!-- alias&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>alias&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M954,-1168.594C954,-1094.2993 954,-947.7738 954,-856.6848"/>
<polygon fill="#000000" stroke="#000000" points="957.5001,-856.6812 954,-846.6812 950.5001,-856.6812 957.5001,-856.6812"/>
<text text-anchor="middle" x="1000.5" y="-975.3" font-family="Times,serif" font-size="14.00" fill="#000000">from_sample</text>
</g>
<!-- alias&#45;&gt;file -->
<g id="edge17" class="edge">
<title>alias&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M870.9908,-1168.8161C837.1265,-1150.3566 797.4326,-1129.2018 761,-1111 743.9223,-1102.4679 739.0385,-1101.6101 722,-1093 691.3388,-1077.5059 658.5892,-1059.9513 628.3978,-1043.3416"/>
<polygon fill="#000000" stroke="#000000" points="629.983,-1040.2189 619.5362,-1038.4534 626.6019,-1046.3482 629.983,-1040.2189"/>
<text text-anchor="middle" x="744" y="-1081.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
</g>
</svg>
</div>
