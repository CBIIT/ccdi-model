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
<svg width="2603pt" height="1528pt"
 viewBox="0.00 0.00 2602.61 1528.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1524)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1524 2598.6077,-1524 2598.6077,4 -4,4"/>
<!-- clinical_measure_file -->
<g id="node1" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M48.6077,-674C48.6077,-674 400.6077,-674 400.6077,-674 406.6077,-674 412.6077,-680 412.6077,-686 412.6077,-686 412.6077,-915 412.6077,-915 412.6077,-921 406.6077,-927 400.6077,-927 400.6077,-927 48.6077,-927 48.6077,-927 42.6077,-927 36.6077,-921 36.6077,-915 36.6077,-915 36.6077,-686 36.6077,-686 36.6077,-680 42.6077,-674 48.6077,-674"/>
<text text-anchor="middle" x="120.1077" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="203.6077,-674 203.6077,-927 "/>
<text text-anchor="middle" x="214.1077" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="224.6077,-674 224.6077,-927 "/>
<text text-anchor="middle" x="308.1077" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="224.6077,-904 391.6077,-904 "/>
<text text-anchor="middle" x="308.1077" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="224.6077,-881 391.6077,-881 "/>
<text text-anchor="middle" x="308.1077" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="224.6077,-858 391.6077,-858 "/>
<text text-anchor="middle" x="308.1077" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="224.6077,-835 391.6077,-835 "/>
<text text-anchor="middle" x="308.1077" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="224.6077,-812 391.6077,-812 "/>
<text text-anchor="middle" x="308.1077" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="224.6077,-789 391.6077,-789 "/>
<text text-anchor="middle" x="308.1077" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="224.6077,-766 391.6077,-766 "/>
<text text-anchor="middle" x="308.1077" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="224.6077,-743 391.6077,-743 "/>
<text text-anchor="middle" x="308.1077" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="224.6077,-720 391.6077,-720 "/>
<text text-anchor="middle" x="308.1077" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="224.6077,-697 391.6077,-697 "/>
<text text-anchor="middle" x="308.1077" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="391.6077,-674 391.6077,-927 "/>
<text text-anchor="middle" x="402.1077" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node8" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M918.1077,-495.5C918.1077,-495.5 1149.1077,-495.5 1149.1077,-495.5 1155.1077,-495.5 1161.1077,-501.5 1161.1077,-507.5 1161.1077,-507.5 1161.1077,-575.5 1161.1077,-575.5 1161.1077,-581.5 1155.1077,-587.5 1149.1077,-587.5 1149.1077,-587.5 918.1077,-587.5 918.1077,-587.5 912.1077,-587.5 906.1077,-581.5 906.1077,-575.5 906.1077,-575.5 906.1077,-507.5 906.1077,-507.5 906.1077,-501.5 912.1077,-495.5 918.1077,-495.5"/>
<text text-anchor="middle" x="954.1077" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1002.1077,-495.5 1002.1077,-587.5 "/>
<text text-anchor="middle" x="1012.6077" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1023.1077,-495.5 1023.1077,-587.5 "/>
<text text-anchor="middle" x="1081.6077" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="1023.1077,-564.5 1140.1077,-564.5 "/>
<text text-anchor="middle" x="1081.6077" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="1023.1077,-541.5 1140.1077,-541.5 "/>
<text text-anchor="middle" x="1081.6077" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1023.1077,-518.5 1140.1077,-518.5 "/>
<text text-anchor="middle" x="1081.6077" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1140.1077,-495.5 1140.1077,-587.5 "/>
<text text-anchor="middle" x="1150.6077" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M363.8022,-673.9751C382.4115,-660.8609 401.8996,-648.7818 421.6077,-639 502.7072,-598.7476 741.6939,-569.2801 895.9115,-553.8149"/>
<polygon fill="#000000" stroke="#000000" points="896.3401,-557.2896 905.9444,-552.8165 895.6469,-550.324 896.3401,-557.2896"/>
<text text-anchor="middle" x="649.1077" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- study -->
<g id="node10" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M591.6077,-.5C591.6077,-.5 981.6077,-.5 981.6077,-.5 987.6077,-.5 993.6077,-6.5 993.6077,-12.5 993.6077,-12.5 993.6077,-195.5 993.6077,-195.5 993.6077,-201.5 987.6077,-207.5 981.6077,-207.5 981.6077,-207.5 591.6077,-207.5 591.6077,-207.5 585.6077,-207.5 579.6077,-201.5 579.6077,-195.5 579.6077,-195.5 579.6077,-12.5 579.6077,-12.5 579.6077,-6.5 585.6077,-.5 591.6077,-.5"/>
<text text-anchor="middle" x="607.6077" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="635.6077,-.5 635.6077,-207.5 "/>
<text text-anchor="middle" x="646.1077" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="656.6077,-.5 656.6077,-207.5 "/>
<text text-anchor="middle" x="814.6077" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="656.6077,-184.5 972.6077,-184.5 "/>
<text text-anchor="middle" x="814.6077" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="656.6077,-161.5 972.6077,-161.5 "/>
<text text-anchor="middle" x="814.6077" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="656.6077,-138.5 972.6077,-138.5 "/>
<text text-anchor="middle" x="814.6077" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="656.6077,-115.5 972.6077,-115.5 "/>
<text text-anchor="middle" x="814.6077" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="656.6077,-92.5 972.6077,-92.5 "/>
<text text-anchor="middle" x="814.6077" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="656.6077,-69.5 972.6077,-69.5 "/>
<text text-anchor="middle" x="814.6077" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="656.6077,-46.5 972.6077,-46.5 "/>
<text text-anchor="middle" x="814.6077" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="656.6077,-23.5 972.6077,-23.5 "/>
<text text-anchor="middle" x="814.6077" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="972.6077,-.5 972.6077,-207.5 "/>
<text text-anchor="middle" x="983.1077" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge3" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M188.658,-673.7236C173.6616,-614.4928 158.0256,-542.6944 150.6077,-477 140.3756,-386.383 161.0598,-327.1422 216.6077,-259 261.9304,-203.4013 427.9291,-162.2819 569.1818,-136.4198"/>
<polygon fill="#000000" stroke="#000000" points="570.092,-139.8119 579.3072,-134.5841 568.8432,-132.9242 570.092,-139.8119"/>
<text text-anchor="middle" x="236.6077" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- therapeutic_procedure -->
<g id="node2" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M443.1077,-743C443.1077,-743 800.1077,-743 800.1077,-743 806.1077,-743 812.1077,-749 812.1077,-755 812.1077,-755 812.1077,-846 812.1077,-846 812.1077,-852 806.1077,-858 800.1077,-858 800.1077,-858 443.1077,-858 443.1077,-858 437.1077,-858 431.1077,-852 431.1077,-846 431.1077,-846 431.1077,-755 431.1077,-755 431.1077,-749 437.1077,-743 443.1077,-743"/>
<text text-anchor="middle" x="521.6077" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="612.1077,-743 612.1077,-858 "/>
<text text-anchor="middle" x="622.6077" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="633.1077,-743 633.1077,-858 "/>
<text text-anchor="middle" x="712.1077" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="633.1077,-835 791.1077,-835 "/>
<text text-anchor="middle" x="712.1077" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="633.1077,-812 791.1077,-812 "/>
<text text-anchor="middle" x="712.1077" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="633.1077,-789 791.1077,-789 "/>
<text text-anchor="middle" x="712.1077" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="633.1077,-766 791.1077,-766 "/>
<text text-anchor="middle" x="712.1077" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="791.1077,-743 791.1077,-858 "/>
<text text-anchor="middle" x="801.6077" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M675.2049,-742.5661C717.4437,-699.8102 779.697,-642.8791 843.6077,-606 860.0514,-596.5113 878.105,-588.1394 896.3377,-580.8388"/>
<polygon fill="#000000" stroke="#000000" points="897.8352,-584.0117 905.881,-577.1185 895.2926,-577.4897 897.8352,-584.0117"/>
<text text-anchor="middle" x="936.6077" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- study_arm -->
<g id="node3" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M1351.1077,-317C1351.1077,-317 1648.1077,-317 1648.1077,-317 1654.1077,-317 1660.1077,-323 1660.1077,-329 1660.1077,-329 1660.1077,-374 1660.1077,-374 1660.1077,-380 1654.1077,-386 1648.1077,-386 1648.1077,-386 1351.1077,-386 1351.1077,-386 1345.1077,-386 1339.1077,-380 1339.1077,-374 1339.1077,-374 1339.1077,-329 1339.1077,-329 1339.1077,-323 1345.1077,-317 1351.1077,-317"/>
<text text-anchor="middle" x="1385.1077" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="1431.1077,-317 1431.1077,-386 "/>
<text text-anchor="middle" x="1441.6077" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1452.1077,-317 1452.1077,-386 "/>
<text text-anchor="middle" x="1545.6077" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="1452.1077,-363 1639.1077,-363 "/>
<text text-anchor="middle" x="1545.6077" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="1452.1077,-340 1639.1077,-340 "/>
<text text-anchor="middle" x="1545.6077" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="1639.1077,-317 1639.1077,-386 "/>
<text text-anchor="middle" x="1649.6077" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1443.3154,-316.7877C1410.9201,-297.8629 1368.9493,-275.0882 1329.6077,-259 1224.999,-216.2217 1104.4919,-180.5393 1003.6181,-154.2367"/>
<polygon fill="#000000" stroke="#000000" points="1004.4771,-150.8438 993.9186,-151.7207 1002.7194,-157.6195 1004.4771,-150.8438"/>
<text text-anchor="middle" x="1320.1077" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- publication -->
<g id="node4" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M380.6077,-333.5C380.6077,-333.5 590.6077,-333.5 590.6077,-333.5 596.6077,-333.5 602.6077,-339.5 602.6077,-345.5 602.6077,-345.5 602.6077,-357.5 602.6077,-357.5 602.6077,-363.5 596.6077,-369.5 590.6077,-369.5 590.6077,-369.5 380.6077,-369.5 380.6077,-369.5 374.6077,-369.5 368.6077,-363.5 368.6077,-357.5 368.6077,-357.5 368.6077,-345.5 368.6077,-345.5 368.6077,-339.5 374.6077,-333.5 380.6077,-333.5"/>
<text text-anchor="middle" x="417.1077" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="465.6077,-333.5 465.6077,-369.5 "/>
<text text-anchor="middle" x="476.1077" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="486.6077,-333.5 486.6077,-369.5 "/>
<text text-anchor="middle" x="534.1077" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="581.6077,-333.5 581.6077,-369.5 "/>
<text text-anchor="middle" x="592.1077" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge6" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M507.7409,-333.3007C538.6666,-307.8718 597.2714,-259.6835 652.8056,-214.02"/>
<polygon fill="#000000" stroke="#000000" points="655.1169,-216.6508 660.6181,-207.5961 650.671,-211.2439 655.1169,-216.6508"/>
<text text-anchor="middle" x="687.6077" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- methylation_array_file -->
<g id="node5" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M2236.6077,-1151.5C2236.6077,-1151.5 2582.6077,-1151.5 2582.6077,-1151.5 2588.6077,-1151.5 2594.6077,-1157.5 2594.6077,-1163.5 2594.6077,-1163.5 2594.6077,-1369.5 2594.6077,-1369.5 2594.6077,-1375.5 2588.6077,-1381.5 2582.6077,-1381.5 2582.6077,-1381.5 2236.6077,-1381.5 2236.6077,-1381.5 2230.6077,-1381.5 2224.6077,-1375.5 2224.6077,-1369.5 2224.6077,-1369.5 2224.6077,-1163.5 2224.6077,-1163.5 2224.6077,-1157.5 2230.6077,-1151.5 2236.6077,-1151.5"/>
<text text-anchor="middle" x="2313.6077" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="2402.6077,-1151.5 2402.6077,-1381.5 "/>
<text text-anchor="middle" x="2413.1077" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2423.6077,-1151.5 2423.6077,-1381.5 "/>
<text text-anchor="middle" x="2498.6077" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2423.6077,-1358.5 2573.6077,-1358.5 "/>
<text text-anchor="middle" x="2498.6077" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2423.6077,-1335.5 2573.6077,-1335.5 "/>
<text text-anchor="middle" x="2498.6077" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2423.6077,-1312.5 2573.6077,-1312.5 "/>
<text text-anchor="middle" x="2498.6077" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2423.6077,-1289.5 2573.6077,-1289.5 "/>
<text text-anchor="middle" x="2498.6077" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2423.6077,-1266.5 2573.6077,-1266.5 "/>
<text text-anchor="middle" x="2498.6077" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2423.6077,-1243.5 2573.6077,-1243.5 "/>
<text text-anchor="middle" x="2498.6077" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2423.6077,-1220.5 2573.6077,-1220.5 "/>
<text text-anchor="middle" x="2498.6077" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2423.6077,-1197.5 2573.6077,-1197.5 "/>
<text text-anchor="middle" x="2498.6077" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="2423.6077,-1174.5 2573.6077,-1174.5 "/>
<text text-anchor="middle" x="2498.6077" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="2573.6077,-1151.5 2573.6077,-1381.5 "/>
<text text-anchor="middle" x="2584.1077" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node12" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1501.6077,-639.5C1501.6077,-639.5 1815.6077,-639.5 1815.6077,-639.5 1821.6077,-639.5 1827.6077,-645.5 1827.6077,-651.5 1827.6077,-651.5 1827.6077,-949.5 1827.6077,-949.5 1827.6077,-955.5 1821.6077,-961.5 1815.6077,-961.5 1815.6077,-961.5 1501.6077,-961.5 1501.6077,-961.5 1495.6077,-961.5 1489.6077,-955.5 1489.6077,-949.5 1489.6077,-949.5 1489.6077,-651.5 1489.6077,-651.5 1489.6077,-645.5 1495.6077,-639.5 1501.6077,-639.5"/>
<text text-anchor="middle" x="1523.6077" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1557.6077,-639.5 1557.6077,-961.5 "/>
<text text-anchor="middle" x="1568.1077" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1578.6077,-639.5 1578.6077,-961.5 "/>
<text text-anchor="middle" x="1692.6077" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1578.6077,-938.5 1806.6077,-938.5 "/>
<text text-anchor="middle" x="1692.6077" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1578.6077,-915.5 1806.6077,-915.5 "/>
<text text-anchor="middle" x="1692.6077" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1578.6077,-892.5 1806.6077,-892.5 "/>
<text text-anchor="middle" x="1692.6077" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1578.6077,-869.5 1806.6077,-869.5 "/>
<text text-anchor="middle" x="1692.6077" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1578.6077,-846.5 1806.6077,-846.5 "/>
<text text-anchor="middle" x="1692.6077" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="1578.6077,-823.5 1806.6077,-823.5 "/>
<text text-anchor="middle" x="1692.6077" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1578.6077,-800.5 1806.6077,-800.5 "/>
<text text-anchor="middle" x="1692.6077" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="1578.6077,-777.5 1806.6077,-777.5 "/>
<text text-anchor="middle" x="1692.6077" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="1578.6077,-754.5 1806.6077,-754.5 "/>
<text text-anchor="middle" x="1692.6077" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage</text>
<polyline fill="none" stroke="#000000" points="1578.6077,-731.5 1806.6077,-731.5 "/>
<text text-anchor="middle" x="1692.6077" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1578.6077,-708.5 1806.6077,-708.5 "/>
<text text-anchor="middle" x="1692.6077" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1578.6077,-685.5 1806.6077,-685.5 "/>
<text text-anchor="middle" x="1692.6077" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1578.6077,-662.5 1806.6077,-662.5 "/>
<text text-anchor="middle" x="1692.6077" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_status</text>
<polyline fill="none" stroke="#000000" points="1806.6077,-639.5 1806.6077,-961.5 "/>
<text text-anchor="middle" x="1817.1077" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2341.7364,-1151.3419C2308.7067,-1103.28 2265.3555,-1050.1186 2215.6077,-1013 2103.0519,-929.018 1953.336,-874.3644 1837.4709,-841.5424"/>
<polygon fill="#000000" stroke="#000000" points="1838.3545,-838.1552 1827.781,-838.8258 1836.4649,-844.8954 1838.3545,-838.1552"/>
<text text-anchor="middle" x="2280.1077" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study_personnel -->
<g id="node6" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M633.1077,-294C633.1077,-294 940.1077,-294 940.1077,-294 946.1077,-294 952.1077,-300 952.1077,-306 952.1077,-306 952.1077,-397 952.1077,-397 952.1077,-403 946.1077,-409 940.1077,-409 940.1077,-409 633.1077,-409 633.1077,-409 627.1077,-409 621.1077,-403 621.1077,-397 621.1077,-397 621.1077,-306 621.1077,-306 621.1077,-300 627.1077,-294 633.1077,-294"/>
<text text-anchor="middle" x="688.1077" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="755.1077,-294 755.1077,-409 "/>
<text text-anchor="middle" x="765.6077" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="776.1077,-294 776.1077,-409 "/>
<text text-anchor="middle" x="853.6077" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="776.1077,-386 931.1077,-386 "/>
<text text-anchor="middle" x="853.6077" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="776.1077,-363 931.1077,-363 "/>
<text text-anchor="middle" x="853.6077" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="776.1077,-340 931.1077,-340 "/>
<text text-anchor="middle" x="853.6077" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="776.1077,-317 931.1077,-317 "/>
<text text-anchor="middle" x="853.6077" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="931.1077,-294 931.1077,-409 "/>
<text text-anchor="middle" x="941.6077" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge9" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M786.6077,-293.7846C786.6077,-271.1126 786.6077,-244.2586 786.6077,-217.9942"/>
<polygon fill="#000000" stroke="#000000" points="790.1078,-217.967 786.6077,-207.967 783.1078,-217.967 790.1078,-217.967"/>
<text text-anchor="middle" x="856.1077" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- study_admin -->
<g id="node7" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M982.6077,-259.5C982.6077,-259.5 1308.6077,-259.5 1308.6077,-259.5 1314.6077,-259.5 1320.6077,-265.5 1320.6077,-271.5 1320.6077,-271.5 1320.6077,-431.5 1320.6077,-431.5 1320.6077,-437.5 1314.6077,-443.5 1308.6077,-443.5 1308.6077,-443.5 982.6077,-443.5 982.6077,-443.5 976.6077,-443.5 970.6077,-437.5 970.6077,-431.5 970.6077,-431.5 970.6077,-271.5 970.6077,-271.5 970.6077,-265.5 976.6077,-259.5 982.6077,-259.5"/>
<text text-anchor="middle" x="1024.6077" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="1078.6077,-259.5 1078.6077,-443.5 "/>
<text text-anchor="middle" x="1089.1077" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1099.6077,-259.5 1099.6077,-443.5 "/>
<text text-anchor="middle" x="1199.6077" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="1099.6077,-420.5 1299.6077,-420.5 "/>
<text text-anchor="middle" x="1199.6077" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="1099.6077,-397.5 1299.6077,-397.5 "/>
<text text-anchor="middle" x="1199.6077" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="1099.6077,-374.5 1299.6077,-374.5 "/>
<text text-anchor="middle" x="1199.6077" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="1099.6077,-351.5 1299.6077,-351.5 "/>
<text text-anchor="middle" x="1199.6077" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="1099.6077,-328.5 1299.6077,-328.5 "/>
<text text-anchor="middle" x="1199.6077" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="1099.6077,-305.5 1299.6077,-305.5 "/>
<text text-anchor="middle" x="1199.6077" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="1099.6077,-282.5 1299.6077,-282.5 "/>
<text text-anchor="middle" x="1199.6077" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="1299.6077,-259.5 1299.6077,-443.5 "/>
<text text-anchor="middle" x="1310.1077" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge7" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1011.9293,-259.3401C990.275,-244.4113 967.6672,-228.8251 945.4851,-213.5325"/>
<polygon fill="#000000" stroke="#000000" points="947.227,-210.4822 937.0073,-207.6878 943.2538,-216.2454 947.227,-210.4822"/>
<text text-anchor="middle" x="1033.1077" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge19" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1161.1417,-505.0213C1214.0668,-488.4676 1275.6043,-467.3598 1329.6077,-444 1364.8329,-428.7629 1402.4684,-408.7077 1433.3504,-391.1674"/>
<polygon fill="#000000" stroke="#000000" points="1435.3474,-394.0573 1442.2895,-386.0537 1431.8715,-387.9813 1435.3474,-394.0573"/>
<text text-anchor="middle" x="1332.1077" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge18" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M906.0689,-529.8576C691.5766,-509.6644 279.7867,-468.0105 258.6077,-444 204.2173,-382.3382 209.3317,-324.8208 258.6077,-259 297.1798,-207.477 441.4155,-167.2517 569.4023,-140.7045"/>
<polygon fill="#000000" stroke="#000000" points="570.2785,-144.0977 579.37,-138.6576 568.8704,-137.2408 570.2785,-144.0977"/>
<text text-anchor="middle" x="309.1077" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- synonym -->
<g id="node9" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M1051.1077,-1220.5C1051.1077,-1220.5 1352.1077,-1220.5 1352.1077,-1220.5 1358.1077,-1220.5 1364.1077,-1226.5 1364.1077,-1232.5 1364.1077,-1232.5 1364.1077,-1300.5 1364.1077,-1300.5 1364.1077,-1306.5 1358.1077,-1312.5 1352.1077,-1312.5 1352.1077,-1312.5 1051.1077,-1312.5 1051.1077,-1312.5 1045.1077,-1312.5 1039.1077,-1306.5 1039.1077,-1300.5 1039.1077,-1300.5 1039.1077,-1232.5 1039.1077,-1232.5 1039.1077,-1226.5 1045.1077,-1220.5 1051.1077,-1220.5"/>
<text text-anchor="middle" x="1079.1077" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="1119.1077,-1220.5 1119.1077,-1312.5 "/>
<text text-anchor="middle" x="1129.6077" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1140.1077,-1220.5 1140.1077,-1312.5 "/>
<text text-anchor="middle" x="1241.6077" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_id</text>
<polyline fill="none" stroke="#000000" points="1140.1077,-1289.5 1343.1077,-1289.5 "/>
<text text-anchor="middle" x="1241.6077" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_node</text>
<polyline fill="none" stroke="#000000" points="1140.1077,-1266.5 1343.1077,-1266.5 "/>
<text text-anchor="middle" x="1241.6077" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="1140.1077,-1243.5 1343.1077,-1243.5 "/>
<text text-anchor="middle" x="1241.6077" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="1343.1077,-1220.5 1343.1077,-1312.5 "/>
<text text-anchor="middle" x="1353.6077" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1222.3386,-1220.1229C1268.3952,-1109.4203 1366.1006,-825.1142 1246.6077,-639 1228.6864,-611.0871 1200.5635,-591.0634 1170.5586,-576.7353"/>
<polygon fill="#000000" stroke="#000000" points="1171.7466,-573.4305 1161.1955,-572.4691 1168.8442,-579.8004 1171.7466,-573.4305"/>
<text text-anchor="middle" x="1346.1077" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge15" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1038.8277,-1246.9285C748.6143,-1208.5319 159.801,-1113.6176 27.6077,-962 -19.8882,-907.5252 8.6077,-872.7728 8.6077,-800.5 8.6077,-800.5 8.6077,-800.5 8.6077,-351.5 8.6077,-233.2664 339.023,-164.023 569.1976,-130.1307"/>
<polygon fill="#000000" stroke="#000000" points="570.0055,-133.5499 579.3952,-128.6425 568.9946,-126.6233 570.0055,-133.5499"/>
<text text-anchor="middle" x="51.1077" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1226.7148,-1220.12C1257.0751,-1166.5661 1311.8501,-1077.5712 1373.6077,-1013 1405.8671,-979.2708 1443.9366,-946.9261 1481.5687,-918.0912"/>
<polygon fill="#000000" stroke="#000000" points="1483.7482,-920.8309 1489.5901,-911.9921 1479.5114,-915.2586 1483.7482,-920.8309"/>
<text text-anchor="middle" x="1443.1077" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- sequencing_file -->
<g id="node11" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M1394.1077,-1013.5C1394.1077,-1013.5 1863.1077,-1013.5 1863.1077,-1013.5 1869.1077,-1013.5 1875.1077,-1019.5 1875.1077,-1025.5 1875.1077,-1025.5 1875.1077,-1507.5 1875.1077,-1507.5 1875.1077,-1513.5 1869.1077,-1519.5 1863.1077,-1519.5 1863.1077,-1519.5 1394.1077,-1519.5 1394.1077,-1519.5 1388.1077,-1519.5 1382.1077,-1513.5 1382.1077,-1507.5 1382.1077,-1507.5 1382.1077,-1025.5 1382.1077,-1025.5 1382.1077,-1019.5 1388.1077,-1013.5 1394.1077,-1013.5"/>
<text text-anchor="middle" x="1446.1077" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="1510.1077,-1013.5 1510.1077,-1519.5 "/>
<text text-anchor="middle" x="1520.6077" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1531.1077,-1013.5 1531.1077,-1519.5 "/>
<text text-anchor="middle" x="1692.6077" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="1531.1077,-1496.5 1854.1077,-1496.5 "/>
<text text-anchor="middle" x="1692.6077" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1531.1077,-1473.5 1854.1077,-1473.5 "/>
<text text-anchor="middle" x="1692.6077" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1531.1077,-1450.5 1854.1077,-1450.5 "/>
<text text-anchor="middle" x="1692.6077" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="1531.1077,-1427.5 1854.1077,-1427.5 "/>
<text text-anchor="middle" x="1692.6077" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="1531.1077,-1404.5 1854.1077,-1404.5 "/>
<text text-anchor="middle" x="1692.6077" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1531.1077,-1381.5 1854.1077,-1381.5 "/>
<text text-anchor="middle" x="1692.6077" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1531.1077,-1358.5 1854.1077,-1358.5 "/>
<text text-anchor="middle" x="1692.6077" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1531.1077,-1335.5 1854.1077,-1335.5 "/>
<text text-anchor="middle" x="1692.6077" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1531.1077,-1312.5 1854.1077,-1312.5 "/>
<text text-anchor="middle" x="1692.6077" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1531.1077,-1289.5 1854.1077,-1289.5 "/>
<text text-anchor="middle" x="1692.6077" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1531.1077,-1266.5 1854.1077,-1266.5 "/>
<text text-anchor="middle" x="1692.6077" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1531.1077,-1243.5 1854.1077,-1243.5 "/>
<text text-anchor="middle" x="1692.6077" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="1531.1077,-1220.5 1854.1077,-1220.5 "/>
<text text-anchor="middle" x="1692.6077" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="1531.1077,-1197.5 1854.1077,-1197.5 "/>
<text text-anchor="middle" x="1692.6077" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="1531.1077,-1174.5 1854.1077,-1174.5 "/>
<text text-anchor="middle" x="1692.6077" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="1531.1077,-1151.5 1854.1077,-1151.5 "/>
<text text-anchor="middle" x="1692.6077" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="1531.1077,-1128.5 1854.1077,-1128.5 "/>
<text text-anchor="middle" x="1692.6077" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1531.1077,-1105.5 1854.1077,-1105.5 "/>
<text text-anchor="middle" x="1692.6077" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="1531.1077,-1082.5 1854.1077,-1082.5 "/>
<text text-anchor="middle" x="1692.6077" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="1531.1077,-1059.5 1854.1077,-1059.5 "/>
<text text-anchor="middle" x="1692.6077" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="1531.1077,-1036.5 1854.1077,-1036.5 "/>
<text text-anchor="middle" x="1692.6077" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="1854.1077,-1013.5 1854.1077,-1519.5 "/>
<text text-anchor="middle" x="1864.6077" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1644.9026,-1013.3851C1645.8017,-999.42 1646.6945,-985.552 1647.568,-971.9838"/>
<polygon fill="#000000" stroke="#000000" points="1651.0822,-971.8742 1648.2319,-961.6699 1644.0966,-971.4244 1651.0822,-971.8742"/>
<text text-anchor="middle" x="1712.1077" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1489.3504,-697.9709C1427.6642,-664.3586 1356.1985,-629.6163 1287.6077,-606 1250.3888,-593.1853 1209.3155,-581.6653 1171.2442,-572.0285"/>
<polygon fill="#000000" stroke="#000000" points="1171.6655,-568.5259 1161.1147,-569.4905 1169.9642,-575.316 1171.6655,-568.5259"/>
<text text-anchor="middle" x="1355.1077" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge11" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1684.4093,-639.1986C1702.6202,-500.6415 1716.3576,-314.6711 1669.6077,-259 1586.1978,-159.6732 1237.1231,-123.9806 1003.6598,-111.1653"/>
<polygon fill="#000000" stroke="#000000" points="1003.8463,-107.6704 993.6724,-110.6272 1003.4695,-114.6603 1003.8463,-107.6704"/>
<text text-anchor="middle" x="1736.1077" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- diagnosis -->
<g id="node13" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M842.1077,-651C842.1077,-651 1225.1077,-651 1225.1077,-651 1231.1077,-651 1237.1077,-657 1237.1077,-663 1237.1077,-663 1237.1077,-938 1237.1077,-938 1237.1077,-944 1231.1077,-950 1225.1077,-950 1225.1077,-950 842.1077,-950 842.1077,-950 836.1077,-950 830.1077,-944 830.1077,-938 830.1077,-938 830.1077,-663 830.1077,-663 830.1077,-657 836.1077,-651 842.1077,-651"/>
<text text-anchor="middle" x="872.1077" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="914.1077,-651 914.1077,-950 "/>
<text text-anchor="middle" x="924.6077" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="935.1077,-651 935.1077,-950 "/>
<text text-anchor="middle" x="1075.6077" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="935.1077,-927 1216.1077,-927 "/>
<text text-anchor="middle" x="1075.6077" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="935.1077,-904 1216.1077,-904 "/>
<text text-anchor="middle" x="1075.6077" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="935.1077,-881 1216.1077,-881 "/>
<text text-anchor="middle" x="1075.6077" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="935.1077,-858 1216.1077,-858 "/>
<text text-anchor="middle" x="1075.6077" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="935.1077,-835 1216.1077,-835 "/>
<text text-anchor="middle" x="1075.6077" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="935.1077,-812 1216.1077,-812 "/>
<text text-anchor="middle" x="1075.6077" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="935.1077,-789 1216.1077,-789 "/>
<text text-anchor="middle" x="1075.6077" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="935.1077,-766 1216.1077,-766 "/>
<text text-anchor="middle" x="1075.6077" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis_reference_source</text>
<polyline fill="none" stroke="#000000" points="935.1077,-743 1216.1077,-743 "/>
<text text-anchor="middle" x="1075.6077" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="935.1077,-720 1216.1077,-720 "/>
<text text-anchor="middle" x="1075.6077" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="935.1077,-697 1216.1077,-697 "/>
<text text-anchor="middle" x="1075.6077" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="935.1077,-674 1216.1077,-674 "/>
<text text-anchor="middle" x="1075.6077" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="1216.1077,-651 1216.1077,-950 "/>
<text text-anchor="middle" x="1226.6077" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1033.6077,-650.9639C1033.6077,-632.1028 1033.6077,-613.8228 1033.6077,-597.7769"/>
<polygon fill="#000000" stroke="#000000" points="1037.1078,-597.5713 1033.6077,-587.5714 1030.1078,-597.5714 1037.1078,-597.5713"/>
<text text-anchor="middle" x="1078.1077" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- study_funding -->
<g id="node14" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M1729.1077,-317C1729.1077,-317 2108.1077,-317 2108.1077,-317 2114.1077,-317 2120.1077,-323 2120.1077,-329 2120.1077,-329 2120.1077,-374 2120.1077,-374 2120.1077,-380 2114.1077,-386 2108.1077,-386 2108.1077,-386 1729.1077,-386 1729.1077,-386 1723.1077,-386 1717.1077,-380 1717.1077,-374 1717.1077,-374 1717.1077,-329 1717.1077,-329 1717.1077,-323 1723.1077,-317 1729.1077,-317"/>
<text text-anchor="middle" x="1776.6077" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="1836.1077,-317 1836.1077,-386 "/>
<text text-anchor="middle" x="1846.6077" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1857.1077,-317 1857.1077,-386 "/>
<text text-anchor="middle" x="1978.1077" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="1857.1077,-363 2099.1077,-363 "/>
<text text-anchor="middle" x="1978.1077" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="1857.1077,-340 2099.1077,-340 "/>
<text text-anchor="middle" x="1978.1077" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="2099.1077,-317 2099.1077,-386 "/>
<text text-anchor="middle" x="2109.6077" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge13" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1871.5116,-316.749C1829.439,-287.5685 1764.9867,-247.3229 1702.6077,-226 1577.331,-183.1768 1232.85,-144.8611 1003.8839,-123.0404"/>
<polygon fill="#000000" stroke="#000000" points="1004.0362,-119.5392 993.7501,-122.0782 1003.3744,-126.5079 1004.0362,-119.5392"/>
<text text-anchor="middle" x="1801.6077" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- imaging_file -->
<g id="node15" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M1905.1077,-1105.5C1905.1077,-1105.5 2194.1077,-1105.5 2194.1077,-1105.5 2200.1077,-1105.5 2206.1077,-1111.5 2206.1077,-1117.5 2206.1077,-1117.5 2206.1077,-1415.5 2206.1077,-1415.5 2206.1077,-1421.5 2200.1077,-1427.5 2194.1077,-1427.5 2194.1077,-1427.5 1905.1077,-1427.5 1905.1077,-1427.5 1899.1077,-1427.5 1893.1077,-1421.5 1893.1077,-1415.5 1893.1077,-1415.5 1893.1077,-1117.5 1893.1077,-1117.5 1893.1077,-1111.5 1899.1077,-1105.5 1905.1077,-1105.5"/>
<text text-anchor="middle" x="1945.1077" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="1997.1077,-1105.5 1997.1077,-1427.5 "/>
<text text-anchor="middle" x="2007.6077" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2018.1077,-1105.5 2018.1077,-1427.5 "/>
<text text-anchor="middle" x="2101.6077" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2018.1077,-1404.5 2185.1077,-1404.5 "/>
<text text-anchor="middle" x="2101.6077" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2018.1077,-1381.5 2185.1077,-1381.5 "/>
<text text-anchor="middle" x="2101.6077" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2018.1077,-1358.5 2185.1077,-1358.5 "/>
<text text-anchor="middle" x="2101.6077" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2018.1077,-1335.5 2185.1077,-1335.5 "/>
<text text-anchor="middle" x="2101.6077" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2018.1077,-1312.5 2185.1077,-1312.5 "/>
<text text-anchor="middle" x="2101.6077" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2018.1077,-1289.5 2185.1077,-1289.5 "/>
<text text-anchor="middle" x="2101.6077" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2018.1077,-1266.5 2185.1077,-1266.5 "/>
<text text-anchor="middle" x="2101.6077" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2018.1077,-1243.5 2185.1077,-1243.5 "/>
<text text-anchor="middle" x="2101.6077" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2018.1077,-1220.5 2185.1077,-1220.5 "/>
<text text-anchor="middle" x="2101.6077" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="2018.1077,-1197.5 2185.1077,-1197.5 "/>
<text text-anchor="middle" x="2101.6077" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="2018.1077,-1174.5 2185.1077,-1174.5 "/>
<text text-anchor="middle" x="2101.6077" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="2018.1077,-1151.5 2185.1077,-1151.5 "/>
<text text-anchor="middle" x="2101.6077" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2018.1077,-1128.5 2185.1077,-1128.5 "/>
<text text-anchor="middle" x="2101.6077" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="2185.1077,-1105.5 2185.1077,-1427.5 "/>
<text text-anchor="middle" x="2195.6077" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1953.1202,-1105.4854C1931.873,-1073.8318 1908.5289,-1041.5978 1884.6077,-1013 1869.2633,-994.6558 1852.4422,-976.2818 1835.1182,-958.4402"/>
<polygon fill="#000000" stroke="#000000" points="1837.1625,-955.5251 1827.6658,-950.828 1832.1605,-960.4222 1837.1625,-955.5251"/>
<text text-anchor="middle" x="1922.1077" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
</g>
</svg>
</div>
