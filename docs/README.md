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
<svg width="6149pt" height="1821pt"
 viewBox="0.00 0.00 6149.21 1821.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1817)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1817 6145.2141,-1817 6145.2141,4 -4,4"/>
<!-- synonym -->
<g id="node1" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M3000.2141,-1490.5C3000.2141,-1490.5 3301.2141,-1490.5 3301.2141,-1490.5 3307.2141,-1490.5 3313.2141,-1496.5 3313.2141,-1502.5 3313.2141,-1502.5 3313.2141,-1524.5 3313.2141,-1524.5 3313.2141,-1530.5 3307.2141,-1536.5 3301.2141,-1536.5 3301.2141,-1536.5 3000.2141,-1536.5 3000.2141,-1536.5 2994.2141,-1536.5 2988.2141,-1530.5 2988.2141,-1524.5 2988.2141,-1524.5 2988.2141,-1502.5 2988.2141,-1502.5 2988.2141,-1496.5 2994.2141,-1490.5 3000.2141,-1490.5"/>
<text text-anchor="middle" x="3028.2141" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="3068.2141,-1490.5 3068.2141,-1536.5 "/>
<text text-anchor="middle" x="3078.7141" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3089.2141,-1490.5 3089.2141,-1536.5 "/>
<text text-anchor="middle" x="3190.7141" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="3089.2141,-1513.5 3292.2141,-1513.5 "/>
<text text-anchor="middle" x="3190.7141" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="3292.2141,-1490.5 3292.2141,-1536.5 "/>
<text text-anchor="middle" x="3302.7141" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node9" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M1196.7141,-.5C1196.7141,-.5 1586.7141,-.5 1586.7141,-.5 1592.7141,-.5 1598.7141,-6.5 1598.7141,-12.5 1598.7141,-12.5 1598.7141,-287.5 1598.7141,-287.5 1598.7141,-293.5 1592.7141,-299.5 1586.7141,-299.5 1586.7141,-299.5 1196.7141,-299.5 1196.7141,-299.5 1190.7141,-299.5 1184.7141,-293.5 1184.7141,-287.5 1184.7141,-287.5 1184.7141,-12.5 1184.7141,-12.5 1184.7141,-6.5 1190.7141,-.5 1196.7141,-.5"/>
<text text-anchor="middle" x="1212.7141" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="1240.7141,-.5 1240.7141,-299.5 "/>
<text text-anchor="middle" x="1251.2141" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1261.7141,-.5 1261.7141,-299.5 "/>
<text text-anchor="middle" x="1419.7141" y="-284.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="1261.7141,-276.5 1577.7141,-276.5 "/>
<text text-anchor="middle" x="1419.7141" y="-261.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="1261.7141,-253.5 1577.7141,-253.5 "/>
<text text-anchor="middle" x="1419.7141" y="-238.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_number</text>
<polyline fill="none" stroke="#000000" points="1261.7141,-230.5 1577.7141,-230.5 "/>
<text text-anchor="middle" x="1419.7141" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="1261.7141,-207.5 1577.7141,-207.5 "/>
<text text-anchor="middle" x="1419.7141" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="1261.7141,-184.5 1577.7141,-184.5 "/>
<text text-anchor="middle" x="1419.7141" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="1261.7141,-161.5 1577.7141,-161.5 "/>
<text text-anchor="middle" x="1419.7141" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="1261.7141,-138.5 1577.7141,-138.5 "/>
<text text-anchor="middle" x="1419.7141" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="1261.7141,-115.5 1577.7141,-115.5 "/>
<text text-anchor="middle" x="1419.7141" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="1261.7141,-92.5 1577.7141,-92.5 "/>
<text text-anchor="middle" x="1419.7141" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="1261.7141,-69.5 1577.7141,-69.5 "/>
<text text-anchor="middle" x="1419.7141" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="1261.7141,-46.5 1577.7141,-46.5 "/>
<text text-anchor="middle" x="1419.7141" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="1261.7141,-23.5 1577.7141,-23.5 "/>
<text text-anchor="middle" x="1419.7141" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="1577.7141,-.5 1577.7141,-299.5 "/>
<text text-anchor="middle" x="1588.2141" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge4" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2987.9629,-1507.1321C2385.3675,-1481.9118 305.8177,-1379.6633 112.7141,-1163 -64.4175,-964.2573 -7.5338,-801.5178 112.7141,-564 184.9468,-421.3236 257.2623,-417.4672 402.7141,-351 652.799,-236.7187 967.9207,-187.0165 1174.3667,-165.663"/>
<polygon fill="#000000" stroke="#000000" points="1174.8287,-169.1341 1184.4215,-164.6365 1174.1177,-162.1703 1174.8287,-169.1341"/>
<text text-anchor="middle" x="172.2141" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- sample -->
<g id="node12" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M3994.7141,-783C3994.7141,-783 4308.7141,-783 4308.7141,-783 4314.7141,-783 4320.7141,-789 4320.7141,-795 4320.7141,-795 4320.7141,-932 4320.7141,-932 4320.7141,-938 4314.7141,-944 4308.7141,-944 4308.7141,-944 3994.7141,-944 3994.7141,-944 3988.7141,-944 3982.7141,-938 3982.7141,-932 3982.7141,-932 3982.7141,-795 3982.7141,-795 3982.7141,-789 3988.7141,-783 3994.7141,-783"/>
<text text-anchor="middle" x="4016.7141" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="4050.7141,-783 4050.7141,-944 "/>
<text text-anchor="middle" x="4061.2141" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4071.7141,-783 4071.7141,-944 "/>
<text text-anchor="middle" x="4185.7141" y="-928.8" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="4071.7141,-921 4299.7141,-921 "/>
<text text-anchor="middle" x="4185.7141" y="-905.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="4071.7141,-898 4299.7141,-898 "/>
<text text-anchor="middle" x="4185.7141" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="4071.7141,-875 4299.7141,-875 "/>
<text text-anchor="middle" x="4185.7141" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="4071.7141,-852 4299.7141,-852 "/>
<text text-anchor="middle" x="4185.7141" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="4071.7141,-829 4299.7141,-829 "/>
<text text-anchor="middle" x="4185.7141" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="4071.7141,-806 4299.7141,-806 "/>
<text text-anchor="middle" x="4185.7141" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="4299.7141,-783 4299.7141,-944 "/>
<text text-anchor="middle" x="4310.2141" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3156.1488,-1490.4694C3171.1762,-1432.4682 3219.2028,-1280.293 3322.7141,-1214 3360.2922,-1189.9334 3479.4226,-1206.8238 3522.7141,-1196 3713.3151,-1148.3455 3909.8855,-1031.551 4031.4284,-949.9288"/>
<polygon fill="#000000" stroke="#000000" points="4033.7156,-952.6079 4040.0487,-944.1142 4029.8011,-946.8046 4033.7156,-952.6079"/>
<text text-anchor="middle" x="3601.2141" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- participant -->
<g id="node20" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M1706.7141,-374.5C1706.7141,-374.5 2010.7141,-374.5 2010.7141,-374.5 2016.7141,-374.5 2022.7141,-380.5 2022.7141,-386.5 2022.7141,-386.5 2022.7141,-477.5 2022.7141,-477.5 2022.7141,-483.5 2016.7141,-489.5 2010.7141,-489.5 2010.7141,-489.5 1706.7141,-489.5 1706.7141,-489.5 1700.7141,-489.5 1694.7141,-483.5 1694.7141,-477.5 1694.7141,-477.5 1694.7141,-386.5 1694.7141,-386.5 1694.7141,-380.5 1700.7141,-374.5 1706.7141,-374.5"/>
<text text-anchor="middle" x="1742.7141" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1790.7141,-374.5 1790.7141,-489.5 "/>
<text text-anchor="middle" x="1801.2141" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1811.7141,-374.5 1811.7141,-489.5 "/>
<text text-anchor="middle" x="1906.7141" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="1811.7141,-466.5 2001.7141,-466.5 "/>
<text text-anchor="middle" x="1906.7141" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="1811.7141,-443.5 2001.7141,-443.5 "/>
<text text-anchor="middle" x="1906.7141" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="1811.7141,-420.5 2001.7141,-420.5 "/>
<text text-anchor="middle" x="1906.7141" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1811.7141,-397.5 2001.7141,-397.5 "/>
<text text-anchor="middle" x="1906.7141" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="2001.7141,-374.5 2001.7141,-489.5 "/>
<text text-anchor="middle" x="2012.2141" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3157.581,-1490.112C3175.2837,-1433.9085 3227.8567,-1290.2761 3322.7141,-1214 3381.5387,-1166.6984 3440.0665,-1223.8635 3484.7141,-1163 3642.1812,-948.3412 3662.1148,-762.5026 3484.7141,-564 3430.9277,-503.8156 2111.3851,-531.056 2032.7141,-513 2013.0378,-508.484 1992.9291,-501.5688 1973.6948,-493.6429"/>
<polygon fill="#000000" stroke="#000000" points="1974.9017,-490.3531 1964.3285,-489.6769 1972.1723,-496.7991 1974.9017,-490.3531"/>
<text text-anchor="middle" x="3652.2141" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- family_relationship -->
<g id="node2" class="node">
<title>family_relationship</title>
<path fill="none" stroke="#000000" d="M549.2141,-817.5C549.2141,-817.5 918.2141,-817.5 918.2141,-817.5 924.2141,-817.5 930.2141,-823.5 930.2141,-829.5 930.2141,-829.5 930.2141,-897.5 930.2141,-897.5 930.2141,-903.5 924.2141,-909.5 918.2141,-909.5 918.2141,-909.5 549.2141,-909.5 549.2141,-909.5 543.2141,-909.5 537.2141,-903.5 537.2141,-897.5 537.2141,-897.5 537.2141,-829.5 537.2141,-829.5 537.2141,-823.5 543.2141,-817.5 549.2141,-817.5"/>
<text text-anchor="middle" x="614.2141" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
<polyline fill="none" stroke="#000000" points="691.2141,-817.5 691.2141,-909.5 "/>
<text text-anchor="middle" x="701.7141" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="712.2141,-817.5 712.2141,-909.5 "/>
<text text-anchor="middle" x="810.7141" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_id</text>
<polyline fill="none" stroke="#000000" points="712.2141,-886.5 909.2141,-886.5 "/>
<text text-anchor="middle" x="810.7141" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship_id</text>
<polyline fill="none" stroke="#000000" points="712.2141,-863.5 909.2141,-863.5 "/>
<text text-anchor="middle" x="810.7141" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">related_to_participant_id</text>
<polyline fill="none" stroke="#000000" points="712.2141,-840.5 909.2141,-840.5 "/>
<text text-anchor="middle" x="810.7141" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">relationship</text>
<polyline fill="none" stroke="#000000" points="909.2141,-817.5 909.2141,-909.5 "/>
<text text-anchor="middle" x="919.7141" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M750.6052,-817.3033C778.2873,-748.9167 840.283,-622.5359 938.7141,-564 1000.364,-527.3375 1663.8234,-518.0903 1684.7141,-513 1704.05,-508.2886 1723.8346,-501.3666 1742.8062,-493.5219"/>
<polygon fill="#000000" stroke="#000000" points="1744.2088,-496.7289 1752.0487,-489.6024 1741.4758,-490.2844 1744.2088,-496.7289"/>
<text text-anchor="middle" x="1302.2141" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- study_admin -->
<g id="node3" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M713.7141,-351.5C713.7141,-351.5 1039.7141,-351.5 1039.7141,-351.5 1045.7141,-351.5 1051.7141,-357.5 1051.7141,-363.5 1051.7141,-363.5 1051.7141,-500.5 1051.7141,-500.5 1051.7141,-506.5 1045.7141,-512.5 1039.7141,-512.5 1039.7141,-512.5 713.7141,-512.5 713.7141,-512.5 707.7141,-512.5 701.7141,-506.5 701.7141,-500.5 701.7141,-500.5 701.7141,-363.5 701.7141,-363.5 701.7141,-357.5 707.7141,-351.5 713.7141,-351.5"/>
<text text-anchor="middle" x="755.7141" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="809.7141,-351.5 809.7141,-512.5 "/>
<text text-anchor="middle" x="820.2141" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="830.7141,-351.5 830.7141,-512.5 "/>
<text text-anchor="middle" x="930.7141" y="-497.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="830.7141,-489.5 1030.7141,-489.5 "/>
<text text-anchor="middle" x="930.7141" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="830.7141,-466.5 1030.7141,-466.5 "/>
<text text-anchor="middle" x="930.7141" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="830.7141,-443.5 1030.7141,-443.5 "/>
<text text-anchor="middle" x="930.7141" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="830.7141,-420.5 1030.7141,-420.5 "/>
<text text-anchor="middle" x="930.7141" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="830.7141,-397.5 1030.7141,-397.5 "/>
<text text-anchor="middle" x="930.7141" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="830.7141,-374.5 1030.7141,-374.5 "/>
<text text-anchor="middle" x="930.7141" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="1030.7141,-351.5 1030.7141,-512.5 "/>
<text text-anchor="middle" x="1041.2141" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge22" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1023.9478,-351.3789C1071.1576,-325.5281 1124.4638,-296.339 1175.5423,-268.3698"/>
<polygon fill="#000000" stroke="#000000" points="1177.293,-271.4016 1184.3832,-263.5288 1173.931,-265.2618 1177.293,-271.4016"/>
<text text-anchor="middle" x="1130.2141" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- pdx -->
<g id="node4" class="node">
<title>pdx</title>
<path fill="none" stroke="#000000" d="M5800.2141,-1398.5C5800.2141,-1398.5 6129.2141,-1398.5 6129.2141,-1398.5 6135.2141,-1398.5 6141.2141,-1404.5 6141.2141,-1410.5 6141.2141,-1410.5 6141.2141,-1616.5 6141.2141,-1616.5 6141.2141,-1622.5 6135.2141,-1628.5 6129.2141,-1628.5 6129.2141,-1628.5 5800.2141,-1628.5 5800.2141,-1628.5 5794.2141,-1628.5 5788.2141,-1622.5 5788.2141,-1616.5 5788.2141,-1616.5 5788.2141,-1410.5 5788.2141,-1410.5 5788.2141,-1404.5 5794.2141,-1398.5 5800.2141,-1398.5"/>
<text text-anchor="middle" x="5809.7141" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
<polyline fill="none" stroke="#000000" points="5831.2141,-1398.5 5831.2141,-1628.5 "/>
<text text-anchor="middle" x="5841.7141" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="5852.2141,-1398.5 5852.2141,-1628.5 "/>
<text text-anchor="middle" x="5986.2141" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_site</text>
<polyline fill="none" stroke="#000000" points="5852.2141,-1605.5 6120.2141,-1605.5 "/>
<text text-anchor="middle" x="5986.2141" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_type</text>
<polyline fill="none" stroke="#000000" points="5852.2141,-1582.5 6120.2141,-1582.5 "/>
<text text-anchor="middle" x="5986.2141" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_id</text>
<polyline fill="none" stroke="#000000" points="5852.2141,-1559.5 6120.2141,-1559.5 "/>
<text text-anchor="middle" x="5986.2141" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">mouse_strain</text>
<polyline fill="none" stroke="#000000" points="5852.2141,-1536.5 6120.2141,-1536.5 "/>
<text text-anchor="middle" x="5986.2141" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx_id</text>
<polyline fill="none" stroke="#000000" points="5852.2141,-1513.5 6120.2141,-1513.5 "/>
<text text-anchor="middle" x="5986.2141" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">strain_immune_system_humanized</text>
<polyline fill="none" stroke="#000000" points="5852.2141,-1490.5 6120.2141,-1490.5 "/>
<text text-anchor="middle" x="5986.2141" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_characterization_method</text>
<polyline fill="none" stroke="#000000" points="5852.2141,-1467.5 6120.2141,-1467.5 "/>
<text text-anchor="middle" x="5986.2141" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_not_mus_or_ebv_origin</text>
<polyline fill="none" stroke="#000000" points="5852.2141,-1444.5 6120.2141,-1444.5 "/>
<text text-anchor="middle" x="5986.2141" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_preparation</text>
<polyline fill="none" stroke="#000000" points="5852.2141,-1421.5 6120.2141,-1421.5 "/>
<text text-anchor="middle" x="5986.2141" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_humanization</text>
<polyline fill="none" stroke="#000000" points="6120.2141,-1398.5 6120.2141,-1628.5 "/>
<text text-anchor="middle" x="6130.7141" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M5920.4977,-1398.3345C5890.2312,-1334.5801 5843.8698,-1259.2959 5779.7141,-1214 5546.3978,-1049.2714 4703.5236,-930.0393 4330.9439,-884.1957"/>
<polygon fill="#000000" stroke="#000000" points="4331.2249,-880.7041 4320.8731,-882.9604 4330.3726,-887.652 4331.2249,-880.7041"/>
<text text-anchor="middle" x="5761.7141" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study_personnel -->
<g id="node5" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M1082.2141,-374.5C1082.2141,-374.5 1389.2141,-374.5 1389.2141,-374.5 1395.2141,-374.5 1401.2141,-380.5 1401.2141,-386.5 1401.2141,-386.5 1401.2141,-477.5 1401.2141,-477.5 1401.2141,-483.5 1395.2141,-489.5 1389.2141,-489.5 1389.2141,-489.5 1082.2141,-489.5 1082.2141,-489.5 1076.2141,-489.5 1070.2141,-483.5 1070.2141,-477.5 1070.2141,-477.5 1070.2141,-386.5 1070.2141,-386.5 1070.2141,-380.5 1076.2141,-374.5 1082.2141,-374.5"/>
<text text-anchor="middle" x="1137.2141" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="1204.2141,-374.5 1204.2141,-489.5 "/>
<text text-anchor="middle" x="1214.7141" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1225.2141,-374.5 1225.2141,-489.5 "/>
<text text-anchor="middle" x="1302.7141" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="1225.2141,-466.5 1380.2141,-466.5 "/>
<text text-anchor="middle" x="1302.7141" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="1225.2141,-443.5 1380.2141,-443.5 "/>
<text text-anchor="middle" x="1302.7141" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="1225.2141,-420.5 1380.2141,-420.5 "/>
<text text-anchor="middle" x="1302.7141" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="1225.2141,-397.5 1380.2141,-397.5 "/>
<text text-anchor="middle" x="1302.7141" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="1380.2141,-374.5 1380.2141,-489.5 "/>
<text text-anchor="middle" x="1390.7141" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1267.6595,-374.2526C1278.4093,-354.8203 1290.9773,-332.1012 1303.9107,-308.7217"/>
<polygon fill="#000000" stroke="#000000" points="1307.1043,-310.179 1308.8824,-299.7344 1300.9791,-306.7905 1307.1043,-310.179"/>
<text text-anchor="middle" x="1365.2141" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- imaging_file -->
<g id="node6" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M3343.2141,-1318C3343.2141,-1318 3684.2141,-1318 3684.2141,-1318 3690.2141,-1318 3696.2141,-1324 3696.2141,-1330 3696.2141,-1330 3696.2141,-1697 3696.2141,-1697 3696.2141,-1703 3690.2141,-1709 3684.2141,-1709 3684.2141,-1709 3343.2141,-1709 3343.2141,-1709 3337.2141,-1709 3331.2141,-1703 3331.2141,-1697 3331.2141,-1697 3331.2141,-1330 3331.2141,-1330 3331.2141,-1324 3337.2141,-1318 3343.2141,-1318"/>
<text text-anchor="middle" x="3383.2141" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="3435.2141,-1318 3435.2141,-1709 "/>
<text text-anchor="middle" x="3445.7141" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3456.2141,-1318 3456.2141,-1709 "/>
<text text-anchor="middle" x="3565.7141" y="-1693.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="3456.2141,-1686 3675.2141,-1686 "/>
<text text-anchor="middle" x="3565.7141" y="-1670.8" font-family="Times,serif" font-size="14.00" fill="#000000">deidentification_method</text>
<polyline fill="none" stroke="#000000" points="3456.2141,-1663 3675.2141,-1663 "/>
<text text-anchor="middle" x="3565.7141" y="-1647.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="3456.2141,-1640 3675.2141,-1640 "/>
<text text-anchor="middle" x="3565.7141" y="-1624.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="3456.2141,-1617 3675.2141,-1617 "/>
<text text-anchor="middle" x="3565.7141" y="-1601.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="3456.2141,-1594 3675.2141,-1594 "/>
<text text-anchor="middle" x="3565.7141" y="-1578.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="3456.2141,-1571 3675.2141,-1571 "/>
<text text-anchor="middle" x="3565.7141" y="-1555.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="3456.2141,-1548 3675.2141,-1548 "/>
<text text-anchor="middle" x="3565.7141" y="-1532.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="3456.2141,-1525 3675.2141,-1525 "/>
<text text-anchor="middle" x="3565.7141" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">fixation_embedding_method</text>
<polyline fill="none" stroke="#000000" points="3456.2141,-1502 3675.2141,-1502 "/>
<text text-anchor="middle" x="3565.7141" y="-1486.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="3456.2141,-1479 3675.2141,-1479 "/>
<text text-anchor="middle" x="3565.7141" y="-1463.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file_id</text>
<polyline fill="none" stroke="#000000" points="3456.2141,-1456 3675.2141,-1456 "/>
<text text-anchor="middle" x="3565.7141" y="-1440.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="3456.2141,-1433 3675.2141,-1433 "/>
<text text-anchor="middle" x="3565.7141" y="-1417.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="3456.2141,-1410 3675.2141,-1410 "/>
<text text-anchor="middle" x="3565.7141" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">magnification</text>
<polyline fill="none" stroke="#000000" points="3456.2141,-1387 3675.2141,-1387 "/>
<text text-anchor="middle" x="3565.7141" y="-1371.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="3456.2141,-1364 3675.2141,-1364 "/>
<text text-anchor="middle" x="3565.7141" y="-1348.8" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="3456.2141,-1341 3675.2141,-1341 "/>
<text text-anchor="middle" x="3565.7141" y="-1325.8" font-family="Times,serif" font-size="14.00" fill="#000000">staining_method</text>
<polyline fill="none" stroke="#000000" points="3675.2141,-1318 3675.2141,-1709 "/>
<text text-anchor="middle" x="3685.7141" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3625.7853,-1317.6483C3650.1008,-1281.5814 3677.1638,-1245.4316 3705.7141,-1214 3799.073,-1111.2195 3924.8834,-1015.3342 4019.0801,-949.9261"/>
<polygon fill="#000000" stroke="#000000" points="4021.2876,-952.655 4027.5208,-944.0878 4017.3055,-946.8979 4021.2876,-952.655"/>
<text text-anchor="middle" x="3780.2141" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- therapeutic_procedure -->
<g id="node7" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M960.2141,-794.5C960.2141,-794.5 1361.2141,-794.5 1361.2141,-794.5 1367.2141,-794.5 1373.2141,-800.5 1373.2141,-806.5 1373.2141,-806.5 1373.2141,-920.5 1373.2141,-920.5 1373.2141,-926.5 1367.2141,-932.5 1361.2141,-932.5 1361.2141,-932.5 960.2141,-932.5 960.2141,-932.5 954.2141,-932.5 948.2141,-926.5 948.2141,-920.5 948.2141,-920.5 948.2141,-806.5 948.2141,-806.5 948.2141,-800.5 954.2141,-794.5 960.2141,-794.5"/>
<text text-anchor="middle" x="1038.7141" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="1129.2141,-794.5 1129.2141,-932.5 "/>
<text text-anchor="middle" x="1139.7141" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1150.2141,-794.5 1150.2141,-932.5 "/>
<text text-anchor="middle" x="1251.2141" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment_end</text>
<polyline fill="none" stroke="#000000" points="1150.2141,-909.5 1352.2141,-909.5 "/>
<text text-anchor="middle" x="1251.2141" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment_start</text>
<polyline fill="none" stroke="#000000" points="1150.2141,-886.5 1352.2141,-886.5 "/>
<text text-anchor="middle" x="1251.2141" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="1150.2141,-863.5 1352.2141,-863.5 "/>
<text text-anchor="middle" x="1251.2141" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure_id</text>
<polyline fill="none" stroke="#000000" points="1150.2141,-840.5 1352.2141,-840.5 "/>
<text text-anchor="middle" x="1251.2141" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="1150.2141,-817.5 1352.2141,-817.5 "/>
<text text-anchor="middle" x="1251.2141" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1352.2141,-794.5 1352.2141,-932.5 "/>
<text text-anchor="middle" x="1362.7141" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1192.3743,-794.1842C1228.1736,-724.1898 1293.3317,-618.8146 1382.7141,-564 1498.7541,-492.8374 1554.7312,-553.4206 1684.7141,-513 1701.896,-507.657 1719.5713,-500.964 1736.7674,-493.7283"/>
<polygon fill="#000000" stroke="#000000" points="1738.4526,-496.814 1746.2653,-489.6577 1735.6951,-490.38 1738.4526,-496.814"/>
<text text-anchor="middle" x="1556.7141" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- methylation_array_file -->
<g id="node8" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M3726.2141,-1387C3726.2141,-1387 4121.2141,-1387 4121.2141,-1387 4127.2141,-1387 4133.2141,-1393 4133.2141,-1399 4133.2141,-1399 4133.2141,-1628 4133.2141,-1628 4133.2141,-1634 4127.2141,-1640 4121.2141,-1640 4121.2141,-1640 3726.2141,-1640 3726.2141,-1640 3720.2141,-1640 3714.2141,-1634 3714.2141,-1628 3714.2141,-1628 3714.2141,-1399 3714.2141,-1399 3714.2141,-1393 3720.2141,-1387 3726.2141,-1387"/>
<text text-anchor="middle" x="3803.2141" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="3892.2141,-1387 3892.2141,-1640 "/>
<text text-anchor="middle" x="3902.7141" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3913.2141,-1387 3913.2141,-1640 "/>
<text text-anchor="middle" x="4012.7141" y="-1624.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="3913.2141,-1617 4112.2141,-1617 "/>
<text text-anchor="middle" x="4012.7141" y="-1601.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="3913.2141,-1594 4112.2141,-1594 "/>
<text text-anchor="middle" x="4012.7141" y="-1578.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="3913.2141,-1571 4112.2141,-1571 "/>
<text text-anchor="middle" x="4012.7141" y="-1555.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="3913.2141,-1548 4112.2141,-1548 "/>
<text text-anchor="middle" x="4012.7141" y="-1532.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="3913.2141,-1525 4112.2141,-1525 "/>
<text text-anchor="middle" x="4012.7141" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="3913.2141,-1502 4112.2141,-1502 "/>
<text text-anchor="middle" x="4012.7141" y="-1486.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="3913.2141,-1479 4112.2141,-1479 "/>
<text text-anchor="middle" x="4012.7141" y="-1463.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="3913.2141,-1456 4112.2141,-1456 "/>
<text text-anchor="middle" x="4012.7141" y="-1440.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file_id</text>
<polyline fill="none" stroke="#000000" points="3913.2141,-1433 4112.2141,-1433 "/>
<text text-anchor="middle" x="4012.7141" y="-1417.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="3913.2141,-1410 4112.2141,-1410 "/>
<text text-anchor="middle" x="4012.7141" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="4112.2141,-1387 4112.2141,-1640 "/>
<text text-anchor="middle" x="4122.7141" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3968.2161,-1386.6304C4012.8561,-1259.3672 4080.4867,-1066.5608 4119.9677,-954.0053"/>
<polygon fill="#000000" stroke="#000000" points="4123.3395,-954.9667 4123.3468,-944.3718 4116.734,-952.6497 4123.3395,-954.9667"/>
<text text-anchor="middle" x="4129.2141" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- diagnosis -->
<g id="node10" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1403.7141,-668C1403.7141,-668 1777.7141,-668 1777.7141,-668 1783.7141,-668 1789.7141,-674 1789.7141,-680 1789.7141,-680 1789.7141,-1047 1789.7141,-1047 1789.7141,-1053 1783.7141,-1059 1777.7141,-1059 1777.7141,-1059 1403.7141,-1059 1403.7141,-1059 1397.7141,-1059 1391.7141,-1053 1391.7141,-1047 1391.7141,-1047 1391.7141,-680 1391.7141,-680 1391.7141,-674 1397.7141,-668 1403.7141,-668"/>
<text text-anchor="middle" x="1433.7141" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1475.7141,-668 1475.7141,-1059 "/>
<text text-anchor="middle" x="1486.2141" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1496.7141,-668 1496.7141,-1059 "/>
<text text-anchor="middle" x="1632.7141" y="-1043.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1496.7141,-1036 1768.7141,-1036 "/>
<text text-anchor="middle" x="1632.7141" y="-1020.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1496.7141,-1013 1768.7141,-1013 "/>
<text text-anchor="middle" x="1632.7141" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1496.7141,-990 1768.7141,-990 "/>
<text text-anchor="middle" x="1632.7141" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1496.7141,-967 1768.7141,-967 "/>
<text text-anchor="middle" x="1632.7141" y="-951.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1496.7141,-944 1768.7141,-944 "/>
<text text-anchor="middle" x="1632.7141" y="-928.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="1496.7141,-921 1768.7141,-921 "/>
<text text-anchor="middle" x="1632.7141" y="-905.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="1496.7141,-898 1768.7141,-898 "/>
<text text-anchor="middle" x="1632.7141" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="1496.7141,-875 1768.7141,-875 "/>
<text text-anchor="middle" x="1632.7141" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1496.7141,-852 1768.7141,-852 "/>
<text text-anchor="middle" x="1632.7141" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="1496.7141,-829 1768.7141,-829 "/>
<text text-anchor="middle" x="1632.7141" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1496.7141,-806 1768.7141,-806 "/>
<text text-anchor="middle" x="1632.7141" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="1496.7141,-783 1768.7141,-783 "/>
<text text-anchor="middle" x="1632.7141" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1496.7141,-760 1768.7141,-760 "/>
<text text-anchor="middle" x="1632.7141" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1496.7141,-737 1768.7141,-737 "/>
<text text-anchor="middle" x="1632.7141" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1496.7141,-714 1768.7141,-714 "/>
<text text-anchor="middle" x="1632.7141" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1496.7141,-691 1768.7141,-691 "/>
<text text-anchor="middle" x="1632.7141" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="1768.7141,-668 1768.7141,-1059 "/>
<text text-anchor="middle" x="1779.2141" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1712.168,-667.9502C1750.0299,-606.9898 1789.2395,-543.8594 1817.5632,-498.2561"/>
<polygon fill="#000000" stroke="#000000" points="1820.5977,-500.004 1822.9006,-489.6625 1814.6513,-496.3107 1820.5977,-500.004"/>
<text text-anchor="middle" x="1839.2141" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- sample_diagnosis -->
<g id="node11" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M4163.2141,-1364C4163.2141,-1364 4596.2141,-1364 4596.2141,-1364 4602.2141,-1364 4608.2141,-1370 4608.2141,-1376 4608.2141,-1376 4608.2141,-1651 4608.2141,-1651 4608.2141,-1657 4602.2141,-1663 4596.2141,-1663 4596.2141,-1663 4163.2141,-1663 4163.2141,-1663 4157.2141,-1663 4151.2141,-1657 4151.2141,-1651 4151.2141,-1651 4151.2141,-1376 4151.2141,-1376 4151.2141,-1370 4157.2141,-1364 4163.2141,-1364"/>
<text text-anchor="middle" x="4222.7141" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="4294.2141,-1364 4294.2141,-1663 "/>
<text text-anchor="middle" x="4304.7141" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4315.2141,-1364 4315.2141,-1663 "/>
<text text-anchor="middle" x="4451.2141" y="-1647.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="4315.2141,-1640 4587.2141,-1640 "/>
<text text-anchor="middle" x="4451.2141" y="-1624.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="4315.2141,-1617 4587.2141,-1617 "/>
<text text-anchor="middle" x="4451.2141" y="-1601.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="4315.2141,-1594 4587.2141,-1594 "/>
<text text-anchor="middle" x="4451.2141" y="-1578.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="4315.2141,-1571 4587.2141,-1571 "/>
<text text-anchor="middle" x="4451.2141" y="-1555.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="4315.2141,-1548 4587.2141,-1548 "/>
<text text-anchor="middle" x="4451.2141" y="-1532.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="4315.2141,-1525 4587.2141,-1525 "/>
<text text-anchor="middle" x="4451.2141" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="4315.2141,-1502 4587.2141,-1502 "/>
<text text-anchor="middle" x="4451.2141" y="-1486.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="4315.2141,-1479 4587.2141,-1479 "/>
<text text-anchor="middle" x="4451.2141" y="-1463.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="4315.2141,-1456 4587.2141,-1456 "/>
<text text-anchor="middle" x="4451.2141" y="-1440.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="4315.2141,-1433 4587.2141,-1433 "/>
<text text-anchor="middle" x="4451.2141" y="-1417.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="4315.2141,-1410 4587.2141,-1410 "/>
<text text-anchor="middle" x="4451.2141" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="4315.2141,-1387 4587.2141,-1387 "/>
<text text-anchor="middle" x="4451.2141" y="-1371.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="4587.2141,-1364 4587.2141,-1663 "/>
<text text-anchor="middle" x="4597.7141" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M4327.2633,-1363.969C4282.8257,-1237.2828 4220.5682,-1059.7945 4183.3756,-953.7629"/>
<polygon fill="#000000" stroke="#000000" points="4186.5796,-952.3229 4179.9669,-944.0451 4179.9742,-954.64 4186.5796,-952.3229"/>
<text text-anchor="middle" x="4339.7141" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M4044.7911,-782.8552C3925.6231,-698.9216 3723.5607,-573.8487 3525.7141,-531 3363.5722,-495.8841 2194.4751,-549.8307 2032.7141,-513 2012.8904,-508.4864 1992.6319,-501.523 1973.272,-493.534"/>
<polygon fill="#000000" stroke="#000000" points="1974.4189,-490.2187 1963.8461,-489.536 1971.6855,-496.663 1974.4189,-490.2187"/>
<text text-anchor="middle" x="3617.2141" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- publication -->
<g id="node13" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M1431.2141,-409C1431.2141,-409 1664.2141,-409 1664.2141,-409 1670.2141,-409 1676.2141,-415 1676.2141,-421 1676.2141,-421 1676.2141,-443 1676.2141,-443 1676.2141,-449 1670.2141,-455 1664.2141,-455 1664.2141,-455 1431.2141,-455 1431.2141,-455 1425.2141,-455 1419.2141,-449 1419.2141,-443 1419.2141,-443 1419.2141,-421 1419.2141,-421 1419.2141,-415 1425.2141,-409 1431.2141,-409"/>
<text text-anchor="middle" x="1467.7141" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="1516.2141,-409 1516.2141,-455 "/>
<text text-anchor="middle" x="1526.7141" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1537.2141,-409 1537.2141,-455 "/>
<text text-anchor="middle" x="1596.2141" y="-439.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication_id</text>
<polyline fill="none" stroke="#000000" points="1537.2141,-432 1655.2141,-432 "/>
<text text-anchor="middle" x="1596.2141" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="1655.2141,-409 1655.2141,-455 "/>
<text text-anchor="middle" x="1665.7141" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge9" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1534.948,-408.9228C1522.1956,-385.8704 1501.3926,-348.2649 1479.5439,-308.7692"/>
<polygon fill="#000000" stroke="#000000" points="1482.475,-306.8372 1474.5718,-299.7811 1476.3498,-310.2257 1482.475,-306.8372"/>
<text text-anchor="middle" x="1544.7141" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- follow_up -->
<g id="node14" class="node">
<title>follow_up</title>
<path fill="none" stroke="#000000" d="M1820.2141,-760C1820.2141,-760 2183.2141,-760 2183.2141,-760 2189.2141,-760 2195.2141,-766 2195.2141,-772 2195.2141,-772 2195.2141,-955 2195.2141,-955 2195.2141,-961 2189.2141,-967 2183.2141,-967 2183.2141,-967 1820.2141,-967 1820.2141,-967 1814.2141,-967 1808.2141,-961 1808.2141,-955 1808.2141,-955 1808.2141,-772 1808.2141,-772 1808.2141,-766 1814.2141,-760 1820.2141,-760"/>
<text text-anchor="middle" x="1850.7141" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
<polyline fill="none" stroke="#000000" points="1893.2141,-760 1893.2141,-967 "/>
<text text-anchor="middle" x="1903.7141" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1914.2141,-760 1914.2141,-967 "/>
<text text-anchor="middle" x="2044.2141" y="-951.8" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event</text>
<polyline fill="none" stroke="#000000" points="1914.2141,-944 2174.2141,-944 "/>
<text text-anchor="middle" x="2044.2141" y="-928.8" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity</text>
<polyline fill="none" stroke="#000000" points="1914.2141,-921 2174.2141,-921 "/>
<text text-anchor="middle" x="2044.2141" y="-905.8" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity_method_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1914.2141,-898 2174.2141,-898 "/>
<text text-anchor="middle" x="2044.2141" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_follow_up</text>
<polyline fill="none" stroke="#000000" points="1914.2141,-875 2174.2141,-875 "/>
<text text-anchor="middle" x="2044.2141" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_response</text>
<polyline fill="none" stroke="#000000" points="1914.2141,-852 2174.2141,-852 "/>
<text text-anchor="middle" x="2044.2141" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_category</text>
<polyline fill="none" stroke="#000000" points="1914.2141,-829 2174.2141,-829 "/>
<text text-anchor="middle" x="2044.2141" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_id</text>
<polyline fill="none" stroke="#000000" points="1914.2141,-806 2174.2141,-806 "/>
<text text-anchor="middle" x="2044.2141" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_other</text>
<polyline fill="none" stroke="#000000" points="1914.2141,-783 2174.2141,-783 "/>
<text text-anchor="middle" x="2044.2141" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">risk_factor</text>
<polyline fill="none" stroke="#000000" points="2174.2141,-760 2174.2141,-967 "/>
<text text-anchor="middle" x="2184.7141" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1967.3711,-759.8706C1940.5766,-679.0185 1904.1412,-569.0752 1881.0224,-499.3148"/>
<polygon fill="#000000" stroke="#000000" points="1884.3192,-498.1365 1877.851,-489.7452 1877.6745,-500.3385 1884.3192,-498.1365"/>
<text text-anchor="middle" x="1937.7141" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- clinical_measure_file -->
<g id="node15" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M134.2141,-725.5C134.2141,-725.5 507.2141,-725.5 507.2141,-725.5 513.2141,-725.5 519.2141,-731.5 519.2141,-737.5 519.2141,-737.5 519.2141,-989.5 519.2141,-989.5 519.2141,-995.5 513.2141,-1001.5 507.2141,-1001.5 507.2141,-1001.5 134.2141,-1001.5 134.2141,-1001.5 128.2141,-1001.5 122.2141,-995.5 122.2141,-989.5 122.2141,-989.5 122.2141,-737.5 122.2141,-737.5 122.2141,-731.5 128.2141,-725.5 134.2141,-725.5"/>
<text text-anchor="middle" x="205.7141" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="289.2141,-725.5 289.2141,-1001.5 "/>
<text text-anchor="middle" x="299.7141" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="310.2141,-725.5 310.2141,-1001.5 "/>
<text text-anchor="middle" x="404.2141" y="-986.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="310.2141,-978.5 498.2141,-978.5 "/>
<text text-anchor="middle" x="404.2141" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="310.2141,-955.5 498.2141,-955.5 "/>
<text text-anchor="middle" x="404.2141" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file_id</text>
<polyline fill="none" stroke="#000000" points="310.2141,-932.5 498.2141,-932.5 "/>
<text text-anchor="middle" x="404.2141" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="310.2141,-909.5 498.2141,-909.5 "/>
<text text-anchor="middle" x="404.2141" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="310.2141,-886.5 498.2141,-886.5 "/>
<text text-anchor="middle" x="404.2141" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="310.2141,-863.5 498.2141,-863.5 "/>
<text text-anchor="middle" x="404.2141" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="310.2141,-840.5 498.2141,-840.5 "/>
<text text-anchor="middle" x="404.2141" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="310.2141,-817.5 498.2141,-817.5 "/>
<text text-anchor="middle" x="404.2141" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="310.2141,-794.5 498.2141,-794.5 "/>
<text text-anchor="middle" x="404.2141" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="310.2141,-771.5 498.2141,-771.5 "/>
<text text-anchor="middle" x="404.2141" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="310.2141,-748.5 498.2141,-748.5 "/>
<text text-anchor="middle" x="404.2141" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="498.2141,-725.5 498.2141,-1001.5 "/>
<text text-anchor="middle" x="508.7141" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge20" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M338.5379,-725.4796C360.966,-608.8108 410.8799,-445.9348 520.7141,-351 617.3152,-267.5033 949.6049,-208.2995 1174.6743,-176.6571"/>
<polygon fill="#000000" stroke="#000000" points="1175.2206,-180.1148 1184.6398,-175.2642 1174.2516,-173.1822 1175.2206,-180.1148"/>
<text text-anchor="middle" x="606.7141" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M383.7251,-725.1576C417.8538,-665.9535 465.8486,-601.8587 527.7141,-564 622.5583,-505.9601 664.8417,-539.4474 775.7141,-531 876.442,-523.3255 1586.3028,-535.808 1684.7141,-513 1704.3808,-508.442 1724.4844,-501.5047 1743.7165,-493.5695"/>
<polygon fill="#000000" stroke="#000000" points="1745.2408,-496.7249 1753.082,-489.5999 1742.509,-490.2799 1745.2408,-496.7249"/>
<text text-anchor="middle" x="905.2141" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- molecular_test -->
<g id="node16" class="node">
<title>molecular_test</title>
<path fill="none" stroke="#000000" d="M2225.7141,-564.5C2225.7141,-564.5 2613.7141,-564.5 2613.7141,-564.5 2619.7141,-564.5 2625.7141,-570.5 2625.7141,-576.5 2625.7141,-576.5 2625.7141,-1150.5 2625.7141,-1150.5 2625.7141,-1156.5 2619.7141,-1162.5 2613.7141,-1162.5 2613.7141,-1162.5 2225.7141,-1162.5 2225.7141,-1162.5 2219.7141,-1162.5 2213.7141,-1156.5 2213.7141,-1150.5 2213.7141,-1150.5 2213.7141,-576.5 2213.7141,-576.5 2213.7141,-570.5 2219.7141,-564.5 2225.7141,-564.5"/>
<text text-anchor="middle" x="2275.2141" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
<polyline fill="none" stroke="#000000" points="2336.7141,-564.5 2336.7141,-1162.5 "/>
<text text-anchor="middle" x="2347.2141" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2357.7141,-564.5 2357.7141,-1162.5 "/>
<text text-anchor="middle" x="2481.2141" y="-1147.3" font-family="Times,serif" font-size="14.00" fill="#000000">aa_change</text>
<polyline fill="none" stroke="#000000" points="2357.7141,-1139.5 2604.7141,-1139.5 "/>
<text text-anchor="middle" x="2481.2141" y="-1124.3" font-family="Times,serif" font-size="14.00" fill="#000000">antigen</text>
<polyline fill="none" stroke="#000000" points="2357.7141,-1116.5 2604.7141,-1116.5 "/>
<text text-anchor="middle" x="2481.2141" y="-1101.3" font-family="Times,serif" font-size="14.00" fill="#000000">biospecimen_type</text>
<polyline fill="none" stroke="#000000" points="2357.7141,-1093.5 2604.7141,-1093.5 "/>
<text text-anchor="middle" x="2481.2141" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000">blood_test_normal_range_lower</text>
<polyline fill="none" stroke="#000000" points="2357.7141,-1070.5 2604.7141,-1070.5 "/>
<text text-anchor="middle" x="2481.2141" y="-1055.3" font-family="Times,serif" font-size="14.00" fill="#000000">blood_test_normal_range_upper</text>
<polyline fill="none" stroke="#000000" points="2357.7141,-1047.5 2604.7141,-1047.5 "/>
<text text-anchor="middle" x="2481.2141" y="-1032.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_count</text>
<polyline fill="none" stroke="#000000" points="2357.7141,-1024.5 2604.7141,-1024.5 "/>
<text text-anchor="middle" x="2481.2141" y="-1009.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome</text>
<polyline fill="none" stroke="#000000" points="2357.7141,-1001.5 2604.7141,-1001.5 "/>
<text text-anchor="middle" x="2481.2141" y="-986.3" font-family="Times,serif" font-size="14.00" fill="#000000">copy_number</text>
<polyline fill="none" stroke="#000000" points="2357.7141,-978.5 2604.7141,-978.5 "/>
<text text-anchor="middle" x="2481.2141" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytoband</text>
<polyline fill="none" stroke="#000000" points="2357.7141,-955.5 2604.7141,-955.5 "/>
<text text-anchor="middle" x="2481.2141" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">exon</text>
<polyline fill="none" stroke="#000000" points="2357.7141,-932.5 2604.7141,-932.5 "/>
<text text-anchor="middle" x="2481.2141" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">gene_symbol</text>
<polyline fill="none" stroke="#000000" points="2357.7141,-909.5 2604.7141,-909.5 "/>
<text text-anchor="middle" x="2481.2141" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">histone_family</text>
<polyline fill="none" stroke="#000000" points="2357.7141,-886.5 2604.7141,-886.5 "/>
<text text-anchor="middle" x="2481.2141" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">histone_variant</text>
<polyline fill="none" stroke="#000000" points="2357.7141,-863.5 2604.7141,-863.5 "/>
<text text-anchor="middle" x="2481.2141" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">intron</text>
<polyline fill="none" stroke="#000000" points="2357.7141,-840.5 2604.7141,-840.5 "/>
<text text-anchor="middle" x="2481.2141" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
<polyline fill="none" stroke="#000000" points="2357.7141,-817.5 2604.7141,-817.5 "/>
<text text-anchor="middle" x="2481.2141" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">loci_abnormal_count</text>
<polyline fill="none" stroke="#000000" points="2357.7141,-794.5 2604.7141,-794.5 "/>
<text text-anchor="middle" x="2481.2141" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">loci_count</text>
<polyline fill="none" stroke="#000000" points="2357.7141,-771.5 2604.7141,-771.5 "/>
<text text-anchor="middle" x="2481.2141" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">locus</text>
<polyline fill="none" stroke="#000000" points="2357.7141,-748.5 2604.7141,-748.5 "/>
<text text-anchor="middle" x="2481.2141" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">mismatch_repair_mutation</text>
<polyline fill="none" stroke="#000000" points="2357.7141,-725.5 2604.7141,-725.5 "/>
<text text-anchor="middle" x="2481.2141" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_analysis_method</text>
<polyline fill="none" stroke="#000000" points="2357.7141,-702.5 2604.7141,-702.5 "/>
<text text-anchor="middle" x="2481.2141" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_consequence</text>
<polyline fill="none" stroke="#000000" points="2357.7141,-679.5 2604.7141,-679.5 "/>
<text text-anchor="middle" x="2481.2141" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test_id</text>
<polyline fill="none" stroke="#000000" points="2357.7141,-656.5 2604.7141,-656.5 "/>
<text text-anchor="middle" x="2481.2141" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathogenicity</text>
<polyline fill="none" stroke="#000000" points="2357.7141,-633.5 2604.7141,-633.5 "/>
<text text-anchor="middle" x="2481.2141" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">ploidy</text>
<polyline fill="none" stroke="#000000" points="2357.7141,-610.5 2604.7141,-610.5 "/>
<text text-anchor="middle" x="2481.2141" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">second_exon</text>
<polyline fill="none" stroke="#000000" points="2357.7141,-587.5 2604.7141,-587.5 "/>
<text text-anchor="middle" x="2481.2141" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 11 properties</text>
<polyline fill="none" stroke="#000000" points="2604.7141,-564.5 2604.7141,-1162.5 "/>
<text text-anchor="middle" x="2615.2141" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2213.6326,-570.5616C2210.6863,-568.3215 2207.7133,-566.1331 2204.7141,-564 2139.7378,-517.7874 2107.2816,-541.2351 2032.7141,-513 2017.345,-507.1804 2001.4394,-500.5968 1985.7746,-493.7594"/>
<polygon fill="#000000" stroke="#000000" points="1987.1473,-490.5396 1976.5851,-489.7082 1984.3235,-496.9448 1987.1473,-490.5396"/>
<text text-anchor="middle" x="2235.7141" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- exposure -->
<g id="node17" class="node">
<title>exposure</title>
<path fill="none" stroke="#000000" d="M2656.2141,-622C2656.2141,-622 3067.2141,-622 3067.2141,-622 3073.2141,-622 3079.2141,-628 3079.2141,-634 3079.2141,-634 3079.2141,-1093 3079.2141,-1093 3079.2141,-1099 3073.2141,-1105 3067.2141,-1105 3067.2141,-1105 2656.2141,-1105 2656.2141,-1105 2650.2141,-1105 2644.2141,-1099 2644.2141,-1093 2644.2141,-1093 2644.2141,-634 2644.2141,-634 2644.2141,-628 2650.2141,-622 2656.2141,-622"/>
<text text-anchor="middle" x="2685.2141" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
<polyline fill="none" stroke="#000000" points="2726.2141,-622 2726.2141,-1105 "/>
<text text-anchor="middle" x="2736.7141" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2747.2141,-622 2747.2141,-1105 "/>
<text text-anchor="middle" x="2902.7141" y="-1089.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_days_per_week</text>
<polyline fill="none" stroke="#000000" points="2747.2141,-1082 3058.2141,-1082 "/>
<text text-anchor="middle" x="2902.7141" y="-1066.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_drinks_per_day</text>
<polyline fill="none" stroke="#000000" points="2747.2141,-1059 3058.2141,-1059 "/>
<text text-anchor="middle" x="2902.7141" y="-1043.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_history</text>
<polyline fill="none" stroke="#000000" points="2747.2141,-1036 3058.2141,-1036 "/>
<text text-anchor="middle" x="2902.7141" y="-1020.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_intensity</text>
<polyline fill="none" stroke="#000000" points="2747.2141,-1013 3058.2141,-1013 "/>
<text text-anchor="middle" x="2902.7141" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000">asbestos_exposure</text>
<polyline fill="none" stroke="#000000" points="2747.2141,-990 3058.2141,-990 "/>
<text text-anchor="middle" x="2902.7141" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">cigarettes_per_day</text>
<polyline fill="none" stroke="#000000" points="2747.2141,-967 3058.2141,-967 "/>
<text text-anchor="middle" x="2902.7141" y="-951.8" font-family="Times,serif" font-size="14.00" fill="#000000">coal_dust_exposure</text>
<polyline fill="none" stroke="#000000" points="2747.2141,-944 3058.2141,-944 "/>
<text text-anchor="middle" x="2902.7141" y="-928.8" font-family="Times,serif" font-size="14.00" fill="#000000">environmental_tobacco_smoke_exposure</text>
<polyline fill="none" stroke="#000000" points="2747.2141,-921 3058.2141,-921 "/>
<text text-anchor="middle" x="2902.7141" y="-905.8" font-family="Times,serif" font-size="14.00" fill="#000000">exposure_id</text>
<polyline fill="none" stroke="#000000" points="2747.2141,-898 3058.2141,-898 "/>
<text text-anchor="middle" x="2902.7141" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">pack_years_smoked</text>
<polyline fill="none" stroke="#000000" points="2747.2141,-875 3058.2141,-875 "/>
<text text-anchor="middle" x="2902.7141" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">radon_exposure</text>
<polyline fill="none" stroke="#000000" points="2747.2141,-852 3058.2141,-852 "/>
<text text-anchor="middle" x="2902.7141" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">respirable_crystalline_silica_exposure</text>
<polyline fill="none" stroke="#000000" points="2747.2141,-829 3058.2141,-829 "/>
<text text-anchor="middle" x="2902.7141" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">smoking_frequency</text>
<polyline fill="none" stroke="#000000" points="2747.2141,-806 3058.2141,-806 "/>
<text text-anchor="middle" x="2902.7141" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">start_days_from_index</text>
<polyline fill="none" stroke="#000000" points="2747.2141,-783 3058.2141,-783 "/>
<text text-anchor="middle" x="2902.7141" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">time_between_waking_and_first_smoke</text>
<polyline fill="none" stroke="#000000" points="2747.2141,-760 3058.2141,-760 "/>
<text text-anchor="middle" x="2902.7141" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_onset_year</text>
<polyline fill="none" stroke="#000000" points="2747.2141,-737 3058.2141,-737 "/>
<text text-anchor="middle" x="2902.7141" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_quit_year</text>
<polyline fill="none" stroke="#000000" points="2747.2141,-714 3058.2141,-714 "/>
<text text-anchor="middle" x="2902.7141" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_status</text>
<polyline fill="none" stroke="#000000" points="2747.2141,-691 3058.2141,-691 "/>
<text text-anchor="middle" x="2902.7141" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_smoke_exposure</text>
<polyline fill="none" stroke="#000000" points="2747.2141,-668 3058.2141,-668 "/>
<text text-anchor="middle" x="2902.7141" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_tobacco_used</text>
<polyline fill="none" stroke="#000000" points="2747.2141,-645 3058.2141,-645 "/>
<text text-anchor="middle" x="2902.7141" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">years_smoked</text>
<polyline fill="none" stroke="#000000" points="3058.2141,-622 3058.2141,-1105 "/>
<text text-anchor="middle" x="3068.7141" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2709.7683,-621.9609C2687.0888,-599.4085 2662.0336,-579.3103 2634.7141,-564 2517.5949,-498.3646 2162.764,-546.3462 2032.7141,-513 2013.8,-508.1502 1994.4277,-501.2765 1975.7982,-493.5596"/>
<polygon fill="#000000" stroke="#000000" points="1976.9979,-490.2666 1966.4252,-489.5817 1974.2632,-496.7103 1976.9979,-490.2666"/>
<text text-anchor="middle" x="2626.2141" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node18" class="node">
<title>single_cell_sequencing_file</title>
<path fill="none" stroke="#000000" d="M4638.2141,-1214.5C4638.2141,-1214.5 5247.2141,-1214.5 5247.2141,-1214.5 5253.2141,-1214.5 5259.2141,-1220.5 5259.2141,-1226.5 5259.2141,-1226.5 5259.2141,-1800.5 5259.2141,-1800.5 5259.2141,-1806.5 5253.2141,-1812.5 5247.2141,-1812.5 5247.2141,-1812.5 4638.2141,-1812.5 4638.2141,-1812.5 4632.2141,-1812.5 4626.2141,-1806.5 4626.2141,-1800.5 4626.2141,-1800.5 4626.2141,-1226.5 4626.2141,-1226.5 4626.2141,-1220.5 4632.2141,-1214.5 4638.2141,-1214.5"/>
<text text-anchor="middle" x="4732.2141" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
<polyline fill="none" stroke="#000000" points="4838.2141,-1214.5 4838.2141,-1812.5 "/>
<text text-anchor="middle" x="4848.7141" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4859.2141,-1214.5 4859.2141,-1812.5 "/>
<text text-anchor="middle" x="5048.7141" y="-1797.3" font-family="Times,serif" font-size="14.00" fill="#000000">Cell_Barcode</text>
<polyline fill="none" stroke="#000000" points="4859.2141,-1789.5 5238.2141,-1789.5 "/>
<text text-anchor="middle" x="5048.7141" y="-1774.3" font-family="Times,serif" font-size="14.00" fill="#000000">Cryopreserved_Cells_in_Sample</text>
<polyline fill="none" stroke="#000000" points="4859.2141,-1766.5 5238.2141,-1766.5 "/>
<text text-anchor="middle" x="5048.7141" y="-1751.3" font-family="Times,serif" font-size="14.00" fill="#000000">Dissociation_Method</text>
<polyline fill="none" stroke="#000000" points="4859.2141,-1743.5 5238.2141,-1743.5 "/>
<text text-anchor="middle" x="5048.7141" y="-1728.3" font-family="Times,serif" font-size="14.00" fill="#000000">End_Bias</text>
<polyline fill="none" stroke="#000000" points="4859.2141,-1720.5 5238.2141,-1720.5 "/>
<text text-anchor="middle" x="5048.7141" y="-1705.3" font-family="Times,serif" font-size="14.00" fill="#000000">Input_Cells_and_Nuclei</text>
<polyline fill="none" stroke="#000000" points="4859.2141,-1697.5 5238.2141,-1697.5 "/>
<text text-anchor="middle" x="5048.7141" y="-1682.3" font-family="Times,serif" font-size="14.00" fill="#000000">Library_Construction_Method</text>
<polyline fill="none" stroke="#000000" points="4859.2141,-1674.5 5238.2141,-1674.5 "/>
<text text-anchor="middle" x="5048.7141" y="-1659.3" font-family="Times,serif" font-size="14.00" fill="#000000">Library_Preparation_Date</text>
<polyline fill="none" stroke="#000000" points="4859.2141,-1651.5 5238.2141,-1651.5 "/>
<text text-anchor="middle" x="5048.7141" y="-1636.3" font-family="Times,serif" font-size="14.00" fill="#000000">Nucleic_Acid_Capture_Date</text>
<polyline fill="none" stroke="#000000" points="4859.2141,-1628.5 5238.2141,-1628.5 "/>
<text text-anchor="middle" x="5048.7141" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">Paired_End</text>
<polyline fill="none" stroke="#000000" points="4859.2141,-1605.5 5238.2141,-1605.5 "/>
<text text-anchor="middle" x="5048.7141" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">Protocols_Link</text>
<polyline fill="none" stroke="#000000" points="4859.2141,-1582.5 5238.2141,-1582.5 "/>
<text text-anchor="middle" x="5048.7141" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">Read1</text>
<polyline fill="none" stroke="#000000" points="4859.2141,-1559.5 5238.2141,-1559.5 "/>
<text text-anchor="middle" x="5048.7141" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">Read2</text>
<polyline fill="none" stroke="#000000" points="4859.2141,-1536.5 5238.2141,-1536.5 "/>
<text text-anchor="middle" x="5048.7141" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Feature_barcoding</text>
<polyline fill="none" stroke="#000000" points="4859.2141,-1513.5 5238.2141,-1513.5 "/>
<text text-anchor="middle" x="5048.7141" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Oligo_dT_Poly_dT</text>
<polyline fill="none" stroke="#000000" points="4859.2141,-1490.5 5238.2141,-1490.5 "/>
<text text-anchor="middle" x="5048.7141" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Random</text>
<polyline fill="none" stroke="#000000" points="4859.2141,-1467.5 5238.2141,-1467.5 "/>
<text text-anchor="middle" x="5048.7141" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">Sequencing_Library_Construction_Date</text>
<polyline fill="none" stroke="#000000" points="4859.2141,-1444.5 5238.2141,-1444.5 "/>
<text text-anchor="middle" x="5048.7141" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">Single_Cell_Dissociation_Date</text>
<polyline fill="none" stroke="#000000" points="4859.2141,-1421.5 5238.2141,-1421.5 "/>
<text text-anchor="middle" x="5048.7141" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">Single_Cell_Isolation_Method</text>
<polyline fill="none" stroke="#000000" points="4859.2141,-1398.5 5238.2141,-1398.5 "/>
<text text-anchor="middle" x="5048.7141" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">Spike_In</text>
<polyline fill="none" stroke="#000000" points="4859.2141,-1375.5 5238.2141,-1375.5 "/>
<text text-anchor="middle" x="5048.7141" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">Total_Number_of_Input_Cells</text>
<polyline fill="none" stroke="#000000" points="4859.2141,-1352.5 5238.2141,-1352.5 "/>
<text text-anchor="middle" x="5048.7141" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">UMI</text>
<polyline fill="none" stroke="#000000" points="4859.2141,-1329.5 5238.2141,-1329.5 "/>
<text text-anchor="middle" x="5048.7141" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="4859.2141,-1306.5 5238.2141,-1306.5 "/>
<text text-anchor="middle" x="5048.7141" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">cDNA_Length</text>
<polyline fill="none" stroke="#000000" points="4859.2141,-1283.5 5238.2141,-1283.5 "/>
<text text-anchor="middle" x="5048.7141" y="-1268.3" font-family="Times,serif" font-size="14.00" fill="#000000">cDNA_Offset</text>
<polyline fill="none" stroke="#000000" points="4859.2141,-1260.5 5238.2141,-1260.5 "/>
<text text-anchor="middle" x="5048.7141" y="-1245.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="4859.2141,-1237.5 5238.2141,-1237.5 "/>
<text text-anchor="middle" x="5048.7141" y="-1222.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 24 properties</text>
<polyline fill="none" stroke="#000000" points="5238.2141,-1214.5 5238.2141,-1812.5 "/>
<text text-anchor="middle" x="5248.7141" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge24" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M4626.1365,-1221.0478C4623.3219,-1218.6829 4620.514,-1216.3332 4617.7141,-1214 4504.3634,-1119.5425 4369.0288,-1019.0272 4273.486,-949.9707"/>
<polygon fill="#000000" stroke="#000000" points="4275.3914,-947.0296 4265.2349,-944.0137 4271.2939,-952.705 4275.3914,-947.0296"/>
<text text-anchor="middle" x="4701.2141" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- medical_history -->
<g id="node19" class="node">
<title>medical_history</title>
<path fill="none" stroke="#000000" d="M3109.7141,-829C3109.7141,-829 3463.7141,-829 3463.7141,-829 3469.7141,-829 3475.7141,-835 3475.7141,-841 3475.7141,-841 3475.7141,-886 3475.7141,-886 3475.7141,-892 3469.7141,-898 3463.7141,-898 3463.7141,-898 3109.7141,-898 3109.7141,-898 3103.7141,-898 3097.7141,-892 3097.7141,-886 3097.7141,-886 3097.7141,-841 3097.7141,-841 3097.7141,-835 3103.7141,-829 3109.7141,-829"/>
<text text-anchor="middle" x="3163.2141" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
<polyline fill="none" stroke="#000000" points="3228.7141,-829 3228.7141,-898 "/>
<text text-anchor="middle" x="3239.2141" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3249.7141,-829 3249.7141,-898 "/>
<text text-anchor="middle" x="3352.2141" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_category</text>
<polyline fill="none" stroke="#000000" points="3249.7141,-875 3454.7141,-875 "/>
<text text-anchor="middle" x="3352.2141" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_condition</text>
<polyline fill="none" stroke="#000000" points="3249.7141,-852 3454.7141,-852 "/>
<text text-anchor="middle" x="3352.2141" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_id</text>
<polyline fill="none" stroke="#000000" points="3454.7141,-829 3454.7141,-898 "/>
<text text-anchor="middle" x="3465.2141" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3275.3769,-828.8662C3252.0941,-763.954 3192.1931,-625.0484 3088.7141,-564 2929.3535,-469.9838 2858.474,-540.9335 2673.7141,-531 2602.5666,-527.1748 2102.0575,-529.3737 2032.7141,-513 2013.2059,-508.3936 1993.258,-501.4794 1974.1542,-493.5964"/>
<polygon fill="#000000" stroke="#000000" points="1975.4226,-490.3326 1964.8495,-489.6546 1972.692,-496.7781 1975.4226,-490.3326"/>
<text text-anchor="middle" x="3119.7141" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge21" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1763.365,-374.423C1718.1648,-347.1287 1662.1798,-313.3219 1607.498,-280.3021"/>
<polygon fill="#000000" stroke="#000000" points="1609.1046,-277.1836 1598.735,-275.0104 1605.4861,-283.1758 1609.1046,-277.1836"/>
<text text-anchor="middle" x="1745.2141" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sequencing_file -->
<g id="node21" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M5289.2141,-1214.5C5289.2141,-1214.5 5758.2141,-1214.5 5758.2141,-1214.5 5764.2141,-1214.5 5770.2141,-1220.5 5770.2141,-1226.5 5770.2141,-1226.5 5770.2141,-1800.5 5770.2141,-1800.5 5770.2141,-1806.5 5764.2141,-1812.5 5758.2141,-1812.5 5758.2141,-1812.5 5289.2141,-1812.5 5289.2141,-1812.5 5283.2141,-1812.5 5277.2141,-1806.5 5277.2141,-1800.5 5277.2141,-1800.5 5277.2141,-1226.5 5277.2141,-1226.5 5277.2141,-1220.5 5283.2141,-1214.5 5289.2141,-1214.5"/>
<text text-anchor="middle" x="5341.2141" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="5405.2141,-1214.5 5405.2141,-1812.5 "/>
<text text-anchor="middle" x="5415.7141" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="5426.2141,-1214.5 5426.2141,-1812.5 "/>
<text text-anchor="middle" x="5587.7141" y="-1797.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="5426.2141,-1789.5 5749.2141,-1789.5 "/>
<text text-anchor="middle" x="5587.7141" y="-1774.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="5426.2141,-1766.5 5749.2141,-1766.5 "/>
<text text-anchor="middle" x="5587.7141" y="-1751.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="5426.2141,-1743.5 5749.2141,-1743.5 "/>
<text text-anchor="middle" x="5587.7141" y="-1728.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="5426.2141,-1720.5 5749.2141,-1720.5 "/>
<text text-anchor="middle" x="5587.7141" y="-1705.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="5426.2141,-1697.5 5749.2141,-1697.5 "/>
<text text-anchor="middle" x="5587.7141" y="-1682.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="5426.2141,-1674.5 5749.2141,-1674.5 "/>
<text text-anchor="middle" x="5587.7141" y="-1659.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="5426.2141,-1651.5 5749.2141,-1651.5 "/>
<text text-anchor="middle" x="5587.7141" y="-1636.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="5426.2141,-1628.5 5749.2141,-1628.5 "/>
<text text-anchor="middle" x="5587.7141" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="5426.2141,-1605.5 5749.2141,-1605.5 "/>
<text text-anchor="middle" x="5587.7141" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="5426.2141,-1582.5 5749.2141,-1582.5 "/>
<text text-anchor="middle" x="5587.7141" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="5426.2141,-1559.5 5749.2141,-1559.5 "/>
<text text-anchor="middle" x="5587.7141" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="5426.2141,-1536.5 5749.2141,-1536.5 "/>
<text text-anchor="middle" x="5587.7141" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="5426.2141,-1513.5 5749.2141,-1513.5 "/>
<text text-anchor="middle" x="5587.7141" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="5426.2141,-1490.5 5749.2141,-1490.5 "/>
<text text-anchor="middle" x="5587.7141" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="5426.2141,-1467.5 5749.2141,-1467.5 "/>
<text text-anchor="middle" x="5587.7141" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="5426.2141,-1444.5 5749.2141,-1444.5 "/>
<text text-anchor="middle" x="5587.7141" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="5426.2141,-1421.5 5749.2141,-1421.5 "/>
<text text-anchor="middle" x="5587.7141" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="5426.2141,-1398.5 5749.2141,-1398.5 "/>
<text text-anchor="middle" x="5587.7141" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="5426.2141,-1375.5 5749.2141,-1375.5 "/>
<text text-anchor="middle" x="5587.7141" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="5426.2141,-1352.5 5749.2141,-1352.5 "/>
<text text-anchor="middle" x="5587.7141" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="5426.2141,-1329.5 5749.2141,-1329.5 "/>
<text text-anchor="middle" x="5587.7141" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="5426.2141,-1306.5 5749.2141,-1306.5 "/>
<text text-anchor="middle" x="5587.7141" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="5426.2141,-1283.5 5749.2141,-1283.5 "/>
<text text-anchor="middle" x="5587.7141" y="-1268.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="5426.2141,-1260.5 5749.2141,-1260.5 "/>
<text text-anchor="middle" x="5587.7141" y="-1245.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="5426.2141,-1237.5 5749.2141,-1237.5 "/>
<text text-anchor="middle" x="5587.7141" y="-1222.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 1 properties</text>
<polyline fill="none" stroke="#000000" points="5749.2141,-1214.5 5749.2141,-1812.5 "/>
<text text-anchor="middle" x="5759.7141" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M5277.2132,-1219.7741C5274.3945,-1217.8103 5271.5613,-1215.8848 5268.7141,-1214 4973.6172,-1018.6446 4563.1918,-926.8865 4330.8459,-888.1759"/>
<polygon fill="#000000" stroke="#000000" points="4331.3818,-884.717 4320.9451,-886.5405 4330.241,-891.6235 4331.3818,-884.717"/>
<text text-anchor="middle" x="5295.2141" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- study_funding -->
<g id="node22" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M2053.2141,-386C2053.2141,-386 2432.2141,-386 2432.2141,-386 2438.2141,-386 2444.2141,-392 2444.2141,-398 2444.2141,-398 2444.2141,-466 2444.2141,-466 2444.2141,-472 2438.2141,-478 2432.2141,-478 2432.2141,-478 2053.2141,-478 2053.2141,-478 2047.2141,-478 2041.2141,-472 2041.2141,-466 2041.2141,-466 2041.2141,-398 2041.2141,-398 2041.2141,-392 2047.2141,-386 2053.2141,-386"/>
<text text-anchor="middle" x="2100.7141" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="2160.2141,-386 2160.2141,-478 "/>
<text text-anchor="middle" x="2170.7141" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2181.2141,-386 2181.2141,-478 "/>
<text text-anchor="middle" x="2302.2141" y="-462.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="2181.2141,-455 2423.2141,-455 "/>
<text text-anchor="middle" x="2302.2141" y="-439.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="2181.2141,-432 2423.2141,-432 "/>
<text text-anchor="middle" x="2302.2141" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="2181.2141,-409 2423.2141,-409 "/>
<text text-anchor="middle" x="2302.2141" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding_id</text>
<polyline fill="none" stroke="#000000" points="2423.2141,-386 2423.2141,-478 "/>
<text text-anchor="middle" x="2433.7141" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge19" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2126.556,-385.9213C2095.856,-374.1518 2062.6523,-361.7849 2031.7141,-351 1891.8449,-302.2422 1732.9833,-252.319 1608.5251,-214.4234"/>
<polygon fill="#000000" stroke="#000000" points="1609.4547,-211.0479 1598.8689,-211.4864 1607.4177,-217.745 1609.4547,-211.0479"/>
<text text-anchor="middle" x="2024.7141" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- study_arm -->
<g id="node23" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M2474.2141,-386C2474.2141,-386 2771.2141,-386 2771.2141,-386 2777.2141,-386 2783.2141,-392 2783.2141,-398 2783.2141,-398 2783.2141,-466 2783.2141,-466 2783.2141,-472 2777.2141,-478 2771.2141,-478 2771.2141,-478 2474.2141,-478 2474.2141,-478 2468.2141,-478 2462.2141,-472 2462.2141,-466 2462.2141,-466 2462.2141,-398 2462.2141,-398 2462.2141,-392 2468.2141,-386 2474.2141,-386"/>
<text text-anchor="middle" x="2508.2141" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="2554.2141,-386 2554.2141,-478 "/>
<text text-anchor="middle" x="2564.7141" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2575.2141,-386 2575.2141,-478 "/>
<text text-anchor="middle" x="2668.7141" y="-462.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="2575.2141,-455 2762.2141,-455 "/>
<text text-anchor="middle" x="2668.7141" y="-439.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="2575.2141,-432 2762.2141,-432 "/>
<text text-anchor="middle" x="2668.7141" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="2575.2141,-409 2762.2141,-409 "/>
<text text-anchor="middle" x="2668.7141" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm_id</text>
<polyline fill="none" stroke="#000000" points="2762.2141,-386 2762.2141,-478 "/>
<text text-anchor="middle" x="2772.7141" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge18" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2537.6567,-385.9306C2511.3335,-373.1321 2481.8469,-360.2293 2453.7141,-351 2169.0228,-257.6039 1826.3245,-202.5198 1608.7295,-174.2892"/>
<polygon fill="#000000" stroke="#000000" points="1609.1516,-170.8147 1598.786,-173.0065 1608.256,-177.7572 1609.1516,-170.8147"/>
<text text-anchor="middle" x="2418.2141" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
</g>
</svg>
</div>
