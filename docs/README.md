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
<svg width="5059pt" height="1758pt"
 viewBox="0.00 0.00 5058.50 1758.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1754)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1754 5054.5,-1754 5054.5,4 -4,4"/>
<!-- study_funding -->
<g id="node1" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M1936,-374.5C1936,-374.5 2315,-374.5 2315,-374.5 2321,-374.5 2327,-380.5 2327,-386.5 2327,-386.5 2327,-431.5 2327,-431.5 2327,-437.5 2321,-443.5 2315,-443.5 2315,-443.5 1936,-443.5 1936,-443.5 1930,-443.5 1924,-437.5 1924,-431.5 1924,-431.5 1924,-386.5 1924,-386.5 1924,-380.5 1930,-374.5 1936,-374.5"/>
<text text-anchor="middle" x="1983.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="2043,-374.5 2043,-443.5 "/>
<text text-anchor="middle" x="2053.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2064,-374.5 2064,-443.5 "/>
<text text-anchor="middle" x="2185" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="2064,-420.5 2306,-420.5 "/>
<text text-anchor="middle" x="2185" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="2064,-397.5 2306,-397.5 "/>
<text text-anchor="middle" x="2185" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="2306,-374.5 2306,-443.5 "/>
<text text-anchor="middle" x="2316.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node5" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M3795.5,-.5C3795.5,-.5 4185.5,-.5 4185.5,-.5 4191.5,-.5 4197.5,-6.5 4197.5,-12.5 4197.5,-12.5 4197.5,-264.5 4197.5,-264.5 4197.5,-270.5 4191.5,-276.5 4185.5,-276.5 4185.5,-276.5 3795.5,-276.5 3795.5,-276.5 3789.5,-276.5 3783.5,-270.5 3783.5,-264.5 3783.5,-264.5 3783.5,-12.5 3783.5,-12.5 3783.5,-6.5 3789.5,-.5 3795.5,-.5"/>
<text text-anchor="middle" x="3811.5" y="-134.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="3839.5,-.5 3839.5,-276.5 "/>
<text text-anchor="middle" x="3850" y="-134.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3860.5,-.5 3860.5,-276.5 "/>
<text text-anchor="middle" x="4018.5" y="-261.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="3860.5,-253.5 4176.5,-253.5 "/>
<text text-anchor="middle" x="4018.5" y="-238.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="3860.5,-230.5 4176.5,-230.5 "/>
<text text-anchor="middle" x="4018.5" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_shorthand</text>
<polyline fill="none" stroke="#000000" points="3860.5,-207.5 4176.5,-207.5 "/>
<text text-anchor="middle" x="4018.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="3860.5,-184.5 4176.5,-184.5 "/>
<text text-anchor="middle" x="4018.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="3860.5,-161.5 4176.5,-161.5 "/>
<text text-anchor="middle" x="4018.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="3860.5,-138.5 4176.5,-138.5 "/>
<text text-anchor="middle" x="4018.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="3860.5,-115.5 4176.5,-115.5 "/>
<text text-anchor="middle" x="4018.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="3860.5,-92.5 4176.5,-92.5 "/>
<text text-anchor="middle" x="4018.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="3860.5,-69.5 4176.5,-69.5 "/>
<text text-anchor="middle" x="4018.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="3860.5,-46.5 4176.5,-46.5 "/>
<text text-anchor="middle" x="4018.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="3860.5,-23.5 4176.5,-23.5 "/>
<text text-anchor="middle" x="4018.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="4176.5,-.5 4176.5,-276.5 "/>
<text text-anchor="middle" x="4187" y="-134.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge10" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2143.232,-374.4371C2158.9004,-347.8078 2184.3994,-312.6519 2217.5,-295 2351.8264,-223.3664 3329.9222,-169.2827 3773.1865,-148.1759"/>
<polygon fill="#000000" stroke="#000000" points="3773.411,-151.6693 3783.2337,-147.6988 3773.0789,-144.6772 3773.411,-151.6693"/>
<text text-anchor="middle" x="2279.5" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- sample -->
<g id="node2" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1883.5,-823.5C1883.5,-823.5 2197.5,-823.5 2197.5,-823.5 2203.5,-823.5 2209.5,-829.5 2209.5,-835.5 2209.5,-835.5 2209.5,-972.5 2209.5,-972.5 2209.5,-978.5 2203.5,-984.5 2197.5,-984.5 2197.5,-984.5 1883.5,-984.5 1883.5,-984.5 1877.5,-984.5 1871.5,-978.5 1871.5,-972.5 1871.5,-972.5 1871.5,-835.5 1871.5,-835.5 1871.5,-829.5 1877.5,-823.5 1883.5,-823.5"/>
<text text-anchor="middle" x="1905.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1939.5,-823.5 1939.5,-984.5 "/>
<text text-anchor="middle" x="1950" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1960.5,-823.5 1960.5,-984.5 "/>
<text text-anchor="middle" x="2074.5" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="1960.5,-961.5 2188.5,-961.5 "/>
<text text-anchor="middle" x="2074.5" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1960.5,-938.5 2188.5,-938.5 "/>
<text text-anchor="middle" x="2074.5" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1960.5,-915.5 2188.5,-915.5 "/>
<text text-anchor="middle" x="2074.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1960.5,-892.5 2188.5,-892.5 "/>
<text text-anchor="middle" x="2074.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1960.5,-869.5 2188.5,-869.5 "/>
<text text-anchor="middle" x="2074.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1960.5,-846.5 2188.5,-846.5 "/>
<text text-anchor="middle" x="2074.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="2188.5,-823.5 2188.5,-984.5 "/>
<text text-anchor="middle" x="2199" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node3" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M3233.5,-541.5C3233.5,-541.5 3537.5,-541.5 3537.5,-541.5 3543.5,-541.5 3549.5,-547.5 3549.5,-553.5 3549.5,-553.5 3549.5,-644.5 3549.5,-644.5 3549.5,-650.5 3543.5,-656.5 3537.5,-656.5 3537.5,-656.5 3233.5,-656.5 3233.5,-656.5 3227.5,-656.5 3221.5,-650.5 3221.5,-644.5 3221.5,-644.5 3221.5,-553.5 3221.5,-553.5 3221.5,-547.5 3227.5,-541.5 3233.5,-541.5"/>
<text text-anchor="middle" x="3269.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="3317.5,-541.5 3317.5,-656.5 "/>
<text text-anchor="middle" x="3328" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3338.5,-541.5 3338.5,-656.5 "/>
<text text-anchor="middle" x="3433.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="3338.5,-633.5 3528.5,-633.5 "/>
<text text-anchor="middle" x="3433.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="3338.5,-610.5 3528.5,-610.5 "/>
<text text-anchor="middle" x="3433.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="3338.5,-587.5 3528.5,-587.5 "/>
<text text-anchor="middle" x="3433.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="3338.5,-564.5 3528.5,-564.5 "/>
<text text-anchor="middle" x="3433.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="3528.5,-541.5 3528.5,-656.5 "/>
<text text-anchor="middle" x="3539" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2092.5353,-823.2887C2123.8283,-781.7415 2167.463,-734.3928 2218.5,-708 2277.3582,-677.5626 2300.9322,-699.5698 2366.5,-690 2405.7593,-684.27 2415.135,-679.9521 2454.5,-675 2717.1659,-641.9568 3023.4171,-620.1512 3210.8567,-608.6878"/>
<polygon fill="#000000" stroke="#000000" points="3211.3121,-612.1667 3221.081,-608.0656 3210.8868,-605.1796 3211.3121,-612.1667"/>
<text text-anchor="middle" x="2491" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge19" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2098.7332,-823.4488C2130.4692,-784.2396 2172.5968,-738.9973 2218.5,-708 2714.6782,-372.943 3420.8455,-224.5681 3773.1314,-168.1611"/>
<polygon fill="#000000" stroke="#000000" points="3773.8668,-171.5882 3783.1924,-166.5598 3772.7665,-164.6752 3773.8668,-171.5882"/>
<text text-anchor="middle" x="2613" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge13" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3508.5353,-541.499C3534.8792,-526.5436 3561.636,-509.1734 3584.5,-490 3655.2363,-430.6818 3646.8346,-390.7986 3714.5,-328 3733.3885,-310.47 3754.0129,-293.3281 3775.2052,-276.9657"/>
<polygon fill="#000000" stroke="#000000" points="3777.5364,-279.5891 3783.3528,-270.7336 3773.2835,-274.0291 3777.5364,-279.5891"/>
<text text-anchor="middle" x="3765" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_arm -->
<g id="node6" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M3267,-374.5C3267,-374.5 3564,-374.5 3564,-374.5 3570,-374.5 3576,-380.5 3576,-386.5 3576,-386.5 3576,-431.5 3576,-431.5 3576,-437.5 3570,-443.5 3564,-443.5 3564,-443.5 3267,-443.5 3267,-443.5 3261,-443.5 3255,-437.5 3255,-431.5 3255,-431.5 3255,-386.5 3255,-386.5 3255,-380.5 3261,-374.5 3267,-374.5"/>
<text text-anchor="middle" x="3301" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="3347,-374.5 3347,-443.5 "/>
<text text-anchor="middle" x="3357.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3368,-374.5 3368,-443.5 "/>
<text text-anchor="middle" x="3461.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="3368,-420.5 3555,-420.5 "/>
<text text-anchor="middle" x="3461.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="3368,-397.5 3555,-397.5 "/>
<text text-anchor="middle" x="3461.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="3555,-374.5 3555,-443.5 "/>
<text text-anchor="middle" x="3565.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge14" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M3394.5824,-541.4781C3399.028,-513.3226 3404.2995,-479.9365 3408.4383,-453.7239"/>
<polygon fill="#000000" stroke="#000000" points="3411.9195,-454.1171 3410.0221,-443.6935 3405.0052,-453.0253 3411.9195,-454.1171"/>
<text text-anchor="middle" x="3451" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- follow_up -->
<g id="node4" class="node">
<title>follow_up</title>
<path fill="none" stroke="#000000" d="M2240,-800.5C2240,-800.5 2603,-800.5 2603,-800.5 2609,-800.5 2615,-806.5 2615,-812.5 2615,-812.5 2615,-995.5 2615,-995.5 2615,-1001.5 2609,-1007.5 2603,-1007.5 2603,-1007.5 2240,-1007.5 2240,-1007.5 2234,-1007.5 2228,-1001.5 2228,-995.5 2228,-995.5 2228,-812.5 2228,-812.5 2228,-806.5 2234,-800.5 2240,-800.5"/>
<text text-anchor="middle" x="2270.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
<polyline fill="none" stroke="#000000" points="2313,-800.5 2313,-1007.5 "/>
<text text-anchor="middle" x="2323.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2334,-800.5 2334,-1007.5 "/>
<text text-anchor="middle" x="2464" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event</text>
<polyline fill="none" stroke="#000000" points="2334,-984.5 2594,-984.5 "/>
<text text-anchor="middle" x="2464" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity</text>
<polyline fill="none" stroke="#000000" points="2334,-961.5 2594,-961.5 "/>
<text text-anchor="middle" x="2464" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity_method_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2334,-938.5 2594,-938.5 "/>
<text text-anchor="middle" x="2464" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_follow_up</text>
<polyline fill="none" stroke="#000000" points="2334,-915.5 2594,-915.5 "/>
<text text-anchor="middle" x="2464" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_response</text>
<polyline fill="none" stroke="#000000" points="2334,-892.5 2594,-892.5 "/>
<text text-anchor="middle" x="2464" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_category</text>
<polyline fill="none" stroke="#000000" points="2334,-869.5 2594,-869.5 "/>
<text text-anchor="middle" x="2464" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_id</text>
<polyline fill="none" stroke="#000000" points="2334,-846.5 2594,-846.5 "/>
<text text-anchor="middle" x="2464" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_other</text>
<polyline fill="none" stroke="#000000" points="2334,-823.5 2594,-823.5 "/>
<text text-anchor="middle" x="2464" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">risk_factor</text>
<polyline fill="none" stroke="#000000" points="2594,-800.5 2594,-1007.5 "/>
<text text-anchor="middle" x="2604.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2453.3007,-800.4753C2472.9277,-754.3863 2503.0649,-704.0563 2547.5,-675 2601.6375,-639.5992 2981.9928,-616.8042 3211.2555,-606.1174"/>
<polygon fill="#000000" stroke="#000000" points="3211.5511,-609.6076 3221.3786,-605.6488 3211.2274,-602.6151 3211.5511,-609.6076"/>
<text text-anchor="middle" x="2592.5" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3453.7165,-374.281C3482.3322,-349.6482 3523.3096,-317.1563 3563.5,-295 3629.0421,-258.8678 3704.591,-228.0364 3773.7498,-203.5342"/>
<polygon fill="#000000" stroke="#000000" points="3775.1912,-206.7375 3783.4643,-200.1189 3772.8695,-200.1337 3775.1912,-206.7375"/>
<text text-anchor="middle" x="3612" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node7" class="node">
<title>single_cell_sequencing_file</title>
<path fill="none" stroke="#000000" d="M12,-1151.5C12,-1151.5 621,-1151.5 621,-1151.5 627,-1151.5 633,-1157.5 633,-1163.5 633,-1163.5 633,-1737.5 633,-1737.5 633,-1743.5 627,-1749.5 621,-1749.5 621,-1749.5 12,-1749.5 12,-1749.5 6,-1749.5 0,-1743.5 0,-1737.5 0,-1737.5 0,-1163.5 0,-1163.5 0,-1157.5 6,-1151.5 12,-1151.5"/>
<text text-anchor="middle" x="106" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
<polyline fill="none" stroke="#000000" points="212,-1151.5 212,-1749.5 "/>
<text text-anchor="middle" x="222.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="233,-1151.5 233,-1749.5 "/>
<text text-anchor="middle" x="422.5" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">Cell_Barcode</text>
<polyline fill="none" stroke="#000000" points="233,-1726.5 612,-1726.5 "/>
<text text-anchor="middle" x="422.5" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">Cryopreserved_Cells_in_Sample</text>
<polyline fill="none" stroke="#000000" points="233,-1703.5 612,-1703.5 "/>
<text text-anchor="middle" x="422.5" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">Dissociation_Method</text>
<polyline fill="none" stroke="#000000" points="233,-1680.5 612,-1680.5 "/>
<text text-anchor="middle" x="422.5" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">End_Bias</text>
<polyline fill="none" stroke="#000000" points="233,-1657.5 612,-1657.5 "/>
<text text-anchor="middle" x="422.5" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">Input_Cells_and_Nuclei</text>
<polyline fill="none" stroke="#000000" points="233,-1634.5 612,-1634.5 "/>
<text text-anchor="middle" x="422.5" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">Library_Construction_Method</text>
<polyline fill="none" stroke="#000000" points="233,-1611.5 612,-1611.5 "/>
<text text-anchor="middle" x="422.5" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">Library_Preparation_Date</text>
<polyline fill="none" stroke="#000000" points="233,-1588.5 612,-1588.5 "/>
<text text-anchor="middle" x="422.5" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">Nucleic_Acid_Capture_Date</text>
<polyline fill="none" stroke="#000000" points="233,-1565.5 612,-1565.5 "/>
<text text-anchor="middle" x="422.5" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">Paired_End</text>
<polyline fill="none" stroke="#000000" points="233,-1542.5 612,-1542.5 "/>
<text text-anchor="middle" x="422.5" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">Protocols_Link</text>
<polyline fill="none" stroke="#000000" points="233,-1519.5 612,-1519.5 "/>
<text text-anchor="middle" x="422.5" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">Read1</text>
<polyline fill="none" stroke="#000000" points="233,-1496.5 612,-1496.5 "/>
<text text-anchor="middle" x="422.5" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">Read2</text>
<polyline fill="none" stroke="#000000" points="233,-1473.5 612,-1473.5 "/>
<text text-anchor="middle" x="422.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Feature_barcoding</text>
<polyline fill="none" stroke="#000000" points="233,-1450.5 612,-1450.5 "/>
<text text-anchor="middle" x="422.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Oligo_dT_Poly_dT</text>
<polyline fill="none" stroke="#000000" points="233,-1427.5 612,-1427.5 "/>
<text text-anchor="middle" x="422.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Random</text>
<polyline fill="none" stroke="#000000" points="233,-1404.5 612,-1404.5 "/>
<text text-anchor="middle" x="422.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">Sequencing_Library_Construction_Date</text>
<polyline fill="none" stroke="#000000" points="233,-1381.5 612,-1381.5 "/>
<text text-anchor="middle" x="422.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">Single_Cell_Dissociation_Date</text>
<polyline fill="none" stroke="#000000" points="233,-1358.5 612,-1358.5 "/>
<text text-anchor="middle" x="422.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">Single_Cell_Isolation_Method</text>
<polyline fill="none" stroke="#000000" points="233,-1335.5 612,-1335.5 "/>
<text text-anchor="middle" x="422.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">Spike_In</text>
<polyline fill="none" stroke="#000000" points="233,-1312.5 612,-1312.5 "/>
<text text-anchor="middle" x="422.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">Total_Number_of_Input_Cells</text>
<polyline fill="none" stroke="#000000" points="233,-1289.5 612,-1289.5 "/>
<text text-anchor="middle" x="422.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">UMI</text>
<polyline fill="none" stroke="#000000" points="233,-1266.5 612,-1266.5 "/>
<text text-anchor="middle" x="422.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="233,-1243.5 612,-1243.5 "/>
<text text-anchor="middle" x="422.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">cDNA_Length</text>
<polyline fill="none" stroke="#000000" points="233,-1220.5 612,-1220.5 "/>
<text text-anchor="middle" x="422.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">cDNA_Offset</text>
<polyline fill="none" stroke="#000000" points="233,-1197.5 612,-1197.5 "/>
<text text-anchor="middle" x="422.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="233,-1174.5 612,-1174.5 "/>
<text text-anchor="middle" x="422.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 23 properties</text>
<polyline fill="none" stroke="#000000" points="612,-1151.5 612,-1749.5 "/>
<text text-anchor="middle" x="622.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M633.0121,-1155.3087C635.834,-1153.8409 638.6635,-1152.4042 641.5,-1151 853.639,-1045.9829 1534.1728,-959.586 1861.4315,-922.9271"/>
<polygon fill="#000000" stroke="#000000" points="1861.9386,-926.3923 1871.4882,-921.8038 1861.1614,-919.4356 1861.9386,-926.3923"/>
<text text-anchor="middle" x="833" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- study_personnel -->
<g id="node8" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M3837,-351.5C3837,-351.5 4144,-351.5 4144,-351.5 4150,-351.5 4156,-357.5 4156,-363.5 4156,-363.5 4156,-454.5 4156,-454.5 4156,-460.5 4150,-466.5 4144,-466.5 4144,-466.5 3837,-466.5 3837,-466.5 3831,-466.5 3825,-460.5 3825,-454.5 3825,-454.5 3825,-363.5 3825,-363.5 3825,-357.5 3831,-351.5 3837,-351.5"/>
<text text-anchor="middle" x="3892" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="3959,-351.5 3959,-466.5 "/>
<text text-anchor="middle" x="3969.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3980,-351.5 3980,-466.5 "/>
<text text-anchor="middle" x="4057.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="3980,-443.5 4135,-443.5 "/>
<text text-anchor="middle" x="4057.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="3980,-420.5 4135,-420.5 "/>
<text text-anchor="middle" x="4057.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="3980,-397.5 4135,-397.5 "/>
<text text-anchor="middle" x="4057.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="3980,-374.5 4135,-374.5 "/>
<text text-anchor="middle" x="4057.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="4135,-351.5 4135,-466.5 "/>
<text text-anchor="middle" x="4145.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge21" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3990.5,-351.3027C3990.5,-332.11 3990.5,-309.7702 3990.5,-286.9242"/>
<polygon fill="#000000" stroke="#000000" points="3994.0001,-286.7571 3990.5,-276.7572 3987.0001,-286.7572 3994.0001,-286.7571"/>
<text text-anchor="middle" x="4060" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- therapeutic_procedure -->
<g id="node9" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M2766.5,-846.5C2766.5,-846.5 3158.5,-846.5 3158.5,-846.5 3164.5,-846.5 3170.5,-852.5 3170.5,-858.5 3170.5,-858.5 3170.5,-949.5 3170.5,-949.5 3170.5,-955.5 3164.5,-961.5 3158.5,-961.5 3158.5,-961.5 2766.5,-961.5 2766.5,-961.5 2760.5,-961.5 2754.5,-955.5 2754.5,-949.5 2754.5,-949.5 2754.5,-858.5 2754.5,-858.5 2754.5,-852.5 2760.5,-846.5 2766.5,-846.5"/>
<text text-anchor="middle" x="2845" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="2935.5,-846.5 2935.5,-961.5 "/>
<text text-anchor="middle" x="2946" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2956.5,-846.5 2956.5,-961.5 "/>
<text text-anchor="middle" x="3053" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment_start</text>
<polyline fill="none" stroke="#000000" points="2956.5,-938.5 3149.5,-938.5 "/>
<text text-anchor="middle" x="3053" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="2956.5,-915.5 3149.5,-915.5 "/>
<text text-anchor="middle" x="3053" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="2956.5,-892.5 3149.5,-892.5 "/>
<text text-anchor="middle" x="3053" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="2956.5,-869.5 3149.5,-869.5 "/>
<text text-anchor="middle" x="3053" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="3149.5,-846.5 3149.5,-961.5 "/>
<text text-anchor="middle" x="3160" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3009.5916,-846.1615C3053.3604,-795.4593 3122.6102,-722.6118 3195.5,-675 3202.7396,-670.2711 3210.3201,-665.7543 3218.1113,-661.4522"/>
<polygon fill="#000000" stroke="#000000" points="3219.8346,-664.4996 3226.9903,-656.6863 3216.524,-658.3319 3219.8346,-664.4996"/>
<text text-anchor="middle" x="3288.5" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- clinical_measure_file -->
<g id="node10" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M4028.5,-777.5C4028.5,-777.5 4380.5,-777.5 4380.5,-777.5 4386.5,-777.5 4392.5,-783.5 4392.5,-789.5 4392.5,-789.5 4392.5,-1018.5 4392.5,-1018.5 4392.5,-1024.5 4386.5,-1030.5 4380.5,-1030.5 4380.5,-1030.5 4028.5,-1030.5 4028.5,-1030.5 4022.5,-1030.5 4016.5,-1024.5 4016.5,-1018.5 4016.5,-1018.5 4016.5,-789.5 4016.5,-789.5 4016.5,-783.5 4022.5,-777.5 4028.5,-777.5"/>
<text text-anchor="middle" x="4100" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="4183.5,-777.5 4183.5,-1030.5 "/>
<text text-anchor="middle" x="4194" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4204.5,-777.5 4204.5,-1030.5 "/>
<text text-anchor="middle" x="4288" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="4204.5,-1007.5 4371.5,-1007.5 "/>
<text text-anchor="middle" x="4288" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="4204.5,-984.5 4371.5,-984.5 "/>
<text text-anchor="middle" x="4288" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="4204.5,-961.5 4371.5,-961.5 "/>
<text text-anchor="middle" x="4288" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="4204.5,-938.5 4371.5,-938.5 "/>
<text text-anchor="middle" x="4288" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="4204.5,-915.5 4371.5,-915.5 "/>
<text text-anchor="middle" x="4288" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="4204.5,-892.5 4371.5,-892.5 "/>
<text text-anchor="middle" x="4288" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="4204.5,-869.5 4371.5,-869.5 "/>
<text text-anchor="middle" x="4288" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="4204.5,-846.5 4371.5,-846.5 "/>
<text text-anchor="middle" x="4288" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="4204.5,-823.5 4371.5,-823.5 "/>
<text text-anchor="middle" x="4288" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="4204.5,-800.5 4371.5,-800.5 "/>
<text text-anchor="middle" x="4288" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="4371.5,-777.5 4371.5,-1030.5 "/>
<text text-anchor="middle" x="4382" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M4100.469,-777.3739C4072.8527,-750.7566 4041.232,-725.4827 4007.5,-708 3997.4271,-702.7794 3740.1775,-658.7131 3559.7086,-628.2353"/>
<polygon fill="#000000" stroke="#000000" points="3560.2705,-624.7807 3549.8273,-626.5671 3559.1052,-631.683 3560.2705,-624.7807"/>
<text text-anchor="middle" x="4041" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge15" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M4219.0498,-777.3551C4227.6252,-656.7587 4226.7124,-472.696 4164.5,-328 4158.1447,-313.2187 4150.1326,-298.845 4141.0559,-285.0569"/>
<polygon fill="#000000" stroke="#000000" points="4143.7887,-282.8513 4135.272,-276.5491 4137.9997,-286.7868 4143.7887,-282.8513"/>
<text text-anchor="middle" x="4300.5" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- pdx -->
<g id="node11" class="node">
<title>pdx</title>
<path fill="none" stroke="#000000" d="M663,-1347C663,-1347 992,-1347 992,-1347 998,-1347 1004,-1353 1004,-1359 1004,-1359 1004,-1542 1004,-1542 1004,-1548 998,-1554 992,-1554 992,-1554 663,-1554 663,-1554 657,-1554 651,-1548 651,-1542 651,-1542 651,-1359 651,-1359 651,-1353 657,-1347 663,-1347"/>
<text text-anchor="middle" x="672.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
<polyline fill="none" stroke="#000000" points="694,-1347 694,-1554 "/>
<text text-anchor="middle" x="704.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="715,-1347 715,-1554 "/>
<text text-anchor="middle" x="849" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_site</text>
<polyline fill="none" stroke="#000000" points="715,-1531 983,-1531 "/>
<text text-anchor="middle" x="849" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_type</text>
<polyline fill="none" stroke="#000000" points="715,-1508 983,-1508 "/>
<text text-anchor="middle" x="849" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">model_id</text>
<polyline fill="none" stroke="#000000" points="715,-1485 983,-1485 "/>
<text text-anchor="middle" x="849" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">mouse_strain</text>
<polyline fill="none" stroke="#000000" points="715,-1462 983,-1462 "/>
<text text-anchor="middle" x="849" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">strain_immune_system_humanized</text>
<polyline fill="none" stroke="#000000" points="715,-1439 983,-1439 "/>
<text text-anchor="middle" x="849" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_characterization_method</text>
<polyline fill="none" stroke="#000000" points="715,-1416 983,-1416 "/>
<text text-anchor="middle" x="849" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_not_mus_or_ebv_origin</text>
<polyline fill="none" stroke="#000000" points="715,-1393 983,-1393 "/>
<text text-anchor="middle" x="849" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_preparation</text>
<polyline fill="none" stroke="#000000" points="715,-1370 983,-1370 "/>
<text text-anchor="middle" x="849" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_humanization</text>
<polyline fill="none" stroke="#000000" points="983,-1347 983,-1554 "/>
<text text-anchor="middle" x="993.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M866.9593,-1346.9008C897.1697,-1281.2228 945.1738,-1199.7424 1012.5,-1151 1146.8843,-1053.7094 1604.0785,-970.6575 1861.1742,-930.2479"/>
<polygon fill="#000000" stroke="#000000" points="1862.0319,-933.6563 1871.37,-928.6512 1860.9488,-926.7406 1862.0319,-933.6563"/>
<text text-anchor="middle" x="1094.5" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- family_relationship -->
<g id="node12" class="node">
<title>family_relationship</title>
<path fill="none" stroke="#000000" d="M3201,-869.5C3201,-869.5 3570,-869.5 3570,-869.5 3576,-869.5 3582,-875.5 3582,-881.5 3582,-881.5 3582,-926.5 3582,-926.5 3582,-932.5 3576,-938.5 3570,-938.5 3570,-938.5 3201,-938.5 3201,-938.5 3195,-938.5 3189,-932.5 3189,-926.5 3189,-926.5 3189,-881.5 3189,-881.5 3189,-875.5 3195,-869.5 3201,-869.5"/>
<text text-anchor="middle" x="3266" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
<polyline fill="none" stroke="#000000" points="3343,-869.5 3343,-938.5 "/>
<text text-anchor="middle" x="3353.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3364,-869.5 3364,-938.5 "/>
<text text-anchor="middle" x="3462.5" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_id</text>
<polyline fill="none" stroke="#000000" points="3364,-915.5 3561,-915.5 "/>
<text text-anchor="middle" x="3462.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">related_to_participant_id</text>
<polyline fill="none" stroke="#000000" points="3364,-892.5 3561,-892.5 "/>
<text text-anchor="middle" x="3462.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">relationship</text>
<polyline fill="none" stroke="#000000" points="3561,-869.5 3561,-938.5 "/>
<text text-anchor="middle" x="3571.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3385.5,-869.3096C3385.5,-820.2069 3385.5,-729.4399 3385.5,-666.7188"/>
<polygon fill="#000000" stroke="#000000" points="3389.0001,-666.5165 3385.5,-656.5165 3382.0001,-666.5166 3389.0001,-666.5165"/>
<text text-anchor="middle" x="3465" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- sample_diagnosis -->
<g id="node13" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M1034,-1289.5C1034,-1289.5 1467,-1289.5 1467,-1289.5 1473,-1289.5 1479,-1295.5 1479,-1301.5 1479,-1301.5 1479,-1599.5 1479,-1599.5 1479,-1605.5 1473,-1611.5 1467,-1611.5 1467,-1611.5 1034,-1611.5 1034,-1611.5 1028,-1611.5 1022,-1605.5 1022,-1599.5 1022,-1599.5 1022,-1301.5 1022,-1301.5 1022,-1295.5 1028,-1289.5 1034,-1289.5"/>
<text text-anchor="middle" x="1093.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1165,-1289.5 1165,-1611.5 "/>
<text text-anchor="middle" x="1175.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1186,-1289.5 1186,-1611.5 "/>
<text text-anchor="middle" x="1322" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1186,-1588.5 1458,-1588.5 "/>
<text text-anchor="middle" x="1322" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1186,-1565.5 1458,-1565.5 "/>
<text text-anchor="middle" x="1322" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1186,-1542.5 1458,-1542.5 "/>
<text text-anchor="middle" x="1322" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1186,-1519.5 1458,-1519.5 "/>
<text text-anchor="middle" x="1322" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="1186,-1496.5 1458,-1496.5 "/>
<text text-anchor="middle" x="1322" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="1186,-1473.5 1458,-1473.5 "/>
<text text-anchor="middle" x="1322" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="1186,-1450.5 1458,-1450.5 "/>
<text text-anchor="middle" x="1322" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1186,-1427.5 1458,-1427.5 "/>
<text text-anchor="middle" x="1322" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1186,-1404.5 1458,-1404.5 "/>
<text text-anchor="middle" x="1322" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="1186,-1381.5 1458,-1381.5 "/>
<text text-anchor="middle" x="1322" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1186,-1358.5 1458,-1358.5 "/>
<text text-anchor="middle" x="1322" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1186,-1335.5 1458,-1335.5 "/>
<text text-anchor="middle" x="1322" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1186,-1312.5 1458,-1312.5 "/>
<text text-anchor="middle" x="1322" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1458,-1289.5 1458,-1611.5 "/>
<text text-anchor="middle" x="1468.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1355.3896,-1289.2154C1392.7838,-1240.3289 1438.0267,-1189.4536 1487.5,-1151 1599.5405,-1063.9155 1747.1363,-1000.0041 1861.6625,-959.0352"/>
<polygon fill="#000000" stroke="#000000" points="1862.9887,-962.2784 1871.2414,-955.6344 1860.6467,-955.6818 1862.9887,-962.2784"/>
<text text-anchor="middle" x="1601.5" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
<!-- methylation_array_file -->
<g id="node14" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M1509,-1335.5C1509,-1335.5 1876,-1335.5 1876,-1335.5 1882,-1335.5 1888,-1341.5 1888,-1347.5 1888,-1347.5 1888,-1553.5 1888,-1553.5 1888,-1559.5 1882,-1565.5 1876,-1565.5 1876,-1565.5 1509,-1565.5 1509,-1565.5 1503,-1565.5 1497,-1559.5 1497,-1553.5 1497,-1553.5 1497,-1347.5 1497,-1347.5 1497,-1341.5 1503,-1335.5 1509,-1335.5"/>
<text text-anchor="middle" x="1586" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="1675,-1335.5 1675,-1565.5 "/>
<text text-anchor="middle" x="1685.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1696,-1335.5 1696,-1565.5 "/>
<text text-anchor="middle" x="1781.5" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1696,-1542.5 1867,-1542.5 "/>
<text text-anchor="middle" x="1781.5" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1696,-1519.5 1867,-1519.5 "/>
<text text-anchor="middle" x="1781.5" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1696,-1496.5 1867,-1496.5 "/>
<text text-anchor="middle" x="1781.5" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1696,-1473.5 1867,-1473.5 "/>
<text text-anchor="middle" x="1781.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1696,-1450.5 1867,-1450.5 "/>
<text text-anchor="middle" x="1781.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1696,-1427.5 1867,-1427.5 "/>
<text text-anchor="middle" x="1781.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1696,-1404.5 1867,-1404.5 "/>
<text text-anchor="middle" x="1781.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1696,-1381.5 1867,-1381.5 "/>
<text text-anchor="middle" x="1781.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="1696,-1358.5 1867,-1358.5 "/>
<text text-anchor="middle" x="1781.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="1867,-1335.5 1867,-1565.5 "/>
<text text-anchor="middle" x="1877.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1763.1472,-1335.4001C1802.8221,-1271.1722 1853.4694,-1189.859 1899.5,-1118 1925.8832,-1076.8128 1955.6091,-1031.5353 1980.9414,-993.276"/>
<polygon fill="#000000" stroke="#000000" points="1984.0043,-994.99 1986.6103,-984.7206 1978.169,-991.1235 1984.0043,-994.99"/>
<text text-anchor="middle" x="1991" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- synonym -->
<g id="node15" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M2806,-1427.5C2806,-1427.5 3107,-1427.5 3107,-1427.5 3113,-1427.5 3119,-1433.5 3119,-1439.5 3119,-1439.5 3119,-1461.5 3119,-1461.5 3119,-1467.5 3113,-1473.5 3107,-1473.5 3107,-1473.5 2806,-1473.5 2806,-1473.5 2800,-1473.5 2794,-1467.5 2794,-1461.5 2794,-1461.5 2794,-1439.5 2794,-1439.5 2794,-1433.5 2800,-1427.5 2806,-1427.5"/>
<text text-anchor="middle" x="2834" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="2874,-1427.5 2874,-1473.5 "/>
<text text-anchor="middle" x="2884.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2895,-1427.5 2895,-1473.5 "/>
<text text-anchor="middle" x="2996.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="2895,-1450.5 3098,-1450.5 "/>
<text text-anchor="middle" x="2996.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="3098,-1427.5 3098,-1473.5 "/>
<text text-anchor="middle" x="3108.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2951.1137,-1427.3933C2936.1999,-1369.2135 2888.4179,-1216.6538 2784.5,-1151 2740.7834,-1123.3805 2603.5859,-1141.0131 2552.5,-1133 2524.065,-1128.5398 2517.9594,-1122.3022 2489.5,-1118 2429.8231,-1108.9787 2272.8489,-1126.2472 2218.5,-1100 2169.611,-1076.3896 2127.9438,-1032.8433 2097.2414,-992.7831"/>
<polygon fill="#000000" stroke="#000000" points="2099.8631,-990.4461 2091.0532,-984.5608 2094.2701,-994.6554 2099.8631,-990.4461"/>
<text text-anchor="middle" x="2595" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2949.0658,-1427.2141C2930.2808,-1371.857 2875.7972,-1231.0494 2784.5,-1151 2739.6937,-1111.7138 2693.6685,-1149.5062 2660.5,-1100 2636.2566,-1063.8151 2632.0831,-741.0086 2660.5,-708 2696.0239,-666.736 3007.9627,-631.9368 3210.9321,-613.3955"/>
<polygon fill="#000000" stroke="#000000" points="3211.4742,-616.8607 3221.1166,-612.4704 3210.8409,-609.8894 3211.4742,-616.8607"/>
<text text-anchor="middle" x="2703" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge17" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3119.2917,-1434.4365C3460.707,-1397.1976 4233.9481,-1293.0779 4401.5,-1100 4458.8617,-1033.8994 4420.5,-991.5195 4420.5,-904 4420.5,-904 4420.5,-904 4420.5,-409 4420.5,-296.7417 4314.2002,-229.2433 4207.3054,-189.7467"/>
<polygon fill="#000000" stroke="#000000" points="4208.2223,-186.3565 4197.628,-186.2466 4205.8414,-192.9392 4208.2223,-186.3565"/>
<text text-anchor="middle" x="4463" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- publication -->
<g id="node16" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M4460.5,-391C4460.5,-391 4670.5,-391 4670.5,-391 4676.5,-391 4682.5,-397 4682.5,-403 4682.5,-403 4682.5,-415 4682.5,-415 4682.5,-421 4676.5,-427 4670.5,-427 4670.5,-427 4460.5,-427 4460.5,-427 4454.5,-427 4448.5,-421 4448.5,-415 4448.5,-415 4448.5,-403 4448.5,-403 4448.5,-397 4454.5,-391 4460.5,-391"/>
<text text-anchor="middle" x="4497" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="4545.5,-391 4545.5,-427 "/>
<text text-anchor="middle" x="4556" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4566.5,-391 4566.5,-427 "/>
<text text-anchor="middle" x="4614" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="4661.5,-391 4661.5,-427 "/>
<text text-anchor="middle" x="4672" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge11" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M4548.9472,-390.8058C4525.5819,-366.0757 4480.6097,-321.8619 4434.5,-295 4364.4046,-254.1649 4281.92,-221.469 4207.1901,-196.7394"/>
<polygon fill="#000000" stroke="#000000" points="4208.2384,-193.3999 4197.6456,-193.6101 4206.0575,-200.0515 4208.2384,-193.3999"/>
<text text-anchor="middle" x="4504.5" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- sequencing_file -->
<g id="node17" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M1918,-1163C1918,-1163 2387,-1163 2387,-1163 2393,-1163 2399,-1169 2399,-1175 2399,-1175 2399,-1726 2399,-1726 2399,-1732 2393,-1738 2387,-1738 2387,-1738 1918,-1738 1918,-1738 1912,-1738 1906,-1732 1906,-1726 1906,-1726 1906,-1175 1906,-1175 1906,-1169 1912,-1163 1918,-1163"/>
<text text-anchor="middle" x="1970" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="2034,-1163 2034,-1738 "/>
<text text-anchor="middle" x="2044.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2055,-1163 2055,-1738 "/>
<text text-anchor="middle" x="2216.5" y="-1722.8" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="2055,-1715 2378,-1715 "/>
<text text-anchor="middle" x="2216.5" y="-1699.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2055,-1692 2378,-1692 "/>
<text text-anchor="middle" x="2216.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2055,-1669 2378,-1669 "/>
<text text-anchor="middle" x="2216.5" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="2055,-1646 2378,-1646 "/>
<text text-anchor="middle" x="2216.5" y="-1630.8" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="2055,-1623 2378,-1623 "/>
<text text-anchor="middle" x="2216.5" y="-1607.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2055,-1600 2378,-1600 "/>
<text text-anchor="middle" x="2216.5" y="-1584.8" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="2055,-1577 2378,-1577 "/>
<text text-anchor="middle" x="2216.5" y="-1561.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2055,-1554 2378,-1554 "/>
<text text-anchor="middle" x="2216.5" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2055,-1531 2378,-1531 "/>
<text text-anchor="middle" x="2216.5" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2055,-1508 2378,-1508 "/>
<text text-anchor="middle" x="2216.5" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2055,-1485 2378,-1485 "/>
<text text-anchor="middle" x="2216.5" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2055,-1462 2378,-1462 "/>
<text text-anchor="middle" x="2216.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2055,-1439 2378,-1439 "/>
<text text-anchor="middle" x="2216.5" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="2055,-1416 2378,-1416 "/>
<text text-anchor="middle" x="2216.5" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="2055,-1393 2378,-1393 "/>
<text text-anchor="middle" x="2216.5" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="2055,-1370 2378,-1370 "/>
<text text-anchor="middle" x="2216.5" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="2055,-1347 2378,-1347 "/>
<text text-anchor="middle" x="2216.5" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="2055,-1324 2378,-1324 "/>
<text text-anchor="middle" x="2216.5" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="2055,-1301 2378,-1301 "/>
<text text-anchor="middle" x="2216.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2055,-1278 2378,-1278 "/>
<text text-anchor="middle" x="2216.5" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="2055,-1255 2378,-1255 "/>
<text text-anchor="middle" x="2216.5" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="2055,-1232 2378,-1232 "/>
<text text-anchor="middle" x="2216.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="2055,-1209 2378,-1209 "/>
<text text-anchor="middle" x="2216.5" y="-1193.8" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="2055,-1186 2378,-1186 "/>
<text text-anchor="middle" x="2216.5" y="-1170.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="2378,-1163 2378,-1738 "/>
<text text-anchor="middle" x="2388.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2093.5481,-1162.8463C2081.0021,-1101.6284 2068.6542,-1041.3773 2059.0326,-994.4292"/>
<polygon fill="#000000" stroke="#000000" points="2062.4582,-993.711 2057.0218,-984.6173 2055.6008,-995.1164 2062.4582,-993.711"/>
<text text-anchor="middle" x="2153" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- diagnosis -->
<g id="node18" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M3612.5,-708.5C3612.5,-708.5 3986.5,-708.5 3986.5,-708.5 3992.5,-708.5 3998.5,-714.5 3998.5,-720.5 3998.5,-720.5 3998.5,-1087.5 3998.5,-1087.5 3998.5,-1093.5 3992.5,-1099.5 3986.5,-1099.5 3986.5,-1099.5 3612.5,-1099.5 3612.5,-1099.5 3606.5,-1099.5 3600.5,-1093.5 3600.5,-1087.5 3600.5,-1087.5 3600.5,-720.5 3600.5,-720.5 3600.5,-714.5 3606.5,-708.5 3612.5,-708.5"/>
<text text-anchor="middle" x="3642.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="3684.5,-708.5 3684.5,-1099.5 "/>
<text text-anchor="middle" x="3695" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3705.5,-708.5 3705.5,-1099.5 "/>
<text text-anchor="middle" x="3841.5" y="-1084.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="3705.5,-1076.5 3977.5,-1076.5 "/>
<text text-anchor="middle" x="3841.5" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="3705.5,-1053.5 3977.5,-1053.5 "/>
<text text-anchor="middle" x="3841.5" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="3705.5,-1030.5 3977.5,-1030.5 "/>
<text text-anchor="middle" x="3841.5" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="3705.5,-1007.5 3977.5,-1007.5 "/>
<text text-anchor="middle" x="3841.5" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="3705.5,-984.5 3977.5,-984.5 "/>
<text text-anchor="middle" x="3841.5" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="3705.5,-961.5 3977.5,-961.5 "/>
<text text-anchor="middle" x="3841.5" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="3705.5,-938.5 3977.5,-938.5 "/>
<text text-anchor="middle" x="3841.5" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="3705.5,-915.5 3977.5,-915.5 "/>
<text text-anchor="middle" x="3841.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="3705.5,-892.5 3977.5,-892.5 "/>
<text text-anchor="middle" x="3841.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="3705.5,-869.5 3977.5,-869.5 "/>
<text text-anchor="middle" x="3841.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="3705.5,-846.5 3977.5,-846.5 "/>
<text text-anchor="middle" x="3841.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="3705.5,-823.5 3977.5,-823.5 "/>
<text text-anchor="middle" x="3841.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="3705.5,-800.5 3977.5,-800.5 "/>
<text text-anchor="middle" x="3841.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="3705.5,-777.5 3977.5,-777.5 "/>
<text text-anchor="middle" x="3841.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="3705.5,-754.5 3977.5,-754.5 "/>
<text text-anchor="middle" x="3841.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="3705.5,-731.5 3977.5,-731.5 "/>
<text text-anchor="middle" x="3841.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="3977.5,-708.5 3977.5,-1099.5 "/>
<text text-anchor="middle" x="3988" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3600.2507,-710.5658C3583.31,-697.7732 3565.963,-685.7339 3548.5,-675 3540.8815,-670.3172 3532.9275,-665.731 3524.8084,-661.2782"/>
<polygon fill="#000000" stroke="#000000" points="3526.4052,-658.1629 3515.9415,-656.5008 3523.0848,-664.3254 3526.4052,-658.1629"/>
<text text-anchor="middle" x="3617" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- imaging_file -->
<g id="node19" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M2429.5,-1289.5C2429.5,-1289.5 2763.5,-1289.5 2763.5,-1289.5 2769.5,-1289.5 2775.5,-1295.5 2775.5,-1301.5 2775.5,-1301.5 2775.5,-1599.5 2775.5,-1599.5 2775.5,-1605.5 2769.5,-1611.5 2763.5,-1611.5 2763.5,-1611.5 2429.5,-1611.5 2429.5,-1611.5 2423.5,-1611.5 2417.5,-1605.5 2417.5,-1599.5 2417.5,-1599.5 2417.5,-1301.5 2417.5,-1301.5 2417.5,-1295.5 2423.5,-1289.5 2429.5,-1289.5"/>
<text text-anchor="middle" x="2469.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="2521.5,-1289.5 2521.5,-1611.5 "/>
<text text-anchor="middle" x="2532" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2542.5,-1289.5 2542.5,-1611.5 "/>
<text text-anchor="middle" x="2648.5" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2542.5,-1588.5 2754.5,-1588.5 "/>
<text text-anchor="middle" x="2648.5" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2542.5,-1565.5 2754.5,-1565.5 "/>
<text text-anchor="middle" x="2648.5" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2542.5,-1542.5 2754.5,-1542.5 "/>
<text text-anchor="middle" x="2648.5" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2542.5,-1519.5 2754.5,-1519.5 "/>
<text text-anchor="middle" x="2648.5" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2542.5,-1496.5 2754.5,-1496.5 "/>
<text text-anchor="middle" x="2648.5" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2542.5,-1473.5 2754.5,-1473.5 "/>
<text text-anchor="middle" x="2648.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2542.5,-1450.5 2754.5,-1450.5 "/>
<text text-anchor="middle" x="2648.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2542.5,-1427.5 2754.5,-1427.5 "/>
<text text-anchor="middle" x="2648.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2542.5,-1404.5 2754.5,-1404.5 "/>
<text text-anchor="middle" x="2648.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="2542.5,-1381.5 2754.5,-1381.5 "/>
<text text-anchor="middle" x="2648.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="2542.5,-1358.5 2754.5,-1358.5 "/>
<text text-anchor="middle" x="2648.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="2542.5,-1335.5 2754.5,-1335.5 "/>
<text text-anchor="middle" x="2648.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2542.5,-1312.5 2754.5,-1312.5 "/>
<text text-anchor="middle" x="2648.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="2754.5,-1289.5 2754.5,-1611.5 "/>
<text text-anchor="middle" x="2765" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2524.335,-1289.1718C2494.6454,-1238.5184 2455.7364,-1186.5935 2407.5,-1151 2337.4918,-1099.3412 2292.7404,-1145.3668 2218.5,-1100 2173.8262,-1072.7007 2133.6695,-1030.895 2102.8535,-992.895"/>
<polygon fill="#000000" stroke="#000000" points="2105.3999,-990.4751 2096.4212,-984.8506 2099.9327,-994.8466 2105.3999,-990.4751"/>
<text text-anchor="middle" x="2431" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- study_admin -->
<g id="node20" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M4712.5,-328.5C4712.5,-328.5 5038.5,-328.5 5038.5,-328.5 5044.5,-328.5 5050.5,-334.5 5050.5,-340.5 5050.5,-340.5 5050.5,-477.5 5050.5,-477.5 5050.5,-483.5 5044.5,-489.5 5038.5,-489.5 5038.5,-489.5 4712.5,-489.5 4712.5,-489.5 4706.5,-489.5 4700.5,-483.5 4700.5,-477.5 4700.5,-477.5 4700.5,-340.5 4700.5,-340.5 4700.5,-334.5 4706.5,-328.5 4712.5,-328.5"/>
<text text-anchor="middle" x="4754.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="4808.5,-328.5 4808.5,-489.5 "/>
<text text-anchor="middle" x="4819" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4829.5,-328.5 4829.5,-489.5 "/>
<text text-anchor="middle" x="4929.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="4829.5,-466.5 5029.5,-466.5 "/>
<text text-anchor="middle" x="4929.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="4829.5,-443.5 5029.5,-443.5 "/>
<text text-anchor="middle" x="4929.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="4829.5,-420.5 5029.5,-420.5 "/>
<text text-anchor="middle" x="4929.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="4829.5,-397.5 5029.5,-397.5 "/>
<text text-anchor="middle" x="4929.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="4829.5,-374.5 5029.5,-374.5 "/>
<text text-anchor="middle" x="4929.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="4829.5,-351.5 5029.5,-351.5 "/>
<text text-anchor="middle" x="4929.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="5029.5,-328.5 5029.5,-489.5 "/>
<text text-anchor="middle" x="5040" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge5" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M4700.4387,-331.2136C4697.4433,-330.1179 4694.4621,-329.0456 4691.5,-328 4532.1613,-271.7519 4347.5116,-222.4569 4207.7334,-188.253"/>
<polygon fill="#000000" stroke="#000000" points="4208.2925,-184.7868 4197.7479,-185.8165 4206.6332,-191.5873 4208.2925,-184.7868"/>
<text text-anchor="middle" x="4692" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
</g>
</svg>
</div>
