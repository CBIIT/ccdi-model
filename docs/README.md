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
<svg width="2140pt" height="1574pt"
 viewBox="0.00 0.00 2140.34 1574.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1570)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1570 2136.3414,-1570 2136.3414,4 -4,4"/>
<!-- diagnosis -->
<g id="node1" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M584.8414,-651C584.8414,-651 967.8414,-651 967.8414,-651 973.8414,-651 979.8414,-657 979.8414,-663 979.8414,-663 979.8414,-938 979.8414,-938 979.8414,-944 973.8414,-950 967.8414,-950 967.8414,-950 584.8414,-950 584.8414,-950 578.8414,-950 572.8414,-944 572.8414,-938 572.8414,-938 572.8414,-663 572.8414,-663 572.8414,-657 578.8414,-651 584.8414,-651"/>
<text text-anchor="middle" x="614.8414" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="656.8414,-651 656.8414,-950 "/>
<text text-anchor="middle" x="667.3414" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="677.8414,-651 677.8414,-950 "/>
<text text-anchor="middle" x="818.3414" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="677.8414,-927 958.8414,-927 "/>
<text text-anchor="middle" x="818.3414" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="677.8414,-904 958.8414,-904 "/>
<text text-anchor="middle" x="818.3414" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="677.8414,-881 958.8414,-881 "/>
<text text-anchor="middle" x="818.3414" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="677.8414,-858 958.8414,-858 "/>
<text text-anchor="middle" x="818.3414" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="677.8414,-835 958.8414,-835 "/>
<text text-anchor="middle" x="818.3414" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="677.8414,-812 958.8414,-812 "/>
<text text-anchor="middle" x="818.3414" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="677.8414,-789 958.8414,-789 "/>
<text text-anchor="middle" x="818.3414" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="677.8414,-766 958.8414,-766 "/>
<text text-anchor="middle" x="818.3414" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis_reference_source</text>
<polyline fill="none" stroke="#000000" points="677.8414,-743 958.8414,-743 "/>
<text text-anchor="middle" x="818.3414" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="677.8414,-720 958.8414,-720 "/>
<text text-anchor="middle" x="818.3414" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="677.8414,-697 958.8414,-697 "/>
<text text-anchor="middle" x="818.3414" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="677.8414,-674 958.8414,-674 "/>
<text text-anchor="middle" x="818.3414" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="958.8414,-651 958.8414,-950 "/>
<text text-anchor="middle" x="969.3414" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node12" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M409.8414,-495.5C409.8414,-495.5 640.8414,-495.5 640.8414,-495.5 646.8414,-495.5 652.8414,-501.5 652.8414,-507.5 652.8414,-507.5 652.8414,-575.5 652.8414,-575.5 652.8414,-581.5 646.8414,-587.5 640.8414,-587.5 640.8414,-587.5 409.8414,-587.5 409.8414,-587.5 403.8414,-587.5 397.8414,-581.5 397.8414,-575.5 397.8414,-575.5 397.8414,-507.5 397.8414,-507.5 397.8414,-501.5 403.8414,-495.5 409.8414,-495.5"/>
<text text-anchor="middle" x="445.8414" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="493.8414,-495.5 493.8414,-587.5 "/>
<text text-anchor="middle" x="504.3414" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="514.8414,-495.5 514.8414,-587.5 "/>
<text text-anchor="middle" x="573.3414" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="514.8414,-564.5 631.8414,-564.5 "/>
<text text-anchor="middle" x="573.3414" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="514.8414,-541.5 631.8414,-541.5 "/>
<text text-anchor="middle" x="573.3414" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="514.8414,-518.5 631.8414,-518.5 "/>
<text text-anchor="middle" x="573.3414" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="631.8414,-495.5 631.8414,-587.5 "/>
<text text-anchor="middle" x="642.3414" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M631.4242,-650.9639C612.1012,-631.025 593.4075,-611.7356 577.2357,-595.0484"/>
<polygon fill="#000000" stroke="#000000" points="579.4624,-592.3167 569.9897,-587.5714 574.4356,-597.1883 579.4624,-592.3167"/>
<text text-anchor="middle" x="644.8414" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- therapeutic_procedure -->
<g id="node2" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M1009.8414,-743C1009.8414,-743 1366.8414,-743 1366.8414,-743 1372.8414,-743 1378.8414,-749 1378.8414,-755 1378.8414,-755 1378.8414,-846 1378.8414,-846 1378.8414,-852 1372.8414,-858 1366.8414,-858 1366.8414,-858 1009.8414,-858 1009.8414,-858 1003.8414,-858 997.8414,-852 997.8414,-846 997.8414,-846 997.8414,-755 997.8414,-755 997.8414,-749 1003.8414,-743 1009.8414,-743"/>
<text text-anchor="middle" x="1088.3414" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="1178.8414,-743 1178.8414,-858 "/>
<text text-anchor="middle" x="1189.3414" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1199.8414,-743 1199.8414,-858 "/>
<text text-anchor="middle" x="1278.8414" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="1199.8414,-835 1357.8414,-835 "/>
<text text-anchor="middle" x="1278.8414" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="1199.8414,-812 1357.8414,-812 "/>
<text text-anchor="middle" x="1278.8414" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1199.8414,-789 1357.8414,-789 "/>
<text text-anchor="middle" x="1278.8414" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="1199.8414,-766 1357.8414,-766 "/>
<text text-anchor="middle" x="1278.8414" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1357.8414,-743 1357.8414,-858 "/>
<text text-anchor="middle" x="1368.3414" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1132.5089,-742.8892C1095.1718,-707.6817 1043.1718,-664.6344 989.3414,-639 886.0706,-589.8218 758.2007,-565.3048 662.8637,-553.1663"/>
<polygon fill="#000000" stroke="#000000" points="663.2222,-549.684 652.8668,-551.9236 662.3586,-556.6306 663.2222,-549.684"/>
<text text-anchor="middle" x="1035.3414" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- study_arm -->
<g id="node3" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M179.8414,-317C179.8414,-317 476.8414,-317 476.8414,-317 482.8414,-317 488.8414,-323 488.8414,-329 488.8414,-329 488.8414,-374 488.8414,-374 488.8414,-380 482.8414,-386 476.8414,-386 476.8414,-386 179.8414,-386 179.8414,-386 173.8414,-386 167.8414,-380 167.8414,-374 167.8414,-374 167.8414,-329 167.8414,-329 167.8414,-323 173.8414,-317 179.8414,-317"/>
<text text-anchor="middle" x="213.8414" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="259.8414,-317 259.8414,-386 "/>
<text text-anchor="middle" x="270.3414" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="280.8414,-317 280.8414,-386 "/>
<text text-anchor="middle" x="374.3414" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="280.8414,-363 467.8414,-363 "/>
<text text-anchor="middle" x="374.3414" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="280.8414,-340 467.8414,-340 "/>
<text text-anchor="middle" x="374.3414" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="467.8414,-317 467.8414,-386 "/>
<text text-anchor="middle" x="478.3414" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node8" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M624.3414,-.5C624.3414,-.5 1014.3414,-.5 1014.3414,-.5 1020.3414,-.5 1026.3414,-6.5 1026.3414,-12.5 1026.3414,-12.5 1026.3414,-195.5 1026.3414,-195.5 1026.3414,-201.5 1020.3414,-207.5 1014.3414,-207.5 1014.3414,-207.5 624.3414,-207.5 624.3414,-207.5 618.3414,-207.5 612.3414,-201.5 612.3414,-195.5 612.3414,-195.5 612.3414,-12.5 612.3414,-12.5 612.3414,-6.5 618.3414,-.5 624.3414,-.5"/>
<text text-anchor="middle" x="640.3414" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="668.3414,-.5 668.3414,-207.5 "/>
<text text-anchor="middle" x="678.8414" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="689.3414,-.5 689.3414,-207.5 "/>
<text text-anchor="middle" x="847.3414" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="689.3414,-184.5 1005.3414,-184.5 "/>
<text text-anchor="middle" x="847.3414" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="689.3414,-161.5 1005.3414,-161.5 "/>
<text text-anchor="middle" x="847.3414" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="689.3414,-138.5 1005.3414,-138.5 "/>
<text text-anchor="middle" x="847.3414" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="689.3414,-115.5 1005.3414,-115.5 "/>
<text text-anchor="middle" x="847.3414" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="689.3414,-92.5 1005.3414,-92.5 "/>
<text text-anchor="middle" x="847.3414" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="689.3414,-69.5 1005.3414,-69.5 "/>
<text text-anchor="middle" x="847.3414" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="689.3414,-46.5 1005.3414,-46.5 "/>
<text text-anchor="middle" x="847.3414" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="689.3414,-23.5 1005.3414,-23.5 "/>
<text text-anchor="middle" x="847.3414" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="1005.3414,-.5 1005.3414,-207.5 "/>
<text text-anchor="middle" x="1015.8414" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M343.9143,-316.7956C358.3297,-288.4515 382.3583,-249.3836 414.3414,-226 469.3167,-185.8062 537.6109,-158.7233 602.3594,-140.5268"/>
<polygon fill="#000000" stroke="#000000" points="603.586,-143.8196 612.3006,-137.7942 601.7306,-137.0699 603.586,-143.8196"/>
<text text-anchor="middle" x="462.8414" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- sample -->
<g id="node4" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1408.3414,-639.5C1408.3414,-639.5 1722.3414,-639.5 1722.3414,-639.5 1728.3414,-639.5 1734.3414,-645.5 1734.3414,-651.5 1734.3414,-651.5 1734.3414,-949.5 1734.3414,-949.5 1734.3414,-955.5 1728.3414,-961.5 1722.3414,-961.5 1722.3414,-961.5 1408.3414,-961.5 1408.3414,-961.5 1402.3414,-961.5 1396.3414,-955.5 1396.3414,-949.5 1396.3414,-949.5 1396.3414,-651.5 1396.3414,-651.5 1396.3414,-645.5 1402.3414,-639.5 1408.3414,-639.5"/>
<text text-anchor="middle" x="1430.3414" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1464.3414,-639.5 1464.3414,-961.5 "/>
<text text-anchor="middle" x="1474.8414" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1485.3414,-639.5 1485.3414,-961.5 "/>
<text text-anchor="middle" x="1599.3414" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1485.3414,-938.5 1713.3414,-938.5 "/>
<text text-anchor="middle" x="1599.3414" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1485.3414,-915.5 1713.3414,-915.5 "/>
<text text-anchor="middle" x="1599.3414" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1485.3414,-892.5 1713.3414,-892.5 "/>
<text text-anchor="middle" x="1599.3414" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1485.3414,-869.5 1713.3414,-869.5 "/>
<text text-anchor="middle" x="1599.3414" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1485.3414,-846.5 1713.3414,-846.5 "/>
<text text-anchor="middle" x="1599.3414" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="1485.3414,-823.5 1713.3414,-823.5 "/>
<text text-anchor="middle" x="1599.3414" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1485.3414,-800.5 1713.3414,-800.5 "/>
<text text-anchor="middle" x="1599.3414" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="1485.3414,-777.5 1713.3414,-777.5 "/>
<text text-anchor="middle" x="1599.3414" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="1485.3414,-754.5 1713.3414,-754.5 "/>
<text text-anchor="middle" x="1599.3414" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage</text>
<polyline fill="none" stroke="#000000" points="1485.3414,-731.5 1713.3414,-731.5 "/>
<text text-anchor="middle" x="1599.3414" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1485.3414,-708.5 1713.3414,-708.5 "/>
<text text-anchor="middle" x="1599.3414" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1485.3414,-685.5 1713.3414,-685.5 "/>
<text text-anchor="middle" x="1599.3414" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1485.3414,-662.5 1713.3414,-662.5 "/>
<text text-anchor="middle" x="1599.3414" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_status</text>
<polyline fill="none" stroke="#000000" points="1713.3414,-639.5 1713.3414,-961.5 "/>
<text text-anchor="middle" x="1723.8414" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge18" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1684.3007,-639.1621C1720.6152,-580.6946 1755.8241,-512.199 1774.3414,-444 1795.8861,-364.6507 1827.6209,-321.6242 1774.3414,-259 1727.0419,-203.4047 1303.6653,-151.8452 1036.7419,-124.4734"/>
<polygon fill="#000000" stroke="#000000" points="1036.8279,-120.9641 1026.5239,-123.4296 1036.1164,-127.9278 1036.8279,-120.9641"/>
<text text-anchor="middle" x="1803.8414" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1396.2297,-642.8303C1393.6133,-641.5023 1390.9834,-640.2242 1388.3414,-639 1262.7412,-580.8002 873.3391,-555.9292 663.1787,-546.5177"/>
<polygon fill="#000000" stroke="#000000" points="663.1443,-543.0129 652.9994,-546.0677 662.835,-550.006 663.1443,-543.0129"/>
<text text-anchor="middle" x="1372.8414" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- methylation_array_file -->
<g id="node5" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M1774.3414,-1174.5C1774.3414,-1174.5 2120.3414,-1174.5 2120.3414,-1174.5 2126.3414,-1174.5 2132.3414,-1180.5 2132.3414,-1186.5 2132.3414,-1186.5 2132.3414,-1392.5 2132.3414,-1392.5 2132.3414,-1398.5 2126.3414,-1404.5 2120.3414,-1404.5 2120.3414,-1404.5 1774.3414,-1404.5 1774.3414,-1404.5 1768.3414,-1404.5 1762.3414,-1398.5 1762.3414,-1392.5 1762.3414,-1392.5 1762.3414,-1186.5 1762.3414,-1186.5 1762.3414,-1180.5 1768.3414,-1174.5 1774.3414,-1174.5"/>
<text text-anchor="middle" x="1851.3414" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="1940.3414,-1174.5 1940.3414,-1404.5 "/>
<text text-anchor="middle" x="1950.8414" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1961.3414,-1174.5 1961.3414,-1404.5 "/>
<text text-anchor="middle" x="2036.3414" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1961.3414,-1381.5 2111.3414,-1381.5 "/>
<text text-anchor="middle" x="2036.3414" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1961.3414,-1358.5 2111.3414,-1358.5 "/>
<text text-anchor="middle" x="2036.3414" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1961.3414,-1335.5 2111.3414,-1335.5 "/>
<text text-anchor="middle" x="2036.3414" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1961.3414,-1312.5 2111.3414,-1312.5 "/>
<text text-anchor="middle" x="2036.3414" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1961.3414,-1289.5 2111.3414,-1289.5 "/>
<text text-anchor="middle" x="2036.3414" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1961.3414,-1266.5 2111.3414,-1266.5 "/>
<text text-anchor="middle" x="2036.3414" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1961.3414,-1243.5 2111.3414,-1243.5 "/>
<text text-anchor="middle" x="2036.3414" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1961.3414,-1220.5 2111.3414,-1220.5 "/>
<text text-anchor="middle" x="2036.3414" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="1961.3414,-1197.5 2111.3414,-1197.5 "/>
<text text-anchor="middle" x="2036.3414" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="2111.3414,-1174.5 2111.3414,-1404.5 "/>
<text text-anchor="middle" x="2121.8414" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1870.8673,-1174.4034C1836.2445,-1123.9271 1794.0261,-1064.5584 1753.3414,-1013 1742.0776,-998.7258 1730.1532,-984.1498 1717.993,-969.6558"/>
<polygon fill="#000000" stroke="#000000" points="1720.3365,-967.0054 1711.2157,-961.6144 1714.984,-971.5165 1720.3365,-967.0054"/>
<text text-anchor="middle" x="1824.8414" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- imaging_file -->
<g id="node6" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M1398.3414,-1128.5C1398.3414,-1128.5 1732.3414,-1128.5 1732.3414,-1128.5 1738.3414,-1128.5 1744.3414,-1134.5 1744.3414,-1140.5 1744.3414,-1140.5 1744.3414,-1438.5 1744.3414,-1438.5 1744.3414,-1444.5 1738.3414,-1450.5 1732.3414,-1450.5 1732.3414,-1450.5 1398.3414,-1450.5 1398.3414,-1450.5 1392.3414,-1450.5 1386.3414,-1444.5 1386.3414,-1438.5 1386.3414,-1438.5 1386.3414,-1140.5 1386.3414,-1140.5 1386.3414,-1134.5 1392.3414,-1128.5 1398.3414,-1128.5"/>
<text text-anchor="middle" x="1438.3414" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="1490.3414,-1128.5 1490.3414,-1450.5 "/>
<text text-anchor="middle" x="1500.8414" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1511.3414,-1128.5 1511.3414,-1450.5 "/>
<text text-anchor="middle" x="1617.3414" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1511.3414,-1427.5 1723.3414,-1427.5 "/>
<text text-anchor="middle" x="1617.3414" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1511.3414,-1404.5 1723.3414,-1404.5 "/>
<text text-anchor="middle" x="1617.3414" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1511.3414,-1381.5 1723.3414,-1381.5 "/>
<text text-anchor="middle" x="1617.3414" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1511.3414,-1358.5 1723.3414,-1358.5 "/>
<text text-anchor="middle" x="1617.3414" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1511.3414,-1335.5 1723.3414,-1335.5 "/>
<text text-anchor="middle" x="1617.3414" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1511.3414,-1312.5 1723.3414,-1312.5 "/>
<text text-anchor="middle" x="1617.3414" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1511.3414,-1289.5 1723.3414,-1289.5 "/>
<text text-anchor="middle" x="1617.3414" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1511.3414,-1266.5 1723.3414,-1266.5 "/>
<text text-anchor="middle" x="1617.3414" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1511.3414,-1243.5 1723.3414,-1243.5 "/>
<text text-anchor="middle" x="1617.3414" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="1511.3414,-1220.5 1723.3414,-1220.5 "/>
<text text-anchor="middle" x="1617.3414" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="1511.3414,-1197.5 1723.3414,-1197.5 "/>
<text text-anchor="middle" x="1617.3414" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="1511.3414,-1174.5 1723.3414,-1174.5 "/>
<text text-anchor="middle" x="1617.3414" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1511.3414,-1151.5 1723.3414,-1151.5 "/>
<text text-anchor="middle" x="1617.3414" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="1723.3414,-1128.5 1723.3414,-1450.5 "/>
<text text-anchor="middle" x="1733.8414" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1565.3414,-1128.3669C1565.3414,-1078.1459 1565.3414,-1022.594 1565.3414,-971.7088"/>
<polygon fill="#000000" stroke="#000000" points="1568.8415,-971.5969 1565.3414,-961.597 1561.8415,-971.597 1568.8415,-971.5969"/>
<text text-anchor="middle" x="1619.8414" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- study_admin -->
<g id="node7" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M656.3414,-259.5C656.3414,-259.5 982.3414,-259.5 982.3414,-259.5 988.3414,-259.5 994.3414,-265.5 994.3414,-271.5 994.3414,-271.5 994.3414,-431.5 994.3414,-431.5 994.3414,-437.5 988.3414,-443.5 982.3414,-443.5 982.3414,-443.5 656.3414,-443.5 656.3414,-443.5 650.3414,-443.5 644.3414,-437.5 644.3414,-431.5 644.3414,-431.5 644.3414,-271.5 644.3414,-271.5 644.3414,-265.5 650.3414,-259.5 656.3414,-259.5"/>
<text text-anchor="middle" x="698.3414" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="752.3414,-259.5 752.3414,-443.5 "/>
<text text-anchor="middle" x="762.8414" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="773.3414,-259.5 773.3414,-443.5 "/>
<text text-anchor="middle" x="873.3414" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="773.3414,-420.5 973.3414,-420.5 "/>
<text text-anchor="middle" x="873.3414" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="773.3414,-397.5 973.3414,-397.5 "/>
<text text-anchor="middle" x="873.3414" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="773.3414,-374.5 973.3414,-374.5 "/>
<text text-anchor="middle" x="873.3414" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="773.3414,-351.5 973.3414,-351.5 "/>
<text text-anchor="middle" x="873.3414" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="773.3414,-328.5 973.3414,-328.5 "/>
<text text-anchor="middle" x="873.3414" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="773.3414,-305.5 973.3414,-305.5 "/>
<text text-anchor="middle" x="873.3414" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="773.3414,-282.5 973.3414,-282.5 "/>
<text text-anchor="middle" x="873.3414" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="973.3414,-259.5 973.3414,-443.5 "/>
<text text-anchor="middle" x="983.8414" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge14" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M819.3414,-259.3401C819.3414,-245.8477 819.3414,-231.8183 819.3414,-217.9539"/>
<polygon fill="#000000" stroke="#000000" points="822.8415,-217.8977 819.3414,-207.8977 815.8415,-217.8977 822.8415,-217.8977"/>
<text text-anchor="middle" x="875.8414" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- study_funding -->
<g id="node9" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M1024.8414,-317C1024.8414,-317 1403.8414,-317 1403.8414,-317 1409.8414,-317 1415.8414,-323 1415.8414,-329 1415.8414,-329 1415.8414,-374 1415.8414,-374 1415.8414,-380 1409.8414,-386 1403.8414,-386 1403.8414,-386 1024.8414,-386 1024.8414,-386 1018.8414,-386 1012.8414,-380 1012.8414,-374 1012.8414,-374 1012.8414,-329 1012.8414,-329 1012.8414,-323 1018.8414,-317 1024.8414,-317"/>
<text text-anchor="middle" x="1072.3414" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="1131.8414,-317 1131.8414,-386 "/>
<text text-anchor="middle" x="1142.3414" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1152.8414,-317 1152.8414,-386 "/>
<text text-anchor="middle" x="1273.8414" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="1152.8414,-363 1394.8414,-363 "/>
<text text-anchor="middle" x="1273.8414" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="1152.8414,-340 1394.8414,-340 "/>
<text text-anchor="middle" x="1273.8414" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="1394.8414,-317 1394.8414,-386 "/>
<text text-anchor="middle" x="1405.3414" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge4" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1159.0024,-316.8256C1115.7962,-289.7534 1053.2804,-250.582 993.6289,-213.2055"/>
<polygon fill="#000000" stroke="#000000" points="995.1837,-210.0494 984.8513,-207.7056 991.4669,-215.9812 995.1837,-210.0494"/>
<text text-anchor="middle" x="1090.3414" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- study_personnel -->
<g id="node10" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M1445.8414,-294C1445.8414,-294 1752.8414,-294 1752.8414,-294 1758.8414,-294 1764.8414,-300 1764.8414,-306 1764.8414,-306 1764.8414,-397 1764.8414,-397 1764.8414,-403 1758.8414,-409 1752.8414,-409 1752.8414,-409 1445.8414,-409 1445.8414,-409 1439.8414,-409 1433.8414,-403 1433.8414,-397 1433.8414,-397 1433.8414,-306 1433.8414,-306 1433.8414,-300 1439.8414,-294 1445.8414,-294"/>
<text text-anchor="middle" x="1500.8414" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="1567.8414,-294 1567.8414,-409 "/>
<text text-anchor="middle" x="1578.3414" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1588.8414,-294 1588.8414,-409 "/>
<text text-anchor="middle" x="1666.3414" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="1588.8414,-386 1743.8414,-386 "/>
<text text-anchor="middle" x="1666.3414" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="1588.8414,-363 1743.8414,-363 "/>
<text text-anchor="middle" x="1666.3414" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="1588.8414,-340 1743.8414,-340 "/>
<text text-anchor="middle" x="1666.3414" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="1588.8414,-317 1743.8414,-317 "/>
<text text-anchor="middle" x="1666.3414" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="1743.8414,-294 1743.8414,-409 "/>
<text text-anchor="middle" x="1754.3414" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge19" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1500.9689,-293.9884C1476.7624,-281.3066 1450.5443,-268.7611 1425.3414,-259 1299.7583,-210.3616 1153.6367,-172.4729 1036.3461,-146.3329"/>
<polygon fill="#000000" stroke="#000000" points="1037.044,-142.9028 1026.5236,-144.1563 1035.5295,-149.737 1037.044,-142.9028"/>
<text text-anchor="middle" x="1430.8414" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- synonym -->
<g id="node11" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M318.8414,-1243.5C318.8414,-1243.5 619.8414,-1243.5 619.8414,-1243.5 625.8414,-1243.5 631.8414,-1249.5 631.8414,-1255.5 631.8414,-1255.5 631.8414,-1323.5 631.8414,-1323.5 631.8414,-1329.5 625.8414,-1335.5 619.8414,-1335.5 619.8414,-1335.5 318.8414,-1335.5 318.8414,-1335.5 312.8414,-1335.5 306.8414,-1329.5 306.8414,-1323.5 306.8414,-1323.5 306.8414,-1255.5 306.8414,-1255.5 306.8414,-1249.5 312.8414,-1243.5 318.8414,-1243.5"/>
<text text-anchor="middle" x="346.8414" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="386.8414,-1243.5 386.8414,-1335.5 "/>
<text text-anchor="middle" x="397.3414" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="407.8414,-1243.5 407.8414,-1335.5 "/>
<text text-anchor="middle" x="509.3414" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_id</text>
<polyline fill="none" stroke="#000000" points="407.8414,-1312.5 610.8414,-1312.5 "/>
<text text-anchor="middle" x="509.3414" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_node</text>
<polyline fill="none" stroke="#000000" points="407.8414,-1289.5 610.8414,-1289.5 "/>
<text text-anchor="middle" x="509.3414" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="407.8414,-1266.5 610.8414,-1266.5 "/>
<text text-anchor="middle" x="509.3414" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="610.8414,-1243.5 610.8414,-1335.5 "/>
<text text-anchor="middle" x="621.3414" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M517.4878,-1243.3367C587.7601,-1179.1199 725.4551,-1064.8868 866.3414,-1013 918.7304,-993.7057 1300.9533,-986.3093 1386.7601,-961.6326"/>
<polygon fill="#000000" stroke="#000000" points="1388.0088,-964.9037 1396.2823,-958.2856 1385.6875,-958.2998 1388.0088,-964.9037"/>
<text text-anchor="middle" x="1291.8414" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge12" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M363.7993,-1243.3752C258.4747,-1191.3231 101.4047,-1096.0729 23.3414,-962 -13.0241,-899.5427 4.3414,-872.7728 4.3414,-800.5 4.3414,-800.5 4.3414,-800.5 4.3414,-351.5 4.3414,-226.3409 360.6953,-158.4853 602.1292,-126.8752"/>
<polygon fill="#000000" stroke="#000000" points="602.6349,-130.339 612.1015,-125.5815 601.7343,-123.3971 602.6349,-130.339"/>
<text text-anchor="middle" x="46.8414" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M463.2438,-1243.3242C450.4713,-1135.6429 426.1876,-860.2373 478.3414,-639 481.7044,-624.7339 487.3813,-610.1099 493.6499,-596.6704"/>
<polygon fill="#000000" stroke="#000000" points="496.8468,-598.0992 498.063,-587.5743 490.5489,-595.0436 496.8468,-598.0992"/>
<text text-anchor="middle" x="520.8414" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge6" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M433.3372,-495.4008C425.1803,-489.7115 417.3656,-483.5647 410.3414,-477 385.3372,-453.6315 364.385,-421.1575 349.9193,-395.0977"/>
<polygon fill="#000000" stroke="#000000" points="352.9225,-393.2936 345.0771,-386.1731 346.7697,-396.6318 352.9225,-393.2936"/>
<text text-anchor="middle" x="460.8414" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge7" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M521.3942,-495.2976C516.3239,-425.5075 510.7544,-297.2766 534.3414,-259 551.7471,-230.7543 576.2325,-207.3006 603.618,-187.9291"/>
<polygon fill="#000000" stroke="#000000" points="605.9328,-190.586 612.2054,-182.0475 601.9772,-184.8107 605.9328,-190.586"/>
<text text-anchor="middle" x="584.8414" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- clinical_measure_file -->
<g id="node13" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M44.3414,-674C44.3414,-674 396.3414,-674 396.3414,-674 402.3414,-674 408.3414,-680 408.3414,-686 408.3414,-686 408.3414,-915 408.3414,-915 408.3414,-921 402.3414,-927 396.3414,-927 396.3414,-927 44.3414,-927 44.3414,-927 38.3414,-927 32.3414,-921 32.3414,-915 32.3414,-915 32.3414,-686 32.3414,-686 32.3414,-680 38.3414,-674 44.3414,-674"/>
<text text-anchor="middle" x="115.8414" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="199.3414,-674 199.3414,-927 "/>
<text text-anchor="middle" x="209.8414" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="220.3414,-674 220.3414,-927 "/>
<text text-anchor="middle" x="303.8414" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="220.3414,-904 387.3414,-904 "/>
<text text-anchor="middle" x="303.8414" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="220.3414,-881 387.3414,-881 "/>
<text text-anchor="middle" x="303.8414" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="220.3414,-858 387.3414,-858 "/>
<text text-anchor="middle" x="303.8414" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="220.3414,-835 387.3414,-835 "/>
<text text-anchor="middle" x="303.8414" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="220.3414,-812 387.3414,-812 "/>
<text text-anchor="middle" x="303.8414" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="220.3414,-789 387.3414,-789 "/>
<text text-anchor="middle" x="303.8414" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="220.3414,-766 387.3414,-766 "/>
<text text-anchor="middle" x="303.8414" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="220.3414,-743 387.3414,-743 "/>
<text text-anchor="middle" x="303.8414" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="220.3414,-720 387.3414,-720 "/>
<text text-anchor="middle" x="303.8414" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="220.3414,-697 387.3414,-697 "/>
<text text-anchor="middle" x="303.8414" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="387.3414,-674 387.3414,-927 "/>
<text text-anchor="middle" x="397.8414" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge15" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M158.8674,-673.8492C110.641,-554.1246 65.6929,-375.8871 158.3414,-259 213.3032,-189.6591 431.1418,-148.3394 601.9117,-126.0232"/>
<polygon fill="#000000" stroke="#000000" points="602.5903,-129.4647 612.0593,-124.7121 601.6933,-122.5224 602.5903,-129.4647"/>
<text text-anchor="middle" x="193.3414" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M176.8877,-673.8263C175.7282,-649.2336 180.5584,-625.1776 196.3414,-606 220.9487,-576.1 308.8563,-559.8569 387.6143,-551.1516"/>
<polygon fill="#000000" stroke="#000000" points="388.0933,-554.6205 397.6638,-550.0756 387.348,-547.6602 388.0933,-554.6205"/>
<text text-anchor="middle" x="325.8414" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- sequencing_file -->
<g id="node14" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M886.8414,-1013.5C886.8414,-1013.5 1355.8414,-1013.5 1355.8414,-1013.5 1361.8414,-1013.5 1367.8414,-1019.5 1367.8414,-1025.5 1367.8414,-1025.5 1367.8414,-1553.5 1367.8414,-1553.5 1367.8414,-1559.5 1361.8414,-1565.5 1355.8414,-1565.5 1355.8414,-1565.5 886.8414,-1565.5 886.8414,-1565.5 880.8414,-1565.5 874.8414,-1559.5 874.8414,-1553.5 874.8414,-1553.5 874.8414,-1025.5 874.8414,-1025.5 874.8414,-1019.5 880.8414,-1013.5 886.8414,-1013.5"/>
<text text-anchor="middle" x="938.8414" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="1002.8414,-1013.5 1002.8414,-1565.5 "/>
<text text-anchor="middle" x="1013.3414" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1023.8414,-1013.5 1023.8414,-1565.5 "/>
<text text-anchor="middle" x="1185.3414" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="1023.8414,-1542.5 1346.8414,-1542.5 "/>
<text text-anchor="middle" x="1185.3414" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1023.8414,-1519.5 1346.8414,-1519.5 "/>
<text text-anchor="middle" x="1185.3414" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1023.8414,-1496.5 1346.8414,-1496.5 "/>
<text text-anchor="middle" x="1185.3414" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="1023.8414,-1473.5 1346.8414,-1473.5 "/>
<text text-anchor="middle" x="1185.3414" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="1023.8414,-1450.5 1346.8414,-1450.5 "/>
<text text-anchor="middle" x="1185.3414" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1023.8414,-1427.5 1346.8414,-1427.5 "/>
<text text-anchor="middle" x="1185.3414" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1023.8414,-1404.5 1346.8414,-1404.5 "/>
<text text-anchor="middle" x="1185.3414" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1023.8414,-1381.5 1346.8414,-1381.5 "/>
<text text-anchor="middle" x="1185.3414" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1023.8414,-1358.5 1346.8414,-1358.5 "/>
<text text-anchor="middle" x="1185.3414" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1023.8414,-1335.5 1346.8414,-1335.5 "/>
<text text-anchor="middle" x="1185.3414" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1023.8414,-1312.5 1346.8414,-1312.5 "/>
<text text-anchor="middle" x="1185.3414" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1023.8414,-1289.5 1346.8414,-1289.5 "/>
<text text-anchor="middle" x="1185.3414" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="1023.8414,-1266.5 1346.8414,-1266.5 "/>
<text text-anchor="middle" x="1185.3414" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="1023.8414,-1243.5 1346.8414,-1243.5 "/>
<text text-anchor="middle" x="1185.3414" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="1023.8414,-1220.5 1346.8414,-1220.5 "/>
<text text-anchor="middle" x="1185.3414" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="1023.8414,-1197.5 1346.8414,-1197.5 "/>
<text text-anchor="middle" x="1185.3414" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="1023.8414,-1174.5 1346.8414,-1174.5 "/>
<text text-anchor="middle" x="1185.3414" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="1023.8414,-1151.5 1346.8414,-1151.5 "/>
<text text-anchor="middle" x="1185.3414" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1023.8414,-1128.5 1346.8414,-1128.5 "/>
<text text-anchor="middle" x="1185.3414" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="1023.8414,-1105.5 1346.8414,-1105.5 "/>
<text text-anchor="middle" x="1185.3414" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="1023.8414,-1082.5 1346.8414,-1082.5 "/>
<text text-anchor="middle" x="1185.3414" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="1023.8414,-1059.5 1346.8414,-1059.5 "/>
<text text-anchor="middle" x="1185.3414" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="1023.8414,-1036.5 1346.8414,-1036.5 "/>
<text text-anchor="middle" x="1185.3414" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="1346.8414,-1013.5 1346.8414,-1565.5 "/>
<text text-anchor="middle" x="1357.3414" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1368.0108,-1017.8303C1382.9341,-1001.3945 1397.7068,-985.1245 1412.0548,-969.3224"/>
<polygon fill="#000000" stroke="#000000" points="1414.9319,-971.3603 1419.0629,-961.6039 1409.7495,-966.6547 1414.9319,-971.3603"/>
<text text-anchor="middle" x="1461.8414" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- publication -->
<g id="node15" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M1833.3414,-333.5C1833.3414,-333.5 2043.3414,-333.5 2043.3414,-333.5 2049.3414,-333.5 2055.3414,-339.5 2055.3414,-345.5 2055.3414,-345.5 2055.3414,-357.5 2055.3414,-357.5 2055.3414,-363.5 2049.3414,-369.5 2043.3414,-369.5 2043.3414,-369.5 1833.3414,-369.5 1833.3414,-369.5 1827.3414,-369.5 1821.3414,-363.5 1821.3414,-357.5 1821.3414,-357.5 1821.3414,-345.5 1821.3414,-345.5 1821.3414,-339.5 1827.3414,-333.5 1833.3414,-333.5"/>
<text text-anchor="middle" x="1869.8414" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="1918.3414,-333.5 1918.3414,-369.5 "/>
<text text-anchor="middle" x="1928.8414" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1939.3414,-333.5 1939.3414,-369.5 "/>
<text text-anchor="middle" x="1986.8414" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="2034.3414,-333.5 2034.3414,-369.5 "/>
<text text-anchor="middle" x="2044.8414" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge5" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1925.5056,-333.2024C1904.4617,-304.8187 1859.689,-250.8626 1807.3414,-226 1675.109,-163.1959 1285.2531,-130.0885 1036.6281,-114.8764"/>
<polygon fill="#000000" stroke="#000000" points="1036.5654,-111.3662 1026.3717,-114.2541 1036.1414,-118.3534 1036.5654,-111.3662"/>
<text text-anchor="middle" x="1883.3414" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
</g>
</svg>
</div>
