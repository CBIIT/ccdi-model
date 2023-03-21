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
<svg width="5819pt" height="1988pt"
 viewBox="0.00 0.00 5819.00 1988.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1984)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1984 5815,-1984 5815,4 -4,4"/>
<!-- study_arm -->
<g id="node1" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M3578,-386C3578,-386 3875,-386 3875,-386 3881,-386 3887,-392 3887,-398 3887,-398 3887,-466 3887,-466 3887,-472 3881,-478 3875,-478 3875,-478 3578,-478 3578,-478 3572,-478 3566,-472 3566,-466 3566,-466 3566,-398 3566,-398 3566,-392 3572,-386 3578,-386"/>
<text text-anchor="middle" x="3612" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="3658,-386 3658,-478 "/>
<text text-anchor="middle" x="3668.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3679,-386 3679,-478 "/>
<text text-anchor="middle" x="3772.5" y="-462.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="3679,-455 3866,-455 "/>
<text text-anchor="middle" x="3772.5" y="-439.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="3679,-432 3866,-432 "/>
<text text-anchor="middle" x="3772.5" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="3679,-409 3866,-409 "/>
<text text-anchor="middle" x="3772.5" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm_id</text>
<polyline fill="none" stroke="#000000" points="3866,-386 3866,-478 "/>
<text text-anchor="middle" x="3876.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node11" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M4191.5,-.5C4191.5,-.5 4581.5,-.5 4581.5,-.5 4587.5,-.5 4593.5,-6.5 4593.5,-12.5 4593.5,-12.5 4593.5,-287.5 4593.5,-287.5 4593.5,-293.5 4587.5,-299.5 4581.5,-299.5 4581.5,-299.5 4191.5,-299.5 4191.5,-299.5 4185.5,-299.5 4179.5,-293.5 4179.5,-287.5 4179.5,-287.5 4179.5,-12.5 4179.5,-12.5 4179.5,-6.5 4185.5,-.5 4191.5,-.5"/>
<text text-anchor="middle" x="4207.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="4235.5,-.5 4235.5,-299.5 "/>
<text text-anchor="middle" x="4246" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4256.5,-.5 4256.5,-299.5 "/>
<text text-anchor="middle" x="4414.5" y="-284.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="4256.5,-276.5 4572.5,-276.5 "/>
<text text-anchor="middle" x="4414.5" y="-261.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="4256.5,-253.5 4572.5,-253.5 "/>
<text text-anchor="middle" x="4414.5" y="-238.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_shorthand</text>
<polyline fill="none" stroke="#000000" points="4256.5,-230.5 4572.5,-230.5 "/>
<text text-anchor="middle" x="4414.5" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="4256.5,-207.5 4572.5,-207.5 "/>
<text text-anchor="middle" x="4414.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="4256.5,-184.5 4572.5,-184.5 "/>
<text text-anchor="middle" x="4414.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="4256.5,-161.5 4572.5,-161.5 "/>
<text text-anchor="middle" x="4414.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="4256.5,-138.5 4572.5,-138.5 "/>
<text text-anchor="middle" x="4414.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="4256.5,-115.5 4572.5,-115.5 "/>
<text text-anchor="middle" x="4414.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="4256.5,-92.5 4572.5,-92.5 "/>
<text text-anchor="middle" x="4414.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="4256.5,-69.5 4572.5,-69.5 "/>
<text text-anchor="middle" x="4414.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="4256.5,-46.5 4572.5,-46.5 "/>
<text text-anchor="middle" x="4414.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="4256.5,-23.5 4572.5,-23.5 "/>
<text text-anchor="middle" x="4414.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="4572.5,-.5 4572.5,-299.5 "/>
<text text-anchor="middle" x="4583" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge27" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3834.3777,-385.9068C3925.0287,-347.1741 4057.4189,-290.6074 4169.8358,-242.5747"/>
<polygon fill="#000000" stroke="#000000" points="4171.4475,-245.6922 4179.2681,-238.5446 4168.6971,-239.2552 4171.4475,-245.6922"/>
<text text-anchor="middle" x="4027" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- pdx -->
<g id="node2" class="node">
<title>pdx</title>
<path fill="none" stroke="#000000" d="M1040,-1565.5C1040,-1565.5 1369,-1565.5 1369,-1565.5 1375,-1565.5 1381,-1571.5 1381,-1577.5 1381,-1577.5 1381,-1783.5 1381,-1783.5 1381,-1789.5 1375,-1795.5 1369,-1795.5 1369,-1795.5 1040,-1795.5 1040,-1795.5 1034,-1795.5 1028,-1789.5 1028,-1783.5 1028,-1783.5 1028,-1577.5 1028,-1577.5 1028,-1571.5 1034,-1565.5 1040,-1565.5"/>
<text text-anchor="middle" x="1049.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
<polyline fill="none" stroke="#000000" points="1071,-1565.5 1071,-1795.5 "/>
<text text-anchor="middle" x="1081.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1092,-1565.5 1092,-1795.5 "/>
<text text-anchor="middle" x="1226" y="-1780.3" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_site</text>
<polyline fill="none" stroke="#000000" points="1092,-1772.5 1360,-1772.5 "/>
<text text-anchor="middle" x="1226" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_type</text>
<polyline fill="none" stroke="#000000" points="1092,-1749.5 1360,-1749.5 "/>
<text text-anchor="middle" x="1226" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_id</text>
<polyline fill="none" stroke="#000000" points="1092,-1726.5 1360,-1726.5 "/>
<text text-anchor="middle" x="1226" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">mouse_strain</text>
<polyline fill="none" stroke="#000000" points="1092,-1703.5 1360,-1703.5 "/>
<text text-anchor="middle" x="1226" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx_id</text>
<polyline fill="none" stroke="#000000" points="1092,-1680.5 1360,-1680.5 "/>
<text text-anchor="middle" x="1226" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">strain_immune_system_humanized</text>
<polyline fill="none" stroke="#000000" points="1092,-1657.5 1360,-1657.5 "/>
<text text-anchor="middle" x="1226" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_characterization_method</text>
<polyline fill="none" stroke="#000000" points="1092,-1634.5 1360,-1634.5 "/>
<text text-anchor="middle" x="1226" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_not_mus_or_ebv_origin</text>
<polyline fill="none" stroke="#000000" points="1092,-1611.5 1360,-1611.5 "/>
<text text-anchor="middle" x="1226" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_preparation</text>
<polyline fill="none" stroke="#000000" points="1092,-1588.5 1360,-1588.5 "/>
<text text-anchor="middle" x="1226" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_humanization</text>
<polyline fill="none" stroke="#000000" points="1360,-1565.5 1360,-1795.5 "/>
<text text-anchor="middle" x="1370.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node10" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1249.5,-950C1249.5,-950 1563.5,-950 1563.5,-950 1569.5,-950 1575.5,-956 1575.5,-962 1575.5,-962 1575.5,-1099 1575.5,-1099 1575.5,-1105 1569.5,-1111 1563.5,-1111 1563.5,-1111 1249.5,-1111 1249.5,-1111 1243.5,-1111 1237.5,-1105 1237.5,-1099 1237.5,-1099 1237.5,-962 1237.5,-962 1237.5,-956 1243.5,-950 1249.5,-950"/>
<text text-anchor="middle" x="1271.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1305.5,-950 1305.5,-1111 "/>
<text text-anchor="middle" x="1316" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1326.5,-950 1326.5,-1111 "/>
<text text-anchor="middle" x="1440.5" y="-1095.8" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="1326.5,-1088 1554.5,-1088 "/>
<text text-anchor="middle" x="1440.5" y="-1072.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1326.5,-1065 1554.5,-1065 "/>
<text text-anchor="middle" x="1440.5" y="-1049.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1326.5,-1042 1554.5,-1042 "/>
<text text-anchor="middle" x="1440.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1326.5,-1019 1554.5,-1019 "/>
<text text-anchor="middle" x="1440.5" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1326.5,-996 1554.5,-996 "/>
<text text-anchor="middle" x="1440.5" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1326.5,-973 1554.5,-973 "/>
<text text-anchor="middle" x="1440.5" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="1554.5,-950 1554.5,-1111 "/>
<text text-anchor="middle" x="1565" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1240.2646,-1565.4159C1279.723,-1438.4457 1342.3999,-1236.7628 1378.4626,-1120.7195"/>
<polygon fill="#000000" stroke="#000000" points="1381.8144,-1121.7275 1381.4398,-1111.1393 1375.1297,-1119.6501 1381.8144,-1121.7275"/>
<text text-anchor="middle" x="1329.5" y="-1351.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- medical_history -->
<g id="node3" class="node">
<title>medical_history</title>
<path fill="none" stroke="#000000" d="M3316.5,-996C3316.5,-996 3670.5,-996 3670.5,-996 3676.5,-996 3682.5,-1002 3682.5,-1008 3682.5,-1008 3682.5,-1053 3682.5,-1053 3682.5,-1059 3676.5,-1065 3670.5,-1065 3670.5,-1065 3316.5,-1065 3316.5,-1065 3310.5,-1065 3304.5,-1059 3304.5,-1053 3304.5,-1053 3304.5,-1008 3304.5,-1008 3304.5,-1002 3310.5,-996 3316.5,-996"/>
<text text-anchor="middle" x="3370" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
<polyline fill="none" stroke="#000000" points="3435.5,-996 3435.5,-1065 "/>
<text text-anchor="middle" x="3446" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3456.5,-996 3456.5,-1065 "/>
<text text-anchor="middle" x="3559" y="-1049.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_category</text>
<polyline fill="none" stroke="#000000" points="3456.5,-1042 3661.5,-1042 "/>
<text text-anchor="middle" x="3559" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_condition</text>
<polyline fill="none" stroke="#000000" points="3456.5,-1019 3661.5,-1019 "/>
<text text-anchor="middle" x="3559" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_id</text>
<polyline fill="none" stroke="#000000" points="3661.5,-996 3661.5,-1065 "/>
<text text-anchor="middle" x="3672" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node7" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M3026.5,-564.5C3026.5,-564.5 3330.5,-564.5 3330.5,-564.5 3336.5,-564.5 3342.5,-570.5 3342.5,-576.5 3342.5,-576.5 3342.5,-667.5 3342.5,-667.5 3342.5,-673.5 3336.5,-679.5 3330.5,-679.5 3330.5,-679.5 3026.5,-679.5 3026.5,-679.5 3020.5,-679.5 3014.5,-673.5 3014.5,-667.5 3014.5,-667.5 3014.5,-576.5 3014.5,-576.5 3014.5,-570.5 3020.5,-564.5 3026.5,-564.5"/>
<text text-anchor="middle" x="3062.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="3110.5,-564.5 3110.5,-679.5 "/>
<text text-anchor="middle" x="3121" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3131.5,-564.5 3131.5,-679.5 "/>
<text text-anchor="middle" x="3226.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="3131.5,-656.5 3321.5,-656.5 "/>
<text text-anchor="middle" x="3226.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="3131.5,-633.5 3321.5,-633.5 "/>
<text text-anchor="middle" x="3226.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="3131.5,-610.5 3321.5,-610.5 "/>
<text text-anchor="middle" x="3226.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="3131.5,-587.5 3321.5,-587.5 "/>
<text text-anchor="middle" x="3226.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="3321.5,-564.5 3321.5,-679.5 "/>
<text text-anchor="middle" x="3332" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3483.7325,-995.8793C3463.7056,-930.3177 3412.3272,-786.684 3324.5,-698 3320.3135,-693.7726 3315.8422,-689.7302 3311.1603,-685.8706"/>
<polygon fill="#000000" stroke="#000000" points="3313.1242,-682.9629 3303.095,-679.5473 3308.8052,-688.4717 3313.1242,-682.9629"/>
<text text-anchor="middle" x="3406.5" y="-701.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- methylation_array_file -->
<g id="node4" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M1411,-1554C1411,-1554 1806,-1554 1806,-1554 1812,-1554 1818,-1560 1818,-1566 1818,-1566 1818,-1795 1818,-1795 1818,-1801 1812,-1807 1806,-1807 1806,-1807 1411,-1807 1411,-1807 1405,-1807 1399,-1801 1399,-1795 1399,-1795 1399,-1566 1399,-1566 1399,-1560 1405,-1554 1411,-1554"/>
<text text-anchor="middle" x="1488" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="1577,-1554 1577,-1807 "/>
<text text-anchor="middle" x="1587.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1598,-1554 1598,-1807 "/>
<text text-anchor="middle" x="1697.5" y="-1791.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1598,-1784 1797,-1784 "/>
<text text-anchor="middle" x="1697.5" y="-1768.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1598,-1761 1797,-1761 "/>
<text text-anchor="middle" x="1697.5" y="-1745.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1598,-1738 1797,-1738 "/>
<text text-anchor="middle" x="1697.5" y="-1722.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1598,-1715 1797,-1715 "/>
<text text-anchor="middle" x="1697.5" y="-1699.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1598,-1692 1797,-1692 "/>
<text text-anchor="middle" x="1697.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1598,-1669 1797,-1669 "/>
<text text-anchor="middle" x="1697.5" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1598,-1646 1797,-1646 "/>
<text text-anchor="middle" x="1697.5" y="-1630.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1598,-1623 1797,-1623 "/>
<text text-anchor="middle" x="1697.5" y="-1607.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file_id</text>
<polyline fill="none" stroke="#000000" points="1598,-1600 1797,-1600 "/>
<text text-anchor="middle" x="1697.5" y="-1584.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="1598,-1577 1797,-1577 "/>
<text text-anchor="middle" x="1697.5" y="-1561.8" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="1797,-1554 1797,-1807 "/>
<text text-anchor="middle" x="1807.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1569.0728,-1553.6304C1529.5233,-1426.3672 1469.605,-1233.5608 1434.6263,-1121.0053"/>
<polygon fill="#000000" stroke="#000000" points="1437.9426,-1119.8826 1431.6325,-1111.3718 1431.2579,-1121.9601 1437.9426,-1119.8826"/>
<text text-anchor="middle" x="1599" y="-1351.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- sequencing_file -->
<g id="node5" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M1848,-1381.5C1848,-1381.5 2317,-1381.5 2317,-1381.5 2323,-1381.5 2329,-1387.5 2329,-1393.5 2329,-1393.5 2329,-1967.5 2329,-1967.5 2329,-1973.5 2323,-1979.5 2317,-1979.5 2317,-1979.5 1848,-1979.5 1848,-1979.5 1842,-1979.5 1836,-1973.5 1836,-1967.5 1836,-1967.5 1836,-1393.5 1836,-1393.5 1836,-1387.5 1842,-1381.5 1848,-1381.5"/>
<text text-anchor="middle" x="1900" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="1964,-1381.5 1964,-1979.5 "/>
<text text-anchor="middle" x="1974.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1985,-1381.5 1985,-1979.5 "/>
<text text-anchor="middle" x="2146.5" y="-1964.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="1985,-1956.5 2308,-1956.5 "/>
<text text-anchor="middle" x="2146.5" y="-1941.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1985,-1933.5 2308,-1933.5 "/>
<text text-anchor="middle" x="2146.5" y="-1918.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1985,-1910.5 2308,-1910.5 "/>
<text text-anchor="middle" x="2146.5" y="-1895.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="1985,-1887.5 2308,-1887.5 "/>
<text text-anchor="middle" x="2146.5" y="-1872.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="1985,-1864.5 2308,-1864.5 "/>
<text text-anchor="middle" x="2146.5" y="-1849.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1985,-1841.5 2308,-1841.5 "/>
<text text-anchor="middle" x="2146.5" y="-1826.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="1985,-1818.5 2308,-1818.5 "/>
<text text-anchor="middle" x="2146.5" y="-1803.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1985,-1795.5 2308,-1795.5 "/>
<text text-anchor="middle" x="2146.5" y="-1780.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1985,-1772.5 2308,-1772.5 "/>
<text text-anchor="middle" x="2146.5" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1985,-1749.5 2308,-1749.5 "/>
<text text-anchor="middle" x="2146.5" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1985,-1726.5 2308,-1726.5 "/>
<text text-anchor="middle" x="2146.5" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1985,-1703.5 2308,-1703.5 "/>
<text text-anchor="middle" x="2146.5" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1985,-1680.5 2308,-1680.5 "/>
<text text-anchor="middle" x="2146.5" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="1985,-1657.5 2308,-1657.5 "/>
<text text-anchor="middle" x="2146.5" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="1985,-1634.5 2308,-1634.5 "/>
<text text-anchor="middle" x="2146.5" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="1985,-1611.5 2308,-1611.5 "/>
<text text-anchor="middle" x="2146.5" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="1985,-1588.5 2308,-1588.5 "/>
<text text-anchor="middle" x="2146.5" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="1985,-1565.5 2308,-1565.5 "/>
<text text-anchor="middle" x="2146.5" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="1985,-1542.5 2308,-1542.5 "/>
<text text-anchor="middle" x="2146.5" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1985,-1519.5 2308,-1519.5 "/>
<text text-anchor="middle" x="2146.5" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="1985,-1496.5 2308,-1496.5 "/>
<text text-anchor="middle" x="2146.5" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="1985,-1473.5 2308,-1473.5 "/>
<text text-anchor="middle" x="2146.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="1985,-1450.5 2308,-1450.5 "/>
<text text-anchor="middle" x="2146.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="1985,-1427.5 2308,-1427.5 "/>
<text text-anchor="middle" x="2146.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="1985,-1404.5 2308,-1404.5 "/>
<text text-anchor="middle" x="2146.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 1 properties</text>
<polyline fill="none" stroke="#000000" points="2308,-1381.5 2308,-1979.5 "/>
<text text-anchor="middle" x="2318.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1835.6072,-1386.8128C1832.5895,-1384.8286 1829.5535,-1382.8901 1826.5,-1381 1775.0812,-1349.1725 1753.7233,-1360.2266 1694.5,-1348 1645.984,-1337.9839 1625.4317,-1357.9056 1584.5,-1330 1511.3509,-1280.1298 1463.6604,-1189.3823 1436.2287,-1120.802"/>
<polygon fill="#000000" stroke="#000000" points="1439.4028,-1119.3093 1432.4918,-1111.2787 1432.8865,-1121.8662 1439.4028,-1119.3093"/>
<text text-anchor="middle" x="1856" y="-1351.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- synonym -->
<g id="node6" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M3790,-1657.5C3790,-1657.5 4091,-1657.5 4091,-1657.5 4097,-1657.5 4103,-1663.5 4103,-1669.5 4103,-1669.5 4103,-1691.5 4103,-1691.5 4103,-1697.5 4097,-1703.5 4091,-1703.5 4091,-1703.5 3790,-1703.5 3790,-1703.5 3784,-1703.5 3778,-1697.5 3778,-1691.5 3778,-1691.5 3778,-1669.5 3778,-1669.5 3778,-1663.5 3784,-1657.5 3790,-1657.5"/>
<text text-anchor="middle" x="3818" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="3858,-1657.5 3858,-1703.5 "/>
<text text-anchor="middle" x="3868.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3879,-1657.5 3879,-1703.5 "/>
<text text-anchor="middle" x="3980.5" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="3879,-1680.5 4082,-1680.5 "/>
<text text-anchor="middle" x="3980.5" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="4082,-1657.5 4082,-1703.5 "/>
<text text-anchor="middle" x="4092.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3941.3544,-1657.1345C3946.2179,-1517.9731 3968.018,-802.0001 3904.5,-731 3868.1475,-690.3654 3556.0411,-655.3542 3353.0515,-636.6031"/>
<polygon fill="#000000" stroke="#000000" points="3353.1444,-633.097 3342.8662,-635.6674 3352.504,-640.0676 3353.1444,-633.097"/>
<text text-anchor="middle" x="3992" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3934.1323,-1657.0873C3916.7172,-1598.1893 3862.1828,-1444.0834 3753.5,-1381 3591.5494,-1286.9981 3098.6897,-1352.937 2911.5,-1348 2874.6483,-1347.0281 1616.417,-1348.447 1584.5,-1330 1506.8496,-1285.1205 1459.4352,-1191.7547 1433.281,-1121.1253"/>
<polygon fill="#000000" stroke="#000000" points="1436.4255,-1119.5291 1429.7307,-1111.3175 1429.8435,-1121.9118 1436.4255,-1119.5291"/>
<text text-anchor="middle" x="3752" y="-1351.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge17" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M4008.8366,-1657.4146C4124.5276,-1614.1634 4355.5362,-1508.7907 4449.5,-1330 4614.7036,-1015.6568 4647.4354,-825.8313 4449.5,-531 4437.7231,-513.4579 4417.7315,-530.2282 4405.5,-513 4364.4117,-455.1267 4355.759,-378.0412 4358.9723,-309.7948"/>
<polygon fill="#000000" stroke="#000000" points="4362.4678,-309.9725 4359.5301,-299.7931 4355.4786,-309.5827 4362.4678,-309.9725"/>
<text text-anchor="middle" x="4576" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge20" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M3342.5468,-565.1225C3419.3492,-538.4939 3509.9692,-507.0745 3583.88,-481.4485"/>
<polygon fill="#000000" stroke="#000000" points="3585.4298,-484.6157 3593.7315,-478.0329 3583.1367,-478.0019 3585.4298,-484.6157"/>
<text text-anchor="middle" x="3487" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge21" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3220.8907,-564.4022C3270.1382,-501.8531 3357.2955,-403.8287 3455.5,-351 3680.2201,-230.1127 3972.3134,-181.9302 4168.8985,-162.7262"/>
<polygon fill="#000000" stroke="#000000" points="4169.4452,-166.1899 4179.0651,-161.7505 4168.7764,-159.2219 4169.4452,-166.1899"/>
<text text-anchor="middle" x="3506" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- publication -->
<g id="node8" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M4427,-409C4427,-409 4660,-409 4660,-409 4666,-409 4672,-415 4672,-421 4672,-421 4672,-443 4672,-443 4672,-449 4666,-455 4660,-455 4660,-455 4427,-455 4427,-455 4421,-455 4415,-449 4415,-443 4415,-443 4415,-421 4415,-421 4415,-415 4421,-409 4427,-409"/>
<text text-anchor="middle" x="4463.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="4512,-409 4512,-455 "/>
<text text-anchor="middle" x="4522.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4533,-409 4533,-455 "/>
<text text-anchor="middle" x="4592" y="-439.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication_id</text>
<polyline fill="none" stroke="#000000" points="4533,-432 4651,-432 "/>
<text text-anchor="middle" x="4592" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="4651,-409 4651,-455 "/>
<text text-anchor="middle" x="4661.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge7" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M4530.652,-408.9228C4517.8179,-385.8704 4496.8815,-348.2649 4474.8928,-308.7692"/>
<polygon fill="#000000" stroke="#000000" points="4477.8112,-306.8158 4469.8888,-299.7811 4471.6951,-310.2208 4477.8112,-306.8158"/>
<text text-anchor="middle" x="4539.5" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- follow_up -->
<g id="node9" class="node">
<title>follow_up</title>
<path fill="none" stroke="#000000" d="M844,-927C844,-927 1207,-927 1207,-927 1213,-927 1219,-933 1219,-939 1219,-939 1219,-1122 1219,-1122 1219,-1128 1213,-1134 1207,-1134 1207,-1134 844,-1134 844,-1134 838,-1134 832,-1128 832,-1122 832,-1122 832,-939 832,-939 832,-933 838,-927 844,-927"/>
<text text-anchor="middle" x="874.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
<polyline fill="none" stroke="#000000" points="917,-927 917,-1134 "/>
<text text-anchor="middle" x="927.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="938,-927 938,-1134 "/>
<text text-anchor="middle" x="1068" y="-1118.8" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event</text>
<polyline fill="none" stroke="#000000" points="938,-1111 1198,-1111 "/>
<text text-anchor="middle" x="1068" y="-1095.8" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity</text>
<polyline fill="none" stroke="#000000" points="938,-1088 1198,-1088 "/>
<text text-anchor="middle" x="1068" y="-1072.8" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity_method_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="938,-1065 1198,-1065 "/>
<text text-anchor="middle" x="1068" y="-1049.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_follow_up</text>
<polyline fill="none" stroke="#000000" points="938,-1042 1198,-1042 "/>
<text text-anchor="middle" x="1068" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_response</text>
<polyline fill="none" stroke="#000000" points="938,-1019 1198,-1019 "/>
<text text-anchor="middle" x="1068" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_category</text>
<polyline fill="none" stroke="#000000" points="938,-996 1198,-996 "/>
<text text-anchor="middle" x="1068" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_id</text>
<polyline fill="none" stroke="#000000" points="938,-973 1198,-973 "/>
<text text-anchor="middle" x="1068" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_other</text>
<polyline fill="none" stroke="#000000" points="938,-950 1198,-950 "/>
<text text-anchor="middle" x="1068" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">risk_factor</text>
<polyline fill="none" stroke="#000000" points="1198,-927 1198,-1134 "/>
<text text-anchor="middle" x="1208.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1067.5204,-926.9722C1100.7202,-859.3258 1153.954,-775.5462 1228.5,-731 1304.0508,-685.8534 2540.0773,-642.2297 3004.2209,-627.3634"/>
<polygon fill="#000000" stroke="#000000" points="3004.4847,-630.8569 3014.3677,-627.039 3004.261,-623.8604 3004.4847,-630.8569"/>
<text text-anchor="middle" x="1512.5" y="-701.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1430.8495,-949.8937C1456.7696,-879.2711 1505.1813,-780.4142 1584.5,-731 1702.6404,-657.4006 2615.4417,-632.206 3004.1475,-624.757"/>
<polygon fill="#000000" stroke="#000000" points="3004.4312,-628.2524 3014.3629,-624.5631 3004.2982,-621.2536 3004.4312,-628.2524"/>
<text text-anchor="middle" x="1727" y="-701.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge13" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1384.3845,-949.8432C1369.2715,-875.4108 1361.3287,-766.3716 1420.5,-698 1965.9437,-67.7472 2443.7038,-501.538 3263.5,-351 3578.3026,-293.1932 3943.1489,-228.275 4169.4218,-188.2573"/>
<polygon fill="#000000" stroke="#000000" points="4170.183,-191.6771 4179.4208,-186.4892 4168.964,-184.7841 4170.183,-191.6771"/>
<text text-anchor="middle" x="1620" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample_diagnosis -->
<g id="node12" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M2359,-1542.5C2359,-1542.5 2792,-1542.5 2792,-1542.5 2798,-1542.5 2804,-1548.5 2804,-1554.5 2804,-1554.5 2804,-1806.5 2804,-1806.5 2804,-1812.5 2798,-1818.5 2792,-1818.5 2792,-1818.5 2359,-1818.5 2359,-1818.5 2353,-1818.5 2347,-1812.5 2347,-1806.5 2347,-1806.5 2347,-1554.5 2347,-1554.5 2347,-1548.5 2353,-1542.5 2359,-1542.5"/>
<text text-anchor="middle" x="2418.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2490,-1542.5 2490,-1818.5 "/>
<text text-anchor="middle" x="2500.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2511,-1542.5 2511,-1818.5 "/>
<text text-anchor="middle" x="2647" y="-1803.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="2511,-1795.5 2783,-1795.5 "/>
<text text-anchor="middle" x="2647" y="-1780.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2511,-1772.5 2783,-1772.5 "/>
<text text-anchor="middle" x="2647" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="2511,-1749.5 2783,-1749.5 "/>
<text text-anchor="middle" x="2647" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="2511,-1726.5 2783,-1726.5 "/>
<text text-anchor="middle" x="2647" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="2511,-1703.5 2783,-1703.5 "/>
<text text-anchor="middle" x="2647" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2511,-1680.5 2783,-1680.5 "/>
<text text-anchor="middle" x="2647" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="2511,-1657.5 2783,-1657.5 "/>
<text text-anchor="middle" x="2647" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="2511,-1634.5 2783,-1634.5 "/>
<text text-anchor="middle" x="2647" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="2511,-1611.5 2783,-1611.5 "/>
<text text-anchor="middle" x="2647" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="2511,-1588.5 2783,-1588.5 "/>
<text text-anchor="middle" x="2647" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="2511,-1565.5 2783,-1565.5 "/>
<text text-anchor="middle" x="2647" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="2783,-1542.5 2783,-1818.5 "/>
<text text-anchor="middle" x="2793.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2500.813,-1542.267C2460.7266,-1482.13 2405.4862,-1417.2386 2337.5,-1381 2175.7844,-1294.8008 2109.3513,-1360.1503 1926.5,-1348 1888.5311,-1345.477 1617.068,-1349.6807 1584.5,-1330 1507.9871,-1283.7636 1460.4911,-1191.0864 1434.01,-1121.0038"/>
<polygon fill="#000000" stroke="#000000" points="1437.1626,-1119.4378 1430.412,-1111.272 1430.597,-1121.8652 1437.1626,-1119.4378"/>
<text text-anchor="middle" x="2366.5" y="-1351.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
<!-- molecular_test -->
<g id="node13" class="node">
<title>molecular_test</title>
<path fill="none" stroke="#000000" d="M1605.5,-731.5C1605.5,-731.5 1993.5,-731.5 1993.5,-731.5 1999.5,-731.5 2005.5,-737.5 2005.5,-743.5 2005.5,-743.5 2005.5,-1317.5 2005.5,-1317.5 2005.5,-1323.5 1999.5,-1329.5 1993.5,-1329.5 1993.5,-1329.5 1605.5,-1329.5 1605.5,-1329.5 1599.5,-1329.5 1593.5,-1323.5 1593.5,-1317.5 1593.5,-1317.5 1593.5,-743.5 1593.5,-743.5 1593.5,-737.5 1599.5,-731.5 1605.5,-731.5"/>
<text text-anchor="middle" x="1655" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
<polyline fill="none" stroke="#000000" points="1716.5,-731.5 1716.5,-1329.5 "/>
<text text-anchor="middle" x="1727" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1737.5,-731.5 1737.5,-1329.5 "/>
<text text-anchor="middle" x="1861" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">aa_change</text>
<polyline fill="none" stroke="#000000" points="1737.5,-1306.5 1984.5,-1306.5 "/>
<text text-anchor="middle" x="1861" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">antigen</text>
<polyline fill="none" stroke="#000000" points="1737.5,-1283.5 1984.5,-1283.5 "/>
<text text-anchor="middle" x="1861" y="-1268.3" font-family="Times,serif" font-size="14.00" fill="#000000">biospecimen_type</text>
<polyline fill="none" stroke="#000000" points="1737.5,-1260.5 1984.5,-1260.5 "/>
<text text-anchor="middle" x="1861" y="-1245.3" font-family="Times,serif" font-size="14.00" fill="#000000">blood_test_normal_range_lower</text>
<polyline fill="none" stroke="#000000" points="1737.5,-1237.5 1984.5,-1237.5 "/>
<text text-anchor="middle" x="1861" y="-1222.3" font-family="Times,serif" font-size="14.00" fill="#000000">blood_test_normal_range_upper</text>
<polyline fill="none" stroke="#000000" points="1737.5,-1214.5 1984.5,-1214.5 "/>
<text text-anchor="middle" x="1861" y="-1199.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_count</text>
<polyline fill="none" stroke="#000000" points="1737.5,-1191.5 1984.5,-1191.5 "/>
<text text-anchor="middle" x="1861" y="-1176.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome</text>
<polyline fill="none" stroke="#000000" points="1737.5,-1168.5 1984.5,-1168.5 "/>
<text text-anchor="middle" x="1861" y="-1153.3" font-family="Times,serif" font-size="14.00" fill="#000000">copy_number</text>
<polyline fill="none" stroke="#000000" points="1737.5,-1145.5 1984.5,-1145.5 "/>
<text text-anchor="middle" x="1861" y="-1130.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytoband</text>
<polyline fill="none" stroke="#000000" points="1737.5,-1122.5 1984.5,-1122.5 "/>
<text text-anchor="middle" x="1861" y="-1107.3" font-family="Times,serif" font-size="14.00" fill="#000000">exon</text>
<polyline fill="none" stroke="#000000" points="1737.5,-1099.5 1984.5,-1099.5 "/>
<text text-anchor="middle" x="1861" y="-1084.3" font-family="Times,serif" font-size="14.00" fill="#000000">gene_symbol</text>
<polyline fill="none" stroke="#000000" points="1737.5,-1076.5 1984.5,-1076.5 "/>
<text text-anchor="middle" x="1861" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">histone_family</text>
<polyline fill="none" stroke="#000000" points="1737.5,-1053.5 1984.5,-1053.5 "/>
<text text-anchor="middle" x="1861" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">histone_variant</text>
<polyline fill="none" stroke="#000000" points="1737.5,-1030.5 1984.5,-1030.5 "/>
<text text-anchor="middle" x="1861" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">intron</text>
<polyline fill="none" stroke="#000000" points="1737.5,-1007.5 1984.5,-1007.5 "/>
<text text-anchor="middle" x="1861" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
<polyline fill="none" stroke="#000000" points="1737.5,-984.5 1984.5,-984.5 "/>
<text text-anchor="middle" x="1861" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">loci_abnormal_count</text>
<polyline fill="none" stroke="#000000" points="1737.5,-961.5 1984.5,-961.5 "/>
<text text-anchor="middle" x="1861" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">loci_count</text>
<polyline fill="none" stroke="#000000" points="1737.5,-938.5 1984.5,-938.5 "/>
<text text-anchor="middle" x="1861" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">locus</text>
<polyline fill="none" stroke="#000000" points="1737.5,-915.5 1984.5,-915.5 "/>
<text text-anchor="middle" x="1861" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">mismatch_repair_mutation</text>
<polyline fill="none" stroke="#000000" points="1737.5,-892.5 1984.5,-892.5 "/>
<text text-anchor="middle" x="1861" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_analysis_method</text>
<polyline fill="none" stroke="#000000" points="1737.5,-869.5 1984.5,-869.5 "/>
<text text-anchor="middle" x="1861" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_consequence</text>
<polyline fill="none" stroke="#000000" points="1737.5,-846.5 1984.5,-846.5 "/>
<text text-anchor="middle" x="1861" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test_id</text>
<polyline fill="none" stroke="#000000" points="1737.5,-823.5 1984.5,-823.5 "/>
<text text-anchor="middle" x="1861" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathogenicity</text>
<polyline fill="none" stroke="#000000" points="1737.5,-800.5 1984.5,-800.5 "/>
<text text-anchor="middle" x="1861" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">ploidy</text>
<polyline fill="none" stroke="#000000" points="1737.5,-777.5 1984.5,-777.5 "/>
<text text-anchor="middle" x="1861" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">second_exon</text>
<polyline fill="none" stroke="#000000" points="1737.5,-754.5 1984.5,-754.5 "/>
<text text-anchor="middle" x="1861" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 11 properties</text>
<polyline fill="none" stroke="#000000" points="1984.5,-731.5 1984.5,-1329.5 "/>
<text text-anchor="middle" x="1995" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2005.8601,-736.2152C2008.7112,-734.4219 2011.5911,-732.6825 2014.5,-731 2098.0768,-682.6599 2700.4607,-645.9624 3004.2557,-630.3057"/>
<polygon fill="#000000" stroke="#000000" points="3004.6831,-633.7884 3014.4905,-629.7803 3004.3242,-626.7976 3004.6831,-633.7884"/>
<text text-anchor="middle" x="2219.5" y="-701.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- diagnosis -->
<g id="node14" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M2035.5,-835C2035.5,-835 2409.5,-835 2409.5,-835 2415.5,-835 2421.5,-841 2421.5,-847 2421.5,-847 2421.5,-1214 2421.5,-1214 2421.5,-1220 2415.5,-1226 2409.5,-1226 2409.5,-1226 2035.5,-1226 2035.5,-1226 2029.5,-1226 2023.5,-1220 2023.5,-1214 2023.5,-1214 2023.5,-847 2023.5,-847 2023.5,-841 2029.5,-835 2035.5,-835"/>
<text text-anchor="middle" x="2065.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="2107.5,-835 2107.5,-1226 "/>
<text text-anchor="middle" x="2118" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2128.5,-835 2128.5,-1226 "/>
<text text-anchor="middle" x="2264.5" y="-1210.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2128.5,-1203 2400.5,-1203 "/>
<text text-anchor="middle" x="2264.5" y="-1187.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="2128.5,-1180 2400.5,-1180 "/>
<text text-anchor="middle" x="2264.5" y="-1164.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="2128.5,-1157 2400.5,-1157 "/>
<text text-anchor="middle" x="2264.5" y="-1141.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2128.5,-1134 2400.5,-1134 "/>
<text text-anchor="middle" x="2264.5" y="-1118.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="2128.5,-1111 2400.5,-1111 "/>
<text text-anchor="middle" x="2264.5" y="-1095.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="2128.5,-1088 2400.5,-1088 "/>
<text text-anchor="middle" x="2264.5" y="-1072.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="2128.5,-1065 2400.5,-1065 "/>
<text text-anchor="middle" x="2264.5" y="-1049.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="2128.5,-1042 2400.5,-1042 "/>
<text text-anchor="middle" x="2264.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="2128.5,-1019 2400.5,-1019 "/>
<text text-anchor="middle" x="2264.5" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="2128.5,-996 2400.5,-996 "/>
<text text-anchor="middle" x="2264.5" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2128.5,-973 2400.5,-973 "/>
<text text-anchor="middle" x="2264.5" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="2128.5,-950 2400.5,-950 "/>
<text text-anchor="middle" x="2264.5" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="2128.5,-927 2400.5,-927 "/>
<text text-anchor="middle" x="2264.5" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="2128.5,-904 2400.5,-904 "/>
<text text-anchor="middle" x="2264.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="2128.5,-881 2400.5,-881 "/>
<text text-anchor="middle" x="2264.5" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="2128.5,-858 2400.5,-858 "/>
<text text-anchor="middle" x="2264.5" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="2400.5,-835 2400.5,-1226 "/>
<text text-anchor="middle" x="2411" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2323.7239,-834.7744C2353.0316,-794.7001 2388.6478,-756.9046 2430.5,-731 2523.6818,-673.3246 2813.6398,-644.5112 3003.9652,-631.4485"/>
<polygon fill="#000000" stroke="#000000" points="3004.3438,-634.931 3014.0841,-630.7624 3003.8702,-627.947 3004.3438,-634.931"/>
<text text-anchor="middle" x="2545" y="-701.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- therapeutic_procedure -->
<g id="node15" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M3332,-1611.5C3332,-1611.5 3733,-1611.5 3733,-1611.5 3739,-1611.5 3745,-1617.5 3745,-1623.5 3745,-1623.5 3745,-1737.5 3745,-1737.5 3745,-1743.5 3739,-1749.5 3733,-1749.5 3733,-1749.5 3332,-1749.5 3332,-1749.5 3326,-1749.5 3320,-1743.5 3320,-1737.5 3320,-1737.5 3320,-1623.5 3320,-1623.5 3320,-1617.5 3326,-1611.5 3332,-1611.5"/>
<text text-anchor="middle" x="3410.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="3501,-1611.5 3501,-1749.5 "/>
<text text-anchor="middle" x="3511.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3522,-1611.5 3522,-1749.5 "/>
<text text-anchor="middle" x="3623" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment_end</text>
<polyline fill="none" stroke="#000000" points="3522,-1726.5 3724,-1726.5 "/>
<text text-anchor="middle" x="3623" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment_start</text>
<polyline fill="none" stroke="#000000" points="3522,-1703.5 3724,-1703.5 "/>
<text text-anchor="middle" x="3623" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="3522,-1680.5 3724,-1680.5 "/>
<text text-anchor="middle" x="3623" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure_id</text>
<polyline fill="none" stroke="#000000" points="3522,-1657.5 3724,-1657.5 "/>
<text text-anchor="middle" x="3623" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="3522,-1634.5 3724,-1634.5 "/>
<text text-anchor="middle" x="3623" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="3724,-1611.5 3724,-1749.5 "/>
<text text-anchor="middle" x="3734.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3574.5683,-1611.4244C3613.6764,-1542.8633 3669.1535,-1433.353 3691.5,-1330 3705.5653,-1264.9476 3733.3868,-782.7218 3691.5,-731 3649.1254,-678.6759 3484.4918,-650.4292 3353.0057,-635.9037"/>
<polygon fill="#000000" stroke="#000000" points="3353.1188,-632.3955 3342.7995,-634.7962 3352.3635,-639.3547 3353.1188,-632.3955"/>
<text text-anchor="middle" x="3807.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>therapeutic_procedure&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3400.9786,-1611.3994C3259.7069,-1540.6512 3026.5898,-1433.8038 2812.5,-1381 2653.066,-1341.6767 2608.4619,-1357.0568 2444.5,-1348 2396.7845,-1345.3643 1625.7864,-1354.0655 1584.5,-1330 1507.0154,-1284.835 1459.5747,-1191.5144 1433.3691,-1120.9736"/>
<polygon fill="#000000" stroke="#000000" points="1436.5151,-1119.3829 1429.8114,-1111.1786 1429.9356,-1121.7727 1436.5151,-1119.3829"/>
<text text-anchor="middle" x="2814.5" y="-1351.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- clinical_measure_file -->
<g id="node16" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M4056,-892.5C4056,-892.5 4429,-892.5 4429,-892.5 4435,-892.5 4441,-898.5 4441,-904.5 4441,-904.5 4441,-1156.5 4441,-1156.5 4441,-1162.5 4435,-1168.5 4429,-1168.5 4429,-1168.5 4056,-1168.5 4056,-1168.5 4050,-1168.5 4044,-1162.5 4044,-1156.5 4044,-1156.5 4044,-904.5 4044,-904.5 4044,-898.5 4050,-892.5 4056,-892.5"/>
<text text-anchor="middle" x="4127.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="4211,-892.5 4211,-1168.5 "/>
<text text-anchor="middle" x="4221.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4232,-892.5 4232,-1168.5 "/>
<text text-anchor="middle" x="4326" y="-1153.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="4232,-1145.5 4420,-1145.5 "/>
<text text-anchor="middle" x="4326" y="-1130.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="4232,-1122.5 4420,-1122.5 "/>
<text text-anchor="middle" x="4326" y="-1107.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file_id</text>
<polyline fill="none" stroke="#000000" points="4232,-1099.5 4420,-1099.5 "/>
<text text-anchor="middle" x="4326" y="-1084.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="4232,-1076.5 4420,-1076.5 "/>
<text text-anchor="middle" x="4326" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="4232,-1053.5 4420,-1053.5 "/>
<text text-anchor="middle" x="4326" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="4232,-1030.5 4420,-1030.5 "/>
<text text-anchor="middle" x="4326" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="4232,-1007.5 4420,-1007.5 "/>
<text text-anchor="middle" x="4326" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="4232,-984.5 4420,-984.5 "/>
<text text-anchor="middle" x="4326" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="4232,-961.5 4420,-961.5 "/>
<text text-anchor="middle" x="4326" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="4232,-938.5 4420,-938.5 "/>
<text text-anchor="middle" x="4326" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="4232,-915.5 4420,-915.5 "/>
<text text-anchor="middle" x="4326" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="4420,-892.5 4420,-1168.5 "/>
<text text-anchor="middle" x="4430.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M4166.537,-892.2419C4130.6826,-836.5768 4083.7936,-775.2252 4029.5,-731 4015.3822,-719.5003 3972.1149,-702.6118 3954.5,-698 3844.69,-669.2502 3545.7173,-645.5519 3352.5555,-632.6252"/>
<polygon fill="#000000" stroke="#000000" points="3352.788,-629.1331 3342.5775,-631.9608 3352.3228,-636.1176 3352.788,-629.1331"/>
<text text-anchor="middle" x="4125" y="-701.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge1" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M4248.9513,-892.2574C4255.2998,-768.9283 4265.7316,-597.8326 4277.5,-531 4290.4924,-457.2163 4312.154,-377.2654 4332.7588,-309.7444"/>
<polygon fill="#000000" stroke="#000000" points="4336.1998,-310.4616 4335.79,-299.8747 4329.5083,-308.4065 4336.1998,-310.4616"/>
<text text-anchor="middle" x="4363.5" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- exposure -->
<g id="node17" class="node">
<title>exposure</title>
<path fill="none" stroke="#000000" d="M2452,-789C2452,-789 2863,-789 2863,-789 2869,-789 2875,-795 2875,-801 2875,-801 2875,-1260 2875,-1260 2875,-1266 2869,-1272 2863,-1272 2863,-1272 2452,-1272 2452,-1272 2446,-1272 2440,-1266 2440,-1260 2440,-1260 2440,-801 2440,-801 2440,-795 2446,-789 2452,-789"/>
<text text-anchor="middle" x="2481" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
<polyline fill="none" stroke="#000000" points="2522,-789 2522,-1272 "/>
<text text-anchor="middle" x="2532.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2543,-789 2543,-1272 "/>
<text text-anchor="middle" x="2698.5" y="-1256.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_days_per_week</text>
<polyline fill="none" stroke="#000000" points="2543,-1249 2854,-1249 "/>
<text text-anchor="middle" x="2698.5" y="-1233.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_drinks_per_day</text>
<polyline fill="none" stroke="#000000" points="2543,-1226 2854,-1226 "/>
<text text-anchor="middle" x="2698.5" y="-1210.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_history</text>
<polyline fill="none" stroke="#000000" points="2543,-1203 2854,-1203 "/>
<text text-anchor="middle" x="2698.5" y="-1187.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_intensity</text>
<polyline fill="none" stroke="#000000" points="2543,-1180 2854,-1180 "/>
<text text-anchor="middle" x="2698.5" y="-1164.8" font-family="Times,serif" font-size="14.00" fill="#000000">asbestos_exposure</text>
<polyline fill="none" stroke="#000000" points="2543,-1157 2854,-1157 "/>
<text text-anchor="middle" x="2698.5" y="-1141.8" font-family="Times,serif" font-size="14.00" fill="#000000">cigarettes_per_day</text>
<polyline fill="none" stroke="#000000" points="2543,-1134 2854,-1134 "/>
<text text-anchor="middle" x="2698.5" y="-1118.8" font-family="Times,serif" font-size="14.00" fill="#000000">coal_dust_exposure</text>
<polyline fill="none" stroke="#000000" points="2543,-1111 2854,-1111 "/>
<text text-anchor="middle" x="2698.5" y="-1095.8" font-family="Times,serif" font-size="14.00" fill="#000000">environmental_tobacco_smoke_exposure</text>
<polyline fill="none" stroke="#000000" points="2543,-1088 2854,-1088 "/>
<text text-anchor="middle" x="2698.5" y="-1072.8" font-family="Times,serif" font-size="14.00" fill="#000000">exposure_id</text>
<polyline fill="none" stroke="#000000" points="2543,-1065 2854,-1065 "/>
<text text-anchor="middle" x="2698.5" y="-1049.8" font-family="Times,serif" font-size="14.00" fill="#000000">pack_years_smoked</text>
<polyline fill="none" stroke="#000000" points="2543,-1042 2854,-1042 "/>
<text text-anchor="middle" x="2698.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">radon_exposure</text>
<polyline fill="none" stroke="#000000" points="2543,-1019 2854,-1019 "/>
<text text-anchor="middle" x="2698.5" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">respirable_crystalline_silica_exposure</text>
<polyline fill="none" stroke="#000000" points="2543,-996 2854,-996 "/>
<text text-anchor="middle" x="2698.5" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">smoking_frequency</text>
<polyline fill="none" stroke="#000000" points="2543,-973 2854,-973 "/>
<text text-anchor="middle" x="2698.5" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">start_days_from_index</text>
<polyline fill="none" stroke="#000000" points="2543,-950 2854,-950 "/>
<text text-anchor="middle" x="2698.5" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">time_between_waking_and_first_smoke</text>
<polyline fill="none" stroke="#000000" points="2543,-927 2854,-927 "/>
<text text-anchor="middle" x="2698.5" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_onset_year</text>
<polyline fill="none" stroke="#000000" points="2543,-904 2854,-904 "/>
<text text-anchor="middle" x="2698.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_quit_year</text>
<polyline fill="none" stroke="#000000" points="2543,-881 2854,-881 "/>
<text text-anchor="middle" x="2698.5" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_status</text>
<polyline fill="none" stroke="#000000" points="2543,-858 2854,-858 "/>
<text text-anchor="middle" x="2698.5" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_smoke_exposure</text>
<polyline fill="none" stroke="#000000" points="2543,-835 2854,-835 "/>
<text text-anchor="middle" x="2698.5" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_tobacco_used</text>
<polyline fill="none" stroke="#000000" points="2543,-812 2854,-812 "/>
<text text-anchor="middle" x="2698.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">years_smoked</text>
<polyline fill="none" stroke="#000000" points="2854,-789 2854,-1272 "/>
<text text-anchor="middle" x="2864.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2819.1312,-788.9429C2839.219,-767.7084 2860.7578,-747.9025 2883.5,-731 2919.4536,-704.2786 2962.662,-683.4893 3004.7821,-667.5744"/>
<polygon fill="#000000" stroke="#000000" points="3006.1525,-670.7993 3014.3165,-664.0466 3003.7234,-664.2343 3006.1525,-670.7993"/>
<text text-anchor="middle" x="2978" y="-701.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- study_admin -->
<g id="node18" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M4702.5,-351.5C4702.5,-351.5 5028.5,-351.5 5028.5,-351.5 5034.5,-351.5 5040.5,-357.5 5040.5,-363.5 5040.5,-363.5 5040.5,-500.5 5040.5,-500.5 5040.5,-506.5 5034.5,-512.5 5028.5,-512.5 5028.5,-512.5 4702.5,-512.5 4702.5,-512.5 4696.5,-512.5 4690.5,-506.5 4690.5,-500.5 4690.5,-500.5 4690.5,-363.5 4690.5,-363.5 4690.5,-357.5 4696.5,-351.5 4702.5,-351.5"/>
<text text-anchor="middle" x="4744.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="4798.5,-351.5 4798.5,-512.5 "/>
<text text-anchor="middle" x="4809" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4819.5,-351.5 4819.5,-512.5 "/>
<text text-anchor="middle" x="4919.5" y="-497.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="4819.5,-489.5 5019.5,-489.5 "/>
<text text-anchor="middle" x="4919.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="4819.5,-466.5 5019.5,-466.5 "/>
<text text-anchor="middle" x="4919.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="4819.5,-443.5 5019.5,-443.5 "/>
<text text-anchor="middle" x="4919.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="4819.5,-420.5 5019.5,-420.5 "/>
<text text-anchor="middle" x="4919.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="4819.5,-397.5 5019.5,-397.5 "/>
<text text-anchor="middle" x="4919.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="4819.5,-374.5 5019.5,-374.5 "/>
<text text-anchor="middle" x="4919.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="5019.5,-351.5 5019.5,-512.5 "/>
<text text-anchor="middle" x="5030" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge24" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M4728.5584,-351.3789C4689.241,-328.2317 4645.3774,-302.408 4602.5258,-277.1801"/>
<polygon fill="#000000" stroke="#000000" points="4604.0786,-274.0328 4593.6854,-271.9755 4600.5272,-280.0651 4604.0786,-274.0328"/>
<text text-anchor="middle" x="4754" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- family_relationship -->
<g id="node19" class="node">
<title>family_relationship</title>
<path fill="none" stroke="#000000" d="M2905,-984.5C2905,-984.5 3274,-984.5 3274,-984.5 3280,-984.5 3286,-990.5 3286,-996.5 3286,-996.5 3286,-1064.5 3286,-1064.5 3286,-1070.5 3280,-1076.5 3274,-1076.5 3274,-1076.5 2905,-1076.5 2905,-1076.5 2899,-1076.5 2893,-1070.5 2893,-1064.5 2893,-1064.5 2893,-996.5 2893,-996.5 2893,-990.5 2899,-984.5 2905,-984.5"/>
<text text-anchor="middle" x="2970" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
<polyline fill="none" stroke="#000000" points="3047,-984.5 3047,-1076.5 "/>
<text text-anchor="middle" x="3057.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3068,-984.5 3068,-1076.5 "/>
<text text-anchor="middle" x="3166.5" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_id</text>
<polyline fill="none" stroke="#000000" points="3068,-1053.5 3265,-1053.5 "/>
<text text-anchor="middle" x="3166.5" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship_id</text>
<polyline fill="none" stroke="#000000" points="3068,-1030.5 3265,-1030.5 "/>
<text text-anchor="middle" x="3166.5" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">related_to_participant_id</text>
<polyline fill="none" stroke="#000000" points="3068,-1007.5 3265,-1007.5 "/>
<text text-anchor="middle" x="3166.5" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">relationship</text>
<polyline fill="none" stroke="#000000" points="3265,-984.5 3265,-1076.5 "/>
<text text-anchor="middle" x="3275.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3099.5364,-984.4339C3115.2192,-912.4516 3145.6165,-772.9314 3163.7799,-689.5637"/>
<polygon fill="#000000" stroke="#000000" points="3167.2234,-690.1995 3165.9325,-679.6836 3160.3838,-688.7093 3167.2234,-690.1995"/>
<text text-anchor="middle" x="3241" y="-701.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node20" class="node">
<title>single_cell_sequencing_file</title>
<path fill="none" stroke="#000000" d="M12,-1381.5C12,-1381.5 621,-1381.5 621,-1381.5 627,-1381.5 633,-1387.5 633,-1393.5 633,-1393.5 633,-1967.5 633,-1967.5 633,-1973.5 627,-1979.5 621,-1979.5 621,-1979.5 12,-1979.5 12,-1979.5 6,-1979.5 0,-1973.5 0,-1967.5 0,-1967.5 0,-1393.5 0,-1393.5 0,-1387.5 6,-1381.5 12,-1381.5"/>
<text text-anchor="middle" x="106" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
<polyline fill="none" stroke="#000000" points="212,-1381.5 212,-1979.5 "/>
<text text-anchor="middle" x="222.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="233,-1381.5 233,-1979.5 "/>
<text text-anchor="middle" x="422.5" y="-1964.3" font-family="Times,serif" font-size="14.00" fill="#000000">Cell_Barcode</text>
<polyline fill="none" stroke="#000000" points="233,-1956.5 612,-1956.5 "/>
<text text-anchor="middle" x="422.5" y="-1941.3" font-family="Times,serif" font-size="14.00" fill="#000000">Cryopreserved_Cells_in_Sample</text>
<polyline fill="none" stroke="#000000" points="233,-1933.5 612,-1933.5 "/>
<text text-anchor="middle" x="422.5" y="-1918.3" font-family="Times,serif" font-size="14.00" fill="#000000">Dissociation_Method</text>
<polyline fill="none" stroke="#000000" points="233,-1910.5 612,-1910.5 "/>
<text text-anchor="middle" x="422.5" y="-1895.3" font-family="Times,serif" font-size="14.00" fill="#000000">End_Bias</text>
<polyline fill="none" stroke="#000000" points="233,-1887.5 612,-1887.5 "/>
<text text-anchor="middle" x="422.5" y="-1872.3" font-family="Times,serif" font-size="14.00" fill="#000000">Input_Cells_and_Nuclei</text>
<polyline fill="none" stroke="#000000" points="233,-1864.5 612,-1864.5 "/>
<text text-anchor="middle" x="422.5" y="-1849.3" font-family="Times,serif" font-size="14.00" fill="#000000">Library_Construction_Method</text>
<polyline fill="none" stroke="#000000" points="233,-1841.5 612,-1841.5 "/>
<text text-anchor="middle" x="422.5" y="-1826.3" font-family="Times,serif" font-size="14.00" fill="#000000">Library_Preparation_Date</text>
<polyline fill="none" stroke="#000000" points="233,-1818.5 612,-1818.5 "/>
<text text-anchor="middle" x="422.5" y="-1803.3" font-family="Times,serif" font-size="14.00" fill="#000000">Nucleic_Acid_Capture_Date</text>
<polyline fill="none" stroke="#000000" points="233,-1795.5 612,-1795.5 "/>
<text text-anchor="middle" x="422.5" y="-1780.3" font-family="Times,serif" font-size="14.00" fill="#000000">Paired_End</text>
<polyline fill="none" stroke="#000000" points="233,-1772.5 612,-1772.5 "/>
<text text-anchor="middle" x="422.5" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">Protocols_Link</text>
<polyline fill="none" stroke="#000000" points="233,-1749.5 612,-1749.5 "/>
<text text-anchor="middle" x="422.5" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">Read1</text>
<polyline fill="none" stroke="#000000" points="233,-1726.5 612,-1726.5 "/>
<text text-anchor="middle" x="422.5" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">Read2</text>
<polyline fill="none" stroke="#000000" points="233,-1703.5 612,-1703.5 "/>
<text text-anchor="middle" x="422.5" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Feature_barcoding</text>
<polyline fill="none" stroke="#000000" points="233,-1680.5 612,-1680.5 "/>
<text text-anchor="middle" x="422.5" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Oligo_dT_Poly_dT</text>
<polyline fill="none" stroke="#000000" points="233,-1657.5 612,-1657.5 "/>
<text text-anchor="middle" x="422.5" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Random</text>
<polyline fill="none" stroke="#000000" points="233,-1634.5 612,-1634.5 "/>
<text text-anchor="middle" x="422.5" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">Sequencing_Library_Construction_Date</text>
<polyline fill="none" stroke="#000000" points="233,-1611.5 612,-1611.5 "/>
<text text-anchor="middle" x="422.5" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">Single_Cell_Dissociation_Date</text>
<polyline fill="none" stroke="#000000" points="233,-1588.5 612,-1588.5 "/>
<text text-anchor="middle" x="422.5" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">Single_Cell_Isolation_Method</text>
<polyline fill="none" stroke="#000000" points="233,-1565.5 612,-1565.5 "/>
<text text-anchor="middle" x="422.5" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">Spike_In</text>
<polyline fill="none" stroke="#000000" points="233,-1542.5 612,-1542.5 "/>
<text text-anchor="middle" x="422.5" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">Total_Number_of_Input_Cells</text>
<polyline fill="none" stroke="#000000" points="233,-1519.5 612,-1519.5 "/>
<text text-anchor="middle" x="422.5" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">UMI</text>
<polyline fill="none" stroke="#000000" points="233,-1496.5 612,-1496.5 "/>
<text text-anchor="middle" x="422.5" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="233,-1473.5 612,-1473.5 "/>
<text text-anchor="middle" x="422.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">cDNA_Length</text>
<polyline fill="none" stroke="#000000" points="233,-1450.5 612,-1450.5 "/>
<text text-anchor="middle" x="422.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">cDNA_Offset</text>
<polyline fill="none" stroke="#000000" points="233,-1427.5 612,-1427.5 "/>
<text text-anchor="middle" x="422.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="233,-1404.5 612,-1404.5 "/>
<text text-anchor="middle" x="422.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 24 properties</text>
<polyline fill="none" stroke="#000000" points="612,-1381.5 612,-1979.5 "/>
<text text-anchor="middle" x="622.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M633.1742,-1385.6092C636.2735,-1384.0341 639.3823,-1382.4971 642.5,-1381 729.6477,-1339.1521 761.3128,-1357.6951 857.5,-1348 898.4522,-1343.8722 1192.2044,-1351.1742 1227.5,-1330 1304.3979,-1283.8681 1352.2172,-1190.938 1378.8742,-1120.7599"/>
<polygon fill="#000000" stroke="#000000" points="1382.2926,-1121.6086 1382.4959,-1111.0157 1375.7312,-1119.1698 1382.2926,-1121.6086"/>
<text text-anchor="middle" x="966" y="-1351.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- imaging_file -->
<g id="node21" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M663.5,-1508C663.5,-1508 997.5,-1508 997.5,-1508 1003.5,-1508 1009.5,-1514 1009.5,-1520 1009.5,-1520 1009.5,-1841 1009.5,-1841 1009.5,-1847 1003.5,-1853 997.5,-1853 997.5,-1853 663.5,-1853 663.5,-1853 657.5,-1853 651.5,-1847 651.5,-1841 651.5,-1841 651.5,-1520 651.5,-1520 651.5,-1514 657.5,-1508 663.5,-1508"/>
<text text-anchor="middle" x="703.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="755.5,-1508 755.5,-1853 "/>
<text text-anchor="middle" x="766" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="776.5,-1508 776.5,-1853 "/>
<text text-anchor="middle" x="882.5" y="-1837.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="776.5,-1830 988.5,-1830 "/>
<text text-anchor="middle" x="882.5" y="-1814.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="776.5,-1807 988.5,-1807 "/>
<text text-anchor="middle" x="882.5" y="-1791.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="776.5,-1784 988.5,-1784 "/>
<text text-anchor="middle" x="882.5" y="-1768.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="776.5,-1761 988.5,-1761 "/>
<text text-anchor="middle" x="882.5" y="-1745.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="776.5,-1738 988.5,-1738 "/>
<text text-anchor="middle" x="882.5" y="-1722.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="776.5,-1715 988.5,-1715 "/>
<text text-anchor="middle" x="882.5" y="-1699.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="776.5,-1692 988.5,-1692 "/>
<text text-anchor="middle" x="882.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="776.5,-1669 988.5,-1669 "/>
<text text-anchor="middle" x="882.5" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="776.5,-1646 988.5,-1646 "/>
<text text-anchor="middle" x="882.5" y="-1630.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="776.5,-1623 988.5,-1623 "/>
<text text-anchor="middle" x="882.5" y="-1607.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file_id</text>
<polyline fill="none" stroke="#000000" points="776.5,-1600 988.5,-1600 "/>
<text text-anchor="middle" x="882.5" y="-1584.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="776.5,-1577 988.5,-1577 "/>
<text text-anchor="middle" x="882.5" y="-1561.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="776.5,-1554 988.5,-1554 "/>
<text text-anchor="middle" x="882.5" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="776.5,-1531 988.5,-1531 "/>
<text text-anchor="middle" x="882.5" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="988.5,-1508 988.5,-1853 "/>
<text text-anchor="middle" x="999" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge28" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M907.8882,-1507.9626C936.5369,-1460.7085 973.3122,-1413.5882 1018.5,-1381 1057.2756,-1353.0361 1189.0322,-1358.3859 1227.5,-1330 1298.3756,-1277.7001 1346.4869,-1188.1845 1374.8275,-1120.6049"/>
<polygon fill="#000000" stroke="#000000" points="1378.1205,-1121.8001 1378.6956,-1111.2209 1371.6487,-1119.1324 1378.1205,-1121.8001"/>
<text text-anchor="middle" x="1228" y="-1351.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- study_personnel -->
<g id="node22" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M5071,-374.5C5071,-374.5 5378,-374.5 5378,-374.5 5384,-374.5 5390,-380.5 5390,-386.5 5390,-386.5 5390,-477.5 5390,-477.5 5390,-483.5 5384,-489.5 5378,-489.5 5378,-489.5 5071,-489.5 5071,-489.5 5065,-489.5 5059,-483.5 5059,-477.5 5059,-477.5 5059,-386.5 5059,-386.5 5059,-380.5 5065,-374.5 5071,-374.5"/>
<text text-anchor="middle" x="5126" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="5193,-374.5 5193,-489.5 "/>
<text text-anchor="middle" x="5203.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="5214,-374.5 5214,-489.5 "/>
<text text-anchor="middle" x="5291.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="5214,-466.5 5369,-466.5 "/>
<text text-anchor="middle" x="5291.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="5214,-443.5 5369,-443.5 "/>
<text text-anchor="middle" x="5291.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="5214,-420.5 5369,-420.5 "/>
<text text-anchor="middle" x="5291.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="5214,-397.5 5369,-397.5 "/>
<text text-anchor="middle" x="5291.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="5369,-374.5 5369,-489.5 "/>
<text text-anchor="middle" x="5379.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge19" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M5105.8938,-374.4145C5087.2044,-366.1232 5067.9587,-358.0308 5049.5,-351 4903.1093,-295.2408 4734.068,-244.1922 4603.3135,-207.4932"/>
<polygon fill="#000000" stroke="#000000" points="4604.1434,-204.091 4593.57,-204.7651 4602.256,-210.8318 4604.1434,-204.091"/>
<text text-anchor="middle" x="5066" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- study_funding -->
<g id="node23" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M5420,-386C5420,-386 5799,-386 5799,-386 5805,-386 5811,-392 5811,-398 5811,-398 5811,-466 5811,-466 5811,-472 5805,-478 5799,-478 5799,-478 5420,-478 5420,-478 5414,-478 5408,-472 5408,-466 5408,-466 5408,-398 5408,-398 5408,-392 5414,-386 5420,-386"/>
<text text-anchor="middle" x="5467.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="5527,-386 5527,-478 "/>
<text text-anchor="middle" x="5537.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="5548,-386 5548,-478 "/>
<text text-anchor="middle" x="5669" y="-462.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="5548,-455 5790,-455 "/>
<text text-anchor="middle" x="5669" y="-439.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="5548,-432 5790,-432 "/>
<text text-anchor="middle" x="5669" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="5548,-409 5790,-409 "/>
<text text-anchor="middle" x="5669" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding_id</text>
<polyline fill="none" stroke="#000000" points="5790,-386 5790,-478 "/>
<text text-anchor="middle" x="5800.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge25" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M5500.6425,-385.9186C5468.4637,-373.4169 5432.9042,-360.678 5399.5,-351 5129.6676,-272.8229 4810.6643,-215.047 4603.7594,-181.9846"/>
<polygon fill="#000000" stroke="#000000" points="4604.1108,-178.4965 4593.6847,-180.3801 4603.0098,-185.4094 4604.1108,-178.4965"/>
<text text-anchor="middle" x="5380.5" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
</g>
</svg>
</div>
