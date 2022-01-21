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
<svg width="2047pt" height="1284pt"
 viewBox="0.00 0.00 2047.35 1284.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1280)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1280 2043.3454,-1280 2043.3454,4 -4,4"/>
<!-- genomic_detail -->
<g id="node1" class="node">
<title>genomic_detail</title>
<path fill="none" stroke="#000000" d="M369.8454,-1045.5C369.8454,-1045.5 736.8454,-1045.5 736.8454,-1045.5 742.8454,-1045.5 748.8454,-1051.5 748.8454,-1057.5 748.8454,-1057.5 748.8454,-1263.5 748.8454,-1263.5 748.8454,-1269.5 742.8454,-1275.5 736.8454,-1275.5 736.8454,-1275.5 369.8454,-1275.5 369.8454,-1275.5 363.8454,-1275.5 357.8454,-1269.5 357.8454,-1263.5 357.8454,-1263.5 357.8454,-1057.5 357.8454,-1057.5 357.8454,-1051.5 363.8454,-1045.5 369.8454,-1045.5"/>
<text text-anchor="middle" x="420.3454" y="-1156.8" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_detail</text>
<polyline fill="none" stroke="#000000" points="482.8454,-1045.5 482.8454,-1275.5 "/>
<text text-anchor="middle" x="493.3454" y="-1156.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="503.8454,-1045.5 503.8454,-1275.5 "/>
<text text-anchor="middle" x="615.8454" y="-1260.3" font-family="Times,serif" font-size="14.00" fill="#000000">average_read_length</text>
<polyline fill="none" stroke="#000000" points="503.8454,-1252.5 727.8454,-1252.5 "/>
<text text-anchor="middle" x="615.8454" y="-1237.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="503.8454,-1229.5 727.8454,-1229.5 "/>
<text text-anchor="middle" x="615.8454" y="-1214.3" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_detail_id</text>
<polyline fill="none" stroke="#000000" points="503.8454,-1206.5 727.8454,-1206.5 "/>
<text text-anchor="middle" x="615.8454" y="-1191.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="503.8454,-1183.5 727.8454,-1183.5 "/>
<text text-anchor="middle" x="615.8454" y="-1168.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="503.8454,-1160.5 727.8454,-1160.5 "/>
<text text-anchor="middle" x="615.8454" y="-1145.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="503.8454,-1137.5 727.8454,-1137.5 "/>
<text text-anchor="middle" x="615.8454" y="-1122.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="503.8454,-1114.5 727.8454,-1114.5 "/>
<text text-anchor="middle" x="615.8454" y="-1099.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="503.8454,-1091.5 727.8454,-1091.5 "/>
<text text-anchor="middle" x="615.8454" y="-1076.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="503.8454,-1068.5 727.8454,-1068.5 "/>
<text text-anchor="middle" x="615.8454" y="-1053.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="727.8454,-1045.5 727.8454,-1275.5 "/>
<text text-anchor="middle" x="738.3454" y="-1156.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file -->
<g id="node11" class="node">
<title>file</title>
<path fill="none" stroke="#000000" d="M803.8454,-809.5C803.8454,-809.5 994.8454,-809.5 994.8454,-809.5 1000.8454,-809.5 1006.8454,-815.5 1006.8454,-821.5 1006.8454,-821.5 1006.8454,-981.5 1006.8454,-981.5 1006.8454,-987.5 1000.8454,-993.5 994.8454,-993.5 994.8454,-993.5 803.8454,-993.5 803.8454,-993.5 797.8454,-993.5 791.8454,-987.5 791.8454,-981.5 791.8454,-981.5 791.8454,-821.5 791.8454,-821.5 791.8454,-815.5 797.8454,-809.5 803.8454,-809.5"/>
<text text-anchor="middle" x="811.3454" y="-897.8" font-family="Times,serif" font-size="14.00" fill="#000000">file</text>
<polyline fill="none" stroke="#000000" points="830.8454,-809.5 830.8454,-993.5 "/>
<text text-anchor="middle" x="841.3454" y="-897.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="851.8454,-809.5 851.8454,-993.5 "/>
<text text-anchor="middle" x="918.8454" y="-978.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_url</text>
<polyline fill="none" stroke="#000000" points="851.8454,-970.5 985.8454,-970.5 "/>
<text text-anchor="middle" x="918.8454" y="-955.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="851.8454,-947.5 985.8454,-947.5 "/>
<text text-anchor="middle" x="918.8454" y="-932.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="851.8454,-924.5 985.8454,-924.5 "/>
<text text-anchor="middle" x="918.8454" y="-909.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_id</text>
<polyline fill="none" stroke="#000000" points="851.8454,-901.5 985.8454,-901.5 "/>
<text text-anchor="middle" x="918.8454" y="-886.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="851.8454,-878.5 985.8454,-878.5 "/>
<text text-anchor="middle" x="918.8454" y="-863.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="851.8454,-855.5 985.8454,-855.5 "/>
<text text-anchor="middle" x="918.8454" y="-840.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="851.8454,-832.5 985.8454,-832.5 "/>
<text text-anchor="middle" x="918.8454" y="-817.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="985.8454,-809.5 985.8454,-993.5 "/>
<text text-anchor="middle" x="996.3454" y="-897.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genomic_detail&#45;&gt;file -->
<g id="edge3" class="edge">
<title>genomic_detail&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M707.121,-1045.3905C732.7414,-1026.2123 758.9312,-1006.6078 783.4053,-988.2876"/>
<polygon fill="#000000" stroke="#000000" points="785.728,-990.9209 791.6361,-982.1263 781.5331,-985.317 785.728,-990.9209"/>
<text text-anchor="middle" x="769.3454" y="-1015.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- alias -->
<g id="node2" class="node">
<title>alias</title>
<path fill="none" stroke="#000000" d="M1266.8454,-1114.5C1266.8454,-1114.5 1471.8454,-1114.5 1471.8454,-1114.5 1477.8454,-1114.5 1483.8454,-1120.5 1483.8454,-1126.5 1483.8454,-1126.5 1483.8454,-1194.5 1483.8454,-1194.5 1483.8454,-1200.5 1477.8454,-1206.5 1471.8454,-1206.5 1471.8454,-1206.5 1266.8454,-1206.5 1266.8454,-1206.5 1260.8454,-1206.5 1254.8454,-1200.5 1254.8454,-1194.5 1254.8454,-1194.5 1254.8454,-1126.5 1254.8454,-1126.5 1254.8454,-1120.5 1260.8454,-1114.5 1266.8454,-1114.5"/>
<text text-anchor="middle" x="1279.8454" y="-1156.8" font-family="Times,serif" font-size="14.00" fill="#000000">alias</text>
<polyline fill="none" stroke="#000000" points="1304.8454,-1114.5 1304.8454,-1206.5 "/>
<text text-anchor="middle" x="1315.3454" y="-1156.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1325.8454,-1114.5 1325.8454,-1206.5 "/>
<text text-anchor="middle" x="1394.3454" y="-1191.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_id</text>
<polyline fill="none" stroke="#000000" points="1325.8454,-1183.5 1462.8454,-1183.5 "/>
<text text-anchor="middle" x="1394.3454" y="-1168.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_node</text>
<polyline fill="none" stroke="#000000" points="1325.8454,-1160.5 1462.8454,-1160.5 "/>
<text text-anchor="middle" x="1394.3454" y="-1145.3" font-family="Times,serif" font-size="14.00" fill="#000000">repository_id</text>
<polyline fill="none" stroke="#000000" points="1325.8454,-1137.5 1462.8454,-1137.5 "/>
<text text-anchor="middle" x="1394.3454" y="-1122.3" font-family="Times,serif" font-size="14.00" fill="#000000">repository_name</text>
<polyline fill="none" stroke="#000000" points="1462.8454,-1114.5 1462.8454,-1206.5 "/>
<text text-anchor="middle" x="1473.3454" y="-1156.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- experiment -->
<g id="node3" class="node">
<title>experiment</title>
<path fill="none" stroke="#000000" d="M1131.3454,-259.5C1131.3454,-259.5 1399.3454,-259.5 1399.3454,-259.5 1405.3454,-259.5 1411.3454,-265.5 1411.3454,-271.5 1411.3454,-271.5 1411.3454,-316.5 1411.3454,-316.5 1411.3454,-322.5 1405.3454,-328.5 1399.3454,-328.5 1399.3454,-328.5 1131.3454,-328.5 1131.3454,-328.5 1125.3454,-328.5 1119.3454,-322.5 1119.3454,-316.5 1119.3454,-316.5 1119.3454,-271.5 1119.3454,-271.5 1119.3454,-265.5 1125.3454,-259.5 1131.3454,-259.5"/>
<text text-anchor="middle" x="1168.3454" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">experiment</text>
<polyline fill="none" stroke="#000000" points="1217.3454,-259.5 1217.3454,-328.5 "/>
<text text-anchor="middle" x="1227.8454" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1238.3454,-259.5 1238.3454,-328.5 "/>
<text text-anchor="middle" x="1314.3454" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="1238.3454,-305.5 1390.3454,-305.5 "/>
<text text-anchor="middle" x="1314.3454" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">experiment_id</text>
<polyline fill="none" stroke="#000000" points="1238.3454,-282.5 1390.3454,-282.5 "/>
<text text-anchor="middle" x="1314.3454" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">protocol</text>
<polyline fill="none" stroke="#000000" points="1390.3454,-259.5 1390.3454,-328.5 "/>
<text text-anchor="middle" x="1400.8454" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- alias&#45;&gt;experiment -->
<g id="edge13" class="edge">
<title>alias&#45;&gt;experiment</title>
<path fill="none" stroke="#000000" d="M1339.4815,-1114.2934C1294.6342,-1041.8578 1211.8955,-895.5956 1181.3454,-758 1156.8768,-647.7948 1159.9973,-614.852 1181.3454,-504 1192.9089,-443.956 1221.486,-379.2566 1242.0996,-337.7829"/>
<polygon fill="#000000" stroke="#000000" points="1245.2596,-339.2894 1246.6291,-328.7835 1239.0069,-336.1423 1245.2596,-339.2894"/>
<text text-anchor="middle" x="1239.8454" y="-779.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_experiment</text>
</g>
<!-- study_subject -->
<g id="node9" class="node">
<title>study_subject</title>
<path fill="none" stroke="#000000" d="M1441.8454,-213.5C1441.8454,-213.5 1724.8454,-213.5 1724.8454,-213.5 1730.8454,-213.5 1736.8454,-219.5 1736.8454,-225.5 1736.8454,-225.5 1736.8454,-362.5 1736.8454,-362.5 1736.8454,-368.5 1730.8454,-374.5 1724.8454,-374.5 1724.8454,-374.5 1441.8454,-374.5 1441.8454,-374.5 1435.8454,-374.5 1429.8454,-368.5 1429.8454,-362.5 1429.8454,-362.5 1429.8454,-225.5 1429.8454,-225.5 1429.8454,-219.5 1435.8454,-213.5 1441.8454,-213.5"/>
<text text-anchor="middle" x="1487.8454" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_subject</text>
<polyline fill="none" stroke="#000000" points="1545.8454,-213.5 1545.8454,-374.5 "/>
<text text-anchor="middle" x="1556.3454" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1566.8454,-213.5 1566.8454,-374.5 "/>
<text text-anchor="middle" x="1641.3454" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_enrollment</text>
<polyline fill="none" stroke="#000000" points="1566.8454,-351.5 1715.8454,-351.5 "/>
<text text-anchor="middle" x="1641.3454" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_unit</text>
<polyline fill="none" stroke="#000000" points="1566.8454,-328.5 1715.8454,-328.5 "/>
<text text-anchor="middle" x="1641.3454" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="1566.8454,-305.5 1715.8454,-305.5 "/>
<text text-anchor="middle" x="1641.3454" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="1566.8454,-282.5 1715.8454,-282.5 "/>
<text text-anchor="middle" x="1641.3454" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1566.8454,-259.5 1715.8454,-259.5 "/>
<text text-anchor="middle" x="1641.3454" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_subject_id</text>
<polyline fill="none" stroke="#000000" points="1566.8454,-236.5 1715.8454,-236.5 "/>
<text text-anchor="middle" x="1641.3454" y="-221.3" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="1715.8454,-213.5 1715.8454,-374.5 "/>
<text text-anchor="middle" x="1726.3454" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- alias&#45;&gt;study_subject -->
<g id="edge19" class="edge">
<title>alias&#45;&gt;study_subject</title>
<path fill="none" stroke="#000000" d="M1398.0879,-1114.3683C1441.6381,-1041.739 1522.9098,-894.8738 1557.3454,-758 1589.2062,-631.3606 1591.1727,-479.3819 1588.3099,-384.7254"/>
<polygon fill="#000000" stroke="#000000" points="1591.8042,-384.4908 1587.979,-374.6106 1584.808,-384.7197 1591.8042,-384.4908"/>
<text text-anchor="middle" x="1611.8454" y="-779.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_subject</text>
</g>
<!-- study -->
<g id="node10" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M643.8454,-.5C643.8454,-.5 888.8454,-.5 888.8454,-.5 894.8454,-.5 900.8454,-6.5 900.8454,-12.5 900.8454,-12.5 900.8454,-149.5 900.8454,-149.5 900.8454,-155.5 894.8454,-161.5 888.8454,-161.5 888.8454,-161.5 643.8454,-161.5 643.8454,-161.5 637.8454,-161.5 631.8454,-155.5 631.8454,-149.5 631.8454,-149.5 631.8454,-12.5 631.8454,-12.5 631.8454,-6.5 637.8454,-.5 643.8454,-.5"/>
<text text-anchor="middle" x="659.8454" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="687.8454,-.5 687.8454,-161.5 "/>
<text text-anchor="middle" x="698.3454" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="708.8454,-.5 708.8454,-161.5 "/>
<text text-anchor="middle" x="794.3454" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_phs_accession</text>
<polyline fill="none" stroke="#000000" points="708.8454,-138.5 879.8454,-138.5 "/>
<text text-anchor="middle" x="794.3454" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">index_date</text>
<polyline fill="none" stroke="#000000" points="708.8454,-115.5 879.8454,-115.5 "/>
<text text-anchor="middle" x="794.3454" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="708.8454,-92.5 879.8454,-92.5 "/>
<text text-anchor="middle" x="794.3454" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="708.8454,-69.5 879.8454,-69.5 "/>
<text text-anchor="middle" x="794.3454" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_external_url</text>
<polyline fill="none" stroke="#000000" points="708.8454,-46.5 879.8454,-46.5 "/>
<text text-anchor="middle" x="794.3454" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="708.8454,-23.5 879.8454,-23.5 "/>
<text text-anchor="middle" x="794.3454" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_title</text>
<polyline fill="none" stroke="#000000" points="879.8454,-.5 879.8454,-161.5 "/>
<text text-anchor="middle" x="890.3454" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- alias&#45;&gt;study -->
<g id="edge9" class="edge">
<title>alias&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1483.8937,-1136.3083C1660.3061,-1095.7084 1978.3454,-1007.7766 1978.3454,-901.5 1978.3454,-901.5 1978.3454,-901.5 1978.3454,-294 1978.3454,-186.7747 1232.9851,-116.732 911.301,-91.4958"/>
<polygon fill="#000000" stroke="#000000" points="911.2151,-87.9785 900.973,-90.6895 910.6703,-94.9573 911.2151,-87.9785"/>
<text text-anchor="middle" x="2008.8454" y="-627.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- alias&#45;&gt;file -->
<g id="edge2" class="edge">
<title>alias&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M1273.2935,-1114.494C1222.5306,-1089.5842 1159.4825,-1057.6968 1104.3454,-1027 1075.2683,-1010.8117 1044.413,-992.5301 1015.7093,-975.0305"/>
<polygon fill="#000000" stroke="#000000" points="1017.2319,-971.859 1006.8746,-969.6278 1013.5799,-977.8309 1017.2319,-971.859"/>
<text text-anchor="middle" x="1126.3454" y="-1015.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- sample -->
<g id="node12" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1202.3454,-504.5C1202.3454,-504.5 1536.3454,-504.5 1536.3454,-504.5 1542.3454,-504.5 1548.3454,-510.5 1548.3454,-516.5 1548.3454,-516.5 1548.3454,-745.5 1548.3454,-745.5 1548.3454,-751.5 1542.3454,-757.5 1536.3454,-757.5 1536.3454,-757.5 1202.3454,-757.5 1202.3454,-757.5 1196.3454,-757.5 1190.3454,-751.5 1190.3454,-745.5 1190.3454,-745.5 1190.3454,-516.5 1190.3454,-516.5 1190.3454,-510.5 1196.3454,-504.5 1202.3454,-504.5"/>
<text text-anchor="middle" x="1224.3454" y="-627.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1258.3454,-504.5 1258.3454,-757.5 "/>
<text text-anchor="middle" x="1268.8454" y="-627.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1279.3454,-504.5 1279.3454,-757.5 "/>
<text text-anchor="middle" x="1403.3454" y="-742.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1279.3454,-734.5 1527.3454,-734.5 "/>
<text text-anchor="middle" x="1403.3454" y="-719.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_sample_id</text>
<polyline fill="none" stroke="#000000" points="1279.3454,-711.5 1527.3454,-711.5 "/>
<text text-anchor="middle" x="1403.3454" y="-696.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="1279.3454,-688.5 1527.3454,-688.5 "/>
<text text-anchor="middle" x="1403.3454" y="-673.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1279.3454,-665.5 1527.3454,-665.5 "/>
<text text-anchor="middle" x="1403.3454" y="-650.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="1279.3454,-642.5 1527.3454,-642.5 "/>
<text text-anchor="middle" x="1403.3454" y="-627.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_subject_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1279.3454,-619.5 1527.3454,-619.5 "/>
<text text-anchor="middle" x="1403.3454" y="-604.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1279.3454,-596.5 1527.3454,-596.5 "/>
<text text-anchor="middle" x="1403.3454" y="-581.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="1279.3454,-573.5 1527.3454,-573.5 "/>
<text text-anchor="middle" x="1403.3454" y="-558.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="1279.3454,-550.5 1527.3454,-550.5 "/>
<text text-anchor="middle" x="1403.3454" y="-535.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage</text>
<polyline fill="none" stroke="#000000" points="1279.3454,-527.5 1527.3454,-527.5 "/>
<text text-anchor="middle" x="1403.3454" y="-512.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_status</text>
<polyline fill="none" stroke="#000000" points="1527.3454,-504.5 1527.3454,-757.5 "/>
<text text-anchor="middle" x="1537.8454" y="-627.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- alias&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>alias&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1369.3454,-1114.4366C1369.3454,-1037.9901 1369.3454,-882.0332 1369.3454,-767.8521"/>
<polygon fill="#000000" stroke="#000000" points="1372.8455,-767.6312 1369.3454,-757.6312 1365.8455,-767.6313 1372.8455,-767.6312"/>
<text text-anchor="middle" x="1405.8454" y="-897.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- experiment&#45;&gt;study -->
<g id="edge8" class="edge">
<title>experiment&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1203.1849,-259.4255C1175.1826,-244.3963 1141.4791,-227.052 1110.3454,-213 1045.7373,-183.8395 972.6076,-155.1914 910.439,-132.0758"/>
<polygon fill="#000000" stroke="#000000" points="911.5471,-128.7539 900.9541,-128.5603 909.1143,-135.3176 911.5471,-128.7539"/>
<text text-anchor="middle" x="1094.8454" y="-183.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- imaging_detail -->
<g id="node4" class="node">
<title>imaging_detail</title>
<path fill="none" stroke="#000000" d="M778.8454,-1103C778.8454,-1103 1065.8454,-1103 1065.8454,-1103 1071.8454,-1103 1077.8454,-1109 1077.8454,-1115 1077.8454,-1115 1077.8454,-1206 1077.8454,-1206 1077.8454,-1212 1071.8454,-1218 1065.8454,-1218 1065.8454,-1218 778.8454,-1218 778.8454,-1218 772.8454,-1218 766.8454,-1212 766.8454,-1206 766.8454,-1206 766.8454,-1115 766.8454,-1115 766.8454,-1109 772.8454,-1103 778.8454,-1103"/>
<text text-anchor="middle" x="827.8454" y="-1156.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_detail</text>
<polyline fill="none" stroke="#000000" points="888.8454,-1103 888.8454,-1218 "/>
<text text-anchor="middle" x="899.3454" y="-1156.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="909.8454,-1103 909.8454,-1218 "/>
<text text-anchor="middle" x="983.3454" y="-1202.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="909.8454,-1195 1056.8454,-1195 "/>
<text text-anchor="middle" x="983.3454" y="-1179.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_detail_id</text>
<polyline fill="none" stroke="#000000" points="909.8454,-1172 1056.8454,-1172 "/>
<text text-anchor="middle" x="983.3454" y="-1156.8" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="909.8454,-1149 1056.8454,-1149 "/>
<text text-anchor="middle" x="983.3454" y="-1133.8" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="909.8454,-1126 1056.8454,-1126 "/>
<text text-anchor="middle" x="983.3454" y="-1110.8" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="1056.8454,-1103 1056.8454,-1218 "/>
<text text-anchor="middle" x="1067.3454" y="-1156.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_detail&#45;&gt;file -->
<g id="edge1" class="edge">
<title>imaging_detail&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M917.2124,-1102.6977C914.6328,-1073.6488 911.429,-1037.5715 908.4497,-1004.0221"/>
<polygon fill="#000000" stroke="#000000" points="911.9042,-1003.3531 907.5333,-993.7019 904.9316,-1003.9724 911.9042,-1003.3531"/>
<text text-anchor="middle" x="931.3454" y="-1015.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- study_funding -->
<g id="node5" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M145.8454,-259.5C145.8454,-259.5 422.8454,-259.5 422.8454,-259.5 428.8454,-259.5 434.8454,-265.5 434.8454,-271.5 434.8454,-271.5 434.8454,-316.5 434.8454,-316.5 434.8454,-322.5 428.8454,-328.5 422.8454,-328.5 422.8454,-328.5 145.8454,-328.5 145.8454,-328.5 139.8454,-328.5 133.8454,-322.5 133.8454,-316.5 133.8454,-316.5 133.8454,-271.5 133.8454,-271.5 133.8454,-265.5 139.8454,-259.5 145.8454,-259.5"/>
<text text-anchor="middle" x="193.3454" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="252.8454,-259.5 252.8454,-328.5 "/>
<text text-anchor="middle" x="263.3454" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="273.8454,-259.5 273.8454,-328.5 "/>
<text text-anchor="middle" x="343.8454" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="273.8454,-305.5 413.8454,-305.5 "/>
<text text-anchor="middle" x="343.8454" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_id</text>
<polyline fill="none" stroke="#000000" points="273.8454,-282.5 413.8454,-282.5 "/>
<text text-anchor="middle" x="343.8454" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding_id</text>
<polyline fill="none" stroke="#000000" points="413.8454,-259.5 413.8454,-328.5 "/>
<text text-anchor="middle" x="424.3454" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge11" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M349.1156,-259.4627C377.7306,-244.6062 411.9413,-227.386 443.3454,-213 501.2545,-186.4724 566.0832,-159.4679 622.3782,-136.8535"/>
<polygon fill="#000000" stroke="#000000" points="623.7178,-140.0873 631.698,-133.1183 621.1137,-133.5897 623.7178,-140.0873"/>
<text text-anchor="middle" x="543.8454" y="-183.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- study_admin -->
<g id="node6" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M464.8454,-236.5C464.8454,-236.5 735.8454,-236.5 735.8454,-236.5 741.8454,-236.5 747.8454,-242.5 747.8454,-248.5 747.8454,-248.5 747.8454,-339.5 747.8454,-339.5 747.8454,-345.5 741.8454,-351.5 735.8454,-351.5 735.8454,-351.5 464.8454,-351.5 464.8454,-351.5 458.8454,-351.5 452.8454,-345.5 452.8454,-339.5 452.8454,-339.5 452.8454,-248.5 452.8454,-248.5 452.8454,-242.5 458.8454,-236.5 464.8454,-236.5"/>
<text text-anchor="middle" x="506.8454" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="560.8454,-236.5 560.8454,-351.5 "/>
<text text-anchor="middle" x="571.3454" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="581.8454,-236.5 581.8454,-351.5 "/>
<text text-anchor="middle" x="654.3454" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_access_level</text>
<polyline fill="none" stroke="#000000" points="581.8454,-328.5 726.8454,-328.5 "/>
<text text-anchor="middle" x="654.3454" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="581.8454,-305.5 726.8454,-305.5 "/>
<text text-anchor="middle" x="654.3454" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types</text>
<polyline fill="none" stroke="#000000" points="581.8454,-282.5 726.8454,-282.5 "/>
<text text-anchor="middle" x="654.3454" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">species</text>
<polyline fill="none" stroke="#000000" points="581.8454,-259.5 726.8454,-259.5 "/>
<text text-anchor="middle" x="654.3454" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_type</text>
<polyline fill="none" stroke="#000000" points="726.8454,-236.5 726.8454,-351.5 "/>
<text text-anchor="middle" x="737.3454" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge12" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M645.2674,-236.3591C661.2433,-215.86 679.6222,-192.2775 697.1551,-169.7804"/>
<polygon fill="#000000" stroke="#000000" points="699.9296,-171.914 703.3161,-161.875 694.4083,-167.611 699.9296,-171.914"/>
<text text-anchor="middle" x="718.8454" y="-183.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- study_personnel -->
<g id="node7" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M777.8454,-248C777.8454,-248 1088.8454,-248 1088.8454,-248 1094.8454,-248 1100.8454,-254 1100.8454,-260 1100.8454,-260 1100.8454,-328 1100.8454,-328 1100.8454,-334 1094.8454,-340 1088.8454,-340 1088.8454,-340 777.8454,-340 777.8454,-340 771.8454,-340 765.8454,-334 765.8454,-328 765.8454,-328 765.8454,-260 765.8454,-260 765.8454,-254 771.8454,-248 777.8454,-248"/>
<text text-anchor="middle" x="832.8454" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="899.8454,-248 899.8454,-340 "/>
<text text-anchor="middle" x="910.3454" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="920.8454,-248 920.8454,-340 "/>
<text text-anchor="middle" x="1000.3454" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="920.8454,-317 1079.8454,-317 "/>
<text text-anchor="middle" x="1000.3454" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="920.8454,-294 1079.8454,-294 "/>
<text text-anchor="middle" x="1000.3454" y="-278.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="920.8454,-271 1079.8454,-271 "/>
<text text-anchor="middle" x="1000.3454" y="-255.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_ID</text>
<polyline fill="none" stroke="#000000" points="1079.8454,-248 1079.8454,-340 "/>
<text text-anchor="middle" x="1090.3454" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge10" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M897.1089,-247.7822C879.1228,-224.8418 856.7743,-196.3374 835.6703,-169.4203"/>
<polygon fill="#000000" stroke="#000000" points="838.3868,-167.2125 829.4624,-161.5024 832.8781,-171.5316 838.3868,-167.2125"/>
<text text-anchor="middle" x="884.8454" y="-183.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- diagnosis -->
<g id="node8" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1616.3454,-550.5C1616.3454,-550.5 1930.3454,-550.5 1930.3454,-550.5 1936.3454,-550.5 1942.3454,-556.5 1942.3454,-562.5 1942.3454,-562.5 1942.3454,-699.5 1942.3454,-699.5 1942.3454,-705.5 1936.3454,-711.5 1930.3454,-711.5 1930.3454,-711.5 1616.3454,-711.5 1616.3454,-711.5 1610.3454,-711.5 1604.3454,-705.5 1604.3454,-699.5 1604.3454,-699.5 1604.3454,-562.5 1604.3454,-562.5 1604.3454,-556.5 1610.3454,-550.5 1616.3454,-550.5"/>
<text text-anchor="middle" x="1646.3454" y="-627.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1688.3454,-550.5 1688.3454,-711.5 "/>
<text text-anchor="middle" x="1698.8454" y="-627.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1709.3454,-550.5 1709.3454,-711.5 "/>
<text text-anchor="middle" x="1815.3454" y="-696.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1709.3454,-688.5 1921.3454,-688.5 "/>
<text text-anchor="middle" x="1815.3454" y="-673.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_status</text>
<polyline fill="none" stroke="#000000" points="1709.3454,-665.5 1921.3454,-665.5 "/>
<text text-anchor="middle" x="1815.3454" y="-650.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1709.3454,-642.5 1921.3454,-642.5 "/>
<text text-anchor="middle" x="1815.3454" y="-627.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1709.3454,-619.5 1921.3454,-619.5 "/>
<text text-anchor="middle" x="1815.3454" y="-604.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1709.3454,-596.5 1921.3454,-596.5 "/>
<text text-anchor="middle" x="1815.3454" y="-581.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1709.3454,-573.5 1921.3454,-573.5 "/>
<text text-anchor="middle" x="1815.3454" y="-558.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="1921.3454,-550.5 1921.3454,-711.5 "/>
<text text-anchor="middle" x="1931.8454" y="-627.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;study_subject -->
<g id="edge20" class="edge">
<title>diagnosis&#45;&gt;study_subject</title>
<path fill="none" stroke="#000000" d="M1727.8357,-550.2801C1699.5035,-500.0277 1663.0234,-435.3236 1633.8074,-383.5035"/>
<polygon fill="#000000" stroke="#000000" points="1636.7728,-381.6366 1628.8127,-374.6446 1630.6751,-385.0745 1636.7728,-381.6366"/>
<text text-anchor="middle" x="1749.8454" y="-435.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_subject</text>
</g>
<!-- study_subject&#45;&gt;study -->
<g id="edge5" class="edge">
<title>study_subject&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1429.8054,-216.3655C1426.6397,-215.1995 1423.4842,-214.0757 1420.3454,-213 1249.9743,-154.6103 1045.3051,-118.4548 910.8478,-99.0643"/>
<polygon fill="#000000" stroke="#000000" points="911.2817,-95.5908 900.8869,-97.64 910.2908,-102.5203 911.2817,-95.5908"/>
<text text-anchor="middle" x="1381.8454" y="-183.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- file&#45;&gt;experiment -->
<g id="edge15" class="edge">
<title>file&#45;&gt;experiment</title>
<path fill="none" stroke="#000000" d="M862.9806,-809.2629C835.6552,-723.8642 811.5719,-596.4894 867.3454,-504 868.51,-502.0687 1075.2736,-393.5562 1190.2815,-333.3006"/>
<polygon fill="#000000" stroke="#000000" points="1192.1835,-336.2554 1199.4174,-328.5144 1188.9351,-330.0548 1192.1835,-336.2554"/>
<text text-anchor="middle" x="918.8454" y="-627.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_experiment</text>
</g>
<!-- file&#45;&gt;study_subject -->
<g id="edge16" class="edge">
<title>file&#45;&gt;study_subject</title>
<path fill="none" stroke="#000000" d="M948.2429,-809.2683C956.2116,-792.4603 963.941,-774.8941 970.3454,-758 1011.8122,-648.616 964.1455,-593.6064 1039.3454,-504 1113.8584,-415.2122 1163.9986,-425.2079 1275.3454,-393 1334.8031,-375.8014 1356.1538,-392.0377 1419.7547,-374.8953"/>
<polygon fill="#000000" stroke="#000000" points="1420.8055,-378.2352 1429.4546,-372.116 1418.8773,-371.506 1420.8055,-378.2352"/>
<text text-anchor="middle" x="1110.3454" y="-627.3" font-family="Times,serif" font-size="14.00" fill="#000000">from_study_subject</text>
</g>
<!-- file&#45;&gt;study -->
<g id="edge7" class="edge">
<title>file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M791.6119,-876.9991C592.3673,-824.9386 173.1606,-682.0478 25.3454,-375 -5.8854,-310.126 -10.6172,-275.3754 25.3454,-213 39.9666,-187.6404 54.693,-189.6037 82.3454,-180 179.1001,-146.3971 451.0098,-113.5835 621.4249,-95.4512"/>
<polygon fill="#000000" stroke="#000000" points="621.9105,-98.9194 631.486,-94.3851 621.1729,-91.9584 621.9105,-98.9194"/>
<text text-anchor="middle" x="121.8454" y="-435.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- file&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M994.3342,-809.203C1011.0392,-796.53 1028.9866,-784.8525 1047.3454,-776 1084.4817,-758.0933 1099.6025,-772.0975 1138.3454,-758 1152.4571,-752.8652 1166.7462,-746.9602 1180.9355,-740.5669"/>
<polygon fill="#000000" stroke="#000000" points="1182.6122,-743.6486 1190.2427,-736.2983 1179.6939,-737.2858 1182.6122,-743.6486"/>
<text text-anchor="middle" x="1093.8454" y="-779.8" font-family="Times,serif" font-size="14.00" fill="#000000">from_sample</text>
</g>
<!-- clinical_measure -->
<g id="node13" class="node">
<title>clinical_measure</title>
<path fill="none" stroke="#000000" d="M290.8454,-393.5C290.8454,-393.5 671.8454,-393.5 671.8454,-393.5 677.8454,-393.5 683.8454,-399.5 683.8454,-405.5 683.8454,-405.5 683.8454,-473.5 683.8454,-473.5 683.8454,-479.5 677.8454,-485.5 671.8454,-485.5 671.8454,-485.5 290.8454,-485.5 290.8454,-485.5 284.8454,-485.5 278.8454,-479.5 278.8454,-473.5 278.8454,-473.5 278.8454,-405.5 278.8454,-405.5 278.8454,-399.5 284.8454,-393.5 290.8454,-393.5"/>
<text text-anchor="middle" x="347.3454" y="-435.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure</text>
<polyline fill="none" stroke="#000000" points="415.8454,-393.5 415.8454,-485.5 "/>
<text text-anchor="middle" x="426.3454" y="-435.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="436.8454,-393.5 436.8454,-485.5 "/>
<text text-anchor="middle" x="549.8454" y="-470.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_measure</text>
<polyline fill="none" stroke="#000000" points="436.8454,-462.5 662.8454,-462.5 "/>
<text text-anchor="middle" x="549.8454" y="-447.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_description</text>
<polyline fill="none" stroke="#000000" points="436.8454,-439.5 662.8454,-439.5 "/>
<text text-anchor="middle" x="549.8454" y="-424.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_id</text>
<polyline fill="none" stroke="#000000" points="436.8454,-416.5 662.8454,-416.5 "/>
<text text-anchor="middle" x="549.8454" y="-401.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_measure</text>
<polyline fill="none" stroke="#000000" points="662.8454,-393.5 662.8454,-485.5 "/>
<text text-anchor="middle" x="673.3454" y="-435.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file&#45;&gt;clinical_measure -->
<g id="edge4" class="edge">
<title>file&#45;&gt;clinical_measure</title>
<path fill="none" stroke="#000000" d="M791.7644,-855.8583C759.0453,-838.6666 724.577,-816.891 697.3454,-791 605.7513,-703.9149 537.8033,-569.8849 504.4199,-494.9989"/>
<polygon fill="#000000" stroke="#000000" points="507.5662,-493.4592 500.3271,-485.7232 501.1619,-496.2851 507.5662,-493.4592"/>
<text text-anchor="middle" x="768.3454" y="-779.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure</text>
</g>
<!-- sample&#45;&gt;experiment -->
<g id="edge14" class="edge">
<title>sample&#45;&gt;experiment</title>
<path fill="none" stroke="#000000" d="M1307.7708,-504.4266C1305.4669,-498.2496 1303.308,-492.0864 1301.3454,-486 1285.4852,-436.8145 1275.751,-378.155 1270.4694,-338.7275"/>
<polygon fill="#000000" stroke="#000000" points="1273.918,-338.1046 1269.159,-328.6388 1266.9763,-339.0063 1273.918,-338.1046"/>
<text text-anchor="middle" x="1352.8454" y="-435.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_experiment</text>
</g>
<!-- sample&#45;&gt;study_subject -->
<g id="edge18" class="edge">
<title>sample&#45;&gt;study_subject</title>
<path fill="none" stroke="#000000" d="M1399.7195,-504.2125C1412.4902,-457.8025 1427.5569,-411.9963 1441.3454,-393 1443.999,-389.3442 1446.8305,-385.7764 1449.8099,-382.2989"/>
<polygon fill="#000000" stroke="#000000" points="1452.45,-384.5976 1456.5569,-374.8311 1447.2559,-379.9048 1452.45,-384.5976"/>
<text text-anchor="middle" x="1501.8454" y="-435.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_subject</text>
</g>
<!-- clinical_measure&#45;&gt;study -->
<g id="edge6" class="edge">
<title>clinical_measure&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M278.8003,-420.043C179.696,-408.426 78.3872,-392.5408 63.3454,-375 16.4763,-320.344 17.3708,-268.4106 63.3454,-213 132.8371,-129.2457 436.7173,-98.3015 621.4534,-87.1141"/>
<polygon fill="#000000" stroke="#000000" points="621.7519,-90.6027 631.527,-86.5165 621.3372,-83.615 621.7519,-90.6027"/>
<text text-anchor="middle" x="93.8454" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
</g>
</svg>
</div>
