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
<svg width="3722pt" height="1574pt"
 viewBox="0.00 0.00 3722.00 1574.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1570)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1570 3718,-1570 3718,4 -4,4"/>
<!-- study -->
<g id="node1" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M1101,-.5C1101,-.5 1491,-.5 1491,-.5 1497,-.5 1503,-6.5 1503,-12.5 1503,-12.5 1503,-195.5 1503,-195.5 1503,-201.5 1497,-207.5 1491,-207.5 1491,-207.5 1101,-207.5 1101,-207.5 1095,-207.5 1089,-201.5 1089,-195.5 1089,-195.5 1089,-12.5 1089,-12.5 1089,-6.5 1095,-.5 1101,-.5"/>
<text text-anchor="middle" x="1117" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="1145,-.5 1145,-207.5 "/>
<text text-anchor="middle" x="1155.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1166,-.5 1166,-207.5 "/>
<text text-anchor="middle" x="1324" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="1166,-184.5 1482,-184.5 "/>
<text text-anchor="middle" x="1324" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="1166,-161.5 1482,-161.5 "/>
<text text-anchor="middle" x="1324" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="1166,-138.5 1482,-138.5 "/>
<text text-anchor="middle" x="1324" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="1166,-115.5 1482,-115.5 "/>
<text text-anchor="middle" x="1324" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="1166,-92.5 1482,-92.5 "/>
<text text-anchor="middle" x="1324" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="1166,-69.5 1482,-69.5 "/>
<text text-anchor="middle" x="1324" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="1166,-46.5 1482,-46.5 "/>
<text text-anchor="middle" x="1324" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="1166,-23.5 1482,-23.5 "/>
<text text-anchor="middle" x="1324" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="1482,-.5 1482,-207.5 "/>
<text text-anchor="middle" x="1492.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis -->
<g id="node2" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M618.5,-639.5C618.5,-639.5 1001.5,-639.5 1001.5,-639.5 1007.5,-639.5 1013.5,-645.5 1013.5,-651.5 1013.5,-651.5 1013.5,-926.5 1013.5,-926.5 1013.5,-932.5 1007.5,-938.5 1001.5,-938.5 1001.5,-938.5 618.5,-938.5 618.5,-938.5 612.5,-938.5 606.5,-932.5 606.5,-926.5 606.5,-926.5 606.5,-651.5 606.5,-651.5 606.5,-645.5 612.5,-639.5 618.5,-639.5"/>
<text text-anchor="middle" x="648.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="690.5,-639.5 690.5,-938.5 "/>
<text text-anchor="middle" x="701" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="711.5,-639.5 711.5,-938.5 "/>
<text text-anchor="middle" x="852" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="711.5,-915.5 992.5,-915.5 "/>
<text text-anchor="middle" x="852" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="711.5,-892.5 992.5,-892.5 "/>
<text text-anchor="middle" x="852" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="711.5,-869.5 992.5,-869.5 "/>
<text text-anchor="middle" x="852" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="711.5,-846.5 992.5,-846.5 "/>
<text text-anchor="middle" x="852" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="711.5,-823.5 992.5,-823.5 "/>
<text text-anchor="middle" x="852" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="711.5,-800.5 992.5,-800.5 "/>
<text text-anchor="middle" x="852" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="711.5,-777.5 992.5,-777.5 "/>
<text text-anchor="middle" x="852" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="711.5,-754.5 992.5,-754.5 "/>
<text text-anchor="middle" x="852" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis_reference_source</text>
<polyline fill="none" stroke="#000000" points="711.5,-731.5 992.5,-731.5 "/>
<text text-anchor="middle" x="852" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="711.5,-708.5 992.5,-708.5 "/>
<text text-anchor="middle" x="852" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="711.5,-685.5 992.5,-685.5 "/>
<text text-anchor="middle" x="852" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="711.5,-662.5 992.5,-662.5 "/>
<text text-anchor="middle" x="852" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="992.5,-639.5 992.5,-938.5 "/>
<text text-anchor="middle" x="1003" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node15" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M800.5,-495.5C800.5,-495.5 1031.5,-495.5 1031.5,-495.5 1037.5,-495.5 1043.5,-501.5 1043.5,-507.5 1043.5,-507.5 1043.5,-575.5 1043.5,-575.5 1043.5,-581.5 1037.5,-587.5 1031.5,-587.5 1031.5,-587.5 800.5,-587.5 800.5,-587.5 794.5,-587.5 788.5,-581.5 788.5,-575.5 788.5,-575.5 788.5,-507.5 788.5,-507.5 788.5,-501.5 794.5,-495.5 800.5,-495.5"/>
<text text-anchor="middle" x="836.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="884.5,-495.5 884.5,-587.5 "/>
<text text-anchor="middle" x="895" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="905.5,-495.5 905.5,-587.5 "/>
<text text-anchor="middle" x="964" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="905.5,-564.5 1022.5,-564.5 "/>
<text text-anchor="middle" x="964" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="905.5,-541.5 1022.5,-541.5 "/>
<text text-anchor="middle" x="964" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="905.5,-518.5 1022.5,-518.5 "/>
<text text-anchor="middle" x="964" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1022.5,-495.5 1022.5,-587.5 "/>
<text text-anchor="middle" x="1033" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M874.106,-639.3186C880.4641,-624.4731 886.5989,-610.1488 892.1218,-597.2533"/>
<polygon fill="#000000" stroke="#000000" points="895.4999,-598.2559 896.2195,-587.6855 889.0652,-595.5 895.4999,-598.2559"/>
<text text-anchor="middle" x="932.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- clinical_measure_file -->
<g id="node3" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M12,-662.5C12,-662.5 364,-662.5 364,-662.5 370,-662.5 376,-668.5 376,-674.5 376,-674.5 376,-903.5 376,-903.5 376,-909.5 370,-915.5 364,-915.5 364,-915.5 12,-915.5 12,-915.5 6,-915.5 0,-909.5 0,-903.5 0,-903.5 0,-674.5 0,-674.5 0,-668.5 6,-662.5 12,-662.5"/>
<text text-anchor="middle" x="83.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="167,-662.5 167,-915.5 "/>
<text text-anchor="middle" x="177.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="188,-662.5 188,-915.5 "/>
<text text-anchor="middle" x="271.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="188,-892.5 355,-892.5 "/>
<text text-anchor="middle" x="271.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="188,-869.5 355,-869.5 "/>
<text text-anchor="middle" x="271.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="188,-846.5 355,-846.5 "/>
<text text-anchor="middle" x="271.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="188,-823.5 355,-823.5 "/>
<text text-anchor="middle" x="271.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="188,-800.5 355,-800.5 "/>
<text text-anchor="middle" x="271.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="188,-777.5 355,-777.5 "/>
<text text-anchor="middle" x="271.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="188,-754.5 355,-754.5 "/>
<text text-anchor="middle" x="271.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="188,-731.5 355,-731.5 "/>
<text text-anchor="middle" x="271.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="188,-708.5 355,-708.5 "/>
<text text-anchor="middle" x="271.5" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="188,-685.5 355,-685.5 "/>
<text text-anchor="middle" x="271.5" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="355,-662.5 355,-915.5 "/>
<text text-anchor="middle" x="365.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge1" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M148.946,-662.4877C135.4301,-601.5311 126.8305,-527.5914 141,-462 161.916,-365.1782 162.924,-329.0093 233,-259 258.1889,-233.8351 271.7187,-235.6202 306,-226 565.4767,-153.1845 875.3297,-123.8139 1078.4232,-111.9763"/>
<polygon fill="#000000" stroke="#000000" points="1078.8338,-115.4586 1088.6169,-111.3917 1078.4329,-108.4701 1078.8338,-115.4586"/>
<text text-anchor="middle" x="227" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M376.1082,-700.8134C451.4076,-667.8659 539.6802,-632.1427 622,-606 672.3102,-590.0227 728.6931,-576.6116 778.5227,-566.2292"/>
<polygon fill="#000000" stroke="#000000" points="779.3103,-569.6405 788.3975,-564.1932 777.8968,-562.7847 779.3103,-569.6405"/>
<text text-anchor="middle" x="751.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- sample -->
<g id="node4" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M2167,-720C2167,-720 2481,-720 2481,-720 2487,-720 2493,-726 2493,-732 2493,-732 2493,-846 2493,-846 2493,-852 2487,-858 2481,-858 2481,-858 2167,-858 2167,-858 2161,-858 2155,-852 2155,-846 2155,-846 2155,-732 2155,-732 2155,-726 2161,-720 2167,-720"/>
<text text-anchor="middle" x="2189" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="2223,-720 2223,-858 "/>
<text text-anchor="middle" x="2233.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2244,-720 2244,-858 "/>
<text text-anchor="middle" x="2358" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="2244,-835 2472,-835 "/>
<text text-anchor="middle" x="2358" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="2244,-812 2472,-812 "/>
<text text-anchor="middle" x="2358" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="2244,-789 2472,-789 "/>
<text text-anchor="middle" x="2358" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="2244,-766 2472,-766 "/>
<text text-anchor="middle" x="2358" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="2244,-743 2472,-743 "/>
<text text-anchor="middle" x="2358" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="2472,-720 2472,-858 "/>
<text text-anchor="middle" x="2482.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge19" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2323.5068,-719.6869C2318.5918,-599.0212 2289.7713,-351.2972 2141,-226 2093.6044,-186.0828 1747.5747,-146.2584 1513.2789,-123.4379"/>
<polygon fill="#000000" stroke="#000000" points="1513.5446,-119.9473 1503.2533,-122.4651 1512.8685,-126.9146 1513.5446,-119.9473"/>
<text text-anchor="middle" x="2322.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2154.828,-754.7123C1996.8512,-723.1207 1754.3581,-675.7183 1543,-639 1374.9769,-609.8101 1180.8835,-580.2694 1053.6933,-561.4764"/>
<polygon fill="#000000" stroke="#000000" points="1053.9128,-557.9709 1043.509,-559.9734 1052.8908,-564.8959 1053.9128,-557.9709"/>
<text text-anchor="middle" x="1459.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_admin -->
<g id="node5" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M399,-259.5C399,-259.5 725,-259.5 725,-259.5 731,-259.5 737,-265.5 737,-271.5 737,-271.5 737,-431.5 737,-431.5 737,-437.5 731,-443.5 725,-443.5 725,-443.5 399,-443.5 399,-443.5 393,-443.5 387,-437.5 387,-431.5 387,-431.5 387,-271.5 387,-271.5 387,-265.5 393,-259.5 399,-259.5"/>
<text text-anchor="middle" x="441" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="495,-259.5 495,-443.5 "/>
<text text-anchor="middle" x="505.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="516,-259.5 516,-443.5 "/>
<text text-anchor="middle" x="616" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="516,-420.5 716,-420.5 "/>
<text text-anchor="middle" x="616" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="516,-397.5 716,-397.5 "/>
<text text-anchor="middle" x="616" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="516,-374.5 716,-374.5 "/>
<text text-anchor="middle" x="616" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="516,-351.5 716,-351.5 "/>
<text text-anchor="middle" x="616" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="516,-328.5 716,-328.5 "/>
<text text-anchor="middle" x="616" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="516,-305.5 716,-305.5 "/>
<text text-anchor="middle" x="616" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="516,-282.5 716,-282.5 "/>
<text text-anchor="middle" x="616" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="716,-259.5 716,-443.5 "/>
<text text-anchor="middle" x="726.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge10" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M737.2083,-262.4848C740.1515,-261.2948 743.0835,-260.132 746,-259 853.3993,-217.3121 976.5381,-181.5501 1079.0363,-154.9162"/>
<polygon fill="#000000" stroke="#000000" points="1080.085,-158.2602 1088.8898,-152.3673 1078.3319,-151.4833 1080.085,-158.2602"/>
<text text-anchor="middle" x="890.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- study_arm -->
<g id="node6" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M767.5,-317C767.5,-317 1064.5,-317 1064.5,-317 1070.5,-317 1076.5,-323 1076.5,-329 1076.5,-329 1076.5,-374 1076.5,-374 1076.5,-380 1070.5,-386 1064.5,-386 1064.5,-386 767.5,-386 767.5,-386 761.5,-386 755.5,-380 755.5,-374 755.5,-374 755.5,-329 755.5,-329 755.5,-323 761.5,-317 767.5,-317"/>
<text text-anchor="middle" x="801.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="847.5,-317 847.5,-386 "/>
<text text-anchor="middle" x="858" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="868.5,-317 868.5,-386 "/>
<text text-anchor="middle" x="962" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="868.5,-363 1055.5,-363 "/>
<text text-anchor="middle" x="962" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="868.5,-340 1055.5,-340 "/>
<text text-anchor="middle" x="962" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="1055.5,-317 1055.5,-386 "/>
<text text-anchor="middle" x="1066" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge2" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M969.2375,-316.8256C1010.8029,-289.7534 1070.9447,-250.582 1128.331,-213.2055"/>
<polygon fill="#000000" stroke="#000000" points="1130.306,-216.0961 1136.7752,-207.7056 1126.4856,-210.2305 1130.306,-216.0961"/>
<text text-anchor="middle" x="1154.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- study_funding -->
<g id="node7" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M1106.5,-317C1106.5,-317 1485.5,-317 1485.5,-317 1491.5,-317 1497.5,-323 1497.5,-329 1497.5,-329 1497.5,-374 1497.5,-374 1497.5,-380 1491.5,-386 1485.5,-386 1485.5,-386 1106.5,-386 1106.5,-386 1100.5,-386 1094.5,-380 1094.5,-374 1094.5,-374 1094.5,-329 1094.5,-329 1094.5,-323 1100.5,-317 1106.5,-317"/>
<text text-anchor="middle" x="1154" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="1213.5,-317 1213.5,-386 "/>
<text text-anchor="middle" x="1224" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1234.5,-317 1234.5,-386 "/>
<text text-anchor="middle" x="1355.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="1234.5,-363 1476.5,-363 "/>
<text text-anchor="middle" x="1355.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="1234.5,-340 1476.5,-340 "/>
<text text-anchor="middle" x="1355.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="1476.5,-317 1476.5,-386 "/>
<text text-anchor="middle" x="1487" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge3" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1296,-316.8256C1296,-290.8629 1296,-253.7725 1296,-217.8091"/>
<polygon fill="#000000" stroke="#000000" points="1299.5001,-217.7056 1296,-207.7056 1292.5001,-217.7056 1299.5001,-217.7056"/>
<text text-anchor="middle" x="1358" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- sample_diagnosis -->
<g id="node8" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M2373,-1059.5C2373,-1059.5 2815,-1059.5 2815,-1059.5 2821,-1059.5 2827,-1065.5 2827,-1071.5 2827,-1071.5 2827,-1484.5 2827,-1484.5 2827,-1490.5 2821,-1496.5 2815,-1496.5 2815,-1496.5 2373,-1496.5 2373,-1496.5 2367,-1496.5 2361,-1490.5 2361,-1484.5 2361,-1484.5 2361,-1071.5 2361,-1071.5 2361,-1065.5 2367,-1059.5 2373,-1059.5"/>
<text text-anchor="middle" x="2432.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2504,-1059.5 2504,-1496.5 "/>
<text text-anchor="middle" x="2514.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2525,-1059.5 2525,-1496.5 "/>
<text text-anchor="middle" x="2665.5" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2525,-1473.5 2806,-1473.5 "/>
<text text-anchor="middle" x="2665.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="2525,-1450.5 2806,-1450.5 "/>
<text text-anchor="middle" x="2665.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2525,-1427.5 2806,-1427.5 "/>
<text text-anchor="middle" x="2665.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="2525,-1404.5 2806,-1404.5 "/>
<text text-anchor="middle" x="2665.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="2525,-1381.5 2806,-1381.5 "/>
<text text-anchor="middle" x="2665.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2525,-1358.5 2806,-1358.5 "/>
<text text-anchor="middle" x="2665.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2525,-1335.5 2806,-1335.5 "/>
<text text-anchor="middle" x="2665.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis_reference_source</text>
<polyline fill="none" stroke="#000000" points="2525,-1312.5 2806,-1312.5 "/>
<text text-anchor="middle" x="2665.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="2525,-1289.5 2806,-1289.5 "/>
<text text-anchor="middle" x="2665.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="2525,-1266.5 2806,-1266.5 "/>
<text text-anchor="middle" x="2665.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="2525,-1243.5 2806,-1243.5 "/>
<text text-anchor="middle" x="2665.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="2525,-1220.5 2806,-1220.5 "/>
<text text-anchor="middle" x="2665.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="2525,-1197.5 2806,-1197.5 "/>
<text text-anchor="middle" x="2665.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="2525,-1174.5 2806,-1174.5 "/>
<text text-anchor="middle" x="2665.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="2525,-1151.5 2806,-1151.5 "/>
<text text-anchor="middle" x="2665.5" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="2525,-1128.5 2806,-1128.5 "/>
<text text-anchor="middle" x="2665.5" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="2525,-1105.5 2806,-1105.5 "/>
<text text-anchor="middle" x="2665.5" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="2525,-1082.5 2806,-1082.5 "/>
<text text-anchor="middle" x="2665.5" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="2806,-1059.5 2806,-1496.5 "/>
<text text-anchor="middle" x="2816.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2502.0623,-1059.462C2485.2668,-1024.563 2467.0006,-989.3287 2448,-957 2429.8609,-926.1372 2407.2646,-894.0861 2386.3489,-866.356"/>
<polygon fill="#000000" stroke="#000000" points="2389.0464,-864.121 2380.21,-858.2757 2383.4726,-868.3557 2389.0464,-864.121"/>
<text text-anchor="middle" x="2526" y="-960.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
<!-- therapeutic_procedure -->
<g id="node9" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M1165.5,-731.5C1165.5,-731.5 1522.5,-731.5 1522.5,-731.5 1528.5,-731.5 1534.5,-737.5 1534.5,-743.5 1534.5,-743.5 1534.5,-834.5 1534.5,-834.5 1534.5,-840.5 1528.5,-846.5 1522.5,-846.5 1522.5,-846.5 1165.5,-846.5 1165.5,-846.5 1159.5,-846.5 1153.5,-840.5 1153.5,-834.5 1153.5,-834.5 1153.5,-743.5 1153.5,-743.5 1153.5,-737.5 1159.5,-731.5 1165.5,-731.5"/>
<text text-anchor="middle" x="1244" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="1334.5,-731.5 1334.5,-846.5 "/>
<text text-anchor="middle" x="1345" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1355.5,-731.5 1355.5,-846.5 "/>
<text text-anchor="middle" x="1434.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="1355.5,-823.5 1513.5,-823.5 "/>
<text text-anchor="middle" x="1434.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="1355.5,-800.5 1513.5,-800.5 "/>
<text text-anchor="middle" x="1434.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1355.5,-777.5 1513.5,-777.5 "/>
<text text-anchor="middle" x="1434.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="1355.5,-754.5 1513.5,-754.5 "/>
<text text-anchor="middle" x="1434.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1513.5,-731.5 1513.5,-846.5 "/>
<text text-anchor="middle" x="1524" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1273.0778,-731.1869C1234.7499,-701.4943 1185.7987,-665.988 1139,-639 1107.4526,-620.8071 1097.3591,-620.6081 1064,-606 1053.3691,-601.3447 1042.3053,-596.5079 1031.2268,-591.6702"/>
<polygon fill="#000000" stroke="#000000" points="1032.4917,-588.4034 1021.9266,-587.6102 1029.6911,-594.8188 1032.4917,-588.4034"/>
<text text-anchor="middle" x="1194" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- study_personnel -->
<g id="node10" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M1527.5,-294C1527.5,-294 1834.5,-294 1834.5,-294 1840.5,-294 1846.5,-300 1846.5,-306 1846.5,-306 1846.5,-397 1846.5,-397 1846.5,-403 1840.5,-409 1834.5,-409 1834.5,-409 1527.5,-409 1527.5,-409 1521.5,-409 1515.5,-403 1515.5,-397 1515.5,-397 1515.5,-306 1515.5,-306 1515.5,-300 1521.5,-294 1527.5,-294"/>
<text text-anchor="middle" x="1582.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="1649.5,-294 1649.5,-409 "/>
<text text-anchor="middle" x="1660" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1670.5,-294 1670.5,-409 "/>
<text text-anchor="middle" x="1748" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="1670.5,-386 1825.5,-386 "/>
<text text-anchor="middle" x="1748" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="1670.5,-363 1825.5,-363 "/>
<text text-anchor="middle" x="1748" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="1670.5,-340 1825.5,-340 "/>
<text text-anchor="middle" x="1748" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="1670.5,-317 1825.5,-317 "/>
<text text-anchor="middle" x="1748" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="1825.5,-294 1825.5,-409 "/>
<text text-anchor="middle" x="1836" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge20" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1591.2205,-293.7846C1553.829,-269.7472 1509.1251,-241.009 1465.9548,-213.2566"/>
<polygon fill="#000000" stroke="#000000" points="1467.6482,-210.1845 1457.3438,-207.721 1463.8629,-216.0727 1467.6482,-210.1845"/>
<text text-anchor="middle" x="1569.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- sequencing_file -->
<g id="node11" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M2856.5,-990.5C2856.5,-990.5 3325.5,-990.5 3325.5,-990.5 3331.5,-990.5 3337.5,-996.5 3337.5,-1002.5 3337.5,-1002.5 3337.5,-1553.5 3337.5,-1553.5 3337.5,-1559.5 3331.5,-1565.5 3325.5,-1565.5 3325.5,-1565.5 2856.5,-1565.5 2856.5,-1565.5 2850.5,-1565.5 2844.5,-1559.5 2844.5,-1553.5 2844.5,-1553.5 2844.5,-1002.5 2844.5,-1002.5 2844.5,-996.5 2850.5,-990.5 2856.5,-990.5"/>
<text text-anchor="middle" x="2908.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="2972.5,-990.5 2972.5,-1565.5 "/>
<text text-anchor="middle" x="2983" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2993.5,-990.5 2993.5,-1565.5 "/>
<text text-anchor="middle" x="3155" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="2993.5,-1542.5 3316.5,-1542.5 "/>
<text text-anchor="middle" x="3155" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2993.5,-1519.5 3316.5,-1519.5 "/>
<text text-anchor="middle" x="3155" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2993.5,-1496.5 3316.5,-1496.5 "/>
<text text-anchor="middle" x="3155" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="2993.5,-1473.5 3316.5,-1473.5 "/>
<text text-anchor="middle" x="3155" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="2993.5,-1450.5 3316.5,-1450.5 "/>
<text text-anchor="middle" x="3155" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2993.5,-1427.5 3316.5,-1427.5 "/>
<text text-anchor="middle" x="3155" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="2993.5,-1404.5 3316.5,-1404.5 "/>
<text text-anchor="middle" x="3155" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2993.5,-1381.5 3316.5,-1381.5 "/>
<text text-anchor="middle" x="3155" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2993.5,-1358.5 3316.5,-1358.5 "/>
<text text-anchor="middle" x="3155" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2993.5,-1335.5 3316.5,-1335.5 "/>
<text text-anchor="middle" x="3155" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2993.5,-1312.5 3316.5,-1312.5 "/>
<text text-anchor="middle" x="3155" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2993.5,-1289.5 3316.5,-1289.5 "/>
<text text-anchor="middle" x="3155" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2993.5,-1266.5 3316.5,-1266.5 "/>
<text text-anchor="middle" x="3155" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="2993.5,-1243.5 3316.5,-1243.5 "/>
<text text-anchor="middle" x="3155" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="2993.5,-1220.5 3316.5,-1220.5 "/>
<text text-anchor="middle" x="3155" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="2993.5,-1197.5 3316.5,-1197.5 "/>
<text text-anchor="middle" x="3155" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="2993.5,-1174.5 3316.5,-1174.5 "/>
<text text-anchor="middle" x="3155" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="2993.5,-1151.5 3316.5,-1151.5 "/>
<text text-anchor="middle" x="3155" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="2993.5,-1128.5 3316.5,-1128.5 "/>
<text text-anchor="middle" x="3155" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2993.5,-1105.5 3316.5,-1105.5 "/>
<text text-anchor="middle" x="3155" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="2993.5,-1082.5 3316.5,-1082.5 "/>
<text text-anchor="middle" x="3155" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="2993.5,-1059.5 3316.5,-1059.5 "/>
<text text-anchor="middle" x="3155" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="2993.5,-1036.5 3316.5,-1036.5 "/>
<text text-anchor="middle" x="3155" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="2993.5,-1013.5 3316.5,-1013.5 "/>
<text text-anchor="middle" x="3155" y="-998.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="3316.5,-990.5 3316.5,-1565.5 "/>
<text text-anchor="middle" x="3327" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2844.1806,-995.8427C2841.4638,-993.8614 2838.7367,-991.9131 2836,-990 2735.1528,-919.5018 2606.1139,-869.0498 2502.8114,-836.3243"/>
<polygon fill="#000000" stroke="#000000" points="2503.8027,-832.9672 2493.2135,-833.3112 2501.706,-839.6458 2503.8027,-832.9672"/>
<text text-anchor="middle" x="2864.5" y="-960.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- methylation_array_file -->
<g id="node12" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M1963.5,-1163C1963.5,-1163 2330.5,-1163 2330.5,-1163 2336.5,-1163 2342.5,-1169 2342.5,-1175 2342.5,-1175 2342.5,-1381 2342.5,-1381 2342.5,-1387 2336.5,-1393 2330.5,-1393 2330.5,-1393 1963.5,-1393 1963.5,-1393 1957.5,-1393 1951.5,-1387 1951.5,-1381 1951.5,-1381 1951.5,-1175 1951.5,-1175 1951.5,-1169 1957.5,-1163 1963.5,-1163"/>
<text text-anchor="middle" x="2040.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="2129.5,-1163 2129.5,-1393 "/>
<text text-anchor="middle" x="2140" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2150.5,-1163 2150.5,-1393 "/>
<text text-anchor="middle" x="2236" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2150.5,-1370 2321.5,-1370 "/>
<text text-anchor="middle" x="2236" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2150.5,-1347 2321.5,-1347 "/>
<text text-anchor="middle" x="2236" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2150.5,-1324 2321.5,-1324 "/>
<text text-anchor="middle" x="2236" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2150.5,-1301 2321.5,-1301 "/>
<text text-anchor="middle" x="2236" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2150.5,-1278 2321.5,-1278 "/>
<text text-anchor="middle" x="2236" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2150.5,-1255 2321.5,-1255 "/>
<text text-anchor="middle" x="2236" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2150.5,-1232 2321.5,-1232 "/>
<text text-anchor="middle" x="2236" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2150.5,-1209 2321.5,-1209 "/>
<text text-anchor="middle" x="2236" y="-1193.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="2150.5,-1186 2321.5,-1186 "/>
<text text-anchor="middle" x="2236" y="-1170.8" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="2321.5,-1163 2321.5,-1393 "/>
<text text-anchor="middle" x="2332" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2188.7224,-1162.733C2221.6236,-1071.8365 2266.6292,-947.4991 2295.5119,-867.7044"/>
<polygon fill="#000000" stroke="#000000" points="2298.8398,-868.7937 2298.9524,-858.1994 2292.2577,-866.4111 2298.8398,-868.7937"/>
<text text-anchor="middle" x="2352.5" y="-960.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- imaging_file -->
<g id="node13" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M3368,-1117C3368,-1117 3702,-1117 3702,-1117 3708,-1117 3714,-1123 3714,-1129 3714,-1129 3714,-1427 3714,-1427 3714,-1433 3708,-1439 3702,-1439 3702,-1439 3368,-1439 3368,-1439 3362,-1439 3356,-1433 3356,-1427 3356,-1427 3356,-1129 3356,-1129 3356,-1123 3362,-1117 3368,-1117"/>
<text text-anchor="middle" x="3408" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="3460,-1117 3460,-1439 "/>
<text text-anchor="middle" x="3470.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3481,-1117 3481,-1439 "/>
<text text-anchor="middle" x="3587" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="3481,-1416 3693,-1416 "/>
<text text-anchor="middle" x="3587" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="3481,-1393 3693,-1393 "/>
<text text-anchor="middle" x="3587" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="3481,-1370 3693,-1370 "/>
<text text-anchor="middle" x="3587" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="3481,-1347 3693,-1347 "/>
<text text-anchor="middle" x="3587" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="3481,-1324 3693,-1324 "/>
<text text-anchor="middle" x="3587" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="3481,-1301 3693,-1301 "/>
<text text-anchor="middle" x="3587" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="3481,-1278 3693,-1278 "/>
<text text-anchor="middle" x="3587" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="3481,-1255 3693,-1255 "/>
<text text-anchor="middle" x="3587" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="3481,-1232 3693,-1232 "/>
<text text-anchor="middle" x="3587" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="3481,-1209 3693,-1209 "/>
<text text-anchor="middle" x="3587" y="-1193.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="3481,-1186 3693,-1186 "/>
<text text-anchor="middle" x="3587" y="-1170.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="3481,-1163 3693,-1163 "/>
<text text-anchor="middle" x="3587" y="-1147.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="3481,-1140 3693,-1140 "/>
<text text-anchor="middle" x="3587" y="-1124.8" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="3693,-1117 3693,-1439 "/>
<text text-anchor="middle" x="3703.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3461.0301,-1116.7987C3431.8472,-1069.2966 3393.9085,-1021.6285 3347,-990 3211.586,-898.6959 2758.7222,-836.2349 2503.2654,-807.3241"/>
<polygon fill="#000000" stroke="#000000" points="2503.4627,-803.8243 2493.1339,-806.1834 2502.6795,-810.7804 2503.4627,-803.8243"/>
<text text-anchor="middle" x="3359.5" y="-960.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- publication -->
<g id="node14" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M1877,-333.5C1877,-333.5 2087,-333.5 2087,-333.5 2093,-333.5 2099,-339.5 2099,-345.5 2099,-345.5 2099,-357.5 2099,-357.5 2099,-363.5 2093,-369.5 2087,-369.5 2087,-369.5 1877,-369.5 1877,-369.5 1871,-369.5 1865,-363.5 1865,-357.5 1865,-357.5 1865,-345.5 1865,-345.5 1865,-339.5 1871,-333.5 1877,-333.5"/>
<text text-anchor="middle" x="1913.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="1962,-333.5 1962,-369.5 "/>
<text text-anchor="middle" x="1972.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1983,-333.5 1983,-369.5 "/>
<text text-anchor="middle" x="2030.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="2078,-333.5 2078,-369.5 "/>
<text text-anchor="middle" x="2088.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge4" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1962.1107,-333.2775C1938.464,-312.516 1897.0186,-278.8975 1856,-259 1748.1817,-206.6989 1619.8441,-169.5612 1513.2461,-144.776"/>
<polygon fill="#000000" stroke="#000000" points="1513.858,-141.3253 1503.3275,-142.4907 1512.2863,-148.1466 1513.858,-141.3253"/>
<text text-anchor="middle" x="1864" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge5" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M788.4478,-530.8846C611.6097,-514.8567 309.8598,-482.254 277,-444 223.424,-381.6292 223.4097,-321.3584 277,-259 328.563,-199.0007 795.1365,-147.9313 1078.7509,-122.0851"/>
<polygon fill="#000000" stroke="#000000" points="1079.1191,-125.5661 1088.7617,-121.1763 1078.4862,-118.5948 1079.1191,-125.5661"/>
<text text-anchor="middle" x="327.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge6" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M916,-495.0208C916,-464.9487 916,-426.0098 916,-396.2801"/>
<polygon fill="#000000" stroke="#000000" points="919.5001,-396.178 916,-386.178 912.5001,-396.178 919.5001,-396.178"/>
<text text-anchor="middle" x="966.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- synonym -->
<g id="node16" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M1620.5,-1255C1620.5,-1255 1921.5,-1255 1921.5,-1255 1927.5,-1255 1933.5,-1261 1933.5,-1267 1933.5,-1267 1933.5,-1289 1933.5,-1289 1933.5,-1295 1927.5,-1301 1921.5,-1301 1921.5,-1301 1620.5,-1301 1620.5,-1301 1614.5,-1301 1608.5,-1295 1608.5,-1289 1608.5,-1289 1608.5,-1267 1608.5,-1267 1608.5,-1261 1614.5,-1255 1620.5,-1255"/>
<text text-anchor="middle" x="1648.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="1688.5,-1255 1688.5,-1301 "/>
<text text-anchor="middle" x="1699" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1709.5,-1255 1709.5,-1301 "/>
<text text-anchor="middle" x="1811" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="1709.5,-1278 1912.5,-1278 "/>
<text text-anchor="middle" x="1811" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="1912.5,-1255 1912.5,-1301 "/>
<text text-anchor="middle" x="1923" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge15" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1782.6877,-1254.9742C1808.5828,-1204.8135 1873.979,-1082.7367 1943,-990 2015.3101,-892.844 2127,-910.1117 2127,-789 2127,-789 2127,-789 2127,-351.5 2127,-309.5306 2137.8834,-288.4688 2108,-259 2025.5775,-177.721 1724.609,-137.3296 1513.2488,-118.5699"/>
<polygon fill="#000000" stroke="#000000" points="1513.5207,-115.0804 1503.253,-117.6928 1512.9088,-122.0536 1513.5207,-115.0804"/>
<text text-anchor="middle" x="2169.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1777.0831,-1254.6019C1793.1862,-1197.9001 1842.7287,-1053.1776 1943,-990 2016.6375,-943.6035 2059.0579,-1008.6505 2138,-972 2189.0393,-948.304 2234.3403,-904.5171 2267.4547,-865.7158"/>
<polygon fill="#000000" stroke="#000000" points="2270.1597,-867.9371 2273.9132,-858.0294 2264.8005,-863.434 2270.1597,-867.9371"/>
<text text-anchor="middle" x="2204.5" y="-960.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1640.3781,-1254.979C1476.1705,-1218.6411 1199.0021,-1131.2798 1060,-939 981.2612,-830.0816 1083.6532,-758.4232 1022,-639 1013.5803,-622.6908 1001.2736,-607.7181 988.0015,-594.6564"/>
<polygon fill="#000000" stroke="#000000" points="990.2157,-591.933 980.5473,-587.6002 985.4035,-597.0166 990.2157,-591.933"/>
<text text-anchor="middle" x="1102.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
</g>
</svg>
</div>
