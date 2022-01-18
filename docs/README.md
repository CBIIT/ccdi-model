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
<svg width="1792pt" height="1327pt"
 viewBox="0.00 0.00 1791.50 1327.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1323)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1323 1787.5,-1323 1787.5,4 -4,4"/>
<!-- study_subject -->
<g id="node1" class="node">
<title>study_subject</title>
<path fill="none" stroke="#000000" d="M903.5,-190.5C903.5,-190.5 1186.5,-190.5 1186.5,-190.5 1192.5,-190.5 1198.5,-196.5 1198.5,-202.5 1198.5,-202.5 1198.5,-339.5 1198.5,-339.5 1198.5,-345.5 1192.5,-351.5 1186.5,-351.5 1186.5,-351.5 903.5,-351.5 903.5,-351.5 897.5,-351.5 891.5,-345.5 891.5,-339.5 891.5,-339.5 891.5,-202.5 891.5,-202.5 891.5,-196.5 897.5,-190.5 903.5,-190.5"/>
<text text-anchor="middle" x="949.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_subject</text>
<polyline fill="none" stroke="#000000" points="1007.5,-190.5 1007.5,-351.5 "/>
<text text-anchor="middle" x="1018" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1028.5,-190.5 1028.5,-351.5 "/>
<text text-anchor="middle" x="1103" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_enrollment</text>
<polyline fill="none" stroke="#000000" points="1028.5,-328.5 1177.5,-328.5 "/>
<text text-anchor="middle" x="1103" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_unit</text>
<polyline fill="none" stroke="#000000" points="1028.5,-305.5 1177.5,-305.5 "/>
<text text-anchor="middle" x="1103" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="1028.5,-282.5 1177.5,-282.5 "/>
<text text-anchor="middle" x="1103" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="1028.5,-259.5 1177.5,-259.5 "/>
<text text-anchor="middle" x="1103" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1028.5,-236.5 1177.5,-236.5 "/>
<text text-anchor="middle" x="1103" y="-221.3" font-family="Times,serif" font-size="14.00" fill="#000000">subject_id</text>
<polyline fill="none" stroke="#000000" points="1028.5,-213.5 1177.5,-213.5 "/>
<text text-anchor="middle" x="1103" y="-198.3" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="1177.5,-190.5 1177.5,-351.5 "/>
<text text-anchor="middle" x="1188" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node9" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M932.5,-.5C932.5,-.5 1157.5,-.5 1157.5,-.5 1163.5,-.5 1169.5,-6.5 1169.5,-12.5 1169.5,-12.5 1169.5,-126.5 1169.5,-126.5 1169.5,-132.5 1163.5,-138.5 1157.5,-138.5 1157.5,-138.5 932.5,-138.5 932.5,-138.5 926.5,-138.5 920.5,-132.5 920.5,-126.5 920.5,-126.5 920.5,-12.5 920.5,-12.5 920.5,-6.5 926.5,-.5 932.5,-.5"/>
<text text-anchor="middle" x="948.5" y="-65.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="976.5,-.5 976.5,-138.5 "/>
<text text-anchor="middle" x="987" y="-65.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="997.5,-.5 997.5,-138.5 "/>
<text text-anchor="middle" x="1073" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">index_date</text>
<polyline fill="none" stroke="#000000" points="997.5,-115.5 1148.5,-115.5 "/>
<text text-anchor="middle" x="1073" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="997.5,-92.5 1148.5,-92.5 "/>
<text text-anchor="middle" x="1073" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="997.5,-69.5 1148.5,-69.5 "/>
<text text-anchor="middle" x="1073" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="997.5,-46.5 1148.5,-46.5 "/>
<text text-anchor="middle" x="1073" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_external_url</text>
<polyline fill="none" stroke="#000000" points="997.5,-23.5 1148.5,-23.5 "/>
<text text-anchor="middle" x="1073" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_title</text>
<polyline fill="none" stroke="#000000" points="1148.5,-.5 1148.5,-138.5 "/>
<text text-anchor="middle" x="1159" y="-65.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_subject&#45;&gt;study -->
<g id="edge18" class="edge">
<title>study_subject&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1045,-190.4932C1045,-176.7786 1045,-162.5421 1045,-148.8576"/>
<polygon fill="#000000" stroke="#000000" points="1048.5001,-148.5183 1045,-138.5184 1041.5001,-148.5184 1048.5001,-148.5183"/>
<text text-anchor="middle" x="1075.5" y="-160.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- experiment -->
<g id="node2" class="node">
<title>experiment</title>
<path fill="none" stroke="#000000" d="M478,-507C478,-507 746,-507 746,-507 752,-507 758,-513 758,-519 758,-519 758,-541 758,-541 758,-547 752,-553 746,-553 746,-553 478,-553 478,-553 472,-553 466,-547 466,-541 466,-541 466,-519 466,-519 466,-513 472,-507 478,-507"/>
<text text-anchor="middle" x="515" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">experiment</text>
<polyline fill="none" stroke="#000000" points="564,-507 564,-553 "/>
<text text-anchor="middle" x="574.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="585,-507 585,-553 "/>
<text text-anchor="middle" x="661" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="585,-530 737,-530 "/>
<text text-anchor="middle" x="661" y="-514.8" font-family="Times,serif" font-size="14.00" fill="#000000">protocol</text>
<polyline fill="none" stroke="#000000" points="737,-507 737,-553 "/>
<text text-anchor="middle" x="747.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding -->
<g id="node3" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M594.5,-248C594.5,-248 861.5,-248 861.5,-248 867.5,-248 873.5,-254 873.5,-260 873.5,-260 873.5,-282 873.5,-282 873.5,-288 867.5,-294 861.5,-294 861.5,-294 594.5,-294 594.5,-294 588.5,-294 582.5,-288 582.5,-282 582.5,-282 582.5,-260 582.5,-260 582.5,-254 588.5,-248 594.5,-248"/>
<text text-anchor="middle" x="642" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="701.5,-248 701.5,-294 "/>
<text text-anchor="middle" x="712" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="722.5,-248 722.5,-294 "/>
<text text-anchor="middle" x="787.5" y="-278.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_ID</text>
<polyline fill="none" stroke="#000000" points="722.5,-271 852.5,-271 "/>
<text text-anchor="middle" x="787.5" y="-255.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="852.5,-248 852.5,-294 "/>
<text text-anchor="middle" x="863" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge15" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M764.3639,-247.8854C804.1227,-222.6128 869.8974,-180.8034 927.7781,-144.0117"/>
<polygon fill="#000000" stroke="#000000" points="929.6948,-146.9407 936.2566,-138.6224 925.9396,-141.0331 929.6948,-146.9407"/>
<text text-anchor="middle" x="936.5" y="-160.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- alias -->
<g id="node4" class="node">
<title>alias</title>
<path fill="none" stroke="#000000" d="M907.5,-1169C907.5,-1169 1112.5,-1169 1112.5,-1169 1118.5,-1169 1124.5,-1175 1124.5,-1181 1124.5,-1181 1124.5,-1249 1124.5,-1249 1124.5,-1255 1118.5,-1261 1112.5,-1261 1112.5,-1261 907.5,-1261 907.5,-1261 901.5,-1261 895.5,-1255 895.5,-1249 895.5,-1249 895.5,-1181 895.5,-1181 895.5,-1175 901.5,-1169 907.5,-1169"/>
<text text-anchor="middle" x="920.5" y="-1211.3" font-family="Times,serif" font-size="14.00" fill="#000000">alias</text>
<polyline fill="none" stroke="#000000" points="945.5,-1169 945.5,-1261 "/>
<text text-anchor="middle" x="956" y="-1211.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="966.5,-1169 966.5,-1261 "/>
<text text-anchor="middle" x="1035" y="-1245.8" font-family="Times,serif" font-size="14.00" fill="#000000">CDS_ID</text>
<polyline fill="none" stroke="#000000" points="966.5,-1238 1103.5,-1238 "/>
<text text-anchor="middle" x="1035" y="-1222.8" font-family="Times,serif" font-size="14.00" fill="#000000">CDS_node</text>
<polyline fill="none" stroke="#000000" points="966.5,-1215 1103.5,-1215 "/>
<text text-anchor="middle" x="1035" y="-1199.8" font-family="Times,serif" font-size="14.00" fill="#000000">repository_ID</text>
<polyline fill="none" stroke="#000000" points="966.5,-1192 1103.5,-1192 "/>
<text text-anchor="middle" x="1035" y="-1176.8" font-family="Times,serif" font-size="14.00" fill="#000000">repository_name</text>
<polyline fill="none" stroke="#000000" points="1103.5,-1169 1103.5,-1261 "/>
<text text-anchor="middle" x="1114" y="-1211.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- alias&#45;&gt;study_subject -->
<g id="edge8" class="edge">
<title>alias&#45;&gt;study_subject</title>
<path fill="none" stroke="#000000" d="M1034.2509,-1168.723C1083.3577,-1076.8247 1200.5163,-866.5163 1325,-708 1344.6051,-683.0351 1362.9979,-686.3863 1375,-657 1417.6839,-552.4917 1438.2888,-496.4796 1375,-403 1337.1599,-347.1089 1271.408,-314.8811 1208.5055,-296.2988"/>
<polygon fill="#000000" stroke="#000000" points="1209.4214,-292.9205 1198.8449,-293.5436 1207.5015,-299.6521 1209.4214,-292.9205"/>
<text text-anchor="middle" x="1385.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_subject</text>
</g>
<!-- alias&#45;&gt;experiment -->
<g id="edge7" class="edge">
<title>alias&#45;&gt;experiment</title>
<path fill="none" stroke="#000000" d="M1020.1766,-1168.9421C1038.2326,-1076.0913 1067.2316,-862.1633 991,-708 945.7422,-616.4751 861.3595,-696.0048 767,-657 715.1322,-635.5597 667.0811,-590.7059 638.6349,-560.4631"/>
<polygon fill="#000000" stroke="#000000" points="641.1948,-558.0762 631.8348,-553.1122 636.0562,-562.8297 641.1948,-558.0762"/>
<text text-anchor="middle" x="1088.5" y="-868.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_experiment</text>
</g>
<!-- file -->
<g id="node5" class="node">
<title>file</title>
<path fill="none" stroke="#000000" d="M347.5,-898.5C347.5,-898.5 532.5,-898.5 532.5,-898.5 538.5,-898.5 544.5,-904.5 544.5,-910.5 544.5,-910.5 544.5,-1047.5 544.5,-1047.5 544.5,-1053.5 538.5,-1059.5 532.5,-1059.5 532.5,-1059.5 347.5,-1059.5 347.5,-1059.5 341.5,-1059.5 335.5,-1053.5 335.5,-1047.5 335.5,-1047.5 335.5,-910.5 335.5,-910.5 335.5,-904.5 341.5,-898.5 347.5,-898.5"/>
<text text-anchor="middle" x="355" y="-975.3" font-family="Times,serif" font-size="14.00" fill="#000000">file</text>
<polyline fill="none" stroke="#000000" points="374.5,-898.5 374.5,-1059.5 "/>
<text text-anchor="middle" x="385" y="-975.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="395.5,-898.5 395.5,-1059.5 "/>
<text text-anchor="middle" x="459.5" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_url</text>
<polyline fill="none" stroke="#000000" points="395.5,-1036.5 523.5,-1036.5 "/>
<text text-anchor="middle" x="459.5" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="395.5,-1013.5 523.5,-1013.5 "/>
<text text-anchor="middle" x="459.5" y="-998.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_id</text>
<polyline fill="none" stroke="#000000" points="395.5,-990.5 523.5,-990.5 "/>
<text text-anchor="middle" x="459.5" y="-975.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="395.5,-967.5 523.5,-967.5 "/>
<text text-anchor="middle" x="459.5" y="-952.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="395.5,-944.5 523.5,-944.5 "/>
<text text-anchor="middle" x="459.5" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="395.5,-921.5 523.5,-921.5 "/>
<text text-anchor="middle" x="459.5" y="-906.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="523.5,-898.5 523.5,-1059.5 "/>
<text text-anchor="middle" x="534" y="-975.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- alias&#45;&gt;file -->
<g id="edge2" class="edge">
<title>alias&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M925.729,-1168.7609C889.6676,-1149.7804 846.7782,-1128.2585 807,-1111 723.922,-1074.955 627.4798,-1040.5441 554.3133,-1015.8981"/>
<polygon fill="#000000" stroke="#000000" points="555.1962,-1012.5026 544.6023,-1012.6382 552.9685,-1019.1387 555.1962,-1012.5026"/>
<text text-anchor="middle" x="781" y="-1081.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- alias&#45;&gt;study -->
<g id="edge14" class="edge">
<title>alias&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1057.6705,-1168.9537C1079.6827,-1149.3438 1106.9099,-1127.2871 1134,-1111 1267.9673,-1030.4561 1460,-1135.3156 1460,-979 1460,-979 1460,-979 1460,-271 1460,-207.4458 1300.5099,-145.2508 1179.2751,-107.1545"/>
<polygon fill="#000000" stroke="#000000" points="1180.1022,-103.7463 1169.5137,-104.1129 1178.0197,-110.4293 1180.1022,-103.7463"/>
<text text-anchor="middle" x="1490.5" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- sample -->
<g id="node12" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M692,-708.5C692,-708.5 970,-708.5 970,-708.5 976,-708.5 982,-714.5 982,-720.5 982,-720.5 982,-834.5 982,-834.5 982,-840.5 976,-846.5 970,-846.5 970,-846.5 692,-846.5 692,-846.5 686,-846.5 680,-840.5 680,-834.5 680,-834.5 680,-720.5 680,-720.5 680,-714.5 686,-708.5 692,-708.5"/>
<text text-anchor="middle" x="714" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="748,-708.5 748,-846.5 "/>
<text text-anchor="middle" x="758.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="769,-708.5 769,-846.5 "/>
<text text-anchor="middle" x="865" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="769,-823.5 961,-823.5 "/>
<text text-anchor="middle" x="865" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_collection_day</text>
<polyline fill="none" stroke="#000000" points="769,-800.5 961,-800.5 "/>
<text text-anchor="middle" x="865" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_collection_event</text>
<polyline fill="none" stroke="#000000" points="769,-777.5 961,-777.5 "/>
<text text-anchor="middle" x="865" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="769,-754.5 961,-754.5 "/>
<text text-anchor="middle" x="865" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="769,-731.5 961,-731.5 "/>
<text text-anchor="middle" x="865" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="961,-708.5 961,-846.5 "/>
<text text-anchor="middle" x="971.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- alias&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>alias&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M971.5854,-1168.7856C948.7601,-1139.2711 920.8706,-1099.2892 903,-1060 873.1869,-994.4548 854.2735,-914.5125 843.3527,-856.4186"/>
<polygon fill="#000000" stroke="#000000" points="846.7909,-855.7629 841.537,-846.5625 839.9067,-857.0312 846.7909,-855.7629"/>
<text text-anchor="middle" x="949.5" y="-975.3" font-family="Times,serif" font-size="14.00" fill="#000000">from_sample</text>
</g>
<!-- file&#45;&gt;study_subject -->
<g id="edge11" class="edge">
<title>file&#45;&gt;study_subject</title>
<path fill="none" stroke="#000000" d="M335.3586,-968.047C258.3042,-953.8872 158.5003,-921.4239 108,-847 3.7933,-693.4273 268.7581,-409.4715 276,-403 304.6792,-377.3717 318.4051,-378.1201 356,-370 467.3068,-345.959 753.01,-378.8516 881.1556,-351.8227"/>
<polygon fill="#000000" stroke="#000000" points="882.2614,-355.1593 891.2134,-349.4926 880.6815,-348.34 882.2614,-355.1593"/>
<text text-anchor="middle" x="160.5" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_subject</text>
</g>
<!-- file&#45;&gt;experiment -->
<g id="edge5" class="edge">
<title>file&#45;&gt;experiment</title>
<path fill="none" stroke="#000000" d="M515.2024,-898.2375C519.1588,-892.2709 522.8097,-886.1676 526,-880 562.154,-810.1066 549.225,-784.4179 568,-708 580.4429,-657.3549 594.9798,-598.6326 603.8348,-562.9124"/>
<polygon fill="#000000" stroke="#000000" points="607.2739,-563.585 606.2834,-553.0366 600.4796,-561.9003 607.2739,-563.585"/>
<text text-anchor="middle" x="619.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_experiment</text>
</g>
<!-- file&#45;&gt;study -->
<g id="edge16" class="edge">
<title>file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M335.4472,-953.2516C205.3186,-918.0868 0,-850.9634 0,-777.5 0,-777.5 0,-777.5 0,-271 0,-179.3742 627.4075,-108.762 909.9312,-81.6099"/>
<polygon fill="#000000" stroke="#000000" points="910.6243,-85.0597 920.2455,-80.6233 909.9576,-78.0915 910.6243,-85.0597"/>
<text text-anchor="middle" x="30.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- file&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M544.5239,-925.1341C588.5158,-902.4631 640.4174,-875.7158 687.8739,-851.2594"/>
<polygon fill="#000000" stroke="#000000" points="689.705,-854.2532 696.9908,-846.561 686.4984,-848.0308 689.705,-854.2532"/>
<text text-anchor="middle" x="705.5" y="-868.8" font-family="Times,serif" font-size="14.00" fill="#000000">from_sample</text>
</g>
<!-- clinical_measure -->
<g id="node13" class="node">
<title>clinical_measure</title>
<path fill="none" stroke="#000000" d="M129.5,-731.5C129.5,-731.5 510.5,-731.5 510.5,-731.5 516.5,-731.5 522.5,-737.5 522.5,-743.5 522.5,-743.5 522.5,-811.5 522.5,-811.5 522.5,-817.5 516.5,-823.5 510.5,-823.5 510.5,-823.5 129.5,-823.5 129.5,-823.5 123.5,-823.5 117.5,-817.5 117.5,-811.5 117.5,-811.5 117.5,-743.5 117.5,-743.5 117.5,-737.5 123.5,-731.5 129.5,-731.5"/>
<text text-anchor="middle" x="186" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure</text>
<polyline fill="none" stroke="#000000" points="254.5,-731.5 254.5,-823.5 "/>
<text text-anchor="middle" x="265" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="275.5,-731.5 275.5,-823.5 "/>
<text text-anchor="middle" x="388.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_measure</text>
<polyline fill="none" stroke="#000000" points="275.5,-800.5 501.5,-800.5 "/>
<text text-anchor="middle" x="388.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_ID</text>
<polyline fill="none" stroke="#000000" points="275.5,-777.5 501.5,-777.5 "/>
<text text-anchor="middle" x="388.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_description</text>
<polyline fill="none" stroke="#000000" points="275.5,-754.5 501.5,-754.5 "/>
<text text-anchor="middle" x="388.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_measure</text>
<polyline fill="none" stroke="#000000" points="501.5,-731.5 501.5,-823.5 "/>
<text text-anchor="middle" x="512" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file&#45;&gt;clinical_measure -->
<g id="edge1" class="edge">
<title>file&#45;&gt;clinical_measure</title>
<path fill="none" stroke="#000000" d="M392.0555,-898.4932C378.8623,-876.3396 364.858,-852.824 352.7383,-832.4731"/>
<polygon fill="#000000" stroke="#000000" points="355.6143,-830.462 347.4904,-823.661 349.6001,-834.0437 355.6143,-830.462"/>
<text text-anchor="middle" x="451" y="-868.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure</text>
</g>
<!-- specimen -->
<g id="node6" class="node">
<title>specimen</title>
<path fill="none" stroke="#000000" d="M788.5,-512C788.5,-512 997.5,-512 997.5,-512 1003.5,-512 1009.5,-518 1009.5,-524 1009.5,-524 1009.5,-536 1009.5,-536 1009.5,-542 1003.5,-548 997.5,-548 997.5,-548 788.5,-548 788.5,-548 782.5,-548 776.5,-542 776.5,-536 776.5,-536 776.5,-524 776.5,-524 776.5,-518 782.5,-512 788.5,-512"/>
<text text-anchor="middle" x="819" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">specimen</text>
<polyline fill="none" stroke="#000000" points="861.5,-512 861.5,-548 "/>
<text text-anchor="middle" x="872" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="882.5,-512 882.5,-548 "/>
<text text-anchor="middle" x="935.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">specimen_id</text>
<polyline fill="none" stroke="#000000" points="988.5,-512 988.5,-548 "/>
<text text-anchor="middle" x="999" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- specimen&#45;&gt;study_subject -->
<g id="edge10" class="edge">
<title>specimen&#45;&gt;study_subject</title>
<path fill="none" stroke="#000000" d="M903.6883,-511.7876C921.9692,-480.6379 960.3831,-415.1828 992.5508,-360.3707"/>
<polygon fill="#000000" stroke="#000000" points="995.6129,-362.068 997.6558,-351.672 989.5757,-358.525 995.6129,-362.068"/>
<text text-anchor="middle" x="1043.5" y="-373.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_subject</text>
</g>
<!-- imaging_detail -->
<g id="node7" class="node">
<title>imaging_detail</title>
<path fill="none" stroke="#000000" d="M492,-1157.5C492,-1157.5 786,-1157.5 786,-1157.5 792,-1157.5 798,-1163.5 798,-1169.5 798,-1169.5 798,-1260.5 798,-1260.5 798,-1266.5 792,-1272.5 786,-1272.5 786,-1272.5 492,-1272.5 492,-1272.5 486,-1272.5 480,-1266.5 480,-1260.5 480,-1260.5 480,-1169.5 480,-1169.5 480,-1163.5 486,-1157.5 492,-1157.5"/>
<text text-anchor="middle" x="541" y="-1211.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_detail</text>
<polyline fill="none" stroke="#000000" points="602,-1157.5 602,-1272.5 "/>
<text text-anchor="middle" x="612.5" y="-1211.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="623,-1157.5 623,-1272.5 "/>
<text text-anchor="middle" x="700" y="-1257.3" font-family="Times,serif" font-size="14.00" fill="#000000">image_id</text>
<polyline fill="none" stroke="#000000" points="623,-1249.5 777,-1249.5 "/>
<text text-anchor="middle" x="700" y="-1234.3" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="623,-1226.5 777,-1226.5 "/>
<text text-anchor="middle" x="700" y="-1211.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="623,-1203.5 777,-1203.5 "/>
<text text-anchor="middle" x="700" y="-1188.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="623,-1180.5 777,-1180.5 "/>
<text text-anchor="middle" x="700" y="-1165.3" font-family="Times,serif" font-size="14.00" fill="#000000">software_packages</text>
<polyline fill="none" stroke="#000000" points="777,-1157.5 777,-1272.5 "/>
<text text-anchor="middle" x="787.5" y="-1211.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_detail&#45;&gt;file -->
<g id="edge4" class="edge">
<title>imaging_detail&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M590.3191,-1157.2679C567.6094,-1130.3357 540.0716,-1097.6779 514.8025,-1067.7105"/>
<polygon fill="#000000" stroke="#000000" points="517.2097,-1065.1358 508.0876,-1059.7471 511.8583,-1069.6483 517.2097,-1065.1358"/>
<text text-anchor="middle" x="556" y="-1081.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- therapeutic_procedure -->
<g id="node8" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M1154.5,-1180.5C1154.5,-1180.5 1511.5,-1180.5 1511.5,-1180.5 1517.5,-1180.5 1523.5,-1186.5 1523.5,-1192.5 1523.5,-1192.5 1523.5,-1237.5 1523.5,-1237.5 1523.5,-1243.5 1517.5,-1249.5 1511.5,-1249.5 1511.5,-1249.5 1154.5,-1249.5 1154.5,-1249.5 1148.5,-1249.5 1142.5,-1243.5 1142.5,-1237.5 1142.5,-1237.5 1142.5,-1192.5 1142.5,-1192.5 1142.5,-1186.5 1148.5,-1180.5 1154.5,-1180.5"/>
<text text-anchor="middle" x="1233" y="-1211.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="1323.5,-1180.5 1323.5,-1249.5 "/>
<text text-anchor="middle" x="1334" y="-1211.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1344.5,-1180.5 1344.5,-1249.5 "/>
<text text-anchor="middle" x="1423.5" y="-1234.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="1344.5,-1226.5 1502.5,-1226.5 "/>
<text text-anchor="middle" x="1423.5" y="-1211.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="1344.5,-1203.5 1502.5,-1203.5 "/>
<text text-anchor="middle" x="1423.5" y="-1188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1502.5,-1180.5 1502.5,-1249.5 "/>
<text text-anchor="middle" x="1513" y="-1211.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis -->
<g id="node10" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1040,-403.5C1040,-403.5 1354,-403.5 1354,-403.5 1360,-403.5 1366,-409.5 1366,-415.5 1366,-415.5 1366,-644.5 1366,-644.5 1366,-650.5 1360,-656.5 1354,-656.5 1354,-656.5 1040,-656.5 1040,-656.5 1034,-656.5 1028,-650.5 1028,-644.5 1028,-644.5 1028,-415.5 1028,-415.5 1028,-409.5 1034,-403.5 1040,-403.5"/>
<text text-anchor="middle" x="1070" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1112,-403.5 1112,-656.5 "/>
<text text-anchor="middle" x="1122.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1133,-403.5 1133,-656.5 "/>
<text text-anchor="middle" x="1239" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1133,-633.5 1345,-633.5 "/>
<text text-anchor="middle" x="1239" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_status</text>
<polyline fill="none" stroke="#000000" points="1133,-610.5 1345,-610.5 "/>
<text text-anchor="middle" x="1239" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1133,-587.5 1345,-587.5 "/>
<text text-anchor="middle" x="1239" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_ID</text>
<polyline fill="none" stroke="#000000" points="1133,-564.5 1345,-564.5 "/>
<text text-anchor="middle" x="1239" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">incidence_type</text>
<polyline fill="none" stroke="#000000" points="1133,-541.5 1345,-541.5 "/>
<text text-anchor="middle" x="1239" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1133,-518.5 1345,-518.5 "/>
<text text-anchor="middle" x="1239" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1133,-495.5 1345,-495.5 "/>
<text text-anchor="middle" x="1239" y="-480.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="1133,-472.5 1345,-472.5 "/>
<text text-anchor="middle" x="1239" y="-457.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1133,-449.5 1345,-449.5 "/>
<text text-anchor="middle" x="1239" y="-434.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="1133,-426.5 1345,-426.5 "/>
<text text-anchor="middle" x="1239" y="-411.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage</text>
<polyline fill="none" stroke="#000000" points="1345,-403.5 1345,-656.5 "/>
<text text-anchor="middle" x="1355.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;study_subject -->
<g id="edge12" class="edge">
<title>diagnosis&#45;&gt;study_subject</title>
<path fill="none" stroke="#000000" d="M1127.4881,-403.3974C1120.9858,-392.0546 1114.4248,-380.7871 1108,-370 1106.0893,-366.792 1104.1293,-363.5359 1102.1368,-360.255"/>
<polygon fill="#000000" stroke="#000000" points="1105.0025,-358.2324 1096.7983,-351.5286 1099.0312,-361.8854 1105.0025,-358.2324"/>
<text text-anchor="middle" x="1176.5" y="-373.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_subject</text>
</g>
<!-- study_admin -->
<g id="node11" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M1500.5,-213.5C1500.5,-213.5 1771.5,-213.5 1771.5,-213.5 1777.5,-213.5 1783.5,-219.5 1783.5,-225.5 1783.5,-225.5 1783.5,-316.5 1783.5,-316.5 1783.5,-322.5 1777.5,-328.5 1771.5,-328.5 1771.5,-328.5 1500.5,-328.5 1500.5,-328.5 1494.5,-328.5 1488.5,-322.5 1488.5,-316.5 1488.5,-316.5 1488.5,-225.5 1488.5,-225.5 1488.5,-219.5 1494.5,-213.5 1500.5,-213.5"/>
<text text-anchor="middle" x="1542.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="1596.5,-213.5 1596.5,-328.5 "/>
<text text-anchor="middle" x="1607" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1617.5,-213.5 1617.5,-328.5 "/>
<text text-anchor="middle" x="1690" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_access_level</text>
<polyline fill="none" stroke="#000000" points="1617.5,-305.5 1762.5,-305.5 "/>
<text text-anchor="middle" x="1690" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="1617.5,-282.5 1762.5,-282.5 "/>
<text text-anchor="middle" x="1690" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types</text>
<polyline fill="none" stroke="#000000" points="1617.5,-259.5 1762.5,-259.5 "/>
<text text-anchor="middle" x="1690" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">species</text>
<polyline fill="none" stroke="#000000" points="1617.5,-236.5 1762.5,-236.5 "/>
<text text-anchor="middle" x="1690" y="-221.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_type</text>
<polyline fill="none" stroke="#000000" points="1762.5,-213.5 1762.5,-328.5 "/>
<text text-anchor="middle" x="1773" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge17" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1567.6158,-213.4335C1540.0523,-192.8421 1506.9997,-171.2332 1474,-157 1380.1735,-116.5315 1266.5934,-94.4365 1179.8769,-82.5777"/>
<polygon fill="#000000" stroke="#000000" points="1180.0816,-79.0739 1169.7057,-81.2167 1179.1532,-86.0121 1180.0816,-79.0739"/>
<text text-anchor="middle" x="1532.5" y="-160.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- sample&#45;&gt;study_subject -->
<g id="edge9" class="edge">
<title>sample&#45;&gt;study_subject</title>
<path fill="none" stroke="#000000" d="M679.7092,-709.4084C678.1353,-708.927 676.5653,-708.4573 675,-708 601.8753,-686.6382 385.7,-714.7362 336,-657 262.3521,-571.4436 259.978,-486.4539 336,-403 415.9807,-315.2004 747.3528,-381.7714 881.1034,-351.788"/>
<polygon fill="#000000" stroke="#000000" points="882.3124,-355.0923 891.1465,-349.2436 880.5932,-348.3067 882.3124,-355.0923"/>
<text text-anchor="middle" x="396.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_subject</text>
</g>
<!-- sample&#45;&gt;experiment -->
<g id="edge6" class="edge">
<title>sample&#45;&gt;experiment</title>
<path fill="none" stroke="#000000" d="M764.509,-708.0896C758.8832,-702.0099 753.3163,-695.9197 748,-690 708.4768,-645.9914 664.4227,-593.497 637.457,-560.9509"/>
<polygon fill="#000000" stroke="#000000" points="640.0533,-558.5984 630.9826,-553.1236 634.6594,-563.06 640.0533,-558.5984"/>
<text text-anchor="middle" x="799.5" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_experiment</text>
</g>
<!-- sample&#45;&gt;specimen -->
<g id="edge13" class="edge">
<title>sample&#45;&gt;specimen</title>
<path fill="none" stroke="#000000" d="M848.3529,-708.2283C860.8081,-658.5079 876.9355,-594.1285 886.0044,-557.926"/>
<polygon fill="#000000" stroke="#000000" points="889.4384,-558.6208 888.4734,-548.07 882.6482,-556.9198 889.4384,-558.6208"/>
<text text-anchor="middle" x="902" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_specimen</text>
</g>
<!-- genomic_detail -->
<g id="node14" class="node">
<title>genomic_detail</title>
<path fill="none" stroke="#000000" d="M58,-1111.5C58,-1111.5 450,-1111.5 450,-1111.5 456,-1111.5 462,-1117.5 462,-1123.5 462,-1123.5 462,-1306.5 462,-1306.5 462,-1312.5 456,-1318.5 450,-1318.5 450,-1318.5 58,-1318.5 58,-1318.5 52,-1318.5 46,-1312.5 46,-1306.5 46,-1306.5 46,-1123.5 46,-1123.5 46,-1117.5 52,-1111.5 58,-1111.5"/>
<text text-anchor="middle" x="108.5" y="-1211.3" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_detail</text>
<polyline fill="none" stroke="#000000" points="171,-1111.5 171,-1318.5 "/>
<text text-anchor="middle" x="181.5" y="-1211.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="192,-1111.5 192,-1318.5 "/>
<text text-anchor="middle" x="316.5" y="-1303.3" font-family="Times,serif" font-size="14.00" fill="#000000">average_read_length</text>
<polyline fill="none" stroke="#000000" points="192,-1295.5 441,-1295.5 "/>
<text text-anchor="middle" x="316.5" y="-1280.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="192,-1272.5 441,-1272.5 "/>
<text text-anchor="middle" x="316.5" y="-1257.3" font-family="Times,serif" font-size="14.00" fill="#000000">genome_reference_or_accession</text>
<polyline fill="none" stroke="#000000" points="192,-1249.5 441,-1249.5 "/>
<text text-anchor="middle" x="316.5" y="-1234.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="192,-1226.5 441,-1226.5 "/>
<text text-anchor="middle" x="316.5" y="-1211.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="192,-1203.5 441,-1203.5 "/>
<text text-anchor="middle" x="316.5" y="-1188.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="192,-1180.5 441,-1180.5 "/>
<text text-anchor="middle" x="316.5" y="-1165.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="192,-1157.5 441,-1157.5 "/>
<text text-anchor="middle" x="316.5" y="-1142.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="192,-1134.5 441,-1134.5 "/>
<text text-anchor="middle" x="316.5" y="-1119.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="441,-1111.5 441,-1318.5 "/>
<text text-anchor="middle" x="451.5" y="-1211.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genomic_detail&#45;&gt;file -->
<g id="edge3" class="edge">
<title>genomic_detail&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M335.5823,-1111.487C347.1124,-1096.8574 358.8802,-1081.9262 370.1623,-1067.6113"/>
<polygon fill="#000000" stroke="#000000" points="372.9344,-1069.7483 376.3755,-1059.7278 367.4367,-1065.4153 372.9344,-1069.7483"/>
<text text-anchor="middle" x="381" y="-1081.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
</g>
</svg>
</div>