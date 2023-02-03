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
<svg width="3025pt" height="1735pt"
 viewBox="0.00 0.00 3024.50 1735.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1731)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1731 3020.5,-1731 3020.5,4 -4,4"/>
<!-- sequencing_file -->
<g id="node1" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M1169,-1151.5C1169,-1151.5 1638,-1151.5 1638,-1151.5 1644,-1151.5 1650,-1157.5 1650,-1163.5 1650,-1163.5 1650,-1714.5 1650,-1714.5 1650,-1720.5 1644,-1726.5 1638,-1726.5 1638,-1726.5 1169,-1726.5 1169,-1726.5 1163,-1726.5 1157,-1720.5 1157,-1714.5 1157,-1714.5 1157,-1163.5 1157,-1163.5 1157,-1157.5 1163,-1151.5 1169,-1151.5"/>
<text text-anchor="middle" x="1221" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="1285,-1151.5 1285,-1726.5 "/>
<text text-anchor="middle" x="1295.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1306,-1151.5 1306,-1726.5 "/>
<text text-anchor="middle" x="1467.5" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="1306,-1703.5 1629,-1703.5 "/>
<text text-anchor="middle" x="1467.5" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1306,-1680.5 1629,-1680.5 "/>
<text text-anchor="middle" x="1467.5" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1306,-1657.5 1629,-1657.5 "/>
<text text-anchor="middle" x="1467.5" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="1306,-1634.5 1629,-1634.5 "/>
<text text-anchor="middle" x="1467.5" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="1306,-1611.5 1629,-1611.5 "/>
<text text-anchor="middle" x="1467.5" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1306,-1588.5 1629,-1588.5 "/>
<text text-anchor="middle" x="1467.5" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="1306,-1565.5 1629,-1565.5 "/>
<text text-anchor="middle" x="1467.5" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1306,-1542.5 1629,-1542.5 "/>
<text text-anchor="middle" x="1467.5" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1306,-1519.5 1629,-1519.5 "/>
<text text-anchor="middle" x="1467.5" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1306,-1496.5 1629,-1496.5 "/>
<text text-anchor="middle" x="1467.5" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1306,-1473.5 1629,-1473.5 "/>
<text text-anchor="middle" x="1467.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1306,-1450.5 1629,-1450.5 "/>
<text text-anchor="middle" x="1467.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1306,-1427.5 1629,-1427.5 "/>
<text text-anchor="middle" x="1467.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="1306,-1404.5 1629,-1404.5 "/>
<text text-anchor="middle" x="1467.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="1306,-1381.5 1629,-1381.5 "/>
<text text-anchor="middle" x="1467.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="1306,-1358.5 1629,-1358.5 "/>
<text text-anchor="middle" x="1467.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="1306,-1335.5 1629,-1335.5 "/>
<text text-anchor="middle" x="1467.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="1306,-1312.5 1629,-1312.5 "/>
<text text-anchor="middle" x="1467.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="1306,-1289.5 1629,-1289.5 "/>
<text text-anchor="middle" x="1467.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1306,-1266.5 1629,-1266.5 "/>
<text text-anchor="middle" x="1467.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="1306,-1243.5 1629,-1243.5 "/>
<text text-anchor="middle" x="1467.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="1306,-1220.5 1629,-1220.5 "/>
<text text-anchor="middle" x="1467.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="1306,-1197.5 1629,-1197.5 "/>
<text text-anchor="middle" x="1467.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="1306,-1174.5 1629,-1174.5 "/>
<text text-anchor="middle" x="1467.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="1629,-1151.5 1629,-1726.5 "/>
<text text-anchor="middle" x="1639.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node10" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1246.5,-800.5C1246.5,-800.5 1560.5,-800.5 1560.5,-800.5 1566.5,-800.5 1572.5,-806.5 1572.5,-812.5 1572.5,-812.5 1572.5,-949.5 1572.5,-949.5 1572.5,-955.5 1566.5,-961.5 1560.5,-961.5 1560.5,-961.5 1246.5,-961.5 1246.5,-961.5 1240.5,-961.5 1234.5,-955.5 1234.5,-949.5 1234.5,-949.5 1234.5,-812.5 1234.5,-812.5 1234.5,-806.5 1240.5,-800.5 1246.5,-800.5"/>
<text text-anchor="middle" x="1268.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1302.5,-800.5 1302.5,-961.5 "/>
<text text-anchor="middle" x="1313" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1323.5,-800.5 1323.5,-961.5 "/>
<text text-anchor="middle" x="1437.5" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="1323.5,-938.5 1551.5,-938.5 "/>
<text text-anchor="middle" x="1437.5" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1323.5,-915.5 1551.5,-915.5 "/>
<text text-anchor="middle" x="1437.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1323.5,-892.5 1551.5,-892.5 "/>
<text text-anchor="middle" x="1437.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1323.5,-869.5 1551.5,-869.5 "/>
<text text-anchor="middle" x="1437.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1323.5,-846.5 1551.5,-846.5 "/>
<text text-anchor="middle" x="1437.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1323.5,-823.5 1551.5,-823.5 "/>
<text text-anchor="middle" x="1437.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="1551.5,-800.5 1551.5,-961.5 "/>
<text text-anchor="middle" x="1562" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1403.5,-1151.4187C1403.5,-1086.1568 1403.5,-1021.5215 1403.5,-971.8143"/>
<polygon fill="#000000" stroke="#000000" points="1407.0001,-971.758 1403.5,-961.7581 1400.0001,-971.7581 1407.0001,-971.758"/>
<text text-anchor="middle" x="1470" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- diagnosis -->
<g id="node2" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1602.5,-662.5C1602.5,-662.5 1976.5,-662.5 1976.5,-662.5 1982.5,-662.5 1988.5,-668.5 1988.5,-674.5 1988.5,-674.5 1988.5,-1087.5 1988.5,-1087.5 1988.5,-1093.5 1982.5,-1099.5 1976.5,-1099.5 1976.5,-1099.5 1602.5,-1099.5 1602.5,-1099.5 1596.5,-1099.5 1590.5,-1093.5 1590.5,-1087.5 1590.5,-1087.5 1590.5,-674.5 1590.5,-674.5 1590.5,-668.5 1596.5,-662.5 1602.5,-662.5"/>
<text text-anchor="middle" x="1632.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1674.5,-662.5 1674.5,-1099.5 "/>
<text text-anchor="middle" x="1685" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1695.5,-662.5 1695.5,-1099.5 "/>
<text text-anchor="middle" x="1831.5" y="-1084.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1695.5,-1076.5 1967.5,-1076.5 "/>
<text text-anchor="middle" x="1831.5" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1695.5,-1053.5 1967.5,-1053.5 "/>
<text text-anchor="middle" x="1831.5" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1695.5,-1030.5 1967.5,-1030.5 "/>
<text text-anchor="middle" x="1831.5" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1695.5,-1007.5 1967.5,-1007.5 "/>
<text text-anchor="middle" x="1831.5" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="1695.5,-984.5 1967.5,-984.5 "/>
<text text-anchor="middle" x="1831.5" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="1695.5,-961.5 1967.5,-961.5 "/>
<text text-anchor="middle" x="1831.5" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="1695.5,-938.5 1967.5,-938.5 "/>
<text text-anchor="middle" x="1831.5" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1695.5,-915.5 1967.5,-915.5 "/>
<text text-anchor="middle" x="1831.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1695.5,-892.5 1967.5,-892.5 "/>
<text text-anchor="middle" x="1831.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="1695.5,-869.5 1967.5,-869.5 "/>
<text text-anchor="middle" x="1831.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="1695.5,-846.5 1967.5,-846.5 "/>
<text text-anchor="middle" x="1831.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="1695.5,-823.5 1967.5,-823.5 "/>
<text text-anchor="middle" x="1831.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="1695.5,-800.5 1967.5,-800.5 "/>
<text text-anchor="middle" x="1831.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1695.5,-777.5 1967.5,-777.5 "/>
<text text-anchor="middle" x="1831.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="1695.5,-754.5 1967.5,-754.5 "/>
<text text-anchor="middle" x="1831.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="1695.5,-731.5 1967.5,-731.5 "/>
<text text-anchor="middle" x="1831.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1695.5,-708.5 1967.5,-708.5 "/>
<text text-anchor="middle" x="1831.5" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1695.5,-685.5 1967.5,-685.5 "/>
<text text-anchor="middle" x="1831.5" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1967.5,-662.5 1967.5,-1099.5 "/>
<text text-anchor="middle" x="1978" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node11" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M1872.5,-495.5C1872.5,-495.5 2176.5,-495.5 2176.5,-495.5 2182.5,-495.5 2188.5,-501.5 2188.5,-507.5 2188.5,-507.5 2188.5,-598.5 2188.5,-598.5 2188.5,-604.5 2182.5,-610.5 2176.5,-610.5 2176.5,-610.5 1872.5,-610.5 1872.5,-610.5 1866.5,-610.5 1860.5,-604.5 1860.5,-598.5 1860.5,-598.5 1860.5,-507.5 1860.5,-507.5 1860.5,-501.5 1866.5,-495.5 1872.5,-495.5"/>
<text text-anchor="middle" x="1908.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1956.5,-495.5 1956.5,-610.5 "/>
<text text-anchor="middle" x="1967" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1977.5,-495.5 1977.5,-610.5 "/>
<text text-anchor="middle" x="2072.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="1977.5,-587.5 2167.5,-587.5 "/>
<text text-anchor="middle" x="2072.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="1977.5,-564.5 2167.5,-564.5 "/>
<text text-anchor="middle" x="2072.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="1977.5,-541.5 2167.5,-541.5 "/>
<text text-anchor="middle" x="2072.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1977.5,-518.5 2167.5,-518.5 "/>
<text text-anchor="middle" x="2072.5" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="2167.5,-495.5 2167.5,-610.5 "/>
<text text-anchor="middle" x="2178" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1895.6876,-662.3658C1903.8868,-650.7141 1912.4984,-639.498 1921.5,-629 1924.8497,-625.0935 1928.4361,-621.2719 1932.1891,-617.5518"/>
<polygon fill="#000000" stroke="#000000" points="1934.7475,-619.949 1939.5931,-610.5272 1929.9296,-614.8709 1934.7475,-619.949"/>
<text text-anchor="middle" x="1966" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- study_admin -->
<g id="node3" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M707.5,-259.5C707.5,-259.5 1033.5,-259.5 1033.5,-259.5 1039.5,-259.5 1045.5,-265.5 1045.5,-271.5 1045.5,-271.5 1045.5,-431.5 1045.5,-431.5 1045.5,-437.5 1039.5,-443.5 1033.5,-443.5 1033.5,-443.5 707.5,-443.5 707.5,-443.5 701.5,-443.5 695.5,-437.5 695.5,-431.5 695.5,-431.5 695.5,-271.5 695.5,-271.5 695.5,-265.5 701.5,-259.5 707.5,-259.5"/>
<text text-anchor="middle" x="749.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="803.5,-259.5 803.5,-443.5 "/>
<text text-anchor="middle" x="814" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="824.5,-259.5 824.5,-443.5 "/>
<text text-anchor="middle" x="924.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="824.5,-420.5 1024.5,-420.5 "/>
<text text-anchor="middle" x="924.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="824.5,-397.5 1024.5,-397.5 "/>
<text text-anchor="middle" x="924.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="824.5,-374.5 1024.5,-374.5 "/>
<text text-anchor="middle" x="924.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="824.5,-351.5 1024.5,-351.5 "/>
<text text-anchor="middle" x="924.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="824.5,-328.5 1024.5,-328.5 "/>
<text text-anchor="middle" x="924.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="824.5,-305.5 1024.5,-305.5 "/>
<text text-anchor="middle" x="924.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="824.5,-282.5 1024.5,-282.5 "/>
<text text-anchor="middle" x="924.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="1024.5,-259.5 1024.5,-443.5 "/>
<text text-anchor="middle" x="1035" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node4" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M1619.5,-.5C1619.5,-.5 2009.5,-.5 2009.5,-.5 2015.5,-.5 2021.5,-6.5 2021.5,-12.5 2021.5,-12.5 2021.5,-195.5 2021.5,-195.5 2021.5,-201.5 2015.5,-207.5 2009.5,-207.5 2009.5,-207.5 1619.5,-207.5 1619.5,-207.5 1613.5,-207.5 1607.5,-201.5 1607.5,-195.5 1607.5,-195.5 1607.5,-12.5 1607.5,-12.5 1607.5,-6.5 1613.5,-.5 1619.5,-.5"/>
<text text-anchor="middle" x="1635.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="1663.5,-.5 1663.5,-207.5 "/>
<text text-anchor="middle" x="1674" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1684.5,-.5 1684.5,-207.5 "/>
<text text-anchor="middle" x="1842.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="1684.5,-184.5 2000.5,-184.5 "/>
<text text-anchor="middle" x="1842.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="1684.5,-161.5 2000.5,-161.5 "/>
<text text-anchor="middle" x="1842.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="1684.5,-138.5 2000.5,-138.5 "/>
<text text-anchor="middle" x="1842.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="1684.5,-115.5 2000.5,-115.5 "/>
<text text-anchor="middle" x="1842.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="1684.5,-92.5 2000.5,-92.5 "/>
<text text-anchor="middle" x="1842.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="1684.5,-69.5 2000.5,-69.5 "/>
<text text-anchor="middle" x="1842.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="1684.5,-46.5 2000.5,-46.5 "/>
<text text-anchor="middle" x="1842.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="1684.5,-23.5 2000.5,-23.5 "/>
<text text-anchor="middle" x="1842.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="2000.5,-.5 2000.5,-207.5 "/>
<text text-anchor="middle" x="2011" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge14" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1045.5293,-262.5649C1048.8651,-261.333 1052.1907,-260.143 1055.5,-259 1233.2238,-197.619 1443.1977,-157.0527 1597.1925,-132.8731"/>
<polygon fill="#000000" stroke="#000000" points="1597.9127,-136.3031 1607.254,-131.304 1596.8341,-129.3867 1597.9127,-136.3031"/>
<text text-anchor="middle" x="1212" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- sample_diagnosis -->
<g id="node5" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M1680,-1220.5C1680,-1220.5 2113,-1220.5 2113,-1220.5 2119,-1220.5 2125,-1226.5 2125,-1232.5 2125,-1232.5 2125,-1645.5 2125,-1645.5 2125,-1651.5 2119,-1657.5 2113,-1657.5 2113,-1657.5 1680,-1657.5 1680,-1657.5 1674,-1657.5 1668,-1651.5 1668,-1645.5 1668,-1645.5 1668,-1232.5 1668,-1232.5 1668,-1226.5 1674,-1220.5 1680,-1220.5"/>
<text text-anchor="middle" x="1739.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1811,-1220.5 1811,-1657.5 "/>
<text text-anchor="middle" x="1821.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1832,-1220.5 1832,-1657.5 "/>
<text text-anchor="middle" x="1968" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1832,-1634.5 2104,-1634.5 "/>
<text text-anchor="middle" x="1968" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1832,-1611.5 2104,-1611.5 "/>
<text text-anchor="middle" x="1968" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1832,-1588.5 2104,-1588.5 "/>
<text text-anchor="middle" x="1968" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1832,-1565.5 2104,-1565.5 "/>
<text text-anchor="middle" x="1968" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="1832,-1542.5 2104,-1542.5 "/>
<text text-anchor="middle" x="1968" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="1832,-1519.5 2104,-1519.5 "/>
<text text-anchor="middle" x="1968" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="1832,-1496.5 2104,-1496.5 "/>
<text text-anchor="middle" x="1968" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1832,-1473.5 2104,-1473.5 "/>
<text text-anchor="middle" x="1968" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="1832,-1450.5 2104,-1450.5 "/>
<text text-anchor="middle" x="1968" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="1832,-1427.5 2104,-1427.5 "/>
<text text-anchor="middle" x="1968" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1832,-1404.5 2104,-1404.5 "/>
<text text-anchor="middle" x="1968" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="1832,-1381.5 2104,-1381.5 "/>
<text text-anchor="middle" x="1968" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="1832,-1358.5 2104,-1358.5 "/>
<text text-anchor="middle" x="1968" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1832,-1335.5 2104,-1335.5 "/>
<text text-anchor="middle" x="1968" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="1832,-1312.5 2104,-1312.5 "/>
<text text-anchor="middle" x="1968" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="1832,-1289.5 2104,-1289.5 "/>
<text text-anchor="middle" x="1968" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1832,-1266.5 2104,-1266.5 "/>
<text text-anchor="middle" x="1968" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1832,-1243.5 2104,-1243.5 "/>
<text text-anchor="middle" x="1968" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="2104,-1220.5 2104,-1657.5 "/>
<text text-anchor="middle" x="2114.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1728.5738,-1220.1481C1706.3967,-1195.7947 1683.1298,-1172.1747 1659.5,-1151 1628.6535,-1123.3585 1612.2624,-1127.735 1581.5,-1100 1538.5964,-1061.3187 1497.4562,-1011.8152 1465.5554,-969.6625"/>
<polygon fill="#000000" stroke="#000000" points="1468.3096,-967.5014 1459.5046,-961.6088 1462.7131,-971.7062 1468.3096,-967.5014"/>
<text text-anchor="middle" x="1706.5" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
<!-- pdx -->
<g id="node6" class="node">
<title>pdx</title>
<path fill="none" stroke="#000000" d="M12,-1335.5C12,-1335.5 341,-1335.5 341,-1335.5 347,-1335.5 353,-1341.5 353,-1347.5 353,-1347.5 353,-1530.5 353,-1530.5 353,-1536.5 347,-1542.5 341,-1542.5 341,-1542.5 12,-1542.5 12,-1542.5 6,-1542.5 0,-1536.5 0,-1530.5 0,-1530.5 0,-1347.5 0,-1347.5 0,-1341.5 6,-1335.5 12,-1335.5"/>
<text text-anchor="middle" x="21.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
<polyline fill="none" stroke="#000000" points="43,-1335.5 43,-1542.5 "/>
<text text-anchor="middle" x="53.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="64,-1335.5 64,-1542.5 "/>
<text text-anchor="middle" x="198" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">injection_type_and_site</text>
<polyline fill="none" stroke="#000000" points="64,-1519.5 332,-1519.5 "/>
<text text-anchor="middle" x="198" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_id</text>
<polyline fill="none" stroke="#000000" points="64,-1496.5 332,-1496.5 "/>
<text text-anchor="middle" x="198" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_type</text>
<polyline fill="none" stroke="#000000" points="64,-1473.5 332,-1473.5 "/>
<text text-anchor="middle" x="198" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">mouse_strain</text>
<polyline fill="none" stroke="#000000" points="64,-1450.5 332,-1450.5 "/>
<text text-anchor="middle" x="198" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">strain_immune_system_humanized</text>
<polyline fill="none" stroke="#000000" points="64,-1427.5 332,-1427.5 "/>
<text text-anchor="middle" x="198" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_characterization_method</text>
<polyline fill="none" stroke="#000000" points="64,-1404.5 332,-1404.5 "/>
<text text-anchor="middle" x="198" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_not_mus_or_ebv_origin</text>
<polyline fill="none" stroke="#000000" points="64,-1381.5 332,-1381.5 "/>
<text text-anchor="middle" x="198" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_preparation</text>
<polyline fill="none" stroke="#000000" points="64,-1358.5 332,-1358.5 "/>
<text text-anchor="middle" x="198" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_humanization</text>
<polyline fill="none" stroke="#000000" points="332,-1335.5 332,-1542.5 "/>
<text text-anchor="middle" x="342.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M219.4201,-1335.1832C250.226,-1272.9911 297.6011,-1197.2651 361.5,-1151 498.7563,-1051.6216 964.4794,-957.5446 1224.4011,-911.1317"/>
<polygon fill="#000000" stroke="#000000" points="1225.0928,-914.5637 1234.3245,-909.365 1223.8658,-907.672 1225.0928,-914.5637"/>
<text text-anchor="middle" x="427.5" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study_funding -->
<g id="node7" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M1076,-317C1076,-317 1455,-317 1455,-317 1461,-317 1467,-323 1467,-329 1467,-329 1467,-374 1467,-374 1467,-380 1461,-386 1455,-386 1455,-386 1076,-386 1076,-386 1070,-386 1064,-380 1064,-374 1064,-374 1064,-329 1064,-329 1064,-323 1070,-317 1076,-317"/>
<text text-anchor="middle" x="1123.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="1183,-317 1183,-386 "/>
<text text-anchor="middle" x="1193.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1204,-317 1204,-386 "/>
<text text-anchor="middle" x="1325" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="1204,-363 1446,-363 "/>
<text text-anchor="middle" x="1325" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="1204,-340 1446,-340 "/>
<text text-anchor="middle" x="1325" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="1446,-317 1446,-386 "/>
<text text-anchor="middle" x="1456.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1323.6656,-316.7274C1369.2828,-290.1709 1434.8239,-253.5702 1494.5,-226 1527.5725,-210.7206 1563.1457,-195.7662 1598.1279,-181.8565"/>
<polygon fill="#000000" stroke="#000000" points="1599.4784,-185.0863 1607.4897,-178.1531 1596.9034,-178.5771 1599.4784,-185.0863"/>
<text text-anchor="middle" x="1556.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- publication -->
<g id="node8" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M1497.5,-333.5C1497.5,-333.5 1707.5,-333.5 1707.5,-333.5 1713.5,-333.5 1719.5,-339.5 1719.5,-345.5 1719.5,-345.5 1719.5,-357.5 1719.5,-357.5 1719.5,-363.5 1713.5,-369.5 1707.5,-369.5 1707.5,-369.5 1497.5,-369.5 1497.5,-369.5 1491.5,-369.5 1485.5,-363.5 1485.5,-357.5 1485.5,-357.5 1485.5,-345.5 1485.5,-345.5 1485.5,-339.5 1491.5,-333.5 1497.5,-333.5"/>
<text text-anchor="middle" x="1534" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="1582.5,-333.5 1582.5,-369.5 "/>
<text text-anchor="middle" x="1593" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1603.5,-333.5 1603.5,-369.5 "/>
<text text-anchor="middle" x="1651" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="1698.5,-333.5 1698.5,-369.5 "/>
<text text-anchor="middle" x="1709" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge5" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1602.614,-333.2045C1603.6272,-307.1642 1608.7352,-258.9249 1631.5,-226 1633.943,-222.4667 1636.5247,-219.0083 1639.2282,-215.625"/>
<polygon fill="#000000" stroke="#000000" points="1641.9938,-217.7743 1645.7494,-207.8674 1636.6355,-213.27 1641.9938,-217.7743"/>
<text text-anchor="middle" x="1682.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- study_arm -->
<g id="node9" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M1946,-317C1946,-317 2243,-317 2243,-317 2249,-317 2255,-323 2255,-329 2255,-329 2255,-374 2255,-374 2255,-380 2249,-386 2243,-386 2243,-386 1946,-386 1946,-386 1940,-386 1934,-380 1934,-374 1934,-374 1934,-329 1934,-329 1934,-323 1940,-317 1946,-317"/>
<text text-anchor="middle" x="1980" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="2026,-317 2026,-386 "/>
<text text-anchor="middle" x="2036.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2047,-317 2047,-386 "/>
<text text-anchor="middle" x="2140.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="2047,-363 2234,-363 "/>
<text text-anchor="middle" x="2140.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="2047,-340 2234,-340 "/>
<text text-anchor="middle" x="2140.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="2234,-317 2234,-386 "/>
<text text-anchor="middle" x="2244.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge18" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2055.2724,-316.8256C2024.959,-290.0308 1981.2369,-251.3835 1939.346,-214.3549"/>
<polygon fill="#000000" stroke="#000000" points="1941.6341,-211.7061 1931.8235,-207.7056 1936.998,-216.9509 1941.6341,-211.7061"/>
<text text-anchor="middle" x="2011" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge16" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1469.4952,-800.3263C1553.7607,-696.0014 1692.9415,-518.83 1728.5,-444 1731.0383,-438.6583 1762.1897,-314.4964 1786.2778,-217.7498"/>
<polygon fill="#000000" stroke="#000000" points="1789.7142,-218.4343 1788.7332,-207.8849 1782.9214,-216.7435 1789.7142,-218.4343"/>
<text text-anchor="middle" x="1754" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1447.1973,-800.4298C1478.0341,-751.873 1524.0407,-693.509 1581.5,-662 1642.6961,-628.4418 1669.254,-658.6147 1737.5,-644 1774.9182,-635.987 1814.4059,-625.1151 1851.7194,-613.6747"/>
<polygon fill="#000000" stroke="#000000" points="1853.1495,-616.896 1861.6675,-610.5957 1851.0798,-610.209 1853.1495,-616.896"/>
<text text-anchor="middle" x="1829" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge3" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1875.1231,-495.3994C1855.0823,-481.506 1837.1206,-464.5569 1824.5,-444 1783.4195,-377.0863 1782.3141,-287.9633 1790.741,-217.7513"/>
<polygon fill="#000000" stroke="#000000" points="1794.2508,-217.898 1792.0499,-207.5342 1787.3075,-217.0084 1794.2508,-217.898"/>
<text text-anchor="middle" x="1875" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge2" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M2044.5592,-495.2582C2055.5572,-463.5997 2068.9782,-424.9664 2079.1365,-395.7249"/>
<polygon fill="#000000" stroke="#000000" points="2082.4728,-396.7867 2082.4482,-386.1919 2075.8604,-394.4896 2082.4728,-396.7867"/>
<text text-anchor="middle" x="2105" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- therapeutic_procedure -->
<g id="node12" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M2140,-823.5C2140,-823.5 2497,-823.5 2497,-823.5 2503,-823.5 2509,-829.5 2509,-835.5 2509,-835.5 2509,-926.5 2509,-926.5 2509,-932.5 2503,-938.5 2497,-938.5 2497,-938.5 2140,-938.5 2140,-938.5 2134,-938.5 2128,-932.5 2128,-926.5 2128,-926.5 2128,-835.5 2128,-835.5 2128,-829.5 2134,-823.5 2140,-823.5"/>
<text text-anchor="middle" x="2218.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="2309,-823.5 2309,-938.5 "/>
<text text-anchor="middle" x="2319.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2330,-823.5 2330,-938.5 "/>
<text text-anchor="middle" x="2409" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="2330,-915.5 2488,-915.5 "/>
<text text-anchor="middle" x="2409" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="2330,-892.5 2488,-892.5 "/>
<text text-anchor="middle" x="2409" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="2330,-869.5 2488,-869.5 "/>
<text text-anchor="middle" x="2409" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="2330,-846.5 2488,-846.5 "/>
<text text-anchor="middle" x="2409" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="2488,-823.5 2488,-938.5 "/>
<text text-anchor="middle" x="2498.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2266.9527,-823.4914C2215.5468,-766.1407 2136.7037,-678.1797 2082.9858,-618.2495"/>
<polygon fill="#000000" stroke="#000000" points="2085.5162,-615.8286 2076.2353,-610.7183 2080.3036,-620.5009 2085.5162,-615.8286"/>
<text text-anchor="middle" x="2195.5" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- study_personnel -->
<g id="node13" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M2285,-294C2285,-294 2592,-294 2592,-294 2598,-294 2604,-300 2604,-306 2604,-306 2604,-397 2604,-397 2604,-403 2598,-409 2592,-409 2592,-409 2285,-409 2285,-409 2279,-409 2273,-403 2273,-397 2273,-397 2273,-306 2273,-306 2273,-300 2279,-294 2285,-294"/>
<text text-anchor="middle" x="2340" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="2407,-294 2407,-409 "/>
<text text-anchor="middle" x="2417.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2428,-294 2428,-409 "/>
<text text-anchor="middle" x="2505.5" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="2428,-386 2583,-386 "/>
<text text-anchor="middle" x="2505.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="2428,-363 2583,-363 "/>
<text text-anchor="middle" x="2505.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="2428,-340 2583,-340 "/>
<text text-anchor="middle" x="2505.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="2428,-317 2583,-317 "/>
<text text-anchor="middle" x="2505.5" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="2583,-294 2583,-409 "/>
<text text-anchor="middle" x="2593.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge12" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2336.7655,-293.9944C2313.3664,-281.7326 2288.3442,-269.3681 2264.5,-259 2189.8338,-226.533 2105.978,-196.0959 2031.0689,-170.9361"/>
<polygon fill="#000000" stroke="#000000" points="2032.1017,-167.591 2021.5079,-167.7371 2029.8805,-174.2293 2032.1017,-167.591"/>
<text text-anchor="middle" x="2286" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- methylation_array_file -->
<g id="node14" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M383,-1324C383,-1324 750,-1324 750,-1324 756,-1324 762,-1330 762,-1336 762,-1336 762,-1542 762,-1542 762,-1548 756,-1554 750,-1554 750,-1554 383,-1554 383,-1554 377,-1554 371,-1548 371,-1542 371,-1542 371,-1336 371,-1336 371,-1330 377,-1324 383,-1324"/>
<text text-anchor="middle" x="460" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="549,-1324 549,-1554 "/>
<text text-anchor="middle" x="559.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="570,-1324 570,-1554 "/>
<text text-anchor="middle" x="655.5" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="570,-1531 741,-1531 "/>
<text text-anchor="middle" x="655.5" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="570,-1508 741,-1508 "/>
<text text-anchor="middle" x="655.5" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="570,-1485 741,-1485 "/>
<text text-anchor="middle" x="655.5" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="570,-1462 741,-1462 "/>
<text text-anchor="middle" x="655.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="570,-1439 741,-1439 "/>
<text text-anchor="middle" x="655.5" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="570,-1416 741,-1416 "/>
<text text-anchor="middle" x="655.5" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="570,-1393 741,-1393 "/>
<text text-anchor="middle" x="655.5" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="570,-1370 741,-1370 "/>
<text text-anchor="middle" x="655.5" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="570,-1347 741,-1347 "/>
<text text-anchor="middle" x="655.5" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="741,-1324 741,-1554 "/>
<text text-anchor="middle" x="751.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M628.0491,-1323.8398C663.69,-1265.8494 713.064,-1198.0589 771.5,-1151 905.8112,-1042.8383 1089.9118,-970.7462 1224.771,-928.4718"/>
<polygon fill="#000000" stroke="#000000" points="1225.8847,-931.7909 1234.3944,-925.4795 1223.8062,-925.1066 1225.8847,-931.7909"/>
<text text-anchor="middle" x="892" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- synonym -->
<g id="node15" class="node">
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
<!-- synonym&#45;&gt;study -->
<g id="edge9" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2400.7246,-1415.9981C2539.5553,-1376.9591 2793.8703,-1283.4586 2912.5,-1100 2965.5502,-1017.9588 2931.5,-978.699 2931.5,-881 2931.5,-881 2931.5,-881 2931.5,-351.5 2931.5,-260.3005 2356.5881,-172.5714 2031.672,-130.2729"/>
<polygon fill="#000000" stroke="#000000" points="2032.0222,-126.7891 2021.6549,-128.973 2031.1213,-133.7309 2032.0222,-126.7891"/>
<text text-anchor="middle" x="2974" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2299.637,-1415.9841C2283.9055,-1359.4997 2234.9771,-1214.0569 2134.5,-1151 2095.0152,-1126.2203 1971.902,-1137.4659 1925.5,-1133 1862.7696,-1126.9626 1847.2227,-1124.1167 1784.5,-1118 1739.4257,-1113.6044 1621.4938,-1121.2487 1581.5,-1100 1526.8165,-1070.9466 1482.7427,-1017.2036 1452.1307,-970.23"/>
<polygon fill="#000000" stroke="#000000" points="1454.9107,-968.0809 1446.5719,-961.5453 1449.015,-971.8546 1454.9107,-968.0809"/>
<text text-anchor="middle" x="1968" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2297.0183,-1415.9029C2276.5501,-1362.8978 2219.7565,-1230.9519 2134.5,-1151 2098.1079,-1116.8722 2060.9476,-1142.3038 2034.5,-1100 1985.7835,-1022.0764 2005.0025,-749.4125 2017.2882,-620.9393"/>
<polygon fill="#000000" stroke="#000000" points="2020.7873,-621.117 2018.2696,-610.8257 2013.82,-620.4408 2020.7873,-621.117"/>
<text text-anchor="middle" x="2077" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- imaging_file -->
<g id="node16" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M792.5,-1278C792.5,-1278 1126.5,-1278 1126.5,-1278 1132.5,-1278 1138.5,-1284 1138.5,-1290 1138.5,-1290 1138.5,-1588 1138.5,-1588 1138.5,-1594 1132.5,-1600 1126.5,-1600 1126.5,-1600 792.5,-1600 792.5,-1600 786.5,-1600 780.5,-1594 780.5,-1588 780.5,-1588 780.5,-1290 780.5,-1290 780.5,-1284 786.5,-1278 792.5,-1278"/>
<text text-anchor="middle" x="832.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="884.5,-1278 884.5,-1600 "/>
<text text-anchor="middle" x="895" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="905.5,-1278 905.5,-1600 "/>
<text text-anchor="middle" x="1011.5" y="-1584.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="905.5,-1577 1117.5,-1577 "/>
<text text-anchor="middle" x="1011.5" y="-1561.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="905.5,-1554 1117.5,-1554 "/>
<text text-anchor="middle" x="1011.5" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="905.5,-1531 1117.5,-1531 "/>
<text text-anchor="middle" x="1011.5" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="905.5,-1508 1117.5,-1508 "/>
<text text-anchor="middle" x="1011.5" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="905.5,-1485 1117.5,-1485 "/>
<text text-anchor="middle" x="1011.5" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="905.5,-1462 1117.5,-1462 "/>
<text text-anchor="middle" x="1011.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="905.5,-1439 1117.5,-1439 "/>
<text text-anchor="middle" x="1011.5" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="905.5,-1416 1117.5,-1416 "/>
<text text-anchor="middle" x="1011.5" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="905.5,-1393 1117.5,-1393 "/>
<text text-anchor="middle" x="1011.5" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="905.5,-1370 1117.5,-1370 "/>
<text text-anchor="middle" x="1011.5" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="905.5,-1347 1117.5,-1347 "/>
<text text-anchor="middle" x="1011.5" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="905.5,-1324 1117.5,-1324 "/>
<text text-anchor="middle" x="1011.5" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="905.5,-1301 1117.5,-1301 "/>
<text text-anchor="middle" x="1011.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="1117.5,-1278 1117.5,-1600 "/>
<text text-anchor="middle" x="1128" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1058.1306,-1277.8019C1085.9255,-1235.5008 1117.166,-1190.6485 1148.5,-1151 1199.1866,-1086.8637 1262.2142,-1020.0294 1312.9262,-968.9011"/>
<polygon fill="#000000" stroke="#000000" points="1315.4262,-971.3507 1319.9976,-961.7928 1310.4636,-966.4138 1315.4262,-971.3507"/>
<text text-anchor="middle" x="1228" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node17" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M2539.5,-754.5C2539.5,-754.5 2891.5,-754.5 2891.5,-754.5 2897.5,-754.5 2903.5,-760.5 2903.5,-766.5 2903.5,-766.5 2903.5,-995.5 2903.5,-995.5 2903.5,-1001.5 2897.5,-1007.5 2891.5,-1007.5 2891.5,-1007.5 2539.5,-1007.5 2539.5,-1007.5 2533.5,-1007.5 2527.5,-1001.5 2527.5,-995.5 2527.5,-995.5 2527.5,-766.5 2527.5,-766.5 2527.5,-760.5 2533.5,-754.5 2539.5,-754.5"/>
<text text-anchor="middle" x="2611" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="2694.5,-754.5 2694.5,-1007.5 "/>
<text text-anchor="middle" x="2705" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2715.5,-754.5 2715.5,-1007.5 "/>
<text text-anchor="middle" x="2799" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2715.5,-984.5 2882.5,-984.5 "/>
<text text-anchor="middle" x="2799" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2715.5,-961.5 2882.5,-961.5 "/>
<text text-anchor="middle" x="2799" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2715.5,-938.5 2882.5,-938.5 "/>
<text text-anchor="middle" x="2799" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2715.5,-915.5 2882.5,-915.5 "/>
<text text-anchor="middle" x="2799" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2715.5,-892.5 2882.5,-892.5 "/>
<text text-anchor="middle" x="2799" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2715.5,-869.5 2882.5,-869.5 "/>
<text text-anchor="middle" x="2799" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2715.5,-846.5 2882.5,-846.5 "/>
<text text-anchor="middle" x="2799" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2715.5,-823.5 2882.5,-823.5 "/>
<text text-anchor="middle" x="2799" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2715.5,-800.5 2882.5,-800.5 "/>
<text text-anchor="middle" x="2799" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2715.5,-777.5 2882.5,-777.5 "/>
<text text-anchor="middle" x="2799" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="2882.5,-754.5 2882.5,-1007.5 "/>
<text text-anchor="middle" x="2893" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge17" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2734.5283,-754.2863C2747.9421,-612.6828 2744.5183,-386.5936 2613.5,-259 2532.3274,-179.9492 2239.2891,-139.1127 2031.6917,-119.6346"/>
<polygon fill="#000000" stroke="#000000" points="2031.8428,-116.1337 2021.5622,-118.6948 2031.196,-123.1038 2031.8428,-116.1337"/>
<text text-anchor="middle" x="2808.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2625.3385,-754.2629C2595.0211,-719.691 2558.5965,-685.3695 2518.5,-662 2514.876,-659.8878 2339.5129,-621.449 2198.7589,-590.8103"/>
<polygon fill="#000000" stroke="#000000" points="2199.2029,-587.3251 2188.6873,-588.6184 2197.7143,-594.165 2199.2029,-587.3251"/>
<text text-anchor="middle" x="2562" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
</g>
</svg>
</div>
