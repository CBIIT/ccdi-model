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
<svg width="3026pt" height="1528pt"
 viewBox="0.00 0.00 3026.00 1528.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1524)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1524 3022,-1524 3022,4 -4,4"/>
<!-- study_funding -->
<g id="node1" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M12,-317C12,-317 391,-317 391,-317 397,-317 403,-323 403,-329 403,-329 403,-374 403,-374 403,-380 397,-386 391,-386 391,-386 12,-386 12,-386 6,-386 0,-380 0,-374 0,-374 0,-329 0,-329 0,-323 6,-317 12,-317"/>
<text text-anchor="middle" x="59.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="119,-317 119,-386 "/>
<text text-anchor="middle" x="129.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="140,-317 140,-386 "/>
<text text-anchor="middle" x="261" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="140,-363 382,-363 "/>
<text text-anchor="middle" x="261" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="140,-340 382,-340 "/>
<text text-anchor="middle" x="261" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="382,-317 382,-386 "/>
<text text-anchor="middle" x="392.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node2" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M1472.5,-.5C1472.5,-.5 1862.5,-.5 1862.5,-.5 1868.5,-.5 1874.5,-6.5 1874.5,-12.5 1874.5,-12.5 1874.5,-195.5 1874.5,-195.5 1874.5,-201.5 1868.5,-207.5 1862.5,-207.5 1862.5,-207.5 1472.5,-207.5 1472.5,-207.5 1466.5,-207.5 1460.5,-201.5 1460.5,-195.5 1460.5,-195.5 1460.5,-12.5 1460.5,-12.5 1460.5,-6.5 1466.5,-.5 1472.5,-.5"/>
<text text-anchor="middle" x="1488.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="1516.5,-.5 1516.5,-207.5 "/>
<text text-anchor="middle" x="1527" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1537.5,-.5 1537.5,-207.5 "/>
<text text-anchor="middle" x="1695.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="1537.5,-184.5 1853.5,-184.5 "/>
<text text-anchor="middle" x="1695.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="1537.5,-161.5 1853.5,-161.5 "/>
<text text-anchor="middle" x="1695.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="1537.5,-138.5 1853.5,-138.5 "/>
<text text-anchor="middle" x="1695.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="1537.5,-115.5 1853.5,-115.5 "/>
<text text-anchor="middle" x="1695.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="1537.5,-92.5 1853.5,-92.5 "/>
<text text-anchor="middle" x="1695.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="1537.5,-69.5 1853.5,-69.5 "/>
<text text-anchor="middle" x="1695.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="1537.5,-46.5 1853.5,-46.5 "/>
<text text-anchor="middle" x="1695.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="1537.5,-23.5 1853.5,-23.5 "/>
<text text-anchor="middle" x="1695.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="1853.5,-.5 1853.5,-207.5 "/>
<text text-anchor="middle" x="1864" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge5" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M216.7092,-316.7587C231.6653,-287.1632 257.4948,-246.3004 293.5,-226 391.6693,-170.6504 1088.3496,-130.7365 1450.2912,-113.4844"/>
<polygon fill="#000000" stroke="#000000" points="1450.5476,-116.9762 1460.3703,-113.0057 1450.2155,-109.9841 1450.5476,-116.9762"/>
<text text-anchor="middle" x="355.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- sequencing_file -->
<g id="node3" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M2537,-967.5C2537,-967.5 3006,-967.5 3006,-967.5 3012,-967.5 3018,-973.5 3018,-979.5 3018,-979.5 3018,-1507.5 3018,-1507.5 3018,-1513.5 3012,-1519.5 3006,-1519.5 3006,-1519.5 2537,-1519.5 2537,-1519.5 2531,-1519.5 2525,-1513.5 2525,-1507.5 2525,-1507.5 2525,-979.5 2525,-979.5 2525,-973.5 2531,-967.5 2537,-967.5"/>
<text text-anchor="middle" x="2589" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="2653,-967.5 2653,-1519.5 "/>
<text text-anchor="middle" x="2663.5" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2674,-967.5 2674,-1519.5 "/>
<text text-anchor="middle" x="2835.5" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="2674,-1496.5 2997,-1496.5 "/>
<text text-anchor="middle" x="2835.5" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2674,-1473.5 2997,-1473.5 "/>
<text text-anchor="middle" x="2835.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2674,-1450.5 2997,-1450.5 "/>
<text text-anchor="middle" x="2835.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="2674,-1427.5 2997,-1427.5 "/>
<text text-anchor="middle" x="2835.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="2674,-1404.5 2997,-1404.5 "/>
<text text-anchor="middle" x="2835.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2674,-1381.5 2997,-1381.5 "/>
<text text-anchor="middle" x="2835.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2674,-1358.5 2997,-1358.5 "/>
<text text-anchor="middle" x="2835.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2674,-1335.5 2997,-1335.5 "/>
<text text-anchor="middle" x="2835.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2674,-1312.5 2997,-1312.5 "/>
<text text-anchor="middle" x="2835.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2674,-1289.5 2997,-1289.5 "/>
<text text-anchor="middle" x="2835.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2674,-1266.5 2997,-1266.5 "/>
<text text-anchor="middle" x="2835.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2674,-1243.5 2997,-1243.5 "/>
<text text-anchor="middle" x="2835.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="2674,-1220.5 2997,-1220.5 "/>
<text text-anchor="middle" x="2835.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="2674,-1197.5 2997,-1197.5 "/>
<text text-anchor="middle" x="2835.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="2674,-1174.5 2997,-1174.5 "/>
<text text-anchor="middle" x="2835.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="2674,-1151.5 2997,-1151.5 "/>
<text text-anchor="middle" x="2835.5" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="2674,-1128.5 2997,-1128.5 "/>
<text text-anchor="middle" x="2835.5" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="2674,-1105.5 2997,-1105.5 "/>
<text text-anchor="middle" x="2835.5" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2674,-1082.5 2997,-1082.5 "/>
<text text-anchor="middle" x="2835.5" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="2674,-1059.5 2997,-1059.5 "/>
<text text-anchor="middle" x="2835.5" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="2674,-1036.5 2997,-1036.5 "/>
<text text-anchor="middle" x="2835.5" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="2674,-1013.5 2997,-1013.5 "/>
<text text-anchor="middle" x="2835.5" y="-998.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="2674,-990.5 2997,-990.5 "/>
<text text-anchor="middle" x="2835.5" y="-975.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="2997,-967.5 2997,-1519.5 "/>
<text text-anchor="middle" x="3007.5" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node14" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1810.5,-639.5C1810.5,-639.5 2124.5,-639.5 2124.5,-639.5 2130.5,-639.5 2136.5,-645.5 2136.5,-651.5 2136.5,-651.5 2136.5,-903.5 2136.5,-903.5 2136.5,-909.5 2130.5,-915.5 2124.5,-915.5 2124.5,-915.5 1810.5,-915.5 1810.5,-915.5 1804.5,-915.5 1798.5,-909.5 1798.5,-903.5 1798.5,-903.5 1798.5,-651.5 1798.5,-651.5 1798.5,-645.5 1804.5,-639.5 1810.5,-639.5"/>
<text text-anchor="middle" x="1832.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1866.5,-639.5 1866.5,-915.5 "/>
<text text-anchor="middle" x="1877" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1887.5,-639.5 1887.5,-915.5 "/>
<text text-anchor="middle" x="2001.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1887.5,-892.5 2115.5,-892.5 "/>
<text text-anchor="middle" x="2001.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1887.5,-869.5 2115.5,-869.5 "/>
<text text-anchor="middle" x="2001.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1887.5,-846.5 2115.5,-846.5 "/>
<text text-anchor="middle" x="2001.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1887.5,-823.5 2115.5,-823.5 "/>
<text text-anchor="middle" x="2001.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1887.5,-800.5 2115.5,-800.5 "/>
<text text-anchor="middle" x="2001.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="1887.5,-777.5 2115.5,-777.5 "/>
<text text-anchor="middle" x="2001.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1887.5,-754.5 2115.5,-754.5 "/>
<text text-anchor="middle" x="2001.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="1887.5,-731.5 2115.5,-731.5 "/>
<text text-anchor="middle" x="2001.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="1887.5,-708.5 2115.5,-708.5 "/>
<text text-anchor="middle" x="2001.5" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1887.5,-685.5 2115.5,-685.5 "/>
<text text-anchor="middle" x="2001.5" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1887.5,-662.5 2115.5,-662.5 "/>
<text text-anchor="middle" x="2001.5" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="2115.5,-639.5 2115.5,-915.5 "/>
<text text-anchor="middle" x="2126" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2524.9111,-973.3074C2521.7871,-971.1599 2518.6497,-969.0564 2515.5,-967 2402.8811,-893.4723 2258.5504,-845.077 2146.2834,-815.6082"/>
<polygon fill="#000000" stroke="#000000" points="2147.1092,-812.2066 2136.5504,-813.0796 2145.349,-818.9817 2147.1092,-812.2066"/>
<text text-anchor="middle" x="2541" y="-937.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node4" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M471.5,-651C471.5,-651 823.5,-651 823.5,-651 829.5,-651 835.5,-657 835.5,-663 835.5,-663 835.5,-892 835.5,-892 835.5,-898 829.5,-904 823.5,-904 823.5,-904 471.5,-904 471.5,-904 465.5,-904 459.5,-898 459.5,-892 459.5,-892 459.5,-663 459.5,-663 459.5,-657 465.5,-651 471.5,-651"/>
<text text-anchor="middle" x="543" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="626.5,-651 626.5,-904 "/>
<text text-anchor="middle" x="637" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="647.5,-651 647.5,-904 "/>
<text text-anchor="middle" x="731" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="647.5,-881 814.5,-881 "/>
<text text-anchor="middle" x="731" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="647.5,-858 814.5,-858 "/>
<text text-anchor="middle" x="731" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="647.5,-835 814.5,-835 "/>
<text text-anchor="middle" x="731" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="647.5,-812 814.5,-812 "/>
<text text-anchor="middle" x="731" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="647.5,-789 814.5,-789 "/>
<text text-anchor="middle" x="731" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="647.5,-766 814.5,-766 "/>
<text text-anchor="middle" x="731" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="647.5,-743 814.5,-743 "/>
<text text-anchor="middle" x="731" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="647.5,-720 814.5,-720 "/>
<text text-anchor="middle" x="731" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="647.5,-697 814.5,-697 "/>
<text text-anchor="middle" x="731" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="647.5,-674 814.5,-674 "/>
<text text-anchor="middle" x="731" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="814.5,-651 814.5,-904 "/>
<text text-anchor="middle" x="825" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge6" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M783.9531,-650.8673C910.7606,-537.7938 1108.449,-372.9114 1300.5,-259 1347.4019,-231.1811 1400.2246,-205.7955 1450.8724,-183.9831"/>
<polygon fill="#000000" stroke="#000000" points="1452.4829,-187.1011 1460.3022,-179.952 1449.7314,-180.6645 1452.4829,-187.1011"/>
<text text-anchor="middle" x="1091.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- participant -->
<g id="node12" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M1355,-495.5C1355,-495.5 1586,-495.5 1586,-495.5 1592,-495.5 1598,-501.5 1598,-507.5 1598,-507.5 1598,-575.5 1598,-575.5 1598,-581.5 1592,-587.5 1586,-587.5 1586,-587.5 1355,-587.5 1355,-587.5 1349,-587.5 1343,-581.5 1343,-575.5 1343,-575.5 1343,-507.5 1343,-507.5 1343,-501.5 1349,-495.5 1355,-495.5"/>
<text text-anchor="middle" x="1391" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1439,-495.5 1439,-587.5 "/>
<text text-anchor="middle" x="1449.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1460,-495.5 1460,-587.5 "/>
<text text-anchor="middle" x="1518.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="1460,-564.5 1577,-564.5 "/>
<text text-anchor="middle" x="1518.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="1460,-541.5 1577,-541.5 "/>
<text text-anchor="middle" x="1518.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1460,-518.5 1577,-518.5 "/>
<text text-anchor="middle" x="1518.5" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1577,-495.5 1577,-587.5 "/>
<text text-anchor="middle" x="1587.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M818.4709,-650.9073C827.0947,-646.5645 835.793,-642.5602 844.5,-639 930.5481,-603.8158 1175.8992,-572.5858 1332.6581,-555.4286"/>
<polygon fill="#000000" stroke="#000000" points="1333.2902,-558.8805 1342.8528,-554.3189 1332.5327,-551.9216 1333.2902,-558.8805"/>
<text text-anchor="middle" x="1090" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- methylation_array_file -->
<g id="node5" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M1751,-1128.5C1751,-1128.5 2118,-1128.5 2118,-1128.5 2124,-1128.5 2130,-1134.5 2130,-1140.5 2130,-1140.5 2130,-1346.5 2130,-1346.5 2130,-1352.5 2124,-1358.5 2118,-1358.5 2118,-1358.5 1751,-1358.5 1751,-1358.5 1745,-1358.5 1739,-1352.5 1739,-1346.5 1739,-1346.5 1739,-1140.5 1739,-1140.5 1739,-1134.5 1745,-1128.5 1751,-1128.5"/>
<text text-anchor="middle" x="1828" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="1917,-1128.5 1917,-1358.5 "/>
<text text-anchor="middle" x="1927.5" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1938,-1128.5 1938,-1358.5 "/>
<text text-anchor="middle" x="2023.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1938,-1335.5 2109,-1335.5 "/>
<text text-anchor="middle" x="2023.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1938,-1312.5 2109,-1312.5 "/>
<text text-anchor="middle" x="2023.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1938,-1289.5 2109,-1289.5 "/>
<text text-anchor="middle" x="2023.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1938,-1266.5 2109,-1266.5 "/>
<text text-anchor="middle" x="2023.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1938,-1243.5 2109,-1243.5 "/>
<text text-anchor="middle" x="2023.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1938,-1220.5 2109,-1220.5 "/>
<text text-anchor="middle" x="2023.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1938,-1197.5 2109,-1197.5 "/>
<text text-anchor="middle" x="2023.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1938,-1174.5 2109,-1174.5 "/>
<text text-anchor="middle" x="2023.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="1938,-1151.5 2109,-1151.5 "/>
<text text-anchor="middle" x="2023.5" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="2109,-1128.5 2109,-1358.5 "/>
<text text-anchor="middle" x="2119.5" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1942.6573,-1128.309C1946.9871,-1067.1664 1952.3571,-991.336 1956.9955,-925.8368"/>
<polygon fill="#000000" stroke="#000000" points="1960.4885,-926.0569 1957.7038,-915.8347 1953.506,-925.5624 1960.4885,-926.0569"/>
<text text-anchor="middle" x="2048" y="-937.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study_admin -->
<g id="node6" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M1846.5,-259.5C1846.5,-259.5 2172.5,-259.5 2172.5,-259.5 2178.5,-259.5 2184.5,-265.5 2184.5,-271.5 2184.5,-271.5 2184.5,-431.5 2184.5,-431.5 2184.5,-437.5 2178.5,-443.5 2172.5,-443.5 2172.5,-443.5 1846.5,-443.5 1846.5,-443.5 1840.5,-443.5 1834.5,-437.5 1834.5,-431.5 1834.5,-431.5 1834.5,-271.5 1834.5,-271.5 1834.5,-265.5 1840.5,-259.5 1846.5,-259.5"/>
<text text-anchor="middle" x="1888.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="1942.5,-259.5 1942.5,-443.5 "/>
<text text-anchor="middle" x="1953" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1963.5,-259.5 1963.5,-443.5 "/>
<text text-anchor="middle" x="2063.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="1963.5,-420.5 2163.5,-420.5 "/>
<text text-anchor="middle" x="2063.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="1963.5,-397.5 2163.5,-397.5 "/>
<text text-anchor="middle" x="2063.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="1963.5,-374.5 2163.5,-374.5 "/>
<text text-anchor="middle" x="2063.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="1963.5,-351.5 2163.5,-351.5 "/>
<text text-anchor="middle" x="2063.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="1963.5,-328.5 2163.5,-328.5 "/>
<text text-anchor="middle" x="2063.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="1963.5,-305.5 2163.5,-305.5 "/>
<text text-anchor="middle" x="2063.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="1963.5,-282.5 2163.5,-282.5 "/>
<text text-anchor="middle" x="2063.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="2163.5,-259.5 2163.5,-443.5 "/>
<text text-anchor="middle" x="2174" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge3" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1882.1518,-259.3401C1861.6138,-244.4771 1840.1754,-228.9624 1819.1333,-213.7346"/>
<polygon fill="#000000" stroke="#000000" points="1820.9308,-210.7151 1810.7776,-207.6878 1816.8269,-216.3859 1820.9308,-210.7151"/>
<text text-anchor="middle" x="1906" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- synonym -->
<g id="node7" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M1408,-1220.5C1408,-1220.5 1709,-1220.5 1709,-1220.5 1715,-1220.5 1721,-1226.5 1721,-1232.5 1721,-1232.5 1721,-1254.5 1721,-1254.5 1721,-1260.5 1715,-1266.5 1709,-1266.5 1709,-1266.5 1408,-1266.5 1408,-1266.5 1402,-1266.5 1396,-1260.5 1396,-1254.5 1396,-1254.5 1396,-1232.5 1396,-1232.5 1396,-1226.5 1402,-1220.5 1408,-1220.5"/>
<text text-anchor="middle" x="1436" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="1476,-1220.5 1476,-1266.5 "/>
<text text-anchor="middle" x="1486.5" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1497,-1220.5 1497,-1266.5 "/>
<text text-anchor="middle" x="1598.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="1497,-1243.5 1700,-1243.5 "/>
<text text-anchor="middle" x="1598.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="1700,-1220.5 1700,-1266.5 "/>
<text text-anchor="middle" x="1710.5" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge15" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1413.4022,-1220.4781C1142.7171,-1174.4735 576.6952,-1062.8585 450.5,-916 410.0065,-868.876 431.5,-839.6321 431.5,-777.5 431.5,-777.5 431.5,-777.5 431.5,-351.5 431.5,-248.8441 1095.4885,-163.7115 1450.1322,-125.5625"/>
<polygon fill="#000000" stroke="#000000" points="1450.7032,-129.0214 1460.2731,-124.4753 1449.957,-122.0613 1450.7032,-129.0214"/>
<text text-anchor="middle" x="474" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1569.2103,-1220.3371C1592.8954,-1167.6845 1649.1494,-1034.3872 1668.5,-916 1688.3592,-794.5012 1683.1056,-761.2416 1668.5,-639 1666.7096,-624.0151 1670.6836,-617.1376 1660.5,-606 1651.6805,-596.3543 1631.7066,-586.8215 1607.8752,-578.1641"/>
<polygon fill="#000000" stroke="#000000" points="1608.7927,-574.7768 1598.1979,-574.7645 1606.4726,-581.3812 1608.7927,-574.7768"/>
<text text-anchor="middle" x="1724" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1569.4288,-1220.2208C1593.584,-1170.2695 1655.2979,-1050.5655 1729.5,-967 1741.4295,-953.5651 1763.8277,-933.8872 1790.2876,-912.2334"/>
<polygon fill="#000000" stroke="#000000" points="1792.6875,-914.793 1798.236,-905.7672 1788.2699,-909.3629 1792.6875,-914.793"/>
<text text-anchor="middle" x="1804" y="-937.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study_personnel -->
<g id="node8" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M2215,-294C2215,-294 2522,-294 2522,-294 2528,-294 2534,-300 2534,-306 2534,-306 2534,-397 2534,-397 2534,-403 2528,-409 2522,-409 2522,-409 2215,-409 2215,-409 2209,-409 2203,-403 2203,-397 2203,-397 2203,-306 2203,-306 2203,-300 2209,-294 2215,-294"/>
<text text-anchor="middle" x="2270" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="2337,-294 2337,-409 "/>
<text text-anchor="middle" x="2347.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2358,-294 2358,-409 "/>
<text text-anchor="middle" x="2435.5" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="2358,-386 2513,-386 "/>
<text text-anchor="middle" x="2435.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="2358,-363 2513,-363 "/>
<text text-anchor="middle" x="2435.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="2358,-340 2513,-340 "/>
<text text-anchor="middle" x="2435.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="2358,-317 2513,-317 "/>
<text text-anchor="middle" x="2435.5" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="2513,-294 2513,-409 "/>
<text text-anchor="middle" x="2523.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2267.8855,-293.9387C2243.9405,-281.4742 2218.1693,-269.0369 2193.5,-259 2094.285,-218.6336 1980.6787,-183.8096 1884.495,-157.4534"/>
<polygon fill="#000000" stroke="#000000" points="1885.2167,-154.0225 1874.6481,-154.768 1883.3749,-160.7758 1885.2167,-154.0225"/>
<text text-anchor="middle" x="2207" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- imaging_file -->
<g id="node9" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M2160.5,-1082.5C2160.5,-1082.5 2494.5,-1082.5 2494.5,-1082.5 2500.5,-1082.5 2506.5,-1088.5 2506.5,-1094.5 2506.5,-1094.5 2506.5,-1392.5 2506.5,-1392.5 2506.5,-1398.5 2500.5,-1404.5 2494.5,-1404.5 2494.5,-1404.5 2160.5,-1404.5 2160.5,-1404.5 2154.5,-1404.5 2148.5,-1398.5 2148.5,-1392.5 2148.5,-1392.5 2148.5,-1094.5 2148.5,-1094.5 2148.5,-1088.5 2154.5,-1082.5 2160.5,-1082.5"/>
<text text-anchor="middle" x="2200.5" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="2252.5,-1082.5 2252.5,-1404.5 "/>
<text text-anchor="middle" x="2263" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2273.5,-1082.5 2273.5,-1404.5 "/>
<text text-anchor="middle" x="2379.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2273.5,-1381.5 2485.5,-1381.5 "/>
<text text-anchor="middle" x="2379.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2273.5,-1358.5 2485.5,-1358.5 "/>
<text text-anchor="middle" x="2379.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2273.5,-1335.5 2485.5,-1335.5 "/>
<text text-anchor="middle" x="2379.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2273.5,-1312.5 2485.5,-1312.5 "/>
<text text-anchor="middle" x="2379.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2273.5,-1289.5 2485.5,-1289.5 "/>
<text text-anchor="middle" x="2379.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2273.5,-1266.5 2485.5,-1266.5 "/>
<text text-anchor="middle" x="2379.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2273.5,-1243.5 2485.5,-1243.5 "/>
<text text-anchor="middle" x="2379.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2273.5,-1220.5 2485.5,-1220.5 "/>
<text text-anchor="middle" x="2379.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2273.5,-1197.5 2485.5,-1197.5 "/>
<text text-anchor="middle" x="2379.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="2273.5,-1174.5 2485.5,-1174.5 "/>
<text text-anchor="middle" x="2379.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="2273.5,-1151.5 2485.5,-1151.5 "/>
<text text-anchor="middle" x="2379.5" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="2273.5,-1128.5 2485.5,-1128.5 "/>
<text text-anchor="middle" x="2379.5" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2273.5,-1105.5 2485.5,-1105.5 "/>
<text text-anchor="middle" x="2379.5" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="2485.5,-1082.5 2485.5,-1404.5 "/>
<text text-anchor="middle" x="2496" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2244.1868,-1082.1814C2215.2869,-1032.5055 2180.7121,-979.0712 2143.5,-934 2140.5652,-930.4454 2137.5477,-926.9004 2134.4602,-923.3711"/>
<polygon fill="#000000" stroke="#000000" points="2136.8625,-920.8061 2127.5947,-915.6719 2131.6379,-925.4649 2136.8625,-920.8061"/>
<text text-anchor="middle" x="2204" y="-937.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- study_arm -->
<g id="node10" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M1322,-317C1322,-317 1619,-317 1619,-317 1625,-317 1631,-323 1631,-329 1631,-329 1631,-374 1631,-374 1631,-380 1625,-386 1619,-386 1619,-386 1322,-386 1322,-386 1316,-386 1310,-380 1310,-374 1310,-374 1310,-329 1310,-329 1310,-323 1316,-317 1322,-317"/>
<text text-anchor="middle" x="1356" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="1402,-317 1402,-386 "/>
<text text-anchor="middle" x="1412.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1423,-317 1423,-386 "/>
<text text-anchor="middle" x="1516.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="1423,-363 1610,-363 "/>
<text text-anchor="middle" x="1516.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="1423,-340 1610,-340 "/>
<text text-anchor="middle" x="1516.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="1610,-317 1610,-386 "/>
<text text-anchor="middle" x="1620.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge4" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1492.4503,-316.7713C1509.141,-291.0564 1533.1419,-255.5137 1556.5,-226 1559.2739,-222.4951 1562.1222,-218.964 1565.0255,-215.423"/>
<polygon fill="#000000" stroke="#000000" points="1567.7727,-217.5933 1571.4619,-207.6614 1562.3843,-213.1249 1567.7727,-217.5933"/>
<text text-anchor="middle" x="1605" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- publication -->
<g id="node11" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M2564.5,-333.5C2564.5,-333.5 2774.5,-333.5 2774.5,-333.5 2780.5,-333.5 2786.5,-339.5 2786.5,-345.5 2786.5,-345.5 2786.5,-357.5 2786.5,-357.5 2786.5,-363.5 2780.5,-369.5 2774.5,-369.5 2774.5,-369.5 2564.5,-369.5 2564.5,-369.5 2558.5,-369.5 2552.5,-363.5 2552.5,-357.5 2552.5,-357.5 2552.5,-345.5 2552.5,-345.5 2552.5,-339.5 2558.5,-333.5 2564.5,-333.5"/>
<text text-anchor="middle" x="2601" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="2649.5,-333.5 2649.5,-369.5 "/>
<text text-anchor="middle" x="2660" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2670.5,-333.5 2670.5,-369.5 "/>
<text text-anchor="middle" x="2718" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="2765.5,-333.5 2765.5,-369.5 "/>
<text text-anchor="middle" x="2776" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge9" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2650.7552,-333.3393C2627.5611,-311.9804 2585.9152,-277.143 2543.5,-259 2427.8608,-209.5355 2104.7838,-160.2716 1885.0279,-130.9749"/>
<polygon fill="#000000" stroke="#000000" points="1885.3436,-127.4862 1874.9697,-129.6383 1884.4215,-134.4252 1885.3436,-127.4862"/>
<text text-anchor="middle" x="2541.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge18" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1585.8201,-495.2819C1606.8345,-481.7892 1626.2639,-464.8864 1639.5,-444 1681.6533,-377.4824 1687.5727,-288.344 1683.5253,-218.0257"/>
<polygon fill="#000000" stroke="#000000" points="1687.0015,-217.5438 1682.859,-207.7924 1680.0163,-217.9987 1687.0015,-217.5438"/>
<text text-anchor="middle" x="1736" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge19" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1470.5,-495.0208C1470.5,-464.9487 1470.5,-426.0098 1470.5,-396.2801"/>
<polygon fill="#000000" stroke="#000000" points="1474.0001,-396.178 1470.5,-386.178 1467.0001,-396.178 1474.0001,-396.178"/>
<text text-anchor="middle" x="1521" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- diagnosis -->
<g id="node13" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M866,-639.5C866,-639.5 1249,-639.5 1249,-639.5 1255,-639.5 1261,-645.5 1261,-651.5 1261,-651.5 1261,-903.5 1261,-903.5 1261,-909.5 1255,-915.5 1249,-915.5 1249,-915.5 866,-915.5 866,-915.5 860,-915.5 854,-909.5 854,-903.5 854,-903.5 854,-651.5 854,-651.5 854,-645.5 860,-639.5 866,-639.5"/>
<text text-anchor="middle" x="896" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="938,-639.5 938,-915.5 "/>
<text text-anchor="middle" x="948.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="959,-639.5 959,-915.5 "/>
<text text-anchor="middle" x="1099.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="959,-892.5 1240,-892.5 "/>
<text text-anchor="middle" x="1099.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="959,-869.5 1240,-869.5 "/>
<text text-anchor="middle" x="1099.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="959,-846.5 1240,-846.5 "/>
<text text-anchor="middle" x="1099.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="959,-823.5 1240,-823.5 "/>
<text text-anchor="middle" x="1099.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="959,-800.5 1240,-800.5 "/>
<text text-anchor="middle" x="1099.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="959,-777.5 1240,-777.5 "/>
<text text-anchor="middle" x="1099.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="959,-754.5 1240,-754.5 "/>
<text text-anchor="middle" x="1099.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="959,-731.5 1240,-731.5 "/>
<text text-anchor="middle" x="1099.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis_reference_source</text>
<polyline fill="none" stroke="#000000" points="959,-708.5 1240,-708.5 "/>
<text text-anchor="middle" x="1099.5" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="959,-685.5 1240,-685.5 "/>
<text text-anchor="middle" x="1099.5" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="959,-662.5 1240,-662.5 "/>
<text text-anchor="middle" x="1099.5" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="1240,-639.5 1240,-915.5 "/>
<text text-anchor="middle" x="1250.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1261.1431,-643.7749C1263.9397,-642.1628 1266.7263,-640.5704 1269.5,-639 1298.3279,-622.6788 1330.2947,-606.3949 1360.0965,-591.9402"/>
<polygon fill="#000000" stroke="#000000" points="1361.7839,-595.0122 1369.27,-587.515 1358.7425,-588.7075 1361.7839,-595.0122"/>
<text text-anchor="middle" x="1374" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge1" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1900.7003,-639.225C1874.2595,-580.1594 1845.4725,-509.7852 1825.5,-444 1801.19,-363.9282 1825.2994,-335.1017 1790.5,-259 1783.8157,-244.3823 1775.466,-229.9302 1766.2829,-216.0715"/>
<polygon fill="#000000" stroke="#000000" points="1768.9848,-213.8207 1760.4649,-207.523 1763.1979,-217.7593 1768.9848,-213.8207"/>
<text text-anchor="middle" x="1873" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1798.2904,-646.4935C1793.6967,-643.893 1789.0958,-641.3893 1784.5,-639 1761.3044,-626.941 1752.1031,-632.2405 1728.5,-621 1717.4816,-615.7527 1716.6289,-611.0085 1705.5,-606 1674.775,-592.1725 1640.424,-580.7061 1607.6765,-571.47"/>
<polygon fill="#000000" stroke="#000000" points="1608.602,-568.0946 1598.0306,-568.7999 1606.7344,-574.8409 1608.602,-568.0946"/>
<text text-anchor="middle" x="1765" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- therapeutic_procedure -->
<g id="node15" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M1291,-720C1291,-720 1648,-720 1648,-720 1654,-720 1660,-726 1660,-732 1660,-732 1660,-823 1660,-823 1660,-829 1654,-835 1648,-835 1648,-835 1291,-835 1291,-835 1285,-835 1279,-829 1279,-823 1279,-823 1279,-732 1279,-732 1279,-726 1285,-720 1291,-720"/>
<text text-anchor="middle" x="1369.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="1460,-720 1460,-835 "/>
<text text-anchor="middle" x="1470.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1481,-720 1481,-835 "/>
<text text-anchor="middle" x="1560" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="1481,-812 1639,-812 "/>
<text text-anchor="middle" x="1560" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="1481,-789 1639,-789 "/>
<text text-anchor="middle" x="1560" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1481,-766 1639,-766 "/>
<text text-anchor="middle" x="1560" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="1481,-743 1639,-743 "/>
<text text-anchor="middle" x="1560" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1639,-720 1639,-835 "/>
<text text-anchor="middle" x="1649.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1469.7446,-719.7679C1469.9021,-682.5975 1470.1058,-634.5208 1470.262,-597.6631"/>
<polygon fill="#000000" stroke="#000000" points="1473.7622,-597.5979 1470.3047,-587.5832 1466.7623,-597.5682 1473.7622,-597.5979"/>
<text text-anchor="middle" x="1563.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
</g>
</svg>
</div>
