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
<svg width="5214pt" height="1988pt"
 viewBox="0.00 0.00 5214.00 1988.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1984)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1984 5210,-1984 5210,4 -4,4"/>
<!-- molecular_test -->
<g id="node1" class="node">
<title>molecular_test</title>
<path fill="none" stroke="#000000" d="M2730.5,-731.5C2730.5,-731.5 3118.5,-731.5 3118.5,-731.5 3124.5,-731.5 3130.5,-737.5 3130.5,-743.5 3130.5,-743.5 3130.5,-1317.5 3130.5,-1317.5 3130.5,-1323.5 3124.5,-1329.5 3118.5,-1329.5 3118.5,-1329.5 2730.5,-1329.5 2730.5,-1329.5 2724.5,-1329.5 2718.5,-1323.5 2718.5,-1317.5 2718.5,-1317.5 2718.5,-743.5 2718.5,-743.5 2718.5,-737.5 2724.5,-731.5 2730.5,-731.5"/>
<text text-anchor="middle" x="2780" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
<polyline fill="none" stroke="#000000" points="2841.5,-731.5 2841.5,-1329.5 "/>
<text text-anchor="middle" x="2852" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2862.5,-731.5 2862.5,-1329.5 "/>
<text text-anchor="middle" x="2986" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">aa_change</text>
<polyline fill="none" stroke="#000000" points="2862.5,-1306.5 3109.5,-1306.5 "/>
<text text-anchor="middle" x="2986" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">antigen</text>
<polyline fill="none" stroke="#000000" points="2862.5,-1283.5 3109.5,-1283.5 "/>
<text text-anchor="middle" x="2986" y="-1268.3" font-family="Times,serif" font-size="14.00" fill="#000000">biospecimen_type</text>
<polyline fill="none" stroke="#000000" points="2862.5,-1260.5 3109.5,-1260.5 "/>
<text text-anchor="middle" x="2986" y="-1245.3" font-family="Times,serif" font-size="14.00" fill="#000000">blood_test_normal_range_lower</text>
<polyline fill="none" stroke="#000000" points="2862.5,-1237.5 3109.5,-1237.5 "/>
<text text-anchor="middle" x="2986" y="-1222.3" font-family="Times,serif" font-size="14.00" fill="#000000">blood_test_normal_range_upper</text>
<polyline fill="none" stroke="#000000" points="2862.5,-1214.5 3109.5,-1214.5 "/>
<text text-anchor="middle" x="2986" y="-1199.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_count</text>
<polyline fill="none" stroke="#000000" points="2862.5,-1191.5 3109.5,-1191.5 "/>
<text text-anchor="middle" x="2986" y="-1176.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome</text>
<polyline fill="none" stroke="#000000" points="2862.5,-1168.5 3109.5,-1168.5 "/>
<text text-anchor="middle" x="2986" y="-1153.3" font-family="Times,serif" font-size="14.00" fill="#000000">copy_number</text>
<polyline fill="none" stroke="#000000" points="2862.5,-1145.5 3109.5,-1145.5 "/>
<text text-anchor="middle" x="2986" y="-1130.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytoband</text>
<polyline fill="none" stroke="#000000" points="2862.5,-1122.5 3109.5,-1122.5 "/>
<text text-anchor="middle" x="2986" y="-1107.3" font-family="Times,serif" font-size="14.00" fill="#000000">exon</text>
<polyline fill="none" stroke="#000000" points="2862.5,-1099.5 3109.5,-1099.5 "/>
<text text-anchor="middle" x="2986" y="-1084.3" font-family="Times,serif" font-size="14.00" fill="#000000">gene_symbol</text>
<polyline fill="none" stroke="#000000" points="2862.5,-1076.5 3109.5,-1076.5 "/>
<text text-anchor="middle" x="2986" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">histone_family</text>
<polyline fill="none" stroke="#000000" points="2862.5,-1053.5 3109.5,-1053.5 "/>
<text text-anchor="middle" x="2986" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">histone_variant</text>
<polyline fill="none" stroke="#000000" points="2862.5,-1030.5 3109.5,-1030.5 "/>
<text text-anchor="middle" x="2986" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">intron</text>
<polyline fill="none" stroke="#000000" points="2862.5,-1007.5 3109.5,-1007.5 "/>
<text text-anchor="middle" x="2986" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
<polyline fill="none" stroke="#000000" points="2862.5,-984.5 3109.5,-984.5 "/>
<text text-anchor="middle" x="2986" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">loci_abnormal_count</text>
<polyline fill="none" stroke="#000000" points="2862.5,-961.5 3109.5,-961.5 "/>
<text text-anchor="middle" x="2986" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">loci_count</text>
<polyline fill="none" stroke="#000000" points="2862.5,-938.5 3109.5,-938.5 "/>
<text text-anchor="middle" x="2986" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">locus</text>
<polyline fill="none" stroke="#000000" points="2862.5,-915.5 3109.5,-915.5 "/>
<text text-anchor="middle" x="2986" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">mismatch_repair_mutation</text>
<polyline fill="none" stroke="#000000" points="2862.5,-892.5 3109.5,-892.5 "/>
<text text-anchor="middle" x="2986" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_analysis_method</text>
<polyline fill="none" stroke="#000000" points="2862.5,-869.5 3109.5,-869.5 "/>
<text text-anchor="middle" x="2986" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_consequence</text>
<polyline fill="none" stroke="#000000" points="2862.5,-846.5 3109.5,-846.5 "/>
<text text-anchor="middle" x="2986" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test_id</text>
<polyline fill="none" stroke="#000000" points="2862.5,-823.5 3109.5,-823.5 "/>
<text text-anchor="middle" x="2986" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathogenicity</text>
<polyline fill="none" stroke="#000000" points="2862.5,-800.5 3109.5,-800.5 "/>
<text text-anchor="middle" x="2986" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">ploidy</text>
<polyline fill="none" stroke="#000000" points="2862.5,-777.5 3109.5,-777.5 "/>
<text text-anchor="middle" x="2986" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">second_exon</text>
<polyline fill="none" stroke="#000000" points="2862.5,-754.5 3109.5,-754.5 "/>
<text text-anchor="middle" x="2986" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 11 properties</text>
<polyline fill="none" stroke="#000000" points="3109.5,-731.5 3109.5,-1329.5 "/>
<text text-anchor="middle" x="3120" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node6" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M2144.5,-564.5C2144.5,-564.5 2448.5,-564.5 2448.5,-564.5 2454.5,-564.5 2460.5,-570.5 2460.5,-576.5 2460.5,-576.5 2460.5,-667.5 2460.5,-667.5 2460.5,-673.5 2454.5,-679.5 2448.5,-679.5 2448.5,-679.5 2144.5,-679.5 2144.5,-679.5 2138.5,-679.5 2132.5,-673.5 2132.5,-667.5 2132.5,-667.5 2132.5,-576.5 2132.5,-576.5 2132.5,-570.5 2138.5,-564.5 2144.5,-564.5"/>
<text text-anchor="middle" x="2180.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="2228.5,-564.5 2228.5,-679.5 "/>
<text text-anchor="middle" x="2239" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2249.5,-564.5 2249.5,-679.5 "/>
<text text-anchor="middle" x="2344.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="2249.5,-656.5 2439.5,-656.5 "/>
<text text-anchor="middle" x="2344.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="2249.5,-633.5 2439.5,-633.5 "/>
<text text-anchor="middle" x="2344.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="2249.5,-610.5 2439.5,-610.5 "/>
<text text-anchor="middle" x="2344.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="2249.5,-587.5 2439.5,-587.5 "/>
<text text-anchor="middle" x="2344.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="2439.5,-564.5 2439.5,-679.5 "/>
<text text-anchor="middle" x="2450" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2718.2995,-740.9349C2713.7622,-737.4995 2709.1619,-734.1836 2704.5,-731 2635.6904,-684.0101 2547.5668,-657.2595 2470.8384,-642.0392"/>
<polygon fill="#000000" stroke="#000000" points="2471.0573,-638.5169 2460.5752,-640.058 2469.7305,-645.39 2471.0573,-638.5169"/>
<text text-anchor="middle" x="2729.5" y="-701.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- study -->
<g id="node2" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M2395.5,-.5C2395.5,-.5 2785.5,-.5 2785.5,-.5 2791.5,-.5 2797.5,-6.5 2797.5,-12.5 2797.5,-12.5 2797.5,-287.5 2797.5,-287.5 2797.5,-293.5 2791.5,-299.5 2785.5,-299.5 2785.5,-299.5 2395.5,-299.5 2395.5,-299.5 2389.5,-299.5 2383.5,-293.5 2383.5,-287.5 2383.5,-287.5 2383.5,-12.5 2383.5,-12.5 2383.5,-6.5 2389.5,-.5 2395.5,-.5"/>
<text text-anchor="middle" x="2411.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="2439.5,-.5 2439.5,-299.5 "/>
<text text-anchor="middle" x="2450" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2460.5,-.5 2460.5,-299.5 "/>
<text text-anchor="middle" x="2618.5" y="-284.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="2460.5,-276.5 2776.5,-276.5 "/>
<text text-anchor="middle" x="2618.5" y="-261.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="2460.5,-253.5 2776.5,-253.5 "/>
<text text-anchor="middle" x="2618.5" y="-238.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_shorthand</text>
<polyline fill="none" stroke="#000000" points="2460.5,-230.5 2776.5,-230.5 "/>
<text text-anchor="middle" x="2618.5" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="2460.5,-207.5 2776.5,-207.5 "/>
<text text-anchor="middle" x="2618.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="2460.5,-184.5 2776.5,-184.5 "/>
<text text-anchor="middle" x="2618.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="2460.5,-161.5 2776.5,-161.5 "/>
<text text-anchor="middle" x="2618.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="2460.5,-138.5 2776.5,-138.5 "/>
<text text-anchor="middle" x="2618.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="2460.5,-115.5 2776.5,-115.5 "/>
<text text-anchor="middle" x="2618.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="2460.5,-92.5 2776.5,-92.5 "/>
<text text-anchor="middle" x="2618.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="2460.5,-69.5 2776.5,-69.5 "/>
<text text-anchor="middle" x="2618.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="2460.5,-46.5 2776.5,-46.5 "/>
<text text-anchor="middle" x="2618.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="2460.5,-23.5 2776.5,-23.5 "/>
<text text-anchor="middle" x="2618.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="2776.5,-.5 2776.5,-299.5 "/>
<text text-anchor="middle" x="2787" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file -->
<g id="node3" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M12,-892.5C12,-892.5 385,-892.5 385,-892.5 391,-892.5 397,-898.5 397,-904.5 397,-904.5 397,-1156.5 397,-1156.5 397,-1162.5 391,-1168.5 385,-1168.5 385,-1168.5 12,-1168.5 12,-1168.5 6,-1168.5 0,-1162.5 0,-1156.5 0,-1156.5 0,-904.5 0,-904.5 0,-898.5 6,-892.5 12,-892.5"/>
<text text-anchor="middle" x="83.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="167,-892.5 167,-1168.5 "/>
<text text-anchor="middle" x="177.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="188,-892.5 188,-1168.5 "/>
<text text-anchor="middle" x="282" y="-1153.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="188,-1145.5 376,-1145.5 "/>
<text text-anchor="middle" x="282" y="-1130.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="188,-1122.5 376,-1122.5 "/>
<text text-anchor="middle" x="282" y="-1107.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file_id</text>
<polyline fill="none" stroke="#000000" points="188,-1099.5 376,-1099.5 "/>
<text text-anchor="middle" x="282" y="-1084.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="188,-1076.5 376,-1076.5 "/>
<text text-anchor="middle" x="282" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="188,-1053.5 376,-1053.5 "/>
<text text-anchor="middle" x="282" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="188,-1030.5 376,-1030.5 "/>
<text text-anchor="middle" x="282" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="188,-1007.5 376,-1007.5 "/>
<text text-anchor="middle" x="282" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="188,-984.5 376,-984.5 "/>
<text text-anchor="middle" x="282" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="188,-961.5 376,-961.5 "/>
<text text-anchor="middle" x="282" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="188,-938.5 376,-938.5 "/>
<text text-anchor="middle" x="282" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="188,-915.5 376,-915.5 "/>
<text text-anchor="middle" x="282" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="376,-892.5 376,-1168.5 "/>
<text text-anchor="middle" x="386.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge28" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M264.815,-892.1255C305.4374,-822.5759 364.1737,-743.5901 439.5,-698 1072.5533,-314.854 1966.1002,-198.1731 2373.2058,-163.7822"/>
<polygon fill="#000000" stroke="#000000" points="2373.6523,-167.2572 2383.3258,-162.9358 2373.0689,-160.2815 2373.6523,-167.2572"/>
<text text-anchor="middle" x="833.5" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M262.5206,-892.2867C296.7358,-833.483 344.5158,-769.6758 405.5,-731 481.2105,-682.9849 515.3378,-707.3615 604.5,-698 894.6593,-667.5351 1751.6571,-638.6342 2122.3626,-627.1781"/>
<polygon fill="#000000" stroke="#000000" points="2122.4908,-630.6759 2132.3781,-626.8692 2122.2749,-623.6792 2122.4908,-630.6759"/>
<text text-anchor="middle" x="734" y="-701.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- study_admin -->
<g id="node4" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M1514.5,-351.5C1514.5,-351.5 1840.5,-351.5 1840.5,-351.5 1846.5,-351.5 1852.5,-357.5 1852.5,-363.5 1852.5,-363.5 1852.5,-500.5 1852.5,-500.5 1852.5,-506.5 1846.5,-512.5 1840.5,-512.5 1840.5,-512.5 1514.5,-512.5 1514.5,-512.5 1508.5,-512.5 1502.5,-506.5 1502.5,-500.5 1502.5,-500.5 1502.5,-363.5 1502.5,-363.5 1502.5,-357.5 1508.5,-351.5 1514.5,-351.5"/>
<text text-anchor="middle" x="1556.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="1610.5,-351.5 1610.5,-512.5 "/>
<text text-anchor="middle" x="1621" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1631.5,-351.5 1631.5,-512.5 "/>
<text text-anchor="middle" x="1731.5" y="-497.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="1631.5,-489.5 1831.5,-489.5 "/>
<text text-anchor="middle" x="1731.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="1631.5,-466.5 1831.5,-466.5 "/>
<text text-anchor="middle" x="1731.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="1631.5,-443.5 1831.5,-443.5 "/>
<text text-anchor="middle" x="1731.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="1631.5,-420.5 1831.5,-420.5 "/>
<text text-anchor="middle" x="1731.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="1631.5,-397.5 1831.5,-397.5 "/>
<text text-anchor="middle" x="1731.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="1631.5,-374.5 1831.5,-374.5 "/>
<text text-anchor="middle" x="1731.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="1831.5,-351.5 1831.5,-512.5 "/>
<text text-anchor="middle" x="1842" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge18" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1852.5218,-354.6098C1855.8674,-353.3774 1859.1958,-352.1727 1862.5,-351 2031.3053,-291.0896 2227.2605,-237.8816 2373.3189,-201.2832"/>
<polygon fill="#000000" stroke="#000000" points="2374.454,-204.6072 2383.3068,-198.7869 2372.7566,-197.8161 2374.454,-204.6072"/>
<text text-anchor="middle" x="2016" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- study_funding -->
<g id="node5" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M1883,-386C1883,-386 2262,-386 2262,-386 2268,-386 2274,-392 2274,-398 2274,-398 2274,-466 2274,-466 2274,-472 2268,-478 2262,-478 2262,-478 1883,-478 1883,-478 1877,-478 1871,-472 1871,-466 1871,-466 1871,-398 1871,-398 1871,-392 1877,-386 1883,-386"/>
<text text-anchor="middle" x="1930.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="1990,-386 1990,-478 "/>
<text text-anchor="middle" x="2000.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2011,-386 2011,-478 "/>
<text text-anchor="middle" x="2132" y="-462.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="2011,-455 2253,-455 "/>
<text text-anchor="middle" x="2132" y="-439.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="2011,-432 2253,-432 "/>
<text text-anchor="middle" x="2132" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="2011,-409 2253,-409 "/>
<text text-anchor="middle" x="2132" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding_id</text>
<polyline fill="none" stroke="#000000" points="2253,-386 2253,-478 "/>
<text text-anchor="middle" x="2263.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge2" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2104.6918,-385.9761C2122.5493,-363.1111 2146.4001,-336.4931 2172.5,-318 2232.9159,-275.1924 2305.813,-241.0705 2373.6973,-215.0645"/>
<polygon fill="#000000" stroke="#000000" points="2375.1296,-218.2647 2383.2409,-211.4487 2372.6495,-211.7187 2375.1296,-218.2647"/>
<text text-anchor="middle" x="2234.5" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge25" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2288.5647,-564.3556C2283.4751,-506.6164 2283.5764,-417.0734 2320.5,-351 2334.9708,-325.105 2354.3188,-301.5764 2376.0407,-280.4938"/>
<polygon fill="#000000" stroke="#000000" points="2378.6384,-282.8543 2383.4947,-273.438 2373.8263,-277.7707 2378.6384,-282.8543"/>
<text text-anchor="middle" x="2371" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_arm -->
<g id="node12" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M2442,-386C2442,-386 2739,-386 2739,-386 2745,-386 2751,-392 2751,-398 2751,-398 2751,-466 2751,-466 2751,-472 2745,-478 2739,-478 2739,-478 2442,-478 2442,-478 2436,-478 2430,-472 2430,-466 2430,-466 2430,-398 2430,-398 2430,-392 2436,-386 2442,-386"/>
<text text-anchor="middle" x="2476" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="2522,-386 2522,-478 "/>
<text text-anchor="middle" x="2532.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2543,-386 2543,-478 "/>
<text text-anchor="middle" x="2636.5" y="-462.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="2543,-455 2730,-455 "/>
<text text-anchor="middle" x="2636.5" y="-439.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="2543,-432 2730,-432 "/>
<text text-anchor="middle" x="2636.5" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="2543,-409 2730,-409 "/>
<text text-anchor="middle" x="2636.5" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm_id</text>
<polyline fill="none" stroke="#000000" points="2730,-386 2730,-478 "/>
<text text-anchor="middle" x="2740.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge24" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M2385.5075,-564.4781C2425.2599,-538.7878 2471.7508,-508.7427 2510.3992,-483.7658"/>
<polygon fill="#000000" stroke="#000000" points="2512.5283,-486.5572 2519.0273,-478.1898 2508.7288,-480.6781 2512.5283,-486.5572"/>
<text text-anchor="middle" x="2485" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- synonym -->
<g id="node7" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M4893,-1657.5C4893,-1657.5 5194,-1657.5 5194,-1657.5 5200,-1657.5 5206,-1663.5 5206,-1669.5 5206,-1669.5 5206,-1691.5 5206,-1691.5 5206,-1697.5 5200,-1703.5 5194,-1703.5 5194,-1703.5 4893,-1703.5 4893,-1703.5 4887,-1703.5 4881,-1697.5 4881,-1691.5 4881,-1691.5 4881,-1669.5 4881,-1669.5 4881,-1663.5 4887,-1657.5 4893,-1657.5"/>
<text text-anchor="middle" x="4921" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="4961,-1657.5 4961,-1703.5 "/>
<text text-anchor="middle" x="4971.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4982,-1657.5 4982,-1703.5 "/>
<text text-anchor="middle" x="5083.5" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="4982,-1680.5 5185,-1680.5 "/>
<text text-anchor="middle" x="5083.5" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="5185,-1657.5 5185,-1703.5 "/>
<text text-anchor="middle" x="5195.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge23" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M5043.2558,-1657.4722C5042.3873,-1573.5194 5039.5,-1275.9474 5039.5,-1030.5 5039.5,-1030.5 5039.5,-1030.5 5039.5,-432 5039.5,-208.3711 3407.0813,-161.9275 2807.7701,-152.4121"/>
<polygon fill="#000000" stroke="#000000" points="2807.7702,-148.9117 2797.7165,-152.2544 2807.6604,-155.9109 2807.7702,-148.9117"/>
<text text-anchor="middle" x="5082" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M5038.7695,-1657.4877C5025.5156,-1598.416 4982.7263,-1439.6502 4889.5,-1348 4406.3473,-873.0154 4151.3466,-901.0357 3495.5,-731 3306.5399,-682.0099 2755.0228,-646.4819 2470.608,-630.8516"/>
<polygon fill="#000000" stroke="#000000" points="2470.7805,-627.3559 2460.6042,-630.304 2470.3979,-634.3455 2470.7805,-627.3559"/>
<text text-anchor="middle" x="4900" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- sample -->
<g id="node23" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M3160.5,-950C3160.5,-950 3474.5,-950 3474.5,-950 3480.5,-950 3486.5,-956 3486.5,-962 3486.5,-962 3486.5,-1099 3486.5,-1099 3486.5,-1105 3480.5,-1111 3474.5,-1111 3474.5,-1111 3160.5,-1111 3160.5,-1111 3154.5,-1111 3148.5,-1105 3148.5,-1099 3148.5,-1099 3148.5,-962 3148.5,-962 3148.5,-956 3154.5,-950 3160.5,-950"/>
<text text-anchor="middle" x="3182.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="3216.5,-950 3216.5,-1111 "/>
<text text-anchor="middle" x="3227" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3237.5,-950 3237.5,-1111 "/>
<text text-anchor="middle" x="3351.5" y="-1095.8" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="3237.5,-1088 3465.5,-1088 "/>
<text text-anchor="middle" x="3351.5" y="-1072.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="3237.5,-1065 3465.5,-1065 "/>
<text text-anchor="middle" x="3351.5" y="-1049.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="3237.5,-1042 3465.5,-1042 "/>
<text text-anchor="middle" x="3351.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="3237.5,-1019 3465.5,-1019 "/>
<text text-anchor="middle" x="3351.5" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="3237.5,-996 3465.5,-996 "/>
<text text-anchor="middle" x="3351.5" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="3237.5,-973 3465.5,-973 "/>
<text text-anchor="middle" x="3351.5" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="3465.5,-950 3465.5,-1111 "/>
<text text-anchor="middle" x="3476" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M5037.3552,-1657.439C5020.9807,-1600.6936 4970.7006,-1453.6355 4872.5,-1381 4844.5146,-1360.3002 3899.5046,-1155.5294 3496.5931,-1068.8933"/>
<polygon fill="#000000" stroke="#000000" points="3497.1027,-1065.423 3486.5904,-1066.7428 3495.6314,-1072.2666 3497.1027,-1065.423"/>
<text text-anchor="middle" x="4843" y="-1351.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- follow_up -->
<g id="node8" class="node">
<title>follow_up</title>
<path fill="none" stroke="#000000" d="M427,-927C427,-927 790,-927 790,-927 796,-927 802,-933 802,-939 802,-939 802,-1122 802,-1122 802,-1128 796,-1134 790,-1134 790,-1134 427,-1134 427,-1134 421,-1134 415,-1128 415,-1122 415,-1122 415,-939 415,-939 415,-933 421,-927 427,-927"/>
<text text-anchor="middle" x="457.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
<polyline fill="none" stroke="#000000" points="500,-927 500,-1134 "/>
<text text-anchor="middle" x="510.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="521,-927 521,-1134 "/>
<text text-anchor="middle" x="651" y="-1118.8" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event</text>
<polyline fill="none" stroke="#000000" points="521,-1111 781,-1111 "/>
<text text-anchor="middle" x="651" y="-1095.8" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity</text>
<polyline fill="none" stroke="#000000" points="521,-1088 781,-1088 "/>
<text text-anchor="middle" x="651" y="-1072.8" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity_method_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="521,-1065 781,-1065 "/>
<text text-anchor="middle" x="651" y="-1049.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_follow_up</text>
<polyline fill="none" stroke="#000000" points="521,-1042 781,-1042 "/>
<text text-anchor="middle" x="651" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_response</text>
<polyline fill="none" stroke="#000000" points="521,-1019 781,-1019 "/>
<text text-anchor="middle" x="651" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_category</text>
<polyline fill="none" stroke="#000000" points="521,-996 781,-996 "/>
<text text-anchor="middle" x="651" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_id</text>
<polyline fill="none" stroke="#000000" points="521,-973 781,-973 "/>
<text text-anchor="middle" x="651" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_other</text>
<polyline fill="none" stroke="#000000" points="521,-950 781,-950 "/>
<text text-anchor="middle" x="651" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">risk_factor</text>
<polyline fill="none" stroke="#000000" points="781,-927 781,-1134 "/>
<text text-anchor="middle" x="791.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M649.7622,-926.9362C682.6175,-859.0439 735.5982,-774.9894 810.5,-731 921.2005,-665.9862 1753.7881,-636.258 2122.116,-626.1853"/>
<polygon fill="#000000" stroke="#000000" points="2122.4389,-629.6779 2132.3402,-625.9075 2122.2487,-622.6805 2122.4389,-629.6779"/>
<text text-anchor="middle" x="979.5" y="-701.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- study_personnel -->
<g id="node9" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M2781,-374.5C2781,-374.5 3088,-374.5 3088,-374.5 3094,-374.5 3100,-380.5 3100,-386.5 3100,-386.5 3100,-477.5 3100,-477.5 3100,-483.5 3094,-489.5 3088,-489.5 3088,-489.5 2781,-489.5 2781,-489.5 2775,-489.5 2769,-483.5 2769,-477.5 2769,-477.5 2769,-386.5 2769,-386.5 2769,-380.5 2775,-374.5 2781,-374.5"/>
<text text-anchor="middle" x="2836" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="2903,-374.5 2903,-489.5 "/>
<text text-anchor="middle" x="2913.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2924,-374.5 2924,-489.5 "/>
<text text-anchor="middle" x="3001.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="2924,-466.5 3079,-466.5 "/>
<text text-anchor="middle" x="3001.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="2924,-443.5 3079,-443.5 "/>
<text text-anchor="middle" x="3001.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="2924,-420.5 3079,-420.5 "/>
<text text-anchor="middle" x="3001.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="2924,-397.5 3079,-397.5 "/>
<text text-anchor="middle" x="3001.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="3079,-374.5 3079,-489.5 "/>
<text text-anchor="middle" x="3089.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge16" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2864.0564,-374.2526C2839.5163,-354.1355 2810.6793,-330.4958 2781.0998,-306.2475"/>
<polygon fill="#000000" stroke="#000000" points="2783.1072,-303.3674 2773.1547,-299.7344 2778.6694,-308.7809 2783.1072,-303.3674"/>
<text text-anchor="middle" x="2882" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node10" class="node">
<title>single_cell_sequencing_file</title>
<path fill="none" stroke="#000000" d="M2065,-1381.5C2065,-1381.5 2674,-1381.5 2674,-1381.5 2680,-1381.5 2686,-1387.5 2686,-1393.5 2686,-1393.5 2686,-1967.5 2686,-1967.5 2686,-1973.5 2680,-1979.5 2674,-1979.5 2674,-1979.5 2065,-1979.5 2065,-1979.5 2059,-1979.5 2053,-1973.5 2053,-1967.5 2053,-1967.5 2053,-1393.5 2053,-1393.5 2053,-1387.5 2059,-1381.5 2065,-1381.5"/>
<text text-anchor="middle" x="2159" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
<polyline fill="none" stroke="#000000" points="2265,-1381.5 2265,-1979.5 "/>
<text text-anchor="middle" x="2275.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2286,-1381.5 2286,-1979.5 "/>
<text text-anchor="middle" x="2475.5" y="-1964.3" font-family="Times,serif" font-size="14.00" fill="#000000">Cell_Barcode</text>
<polyline fill="none" stroke="#000000" points="2286,-1956.5 2665,-1956.5 "/>
<text text-anchor="middle" x="2475.5" y="-1941.3" font-family="Times,serif" font-size="14.00" fill="#000000">Cryopreserved_Cells_in_Sample</text>
<polyline fill="none" stroke="#000000" points="2286,-1933.5 2665,-1933.5 "/>
<text text-anchor="middle" x="2475.5" y="-1918.3" font-family="Times,serif" font-size="14.00" fill="#000000">Dissociation_Method</text>
<polyline fill="none" stroke="#000000" points="2286,-1910.5 2665,-1910.5 "/>
<text text-anchor="middle" x="2475.5" y="-1895.3" font-family="Times,serif" font-size="14.00" fill="#000000">End_Bias</text>
<polyline fill="none" stroke="#000000" points="2286,-1887.5 2665,-1887.5 "/>
<text text-anchor="middle" x="2475.5" y="-1872.3" font-family="Times,serif" font-size="14.00" fill="#000000">Input_Cells_and_Nuclei</text>
<polyline fill="none" stroke="#000000" points="2286,-1864.5 2665,-1864.5 "/>
<text text-anchor="middle" x="2475.5" y="-1849.3" font-family="Times,serif" font-size="14.00" fill="#000000">Library_Construction_Method</text>
<polyline fill="none" stroke="#000000" points="2286,-1841.5 2665,-1841.5 "/>
<text text-anchor="middle" x="2475.5" y="-1826.3" font-family="Times,serif" font-size="14.00" fill="#000000">Library_Preparation_Date</text>
<polyline fill="none" stroke="#000000" points="2286,-1818.5 2665,-1818.5 "/>
<text text-anchor="middle" x="2475.5" y="-1803.3" font-family="Times,serif" font-size="14.00" fill="#000000">Nucleic_Acid_Capture_Date</text>
<polyline fill="none" stroke="#000000" points="2286,-1795.5 2665,-1795.5 "/>
<text text-anchor="middle" x="2475.5" y="-1780.3" font-family="Times,serif" font-size="14.00" fill="#000000">Paired_End</text>
<polyline fill="none" stroke="#000000" points="2286,-1772.5 2665,-1772.5 "/>
<text text-anchor="middle" x="2475.5" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">Protocols_Link</text>
<polyline fill="none" stroke="#000000" points="2286,-1749.5 2665,-1749.5 "/>
<text text-anchor="middle" x="2475.5" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">Read1</text>
<polyline fill="none" stroke="#000000" points="2286,-1726.5 2665,-1726.5 "/>
<text text-anchor="middle" x="2475.5" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">Read2</text>
<polyline fill="none" stroke="#000000" points="2286,-1703.5 2665,-1703.5 "/>
<text text-anchor="middle" x="2475.5" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Feature_barcoding</text>
<polyline fill="none" stroke="#000000" points="2286,-1680.5 2665,-1680.5 "/>
<text text-anchor="middle" x="2475.5" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Oligo_dT_Poly_dT</text>
<polyline fill="none" stroke="#000000" points="2286,-1657.5 2665,-1657.5 "/>
<text text-anchor="middle" x="2475.5" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Random</text>
<polyline fill="none" stroke="#000000" points="2286,-1634.5 2665,-1634.5 "/>
<text text-anchor="middle" x="2475.5" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">Sequencing_Library_Construction_Date</text>
<polyline fill="none" stroke="#000000" points="2286,-1611.5 2665,-1611.5 "/>
<text text-anchor="middle" x="2475.5" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">Single_Cell_Dissociation_Date</text>
<polyline fill="none" stroke="#000000" points="2286,-1588.5 2665,-1588.5 "/>
<text text-anchor="middle" x="2475.5" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">Single_Cell_Isolation_Method</text>
<polyline fill="none" stroke="#000000" points="2286,-1565.5 2665,-1565.5 "/>
<text text-anchor="middle" x="2475.5" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">Spike_In</text>
<polyline fill="none" stroke="#000000" points="2286,-1542.5 2665,-1542.5 "/>
<text text-anchor="middle" x="2475.5" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">Total_Number_of_Input_Cells</text>
<polyline fill="none" stroke="#000000" points="2286,-1519.5 2665,-1519.5 "/>
<text text-anchor="middle" x="2475.5" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">UMI</text>
<polyline fill="none" stroke="#000000" points="2286,-1496.5 2665,-1496.5 "/>
<text text-anchor="middle" x="2475.5" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="2286,-1473.5 2665,-1473.5 "/>
<text text-anchor="middle" x="2475.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">cDNA_Length</text>
<polyline fill="none" stroke="#000000" points="2286,-1450.5 2665,-1450.5 "/>
<text text-anchor="middle" x="2475.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">cDNA_Offset</text>
<polyline fill="none" stroke="#000000" points="2286,-1427.5 2665,-1427.5 "/>
<text text-anchor="middle" x="2475.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2286,-1404.5 2665,-1404.5 "/>
<text text-anchor="middle" x="2475.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 24 properties</text>
<polyline fill="none" stroke="#000000" points="2665,-1381.5 2665,-1979.5 "/>
<text text-anchor="middle" x="2675.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2686.1901,-1385.6421C2689.2842,-1384.0565 2692.3878,-1382.5085 2695.5,-1381 2778.5434,-1340.749 2808.8511,-1358.8083 2900.5,-1348 2953.395,-1341.762 3094.2293,-1358.0598 3139.5,-1330 3215.363,-1282.9785 3262.9096,-1190.6573 3289.5782,-1120.8808"/>
<polygon fill="#000000" stroke="#000000" points="3292.9772,-1121.7841 3293.2035,-1111.1917 3286.4211,-1119.331 3292.9772,-1121.7841"/>
<text text-anchor="middle" x="3009" y="-1351.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- methylation_array_file -->
<g id="node11" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M2716,-1554C2716,-1554 3111,-1554 3111,-1554 3117,-1554 3123,-1560 3123,-1566 3123,-1566 3123,-1795 3123,-1795 3123,-1801 3117,-1807 3111,-1807 3111,-1807 2716,-1807 2716,-1807 2710,-1807 2704,-1801 2704,-1795 2704,-1795 2704,-1566 2704,-1566 2704,-1560 2710,-1554 2716,-1554"/>
<text text-anchor="middle" x="2793" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="2882,-1554 2882,-1807 "/>
<text text-anchor="middle" x="2892.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2903,-1554 2903,-1807 "/>
<text text-anchor="middle" x="3002.5" y="-1791.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2903,-1784 3102,-1784 "/>
<text text-anchor="middle" x="3002.5" y="-1768.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2903,-1761 3102,-1761 "/>
<text text-anchor="middle" x="3002.5" y="-1745.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2903,-1738 3102,-1738 "/>
<text text-anchor="middle" x="3002.5" y="-1722.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2903,-1715 3102,-1715 "/>
<text text-anchor="middle" x="3002.5" y="-1699.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2903,-1692 3102,-1692 "/>
<text text-anchor="middle" x="3002.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2903,-1669 3102,-1669 "/>
<text text-anchor="middle" x="3002.5" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2903,-1646 3102,-1646 "/>
<text text-anchor="middle" x="3002.5" y="-1630.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2903,-1623 3102,-1623 "/>
<text text-anchor="middle" x="3002.5" y="-1607.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file_id</text>
<polyline fill="none" stroke="#000000" points="2903,-1600 3102,-1600 "/>
<text text-anchor="middle" x="3002.5" y="-1584.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="2903,-1577 3102,-1577 "/>
<text text-anchor="middle" x="3002.5" y="-1561.8" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="3102,-1554 3102,-1807 "/>
<text text-anchor="middle" x="3112.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2996.7456,-1553.8469C3039.9248,-1487.5401 3093.1842,-1404.7906 3139.5,-1330 3182.9048,-1259.9102 3230.5472,-1179.5571 3265.6114,-1119.7369"/>
<polygon fill="#000000" stroke="#000000" points="3268.6575,-1121.4614 3270.6916,-1111.0636 3262.6173,-1117.9235 3268.6575,-1121.4614"/>
<text text-anchor="middle" x="3219" y="-1351.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge19" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2590.5,-385.7492C2590.5,-364.3874 2590.5,-337.6254 2590.5,-309.87"/>
<polygon fill="#000000" stroke="#000000" points="2594.0001,-309.6075 2590.5,-299.6075 2587.0001,-309.6076 2594.0001,-309.6075"/>
<text text-anchor="middle" x="2639" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- pdx -->
<g id="node13" class="node">
<title>pdx</title>
<path fill="none" stroke="#000000" d="M3153,-1565.5C3153,-1565.5 3482,-1565.5 3482,-1565.5 3488,-1565.5 3494,-1571.5 3494,-1577.5 3494,-1577.5 3494,-1783.5 3494,-1783.5 3494,-1789.5 3488,-1795.5 3482,-1795.5 3482,-1795.5 3153,-1795.5 3153,-1795.5 3147,-1795.5 3141,-1789.5 3141,-1783.5 3141,-1783.5 3141,-1577.5 3141,-1577.5 3141,-1571.5 3147,-1565.5 3153,-1565.5"/>
<text text-anchor="middle" x="3162.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
<polyline fill="none" stroke="#000000" points="3184,-1565.5 3184,-1795.5 "/>
<text text-anchor="middle" x="3194.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3205,-1565.5 3205,-1795.5 "/>
<text text-anchor="middle" x="3339" y="-1780.3" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_site</text>
<polyline fill="none" stroke="#000000" points="3205,-1772.5 3473,-1772.5 "/>
<text text-anchor="middle" x="3339" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_type</text>
<polyline fill="none" stroke="#000000" points="3205,-1749.5 3473,-1749.5 "/>
<text text-anchor="middle" x="3339" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_id</text>
<polyline fill="none" stroke="#000000" points="3205,-1726.5 3473,-1726.5 "/>
<text text-anchor="middle" x="3339" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">mouse_strain</text>
<polyline fill="none" stroke="#000000" points="3205,-1703.5 3473,-1703.5 "/>
<text text-anchor="middle" x="3339" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx_id</text>
<polyline fill="none" stroke="#000000" points="3205,-1680.5 3473,-1680.5 "/>
<text text-anchor="middle" x="3339" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">strain_immune_system_humanized</text>
<polyline fill="none" stroke="#000000" points="3205,-1657.5 3473,-1657.5 "/>
<text text-anchor="middle" x="3339" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_characterization_method</text>
<polyline fill="none" stroke="#000000" points="3205,-1634.5 3473,-1634.5 "/>
<text text-anchor="middle" x="3339" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_not_mus_or_ebv_origin</text>
<polyline fill="none" stroke="#000000" points="3205,-1611.5 3473,-1611.5 "/>
<text text-anchor="middle" x="3339" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_preparation</text>
<polyline fill="none" stroke="#000000" points="3205,-1588.5 3473,-1588.5 "/>
<text text-anchor="middle" x="3339" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_humanization</text>
<polyline fill="none" stroke="#000000" points="3473,-1565.5 3473,-1795.5 "/>
<text text-anchor="middle" x="3483.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3317.5,-1565.4159C3317.5,-1438.7007 3317.5,-1237.5724 3317.5,-1121.4196"/>
<polygon fill="#000000" stroke="#000000" points="3321.0001,-1121.1392 3317.5,-1111.1393 3314.0001,-1121.1393 3321.0001,-1121.1392"/>
<text text-anchor="middle" x="3341.5" y="-1351.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- family_relationship -->
<g id="node14" class="node">
<title>family_relationship</title>
<path fill="none" stroke="#000000" d="M832,-984.5C832,-984.5 1201,-984.5 1201,-984.5 1207,-984.5 1213,-990.5 1213,-996.5 1213,-996.5 1213,-1064.5 1213,-1064.5 1213,-1070.5 1207,-1076.5 1201,-1076.5 1201,-1076.5 832,-1076.5 832,-1076.5 826,-1076.5 820,-1070.5 820,-1064.5 820,-1064.5 820,-996.5 820,-996.5 820,-990.5 826,-984.5 832,-984.5"/>
<text text-anchor="middle" x="897" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
<polyline fill="none" stroke="#000000" points="974,-984.5 974,-1076.5 "/>
<text text-anchor="middle" x="984.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="995,-984.5 995,-1076.5 "/>
<text text-anchor="middle" x="1093.5" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_id</text>
<polyline fill="none" stroke="#000000" points="995,-1053.5 1192,-1053.5 "/>
<text text-anchor="middle" x="1093.5" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship_id</text>
<polyline fill="none" stroke="#000000" points="995,-1030.5 1192,-1030.5 "/>
<text text-anchor="middle" x="1093.5" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">related_to_participant_id</text>
<polyline fill="none" stroke="#000000" points="995,-1007.5 1192,-1007.5 "/>
<text text-anchor="middle" x="1093.5" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">relationship</text>
<polyline fill="none" stroke="#000000" points="1192,-984.5 1192,-1076.5 "/>
<text text-anchor="middle" x="1202.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1033.3808,-984.286C1061.0495,-915.8769 1123.0281,-789.4673 1221.5,-731 1297.045,-686.1454 1837.7199,-648.567 2122.3028,-631.6365"/>
<polygon fill="#000000" stroke="#000000" points="2122.5417,-635.1286 2132.3171,-631.0429 2122.1275,-628.1408 2122.5417,-635.1286"/>
<text text-anchor="middle" x="1431" y="-701.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- imaging_file -->
<g id="node15" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M3524,-1485C3524,-1485 3865,-1485 3865,-1485 3871,-1485 3877,-1491 3877,-1497 3877,-1497 3877,-1864 3877,-1864 3877,-1870 3871,-1876 3865,-1876 3865,-1876 3524,-1876 3524,-1876 3518,-1876 3512,-1870 3512,-1864 3512,-1864 3512,-1497 3512,-1497 3512,-1491 3518,-1485 3524,-1485"/>
<text text-anchor="middle" x="3564" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="3616,-1485 3616,-1876 "/>
<text text-anchor="middle" x="3626.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3637,-1485 3637,-1876 "/>
<text text-anchor="middle" x="3746.5" y="-1860.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="3637,-1853 3856,-1853 "/>
<text text-anchor="middle" x="3746.5" y="-1837.8" font-family="Times,serif" font-size="14.00" fill="#000000">deidentification_method</text>
<polyline fill="none" stroke="#000000" points="3637,-1830 3856,-1830 "/>
<text text-anchor="middle" x="3746.5" y="-1814.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="3637,-1807 3856,-1807 "/>
<text text-anchor="middle" x="3746.5" y="-1791.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="3637,-1784 3856,-1784 "/>
<text text-anchor="middle" x="3746.5" y="-1768.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="3637,-1761 3856,-1761 "/>
<text text-anchor="middle" x="3746.5" y="-1745.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="3637,-1738 3856,-1738 "/>
<text text-anchor="middle" x="3746.5" y="-1722.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="3637,-1715 3856,-1715 "/>
<text text-anchor="middle" x="3746.5" y="-1699.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="3637,-1692 3856,-1692 "/>
<text text-anchor="middle" x="3746.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">fixation_embedding_method</text>
<polyline fill="none" stroke="#000000" points="3637,-1669 3856,-1669 "/>
<text text-anchor="middle" x="3746.5" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="3637,-1646 3856,-1646 "/>
<text text-anchor="middle" x="3746.5" y="-1630.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file_id</text>
<polyline fill="none" stroke="#000000" points="3637,-1623 3856,-1623 "/>
<text text-anchor="middle" x="3746.5" y="-1607.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="3637,-1600 3856,-1600 "/>
<text text-anchor="middle" x="3746.5" y="-1584.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="3637,-1577 3856,-1577 "/>
<text text-anchor="middle" x="3746.5" y="-1561.8" font-family="Times,serif" font-size="14.00" fill="#000000">magnification</text>
<polyline fill="none" stroke="#000000" points="3637,-1554 3856,-1554 "/>
<text text-anchor="middle" x="3746.5" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="3637,-1531 3856,-1531 "/>
<text text-anchor="middle" x="3746.5" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="3637,-1508 3856,-1508 "/>
<text text-anchor="middle" x="3746.5" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">staining_method</text>
<polyline fill="none" stroke="#000000" points="3856,-1485 3856,-1876 "/>
<text text-anchor="middle" x="3866.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3580.8763,-1484.5971C3510.6208,-1363.467 3423.7953,-1213.7678 3369.5163,-1120.1833"/>
<polygon fill="#000000" stroke="#000000" points="3372.4116,-1118.199 3364.3667,-1111.3047 3366.3564,-1121.7111 3372.4116,-1118.199"/>
<text text-anchor="middle" x="3560" y="-1351.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- sequencing_file -->
<g id="node16" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M3907,-1381.5C3907,-1381.5 4376,-1381.5 4376,-1381.5 4382,-1381.5 4388,-1387.5 4388,-1393.5 4388,-1393.5 4388,-1967.5 4388,-1967.5 4388,-1973.5 4382,-1979.5 4376,-1979.5 4376,-1979.5 3907,-1979.5 3907,-1979.5 3901,-1979.5 3895,-1973.5 3895,-1967.5 3895,-1967.5 3895,-1393.5 3895,-1393.5 3895,-1387.5 3901,-1381.5 3907,-1381.5"/>
<text text-anchor="middle" x="3959" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="4023,-1381.5 4023,-1979.5 "/>
<text text-anchor="middle" x="4033.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4044,-1381.5 4044,-1979.5 "/>
<text text-anchor="middle" x="4205.5" y="-1964.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="4044,-1956.5 4367,-1956.5 "/>
<text text-anchor="middle" x="4205.5" y="-1941.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="4044,-1933.5 4367,-1933.5 "/>
<text text-anchor="middle" x="4205.5" y="-1918.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="4044,-1910.5 4367,-1910.5 "/>
<text text-anchor="middle" x="4205.5" y="-1895.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="4044,-1887.5 4367,-1887.5 "/>
<text text-anchor="middle" x="4205.5" y="-1872.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="4044,-1864.5 4367,-1864.5 "/>
<text text-anchor="middle" x="4205.5" y="-1849.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="4044,-1841.5 4367,-1841.5 "/>
<text text-anchor="middle" x="4205.5" y="-1826.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="4044,-1818.5 4367,-1818.5 "/>
<text text-anchor="middle" x="4205.5" y="-1803.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="4044,-1795.5 4367,-1795.5 "/>
<text text-anchor="middle" x="4205.5" y="-1780.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="4044,-1772.5 4367,-1772.5 "/>
<text text-anchor="middle" x="4205.5" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="4044,-1749.5 4367,-1749.5 "/>
<text text-anchor="middle" x="4205.5" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="4044,-1726.5 4367,-1726.5 "/>
<text text-anchor="middle" x="4205.5" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="4044,-1703.5 4367,-1703.5 "/>
<text text-anchor="middle" x="4205.5" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="4044,-1680.5 4367,-1680.5 "/>
<text text-anchor="middle" x="4205.5" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="4044,-1657.5 4367,-1657.5 "/>
<text text-anchor="middle" x="4205.5" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="4044,-1634.5 4367,-1634.5 "/>
<text text-anchor="middle" x="4205.5" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="4044,-1611.5 4367,-1611.5 "/>
<text text-anchor="middle" x="4205.5" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="4044,-1588.5 4367,-1588.5 "/>
<text text-anchor="middle" x="4205.5" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="4044,-1565.5 4367,-1565.5 "/>
<text text-anchor="middle" x="4205.5" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="4044,-1542.5 4367,-1542.5 "/>
<text text-anchor="middle" x="4205.5" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="4044,-1519.5 4367,-1519.5 "/>
<text text-anchor="middle" x="4205.5" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="4044,-1496.5 4367,-1496.5 "/>
<text text-anchor="middle" x="4205.5" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="4044,-1473.5 4367,-1473.5 "/>
<text text-anchor="middle" x="4205.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="4044,-1450.5 4367,-1450.5 "/>
<text text-anchor="middle" x="4205.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="4044,-1427.5 4367,-1427.5 "/>
<text text-anchor="middle" x="4205.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="4044,-1404.5 4367,-1404.5 "/>
<text text-anchor="middle" x="4205.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 1 properties</text>
<polyline fill="none" stroke="#000000" points="4367,-1381.5 4367,-1979.5 "/>
<text text-anchor="middle" x="4377.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3894.6511,-1388.0895C3891.9391,-1385.6976 3889.2217,-1383.3337 3886.5,-1381 3763.0854,-1275.1815 3604.3094,-1180.1976 3485.8537,-1115.8889"/>
<polygon fill="#000000" stroke="#000000" points="3487.4983,-1112.7993 3477.0376,-1111.1188 3484.1672,-1118.9559 3487.4983,-1112.7993"/>
<text text-anchor="middle" x="3925" y="-1351.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- exposure -->
<g id="node17" class="node">
<title>exposure</title>
<path fill="none" stroke="#000000" d="M1243,-789C1243,-789 1654,-789 1654,-789 1660,-789 1666,-795 1666,-801 1666,-801 1666,-1260 1666,-1260 1666,-1266 1660,-1272 1654,-1272 1654,-1272 1243,-1272 1243,-1272 1237,-1272 1231,-1266 1231,-1260 1231,-1260 1231,-801 1231,-801 1231,-795 1237,-789 1243,-789"/>
<text text-anchor="middle" x="1272" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
<polyline fill="none" stroke="#000000" points="1313,-789 1313,-1272 "/>
<text text-anchor="middle" x="1323.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1334,-789 1334,-1272 "/>
<text text-anchor="middle" x="1489.5" y="-1256.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_days_per_week</text>
<polyline fill="none" stroke="#000000" points="1334,-1249 1645,-1249 "/>
<text text-anchor="middle" x="1489.5" y="-1233.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_drinks_per_day</text>
<polyline fill="none" stroke="#000000" points="1334,-1226 1645,-1226 "/>
<text text-anchor="middle" x="1489.5" y="-1210.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_history</text>
<polyline fill="none" stroke="#000000" points="1334,-1203 1645,-1203 "/>
<text text-anchor="middle" x="1489.5" y="-1187.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_intensity</text>
<polyline fill="none" stroke="#000000" points="1334,-1180 1645,-1180 "/>
<text text-anchor="middle" x="1489.5" y="-1164.8" font-family="Times,serif" font-size="14.00" fill="#000000">asbestos_exposure</text>
<polyline fill="none" stroke="#000000" points="1334,-1157 1645,-1157 "/>
<text text-anchor="middle" x="1489.5" y="-1141.8" font-family="Times,serif" font-size="14.00" fill="#000000">cigarettes_per_day</text>
<polyline fill="none" stroke="#000000" points="1334,-1134 1645,-1134 "/>
<text text-anchor="middle" x="1489.5" y="-1118.8" font-family="Times,serif" font-size="14.00" fill="#000000">coal_dust_exposure</text>
<polyline fill="none" stroke="#000000" points="1334,-1111 1645,-1111 "/>
<text text-anchor="middle" x="1489.5" y="-1095.8" font-family="Times,serif" font-size="14.00" fill="#000000">environmental_tobacco_smoke_exposure</text>
<polyline fill="none" stroke="#000000" points="1334,-1088 1645,-1088 "/>
<text text-anchor="middle" x="1489.5" y="-1072.8" font-family="Times,serif" font-size="14.00" fill="#000000">exposure_id</text>
<polyline fill="none" stroke="#000000" points="1334,-1065 1645,-1065 "/>
<text text-anchor="middle" x="1489.5" y="-1049.8" font-family="Times,serif" font-size="14.00" fill="#000000">pack_years_smoked</text>
<polyline fill="none" stroke="#000000" points="1334,-1042 1645,-1042 "/>
<text text-anchor="middle" x="1489.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">radon_exposure</text>
<polyline fill="none" stroke="#000000" points="1334,-1019 1645,-1019 "/>
<text text-anchor="middle" x="1489.5" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">respirable_crystalline_silica_exposure</text>
<polyline fill="none" stroke="#000000" points="1334,-996 1645,-996 "/>
<text text-anchor="middle" x="1489.5" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">smoking_frequency</text>
<polyline fill="none" stroke="#000000" points="1334,-973 1645,-973 "/>
<text text-anchor="middle" x="1489.5" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">start_days_from_index</text>
<polyline fill="none" stroke="#000000" points="1334,-950 1645,-950 "/>
<text text-anchor="middle" x="1489.5" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">time_between_waking_and_first_smoke</text>
<polyline fill="none" stroke="#000000" points="1334,-927 1645,-927 "/>
<text text-anchor="middle" x="1489.5" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_onset_year</text>
<polyline fill="none" stroke="#000000" points="1334,-904 1645,-904 "/>
<text text-anchor="middle" x="1489.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_quit_year</text>
<polyline fill="none" stroke="#000000" points="1334,-881 1645,-881 "/>
<text text-anchor="middle" x="1489.5" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_status</text>
<polyline fill="none" stroke="#000000" points="1334,-858 1645,-858 "/>
<text text-anchor="middle" x="1489.5" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_smoke_exposure</text>
<polyline fill="none" stroke="#000000" points="1334,-835 1645,-835 "/>
<text text-anchor="middle" x="1489.5" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_tobacco_used</text>
<polyline fill="none" stroke="#000000" points="1334,-812 1645,-812 "/>
<text text-anchor="middle" x="1489.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">years_smoked</text>
<polyline fill="none" stroke="#000000" points="1645,-789 1645,-1272 "/>
<text text-anchor="middle" x="1655.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1603.7238,-788.8104C1625.6261,-766.7509 1649.604,-746.8056 1675.5,-731 1748.7543,-686.2891 1965.2612,-655.4558 2122.044,-638.2744"/>
<polygon fill="#000000" stroke="#000000" points="2122.7189,-641.7217 2132.2825,-637.1624 2121.963,-634.7627 2122.7189,-641.7217"/>
<text text-anchor="middle" x="1802" y="-701.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- publication -->
<g id="node18" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M3176,-409C3176,-409 3409,-409 3409,-409 3415,-409 3421,-415 3421,-421 3421,-421 3421,-443 3421,-443 3421,-449 3415,-455 3409,-455 3409,-455 3176,-455 3176,-455 3170,-455 3164,-449 3164,-443 3164,-443 3164,-421 3164,-421 3164,-415 3170,-409 3176,-409"/>
<text text-anchor="middle" x="3212.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="3261,-409 3261,-455 "/>
<text text-anchor="middle" x="3271.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3282,-409 3282,-455 "/>
<text text-anchor="middle" x="3341" y="-439.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication_id</text>
<polyline fill="none" stroke="#000000" points="3282,-432 3400,-432 "/>
<text text-anchor="middle" x="3341" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="3400,-409 3400,-455 "/>
<text text-anchor="middle" x="3410.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge4" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3269.2159,-408.7045C3242.455,-383.1282 3196.1882,-342.4544 3149.5,-318 3042.6453,-262.0315 2914.3029,-221.789 2807.5577,-194.7485"/>
<polygon fill="#000000" stroke="#000000" points="2808.1762,-191.2952 2797.6249,-192.2546 2806.4715,-198.0845 2808.1762,-191.2952"/>
<text text-anchor="middle" x="3221.5" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- therapeutic_procedure -->
<g id="node19" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M1622,-1611.5C1622,-1611.5 2023,-1611.5 2023,-1611.5 2029,-1611.5 2035,-1617.5 2035,-1623.5 2035,-1623.5 2035,-1737.5 2035,-1737.5 2035,-1743.5 2029,-1749.5 2023,-1749.5 2023,-1749.5 1622,-1749.5 1622,-1749.5 1616,-1749.5 1610,-1743.5 1610,-1737.5 1610,-1737.5 1610,-1623.5 1610,-1623.5 1610,-1617.5 1616,-1611.5 1622,-1611.5"/>
<text text-anchor="middle" x="1700.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="1791,-1611.5 1791,-1749.5 "/>
<text text-anchor="middle" x="1801.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1812,-1611.5 1812,-1749.5 "/>
<text text-anchor="middle" x="1913" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment_end</text>
<polyline fill="none" stroke="#000000" points="1812,-1726.5 2014,-1726.5 "/>
<text text-anchor="middle" x="1913" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment_start</text>
<polyline fill="none" stroke="#000000" points="1812,-1703.5 2014,-1703.5 "/>
<text text-anchor="middle" x="1913" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="1812,-1680.5 2014,-1680.5 "/>
<text text-anchor="middle" x="1913" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure_id</text>
<polyline fill="none" stroke="#000000" points="1812,-1657.5 2014,-1657.5 "/>
<text text-anchor="middle" x="1913" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="1812,-1634.5 2014,-1634.5 "/>
<text text-anchor="middle" x="1913" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="2014,-1611.5 2014,-1749.5 "/>
<text text-anchor="middle" x="2024.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1853.1,-1611.2051C1888.3229,-1540.4298 1953.2846,-1433.6845 2044.5,-1381 2130.3098,-1331.4376 2421.5581,-1403.969 2487.5,-1330 2531.789,-1280.3197 2519.8134,-789.1849 2487.5,-731 2477.7922,-713.5198 2464.0629,-698.6298 2448.3637,-686.0019"/>
<polygon fill="#000000" stroke="#000000" points="2450.0569,-682.8911 2439.9853,-679.6028 2445.808,-688.4541 2450.0569,-682.8911"/>
<text text-anchor="middle" x="2608.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>therapeutic_procedure&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1851.5263,-1611.4396C1885.9029,-1539.4944 1950.6034,-1430.5018 2044.5,-1381 2091.8099,-1356.0584 2473.8796,-1376.9871 2525.5,-1363 2539.1263,-1359.3078 2539.8614,-1351.6465 2553.5,-1348 2616.4313,-1331.1741 3083.3821,-1363.0793 3139.5,-1330 3216.6384,-1284.5299 3264.0857,-1191.4962 3290.386,-1121.113"/>
<polygon fill="#000000" stroke="#000000" points="3293.8126,-1121.9332 3293.9577,-1111.3393 3287.2379,-1119.5305 3293.8126,-1121.9332"/>
<text text-anchor="middle" x="2646.5" y="-1351.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- sample_diagnosis -->
<g id="node20" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M4418,-1542.5C4418,-1542.5 4851,-1542.5 4851,-1542.5 4857,-1542.5 4863,-1548.5 4863,-1554.5 4863,-1554.5 4863,-1806.5 4863,-1806.5 4863,-1812.5 4857,-1818.5 4851,-1818.5 4851,-1818.5 4418,-1818.5 4418,-1818.5 4412,-1818.5 4406,-1812.5 4406,-1806.5 4406,-1806.5 4406,-1554.5 4406,-1554.5 4406,-1548.5 4412,-1542.5 4418,-1542.5"/>
<text text-anchor="middle" x="4477.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="4549,-1542.5 4549,-1818.5 "/>
<text text-anchor="middle" x="4559.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4570,-1542.5 4570,-1818.5 "/>
<text text-anchor="middle" x="4706" y="-1803.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="4570,-1795.5 4842,-1795.5 "/>
<text text-anchor="middle" x="4706" y="-1780.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="4570,-1772.5 4842,-1772.5 "/>
<text text-anchor="middle" x="4706" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="4570,-1749.5 4842,-1749.5 "/>
<text text-anchor="middle" x="4706" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="4570,-1726.5 4842,-1726.5 "/>
<text text-anchor="middle" x="4706" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="4570,-1703.5 4842,-1703.5 "/>
<text text-anchor="middle" x="4706" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="4570,-1680.5 4842,-1680.5 "/>
<text text-anchor="middle" x="4706" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="4570,-1657.5 4842,-1657.5 "/>
<text text-anchor="middle" x="4706" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="4570,-1634.5 4842,-1634.5 "/>
<text text-anchor="middle" x="4706" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="4570,-1611.5 4842,-1611.5 "/>
<text text-anchor="middle" x="4706" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="4570,-1588.5 4842,-1588.5 "/>
<text text-anchor="middle" x="4706" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="4570,-1565.5 4842,-1565.5 "/>
<text text-anchor="middle" x="4706" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="4842,-1542.5 4842,-1818.5 "/>
<text text-anchor="middle" x="4852.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M4551.2325,-1542.2976C4510.9841,-1485.4636 4458.2003,-1423.2074 4397.5,-1381 4117.82,-1186.5271 3723.6118,-1094.8941 3496.932,-1055.8751"/>
<polygon fill="#000000" stroke="#000000" points="3497.3806,-1052.4012 3486.9344,-1054.1697 3496.2034,-1059.3015 3497.3806,-1052.4012"/>
<text text-anchor="middle" x="4433.5" y="-1351.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
<!-- diagnosis -->
<g id="node21" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1696.5,-835C1696.5,-835 2070.5,-835 2070.5,-835 2076.5,-835 2082.5,-841 2082.5,-847 2082.5,-847 2082.5,-1214 2082.5,-1214 2082.5,-1220 2076.5,-1226 2070.5,-1226 2070.5,-1226 1696.5,-1226 1696.5,-1226 1690.5,-1226 1684.5,-1220 1684.5,-1214 1684.5,-1214 1684.5,-847 1684.5,-847 1684.5,-841 1690.5,-835 1696.5,-835"/>
<text text-anchor="middle" x="1726.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1768.5,-835 1768.5,-1226 "/>
<text text-anchor="middle" x="1779" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1789.5,-835 1789.5,-1226 "/>
<text text-anchor="middle" x="1925.5" y="-1210.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1789.5,-1203 2061.5,-1203 "/>
<text text-anchor="middle" x="1925.5" y="-1187.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1789.5,-1180 2061.5,-1180 "/>
<text text-anchor="middle" x="1925.5" y="-1164.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1789.5,-1157 2061.5,-1157 "/>
<text text-anchor="middle" x="1925.5" y="-1141.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1789.5,-1134 2061.5,-1134 "/>
<text text-anchor="middle" x="1925.5" y="-1118.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1789.5,-1111 2061.5,-1111 "/>
<text text-anchor="middle" x="1925.5" y="-1095.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="1789.5,-1088 2061.5,-1088 "/>
<text text-anchor="middle" x="1925.5" y="-1072.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="1789.5,-1065 2061.5,-1065 "/>
<text text-anchor="middle" x="1925.5" y="-1049.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="1789.5,-1042 2061.5,-1042 "/>
<text text-anchor="middle" x="1925.5" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1789.5,-1019 2061.5,-1019 "/>
<text text-anchor="middle" x="1925.5" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="1789.5,-996 2061.5,-996 "/>
<text text-anchor="middle" x="1925.5" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1789.5,-973 2061.5,-973 "/>
<text text-anchor="middle" x="1925.5" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="1789.5,-950 2061.5,-950 "/>
<text text-anchor="middle" x="1925.5" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1789.5,-927 2061.5,-927 "/>
<text text-anchor="middle" x="1925.5" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1789.5,-904 2061.5,-904 "/>
<text text-anchor="middle" x="1925.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1789.5,-881 2061.5,-881 "/>
<text text-anchor="middle" x="1925.5" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1789.5,-858 2061.5,-858 "/>
<text text-anchor="middle" x="1925.5" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="2061.5,-835 2061.5,-1226 "/>
<text text-anchor="middle" x="2072" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1999.1519,-834.8759C2026.4933,-797.6885 2057.6571,-761.0578 2091.5,-731 2111.0084,-713.6735 2133.7579,-698.1402 2156.8622,-684.6011"/>
<polygon fill="#000000" stroke="#000000" points="2158.7992,-687.5249 2165.7285,-679.5101 2155.3135,-681.4544 2158.7992,-687.5249"/>
<text text-anchor="middle" x="2176" y="-701.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- medical_history -->
<g id="node22" class="node">
<title>medical_history</title>
<path fill="none" stroke="#000000" d="M2112.5,-996C2112.5,-996 2466.5,-996 2466.5,-996 2472.5,-996 2478.5,-1002 2478.5,-1008 2478.5,-1008 2478.5,-1053 2478.5,-1053 2478.5,-1059 2472.5,-1065 2466.5,-1065 2466.5,-1065 2112.5,-1065 2112.5,-1065 2106.5,-1065 2100.5,-1059 2100.5,-1053 2100.5,-1053 2100.5,-1008 2100.5,-1008 2100.5,-1002 2106.5,-996 2112.5,-996"/>
<text text-anchor="middle" x="2166" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
<polyline fill="none" stroke="#000000" points="2231.5,-996 2231.5,-1065 "/>
<text text-anchor="middle" x="2242" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2252.5,-996 2252.5,-1065 "/>
<text text-anchor="middle" x="2355" y="-1049.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_category</text>
<polyline fill="none" stroke="#000000" points="2252.5,-1042 2457.5,-1042 "/>
<text text-anchor="middle" x="2355" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_condition</text>
<polyline fill="none" stroke="#000000" points="2252.5,-1019 2457.5,-1019 "/>
<text text-anchor="middle" x="2355" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_id</text>
<polyline fill="none" stroke="#000000" points="2457.5,-996 2457.5,-1065 "/>
<text text-anchor="middle" x="2468" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2290.0968,-995.6715C2291.256,-928.0224 2293.8304,-777.7918 2295.3381,-689.8075"/>
<polygon fill="#000000" stroke="#000000" points="2298.84,-689.7168 2295.512,-679.6583 2291.8411,-689.5968 2298.84,-689.7168"/>
<text text-anchor="middle" x="2362.5" y="-701.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge26" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3291.4355,-949.5869C3258.852,-847.9099 3201.7396,-667.938 3155.5,-513 3134.0958,-441.2795 3159.9118,-406.3229 3109.5,-351 3031.2428,-265.119 2911.9959,-215.5702 2807.5317,-187.1701"/>
<polygon fill="#000000" stroke="#000000" points="2808.3573,-183.768 2797.7929,-184.5717 2806.5526,-190.5314 2808.3573,-183.768"/>
<text text-anchor="middle" x="3201" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3292.1853,-949.7789C3265.7814,-879.8408 3217.2091,-782.0875 3139.5,-731 3125.6081,-721.8672 2713.3473,-671.5567 2470.5937,-642.5833"/>
<polygon fill="#000000" stroke="#000000" points="2470.9424,-639.1002 2460.5982,-641.391 2470.1132,-646.0509 2470.9424,-639.1002"/>
<text text-anchor="middle" x="3063" y="-701.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
</g>
</svg>
</div>
