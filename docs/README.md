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
<svg width="4026pt" height="1735pt"
 viewBox="0.00 0.00 4025.50 1735.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1731)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1731 4021.5,-1731 4021.5,4 -4,4"/>
<!-- therapeutic_procedure -->
<g id="node1" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M1466,-823.5C1466,-823.5 1823,-823.5 1823,-823.5 1829,-823.5 1835,-829.5 1835,-835.5 1835,-835.5 1835,-926.5 1835,-926.5 1835,-932.5 1829,-938.5 1823,-938.5 1823,-938.5 1466,-938.5 1466,-938.5 1460,-938.5 1454,-932.5 1454,-926.5 1454,-926.5 1454,-835.5 1454,-835.5 1454,-829.5 1460,-823.5 1466,-823.5"/>
<text text-anchor="middle" x="1544.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="1635,-823.5 1635,-938.5 "/>
<text text-anchor="middle" x="1645.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1656,-823.5 1656,-938.5 "/>
<text text-anchor="middle" x="1735" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="1656,-915.5 1814,-915.5 "/>
<text text-anchor="middle" x="1735" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="1656,-892.5 1814,-892.5 "/>
<text text-anchor="middle" x="1735" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1656,-869.5 1814,-869.5 "/>
<text text-anchor="middle" x="1735" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="1656,-846.5 1814,-846.5 "/>
<text text-anchor="middle" x="1735" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1814,-823.5 1814,-938.5 "/>
<text text-anchor="middle" x="1824.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node17" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M2100.5,-495.5C2100.5,-495.5 2404.5,-495.5 2404.5,-495.5 2410.5,-495.5 2416.5,-501.5 2416.5,-507.5 2416.5,-507.5 2416.5,-598.5 2416.5,-598.5 2416.5,-604.5 2410.5,-610.5 2404.5,-610.5 2404.5,-610.5 2100.5,-610.5 2100.5,-610.5 2094.5,-610.5 2088.5,-604.5 2088.5,-598.5 2088.5,-598.5 2088.5,-507.5 2088.5,-507.5 2088.5,-501.5 2094.5,-495.5 2100.5,-495.5"/>
<text text-anchor="middle" x="2136.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="2184.5,-495.5 2184.5,-610.5 "/>
<text text-anchor="middle" x="2195" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2205.5,-495.5 2205.5,-610.5 "/>
<text text-anchor="middle" x="2300.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="2205.5,-587.5 2395.5,-587.5 "/>
<text text-anchor="middle" x="2300.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="2205.5,-564.5 2395.5,-564.5 "/>
<text text-anchor="middle" x="2300.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="2205.5,-541.5 2395.5,-541.5 "/>
<text text-anchor="middle" x="2300.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="2205.5,-518.5 2395.5,-518.5 "/>
<text text-anchor="middle" x="2300.5" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="2395.5,-495.5 2395.5,-610.5 "/>
<text text-anchor="middle" x="2406" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1682.8772,-823.0351C1718.8815,-773.1374 1777.1696,-702.9005 1844.5,-662 1914.9643,-619.1958 2002.2481,-592.9644 2077.979,-577.0054"/>
<polygon fill="#000000" stroke="#000000" points="2079.0197,-580.3645 2088.107,-574.9174 2077.6063,-573.5087 2079.0197,-580.3645"/>
<text text-anchor="middle" x="1998.5" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- diagnosis -->
<g id="node2" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1865.5,-662.5C1865.5,-662.5 2239.5,-662.5 2239.5,-662.5 2245.5,-662.5 2251.5,-668.5 2251.5,-674.5 2251.5,-674.5 2251.5,-1087.5 2251.5,-1087.5 2251.5,-1093.5 2245.5,-1099.5 2239.5,-1099.5 2239.5,-1099.5 1865.5,-1099.5 1865.5,-1099.5 1859.5,-1099.5 1853.5,-1093.5 1853.5,-1087.5 1853.5,-1087.5 1853.5,-674.5 1853.5,-674.5 1853.5,-668.5 1859.5,-662.5 1865.5,-662.5"/>
<text text-anchor="middle" x="1895.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1937.5,-662.5 1937.5,-1099.5 "/>
<text text-anchor="middle" x="1948" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1958.5,-662.5 1958.5,-1099.5 "/>
<text text-anchor="middle" x="2094.5" y="-1084.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1958.5,-1076.5 2230.5,-1076.5 "/>
<text text-anchor="middle" x="2094.5" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1958.5,-1053.5 2230.5,-1053.5 "/>
<text text-anchor="middle" x="2094.5" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1958.5,-1030.5 2230.5,-1030.5 "/>
<text text-anchor="middle" x="2094.5" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1958.5,-1007.5 2230.5,-1007.5 "/>
<text text-anchor="middle" x="2094.5" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="1958.5,-984.5 2230.5,-984.5 "/>
<text text-anchor="middle" x="2094.5" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="1958.5,-961.5 2230.5,-961.5 "/>
<text text-anchor="middle" x="2094.5" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="1958.5,-938.5 2230.5,-938.5 "/>
<text text-anchor="middle" x="2094.5" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1958.5,-915.5 2230.5,-915.5 "/>
<text text-anchor="middle" x="2094.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1958.5,-892.5 2230.5,-892.5 "/>
<text text-anchor="middle" x="2094.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="1958.5,-869.5 2230.5,-869.5 "/>
<text text-anchor="middle" x="2094.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="1958.5,-846.5 2230.5,-846.5 "/>
<text text-anchor="middle" x="2094.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="1958.5,-823.5 2230.5,-823.5 "/>
<text text-anchor="middle" x="2094.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="1958.5,-800.5 2230.5,-800.5 "/>
<text text-anchor="middle" x="2094.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1958.5,-777.5 2230.5,-777.5 "/>
<text text-anchor="middle" x="2094.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="1958.5,-754.5 2230.5,-754.5 "/>
<text text-anchor="middle" x="2094.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="1958.5,-731.5 2230.5,-731.5 "/>
<text text-anchor="middle" x="2094.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1958.5,-708.5 2230.5,-708.5 "/>
<text text-anchor="middle" x="2094.5" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1958.5,-685.5 2230.5,-685.5 "/>
<text text-anchor="middle" x="2094.5" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="2230.5,-662.5 2230.5,-1099.5 "/>
<text text-anchor="middle" x="2241" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2146.2301,-662.2972C2153.3036,-650.7605 2160.7321,-639.5786 2168.5,-629 2171.1245,-625.4259 2173.9382,-621.8919 2176.8875,-618.4186"/>
<polygon fill="#000000" stroke="#000000" points="2179.5218,-620.7231 2183.54,-610.9198 2174.2854,-616.0777 2179.5218,-620.7231"/>
<text text-anchor="middle" x="2213" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- sample -->
<g id="node3" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1110.5,-800.5C1110.5,-800.5 1424.5,-800.5 1424.5,-800.5 1430.5,-800.5 1436.5,-806.5 1436.5,-812.5 1436.5,-812.5 1436.5,-949.5 1436.5,-949.5 1436.5,-955.5 1430.5,-961.5 1424.5,-961.5 1424.5,-961.5 1110.5,-961.5 1110.5,-961.5 1104.5,-961.5 1098.5,-955.5 1098.5,-949.5 1098.5,-949.5 1098.5,-812.5 1098.5,-812.5 1098.5,-806.5 1104.5,-800.5 1110.5,-800.5"/>
<text text-anchor="middle" x="1132.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1166.5,-800.5 1166.5,-961.5 "/>
<text text-anchor="middle" x="1177" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1187.5,-800.5 1187.5,-961.5 "/>
<text text-anchor="middle" x="1301.5" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="1187.5,-938.5 1415.5,-938.5 "/>
<text text-anchor="middle" x="1301.5" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1187.5,-915.5 1415.5,-915.5 "/>
<text text-anchor="middle" x="1301.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1187.5,-892.5 1415.5,-892.5 "/>
<text text-anchor="middle" x="1301.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1187.5,-869.5 1415.5,-869.5 "/>
<text text-anchor="middle" x="1301.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1187.5,-846.5 1415.5,-846.5 "/>
<text text-anchor="middle" x="1301.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1187.5,-823.5 1415.5,-823.5 "/>
<text text-anchor="middle" x="1301.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="1415.5,-800.5 1415.5,-961.5 "/>
<text text-anchor="middle" x="1426" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node5" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M2613.5,-.5C2613.5,-.5 3003.5,-.5 3003.5,-.5 3009.5,-.5 3015.5,-6.5 3015.5,-12.5 3015.5,-12.5 3015.5,-195.5 3015.5,-195.5 3015.5,-201.5 3009.5,-207.5 3003.5,-207.5 3003.5,-207.5 2613.5,-207.5 2613.5,-207.5 2607.5,-207.5 2601.5,-201.5 2601.5,-195.5 2601.5,-195.5 2601.5,-12.5 2601.5,-12.5 2601.5,-6.5 2607.5,-.5 2613.5,-.5"/>
<text text-anchor="middle" x="2629.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="2657.5,-.5 2657.5,-207.5 "/>
<text text-anchor="middle" x="2668" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2678.5,-.5 2678.5,-207.5 "/>
<text text-anchor="middle" x="2836.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="2678.5,-184.5 2994.5,-184.5 "/>
<text text-anchor="middle" x="2836.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="2678.5,-161.5 2994.5,-161.5 "/>
<text text-anchor="middle" x="2836.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="2678.5,-138.5 2994.5,-138.5 "/>
<text text-anchor="middle" x="2836.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="2678.5,-115.5 2994.5,-115.5 "/>
<text text-anchor="middle" x="2836.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="2678.5,-92.5 2994.5,-92.5 "/>
<text text-anchor="middle" x="2836.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="2678.5,-69.5 2994.5,-69.5 "/>
<text text-anchor="middle" x="2836.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="2678.5,-46.5 2994.5,-46.5 "/>
<text text-anchor="middle" x="2836.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="2678.5,-23.5 2994.5,-23.5 "/>
<text text-anchor="middle" x="2836.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="2994.5,-.5 2994.5,-207.5 "/>
<text text-anchor="middle" x="3005" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge14" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1325.3334,-800.3853C1358.0433,-757.2381 1401.0126,-704.4067 1444.5,-662 1614.5898,-496.137 1156.8324,-632.4577 2083.5,-259 2247.4645,-192.9204 2444.1739,-153.1302 2591.2984,-130.4407"/>
<polygon fill="#000000" stroke="#000000" points="2592.0036,-133.8737 2601.3603,-128.9037 2590.9465,-126.9539 2592.0036,-133.8737"/>
<text text-anchor="middle" x="1634" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1311.4023,-800.2679C1342.1049,-751.9698 1387.7308,-693.9468 1444.5,-662 1549.7357,-602.7788 1873.609,-574.0797 2077.9378,-561.5238"/>
<polygon fill="#000000" stroke="#000000" points="2078.4129,-565.0015 2088.1823,-560.9016 2077.9885,-558.0144 2078.4129,-565.0015"/>
<text text-anchor="middle" x="1558" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_funding -->
<g id="node4" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M2619,-317C2619,-317 2998,-317 2998,-317 3004,-317 3010,-323 3010,-329 3010,-329 3010,-374 3010,-374 3010,-380 3004,-386 2998,-386 2998,-386 2619,-386 2619,-386 2613,-386 2607,-380 2607,-374 2607,-374 2607,-329 2607,-329 2607,-323 2613,-317 2619,-317"/>
<text text-anchor="middle" x="2666.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="2726,-317 2726,-386 "/>
<text text-anchor="middle" x="2736.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2747,-317 2747,-386 "/>
<text text-anchor="middle" x="2868" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="2747,-363 2989,-363 "/>
<text text-anchor="middle" x="2868" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="2747,-340 2989,-340 "/>
<text text-anchor="middle" x="2868" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="2989,-317 2989,-386 "/>
<text text-anchor="middle" x="2999.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge12" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2808.5,-316.8256C2808.5,-290.8629 2808.5,-253.7725 2808.5,-217.8091"/>
<polygon fill="#000000" stroke="#000000" points="2812.0001,-217.7056 2808.5,-207.7056 2805.0001,-217.7056 2812.0001,-217.7056"/>
<text text-anchor="middle" x="2870.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- study_personnel -->
<g id="node6" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M3040,-294C3040,-294 3347,-294 3347,-294 3353,-294 3359,-300 3359,-306 3359,-306 3359,-397 3359,-397 3359,-403 3353,-409 3347,-409 3347,-409 3040,-409 3040,-409 3034,-409 3028,-403 3028,-397 3028,-397 3028,-306 3028,-306 3028,-300 3034,-294 3040,-294"/>
<text text-anchor="middle" x="3095" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="3162,-294 3162,-409 "/>
<text text-anchor="middle" x="3172.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3183,-294 3183,-409 "/>
<text text-anchor="middle" x="3260.5" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="3183,-386 3338,-386 "/>
<text text-anchor="middle" x="3260.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="3183,-363 3338,-363 "/>
<text text-anchor="middle" x="3260.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="3183,-340 3338,-340 "/>
<text text-anchor="middle" x="3260.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="3183,-317 3338,-317 "/>
<text text-anchor="middle" x="3260.5" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="3338,-294 3338,-409 "/>
<text text-anchor="middle" x="3348.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge15" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3103.7205,-293.7846C3066.329,-269.7472 3021.6251,-241.009 2978.4548,-213.2566"/>
<polygon fill="#000000" stroke="#000000" points="2980.1482,-210.1845 2969.8438,-207.721 2976.3629,-216.0727 2980.1482,-210.1845"/>
<text text-anchor="middle" x="3082" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- pdx -->
<g id="node7" class="node">
<title>pdx</title>
<path fill="none" stroke="#000000" d="M998,-1335.5C998,-1335.5 1327,-1335.5 1327,-1335.5 1333,-1335.5 1339,-1341.5 1339,-1347.5 1339,-1347.5 1339,-1530.5 1339,-1530.5 1339,-1536.5 1333,-1542.5 1327,-1542.5 1327,-1542.5 998,-1542.5 998,-1542.5 992,-1542.5 986,-1536.5 986,-1530.5 986,-1530.5 986,-1347.5 986,-1347.5 986,-1341.5 992,-1335.5 998,-1335.5"/>
<text text-anchor="middle" x="1007.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
<polyline fill="none" stroke="#000000" points="1029,-1335.5 1029,-1542.5 "/>
<text text-anchor="middle" x="1039.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1050,-1335.5 1050,-1542.5 "/>
<text text-anchor="middle" x="1184" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">injection_type_and_site</text>
<polyline fill="none" stroke="#000000" points="1050,-1519.5 1318,-1519.5 "/>
<text text-anchor="middle" x="1184" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_id</text>
<polyline fill="none" stroke="#000000" points="1050,-1496.5 1318,-1496.5 "/>
<text text-anchor="middle" x="1184" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_type</text>
<polyline fill="none" stroke="#000000" points="1050,-1473.5 1318,-1473.5 "/>
<text text-anchor="middle" x="1184" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">mouse_strain</text>
<polyline fill="none" stroke="#000000" points="1050,-1450.5 1318,-1450.5 "/>
<text text-anchor="middle" x="1184" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">strain_immune_system_humanized</text>
<polyline fill="none" stroke="#000000" points="1050,-1427.5 1318,-1427.5 "/>
<text text-anchor="middle" x="1184" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_characterization_method</text>
<polyline fill="none" stroke="#000000" points="1050,-1404.5 1318,-1404.5 "/>
<text text-anchor="middle" x="1184" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_not_mus_or_ebv_origin</text>
<polyline fill="none" stroke="#000000" points="1050,-1381.5 1318,-1381.5 "/>
<text text-anchor="middle" x="1184" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_preparation</text>
<polyline fill="none" stroke="#000000" points="1050,-1358.5 1318,-1358.5 "/>
<text text-anchor="middle" x="1184" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_humanization</text>
<polyline fill="none" stroke="#000000" points="1318,-1335.5 1318,-1542.5 "/>
<text text-anchor="middle" x="1328.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1182.0036,-1335.3522C1201.6418,-1230.9891 1231.6388,-1071.5767 1250.3818,-971.9709"/>
<polygon fill="#000000" stroke="#000000" points="1253.8625,-972.3996 1252.2722,-961.9248 1246.9832,-971.1051 1253.8625,-972.3996"/>
<text text-anchor="middle" x="1245.5" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study_arm -->
<g id="node8" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M2104,-317C2104,-317 2401,-317 2401,-317 2407,-317 2413,-323 2413,-329 2413,-329 2413,-374 2413,-374 2413,-380 2407,-386 2401,-386 2401,-386 2104,-386 2104,-386 2098,-386 2092,-380 2092,-374 2092,-374 2092,-329 2092,-329 2092,-323 2098,-317 2104,-317"/>
<text text-anchor="middle" x="2138" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="2184,-317 2184,-386 "/>
<text text-anchor="middle" x="2194.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2205,-317 2205,-386 "/>
<text text-anchor="middle" x="2298.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="2205,-363 2392,-363 "/>
<text text-anchor="middle" x="2298.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="2205,-340 2392,-340 "/>
<text text-anchor="middle" x="2298.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="2392,-317 2392,-386 "/>
<text text-anchor="middle" x="2402.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2267.7014,-316.7608C2281.9597,-288.1979 2305.9633,-248.8375 2338.5,-226 2380.5702,-196.4709 2489.2016,-167.3921 2591.438,-145.0347"/>
<polygon fill="#000000" stroke="#000000" points="2592.2793,-148.4337 2601.3094,-142.8923 2590.7945,-141.5929 2592.2793,-148.4337"/>
<text text-anchor="middle" x="2387" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- imaging_file -->
<g id="node9" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M1369.5,-1278C1369.5,-1278 1703.5,-1278 1703.5,-1278 1709.5,-1278 1715.5,-1284 1715.5,-1290 1715.5,-1290 1715.5,-1588 1715.5,-1588 1715.5,-1594 1709.5,-1600 1703.5,-1600 1703.5,-1600 1369.5,-1600 1369.5,-1600 1363.5,-1600 1357.5,-1594 1357.5,-1588 1357.5,-1588 1357.5,-1290 1357.5,-1290 1357.5,-1284 1363.5,-1278 1369.5,-1278"/>
<text text-anchor="middle" x="1409.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="1461.5,-1278 1461.5,-1600 "/>
<text text-anchor="middle" x="1472" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1482.5,-1278 1482.5,-1600 "/>
<text text-anchor="middle" x="1588.5" y="-1584.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1482.5,-1577 1694.5,-1577 "/>
<text text-anchor="middle" x="1588.5" y="-1561.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1482.5,-1554 1694.5,-1554 "/>
<text text-anchor="middle" x="1588.5" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1482.5,-1531 1694.5,-1531 "/>
<text text-anchor="middle" x="1588.5" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1482.5,-1508 1694.5,-1508 "/>
<text text-anchor="middle" x="1588.5" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1482.5,-1485 1694.5,-1485 "/>
<text text-anchor="middle" x="1588.5" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1482.5,-1462 1694.5,-1462 "/>
<text text-anchor="middle" x="1588.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1482.5,-1439 1694.5,-1439 "/>
<text text-anchor="middle" x="1588.5" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1482.5,-1416 1694.5,-1416 "/>
<text text-anchor="middle" x="1588.5" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1482.5,-1393 1694.5,-1393 "/>
<text text-anchor="middle" x="1588.5" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="1482.5,-1370 1694.5,-1370 "/>
<text text-anchor="middle" x="1588.5" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="1482.5,-1347 1694.5,-1347 "/>
<text text-anchor="middle" x="1588.5" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="1482.5,-1324 1694.5,-1324 "/>
<text text-anchor="middle" x="1588.5" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1482.5,-1301 1694.5,-1301 "/>
<text text-anchor="middle" x="1588.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="1694.5,-1278 1694.5,-1600 "/>
<text text-anchor="middle" x="1705" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1458.8746,-1277.9777C1410.7091,-1178.0657 1350.6159,-1053.4113 1310.7544,-970.7247"/>
<polygon fill="#000000" stroke="#000000" points="1313.8538,-969.094 1306.3584,-961.606 1307.5483,-972.1338 1313.8538,-969.094"/>
<text text-anchor="middle" x="1441" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- study_admin -->
<g id="node10" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M3389.5,-259.5C3389.5,-259.5 3715.5,-259.5 3715.5,-259.5 3721.5,-259.5 3727.5,-265.5 3727.5,-271.5 3727.5,-271.5 3727.5,-431.5 3727.5,-431.5 3727.5,-437.5 3721.5,-443.5 3715.5,-443.5 3715.5,-443.5 3389.5,-443.5 3389.5,-443.5 3383.5,-443.5 3377.5,-437.5 3377.5,-431.5 3377.5,-431.5 3377.5,-271.5 3377.5,-271.5 3377.5,-265.5 3383.5,-259.5 3389.5,-259.5"/>
<text text-anchor="middle" x="3431.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="3485.5,-259.5 3485.5,-443.5 "/>
<text text-anchor="middle" x="3496" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3506.5,-259.5 3506.5,-443.5 "/>
<text text-anchor="middle" x="3606.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="3506.5,-420.5 3706.5,-420.5 "/>
<text text-anchor="middle" x="3606.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="3506.5,-397.5 3706.5,-397.5 "/>
<text text-anchor="middle" x="3606.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="3506.5,-374.5 3706.5,-374.5 "/>
<text text-anchor="middle" x="3606.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="3506.5,-351.5 3706.5,-351.5 "/>
<text text-anchor="middle" x="3606.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="3506.5,-328.5 3706.5,-328.5 "/>
<text text-anchor="middle" x="3606.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="3506.5,-305.5 3706.5,-305.5 "/>
<text text-anchor="middle" x="3606.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="3506.5,-282.5 3706.5,-282.5 "/>
<text text-anchor="middle" x="3606.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="3706.5,-259.5 3706.5,-443.5 "/>
<text text-anchor="middle" x="3717" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge6" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3377.2991,-262.4657C3374.3536,-261.2816 3371.4191,-260.1252 3368.5,-259 3257.8266,-216.3382 3130.6838,-180.1676 3025.547,-153.525"/>
<polygon fill="#000000" stroke="#000000" points="3026.3182,-150.11 3015.7658,-151.0577 3024.606,-156.8974 3026.3182,-150.11"/>
<text text-anchor="middle" x="3365" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- clinical_measure_file -->
<g id="node11" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M2402.5,-754.5C2402.5,-754.5 2754.5,-754.5 2754.5,-754.5 2760.5,-754.5 2766.5,-760.5 2766.5,-766.5 2766.5,-766.5 2766.5,-995.5 2766.5,-995.5 2766.5,-1001.5 2760.5,-1007.5 2754.5,-1007.5 2754.5,-1007.5 2402.5,-1007.5 2402.5,-1007.5 2396.5,-1007.5 2390.5,-1001.5 2390.5,-995.5 2390.5,-995.5 2390.5,-766.5 2390.5,-766.5 2390.5,-760.5 2396.5,-754.5 2402.5,-754.5"/>
<text text-anchor="middle" x="2474" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="2557.5,-754.5 2557.5,-1007.5 "/>
<text text-anchor="middle" x="2568" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2578.5,-754.5 2578.5,-1007.5 "/>
<text text-anchor="middle" x="2662" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2578.5,-984.5 2745.5,-984.5 "/>
<text text-anchor="middle" x="2662" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2578.5,-961.5 2745.5,-961.5 "/>
<text text-anchor="middle" x="2662" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2578.5,-938.5 2745.5,-938.5 "/>
<text text-anchor="middle" x="2662" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2578.5,-915.5 2745.5,-915.5 "/>
<text text-anchor="middle" x="2662" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2578.5,-892.5 2745.5,-892.5 "/>
<text text-anchor="middle" x="2662" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2578.5,-869.5 2745.5,-869.5 "/>
<text text-anchor="middle" x="2662" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2578.5,-846.5 2745.5,-846.5 "/>
<text text-anchor="middle" x="2662" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2578.5,-823.5 2745.5,-823.5 "/>
<text text-anchor="middle" x="2662" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2578.5,-800.5 2745.5,-800.5 "/>
<text text-anchor="middle" x="2662" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2578.5,-777.5 2745.5,-777.5 "/>
<text text-anchor="middle" x="2662" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="2745.5,-754.5 2745.5,-1007.5 "/>
<text text-anchor="middle" x="2756" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge9" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2569.7973,-754.3571C2561.2185,-597.814 2554.9556,-341.9208 2598.5,-259 2606.8546,-243.0905 2617.66,-228.3905 2629.9565,-214.9072"/>
<polygon fill="#000000" stroke="#000000" points="2632.598,-217.2081 2636.9352,-207.5417 2627.5166,-212.3935 2632.598,-217.2081"/>
<text text-anchor="middle" x="2650.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2484.5584,-754.4972C2453.5453,-720.1427 2416.6105,-685.8814 2376.5,-662 2348.5286,-645.3461 2331.4972,-663.5934 2305.5,-644 2296.669,-637.3443 2289.0524,-628.7538 2282.5692,-619.5144"/>
<polygon fill="#000000" stroke="#000000" points="2285.3307,-617.3418 2276.9317,-610.8836 2279.4701,-621.1699 2285.3307,-617.3418"/>
<text text-anchor="middle" x="2435" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- sequencing_file -->
<g id="node12" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M12,-1151.5C12,-1151.5 481,-1151.5 481,-1151.5 487,-1151.5 493,-1157.5 493,-1163.5 493,-1163.5 493,-1714.5 493,-1714.5 493,-1720.5 487,-1726.5 481,-1726.5 481,-1726.5 12,-1726.5 12,-1726.5 6,-1726.5 0,-1720.5 0,-1714.5 0,-1714.5 0,-1163.5 0,-1163.5 0,-1157.5 6,-1151.5 12,-1151.5"/>
<text text-anchor="middle" x="64" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="128,-1151.5 128,-1726.5 "/>
<text text-anchor="middle" x="138.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="149,-1151.5 149,-1726.5 "/>
<text text-anchor="middle" x="310.5" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="149,-1703.5 472,-1703.5 "/>
<text text-anchor="middle" x="310.5" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="149,-1680.5 472,-1680.5 "/>
<text text-anchor="middle" x="310.5" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="149,-1657.5 472,-1657.5 "/>
<text text-anchor="middle" x="310.5" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="149,-1634.5 472,-1634.5 "/>
<text text-anchor="middle" x="310.5" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="149,-1611.5 472,-1611.5 "/>
<text text-anchor="middle" x="310.5" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="149,-1588.5 472,-1588.5 "/>
<text text-anchor="middle" x="310.5" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="149,-1565.5 472,-1565.5 "/>
<text text-anchor="middle" x="310.5" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="149,-1542.5 472,-1542.5 "/>
<text text-anchor="middle" x="310.5" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="149,-1519.5 472,-1519.5 "/>
<text text-anchor="middle" x="310.5" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="149,-1496.5 472,-1496.5 "/>
<text text-anchor="middle" x="310.5" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="149,-1473.5 472,-1473.5 "/>
<text text-anchor="middle" x="310.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="149,-1450.5 472,-1450.5 "/>
<text text-anchor="middle" x="310.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="149,-1427.5 472,-1427.5 "/>
<text text-anchor="middle" x="310.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="149,-1404.5 472,-1404.5 "/>
<text text-anchor="middle" x="310.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="149,-1381.5 472,-1381.5 "/>
<text text-anchor="middle" x="310.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="149,-1358.5 472,-1358.5 "/>
<text text-anchor="middle" x="310.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="149,-1335.5 472,-1335.5 "/>
<text text-anchor="middle" x="310.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="149,-1312.5 472,-1312.5 "/>
<text text-anchor="middle" x="310.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="149,-1289.5 472,-1289.5 "/>
<text text-anchor="middle" x="310.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="149,-1266.5 472,-1266.5 "/>
<text text-anchor="middle" x="310.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="149,-1243.5 472,-1243.5 "/>
<text text-anchor="middle" x="310.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="149,-1220.5 472,-1220.5 "/>
<text text-anchor="middle" x="310.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="149,-1197.5 472,-1197.5 "/>
<text text-anchor="middle" x="310.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="149,-1174.5 472,-1174.5 "/>
<text text-anchor="middle" x="310.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="472,-1151.5 472,-1726.5 "/>
<text text-anchor="middle" x="482.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M493.2235,-1156.7029C495.971,-1154.7664 498.73,-1152.8647 501.5,-1151 682.6681,-1029.0434 925.0028,-955.8269 1088.1776,-917.0145"/>
<polygon fill="#000000" stroke="#000000" points="1089.3921,-920.3241 1098.3214,-914.6217 1087.785,-913.5111 1089.3921,-920.3241"/>
<text text-anchor="middle" x="605" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sample_diagnosis -->
<g id="node13" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M523,-1220.5C523,-1220.5 956,-1220.5 956,-1220.5 962,-1220.5 968,-1226.5 968,-1232.5 968,-1232.5 968,-1645.5 968,-1645.5 968,-1651.5 962,-1657.5 956,-1657.5 956,-1657.5 523,-1657.5 523,-1657.5 517,-1657.5 511,-1651.5 511,-1645.5 511,-1645.5 511,-1232.5 511,-1232.5 511,-1226.5 517,-1220.5 523,-1220.5"/>
<text text-anchor="middle" x="582.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="654,-1220.5 654,-1657.5 "/>
<text text-anchor="middle" x="664.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="675,-1220.5 675,-1657.5 "/>
<text text-anchor="middle" x="811" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="675,-1634.5 947,-1634.5 "/>
<text text-anchor="middle" x="811" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="675,-1611.5 947,-1611.5 "/>
<text text-anchor="middle" x="811" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="675,-1588.5 947,-1588.5 "/>
<text text-anchor="middle" x="811" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="675,-1565.5 947,-1565.5 "/>
<text text-anchor="middle" x="811" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="675,-1542.5 947,-1542.5 "/>
<text text-anchor="middle" x="811" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="675,-1519.5 947,-1519.5 "/>
<text text-anchor="middle" x="811" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="675,-1496.5 947,-1496.5 "/>
<text text-anchor="middle" x="811" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="675,-1473.5 947,-1473.5 "/>
<text text-anchor="middle" x="811" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="675,-1450.5 947,-1450.5 "/>
<text text-anchor="middle" x="811" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="675,-1427.5 947,-1427.5 "/>
<text text-anchor="middle" x="811" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="675,-1404.5 947,-1404.5 "/>
<text text-anchor="middle" x="811" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="675,-1381.5 947,-1381.5 "/>
<text text-anchor="middle" x="811" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="675,-1358.5 947,-1358.5 "/>
<text text-anchor="middle" x="811" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="675,-1335.5 947,-1335.5 "/>
<text text-anchor="middle" x="811" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="675,-1312.5 947,-1312.5 "/>
<text text-anchor="middle" x="811" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="675,-1289.5 947,-1289.5 "/>
<text text-anchor="middle" x="811" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="675,-1266.5 947,-1266.5 "/>
<text text-anchor="middle" x="811" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="675,-1243.5 947,-1243.5 "/>
<text text-anchor="middle" x="811" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="947,-1220.5 947,-1657.5 "/>
<text text-anchor="middle" x="957.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M914.0648,-1220.4655C934.6581,-1196.6218 955.7397,-1173.0321 976.5,-1151 1036.7716,-1087.036 1109.206,-1019.799 1166.7294,-968.4223"/>
<polygon fill="#000000" stroke="#000000" points="1169.2479,-970.866 1174.3848,-961.5998 1164.5906,-965.6401 1169.2479,-970.866"/>
<text text-anchor="middle" x="1080.5" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
<!-- synonym -->
<g id="node14" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M2155,-1416C2155,-1416 2456,-1416 2456,-1416 2462,-1416 2468,-1422 2468,-1428 2468,-1428 2468,-1450 2468,-1450 2468,-1456 2462,-1462 2456,-1462 2456,-1462 2155,-1462 2155,-1462 2149,-1462 2143,-1456 2143,-1450 2143,-1450 2143,-1428 2143,-1428 2143,-1422 2149,-1416 2155,-1416"/>
<text text-anchor="middle" x="2183" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="2223,-1416 2223,-1462 "/>
<text text-anchor="middle" x="2233.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2244,-1416 2244,-1462 "/>
<text text-anchor="middle" x="2345.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="2244,-1439 2447,-1439 "/>
<text text-anchor="middle" x="2345.5" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="2447,-1416 2447,-1462 "/>
<text text-anchor="middle" x="2457.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2299.4012,-1415.7545C2283.2768,-1359.3962 2233.7836,-1215.3871 2134.5,-1151 2027.8855,-1081.8587 1977.1651,-1128.1539 1850.5,-1118 1805.489,-1114.3918 1484.8064,-1120.357 1444.5,-1100 1388.9273,-1071.9326 1344.8425,-1017.5925 1314.5689,-970.0659"/>
<polygon fill="#000000" stroke="#000000" points="1317.5356,-968.2087 1309.2657,-961.586 1311.6006,-971.9204 1317.5356,-968.2087"/>
<text text-anchor="middle" x="2140" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge20" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2445.8496,-1415.9498C2809.744,-1352.2397 3755.5,-1159.8364 3755.5,-881 3755.5,-881 3755.5,-881 3755.5,-351.5 3755.5,-309.5306 3766.7221,-288.1214 3736.5,-259 3637.5377,-163.6417 3267.7281,-126.6746 3025.8877,-112.5366"/>
<polygon fill="#000000" stroke="#000000" points="3025.7316,-109.022 3015.547,-111.9415 3025.3293,-116.0104 3025.7316,-109.022"/>
<text text-anchor="middle" x="3798" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2304.2868,-1415.7911C2299.3419,-1321.7209 2280.0404,-959.6408 2260.5,-662 2259.6283,-648.7227 2258.6339,-634.5405 2257.6494,-620.9455"/>
<polygon fill="#000000" stroke="#000000" points="2261.1195,-620.4071 2256.9007,-610.6885 2254.1381,-620.9168 2261.1195,-620.4071"/>
<text text-anchor="middle" x="2329" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- methylation_array_file -->
<g id="node15" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M1746,-1324C1746,-1324 2113,-1324 2113,-1324 2119,-1324 2125,-1330 2125,-1336 2125,-1336 2125,-1542 2125,-1542 2125,-1548 2119,-1554 2113,-1554 2113,-1554 1746,-1554 1746,-1554 1740,-1554 1734,-1548 1734,-1542 1734,-1542 1734,-1336 1734,-1336 1734,-1330 1740,-1324 1746,-1324"/>
<text text-anchor="middle" x="1823" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="1912,-1324 1912,-1554 "/>
<text text-anchor="middle" x="1922.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1933,-1324 1933,-1554 "/>
<text text-anchor="middle" x="2018.5" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1933,-1531 2104,-1531 "/>
<text text-anchor="middle" x="2018.5" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1933,-1508 2104,-1508 "/>
<text text-anchor="middle" x="2018.5" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1933,-1485 2104,-1485 "/>
<text text-anchor="middle" x="2018.5" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1933,-1462 2104,-1462 "/>
<text text-anchor="middle" x="2018.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1933,-1439 2104,-1439 "/>
<text text-anchor="middle" x="2018.5" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1933,-1416 2104,-1416 "/>
<text text-anchor="middle" x="2018.5" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1933,-1393 2104,-1393 "/>
<text text-anchor="middle" x="2018.5" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1933,-1370 2104,-1370 "/>
<text text-anchor="middle" x="2018.5" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="1933,-1347 2104,-1347 "/>
<text text-anchor="middle" x="2018.5" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="2104,-1324 2104,-1554 "/>
<text text-anchor="middle" x="2114.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1875.0869,-1323.7157C1840.444,-1262.8965 1789.7633,-1192.4808 1724.5,-1151 1671.1232,-1117.0741 1498.8886,-1132.2789 1444.5,-1100 1392.0609,-1068.8782 1348.7016,-1016.091 1318.0236,-970.1402"/>
<polygon fill="#000000" stroke="#000000" points="1320.8595,-968.0825 1312.4436,-961.6465 1315.0091,-971.926 1320.8595,-968.0825"/>
<text text-anchor="middle" x="1755" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- publication -->
<g id="node16" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M3795.5,-333.5C3795.5,-333.5 4005.5,-333.5 4005.5,-333.5 4011.5,-333.5 4017.5,-339.5 4017.5,-345.5 4017.5,-345.5 4017.5,-357.5 4017.5,-357.5 4017.5,-363.5 4011.5,-369.5 4005.5,-369.5 4005.5,-369.5 3795.5,-369.5 3795.5,-369.5 3789.5,-369.5 3783.5,-363.5 3783.5,-357.5 3783.5,-357.5 3783.5,-345.5 3783.5,-345.5 3783.5,-339.5 3789.5,-333.5 3795.5,-333.5"/>
<text text-anchor="middle" x="3832" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="3880.5,-333.5 3880.5,-369.5 "/>
<text text-anchor="middle" x="3891" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3901.5,-333.5 3901.5,-369.5 "/>
<text text-anchor="middle" x="3949" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="3996.5,-333.5 3996.5,-369.5 "/>
<text text-anchor="middle" x="4007" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge7" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3887.6541,-333.2236C3866.5964,-304.869 3821.8051,-250.952 3769.5,-226 3641.9601,-165.1574 3267.7687,-131.6229 3025.7005,-115.7618"/>
<polygon fill="#000000" stroke="#000000" points="3025.9175,-112.2686 3015.7115,-115.1123 3025.4633,-119.2538 3025.9175,-112.2686"/>
<text text-anchor="middle" x="3845.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge16" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2369.9436,-495.241C2389.9221,-480.899 2408.6541,-463.8369 2422.5,-444 2470.702,-374.9413 2410.3276,-324.3088 2463.5,-259 2496.995,-217.8599 2543.7108,-187.2489 2591.9662,-164.6188"/>
<polygon fill="#000000" stroke="#000000" points="2593.6755,-167.6857 2601.3123,-160.3421 2590.7628,-161.3205 2593.6755,-167.6857"/>
<text text-anchor="middle" x="2514" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge17" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M2252.5,-495.2582C2252.5,-463.875 2252.5,-425.6377 2252.5,-396.4898"/>
<polygon fill="#000000" stroke="#000000" points="2256.0001,-396.1919 2252.5,-386.1919 2249.0001,-396.192 2256.0001,-396.1919"/>
<text text-anchor="middle" x="2303" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
</g>
</svg>
</div>
