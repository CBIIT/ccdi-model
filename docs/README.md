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
<svg width="3949pt" height="1758pt"
 viewBox="0.00 0.00 3948.50 1758.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1754)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1754 3944.5,-1754 3944.5,4 -4,4"/>
<!-- clinical_measure_file -->
<g id="node1" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M2028.5,-777.5C2028.5,-777.5 2380.5,-777.5 2380.5,-777.5 2386.5,-777.5 2392.5,-783.5 2392.5,-789.5 2392.5,-789.5 2392.5,-1018.5 2392.5,-1018.5 2392.5,-1024.5 2386.5,-1030.5 2380.5,-1030.5 2380.5,-1030.5 2028.5,-1030.5 2028.5,-1030.5 2022.5,-1030.5 2016.5,-1024.5 2016.5,-1018.5 2016.5,-1018.5 2016.5,-789.5 2016.5,-789.5 2016.5,-783.5 2022.5,-777.5 2028.5,-777.5"/>
<text text-anchor="middle" x="2100" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="2183.5,-777.5 2183.5,-1030.5 "/>
<text text-anchor="middle" x="2194" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2204.5,-777.5 2204.5,-1030.5 "/>
<text text-anchor="middle" x="2288" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2204.5,-1007.5 2371.5,-1007.5 "/>
<text text-anchor="middle" x="2288" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2204.5,-984.5 2371.5,-984.5 "/>
<text text-anchor="middle" x="2288" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2204.5,-961.5 2371.5,-961.5 "/>
<text text-anchor="middle" x="2288" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2204.5,-938.5 2371.5,-938.5 "/>
<text text-anchor="middle" x="2288" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2204.5,-915.5 2371.5,-915.5 "/>
<text text-anchor="middle" x="2288" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2204.5,-892.5 2371.5,-892.5 "/>
<text text-anchor="middle" x="2288" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2204.5,-869.5 2371.5,-869.5 "/>
<text text-anchor="middle" x="2288" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2204.5,-846.5 2371.5,-846.5 "/>
<text text-anchor="middle" x="2288" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2204.5,-823.5 2371.5,-823.5 "/>
<text text-anchor="middle" x="2288" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2204.5,-800.5 2371.5,-800.5 "/>
<text text-anchor="middle" x="2288" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="2371.5,-777.5 2371.5,-1030.5 "/>
<text text-anchor="middle" x="2382" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node9" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M2646.5,-.5C2646.5,-.5 3036.5,-.5 3036.5,-.5 3042.5,-.5 3048.5,-6.5 3048.5,-12.5 3048.5,-12.5 3048.5,-264.5 3048.5,-264.5 3048.5,-270.5 3042.5,-276.5 3036.5,-276.5 3036.5,-276.5 2646.5,-276.5 2646.5,-276.5 2640.5,-276.5 2634.5,-270.5 2634.5,-264.5 2634.5,-264.5 2634.5,-12.5 2634.5,-12.5 2634.5,-6.5 2640.5,-.5 2646.5,-.5"/>
<text text-anchor="middle" x="2662.5" y="-134.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="2690.5,-.5 2690.5,-276.5 "/>
<text text-anchor="middle" x="2701" y="-134.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2711.5,-.5 2711.5,-276.5 "/>
<text text-anchor="middle" x="2869.5" y="-261.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="2711.5,-253.5 3027.5,-253.5 "/>
<text text-anchor="middle" x="2869.5" y="-238.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="2711.5,-230.5 3027.5,-230.5 "/>
<text text-anchor="middle" x="2869.5" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_shorthand</text>
<polyline fill="none" stroke="#000000" points="2711.5,-207.5 3027.5,-207.5 "/>
<text text-anchor="middle" x="2869.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="2711.5,-184.5 3027.5,-184.5 "/>
<text text-anchor="middle" x="2869.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="2711.5,-161.5 3027.5,-161.5 "/>
<text text-anchor="middle" x="2869.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="2711.5,-138.5 3027.5,-138.5 "/>
<text text-anchor="middle" x="2869.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="2711.5,-115.5 3027.5,-115.5 "/>
<text text-anchor="middle" x="2869.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="2711.5,-92.5 3027.5,-92.5 "/>
<text text-anchor="middle" x="2869.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="2711.5,-69.5 3027.5,-69.5 "/>
<text text-anchor="middle" x="2869.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="2711.5,-46.5 3027.5,-46.5 "/>
<text text-anchor="middle" x="2869.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="2711.5,-23.5 3027.5,-23.5 "/>
<text text-anchor="middle" x="2869.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="3027.5,-.5 3027.5,-276.5 "/>
<text text-anchor="middle" x="3038" y="-134.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge14" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2083.0616,-777.3686C1978.5501,-652.762 1860.3139,-462.1892 1968.5,-328 2049.3397,-227.73 2392.7657,-177.8019 2624.0159,-155.0998"/>
<polygon fill="#000000" stroke="#000000" points="2624.639,-158.5559 2634.2537,-154.1053 2623.9622,-151.5887 2624.639,-158.5559"/>
<text text-anchor="middle" x="2020.5" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- participant -->
<g id="node19" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M2562.5,-541.5C2562.5,-541.5 2866.5,-541.5 2866.5,-541.5 2872.5,-541.5 2878.5,-547.5 2878.5,-553.5 2878.5,-553.5 2878.5,-644.5 2878.5,-644.5 2878.5,-650.5 2872.5,-656.5 2866.5,-656.5 2866.5,-656.5 2562.5,-656.5 2562.5,-656.5 2556.5,-656.5 2550.5,-650.5 2550.5,-644.5 2550.5,-644.5 2550.5,-553.5 2550.5,-553.5 2550.5,-547.5 2556.5,-541.5 2562.5,-541.5"/>
<text text-anchor="middle" x="2598.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="2646.5,-541.5 2646.5,-656.5 "/>
<text text-anchor="middle" x="2657" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2667.5,-541.5 2667.5,-656.5 "/>
<text text-anchor="middle" x="2762.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="2667.5,-633.5 2857.5,-633.5 "/>
<text text-anchor="middle" x="2762.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="2667.5,-610.5 2857.5,-610.5 "/>
<text text-anchor="middle" x="2762.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="2667.5,-587.5 2857.5,-587.5 "/>
<text text-anchor="middle" x="2762.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="2667.5,-564.5 2857.5,-564.5 "/>
<text text-anchor="middle" x="2762.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="2857.5,-541.5 2857.5,-656.5 "/>
<text text-anchor="middle" x="2868" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2176.3907,-777.3519C2175.3848,-740.5568 2182.3092,-702.8324 2206.5,-675 2228.6152,-649.5556 2401.8509,-627.6533 2539.961,-613.9864"/>
<polygon fill="#000000" stroke="#000000" points="2540.6502,-617.4357 2550.2607,-612.9759 2539.9667,-610.4691 2540.6502,-617.4357"/>
<text text-anchor="middle" x="2336" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- sequencing_file -->
<g id="node2" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M12,-1163C12,-1163 481,-1163 481,-1163 487,-1163 493,-1169 493,-1175 493,-1175 493,-1726 493,-1726 493,-1732 487,-1738 481,-1738 481,-1738 12,-1738 12,-1738 6,-1738 0,-1732 0,-1726 0,-1726 0,-1175 0,-1175 0,-1169 6,-1163 12,-1163"/>
<text text-anchor="middle" x="64" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="128,-1163 128,-1738 "/>
<text text-anchor="middle" x="138.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="149,-1163 149,-1738 "/>
<text text-anchor="middle" x="310.5" y="-1722.8" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="149,-1715 472,-1715 "/>
<text text-anchor="middle" x="310.5" y="-1699.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="149,-1692 472,-1692 "/>
<text text-anchor="middle" x="310.5" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="149,-1669 472,-1669 "/>
<text text-anchor="middle" x="310.5" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="149,-1646 472,-1646 "/>
<text text-anchor="middle" x="310.5" y="-1630.8" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="149,-1623 472,-1623 "/>
<text text-anchor="middle" x="310.5" y="-1607.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="149,-1600 472,-1600 "/>
<text text-anchor="middle" x="310.5" y="-1584.8" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="149,-1577 472,-1577 "/>
<text text-anchor="middle" x="310.5" y="-1561.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="149,-1554 472,-1554 "/>
<text text-anchor="middle" x="310.5" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="149,-1531 472,-1531 "/>
<text text-anchor="middle" x="310.5" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="149,-1508 472,-1508 "/>
<text text-anchor="middle" x="310.5" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="149,-1485 472,-1485 "/>
<text text-anchor="middle" x="310.5" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="149,-1462 472,-1462 "/>
<text text-anchor="middle" x="310.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="149,-1439 472,-1439 "/>
<text text-anchor="middle" x="310.5" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="149,-1416 472,-1416 "/>
<text text-anchor="middle" x="310.5" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="149,-1393 472,-1393 "/>
<text text-anchor="middle" x="310.5" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="149,-1370 472,-1370 "/>
<text text-anchor="middle" x="310.5" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="149,-1347 472,-1347 "/>
<text text-anchor="middle" x="310.5" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="149,-1324 472,-1324 "/>
<text text-anchor="middle" x="310.5" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="149,-1301 472,-1301 "/>
<text text-anchor="middle" x="310.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="149,-1278 472,-1278 "/>
<text text-anchor="middle" x="310.5" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="149,-1255 472,-1255 "/>
<text text-anchor="middle" x="310.5" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="149,-1232 472,-1232 "/>
<text text-anchor="middle" x="310.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="149,-1209 472,-1209 "/>
<text text-anchor="middle" x="310.5" y="-1193.8" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="149,-1186 472,-1186 "/>
<text text-anchor="middle" x="310.5" y="-1170.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="472,-1163 472,-1738 "/>
<text text-anchor="middle" x="482.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node7" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1671.5,-823.5C1671.5,-823.5 1985.5,-823.5 1985.5,-823.5 1991.5,-823.5 1997.5,-829.5 1997.5,-835.5 1997.5,-835.5 1997.5,-972.5 1997.5,-972.5 1997.5,-978.5 1991.5,-984.5 1985.5,-984.5 1985.5,-984.5 1671.5,-984.5 1671.5,-984.5 1665.5,-984.5 1659.5,-978.5 1659.5,-972.5 1659.5,-972.5 1659.5,-835.5 1659.5,-835.5 1659.5,-829.5 1665.5,-823.5 1671.5,-823.5"/>
<text text-anchor="middle" x="1693.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1727.5,-823.5 1727.5,-984.5 "/>
<text text-anchor="middle" x="1738" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1748.5,-823.5 1748.5,-984.5 "/>
<text text-anchor="middle" x="1862.5" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="1748.5,-961.5 1976.5,-961.5 "/>
<text text-anchor="middle" x="1862.5" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1748.5,-938.5 1976.5,-938.5 "/>
<text text-anchor="middle" x="1862.5" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1748.5,-915.5 1976.5,-915.5 "/>
<text text-anchor="middle" x="1862.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1748.5,-892.5 1976.5,-892.5 "/>
<text text-anchor="middle" x="1862.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1748.5,-869.5 1976.5,-869.5 "/>
<text text-anchor="middle" x="1862.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1748.5,-846.5 1976.5,-846.5 "/>
<text text-anchor="middle" x="1862.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="1976.5,-823.5 1976.5,-984.5 "/>
<text text-anchor="middle" x="1987" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M482.2646,-1162.9524C488.5855,-1158.7565 494.9988,-1154.7635 501.5,-1151 694.4804,-1039.2854 1333.8836,-957.1662 1649.3277,-922.3775"/>
<polygon fill="#000000" stroke="#000000" points="1649.9303,-925.8324 1659.4882,-921.261 1649.1656,-918.8743 1649.9303,-925.8324"/>
<text text-anchor="middle" x="624" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- therapeutic_procedure -->
<g id="node3" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M2594.5,-846.5C2594.5,-846.5 2986.5,-846.5 2986.5,-846.5 2992.5,-846.5 2998.5,-852.5 2998.5,-858.5 2998.5,-858.5 2998.5,-949.5 2998.5,-949.5 2998.5,-955.5 2992.5,-961.5 2986.5,-961.5 2986.5,-961.5 2594.5,-961.5 2594.5,-961.5 2588.5,-961.5 2582.5,-955.5 2582.5,-949.5 2582.5,-949.5 2582.5,-858.5 2582.5,-858.5 2582.5,-852.5 2588.5,-846.5 2594.5,-846.5"/>
<text text-anchor="middle" x="2673" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="2763.5,-846.5 2763.5,-961.5 "/>
<text text-anchor="middle" x="2774" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2784.5,-846.5 2784.5,-961.5 "/>
<text text-anchor="middle" x="2881" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment_start</text>
<polyline fill="none" stroke="#000000" points="2784.5,-938.5 2977.5,-938.5 "/>
<text text-anchor="middle" x="2881" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="2784.5,-915.5 2977.5,-915.5 "/>
<text text-anchor="middle" x="2881" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="2784.5,-892.5 2977.5,-892.5 "/>
<text text-anchor="middle" x="2881" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="2784.5,-869.5 2977.5,-869.5 "/>
<text text-anchor="middle" x="2881" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="2977.5,-846.5 2977.5,-961.5 "/>
<text text-anchor="middle" x="2988" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2776.1156,-846.2733C2763.3746,-795.1414 2744.7652,-720.4591 2731.3349,-666.5612"/>
<polygon fill="#000000" stroke="#000000" points="2734.7041,-665.6065 2728.89,-656.7495 2727.9118,-667.2991 2734.7041,-665.6065"/>
<text text-anchor="middle" x="2830.5" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- study_arm -->
<g id="node4" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M2339,-374.5C2339,-374.5 2636,-374.5 2636,-374.5 2642,-374.5 2648,-380.5 2648,-386.5 2648,-386.5 2648,-431.5 2648,-431.5 2648,-437.5 2642,-443.5 2636,-443.5 2636,-443.5 2339,-443.5 2339,-443.5 2333,-443.5 2327,-437.5 2327,-431.5 2327,-431.5 2327,-386.5 2327,-386.5 2327,-380.5 2333,-374.5 2339,-374.5"/>
<text text-anchor="middle" x="2373" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="2419,-374.5 2419,-443.5 "/>
<text text-anchor="middle" x="2429.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2440,-374.5 2440,-443.5 "/>
<text text-anchor="middle" x="2533.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="2440,-420.5 2627,-420.5 "/>
<text text-anchor="middle" x="2533.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="2440,-397.5 2627,-397.5 "/>
<text text-anchor="middle" x="2533.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="2627,-374.5 2627,-443.5 "/>
<text text-anchor="middle" x="2637.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge15" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2532.6939,-374.4662C2563.905,-350.6171 2607.7304,-317.129 2652.5811,-282.8575"/>
<polygon fill="#000000" stroke="#000000" points="2654.8476,-285.5305 2660.6683,-276.6779 2650.5974,-279.9685 2654.8476,-285.5305"/>
<text text-anchor="middle" x="2682" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- sample_diagnosis -->
<g id="node5" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M523,-1289.5C523,-1289.5 956,-1289.5 956,-1289.5 962,-1289.5 968,-1295.5 968,-1301.5 968,-1301.5 968,-1599.5 968,-1599.5 968,-1605.5 962,-1611.5 956,-1611.5 956,-1611.5 523,-1611.5 523,-1611.5 517,-1611.5 511,-1605.5 511,-1599.5 511,-1599.5 511,-1301.5 511,-1301.5 511,-1295.5 517,-1289.5 523,-1289.5"/>
<text text-anchor="middle" x="582.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="654,-1289.5 654,-1611.5 "/>
<text text-anchor="middle" x="664.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="675,-1289.5 675,-1611.5 "/>
<text text-anchor="middle" x="811" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="675,-1588.5 947,-1588.5 "/>
<text text-anchor="middle" x="811" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="675,-1565.5 947,-1565.5 "/>
<text text-anchor="middle" x="811" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="675,-1542.5 947,-1542.5 "/>
<text text-anchor="middle" x="811" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="675,-1519.5 947,-1519.5 "/>
<text text-anchor="middle" x="811" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="675,-1496.5 947,-1496.5 "/>
<text text-anchor="middle" x="811" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="675,-1473.5 947,-1473.5 "/>
<text text-anchor="middle" x="811" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="675,-1450.5 947,-1450.5 "/>
<text text-anchor="middle" x="811" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="675,-1427.5 947,-1427.5 "/>
<text text-anchor="middle" x="811" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="675,-1404.5 947,-1404.5 "/>
<text text-anchor="middle" x="811" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="675,-1381.5 947,-1381.5 "/>
<text text-anchor="middle" x="811" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="675,-1358.5 947,-1358.5 "/>
<text text-anchor="middle" x="811" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="675,-1335.5 947,-1335.5 "/>
<text text-anchor="middle" x="811" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="675,-1312.5 947,-1312.5 "/>
<text text-anchor="middle" x="811" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="947,-1289.5 947,-1611.5 "/>
<text text-anchor="middle" x="957.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M838.1394,-1289.3229C875.923,-1238.8336 922.9816,-1186.971 976.5,-1151 1182.4927,-1012.5474 1466.7831,-950.5269 1649.1529,-923.5757"/>
<polygon fill="#000000" stroke="#000000" points="1649.7239,-927.0295 1659.1144,-922.1234 1648.7141,-920.1027 1649.7239,-927.0295"/>
<text text-anchor="middle" x="1091.5" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
<!-- study_personnel -->
<g id="node6" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M1990,-351.5C1990,-351.5 2297,-351.5 2297,-351.5 2303,-351.5 2309,-357.5 2309,-363.5 2309,-363.5 2309,-454.5 2309,-454.5 2309,-460.5 2303,-466.5 2297,-466.5 2297,-466.5 1990,-466.5 1990,-466.5 1984,-466.5 1978,-460.5 1978,-454.5 1978,-454.5 1978,-363.5 1978,-363.5 1978,-357.5 1984,-351.5 1990,-351.5"/>
<text text-anchor="middle" x="2045" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="2112,-351.5 2112,-466.5 "/>
<text text-anchor="middle" x="2122.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2133,-351.5 2133,-466.5 "/>
<text text-anchor="middle" x="2210.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="2133,-443.5 2288,-443.5 "/>
<text text-anchor="middle" x="2210.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="2133,-420.5 2288,-420.5 "/>
<text text-anchor="middle" x="2210.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="2133,-397.5 2288,-397.5 "/>
<text text-anchor="middle" x="2210.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="2133,-374.5 2288,-374.5 "/>
<text text-anchor="middle" x="2210.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="2288,-351.5 2288,-466.5 "/>
<text text-anchor="middle" x="2298.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge18" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2263.6354,-351.3916C2281.578,-343.2787 2299.9429,-335.2446 2317.5,-328 2417.3487,-286.7996 2529.7807,-245.4895 2624.8246,-212.0032"/>
<polygon fill="#000000" stroke="#000000" points="2625.9884,-215.3041 2634.2605,-208.6843 2623.6657,-208.7007 2625.9884,-215.3041"/>
<text text-anchor="middle" x="2458" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge11" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1817.0636,-823.36C1804.4737,-700.6621 1800.0582,-466.7376 1922.5,-328 2013.2715,-225.1478 2382.3512,-175.6079 2624.2706,-153.749"/>
<polygon fill="#000000" stroke="#000000" points="2624.6078,-157.233 2634.2562,-152.856 2623.9841,-150.2608 2624.6078,-157.233"/>
<text text-anchor="middle" x="1870" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1885.4935,-823.1163C1917.289,-783.3327 1960.0205,-737.6759 2007.5,-708 2093.9351,-653.9759 2360.1987,-624.4183 2540.1428,-610.1628"/>
<polygon fill="#000000" stroke="#000000" points="2540.5582,-613.6411 2550.2542,-609.3706 2540.0114,-606.6624 2540.5582,-613.6411"/>
<text text-anchor="middle" x="2124" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_admin -->
<g id="node8" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M2678.5,-328.5C2678.5,-328.5 3004.5,-328.5 3004.5,-328.5 3010.5,-328.5 3016.5,-334.5 3016.5,-340.5 3016.5,-340.5 3016.5,-477.5 3016.5,-477.5 3016.5,-483.5 3010.5,-489.5 3004.5,-489.5 3004.5,-489.5 2678.5,-489.5 2678.5,-489.5 2672.5,-489.5 2666.5,-483.5 2666.5,-477.5 2666.5,-477.5 2666.5,-340.5 2666.5,-340.5 2666.5,-334.5 2672.5,-328.5 2678.5,-328.5"/>
<text text-anchor="middle" x="2720.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="2774.5,-328.5 2774.5,-489.5 "/>
<text text-anchor="middle" x="2785" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2795.5,-328.5 2795.5,-489.5 "/>
<text text-anchor="middle" x="2895.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="2795.5,-466.5 2995.5,-466.5 "/>
<text text-anchor="middle" x="2895.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="2795.5,-443.5 2995.5,-443.5 "/>
<text text-anchor="middle" x="2895.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="2795.5,-420.5 2995.5,-420.5 "/>
<text text-anchor="middle" x="2895.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="2795.5,-397.5 2995.5,-397.5 "/>
<text text-anchor="middle" x="2895.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="2795.5,-374.5 2995.5,-374.5 "/>
<text text-anchor="middle" x="2895.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="2795.5,-351.5 2995.5,-351.5 "/>
<text text-anchor="middle" x="2895.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="2995.5,-328.5 2995.5,-489.5 "/>
<text text-anchor="middle" x="3006" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge17" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2841.5,-328.2075C2841.5,-315.0539 2841.5,-301.0753 2841.5,-286.9023"/>
<polygon fill="#000000" stroke="#000000" points="2845.0001,-286.5567 2841.5,-276.5568 2838.0001,-286.5568 2845.0001,-286.5567"/>
<text text-anchor="middle" x="2898" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- study_funding -->
<g id="node10" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M3047,-374.5C3047,-374.5 3426,-374.5 3426,-374.5 3432,-374.5 3438,-380.5 3438,-386.5 3438,-386.5 3438,-431.5 3438,-431.5 3438,-437.5 3432,-443.5 3426,-443.5 3426,-443.5 3047,-443.5 3047,-443.5 3041,-443.5 3035,-437.5 3035,-431.5 3035,-431.5 3035,-386.5 3035,-386.5 3035,-380.5 3041,-374.5 3047,-374.5"/>
<text text-anchor="middle" x="3094.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="3154,-374.5 3154,-443.5 "/>
<text text-anchor="middle" x="3164.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3175,-374.5 3175,-443.5 "/>
<text text-anchor="middle" x="3296" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="3175,-420.5 3417,-420.5 "/>
<text text-anchor="middle" x="3296" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="3175,-397.5 3417,-397.5 "/>
<text text-anchor="middle" x="3296" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="3417,-374.5 3417,-443.5 "/>
<text text-anchor="middle" x="3427.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge23" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3186.0718,-374.4662C3151.1016,-350.5183 3101.9394,-316.8515 3051.6776,-282.4318"/>
<polygon fill="#000000" stroke="#000000" points="3053.5038,-279.4403 3043.2755,-276.6779 3049.5486,-285.2159 3053.5038,-279.4403"/>
<text text-anchor="middle" x="3147.5" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- methylation_array_file -->
<g id="node11" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M998,-1335.5C998,-1335.5 1365,-1335.5 1365,-1335.5 1371,-1335.5 1377,-1341.5 1377,-1347.5 1377,-1347.5 1377,-1553.5 1377,-1553.5 1377,-1559.5 1371,-1565.5 1365,-1565.5 1365,-1565.5 998,-1565.5 998,-1565.5 992,-1565.5 986,-1559.5 986,-1553.5 986,-1553.5 986,-1347.5 986,-1347.5 986,-1341.5 992,-1335.5 998,-1335.5"/>
<text text-anchor="middle" x="1075" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="1164,-1335.5 1164,-1565.5 "/>
<text text-anchor="middle" x="1174.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1185,-1335.5 1185,-1565.5 "/>
<text text-anchor="middle" x="1270.5" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1185,-1542.5 1356,-1542.5 "/>
<text text-anchor="middle" x="1270.5" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1185,-1519.5 1356,-1519.5 "/>
<text text-anchor="middle" x="1270.5" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1185,-1496.5 1356,-1496.5 "/>
<text text-anchor="middle" x="1270.5" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1185,-1473.5 1356,-1473.5 "/>
<text text-anchor="middle" x="1270.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1185,-1450.5 1356,-1450.5 "/>
<text text-anchor="middle" x="1270.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1185,-1427.5 1356,-1427.5 "/>
<text text-anchor="middle" x="1270.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1185,-1404.5 1356,-1404.5 "/>
<text text-anchor="middle" x="1270.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1185,-1381.5 1356,-1381.5 "/>
<text text-anchor="middle" x="1270.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="1185,-1358.5 1356,-1358.5 "/>
<text text-anchor="middle" x="1270.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="1356,-1335.5 1356,-1565.5 "/>
<text text-anchor="middle" x="1366.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1243.0042,-1335.3936C1279.1069,-1275.3137 1328.9218,-1203.5824 1386.5,-1151 1463.6892,-1080.5081 1564.5403,-1022.2088 1650.4149,-979.9852"/>
<polygon fill="#000000" stroke="#000000" points="1652.0229,-983.0951 1659.474,-975.563 1648.9522,-976.8045 1652.0229,-983.0951"/>
<text text-anchor="middle" x="1510" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- diagnosis -->
<g id="node12" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M3028.5,-708.5C3028.5,-708.5 3402.5,-708.5 3402.5,-708.5 3408.5,-708.5 3414.5,-714.5 3414.5,-720.5 3414.5,-720.5 3414.5,-1087.5 3414.5,-1087.5 3414.5,-1093.5 3408.5,-1099.5 3402.5,-1099.5 3402.5,-1099.5 3028.5,-1099.5 3028.5,-1099.5 3022.5,-1099.5 3016.5,-1093.5 3016.5,-1087.5 3016.5,-1087.5 3016.5,-720.5 3016.5,-720.5 3016.5,-714.5 3022.5,-708.5 3028.5,-708.5"/>
<text text-anchor="middle" x="3058.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="3100.5,-708.5 3100.5,-1099.5 "/>
<text text-anchor="middle" x="3111" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3121.5,-708.5 3121.5,-1099.5 "/>
<text text-anchor="middle" x="3257.5" y="-1084.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="3121.5,-1076.5 3393.5,-1076.5 "/>
<text text-anchor="middle" x="3257.5" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="3121.5,-1053.5 3393.5,-1053.5 "/>
<text text-anchor="middle" x="3257.5" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="3121.5,-1030.5 3393.5,-1030.5 "/>
<text text-anchor="middle" x="3257.5" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="3121.5,-1007.5 3393.5,-1007.5 "/>
<text text-anchor="middle" x="3257.5" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="3121.5,-984.5 3393.5,-984.5 "/>
<text text-anchor="middle" x="3257.5" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="3121.5,-961.5 3393.5,-961.5 "/>
<text text-anchor="middle" x="3257.5" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="3121.5,-938.5 3393.5,-938.5 "/>
<text text-anchor="middle" x="3257.5" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="3121.5,-915.5 3393.5,-915.5 "/>
<text text-anchor="middle" x="3257.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="3121.5,-892.5 3393.5,-892.5 "/>
<text text-anchor="middle" x="3257.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="3121.5,-869.5 3393.5,-869.5 "/>
<text text-anchor="middle" x="3257.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="3121.5,-846.5 3393.5,-846.5 "/>
<text text-anchor="middle" x="3257.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="3121.5,-823.5 3393.5,-823.5 "/>
<text text-anchor="middle" x="3257.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="3121.5,-800.5 3393.5,-800.5 "/>
<text text-anchor="middle" x="3257.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="3121.5,-777.5 3393.5,-777.5 "/>
<text text-anchor="middle" x="3257.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="3121.5,-754.5 3393.5,-754.5 "/>
<text text-anchor="middle" x="3257.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="3121.5,-731.5 3393.5,-731.5 "/>
<text text-anchor="middle" x="3257.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="3393.5,-708.5 3393.5,-1099.5 "/>
<text text-anchor="middle" x="3404" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3016.2387,-713.7799C3013.3311,-711.8123 3010.4176,-709.8844 3007.5,-708 2971.1248,-684.5062 2928.9633,-665.0692 2888.1553,-649.4422"/>
<polygon fill="#000000" stroke="#000000" points="2889.2391,-646.1104 2878.6472,-645.8597 2886.7709,-652.6608 2889.2391,-646.1104"/>
<text text-anchor="middle" x="3016" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- imaging_file -->
<g id="node13" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M1407.5,-1289.5C1407.5,-1289.5 1741.5,-1289.5 1741.5,-1289.5 1747.5,-1289.5 1753.5,-1295.5 1753.5,-1301.5 1753.5,-1301.5 1753.5,-1599.5 1753.5,-1599.5 1753.5,-1605.5 1747.5,-1611.5 1741.5,-1611.5 1741.5,-1611.5 1407.5,-1611.5 1407.5,-1611.5 1401.5,-1611.5 1395.5,-1605.5 1395.5,-1599.5 1395.5,-1599.5 1395.5,-1301.5 1395.5,-1301.5 1395.5,-1295.5 1401.5,-1289.5 1407.5,-1289.5"/>
<text text-anchor="middle" x="1447.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="1499.5,-1289.5 1499.5,-1611.5 "/>
<text text-anchor="middle" x="1510" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1520.5,-1289.5 1520.5,-1611.5 "/>
<text text-anchor="middle" x="1626.5" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1520.5,-1588.5 1732.5,-1588.5 "/>
<text text-anchor="middle" x="1626.5" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1520.5,-1565.5 1732.5,-1565.5 "/>
<text text-anchor="middle" x="1626.5" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1520.5,-1542.5 1732.5,-1542.5 "/>
<text text-anchor="middle" x="1626.5" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1520.5,-1519.5 1732.5,-1519.5 "/>
<text text-anchor="middle" x="1626.5" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1520.5,-1496.5 1732.5,-1496.5 "/>
<text text-anchor="middle" x="1626.5" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1520.5,-1473.5 1732.5,-1473.5 "/>
<text text-anchor="middle" x="1626.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1520.5,-1450.5 1732.5,-1450.5 "/>
<text text-anchor="middle" x="1626.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1520.5,-1427.5 1732.5,-1427.5 "/>
<text text-anchor="middle" x="1626.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1520.5,-1404.5 1732.5,-1404.5 "/>
<text text-anchor="middle" x="1626.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="1520.5,-1381.5 1732.5,-1381.5 "/>
<text text-anchor="middle" x="1626.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="1520.5,-1358.5 1732.5,-1358.5 "/>
<text text-anchor="middle" x="1626.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="1520.5,-1335.5 1732.5,-1335.5 "/>
<text text-anchor="middle" x="1626.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1520.5,-1312.5 1732.5,-1312.5 "/>
<text text-anchor="middle" x="1626.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="1732.5,-1289.5 1732.5,-1611.5 "/>
<text text-anchor="middle" x="1743" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1649.3346,-1289.4878C1694.2128,-1192.9289 1749.6099,-1073.738 1786.8229,-993.6714"/>
<polygon fill="#000000" stroke="#000000" points="1790.0019,-995.1356 1791.0428,-984.592 1783.654,-992.1853 1790.0019,-995.1356"/>
<text text-anchor="middle" x="1779" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- synonym -->
<g id="node14" class="node">
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
<g id="edge21" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2951.2407,-1427.1887C2936.6247,-1368.5287 2889.484,-1214.9352 2784.5,-1151 2746.1231,-1127.6285 2425.0306,-1139.0031 2380.5,-1133 2350.6883,-1128.9811 2344.2828,-1122.2281 2314.5,-1118 2246.839,-1108.3946 2069.1947,-1129.3946 2007.5,-1100 1958.2599,-1076.5394 1916.2883,-1032.8756 1885.3897,-992.705"/>
<polygon fill="#000000" stroke="#000000" points="1888.1803,-990.5924 1879.3588,-984.7245 1882.5956,-994.8128 1888.1803,-990.5924"/>
<text text-anchor="middle" x="2423" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge20" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3119.3459,-1435.4612C3322.5596,-1407.2859 3664.1567,-1327.0223 3835.5,-1100 3888.2499,-1030.1086 3855.5,-991.5635 3855.5,-904 3855.5,-904 3855.5,-904 3855.5,-409 3855.5,-372.0229 3863.1927,-353.5893 3836.5,-328 3727.5579,-223.5613 3317.4005,-173.982 3058.9241,-152.6477"/>
<polygon fill="#000000" stroke="#000000" points="3058.8988,-149.1341 3048.6469,-151.8077 3058.3285,-156.1108 3058.8988,-149.1341"/>
<text text-anchor="middle" x="3898" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2950.5026,-1427.1226C2934.4505,-1369.6551 2884.7556,-1221.0793 2784.5,-1151 2675.0864,-1074.5192 2574.5081,-1202.0943 2488.5,-1100 2376.2514,-966.7573 2395.8517,-855.5455 2488.5,-708 2501.8439,-686.7494 2520.6253,-669.5434 2541.7216,-655.6377"/>
<polygon fill="#000000" stroke="#000000" points="2543.6424,-658.5643 2550.2379,-650.2727 2539.9112,-652.6416 2543.6424,-658.5643"/>
<text text-anchor="middle" x="2531" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- pdx -->
<g id="node15" class="node">
<title>pdx</title>
<path fill="none" stroke="#000000" d="M1784,-1347C1784,-1347 2113,-1347 2113,-1347 2119,-1347 2125,-1353 2125,-1359 2125,-1359 2125,-1542 2125,-1542 2125,-1548 2119,-1554 2113,-1554 2113,-1554 1784,-1554 1784,-1554 1778,-1554 1772,-1548 1772,-1542 1772,-1542 1772,-1359 1772,-1359 1772,-1353 1778,-1347 1784,-1347"/>
<text text-anchor="middle" x="1793.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
<polyline fill="none" stroke="#000000" points="1815,-1347 1815,-1554 "/>
<text text-anchor="middle" x="1825.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1836,-1347 1836,-1554 "/>
<text text-anchor="middle" x="1970" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_site</text>
<polyline fill="none" stroke="#000000" points="1836,-1531 2104,-1531 "/>
<text text-anchor="middle" x="1970" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_type</text>
<polyline fill="none" stroke="#000000" points="1836,-1508 2104,-1508 "/>
<text text-anchor="middle" x="1970" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">model_id</text>
<polyline fill="none" stroke="#000000" points="1836,-1485 2104,-1485 "/>
<text text-anchor="middle" x="1970" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">mouse_strain</text>
<polyline fill="none" stroke="#000000" points="1836,-1462 2104,-1462 "/>
<text text-anchor="middle" x="1970" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">strain_immune_system_humanized</text>
<polyline fill="none" stroke="#000000" points="1836,-1439 2104,-1439 "/>
<text text-anchor="middle" x="1970" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_characterization_method</text>
<polyline fill="none" stroke="#000000" points="1836,-1416 2104,-1416 "/>
<text text-anchor="middle" x="1970" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_not_mus_or_ebv_origin</text>
<polyline fill="none" stroke="#000000" points="1836,-1393 2104,-1393 "/>
<text text-anchor="middle" x="1970" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_preparation</text>
<polyline fill="none" stroke="#000000" points="1836,-1370 2104,-1370 "/>
<text text-anchor="middle" x="1970" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_humanization</text>
<polyline fill="none" stroke="#000000" points="2104,-1347 2104,-1554 "/>
<text text-anchor="middle" x="2114.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1925.7172,-1346.7433C1903.3731,-1244.9846 1869.6483,-1091.3963 1848.3658,-994.472"/>
<polygon fill="#000000" stroke="#000000" points="1851.7813,-993.7074 1846.218,-984.6908 1844.9442,-995.2087 1851.7813,-993.7074"/>
<text text-anchor="middle" x="1902.5" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- family_relationship -->
<g id="node16" class="node">
<title>family_relationship</title>
<path fill="none" stroke="#000000" d="M3445,-869.5C3445,-869.5 3814,-869.5 3814,-869.5 3820,-869.5 3826,-875.5 3826,-881.5 3826,-881.5 3826,-926.5 3826,-926.5 3826,-932.5 3820,-938.5 3814,-938.5 3814,-938.5 3445,-938.5 3445,-938.5 3439,-938.5 3433,-932.5 3433,-926.5 3433,-926.5 3433,-881.5 3433,-881.5 3433,-875.5 3439,-869.5 3445,-869.5"/>
<text text-anchor="middle" x="3510" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
<polyline fill="none" stroke="#000000" points="3587,-869.5 3587,-938.5 "/>
<text text-anchor="middle" x="3597.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3608,-869.5 3608,-938.5 "/>
<text text-anchor="middle" x="3706.5" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_id</text>
<polyline fill="none" stroke="#000000" points="3608,-915.5 3805,-915.5 "/>
<text text-anchor="middle" x="3706.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">related_to_participant_id</text>
<polyline fill="none" stroke="#000000" points="3608,-892.5 3805,-892.5 "/>
<text text-anchor="middle" x="3706.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">relationship</text>
<polyline fill="none" stroke="#000000" points="3805,-869.5 3805,-938.5 "/>
<text text-anchor="middle" x="3815.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3604.2701,-869.3763C3569.2207,-824.1347 3501.2635,-746.1929 3423.5,-708 3331.9624,-663.0421 3067.36,-630.9958 2888.5986,-613.7414"/>
<polygon fill="#000000" stroke="#000000" points="2888.842,-610.2488 2878.5537,-612.7787 2888.1741,-617.2168 2888.842,-610.2488"/>
<text text-anchor="middle" x="3448" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- publication -->
<g id="node17" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M3605.5,-391C3605.5,-391 3815.5,-391 3815.5,-391 3821.5,-391 3827.5,-397 3827.5,-403 3827.5,-403 3827.5,-415 3827.5,-415 3827.5,-421 3821.5,-427 3815.5,-427 3815.5,-427 3605.5,-427 3605.5,-427 3599.5,-427 3593.5,-421 3593.5,-415 3593.5,-415 3593.5,-403 3593.5,-403 3593.5,-397 3599.5,-391 3605.5,-391"/>
<text text-anchor="middle" x="3642" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="3690.5,-391 3690.5,-427 "/>
<text text-anchor="middle" x="3701" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3711.5,-391 3711.5,-427 "/>
<text text-anchor="middle" x="3759" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="3806.5,-391 3806.5,-427 "/>
<text text-anchor="middle" x="3817" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge6" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3684.812,-390.9041C3659.034,-373.2847 3617.7678,-346.5249 3579.5,-328 3540.7769,-309.2547 3529.693,-307.4096 3488.5,-295 3346.8199,-252.3182 3185.0141,-213.1822 3058.6562,-184.7222"/>
<polygon fill="#000000" stroke="#000000" points="3059.3777,-181.2972 3048.8537,-182.5198 3057.8431,-188.1269 3059.3777,-181.2972"/>
<text text-anchor="middle" x="3586.5" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node18" class="node">
<title>single_cell_sequencing_file</title>
<path fill="none" stroke="#000000" d="M2155,-1151.5C2155,-1151.5 2764,-1151.5 2764,-1151.5 2770,-1151.5 2776,-1157.5 2776,-1163.5 2776,-1163.5 2776,-1737.5 2776,-1737.5 2776,-1743.5 2770,-1749.5 2764,-1749.5 2764,-1749.5 2155,-1749.5 2155,-1749.5 2149,-1749.5 2143,-1743.5 2143,-1737.5 2143,-1737.5 2143,-1163.5 2143,-1163.5 2143,-1157.5 2149,-1151.5 2155,-1151.5"/>
<text text-anchor="middle" x="2249" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
<polyline fill="none" stroke="#000000" points="2355,-1151.5 2355,-1749.5 "/>
<text text-anchor="middle" x="2365.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2376,-1151.5 2376,-1749.5 "/>
<text text-anchor="middle" x="2565.5" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">Cell_Barcode</text>
<polyline fill="none" stroke="#000000" points="2376,-1726.5 2755,-1726.5 "/>
<text text-anchor="middle" x="2565.5" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">Cryopreserved_Cells_in_Sample</text>
<polyline fill="none" stroke="#000000" points="2376,-1703.5 2755,-1703.5 "/>
<text text-anchor="middle" x="2565.5" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">Dissociation_Method</text>
<polyline fill="none" stroke="#000000" points="2376,-1680.5 2755,-1680.5 "/>
<text text-anchor="middle" x="2565.5" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">End_Bias</text>
<polyline fill="none" stroke="#000000" points="2376,-1657.5 2755,-1657.5 "/>
<text text-anchor="middle" x="2565.5" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">Input_Cells_and_Nuclei</text>
<polyline fill="none" stroke="#000000" points="2376,-1634.5 2755,-1634.5 "/>
<text text-anchor="middle" x="2565.5" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">Library_Construction_Method</text>
<polyline fill="none" stroke="#000000" points="2376,-1611.5 2755,-1611.5 "/>
<text text-anchor="middle" x="2565.5" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">Library_Preparation_Date</text>
<polyline fill="none" stroke="#000000" points="2376,-1588.5 2755,-1588.5 "/>
<text text-anchor="middle" x="2565.5" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">Nucleic_Acid_Capture_Date</text>
<polyline fill="none" stroke="#000000" points="2376,-1565.5 2755,-1565.5 "/>
<text text-anchor="middle" x="2565.5" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">Paired_End</text>
<polyline fill="none" stroke="#000000" points="2376,-1542.5 2755,-1542.5 "/>
<text text-anchor="middle" x="2565.5" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">Protocols_Link</text>
<polyline fill="none" stroke="#000000" points="2376,-1519.5 2755,-1519.5 "/>
<text text-anchor="middle" x="2565.5" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">Read1</text>
<polyline fill="none" stroke="#000000" points="2376,-1496.5 2755,-1496.5 "/>
<text text-anchor="middle" x="2565.5" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">Read2</text>
<polyline fill="none" stroke="#000000" points="2376,-1473.5 2755,-1473.5 "/>
<text text-anchor="middle" x="2565.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Feature_barcoding</text>
<polyline fill="none" stroke="#000000" points="2376,-1450.5 2755,-1450.5 "/>
<text text-anchor="middle" x="2565.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Oligo_dT_Poly_dT</text>
<polyline fill="none" stroke="#000000" points="2376,-1427.5 2755,-1427.5 "/>
<text text-anchor="middle" x="2565.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Random</text>
<polyline fill="none" stroke="#000000" points="2376,-1404.5 2755,-1404.5 "/>
<text text-anchor="middle" x="2565.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">Sequencing_Library_Construction_Date</text>
<polyline fill="none" stroke="#000000" points="2376,-1381.5 2755,-1381.5 "/>
<text text-anchor="middle" x="2565.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">Single_Cell_Dissociation_Date</text>
<polyline fill="none" stroke="#000000" points="2376,-1358.5 2755,-1358.5 "/>
<text text-anchor="middle" x="2565.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">Single_Cell_Isolation_Method</text>
<polyline fill="none" stroke="#000000" points="2376,-1335.5 2755,-1335.5 "/>
<text text-anchor="middle" x="2565.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">Spike_In</text>
<polyline fill="none" stroke="#000000" points="2376,-1312.5 2755,-1312.5 "/>
<text text-anchor="middle" x="2565.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">Total_Number_of_Input_Cells</text>
<polyline fill="none" stroke="#000000" points="2376,-1289.5 2755,-1289.5 "/>
<text text-anchor="middle" x="2565.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">UMI</text>
<polyline fill="none" stroke="#000000" points="2376,-1266.5 2755,-1266.5 "/>
<text text-anchor="middle" x="2565.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="2376,-1243.5 2755,-1243.5 "/>
<text text-anchor="middle" x="2565.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">cDNA_Length</text>
<polyline fill="none" stroke="#000000" points="2376,-1220.5 2755,-1220.5 "/>
<text text-anchor="middle" x="2565.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">cDNA_Offset</text>
<polyline fill="none" stroke="#000000" points="2376,-1197.5 2755,-1197.5 "/>
<text text-anchor="middle" x="2565.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2376,-1174.5 2755,-1174.5 "/>
<text text-anchor="middle" x="2565.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 23 properties</text>
<polyline fill="none" stroke="#000000" points="2755,-1151.5 2755,-1749.5 "/>
<text text-anchor="middle" x="2765.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2142.749,-1156.9434C2139.6689,-1154.9328 2136.5856,-1152.951 2133.5,-1151 2082.4378,-1118.7134 2057.0988,-1134.4925 2007.5,-1100 1965.2911,-1070.6467 1925.8757,-1029.6532 1894.8352,-992.7399"/>
<polygon fill="#000000" stroke="#000000" points="1897.4258,-990.3813 1888.3406,-984.9306 1892.0438,-994.8572 1897.4258,-990.3813"/>
<text text-anchor="middle" x="2202" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge5" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M2645.7765,-541.4781C2610.6496,-512.0768 2568.7083,-476.9717 2536.8278,-450.2876"/>
<polygon fill="#000000" stroke="#000000" points="2538.8645,-447.4281 2528.9496,-443.6935 2534.3716,-452.7959 2538.8645,-447.4281"/>
<text text-anchor="middle" x="2672" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge4" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2878.9273,-585.8161C3083.586,-567.7094 3410.8475,-532.5059 3447.5,-490 3494.5186,-435.4725 3490.1428,-386.0137 3447.5,-328 3400.266,-263.7402 3212.8223,-211.5814 3058.7598,-178.3738"/>
<polygon fill="#000000" stroke="#000000" points="3059.173,-174.8831 3048.6621,-176.214 3057.7088,-181.7283 3059.173,-174.8831"/>
<text text-anchor="middle" x="3531" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
</g>
</svg>
</div>
