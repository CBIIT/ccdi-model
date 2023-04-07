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
<svg width="6385pt" height="1821pt"
 viewBox="0.00 0.00 6385.00 1821.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1817)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1817 6381,-1817 6381,4 -4,4"/>
<!-- exposure -->
<g id="node1" class="node">
<title>exposure</title>
<path fill="none" stroke="#000000" d="M3762,-622C3762,-622 4173,-622 4173,-622 4179,-622 4185,-628 4185,-634 4185,-634 4185,-1093 4185,-1093 4185,-1099 4179,-1105 4173,-1105 4173,-1105 3762,-1105 3762,-1105 3756,-1105 3750,-1099 3750,-1093 3750,-1093 3750,-634 3750,-634 3750,-628 3756,-622 3762,-622"/>
<text text-anchor="middle" x="3791" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
<polyline fill="none" stroke="#000000" points="3832,-622 3832,-1105 "/>
<text text-anchor="middle" x="3842.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3853,-622 3853,-1105 "/>
<text text-anchor="middle" x="4008.5" y="-1089.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_days_per_week</text>
<polyline fill="none" stroke="#000000" points="3853,-1082 4164,-1082 "/>
<text text-anchor="middle" x="4008.5" y="-1066.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_drinks_per_day</text>
<polyline fill="none" stroke="#000000" points="3853,-1059 4164,-1059 "/>
<text text-anchor="middle" x="4008.5" y="-1043.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_history</text>
<polyline fill="none" stroke="#000000" points="3853,-1036 4164,-1036 "/>
<text text-anchor="middle" x="4008.5" y="-1020.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_intensity</text>
<polyline fill="none" stroke="#000000" points="3853,-1013 4164,-1013 "/>
<text text-anchor="middle" x="4008.5" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000">asbestos_exposure</text>
<polyline fill="none" stroke="#000000" points="3853,-990 4164,-990 "/>
<text text-anchor="middle" x="4008.5" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">cigarettes_per_day</text>
<polyline fill="none" stroke="#000000" points="3853,-967 4164,-967 "/>
<text text-anchor="middle" x="4008.5" y="-951.8" font-family="Times,serif" font-size="14.00" fill="#000000">coal_dust_exposure</text>
<polyline fill="none" stroke="#000000" points="3853,-944 4164,-944 "/>
<text text-anchor="middle" x="4008.5" y="-928.8" font-family="Times,serif" font-size="14.00" fill="#000000">environmental_tobacco_smoke_exposure</text>
<polyline fill="none" stroke="#000000" points="3853,-921 4164,-921 "/>
<text text-anchor="middle" x="4008.5" y="-905.8" font-family="Times,serif" font-size="14.00" fill="#000000">exposure_id</text>
<polyline fill="none" stroke="#000000" points="3853,-898 4164,-898 "/>
<text text-anchor="middle" x="4008.5" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">pack_years_smoked</text>
<polyline fill="none" stroke="#000000" points="3853,-875 4164,-875 "/>
<text text-anchor="middle" x="4008.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">radon_exposure</text>
<polyline fill="none" stroke="#000000" points="3853,-852 4164,-852 "/>
<text text-anchor="middle" x="4008.5" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">respirable_crystalline_silica_exposure</text>
<polyline fill="none" stroke="#000000" points="3853,-829 4164,-829 "/>
<text text-anchor="middle" x="4008.5" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">smoking_frequency</text>
<polyline fill="none" stroke="#000000" points="3853,-806 4164,-806 "/>
<text text-anchor="middle" x="4008.5" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">start_days_from_index</text>
<polyline fill="none" stroke="#000000" points="3853,-783 4164,-783 "/>
<text text-anchor="middle" x="4008.5" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">time_between_waking_and_first_smoke</text>
<polyline fill="none" stroke="#000000" points="3853,-760 4164,-760 "/>
<text text-anchor="middle" x="4008.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_onset_year</text>
<polyline fill="none" stroke="#000000" points="3853,-737 4164,-737 "/>
<text text-anchor="middle" x="4008.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_quit_year</text>
<polyline fill="none" stroke="#000000" points="3853,-714 4164,-714 "/>
<text text-anchor="middle" x="4008.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_status</text>
<polyline fill="none" stroke="#000000" points="3853,-691 4164,-691 "/>
<text text-anchor="middle" x="4008.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_smoke_exposure</text>
<polyline fill="none" stroke="#000000" points="3853,-668 4164,-668 "/>
<text text-anchor="middle" x="4008.5" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_tobacco_used</text>
<polyline fill="none" stroke="#000000" points="3853,-645 4164,-645 "/>
<text text-anchor="middle" x="4008.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">years_smoked</text>
<polyline fill="none" stroke="#000000" points="4164,-622 4164,-1105 "/>
<text text-anchor="middle" x="4174.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node3" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M2979.5,-374.5C2979.5,-374.5 3283.5,-374.5 3283.5,-374.5 3289.5,-374.5 3295.5,-380.5 3295.5,-386.5 3295.5,-386.5 3295.5,-477.5 3295.5,-477.5 3295.5,-483.5 3289.5,-489.5 3283.5,-489.5 3283.5,-489.5 2979.5,-489.5 2979.5,-489.5 2973.5,-489.5 2967.5,-483.5 2967.5,-477.5 2967.5,-477.5 2967.5,-386.5 2967.5,-386.5 2967.5,-380.5 2973.5,-374.5 2979.5,-374.5"/>
<text text-anchor="middle" x="3015.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="3063.5,-374.5 3063.5,-489.5 "/>
<text text-anchor="middle" x="3074" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3084.5,-374.5 3084.5,-489.5 "/>
<text text-anchor="middle" x="3179.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="3084.5,-466.5 3274.5,-466.5 "/>
<text text-anchor="middle" x="3179.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="3084.5,-443.5 3274.5,-443.5 "/>
<text text-anchor="middle" x="3179.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="3084.5,-420.5 3274.5,-420.5 "/>
<text text-anchor="middle" x="3179.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="3084.5,-397.5 3274.5,-397.5 "/>
<text text-anchor="middle" x="3179.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="3274.5,-374.5 3274.5,-489.5 "/>
<text text-anchor="middle" x="3285" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3811.385,-621.7549C3789.9629,-599.9286 3766.6099,-580.0499 3741.5,-564 3670.3106,-518.4968 3459.4824,-479.4474 3305.5653,-455.8751"/>
<polygon fill="#000000" stroke="#000000" points="3305.9242,-452.3895 3295.5114,-454.345 3304.8709,-459.3098 3305.9242,-452.3895"/>
<text text-anchor="middle" x="3739" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- imaging_file -->
<g id="node2" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M1138,-1318C1138,-1318 1479,-1318 1479,-1318 1485,-1318 1491,-1324 1491,-1330 1491,-1330 1491,-1697 1491,-1697 1491,-1703 1485,-1709 1479,-1709 1479,-1709 1138,-1709 1138,-1709 1132,-1709 1126,-1703 1126,-1697 1126,-1697 1126,-1330 1126,-1330 1126,-1324 1132,-1318 1138,-1318"/>
<text text-anchor="middle" x="1178" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="1230,-1318 1230,-1709 "/>
<text text-anchor="middle" x="1240.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1251,-1318 1251,-1709 "/>
<text text-anchor="middle" x="1360.5" y="-1693.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1251,-1686 1470,-1686 "/>
<text text-anchor="middle" x="1360.5" y="-1670.8" font-family="Times,serif" font-size="14.00" fill="#000000">deidentification_method</text>
<polyline fill="none" stroke="#000000" points="1251,-1663 1470,-1663 "/>
<text text-anchor="middle" x="1360.5" y="-1647.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1251,-1640 1470,-1640 "/>
<text text-anchor="middle" x="1360.5" y="-1624.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1251,-1617 1470,-1617 "/>
<text text-anchor="middle" x="1360.5" y="-1601.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1251,-1594 1470,-1594 "/>
<text text-anchor="middle" x="1360.5" y="-1578.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1251,-1571 1470,-1571 "/>
<text text-anchor="middle" x="1360.5" y="-1555.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1251,-1548 1470,-1548 "/>
<text text-anchor="middle" x="1360.5" y="-1532.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1251,-1525 1470,-1525 "/>
<text text-anchor="middle" x="1360.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">fixation_embedding_method</text>
<polyline fill="none" stroke="#000000" points="1251,-1502 1470,-1502 "/>
<text text-anchor="middle" x="1360.5" y="-1486.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="1251,-1479 1470,-1479 "/>
<text text-anchor="middle" x="1360.5" y="-1463.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file_id</text>
<polyline fill="none" stroke="#000000" points="1251,-1456 1470,-1456 "/>
<text text-anchor="middle" x="1360.5" y="-1440.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="1251,-1433 1470,-1433 "/>
<text text-anchor="middle" x="1360.5" y="-1417.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="1251,-1410 1470,-1410 "/>
<text text-anchor="middle" x="1360.5" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">magnification</text>
<polyline fill="none" stroke="#000000" points="1251,-1387 1470,-1387 "/>
<text text-anchor="middle" x="1360.5" y="-1371.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1251,-1364 1470,-1364 "/>
<text text-anchor="middle" x="1360.5" y="-1348.8" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="1251,-1341 1470,-1341 "/>
<text text-anchor="middle" x="1360.5" y="-1325.8" font-family="Times,serif" font-size="14.00" fill="#000000">staining_method</text>
<polyline fill="none" stroke="#000000" points="1470,-1318 1470,-1709 "/>
<text text-anchor="middle" x="1480.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node12" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M2047.5,-783C2047.5,-783 2361.5,-783 2361.5,-783 2367.5,-783 2373.5,-789 2373.5,-795 2373.5,-795 2373.5,-932 2373.5,-932 2373.5,-938 2367.5,-944 2361.5,-944 2361.5,-944 2047.5,-944 2047.5,-944 2041.5,-944 2035.5,-938 2035.5,-932 2035.5,-932 2035.5,-795 2035.5,-795 2035.5,-789 2041.5,-783 2047.5,-783"/>
<text text-anchor="middle" x="2069.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="2103.5,-783 2103.5,-944 "/>
<text text-anchor="middle" x="2114" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2124.5,-783 2124.5,-944 "/>
<text text-anchor="middle" x="2238.5" y="-928.8" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="2124.5,-921 2352.5,-921 "/>
<text text-anchor="middle" x="2238.5" y="-905.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="2124.5,-898 2352.5,-898 "/>
<text text-anchor="middle" x="2238.5" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="2124.5,-875 2352.5,-875 "/>
<text text-anchor="middle" x="2238.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="2124.5,-852 2352.5,-852 "/>
<text text-anchor="middle" x="2238.5" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="2124.5,-829 2352.5,-829 "/>
<text text-anchor="middle" x="2238.5" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="2124.5,-806 2352.5,-806 "/>
<text text-anchor="middle" x="2238.5" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="2352.5,-783 2352.5,-944 "/>
<text text-anchor="middle" x="2363" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1397.6663,-1317.7967C1424.8069,-1277.4656 1458.5631,-1239.5519 1499.5,-1214 1609.9182,-1145.0794 1660.9207,-1193.3058 1790.5,-1181 1842.6406,-1176.0484 1980.9662,-1190.5663 2025.5,-1163 2101.5025,-1115.9546 2149.36,-1023.637 2176.267,-953.8679"/>
<polygon fill="#000000" stroke="#000000" points="2179.667,-954.7716 2179.9254,-944.1799 2173.1183,-952.2986 2179.667,-954.7716"/>
<text text-anchor="middle" x="1845" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- study -->
<g id="node21" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M4936.5,-.5C4936.5,-.5 5326.5,-.5 5326.5,-.5 5332.5,-.5 5338.5,-6.5 5338.5,-12.5 5338.5,-12.5 5338.5,-287.5 5338.5,-287.5 5338.5,-293.5 5332.5,-299.5 5326.5,-299.5 5326.5,-299.5 4936.5,-299.5 4936.5,-299.5 4930.5,-299.5 4924.5,-293.5 4924.5,-287.5 4924.5,-287.5 4924.5,-12.5 4924.5,-12.5 4924.5,-6.5 4930.5,-.5 4936.5,-.5"/>
<text text-anchor="middle" x="4952.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="4980.5,-.5 4980.5,-299.5 "/>
<text text-anchor="middle" x="4991" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="5001.5,-.5 5001.5,-299.5 "/>
<text text-anchor="middle" x="5159.5" y="-284.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="5001.5,-276.5 5317.5,-276.5 "/>
<text text-anchor="middle" x="5159.5" y="-261.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="5001.5,-253.5 5317.5,-253.5 "/>
<text text-anchor="middle" x="5159.5" y="-238.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_number</text>
<polyline fill="none" stroke="#000000" points="5001.5,-230.5 5317.5,-230.5 "/>
<text text-anchor="middle" x="5159.5" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="5001.5,-207.5 5317.5,-207.5 "/>
<text text-anchor="middle" x="5159.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="5001.5,-184.5 5317.5,-184.5 "/>
<text text-anchor="middle" x="5159.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="5001.5,-161.5 5317.5,-161.5 "/>
<text text-anchor="middle" x="5159.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="5001.5,-138.5 5317.5,-138.5 "/>
<text text-anchor="middle" x="5159.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="5001.5,-115.5 5317.5,-115.5 "/>
<text text-anchor="middle" x="5159.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="5001.5,-92.5 5317.5,-92.5 "/>
<text text-anchor="middle" x="5159.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="5001.5,-69.5 5317.5,-69.5 "/>
<text text-anchor="middle" x="5159.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="5001.5,-46.5 5317.5,-46.5 "/>
<text text-anchor="middle" x="5159.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="5001.5,-23.5 5317.5,-23.5 "/>
<text text-anchor="middle" x="5159.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="5317.5,-.5 5317.5,-299.5 "/>
<text text-anchor="middle" x="5328" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge22" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3295.5931,-408.8629C3654.8496,-358.2077 4511.0212,-237.4875 4914.3197,-180.6224"/>
<polygon fill="#000000" stroke="#000000" points="4914.9377,-184.07 4924.3511,-179.208 4913.9603,-177.1386 4914.9377,-184.07"/>
<text text-anchor="middle" x="3944" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- pdx -->
<g id="node4" class="node">
<title>pdx</title>
<path fill="none" stroke="#000000" d="M1521,-1398.5C1521,-1398.5 1850,-1398.5 1850,-1398.5 1856,-1398.5 1862,-1404.5 1862,-1410.5 1862,-1410.5 1862,-1616.5 1862,-1616.5 1862,-1622.5 1856,-1628.5 1850,-1628.5 1850,-1628.5 1521,-1628.5 1521,-1628.5 1515,-1628.5 1509,-1622.5 1509,-1616.5 1509,-1616.5 1509,-1410.5 1509,-1410.5 1509,-1404.5 1515,-1398.5 1521,-1398.5"/>
<text text-anchor="middle" x="1530.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
<polyline fill="none" stroke="#000000" points="1552,-1398.5 1552,-1628.5 "/>
<text text-anchor="middle" x="1562.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1573,-1398.5 1573,-1628.5 "/>
<text text-anchor="middle" x="1707" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_site</text>
<polyline fill="none" stroke="#000000" points="1573,-1605.5 1841,-1605.5 "/>
<text text-anchor="middle" x="1707" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_type</text>
<polyline fill="none" stroke="#000000" points="1573,-1582.5 1841,-1582.5 "/>
<text text-anchor="middle" x="1707" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_id</text>
<polyline fill="none" stroke="#000000" points="1573,-1559.5 1841,-1559.5 "/>
<text text-anchor="middle" x="1707" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">mouse_strain</text>
<polyline fill="none" stroke="#000000" points="1573,-1536.5 1841,-1536.5 "/>
<text text-anchor="middle" x="1707" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx_id</text>
<polyline fill="none" stroke="#000000" points="1573,-1513.5 1841,-1513.5 "/>
<text text-anchor="middle" x="1707" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">strain_immune_system_humanized</text>
<polyline fill="none" stroke="#000000" points="1573,-1490.5 1841,-1490.5 "/>
<text text-anchor="middle" x="1707" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_characterization_method</text>
<polyline fill="none" stroke="#000000" points="1573,-1467.5 1841,-1467.5 "/>
<text text-anchor="middle" x="1707" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_not_mus_or_ebv_origin</text>
<polyline fill="none" stroke="#000000" points="1573,-1444.5 1841,-1444.5 "/>
<text text-anchor="middle" x="1707" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_preparation</text>
<polyline fill="none" stroke="#000000" points="1573,-1421.5 1841,-1421.5 "/>
<text text-anchor="middle" x="1707" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_humanization</text>
<polyline fill="none" stroke="#000000" points="1841,-1398.5 1841,-1628.5 "/>
<text text-anchor="middle" x="1851.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1732.8365,-1398.2348C1763.7242,-1335.8512 1809.6694,-1261.9631 1870.5,-1214 1927.4492,-1169.0973 1968.8808,-1208.3181 2025.5,-1163 2093.8162,-1108.3196 2142.0292,-1019.985 2171.0739,-953.3879"/>
<polygon fill="#000000" stroke="#000000" points="2174.315,-954.7104 2175.0452,-944.1408 2167.8831,-951.9482 2174.315,-954.7104"/>
<text text-anchor="middle" x="2017.5" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- clinical_measure_file -->
<g id="node5" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M1189,-725.5C1189,-725.5 1562,-725.5 1562,-725.5 1568,-725.5 1574,-731.5 1574,-737.5 1574,-737.5 1574,-989.5 1574,-989.5 1574,-995.5 1568,-1001.5 1562,-1001.5 1562,-1001.5 1189,-1001.5 1189,-1001.5 1183,-1001.5 1177,-995.5 1177,-989.5 1177,-989.5 1177,-737.5 1177,-737.5 1177,-731.5 1183,-725.5 1189,-725.5"/>
<text text-anchor="middle" x="1260.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="1344,-725.5 1344,-1001.5 "/>
<text text-anchor="middle" x="1354.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1365,-725.5 1365,-1001.5 "/>
<text text-anchor="middle" x="1459" y="-986.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1365,-978.5 1553,-978.5 "/>
<text text-anchor="middle" x="1459" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1365,-955.5 1553,-955.5 "/>
<text text-anchor="middle" x="1459" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file_id</text>
<polyline fill="none" stroke="#000000" points="1365,-932.5 1553,-932.5 "/>
<text text-anchor="middle" x="1459" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1365,-909.5 1553,-909.5 "/>
<text text-anchor="middle" x="1459" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1365,-886.5 1553,-886.5 "/>
<text text-anchor="middle" x="1459" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1365,-863.5 1553,-863.5 "/>
<text text-anchor="middle" x="1459" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1365,-840.5 1553,-840.5 "/>
<text text-anchor="middle" x="1459" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1365,-817.5 1553,-817.5 "/>
<text text-anchor="middle" x="1459" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1365,-794.5 1553,-794.5 "/>
<text text-anchor="middle" x="1459" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1365,-771.5 1553,-771.5 "/>
<text text-anchor="middle" x="1459" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1365,-748.5 1553,-748.5 "/>
<text text-anchor="middle" x="1459" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="1553,-725.5 1553,-1001.5 "/>
<text text-anchor="middle" x="1563.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1439.1208,-725.3946C1473.3152,-666.427 1521.191,-602.457 1582.5,-564 1696.7714,-492.3214 2577.1995,-452.0951 2957.4878,-437.9097"/>
<polygon fill="#000000" stroke="#000000" points="2957.6217,-441.4073 2967.4849,-437.5385 2957.3619,-434.4121 2957.6217,-441.4073"/>
<text text-anchor="middle" x="1815" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge15" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1437.609,-725.4822C1480.7858,-649.4409 1546.7727,-563.9469 1636.5,-531 2244.7327,-307.6633 4247.9993,-192.7163 4914.0235,-159.9879"/>
<polygon fill="#000000" stroke="#000000" points="4914.3968,-163.4739 4924.2134,-159.4884 4914.054,-156.4823 4914.3968,-163.4739"/>
<text text-anchor="middle" x="2602.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- sequencing_file -->
<g id="node6" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M1892,-1214.5C1892,-1214.5 2361,-1214.5 2361,-1214.5 2367,-1214.5 2373,-1220.5 2373,-1226.5 2373,-1226.5 2373,-1800.5 2373,-1800.5 2373,-1806.5 2367,-1812.5 2361,-1812.5 2361,-1812.5 1892,-1812.5 1892,-1812.5 1886,-1812.5 1880,-1806.5 1880,-1800.5 1880,-1800.5 1880,-1226.5 1880,-1226.5 1880,-1220.5 1886,-1214.5 1892,-1214.5"/>
<text text-anchor="middle" x="1944" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="2008,-1214.5 2008,-1812.5 "/>
<text text-anchor="middle" x="2018.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2029,-1214.5 2029,-1812.5 "/>
<text text-anchor="middle" x="2190.5" y="-1797.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="2029,-1789.5 2352,-1789.5 "/>
<text text-anchor="middle" x="2190.5" y="-1774.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2029,-1766.5 2352,-1766.5 "/>
<text text-anchor="middle" x="2190.5" y="-1751.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2029,-1743.5 2352,-1743.5 "/>
<text text-anchor="middle" x="2190.5" y="-1728.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="2029,-1720.5 2352,-1720.5 "/>
<text text-anchor="middle" x="2190.5" y="-1705.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="2029,-1697.5 2352,-1697.5 "/>
<text text-anchor="middle" x="2190.5" y="-1682.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2029,-1674.5 2352,-1674.5 "/>
<text text-anchor="middle" x="2190.5" y="-1659.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="2029,-1651.5 2352,-1651.5 "/>
<text text-anchor="middle" x="2190.5" y="-1636.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2029,-1628.5 2352,-1628.5 "/>
<text text-anchor="middle" x="2190.5" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2029,-1605.5 2352,-1605.5 "/>
<text text-anchor="middle" x="2190.5" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2029,-1582.5 2352,-1582.5 "/>
<text text-anchor="middle" x="2190.5" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2029,-1559.5 2352,-1559.5 "/>
<text text-anchor="middle" x="2190.5" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2029,-1536.5 2352,-1536.5 "/>
<text text-anchor="middle" x="2190.5" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2029,-1513.5 2352,-1513.5 "/>
<text text-anchor="middle" x="2190.5" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="2029,-1490.5 2352,-1490.5 "/>
<text text-anchor="middle" x="2190.5" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="2029,-1467.5 2352,-1467.5 "/>
<text text-anchor="middle" x="2190.5" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="2029,-1444.5 2352,-1444.5 "/>
<text text-anchor="middle" x="2190.5" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="2029,-1421.5 2352,-1421.5 "/>
<text text-anchor="middle" x="2190.5" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="2029,-1398.5 2352,-1398.5 "/>
<text text-anchor="middle" x="2190.5" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="2029,-1375.5 2352,-1375.5 "/>
<text text-anchor="middle" x="2190.5" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2029,-1352.5 2352,-1352.5 "/>
<text text-anchor="middle" x="2190.5" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="2029,-1329.5 2352,-1329.5 "/>
<text text-anchor="middle" x="2190.5" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="2029,-1306.5 2352,-1306.5 "/>
<text text-anchor="middle" x="2190.5" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="2029,-1283.5 2352,-1283.5 "/>
<text text-anchor="middle" x="2190.5" y="-1268.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="2029,-1260.5 2352,-1260.5 "/>
<text text-anchor="middle" x="2190.5" y="-1245.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="2029,-1237.5 2352,-1237.5 "/>
<text text-anchor="middle" x="2190.5" y="-1222.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 1 properties</text>
<polyline fill="none" stroke="#000000" points="2352,-1214.5 2352,-1812.5 "/>
<text text-anchor="middle" x="2362.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge23" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2124.0952,-1214.2193C2125.054,-1202.9922 2126.1819,-1191.8884 2127.5,-1181 2136.9141,-1103.2318 2158.5818,-1016.9644 2176.5416,-954.0033"/>
<polygon fill="#000000" stroke="#000000" points="2179.9884,-954.6814 2179.3897,-944.1035 2173.2613,-952.7459 2179.9884,-954.6814"/>
<text text-anchor="middle" x="2194" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- study_funding -->
<g id="node7" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M4615,-386C4615,-386 4994,-386 4994,-386 5000,-386 5006,-392 5006,-398 5006,-398 5006,-466 5006,-466 5006,-472 5000,-478 4994,-478 4994,-478 4615,-478 4615,-478 4609,-478 4603,-472 4603,-466 4603,-466 4603,-398 4603,-398 4603,-392 4609,-386 4615,-386"/>
<text text-anchor="middle" x="4662.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="4722,-386 4722,-478 "/>
<text text-anchor="middle" x="4732.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4743,-386 4743,-478 "/>
<text text-anchor="middle" x="4864" y="-462.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="4743,-455 4985,-455 "/>
<text text-anchor="middle" x="4864" y="-439.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="4743,-432 4985,-432 "/>
<text text-anchor="middle" x="4864" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="4743,-409 4985,-409 "/>
<text text-anchor="middle" x="4864" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding_id</text>
<polyline fill="none" stroke="#000000" points="4985,-386 4985,-478 "/>
<text text-anchor="middle" x="4995.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge16" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M4837.2706,-385.7291C4853.7774,-363.9848 4874.8543,-338.4181 4896.5,-318 4903.064,-311.8083 4909.8661,-305.6571 4916.8404,-299.5713"/>
<polygon fill="#000000" stroke="#000000" points="4919.1821,-302.1737 4924.4728,-292.9944 4914.6126,-296.8708 4919.1821,-302.1737"/>
<text text-anchor="middle" x="4958.5" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- follow_up -->
<g id="node8" class="node">
<title>follow_up</title>
<path fill="none" stroke="#000000" d="M4215,-760C4215,-760 4578,-760 4578,-760 4584,-760 4590,-766 4590,-772 4590,-772 4590,-955 4590,-955 4590,-961 4584,-967 4578,-967 4578,-967 4215,-967 4215,-967 4209,-967 4203,-961 4203,-955 4203,-955 4203,-772 4203,-772 4203,-766 4209,-760 4215,-760"/>
<text text-anchor="middle" x="4245.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
<polyline fill="none" stroke="#000000" points="4288,-760 4288,-967 "/>
<text text-anchor="middle" x="4298.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4309,-760 4309,-967 "/>
<text text-anchor="middle" x="4439" y="-951.8" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event</text>
<polyline fill="none" stroke="#000000" points="4309,-944 4569,-944 "/>
<text text-anchor="middle" x="4439" y="-928.8" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity</text>
<polyline fill="none" stroke="#000000" points="4309,-921 4569,-921 "/>
<text text-anchor="middle" x="4439" y="-905.8" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity_method_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="4309,-898 4569,-898 "/>
<text text-anchor="middle" x="4439" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_follow_up</text>
<polyline fill="none" stroke="#000000" points="4309,-875 4569,-875 "/>
<text text-anchor="middle" x="4439" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_response</text>
<polyline fill="none" stroke="#000000" points="4309,-852 4569,-852 "/>
<text text-anchor="middle" x="4439" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_category</text>
<polyline fill="none" stroke="#000000" points="4309,-829 4569,-829 "/>
<text text-anchor="middle" x="4439" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_id</text>
<polyline fill="none" stroke="#000000" points="4309,-806 4569,-806 "/>
<text text-anchor="middle" x="4439" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_other</text>
<polyline fill="none" stroke="#000000" points="4309,-783 4569,-783 "/>
<text text-anchor="middle" x="4439" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">risk_factor</text>
<polyline fill="none" stroke="#000000" points="4569,-760 4569,-967 "/>
<text text-anchor="middle" x="4579.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M4354.1484,-759.7543C4321.0086,-692.4661 4268.1309,-609.1923 4194.5,-564 4049.3633,-474.9197 3567.8352,-445.7381 3305.5141,-436.3433"/>
<polygon fill="#000000" stroke="#000000" points="3305.6219,-432.8451 3295.5048,-435.9907 3305.3753,-439.8407 3305.6219,-432.8451"/>
<text text-anchor="middle" x="4195.5" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- diagnosis -->
<g id="node9" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M4620.5,-668C4620.5,-668 4994.5,-668 4994.5,-668 5000.5,-668 5006.5,-674 5006.5,-680 5006.5,-680 5006.5,-1047 5006.5,-1047 5006.5,-1053 5000.5,-1059 4994.5,-1059 4994.5,-1059 4620.5,-1059 4620.5,-1059 4614.5,-1059 4608.5,-1053 4608.5,-1047 4608.5,-1047 4608.5,-680 4608.5,-680 4608.5,-674 4614.5,-668 4620.5,-668"/>
<text text-anchor="middle" x="4650.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="4692.5,-668 4692.5,-1059 "/>
<text text-anchor="middle" x="4703" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4713.5,-668 4713.5,-1059 "/>
<text text-anchor="middle" x="4849.5" y="-1043.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="4713.5,-1036 4985.5,-1036 "/>
<text text-anchor="middle" x="4849.5" y="-1020.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="4713.5,-1013 4985.5,-1013 "/>
<text text-anchor="middle" x="4849.5" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="4713.5,-990 4985.5,-990 "/>
<text text-anchor="middle" x="4849.5" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="4713.5,-967 4985.5,-967 "/>
<text text-anchor="middle" x="4849.5" y="-951.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="4713.5,-944 4985.5,-944 "/>
<text text-anchor="middle" x="4849.5" y="-928.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="4713.5,-921 4985.5,-921 "/>
<text text-anchor="middle" x="4849.5" y="-905.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="4713.5,-898 4985.5,-898 "/>
<text text-anchor="middle" x="4849.5" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="4713.5,-875 4985.5,-875 "/>
<text text-anchor="middle" x="4849.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="4713.5,-852 4985.5,-852 "/>
<text text-anchor="middle" x="4849.5" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="4713.5,-829 4985.5,-829 "/>
<text text-anchor="middle" x="4849.5" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="4713.5,-806 4985.5,-806 "/>
<text text-anchor="middle" x="4849.5" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="4713.5,-783 4985.5,-783 "/>
<text text-anchor="middle" x="4849.5" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="4713.5,-760 4985.5,-760 "/>
<text text-anchor="middle" x="4849.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="4713.5,-737 4985.5,-737 "/>
<text text-anchor="middle" x="4849.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="4713.5,-714 4985.5,-714 "/>
<text text-anchor="middle" x="4849.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="4713.5,-691 4985.5,-691 "/>
<text text-anchor="middle" x="4849.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="4985.5,-668 4985.5,-1059 "/>
<text text-anchor="middle" x="4996" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M4708.3644,-667.7237C4678.8084,-627.1357 4642.5584,-589.1266 4599.5,-564 4490.0196,-500.113 3670.567,-456.0449 3305.7696,-439.3893"/>
<polygon fill="#000000" stroke="#000000" points="3305.7908,-435.8867 3295.642,-438.9286 3305.4726,-442.8795 3305.7908,-435.8867"/>
<text text-anchor="middle" x="4588" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- methylation_array_file -->
<g id="node10" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M2403,-1387C2403,-1387 2798,-1387 2798,-1387 2804,-1387 2810,-1393 2810,-1399 2810,-1399 2810,-1628 2810,-1628 2810,-1634 2804,-1640 2798,-1640 2798,-1640 2403,-1640 2403,-1640 2397,-1640 2391,-1634 2391,-1628 2391,-1628 2391,-1399 2391,-1399 2391,-1393 2397,-1387 2403,-1387"/>
<text text-anchor="middle" x="2480" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="2569,-1387 2569,-1640 "/>
<text text-anchor="middle" x="2579.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2590,-1387 2590,-1640 "/>
<text text-anchor="middle" x="2689.5" y="-1624.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2590,-1617 2789,-1617 "/>
<text text-anchor="middle" x="2689.5" y="-1601.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2590,-1594 2789,-1594 "/>
<text text-anchor="middle" x="2689.5" y="-1578.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2590,-1571 2789,-1571 "/>
<text text-anchor="middle" x="2689.5" y="-1555.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2590,-1548 2789,-1548 "/>
<text text-anchor="middle" x="2689.5" y="-1532.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2590,-1525 2789,-1525 "/>
<text text-anchor="middle" x="2689.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2590,-1502 2789,-1502 "/>
<text text-anchor="middle" x="2689.5" y="-1486.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2590,-1479 2789,-1479 "/>
<text text-anchor="middle" x="2689.5" y="-1463.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2590,-1456 2789,-1456 "/>
<text text-anchor="middle" x="2689.5" y="-1440.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file_id</text>
<polyline fill="none" stroke="#000000" points="2590,-1433 2789,-1433 "/>
<text text-anchor="middle" x="2689.5" y="-1417.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="2590,-1410 2789,-1410 "/>
<text text-anchor="middle" x="2689.5" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="2789,-1387 2789,-1640 "/>
<text text-anchor="middle" x="2799.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2537.5589,-1386.809C2500.4837,-1325.1846 2447.7869,-1255.6081 2381.5,-1214 2343.9926,-1190.4567 2315.6113,-1226.4951 2283.5,-1196 2218.6796,-1134.4421 2202.7936,-1030.1745 2200.6951,-954.7906"/>
<polygon fill="#000000" stroke="#000000" points="2204.1857,-954.2809 2200.4868,-944.3527 2197.1871,-954.4206 2204.1857,-954.2809"/>
<text text-anchor="middle" x="2375" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- therapeutic_procedure -->
<g id="node11" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M1604,-794.5C1604,-794.5 2005,-794.5 2005,-794.5 2011,-794.5 2017,-800.5 2017,-806.5 2017,-806.5 2017,-920.5 2017,-920.5 2017,-926.5 2011,-932.5 2005,-932.5 2005,-932.5 1604,-932.5 1604,-932.5 1598,-932.5 1592,-926.5 1592,-920.5 1592,-920.5 1592,-806.5 1592,-806.5 1592,-800.5 1598,-794.5 1604,-794.5"/>
<text text-anchor="middle" x="1682.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="1773,-794.5 1773,-932.5 "/>
<text text-anchor="middle" x="1783.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1794,-794.5 1794,-932.5 "/>
<text text-anchor="middle" x="1895" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment_end</text>
<polyline fill="none" stroke="#000000" points="1794,-909.5 1996,-909.5 "/>
<text text-anchor="middle" x="1895" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment_start</text>
<polyline fill="none" stroke="#000000" points="1794,-886.5 1996,-886.5 "/>
<text text-anchor="middle" x="1895" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="1794,-863.5 1996,-863.5 "/>
<text text-anchor="middle" x="1895" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure_id</text>
<polyline fill="none" stroke="#000000" points="1794,-840.5 1996,-840.5 "/>
<text text-anchor="middle" x="1895" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="1794,-817.5 1996,-817.5 "/>
<text text-anchor="middle" x="1895" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1996,-794.5 1996,-932.5 "/>
<text text-anchor="middle" x="2006.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1839.8424,-794.4633C1877.6283,-726.9746 1943.4846,-625.6364 2026.5,-564 2061.3775,-538.1045 2076.1159,-540.5184 2118.5,-531 2273.5684,-496.1754 2710.8684,-461.411 2957.2103,-443.8163"/>
<polygon fill="#000000" stroke="#000000" points="2957.6168,-447.2963 2967.3429,-443.0945 2957.1194,-440.3139 2957.6168,-447.2963"/>
<text text-anchor="middle" x="2211.5" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2209.7567,-782.703C2219.396,-705.4294 2246.5121,-591.9188 2322.5,-531 2370.9868,-492.1286 2733.8953,-459.9864 2956.861,-443.6428"/>
<polygon fill="#000000" stroke="#000000" points="2957.3218,-447.1186 2967.0407,-442.9005 2956.8126,-440.1371 2957.3218,-447.1186"/>
<text text-anchor="middle" x="2359" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample_diagnosis -->
<g id="node13" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M12,-1364C12,-1364 445,-1364 445,-1364 451,-1364 457,-1370 457,-1376 457,-1376 457,-1651 457,-1651 457,-1657 451,-1663 445,-1663 445,-1663 12,-1663 12,-1663 6,-1663 0,-1657 0,-1651 0,-1651 0,-1376 0,-1376 0,-1370 6,-1364 12,-1364"/>
<text text-anchor="middle" x="71.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="143,-1364 143,-1663 "/>
<text text-anchor="middle" x="153.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="164,-1364 164,-1663 "/>
<text text-anchor="middle" x="300" y="-1647.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="164,-1640 436,-1640 "/>
<text text-anchor="middle" x="300" y="-1624.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="164,-1617 436,-1617 "/>
<text text-anchor="middle" x="300" y="-1601.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="164,-1594 436,-1594 "/>
<text text-anchor="middle" x="300" y="-1578.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="164,-1571 436,-1571 "/>
<text text-anchor="middle" x="300" y="-1555.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="164,-1548 436,-1548 "/>
<text text-anchor="middle" x="300" y="-1532.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="164,-1525 436,-1525 "/>
<text text-anchor="middle" x="300" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="164,-1502 436,-1502 "/>
<text text-anchor="middle" x="300" y="-1486.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="164,-1479 436,-1479 "/>
<text text-anchor="middle" x="300" y="-1463.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="164,-1456 436,-1456 "/>
<text text-anchor="middle" x="300" y="-1440.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="164,-1433 436,-1433 "/>
<text text-anchor="middle" x="300" y="-1417.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="164,-1410 436,-1410 "/>
<text text-anchor="middle" x="300" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="164,-1387 436,-1387 "/>
<text text-anchor="middle" x="300" y="-1371.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="436,-1364 436,-1663 "/>
<text text-anchor="middle" x="446.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M309.8042,-1363.7176C348.9424,-1306.6852 401.4199,-1247.4271 465.5,-1214 573.4694,-1157.6783 890.8161,-1185.7495 1012.5,-1181 1040.6219,-1179.9024 2001.1459,-1177.1042 2025.5,-1163 2103.2254,-1117.987 2150.9634,-1024.6423 2177.3766,-954.0544"/>
<polygon fill="#000000" stroke="#000000" points="2180.8137,-954.8463 2180.963,-944.2526 2174.2399,-952.441 2180.8137,-954.8463"/>
<text text-anchor="middle" x="1086.5" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
<!-- synonym -->
<g id="node14" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M2840,-1490.5C2840,-1490.5 3141,-1490.5 3141,-1490.5 3147,-1490.5 3153,-1496.5 3153,-1502.5 3153,-1502.5 3153,-1524.5 3153,-1524.5 3153,-1530.5 3147,-1536.5 3141,-1536.5 3141,-1536.5 2840,-1536.5 2840,-1536.5 2834,-1536.5 2828,-1530.5 2828,-1524.5 2828,-1524.5 2828,-1502.5 2828,-1502.5 2828,-1496.5 2834,-1490.5 2840,-1490.5"/>
<text text-anchor="middle" x="2868" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="2908,-1490.5 2908,-1536.5 "/>
<text text-anchor="middle" x="2918.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2929,-1490.5 2929,-1536.5 "/>
<text text-anchor="middle" x="3030.5" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="2929,-1513.5 3132,-1513.5 "/>
<text text-anchor="middle" x="3030.5" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="3132,-1490.5 3132,-1536.5 "/>
<text text-anchor="middle" x="3142.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2984.7723,-1490.3213C2969.1987,-1432.6476 2920.2561,-1282.421 2818.5,-1214 2727.6884,-1152.9381 2683.0827,-1194.6057 2574.5,-1181 2539.8741,-1176.6613 2441.7184,-1189.0515 2418.5,-1163 2374.2174,-1113.3141 2375.9367,-615.1665 2418.5,-564 2485.7284,-483.183 2768.7,-451.6335 2957.3044,-439.465"/>
<polygon fill="#000000" stroke="#000000" points="2957.5769,-442.9549 2967.3359,-438.8303 2957.1348,-435.9689 2957.5769,-442.9549"/>
<text text-anchor="middle" x="2461" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2985.2019,-1490.2519C2970.4951,-1431.7403 2923.1588,-1278.4662 2818.5,-1214 2756.1574,-1175.5991 2559.0887,-1218.7739 2489.5,-1196 2477.9013,-1192.2041 2477.7361,-1185.7633 2466.5,-1181 2433.3452,-1166.9447 2416.7421,-1184.0164 2387.5,-1163 2315.4314,-1111.204 2266.1322,-1021.3989 2237.0218,-953.601"/>
<polygon fill="#000000" stroke="#000000" points="2240.1614,-952.0384 2233.0479,-944.1867 2233.7124,-954.7607 2240.1614,-952.0384"/>
<text text-anchor="middle" x="2532" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge8" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3153.0355,-1510.4377C3589.388,-1498.5181 4770.0925,-1440.7246 5015.5,-1163 5254.7424,-892.2523 4980.2725,-704.598 5054.5,-351 5057.3849,-337.2571 5061.082,-323.2178 5065.2907,-309.2653"/>
<polygon fill="#000000" stroke="#000000" points="5068.6614,-310.2125 5068.2825,-299.6244 5061.9759,-308.1378 5068.6614,-310.2125"/>
<text text-anchor="middle" x="5087" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study_personnel -->
<g id="node15" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M5075,-374.5C5075,-374.5 5382,-374.5 5382,-374.5 5388,-374.5 5394,-380.5 5394,-386.5 5394,-386.5 5394,-477.5 5394,-477.5 5394,-483.5 5388,-489.5 5382,-489.5 5382,-489.5 5075,-489.5 5075,-489.5 5069,-489.5 5063,-483.5 5063,-477.5 5063,-477.5 5063,-386.5 5063,-386.5 5063,-380.5 5069,-374.5 5075,-374.5"/>
<text text-anchor="middle" x="5130" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="5197,-374.5 5197,-489.5 "/>
<text text-anchor="middle" x="5207.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="5218,-374.5 5218,-489.5 "/>
<text text-anchor="middle" x="5295.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="5218,-466.5 5373,-466.5 "/>
<text text-anchor="middle" x="5295.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="5218,-443.5 5373,-443.5 "/>
<text text-anchor="middle" x="5295.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="5218,-420.5 5373,-420.5 "/>
<text text-anchor="middle" x="5295.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="5218,-397.5 5373,-397.5 "/>
<text text-anchor="middle" x="5295.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="5373,-374.5 5373,-489.5 "/>
<text text-anchor="middle" x="5383.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge25" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M5208.6365,-374.2526C5202.0113,-354.9915 5194.2753,-332.5013 5186.3083,-309.3395"/>
<polygon fill="#000000" stroke="#000000" points="5189.5668,-308.0521 5183.0044,-299.7344 5182.9474,-310.3291 5189.5668,-308.0521"/>
<text text-anchor="middle" x="5263" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- study_arm -->
<g id="node16" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M5424,-386C5424,-386 5721,-386 5721,-386 5727,-386 5733,-392 5733,-398 5733,-398 5733,-466 5733,-466 5733,-472 5727,-478 5721,-478 5721,-478 5424,-478 5424,-478 5418,-478 5412,-472 5412,-466 5412,-466 5412,-398 5412,-398 5412,-392 5418,-386 5424,-386"/>
<text text-anchor="middle" x="5458" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="5504,-386 5504,-478 "/>
<text text-anchor="middle" x="5514.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="5525,-386 5525,-478 "/>
<text text-anchor="middle" x="5618.5" y="-462.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="5525,-455 5712,-455 "/>
<text text-anchor="middle" x="5618.5" y="-439.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="5525,-432 5712,-432 "/>
<text text-anchor="middle" x="5618.5" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="5525,-409 5712,-409 "/>
<text text-anchor="middle" x="5618.5" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm_id</text>
<polyline fill="none" stroke="#000000" points="5712,-386 5712,-478 "/>
<text text-anchor="middle" x="5722.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge3" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M5500.1716,-385.7492C5457.9865,-358.7737 5402.3344,-323.1866 5347.0932,-287.8623"/>
<polygon fill="#000000" stroke="#000000" points="5348.9013,-284.8642 5338.591,-282.4255 5345.1302,-290.7615 5348.9013,-284.8642"/>
<text text-anchor="middle" x="5465" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- study_admin -->
<g id="node17" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M5763.5,-351.5C5763.5,-351.5 6089.5,-351.5 6089.5,-351.5 6095.5,-351.5 6101.5,-357.5 6101.5,-363.5 6101.5,-363.5 6101.5,-500.5 6101.5,-500.5 6101.5,-506.5 6095.5,-512.5 6089.5,-512.5 6089.5,-512.5 5763.5,-512.5 5763.5,-512.5 5757.5,-512.5 5751.5,-506.5 5751.5,-500.5 5751.5,-500.5 5751.5,-363.5 5751.5,-363.5 5751.5,-357.5 5757.5,-351.5 5763.5,-351.5"/>
<text text-anchor="middle" x="5805.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="5859.5,-351.5 5859.5,-512.5 "/>
<text text-anchor="middle" x="5870" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="5880.5,-351.5 5880.5,-512.5 "/>
<text text-anchor="middle" x="5980.5" y="-497.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="5880.5,-489.5 6080.5,-489.5 "/>
<text text-anchor="middle" x="5980.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="5880.5,-466.5 6080.5,-466.5 "/>
<text text-anchor="middle" x="5980.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="5880.5,-443.5 6080.5,-443.5 "/>
<text text-anchor="middle" x="5980.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="5880.5,-420.5 6080.5,-420.5 "/>
<text text-anchor="middle" x="5980.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="5880.5,-397.5 6080.5,-397.5 "/>
<text text-anchor="middle" x="5980.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="5880.5,-374.5 6080.5,-374.5 "/>
<text text-anchor="middle" x="5980.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="6080.5,-351.5 6080.5,-512.5 "/>
<text text-anchor="middle" x="6091" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge5" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M5751.3572,-354.435C5748.387,-353.2709 5745.4329,-352.1249 5742.5,-351 5613.3271,-301.4546 5466.0786,-252.7881 5348.5038,-215.7539"/>
<polygon fill="#000000" stroke="#000000" points="5349.2487,-212.3193 5338.6593,-212.6584 5347.1489,-218.9969 5349.2487,-212.3193"/>
<text text-anchor="middle" x="5750" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- molecular_test -->
<g id="node18" class="node">
<title>molecular_test</title>
<path fill="none" stroke="#000000" d="M2524.5,-564.5C2524.5,-564.5 2912.5,-564.5 2912.5,-564.5 2918.5,-564.5 2924.5,-570.5 2924.5,-576.5 2924.5,-576.5 2924.5,-1150.5 2924.5,-1150.5 2924.5,-1156.5 2918.5,-1162.5 2912.5,-1162.5 2912.5,-1162.5 2524.5,-1162.5 2524.5,-1162.5 2518.5,-1162.5 2512.5,-1156.5 2512.5,-1150.5 2512.5,-1150.5 2512.5,-576.5 2512.5,-576.5 2512.5,-570.5 2518.5,-564.5 2524.5,-564.5"/>
<text text-anchor="middle" x="2574" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
<polyline fill="none" stroke="#000000" points="2635.5,-564.5 2635.5,-1162.5 "/>
<text text-anchor="middle" x="2646" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2656.5,-564.5 2656.5,-1162.5 "/>
<text text-anchor="middle" x="2780" y="-1147.3" font-family="Times,serif" font-size="14.00" fill="#000000">aa_change</text>
<polyline fill="none" stroke="#000000" points="2656.5,-1139.5 2903.5,-1139.5 "/>
<text text-anchor="middle" x="2780" y="-1124.3" font-family="Times,serif" font-size="14.00" fill="#000000">antigen</text>
<polyline fill="none" stroke="#000000" points="2656.5,-1116.5 2903.5,-1116.5 "/>
<text text-anchor="middle" x="2780" y="-1101.3" font-family="Times,serif" font-size="14.00" fill="#000000">biospecimen_type</text>
<polyline fill="none" stroke="#000000" points="2656.5,-1093.5 2903.5,-1093.5 "/>
<text text-anchor="middle" x="2780" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000">blood_test_normal_range_lower</text>
<polyline fill="none" stroke="#000000" points="2656.5,-1070.5 2903.5,-1070.5 "/>
<text text-anchor="middle" x="2780" y="-1055.3" font-family="Times,serif" font-size="14.00" fill="#000000">blood_test_normal_range_upper</text>
<polyline fill="none" stroke="#000000" points="2656.5,-1047.5 2903.5,-1047.5 "/>
<text text-anchor="middle" x="2780" y="-1032.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_count</text>
<polyline fill="none" stroke="#000000" points="2656.5,-1024.5 2903.5,-1024.5 "/>
<text text-anchor="middle" x="2780" y="-1009.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome</text>
<polyline fill="none" stroke="#000000" points="2656.5,-1001.5 2903.5,-1001.5 "/>
<text text-anchor="middle" x="2780" y="-986.3" font-family="Times,serif" font-size="14.00" fill="#000000">copy_number</text>
<polyline fill="none" stroke="#000000" points="2656.5,-978.5 2903.5,-978.5 "/>
<text text-anchor="middle" x="2780" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytoband</text>
<polyline fill="none" stroke="#000000" points="2656.5,-955.5 2903.5,-955.5 "/>
<text text-anchor="middle" x="2780" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">exon</text>
<polyline fill="none" stroke="#000000" points="2656.5,-932.5 2903.5,-932.5 "/>
<text text-anchor="middle" x="2780" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">gene_symbol</text>
<polyline fill="none" stroke="#000000" points="2656.5,-909.5 2903.5,-909.5 "/>
<text text-anchor="middle" x="2780" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">histone_family</text>
<polyline fill="none" stroke="#000000" points="2656.5,-886.5 2903.5,-886.5 "/>
<text text-anchor="middle" x="2780" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">histone_variant</text>
<polyline fill="none" stroke="#000000" points="2656.5,-863.5 2903.5,-863.5 "/>
<text text-anchor="middle" x="2780" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">intron</text>
<polyline fill="none" stroke="#000000" points="2656.5,-840.5 2903.5,-840.5 "/>
<text text-anchor="middle" x="2780" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
<polyline fill="none" stroke="#000000" points="2656.5,-817.5 2903.5,-817.5 "/>
<text text-anchor="middle" x="2780" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">loci_abnormal_count</text>
<polyline fill="none" stroke="#000000" points="2656.5,-794.5 2903.5,-794.5 "/>
<text text-anchor="middle" x="2780" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">loci_count</text>
<polyline fill="none" stroke="#000000" points="2656.5,-771.5 2903.5,-771.5 "/>
<text text-anchor="middle" x="2780" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">locus</text>
<polyline fill="none" stroke="#000000" points="2656.5,-748.5 2903.5,-748.5 "/>
<text text-anchor="middle" x="2780" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">mismatch_repair_mutation</text>
<polyline fill="none" stroke="#000000" points="2656.5,-725.5 2903.5,-725.5 "/>
<text text-anchor="middle" x="2780" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_analysis_method</text>
<polyline fill="none" stroke="#000000" points="2656.5,-702.5 2903.5,-702.5 "/>
<text text-anchor="middle" x="2780" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_consequence</text>
<polyline fill="none" stroke="#000000" points="2656.5,-679.5 2903.5,-679.5 "/>
<text text-anchor="middle" x="2780" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test_id</text>
<polyline fill="none" stroke="#000000" points="2656.5,-656.5 2903.5,-656.5 "/>
<text text-anchor="middle" x="2780" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathogenicity</text>
<polyline fill="none" stroke="#000000" points="2656.5,-633.5 2903.5,-633.5 "/>
<text text-anchor="middle" x="2780" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">ploidy</text>
<polyline fill="none" stroke="#000000" points="2656.5,-610.5 2903.5,-610.5 "/>
<text text-anchor="middle" x="2780" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">second_exon</text>
<polyline fill="none" stroke="#000000" points="2656.5,-587.5 2903.5,-587.5 "/>
<text text-anchor="middle" x="2780" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 11 properties</text>
<polyline fill="none" stroke="#000000" points="2903.5,-564.5 2903.5,-1162.5 "/>
<text text-anchor="middle" x="2914" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2924.5642,-572.8063C2927.5286,-569.8274 2930.5076,-566.8905 2933.5,-564 2959.7101,-538.6817 2991.3651,-515.1396 3021.6011,-495.1554"/>
<polygon fill="#000000" stroke="#000000" points="3023.6266,-498.0129 3030.0858,-489.6147 3019.7993,-492.1519 3023.6266,-498.0129"/>
<text text-anchor="middle" x="3031.5" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- publication -->
<g id="node19" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M6132,-409C6132,-409 6365,-409 6365,-409 6371,-409 6377,-415 6377,-421 6377,-421 6377,-443 6377,-443 6377,-449 6371,-455 6365,-455 6365,-455 6132,-455 6132,-455 6126,-455 6120,-449 6120,-443 6120,-443 6120,-421 6120,-421 6120,-415 6126,-409 6132,-409"/>
<text text-anchor="middle" x="6168.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="6217,-409 6217,-455 "/>
<text text-anchor="middle" x="6227.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="6238,-409 6238,-455 "/>
<text text-anchor="middle" x="6297" y="-439.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication_id</text>
<polyline fill="none" stroke="#000000" points="6238,-432 6356,-432 "/>
<text text-anchor="middle" x="6297" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="6356,-409 6356,-455 "/>
<text text-anchor="middle" x="6366.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge1" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M6216.3075,-408.9695C6189.28,-390.6759 6149.0122,-365.7886 6110.5,-351 5858.424,-254.2034 5551.0389,-200.814 5348.7429,-173.8278"/>
<polygon fill="#000000" stroke="#000000" points="5348.961,-170.3263 5338.5882,-172.4836 5348.0424,-177.2657 5348.961,-170.3263"/>
<text text-anchor="middle" x="6110.5" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- medical_history -->
<g id="node20" class="node">
<title>medical_history</title>
<path fill="none" stroke="#000000" d="M2954.5,-829C2954.5,-829 3308.5,-829 3308.5,-829 3314.5,-829 3320.5,-835 3320.5,-841 3320.5,-841 3320.5,-886 3320.5,-886 3320.5,-892 3314.5,-898 3308.5,-898 3308.5,-898 2954.5,-898 2954.5,-898 2948.5,-898 2942.5,-892 2942.5,-886 2942.5,-886 2942.5,-841 2942.5,-841 2942.5,-835 2948.5,-829 2954.5,-829"/>
<text text-anchor="middle" x="3008" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
<polyline fill="none" stroke="#000000" points="3073.5,-829 3073.5,-898 "/>
<text text-anchor="middle" x="3084" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3094.5,-829 3094.5,-898 "/>
<text text-anchor="middle" x="3197" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_category</text>
<polyline fill="none" stroke="#000000" points="3094.5,-875 3299.5,-875 "/>
<text text-anchor="middle" x="3197" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_condition</text>
<polyline fill="none" stroke="#000000" points="3094.5,-852 3299.5,-852 "/>
<text text-anchor="middle" x="3197" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_id</text>
<polyline fill="none" stroke="#000000" points="3299.5,-829 3299.5,-898 "/>
<text text-anchor="middle" x="3310" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3131.5,-828.918C3131.5,-757.5964 3131.5,-593.0577 3131.5,-499.7651"/>
<polygon fill="#000000" stroke="#000000" points="3135.0001,-499.5822 3131.5,-489.5822 3128.0001,-499.5822 3135.0001,-499.5822"/>
<text text-anchor="middle" x="3199.5" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node22" class="node">
<title>single_cell_sequencing_file</title>
<path fill="none" stroke="#000000" d="M487,-1214.5C487,-1214.5 1096,-1214.5 1096,-1214.5 1102,-1214.5 1108,-1220.5 1108,-1226.5 1108,-1226.5 1108,-1800.5 1108,-1800.5 1108,-1806.5 1102,-1812.5 1096,-1812.5 1096,-1812.5 487,-1812.5 487,-1812.5 481,-1812.5 475,-1806.5 475,-1800.5 475,-1800.5 475,-1226.5 475,-1226.5 475,-1220.5 481,-1214.5 487,-1214.5"/>
<text text-anchor="middle" x="581" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
<polyline fill="none" stroke="#000000" points="687,-1214.5 687,-1812.5 "/>
<text text-anchor="middle" x="697.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="708,-1214.5 708,-1812.5 "/>
<text text-anchor="middle" x="897.5" y="-1797.3" font-family="Times,serif" font-size="14.00" fill="#000000">Cell_Barcode</text>
<polyline fill="none" stroke="#000000" points="708,-1789.5 1087,-1789.5 "/>
<text text-anchor="middle" x="897.5" y="-1774.3" font-family="Times,serif" font-size="14.00" fill="#000000">Cryopreserved_Cells_in_Sample</text>
<polyline fill="none" stroke="#000000" points="708,-1766.5 1087,-1766.5 "/>
<text text-anchor="middle" x="897.5" y="-1751.3" font-family="Times,serif" font-size="14.00" fill="#000000">Dissociation_Method</text>
<polyline fill="none" stroke="#000000" points="708,-1743.5 1087,-1743.5 "/>
<text text-anchor="middle" x="897.5" y="-1728.3" font-family="Times,serif" font-size="14.00" fill="#000000">End_Bias</text>
<polyline fill="none" stroke="#000000" points="708,-1720.5 1087,-1720.5 "/>
<text text-anchor="middle" x="897.5" y="-1705.3" font-family="Times,serif" font-size="14.00" fill="#000000">Input_Cells_and_Nuclei</text>
<polyline fill="none" stroke="#000000" points="708,-1697.5 1087,-1697.5 "/>
<text text-anchor="middle" x="897.5" y="-1682.3" font-family="Times,serif" font-size="14.00" fill="#000000">Library_Construction_Method</text>
<polyline fill="none" stroke="#000000" points="708,-1674.5 1087,-1674.5 "/>
<text text-anchor="middle" x="897.5" y="-1659.3" font-family="Times,serif" font-size="14.00" fill="#000000">Library_Preparation_Date</text>
<polyline fill="none" stroke="#000000" points="708,-1651.5 1087,-1651.5 "/>
<text text-anchor="middle" x="897.5" y="-1636.3" font-family="Times,serif" font-size="14.00" fill="#000000">Nucleic_Acid_Capture_Date</text>
<polyline fill="none" stroke="#000000" points="708,-1628.5 1087,-1628.5 "/>
<text text-anchor="middle" x="897.5" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">Paired_End</text>
<polyline fill="none" stroke="#000000" points="708,-1605.5 1087,-1605.5 "/>
<text text-anchor="middle" x="897.5" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">Protocols_Link</text>
<polyline fill="none" stroke="#000000" points="708,-1582.5 1087,-1582.5 "/>
<text text-anchor="middle" x="897.5" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">Read1</text>
<polyline fill="none" stroke="#000000" points="708,-1559.5 1087,-1559.5 "/>
<text text-anchor="middle" x="897.5" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">Read2</text>
<polyline fill="none" stroke="#000000" points="708,-1536.5 1087,-1536.5 "/>
<text text-anchor="middle" x="897.5" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Feature_barcoding</text>
<polyline fill="none" stroke="#000000" points="708,-1513.5 1087,-1513.5 "/>
<text text-anchor="middle" x="897.5" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Oligo_dT_Poly_dT</text>
<polyline fill="none" stroke="#000000" points="708,-1490.5 1087,-1490.5 "/>
<text text-anchor="middle" x="897.5" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Random</text>
<polyline fill="none" stroke="#000000" points="708,-1467.5 1087,-1467.5 "/>
<text text-anchor="middle" x="897.5" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">Sequencing_Library_Construction_Date</text>
<polyline fill="none" stroke="#000000" points="708,-1444.5 1087,-1444.5 "/>
<text text-anchor="middle" x="897.5" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">Single_Cell_Dissociation_Date</text>
<polyline fill="none" stroke="#000000" points="708,-1421.5 1087,-1421.5 "/>
<text text-anchor="middle" x="897.5" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">Single_Cell_Isolation_Method</text>
<polyline fill="none" stroke="#000000" points="708,-1398.5 1087,-1398.5 "/>
<text text-anchor="middle" x="897.5" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">Spike_In</text>
<polyline fill="none" stroke="#000000" points="708,-1375.5 1087,-1375.5 "/>
<text text-anchor="middle" x="897.5" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">Total_Number_of_Input_Cells</text>
<polyline fill="none" stroke="#000000" points="708,-1352.5 1087,-1352.5 "/>
<text text-anchor="middle" x="897.5" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">UMI</text>
<polyline fill="none" stroke="#000000" points="708,-1329.5 1087,-1329.5 "/>
<text text-anchor="middle" x="897.5" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="708,-1306.5 1087,-1306.5 "/>
<text text-anchor="middle" x="897.5" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">cDNA_Length</text>
<polyline fill="none" stroke="#000000" points="708,-1283.5 1087,-1283.5 "/>
<text text-anchor="middle" x="897.5" y="-1268.3" font-family="Times,serif" font-size="14.00" fill="#000000">cDNA_Offset</text>
<polyline fill="none" stroke="#000000" points="708,-1260.5 1087,-1260.5 "/>
<text text-anchor="middle" x="897.5" y="-1245.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="708,-1237.5 1087,-1237.5 "/>
<text text-anchor="middle" x="897.5" y="-1222.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 24 properties</text>
<polyline fill="none" stroke="#000000" points="1087,-1214.5 1087,-1812.5 "/>
<text text-anchor="middle" x="1097.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1108.2465,-1218.1304C1110.9905,-1216.7234 1113.7418,-1215.3462 1116.5,-1214 1197.4623,-1174.4848 1226.8108,-1189.4968 1316.5,-1181 1355.7259,-1177.2839 1991.479,-1182.876 2025.5,-1163 2103.0534,-1117.6913 2150.8187,-1024.3935 2177.2853,-953.8973"/>
<polygon fill="#000000" stroke="#000000" points="2180.7181,-954.7023 2180.8794,-944.1087 2174.1471,-952.2896 2180.7181,-954.7023"/>
<text text-anchor="middle" x="1425" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- family_relationship -->
<g id="node23" class="node">
<title>family_relationship</title>
<path fill="none" stroke="#000000" d="M3351,-817.5C3351,-817.5 3720,-817.5 3720,-817.5 3726,-817.5 3732,-823.5 3732,-829.5 3732,-829.5 3732,-897.5 3732,-897.5 3732,-903.5 3726,-909.5 3720,-909.5 3720,-909.5 3351,-909.5 3351,-909.5 3345,-909.5 3339,-903.5 3339,-897.5 3339,-897.5 3339,-829.5 3339,-829.5 3339,-823.5 3345,-817.5 3351,-817.5"/>
<text text-anchor="middle" x="3416" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
<polyline fill="none" stroke="#000000" points="3493,-817.5 3493,-909.5 "/>
<text text-anchor="middle" x="3503.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3514,-817.5 3514,-909.5 "/>
<text text-anchor="middle" x="3612.5" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_id</text>
<polyline fill="none" stroke="#000000" points="3514,-886.5 3711,-886.5 "/>
<text text-anchor="middle" x="3612.5" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship_id</text>
<polyline fill="none" stroke="#000000" points="3514,-863.5 3711,-863.5 "/>
<text text-anchor="middle" x="3612.5" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">related_to_participant_id</text>
<polyline fill="none" stroke="#000000" points="3514,-840.5 3711,-840.5 "/>
<text text-anchor="middle" x="3612.5" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">relationship</text>
<polyline fill="none" stroke="#000000" points="3711,-817.5 3711,-909.5 "/>
<text text-anchor="middle" x="3721.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3511.1914,-817.4102C3476.6933,-754.9289 3408.8311,-642.1893 3329.5,-564 3303.6803,-538.552 3272.2975,-515.0406 3242.199,-495.1282"/>
<polygon fill="#000000" stroke="#000000" points="3244.0356,-492.1474 3233.7494,-489.6087 3240.2074,-498.0078 3244.0356,-492.1474"/>
<text text-anchor="middle" x="3385" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
</g>
</svg>
</div>
