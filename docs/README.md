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
<svg width="2144pt" height="1528pt"
 viewBox="0.00 0.00 2143.84 1528.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1524)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1524 2139.8403,-1524 2139.8403,4 -4,4"/>
<!-- study -->
<g id="node1" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M588.8403,-.5C588.8403,-.5 978.8403,-.5 978.8403,-.5 984.8403,-.5 990.8403,-6.5 990.8403,-12.5 990.8403,-12.5 990.8403,-195.5 990.8403,-195.5 990.8403,-201.5 984.8403,-207.5 978.8403,-207.5 978.8403,-207.5 588.8403,-207.5 588.8403,-207.5 582.8403,-207.5 576.8403,-201.5 576.8403,-195.5 576.8403,-195.5 576.8403,-12.5 576.8403,-12.5 576.8403,-6.5 582.8403,-.5 588.8403,-.5"/>
<text text-anchor="middle" x="604.8403" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="632.8403,-.5 632.8403,-207.5 "/>
<text text-anchor="middle" x="643.3403" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="653.8403,-.5 653.8403,-207.5 "/>
<text text-anchor="middle" x="811.8403" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="653.8403,-184.5 969.8403,-184.5 "/>
<text text-anchor="middle" x="811.8403" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="653.8403,-161.5 969.8403,-161.5 "/>
<text text-anchor="middle" x="811.8403" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="653.8403,-138.5 969.8403,-138.5 "/>
<text text-anchor="middle" x="811.8403" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="653.8403,-115.5 969.8403,-115.5 "/>
<text text-anchor="middle" x="811.8403" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="653.8403,-92.5 969.8403,-92.5 "/>
<text text-anchor="middle" x="811.8403" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="653.8403,-69.5 969.8403,-69.5 "/>
<text text-anchor="middle" x="811.8403" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="653.8403,-46.5 969.8403,-46.5 "/>
<text text-anchor="middle" x="811.8403" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="653.8403,-23.5 969.8403,-23.5 "/>
<text text-anchor="middle" x="811.8403" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="969.8403,-.5 969.8403,-207.5 "/>
<text text-anchor="middle" x="980.3403" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file -->
<g id="node2" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M1446.3403,-1105.5C1446.3403,-1105.5 1735.3403,-1105.5 1735.3403,-1105.5 1741.3403,-1105.5 1747.3403,-1111.5 1747.3403,-1117.5 1747.3403,-1117.5 1747.3403,-1415.5 1747.3403,-1415.5 1747.3403,-1421.5 1741.3403,-1427.5 1735.3403,-1427.5 1735.3403,-1427.5 1446.3403,-1427.5 1446.3403,-1427.5 1440.3403,-1427.5 1434.3403,-1421.5 1434.3403,-1415.5 1434.3403,-1415.5 1434.3403,-1117.5 1434.3403,-1117.5 1434.3403,-1111.5 1440.3403,-1105.5 1446.3403,-1105.5"/>
<text text-anchor="middle" x="1486.3403" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="1538.3403,-1105.5 1538.3403,-1427.5 "/>
<text text-anchor="middle" x="1548.8403" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1559.3403,-1105.5 1559.3403,-1427.5 "/>
<text text-anchor="middle" x="1642.8403" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1559.3403,-1404.5 1726.3403,-1404.5 "/>
<text text-anchor="middle" x="1642.8403" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1559.3403,-1381.5 1726.3403,-1381.5 "/>
<text text-anchor="middle" x="1642.8403" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1559.3403,-1358.5 1726.3403,-1358.5 "/>
<text text-anchor="middle" x="1642.8403" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1559.3403,-1335.5 1726.3403,-1335.5 "/>
<text text-anchor="middle" x="1642.8403" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1559.3403,-1312.5 1726.3403,-1312.5 "/>
<text text-anchor="middle" x="1642.8403" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1559.3403,-1289.5 1726.3403,-1289.5 "/>
<text text-anchor="middle" x="1642.8403" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1559.3403,-1266.5 1726.3403,-1266.5 "/>
<text text-anchor="middle" x="1642.8403" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1559.3403,-1243.5 1726.3403,-1243.5 "/>
<text text-anchor="middle" x="1642.8403" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1559.3403,-1220.5 1726.3403,-1220.5 "/>
<text text-anchor="middle" x="1642.8403" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="1559.3403,-1197.5 1726.3403,-1197.5 "/>
<text text-anchor="middle" x="1642.8403" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="1559.3403,-1174.5 1726.3403,-1174.5 "/>
<text text-anchor="middle" x="1642.8403" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="1559.3403,-1151.5 1726.3403,-1151.5 "/>
<text text-anchor="middle" x="1642.8403" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1559.3403,-1128.5 1726.3403,-1128.5 "/>
<text text-anchor="middle" x="1642.8403" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="1726.3403,-1105.5 1726.3403,-1427.5 "/>
<text text-anchor="middle" x="1736.8403" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node9" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1433.8403,-639.5C1433.8403,-639.5 1747.8403,-639.5 1747.8403,-639.5 1753.8403,-639.5 1759.8403,-645.5 1759.8403,-651.5 1759.8403,-651.5 1759.8403,-949.5 1759.8403,-949.5 1759.8403,-955.5 1753.8403,-961.5 1747.8403,-961.5 1747.8403,-961.5 1433.8403,-961.5 1433.8403,-961.5 1427.8403,-961.5 1421.8403,-955.5 1421.8403,-949.5 1421.8403,-949.5 1421.8403,-651.5 1421.8403,-651.5 1421.8403,-645.5 1427.8403,-639.5 1433.8403,-639.5"/>
<text text-anchor="middle" x="1455.8403" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1489.8403,-639.5 1489.8403,-961.5 "/>
<text text-anchor="middle" x="1500.3403" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1510.8403,-639.5 1510.8403,-961.5 "/>
<text text-anchor="middle" x="1624.8403" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1510.8403,-938.5 1738.8403,-938.5 "/>
<text text-anchor="middle" x="1624.8403" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1510.8403,-915.5 1738.8403,-915.5 "/>
<text text-anchor="middle" x="1624.8403" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1510.8403,-892.5 1738.8403,-892.5 "/>
<text text-anchor="middle" x="1624.8403" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1510.8403,-869.5 1738.8403,-869.5 "/>
<text text-anchor="middle" x="1624.8403" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1510.8403,-846.5 1738.8403,-846.5 "/>
<text text-anchor="middle" x="1624.8403" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="1510.8403,-823.5 1738.8403,-823.5 "/>
<text text-anchor="middle" x="1624.8403" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1510.8403,-800.5 1738.8403,-800.5 "/>
<text text-anchor="middle" x="1624.8403" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="1510.8403,-777.5 1738.8403,-777.5 "/>
<text text-anchor="middle" x="1624.8403" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="1510.8403,-754.5 1738.8403,-754.5 "/>
<text text-anchor="middle" x="1624.8403" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage</text>
<polyline fill="none" stroke="#000000" points="1510.8403,-731.5 1738.8403,-731.5 "/>
<text text-anchor="middle" x="1624.8403" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1510.8403,-708.5 1738.8403,-708.5 "/>
<text text-anchor="middle" x="1624.8403" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1510.8403,-685.5 1738.8403,-685.5 "/>
<text text-anchor="middle" x="1624.8403" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1510.8403,-662.5 1738.8403,-662.5 "/>
<text text-anchor="middle" x="1624.8403" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_status</text>
<polyline fill="none" stroke="#000000" points="1738.8403,-639.5 1738.8403,-961.5 "/>
<text text-anchor="middle" x="1749.3403" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1590.8403,-1105.4767C1590.8403,-1062.2772 1590.8403,-1015.4171 1590.8403,-971.6882"/>
<polygon fill="#000000" stroke="#000000" points="1594.3404,-971.5296 1590.8403,-961.5297 1587.3404,-971.5297 1594.3404,-971.5296"/>
<text text-anchor="middle" x="1645.3403" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- study_arm -->
<g id="node3" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M915.3403,-317C915.3403,-317 1212.3403,-317 1212.3403,-317 1218.3403,-317 1224.3403,-323 1224.3403,-329 1224.3403,-329 1224.3403,-374 1224.3403,-374 1224.3403,-380 1218.3403,-386 1212.3403,-386 1212.3403,-386 915.3403,-386 915.3403,-386 909.3403,-386 903.3403,-380 903.3403,-374 903.3403,-374 903.3403,-329 903.3403,-329 903.3403,-323 909.3403,-317 915.3403,-317"/>
<text text-anchor="middle" x="949.3403" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="995.3403,-317 995.3403,-386 "/>
<text text-anchor="middle" x="1005.8403" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1016.3403,-317 1016.3403,-386 "/>
<text text-anchor="middle" x="1109.8403" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="1016.3403,-363 1203.3403,-363 "/>
<text text-anchor="middle" x="1109.8403" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="1016.3403,-340 1203.3403,-340 "/>
<text text-anchor="middle" x="1109.8403" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="1203.3403,-317 1203.3403,-386 "/>
<text text-anchor="middle" x="1213.8403" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge4" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1024.6126,-316.8256C994.2993,-290.0308 950.5771,-251.3835 908.6862,-214.3549"/>
<polygon fill="#000000" stroke="#000000" points="910.9743,-211.7061 901.1638,-207.7056 906.3383,-216.9509 910.9743,-211.7061"/>
<text text-anchor="middle" x="981.3403" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- participant -->
<g id="node4" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M686.3403,-495.5C686.3403,-495.5 917.3403,-495.5 917.3403,-495.5 923.3403,-495.5 929.3403,-501.5 929.3403,-507.5 929.3403,-507.5 929.3403,-575.5 929.3403,-575.5 929.3403,-581.5 923.3403,-587.5 917.3403,-587.5 917.3403,-587.5 686.3403,-587.5 686.3403,-587.5 680.3403,-587.5 674.3403,-581.5 674.3403,-575.5 674.3403,-575.5 674.3403,-507.5 674.3403,-507.5 674.3403,-501.5 680.3403,-495.5 686.3403,-495.5"/>
<text text-anchor="middle" x="722.3403" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="770.3403,-495.5 770.3403,-587.5 "/>
<text text-anchor="middle" x="780.8403" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="791.3403,-495.5 791.3403,-587.5 "/>
<text text-anchor="middle" x="849.8403" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="791.3403,-564.5 908.3403,-564.5 "/>
<text text-anchor="middle" x="849.8403" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="791.3403,-541.5 908.3403,-541.5 "/>
<text text-anchor="middle" x="849.8403" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="791.3403,-518.5 908.3403,-518.5 "/>
<text text-anchor="middle" x="849.8403" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="908.3403,-495.5 908.3403,-587.5 "/>
<text text-anchor="middle" x="918.8403" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge10" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M796.9617,-495.4217C795.4087,-479.1869 793.8369,-460.7995 792.8403,-444 788.3749,-368.7305 786.125,-283.9559 784.9914,-217.8863"/>
<polygon fill="#000000" stroke="#000000" points="788.4906,-217.8037 784.8254,-207.8631 781.4915,-217.9197 788.4906,-217.8037"/>
<text text-anchor="middle" x="843.3403" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge9" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M865.5977,-495.2637C909.0506,-463.752 966.0461,-422.4194 1007.7667,-392.1641"/>
<polygon fill="#000000" stroke="#000000" points="1009.8579,-394.971 1015.8986,-386.2669 1005.7484,-389.3042 1009.8579,-394.971"/>
<text text-anchor="middle" x="960.3403" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- diagnosis -->
<g id="node5" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M610.3403,-651C610.3403,-651 993.3403,-651 993.3403,-651 999.3403,-651 1005.3403,-657 1005.3403,-663 1005.3403,-663 1005.3403,-938 1005.3403,-938 1005.3403,-944 999.3403,-950 993.3403,-950 993.3403,-950 610.3403,-950 610.3403,-950 604.3403,-950 598.3403,-944 598.3403,-938 598.3403,-938 598.3403,-663 598.3403,-663 598.3403,-657 604.3403,-651 610.3403,-651"/>
<text text-anchor="middle" x="640.3403" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="682.3403,-651 682.3403,-950 "/>
<text text-anchor="middle" x="692.8403" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="703.3403,-651 703.3403,-950 "/>
<text text-anchor="middle" x="843.8403" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="703.3403,-927 984.3403,-927 "/>
<text text-anchor="middle" x="843.8403" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="703.3403,-904 984.3403,-904 "/>
<text text-anchor="middle" x="843.8403" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="703.3403,-881 984.3403,-881 "/>
<text text-anchor="middle" x="843.8403" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="703.3403,-858 984.3403,-858 "/>
<text text-anchor="middle" x="843.8403" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="703.3403,-835 984.3403,-835 "/>
<text text-anchor="middle" x="843.8403" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="703.3403,-812 984.3403,-812 "/>
<text text-anchor="middle" x="843.8403" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="703.3403,-789 984.3403,-789 "/>
<text text-anchor="middle" x="843.8403" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="703.3403,-766 984.3403,-766 "/>
<text text-anchor="middle" x="843.8403" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis_reference_source</text>
<polyline fill="none" stroke="#000000" points="703.3403,-743 984.3403,-743 "/>
<text text-anchor="middle" x="843.8403" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="703.3403,-720 984.3403,-720 "/>
<text text-anchor="middle" x="843.8403" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="703.3403,-697 984.3403,-697 "/>
<text text-anchor="middle" x="843.8403" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="703.3403,-674 984.3403,-674 "/>
<text text-anchor="middle" x="843.8403" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="984.3403,-651 984.3403,-950 "/>
<text text-anchor="middle" x="994.8403" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M801.8403,-650.9639C801.8403,-632.1028 801.8403,-613.8228 801.8403,-597.7769"/>
<polygon fill="#000000" stroke="#000000" points="805.3404,-597.5713 801.8403,-587.5714 798.3404,-597.5714 805.3404,-597.5713"/>
<text text-anchor="middle" x="846.3403" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- methylation_array_file -->
<g id="node6" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M1777.8403,-1151.5C1777.8403,-1151.5 2123.8403,-1151.5 2123.8403,-1151.5 2129.8403,-1151.5 2135.8403,-1157.5 2135.8403,-1163.5 2135.8403,-1163.5 2135.8403,-1369.5 2135.8403,-1369.5 2135.8403,-1375.5 2129.8403,-1381.5 2123.8403,-1381.5 2123.8403,-1381.5 1777.8403,-1381.5 1777.8403,-1381.5 1771.8403,-1381.5 1765.8403,-1375.5 1765.8403,-1369.5 1765.8403,-1369.5 1765.8403,-1163.5 1765.8403,-1163.5 1765.8403,-1157.5 1771.8403,-1151.5 1777.8403,-1151.5"/>
<text text-anchor="middle" x="1854.8403" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="1943.8403,-1151.5 1943.8403,-1381.5 "/>
<text text-anchor="middle" x="1954.3403" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1964.8403,-1151.5 1964.8403,-1381.5 "/>
<text text-anchor="middle" x="2039.8403" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1964.8403,-1358.5 2114.8403,-1358.5 "/>
<text text-anchor="middle" x="2039.8403" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1964.8403,-1335.5 2114.8403,-1335.5 "/>
<text text-anchor="middle" x="2039.8403" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1964.8403,-1312.5 2114.8403,-1312.5 "/>
<text text-anchor="middle" x="2039.8403" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1964.8403,-1289.5 2114.8403,-1289.5 "/>
<text text-anchor="middle" x="2039.8403" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1964.8403,-1266.5 2114.8403,-1266.5 "/>
<text text-anchor="middle" x="2039.8403" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1964.8403,-1243.5 2114.8403,-1243.5 "/>
<text text-anchor="middle" x="2039.8403" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1964.8403,-1220.5 2114.8403,-1220.5 "/>
<text text-anchor="middle" x="2039.8403" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1964.8403,-1197.5 2114.8403,-1197.5 "/>
<text text-anchor="middle" x="2039.8403" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="1964.8403,-1174.5 2114.8403,-1174.5 "/>
<text text-anchor="middle" x="2039.8403" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="2114.8403,-1151.5 2114.8403,-1381.5 "/>
<text text-anchor="middle" x="2125.3403" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1863.1988,-1151.4784C1829.9806,-1108.0142 1791.7562,-1058.1577 1756.8403,-1013 1745.9677,-998.9382 1734.6686,-984.3731 1723.3088,-969.7633"/>
<polygon fill="#000000" stroke="#000000" points="1725.8964,-967.3893 1716.9939,-961.6451 1720.3712,-971.6872 1725.8964,-967.3893"/>
<text text-anchor="middle" x="1830.3403" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study_admin -->
<g id="node7" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M157.8403,-259.5C157.8403,-259.5 483.8403,-259.5 483.8403,-259.5 489.8403,-259.5 495.8403,-265.5 495.8403,-271.5 495.8403,-271.5 495.8403,-431.5 495.8403,-431.5 495.8403,-437.5 489.8403,-443.5 483.8403,-443.5 483.8403,-443.5 157.8403,-443.5 157.8403,-443.5 151.8403,-443.5 145.8403,-437.5 145.8403,-431.5 145.8403,-431.5 145.8403,-271.5 145.8403,-271.5 145.8403,-265.5 151.8403,-259.5 157.8403,-259.5"/>
<text text-anchor="middle" x="199.8403" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="253.8403,-259.5 253.8403,-443.5 "/>
<text text-anchor="middle" x="264.3403" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="274.8403,-259.5 274.8403,-443.5 "/>
<text text-anchor="middle" x="374.8403" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="274.8403,-420.5 474.8403,-420.5 "/>
<text text-anchor="middle" x="374.8403" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="274.8403,-397.5 474.8403,-397.5 "/>
<text text-anchor="middle" x="374.8403" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="274.8403,-374.5 474.8403,-374.5 "/>
<text text-anchor="middle" x="374.8403" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="274.8403,-351.5 474.8403,-351.5 "/>
<text text-anchor="middle" x="374.8403" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="274.8403,-328.5 474.8403,-328.5 "/>
<text text-anchor="middle" x="374.8403" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="274.8403,-305.5 474.8403,-305.5 "/>
<text text-anchor="middle" x="374.8403" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="274.8403,-282.5 474.8403,-282.5 "/>
<text text-anchor="middle" x="374.8403" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="474.8403,-259.5 474.8403,-443.5 "/>
<text text-anchor="middle" x="485.3403" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge18" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M483.4554,-259.4241C504.0527,-248.0472 524.8938,-236.6735 544.8403,-226 553.2238,-221.5139 561.7897,-216.9677 570.4557,-212.3994"/>
<polygon fill="#000000" stroke="#000000" points="572.298,-215.385 579.5193,-207.6324 569.0395,-209.1897 572.298,-215.385"/>
<text text-anchor="middle" x="601.3403" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- publication -->
<g id="node8" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M525.8403,-333.5C525.8403,-333.5 735.8403,-333.5 735.8403,-333.5 741.8403,-333.5 747.8403,-339.5 747.8403,-345.5 747.8403,-345.5 747.8403,-357.5 747.8403,-357.5 747.8403,-363.5 741.8403,-369.5 735.8403,-369.5 735.8403,-369.5 525.8403,-369.5 525.8403,-369.5 519.8403,-369.5 513.8403,-363.5 513.8403,-357.5 513.8403,-357.5 513.8403,-345.5 513.8403,-345.5 513.8403,-339.5 519.8403,-333.5 525.8403,-333.5"/>
<text text-anchor="middle" x="562.3403" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="610.8403,-333.5 610.8403,-369.5 "/>
<text text-anchor="middle" x="621.3403" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="631.8403,-333.5 631.8403,-369.5 "/>
<text text-anchor="middle" x="679.3403" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="726.8403,-333.5 726.8403,-369.5 "/>
<text text-anchor="middle" x="737.3403" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge17" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M633.4228,-333.4005C637.636,-308.0141 647.6289,-261.0194 667.8403,-226 669.7418,-222.7053 671.7498,-219.4303 673.8485,-216.1815"/>
<polygon fill="#000000" stroke="#000000" points="676.9147,-217.8947 679.6052,-207.6472 671.1115,-213.9802 676.9147,-217.8947"/>
<text text-anchor="middle" x="718.8403" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge7" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1610.0209,-639.2298C1622.713,-500.694 1629.5001,-314.7374 1582.8403,-259 1509.719,-171.653 1211.7605,-132.8474 1001.1852,-116.0867"/>
<polygon fill="#000000" stroke="#000000" points="1001.1541,-112.5736 990.911,-115.2809 1000.6066,-119.5522 1001.1541,-112.5736"/>
<text text-anchor="middle" x="1655.3403" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1421.8236,-643.5304C1418.8448,-641.9566 1415.8497,-640.4446 1412.8403,-639 1331.4069,-599.9102 1093.2635,-570.1005 939.4619,-554.2487"/>
<polygon fill="#000000" stroke="#000000" points="939.7601,-550.761 929.4558,-553.2248 939.0475,-557.7246 939.7601,-550.761"/>
<text text-anchor="middle" x="1390.3403" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sequencing_file -->
<g id="node10" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M935.3403,-1013.5C935.3403,-1013.5 1404.3403,-1013.5 1404.3403,-1013.5 1410.3403,-1013.5 1416.3403,-1019.5 1416.3403,-1025.5 1416.3403,-1025.5 1416.3403,-1507.5 1416.3403,-1507.5 1416.3403,-1513.5 1410.3403,-1519.5 1404.3403,-1519.5 1404.3403,-1519.5 935.3403,-1519.5 935.3403,-1519.5 929.3403,-1519.5 923.3403,-1513.5 923.3403,-1507.5 923.3403,-1507.5 923.3403,-1025.5 923.3403,-1025.5 923.3403,-1019.5 929.3403,-1013.5 935.3403,-1013.5"/>
<text text-anchor="middle" x="987.3403" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="1051.3403,-1013.5 1051.3403,-1519.5 "/>
<text text-anchor="middle" x="1061.8403" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1072.3403,-1013.5 1072.3403,-1519.5 "/>
<text text-anchor="middle" x="1233.8403" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="1072.3403,-1496.5 1395.3403,-1496.5 "/>
<text text-anchor="middle" x="1233.8403" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1072.3403,-1473.5 1395.3403,-1473.5 "/>
<text text-anchor="middle" x="1233.8403" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1072.3403,-1450.5 1395.3403,-1450.5 "/>
<text text-anchor="middle" x="1233.8403" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="1072.3403,-1427.5 1395.3403,-1427.5 "/>
<text text-anchor="middle" x="1233.8403" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="1072.3403,-1404.5 1395.3403,-1404.5 "/>
<text text-anchor="middle" x="1233.8403" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1072.3403,-1381.5 1395.3403,-1381.5 "/>
<text text-anchor="middle" x="1233.8403" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1072.3403,-1358.5 1395.3403,-1358.5 "/>
<text text-anchor="middle" x="1233.8403" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1072.3403,-1335.5 1395.3403,-1335.5 "/>
<text text-anchor="middle" x="1233.8403" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1072.3403,-1312.5 1395.3403,-1312.5 "/>
<text text-anchor="middle" x="1233.8403" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1072.3403,-1289.5 1395.3403,-1289.5 "/>
<text text-anchor="middle" x="1233.8403" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1072.3403,-1266.5 1395.3403,-1266.5 "/>
<text text-anchor="middle" x="1233.8403" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1072.3403,-1243.5 1395.3403,-1243.5 "/>
<text text-anchor="middle" x="1233.8403" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="1072.3403,-1220.5 1395.3403,-1220.5 "/>
<text text-anchor="middle" x="1233.8403" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="1072.3403,-1197.5 1395.3403,-1197.5 "/>
<text text-anchor="middle" x="1233.8403" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="1072.3403,-1174.5 1395.3403,-1174.5 "/>
<text text-anchor="middle" x="1233.8403" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="1072.3403,-1151.5 1395.3403,-1151.5 "/>
<text text-anchor="middle" x="1233.8403" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="1072.3403,-1128.5 1395.3403,-1128.5 "/>
<text text-anchor="middle" x="1233.8403" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1072.3403,-1105.5 1395.3403,-1105.5 "/>
<text text-anchor="middle" x="1233.8403" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="1072.3403,-1082.5 1395.3403,-1082.5 "/>
<text text-anchor="middle" x="1233.8403" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="1072.3403,-1059.5 1395.3403,-1059.5 "/>
<text text-anchor="middle" x="1233.8403" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="1072.3403,-1036.5 1395.3403,-1036.5 "/>
<text text-anchor="middle" x="1233.8403" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="1395.3403,-1013.5 1395.3403,-1519.5 "/>
<text text-anchor="middle" x="1405.8403" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1398.5128,-1013.3851C1411.9951,-998.4616 1425.3773,-983.649 1438.4359,-969.1947"/>
<polygon fill="#000000" stroke="#000000" points="1441.1273,-971.4365 1445.234,-961.6699 1435.9331,-966.7439 1441.1273,-971.4365"/>
<text text-anchor="middle" x="1484.3403" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node11" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M44.8403,-674C44.8403,-674 396.8403,-674 396.8403,-674 402.8403,-674 408.8403,-680 408.8403,-686 408.8403,-686 408.8403,-915 408.8403,-915 408.8403,-921 402.8403,-927 396.8403,-927 396.8403,-927 44.8403,-927 44.8403,-927 38.8403,-927 32.8403,-921 32.8403,-915 32.8403,-915 32.8403,-686 32.8403,-686 32.8403,-680 38.8403,-674 44.8403,-674"/>
<text text-anchor="middle" x="116.3403" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="199.8403,-674 199.8403,-927 "/>
<text text-anchor="middle" x="210.3403" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="220.8403,-674 220.8403,-927 "/>
<text text-anchor="middle" x="304.3403" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="220.8403,-904 387.8403,-904 "/>
<text text-anchor="middle" x="304.3403" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="220.8403,-881 387.8403,-881 "/>
<text text-anchor="middle" x="304.3403" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="220.8403,-858 387.8403,-858 "/>
<text text-anchor="middle" x="304.3403" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="220.8403,-835 387.8403,-835 "/>
<text text-anchor="middle" x="304.3403" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="220.8403,-812 387.8403,-812 "/>
<text text-anchor="middle" x="304.3403" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="220.8403,-789 387.8403,-789 "/>
<text text-anchor="middle" x="304.3403" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="220.8403,-766 387.8403,-766 "/>
<text text-anchor="middle" x="304.3403" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="220.8403,-743 387.8403,-743 "/>
<text text-anchor="middle" x="304.3403" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="220.8403,-720 387.8403,-720 "/>
<text text-anchor="middle" x="304.3403" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="220.8403,-697 387.8403,-697 "/>
<text text-anchor="middle" x="304.3403" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="387.8403,-674 387.8403,-927 "/>
<text text-anchor="middle" x="398.3403" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge13" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M180.0664,-673.8406C138.7623,-534.3891 87.4618,-321.6052 136.8403,-259 190.0446,-191.5442 399.8889,-150.1458 566.3621,-127.299"/>
<polygon fill="#000000" stroke="#000000" points="567.3211,-130.7011 576.7597,-125.8883 566.3799,-123.7646 567.3211,-130.7011"/>
<text text-anchor="middle" x="216.8403" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M196.2804,-673.7806C197.9461,-648.8293 205.0717,-624.64 221.8403,-606 250.9393,-573.6532 502.1341,-555.6751 664.2659,-547.3468"/>
<polygon fill="#000000" stroke="#000000" points="664.5199,-550.8386 674.3297,-546.8364 664.1652,-543.8475 664.5199,-550.8386"/>
<text text-anchor="middle" x="351.3403" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- therapeutic_procedure -->
<g id="node12" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M1035.3403,-743C1035.3403,-743 1392.3403,-743 1392.3403,-743 1398.3403,-743 1404.3403,-749 1404.3403,-755 1404.3403,-755 1404.3403,-846 1404.3403,-846 1404.3403,-852 1398.3403,-858 1392.3403,-858 1392.3403,-858 1035.3403,-858 1035.3403,-858 1029.3403,-858 1023.3403,-852 1023.3403,-846 1023.3403,-846 1023.3403,-755 1023.3403,-755 1023.3403,-749 1029.3403,-743 1035.3403,-743"/>
<text text-anchor="middle" x="1113.8403" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="1204.3403,-743 1204.3403,-858 "/>
<text text-anchor="middle" x="1214.8403" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1225.3403,-743 1225.3403,-858 "/>
<text text-anchor="middle" x="1304.3403" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="1225.3403,-835 1383.3403,-835 "/>
<text text-anchor="middle" x="1304.3403" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="1225.3403,-812 1383.3403,-812 "/>
<text text-anchor="middle" x="1304.3403" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1225.3403,-789 1383.3403,-789 "/>
<text text-anchor="middle" x="1304.3403" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="1225.3403,-766 1383.3403,-766 "/>
<text text-anchor="middle" x="1304.3403" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1383.3403,-743 1383.3403,-858 "/>
<text text-anchor="middle" x="1393.8403" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1150.6926,-742.7175C1112.7765,-709.8012 1062.5755,-669.2282 1013.8403,-639 986.0729,-621.7772 954.7583,-605.7286 924.888,-591.8239"/>
<polygon fill="#000000" stroke="#000000" points="926.217,-588.5826 915.6698,-587.5786 923.2888,-594.9408 926.217,-588.5826"/>
<text text-anchor="middle" x="1074.8403" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- study_personnel -->
<g id="node13" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M1254.3403,-294C1254.3403,-294 1561.3403,-294 1561.3403,-294 1567.3403,-294 1573.3403,-300 1573.3403,-306 1573.3403,-306 1573.3403,-397 1573.3403,-397 1573.3403,-403 1567.3403,-409 1561.3403,-409 1561.3403,-409 1254.3403,-409 1254.3403,-409 1248.3403,-409 1242.3403,-403 1242.3403,-397 1242.3403,-397 1242.3403,-306 1242.3403,-306 1242.3403,-300 1248.3403,-294 1254.3403,-294"/>
<text text-anchor="middle" x="1309.3403" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="1376.3403,-294 1376.3403,-409 "/>
<text text-anchor="middle" x="1386.8403" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1397.3403,-294 1397.3403,-409 "/>
<text text-anchor="middle" x="1474.8403" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="1397.3403,-386 1552.3403,-386 "/>
<text text-anchor="middle" x="1474.8403" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="1397.3403,-363 1552.3403,-363 "/>
<text text-anchor="middle" x="1474.8403" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="1397.3403,-340 1552.3403,-340 "/>
<text text-anchor="middle" x="1474.8403" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="1397.3403,-317 1552.3403,-317 "/>
<text text-anchor="middle" x="1474.8403" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="1552.3403,-294 1552.3403,-409 "/>
<text text-anchor="middle" x="1562.8403" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge15" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1306.1058,-293.9944C1282.7066,-281.7326 1257.6845,-269.3681 1233.8403,-259 1159.174,-226.533 1075.3183,-196.0959 1000.4092,-170.9361"/>
<polygon fill="#000000" stroke="#000000" points="1001.442,-167.591 990.8481,-167.7371 999.2208,-174.2293 1001.442,-167.591"/>
<text text-anchor="middle" x="1255.3403" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- synonym -->
<g id="node14" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M344.3403,-1220.5C344.3403,-1220.5 645.3403,-1220.5 645.3403,-1220.5 651.3403,-1220.5 657.3403,-1226.5 657.3403,-1232.5 657.3403,-1232.5 657.3403,-1300.5 657.3403,-1300.5 657.3403,-1306.5 651.3403,-1312.5 645.3403,-1312.5 645.3403,-1312.5 344.3403,-1312.5 344.3403,-1312.5 338.3403,-1312.5 332.3403,-1306.5 332.3403,-1300.5 332.3403,-1300.5 332.3403,-1232.5 332.3403,-1232.5 332.3403,-1226.5 338.3403,-1220.5 344.3403,-1220.5"/>
<text text-anchor="middle" x="372.3403" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="412.3403,-1220.5 412.3403,-1312.5 "/>
<text text-anchor="middle" x="422.8403" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="433.3403,-1220.5 433.3403,-1312.5 "/>
<text text-anchor="middle" x="534.8403" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_id</text>
<polyline fill="none" stroke="#000000" points="433.3403,-1289.5 636.3403,-1289.5 "/>
<text text-anchor="middle" x="534.8403" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_node</text>
<polyline fill="none" stroke="#000000" points="433.3403,-1266.5 636.3403,-1266.5 "/>
<text text-anchor="middle" x="534.8403" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="433.3403,-1243.5 636.3403,-1243.5 "/>
<text text-anchor="middle" x="534.8403" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="636.3403,-1220.5 636.3403,-1312.5 "/>
<text text-anchor="middle" x="646.8403" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge2" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M367.3224,-1220.3922C256.9523,-1173.3485 102.982,-1089.0791 23.8403,-962 -14.3661,-900.6515 4.8403,-872.7728 4.8403,-800.5 4.8403,-800.5 4.8403,-800.5 4.8403,-351.5 4.8403,-233.0847 335.9246,-163.8758 566.406,-130.043"/>
<polygon fill="#000000" stroke="#000000" points="567.2251,-133.4607 576.617,-128.5575 566.2173,-126.5337 567.2251,-133.4607"/>
<text text-anchor="middle" x="47.3403" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M479.1097,-1220.2689C444.0731,-1108.0435 372.5789,-817.3493 503.8403,-639 524.0608,-611.5256 595.9128,-587.5829 663.9925,-570.2993"/>
<polygon fill="#000000" stroke="#000000" points="665.1498,-573.6178 674.0031,-567.798 663.4529,-566.8266 665.1498,-573.6178"/>
<text text-anchor="middle" x="546.3403" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M552.0922,-1220.3526C629.1675,-1161.055 772.949,-1060.1553 913.8403,-1013 964.4209,-996.071 1328.6018,-985.618 1412.1498,-961.2225"/>
<polygon fill="#000000" stroke="#000000" points="1413.3986,-964.4933 1421.6523,-957.8504 1411.0576,-957.8963 1413.3986,-964.4933"/>
<text text-anchor="middle" x="1322.3403" y="-983.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study_funding -->
<g id="node15" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M1642.3403,-317C1642.3403,-317 2021.3403,-317 2021.3403,-317 2027.3403,-317 2033.3403,-323 2033.3403,-329 2033.3403,-329 2033.3403,-374 2033.3403,-374 2033.3403,-380 2027.3403,-386 2021.3403,-386 2021.3403,-386 1642.3403,-386 1642.3403,-386 1636.3403,-386 1630.3403,-380 1630.3403,-374 1630.3403,-374 1630.3403,-329 1630.3403,-329 1630.3403,-323 1636.3403,-317 1642.3403,-317"/>
<text text-anchor="middle" x="1689.8403" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="1749.3403,-317 1749.3403,-386 "/>
<text text-anchor="middle" x="1759.8403" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1770.3403,-317 1770.3403,-386 "/>
<text text-anchor="middle" x="1891.3403" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="1770.3403,-363 2012.3403,-363 "/>
<text text-anchor="middle" x="1891.3403" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="1770.3403,-340 2012.3403,-340 "/>
<text text-anchor="middle" x="1891.3403" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="2012.3403,-317 2012.3403,-386 "/>
<text text-anchor="middle" x="2022.8403" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge5" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1784.6739,-316.9524C1742.5563,-287.9024 1678.0773,-247.7338 1615.8403,-226 1505.6603,-187.524 1208.5843,-149.5217 1001.0347,-126.4088"/>
<polygon fill="#000000" stroke="#000000" points="1001.2358,-122.9097 990.9107,-125.2853 1000.4636,-129.867 1001.2358,-122.9097"/>
<text text-anchor="middle" x="1708.8403" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
</g>
</svg>
</div>
