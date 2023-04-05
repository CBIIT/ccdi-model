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
<svg width="6000pt" height="1821pt"
 viewBox="0.00 0.00 6000.08 1821.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1817)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1817 5996.0832,-1817 5996.0832,4 -4,4"/>
<!-- sample -->
<g id="node1" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M4090.5832,-783C4090.5832,-783 4404.5832,-783 4404.5832,-783 4410.5832,-783 4416.5832,-789 4416.5832,-795 4416.5832,-795 4416.5832,-932 4416.5832,-932 4416.5832,-938 4410.5832,-944 4404.5832,-944 4404.5832,-944 4090.5832,-944 4090.5832,-944 4084.5832,-944 4078.5832,-938 4078.5832,-932 4078.5832,-932 4078.5832,-795 4078.5832,-795 4078.5832,-789 4084.5832,-783 4090.5832,-783"/>
<text text-anchor="middle" x="4112.5832" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="4146.5832,-783 4146.5832,-944 "/>
<text text-anchor="middle" x="4157.0832" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4167.5832,-783 4167.5832,-944 "/>
<text text-anchor="middle" x="4281.5832" y="-928.8" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="4167.5832,-921 4395.5832,-921 "/>
<text text-anchor="middle" x="4281.5832" y="-905.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="4167.5832,-898 4395.5832,-898 "/>
<text text-anchor="middle" x="4281.5832" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="4167.5832,-875 4395.5832,-875 "/>
<text text-anchor="middle" x="4281.5832" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="4167.5832,-852 4395.5832,-852 "/>
<text text-anchor="middle" x="4281.5832" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="4167.5832,-829 4395.5832,-829 "/>
<text text-anchor="middle" x="4281.5832" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="4167.5832,-806 4395.5832,-806 "/>
<text text-anchor="middle" x="4281.5832" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="4395.5832,-783 4395.5832,-944 "/>
<text text-anchor="middle" x="4406.0832" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node16" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M1729.5832,-374.5C1729.5832,-374.5 2033.5832,-374.5 2033.5832,-374.5 2039.5832,-374.5 2045.5832,-380.5 2045.5832,-386.5 2045.5832,-386.5 2045.5832,-477.5 2045.5832,-477.5 2045.5832,-483.5 2039.5832,-489.5 2033.5832,-489.5 2033.5832,-489.5 1729.5832,-489.5 1729.5832,-489.5 1723.5832,-489.5 1717.5832,-483.5 1717.5832,-477.5 1717.5832,-477.5 1717.5832,-386.5 1717.5832,-386.5 1717.5832,-380.5 1723.5832,-374.5 1729.5832,-374.5"/>
<text text-anchor="middle" x="1765.5832" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1813.5832,-374.5 1813.5832,-489.5 "/>
<text text-anchor="middle" x="1824.0832" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1834.5832,-374.5 1834.5832,-489.5 "/>
<text text-anchor="middle" x="1929.5832" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="1834.5832,-466.5 2024.5832,-466.5 "/>
<text text-anchor="middle" x="1929.5832" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="1834.5832,-443.5 2024.5832,-443.5 "/>
<text text-anchor="middle" x="1929.5832" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="1834.5832,-420.5 2024.5832,-420.5 "/>
<text text-anchor="middle" x="1929.5832" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1834.5832,-397.5 2024.5832,-397.5 "/>
<text text-anchor="middle" x="1929.5832" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="2024.5832,-374.5 2024.5832,-489.5 "/>
<text text-anchor="middle" x="2035.0832" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M4078.5164,-784.476C3947.7636,-723.604 3762.0608,-637.6787 3598.5832,-564 3565.3821,-549.0364 3559.1746,-538.7119 3523.5832,-531 3364.0508,-496.4328 2213.7006,-549.4302 2054.5832,-513 2034.8585,-508.484 2014.7086,-501.5193 1995.4568,-493.5298"/>
<polygon fill="#000000" stroke="#000000" points="1996.6552,-490.2359 1986.0838,-489.5315 1993.9086,-496.6746 1996.6552,-490.2359"/>
<text text-anchor="middle" x="3600.0832" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample_diagnosis -->
<g id="node2" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M5547.0832,-1375.5C5547.0832,-1375.5 5980.0832,-1375.5 5980.0832,-1375.5 5986.0832,-1375.5 5992.0832,-1381.5 5992.0832,-1387.5 5992.0832,-1387.5 5992.0832,-1639.5 5992.0832,-1639.5 5992.0832,-1645.5 5986.0832,-1651.5 5980.0832,-1651.5 5980.0832,-1651.5 5547.0832,-1651.5 5547.0832,-1651.5 5541.0832,-1651.5 5535.0832,-1645.5 5535.0832,-1639.5 5535.0832,-1639.5 5535.0832,-1387.5 5535.0832,-1387.5 5535.0832,-1381.5 5541.0832,-1375.5 5547.0832,-1375.5"/>
<text text-anchor="middle" x="5606.5832" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="5678.0832,-1375.5 5678.0832,-1651.5 "/>
<text text-anchor="middle" x="5688.5832" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="5699.0832,-1375.5 5699.0832,-1651.5 "/>
<text text-anchor="middle" x="5835.0832" y="-1636.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="5699.0832,-1628.5 5971.0832,-1628.5 "/>
<text text-anchor="middle" x="5835.0832" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="5699.0832,-1605.5 5971.0832,-1605.5 "/>
<text text-anchor="middle" x="5835.0832" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="5699.0832,-1582.5 5971.0832,-1582.5 "/>
<text text-anchor="middle" x="5835.0832" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="5699.0832,-1559.5 5971.0832,-1559.5 "/>
<text text-anchor="middle" x="5835.0832" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="5699.0832,-1536.5 5971.0832,-1536.5 "/>
<text text-anchor="middle" x="5835.0832" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="5699.0832,-1513.5 5971.0832,-1513.5 "/>
<text text-anchor="middle" x="5835.0832" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="5699.0832,-1490.5 5971.0832,-1490.5 "/>
<text text-anchor="middle" x="5835.0832" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="5699.0832,-1467.5 5971.0832,-1467.5 "/>
<text text-anchor="middle" x="5835.0832" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="5699.0832,-1444.5 5971.0832,-1444.5 "/>
<text text-anchor="middle" x="5835.0832" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="5699.0832,-1421.5 5971.0832,-1421.5 "/>
<text text-anchor="middle" x="5835.0832" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="5699.0832,-1398.5 5971.0832,-1398.5 "/>
<text text-anchor="middle" x="5835.0832" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="5971.0832,-1375.5 5971.0832,-1651.5 "/>
<text text-anchor="middle" x="5981.5832" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge24" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M5682.3101,-1375.4772C5642.1011,-1317.9785 5588.798,-1255.1557 5526.5832,-1214 5180.5895,-985.122 4688.0392,-904.7965 4426.6393,-877.2932"/>
<polygon fill="#000000" stroke="#000000" points="4426.9791,-873.8098 4416.6711,-876.2582 4426.2562,-880.7723 4426.9791,-873.8098"/>
<text text-anchor="middle" x="5570.5832" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
<!-- synonym -->
<g id="node3" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M2851.0832,-1490.5C2851.0832,-1490.5 3152.0832,-1490.5 3152.0832,-1490.5 3158.0832,-1490.5 3164.0832,-1496.5 3164.0832,-1502.5 3164.0832,-1502.5 3164.0832,-1524.5 3164.0832,-1524.5 3164.0832,-1530.5 3158.0832,-1536.5 3152.0832,-1536.5 3152.0832,-1536.5 2851.0832,-1536.5 2851.0832,-1536.5 2845.0832,-1536.5 2839.0832,-1530.5 2839.0832,-1524.5 2839.0832,-1524.5 2839.0832,-1502.5 2839.0832,-1502.5 2839.0832,-1496.5 2845.0832,-1490.5 2851.0832,-1490.5"/>
<text text-anchor="middle" x="2879.0832" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="2919.0832,-1490.5 2919.0832,-1536.5 "/>
<text text-anchor="middle" x="2929.5832" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2940.0832,-1490.5 2940.0832,-1536.5 "/>
<text text-anchor="middle" x="3041.5832" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="2940.0832,-1513.5 3143.0832,-1513.5 "/>
<text text-anchor="middle" x="3041.5832" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="3143.0832,-1490.5 3143.0832,-1536.5 "/>
<text text-anchor="middle" x="3153.5832" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3006.7942,-1490.238C3021.2834,-1431.6937 3068.0601,-1278.3492 3172.5832,-1214 3205.5542,-1193.7016 3482.8491,-1204.6745 3520.5832,-1196 3735.71,-1146.5455 3964.1378,-1030.2032 4106.3059,-949.172"/>
<polygon fill="#000000" stroke="#000000" points="4108.1788,-952.1329 4115.1213,-944.1297 4104.7032,-946.0566 4108.1788,-952.1329"/>
<text text-anchor="middle" x="3605.0832" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3007.4719,-1490.082C3023.262,-1432.5219 3072.3135,-1283.7514 3172.5832,-1214 3286.8469,-1134.5139 3391.5299,-1269.1349 3481.5832,-1163 3653.8225,-960.0027 3659.0214,-762.469 3481.5832,-564 3437.7648,-514.9881 3253.193,-535.1937 3187.5832,-531 3061.9349,-522.9688 2177.2612,-541.3219 2054.5832,-513 2035.0056,-508.4802 2015.0049,-501.563 1995.8779,-493.6362"/>
<polygon fill="#000000" stroke="#000000" points="1997.136,-490.3679 1986.5642,-489.6699 1994.3933,-496.8082 1997.136,-490.3679"/>
<text text-anchor="middle" x="3656.0832" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study -->
<g id="node20" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M1128.5832,-.5C1128.5832,-.5 1518.5832,-.5 1518.5832,-.5 1524.5832,-.5 1530.5832,-6.5 1530.5832,-12.5 1530.5832,-12.5 1530.5832,-287.5 1530.5832,-287.5 1530.5832,-293.5 1524.5832,-299.5 1518.5832,-299.5 1518.5832,-299.5 1128.5832,-299.5 1128.5832,-299.5 1122.5832,-299.5 1116.5832,-293.5 1116.5832,-287.5 1116.5832,-287.5 1116.5832,-12.5 1116.5832,-12.5 1116.5832,-6.5 1122.5832,-.5 1128.5832,-.5"/>
<text text-anchor="middle" x="1144.5832" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="1172.5832,-.5 1172.5832,-299.5 "/>
<text text-anchor="middle" x="1183.0832" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1193.5832,-.5 1193.5832,-299.5 "/>
<text text-anchor="middle" x="1351.5832" y="-284.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="1193.5832,-276.5 1509.5832,-276.5 "/>
<text text-anchor="middle" x="1351.5832" y="-261.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="1193.5832,-253.5 1509.5832,-253.5 "/>
<text text-anchor="middle" x="1351.5832" y="-238.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_number</text>
<polyline fill="none" stroke="#000000" points="1193.5832,-230.5 1509.5832,-230.5 "/>
<text text-anchor="middle" x="1351.5832" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="1193.5832,-207.5 1509.5832,-207.5 "/>
<text text-anchor="middle" x="1351.5832" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="1193.5832,-184.5 1509.5832,-184.5 "/>
<text text-anchor="middle" x="1351.5832" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="1193.5832,-161.5 1509.5832,-161.5 "/>
<text text-anchor="middle" x="1351.5832" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="1193.5832,-138.5 1509.5832,-138.5 "/>
<text text-anchor="middle" x="1351.5832" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="1193.5832,-115.5 1509.5832,-115.5 "/>
<text text-anchor="middle" x="1351.5832" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="1193.5832,-92.5 1509.5832,-92.5 "/>
<text text-anchor="middle" x="1351.5832" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="1193.5832,-69.5 1509.5832,-69.5 "/>
<text text-anchor="middle" x="1351.5832" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="1193.5832,-46.5 1509.5832,-46.5 "/>
<text text-anchor="middle" x="1351.5832" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="1193.5832,-23.5 1509.5832,-23.5 "/>
<text text-anchor="middle" x="1351.5832" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="1509.5832,-.5 1509.5832,-299.5 "/>
<text text-anchor="middle" x="1520.0832" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge12" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2839.0273,-1506.1316C2255.886,-1478.0599 293.9928,-1368.8689 111.5832,-1163 -64.9687,-963.7421 -6.0417,-802.8276 111.5832,-564 180.1995,-424.6805 248.4711,-417.9829 388.5832,-351 619.1933,-240.7531 910.572,-190.414 1106.2351,-167.7993"/>
<polygon fill="#000000" stroke="#000000" points="1106.8148,-171.256 1116.3535,-166.6447 1106.0211,-164.3011 1106.8148,-171.256"/>
<text text-anchor="middle" x="172.0832" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node4" class="node">
<title>single_cell_sequencing_file</title>
<path fill="none" stroke="#000000" d="M3194.0832,-1214.5C3194.0832,-1214.5 3803.0832,-1214.5 3803.0832,-1214.5 3809.0832,-1214.5 3815.0832,-1220.5 3815.0832,-1226.5 3815.0832,-1226.5 3815.0832,-1800.5 3815.0832,-1800.5 3815.0832,-1806.5 3809.0832,-1812.5 3803.0832,-1812.5 3803.0832,-1812.5 3194.0832,-1812.5 3194.0832,-1812.5 3188.0832,-1812.5 3182.0832,-1806.5 3182.0832,-1800.5 3182.0832,-1800.5 3182.0832,-1226.5 3182.0832,-1226.5 3182.0832,-1220.5 3188.0832,-1214.5 3194.0832,-1214.5"/>
<text text-anchor="middle" x="3288.0832" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
<polyline fill="none" stroke="#000000" points="3394.0832,-1214.5 3394.0832,-1812.5 "/>
<text text-anchor="middle" x="3404.5832" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3415.0832,-1214.5 3415.0832,-1812.5 "/>
<text text-anchor="middle" x="3604.5832" y="-1797.3" font-family="Times,serif" font-size="14.00" fill="#000000">Cell_Barcode</text>
<polyline fill="none" stroke="#000000" points="3415.0832,-1789.5 3794.0832,-1789.5 "/>
<text text-anchor="middle" x="3604.5832" y="-1774.3" font-family="Times,serif" font-size="14.00" fill="#000000">Cryopreserved_Cells_in_Sample</text>
<polyline fill="none" stroke="#000000" points="3415.0832,-1766.5 3794.0832,-1766.5 "/>
<text text-anchor="middle" x="3604.5832" y="-1751.3" font-family="Times,serif" font-size="14.00" fill="#000000">Dissociation_Method</text>
<polyline fill="none" stroke="#000000" points="3415.0832,-1743.5 3794.0832,-1743.5 "/>
<text text-anchor="middle" x="3604.5832" y="-1728.3" font-family="Times,serif" font-size="14.00" fill="#000000">End_Bias</text>
<polyline fill="none" stroke="#000000" points="3415.0832,-1720.5 3794.0832,-1720.5 "/>
<text text-anchor="middle" x="3604.5832" y="-1705.3" font-family="Times,serif" font-size="14.00" fill="#000000">Input_Cells_and_Nuclei</text>
<polyline fill="none" stroke="#000000" points="3415.0832,-1697.5 3794.0832,-1697.5 "/>
<text text-anchor="middle" x="3604.5832" y="-1682.3" font-family="Times,serif" font-size="14.00" fill="#000000">Library_Construction_Method</text>
<polyline fill="none" stroke="#000000" points="3415.0832,-1674.5 3794.0832,-1674.5 "/>
<text text-anchor="middle" x="3604.5832" y="-1659.3" font-family="Times,serif" font-size="14.00" fill="#000000">Library_Preparation_Date</text>
<polyline fill="none" stroke="#000000" points="3415.0832,-1651.5 3794.0832,-1651.5 "/>
<text text-anchor="middle" x="3604.5832" y="-1636.3" font-family="Times,serif" font-size="14.00" fill="#000000">Nucleic_Acid_Capture_Date</text>
<polyline fill="none" stroke="#000000" points="3415.0832,-1628.5 3794.0832,-1628.5 "/>
<text text-anchor="middle" x="3604.5832" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">Paired_End</text>
<polyline fill="none" stroke="#000000" points="3415.0832,-1605.5 3794.0832,-1605.5 "/>
<text text-anchor="middle" x="3604.5832" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">Protocols_Link</text>
<polyline fill="none" stroke="#000000" points="3415.0832,-1582.5 3794.0832,-1582.5 "/>
<text text-anchor="middle" x="3604.5832" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">Read1</text>
<polyline fill="none" stroke="#000000" points="3415.0832,-1559.5 3794.0832,-1559.5 "/>
<text text-anchor="middle" x="3604.5832" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">Read2</text>
<polyline fill="none" stroke="#000000" points="3415.0832,-1536.5 3794.0832,-1536.5 "/>
<text text-anchor="middle" x="3604.5832" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Feature_barcoding</text>
<polyline fill="none" stroke="#000000" points="3415.0832,-1513.5 3794.0832,-1513.5 "/>
<text text-anchor="middle" x="3604.5832" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Oligo_dT_Poly_dT</text>
<polyline fill="none" stroke="#000000" points="3415.0832,-1490.5 3794.0832,-1490.5 "/>
<text text-anchor="middle" x="3604.5832" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Random</text>
<polyline fill="none" stroke="#000000" points="3415.0832,-1467.5 3794.0832,-1467.5 "/>
<text text-anchor="middle" x="3604.5832" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">Sequencing_Library_Construction_Date</text>
<polyline fill="none" stroke="#000000" points="3415.0832,-1444.5 3794.0832,-1444.5 "/>
<text text-anchor="middle" x="3604.5832" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">Single_Cell_Dissociation_Date</text>
<polyline fill="none" stroke="#000000" points="3415.0832,-1421.5 3794.0832,-1421.5 "/>
<text text-anchor="middle" x="3604.5832" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">Single_Cell_Isolation_Method</text>
<polyline fill="none" stroke="#000000" points="3415.0832,-1398.5 3794.0832,-1398.5 "/>
<text text-anchor="middle" x="3604.5832" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">Spike_In</text>
<polyline fill="none" stroke="#000000" points="3415.0832,-1375.5 3794.0832,-1375.5 "/>
<text text-anchor="middle" x="3604.5832" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">Total_Number_of_Input_Cells</text>
<polyline fill="none" stroke="#000000" points="3415.0832,-1352.5 3794.0832,-1352.5 "/>
<text text-anchor="middle" x="3604.5832" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">UMI</text>
<polyline fill="none" stroke="#000000" points="3415.0832,-1329.5 3794.0832,-1329.5 "/>
<text text-anchor="middle" x="3604.5832" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="3415.0832,-1306.5 3794.0832,-1306.5 "/>
<text text-anchor="middle" x="3604.5832" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">cDNA_Length</text>
<polyline fill="none" stroke="#000000" points="3415.0832,-1283.5 3794.0832,-1283.5 "/>
<text text-anchor="middle" x="3604.5832" y="-1268.3" font-family="Times,serif" font-size="14.00" fill="#000000">cDNA_Offset</text>
<polyline fill="none" stroke="#000000" points="3415.0832,-1260.5 3794.0832,-1260.5 "/>
<text text-anchor="middle" x="3604.5832" y="-1245.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="3415.0832,-1237.5 3794.0832,-1237.5 "/>
<text text-anchor="middle" x="3604.5832" y="-1222.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 24 properties</text>
<polyline fill="none" stroke="#000000" points="3794.0832,-1214.5 3794.0832,-1812.5 "/>
<text text-anchor="middle" x="3804.5832" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3815.3178,-1221.2317C3818.082,-1218.8079 3820.8376,-1216.3968 3823.5832,-1214 3928.9352,-1122.0299 4052.487,-1020.5984 4138.9506,-950.6189"/>
<polygon fill="#000000" stroke="#000000" points="4141.3643,-953.1682 4146.9382,-944.1581 4136.9621,-947.7256 4141.3643,-953.1682"/>
<text text-anchor="middle" x="3966.0832" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- methylation_array_file -->
<g id="node5" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M3845.0832,-1387C3845.0832,-1387 4240.0832,-1387 4240.0832,-1387 4246.0832,-1387 4252.0832,-1393 4252.0832,-1399 4252.0832,-1399 4252.0832,-1628 4252.0832,-1628 4252.0832,-1634 4246.0832,-1640 4240.0832,-1640 4240.0832,-1640 3845.0832,-1640 3845.0832,-1640 3839.0832,-1640 3833.0832,-1634 3833.0832,-1628 3833.0832,-1628 3833.0832,-1399 3833.0832,-1399 3833.0832,-1393 3839.0832,-1387 3845.0832,-1387"/>
<text text-anchor="middle" x="3922.0832" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="4011.0832,-1387 4011.0832,-1640 "/>
<text text-anchor="middle" x="4021.5832" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4032.0832,-1387 4032.0832,-1640 "/>
<text text-anchor="middle" x="4131.5832" y="-1624.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="4032.0832,-1617 4231.0832,-1617 "/>
<text text-anchor="middle" x="4131.5832" y="-1601.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="4032.0832,-1594 4231.0832,-1594 "/>
<text text-anchor="middle" x="4131.5832" y="-1578.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="4032.0832,-1571 4231.0832,-1571 "/>
<text text-anchor="middle" x="4131.5832" y="-1555.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="4032.0832,-1548 4231.0832,-1548 "/>
<text text-anchor="middle" x="4131.5832" y="-1532.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="4032.0832,-1525 4231.0832,-1525 "/>
<text text-anchor="middle" x="4131.5832" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="4032.0832,-1502 4231.0832,-1502 "/>
<text text-anchor="middle" x="4131.5832" y="-1486.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="4032.0832,-1479 4231.0832,-1479 "/>
<text text-anchor="middle" x="4131.5832" y="-1463.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="4032.0832,-1456 4231.0832,-1456 "/>
<text text-anchor="middle" x="4131.5832" y="-1440.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file_id</text>
<polyline fill="none" stroke="#000000" points="4032.0832,-1433 4231.0832,-1433 "/>
<text text-anchor="middle" x="4131.5832" y="-1417.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="4032.0832,-1410 4231.0832,-1410 "/>
<text text-anchor="middle" x="4131.5832" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="4231.0832,-1387 4231.0832,-1640 "/>
<text text-anchor="middle" x="4241.5832" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M4082.5959,-1386.6304C4122.7328,-1259.3672 4183.541,-1066.5608 4219.0393,-954.0053"/>
<polygon fill="#000000" stroke="#000000" points="4222.4076,-954.9615 4222.0775,-944.3718 4215.7317,-952.856 4222.4076,-954.9615"/>
<text text-anchor="middle" x="4237.0832" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study_arm -->
<g id="node6" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M694.0832,-386C694.0832,-386 991.0832,-386 991.0832,-386 997.0832,-386 1003.0832,-392 1003.0832,-398 1003.0832,-398 1003.0832,-466 1003.0832,-466 1003.0832,-472 997.0832,-478 991.0832,-478 991.0832,-478 694.0832,-478 694.0832,-478 688.0832,-478 682.0832,-472 682.0832,-466 682.0832,-466 682.0832,-398 682.0832,-398 682.0832,-392 688.0832,-386 694.0832,-386"/>
<text text-anchor="middle" x="728.0832" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="774.0832,-386 774.0832,-478 "/>
<text text-anchor="middle" x="784.5832" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="795.0832,-386 795.0832,-478 "/>
<text text-anchor="middle" x="888.5832" y="-462.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="795.0832,-455 982.0832,-455 "/>
<text text-anchor="middle" x="888.5832" y="-439.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="795.0832,-432 982.0832,-432 "/>
<text text-anchor="middle" x="888.5832" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="795.0832,-409 982.0832,-409 "/>
<text text-anchor="middle" x="888.5832" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm_id</text>
<polyline fill="none" stroke="#000000" points="982.0832,-386 982.0832,-478 "/>
<text text-anchor="middle" x="992.5832" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M921.2032,-385.9068C972.123,-356.0536 1041.1135,-315.606 1107.5817,-276.6371"/>
<polygon fill="#000000" stroke="#000000" points="1109.6609,-279.4753 1116.5175,-271.3982 1106.1206,-273.4366 1109.6609,-279.4753"/>
<text text-anchor="middle" x="1075.0832" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- exposure -->
<g id="node7" class="node">
<title>exposure</title>
<path fill="none" stroke="#000000" d="M548.0832,-622C548.0832,-622 959.0832,-622 959.0832,-622 965.0832,-622 971.0832,-628 971.0832,-634 971.0832,-634 971.0832,-1093 971.0832,-1093 971.0832,-1099 965.0832,-1105 959.0832,-1105 959.0832,-1105 548.0832,-1105 548.0832,-1105 542.0832,-1105 536.0832,-1099 536.0832,-1093 536.0832,-1093 536.0832,-634 536.0832,-634 536.0832,-628 542.0832,-622 548.0832,-622"/>
<text text-anchor="middle" x="577.0832" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
<polyline fill="none" stroke="#000000" points="618.0832,-622 618.0832,-1105 "/>
<text text-anchor="middle" x="628.5832" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="639.0832,-622 639.0832,-1105 "/>
<text text-anchor="middle" x="794.5832" y="-1089.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_days_per_week</text>
<polyline fill="none" stroke="#000000" points="639.0832,-1082 950.0832,-1082 "/>
<text text-anchor="middle" x="794.5832" y="-1066.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_drinks_per_day</text>
<polyline fill="none" stroke="#000000" points="639.0832,-1059 950.0832,-1059 "/>
<text text-anchor="middle" x="794.5832" y="-1043.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_history</text>
<polyline fill="none" stroke="#000000" points="639.0832,-1036 950.0832,-1036 "/>
<text text-anchor="middle" x="794.5832" y="-1020.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_intensity</text>
<polyline fill="none" stroke="#000000" points="639.0832,-1013 950.0832,-1013 "/>
<text text-anchor="middle" x="794.5832" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000">asbestos_exposure</text>
<polyline fill="none" stroke="#000000" points="639.0832,-990 950.0832,-990 "/>
<text text-anchor="middle" x="794.5832" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">cigarettes_per_day</text>
<polyline fill="none" stroke="#000000" points="639.0832,-967 950.0832,-967 "/>
<text text-anchor="middle" x="794.5832" y="-951.8" font-family="Times,serif" font-size="14.00" fill="#000000">coal_dust_exposure</text>
<polyline fill="none" stroke="#000000" points="639.0832,-944 950.0832,-944 "/>
<text text-anchor="middle" x="794.5832" y="-928.8" font-family="Times,serif" font-size="14.00" fill="#000000">environmental_tobacco_smoke_exposure</text>
<polyline fill="none" stroke="#000000" points="639.0832,-921 950.0832,-921 "/>
<text text-anchor="middle" x="794.5832" y="-905.8" font-family="Times,serif" font-size="14.00" fill="#000000">exposure_id</text>
<polyline fill="none" stroke="#000000" points="639.0832,-898 950.0832,-898 "/>
<text text-anchor="middle" x="794.5832" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">pack_years_smoked</text>
<polyline fill="none" stroke="#000000" points="639.0832,-875 950.0832,-875 "/>
<text text-anchor="middle" x="794.5832" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">radon_exposure</text>
<polyline fill="none" stroke="#000000" points="639.0832,-852 950.0832,-852 "/>
<text text-anchor="middle" x="794.5832" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">respirable_crystalline_silica_exposure</text>
<polyline fill="none" stroke="#000000" points="639.0832,-829 950.0832,-829 "/>
<text text-anchor="middle" x="794.5832" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">smoking_frequency</text>
<polyline fill="none" stroke="#000000" points="639.0832,-806 950.0832,-806 "/>
<text text-anchor="middle" x="794.5832" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">start_days_from_index</text>
<polyline fill="none" stroke="#000000" points="639.0832,-783 950.0832,-783 "/>
<text text-anchor="middle" x="794.5832" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">time_between_waking_and_first_smoke</text>
<polyline fill="none" stroke="#000000" points="639.0832,-760 950.0832,-760 "/>
<text text-anchor="middle" x="794.5832" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_onset_year</text>
<polyline fill="none" stroke="#000000" points="639.0832,-737 950.0832,-737 "/>
<text text-anchor="middle" x="794.5832" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_quit_year</text>
<polyline fill="none" stroke="#000000" points="639.0832,-714 950.0832,-714 "/>
<text text-anchor="middle" x="794.5832" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_status</text>
<polyline fill="none" stroke="#000000" points="639.0832,-691 950.0832,-691 "/>
<text text-anchor="middle" x="794.5832" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_smoke_exposure</text>
<polyline fill="none" stroke="#000000" points="639.0832,-668 950.0832,-668 "/>
<text text-anchor="middle" x="794.5832" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_tobacco_used</text>
<polyline fill="none" stroke="#000000" points="639.0832,-645 950.0832,-645 "/>
<text text-anchor="middle" x="794.5832" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">years_smoked</text>
<polyline fill="none" stroke="#000000" points="950.0832,-622 950.0832,-1105 "/>
<text text-anchor="middle" x="960.5832" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M904.6593,-621.8247C927.2748,-599.2968 952.2829,-579.2415 979.5832,-564 1121.1844,-484.9455 1550.1204,-551.8064 1707.5832,-513 1726.9066,-508.2378 1746.6846,-501.2887 1765.6533,-493.4323"/>
<polygon fill="#000000" stroke="#000000" points="1767.0581,-496.6384 1774.8947,-489.5083 1764.3221,-490.1952 1767.0581,-496.6384"/>
<text text-anchor="middle" x="1138.0832" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- follow_up -->
<g id="node8" class="node">
<title>follow_up</title>
<path fill="none" stroke="#000000" d="M1001.0832,-760C1001.0832,-760 1364.0832,-760 1364.0832,-760 1370.0832,-760 1376.0832,-766 1376.0832,-772 1376.0832,-772 1376.0832,-955 1376.0832,-955 1376.0832,-961 1370.0832,-967 1364.0832,-967 1364.0832,-967 1001.0832,-967 1001.0832,-967 995.0832,-967 989.0832,-961 989.0832,-955 989.0832,-955 989.0832,-772 989.0832,-772 989.0832,-766 995.0832,-760 1001.0832,-760"/>
<text text-anchor="middle" x="1031.5832" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
<polyline fill="none" stroke="#000000" points="1074.0832,-760 1074.0832,-967 "/>
<text text-anchor="middle" x="1084.5832" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1095.0832,-760 1095.0832,-967 "/>
<text text-anchor="middle" x="1225.0832" y="-951.8" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event</text>
<polyline fill="none" stroke="#000000" points="1095.0832,-944 1355.0832,-944 "/>
<text text-anchor="middle" x="1225.0832" y="-928.8" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity</text>
<polyline fill="none" stroke="#000000" points="1095.0832,-921 1355.0832,-921 "/>
<text text-anchor="middle" x="1225.0832" y="-905.8" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity_method_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1095.0832,-898 1355.0832,-898 "/>
<text text-anchor="middle" x="1225.0832" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_follow_up</text>
<polyline fill="none" stroke="#000000" points="1095.0832,-875 1355.0832,-875 "/>
<text text-anchor="middle" x="1225.0832" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_response</text>
<polyline fill="none" stroke="#000000" points="1095.0832,-852 1355.0832,-852 "/>
<text text-anchor="middle" x="1225.0832" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_category</text>
<polyline fill="none" stroke="#000000" points="1095.0832,-829 1355.0832,-829 "/>
<text text-anchor="middle" x="1225.0832" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_id</text>
<polyline fill="none" stroke="#000000" points="1095.0832,-806 1355.0832,-806 "/>
<text text-anchor="middle" x="1225.0832" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_other</text>
<polyline fill="none" stroke="#000000" points="1095.0832,-783 1355.0832,-783 "/>
<text text-anchor="middle" x="1225.0832" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">risk_factor</text>
<polyline fill="none" stroke="#000000" points="1355.0832,-760 1355.0832,-967 "/>
<text text-anchor="middle" x="1365.5832" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1225.7834,-759.7997C1259.1585,-692.9813 1311.9739,-610.2347 1384.5832,-564 1507.174,-485.9392 1568.5757,-555.4132 1707.5832,-513 1724.9278,-507.7079 1742.7615,-501.0053 1760.0925,-493.731"/>
<polygon fill="#000000" stroke="#000000" points="1761.8458,-496.7878 1769.6628,-489.6362 1759.0922,-490.3521 1761.8458,-496.7878"/>
<text text-anchor="middle" x="1503.5832" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- family_relationship -->
<g id="node9" class="node">
<title>family_relationship</title>
<path fill="none" stroke="#000000" d="M1406.0832,-817.5C1406.0832,-817.5 1775.0832,-817.5 1775.0832,-817.5 1781.0832,-817.5 1787.0832,-823.5 1787.0832,-829.5 1787.0832,-829.5 1787.0832,-897.5 1787.0832,-897.5 1787.0832,-903.5 1781.0832,-909.5 1775.0832,-909.5 1775.0832,-909.5 1406.0832,-909.5 1406.0832,-909.5 1400.0832,-909.5 1394.0832,-903.5 1394.0832,-897.5 1394.0832,-897.5 1394.0832,-829.5 1394.0832,-829.5 1394.0832,-823.5 1400.0832,-817.5 1406.0832,-817.5"/>
<text text-anchor="middle" x="1471.0832" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
<polyline fill="none" stroke="#000000" points="1548.0832,-817.5 1548.0832,-909.5 "/>
<text text-anchor="middle" x="1558.5832" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1569.0832,-817.5 1569.0832,-909.5 "/>
<text text-anchor="middle" x="1667.5832" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_id</text>
<polyline fill="none" stroke="#000000" points="1569.0832,-886.5 1766.0832,-886.5 "/>
<text text-anchor="middle" x="1667.5832" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship_id</text>
<polyline fill="none" stroke="#000000" points="1569.0832,-863.5 1766.0832,-863.5 "/>
<text text-anchor="middle" x="1667.5832" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">related_to_participant_id</text>
<polyline fill="none" stroke="#000000" points="1569.0832,-840.5 1766.0832,-840.5 "/>
<text text-anchor="middle" x="1667.5832" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">relationship</text>
<polyline fill="none" stroke="#000000" points="1766.0832,-817.5 1766.0832,-909.5 "/>
<text text-anchor="middle" x="1776.5832" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1604.1174,-817.2736C1625.7716,-749.0824 1673.3663,-620.0076 1746.5832,-531 1756.8277,-518.5461 1768.9731,-506.8401 1781.7141,-496.1429"/>
<polygon fill="#000000" stroke="#000000" points="1784.1782,-498.6495 1789.7125,-489.615 1779.7521,-493.2264 1784.1782,-498.6495"/>
<text text-anchor="middle" x="1826.0832" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- medical_history -->
<g id="node10" class="node">
<title>medical_history</title>
<path fill="none" stroke="#000000" d="M1817.5832,-829C1817.5832,-829 2171.5832,-829 2171.5832,-829 2177.5832,-829 2183.5832,-835 2183.5832,-841 2183.5832,-841 2183.5832,-886 2183.5832,-886 2183.5832,-892 2177.5832,-898 2171.5832,-898 2171.5832,-898 1817.5832,-898 1817.5832,-898 1811.5832,-898 1805.5832,-892 1805.5832,-886 1805.5832,-886 1805.5832,-841 1805.5832,-841 1805.5832,-835 1811.5832,-829 1817.5832,-829"/>
<text text-anchor="middle" x="1871.0832" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
<polyline fill="none" stroke="#000000" points="1936.5832,-829 1936.5832,-898 "/>
<text text-anchor="middle" x="1947.0832" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1957.5832,-829 1957.5832,-898 "/>
<text text-anchor="middle" x="2060.0832" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_category</text>
<polyline fill="none" stroke="#000000" points="1957.5832,-875 2162.5832,-875 "/>
<text text-anchor="middle" x="2060.0832" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_condition</text>
<polyline fill="none" stroke="#000000" points="1957.5832,-852 2162.5832,-852 "/>
<text text-anchor="middle" x="2060.0832" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_id</text>
<polyline fill="none" stroke="#000000" points="2162.5832,-829 2162.5832,-898 "/>
<text text-anchor="middle" x="2173.0832" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1985.527,-828.918C1966.8306,-757.5242 1923.6732,-592.7242 1899.2551,-499.4817"/>
<polygon fill="#000000" stroke="#000000" points="1902.5819,-498.3693 1896.6627,-489.5822 1895.8103,-500.1427 1902.5819,-498.3693"/>
<text text-anchor="middle" x="1977.5832" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- imaging_file -->
<g id="node11" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M4282.0832,-1318C4282.0832,-1318 4623.0832,-1318 4623.0832,-1318 4629.0832,-1318 4635.0832,-1324 4635.0832,-1330 4635.0832,-1330 4635.0832,-1697 4635.0832,-1697 4635.0832,-1703 4629.0832,-1709 4623.0832,-1709 4623.0832,-1709 4282.0832,-1709 4282.0832,-1709 4276.0832,-1709 4270.0832,-1703 4270.0832,-1697 4270.0832,-1697 4270.0832,-1330 4270.0832,-1330 4270.0832,-1324 4276.0832,-1318 4282.0832,-1318"/>
<text text-anchor="middle" x="4322.0832" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="4374.0832,-1318 4374.0832,-1709 "/>
<text text-anchor="middle" x="4384.5832" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4395.0832,-1318 4395.0832,-1709 "/>
<text text-anchor="middle" x="4504.5832" y="-1693.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="4395.0832,-1686 4614.0832,-1686 "/>
<text text-anchor="middle" x="4504.5832" y="-1670.8" font-family="Times,serif" font-size="14.00" fill="#000000">deidentification_method</text>
<polyline fill="none" stroke="#000000" points="4395.0832,-1663 4614.0832,-1663 "/>
<text text-anchor="middle" x="4504.5832" y="-1647.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="4395.0832,-1640 4614.0832,-1640 "/>
<text text-anchor="middle" x="4504.5832" y="-1624.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="4395.0832,-1617 4614.0832,-1617 "/>
<text text-anchor="middle" x="4504.5832" y="-1601.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="4395.0832,-1594 4614.0832,-1594 "/>
<text text-anchor="middle" x="4504.5832" y="-1578.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="4395.0832,-1571 4614.0832,-1571 "/>
<text text-anchor="middle" x="4504.5832" y="-1555.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="4395.0832,-1548 4614.0832,-1548 "/>
<text text-anchor="middle" x="4504.5832" y="-1532.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="4395.0832,-1525 4614.0832,-1525 "/>
<text text-anchor="middle" x="4504.5832" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">fixation_embedding_method</text>
<polyline fill="none" stroke="#000000" points="4395.0832,-1502 4614.0832,-1502 "/>
<text text-anchor="middle" x="4504.5832" y="-1486.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="4395.0832,-1479 4614.0832,-1479 "/>
<text text-anchor="middle" x="4504.5832" y="-1463.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file_id</text>
<polyline fill="none" stroke="#000000" points="4395.0832,-1456 4614.0832,-1456 "/>
<text text-anchor="middle" x="4504.5832" y="-1440.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="4395.0832,-1433 4614.0832,-1433 "/>
<text text-anchor="middle" x="4504.5832" y="-1417.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="4395.0832,-1410 4614.0832,-1410 "/>
<text text-anchor="middle" x="4504.5832" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">magnification</text>
<polyline fill="none" stroke="#000000" points="4395.0832,-1387 4614.0832,-1387 "/>
<text text-anchor="middle" x="4504.5832" y="-1371.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="4395.0832,-1364 4614.0832,-1364 "/>
<text text-anchor="middle" x="4504.5832" y="-1348.8" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="4395.0832,-1341 4614.0832,-1341 "/>
<text text-anchor="middle" x="4504.5832" y="-1325.8" font-family="Times,serif" font-size="14.00" fill="#000000">staining_method</text>
<polyline fill="none" stroke="#000000" points="4614.0832,-1318 4614.0832,-1709 "/>
<text text-anchor="middle" x="4624.5832" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M4390.7985,-1317.5971C4352.7114,-1196.8333 4305.6685,-1047.673 4276.1362,-954.0339"/>
<polygon fill="#000000" stroke="#000000" points="4279.4136,-952.7889 4273.0678,-944.3047 4272.7377,-954.8944 4279.4136,-952.7889"/>
<text text-anchor="middle" x="4405.0832" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- publication -->
<g id="node12" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M1033.0832,-409C1033.0832,-409 1266.0832,-409 1266.0832,-409 1272.0832,-409 1278.0832,-415 1278.0832,-421 1278.0832,-421 1278.0832,-443 1278.0832,-443 1278.0832,-449 1272.0832,-455 1266.0832,-455 1266.0832,-455 1033.0832,-455 1033.0832,-455 1027.0832,-455 1021.0832,-449 1021.0832,-443 1021.0832,-443 1021.0832,-421 1021.0832,-421 1021.0832,-415 1027.0832,-409 1033.0832,-409"/>
<text text-anchor="middle" x="1069.5832" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="1118.0832,-409 1118.0832,-455 "/>
<text text-anchor="middle" x="1128.5832" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1139.0832,-409 1139.0832,-455 "/>
<text text-anchor="middle" x="1198.0832" y="-439.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication_id</text>
<polyline fill="none" stroke="#000000" points="1139.0832,-432 1257.0832,-432 "/>
<text text-anchor="middle" x="1198.0832" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="1257.0832,-409 1257.0832,-455 "/>
<text text-anchor="middle" x="1267.5832" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge6" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1163.8224,-408.9228C1178.0462,-385.8704 1201.2496,-348.2649 1225.6192,-308.7692"/>
<polygon fill="#000000" stroke="#000000" points="1228.8926,-310.1294 1231.1651,-299.7811 1222.9354,-306.4536 1228.8926,-310.1294"/>
<text text-anchor="middle" x="1267.5832" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- molecular_test -->
<g id="node13" class="node">
<title>molecular_test</title>
<path fill="none" stroke="#000000" d="M2213.5832,-564.5C2213.5832,-564.5 2601.5832,-564.5 2601.5832,-564.5 2607.5832,-564.5 2613.5832,-570.5 2613.5832,-576.5 2613.5832,-576.5 2613.5832,-1150.5 2613.5832,-1150.5 2613.5832,-1156.5 2607.5832,-1162.5 2601.5832,-1162.5 2601.5832,-1162.5 2213.5832,-1162.5 2213.5832,-1162.5 2207.5832,-1162.5 2201.5832,-1156.5 2201.5832,-1150.5 2201.5832,-1150.5 2201.5832,-576.5 2201.5832,-576.5 2201.5832,-570.5 2207.5832,-564.5 2213.5832,-564.5"/>
<text text-anchor="middle" x="2263.0832" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
<polyline fill="none" stroke="#000000" points="2324.5832,-564.5 2324.5832,-1162.5 "/>
<text text-anchor="middle" x="2335.0832" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2345.5832,-564.5 2345.5832,-1162.5 "/>
<text text-anchor="middle" x="2469.0832" y="-1147.3" font-family="Times,serif" font-size="14.00" fill="#000000">aa_change</text>
<polyline fill="none" stroke="#000000" points="2345.5832,-1139.5 2592.5832,-1139.5 "/>
<text text-anchor="middle" x="2469.0832" y="-1124.3" font-family="Times,serif" font-size="14.00" fill="#000000">antigen</text>
<polyline fill="none" stroke="#000000" points="2345.5832,-1116.5 2592.5832,-1116.5 "/>
<text text-anchor="middle" x="2469.0832" y="-1101.3" font-family="Times,serif" font-size="14.00" fill="#000000">biospecimen_type</text>
<polyline fill="none" stroke="#000000" points="2345.5832,-1093.5 2592.5832,-1093.5 "/>
<text text-anchor="middle" x="2469.0832" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000">blood_test_normal_range_lower</text>
<polyline fill="none" stroke="#000000" points="2345.5832,-1070.5 2592.5832,-1070.5 "/>
<text text-anchor="middle" x="2469.0832" y="-1055.3" font-family="Times,serif" font-size="14.00" fill="#000000">blood_test_normal_range_upper</text>
<polyline fill="none" stroke="#000000" points="2345.5832,-1047.5 2592.5832,-1047.5 "/>
<text text-anchor="middle" x="2469.0832" y="-1032.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_count</text>
<polyline fill="none" stroke="#000000" points="2345.5832,-1024.5 2592.5832,-1024.5 "/>
<text text-anchor="middle" x="2469.0832" y="-1009.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome</text>
<polyline fill="none" stroke="#000000" points="2345.5832,-1001.5 2592.5832,-1001.5 "/>
<text text-anchor="middle" x="2469.0832" y="-986.3" font-family="Times,serif" font-size="14.00" fill="#000000">copy_number</text>
<polyline fill="none" stroke="#000000" points="2345.5832,-978.5 2592.5832,-978.5 "/>
<text text-anchor="middle" x="2469.0832" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytoband</text>
<polyline fill="none" stroke="#000000" points="2345.5832,-955.5 2592.5832,-955.5 "/>
<text text-anchor="middle" x="2469.0832" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">exon</text>
<polyline fill="none" stroke="#000000" points="2345.5832,-932.5 2592.5832,-932.5 "/>
<text text-anchor="middle" x="2469.0832" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">gene_symbol</text>
<polyline fill="none" stroke="#000000" points="2345.5832,-909.5 2592.5832,-909.5 "/>
<text text-anchor="middle" x="2469.0832" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">histone_family</text>
<polyline fill="none" stroke="#000000" points="2345.5832,-886.5 2592.5832,-886.5 "/>
<text text-anchor="middle" x="2469.0832" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">histone_variant</text>
<polyline fill="none" stroke="#000000" points="2345.5832,-863.5 2592.5832,-863.5 "/>
<text text-anchor="middle" x="2469.0832" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">intron</text>
<polyline fill="none" stroke="#000000" points="2345.5832,-840.5 2592.5832,-840.5 "/>
<text text-anchor="middle" x="2469.0832" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
<polyline fill="none" stroke="#000000" points="2345.5832,-817.5 2592.5832,-817.5 "/>
<text text-anchor="middle" x="2469.0832" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">loci_abnormal_count</text>
<polyline fill="none" stroke="#000000" points="2345.5832,-794.5 2592.5832,-794.5 "/>
<text text-anchor="middle" x="2469.0832" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">loci_count</text>
<polyline fill="none" stroke="#000000" points="2345.5832,-771.5 2592.5832,-771.5 "/>
<text text-anchor="middle" x="2469.0832" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">locus</text>
<polyline fill="none" stroke="#000000" points="2345.5832,-748.5 2592.5832,-748.5 "/>
<text text-anchor="middle" x="2469.0832" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">mismatch_repair_mutation</text>
<polyline fill="none" stroke="#000000" points="2345.5832,-725.5 2592.5832,-725.5 "/>
<text text-anchor="middle" x="2469.0832" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_analysis_method</text>
<polyline fill="none" stroke="#000000" points="2345.5832,-702.5 2592.5832,-702.5 "/>
<text text-anchor="middle" x="2469.0832" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_consequence</text>
<polyline fill="none" stroke="#000000" points="2345.5832,-679.5 2592.5832,-679.5 "/>
<text text-anchor="middle" x="2469.0832" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test_id</text>
<polyline fill="none" stroke="#000000" points="2345.5832,-656.5 2592.5832,-656.5 "/>
<text text-anchor="middle" x="2469.0832" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathogenicity</text>
<polyline fill="none" stroke="#000000" points="2345.5832,-633.5 2592.5832,-633.5 "/>
<text text-anchor="middle" x="2469.0832" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">ploidy</text>
<polyline fill="none" stroke="#000000" points="2345.5832,-610.5 2592.5832,-610.5 "/>
<text text-anchor="middle" x="2469.0832" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">second_exon</text>
<polyline fill="none" stroke="#000000" points="2345.5832,-587.5 2592.5832,-587.5 "/>
<text text-anchor="middle" x="2469.0832" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 11 properties</text>
<polyline fill="none" stroke="#000000" points="2592.5832,-564.5 2592.5832,-1162.5 "/>
<text text-anchor="middle" x="2603.0832" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2201.2961,-570.8408C2198.4151,-568.5119 2195.5107,-566.2305 2192.5832,-564 2140.5723,-524.3715 2114.9121,-538.2187 2054.5832,-513 2040.14,-506.9624 2025.1413,-500.3975 2010.283,-493.7049"/>
<polygon fill="#000000" stroke="#000000" points="2011.6092,-490.4633 2001.056,-489.5249 2008.7206,-496.8395 2011.6092,-490.4633"/>
<text text-anchor="middle" x="2228.5832" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- diagnosis -->
<g id="node14" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M2643.5832,-668C2643.5832,-668 3017.5832,-668 3017.5832,-668 3023.5832,-668 3029.5832,-674 3029.5832,-680 3029.5832,-680 3029.5832,-1047 3029.5832,-1047 3029.5832,-1053 3023.5832,-1059 3017.5832,-1059 3017.5832,-1059 2643.5832,-1059 2643.5832,-1059 2637.5832,-1059 2631.5832,-1053 2631.5832,-1047 2631.5832,-1047 2631.5832,-680 2631.5832,-680 2631.5832,-674 2637.5832,-668 2643.5832,-668"/>
<text text-anchor="middle" x="2673.5832" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="2715.5832,-668 2715.5832,-1059 "/>
<text text-anchor="middle" x="2726.0832" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2736.5832,-668 2736.5832,-1059 "/>
<text text-anchor="middle" x="2872.5832" y="-1043.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2736.5832,-1036 3008.5832,-1036 "/>
<text text-anchor="middle" x="2872.5832" y="-1020.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="2736.5832,-1013 3008.5832,-1013 "/>
<text text-anchor="middle" x="2872.5832" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="2736.5832,-990 3008.5832,-990 "/>
<text text-anchor="middle" x="2872.5832" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2736.5832,-967 3008.5832,-967 "/>
<text text-anchor="middle" x="2872.5832" y="-951.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="2736.5832,-944 3008.5832,-944 "/>
<text text-anchor="middle" x="2872.5832" y="-928.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="2736.5832,-921 3008.5832,-921 "/>
<text text-anchor="middle" x="2872.5832" y="-905.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="2736.5832,-898 3008.5832,-898 "/>
<text text-anchor="middle" x="2872.5832" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="2736.5832,-875 3008.5832,-875 "/>
<text text-anchor="middle" x="2872.5832" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="2736.5832,-852 3008.5832,-852 "/>
<text text-anchor="middle" x="2872.5832" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="2736.5832,-829 3008.5832,-829 "/>
<text text-anchor="middle" x="2872.5832" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2736.5832,-806 3008.5832,-806 "/>
<text text-anchor="middle" x="2872.5832" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="2736.5832,-783 3008.5832,-783 "/>
<text text-anchor="middle" x="2872.5832" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="2736.5832,-760 3008.5832,-760 "/>
<text text-anchor="middle" x="2872.5832" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="2736.5832,-737 3008.5832,-737 "/>
<text text-anchor="middle" x="2872.5832" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="2736.5832,-714 3008.5832,-714 "/>
<text text-anchor="middle" x="2872.5832" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="2736.5832,-691 3008.5832,-691 "/>
<text text-anchor="middle" x="2872.5832" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="3008.5832,-668 3008.5832,-1059 "/>
<text text-anchor="middle" x="3019.0832" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2731.2991,-667.9771C2701.7487,-627.3796 2665.5383,-589.3028 2622.5832,-564 2513.3893,-499.6791 2177.181,-545.098 2054.5832,-513 2035.9203,-508.1137 2016.8061,-501.2657 1998.4095,-493.5997"/>
<polygon fill="#000000" stroke="#000000" points="1999.7236,-490.3552 1989.1523,-489.6497 1996.9763,-496.7935 1999.7236,-490.3552"/>
<text text-anchor="middle" x="2619.0832" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- study_funding -->
<g id="node15" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M1308.0832,-386C1308.0832,-386 1687.0832,-386 1687.0832,-386 1693.0832,-386 1699.0832,-392 1699.0832,-398 1699.0832,-398 1699.0832,-466 1699.0832,-466 1699.0832,-472 1693.0832,-478 1687.0832,-478 1687.0832,-478 1308.0832,-478 1308.0832,-478 1302.0832,-478 1296.0832,-472 1296.0832,-466 1296.0832,-466 1296.0832,-398 1296.0832,-398 1296.0832,-392 1302.0832,-386 1308.0832,-386"/>
<text text-anchor="middle" x="1355.5832" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="1415.0832,-386 1415.0832,-478 "/>
<text text-anchor="middle" x="1425.5832" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1436.0832,-386 1436.0832,-478 "/>
<text text-anchor="middle" x="1557.0832" y="-462.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="1436.0832,-455 1678.0832,-455 "/>
<text text-anchor="middle" x="1557.0832" y="-439.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="1436.0832,-432 1678.0832,-432 "/>
<text text-anchor="middle" x="1557.0832" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="1436.0832,-409 1678.0832,-409 "/>
<text text-anchor="middle" x="1557.0832" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding_id</text>
<polyline fill="none" stroke="#000000" points="1678.0832,-386 1678.0832,-478 "/>
<text text-anchor="middle" x="1688.5832" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge20" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1469.0455,-385.7492C1455.6336,-364.0127 1438.7717,-336.6847 1421.3245,-308.4083"/>
<polygon fill="#000000" stroke="#000000" points="1424.124,-306.28 1415.8943,-299.6075 1418.1667,-309.9558 1424.124,-306.28"/>
<text text-anchor="middle" x="1498.5832" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge17" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1767.6542,-374.423C1702.0494,-341.2679 1617.4299,-298.5032 1539.6845,-259.2125"/>
<polygon fill="#000000" stroke="#000000" points="1541.2315,-256.0727 1530.7278,-254.686 1538.0741,-262.3202 1541.2315,-256.0727"/>
<text text-anchor="middle" x="1736.0832" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- therapeutic_procedure -->
<g id="node17" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M3060.0832,-794.5C3060.0832,-794.5 3461.0832,-794.5 3461.0832,-794.5 3467.0832,-794.5 3473.0832,-800.5 3473.0832,-806.5 3473.0832,-806.5 3473.0832,-920.5 3473.0832,-920.5 3473.0832,-926.5 3467.0832,-932.5 3461.0832,-932.5 3461.0832,-932.5 3060.0832,-932.5 3060.0832,-932.5 3054.0832,-932.5 3048.0832,-926.5 3048.0832,-920.5 3048.0832,-920.5 3048.0832,-806.5 3048.0832,-806.5 3048.0832,-800.5 3054.0832,-794.5 3060.0832,-794.5"/>
<text text-anchor="middle" x="3138.5832" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="3229.0832,-794.5 3229.0832,-932.5 "/>
<text text-anchor="middle" x="3239.5832" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3250.0832,-794.5 3250.0832,-932.5 "/>
<text text-anchor="middle" x="3351.0832" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment_end</text>
<polyline fill="none" stroke="#000000" points="3250.0832,-909.5 3452.0832,-909.5 "/>
<text text-anchor="middle" x="3351.0832" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment_start</text>
<polyline fill="none" stroke="#000000" points="3250.0832,-886.5 3452.0832,-886.5 "/>
<text text-anchor="middle" x="3351.0832" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="3250.0832,-863.5 3452.0832,-863.5 "/>
<text text-anchor="middle" x="3351.0832" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure_id</text>
<polyline fill="none" stroke="#000000" points="3250.0832,-840.5 3452.0832,-840.5 "/>
<text text-anchor="middle" x="3351.0832" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="3250.0832,-817.5 3452.0832,-817.5 "/>
<text text-anchor="middle" x="3351.0832" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="3452.0832,-794.5 3452.0832,-932.5 "/>
<text text-anchor="middle" x="3462.5832" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3230.5736,-794.388C3195.6497,-723.2243 3130.7556,-615.6569 3038.5832,-564 2894.1757,-483.0685 2832.8347,-540.767 2667.5832,-531 2531.5397,-522.9593 2187.1619,-544.5496 2054.5832,-513 2035.1751,-508.3815 2015.3355,-501.4608 1996.3388,-493.5751"/>
<polygon fill="#000000" stroke="#000000" points="1997.6582,-490.3328 1987.0865,-489.6322 1994.9139,-496.7724 1997.6582,-490.3328"/>
<text text-anchor="middle" x="3090.5832" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- sequencing_file -->
<g id="node18" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M4665.0832,-1214.5C4665.0832,-1214.5 5134.0832,-1214.5 5134.0832,-1214.5 5140.0832,-1214.5 5146.0832,-1220.5 5146.0832,-1226.5 5146.0832,-1226.5 5146.0832,-1800.5 5146.0832,-1800.5 5146.0832,-1806.5 5140.0832,-1812.5 5134.0832,-1812.5 5134.0832,-1812.5 4665.0832,-1812.5 4665.0832,-1812.5 4659.0832,-1812.5 4653.0832,-1806.5 4653.0832,-1800.5 4653.0832,-1800.5 4653.0832,-1226.5 4653.0832,-1226.5 4653.0832,-1220.5 4659.0832,-1214.5 4665.0832,-1214.5"/>
<text text-anchor="middle" x="4717.0832" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="4781.0832,-1214.5 4781.0832,-1812.5 "/>
<text text-anchor="middle" x="4791.5832" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4802.0832,-1214.5 4802.0832,-1812.5 "/>
<text text-anchor="middle" x="4963.5832" y="-1797.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="4802.0832,-1789.5 5125.0832,-1789.5 "/>
<text text-anchor="middle" x="4963.5832" y="-1774.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="4802.0832,-1766.5 5125.0832,-1766.5 "/>
<text text-anchor="middle" x="4963.5832" y="-1751.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="4802.0832,-1743.5 5125.0832,-1743.5 "/>
<text text-anchor="middle" x="4963.5832" y="-1728.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="4802.0832,-1720.5 5125.0832,-1720.5 "/>
<text text-anchor="middle" x="4963.5832" y="-1705.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="4802.0832,-1697.5 5125.0832,-1697.5 "/>
<text text-anchor="middle" x="4963.5832" y="-1682.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="4802.0832,-1674.5 5125.0832,-1674.5 "/>
<text text-anchor="middle" x="4963.5832" y="-1659.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="4802.0832,-1651.5 5125.0832,-1651.5 "/>
<text text-anchor="middle" x="4963.5832" y="-1636.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="4802.0832,-1628.5 5125.0832,-1628.5 "/>
<text text-anchor="middle" x="4963.5832" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="4802.0832,-1605.5 5125.0832,-1605.5 "/>
<text text-anchor="middle" x="4963.5832" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="4802.0832,-1582.5 5125.0832,-1582.5 "/>
<text text-anchor="middle" x="4963.5832" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="4802.0832,-1559.5 5125.0832,-1559.5 "/>
<text text-anchor="middle" x="4963.5832" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="4802.0832,-1536.5 5125.0832,-1536.5 "/>
<text text-anchor="middle" x="4963.5832" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="4802.0832,-1513.5 5125.0832,-1513.5 "/>
<text text-anchor="middle" x="4963.5832" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="4802.0832,-1490.5 5125.0832,-1490.5 "/>
<text text-anchor="middle" x="4963.5832" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="4802.0832,-1467.5 5125.0832,-1467.5 "/>
<text text-anchor="middle" x="4963.5832" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="4802.0832,-1444.5 5125.0832,-1444.5 "/>
<text text-anchor="middle" x="4963.5832" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="4802.0832,-1421.5 5125.0832,-1421.5 "/>
<text text-anchor="middle" x="4963.5832" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="4802.0832,-1398.5 5125.0832,-1398.5 "/>
<text text-anchor="middle" x="4963.5832" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="4802.0832,-1375.5 5125.0832,-1375.5 "/>
<text text-anchor="middle" x="4963.5832" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="4802.0832,-1352.5 5125.0832,-1352.5 "/>
<text text-anchor="middle" x="4963.5832" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="4802.0832,-1329.5 5125.0832,-1329.5 "/>
<text text-anchor="middle" x="4963.5832" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="4802.0832,-1306.5 5125.0832,-1306.5 "/>
<text text-anchor="middle" x="4963.5832" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="4802.0832,-1283.5 5125.0832,-1283.5 "/>
<text text-anchor="middle" x="4963.5832" y="-1268.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="4802.0832,-1260.5 5125.0832,-1260.5 "/>
<text text-anchor="middle" x="4963.5832" y="-1245.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="4802.0832,-1237.5 5125.0832,-1237.5 "/>
<text text-anchor="middle" x="4963.5832" y="-1222.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 1 properties</text>
<polyline fill="none" stroke="#000000" points="5125.0832,-1214.5 5125.0832,-1812.5 "/>
<text text-anchor="middle" x="5135.5832" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M4652.9512,-1223.6054C4649.8233,-1220.374 4646.6999,-1217.171 4643.5832,-1214 4550.3754,-1119.1682 4435.8873,-1019.4561 4354.0286,-950.7371"/>
<polygon fill="#000000" stroke="#000000" points="4356.1229,-947.9257 4346.2104,-944.1848 4351.6266,-953.2907 4356.1229,-947.9257"/>
<text text-anchor="middle" x="4690.0832" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node19" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M133.0832,-725.5C133.0832,-725.5 506.0832,-725.5 506.0832,-725.5 512.0832,-725.5 518.0832,-731.5 518.0832,-737.5 518.0832,-737.5 518.0832,-989.5 518.0832,-989.5 518.0832,-995.5 512.0832,-1001.5 506.0832,-1001.5 506.0832,-1001.5 133.0832,-1001.5 133.0832,-1001.5 127.0832,-1001.5 121.0832,-995.5 121.0832,-989.5 121.0832,-989.5 121.0832,-737.5 121.0832,-737.5 121.0832,-731.5 127.0832,-725.5 133.0832,-725.5"/>
<text text-anchor="middle" x="204.5832" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="288.0832,-725.5 288.0832,-1001.5 "/>
<text text-anchor="middle" x="298.5832" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="309.0832,-725.5 309.0832,-1001.5 "/>
<text text-anchor="middle" x="403.0832" y="-986.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="309.0832,-978.5 497.0832,-978.5 "/>
<text text-anchor="middle" x="403.0832" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="309.0832,-955.5 497.0832,-955.5 "/>
<text text-anchor="middle" x="403.0832" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file_id</text>
<polyline fill="none" stroke="#000000" points="309.0832,-932.5 497.0832,-932.5 "/>
<text text-anchor="middle" x="403.0832" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="309.0832,-909.5 497.0832,-909.5 "/>
<text text-anchor="middle" x="403.0832" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="309.0832,-886.5 497.0832,-886.5 "/>
<text text-anchor="middle" x="403.0832" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="309.0832,-863.5 497.0832,-863.5 "/>
<text text-anchor="middle" x="403.0832" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="309.0832,-840.5 497.0832,-840.5 "/>
<text text-anchor="middle" x="403.0832" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="309.0832,-817.5 497.0832,-817.5 "/>
<text text-anchor="middle" x="403.0832" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="309.0832,-794.5 497.0832,-794.5 "/>
<text text-anchor="middle" x="403.0832" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="309.0832,-771.5 497.0832,-771.5 "/>
<text text-anchor="middle" x="403.0832" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="309.0832,-748.5 497.0832,-748.5 "/>
<text text-anchor="middle" x="403.0832" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="497.0832,-725.5 497.0832,-1001.5 "/>
<text text-anchor="middle" x="507.5832" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M382.6599,-725.2647C416.8024,-666.083 464.7896,-601.976 526.5832,-564 618.6903,-507.3945 659.7981,-539.3826 767.5832,-531 871.7323,-522.9002 1605.8093,-536.5523 1707.5832,-513 1727.2514,-508.4484 1747.3557,-501.5145 1766.5882,-493.5807"/>
<polygon fill="#000000" stroke="#000000" points="1768.1122,-496.7362 1775.9539,-489.6117 1765.3808,-490.2911 1768.1122,-496.7362"/>
<text text-anchor="middle" x="897.0832" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge18" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M332.402,-725.2579C350.5728,-609.0584 394.4854,-446.9893 500.5832,-351 588.6888,-271.2887 893.3744,-212.1336 1106.1835,-179.3365"/>
<polygon fill="#000000" stroke="#000000" points="1106.8921,-182.7689 1116.2466,-177.7947 1105.8319,-175.8496 1106.8921,-182.7689"/>
<text text-anchor="middle" x="586.5832" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- pdx -->
<g id="node21" class="node">
<title>pdx</title>
<path fill="none" stroke="#000000" d="M5176.0832,-1398.5C5176.0832,-1398.5 5505.0832,-1398.5 5505.0832,-1398.5 5511.0832,-1398.5 5517.0832,-1404.5 5517.0832,-1410.5 5517.0832,-1410.5 5517.0832,-1616.5 5517.0832,-1616.5 5517.0832,-1622.5 5511.0832,-1628.5 5505.0832,-1628.5 5505.0832,-1628.5 5176.0832,-1628.5 5176.0832,-1628.5 5170.0832,-1628.5 5164.0832,-1622.5 5164.0832,-1616.5 5164.0832,-1616.5 5164.0832,-1410.5 5164.0832,-1410.5 5164.0832,-1404.5 5170.0832,-1398.5 5176.0832,-1398.5"/>
<text text-anchor="middle" x="5185.5832" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
<polyline fill="none" stroke="#000000" points="5207.0832,-1398.5 5207.0832,-1628.5 "/>
<text text-anchor="middle" x="5217.5832" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="5228.0832,-1398.5 5228.0832,-1628.5 "/>
<text text-anchor="middle" x="5362.0832" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_site</text>
<polyline fill="none" stroke="#000000" points="5228.0832,-1605.5 5496.0832,-1605.5 "/>
<text text-anchor="middle" x="5362.0832" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_type</text>
<polyline fill="none" stroke="#000000" points="5228.0832,-1582.5 5496.0832,-1582.5 "/>
<text text-anchor="middle" x="5362.0832" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_id</text>
<polyline fill="none" stroke="#000000" points="5228.0832,-1559.5 5496.0832,-1559.5 "/>
<text text-anchor="middle" x="5362.0832" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">mouse_strain</text>
<polyline fill="none" stroke="#000000" points="5228.0832,-1536.5 5496.0832,-1536.5 "/>
<text text-anchor="middle" x="5362.0832" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx_id</text>
<polyline fill="none" stroke="#000000" points="5228.0832,-1513.5 5496.0832,-1513.5 "/>
<text text-anchor="middle" x="5362.0832" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">strain_immune_system_humanized</text>
<polyline fill="none" stroke="#000000" points="5228.0832,-1490.5 5496.0832,-1490.5 "/>
<text text-anchor="middle" x="5362.0832" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_characterization_method</text>
<polyline fill="none" stroke="#000000" points="5228.0832,-1467.5 5496.0832,-1467.5 "/>
<text text-anchor="middle" x="5362.0832" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_not_mus_or_ebv_origin</text>
<polyline fill="none" stroke="#000000" points="5228.0832,-1444.5 5496.0832,-1444.5 "/>
<text text-anchor="middle" x="5362.0832" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_preparation</text>
<polyline fill="none" stroke="#000000" points="5228.0832,-1421.5 5496.0832,-1421.5 "/>
<text text-anchor="middle" x="5362.0832" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_humanization</text>
<polyline fill="none" stroke="#000000" points="5496.0832,-1398.5 5496.0832,-1628.5 "/>
<text text-anchor="middle" x="5506.5832" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M5291.3461,-1398.3059C5259.9555,-1336.5265 5213.9694,-1263.2042 5154.5832,-1214 4939.3431,-1035.6633 4623.0971,-941.3916 4426.5501,-897.0454"/>
<polygon fill="#000000" stroke="#000000" points="4427.2222,-893.6093 4416.6993,-894.842 4425.6942,-900.4405 4427.2222,-893.6093"/>
<text text-anchor="middle" x="5137.5832" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study_personnel -->
<g id="node22" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M2076.0832,-374.5C2076.0832,-374.5 2383.0832,-374.5 2383.0832,-374.5 2389.0832,-374.5 2395.0832,-380.5 2395.0832,-386.5 2395.0832,-386.5 2395.0832,-477.5 2395.0832,-477.5 2395.0832,-483.5 2389.0832,-489.5 2383.0832,-489.5 2383.0832,-489.5 2076.0832,-489.5 2076.0832,-489.5 2070.0832,-489.5 2064.0832,-483.5 2064.0832,-477.5 2064.0832,-477.5 2064.0832,-386.5 2064.0832,-386.5 2064.0832,-380.5 2070.0832,-374.5 2076.0832,-374.5"/>
<text text-anchor="middle" x="2131.0832" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="2198.0832,-374.5 2198.0832,-489.5 "/>
<text text-anchor="middle" x="2208.5832" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2219.0832,-374.5 2219.0832,-489.5 "/>
<text text-anchor="middle" x="2296.5832" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="2219.0832,-466.5 2374.0832,-466.5 "/>
<text text-anchor="middle" x="2296.5832" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="2219.0832,-443.5 2374.0832,-443.5 "/>
<text text-anchor="middle" x="2296.5832" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="2219.0832,-420.5 2374.0832,-420.5 "/>
<text text-anchor="middle" x="2296.5832" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="2219.0832,-397.5 2374.0832,-397.5 "/>
<text text-anchor="middle" x="2296.5832" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="2374.0832,-374.5 2374.0832,-489.5 "/>
<text text-anchor="middle" x="2384.5832" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge16" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2112.0877,-374.4056C2093.0803,-366.0229 2073.4463,-357.9051 2054.5832,-351 1885.2805,-289.0242 1687.8706,-235.825 1540.9032,-199.7538"/>
<polygon fill="#000000" stroke="#000000" points="1541.3988,-196.2719 1530.8535,-197.2946 1539.735,-203.0713 1541.3988,-196.2719"/>
<text text-anchor="middle" x="2067.0832" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- study_admin -->
<g id="node23" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M2425.5832,-351.5C2425.5832,-351.5 2751.5832,-351.5 2751.5832,-351.5 2757.5832,-351.5 2763.5832,-357.5 2763.5832,-363.5 2763.5832,-363.5 2763.5832,-500.5 2763.5832,-500.5 2763.5832,-506.5 2757.5832,-512.5 2751.5832,-512.5 2751.5832,-512.5 2425.5832,-512.5 2425.5832,-512.5 2419.5832,-512.5 2413.5832,-506.5 2413.5832,-500.5 2413.5832,-500.5 2413.5832,-363.5 2413.5832,-363.5 2413.5832,-357.5 2419.5832,-351.5 2425.5832,-351.5"/>
<text text-anchor="middle" x="2467.5832" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="2521.5832,-351.5 2521.5832,-512.5 "/>
<text text-anchor="middle" x="2532.0832" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2542.5832,-351.5 2542.5832,-512.5 "/>
<text text-anchor="middle" x="2642.5832" y="-497.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="2542.5832,-489.5 2742.5832,-489.5 "/>
<text text-anchor="middle" x="2642.5832" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="2542.5832,-466.5 2742.5832,-466.5 "/>
<text text-anchor="middle" x="2642.5832" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="2542.5832,-443.5 2742.5832,-443.5 "/>
<text text-anchor="middle" x="2642.5832" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="2542.5832,-420.5 2742.5832,-420.5 "/>
<text text-anchor="middle" x="2642.5832" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="2542.5832,-397.5 2742.5832,-397.5 "/>
<text text-anchor="middle" x="2642.5832" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="2542.5832,-374.5 2742.5832,-374.5 "/>
<text text-anchor="middle" x="2642.5832" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="2742.5832,-351.5 2742.5832,-512.5 "/>
<text text-anchor="middle" x="2753.0832" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge2" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2413.4379,-354.1328C2410.1377,-353.0507 2406.8507,-352.0049 2403.5832,-351 2111.2781,-261.1076 1761.4368,-204.9676 1540.815,-175.5648"/>
<polygon fill="#000000" stroke="#000000" points="1541.1081,-172.0731 1530.7348,-174.228 1540.1878,-179.0124 1541.1081,-172.0731"/>
<text text-anchor="middle" x="2375.0832" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
</g>
</svg>
</div>
