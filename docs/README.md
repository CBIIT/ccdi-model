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
<svg width="3612pt" height="1712pt"
 viewBox="0.00 0.00 3612.00 1712.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1708)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1708 3608,-1708 3608,4 -4,4"/>
<!-- sample -->
<g id="node1" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1376.5,-812C1376.5,-812 1690.5,-812 1690.5,-812 1696.5,-812 1702.5,-818 1702.5,-824 1702.5,-824 1702.5,-961 1702.5,-961 1702.5,-967 1696.5,-973 1690.5,-973 1690.5,-973 1376.5,-973 1376.5,-973 1370.5,-973 1364.5,-967 1364.5,-961 1364.5,-961 1364.5,-824 1364.5,-824 1364.5,-818 1370.5,-812 1376.5,-812"/>
<text text-anchor="middle" x="1398.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1432.5,-812 1432.5,-973 "/>
<text text-anchor="middle" x="1443" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1453.5,-812 1453.5,-973 "/>
<text text-anchor="middle" x="1567.5" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="1453.5,-950 1681.5,-950 "/>
<text text-anchor="middle" x="1567.5" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1453.5,-927 1681.5,-927 "/>
<text text-anchor="middle" x="1567.5" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1453.5,-904 1681.5,-904 "/>
<text text-anchor="middle" x="1567.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1453.5,-881 1681.5,-881 "/>
<text text-anchor="middle" x="1567.5" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1453.5,-858 1681.5,-858 "/>
<text text-anchor="middle" x="1567.5" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1453.5,-835 1681.5,-835 "/>
<text text-anchor="middle" x="1567.5" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="1681.5,-812 1681.5,-973 "/>
<text text-anchor="middle" x="1692" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node3" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M2089.5,-541.5C2089.5,-541.5 2393.5,-541.5 2393.5,-541.5 2399.5,-541.5 2405.5,-547.5 2405.5,-553.5 2405.5,-553.5 2405.5,-644.5 2405.5,-644.5 2405.5,-650.5 2399.5,-656.5 2393.5,-656.5 2393.5,-656.5 2089.5,-656.5 2089.5,-656.5 2083.5,-656.5 2077.5,-650.5 2077.5,-644.5 2077.5,-644.5 2077.5,-553.5 2077.5,-553.5 2077.5,-547.5 2083.5,-541.5 2089.5,-541.5"/>
<text text-anchor="middle" x="2125.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="2173.5,-541.5 2173.5,-656.5 "/>
<text text-anchor="middle" x="2184" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2194.5,-541.5 2194.5,-656.5 "/>
<text text-anchor="middle" x="2289.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="2194.5,-633.5 2384.5,-633.5 "/>
<text text-anchor="middle" x="2289.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="2194.5,-610.5 2384.5,-610.5 "/>
<text text-anchor="middle" x="2289.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="2194.5,-587.5 2384.5,-587.5 "/>
<text text-anchor="middle" x="2289.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="2194.5,-564.5 2384.5,-564.5 "/>
<text text-anchor="middle" x="2289.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="2384.5,-541.5 2384.5,-656.5 "/>
<text text-anchor="middle" x="2395" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1630.7988,-811.8249C1678.7667,-775.5389 1738.9935,-734.9118 1798.5,-708 1883.3636,-669.6205 1983.7374,-643.5009 2067.4657,-626.4763"/>
<polygon fill="#000000" stroke="#000000" points="2068.2149,-629.8958 2077.3308,-624.4967 2066.8376,-623.0326 2068.2149,-629.8958"/>
<text text-anchor="middle" x="1916" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study -->
<g id="node16" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M2257.5,-.5C2257.5,-.5 2647.5,-.5 2647.5,-.5 2653.5,-.5 2659.5,-6.5 2659.5,-12.5 2659.5,-12.5 2659.5,-264.5 2659.5,-264.5 2659.5,-270.5 2653.5,-276.5 2647.5,-276.5 2647.5,-276.5 2257.5,-276.5 2257.5,-276.5 2251.5,-276.5 2245.5,-270.5 2245.5,-264.5 2245.5,-264.5 2245.5,-12.5 2245.5,-12.5 2245.5,-6.5 2251.5,-.5 2257.5,-.5"/>
<text text-anchor="middle" x="2273.5" y="-134.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="2301.5,-.5 2301.5,-276.5 "/>
<text text-anchor="middle" x="2312" y="-134.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2322.5,-.5 2322.5,-276.5 "/>
<text text-anchor="middle" x="2480.5" y="-261.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="2322.5,-253.5 2638.5,-253.5 "/>
<text text-anchor="middle" x="2480.5" y="-238.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="2322.5,-230.5 2638.5,-230.5 "/>
<text text-anchor="middle" x="2480.5" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_shorthand</text>
<polyline fill="none" stroke="#000000" points="2322.5,-207.5 2638.5,-207.5 "/>
<text text-anchor="middle" x="2480.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="2322.5,-184.5 2638.5,-184.5 "/>
<text text-anchor="middle" x="2480.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="2322.5,-161.5 2638.5,-161.5 "/>
<text text-anchor="middle" x="2480.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="2322.5,-138.5 2638.5,-138.5 "/>
<text text-anchor="middle" x="2480.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="2322.5,-115.5 2638.5,-115.5 "/>
<text text-anchor="middle" x="2480.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="2322.5,-92.5 2638.5,-92.5 "/>
<text text-anchor="middle" x="2480.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="2322.5,-69.5 2638.5,-69.5 "/>
<text text-anchor="middle" x="2480.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="2322.5,-46.5 2638.5,-46.5 "/>
<text text-anchor="middle" x="2480.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="2322.5,-23.5 2638.5,-23.5 "/>
<text text-anchor="middle" x="2480.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="2638.5,-.5 2638.5,-276.5 "/>
<text text-anchor="middle" x="2649" y="-134.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge12" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1502.4494,-811.7212C1462.237,-692.0255 1409.573,-466.7978 1520.5,-328 1607.8769,-218.6693 1988.2301,-171.0385 2235.221,-151.3349"/>
<polygon fill="#000000" stroke="#000000" points="2235.7198,-154.8065 2245.4139,-150.5316 2235.1697,-147.8282 2235.7198,-154.8065"/>
<text text-anchor="middle" x="1491" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- publication -->
<g id="node2" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M1541.5,-391C1541.5,-391 1751.5,-391 1751.5,-391 1757.5,-391 1763.5,-397 1763.5,-403 1763.5,-403 1763.5,-415 1763.5,-415 1763.5,-421 1757.5,-427 1751.5,-427 1751.5,-427 1541.5,-427 1541.5,-427 1535.5,-427 1529.5,-421 1529.5,-415 1529.5,-415 1529.5,-403 1529.5,-403 1529.5,-397 1535.5,-391 1541.5,-391"/>
<text text-anchor="middle" x="1578" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="1626.5,-391 1626.5,-427 "/>
<text text-anchor="middle" x="1637" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1647.5,-391 1647.5,-427 "/>
<text text-anchor="middle" x="1695" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="1742.5,-391 1742.5,-427 "/>
<text text-anchor="middle" x="1753" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge7" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1646.9879,-390.9965C1648.6971,-365.6583 1655.7168,-319.8069 1683.5,-295 1763.7027,-223.3889 2037.3263,-180.5908 2235.3782,-158.298"/>
<polygon fill="#000000" stroke="#000000" points="2235.7925,-161.7736 2245.3428,-157.1864 2235.0164,-154.8167 2235.7925,-161.7736"/>
<text text-anchor="middle" x="1734.5" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- study_arm -->
<g id="node14" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M2648,-374.5C2648,-374.5 2945,-374.5 2945,-374.5 2951,-374.5 2957,-380.5 2957,-386.5 2957,-386.5 2957,-431.5 2957,-431.5 2957,-437.5 2951,-443.5 2945,-443.5 2945,-443.5 2648,-443.5 2648,-443.5 2642,-443.5 2636,-437.5 2636,-431.5 2636,-431.5 2636,-386.5 2636,-386.5 2636,-380.5 2642,-374.5 2648,-374.5"/>
<text text-anchor="middle" x="2682" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="2728,-374.5 2728,-443.5 "/>
<text text-anchor="middle" x="2738.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2749,-374.5 2749,-443.5 "/>
<text text-anchor="middle" x="2842.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="2749,-420.5 2936,-420.5 "/>
<text text-anchor="middle" x="2842.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="2749,-397.5 2936,-397.5 "/>
<text text-anchor="middle" x="2842.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="2936,-374.5 2936,-443.5 "/>
<text text-anchor="middle" x="2946.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge9" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M2405.9685,-559.2324C2475.236,-540.7735 2556.1671,-516.9379 2627.5,-490 2659.0855,-478.0722 2692.8328,-462.5052 2721.7995,-448.2093"/>
<polygon fill="#000000" stroke="#000000" points="2723.6331,-451.2063 2731.0275,-443.6186 2720.5153,-444.939 2723.6331,-451.2063"/>
<text text-anchor="middle" x="2626" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge10" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2077.3453,-578.7322C1969.3604,-561.6393 1842.0083,-532.9888 1808.5,-490 1764.2366,-433.2131 1765.3687,-385.6514 1808.5,-328 1860.4384,-258.5767 2069.5399,-205.8395 2235.5752,-173.843"/>
<polygon fill="#000000" stroke="#000000" points="2236.2802,-177.2717 2245.4448,-171.9556 2234.9653,-170.3963 2236.2802,-177.2717"/>
<text text-anchor="middle" x="1859" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- diagnosis -->
<g id="node4" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1819.5,-708.5C1819.5,-708.5 2193.5,-708.5 2193.5,-708.5 2199.5,-708.5 2205.5,-714.5 2205.5,-720.5 2205.5,-720.5 2205.5,-1064.5 2205.5,-1064.5 2205.5,-1070.5 2199.5,-1076.5 2193.5,-1076.5 2193.5,-1076.5 1819.5,-1076.5 1819.5,-1076.5 1813.5,-1076.5 1807.5,-1070.5 1807.5,-1064.5 1807.5,-1064.5 1807.5,-720.5 1807.5,-720.5 1807.5,-714.5 1813.5,-708.5 1819.5,-708.5"/>
<text text-anchor="middle" x="1849.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1891.5,-708.5 1891.5,-1076.5 "/>
<text text-anchor="middle" x="1902" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1912.5,-708.5 1912.5,-1076.5 "/>
<text text-anchor="middle" x="2048.5" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1912.5,-1053.5 2184.5,-1053.5 "/>
<text text-anchor="middle" x="2048.5" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1912.5,-1030.5 2184.5,-1030.5 "/>
<text text-anchor="middle" x="2048.5" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1912.5,-1007.5 2184.5,-1007.5 "/>
<text text-anchor="middle" x="2048.5" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1912.5,-984.5 2184.5,-984.5 "/>
<text text-anchor="middle" x="2048.5" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1912.5,-961.5 2184.5,-961.5 "/>
<text text-anchor="middle" x="2048.5" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="1912.5,-938.5 2184.5,-938.5 "/>
<text text-anchor="middle" x="2048.5" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="1912.5,-915.5 2184.5,-915.5 "/>
<text text-anchor="middle" x="2048.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="1912.5,-892.5 2184.5,-892.5 "/>
<text text-anchor="middle" x="2048.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1912.5,-869.5 2184.5,-869.5 "/>
<text text-anchor="middle" x="2048.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="1912.5,-846.5 2184.5,-846.5 "/>
<text text-anchor="middle" x="2048.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1912.5,-823.5 2184.5,-823.5 "/>
<text text-anchor="middle" x="2048.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1912.5,-800.5 2184.5,-800.5 "/>
<text text-anchor="middle" x="2048.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1912.5,-777.5 2184.5,-777.5 "/>
<text text-anchor="middle" x="2048.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1912.5,-754.5 2184.5,-754.5 "/>
<text text-anchor="middle" x="2048.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1912.5,-731.5 2184.5,-731.5 "/>
<text text-anchor="middle" x="2048.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="2184.5,-708.5 2184.5,-1076.5 "/>
<text text-anchor="middle" x="2195" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2110.9302,-708.3139C2119.7534,-696.6599 2128.9662,-685.4351 2138.5,-675 2142.0167,-671.1509 2145.7538,-667.3689 2149.6415,-663.6742"/>
<polygon fill="#000000" stroke="#000000" points="2152.2691,-666.0141 2157.285,-656.6818 2147.5442,-660.8492 2152.2691,-666.0141"/>
<text text-anchor="middle" x="2183" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- sample_diagnosis -->
<g id="node5" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M523,-1255C523,-1255 956,-1255 956,-1255 962,-1255 968,-1261 968,-1267 968,-1267 968,-1565 968,-1565 968,-1571 962,-1577 956,-1577 956,-1577 523,-1577 523,-1577 517,-1577 511,-1571 511,-1565 511,-1565 511,-1267 511,-1267 511,-1261 517,-1255 523,-1255"/>
<text text-anchor="middle" x="582.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="654,-1255 654,-1577 "/>
<text text-anchor="middle" x="664.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="675,-1255 675,-1577 "/>
<text text-anchor="middle" x="811" y="-1561.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="675,-1554 947,-1554 "/>
<text text-anchor="middle" x="811" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="675,-1531 947,-1531 "/>
<text text-anchor="middle" x="811" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="675,-1508 947,-1508 "/>
<text text-anchor="middle" x="811" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="675,-1485 947,-1485 "/>
<text text-anchor="middle" x="811" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="675,-1462 947,-1462 "/>
<text text-anchor="middle" x="811" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="675,-1439 947,-1439 "/>
<text text-anchor="middle" x="811" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="675,-1416 947,-1416 "/>
<text text-anchor="middle" x="811" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="675,-1393 947,-1393 "/>
<text text-anchor="middle" x="811" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="675,-1370 947,-1370 "/>
<text text-anchor="middle" x="811" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="675,-1347 947,-1347 "/>
<text text-anchor="middle" x="811" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="675,-1324 947,-1324 "/>
<text text-anchor="middle" x="811" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="675,-1301 947,-1301 "/>
<text text-anchor="middle" x="811" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="675,-1278 947,-1278 "/>
<text text-anchor="middle" x="811" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="947,-1255 947,-1577 "/>
<text text-anchor="middle" x="957.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M849.978,-1254.8823C886.6559,-1209.5998 930.3001,-1163.1726 977.5,-1128 1091.1452,-1043.3136 1239.8289,-982.3927 1354.8447,-943.7553"/>
<polygon fill="#000000" stroke="#000000" points="1356.0832,-947.0319 1364.4635,-940.5495 1353.8699,-940.391 1356.0832,-947.0319"/>
<text text-anchor="middle" x="1090.5" y="-1098.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
<!-- pdx -->
<g id="node6" class="node">
<title>pdx</title>
<path fill="none" stroke="#000000" d="M998,-1312.5C998,-1312.5 1327,-1312.5 1327,-1312.5 1333,-1312.5 1339,-1318.5 1339,-1324.5 1339,-1324.5 1339,-1507.5 1339,-1507.5 1339,-1513.5 1333,-1519.5 1327,-1519.5 1327,-1519.5 998,-1519.5 998,-1519.5 992,-1519.5 986,-1513.5 986,-1507.5 986,-1507.5 986,-1324.5 986,-1324.5 986,-1318.5 992,-1312.5 998,-1312.5"/>
<text text-anchor="middle" x="1007.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
<polyline fill="none" stroke="#000000" points="1029,-1312.5 1029,-1519.5 "/>
<text text-anchor="middle" x="1039.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1050,-1312.5 1050,-1519.5 "/>
<text text-anchor="middle" x="1184" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_site</text>
<polyline fill="none" stroke="#000000" points="1050,-1496.5 1318,-1496.5 "/>
<text text-anchor="middle" x="1184" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_type</text>
<polyline fill="none" stroke="#000000" points="1050,-1473.5 1318,-1473.5 "/>
<text text-anchor="middle" x="1184" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_id</text>
<polyline fill="none" stroke="#000000" points="1050,-1450.5 1318,-1450.5 "/>
<text text-anchor="middle" x="1184" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">mouse_strain</text>
<polyline fill="none" stroke="#000000" points="1050,-1427.5 1318,-1427.5 "/>
<text text-anchor="middle" x="1184" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">strain_immune_system_humanized</text>
<polyline fill="none" stroke="#000000" points="1050,-1404.5 1318,-1404.5 "/>
<text text-anchor="middle" x="1184" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_characterization_method</text>
<polyline fill="none" stroke="#000000" points="1050,-1381.5 1318,-1381.5 "/>
<text text-anchor="middle" x="1184" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_not_mus_or_ebv_origin</text>
<polyline fill="none" stroke="#000000" points="1050,-1358.5 1318,-1358.5 "/>
<text text-anchor="middle" x="1184" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_preparation</text>
<polyline fill="none" stroke="#000000" points="1050,-1335.5 1318,-1335.5 "/>
<text text-anchor="middle" x="1184" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_humanization</text>
<polyline fill="none" stroke="#000000" points="1318,-1312.5 1318,-1519.5 "/>
<text text-anchor="middle" x="1328.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1226.3058,-1312.1643C1261.202,-1256.692 1305.8959,-1187.7204 1348.5,-1128 1383.9609,-1078.2926 1425.8201,-1024.6302 1460.7444,-981.1026"/>
<polygon fill="#000000" stroke="#000000" points="1463.6433,-983.0827 1467.1817,-973.0962 1458.1879,-978.6965 1463.6433,-983.0827"/>
<text text-anchor="middle" x="1395.5" y="-1098.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study_admin -->
<g id="node7" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M1930.5,-328.5C1930.5,-328.5 2256.5,-328.5 2256.5,-328.5 2262.5,-328.5 2268.5,-334.5 2268.5,-340.5 2268.5,-340.5 2268.5,-477.5 2268.5,-477.5 2268.5,-483.5 2262.5,-489.5 2256.5,-489.5 2256.5,-489.5 1930.5,-489.5 1930.5,-489.5 1924.5,-489.5 1918.5,-483.5 1918.5,-477.5 1918.5,-477.5 1918.5,-340.5 1918.5,-340.5 1918.5,-334.5 1924.5,-328.5 1930.5,-328.5"/>
<text text-anchor="middle" x="1972.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="2026.5,-328.5 2026.5,-489.5 "/>
<text text-anchor="middle" x="2037" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2047.5,-328.5 2047.5,-489.5 "/>
<text text-anchor="middle" x="2147.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="2047.5,-466.5 2247.5,-466.5 "/>
<text text-anchor="middle" x="2147.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="2047.5,-443.5 2247.5,-443.5 "/>
<text text-anchor="middle" x="2147.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="2047.5,-420.5 2247.5,-420.5 "/>
<text text-anchor="middle" x="2147.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="2047.5,-397.5 2247.5,-397.5 "/>
<text text-anchor="middle" x="2147.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="2047.5,-374.5 2247.5,-374.5 "/>
<text text-anchor="middle" x="2147.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="2047.5,-351.5 2247.5,-351.5 "/>
<text text-anchor="middle" x="2147.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="2247.5,-328.5 2247.5,-489.5 "/>
<text text-anchor="middle" x="2258" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge6" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2200.7256,-328.2075C2219.8775,-313.7768 2240.3472,-298.3533 2261.0298,-282.7693"/>
<polygon fill="#000000" stroke="#000000" points="2263.3945,-285.3699 2269.2749,-276.5568 2259.182,-279.7793 2263.3945,-285.3699"/>
<text text-anchor="middle" x="2297" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- imaging_file -->
<g id="node8" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M1369.5,-1255C1369.5,-1255 1703.5,-1255 1703.5,-1255 1709.5,-1255 1715.5,-1261 1715.5,-1267 1715.5,-1267 1715.5,-1565 1715.5,-1565 1715.5,-1571 1709.5,-1577 1703.5,-1577 1703.5,-1577 1369.5,-1577 1369.5,-1577 1363.5,-1577 1357.5,-1571 1357.5,-1565 1357.5,-1565 1357.5,-1267 1357.5,-1267 1357.5,-1261 1363.5,-1255 1369.5,-1255"/>
<text text-anchor="middle" x="1409.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="1461.5,-1255 1461.5,-1577 "/>
<text text-anchor="middle" x="1472" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1482.5,-1255 1482.5,-1577 "/>
<text text-anchor="middle" x="1588.5" y="-1561.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1482.5,-1554 1694.5,-1554 "/>
<text text-anchor="middle" x="1588.5" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1482.5,-1531 1694.5,-1531 "/>
<text text-anchor="middle" x="1588.5" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1482.5,-1508 1694.5,-1508 "/>
<text text-anchor="middle" x="1588.5" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1482.5,-1485 1694.5,-1485 "/>
<text text-anchor="middle" x="1588.5" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1482.5,-1462 1694.5,-1462 "/>
<text text-anchor="middle" x="1588.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1482.5,-1439 1694.5,-1439 "/>
<text text-anchor="middle" x="1588.5" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1482.5,-1416 1694.5,-1416 "/>
<text text-anchor="middle" x="1588.5" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1482.5,-1393 1694.5,-1393 "/>
<text text-anchor="middle" x="1588.5" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1482.5,-1370 1694.5,-1370 "/>
<text text-anchor="middle" x="1588.5" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="1482.5,-1347 1694.5,-1347 "/>
<text text-anchor="middle" x="1588.5" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="1482.5,-1324 1694.5,-1324 "/>
<text text-anchor="middle" x="1588.5" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="1482.5,-1301 1694.5,-1301 "/>
<text text-anchor="middle" x="1588.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1482.5,-1278 1694.5,-1278 "/>
<text text-anchor="middle" x="1588.5" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="1694.5,-1255 1694.5,-1577 "/>
<text text-anchor="middle" x="1705" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1535.5754,-1254.6611C1535.0649,-1165.5701 1534.4495,-1058.1863 1534.022,-983.5881"/>
<polygon fill="#000000" stroke="#000000" points="1537.5203,-983.2646 1533.963,-973.2849 1530.5204,-983.3048 1537.5203,-983.2646"/>
<text text-anchor="middle" x="1589" y="-1098.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- methylation_array_file -->
<g id="node9" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M1746,-1301C1746,-1301 2113,-1301 2113,-1301 2119,-1301 2125,-1307 2125,-1313 2125,-1313 2125,-1519 2125,-1519 2125,-1525 2119,-1531 2113,-1531 2113,-1531 1746,-1531 1746,-1531 1740,-1531 1734,-1525 1734,-1519 1734,-1519 1734,-1313 1734,-1313 1734,-1307 1740,-1301 1746,-1301"/>
<text text-anchor="middle" x="1823" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="1912,-1301 1912,-1531 "/>
<text text-anchor="middle" x="1922.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1933,-1301 1933,-1531 "/>
<text text-anchor="middle" x="2018.5" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1933,-1508 2104,-1508 "/>
<text text-anchor="middle" x="2018.5" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1933,-1485 2104,-1485 "/>
<text text-anchor="middle" x="2018.5" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1933,-1462 2104,-1462 "/>
<text text-anchor="middle" x="2018.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1933,-1439 2104,-1439 "/>
<text text-anchor="middle" x="2018.5" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1933,-1416 2104,-1416 "/>
<text text-anchor="middle" x="2018.5" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1933,-1393 2104,-1393 "/>
<text text-anchor="middle" x="2018.5" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1933,-1370 2104,-1370 "/>
<text text-anchor="middle" x="2018.5" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1933,-1347 2104,-1347 "/>
<text text-anchor="middle" x="2018.5" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="1933,-1324 2104,-1324 "/>
<text text-anchor="middle" x="2018.5" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="2104,-1301 2104,-1531 "/>
<text text-anchor="middle" x="2114.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1850.0683,-1300.9242C1812.7227,-1247.7326 1767.1219,-1184.0639 1724.5,-1128 1686.9317,-1078.5835 1643.4478,-1024.7247 1607.469,-981.001"/>
<polygon fill="#000000" stroke="#000000" points="1610.1328,-978.7299 1601.0724,-973.2381 1604.7305,-983.1814 1610.1328,-978.7299"/>
<text text-anchor="middle" x="1801" y="-1098.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study_personnel -->
<g id="node10" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M2299,-351.5C2299,-351.5 2606,-351.5 2606,-351.5 2612,-351.5 2618,-357.5 2618,-363.5 2618,-363.5 2618,-454.5 2618,-454.5 2618,-460.5 2612,-466.5 2606,-466.5 2606,-466.5 2299,-466.5 2299,-466.5 2293,-466.5 2287,-460.5 2287,-454.5 2287,-454.5 2287,-363.5 2287,-363.5 2287,-357.5 2293,-351.5 2299,-351.5"/>
<text text-anchor="middle" x="2354" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="2421,-351.5 2421,-466.5 "/>
<text text-anchor="middle" x="2431.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2442,-351.5 2442,-466.5 "/>
<text text-anchor="middle" x="2519.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="2442,-443.5 2597,-443.5 "/>
<text text-anchor="middle" x="2519.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="2442,-420.5 2597,-420.5 "/>
<text text-anchor="middle" x="2519.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="2442,-397.5 2597,-397.5 "/>
<text text-anchor="middle" x="2519.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="2442,-374.5 2597,-374.5 "/>
<text text-anchor="middle" x="2519.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="2597,-351.5 2597,-466.5 "/>
<text text-anchor="middle" x="2607.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge21" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2452.5,-351.3027C2452.5,-332.11 2452.5,-309.7702 2452.5,-286.9242"/>
<polygon fill="#000000" stroke="#000000" points="2456.0001,-286.7571 2452.5,-276.7572 2449.0001,-286.7572 2456.0001,-286.7571"/>
<text text-anchor="middle" x="2522" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- synonym -->
<g id="node11" class="node">
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
<g id="edge16" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2299.2573,-1392.9722C2282.809,-1337.1039 2232.6431,-1194.1125 2134.5,-1128 2071.8641,-1085.8064 1868.651,-1104.9714 1798.5,-1077 1739.9226,-1053.6433 1681.6562,-1015.188 1634.7383,-979.4135"/>
<polygon fill="#000000" stroke="#000000" points="1636.7709,-976.5612 1626.7116,-973.235 1632.5011,-982.1082 1636.7709,-976.5612"/>
<text text-anchor="middle" x="2124" y="-1098.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2300.6583,-1392.7115C2289.5223,-1337.9506 2262.2263,-1196.6063 2251.5,-1077 2238.4224,-931.1759 2238.6187,-759.3755 2240.0056,-666.6235"/>
<polygon fill="#000000" stroke="#000000" points="2243.5065,-666.5856 2240.1659,-656.5312 2236.5074,-666.4743 2243.5065,-666.5856"/>
<text text-anchor="middle" x="2294" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge18" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2468.126,-1398.4203C2661.7347,-1368.2899 2979.6597,-1287.9421 3145.5,-1077 3196.7201,-1011.8501 3172.5,-975.3734 3172.5,-892.5 3172.5,-892.5 3172.5,-892.5 3172.5,-409 3172.5,-300.3943 2881.7922,-220.5921 2669.8208,-176.8395"/>
<polygon fill="#000000" stroke="#000000" points="2670.287,-173.3623 2659.7879,-174.7833 2668.8815,-180.2198 2670.287,-173.3623"/>
<text text-anchor="middle" x="3215" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- clinical_measure_file -->
<g id="node12" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M2772.5,-766C2772.5,-766 3124.5,-766 3124.5,-766 3130.5,-766 3136.5,-772 3136.5,-778 3136.5,-778 3136.5,-1007 3136.5,-1007 3136.5,-1013 3130.5,-1019 3124.5,-1019 3124.5,-1019 2772.5,-1019 2772.5,-1019 2766.5,-1019 2760.5,-1013 2760.5,-1007 2760.5,-1007 2760.5,-778 2760.5,-778 2760.5,-772 2766.5,-766 2772.5,-766"/>
<text text-anchor="middle" x="2844" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="2927.5,-766 2927.5,-1019 "/>
<text text-anchor="middle" x="2938" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2948.5,-766 2948.5,-1019 "/>
<text text-anchor="middle" x="3032" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2948.5,-996 3115.5,-996 "/>
<text text-anchor="middle" x="3032" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2948.5,-973 3115.5,-973 "/>
<text text-anchor="middle" x="3032" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2948.5,-950 3115.5,-950 "/>
<text text-anchor="middle" x="3032" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2948.5,-927 3115.5,-927 "/>
<text text-anchor="middle" x="3032" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2948.5,-904 3115.5,-904 "/>
<text text-anchor="middle" x="3032" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2948.5,-881 3115.5,-881 "/>
<text text-anchor="middle" x="3032" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2948.5,-858 3115.5,-858 "/>
<text text-anchor="middle" x="3032" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2948.5,-835 3115.5,-835 "/>
<text text-anchor="middle" x="3032" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2948.5,-812 3115.5,-812 "/>
<text text-anchor="middle" x="3032" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2948.5,-789 3115.5,-789 "/>
<text text-anchor="middle" x="3032" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="3115.5,-766 3115.5,-1019 "/>
<text text-anchor="middle" x="3126" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2822.7408,-765.9481C2795.6817,-743.9838 2765.993,-723.317 2735.5,-708 2635.9126,-657.9761 2513.6793,-630.7628 2415.7177,-616.0373"/>
<polygon fill="#000000" stroke="#000000" points="2416.1157,-612.5583 2405.7124,-614.5639 2415.0958,-619.4836 2416.1157,-612.5583"/>
<text text-anchor="middle" x="2815" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge5" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2960.4232,-765.9498C2973.8598,-610.4877 2990.8573,-362.9399 2966.5,-328 2930.3216,-276.103 2792.938,-226.9693 2669.3048,-191.7418"/>
<polygon fill="#000000" stroke="#000000" points="2670.2473,-188.3712 2659.6721,-189.0171 2668.3419,-195.1069 2670.2473,-188.3712"/>
<text text-anchor="middle" x="3062.5" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- sequencing_file -->
<g id="node13" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M12,-1128.5C12,-1128.5 481,-1128.5 481,-1128.5 487,-1128.5 493,-1134.5 493,-1140.5 493,-1140.5 493,-1691.5 493,-1691.5 493,-1697.5 487,-1703.5 481,-1703.5 481,-1703.5 12,-1703.5 12,-1703.5 6,-1703.5 0,-1697.5 0,-1691.5 0,-1691.5 0,-1140.5 0,-1140.5 0,-1134.5 6,-1128.5 12,-1128.5"/>
<text text-anchor="middle" x="64" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="128,-1128.5 128,-1703.5 "/>
<text text-anchor="middle" x="138.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="149,-1128.5 149,-1703.5 "/>
<text text-anchor="middle" x="310.5" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="149,-1680.5 472,-1680.5 "/>
<text text-anchor="middle" x="310.5" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="149,-1657.5 472,-1657.5 "/>
<text text-anchor="middle" x="310.5" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="149,-1634.5 472,-1634.5 "/>
<text text-anchor="middle" x="310.5" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="149,-1611.5 472,-1611.5 "/>
<text text-anchor="middle" x="310.5" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="149,-1588.5 472,-1588.5 "/>
<text text-anchor="middle" x="310.5" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="149,-1565.5 472,-1565.5 "/>
<text text-anchor="middle" x="310.5" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="149,-1542.5 472,-1542.5 "/>
<text text-anchor="middle" x="310.5" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="149,-1519.5 472,-1519.5 "/>
<text text-anchor="middle" x="310.5" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="149,-1496.5 472,-1496.5 "/>
<text text-anchor="middle" x="310.5" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="149,-1473.5 472,-1473.5 "/>
<text text-anchor="middle" x="310.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="149,-1450.5 472,-1450.5 "/>
<text text-anchor="middle" x="310.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="149,-1427.5 472,-1427.5 "/>
<text text-anchor="middle" x="310.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="149,-1404.5 472,-1404.5 "/>
<text text-anchor="middle" x="310.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="149,-1381.5 472,-1381.5 "/>
<text text-anchor="middle" x="310.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="149,-1358.5 472,-1358.5 "/>
<text text-anchor="middle" x="310.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="149,-1335.5 472,-1335.5 "/>
<text text-anchor="middle" x="310.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="149,-1312.5 472,-1312.5 "/>
<text text-anchor="middle" x="310.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="149,-1289.5 472,-1289.5 "/>
<text text-anchor="middle" x="310.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="149,-1266.5 472,-1266.5 "/>
<text text-anchor="middle" x="310.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="149,-1243.5 472,-1243.5 "/>
<text text-anchor="middle" x="310.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="149,-1220.5 472,-1220.5 "/>
<text text-anchor="middle" x="310.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="149,-1197.5 472,-1197.5 "/>
<text text-anchor="middle" x="310.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="149,-1174.5 472,-1174.5 "/>
<text text-anchor="middle" x="310.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="149,-1151.5 472,-1151.5 "/>
<text text-anchor="middle" x="310.5" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="472,-1128.5 472,-1703.5 "/>
<text text-anchor="middle" x="482.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M493.3552,-1132.9691C496.0564,-1131.275 498.7714,-1129.6179 501.5,-1128 644.132,-1043.425 1098.5098,-961.0615 1354.2315,-919.82"/>
<polygon fill="#000000" stroke="#000000" points="1355.0556,-923.2326 1364.373,-918.1892 1353.9442,-916.3214 1355.0556,-923.2326"/>
<text text-anchor="middle" x="628" y="-1098.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge2" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2752.5828,-374.4662C2722.3161,-350.6665 2679.8422,-317.2676 2636.3529,-283.0704"/>
<polygon fill="#000000" stroke="#000000" points="2638.2477,-280.1079 2628.2234,-276.6779 2633.9208,-285.6104 2638.2477,-280.1079"/>
<text text-anchor="middle" x="2713" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- therapeutic_procedure -->
<g id="node15" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M2357,-835C2357,-835 2714,-835 2714,-835 2720,-835 2726,-841 2726,-847 2726,-847 2726,-938 2726,-938 2726,-944 2720,-950 2714,-950 2714,-950 2357,-950 2357,-950 2351,-950 2345,-944 2345,-938 2345,-938 2345,-847 2345,-847 2345,-841 2351,-835 2357,-835"/>
<text text-anchor="middle" x="2435.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="2526,-835 2526,-950 "/>
<text text-anchor="middle" x="2536.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2547,-835 2547,-950 "/>
<text text-anchor="middle" x="2626" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="2547,-927 2705,-927 "/>
<text text-anchor="middle" x="2626" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="2547,-904 2705,-904 "/>
<text text-anchor="middle" x="2626" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="2547,-881 2705,-881 "/>
<text text-anchor="middle" x="2626" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="2547,-858 2705,-858 "/>
<text text-anchor="middle" x="2626" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="2705,-835 2705,-950 "/>
<text text-anchor="middle" x="2715.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2477.7658,-834.864C2428.4137,-785.5958 2357.4577,-714.7605 2306.1998,-663.5898"/>
<polygon fill="#000000" stroke="#000000" points="2308.652,-661.0922 2299.1021,-656.5041 2303.7064,-666.0462 2308.652,-661.0922"/>
<text text-anchor="middle" x="2420.5" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- study_funding -->
<g id="node17" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M3213,-374.5C3213,-374.5 3592,-374.5 3592,-374.5 3598,-374.5 3604,-380.5 3604,-386.5 3604,-386.5 3604,-431.5 3604,-431.5 3604,-437.5 3598,-443.5 3592,-443.5 3592,-443.5 3213,-443.5 3213,-443.5 3207,-443.5 3201,-437.5 3201,-431.5 3201,-431.5 3201,-386.5 3201,-386.5 3201,-380.5 3207,-374.5 3213,-374.5"/>
<text text-anchor="middle" x="3260.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="3320,-374.5 3320,-443.5 "/>
<text text-anchor="middle" x="3330.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3341,-374.5 3341,-443.5 "/>
<text text-anchor="middle" x="3462" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="3341,-420.5 3583,-420.5 "/>
<text text-anchor="middle" x="3462" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="3341,-397.5 3583,-397.5 "/>
<text text-anchor="middle" x="3462" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="3583,-374.5 3583,-443.5 "/>
<text text-anchor="middle" x="3593.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3347.1624,-374.3195C3304.6462,-349.0499 3243.7032,-315.7413 3186.5,-295 3017.816,-233.837 2818.2145,-193.1905 2669.7709,-168.6863"/>
<polygon fill="#000000" stroke="#000000" points="2670.055,-165.1863 2659.6206,-167.0228 2668.9228,-172.0941 2670.055,-165.1863"/>
<text text-anchor="middle" x="3285.5" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
</g>
</svg>
</div>
